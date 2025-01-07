ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 5445

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | K55VD                       | Notebook    | [d0bc9affdb](https://linux-hardware.org/?probe=d0bc9affdb) | Jan 06, 2025 |
| Lenovo        | ThinkPad X395 20NLS0J400    | Notebook    | [7ff6bae738](https://linux-hardware.org/?probe=7ff6bae738) | Jan 06, 2025 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [f66034865a](https://linux-hardware.org/?probe=f66034865a) | Jan 05, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [b228dff2bb](https://linux-hardware.org/?probe=b228dff2bb) | Jan 05, 2025 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [a9123709a5](https://linux-hardware.org/?probe=a9123709a5) | Jan 05, 2025 |
| Lenovo        | ThinkPad T480s 20L8S0230... | Notebook    | [e6a02c7ad9](https://linux-hardware.org/?probe=e6a02c7ad9) | Jan 04, 2025 |
| ZOTAC         | ZBOX-ID81                   | Mini pc     | [6c6b63aa60](https://linux-hardware.org/?probe=6c6b63aa60) | Jan 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop TP47... | Convertible | [0ec4580ad5](https://linux-hardware.org/?probe=0ec4580ad5) | Jan 04, 2025 |
| ASRock        | 4X4-5000 Series             | Desktop     | [1ff935c41c](https://linux-hardware.org/?probe=1ff935c41c) | Jan 03, 2025 |
| ASRock        | 4X4-5000 Series             | Desktop     | [559f6b8201](https://linux-hardware.org/?probe=559f6b8201) | Jan 03, 2025 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [890bc399f9](https://linux-hardware.org/?probe=890bc399f9) | Jan 03, 2025 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [cd15dad76b](https://linux-hardware.org/?probe=cd15dad76b) | Jan 02, 2025 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [8aefe7b2c7](https://linux-hardware.org/?probe=8aefe7b2c7) | Jan 01, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [173b640d4f](https://linux-hardware.org/?probe=173b640d4f) | Jan 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [2b6b95b19f](https://linux-hardware.org/?probe=2b6b95b19f) | Jan 01, 2025 |
| Dell          | 0M3F6C A01                  | Desktop     | [480dd5a7e1](https://linux-hardware.org/?probe=480dd5a7e1) | Dec 31, 2024 |
| HP            | 3029h                       | Desktop     | [8fb8a4860d](https://linux-hardware.org/?probe=8fb8a4860d) | Dec 31, 2024 |
| Dell          | 0M3F6C A01                  | Desktop     | [2a62b1ff44](https://linux-hardware.org/?probe=2a62b1ff44) | Dec 31, 2024 |
| Acer          | Aspire A317-52              | Notebook    | [8a5d9221e7](https://linux-hardware.org/?probe=8a5d9221e7) | Dec 31, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [aea33edd13](https://linux-hardware.org/?probe=aea33edd13) | Dec 31, 2024 |
| Lenovo        | ThinkPad T560 20FJS1WT00    | Notebook    | [f78acad9fd](https://linux-hardware.org/?probe=f78acad9fd) | Dec 31, 2024 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [3cf042bf3f](https://linux-hardware.org/?probe=3cf042bf3f) | Dec 31, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [319daa2c12](https://linux-hardware.org/?probe=319daa2c12) | Dec 30, 2024 |
| ASRock        | AB350M Pro4                 | Desktop     | [1abbc80099](https://linux-hardware.org/?probe=1abbc80099) | Dec 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [38bd32bd79](https://linux-hardware.org/?probe=38bd32bd79) | Dec 30, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [f238160729](https://linux-hardware.org/?probe=f238160729) | Dec 30, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [00ff33fe24](https://linux-hardware.org/?probe=00ff33fe24) | Dec 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [405fb793dc](https://linux-hardware.org/?probe=405fb793dc) | Dec 29, 2024 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [9ac85fd3e8](https://linux-hardware.org/?probe=9ac85fd3e8) | Dec 28, 2024 |
| MSI           | Z97-G43 GAMING              | Desktop     | [28be42de72](https://linux-hardware.org/?probe=28be42de72) | Dec 28, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [29e44582de](https://linux-hardware.org/?probe=29e44582de) | Dec 28, 2024 |
| Notebook      | NH5xAx                      | Notebook    | [02cccce76f](https://linux-hardware.org/?probe=02cccce76f) | Dec 28, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [c24b7f290f](https://linux-hardware.org/?probe=c24b7f290f) | Dec 27, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [efbbc1e8ad](https://linux-hardware.org/?probe=efbbc1e8ad) | Dec 26, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e544b8e949](https://linux-hardware.org/?probe=e544b8e949) | Dec 25, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [6a859ac63c](https://linux-hardware.org/?probe=6a859ac63c) | Dec 24, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6e1325a330](https://linux-hardware.org/?probe=6e1325a330) | Dec 22, 2024 |
| Intel         | X99                         | Desktop     | [4018709a31](https://linux-hardware.org/?probe=4018709a31) | Dec 22, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6abe074048](https://linux-hardware.org/?probe=6abe074048) | Dec 21, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [28facab032](https://linux-hardware.org/?probe=28facab032) | Dec 21, 2024 |
| Biostar       | H510MHP                     | Desktop     | [344aa9c0da](https://linux-hardware.org/?probe=344aa9c0da) | Dec 21, 2024 |
| HP            | ENVY 15                     | Notebook    | [2bdd1f696d](https://linux-hardware.org/?probe=2bdd1f696d) | Dec 21, 2024 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [2472f683ab](https://linux-hardware.org/?probe=2472f683ab) | Dec 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7519002463](https://linux-hardware.org/?probe=7519002463) | Dec 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ec4fbed784](https://linux-hardware.org/?probe=ec4fbed784) | Dec 21, 2024 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [25d5764264](https://linux-hardware.org/?probe=25d5764264) | Dec 21, 2024 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a50b7373f6](https://linux-hardware.org/?probe=a50b7373f6) | Dec 21, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [5ecba07bcb](https://linux-hardware.org/?probe=5ecba07bcb) | Dec 21, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [2f18fb67da](https://linux-hardware.org/?probe=2f18fb67da) | Dec 21, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [de4d92e726](https://linux-hardware.org/?probe=de4d92e726) | Dec 20, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [2cb901e525](https://linux-hardware.org/?probe=2cb901e525) | Dec 20, 2024 |
| Lenovo        | ThinkPad W540 20BHS14J0J    | Notebook    | [4bfbb1305a](https://linux-hardware.org/?probe=4bfbb1305a) | Dec 20, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [a2c7b2e72e](https://linux-hardware.org/?probe=a2c7b2e72e) | Dec 20, 2024 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [73af2fce67](https://linux-hardware.org/?probe=73af2fce67) | Dec 20, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [54970d3023](https://linux-hardware.org/?probe=54970d3023) | Dec 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2e97ec9da3](https://linux-hardware.org/?probe=2e97ec9da3) | Dec 19, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [85527618fc](https://linux-hardware.org/?probe=85527618fc) | Dec 19, 2024 |
| Lenovo        | 3777 WIN SDK0T76463 3422... | All in one  | [ed33639be3](https://linux-hardware.org/?probe=ed33639be3) | Dec 19, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [a31e7950da](https://linux-hardware.org/?probe=a31e7950da) | Dec 19, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [20a921dcdd](https://linux-hardware.org/?probe=20a921dcdd) | Dec 18, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [5ec2022b69](https://linux-hardware.org/?probe=5ec2022b69) | Dec 18, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [8bdebb5383](https://linux-hardware.org/?probe=8bdebb5383) | Dec 17, 2024 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [4ec2092033](https://linux-hardware.org/?probe=4ec2092033) | Dec 17, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [6f354f73aa](https://linux-hardware.org/?probe=6f354f73aa) | Dec 16, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [524c33e748](https://linux-hardware.org/?probe=524c33e748) | Dec 16, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a8053e70d7](https://linux-hardware.org/?probe=a8053e70d7) | Dec 16, 2024 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [634639adbc](https://linux-hardware.org/?probe=634639adbc) | Dec 15, 2024 |
| Biostar       | IH61MF-Q5                   | Desktop     | [4ff0b038b3](https://linux-hardware.org/?probe=4ff0b038b3) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [98e4e31c99](https://linux-hardware.org/?probe=98e4e31c99) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [8c4e0cc970](https://linux-hardware.org/?probe=8c4e0cc970) | Dec 15, 2024 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [80eb154594](https://linux-hardware.org/?probe=80eb154594) | Dec 15, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [37def171f5](https://linux-hardware.org/?probe=37def171f5) | Dec 14, 2024 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [fb3d972ca7](https://linux-hardware.org/?probe=fb3d972ca7) | Dec 14, 2024 |
| Lenovo        | ThinkPad A485 20MVS08500    | Notebook    | [64a9a91c57](https://linux-hardware.org/?probe=64a9a91c57) | Dec 14, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [a7ba503bce](https://linux-hardware.org/?probe=a7ba503bce) | Dec 13, 2024 |
| Google        | Cyan                        | Notebook    | [07d137b1c9](https://linux-hardware.org/?probe=07d137b1c9) | Dec 13, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [b5eb8e7554](https://linux-hardware.org/?probe=b5eb8e7554) | Dec 13, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [0b9d7716cd](https://linux-hardware.org/?probe=0b9d7716cd) | Dec 13, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [9c3c2fb92b](https://linux-hardware.org/?probe=9c3c2fb92b) | Dec 13, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [8fab92cc9d](https://linux-hardware.org/?probe=8fab92cc9d) | Dec 12, 2024 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [950033e6a5](https://linux-hardware.org/?probe=950033e6a5) | Dec 12, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [dba79b373a](https://linux-hardware.org/?probe=dba79b373a) | Dec 12, 2024 |
| HP            | 8053                        | Desktop     | [b9284c32ad](https://linux-hardware.org/?probe=b9284c32ad) | Dec 11, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [c4f5feb755](https://linux-hardware.org/?probe=c4f5feb755) | Dec 11, 2024 |
| HP            | 8053                        | Desktop     | [0f305b9d7f](https://linux-hardware.org/?probe=0f305b9d7f) | Dec 11, 2024 |
| ASUSTek       | X205TA                      | Notebook    | [5bd8e61a56](https://linux-hardware.org/?probe=5bd8e61a56) | Dec 10, 2024 |
| Acer          | Aspire A317-52              | Notebook    | [9523b85250](https://linux-hardware.org/?probe=9523b85250) | Dec 10, 2024 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [d51d33b4aa](https://linux-hardware.org/?probe=d51d33b4aa) | Dec 10, 2024 |
| Dell          | Latitude E7470              | Notebook    | [b683114583](https://linux-hardware.org/?probe=b683114583) | Dec 10, 2024 |
| ASUSTek       | UX305CA                     | Notebook    | [826fafd993](https://linux-hardware.org/?probe=826fafd993) | Dec 09, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c4d956f844](https://linux-hardware.org/?probe=c4d956f844) | Dec 09, 2024 |
| Gigabyte      | B650 UD AC-Y1               | Desktop     | [c21b83dc80](https://linux-hardware.org/?probe=c21b83dc80) | Dec 09, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [53d86bd60f](https://linux-hardware.org/?probe=53d86bd60f) | Dec 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [33643facc4](https://linux-hardware.org/?probe=33643facc4) | Dec 08, 2024 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [41278492e7](https://linux-hardware.org/?probe=41278492e7) | Dec 07, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d45c582a18](https://linux-hardware.org/?probe=d45c582a18) | Dec 07, 2024 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [cda9658f32](https://linux-hardware.org/?probe=cda9658f32) | Dec 06, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [cb9e678fc7](https://linux-hardware.org/?probe=cb9e678fc7) | Dec 05, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [7e5c438d1a](https://linux-hardware.org/?probe=7e5c438d1a) | Dec 05, 2024 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [8270c3a002](https://linux-hardware.org/?probe=8270c3a002) | Dec 05, 2024 |
| Lenovo        | 318E SDK0T76530 WIN 3556... | Desktop     | [fc10338586](https://linux-hardware.org/?probe=fc10338586) | Dec 04, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2277464b80](https://linux-hardware.org/?probe=2277464b80) | Dec 04, 2024 |
| Lenovo        | 318E SDK0T76530 WIN 3556... | Desktop     | [3970b3f161](https://linux-hardware.org/?probe=3970b3f161) | Dec 04, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [291629dda6](https://linux-hardware.org/?probe=291629dda6) | Dec 03, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [f880b60a76](https://linux-hardware.org/?probe=f880b60a76) | Dec 03, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [43eaee20f2](https://linux-hardware.org/?probe=43eaee20f2) | Dec 03, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [e556a40293](https://linux-hardware.org/?probe=e556a40293) | Dec 03, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [33eb230c2a](https://linux-hardware.org/?probe=33eb230c2a) | Dec 03, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0b71bb31ea](https://linux-hardware.org/?probe=0b71bb31ea) | Dec 03, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | Notebook    | [ad86291778](https://linux-hardware.org/?probe=ad86291778) | Dec 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | Notebook    | [d36311286b](https://linux-hardware.org/?probe=d36311286b) | Dec 02, 2024 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [6a87bc023b](https://linux-hardware.org/?probe=6a87bc023b) | Dec 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [9eddfe9de4](https://linux-hardware.org/?probe=9eddfe9de4) | Dec 02, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [6a5dd9d520](https://linux-hardware.org/?probe=6a5dd9d520) | Dec 01, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [0d619706e0](https://linux-hardware.org/?probe=0d619706e0) | Dec 01, 2024 |
| Lenovo        | NOK                         | Desktop     | [1181589067](https://linux-hardware.org/?probe=1181589067) | Dec 01, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c751e5836a](https://linux-hardware.org/?probe=c751e5836a) | Dec 01, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [b18d4ba53a](https://linux-hardware.org/?probe=b18d4ba53a) | Nov 30, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [767c9d535d](https://linux-hardware.org/?probe=767c9d535d) | Nov 30, 2024 |
| Dell          | Inspiron 5759               | Notebook    | [fc9f572f22](https://linux-hardware.org/?probe=fc9f572f22) | Nov 30, 2024 |
| HP            | Notebook                    | Notebook    | [7bc5ba9b86](https://linux-hardware.org/?probe=7bc5ba9b86) | Nov 30, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [80d6c8ab76](https://linux-hardware.org/?probe=80d6c8ab76) | Nov 30, 2024 |
| Gigabyte      | Z270X-Gaming 7              | Desktop     | [47e2ee96e9](https://linux-hardware.org/?probe=47e2ee96e9) | Nov 30, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [751428f37c](https://linux-hardware.org/?probe=751428f37c) | Nov 29, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [03b7e73d38](https://linux-hardware.org/?probe=03b7e73d38) | Nov 29, 2024 |
| Lenovo        | ThinkPad R500 2718W3V       | Notebook    | [3804c95f6f](https://linux-hardware.org/?probe=3804c95f6f) | Nov 29, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bebca26775](https://linux-hardware.org/?probe=bebca26775) | Nov 29, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [cd2b9033b8](https://linux-hardware.org/?probe=cd2b9033b8) | Nov 28, 2024 |
| Lenovo        | RESCUER R720-15IKBN 80WW    | Notebook    | [0e9a9bef8d](https://linux-hardware.org/?probe=0e9a9bef8d) | Nov 28, 2024 |
| Dell          | Precision 7520              | Notebook    | [414d389f1b](https://linux-hardware.org/?probe=414d389f1b) | Nov 28, 2024 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [16fb8ac1cf](https://linux-hardware.org/?probe=16fb8ac1cf) | Nov 27, 2024 |
| Dell          | Latitude E6320              | Notebook    | [4796ce988e](https://linux-hardware.org/?probe=4796ce988e) | Nov 27, 2024 |
| HP            | 8951                        | Desktop     | [742889b10a](https://linux-hardware.org/?probe=742889b10a) | Nov 27, 2024 |
| MSI           | GS43VR 7RE                  | Notebook    | [420a91c666](https://linux-hardware.org/?probe=420a91c666) | Nov 27, 2024 |
| Dell          | Inspiron 5590               | Notebook    | [6849528aa9](https://linux-hardware.org/?probe=6849528aa9) | Nov 27, 2024 |
| Samsung       | 940XGK                      | Notebook    | [2cd0f44890](https://linux-hardware.org/?probe=2cd0f44890) | Nov 26, 2024 |
| ASRock        | A300M-STX                   | Desktop     | [07fe25b59a](https://linux-hardware.org/?probe=07fe25b59a) | Nov 25, 2024 |
| Lenovo        | ThinkPad W540 20BHS14J0J    | Notebook    | [5f77ea0b14](https://linux-hardware.org/?probe=5f77ea0b14) | Nov 25, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [bd42e89f36](https://linux-hardware.org/?probe=bd42e89f36) | Nov 25, 2024 |
| ASRock        | J3355B-ITX                  | Desktop     | [a518434234](https://linux-hardware.org/?probe=a518434234) | Nov 25, 2024 |
| JGINYUE       | X99-D8 Server V1.0          | Desktop     | [3f50efb197](https://linux-hardware.org/?probe=3f50efb197) | Nov 24, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e7dd6ffefe](https://linux-hardware.org/?probe=e7dd6ffefe) | Nov 24, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [98d3557c1e](https://linux-hardware.org/?probe=98d3557c1e) | Nov 24, 2024 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [f8ba79bd9c](https://linux-hardware.org/?probe=f8ba79bd9c) | Nov 23, 2024 |
| Lenovo        | ThinkPad W540 20BHS0620V    | Notebook    | [e473ec9a1b](https://linux-hardware.org/?probe=e473ec9a1b) | Nov 23, 2024 |
| Dell          | 0M3F6C A01                  | Desktop     | [0fa1bd4afb](https://linux-hardware.org/?probe=0fa1bd4afb) | Nov 23, 2024 |
| Acer          | TMP455-M                    | Notebook    | [2634525f74](https://linux-hardware.org/?probe=2634525f74) | Nov 22, 2024 |
| Acer          | TMP455-M                    | Notebook    | [eb61c20a0f](https://linux-hardware.org/?probe=eb61c20a0f) | Nov 22, 2024 |
| HP            | 2B0D A01                    | All in one  | [d728d14499](https://linux-hardware.org/?probe=d728d14499) | Nov 22, 2024 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [a6c7dc11fa](https://linux-hardware.org/?probe=a6c7dc11fa) | Nov 22, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [37b4074a42](https://linux-hardware.org/?probe=37b4074a42) | Nov 21, 2024 |
| AZW           | GTR V01                     | Mini pc     | [013e6e0944](https://linux-hardware.org/?probe=013e6e0944) | Nov 20, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [7c51dc9811](https://linux-hardware.org/?probe=7c51dc9811) | Nov 20, 2024 |
| HP            | Pavilion dv7                | Notebook    | [173de4914d](https://linux-hardware.org/?probe=173de4914d) | Nov 20, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [ded486b775](https://linux-hardware.org/?probe=ded486b775) | Nov 18, 2024 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [44e416674c](https://linux-hardware.org/?probe=44e416674c) | Nov 17, 2024 |
| Intel Clie... | LAPQC71B                    | Notebook    | [5db38e2711](https://linux-hardware.org/?probe=5db38e2711) | Nov 17, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [22fd04f7ee](https://linux-hardware.org/?probe=22fd04f7ee) | Nov 17, 2024 |
| ECS           | H110M4-C43                  | Desktop     | [f68d39f617](https://linux-hardware.org/?probe=f68d39f617) | Nov 17, 2024 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [1971287fa0](https://linux-hardware.org/?probe=1971287fa0) | Nov 17, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [2c760ab64f](https://linux-hardware.org/?probe=2c760ab64f) | Nov 17, 2024 |
| Dell          | Latitude 5520               | Notebook    | [007adcd9ad](https://linux-hardware.org/?probe=007adcd9ad) | Nov 16, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ad30ba36ce](https://linux-hardware.org/?probe=ad30ba36ce) | Nov 16, 2024 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [976962bd2c](https://linux-hardware.org/?probe=976962bd2c) | Nov 15, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [561df0051a](https://linux-hardware.org/?probe=561df0051a) | Nov 15, 2024 |
| Dell          | Latitude E6500              | Notebook    | [db92f98536](https://linux-hardware.org/?probe=db92f98536) | Nov 15, 2024 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [bd4c200cbb](https://linux-hardware.org/?probe=bd4c200cbb) | Nov 15, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e89b4f9ddd](https://linux-hardware.org/?probe=e89b4f9ddd) | Nov 15, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [83ea680cc0](https://linux-hardware.org/?probe=83ea680cc0) | Nov 14, 2024 |
| ECS           | H110M4-C43                  | Desktop     | [83e2429bf4](https://linux-hardware.org/?probe=83e2429bf4) | Nov 14, 2024 |
| Lenovo        | ThinkPad W540 20BHS0620V    | Notebook    | [969a725e1e](https://linux-hardware.org/?probe=969a725e1e) | Nov 14, 2024 |
| ASRock        | X600M-STX                   | Desktop     | [c16fbb9c2c](https://linux-hardware.org/?probe=c16fbb9c2c) | Nov 13, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [41b2d06822](https://linux-hardware.org/?probe=41b2d06822) | Nov 13, 2024 |
| HP            | 2B0D A01                    | All in one  | [7164f8f49b](https://linux-hardware.org/?probe=7164f8f49b) | Nov 13, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [e3b498b57a](https://linux-hardware.org/?probe=e3b498b57a) | Nov 12, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [ae3218fa93](https://linux-hardware.org/?probe=ae3218fa93) | Nov 12, 2024 |
| Medion        | P7816                       | Notebook    | [58ec8f58ec](https://linux-hardware.org/?probe=58ec8f58ec) | Nov 12, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [583860bb6e](https://linux-hardware.org/?probe=583860bb6e) | Nov 12, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ccf9df80ca](https://linux-hardware.org/?probe=ccf9df80ca) | Nov 11, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [d14a8b1c68](https://linux-hardware.org/?probe=d14a8b1c68) | Nov 11, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [5fb9bf3774](https://linux-hardware.org/?probe=5fb9bf3774) | Nov 11, 2024 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ccf5f021fa](https://linux-hardware.org/?probe=ccf5f021fa) | Nov 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7ed44ec1d3](https://linux-hardware.org/?probe=7ed44ec1d3) | Nov 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [b1bda06aca](https://linux-hardware.org/?probe=b1bda06aca) | Nov 10, 2024 |
| ASUSTek       | PRIME B760M-A AX            | Desktop     | [1af3427ba7](https://linux-hardware.org/?probe=1af3427ba7) | Nov 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [913257fc83](https://linux-hardware.org/?probe=913257fc83) | Nov 09, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [f33ffb3943](https://linux-hardware.org/?probe=f33ffb3943) | Nov 09, 2024 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [a3df47c0e2](https://linux-hardware.org/?probe=a3df47c0e2) | Nov 08, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [25543c5070](https://linux-hardware.org/?probe=25543c5070) | Nov 08, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [d05ecd9f91](https://linux-hardware.org/?probe=d05ecd9f91) | Nov 08, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [05c250783f](https://linux-hardware.org/?probe=05c250783f) | Nov 07, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [db705d3a4b](https://linux-hardware.org/?probe=db705d3a4b) | Nov 07, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [0c1e400e1f](https://linux-hardware.org/?probe=0c1e400e1f) | Nov 07, 2024 |
| Gigabyte      | Z790 AORUS ELITE AX-W       | Desktop     | [1533a22e66](https://linux-hardware.org/?probe=1533a22e66) | Nov 06, 2024 |
| Dell          | 0VTJVC A00                  | Desktop     | [e95dd1e5ab](https://linux-hardware.org/?probe=e95dd1e5ab) | Nov 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [2be2989e95](https://linux-hardware.org/?probe=2be2989e95) | Nov 05, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [b04dd94b4f](https://linux-hardware.org/?probe=b04dd94b4f) | Nov 04, 2024 |
| Unknown       | Unknown                     | Notebook    | [c7f9fb9e1a](https://linux-hardware.org/?probe=c7f9fb9e1a) | Nov 04, 2024 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [386606f6bd](https://linux-hardware.org/?probe=386606f6bd) | Nov 04, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [62ad9febaa](https://linux-hardware.org/?probe=62ad9febaa) | Nov 04, 2024 |
| Dell          | 0VTJVC A00                  | Desktop     | [01b2ef1315](https://linux-hardware.org/?probe=01b2ef1315) | Nov 03, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [4690d07a14](https://linux-hardware.org/?probe=4690d07a14) | Nov 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [34d06fac26](https://linux-hardware.org/?probe=34d06fac26) | Nov 02, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [be82de4944](https://linux-hardware.org/?probe=be82de4944) | Nov 01, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [5736e11451](https://linux-hardware.org/?probe=5736e11451) | Oct 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c49f5edf81](https://linux-hardware.org/?probe=c49f5edf81) | Oct 31, 2024 |
| Lenovo        | ThinkPad X280 20KESEYC00    | Notebook    | [bc3e6aa2dc](https://linux-hardware.org/?probe=bc3e6aa2dc) | Oct 30, 2024 |
| Lenovo        | ThinkPad T490s 20NYS3L72... | Notebook    | [f8310dbb63](https://linux-hardware.org/?probe=f8310dbb63) | Oct 30, 2024 |
| Lenovo        | ThinkCentre M81 M 5049-Y... | Desktop     | [e6e78d2a35](https://linux-hardware.org/?probe=e6e78d2a35) | Oct 30, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [605574a95c](https://linux-hardware.org/?probe=605574a95c) | Oct 29, 2024 |
| MSI           | H410M PRO-VH                | Desktop     | [11a6d15fa6](https://linux-hardware.org/?probe=11a6d15fa6) | Oct 29, 2024 |
| MSI           | Z370 GAMING M5              | Desktop     | [40c5892fdd](https://linux-hardware.org/?probe=40c5892fdd) | Oct 29, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [1afede481b](https://linux-hardware.org/?probe=1afede481b) | Oct 29, 2024 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [3648083e1b](https://linux-hardware.org/?probe=3648083e1b) | Oct 28, 2024 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [cbebfa258b](https://linux-hardware.org/?probe=cbebfa258b) | Oct 28, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [35db8c4932](https://linux-hardware.org/?probe=35db8c4932) | Oct 28, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6f3cddbb64](https://linux-hardware.org/?probe=6f3cddbb64) | Oct 28, 2024 |
| Acer          | Predator G3-605             | Desktop     | [82a4e8511c](https://linux-hardware.org/?probe=82a4e8511c) | Oct 28, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [3f0aba2e5b](https://linux-hardware.org/?probe=3f0aba2e5b) | Oct 28, 2024 |
| Unknown       | Unknown                     | Desktop     | [eb20d7508d](https://linux-hardware.org/?probe=eb20d7508d) | Oct 25, 2024 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [5692ef7249](https://linux-hardware.org/?probe=5692ef7249) | Oct 25, 2024 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5c0a3f88cf](https://linux-hardware.org/?probe=5c0a3f88cf) | Oct 24, 2024 |
| Dell          | Latitude E5540              | Notebook    | [da1eff5497](https://linux-hardware.org/?probe=da1eff5497) | Oct 24, 2024 |
| Unknown       | Unknown                     | Notebook    | [af08761713](https://linux-hardware.org/?probe=af08761713) | Oct 24, 2024 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [7d14ffe3bb](https://linux-hardware.org/?probe=7d14ffe3bb) | Oct 23, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [632d66a3f3](https://linux-hardware.org/?probe=632d66a3f3) | Oct 23, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [82324c101a](https://linux-hardware.org/?probe=82324c101a) | Oct 22, 2024 |
| ASRock        | B450 Steel Legend           | Desktop     | [ca46c5b67a](https://linux-hardware.org/?probe=ca46c5b67a) | Oct 22, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [258537d343](https://linux-hardware.org/?probe=258537d343) | Oct 22, 2024 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [1f2717878d](https://linux-hardware.org/?probe=1f2717878d) | Oct 22, 2024 |
| Dell          | Inspiron 7386               | Convertible | [7c1113ca1e](https://linux-hardware.org/?probe=7c1113ca1e) | Oct 22, 2024 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [945da5a2f2](https://linux-hardware.org/?probe=945da5a2f2) | Oct 21, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0f3d9053e1](https://linux-hardware.org/?probe=0f3d9053e1) | Oct 21, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0915e50195](https://linux-hardware.org/?probe=0915e50195) | Oct 21, 2024 |
| MSI           | Modern 14 B10MW             | Notebook    | [7f701f4c7e](https://linux-hardware.org/?probe=7f701f4c7e) | Oct 21, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [d2070e6e2d](https://linux-hardware.org/?probe=d2070e6e2d) | Oct 20, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [1b092c455a](https://linux-hardware.org/?probe=1b092c455a) | Oct 20, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [c3ac26fbb4](https://linux-hardware.org/?probe=c3ac26fbb4) | Oct 20, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [8886e7de9c](https://linux-hardware.org/?probe=8886e7de9c) | Oct 20, 2024 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [0013e23e0e](https://linux-hardware.org/?probe=0013e23e0e) | Oct 20, 2024 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [a6733a4c0c](https://linux-hardware.org/?probe=a6733a4c0c) | Oct 20, 2024 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [d0a34284ae](https://linux-hardware.org/?probe=d0a34284ae) | Oct 20, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [7f72600a21](https://linux-hardware.org/?probe=7f72600a21) | Oct 20, 2024 |
| HP            | 86EE                        | All in one  | [b32f215a0e](https://linux-hardware.org/?probe=b32f215a0e) | Oct 19, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [454576f29c](https://linux-hardware.org/?probe=454576f29c) | Oct 19, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1fb4ba033c](https://linux-hardware.org/?probe=1fb4ba033c) | Oct 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [abab79db3c](https://linux-hardware.org/?probe=abab79db3c) | Oct 19, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [e041b45976](https://linux-hardware.org/?probe=e041b45976) | Oct 19, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [b56d767db4](https://linux-hardware.org/?probe=b56d767db4) | Oct 19, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e6d3630bb4](https://linux-hardware.org/?probe=e6d3630bb4) | Oct 19, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [f19e331117](https://linux-hardware.org/?probe=f19e331117) | Oct 19, 2024 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [57d65c1142](https://linux-hardware.org/?probe=57d65c1142) | Oct 19, 2024 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [7f08763473](https://linux-hardware.org/?probe=7f08763473) | Oct 19, 2024 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [f3ed5c74a3](https://linux-hardware.org/?probe=f3ed5c74a3) | Oct 19, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [bf00a67abe](https://linux-hardware.org/?probe=bf00a67abe) | Oct 19, 2024 |
| ASRock        | B250M Pro4                  | Desktop     | [d920080f25](https://linux-hardware.org/?probe=d920080f25) | Oct 19, 2024 |
| ASRock        | B250M Pro4                  | Desktop     | [29b043cb95](https://linux-hardware.org/?probe=29b043cb95) | Oct 19, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0be150631e](https://linux-hardware.org/?probe=0be150631e) | Oct 19, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [385b656d3b](https://linux-hardware.org/?probe=385b656d3b) | Oct 19, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [23b3c6dbf9](https://linux-hardware.org/?probe=23b3c6dbf9) | Oct 18, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [3076359295](https://linux-hardware.org/?probe=3076359295) | Oct 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [bfc19a1c40](https://linux-hardware.org/?probe=bfc19a1c40) | Oct 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1c4e2fa10c](https://linux-hardware.org/?probe=1c4e2fa10c) | Oct 17, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [7cd0767236](https://linux-hardware.org/?probe=7cd0767236) | Oct 16, 2024 |
| MSI           | Katana 15 B13VGK            | Notebook    | [84060518eb](https://linux-hardware.org/?probe=84060518eb) | Oct 16, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [ab61c7e029](https://linux-hardware.org/?probe=ab61c7e029) | Oct 16, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [ffc8702d4a](https://linux-hardware.org/?probe=ffc8702d4a) | Oct 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [2a70c8af1b](https://linux-hardware.org/?probe=2a70c8af1b) | Oct 16, 2024 |
| Gigabyte      | B650 EAGLE AX               | Desktop     | [c3b6e7482d](https://linux-hardware.org/?probe=c3b6e7482d) | Oct 15, 2024 |
| Dell          | Latitude E6230              | Notebook    | [3f841532de](https://linux-hardware.org/?probe=3f841532de) | Oct 14, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [12e66fbbf2](https://linux-hardware.org/?probe=12e66fbbf2) | Oct 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [ec688a0cae](https://linux-hardware.org/?probe=ec688a0cae) | Oct 13, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [38ada20a08](https://linux-hardware.org/?probe=38ada20a08) | Oct 13, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [ee6df68e2a](https://linux-hardware.org/?probe=ee6df68e2a) | Oct 13, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [f2d560b192](https://linux-hardware.org/?probe=f2d560b192) | Oct 12, 2024 |
| AZW           | SER V1                      | Desktop     | [b309637493](https://linux-hardware.org/?probe=b309637493) | Oct 11, 2024 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [a87a56e961](https://linux-hardware.org/?probe=a87a56e961) | Oct 11, 2024 |
| Dell          | Latitude 5420               | Notebook    | [622540975d](https://linux-hardware.org/?probe=622540975d) | Oct 10, 2024 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [da3ad9fe6c](https://linux-hardware.org/?probe=da3ad9fe6c) | Oct 10, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [67a788fa83](https://linux-hardware.org/?probe=67a788fa83) | Oct 10, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f108ee0d16](https://linux-hardware.org/?probe=f108ee0d16) | Oct 10, 2024 |
| AZW           | SER V1                      | Desktop     | [7ccd942fc1](https://linux-hardware.org/?probe=7ccd942fc1) | Oct 10, 2024 |
| HP            | 802F                        | Desktop     | [2678cdc4b4](https://linux-hardware.org/?probe=2678cdc4b4) | Oct 10, 2024 |
| ASUSTek       | X556UQK                     | Notebook    | [b5e78247a7](https://linux-hardware.org/?probe=b5e78247a7) | Oct 09, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [527a8fe27c](https://linux-hardware.org/?probe=527a8fe27c) | Oct 09, 2024 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [0261150227](https://linux-hardware.org/?probe=0261150227) | Oct 09, 2024 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [52e52f0167](https://linux-hardware.org/?probe=52e52f0167) | Oct 09, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [bfa8131b20](https://linux-hardware.org/?probe=bfa8131b20) | Oct 09, 2024 |
| HP            | 2B0D A01                    | All in one  | [e08e3b81b2](https://linux-hardware.org/?probe=e08e3b81b2) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b02ac16d4e](https://linux-hardware.org/?probe=b02ac16d4e) | Oct 08, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [4d89b5ebcb](https://linux-hardware.org/?probe=4d89b5ebcb) | Oct 08, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [222b41c35d](https://linux-hardware.org/?probe=222b41c35d) | Oct 08, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [a0ce848ae5](https://linux-hardware.org/?probe=a0ce848ae5) | Oct 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [81e045d718](https://linux-hardware.org/?probe=81e045d718) | Oct 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [6d3e3dc090](https://linux-hardware.org/?probe=6d3e3dc090) | Oct 07, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [4068a6c8c4](https://linux-hardware.org/?probe=4068a6c8c4) | Oct 06, 2024 |
| Fujitsu       | LIFEBOOK U729               | Notebook    | [15f399627a](https://linux-hardware.org/?probe=15f399627a) | Oct 06, 2024 |
| Dell          | Inspiron 3551               | Notebook    | [1a59d5c1ee](https://linux-hardware.org/?probe=1a59d5c1ee) | Oct 05, 2024 |
| Dell          | Inspiron 7520               | Notebook    | [b222dbff7d](https://linux-hardware.org/?probe=b222dbff7d) | Oct 04, 2024 |
| Dell          | Latitude 7390               | Notebook    | [89ac346e1f](https://linux-hardware.org/?probe=89ac346e1f) | Oct 04, 2024 |
| Dell          | Precision 7540              | Notebook    | [e77f5beae9](https://linux-hardware.org/?probe=e77f5beae9) | Oct 03, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [094b929092](https://linux-hardware.org/?probe=094b929092) | Oct 03, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [bdc1ce0ed5](https://linux-hardware.org/?probe=bdc1ce0ed5) | Oct 03, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [0fe758dc03](https://linux-hardware.org/?probe=0fe758dc03) | Oct 03, 2024 |
| Lenovo        | Yoga Pro 7 14AHP9 83E3      | Notebook    | [ed0a6b20fe](https://linux-hardware.org/?probe=ed0a6b20fe) | Oct 02, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [2b916500bc](https://linux-hardware.org/?probe=2b916500bc) | Oct 01, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [226c453497](https://linux-hardware.org/?probe=226c453497) | Oct 01, 2024 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [5133bf5060](https://linux-hardware.org/?probe=5133bf5060) | Oct 01, 2024 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [693a1a45df](https://linux-hardware.org/?probe=693a1a45df) | Oct 01, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [1183c6ec8f](https://linux-hardware.org/?probe=1183c6ec8f) | Oct 01, 2024 |
| Dell          | G7 7588                     | Notebook    | [a05740b926](https://linux-hardware.org/?probe=a05740b926) | Oct 01, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [dd40f4370a](https://linux-hardware.org/?probe=dd40f4370a) | Sep 30, 2024 |
| Unknown       | Unknown                     | Notebook    | [b2607af0bf](https://linux-hardware.org/?probe=b2607af0bf) | Sep 30, 2024 |
| HP            | Folio 13                    | Notebook    | [83bf0a4e66](https://linux-hardware.org/?probe=83bf0a4e66) | Sep 30, 2024 |
| MSI           | X99A GODLIKE GAMING CARB... | Desktop     | [832c7301cc](https://linux-hardware.org/?probe=832c7301cc) | Sep 29, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [1d55438162](https://linux-hardware.org/?probe=1d55438162) | Sep 29, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [8815e16a5e](https://linux-hardware.org/?probe=8815e16a5e) | Sep 29, 2024 |
| Timi          | Mi NoteBook 14              | Notebook    | [7e9cbce7a8](https://linux-hardware.org/?probe=7e9cbce7a8) | Sep 29, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [ecd54eabf9](https://linux-hardware.org/?probe=ecd54eabf9) | Sep 29, 2024 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [f726485cd0](https://linux-hardware.org/?probe=f726485cd0) | Sep 29, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2a63def166](https://linux-hardware.org/?probe=2a63def166) | Sep 29, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [a0c44a617b](https://linux-hardware.org/?probe=a0c44a617b) | Sep 28, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [5f718e6c39](https://linux-hardware.org/?probe=5f718e6c39) | Sep 28, 2024 |
| HP            | 1998                        | Desktop     | [86b5dfa46a](https://linux-hardware.org/?probe=86b5dfa46a) | Sep 27, 2024 |
| HP            | 1998                        | Desktop     | [a270bc41e8](https://linux-hardware.org/?probe=a270bc41e8) | Sep 27, 2024 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [30221d4c1c](https://linux-hardware.org/?probe=30221d4c1c) | Sep 27, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7139de484e](https://linux-hardware.org/?probe=7139de484e) | Sep 27, 2024 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [123ae02ef6](https://linux-hardware.org/?probe=123ae02ef6) | Sep 26, 2024 |
| ASRock        | B250M Pro4                  | Desktop     | [28552e8c78](https://linux-hardware.org/?probe=28552e8c78) | Sep 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [5c78d4f841](https://linux-hardware.org/?probe=5c78d4f841) | Sep 26, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6ca9ff799b](https://linux-hardware.org/?probe=6ca9ff799b) | Sep 26, 2024 |
| MSI           | A320M PRO-VD/S              | Desktop     | [40cd5165c5](https://linux-hardware.org/?probe=40cd5165c5) | Sep 25, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [ddad48a432](https://linux-hardware.org/?probe=ddad48a432) | Sep 25, 2024 |
| Shenzhen M... | F7BSD                       | Mini pc     | [0a6ec6959a](https://linux-hardware.org/?probe=0a6ec6959a) | Sep 24, 2024 |
| Acer          | Aspire A315-24PT            | Notebook    | [793dc850a6](https://linux-hardware.org/?probe=793dc850a6) | Sep 24, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d94733433a](https://linux-hardware.org/?probe=d94733433a) | Sep 24, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [33fb3994d7](https://linux-hardware.org/?probe=33fb3994d7) | Sep 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c2587deab9](https://linux-hardware.org/?probe=c2587deab9) | Sep 24, 2024 |
| Acidanther... | MacBookPro11,2              | Notebook    | [036522cecc](https://linux-hardware.org/?probe=036522cecc) | Sep 23, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a676f3fe5f](https://linux-hardware.org/?probe=a676f3fe5f) | Sep 23, 2024 |
| Casper        | NIRVANA NB C500             | Notebook    | [ad7927b7b6](https://linux-hardware.org/?probe=ad7927b7b6) | Sep 23, 2024 |
| ASRock        | X670E Taichi                | Desktop     | [5482e0ffdf](https://linux-hardware.org/?probe=5482e0ffdf) | Sep 23, 2024 |
| Gigabyte      | B450M H                     | Desktop     | [eaf773b0b3](https://linux-hardware.org/?probe=eaf773b0b3) | Sep 23, 2024 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | Notebook    | [b5b460246c](https://linux-hardware.org/?probe=b5b460246c) | Sep 23, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [ada9824b2e](https://linux-hardware.org/?probe=ada9824b2e) | Sep 22, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [d85acdf3ac](https://linux-hardware.org/?probe=d85acdf3ac) | Sep 22, 2024 |
| Huanan        | X99-F8                      | Desktop     | [ba69d58749](https://linux-hardware.org/?probe=ba69d58749) | Sep 22, 2024 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [2e4e4f181f](https://linux-hardware.org/?probe=2e4e4f181f) | Sep 21, 2024 |
| Dell          | Latitude 7480               | Notebook    | [88b66b0476](https://linux-hardware.org/?probe=88b66b0476) | Sep 20, 2024 |
| HP            | 802F                        | Desktop     | [8f5648baef](https://linux-hardware.org/?probe=8f5648baef) | Sep 20, 2024 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [ce54b5370d](https://linux-hardware.org/?probe=ce54b5370d) | Sep 20, 2024 |
| Dell          | Latitude 5510               | Notebook    | [3ab14db3ae](https://linux-hardware.org/?probe=3ab14db3ae) | Sep 19, 2024 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [2138db3b36](https://linux-hardware.org/?probe=2138db3b36) | Sep 19, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [0f13438fec](https://linux-hardware.org/?probe=0f13438fec) | Sep 18, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [c4d1b20e65](https://linux-hardware.org/?probe=c4d1b20e65) | Sep 17, 2024 |
| HP            | G42                         | Notebook    | [1fa39a4ae1](https://linux-hardware.org/?probe=1fa39a4ae1) | Sep 17, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [44c005d71d](https://linux-hardware.org/?probe=44c005d71d) | Sep 16, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [20d890925f](https://linux-hardware.org/?probe=20d890925f) | Sep 16, 2024 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [949b1d1d9e](https://linux-hardware.org/?probe=949b1d1d9e) | Sep 16, 2024 |
| Fujitsu       | LIFEBOOK U729               | Notebook    | [94bef52ce4](https://linux-hardware.org/?probe=94bef52ce4) | Sep 15, 2024 |
| Lenovo        | ThinkPad T420 4236Y19       | Notebook    | [13fbdbca13](https://linux-hardware.org/?probe=13fbdbca13) | Sep 15, 2024 |
| MECER         | Z140C-Xpr-FPLUS             | Notebook    | [7485697159](https://linux-hardware.org/?probe=7485697159) | Sep 15, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [c1fca7c250](https://linux-hardware.org/?probe=c1fca7c250) | Sep 15, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [556862a19d](https://linux-hardware.org/?probe=556862a19d) | Sep 15, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [cb72ac3b7c](https://linux-hardware.org/?probe=cb72ac3b7c) | Sep 15, 2024 |
| Dell          | Precision 3541              | Notebook    | [2ab0c627bf](https://linux-hardware.org/?probe=2ab0c627bf) | Sep 14, 2024 |
| ASRock        | Z370 Extreme4               | Desktop     | [53e502252c](https://linux-hardware.org/?probe=53e502252c) | Sep 14, 2024 |
| Acer          | Predator G3-605             | Desktop     | [0986180fe7](https://linux-hardware.org/?probe=0986180fe7) | Sep 14, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [510bb09c29](https://linux-hardware.org/?probe=510bb09c29) | Sep 14, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [fe56dbfcd2](https://linux-hardware.org/?probe=fe56dbfcd2) | Sep 14, 2024 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [a07b77e4ed](https://linux-hardware.org/?probe=a07b77e4ed) | Sep 13, 2024 |
| Samsung       | Galaxy Book 12              | Tablet      | [55967569d3](https://linux-hardware.org/?probe=55967569d3) | Sep 13, 2024 |
| ASUSTek       | ROG Strix G531GU_G531GU     | Notebook    | [8efae527ee](https://linux-hardware.org/?probe=8efae527ee) | Sep 13, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [cac90131df](https://linux-hardware.org/?probe=cac90131df) | Sep 13, 2024 |
| Dell          | Latitude 7490               | Notebook    | [c3088ac0e7](https://linux-hardware.org/?probe=c3088ac0e7) | Sep 12, 2024 |
| Dell          | Latitude 7490               | Notebook    | [354bdc75f3](https://linux-hardware.org/?probe=354bdc75f3) | Sep 12, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [200d1008af](https://linux-hardware.org/?probe=200d1008af) | Sep 12, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [47ced3aae0](https://linux-hardware.org/?probe=47ced3aae0) | Sep 12, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [f1283f35a2](https://linux-hardware.org/?probe=f1283f35a2) | Sep 12, 2024 |
| ASRock        | H170M Pro4                  | Desktop     | [f263cf1630](https://linux-hardware.org/?probe=f263cf1630) | Sep 11, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [41e5b4b4a3](https://linux-hardware.org/?probe=41e5b4b4a3) | Sep 11, 2024 |
| Dell          | 0M3F6C A01                  | Desktop     | [11ec44761a](https://linux-hardware.org/?probe=11ec44761a) | Sep 11, 2024 |
| Acer          | Nitro AN515-56              | Notebook    | [77aeb8d14e](https://linux-hardware.org/?probe=77aeb8d14e) | Sep 10, 2024 |
| Dell          | 0M3F6C A01                  | Desktop     | [305e71b5c8](https://linux-hardware.org/?probe=305e71b5c8) | Sep 10, 2024 |
| Acer          | Nitro AN515-56              | Notebook    | [722f73a308](https://linux-hardware.org/?probe=722f73a308) | Sep 10, 2024 |
| ASUSTek       | H110M-CS                    | Desktop     | [90196d4184](https://linux-hardware.org/?probe=90196d4184) | Sep 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4030cf137e](https://linux-hardware.org/?probe=4030cf137e) | Sep 09, 2024 |
| AZW           | GK mini                     | Desktop     | [51bb1a46f8](https://linux-hardware.org/?probe=51bb1a46f8) | Sep 09, 2024 |
| Toshiba       | Satellite P875              | Notebook    | [947e6f3bf9](https://linux-hardware.org/?probe=947e6f3bf9) | Sep 09, 2024 |
| Lenovo        | ThinkPad X390 20Q1SCU200    | Notebook    | [d449445712](https://linux-hardware.org/?probe=d449445712) | Sep 09, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06f24cf1fb](https://linux-hardware.org/?probe=06f24cf1fb) | Sep 08, 2024 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [911423c12e](https://linux-hardware.org/?probe=911423c12e) | Sep 08, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [32f27af720](https://linux-hardware.org/?probe=32f27af720) | Sep 07, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [144f86e54b](https://linux-hardware.org/?probe=144f86e54b) | Sep 07, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [3d987c5904](https://linux-hardware.org/?probe=3d987c5904) | Sep 07, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7a7eff6254](https://linux-hardware.org/?probe=7a7eff6254) | Sep 06, 2024 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [ba2147836a](https://linux-hardware.org/?probe=ba2147836a) | Sep 06, 2024 |
| Dell          | 0P301D A02                  | Desktop     | [3643e9b293](https://linux-hardware.org/?probe=3643e9b293) | Sep 06, 2024 |
| Dell          | 0P301D A02                  | Desktop     | [a37947e498](https://linux-hardware.org/?probe=a37947e498) | Sep 06, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f27ba0493e](https://linux-hardware.org/?probe=f27ba0493e) | Sep 05, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eb753d52a6](https://linux-hardware.org/?probe=eb753d52a6) | Sep 05, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [063e9a37bb](https://linux-hardware.org/?probe=063e9a37bb) | Sep 05, 2024 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [b37cf62016](https://linux-hardware.org/?probe=b37cf62016) | Sep 05, 2024 |
| MSI           | B85-G43                     | Desktop     | [1e054befbc](https://linux-hardware.org/?probe=1e054befbc) | Sep 04, 2024 |
| HP            | 1850                        | Desktop     | [29a0446b30](https://linux-hardware.org/?probe=29a0446b30) | Sep 04, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [edeb2a22da](https://linux-hardware.org/?probe=edeb2a22da) | Sep 03, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [5183ec1fdf](https://linux-hardware.org/?probe=5183ec1fdf) | Sep 03, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5fece1ca7d](https://linux-hardware.org/?probe=5fece1ca7d) | Sep 03, 2024 |
| ASRock        | H170M Pro4                  | Desktop     | [1846c4eb3f](https://linux-hardware.org/?probe=1846c4eb3f) | Sep 03, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [aceed32f04](https://linux-hardware.org/?probe=aceed32f04) | Sep 03, 2024 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d42f118891](https://linux-hardware.org/?probe=d42f118891) | Sep 03, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [97f086dd12](https://linux-hardware.org/?probe=97f086dd12) | Sep 03, 2024 |
| ASRock        | H170M Pro4                  | Desktop     | [6e1160875e](https://linux-hardware.org/?probe=6e1160875e) | Sep 02, 2024 |
| Dell          | Latitude 5480               | Notebook    | [30fb323c58](https://linux-hardware.org/?probe=30fb323c58) | Sep 01, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c74b9009e8](https://linux-hardware.org/?probe=c74b9009e8) | Aug 31, 2024 |
| Huanan        | X99-F8                      | Desktop     | [d930095522](https://linux-hardware.org/?probe=d930095522) | Aug 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [33cb105809](https://linux-hardware.org/?probe=33cb105809) | Aug 31, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [8eb3f4820f](https://linux-hardware.org/?probe=8eb3f4820f) | Aug 31, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a09a263f48](https://linux-hardware.org/?probe=a09a263f48) | Aug 31, 2024 |
| Lenovo        | ThinkPad T490 20N3S9UH0L    | Notebook    | [c02f70d601](https://linux-hardware.org/?probe=c02f70d601) | Aug 31, 2024 |
| HP            | 1850                        | Desktop     | [497427a54f](https://linux-hardware.org/?probe=497427a54f) | Aug 31, 2024 |
| Dell          | Latitude 3540               | Notebook    | [743cd89273](https://linux-hardware.org/?probe=743cd89273) | Aug 31, 2024 |
| Dell          | Vostro 5481                 | Notebook    | [04820e5465](https://linux-hardware.org/?probe=04820e5465) | Aug 30, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7648872630](https://linux-hardware.org/?probe=7648872630) | Aug 30, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [9b192254cc](https://linux-hardware.org/?probe=9b192254cc) | Aug 30, 2024 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [88aeb5276d](https://linux-hardware.org/?probe=88aeb5276d) | Aug 30, 2024 |
| HP            | 8053                        | Desktop     | [ddd7e6112f](https://linux-hardware.org/?probe=ddd7e6112f) | Aug 29, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [135301e31b](https://linux-hardware.org/?probe=135301e31b) | Aug 29, 2024 |
| Gigabyte      | H410M H                     | Desktop     | [3910ecd921](https://linux-hardware.org/?probe=3910ecd921) | Aug 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [28dd42ce86](https://linux-hardware.org/?probe=28dd42ce86) | Aug 28, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5fbbe46a7d](https://linux-hardware.org/?probe=5fbbe46a7d) | Aug 28, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bc3d3571cf](https://linux-hardware.org/?probe=bc3d3571cf) | Aug 28, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [8662d6d9a4](https://linux-hardware.org/?probe=8662d6d9a4) | Aug 27, 2024 |
| Lenovo        | ThinkPad E14 20RA005UTX     | Notebook    | [11b6cf5667](https://linux-hardware.org/?probe=11b6cf5667) | Aug 27, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [0a52089bbd](https://linux-hardware.org/?probe=0a52089bbd) | Aug 27, 2024 |
| Dell          | 084J0R A00                  | Desktop     | [6e7707b22d](https://linux-hardware.org/?probe=6e7707b22d) | Aug 27, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [4030698d5c](https://linux-hardware.org/?probe=4030698d5c) | Aug 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [390c79d9e7](https://linux-hardware.org/?probe=390c79d9e7) | Aug 27, 2024 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [ba17ccfdcf](https://linux-hardware.org/?probe=ba17ccfdcf) | Aug 27, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [fcb0a29b79](https://linux-hardware.org/?probe=fcb0a29b79) | Aug 27, 2024 |
| ASRock        | H170M Pro4                  | Desktop     | [503ee7ab5d](https://linux-hardware.org/?probe=503ee7ab5d) | Aug 27, 2024 |
| ASRock        | A320M-ITX                   | Desktop     | [72cbd14652](https://linux-hardware.org/?probe=72cbd14652) | Aug 27, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [279a906ea1](https://linux-hardware.org/?probe=279a906ea1) | Aug 27, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [98661fedcc](https://linux-hardware.org/?probe=98661fedcc) | Aug 26, 2024 |
| Lenovo        | ThinkPad T431s 20AA000EM... | Notebook    | [ac07d62bd7](https://linux-hardware.org/?probe=ac07d62bd7) | Aug 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [0f53ca6134](https://linux-hardware.org/?probe=0f53ca6134) | Aug 26, 2024 |
| Dell          | Inspiron 3551               | Notebook    | [4b2bec1c78](https://linux-hardware.org/?probe=4b2bec1c78) | Aug 26, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [561ae6416f](https://linux-hardware.org/?probe=561ae6416f) | Aug 26, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [efdba9e0cb](https://linux-hardware.org/?probe=efdba9e0cb) | Aug 25, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [a7ac33ab5c](https://linux-hardware.org/?probe=a7ac33ab5c) | Aug 25, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [587cdb384a](https://linux-hardware.org/?probe=587cdb384a) | Aug 25, 2024 |
| ASRock        | B250M Pro4                  | Desktop     | [97a7b1d3c7](https://linux-hardware.org/?probe=97a7b1d3c7) | Aug 25, 2024 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [19756dc35b](https://linux-hardware.org/?probe=19756dc35b) | Aug 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d2acc5a68f](https://linux-hardware.org/?probe=d2acc5a68f) | Aug 25, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [4a207d02b6](https://linux-hardware.org/?probe=4a207d02b6) | Aug 25, 2024 |
| Dell          | Latitude 3420               | Notebook    | [da748e7b49](https://linux-hardware.org/?probe=da748e7b49) | Aug 25, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [4715fed7ea](https://linux-hardware.org/?probe=4715fed7ea) | Aug 24, 2024 |
| HUAWEI        | VLT-WX0                     | Notebook    | [38c3fa484e](https://linux-hardware.org/?probe=38c3fa484e) | Aug 24, 2024 |
| Dell          | Precision 7530              | Notebook    | [67e1c5e840](https://linux-hardware.org/?probe=67e1c5e840) | Aug 24, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [27a5a9d60e](https://linux-hardware.org/?probe=27a5a9d60e) | Aug 24, 2024 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [cebaebc39f](https://linux-hardware.org/?probe=cebaebc39f) | Aug 23, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [175d9d895e](https://linux-hardware.org/?probe=175d9d895e) | Aug 23, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [db9806a453](https://linux-hardware.org/?probe=db9806a453) | Aug 23, 2024 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b70e5b3f1b](https://linux-hardware.org/?probe=b70e5b3f1b) | Aug 23, 2024 |
| ASRock        | B250M Pro4                  | Desktop     | [e58fd49e45](https://linux-hardware.org/?probe=e58fd49e45) | Aug 23, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [90fe53af7c](https://linux-hardware.org/?probe=90fe53af7c) | Aug 22, 2024 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [935b5d9511](https://linux-hardware.org/?probe=935b5d9511) | Aug 22, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [dc0f500aeb](https://linux-hardware.org/?probe=dc0f500aeb) | Aug 22, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [1f1b69b92e](https://linux-hardware.org/?probe=1f1b69b92e) | Aug 22, 2024 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [da8956c0a7](https://linux-hardware.org/?probe=da8956c0a7) | Aug 22, 2024 |
| Lenovo        | SHARKBAY 31900059 STD       | All in one  | [eba82837d7](https://linux-hardware.org/?probe=eba82837d7) | Aug 22, 2024 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [aa44dc61f4](https://linux-hardware.org/?probe=aa44dc61f4) | Aug 21, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [a597fbf188](https://linux-hardware.org/?probe=a597fbf188) | Aug 21, 2024 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [add09e061b](https://linux-hardware.org/?probe=add09e061b) | Aug 21, 2024 |
| HP            | 8053                        | Desktop     | [7332af6a12](https://linux-hardware.org/?probe=7332af6a12) | Aug 20, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [921cf79eb2](https://linux-hardware.org/?probe=921cf79eb2) | Aug 20, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [df1f476ad7](https://linux-hardware.org/?probe=df1f476ad7) | Aug 20, 2024 |
| Huanan        | X99-F8                      | Desktop     | [72a72ff695](https://linux-hardware.org/?probe=72a72ff695) | Aug 20, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [19620ec0f0](https://linux-hardware.org/?probe=19620ec0f0) | Aug 20, 2024 |
| Dell          | 0XHGV1 A00                  | Desktop     | [0cf3db71c9](https://linux-hardware.org/?probe=0cf3db71c9) | Aug 20, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5d03c0ea61](https://linux-hardware.org/?probe=5d03c0ea61) | Aug 19, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [0d829aac0e](https://linux-hardware.org/?probe=0d829aac0e) | Aug 19, 2024 |
| Notebook      | N85_N87HCHN                 | Notebook    | [0f1213f3e0](https://linux-hardware.org/?probe=0f1213f3e0) | Aug 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbbae7427](https://linux-hardware.org/?probe=acbbae7427) | Aug 18, 2024 |
| Lenovo        | ThinkPad P50 20EQS0TM00     | Notebook    | [0d8a3c8037](https://linux-hardware.org/?probe=0d8a3c8037) | Aug 18, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [7e6f232032](https://linux-hardware.org/?probe=7e6f232032) | Aug 18, 2024 |
| Fujitsu       | LIFEBOOK U729               | Notebook    | [84c5ee6ec3](https://linux-hardware.org/?probe=84c5ee6ec3) | Aug 18, 2024 |
| ASRock        | A300M-STX                   | Desktop     | [c5cef03388](https://linux-hardware.org/?probe=c5cef03388) | Aug 18, 2024 |
| HP            | Laptop 17-ak0xx             | Notebook    | [9cf5071a77](https://linux-hardware.org/?probe=9cf5071a77) | Aug 17, 2024 |
| Sony          | SVE1511Q1ESI                | Notebook    | [6f96e76030](https://linux-hardware.org/?probe=6f96e76030) | Aug 17, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [0d3fd20eba](https://linux-hardware.org/?probe=0d3fd20eba) | Aug 17, 2024 |
| Lenovo        | ThinkPad T490 20N3SDGJ02    | Notebook    | [230480ef42](https://linux-hardware.org/?probe=230480ef42) | Aug 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4e9cb146ce](https://linux-hardware.org/?probe=4e9cb146ce) | Aug 17, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [1dce11edb7](https://linux-hardware.org/?probe=1dce11edb7) | Aug 17, 2024 |
| Unknown       | Unknown                     | Notebook    | [8afc1dbdf1](https://linux-hardware.org/?probe=8afc1dbdf1) | Aug 17, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [ac1f986bef](https://linux-hardware.org/?probe=ac1f986bef) | Aug 17, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [3100c0b501](https://linux-hardware.org/?probe=3100c0b501) | Aug 17, 2024 |
| Dell          | Vostro 5481                 | Notebook    | [c76a7034cd](https://linux-hardware.org/?probe=c76a7034cd) | Aug 16, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [827dae32cf](https://linux-hardware.org/?probe=827dae32cf) | Aug 16, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [01ce9d6528](https://linux-hardware.org/?probe=01ce9d6528) | Aug 16, 2024 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [bae502a4a6](https://linux-hardware.org/?probe=bae502a4a6) | Aug 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f12d3b4f89](https://linux-hardware.org/?probe=f12d3b4f89) | Aug 15, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c30422de88](https://linux-hardware.org/?probe=c30422de88) | Aug 15, 2024 |
| Lenovo        | 3176 NOK                    | Desktop     | [0589f04596](https://linux-hardware.org/?probe=0589f04596) | Aug 15, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [848c3baea2](https://linux-hardware.org/?probe=848c3baea2) | Aug 14, 2024 |
| HP            | 1850                        | Desktop     | [d54e50f3b1](https://linux-hardware.org/?probe=d54e50f3b1) | Aug 14, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a25f1be119](https://linux-hardware.org/?probe=a25f1be119) | Aug 13, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [6447512d98](https://linux-hardware.org/?probe=6447512d98) | Aug 13, 2024 |
| HP            | 8053                        | Desktop     | [247a2a52da](https://linux-hardware.org/?probe=247a2a52da) | Aug 13, 2024 |
| HP            | 2B2C                        | Desktop     | [5cfdd8de1c](https://linux-hardware.org/?probe=5cfdd8de1c) | Aug 12, 2024 |
| Acer          | Predator G3-710             | Desktop     | [4fe7b89bee](https://linux-hardware.org/?probe=4fe7b89bee) | Aug 12, 2024 |
| Intel         | Unknown                     | Desktop     | [c358a45a87](https://linux-hardware.org/?probe=c358a45a87) | Aug 12, 2024 |
| Dell          | Precision M4600             | Notebook    | [fee987030c](https://linux-hardware.org/?probe=fee987030c) | Aug 12, 2024 |
| ASUSTek       | G750JM                      | Notebook    | [f7169a12d4](https://linux-hardware.org/?probe=f7169a12d4) | Aug 11, 2024 |
| Dell          | Vostro 15 3515              | Notebook    | [1a4a792879](https://linux-hardware.org/?probe=1a4a792879) | Aug 11, 2024 |
| Medion        | MS-7616                     | Desktop     | [b9f5b7b663](https://linux-hardware.org/?probe=b9f5b7b663) | Aug 11, 2024 |
| Dell          | Precision M4600             | Notebook    | [7decf1dba0](https://linux-hardware.org/?probe=7decf1dba0) | Aug 11, 2024 |
| Unknown       | Unknown                     | Notebook    | [4ef8a514bb](https://linux-hardware.org/?probe=4ef8a514bb) | Aug 11, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [e6011d2739](https://linux-hardware.org/?probe=e6011d2739) | Aug 10, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [c60e9bf9c3](https://linux-hardware.org/?probe=c60e9bf9c3) | Aug 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ef94c4980f](https://linux-hardware.org/?probe=ef94c4980f) | Aug 10, 2024 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [b006c903a5](https://linux-hardware.org/?probe=b006c903a5) | Aug 09, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [995cc2755c](https://linux-hardware.org/?probe=995cc2755c) | Aug 09, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [b17bc38220](https://linux-hardware.org/?probe=b17bc38220) | Aug 09, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b96840ca66](https://linux-hardware.org/?probe=b96840ca66) | Aug 09, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [adf8284c15](https://linux-hardware.org/?probe=adf8284c15) | Aug 09, 2024 |
| Acer          | Swift SFG14-63              | Notebook    | [13962c151c](https://linux-hardware.org/?probe=13962c151c) | Aug 09, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [b2182890a9](https://linux-hardware.org/?probe=b2182890a9) | Aug 09, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [589642642a](https://linux-hardware.org/?probe=589642642a) | Aug 09, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8MU0... | Notebook    | [39cd01c474](https://linux-hardware.org/?probe=39cd01c474) | Aug 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [096fc9182f](https://linux-hardware.org/?probe=096fc9182f) | Aug 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [458556ade2](https://linux-hardware.org/?probe=458556ade2) | Aug 08, 2024 |
| Dell          | Latitude E6540              | Notebook    | [f42bc0d88a](https://linux-hardware.org/?probe=f42bc0d88a) | Aug 08, 2024 |
| Lenovo        | ThinkPad X230 2325YHU       | Notebook    | [fcb28699a1](https://linux-hardware.org/?probe=fcb28699a1) | Aug 08, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [f2d62223f1](https://linux-hardware.org/?probe=f2d62223f1) | Aug 07, 2024 |
| Dell          | 0U880P A00                  | Desktop     | [d1579704bc](https://linux-hardware.org/?probe=d1579704bc) | Aug 07, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0b6fcf20b7](https://linux-hardware.org/?probe=0b6fcf20b7) | Aug 07, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d5c3de32a3](https://linux-hardware.org/?probe=d5c3de32a3) | Aug 06, 2024 |
| Dell          | Latitude 3410               | Notebook    | [4709ba4ef7](https://linux-hardware.org/?probe=4709ba4ef7) | Aug 06, 2024 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [0ffaa166a9](https://linux-hardware.org/?probe=0ffaa166a9) | Aug 05, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [a449eca4ed](https://linux-hardware.org/?probe=a449eca4ed) | Aug 04, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [f20f2b491d](https://linux-hardware.org/?probe=f20f2b491d) | Aug 04, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [40d6662f45](https://linux-hardware.org/?probe=40d6662f45) | Aug 04, 2024 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [d6fda43aa3](https://linux-hardware.org/?probe=d6fda43aa3) | Aug 04, 2024 |
| Unknown       | Unknown                     | Notebook    | [24f692b500](https://linux-hardware.org/?probe=24f692b500) | Aug 04, 2024 |
| Dell          | 0M3F6C A01                  | Desktop     | [727f97a807](https://linux-hardware.org/?probe=727f97a807) | Aug 04, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [a8c595d2ef](https://linux-hardware.org/?probe=a8c595d2ef) | Aug 03, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [fe6df07eaa](https://linux-hardware.org/?probe=fe6df07eaa) | Aug 03, 2024 |
| ASUSTek       | K53E                        | Notebook    | [3a238385b4](https://linux-hardware.org/?probe=3a238385b4) | Aug 03, 2024 |
| Lenovo        | ThinkStation D20 4155K4U    | Desktop     | [db60503231](https://linux-hardware.org/?probe=db60503231) | Aug 03, 2024 |
| Prestigio     | PSB141S01                   | Notebook    | [1e3d3427dc](https://linux-hardware.org/?probe=1e3d3427dc) | Aug 03, 2024 |
| HP            | Notebook                    | Notebook    | [fbe8e7310f](https://linux-hardware.org/?probe=fbe8e7310f) | Aug 03, 2024 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [afeb78c7e9](https://linux-hardware.org/?probe=afeb78c7e9) | Aug 02, 2024 |
| ASRock        | J4105-ITX                   | Desktop     | [1dc3e6bb80](https://linux-hardware.org/?probe=1dc3e6bb80) | Aug 02, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9923acf6c3](https://linux-hardware.org/?probe=9923acf6c3) | Aug 01, 2024 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [34d6b03cd8](https://linux-hardware.org/?probe=34d6b03cd8) | Aug 01, 2024 |
| Gigabyte      | H67MA-D2H-B3                | Desktop     | [dcd172f513](https://linux-hardware.org/?probe=dcd172f513) | Aug 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [fda3eb1b69](https://linux-hardware.org/?probe=fda3eb1b69) | Jul 31, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [322addb26b](https://linux-hardware.org/?probe=322addb26b) | Jul 31, 2024 |
| Dell          | Inspiron 5759               | Notebook    | [3a1815a809](https://linux-hardware.org/?probe=3a1815a809) | Jul 31, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2556f53227](https://linux-hardware.org/?probe=2556f53227) | Jul 31, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6b88264648](https://linux-hardware.org/?probe=6b88264648) | Jul 31, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [15d02e4b03](https://linux-hardware.org/?probe=15d02e4b03) | Jul 31, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f4300b5164](https://linux-hardware.org/?probe=f4300b5164) | Jul 30, 2024 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2c61d4cf7a](https://linux-hardware.org/?probe=2c61d4cf7a) | Jul 29, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a9be31f0e5](https://linux-hardware.org/?probe=a9be31f0e5) | Jul 29, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [b6be1e68b7](https://linux-hardware.org/?probe=b6be1e68b7) | Jul 29, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [93fc33c957](https://linux-hardware.org/?probe=93fc33c957) | Jul 29, 2024 |
| MSI           | H61M-P31/W8                 | Desktop     | [bf715c4bd6](https://linux-hardware.org/?probe=bf715c4bd6) | Jul 28, 2024 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [429d9c2dee](https://linux-hardware.org/?probe=429d9c2dee) | Jul 28, 2024 |
| Lenovo        | ThinkPad X250 20CLS60800    | Notebook    | [856ee29487](https://linux-hardware.org/?probe=856ee29487) | Jul 27, 2024 |
| ASRockRack    | ROME2D16-2T                 | Server      | [5a5b3cd0e2](https://linux-hardware.org/?probe=5a5b3cd0e2) | Jul 27, 2024 |
| HP            | 8767 A                      | Desktop     | [d377d98814](https://linux-hardware.org/?probe=d377d98814) | Jul 26, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [43c3d54837](https://linux-hardware.org/?probe=43c3d54837) | Jul 25, 2024 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [e3c3a39169](https://linux-hardware.org/?probe=e3c3a39169) | Jul 25, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [0a7d9da06c](https://linux-hardware.org/?probe=0a7d9da06c) | Jul 25, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [be11148fa0](https://linux-hardware.org/?probe=be11148fa0) | Jul 25, 2024 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [6d14b0b8cd](https://linux-hardware.org/?probe=6d14b0b8cd) | Jul 24, 2024 |
| BESSTAR Te... | UM300 V1.0                  | Desktop     | [d089d6eb60](https://linux-hardware.org/?probe=d089d6eb60) | Jul 24, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [18375f7eda](https://linux-hardware.org/?probe=18375f7eda) | Jul 23, 2024 |
| ECS           | H110M4-C43                  | Desktop     | [c480519fab](https://linux-hardware.org/?probe=c480519fab) | Jul 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d60f72815e](https://linux-hardware.org/?probe=d60f72815e) | Jul 23, 2024 |
| Dell          | Inspiron 7472               | Notebook    | [5124620552](https://linux-hardware.org/?probe=5124620552) | Jul 23, 2024 |
| Dell          | Latitude E6440              | Notebook    | [3440c7ee39](https://linux-hardware.org/?probe=3440c7ee39) | Jul 22, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [768165c808](https://linux-hardware.org/?probe=768165c808) | Jul 22, 2024 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [58536682ec](https://linux-hardware.org/?probe=58536682ec) | Jul 22, 2024 |
| HP            | ProBook 6560b               | Notebook    | [8492f0d6a2](https://linux-hardware.org/?probe=8492f0d6a2) | Jul 22, 2024 |
| HP            | ProBook 6560b               | Notebook    | [cb6317449c](https://linux-hardware.org/?probe=cb6317449c) | Jul 22, 2024 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [7d9f8adaca](https://linux-hardware.org/?probe=7d9f8adaca) | Jul 22, 2024 |
| Dell          | Vostro 5620                 | Notebook    | [5ab903f619](https://linux-hardware.org/?probe=5ab903f619) | Jul 20, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [15d7334bb1](https://linux-hardware.org/?probe=15d7334bb1) | Jul 20, 2024 |
| HP            | 1850                        | Desktop     | [41ee740278](https://linux-hardware.org/?probe=41ee740278) | Jul 20, 2024 |
| HP            | Folio 13                    | Notebook    | [8e2db3f28d](https://linux-hardware.org/?probe=8e2db3f28d) | Jul 20, 2024 |
| Acer          | Aspire F5-572               | Notebook    | [25a7a5ebdd](https://linux-hardware.org/?probe=25a7a5ebdd) | Jul 19, 2024 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [d20c9376fa](https://linux-hardware.org/?probe=d20c9376fa) | Jul 19, 2024 |
| HP            | 8053                        | Desktop     | [228dd5d88a](https://linux-hardware.org/?probe=228dd5d88a) | Jul 18, 2024 |
| HP            | Unknown                     | Notebook    | [efa1195831](https://linux-hardware.org/?probe=efa1195831) | Jul 18, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [bd5d5f6b75](https://linux-hardware.org/?probe=bd5d5f6b75) | Jul 17, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [2bd5211193](https://linux-hardware.org/?probe=2bd5211193) | Jul 17, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [537cf590b0](https://linux-hardware.org/?probe=537cf590b0) | Jul 17, 2024 |
| BESSTAR Te... | UM300 V1.0                  | Desktop     | [234d4729df](https://linux-hardware.org/?probe=234d4729df) | Jul 16, 2024 |
| HP            | ENVY 17                     | Notebook    | [c2e6026bc8](https://linux-hardware.org/?probe=c2e6026bc8) | Jul 16, 2024 |
| Acer          | AOD257                      | Notebook    | [c96b02eea6](https://linux-hardware.org/?probe=c96b02eea6) | Jul 16, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [1a0b5dd4f4](https://linux-hardware.org/?probe=1a0b5dd4f4) | Jul 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [bbf6a07635](https://linux-hardware.org/?probe=bbf6a07635) | Jul 16, 2024 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [ef46a1640f](https://linux-hardware.org/?probe=ef46a1640f) | Jul 15, 2024 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [ea9ae29548](https://linux-hardware.org/?probe=ea9ae29548) | Jul 14, 2024 |
| MSI           | MS-B9221                    | Desktop     | [6def5391ec](https://linux-hardware.org/?probe=6def5391ec) | Jul 14, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [88aa7d03b9](https://linux-hardware.org/?probe=88aa7d03b9) | Jul 14, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [5ca6a9bef8](https://linux-hardware.org/?probe=5ca6a9bef8) | Jul 13, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [39095eabda](https://linux-hardware.org/?probe=39095eabda) | Jul 13, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14c7e380fc](https://linux-hardware.org/?probe=14c7e380fc) | Jul 13, 2024 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c5bbc1d2a2](https://linux-hardware.org/?probe=c5bbc1d2a2) | Jul 12, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [909f552c4d](https://linux-hardware.org/?probe=909f552c4d) | Jul 11, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [25d0c0cc2d](https://linux-hardware.org/?probe=25d0c0cc2d) | Jul 11, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [fc07f7747d](https://linux-hardware.org/?probe=fc07f7747d) | Jul 10, 2024 |
| Acer          | UI2H                        | All in one  | [bf68d03983](https://linux-hardware.org/?probe=bf68d03983) | Jul 09, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [d06d70823a](https://linux-hardware.org/?probe=d06d70823a) | Jul 09, 2024 |
| ECS           | H110M4-C43                  | Desktop     | [15fb98442e](https://linux-hardware.org/?probe=15fb98442e) | Jul 09, 2024 |
| Lenovo        | 371F SDK0R32862 WIN 3258... | All in one  | [25969f986d](https://linux-hardware.org/?probe=25969f986d) | Jul 09, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | Notebook    | [0eff33b928](https://linux-hardware.org/?probe=0eff33b928) | Jul 09, 2024 |
| HP            | 158B                        | Desktop     | [882b1d95b2](https://linux-hardware.org/?probe=882b1d95b2) | Jul 09, 2024 |
| HP            | Folio 13                    | Notebook    | [88f232a268](https://linux-hardware.org/?probe=88f232a268) | Jul 08, 2024 |
| HP            | 802F                        | Desktop     | [287eec5051](https://linux-hardware.org/?probe=287eec5051) | Jul 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [738373c2bd](https://linux-hardware.org/?probe=738373c2bd) | Jul 08, 2024 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [5bb7c7675f](https://linux-hardware.org/?probe=5bb7c7675f) | Jul 08, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [2322ccf135](https://linux-hardware.org/?probe=2322ccf135) | Jul 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bc2ad8521d](https://linux-hardware.org/?probe=bc2ad8521d) | Jul 08, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [5409aa4c40](https://linux-hardware.org/?probe=5409aa4c40) | Jul 08, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [d83f32d474](https://linux-hardware.org/?probe=d83f32d474) | Jul 07, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [b8abc7e257](https://linux-hardware.org/?probe=b8abc7e257) | Jul 07, 2024 |
| Lenovo        | ThinkPad T430s 2355HFG      | Notebook    | [92d6389375](https://linux-hardware.org/?probe=92d6389375) | Jul 07, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [4b9f15c056](https://linux-hardware.org/?probe=4b9f15c056) | Jul 07, 2024 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [626f3d11a6](https://linux-hardware.org/?probe=626f3d11a6) | Jul 06, 2024 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [0aa2ba0ae2](https://linux-hardware.org/?probe=0aa2ba0ae2) | Jul 06, 2024 |
| Dell          | 08HPGT A01                  | Desktop     | [d912c22e0f](https://linux-hardware.org/?probe=d912c22e0f) | Jul 06, 2024 |
| Dell          | G15 Special Edition 5521    | Notebook    | [79c75669bc](https://linux-hardware.org/?probe=79c75669bc) | Jul 06, 2024 |
| Lenovo        | ThinkPad T430s 2355HFG      | Notebook    | [ab1db76346](https://linux-hardware.org/?probe=ab1db76346) | Jul 06, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [a3ef2a72cc](https://linux-hardware.org/?probe=a3ef2a72cc) | Jul 06, 2024 |
| HP            | Pavilion 15                 | Notebook    | [d5012fb143](https://linux-hardware.org/?probe=d5012fb143) | Jul 05, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [727dc315dd](https://linux-hardware.org/?probe=727dc315dd) | Jul 05, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [e1efd4702d](https://linux-hardware.org/?probe=e1efd4702d) | Jul 05, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b5a909722b](https://linux-hardware.org/?probe=b5a909722b) | Jul 04, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [a603c07b6d](https://linux-hardware.org/?probe=a603c07b6d) | Jul 04, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f767f8d3ba](https://linux-hardware.org/?probe=f767f8d3ba) | Jul 04, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [2f6141fce5](https://linux-hardware.org/?probe=2f6141fce5) | Jul 04, 2024 |
| Intel         | CRESCENTBAY                 | Desktop     | [1d5bcb33a2](https://linux-hardware.org/?probe=1d5bcb33a2) | Jul 04, 2024 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [30895ceae1](https://linux-hardware.org/?probe=30895ceae1) | Jul 03, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [97e952ccd4](https://linux-hardware.org/?probe=97e952ccd4) | Jul 02, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [c82073c3ef](https://linux-hardware.org/?probe=c82073c3ef) | Jul 02, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [daf68f5aca](https://linux-hardware.org/?probe=daf68f5aca) | Jul 02, 2024 |
| Dell          | Latitude E5450              | Notebook    | [fa201775ac](https://linux-hardware.org/?probe=fa201775ac) | Jul 02, 2024 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [22926e0513](https://linux-hardware.org/?probe=22926e0513) | Jul 02, 2024 |
| HP            | 1495                        | Desktop     | [cd196863f3](https://linux-hardware.org/?probe=cd196863f3) | Jul 02, 2024 |
| ASUSTek       | S551LN                      | Notebook    | [f688204027](https://linux-hardware.org/?probe=f688204027) | Jul 02, 2024 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [269dcf91b7](https://linux-hardware.org/?probe=269dcf91b7) | Jul 01, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [63adc91261](https://linux-hardware.org/?probe=63adc91261) | Jul 01, 2024 |
| HP            | Folio 13                    | Notebook    | [04ee1d8480](https://linux-hardware.org/?probe=04ee1d8480) | Jul 01, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e8b885d16c](https://linux-hardware.org/?probe=e8b885d16c) | Jul 01, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [96b756fda4](https://linux-hardware.org/?probe=96b756fda4) | Jun 30, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3688917ab8](https://linux-hardware.org/?probe=3688917ab8) | Jun 30, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [6e4a727140](https://linux-hardware.org/?probe=6e4a727140) | Jun 30, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7c6efb1095](https://linux-hardware.org/?probe=7c6efb1095) | Jun 30, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [e893cc7e62](https://linux-hardware.org/?probe=e893cc7e62) | Jun 29, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [dcab224dcc](https://linux-hardware.org/?probe=dcab224dcc) | Jun 29, 2024 |
| Acer          | AOD257                      | Notebook    | [be9d7a24d6](https://linux-hardware.org/?probe=be9d7a24d6) | Jun 29, 2024 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [464c82e7d2](https://linux-hardware.org/?probe=464c82e7d2) | Jun 29, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b23ddd687d](https://linux-hardware.org/?probe=b23ddd687d) | Jun 29, 2024 |
| Medion        | MAG Z390M MORTAR            | Desktop     | [01f25763d5](https://linux-hardware.org/?probe=01f25763d5) | Jun 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [03cb959918](https://linux-hardware.org/?probe=03cb959918) | Jun 29, 2024 |
| Dell          | Latitude E5450              | Notebook    | [8a88a5724d](https://linux-hardware.org/?probe=8a88a5724d) | Jun 29, 2024 |
| ASRock        | X370M Pro4                  | Desktop     | [65e29ff944](https://linux-hardware.org/?probe=65e29ff944) | Jun 29, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6024f234f9](https://linux-hardware.org/?probe=6024f234f9) | Jun 28, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [8d9438d6cd](https://linux-hardware.org/?probe=8d9438d6cd) | Jun 28, 2024 |
| Dell          | Precision 3581              | Notebook    | [88ae29c93e](https://linux-hardware.org/?probe=88ae29c93e) | Jun 28, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [9cfa79abea](https://linux-hardware.org/?probe=9cfa79abea) | Jun 28, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [f00a1ad952](https://linux-hardware.org/?probe=f00a1ad952) | Jun 28, 2024 |
| Toshiba       | Satellite C850-B524         | Notebook    | [9b83cfd874](https://linux-hardware.org/?probe=9b83cfd874) | Jun 27, 2024 |
| MSI           | A320M PRO-VD/S              | Desktop     | [4c9657cf8f](https://linux-hardware.org/?probe=4c9657cf8f) | Jun 27, 2024 |
| Acer          | Predator PT316-51s          | Notebook    | [4eaaff5dc9](https://linux-hardware.org/?probe=4eaaff5dc9) | Jun 26, 2024 |
| HP            | 2B2C                        | Desktop     | [c370ca2da9](https://linux-hardware.org/?probe=c370ca2da9) | Jun 26, 2024 |
| HP            | 8053                        | Desktop     | [882315caa6](https://linux-hardware.org/?probe=882315caa6) | Jun 26, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [34712a7961](https://linux-hardware.org/?probe=34712a7961) | Jun 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [13a101288f](https://linux-hardware.org/?probe=13a101288f) | Jun 25, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [b2f4ec3a3a](https://linux-hardware.org/?probe=b2f4ec3a3a) | Jun 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [5e9b93f0ff](https://linux-hardware.org/?probe=5e9b93f0ff) | Jun 25, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [51ebd1fdae](https://linux-hardware.org/?probe=51ebd1fdae) | Jun 24, 2024 |
| ASRock        | X670E Pro RS                | Desktop     | [42bb8b9dc7](https://linux-hardware.org/?probe=42bb8b9dc7) | Jun 24, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [7e56da8bf4](https://linux-hardware.org/?probe=7e56da8bf4) | Jun 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [b72fca7306](https://linux-hardware.org/?probe=b72fca7306) | Jun 24, 2024 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [a3be576623](https://linux-hardware.org/?probe=a3be576623) | Jun 23, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de8abf8320](https://linux-hardware.org/?probe=de8abf8320) | Jun 23, 2024 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [412057df6b](https://linux-hardware.org/?probe=412057df6b) | Jun 23, 2024 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [f35cbc41cb](https://linux-hardware.org/?probe=f35cbc41cb) | Jun 23, 2024 |
| HP            | ENVY 17                     | Notebook    | [4da0c0dfda](https://linux-hardware.org/?probe=4da0c0dfda) | Jun 23, 2024 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [5ecb1a2831](https://linux-hardware.org/?probe=5ecb1a2831) | Jun 23, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [4b834151ff](https://linux-hardware.org/?probe=4b834151ff) | Jun 23, 2024 |
| Dell          | Inspiron 5759               | Notebook    | [257ab0a418](https://linux-hardware.org/?probe=257ab0a418) | Jun 22, 2024 |
| Microsoft     | Surface Go                  | Tablet      | [8e77a6133d](https://linux-hardware.org/?probe=8e77a6133d) | Jun 22, 2024 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [34de0a9462](https://linux-hardware.org/?probe=34de0a9462) | Jun 22, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [84a1bae019](https://linux-hardware.org/?probe=84a1bae019) | Jun 22, 2024 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [b4f3cb7cb2](https://linux-hardware.org/?probe=b4f3cb7cb2) | Jun 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [3b3002d062](https://linux-hardware.org/?probe=3b3002d062) | Jun 21, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [b39784c8de](https://linux-hardware.org/?probe=b39784c8de) | Jun 21, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [3047e08dec](https://linux-hardware.org/?probe=3047e08dec) | Jun 21, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [7ca2d90687](https://linux-hardware.org/?probe=7ca2d90687) | Jun 20, 2024 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [824457dc95](https://linux-hardware.org/?probe=824457dc95) | Jun 20, 2024 |
| ASUSTek       | Z97-A                       | Desktop     | [29ecbc5589](https://linux-hardware.org/?probe=29ecbc5589) | Jun 20, 2024 |
| Acer          | Predator PT316-51s          | Notebook    | [c6dff2e738](https://linux-hardware.org/?probe=c6dff2e738) | Jun 20, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7bd5c92807](https://linux-hardware.org/?probe=7bd5c92807) | Jun 20, 2024 |
| Acer          | Lars                        | Notebook    | [dce4990fc5](https://linux-hardware.org/?probe=dce4990fc5) | Jun 19, 2024 |
| HP            | Pavilion dv6                | Notebook    | [6d30187c55](https://linux-hardware.org/?probe=6d30187c55) | Jun 19, 2024 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [a680cbc64f](https://linux-hardware.org/?probe=a680cbc64f) | Jun 18, 2024 |
| Jumper        | EZbook                      | Notebook    | [c645f63b1d](https://linux-hardware.org/?probe=c645f63b1d) | Jun 18, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [f27eb6502c](https://linux-hardware.org/?probe=f27eb6502c) | Jun 17, 2024 |
| Acer          | Aspire XC-605               | Desktop     | [0823e1deb1](https://linux-hardware.org/?probe=0823e1deb1) | Jun 17, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dd1e4ad6a1](https://linux-hardware.org/?probe=dd1e4ad6a1) | Jun 16, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8051e15b02](https://linux-hardware.org/?probe=8051e15b02) | Jun 16, 2024 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [aba1c7e44f](https://linux-hardware.org/?probe=aba1c7e44f) | Jun 16, 2024 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [2c9d74b7d3](https://linux-hardware.org/?probe=2c9d74b7d3) | Jun 16, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [d15c410d9d](https://linux-hardware.org/?probe=d15c410d9d) | Jun 15, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [9cb777bbd0](https://linux-hardware.org/?probe=9cb777bbd0) | Jun 15, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [822483ea88](https://linux-hardware.org/?probe=822483ea88) | Jun 14, 2024 |
| Lenovo        | Yoga 7 2-in-1 14AHP9 83D... | Convertible | [269768d400](https://linux-hardware.org/?probe=269768d400) | Jun 14, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [4c1e3978f4](https://linux-hardware.org/?probe=4c1e3978f4) | Jun 14, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [1e0d37ab0f](https://linux-hardware.org/?probe=1e0d37ab0f) | Jun 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [990db2a166](https://linux-hardware.org/?probe=990db2a166) | Jun 14, 2024 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [60f09523bd](https://linux-hardware.org/?probe=60f09523bd) | Jun 13, 2024 |
| ASUSTek       | Zenbook UX8402ZE_UX8402Z... | Notebook    | [5541061e08](https://linux-hardware.org/?probe=5541061e08) | Jun 12, 2024 |
| Alienware     | M14xR2                      | Notebook    | [18ff5aad9f](https://linux-hardware.org/?probe=18ff5aad9f) | Jun 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e57acd1ee1](https://linux-hardware.org/?probe=e57acd1ee1) | Jun 11, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [5b1865c7a4](https://linux-hardware.org/?probe=5b1865c7a4) | Jun 11, 2024 |
| System76      | Oryx Pro                    | Notebook    | [62625b4530](https://linux-hardware.org/?probe=62625b4530) | Jun 10, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3cfbaa4424](https://linux-hardware.org/?probe=3cfbaa4424) | Jun 10, 2024 |
| Biostar       | H510MHP                     | Desktop     | [80bd5a6ab1](https://linux-hardware.org/?probe=80bd5a6ab1) | Jun 09, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [e863d2b8ce](https://linux-hardware.org/?probe=e863d2b8ce) | Jun 08, 2024 |
| Sony          | SVF15212SNW                 | Notebook    | [aabfef4f8c](https://linux-hardware.org/?probe=aabfef4f8c) | Jun 08, 2024 |
| Computer D... | W240EU/W250EUQ/W270EUQ      | Notebook    | [910415248e](https://linux-hardware.org/?probe=910415248e) | Jun 08, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [8211ffc9b9](https://linux-hardware.org/?probe=8211ffc9b9) | Jun 07, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [92cb83187e](https://linux-hardware.org/?probe=92cb83187e) | Jun 07, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [d1d6841038](https://linux-hardware.org/?probe=d1d6841038) | Jun 07, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [6712e54c02](https://linux-hardware.org/?probe=6712e54c02) | Jun 07, 2024 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [2611518af0](https://linux-hardware.org/?probe=2611518af0) | Jun 06, 2024 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [ed554c7b58](https://linux-hardware.org/?probe=ed554c7b58) | Jun 06, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [48e65e34a9](https://linux-hardware.org/?probe=48e65e34a9) | Jun 06, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [d1313b1f24](https://linux-hardware.org/?probe=d1313b1f24) | Jun 06, 2024 |
| Intel         | NUC13ANBi3 N13056-202       | Mini pc     | [b66427f026](https://linux-hardware.org/?probe=b66427f026) | Jun 05, 2024 |
| Intel         | NUC13ANBi3 N13056-202       | Mini pc     | [23c0160ba0](https://linux-hardware.org/?probe=23c0160ba0) | Jun 05, 2024 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [0d35e8cc84](https://linux-hardware.org/?probe=0d35e8cc84) | Jun 05, 2024 |
| Lenovo        | XiaoXinAir 15ITL 2021 82... | Notebook    | [769af1d021](https://linux-hardware.org/?probe=769af1d021) | Jun 05, 2024 |
| Acer          | Aspire XC-605               | Desktop     | [0333530a8b](https://linux-hardware.org/?probe=0333530a8b) | Jun 05, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [1ff6721cbc](https://linux-hardware.org/?probe=1ff6721cbc) | Jun 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [827ca372c7](https://linux-hardware.org/?probe=827ca372c7) | Jun 05, 2024 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [a5ac10b4d5](https://linux-hardware.org/?probe=a5ac10b4d5) | Jun 04, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [574e2fa295](https://linux-hardware.org/?probe=574e2fa295) | Jun 04, 2024 |
| Framework     | Laptop                      | Notebook    | [1a232fe39e](https://linux-hardware.org/?probe=1a232fe39e) | Jun 04, 2024 |
| ASUSTek       | H81M-E                      | Desktop     | [860b682ea7](https://linux-hardware.org/?probe=860b682ea7) | Jun 03, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [b70501d2ed](https://linux-hardware.org/?probe=b70501d2ed) | Jun 02, 2024 |
| Sony          | SVF15212SNW                 | Notebook    | [2a3b5b2492](https://linux-hardware.org/?probe=2a3b5b2492) | Jun 02, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [bd53a6b27b](https://linux-hardware.org/?probe=bd53a6b27b) | Jun 02, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [ab1fae990c](https://linux-hardware.org/?probe=ab1fae990c) | Jun 02, 2024 |
| Lenovo        | 3716 SDK0J40709 WIN 3259... | Desktop     | [ccaf5aa9c4](https://linux-hardware.org/?probe=ccaf5aa9c4) | Jun 02, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [ee5484cf0b](https://linux-hardware.org/?probe=ee5484cf0b) | Jun 02, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [f3cc621f63](https://linux-hardware.org/?probe=f3cc621f63) | Jun 01, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [ceb3eb9275](https://linux-hardware.org/?probe=ceb3eb9275) | May 31, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [2db6b3bc8b](https://linux-hardware.org/?probe=2db6b3bc8b) | May 31, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | Notebook    | [ea87d9525c](https://linux-hardware.org/?probe=ea87d9525c) | May 31, 2024 |
| HP            | Pavilion 15                 | Notebook    | [b217cf57f0](https://linux-hardware.org/?probe=b217cf57f0) | May 30, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [9272513345](https://linux-hardware.org/?probe=9272513345) | May 30, 2024 |
| Google        | Peppy                       | Notebook    | [865fb93195](https://linux-hardware.org/?probe=865fb93195) | May 30, 2024 |
| ASUSTek       | A88XM-E/USB                 | Desktop     | [f3bc277c6b](https://linux-hardware.org/?probe=f3bc277c6b) | May 29, 2024 |
| NEC Comput... | PC-VY25AAZR7                | Notebook    | [4f0ba53785](https://linux-hardware.org/?probe=4f0ba53785) | May 29, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [dc62a04668](https://linux-hardware.org/?probe=dc62a04668) | May 29, 2024 |
| HP            | 2B0D A01                    | All in one  | [d7f930780c](https://linux-hardware.org/?probe=d7f930780c) | May 28, 2024 |
| INET          | Z12B                        | Mini pc     | [6d2a7397d1](https://linux-hardware.org/?probe=6d2a7397d1) | May 28, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [534f5e8708](https://linux-hardware.org/?probe=534f5e8708) | May 28, 2024 |
| Lenovo        | ThinkPad L490 20Q6S93T00    | Notebook    | [d289a1a217](https://linux-hardware.org/?probe=d289a1a217) | May 28, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [db1ab57fd8](https://linux-hardware.org/?probe=db1ab57fd8) | May 28, 2024 |
| ASRock        | A320M/ac                    | Desktop     | [c75b099b4f](https://linux-hardware.org/?probe=c75b099b4f) | May 27, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [759686893f](https://linux-hardware.org/?probe=759686893f) | May 27, 2024 |
| ASUSTek       | A88XM-E/USB                 | Desktop     | [7872140812](https://linux-hardware.org/?probe=7872140812) | May 27, 2024 |
| MSI           | X99A GODLIKE GAMING CARB... | Desktop     | [b93de9cc86](https://linux-hardware.org/?probe=b93de9cc86) | May 27, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [911c4c5beb](https://linux-hardware.org/?probe=911c4c5beb) | May 26, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [18e7ec53a7](https://linux-hardware.org/?probe=18e7ec53a7) | May 26, 2024 |
| MSI           | MEG X570 ACE                | Desktop     | [dc6d05d734](https://linux-hardware.org/?probe=dc6d05d734) | May 26, 2024 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [2e7f40d00f](https://linux-hardware.org/?probe=2e7f40d00f) | May 26, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [58495c89d8](https://linux-hardware.org/?probe=58495c89d8) | May 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [c6e7aa154b](https://linux-hardware.org/?probe=c6e7aa154b) | May 25, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [34380f7af8](https://linux-hardware.org/?probe=34380f7af8) | May 25, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [4792948fe4](https://linux-hardware.org/?probe=4792948fe4) | May 24, 2024 |
| HP            | Folio 13                    | Notebook    | [1590d35611](https://linux-hardware.org/?probe=1590d35611) | May 23, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [46e41cfcd5](https://linux-hardware.org/?probe=46e41cfcd5) | May 23, 2024 |
| Dell          | Inspiron 13 5330            | Notebook    | [bf22ef091a](https://linux-hardware.org/?probe=bf22ef091a) | May 23, 2024 |
| HP            | Pavilion Laptop 14-bk1xx    | Notebook    | [ebaedcc4ab](https://linux-hardware.org/?probe=ebaedcc4ab) | May 23, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [c2cb0c1b2a](https://linux-hardware.org/?probe=c2cb0c1b2a) | May 23, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [d67cb5d7ec](https://linux-hardware.org/?probe=d67cb5d7ec) | May 23, 2024 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [a15056ed04](https://linux-hardware.org/?probe=a15056ed04) | May 22, 2024 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [14af57730c](https://linux-hardware.org/?probe=14af57730c) | May 22, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [b817212e79](https://linux-hardware.org/?probe=b817212e79) | May 22, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [73f9290f9b](https://linux-hardware.org/?probe=73f9290f9b) | May 22, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [eaf9fa8e3b](https://linux-hardware.org/?probe=eaf9fa8e3b) | May 22, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [ceff35c915](https://linux-hardware.org/?probe=ceff35c915) | May 22, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [e572246965](https://linux-hardware.org/?probe=e572246965) | May 22, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5d83ab9730](https://linux-hardware.org/?probe=5d83ab9730) | May 22, 2024 |
| Biostar       | A10N-9630E                  | Desktop     | [581dcc6f2e](https://linux-hardware.org/?probe=581dcc6f2e) | May 22, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [57f0c1332e](https://linux-hardware.org/?probe=57f0c1332e) | May 22, 2024 |
| SYWZ          | S210H Series                | Desktop     | [dd23648417](https://linux-hardware.org/?probe=dd23648417) | May 21, 2024 |
| Unknown       | Unknown                     | Notebook    | [c9b4ab2b7c](https://linux-hardware.org/?probe=c9b4ab2b7c) | May 21, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [801ac614fb](https://linux-hardware.org/?probe=801ac614fb) | May 20, 2024 |
| MSI           | Prestige 15 A10SC           | Notebook    | [be65aec8b2](https://linux-hardware.org/?probe=be65aec8b2) | May 20, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [715b80acf5](https://linux-hardware.org/?probe=715b80acf5) | May 20, 2024 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [3417586e6c](https://linux-hardware.org/?probe=3417586e6c) | May 20, 2024 |
| Lenovo        | ThinkPad P50 20EQS3X10C     | Notebook    | [2859984d97](https://linux-hardware.org/?probe=2859984d97) | May 19, 2024 |
| Dell          | Inspiron 5468               | Notebook    | [266dc7095b](https://linux-hardware.org/?probe=266dc7095b) | May 19, 2024 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [b772ef73f7](https://linux-hardware.org/?probe=b772ef73f7) | May 19, 2024 |
| Toshiba       | Satellite S55-A             | Notebook    | [e1eb3baa10](https://linux-hardware.org/?probe=e1eb3baa10) | May 18, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [2e183ea08a](https://linux-hardware.org/?probe=2e183ea08a) | May 18, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [68583d84cf](https://linux-hardware.org/?probe=68583d84cf) | May 18, 2024 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [55679071f3](https://linux-hardware.org/?probe=55679071f3) | May 18, 2024 |
| Lenovo        | ThinkPad T460 20FMS0Y600    | Notebook    | [f07f2852ab](https://linux-hardware.org/?probe=f07f2852ab) | May 18, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [e4cffb0ae3](https://linux-hardware.org/?probe=e4cffb0ae3) | May 18, 2024 |
| HP            | 802E                        | Desktop     | [0bbef6be9a](https://linux-hardware.org/?probe=0bbef6be9a) | May 18, 2024 |
| Intel         | X99                         | Desktop     | [b2a18ce6a9](https://linux-hardware.org/?probe=b2a18ce6a9) | May 17, 2024 |
| Toshiba       | Satellite C850-B524         | Notebook    | [651d7e556b](https://linux-hardware.org/?probe=651d7e556b) | May 17, 2024 |
| Unknown       | HX90                        | Desktop     | [1a1ccc00aa](https://linux-hardware.org/?probe=1a1ccc00aa) | May 17, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [05e6899e5d](https://linux-hardware.org/?probe=05e6899e5d) | May 16, 2024 |
| INET          | Z12B                        | Mini pc     | [1c38a666d2](https://linux-hardware.org/?probe=1c38a666d2) | May 16, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a2a1657573](https://linux-hardware.org/?probe=a2a1657573) | May 16, 2024 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [3d6162a289](https://linux-hardware.org/?probe=3d6162a289) | May 16, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [d353837417](https://linux-hardware.org/?probe=d353837417) | May 15, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [60672407b2](https://linux-hardware.org/?probe=60672407b2) | May 15, 2024 |
| Dell          | Latitude 7490               | Notebook    | [2035401665](https://linux-hardware.org/?probe=2035401665) | May 15, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [052d7d9fb4](https://linux-hardware.org/?probe=052d7d9fb4) | May 15, 2024 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | Notebook    | [d5633e7cde](https://linux-hardware.org/?probe=d5633e7cde) | May 15, 2024 |
| ASUSTek       | H110M-A                     | Desktop     | [16c08bf32a](https://linux-hardware.org/?probe=16c08bf32a) | May 14, 2024 |
| Intel         | B75                         | Desktop     | [c896322be3](https://linux-hardware.org/?probe=c896322be3) | May 14, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [f2b539b063](https://linux-hardware.org/?probe=f2b539b063) | May 14, 2024 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d03fc6ca71](https://linux-hardware.org/?probe=d03fc6ca71) | May 14, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [2f12b92881](https://linux-hardware.org/?probe=2f12b92881) | May 14, 2024 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [840d8d9d03](https://linux-hardware.org/?probe=840d8d9d03) | May 13, 2024 |
| Schenker      | KEY16_17_SKE16_17E19_M19    | Notebook    | [b1d6c02fd6](https://linux-hardware.org/?probe=b1d6c02fd6) | May 12, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [80132f1ea4](https://linux-hardware.org/?probe=80132f1ea4) | May 12, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8957a41459](https://linux-hardware.org/?probe=8957a41459) | May 12, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [e3f9b42de5](https://linux-hardware.org/?probe=e3f9b42de5) | May 12, 2024 |
| Dell          | XPS 13 9380                 | Notebook    | [47aec6e343](https://linux-hardware.org/?probe=47aec6e343) | May 11, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9a65b78ec1](https://linux-hardware.org/?probe=9a65b78ec1) | May 11, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9fd24b64e1](https://linux-hardware.org/?probe=9fd24b64e1) | May 11, 2024 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [826c438407](https://linux-hardware.org/?probe=826c438407) | May 10, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c3e24c6a8e](https://linux-hardware.org/?probe=c3e24c6a8e) | May 10, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [c91df0ad77](https://linux-hardware.org/?probe=c91df0ad77) | May 10, 2024 |
| Acer          | Aspire E5-411G              | Notebook    | [82675c702e](https://linux-hardware.org/?probe=82675c702e) | May 10, 2024 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [65b8f85c07](https://linux-hardware.org/?probe=65b8f85c07) | May 09, 2024 |
| Sony          | SVD11225CLB                 | Notebook    | [cbc4c57710](https://linux-hardware.org/?probe=cbc4c57710) | May 09, 2024 |
| Lenovo        | ThinkPad T470 20HES18C00    | Notebook    | [a2d8841244](https://linux-hardware.org/?probe=a2d8841244) | May 08, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [cb100ba8bc](https://linux-hardware.org/?probe=cb100ba8bc) | May 08, 2024 |
| Acer          | Aspire 5720                 | Notebook    | [0a218dfdfe](https://linux-hardware.org/?probe=0a218dfdfe) | May 08, 2024 |
| EVOC          | P7xxTM1                     | Notebook    | [7c15b2991c](https://linux-hardware.org/?probe=7c15b2991c) | May 08, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [5aee2550ce](https://linux-hardware.org/?probe=5aee2550ce) | May 08, 2024 |
| Lenovo        | B50-30 80ES                 | Notebook    | [c19f3dfc3a](https://linux-hardware.org/?probe=c19f3dfc3a) | May 07, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [6b97d23143](https://linux-hardware.org/?probe=6b97d23143) | May 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [de2ed6e188](https://linux-hardware.org/?probe=de2ed6e188) | May 07, 2024 |
| Dell          | 0V8DVD A01                  | All in one  | [2018075583](https://linux-hardware.org/?probe=2018075583) | May 07, 2024 |
| Gigabyte      | H81M-H                      | Desktop     | [5ea3b70747](https://linux-hardware.org/?probe=5ea3b70747) | May 06, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [3679c79ac4](https://linux-hardware.org/?probe=3679c79ac4) | May 06, 2024 |
| Unknown       | Unknown                     | Notebook    | [a857b08dd7](https://linux-hardware.org/?probe=a857b08dd7) | May 06, 2024 |
| Acer          | Lars                        | Notebook    | [6ec82dab78](https://linux-hardware.org/?probe=6ec82dab78) | May 05, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4c7d6f1e6a](https://linux-hardware.org/?probe=4c7d6f1e6a) | May 05, 2024 |
| Dell          | Latitude 5410               | Notebook    | [8302f81328](https://linux-hardware.org/?probe=8302f81328) | May 04, 2024 |
| Dell          | 03NVJ6 A03                  | Desktop     | [fd0f0fad2d](https://linux-hardware.org/?probe=fd0f0fad2d) | May 04, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [9ca1c7c92f](https://linux-hardware.org/?probe=9ca1c7c92f) | May 04, 2024 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [055f5e4645](https://linux-hardware.org/?probe=055f5e4645) | May 04, 2024 |
| Gigabyte      | B365M H                     | Desktop     | [26c29ceb49](https://linux-hardware.org/?probe=26c29ceb49) | May 04, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [277b1dc273](https://linux-hardware.org/?probe=277b1dc273) | May 04, 2024 |
| Dell          | 0C2XKD A01                  | Desktop     | [a246668749](https://linux-hardware.org/?probe=a246668749) | May 04, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [b7341e861f](https://linux-hardware.org/?probe=b7341e861f) | May 03, 2024 |
| HP            | 83F0                        | Desktop     | [896e46f757](https://linux-hardware.org/?probe=896e46f757) | May 03, 2024 |
| Acer          | Swift SFG14-72              | Notebook    | [00c7e89498](https://linux-hardware.org/?probe=00c7e89498) | May 03, 2024 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [82d8781e9b](https://linux-hardware.org/?probe=82d8781e9b) | May 03, 2024 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [9b4c380b5e](https://linux-hardware.org/?probe=9b4c380b5e) | May 03, 2024 |
| MSI           | MAG B460M MORTAR            | Desktop     | [4c66dab9c1](https://linux-hardware.org/?probe=4c66dab9c1) | May 03, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [a493ee87d2](https://linux-hardware.org/?probe=a493ee87d2) | May 02, 2024 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [64005c86c7](https://linux-hardware.org/?probe=64005c86c7) | May 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e02873ea23](https://linux-hardware.org/?probe=e02873ea23) | May 02, 2024 |
| Intel         | H55                         | Desktop     | [b7cf243933](https://linux-hardware.org/?probe=b7cf243933) | May 02, 2024 |
| American M... | E5 Ver:3.2S                 | Desktop     | [748bf7d3e8](https://linux-hardware.org/?probe=748bf7d3e8) | May 01, 2024 |
| Acer          | Aspire SW5-173              | Notebook    | [e72a0709d4](https://linux-hardware.org/?probe=e72a0709d4) | May 01, 2024 |
| ECT           | Unknown                     | Notebook    | [0ebb9fcdd0](https://linux-hardware.org/?probe=0ebb9fcdd0) | May 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ad08810e0e](https://linux-hardware.org/?probe=ad08810e0e) | May 01, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [6df35e20b1](https://linux-hardware.org/?probe=6df35e20b1) | May 01, 2024 |
| Dell          | 00F82W A00                  | Desktop     | [850344d254](https://linux-hardware.org/?probe=850344d254) | Apr 30, 2024 |
| Intel         | H61S                        | Desktop     | [6b425a599b](https://linux-hardware.org/?probe=6b425a599b) | Apr 30, 2024 |
| Acer          | H81-M1                      | Desktop     | [cf0c78b108](https://linux-hardware.org/?probe=cf0c78b108) | Apr 30, 2024 |
| Pegatron      | NARRA3                      | Desktop     | [ca94843c0a](https://linux-hardware.org/?probe=ca94843c0a) | Apr 29, 2024 |
| ASRock        | A320M/ac                    | Desktop     | [aeafdb6795](https://linux-hardware.org/?probe=aeafdb6795) | Apr 29, 2024 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [d4d6667b5e](https://linux-hardware.org/?probe=d4d6667b5e) | Apr 29, 2024 |
| Dell          | G7 7588                     | Notebook    | [9745a22fe0](https://linux-hardware.org/?probe=9745a22fe0) | Apr 28, 2024 |
| HP            | 3029h                       | Desktop     | [1ae766a3ba](https://linux-hardware.org/?probe=1ae766a3ba) | Apr 28, 2024 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | Notebook    | [15fdd20de0](https://linux-hardware.org/?probe=15fdd20de0) | Apr 28, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [16169fa717](https://linux-hardware.org/?probe=16169fa717) | Apr 28, 2024 |
| Dell          | 0WWJRX A01                  | Desktop     | [21af8ccdc8](https://linux-hardware.org/?probe=21af8ccdc8) | Apr 27, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [5004ab8c5b](https://linux-hardware.org/?probe=5004ab8c5b) | Apr 27, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [21e5ae7f3e](https://linux-hardware.org/?probe=21e5ae7f3e) | Apr 27, 2024 |
| Dell          | Latitude E7450              | Notebook    | [eb354c66fa](https://linux-hardware.org/?probe=eb354c66fa) | Apr 27, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [85005d847f](https://linux-hardware.org/?probe=85005d847f) | Apr 27, 2024 |
| Dell          | Latitude 5300               | Notebook    | [dfae5f452a](https://linux-hardware.org/?probe=dfae5f452a) | Apr 27, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [4324e618e8](https://linux-hardware.org/?probe=4324e618e8) | Apr 27, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0ff3e84a1c](https://linux-hardware.org/?probe=0ff3e84a1c) | Apr 27, 2024 |
| Dell          | Inspiron 3558               | Notebook    | [1fe97163aa](https://linux-hardware.org/?probe=1fe97163aa) | Apr 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [a1db5a84e2](https://linux-hardware.org/?probe=a1db5a84e2) | Apr 26, 2024 |
| Acer          | Aspire XC-605               | Desktop     | [d1ebb51ac8](https://linux-hardware.org/?probe=d1ebb51ac8) | Apr 25, 2024 |
| HP            | 2B36                        | Desktop     | [d52be34009](https://linux-hardware.org/?probe=d52be34009) | Apr 25, 2024 |
| Sony          | SVF1521X1RB                 | Notebook    | [49942872ab](https://linux-hardware.org/?probe=49942872ab) | Apr 25, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [9850b81106](https://linux-hardware.org/?probe=9850b81106) | Apr 25, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [7260ec24ee](https://linux-hardware.org/?probe=7260ec24ee) | Apr 25, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [b27f71816a](https://linux-hardware.org/?probe=b27f71816a) | Apr 24, 2024 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [dc86ce5b59](https://linux-hardware.org/?probe=dc86ce5b59) | Apr 24, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [1d5f001265](https://linux-hardware.org/?probe=1d5f001265) | Apr 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [280fa2d735](https://linux-hardware.org/?probe=280fa2d735) | Apr 24, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [7bb8c6f187](https://linux-hardware.org/?probe=7bb8c6f187) | Apr 24, 2024 |
| HP            | Laptop 17z-ca100            | Notebook    | [80cb3eace6](https://linux-hardware.org/?probe=80cb3eace6) | Apr 23, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [488c5e3d42](https://linux-hardware.org/?probe=488c5e3d42) | Apr 23, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [6c32f9323b](https://linux-hardware.org/?probe=6c32f9323b) | Apr 23, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [28cc5a5993](https://linux-hardware.org/?probe=28cc5a5993) | Apr 23, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [d3bf170f28](https://linux-hardware.org/?probe=d3bf170f28) | Apr 22, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c2d77decab](https://linux-hardware.org/?probe=c2d77decab) | Apr 22, 2024 |
| INET          | Z12B                        | Mini pc     | [5fbb33ad1d](https://linux-hardware.org/?probe=5fbb33ad1d) | Apr 22, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [3b1f047a27](https://linux-hardware.org/?probe=3b1f047a27) | Apr 22, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [8e6a73d201](https://linux-hardware.org/?probe=8e6a73d201) | Apr 22, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7d3fad530f](https://linux-hardware.org/?probe=7d3fad530f) | Apr 22, 2024 |
| HP            | 802F                        | Desktop     | [8a38f4d001](https://linux-hardware.org/?probe=8a38f4d001) | Apr 21, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [d9d4c8fda0](https://linux-hardware.org/?probe=d9d4c8fda0) | Apr 21, 2024 |
| Dell          | Latitude E5400              | Notebook    | [fba5edc10c](https://linux-hardware.org/?probe=fba5edc10c) | Apr 21, 2024 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [16b4e64118](https://linux-hardware.org/?probe=16b4e64118) | Apr 21, 2024 |
| HP            | Presario CQ56               | Notebook    | [80adb74ef1](https://linux-hardware.org/?probe=80adb74ef1) | Apr 21, 2024 |
| HP            | 2B36                        | Desktop     | [4b5101fd25](https://linux-hardware.org/?probe=4b5101fd25) | Apr 21, 2024 |
| Dell          | 00F82W A00                  | Desktop     | [8d86d9c0a6](https://linux-hardware.org/?probe=8d86d9c0a6) | Apr 21, 2024 |
| HP            | 802F                        | Desktop     | [cb7a0fabc8](https://linux-hardware.org/?probe=cb7a0fabc8) | Apr 21, 2024 |
| MSI           | A320M PRO-VD/S              | Desktop     | [1c4a853ae2](https://linux-hardware.org/?probe=1c4a853ae2) | Apr 21, 2024 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [eb8b3c8970](https://linux-hardware.org/?probe=eb8b3c8970) | Apr 21, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [5b29bd1ecf](https://linux-hardware.org/?probe=5b29bd1ecf) | Apr 21, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [713e7bdc86](https://linux-hardware.org/?probe=713e7bdc86) | Apr 20, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [24e31227a4](https://linux-hardware.org/?probe=24e31227a4) | Apr 20, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [4eade3ca4d](https://linux-hardware.org/?probe=4eade3ca4d) | Apr 20, 2024 |
| Acer          | Enduro EUN314-51W           | Notebook    | [7a57f25e0e](https://linux-hardware.org/?probe=7a57f25e0e) | Apr 20, 2024 |
| HP            | 18E7                        | Desktop     | [1d707ddc17](https://linux-hardware.org/?probe=1d707ddc17) | Apr 20, 2024 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [19d3a51e2c](https://linux-hardware.org/?probe=19d3a51e2c) | Apr 20, 2024 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [d96460dbea](https://linux-hardware.org/?probe=d96460dbea) | Apr 20, 2024 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [f83f880363](https://linux-hardware.org/?probe=f83f880363) | Apr 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [bda99e9656](https://linux-hardware.org/?probe=bda99e9656) | Apr 20, 2024 |
| Unknown       | Unknown                     | Desktop     | [4f687b566d](https://linux-hardware.org/?probe=4f687b566d) | Apr 20, 2024 |
| Acer          | Aspire A314-22              | Notebook    | [cb041e53b1](https://linux-hardware.org/?probe=cb041e53b1) | Apr 20, 2024 |
| Dell          | Precision 7720              | Notebook    | [53cebf5b16](https://linux-hardware.org/?probe=53cebf5b16) | Apr 20, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [290ea848f0](https://linux-hardware.org/?probe=290ea848f0) | Apr 19, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [af4cc3e115](https://linux-hardware.org/?probe=af4cc3e115) | Apr 19, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [aa8437e096](https://linux-hardware.org/?probe=aa8437e096) | Apr 19, 2024 |
| ASUSTek       | D425MC                      | Desktop     | [7be445a3bf](https://linux-hardware.org/?probe=7be445a3bf) | Apr 19, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [326cc8c1ea](https://linux-hardware.org/?probe=326cc8c1ea) | Apr 19, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [5378e196b0](https://linux-hardware.org/?probe=5378e196b0) | Apr 19, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [5acad8a956](https://linux-hardware.org/?probe=5acad8a956) | Apr 19, 2024 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [3c0df82050](https://linux-hardware.org/?probe=3c0df82050) | Apr 19, 2024 |
| DFI           | HD101-H81D                  | Desktop     | [a6b195fbc8](https://linux-hardware.org/?probe=a6b195fbc8) | Apr 18, 2024 |
| Acer          | Aspire XC-605               | Desktop     | [d9014cb8e6](https://linux-hardware.org/?probe=d9014cb8e6) | Apr 18, 2024 |
| Unknown       | Unknown                     | Desktop     | [8424abb1e7](https://linux-hardware.org/?probe=8424abb1e7) | Apr 18, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [78d6c9eb2c](https://linux-hardware.org/?probe=78d6c9eb2c) | Apr 18, 2024 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [05c7db4b10](https://linux-hardware.org/?probe=05c7db4b10) | Apr 18, 2024 |
| Dell          | 0V8F20 A01                  | Desktop     | [5b99cd208d](https://linux-hardware.org/?probe=5b99cd208d) | Apr 17, 2024 |
| Sony          | SVF1521X1RB                 | Notebook    | [9e0873ff32](https://linux-hardware.org/?probe=9e0873ff32) | Apr 17, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [f95926a55e](https://linux-hardware.org/?probe=f95926a55e) | Apr 17, 2024 |
| Lenovo        | 36EB NOK                    | Desktop     | [c83418c56a](https://linux-hardware.org/?probe=c83418c56a) | Apr 17, 2024 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [86e82df824](https://linux-hardware.org/?probe=86e82df824) | Apr 17, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [f61bc8b75c](https://linux-hardware.org/?probe=f61bc8b75c) | Apr 17, 2024 |
| Biostar       | H61MLC                      | Desktop     | [8f70d8bdb9](https://linux-hardware.org/?probe=8f70d8bdb9) | Apr 16, 2024 |
| Acer          | H81-M1                      | Desktop     | [1c508f5a38](https://linux-hardware.org/?probe=1c508f5a38) | Apr 16, 2024 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a9de65b3dc](https://linux-hardware.org/?probe=a9de65b3dc) | Apr 16, 2024 |
| MSI           | PRO B650-S WIFI             | Desktop     | [580df50da1](https://linux-hardware.org/?probe=580df50da1) | Apr 16, 2024 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [2667935967](https://linux-hardware.org/?probe=2667935967) | Apr 16, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [546afe3c79](https://linux-hardware.org/?probe=546afe3c79) | Apr 15, 2024 |
| HP            | OMEN Laptop 15-en1001np ... | Notebook    | [a9e386b4a8](https://linux-hardware.org/?probe=a9e386b4a8) | Apr 15, 2024 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a8d2383fa0](https://linux-hardware.org/?probe=a8d2383fa0) | Apr 15, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [154867d800](https://linux-hardware.org/?probe=154867d800) | Apr 14, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [16d5936653](https://linux-hardware.org/?probe=16d5936653) | Apr 14, 2024 |
| Dell          | G7 7588                     | Notebook    | [06f5f64e59](https://linux-hardware.org/?probe=06f5f64e59) | Apr 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [c88e8fcf4f](https://linux-hardware.org/?probe=c88e8fcf4f) | Apr 14, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [49aec34132](https://linux-hardware.org/?probe=49aec34132) | Apr 13, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [20e54ade99](https://linux-hardware.org/?probe=20e54ade99) | Apr 13, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b8f62dc34c](https://linux-hardware.org/?probe=b8f62dc34c) | Apr 13, 2024 |
| ASUSTek       | X550JX                      | Notebook    | [10e9087348](https://linux-hardware.org/?probe=10e9087348) | Apr 13, 2024 |
| HP            | Folio 13                    | Notebook    | [2112e4d193](https://linux-hardware.org/?probe=2112e4d193) | Apr 13, 2024 |
| MSI           | GP63 Leopard 8RE            | Notebook    | [31525e1fa0](https://linux-hardware.org/?probe=31525e1fa0) | Apr 13, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [705cf8272f](https://linux-hardware.org/?probe=705cf8272f) | Apr 12, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [94b1f5a4cd](https://linux-hardware.org/?probe=94b1f5a4cd) | Apr 12, 2024 |
| BESSTAR Te... | X400                        | Notebook    | [0701fdbfed](https://linux-hardware.org/?probe=0701fdbfed) | Apr 12, 2024 |
| HP            | 3397                        | Desktop     | [31cfb1bfb0](https://linux-hardware.org/?probe=31cfb1bfb0) | Apr 12, 2024 |
| Packard Be... | EasyNote LM98               | Notebook    | [e5f560059b](https://linux-hardware.org/?probe=e5f560059b) | Apr 12, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ed5c941b3f](https://linux-hardware.org/?probe=ed5c941b3f) | Apr 12, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [d688f191c9](https://linux-hardware.org/?probe=d688f191c9) | Apr 12, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [bc81c86e6b](https://linux-hardware.org/?probe=bc81c86e6b) | Apr 12, 2024 |
| Toshiba       | Satellite M645              | Notebook    | [f5c39a1c49](https://linux-hardware.org/?probe=f5c39a1c49) | Apr 12, 2024 |
| HP            | 89E9 0100                   | All in one  | [9fbed368d0](https://linux-hardware.org/?probe=9fbed368d0) | Apr 12, 2024 |
| Lenovo        | G40-30 80FY                 | Notebook    | [d1d8e1d51f](https://linux-hardware.org/?probe=d1d8e1d51f) | Apr 11, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 3144      | 93.4%   |
| ArcoLinux             | 174       | 5.17%   |
| ArcoLinux 20.6.5      | 11        | 0.33%   |
| ArcoLinux 20.7.5      | 8         | 0.24%   |
| ArcoLinux 20.3.4      | 4         | 0.12%   |
| ArcoLinux 20.3.3      | 3         | 0.09%   |
| ArcoLinux 20.2.12     | 3         | 0.09%   |
| ArcoLinux 19.12.15    | 3         | 0.09%   |
| ArcoLinux 19.07.11    | 3         | 0.09%   |
| ArcoLinux 20.1.4      | 2         | 0.06%   |
| ArcoLinux 19.02.4     | 2         | 0.06%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.03%   |
| ArcoLinux 6.9.2       | 1         | 0.03%   |
| ArcoLinux 6.9.1       | 1         | 0.03%   |
| ArcoLinux 20.5.7      | 1         | 0.03%   |
| ArcoLinux 20.5.2      | 1         | 0.03%   |
| ArcoLinux 20.4.11     | 1         | 0.03%   |
| ArcoLinux 20.2.9      | 1         | 0.03%   |
| ArcoLinux 19.11.3     | 1         | 0.03%   |
| ArcoLinux 19.03.3     | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 3336      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 6.6.1-arch1-1     | 80        | 1.82%   |
| 6.7.4-arch1-1     | 56        | 1.27%   |
| 5.15.7-arch1-1    | 47        | 1.07%   |
| 6.4.12-arch1-1    | 46        | 1.04%   |
| 6.7.9-arch1-1     | 44        | 1%      |
| 6.7.0-arch3-1     | 41        | 0.93%   |
| 6.3.8-arch1-1     | 40        | 0.91%   |
| 5.15.10-arch1-1   | 38        | 0.86%   |
| 5.13.13-arch1-1   | 38        | 0.86%   |
| 6.6.8-arch1-1     | 35        | 0.79%   |
| 6.5.9-arch2-1     | 33        | 0.75%   |
| 6.8.1-arch1-1     | 32        | 0.73%   |
| 6.5.8-arch1-1     | 32        | 0.73%   |
| 6.4.11-arch1-1    | 32        | 0.73%   |
| 6.3.9-arch1-1     | 30        | 0.68%   |
| 6.2.11-arch1-1    | 29        | 0.66%   |
| 6.8.2-arch2-1     | 28        | 0.64%   |
| 6.5.3-arch1-1     | 26        | 0.59%   |
| 6.3.2-arch1-1     | 26        | 0.59%   |
| 5.16.11-arch1-1   | 26        | 0.59%   |
| 5.14.14-arch1-1   | 26        | 0.59%   |
| 6.2.8-arch1-1     | 25        | 0.57%   |
| 6.9.4-1-cachyos   | 24        | 0.55%   |
| 6.6.7-arch1-1     | 22        | 0.5%    |
| 6.5.5-arch1-1     | 22        | 0.5%    |
| 6.10.4-1-cachyos  | 22        | 0.5%    |
| 5.13.12-arch1-1   | 22        | 0.5%    |
| 6.3.3-arch1-1     | 21        | 0.48%   |
| 5.14.12-arch1-1   | 21        | 0.48%   |
| 6.9.5-zen1-1-zen  | 20        | 0.45%   |
| 6.8.7-arch1-1     | 20        | 0.45%   |
| 6.5.7-arch1-1     | 20        | 0.45%   |
| 6.4.10-arch1-1    | 20        | 0.45%   |
| 6.12.1-zen1-1-zen | 20        | 0.45%   |
| 6.1.12-arch1-1    | 20        | 0.45%   |
| 6.6.3-arch1-1     | 19        | 0.43%   |
| 6.4.11-arch2-1    | 19        | 0.43%   |
| 6.3.7-arch1-1     | 19        | 0.43%   |
| 6.10.10-arch1-1   | 19        | 0.43%   |
| 6.6.2-arch1-1     | 18        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6.1   | 84        | 1.91%   |
| 6.7.4   | 65        | 1.48%   |
| 6.4.12  | 62        | 1.41%   |
| 5.15.7  | 59        | 1.34%   |
| 6.3.8   | 57        | 1.3%    |
| 6.4.11  | 56        | 1.27%   |
| 6.7.9   | 53        | 1.2%    |
| 6.7.0   | 49        | 1.11%   |
| 6.6.8   | 46        | 1.05%   |
| 6.9.1   | 42        | 0.95%   |
| 6.8.7   | 42        | 0.95%   |
| 6.8.2   | 42        | 0.95%   |
| 6.8.9   | 41        | 0.93%   |
| 5.15.10 | 40        | 0.91%   |
| 6.5.3   | 39        | 0.89%   |
| 6.5.9   | 38        | 0.86%   |
| 5.13.13 | 38        | 0.86%   |
| 6.10.10 | 37        | 0.84%   |
| 6.8.1   | 36        | 0.82%   |
| 6.3.2   | 35        | 0.8%    |
| 6.8.5   | 34        | 0.77%   |
| 6.5.8   | 34        | 0.77%   |
| 6.3.9   | 34        | 0.77%   |
| 6.10.4  | 34        | 0.77%   |
| 6.5.5   | 33        | 0.75%   |
| 6.3.1   | 33        | 0.75%   |
| 6.2.11  | 33        | 0.75%   |
| 6.9.5   | 32        | 0.73%   |
| 6.6.7   | 31        | 0.7%    |
| 6.3.3   | 29        | 0.66%   |
| 5.16.11 | 29        | 0.66%   |
| 6.2.8   | 28        | 0.64%   |
| 6.12.1  | 28        | 0.64%   |
| 6.1.12  | 28        | 0.64%   |
| 6.9.4   | 26        | 0.59%   |
| 6.5.7   | 26        | 0.59%   |
| 5.14.14 | 26        | 0.59%   |
| 6.3.5   | 25        | 0.57%   |
| 6.0.2   | 25        | 0.57%   |
| 5.17.1  | 25        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.6      | 353       | 8.48%   |
| 5.15     | 301       | 7.23%   |
| 6.1      | 277       | 6.65%   |
| 6.3      | 263       | 6.32%   |
| 6.7      | 256       | 6.15%   |
| 6.4      | 254       | 6.1%    |
| 6.8      | 218       | 5.24%   |
| 5.10     | 215       | 5.16%   |
| 6.5      | 199       | 4.78%   |
| 6.9      | 175       | 4.2%    |
| 6.2      | 151       | 3.63%   |
| 6.10     | 144       | 3.46%   |
| 5.16     | 133       | 3.19%   |
| 5.14     | 131       | 3.15%   |
| 6.0      | 122       | 2.93%   |
| 6.11     | 114       | 2.74%   |
| 5.13     | 112       | 2.69%   |
| 5.9      | 109       | 2.62%   |
| 5.12     | 105       | 2.52%   |
| 5.17     | 92        | 2.21%   |
| 5.18     | 89        | 2.14%   |
| 5.11     | 78        | 1.87%   |
| 5.19     | 72        | 1.73%   |
| 6.12     | 69        | 1.66%   |
| 5.4      | 59        | 1.42%   |
| 5.8      | 34        | 0.82%   |
| 5.6      | 7         | 0.17%   |
| 5.7      | 6         | 0.14%   |
| 5.5      | 5         | 0.12%   |
| 5.3      | 3         | 0.07%   |
| 5.0      | 3         | 0.07%   |
| 6.3.3    | 2         | 0.05%   |
| 5.15.96  | 2         | 0.05%   |
| 4.19     | 2         | 0.05%   |
| 6.5.2    | 1         | 0.02%   |
| 6.3.0    | 1         | 0.02%   |
| 6.2.0    | 1         | 0.02%   |
| 5.2      | 1         | 0.02%   |
| 5.15.107 | 1         | 0.02%   |
| 4.20     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3336      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 1254      | 33.75%  |
| KDE5           | 613       | 16.5%   |
| GNOME          | 347       | 9.34%   |
| i3             | 223       | 6%      |
| Unknown        | 147       | 3.96%   |
| Cinnamon       | 131       | 3.53%   |
| awesome        | 131       | 3.53%   |
| qtile          | 91        | 2.45%   |
| Hyprland       | 86        | 2.31%   |
| KDE6           | 84        | 2.26%   |
| X-Cinnamon     | 79        | 2.13%   |
| bspwm          | 72        | 1.94%   |
| Deepin         | 61        | 1.64%   |
| xmonad         | 57        | 1.53%   |
| Budgie         | 56        | 1.51%   |
| DWM            | 46        | 1.24%   |
| LXQt           | 37        | 1%      |
| LeftWM         | 34        | 0.91%   |
| KDE            | 30        | 0.81%   |
| MATE           | 27        | 0.73%   |
| chadwm         | 27        | 0.73%   |
| herbstluftwm   | 14        | 0.38%   |
| i3-with-shmlog | 13        | 0.35%   |
| sway           | 11        | 0.3%    |
| wayfire        | 6         | 0.16%   |
| Cutefish       | 5         | 0.13%   |
| Openbox        | 4         | 0.11%   |
| ICEWM          | 4         | 0.11%   |
| Unity          | 3         | 0.08%   |
| spectrwm       | 3         | 0.08%   |
| Hypr           | 3         | 0.08%   |
| cwm            | 3         | 0.08%   |
| GNOME Classic  | 2         | 0.05%   |
| dusk           | 2         | 0.05%   |
| dk             | 2         | 0.05%   |
| XFCE:GNOME:    | 1         | 0.03%   |
| river          | 1         | 0.03%   |
| Pantheon       | 1         | 0.03%   |
| niri           | 1         | 0.03%   |
| LXDE           | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2853      | 82.2%   |
| Wayland | 446       | 12.85%  |
| Tty     | 111       | 3.2%    |
| Unknown | 61        | 1.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2332      | 65.89%  |
| LightDM | 592       | 16.73%  |
| TDM     | 295       | 8.34%   |
| Unknown | 217       | 6.13%   |
| GDM     | 78        | 2.2%    |
| Ly      | 12        | 0.34%   |
| LXDM    | 11        | 0.31%   |
| XDM     | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1788      | 52.53%  |
| en_GB   | 262       | 7.7%    |
| de_DE   | 167       | 4.91%   |
| C       | 126       | 3.7%    |
| en_CA   | 112       | 3.29%   |
| ru_RU   | 84        | 2.47%   |
| en_IN   | 83        | 2.44%   |
| fr_FR   | 68        | 2%      |
| pt_BR   | 67        | 1.97%   |
| en_AU   | 65        | 1.91%   |
| es_ES   | 60        | 1.76%   |
| it_IT   | 48        | 1.41%   |
| es_MX   | 37        | 1.09%   |
| pl_PL   | 35        | 1.03%   |
| en_ZA   | 28        | 0.82%   |
| hu_HU   | 27        | 0.79%   |
| tr_TR   | 26        | 0.76%   |
| es_AR   | 26        | 0.76%   |
| sv_SE   | 18        | 0.53%   |
| nl_NL   | 16        | 0.47%   |
| zh_CN   | 15        | 0.44%   |
| Unknown | 15        | 0.44%   |
| en_PH   | 11        | 0.32%   |
| fr_CA   | 10        | 0.29%   |
| en_IE   | 10        | 0.29%   |
| en_DK   | 10        | 0.29%   |
| de_AT   | 10        | 0.29%   |
| nl_BE   | 9         | 0.26%   |
| ja_JP   | 9         | 0.26%   |
| en_IL   | 9         | 0.26%   |
| da_DK   | 9         | 0.26%   |
| pt_PT   | 8         | 0.24%   |
| cs_CZ   | 8         | 0.24%   |
| ru_UA   | 7         | 0.21%   |
| fi_FI   | 7         | 0.21%   |
| de_CH   | 7         | 0.21%   |
| uk_UA   | 6         | 0.18%   |
| en_SG   | 6         | 0.18%   |
| nb_NO   | 5         | 0.15%   |
| fr_BE   | 5         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2593      | 76.56%  |
| BIOS | 794       | 23.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2376      | 68.51%  |
| Btrfs    | 811       | 23.39%  |
| Overlay  | 191       | 5.51%   |
| Xfs      | 40        | 1.15%   |
| F2fs     | 31        | 0.89%   |
| Unknown  | 11        | 0.32%   |
| Jfs      | 4         | 0.12%   |
| Reiserfs | 3         | 0.09%   |
| Tmpfs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2750      | 81.03%  |
| MBR     | 440       | 12.96%  |
| Unknown | 204       | 6.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2527      | 72.53%  |
| Yes       | 957       | 27.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1981      | 58.04%  |
| Yes       | 1432      | 41.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 653       | 19.57%  |
| Lenovo                               | 567       | 17%     |
| Dell                                 | 363       | 10.88%  |
| Hewlett-Packard                      | 357       | 10.7%   |
| Gigabyte Technology                  | 272       | 8.15%   |
| MSI                                  | 263       | 7.88%   |
| Acer                                 | 146       | 4.38%   |
| ASRock                               | 131       | 3.93%   |
| Apple                                | 86        | 2.58%   |
| Intel                                | 40        | 1.2%    |
| Toshiba                              | 33        | 0.99%   |
| Unknown                              | 28        | 0.84%   |
| Samsung Electronics                  | 26        | 0.78%   |
| Supermicro                           | 19        | 0.57%   |
| Fujitsu                              | 19        | 0.57%   |
| AZW                                  | 18        | 0.54%   |
| Sony                                 | 17        | 0.51%   |
| HUAWEI                               | 17        | 0.51%   |
| Medion                               | 15        | 0.45%   |
| Razer                                | 14        | 0.42%   |
| System76                             | 13        | 0.39%   |
| Alienware                            | 12        | 0.36%   |
| Notebook                             | 11        | 0.33%   |
| TUXEDO                               | 10        | 0.3%    |
| Packard Bell                         | 10        | 0.3%    |
| Biostar                              | 10        | 0.3%    |
| Microsoft                            | 9         | 0.27%   |
| Google                               | 9         | 0.27%   |
| Chuwi                                | 9         | 0.27%   |
| Timi                                 | 8         | 0.24%   |
| Framework                            | 7         | 0.21%   |
| BESSTAR Tech                         | 7         | 0.21%   |
| Shenzhen Meigao Electronic Equipment | 6         | 0.18%   |
| Huanan                               | 6         | 0.18%   |
| Schenker                             | 5         | 0.15%   |
| Pegatron                             | 5         | 0.15%   |
| Monster                              | 5         | 0.15%   |
| Foxconn                              | 5         | 0.15%   |
| ZOTAC                                | 4         | 0.12%   |
| Casper                               | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 38        | 1.14%   |
| ASUS TUF Gaming X570-PLUS    | 26        | 0.78%   |
| ASUS All Series              | 25        | 0.75%   |
| MSI MS-7C37                  | 13        | 0.39%   |
| ASUS ROG STRIX B550-F GAMING | 13        | 0.39%   |
| ASUS PRIME X570-P            | 12        | 0.36%   |
| MSI MS-7C91                  | 11        | 0.33%   |
| AZW SER                      | 11        | 0.33%   |
| Supermicro SYS-5019A-FTN4    | 10        | 0.3%    |
| MSI MS-7B79                  | 10        | 0.3%    |
| HP Pavilion Notebook         | 10        | 0.3%    |
| Gigabyte X570 AORUS ELITE    | 10        | 0.3%    |
| MSI MS-7C56                  | 9         | 0.27%   |
| MSI MS-7C02                  | 9         | 0.27%   |
| MSI MS-7B89                  | 9         | 0.27%   |
| HP Notebook                  | 9         | 0.27%   |
| Gigabyte X570 AORUS MASTER   | 9         | 0.27%   |
| Dell OptiPlex 7010           | 9         | 0.27%   |
| MSI MS-7B86                  | 8         | 0.24%   |
| MSI MS-7A38                  | 8         | 0.24%   |
| Gigabyte B450 AORUS ELITE    | 8         | 0.24%   |
| ASUS ROG STRIX B450-F GAMING | 8         | 0.24%   |
| ASUS PRIME X470-PRO          | 8         | 0.24%   |
| HP Laptop 15s-eq2xxx         | 7         | 0.21%   |
| HP EliteBook 840 G3          | 7         | 0.21%   |
| Gigabyte X570 GAMING X       | 7         | 0.21%   |
| ASUS Z170 PRO GAMING         | 7         | 0.21%   |
| ASUS ROG CROSSHAIR VIII HERO | 7         | 0.21%   |
| ASUS PRIME A320M-K           | 7         | 0.21%   |
| ASRock B450M Pro4            | 7         | 0.21%   |
| Apple MacBookAir7,2          | 7         | 0.21%   |
| Razer Blade                  | 6         | 0.18%   |
| Gigabyte X570 AORUS PRO WIFI | 6         | 0.18%   |
| Gigabyte B450M DS3H V2       | 6         | 0.18%   |
| Dell OptiPlex 9020           | 6         | 0.18%   |
| Dell OptiPlex 9010           | 6         | 0.18%   |
| ASUS PRIME B450M-A           | 6         | 0.18%   |
| Apple MacBookPro9,2          | 6         | 0.18%   |
| Apple MacBookAir6,2          | 6         | 0.18%   |
| MSI MS-7C95                  | 5         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 266       | 7.97%   |
| ASUS ROG           | 121       | 3.63%   |
| Lenovo IdeaPad     | 108       | 3.24%   |
| ASUS PRIME         | 104       | 3.12%   |
| Dell Inspiron      | 103       | 3.09%   |
| Dell Latitude      | 90        | 2.7%    |
| ASUS TUF           | 90        | 2.7%    |
| Acer Aspire        | 78        | 2.34%   |
| HP Pavilion        | 67        | 2.01%   |
| ASUS VivoBook      | 60        | 1.8%    |
| Dell OptiPlex      | 54        | 1.62%   |
| Lenovo Legion      | 49        | 1.47%   |
| HP Laptop          | 49        | 1.47%   |
| HP EliteBook       | 41        | 1.23%   |
| Dell XPS           | 39        | 1.17%   |
| Unknown            | 38        | 1.14%   |
| Gigabyte X570      | 35        | 1.05%   |
| Lenovo ThinkCentre | 33        | 0.99%   |
| Dell Precision     | 32        | 0.96%   |
| Toshiba Satellite  | 29        | 0.87%   |
| HP ENVY            | 25        | 0.75%   |
| ASUS ASUS          | 25        | 0.75%   |
| ASUS All           | 25        | 0.75%   |
| Lenovo Yoga        | 24        | 0.72%   |
| Dell Vostro        | 24        | 0.72%   |
| Acer Nitro         | 21        | 0.63%   |
| Gigabyte B450M     | 20        | 0.6%    |
| HP ProBook         | 18        | 0.54%   |
| HP OMEN            | 17        | 0.51%   |
| Gigabyte B450      | 17        | 0.51%   |
| HP Compaq          | 16        | 0.48%   |
| ASUS Zenbook       | 16        | 0.48%   |
| Acer Predator      | 16        | 0.48%   |
| HP EliteDesk       | 14        | 0.42%   |
| Gigabyte B550      | 14        | 0.42%   |
| ASRock B450M       | 14        | 0.42%   |
| Razer Blade        | 13        | 0.39%   |
| MSI MS-7C37        | 13        | 0.39%   |
| HP ProDesk         | 13        | 0.39%   |
| Acer Swift         | 13        | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 402       | 12.05%  |
| 2020    | 401       | 12.02%  |
| 2019    | 399       | 11.96%  |
| 2021    | 311       | 9.32%   |
| 2017    | 250       | 7.49%   |
| 2012    | 210       | 6.29%   |
| 2013    | 206       | 6.18%   |
| 2022    | 181       | 5.43%   |
| 2016    | 181       | 5.43%   |
| 2015    | 157       | 4.71%   |
| 2014    | 157       | 4.71%   |
| 2011    | 155       | 4.65%   |
| 2010    | 97        | 2.91%   |
| 2023    | 92        | 2.76%   |
| 2008    | 48        | 1.44%   |
| 2009    | 37        | 1.11%   |
| 2024    | 22        | 0.66%   |
| 2007    | 20        | 0.6%    |
| 2006    | 7         | 0.21%   |
| 2005    | 1         | 0.03%   |
| 2004    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1735      | 52.01%  |
| Desktop     | 1401      | 42%     |
| Convertible | 76        | 2.28%   |
| Mini pc     | 59        | 1.77%   |
| All in one  | 39        | 1.17%   |
| Tablet      | 17        | 0.51%   |
| Server      | 8         | 0.24%   |
| Stick pc    | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3333      | 99.88%  |
| Enabled  | 4         | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3319      | 99.49%  |
| Yes  | 17        | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 879       | 25.9%   |
| 4.01-8.0        | 751       | 22.13%  |
| 32.01-64.0      | 583       | 17.18%  |
| 8.01-16.0       | 581       | 17.12%  |
| 3.01-4.0        | 293       | 8.63%   |
| 64.01-256.0     | 160       | 4.71%   |
| 24.01-32.0      | 97        | 2.86%   |
| 1.01-2.0        | 28        | 0.82%   |
| 2.01-3.0        | 18        | 0.53%   |
| More than 256.0 | 3         | 0.09%   |
| Unknown         | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1251      | 32.3%   |
| 2.01-3.0    | 956       | 24.68%  |
| 4.01-8.0    | 616       | 15.9%   |
| 3.01-4.0    | 570       | 14.72%  |
| 0.51-1.0    | 254       | 6.56%   |
| 8.01-16.0   | 173       | 4.47%   |
| 0.01-0.5    | 29        | 0.75%   |
| 16.01-24.0  | 17        | 0.44%   |
| 24.01-32.0  | 3         | 0.08%   |
| 32.01-64.0  | 2         | 0.05%   |
| 64.01-256.0 | 1         | 0.03%   |
| Unknown     | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1623      | 46.41%  |
| 2      | 1013      | 28.97%  |
| 3      | 423       | 12.1%   |
| 4      | 213       | 6.09%   |
| 5      | 118       | 3.37%   |
| 6      | 48        | 1.37%   |
| 7      | 21        | 0.6%    |
| 0      | 11        | 0.31%   |
| 8      | 10        | 0.29%   |
| 9      | 7         | 0.2%    |
| 11     | 3         | 0.09%   |
| 10     | 2         | 0.06%   |
| 21     | 1         | 0.03%   |
| 20     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 14     | 1         | 0.03%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2554      | 75.9%   |
| Yes       | 811       | 24.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2909      | 86.81%  |
| No        | 442       | 13.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2586      | 77.06%  |
| No        | 770       | 22.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2385      | 70.4%   |
| No        | 1003      | 29.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 743       | 22.08%  |
| Germany      | 263       | 7.82%   |
| UK           | 187       | 5.56%   |
| Canada       | 150       | 4.46%   |
| India        | 128       | 3.8%    |
| Brazil       | 120       | 3.57%   |
| Russia       | 101       | 3%      |
| France       | 95        | 2.82%   |
| Spain        | 90        | 2.67%   |
| Australia    | 79        | 2.35%   |
| Italy        | 74        | 2.2%    |
| Netherlands  | 65        | 1.93%   |
| Belgium      | 64        | 1.9%    |
| Sweden       | 62        | 1.84%   |
| Turkey       | 61        | 1.81%   |
| Poland       | 58        | 1.72%   |
| Mexico       | 54        | 1.6%    |
| Hungary      | 44        | 1.31%   |
| Argentina    | 44        | 1.31%   |
| Romania      | 34        | 1.01%   |
| Switzerland  | 33        | 0.98%   |
| Indonesia    | 32        | 0.95%   |
| Norway       | 31        | 0.92%   |
| South Africa | 30        | 0.89%   |
| Portugal     | 29        | 0.86%   |
| Ukraine      | 26        | 0.77%   |
| Austria      | 26        | 0.77%   |
| Greece       | 25        | 0.74%   |
| Czechia      | 25        | 0.74%   |
| Bulgaria     | 25        | 0.74%   |
| Finland      | 24        | 0.71%   |
| China        | 23        | 0.68%   |
| Denmark      | 22        | 0.65%   |
| Colombia     | 19        | 0.56%   |
| Iran         | 18        | 0.53%   |
| Egypt        | 18        | 0.53%   |
| Vietnam      | 17        | 0.51%   |
| Serbia       | 17        | 0.51%   |
| Philippines  | 17        | 0.51%   |
| Ireland      | 15        | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 36        | 0.99%   |
| Sydney            | 31        | 0.85%   |
| Istanbul          | 26        | 0.71%   |
| Toronto           | 23        | 0.63%   |
| Moscow            | 23        | 0.63%   |
| Madrid            | 19        | 0.52%   |
| Amsterdam         | 19        | 0.52%   |
| Durham            | 18        | 0.49%   |
| Stockholm         | 17        | 0.47%   |
| Paris             | 17        | 0.47%   |
| Melbourne         | 17        | 0.47%   |
| Vienna            | 16        | 0.44%   |
| Sao Paulo         | 16        | 0.44%   |
| Budapest          | 16        | 0.44%   |
| Warsaw            | 15        | 0.41%   |
| New York          | 15        | 0.41%   |
| Los Angeles       | 15        | 0.41%   |
| Helsinki          | 15        | 0.41%   |
| Bengaluru         | 15        | 0.41%   |
| Tehran            | 14        | 0.38%   |
| Pune              | 14        | 0.38%   |
| Sofia             | 13        | 0.36%   |
| Houston           | 13        | 0.36%   |
| Dallas            | 13        | 0.36%   |
| Brisbane          | 13        | 0.36%   |
| Atlanta           | 13        | 0.36%   |
| Athens            | 13        | 0.36%   |
| Portland          | 12        | 0.33%   |
| Oslo              | 12        | 0.33%   |
| Frankfurt am Main | 12        | 0.33%   |
| Bucharest         | 12        | 0.33%   |
| Rio de Janeiro    | 11        | 0.3%    |
| Prague            | 11        | 0.3%    |
| London            | 11        | 0.3%    |
| Lier              | 11        | 0.3%    |
| Hamburg           | 11        | 0.3%    |
| Denver            | 11        | 0.3%    |
| Charlotte         | 11        | 0.3%    |
| Zurich            | 10        | 0.27%   |
| St Petersburg     | 10        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1037      | 1884   | 17.79%  |
| WDC                         | 764       | 1328   | 13.11%  |
| Seagate                     | 686       | 1103   | 11.77%  |
| Sandisk                     | 388       | 531    | 6.66%   |
| Kingston                    | 322       | 515    | 5.52%   |
| Toshiba                     | 310       | 419    | 5.32%   |
| Crucial                     | 217       | 324    | 3.72%   |
| SK hynix                    | 159       | 212    | 2.73%   |
| Intel                       | 149       | 222    | 2.56%   |
| Unknown                     | 130       | 185    | 2.23%   |
| Phison Electronics          | 103       | 161    | 1.77%   |
| Hitachi                     | 100       | 133    | 1.72%   |
| Micron Technology           | 94        | 113    | 1.61%   |
| Micron/Crucial Technology   | 86        | 124    | 1.48%   |
| A-DATA Technology           | 84        | 113    | 1.44%   |
| HGST                        | 74        | 109    | 1.27%   |
| China                       | 57        | 80     | 0.98%   |
| Kingston Technology Company | 56        | 88     | 0.96%   |
| Silicon Motion              | 53        | 81     | 0.91%   |
| Apple                       | 51        | 78     | 0.87%   |
| KIOXIA                      | 49        | 73     | 0.84%   |
| PNY                         | 43        | 63     | 0.74%   |
| SPCC                        | 36        | 45     | 0.62%   |
| JMicron Technology          | 36        | 40     | 0.62%   |
| MAXIO Technology (Hangzhou) | 32        | 43     | 0.55%   |
| ADATA Technology            | 31        | 40     | 0.53%   |
| Phison                      | 29        | 46     | 0.5%    |
| Patriot                     | 25        | 36     | 0.43%   |
| SABRENT                     | 22        | 29     | 0.38%   |
| LITEON                      | 22        | 31     | 0.38%   |
| Transcend                   | 21        | 25     | 0.36%   |
| Realtek Semiconductor       | 21        | 28     | 0.36%   |
| Intenso                     | 21        | 31     | 0.36%   |
| Hewlett-Packard             | 21        | 32     | 0.36%   |
| Corsair                     | 21        | 39     | 0.36%   |
| Plextor                     | 17        | 21     | 0.29%   |
| OCZ                         | 17        | 22     | 0.29%   |
| Team                        | 16        | 25     | 0.27%   |
| Lexar                       | 16        | 16     | 0.27%   |
| Gigabyte Technology         | 16        | 20     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 167       | 2.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 99        | 1.5%    |
| Kingston SA400S37240G 240GB SSD                       | 75        | 1.14%   |
| Samsung SSD 860 EVO 500GB                             | 68        | 1.03%   |
| Seagate ST1000LM035-1RK172 1TB                        | 63        | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 54        | 0.82%   |
| Kingston SA400S37480G 480GB SSD                       | 51        | 0.77%   |
| Samsung SSD 850 EVO 250GB                             | 50        | 0.76%   |
| Samsung SSD 860 EVO 1TB                               | 47        | 0.71%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 45        | 0.68%   |
| Crucial CT1000MX500SSD1 1TB                           | 45        | 0.68%   |
| Samsung SSD 850 EVO 500GB                             | 44        | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB                        | 42        | 0.64%   |
| Toshiba MQ01ABD100 1TB                                | 41        | 0.62%   |
| Phison E12 NVMe Controller 480GB                      | 41        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 39        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB                        | 39        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 38        | 0.58%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 34        | 0.52%   |
| Samsung SSD 860 EVO 250GB                             | 34        | 0.52%   |
| Crucial CT500MX500SSD1 500GB                          | 34        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 33        | 0.5%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 32        | 0.49%   |
| Samsung SSD 870 EVO 1TB                               | 32        | 0.49%   |
| Unknown SD/MMC/MS PRO 128GB                           | 28        | 0.42%   |
| Toshiba MQ04ABF100 1TB                                | 28        | 0.42%   |
| Kingston SA400S37120G 120GB SSD                       | 28        | 0.42%   |
| Toshiba DT01ACA100 1TB                                | 27        | 0.41%   |
| Samsung SSD 980 1TB                                   | 27        | 0.41%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB    | 26        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                          | 24        | 0.36%   |
| Seagate ST4000DM004-2CV104 4TB                        | 23        | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                        | 23        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                          | 23        | 0.35%   |
| JMicron Generic 500GB                                 | 23        | 0.35%   |
| Intel SSD 660P Series 1024GB                          | 23        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 22        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB                        | 22        | 0.33%   |
| Phison E16 PCIe4 NVMe Controller 1TB                  | 22        | 0.33%   |
| Unknown MMC Card  32GB                                | 21        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 669       | 1059   | 36.03%  |
| WDC                 | 576       | 1005   | 31.02%  |
| Toshiba             | 225       | 304    | 12.12%  |
| Hitachi             | 100       | 133    | 5.39%   |
| HGST                | 72        | 105    | 3.88%   |
| Samsung Electronics | 60        | 90     | 3.23%   |
| Unknown             | 29        | 40     | 1.56%   |
| JMicron Technology  | 24        | 26     | 1.29%   |
| SABRENT             | 18        | 24     | 0.97%   |
| Apple               | 12        | 21     | 0.65%   |
| Fujitsu             | 8         | 9      | 0.43%   |
| Maxtor              | 7         | 10     | 0.38%   |
| External            | 7         | 11     | 0.38%   |
| ASMT                | 7         | 11     | 0.38%   |
| TO Exter            | 6         | 6      | 0.32%   |
| Hewlett-Packard     | 6         | 9      | 0.32%   |
| ASMedia             | 4         | 5      | 0.22%   |
| Intenso             | 3         | 3      | 0.16%   |
| USB3.0              | 2         | 2      | 0.11%   |
| LaCie               | 2         | 2      | 0.11%   |
| Inateck             | 2         | 2      | 0.11%   |
| Fantom              | 2         | 6      | 0.11%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| TDAS                | 1         | 4      | 0.05%   |
| RSH-319             | 1         | 1      | 0.05%   |
| Min Yi U            | 1         | 1      | 0.05%   |
| Mercury             | 1         | 1      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| IBM-ESXS            | 1         | 2      | 0.05%   |
| HGST HUS            | 1         | 1      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| H/W                 | 1         | 12     | 0.05%   |
| ExcelStor           | 1         | 2      | 0.05%   |
| CSD                 | 1         | 1      | 0.05%   |
| ASUSTOR             | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |
| Unknown             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 520       | 925    | 25.28%  |
| Kingston            | 248       | 371    | 12.06%  |
| Crucial             | 200       | 293    | 9.72%   |
| SanDisk             | 162       | 206    | 7.88%   |
| WDC                 | 150       | 228    | 7.29%   |
| A-DATA Technology   | 66        | 93     | 3.21%   |
| China               | 57        | 80     | 2.77%   |
| PNY                 | 42        | 59     | 2.04%   |
| SK hynix            | 40        | 61     | 1.94%   |
| Intel               | 39        | 59     | 1.9%    |
| Apple               | 35        | 46     | 1.7%    |
| Toshiba             | 33        | 45     | 1.6%    |
| SPCC                | 31        | 38     | 1.51%   |
| Micron Technology   | 31        | 35     | 1.51%   |
| Patriot             | 25        | 36     | 1.22%   |
| Transcend           | 19        | 23     | 0.92%   |
| LITEON              | 19        | 28     | 0.92%   |
| Intenso             | 18        | 28     | 0.88%   |
| OCZ                 | 17        | 22     | 0.83%   |
| Team                | 16        | 25     | 0.78%   |
| Plextor             | 15        | 19     | 0.73%   |
| LITEONIT            | 15        | 15     | 0.73%   |
| Lexar               | 14        | 14     | 0.68%   |
| Hewlett-Packard     | 12        | 19     | 0.58%   |
| GOODRAM             | 11        | 15     | 0.53%   |
| Gigabyte Technology | 10        | 11     | 0.49%   |
| Corsair             | 10        | 20     | 0.49%   |
| KingSpec            | 9         | 14     | 0.44%   |
| Unknown             | 9         | 9      | 0.44%   |
| Seagate             | 7         | 13     | 0.34%   |
| Apacer              | 6         | 6      | 0.29%   |
| XrayDisk            | 5         | 6      | 0.24%   |
| Verbatim            | 5         | 8      | 0.24%   |
| USB3.0              | 5         | 8      | 0.24%   |
| Unknown             | 5         | 5      | 0.24%   |
| T-FORCE             | 5         | 5      | 0.24%   |
| Netac               | 5         | 10     | 0.24%   |
| Mushkin             | 5         | 9      | 0.24%   |
| HS-SSD-C100         | 5         | 6      | 0.24%   |
| Fanxiang            | 5         | 5      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1662      | 2827   | 33.34%  |
| SSD     | 1655      | 3101   | 33.2%   |
| HDD     | 1519      | 2915   | 30.47%  |
| MMC     | 92        | 127    | 1.85%   |
| Unknown | 57        | 80     | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2371      | 5603   | 53.17%  |
| NVMe | 1658      | 2795   | 37.18%  |
| SAS  | 338       | 525    | 7.58%   |
| MMC  | 92        | 127    | 2.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1666      | 3031   | 48.36%  |
| 0.51-1.0   | 1136      | 1845   | 32.98%  |
| 1.01-2.0   | 375       | 679    | 10.89%  |
| 3.01-4.0   | 119       | 186    | 3.45%   |
| 4.01-10.0  | 66        | 147    | 1.92%   |
| 2.01-3.0   | 57        | 90     | 1.65%   |
| 10.01-20.0 | 26        | 38     | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 740       | 20.2%   |
| 251-500        | 730       | 19.93%  |
| 501-1000       | 582       | 15.89%  |
| More than 3000 | 496       | 13.54%  |
| 1001-2000      | 434       | 11.85%  |
| 1-20           | 171       | 4.67%   |
| 2001-3000      | 160       | 4.37%   |
| Unknown        | 145       | 3.96%   |
| 51-100         | 137       | 3.74%   |
| 21-50          | 68        | 1.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 989       | 25.57%  |
| 21-50          | 690       | 17.84%  |
| 101-250        | 579       | 14.97%  |
| 51-100         | 453       | 11.71%  |
| 251-500        | 366       | 9.46%   |
| 501-1000       | 292       | 7.55%   |
| 1001-2000      | 173       | 4.47%   |
| Unknown        | 145       | 3.75%   |
| More than 3000 | 105       | 2.71%   |
| 2001-3000      | 72        | 1.86%   |
| 0              | 4         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                          | 15        | 25     | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 14        | 14     | 1.94%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 13        | 14     | 1.81%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 11        | 24     | 1.53%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 512GB | 10        | 11     | 1.39%   |
| Seagate ST500LT012-1DG142 500GB                                 | 9         | 10     | 1.25%   |
| Toshiba MQ01ABF050 500GB                                        | 8         | 12     | 1.11%   |
| Seagate ST1000DM003-9YN162 1TB                                  | 8         | 10     | 1.11%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 7         | 11     | 0.97%   |
| SanDisk SSD PLUS 1000GB                                         | 7         | 9      | 0.97%   |
| Seagate ST9500325AS 500GB                                       | 6         | 10     | 0.83%   |
| Seagate ST9320325AS 320GB                                       | 6         | 8      | 0.83%   |
| Seagate ST500DM002-1BD142 500GB                                 | 6         | 7      | 0.83%   |
| Seagate ST3500413AS 500GB                                       | 6         | 7      | 0.83%   |
| Seagate ST31000528AS 1TB                                        | 6         | 6      | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 6         | 12     | 0.83%   |
| Hitachi HTS547575A9E384 752GB                                   | 6         | 6      | 0.83%   |
| HGST HTS721010A9E630 1TB                                        | 6         | 9      | 0.83%   |
| WDC WD20EARS-00MVWB0 2TB                                        | 5         | 10     | 0.69%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 5         | 5      | 0.69%   |
| Seagate ST31000524AS 1TB                                        | 5         | 6      | 0.69%   |
| HGST HTS541010A9E680 1TB                                        | 5         | 8      | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 4         | 4      | 0.56%   |
| WDC WD20EARX-00PASB0 2TB                                        | 4         | 5      | 0.56%   |
| Toshiba DT01ACA100 1TB                                          | 4         | 7      | 0.56%   |
| Seagate ST3500312CS 500GB                                       | 4         | 9      | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB                                  | 4         | 10     | 0.56%   |
| Kingston SV300S37A120G 120GB SSD                                | 4         | 4      | 0.56%   |
| Kingston SA400S37480G 480GB SSD                                 | 4         | 5      | 0.56%   |
| Hitachi HDS721010CLA332 1TB                                     | 4         | 6      | 0.56%   |
| HGST HTS725050A7E630 500GB                                      | 4         | 5      | 0.56%   |
| HGST HTS545050A7E380 500GB                                      | 4         | 5      | 0.56%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 3         | 4      | 0.42%   |
| WDC WD5000AAKX-60U6AA0 500GB                                    | 3         | 4      | 0.42%   |
| WDC WD5000AAKX-001CA0 500GB                                     | 3         | 4      | 0.42%   |
| WDC WD3200AAJS-22L7A0 320GB                                     | 3         | 3      | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB                                        | 3         | 5      | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 3         | 3      | 0.42%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 3         | 6      | 0.42%   |
| Toshiba MQ04ABF100 1TB                                          | 3         | 4      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 176       | 234    | 25.36%  |
| WDC                         | 163       | 249    | 23.49%  |
| Samsung Electronics         | 59        | 86     | 8.5%    |
| Toshiba                     | 55        | 78     | 7.93%   |
| Hitachi                     | 38        | 48     | 5.48%   |
| HGST                        | 26        | 44     | 3.75%   |
| SanDisk                     | 22        | 31     | 3.17%   |
| Kingston                    | 20        | 27     | 2.88%   |
| Intel                       | 15        | 31     | 2.16%   |
| SK hynix                    | 13        | 16     | 1.87%   |
| Crucial                     | 13        | 19     | 1.87%   |
| Micron Technology           | 8         | 11     | 1.15%   |
| A-DATA Technology           | 8         | 11     | 1.15%   |
| China                       | 6         | 7      | 0.86%   |
| Maxtor                      | 5         | 8      | 0.72%   |
| Hewlett-Packard             | 5         | 5      | 0.72%   |
| Corsair                     | 5         | 15     | 0.72%   |
| Fujitsu                     | 4         | 5      | 0.58%   |
| Apple                       | 4         | 4      | 0.58%   |
| Transcend                   | 3         | 3      | 0.43%   |
| Micron/Crucial Technology   | 3         | 5      | 0.43%   |
| ASMedia                     | 3         | 4      | 0.43%   |
| USB3.0                      | 2         | 4      | 0.29%   |
| Silicon Motion              | 2         | 3      | 0.29%   |
| Realtek Semiconductor       | 2         | 2      | 0.29%   |
| Plextor                     | 2         | 2      | 0.29%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.29%   |
| LITEONIT                    | 2         | 2      | 0.29%   |
| Inateck                     | 2         | 2      | 0.29%   |
| Drevo                       | 2         | 2      | 0.29%   |
| Colorful                    | 2         | 5      | 0.29%   |
| ASMT                        | 2         | 2      | 0.29%   |
| Unknown                     | 2         | 2      | 0.29%   |
| XPG                         | 1         | 1      | 0.14%   |
| Team                        | 1         | 1      | 0.14%   |
| Super Talent                | 1         | 1      | 0.14%   |
| StoreJet                    | 1         | 1      | 0.14%   |
| SSSTC                       | 1         | 1      | 0.14%   |
| SPCC                        | 1         | 1      | 0.14%   |
| Ramsta                      | 1         | 3      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 176       | 234    | 36.14%  |
| WDC                 | 152       | 234    | 31.21%  |
| Toshiba             | 51        | 72     | 10.47%  |
| Hitachi             | 38        | 48     | 7.8%    |
| HGST                | 26        | 44     | 5.34%   |
| Samsung Electronics | 17        | 21     | 3.49%   |
| Maxtor              | 5         | 8      | 1.03%   |
| Fujitsu             | 4         | 5      | 0.82%   |
| Apple               | 4         | 4      | 0.82%   |
| Hewlett-Packard     | 3         | 3      | 0.62%   |
| ASMedia             | 3         | 4      | 0.62%   |
| Inateck             | 2         | 2      | 0.41%   |
| LaCie               | 1         | 1      | 0.21%   |
| JMicron Technology  | 1         | 1      | 0.21%   |
| HGST HTS            | 1         | 1      | 0.21%   |
| CSD                 | 1         | 1      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 450       | 685    | 68.91%  |
| SSD  | 158       | 245    | 24.2%   |
| NVMe | 45        | 59     | 6.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                  | 4         | 4      | 20%     |
| Samsung Electronics SSD 980 500GB                | 2         | 2      | 10%     |
| WDC WD5000AAKX-001CA0 500GB                      | 1         | 1      | 5%      |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 5%      |
| Toshiba XG6 NVMe SSD Controller 1024GB           | 1         | 1      | 5%      |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 5%      |
| Seagate ST91000430AS 1TB                         | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 5%      |
| Seagate ST3500410AS 500GB                        | 1         | 1      | 5%      |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 5%      |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 5%      |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 5%      |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 5%      |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 5%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 36.84%  |
| Samsung Electronics | 7         | 7      | 36.84%  |
| WDC                 | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Toshiba             | 1         | 1      | 5.26%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2856      | 6972   | 69.91%  |
| Malfunc  | 631       | 989    | 15.45%  |
| Detected | 579       | 1068   | 14.17%  |
| Failed   | 19        | 21     | 0.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2036      | 41.51%  |
| AMD                              | 862       | 17.57%  |
| Samsung Electronics              | 600       | 12.23%  |
| SanDisk                          | 300       | 6.12%   |
| Phison Electronics               | 146       | 2.98%   |
| Kingston Technology Company      | 139       | 2.83%   |
| SK hynix                         | 120       | 2.45%   |
| Micron/Crucial Technology        | 104       | 2.12%   |
| ASMedia Technology               | 87        | 1.77%   |
| Micron Technology                | 65        | 1.33%   |
| Silicon Motion                   | 59        | 1.2%    |
| KIOXIA                           | 54        | 1.1%    |
| Toshiba America Info Systems     | 50        | 1.02%   |
| ADATA Technology                 | 48        | 0.98%   |
| Marvell Technology Group         | 38        | 0.77%   |
| MAXIO Technology (Hangzhou)      | 32        | 0.65%   |
| Realtek Semiconductor            | 28        | 0.57%   |
| Nvidia                           | 22        | 0.45%   |
| Shenzhen Longsys Electronics     | 14        | 0.29%   |
| Seagate Technology               | 14        | 0.29%   |
| Union Memory (Shenzhen)          | 13        | 0.27%   |
| JMicron Technology               | 11        | 0.22%   |
| INNOGRIT                         | 10        | 0.2%    |
| Lite-On Technology               | 7         | 0.14%   |
| Apple                            | 5         | 0.1%    |
| Solid State Storage Technology   | 4         | 0.08%   |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| Biwin Storage Technology         | 4         | 0.08%   |
| Adaptec                          | 4         | 0.08%   |
| VIA Technologies                 | 3         | 0.06%   |
| Netac Technology                 | 3         | 0.06%   |
| Lenovo                           | 3         | 0.06%   |
| Broadcom / LSI                   | 3         | 0.06%   |
| Solidigm                         | 2         | 0.04%   |
| Silicon Image                    | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Transcend                        | 1         | 0.02%   |
| TenaFe                           | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 584       | 10.73%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 280       | 5.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 178       | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 174       | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 141       | 2.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 127       | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 119       | 2.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 114       | 2.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 113       | 2.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 111       | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 103       | 1.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 100       | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 87        | 1.6%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 83        | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 80        | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                            | 78        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 74        | 1.36%   |
| Phison E12 NVMe Controller                                                     | 69        | 1.27%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 68        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 63        | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 61        | 1.12%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 59        | 1.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 59        | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 59        | 1.08%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 56        | 1.03%   |
| Intel SATA Controller [RAID mode]                                              | 52        | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 51        | 0.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 49        | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 49        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 47        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 45        | 0.83%   |
| Intel SSD 660P Series                                                          | 45        | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 45        | 0.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 39        | 0.72%   |
| AMD 600 Series Chipset SATA Controller                                         | 39        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 38        | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 37        | 0.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 34        | 0.62%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 33        | 0.61%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 33        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2565      | 54.68%  |
| NVMe | 1659      | 35.37%  |
| RAID | 300       | 6.4%    |
| IDE  | 159       | 3.39%   |
| SAS  | 6         | 0.13%   |
| SCSI | 2         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 2286      | 68.53%  |
| AMD     | 1049      | 31.44%  |
| Unknown | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 55        | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 1.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 38        | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 34        | 1.02%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 34        | 1.02%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 32        | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 31        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 31        | 0.93%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 30        | 0.9%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 29        | 0.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 29        | 0.87%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 28        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 27        | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.78%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 26        | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 25        | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 24        | 0.72%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 23        | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 21        | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 21        | 0.63%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 21        | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 0.63%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 20        | 0.6%    |
| Intel Core i7-7700K CPU @ 4.20GHz             | 19        | 0.57%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 19        | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 18        | 0.54%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 17        | 0.51%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 16        | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 16        | 0.48%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 16        | 0.48%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 16        | 0.48%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.48%   |
| Intel 12th Gen Core i7-12700H                 | 16        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 778       | 23.27%  |
| Intel Core i7           | 701       | 20.96%  |
| AMD Ryzen 5             | 339       | 10.14%  |
| AMD Ryzen 7             | 312       | 9.33%   |
| Other                   | 268       | 8.01%   |
| Intel Core i3           | 178       | 5.32%   |
| AMD Ryzen 9             | 143       | 4.28%   |
| Intel Celeron           | 85        | 2.54%   |
| Intel Xeon              | 72        | 2.15%   |
| Intel Pentium           | 66        | 1.97%   |
| AMD Ryzen 3             | 59        | 1.76%   |
| Intel Core 2 Duo        | 46        | 1.38%   |
| Intel Core i9           | 31        | 0.93%   |
| AMD FX                  | 29        | 0.87%   |
| Intel Atom              | 27        | 0.81%   |
| AMD A6                  | 21        | 0.63%   |
| AMD A10                 | 19        | 0.57%   |
| Intel Pentium Dual-Core | 12        | 0.36%   |
| AMD Ryzen 7 PRO         | 12        | 0.36%   |
| AMD A4                  | 12        | 0.36%   |
| AMD A8                  | 11        | 0.33%   |
| AMD Ryzen Threadripper  | 9         | 0.27%   |
| AMD A12                 | 8         | 0.24%   |
| AMD Phenom II X4        | 7         | 0.21%   |
| AMD Athlon II X2        | 7         | 0.21%   |
| Intel Pentium Silver    | 6         | 0.18%   |
| Intel Core 2            | 6         | 0.18%   |
| AMD Ryzen 5 PRO         | 6         | 0.18%   |
| AMD E2                  | 6         | 0.18%   |
| AMD Athlon              | 6         | 0.18%   |
| Intel Pentium Gold      | 5         | 0.15%   |
| Intel Pentium Dual      | 5         | 0.15%   |
| Intel Core m3           | 5         | 0.15%   |
| Intel Core 2 Quad       | 5         | 0.15%   |
| AMD E1                  | 5         | 0.15%   |
| AMD Phenom II X6        | 4         | 0.12%   |
| AMD Athlon 64 X2        | 4         | 0.12%   |
| Intel Xeon Silver       | 3         | 0.09%   |
| Intel Core              | 3         | 0.09%   |
| AMD E                   | 3         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1146      | 34.25%  |
| 2       | 936       | 27.97%  |
| 6       | 534       | 15.96%  |
| 8       | 440       | 13.15%  |
| 12      | 104       | 3.11%   |
| 16      | 55        | 1.64%   |
| 10      | 42        | 1.26%   |
| 14      | 35        | 1.05%   |
| 1       | 18        | 0.54%   |
| 24      | 14        | 0.42%   |
| 3       | 13        | 0.39%   |
| 40      | 2         | 0.06%   |
| 20      | 2         | 0.06%   |
| 18      | 2         | 0.06%   |
| 48      | 1         | 0.03%   |
| 32      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3320      | 99.49%  |
| 2       | 16        | 0.48%   |
| Unknown | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2665      | 79.74%  |
| 1       | 676       | 20.23%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3329      | 99.79%  |
| Unknown        | 7         | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1669      | 47.29%  |
| 0x306c3    | 98        | 2.78%   |
| 0x906ea    | 91        | 2.58%   |
| 0x306a9    | 91        | 2.58%   |
| 0x08701021 | 89        | 2.52%   |
| 0x206a7    | 85        | 2.41%   |
| 0x906e9    | 65        | 1.84%   |
| 0x806ea    | 54        | 1.53%   |
| 0x0800820d | 53        | 1.5%    |
| 0x0a50000c | 52        | 1.47%   |
| 0x806e9    | 51        | 1.45%   |
| 0x506e3    | 50        | 1.42%   |
| 0x406e3    | 44        | 1.25%   |
| 0x08108109 | 41        | 1.16%   |
| 0x0a201016 | 39        | 1.11%   |
| 0x806c1    | 38        | 1.08%   |
| 0x08600106 | 38        | 1.08%   |
| 0x806ec    | 35        | 0.99%   |
| 0x40651    | 34        | 0.96%   |
| 0x306d4    | 29        | 0.82%   |
| 0x0a50000d | 29        | 0.82%   |
| 0x08108102 | 28        | 0.79%   |
| 0x08701013 | 27        | 0.77%   |
| 0xa0652    | 25        | 0.71%   |
| 0x08608103 | 25        | 0.71%   |
| 0x20655    | 24        | 0.68%   |
| 0x1067a    | 22        | 0.62%   |
| 0x0a201009 | 22        | 0.62%   |
| 0x0a20120a | 19        | 0.54%   |
| 0x706e5    | 16        | 0.45%   |
| 0x08701030 | 16        | 0.45%   |
| 0x0810100b | 16        | 0.45%   |
| 0xa0655    | 15        | 0.43%   |
| 0x08600104 | 15        | 0.43%   |
| 0x0a601203 | 14        | 0.4%    |
| 0x08101016 | 14        | 0.4%    |
| 0x806d1    | 13        | 0.37%   |
| 0x0a404102 | 13        | 0.37%   |
| 0x06006705 | 13        | 0.37%   |
| 0xa0653    | 12        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 667       | 19.94%  |
| Haswell           | 290       | 8.67%   |
| Zen 3             | 271       | 8.1%    |
| Zen 2             | 251       | 7.5%    |
| IvyBridge         | 220       | 6.58%   |
| Skylake           | 194       | 5.8%    |
| Zen+              | 173       | 5.17%   |
| SandyBridge       | 164       | 4.9%    |
| Unknown           | 144       | 4.3%    |
| Alderlake Hybrid  | 114       | 3.41%   |
| CometLake         | 109       | 3.26%   |
| TigerLake         | 92        | 2.75%   |
| Broadwell         | 74        | 2.21%   |
| Zen               | 69        | 2.06%   |
| IceLake           | 61        | 1.82%   |
| Westmere          | 59        | 1.76%   |
| Penryn            | 59        | 1.76%   |
| Silvermont        | 50        | 1.49%   |
| Excavator         | 45        | 1.35%   |
| Piledriver        | 41        | 1.23%   |
| Goldmont plus     | 31        | 0.93%   |
| K10               | 25        | 0.75%   |
| Goldmont          | 24        | 0.72%   |
| Nehalem           | 22        | 0.66%   |
| Core              | 22        | 0.66%   |
| Steamroller       | 14        | 0.42%   |
| Jaguar            | 9         | 0.27%   |
| Tremont           | 8         | 0.24%   |
| Puma              | 7         | 0.21%   |
| Gracemont         | 7         | 0.21%   |
| Bobcat            | 7         | 0.21%   |
| K8 Hammer         | 6         | 0.18%   |
| K10 Llano         | 4         | 0.12%   |
| Bonnell           | 4         | 0.12%   |
| Bulldozer         | 3         | 0.09%   |
| Meteorlake Hybrid | 2         | 0.06%   |
| NetBurst          | 1         | 0.03%   |
| K8 & K10 hybrid   | 1         | 0.03%   |
| CannonLake        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1773      | 43.3%   |
| Nvidia                     | 1294      | 31.6%   |
| AMD                        | 1007      | 24.59%  |
| ASPEED Technology          | 17        | 0.42%   |
| Matrox Electronics Systems | 3         | 0.07%   |
| ATI Technologies           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 126       | 3%      |
| Intel 3rd Gen Core processor Graphics Controller                            | 117       | 2.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 111       | 2.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 103       | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 98        | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 97        | 2.31%   |
| Intel UHD Graphics 620                                                      | 93        | 2.21%   |
| Intel HD Graphics 620                                                       | 87        | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 78        | 1.85%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 78        | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 77        | 1.83%   |
| Intel HD Graphics 630                                                       | 76        | 1.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 72        | 1.71%   |
| Intel HD Graphics 530                                                       | 66        | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 64        | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 61        | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 58        | 1.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 53        | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 53        | 1.26%   |
| Intel HD Graphics 5500                                                      | 51        | 1.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 48        | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 45        | 1.07%   |
| Intel Core Processor Integrated Graphics Controller                         | 43        | 1.02%   |
| AMD Lucienne                                                                | 40        | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 39        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 37        | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 35        | 0.83%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 35        | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 34        | 0.81%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 33        | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 32        | 0.76%   |
| AMD Raphael                                                                 | 31        | 0.74%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 30        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 29        | 0.69%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 29        | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 28        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 27        | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 27        | 0.64%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 27        | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 26        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1118      | 33.17%  |
| 1 x AMD        | 763       | 22.63%  |
| 1 x Nvidia     | 646       | 19.16%  |
| Intel + Nvidia | 537       | 15.93%  |
| AMD + Nvidia   | 107       | 3.17%   |
| Intel + AMD    | 72        | 2.14%   |
| 2 x AMD        | 70        | 2.08%   |
| 2 x Intel      | 26        | 0.77%   |
| 1 x ASPEED     | 14        | 0.42%   |
| 2 x Nvidia     | 9         | 0.27%   |
| Other          | 3         | 0.09%   |
| 1 x Matrox     | 3         | 0.09%   |
| AMD + ASPEED   | 3         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2373      | 69.67%  |
| Proprietary | 925       | 27.16%  |
| Unknown     | 108       | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1740      | 50.63%  |
| 7.01-8.0   | 343       | 9.98%   |
| 1.01-2.0   | 314       | 9.14%   |
| 0.01-0.5   | 297       | 8.64%   |
| 3.01-4.0   | 239       | 6.95%   |
| 8.01-16.0  | 152       | 4.42%   |
| 0.51-1.0   | 142       | 4.13%   |
| 5.01-6.0   | 141       | 4.1%    |
| 2.01-3.0   | 35        | 1.02%   |
| 16.01-24.0 | 31        | 0.9%    |
| 4.01-5.0   | 3         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 454       | 11.44%  |
| AU Optronics            | 396       | 9.98%   |
| BOE                     | 331       | 8.34%   |
| LG Display              | 317       | 7.99%   |
| Chimei Innolux          | 311       | 7.84%   |
| Dell                    | 272       | 6.85%   |
| Goldstar                | 270       | 6.8%    |
| Acer                    | 144       | 3.63%   |
| Hewlett-Packard         | 123       | 3.1%    |
| AOC                     | 120       | 3.02%   |
| BenQ                    | 105       | 2.65%   |
| Ancor Communications    | 100       | 2.52%   |
| Philips                 | 75        | 1.89%   |
| Apple                   | 72        | 1.81%   |
| Sharp                   | 64        | 1.61%   |
| Lenovo                  | 63        | 1.59%   |
| ASUSTek Computer        | 57        | 1.44%   |
| PANDA                   | 51        | 1.29%   |
| Unknown                 | 44        | 1.11%   |
| ViewSonic               | 42        | 1.06%   |
| MSI                     | 38        | 0.96%   |
| Iiyama                  | 37        | 0.93%   |
| Sony                    | 33        | 0.83%   |
| Chi Mei Optoelectronics | 26        | 0.66%   |
| Gigabyte Technology     | 25        | 0.63%   |
| CSO                     | 22        | 0.55%   |
| Sceptre Tech            | 21        | 0.53%   |
| Vizio                   | 20        | 0.5%    |
| InfoVision              | 19        | 0.48%   |
| Eizo                    | 19        | 0.48%   |
| LG Electronics          | 16        | 0.4%    |
| Toshiba                 | 14        | 0.35%   |
| Panasonic               | 12        | 0.3%    |
| HannStar                | 10        | 0.25%   |
| Vestel Elektronik       | 9         | 0.23%   |
| Unknown (XXX)           | 9         | 0.23%   |
| Unknown                 | 9         | 0.23%   |
| Insignia                | 7         | 0.18%   |
| HKC                     | 7         | 0.18%   |
| MStar                   | 6         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 34        | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 24        | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 19        | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 17        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 17        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 16        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 14        | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 13        | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 13        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 12        | 0.29%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 12        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 11        | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 11        | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 10        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.24%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 10        | 0.24%   |
| Vestel Elektronik 49FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 9         | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 9         | 0.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 9         | 0.22%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 9         | 0.22%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 9         | 0.22%   |
| Unknown                                                               | 9         | 0.22%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 8         | 0.19%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 8         | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 8         | 0.19%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 8         | 0.19%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 8         | 0.19%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1810      | 48.45%  |
| 1366x768 (WXGA)    | 497       | 13.3%   |
| 2560x1440 (QHD)    | 309       | 8.27%   |
| 3840x2160 (4K)     | 292       | 7.82%   |
| 1600x900 (HD+)     | 117       | 3.13%   |
| 1920x1200 (WUXGA)  | 73        | 1.95%   |
| 2560x1080          | 68        | 1.82%   |
| 1680x1050 (WSXGA+) | 65        | 1.74%   |
| 1440x900 (WXGA+)   | 65        | 1.74%   |
| 3440x1440          | 55        | 1.47%   |
| 1280x1024 (SXGA)   | 52        | 1.39%   |
| 2560x1600          | 38        | 1.02%   |
| 1280x800 (WXGA)    | 37        | 0.99%   |
| 2288x1287          | 35        | 0.94%   |
| 2880x1800          | 31        | 0.83%   |
| Unknown            | 26        | 0.7%    |
| 3840x1080          | 25        | 0.67%   |
| 1360x768           | 21        | 0.56%   |
| 2160x1440          | 13        | 0.35%   |
| 1920x540           | 12        | 0.32%   |
| 3840x2400          | 10        | 0.27%   |
| 1600x1200          | 8         | 0.21%   |
| 3840x1600          | 6         | 0.16%   |
| 3200x1800 (QHD+)   | 6         | 0.16%   |
| 3456x2160          | 4         | 0.11%   |
| 2880x1920          | 4         | 0.11%   |
| 2256x1504          | 4         | 0.11%   |
| 2240x1400          | 3         | 0.08%   |
| 1280x720 (HD)      | 3         | 0.08%   |
| 1024x768 (XGA)     | 3         | 0.08%   |
| 1024x600           | 3         | 0.08%   |
| 800x1280           | 2         | 0.05%   |
| 5760x2160          | 2         | 0.05%   |
| 3200x2000          | 2         | 0.05%   |
| 3000x2000          | 2         | 0.05%   |
| 2944x1080          | 2         | 0.05%   |
| 2736x1824          | 2         | 0.05%   |
| 2160x1350          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 1800x1200          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 919       | 23.2%   |
| 27      | 405       | 10.22%  |
| 24      | 358       | 9.04%   |
| 13      | 291       | 7.35%   |
| 14      | 277       | 6.99%   |
| 23      | 239       | 6.03%   |
| 21      | 204       | 5.15%   |
| 31      | 180       | 4.54%   |
| 17      | 176       | 4.44%   |
| Unknown | 106       | 2.68%   |
| 34      | 100       | 2.52%   |
| 19      | 73        | 1.84%   |
| 12      | 60        | 1.51%   |
| 18      | 55        | 1.39%   |
| 22      | 45        | 1.14%   |
| 16      | 44        | 1.11%   |
| 40      | 40        | 1.01%   |
| 20      | 38        | 0.96%   |
| 54      | 37        | 0.93%   |
| 84      | 35        | 0.88%   |
| 142     | 34        | 0.86%   |
| 72      | 30        | 0.76%   |
| 32      | 28        | 0.71%   |
| 11      | 21        | 0.53%   |
| 28      | 20        | 0.5%    |
| 26      | 14        | 0.35%   |
| 25      | 13        | 0.33%   |
| 49      | 12        | 0.3%    |
| 48      | 11        | 0.28%   |
| 65      | 10        | 0.25%   |
| 52      | 10        | 0.25%   |
| 42      | 9         | 0.23%   |
| 29      | 9         | 0.23%   |
| 10      | 8         | 0.2%    |
| 74      | 7         | 0.18%   |
| 43      | 5         | 0.13%   |
| 37      | 5         | 0.13%   |
| 36      | 5         | 0.13%   |
| 35      | 5         | 0.13%   |
| 46      | 4         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1375      | 35.71%  |
| 501-600        | 902       | 23.42%  |
| 401-500        | 370       | 9.61%   |
| 601-700        | 249       | 6.47%   |
| 201-300        | 238       | 6.18%   |
| 351-400        | 207       | 5.38%   |
| 701-800        | 131       | 3.4%    |
| Unknown        | 106       | 2.75%   |
| 1001-1500      | 90        | 2.34%   |
| 1501-2000      | 73        | 1.9%    |
| 801-900        | 57        | 1.48%   |
| More than 2000 | 34        | 0.88%   |
| 901-1000       | 17        | 0.44%   |
| 1-100          | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2744      | 78.9%   |
| 16/10   | 348       | 10.01%  |
| 21/9    | 128       | 3.68%   |
| Unknown | 79        | 2.27%   |
| 5/4     | 50        | 1.44%   |
| 3/2     | 39        | 1.12%   |
| 1.00    | 34        | 0.98%   |
| 4/3     | 20        | 0.58%   |
| 32/9    | 19        | 0.55%   |
| 6/5     | 6         | 0.17%   |
| 2.00    | 2         | 0.06%   |
| 0.67    | 2         | 0.06%   |
| 0.56    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 3.33    | 1         | 0.03%   |
| 2.70    | 1         | 0.03%   |
| 0.80    | 1         | 0.03%   |
| 0.25    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 915       | 23.41%  |
| 201-250        | 675       | 17.27%  |
| 81-90          | 456       | 11.67%  |
| 301-350        | 417       | 10.67%  |
| 351-500        | 323       | 8.27%   |
| More than 1000 | 167       | 4.27%   |
| 151-200        | 159       | 4.07%   |
| 121-130        | 141       | 3.61%   |
| 251-300        | 126       | 3.22%   |
| Unknown        | 106       | 2.71%   |
| 71-80          | 105       | 2.69%   |
| 501-1000       | 90        | 2.3%    |
| 141-150        | 73        | 1.87%   |
| 61-70          | 55        | 1.41%   |
| 111-120        | 35        | 0.9%    |
| 51-60          | 23        | 0.59%   |
| 91-100         | 18        | 0.46%   |
| 131-140        | 15        | 0.38%   |
| 41-50          | 7         | 0.18%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1258      | 33.56%  |
| 121-160       | 1091      | 29.11%  |
| 101-120       | 850       | 22.68%  |
| 161-240       | 224       | 5.98%   |
| 1-50          | 139       | 3.71%   |
| Unknown       | 106       | 2.83%   |
| More than 240 | 80        | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2553      | 74.32%  |
| 2     | 716       | 20.84%  |
| 3     | 90        | 2.62%   |
| 0     | 69        | 2.01%   |
| 4     | 7         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1912      | 38.56%  |
| Intel                             | 1831      | 36.92%  |
| Qualcomm Atheros                  | 448       | 9.03%   |
| Broadcom                          | 169       | 3.41%   |
| MediaTek                          | 128       | 2.58%   |
| TP-Link                           | 51        | 1.03%   |
| Broadcom Limited                  | 51        | 1.03%   |
| Ralink Technology                 | 45        | 0.91%   |
| ASIX Electronics                  | 23        | 0.46%   |
| Marvell Technology Group          | 20        | 0.4%    |
| Microsoft                         | 17        | 0.34%   |
| Sierra Wireless                   | 16        | 0.32%   |
| Samsung Electronics               | 16        | 0.32%   |
| Nvidia                            | 16        | 0.32%   |
| Aquantia                          | 15        | 0.3%    |
| Ralink                            | 14        | 0.28%   |
| Ericsson Business Mobile Networks | 11        | 0.22%   |
| DisplayLink                       | 11        | 0.22%   |
| Dell                              | 11        | 0.22%   |
| NetGear                           | 9         | 0.18%   |
| D-Link                            | 9         | 0.18%   |
| Qualcomm                          | 8         | 0.16%   |
| Qualcomm Atheros Communications   | 7         | 0.14%   |
| Lenovo                            | 7         | 0.14%   |
| D-Link System                     | 7         | 0.14%   |
| Xiaomi                            | 6         | 0.12%   |
| OPPO Electronics                  | 6         | 0.12%   |
| ASUSTek Computer                  | 6         | 0.12%   |
| Huawei Technologies               | 5         | 0.1%    |
| Hewlett-Packard                   | 5         | 0.1%    |
| Fibocom                           | 5         | 0.1%    |
| Edimax Technology                 | 5         | 0.1%    |
| Motorola PCS                      | 4         | 0.08%   |
| JMicron Technology                | 4         | 0.08%   |
| Insyde Software                   | 4         | 0.08%   |
| T & A Mobile Phones               | 3         | 0.06%   |
| Microchip Technology              | 3         | 0.06%   |
| ICS Advent                        | 3         | 0.06%   |
| Tenda                             | 2         | 0.04%   |
| Solarflare Communications         | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1356      | 22.81%  |
| Intel Wi-Fi 6 AX200                                                    | 242       | 4.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 149       | 2.51%   |
| Realtek RTL8125 2.5GbE Controller                                      | 146       | 2.46%   |
| Intel I211 Gigabit Network Connection                                  | 133       | 2.24%   |
| Intel Wireless 8265 / 8275                                             | 116       | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 108       | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 97        | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 94        | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 85        | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 85        | 1.43%   |
| Intel Wireless 7260                                                    | 77        | 1.3%    |
| Intel Wireless 7265                                                    | 76        | 1.28%   |
| Intel Ethernet Controller I225-V                                       | 74        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                                   | 73        | 1.23%   |
| Intel Wireless 8260                                                    | 69        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 68        | 1.14%   |
| Intel Wi-Fi 6 AX201                                                    | 68        | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 64        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 63        | 1.06%   |
| Intel Ethernet Connection I217-LM                                      | 60        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 59        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 54        | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 53        | 0.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 53        | 0.89%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 53        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                                   | 52        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 51        | 0.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 49        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 45        | 0.76%   |
| Intel Wireless 3165                                                    | 44        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 40        | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 40        | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 37        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                  | 35        | 0.59%   |
| Intel Ethernet Connection I219-LM                                      | 29        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                                  | 29        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 28        | 0.47%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 27        | 0.45%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 26        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1428      | 52.73%  |
| Realtek Semiconductor                 | 446       | 16.47%  |
| Qualcomm Atheros                      | 355       | 13.11%  |
| Broadcom                              | 120       | 4.43%   |
| MediaTek                              | 112       | 4.14%   |
| TP-Link                               | 45        | 1.66%   |
| Ralink Technology                     | 45        | 1.66%   |
| Broadcom Limited                      | 39        | 1.44%   |
| Sierra Wireless                       | 16        | 0.59%   |
| Microsoft                             | 16        | 0.59%   |
| Ralink                                | 14        | 0.52%   |
| NetGear                               | 9         | 0.33%   |
| D-Link                                | 9         | 0.33%   |
| Qualcomm Atheros Communications       | 7         | 0.26%   |
| Dell                                  | 7         | 0.26%   |
| Marvell Technology Group              | 6         | 0.22%   |
| ASUSTek Computer                      | 6         | 0.22%   |
| Fibocom                               | 5         | 0.18%   |
| Edimax Technology                     | 5         | 0.18%   |
| D-Link System                         | 4         | 0.15%   |
| Hewlett-Packard                       | 3         | 0.11%   |
| Tenda                                 | 2         | 0.07%   |
| Qualcomm Technologies                 | 2         | 0.07%   |
| Belkin Components                     | 2         | 0.07%   |
| Xiaomi                                | 1         | 0.04%   |
| Ovislink                              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| CyberTAN Technology                   | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 242       | 8.88%   |
| Intel Wireless 8265 / 8275                                           | 116       | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 97        | 3.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 94        | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 85        | 3.12%   |
| Intel Wireless 7260                                                  | 77        | 2.83%   |
| Intel Wireless 7265                                                  | 76        | 2.79%   |
| Intel Wireless 8260                                                  | 69        | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 68        | 2.5%    |
| Intel Wi-Fi 6 AX201                                                  | 68        | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 64        | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 63        | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 59        | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 54        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 53        | 1.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 53        | 1.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 53        | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 51        | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 49        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 45        | 1.65%   |
| Intel Wireless 3165                                                  | 44        | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 40        | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 40        | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 28        | 1.03%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 27        | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 26        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 26        | 0.95%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 25        | 0.92%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 24        | 0.88%   |
| Realtek 802.11ac NIC                                                 | 24        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 23        | 0.84%   |
| Ralink MT7601U Wireless Adapter                                      | 23        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 23        | 0.84%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 23        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 22        | 0.81%   |
| Intel Wireless 3160                                                  | 22        | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 21        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                       | 21        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 19        | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 18        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1752      | 56.64%  |
| Intel                                  | 940       | 30.39%  |
| Qualcomm Atheros                       | 125       | 4.04%   |
| Broadcom                               | 81        | 2.62%   |
| ASIX Electronics                       | 23        | 0.74%   |
| Nvidia                                 | 16        | 0.52%   |
| Aquantia                               | 15        | 0.48%   |
| MediaTek                               | 14        | 0.45%   |
| Marvell Technology Group               | 14        | 0.45%   |
| Broadcom Limited                       | 12        | 0.39%   |
| Samsung Electronics                    | 11        | 0.36%   |
| DisplayLink                            | 11        | 0.36%   |
| Qualcomm                               | 8         | 0.26%   |
| TP-Link                                | 6         | 0.19%   |
| OPPO Electronics                       | 6         | 0.19%   |
| Lenovo                                 | 6         | 0.19%   |
| Xiaomi                                 | 5         | 0.16%   |
| Motorola PCS                           | 4         | 0.13%   |
| JMicron Technology                     | 4         | 0.13%   |
| Insyde Software                        | 4         | 0.13%   |
| T & A Mobile Phones                    | 3         | 0.1%    |
| ICS Advent                             | 3         | 0.1%    |
| Huawei Technologies                    | 3         | 0.1%    |
| D-Link System                          | 3         | 0.1%    |
| Solarflare Communications              | 2         | 0.06%   |
| Emulex                                 | 2         | 0.06%   |
| Apple                                  | 2         | 0.06%   |
| vivo                                   | 1         | 0.03%   |
| VIA Technologies                       | 1         | 0.03%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.03%   |
| Research In Motion                     | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| QinHeng Electronics                    | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| Novatel Wireless                       | 1         | 0.03%   |
| Microsoft                              | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| Mellanox Technologies                  | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1356      | 42.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 149       | 4.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 146       | 4.6%    |
| Intel I211 Gigabit Network Connection                                  | 133       | 4.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 108       | 3.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 85        | 2.68%   |
| Intel Ethernet Controller I225-V                                       | 74        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 73        | 2.3%    |
| Intel Ethernet Connection I217-LM                                      | 60        | 1.89%   |
| Intel Ethernet Connection (7) I219-V                                   | 52        | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                                  | 35        | 1.1%    |
| Intel Ethernet Connection I219-LM                                      | 29        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                  | 29        | 0.91%   |
| Intel Ethernet Connection I218-LM                                      | 26        | 0.82%   |
| Intel Ethernet Connection I217-V                                       | 25        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 23        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                  | 22        | 0.69%   |
| Realtek Killer E2600 GbE Controller                                    | 21        | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                          | 21        | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 20        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 18        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                  | 18        | 0.57%   |
| Intel I210 Gigabit Network Connection                                  | 17        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                | 17        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                               | 17        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 16        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 15        | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 15        | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                                  | 14        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                                   | 13        | 0.41%   |
| Intel Ethernet Connection (2) I218-V                                   | 13        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 11        | 0.35%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 11        | 0.35%   |
| Intel Ethernet Controller I226-V                                       | 10        | 0.32%   |
| Intel Ethernet Connection X553 1GbE                                    | 10        | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.28%   |
| Intel Ethernet Connection I219-V                                       | 9         | 0.28%   |
| Intel Ethernet Connection (6) I219-LM                                  | 9         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2902      | 52.44%  |
| WiFi     | 2586      | 46.73%  |
| Modem    | 42        | 0.76%   |
| Unknown  | 4         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1955      | 55.67%  |
| Ethernet | 1557      | 44.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1889      | 56.34%  |
| 1     | 1306      | 38.95%  |
| 3     | 108       | 3.22%   |
| 4     | 24        | 0.72%   |
| 0     | 19        | 0.57%   |
| 5     | 4         | 0.12%   |
| 6     | 2         | 0.06%   |
| 9     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2438      | 71.06%  |
| Yes  | 993       | 28.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1254      | 51.78%  |
| Realtek Semiconductor           | 245       | 10.12%  |
| Qualcomm Atheros Communications | 160       | 6.61%   |
| Cambridge Silicon Radio         | 138       | 5.7%    |
| IMC Networks                    | 123       | 5.08%   |
| Apple                           | 90        | 3.72%   |
| Broadcom                        | 84        | 3.47%   |
| Foxconn / Hon Hai               | 65        | 2.68%   |
| Lite-On Technology              | 60        | 2.48%   |
| ASUSTek Computer                | 55        | 2.27%   |
| MediaTek                        | 50        | 2.06%   |
| TP-Link                         | 22        | 0.91%   |
| Dell                            | 17        | 0.7%    |
| Realtek                         | 12        | 0.5%    |
| Toshiba                         | 9         | 0.37%   |
| Hewlett-Packard                 | 6         | 0.25%   |
| Marvell Semiconductor           | 4         | 0.17%   |
| Edimax Technology               | 4         | 0.17%   |
| Belkin Components               | 4         | 0.17%   |
| Ralink                          | 3         | 0.12%   |
| Dynex                           | 3         | 0.12%   |
| Actions                         | 3         | 0.12%   |
| Ralink Technology               | 2         | 0.08%   |
| HTC (High Tech Computer)        | 2         | 0.08%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Foxconn International           | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 397       | 16.38%  |
| Intel AX200 Bluetooth                               | 234       | 9.65%   |
| Intel AX201 Bluetooth                               | 195       | 8.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 167       | 6.89%   |
| Realtek Bluetooth Radio                             | 141       | 5.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 138       | 5.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 95        | 3.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 58        | 2.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 56        | 2.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 54        | 2.23%   |
| Intel AX211 Bluetooth                               | 53        | 2.19%   |
| MediaTek Wireless_Device                            | 49        | 2.02%   |
| Intel AX210 Bluetooth                               | 48        | 1.98%   |
| IMC Networks Bluetooth Radio                        | 48        | 1.98%   |
| Apple Bluetooth Host Controller                     | 42        | 1.73%   |
| IMC Networks Wireless_Device                        | 38        | 1.57%   |
| Apple Bluetooth USB Host Controller                 | 36        | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 33        | 1.36%   |
| Broadcom BCM2045B (BDC-2.1)                         | 27        | 1.11%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 22        | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 0.91%   |
| Lite-On Bluetooth Device                            | 22        | 0.91%   |
| IMC Networks Bluetooth Device                       | 21        | 0.87%   |
| Realtek 802.11ac WLAN Adapter                       | 20        | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 20        | 0.83%   |
| ASUS ASUS USB-BT500                                 | 20        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 0.78%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 19        | 0.78%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 15        | 0.62%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 0.58%   |
| Realtek Bluetooth Radio                             | 12        | 0.5%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 0.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 10        | 0.41%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 10        | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2225      | 42.53%  |
| AMD                                          | 1208      | 23.09%  |
| Nvidia                                       | 1037      | 19.82%  |
| C-Media Electronics                          | 104       | 1.99%   |
| Logitech                                     | 70        | 1.34%   |
| Texas Instruments                            | 41        | 0.78%   |
| Kingston Technology                          | 37        | 0.71%   |
| JMTek                                        | 31        | 0.59%   |
| Razer USA                                    | 30        | 0.57%   |
| Focusrite-Novation                           | 27        | 0.52%   |
| ASUSTek Computer                             | 26        | 0.5%    |
| Realtek Semiconductor                        | 20        | 0.38%   |
| Generalplus Technology                       | 20        | 0.38%   |
| Creative Labs                                | 20        | 0.38%   |
| Corsair                                      | 20        | 0.38%   |
| SteelSeries ApS                              | 19        | 0.36%   |
| Creative Technology                          | 19        | 0.36%   |
| DSEA A/S                                     | 11        | 0.21%   |
| BEHRINGER International                      | 10        | 0.19%   |
| Sony                                         | 9         | 0.17%   |
| RODE Microphones                             | 9         | 0.17%   |
| Lenovo                                       | 9         | 0.17%   |
| Hewlett-Packard                              | 9         | 0.17%   |
| GN Netcom                                    | 9         | 0.17%   |
| Samson Technologies                          | 8         | 0.15%   |
| Astro Gaming                                 | 7         | 0.13%   |
| Yamaha                                       | 6         | 0.11%   |
| XMOS                                         | 6         | 0.11%   |
| Thesycon Systemsoftware & Consulting         | 6         | 0.11%   |
| SAVITECH                                     | 6         | 0.11%   |
| PreSonus Audio Electronics                   | 6         | 0.11%   |
| Blue Microphones                             | 6         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.1%    |
| Plantronics                                  | 5         | 0.1%    |
| Jieli Technology                             | 5         | 0.1%    |
| Audio-Technica                               | 5         | 0.1%    |
| Native Instruments                           | 4         | 0.08%   |
| Micro Star International                     | 4         | 0.08%   |
| M-Audio                                      | 4         | 0.08%   |
| KTMicro                                      | 4         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 476       | 7.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 284       | 4.51%   |
| Intel Sunrise Point-LP HD Audio                                            | 272       | 4.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 214       | 3.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 202       | 3.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 190       | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 167       | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 166       | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 126       | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 118       | 1.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 117       | 1.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 115       | 1.83%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 105       | 1.67%   |
| Intel 200 Series PCH HD Audio                                              | 100       | 1.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 94        | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 92        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 87        | 1.38%   |
| Nvidia TU116 High Definition Audio Controller                              | 81        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 81        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 78        | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 78        | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 77        | 1.22%   |
| Nvidia GP106 High Definition Audio Controller                              | 73        | 1.16%   |
| Nvidia GA104 High Definition Audio Controller                              | 73        | 1.16%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 70        | 1.11%   |
| Nvidia GP104 High Definition Audio Controller                              | 69        | 1.1%    |
| Intel Comet Lake PCH cAVS                                                  | 68        | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 68        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 68        | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 66        | 1.05%   |
| Intel Broadwell-U Audio Controller                                         | 66        | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                              | 61        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 57        | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 53        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 52        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 51        | 0.81%   |
| AMD FCH Azalia Controller                                                  | 51        | 0.81%   |
| AMD Navi 10 HDMI Audio                                                     | 49        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 45        | 0.71%   |
| Nvidia TU104 HD Audio Controller                                           | 43        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 789       | 21.01%  |
| SK hynix                     | 649       | 17.28%  |
| Kingston                     | 426       | 11.34%  |
| Micron Technology            | 351       | 9.35%   |
| Corsair                      | 317       | 8.44%   |
| Crucial                      | 259       | 6.9%    |
| G.Skill                      | 216       | 5.75%   |
| Unknown                      | 177       | 4.71%   |
| A-DATA Technology            | 90        | 2.4%    |
| Ramaxel Technology           | 63        | 1.68%   |
| Team                         | 53        | 1.41%   |
| Nanya Technology             | 36        | 0.96%   |
| Elpida                       | 34        | 0.91%   |
| Unknown                      | 29        | 0.77%   |
| Patriot                      | 21        | 0.56%   |
| Unknown (ABCD)               | 19        | 0.51%   |
| Apacer                       | 14        | 0.37%   |
| GOODRAM                      | 12        | 0.32%   |
| PNY                          | 11        | 0.29%   |
| Neo Forza                    | 10        | 0.27%   |
| Transcend                    | 9         | 0.24%   |
| Timetec                      | 9         | 0.24%   |
| Smart                        | 8         | 0.21%   |
| Silicon Power                | 8         | 0.21%   |
| Avant                        | 8         | 0.21%   |
| AMD                          | 8         | 0.21%   |
| Goldkey                      | 7         | 0.19%   |
| ASint Technology             | 6         | 0.16%   |
| Patriot Memory (PDP Systems) | 5         | 0.13%   |
| Lexar                        | 5         | 0.13%   |
| Sesame                       | 4         | 0.11%   |
| Kllisre                      | 4         | 0.11%   |
| Kingmax                      | 4         | 0.11%   |
| Atermiter                    | 4         | 0.11%   |
| Asgard                       | 4         | 0.11%   |
| Teikon                       | 3         | 0.08%   |
| Smart Brazil                 | 3         | 0.08%   |
| Golden Empire                | 3         | 0.08%   |
| GeIL                         | 3         | 0.08%   |
| CSX                          | 3         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 0.84%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 31        | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 30        | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 30        | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 29        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 29        | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 0.72%   |
| Unknown                                                          | 29        | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 26        | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 22        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 21        | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 19        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s            | 19        | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.42%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 17        | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.37%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.37%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 14        | 0.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s              | 14        | 0.35%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 13        | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 13        | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.3%    |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s            | 12        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1866      | 58.59%  |
| DDR3    | 885       | 27.79%  |
| DDR5    | 128       | 4.02%   |
| LPDDR4  | 74        | 2.32%   |
| LPDDR3  | 59        | 1.85%   |
| SDRAM   | 44        | 1.38%   |
| DDR2    | 41        | 1.29%   |
| Unknown | 41        | 1.29%   |
| LPDDR5  | 38        | 1.19%   |
| DRAM    | 5         | 0.16%   |
| DDR     | 4         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1709      | 53.67%  |
| DIMM         | 1264      | 39.7%   |
| Row Of Chips | 188       | 5.9%    |
| Chip         | 16        | 0.5%    |
| Unknown      | 4         | 0.13%   |
| RIMM         | 3         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1501      | 42.69%  |
| 4096  | 824       | 23.44%  |
| 16384 | 737       | 20.96%  |
| 2048  | 229       | 6.51%   |
| 32768 | 181       | 5.15%   |
| 1024  | 33        | 0.94%   |
| 49152 | 4         | 0.11%   |
| 24576 | 2         | 0.06%   |
| 512   | 2         | 0.06%   |
| 12288 | 1         | 0.03%   |
| 64    | 1         | 0.03%   |
| 16    | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 635       | 17.94%  |
| 1600    | 628       | 17.74%  |
| 2667    | 564       | 15.93%  |
| 2400    | 275       | 7.77%   |
| 3600    | 170       | 4.8%    |
| 1333    | 151       | 4.27%   |
| 2133    | 150       | 4.24%   |
| 1334    | 68        | 1.92%   |
| 4800    | 57        | 1.61%   |
| 3733    | 51        | 1.44%   |
| 3800    | 50        | 1.41%   |
| 1867    | 48        | 1.36%   |
| 3000    | 43        | 1.21%   |
| 3266    | 36        | 1.02%   |
| 6400    | 34        | 0.96%   |
| 3400    | 33        | 0.93%   |
| 1067    | 33        | 0.93%   |
| 5600    | 27        | 0.76%   |
| 4267    | 27        | 0.76%   |
| 800     | 27        | 0.76%   |
| Unknown | 27        | 0.76%   |
| 2666    | 26        | 0.73%   |
| 1866    | 24        | 0.68%   |
| 4000    | 23        | 0.65%   |
| 1800    | 23        | 0.65%   |
| 667     | 22        | 0.62%   |
| 6000    | 21        | 0.59%   |
| 3466    | 20        | 0.56%   |
| 2933    | 16        | 0.45%   |
| 3866    | 15        | 0.42%   |
| 3666    | 15        | 0.42%   |
| 2800    | 15        | 0.42%   |
| 2048    | 14        | 0.4%    |
| 5200    | 11        | 0.31%   |
| 4266    | 11        | 0.31%   |
| 3534    | 11        | 0.31%   |
| 4199    | 10        | 0.28%   |
| 8400    | 9         | 0.25%   |
| 3334    | 8         | 0.23%   |
| 2000    | 8         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 25        | 34.72%  |
| Brother Industries    | 24        | 33.33%  |
| Seiko Epson           | 8         | 11.11%  |
| Canon                 | 6         | 8.33%   |
| Samsung Electronics   | 2         | 2.78%   |
| Ricoh                 | 1         | 1.39%   |
| Prolific Technology   | 1         | 1.39%   |
| MIIIW                 | 1         | 1.39%   |
| Lexmark International | 1         | 1.39%   |
| Kyocera               | 1         | 1.39%   |
| Gprinter              | 1         | 1.39%   |
| Dymo-CoStar           | 1         | 1.39%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series              | 3         | 4.11%   |
| Seiko Epson ET-4700 Series             | 2         | 2.74%   |
| HP DeskJet F4100 Printer series        | 2         | 2.74%   |
| HP DeskJet 2700 series                 | 2         | 2.74%   |
| HP DeskJet 2620 All-in-One Printer     | 2         | 2.74%   |
| Brother MFC-J6545DW                    | 2         | 2.74%   |
| Brother DCP-7055 scanner/printer       | 2         | 2.74%   |
| Seiko Epson XP-243 245 247 Series      | 1         | 1.37%   |
| Seiko Epson XP-2100 Series             | 1         | 1.37%   |
| Seiko Epson WF-2870 Series             | 1         | 1.37%   |
| Seiko Epson Stylus NX230/SX235W Series | 1         | 1.37%   |
| Seiko Epson L6270 Series               | 1         | 1.37%   |
| Seiko Epson L3150 Series               | 1         | 1.37%   |
| Samsung SCX-3400 Series                | 1         | 1.37%   |
| Samsung SCX-3200 Series                | 1         | 1.37%   |
| Ricoh SP 213w                          | 1         | 1.37%   |
| Prolific PL2305 Parallel Port          | 1         | 1.37%   |
| MIIIW MW Keyboard Air Mini             | 1         | 1.37%   |
| Lexmark International B2236dw          | 1         | 1.37%   |
| Kyocera UTAX_TA LP 3240_LP 4240        | 1         | 1.37%   |
| HP PSC 1400                            | 1         | 1.37%   |
| HP OfficeJet Pro 8020 series           | 1         | 1.37%   |
| HP OfficeJet Pro 6960                  | 1         | 1.37%   |
| HP OfficeJet 5200 series               | 1         | 1.37%   |
| HP OfficeJet 4650 series               | 1         | 1.37%   |
| HP LaserJet Professional P1102w        | 1         | 1.37%   |
| HP LaserJet P1005                      | 1         | 1.37%   |
| HP LaserJet M203-M206                  | 1         | 1.37%   |
| HP LaserJet 3050                       | 1         | 1.37%   |
| HP LaserJet 1020                       | 1         | 1.37%   |
| HP LaserJet 1015                       | 1         | 1.37%   |
| HP Ink Tank Wireless 410 series        | 1         | 1.37%   |
| HP Ink Tank 110 series                 | 1         | 1.37%   |
| HP ENVY 6400 series                    | 1         | 1.37%   |
| HP ENVY 5000 series                    | 1         | 1.37%   |
| HP ENVY 4500 series                    | 1         | 1.37%   |
| HP DeskJet F2492 All-in-One            | 1         | 1.37%   |
| HP Deskjet 4640 series                 | 1         | 1.37%   |
| HP DeskJet 3700 series                 | 1         | 1.37%   |
| HP Deskjet 1050 J410                   | 1         | 1.37%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Hewlett-Packard | 2         | 22.22%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 22.22%  |
| Seiko Epson Perfection V37/V370                         | 1         | 11.11%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 11.11%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 11.11%  |
| HP ScanJet 2400c                                        | 1         | 11.11%  |
| HP ScanJet 2200c                                        | 1         | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 444       | 21.85%  |
| IMC Networks                           | 229       | 11.27%  |
| Microdia                               | 168       | 8.27%   |
| Logitech                               | 145       | 7.14%   |
| Realtek Semiconductor                  | 140       | 6.89%   |
| Bison Electronics                      | 140       | 6.89%   |
| Sunplus Innovation Technology          | 107       | 5.27%   |
| Quanta                                 | 91        | 4.48%   |
| Apple                                  | 67        | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 51        | 2.51%   |
| Syntek                                 | 50        | 2.46%   |
| Lite-On Technology                     | 38        | 1.87%   |
| Luxvisions Innotech Limited            | 37        | 1.82%   |
| Suyin                                  | 34        | 1.67%   |
| Acer                                   | 32        | 1.57%   |
| Sonix Technology                       | 26        | 1.28%   |
| Samsung Electronics                    | 23        | 1.13%   |
| Silicon Motion                         | 20        | 0.98%   |
| Microsoft                              | 18        | 0.89%   |
| Lenovo                                 | 14        | 0.69%   |
| Alcor Micro                            | 12        | 0.59%   |
| Razer USA                              | 10        | 0.49%   |
| Generalplus Technology                 | 10        | 0.49%   |
| ARC International                      | 7         | 0.34%   |
| Primax Electronics                     | 6         | 0.3%    |
| KYE Systems (Mouse Systems)            | 5         | 0.25%   |
| Importek                               | 5         | 0.25%   |
| Hewlett-Packard                        | 5         | 0.25%   |
| GEMBIRD                                | 5         | 0.25%   |
| Creative Technology                    | 5         | 0.25%   |
| Z-Star Microelectronics                | 4         | 0.2%    |
| Ricoh                                  | 4         | 0.2%    |
| MacroSilicon                           | 4         | 0.2%    |
| icSpring                               | 4         | 0.2%    |
| Google                                 | 4         | 0.2%    |
| WaveRider Communications               | 3         | 0.15%   |
| SunplusIT                              | 3         | 0.15%   |
| Shinetech                              | 3         | 0.15%   |
| OPPO Electronics                       | 3         | 0.15%   |
| Unknown                                | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 122       | 5.98%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 69        | 3.38%   |
| IMC Networks Integrated Camera                      | 66        | 3.23%   |
| Microdia Integrated_Webcam_HD                       | 65        | 3.18%   |
| Realtek Integrated_Webcam_HD                        | 56        | 2.74%   |
| Bison Integrated Camera                             | 47        | 2.3%    |
| Chicony HD WebCam                                   | 41        | 2.01%   |
| Logitech HD Pro Webcam C920                         | 38        | 1.86%   |
| Syntek Integrated Camera                            | 34        | 1.67%   |
| Sunplus Integrated_Webcam_HD                        | 32        | 1.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 31        | 1.52%   |
| Logitech Webcam C270                                | 28        | 1.37%   |
| Lite-On Integrated Camera                           | 27        | 1.32%   |
| Samsung Galaxy series, misc. (MTP mode)             | 23        | 1.13%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 23        | 1.13%   |
| Logitech C922 Pro Stream Webcam                     | 18        | 0.88%   |
| Chicony HP Wide Vision HD Camera                    | 18        | 0.88%   |
| Bison HD Webcam                                     | 17        | 0.83%   |
| Bison EasyCamera                                    | 17        | 0.83%   |
| Apple Built-in iSight                               | 17        | 0.83%   |
| Sonix USB2.0 HD UVC WebCam                          | 16        | 0.78%   |
| Quanta HD User Facing                               | 16        | 0.78%   |
| Chicony USB2.0 VGA UVC WebCam                       | 16        | 0.78%   |
| Chicony USB2.0 Camera                               | 16        | 0.78%   |
| Chicony EasyCamera                                  | 16        | 0.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 15        | 0.73%   |
| Sunplus HD WebCam                                   | 14        | 0.69%   |
| Quanta HP TrueVision HD Camera                      | 14        | 0.69%   |
| Microdia USB 2.0 Camera                             | 14        | 0.69%   |
| Microdia Integrated Webcam                          | 14        | 0.69%   |
| Chicony HP TrueVision HD Camera                     | 14        | 0.69%   |
| Chicony HP TrueVision HD                            | 14        | 0.69%   |
| Apple FaceTime HD Camera (Built-in)                 | 14        | 0.69%   |
| Chicony TOSHIBA Web Camera - HD                     | 13        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.64%   |
| Bison SunplusIT Integrated Camera                   | 13        | 0.64%   |
| Acer BisonCam,NB Pro                                | 13        | 0.64%   |
| Chicony HP HD Camera                                | 12        | 0.59%   |
| Quanta HD Webcam                                    | 11        | 0.54%   |
| Chicony HD User Facing                              | 11        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 115       | 34.12%  |
| Synaptics                          | 99        | 29.38%  |
| Shenzhen Goodix Technology         | 47        | 13.95%  |
| Elan Microelectronics              | 24        | 7.12%   |
| Upek                               | 19        | 5.64%   |
| LighTuning Technology              | 17        | 5.04%   |
| AuthenTec                          | 9         | 2.67%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.89%   |
| STMicroelectronics                 | 2         | 0.59%   |
| Next Biometrics                    | 1         | 0.3%    |
| DigitalPersona                     | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 33        | 9.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 8.31%   |
| Shenzhen Goodix  Fingerprint Device                                        | 24        | 7.12%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 5.93%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 5.34%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 5.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 4.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 3.26%   |
| Elan ELAN:Fingerprint                                                      | 11        | 3.26%   |
| Synaptics  WBDI                                                            | 9         | 2.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.37%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 2.37%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.08%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 2.08%   |
| Synaptics Prometheus Fingerprint Reader                                    | 6         | 1.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.48%   |
| Synaptics WBDI                                                             | 5         | 1.48%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.19%   |
| Validity Sensors VFS491                                                    | 3         | 0.89%   |
| Synaptics WBDI Device                                                      | 3         | 0.89%   |
| Synaptics UWP WBDI                                                         | 3         | 0.89%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.89%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.89%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.89%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 3         | 0.89%   |
| AuthenTec AES2810                                                          | 3         | 0.89%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.59%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.59%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.59%   |
| Synaptics TouchPad                                                         | 2         | 0.59%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.59%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.59%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.59%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 63        | 40.13%  |
| Alcor Micro           | 61        | 38.85%  |
| Upek                  | 8         | 5.1%    |
| O2 Micro              | 7         | 4.46%   |
| Lenovo                | 6         | 3.82%   |
| SCM Microsystems      | 3         | 1.91%   |
| OmniKey               | 2         | 1.27%   |
| Gemalto (was Gemplus) | 2         | 1.27%   |
| Yubico.com            | 1         | 0.64%   |
| Clay Logic            | 1         | 0.64%   |
| Chicony Electronics   | 1         | 0.64%   |
| Cherry                | 1         | 0.64%   |
| Aladdin R.D.          | 1         | 0.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 61        | 38.85%  |
| Broadcom 5880                                                                | 27        | 17.2%   |
| Broadcom 58200                                                               | 14        | 8.92%   |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 8.28%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 5.1%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 5.1%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 3.82%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.82%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.27%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.27%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.64%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.64%   |
| OmniKey CardMan 1021                                                         | 1         | 0.64%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.64%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.64%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.64%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.64%   |
| Cherry Smart Card Reader USB                                                 | 1         | 0.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.64%   |
| Aladdin R.D. JaCarta LT                                                      | 1         | 0.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2539      | 74.2%   |
| 1     | 721       | 21.07%  |
| 2     | 148       | 4.32%   |
| 3     | 8         | 0.23%   |
| 4     | 6         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 337       | 32.88%  |
| Graphics card            | 263       | 25.66%  |
| Chipcard                 | 150       | 14.63%  |
| Net/wireless             | 72        | 7.02%   |
| Multimedia controller    | 53        | 5.17%   |
| Camera                   | 40        | 3.9%    |
| Unassigned class         | 27        | 2.63%   |
| Communication controller | 20        | 1.95%   |
| Bluetooth                | 15        | 1.46%   |
| Net/ethernet             | 14        | 1.37%   |
| Network                  | 9         | 0.88%   |
| Card reader              | 8         | 0.78%   |
| Sound                    | 5         | 0.49%   |
| Storage                  | 3         | 0.29%   |
| Storage/raid             | 2         | 0.2%    |
| Storage/nvme             | 2         | 0.2%    |
| Modem                    | 2         | 0.2%    |
| Dvb card                 | 2         | 0.2%    |
| Wireless                 | 1         | 0.1%    |

