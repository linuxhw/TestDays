Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 7070

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [a4d77f98eb](https://linux-hardware.org/?probe=a4d77f98eb) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [921aebe62a](https://linux-hardware.org/?probe=921aebe62a) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | Notebook    | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [fa2df8125a](https://linux-hardware.org/?probe=fa2df8125a) | Feb 28, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8cadddf432](https://linux-hardware.org/?probe=8cadddf432) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [72d16085b5](https://linux-hardware.org/?probe=72d16085b5) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f03ce01ac3](https://linux-hardware.org/?probe=f03ce01ac3) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [24952b3b19](https://linux-hardware.org/?probe=24952b3b19) | Feb 27, 2023 |
| AZW           | SER V01                     | Mini pc     | [73570a1c9a](https://linux-hardware.org/?probe=73570a1c9a) | Feb 26, 2023 |
| AZW           | SER V01                     | Mini pc     | [e82b3753f7](https://linux-hardware.org/?probe=e82b3753f7) | Feb 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [319e003280](https://linux-hardware.org/?probe=319e003280) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6a77bfec73](https://linux-hardware.org/?probe=6a77bfec73) | Feb 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [d3e84076c7](https://linux-hardware.org/?probe=d3e84076c7) | Feb 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [32453b16fb](https://linux-hardware.org/?probe=32453b16fb) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2e7905f753](https://linux-hardware.org/?probe=2e7905f753) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [cbadc857a2](https://linux-hardware.org/?probe=cbadc857a2) | Feb 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c7477f1aca](https://linux-hardware.org/?probe=c7477f1aca) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dc7b5cb76e](https://linux-hardware.org/?probe=dc7b5cb76e) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | Notebook    | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | Notebook    | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | Notebook    | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9d39d13682](https://linux-hardware.org/?probe=9d39d13682) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3c27f298a3](https://linux-hardware.org/?probe=3c27f298a3) | Feb 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [8bb60bdebb](https://linux-hardware.org/?probe=8bb60bdebb) | Feb 22, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d8bafec2da](https://linux-hardware.org/?probe=d8bafec2da) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [e7175cb8fe](https://linux-hardware.org/?probe=e7175cb8fe) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | Notebook    | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [56cbaf4274](https://linux-hardware.org/?probe=56cbaf4274) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f75f800bd4](https://linux-hardware.org/?probe=f75f800bd4) | Feb 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a4b049c92b](https://linux-hardware.org/?probe=a4b049c92b) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [804306660e](https://linux-hardware.org/?probe=804306660e) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | Notebook    | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| Acer          | H57M01                      | Desktop     | [5e5e9d03a4](https://linux-hardware.org/?probe=5e5e9d03a4) | Feb 19, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [3f26c5e55c](https://linux-hardware.org/?probe=3f26c5e55c) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [e87ff10942](https://linux-hardware.org/?probe=e87ff10942) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [eff21e4d65](https://linux-hardware.org/?probe=eff21e4d65) | Feb 18, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [cbe7b5e34f](https://linux-hardware.org/?probe=cbe7b5e34f) | Feb 18, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [2c3eb25bc4](https://linux-hardware.org/?probe=2c3eb25bc4) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [0f6c993491](https://linux-hardware.org/?probe=0f6c993491) | Feb 17, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Intel         | DH77DF AAG40293-301         | Desktop     | [f44579d8b4](https://linux-hardware.org/?probe=f44579d8b4) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [db4fef5830](https://linux-hardware.org/?probe=db4fef5830) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | Notebook    | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | Notebook    | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | 371C No DPK                 | All in one  | [02248f5982](https://linux-hardware.org/?probe=02248f5982) | Feb 16, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [5d03d010f4](https://linux-hardware.org/?probe=5d03d010f4) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [db10d61562](https://linux-hardware.org/?probe=db10d61562) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | Notebook    | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Intel         | X79M-S                      | Desktop     | [2d3579e9b7](https://linux-hardware.org/?probe=2d3579e9b7) | Feb 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | Notebook    | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | Notebook    | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Gigabyte      | G41MT-D3V                   | Desktop     | [8a7ce6b005](https://linux-hardware.org/?probe=8a7ce6b005) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [e5b971a4b0](https://linux-hardware.org/?probe=e5b971a4b0) | Feb 14, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [3f40aab3d2](https://linux-hardware.org/?probe=3f40aab3d2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4211a6a7f4](https://linux-hardware.org/?probe=4211a6a7f4) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f3e396ccc3](https://linux-hardware.org/?probe=f3e396ccc3) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [926e34c5a9](https://linux-hardware.org/?probe=926e34c5a9) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | Notebook    | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7458415afe](https://linux-hardware.org/?probe=7458415afe) | Feb 13, 2023 |
| Google        | Droid                       | Notebook    | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [39b7eef9e8](https://linux-hardware.org/?probe=39b7eef9e8) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | Notebook    | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| ASUSTek       | P5VD2-X                     | Desktop     | [32a509e760](https://linux-hardware.org/?probe=32a509e760) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [7b2f03d111](https://linux-hardware.org/?probe=7b2f03d111) | Feb 10, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [0bd59541f9](https://linux-hardware.org/?probe=0bd59541f9) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [f7df102318](https://linux-hardware.org/?probe=f7df102318) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | Notebook    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | Notebook    | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Lenovo        | 3741 NOK                    | Desktop     | [eeb2a331be](https://linux-hardware.org/?probe=eeb2a331be) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [e6f4812d50](https://linux-hardware.org/?probe=e6f4812d50) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [49e414926e](https://linux-hardware.org/?probe=49e414926e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | Notebook    | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a255954f75](https://linux-hardware.org/?probe=a255954f75) | Feb 06, 2023 |
| Unknown       | Intel X79                   | Desktop     | [2ad659fd7a](https://linux-hardware.org/?probe=2ad659fd7a) | Feb 06, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2e5b18f7c5](https://linux-hardware.org/?probe=2e5b18f7c5) | Feb 05, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [c3891f43b5](https://linux-hardware.org/?probe=c3891f43b5) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc948f9e70](https://linux-hardware.org/?probe=dc948f9e70) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| Cisco Syst... | UCSC-C220-M3S 74-10442-0... | Desktop     | [9e8c261333](https://linux-hardware.org/?probe=9e8c261333) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [bede5aa93c](https://linux-hardware.org/?probe=bede5aa93c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | Notebook    | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | Notebook    | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X8DTL                       | Server      | [a3be5cdf41](https://linux-hardware.org/?probe=a3be5cdf41) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| Supermicro    | H12DSU-iN                   | Desktop     | [0bd8186d9e](https://linux-hardware.org/?probe=0bd8186d9e) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | Notebook    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| HP            | 805D                        | Desktop     | [109d9e2356](https://linux-hardware.org/?probe=109d9e2356) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [dafdc36e54](https://linux-hardware.org/?probe=dafdc36e54) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [ed417f3a04](https://linux-hardware.org/?probe=ed417f3a04) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| HP            | 805D                        | Desktop     | [7a8522045b](https://linux-hardware.org/?probe=7a8522045b) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | Notebook    | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [838de293f2](https://linux-hardware.org/?probe=838de293f2) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | Notebook    | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | Desktop     | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | Notebook    | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| HP            | G62                         | Notebook    | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | Notebook    | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | Notebook    | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | Notebook    | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [854a69817d](https://linux-hardware.org/?probe=854a69817d) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Medion        | MS-7675                     | Desktop     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| MSI           | MS-7383                     | Desktop     | [d47659fcf8](https://linux-hardware.org/?probe=d47659fcf8) | Jan 25, 2023 |
| MSI           | MS-7383                     | Desktop     | [b848100b0e](https://linux-hardware.org/?probe=b848100b0e) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | Notebook    | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [872cd0446b](https://linux-hardware.org/?probe=872cd0446b) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b2aecb083b](https://linux-hardware.org/?probe=b2aecb083b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [73779874bd](https://linux-hardware.org/?probe=73779874bd) | Jan 23, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [39f5980c8d](https://linux-hardware.org/?probe=39f5980c8d) | Jan 22, 2023 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [70bd257f2c](https://linux-hardware.org/?probe=70bd257f2c) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [88d7926aef](https://linux-hardware.org/?probe=88d7926aef) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [05c0d355e1](https://linux-hardware.org/?probe=05c0d355e1) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | Notebook    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | Notebook    | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| AZW           | U59                         | Desktop     | [de70883bbf](https://linux-hardware.org/?probe=de70883bbf) | Jan 20, 2023 |
| MSI           | H170 GAMING M3              | Desktop     | [2fe05693b8](https://linux-hardware.org/?probe=2fe05693b8) | Jan 20, 2023 |
| Toshiba       | NB520                       | Notebook    | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [78e90e4760](https://linux-hardware.org/?probe=78e90e4760) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [26e47819f8](https://linux-hardware.org/?probe=26e47819f8) | Jan 18, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [bb86adb1ed](https://linux-hardware.org/?probe=bb86adb1ed) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [4d510de3d8](https://linux-hardware.org/?probe=4d510de3d8) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [9f9fa2e0be](https://linux-hardware.org/?probe=9f9fa2e0be) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6b721444d5](https://linux-hardware.org/?probe=6b721444d5) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [7f1cfd2c02](https://linux-hardware.org/?probe=7f1cfd2c02) | Jan 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [8f292282cb](https://linux-hardware.org/?probe=8f292282cb) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [8b665c7b84](https://linux-hardware.org/?probe=8b665c7b84) | Jan 18, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [70c0fea989](https://linux-hardware.org/?probe=70c0fea989) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| Eii           | GB01                        | Desktop     | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [407f5b7997](https://linux-hardware.org/?probe=407f5b7997) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e44a974b71](https://linux-hardware.org/?probe=e44a974b71) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [04e8f0fb25](https://linux-hardware.org/?probe=04e8f0fb25) | Jan 17, 2023 |
| HP            | 3047h                       | Desktop     | [ad1e495439](https://linux-hardware.org/?probe=ad1e495439) | Jan 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [7d05783196](https://linux-hardware.org/?probe=7d05783196) | Jan 17, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [53b9512a96](https://linux-hardware.org/?probe=53b9512a96) | Jan 17, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0e4dd4c424](https://linux-hardware.org/?probe=0e4dd4c424) | Jan 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | Notebook    | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [be72db11da](https://linux-hardware.org/?probe=be72db11da) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | Notebook    | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [92f9f48219](https://linux-hardware.org/?probe=92f9f48219) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | Notebook    | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | Notebook    | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| MSI           | MS-B1711                    | Desktop     | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [b6b45a8594](https://linux-hardware.org/?probe=b6b45a8594) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [7732b2e5e1](https://linux-hardware.org/?probe=7732b2e5e1) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [af87fe7cb0](https://linux-hardware.org/?probe=af87fe7cb0) | Jan 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c54bd7b409](https://linux-hardware.org/?probe=c54bd7b409) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [6ae0a203a7](https://linux-hardware.org/?probe=6ae0a203a7) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [76ce1a38ba](https://linux-hardware.org/?probe=76ce1a38ba) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [0d01d0023b](https://linux-hardware.org/?probe=0d01d0023b) | Jan 13, 2023 |
| HP            | 8433 11                     | Desktop     | [bc44066299](https://linux-hardware.org/?probe=bc44066299) | Jan 13, 2023 |
| HP            | 212A                        | Desktop     | [92f32467ec](https://linux-hardware.org/?probe=92f32467ec) | Jan 13, 2023 |
| eMachines     | E725                        | Notebook    | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| Biostar       | B250MHC                     | Desktop     | [100bfd62e6](https://linux-hardware.org/?probe=100bfd62e6) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0402d5609b](https://linux-hardware.org/?probe=0402d5609b) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [287fab2142](https://linux-hardware.org/?probe=287fab2142) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | Notebook    | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [bd4173beb3](https://linux-hardware.org/?probe=bd4173beb3) | Jan 12, 2023 |
| Lenovo        | 3102 SDK0K17763 WIN 1801... | Desktop     | [a3ce2fe598](https://linux-hardware.org/?probe=a3ce2fe598) | Jan 12, 2023 |
| Dell          | 0FM586                      | Desktop     | [529bc38dd7](https://linux-hardware.org/?probe=529bc38dd7) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [15648a0bb0](https://linux-hardware.org/?probe=15648a0bb0) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4ce3e32165](https://linux-hardware.org/?probe=4ce3e32165) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [26089f2f9b](https://linux-hardware.org/?probe=26089f2f9b) | Jan 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [32acfb0bee](https://linux-hardware.org/?probe=32acfb0bee) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [64d4a8c163](https://linux-hardware.org/?probe=64d4a8c163) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | Notebook    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | Notebook    | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e829eab59d](https://linux-hardware.org/?probe=e829eab59d) | Jan 10, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [89397e1c47](https://linux-hardware.org/?probe=89397e1c47) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | Notebook    | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | PRO A320M-B                 | Desktop     | [3ffa3cf6f0](https://linux-hardware.org/?probe=3ffa3cf6f0) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| Medion        | AXA                         | All in one  | [37a1a1bc8b](https://linux-hardware.org/?probe=37a1a1bc8b) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | Notebook    | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [60f83cacd0](https://linux-hardware.org/?probe=60f83cacd0) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [f56cccfdc7](https://linux-hardware.org/?probe=f56cccfdc7) | Jan 09, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [1905ffef34](https://linux-hardware.org/?probe=1905ffef34) | Jan 09, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | Notebook    | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3698ce3c60](https://linux-hardware.org/?probe=3698ce3c60) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| Samsung       | 950QED                      | Convertible | [186e8cc52c](https://linux-hardware.org/?probe=186e8cc52c) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Pyramid       | CPYSKI0002 A                | Desktop     | [0b20d79be6](https://linux-hardware.org/?probe=0b20d79be6) | Jan 09, 2023 |
| Dell          | Studio 1558                 | Notebook    | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [10efec9ea3](https://linux-hardware.org/?probe=10efec9ea3) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | Aspire C24-860              | All in one  | [ab25618998](https://linux-hardware.org/?probe=ab25618998) | Jan 07, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | Notebook    | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ef473bb212](https://linux-hardware.org/?probe=ef473bb212) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [7831fb0431](https://linux-hardware.org/?probe=7831fb0431) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [46c8437a45](https://linux-hardware.org/?probe=46c8437a45) | Jan 05, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Unknown       | AM02                        | Mini pc     | [6f6c81bf78](https://linux-hardware.org/?probe=6f6c81bf78) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Dell          | 0FM586                      | Desktop     | [7e181126bc](https://linux-hardware.org/?probe=7e181126bc) | Jan 03, 2023 |
| Dell          | 0FM586                      | Desktop     | [fff469554f](https://linux-hardware.org/?probe=fff469554f) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | Notebook    | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b557b201c4](https://linux-hardware.org/?probe=b557b201c4) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [b0e7bc419b](https://linux-hardware.org/?probe=b0e7bc419b) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| MSI           | Boston                      | Desktop     | [a5fd252dc2](https://linux-hardware.org/?probe=a5fd252dc2) | Dec 30, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | Notebook    | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | Notebook    | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [328cfe3747](https://linux-hardware.org/?probe=328cfe3747) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Teclast       | TbooK 16 Power              | Tablet      | [c8a0dcd956](https://linux-hardware.org/?probe=c8a0dcd956) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | Notebook    | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | Notebook    | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [305018336b](https://linux-hardware.org/?probe=305018336b) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [aef3959b18](https://linux-hardware.org/?probe=aef3959b18) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [9c75de7af7](https://linux-hardware.org/?probe=9c75de7af7) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| Lenovo        | 318D                        | All in one  | [1bc8e7088b](https://linux-hardware.org/?probe=1bc8e7088b) | Dec 24, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | MS-B1421                    | Desktop     | [58968767bd](https://linux-hardware.org/?probe=58968767bd) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [031afb1b20](https://linux-hardware.org/?probe=031afb1b20) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7502622c61](https://linux-hardware.org/?probe=7502622c61) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | Notebook    | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [405443fc24](https://linux-hardware.org/?probe=405443fc24) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2c931919d](https://linux-hardware.org/?probe=d2c931919d) | Dec 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [e048dd7a4e](https://linux-hardware.org/?probe=e048dd7a4e) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| HP            | 8597                        | Desktop     | [5a7ae7c6d7](https://linux-hardware.org/?probe=5a7ae7c6d7) | Dec 19, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c47ff5ba34](https://linux-hardware.org/?probe=c47ff5ba34) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | Notebook    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [631f80f725](https://linux-hardware.org/?probe=631f80f725) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [b6c7b47859](https://linux-hardware.org/?probe=b6c7b47859) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [3af8ddb8cc](https://linux-hardware.org/?probe=3af8ddb8cc) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Lenovo        | 318D                        | All in one  | [da52280286](https://linux-hardware.org/?probe=da52280286) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [bbf59c4c2a](https://linux-hardware.org/?probe=bbf59c4c2a) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [33d60ebbbe](https://linux-hardware.org/?probe=33d60ebbbe) | Dec 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [7d1ece638c](https://linux-hardware.org/?probe=7d1ece638c) | Dec 14, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f46b869c82](https://linux-hardware.org/?probe=f46b869c82) | Dec 14, 2022 |
| Pro-B         | INSYS                       | Desktop     | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9d665864a0](https://linux-hardware.org/?probe=9d665864a0) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [0af09d12d5](https://linux-hardware.org/?probe=0af09d12d5) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | Desktop     | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [238bda76a3](https://linux-hardware.org/?probe=238bda76a3) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [7870cee549](https://linux-hardware.org/?probe=7870cee549) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | Notebook    | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | Notebook    | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | Notebook    | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [e088d4027d](https://linux-hardware.org/?probe=e088d4027d) | Dec 10, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [aefce63130](https://linux-hardware.org/?probe=aefce63130) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [c72c2382b3](https://linux-hardware.org/?probe=c72c2382b3) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [e098953c51](https://linux-hardware.org/?probe=e098953c51) | Dec 09, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [314ed3ea05](https://linux-hardware.org/?probe=314ed3ea05) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [4be2d528de](https://linux-hardware.org/?probe=4be2d528de) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [787a504fd5](https://linux-hardware.org/?probe=787a504fd5) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [345597cd78](https://linux-hardware.org/?probe=345597cd78) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | Notebook    | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Gigabyte      | H510M S2H V2                | Desktop     | [b0b53bc408](https://linux-hardware.org/?probe=b0b53bc408) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | Notebook    | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [0a028304a1](https://linux-hardware.org/?probe=0a028304a1) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | Notebook    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [e46ba957f0](https://linux-hardware.org/?probe=e46ba957f0) | Dec 02, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [85eab170d2](https://linux-hardware.org/?probe=85eab170d2) | Dec 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f27e558f3](https://linux-hardware.org/?probe=0f27e558f3) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | Notebook    | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Medion        | D3F3-EM                     | Desktop     | [ae428a6a6a](https://linux-hardware.org/?probe=ae428a6a6a) | Nov 29, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9d7352a65d](https://linux-hardware.org/?probe=9d7352a65d) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a95de3b373](https://linux-hardware.org/?probe=a95de3b373) | Nov 29, 2022 |
| HP            | Notebook                    | Notebook    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [982d7f7d0b](https://linux-hardware.org/?probe=982d7f7d0b) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [e311874280](https://linux-hardware.org/?probe=e311874280) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | Desktop     | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [fc74dc1357](https://linux-hardware.org/?probe=fc74dc1357) | Nov 22, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [5f50e13ad0](https://linux-hardware.org/?probe=5f50e13ad0) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [81c02af38c](https://linux-hardware.org/?probe=81c02af38c) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [934f31fcac](https://linux-hardware.org/?probe=934f31fcac) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8de96e0012](https://linux-hardware.org/?probe=8de96e0012) | Nov 20, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [71b3224c4d](https://linux-hardware.org/?probe=71b3224c4d) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [9d276a36d8](https://linux-hardware.org/?probe=9d276a36d8) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [362cf69f1f](https://linux-hardware.org/?probe=362cf69f1f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | Notebook    | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | Notebook    | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [469ead98f8](https://linux-hardware.org/?probe=469ead98f8) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | Notebook    | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| HP            | 0AA8h                       | Desktop     | [0f88d64eeb](https://linux-hardware.org/?probe=0f88d64eeb) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c9e0bcd9d6](https://linux-hardware.org/?probe=c9e0bcd9d6) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [f588871a3a](https://linux-hardware.org/?probe=f588871a3a) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [5086b0aa3e](https://linux-hardware.org/?probe=5086b0aa3e) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c16c0f7d8f](https://linux-hardware.org/?probe=c16c0f7d8f) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | Notebook    | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [ea1d9a2fa4](https://linux-hardware.org/?probe=ea1d9a2fa4) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [e0b38a3d54](https://linux-hardware.org/?probe=e0b38a3d54) | Nov 11, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| HP            | 805E                        | All in one  | [fdd688e64e](https://linux-hardware.org/?probe=fdd688e64e) | Nov 11, 2022 |
| HP            | 805E                        | All in one  | [c37ec12e5f](https://linux-hardware.org/?probe=c37ec12e5f) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | Notebook    | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | Notebook    | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [4b5ec389d9](https://linux-hardware.org/?probe=4b5ec389d9) | Nov 09, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [292caf8ccf](https://linux-hardware.org/?probe=292caf8ccf) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [3900976672](https://linux-hardware.org/?probe=3900976672) | Nov 08, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [0aad7f7578](https://linux-hardware.org/?probe=0aad7f7578) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | Notebook    | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | Notebook    | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | Notebook    | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | Notebook    | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| HP            | 8459                        | Desktop     | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| HP            | 1998                        | Desktop     | [ba48cbeebe](https://linux-hardware.org/?probe=ba48cbeebe) | Nov 04, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [93b2e9aea5](https://linux-hardware.org/?probe=93b2e9aea5) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [5466838c04](https://linux-hardware.org/?probe=5466838c04) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [3bec3377a8](https://linux-hardware.org/?probe=3bec3377a8) | Nov 03, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [347b32510b](https://linux-hardware.org/?probe=347b32510b) | Nov 03, 2022 |
| HP            | G62                         | Notebook    | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | Notebook    | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [f0db98f6bb](https://linux-hardware.org/?probe=f0db98f6bb) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [fc832e8881](https://linux-hardware.org/?probe=fc832e8881) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [416db8870a](https://linux-hardware.org/?probe=416db8870a) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | Notebook    | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [55aa58c274](https://linux-hardware.org/?probe=55aa58c274) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| Unknown       | Unknown                     | Soc         | [44fc490d82](https://linux-hardware.org/?probe=44fc490d82) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | Notebook    | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Intel         | H410M-E                     | Desktop     | [854c3ec5b1](https://linux-hardware.org/?probe=854c3ec5b1) | Oct 27, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [5b6d2d2922](https://linux-hardware.org/?probe=5b6d2d2922) | Oct 27, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [033d6281bd](https://linux-hardware.org/?probe=033d6281bd) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [f9e114a7e9](https://linux-hardware.org/?probe=f9e114a7e9) | Oct 26, 2022 |
| Intel         | H410M-E                     | Desktop     | [69d7d07e13](https://linux-hardware.org/?probe=69d7d07e13) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | Notebook    | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [696c30d8c3](https://linux-hardware.org/?probe=696c30d8c3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | Notebook    | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c05a08e1af](https://linux-hardware.org/?probe=c05a08e1af) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [936e43f0bc](https://linux-hardware.org/?probe=936e43f0bc) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [cce3979970](https://linux-hardware.org/?probe=cce3979970) | Oct 22, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6105b0d3a9](https://linux-hardware.org/?probe=6105b0d3a9) | Oct 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | Notebook    | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | K54C                        | Notebook    | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [18c1a4a04d](https://linux-hardware.org/?probe=18c1a4a04d) | Oct 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff6334ee8f](https://linux-hardware.org/?probe=ff6334ee8f) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [e1eacaa737](https://linux-hardware.org/?probe=e1eacaa737) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| MSI           | IONA                        | Desktop     | [7c164d5733](https://linux-hardware.org/?probe=7c164d5733) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a7941186ab](https://linux-hardware.org/?probe=a7941186ab) | Oct 16, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| HP            | 1495                        | Desktop     | [109913631a](https://linux-hardware.org/?probe=109913631a) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [8bfcad8486](https://linux-hardware.org/?probe=8bfcad8486) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [99fe717434](https://linux-hardware.org/?probe=99fe717434) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [b75b67267c](https://linux-hardware.org/?probe=b75b67267c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [0e3ba8fdb3](https://linux-hardware.org/?probe=0e3ba8fdb3) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [78abe50673](https://linux-hardware.org/?probe=78abe50673) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | Notebook    | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [100f7e1b46](https://linux-hardware.org/?probe=100f7e1b46) | Oct 12, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [5b1999a241](https://linux-hardware.org/?probe=5b1999a241) | Oct 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [1a2fe5eeb4](https://linux-hardware.org/?probe=1a2fe5eeb4) | Oct 12, 2022 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [f3b5809fc9](https://linux-hardware.org/?probe=f3b5809fc9) | Oct 12, 2022 |
| HP            | 3397                        | Desktop     | [c374208e14](https://linux-hardware.org/?probe=c374208e14) | Oct 11, 2022 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [b8c2a39217](https://linux-hardware.org/?probe=b8c2a39217) | Oct 10, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c3a4a7983b](https://linux-hardware.org/?probe=c3a4a7983b) | Oct 10, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [d223d492fe](https://linux-hardware.org/?probe=d223d492fe) | Oct 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | Notebook    | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [dd8bbe4068](https://linux-hardware.org/?probe=dd8bbe4068) | Oct 08, 2022 |
| Medion        | E2221T MD61083              | Convertible | [9f7f0f4ea8](https://linux-hardware.org/?probe=9f7f0f4ea8) | Oct 07, 2022 |
| Medion        | E2221T MD61083              | Convertible | [2eaf3df98c](https://linux-hardware.org/?probe=2eaf3df98c) | Oct 07, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5b30b0591e](https://linux-hardware.org/?probe=5b30b0591e) | Oct 07, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [2550504760](https://linux-hardware.org/?probe=2550504760) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6f0bd5a568](https://linux-hardware.org/?probe=6f0bd5a568) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | Notebook    | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Lenovo        | 1031 SDK0E50510 WIN 2625... | Desktop     | [771e19629c](https://linux-hardware.org/?probe=771e19629c) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [c6dd3eef5d](https://linux-hardware.org/?probe=c6dd3eef5d) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | Notebook    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Shuttle       | DH470                       | Desktop     | [408e44b18b](https://linux-hardware.org/?probe=408e44b18b) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | Notebook    | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [fc1fb9966e](https://linux-hardware.org/?probe=fc1fb9966e) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [d19e0fb48b](https://linux-hardware.org/?probe=d19e0fb48b) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4707a778dc](https://linux-hardware.org/?probe=4707a778dc) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [255a0a928a](https://linux-hardware.org/?probe=255a0a928a) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [77d108e391](https://linux-hardware.org/?probe=77d108e391) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| HP            | 2B35                        | Desktop     | [724e0d61e3](https://linux-hardware.org/?probe=724e0d61e3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Acer          | Aspire X1900                | Desktop     | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 716       | 13.91%  |
| Ubuntu 18.04                 | 505       | 9.81%   |
| Debian 11                    | 210       | 4.08%   |
| Ubuntu 22.04                 | 203       | 3.94%   |
| OpenMandriva 4.2             | 181       | 3.52%   |
| OpenMandriva 4.3             | 118       | 2.29%   |
| KDE neon 20.04               | 112       | 2.18%   |
| Zorin 16                     | 86        | 1.67%   |
| Debian 10                    | 81        | 1.57%   |
| Manjaro                      | 78        | 1.52%   |
| Linux Mint 20.3              | 76        | 1.48%   |
| Ubuntu 20.10                 | 72        | 1.4%    |
| Linux Mint 19.3              | 70        | 1.36%   |
| OpenMandriva 23.01           | 68        | 1.32%   |
| Arch                         | 65        | 1.26%   |
| Arch Rolling                 | 62        | 1.2%    |
| Xubuntu 20.04                | 61        | 1.19%   |
| Ubuntu 19.04                 | 61        | 1.19%   |
| Ubuntu 19.10                 | 58        | 1.13%   |
| Linux Mint 20.1              | 57        | 1.11%   |
| Ubuntu 21.04                 | 53        | 1.03%   |
| Fedora 36                    | 53        | 1.03%   |
| Linux Mint 20                | 52        | 1.01%   |
| Ubuntu 21.10                 | 50        | 0.97%   |
| Linux Mint 20.2              | 47        | 0.91%   |
| Fedora 35                    | 47        | 0.91%   |
| Xubuntu 18.04                | 46        | 0.89%   |
| ROSA R10                     | 43        | 0.84%   |
| Kubuntu 20.04                | 43        | 0.84%   |
| Fedora 34                    | 40        | 0.78%   |
| Zorin 15                     | 39        | 0.76%   |
| Fedora 33                    | 38        | 0.74%   |
| Pop!_OS 20.04                | 37        | 0.72%   |
| Linux Mint 21                | 36        | 0.7%    |
| Fedora 37                    | 34        | 0.66%   |
| Ubuntu 18.10                 | 33        | 0.64%   |
| Pop!_OS 22.04                | 31        | 0.6%    |
| Linux Mint 19.2              | 30        | 0.58%   |
| Ubuntu 16.04                 | 29        | 0.56%   |
| openSUSE Tumbleweed-XXXXXXXX | 29        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1727      | 35.41%  |
| Linux Mint    | 407       | 8.35%   |
| OpenMandriva  | 391       | 8.02%   |
| Debian        | 348       | 7.14%   |
| Fedora        | 237       | 4.86%   |
| Manjaro       | 186       | 3.81%   |
| KDE neon      | 138       | 2.83%   |
| Zorin         | 130       | 2.67%   |
| Arch          | 125       | 2.56%   |
| Endless       | 123       | 2.52%   |
| Xubuntu       | 122       | 2.5%    |
| Pop!_OS       | 115       | 2.36%   |
| ROSA          | 107       | 2.19%   |
| Kubuntu       | 102       | 2.09%   |
| Ubuntu MATE   | 56        | 1.15%   |
| Elementary    | 51        | 1.05%   |
| openSUSE      | 45        | 0.92%   |
| Gentoo        | 43        | 0.88%   |
| Ubuntu Unity  | 39        | 0.8%    |
| ArcoLinux     | 35        | 0.72%   |
| Lubuntu       | 29        | 0.59%   |
| BlackPanther  | 28        | 0.57%   |
| Kali          | 27        | 0.55%   |
| SteamOS       | 20        | 0.41%   |
| LMDE          | 19        | 0.39%   |
| Parrot        | 18        | 0.37%   |
| MX            | 18        | 0.37%   |
| EndeavourOS   | 16        | 0.33%   |
| Clear Linux   | 16        | 0.33%   |
| Ubuntu Budgie | 12        | 0.25%   |
| Nobara        | 11        | 0.23%   |
| CentOS        | 10        | 0.21%   |
| Garuda Linux  | 9         | 0.18%   |
| Reborn OS     | 8         | 0.16%   |
| Deepin        | 6         | 0.12%   |
| Ubuntu Studio | 5         | 0.1%    |
| Solus         | 5         | 0.1%    |
| RHEL          | 5         | 0.1%    |
| Peppermint    | 5         | 0.1%    |
| LFS           | 4         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 3.16%   |
| 5.16.7-desktop-1omv4003         | 116       | 2.07%   |
| 5.4.0-42-generic                | 96        | 1.71%   |
| 6.1.1-desktop-1omv2290          | 62        | 1.11%   |
| 5.4.0-58-generic                | 60        | 1.07%   |
| 5.15.0-56-generic               | 60        | 1.07%   |
| 5.10.0-8-amd64                  | 56        | 1%      |
| 5.4.0-52-generic                | 49        | 0.87%   |
| 5.4.0-54-generic                | 48        | 0.86%   |
| 5.4.0-26-generic                | 47        | 0.84%   |
| 5.15.0-52-generic               | 44        | 0.79%   |
| 5.3.0-28-generic                | 42        | 0.75%   |
| 5.15.0-58-generic               | 40        | 0.71%   |
| 5.4.0-48-generic                | 39        | 0.7%    |
| 5.3.0-40-generic                | 37        | 0.66%   |
| 5.11.0-27-generic               | 37        | 0.66%   |
| 5.0.0-37-generic                | 36        | 0.64%   |
| 5.4.0-29-generic                | 34        | 0.61%   |
| 5.4.0-65-generic                | 32        | 0.57%   |
| 5.3.0-46-generic                | 32        | 0.57%   |
| 5.11.0-43-generic               | 32        | 0.57%   |
| 5.13.0-30-generic               | 31        | 0.55%   |
| 5.10.0-18-amd64                 | 31        | 0.55%   |
| 5.0.0-32-generic                | 30        | 0.54%   |
| 5.4.0-72-generic                | 29        | 0.52%   |
| 5.4.0-40-generic                | 29        | 0.52%   |
| 5.15.0-48-generic               | 29        | 0.52%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.52%   |
| 5.15.0-60-generic               | 28        | 0.5%    |
| 5.4.0-47-generic                | 27        | 0.48%   |
| 5.4.0-37-generic                | 27        | 0.48%   |
| 5.3.0-51-generic                | 27        | 0.48%   |
| 5.15.0-53-generic               | 26        | 0.46%   |
| 5.13.0-39-generic               | 26        | 0.46%   |
| 5.13.0-28-generic               | 26        | 0.46%   |
| 5.11.0-41-generic               | 26        | 0.46%   |
| 5.8.0-43-generic                | 25        | 0.45%   |
| 5.8.0-44-generic                | 24        | 0.43%   |
| 5.11.0-37-generic               | 24        | 0.43%   |
| 5.4.0-70-generic                | 23        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 941       | 17.87%  |
| 4.15.0  | 415       | 7.88%   |
| 5.15.0  | 399       | 7.58%   |
| 5.11.0  | 275       | 5.22%   |
| 5.8.0   | 266       | 5.05%   |
| 5.3.0   | 254       | 4.82%   |
| 5.10.0  | 250       | 4.75%   |
| 5.13.0  | 236       | 4.48%   |
| 5.0.0   | 198       | 3.76%   |
| 5.10.14 | 179       | 3.4%    |
| 5.16.7  | 120       | 2.28%   |
| 4.18.0  | 114       | 2.16%   |
| 4.19.0  | 83        | 1.58%   |
| 6.1.1   | 72        | 1.37%   |
| 5.19.0  | 69        | 1.31%   |
| 4.9.60  | 33        | 0.63%   |
| 6.0.0   | 25        | 0.47%   |
| 4.4.0   | 22        | 0.42%   |
| 4.18.16 | 22        | 0.42%   |
| 5.18.0  | 19        | 0.36%   |
| 5.14.0  | 19        | 0.36%   |
| 5.9.16  | 15        | 0.28%   |
| 5.17.5  | 15        | 0.28%   |
| 6.0.12  | 14        | 0.27%   |
| 5.9.0   | 13        | 0.25%   |
| 5.7.0   | 12        | 0.23%   |
| 5.3.18  | 12        | 0.23%   |
| 5.16.0  | 12        | 0.23%   |
| 5.12.4  | 12        | 0.23%   |
| 4.9.20  | 12        | 0.23%   |
| 5.16.11 | 11        | 0.21%   |
| 5.15.6  | 11        | 0.21%   |
| 6.0.10  | 10        | 0.19%   |
| 5.8.11  | 10        | 0.19%   |
| 5.6.0   | 10        | 0.19%   |
| 5.15.32 | 10        | 0.19%   |
| 5.13.12 | 10        | 0.19%   |
| 5.11.12 | 10        | 0.19%   |
| 6.1.11  | 9         | 0.17%   |
| 6.0.8   | 9         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1004      | 19.29%  |
| 5.15    | 516       | 9.91%   |
| 5.10    | 509       | 9.78%   |
| 4.15    | 415       | 7.97%   |
| 5.11    | 332       | 6.38%   |
| 5.8     | 326       | 6.26%   |
| 5.3     | 282       | 5.42%   |
| 5.13    | 274       | 5.26%   |
| 5.0     | 202       | 3.88%   |
| 5.16    | 182       | 3.5%    |
| 4.18    | 137       | 2.63%   |
| 6.1     | 127       | 2.44%   |
| 5.19    | 127       | 2.44%   |
| 6.0     | 101       | 1.94%   |
| 4.19    | 98        | 1.88%   |
| 4.9     | 79        | 1.52%   |
| 5.14    | 72        | 1.38%   |
| 5.18    | 65        | 1.25%   |
| 5.9     | 52        | 1%      |
| 5.6     | 51        | 0.98%   |
| 5.17    | 48        | 0.92%   |
| 5.7     | 45        | 0.86%   |
| 5.12    | 44        | 0.85%   |
| 5.5     | 26        | 0.5%    |
| 4.4     | 26        | 0.5%    |
| 4.1     | 9         | 0.17%   |
| 5.2     | 8         | 0.15%   |
| 3.10    | 8         | 0.15%   |
| 5.1     | 7         | 0.13%   |
| 4.16    | 6         | 0.12%   |
| 4.20    | 4         | 0.08%   |
| 4.17    | 4         | 0.08%   |
| 4.13    | 4         | 0.08%   |
| 4.8     | 3         | 0.06%   |
| 4.14    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 6.2     | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 3.18    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4503      | 95.67%  |
| i686    | 174       | 3.7%    |
| aarch64 | 23        | 0.49%   |
| armv7l  | 6         | 0.13%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2098      | 42.37%  |
| KDE5             | 854       | 17.25%  |
| Unknown          | 631       | 12.74%  |
| XFCE             | 368       | 7.43%   |
| X-Cinnamon       | 316       | 6.38%   |
| KDE              | 157       | 3.17%   |
| MATE             | 150       | 3.03%   |
| Cinnamon         | 49        | 0.99%   |
| KDE4             | 48        | 0.97%   |
| Pantheon         | 47        | 0.95%   |
| LXQt             | 44        | 0.89%   |
| Unity            | 38        | 0.77%   |
| i3               | 32        | 0.65%   |
| Budgie           | 21        | 0.42%   |
| LXDE             | 20        | 0.4%    |
| Deepin           | 19        | 0.38%   |
| GNOME Flashback  | 14        | 0.28%   |
| openbox          | 9         | 0.18%   |
| GNOME Classic    | 6         | 0.12%   |
| bspwm            | 5         | 0.1%    |
| qtile            | 4         | 0.08%   |
| xmonad           | 3         | 0.06%   |
| enlightenment    | 3         | 0.06%   |
| DWM              | 3         | 0.06%   |
| trinity          | 2         | 0.04%   |
| LeftWM           | 2         | 0.04%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| ICEWM            | 1         | 0.02%   |
| i3-with-shmlog   | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3838      | 79.17%  |
| Wayland | 598       | 12.33%  |
| Unknown | 339       | 6.99%   |
| Tty     | 73        | 1.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2600      | 53.16%  |
| SDDM    | 751       | 15.35%  |
| GDM     | 548       | 11.2%   |
| GDM3    | 400       | 8.18%   |
| LightDM | 367       | 7.5%    |
| TDM     | 150       | 3.07%   |
| KDM     | 48        | 0.98%   |
| XDM     | 13        | 0.27%   |
| Ly      | 5         | 0.1%    |
| LXDM    | 5         | 0.1%    |
| SLiM    | 4         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 2816      | 58.11%  |
| en_US          | 809       | 16.69%  |
| Unknown        | 635       | 13.1%   |
| ca_ES          | 176       | 3.63%   |
| en_GB          | 102       | 2.1%    |
| C              | 49        | 1.01%   |
| gl_ES          | 32        | 0.66%   |
| de_DE          | 30        | 0.62%   |
| eu_ES          | 25        | 0.52%   |
| fr_FR          | 20        | 0.41%   |
| ru_RU          | 17        | 0.35%   |
| it_IT          | 15        | 0.31%   |
| an_ES          | 12        | 0.25%   |
| es_MX          | 10        | 0.21%   |
| es_AR          | 9         | 0.19%   |
| pt_BR          | 6         | 0.12%   |
| en_IE          | 6         | 0.12%   |
| ca_AD          | 6         | 0.12%   |
| pl_PL          | 5         | 0.1%    |
| ca_ES@valencia | 5         | 0.1%    |
| C.UTF8         | 5         | 0.1%    |
| ro_RO          | 4         | 0.08%   |
| en_AG          | 4         | 0.08%   |
| pt_PT          | 3         | 0.06%   |
| nl_NL          | 3         | 0.06%   |
| fr_BE          | 3         | 0.06%   |
| es_ES.UTF8     | 3         | 0.06%   |
| de_AT          | 3         | 0.06%   |
| POSIX          | 2         | 0.04%   |
| fr_CH          | 2         | 0.04%   |
| es_US          | 2         | 0.04%   |
| es_BO          | 2         | 0.04%   |
| en_DK          | 2         | 0.04%   |
| en_AU          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |
| et_EE          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2487      | 51.7%   |
| EFI  | 2323      | 48.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3720      | 77.15%  |
| Overlay  | 424       | 8.79%   |
| Btrfs    | 311       | 6.45%   |
| Unknown  | 212       | 4.4%    |
| Xfs      | 66        | 1.37%   |
| Ext3     | 33        | 0.68%   |
| Zfs      | 23        | 0.48%   |
| Ext2     | 16        | 0.33%   |
| Tmpfs    | 8         | 0.17%   |
| Reiserfs | 4         | 0.08%   |
| Jfs      | 2         | 0.04%   |
| Aufs     | 2         | 0.04%   |
| F2fs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2788      | 57.81%  |
| GPT     | 1515      | 31.41%  |
| MBR     | 520       | 10.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4019      | 83.56%  |
| Yes       | 791       | 16.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3199      | 66.66%  |
| Yes       | 1600      | 33.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 909       | 19.32%  |
| Hewlett-Packard         | 671       | 14.26%  |
| Lenovo                  | 556       | 11.82%  |
| MSI                     | 407       | 8.65%   |
| Gigabyte Technology     | 394       | 8.37%   |
| Acer                    | 316       | 6.72%   |
| Dell                    | 292       | 6.21%   |
| ASRock                  | 118       | 2.51%   |
| Apple                   | 109       | 2.32%   |
| Toshiba                 | 104       | 2.21%   |
| Intel                   | 71        | 1.51%   |
| Unknown                 | 66        | 1.4%    |
| Packard Bell            | 43        | 0.91%   |
| Sony                    | 40        | 0.85%   |
| Medion                  | 37        | 0.79%   |
| HUAWEI                  | 37        | 0.79%   |
| Chuwi                   | 32        | 0.68%   |
| Samsung Electronics     | 31        | 0.66%   |
| SLIMBOOK                | 27        | 0.57%   |
| Notebook                | 27        | 0.57%   |
| LG Electronics          | 21        | 0.45%   |
| Fujitsu                 | 20        | 0.43%   |
| Raspberry Pi Foundation | 19        | 0.4%    |
| Pegatron                | 18        | 0.38%   |
| eMachines               | 18        | 0.38%   |
| ECS                     | 17        | 0.36%   |
| Valve                   | 16        | 0.34%   |
| BESSTAR Tech            | 15        | 0.32%   |
| Teclast                 | 14        | 0.3%    |
| Timi                    | 12        | 0.26%   |
| Fujitsu Siemens         | 12        | 0.26%   |
| Foxconn                 | 12        | 0.26%   |
| AMI                     | 12        | 0.26%   |
| Supermicro              | 10        | 0.21%   |
| Huanan                  | 10        | 0.21%   |
| AZW                     | 9         | 0.19%   |
| Microsoft               | 8         | 0.17%   |
| Clevo                   | 8         | 0.17%   |
| Shuttle                 | 6         | 0.13%   |
| IBM                     | 6         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 91        | 1.93%   |
| ASUS All Series                            | 52        | 1.11%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.47%   |
| HP Pavilion g6                             | 21        | 0.45%   |
| HP Pavilion dv6                            | 19        | 0.4%    |
| HP Notebook                                | 19        | 0.4%    |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.38%   |
| Valve Jupiter                              | 16        | 0.34%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.32%   |
| Gigabyte B450M DS3H                        | 13        | 0.28%   |
| MSI MS-7C37                                | 11        | 0.23%   |
| HP G62                                     | 11        | 0.23%   |
| RPi Raspberry Pi                           | 10        | 0.21%   |
| MSI MS-7817                                | 10        | 0.21%   |
| HP Pavilion 15                             | 10        | 0.21%   |
| HP Laptop 15-da0xxx                        | 10        | 0.21%   |
| Gigabyte 970A-DS3P                         | 10        | 0.21%   |
| Dell XPS 13 7390                           | 10        | 0.21%   |
| ASUS P5G41T-M LX                           | 10        | 0.21%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.19%   |
| Gigabyte H110M-S2H                         | 9         | 0.19%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.17%   |
| MSI MS-7B79                                | 8         | 0.17%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.17%   |
| HUAWEI BOHK-WAX9X                          | 8         | 0.17%   |
| Gigabyte B450 AORUS M                      | 8         | 0.17%   |
| ASUS X555LAB                               | 8         | 0.17%   |
| ASUS X550VX                                | 8         | 0.17%   |
| ASUS X540NA                                | 8         | 0.17%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.17%   |
| ASUS PRIME B450M-A                         | 8         | 0.17%   |
| ASUS PRIME A320M-K                         | 8         | 0.17%   |
| MSI MS-7C02                                | 7         | 0.15%   |
| MSI MS-7B86                                | 7         | 0.15%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.15%   |
| Lenovo G50-70 20351                        | 7         | 0.15%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.15%   |
| HP Pavilion dv7                            | 7         | 0.15%   |
| HP OMEN by Laptop                          | 7         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 230       | 4.89%   |
| Lenovo ThinkPad       | 177       | 3.76%   |
| HP Pavilion           | 141       | 3%      |
| Lenovo IdeaPad        | 131       | 2.78%   |
| Unknown               | 91        | 1.93%   |
| HP Compaq             | 89        | 1.89%   |
| Dell Latitude         | 87        | 1.85%   |
| Toshiba Satellite     | 80        | 1.7%    |
| ASUS PRIME            | 80        | 1.7%    |
| ASUS VivoBook         | 79        | 1.68%   |
| HP Laptop             | 68        | 1.45%   |
| HP EliteBook          | 65        | 1.38%   |
| ASUS ROG              | 62        | 1.32%   |
| ASUS TUF              | 60        | 1.28%   |
| Dell XPS              | 58        | 1.23%   |
| Lenovo ThinkCentre    | 54        | 1.15%   |
| ASUS All              | 52        | 1.11%   |
| Dell OptiPlex         | 47        | 1%      |
| HP ProBook            | 40        | 0.85%   |
| Dell Inspiron         | 39        | 0.83%   |
| ASUS ZenBook          | 36        | 0.77%   |
| Packard Bell EasyNote | 31        | 0.66%   |
| HP 250                | 31        | 0.66%   |
| MSI Prestige          | 25        | 0.53%   |
| Lenovo Yoga           | 24        | 0.51%   |
| HP OMEN               | 23        | 0.49%   |
| Lenovo Legion         | 22        | 0.47%   |
| Gigabyte B450M        | 22        | 0.47%   |
| Gigabyte X570         | 21        | 0.45%   |
| MSI Modern            | 20        | 0.43%   |
| Dell Precision        | 20        | 0.43%   |
| RPi Raspberry         | 19        | 0.4%    |
| HP Notebook           | 19        | 0.4%    |
| HP ENVY               | 19        | 0.4%    |
| Acer Extensa          | 19        | 0.4%    |
| Lenovo ThinkBook      | 18        | 0.38%   |
| ASUS ASUS             | 17        | 0.36%   |
| Valve Jupiter         | 16        | 0.34%   |
| Acer TravelMate       | 16        | 0.34%   |
| Gigabyte B450         | 15        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 482       | 10.24%  |
| 2019    | 447       | 9.5%    |
| 2020    | 399       | 8.48%   |
| 2014    | 324       | 6.89%   |
| 2013    | 296       | 6.29%   |
| 2012    | 296       | 6.29%   |
| 2021    | 293       | 6.23%   |
| 2017    | 287       | 6.1%    |
| 2015    | 276       | 5.87%   |
| 2011    | 274       | 5.82%   |
| 2010    | 253       | 5.38%   |
| 2009    | 230       | 4.89%   |
| 2008    | 222       | 4.72%   |
| 2016    | 221       | 4.7%    |
| 2007    | 159       | 3.38%   |
| 2022    | 98        | 2.08%   |
| 2006    | 82        | 1.74%   |
| Unknown | 29        | 0.62%   |
| 2005    | 22        | 0.47%   |
| 2004    | 7         | 0.15%   |
| 2003    | 3         | 0.06%   |
| 2002    | 2         | 0.04%   |
| 2001    | 2         | 0.04%   |
| 2023    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2600      | 55.26%  |
| Desktop        | 1783      | 37.9%   |
| All in one     | 80        | 1.7%    |
| Convertible    | 74        | 1.57%   |
| Mini pc        | 71        | 1.51%   |
| Tablet         | 41        | 0.87%   |
| System on chip | 26        | 0.55%   |
| Server         | 26        | 0.55%   |
| Phone          | 3         | 0.06%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4421      | 93.39%  |
| Enabled  | 313       | 6.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4698      | 99.85%  |
| Yes  | 7         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1067      | 22.3%   |
| 3.01-4.0        | 1004      | 20.98%  |
| 16.01-24.0      | 971       | 20.29%  |
| 8.01-16.0       | 870       | 18.18%  |
| 32.01-64.0      | 398       | 8.32%   |
| 1.01-2.0        | 225       | 4.7%    |
| 2.01-3.0        | 76        | 1.59%   |
| 64.01-256.0     | 62        | 1.3%    |
| 0.51-1.0        | 57        | 1.19%   |
| 24.01-32.0      | 47        | 0.98%   |
| More than 256.0 | 5         | 0.1%    |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2045      | 39.25%  |
| 2.01-3.0   | 1317      | 25.28%  |
| 4.01-8.0   | 640       | 12.28%  |
| 3.01-4.0   | 557       | 10.69%  |
| 0.51-1.0   | 409       | 7.85%   |
| 8.01-16.0  | 164       | 3.15%   |
| 0.01-0.5   | 58        | 1.11%   |
| 24.01-32.0 | 10        | 0.19%   |
| 16.01-24.0 | 8         | 0.15%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2916      | 59.96%  |
| 2       | 1201      | 24.7%   |
| 3       | 393       | 8.08%   |
| 4       | 173       | 3.56%   |
| 5       | 70        | 1.44%   |
| 0       | 41        | 0.84%   |
| 6       | 33        | 0.68%   |
| 7       | 13        | 0.27%   |
| 9       | 7         | 0.14%   |
| 8       | 6         | 0.12%   |
| 10      | 3         | 0.06%   |
| 12      | 2         | 0.04%   |
| 11      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2817      | 59.33%  |
| Yes       | 1931      | 40.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4084      | 86.49%  |
| No        | 638       | 13.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3529      | 74.39%  |
| No        | 1215      | 25.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2686      | 56.39%  |
| No        | 2077      | 43.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 4705      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 772       | 15.05%  |
| Barcelona                  | 522       | 10.17%  |
| Seville                    | 177       | 3.45%   |
| Valencia                   | 172       | 3.35%   |
| Zaragoza                   | 75        | 1.46%   |
| Málaga                    | 74        | 1.44%   |
| Granada                    | 67        | 1.31%   |
| Valladolid                 | 56        | 1.09%   |
| Sabadell                   | 49        | 0.95%   |
| Palma                      | 49        | 0.95%   |
| Alcobendas                 | 49        | 0.95%   |
| Córdoba                   | 48        | 0.94%   |
| Bilbao                     | 48        | 0.94%   |
| Vigo                       | 45        | 0.88%   |
| Las Palmas de Gran Canaria | 45        | 0.88%   |
| Ourense                    | 37        | 0.72%   |
| Murcia                     | 36        | 0.7%    |
| Pamplona                   | 34        | 0.66%   |
| Donostia / San Sebastian   | 31        | 0.6%    |
| Alicante                   | 31        | 0.6%    |
| Alcalá de Henares         | 31        | 0.6%    |
| Oviedo                     | 30        | 0.58%   |
| Santa Cruz de Tenerife     | 27        | 0.53%   |
| Gijón                     | 27        | 0.53%   |
| Almería                   | 27        | 0.53%   |
| A Coruña                  | 27        | 0.53%   |
| Santiago de Compostela     | 25        | 0.49%   |
| León                      | 25        | 0.49%   |
| Mostoles                   | 24        | 0.47%   |
| Barakaldo                  | 23        | 0.45%   |
| Vitoria-Gasteiz            | 21        | 0.41%   |
| Salamanca                  | 21        | 0.41%   |
| Burgos                     | 21        | 0.41%   |
| Albacete                   | 21        | 0.41%   |
| Terrassa                   | 20        | 0.39%   |
| Santander                  | 20        | 0.39%   |
| Cartagena                  | 20        | 0.39%   |
| Lugo                       | 19        | 0.37%   |
| Getxo                      | 19        | 0.37%   |
| Reus                       | 17        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1173      | 1794   | 17.07%  |
| WDC                         | 966       | 1405   | 14.06%  |
| Samsung Electronics         | 903       | 1286   | 13.14%  |
| Kingston                    | 775       | 1063   | 11.28%  |
| Toshiba                     | 509       | 763    | 7.41%   |
| SanDisk                     | 368       | 490    | 5.36%   |
| Unknown                     | 263       | 337    | 3.83%   |
| Crucial                     | 260       | 360    | 3.78%   |
| Hitachi                     | 212       | 252    | 3.09%   |
| SK hynix                    | 161       | 209    | 2.34%   |
| Intel                       | 143       | 186    | 2.08%   |
| HGST                        | 122       | 154    | 1.78%   |
| Micron Technology           | 105       | 128    | 1.53%   |
| China                       | 62        | 83     | 0.9%    |
| Phison                      | 51        | 57     | 0.74%   |
| Fujitsu                     | 43        | 49     | 0.63%   |
| KIOXIA                      | 40        | 51     | 0.58%   |
| Apple                       | 37        | 51     | 0.54%   |
| Micron/Crucial Technology   | 36        | 45     | 0.52%   |
| Maxtor                      | 36        | 48     | 0.52%   |
| OCZ                         | 32        | 41     | 0.47%   |
| Silicon Motion              | 26        | 32     | 0.38%   |
| JMicron Technology          | 25        | 27     | 0.36%   |
| Netac                       | 23        | 33     | 0.33%   |
| Transcend                   | 22        | 43     | 0.32%   |
| KIOXIA-EXCERIA              | 21        | 28     | 0.31%   |
| A-DATA Technology           | 20        | 27     | 0.29%   |
| Unknown                     | 20        | 22     | 0.29%   |
| LITEON                      | 19        | 20     | 0.28%   |
| Corsair                     | 19        | 24     | 0.28%   |
| KingSpec                    | 18        | 24     | 0.26%   |
| USB30                       | 16        | 33     | 0.23%   |
| PNY                         | 16        | 25     | 0.23%   |
| Kingston Technology Company | 16        | 20     | 0.23%   |
| KingDian                    | 16        | 19     | 0.23%   |
| Emtec                       | 15        | 18     | 0.22%   |
| Phison Electronics          | 14        | 15     | 0.2%    |
| Intenso                     | 13        | 18     | 0.19%   |
| Patriot                     | 11        | 18     | 0.16%   |
| Teclast                     | 10        | 10     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 255       | 3.38%   |
| Kingston SA400S37480G 480GB SSD        | 110       | 1.46%   |
| Seagate ST1000DM010-2EP102 1TB         | 89        | 1.18%   |
| Kingston SA400S37120G 120GB SSD        | 80        | 1.06%   |
| Seagate ST500DM002-1BD142 500GB        | 74        | 0.98%   |
| Kingston SV300S37A120G 120GB SSD       | 69        | 0.92%   |
| Seagate ST3500418AS 500GB              | 62        | 0.82%   |
| Samsung SSD 860 EVO 500GB              | 57        | 0.76%   |
| Unknown MMC Card  64GB                 | 53        | 0.7%    |
| Unknown MMC Card  32GB                 | 48        | 0.64%   |
| Crucial CT500MX500SSD1 500GB           | 47        | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB         | 45        | 0.6%    |
| Samsung SSD 850 EVO 500GB              | 44        | 0.58%   |
| Samsung SSD 850 EVO 250GB              | 44        | 0.58%   |
| Toshiba DT01ACA100 1TB                 | 43        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB        | 43        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB         | 43        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB         | 41        | 0.54%   |
| Toshiba MQ01ABD100 1TB                 | 40        | 0.53%   |
| Seagate ST9500325AS 500GB              | 39        | 0.52%   |
| Kingston SUV400S37240G 240GB SSD       | 39        | 0.52%   |
| HGST HTS721010A9E630 1TB               | 38        | 0.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 37        | 0.49%   |
| SanDisk SSD PLUS 480GB                 | 37        | 0.49%   |
| Samsung NVMe SSD Drive 512GB           | 36        | 0.48%   |
| Samsung NVMe SSD Drive 500GB           | 36        | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB         | 35        | 0.46%   |
| Toshiba MQ01ABF050 500GB               | 34        | 0.45%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 0.45%   |
| Seagate ST31000528AS 1TB               | 33        | 0.44%   |
| Kingston SV300S37A240G 240GB SSD       | 33        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB           | 32        | 0.42%   |
| Intel NVMe SSD Drive 512GB             | 30        | 0.4%    |
| Unknown SD/MMC/MS PRO 16GB             | 29        | 0.38%   |
| Unknown MMC Card  128GB                | 29        | 0.38%   |
| Toshiba MQ04ABF100 1TB                 | 28        | 0.37%   |
| Toshiba MQ01ABD050 500GB               | 28        | 0.37%   |
| Seagate Expansion 1TB                  | 28        | 0.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 28        | 0.37%   |
| WDC WD20EARX-00PASB0 2TB               | 27        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1162      | 1778   | 40%     |
| WDC                 | 759       | 1095   | 26.13%  |
| Toshiba             | 365       | 513    | 12.56%  |
| Hitachi             | 212       | 252    | 7.3%    |
| HGST                | 122       | 154    | 4.2%    |
| Samsung Electronics | 118       | 145    | 4.06%   |
| Fujitsu             | 42        | 48     | 1.45%   |
| Maxtor              | 31        | 42     | 1.07%   |
| Unknown             | 29        | 35     | 1%      |
| JMicron Technology  | 17        | 18     | 0.59%   |
| Apple               | 16        | 20     | 0.55%   |
| USB3.0              | 6         | 6      | 0.21%   |
| ASMT                | 5         | 9      | 0.17%   |
| SABRENT             | 3         | 3      | 0.1%    |
| Hewlett-Packard     | 3         | 4      | 0.1%    |
| USB                 | 2         | 2      | 0.07%   |
| Intenso             | 2         | 3      | 0.07%   |
| Quantum             | 1         | 1      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| OEM                 | 1         | 1      | 0.03%   |
| Maxone              | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| IBM-207x            | 1         | 8      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| HGST HTS            | 1         | 1      | 0.03%   |
| Generic-            | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 705       | 967    | 30.19%  |
| Samsung Electronics | 408       | 562    | 17.47%  |
| Crucial             | 234       | 323    | 10.02%  |
| SanDisk             | 222       | 279    | 9.51%   |
| WDC                 | 120       | 170    | 5.14%   |
| Toshiba             | 95        | 170    | 4.07%   |
| China               | 60        | 81     | 2.57%   |
| SK hynix            | 38        | 42     | 1.63%   |
| Intel               | 34        | 50     | 1.46%   |
| Micron Technology   | 33        | 42     | 1.41%   |
| OCZ                 | 32        | 41     | 1.37%   |
| Netac               | 23        | 33     | 0.99%   |
| Transcend           | 21        | 42     | 0.9%    |
| LITEON              | 18        | 18     | 0.77%   |
| KingSpec            | 18        | 24     | 0.77%   |
| A-DATA Technology   | 17        | 24     | 0.73%   |
| USB30               | 16        | 33     | 0.69%   |
| KIOXIA-EXCERIA      | 16        | 20     | 0.69%   |
| KingDian            | 15        | 18     | 0.64%   |
| Apple               | 15        | 18     | 0.64%   |
| Emtec               | 13        | 16     | 0.56%   |
| Intenso             | 11        | 13     | 0.47%   |
| Teclast             | 10        | 10     | 0.43%   |
| PNY                 | 10        | 19     | 0.43%   |
| Patriot             | 10        | 17     | 0.43%   |
| Unknown             | 10        | 10     | 0.43%   |
| FORESEE             | 9         | 11     | 0.39%   |
| Corsair             | 8         | 11     | 0.34%   |
| Drevo               | 7         | 9      | 0.3%    |
| GOODRAM             | 6         | 8      | 0.26%   |
| Maxtor              | 5         | 6      | 0.21%   |
| LITEONIT            | 5         | 6      | 0.21%   |
| Dogfish             | 5         | 5      | 0.21%   |
| BAITITON            | 5         | 5      | 0.21%   |
| Hoodisk             | 4         | 5      | 0.17%   |
| Unknown             | 3         | 3      | 0.13%   |
| TCSUNBOW            | 3         | 3      | 0.13%   |
| SPCC                | 3         | 3      | 0.13%   |
| Plextor             | 3         | 4      | 0.13%   |
| KingFast            | 3         | 3      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2468      | 4145   | 40.35%  |
| SSD     | 2017      | 3202   | 32.97%  |
| NVMe    | 1311      | 1832   | 21.43%  |
| MMC     | 241       | 316    | 3.94%   |
| Unknown | 80        | 99     | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3581      | 7151   | 66.82%  |
| NVMe | 1309      | 1827   | 24.43%  |
| MMC  | 241       | 316    | 4.5%    |
| SAS  | 228       | 300    | 4.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2868      | 4708   | 62.33%  |
| 0.51-1.0   | 1230      | 1806   | 26.73%  |
| 1.01-2.0   | 313       | 494    | 6.8%    |
| 3.01-4.0   | 75        | 123    | 1.63%   |
| 2.01-3.0   | 75        | 121    | 1.63%   |
| 4.01-10.0  | 39        | 94     | 0.85%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1389      | 27.77%  |
| 251-500        | 1167      | 23.33%  |
| 501-1000       | 665       | 13.29%  |
| 1-20           | 394       | 7.88%   |
| 1001-2000      | 343       | 6.86%   |
| 51-100         | 342       | 6.84%   |
| 21-50          | 215       | 4.3%    |
| More than 3000 | 190       | 3.8%    |
| 2001-3000      | 173       | 3.46%   |
| Unknown        | 124       | 2.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2045      | 39.38%  |
| 21-50          | 880       | 16.95%  |
| 101-250        | 664       | 12.79%  |
| 51-100         | 539       | 10.38%  |
| 251-500        | 382       | 7.36%   |
| 501-1000       | 274       | 5.28%   |
| 1001-2000      | 157       | 3.02%   |
| Unknown        | 124       | 2.39%   |
| More than 3000 | 70        | 1.35%   |
| 2001-3000      | 56        | 1.08%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 13        | 19     | 2.97%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 12     | 2.74%   |
| Kingston SV300S37A120G 120GB SSD   | 12        | 15     | 2.74%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 1.83%   |
| Seagate ST500LT012-1DG142 500GB    | 7         | 7      | 1.6%    |
| SanDisk SSD PLUS 480GB             | 7         | 9      | 1.6%    |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 7      | 1.37%   |
| Seagate ST3500320AS 500GB          | 5         | 8      | 1.14%   |
| Seagate ST31000528AS 1TB           | 5         | 6      | 1.14%   |
| HGST HTS545050A7E680 500GB         | 5         | 7      | 1.14%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 6      | 0.91%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 0.91%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 0.91%   |
| Seagate ST31500341AS 1TB           | 4         | 4      | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 0.91%   |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 7      | 0.91%   |
| HGST HTS721010A9E630 1TB           | 4         | 4      | 0.91%   |
| Drevo X1 SSD 240GB                 | 4         | 6      | 0.91%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 3         | 3      | 0.68%   |
| WDC WD20EZRX-00DC0B0 2TB           | 3         | 3      | 0.68%   |
| WDC WD20EARX-00PASB0 2TB           | 3         | 4      | 0.68%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 0.68%   |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.68%   |
| Seagate ST3200822A 200GB           | 3         | 3      | 0.68%   |
| Seagate ST2000DL003-9VT166 2TB     | 3         | 4      | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB     | 3         | 4      | 0.68%   |
| Samsung Electronics HD501LJ 500GB  | 3         | 3      | 0.68%   |
| Kingston SUV400S37240G 240GB SSD   | 3         | 5      | 0.68%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 6      | 0.68%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.68%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.68%   |
| Fujitsu MHZ2250BH G2 250GB         | 3         | 4      | 0.68%   |
| WDC WD6400AAKS-22A7B0 640GB        | 2         | 2      | 0.46%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 0.46%   |
| WDC WD5000AAKS-402AA0 500GB        | 2         | 2      | 0.46%   |
| WDC WD40EZRX-00SPEB0 4TB           | 2         | 3      | 0.46%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 2      | 0.46%   |
| WDC WD3200BEKT-60V5T1 320GB        | 2         | 2      | 0.46%   |
| WDC WD2500AAJS-00B4A0 250GB        | 2         | 2      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 148       | 189    | 34.58%  |
| WDC                 | 75        | 93     | 17.52%  |
| Toshiba             | 31        | 33     | 7.24%   |
| Hitachi             | 30        | 32     | 7.01%   |
| Samsung Electronics | 29        | 30     | 6.78%   |
| Kingston            | 23        | 31     | 5.37%   |
| HGST                | 18        | 21     | 4.21%   |
| SanDisk             | 13        | 15     | 3.04%   |
| Intel               | 10        | 11     | 2.34%   |
| Crucial             | 9         | 11     | 2.1%    |
| Maxtor              | 8         | 8      | 1.87%   |
| Fujitsu             | 6         | 7      | 1.4%    |
| Drevo               | 5         | 7      | 1.17%   |
| OCZ                 | 3         | 3      | 0.7%    |
| Micron Technology   | 3         | 4      | 0.7%    |
| China               | 3         | 4      | 0.7%    |
| SK hynix            | 2         | 2      | 0.47%   |
| KingDian            | 2         | 2      | 0.47%   |
| Transcend           | 1         | 5      | 0.23%   |
| Patriot             | 1         | 1      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |
| IBM                 | 1         | 1      | 0.23%   |
| Hypertec            | 1         | 1      | 0.23%   |
| Dogfish             | 1         | 1      | 0.23%   |
| ASMT                | 1         | 2      | 0.23%   |
| Apple               | 1         | 1      | 0.23%   |
| A-DATA Technology   | 1         | 1      | 0.23%   |
| Unknown             | 1         | 1      | 0.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 148       | 189    | 44.85%  |
| WDC                 | 73        | 91     | 22.12%  |
| Hitachi             | 30        | 32     | 9.09%   |
| Toshiba             | 26        | 28     | 7.88%   |
| HGST                | 18        | 21     | 5.45%   |
| Samsung Electronics | 17        | 18     | 5.15%   |
| Maxtor              | 8         | 8      | 2.42%   |
| Fujitsu             | 6         | 7      | 1.82%   |
| IBM                 | 1         | 1      | 0.3%    |
| China               | 1         | 1      | 0.3%    |
| ASMT                | 1         | 2      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 310       | 399    | 76.92%  |
| SSD  | 85        | 110    | 21.09%  |
| NVMe | 8         | 9      | 1.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB         | 2         | 2      | 15.38%  |
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 7.69%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 7.69%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 7.69%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 53.85%  |
| Samsung Electronics | 3         | 3      | 23.08%  |
| WDC                 | 1         | 1      | 7.69%   |
| Toshiba             | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3014      | 6031   | 58.98%  |
| Works    | 1696      | 3032   | 33.19%  |
| Malfunc  | 387       | 518    | 7.57%   |
| Failed   | 13        | 13     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3202      | 55.86%  |
| AMD                              | 810       | 14.13%  |
| Samsung Electronics              | 439       | 7.66%   |
| SanDisk                          | 250       | 4.36%   |
| SK hynix                         | 114       | 1.99%   |
| Nvidia                           | 104       | 1.81%   |
| Kingston Technology Company      | 94        | 1.64%   |
| Phison Electronics               | 87        | 1.52%   |
| JMicron Technology               | 81        | 1.41%   |
| ASMedia Technology               | 78        | 1.36%   |
| Micron Technology                | 74        | 1.29%   |
| Marvell Technology Group         | 62        | 1.08%   |
| Micron/Crucial Technology        | 60        | 1.05%   |
| Toshiba America Info Systems     | 55        | 0.96%   |
| KIOXIA                           | 53        | 0.92%   |
| Silicon Motion                   | 34        | 0.59%   |
| VIA Technologies                 | 33        | 0.58%   |
| Silicon Integrated Systems [SiS] | 21        | 0.37%   |
| LSI Logic / Symbios Logic        | 13        | 0.23%   |
| Union Memory (Shenzhen)          | 9         | 0.16%   |
| Hewlett-Packard                  | 6         | 0.1%    |
| Silicon Image                    | 5         | 0.09%   |
| Apple                            | 5         | 0.09%   |
| Realtek Semiconductor            | 4         | 0.07%   |
| Broadcom / LSI                   | 4         | 0.07%   |
| ADATA Technology                 | 4         | 0.07%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| O2 Micro                         | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Adaptec                          | 3         | 0.05%   |
| 3ware                            | 3         | 0.05%   |
| Seagate Technology               | 2         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.03%   |
| Lenovo                           | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.02%   |
| Swissbit                         | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 566       | 8.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 248       | 3.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 239       | 3.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 238       | 3.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 144       | 2.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 139       | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 126       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 125       | 1.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 123       | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 122       | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 118       | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 115       | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 102       | 1.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 93        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 92        | 1.36%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 91        | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 89        | 1.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 87        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 85        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 85        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 84        | 1.25%   |
| Samsung NVMe SSD Controller 980                                                         | 82        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 79        | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 77        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 76        | 1.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 76        | 1.13%   |
| Micron Non-Volatile memory controller                                                   | 74        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 71        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 68        | 1.01%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 66        | 0.98%   |
| Intel SSD 660P Series                                                                   | 62        | 0.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 60        | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 60        | 0.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 56        | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 53        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 53        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 49        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 47        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 47        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 47        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3357      | 57.27%  |
| NVMe | 1323      | 22.57%  |
| IDE  | 803       | 13.7%   |
| RAID | 362       | 6.18%   |
| SCSI | 9         | 0.15%   |
| SAS  | 8         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3649      | 77.56%  |
| AMD          | 1025      | 21.79%  |
| ARM          | 28        | 0.6%    |
| QUALCOMM     | 2         | 0.04%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 61        | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 49        | 1.04%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 47        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 39        | 0.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 39        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 37        | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 37        | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.74%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 34        | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor             | 32        | 0.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 28        | 0.59%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 28        | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.57%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 26        | 0.55%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 26        | 0.55%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 26        | 0.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.49%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 23        | 0.49%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 22        | 0.47%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 22        | 0.47%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.45%   |
| ARM Processor                                 | 21        | 0.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 20        | 0.42%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 19        | 0.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.38%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 18        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 906       | 19.21%  |
| Intel Core i7           | 883       | 18.72%  |
| Intel Core i3           | 381       | 8.08%   |
| Other                   | 297       | 6.3%    |
| Intel Celeron           | 291       | 6.17%   |
| AMD Ryzen 5             | 246       | 5.22%   |
| Intel Core 2 Duo        | 234       | 4.96%   |
| AMD Ryzen 7             | 220       | 4.66%   |
| Intel Atom              | 139       | 2.95%   |
| Intel Xeon              | 98        | 2.08%   |
| Intel Pentium           | 88        | 1.87%   |
| Intel Pentium Dual-Core | 79        | 1.68%   |
| Intel Core 2 Quad       | 72        | 1.53%   |
| AMD FX                  | 59        | 1.25%   |
| Intel Pentium Dual      | 52        | 1.1%    |
| Intel Core 2            | 50        | 1.06%   |
| AMD A4                  | 44        | 0.93%   |
| AMD Ryzen 9             | 42        | 0.89%   |
| AMD Ryzen 3             | 42        | 0.89%   |
| AMD A6                  | 36        | 0.76%   |
| Intel Genuine           | 34        | 0.72%   |
| AMD A10                 | 32        | 0.68%   |
| AMD A8                  | 30        | 0.64%   |
| Intel Core i9           | 27        | 0.57%   |
| Intel Pentium 4         | 25        | 0.53%   |
| AMD Athlon 64 X2        | 24        | 0.51%   |
| AMD Athlon II X2        | 22        | 0.47%   |
| AMD E1                  | 21        | 0.45%   |
| AMD Athlon              | 19        | 0.4%    |
| AMD Phenom II X4        | 14        | 0.3%    |
| AMD E                   | 14        | 0.3%    |
| AMD Ryzen 7 PRO         | 11        | 0.23%   |
| Intel Pentium D         | 10        | 0.21%   |
| AMD Phenom              | 10        | 0.21%   |
| Intel Pentium Silver    | 9         | 0.19%   |
| Intel Pentium M         | 9         | 0.19%   |
| Intel Celeron M         | 8         | 0.17%   |
| AMD Phenom II X6        | 8         | 0.17%   |
| Intel Pentium Gold      | 7         | 0.15%   |
| Intel Core m3           | 7         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1954      | 41.39%  |
| 4       | 1670      | 35.37%  |
| 6       | 433       | 9.17%   |
| 8       | 329       | 6.97%   |
| 1       | 181       | 3.83%   |
| 12      | 52        | 1.1%    |
| 10      | 22        | 0.47%   |
| 3       | 20        | 0.42%   |
| 14      | 19        | 0.4%    |
| 16      | 18        | 0.38%   |
| Unknown | 13        | 0.28%   |
| 20      | 3         | 0.06%   |
| 32      | 2         | 0.04%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4665      | 99.13%  |
| 2       | 38        | 0.81%   |
| Unknown | 3         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2936      | 62.23%  |
| 1       | 1768      | 37.47%  |
| Unknown | 13        | 0.28%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4520      | 95.5%   |
| Unknown        | 113       | 2.39%   |
| 32-bit         | 66        | 1.39%   |
| 64-bit         | 34        | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 952       | 19.54%  |
| 0x306c3    | 253       | 5.19%   |
| 0x206a7    | 230       | 4.72%   |
| 0x306a9    | 212       | 4.35%   |
| 0x1067a    | 175       | 3.59%   |
| 0x906ea    | 141       | 2.89%   |
| 0x806ea    | 118       | 2.42%   |
| 0x806c1    | 108       | 2.22%   |
| 0x506e3    | 106       | 2.18%   |
| 0x6fd      | 105       | 2.15%   |
| 0x806ec    | 99        | 2.03%   |
| 0x40651    | 99        | 2.03%   |
| 0x20655    | 97        | 1.99%   |
| 0x806e9    | 91        | 1.87%   |
| 0x406e3    | 89        | 1.83%   |
| 0x306d4    | 75        | 1.54%   |
| 0x906e9    | 71        | 1.46%   |
| 0x08108109 | 70        | 1.44%   |
| 0x30678    | 56        | 1.15%   |
| 0x10676    | 55        | 1.13%   |
| 0x6fb      | 50        | 1.03%   |
| 0x20652    | 48        | 0.99%   |
| 0x08701021 | 47        | 0.96%   |
| 0x706a1    | 45        | 0.92%   |
| 0x0a50000c | 45        | 0.92%   |
| 0x0800820d | 42        | 0.86%   |
| 0x706e5    | 41        | 0.84%   |
| 0x406c4    | 41        | 0.84%   |
| 0x506c9    | 40        | 0.82%   |
| 0xa0652    | 37        | 0.76%   |
| 0x06006705 | 36        | 0.74%   |
| 0x6f6      | 35        | 0.72%   |
| 0x08600106 | 35        | 0.72%   |
| 0x706a8    | 34        | 0.7%    |
| 0x08108102 | 34        | 0.7%    |
| 0x010000c8 | 33        | 0.68%   |
| 0x06001119 | 32        | 0.66%   |
| 0x06000852 | 32        | 0.66%   |
| 0x906ed    | 30        | 0.62%   |
| 0x806eb    | 30        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 731       | 15.5%   |
| Haswell          | 453       | 9.6%    |
| Penryn           | 293       | 6.21%   |
| SandyBridge      | 287       | 6.08%   |
| Core             | 254       | 5.38%   |
| IvyBridge        | 251       | 5.32%   |
| Skylake          | 238       | 5.05%   |
| Zen+             | 188       | 3.99%   |
| Zen 2            | 180       | 3.82%   |
| Westmere         | 173       | 3.67%   |
| Silvermont       | 164       | 3.48%   |
| TigerLake        | 145       | 3.07%   |
| Unknown          | 117       | 2.48%   |
| Zen 3            | 106       | 2.25%   |
| Broadwell        | 103       | 2.18%   |
| CometLake        | 102       | 2.16%   |
| Goldmont plus    | 95        | 2.01%   |
| K10              | 90        | 1.91%   |
| Piledriver       | 89        | 1.89%   |
| Zen              | 85        | 1.8%    |
| Icelake          | 72        | 1.53%   |
| Bonnell          | 67        | 1.42%   |
| Excavator        | 62        | 1.31%   |
| K8 Hammer        | 52        | 1.1%    |
| Nehalem          | 45        | 0.95%   |
| Goldmont         | 45        | 0.95%   |
| NetBurst         | 38        | 0.81%   |
| Puma             | 32        | 0.68%   |
| Alderlake Hybrid | 32        | 0.68%   |
| P6               | 30        | 0.64%   |
| Jaguar           | 26        | 0.55%   |
| Bobcat           | 22        | 0.47%   |
| Steamroller      | 21        | 0.45%   |
| K10 Llano        | 9         | 0.19%   |
| Tremont          | 8         | 0.17%   |
| Bulldozer        | 8         | 0.17%   |
| K8 & K10 hybrid  | 3         | 0.06%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2708      | 48.77%  |
| Nvidia                                       | 1620      | 29.17%  |
| AMD                                          | 1169      | 21.05%  |
| Matrox Electronics Systems                   | 21        | 0.38%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.23%   |
| VIA Technologies                             | 10        | 0.18%   |
| ASPEED Technology                            | 9         | 0.16%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 198       | 3.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 139       | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 129       | 2.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 128       | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 119       | 2.07%   |
| Intel UHD Graphics 620                                                                   | 117       | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 108       | 1.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 101       | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 98        | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 96        | 1.67%   |
| Intel HD Graphics 620                                                                    | 94        | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 88        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 87        | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 87        | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 86        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 86        | 1.5%    |
| AMD Renoir                                                                               | 85        | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 78        | 1.36%   |
| Intel HD Graphics 5500                                                                   | 73        | 1.27%   |
| Intel HD Graphics 530                                                                    | 73        | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 72        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 68        | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 66        | 1.15%   |
| Intel HD Graphics 630                                                                    | 65        | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 62        | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 61        | 1.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 57        | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 56        | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 50        | 0.87%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 46        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 45        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 45        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 45        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.77%   |
| Intel HD Graphics 500                                                                    | 43        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 38        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 38        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1936      | 40.89%  |
| 1 x AMD                | 920       | 19.43%  |
| 1 x Nvidia             | 905       | 19.11%  |
| Intel + Nvidia         | 613       | 12.95%  |
| Intel + AMD            | 96        | 2.03%   |
| AMD + Nvidia           | 84        | 1.77%   |
| 2 x AMD                | 70        | 1.48%   |
| Other                  | 34        | 0.72%   |
| 1 x Matrox             | 18        | 0.38%   |
| 2 x Nvidia             | 14        | 0.3%    |
| 1 x SiS                | 13        | 0.27%   |
| 1 x VIA                | 10        | 0.21%   |
| 1 x ASPEED             | 6         | 0.13%   |
| 2 x Intel              | 5         | 0.11%   |
| Nvidia + Matrox        | 3         | 0.06%   |
| Nvidia + ASPEED        | 3         | 0.06%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3791      | 79.33%  |
| Proprietary | 790       | 16.53%  |
| Unknown     | 198       | 4.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2563      | 52.83%  |
| 1.01-2.0   | 665       | 13.71%  |
| 0.01-0.5   | 578       | 11.92%  |
| 3.01-4.0   | 367       | 7.57%   |
| 0.51-1.0   | 358       | 7.38%   |
| 7.01-8.0   | 173       | 3.57%   |
| 5.01-6.0   | 87        | 1.79%   |
| 2.01-3.0   | 27        | 0.56%   |
| 8.01-16.0  | 27        | 0.56%   |
| 16.01-24.0 | 6         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 598       | 11.78%  |
| AU Optronics            | 542       | 10.68%  |
| Chimei Innolux          | 482       | 9.5%    |
| LG Display              | 423       | 8.33%   |
| Goldstar                | 364       | 7.17%   |
| BOE                     | 354       | 6.97%   |
| Hewlett-Packard         | 247       | 4.87%   |
| BenQ                    | 209       | 4.12%   |
| Dell                    | 200       | 3.94%   |
| Acer                    | 177       | 3.49%   |
| Ancor Communications    | 152       | 2.99%   |
| Philips                 | 133       | 2.62%   |
| AOC                     | 102       | 2.01%   |
| Apple                   | 97        | 1.91%   |
| Chi Mei Optoelectronics | 95        | 1.87%   |
| Sharp                   | 89        | 1.75%   |
| Lenovo                  | 79        | 1.56%   |
| PANDA                   | 57        | 1.12%   |
| LG Electronics          | 53        | 1.04%   |
| Sony                    | 49        | 0.97%   |
| Unknown                 | 46        | 0.91%   |
| LG Philips              | 41        | 0.81%   |
| HannStar                | 41        | 0.81%   |
| ASUSTek Computer        | 32        | 0.63%   |
| ViewSonic               | 27        | 0.53%   |
| InfoVision              | 21        | 0.41%   |
| MSI                     | 19        | 0.37%   |
| Eizo                    | 14        | 0.28%   |
| CPT                     | 12        | 0.24%   |
| Toshiba                 | 11        | 0.22%   |
| OEM                     | 11        | 0.22%   |
| Panasonic               | 10        | 0.2%    |
| ___                     | 9         | 0.18%   |
| Vestel Elektronik       | 9         | 0.18%   |
| NEC Computers           | 9         | 0.18%   |
| Hitachi                 | 9         | 0.18%   |
| Quanta Display          | 8         | 0.16%   |
| Packard Bell            | 8         | 0.16%   |
| Iiyama                  | 8         | 0.16%   |
| Xiaomi                  | 7         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 1.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 35        | 0.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.57%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 29        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 26        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 22        | 0.42%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.42%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch                  | 21        | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 21        | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.31%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 15        | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 15        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 14        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 14        | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 13        | 0.25%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 13        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 13        | 0.25%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 13        | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.23%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 12        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 11        | 0.21%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 11        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 11        | 0.21%   |
| Ancor Communications ASUS VX239 ACI23E1 1920x1080 509x286mm 23.0-inch    | 11        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2093      | 43.31%  |
| 1366x768 (WXGA)    | 1009      | 20.88%  |
| 3840x2160 (4K)     | 227       | 4.7%    |
| 1280x1024 (SXGA)   | 203       | 4.2%    |
| 2560x1440 (QHD)    | 175       | 3.62%   |
| 1280x800 (WXGA)    | 159       | 3.29%   |
| 1680x1050 (WSXGA+) | 147       | 3.04%   |
| 1440x900 (WXGA+)   | 140       | 2.9%    |
| 1600x900 (HD+)     | 110       | 2.28%   |
| 1920x1200 (WUXGA)  | 84        | 1.74%   |
| Unknown            | 58        | 1.2%    |
| 2560x1080          | 54        | 1.12%   |
| 1360x768           | 46        | 0.95%   |
| 1024x600           | 41        | 0.85%   |
| 3440x1440          | 30        | 0.62%   |
| 2560x1600          | 26        | 0.54%   |
| 1024x768 (XGA)     | 25        | 0.52%   |
| 2160x1440          | 22        | 0.46%   |
| 800x1280           | 16        | 0.33%   |
| 3840x1080          | 16        | 0.33%   |
| 2880x1800          | 13        | 0.27%   |
| 1920x540           | 13        | 0.27%   |
| 1600x1200          | 13        | 0.27%   |
| 3200x1800 (QHD+)   | 8         | 0.17%   |
| 3840x2400          | 6         | 0.12%   |
| 2288x1287          | 6         | 0.12%   |
| 3200x1080          | 5         | 0.1%    |
| 1920x1280          | 5         | 0.1%    |
| 4480x1080          | 4         | 0.08%   |
| 2736x1824          | 4         | 0.08%   |
| 1280x768           | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3360x1080          | 3         | 0.06%   |
| 2960x1050          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1400x1050          | 3         | 0.06%   |
| 7680x2160          | 2         | 0.04%   |
| 5760x2160          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1477      | 29.16%  |
| 13      | 382       | 7.54%   |
| 24      | 367       | 7.25%   |
| 21      | 358       | 7.07%   |
| 27      | 328       | 6.48%   |
| Unknown | 293       | 5.78%   |
| 23      | 289       | 5.71%   |
| 17      | 266       | 5.25%   |
| 14      | 262       | 5.17%   |
| 19      | 148       | 2.92%   |
| 18      | 119       | 2.35%   |
| 22      | 84        | 1.66%   |
| 34      | 77        | 1.52%   |
| 20      | 74        | 1.46%   |
| 31      | 72        | 1.42%   |
| 12      | 67        | 1.32%   |
| 10      | 50        | 0.99%   |
| 11      | 49        | 0.97%   |
| 84      | 42        | 0.83%   |
| 16      | 38        | 0.75%   |
| 25      | 24        | 0.47%   |
| 72      | 23        | 0.45%   |
| 54      | 23        | 0.45%   |
| 32      | 23        | 0.45%   |
| 26      | 22        | 0.43%   |
| 40      | 17        | 0.34%   |
| 65      | 7         | 0.14%   |
| 52      | 7         | 0.14%   |
| 46      | 7         | 0.14%   |
| 28      | 7         | 0.14%   |
| 7       | 6         | 0.12%   |
| 142     | 5         | 0.1%    |
| 48      | 5         | 0.1%    |
| 60      | 4         | 0.08%   |
| 43      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 8       | 4         | 0.08%   |
| 47      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 38      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1999      | 40.17%  |
| 501-600        | 916       | 18.41%  |
| 401-500        | 710       | 14.27%  |
| 201-300        | 392       | 7.88%   |
| Unknown        | 293       | 5.89%   |
| 351-400        | 268       | 5.39%   |
| 601-700        | 118       | 2.37%   |
| 701-800        | 101       | 2.03%   |
| 1501-2000      | 67        | 1.35%   |
| 1001-1500      | 61        | 1.23%   |
| 801-900        | 27        | 0.54%   |
| 1-100          | 8         | 0.16%   |
| 901-1000       | 7         | 0.14%   |
| More than 2000 | 5         | 0.1%    |
| 101-200        | 4         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3375      | 73.53%  |
| 16/10   | 572       | 12.46%  |
| Unknown | 238       | 5.19%   |
| 5/4     | 187       | 4.07%   |
| 21/9    | 80        | 1.74%   |
| 4/3     | 53        | 1.15%   |
| 3/2     | 52        | 1.13%   |
| 0.62    | 12        | 0.26%   |
| 0.67    | 6         | 0.13%   |
| 1.00    | 5         | 0.11%   |
| 32/9    | 4         | 0.09%   |
| 6/5     | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1478      | 29.38%  |
| 201-250        | 892       | 17.73%  |
| 81-90          | 456       | 9.07%   |
| 301-350        | 337       | 6.7%    |
| 151-200        | 330       | 6.56%   |
| Unknown        | 293       | 5.83%   |
| 141-150        | 212       | 4.21%   |
| 71-80          | 189       | 3.76%   |
| 351-500        | 178       | 3.54%   |
| 251-300        | 128       | 2.54%   |
| More than 1000 | 122       | 2.43%   |
| 121-130        | 118       | 2.35%   |
| 61-70          | 58        | 1.15%   |
| 41-50          | 50        | 0.99%   |
| 51-60          | 49        | 0.97%   |
| 501-1000       | 47        | 0.93%   |
| 131-140        | 35        | 0.7%    |
| 111-120        | 28        | 0.56%   |
| 91-100         | 18        | 0.36%   |
| 1-40           | 12        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1699      | 34.75%  |
| 101-120       | 1351      | 27.63%  |
| 121-160       | 1137      | 23.26%  |
| Unknown       | 293       | 5.99%   |
| 161-240       | 241       | 4.93%   |
| 1-50          | 104       | 2.13%   |
| More than 240 | 64        | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3836      | 79.63%  |
| 2     | 683       | 14.18%  |
| 0     | 215       | 4.46%   |
| 3     | 77        | 1.6%    |
| 4     | 6         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2695      | 37.88%  |
| Intel                             | 1995      | 28.04%  |
| Qualcomm Atheros                  | 902       | 12.68%  |
| Broadcom                          | 437       | 6.14%   |
| TP-Link                           | 115       | 1.62%   |
| Ralink Technology                 | 113       | 1.59%   |
| Marvell Technology Group          | 109       | 1.53%   |
| Broadcom Limited                  | 94        | 1.32%   |
| Nvidia                            | 87        | 1.22%   |
| Ralink                            | 77        | 1.08%   |
| MediaTek                          | 54        | 0.76%   |
| Qualcomm Atheros Communications   | 42        | 0.59%   |
| Samsung Electronics               | 29        | 0.41%   |
| Xiaomi                            | 27        | 0.38%   |
| D-Link                            | 23        | 0.32%   |
| ASIX Electronics                  | 23        | 0.32%   |
| Silicon Integrated Systems [SiS]  | 19        | 0.27%   |
| VIA Technologies                  | 17        | 0.24%   |
| ASUSTek Computer                  | 17        | 0.24%   |
| D-Link System                     | 16        | 0.22%   |
| DisplayLink                       | 15        | 0.21%   |
| Qualcomm                          | 14        | 0.2%    |
| Sierra Wireless                   | 12        | 0.17%   |
| Hewlett-Packard                   | 12        | 0.17%   |
| Ericsson Business Mobile Networks | 12        | 0.17%   |
| Dell                              | 12        | 0.17%   |
| Belkin Components                 | 12        | 0.17%   |
| Lenovo                            | 11        | 0.15%   |
| JMicron Technology                | 11        | 0.15%   |
| Microsoft                         | 8         | 0.11%   |
| Huawei Technologies               | 8         | 0.11%   |
| Edimax Technology                 | 6         | 0.08%   |
| ZyDAS                             | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| NetGear                           | 4         | 0.06%   |
| LSI                               | 4         | 0.06%   |
| Gemtek                            | 4         | 0.06%   |
| Attansic Technology               | 4         | 0.06%   |
| Accton Technology                 | 4         | 0.06%   |
| Toshiba                           | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1838      | 22.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 298       | 3.64%   |
| Intel Wi-Fi 6 AX200                                                     | 183       | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 143       | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 120       | 1.46%   |
| Intel Wireless 8265 / 8275                                              | 120       | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 109       | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 108       | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 106       | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 105       | 1.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 101       | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 101       | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 100       | 1.22%   |
| Intel Wireless 7265                                                     | 97        | 1.18%   |
| Intel Wireless 3165                                                     | 87        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 1.05%   |
| Intel I211 Gigabit Network Connection                                   | 82        | 1%      |
| Intel Ethernet Connection (2) I219-V                                    | 81        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                       | 68        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 68        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 67        | 0.82%   |
| Intel Wireless 7260                                                     | 66        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 50        | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 48        | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 45        | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 0.54%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 43        | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 42        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 42        | 0.51%   |
| Intel Wireless 8260                                                     | 42        | 0.51%   |
| Intel WiFi Link 5100                                                    | 41        | 0.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 41        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 40        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                 | 39        | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 38        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1498      | 39.9%   |
| Realtek Semiconductor                 | 710       | 18.91%  |
| Qualcomm Atheros                      | 694       | 18.49%  |
| Broadcom                              | 271       | 7.22%   |
| Ralink Technology                     | 113       | 3.01%   |
| TP-Link                               | 96        | 2.56%   |
| Ralink                                | 77        | 2.05%   |
| Broadcom Limited                      | 64        | 1.7%    |
| Qualcomm Atheros Communications       | 42        | 1.12%   |
| MediaTek                              | 42        | 1.12%   |
| D-Link                                | 23        | 0.61%   |
| ASUSTek Computer                      | 17        | 0.45%   |
| Sierra Wireless                       | 12        | 0.32%   |
| Belkin Components                     | 12        | 0.32%   |
| D-Link System                         | 10        | 0.27%   |
| Microsoft                             | 7         | 0.19%   |
| Dell                                  | 7         | 0.19%   |
| Marvell Technology Group              | 6         | 0.16%   |
| Edimax Technology                     | 6         | 0.16%   |
| ZyDAS                                 | 5         | 0.13%   |
| Qualcomm                              | 4         | 0.11%   |
| NetGear                               | 4         | 0.11%   |
| Hewlett-Packard                       | 4         | 0.11%   |
| Gemtek                                | 4         | 0.11%   |
| Ericsson Business Mobile Networks     | 4         | 0.11%   |
| Texas Instruments                     | 3         | 0.08%   |
| Sitecom Europe                        | 2         | 0.05%   |
| Linksys                               | 2         | 0.05%   |
| Fibocom                               | 2         | 0.05%   |
| Accton Technology                     | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Wacom                                 | 1         | 0.03%   |
| TRENDnet                              | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Standard Microsystems                 | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| AirTies Wireless Networks             | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 183       | 4.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 120       | 3.17%   |
| Intel Wireless 8265 / 8275                                              | 120       | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 109       | 2.88%   |
| Intel Wi-Fi 6 AX201                                                     | 108       | 2.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 106       | 2.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 101       | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 101       | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 100       | 2.65%   |
| Intel Wireless 7265                                                     | 97        | 2.57%   |
| Intel Wireless 3165                                                     | 87        | 2.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 2.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 68        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 67        | 1.77%   |
| Intel Wireless 7260                                                     | 66        | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                           | 50        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 48        | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 45        | 1.19%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 42        | 1.11%   |
| Intel Wireless 8260                                                     | 42        | 1.11%   |
| Intel WiFi Link 5100                                                    | 41        | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 41        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 40        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                         | 38        | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 37        | 0.98%   |
| Intel Wireless 3160                                                     | 37        | 0.98%   |
| Realtek 802.11ac NIC                                                    | 36        | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 36        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 33        | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 32        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 31        | 0.82%   |
| Intel Wireless-AC 9260                                                  | 30        | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 29        | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2397      | 56.04%  |
| Intel                                  | 906       | 21.18%  |
| Qualcomm Atheros                       | 289       | 6.76%   |
| Broadcom                               | 214       | 5%      |
| Marvell Technology Group               | 104       | 2.43%   |
| Nvidia                                 | 87        | 2.03%   |
| Broadcom Limited                       | 32        | 0.75%   |
| Samsung Electronics                    | 28        | 0.65%   |
| Xiaomi                                 | 26        | 0.61%   |
| ASIX Electronics                       | 23        | 0.54%   |
| TP-Link                                | 19        | 0.44%   |
| Silicon Integrated Systems [SiS]       | 19        | 0.44%   |
| VIA Technologies                       | 17        | 0.4%    |
| DisplayLink                            | 15        | 0.35%   |
| MediaTek                               | 12        | 0.28%   |
| Lenovo                                 | 11        | 0.26%   |
| JMicron Technology                     | 11        | 0.26%   |
| Qualcomm                               | 10        | 0.23%   |
| D-Link System                          | 6         | 0.14%   |
| LSI                                    | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Attansic Technology                    | 4         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.07%   |
| Microchip Technology                   | 3         | 0.07%   |
| IBM                                    | 3         | 0.07%   |
| Huawei Technologies                    | 3         | 0.07%   |
| Aquantia                               | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Davicom Semiconductor                  | 2         | 0.05%   |
| ADMtek                                 | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OPPO                                   | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Microsoft                              | 1         | 0.02%   |
| Meizu                                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1838      | 42.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 298       | 6.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 143       | 3.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 105       | 2.41%   |
| Intel I211 Gigabit Network Connection                             | 82        | 1.88%   |
| Intel Ethernet Connection (2) I219-V                              | 81        | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 68        | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 43        | 0.99%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 39        | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 37        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 36        | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 36        | 0.83%   |
| Intel Ethernet Controller I225-V                                  | 34        | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 32        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 28        | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 27        | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 27        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 25        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 25        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 23        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                              | 23        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 23        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 22        | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 20        | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 19        | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18        | 0.41%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.41%   |
| Intel Ethernet Connection (13) I219-V                             | 17        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4079      | 53.27%  |
| WiFi     | 3526      | 46.05%  |
| Modem    | 48        | 0.63%   |
| Unknown  | 4         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2676      | 54.53%  |
| Ethernet | 2231      | 45.47%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2532      | 53.54%  |
| 1     | 1995      | 42.19%  |
| 0     | 110       | 2.33%   |
| 3     | 69        | 1.46%   |
| 4     | 15        | 0.32%   |
| 6     | 4         | 0.08%   |
| 5     | 4         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4557      | 96.44%  |
| Yes  | 168       | 3.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1188      | 43.66%  |
| Realtek Semiconductor           | 321       | 11.8%   |
| Cambridge Silicon Radio         | 236       | 8.67%   |
| IMC Networks                    | 167       | 6.14%   |
| Qualcomm Atheros Communications | 152       | 5.59%   |
| Broadcom                        | 118       | 4.34%   |
| Apple                           | 107       | 3.93%   |
| Lite-On Technology              | 94        | 3.45%   |
| Foxconn / Hon Hai               | 81        | 2.98%   |
| ASUSTek Computer                | 47        | 1.73%   |
| Realtek                         | 36        | 1.32%   |
| Toshiba                         | 35        | 1.29%   |
| Dell                            | 28        | 1.03%   |
| Hewlett-Packard                 | 23        | 0.85%   |
| Ralink                          | 17        | 0.62%   |
| Alps Electric                   | 13        | 0.48%   |
| Belkin Components               | 9         | 0.33%   |
| Integrated System Solution      | 8         | 0.29%   |
| Foxconn International           | 8         | 0.29%   |
| MediaTek                        | 7         | 0.26%   |
| TP-Link                         | 6         | 0.22%   |
| Ralink Technology               | 4         | 0.15%   |
| Marvell Semiconductor           | 4         | 0.15%   |
| Edimax Technology               | 3         | 0.11%   |
| Roper                           | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 450       | 16.54%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 236       | 8.67%   |
| Realtek Bluetooth Radio                             | 229       | 8.42%   |
| Intel AX201 Bluetooth                               | 211       | 7.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 195       | 7.17%   |
| Intel AX200 Bluetooth                               | 178       | 6.54%   |
| IMC Networks Bluetooth Radio                        | 80        | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 63        | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 2.17%   |
| IMC Networks Bluetooth Device                       | 47        | 1.73%   |
| Intel Wireless-AC 3168 Bluetooth                    | 43        | 1.58%   |
| Apple Bluetooth Host Controller                     | 41        | 1.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 37        | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 35        | 1.29%   |
| Apple Bluetooth USB Host Controller                 | 33        | 1.21%   |
| Intel AX210 Bluetooth                               | 31        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.03%   |
| Realtek 802.11ac WLAN Adapter                       | 25        | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 25        | 0.92%   |
| Lite-On Bluetooth Device                            | 25        | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 0.88%   |
| IMC Networks Wireless_Device                        | 24        | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                    | 23        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 0.7%    |
| Intel Bluetooth Device                              | 18        | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 18        | 0.66%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.62%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.55%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 15        | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.48%   |
| Apple Bluetooth HCI                                 | 13        | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.44%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.44%   |
| Realtek Bluetooth Radio                             | 11        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.4%    |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3440      | 54.26%  |
| AMD                                  | 1240      | 19.56%  |
| Nvidia                               | 1104      | 17.41%  |
| C-Media Electronics                  | 102       | 1.61%   |
| Creative Labs                        | 37        | 0.58%   |
| Logitech                             | 34        | 0.54%   |
| Texas Instruments                    | 23        | 0.36%   |
| JMTek                                | 22        | 0.35%   |
| Silicon Integrated Systems [SiS]     | 21        | 0.33%   |
| VIA Technologies                     | 19        | 0.3%    |
| GN Netcom                            | 19        | 0.3%    |
| Plantronics                          | 18        | 0.28%   |
| Kingston Technology                  | 18        | 0.28%   |
| Corsair                              | 15        | 0.24%   |
| Focusrite-Novation                   | 13        | 0.21%   |
| Realtek Semiconductor                | 12        | 0.19%   |
| ASUSTek Computer                     | 12        | 0.19%   |
| Lenovo                               | 11        | 0.17%   |
| Creative Technology                  | 11        | 0.17%   |
| Generalplus Technology               | 10        | 0.16%   |
| SteelSeries ApS                      | 8         | 0.13%   |
| DSEA A/S                             | 7         | 0.11%   |
| Ensoniq                              | 6         | 0.09%   |
| BEHRINGER International              | 6         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.08%   |
| M-Audio                              | 5         | 0.08%   |
| Hewlett-Packard                      | 5         | 0.08%   |
| Apple                                | 5         | 0.08%   |
| Yamaha                               | 4         | 0.06%   |
| Tenx Technology                      | 4         | 0.06%   |
| Razer USA                            | 4         | 0.06%   |
| Dell                                 | 4         | 0.06%   |
| Blue Microphones                     | 4         | 0.06%   |
| Sony                                 | 3         | 0.05%   |
| SAVITECH                             | 3         | 0.05%   |
| QinHeng Electronics                  | 3         | 0.05%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| Micro Star International             | 3         | 0.05%   |
| Guillemot                            | 3         | 0.05%   |
| Evolution Electronics                | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 353       | 4.71%   |
| Intel Sunrise Point-LP HD Audio                                            | 328       | 4.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 266       | 3.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 263       | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 249       | 3.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 218       | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 203       | 2.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 187       | 2.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 186       | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 181       | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 150       | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 150       | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 145       | 1.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 145       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 141       | 1.88%   |
| AMD FCH Azalia Controller                                                  | 134       | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 130       | 1.73%   |
| Intel 8 Series HD Audio Controller                                         | 130       | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 129       | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 125       | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 110       | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 105       | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 102       | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 101       | 1.35%   |
| Intel 200 Series PCH HD Audio                                              | 100       | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 97        | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 95        | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 95        | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 87        | 1.16%   |
| Nvidia High Definition Audio Controller                                    | 85        | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 80        | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                   | 67        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 65        | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 65        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 61        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 60        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 58        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 56        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 53        | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 50        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 597       | 22.48%  |
| SK hynix            | 426       | 16.04%  |
| Kingston            | 414       | 15.59%  |
| Unknown             | 294       | 11.07%  |
| Micron Technology   | 242       | 9.11%   |
| Crucial             | 185       | 6.97%   |
| Corsair             | 115       | 4.33%   |
| G.Skill             | 81        | 3.05%   |
| Ramaxel Technology  | 64        | 2.41%   |
| Elpida              | 37        | 1.39%   |
| Unknown (ABCD)      | 34        | 1.28%   |
| A-DATA Technology   | 22        | 0.83%   |
| Nanya Technology    | 21        | 0.79%   |
| Silicon Power       | 14        | 0.53%   |
| GOODRAM             | 12        | 0.45%   |
| Unknown             | 12        | 0.45%   |
| Transcend           | 8         | 0.3%    |
| Team                | 8         | 0.3%    |
| Apacer              | 7         | 0.26%   |
| Unifosa             | 6         | 0.23%   |
| Wilk                | 4         | 0.15%   |
| Patriot             | 4         | 0.15%   |
| ASint Technology    | 4         | 0.15%   |
| Kllisre             | 3         | 0.11%   |
| Atermiter           | 3         | 0.11%   |
| Timetec             | 2         | 0.08%   |
| SHARETRONIC         | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| PNY                 | 2         | 0.08%   |
| Micron/Elpida       | 2         | 0.08%   |
| KomputerBay         | 2         | 0.08%   |
| Innodisk            | 2         | 0.08%   |
| Exceleram           | 2         | 0.08%   |
| Avant               | 2         | 0.08%   |
| Unknown (AB)        | 1         | 0.04%   |
| Unknown (0x5846)    | 1         | 0.04%   |
| Unknown (07FB)      | 1         | 0.04%   |
| Toshiba             | 1         | 0.04%   |
| Thermaltake         | 1         | 0.04%   |
| Pioneer             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 29        | 1.02%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.74%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 18        | 0.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 18        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 17        | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.53%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 15        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 12        | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.42%   |
| Unknown                                                          | 12        | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.39%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s         | 11        | 0.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 0.39%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.35%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 10        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.35%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 10        | 0.35%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 10        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 9         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1095      | 47.34%  |
| DDR3    | 748       | 32.34%  |
| DDR2    | 135       | 5.84%   |
| LPDDR4  | 87        | 3.76%   |
| Unknown | 75        | 3.24%   |
| SDRAM   | 68        | 2.94%   |
| LPDDR3  | 59        | 2.55%   |
| DDR5    | 17        | 0.73%   |
| DDR     | 17        | 0.73%   |
| LPDDR5  | 6         | 0.26%   |
| DRAM    | 6         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1361      | 58.82%  |
| DIMM         | 782       | 33.79%  |
| Row Of Chips | 156       | 6.74%   |
| Chip         | 9         | 0.39%   |
| FB-DIMM      | 3         | 0.13%   |
| RIMM         | 2         | 0.09%   |
| Unknown      | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 956       | 38.07%  |
| 4096  | 692       | 27.56%  |
| 2048  | 347       | 13.82%  |
| 16384 | 345       | 13.74%  |
| 1024  | 110       | 4.38%   |
| 32768 | 47        | 1.87%   |
| 512   | 8         | 0.32%   |
| 65536 | 3         | 0.12%   |
| 256   | 2         | 0.08%   |
| 3072  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 470       | 18.75%  |
| 2667    | 370       | 14.76%  |
| 3200    | 353       | 14.08%  |
| 2400    | 200       | 7.98%   |
| 1333    | 169       | 6.74%   |
| 2133    | 130       | 5.19%   |
| 667     | 89        | 3.55%   |
| 1334    | 78        | 3.11%   |
| 800     | 73        | 2.91%   |
| 3600    | 63        | 2.51%   |
| 1867    | 56        | 2.23%   |
| Unknown | 56        | 2.23%   |
| 4267    | 31        | 1.24%   |
| 8400    | 30        | 1.2%    |
| 1067    | 27        | 1.08%   |
| 3466    | 24        | 0.96%   |
| 3266    | 24        | 0.96%   |
| 2933    | 19        | 0.76%   |
| 1866    | 18        | 0.72%   |
| 3400    | 17        | 0.68%   |
| 1066    | 17        | 0.68%   |
| 533     | 17        | 0.68%   |
| 4800    | 15        | 0.6%    |
| 3733    | 13        | 0.52%   |
| 2733    | 13        | 0.52%   |
| 2048    | 13        | 0.52%   |
| 4199    | 12        | 0.48%   |
| 3000    | 12        | 0.48%   |
| 2666    | 8         | 0.32%   |
| 6400    | 7         | 0.28%   |
| 3800    | 7         | 0.28%   |
| 2800    | 7         | 0.28%   |
| 4266    | 6         | 0.24%   |
| 1639    | 5         | 0.2%    |
| 975     | 5         | 0.2%    |
| 400     | 5         | 0.2%    |
| 3500    | 4         | 0.16%   |
| 1800    | 4         | 0.16%   |
| 5200    | 3         | 0.12%   |
| 3666    | 3         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 62        | 49.6%   |
| Brother Industries       | 23        | 18.4%   |
| Canon                    | 13        | 10.4%   |
| Samsung Electronics      | 9         | 7.2%    |
| Seiko Epson              | 8         | 6.4%    |
| Oki Data                 | 3         | 2.4%    |
| Dymo-CoStar              | 2         | 1.6%    |
| Ricoh                    | 1         | 0.8%    |
| Magic Control Technology | 1         | 0.8%    |
| Lexmark International    | 1         | 0.8%    |
| Kyocera                  | 1         | 0.8%    |
| Apple                    | 1         | 0.8%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 3.97%   |
| Brother HL-2030 Laser Printer                   | 5         | 3.97%   |
| Canon PIXMA MG2500 Series                       | 4         | 3.17%   |
| Oki Data USB Device                             | 3         | 2.38%   |
| HP LaserJet 1020                                | 3         | 2.38%   |
| HP DeskJet F2492 All-in-One                     | 3         | 2.38%   |
| HP DeskJet 2700 series                          | 3         | 2.38%   |
| HP DeskJet 2620 All-in-One Printer              | 3         | 2.38%   |
| HP Deskjet 1050 J410                            | 3         | 2.38%   |
| Canon LiDE 400                                  | 3         | 2.38%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.59%   |
| Samsung M2070 Series                            | 2         | 1.59%   |
| HP LaserJet 1010                                | 2         | 1.59%   |
| HP ENVY 5540 series                             | 2         | 1.59%   |
| HP ENVY 5000 series                             | 2         | 1.59%   |
| HP ENVY 4520 series                             | 2         | 1.59%   |
| HP DeskJet 5550                                 | 2         | 1.59%   |
| HP DeskJet 3630 series                          | 2         | 1.59%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.59%   |
| Brother Printer                                 | 2         | 1.59%   |
| Brother MFC-J5330DW                             | 2         | 1.59%   |
| Brother DCP-1510                                | 2         | 1.59%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.79%   |
| Seiko Epson XP-230 Series                       | 1         | 0.79%   |
| Seiko Epson XP-225 Series                       | 1         | 0.79%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.79%   |
| Seiko Epson Printer                             | 1         | 0.79%   |
| Seiko Epson L555 Series                         | 1         | 0.79%   |
| Seiko Epson L1300 Series                        | 1         | 0.79%   |
| Seiko Epson ET-2700 Series                      | 1         | 0.79%   |
| Samsung SCX-4300 Series                         | 1         | 0.79%   |
| Samsung SCX-3400 Series                         | 1         | 0.79%   |
| Samsung SCX-3200 Series                         | 1         | 0.79%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.79%   |
| Samsung M267x 287x Series                       | 1         | 0.79%   |
| Ricoh SP 112                                    | 1         | 0.79%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.79%   |
| Lexmark International B2236dw                   | 1         | 0.79%   |
| Kyocera ECOSYS M5521cdn                         | 1         | 0.79%   |
| HP PSC-1315/PSC-1317                            | 1         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 43.75%  |
| Hewlett-Packard             | 8         | 25%     |
| Seiko Epson                 | 6         | 18.75%  |
| Acer Peripherals (now BenQ) | 2         | 6.25%   |
| Mustek Systems              | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.5%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.25%   |
| HP Scanjet 300                                           | 2         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 3.13%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.13%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.13%   |
| HP Scanjet N6010                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                         | 1         | 3.13%   |
| HP ScanJet 4570c                                         | 1         | 3.13%   |
| HP ScanJet 4300c                                         | 1         | 3.13%   |
| HP ScanJet 3570c                                         | 1         | 3.13%   |
| HP ScanJet 3300c                                         | 1         | 3.13%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 624       | 22.93%  |
| IMC Networks                           | 298       | 10.95%  |
| Acer                                   | 254       | 9.33%   |
| Realtek Semiconductor                  | 175       | 6.43%   |
| Microdia                               | 168       | 6.17%   |
| Logitech                               | 128       | 4.7%    |
| Quanta                                 | 122       | 4.48%   |
| Suyin                                  | 118       | 4.34%   |
| Sunplus Innovation Technology          | 116       | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 97        | 3.56%   |
| Syntek                                 | 75        | 2.76%   |
| Apple                                  | 75        | 2.76%   |
| Alcor Micro                            | 48        | 1.76%   |
| Lite-On Technology                     | 42        | 1.54%   |
| Luxvisions Innotech Limited            | 33        | 1.21%   |
| Ricoh                                  | 31        | 1.14%   |
| Silicon Motion                         | 20        | 0.74%   |
| Samsung Electronics                    | 20        | 0.74%   |
| Creative Technology                    | 18        | 0.66%   |
| Z-Star Microelectronics                | 16        | 0.59%   |
| Microsoft                              | 16        | 0.59%   |
| GEMBIRD                                | 13        | 0.48%   |
| Sonix Technology                       | 11        | 0.4%    |
| Generalplus Technology                 | 11        | 0.4%    |
| Lenovo                                 | 10        | 0.37%   |
| KYE Systems (Mouse Systems)            | 9         | 0.33%   |
| Importek                               | 9         | 0.33%   |
| icSpring                               | 9         | 0.33%   |
| ALi                                    | 9         | 0.33%   |
| Sunplus Technology                     | 8         | 0.29%   |
| ARC International                      | 8         | 0.29%   |
| Jieli Technology                       | 7         | 0.26%   |
| Intel                                  | 7         | 0.26%   |
| SunplusIT                              | 6         | 0.22%   |
| Primax Electronics                     | 6         | 0.22%   |
| Genesys Logic                          | 6         | 0.22%   |
| Cubeternet                             | 6         | 0.22%   |
| 2M UVC CAMERA                          | 6         | 0.22%   |
| OmniVision Technologies                | 5         | 0.18%   |
| DigiTech                               | 5         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 80        | 2.92%   |
| Chicony HD WebCam                                       | 69        | 2.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 2.45%   |
| Chicony Integrated Camera                               | 64        | 2.34%   |
| Acer Integrated Camera                                  | 60        | 2.19%   |
| Microdia Integrated_Webcam_HD                           | 58        | 2.12%   |
| Acer HD Webcam                                          | 53        | 1.94%   |
| IMC Networks Integrated Camera                          | 46        | 1.68%   |
| Chicony USB2.0 VGA UVC WebCam                           | 41        | 1.5%    |
| Realtek Integrated_Webcam_HD                            | 35        | 1.28%   |
| Logitech Webcam C270                                    | 33        | 1.21%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 32        | 1.17%   |
| Apple Built-in iSight                                   | 31        | 1.13%   |
| Quanta HP TrueVision HD Camera                          | 29        | 1.06%   |
| Chicony EasyCamera                                      | 29        | 1.06%   |
| Syntek Integrated Camera                                | 28        | 1.02%   |
| Realtek USB Camera                                      | 28        | 1.02%   |
| Sunplus HD WebCam                                       | 26        | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 0.95%   |
| Chicony USB 2.0 Camera                                  | 25        | 0.91%   |
| Microdia Webcam Vitade AF                               | 24        | 0.88%   |
| Acer EasyCamera                                         | 21        | 0.77%   |
| Samsung Galaxy A5 (MTP)                                 | 20        | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                            | 19        | 0.69%   |
| Chicony HP Truevision HD                                | 19        | 0.69%   |
| Apple FaceTime HD Camera (Built-in)                     | 19        | 0.69%   |
| Acer HD Camera                                          | 19        | 0.69%   |
| Syntek EasyCamera                                       | 18        | 0.66%   |
| Lite-On Integrated Camera                               | 18        | 0.66%   |
| Chicony VGA Webcam                                      | 18        | 0.66%   |
| Chicony HP HD Camera                                    | 18        | 0.66%   |
| Syntek Lenovo EasyCamera                                | 17        | 0.62%   |
| Chicony USB2.0 Camera                                   | 17        | 0.62%   |
| Chicony HP TrueVision HD Camera                         | 17        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 17        | 0.62%   |
| Acer Lenovo EasyCamera                                  | 17        | 0.62%   |
| Realtek Lenovo EasyCamera                               | 16        | 0.58%   |
| Quanta HP HD Camera                                     | 16        | 0.58%   |
| Logitech HD Pro Webcam C920                             | 16        | 0.58%   |
| IMC Networks ov9734_azurewave_camera                    | 16        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 116       | 29.82%  |
| Validity Sensors           | 92        | 23.65%  |
| Shenzhen Goodix Technology | 64        | 16.45%  |
| Elan Microelectronics      | 37        | 9.51%   |
| AuthenTec                  | 35        | 9%      |
| Upek                       | 25        | 6.43%   |
| LighTuning Technology      | 13        | 3.34%   |
| STMicroelectronics         | 7         | 1.8%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 50        | 12.85%  |
| Shenzhen Goodix  Fingerprint Device                                        | 45        | 11.57%  |
| Elan ELAN:Fingerprint                                                      | 34        | 8.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 6.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 5.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 4.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.83%   |
| Synaptics  WBDI                                                            | 10        | 2.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.06%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.8%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.8%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.54%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.54%   |
| AuthenTec AES1600                                                          | 6         | 1.54%   |
| Validity Sensors VFS491                                                    | 5         | 1.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.29%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.29%   |
| AuthenTec AES2810                                                          | 5         | 1.29%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.03%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.03%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.77%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.77%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.77%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.51%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.51%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.51%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 67        | 34.36%  |
| Broadcom                  | 52        | 26.67%  |
| O2 Micro                  | 23        | 11.79%  |
| Lenovo                    | 8         | 4.1%    |
| Advanced Card Systems     | 8         | 4.1%    |
| Chicony Electronics       | 6         | 3.08%   |
| Realtek Semiconductor     | 5         | 2.56%   |
| Cherry                    | 5         | 2.56%   |
| C3PO                      | 5         | 2.56%   |
| Upek                      | 4         | 2.05%   |
| SCM Microsystems          | 3         | 1.54%   |
| Gemalto (was Gemplus)     | 3         | 1.54%   |
| OmniKey                   | 2         | 1.03%   |
| Hewlett-Packard           | 2         | 1.03%   |
| In Focus Systems          | 1         | 0.51%   |
| Fujitsu Siemens Computers | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 63        | 32.31%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 11.28%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 9.23%   |
| Broadcom 5880                                                                | 16        | 8.21%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 4.62%   |
| Broadcom 58200                                                               | 9         | 4.62%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 4.1%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 3.08%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 3.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 2.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.05%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 2.05%   |
| C3PO LTC31v2                                                                 | 4         | 2.05%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 2.05%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.03%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.03%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.03%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.03%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.51%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.51%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.51%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.51%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.51%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.51%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.51%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.51%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3535      | 73.29%  |
| 1     | 1021      | 21.17%  |
| 2     | 223       | 4.62%   |
| 3     | 29        | 0.6%    |
| 4     | 7         | 0.15%   |
| 5     | 5         | 0.1%    |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 399       | 25.64%  |
| Fingerprint reader       | 381       | 24.49%  |
| Net/wireless             | 230       | 14.78%  |
| Chipcard                 | 158       | 10.15%  |
| Multimedia controller    | 96        | 6.17%   |
| Camera                   | 51        | 3.28%   |
| Communication controller | 50        | 3.21%   |
| Bluetooth                | 39        | 2.51%   |
| Unassigned class         | 28        | 1.8%    |
| Storage                  | 24        | 1.54%   |
| Sound                    | 22        | 1.41%   |
| Card reader              | 22        | 1.41%   |
| Net/ethernet             | 14        | 0.9%    |
| Network                  | 11        | 0.71%   |
| Flash memory             | 10        | 0.64%   |
| Modem                    | 9         | 0.58%   |
| Dvb card                 | 6         | 0.39%   |
| Firewire controller      | 3         | 0.19%   |
| Tv card                  | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |

