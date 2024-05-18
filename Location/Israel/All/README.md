Linux in Israel - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Israel.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Israel/Desktop/README.md) and [notebooks](/Location/Israel/Notebook/README.md).

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

Total: 1174

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | DH77EB AAG39073-304         | Desktop     | [6fd6f40abe](https://linux-hardware.org/?probe=6fd6f40abe) | May 08, 2024 |
| N-one         | Nbook Ultra                 | Notebook    | [ae1609d065](https://linux-hardware.org/?probe=ae1609d065) | May 03, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [ab7c916d4c](https://linux-hardware.org/?probe=ab7c916d4c) | Apr 30, 2024 |
| Acer          | Aspire A115-32              | Notebook    | [32a4949c7c](https://linux-hardware.org/?probe=32a4949c7c) | Apr 30, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [44057fd7b0](https://linux-hardware.org/?probe=44057fd7b0) | Apr 30, 2024 |
| MSI           | H170M PRO-VDH               | Desktop     | [88dbd5e70e](https://linux-hardware.org/?probe=88dbd5e70e) | Apr 29, 2024 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [14706b4b9f](https://linux-hardware.org/?probe=14706b4b9f) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [dfcd535d56](https://linux-hardware.org/?probe=dfcd535d56) | Apr 27, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [8eb518c57d](https://linux-hardware.org/?probe=8eb518c57d) | Apr 26, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [82c3a3a90b](https://linux-hardware.org/?probe=82c3a3a90b) | Apr 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55dc7f440b](https://linux-hardware.org/?probe=55dc7f440b) | Apr 24, 2024 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [8031865fea](https://linux-hardware.org/?probe=8031865fea) | Apr 23, 2024 |
| Lenovo        | IdeaPad Pro 5 14IRH8 83A... | Notebook    | [d53dd10be1](https://linux-hardware.org/?probe=d53dd10be1) | Apr 23, 2024 |
| Lenovo        | B50-10 80QR                 | Notebook    | [3ac8b8986f](https://linux-hardware.org/?probe=3ac8b8986f) | Apr 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [a7180ee8da](https://linux-hardware.org/?probe=a7180ee8da) | Apr 23, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [4f61acab6e](https://linux-hardware.org/?probe=4f61acab6e) | Apr 19, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [267091524b](https://linux-hardware.org/?probe=267091524b) | Apr 18, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [8c33938518](https://linux-hardware.org/?probe=8c33938518) | Apr 13, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [21882b12a8](https://linux-hardware.org/?probe=21882b12a8) | Apr 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [a75cf3dc0f](https://linux-hardware.org/?probe=a75cf3dc0f) | Apr 10, 2024 |
| Dell          | 0KP561                      | Desktop     | [dd6f49d82f](https://linux-hardware.org/?probe=dd6f49d82f) | Apr 06, 2024 |
| Lenovo        | ThinkPad Edge 021722G       | Notebook    | [c737a0d5d1](https://linux-hardware.org/?probe=c737a0d5d1) | Apr 06, 2024 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8603f205ba](https://linux-hardware.org/?probe=8603f205ba) | Apr 05, 2024 |
| Lenovo        | Yoga 500-15ISK 80R6         | Notebook    | [a3712304cd](https://linux-hardware.org/?probe=a3712304cd) | Apr 05, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [690e191e65](https://linux-hardware.org/?probe=690e191e65) | Mar 26, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [8f0042ce48](https://linux-hardware.org/?probe=8f0042ce48) | Mar 25, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [d51e75a4b6](https://linux-hardware.org/?probe=d51e75a4b6) | Mar 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [0cee79fd45](https://linux-hardware.org/?probe=0cee79fd45) | Mar 24, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a72ba0acf1](https://linux-hardware.org/?probe=a72ba0acf1) | Mar 20, 2024 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [13aa36af3e](https://linux-hardware.org/?probe=13aa36af3e) | Mar 20, 2024 |
| Nvidia        | Tegra                       | Soc         | [08cba116d3](https://linux-hardware.org/?probe=08cba116d3) | Mar 19, 2024 |
| Nvidia        | Tegra                       | Soc         | [bfafae4c46](https://linux-hardware.org/?probe=bfafae4c46) | Mar 19, 2024 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [972b9375c7](https://linux-hardware.org/?probe=972b9375c7) | Mar 16, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [57bcbad84b](https://linux-hardware.org/?probe=57bcbad84b) | Mar 14, 2024 |
| Lenovo        | ThinkPad T420 4178B9G       | Notebook    | [6c729a3045](https://linux-hardware.org/?probe=6c729a3045) | Mar 13, 2024 |
| HP            | ProBook 6450b               | Notebook    | [6fe298067d](https://linux-hardware.org/?probe=6fe298067d) | Mar 13, 2024 |
| Lenovo        | 3176 SDK0K17763 WIN 1801... | Desktop     | [51143831ed](https://linux-hardware.org/?probe=51143831ed) | Mar 12, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [859c361cb9](https://linux-hardware.org/?probe=859c361cb9) | Mar 12, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [120f62e576](https://linux-hardware.org/?probe=120f62e576) | Mar 08, 2024 |
| AMI           | PC1068                      | Notebook    | [9b34e1b326](https://linux-hardware.org/?probe=9b34e1b326) | Mar 07, 2024 |
| Dell          | 0NC2VH A01                  | Desktop     | [3b3cdc41db](https://linux-hardware.org/?probe=3b3cdc41db) | Mar 07, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [6cffe59389](https://linux-hardware.org/?probe=6cffe59389) | Mar 02, 2024 |
| Gigabyte      | Z490 VISION G               | Desktop     | [23347b4c30](https://linux-hardware.org/?probe=23347b4c30) | Mar 02, 2024 |
| Gigabyte      | Z490 VISION G               | Desktop     | [f202c83002](https://linux-hardware.org/?probe=f202c83002) | Mar 02, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [b827b5e796](https://linux-hardware.org/?probe=b827b5e796) | Feb 29, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [20be6de7bc](https://linux-hardware.org/?probe=20be6de7bc) | Feb 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [f03ada23b3](https://linux-hardware.org/?probe=f03ada23b3) | Feb 27, 2024 |
| Lenovo        | ThinkPad T420 4178B9G       | Notebook    | [c3206e3d16](https://linux-hardware.org/?probe=c3206e3d16) | Feb 26, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [4141eaaff5](https://linux-hardware.org/?probe=4141eaaff5) | Feb 25, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [c3f8f76b3a](https://linux-hardware.org/?probe=c3f8f76b3a) | Feb 24, 2024 |
| Dell          | Vostro 14 5401              | Notebook    | [e24927a5e5](https://linux-hardware.org/?probe=e24927a5e5) | Feb 19, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [6e61ee4b06](https://linux-hardware.org/?probe=6e61ee4b06) | Feb 18, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [2814bf63c1](https://linux-hardware.org/?probe=2814bf63c1) | Feb 18, 2024 |
| Lenovo        | ThinkPad T420 4178B9G       | Notebook    | [cce168db8a](https://linux-hardware.org/?probe=cce168db8a) | Feb 17, 2024 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [f940559e53](https://linux-hardware.org/?probe=f940559e53) | Feb 16, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [9adf8fd817](https://linux-hardware.org/?probe=9adf8fd817) | Feb 12, 2024 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [7841583f57](https://linux-hardware.org/?probe=7841583f57) | Feb 12, 2024 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [082308a172](https://linux-hardware.org/?probe=082308a172) | Feb 12, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [953b2c870f](https://linux-hardware.org/?probe=953b2c870f) | Feb 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [621267c761](https://linux-hardware.org/?probe=621267c761) | Feb 09, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [44bda25372](https://linux-hardware.org/?probe=44bda25372) | Feb 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [bb080b509b](https://linux-hardware.org/?probe=bb080b509b) | Feb 07, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [87f113db8c](https://linux-hardware.org/?probe=87f113db8c) | Feb 03, 2024 |
| Lenovo        | V14 G4 IRU 83A0             | Notebook    | [4f65dbee97](https://linux-hardware.org/?probe=4f65dbee97) | Feb 03, 2024 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | Notebook    | [001809149c](https://linux-hardware.org/?probe=001809149c) | Jan 31, 2024 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [d3aaef580d](https://linux-hardware.org/?probe=d3aaef580d) | Jan 28, 2024 |
| HP            | Pavilion 15                 | Notebook    | [3aed9dffe5](https://linux-hardware.org/?probe=3aed9dffe5) | Jan 26, 2024 |
| HP            | Pavilion 15                 | Notebook    | [5d449f9a23](https://linux-hardware.org/?probe=5d449f9a23) | Jan 26, 2024 |
| Apple         | Mac-F2208EC8                | Mini pc     | [fff575809c](https://linux-hardware.org/?probe=fff575809c) | Jan 25, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [a80c29ee33](https://linux-hardware.org/?probe=a80c29ee33) | Jan 23, 2024 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [27878d88fd](https://linux-hardware.org/?probe=27878d88fd) | Jan 23, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [a84ee0f485](https://linux-hardware.org/?probe=a84ee0f485) | Jan 23, 2024 |
| Lenovo        | IdeaPad Slim 3 16IRU8 82... | Notebook    | [7c0ccbc993](https://linux-hardware.org/?probe=7c0ccbc993) | Jan 17, 2024 |
| Lenovo        | LOQ 16IRH8 82XW             | Notebook    | [4bebc58063](https://linux-hardware.org/?probe=4bebc58063) | Jan 15, 2024 |
| Lenovo        | LOQ 16IRH8 82XW             | Notebook    | [2eef3e875d](https://linux-hardware.org/?probe=2eef3e875d) | Jan 15, 2024 |
| ASUSTek       | ROG Strix G532LW_G532LW     | Notebook    | [c2778b6624](https://linux-hardware.org/?probe=c2778b6624) | Jan 13, 2024 |
| Dell          | G5 5587                     | Notebook    | [a1342378d3](https://linux-hardware.org/?probe=a1342378d3) | Jan 10, 2024 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [26b15c1102](https://linux-hardware.org/?probe=26b15c1102) | Jan 08, 2024 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [042f4d56ce](https://linux-hardware.org/?probe=042f4d56ce) | Jan 06, 2024 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [3607077350](https://linux-hardware.org/?probe=3607077350) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [f42a6325e3](https://linux-hardware.org/?probe=f42a6325e3) | Dec 29, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [0d4c53d42f](https://linux-hardware.org/?probe=0d4c53d42f) | Dec 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [94cf6bda69](https://linux-hardware.org/?probe=94cf6bda69) | Dec 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [69ec584b3a](https://linux-hardware.org/?probe=69ec584b3a) | Dec 25, 2023 |
| Lenovo        | Unknown                     | Notebook    | [9faf2278bb](https://linux-hardware.org/?probe=9faf2278bb) | Dec 24, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [5267b86c06](https://linux-hardware.org/?probe=5267b86c06) | Dec 24, 2023 |
| Gigabyte      | B460M GAMING HD             | Desktop     | [6669971369](https://linux-hardware.org/?probe=6669971369) | Dec 23, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9425eb3c77](https://linux-hardware.org/?probe=9425eb3c77) | Dec 23, 2023 |
| Lenovo        | M30-70 80H8                 | Notebook    | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [2464a532b8](https://linux-hardware.org/?probe=2464a532b8) | Dec 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7a4d520ba9](https://linux-hardware.org/?probe=7a4d520ba9) | Dec 20, 2023 |
| Intel         | H61                         | Desktop     | [01b739e240](https://linux-hardware.org/?probe=01b739e240) | Dec 20, 2023 |
| Lenovo        | 310C SDK0J40705 WIN 3425... | Desktop     | [c1ee1cd84d](https://linux-hardware.org/?probe=c1ee1cd84d) | Dec 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [c20f7cf0e0](https://linux-hardware.org/?probe=c20f7cf0e0) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [20edb747d9](https://linux-hardware.org/?probe=20edb747d9) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [44c8944047](https://linux-hardware.org/?probe=44c8944047) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1c015093b2](https://linux-hardware.org/?probe=1c015093b2) | Dec 18, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [22d7c1e77c](https://linux-hardware.org/?probe=22d7c1e77c) | Dec 16, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| HP            | 18E4                        | Desktop     | [1dd0e805dc](https://linux-hardware.org/?probe=1dd0e805dc) | Dec 13, 2023 |
| Acer          | Predator G3610              | Desktop     | [0a8a3e6bc5](https://linux-hardware.org/?probe=0a8a3e6bc5) | Dec 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [9bb3c76c9f](https://linux-hardware.org/?probe=9bb3c76c9f) | Dec 10, 2023 |
| ASUSTek       | D540MA-C                    | Desktop     | [a5beb93a51](https://linux-hardware.org/?probe=a5beb93a51) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [ddfffa5172](https://linux-hardware.org/?probe=ddfffa5172) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [eea00eb64c](https://linux-hardware.org/?probe=eea00eb64c) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5940ba1d2c](https://linux-hardware.org/?probe=5940ba1d2c) | Dec 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ee3494fa57](https://linux-hardware.org/?probe=ee3494fa57) | Dec 06, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [a7dd623bb6](https://linux-hardware.org/?probe=a7dd623bb6) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [d28a7f3ad6](https://linux-hardware.org/?probe=d28a7f3ad6) | Dec 04, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [20e77986a2](https://linux-hardware.org/?probe=20e77986a2) | Dec 03, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [55eb62ad2f](https://linux-hardware.org/?probe=55eb62ad2f) | Dec 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8952a98c](https://linux-hardware.org/?probe=ff8952a98c) | Dec 01, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [dac97296b0](https://linux-hardware.org/?probe=dac97296b0) | Nov 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [be36e8725c](https://linux-hardware.org/?probe=be36e8725c) | Nov 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [a719bb0ba3](https://linux-hardware.org/?probe=a719bb0ba3) | Nov 25, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a59b920838](https://linux-hardware.org/?probe=a59b920838) | Nov 24, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d188fc3095](https://linux-hardware.org/?probe=d188fc3095) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [ab7968d6da](https://linux-hardware.org/?probe=ab7968d6da) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [95f01d6e47](https://linux-hardware.org/?probe=95f01d6e47) | Nov 15, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [f191f17f2a](https://linux-hardware.org/?probe=f191f17f2a) | Nov 14, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [a814c93afe](https://linux-hardware.org/?probe=a814c93afe) | Nov 09, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [74a1a56aff](https://linux-hardware.org/?probe=74a1a56aff) | Oct 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [42a94f2f97](https://linux-hardware.org/?probe=42a94f2f97) | Oct 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [37e69bd8a8](https://linux-hardware.org/?probe=37e69bd8a8) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| HP            | 83EB                        | All in one  | [f655dc8e65](https://linux-hardware.org/?probe=f655dc8e65) | Oct 18, 2023 |
| MSI           | MS-1T31                     | Desktop     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [9ed8384df0](https://linux-hardware.org/?probe=9ed8384df0) | Oct 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5b710d03c5](https://linux-hardware.org/?probe=5b710d03c5) | Oct 09, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [3dc549dba2](https://linux-hardware.org/?probe=3dc549dba2) | Oct 09, 2023 |
| Dell          | Latitude 5411               | Notebook    | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [05d87a2b59](https://linux-hardware.org/?probe=05d87a2b59) | Oct 08, 2023 |
| Dell          | Latitude 7400               | Notebook    | [1c4da154d8](https://linux-hardware.org/?probe=1c4da154d8) | Oct 07, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [7480d29d9f](https://linux-hardware.org/?probe=7480d29d9f) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d5b22876c6](https://linux-hardware.org/?probe=d5b22876c6) | Oct 04, 2023 |
| Dell          | Precision 5750              | Notebook    | [839fea4442](https://linux-hardware.org/?probe=839fea4442) | Oct 04, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [9dc3e0f9f9](https://linux-hardware.org/?probe=9dc3e0f9f9) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [18c399ea1e](https://linux-hardware.org/?probe=18c399ea1e) | Oct 04, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [3d7d389342](https://linux-hardware.org/?probe=3d7d389342) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4095fbc19e](https://linux-hardware.org/?probe=4095fbc19e) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [faf68444bc](https://linux-hardware.org/?probe=faf68444bc) | Sep 24, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d3f5dd9d13](https://linux-hardware.org/?probe=d3f5dd9d13) | Sep 19, 2023 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [264e42215e](https://linux-hardware.org/?probe=264e42215e) | Sep 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [243f46cfa8](https://linux-hardware.org/?probe=243f46cfa8) | Sep 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5cd83bcad9](https://linux-hardware.org/?probe=5cd83bcad9) | Sep 15, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [951faca7d0](https://linux-hardware.org/?probe=951faca7d0) | Sep 11, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [433e6a45a9](https://linux-hardware.org/?probe=433e6a45a9) | Sep 11, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [139a93ab8b](https://linux-hardware.org/?probe=139a93ab8b) | Sep 09, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [3eab920cfc](https://linux-hardware.org/?probe=3eab920cfc) | Sep 07, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [29d9f2566a](https://linux-hardware.org/?probe=29d9f2566a) | Sep 06, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [5c165fd73b](https://linux-hardware.org/?probe=5c165fd73b) | Sep 06, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [681020d244](https://linux-hardware.org/?probe=681020d244) | Sep 01, 2023 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [dc7b90d27f](https://linux-hardware.org/?probe=dc7b90d27f) | Sep 01, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [b37d00fb4d](https://linux-hardware.org/?probe=b37d00fb4d) | Sep 01, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [c1a4e5d47f](https://linux-hardware.org/?probe=c1a4e5d47f) | Aug 30, 2023 |
| ASUSTek       | D540MA-C                    | Desktop     | [67eb1455a6](https://linux-hardware.org/?probe=67eb1455a6) | Aug 30, 2023 |
| Dell          | 0X75JG A01                  | Desktop     | [bdf9baca2f](https://linux-hardware.org/?probe=bdf9baca2f) | Aug 29, 2023 |
| HP            | 255 G2                      | Notebook    | [23bf2dd515](https://linux-hardware.org/?probe=23bf2dd515) | Aug 29, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3c5aa8e05a](https://linux-hardware.org/?probe=3c5aa8e05a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [1562efcaf2](https://linux-hardware.org/?probe=1562efcaf2) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [e45572b49a](https://linux-hardware.org/?probe=e45572b49a) | Aug 23, 2023 |
| Dell          | 0215PR A02                  | Desktop     | [dd5966ce9b](https://linux-hardware.org/?probe=dd5966ce9b) | Aug 23, 2023 |
| ASUSTek       | Z10PG-D24 Series            | Desktop     | [127be55832](https://linux-hardware.org/?probe=127be55832) | Aug 23, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [a554b5fcd4](https://linux-hardware.org/?probe=a554b5fcd4) | Aug 22, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [71520ab551](https://linux-hardware.org/?probe=71520ab551) | Aug 22, 2023 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [3b1c4bacb9](https://linux-hardware.org/?probe=3b1c4bacb9) | Aug 21, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [a662b29087](https://linux-hardware.org/?probe=a662b29087) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [97ed27473e](https://linux-hardware.org/?probe=97ed27473e) | Aug 20, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [28a27adc22](https://linux-hardware.org/?probe=28a27adc22) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [498c86055c](https://linux-hardware.org/?probe=498c86055c) | Aug 19, 2023 |
| Lenovo        | ThinkPad T440p 20AN007BI... | Notebook    | [7a389ac976](https://linux-hardware.org/?probe=7a389ac976) | Aug 19, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [41bbf2a956](https://linux-hardware.org/?probe=41bbf2a956) | Aug 14, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [8ef1bbdcec](https://linux-hardware.org/?probe=8ef1bbdcec) | Aug 13, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [8360dc045f](https://linux-hardware.org/?probe=8360dc045f) | Aug 06, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [cad443cf78](https://linux-hardware.org/?probe=cad443cf78) | Aug 06, 2023 |
| HP            | 805D                        | Desktop     | [672e431e69](https://linux-hardware.org/?probe=672e431e69) | Aug 06, 2023 |
| Dell          | Latitude 5480               | Notebook    | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Lenovo        | ThinkPad X280 20KES3D900    | Notebook    | [865dbfa247](https://linux-hardware.org/?probe=865dbfa247) | Aug 03, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | Desktop     | [0e28c2aae2](https://linux-hardware.org/?probe=0e28c2aae2) | Aug 02, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0be5bf84c6](https://linux-hardware.org/?probe=0be5bf84c6) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [9920824f1f](https://linux-hardware.org/?probe=9920824f1f) | Jul 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [4172f7fd39](https://linux-hardware.org/?probe=4172f7fd39) | Jul 21, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [7b7cf50cba](https://linux-hardware.org/?probe=7b7cf50cba) | Jul 18, 2023 |
| Lenovo        | ThinkPad X240 20AMA04FIV    | Notebook    | [e16d9ae667](https://linux-hardware.org/?probe=e16d9ae667) | Jul 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| HP            | 8267 A01                    | Mini pc     | [442a7f8911](https://linux-hardware.org/?probe=442a7f8911) | Jul 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [5ac5b565cd](https://linux-hardware.org/?probe=5ac5b565cd) | Jul 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f79821f2eb](https://linux-hardware.org/?probe=f79821f2eb) | Jul 09, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f003f0aa32](https://linux-hardware.org/?probe=f003f0aa32) | Jul 06, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f3828ea18b](https://linux-hardware.org/?probe=f3828ea18b) | Jul 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [a39f1dd1ad](https://linux-hardware.org/?probe=a39f1dd1ad) | Jul 04, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [7aed7e46ad](https://linux-hardware.org/?probe=7aed7e46ad) | Jul 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [a4a8cc1e65](https://linux-hardware.org/?probe=a4a8cc1e65) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [48b0ff43fa](https://linux-hardware.org/?probe=48b0ff43fa) | Jun 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [d5cb3d4bfa](https://linux-hardware.org/?probe=d5cb3d4bfa) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L50-A         | Notebook    | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1a8f2401f1](https://linux-hardware.org/?probe=1a8f2401f1) | Jun 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [a9079161b0](https://linux-hardware.org/?probe=a9079161b0) | Jun 23, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | Notebook    | [a2e5b66940](https://linux-hardware.org/?probe=a2e5b66940) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [6c260b1543](https://linux-hardware.org/?probe=6c260b1543) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7c906bbd1c](https://linux-hardware.org/?probe=7c906bbd1c) | Jun 20, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [65385cc189](https://linux-hardware.org/?probe=65385cc189) | Jun 19, 2023 |
| Framework     | Laptop                      | Notebook    | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| Razer         | Blade Stealth               | Notebook    | [f218e04a1c](https://linux-hardware.org/?probe=f218e04a1c) | Jun 14, 2023 |
| Google        | Atlas                       | Notebook    | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [d183d47822](https://linux-hardware.org/?probe=d183d47822) | Jun 12, 2023 |
| Dell          | Latitude 7440               | Notebook    | [f63ada6c61](https://linux-hardware.org/?probe=f63ada6c61) | Jun 10, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [9e3dfb25be](https://linux-hardware.org/?probe=9e3dfb25be) | Jun 09, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e7c8a1c727](https://linux-hardware.org/?probe=e7c8a1c727) | Jun 06, 2023 |
| Lenovo        | ThinkPad P51 20HH0011US     | Notebook    | [4766608bc1](https://linux-hardware.org/?probe=4766608bc1) | Jun 06, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [bb29d15c61](https://linux-hardware.org/?probe=bb29d15c61) | Jun 05, 2023 |
| Huanan        | X79 V7.11                   | Desktop     | [79bbc880ba](https://linux-hardware.org/?probe=79bbc880ba) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [312b05f0a4](https://linux-hardware.org/?probe=312b05f0a4) | May 29, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [16d7a61394](https://linux-hardware.org/?probe=16d7a61394) | May 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [9cba800830](https://linux-hardware.org/?probe=9cba800830) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3c3f22e8c7](https://linux-hardware.org/?probe=3c3f22e8c7) | May 17, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [00e3bf6a3e](https://linux-hardware.org/?probe=00e3bf6a3e) | May 17, 2023 |
| Dell          | Latitude 5401               | Notebook    | [4304efbed6](https://linux-hardware.org/?probe=4304efbed6) | May 15, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [423359d677](https://linux-hardware.org/?probe=423359d677) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [0b26ce1a71](https://linux-hardware.org/?probe=0b26ce1a71) | May 12, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [c821704a04](https://linux-hardware.org/?probe=c821704a04) | May 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [9bd04974e8](https://linux-hardware.org/?probe=9bd04974e8) | May 09, 2023 |
| MSI           | H61M-E23                    | Desktop     | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Razer         | Blade                       | Notebook    | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [b577b4aa25](https://linux-hardware.org/?probe=b577b4aa25) | May 06, 2023 |
| Apple         | MacBook10,1                 | Notebook    | [b951048d8f](https://linux-hardware.org/?probe=b951048d8f) | May 05, 2023 |
| Apple         | MacBook10,1                 | Notebook    | [6796aa4cf0](https://linux-hardware.org/?probe=6796aa4cf0) | May 05, 2023 |
| Acer          | Aspire one                  | Notebook    | [90d59ac61a](https://linux-hardware.org/?probe=90d59ac61a) | May 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [aeabc8c63c](https://linux-hardware.org/?probe=aeabc8c63c) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [18de5959b7](https://linux-hardware.org/?probe=18de5959b7) | May 01, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [0aa17c06c5](https://linux-hardware.org/?probe=0aa17c06c5) | Apr 30, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d8af950fd8](https://linux-hardware.org/?probe=d8af950fd8) | Apr 28, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [854cf327d8](https://linux-hardware.org/?probe=854cf327d8) | Apr 27, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d805c85a12](https://linux-hardware.org/?probe=d805c85a12) | Apr 24, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [b80d03be6d](https://linux-hardware.org/?probe=b80d03be6d) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [09d116d762](https://linux-hardware.org/?probe=09d116d762) | Apr 23, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2afc5398b8](https://linux-hardware.org/?probe=2afc5398b8) | Apr 22, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [1cb8a5dfb4](https://linux-hardware.org/?probe=1cb8a5dfb4) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [0baff3522f](https://linux-hardware.org/?probe=0baff3522f) | Apr 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [56768ba5a6](https://linux-hardware.org/?probe=56768ba5a6) | Apr 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | Notebook    | [5a17f65715](https://linux-hardware.org/?probe=5a17f65715) | Apr 14, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [c59729f9d2](https://linux-hardware.org/?probe=c59729f9d2) | Apr 14, 2023 |
| Dell          | Latitude 5491               | Notebook    | [ef97e6890a](https://linux-hardware.org/?probe=ef97e6890a) | Apr 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| Intel         | D945GCCR AAD78647-301       | Desktop     | [fac1992089](https://linux-hardware.org/?probe=fac1992089) | Apr 13, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [917791ff47](https://linux-hardware.org/?probe=917791ff47) | Apr 12, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [e9790ea3b6](https://linux-hardware.org/?probe=e9790ea3b6) | Apr 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc28f6d3f0](https://linux-hardware.org/?probe=fc28f6d3f0) | Apr 08, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [1927fa08d1](https://linux-hardware.org/?probe=1927fa08d1) | Apr 07, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c871e7c68b](https://linux-hardware.org/?probe=c871e7c68b) | Apr 07, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | 8455                        | Desktop     | [a52e3d086a](https://linux-hardware.org/?probe=a52e3d086a) | Apr 04, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f0d73d9284](https://linux-hardware.org/?probe=f0d73d9284) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| ASUSTek       | PN51-S1                     | Mini pc     | [2b534dd0fa](https://linux-hardware.org/?probe=2b534dd0fa) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [4cfac9a162](https://linux-hardware.org/?probe=4cfac9a162) | Mar 30, 2023 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [507f441bfc](https://linux-hardware.org/?probe=507f441bfc) | Mar 30, 2023 |
| Acer          | Aspire 5820                 | Notebook    | [3e0e45bc17](https://linux-hardware.org/?probe=3e0e45bc17) | Mar 26, 2023 |
| ASUSTek       | PN62                        | Mini pc     | [9cd806cb31](https://linux-hardware.org/?probe=9cd806cb31) | Mar 20, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [923aa59ad5](https://linux-hardware.org/?probe=923aa59ad5) | Mar 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [5667e8416e](https://linux-hardware.org/?probe=5667e8416e) | Mar 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [2c2920d462](https://linux-hardware.org/?probe=2c2920d462) | Mar 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [28769bd85b](https://linux-hardware.org/?probe=28769bd85b) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [76054930ac](https://linux-hardware.org/?probe=76054930ac) | Mar 12, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [a925c8a320](https://linux-hardware.org/?probe=a925c8a320) | Mar 12, 2023 |
| Gigabyte      | AORUS 17G XC                | Notebook    | [fb998b9957](https://linux-hardware.org/?probe=fb998b9957) | Mar 12, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ac772ea51f](https://linux-hardware.org/?probe=ac772ea51f) | Mar 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [35a78f2cf1](https://linux-hardware.org/?probe=35a78f2cf1) | Mar 08, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [4e05d0a0e9](https://linux-hardware.org/?probe=4e05d0a0e9) | Mar 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [c0e9304de5](https://linux-hardware.org/?probe=c0e9304de5) | Mar 01, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [3db8300147](https://linux-hardware.org/?probe=3db8300147) | Mar 01, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [2d713931d2](https://linux-hardware.org/?probe=2d713931d2) | Feb 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [dd5ce2c6db](https://linux-hardware.org/?probe=dd5ce2c6db) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [677e93841e](https://linux-hardware.org/?probe=677e93841e) | Feb 27, 2023 |
| HP            | Pavilion TS 14              | Notebook    | [37296c42c3](https://linux-hardware.org/?probe=37296c42c3) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [d3b6621252](https://linux-hardware.org/?probe=d3b6621252) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [323b6463a9](https://linux-hardware.org/?probe=323b6463a9) | Feb 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b0436b55d](https://linux-hardware.org/?probe=4b0436b55d) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a4c4313238](https://linux-hardware.org/?probe=a4c4313238) | Feb 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [a459216464](https://linux-hardware.org/?probe=a459216464) | Feb 21, 2023 |
| Alienware     | 15 R2                       | Notebook    | [96aa09ae59](https://linux-hardware.org/?probe=96aa09ae59) | Feb 21, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d1f67d5e08](https://linux-hardware.org/?probe=d1f67d5e08) | Feb 21, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7415192b86](https://linux-hardware.org/?probe=7415192b86) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [e958da375f](https://linux-hardware.org/?probe=e958da375f) | Feb 19, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [e47bb0ee84](https://linux-hardware.org/?probe=e47bb0ee84) | Feb 19, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [6f8fadfe19](https://linux-hardware.org/?probe=6f8fadfe19) | Feb 15, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [390686f5f6](https://linux-hardware.org/?probe=390686f5f6) | Feb 14, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [26ea96167c](https://linux-hardware.org/?probe=26ea96167c) | Feb 12, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [bb53ff2532](https://linux-hardware.org/?probe=bb53ff2532) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a1133b56be](https://linux-hardware.org/?probe=a1133b56be) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [ab928273ba](https://linux-hardware.org/?probe=ab928273ba) | Feb 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [5995e0b36b](https://linux-hardware.org/?probe=5995e0b36b) | Feb 11, 2023 |
| Heptagon S... | HQ-BOX2 Server              | Notebook    | [476197a287](https://linux-hardware.org/?probe=476197a287) | Feb 09, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| ASUSTek       | X556UV                      | Notebook    | [ae90dba4ca](https://linux-hardware.org/?probe=ae90dba4ca) | Feb 04, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| Gigabyte      | G1.Sniper 3                 | Desktop     | [f7f587188e](https://linux-hardware.org/?probe=f7f587188e) | Feb 03, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4b8ddf5d09](https://linux-hardware.org/?probe=4b8ddf5d09) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK U554               | Notebook    | [22bf4111de](https://linux-hardware.org/?probe=22bf4111de) | Jan 23, 2023 |
| Acer          | TravelMate P257-M           | Notebook    | [1345fa56c4](https://linux-hardware.org/?probe=1345fa56c4) | Jan 22, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [79a45b9ea0](https://linux-hardware.org/?probe=79a45b9ea0) | Jan 19, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [b6a8598370](https://linux-hardware.org/?probe=b6a8598370) | Jan 19, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [61c432b134](https://linux-hardware.org/?probe=61c432b134) | Jan 13, 2023 |
| Dell          | Vostro 14 5401              | Notebook    | [b56e81d82d](https://linux-hardware.org/?probe=b56e81d82d) | Jan 11, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [3965f2f9f4](https://linux-hardware.org/?probe=3965f2f9f4) | Jan 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [78a20b41ee](https://linux-hardware.org/?probe=78a20b41ee) | Jan 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [abe344877a](https://linux-hardware.org/?probe=abe344877a) | Jan 09, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [6a5da8e502](https://linux-hardware.org/?probe=6a5da8e502) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9767004b24](https://linux-hardware.org/?probe=9767004b24) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [87c4201895](https://linux-hardware.org/?probe=87c4201895) | Jan 07, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [874b25fc88](https://linux-hardware.org/?probe=874b25fc88) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4641833cab](https://linux-hardware.org/?probe=4641833cab) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Dell          | 0PV9DG A01                  | Server      | [7f408923fa](https://linux-hardware.org/?probe=7f408923fa) | Dec 27, 2022 |
| GPD           | G1621-02                    | Notebook    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [10f4ac5e13](https://linux-hardware.org/?probe=10f4ac5e13) | Dec 24, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b9b1f8140b](https://linux-hardware.org/?probe=b9b1f8140b) | Dec 18, 2022 |
| MSI           | Summit E16FlipEvo A12MT     | Notebook    | [426289da4e](https://linux-hardware.org/?probe=426289da4e) | Dec 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [011df4cb7f](https://linux-hardware.org/?probe=011df4cb7f) | Dec 02, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [dc13dde66a](https://linux-hardware.org/?probe=dc13dde66a) | Nov 29, 2022 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [ec30826806](https://linux-hardware.org/?probe=ec30826806) | Nov 21, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [504222de34](https://linux-hardware.org/?probe=504222de34) | Nov 20, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [f685fd9050](https://linux-hardware.org/?probe=f685fd9050) | Nov 20, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [ade5f58f0e](https://linux-hardware.org/?probe=ade5f58f0e) | Nov 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [58c63522a4](https://linux-hardware.org/?probe=58c63522a4) | Nov 20, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| Dell          | Vostro 3300                 | Notebook    | [ae100dd7e2](https://linux-hardware.org/?probe=ae100dd7e2) | Nov 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [c22dce3d23](https://linux-hardware.org/?probe=c22dce3d23) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| HP            | 88BE                        | Desktop     | [1c03e5957d](https://linux-hardware.org/?probe=1c03e5957d) | Nov 13, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [f04bf95806](https://linux-hardware.org/?probe=f04bf95806) | Nov 08, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [da03d56b4e](https://linux-hardware.org/?probe=da03d56b4e) | Nov 07, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4099d3c69b](https://linux-hardware.org/?probe=4099d3c69b) | Nov 05, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c35a514fe5](https://linux-hardware.org/?probe=c35a514fe5) | Nov 05, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [be2ceae6ca](https://linux-hardware.org/?probe=be2ceae6ca) | Nov 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4457c6182e](https://linux-hardware.org/?probe=4457c6182e) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [66b04ff6f8](https://linux-hardware.org/?probe=66b04ff6f8) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [989fe39fa7](https://linux-hardware.org/?probe=989fe39fa7) | Oct 10, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [dc262edc58](https://linux-hardware.org/?probe=dc262edc58) | Oct 09, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [b98f2dc115](https://linux-hardware.org/?probe=b98f2dc115) | Oct 08, 2022 |
| Dell          | 014GRG A01                  | Desktop     | [05a023826f](https://linux-hardware.org/?probe=05a023826f) | Oct 06, 2022 |
| AYANEO        | AIR                         | Tablet      | [a5e36506b9](https://linux-hardware.org/?probe=a5e36506b9) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [a0d832ff6a](https://linux-hardware.org/?probe=a0d832ff6a) | Sep 28, 2022 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [bc43cff31b](https://linux-hardware.org/?probe=bc43cff31b) | Sep 23, 2022 |
| Dell          | 0WCJNT A06                  | Server      | [4cc4b2f914](https://linux-hardware.org/?probe=4cc4b2f914) | Sep 22, 2022 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [c996a3c4dd](https://linux-hardware.org/?probe=c996a3c4dd) | Sep 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [cc3af3e194](https://linux-hardware.org/?probe=cc3af3e194) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [4d7948b375](https://linux-hardware.org/?probe=4d7948b375) | Sep 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [598341495c](https://linux-hardware.org/?probe=598341495c) | Sep 16, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [1e4d0a6189](https://linux-hardware.org/?probe=1e4d0a6189) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [1820ffa037](https://linux-hardware.org/?probe=1820ffa037) | Sep 09, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [3f0d8d8ff5](https://linux-hardware.org/?probe=3f0d8d8ff5) | Sep 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0796b79ff6](https://linux-hardware.org/?probe=0796b79ff6) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | Latitude E4300              | Notebook    | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| Dell          | 0CRH6C A01                  | Desktop     | [d4a37f016b](https://linux-hardware.org/?probe=d4a37f016b) | Sep 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f65d685d05](https://linux-hardware.org/?probe=f65d685d05) | Aug 30, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [9158baf2c0](https://linux-hardware.org/?probe=9158baf2c0) | Aug 28, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [e7f6559a38](https://linux-hardware.org/?probe=e7f6559a38) | Aug 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | 18E7                        | Desktop     | [f1c1f9c891](https://linux-hardware.org/?probe=f1c1f9c891) | Aug 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [b9f6292104](https://linux-hardware.org/?probe=b9f6292104) | Aug 07, 2022 |
| Lenovo        | G50-80 80L0                 | Notebook    | [eb58813044](https://linux-hardware.org/?probe=eb58813044) | Aug 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS3UW00    | Notebook    | [ddefadf8f1](https://linux-hardware.org/?probe=ddefadf8f1) | Aug 06, 2022 |
| Gigabyte      | Z690 AORUS ULTRA            | Desktop     | [06d2014c22](https://linux-hardware.org/?probe=06d2014c22) | Aug 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d1ca5eafe5](https://linux-hardware.org/?probe=d1ca5eafe5) | Aug 03, 2022 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [8e9bf5b1f9](https://linux-hardware.org/?probe=8e9bf5b1f9) | Aug 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [6362df4235](https://linux-hardware.org/?probe=6362df4235) | Jul 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1512e3bf4d](https://linux-hardware.org/?probe=1512e3bf4d) | Jul 22, 2022 |
| Dell          | G7 7500                     | Notebook    | [f5e6475121](https://linux-hardware.org/?probe=f5e6475121) | Jul 22, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [e52633f694](https://linux-hardware.org/?probe=e52633f694) | Jul 17, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [8f556b89fc](https://linux-hardware.org/?probe=8f556b89fc) | Jul 16, 2022 |
| ASUSTek       | G53JW                       | Notebook    | [2090800f5c](https://linux-hardware.org/?probe=2090800f5c) | Jul 06, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [4281fab7fd](https://linux-hardware.org/?probe=4281fab7fd) | Jul 05, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [c186124284](https://linux-hardware.org/?probe=c186124284) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [fce4d4547c](https://linux-hardware.org/?probe=fce4d4547c) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [ac6fde7f04](https://linux-hardware.org/?probe=ac6fde7f04) | Jul 02, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| TYAN Compu... | S7010                       | Server      | [af4d333445](https://linux-hardware.org/?probe=af4d333445) | Jun 28, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| Dell          | Latitude 7300               | Notebook    | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [5708a69dc1](https://linux-hardware.org/?probe=5708a69dc1) | Jun 26, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [150ea72986](https://linux-hardware.org/?probe=150ea72986) | Jun 23, 2022 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [7f2adf56e4](https://linux-hardware.org/?probe=7f2adf56e4) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [755c2fc534](https://linux-hardware.org/?probe=755c2fc534) | Jun 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Purism        | Librem 14                   | Notebook    | [89d920a7d2](https://linux-hardware.org/?probe=89d920a7d2) | Jun 11, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1c8e5b49d3](https://linux-hardware.org/?probe=1c8e5b49d3) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [00d3a71a00](https://linux-hardware.org/?probe=00d3a71a00) | Jun 06, 2022 |
| Foxconn       | H81MXV FAB A                | Desktop     | [1f880ea008](https://linux-hardware.org/?probe=1f880ea008) | Jun 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e308c653b2](https://linux-hardware.org/?probe=e308c653b2) | May 30, 2022 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [df4917e32f](https://linux-hardware.org/?probe=df4917e32f) | May 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [c01e0f9ac4](https://linux-hardware.org/?probe=c01e0f9ac4) | May 25, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [7ba08ba4b5](https://linux-hardware.org/?probe=7ba08ba4b5) | May 21, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [81aa40219e](https://linux-hardware.org/?probe=81aa40219e) | May 21, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| HP            | 8298                        | Desktop     | [3f45b43adb](https://linux-hardware.org/?probe=3f45b43adb) | May 19, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [dc2f9f56a5](https://linux-hardware.org/?probe=dc2f9f56a5) | May 18, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [813349f89b](https://linux-hardware.org/?probe=813349f89b) | May 17, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [d14ee897f2](https://linux-hardware.org/?probe=d14ee897f2) | May 17, 2022 |
| Dell          | 0R4CNN A01                  | Server      | [b12db2e5d7](https://linux-hardware.org/?probe=b12db2e5d7) | May 16, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [22f5a0269f](https://linux-hardware.org/?probe=22f5a0269f) | May 15, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8b8bd9dead](https://linux-hardware.org/?probe=8b8bd9dead) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| Dell          | Latitude 5421               | Notebook    | [3b2e352ea9](https://linux-hardware.org/?probe=3b2e352ea9) | May 11, 2022 |
| Dell          | Latitude 5421               | Notebook    | [105382c79b](https://linux-hardware.org/?probe=105382c79b) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [ff11e148fd](https://linux-hardware.org/?probe=ff11e148fd) | May 04, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [8ef837bdb4](https://linux-hardware.org/?probe=8ef837bdb4) | May 04, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [f51fab0e09](https://linux-hardware.org/?probe=f51fab0e09) | Apr 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| Dell          | Latitude 7400               | Notebook    | [7f20623ac0](https://linux-hardware.org/?probe=7f20623ac0) | Apr 28, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6f956cd55c](https://linux-hardware.org/?probe=6f956cd55c) | Apr 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3a052b2111](https://linux-hardware.org/?probe=3a052b2111) | Apr 21, 2022 |
| Acer          | Aspire V7-482PG             | Notebook    | [40eb526de9](https://linux-hardware.org/?probe=40eb526de9) | Apr 18, 2022 |
| ASUSTek       | D540MA-C                    | Desktop     | [f8639b84f5](https://linux-hardware.org/?probe=f8639b84f5) | Apr 16, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [e13fc569ce](https://linux-hardware.org/?probe=e13fc569ce) | Apr 13, 2022 |
| Lenovo        | Legion Y730-15ICH 81HD      | Notebook    | [9ad8e2f080](https://linux-hardware.org/?probe=9ad8e2f080) | Apr 13, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [7f35e9e656](https://linux-hardware.org/?probe=7f35e9e656) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f242f094a9](https://linux-hardware.org/?probe=f242f094a9) | Apr 09, 2022 |
| Lenovo        | ThinkPad 10 2nd 20E30035... | Tablet      | [76ddd6a6bc](https://linux-hardware.org/?probe=76ddd6a6bc) | Apr 07, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [05569f49ca](https://linux-hardware.org/?probe=05569f49ca) | Apr 04, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a94e9d5553](https://linux-hardware.org/?probe=a94e9d5553) | Apr 01, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [22e95f050f](https://linux-hardware.org/?probe=22e95f050f) | Mar 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [b0cf6455ae](https://linux-hardware.org/?probe=b0cf6455ae) | Mar 24, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9e98e995e7](https://linux-hardware.org/?probe=9e98e995e7) | Mar 18, 2022 |
| MSI           | H61M-E22                    | Desktop     | [1ce895a81c](https://linux-hardware.org/?probe=1ce895a81c) | Mar 17, 2022 |
| Acer          | Aspire 5820                 | Notebook    | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [0d64cbab8e](https://linux-hardware.org/?probe=0d64cbab8e) | Mar 08, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [8b2771b584](https://linux-hardware.org/?probe=8b2771b584) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [48c1285eec](https://linux-hardware.org/?probe=48c1285eec) | Mar 02, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Dell          | Latitude 5411               | Notebook    | [c6e4b5cf11](https://linux-hardware.org/?probe=c6e4b5cf11) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f1d191a15c](https://linux-hardware.org/?probe=f1d191a15c) | Mar 02, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [46656cb5cc](https://linux-hardware.org/?probe=46656cb5cc) | Mar 02, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [63caa45089](https://linux-hardware.org/?probe=63caa45089) | Mar 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [376b49560d](https://linux-hardware.org/?probe=376b49560d) | Feb 28, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [e55893075e](https://linux-hardware.org/?probe=e55893075e) | Feb 28, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [1398ef93be](https://linux-hardware.org/?probe=1398ef93be) | Feb 22, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [cf906c0ca1](https://linux-hardware.org/?probe=cf906c0ca1) | Feb 20, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [807790386b](https://linux-hardware.org/?probe=807790386b) | Feb 20, 2022 |
| Dell          | Studio 1555                 | Notebook    | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [56c75c35b6](https://linux-hardware.org/?probe=56c75c35b6) | Feb 19, 2022 |
| Dell          | Latitude E6330              | Notebook    | [4d2f890592](https://linux-hardware.org/?probe=4d2f890592) | Feb 17, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [9295ca6d10](https://linux-hardware.org/?probe=9295ca6d10) | Feb 13, 2022 |
| Gigabyte      | H55M-D2H                    | Desktop     | [f85ece5bf7](https://linux-hardware.org/?probe=f85ece5bf7) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [331b62c0e9](https://linux-hardware.org/?probe=331b62c0e9) | Feb 11, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [136ea58ce8](https://linux-hardware.org/?probe=136ea58ce8) | Feb 11, 2022 |
| Shuttle       | FH87                        | Desktop     | [1588ed0352](https://linux-hardware.org/?probe=1588ed0352) | Feb 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518NR8    | Desktop     | [cc2ea0bba2](https://linux-hardware.org/?probe=cc2ea0bba2) | Feb 08, 2022 |
| HP            | 2B34                        | Desktop     | [a44a14f358](https://linux-hardware.org/?probe=a44a14f358) | Feb 08, 2022 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [52699a1847](https://linux-hardware.org/?probe=52699a1847) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [310e0596c7](https://linux-hardware.org/?probe=310e0596c7) | Feb 05, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [46a851b841](https://linux-hardware.org/?probe=46a851b841) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [0bd0a24a20](https://linux-hardware.org/?probe=0bd0a24a20) | Feb 02, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [852eb2b367](https://linux-hardware.org/?probe=852eb2b367) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M91p 4524B96    | Desktop     | [5a90acd016](https://linux-hardware.org/?probe=5a90acd016) | Jan 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [80213a278f](https://linux-hardware.org/?probe=80213a278f) | Jan 20, 2022 |
| Dell          | Latitude 3350               | Notebook    | [682af42b93](https://linux-hardware.org/?probe=682af42b93) | Jan 18, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [8ab84f13d3](https://linux-hardware.org/?probe=8ab84f13d3) | Jan 14, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50669a06d2](https://linux-hardware.org/?probe=50669a06d2) | Jan 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [48e8e52d84](https://linux-hardware.org/?probe=48e8e52d84) | Jan 13, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [0f78e87ab1](https://linux-hardware.org/?probe=0f78e87ab1) | Jan 03, 2022 |
| Supermicro    | X9DAi                       | Desktop     | [a86bdc7f4d](https://linux-hardware.org/?probe=a86bdc7f4d) | Jan 03, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [ffc754462f](https://linux-hardware.org/?probe=ffc754462f) | Dec 30, 2021 |
| Dell          | Vostro 3560                 | Notebook    | [cd630222d7](https://linux-hardware.org/?probe=cd630222d7) | Dec 30, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [195c9a8567](https://linux-hardware.org/?probe=195c9a8567) | Dec 29, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [14f60e1eef](https://linux-hardware.org/?probe=14f60e1eef) | Dec 28, 2021 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [0f43701ca4](https://linux-hardware.org/?probe=0f43701ca4) | Dec 20, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [6d2be9add8](https://linux-hardware.org/?probe=6d2be9add8) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| AZW           | U59                         | Desktop     | [021639604a](https://linux-hardware.org/?probe=021639604a) | Dec 15, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [0eee85762e](https://linux-hardware.org/?probe=0eee85762e) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f986757d36](https://linux-hardware.org/?probe=f986757d36) | Dec 14, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [8462457866](https://linux-hardware.org/?probe=8462457866) | Dec 14, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [d4f31ef495](https://linux-hardware.org/?probe=d4f31ef495) | Dec 01, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [a5e249d28f](https://linux-hardware.org/?probe=a5e249d28f) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [df4d55c39b](https://linux-hardware.org/?probe=df4d55c39b) | Nov 26, 2021 |
| ASUSTek       | UX331UA                     | Notebook    | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [540612a510](https://linux-hardware.org/?probe=540612a510) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [8d8d873287](https://linux-hardware.org/?probe=8d8d873287) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| Gigabyte      | B460 HD3                    | Desktop     | [19bfb20536](https://linux-hardware.org/?probe=19bfb20536) | Nov 19, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [ba96dd251c](https://linux-hardware.org/?probe=ba96dd251c) | Nov 17, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | BU403UAV                    | Notebook    | [cb7fcf5c15](https://linux-hardware.org/?probe=cb7fcf5c15) | Nov 15, 2021 |
| Gigabyte      | B560M H                     | Desktop     | [358ab5a9fe](https://linux-hardware.org/?probe=358ab5a9fe) | Nov 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb3074bfdc](https://linux-hardware.org/?probe=eb3074bfdc) | Nov 14, 2021 |
| ASUSTek       | GL502VMK                    | Notebook    | [78bc4b00c0](https://linux-hardware.org/?probe=78bc4b00c0) | Nov 12, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [55b02178a3](https://linux-hardware.org/?probe=55b02178a3) | Nov 11, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [b95625ab23](https://linux-hardware.org/?probe=b95625ab23) | Nov 10, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [b6127e027b](https://linux-hardware.org/?probe=b6127e027b) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cab956de97](https://linux-hardware.org/?probe=cab956de97) | Nov 06, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Dell          | Latitude 5410               | Notebook    | [35fd3a8949](https://linux-hardware.org/?probe=35fd3a8949) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [28366fcde0](https://linux-hardware.org/?probe=28366fcde0) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [c5e111be13](https://linux-hardware.org/?probe=c5e111be13) | Nov 04, 2021 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [6cc81555db](https://linux-hardware.org/?probe=6cc81555db) | Nov 04, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [e221c43af2](https://linux-hardware.org/?probe=e221c43af2) | Oct 27, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ed20604458](https://linux-hardware.org/?probe=ed20604458) | Oct 26, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [3f5d6aaab8](https://linux-hardware.org/?probe=3f5d6aaab8) | Oct 26, 2021 |
| Dell          | 0V8F20 A01                  | Desktop     | [8e371fe4cb](https://linux-hardware.org/?probe=8e371fe4cb) | Oct 24, 2021 |
| MSI           | G41TM-P33                   | Desktop     | [8216f8bfae](https://linux-hardware.org/?probe=8216f8bfae) | Oct 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b792457755](https://linux-hardware.org/?probe=b792457755) | Oct 21, 2021 |
| Foxconn       | H81MXV FAB A                | Desktop     | [b030daf542](https://linux-hardware.org/?probe=b030daf542) | Oct 20, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [b39ed56cc9](https://linux-hardware.org/?probe=b39ed56cc9) | Oct 19, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [aa3b1b645e](https://linux-hardware.org/?probe=aa3b1b645e) | Oct 16, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b8d00b123f](https://linux-hardware.org/?probe=b8d00b123f) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [e3149252a0](https://linux-hardware.org/?probe=e3149252a0) | Oct 16, 2021 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [b78fec94ab](https://linux-hardware.org/?probe=b78fec94ab) | Oct 16, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [853a82796c](https://linux-hardware.org/?probe=853a82796c) | Oct 15, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [28136dcca0](https://linux-hardware.org/?probe=28136dcca0) | Oct 13, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f86adc0f8d](https://linux-hardware.org/?probe=f86adc0f8d) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [267712392b](https://linux-hardware.org/?probe=267712392b) | Oct 11, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [f850c51db9](https://linux-hardware.org/?probe=f850c51db9) | Oct 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c9ef1c033f](https://linux-hardware.org/?probe=c9ef1c033f) | Oct 09, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [688258aedb](https://linux-hardware.org/?probe=688258aedb) | Oct 01, 2021 |
| Notebook      | N2x0WU                      | Notebook    | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| HP            | 1497                        | Desktop     | [fcfd0c8e49](https://linux-hardware.org/?probe=fcfd0c8e49) | Sep 27, 2021 |
| Dell          | Latitude 5420               | Notebook    | [a31b3507c4](https://linux-hardware.org/?probe=a31b3507c4) | Sep 26, 2021 |
| Dell          | Latitude 5420               | Notebook    | [a077664ed2](https://linux-hardware.org/?probe=a077664ed2) | Sep 26, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ab36263477](https://linux-hardware.org/?probe=ab36263477) | Sep 25, 2021 |
| ASUSTek       | H81M-E R2.0                 | Desktop     | [18852b576b](https://linux-hardware.org/?probe=18852b576b) | Sep 24, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [e79a9eb09d](https://linux-hardware.org/?probe=e79a9eb09d) | Sep 22, 2021 |
| HP            | EliteBook x360 1040 G6      | Convertible | [7e2118517f](https://linux-hardware.org/?probe=7e2118517f) | Sep 17, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [28ce3a6f8d](https://linux-hardware.org/?probe=28ce3a6f8d) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [41894dc479](https://linux-hardware.org/?probe=41894dc479) | Sep 10, 2021 |
| Dell          | Vostro 7590                 | Notebook    | [8f4e694845](https://linux-hardware.org/?probe=8f4e694845) | Sep 10, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| ITI LIMITE... | SMAASH XU3i                 | Desktop     | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | Notebook    | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ProBook 4520s               | Notebook    | [4f947f1b22](https://linux-hardware.org/?probe=4f947f1b22) | Sep 06, 2021 |
| HP            | ProBook 4520s               | Notebook    | [fac0dbdf09](https://linux-hardware.org/?probe=fac0dbdf09) | Sep 06, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [e5e1953ed8](https://linux-hardware.org/?probe=e5e1953ed8) | Sep 05, 2021 |
| HP            | 158A                        | Desktop     | [6c22e51bfc](https://linux-hardware.org/?probe=6c22e51bfc) | Sep 04, 2021 |
| HP            | Spectre Notebook            | Notebook    | [6a3406a77f](https://linux-hardware.org/?probe=6a3406a77f) | Sep 02, 2021 |
| HP            | Spectre Notebook            | Notebook    | [9966ff0b8f](https://linux-hardware.org/?probe=9966ff0b8f) | Sep 02, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [79010f7e30](https://linux-hardware.org/?probe=79010f7e30) | Aug 31, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [f2e7416585](https://linux-hardware.org/?probe=f2e7416585) | Aug 25, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [17afc04962](https://linux-hardware.org/?probe=17afc04962) | Aug 16, 2021 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [68213450a7](https://linux-hardware.org/?probe=68213450a7) | Aug 14, 2021 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [0ca5c5faa2](https://linux-hardware.org/?probe=0ca5c5faa2) | Aug 11, 2021 |
| IP3 Tech      | AP1                         | Notebook    | [b27a94c64c](https://linux-hardware.org/?probe=b27a94c64c) | Aug 08, 2021 |
| Dell          | Latitude 5410               | Notebook    | [4f2e0ccb9f](https://linux-hardware.org/?probe=4f2e0ccb9f) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [37cbdcae11](https://linux-hardware.org/?probe=37cbdcae11) | Aug 03, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [cab34266f1](https://linux-hardware.org/?probe=cab34266f1) | Aug 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [6c6c327314](https://linux-hardware.org/?probe=6c6c327314) | Aug 02, 2021 |
| Dell          | Latitude 5410               | Notebook    | [73c46f7a65](https://linux-hardware.org/?probe=73c46f7a65) | Aug 01, 2021 |
| Dell          | Latitude 5410               | Notebook    | [8357a0ce64](https://linux-hardware.org/?probe=8357a0ce64) | Aug 01, 2021 |
| Gigabyte      | X58-USB3                    | Desktop     | [8a48f8d2bc](https://linux-hardware.org/?probe=8a48f8d2bc) | Jul 31, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [10ca0bf6bd](https://linux-hardware.org/?probe=10ca0bf6bd) | Jul 30, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| HP            | Unknown                     | Notebook    | [f048334d4b](https://linux-hardware.org/?probe=f048334d4b) | Jul 21, 2021 |
| Dell          | Latitude E4300              | Notebook    | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [1c9f5ba40f](https://linux-hardware.org/?probe=1c9f5ba40f) | Jul 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c74efec985](https://linux-hardware.org/?probe=c74efec985) | Jul 19, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [942e69cf0e](https://linux-hardware.org/?probe=942e69cf0e) | Jul 11, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [bdd432febf](https://linux-hardware.org/?probe=bdd432febf) | Jul 04, 2021 |
| Dell          | 06X1TJ A00                  | Desktop     | [49b9a37043](https://linux-hardware.org/?probe=49b9a37043) | Jul 03, 2021 |
| Dell          | 0GMM0G A00                  | Desktop     | [2c9050ccd9](https://linux-hardware.org/?probe=2c9050ccd9) | Jul 03, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [1ef68fcd87](https://linux-hardware.org/?probe=1ef68fcd87) | Jul 02, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [d479a6fd61](https://linux-hardware.org/?probe=d479a6fd61) | Jun 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [13ed380099](https://linux-hardware.org/?probe=13ed380099) | Jun 24, 2021 |
| HP            | Notebook                    | Notebook    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [79f64eaadf](https://linux-hardware.org/?probe=79f64eaadf) | Jun 19, 2021 |
| HP            | Notebook                    | Notebook    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [5475faba11](https://linux-hardware.org/?probe=5475faba11) | Jun 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [988cd2f5ee](https://linux-hardware.org/?probe=988cd2f5ee) | Jun 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [232ecea688](https://linux-hardware.org/?probe=232ecea688) | Jun 15, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [666afe018d](https://linux-hardware.org/?probe=666afe018d) | Jun 14, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [bed714271e](https://linux-hardware.org/?probe=bed714271e) | Jun 14, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [59cf3396c0](https://linux-hardware.org/?probe=59cf3396c0) | Jun 13, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [ecec039fdb](https://linux-hardware.org/?probe=ecec039fdb) | Jun 13, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [276793666d](https://linux-hardware.org/?probe=276793666d) | Jun 13, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [5d36394bec](https://linux-hardware.org/?probe=5d36394bec) | Jun 08, 2021 |
| Dell          | Vostro 5590                 | Notebook    | [debb5f4ac5](https://linux-hardware.org/?probe=debb5f4ac5) | Jun 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [aea7394e24](https://linux-hardware.org/?probe=aea7394e24) | Jun 01, 2021 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [38d5c55bd7](https://linux-hardware.org/?probe=38d5c55bd7) | May 31, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e334fad2cc](https://linux-hardware.org/?probe=e334fad2cc) | May 30, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f17aef391a](https://linux-hardware.org/?probe=f17aef391a) | May 28, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ee70288bc8](https://linux-hardware.org/?probe=ee70288bc8) | May 27, 2021 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [a760607f4e](https://linux-hardware.org/?probe=a760607f4e) | May 27, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a7a67287a3](https://linux-hardware.org/?probe=a7a67287a3) | May 26, 2021 |
| Acer          | Aspire 4333                 | Notebook    | [9f3738469d](https://linux-hardware.org/?probe=9f3738469d) | May 24, 2021 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [7070bcfa9a](https://linux-hardware.org/?probe=7070bcfa9a) | May 24, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [2f7da43eb2](https://linux-hardware.org/?probe=2f7da43eb2) | May 23, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [a1b3c9d405](https://linux-hardware.org/?probe=a1b3c9d405) | May 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c2267f8dd1](https://linux-hardware.org/?probe=c2267f8dd1) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d139816804](https://linux-hardware.org/?probe=d139816804) | May 16, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [6fe368312c](https://linux-hardware.org/?probe=6fe368312c) | May 15, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [9497cc9d85](https://linux-hardware.org/?probe=9497cc9d85) | May 15, 2021 |
| Dell          | Latitude E4300              | Notebook    | [7ed9015fd5](https://linux-hardware.org/?probe=7ed9015fd5) | May 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ab559fd00d](https://linux-hardware.org/?probe=ab559fd00d) | May 09, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8bf60ca353](https://linux-hardware.org/?probe=8bf60ca353) | May 08, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [c72aec456a](https://linux-hardware.org/?probe=c72aec456a) | May 06, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c8a2e1e897](https://linux-hardware.org/?probe=c8a2e1e897) | May 06, 2021 |
| LG Electro... | 15Z980-A.AAS8U1             | Notebook    | [2a68dcd848](https://linux-hardware.org/?probe=2a68dcd848) | May 03, 2021 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [e0e3552e96](https://linux-hardware.org/?probe=e0e3552e96) | Apr 28, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f8b00a2f85](https://linux-hardware.org/?probe=f8b00a2f85) | Apr 27, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [be75ff3da4](https://linux-hardware.org/?probe=be75ff3da4) | Apr 25, 2021 |
| HP            | 3397                        | Desktop     | [08ea9bb12b](https://linux-hardware.org/?probe=08ea9bb12b) | Apr 22, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0752e29519](https://linux-hardware.org/?probe=0752e29519) | Apr 21, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [6dd3daccc6](https://linux-hardware.org/?probe=6dd3daccc6) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [1e2ec488ee](https://linux-hardware.org/?probe=1e2ec488ee) | Apr 21, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [171825e444](https://linux-hardware.org/?probe=171825e444) | Apr 21, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c5109bab9c](https://linux-hardware.org/?probe=c5109bab9c) | Apr 17, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [95f2d11b2e](https://linux-hardware.org/?probe=95f2d11b2e) | Apr 16, 2021 |
| ASUSTek       | D540MA-C                    | Desktop     | [945b05bee8](https://linux-hardware.org/?probe=945b05bee8) | Apr 16, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [e6b5c6b72b](https://linux-hardware.org/?probe=e6b5c6b72b) | Apr 11, 2021 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [23fd0be92f](https://linux-hardware.org/?probe=23fd0be92f) | Apr 10, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [9881ce611d](https://linux-hardware.org/?probe=9881ce611d) | Apr 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [ca15c642d7](https://linux-hardware.org/?probe=ca15c642d7) | Apr 08, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a5823c243c](https://linux-hardware.org/?probe=a5823c243c) | Apr 02, 2021 |
| Unknown       | Unknown                     | All in one  | [a8185511a2](https://linux-hardware.org/?probe=a8185511a2) | Apr 01, 2021 |
| Unknown       | Unknown                     | All in one  | [f07c298443](https://linux-hardware.org/?probe=f07c298443) | Apr 01, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [fefe0c7d71](https://linux-hardware.org/?probe=fefe0c7d71) | Apr 01, 2021 |
| MSI           | H87-G43 GAMING              | Desktop     | [5bd49fbcea](https://linux-hardware.org/?probe=5bd49fbcea) | Mar 28, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8d84b967f2](https://linux-hardware.org/?probe=8d84b967f2) | Mar 25, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [91a8d56cfd](https://linux-hardware.org/?probe=91a8d56cfd) | Mar 25, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [4cc755d1c2](https://linux-hardware.org/?probe=4cc755d1c2) | Mar 25, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [f71120521c](https://linux-hardware.org/?probe=f71120521c) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [edf6ab636e](https://linux-hardware.org/?probe=edf6ab636e) | Mar 19, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [feb8706c98](https://linux-hardware.org/?probe=feb8706c98) | Mar 18, 2021 |
| ASRock        | H71M-DGS                    | Desktop     | [30424c4317](https://linux-hardware.org/?probe=30424c4317) | Mar 18, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [fa7b8613f2](https://linux-hardware.org/?probe=fa7b8613f2) | Mar 16, 2021 |
| Gigabyte      | Z490M                       | Desktop     | [6eecc1d3cc](https://linux-hardware.org/?probe=6eecc1d3cc) | Mar 15, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ff15d5b8ad](https://linux-hardware.org/?probe=ff15d5b8ad) | Mar 12, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | Desktop     | [0fbdab8514](https://linux-hardware.org/?probe=0fbdab8514) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [7140c5ee85](https://linux-hardware.org/?probe=7140c5ee85) | Mar 11, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [93a598b2c2](https://linux-hardware.org/?probe=93a598b2c2) | Mar 11, 2021 |
| Intel         | DG43RK AAE78175-403         | Desktop     | [942660dca5](https://linux-hardware.org/?probe=942660dca5) | Mar 11, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2d19cc5e17](https://linux-hardware.org/?probe=2d19cc5e17) | Mar 11, 2021 |
| Lenovo        | ThinkCentre M81 5049PA4     | Desktop     | [99082a91ac](https://linux-hardware.org/?probe=99082a91ac) | Mar 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [a50f9abd26](https://linux-hardware.org/?probe=a50f9abd26) | Mar 11, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [1e4054e9fe](https://linux-hardware.org/?probe=1e4054e9fe) | Mar 09, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [77a787d158](https://linux-hardware.org/?probe=77a787d158) | Mar 08, 2021 |
| Supermicro    | X8DAL                       | Server      | [ef1b6d7f7e](https://linux-hardware.org/?probe=ef1b6d7f7e) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a55964d5d9](https://linux-hardware.org/?probe=a55964d5d9) | Mar 06, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4336742334](https://linux-hardware.org/?probe=4336742334) | Mar 04, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [fb3d2fc3e9](https://linux-hardware.org/?probe=fb3d2fc3e9) | Mar 03, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [061392ad81](https://linux-hardware.org/?probe=061392ad81) | Mar 01, 2021 |
| ASUSTek       | GL503VD                     | Notebook    | [d03b00803b](https://linux-hardware.org/?probe=d03b00803b) | Feb 27, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [618d47c042](https://linux-hardware.org/?probe=618d47c042) | Feb 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [2fff8b3674](https://linux-hardware.org/?probe=2fff8b3674) | Feb 24, 2021 |
| Gigabyte      | H81-D3                      | Desktop     | [d05b1b3efc](https://linux-hardware.org/?probe=d05b1b3efc) | Feb 22, 2021 |
| ASRock        | H77M                        | Desktop     | [eb7af012c2](https://linux-hardware.org/?probe=eb7af012c2) | Feb 19, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [c2bd3800b7](https://linux-hardware.org/?probe=c2bd3800b7) | Feb 18, 2021 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [95fc52db78](https://linux-hardware.org/?probe=95fc52db78) | Feb 17, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [2b4a74a520](https://linux-hardware.org/?probe=2b4a74a520) | Feb 16, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [f4c77fc7dc](https://linux-hardware.org/?probe=f4c77fc7dc) | Feb 16, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [802f6994df](https://linux-hardware.org/?probe=802f6994df) | Feb 16, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [aead87bf38](https://linux-hardware.org/?probe=aead87bf38) | Feb 14, 2021 |
| Lenovo        | 3176 NOK                    | Desktop     | [c5216ce396](https://linux-hardware.org/?probe=c5216ce396) | Feb 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [a2ab510560](https://linux-hardware.org/?probe=a2ab510560) | Feb 14, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [66af036f49](https://linux-hardware.org/?probe=66af036f49) | Feb 13, 2021 |
| MSI           | B150M BAZOOKA               | Desktop     | [749beaf127](https://linux-hardware.org/?probe=749beaf127) | Feb 13, 2021 |
| Gigabyte      | B460M D3H                   | Desktop     | [8cdafac5a3](https://linux-hardware.org/?probe=8cdafac5a3) | Feb 13, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8711f89b6b](https://linux-hardware.org/?probe=8711f89b6b) | Feb 13, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [351477b72b](https://linux-hardware.org/?probe=351477b72b) | Feb 13, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [3e8ad6be09](https://linux-hardware.org/?probe=3e8ad6be09) | Feb 10, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [655d6c5817](https://linux-hardware.org/?probe=655d6c5817) | Feb 06, 2021 |
| Supermicro    | X10DRD-iNT                  | Server      | [21124e85cc](https://linux-hardware.org/?probe=21124e85cc) | Feb 05, 2021 |
| Lenovo        | ThinkPad T580 20L9001YIV    | Notebook    | [799c676c40](https://linux-hardware.org/?probe=799c676c40) | Feb 04, 2021 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [586d4a5a82](https://linux-hardware.org/?probe=586d4a5a82) | Feb 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [017e9abf15](https://linux-hardware.org/?probe=017e9abf15) | Feb 04, 2021 |
| Lenovo        | ThinkPad E550 20DF004RIV    | Notebook    | [23140cf3f9](https://linux-hardware.org/?probe=23140cf3f9) | Jan 29, 2021 |
| Lenovo        | G40-70 20369                | Notebook    | [1763668816](https://linux-hardware.org/?probe=1763668816) | Jan 29, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [e6be0abafb](https://linux-hardware.org/?probe=e6be0abafb) | Jan 28, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9aa53da922](https://linux-hardware.org/?probe=9aa53da922) | Jan 19, 2021 |
| Dell          | Latitude E6420              | Notebook    | [20a4b3769d](https://linux-hardware.org/?probe=20a4b3769d) | Jan 19, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [4df2203870](https://linux-hardware.org/?probe=4df2203870) | Jan 19, 2021 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [65724a4aa6](https://linux-hardware.org/?probe=65724a4aa6) | Jan 18, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [cc4593764d](https://linux-hardware.org/?probe=cc4593764d) | Jan 18, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1883634f7b](https://linux-hardware.org/?probe=1883634f7b) | Jan 18, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [23a9e9c5f6](https://linux-hardware.org/?probe=23a9e9c5f6) | Jan 17, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [750413cc61](https://linux-hardware.org/?probe=750413cc61) | Jan 16, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [725729e04e](https://linux-hardware.org/?probe=725729e04e) | Jan 13, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [9c40fd9781](https://linux-hardware.org/?probe=9c40fd9781) | Jan 13, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [94b70d7578](https://linux-hardware.org/?probe=94b70d7578) | Jan 12, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [4723903be4](https://linux-hardware.org/?probe=4723903be4) | Jan 11, 2021 |
| Gigabyte      | P55-UD3L                    | Desktop     | [8c6a5c5e60](https://linux-hardware.org/?probe=8c6a5c5e60) | Jan 10, 2021 |
| ASRock        | H97M Anniversary            | Desktop     | [b630702ecc](https://linux-hardware.org/?probe=b630702ecc) | Jan 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [c1eeffc9d8](https://linux-hardware.org/?probe=c1eeffc9d8) | Jan 08, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [2583ebac59](https://linux-hardware.org/?probe=2583ebac59) | Jan 08, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [b7c82c53b6](https://linux-hardware.org/?probe=b7c82c53b6) | Jan 07, 2021 |
| Dell          | Inspiron 5567               | Notebook    | [0d62d918c5](https://linux-hardware.org/?probe=0d62d918c5) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [5a3a67e5c3](https://linux-hardware.org/?probe=5a3a67e5c3) | Jan 07, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [f37800ed52](https://linux-hardware.org/?probe=f37800ed52) | Jan 07, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [b8bab31c57](https://linux-hardware.org/?probe=b8bab31c57) | Jan 06, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [d55bf78096](https://linux-hardware.org/?probe=d55bf78096) | Jan 06, 2021 |
| Unknown       | G41 Series                  | Desktop     | [578bc526ef](https://linux-hardware.org/?probe=578bc526ef) | Jan 06, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [0efe5f5a7e](https://linux-hardware.org/?probe=0efe5f5a7e) | Jan 04, 2021 |
| Unknown       | G41 Series                  | Desktop     | [5a6543b6f1](https://linux-hardware.org/?probe=5a6543b6f1) | Jan 03, 2021 |
| Unknown       | Unknown                     | Notebook    | [b364724e53](https://linux-hardware.org/?probe=b364724e53) | Jan 02, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8d338ea73c](https://linux-hardware.org/?probe=8d338ea73c) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [ef84edb346](https://linux-hardware.org/?probe=ef84edb346) | Dec 31, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [2ed921327b](https://linux-hardware.org/?probe=2ed921327b) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [9448ec4439](https://linux-hardware.org/?probe=9448ec4439) | Dec 30, 2020 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [7cd92f4564](https://linux-hardware.org/?probe=7cd92f4564) | Dec 30, 2020 |
| Unknown       | Unknown                     | Notebook    | [749c45e229](https://linux-hardware.org/?probe=749c45e229) | Dec 29, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [01024cf86e](https://linux-hardware.org/?probe=01024cf86e) | Dec 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [66fd37cef4](https://linux-hardware.org/?probe=66fd37cef4) | Dec 27, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [c79668f190](https://linux-hardware.org/?probe=c79668f190) | Dec 24, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [56b69fe95e](https://linux-hardware.org/?probe=56b69fe95e) | Dec 23, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | Notebook    | [ddc1a4457d](https://linux-hardware.org/?probe=ddc1a4457d) | Dec 22, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [b4ebedb0e2](https://linux-hardware.org/?probe=b4ebedb0e2) | Dec 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [8d41f37972](https://linux-hardware.org/?probe=8d41f37972) | Dec 18, 2020 |
| Nvidia        | Tegra                       | Soc         | [eb55f6a449](https://linux-hardware.org/?probe=eb55f6a449) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e42b0f86e0](https://linux-hardware.org/?probe=e42b0f86e0) | Dec 14, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [5c1982b26c](https://linux-hardware.org/?probe=5c1982b26c) | Dec 08, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [5b58c4ff46](https://linux-hardware.org/?probe=5b58c4ff46) | Dec 08, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [df5f3d5a4d](https://linux-hardware.org/?probe=df5f3d5a4d) | Dec 07, 2020 |
| ASUSTek       | H97M-E                      | Desktop     | [4f0b22ee7f](https://linux-hardware.org/?probe=4f0b22ee7f) | Nov 30, 2020 |
| Dell          | XPS 13 9370                 | Notebook    | [4cbbe5b21a](https://linux-hardware.org/?probe=4cbbe5b21a) | Nov 26, 2020 |
| Lenovo        | Unknown                     | Notebook    | [40c892a262](https://linux-hardware.org/?probe=40c892a262) | Nov 26, 2020 |
| MSI           | X470 GAMING PLUS            | Desktop     | [b5d6fe9f9c](https://linux-hardware.org/?probe=b5d6fe9f9c) | Nov 24, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [f65b9a326b](https://linux-hardware.org/?probe=f65b9a326b) | Nov 21, 2020 |
| Gigabyte      | Z270X-UD5-CF                | Desktop     | [8f674b7608](https://linux-hardware.org/?probe=8f674b7608) | Nov 21, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [46d30ce200](https://linux-hardware.org/?probe=46d30ce200) | Nov 20, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [c42752eed3](https://linux-hardware.org/?probe=c42752eed3) | Nov 19, 2020 |
| Toshiba       | Satellite L755              | Notebook    | [a6e2af6e5b](https://linux-hardware.org/?probe=a6e2af6e5b) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [1674d3318e](https://linux-hardware.org/?probe=1674d3318e) | Nov 18, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [0ae9d90f3f](https://linux-hardware.org/?probe=0ae9d90f3f) | Nov 18, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [375ec8881d](https://linux-hardware.org/?probe=375ec8881d) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2f9457bf32](https://linux-hardware.org/?probe=2f9457bf32) | Nov 17, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f2e24821f4](https://linux-hardware.org/?probe=f2e24821f4) | Nov 17, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [accc9c10e5](https://linux-hardware.org/?probe=accc9c10e5) | Nov 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e13999e22a](https://linux-hardware.org/?probe=e13999e22a) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | Notebook    | [e04b97eabe](https://linux-hardware.org/?probe=e04b97eabe) | Nov 11, 2020 |
| Acer          | Aspire A715-72G             | Notebook    | [90ef23a01c](https://linux-hardware.org/?probe=90ef23a01c) | Nov 11, 2020 |
| Toshiba       | PORTEGE R700                | Notebook    | [4572167747](https://linux-hardware.org/?probe=4572167747) | Nov 10, 2020 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [21105809e4](https://linux-hardware.org/?probe=21105809e4) | Nov 08, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [22a316e31b](https://linux-hardware.org/?probe=22a316e31b) | Nov 08, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [a1662fff6f](https://linux-hardware.org/?probe=a1662fff6f) | Nov 08, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1c3bd52baa](https://linux-hardware.org/?probe=1c3bd52baa) | Nov 05, 2020 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [1b6972fae9](https://linux-hardware.org/?probe=1b6972fae9) | Nov 05, 2020 |
| Dell          | 0CU409                      | Desktop     | [6adb83b2e0](https://linux-hardware.org/?probe=6adb83b2e0) | Nov 04, 2020 |
| Lenovo        | Yoga 3 11 80J8              | Notebook    | [b4f083536f](https://linux-hardware.org/?probe=b4f083536f) | Nov 04, 2020 |
| Lenovo        | ThinkCentre A58 751581G     | Desktop     | [987ed81d7d](https://linux-hardware.org/?probe=987ed81d7d) | Nov 03, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [b0a2e83351](https://linux-hardware.org/?probe=b0a2e83351) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [b94cef8d24](https://linux-hardware.org/?probe=b94cef8d24) | Nov 03, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [c872f1d76f](https://linux-hardware.org/?probe=c872f1d76f) | Nov 03, 2020 |
| Dell          | 0KWVT8 A02                  | Desktop     | [2403e6e21e](https://linux-hardware.org/?probe=2403e6e21e) | Nov 03, 2020 |
| Dell          | Latitude E6330              | Notebook    | [f7e530a8c2](https://linux-hardware.org/?probe=f7e530a8c2) | Nov 02, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e8426a064f](https://linux-hardware.org/?probe=e8426a064f) | Nov 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [c59e7b1e56](https://linux-hardware.org/?probe=c59e7b1e56) | Nov 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [f8fa4c9c31](https://linux-hardware.org/?probe=f8fa4c9c31) | Nov 01, 2020 |
| Dell          | 0KP561                      | Desktop     | [da357993dd](https://linux-hardware.org/?probe=da357993dd) | Oct 31, 2020 |
| Dell          | 0KP561                      | Desktop     | [b14be76868](https://linux-hardware.org/?probe=b14be76868) | Oct 31, 2020 |
| Lenovo        | ThinkPad E480 20KN0062IV    | Notebook    | [fba2fb0e45](https://linux-hardware.org/?probe=fba2fb0e45) | Oct 30, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [1a691f72dc](https://linux-hardware.org/?probe=1a691f72dc) | Oct 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [990f9bb22f](https://linux-hardware.org/?probe=990f9bb22f) | Oct 29, 2020 |
| Dell          | Latitude 7490               | Notebook    | [2d61d426d5](https://linux-hardware.org/?probe=2d61d426d5) | Oct 28, 2020 |
| HP            | 158A                        | Desktop     | [f83412f912](https://linux-hardware.org/?probe=f83412f912) | Oct 27, 2020 |
| Dell          | Latitude 7300               | Notebook    | [ebf99bafc8](https://linux-hardware.org/?probe=ebf99bafc8) | Oct 27, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5bd58e33be](https://linux-hardware.org/?probe=5bd58e33be) | Oct 27, 2020 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [156543a1d2](https://linux-hardware.org/?probe=156543a1d2) | Oct 26, 2020 |
| HP            | 82B4                        | Desktop     | [d98d676e9c](https://linux-hardware.org/?probe=d98d676e9c) | Oct 26, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7c9e9b741c](https://linux-hardware.org/?probe=7c9e9b741c) | Oct 25, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d3f4deffa5](https://linux-hardware.org/?probe=d3f4deffa5) | Oct 25, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [36d289ce92](https://linux-hardware.org/?probe=36d289ce92) | Oct 20, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [e360fd1fa2](https://linux-hardware.org/?probe=e360fd1fa2) | Oct 18, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [6ba76947d7](https://linux-hardware.org/?probe=6ba76947d7) | Oct 18, 2020 |
| Dell          | Vostro 14 5401              | Notebook    | [89826d13da](https://linux-hardware.org/?probe=89826d13da) | Oct 13, 2020 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [44d70b326c](https://linux-hardware.org/?probe=44d70b326c) | Oct 13, 2020 |
| ASUSTek       | UX430UNR                    | Notebook    | [03dd6f184c](https://linux-hardware.org/?probe=03dd6f184c) | Oct 12, 2020 |
| Dell          | Vostro 14 5401              | Notebook    | [d3f66acd1b](https://linux-hardware.org/?probe=d3f66acd1b) | Oct 12, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [cab83dd9ff](https://linux-hardware.org/?probe=cab83dd9ff) | Oct 12, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [b998e489c5](https://linux-hardware.org/?probe=b998e489c5) | Oct 07, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [ba633c064d](https://linux-hardware.org/?probe=ba633c064d) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [a9d940dd83](https://linux-hardware.org/?probe=a9d940dd83) | Oct 04, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [c7e2a6001a](https://linux-hardware.org/?probe=c7e2a6001a) | Oct 04, 2020 |
| Dell          | Latitude 7400               | Notebook    | [6eac6cfa15](https://linux-hardware.org/?probe=6eac6cfa15) | Oct 04, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [e0aadcb07c](https://linux-hardware.org/?probe=e0aadcb07c) | Oct 04, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [986a5e604f](https://linux-hardware.org/?probe=986a5e604f) | Oct 03, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [268a9d5625](https://linux-hardware.org/?probe=268a9d5625) | Oct 01, 2020 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [353229fd96](https://linux-hardware.org/?probe=353229fd96) | Sep 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [cc0e0f5c04](https://linux-hardware.org/?probe=cc0e0f5c04) | Sep 29, 2020 |
| MSI           | G41M-E43                    | Desktop     | [5a567b1f97](https://linux-hardware.org/?probe=5a567b1f97) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [c4d11b04b5](https://linux-hardware.org/?probe=c4d11b04b5) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b8c1686e69](https://linux-hardware.org/?probe=b8c1686e69) | Sep 28, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [33801ffba1](https://linux-hardware.org/?probe=33801ffba1) | Sep 28, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [5d73c67b98](https://linux-hardware.org/?probe=5d73c67b98) | Sep 28, 2020 |
| Lenovo        | ThinkPad E14 20RA0036IV     | Notebook    | [d53e57ac10](https://linux-hardware.org/?probe=d53e57ac10) | Sep 25, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [9b2604c2e1](https://linux-hardware.org/?probe=9b2604c2e1) | Sep 21, 2020 |
| Lenovo        | ThinkCentre M81 5049W15     | Desktop     | [9c9f5b4cfa](https://linux-hardware.org/?probe=9c9f5b4cfa) | Sep 10, 2020 |
| Gigabyte      | B360M HD3                   | Desktop     | [7521b3b6e2](https://linux-hardware.org/?probe=7521b3b6e2) | Sep 07, 2020 |
| HP            | 339A                        | Desktop     | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [24b00b8ca8](https://linux-hardware.org/?probe=24b00b8ca8) | Sep 04, 2020 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [42deb7cee5](https://linux-hardware.org/?probe=42deb7cee5) | Sep 03, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5bfd2a1403](https://linux-hardware.org/?probe=5bfd2a1403) | Sep 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f8631e5f4a](https://linux-hardware.org/?probe=f8631e5f4a) | Sep 03, 2020 |
| Dell          | Latitude E5270              | Notebook    | [745e05ba12](https://linux-hardware.org/?probe=745e05ba12) | Aug 31, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [aa629696b3](https://linux-hardware.org/?probe=aa629696b3) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [eee9972fdf](https://linux-hardware.org/?probe=eee9972fdf) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [cb7fda5c3f](https://linux-hardware.org/?probe=cb7fda5c3f) | Aug 27, 2020 |
| MSI           | 2A9Ch                       | Desktop     | [0ece5d52d2](https://linux-hardware.org/?probe=0ece5d52d2) | Aug 27, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [56afe1e282](https://linux-hardware.org/?probe=56afe1e282) | Aug 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [99c5924655](https://linux-hardware.org/?probe=99c5924655) | Aug 23, 2020 |
| ASRock        | H97M Anniversary            | Desktop     | [613aba4134](https://linux-hardware.org/?probe=613aba4134) | Aug 23, 2020 |
| Lenovo        | ThinkPad L390 20NR001LIV    | Notebook    | [9fef5634b2](https://linux-hardware.org/?probe=9fef5634b2) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee5213ce49](https://linux-hardware.org/?probe=ee5213ce49) | Aug 19, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | Notebook    | [5f1ce912be](https://linux-hardware.org/?probe=5f1ce912be) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [635a148f20](https://linux-hardware.org/?probe=635a148f20) | Aug 19, 2020 |
| Toshiba       | Satellite P50t-B-10T        | Notebook    | [0f41a5b6ec](https://linux-hardware.org/?probe=0f41a5b6ec) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a114ae9c9c](https://linux-hardware.org/?probe=a114ae9c9c) | Aug 12, 2020 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | Desktop     | [1828dedb7f](https://linux-hardware.org/?probe=1828dedb7f) | Aug 10, 2020 |
| Lenovo        | ThinkPad T490 20N20073IV    | Notebook    | [3878e27014](https://linux-hardware.org/?probe=3878e27014) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [0d864b4feb](https://linux-hardware.org/?probe=0d864b4feb) | Aug 08, 2020 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [69e782093d](https://linux-hardware.org/?probe=69e782093d) | Aug 08, 2020 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [3fe0ec39fc](https://linux-hardware.org/?probe=3fe0ec39fc) | Aug 07, 2020 |
| ASRock        | H55M                        | Desktop     | [f2d0fa78ac](https://linux-hardware.org/?probe=f2d0fa78ac) | Aug 06, 2020 |
| Apple         | Mac-F22C86C8                | Mini pc     | [6d92297671](https://linux-hardware.org/?probe=6d92297671) | Aug 05, 2020 |
| Nvidia        | Tegra                       | Soc         | [273bc677cd](https://linux-hardware.org/?probe=273bc677cd) | Aug 05, 2020 |
| Supermicro    | X8DAL                       | Server      | [03a282558d](https://linux-hardware.org/?probe=03a282558d) | Aug 05, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5c3dc530c3](https://linux-hardware.org/?probe=5c3dc530c3) | Aug 04, 2020 |
| Supermicro    | X8DAL                       | Server      | [08cd245e63](https://linux-hardware.org/?probe=08cd245e63) | Aug 03, 2020 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [fb785080a3](https://linux-hardware.org/?probe=fb785080a3) | Aug 02, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [38442a922b](https://linux-hardware.org/?probe=38442a922b) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e934fab850](https://linux-hardware.org/?probe=e934fab850) | Aug 01, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [38feef34d4](https://linux-hardware.org/?probe=38feef34d4) | Aug 01, 2020 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6156b4dec2](https://linux-hardware.org/?probe=6156b4dec2) | Aug 01, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [2e41ce3f03](https://linux-hardware.org/?probe=2e41ce3f03) | Jul 31, 2020 |
| Gigabyte      | Z97-HD3                     | Desktop     | [50888e0851](https://linux-hardware.org/?probe=50888e0851) | Jul 31, 2020 |
| ASRock        | H55M                        | Desktop     | [dcbc0735f5](https://linux-hardware.org/?probe=dcbc0735f5) | Jul 30, 2020 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [a7e0318966](https://linux-hardware.org/?probe=a7e0318966) | Jul 30, 2020 |
| ASUSTek       | AT3N7A-I                    | Desktop     | [57c3ce82b7](https://linux-hardware.org/?probe=57c3ce82b7) | Jul 29, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ef4f365d92](https://linux-hardware.org/?probe=ef4f365d92) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6126a00ffc](https://linux-hardware.org/?probe=6126a00ffc) | Jul 24, 2020 |
| Dell          | Latitude E6530              | Notebook    | [6e1b2fb388](https://linux-hardware.org/?probe=6e1b2fb388) | Jul 24, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [c86e7dc968](https://linux-hardware.org/?probe=c86e7dc968) | Jul 23, 2020 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [3944aa1028](https://linux-hardware.org/?probe=3944aa1028) | Jul 20, 2020 |
| HP            | ProBook 640 G2              | Notebook    | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [6e6f80378d](https://linux-hardware.org/?probe=6e6f80378d) | Jul 11, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | Notebook    | [d0aacf7693](https://linux-hardware.org/?probe=d0aacf7693) | Jul 09, 2020 |
| Lenovo        | ThinkPad X260 20F60041IV    | Notebook    | [868953dc99](https://linux-hardware.org/?probe=868953dc99) | Jul 09, 2020 |
| Dell          | Latitude 5400               | Notebook    | [ae1c2d9825](https://linux-hardware.org/?probe=ae1c2d9825) | Jul 08, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [2a63a11959](https://linux-hardware.org/?probe=2a63a11959) | Jul 08, 2020 |
| ASUSTek       | UX461UA                     | Convertible | [a294adac80](https://linux-hardware.org/?probe=a294adac80) | Jul 02, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [52fad4367c](https://linux-hardware.org/?probe=52fad4367c) | Jul 01, 2020 |
| HP            | Pavilion dv6                | Notebook    | [39df31f4c6](https://linux-hardware.org/?probe=39df31f4c6) | Jun 27, 2020 |
| Lenovo        | ThinkPad E14 20RA0016IV     | Notebook    | [2878e88064](https://linux-hardware.org/?probe=2878e88064) | Jun 24, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [866c72927a](https://linux-hardware.org/?probe=866c72927a) | Jun 22, 2020 |
| Dell          | Inspiron 5379               | Notebook    | [f7fe8744d9](https://linux-hardware.org/?probe=f7fe8744d9) | Jun 21, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [da847897f9](https://linux-hardware.org/?probe=da847897f9) | Jun 15, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| MSI           | G41M-E43                    | Desktop     | [4c72170ef6](https://linux-hardware.org/?probe=4c72170ef6) | Jun 06, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [1ce6e06069](https://linux-hardware.org/?probe=1ce6e06069) | May 30, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [48f5173ede](https://linux-hardware.org/?probe=48f5173ede) | May 27, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [72b226183e](https://linux-hardware.org/?probe=72b226183e) | May 27, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [680a98718a](https://linux-hardware.org/?probe=680a98718a) | May 19, 2020 |
| Dell          | Latitude 5490               | Notebook    | [2afe6adf1b](https://linux-hardware.org/?probe=2afe6adf1b) | May 18, 2020 |
| Dell          | Latitude 5490               | Notebook    | [c2b1c12105](https://linux-hardware.org/?probe=c2b1c12105) | May 17, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [bd5ec5436e](https://linux-hardware.org/?probe=bd5ec5436e) | May 15, 2020 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [355e03bb68](https://linux-hardware.org/?probe=355e03bb68) | May 15, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| HP            | 339A                        | Desktop     | [ab1afaacc9](https://linux-hardware.org/?probe=ab1afaacc9) | May 14, 2020 |
| HP            | G42                         | Notebook    | [6d45062a76](https://linux-hardware.org/?probe=6d45062a76) | May 14, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [c815568345](https://linux-hardware.org/?probe=c815568345) | May 14, 2020 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [3edebf56b2](https://linux-hardware.org/?probe=3edebf56b2) | May 13, 2020 |
| Lenovo        | ThinkPad X200 74587DU       | Notebook    | [ba354beaa9](https://linux-hardware.org/?probe=ba354beaa9) | May 10, 2020 |
| ASUSTek       | K54C                        | Notebook    | [c2656ceae6](https://linux-hardware.org/?probe=c2656ceae6) | May 07, 2020 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [6f86c55589](https://linux-hardware.org/?probe=6f86c55589) | May 04, 2020 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [fc58b96f3e](https://linux-hardware.org/?probe=fc58b96f3e) | May 01, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0fe3c99d58](https://linux-hardware.org/?probe=0fe3c99d58) | Apr 30, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [d1078cd496](https://linux-hardware.org/?probe=d1078cd496) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [d575d16183](https://linux-hardware.org/?probe=d575d16183) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b5e521462a](https://linux-hardware.org/?probe=b5e521462a) | Apr 29, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [fcf5dd997f](https://linux-hardware.org/?probe=fcf5dd997f) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [3512230c03](https://linux-hardware.org/?probe=3512230c03) | Apr 28, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [a648a57d33](https://linux-hardware.org/?probe=a648a57d33) | Apr 28, 2020 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [20f18f18b8](https://linux-hardware.org/?probe=20f18f18b8) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [e93143c6fd](https://linux-hardware.org/?probe=e93143c6fd) | Apr 27, 2020 |
| Dell          | 097YXY A00                  | Desktop     | [baa8d3b29f](https://linux-hardware.org/?probe=baa8d3b29f) | Apr 27, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [4cc7a86795](https://linux-hardware.org/?probe=4cc7a86795) | Apr 26, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [d9a55aeca2](https://linux-hardware.org/?probe=d9a55aeca2) | Apr 25, 2020 |
| Toshiba       | Satellite A200              | Notebook    | [1e6ea00cd0](https://linux-hardware.org/?probe=1e6ea00cd0) | Apr 25, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [2516b70573](https://linux-hardware.org/?probe=2516b70573) | Apr 23, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [cdcce3c09c](https://linux-hardware.org/?probe=cdcce3c09c) | Apr 23, 2020 |
| MSI           | G41TM-P33                   | Desktop     | [d99b7f2578](https://linux-hardware.org/?probe=d99b7f2578) | Apr 22, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [434a4a46f9](https://linux-hardware.org/?probe=434a4a46f9) | Apr 19, 2020 |
| Dell          | XPS 13 9350                 | Notebook    | [d718b985ec](https://linux-hardware.org/?probe=d718b985ec) | Apr 18, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [cd641ec5c7](https://linux-hardware.org/?probe=cd641ec5c7) | Apr 17, 2020 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [28e6c33fec](https://linux-hardware.org/?probe=28e6c33fec) | Apr 17, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [7e17ce97e9](https://linux-hardware.org/?probe=7e17ce97e9) | Apr 17, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [189e02e90e](https://linux-hardware.org/?probe=189e02e90e) | Apr 12, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Israel/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 141       | 16.32%  |
| Ubuntu 18.04                 | 64        | 7.41%   |
| Ubuntu 22.04                 | 49        | 5.67%   |
| Arch Rolling                 | 19        | 2.2%    |
| OpenMandriva 4.3             | 17        | 1.97%   |
| OpenMandriva 4.2             | 16        | 1.85%   |
| Manjaro                      | 15        | 1.74%   |
| ROSA R11                     | 14        | 1.62%   |
| Fedora 38                    | 13        | 1.5%    |
| Fedora 37                    | 13        | 1.5%    |
| Ubuntu 21.04                 | 11        | 1.27%   |
| Ubuntu 19.04                 | 11        | 1.27%   |
| Fedora 36                    | 11        | 1.27%   |
| Linux Mint 20.1              | 10        | 1.16%   |
| Fedora 35                    | 10        | 1.16%   |
| Ubuntu 23.10                 | 9         | 1.04%   |
| Ubuntu 23.04                 | 9         | 1.04%   |
| Linux Mint 20.3              | 9         | 1.04%   |
| ArcoLinux Rolling            | 9         | 1.04%   |
| Zorin 16                     | 8         | 0.93%   |
| Ubuntu 20.10                 | 8         | 0.93%   |
| Ubuntu 19.10                 | 8         | 0.93%   |
| ROSA R11.1                   | 8         | 0.93%   |
| Pop!_OS 22.04                | 8         | 0.93%   |
| Pop!_OS 21.04                | 8         | 0.93%   |
| Linux Mint 21.1              | 8         | 0.93%   |
| Fedora 40                    | 8         | 0.93%   |
| Debian 11                    | 8         | 0.93%   |
| Arch                         | 8         | 0.93%   |
| ROSA R10                     | 7         | 0.81%   |
| Linux Mint 21.2              | 7         | 0.81%   |
| Linux Mint 21                | 7         | 0.81%   |
| Linux Mint 19.3              | 7         | 0.81%   |
| Kubuntu 20.04                | 7         | 0.81%   |
| Fedora 34                    | 7         | 0.81%   |
| Fedora 33                    | 7         | 0.81%   |
| Zorin 15                     | 6         | 0.69%   |
| Pop!_OS 21.10                | 6         | 0.69%   |
| Pop!_OS 20.04                | 6         | 0.69%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 312       | 39.15%  |
| Fedora        | 68        | 8.53%   |
| Linux Mint    | 61        | 7.65%   |
| OpenMandriva  | 54        | 6.78%   |
| ROSA          | 37        | 4.64%   |
| Pop!_OS       | 31        | 3.89%   |
| Manjaro       | 31        | 3.89%   |
| Arch          | 27        | 3.39%   |
| Debian        | 20        | 2.51%   |
| Kubuntu       | 18        | 2.26%   |
| Zorin         | 16        | 2.01%   |
| Xubuntu       | 15        | 1.88%   |
| SteamOS       | 10        | 1.25%   |
| ArcoLinux     | 9         | 1.13%   |
| Endless       | 8         | 1%      |
| Ubuntu MATE   | 7         | 0.88%   |
| Elementary    | 7         | 0.88%   |
| openSUSE      | 6         | 0.75%   |
| CentOS        | 6         | 0.75%   |
| KDE neon      | 5         | 0.63%   |
| Kali          | 5         | 0.63%   |
| Ubuntu Unity  | 3         | 0.38%   |
| Rocky Linux   | 3         | 0.38%   |
| Clear Linux   | 3         | 0.38%   |
| BlackPanther  | 3         | 0.38%   |
| Ubuntu Budgie | 2         | 0.25%   |
| Nobara        | 2         | 0.25%   |
| Neptune OS    | 2         | 0.25%   |
| Lubuntu       | 2         | 0.25%   |
| Gentoo        | 2         | 0.25%   |
| EndeavourOS   | 2         | 0.25%   |
| Devuan        | 2         | 0.25%   |
| Artix         | 2         | 0.25%   |
| Alpine        | 2         | 0.25%   |
| Xero          | 1         | 0.13%   |
| UbuntuDDE     | 1         | 0.13%   |
| Ubuntu Studio | 1         | 0.13%   |
| Siduction     | 1         | 0.13%   |
| Salix         | 1         | 0.13%   |
| RHEL          | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 26        | 2.75%   |
| 5.16.7-desktop-1omv4003         | 17        | 1.8%    |
| 5.10.14-desktop-1omv4002        | 15        | 1.58%   |
| 5.4.0-48-generic                | 14        | 1.48%   |
| 5.4.0-52-generic                | 10        | 1.06%   |
| 6.6.2-desktop-1omv2390          | 7         | 0.74%   |
| 6.2.0-20-generic                | 7         | 0.74%   |
| 5.15.0-91-generic               | 7         | 0.74%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 7         | 0.74%   |
| 6.8.7-300.fc40.x86_64           | 6         | 0.63%   |
| 6.2.6-desktop-1omv2390          | 6         | 0.63%   |
| 5.4.0-72-generic                | 6         | 0.63%   |
| 5.4.0-65-generic                | 6         | 0.63%   |
| 5.4.0-26-generic                | 6         | 0.63%   |
| 5.15.0-56-generic               | 6         | 0.63%   |
| 5.11.0-37-generic               | 6         | 0.63%   |
| 6.5.0-14-generic                | 5         | 0.53%   |
| 5.4.0-58-generic                | 5         | 0.53%   |
| 5.3.0-46-generic                | 5         | 0.53%   |
| 5.15.0-47-generic               | 5         | 0.53%   |
| 5.13.0-30-generic               | 5         | 0.53%   |
| 5.11.0-40-generic               | 5         | 0.53%   |
| 5.11.0-27-generic               | 5         | 0.53%   |
| 5.0.0-23-generic                | 5         | 0.53%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5         | 0.53%   |
| 6.4.11-desktop-1omv2390         | 4         | 0.42%   |
| 6.2.0-26-generic                | 4         | 0.42%   |
| 6.1.1-desktop-1omv2290          | 4         | 0.42%   |
| 5.4.0-70-generic                | 4         | 0.42%   |
| 5.4.0-40-generic                | 4         | 0.42%   |
| 5.4.0-37-generic                | 4         | 0.42%   |
| 5.3.0-42-generic                | 4         | 0.42%   |
| 5.3.0-28-generic                | 4         | 0.42%   |
| 5.15.0-78-generic               | 4         | 0.42%   |
| 5.15.0-57-generic               | 4         | 0.42%   |
| 5.15.0-50-generic               | 4         | 0.42%   |
| 5.15.0-41-generic               | 4         | 0.42%   |
| 5.13.0-valve36-1-neptune        | 4         | 0.42%   |
| 5.13.0-7620-generic             | 4         | 0.42%   |
| 5.11.0-38-generic               | 4         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 136       | 15.21%  |
| 5.15.0  | 70        | 7.83%   |
| 4.15.0  | 51        | 5.7%    |
| 5.8.0   | 43        | 4.81%   |
| 5.11.0  | 38        | 4.25%   |
| 5.13.0  | 35        | 3.91%   |
| 5.3.0   | 31        | 3.47%   |
| 6.2.0   | 29        | 3.24%   |
| 5.0.0   | 25        | 2.8%    |
| 6.5.0   | 23        | 2.57%   |
| 5.19.0  | 22        | 2.46%   |
| 5.16.7  | 17        | 1.9%    |
| 5.10.14 | 15        | 1.68%   |
| 4.18.0  | 13        | 1.45%   |
| 6.1.0   | 11        | 1.23%   |
| 5.10.0  | 10        | 1.12%   |
| 6.6.2   | 9         | 1.01%   |
| 6.2.6   | 8         | 0.89%   |
| 6.8.7   | 7         | 0.78%   |
| 6.3.5   | 6         | 0.67%   |
| 4.9.60  | 6         | 0.67%   |
| 6.2.9   | 5         | 0.56%   |
| 6.4.11  | 4         | 0.45%   |
| 6.1.52  | 4         | 0.45%   |
| 6.1.12  | 4         | 0.45%   |
| 6.1.1   | 4         | 0.45%   |
| 5.9.16  | 4         | 0.45%   |
| 4.19.0  | 4         | 0.45%   |
| 4.1.34  | 4         | 0.45%   |
| 6.6.7   | 3         | 0.34%   |
| 6.5.6   | 3         | 0.34%   |
| 6.0.8   | 3         | 0.34%   |
| 6.0.7   | 3         | 0.34%   |
| 6.0.0   | 3         | 0.34%   |
| 5.8.5   | 3         | 0.34%   |
| 5.14.10 | 3         | 0.34%   |
| 5.10.74 | 3         | 0.34%   |
| 4.9.20  | 3         | 0.34%   |
| 4.18.16 | 3         | 0.34%   |
| 6.8.0   | 2         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 141       | 16.15%  |
| 5.15    | 90        | 10.31%  |
| 4.15    | 51        | 5.84%   |
| 5.8     | 50        | 5.73%   |
| 6.2     | 48        | 5.5%    |
| 5.11    | 45        | 5.15%   |
| 6.1     | 40        | 4.58%   |
| 5.10    | 40        | 4.58%   |
| 5.13    | 39        | 4.47%   |
| 5.3     | 33        | 3.78%   |
| 6.5     | 30        | 3.44%   |
| 5.16    | 30        | 3.44%   |
| 5.19    | 29        | 3.32%   |
| 5.0     | 26        | 2.98%   |
| 6.6     | 19        | 2.18%   |
| 4.18    | 16        | 1.83%   |
| 4.9     | 15        | 1.72%   |
| 6.0     | 14        | 1.6%    |
| 6.4     | 13        | 1.49%   |
| 6.8     | 11        | 1.26%   |
| 5.9     | 11        | 1.26%   |
| 5.14    | 10        | 1.15%   |
| 6.7     | 9         | 1.03%   |
| 6.3     | 9         | 1.03%   |
| 5.18    | 9         | 1.03%   |
| 5.17    | 8         | 0.92%   |
| 4.19    | 8         | 0.92%   |
| 5.12    | 6         | 0.69%   |
| 4.1     | 6         | 0.69%   |
| 5.7     | 5         | 0.57%   |
| 5.6     | 4         | 0.46%   |
| 5.5     | 2         | 0.23%   |
| 4.4     | 2         | 0.23%   |
| 3.10    | 2         | 0.23%   |
| 4.7     | 1         | 0.11%   |
| 2.6     | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 756       | 97.55%  |
| i686    | 14        | 1.81%   |
| aarch64 | 5         | 0.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 372       | 46.1%   |
| KDE5            | 156       | 19.33%  |
| Unknown         | 86        | 10.66%  |
| X-Cinnamon      | 53        | 6.57%   |
| XFCE            | 43        | 5.33%   |
| KDE4            | 28        | 3.47%   |
| MATE            | 14        | 1.73%   |
| KDE             | 12        | 1.49%   |
| Cinnamon        | 9         | 1.12%   |
| Pantheon        | 7         | 0.87%   |
| i3              | 6         | 0.74%   |
| Unity           | 4         | 0.5%    |
| LXQt            | 4         | 0.5%    |
| LXDE            | 2         | 0.25%   |
| KDE6            | 2         | 0.25%   |
| Budgie          | 2         | 0.25%   |
| Trinity         | 1         | 0.12%   |
| i3-with-shmlog  | 1         | 0.12%   |
| Hyprland        | 1         | 0.12%   |
| GNOME Flashback | 1         | 0.12%   |
| GNOME Classic   | 1         | 0.12%   |
| dwm             | 1         | 0.12%   |
| Deepin          | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 591       | 73.69%  |
| Wayland | 146       | 18.2%   |
| Unknown | 52        | 6.48%   |
| Tty     | 13        | 1.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 358       | 44.42%  |
| SDDM    | 118       | 14.64%  |
| GDM     | 113       | 14.02%  |
| GDM3    | 103       | 12.78%  |
| LightDM | 67        | 8.31%   |
| KDM     | 28        | 3.47%   |
| TDM     | 17        | 2.11%   |
| XDM     | 1         | 0.12%   |
| LXDM    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_IL      | 302       | 37.75%  |
| en_US      | 270       | 33.75%  |
| Unknown    | 94        | 11.75%  |
| ru_RU      | 48        | 6%      |
| he_IL      | 35        | 4.38%   |
| C          | 15        | 1.88%   |
| en_GB      | 7         | 0.88%   |
| fr_FR      | 5         | 0.63%   |
| en_AG      | 4         | 0.5%    |
| uk_UA      | 2         | 0.25%   |
| POSIX      | 2         | 0.25%   |
| es_ES      | 2         | 0.25%   |
| de_DE      | 2         | 0.25%   |
| ru_UA      | 1         | 0.13%   |
| pt_BR      | 1         | 0.13%   |
| it_IT      | 1         | 0.13%   |
| is         | 1         | 0.13%   |
| en_US.UTF8 | 1         | 0.13%   |
| en_NZ      | 1         | 0.13%   |
| en_IE      | 1         | 0.13%   |
| en_DK      | 1         | 0.13%   |
| en_CA      | 1         | 0.13%   |
| en_AU      | 1         | 0.13%   |
| C.UTF8     | 1         | 0.13%   |
| aa_DJ      | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 425       | 53.19%  |
| BIOS | 374       | 46.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 571       | 71.82%  |
| Btrfs   | 84        | 10.57%  |
| Overlay | 53        | 6.67%   |
| Tmpfs   | 38        | 4.78%   |
| Unknown | 24        | 3.02%   |
| Xfs     | 17        | 2.14%   |
| Zfs     | 4         | 0.5%    |
| Ext3    | 2         | 0.25%   |
| F2fs    | 1         | 0.13%   |
| Ext2    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 369       | 46.3%   |
| GPT     | 347       | 43.54%  |
| MBR     | 81        | 10.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 684       | 86.69%  |
| Yes       | 105       | 13.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 562       | 71.23%  |
| Yes       | 227       | 28.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 181       | 23.39%  |
| Lenovo                  | 144       | 18.6%   |
| Dell                    | 118       | 15.25%  |
| Gigabyte Technology     | 102       | 13.18%  |
| Hewlett-Packard         | 80        | 10.34%  |
| MSI                     | 18        | 2.33%   |
| Intel                   | 15        | 1.94%   |
| Acer                    | 15        | 1.94%   |
| Apple                   | 13        | 1.68%   |
| ASRock                  | 10        | 1.29%   |
| Valve                   | 9         | 1.16%   |
| Samsung Electronics     | 7         | 0.9%    |
| Unknown                 | 6         | 0.78%   |
| Toshiba                 | 5         | 0.65%   |
| Fujitsu                 | 4         | 0.52%   |
| Supermicro              | 3         | 0.39%   |
| Nvidia                  | 3         | 0.39%   |
| LG Electronics          | 3         | 0.39%   |
| Timi                    | 2         | 0.26%   |
| Razer                   | 2         | 0.26%   |
| Raspberry Pi Foundation | 2         | 0.26%   |
| Pegatron                | 2         | 0.26%   |
| Huanan                  | 2         | 0.26%   |
| Fujitsu Siemens         | 2         | 0.26%   |
| Foxconn                 | 2         | 0.26%   |
| AMI                     | 2         | 0.26%   |
| Alienware               | 2         | 0.26%   |
| TYAN Computer           | 1         | 0.13%   |
| System76                | 1         | 0.13%   |
| Shuttle                 | 1         | 0.13%   |
| Purism                  | 1         | 0.13%   |
| Notebook                | 1         | 0.13%   |
| Neousys Technology      | 1         | 0.13%   |
| N-one                   | 1         | 0.13%   |
| Microsoft               | 1         | 0.13%   |
| ITI LIMITED             | 1         | 0.13%   |
| IP3 Tech                | 1         | 0.13%   |
| HUAWEI                  | 1         | 0.13%   |
| Heptagon Systems        | 1         | 0.13%   |
| Hardkernel              | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 11        | 1.42%   |
| Unknown                               | 11        | 1.42%   |
| Valve Jupiter                         | 9         | 1.16%   |
| Gigabyte H61M-S2PV                    | 4         | 0.52%   |
| Nvidia Tegra                          | 3         | 0.39%   |
| MSI MS-7592                           | 3         | 0.39%   |
| Lenovo IdeaPad 5 14ITL05 82FE         | 3         | 0.39%   |
| HP Pavilion Notebook                  | 3         | 0.39%   |
| HP Compaq Presario CQ61               | 3         | 0.39%   |
| Gigabyte H61M-S1                      | 3         | 0.39%   |
| Gigabyte G31M-ES2L                    | 3         | 0.39%   |
| Dell Latitude 7400                    | 3         | 0.39%   |
| Dell Inspiron 3593                    | 3         | 0.39%   |
| ASUS UX331UA                          | 3         | 0.39%   |
| ASUS PRIME Z490-P                     | 3         | 0.39%   |
| ASUS P8H61-M LX R2.0                  | 3         | 0.39%   |
| ASUS H110M-A/M.2                      | 3         | 0.39%   |
| RPi Raspberry Pi 4 Model B Rev 1.4    | 2         | 0.26%   |
| MSI MS-7982                           | 2         | 0.26%   |
| Lenovo V14-IIL 82C4                   | 2         | 0.26%   |
| Lenovo Legion Y530-15ICH 81FV         | 2         | 0.26%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 0.26%   |
| Lenovo IdeaPad L340-15IWL 81LG        | 2         | 0.26%   |
| Lenovo G560 0679                      | 2         | 0.26%   |
| Lenovo G50-80 80L0                    | 2         | 0.26%   |
| Intel NUC8i7BEH                       | 2         | 0.26%   |
| Intel NUC8i3BEH                       | 2         | 0.26%   |
| Intel DH77EB AAG39073-304             | 2         | 0.26%   |
| HP ZBook 15 G5                        | 2         | 0.26%   |
| HP ZBook 15 G3                        | 2         | 0.26%   |
| HP Spectre x360 Convertible 13-aw0xxx | 2         | 0.26%   |
| HP ProBook 430 G6                     | 2         | 0.26%   |
| HP EliteBook 840 G6                   | 2         | 0.26%   |
| HP EliteBook 840 G5                   | 2         | 0.26%   |
| Gigabyte Z390 GAMING X                | 2         | 0.26%   |
| Gigabyte X570 AORUS ULTRA             | 2         | 0.26%   |
| Gigabyte P55-UD3L                     | 2         | 0.26%   |
| Gigabyte H97-HD3                      | 2         | 0.26%   |
| Gigabyte H55M-D2H                     | 2         | 0.26%   |
| Gigabyte B460HD3                      | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 58        | 7.49%   |
| ASUS PRIME         | 39        | 5.04%   |
| Dell Latitude      | 35        | 4.52%   |
| ASUS ROG           | 26        | 3.36%   |
| Lenovo IdeaPad     | 25        | 3.23%   |
| Dell Inspiron      | 24        | 3.1%    |
| ASUS VivoBook      | 23        | 2.97%   |
| Dell Vostro        | 19        | 2.45%   |
| HP Pavilion        | 14        | 1.81%   |
| Dell OptiPlex      | 13        | 1.68%   |
| Dell XPS           | 11        | 1.42%   |
| ASUS All           | 11        | 1.42%   |
| Acer Aspire        | 11        | 1.42%   |
| Unknown            | 11        | 1.42%   |
| ASUS TUF           | 10        | 1.29%   |
| Valve Jupiter      | 9         | 1.16%   |
| Lenovo Legion      | 9         | 1.16%   |
| Lenovo Yoga        | 8         | 1.03%   |
| HP ZBook           | 8         | 1.03%   |
| HP EliteBook       | 8         | 1.03%   |
| Lenovo ThinkCentre | 7         | 0.9%    |
| HP ProBook         | 7         | 0.9%    |
| HP Compaq          | 7         | 0.9%    |
| Dell Precision     | 7         | 0.9%    |
| ASUS ZenBook       | 6         | 0.78%   |
| HP Laptop          | 5         | 0.65%   |
| Gigabyte Z690      | 5         | 0.65%   |
| ASUS ASUS          | 5         | 0.65%   |
| Toshiba Satellite  | 4         | 0.52%   |
| Lenovo IdeaPadFlex | 4         | 0.52%   |
| HP ProDesk         | 4         | 0.52%   |
| Gigabyte X570      | 4         | 0.52%   |
| Gigabyte H61M-S2PV | 4         | 0.52%   |
| Fujitsu LIFEBOOK   | 4         | 0.52%   |
| Dell PowerEdge     | 4         | 0.52%   |
| ASUS H110M-A       | 4         | 0.52%   |
| Nvidia Tegra       | 3         | 0.39%   |
| MSI MS-7592        | 3         | 0.39%   |
| Lenovo V520-15IKL  | 3         | 0.39%   |
| Lenovo G50-80      | 3         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 88        | 11.37%  |
| 2018    | 87        | 11.24%  |
| 2020    | 82        | 10.59%  |
| 2021    | 62        | 8.01%   |
| 2012    | 56        | 7.24%   |
| 2017    | 50        | 6.46%   |
| 2015    | 44        | 5.68%   |
| 2016    | 40        | 5.17%   |
| 2014    | 39        | 5.04%   |
| 2013    | 39        | 5.04%   |
| 2011    | 39        | 5.04%   |
| 2022    | 33        | 4.26%   |
| 2010    | 33        | 4.26%   |
| 2009    | 24        | 3.1%    |
| 2008    | 18        | 2.33%   |
| 2023    | 17        | 2.2%    |
| 2007    | 14        | 1.81%   |
| Unknown | 5         | 0.65%   |
| 2006    | 3         | 0.39%   |
| 2024    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 407       | 52.58%  |
| Desktop        | 307       | 39.66%  |
| Convertible    | 19        | 2.45%   |
| Mini pc        | 16        | 2.07%   |
| Server         | 8         | 1.03%   |
| Tablet         | 6         | 0.78%   |
| All in one     | 6         | 0.78%   |
| System on chip | 5         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 709       | 91.01%  |
| Enabled  | 70        | 8.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 772       | 99.74%  |
| Yes  | 2         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 192       | 24.33%  |
| 4.01-8.0        | 155       | 19.65%  |
| 32.01-64.0      | 137       | 17.36%  |
| 8.01-16.0       | 129       | 16.35%  |
| 3.01-4.0        | 92        | 11.66%  |
| 64.01-256.0     | 34        | 4.31%   |
| 1.01-2.0        | 29        | 3.68%   |
| 24.01-32.0      | 10        | 1.27%   |
| 2.01-3.0        | 7         | 0.89%   |
| 0.51-1.0        | 3         | 0.38%   |
| More than 256.0 | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 235       | 27.39%  |
| 2.01-3.0    | 194       | 22.61%  |
| 4.01-8.0    | 157       | 18.3%   |
| 3.01-4.0    | 122       | 14.22%  |
| 8.01-16.0   | 84        | 9.79%   |
| 0.51-1.0    | 45        | 5.24%   |
| 16.01-24.0  | 10        | 1.17%   |
| 0.01-0.5    | 8         | 0.93%   |
| 24.01-32.0  | 1         | 0.12%   |
| 64.01-256.0 | 1         | 0.12%   |
| Unknown     | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 496       | 62.16%  |
| 2      | 178       | 22.31%  |
| 3      | 73        | 9.15%   |
| 4      | 22        | 2.76%   |
| 5      | 14        | 1.75%   |
| 0      | 5         | 0.63%   |
| 6      | 4         | 0.5%    |
| 7      | 3         | 0.38%   |
| 8      | 2         | 0.25%   |
| 10     | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 554       | 70.84%  |
| Yes       | 228       | 29.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 659       | 84.81%  |
| No        | 118       | 15.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 574       | 73.68%  |
| No        | 205       | 26.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 60.54%  |
| No        | 309       | 39.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Israel  | 774       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Tel Aviv            | 317       | 37.29%  |
| Ramat Gan           | 64        | 7.53%   |
| Haifa               | 46        | 5.41%   |
| Jerusalem           | 36        | 4.24%   |
| Petaẖ Tiqwa       | 27        | 3.18%   |
| Petah Tikva         | 25        | 2.94%   |
| Herzliya            | 22        | 2.59%   |
| Netanya             | 19        | 2.24%   |
| Rishon LeZiyyon     | 18        | 2.12%   |
| Rishon LeTsiyyon    | 16        | 1.88%   |
| Holon               | 15        | 1.76%   |
| Givatayim           | 15        | 1.76%   |
| Rehovot             | 13        | 1.53%   |
| Ramat HaSharon      | 10        | 1.18%   |
| Raanana             | 9         | 1.06%   |
| Kfar Saba           | 9         | 1.06%   |
| Beersheba           | 9         | 1.06%   |
| Ashquelon           | 9         | 1.06%   |
| Ashdod              | 9         | 1.06%   |
| Rosh HaAyin         | 8         | 0.94%   |
| Nahariya            | 8         | 0.94%   |
| Kiryat Ono          | 8         | 0.94%   |
| Qiryat Ata          | 7         | 0.82%   |
| Lod                 | 6         | 0.71%   |
| Hod HaSharon        | 6         | 0.71%   |
| Bat Yam             | 6         | 0.71%   |
| Ness Ziona          | 5         | 0.59%   |
| Pardes Hanna Karkur | 4         | 0.47%   |
| Givat Shmuel        | 4         | 0.47%   |
| Bet Shemesh         | 4         | 0.47%   |
| Yehud               | 3         | 0.35%   |
| Yaqum               | 3         | 0.35%   |
| Tiberias            | 3         | 0.35%   |
| Tel Mond            | 3         | 0.35%   |
| Sderot              | 3         | 0.35%   |
| Ramla               | 3         | 0.35%   |
| Qiryat Bialik       | 3         | 0.35%   |
| Karmi’el          | 3         | 0.35%   |
| Hadera              | 3         | 0.35%   |
| Ganei Tikva         | 3         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 178       | 293    | 15.78%  |
| Samsung Electronics       | 167       | 252    | 14.8%   |
| Seagate                   | 125       | 182    | 11.08%  |
| SanDisk                   | 99        | 121    | 8.78%   |
| Kingston                  | 65        | 82     | 5.76%   |
| Toshiba                   | 60        | 69     | 5.32%   |
| Hitachi                   | 51        | 81     | 4.52%   |
| Intel                     | 45        | 72     | 3.99%   |
| SK hynix                  | 38        | 52     | 3.37%   |
| Crucial                   | 31        | 54     | 2.75%   |
| Micron Technology         | 26        | 35     | 2.3%    |
| HGST                      | 26        | 30     | 2.3%    |
| Unknown                   | 23        | 29     | 2.04%   |
| Transcend                 | 23        | 31     | 2.04%   |
| KIOXIA                    | 15        | 16     | 1.33%   |
| A-DATA Technology         | 13        | 16     | 1.15%   |
| Corsair                   | 12        | 21     | 1.06%   |
| StoreJet                  | 9         | 10     | 0.8%    |
| Silicon Motion            | 8         | 8      | 0.71%   |
| Apple                     | 8         | 11     | 0.71%   |
| XPG                       | 6         | 12     | 0.53%   |
| Phison Electronics        | 6         | 7      | 0.53%   |
| Phison                    | 6         | 7      | 0.53%   |
| China                     | 6         | 8      | 0.53%   |
| Unknown                   | 6         | 7      | 0.53%   |
| SPCC                      | 5         | 5      | 0.44%   |
| Micron/Crucial Technology | 4         | 4      | 0.35%   |
| LITEON                    | 4         | 4      | 0.35%   |
| JMicron Technology        | 4         | 4      | 0.35%   |
| Fujitsu                   | 4         | 5      | 0.35%   |
| ADATA Technology          | 4         | 4      | 0.35%   |
| PNY                       | 3         | 4      | 0.27%   |
| OCZ                       | 3         | 3      | 0.27%   |
| Netac                     | 3         | 3      | 0.27%   |
| LITEONIT                  | 3         | 3      | 0.27%   |
| Apacer                    | 3         | 3      | 0.27%   |
| XrayDisk                  | 2         | 3      | 0.18%   |
| USB3.0                    | 2         | 2      | 0.18%   |
| SSSTC                     | 2         | 2      | 0.18%   |
| O2 Micro                  | 2         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SanDisk SSD PLUS 240GB                             | 19        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 14        | 1.12%   |
| Kingston SA400S37240G 240GB SSD                    | 13        | 1.04%   |
| Seagate ST500DM002-1BD142 500GB                    | 11        | 0.88%   |
| Samsung NVMe SSD Drive 512GB                       | 10        | 0.8%    |
| Hitachi HDS721050CLA362 500GB                      | 10        | 0.8%    |
| Seagate ST500LT012-1DG142 500GB                    | 9         | 0.72%   |
| Samsung SSD 860 EVO 500GB                          | 9         | 0.72%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 8         | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 8         | 0.64%   |
| Kingston SV300S37A120G 120GB SSD                   | 8         | 0.64%   |
| Unknown MMC Card  64GB                             | 7         | 0.56%   |
| Intel NVMe SSD Drive 512GB                         | 7         | 0.56%   |
| WDC WD20PURX-64P6ZY0 2TB                           | 6         | 0.48%   |
| Toshiba DT01ACA100 1TB                             | 6         | 0.48%   |
| SK hynix NVMe SSD Drive 256GB                      | 6         | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                     | 6         | 0.48%   |
| Samsung SSD 850 EVO 500GB                          | 6         | 0.48%   |
| Samsung SSD 850 EVO 250GB                          | 6         | 0.48%   |
| Samsung NVMe SSD Drive 500GB                       | 6         | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 6         | 0.48%   |
| HGST HTS545050A7E680 500GB                         | 6         | 0.48%   |
| Crucial CT500MX500SSD1 500GB                       | 6         | 0.48%   |
| Unknown                                            | 6         | 0.48%   |
| Toshiba MQ01ABF050 500GB                           | 5         | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                      | 5         | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB                     | 5         | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 0.4%    |
| SanDisk NVMe SSD Drive 512GB                       | 5         | 0.4%    |
| SanDisk Extreme SSD 1TB                            | 5         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                     | 5         | 0.4%    |
| Samsung SSD 860 QVO 1TB                            | 5         | 0.4%    |
| Samsung SSD 860 EVO 250GB                          | 5         | 0.4%    |
| Kingston SA400S37120G 120GB SSD                    | 5         | 0.4%    |
| Intel SSDPEKNW512G8 512GB                          | 5         | 0.4%    |
| Intel SSDPEKNU512GZ 512GB                          | 5         | 0.4%    |
| HGST HTS721010A9E630 1TB                           | 5         | 0.4%    |
| HGST HTS541010A9E680 1TB                           | 5         | 0.4%    |
| Crucial CT250MX500SSD1 250GB                       | 5         | 0.4%    |
| WDC WD5000AAKX-08U6AA0 500GB                       | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 148       | 254    | 35.49%  |
| Seagate             | 125       | 181    | 29.98%  |
| Hitachi             | 51        | 81     | 12.23%  |
| Toshiba             | 41        | 48     | 9.83%   |
| HGST                | 26        | 30     | 6.24%   |
| Samsung Electronics | 11        | 17     | 2.64%   |
| Fujitsu             | 4         | 5      | 0.96%   |
| Apple               | 3         | 3      | 0.72%   |
| JMicron Technology  | 2         | 2      | 0.48%   |
| USB3.0              | 1         | 1      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |
| TPH01204000GB       | 1         | 1      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| Mercury             | 1         | 1      | 0.24%   |
| IBM/Hitachi         | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 84     | 18.21%  |
| SanDisk             | 55        | 68     | 16.42%  |
| Kingston            | 49        | 61     | 14.63%  |
| Crucial             | 25        | 46     | 7.46%   |
| Transcend           | 20        | 28     | 5.97%   |
| Micron Technology   | 14        | 18     | 4.18%   |
| Intel               | 13        | 16     | 3.88%   |
| A-DATA Technology   | 11        | 13     | 3.28%   |
| WDC                 | 10        | 10     | 2.99%   |
| SK hynix            | 10        | 21     | 2.99%   |
| Corsair             | 10        | 17     | 2.99%   |
| Toshiba             | 6         | 6      | 1.79%   |
| China               | 6         | 8      | 1.79%   |
| StoreJet            | 4         | 4      | 1.19%   |
| LITEON              | 4         | 4      | 1.19%   |
| Apple               | 4         | 4      | 1.19%   |
| SPCC                | 3         | 3      | 0.9%    |
| PNY                 | 3         | 4      | 0.9%    |
| OCZ                 | 3         | 3      | 0.9%    |
| LITEONIT            | 3         | 3      | 0.9%    |
| Apacer              | 3         | 3      | 0.9%    |
| Netac               | 2         | 2      | 0.6%    |
| KIOXIA-EXCERIA      | 2         | 2      | 0.6%    |
| XrayDisk            | 1         | 2      | 0.3%    |
| Verbatim            | 1         | 1      | 0.3%    |
| USB3.0              | 1         | 1      | 0.3%    |
| Seagate             | 1         | 1      | 0.3%    |
| Plextor             | 1         | 1      | 0.3%    |
| Patriot             | 1         | 1      | 0.3%    |
| OCZ-VERTEX3         | 1         | 1      | 0.3%    |
| NGFF                | 1         | 1      | 0.3%    |
| LS600               | 1         | 1      | 0.3%    |
| Lenovo              | 1         | 1      | 0.3%    |
| KingSpec            | 1         | 1      | 0.3%    |
| KingDian            | 1         | 2      | 0.3%    |
| faspeed             | 1         | 1      | 0.3%    |
| External            | 1         | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 342       | 627    | 34.06%  |
| NVMe    | 331       | 470    | 32.97%  |
| SSD     | 295       | 444    | 29.38%  |
| MMC     | 24        | 33     | 2.39%   |
| Unknown | 12        | 15     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 498       | 1029   | 55.21%  |
| NVMe | 331       | 468    | 36.7%   |
| SAS  | 49        | 59     | 5.43%   |
| MMC  | 24        | 33     | 2.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 383       | 649    | 58.21%  |
| 0.51-1.0   | 173       | 241    | 26.29%  |
| 1.01-2.0   | 66        | 109    | 10.03%  |
| 3.01-4.0   | 16        | 39     | 2.43%   |
| 2.01-3.0   | 13        | 19     | 1.98%   |
| 4.01-10.0  | 5         | 8      | 0.76%   |
| 10.01-20.0 | 2         | 6      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 196       | 24.14%  |
| 101-250        | 193       | 23.77%  |
| 501-1000       | 138       | 17%     |
| 1001-2000      | 63        | 7.76%   |
| 1-20           | 54        | 6.65%   |
| 51-100         | 40        | 4.93%   |
| More than 3000 | 39        | 4.8%    |
| 2001-3000      | 39        | 4.8%    |
| 21-50          | 29        | 3.57%   |
| Unknown        | 21        | 2.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 313       | 37.13%  |
| 21-50          | 143       | 16.96%  |
| 101-250        | 116       | 13.76%  |
| 51-100         | 79        | 9.37%   |
| 251-500        | 65        | 7.71%   |
| 501-1000       | 43        | 5.1%    |
| 1001-2000      | 34        | 4.03%   |
| Unknown        | 21        | 2.49%   |
| 2001-3000      | 16        | 1.9%    |
| More than 3000 | 13        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 5         | 7      | 5.95%   |
| WDC WD10EARS-00Y5B1 1TB               | 2         | 4      | 2.38%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 2      | 2.38%   |
| Hitachi HTS545025B9A300 250GB         | 2         | 2      | 2.38%   |
| Hitachi HDS721050DLE630 500GB         | 2         | 2      | 2.38%   |
| Hitachi HDS721050CLA362 500GB         | 2         | 3      | 2.38%   |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 2.38%   |
| WDC WDS240G1G0B-00RC30 240GB SSD      | 1         | 1      | 1.19%   |
| WDC WD6400BPVT-75HXZT1 640GB          | 1         | 1      | 1.19%   |
| WDC WD5001AALS-00LWTA0 500GB          | 1         | 1      | 1.19%   |
| WDC WD5000BPVT-75HXZT1 500GB          | 1         | 1      | 1.19%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.19%   |
| WDC WD5000AAKX-221CA1 500GB           | 1         | 1      | 1.19%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 1.19%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 1.19%   |
| WDC WD30PURX-64P6ZY0 3TB              | 1         | 1      | 1.19%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 1.19%   |
| WDC WD2500BEVT-22A23T0 250GB          | 1         | 2      | 1.19%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 1      | 1.19%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 2      | 1.19%   |
| WDC WD1600BJKT-75F4T0 160GB           | 1         | 1      | 1.19%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 2      | 1.19%   |
| WDC WD10EZEX-00ZF5A0 1TB              | 1         | 1      | 1.19%   |
| WDC WD10EZEX-00RKKA0 1TB              | 1         | 1      | 1.19%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 1      | 1.19%   |
| WDC WD10EAVS-32D7B1 1TB               | 1         | 1      | 1.19%   |
| WDC WD10EADS-00M2B0 1TB               | 1         | 1      | 1.19%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 1      | 1.19%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 1.19%   |
| Toshiba MK6475GSX 640GB               | 1         | 1      | 1.19%   |
| Toshiba MK5075GSX 500GB               | 1         | 1      | 1.19%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 1.19%   |
| Toshiba MK1646GSX 160GB               | 1         | 1      | 1.19%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD | 1         | 5      | 1.19%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.19%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 1.19%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.19%   |
| Seagate ST9120817AS 120GB             | 1         | 1      | 1.19%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.19%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.19%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 23        | 30     | 28.4%   |
| Seagate             | 16        | 20     | 19.75%  |
| Hitachi             | 15        | 19     | 18.52%  |
| HGST                | 10        | 12     | 12.35%  |
| Toshiba             | 5         | 5      | 6.17%   |
| SK hynix            | 2         | 6      | 2.47%   |
| SanDisk             | 2         | 3      | 2.47%   |
| Samsung Electronics | 2         | 3      | 2.47%   |
| Corsair             | 2         | 3      | 2.47%   |
| Intel               | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 1      | 1.23%   |
| Fujitsu             | 1         | 1      | 1.23%   |
| Crucial             | 1         | 1      | 1.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 29     | 30.99%  |
| Seagate             | 16        | 20     | 22.54%  |
| Hitachi             | 15        | 19     | 21.13%  |
| HGST                | 10        | 12     | 14.08%  |
| Toshiba             | 5         | 5      | 7.04%   |
| Samsung Electronics | 2         | 3      | 2.82%   |
| Fujitsu             | 1         | 1      | 1.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 89     | 85.51%  |
| SSD  | 9         | 15     | 13.04%  |
| NVMe | 1         | 1      | 1.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MK3256GSY 320GB         | 1         | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB | 1         | 1      | 33.33%  |
| Hitachi HTS547550A9E384 500GB   | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 445       | 922    | 53.17%  |
| Works    | 323       | 558    | 38.59%  |
| Malfunc  | 67        | 105    | 8%      |
| Failed   | 2         | 4      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 580       | 57.14%  |
| Samsung Electronics                     | 109       | 10.74%  |
| AMD                                     | 70        | 6.9%    |
| SanDisk                                 | 63        | 6.21%   |
| SK hynix                                | 28        | 2.76%   |
| Kingston Technology Company             | 18        | 1.77%   |
| KIOXIA                                  | 15        | 1.48%   |
| Toshiba America Info Systems            | 14        | 1.38%   |
| Phison Electronics                      | 13        | 1.28%   |
| Micron Technology                       | 12        | 1.18%   |
| Silicon Motion                          | 11        | 1.08%   |
| ADATA Technology                        | 11        | 1.08%   |
| Micron/Crucial Technology               | 10        | 0.99%   |
| JMicron Technology                      | 10        | 0.99%   |
| Marvell Technology Group                | 9         | 0.89%   |
| Nvidia                                  | 8         | 0.79%   |
| ASMedia Technology                      | 8         | 0.79%   |
| Realtek Semiconductor                   | 4         | 0.39%   |
| Transcend                               | 3         | 0.3%    |
| LSI Logic / Symbios Logic               | 3         | 0.3%    |
| VIA Technologies                        | 2         | 0.2%    |
| Union Memory (Shenzhen)                 | 2         | 0.2%    |
| Solid State Storage Technology          | 2         | 0.2%    |
| O2 Micro                                | 2         | 0.2%    |
| Solidigm                                | 1         | 0.1%    |
| Shenzhen Unionmemory Information System | 1         | 0.1%    |
| Shenzhen Longsys Electronics            | 1         | 0.1%    |
| MAXIO Technology (Hangzhou)             | 1         | 0.1%    |
| Broadcom / LSI                          | 1         | 0.1%    |
| Biwin Storage Technology                | 1         | 0.1%    |
| Apple                                   | 1         | 0.1%    |
| Adaptec                                 | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 57        | 5.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 52        | 4.58%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 50        | 4.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 32        | 2.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 31        | 2.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 31        | 2.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28        | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 26        | 2.29%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 21        | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 20        | 1.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 19        | 1.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 18        | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 18        | 1.59%   |
| Intel SATA Controller [RAID mode]                                                       | 17        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17        | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16        | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 16        | 1.41%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 1.41%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 16        | 1.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 16        | 1.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 15        | 1.32%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15        | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 14        | 1.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 14        | 1.23%   |
| Intel SSD 660P Series                                                                   | 14        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 1.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 12        | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 11        | 0.97%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 10        | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 10        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 10        | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 9         | 0.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 8         | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 526       | 51.67%  |
| NVMe | 332       | 32.61%  |
| RAID | 82        | 8.06%   |
| IDE  | 75        | 7.37%   |
| SAS  | 3         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 673       | 86.95%  |
| AMD          | 95        | 12.27%  |
| ARM          | 4         | 0.52%   |
| CentaurHauls | 1         | 0.13%   |
| Unknown      | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 20        | 2.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 17        | 2.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 11        | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 11        | 1.41%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 10        | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 10        | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 10        | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 10        | 1.28%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 9         | 1.16%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9         | 1.16%   |
| AMD Custom APU 0405                         | 9         | 1.16%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 8         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 8         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 8         | 1.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 7         | 0.9%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 6         | 0.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 6         | 0.77%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 6         | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 6         | 0.77%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 5         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 5         | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 5         | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5         | 0.64%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 0.64%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5         | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 5         | 0.64%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 5         | 0.64%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 5         | 0.64%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 4         | 0.51%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz | 4         | 0.51%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 4         | 0.51%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 4         | 0.51%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 0.51%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4         | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 4         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4         | 0.51%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 4         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 213       | 27.41%  |
| Intel Core i5           | 179       | 23.04%  |
| Other                   | 105       | 13.51%  |
| Intel Core i3           | 61        | 7.85%   |
| AMD Ryzen 5             | 24        | 3.09%   |
| Intel Xeon              | 21        | 2.7%    |
| Intel Core 2 Duo        | 20        | 2.57%   |
| AMD Ryzen 7             | 20        | 2.57%   |
| Intel Pentium Dual-Core | 18        | 2.32%   |
| Intel Pentium           | 17        | 2.19%   |
| AMD Ryzen 9             | 14        | 1.8%    |
| Intel Atom              | 12        | 1.54%   |
| Intel Celeron           | 11        | 1.42%   |
| Intel Core i9           | 8         | 1.03%   |
| Intel Pentium Dual      | 7         | 0.9%    |
| Intel Genuine           | 5         | 0.64%   |
| AMD A8                  | 4         | 0.51%   |
| AMD Ryzen 3             | 3         | 0.39%   |
| AMD FX                  | 3         | 0.39%   |
| AMD A6                  | 3         | 0.39%   |
| Intel Pentium Gold      | 2         | 0.26%   |
| Intel Core m3           | 2         | 0.26%   |
| Intel Core 2 Quad       | 2         | 0.26%   |
| AMD Ryzen 7 PRO         | 2         | 0.26%   |
| AMD A10                 | 2         | 0.26%   |
| Intel Xeon Gold         | 1         | 0.13%   |
| Intel Pentium Silver    | 1         | 0.13%   |
| Intel Pentium 4         | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |
| Intel Core 2            | 1         | 0.13%   |
| Intel Celeron Dual-Core | 1         | 0.13%   |
| CentaurHauls VIA C7     | 1         | 0.13%   |
| ARM BCM                 | 1         | 0.13%   |
| AMD Turion 64 X2 Mobile | 1         | 0.13%   |
| AMD Ryzen Threadripper  | 1         | 0.13%   |
| AMD Ryzen 5 PRO         | 1         | 0.13%   |
| AMD Ryzen 3 PRO         | 1         | 0.13%   |
| AMD Phenom II X4        | 1         | 0.13%   |
| AMD Phenom              | 1         | 0.13%   |
| AMD EPYC                | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 319       | 41.11%  |
| 2       | 234       | 30.15%  |
| 6       | 84        | 10.82%  |
| 8       | 68        | 8.76%   |
| 12      | 17        | 2.19%   |
| 10      | 17        | 2.19%   |
| 14      | 11        | 1.42%   |
| 1       | 10        | 1.29%   |
| 16      | 9         | 1.16%   |
| 3       | 2         | 0.26%   |
| 44      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 24      | 1         | 0.13%   |
| 20      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 763       | 98.58%  |
| 2       | 9         | 1.16%   |
| 4       | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 578       | 74.29%  |
| 1       | 199       | 25.58%  |
| Unknown | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 758       | 97.93%  |
| Unknown        | 13        | 1.68%   |
| 32-bit         | 3         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 274       | 33.46%  |
| 0x306c3    | 33        | 4.03%   |
| 0x206a7    | 33        | 4.03%   |
| 0x806ea    | 31        | 3.79%   |
| 0x306a9    | 29        | 3.54%   |
| 0x1067a    | 27        | 3.3%    |
| 0x806ec    | 26        | 3.17%   |
| 0x806c1    | 25        | 3.05%   |
| 0x506e3    | 24        | 2.93%   |
| 0x906e9    | 22        | 2.69%   |
| 0x906ea    | 19        | 2.32%   |
| 0x406e3    | 16        | 1.95%   |
| 0x806e9    | 14        | 1.71%   |
| 0x706e5    | 13        | 1.59%   |
| 0x906ed    | 12        | 1.47%   |
| 0x306d4    | 12        | 1.47%   |
| 0x20655    | 10        | 1.22%   |
| 0xa0652    | 9         | 1.1%    |
| 0x90672    | 9         | 1.1%    |
| 0x6fd      | 9         | 1.1%    |
| 0x40651    | 9         | 1.1%    |
| 0x08108109 | 7         | 0.85%   |
| 0xa0671    | 6         | 0.73%   |
| 0x806eb    | 6         | 0.73%   |
| 0x106e5    | 6         | 0.73%   |
| 0xa0655    | 5         | 0.61%   |
| 0xa0653    | 5         | 0.61%   |
| 0x906a4    | 5         | 0.61%   |
| 0x906a3    | 5         | 0.61%   |
| 0x306e4    | 5         | 0.61%   |
| 0x08701021 | 5         | 0.61%   |
| 0x706a1    | 4         | 0.49%   |
| 0x10676    | 4         | 0.49%   |
| 0x0a50000c | 4         | 0.49%   |
| 0x08600104 | 4         | 0.49%   |
| 0x806d1    | 3         | 0.37%   |
| 0x406c4    | 3         | 0.37%   |
| 0x106ca    | 3         | 0.37%   |
| 0x106c2    | 3         | 0.37%   |
| 0x106a5    | 3         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 194       | 24.94%  |
| Haswell          | 64        | 8.23%   |
| Skylake          | 55        | 7.07%   |
| Unknown          | 50        | 6.43%   |
| IvyBridge        | 49        | 6.3%    |
| SandyBridge      | 42        | 5.4%    |
| Penryn           | 40        | 5.14%   |
| TigerLake        | 37        | 4.76%   |
| CometLake        | 32        | 4.11%   |
| IceLake          | 27        | 3.47%   |
| Alderlake Hybrid | 27        | 3.47%   |
| Broadwell        | 21        | 2.7%    |
| Zen 2            | 20        | 2.57%   |
| Westmere         | 19        | 2.44%   |
| Zen 3            | 14        | 1.8%    |
| Core             | 14        | 1.8%    |
| Zen+             | 13        | 1.67%   |
| Nehalem          | 11        | 1.41%   |
| Silvermont       | 9         | 1.16%   |
| Zen              | 7         | 0.9%    |
| Piledriver       | 6         | 0.77%   |
| Goldmont plus    | 5         | 0.64%   |
| Bonnell          | 5         | 0.64%   |
| Steamroller      | 3         | 0.39%   |
| K10              | 3         | 0.39%   |
| Tremont          | 2         | 0.26%   |
| Puma             | 2         | 0.26%   |
| K8 Hammer        | 2         | 0.26%   |
| NetBurst         | 1         | 0.13%   |
| Jaguar           | 1         | 0.13%   |
| Goldmont         | 1         | 0.13%   |
| Excavator        | 1         | 0.13%   |
| Bulldozer        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 529       | 55.98%  |
| Nvidia                     | 296       | 31.32%  |
| AMD                        | 114       | 12.06%  |
| ASPEED Technology          | 3         | 0.32%   |
| Matrox Electronics Systems | 2         | 0.21%   |
| VIA Technologies           | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 36        | 3.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 3.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 2.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 27        | 2.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 2.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 2.18%   |
| Intel HD Graphics 530                                                                    | 19        | 1.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 1.66%   |
| Intel HD Graphics 630                                                                    | 16        | 1.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 1.56%   |
| Intel HD Graphics 620                                                                    | 15        | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 15        | 1.56%   |
| Intel HD Graphics 5500                                                                   | 14        | 1.45%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 1.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 1.04%   |
| Intel Iris Plus Graphics G7                                                              | 10        | 1.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.93%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 9         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 0.83%   |
| Nvidia GT218 [GeForce 210]                                                               | 7         | 0.73%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 7         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.73%   |
| Intel AlderLake-S GT1                                                                    | 7         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 6         | 0.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 6         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.62%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6         | 0.62%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 6         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 374       | 47.58%  |
| 1 x Nvidia      | 151       | 19.21%  |
| Intel + Nvidia  | 132       | 16.79%  |
| 1 x AMD         | 81        | 10.31%  |
| AMD + Nvidia    | 15        | 1.91%   |
| Intel + AMD     | 13        | 1.65%   |
| Other           | 5         | 0.64%   |
| 2 x AMD         | 5         | 0.64%   |
| 2 x Intel       | 4         | 0.51%   |
| 1 x ASPEED      | 2         | 0.25%   |
| 1 x VIA         | 1         | 0.13%   |
| Nvidia + Matrox | 1         | 0.13%   |
| Nvidia + ASPEED | 1         | 0.13%   |
| 1 x Matrox      | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 568       | 72.08%  |
| Proprietary | 182       | 23.1%   |
| Unknown     | 38        | 4.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 503       | 63.11%  |
| 1.01-2.0   | 86        | 10.79%  |
| 3.01-4.0   | 58        | 7.28%   |
| 0.01-0.5   | 40        | 5.02%   |
| 7.01-8.0   | 38        | 4.77%   |
| 0.51-1.0   | 35        | 4.39%   |
| 5.01-6.0   | 15        | 1.88%   |
| 8.01-16.0  | 13        | 1.63%   |
| 2.01-3.0   | 6         | 0.75%   |
| 16.01-24.0 | 2         | 0.25%   |
| 24.01-32.0 | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 141       | 16.13%  |
| Dell                    | 99        | 11.33%  |
| AU Optronics            | 89        | 10.18%  |
| Chimei Innolux          | 74        | 8.47%   |
| LG Display              | 67        | 7.67%   |
| BOE                     | 66        | 7.55%   |
| Goldstar                | 38        | 4.35%   |
| Philips                 | 33        | 3.78%   |
| Lenovo                  | 28        | 3.2%    |
| Sharp                   | 20        | 2.29%   |
| AOC                     | 19        | 2.17%   |
| Hewlett-Packard         | 18        | 2.06%   |
| Ancor Communications    | 13        | 1.49%   |
| ASUSTek Computer        | 11        | 1.26%   |
| Chi Mei Optoelectronics | 10        | 1.14%   |
| ViewSonic               | 8         | 0.92%   |
| Valve                   | 8         | 0.92%   |
| Unknown                 | 8         | 0.92%   |
| InfoVision              | 8         | 0.92%   |
| Apple                   | 8         | 0.92%   |
| Acer                    | 8         | 0.92%   |
| BenQ                    | 7         | 0.8%    |
| PANDA                   | 5         | 0.57%   |
| LG Philips              | 5         | 0.57%   |
| CSO                     | 5         | 0.57%   |
| Toshiba                 | 4         | 0.46%   |
| Sony                    | 4         | 0.46%   |
| LG Electronics          | 4         | 0.46%   |
| Lenovo Group Limited    | 4         | 0.46%   |
| Gigabyte Technology     | 4         | 0.46%   |
| VIE                     | 3         | 0.34%   |
| SANYO                   | 3         | 0.34%   |
| Panasonic               | 3         | 0.34%   |
| Unknown                 | 3         | 0.34%   |
| RIS                     | 2         | 0.23%   |
| Plain Tree Systems      | 2         | 0.23%   |
| NEX                     | 2         | 0.23%   |
| Iiyama                  | 2         | 0.23%   |
| Hyundai ImageQuest      | 2         | 0.23%   |
| HKC                     | 2         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 8         | 0.88%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 8         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 8         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 8         | 0.88%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 7         | 0.77%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 6         | 0.66%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 5         | 0.55%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 5         | 0.55%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 5         | 0.55%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 5         | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 4         | 0.44%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 4         | 0.44%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 4         | 0.44%   |
| Philips 222EL PHLC052 1920x1080 476x268mm 21.5-inch                  | 4         | 0.44%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 4         | 0.44%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                 | 4         | 0.44%   |
| Dell P2219H DELA115 1920x1080 476x267mm 21.5-inch                    | 4         | 0.44%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 4         | 0.44%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                      | 4         | 0.44%   |
| Samsung Electronics SyncMaster SAM044B 1680x1050 474x296mm 22.0-inch | 3         | 0.33%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch | 3         | 0.33%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch  | 3         | 0.33%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 0.33%   |
| Lenovo E27q-20 LEN62D0 2560x1440 597x336mm 27.0-inch                 | 3         | 0.33%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 3         | 0.33%   |
| Dell U2715H DELD067 2560x1440 600x340mm 27.2-inch                    | 3         | 0.33%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                     | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 3         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 3         | 0.33%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                    | 3         | 0.33%   |
| AU Optronics LCD Monitor AUOE68C 2560x1440 309x174mm 14.0-inch       | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO633D 1920x1080 309x174mm 14.0-inch       | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch       | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO102D 1920x1080 293x165mm 13.2-inch       | 3         | 0.33%   |
| Unknown                                                              | 3         | 0.33%   |
| ViewSonic VX2237 SERIES VSC2C24 1680x1050 474x296mm 22.0-inch        | 2         | 0.22%   |
| Unknown LCD Monitor RIS RD24L 1920x1080                              | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 422       | 51.53%  |
| 1366x768 (WXGA)    | 94        | 11.48%  |
| 3840x2160 (4K)     | 61        | 7.45%   |
| 2560x1440 (QHD)    | 45        | 5.49%   |
| 1920x1200 (WUXGA)  | 28        | 3.42%   |
| 1680x1050 (WSXGA+) | 28        | 3.42%   |
| 1280x1024 (SXGA)   | 22        | 2.69%   |
| 1280x800 (WXGA)    | 14        | 1.71%   |
| Unknown            | 12        | 1.47%   |
| 1600x900 (HD+)     | 10        | 1.22%   |
| 1440x900 (WXGA+)   | 10        | 1.22%   |
| 800x1280           | 8         | 0.98%   |
| 3440x1440          | 8         | 0.98%   |
| 2560x1600          | 8         | 0.98%   |
| 2560x1080          | 8         | 0.98%   |
| 2880x1800          | 5         | 0.61%   |
| 3200x1800 (QHD+)   | 4         | 0.49%   |
| 3840x1080          | 3         | 0.37%   |
| 1024x768 (XGA)     | 3         | 0.37%   |
| 2880x1620          | 2         | 0.24%   |
| 2160x1440          | 2         | 0.24%   |
| 1920x540           | 2         | 0.24%   |
| 1360x768           | 2         | 0.24%   |
| 1280x768           | 2         | 0.24%   |
| 1024x600           | 2         | 0.24%   |
| 5360x1440          | 1         | 0.12%   |
| 5120x1440          | 1         | 0.12%   |
| 4480x1440          | 1         | 0.12%   |
| 3840x2400          | 1         | 0.12%   |
| 3840x1200          | 1         | 0.12%   |
| 3520x1080          | 1         | 0.12%   |
| 3456x2160          | 1         | 0.12%   |
| 3200x1200          | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2304x1440          | 1         | 0.12%   |
| 2304x1024          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 2256x1504          | 1         | 0.12%   |
| 1600x2560          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 188       | 21.61%  |
| 13      | 95        | 10.92%  |
| 24      | 89        | 10.23%  |
| 27      | 78        | 8.97%   |
| 14      | 69        | 7.93%   |
| 23      | 67        | 7.7%    |
| 21      | 67        | 7.7%    |
| Unknown | 38        | 4.37%   |
| 22      | 24        | 2.76%   |
| 17      | 22        | 2.53%   |
| 19      | 16        | 1.84%   |
| 34      | 13        | 1.49%   |
| 16      | 11        | 1.26%   |
| 12      | 11        | 1.26%   |
| 31      | 10        | 1.15%   |
| 20      | 9         | 1.03%   |
| 7       | 8         | 0.92%   |
| 40      | 6         | 0.69%   |
| 84      | 5         | 0.57%   |
| 72      | 5         | 0.57%   |
| 33      | 5         | 0.57%   |
| 26      | 4         | 0.46%   |
| 18      | 4         | 0.46%   |
| 60      | 3         | 0.34%   |
| 11      | 3         | 0.34%   |
| 65      | 2         | 0.23%   |
| 32      | 2         | 0.23%   |
| 25      | 2         | 0.23%   |
| 10      | 2         | 0.23%   |
| 8       | 2         | 0.23%   |
| 142     | 1         | 0.11%   |
| 86      | 1         | 0.11%   |
| 54      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 48      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 319       | 37.31%  |
| 501-600        | 219       | 25.61%  |
| 401-500        | 106       | 12.4%   |
| 201-300        | 65        | 7.6%    |
| Unknown        | 38        | 4.44%   |
| 351-400        | 28        | 3.27%   |
| 701-800        | 20        | 2.34%   |
| 601-700        | 20        | 2.34%   |
| 1501-2000      | 10        | 1.17%   |
| 1001-1500      | 10        | 1.17%   |
| 1-100          | 8         | 0.94%   |
| 801-900        | 7         | 0.82%   |
| 101-200        | 2         | 0.23%   |
| 901-1000       | 2         | 0.23%   |
| More than 2000 | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 577       | 74.94%  |
| 16/10   | 101       | 13.12%  |
| Unknown | 37        | 4.81%   |
| 5/4     | 18        | 2.34%   |
| 21/9    | 13        | 1.69%   |
| 0.67    | 8         | 1.04%   |
| 3/2     | 7         | 0.91%   |
| 4/3     | 5         | 0.65%   |
| 1.96    | 1         | 0.13%   |
| 1.00    | 1         | 0.13%   |
| 0.58    | 1         | 0.13%   |
| 0.56    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 201       | 23.37%  |
| 101-110        | 188       | 21.86%  |
| 81-90          | 121       | 14.07%  |
| 301-350        | 82        | 9.53%   |
| 71-80          | 42        | 4.88%   |
| 151-200        | 38        | 4.42%   |
| Unknown        | 38        | 4.42%   |
| 351-500        | 31        | 3.6%    |
| 251-300        | 27        | 3.14%   |
| More than 1000 | 20        | 2.33%   |
| 61-70          | 11        | 1.28%   |
| 141-150        | 11        | 1.28%   |
| 1-40           | 10        | 1.16%   |
| 121-130        | 10        | 1.16%   |
| 111-120        | 10        | 1.16%   |
| 501-1000       | 10        | 1.16%   |
| 131-140        | 4         | 0.47%   |
| 51-60          | 3         | 0.35%   |
| 41-50          | 2         | 0.23%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 280       | 33.37%  |
| 121-160       | 218       | 25.98%  |
| 101-120       | 188       | 22.41%  |
| 161-240       | 65        | 7.75%   |
| Unknown       | 38        | 4.53%   |
| More than 240 | 34        | 4.05%   |
| 1-50          | 16        | 1.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 590       | 74.4%   |
| 2     | 142       | 17.91%  |
| 0     | 39        | 4.92%   |
| 3     | 20        | 2.52%   |
| 4     | 2         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 419       | 36.12%  |
| Intel                           | 398       | 34.31%  |
| Qualcomm Atheros                | 108       | 9.31%   |
| Broadcom                        | 41        | 3.53%   |
| MediaTek                        | 22        | 1.9%    |
| Ralink Technology               | 20        | 1.72%   |
| TP-Link                         | 18        | 1.55%   |
| Broadcom Limited                | 18        | 1.55%   |
| Lenovo                          | 12        | 1.03%   |
| Edimax Technology               | 10        | 0.86%   |
| ASIX Electronics                | 10        | 0.86%   |
| Samsung Electronics             | 7         | 0.6%    |
| Marvell Technology Group        | 7         | 0.6%    |
| DisplayLink                     | 7         | 0.6%    |
| Xiaomi                          | 6         | 0.52%   |
| Qualcomm Atheros Communications | 5         | 0.43%   |
| Nvidia                          | 5         | 0.43%   |
| Google                          | 4         | 0.34%   |
| Ralink                          | 3         | 0.26%   |
| Huawei Technologies             | 3         | 0.26%   |
| U-Blox                          | 2         | 0.17%   |
| Texas Instruments               | 2         | 0.17%   |
| OPPO Electronics                | 2         | 0.17%   |
| Microsoft                       | 2         | 0.17%   |
| ICS Advent                      | 2         | 0.17%   |
| D-Link                          | 2         | 0.17%   |
| Aquantia                        | 2         | 0.17%   |
| VIA Technologies                | 1         | 0.09%   |
| U.S. Robotics                   | 1         | 0.09%   |
| Toshiba                         | 1         | 0.09%   |
| STMicroelectronics              | 1         | 0.09%   |
| Sierra Wireless                 | 1         | 0.09%   |
| ROCCAT                          | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| PEAK-System Technik             | 1         | 0.09%   |
| Nokia Mobile Phones             | 1         | 0.09%   |
| Mellanox Technologies           | 1         | 0.09%   |
| Linksys                         | 1         | 0.09%   |
| LG Electronics                  | 1         | 0.09%   |
| HMD Global                      | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 274       | 19.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 45        | 3.26%   |
| Intel Wireless 8265 / 8275                                             | 32        | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 2.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 28        | 2.03%   |
| Intel Wi-Fi 6 AX201                                                    | 28        | 2.03%   |
| Intel Wi-Fi 6 AX200                                                    | 27        | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 22        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                   | 19        | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 18        | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 17        | 1.23%   |
| Intel I211 Gigabit Network Connection                                  | 16        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 14        | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 14        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 13        | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 13        | 0.94%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 13        | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                                  | 13        | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 13        | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 12        | 0.87%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 0.87%   |
| Intel Wireless 3165                                                    | 11        | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 10        | 0.72%   |
| Intel Wireless 8260                                                    | 10        | 0.72%   |
| Intel Wireless 3160                                                    | 10        | 0.72%   |
| Realtek 802.11ac NIC                                                   | 9         | 0.65%   |
| Intel Wireless 7265                                                    | 9         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 0.58%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 8         | 0.58%   |
| Intel I210 Gigabit Network Connection                                  | 8         | 0.58%   |
| Intel Ethernet Controller I225-V                                       | 8         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                   | 8         | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 0.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 291       | 47.78%  |
| Realtek Semiconductor           | 97        | 15.93%  |
| Qualcomm Atheros                | 86        | 14.12%  |
| Broadcom                        | 35        | 5.75%   |
| MediaTek                        | 22        | 3.61%   |
| Ralink Technology               | 20        | 3.28%   |
| TP-Link                         | 17        | 2.79%   |
| Broadcom Limited                | 13        | 2.13%   |
| Edimax Technology               | 10        | 1.64%   |
| Qualcomm Atheros Communications | 5         | 0.82%   |
| Ralink                          | 3         | 0.49%   |
| Microsoft                       | 2         | 0.33%   |
| D-Link                          | 2         | 0.33%   |
| Sierra Wireless                 | 1         | 0.16%   |
| Qualcomm                        | 1         | 0.16%   |
| Marvell Technology Group        | 1         | 0.16%   |
| Dell                            | 1         | 0.16%   |
| BUFFALO                         | 1         | 0.16%   |
| ASUSTek Computer                | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 32        | 5.2%    |
| Intel Wi-Fi 6 AX201                                            | 28        | 4.55%   |
| Intel Wi-Fi 6 AX200                                            | 27        | 4.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 22        | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 2.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 14        | 2.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 14        | 2.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 2.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 2.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 13        | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 1.95%   |
| Intel Wireless 3165                                            | 11        | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.63%   |
| Intel Wireless 8260                                            | 10        | 1.63%   |
| Intel Wireless 3160                                            | 10        | 1.63%   |
| Realtek 802.11ac NIC                                           | 9         | 1.46%   |
| Intel Wireless 7265                                            | 9         | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 1.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 8         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 7         | 1.14%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 7         | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 1.14%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 7         | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 0.98%   |
| Intel Wireless 7260                                            | 6         | 0.98%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 6         | 0.98%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                | 5         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 380       | 52.27%  |
| Intel                    | 219       | 30.12%  |
| Qualcomm Atheros         | 33        | 4.54%   |
| Broadcom                 | 16        | 2.2%    |
| Lenovo                   | 12        | 1.65%   |
| ASIX Electronics         | 10        | 1.38%   |
| Samsung Electronics      | 7         | 0.96%   |
| DisplayLink              | 7         | 0.96%   |
| Xiaomi                   | 6         | 0.83%   |
| Marvell Technology Group | 6         | 0.83%   |
| Broadcom Limited         | 6         | 0.83%   |
| Nvidia                   | 5         | 0.69%   |
| Google                   | 4         | 0.55%   |
| OPPO Electronics         | 2         | 0.28%   |
| ICS Advent               | 2         | 0.28%   |
| Huawei Technologies      | 2         | 0.28%   |
| Aquantia                 | 2         | 0.28%   |
| VIA Technologies         | 1         | 0.14%   |
| TP-Link                  | 1         | 0.14%   |
| Mellanox Technologies    | 1         | 0.14%   |
| Linksys                  | 1         | 0.14%   |
| HMD Global               | 1         | 0.14%   |
| Davicom Semiconductor    | 1         | 0.14%   |
| Attansic Technology      | 1         | 0.14%   |
| Accton Technology        | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 274       | 36.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 45        | 5.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 3.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 28        | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 23        | 3.06%   |
| Intel Ethernet Connection (2) I219-V                                   | 19        | 2.53%   |
| Intel I211 Gigabit Network Connection                                  | 16        | 2.13%   |
| Intel Ethernet Connection (7) I219-LM                                  | 13        | 1.73%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 1.6%    |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 1.46%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 1.2%    |
| Intel I210 Gigabit Network Connection                                  | 8         | 1.07%   |
| Intel Ethernet Controller I225-V                                       | 8         | 1.07%   |
| Intel Ethernet Connection (7) I219-V                                   | 8         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                                  | 7         | 0.93%   |
| Intel Ethernet Connection (10) I219-V                                  | 7         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.8%    |
| Lenovo ThinkPad TBT 3 Dock                                             | 6         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.67%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                                  | 5         | 0.67%   |
| Intel Ethernet Connection (14) I219-V                                  | 5         | 0.67%   |
| Intel Ethernet Connection (11) I219-LM                                 | 5         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.53%   |
| Lenovo USB-C Dock Ethernet                                             | 4         | 0.53%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.53%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.53%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 0.53%   |
| DisplayLink LAPDOCK                                                    | 4         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.4%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 3         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 658       | 52.72%  |
| WiFi     | 574       | 45.99%  |
| Modem    | 14        | 1.12%   |
| Unknown  | 2         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 424       | 52.22%  |
| Ethernet | 387       | 47.66%  |
| Modem    | 1         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 381       | 48.97%  |
| 1     | 370       | 47.56%  |
| 3     | 16        | 2.06%   |
| 0     | 8         | 1.03%   |
| 7     | 1         | 0.13%   |
| 6     | 1         | 0.13%   |
| 4     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 628       | 78.8%   |
| Yes  | 169       | 21.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 256       | 53.44%  |
| Realtek Semiconductor           | 42        | 8.77%   |
| Qualcomm Atheros Communications | 39        | 8.14%   |
| IMC Networks                    | 39        | 8.14%   |
| Cambridge Silicon Radio         | 30        | 6.26%   |
| Broadcom                        | 15        | 3.13%   |
| Apple                           | 13        | 2.71%   |
| Foxconn / Hon Hai               | 9         | 1.88%   |
| Lite-On Technology              | 7         | 1.46%   |
| Dell                            | 6         | 1.25%   |
| ASUSTek Computer                | 5         | 1.04%   |
| TP-Link                         | 3         | 0.63%   |
| Realtek                         | 3         | 0.63%   |
| Hewlett-Packard                 | 3         | 0.63%   |
| Toshiba                         | 2         | 0.42%   |
| MediaTek                        | 2         | 0.42%   |
| Askey Computer                  | 2         | 0.42%   |
| Marvell Semiconductor           | 1         | 0.21%   |
| Chicony Electronics             | 1         | 0.21%   |
| Actions                         | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 67        | 13.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 46        | 9.6%    |
| Intel Bluetooth wireless interface                  | 44        | 9.19%   |
| Intel Bluetooth Device                              | 38        | 7.93%   |
| Realtek Bluetooth Radio                             | 32        | 6.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 30        | 6.26%   |
| Intel AX200 Bluetooth                               | 24        | 5.01%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 4.38%   |
| IMC Networks Wireless_Device                        | 16        | 3.34%   |
| IMC Networks Bluetooth Radio                        | 13        | 2.71%   |
| Intel AX211 Bluetooth                               | 11        | 2.3%    |
| Intel AX210 Bluetooth                               | 10        | 2.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 1.25%   |
| Lite-On Bluetooth Device                            | 6         | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.25%   |
| Apple Bluetooth Host Controller                     | 6         | 1.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.04%   |
| IMC Networks Bluetooth Device                       | 5         | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.84%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.84%   |
| TP-Link UB500 Adapter                               | 3         | 0.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 0.63%   |
| Realtek Bluetooth Radio                             | 3         | 0.63%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.42%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.42%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.42%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.42%   |
| Foxconn / Hon Hai BT                                | 2         | 0.42%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 2         | 0.42%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.42%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.42%   |
| Broadcom BCM20702A0                                 | 2         | 0.42%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 649       | 58%     |
| Nvidia                                       | 217       | 19.39%  |
| AMD                                          | 122       | 10.9%   |
| Logitech                                     | 14        | 1.25%   |
| C-Media Electronics                          | 14        | 1.25%   |
| Lenovo                                       | 13        | 1.16%   |
| Creative Labs                                | 8         | 0.71%   |
| Realtek Semiconductor                        | 6         | 0.54%   |
| XMOS                                         | 5         | 0.45%   |
| GN Netcom                                    | 5         | 0.45%   |
| Creative Technology                          | 5         | 0.45%   |
| Texas Instruments                            | 4         | 0.36%   |
| Microsoft                                    | 4         | 0.36%   |
| Hewlett-Packard                              | 4         | 0.36%   |
| Generalplus Technology                       | 4         | 0.36%   |
| Focusrite-Novation                           | 4         | 0.36%   |
| Razer USA                                    | 3         | 0.27%   |
| Kingston Technology                          | 3         | 0.27%   |
| JMTek                                        | 3         | 0.27%   |
| Cambridge Silicon Radio                      | 3         | 0.27%   |
| Unknown                                      | 3         | 0.27%   |
| VIA Technologies                             | 2         | 0.18%   |
| SteelSeries ApS                              | 2         | 0.18%   |
| Plantronics                                  | 2         | 0.18%   |
| FIFINE Microphones                           | 2         | 0.18%   |
| ASUSTek Computer                             | 2         | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.09%   |
| Sennheiser Communications                    | 1         | 0.09%   |
| Samson Technologies                          | 1         | 0.09%   |
| PreSonus Audio Electronics                   | 1         | 0.09%   |
| Micro Star International                     | 1         | 0.09%   |
| Meridian                                     | 1         | 0.09%   |
| M-Audio                                      | 1         | 0.09%   |
| iCreate Technologies                         | 1         | 0.09%   |
| HiBy                                         | 1         | 0.09%   |
| Giga-Byte Technology                         | 1         | 0.09%   |
| EGO SYStems                                  | 1         | 0.09%   |
| DigiTech                                     | 1         | 0.09%   |
| Dell                                         | 1         | 0.09%   |
| BR25                                         | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 75        | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 50        | 3.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 45        | 3.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 37        | 2.95%   |
| AMD Family 17h/19h HD Audio Controller                                     | 36        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 35        | 2.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 34        | 2.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 33        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 32        | 2.55%   |
| Intel 200 Series PCH HD Audio                                              | 31        | 2.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 25        | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 24        | 1.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 22        | 1.75%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 1.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 1.51%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 1.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17        | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 17        | 1.35%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 17        | 1.35%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 17        | 1.35%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16        | 1.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 1.2%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 1.2%    |
| Intel 8 Series HD Audio Controller                                         | 15        | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 13        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13        | 1.04%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 12        | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 12        | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 11        | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 0.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10        | 0.8%    |
| AMD FCH Azalia Controller                                                  | 10        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 99        | 19.26%  |
| SK hynix            | 93        | 18.09%  |
| Micron Technology   | 73        | 14.2%   |
| Kingston            | 68        | 13.23%  |
| Unknown             | 44        | 8.56%   |
| Crucial             | 35        | 6.81%   |
| Corsair             | 25        | 4.86%   |
| G.Skill             | 24        | 4.67%   |
| Ramaxel Technology  | 15        | 2.92%   |
| A-DATA Technology   | 8         | 1.56%   |
| Transcend           | 6         | 1.17%   |
| Elpida              | 5         | 0.97%   |
| Nanya Technology    | 4         | 0.78%   |
| Team                | 3         | 0.58%   |
| GeIL                | 2         | 0.39%   |
| V-Color             | 1         | 0.19%   |
| Unknown (09D5)      | 1         | 0.19%   |
| Patriot             | 1         | 0.19%   |
| Lexar Co Limited    | 1         | 0.19%   |
| KETECH              | 1         | 0.19%   |
| Avant               | 1         | 0.19%   |
| ASint Technology    | 1         | 0.19%   |
| Ankowall            | 1         | 0.19%   |
| 48spaces            | 1         | 0.19%   |
| Unknown             | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 5         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 5         | 0.92%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s       | 5         | 0.92%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 4         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.73%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 4         | 0.73%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s      | 4         | 0.73%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 4         | 0.73%   |
| Kingston RAM 9905622-058.A00G 8GB DIMM DDR4 2133MT/s         | 4         | 0.73%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 3         | 0.55%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 3         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 3         | 0.55%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 3         | 0.55%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 0.55%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 3         | 0.55%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM DDR5 4800MT/s     | 3         | 0.55%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 3         | 0.55%   |
| Micron RAM 8ATF2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s        | 3         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 3         | 0.55%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 3         | 0.55%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s        | 3         | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 2         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 2         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 2         | 0.37%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 2         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 2         | 0.37%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 2         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                | 2         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 2         | 0.37%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s             | 2         | 0.37%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 2         | 0.37%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s         | 2         | 0.37%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s      | 2         | 0.37%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 2         | 0.37%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 246       | 55.91%  |
| DDR3    | 95        | 21.59%  |
| Unknown | 25        | 5.68%   |
| DDR2    | 18        | 4.09%   |
| LPDDR3  | 16        | 3.64%   |
| DDR5    | 16        | 3.64%   |
| LPDDR4  | 7         | 1.59%   |
| SDRAM   | 5         | 1.14%   |
| LPDDR5  | 5         | 1.14%   |
| DDR     | 5         | 1.14%   |
| DRAM    | 2         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 236       | 53.76%  |
| DIMM         | 170       | 38.72%  |
| Row Of Chips | 30        | 6.83%   |
| Chip         | 2         | 0.46%   |
| Unknown      | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 157       | 32.64%  |
| 16384 | 122       | 25.36%  |
| 4096  | 113       | 23.49%  |
| 2048  | 49        | 10.19%  |
| 32768 | 24        | 4.99%   |
| 1024  | 16        | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 88        | 18.41%  |
| 2667    | 74        | 15.48%  |
| 1600    | 67        | 14.02%  |
| 2400    | 36        | 7.53%   |
| 2133    | 35        | 7.32%   |
| 1333    | 20        | 4.18%   |
| 800     | 16        | 3.35%   |
| 667     | 14        | 2.93%   |
| 4800    | 12        | 2.51%   |
| 3600    | 12        | 2.51%   |
| 1867    | 9         | 1.88%   |
| 1334    | 9         | 1.88%   |
| Unknown | 8         | 1.67%   |
| 6400    | 6         | 1.26%   |
| 4267    | 6         | 1.26%   |
| 3800    | 6         | 1.26%   |
| 3266    | 6         | 1.26%   |
| 1067    | 6         | 1.26%   |
| 5600    | 3         | 0.63%   |
| 3466    | 3         | 0.63%   |
| 2933    | 3         | 0.63%   |
| 2666    | 3         | 0.63%   |
| 1866    | 3         | 0.63%   |
| 1800    | 3         | 0.63%   |
| 533     | 3         | 0.63%   |
| 6000    | 2         | 0.42%   |
| 3933    | 2         | 0.42%   |
| 3666    | 2         | 0.42%   |
| 3534    | 2         | 0.42%   |
| 3151    | 2         | 0.42%   |
| 2000    | 2         | 0.42%   |
| 400     | 2         | 0.42%   |
| 49926   | 1         | 0.21%   |
| 8400    | 1         | 0.21%   |
| 5900    | 1         | 0.21%   |
| 4400    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 3334    | 1         | 0.21%   |
| 3066    | 1         | 0.21%   |
| 3000    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 50%     |
| Samsung Electronics   | 5         | 19.23%  |
| Canon                 | 2         | 7.69%   |
| Brother Industries    | 2         | 7.69%   |
| Seiko Epson           | 1         | 3.85%   |
| Lexmark International | 1         | 3.85%   |
| GODEX INTERNATIONAL   | 1         | 3.85%   |
| BIXOLON               | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP Officejet 4500 G510g-m          | 3         | 11.54%  |
| HP DeskJet 4670 series             | 3         | 11.54%  |
| Samsung M2070 Series               | 2         | 7.69%   |
| HP Printing Support                | 2         | 7.69%   |
| Seiko Epson ET-2710 Series         | 1         | 3.85%   |
| Samsung SCX-4623 Series            | 1         | 3.85%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 3.85%   |
| Samsung M288x Series               | 1         | 3.85%   |
| Lexmark International CS417dn      | 1         | 3.85%   |
| HP Smart Tank 510 series           | 1         | 3.85%   |
| HP OfficeJet 5600 (USBHUB)         | 1         | 3.85%   |
| HP HP LaserJet M14-M17             | 1         | 3.85%   |
| HP Deskjet 4640 series             | 1         | 3.85%   |
| HP DeskJet 2700 series             | 1         | 3.85%   |
| GODEX INTERNATIONAL DT2            | 1         | 3.85%   |
| Canon TR7500 series                | 1         | 3.85%   |
| Canon PIXMA MX490 Series           | 1         | 3.85%   |
| Brother Printer                    | 1         | 3.85%   |
| Brother MFC-J497DW                 | 1         | 3.85%   |
| BIXOLON BIXOLON_SLP-T400           | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 2         | 66.67%  |
| Canon CanoScan LiDE 220 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 73        | 15.08%  |
| Chicony Electronics                    | 69        | 14.26%  |
| Realtek Semiconductor                  | 52        | 10.74%  |
| Microdia                               | 38        | 7.85%   |
| Logitech                               | 37        | 7.64%   |
| Sunplus Innovation Technology          | 29        | 5.99%   |
| Microsoft                              | 28        | 5.79%   |
| Bison Electronics                      | 20        | 4.13%   |
| Apple                                  | 15        | 3.1%    |
| Syntek                                 | 12        | 2.48%   |
| Quanta                                 | 12        | 2.48%   |
| Acer                                   | 11        | 2.27%   |
| Luxvisions Innotech Limited            | 10        | 2.07%   |
| Lite-On Technology                     | 10        | 2.07%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 2.07%   |
| Suyin                                  | 8         | 1.65%   |
| Generalplus Technology                 | 7         | 1.45%   |
| Samsung Electronics                    | 6         | 1.24%   |
| Silicon Motion                         | 5         | 1.03%   |
| Lenovo                                 | 4         | 0.83%   |
| Alcor Micro                            | 3         | 0.62%   |
| Sonix Technology                       | 2         | 0.41%   |
| Jieli Technology                       | 2         | 0.41%   |
| Cubeternet                             | 2         | 0.41%   |
| ALi                                    | 2         | 0.41%   |
| Z-Star Microelectronics                | 1         | 0.21%   |
| YGTek                                  | 1         | 0.21%   |
| Yealink Network Technology             | 1         | 0.21%   |
| Xiaomi                                 | 1         | 0.21%   |
| WaveRider Communications               | 1         | 0.21%   |
| Ricoh                                  | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| OmniVision Technologies                | 1         | 0.21%   |
| KYE Systems (Mouse Systems)            | 1         | 0.21%   |
| icSpring                               | 1         | 0.21%   |
| Hewlett-Packard                        | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| eMPIA Technology                       | 1         | 0.21%   |
| Aveo Technology                        | 1         | 0.21%   |
| ANYKA                                  | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 28        | 5.77%   |
| Realtek Integrated_Webcam_HD                  | 25        | 5.15%   |
| Chicony integrated camera                     | 25        | 5.15%   |
| Microdia Integrated_Webcam_HD                 | 18        | 3.71%   |
| IMC Networks Integrated Camera                | 18        | 3.71%   |
| Microsoft LifeCam HD-3000                     | 17        | 3.51%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 13        | 2.68%   |
| Syntek Integrated Camera                      | 9         | 1.86%   |
| Logitech Webcam C270                          | 7         | 1.44%   |
| Bison Integrated Camera                       | 7         | 1.44%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 7         | 1.44%   |
| Samsung Galaxy series, misc. (MTP mode)       | 6         | 1.24%   |
| Realtek USB Camera                            | 6         | 1.24%   |
| Acer Integrated Camera                        | 6         | 1.24%   |
| Sunplus Integrated_Webcam_HD                  | 5         | 1.03%   |
| Luxvisions Innotech Limited Integrated Camera | 5         | 1.03%   |
| Logitech HD Pro Webcam C920                   | 5         | 1.03%   |
| Generalplus CAMERA - UVC                      | 5         | 1.03%   |
| Chicony Lenovo EasyCamera                     | 5         | 1.03%   |
| Chicony HP HD Camera                          | 5         | 1.03%   |
| Bison Lenovo EasyCamera                       | 5         | 1.03%   |
| Logitech Webcam C310                          | 4         | 0.82%   |
| Lite-On HP HD Camera                          | 4         | 0.82%   |
| Chicony HP TrueVision HD Camera               | 4         | 0.82%   |
| Chicony EasyCamera                            | 4         | 0.82%   |
| Bison SunplusIT Integrated Camera             | 4         | 0.82%   |
| Sunplus PC Camera                             | 3         | 0.62%   |
| Realtek Lenovo EasyCamera                     | 3         | 0.62%   |
| Realtek Integrated Webcam HD                  | 3         | 0.62%   |
| Microdia Integrated Webcam                    | 3         | 0.62%   |
| Logitech BRIO Ultra HD Webcam                 | 3         | 0.62%   |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 0.62%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 3         | 0.62%   |
| Chicony Integrated Camera (1280x720@30)       | 3         | 0.62%   |
| Syntek Lenovo EasyCamera                      | 2         | 0.41%   |
| Suyin Integrated_Webcam_HD                    | 2         | 0.41%   |
| Suyin Asus Integrated Webcam [CN031B]         | 2         | 0.41%   |
| Sunplus Lenovo EasyCamera                     | 2         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 2         | 0.41%   |
| Sunplus Integrated Camera                     | 2         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 40        | 43.01%  |
| Validity Sensors                   | 25        | 26.88%  |
| Shenzhen Goodix Technology         | 12        | 12.9%   |
| Elan Microelectronics              | 6         | 6.45%   |
| AuthenTec                          | 3         | 3.23%   |
| Upek                               | 2         | 2.15%   |
| STMicroelectronics                 | 2         | 2.15%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.15%   |
| LighTuning Technology              | 1         | 1.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 18.28%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 7.53%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 6.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 5.38%   |
| Elan ELAN:Fingerprint                                                      | 5         | 5.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.3%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 4.3%    |
| Synaptics WBDI                                                             | 4         | 4.3%    |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 4.3%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 3.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.23%   |
| Synaptics UWP WBDI                                                         | 3         | 3.23%   |
| Synaptics  WBDI                                                            | 3         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.15%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.15%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.15%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 2.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.08%   |
| Validity Sensors VFS491                                                    | 1         | 1.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.08%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.08%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.08%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 1.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.08%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.08%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.08%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.08%   |
| AuthenTec AES2810                                                          | 1         | 1.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 28        | 66.67%  |
| Alcor Micro | 14        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 33.33%  |
| Broadcom 58200                                                               | 11        | 26.19%  |
| Broadcom 5880                                                                | 8         | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 529       | 66.37%  |
| 1     | 210       | 26.35%  |
| 2     | 44        | 5.52%   |
| 3     | 9         | 1.13%   |
| 4     | 2         | 0.25%   |
| 7     | 1         | 0.13%   |
| 6     | 1         | 0.13%   |
| 5     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 92        | 27.96%  |
| Graphics card            | 81        | 24.62%  |
| Net/wireless             | 55        | 16.72%  |
| Chipcard                 | 37        | 11.25%  |
| Communication controller | 14        | 4.26%   |
| Camera                   | 14        | 4.26%   |
| Multimedia controller    | 12        | 3.65%   |
| Unassigned class         | 8         | 2.43%   |
| Bluetooth                | 5         | 1.52%   |
| Card reader              | 3         | 0.91%   |
| Storage                  | 2         | 0.61%   |
| Sound                    | 2         | 0.61%   |
| Network                  | 2         | 0.61%   |
| Net/ethernet             | 2         | 0.61%   |

