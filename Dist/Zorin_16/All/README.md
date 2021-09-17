Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=zorin-16

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 15-3568              | Notebook    | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b3a1acb0f6](https://linux-hardware.org/?probe=b3a1acb0f6) | Sep 17, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [b7fe3ed969](https://linux-hardware.org/?probe=b7fe3ed969) | Sep 17, 2021 |
| Dell          | Latitude E5470              | Notebook    | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | Notebook    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | Notebook    | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | Notebook    | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | Notebook    | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | Notebook    | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | Notebook    | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| Acer          | One S1003                   | Tablet      | [e021ddcbf1](https://linux-hardware.org/?probe=e021ddcbf1) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| Intel         | X99                         | Desktop     | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| NCR           | Talladega                   | Desktop     | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | Desktop     | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [68ad9fb8e9](https://linux-hardware.org/?probe=68ad9fb8e9) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| Dell          | Latitude E5470              | Notebook    | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | Notebook    | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Acer          | One S1003                   | Tablet      | [a049a2a4d3](https://linux-hardware.org/?probe=a049a2a4d3) | Sep 13, 2021 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [d4a19b90eb](https://linux-hardware.org/?probe=d4a19b90eb) | Sep 13, 2021 |
| ASUSTek       | Benicia                     | Desktop     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | Notebook    | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| HP            | 339A                        | Desktop     | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| Dell          | Latitude E6430              | Notebook    | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | Notebook    | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | Notebook    | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | Notebook    | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | Desktop     | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | Desktop     | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | Desktop     | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| Dell          | XPS M1330                   | Notebook    | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | Notebook    | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | Notebook    | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | Notebook    | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | Notebook    | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | Notebook    | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | Notebook    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [15f063a517](https://linux-hardware.org/?probe=15f063a517) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [5b8b652e27](https://linux-hardware.org/?probe=5b8b652e27) | Sep 09, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [e3e702ab7b](https://linux-hardware.org/?probe=e3e702ab7b) | Sep 09, 2021 |
| HP            | 2187 A01                    | Desktop     | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | Notebook    | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | Notebook    | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | Notebook    | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| RCA           | W101-CS                     | Tablet      | [7ba24072d5](https://linux-hardware.org/?probe=7ba24072d5) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | Notebook    | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Acer          | V5-171                      | Notebook    | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | Notebook    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | Notebook    | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | Notebook    | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | Notebook    | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | Notebook    | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | Desktop     | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | Desktop     | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| HP            | Pavilion dv5                | Notebook    | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | Notebook    | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [879a8ee9da](https://linux-hardware.org/?probe=879a8ee9da) | Sep 05, 2021 |
| Acer          | One S1003                   | Tablet      | [e5d901c7a5](https://linux-hardware.org/?probe=e5d901c7a5) | Sep 05, 2021 |
| MSI           | IONA                        | Desktop     | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [ff8f35986b](https://linux-hardware.org/?probe=ff8f35986b) | Sep 04, 2021 |
| MSI           | IONA                        | Desktop     | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | Desktop     | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| HP            | 2B4B                        | Desktop     | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | Desktop     | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | Notebook    | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| ASUSTek       | GR8                         | Notebook    | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | Notebook    | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | Notebook    | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | Notebook    | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | Notebook    | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | 1497                        | Desktop     | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Intel         | NUC7JYB J67969-404          | Mini pc     | [3c88709f8a](https://linux-hardware.org/?probe=3c88709f8a) | Sep 01, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | Notebook    | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | 339A                        | Desktop     | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | Desktop     | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| HP            | Pavilion 15                 | Notebook    | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | Desktop     | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | Notebook    | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | Notebook    | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| MSI           | Z87-G43                     | Desktop     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | Notebook    | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | Notebook    | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | Desktop     | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [c59a1fff0d](https://linux-hardware.org/?probe=c59a1fff0d) | Aug 26, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [accc3b9ebb](https://linux-hardware.org/?probe=accc3b9ebb) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| Acer          | AO722                       | Notebook    | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| HP            | 802E                        | Desktop     | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| TianBei       | TB-H7                       | Notebook    | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| Dell          | 0TP406                      | Desktop     | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | Desktop     | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | Notebook    | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | Notebook    | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| Acer          | Aspire 8940G                | Notebook    | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | Notebook    | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [8eed93b589](https://linux-hardware.org/?probe=8eed93b589) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Board                       | Desktop     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Board                       | Desktop     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | Notebook    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | Notebook    | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | Notebook    | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | Notebook    | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | Notebook    | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [0acfc1ab65](https://linux-hardware.org/?probe=0acfc1ab65) | Aug 20, 2021 |
| HP            | 84F0 0100                   | All in one  | [27898f0b8e](https://linux-hardware.org/?probe=27898f0b8e) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | Notebook    | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | Notebook    | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | Desktop     | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [65567a1be4](https://linux-hardware.org/?probe=65567a1be4) | Aug 10, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | Desktop     | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [01e77d1c5f](https://linux-hardware.org/?probe=01e77d1c5f) | Aug 04, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | Notebook    | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [c5d61df0df](https://linux-hardware.org/?probe=c5d61df0df) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | Desktop     | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [733eb370f2](https://linux-hardware.org/?probe=733eb370f2) | Jul 27, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [79b20f33a0](https://linux-hardware.org/?probe=79b20f33a0) | Jul 24, 2021 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [94ef768b69](https://linux-hardware.org/?probe=94ef768b69) | Jul 24, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [3bed53aab7](https://linux-hardware.org/?probe=3bed53aab7) | Jul 14, 2021 |
| Dell          | 0V8WGR A00                  | Desktop     | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Dell          | XPS L501X                   | Notebook    | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | Desktop     | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | Desktop     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | Notebook    | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| HP            | 843C                        | Desktop     | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | Notebook    | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | Desktop     | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | Desktop     | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| HP            | Unknown                     | Notebook    | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | Notebook    | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | Desktop     | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | Desktop     | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | Notebook    | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Quanta        | XV1                         | All in one  | [d3b0fddedf](https://linux-hardware.org/?probe=d3b0fddedf) | May 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Quanta        | XV1                         | All in one  | [5d38d7934e](https://linux-hardware.org/?probe=5d38d7934e) | Apr 30, 2021 |
| Pegatron      | Benicia                     | Desktop     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [236ed4432a](https://linux-hardware.org/?probe=236ed4432a) | Apr 24, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | Desktop     | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | Desktop     | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0761ed6181](https://linux-hardware.org/?probe=0761ed6181) | Apr 16, 2021 |
| Acer          | Aspire XC-605G              | Desktop     | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-27-generic | 133       | 50.96%  |
| 5.11.0-34-generic | 62        | 23.75%  |
| 5.8.0-53-generic  | 13        | 4.98%   |
| 5.8.0-50-generic  | 12        | 4.6%    |
| 5.11.0-25-generic | 12        | 4.6%    |
| 5.8.0-55-generic  | 10        | 3.83%   |
| 5.8.0-59-generic  | 8         | 3.07%   |
| 5.8.0-63-generic  | 4         | 1.53%   |
| 5.8.0-49-generic  | 4         | 1.53%   |
| 5.8.0-45-generic  | 1         | 0.38%   |
| 5.4.0-42-generic  | 1         | 0.38%   |
| 5.10.0-1044-oem   | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 205       | 79.46%  |
| 5.8.0   | 51        | 19.77%  |
| 5.4.0   | 1         | 0.39%   |
| 5.10.0  | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 205       | 79.46%  |
| 5.8     | 51        | 19.77%  |
| 5.4     | 1         | 0.39%   |
| 5.10    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 255       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| GNOME    | 252       | 98.44%  |
| Unknown  | 2         | 0.78%   |
| XFCE     | 1         | 0.39%   |
| Cinnamon | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 251       | 98.05%  |
| Wayland | 4         | 1.56%   |
| Unknown | 1         | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 228       | 89.41%  |
| GDM     | 26        | 10.2%   |
| TDM     | 1         | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 88        | 34.51%  |
| de_DE | 27        | 10.59%  |
| en_GB | 26        | 10.2%   |
| pt_BR | 18        | 7.06%   |
| en_IN | 13        | 5.1%    |
| es_ES | 10        | 3.92%   |
| es_MX | 8         | 3.14%   |
| pl_PL | 5         | 1.96%   |
| nl_NL | 5         | 1.96%   |
| en_ZA | 5         | 1.96%   |
| it_IT | 4         | 1.57%   |
| es_CL | 4         | 1.57%   |
| en_CA | 4         | 1.57%   |
| cs_CZ | 4         | 1.57%   |
| pt_PT | 3         | 1.18%   |
| hu_HU | 3         | 1.18%   |
| en_AU | 3         | 1.18%   |
| fr_FR | 2         | 0.78%   |
| es_PE | 2         | 0.78%   |
| es_CO | 2         | 0.78%   |
| en_NZ | 2         | 0.78%   |
| de_CH | 2         | 0.78%   |
| zh_TW | 1         | 0.39%   |
| sv_SE | 1         | 0.39%   |
| ru_UA | 1         | 0.39%   |
| ru_RU | 1         | 0.39%   |
| nl_BE | 1         | 0.39%   |
| ja_JP | 1         | 0.39%   |
| fr_CA | 1         | 0.39%   |
| fr_BE | 1         | 0.39%   |
| fi_FI | 1         | 0.39%   |
| es_PA | 1         | 0.39%   |
| es_GT | 1         | 0.39%   |
| en_SG | 1         | 0.39%   |
| en_PH | 1         | 0.39%   |
| de_AT | 1         | 0.39%   |
| bg_BG | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 154       | 60.16%  |
| BIOS | 102       | 39.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 239       | 93.73%  |
| Zfs     | 7         | 2.75%   |
| Overlay | 5         | 1.96%   |
| Ext3    | 2         | 0.78%   |
| Btrfs   | 2         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 227       | 89.02%  |
| GPT     | 26        | 10.2%   |
| MBR     | 2         | 0.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 252       | 98.44%  |
| Yes       | 4         | 1.56%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 224       | 87.84%  |
| Yes       | 31        | 12.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 45        | 17.65%  |
| Hewlett-Packard     | 40        | 15.69%  |
| Lenovo              | 37        | 14.51%  |
| Dell                | 31        | 12.16%  |
| Acer                | 22        | 8.63%   |
| MSI                 | 14        | 5.49%   |
| Gigabyte Technology | 14        | 5.49%   |
| Apple               | 9         | 3.53%   |
| Toshiba             | 7         | 2.75%   |
| Intel               | 7         | 2.75%   |
| ASRock              | 4         | 1.57%   |
| Sony                | 3         | 1.18%   |
| LG Electronics      | 3         | 1.18%   |
| Fujitsu             | 2         | 0.78%   |
| Biostar             | 2         | 0.78%   |
| Unknown             | 2         | 0.78%   |
| TianBei             | 1         | 0.39%   |
| Samsung Electronics | 1         | 0.39%   |
| RCA                 | 1         | 0.39%   |
| Razer               | 1         | 0.39%   |
| Quanta              | 1         | 0.39%   |
| Positivo            | 1         | 0.39%   |
| Pegatron            | 1         | 0.39%   |
| Packard Bell        | 1         | 0.39%   |
| NCR                 | 1         | 0.39%   |
| Jumper              | 1         | 0.39%   |
| Insyde              | 1         | 0.39%   |
| Google              | 1         | 0.39%   |
| Foxconn             | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 4         | 1.57%   |
| HP Notebook                            | 3         | 1.18%   |
| ASUS All Series                        | 3         | 1.18%   |
| Intel DQ77MK-R01                       | 2         | 0.78%   |
| HP ENVY Sleekbook 4 PC                 | 2         | 0.78%   |
| Gigabyte A320M-S2H                     | 2         | 0.78%   |
| Dell OptiPlex 990                      | 2         | 0.78%   |
| Dell Inspiron 5566                     | 2         | 0.78%   |
| ASUS M5A97 LE R2.0                     | 2         | 0.78%   |
| ASUS M5A78L-M/USB3                     | 2         | 0.78%   |
| Acer One S1003                         | 2         | 0.78%   |
| Toshiba Satellite S75Dt-A              | 1         | 0.39%   |
| Toshiba Satellite Pro L450D            | 1         | 0.39%   |
| Toshiba Satellite L755                 | 1         | 0.39%   |
| Toshiba Satellite C870-1C2             | 1         | 0.39%   |
| Toshiba Satellite C850D-11C            | 1         | 0.39%   |
| Toshiba Satellite C850-1CP             | 1         | 0.39%   |
| Toshiba Satellite C75D-B               | 1         | 0.39%   |
| TianBei TB-H7                          | 1         | 0.39%   |
| Sony VPCS135FX                         | 1         | 0.39%   |
| Sony VPCF215FX                         | 1         | 0.39%   |
| Sony VGN-SR5                           | 1         | 0.39%   |
| Samsung 550P5C/550P7C                  | 1         | 0.39%   |
| RCA W101-CS                            | 1         | 0.39%   |
| Razer Book 13 - RZ09-0357              | 1         | 0.39%   |
| Quanta CA27                            | 1         | 0.39%   |
| Positivo POS-PIH81DI                   | 1         | 0.39%   |
| Pegatron NE502AV-ABA a6750t            | 1         | 0.39%   |
| Packard Bell DOT S                     | 1         | 0.39%   |
| NCR xxxx-xxxx-xxxx                     | 1         | 0.39%   |
| MSI WE136AA-UUZ p6337ch                | 1         | 0.39%   |
| MSI Pro 3515 Series                    | 1         | 0.39%   |
| MSI MS-7D18                            | 1         | 0.39%   |
| MSI MS-7C37                            | 1         | 0.39%   |
| MSI MS-7B89                            | 1         | 0.39%   |
| MSI MS-7B84                            | 1         | 0.39%   |
| MSI MS-7A71                            | 1         | 0.39%   |
| MSI MS-7914                            | 1         | 0.39%   |
| MSI MS-7817                            | 1         | 0.39%   |
| MSI MS-7816                            | 1         | 0.39%   |
| MSI MS-7798                            | 1         | 0.39%   |
| MSI GS75 Stealth 10SF                  | 1         | 0.39%   |
| MSI GL62 7RDX                          | 1         | 0.39%   |
| MSI GE75 Raider 8RF                    | 1         | 0.39%   |
| LG S460-G.BG31P1                       | 1         | 0.39%   |
| LG A410-K.BE47P1                       | 1         | 0.39%   |
| LG 17U70N-R.AAS7U1                     | 1         | 0.39%   |
| Lenovo Yoga C740-15IML 81TD            | 1         | 0.39%   |
| Lenovo Yoga 730-13IWL 81JR             | 1         | 0.39%   |
| Lenovo Yoga 510-14ISK 80S7             | 1         | 0.39%   |
| Lenovo Yoga 330-11IGM 81A6             | 1         | 0.39%   |
| Lenovo Yoga 3 Pro-1370 80HE            | 1         | 0.39%   |
| Lenovo ThinkPad Yoga 11e 20DAS0SF00    | 1         | 0.39%   |
| Lenovo ThinkPad X131e 3371AL2          | 1         | 0.39%   |
| Lenovo ThinkPad W520 4284AW3           | 1         | 0.39%   |
| Lenovo ThinkPad T520 42435GG           | 1         | 0.39%   |
| Lenovo ThinkPad T520 4242W4F           | 1         | 0.39%   |
| Lenovo ThinkPad T470s W10DG 20JTS0280G | 1         | 0.39%   |
| Lenovo ThinkPad T440p 20AWS1CH00       | 1         | 0.39%   |
| Lenovo ThinkPad P50 20EN001EUS         | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Acer Aspire          | 15        | 5.88%   |
| Lenovo ThinkPad      | 11        | 4.31%   |
| Lenovo IdeaPad       | 8         | 3.14%   |
| Dell Inspiron        | 8         | 3.14%   |
| Toshiba Satellite    | 7         | 2.75%   |
| HP ENVY              | 6         | 2.35%   |
| Dell Latitude        | 6         | 2.35%   |
| Lenovo Yoga          | 5         | 1.96%   |
| HP Pavilion          | 5         | 1.96%   |
| HP EliteBook         | 5         | 1.96%   |
| Dell XPS             | 5         | 1.96%   |
| HP ProBook           | 4         | 1.57%   |
| Dell Precision       | 4         | 1.57%   |
| ASUS M5A97           | 4         | 1.57%   |
| Unknown              | 4         | 1.57%   |
| Lenovo ThinkCentre   | 3         | 1.18%   |
| HP Notebook          | 3         | 1.18%   |
| HP Compaq            | 3         | 1.18%   |
| HP 255               | 3         | 1.18%   |
| Dell Vostro          | 3         | 1.18%   |
| Dell OptiPlex        | 3         | 1.18%   |
| ASUS VivoBook        | 3         | 1.18%   |
| ASUS PRIME           | 3         | 1.18%   |
| ASUS All             | 3         | 1.18%   |
| Intel DQ77MK-R01     | 2         | 0.78%   |
| Gigabyte B550M       | 2         | 0.78%   |
| Gigabyte B450        | 2         | 0.78%   |
| Gigabyte A320M-S2H   | 2         | 0.78%   |
| ASUS TUF             | 2         | 0.78%   |
| ASUS ROG             | 2         | 0.78%   |
| ASUS P8Z77-V         | 2         | 0.78%   |
| ASUS P8H61-M         | 2         | 0.78%   |
| ASUS M5A78L-M        | 2         | 0.78%   |
| ASUS ASUS            | 2         | 0.78%   |
| Apple MacBookPro11   | 2         | 0.78%   |
| Acer Swift           | 2         | 0.78%   |
| Acer One             | 2         | 0.78%   |
| TianBei TB-H7        | 1         | 0.39%   |
| Sony VPCS135FX       | 1         | 0.39%   |
| Sony VPCF215FX       | 1         | 0.39%   |
| Sony VGN-SR5         | 1         | 0.39%   |
| Samsung 550P5C       | 1         | 0.39%   |
| RCA W101-CS          | 1         | 0.39%   |
| Razer Book           | 1         | 0.39%   |
| Quanta CA27          | 1         | 0.39%   |
| Positivo POS-PIH81DI | 1         | 0.39%   |
| Pegatron NE502AV-ABA | 1         | 0.39%   |
| Packard Bell DOT     | 1         | 0.39%   |
| NCR xxxx-xxxx-xxxx   | 1         | 0.39%   |
| MSI WE136AA-UUZ      | 1         | 0.39%   |
| MSI Pro              | 1         | 0.39%   |
| MSI MS-7D18          | 1         | 0.39%   |
| MSI MS-7C37          | 1         | 0.39%   |
| MSI MS-7B89          | 1         | 0.39%   |
| MSI MS-7B84          | 1         | 0.39%   |
| MSI MS-7A71          | 1         | 0.39%   |
| MSI MS-7914          | 1         | 0.39%   |
| MSI MS-7817          | 1         | 0.39%   |
| MSI MS-7816          | 1         | 0.39%   |
| MSI MS-7798          | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 41        | 16.08%  |
| 2020 | 37        | 14.51%  |
| 2018 | 27        | 10.59%  |
| 2014 | 25        | 9.8%    |
| 2019 | 24        | 9.41%   |
| 2012 | 18        | 7.06%   |
| 2011 | 16        | 6.27%   |
| 2013 | 14        | 5.49%   |
| 2015 | 12        | 4.71%   |
| 2016 | 9         | 3.53%   |
| 2008 | 9         | 3.53%   |
| 2017 | 8         | 3.14%   |
| 2010 | 6         | 2.35%   |
| 2009 | 5         | 1.96%   |
| 2007 | 3         | 1.18%   |
| 2006 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 144       | 56.47%  |
| Desktop     | 93        | 36.47%  |
| All in one  | 6         | 2.35%   |
| Convertible | 5         | 1.96%   |
| Tablet      | 4         | 1.57%   |
| Mini pc     | 3         | 1.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 223       | 87.45%  |
| Enabled  | 32        | 12.55%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 254       | 99.61%  |
| Yes  | 1         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 67        | 26.07%  |
| 8.01-16.0   | 56        | 21.79%  |
| 3.01-4.0    | 54        | 21.01%  |
| 16.01-24.0  | 44        | 17.12%  |
| 32.01-64.0  | 24        | 9.34%   |
| 1.01-2.0    | 8         | 3.11%   |
| 64.01-256.0 | 3         | 1.17%   |
| 2.01-3.0    | 1         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 119       | 44.91%  |
| 2.01-3.0   | 85        | 32.08%  |
| 3.01-4.0   | 35        | 13.21%  |
| 4.01-8.0   | 20        | 7.55%   |
| 0.51-1.0   | 4         | 1.51%   |
| 24.01-32.0 | 1         | 0.38%   |
| 8.01-16.0  | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 151       | 59.22%  |
| 2      | 65        | 25.49%  |
| 3      | 19        | 7.45%   |
| 4      | 11        | 4.31%   |
| 5      | 5         | 1.96%   |
| 8      | 2         | 0.78%   |
| 6      | 1         | 0.39%   |
| 0      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 136       | 53.13%  |
| Yes       | 120       | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 89.06%  |
| No        | 28        | 10.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 77.65%  |
| No        | 57        | 22.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 59.61%  |
| No        | 103       | 40.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 53        | 20.78%  |
| Germany      | 31        | 12.16%  |
| UK           | 23        | 9.02%   |
| Brazil       | 21        | 8.24%   |
| India        | 14        | 5.49%   |
| Spain        | 10        | 3.92%   |
| Mexico       | 9         | 3.53%   |
| South Africa | 6         | 2.35%   |
| Netherlands  | 6         | 2.35%   |
| Canada       | 6         | 2.35%   |
| Italy        | 5         | 1.96%   |
| Hungary      | 5         | 1.96%   |
| Chile        | 5         | 1.96%   |
| Australia    | 5         | 1.96%   |
| Poland       | 4         | 1.57%   |
| Czechia      | 4         | 1.57%   |
| Switzerland  | 3         | 1.18%   |
| France       | 3         | 1.18%   |
| Colombia     | 3         | 1.18%   |
| Austria      | 3         | 1.18%   |
| Taiwan       | 2         | 0.78%   |
| Sweden       | 2         | 0.78%   |
| Romania      | 2         | 0.78%   |
| Philippines  | 2         | 0.78%   |
| New Zealand  | 2         | 0.78%   |
| Malaysia     | 2         | 0.78%   |
| Indonesia    | 2         | 0.78%   |
| Belgium      | 2         | 0.78%   |
| Vietnam      | 1         | 0.39%   |
| Ukraine      | 1         | 0.39%   |
| Turkey       | 1         | 0.39%   |
| Thailand     | 1         | 0.39%   |
| Serbia       | 1         | 0.39%   |
| Portugal     | 1         | 0.39%   |
| Peru         | 1         | 0.39%   |
| Panama       | 1         | 0.39%   |
| Mozambique   | 1         | 0.39%   |
| Madagascar   | 1         | 0.39%   |
| Kenya        | 1         | 0.39%   |
| Japan        | 1         | 0.39%   |
| Israel       | 1         | 0.39%   |
| Guatemala    | 1         | 0.39%   |
| Greece       | 1         | 0.39%   |
| Finland      | 1         | 0.39%   |
| Denmark      | 1         | 0.39%   |
| Bulgaria     | 1         | 0.39%   |
| Argentina    | 1         | 0.39%   |
| Angola       | 1         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Vienna                   | 3         | 1.17%   |
| S??o Lu?­s               | 3         | 1.17%   |
| Zurich                   | 2         | 0.78%   |
| Vancouver                | 2         | 0.78%   |
| Taboao da Serra          | 2         | 0.78%   |
| Santiago                 | 2         | 0.78%   |
| Rome                     | 2         | 0.78%   |
| Rio de Janeiro           | 2         | 0.78%   |
| Miami                    | 2         | 0.78%   |
| Mentor                   | 2         | 0.78%   |
| Melbourne                | 2         | 0.78%   |
| Madrid                   | 2         | 0.78%   |
| London                   | 2         | 0.78%   |
| Livingston               | 2         | 0.78%   |
| Kuala Lumpur             | 2         | 0.78%   |
| Johannesburg             | 2         | 0.78%   |
| Hyderabad                | 2         | 0.78%   |
| Glasgow                  | 2         | 0.78%   |
| Dortmund                 | 2         | 0.78%   |
| Contagem                 | 2         | 0.78%   |
| Chennai                  | 2         | 0.78%   |
| Auckland                 | 2         | 0.78%   |
| Ahmedabad                | 2         | 0.78%   |
| Zaventem                 | 1         | 0.39%   |
| Zacatecas City           | 1         | 0.39%   |
| Zabrze                   | 1         | 0.39%   |
| Yokohama                 | 1         | 0.39%   |
| Xalapa                   | 1         | 0.39%   |
| Wylie                    | 1         | 0.39%   |
| Wigan                    | 1         | 0.39%   |
| West Jordan              | 1         | 0.39%   |
| Wandsworth               | 1         | 0.39%   |
| Vespasiano               | 1         | 0.39%   |
| Veracruz                 | 1         | 0.39%   |
| Vadodara                 | 1         | 0.39%   |
| Utrecht                  | 1         | 0.39%   |
| Twinsburg                | 1         | 0.39%   |
| Trujillo                 | 1         | 0.39%   |
| SÃ£o Bernardo do Campo   | 1         | 0.39%   |
| Szombathely              | 1         | 0.39%   |
| Szigetvar                | 1         | 0.39%   |
| Szczecin                 | 1         | 0.39%   |
| Sutton Coldfield         | 1         | 0.39%   |
| Stuttgart                | 1         | 0.39%   |
| Stockholm                | 1         | 0.39%   |
| Stadskanaal              | 1         | 0.39%   |
| St. Cloud                | 1         | 0.39%   |
| Spremberg                | 1         | 0.39%   |
| Solingen                 | 1         | 0.39%   |
| Sheffield                | 1         | 0.39%   |
| Seville                  | 1         | 0.39%   |
| Sechelt                  | 1         | 0.39%   |
| S??o Jo??o del Rei       | 1         | 0.39%   |
| Santa Cruz do Rio Pardo  | 1         | 0.39%   |
| Santa Cruz de Tenerife   | 1         | 0.39%   |
| Sant Carles de la Rapita | 1         | 0.39%   |
| San Francisco            | 1         | 0.39%   |
| Salt Lake City           | 1         | 0.39%   |
| Salem                    | 1         | 0.39%   |
| Sainte-Marie             | 1         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 64        | 76     | 17.11%  |
| Samsung Electronics       | 57        | 71     | 15.24%  |
| WDC                       | 46        | 59     | 12.3%   |
| SanDisk                   | 27        | 34     | 7.22%   |
| Toshiba                   | 24        | 24     | 6.42%   |
| Kingston                  | 19        | 22     | 5.08%   |
| Unknown                   | 17        | 24     | 4.55%   |
| Hitachi                   | 14        | 16     | 3.74%   |
| Crucial                   | 12        | 14     | 3.21%   |
| HGST                      | 8         | 10     | 2.14%   |
| A-DATA Technology         | 7         | 7      | 1.87%   |
| Phison                    | 6         | 7      | 1.6%    |
| Micron Technology         | 5         | 6      | 1.34%   |
| Intel                     | 5         | 5      | 1.34%   |
| Apple                     | 5         | 5      | 1.34%   |
| SK Hynix                  | 4         | 5      | 1.07%   |
| Silicon Motion            | 4         | 6      | 1.07%   |
| Intenso                   | 4         | 4      | 1.07%   |
| China                     | 4         | 5      | 1.07%   |
| Fujitsu                   | 3         | 4      | 0.8%    |
| Team                      | 2         | 2      | 0.53%   |
| SPCC                      | 2         | 2      | 0.53%   |
| PNY                       | 2         | 3      | 0.53%   |
| Patriot                   | 2         | 2      | 0.53%   |
| Micron/Crucial Technology | 2         | 2      | 0.53%   |
| LITEONIT                  | 2         | 3      | 0.53%   |
| Lite-On                   | 2         | 2      | 0.53%   |
| Lexar                     | 2         | 2      | 0.53%   |
| KIOXIA                    | 2         | 2      | 0.53%   |
| JMicron                   | 2         | 3      | 0.53%   |
| Hewlett-Packard           | 2         | 2      | 0.53%   |
| Gigabyte Technology       | 2         | 2      | 0.53%   |
| XPG                       | 1         | 1      | 0.27%   |
| Verbatim                  | 1         | 1      | 0.27%   |
| Vaseky                    | 1         | 1      | 0.27%   |
| USB30                     | 1         | 2      | 0.27%   |
| SABRENT                   | 1         | 1      | 0.27%   |
| OWC                       | 1         | 1      | 0.27%   |
| OCZ                       | 1         | 1      | 0.27%   |
| Netac                     | 1         | 1      | 0.27%   |
| Maxtor                    | 1         | 1      | 0.27%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.27%   |
| KingSpec                  | 1         | 1      | 0.27%   |
| KingFast                  | 1         | 1      | 0.27%   |
| Config                    | 1         | 1      | 0.27%   |
| BUFFALO                   | 1         | 1      | 0.27%   |
| Apacer                    | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 1.45%   |
| Unknown MMC Card  32GB              | 5         | 1.21%   |
| Seagate ST500DM002-1BD142 500GB     | 5         | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 1.21%   |
| Samsung SSD 860 EVO 500GB           | 5         | 1.21%   |
| Unknown SD/MMC/MS PRO 64GB          | 4         | 0.97%   |
| Toshiba MQ01ABF050 500GB            | 4         | 0.97%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 0.97%   |
| Samsung NVMe SSD Drive 500GB        | 4         | 0.97%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 0.97%   |
| Crucial CT240BX500SSD1 240GB        | 4         | 0.97%   |
| WDC WD10EZEX-08WN4A0 1TB            | 3         | 0.73%   |
| Unknown MMC Card  128GB             | 3         | 0.73%   |
| Toshiba HDWD110 1TB                 | 3         | 0.73%   |
| Seagate ST2000DM001-9YN164 2TB      | 3         | 0.73%   |
| SanDisk SSD PLUS 1000GB             | 3         | 0.73%   |
| Sandisk NVMe SSD Drive 256GB        | 3         | 0.73%   |
| Samsung SSD 850 EVO 500GB           | 3         | 0.73%   |
| Samsung SSD 840 EVO 250GB           | 3         | 0.73%   |
| Samsung NVMe SSD Drive 512GB        | 3         | 0.73%   |
| Samsung HD103UJ 1TB                 | 3         | 0.73%   |
| Phison NVMe SSD Drive 1TB           | 3         | 0.73%   |
| Kingston SV300S37A120G 120GB SSD    | 3         | 0.73%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 0.73%   |
| HGST HTS725050A7E630 500GB          | 3         | 0.73%   |
| Crucial CT480BX500SSD1 480GB        | 3         | 0.73%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 2         | 0.48%   |
| WDC WD1600AAJS-75M0A0 160GB         | 2         | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 0.48%   |
| WDC WD10EZEX-60M2NA0 1TB            | 2         | 0.48%   |
| Unknown MMC Card  64GB              | 2         | 0.48%   |
| Toshiba MQ02ABD100H 1TB             | 2         | 0.48%   |
| Toshiba MK3265GSX 320GB             | 2         | 0.48%   |
| SK Hynix NVMe SSD Drive 512GB       | 2         | 0.48%   |
| Silicon Motion NVMe SSD Drive 128GB | 2         | 0.48%   |
| Seagate ST9500325AS 500GB           | 2         | 0.48%   |
| Seagate ST2000LM015-2E8174 2TB      | 2         | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB      | 2         | 0.48%   |
| SanDisk SSD PLUS 480GB              | 2         | 0.48%   |
| SanDisk SDSSDA120G 120GB            | 2         | 0.48%   |
| Sandisk NVMe SSD Drive 512GB        | 2         | 0.48%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.48%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.48%   |
| Samsung SSD 840 EVO 120GB           | 2         | 0.48%   |
| Samsung NVMe SSD Drive 256GB        | 2         | 0.48%   |
| Samsung NVMe SSD Drive 1TB          | 2         | 0.48%   |
| Samsung HD103SJ 1TB                 | 2         | 0.48%   |
| Phison NVMe SSD Drive 512GB         | 2         | 0.48%   |
| Patriot Burst 240GB SSD             | 2         | 0.48%   |
| KIOXIA NVMe SSD Drive 512GB         | 2         | 0.48%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.48%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.48%   |
| Intenso SSD SATAIII 960GB           | 2         | 0.48%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.48%   |
| Hitachi HDT725050VLA360 500GB       | 2         | 0.48%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2         | 0.48%   |
| Crucial CT500MX500SSD1 500GB        | 2         | 0.48%   |
| A-DATA SU750 256GB SSD              | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 72     | 37.72%  |
| WDC                 | 42        | 52     | 25.15%  |
| Toshiba             | 19        | 19     | 11.38%  |
| Hitachi             | 14        | 16     | 8.38%   |
| Samsung Electronics | 9         | 11     | 5.39%   |
| HGST                | 8         | 10     | 4.79%   |
| Unknown             | 4         | 6      | 2.4%    |
| Fujitsu             | 3         | 4      | 1.8%    |
| Hewlett-Packard     | 2         | 2      | 1.2%    |
| Apple               | 2         | 2      | 1.2%    |
| Maxtor              | 1         | 1      | 0.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 36     | 24.06%  |
| SanDisk             | 17        | 22     | 12.78%  |
| Kingston            | 17        | 20     | 12.78%  |
| Crucial             | 12        | 14     | 9.02%   |
| A-DATA Technology   | 6         | 6      | 4.51%   |
| WDC                 | 4         | 4      | 3.01%   |
| Micron Technology   | 4         | 5      | 3.01%   |
| Intenso             | 4         | 4      | 3.01%   |
| China               | 4         | 5      | 3.01%   |
| Apple               | 3         | 3      | 2.26%   |
| Toshiba             | 2         | 2      | 1.5%    |
| Team                | 2         | 2      | 1.5%    |
| SPCC                | 2         | 2      | 1.5%    |
| PNY                 | 2         | 3      | 1.5%    |
| Patriot             | 2         | 2      | 1.5%    |
| LITEONIT            | 2         | 3      | 1.5%    |
| Lexar               | 2         | 2      | 1.5%    |
| Gigabyte Technology | 2         | 2      | 1.5%    |
| Verbatim            | 1         | 1      | 0.75%   |
| USB30               | 1         | 2      | 0.75%   |
| Seagate             | 1         | 1      | 0.75%   |
| SABRENT             | 1         | 1      | 0.75%   |
| PHISON              | 1         | 1      | 0.75%   |
| OWC                 | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 1      | 0.75%   |
| JMicron             | 1         | 2      | 0.75%   |
| Intel               | 1         | 1      | 0.75%   |
| BUFFALO             | 1         | 1      | 0.75%   |
| Apacer              | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 142       | 195    | 42.9%   |
| SSD     | 111       | 153    | 33.53%  |
| NVMe    | 59        | 74     | 17.82%  |
| MMC     | 10        | 14     | 3.02%   |
| Unknown | 9         | 11     | 2.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 209       | 336    | 70.85%  |
| NVMe | 59        | 74     | 20%     |
| SAS  | 17        | 23     | 5.76%   |
| MMC  | 10        | 14     | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 158       | 206    | 59.62%  |
| 0.51-1.0   | 81        | 107    | 30.57%  |
| 1.01-2.0   | 18        | 25     | 6.79%   |
| 3.01-4.0   | 5         | 6      | 1.89%   |
| 4.01-10.0  | 2         | 2      | 0.75%   |
| 2.01-3.0   | 1         | 2      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 70        | 27.45%  |
| 101-250        | 68        | 26.67%  |
| 501-1000       | 43        | 16.86%  |
| 51-100         | 24        | 9.41%   |
| 1001-2000      | 19        | 7.45%   |
| 21-50          | 8         | 3.14%   |
| More than 3000 | 7         | 2.75%   |
| 1-20           | 7         | 2.75%   |
| Unknown        | 5         | 1.96%   |
| 2001-3000      | 4         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 120       | 46.51%  |
| 21-50          | 59        | 22.87%  |
| 101-250        | 26        | 10.08%  |
| 51-100         | 21        | 8.14%   |
| 251-500        | 10        | 3.88%   |
| 501-1000       | 8         | 3.1%    |
| More than 3000 | 5         | 1.94%   |
| Unknown        | 5         | 1.94%   |
| 1001-2000      | 3         | 1.16%   |
| 2001-3000      | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                      | Computers | Drives | Percent |
|----------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB    | 2         | 2      | 25%     |
| WDC WD10JPVX-22JC3T0 1TB   | 1         | 1      | 12.5%   |
| WDC WD10EZEX-21M2NA0 1TB   | 1         | 2      | 12.5%   |
| Toshiba MK3265GSX 320GB    | 1         | 1      | 12.5%   |
| Seagate ST9500420AS 500GB  | 1         | 1      | 12.5%   |
| Seagate ST9200420ASG 200GB | 1         | 1      | 12.5%   |
| HGST HTS725050A7E630 500GB | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 37.5%   |
| WDC     | 2         | 3      | 25%     |
| Seagate | 2         | 2      | 25%     |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 37.5%   |
| WDC     | 2         | 3      | 25%     |
| Seagate | 2         | 2      | 25%     |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 229       | 408    | 87.07%  |
| Works    | 25        | 29     | 9.51%   |
| Malfunc  | 8         | 9      | 3.04%   |
| Failed   | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 179       | 58.31%  |
| AMD                              | 53        | 17.26%  |
| Samsung Electronics              | 22        | 7.17%   |
| Sandisk                          | 12        | 3.91%   |
| Phison Electronics               | 6         | 1.95%   |
| ASMedia Technology               | 5         | 1.63%   |
| SK Hynix                         | 4         | 1.3%    |
| Silicon Motion                   | 4         | 1.3%    |
| KIOXIA                           | 3         | 0.98%   |
| Toshiba America Info Systems     | 2         | 0.65%   |
| Silicon Image                    | 2         | 0.65%   |
| Micron/Crucial Technology        | 2         | 0.65%   |
| Marvell Technology Group         | 2         | 0.65%   |
| Lite-On Technology               | 2         | 0.65%   |
| Kingston Technology Company      | 2         | 0.65%   |
| ADATA Technology                 | 2         | 0.65%   |
| VIA Technologies                 | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Nvidia                           | 1         | 0.33%   |
| Micron Technology                | 1         | 0.33%   |
| JMicron Technology               | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 34        | 9.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 4.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 14        | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11        | 3.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 3.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 2.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 2.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.63%   |
| Intel SATA Controller [RAID mode]                                                       | 8         | 2.34%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 2.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.46%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.46%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.17%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 1.17%   |
| Intel SSD 660P Series                                                                   | 4         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.17%   |
| AMD FCH SATA Controller D                                                               | 4         | 1.17%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.88%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.88%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 0.88%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3         | 0.88%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 0.88%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 3         | 0.88%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.58%   |
| Sandisk PC SN520 NVMe SSD                                                               | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.58%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.58%   |
| Lite-On Non-Volatile memory controller                                                  | 2         | 0.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.58%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 2         | 0.58%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 2         | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 0.58%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.29%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                                    | 1         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 194       | 63.4%   |
| NVMe | 59        | 19.28%  |
| IDE  | 31        | 10.13%  |
| RAID | 22        | 7.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 195       | 76.47%  |
| AMD    | 60        | 23.53%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.96%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 1.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.57%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.18%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 1.18%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 3         | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.18%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.18%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 1.18%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 2         | 0.78%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.78%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.78%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.78%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.78%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.78%   |
| Intel Core i5-3340 CPU @ 3.10GHz              | 2         | 0.78%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.78%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.78%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 0.78%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.78%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2         | 0.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2         | 0.78%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.78%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.78%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.78%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 0.78%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.78%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.78%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2         | 0.78%   |
| AMD FX-8320E Eight-Core Processor             | 2         | 0.78%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 2         | 0.78%   |
| AMD A10-5750M APU with Radeon HD Graphics     | 2         | 0.78%   |
| Intel Xeon CPU X5650 @ 2.67GHz                | 1         | 0.39%   |
| Intel Xeon CPU X3220 @ 2.40GHz                | 1         | 0.39%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.39%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.39%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.39%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.39%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.39%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1         | 0.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.39%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 1         | 0.39%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.39%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 1         | 0.39%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 71        | 27.84%  |
| Intel Core i7                        | 43        | 16.86%  |
| Intel Core i3                        | 27        | 10.59%  |
| AMD Ryzen 5                          | 12        | 4.71%   |
| Intel Core 2 Duo                     | 9         | 3.53%   |
| Intel Celeron                        | 9         | 3.53%   |
| Other                                | 8         | 3.14%   |
| AMD FX                               | 8         | 3.14%   |
| AMD Ryzen 7                          | 7         | 2.75%   |
| AMD Ryzen 3                          | 7         | 2.75%   |
| Intel Atom                           | 6         | 2.35%   |
| AMD A6                               | 6         | 2.35%   |
| Intel Pentium                        | 5         | 1.96%   |
| Intel Xeon                           | 4         | 1.57%   |
| Intel Core 2 Quad                    | 4         | 1.57%   |
| Intel Pentium Dual-Core              | 3         | 1.18%   |
| Intel Pentium Dual                   | 3         | 1.18%   |
| Intel Pentium Silver                 | 2         | 0.78%   |
| AMD E1                               | 2         | 0.78%   |
| AMD A10                              | 2         | 0.78%   |
| Intel Pentium Gold                   | 1         | 0.39%   |
| Intel Core i9                        | 1         | 0.39%   |
| Intel Core 2                         | 1         | 0.39%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.39%   |
| AMD Turion 64 Mobile                 | 1         | 0.39%   |
| AMD Ryzen 9                          | 1         | 0.39%   |
| AMD Ryzen 7 PRO                      | 1         | 0.39%   |
| AMD Phenom II X4                     | 1         | 0.39%   |
| AMD GX                               | 1         | 0.39%   |
| AMD E2                               | 1         | 0.39%   |
| AMD E                                | 1         | 0.39%   |
| AMD C-60                             | 1         | 0.39%   |
| AMD Athlon II X3                     | 1         | 0.39%   |
| AMD Athlon 64 X2                     | 1         | 0.39%   |
| AMD Athlon                           | 1         | 0.39%   |
| AMD A8                               | 1         | 0.39%   |
| AMD A4                               | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 116       | 45.49%  |
| 2      | 106       | 41.57%  |
| 6      | 13        | 5.1%    |
| 8      | 11        | 4.31%   |
| 3      | 4         | 1.57%   |
| 1      | 3         | 1.18%   |
| 12     | 1         | 0.39%   |
| 10     | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 255       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 161       | 63.14%  |
| 1      | 94        | 36.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 255       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 24        | 9.34%   |
| 0x206a7    | 21        | 8.17%   |
| Unknown    | 20        | 7.78%   |
| 0x306c3    | 19        | 7.39%   |
| 0x40651    | 9         | 3.5%    |
| 0x806ea    | 8         | 3.11%   |
| 0x506e3    | 8         | 3.11%   |
| 0x08701021 | 8         | 3.11%   |
| 0x806ec    | 7         | 2.72%   |
| 0x6fb      | 7         | 2.72%   |
| 0x306d4    | 6         | 2.33%   |
| 0x1067a    | 6         | 2.33%   |
| 0x06000852 | 6         | 2.33%   |
| 0x806c1    | 5         | 1.95%   |
| 0x406e3    | 5         | 1.95%   |
| 0x406c4    | 5         | 1.95%   |
| 0x30678    | 5         | 1.95%   |
| 0x08108109 | 5         | 1.95%   |
| 0x6fd      | 4         | 1.56%   |
| 0x06001119 | 4         | 1.56%   |
| 0xa0652    | 3         | 1.17%   |
| 0x906ea    | 3         | 1.17%   |
| 0x706a1    | 3         | 1.17%   |
| 0x20655    | 3         | 1.17%   |
| 0x20652    | 3         | 1.17%   |
| 0x08108102 | 3         | 1.17%   |
| 0x07030106 | 3         | 1.17%   |
| 0x05000119 | 3         | 1.17%   |
| 0xa0655    | 2         | 0.78%   |
| 0xa0653    | 2         | 0.78%   |
| 0x906eb    | 2         | 0.78%   |
| 0x906e9    | 2         | 0.78%   |
| 0x806eb    | 2         | 0.78%   |
| 0x806e9    | 2         | 0.78%   |
| 0x506c9    | 2         | 0.78%   |
| 0x40661    | 2         | 0.78%   |
| 0x10676    | 2         | 0.78%   |
| 0x08600106 | 2         | 0.78%   |
| 0x08101016 | 2         | 0.78%   |
| 0x0800820d | 2         | 0.78%   |
| 0x07030105 | 2         | 0.78%   |
| 0x0700010f | 2         | 0.78%   |
| 0x010000c8 | 2         | 0.78%   |
| 0x906ec    | 1         | 0.39%   |
| 0x906c0    | 1         | 0.39%   |
| 0x706e5    | 1         | 0.39%   |
| 0x6fa      | 1         | 0.39%   |
| 0x6f6      | 1         | 0.39%   |
| 0x306f2    | 1         | 0.39%   |
| 0x306e4    | 1         | 0.39%   |
| 0x30661    | 1         | 0.39%   |
| 0x206c2    | 1         | 0.39%   |
| 0x106e5    | 1         | 0.39%   |
| 0x08701013 | 1         | 0.39%   |
| 0x08608102 | 1         | 0.39%   |
| 0x08600104 | 1         | 0.39%   |
| 0x08001138 | 1         | 0.39%   |
| 0x07030104 | 1         | 0.39%   |
| 0x07000110 | 1         | 0.39%   |
| 0x06006705 | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 34        | 13.33%  |
| Haswell         | 32        | 12.55%  |
| IvyBridge       | 25        | 9.8%    |
| SandyBridge     | 22        | 8.63%   |
| Skylake         | 14        | 5.49%   |
| Core            | 13        | 5.1%    |
| Zen 2           | 12        | 4.71%   |
| Zen+            | 11        | 4.31%   |
| Silvermont      | 11        | 4.31%   |
| Piledriver      | 10        | 3.92%   |
| Westmere        | 8         | 3.14%   |
| Penryn          | 8         | 3.14%   |
| CometLake       | 7         | 2.75%   |
| Puma            | 6         | 2.35%   |
| Broadwell       | 6         | 2.35%   |
| TigerLake       | 5         | 1.96%   |
| Zen             | 4         | 1.57%   |
| Jaguar          | 3         | 1.18%   |
| Goldmont plus   | 3         | 1.18%   |
| Bobcat          | 3         | 1.18%   |
| Nehalem         | 2         | 0.78%   |
| K8 Hammer       | 2         | 0.78%   |
| K10             | 2         | 0.78%   |
| Goldmont        | 2         | 0.78%   |
| Excavator       | 2         | 0.78%   |
| Zen 3           | 1         | 0.39%   |
| Tremont         | 1         | 0.39%   |
| Steamroller     | 1         | 0.39%   |
| K8 & K10 hybrid | 1         | 0.39%   |
| IceLake         | 1         | 0.39%   |
| Bulldozer       | 1         | 0.39%   |
| Bonnell         | 1         | 0.39%   |
| Unknown         | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 49.14%  |
| Nvidia                           | 82        | 28.18%  |
| AMD                              | 65        | 22.34%  |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 5.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.34%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.01%   |
| AMD Picasso                                                                              | 8         | 2.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.67%   |
| Intel HD Graphics 630                                                                    | 5         | 1.67%   |
| Intel HD Graphics 620                                                                    | 5         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.67%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4         | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.34%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.34%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.34%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.34%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 1%      |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1%      |
| Nvidia GK208B [GeForce GT 730]                                                           | 3         | 1%      |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1%      |
| AMD Renoir                                                                               | 3         | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 3         | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.67%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.67%   |
| Intel HD Graphics 530                                                                    | 2         | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.67%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.67%   |
| AMD Trinity 2 [Radeon HD 7540D]                                                          | 2         | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.67%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.67%   |
| AMD Richland [Radeon HD 8650G]                                                           | 2         | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.33%   |
| Nvidia TU117M                                                                            | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.33%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.33%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.33%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.33%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.33%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 43.36%  |
| 1 x Nvidia     | 55        | 21.48%  |
| 1 x AMD        | 54        | 21.09%  |
| Intel + Nvidia | 23        | 8.98%   |
| 2 x AMD        | 4         | 1.56%   |
| Intel + AMD    | 4         | 1.56%   |
| AMD + Nvidia   | 4         | 1.56%   |
| 1 x SiS        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 191       | 74.9%   |
| Proprietary | 56        | 21.96%  |
| Unknown     | 8         | 3.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 52.16%  |
| 1.01-2.0   | 41        | 16.08%  |
| 0.51-1.0   | 27        | 10.59%  |
| 0.01-0.5   | 21        | 8.24%   |
| 3.01-4.0   | 16        | 6.27%   |
| 7.01-8.0   | 7         | 2.75%   |
| 5.01-6.0   | 5         | 1.96%   |
| 2.01-3.0   | 3         | 1.18%   |
| 16.01-24.0 | 1         | 0.39%   |
| 8.01-16.0  | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 35        | 13.57%  |
| AU Optronics            | 32        | 12.4%   |
| Chimei Innolux          | 26        | 10.08%  |
| LG Display              | 22        | 8.53%   |
| BOE                     | 22        | 8.53%   |
| Acer                    | 12        | 4.65%   |
| Goldstar                | 9         | 3.49%   |
| AOC                     | 9         | 3.49%   |
| Sharp                   | 7         | 2.71%   |
| Hewlett-Packard         | 7         | 2.71%   |
| Dell                    | 7         | 2.71%   |
| Apple                   | 7         | 2.71%   |
| Lenovo                  | 6         | 2.33%   |
| Unknown                 | 5         | 1.94%   |
| Philips                 | 5         | 1.94%   |
| Chi Mei Optoelectronics | 5         | 1.94%   |
| BenQ                    | 5         | 1.94%   |
| Vizio                   | 4         | 1.55%   |
| LG Electronics          | 4         | 1.55%   |
| Sony                    | 3         | 1.16%   |
| Ancor Communications    | 3         | 1.16%   |
| Vestel                  | 2         | 0.78%   |
| PANDA                   | 2         | 0.78%   |
| NEC Computers           | 2         | 0.78%   |
| InfoVision              | 2         | 0.78%   |
| Iiyama                  | 2         | 0.78%   |
| Xiaomi                  | 1         | 0.39%   |
| ViewSonic               | 1         | 0.39%   |
| Vestel Elektronik       | 1         | 0.39%   |
| Sceptre Tech            | 1         | 0.39%   |
| LGD                     | 1         | 0.39%   |
| LG Philips              | 1         | 0.39%   |
| HPN                     | 1         | 0.39%   |
| HannStar                | 1         | 0.39%   |
| Gigabyte Technology     | 1         | 0.39%   |
| Gateway                 | 1         | 0.39%   |
| Fujitsu Siemens         | 1         | 0.39%   |
| CPT                     | 1         | 0.39%   |
| AUS                     | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch         | 3         | 1.14%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 3         | 1.14%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                               | 2         | 0.76%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2         | 0.76%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 0.76%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch         | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 340x190mm 15.3-inch         | 2         | 0.76%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch         | 2         | 0.76%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch          | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch           | 2         | 0.76%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch           | 2         | 0.76%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                      | 1         | 0.38%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch               | 1         | 0.38%   |
| Vizio PC VIZCA27 1920x1080 597x336mm 27.0-inch                          | 1         | 0.38%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                     | 1         | 0.38%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.38%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                           | 1         | 0.38%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.38%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                    | 1         | 0.38%   |
| Unknown LCD Monitor RTK                                                 | 1         | 0.38%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                          | 1         | 0.38%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                               | 1         | 0.38%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031                 | 1         | 0.38%   |
| Unknown LCD Monitor GKK MONITOR 1920x1080                               | 1         | 0.38%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                      | 1         | 0.38%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                       | 1         | 0.38%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                         | 1         | 0.38%   |
| Sharp LQ134R1JX48 SHP1528 3840x2400 288x180mm 13.4-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.38%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                 | 1         | 0.38%   |
| Sharp HDMI SHP101E 1920x1080 820x460mm 37.0-inch                        | 1         | 0.38%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1         | 0.38%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch       | 1         | 0.38%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch       | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0604 1920x1080                        | 1         | 0.38%   |
| Samsung Electronics SyncMaster SAM0546 1920x1080 510x287mm 23.0-inch    | 1         | 0.38%   |
| Samsung Electronics S27R65x SAM1046 1920x1080 600x340mm 27.2-inch       | 1         | 0.38%   |
| Samsung Electronics S27R65 SAM1045 1920x1080 598x336mm 27.0-inch        | 1         | 0.38%   |
| Samsung Electronics S27R35A SAM7126 1920x1080 598x336mm 27.0-inch       | 1         | 0.38%   |
| Samsung Electronics S24D300 SAM0B45 1920x1080 521x293mm 23.5-inch       | 1         | 0.38%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1         | 0.38%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1         | 0.38%   |
| Samsung Electronics S19D300 SAM0B34 1280x720 410x230mm 18.5-inch        | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch   | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch    | 1         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 103       | 41.04%  |
| 1366x768 (WXGA)    | 68        | 27.09%  |
| 3840x2160 (4K)     | 19        | 7.57%   |
| 1600x900 (HD+)     | 9         | 3.59%   |
| Unknown            | 7         | 2.79%   |
| 1280x800 (WXGA)    | 5         | 1.99%   |
| 3840x1080          | 4         | 1.59%   |
| 1920x1200 (WUXGA)  | 4         | 1.59%   |
| 3440x1440          | 3         | 1.2%    |
| 2560x1440 (QHD)    | 3         | 1.2%    |
| 3840x2400          | 2         | 0.8%    |
| 2560x1600          | 2         | 0.8%    |
| 1680x1050 (WSXGA+) | 2         | 0.8%    |
| 1440x900 (WXGA+)   | 2         | 0.8%    |
| 1280x1024 (SXGA)   | 2         | 0.8%    |
| 4160x1440          | 1         | 0.4%    |
| 3840x1200          | 1         | 0.4%    |
| 3600x1080          | 1         | 0.4%    |
| 3200x1800 (QHD+)   | 1         | 0.4%    |
| 3120x1050          | 1         | 0.4%    |
| 2944x1080          | 1         | 0.4%    |
| 2880x1800          | 1         | 0.4%    |
| 2464x900           | 1         | 0.4%    |
| 2256x1504          | 1         | 0.4%    |
| 1920x515           | 1         | 0.4%    |
| 1834x1031          | 1         | 0.4%    |
| 1600x1200          | 1         | 0.4%    |
| 1360x768           | 1         | 0.4%    |
| 1280x720 (HD)      | 1         | 0.4%    |
| 1024x768 (XGA)     | 1         | 0.4%    |
| 1024x600           | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 75        | 29.76%  |
| Unknown | 35        | 13.89%  |
| 13      | 29        | 11.51%  |
| 14      | 15        | 5.95%   |
| 27      | 14        | 5.56%   |
| 24      | 13        | 5.16%   |
| 21      | 10        | 3.97%   |
| 17      | 10        | 3.97%   |
| 23      | 8         | 3.17%   |
| 31      | 6         | 2.38%   |
| 18      | 5         | 1.98%   |
| 11      | 5         | 1.98%   |
| 84      | 3         | 1.19%   |
| 34      | 3         | 1.19%   |
| 19      | 3         | 1.19%   |
| 48      | 2         | 0.79%   |
| 46      | 2         | 0.79%   |
| 25      | 2         | 0.79%   |
| 22      | 2         | 0.79%   |
| 74      | 1         | 0.4%    |
| 55      | 1         | 0.4%    |
| 43      | 1         | 0.4%    |
| 41      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 37      | 1         | 0.4%    |
| 36      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |
| 10      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 42.17%  |
| Unknown     | 35        | 14.06%  |
| 501-600     | 34        | 13.65%  |
| 201-300     | 20        | 8.03%   |
| 401-500     | 18        | 7.23%   |
| 351-400     | 12        | 4.82%   |
| 601-700     | 7         | 2.81%   |
| 701-800     | 5         | 2.01%   |
| 1001-1500   | 5         | 2.01%   |
| 1501-2000   | 4         | 1.61%   |
| 801-900     | 2         | 0.8%    |
| 901-1000    | 2         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 173       | 73.93%  |
| Unknown | 33        | 14.1%   |
| 16/10   | 19        | 8.12%   |
| 21/9    | 3         | 1.28%   |
| 4/3     | 2         | 0.85%   |
| 5/4     | 1         | 0.43%   |
| 32/9    | 1         | 0.43%   |
| 3/2     | 1         | 0.43%   |
| 3.73    | 1         | 0.43%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 76        | 30.16%  |
| Unknown        | 35        | 13.89%  |
| 81-90          | 34        | 13.49%  |
| 201-250        | 28        | 11.11%  |
| 301-350        | 14        | 5.56%   |
| 71-80          | 10        | 3.97%   |
| 351-500        | 10        | 3.97%   |
| 121-130        | 8         | 3.17%   |
| 501-1000       | 8         | 3.17%   |
| More than 1000 | 6         | 2.38%   |
| 51-60          | 5         | 1.98%   |
| 251-300        | 5         | 1.98%   |
| 151-200        | 5         | 1.98%   |
| 141-150        | 5         | 1.98%   |
| 41-50          | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 84        | 34.15%  |
| 51-100        | 53        | 21.54%  |
| 121-160       | 50        | 20.33%  |
| Unknown       | 35        | 14.23%  |
| 161-240       | 11        | 4.47%   |
| 1-50          | 7         | 2.85%   |
| More than 240 | 6         | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 219       | 85.21%  |
| 2     | 30        | 11.67%  |
| 0     | 7         | 2.72%   |
| 3     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 145       | 36.99%  |
| Intel                            | 103       | 26.28%  |
| Qualcomm Atheros                 | 55        | 14.03%  |
| Broadcom                         | 26        | 6.63%   |
| Ralink                           | 7         | 1.79%   |
| Broadcom Limited                 | 7         | 1.79%   |
| TP-Link                          | 6         | 1.53%   |
| Ralink Technology                | 6         | 1.53%   |
| Marvell Technology Group         | 5         | 1.28%   |
| DisplayLink                      | 4         | 1.02%   |
| Xiaomi                           | 3         | 0.77%   |
| Samsung Electronics              | 2         | 0.51%   |
| NetGear                          | 2         | 0.51%   |
| MediaTek                         | 2         | 0.51%   |
| D-Link System                    | 2         | 0.51%   |
| ASIX Electronics                 | 2         | 0.51%   |
| ZyXEL Communications             | 1         | 0.26%   |
| T & A Mobile Phones              | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Sierra Wireless                  | 1         | 0.26%   |
| Qualcomm                         | 1         | 0.26%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.26%   |
| Nvidia                           | 1         | 0.26%   |
| Motorola PCS                     | 1         | 0.26%   |
| Linksys                          | 1         | 0.26%   |
| ICS Advent                       | 1         | 0.26%   |
| Huawei Technologies              | 1         | 0.26%   |
| Google                           | 1         | 0.26%   |
| Gemtek                           | 1         | 0.26%   |
| Edimax Technology                | 1         | 0.26%   |
| Dell                             | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 21.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.52%   |
| Intel Wireless 7260                                               | 7         | 1.52%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.3%    |
| Realtek 802.11ac NIC                                              | 5         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.09%   |
| Intel Wireless 8260                                               | 5         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 4         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.87%   |
| Intel WiFi Link 5100                                              | 4         | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.65%   |
| Intel Wireless 3160                                               | 3         | 0.65%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.65%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.65%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.65%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 2         | 0.43%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.43%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.43%   |
| MediaTek TECNO Camon CX                                           | 2         | 0.43%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.43%   |
| Intel Wireless-AC 9260                                            | 2         | 0.43%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.43%   |
| Intel Wireless 7265                                               | 2         | 0.43%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 76        | 36.02%  |
| Realtek Semiconductor | 43        | 20.38%  |
| Qualcomm Atheros      | 41        | 19.43%  |
| Broadcom              | 17        | 8.06%   |
| Ralink                | 7         | 3.32%   |
| TP-Link               | 6         | 2.84%   |
| Ralink Technology     | 6         | 2.84%   |
| Broadcom Limited      | 5         | 2.37%   |
| NetGear               | 2         | 0.95%   |
| ZyXEL Communications  | 1         | 0.47%   |
| Sierra Wireless       | 1         | 0.47%   |
| Qualcomm              | 1         | 0.47%   |
| Linksys               | 1         | 0.47%   |
| Gemtek                | 1         | 0.47%   |
| Edimax Technology     | 1         | 0.47%   |
| Dell                  | 1         | 0.47%   |
| D-Link System         | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 4.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 4.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.29%   |
| Intel Wireless 7260                                            | 7         | 3.29%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.82%   |
| Realtek 802.11ac NIC                                           | 5         | 2.35%   |
| Intel Wireless 8260                                            | 5         | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.35%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 1.88%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.88%   |
| Intel WiFi Link 5100                                           | 4         | 1.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.88%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.41%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.41%   |
| Intel Wireless 3160                                            | 3         | 1.41%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.41%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.41%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.94%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.94%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.94%   |
| Intel Wireless-AC 9260                                         | 2         | 0.94%   |
| Intel Wireless 8265 / 8275                                     | 2         | 0.94%   |
| Intel Wireless 7265                                            | 2         | 0.94%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 0.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.94%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.94%   |
| ZyXEL NWD-270N Wireless N-lite USB Adapter                     | 1         | 0.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.47%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.47%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.47%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 0.47%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 1         | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.47%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.47%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.47%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.47%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1         | 0.47%   |
| Ralink RT2600 802.11 MIMO                                      | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 132       | 54.55%  |
| Intel                            | 50        | 20.66%  |
| Qualcomm Atheros                 | 19        | 7.85%   |
| Broadcom                         | 12        | 4.96%   |
| Marvell Technology Group         | 5         | 2.07%   |
| DisplayLink                      | 4         | 1.65%   |
| Xiaomi                           | 3         | 1.24%   |
| Broadcom Limited                 | 3         | 1.24%   |
| Samsung Electronics              | 2         | 0.83%   |
| MediaTek                         | 2         | 0.83%   |
| ASIX Electronics                 | 2         | 0.83%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.41%   |
| Nvidia                           | 1         | 0.41%   |
| Motorola PCS                     | 1         | 0.41%   |
| ICS Advent                       | 1         | 0.41%   |
| Huawei Technologies              | 1         | 0.41%   |
| Google                           | 1         | 0.41%   |
| D-Link System                    | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 41.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 8.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 6.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.63%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3         | 1.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.22%   |
| Xiaomi SDM660-MTP _SN:6C524624                                    | 2         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.81%   |
| MediaTek TECNO Camon CX                                           | 2         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.81%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.81%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.81%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.41%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 0.41%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.41%   |
| Motorola PCS Moto E (4)                                           | 1         | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.41%   |
| Intel Ethernet controller                                         | 1         | 0.41%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.41%   |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.41%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.41%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.41%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.41%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.41%   |
| Huawei MRD-LX1F                                                   | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 228       | 53.4%   |
| WiFi     | 198       | 46.37%  |
| Unknown  | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 214       | 54.45%  |
| WiFi     | 178       | 45.29%  |
| Unknown  | 1         | 0.25%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 148       | 58.04%  |
| 1     | 99        | 38.82%  |
| 0     | 6         | 2.35%   |
| 3     | 2         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 67.32%  |
| Yes  | 84        | 32.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 36.6%   |
| Realtek Semiconductor           | 18        | 11.76%  |
| Qualcomm Atheros Communications | 17        | 11.11%  |
| Apple                           | 9         | 5.88%   |
| Lite-On Technology              | 8         | 5.23%   |
| IMC Networks                    | 8         | 5.23%   |
| Foxconn / Hon Hai               | 8         | 5.23%   |
| Broadcom                        | 8         | 5.23%   |
| Cambridge Silicon Radio         | 7         | 4.58%   |
| Ralink                          | 3         | 1.96%   |
| Dell                            | 3         | 1.96%   |
| ASUSTek Computer                | 3         | 1.96%   |
| Toshiba                         | 2         | 1.31%   |
| Foxconn International           | 2         | 1.31%   |
| Alps Electric                   | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 11.76%  |
| Intel Bluetooth Device                                                              | 18        | 11.76%  |
| Realtek Bluetooth Radio                                                             | 12        | 7.84%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 7.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 4.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.27%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.27%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.61%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.96%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.96%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.96%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.96%   |
| Apple Bluetooth HCI                                                                 | 3         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.31%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.31%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 1.31%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.31%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 1.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.31%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 1.31%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.31%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.65%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.65%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.65%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.65%   |
| IMC Networks Bluetooth                                                              | 1         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.65%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.65%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.65%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.65%   |
| Dell BT Mini-Receiver                                                               | 1         | 0.65%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.65%   |
| Broadcom Bluetooth                                                                  | 1         | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.65%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 1         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.65%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 187       | 53.58%  |
| AMD                              | 73        | 20.92%  |
| Nvidia                           | 66        | 18.91%  |
| C-Media Electronics              | 5         | 1.43%   |
| Texas Instruments                | 2         | 0.57%   |
| Razer USA                        | 2         | 0.57%   |
| JMTek                            | 2         | 0.57%   |
| Creative Labs                    | 2         | 0.57%   |
| XMOS                             | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Samsung Electronics              | 1         | 0.29%   |
| Numark                           | 1         | 0.29%   |
| Logitech                         | 1         | 0.29%   |
| Klipsch Audio                    | 1         | 0.29%   |
| iConnectivity                    | 1         | 0.29%   |
| GN Netcom                        | 1         | 0.29%   |
| GEMBIRD                          | 1         | 0.29%   |
| Focusrite-Novation               | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 25        | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22        | 5.23%   |
| Intel Sunrise Point-LP HD Audio                                                   | 20        | 4.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17        | 4.04%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                               | 17        | 4.04%   |
| AMD FCH Azalia Controller                                                         | 16        | 3.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 12        | 2.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 11        | 2.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 10        | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                             | 10        | 2.38%   |
| Intel 8 Series HD Audio Controller                                                | 10        | 2.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9         | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9         | 2.14%   |
| AMD Kabini HDMI/DP Audio                                                          | 9         | 2.14%   |
| AMD Starship/Matisse HD Audio Controller                                          | 8         | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 7         | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7         | 1.66%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6         | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                | 6         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 6         | 1.43%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5         | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5         | 1.19%   |
| Nvidia GF119 HDMI Audio Controller                                                | 5         | 1.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 5         | 1.19%   |
| Intel Comet Lake PCH cAVS                                                         | 5         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                        | 5         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 5         | 1.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5         | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5         | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 0.95%   |
| Intel CM238 HD Audio Controller                                                   | 4         | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 4         | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 4         | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3         | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                                     | 3         | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                | 3         | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 3         | 0.71%   |
| AMD Wrestler HDMI Audio                                                           | 3         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                 | 3         | 0.71%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                            | 3         | 0.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 3         | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                                     | 2         | 0.48%   |
| Nvidia GK104 HDMI Audio Controller                                                | 2         | 0.48%   |
| Nvidia Audio device                                                               | 2         | 0.48%   |
| JMTek USB PnP Audio Device                                                        | 2         | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 2         | 0.48%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.48%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 2         | 0.48%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 0.48%   |
| C-Media Electronics USB Advanced Audio Device                                     | 2         | 0.48%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 0.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 0.48%   |
| AMD High Definition Audio Controller                                              | 2         | 0.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 2         | 0.48%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2         | 0.48%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 21.28%  |
| SK Hynix            | 9         | 19.15%  |
| Micron Technology   | 6         | 12.77%  |
| Unknown             | 5         | 10.64%  |
| A-DATA Technology   | 4         | 8.51%   |
| Kingston            | 3         | 6.38%   |
| Ramaxel Technology  | 2         | 4.26%   |
| Crucial             | 2         | 4.26%   |
| Corsair             | 2         | 4.26%   |
| Team                | 1         | 2.13%   |
| Strontium           | 1         | 2.13%   |
| Nanya Technology    | 1         | 2.13%   |
| G.Skill             | 1         | 2.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s        | 2         | 3.7%    |
| A-DATA RAM AE4S240038G17-BHYA 8192MB SODIMM DDR4 2400MT/s        | 2         | 3.7%    |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 1.85%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s          | 1         | 1.85%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 1.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 1.85%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.85%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.85%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s               | 1         | 1.85%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s               | 1         | 1.85%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s             | 1         | 1.85%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s          | 1         | 1.85%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s        | 1         | 1.85%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.85%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.85%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.85%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.85%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.85%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s         | 1         | 1.85%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 1         | 1.85%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 1.85%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.85%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| Samsung RAM M471B2873FHS-CH9 1024MB SODIMM DDR3 1334MT/s         | 1         | 1.85%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.85%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 1         | 1.85%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s         | 1         | 1.85%   |
| Ramaxel RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.85%   |
| Nanya RAM NT1GT64U8HB0BN-3C 1024MB SODIMM DDR 667MT/s            | 1         | 1.85%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s   | 1         | 1.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s    | 1         | 1.85%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.85%   |
| Kingston RAM K821PJ-MID 16384MB SODIMM DDR4 2400MT/s             | 1         | 1.85%   |
| G.Skill RAM F4-3600C19-8GVRB 8192MB DIMM DDR4 2933MT/s           | 1         | 1.85%   |
| Crucial RAM CT8G4SFRA266.C8FJ 8GB SODIMM DDR4 2667MT/s           | 1         | 1.85%   |
| Crucial RAM BL32G32C16S4B.M16FB1 32GB SODIMM DDR4 2667MT/s       | 1         | 1.85%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 1         | 1.85%   |
| Corsair RAM CMD16GX4M2A2666C15 8192MB DIMM DDR4 2667MT/s         | 1         | 1.85%   |
| A-DATA RAM DOVF1B163BE 2048MB SODIMM DDR 800MT/s                 | 1         | 1.85%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4096MB SODIMM DDR4 2400MT/s          | 1         | 1.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 21        | 48.84%  |
| DDR3    | 13        | 30.23%  |
| SDRAM   | 2         | 4.65%   |
| LPDDR4  | 2         | 4.65%   |
| LPDDR3  | 2         | 4.65%   |
| DDR2    | 2         | 4.65%   |
| Unknown | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 68.29%  |
| DIMM         | 8         | 19.51%  |
| Row Of Chips | 5         | 12.2%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 17        | 36.17%  |
| 8192  | 16        | 34.04%  |
| 2048  | 9         | 19.15%  |
| 32768 | 2         | 4.26%   |
| 1024  | 2         | 4.26%   |
| 16384 | 1         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 11        | 23.4%   |
| 2667  | 8         | 17.02%  |
| 3200  | 6         | 12.77%  |
| 2400  | 5         | 10.64%  |
| 1333  | 3         | 6.38%   |
| 4199  | 2         | 4.26%   |
| 2133  | 2         | 4.26%   |
| 1334  | 2         | 4.26%   |
| 667   | 2         | 4.26%   |
| 4267  | 1         | 2.13%   |
| 3266  | 1         | 2.13%   |
| 2933  | 1         | 2.13%   |
| 1867  | 1         | 2.13%   |
| 1067  | 1         | 2.13%   |
| 800   | 1         | 2.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Canon               | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3400 Series         | 1         | 20%     |
| HP OfficeJet 4650 series        | 1         | 20%     |
| HP LaserJet Professional P1102w | 1         | 20%     |
| Canon PIXMA MG2500 Series       | 1         | 20%     |
| Canon LiDE 400                  | 1         | 20%     |

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


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 8800F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 24        | 16.33%  |
| IMC Networks                           | 16        | 10.88%  |
| Realtek Semiconductor                  | 14        | 9.52%   |
| Microdia                               | 13        | 8.84%   |
| Acer                                   | 13        | 8.84%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 7.48%   |
| Sunplus Innovation Technology          | 9         | 6.12%   |
| Suyin                                  | 6         | 4.08%   |
| Quanta                                 | 6         | 4.08%   |
| Lite-On Technology                     | 6         | 4.08%   |
| Apple                                  | 5         | 3.4%    |
| Logitech                               | 3         | 2.04%   |
| Syntek                                 | 2         | 1.36%   |
| Ricoh                                  | 2         | 1.36%   |
| Primax Electronics                     | 2         | 1.36%   |
| Generalplus Technology                 | 2         | 1.36%   |
| Teslong Camera                         | 1         | 0.68%   |
| Silicon Motion                         | 1         | 0.68%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Razer USA                              | 1         | 0.68%   |
| OmniVision Technologies                | 1         | 0.68%   |
| Microsoft                              | 1         | 0.68%   |
| Luxvisions Innotech Limited            | 1         | 0.68%   |
| KYE Systems (Mouse Systems)            | 1         | 0.68%   |
| Jieli Technology                       | 1         | 0.68%   |
| Importek                               | 1         | 0.68%   |
| ARC International                      | 1         | 0.68%   |
| ALi                                    | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 6         | 4.08%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 4.08%   |
| Chicony TOSHIBA Web Camera - HD                     | 5         | 3.4%    |
| Acer Integrated Camera                              | 5         | 3.4%    |
| Microdia Integrated_Webcam_HD                       | 4         | 2.72%   |
| Microdia Integrated Webcam                          | 4         | 2.72%   |
| IMC Networks Integrated Camera                      | 4         | 2.72%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 2.72%   |
| Acer Lenovo EasyCamera                              | 4         | 2.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 2.04%   |
| Chicony Integrated Camera                           | 3         | 2.04%   |
| Chicony HP Truevision HD                            | 3         | 2.04%   |
| Chicony HD WebCam                                   | 3         | 2.04%   |
| Suyin HP Truevision HD                              | 2         | 1.36%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.36%   |
| Sunplus HD WebCam                                   | 2         | 1.36%   |
| Realtek USB Camera                                  | 2         | 1.36%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.36%   |
| Realtek Integrated Webcam                           | 2         | 1.36%   |
| Quanta HD User Facing                               | 2         | 1.36%   |
| Microdia Webcam Vitade AF                           | 2         | 1.36%   |
| Lite-On HP HD Camera                                | 2         | 1.36%   |
| Generalplus GENERAL WEBCAM                          | 2         | 1.36%   |
| Chicony EasyCamera                                  | 2         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 2         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.36%   |
| Teslong Camera Teslong Camera                       | 1         | 0.68%   |
| Syntek USB Camera Device                            | 1         | 0.68%   |
| Syntek Integrated Camera                            | 1         | 0.68%   |
| Suyin WebCam                                        | 1         | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 0.68%   |
| Suyin Acer HD Crystal Eye webcam                    | 1         | 0.68%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.68%   |
| Sunplus Integrated Webcam                           | 1         | 0.68%   |
| Sunplus HP Wide Vision HD                           | 1         | 0.68%   |
| Sunplus HD User Facing                              | 1         | 0.68%   |
| Sunplus Asus Webcam                                 | 1         | 0.68%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.68%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.68%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870] | 1         | 0.68%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.68%   |
| Realtek HD Webcam - Realtek                         | 1         | 0.68%   |
| Realtek HD WebCam                                   | 1         | 0.68%   |
| Razer USA Gaming Webcam [Kiyo]                      | 1         | 0.68%   |
| Quanta VGA WebCam                                   | 1         | 0.68%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 0.68%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.68%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.68%   |
| Primax Villem                                       | 1         | 0.68%   |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.68%   |
| OmniVision OV2640 Webcam                            | 1         | 0.68%   |
| Microsoft Microsoft?‚ LifeCam Cinema                | 1         | 0.68%   |
| Microdia PC Camera (SN9C110)                        | 1         | 0.68%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.68%   |
| Microdia Integrated HD Webcam                       | 1         | 0.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.68%   |
| Logitech Webcam C270                                | 1         | 0.68%   |
| Logitech HD Webcam C910                             | 1         | 0.68%   |
| Logitech HD Pro Webcam C920                         | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 46.67%  |
| Upek                       | 5         | 16.67%  |
| Shenzhen Goodix Technology | 4         | 13.33%  |
| LighTuning Technology      | 2         | 6.67%   |
| Goodix                     | 2         | 6.67%   |
| Synaptics                  | 1         | 3.33%   |
| STMicroelectronics         | 1         | 3.33%   |
| Focal-systems.Corp         | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 10%     |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.67%   |
| Goodix FingerPrint                                                         | 2         | 6.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.33%   |
| Validity Sensors VFS491                                                    | 1         | 3.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.33%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 3.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.33%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.33%   |
| LighTuning Fingerprint Reader                                              | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 57.14%  |
| Alcor Micro | 2         | 28.57%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 28.57%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 176       | 68.75%  |
| 1     | 64        | 25%     |
| 2     | 16        | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 32.26%  |
| Net/wireless             | 22        | 23.66%  |
| Graphics card            | 17        | 18.28%  |
| Multimedia controller    | 8         | 8.6%    |
| Chipcard                 | 5         | 5.38%   |
| Bluetooth                | 3         | 3.23%   |
| Unassigned class         | 1         | 1.08%   |
| Storage                  | 1         | 1.08%   |
| Sound                    | 1         | 1.08%   |
| Net/ethernet             | 1         | 1.08%   |
| Flash memory             | 1         | 1.08%   |
| Dvb card                 | 1         | 1.08%   |
| Communication controller | 1         | 1.08%   |
| Camera                   | 1         | 1.08%   |

