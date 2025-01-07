Linux in Serbia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Serbia/Desktop/README.md) and [notebooks](/Location/Serbia/Notebook/README.md).

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

Total: 1547

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [b2b5aa8eec](https://linux-hardware.org/?probe=b2b5aa8eec) | Jan 05, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [315981955a](https://linux-hardware.org/?probe=315981955a) | Jan 03, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [118b96c4df](https://linux-hardware.org/?probe=118b96c4df) | Jan 03, 2025 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [fd4e4972d2](https://linux-hardware.org/?probe=fd4e4972d2) | Jan 02, 2025 |
| Lenovo        | ThinkPad X230 23252UG       | Notebook    | [d8b0adf8fb](https://linux-hardware.org/?probe=d8b0adf8fb) | Dec 29, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [58be9bacfd](https://linux-hardware.org/?probe=58be9bacfd) | Dec 29, 2024 |
| Lenovo        | ThinkCentre M81 5049D7G     | Desktop     | [2434fa6399](https://linux-hardware.org/?probe=2434fa6399) | Dec 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [118daf4ced](https://linux-hardware.org/?probe=118daf4ced) | Dec 27, 2024 |
| Chuwi         | MiniBook X                  | Notebook    | [2959afdb7e](https://linux-hardware.org/?probe=2959afdb7e) | Dec 27, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [049870e2b4](https://linux-hardware.org/?probe=049870e2b4) | Dec 26, 2024 |
| Apple         | MacBookPro13,2              | Notebook    | [be5b63853b](https://linux-hardware.org/?probe=be5b63853b) | Dec 25, 2024 |
| Gigabyte      | AERO 17 KC                  | Notebook    | [3c4ef2900f](https://linux-hardware.org/?probe=3c4ef2900f) | Dec 24, 2024 |
| HP            | 3396                        | Desktop     | [c26082be18](https://linux-hardware.org/?probe=c26082be18) | Dec 23, 2024 |
| HP            | 3396                        | Desktop     | [a2eda9a830](https://linux-hardware.org/?probe=a2eda9a830) | Dec 23, 2024 |
| ASRock        | N68-GS4 FX                  | Desktop     | [e21e961747](https://linux-hardware.org/?probe=e21e961747) | Dec 22, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [2f18fb67da](https://linux-hardware.org/?probe=2f18fb67da) | Dec 21, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [80f587830a](https://linux-hardware.org/?probe=80f587830a) | Dec 20, 2024 |
| Intel         | NUC13ANBi3 M89896-203       | Mini pc     | [70fdf813cc](https://linux-hardware.org/?probe=70fdf813cc) | Dec 20, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [54970d3023](https://linux-hardware.org/?probe=54970d3023) | Dec 20, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [fcbbbb8ad9](https://linux-hardware.org/?probe=fcbbbb8ad9) | Dec 16, 2024 |
| Lenovo        | ThinkPad T14s Gen 6 21N1... | Notebook    | [179774f835](https://linux-hardware.org/?probe=179774f835) | Dec 15, 2024 |
| Intel         | NUC12WSBi3 M36953-303       | Mini pc     | [fb3d972ca7](https://linux-hardware.org/?probe=fb3d972ca7) | Dec 14, 2024 |
| Acer          | TravelMate 5760G            | Notebook    | [2cd886d5d0](https://linux-hardware.org/?probe=2cd886d5d0) | Dec 14, 2024 |
| Gigabyte      | H81M-S                      | Desktop     | [68e2f55258](https://linux-hardware.org/?probe=68e2f55258) | Dec 13, 2024 |
| Lenovo        | B50-45 20388                | Notebook    | [72fb11f0e5](https://linux-hardware.org/?probe=72fb11f0e5) | Dec 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8444dbbcc1](https://linux-hardware.org/?probe=8444dbbcc1) | Dec 10, 2024 |
| Huanan        | X99-TF                      | Desktop     | [8fd5cc725c](https://linux-hardware.org/?probe=8fd5cc725c) | Dec 10, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [f3e2067835](https://linux-hardware.org/?probe=f3e2067835) | Dec 10, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [6806bb33b6](https://linux-hardware.org/?probe=6806bb33b6) | Dec 04, 2024 |
| MSI           | G41M-P28                    | Desktop     | [1b74dfddb0](https://linux-hardware.org/?probe=1b74dfddb0) | Dec 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [09c386afe5](https://linux-hardware.org/?probe=09c386afe5) | Dec 03, 2024 |
| MSI           | G41M-P28                    | Desktop     | [971098953a](https://linux-hardware.org/?probe=971098953a) | Dec 02, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2e9144632c](https://linux-hardware.org/?probe=2e9144632c) | Dec 02, 2024 |
| HP            | ProBook 430 G1              | Notebook    | [d2da1e52a6](https://linux-hardware.org/?probe=d2da1e52a6) | Dec 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [614c58469c](https://linux-hardware.org/?probe=614c58469c) | Dec 01, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8e8d7035d](https://linux-hardware.org/?probe=d8e8d7035d) | Dec 01, 2024 |
| HP            | 255 G1                      | Notebook    | [0dd46cadda](https://linux-hardware.org/?probe=0dd46cadda) | Nov 29, 2024 |
| MSI           | 770-C45                     | Desktop     | [02a86ec1fe](https://linux-hardware.org/?probe=02a86ec1fe) | Nov 29, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [d24fd529d4](https://linux-hardware.org/?probe=d24fd529d4) | Nov 25, 2024 |
| Dell          | Latitude E6520              | Notebook    | [38d394dc79](https://linux-hardware.org/?probe=38d394dc79) | Nov 24, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5b66a14834](https://linux-hardware.org/?probe=5b66a14834) | Nov 20, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [351278b423](https://linux-hardware.org/?probe=351278b423) | Nov 20, 2024 |
| Acer          | Veriton S6610G              | Desktop     | [07703559d2](https://linux-hardware.org/?probe=07703559d2) | Nov 18, 2024 |
| MSI           | Thin GF63 12UC              | Notebook    | [be325a4b33](https://linux-hardware.org/?probe=be325a4b33) | Nov 17, 2024 |
| MSI           | G41M-P28                    | Desktop     | [6883386504](https://linux-hardware.org/?probe=6883386504) | Nov 15, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [7d2ebdaf04](https://linux-hardware.org/?probe=7d2ebdaf04) | Nov 12, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | Notebook    | [dc7ab7548b](https://linux-hardware.org/?probe=dc7ab7548b) | Nov 10, 2024 |
| Medion        | P6402 MD60800               | Notebook    | [53a167ff43](https://linux-hardware.org/?probe=53a167ff43) | Nov 10, 2024 |
| MSI           | G41M-P28                    | Desktop     | [e0db0a9627](https://linux-hardware.org/?probe=e0db0a9627) | Nov 09, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [2cb55cd612](https://linux-hardware.org/?probe=2cb55cd612) | Nov 09, 2024 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [6fd033b535](https://linux-hardware.org/?probe=6fd033b535) | Nov 09, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [05a19e97e0](https://linux-hardware.org/?probe=05a19e97e0) | Nov 07, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [9a4a8316c4](https://linux-hardware.org/?probe=9a4a8316c4) | Nov 05, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [7277892ee3](https://linux-hardware.org/?probe=7277892ee3) | Nov 03, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [009ebdabc7](https://linux-hardware.org/?probe=009ebdabc7) | Nov 03, 2024 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [27bd6c0cf8](https://linux-hardware.org/?probe=27bd6c0cf8) | Nov 03, 2024 |
| Medion        | MS-7366                     | Desktop     | [0fe38a33d1](https://linux-hardware.org/?probe=0fe38a33d1) | Oct 31, 2024 |
| Lenovo        | ThinkPad X121e 30457KG      | Notebook    | [9242b92b87](https://linux-hardware.org/?probe=9242b92b87) | Oct 30, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [6027aa7a82](https://linux-hardware.org/?probe=6027aa7a82) | Oct 29, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [0846a29ce4](https://linux-hardware.org/?probe=0846a29ce4) | Oct 29, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [dca92ab806](https://linux-hardware.org/?probe=dca92ab806) | Oct 29, 2024 |
| Medion        | MS-7366                     | Desktop     | [786514f25e](https://linux-hardware.org/?probe=786514f25e) | Oct 27, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [e0ef97f425](https://linux-hardware.org/?probe=e0ef97f425) | Oct 24, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [7bdbf89412](https://linux-hardware.org/?probe=7bdbf89412) | Oct 22, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dd1a2d866e](https://linux-hardware.org/?probe=dd1a2d866e) | Oct 19, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d167d5b4b6](https://linux-hardware.org/?probe=d167d5b4b6) | Oct 19, 2024 |
| HP            | 802F                        | Desktop     | [5553cbd4ca](https://linux-hardware.org/?probe=5553cbd4ca) | Oct 17, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [36ce072639](https://linux-hardware.org/?probe=36ce072639) | Oct 14, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [a6d453856a](https://linux-hardware.org/?probe=a6d453856a) | Oct 12, 2024 |
| Micro Comp... | HX100G                      | Desktop     | [2e97a25812](https://linux-hardware.org/?probe=2e97a25812) | Oct 11, 2024 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | Notebook    | [f8affb06fa](https://linux-hardware.org/?probe=f8affb06fa) | Oct 04, 2024 |
| Huanan        | X99-F8                      | Desktop     | [619b6f5845](https://linux-hardware.org/?probe=619b6f5845) | Oct 02, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [458b6c459d](https://linux-hardware.org/?probe=458b6c459d) | Sep 29, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a44ff28e8a](https://linux-hardware.org/?probe=a44ff28e8a) | Sep 29, 2024 |
| Lenovo        | ThinkPad T450 20BV0003US    | Notebook    | [8b03391a58](https://linux-hardware.org/?probe=8b03391a58) | Sep 27, 2024 |
| Lenovo        | ThinkPad T450 20BV0003US    | Notebook    | [219c383c65](https://linux-hardware.org/?probe=219c383c65) | Sep 27, 2024 |
| HP            | Notebook                    | Notebook    | [cfe81118c3](https://linux-hardware.org/?probe=cfe81118c3) | Sep 27, 2024 |
| HP            | Notebook                    | Notebook    | [0695d61a4c](https://linux-hardware.org/?probe=0695d61a4c) | Sep 27, 2024 |
| Medion        | MS-7366                     | Desktop     | [d3f9e281e9](https://linux-hardware.org/?probe=d3f9e281e9) | Sep 23, 2024 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [dd3a3a163e](https://linux-hardware.org/?probe=dd3a3a163e) | Sep 22, 2024 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | Notebook    | [9ea36acf55](https://linux-hardware.org/?probe=9ea36acf55) | Sep 21, 2024 |
| MACHINIST     | X99-RS9 V1.11               | Desktop     | [845631b912](https://linux-hardware.org/?probe=845631b912) | Sep 17, 2024 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [789fe7c711](https://linux-hardware.org/?probe=789fe7c711) | Sep 17, 2024 |
| Dell          | Inspiron 3593               | Notebook    | [fd31f9fa22](https://linux-hardware.org/?probe=fd31f9fa22) | Sep 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [73285b148e](https://linux-hardware.org/?probe=73285b148e) | Sep 11, 2024 |
| HP            | ProBook 440 G3              | Notebook    | [d3d00715d8](https://linux-hardware.org/?probe=d3d00715d8) | Sep 10, 2024 |
| Gigabyte      | AERO 17 KC                  | Notebook    | [ef6af38948](https://linux-hardware.org/?probe=ef6af38948) | Sep 09, 2024 |
| HP            | Notebook                    | Notebook    | [f0c02f3bc1](https://linux-hardware.org/?probe=f0c02f3bc1) | Sep 06, 2024 |
| Acer          | Aspire M3970                | Desktop     | [5c1577174f](https://linux-hardware.org/?probe=5c1577174f) | Sep 06, 2024 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1f335c0708](https://linux-hardware.org/?probe=1f335c0708) | Sep 05, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [eb3537a844](https://linux-hardware.org/?probe=eb3537a844) | Sep 04, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [eaa7e8d7c1](https://linux-hardware.org/?probe=eaa7e8d7c1) | Sep 04, 2024 |
| Lenovo        | ThinkPad T590 20N5S4GB00    | Notebook    | [30fc6b8d42](https://linux-hardware.org/?probe=30fc6b8d42) | Sep 03, 2024 |
| HP            | 802F                        | Desktop     | [7c43df09f7](https://linux-hardware.org/?probe=7c43df09f7) | Sep 02, 2024 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Notebook    | [be1aacd5af](https://linux-hardware.org/?probe=be1aacd5af) | Sep 02, 2024 |
| ASUSTek       | K52F                        | Notebook    | [2f931b5122](https://linux-hardware.org/?probe=2f931b5122) | Aug 31, 2024 |
| HP            | EliteBook 850 G4            | Notebook    | [196f460748](https://linux-hardware.org/?probe=196f460748) | Aug 26, 2024 |
| Toshiba       | Satellite L755              | Notebook    | [25ca4ce2bc](https://linux-hardware.org/?probe=25ca4ce2bc) | Aug 25, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [27ca85151e](https://linux-hardware.org/?probe=27ca85151e) | Aug 23, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [099d384a90](https://linux-hardware.org/?probe=099d384a90) | Aug 22, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | Notebook    | [d559890fdd](https://linux-hardware.org/?probe=d559890fdd) | Aug 21, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [1dbcd28c43](https://linux-hardware.org/?probe=1dbcd28c43) | Aug 20, 2024 |
| Biostar       | TA970 Plus                  | Desktop     | [377448fd65](https://linux-hardware.org/?probe=377448fd65) | Aug 18, 2024 |
| Biostar       | TA970 Plus                  | Desktop     | [acb6724986](https://linux-hardware.org/?probe=acb6724986) | Aug 18, 2024 |
| HP            | Pavilion dv7                | Notebook    | [7f5ad0bf57](https://linux-hardware.org/?probe=7f5ad0bf57) | Aug 13, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [404b2b9643](https://linux-hardware.org/?probe=404b2b9643) | Aug 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [e204f712c3](https://linux-hardware.org/?probe=e204f712c3) | Aug 11, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [e6f02a1205](https://linux-hardware.org/?probe=e6f02a1205) | Aug 11, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [5adc998ab5](https://linux-hardware.org/?probe=5adc998ab5) | Aug 09, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [f21a622ef1](https://linux-hardware.org/?probe=f21a622ef1) | Aug 08, 2024 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [c7526a6b65](https://linux-hardware.org/?probe=c7526a6b65) | Aug 06, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dc9b0a0864](https://linux-hardware.org/?probe=dc9b0a0864) | Aug 05, 2024 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [8c59adcf60](https://linux-hardware.org/?probe=8c59adcf60) | Aug 04, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [6436b82f92](https://linux-hardware.org/?probe=6436b82f92) | Aug 03, 2024 |
| Biostar       | TA970 Plus                  | Desktop     | [b9ca2cb935](https://linux-hardware.org/?probe=b9ca2cb935) | Aug 02, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [caf4309fbe](https://linux-hardware.org/?probe=caf4309fbe) | Aug 02, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [0208f0ca86](https://linux-hardware.org/?probe=0208f0ca86) | Aug 01, 2024 |
| Lenovo        | ThinkPad T590 20N5S4GB00    | Notebook    | [c8205a5fa3](https://linux-hardware.org/?probe=c8205a5fa3) | Jul 30, 2024 |
| Lenovo        | ThinkPad T590 20N5S4GB00    | Notebook    | [b9d54d7c03](https://linux-hardware.org/?probe=b9d54d7c03) | Jul 30, 2024 |
| Lenovo        | ThinkPad T590 20N5S4GB00    | Notebook    | [800180188f](https://linux-hardware.org/?probe=800180188f) | Jul 30, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [d64109dd83](https://linux-hardware.org/?probe=d64109dd83) | Jul 27, 2024 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7eca7458ea](https://linux-hardware.org/?probe=7eca7458ea) | Jul 26, 2024 |
| HP            | ProBook 440 G3              | Notebook    | [2bb0d4150f](https://linux-hardware.org/?probe=2bb0d4150f) | Jul 24, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [c6b7f59209](https://linux-hardware.org/?probe=c6b7f59209) | Jul 23, 2024 |
| Dell          | 0XPDFK A01                  | Desktop     | [dd90b71690](https://linux-hardware.org/?probe=dd90b71690) | Jul 23, 2024 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [b392840045](https://linux-hardware.org/?probe=b392840045) | Jul 22, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [3f3e891da0](https://linux-hardware.org/?probe=3f3e891da0) | Jul 22, 2024 |
| MSI           | GF615M-P33 V2               | Desktop     | [1fdecde171](https://linux-hardware.org/?probe=1fdecde171) | Jul 19, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [6d5758cab5](https://linux-hardware.org/?probe=6d5758cab5) | Jul 19, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [0e35608bc8](https://linux-hardware.org/?probe=0e35608bc8) | Jul 18, 2024 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [b651a9fdfd](https://linux-hardware.org/?probe=b651a9fdfd) | Jul 17, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [6366941838](https://linux-hardware.org/?probe=6366941838) | Jul 17, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d7346cbde0](https://linux-hardware.org/?probe=d7346cbde0) | Jul 17, 2024 |
| Dell          | Latitude E7440              | Notebook    | [452d574c2c](https://linux-hardware.org/?probe=452d574c2c) | Jul 09, 2024 |
| Toshiba       | Satellite L755              | Notebook    | [3a39db9d9b](https://linux-hardware.org/?probe=3a39db9d9b) | Jul 09, 2024 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [04b16c05af](https://linux-hardware.org/?probe=04b16c05af) | Jul 09, 2024 |
| ASUSTek       | A58M-E                      | Desktop     | [fd43969147](https://linux-hardware.org/?probe=fd43969147) | Jul 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9999aa95d2](https://linux-hardware.org/?probe=9999aa95d2) | Jul 07, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [70831ae4a2](https://linux-hardware.org/?probe=70831ae4a2) | Jul 07, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [32be2b30f2](https://linux-hardware.org/?probe=32be2b30f2) | Jul 05, 2024 |
| MSI           | H81M-P33                    | Desktop     | [51486f85b1](https://linux-hardware.org/?probe=51486f85b1) | Jul 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1dba93f632](https://linux-hardware.org/?probe=1dba93f632) | Jul 04, 2024 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [8fefff6140](https://linux-hardware.org/?probe=8fefff6140) | Jul 03, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [d8a111b796](https://linux-hardware.org/?probe=d8a111b796) | Jul 02, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8732c453e6](https://linux-hardware.org/?probe=8732c453e6) | Jun 30, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [5b9357a1e9](https://linux-hardware.org/?probe=5b9357a1e9) | Jun 29, 2024 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3bf2ec223f](https://linux-hardware.org/?probe=3bf2ec223f) | Jun 19, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [86f612102d](https://linux-hardware.org/?probe=86f612102d) | Jun 19, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [d01928c9c4](https://linux-hardware.org/?probe=d01928c9c4) | Jun 15, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f188d375a](https://linux-hardware.org/?probe=5f188d375a) | Jun 14, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [172e6fc98d](https://linux-hardware.org/?probe=172e6fc98d) | Jun 14, 2024 |
| HP            | Compaq Presario CQ60        | Notebook    | [594a3967a3](https://linux-hardware.org/?probe=594a3967a3) | Jun 12, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | Notebook    | [b254287019](https://linux-hardware.org/?probe=b254287019) | Jun 12, 2024 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [74799da2eb](https://linux-hardware.org/?probe=74799da2eb) | Jun 12, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [9a9443ff79](https://linux-hardware.org/?probe=9a9443ff79) | Jun 09, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [765ca44aab](https://linux-hardware.org/?probe=765ca44aab) | Jun 09, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [48e65e34a9](https://linux-hardware.org/?probe=48e65e34a9) | Jun 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [0a84719b87](https://linux-hardware.org/?probe=0a84719b87) | Jun 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [4e4564be77](https://linux-hardware.org/?probe=4e4564be77) | Jun 03, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a7e26ce30a](https://linux-hardware.org/?probe=a7e26ce30a) | Jun 03, 2024 |
| Acer          | Aspire A114-31              | Notebook    | [3953005786](https://linux-hardware.org/?probe=3953005786) | May 31, 2024 |
| Acer          | Aspire A114-31              | Notebook    | [48735b6276](https://linux-hardware.org/?probe=48735b6276) | May 31, 2024 |
| MSI           | H61M-P20                    | Desktop     | [4577901498](https://linux-hardware.org/?probe=4577901498) | May 31, 2024 |
| HP            | 8918                        | Desktop     | [1004c84bae](https://linux-hardware.org/?probe=1004c84bae) | May 30, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [cd4885af14](https://linux-hardware.org/?probe=cd4885af14) | May 28, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [b545c96334](https://linux-hardware.org/?probe=b545c96334) | May 28, 2024 |
| Dell          | 0DR845                      | Desktop     | [a1c98b014b](https://linux-hardware.org/?probe=a1c98b014b) | May 28, 2024 |
| Lenovo        | ThinkPad T590 20N5S4GB00    | Notebook    | [7370423e6a](https://linux-hardware.org/?probe=7370423e6a) | May 27, 2024 |
| Dell          | 0PJDGF A02                  | Desktop     | [51a5de7770](https://linux-hardware.org/?probe=51a5de7770) | May 26, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [ad48868e24](https://linux-hardware.org/?probe=ad48868e24) | May 24, 2024 |
| Dell          | 05XGC8 A01                  | Desktop     | [4b62db7f29](https://linux-hardware.org/?probe=4b62db7f29) | May 21, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [0544db3223](https://linux-hardware.org/?probe=0544db3223) | May 21, 2024 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e84ce47888](https://linux-hardware.org/?probe=e84ce47888) | May 20, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [79c4c910aa](https://linux-hardware.org/?probe=79c4c910aa) | May 16, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | Notebook    | [4cab92f5ed](https://linux-hardware.org/?probe=4cab92f5ed) | May 15, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [c7cb63d9fb](https://linux-hardware.org/?probe=c7cb63d9fb) | May 12, 2024 |
| Medion        | MS-7366                     | Desktop     | [0c36270a48](https://linux-hardware.org/?probe=0c36270a48) | May 06, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [e5f565474a](https://linux-hardware.org/?probe=e5f565474a) | May 05, 2024 |
| Acer          | AOD270                      | Notebook    | [af6b765474](https://linux-hardware.org/?probe=af6b765474) | May 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP36... | Convertible | [8a94ca6d0c](https://linux-hardware.org/?probe=8a94ca6d0c) | May 03, 2024 |
| HP            | ProBook 430 G1              | Notebook    | [7aa4826b7e](https://linux-hardware.org/?probe=7aa4826b7e) | May 03, 2024 |
| Lenovo        | B50-45 20388                | Notebook    | [49ad9c2e0e](https://linux-hardware.org/?probe=49ad9c2e0e) | May 03, 2024 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [32ad893888](https://linux-hardware.org/?probe=32ad893888) | May 02, 2024 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0663c3f0ee](https://linux-hardware.org/?probe=0663c3f0ee) | Apr 30, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [d580243e57](https://linux-hardware.org/?probe=d580243e57) | Apr 30, 2024 |
| HP            | ProBook 440 G3              | Notebook    | [27ac0cda6c](https://linux-hardware.org/?probe=27ac0cda6c) | Apr 29, 2024 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [d40738eda7](https://linux-hardware.org/?probe=d40738eda7) | Apr 28, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | Notebook    | [1361feafda](https://linux-hardware.org/?probe=1361feafda) | Apr 28, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a0fcbd666f](https://linux-hardware.org/?probe=a0fcbd666f) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [3989576cd6](https://linux-hardware.org/?probe=3989576cd6) | Apr 28, 2024 |
| Fujitsu       | D3167-A1 S26361-D3167-A1    | Desktop     | [5182ad8bd7](https://linux-hardware.org/?probe=5182ad8bd7) | Apr 27, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | Notebook    | [a9e235a9db](https://linux-hardware.org/?probe=a9e235a9db) | Apr 27, 2024 |
| Acer          | TravelMate P215-53          | Notebook    | [00d58edb3b](https://linux-hardware.org/?probe=00d58edb3b) | Apr 27, 2024 |
| HP            | ProBook 430 G1              | Notebook    | [9230399ac5](https://linux-hardware.org/?probe=9230399ac5) | Apr 25, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [d8ad825d7c](https://linux-hardware.org/?probe=d8ad825d7c) | Apr 25, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [7dab54dc06](https://linux-hardware.org/?probe=7dab54dc06) | Apr 24, 2024 |
| Lenovo        | G505s 20255                 | Notebook    | [b7d2ec7d4d](https://linux-hardware.org/?probe=b7d2ec7d4d) | Apr 24, 2024 |
| Toshiba       | Satellite Pro L650          | Notebook    | [5a4eb9f755](https://linux-hardware.org/?probe=5a4eb9f755) | Apr 24, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [11d418a07c](https://linux-hardware.org/?probe=11d418a07c) | Apr 22, 2024 |
| ASRock        | H81 Pro BTC                 | Desktop     | [93fdc2cae0](https://linux-hardware.org/?probe=93fdc2cae0) | Apr 22, 2024 |
| SLIMBOOK      | Executive                   | Notebook    | [bdaee49e30](https://linux-hardware.org/?probe=bdaee49e30) | Apr 19, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [2231063264](https://linux-hardware.org/?probe=2231063264) | Apr 19, 2024 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [aeef377b48](https://linux-hardware.org/?probe=aeef377b48) | Apr 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [7e7a28ef89](https://linux-hardware.org/?probe=7e7a28ef89) | Apr 18, 2024 |
| HP            | ProBook 470 G1              | Notebook    | [a400b6efad](https://linux-hardware.org/?probe=a400b6efad) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [7597455fe9](https://linux-hardware.org/?probe=7597455fe9) | Apr 16, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [aaed2b7478](https://linux-hardware.org/?probe=aaed2b7478) | Apr 14, 2024 |
| Dell          | Inspiron 1521               | Notebook    | [0eae25d659](https://linux-hardware.org/?probe=0eae25d659) | Apr 13, 2024 |
| Dell          | 0YC9KY A00                  | Desktop     | [d97e9bda3d](https://linux-hardware.org/?probe=d97e9bda3d) | Apr 12, 2024 |
| Dell          | 0YC9KY A00                  | Desktop     | [250b239ec8](https://linux-hardware.org/?probe=250b239ec8) | Apr 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [b40a1b3e44](https://linux-hardware.org/?probe=b40a1b3e44) | Apr 12, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [6fee790c89](https://linux-hardware.org/?probe=6fee790c89) | Apr 11, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | Notebook    | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [0ca999c16b](https://linux-hardware.org/?probe=0ca999c16b) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [5d0259d7a1](https://linux-hardware.org/?probe=5d0259d7a1) | Apr 06, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17dac6592c](https://linux-hardware.org/?probe=17dac6592c) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [47c56bd4ee](https://linux-hardware.org/?probe=47c56bd4ee) | Apr 05, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7238741c32](https://linux-hardware.org/?probe=7238741c32) | Apr 05, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [a9490d11d7](https://linux-hardware.org/?probe=a9490d11d7) | Apr 04, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [4b51c98fb6](https://linux-hardware.org/?probe=4b51c98fb6) | Apr 04, 2024 |
| Dell          | Latitude E7440              | Notebook    | [81be6cf5c3](https://linux-hardware.org/?probe=81be6cf5c3) | Apr 02, 2024 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [9ce8633d67](https://linux-hardware.org/?probe=9ce8633d67) | Apr 02, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [6d4eaf0bc7](https://linux-hardware.org/?probe=6d4eaf0bc7) | Apr 01, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [1d1e0bf9da](https://linux-hardware.org/?probe=1d1e0bf9da) | Apr 01, 2024 |
| Acer          | Aspire V3-331               | Notebook    | [0b74c17835](https://linux-hardware.org/?probe=0b74c17835) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0bd97f775d](https://linux-hardware.org/?probe=0bd97f775d) | Apr 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d952efad38](https://linux-hardware.org/?probe=d952efad38) | Apr 01, 2024 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [fd422008e5](https://linux-hardware.org/?probe=fd422008e5) | Mar 26, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [233178d530](https://linux-hardware.org/?probe=233178d530) | Mar 25, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [052a56e30a](https://linux-hardware.org/?probe=052a56e30a) | Mar 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [eb3211feaf](https://linux-hardware.org/?probe=eb3211feaf) | Mar 20, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [12f62966ac](https://linux-hardware.org/?probe=12f62966ac) | Mar 19, 2024 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [ad05f2ffb7](https://linux-hardware.org/?probe=ad05f2ffb7) | Mar 18, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [0e826ebda8](https://linux-hardware.org/?probe=0e826ebda8) | Mar 17, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d61cccde04](https://linux-hardware.org/?probe=d61cccde04) | Mar 17, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [aeb84570e9](https://linux-hardware.org/?probe=aeb84570e9) | Mar 17, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [aaab952c4c](https://linux-hardware.org/?probe=aaab952c4c) | Mar 14, 2024 |
| HP            | Pavilion dm3                | Notebook    | [2ae7a34348](https://linux-hardware.org/?probe=2ae7a34348) | Mar 13, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [59f5c0bcab](https://linux-hardware.org/?probe=59f5c0bcab) | Mar 10, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [d9046242c5](https://linux-hardware.org/?probe=d9046242c5) | Mar 10, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [4832f2d4f3](https://linux-hardware.org/?probe=4832f2d4f3) | Mar 09, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [3908a94356](https://linux-hardware.org/?probe=3908a94356) | Mar 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [829d14a64a](https://linux-hardware.org/?probe=829d14a64a) | Mar 08, 2024 |
| MSI           | B75MA-E33                   | Desktop     | [ef665444e1](https://linux-hardware.org/?probe=ef665444e1) | Mar 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [30b8f48fa3](https://linux-hardware.org/?probe=30b8f48fa3) | Mar 05, 2024 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [3fac30b86d](https://linux-hardware.org/?probe=3fac30b86d) | Mar 04, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [5e2bacbc0c](https://linux-hardware.org/?probe=5e2bacbc0c) | Mar 02, 2024 |
| HUAWEI        | HKD-WXX                     | Notebook    | [ec838546ec](https://linux-hardware.org/?probe=ec838546ec) | Feb 29, 2024 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [ae1b4fe578](https://linux-hardware.org/?probe=ae1b4fe578) | Feb 28, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [2c00c513d3](https://linux-hardware.org/?probe=2c00c513d3) | Feb 26, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [60b6b91372](https://linux-hardware.org/?probe=60b6b91372) | Feb 26, 2024 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [01587cc1ed](https://linux-hardware.org/?probe=01587cc1ed) | Feb 24, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [349dce666a](https://linux-hardware.org/?probe=349dce666a) | Feb 23, 2024 |
| Gigabyte      | Z390 UD                     | Desktop     | [81ce4601b2](https://linux-hardware.org/?probe=81ce4601b2) | Feb 21, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [03c4445d03](https://linux-hardware.org/?probe=03c4445d03) | Feb 20, 2024 |
| Lenovo        | Unknown                     | Notebook    | [a51f2dad65](https://linux-hardware.org/?probe=a51f2dad65) | Feb 15, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [31bafcc0cc](https://linux-hardware.org/?probe=31bafcc0cc) | Feb 13, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [1c432f8df1](https://linux-hardware.org/?probe=1c432f8df1) | Feb 11, 2024 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [b8338080c9](https://linux-hardware.org/?probe=b8338080c9) | Feb 08, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [a0c3cd5ffd](https://linux-hardware.org/?probe=a0c3cd5ffd) | Feb 04, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [f2003839e0](https://linux-hardware.org/?probe=f2003839e0) | Feb 01, 2024 |
| Huanan        | X99-8M-F V1.4               | Desktop     | [7625188b91](https://linux-hardware.org/?probe=7625188b91) | Jan 31, 2024 |
| MSI           | 970A-G46                    | Desktop     | [9a7594f5ae](https://linux-hardware.org/?probe=9a7594f5ae) | Jan 29, 2024 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [13d6b2dc0a](https://linux-hardware.org/?probe=13d6b2dc0a) | Jan 27, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [84264495d3](https://linux-hardware.org/?probe=84264495d3) | Jan 27, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f17f689f78](https://linux-hardware.org/?probe=f17f689f78) | Jan 27, 2024 |
| Huanan        | X99-8M-F V1.4               | Desktop     | [65388b76e1](https://linux-hardware.org/?probe=65388b76e1) | Jan 25, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [594794b707](https://linux-hardware.org/?probe=594794b707) | Jan 23, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [8d46c388c2](https://linux-hardware.org/?probe=8d46c388c2) | Jan 22, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [aca7a5c7c5](https://linux-hardware.org/?probe=aca7a5c7c5) | Jan 19, 2024 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [7b3ac920a3](https://linux-hardware.org/?probe=7b3ac920a3) | Jan 17, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [8906f7de53](https://linux-hardware.org/?probe=8906f7de53) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e2058a8b66](https://linux-hardware.org/?probe=e2058a8b66) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [301f2ec339](https://linux-hardware.org/?probe=301f2ec339) | Jan 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [84d67dfe96](https://linux-hardware.org/?probe=84d67dfe96) | Jan 12, 2024 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [9d75a6f8e8](https://linux-hardware.org/?probe=9d75a6f8e8) | Jan 08, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [c5f32d31a4](https://linux-hardware.org/?probe=c5f32d31a4) | Jan 06, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [9867b126a0](https://linux-hardware.org/?probe=9867b126a0) | Jan 05, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [84614ee22e](https://linux-hardware.org/?probe=84614ee22e) | Dec 28, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [5b0afba8bf](https://linux-hardware.org/?probe=5b0afba8bf) | Dec 27, 2023 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [99e618d817](https://linux-hardware.org/?probe=99e618d817) | Dec 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [a32866554a](https://linux-hardware.org/?probe=a32866554a) | Dec 26, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [97f532d3c8](https://linux-hardware.org/?probe=97f532d3c8) | Dec 26, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [a109a64bdd](https://linux-hardware.org/?probe=a109a64bdd) | Dec 24, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [dc5e6d8ad5](https://linux-hardware.org/?probe=dc5e6d8ad5) | Dec 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0121e6cb47](https://linux-hardware.org/?probe=0121e6cb47) | Dec 15, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [ee1bdd536f](https://linux-hardware.org/?probe=ee1bdd536f) | Dec 15, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9362181823](https://linux-hardware.org/?probe=9362181823) | Dec 14, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [cda15a71e9](https://linux-hardware.org/?probe=cda15a71e9) | Dec 14, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [f2efee9279](https://linux-hardware.org/?probe=f2efee9279) | Dec 13, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [0e23ff0a06](https://linux-hardware.org/?probe=0e23ff0a06) | Dec 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ec3c3d632c](https://linux-hardware.org/?probe=ec3c3d632c) | Dec 11, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [371f238337](https://linux-hardware.org/?probe=371f238337) | Dec 11, 2023 |
| MSI           | MS-7309                     | Desktop     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [73890cb8c3](https://linux-hardware.org/?probe=73890cb8c3) | Dec 05, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1c72ad4560](https://linux-hardware.org/?probe=1c72ad4560) | Dec 04, 2023 |
| ASRock        | B450M-HDV                   | Desktop     | [d59279f095](https://linux-hardware.org/?probe=d59279f095) | Dec 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [53fc7f6723](https://linux-hardware.org/?probe=53fc7f6723) | Nov 30, 2023 |
| eMachines     | eME440                      | Notebook    | [a622dddd66](https://linux-hardware.org/?probe=a622dddd66) | Nov 29, 2023 |
| Medion        | MS-7621                     | Desktop     | [18f32a871d](https://linux-hardware.org/?probe=18f32a871d) | Nov 28, 2023 |
| Dell          | Precision M4500             | Notebook    | [044aca6d38](https://linux-hardware.org/?probe=044aca6d38) | Nov 27, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [aa2febcb00](https://linux-hardware.org/?probe=aa2febcb00) | Nov 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [7a52012e4f](https://linux-hardware.org/?probe=7a52012e4f) | Nov 23, 2023 |
| Purism        | Librem 13 v4                | Notebook    | [0fdc9f6ef8](https://linux-hardware.org/?probe=0fdc9f6ef8) | Nov 23, 2023 |
| Purism        | Librem 13 v4                | Notebook    | [83c0da5aab](https://linux-hardware.org/?probe=83c0da5aab) | Nov 23, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [a286df39d9](https://linux-hardware.org/?probe=a286df39d9) | Nov 20, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [d300ce9afc](https://linux-hardware.org/?probe=d300ce9afc) | Nov 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [666f76f4e9](https://linux-hardware.org/?probe=666f76f4e9) | Nov 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [827e0f3b54](https://linux-hardware.org/?probe=827e0f3b54) | Nov 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [8e6ebc6d70](https://linux-hardware.org/?probe=8e6ebc6d70) | Nov 15, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3f0b4a0bfe](https://linux-hardware.org/?probe=3f0b4a0bfe) | Nov 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cdc5e8d8dc](https://linux-hardware.org/?probe=cdc5e8d8dc) | Nov 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b740ed00c5](https://linux-hardware.org/?probe=b740ed00c5) | Nov 15, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [4029b9094e](https://linux-hardware.org/?probe=4029b9094e) | Nov 15, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Toshiba       | Satellite C55t-A            | Notebook    | [22d791cf19](https://linux-hardware.org/?probe=22d791cf19) | Nov 12, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [8f08acd434](https://linux-hardware.org/?probe=8f08acd434) | Nov 12, 2023 |
| ASUSTek       | M5A87                       | Desktop     | [40a4f6c6f0](https://linux-hardware.org/?probe=40a4f6c6f0) | Nov 11, 2023 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | Notebook    | [99fde80a79](https://linux-hardware.org/?probe=99fde80a79) | Nov 11, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e528ff720f](https://linux-hardware.org/?probe=e528ff720f) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [e736653169](https://linux-hardware.org/?probe=e736653169) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| HP            | 655                         | Notebook    | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [c950f24711](https://linux-hardware.org/?probe=c950f24711) | Nov 01, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [87ec116ea6](https://linux-hardware.org/?probe=87ec116ea6) | Nov 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [babfdba8f2](https://linux-hardware.org/?probe=babfdba8f2) | Oct 30, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [102b9b2a5b](https://linux-hardware.org/?probe=102b9b2a5b) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [d8abffeee6](https://linux-hardware.org/?probe=d8abffeee6) | Oct 18, 2023 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [c593fd76c4](https://linux-hardware.org/?probe=c593fd76c4) | Oct 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [89b9e4e457](https://linux-hardware.org/?probe=89b9e4e457) | Oct 10, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [21bc791bbd](https://linux-hardware.org/?probe=21bc791bbd) | Oct 10, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [10baa7a046](https://linux-hardware.org/?probe=10baa7a046) | Oct 06, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4f7948d877](https://linux-hardware.org/?probe=4f7948d877) | Oct 02, 2023 |
| Lenovo        | ThinkCentre M57 6075Y3W     | Desktop     | [8e39080ed3](https://linux-hardware.org/?probe=8e39080ed3) | Sep 28, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [060deb4c88](https://linux-hardware.org/?probe=060deb4c88) | Sep 26, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [1939307392](https://linux-hardware.org/?probe=1939307392) | Sep 25, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [1752297c85](https://linux-hardware.org/?probe=1752297c85) | Sep 22, 2023 |
| Biostar       | A68N-2100                   | Desktop     | [c035c2e73b](https://linux-hardware.org/?probe=c035c2e73b) | Sep 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [b8821b0cf1](https://linux-hardware.org/?probe=b8821b0cf1) | Sep 21, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [d8f04cd109](https://linux-hardware.org/?probe=d8f04cd109) | Sep 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [1929f30e86](https://linux-hardware.org/?probe=1929f30e86) | Sep 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d66a3d9329](https://linux-hardware.org/?probe=d66a3d9329) | Sep 18, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [5cf28fa81f](https://linux-hardware.org/?probe=5cf28fa81f) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [2085bafc62](https://linux-hardware.org/?probe=2085bafc62) | Sep 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| ASUSTek       | K54C                        | Notebook    | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS5260... | Notebook    | [43ff008024](https://linux-hardware.org/?probe=43ff008024) | Sep 14, 2023 |
| Dell          | Latitude E7250              | Notebook    | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [740fa4fb21](https://linux-hardware.org/?probe=740fa4fb21) | Sep 11, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [3b97b2d662](https://linux-hardware.org/?probe=3b97b2d662) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [04d60f1b2d](https://linux-hardware.org/?probe=04d60f1b2d) | Sep 06, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [d66af7c01e](https://linux-hardware.org/?probe=d66af7c01e) | Sep 05, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b87e106b6b](https://linux-hardware.org/?probe=b87e106b6b) | Sep 04, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [60d302fc0f](https://linux-hardware.org/?probe=60d302fc0f) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [8f29742c47](https://linux-hardware.org/?probe=8f29742c47) | Sep 02, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [43e624c0b4](https://linux-hardware.org/?probe=43e624c0b4) | Aug 30, 2023 |
| HP            | EliteBook 835 G7 Noteboo... | Notebook    | [fec29a37b2](https://linux-hardware.org/?probe=fec29a37b2) | Aug 27, 2023 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [5de726089b](https://linux-hardware.org/?probe=5de726089b) | Aug 26, 2023 |
| HP            | 1497                        | Desktop     | [32a8075d02](https://linux-hardware.org/?probe=32a8075d02) | Aug 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d648900305](https://linux-hardware.org/?probe=d648900305) | Aug 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0ec42f4555](https://linux-hardware.org/?probe=0ec42f4555) | Aug 24, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [88533268cf](https://linux-hardware.org/?probe=88533268cf) | Aug 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e0d5cce513](https://linux-hardware.org/?probe=e0d5cce513) | Aug 23, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [2c42cc3ebb](https://linux-hardware.org/?probe=2c42cc3ebb) | Aug 18, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | Notebook    | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [fb2095ddea](https://linux-hardware.org/?probe=fb2095ddea) | Aug 17, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [dfdde7225d](https://linux-hardware.org/?probe=dfdde7225d) | Aug 13, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [618857a4ae](https://linux-hardware.org/?probe=618857a4ae) | Aug 12, 2023 |
| Lenovo        | ThinkPad Edge 03193VG       | Notebook    | [abb370836a](https://linux-hardware.org/?probe=abb370836a) | Aug 10, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [ea34946fbd](https://linux-hardware.org/?probe=ea34946fbd) | Aug 09, 2023 |
| Alienware     | 14                          | Notebook    | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| Dell          | Latitude E7450              | Notebook    | [a426887b24](https://linux-hardware.org/?probe=a426887b24) | Aug 08, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [b2177d3c55](https://linux-hardware.org/?probe=b2177d3c55) | Aug 06, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [21063bc0bb](https://linux-hardware.org/?probe=21063bc0bb) | Aug 05, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [573e7f6ad0](https://linux-hardware.org/?probe=573e7f6ad0) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [437e15fae7](https://linux-hardware.org/?probe=437e15fae7) | Aug 03, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [f09853c0ed](https://linux-hardware.org/?probe=f09853c0ed) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [1cf260b959](https://linux-hardware.org/?probe=1cf260b959) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [6c0a6fff0a](https://linux-hardware.org/?probe=6c0a6fff0a) | Jul 31, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [875ac8e861](https://linux-hardware.org/?probe=875ac8e861) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [14dbf1a55b](https://linux-hardware.org/?probe=14dbf1a55b) | Jul 26, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [10db13c772](https://linux-hardware.org/?probe=10db13c772) | Jul 26, 2023 |
| Synology      | DS923+                      | Notebook    | [4e023a4222](https://linux-hardware.org/?probe=4e023a4222) | Jul 21, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b1ceb90106](https://linux-hardware.org/?probe=b1ceb90106) | Jul 12, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | Notebook    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| HP            | 8918                        | Desktop     | [af366ea249](https://linux-hardware.org/?probe=af366ea249) | Jul 07, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [12561e59a4](https://linux-hardware.org/?probe=12561e59a4) | Jul 07, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [48526cd359](https://linux-hardware.org/?probe=48526cd359) | Jul 07, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [b6be2d7f9f](https://linux-hardware.org/?probe=b6be2d7f9f) | Jun 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ec846958c9](https://linux-hardware.org/?probe=ec846958c9) | Jun 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [310342d290](https://linux-hardware.org/?probe=310342d290) | Jun 30, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [c269ef3dd7](https://linux-hardware.org/?probe=c269ef3dd7) | Jun 24, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [67f3cd78e2](https://linux-hardware.org/?probe=67f3cd78e2) | Jun 22, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8550e224ec](https://linux-hardware.org/?probe=8550e224ec) | Jun 20, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [eeb6dfe9be](https://linux-hardware.org/?probe=eeb6dfe9be) | Jun 18, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [a1eac5da7c](https://linux-hardware.org/?probe=a1eac5da7c) | Jun 18, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c3ec3eaa27](https://linux-hardware.org/?probe=c3ec3eaa27) | Jun 13, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [45094360f2](https://linux-hardware.org/?probe=45094360f2) | Jun 11, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [57fcd66521](https://linux-hardware.org/?probe=57fcd66521) | Jun 11, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| Acer          | Predator G3600              | Desktop     | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X201 3680Y4F       | Notebook    | [7823148e7d](https://linux-hardware.org/?probe=7823148e7d) | Jun 07, 2023 |
| Acer          | Aspire A315-31              | Notebook    | [d5da1b4b30](https://linux-hardware.org/?probe=d5da1b4b30) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [e3fd506f5e](https://linux-hardware.org/?probe=e3fd506f5e) | Jun 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [8505864d45](https://linux-hardware.org/?probe=8505864d45) | May 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| Dell          | Latitude 5440               | Notebook    | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [b5fd752412](https://linux-hardware.org/?probe=b5fd752412) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [1498cf091b](https://linux-hardware.org/?probe=1498cf091b) | May 26, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [46a6988c7a](https://linux-hardware.org/?probe=46a6988c7a) | May 25, 2023 |
| Dell          | Latitude 5440               | Notebook    | [5a27bd40e7](https://linux-hardware.org/?probe=5a27bd40e7) | May 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [a36e076c17](https://linux-hardware.org/?probe=a36e076c17) | May 23, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [39bb190ac7](https://linux-hardware.org/?probe=39bb190ac7) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [59ede76205](https://linux-hardware.org/?probe=59ede76205) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [a5c1b4eecd](https://linux-hardware.org/?probe=a5c1b4eecd) | May 22, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [e4adcd71f1](https://linux-hardware.org/?probe=e4adcd71f1) | May 21, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [09f37f2540](https://linux-hardware.org/?probe=09f37f2540) | May 21, 2023 |
| ASUSTek       | X540SC                      | Notebook    | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [bdd393edd7](https://linux-hardware.org/?probe=bdd393edd7) | May 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [596f37cc9d](https://linux-hardware.org/?probe=596f37cc9d) | May 21, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [386869568d](https://linux-hardware.org/?probe=386869568d) | May 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [467ffa6773](https://linux-hardware.org/?probe=467ffa6773) | May 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [146d4e4aff](https://linux-hardware.org/?probe=146d4e4aff) | May 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [47430a463a](https://linux-hardware.org/?probe=47430a463a) | May 15, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [e50adfaff9](https://linux-hardware.org/?probe=e50adfaff9) | May 15, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b43ec1363a](https://linux-hardware.org/?probe=b43ec1363a) | May 14, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b80a472c1a](https://linux-hardware.org/?probe=b80a472c1a) | May 14, 2023 |
| Dell          | Precision M4500             | Notebook    | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [e826ca7941](https://linux-hardware.org/?probe=e826ca7941) | May 11, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [d01779a93b](https://linux-hardware.org/?probe=d01779a93b) | May 09, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [33cc483e77](https://linux-hardware.org/?probe=33cc483e77) | May 09, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [b1fb1bdecf](https://linux-hardware.org/?probe=b1fb1bdecf) | May 06, 2023 |
| ASUSTek       | A88X-PRO                    | Desktop     | [faabff7b74](https://linux-hardware.org/?probe=faabff7b74) | May 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3a7e1532da](https://linux-hardware.org/?probe=3a7e1532da) | May 03, 2023 |
| Intel         | NUC13SBBi5 M89887-303       | Mini pc     | [77577a0447](https://linux-hardware.org/?probe=77577a0447) | May 02, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [d0d3458299](https://linux-hardware.org/?probe=d0d3458299) | Apr 29, 2023 |
| MSI           | MS-9661 SA                  | Server      | [1888fa6df7](https://linux-hardware.org/?probe=1888fa6df7) | Apr 29, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| ASUSTek       | P5B-MX                      | Desktop     | [3770e032b4](https://linux-hardware.org/?probe=3770e032b4) | Apr 21, 2023 |
| ASUSTek       | PN62S                       | Mini pc     | [8b7d9ca6fd](https://linux-hardware.org/?probe=8b7d9ca6fd) | Apr 21, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [167000be9b](https://linux-hardware.org/?probe=167000be9b) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [258a5bb354](https://linux-hardware.org/?probe=258a5bb354) | Apr 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [ddf5053ffa](https://linux-hardware.org/?probe=ddf5053ffa) | Apr 18, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [34514d69bd](https://linux-hardware.org/?probe=34514d69bd) | Apr 15, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6ac890debf](https://linux-hardware.org/?probe=6ac890debf) | Apr 12, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| ASUSTek       | M2N4-SLI                    | Desktop     | [870bba0c09](https://linux-hardware.org/?probe=870bba0c09) | Apr 03, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b4a624599e](https://linux-hardware.org/?probe=b4a624599e) | Apr 01, 2023 |
| MSI           | H61M-P20                    | Desktop     | [18409d7178](https://linux-hardware.org/?probe=18409d7178) | Mar 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8d0ef2d912](https://linux-hardware.org/?probe=8d0ef2d912) | Mar 26, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [5dfef9c764](https://linux-hardware.org/?probe=5dfef9c764) | Mar 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [6296457407](https://linux-hardware.org/?probe=6296457407) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [f5bd764775](https://linux-hardware.org/?probe=f5bd764775) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [c356d98a54](https://linux-hardware.org/?probe=c356d98a54) | Mar 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b48ee031b3](https://linux-hardware.org/?probe=b48ee031b3) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| Medion        | MS-7800                     | Desktop     | [fcd708adc0](https://linux-hardware.org/?probe=fcd708adc0) | Mar 08, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [46a16afb4b](https://linux-hardware.org/?probe=46a16afb4b) | Mar 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25e3173dc4](https://linux-hardware.org/?probe=25e3173dc4) | Mar 01, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e8e3f57eef](https://linux-hardware.org/?probe=e8e3f57eef) | Feb 26, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [a206715ec6](https://linux-hardware.org/?probe=a206715ec6) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d227d114f4](https://linux-hardware.org/?probe=d227d114f4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T495s 20QJS0GG0... | Notebook    | [6186149a54](https://linux-hardware.org/?probe=6186149a54) | Feb 24, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9171567db4](https://linux-hardware.org/?probe=9171567db4) | Feb 24, 2023 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [2beb8f24f3](https://linux-hardware.org/?probe=2beb8f24f3) | Feb 20, 2023 |
| Lenovo        | 3138 NO DPK                 | Desktop     | [992af7508c](https://linux-hardware.org/?probe=992af7508c) | Feb 20, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [1eb4b696ac](https://linux-hardware.org/?probe=1eb4b696ac) | Feb 18, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [5dde619cce](https://linux-hardware.org/?probe=5dde619cce) | Feb 18, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [eb1d201d1c](https://linux-hardware.org/?probe=eb1d201d1c) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [18f60be847](https://linux-hardware.org/?probe=18f60be847) | Feb 13, 2023 |
| Biostar       | A68N-2100                   | Desktop     | [a0ebf68180](https://linux-hardware.org/?probe=a0ebf68180) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f48f01414c](https://linux-hardware.org/?probe=f48f01414c) | Feb 08, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [310425ba43](https://linux-hardware.org/?probe=310425ba43) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| TWC           | Unknown                     | Notebook    | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [fcd4f7a01a](https://linux-hardware.org/?probe=fcd4f7a01a) | Feb 06, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d389ca29d1](https://linux-hardware.org/?probe=d389ca29d1) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [8f7c4b8632](https://linux-hardware.org/?probe=8f7c4b8632) | Feb 05, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| NCR           | Pocono                      | Desktop     | [1a1c878e10](https://linux-hardware.org/?probe=1a1c878e10) | Jan 31, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [7fb4a85c09](https://linux-hardware.org/?probe=7fb4a85c09) | Jan 30, 2023 |
| ASUSTek       | K55A                        | Notebook    | [e3088b45e1](https://linux-hardware.org/?probe=e3088b45e1) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| Toshiba       | Satellite C870-17H          | Notebook    | [8fe4718795](https://linux-hardware.org/?probe=8fe4718795) | Jan 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [d825caa85e](https://linux-hardware.org/?probe=d825caa85e) | Jan 27, 2023 |
| Dell          | Precision 3550              | Notebook    | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [ef4e303beb](https://linux-hardware.org/?probe=ef4e303beb) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b20da22e41](https://linux-hardware.org/?probe=b20da22e41) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [2194886c52](https://linux-hardware.org/?probe=2194886c52) | Jan 23, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [1bf0fe4342](https://linux-hardware.org/?probe=1bf0fe4342) | Jan 22, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [2375f407c7](https://linux-hardware.org/?probe=2375f407c7) | Jan 22, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [770d2f3bb4](https://linux-hardware.org/?probe=770d2f3bb4) | Jan 22, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9db2cc3370](https://linux-hardware.org/?probe=9db2cc3370) | Jan 21, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bc8b02043e](https://linux-hardware.org/?probe=bc8b02043e) | Jan 20, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| ASUSTek       | X201EP                      | Notebook    | [def6593908](https://linux-hardware.org/?probe=def6593908) | Jan 16, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c5d6c74b79](https://linux-hardware.org/?probe=c5d6c74b79) | Jan 15, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9738e56558](https://linux-hardware.org/?probe=9738e56558) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [295ef21c8b](https://linux-hardware.org/?probe=295ef21c8b) | Jan 15, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [61a73fa103](https://linux-hardware.org/?probe=61a73fa103) | Jan 12, 2023 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | Notebook    | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | Notebook    | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [234580243d](https://linux-hardware.org/?probe=234580243d) | Jan 08, 2023 |
| Lenovo        | ThinkPad W500 4061WFA       | Notebook    | [4850dba7c8](https://linux-hardware.org/?probe=4850dba7c8) | Jan 08, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [f84fb1bab3](https://linux-hardware.org/?probe=f84fb1bab3) | Jan 08, 2023 |
| Medion        | MS-7621                     | Desktop     | [da2d61d475](https://linux-hardware.org/?probe=da2d61d475) | Jan 07, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [db00fde012](https://linux-hardware.org/?probe=db00fde012) | Jan 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [87392c38d4](https://linux-hardware.org/?probe=87392c38d4) | Jan 06, 2023 |
| eMachines     | E725                        | Notebook    | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [4e71ce9f1c](https://linux-hardware.org/?probe=4e71ce9f1c) | Jan 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [2ffb7cc11b](https://linux-hardware.org/?probe=2ffb7cc11b) | Jan 05, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [77abcf7aee](https://linux-hardware.org/?probe=77abcf7aee) | Jan 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b4511daea8](https://linux-hardware.org/?probe=b4511daea8) | Dec 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [05209e0503](https://linux-hardware.org/?probe=05209e0503) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e90b9703e5](https://linux-hardware.org/?probe=e90b9703e5) | Dec 28, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [aff2b93aa5](https://linux-hardware.org/?probe=aff2b93aa5) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f51a366bc2](https://linux-hardware.org/?probe=f51a366bc2) | Dec 26, 2022 |
| NCR           | Pocono                      | Desktop     | [d50ad710fb](https://linux-hardware.org/?probe=d50ad710fb) | Dec 26, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b30f8a638b](https://linux-hardware.org/?probe=b30f8a638b) | Dec 26, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [500abd4186](https://linux-hardware.org/?probe=500abd4186) | Dec 25, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [73c8ec2eb1](https://linux-hardware.org/?probe=73c8ec2eb1) | Dec 22, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [46e5d4fe56](https://linux-hardware.org/?probe=46e5d4fe56) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [caaddcd344](https://linux-hardware.org/?probe=caaddcd344) | Dec 18, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [45eafa4ade](https://linux-hardware.org/?probe=45eafa4ade) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [e8b0c03cb9](https://linux-hardware.org/?probe=e8b0c03cb9) | Dec 15, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f53a29ef5e](https://linux-hardware.org/?probe=f53a29ef5e) | Dec 11, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [1fb1bc61c1](https://linux-hardware.org/?probe=1fb1bc61c1) | Dec 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [4cfe094684](https://linux-hardware.org/?probe=4cfe094684) | Dec 10, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [2e9e8cd930](https://linux-hardware.org/?probe=2e9e8cd930) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [def749869a](https://linux-hardware.org/?probe=def749869a) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9789efe96c](https://linux-hardware.org/?probe=9789efe96c) | Dec 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5a24a1a2](https://linux-hardware.org/?probe=9b5a24a1a2) | Dec 07, 2022 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [a0864dbdc7](https://linux-hardware.org/?probe=a0864dbdc7) | Dec 06, 2022 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ecb93d2406](https://linux-hardware.org/?probe=ecb93d2406) | Dec 06, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3fb8809375](https://linux-hardware.org/?probe=3fb8809375) | Dec 06, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [6b5fd6a48c](https://linux-hardware.org/?probe=6b5fd6a48c) | Dec 05, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [dc937d6d65](https://linux-hardware.org/?probe=dc937d6d65) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a15aba2f94](https://linux-hardware.org/?probe=a15aba2f94) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9e22aec274](https://linux-hardware.org/?probe=9e22aec274) | Dec 03, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [c6bca6efa8](https://linux-hardware.org/?probe=c6bca6efa8) | Dec 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [660b9b7529](https://linux-hardware.org/?probe=660b9b7529) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9d7fdf83b6](https://linux-hardware.org/?probe=9d7fdf83b6) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [e4c533a89b](https://linux-hardware.org/?probe=e4c533a89b) | Nov 28, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [944ade9560](https://linux-hardware.org/?probe=944ade9560) | Nov 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [37b51f19ef](https://linux-hardware.org/?probe=37b51f19ef) | Nov 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34601... | Notebook    | [ed678da106](https://linux-hardware.org/?probe=ed678da106) | Nov 26, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [a28ef28876](https://linux-hardware.org/?probe=a28ef28876) | Nov 20, 2022 |
| HP            | Pavilion dv7                | Notebook    | [839266e415](https://linux-hardware.org/?probe=839266e415) | Nov 19, 2022 |
| HP            | Notebook                    | Notebook    | [2721a90e68](https://linux-hardware.org/?probe=2721a90e68) | Nov 19, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [c3fde80859](https://linux-hardware.org/?probe=c3fde80859) | Nov 14, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [c8e8add499](https://linux-hardware.org/?probe=c8e8add499) | Nov 14, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| HP            | 212B                        | Desktop     | [d2ccd70744](https://linux-hardware.org/?probe=d2ccd70744) | Nov 05, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [80e34bf59e](https://linux-hardware.org/?probe=80e34bf59e) | Nov 05, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [fd5bbb3392](https://linux-hardware.org/?probe=fd5bbb3392) | Nov 05, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [3d642bde4b](https://linux-hardware.org/?probe=3d642bde4b) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| ASUSTek       | X751LB                      | Notebook    | [b9f1ea7699](https://linux-hardware.org/?probe=b9f1ea7699) | Nov 04, 2022 |
| ASUSTek       | X751LB                      | Notebook    | [e7334f33eb](https://linux-hardware.org/?probe=e7334f33eb) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [990a38ea87](https://linux-hardware.org/?probe=990a38ea87) | Nov 01, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [7290b40608](https://linux-hardware.org/?probe=7290b40608) | Oct 27, 2022 |
| MSI           | MS-7309                     | Desktop     | [fe0fae3528](https://linux-hardware.org/?probe=fe0fae3528) | Oct 26, 2022 |
| MSI           | MS-7309                     | Desktop     | [2db582d6dd](https://linux-hardware.org/?probe=2db582d6dd) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [491477817a](https://linux-hardware.org/?probe=491477817a) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [fbd1924bea](https://linux-hardware.org/?probe=fbd1924bea) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| MSI           | H61M-P20                    | Desktop     | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [341d4b53b1](https://linux-hardware.org/?probe=341d4b53b1) | Oct 20, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [6941ece1e9](https://linux-hardware.org/?probe=6941ece1e9) | Oct 18, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f62a50602b](https://linux-hardware.org/?probe=f62a50602b) | Oct 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [b364048b01](https://linux-hardware.org/?probe=b364048b01) | Oct 17, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [c5f81be3fd](https://linux-hardware.org/?probe=c5f81be3fd) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | Notebook    | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Dell          | Precision M4800             | Notebook    | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [24c93934d4](https://linux-hardware.org/?probe=24c93934d4) | Sep 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [29f2bd4304](https://linux-hardware.org/?probe=29f2bd4304) | Sep 25, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [675cc67ba8](https://linux-hardware.org/?probe=675cc67ba8) | Sep 25, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [ffedff132b](https://linux-hardware.org/?probe=ffedff132b) | Sep 25, 2022 |
| Dell          | Latitude 5285               | Tablet      | [1717754347](https://linux-hardware.org/?probe=1717754347) | Sep 24, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [0a4522a059](https://linux-hardware.org/?probe=0a4522a059) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [9fbedd972e](https://linux-hardware.org/?probe=9fbedd972e) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [815fe42722](https://linux-hardware.org/?probe=815fe42722) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [641ad27b06](https://linux-hardware.org/?probe=641ad27b06) | Sep 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [015c8dd353](https://linux-hardware.org/?probe=015c8dd353) | Sep 20, 2022 |
| HP            | ProBook 6560b               | Notebook    | [743f401352](https://linux-hardware.org/?probe=743f401352) | Sep 20, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [4eea730197](https://linux-hardware.org/?probe=4eea730197) | Sep 18, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9e2454a5ab](https://linux-hardware.org/?probe=9e2454a5ab) | Sep 18, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [96564b490b](https://linux-hardware.org/?probe=96564b490b) | Sep 15, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [846849e46c](https://linux-hardware.org/?probe=846849e46c) | Sep 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [131f5046db](https://linux-hardware.org/?probe=131f5046db) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| Foxconn       | 2AA9                        | Desktop     | [b671b09c1a](https://linux-hardware.org/?probe=b671b09c1a) | Sep 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cb47ce6e71](https://linux-hardware.org/?probe=cb47ce6e71) | Sep 09, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [a355222b61](https://linux-hardware.org/?probe=a355222b61) | Sep 07, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [fd6ab0c9e5](https://linux-hardware.org/?probe=fd6ab0c9e5) | Sep 07, 2022 |
| HP            | 304Bh                       | Desktop     | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [beec88b95c](https://linux-hardware.org/?probe=beec88b95c) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [4c90105342](https://linux-hardware.org/?probe=4c90105342) | Sep 01, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [76046f5112](https://linux-hardware.org/?probe=76046f5112) | Aug 30, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [95c8025613](https://linux-hardware.org/?probe=95c8025613) | Aug 30, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [818b7e0b19](https://linux-hardware.org/?probe=818b7e0b19) | Aug 27, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [df8598d6f6](https://linux-hardware.org/?probe=df8598d6f6) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [f945f778b2](https://linux-hardware.org/?probe=f945f778b2) | Aug 26, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6efab17b42](https://linux-hardware.org/?probe=6efab17b42) | Aug 25, 2022 |
| HP            | 0980h                       | Desktop     | [1b4bdc2dd3](https://linux-hardware.org/?probe=1b4bdc2dd3) | Aug 25, 2022 |
| HP            | 0980h                       | Desktop     | [28433ca1db](https://linux-hardware.org/?probe=28433ca1db) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [255a1cdf9a](https://linux-hardware.org/?probe=255a1cdf9a) | Aug 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [141267e725](https://linux-hardware.org/?probe=141267e725) | Aug 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2a9d448350](https://linux-hardware.org/?probe=2a9d448350) | Aug 23, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f7b5d18cbe](https://linux-hardware.org/?probe=f7b5d18cbe) | Aug 23, 2022 |
| HP            | 304Bh                       | Desktop     | [1e3d59e493](https://linux-hardware.org/?probe=1e3d59e493) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | Notebook    | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [83bdc1ea13](https://linux-hardware.org/?probe=83bdc1ea13) | Aug 19, 2022 |
| ASUSTek       | K54C                        | Notebook    | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [ab09f2f44b](https://linux-hardware.org/?probe=ab09f2f44b) | Aug 11, 2022 |
| Sony          | VPCZ12M9E                   | Notebook    | [75f1c2f156](https://linux-hardware.org/?probe=75f1c2f156) | Aug 02, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [bbeebdd421](https://linux-hardware.org/?probe=bbeebdd421) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Sony          | VPCEE23FX                   | Notebook    | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b121274e4f](https://linux-hardware.org/?probe=b121274e4f) | Jul 23, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [4bae560f04](https://linux-hardware.org/?probe=4bae560f04) | Jul 22, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [bece300d92](https://linux-hardware.org/?probe=bece300d92) | Jul 20, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| HP            | Compaq nx7300 (RU373ES#A... | Notebook    | [3004f1d2b9](https://linux-hardware.org/?probe=3004f1d2b9) | Jul 16, 2022 |
| Gigabyte      | AERO 17 KC                  | Notebook    | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [0c4f85c70e](https://linux-hardware.org/?probe=0c4f85c70e) | Jul 13, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | Notebook    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | Notebook    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c01cf9f7fc](https://linux-hardware.org/?probe=c01cf9f7fc) | Jul 05, 2022 |
| HP            | 250 G4                      | Notebook    | [3d629889b2](https://linux-hardware.org/?probe=3d629889b2) | Jul 05, 2022 |
| HP            | 250 G4                      | Notebook    | [e19f8a8485](https://linux-hardware.org/?probe=e19f8a8485) | Jul 05, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [be7fd47ea1](https://linux-hardware.org/?probe=be7fd47ea1) | Jul 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6d3f245289](https://linux-hardware.org/?probe=6d3f245289) | Jul 04, 2022 |
| Timi          | TM1613                      | Notebook    | [38d9919cfd](https://linux-hardware.org/?probe=38d9919cfd) | Jul 03, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| MSI           | H61M-P20                    | Desktop     | [c86cefdaa6](https://linux-hardware.org/?probe=c86cefdaa6) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0db95d58d4](https://linux-hardware.org/?probe=0db95d58d4) | Jun 24, 2022 |
| Lenovo        | ThinkPad T560 20FJS1KE00    | Notebook    | [f0cd91b4d2](https://linux-hardware.org/?probe=f0cd91b4d2) | Jun 21, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [06c982ad14](https://linux-hardware.org/?probe=06c982ad14) | Jun 16, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | Notebook    | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [74d3cc8728](https://linux-hardware.org/?probe=74d3cc8728) | Jun 14, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [c498f6f3bd](https://linux-hardware.org/?probe=c498f6f3bd) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [12471a5b0e](https://linux-hardware.org/?probe=12471a5b0e) | Jun 10, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [7fa5d36a45](https://linux-hardware.org/?probe=7fa5d36a45) | Jun 04, 2022 |
| Gigabyte      | GA-H310TN-R2                | Desktop     | [2fecd41e0b](https://linux-hardware.org/?probe=2fecd41e0b) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ef73457d51](https://linux-hardware.org/?probe=ef73457d51) | May 31, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [2dba625d78](https://linux-hardware.org/?probe=2dba625d78) | May 28, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [ea1d17f234](https://linux-hardware.org/?probe=ea1d17f234) | May 27, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [e1efc36540](https://linux-hardware.org/?probe=e1efc36540) | May 27, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | Notebook    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | Notebook    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [da35dd6295](https://linux-hardware.org/?probe=da35dd6295) | May 22, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [1b7bdd0f65](https://linux-hardware.org/?probe=1b7bdd0f65) | May 21, 2022 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [2fdd079ebc](https://linux-hardware.org/?probe=2fdd079ebc) | May 21, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | Notebook    | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2f12c77058](https://linux-hardware.org/?probe=2f12c77058) | May 16, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [7166bb5a53](https://linux-hardware.org/?probe=7166bb5a53) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f6262ce7f2](https://linux-hardware.org/?probe=f6262ce7f2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [2c2a15aab2](https://linux-hardware.org/?probe=2c2a15aab2) | May 12, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [bc84347b65](https://linux-hardware.org/?probe=bc84347b65) | May 11, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d18df271fd](https://linux-hardware.org/?probe=d18df271fd) | May 09, 2022 |
| Medion        | X781X/X782X                 | Notebook    | [fbe630f91c](https://linux-hardware.org/?probe=fbe630f91c) | May 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [a716192ef4](https://linux-hardware.org/?probe=a716192ef4) | May 06, 2022 |
| Lenovo        | IdeaPad Z370                | Notebook    | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| Lenovo        | SHARKBAY NO DPK             | All in one  | [e23317d53c](https://linux-hardware.org/?probe=e23317d53c) | May 01, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [81d7fd8d2e](https://linux-hardware.org/?probe=81d7fd8d2e) | Apr 30, 2022 |
| HP            | 3396                        | Desktop     | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f4f8108d1e](https://linux-hardware.org/?probe=f4f8108d1e) | Apr 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [4e8f764b38](https://linux-hardware.org/?probe=4e8f764b38) | Apr 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6e1760aed0](https://linux-hardware.org/?probe=6e1760aed0) | Apr 17, 2022 |
| ASUSTek       | P7H55                       | Desktop     | [d619f35fb8](https://linux-hardware.org/?probe=d619f35fb8) | Apr 16, 2022 |
| HP            | 845A                        | Desktop     | [cc8c320581](https://linux-hardware.org/?probe=cc8c320581) | Apr 16, 2022 |
| ASUSTek       | B150-PRO                    | Desktop     | [1ebe5f0e99](https://linux-hardware.org/?probe=1ebe5f0e99) | Apr 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [b888c78ed6](https://linux-hardware.org/?probe=b888c78ed6) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [45dad76f04](https://linux-hardware.org/?probe=45dad76f04) | Apr 12, 2022 |
| HP            | Notebook                    | Notebook    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [0dbb9e7eb0](https://linux-hardware.org/?probe=0dbb9e7eb0) | Apr 09, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [ef7f30cc40](https://linux-hardware.org/?probe=ef7f30cc40) | Apr 07, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [55568ec828](https://linux-hardware.org/?probe=55568ec828) | Apr 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [950a436db3](https://linux-hardware.org/?probe=950a436db3) | Apr 06, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [55eda86e20](https://linux-hardware.org/?probe=55eda86e20) | Apr 05, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [906de71a65](https://linux-hardware.org/?probe=906de71a65) | Apr 02, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Lenovo        | SHARKBAY NO DPK             | All in one  | [7d0de80b18](https://linux-hardware.org/?probe=7d0de80b18) | Mar 29, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [8caaa96b19](https://linux-hardware.org/?probe=8caaa96b19) | Mar 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| HP            | 3398                        | Desktop     | [b84864ecc4](https://linux-hardware.org/?probe=b84864ecc4) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6a8c31fa33](https://linux-hardware.org/?probe=6a8c31fa33) | Mar 21, 2022 |
| HP            | 3032h                       | Desktop     | [e57d52908c](https://linux-hardware.org/?probe=e57d52908c) | Mar 21, 2022 |
| HP            | 3398                        | Desktop     | [5f018df1dd](https://linux-hardware.org/?probe=5f018df1dd) | Mar 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f55145f34a](https://linux-hardware.org/?probe=f55145f34a) | Mar 16, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [117ebec9fc](https://linux-hardware.org/?probe=117ebec9fc) | Mar 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f19c9ef173](https://linux-hardware.org/?probe=f19c9ef173) | Mar 14, 2022 |
| Lenovo        | SHARKBAY NO DPK             | All in one  | [951ea7a2b4](https://linux-hardware.org/?probe=951ea7a2b4) | Mar 11, 2022 |
| Toshiba       | Satellite C870-17H          | Notebook    | [0169bf05d7](https://linux-hardware.org/?probe=0169bf05d7) | Mar 10, 2022 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [9f17c99bb5](https://linux-hardware.org/?probe=9f17c99bb5) | Mar 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [723ab179b6](https://linux-hardware.org/?probe=723ab179b6) | Mar 06, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [4a1c505260](https://linux-hardware.org/?probe=4a1c505260) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2c44722344](https://linux-hardware.org/?probe=2c44722344) | Mar 03, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [69ec87e43a](https://linux-hardware.org/?probe=69ec87e43a) | Mar 02, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [9acf95b26b](https://linux-hardware.org/?probe=9acf95b26b) | Feb 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [03a49e64cf](https://linux-hardware.org/?probe=03a49e64cf) | Feb 28, 2022 |
| Gigabyte      | AERO 17 KC                  | Notebook    | [08b488b969](https://linux-hardware.org/?probe=08b488b969) | Feb 27, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [65b41a7a67](https://linux-hardware.org/?probe=65b41a7a67) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Latitude 7490               | Notebook    | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1f607a3c8c](https://linux-hardware.org/?probe=1f607a3c8c) | Feb 21, 2022 |
| Dell          | Inspiron 3581               | Notebook    | [0ae0e53b53](https://linux-hardware.org/?probe=0ae0e53b53) | Feb 20, 2022 |
| HP            | Notebook                    | Notebook    | [a1f9f76ed0](https://linux-hardware.org/?probe=a1f9f76ed0) | Feb 19, 2022 |
| Gigabyte      | MJPLNCB-00                  | Desktop     | [d9a5169bbc](https://linux-hardware.org/?probe=d9a5169bbc) | Feb 16, 2022 |
| MSI           | A55M-P33                    | Desktop     | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| Toshiba       | Satellite C55-A             | Notebook    | [19133950aa](https://linux-hardware.org/?probe=19133950aa) | Feb 15, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9055e23b83](https://linux-hardware.org/?probe=9055e23b83) | Feb 14, 2022 |
| ASUSTek       | X55A                        | Notebook    | [c6b17158ac](https://linux-hardware.org/?probe=c6b17158ac) | Feb 14, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [fc63d0ede8](https://linux-hardware.org/?probe=fc63d0ede8) | Feb 13, 2022 |
| MSI           | GF615M-P33 V2               | Desktop     | [b5bfcbf8dc](https://linux-hardware.org/?probe=b5bfcbf8dc) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [1eb72bde90](https://linux-hardware.org/?probe=1eb72bde90) | Feb 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d6c5c1a6d2](https://linux-hardware.org/?probe=d6c5c1a6d2) | Feb 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [a530f2976f](https://linux-hardware.org/?probe=a530f2976f) | Feb 10, 2022 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [5480f2aa6c](https://linux-hardware.org/?probe=5480f2aa6c) | Feb 10, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [b28eb819f0](https://linux-hardware.org/?probe=b28eb819f0) | Feb 09, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [1c829ba8dd](https://linux-hardware.org/?probe=1c829ba8dd) | Feb 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [379d3b37b1](https://linux-hardware.org/?probe=379d3b37b1) | Feb 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [80b24c2689](https://linux-hardware.org/?probe=80b24c2689) | Feb 03, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [d644756f37](https://linux-hardware.org/?probe=d644756f37) | Feb 03, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b5ae920f3b](https://linux-hardware.org/?probe=b5ae920f3b) | Feb 02, 2022 |
| BenQ          | Joybook Lite U121           | Notebook    | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [729abacd12](https://linux-hardware.org/?probe=729abacd12) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5e9f8a1c0d](https://linux-hardware.org/?probe=5e9f8a1c0d) | Jan 29, 2022 |
| Dell          | Latitude E6510              | Notebook    | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [ca6be0ae4b](https://linux-hardware.org/?probe=ca6be0ae4b) | Jan 26, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [37ec4f5294](https://linux-hardware.org/?probe=37ec4f5294) | Jan 25, 2022 |
| ASRock        | P75 Pro3                    | Desktop     | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b50f284364](https://linux-hardware.org/?probe=b50f284364) | Jan 23, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [2c53d21746](https://linux-hardware.org/?probe=2c53d21746) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [02be439ac8](https://linux-hardware.org/?probe=02be439ac8) | Jan 22, 2022 |
| HP            | EliteBook 1050 G1           | Notebook    | [1bb5cb826f](https://linux-hardware.org/?probe=1bb5cb826f) | Jan 19, 2022 |
| TWC           | Unknown                     | Notebook    | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| TWC           | Unknown                     | Notebook    | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [fa62cb2996](https://linux-hardware.org/?probe=fa62cb2996) | Jan 11, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| Biostar       | TB250-BTC+                  | Desktop     | [ef57a01461](https://linux-hardware.org/?probe=ef57a01461) | Jan 06, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [f586d10ee6](https://linux-hardware.org/?probe=f586d10ee6) | Jan 05, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [8b6fab3f89](https://linux-hardware.org/?probe=8b6fab3f89) | Jan 05, 2022 |
| MSI           | GT70 2PC                    | Notebook    | [61a5023d6a](https://linux-hardware.org/?probe=61a5023d6a) | Jan 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2d6469644a](https://linux-hardware.org/?probe=2d6469644a) | Jan 02, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [0396ef9c72](https://linux-hardware.org/?probe=0396ef9c72) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6324598512](https://linux-hardware.org/?probe=6324598512) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [38dda4af6b](https://linux-hardware.org/?probe=38dda4af6b) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Dell          | Latitude 7490               | Notebook    | [4e350048ed](https://linux-hardware.org/?probe=4e350048ed) | Dec 27, 2021 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [183a47572f](https://linux-hardware.org/?probe=183a47572f) | Dec 27, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [9fb08ebeb4](https://linux-hardware.org/?probe=9fb08ebeb4) | Dec 26, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [fe350107e3](https://linux-hardware.org/?probe=fe350107e3) | Dec 25, 2021 |
| Gigabyte      | MJPLNCB-00                  | Desktop     | [fe81720eae](https://linux-hardware.org/?probe=fe81720eae) | Dec 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [a6fc4a2adb](https://linux-hardware.org/?probe=a6fc4a2adb) | Dec 22, 2021 |
| MSI           | A55M-P33                    | Desktop     | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [048c623b7a](https://linux-hardware.org/?probe=048c623b7a) | Dec 12, 2021 |
| Biostar       | NF520-A2 TE                 | Desktop     | [5878187120](https://linux-hardware.org/?probe=5878187120) | Dec 07, 2021 |
| Toshiba       | Satellite Pro L650          | Notebook    | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| MSI           | H61M-P20                    | Desktop     | [614ffcb196](https://linux-hardware.org/?probe=614ffcb196) | Dec 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a61a3df5f9](https://linux-hardware.org/?probe=a61a3df5f9) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [19fbf0d287](https://linux-hardware.org/?probe=19fbf0d287) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [3df309c91c](https://linux-hardware.org/?probe=3df309c91c) | Dec 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [478ab590ac](https://linux-hardware.org/?probe=478ab590ac) | Dec 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [60a074698a](https://linux-hardware.org/?probe=60a074698a) | Dec 01, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [440d34a6b0](https://linux-hardware.org/?probe=440d34a6b0) | Nov 28, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [bb7b625409](https://linux-hardware.org/?probe=bb7b625409) | Nov 28, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [7a8c29f7ba](https://linux-hardware.org/?probe=7a8c29f7ba) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [0415c0798f](https://linux-hardware.org/?probe=0415c0798f) | Nov 18, 2021 |
| Acer          | Aspire ES1-533              | Notebook    | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [7708d61566](https://linux-hardware.org/?probe=7708d61566) | Nov 05, 2021 |
| MSI           | G41M-P23                    | Desktop     | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| MSI           | G41M-P23                    | Desktop     | [ce4c8636f0](https://linux-hardware.org/?probe=ce4c8636f0) | Nov 04, 2021 |
| eMachines     | eME440                      | Notebook    | [1427ebffb0](https://linux-hardware.org/?probe=1427ebffb0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [b6338a1294](https://linux-hardware.org/?probe=b6338a1294) | Oct 25, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d180cf6efc](https://linux-hardware.org/?probe=d180cf6efc) | Oct 23, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [cb8bcc4d2d](https://linux-hardware.org/?probe=cb8bcc4d2d) | Oct 22, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [71c19b42fc](https://linux-hardware.org/?probe=71c19b42fc) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | Notebook    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Lenovo        | ThinkCentre M57 6075Y3W     | Desktop     | [a5e2419919](https://linux-hardware.org/?probe=a5e2419919) | Oct 19, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [650c91f4db](https://linux-hardware.org/?probe=650c91f4db) | Oct 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [5e28e542c2](https://linux-hardware.org/?probe=5e28e542c2) | Oct 17, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [7eafd054fc](https://linux-hardware.org/?probe=7eafd054fc) | Oct 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f1fc83e719](https://linux-hardware.org/?probe=f1fc83e719) | Oct 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2802b3ba4f](https://linux-hardware.org/?probe=2802b3ba4f) | Oct 17, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2e7ac4731f](https://linux-hardware.org/?probe=2e7ac4731f) | Oct 16, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [0582e2316b](https://linux-hardware.org/?probe=0582e2316b) | Oct 12, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c8b4b9444e](https://linux-hardware.org/?probe=c8b4b9444e) | Oct 11, 2021 |
| ASRock        | QC5000-ITX/WiFi             | Desktop     | [74391da331](https://linux-hardware.org/?probe=74391da331) | Oct 09, 2021 |
| Lenovo        | G555 0873                   | Notebook    | [a38f52851a](https://linux-hardware.org/?probe=a38f52851a) | Oct 05, 2021 |
| Biostar       | A320MH                      | Desktop     | [85950c5033](https://linux-hardware.org/?probe=85950c5033) | Sep 25, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [bd2044749b](https://linux-hardware.org/?probe=bd2044749b) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| ASUSTek       | H81M-R                      | Desktop     | [dfe4dc9048](https://linux-hardware.org/?probe=dfe4dc9048) | Sep 22, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [02ccb36302](https://linux-hardware.org/?probe=02ccb36302) | Sep 21, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [081e791398](https://linux-hardware.org/?probe=081e791398) | Sep 19, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [59a0efda89](https://linux-hardware.org/?probe=59a0efda89) | Sep 18, 2021 |
| MSI           | MS-7309                     | Desktop     | [f2ac6eb80a](https://linux-hardware.org/?probe=f2ac6eb80a) | Sep 18, 2021 |
| Lenovo        | ThinkCentre M57 6075Y3W     | Desktop     | [f133dd54a3](https://linux-hardware.org/?probe=f133dd54a3) | Sep 18, 2021 |
| ASUSTek       | 1005PE                      | Notebook    | [a3adf0356c](https://linux-hardware.org/?probe=a3adf0356c) | Sep 18, 2021 |
| HP            | 212B                        | Desktop     | [9a7f2627a3](https://linux-hardware.org/?probe=9a7f2627a3) | Sep 15, 2021 |
| HP            | 212B                        | Desktop     | [289f117cde](https://linux-hardware.org/?probe=289f117cde) | Sep 14, 2021 |
| ASUSTek       | H81M-R                      | Desktop     | [6a9795f23f](https://linux-hardware.org/?probe=6a9795f23f) | Sep 13, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [cedbbde363](https://linux-hardware.org/?probe=cedbbde363) | Sep 13, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [67285c1d5d](https://linux-hardware.org/?probe=67285c1d5d) | Sep 11, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [ab6a989deb](https://linux-hardware.org/?probe=ab6a989deb) | Sep 09, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [f77883b614](https://linux-hardware.org/?probe=f77883b614) | Sep 07, 2021 |
| ASRock        | Q1900M                      | Desktop     | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | Desktop     | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| HP            | ProBook 4730s               | Notebook    | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [cad80329d8](https://linux-hardware.org/?probe=cad80329d8) | Aug 31, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [60f43f8815](https://linux-hardware.org/?probe=60f43f8815) | Aug 29, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [ebac51e403](https://linux-hardware.org/?probe=ebac51e403) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [056e1c0825](https://linux-hardware.org/?probe=056e1c0825) | Aug 21, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [433d420dd4](https://linux-hardware.org/?probe=433d420dd4) | Aug 20, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [79051f2400](https://linux-hardware.org/?probe=79051f2400) | Aug 19, 2021 |
| MSI           | 740GM-P25                   | Desktop     | [e1d245e0a3](https://linux-hardware.org/?probe=e1d245e0a3) | Aug 19, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [c0653de55c](https://linux-hardware.org/?probe=c0653de55c) | Aug 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| HP            | G62                         | Notebook    | [b6eeeba9d1](https://linux-hardware.org/?probe=b6eeeba9d1) | Aug 15, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [3f122964da](https://linux-hardware.org/?probe=3f122964da) | Aug 14, 2021 |
| HP            | G62                         | Notebook    | [4adea9bed4](https://linux-hardware.org/?probe=4adea9bed4) | Aug 14, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [3985c521c2](https://linux-hardware.org/?probe=3985c521c2) | Aug 12, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [bf5a5f589f](https://linux-hardware.org/?probe=bf5a5f589f) | Aug 05, 2021 |
| HP            | Pavilion g6                 | Notebook    | [df95184640](https://linux-hardware.org/?probe=df95184640) | Aug 02, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0e0aaaac98](https://linux-hardware.org/?probe=0e0aaaac98) | Aug 02, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fda988dc8a](https://linux-hardware.org/?probe=fda988dc8a) | Jul 30, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [766df6d543](https://linux-hardware.org/?probe=766df6d543) | Jul 30, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [d86a526a9b](https://linux-hardware.org/?probe=d86a526a9b) | Jul 28, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [48b32724e2](https://linux-hardware.org/?probe=48b32724e2) | Jul 27, 2021 |
| Toshiba       | Satellite Pro L650          | Notebook    | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Toshiba       | Satellite C55-B             | Notebook    | [c703c827c6](https://linux-hardware.org/?probe=c703c827c6) | Jul 21, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [25113d73cc](https://linux-hardware.org/?probe=25113d73cc) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b44e9be41b](https://linux-hardware.org/?probe=b44e9be41b) | Jul 19, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56faa89619](https://linux-hardware.org/?probe=56faa89619) | Jul 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| ASUSTek       | M2N-MX                      | Desktop     | [b5def43240](https://linux-hardware.org/?probe=b5def43240) | Jun 23, 2021 |
| HP            | Compaq nx7400 (RU429EA#A... | Notebook    | [ce0542775b](https://linux-hardware.org/?probe=ce0542775b) | Jun 22, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [d04705eaef](https://linux-hardware.org/?probe=d04705eaef) | Jun 20, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [2a7524175d](https://linux-hardware.org/?probe=2a7524175d) | Jun 20, 2021 |
| MSI           | 970A-G43                    | Desktop     | [447e2a364c](https://linux-hardware.org/?probe=447e2a364c) | Jun 18, 2021 |
| ASUSTek       | G551JK                      | Notebook    | [aace05a48f](https://linux-hardware.org/?probe=aace05a48f) | Jun 17, 2021 |
| ASUSTek       | G551JK                      | Notebook    | [2947ae8fc2](https://linux-hardware.org/?probe=2947ae8fc2) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [80b26a6c37](https://linux-hardware.org/?probe=80b26a6c37) | Jun 16, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [8487e42c1e](https://linux-hardware.org/?probe=8487e42c1e) | Jun 12, 2021 |
| MSI           | 970A-G43                    | Desktop     | [009fc99fc0](https://linux-hardware.org/?probe=009fc99fc0) | Jun 11, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [09f134f35d](https://linux-hardware.org/?probe=09f134f35d) | Jun 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [18fd922adc](https://linux-hardware.org/?probe=18fd922adc) | Jun 10, 2021 |
| Gigabyte      | 945PL-S3                    | Desktop     | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| MSI           | 970A-G43                    | Desktop     | [c0523d2ed9](https://linux-hardware.org/?probe=c0523d2ed9) | Jun 08, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b527e6a2a9](https://linux-hardware.org/?probe=b527e6a2a9) | Jun 08, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Dell          | Latitude 5520               | Notebook    | [45b3e7c2af](https://linux-hardware.org/?probe=45b3e7c2af) | Jun 06, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [ec4c7c0192](https://linux-hardware.org/?probe=ec4c7c0192) | Jun 04, 2021 |
| MSI           | CR500                       | Notebook    | [76d2d77034](https://linux-hardware.org/?probe=76d2d77034) | Jun 03, 2021 |
| MSI           | CR500                       | Notebook    | [93f6fd0ae4](https://linux-hardware.org/?probe=93f6fd0ae4) | Jun 02, 2021 |
| MSI           | CR500                       | Notebook    | [b1d00d1444](https://linux-hardware.org/?probe=b1d00d1444) | May 30, 2021 |
| HP            | Notebook                    | Notebook    | [f60121b761](https://linux-hardware.org/?probe=f60121b761) | May 30, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [094ade14ae](https://linux-hardware.org/?probe=094ade14ae) | May 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [229b36f7f9](https://linux-hardware.org/?probe=229b36f7f9) | May 25, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [5824a76242](https://linux-hardware.org/?probe=5824a76242) | May 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [631e15df6a](https://linux-hardware.org/?probe=631e15df6a) | May 18, 2021 |
| Apple         | MacBookPro1,1               | Notebook    | [cc14c7fa2e](https://linux-hardware.org/?probe=cc14c7fa2e) | May 16, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [ff29bdd7f7](https://linux-hardware.org/?probe=ff29bdd7f7) | May 14, 2021 |
| HP            | ProBook 4530s               | Notebook    | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Vostro 5402                 | Notebook    | [03aa94f52f](https://linux-hardware.org/?probe=03aa94f52f) | May 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b5519e189](https://linux-hardware.org/?probe=7b5519e189) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [b57920ccda](https://linux-hardware.org/?probe=b57920ccda) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [19bf5a98df](https://linux-hardware.org/?probe=19bf5a98df) | May 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5ea8612591](https://linux-hardware.org/?probe=5ea8612591) | May 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e3f1850f8e](https://linux-hardware.org/?probe=e3f1850f8e) | May 07, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [211622d161](https://linux-hardware.org/?probe=211622d161) | May 05, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Serbia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 98        | 8.97%   |
| Ubuntu 22.04                 | 65        | 5.95%   |
| Ubuntu 18.04                 | 57        | 5.22%   |
| OpenMandriva 4.3             | 28        | 2.56%   |
| OpenMandriva 4.2             | 26        | 2.38%   |
| Pop!_OS 22.04                | 25        | 2.29%   |
| Zorin 16                     | 21        | 1.92%   |
| Fedora 40                    | 20        | 1.83%   |
| Arch Rolling                 | 20        | 1.83%   |
| BlackPanther 18.1            | 19        | 1.74%   |
| Ubuntu 24.04                 | 16        | 1.46%   |
| Debian 12                    | 16        | 1.46%   |
| OpenMandriva 23.01           | 15        | 1.37%   |
| ArcoLinux Rolling            | 15        | 1.37%   |
| KDE neon 20.04               | 14        | 1.28%   |
| Zorin 15                     | 13        | 1.19%   |
| Arch                         | 13        | 1.19%   |
| ROSA R11                     | 12        | 1.1%    |
| ROSA R10                     | 12        | 1.1%    |
| Fedora 38                    | 12        | 1.1%    |
| Ubuntu 19.10                 | 11        | 1.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 1.01%   |
| Linux Mint 19.3              | 11        | 1.01%   |
| Fedora 39                    | 11        | 1.01%   |
| Ubuntu 21.10                 | 10        | 0.91%   |
| Linux Mint 21.1              | 9         | 0.82%   |
| Linux Mint 20.3              | 9         | 0.82%   |
| Kubuntu 22.04                | 9         | 0.82%   |
| Zorin 17                     | 8         | 0.73%   |
| Ubuntu 23.10                 | 8         | 0.73%   |
| Ubuntu 23.04                 | 8         | 0.73%   |
| Ubuntu 22.10                 | 8         | 0.73%   |
| Ubuntu 21.04                 | 8         | 0.73%   |
| ROSA R11.1                   | 8         | 0.73%   |
| OpenMandriva 23.08           | 8         | 0.73%   |
| Manjaro                      | 8         | 0.73%   |
| Fedora 41                    | 8         | 0.73%   |
| Fedora 37                    | 8         | 0.73%   |
| EndeavourOS Rolling          | 8         | 0.73%   |
| Ubuntu 18.10                 | 7         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 294       | 29.25%  |
| OpenMandriva  | 100       | 9.95%   |
| Fedora        | 71        | 7.06%   |
| Linux Mint    | 63        | 6.27%   |
| Zorin         | 44        | 4.38%   |
| ROSA          | 44        | 4.38%   |
| Pop!_OS       | 43        | 4.28%   |
| Endless       | 35        | 3.48%   |
| Arch          | 33        | 3.28%   |
| Debian        | 30        | 2.99%   |
| Manjaro       | 26        | 2.59%   |
| Kubuntu       | 25        | 2.49%   |
| KDE neon      | 21        | 2.09%   |
| BlackPanther  | 21        | 2.09%   |
| openSUSE      | 18        | 1.79%   |
| ArcoLinux     | 17        | 1.69%   |
| Xubuntu       | 16        | 1.59%   |
| MX            | 12        | 1.19%   |
| Kali          | 11        | 1.09%   |
| EndeavourOS   | 8         | 0.8%    |
| Elementary    | 7         | 0.7%    |
| Lubuntu       | 5         | 0.5%    |
| Ubuntu Unity  | 4         | 0.4%    |
| Ubuntu MATE   | 4         | 0.4%    |
| Clear Linux   | 4         | 0.4%    |
| Nobara        | 3         | 0.3%    |
| Garuda Linux  | 3         | 0.3%    |
| CentOS        | 3         | 0.3%    |
| Void Linux    | 2         | 0.2%    |
| Ubuntu Budgie | 2         | 0.2%    |
| Slackware     | 2         | 0.2%    |
| Peppermint    | 2         | 0.2%    |
| NixOS         | 2         | 0.2%    |
| LMDE          | 2         | 0.2%    |
| LinuxFX       | 2         | 0.2%    |
| Gentoo        | 2         | 0.2%    |
| CachyOS       | 2         | 0.2%    |
| Aurora        | 2         | 0.2%    |
| Artix         | 2         | 0.2%    |
| Xero          | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 26        | 2.19%   |
| 5.10.14-desktop-1omv4002           | 26        | 2.19%   |
| 5.4.0-42-generic                   | 16        | 1.35%   |
| 6.1.1-desktop-1omv2290             | 15        | 1.26%   |
| 4.18.16-desktop-1bP                | 15        | 1.26%   |
| 5.15.0-56-generic                  | 10        | 0.84%   |
| 6.4.11-desktop-1omv2390            | 8         | 0.67%   |
| 5.3.0-40-generic                   | 8         | 0.67%   |
| 4.18.0-15-generic                  | 8         | 0.67%   |
| 5.8.0-14-generic                   | 7         | 0.59%   |
| 5.15.0-53-generic                  | 7         | 0.59%   |
| 6.5.0-35-generic                   | 6         | 0.5%    |
| 5.4.0-58-generic                   | 6         | 0.5%    |
| 5.4.0-48-generic                   | 6         | 0.5%    |
| 5.15.0-48-generic                  | 6         | 0.5%    |
| 5.15.0-46-generic                  | 6         | 0.5%    |
| 5.11.0-35-generic                  | 6         | 0.5%    |
| 5.11.0-27-generic                  | 6         | 0.5%    |
| 4.18.0-17-generic                  | 6         | 0.5%    |
| 6.8.0-31-generic                   | 5         | 0.42%   |
| 6.6.2-desktop-1omv2390             | 5         | 0.42%   |
| 6.5.0-27-generic                   | 5         | 0.42%   |
| 6.5.0-26-generic                   | 5         | 0.42%   |
| 6.2.6-desktop-1omv2390             | 5         | 0.42%   |
| 6.2.0-26-generic                   | 5         | 0.42%   |
| 5.4.0-54-generic                   | 5         | 0.42%   |
| 5.4.0-52-generic                   | 5         | 0.42%   |
| 5.4.0-47-generic                   | 5         | 0.42%   |
| 5.4.0-31-generic                   | 5         | 0.42%   |
| 5.4.0-29-generic                   | 5         | 0.42%   |
| 5.3.0-51-generic                   | 5         | 0.42%   |
| 5.15.0-76-generic                  | 5         | 0.42%   |
| 5.15.0-52-generic                  | 5         | 0.42%   |
| 5.13.0-30-generic                  | 5         | 0.42%   |
| 5.13.0-28-generic                  | 5         | 0.42%   |
| 5.11.0-34-generic                  | 5         | 0.42%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 0.42%   |
| 5.0.0-27-generic                   | 5         | 0.42%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 5         | 0.42%   |
| 6.9.3-76060903-generic             | 4         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 123       | 10.99%  |
| 5.15.0  | 95        | 8.49%   |
| 4.15.0  | 51        | 4.56%   |
| 5.11.0  | 40        | 3.57%   |
| 5.8.0   | 37        | 3.31%   |
| 5.3.0   | 37        | 3.31%   |
| 6.5.0   | 35        | 3.13%   |
| 5.13.0  | 32        | 2.86%   |
| 4.18.0  | 30        | 2.68%   |
| 6.8.0   | 29        | 2.59%   |
| 5.16.7  | 26        | 2.32%   |
| 5.10.14 | 26        | 2.32%   |
| 5.19.0  | 25        | 2.23%   |
| 5.0.0   | 23        | 2.06%   |
| 6.1.0   | 22        | 1.97%   |
| 6.2.0   | 18        | 1.61%   |
| 6.1.1   | 17        | 1.52%   |
| 4.18.16 | 15        | 1.34%   |
| 6.4.11  | 11        | 0.98%   |
| 5.10.0  | 11        | 0.98%   |
| 6.2.6   | 9         | 0.8%    |
| 4.9.20  | 7         | 0.63%   |
| 6.4.6   | 6         | 0.54%   |
| 6.9.3   | 5         | 0.45%   |
| 6.6.2   | 5         | 0.45%   |
| 5.10.74 | 5         | 0.45%   |
| 4.9.60  | 5         | 0.45%   |
| 6.9.7   | 4         | 0.36%   |
| 6.12.5  | 4         | 0.36%   |
| 6.11.7  | 4         | 0.36%   |
| 6.10.0  | 4         | 0.36%   |
| 5.6.14  | 4         | 0.36%   |
| 5.14.21 | 4         | 0.36%   |
| 4.19.0  | 4         | 0.36%   |
| 6.8.5   | 3         | 0.27%   |
| 6.7.9   | 3         | 0.27%   |
| 6.7.0   | 3         | 0.27%   |
| 6.6.7   | 3         | 0.27%   |
| 6.5.11  | 3         | 0.27%   |
| 6.4.12  | 3         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 139       | 12.62%  |
| 5.15    | 111       | 10.08%  |
| 6.1     | 56        | 5.09%   |
| 4.15    | 51        | 4.63%   |
| 5.11    | 50        | 4.54%   |
| 5.10    | 49        | 4.45%   |
| 6.5     | 46        | 4.18%   |
| 4.18    | 45        | 4.09%   |
| 6.8     | 43        | 3.91%   |
| 5.3     | 43        | 3.91%   |
| 5.8     | 42        | 3.81%   |
| 5.19    | 40        | 3.63%   |
| 5.13    | 36        | 3.27%   |
| 6.2     | 35        | 3.18%   |
| 5.16    | 35        | 3.18%   |
| 6.4     | 26        | 2.36%   |
| 5.0     | 26        | 2.36%   |
| 4.9     | 21        | 1.91%   |
| 6.6     | 20        | 1.82%   |
| 6.0     | 19        | 1.73%   |
| 6.9     | 17        | 1.54%   |
| 6.10    | 17        | 1.54%   |
| 6.11    | 15        | 1.36%   |
| 6.3     | 12        | 1.09%   |
| 6.12    | 12        | 1.09%   |
| 5.6     | 11        | 1%      |
| 5.14    | 9         | 0.82%   |
| 6.7     | 8         | 0.73%   |
| 5.9     | 8         | 0.73%   |
| 5.7     | 8         | 0.73%   |
| 4.19    | 8         | 0.73%   |
| 5.18    | 7         | 0.64%   |
| 5.17    | 7         | 0.64%   |
| 4.1     | 6         | 0.54%   |
| 5.12    | 5         | 0.45%   |
| 5.1     | 4         | 0.36%   |
| 4.4     | 3         | 0.27%   |
| 4.13    | 3         | 0.27%   |
| 5.5     | 2         | 0.18%   |
| 5.2     | 2         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 933       | 97.09%  |
| i686    | 23        | 2.39%   |
| aarch64 | 4         | 0.42%   |
| armv7l  | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 423       | 42.05%  |
| KDE5            | 211       | 20.97%  |
| Unknown         | 102       | 10.14%  |
| XFCE            | 80        | 7.95%   |
| X-Cinnamon      | 56        | 5.57%   |
| KDE4            | 25        | 2.49%   |
| KDE             | 19        | 1.89%   |
| KDE6            | 16        | 1.59%   |
| Cinnamon        | 10        | 0.99%   |
| LXQt            | 9         | 0.89%   |
| i3              | 9         | 0.89%   |
| MATE            | 8         | 0.8%    |
| Pantheon        | 7         | 0.7%    |
| Unity           | 4         | 0.4%    |
| LXDE            | 4         | 0.4%    |
| Hyprland        | 4         | 0.4%    |
| Deepin          | 4         | 0.4%    |
| qtile           | 3         | 0.3%    |
| GNOME Flashback | 3         | 0.3%    |
| Budgie          | 2         | 0.2%    |
| Sway            | 1         | 0.1%    |
| Openbox         | 1         | 0.1%    |
| i3-with-shmlog  | 1         | 0.1%    |
| GNOME Classic   | 1         | 0.1%    |
| DWM             | 1         | 0.1%    |
| BunsenLabs      | 1         | 0.1%    |
| awesome         | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 722       | 71.56%  |
| Wayland | 227       | 22.5%   |
| Unknown | 44        | 4.36%   |
| Tty     | 16        | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 455       | 45.27%  |
| SDDM    | 200       | 19.9%   |
| GDM3    | 130       | 12.94%  |
| LightDM | 99        | 9.85%   |
| GDM     | 77        | 7.66%   |
| KDM     | 23        | 2.29%   |
| TDM     | 15        | 1.49%   |
| XDM     | 2         | 0.2%    |
| Ly      | 2         | 0.2%    |
| MDM     | 1         | 0.1%    |
| LXDM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 693       | 69.02%  |
| Unknown     | 132       | 13.15%  |
| sr_RS       | 59        | 5.88%   |
| en_GB       | 27        | 2.69%   |
| sr_RS@latin | 26        | 2.59%   |
| C           | 21        | 2.09%   |
| hu_HU       | 15        | 1.49%   |
| ru_RU       | 9         | 0.9%    |
| de_DE       | 7         | 0.7%    |
| hr_HR       | 5         | 0.5%    |
| en_AU       | 3         | 0.3%    |
| Default     | 2         | 0.2%    |
| sk_SK       | 1         | 0.1%    |
| nl_NL       | 1         | 0.1%    |
| en_IE       | 1         | 0.1%    |
| en_DK       | 1         | 0.1%    |
| en_BW       | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 526       | 53.29%  |
| EFI  | 461       | 46.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 684       | 67.92%  |
| Overlay | 110       | 10.92%  |
| Btrfs   | 91        | 9.04%   |
| Tmpfs   | 57        | 5.66%   |
| Unknown | 44        | 4.37%   |
| Xfs     | 9         | 0.89%   |
| Zfs     | 8         | 0.79%   |
| Ext3    | 2         | 0.2%    |
| Ext2    | 2         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 466       | 46.6%   |
| GPT     | 381       | 38.1%   |
| MBR     | 153       | 15.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 832       | 84.73%  |
| Yes       | 150       | 15.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 681       | 69.07%  |
| Yes       | 305       | 30.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUSTek Computer                 | 195       | 20.35%  |
| Lenovo                           | 161       | 16.81%  |
| Hewlett-Packard                  | 126       | 13.15%  |
| Gigabyte Technology              | 117       | 12.21%  |
| Dell                             | 81        | 8.46%   |
| MSI                              | 70        | 7.31%   |
| Acer                             | 54        | 5.64%   |
| ASRock                           | 26        | 2.71%   |
| Apple                            | 16        | 1.67%   |
| Toshiba                          | 15        | 1.57%   |
| Fujitsu                          | 13        | 1.36%   |
| Biostar                          | 12        | 1.25%   |
| Intel                            | 7         | 0.73%   |
| Medion                           | 6         | 0.63%   |
| Fujitsu Siemens                  | 6         | 0.63%   |
| Sony                             | 5         | 0.52%   |
| Samsung Electronics              | 4         | 0.42%   |
| Raspberry Pi Foundation          | 4         | 0.42%   |
| HUAWEI                           | 4         | 0.42%   |
| Timi                             | 3         | 0.31%   |
| Huanan                           | 3         | 0.31%   |
| Pegatron                         | 2         | 0.21%   |
| LG Electronics                   | 2         | 0.21%   |
| eMachines                        | 2         | 0.21%   |
| TWC                              | 1         | 0.1%    |
| Synology                         | 1         | 0.1%    |
| Supermicro                       | 1         | 0.1%    |
| Sun Microsystems                 | 1         | 0.1%    |
| SLIMBOOK                         | 1         | 0.1%    |
| Sapphire                         | 1         | 0.1%    |
| Razer                            | 1         | 0.1%    |
| Purism                           | 1         | 0.1%    |
| Packard Bell                     | 1         | 0.1%    |
| NCR                              | 1         | 0.1%    |
| Micro Computer (HK) Tech Limited | 1         | 0.1%    |
| MACHINIST                        | 1         | 0.1%    |
| Inventec                         | 1         | 0.1%    |
| IBM                              | 1         | 0.1%    |
| HONOR                            | 1         | 0.1%    |
| Framework                        | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| ASUS PRIME A320M-K            | 21        | 2.19%   |
| ASUS All Series               | 12        | 1.25%   |
| Acer Aspire A315-31           | 7         | 0.73%   |
| MSI MS-7309                   | 6         | 0.63%   |
| HP Notebook                   | 6         | 0.63%   |
| Gigabyte B450M DS3H           | 6         | 0.63%   |
| Gigabyte H61M-S2PV            | 5         | 0.52%   |
| MSI MS-7788                   | 4         | 0.42%   |
| MSI MS-7641                   | 4         | 0.42%   |
| Gigabyte A320M-H              | 4         | 0.42%   |
| Dell Inspiron 3593            | 4         | 0.42%   |
| Biostar A320MH                | 4         | 0.42%   |
| Unknown                       | 4         | 0.42%   |
| MSI MS-7C52                   | 3         | 0.31%   |
| MSI MS-7C02                   | 3         | 0.31%   |
| MSI MS-7721                   | 3         | 0.31%   |
| MSI MS-7693                   | 3         | 0.31%   |
| MSI MS-7597                   | 3         | 0.31%   |
| MSI MS-7592                   | 3         | 0.31%   |
| Lenovo V330-15IKB 81AX        | 3         | 0.31%   |
| Lenovo IdeaPad 5 14ARE05 81YM | 3         | 0.31%   |
| Lenovo IdeaPad 5 14ALC05 82LM | 3         | 0.31%   |
| Lenovo IdeaPad 330-15IKB 81DE | 3         | 0.31%   |
| Lenovo IdeaPad 3 15IIL05 81WE | 3         | 0.31%   |
| Lenovo IdeaPad 110-15IBR 80T7 | 3         | 0.31%   |
| Lenovo B50-45 20388           | 3         | 0.31%   |
| HP ProBook 440 G3             | 3         | 0.31%   |
| HP Pavilion dv7               | 3         | 0.31%   |
| HP Laptop 15-db1xxx           | 3         | 0.31%   |
| HP Laptop 15-db0xxx           | 3         | 0.31%   |
| HP Laptop 15-da0xxx           | 3         | 0.31%   |
| HP EliteBook 840 G5           | 3         | 0.31%   |
| HP 250 G5 Notebook PC         | 3         | 0.31%   |
| Gigabyte GA-890GPA-UD3H       | 3         | 0.31%   |
| Gigabyte F2A68HM-S1           | 3         | 0.31%   |
| Gigabyte EX58-UD5             | 3         | 0.31%   |
| Dell Vostro 15 3515           | 3         | 0.31%   |
| Dell OptiPlex 755             | 3         | 0.31%   |
| Dell OptiPlex 390             | 3         | 0.31%   |
| Dell Inspiron 3542            | 3         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 59        | 6.16%   |
| Lenovo IdeaPad        | 44        | 4.59%   |
| Acer Aspire           | 43        | 4.49%   |
| Dell Inspiron         | 30        | 3.13%   |
| ASUS VivoBook         | 30        | 3.13%   |
| ASUS PRIME            | 30        | 3.13%   |
| HP EliteBook          | 21        | 2.19%   |
| HP Laptop             | 19        | 1.98%   |
| Dell Latitude         | 19        | 1.98%   |
| HP ProBook            | 15        | 1.57%   |
| HP Compaq             | 14        | 1.46%   |
| Toshiba Satellite     | 13        | 1.36%   |
| HP Pavilion           | 13        | 1.36%   |
| ASUS ROG              | 13        | 1.36%   |
| ASUS All              | 12        | 1.25%   |
| Dell OptiPlex         | 11        | 1.15%   |
| Lenovo Legion         | 10        | 1.04%   |
| Gigabyte B450M        | 10        | 1.04%   |
| Lenovo ThinkBook      | 8         | 0.84%   |
| HP 250                | 8         | 0.84%   |
| Dell Vostro           | 8         | 0.84%   |
| Fujitsu ESPRIMO       | 7         | 0.73%   |
| Dell Precision        | 7         | 0.73%   |
| ASUS TUF              | 7         | 0.73%   |
| MSI MS-7309           | 6         | 0.63%   |
| Lenovo Yoga           | 6         | 0.63%   |
| Lenovo ThinkCentre    | 6         | 0.63%   |
| HP Notebook           | 6         | 0.63%   |
| Gigabyte H61M-S2PV    | 5         | 0.52%   |
| Fujitsu Siemens AMILO | 5         | 0.52%   |
| RPi Raspberry         | 4         | 0.42%   |
| MSI MS-7788           | 4         | 0.42%   |
| MSI MS-7641           | 4         | 0.42%   |
| HP OMEN               | 4         | 0.42%   |
| HP ENVY               | 4         | 0.42%   |
| Gigabyte X570         | 4         | 0.42%   |
| Gigabyte A320M-H      | 4         | 0.42%   |
| Fujitsu LIFEBOOK      | 4         | 0.42%   |
| Biostar A320MH        | 4         | 0.42%   |
| ASUS Zenbook          | 4         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 95        | 9.92%   |
| 2017    | 74        | 7.72%   |
| 2020    | 73        | 7.62%   |
| 2012    | 72        | 7.52%   |
| 2011    | 72        | 7.52%   |
| 2019    | 68        | 7.1%    |
| 2014    | 63        | 6.58%   |
| 2013    | 60        | 6.26%   |
| 2010    | 54        | 5.64%   |
| 2016    | 45        | 4.7%    |
| 2009    | 41        | 4.28%   |
| 2008    | 41        | 4.28%   |
| 2021    | 40        | 4.18%   |
| 2022    | 35        | 3.65%   |
| 2015    | 34        | 3.55%   |
| 2007    | 31        | 3.24%   |
| 2023    | 29        | 3.03%   |
| 2006    | 19        | 1.98%   |
| 2024    | 6         | 0.63%   |
| Unknown | 3         | 0.31%   |
| 2005    | 2         | 0.21%   |
| 2004    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 517       | 53.97%  |
| Desktop        | 403       | 42.07%  |
| Convertible    | 16        | 1.67%   |
| Mini pc        | 6         | 0.63%   |
| All in one     | 5         | 0.52%   |
| System on chip | 4         | 0.42%   |
| Tablet         | 4         | 0.42%   |
| Server         | 3         | 0.31%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 898       | 92.96%  |
| Enabled  | 68        | 7.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 957       | 99.9%   |
| Yes  | 1         | 0.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 224       | 22.74%  |
| 8.01-16.0   | 220       | 22.34%  |
| 4.01-8.0    | 219       | 22.23%  |
| 16.01-24.0  | 156       | 15.84%  |
| 32.01-64.0  | 75        | 7.61%   |
| 1.01-2.0    | 41        | 4.16%   |
| 2.01-3.0    | 16        | 1.62%   |
| 24.01-32.0  | 14        | 1.42%   |
| 64.01-256.0 | 14        | 1.42%   |
| 0.51-1.0    | 6         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 363       | 33.12%  |
| 2.01-3.0   | 262       | 23.91%  |
| 4.01-8.0   | 149       | 13.59%  |
| 3.01-4.0   | 146       | 13.32%  |
| 0.51-1.0   | 96        | 8.76%   |
| 8.01-16.0  | 54        | 4.93%   |
| 0.01-0.5   | 15        | 1.37%   |
| 16.01-24.0 | 9         | 0.82%   |
| 24.01-32.0 | 2         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 599       | 60.14%  |
| 2       | 234       | 23.49%  |
| 3       | 80        | 8.03%   |
| 4       | 39        | 3.92%   |
| 0       | 18        | 1.81%   |
| 5       | 15        | 1.51%   |
| 6       | 5         | 0.5%    |
| 7       | 2         | 0.2%    |
| Unknown | 2         | 0.2%    |
| 10      | 1         | 0.1%    |
| 8       | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 610       | 62.31%  |
| Yes       | 369       | 37.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 859       | 89.48%  |
| No        | 101       | 10.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 660       | 68.39%  |
| No        | 305       | 31.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 527       | 54.27%  |
| No        | 444       | 45.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Serbia  | 958       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Belgrade          | 572       | 55.16%  |
| Novi Sad          | 104       | 10.03%  |
| Niš              | 55        | 5.3%    |
| Subotica          | 19        | 1.83%   |
| Zrenjanin         | 14        | 1.35%   |
| Kragujevac        | 14        | 1.35%   |
| Pančevo          | 12        | 1.16%   |
| Požarevac        | 8         | 0.77%   |
| Leskovac          | 8         | 0.77%   |
| Semlin            | 7         | 0.68%   |
| Čačak           | 7         | 0.68%   |
| Becej             | 7         | 0.68%   |
| Backa Topola      | 7         | 0.68%   |
| Senta             | 6         | 0.58%   |
| Karloca           | 6         | 0.58%   |
| Indjija           | 6         | 0.58%   |
| Vršac            | 5         | 0.48%   |
| Savski Venac      | 5         | 0.48%   |
| Palanka           | 5         | 0.48%   |
| Kraljevo          | 5         | 0.48%   |
| Jagodina          | 5         | 0.48%   |
| Bor               | 5         | 0.48%   |
| Sremska Mitrovica | 4         | 0.39%   |
| Sombor            | 4         | 0.39%   |
| Novi Karlovci     | 4         | 0.39%   |
| Novi Belgrade     | 4         | 0.39%   |
| New Belgrade      | 4         | 0.39%   |
| Lazarevac         | 4         | 0.39%   |
| Cuprija           | 4         | 0.39%   |
| Ada               | 4         | 0.39%   |
| Vranje            | 3         | 0.29%   |
| Trstenik          | 3         | 0.29%   |
| Stara Pazova      | 3         | 0.29%   |
| Ruma              | 3         | 0.29%   |
| Ripanj            | 3         | 0.29%   |
| Pirot             | 3         | 0.29%   |
| Obrenovac         | 3         | 0.29%   |
| Novi Knezevac     | 3         | 0.29%   |
| Mladenovac        | 3         | 0.29%   |
| Lozovik           | 3         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 226       | 375    | 16.31%  |
| Samsung Electronics         | 173       | 256    | 12.48%  |
| Seagate                     | 150       | 209    | 10.82%  |
| Kingston                    | 131       | 198    | 9.45%   |
| Toshiba                     | 128       | 178    | 9.24%   |
| Hitachi                     | 59        | 80     | 4.26%   |
| SanDisk                     | 55        | 76     | 3.97%   |
| SPCC                        | 38        | 56     | 2.74%   |
| SK hynix                    | 35        | 42     | 2.53%   |
| Unknown                     | 32        | 42     | 2.31%   |
| Patriot                     | 32        | 38     | 2.31%   |
| Intel                       | 30        | 44     | 2.16%   |
| Micron Technology           | 28        | 35     | 2.02%   |
| HGST                        | 24        | 35     | 1.73%   |
| Gigabyte Technology         | 22        | 29     | 1.59%   |
| Biostar                     | 18        | 22     | 1.3%    |
| A-DATA Technology           | 18        | 18     | 1.3%    |
| Transcend                   | 17        | 24     | 1.23%   |
| Crucial                     | 14        | 17     | 1.01%   |
| Maxtor                      | 11        | 12     | 0.79%   |
| Apacer                      | 10        | 12     | 0.72%   |
| KIOXIA                      | 9         | 10     | 0.65%   |
| Kingston Technology Company | 9         | 18     | 0.65%   |
| Silicon Motion              | 8         | 18     | 0.58%   |
| GeIL                        | 8         | 10     | 0.58%   |
| Fujitsu                     | 7         | 7      | 0.51%   |
| China                       | 7         | 13     | 0.51%   |
| Phison                      | 5         | 13     | 0.36%   |
| ADATA Technology            | 5         | 5      | 0.36%   |
| Unknown                     | 5         | 10     | 0.36%   |
| Phison Electronics          | 4         | 6      | 0.29%   |
| LITEON                      | 4         | 5      | 0.29%   |
| ExcelStor                   | 4         | 4      | 0.29%   |
| AMD                         | 4         | 6      | 0.29%   |
| Verbatim                    | 3         | 3      | 0.22%   |
| TwinMOS                     | 3         | 3      | 0.22%   |
| StoreJet                    | 3         | 4      | 0.22%   |
| OCZ                         | 3         | 4      | 0.22%   |
| Netac                       | 3         | 5      | 0.22%   |
| Apple                       | 3         | 4      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB SSD                       | 31        | 2.07%   |
| Kingston SA400S37240G 240GB SSD                       | 29        | 1.94%   |
| Seagate ST1000LM035-1RK172 1TB                        | 19        | 1.27%   |
| Kingston SA400S37480G 480GB SSD                       | 19        | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 18        | 1.2%    |
| Toshiba MQ01ABF050 500GB                              | 17        | 1.13%   |
| Toshiba DT01ACA100 1TB                                | 17        | 1.13%   |
| Toshiba DT01ACA050 500GB                              | 12        | 0.8%    |
| SPCC Solid State Disk 256GB                           | 11        | 0.73%   |
| Samsung SSD 860 EVO 250GB                             | 11        | 0.73%   |
| Gigabyte GP-GSTFS31240GNTD 240GB                      | 11        | 0.73%   |
| Seagate ST500LT012-1DG142 500GB                       | 9         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 9         | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB                           | 8         | 0.53%   |
| Toshiba MQ01ABD100 1TB                                | 8         | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 8         | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                        | 8         | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                        | 8         | 0.53%   |
| Samsung SSD 850 EVO 250GB                             | 8         | 0.53%   |
| Patriot Burst 240GB SSD                               | 8         | 0.53%   |
| Biostar S100-120GB                                    | 8         | 0.53%   |
| Samsung SSD 860 EVO 500GB                             | 7         | 0.47%   |
| Samsung NVMe SSD Drive 500GB                          | 7         | 0.47%   |
| Samsung NVMe SSD Drive 256GB                          | 7         | 0.47%   |
| Samsung MZALQ512HALU-000L2 512GB                      | 7         | 0.47%   |
| WDC WDS500G2B0A 500GB SSD                             | 6         | 0.4%    |
| Toshiba MQ04ABF100 1TB                                | 6         | 0.4%    |
| Toshiba HDWD110 1TB                                   | 6         | 0.4%    |
| SPCC Solid State Disk 120GB                           | 6         | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 6         | 0.4%    |
| Seagate ST500LT012-9WS142 500GB                       | 6         | 0.4%    |
| Hitachi HDS721050CLA362 500GB                         | 6         | 0.4%    |
| Gigabyte GP-GSTFS31120GNTD 120GB                      | 6         | 0.4%    |
| WDC WD3200AAJS-56B4A0 320GB                           | 5         | 0.33%   |
| WDC WD2500BEVS-22UST0 250GB                           | 5         | 0.33%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5         | 0.33%   |
| Unknown MMC Card  64GB                                | 5         | 0.33%   |
| Toshiba DT01ACA200 2TB                                | 5         | 0.33%   |
| SPCC Solid State Disk 512GB                           | 5         | 0.33%   |
| SPCC Solid State Disk 128GB                           | 5         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 199       | 338    | 33.5%   |
| Seagate             | 144       | 202    | 24.24%  |
| Toshiba             | 113       | 159    | 19.02%  |
| Hitachi             | 59        | 80     | 9.93%   |
| HGST                | 24        | 35     | 4.04%   |
| Samsung Electronics | 22        | 30     | 3.7%    |
| Maxtor              | 11        | 12     | 1.85%   |
| Fujitsu             | 7         | 7      | 1.18%   |
| ExcelStor           | 4         | 4      | 0.67%   |
| Unknown             | 2         | 2      | 0.34%   |
| JMicron Technology  | 2         | 2      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| TO Exter            | 1         | 1      | 0.17%   |
| QUANTUM             | 1         | 1      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 109       | 161    | 23.75%  |
| Samsung Electronics | 68        | 89     | 14.81%  |
| SPCC                | 37        | 55     | 8.06%   |
| Patriot             | 30        | 36     | 6.54%   |
| SanDisk             | 22        | 37     | 4.79%   |
| Gigabyte Technology | 19        | 25     | 4.14%   |
| Transcend           | 17        | 24     | 3.7%    |
| Biostar             | 17        | 21     | 3.7%    |
| WDC                 | 15        | 18     | 3.27%   |
| A-DATA Technology   | 15        | 15     | 3.27%   |
| Crucial             | 14        | 17     | 3.05%   |
| Intel               | 13        | 17     | 2.83%   |
| Apacer              | 9         | 11     | 1.96%   |
| GeIL                | 8         | 10     | 1.74%   |
| Micron Technology   | 7         | 10     | 1.53%   |
| China               | 7         | 13     | 1.53%   |
| Toshiba             | 6         | 7      | 1.31%   |
| LITEON              | 4         | 5      | 0.87%   |
| AMD                 | 4         | 6      | 0.87%   |
| Unknown             | 4         | 9      | 0.87%   |
| Verbatim            | 3         | 3      | 0.65%   |
| TwinMOS             | 3         | 3      | 0.65%   |
| StoreJet            | 3         | 4      | 0.65%   |
| SK hynix            | 3         | 3      | 0.65%   |
| OCZ                 | 3         | 4      | 0.65%   |
| Netac               | 3         | 5      | 0.65%   |
| PNY                 | 2         | 7      | 0.44%   |
| PHD 3.0             | 2         | 3      | 0.44%   |
| Lexar               | 2         | 6      | 0.44%   |
| SSSTC               | 1         | 1      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| Phison              | 1         | 1      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| LITEONIT            | 1         | 1      | 0.22%   |
| Leven               | 1         | 1      | 0.22%   |
| KingDian            | 1         | 1      | 0.22%   |
| Cyclone             | 1         | 1      | 0.22%   |
| Corsair             | 1         | 1      | 0.22%   |
| ADATA SU            | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 508       | 878    | 41.23%  |
| SSD     | 394       | 634    | 31.98%  |
| NVMe    | 298       | 444    | 24.19%  |
| MMC     | 23        | 29     | 1.87%   |
| Unknown | 9         | 13     | 0.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 717       | 1486   | 67.01%  |
| NVMe | 298       | 444    | 27.85%  |
| SAS  | 32        | 39     | 2.99%   |
| MMC  | 23        | 29     | 2.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 594       | 1020   | 66.07%  |
| 0.51-1.0   | 222       | 326    | 24.69%  |
| 1.01-2.0   | 54        | 102    | 6.01%   |
| 3.01-4.0   | 12        | 22     | 1.33%   |
| 4.01-10.0  | 8         | 16     | 0.89%   |
| 2.01-3.0   | 7         | 20     | 0.78%   |
| 10.01-20.0 | 2         | 6      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 275       | 26.19%  |
| 251-500        | 246       | 23.43%  |
| 501-1000       | 135       | 12.86%  |
| 1-20           | 106       | 10.1%   |
| 1001-2000      | 66        | 6.29%   |
| 51-100         | 63        | 6%      |
| 21-50          | 46        | 4.38%   |
| Unknown        | 46        | 4.38%   |
| More than 3000 | 35        | 3.33%   |
| 2001-3000      | 32        | 3.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 410       | 37.58%  |
| 21-50          | 182       | 16.68%  |
| 101-250        | 157       | 14.39%  |
| 51-100         | 115       | 10.54%  |
| 251-500        | 87        | 7.97%   |
| Unknown        | 46        | 4.22%   |
| 501-1000       | 39        | 3.57%   |
| 1001-2000      | 36        | 3.3%    |
| 2001-3000      | 10        | 0.92%   |
| More than 3000 | 8         | 0.73%   |
| 0              | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB           | 5         | 5      | 4.2%    |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 3      | 2.52%   |
| WDC WD2002FAEX-007BA0 2TB          | 2         | 3      | 1.68%   |
| WDC WD10EARS-00Y5B1 1TB            | 2         | 2      | 1.68%   |
| WDC WD10EALX-009BA0 1TB            | 2         | 3      | 1.68%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 2         | 2      | 1.68%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 2      | 1.68%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 5      | 1.68%   |
| Seagate ST380815AS 80GB            | 2         | 2      | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 1.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 3      | 1.68%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 2      | 1.68%   |
| Intel SSDSC2CW120A3 120GB          | 2         | 2      | 1.68%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.68%   |
| Hitachi HDP725050GLA360 500GB      | 2         | 2      | 1.68%   |
| HGST HTS725050A7E630 500GB         | 2         | 6      | 1.68%   |
| WDC WD5002AALX-00J37A0 500GB       | 1         | 1      | 0.84%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 0.84%   |
| WDC WD5000BEVT-24A0RT0 500GB       | 1         | 1      | 0.84%   |
| WDC WD5000AAKX-603CA0 500GB        | 1         | 1      | 0.84%   |
| WDC WD5000AAKX-329BA0 500GB        | 1         | 1      | 0.84%   |
| WDC WD5000AAKX-07U6AA0 500GB       | 1         | 1      | 0.84%   |
| WDC WD5000AAKS-65A7B0 500GB        | 1         | 1      | 0.84%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1         | 1      | 0.84%   |
| WDC WD5000AAKS-00TMA0 500GB        | 1         | 1      | 0.84%   |
| WDC WD40EZRX-00SPEB0 4TB           | 1         | 1      | 0.84%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 1      | 0.84%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 0.84%   |
| WDC WD3200BEKX-75B7WT0 320GB       | 1         | 1      | 0.84%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.84%   |
| WDC WD3200AVVS-63L2B0 320GB        | 1         | 1      | 0.84%   |
| WDC WD3200AVVS-56L2B0 320GB        | 1         | 1      | 0.84%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 1      | 0.84%   |
| WDC WD2003FYYS-05T9B0 2TB          | 1         | 1      | 0.84%   |
| WDC WD1600AAJS-00PSA0 160GB        | 1         | 1      | 0.84%   |
| WDC WD1600AAJS-00L7A0 160GB        | 1         | 1      | 0.84%   |
| WDC WD15EARS-00Z5B1 1TB            | 1         | 1      | 0.84%   |
| WDC WD15EARS-00MVWB0 1TB           | 1         | 1      | 0.84%   |
| WDC WD10EZEX-75WN4A0 1TB           | 1         | 1      | 0.84%   |
| WDC WD10EZEX-22MFCA0 1TB           | 1         | 1      | 0.84%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 42     | 29.82%  |
| Seagate             | 22        | 28     | 19.3%   |
| Toshiba             | 15        | 15     | 13.16%  |
| Hitachi             | 12        | 14     | 10.53%  |
| Samsung Electronics | 10        | 14     | 8.77%   |
| HGST                | 5         | 10     | 4.39%   |
| Maxtor              | 4         | 5      | 3.51%   |
| SPCC                | 2         | 2      | 1.75%   |
| Kingston            | 2         | 2      | 1.75%   |
| Intel               | 2         | 2      | 1.75%   |
| Fujitsu             | 2         | 2      | 1.75%   |
| ExcelStor           | 2         | 2      | 1.75%   |
| Crucial             | 1         | 1      | 0.88%   |
| A-DATA Technology   | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 42     | 33.33%  |
| Seagate             | 22        | 28     | 21.57%  |
| Toshiba             | 14        | 14     | 13.73%  |
| Hitachi             | 12        | 14     | 11.76%  |
| Samsung Electronics | 7         | 9      | 6.86%   |
| HGST                | 5         | 10     | 4.9%    |
| Maxtor              | 4         | 5      | 3.92%   |
| Fujitsu             | 2         | 2      | 1.96%   |
| ExcelStor           | 2         | 2      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 91        | 126    | 88.35%  |
| SSD  | 11        | 13     | 10.68%  |
| NVMe | 1         | 1      | 0.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600AAJS-00YZCA0 160GB | 1         | 1      | 50%     |
| Intel SSDSA2M080G2GC 80GB    | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| Intel  | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 553       | 1212   | 53.69%  |
| Works    | 372       | 644    | 36.12%  |
| Malfunc  | 103       | 140    | 10%     |
| Failed   | 2         | 2      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 574       | 47.48%  |
| AMD                            | 235       | 19.44%  |
| Samsung Electronics            | 101       | 8.35%   |
| SanDisk                        | 46        | 3.8%    |
| Nvidia                         | 36        | 2.98%   |
| Kingston Technology Company    | 36        | 2.98%   |
| SK hynix                       | 32        | 2.65%   |
| JMicron Technology             | 24        | 1.99%   |
| Micron Technology              | 21        | 1.74%   |
| ASMedia Technology             | 13        | 1.08%   |
| Phison Electronics             | 11        | 0.91%   |
| Toshiba America Info Systems   | 10        | 0.83%   |
| Silicon Motion                 | 10        | 0.83%   |
| Marvell Technology Group       | 10        | 0.83%   |
| KIOXIA                         | 9         | 0.74%   |
| ADATA Technology               | 6         | 0.5%    |
| VIA Technologies               | 5         | 0.41%   |
| Union Memory (Shenzhen)        | 4         | 0.33%   |
| Solidigm                       | 4         | 0.33%   |
| Shenzhen Longsys Electronics   | 3         | 0.25%   |
| Realtek Semiconductor          | 3         | 0.25%   |
| Broadcom / LSI                 | 3         | 0.25%   |
| Solid State Storage Technology | 2         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.17%   |
| LSI Logic / Symbios Logic      | 2         | 0.17%   |
| Apple                          | 2         | 0.17%   |
| Transcend                      | 1         | 0.08%   |
| Silicon Image                  | 1         | 0.08%   |
| Seagate Technology             | 1         | 0.08%   |
| Lenovo                         | 1         | 0.08%   |
| Unknown                        | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 156       | 10.83%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 44        | 3.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40        | 2.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 38        | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 37        | 2.57%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 35        | 2.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 31        | 2.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 31        | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 28        | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 27        | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 26        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 24        | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 23        | 1.6%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 22        | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 19        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 18        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 17        | 1.18%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15        | 1.04%   |
| Nvidia MCP61 SATA Controller                                                            | 15        | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 15        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 15        | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 15        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 14        | 0.97%   |
| Nvidia MCP61 IDE                                                                        | 14        | 0.97%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 14        | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 14        | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 13        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 0.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 13        | 0.9%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 12        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 12        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12        | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 0.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 10        | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 10        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 10        | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 10        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 692       | 56.63%  |
| NVMe | 302       | 24.71%  |
| IDE  | 167       | 13.67%  |
| RAID | 57        | 4.66%   |
| SCSI | 3         | 0.25%   |
| SAS  | 1         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 647       | 67.54%  |
| AMD      | 306       | 31.94%  |
| ARM      | 4         | 0.42%   |
| Qualcomm | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor           | 10        | 1.04%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 9         | 0.94%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.83%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.73%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 0.73%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.62%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 0.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 0.62%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 0.62%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 6         | 0.62%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 6         | 0.62%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 6         | 0.62%   |
| AMD FX-6300 Six-Core Processor                | 6         | 0.62%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.52%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 5         | 0.52%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 5         | 0.52%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 5         | 0.52%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.52%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 5         | 0.52%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.52%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.52%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5         | 0.52%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 5         | 0.52%   |
| AMD Ryzen 3 1200 Quad-Core Processor          | 5         | 0.52%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 4         | 0.42%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 4         | 0.42%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 4         | 0.42%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.42%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 148       | 15.42%  |
| Intel Core i7           | 127       | 13.23%  |
| AMD Ryzen 5             | 93        | 9.69%   |
| Intel Core i3           | 89        | 9.27%   |
| Other                   | 59        | 6.15%   |
| Intel Celeron           | 50        | 5.21%   |
| Intel Core 2 Duo        | 48        | 5%      |
| Intel Pentium           | 47        | 4.9%    |
| AMD Ryzen 7             | 45        | 4.69%   |
| AMD Ryzen 3             | 21        | 2.19%   |
| Intel Xeon              | 20        | 2.08%   |
| AMD FX                  | 13        | 1.35%   |
| Intel Pentium Dual-Core | 12        | 1.25%   |
| AMD Phenom II X4        | 12        | 1.25%   |
| AMD Ryzen 9             | 11        | 1.15%   |
| Intel Core 2 Quad       | 10        | 1.04%   |
| Intel Atom              | 10        | 1.04%   |
| AMD Athlon II X2        | 10        | 1.04%   |
| AMD A4                  | 10        | 1.04%   |
| AMD Athlon X4           | 9         | 0.94%   |
| AMD Athlon 64 X2        | 8         | 0.83%   |
| AMD A8                  | 8         | 0.83%   |
| Intel Pentium Silver    | 6         | 0.63%   |
| Intel Core 2            | 6         | 0.63%   |
| AMD Ryzen 5 PRO         | 6         | 0.63%   |
| AMD Athlon II X4        | 6         | 0.63%   |
| AMD E2                  | 5         | 0.52%   |
| AMD Athlon II X3        | 5         | 0.52%   |
| AMD Athlon              | 5         | 0.52%   |
| Intel Pentium Gold      | 4         | 0.42%   |
| Intel Pentium Dual      | 4         | 0.42%   |
| AMD A6                  | 4         | 0.42%   |
| AMD A10                 | 4         | 0.42%   |
| Intel Pentium M         | 3         | 0.31%   |
| AMD Ryzen 3 PRO         | 3         | 0.31%   |
| AMD E1                  | 3         | 0.31%   |
| Intel Genuine           | 2         | 0.21%   |
| Intel Core i9           | 2         | 0.21%   |
| Intel Core              | 2         | 0.21%   |
| AMD Sempron             | 2         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 386       | 40.17%  |
| 4       | 341       | 35.48%  |
| 6       | 96        | 9.99%   |
| 8       | 55        | 5.72%   |
| 1       | 29        | 3.02%   |
| 12      | 13        | 1.35%   |
| 14      | 11        | 1.14%   |
| 10      | 10        | 1.04%   |
| 3       | 10        | 1.04%   |
| 16      | 6         | 0.62%   |
| Unknown | 2         | 0.21%   |
| 32      | 1         | 0.1%    |
| 24      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 953       | 99.48%  |
| 2       | 4         | 0.42%   |
| Unknown | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 584       | 60.77%  |
| 1       | 375       | 39.02%  |
| Unknown | 2         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 932       | 97.18%  |
| Unknown        | 17        | 1.77%   |
| 32-bit         | 9         | 0.94%   |
| 64-bit         | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 347       | 34.29%  |
| 0x206a7    | 52        | 5.14%   |
| 0x306a9    | 39        | 3.85%   |
| 0x1067a    | 34        | 3.36%   |
| 0x306c3    | 30        | 2.96%   |
| 0x406e3    | 21        | 2.08%   |
| 0x806ea    | 18        | 1.78%   |
| 0x08108109 | 18        | 1.78%   |
| 0x906ea    | 17        | 1.68%   |
| 0x0800820d | 17        | 1.68%   |
| 0x6fd      | 15        | 1.48%   |
| 0x010000c8 | 15        | 1.48%   |
| 0x906e9    | 14        | 1.38%   |
| 0x806ec    | 12        | 1.19%   |
| 0x506e3    | 12        | 1.19%   |
| 0x506c9    | 12        | 1.19%   |
| 0x40651    | 12        | 1.19%   |
| 0x06001119 | 12        | 1.19%   |
| 0x806e9    | 11        | 1.09%   |
| 0x706e5    | 11        | 1.09%   |
| 0x10676    | 11        | 1.09%   |
| 0x306d4    | 10        | 0.99%   |
| 0x0a50000c | 10        | 0.99%   |
| 0x806c1    | 9         | 0.89%   |
| 0x0a50000d | 9         | 0.89%   |
| 0x08101016 | 8         | 0.79%   |
| 0x406c4    | 7         | 0.69%   |
| 0x30678    | 7         | 0.69%   |
| 0x20655    | 7         | 0.69%   |
| 0x08701021 | 7         | 0.69%   |
| 0x08600106 | 7         | 0.69%   |
| 0x08108102 | 7         | 0.69%   |
| 0x806eb    | 6         | 0.59%   |
| 0x6fb      | 6         | 0.59%   |
| 0x106e5    | 6         | 0.59%   |
| 0x06003106 | 6         | 0.59%   |
| 0xa0652    | 5         | 0.49%   |
| 0x706a8    | 5         | 0.49%   |
| 0x20652    | 5         | 0.49%   |
| 0x08608103 | 5         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 113       | 11.77%  |
| SandyBridge       | 79        | 8.23%   |
| Haswell           | 67        | 6.98%   |
| Zen+              | 58        | 6.04%   |
| Penryn            | 56        | 5.83%   |
| IvyBridge         | 53        | 5.52%   |
| Skylake           | 46        | 4.79%   |
| K10               | 46        | 4.79%   |
| Unknown           | 43        | 4.48%   |
| Zen 3             | 40        | 4.17%   |
| Core              | 32        | 3.33%   |
| Zen 2             | 31        | 3.23%   |
| Zen               | 31        | 3.23%   |
| Piledriver        | 29        | 3.02%   |
| Silvermont        | 27        | 2.81%   |
| Westmere          | 22        | 2.29%   |
| Alderlake Hybrid  | 22        | 2.29%   |
| Broadwell         | 19        | 1.98%   |
| TigerLake         | 18        | 1.88%   |
| IceLake           | 18        | 1.88%   |
| Goldmont          | 15        | 1.56%   |
| Nehalem           | 12        | 1.25%   |
| K8 Hammer         | 11        | 1.15%   |
| Goldmont plus     | 10        | 1.04%   |
| Steamroller       | 9         | 0.94%   |
| P6                | 7         | 0.73%   |
| Jaguar            | 7         | 0.73%   |
| CometLake         | 7         | 0.73%   |
| Bonnell           | 6         | 0.63%   |
| Puma              | 5         | 0.52%   |
| Excavator         | 5         | 0.52%   |
| K8 & K10 hybrid   | 3         | 0.31%   |
| Bobcat            | 3         | 0.31%   |
| Tremont           | 2         | 0.21%   |
| NetBurst          | 2         | 0.21%   |
| Meteorlake Hybrid | 2         | 0.21%   |
| K10 Llano         | 2         | 0.21%   |
| Gracemont         | 1         | 0.1%    |
| Bulldozer         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 480       | 42.55%  |
| AMD                                          | 361       | 32%     |
| Nvidia                                       | 283       | 25.09%  |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.09%   |
| VIA Technologies                             | 1         | 0.09%   |
| Matrox Electronics Systems                   | 1         | 0.09%   |
| ASPEED Technology                            | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 57        | 4.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 2.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 2.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.04%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 19        | 1.62%   |
| Intel UHD Graphics 620                                                                   | 18        | 1.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.36%   |
| Intel HD Graphics 620                                                                    | 15        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 1.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.94%   |
| Intel HD Graphics 630                                                                    | 11        | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 0.94%   |
| AMD Lucienne                                                                             | 11        | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 0.85%   |
| Intel HD Graphics 530                                                                    | 10        | 0.85%   |
| Intel HD Graphics 500                                                                    | 10        | 0.85%   |
| AMD Barcelo                                                                              | 10        | 0.85%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 9         | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.68%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 8         | 0.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 8         | 0.68%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 8         | 0.68%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 8         | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 0.68%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 8         | 0.68%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 8         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 329       | 33.95%  |
| 1 x AMD        | 281       | 29%     |
| 1 x Nvidia     | 158       | 16.31%  |
| Intel + Nvidia | 106       | 10.94%  |
| Intel + AMD    | 38        | 3.92%   |
| 2 x AMD        | 26        | 2.68%   |
| AMD + Nvidia   | 16        | 1.65%   |
| Other          | 6         | 0.62%   |
| 2 x Nvidia     | 3         | 0.31%   |
| 2 x Intel      | 2         | 0.21%   |
| 1 x VIA        | 1         | 0.1%    |
| Nvidia + XGI   | 1         | 0.1%    |
| 1 x Matrox     | 1         | 0.1%    |
| 1 x ASPEED     | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 793       | 81.17%  |
| Proprietary | 141       | 14.43%  |
| Unknown     | 43        | 4.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 510       | 50.95%  |
| 1.01-2.0   | 144       | 14.39%  |
| 0.01-0.5   | 140       | 13.99%  |
| 0.51-1.0   | 85        | 8.49%   |
| 3.01-4.0   | 73        | 7.29%   |
| 7.01-8.0   | 26        | 2.6%    |
| 5.01-6.0   | 11        | 1.1%    |
| 8.01-16.0  | 9         | 0.9%    |
| 2.01-3.0   | 3         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 133       | 12.7%   |
| AU Optronics            | 121       | 11.56%  |
| BOE                     | 93        | 8.88%   |
| Chimei Innolux          | 84        | 8.02%   |
| LG Display              | 81        | 7.74%   |
| Dell                    | 72        | 6.88%   |
| Goldstar                | 64        | 6.11%   |
| Philips                 | 54        | 5.16%   |
| Hewlett-Packard         | 31        | 2.96%   |
| Lenovo                  | 30        | 2.87%   |
| BenQ                    | 26        | 2.48%   |
| Acer                    | 23        | 2.2%    |
| Ancor Communications    | 22        | 2.1%    |
| AOC                     | 21        | 2.01%   |
| ViewSonic               | 17        | 1.62%   |
| Chi Mei Optoelectronics | 17        | 1.62%   |
| Apple                   | 14        | 1.34%   |
| ASUSTek Computer        | 13        | 1.24%   |
| PANDA                   | 12        | 1.15%   |
| Sharp                   | 11        | 1.05%   |
| LG Electronics          | 8         | 0.76%   |
| Unknown                 | 6         | 0.57%   |
| Toshiba                 | 6         | 0.57%   |
| Sony                    | 6         | 0.57%   |
| LG Philips              | 6         | 0.57%   |
| InfoVision              | 6         | 0.57%   |
| CHD                     | 5         | 0.48%   |
| Belinea                 | 5         | 0.48%   |
| OEM                     | 4         | 0.38%   |
| Gigabyte Technology     | 4         | 0.38%   |
| Fujitsu Siemens         | 4         | 0.38%   |
| CSO                     | 4         | 0.38%   |
| CPT                     | 4         | 0.38%   |
| KTC                     | 3         | 0.29%   |
| Hitachi                 | 3         | 0.29%   |
| HIC                     | 3         | 0.29%   |
| Vestel Elektronik       | 2         | 0.19%   |
| SKY                     | 2         | 0.19%   |
| RTK                     | 2         | 0.19%   |
| Medion                  | 2         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 19        | 1.76%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.93%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.93%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 7         | 0.65%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 477x268mm 21.5-inch              | 6         | 0.56%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 6         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.56%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 5         | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5         | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.46%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.46%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 5         | 0.46%   |
| Toshiba TV TSB0108 1920x540                                           | 4         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.37%   |
| Goldstar W2240 GSM57A0 1920x1080 477x268mm 21.5-inch                  | 4         | 0.37%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 4         | 0.37%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 4         | 0.37%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 4         | 0.37%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.37%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.37%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch         | 4         | 0.37%   |
| AOC Q32E2WG5B AOC3202 2560x1440 698x393mm 31.5-inch                   | 4         | 0.37%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 3         | 0.28%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 3         | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.28%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch     | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 3         | 0.28%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.28%   |
| Philips PHL 328P6A PHL0913 1920x1080 698x393mm 31.5-inch              | 3         | 0.28%   |
| Philips 220E PHLC02E 1920x1080 476x268mm 21.5-inch                    | 3         | 0.28%   |
| OEM 215_LCD_TV OEM3700 1920x1080                                      | 3         | 0.28%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.28%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 3         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 484       | 48.64%  |
| 1366x768 (WXGA)    | 187       | 18.79%  |
| 3840x2160 (4K)     | 49        | 4.92%   |
| 1280x1024 (SXGA)   | 42        | 4.22%   |
| 2560x1440 (QHD)    | 30        | 3.02%   |
| 1680x1050 (WSXGA+) | 30        | 3.02%   |
| 1920x1200 (WUXGA)  | 26        | 2.61%   |
| 1440x900 (WXGA+)   | 22        | 2.21%   |
| 1280x800 (WXGA)    | 20        | 2.01%   |
| 1600x900 (HD+)     | 18        | 1.81%   |
| 2560x1600          | 10        | 1.01%   |
| 1360x768           | 9         | 0.9%    |
| 2880x1800          | 8         | 0.8%    |
| 1920x540           | 8         | 0.8%    |
| Unknown            | 7         | 0.7%    |
| 2560x1080          | 6         | 0.6%    |
| 3840x1080          | 5         | 0.5%    |
| 1024x600           | 4         | 0.4%    |
| 2520x1680          | 3         | 0.3%    |
| 1600x1200          | 3         | 0.3%    |
| 1280x720 (HD)      | 3         | 0.3%    |
| 1024x768 (XGA)     | 3         | 0.3%    |
| 3200x2000          | 2         | 0.2%    |
| 2288x1287          | 2         | 0.2%    |
| 1400x1050          | 2         | 0.2%    |
| 7680x2160          | 1         | 0.1%    |
| 4096x2304          | 1         | 0.1%    |
| 3440x1440          | 1         | 0.1%    |
| 3360x1200          | 1         | 0.1%    |
| 3280x1080          | 1         | 0.1%    |
| 2880x1620          | 1         | 0.1%    |
| 2240x1400          | 1         | 0.1%    |
| 2160x1350          | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1834x1031          | 1         | 0.1%    |
| 1680x945           | 1         | 0.1%    |
| 1280x768           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 306       | 29.34%  |
| 24      | 89        | 8.53%   |
| 21      | 84        | 8.05%   |
| 23      | 79        | 7.57%   |
| 13      | 65        | 6.23%   |
| 17      | 59        | 5.66%   |
| 14      | 59        | 5.66%   |
| 27      | 57        | 5.47%   |
| Unknown | 40        | 3.84%   |
| 19      | 26        | 2.49%   |
| 31      | 24        | 2.3%    |
| 18      | 24        | 2.3%    |
| 22      | 21        | 2.01%   |
| 12      | 21        | 2.01%   |
| 16      | 18        | 1.73%   |
| 20      | 9         | 0.86%   |
| 72      | 8         | 0.77%   |
| 34      | 7         | 0.67%   |
| 84      | 6         | 0.58%   |
| 11      | 6         | 0.58%   |
| 32      | 5         | 0.48%   |
| 46      | 4         | 0.38%   |
| 52      | 3         | 0.29%   |
| 40      | 3         | 0.29%   |
| 10      | 3         | 0.29%   |
| 142     | 2         | 0.19%   |
| 43      | 2         | 0.19%   |
| 26      | 2         | 0.19%   |
| 25      | 2         | 0.19%   |
| 86      | 1         | 0.1%    |
| 65      | 1         | 0.1%    |
| 64      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 48      | 1         | 0.1%    |
| 47      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 33      | 1         | 0.1%    |
| 8       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 436       | 42.58%  |
| 501-600        | 211       | 20.61%  |
| 401-500        | 145       | 14.16%  |
| 201-300        | 59        | 5.76%   |
| 351-400        | 57        | 5.57%   |
| Unknown        | 40        | 3.91%   |
| 601-700        | 27        | 2.64%   |
| 1501-2000      | 14        | 1.37%   |
| 701-800        | 13        | 1.27%   |
| 1001-1500      | 13        | 1.27%   |
| 801-900        | 4         | 0.39%   |
| More than 2000 | 2         | 0.2%    |
| 901-1000       | 2         | 0.2%    |
| 101-200        | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 718       | 76.87%  |
| 16/10   | 103       | 11.03%  |
| 5/4     | 39        | 4.18%   |
| Unknown | 33        | 3.53%   |
| 3/2     | 15        | 1.61%   |
| 4/3     | 13        | 1.39%   |
| 21/9    | 7         | 0.75%   |
| 32/9    | 2         | 0.21%   |
| 1.00    | 2         | 0.21%   |
| 6/5     | 1         | 0.11%   |
| 0.56    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 306       | 29.71%  |
| 201-250        | 226       | 21.94%  |
| 81-90          | 98        | 9.51%   |
| 301-350        | 59        | 5.73%   |
| 151-200        | 50        | 4.85%   |
| 141-150        | 45        | 4.37%   |
| Unknown        | 40        | 3.88%   |
| 351-500        | 37        | 3.59%   |
| 121-130        | 33        | 3.2%    |
| 71-80          | 26        | 2.52%   |
| 251-300        | 25        | 2.43%   |
| More than 1000 | 23        | 2.23%   |
| 111-120        | 18        | 1.75%   |
| 61-70          | 17        | 1.65%   |
| 501-1000       | 12        | 1.17%   |
| 51-60          | 6         | 0.58%   |
| 41-50          | 3         | 0.29%   |
| 91-100         | 3         | 0.29%   |
| 131-140        | 2         | 0.19%   |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 343       | 34.06%  |
| 121-160       | 268       | 26.61%  |
| 101-120       | 268       | 26.61%  |
| 161-240       | 54        | 5.36%   |
| Unknown       | 40        | 3.97%   |
| 1-50          | 23        | 2.28%   |
| More than 240 | 11        | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 788       | 79.44%  |
| 2     | 149       | 15.02%  |
| 0     | 39        | 3.93%   |
| 3     | 16        | 1.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 586       | 41.53%  |
| Intel                             | 353       | 25.02%  |
| Qualcomm Atheros                  | 176       | 12.47%  |
| Broadcom                          | 69        | 4.89%   |
| MediaTek                          | 35        | 2.48%   |
| Nvidia                            | 27        | 1.91%   |
| TP-Link                           | 22        | 1.56%   |
| Ralink Technology                 | 17        | 1.2%    |
| Ralink                            | 16        | 1.13%   |
| Qualcomm Atheros Communications   | 14        | 0.99%   |
| Broadcom Limited                  | 11        | 0.78%   |
| Marvell Technology Group          | 9         | 0.64%   |
| Dell                              | 8         | 0.57%   |
| D-Link                            | 5         | 0.35%   |
| Sierra Wireless                   | 4         | 0.28%   |
| Samsung Electronics               | 4         | 0.28%   |
| Ericsson Business Mobile Networks | 4         | 0.28%   |
| ASUSTek Computer                  | 4         | 0.28%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.21%   |
| VIA Technologies                  | 3         | 0.21%   |
| JMicron Technology                | 3         | 0.21%   |
| Huawei Technologies               | 3         | 0.21%   |
| Edimax Technology                 | 3         | 0.21%   |
| ASIX Electronics                  | 3         | 0.21%   |
| Xiaomi                            | 2         | 0.14%   |
| OPPO Electronics                  | 2         | 0.14%   |
| Lenovo                            | 2         | 0.14%   |
| IMC Networks                      | 2         | 0.14%   |
| Hewlett-Packard                   | 2         | 0.14%   |
| D-Link System                     | 2         | 0.14%   |
| ZyXEL Communications              | 1         | 0.07%   |
| Texas Instruments                 | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus | 1         | 0.07%   |
| Sigma Designs                     | 1         | 0.07%   |
| Qualcomm Technologies             | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Motorola PCS                      | 1         | 0.07%   |
| Microchip Technology              | 1         | 0.07%   |
| LSI                               | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 413       | 25.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 83        | 5.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 33        | 2.05%   |
| Intel Wireless 8265 / 8275                                             | 29        | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 28        | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 28        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 26        | 1.61%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 1.43%   |
| Intel Wi-Fi 6 AX200                                                    | 22        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 15        | 0.93%   |
| Intel Wireless 8260                                                    | 15        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 14        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 14        | 0.87%   |
| Intel Wireless 7260                                                    | 14        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                          | 14        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12        | 0.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 12        | 0.74%   |
| Intel Wireless 3165                                                    | 12        | 0.74%   |
| Intel I211 Gigabit Network Connection                                  | 12        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 12        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 0.68%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 11        | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 10        | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                        | 10        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 10        | 0.62%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 9         | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.56%   |
| Intel Ethernet Connection I217-LM                                      | 9         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 8         | 0.5%    |
| Nvidia MCP61 Ethernet                                                  | 8         | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 8         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 7         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 261       | 37.83%  |
| Qualcomm Atheros                | 141       | 20.43%  |
| Realtek Semiconductor           | 110       | 15.94%  |
| Broadcom                        | 49        | 7.1%    |
| MediaTek                        | 28        | 4.06%   |
| TP-Link                         | 21        | 3.04%   |
| Ralink Technology               | 17        | 2.46%   |
| Ralink                          | 16        | 2.32%   |
| Qualcomm Atheros Communications | 14        | 2.03%   |
| Dell                            | 5         | 0.72%   |
| D-Link                          | 5         | 0.72%   |
| Sierra Wireless                 | 4         | 0.58%   |
| ASUSTek Computer                | 4         | 0.58%   |
| Edimax Technology               | 3         | 0.43%   |
| Broadcom Limited                | 3         | 0.43%   |
| IMC Networks                    | 2         | 0.29%   |
| Hewlett-Packard                 | 2         | 0.29%   |
| ZyXEL Communications            | 1         | 0.14%   |
| NetGear                         | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| Fibocom                         | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 33        | 4.76%   |
| Intel Wireless 8265 / 8275                                     | 29        | 4.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 4.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 3.75%   |
| Intel Wi-Fi 6 AX200                                            | 22        | 3.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 2.16%   |
| Intel Wireless 8260                                            | 15        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14        | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 14        | 2.02%   |
| Intel Wireless 7260                                            | 14        | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 2.02%   |
| Intel Wireless 3165                                            | 12        | 1.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 1.73%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.59%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 10        | 1.44%   |
| Qualcomm Atheros AR9271 802.11n                                | 10        | 1.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 1.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 9         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 9         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 1.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.01%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 7         | 1.01%   |
| Intel Wireless 7265                                            | 7         | 1.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 7         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.01%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 6         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.87%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 6         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 0.87%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 5         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 544       | 61.33%  |
| Intel                             | 184       | 20.74%  |
| Qualcomm Atheros                  | 50        | 5.64%   |
| Nvidia                            | 27        | 3.04%   |
| Broadcom                          | 27        | 3.04%   |
| Marvell Technology Group          | 9         | 1.01%   |
| MediaTek                          | 8         | 0.9%    |
| Broadcom Limited                  | 8         | 0.9%    |
| VIA Technologies                  | 3         | 0.34%   |
| Samsung Electronics               | 3         | 0.34%   |
| JMicron Technology                | 3         | 0.34%   |
| ASIX Electronics                  | 3         | 0.34%   |
| Xiaomi                            | 2         | 0.23%   |
| OPPO Electronics                  | 2         | 0.23%   |
| Lenovo                            | 2         | 0.23%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.11%   |
| TP-Link                           | 1         | 0.11%   |
| Sundance Technology Inc / IC Plus | 1         | 0.11%   |
| Qualcomm Technologies             | 1         | 0.11%   |
| Motorola PCS                      | 1         | 0.11%   |
| ICS Advent                        | 1         | 0.11%   |
| Huawei Technologies               | 1         | 0.11%   |
| DisplayLink                       | 1         | 0.11%   |
| D-Link System                     | 1         | 0.11%   |
| Aquantia                          | 1         | 0.11%   |
| Apple                             | 1         | 0.11%   |
| ADMtek                            | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 413       | 45.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 83        | 9.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 28        | 3.11%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 2.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12        | 1.33%   |
| Intel I211 Gigabit Network Connection                                  | 12        | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.22%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 1%      |
| Intel Ethernet Connection I217-LM                                      | 9         | 1%      |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 1%      |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1%      |
| Nvidia MCP61 Ethernet                                                  | 8         | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7         | 0.78%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 7         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.67%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 6         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.56%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.56%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.56%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                                  | 5         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 4         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 4         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.44%   |
| Intel Ethernet Connection (6) I219-V                                   | 4         | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 0.44%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.33%   |
| Nvidia MCP77 Ethernet                                                  | 3         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 858       | 55.86%  |
| WiFi     | 660       | 42.97%  |
| Modem    | 18        | 1.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 521       | 52.68%  |
| Ethernet | 467       | 47.22%  |
| Modem    | 1         | 0.1%    |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 495       | 51.56%  |
| 1     | 443       | 46.15%  |
| 0     | 10        | 1.04%   |
| 3     | 9         | 0.94%   |
| 5     | 2         | 0.21%   |
| 8     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 934       | 96.89%  |
| Yes  | 30        | 3.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 207       | 39.13%  |
| Realtek Semiconductor           | 70        | 13.23%  |
| Qualcomm Atheros Communications | 44        | 8.32%   |
| Cambridge Silicon Radio         | 33        | 6.24%   |
| Lite-On Technology              | 32        | 6.05%   |
| IMC Networks                    | 32        | 6.05%   |
| Broadcom                        | 23        | 4.35%   |
| Foxconn / Hon Hai               | 22        | 4.16%   |
| Apple                           | 13        | 2.46%   |
| ASUSTek Computer                | 8         | 1.51%   |
| MediaTek                        | 7         | 1.32%   |
| Hewlett-Packard                 | 7         | 1.32%   |
| Toshiba                         | 6         | 1.13%   |
| Dell                            | 6         | 1.13%   |
| Ralink                          | 5         | 0.95%   |
| Foxconn International           | 3         | 0.57%   |
| USI                             | 2         | 0.38%   |
| TP-Link                         | 2         | 0.38%   |
| Ralink Technology               | 2         | 0.38%   |
| Realtek                         | 1         | 0.19%   |
| Opticis                         | 1         | 0.19%   |
| Askey Computer                  | 1         | 0.19%   |
| Alps Electric                   | 1         | 0.19%   |
| Unknown                         | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 78        | 14.74%  |
| Realtek Bluetooth Radio                             | 34        | 6.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 33        | 6.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 32        | 6.05%   |
| Intel AX201 Bluetooth                               | 31        | 5.86%   |
| Intel AX200 Bluetooth                               | 22        | 4.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 3.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 3.02%   |
| Intel AX211 Bluetooth                               | 16        | 3.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 2.65%   |
| IMC Networks Wireless_Device                        | 13        | 2.46%   |
| Lite-On Bluetooth Device                            | 9         | 1.7%    |
| Intel AX210 Bluetooth                               | 9         | 1.7%    |
| IMC Networks Bluetooth Radio                        | 9         | 1.7%    |
| Realtek 802.11ac WLAN Adapter                       | 8         | 1.51%   |
| MediaTek Wireless_Device                            | 7         | 1.32%   |
| Apple Bluetooth Host Controller                     | 7         | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 6         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.13%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 1.13%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 1.13%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.95%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.95%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.95%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 4         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.76%   |
| IMC Networks Bluetooth Device                       | 4         | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.76%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.57%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 624       | 48.15%  |
| AMD                                             | 366       | 28.24%  |
| Nvidia                                          | 214       | 16.51%  |
| C-Media Electronics                             | 12        | 0.93%   |
| Logitech                                        | 8         | 0.62%   |
| Creative Labs                                   | 7         | 0.54%   |
| Generalplus Technology                          | 5         | 0.39%   |
| Focusrite-Novation                              | 5         | 0.39%   |
| VIA Technologies                                | 4         | 0.31%   |
| Hewlett-Packard                                 | 4         | 0.31%   |
| Plantronics                                     | 3         | 0.23%   |
| Microsoft                                       | 3         | 0.23%   |
| ASUSTek Computer                                | 3         | 0.23%   |
| Tenx Technology                                 | 2         | 0.15%   |
| RODE Microphones                                | 2         | 0.15%   |
| Native Instruments                              | 2         | 0.15%   |
| Micro Star International                        | 2         | 0.15%   |
| Kingston Technology                             | 2         | 0.15%   |
| JMTek                                           | 2         | 0.15%   |
| GN Netcom                                       | 2         | 0.15%   |
| Apple                                           | 2         | 0.15%   |
| XMOS                                            | 1         | 0.08%   |
| Veho                                            | 1         | 0.08%   |
| Unknown                                         | 1         | 0.08%   |
| Turtle Beach                                    | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.08%   |
| Syntek                                          | 1         | 0.08%   |
| SteelSeries ApS                                 | 1         | 0.08%   |
| Sony                                            | 1         | 0.08%   |
| SAVITECH                                        | 1         | 0.08%   |
| Realtek Semiconductor                           | 1         | 0.08%   |
| Razer USA                                       | 1         | 0.08%   |
| PreSonus Audio Electronics                      | 1         | 0.08%   |
| Oculus VR                                       | 1         | 0.08%   |
| Nordic Semiconductor ASA                        | 1         | 0.08%   |
| Meizu                                           | 1         | 0.08%   |
| M-Audio                                         | 1         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.08%   |
| LG Electronics                                  | 1         | 0.08%   |
| Lenovo                                          | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 125       | 7.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 75        | 4.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 63        | 3.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 55        | 3.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 52        | 3.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 48        | 3.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 44        | 2.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 42        | 2.63%   |
| AMD FCH Azalia Controller                                                                         | 42        | 2.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 38        | 2.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 35        | 2.19%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 34        | 2.13%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 31        | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 28        | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 1.5%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 23        | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 20        | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 1.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.13%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 1.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 1.06%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                                | 15        | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 15        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 13        | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 13        | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 0.81%   |
| Intel 200 Series PCH HD Audio                                                                     | 13        | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 13        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 134       | 21.2%   |
| Samsung Electronics | 123       | 19.46%  |
| SK hynix            | 101       | 15.98%  |
| Unknown             | 69        | 10.92%  |
| Micron Technology   | 66        | 10.44%  |
| Crucial             | 19        | 3.01%   |
| Ramaxel Technology  | 17        | 2.69%   |
| Patriot             | 16        | 2.53%   |
| Transcend           | 14        | 2.22%   |
| Corsair             | 10        | 1.58%   |
| A-DATA Technology   | 10        | 1.58%   |
| Elpida              | 9         | 1.42%   |
| Apacer              | 9         | 1.42%   |
| Unknown             | 7         | 1.11%   |
| Nanya Technology    | 6         | 0.95%   |
| G.Skill             | 4         | 0.63%   |
| GeIL                | 3         | 0.47%   |
| Unknown (06F1)      | 1         | 0.16%   |
| Unifosa             | 1         | 0.16%   |
| Swissbit            | 1         | 0.16%   |
| Silicon Power       | 1         | 0.16%   |
| SHARETRONIC         | 1         | 0.16%   |
| Ramos Technology    | 1         | 0.16%   |
| Qimonda             | 1         | 0.16%   |
| PNY                 | 1         | 0.16%   |
| Mushkin             | 1         | 0.16%   |
| KETECH              | 1         | 0.16%   |
| Exceleram           | 1         | 0.16%   |
| CSX                 | 1         | 0.16%   |
| AMD                 | 1         | 0.16%   |
| Aeneon              | 1         | 0.16%   |
| 48spaces            | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 7         | 1.01%   |
| Unknown                                                        | 7         | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 6         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 6         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 6         | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 6         | 0.86%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 6         | 0.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 6         | 0.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 6         | 0.86%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 6         | 0.86%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 6         | 0.86%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 5         | 0.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 5         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 5         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s           | 5         | 0.72%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 5         | 0.72%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 5         | 0.72%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 5         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 4         | 0.57%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 4         | 0.57%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s       | 4         | 0.57%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 4         | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 4         | 0.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 0.57%   |
| Patriot RAM 3000 C16 Series 16GB DIMM DDR4 3200MT/s            | 4         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s          | 4         | 0.57%   |
| Kingston RAM KF3200C20S4/32GX 32GB SODIMM DDR4 3200MT/s        | 4         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s          | 4         | 0.57%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 3         | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 0.43%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 3         | 0.43%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                      | 3         | 0.43%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 3         | 0.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 3         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s       | 3         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s | 3         | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 234       | 44.74%  |
| DDR3    | 171       | 32.7%   |
| DDR2    | 31        | 5.93%   |
| Unknown | 27        | 5.16%   |
| DDR5    | 16        | 3.06%   |
| SDRAM   | 13        | 2.49%   |
| LPDDR5  | 10        | 1.91%   |
| LPDDR4  | 10        | 1.91%   |
| LPDDR3  | 5         | 0.96%   |
| DDR     | 5         | 0.96%   |
| DRAM    | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 284       | 54.62%  |
| DIMM         | 198       | 38.08%  |
| Row Of Chips | 33        | 6.35%   |
| Chip         | 3         | 0.58%   |
| FB-DIMM      | 1         | 0.19%   |
| Unknown      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 195       | 33.45%  |
| 4096  | 175       | 30.02%  |
| 2048  | 90        | 15.44%  |
| 16384 | 75        | 12.86%  |
| 1024  | 25        | 4.29%   |
| 32768 | 19        | 3.26%   |
| 512   | 3         | 0.51%   |
| 3072  | 1         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 109       | 18.51%  |
| 3200    | 99        | 16.81%  |
| 2667    | 73        | 12.39%  |
| 1333    | 49        | 8.32%   |
| 2400    | 36        | 6.11%   |
| 800     | 21        | 3.57%   |
| 2133    | 19        | 3.23%   |
| 667     | 19        | 3.23%   |
| 1334    | 18        | 3.06%   |
| 3600    | 13        | 2.21%   |
| 1067    | 13        | 2.21%   |
| 3733    | 9         | 1.53%   |
| 3400    | 9         | 1.53%   |
| Unknown | 9         | 1.53%   |
| 6400    | 8         | 1.36%   |
| 5600    | 7         | 1.19%   |
| 4800    | 7         | 1.19%   |
| 3266    | 6         | 1.02%   |
| 2666    | 6         | 1.02%   |
| 4199    | 5         | 0.85%   |
| 1867    | 5         | 0.85%   |
| 1866    | 5         | 0.85%   |
| 2048    | 4         | 0.68%   |
| 4267    | 3         | 0.51%   |
| 3466    | 3         | 0.51%   |
| 2933    | 3         | 0.51%   |
| 975     | 3         | 0.51%   |
| 400     | 3         | 0.51%   |
| 3151    | 2         | 0.34%   |
| 3000    | 2         | 0.34%   |
| 2800    | 2         | 0.34%   |
| 1800    | 2         | 0.34%   |
| 1648    | 2         | 0.34%   |
| 533     | 2         | 0.34%   |
| 8533    | 1         | 0.17%   |
| 7500    | 1         | 0.17%   |
| 6000    | 1         | 0.17%   |
| 5200    | 1         | 0.17%   |
| 4333    | 1         | 0.17%   |
| 4266    | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 48.28%  |
| Canon                 | 6         | 20.69%  |
| Samsung Electronics   | 4         | 13.79%  |
| Seiko Epson           | 2         | 6.9%    |
| Lexmark International | 2         | 6.9%    |
| Xerox                 | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP LaserJet 1018                           | 3         | 10.34%  |
| Seiko Epson L365 Series                    | 2         | 6.9%    |
| HP LaserJet 1010                           | 2         | 6.9%    |
| Xerox Phaser 3140 and 3155                 | 1         | 3.45%   |
| Samsung SCX-4623 Series                    | 1         | 3.45%   |
| Samsung SCX-3400 Series                    | 1         | 3.45%   |
| Samsung ML-1660 Series                     | 1         | 3.45%   |
| Samsung M2070 Series                       | 1         | 3.45%   |
| Lexmark International Lexmark MS312dn      | 1         | 3.45%   |
| Lexmark International InkJet Color Printer | 1         | 3.45%   |
| HP LaserJet P2015 series                   | 1         | 3.45%   |
| HP LaserJet P2014                          | 1         | 3.45%   |
| HP LaserJet P1005                          | 1         | 3.45%   |
| HP LaserJet M101-M106                      | 1         | 3.45%   |
| HP LaserJet CP 1025                        | 1         | 3.45%   |
| HP LaserJet 1200                           | 1         | 3.45%   |
| HP LaserJet 1020                           | 1         | 3.45%   |
| HP HP LaserJet M14-M17                     | 1         | 3.45%   |
| HP DeskJet 845c                            | 1         | 3.45%   |
| Canon LBP810                               | 1         | 3.45%   |
| Canon LBP6030/6030B/6018L                  | 1         | 3.45%   |
| Canon LBP2900                              | 1         | 3.45%   |
| Canon iP7200 series                        | 1         | 3.45%   |
| Canon G600 series                          | 1         | 3.45%   |
| Canon CanoScan LiDE 300                    | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 9         | 60%     |
| Ultima Electronics | 2         | 13.33%  |
| Mustek Systems     | 2         | 13.33%  |
| Seiko Epson        | 1         | 6.67%   |
| Hewlett-Packard    | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 13.33%  |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 13.33%  |
| Canon CanoScan LiDE 210                                                               | 2         | 13.33%  |
| Canon CanoScan LiDE 110                                                               | 2         | 13.33%  |
| Canon CanoScan LiDE 100                                                               | 2         | 13.33%  |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 6.67%   |
| HP ScanJet 2200c                                                                      | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                                                | 1         | 6.67%   |
| Canon CanoScan LiDE 120                                                               | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 127       | 22.76%  |
| IMC Networks                           | 60        | 10.75%  |
| Realtek Semiconductor                  | 40        | 7.17%   |
| Microdia                               | 40        | 7.17%   |
| Logitech                               | 35        | 6.27%   |
| Bison Electronics                      | 35        | 6.27%   |
| Quanta                                 | 29        | 5.2%    |
| Cheng Uei Precision Industry (Foxlink) | 23        | 4.12%   |
| Syntek                                 | 21        | 3.76%   |
| Sunplus Innovation Technology          | 21        | 3.76%   |
| Suyin                                  | 20        | 3.58%   |
| Apple                                  | 14        | 2.51%   |
| Luxvisions Innotech Limited            | 11        | 1.97%   |
| Lite-On Technology                     | 10        | 1.79%   |
| KYE Systems (Mouse Systems)            | 8         | 1.43%   |
| ShineTech                              | 6         | 1.08%   |
| Acer                                   | 6         | 1.08%   |
| Silicon Motion                         | 5         | 0.9%    |
| Sonix Technology                       | 4         | 0.72%   |
| Lenovo                                 | 4         | 0.72%   |
| Importek                               | 4         | 0.72%   |
| Hewlett-Packard                        | 3         | 0.54%   |
| ALi                                    | 3         | 0.54%   |
| Alcor Micro                            | 3         | 0.54%   |
| Z-Star Microelectronics                | 2         | 0.36%   |
| Ricoh                                  | 2         | 0.36%   |
| OmniVision Technologies                | 2         | 0.36%   |
| Aveo Technology                        | 2         | 0.36%   |
| Arkmicro Technologies                  | 2         | 0.36%   |
| Xiaomi                                 | 1         | 0.18%   |
| SunplusIT                              | 1         | 0.18%   |
| Sony                                   | 1         | 0.18%   |
| Shine-optics                           | 1         | 0.18%   |
| Samsung Electronics                    | 1         | 0.18%   |
| Primax Electronics                     | 1         | 0.18%   |
| Nokia Mobile Phones                    | 1         | 0.18%   |
| Microsoft                              | 1         | 0.18%   |
| HYGD-220831-A                          | 1         | 0.18%   |
| Genesys Logic                          | 1         | 0.18%   |
| Generalplus Technology                 | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 31        | 5.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 19        | 3.4%    |
| Syntek Integrated Camera                                       | 15        | 2.68%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 2.68%   |
| Realtek Integrated_Webcam_HD                                   | 14        | 2.5%    |
| Bison Integrated Camera                                        | 13        | 2.33%   |
| Microdia Integrated_Webcam_HD                                  | 12        | 2.15%   |
| IMC Networks Integrated Camera                                 | 12        | 2.15%   |
| Logitech Webcam C270                                           | 10        | 1.79%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 1.43%   |
| Chicony HP Webcam                                              | 7         | 1.25%   |
| Quanta HD WebCam                                               | 6         | 1.07%   |
| Microdia Camera                                                | 6         | 1.07%   |
| Logitech Webcam C170                                           | 6         | 1.07%   |
| Chicony VGA Webcam                                             | 6         | 1.07%   |
| Apple Built-in iSight                                          | 6         | 1.07%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 5         | 0.89%   |
| ShineTech USB2.0 HD UVC WebCam                                 | 5         | 0.89%   |
| Realtek USB Camera                                             | 5         | 0.89%   |
| Quanta VGA WebCam                                              | 5         | 0.89%   |
| Microdia Integrated Webcam                                     | 5         | 0.89%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 0.89%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 0.89%   |
| Chicony HP HD Camera                                           | 5         | 0.89%   |
| Chicony EasyCamera                                             | 5         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 5         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 5         | 0.89%   |
| Bison Lenovo EasyCamera                                        | 5         | 0.89%   |
| Syntek EasyCamera                                              | 4         | 0.72%   |
| Sunplus ASUS Webcam                                            | 4         | 0.72%   |
| Realtek Lenovo EasyCamera                                      | 4         | 0.72%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 0.72%   |
| Quanta HD User Facing                                          | 4         | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 0.72%   |
| IMC Networks EasyCamera                                        | 4         | 0.72%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 4         | 0.72%   |
| Chicony HP Wide Vision HD Camera                               | 4         | 0.72%   |
| Chicony HD WebCam                                              | 4         | 0.72%   |
| Chicony HD User Facing                                         | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 32        | 33.68%  |
| Synaptics                          | 25        | 26.32%  |
| Shenzhen Goodix Technology         | 14        | 14.74%  |
| Upek                               | 7         | 7.37%   |
| AuthenTec                          | 6         | 6.32%   |
| Elan Microelectronics              | 4         | 4.21%   |
| LighTuning Technology              | 3         | 3.16%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.11%   |
| STMicroelectronics                 | 1         | 1.05%   |
| Microsoft                          | 1         | 1.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 12.63%  |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 11.58%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 8.42%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 6.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 5.26%   |
| Synaptics  WBDI                                                            | 5         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 4.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 4.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 3.16%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 3.16%   |
| Synaptics WBDI                                                             | 2         | 2.11%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.11%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 2.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 2.11%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.11%   |
| AuthenTec AES2810                                                          | 2         | 2.11%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.05%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.05%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.05%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.05%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.05%   |
| Synaptics UWP WBDI                                                         | 1         | 1.05%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.05%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.05%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.05%   |
| Microsoft Fingerprint Reader                                               | 1         | 1.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.05%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.05%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.05%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.05%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 19        | 30.16%  |
| Broadcom                  | 18        | 28.57%  |
| Gemalto (was Gemplus)     | 12        | 19.05%  |
| Upek                      | 3         | 4.76%   |
| OmniKey                   | 3         | 4.76%   |
| O2 Micro                  | 2         | 3.17%   |
| Lenovo                    | 2         | 3.17%   |
| Yubico.com                | 1         | 1.59%   |
| Realtek Semiconductor     | 1         | 1.59%   |
| Precise Biometrics        | 1         | 1.59%   |
| Fujitsu Siemens Computers | 1         | 1.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 30.16%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 12        | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 7.94%   |
| Broadcom 5880                                                                | 5         | 7.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 6.35%   |
| Broadcom 58200                                                               | 4         | 6.35%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.17%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.17%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.59%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.59%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader                   | 1         | 1.59%   |
| OmniKey CardMan 4321                                                         | 1         | 1.59%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.59%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 1.59%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 709       | 71.62%  |
| 1     | 227       | 22.93%  |
| 2     | 44        | 4.44%   |
| 3     | 6         | 0.61%   |
| 4     | 3         | 0.3%    |
| 8     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 95        | 28.27%  |
| Graphics card            | 83        | 24.7%   |
| Chipcard                 | 54        | 16.07%  |
| Net/wireless             | 40        | 11.9%   |
| Multimedia controller    | 14        | 4.17%   |
| Bluetooth                | 11        | 3.27%   |
| Communication controller | 8         | 2.38%   |
| Sound                    | 7         | 2.08%   |
| Camera                   | 7         | 2.08%   |
| Unassigned class         | 4         | 1.19%   |
| Card reader              | 4         | 1.19%   |
| Net/ethernet             | 3         | 0.89%   |
| Storage                  | 2         | 0.6%    |
| Modem                    | 2         | 0.6%    |
| Storage/ide              | 1         | 0.3%    |
| Dvb card                 | 1         | 0.3%    |

