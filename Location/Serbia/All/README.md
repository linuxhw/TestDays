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

Total: 1179

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| ASUSTek       | K53E                        | Notebook    | [314e6bbbd2](https://linux-hardware.org/?probe=314e6bbbd2) | May 04, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [07a49be491](https://linux-hardware.org/?probe=07a49be491) | May 03, 2021 |
| ASUSTek       | K53E                        | Notebook    | [9a34eba18a](https://linux-hardware.org/?probe=9a34eba18a) | May 03, 2021 |
| Fujitsu Si... | AMILO Pi 2512               | Notebook    | [bc0294a996](https://linux-hardware.org/?probe=bc0294a996) | May 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3B00... | Notebook    | [fa546522c1](https://linux-hardware.org/?probe=fa546522c1) | May 02, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [325c441d47](https://linux-hardware.org/?probe=325c441d47) | Apr 27, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [15e01ddb68](https://linux-hardware.org/?probe=15e01ddb68) | Apr 27, 2021 |
| Medion        | P6812                       | Notebook    | [a45bd7fc22](https://linux-hardware.org/?probe=a45bd7fc22) | Apr 19, 2021 |
| Inventec      | R CLASS A02                 | Desktop     | [d678a44af1](https://linux-hardware.org/?probe=d678a44af1) | Apr 18, 2021 |
| Lenovo        | 312A NOK                    | Desktop     | [5db737f928](https://linux-hardware.org/?probe=5db737f928) | Apr 16, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [2b821447d2](https://linux-hardware.org/?probe=2b821447d2) | Apr 14, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [e7a7c4b64f](https://linux-hardware.org/?probe=e7a7c4b64f) | Apr 14, 2021 |
| Acer          | Aspire A315-23              | Notebook    | [c7a0c1bf24](https://linux-hardware.org/?probe=c7a0c1bf24) | Apr 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [88ca55e5af](https://linux-hardware.org/?probe=88ca55e5af) | Apr 08, 2021 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [8f6e544820](https://linux-hardware.org/?probe=8f6e544820) | Apr 07, 2021 |
| ASUSTek       | PN62S                       | Mini pc     | [1c1741820b](https://linux-hardware.org/?probe=1c1741820b) | Apr 03, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [97f260c7d5](https://linux-hardware.org/?probe=97f260c7d5) | Mar 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [084a69a05a](https://linux-hardware.org/?probe=084a69a05a) | Mar 30, 2021 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [9988abc6d1](https://linux-hardware.org/?probe=9988abc6d1) | Mar 30, 2021 |
| Dell          | G5 5587                     | Notebook    | [862386a9b4](https://linux-hardware.org/?probe=862386a9b4) | Mar 27, 2021 |
| HP            | 3032h                       | Desktop     | [04ae8fc721](https://linux-hardware.org/?probe=04ae8fc721) | Mar 26, 2021 |
| Acer          | FIH57                       | Desktop     | [ddb03d82a0](https://linux-hardware.org/?probe=ddb03d82a0) | Mar 24, 2021 |
| ASRock        | QC5000-ITX/WiFi             | Desktop     | [7940fddf34](https://linux-hardware.org/?probe=7940fddf34) | Mar 24, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [59fb434d97](https://linux-hardware.org/?probe=59fb434d97) | Mar 21, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [aab4f11f05](https://linux-hardware.org/?probe=aab4f11f05) | Mar 21, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| HP            | 1497                        | Desktop     | [8a761041cb](https://linux-hardware.org/?probe=8a761041cb) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9d190d0899](https://linux-hardware.org/?probe=9d190d0899) | Mar 17, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [5fe5bdf357](https://linux-hardware.org/?probe=5fe5bdf357) | Mar 16, 2021 |
| MSI           | 880GM-E41                   | Desktop     | [4f6b84a8c0](https://linux-hardware.org/?probe=4f6b84a8c0) | Mar 15, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ed4ddd6238](https://linux-hardware.org/?probe=ed4ddd6238) | Mar 15, 2021 |
| MSI           | H61M-P20                    | Desktop     | [6c184c27d1](https://linux-hardware.org/?probe=6c184c27d1) | Mar 15, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [9aea38338d](https://linux-hardware.org/?probe=9aea38338d) | Mar 15, 2021 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [7e3e20bba4](https://linux-hardware.org/?probe=7e3e20bba4) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [3163da0fc6](https://linux-hardware.org/?probe=3163da0fc6) | Mar 12, 2021 |
| Intel         | 945                         | Desktop     | [87a90ecd5e](https://linux-hardware.org/?probe=87a90ecd5e) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Acer          | Aspire 5742G                | Notebook    | [659f9d690c](https://linux-hardware.org/?probe=659f9d690c) | Mar 10, 2021 |
| Intel         | 945                         | Desktop     | [4644c2d3dd](https://linux-hardware.org/?probe=4644c2d3dd) | Mar 10, 2021 |
| Intel         | 945                         | Desktop     | [bdcdd4c2c9](https://linux-hardware.org/?probe=bdcdd4c2c9) | Mar 09, 2021 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [54b1a7993c](https://linux-hardware.org/?probe=54b1a7993c) | Mar 09, 2021 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [20dd877fba](https://linux-hardware.org/?probe=20dd877fba) | Mar 09, 2021 |
| Dell          | Latitude E6320              | Notebook    | [a69653a323](https://linux-hardware.org/?probe=a69653a323) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| MSI           | MS-7369                     | Desktop     | [6b76ab1b0c](https://linux-hardware.org/?probe=6b76ab1b0c) | Mar 06, 2021 |
| MSI           | MS-7369                     | Desktop     | [c26816dad0](https://linux-hardware.org/?probe=c26816dad0) | Mar 06, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7d5313fdad](https://linux-hardware.org/?probe=7d5313fdad) | Mar 06, 2021 |
| Acer          | One S1003                   | Tablet      | [b03462916e](https://linux-hardware.org/?probe=b03462916e) | Mar 06, 2021 |
| Toshiba       | Satellite L20               | Notebook    | [875478a51a](https://linux-hardware.org/?probe=875478a51a) | Mar 06, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [5750984770](https://linux-hardware.org/?probe=5750984770) | Mar 05, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [c79eedd353](https://linux-hardware.org/?probe=c79eedd353) | Mar 04, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [e21aaf16e3](https://linux-hardware.org/?probe=e21aaf16e3) | Mar 03, 2021 |
| Lenovo        | 312A NOK                    | Desktop     | [10e16e0f14](https://linux-hardware.org/?probe=10e16e0f14) | Mar 02, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [a10534e0ba](https://linux-hardware.org/?probe=a10534e0ba) | Mar 02, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [325e488c16](https://linux-hardware.org/?probe=325e488c16) | Feb 28, 2021 |
| Supermicro    | X8SIL                       | Desktop     | [58108e8eb1](https://linux-hardware.org/?probe=58108e8eb1) | Feb 28, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a94321f4aa](https://linux-hardware.org/?probe=a94321f4aa) | Feb 27, 2021 |
| MSI           | 0A90                        | Desktop     | [36e73df6d5](https://linux-hardware.org/?probe=36e73df6d5) | Feb 26, 2021 |
| Intel         | 945                         | Desktop     | [de9b7b0ef0](https://linux-hardware.org/?probe=de9b7b0ef0) | Feb 25, 2021 |
| Intel         | 945                         | Desktop     | [d0b22beef3](https://linux-hardware.org/?probe=d0b22beef3) | Feb 25, 2021 |
| ASRock        | M3N78D                      | Desktop     | [c40a449681](https://linux-hardware.org/?probe=c40a449681) | Feb 23, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [888ff52208](https://linux-hardware.org/?probe=888ff52208) | Feb 21, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [4611155200](https://linux-hardware.org/?probe=4611155200) | Feb 20, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [12ef122267](https://linux-hardware.org/?probe=12ef122267) | Feb 19, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [d77d8a8749](https://linux-hardware.org/?probe=d77d8a8749) | Feb 18, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d2b9f26b16](https://linux-hardware.org/?probe=d2b9f26b16) | Feb 15, 2021 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [dc49777ce8](https://linux-hardware.org/?probe=dc49777ce8) | Feb 14, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [d282a8d18c](https://linux-hardware.org/?probe=d282a8d18c) | Feb 14, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5843b21ecd](https://linux-hardware.org/?probe=5843b21ecd) | Feb 14, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2dcb1a408a](https://linux-hardware.org/?probe=2dcb1a408a) | Feb 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [1d63d4f78d](https://linux-hardware.org/?probe=1d63d4f78d) | Feb 10, 2021 |
| MSI           | 0A90                        | Desktop     | [bb71cea5b4](https://linux-hardware.org/?probe=bb71cea5b4) | Feb 09, 2021 |
| Dell          | Latitude E5470              | Notebook    | [ac140ada48](https://linux-hardware.org/?probe=ac140ada48) | Feb 09, 2021 |
| ASUSTek       | M4N78-AM                    | Desktop     | [4c528f55f3](https://linux-hardware.org/?probe=4c528f55f3) | Feb 07, 2021 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [e80a31db39](https://linux-hardware.org/?probe=e80a31db39) | Feb 03, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [5aca50689e](https://linux-hardware.org/?probe=5aca50689e) | Jan 29, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [e67f35f505](https://linux-hardware.org/?probe=e67f35f505) | Jan 28, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [d3ee3b13ef](https://linux-hardware.org/?probe=d3ee3b13ef) | Jan 28, 2021 |
| Dell          | Latitude E5470              | Notebook    | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| Dell          | Latitude E6430              | Notebook    | [b7f8906f0f](https://linux-hardware.org/?probe=b7f8906f0f) | Jan 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [68fdde328b](https://linux-hardware.org/?probe=68fdde328b) | Jan 27, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| Acer          | Aspire 5736Z                | Notebook    | [6bb8df4de2](https://linux-hardware.org/?probe=6bb8df4de2) | Jan 21, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [ab2decc440](https://linux-hardware.org/?probe=ab2decc440) | Jan 12, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c7807c2ac4](https://linux-hardware.org/?probe=c7807c2ac4) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | Notebook    | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7e0f5ef3ce](https://linux-hardware.org/?probe=7e0f5ef3ce) | Jan 04, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| ASRock        | B450M Steel Legend          | Desktop     | [e1424f6de3](https://linux-hardware.org/?probe=e1424f6de3) | Dec 31, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [e3a87784d6](https://linux-hardware.org/?probe=e3a87784d6) | Dec 29, 2020 |
| Biostar       | A320MH                      | Desktop     | [42b6908594](https://linux-hardware.org/?probe=42b6908594) | Dec 29, 2020 |
| Gigabyte      | Z87-HD3                     | Desktop     | [2f46386da3](https://linux-hardware.org/?probe=2f46386da3) | Dec 27, 2020 |
| Biostar       | NF520D3                     | Desktop     | [12a6b07515](https://linux-hardware.org/?probe=12a6b07515) | Dec 27, 2020 |
| Biostar       | NF520D3                     | Desktop     | [c78780427f](https://linux-hardware.org/?probe=c78780427f) | Dec 27, 2020 |
| Biostar       | NF520D3                     | Desktop     | [60a378a184](https://linux-hardware.org/?probe=60a378a184) | Dec 27, 2020 |
| ASUSTek       | M4N78-AM                    | Desktop     | [9973c728ba](https://linux-hardware.org/?probe=9973c728ba) | Dec 26, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e62cf453c7](https://linux-hardware.org/?probe=e62cf453c7) | Dec 26, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e339224671](https://linux-hardware.org/?probe=e339224671) | Dec 26, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a5084b2336](https://linux-hardware.org/?probe=a5084b2336) | Dec 26, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [ce08535027](https://linux-hardware.org/?probe=ce08535027) | Dec 25, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [a026c30d04](https://linux-hardware.org/?probe=a026c30d04) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [87ecbeb3f9](https://linux-hardware.org/?probe=87ecbeb3f9) | Dec 22, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [7bbfaa08a2](https://linux-hardware.org/?probe=7bbfaa08a2) | Dec 19, 2020 |
| ASUSTek       | H110M-R                     | Desktop     | [3d6c26aa3c](https://linux-hardware.org/?probe=3d6c26aa3c) | Dec 18, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [a3f26b77de](https://linux-hardware.org/?probe=a3f26b77de) | Dec 17, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [3d19374493](https://linux-hardware.org/?probe=3d19374493) | Dec 17, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [630a5fce15](https://linux-hardware.org/?probe=630a5fce15) | Dec 11, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [9c6b3be687](https://linux-hardware.org/?probe=9c6b3be687) | Dec 10, 2020 |
| HP            | 1497                        | Desktop     | [b93a804d52](https://linux-hardware.org/?probe=b93a804d52) | Dec 09, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [5fe883b8c8](https://linux-hardware.org/?probe=5fe883b8c8) | Dec 06, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [a4512466f1](https://linux-hardware.org/?probe=a4512466f1) | Dec 06, 2020 |
| Acer          | Aspire A717-71G             | Notebook    | [f355a859fe](https://linux-hardware.org/?probe=f355a859fe) | Dec 05, 2020 |
| Acer          | Aspire A717-71G             | Notebook    | [e0144299e5](https://linux-hardware.org/?probe=e0144299e5) | Dec 05, 2020 |
| Gigabyte      | E3000N                      | Desktop     | [2861121763](https://linux-hardware.org/?probe=2861121763) | Dec 03, 2020 |
| HP            | 1495                        | Desktop     | [260725df5b](https://linux-hardware.org/?probe=260725df5b) | Dec 02, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [4d6f15896a](https://linux-hardware.org/?probe=4d6f15896a) | Dec 01, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [cea1efd2f4](https://linux-hardware.org/?probe=cea1efd2f4) | Dec 01, 2020 |
| MSI           | H110M ECO                   | Desktop     | [d848b46f0e](https://linux-hardware.org/?probe=d848b46f0e) | Nov 29, 2020 |
| MSI           | H110M ECO                   | Desktop     | [3789cd7ccf](https://linux-hardware.org/?probe=3789cd7ccf) | Nov 29, 2020 |
| MSI           | 880GMS-E35                  | Desktop     | [821743caaa](https://linux-hardware.org/?probe=821743caaa) | Nov 29, 2020 |
| MSI           | A320M-A PRO                 | Desktop     | [ce774acedc](https://linux-hardware.org/?probe=ce774acedc) | Nov 27, 2020 |
| Acer          | Aspire ES1-533              | Notebook    | [e20dc3c4e4](https://linux-hardware.org/?probe=e20dc3c4e4) | Nov 26, 2020 |
| Acer          | Aspire ES1-533              | Notebook    | [1ff481eb22](https://linux-hardware.org/?probe=1ff481eb22) | Nov 26, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [d09ca3fed0](https://linux-hardware.org/?probe=d09ca3fed0) | Nov 24, 2020 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [c25d3746ee](https://linux-hardware.org/?probe=c25d3746ee) | Nov 24, 2020 |
| Dell          | 0F6X5P A00                  | Desktop     | [458d498ed4](https://linux-hardware.org/?probe=458d498ed4) | Nov 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [b59cef94de](https://linux-hardware.org/?probe=b59cef94de) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [cb540754ed](https://linux-hardware.org/?probe=cb540754ed) | Nov 22, 2020 |
| MSI           | CR610                       | Notebook    | [8e7bf69342](https://linux-hardware.org/?probe=8e7bf69342) | Nov 22, 2020 |
| MSI           | CR610                       | Notebook    | [ba50d62533](https://linux-hardware.org/?probe=ba50d62533) | Nov 22, 2020 |
| Dell          | Inspiron 3541               | Notebook    | [f10a3f7947](https://linux-hardware.org/?probe=f10a3f7947) | Nov 21, 2020 |
| Dell          | Inspiron 3541               | Notebook    | [28a2250b7c](https://linux-hardware.org/?probe=28a2250b7c) | Nov 21, 2020 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| ASUSTek       | H81M-R                      | Desktop     | [10a0831d44](https://linux-hardware.org/?probe=10a0831d44) | Nov 19, 2020 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [aa224b81ef](https://linux-hardware.org/?probe=aa224b81ef) | Nov 18, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [546d681a51](https://linux-hardware.org/?probe=546d681a51) | Nov 18, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [fb7486ffb1](https://linux-hardware.org/?probe=fb7486ffb1) | Nov 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| Unknown       | MCP61                       | Desktop     | [c4aa33a4dc](https://linux-hardware.org/?probe=c4aa33a4dc) | Nov 16, 2020 |
| ASUSTek       | ROG STRIX B360-G GAMING     | Desktop     | [dc19b696c9](https://linux-hardware.org/?probe=dc19b696c9) | Nov 15, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c15d88af85](https://linux-hardware.org/?probe=c15d88af85) | Nov 12, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [c68070f9b3](https://linux-hardware.org/?probe=c68070f9b3) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [99e25d58ad](https://linux-hardware.org/?probe=99e25d58ad) | Nov 10, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9555e785bb](https://linux-hardware.org/?probe=9555e785bb) | Nov 09, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [0de6c928a4](https://linux-hardware.org/?probe=0de6c928a4) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | Notebook    | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| ASUSTek       | A55BM-K                     | Desktop     | [bff939ac49](https://linux-hardware.org/?probe=bff939ac49) | Nov 09, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [579d5eed69](https://linux-hardware.org/?probe=579d5eed69) | Nov 07, 2020 |
| Dell          | Inspiron 1720               | Notebook    | [d2018981ad](https://linux-hardware.org/?probe=d2018981ad) | Nov 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [c6872a9a60](https://linux-hardware.org/?probe=c6872a9a60) | Nov 03, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| MSI           | H110M ECO                   | Desktop     | [bc31d5e177](https://linux-hardware.org/?probe=bc31d5e177) | Nov 01, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c29ca1b5a](https://linux-hardware.org/?probe=4c29ca1b5a) | Oct 31, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| Gigabyte      | 945PL-S3P                   | Desktop     | [b72f72f621](https://linux-hardware.org/?probe=b72f72f621) | Oct 26, 2020 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [ba9fec911f](https://linux-hardware.org/?probe=ba9fec911f) | Oct 20, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [a3067761af](https://linux-hardware.org/?probe=a3067761af) | Oct 18, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [baf94800b6](https://linux-hardware.org/?probe=baf94800b6) | Oct 18, 2020 |
| Dell          | 0GM819                      | Desktop     | [e0cbe10449](https://linux-hardware.org/?probe=e0cbe10449) | Oct 17, 2020 |
| Lenovo        | 3000 N200 0769BNG           | Notebook    | [233a47535c](https://linux-hardware.org/?probe=233a47535c) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [9356879a60](https://linux-hardware.org/?probe=9356879a60) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ccef20bb6](https://linux-hardware.org/?probe=4ccef20bb6) | Oct 13, 2020 |
| Lenovo        | 3000 N200 0769BNG           | Notebook    | [8ea03b6d29](https://linux-hardware.org/?probe=8ea03b6d29) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [43c0586dbe](https://linux-hardware.org/?probe=43c0586dbe) | Oct 12, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [00686fcd7b](https://linux-hardware.org/?probe=00686fcd7b) | Oct 12, 2020 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [a5f35bd977](https://linux-hardware.org/?probe=a5f35bd977) | Oct 12, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [815d325e62](https://linux-hardware.org/?probe=815d325e62) | Oct 10, 2020 |
| Dell          | Latitude E5470              | Notebook    | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ca6c1b562d](https://linux-hardware.org/?probe=ca6c1b562d) | Oct 05, 2020 |
| Acer          | Aspire A515-55              | Notebook    | [d88d774f7f](https://linux-hardware.org/?probe=d88d774f7f) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | Notebook    | [c25c3ef2d8](https://linux-hardware.org/?probe=c25c3ef2d8) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | Notebook    | [e3d174f961](https://linux-hardware.org/?probe=e3d174f961) | Oct 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [cb2c394f1a](https://linux-hardware.org/?probe=cb2c394f1a) | Oct 02, 2020 |
| MSI           | H87-G41 PC Mate             | Desktop     | [ee0ab6bf04](https://linux-hardware.org/?probe=ee0ab6bf04) | Oct 02, 2020 |
| Biostar       | A320MH                      | Desktop     | [ee41403938](https://linux-hardware.org/?probe=ee41403938) | Oct 02, 2020 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [3e7beef386](https://linux-hardware.org/?probe=3e7beef386) | Sep 30, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [61dcf65bfa](https://linux-hardware.org/?probe=61dcf65bfa) | Sep 30, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [d73874f616](https://linux-hardware.org/?probe=d73874f616) | Sep 29, 2020 |
| Gigabyte      | G31M-S2C                    | Desktop     | [d662ed85f8](https://linux-hardware.org/?probe=d662ed85f8) | Sep 29, 2020 |
| HP            | Notebook                    | Notebook    | [9fcfc67d9c](https://linux-hardware.org/?probe=9fcfc67d9c) | Sep 29, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [1734ca75eb](https://linux-hardware.org/?probe=1734ca75eb) | Sep 29, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0KK0... | Notebook    | [d231920967](https://linux-hardware.org/?probe=d231920967) | Sep 28, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b886a607be](https://linux-hardware.org/?probe=b886a607be) | Sep 28, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [e4e1a6fb02](https://linux-hardware.org/?probe=e4e1a6fb02) | Sep 28, 2020 |
| HP            | 355 G2                      | Notebook    | [07981744ab](https://linux-hardware.org/?probe=07981744ab) | Sep 27, 2020 |
| HP            | 355 G2                      | Notebook    | [08e4ab3c53](https://linux-hardware.org/?probe=08e4ab3c53) | Sep 26, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [a34c376304](https://linux-hardware.org/?probe=a34c376304) | Sep 18, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [20c5e9395d](https://linux-hardware.org/?probe=20c5e9395d) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | Notebook    | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| HP            | Laptop 17-by2xxx            | Notebook    | [d3fcaecf43](https://linux-hardware.org/?probe=d3fcaecf43) | Sep 12, 2020 |
| MSI           | 760GM-P21                   | Desktop     | [b23305b1f3](https://linux-hardware.org/?probe=b23305b1f3) | Sep 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [eea494974a](https://linux-hardware.org/?probe=eea494974a) | Sep 11, 2020 |
| ASUSTek       | H97-PLUS                    | Desktop     | [a5726bfa80](https://linux-hardware.org/?probe=a5726bfa80) | Sep 10, 2020 |
| Gigabyte      | F2A58M-DS2H                 | Desktop     | [41b9e1526c](https://linux-hardware.org/?probe=41b9e1526c) | Sep 10, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [44041b729e](https://linux-hardware.org/?probe=44041b729e) | Sep 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [00956078a0](https://linux-hardware.org/?probe=00956078a0) | Sep 03, 2020 |
| Acer          | AOA150                      | Notebook    | [d7397a31d7](https://linux-hardware.org/?probe=d7397a31d7) | Aug 31, 2020 |
| HP            | 2AF3                        | Desktop     | [75f15238ce](https://linux-hardware.org/?probe=75f15238ce) | Aug 31, 2020 |
| ASRock        | X570 Pro4                   | Desktop     | [0d7778cc62](https://linux-hardware.org/?probe=0d7778cc62) | Aug 29, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [cb65aa7264](https://linux-hardware.org/?probe=cb65aa7264) | Aug 25, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [6bb8820098](https://linux-hardware.org/?probe=6bb8820098) | Aug 22, 2020 |
| Dell          | Inspiron 3593               | Notebook    | [2c97a34461](https://linux-hardware.org/?probe=2c97a34461) | Aug 20, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | Notebook    | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | Notebook    | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| Lenovo        | ThinkPad T480 20L6S43212    | Notebook    | [e408e4045b](https://linux-hardware.org/?probe=e408e4045b) | Aug 16, 2020 |
| HP            | 3398                        | Desktop     | [8590b22254](https://linux-hardware.org/?probe=8590b22254) | Aug 15, 2020 |
| Dell          | 0DR845                      | Desktop     | [a4ddbdc998](https://linux-hardware.org/?probe=a4ddbdc998) | Aug 11, 2020 |
| MSI           | GF615M-P33                  | Desktop     | [b5c3471e8b](https://linux-hardware.org/?probe=b5c3471e8b) | Aug 09, 2020 |
| MSI           | GF615M-P33                  | Desktop     | [50b0587266](https://linux-hardware.org/?probe=50b0587266) | Aug 09, 2020 |
| Dell          | Inspiron 5577               | Notebook    | [f10ef91563](https://linux-hardware.org/?probe=f10ef91563) | Aug 06, 2020 |
| HP            | 3032h                       | Desktop     | [9abca57bf3](https://linux-hardware.org/?probe=9abca57bf3) | Aug 06, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [801277e6be](https://linux-hardware.org/?probe=801277e6be) | Aug 05, 2020 |
| MSI           | CR500                       | Notebook    | [a347574891](https://linux-hardware.org/?probe=a347574891) | Aug 03, 2020 |
| MSI           | CR500                       | Notebook    | [21b1264f8c](https://linux-hardware.org/?probe=21b1264f8c) | Aug 03, 2020 |
| ECS           | H61H2-M12                   | Desktop     | [2ac9b3f866](https://linux-hardware.org/?probe=2ac9b3f866) | Aug 02, 2020 |
| ASUSTek       | H110M-R                     | Desktop     | [09dac438f3](https://linux-hardware.org/?probe=09dac438f3) | Jul 31, 2020 |
| ASUSTek       | A58M-E                      | Desktop     | [6cb4e9e3e5](https://linux-hardware.org/?probe=6cb4e9e3e5) | Jul 30, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [a2dd413553](https://linux-hardware.org/?probe=a2dd413553) | Jul 26, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [e1073052d4](https://linux-hardware.org/?probe=e1073052d4) | Jul 26, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [200bdd5138](https://linux-hardware.org/?probe=200bdd5138) | Jul 25, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [8db5efa1fc](https://linux-hardware.org/?probe=8db5efa1fc) | Jul 22, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [4f0031f39f](https://linux-hardware.org/?probe=4f0031f39f) | Jul 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [9bdd60ecdf](https://linux-hardware.org/?probe=9bdd60ecdf) | Jul 19, 2020 |
| Gigabyte      | H61M-S2P                    | Desktop     | [a30442ec07](https://linux-hardware.org/?probe=a30442ec07) | Jul 19, 2020 |
| Gigabyte      | H61M-S2P                    | Desktop     | [57b85cdafa](https://linux-hardware.org/?probe=57b85cdafa) | Jul 19, 2020 |
| MSI           | GF615M-P33 V2               | Desktop     | [64d092bac7](https://linux-hardware.org/?probe=64d092bac7) | Jul 18, 2020 |
| MSI           | GF615M-P33 V2               | Desktop     | [ca930a9e05](https://linux-hardware.org/?probe=ca930a9e05) | Jul 17, 2020 |
| ASUSTek       | H110M-R                     | Desktop     | [26e1de29bc](https://linux-hardware.org/?probe=26e1de29bc) | Jul 14, 2020 |
| HP            | 1497                        | Desktop     | [c26aebcc5f](https://linux-hardware.org/?probe=c26aebcc5f) | Jul 13, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [b5aacd7b39](https://linux-hardware.org/?probe=b5aacd7b39) | Jul 12, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dbc59ac760](https://linux-hardware.org/?probe=dbc59ac760) | Jul 12, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [d40a7e2ced](https://linux-hardware.org/?probe=d40a7e2ced) | Jul 11, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [88afcfbe5b](https://linux-hardware.org/?probe=88afcfbe5b) | Jul 11, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [085d13e046](https://linux-hardware.org/?probe=085d13e046) | Jul 11, 2020 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [6a86c949a2](https://linux-hardware.org/?probe=6a86c949a2) | Jul 10, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [3ab4bed99e](https://linux-hardware.org/?probe=3ab4bed99e) | Jul 05, 2020 |
| Acer          | Aspire E1-531               | Notebook    | [7baad79bd7](https://linux-hardware.org/?probe=7baad79bd7) | Jul 04, 2020 |
| HP            | 18E7                        | Desktop     | [d277840c01](https://linux-hardware.org/?probe=d277840c01) | Jul 03, 2020 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [16211b52a1](https://linux-hardware.org/?probe=16211b52a1) | Jun 25, 2020 |
| Gigabyte      | F2A58M-DS2H                 | Desktop     | [3ed1463dd4](https://linux-hardware.org/?probe=3ed1463dd4) | Jun 17, 2020 |
| Pegatron      | 2AB6                        | Desktop     | [f886c11963](https://linux-hardware.org/?probe=f886c11963) | Jun 12, 2020 |
| Sony          | VPCZ21X9E                   | Notebook    | [72e4be4ea5](https://linux-hardware.org/?probe=72e4be4ea5) | Jun 12, 2020 |
| Sony          | VPCZ21X9E                   | Notebook    | [26affa7385](https://linux-hardware.org/?probe=26affa7385) | Jun 12, 2020 |
| Pegatron      | 2AB6                        | Desktop     | [c9954b4a26](https://linux-hardware.org/?probe=c9954b4a26) | Jun 11, 2020 |
| ASUSTek       | H110M-R                     | Desktop     | [c201f6d857](https://linux-hardware.org/?probe=c201f6d857) | Jun 11, 2020 |
| MSI           | G41M-P28                    | Desktop     | [b0ce30ab32](https://linux-hardware.org/?probe=b0ce30ab32) | Jun 11, 2020 |
| ASUSTek       | A58M-K                      | Desktop     | [117bf5197f](https://linux-hardware.org/?probe=117bf5197f) | Jun 10, 2020 |
| ASUSTek       | A58M-K                      | Desktop     | [f8f58eaad6](https://linux-hardware.org/?probe=f8f58eaad6) | Jun 09, 2020 |
| ASUSTek       | P5Q-VM DO                   | Desktop     | [346628ed49](https://linux-hardware.org/?probe=346628ed49) | Jun 09, 2020 |
| MSI           | G31TM-P21                   | Desktop     | [a63d6c107a](https://linux-hardware.org/?probe=a63d6c107a) | Jun 08, 2020 |
| MSI           | MS-7519                     | Desktop     | [27185a4dad](https://linux-hardware.org/?probe=27185a4dad) | Jun 05, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [099f5faf14](https://linux-hardware.org/?probe=099f5faf14) | Jun 02, 2020 |
| ASUSTek       | N550JX                      | Notebook    | [99693da42c](https://linux-hardware.org/?probe=99693da42c) | May 31, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [3eee5b1f3d](https://linux-hardware.org/?probe=3eee5b1f3d) | May 31, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1a72632c64](https://linux-hardware.org/?probe=1a72632c64) | May 27, 2020 |
| MSI           | B75MA-E33                   | Desktop     | [e7156806db](https://linux-hardware.org/?probe=e7156806db) | May 25, 2020 |
| MSI           | B75MA-E33                   | Desktop     | [508ff9a8bd](https://linux-hardware.org/?probe=508ff9a8bd) | May 25, 2020 |
| ASUSTek       | P5N73-AM                    | Desktop     | [3258ee8b5d](https://linux-hardware.org/?probe=3258ee8b5d) | May 23, 2020 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [9799c4742b](https://linux-hardware.org/?probe=9799c4742b) | May 23, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [c4087d6c6a](https://linux-hardware.org/?probe=c4087d6c6a) | May 21, 2020 |
| ASUSTek       | P5QL PRO                    | Desktop     | [c8e5e768fd](https://linux-hardware.org/?probe=c8e5e768fd) | May 21, 2020 |
| ASUSTek       | K50AB                       | Notebook    | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Dell          | Inspiron N5010              | Notebook    | [f1e4f13c21](https://linux-hardware.org/?probe=f1e4f13c21) | May 18, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [a608769eb0](https://linux-hardware.org/?probe=a608769eb0) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | Notebook    | [92e676e189](https://linux-hardware.org/?probe=92e676e189) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | Notebook    | [b7fd9a70e0](https://linux-hardware.org/?probe=b7fd9a70e0) | May 15, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [59982dc231](https://linux-hardware.org/?probe=59982dc231) | May 14, 2020 |
| ASUSTek       | G551JK                      | Notebook    | [1d29493d79](https://linux-hardware.org/?probe=1d29493d79) | May 14, 2020 |
| ASUSTek       | G551JK                      | Notebook    | [2aa55f08d0](https://linux-hardware.org/?probe=2aa55f08d0) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [03ba757adf](https://linux-hardware.org/?probe=03ba757adf) | May 13, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [dadd9d2790](https://linux-hardware.org/?probe=dadd9d2790) | May 12, 2020 |
| Gigabyte      | P31-DS3L                    | Desktop     | [507a4c1c74](https://linux-hardware.org/?probe=507a4c1c74) | May 12, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [3474070eb8](https://linux-hardware.org/?probe=3474070eb8) | May 10, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4ac3289ec9](https://linux-hardware.org/?probe=4ac3289ec9) | May 09, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [b015c22cfb](https://linux-hardware.org/?probe=b015c22cfb) | May 09, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [507b301572](https://linux-hardware.org/?probe=507b301572) | May 09, 2020 |
| ASUSTek       | K54C                        | Notebook    | [3188c4843a](https://linux-hardware.org/?probe=3188c4843a) | May 08, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [099e174bf4](https://linux-hardware.org/?probe=099e174bf4) | May 07, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [9de43ba1db](https://linux-hardware.org/?probe=9de43ba1db) | May 07, 2020 |
| HP            | 3398                        | Desktop     | [86c6f07f18](https://linux-hardware.org/?probe=86c6f07f18) | May 06, 2020 |
| Lenovo        | ThinkPad L470 20J5S4RS00    | Notebook    | [b646e36068](https://linux-hardware.org/?probe=b646e36068) | May 04, 2020 |
| Gigabyte      | P31-DS3L                    | Desktop     | [63fea1c9cd](https://linux-hardware.org/?probe=63fea1c9cd) | May 03, 2020 |
| ASUSTek       | A58M-K                      | Desktop     | [b40e7fdbef](https://linux-hardware.org/?probe=b40e7fdbef) | May 03, 2020 |
| Gigabyte      | P31-ES3G                    | Desktop     | [33279e03d0](https://linux-hardware.org/?probe=33279e03d0) | Apr 30, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [4cae21a722](https://linux-hardware.org/?probe=4cae21a722) | Apr 22, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [a26c6f5812](https://linux-hardware.org/?probe=a26c6f5812) | Apr 21, 2020 |
| ASUSTek       | P5Q-VM DO                   | Desktop     | [fc60d56b77](https://linux-hardware.org/?probe=fc60d56b77) | Apr 19, 2020 |
| ASUSTek       | A58M-K                      | Desktop     | [c86917f5cc](https://linux-hardware.org/?probe=c86917f5cc) | Apr 17, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [01f3f0f185](https://linux-hardware.org/?probe=01f3f0f185) | Apr 14, 2020 |
| MSI           | FM2-A55M-E33                | Desktop     | [2e15f64ca6](https://linux-hardware.org/?probe=2e15f64ca6) | Apr 14, 2020 |
| Lenovo        | ThinkPad E560 20EV003EMS    | Notebook    | [0b978ac786](https://linux-hardware.org/?probe=0b978ac786) | Apr 14, 2020 |
| HP            | ZBook 15 G3                 | Notebook    | [16ee557e51](https://linux-hardware.org/?probe=16ee557e51) | Apr 12, 2020 |
| HP            | Mini 110-3100               | Notebook    | [a32c0db8bb](https://linux-hardware.org/?probe=a32c0db8bb) | Apr 11, 2020 |
| Pegatron      | 2AB5                        | Desktop     | [b041763dea](https://linux-hardware.org/?probe=b041763dea) | Apr 11, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1418f2501e](https://linux-hardware.org/?probe=1418f2501e) | Apr 10, 2020 |
| Biostar       | TB250-BTC                   | Desktop     | [fd92f418b8](https://linux-hardware.org/?probe=fd92f418b8) | Apr 08, 2020 |
| HP            | 18E7                        | Desktop     | [4d9f332c70](https://linux-hardware.org/?probe=4d9f332c70) | Apr 08, 2020 |
| HP            | 18E7                        | Desktop     | [6f953f68bd](https://linux-hardware.org/?probe=6f953f68bd) | Apr 08, 2020 |
| Gigabyte      | P31-DS3L                    | Desktop     | [b713dcca4f](https://linux-hardware.org/?probe=b713dcca4f) | Apr 08, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a34d2ffc57](https://linux-hardware.org/?probe=a34d2ffc57) | Apr 08, 2020 |
| ASUSTek       | A58M-K                      | Desktop     | [2d7bcf65f9](https://linux-hardware.org/?probe=2d7bcf65f9) | Apr 07, 2020 |
| ASUSTek       | A58M-K                      | Desktop     | [7db11256da](https://linux-hardware.org/?probe=7db11256da) | Apr 05, 2020 |
| ASUSTek       | P5Q-VM DO                   | Desktop     | [f1dcc22829](https://linux-hardware.org/?probe=f1dcc22829) | Apr 05, 2020 |
| Acer          | Aspire 7520G                | Notebook    | [d5bc992097](https://linux-hardware.org/?probe=d5bc992097) | Apr 04, 2020 |
| Toshiba       | TECRA Z50-A                 | Notebook    | [889a5aa1a6](https://linux-hardware.org/?probe=889a5aa1a6) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | Desktop     | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [cb84e8c9af](https://linux-hardware.org/?probe=cb84e8c9af) | Mar 23, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8670fa919e](https://linux-hardware.org/?probe=8670fa919e) | Mar 23, 2020 |
| ASUSTek       | X541NC                      | Notebook    | [63b197a2c0](https://linux-hardware.org/?probe=63b197a2c0) | Mar 21, 2020 |
| Fujitsu Si... | AMILO Li3710                | Notebook    | [11ebf93798](https://linux-hardware.org/?probe=11ebf93798) | Mar 18, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [334884c294](https://linux-hardware.org/?probe=334884c294) | Mar 10, 2020 |
| HP            | 250 G1                      | Notebook    | [7a7e2dfcee](https://linux-hardware.org/?probe=7a7e2dfcee) | Mar 10, 2020 |
| HP            | 250 G4                      | Notebook    | [d8b2caab0f](https://linux-hardware.org/?probe=d8b2caab0f) | Mar 08, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [5870ecc433](https://linux-hardware.org/?probe=5870ecc433) | Mar 08, 2020 |
| Acer          | Aspire E3-112               | Notebook    | [62041aa7fa](https://linux-hardware.org/?probe=62041aa7fa) | Mar 08, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [d51cbbf880](https://linux-hardware.org/?probe=d51cbbf880) | Mar 07, 2020 |
| Lenovo        | ThinkPad T500 2056W2J       | Notebook    | [1923e28174](https://linux-hardware.org/?probe=1923e28174) | Mar 05, 2020 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [a82780cd8c](https://linux-hardware.org/?probe=a82780cd8c) | Mar 04, 2020 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [68b9561775](https://linux-hardware.org/?probe=68b9561775) | Mar 03, 2020 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [6140664ce7](https://linux-hardware.org/?probe=6140664ce7) | Feb 26, 2020 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [d79a2cce0d](https://linux-hardware.org/?probe=d79a2cce0d) | Feb 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bda2f29230](https://linux-hardware.org/?probe=bda2f29230) | Feb 24, 2020 |
| ASUSTek       | H110M-R                     | Desktop     | [2d9562d0e1](https://linux-hardware.org/?probe=2d9562d0e1) | Feb 24, 2020 |
| ASUSTek       | P5Q                         | Desktop     | [f22209135d](https://linux-hardware.org/?probe=f22209135d) | Feb 22, 2020 |
| ASUSTek       | P5Q                         | Desktop     | [6d0cd87c90](https://linux-hardware.org/?probe=6d0cd87c90) | Feb 22, 2020 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [5d93dd0911](https://linux-hardware.org/?probe=5d93dd0911) | Feb 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [eb55029938](https://linux-hardware.org/?probe=eb55029938) | Feb 18, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [530fb26de2](https://linux-hardware.org/?probe=530fb26de2) | Feb 16, 2020 |
| Biostar       | TB85                        | Desktop     | [ee5bd25897](https://linux-hardware.org/?probe=ee5bd25897) | Feb 13, 2020 |
| MSI           | MS-7309                     | Desktop     | [3a6ec44dd2](https://linux-hardware.org/?probe=3a6ec44dd2) | Feb 11, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4d942fa22c](https://linux-hardware.org/?probe=4d942fa22c) | Feb 10, 2020 |
| ASUSTek       | X541UVK                     | Notebook    | [9e44db3513](https://linux-hardware.org/?probe=9e44db3513) | Feb 06, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [91bdd7eccf](https://linux-hardware.org/?probe=91bdd7eccf) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a4a64dfa74](https://linux-hardware.org/?probe=a4a64dfa74) | Feb 01, 2020 |
| Acer          | Aspire E1-530               | Notebook    | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Acer          | Swift SF314-56              | Notebook    | [303332d310](https://linux-hardware.org/?probe=303332d310) | Jan 29, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [06c487df1d](https://linux-hardware.org/?probe=06c487df1d) | Jan 28, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [034e07f7f9](https://linux-hardware.org/?probe=034e07f7f9) | Jan 28, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [b482e7ef86](https://linux-hardware.org/?probe=b482e7ef86) | Jan 25, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [eab9be2c36](https://linux-hardware.org/?probe=eab9be2c36) | Jan 25, 2020 |
| ASUSTek       | F2A55-M LK2 PLUS            | Desktop     | [a292515c70](https://linux-hardware.org/?probe=a292515c70) | Jan 24, 2020 |
| Lenovo        | ThinkPad T520 42406AG       | Notebook    | [7de4fdce8d](https://linux-hardware.org/?probe=7de4fdce8d) | Jan 23, 2020 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [b0d2c5611e](https://linux-hardware.org/?probe=b0d2c5611e) | Jan 22, 2020 |
| HP            | Compaq nc6320 (RU381ES#A... | Notebook    | [d3a7e386ae](https://linux-hardware.org/?probe=d3a7e386ae) | Jan 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [84bf577e7d](https://linux-hardware.org/?probe=84bf577e7d) | Jan 16, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [36dcda44ba](https://linux-hardware.org/?probe=36dcda44ba) | Jan 15, 2020 |
| ASUSTek       | P5B                         | Desktop     | [149a63defe](https://linux-hardware.org/?probe=149a63defe) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [cc4a9ba559](https://linux-hardware.org/?probe=cc4a9ba559) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [72f2c4c12a](https://linux-hardware.org/?probe=72f2c4c12a) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b5d63aec77](https://linux-hardware.org/?probe=b5d63aec77) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d389b1fcb](https://linux-hardware.org/?probe=7d389b1fcb) | Jan 15, 2020 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [afa0b93a9a](https://linux-hardware.org/?probe=afa0b93a9a) | Jan 13, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Serbia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 92        | 11.06%  |
| Ubuntu 18.04                 | 55        | 6.61%   |
| Ubuntu 22.04                 | 46        | 5.53%   |
| OpenMandriva 4.3             | 28        | 3.37%   |
| OpenMandriva 4.2             | 25        | 3%      |
| BlackPanther 18.1            | 18        | 2.16%   |
| Pop!_OS 22.04                | 15        | 1.8%    |
| OpenMandriva 23.01           | 15        | 1.8%    |
| KDE neon 20.04               | 14        | 1.68%   |
| Zorin 15                     | 13        | 1.56%   |
| Arch                         | 13        | 1.56%   |
| ROSA R11                     | 12        | 1.44%   |
| ROSA R10                     | 12        | 1.44%   |
| Arch Rolling                 | 12        | 1.44%   |
| Zorin 16                     | 11        | 1.32%   |
| Ubuntu 19.10                 | 11        | 1.32%   |
| Linux Mint 19.3              | 11        | 1.32%   |
| Ubuntu 21.10                 | 10        | 1.2%    |
| Fedora 38                    | 10        | 1.2%    |
| Linux Mint 20.3              | 9         | 1.08%   |
| Ubuntu 22.10                 | 8         | 0.96%   |
| Ubuntu 21.04                 | 8         | 0.96%   |
| ROSA R11.1                   | 8         | 0.96%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.96%   |
| Linux Mint 21.1              | 8         | 0.96%   |
| Fedora 37                    | 8         | 0.96%   |
| ArcoLinux Rolling            | 8         | 0.96%   |
| Ubuntu 23.04                 | 7         | 0.84%   |
| Ubuntu 18.10                 | 7         | 0.84%   |
| Pop!_OS 20.04                | 7         | 0.84%   |
| Kubuntu 20.04                | 7         | 0.84%   |
| ROSA R9                      | 6         | 0.72%   |
| ROSA 12.2                    | 6         | 0.72%   |
| OpenMandriva 23.03           | 6         | 0.72%   |
| Manjaro                      | 6         | 0.72%   |
| Linux Mint 20.2              | 6         | 0.72%   |
| Linux Mint 20                | 6         | 0.72%   |
| Kubuntu 22.04                | 6         | 0.72%   |
| Fedora 36                    | 6         | 0.72%   |
| Fedora 34                    | 6         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 248       | 32.04%  |
| OpenMandriva  | 80        | 10.34%  |
| Linux Mint    | 51        | 6.59%   |
| ROSA          | 42        | 5.43%   |
| Fedora        | 38        | 4.91%   |
| Endless       | 35        | 4.52%   |
| Pop!_OS       | 33        | 4.26%   |
| Zorin         | 27        | 3.49%   |
| Arch          | 25        | 3.23%   |
| Manjaro       | 20        | 2.58%   |
| Kubuntu       | 20        | 2.58%   |
| BlackPanther  | 20        | 2.58%   |
| KDE neon      | 19        | 2.45%   |
| Debian        | 14        | 1.81%   |
| openSUSE      | 13        | 1.68%   |
| ArcoLinux     | 10        | 1.29%   |
| Kali          | 9         | 1.16%   |
| Xubuntu       | 8         | 1.03%   |
| MX            | 7         | 0.9%    |
| Ubuntu Unity  | 4         | 0.52%   |
| EndeavourOS   | 4         | 0.52%   |
| Elementary    | 4         | 0.52%   |
| Clear Linux   | 4         | 0.52%   |
| Ubuntu MATE   | 3         | 0.39%   |
| Nobara        | 3         | 0.39%   |
| Lubuntu       | 3         | 0.39%   |
| Garuda Linux  | 3         | 0.39%   |
| CentOS        | 3         | 0.39%   |
| Void Linux    | 2         | 0.26%   |
| Ubuntu Budgie | 2         | 0.26%   |
| Slackware     | 2         | 0.26%   |
| NixOS         | 2         | 0.26%   |
| LMDE          | 2         | 0.26%   |
| LinuxFX       | 2         | 0.26%   |
| UbuntuDDE     | 1         | 0.13%   |
| Serbian       | 1         | 0.13%   |
| Peppermint    | 1         | 0.13%   |
| PCLinuxOS     | 1         | 0.13%   |
| Linux Lite    | 1         | 0.13%   |
| LFS           | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 26        | 2.88%   |
| 5.10.14-desktop-1omv4002           | 25        | 2.77%   |
| 5.4.0-42-generic                   | 16        | 1.77%   |
| 6.1.1-desktop-1omv2290             | 15        | 1.66%   |
| 4.18.16-desktop-1bP                | 14        | 1.55%   |
| 5.15.0-56-generic                  | 10        | 1.11%   |
| 5.3.0-40-generic                   | 8         | 0.89%   |
| 4.18.0-15-generic                  | 8         | 0.89%   |
| 5.8.0-14-generic                   | 7         | 0.78%   |
| 5.15.0-53-generic                  | 7         | 0.78%   |
| 5.4.0-58-generic                   | 6         | 0.67%   |
| 5.4.0-48-generic                   | 6         | 0.67%   |
| 5.15.0-48-generic                  | 6         | 0.67%   |
| 5.15.0-46-generic                  | 6         | 0.67%   |
| 5.11.0-35-generic                  | 6         | 0.67%   |
| 5.11.0-27-generic                  | 6         | 0.67%   |
| 4.18.0-17-generic                  | 6         | 0.67%   |
| 6.2.6-desktop-1omv2390             | 5         | 0.55%   |
| 5.4.0-54-generic                   | 5         | 0.55%   |
| 5.4.0-52-generic                   | 5         | 0.55%   |
| 5.4.0-47-generic                   | 5         | 0.55%   |
| 5.4.0-31-generic                   | 5         | 0.55%   |
| 5.4.0-29-generic                   | 5         | 0.55%   |
| 5.3.0-51-generic                   | 5         | 0.55%   |
| 5.15.0-58-generic                  | 5         | 0.55%   |
| 5.15.0-52-generic                  | 5         | 0.55%   |
| 5.13.0-30-generic                  | 5         | 0.55%   |
| 5.13.0-28-generic                  | 5         | 0.55%   |
| 5.11.0-34-generic                  | 5         | 0.55%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 5         | 0.55%   |
| 5.0.0-27-generic                   | 5         | 0.55%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 5         | 0.55%   |
| 6.2.6-76060206-generic             | 4         | 0.44%   |
| 6.2.0-26-generic                   | 4         | 0.44%   |
| 5.6.14-desktop-2bP                 | 4         | 0.44%   |
| 5.4.0-91-generic                   | 4         | 0.44%   |
| 5.4.0-74-generic                   | 4         | 0.44%   |
| 5.4.0-66-generic                   | 4         | 0.44%   |
| 5.4.0-40-generic                   | 4         | 0.44%   |
| 5.4.0-26-generic                   | 4         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 119       | 13.98%  |
| 5.15.0  | 63        | 7.4%    |
| 4.15.0  | 51        | 5.99%   |
| 5.11.0  | 40        | 4.7%    |
| 5.8.0   | 37        | 4.35%   |
| 5.3.0   | 37        | 4.35%   |
| 5.13.0  | 32        | 3.76%   |
| 4.18.0  | 30        | 3.53%   |
| 5.16.7  | 26        | 3.06%   |
| 5.10.14 | 25        | 2.94%   |
| 5.19.0  | 24        | 2.82%   |
| 5.0.0   | 23        | 2.7%    |
| 6.1.1   | 17        | 2%      |
| 4.18.16 | 14        | 1.65%   |
| 6.2.0   | 12        | 1.41%   |
| 5.10.0  | 10        | 1.18%   |
| 6.2.6   | 9         | 1.06%   |
| 6.1.0   | 8         | 0.94%   |
| 4.9.20  | 7         | 0.82%   |
| 5.10.74 | 5         | 0.59%   |
| 4.9.60  | 5         | 0.59%   |
| 5.6.14  | 4         | 0.47%   |
| 4.19.0  | 4         | 0.47%   |
| 6.4.6   | 3         | 0.35%   |
| 6.4.11  | 3         | 0.35%   |
| 6.2.9   | 3         | 0.35%   |
| 6.0.8   | 3         | 0.35%   |
| 6.0.12  | 3         | 0.35%   |
| 5.8.11  | 3         | 0.35%   |
| 5.7.8   | 3         | 0.35%   |
| 5.4.32  | 3         | 0.35%   |
| 5.19.7  | 3         | 0.35%   |
| 5.16.0  | 3         | 0.35%   |
| 5.15.15 | 3         | 0.35%   |
| 5.11.12 | 3         | 0.35%   |
| 4.1.34  | 3         | 0.35%   |
| 6.5.0   | 2         | 0.24%   |
| 6.4.12  | 2         | 0.24%   |
| 6.3.8   | 2         | 0.24%   |
| 6.3.5   | 2         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 135       | 16.09%  |
| 5.15    | 78        | 9.3%    |
| 4.15    | 51        | 6.08%   |
| 5.11    | 50        | 5.96%   |
| 5.10    | 47        | 5.6%    |
| 4.18    | 44        | 5.24%   |
| 5.3     | 43        | 5.13%   |
| 5.8     | 42        | 5.01%   |
| 5.19    | 39        | 4.65%   |
| 6.1     | 38        | 4.53%   |
| 5.13    | 36        | 4.29%   |
| 5.16    | 35        | 4.17%   |
| 6.2     | 29        | 3.46%   |
| 5.0     | 26        | 3.1%    |
| 4.9     | 21        | 2.5%    |
| 6.0     | 19        | 2.26%   |
| 6.3     | 11        | 1.31%   |
| 5.6     | 11        | 1.31%   |
| 6.4     | 10        | 1.19%   |
| 5.9     | 8         | 0.95%   |
| 5.7     | 8         | 0.95%   |
| 5.18    | 7         | 0.83%   |
| 5.17    | 7         | 0.83%   |
| 4.19    | 7         | 0.83%   |
| 5.14    | 6         | 0.72%   |
| 4.1     | 6         | 0.72%   |
| 5.12    | 5         | 0.6%    |
| 5.1     | 4         | 0.48%   |
| 4.4     | 3         | 0.36%   |
| 4.13    | 3         | 0.36%   |
| 6.5     | 2         | 0.24%   |
| 5.5     | 2         | 0.24%   |
| 5.2     | 2         | 0.24%   |
| 4.8     | 1         | 0.12%   |
| 4.17    | 1         | 0.12%   |
| 4.12    | 1         | 0.12%   |
| 4.10    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 720       | 96.51%  |
| i686    | 22        | 2.95%   |
| aarch64 | 3         | 0.4%    |
| armv7l  | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 324       | 41.86%  |
| KDE5            | 174       | 22.48%  |
| Unknown         | 85        | 10.98%  |
| XFCE            | 56        | 7.24%   |
| X-Cinnamon      | 41        | 5.3%    |
| KDE4            | 22        | 2.84%   |
| KDE             | 18        | 2.33%   |
| Cinnamon        | 10        | 1.29%   |
| i3              | 8         | 1.03%   |
| MATE            | 7         | 0.9%    |
| Unity           | 4         | 0.52%   |
| Pantheon        | 4         | 0.52%   |
| LXQt            | 4         | 0.52%   |
| qtile           | 3         | 0.39%   |
| GNOME Flashback | 3         | 0.39%   |
| Deepin          | 3         | 0.39%   |
| LXDE            | 2         | 0.26%   |
| Budgie          | 2         | 0.26%   |
| i3-with-shmlog  | 1         | 0.13%   |
| Hyprland        | 1         | 0.13%   |
| DWM             | 1         | 0.13%   |
| BunsenLabs      | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 612       | 78.76%  |
| Wayland | 111       | 14.29%  |
| Unknown | 42        | 5.41%   |
| Tty     | 12        | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 379       | 48.84%  |
| SDDM    | 149       | 19.2%   |
| GDM3    | 84        | 10.82%  |
| GDM     | 63        | 8.12%   |
| LightDM | 58        | 7.47%   |
| KDM     | 23        | 2.96%   |
| TDM     | 15        | 1.93%   |
| XDM     | 2         | 0.26%   |
| Ly      | 2         | 0.26%   |
| MDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 524       | 67.27%  |
| Unknown     | 130       | 16.69%  |
| sr_RS       | 48        | 6.16%   |
| sr_RS@latin | 20        | 2.57%   |
| en_GB       | 15        | 1.93%   |
| C           | 12        | 1.54%   |
| hu_HU       | 11        | 1.41%   |
| ru_RU       | 5         | 0.64%   |
| de_DE       | 5         | 0.64%   |
| en_AU       | 3         | 0.39%   |
| Default     | 2         | 0.26%   |
| sk_SK       | 1         | 0.13%   |
| nl_NL       | 1         | 0.13%   |
| hr_HR       | 1         | 0.13%   |
| en_IE       | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 405       | 53.22%  |
| EFI  | 356       | 46.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 555       | 71.89%  |
| Overlay | 96        | 12.44%  |
| Btrfs   | 46        | 5.96%   |
| Unknown | 44        | 5.7%    |
| Tmpfs   | 15        | 1.94%   |
| Zfs     | 7         | 0.91%   |
| Xfs     | 6         | 0.78%   |
| Ext2    | 2         | 0.26%   |
| Ext3    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 396       | 51.56%  |
| GPT     | 249       | 32.42%  |
| MBR     | 123       | 16.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 639       | 84.3%   |
| Yes       | 119       | 15.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 526       | 69.21%  |
| Yes       | 234       | 30.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 153       | 20.59%  |
| Lenovo                  | 120       | 16.15%  |
| Gigabyte Technology     | 95        | 12.79%  |
| Hewlett-Packard         | 94        | 12.65%  |
| Dell                    | 65        | 8.75%   |
| MSI                     | 55        | 7.4%    |
| Acer                    | 45        | 6.06%   |
| ASRock                  | 19        | 2.56%   |
| Toshiba                 | 13        | 1.75%   |
| Apple                   | 12        | 1.62%   |
| Biostar                 | 11        | 1.48%   |
| Fujitsu                 | 9         | 1.21%   |
| Fujitsu Siemens         | 6         | 0.81%   |
| Sony                    | 5         | 0.67%   |
| Raspberry Pi Foundation | 4         | 0.54%   |
| Medion                  | 4         | 0.54%   |
| Intel                   | 4         | 0.54%   |
| Timi                    | 3         | 0.4%    |
| Samsung Electronics     | 2         | 0.27%   |
| Pegatron                | 2         | 0.27%   |
| LG Electronics          | 2         | 0.27%   |
| HUAWEI                  | 2         | 0.27%   |
| eMachines               | 2         | 0.27%   |
| TWC                     | 1         | 0.13%   |
| Synology                | 1         | 0.13%   |
| Supermicro              | 1         | 0.13%   |
| Sun Microsystems        | 1         | 0.13%   |
| Sapphire                | 1         | 0.13%   |
| Razer                   | 1         | 0.13%   |
| Packard Bell            | 1         | 0.13%   |
| NCR                     | 1         | 0.13%   |
| Inventec                | 1         | 0.13%   |
| IBM                     | 1         | 0.13%   |
| HONOR                   | 1         | 0.13%   |
| Foxconn                 | 1         | 0.13%   |
| ECS                     | 1         | 0.13%   |
| BenQ                    | 1         | 0.13%   |
| Alienware               | 1         | 0.13%   |
| Unknown                 | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS PRIME A320M-K                 | 16        | 2.15%   |
| ASUS All Series                    | 11        | 1.48%   |
| Acer Aspire A315-31                | 7         | 0.94%   |
| Gigabyte B450M DS3H                | 6         | 0.81%   |
| MSI MS-7309                        | 5         | 0.67%   |
| HP Notebook                        | 5         | 0.67%   |
| MSI MS-7641                        | 4         | 0.54%   |
| Lenovo V330-15IKB 81AX             | 4         | 0.54%   |
| Gigabyte H61M-S2PV                 | 4         | 0.54%   |
| Biostar A320MH                     | 4         | 0.54%   |
| Unknown                            | 4         | 0.54%   |
| MSI MS-7C02                        | 3         | 0.4%    |
| MSI MS-7788                        | 3         | 0.4%    |
| MSI MS-7721                        | 3         | 0.4%    |
| MSI MS-7597                        | 3         | 0.4%    |
| Lenovo IdeaPad 5 14ARE05 81YM      | 3         | 0.4%    |
| Lenovo IdeaPad 330-15IKB 81DE      | 3         | 0.4%    |
| Lenovo IdeaPad 3 15IIL05 81WE      | 3         | 0.4%    |
| Lenovo IdeaPad 110-15IBR 80T7      | 3         | 0.4%    |
| HP 250 G5 Notebook PC              | 3         | 0.4%    |
| Gigabyte F2A68HM-S1                | 3         | 0.4%    |
| Gigabyte A320M-H                   | 3         | 0.4%    |
| Dell Inspiron 3593                 | 3         | 0.4%    |
| ASUS X541NA                        | 3         | 0.4%    |
| ASUS H110M-R                       | 3         | 0.4%    |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 2         | 0.27%   |
| MSI MS-7C84                        | 2         | 0.27%   |
| MSI MS-7786                        | 2         | 0.27%   |
| MSI MS-7693                        | 2         | 0.27%   |
| MSI MS-7623                        | 2         | 0.27%   |
| MSI MS-7592                        | 2         | 0.27%   |
| MSI MS-7529                        | 2         | 0.27%   |
| MSI CR500                          | 2         | 0.27%   |
| Lenovo Legion Y530-15ICH 81FV      | 2         | 0.27%   |
| Lenovo Legion 5 15ARH05H 82B1      | 2         | 0.27%   |
| Lenovo IdeaPad S540-14API 81NH     | 2         | 0.27%   |
| Lenovo IdeaPad L340-15API 81LW     | 2         | 0.27%   |
| Lenovo IdeaPad 5 14ALC05 82LM      | 2         | 0.27%   |
| Lenovo G500 20236                  | 2         | 0.27%   |
| Lenovo B50-45 20388                | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 38        | 5.11%   |
| Lenovo IdeaPad        | 38        | 5.11%   |
| Acer Aspire           | 38        | 5.11%   |
| Dell Inspiron         | 26        | 3.5%    |
| ASUS PRIME            | 20        | 2.69%   |
| ASUS VivoBook         | 18        | 2.42%   |
| Dell Latitude         | 16        | 2.15%   |
| HP Laptop             | 14        | 1.88%   |
| HP EliteBook          | 13        | 1.75%   |
| HP Compaq             | 12        | 1.62%   |
| Toshiba Satellite     | 11        | 1.48%   |
| ASUS All              | 11        | 1.48%   |
| HP ProBook            | 10        | 1.35%   |
| Gigabyte B450M        | 9         | 1.21%   |
| Lenovo Legion         | 8         | 1.08%   |
| HP Pavilion           | 8         | 1.08%   |
| HP 250                | 7         | 0.94%   |
| ASUS ROG              | 7         | 0.94%   |
| Fujitsu ESPRIMO       | 6         | 0.81%   |
| Dell Vostro           | 6         | 0.81%   |
| Dell Precision        | 6         | 0.81%   |
| MSI MS-7309           | 5         | 0.67%   |
| Lenovo ThinkCentre    | 5         | 0.67%   |
| Lenovo ThinkBook      | 5         | 0.67%   |
| HP Notebook           | 5         | 0.67%   |
| Fujitsu Siemens AMILO | 5         | 0.67%   |
| Dell OptiPlex         | 5         | 0.67%   |
| ASUS TUF              | 5         | 0.67%   |
| RPi Raspberry         | 4         | 0.54%   |
| MSI MS-7641           | 4         | 0.54%   |
| Lenovo V330-15IKB     | 4         | 0.54%   |
| HP OMEN               | 4         | 0.54%   |
| Gigabyte H61M-S2PV    | 4         | 0.54%   |
| Biostar A320MH        | 4         | 0.54%   |
| Unknown               | 4         | 0.54%   |
| MSI MS-7C02           | 3         | 0.4%    |
| MSI MS-7788           | 3         | 0.4%    |
| MSI MS-7721           | 3         | 0.4%    |
| MSI MS-7597           | 3         | 0.4%    |
| Gigabyte X570         | 3         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 80        | 10.77%  |
| 2017    | 61        | 8.21%   |
| 2012    | 60        | 8.08%   |
| 2020    | 58        | 7.81%   |
| 2011    | 54        | 7.27%   |
| 2019    | 52        | 7%      |
| 2014    | 51        | 6.86%   |
| 2010    | 50        | 6.73%   |
| 2013    | 46        | 6.19%   |
| 2016    | 38        | 5.11%   |
| 2009    | 36        | 4.85%   |
| 2008    | 35        | 4.71%   |
| 2021    | 28        | 3.77%   |
| 2015    | 26        | 3.5%    |
| 2007    | 25        | 3.36%   |
| 2006    | 18        | 2.42%   |
| 2022    | 17        | 2.29%   |
| Unknown | 3         | 0.4%    |
| 2023    | 2         | 0.27%   |
| 2005    | 2         | 0.27%   |
| 2004    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 402       | 54.1%   |
| Desktop        | 317       | 42.66%  |
| Convertible    | 8         | 1.08%   |
| System on chip | 4         | 0.54%   |
| Tablet         | 3         | 0.4%    |
| Mini pc        | 3         | 0.4%    |
| All in one     | 3         | 0.4%    |
| Server         | 3         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 694       | 92.66%  |
| Enabled  | 55        | 7.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 743       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 186       | 24.38%  |
| 4.01-8.0    | 171       | 22.41%  |
| 8.01-16.0   | 165       | 21.63%  |
| 16.01-24.0  | 119       | 15.6%   |
| 32.01-64.0  | 44        | 5.77%   |
| 1.01-2.0    | 38        | 4.98%   |
| 2.01-3.0    | 14        | 1.83%   |
| 24.01-32.0  | 12        | 1.57%   |
| 64.01-256.0 | 8         | 1.05%   |
| 0.51-1.0    | 6         | 0.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 311       | 36.85%  |
| 2.01-3.0   | 195       | 23.1%   |
| 4.01-8.0   | 102       | 12.09%  |
| 3.01-4.0   | 100       | 11.85%  |
| 0.51-1.0   | 86        | 10.19%  |
| 8.01-16.0  | 28        | 3.32%   |
| 0.01-0.5   | 14        | 1.66%   |
| 16.01-24.0 | 6         | 0.71%   |
| 24.01-32.0 | 2         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 465       | 60.16%  |
| 2       | 187       | 24.19%  |
| 3       | 56        | 7.24%   |
| 4       | 24        | 3.1%    |
| 0       | 16        | 2.07%   |
| 5       | 15        | 1.94%   |
| 6       | 4         | 0.52%   |
| 7       | 2         | 0.26%   |
| Unknown | 2         | 0.26%   |
| 10      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 444       | 58.73%  |
| Yes       | 312       | 41.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 675       | 90.73%  |
| No        | 69        | 9.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 502       | 67.29%  |
| No        | 244       | 32.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 391       | 52.06%  |
| No        | 360       | 47.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Serbia  | 743       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Belgrade           | 444       | 55.99%  |
| Novi Sad           | 82        | 10.34%  |
| Niš               | 44        | 5.55%   |
| Subotica           | 16        | 2.02%   |
| Pančevo           | 11        | 1.39%   |
| Zrenjanin          | 10        | 1.26%   |
| Kragujevac         | 10        | 1.26%   |
| Leskovac           | 8         | 1.01%   |
| Požarevac         | 7         | 0.88%   |
| Backa Topola       | 7         | 0.88%   |
| Senta              | 6         | 0.76%   |
| Becej              | 6         | 0.76%   |
| Savski Venac       | 5         | 0.63%   |
| Jagodina           | 5         | 0.63%   |
| Čačak            | 5         | 0.63%   |
| Semlin             | 4         | 0.5%    |
| Palanka            | 4         | 0.5%    |
| Novi Karlovci      | 4         | 0.5%    |
| Novi Belgrade      | 4         | 0.5%    |
| Cuprija            | 4         | 0.5%    |
| Trstenik           | 3         | 0.38%   |
| Ruma               | 3         | 0.38%   |
| Pirot              | 3         | 0.38%   |
| Obrenovac          | 3         | 0.38%   |
| Novi Knezevac      | 3         | 0.38%   |
| New Belgrade       | 3         | 0.38%   |
| Mladenovac         | 3         | 0.38%   |
| Lozovik            | 3         | 0.38%   |
| Lazarevac          | 3         | 0.38%   |
| Kraljevo           | 3         | 0.38%   |
| Kovin              | 3         | 0.38%   |
| Banatsko Novo Selo | 3         | 0.38%   |
| Zvecka             | 2         | 0.25%   |
| Vršac             | 2         | 0.25%   |
| Varvarin           | 2         | 0.25%   |
| Stara Pazova       | 2         | 0.25%   |
| Sabac              | 2         | 0.25%   |
| Rumenka            | 2         | 0.25%   |
| Pukovac            | 2         | 0.25%   |
| Kruševac          | 2         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 192       | 314    | 18.05%  |
| Seagate                     | 126       | 167    | 11.84%  |
| Samsung Electronics         | 113       | 162    | 10.62%  |
| Toshiba                     | 108       | 149    | 10.15%  |
| Kingston                    | 99        | 144    | 9.3%    |
| Hitachi                     | 51        | 67     | 4.79%   |
| SanDisk                     | 39        | 50     | 3.67%   |
| Intel                       | 26        | 40     | 2.44%   |
| SPCC                        | 25        | 40     | 2.35%   |
| Patriot                     | 24        | 29     | 2.26%   |
| SK hynix                    | 23        | 27     | 2.16%   |
| Unknown                     | 19        | 25     | 1.79%   |
| Micron Technology           | 18        | 22     | 1.69%   |
| HGST                        | 17        | 27     | 1.6%    |
| Gigabyte Technology         | 17        | 20     | 1.6%    |
| Biostar                     | 17        | 19     | 1.6%    |
| Crucial                     | 12        | 14     | 1.13%   |
| A-DATA Technology           | 12        | 12     | 1.13%   |
| Transcend                   | 11        | 12     | 1.03%   |
| Maxtor                      | 11        | 12     | 1.03%   |
| Apacer                      | 8         | 10     | 0.75%   |
| Silicon Motion              | 7         | 10     | 0.66%   |
| KIOXIA                      | 7         | 8      | 0.66%   |
| GeIL                        | 6         | 6      | 0.56%   |
| Fujitsu                     | 6         | 6      | 0.56%   |
| Kingston Technology Company | 5         | 7      | 0.47%   |
| China                       | 5         | 8      | 0.47%   |
| Phison                      | 4         | 12     | 0.38%   |
| LITEON                      | 4         | 5      | 0.38%   |
| AMD                         | 4         | 4      | 0.38%   |
| Unknown                     | 4         | 6      | 0.38%   |
| StoreJet                    | 3         | 3      | 0.28%   |
| ExcelStor                   | 3         | 3      | 0.28%   |
| ADATA Technology            | 3         | 3      | 0.28%   |
| Verbatim                    | 2         | 2      | 0.19%   |
| Union Memory                | 2         | 2      | 0.19%   |
| Realtek Semiconductor       | 2         | 5      | 0.19%   |
| PNY                         | 2         | 4      | 0.19%   |
| Phison Electronics          | 2         | 3      | 0.19%   |
| Lexar                       | 2         | 5      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 23        | 2%      |
| Kingston SA400S37120G 120GB SSD                       | 23        | 2%      |
| Seagate ST1000LM035-1RK172 1TB                        | 18        | 1.57%   |
| Kingston SA400S37480G 480GB SSD                       | 17        | 1.48%   |
| Toshiba MQ01ABF050 500GB                              | 15        | 1.31%   |
| Toshiba DT01ACA100 1TB                                | 15        | 1.31%   |
| Toshiba DT01ACA050 500GB                              | 9         | 0.78%   |
| SPCC Solid State Disk 256GB                           | 9         | 0.78%   |
| Seagate ST500LT012-1DG142 500GB                       | 9         | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB                        | 8         | 0.7%    |
| Patriot Burst 240GB SSD                               | 8         | 0.7%    |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD                  | 8         | 0.7%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 7         | 0.61%   |
| Samsung NVMe SSD Drive 500GB                          | 7         | 0.61%   |
| Biostar S100-120GB SSD                                | 7         | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB                           | 6         | 0.52%   |
| Toshiba MQ04ABF100 1TB                                | 6         | 0.52%   |
| Toshiba MQ01ABD100 1TB                                | 6         | 0.52%   |
| Toshiba HDWD110 1TB                                   | 6         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 6         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                        | 6         | 0.52%   |
| Samsung SSD 860 EVO 500GB                             | 6         | 0.52%   |
| Samsung SSD 860 EVO 250GB                             | 6         | 0.52%   |
| WDC WD3200AAJS-56B4A0 320GB                           | 5         | 0.44%   |
| WDC WD2500BEVS-22UST0 250GB                           | 5         | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 5         | 0.44%   |
| Toshiba DT01ACA200 2TB                                | 5         | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 5         | 0.44%   |
| Seagate ST500LT012-9WS142 500GB                       | 5         | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                       | 5         | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB                        | 5         | 0.44%   |
| Samsung SSD 850 EVO 250GB                             | 5         | 0.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 5         | 0.44%   |
| Samsung MZALQ512HALU-000L2 512GB                      | 5         | 0.44%   |
| Hitachi HDS721050CLA362 500GB                         | 5         | 0.44%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD                  | 5         | 0.44%   |
| Crucial CT240BX500SSD1 240GB                          | 5         | 0.44%   |
| WDC WD5000LPCX-60VHAT0 500GB                          | 4         | 0.35%   |
| WDC WD3200BEVT-22ZCT0 320GB                           | 4         | 0.35%   |
| WDC WD1003FZEX-00K3CA0 1TB                            | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 171       | 287    | 34%     |
| Seagate             | 122       | 162    | 24.25%  |
| Toshiba             | 95        | 133    | 18.89%  |
| Hitachi             | 51        | 67     | 10.14%  |
| Samsung Electronics | 20        | 28     | 3.98%   |
| HGST                | 17        | 27     | 3.38%   |
| Maxtor              | 11        | 12     | 2.19%   |
| Fujitsu             | 6         | 6      | 1.19%   |
| ExcelStor           | 3         | 3      | 0.6%    |
| Unknown             | 2         | 2      | 0.4%    |
| Intenso             | 2         | 2      | 0.4%    |
| QUANTUM             | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 86        | 127    | 24.5%   |
| Samsung Electronics | 47        | 61     | 13.39%  |
| SPCC                | 25        | 40     | 7.12%   |
| Patriot             | 22        | 27     | 6.27%   |
| SanDisk             | 20        | 28     | 5.7%    |
| Gigabyte Technology | 15        | 18     | 4.27%   |
| Biostar             | 14        | 16     | 3.99%   |
| Intel               | 12        | 16     | 3.42%   |
| Crucial             | 12        | 14     | 3.42%   |
| Transcend           | 11        | 12     | 3.13%   |
| A-DATA Technology   | 11        | 11     | 3.13%   |
| WDC                 | 10        | 11     | 2.85%   |
| Micron Technology   | 7         | 8      | 1.99%   |
| Apacer              | 7         | 9      | 1.99%   |
| Toshiba             | 6         | 7      | 1.71%   |
| GeIL                | 6         | 6      | 1.71%   |
| China               | 5         | 8      | 1.42%   |
| LITEON              | 4         | 5      | 1.14%   |
| AMD                 | 4         | 4      | 1.14%   |
| StoreJet            | 3         | 3      | 0.85%   |
| SK hynix            | 3         | 3      | 0.85%   |
| Unknown             | 3         | 5      | 0.85%   |
| Verbatim            | 2         | 2      | 0.57%   |
| PNY                 | 2         | 4      | 0.57%   |
| Lexar               | 2         | 5      | 0.57%   |
| JMicron Technology  | 2         | 2      | 0.57%   |
| SSSTC               | 1         | 1      | 0.28%   |
| Seagate             | 1         | 1      | 0.28%   |
| OCZ                 | 1         | 2      | 0.28%   |
| Netac               | 1         | 1      | 0.28%   |
| Mushkin             | 1         | 1      | 0.28%   |
| LITEONIT            | 1         | 1      | 0.28%   |
| Leven               | 1         | 1      | 0.28%   |
| KingDian            | 1         | 1      | 0.28%   |
| ASMT                | 1         | 1      | 0.28%   |
| ADATA SU            | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 430       | 732    | 45.55%  |
| SSD     | 303       | 463    | 32.1%   |
| NVMe    | 186       | 262    | 19.7%   |
| MMC     | 16        | 21     | 1.69%   |
| Unknown | 9         | 10     | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 588       | 1178   | 72.15%  |
| NVMe | 186       | 262    | 22.82%  |
| SAS  | 25        | 27     | 3.07%   |
| MMC  | 16        | 21     | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 492       | 812    | 67.03%  |
| 0.51-1.0        | 183       | 268    | 24.93%  |
| 1.01-2.0        | 40        | 72     | 5.45%   |
| 3.01-4.0        | 7         | 12     | 0.95%   |
| 2.01-3.0        | 6         | 19     | 0.82%   |
| 4.01-10.0       | 5         | 11     | 0.68%   |
| More than 100.0 | 1         | 1      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 222       | 27.48%  |
| 251-500        | 185       | 22.9%   |
| 501-1000       | 98        | 12.13%  |
| 1-20           | 87        | 10.77%  |
| 1001-2000      | 50        | 6.19%   |
| 51-100         | 50        | 6.19%   |
| 21-50          | 39        | 4.83%   |
| Unknown        | 37        | 4.58%   |
| 2001-3000      | 21        | 2.6%    |
| More than 3000 | 19        | 2.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 328       | 39.42%  |
| 21-50          | 138       | 16.59%  |
| 101-250        | 111       | 13.34%  |
| 51-100         | 88        | 10.58%  |
| 251-500        | 65        | 7.81%   |
| Unknown        | 37        | 4.45%   |
| 501-1000       | 30        | 3.61%   |
| 1001-2000      | 24        | 2.88%   |
| 2001-3000      | 6         | 0.72%   |
| More than 3000 | 5         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB     | 3         | 3      | 3.16%   |
| Toshiba MQ01ABF050 500GB        | 3         | 3      | 3.16%   |
| WDC WD2002FAEX-007BA0 2TB       | 2         | 3      | 2.11%   |
| WDC WD10EALX-009BA0 1TB         | 2         | 3      | 2.11%   |
| Seagate ST500DM002-1BD142 500GB | 2         | 5      | 2.11%   |
| Seagate ST380815AS 80GB         | 2         | 2      | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB  | 2         | 2      | 2.11%   |
| Seagate ST1000DM003-1CH162 1TB  | 2         | 2      | 2.11%   |
| Intel SSDSC2CW120A3 120GB       | 2         | 2      | 2.11%   |
| Hitachi HTS545050A7E380 500GB   | 2         | 2      | 2.11%   |
| Hitachi HDP725050GLA360 500GB   | 2         | 2      | 2.11%   |
| HGST HTS725050A7E630 500GB      | 2         | 6      | 2.11%   |
| WDC WD5002AALX-00J37A0 500GB    | 1         | 1      | 1.05%   |
| WDC WD5000BEVT-24A0RT0 500GB    | 1         | 1      | 1.05%   |
| WDC WD5000AAKX-603CA0 500GB     | 1         | 1      | 1.05%   |
| WDC WD5000AAKX-329BA0 500GB     | 1         | 1      | 1.05%   |
| WDC WD5000AAKS-65A7B0 500GB     | 1         | 1      | 1.05%   |
| WDC WD5000AAKS-00UU3A0 500GB    | 1         | 1      | 1.05%   |
| WDC WD5000AAKS-00TMA0 500GB     | 1         | 1      | 1.05%   |
| WDC WD40EFRX-68WT0N0 4TB        | 1         | 1      | 1.05%   |
| WDC WD3200BEVT-22ZCT0 320GB     | 1         | 1      | 1.05%   |
| WDC WD3200BEKX-75B7WT0 320GB    | 1         | 1      | 1.05%   |
| WDC WD3200BEKT-60PVMT0 320GB    | 1         | 1      | 1.05%   |
| WDC WD3200AVVS-63L2B0 320GB     | 1         | 1      | 1.05%   |
| WDC WD3200AVVS-56L2B0 320GB     | 1         | 1      | 1.05%   |
| WDC WD20EARX-00PASB0 2TB        | 1         | 1      | 1.05%   |
| WDC WD1600AAJS-00PSA0 160GB     | 1         | 1      | 1.05%   |
| WDC WD1600AAJS-00L7A0 160GB     | 1         | 1      | 1.05%   |
| WDC WD15EARS-00Z5B1 1TB         | 1         | 1      | 1.05%   |
| WDC WD15EARS-00MVWB0 1TB        | 1         | 1      | 1.05%   |
| WDC WD10EZEX-75WN4A0 1TB        | 1         | 1      | 1.05%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1         | 1      | 1.05%   |
| WDC WD10EZEX-00RKKA0 1TB        | 1         | 1      | 1.05%   |
| WDC WD10EARS-00Y5B1 1TB         | 1         | 1      | 1.05%   |
| WDC WD10EADS-00M2B0 1TB         | 1         | 2      | 1.05%   |
| WDC WD1003FZEX-00MK2A0 1TB      | 1         | 1      | 1.05%   |
| WDC WD1001FALS-00J7B1 1TB       | 1         | 1      | 1.05%   |
| Toshiba MQ02ABD100H 1TB         | 1         | 1      | 1.05%   |
| Toshiba MQ01ABD032 320GB        | 1         | 1      | 1.05%   |
| Toshiba MK5061GSYN 500GB        | 1         | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 35     | 30.77%  |
| Seagate             | 18        | 23     | 19.78%  |
| Toshiba             | 11        | 11     | 12.09%  |
| Hitachi             | 10        | 11     | 10.99%  |
| Samsung Electronics | 7         | 11     | 7.69%   |
| Maxtor              | 4         | 5      | 4.4%    |
| HGST                | 3         | 8      | 3.3%    |
| SPCC                | 2         | 2      | 2.2%    |
| Kingston            | 2         | 2      | 2.2%    |
| Intel               | 2         | 2      | 2.2%    |
| Fujitsu             | 2         | 2      | 2.2%    |
| ExcelStor           | 1         | 1      | 1.1%    |
| Crucial             | 1         | 1      | 1.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 35     | 34.15%  |
| Seagate             | 18        | 23     | 21.95%  |
| Toshiba             | 10        | 10     | 12.2%   |
| Hitachi             | 10        | 11     | 12.2%   |
| Samsung Electronics | 6         | 8      | 7.32%   |
| Maxtor              | 4         | 5      | 4.88%   |
| HGST                | 3         | 8      | 3.66%   |
| Fujitsu             | 2         | 2      | 2.44%   |
| ExcelStor           | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 72        | 103    | 88.89%  |
| SSD  | 9         | 11     | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600AAJS-00YZCA0 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 437       | 920    | 55.11%  |
| Works    | 274       | 453    | 34.55%  |
| Malfunc  | 81        | 114    | 10.21%  |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 467       | 50.98%  |
| AMD                            | 183       | 19.98%  |
| Samsung Electronics            | 59        | 6.44%   |
| SanDisk                        | 31        | 3.38%   |
| Nvidia                         | 30        | 3.28%   |
| JMicron Technology             | 21        | 2.29%   |
| SK hynix                       | 20        | 2.18%   |
| Kingston Technology Company    | 20        | 2.18%   |
| Micron Technology              | 11        | 1.2%    |
| Marvell Technology Group       | 9         | 0.98%   |
| Toshiba America Info Systems   | 8         | 0.87%   |
| Silicon Motion                 | 8         | 0.87%   |
| Phison Electronics             | 8         | 0.87%   |
| ASMedia Technology             | 8         | 0.87%   |
| KIOXIA                         | 7         | 0.76%   |
| VIA Technologies               | 5         | 0.55%   |
| Union Memory (Shenzhen)        | 4         | 0.44%   |
| ADATA Technology               | 4         | 0.44%   |
| Broadcom / LSI                 | 3         | 0.33%   |
| Shenzhen Longsys Electronics   | 2         | 0.22%   |
| Realtek Semiconductor          | 2         | 0.22%   |
| LSI Logic / Symbios Logic      | 2         | 0.22%   |
| Solid State Storage Technology | 1         | 0.11%   |
| Silicon Image                  | 1         | 0.11%   |
| Lenovo                         | 1         | 0.11%   |
| Apple                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 124       | 11.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 34        | 3.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 30        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 29        | 2.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 28        | 2.55%   |
| AMD FCH SATA Controller D                                                               | 28        | 2.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 26        | 2.37%   |
| AMD 400 Series Chipset SATA Controller                                                  | 25        | 2.28%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 2.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 23        | 2.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 22        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 22        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20        | 1.82%   |
| Samsung NVMe SSD Controller 980                                                         | 17        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16        | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15        | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 14        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 1.18%   |
| Nvidia MCP61 SATA Controller                                                            | 12        | 1.09%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12        | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 12        | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 1.09%   |
| Nvidia MCP61 IDE                                                                        | 11        | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 11        | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 11        | 1%      |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11        | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 0.91%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 10        | 0.91%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 10        | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 9         | 0.82%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9         | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 8         | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8         | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 0.73%   |
| Intel SATA Controller [RAID mode]                                                       | 8         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 8         | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 552       | 59.29%  |
| NVMe | 190       | 20.41%  |
| IDE  | 142       | 15.25%  |
| RAID | 43        | 4.62%   |
| SCSI | 3         | 0.32%   |
| SAS  | 1         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 508       | 68.37%  |
| AMD    | 231       | 31.09%  |
| ARM    | 4         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 1600 Six-Core Processor           | 10        | 1.34%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 7         | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.81%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.81%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.81%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.67%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.67%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 5         | 0.67%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.67%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.67%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 5         | 0.67%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 5         | 0.67%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5         | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.67%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 5         | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.54%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 4         | 0.54%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.54%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 4         | 0.54%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 4         | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.54%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.54%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.54%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 0.54%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.54%   |
| AMD A4-4020 APU with Radeon HD Graphics       | 4         | 0.54%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 3         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 114       | 15.32%  |
| Intel Core i7           | 106       | 14.25%  |
| AMD Ryzen 5             | 74        | 9.95%   |
| Intel Core i3           | 69        | 9.27%   |
| Intel Celeron           | 47        | 6.32%   |
| Intel Core 2 Duo        | 41        | 5.51%   |
| Intel Pentium           | 38        | 5.11%   |
| Other                   | 29        | 3.9%    |
| AMD Ryzen 7             | 25        | 3.36%   |
| Intel Xeon              | 14        | 1.88%   |
| AMD Ryzen 3             | 14        | 1.88%   |
| Intel Pentium Dual-Core | 12        | 1.61%   |
| AMD Phenom II X4        | 11        | 1.48%   |
| Intel Atom              | 9         | 1.21%   |
| AMD FX                  | 9         | 1.21%   |
| AMD Athlon X4           | 9         | 1.21%   |
| AMD A4                  | 9         | 1.21%   |
| Intel Core 2 Quad       | 8         | 1.08%   |
| AMD Ryzen 9             | 7         | 0.94%   |
| AMD Athlon II X2        | 7         | 0.94%   |
| AMD Athlon 64 X2        | 7         | 0.94%   |
| Intel Core 2            | 6         | 0.81%   |
| AMD Athlon II X3        | 5         | 0.67%   |
| AMD A8                  | 5         | 0.67%   |
| Intel Pentium Silver    | 4         | 0.54%   |
| Intel Pentium Dual      | 4         | 0.54%   |
| AMD Athlon II X4        | 4         | 0.54%   |
| AMD A10                 | 4         | 0.54%   |
| Intel Pentium M         | 3         | 0.4%    |
| Intel Pentium Gold      | 3         | 0.4%    |
| AMD Ryzen 5 PRO         | 3         | 0.4%    |
| AMD Ryzen 3 PRO         | 3         | 0.4%    |
| AMD E1                  | 3         | 0.4%    |
| AMD Athlon              | 3         | 0.4%    |
| AMD A6                  | 3         | 0.4%    |
| Intel Genuine           | 2         | 0.27%   |
| AMD Sempron             | 2         | 0.27%   |
| AMD Ryzen Threadripper  | 2         | 0.27%   |
| AMD Phenom II X6        | 2         | 0.27%   |
| AMD Phenom II           | 2         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 314       | 42.2%   |
| 4       | 272       | 36.56%  |
| 6       | 75        | 10.08%  |
| 1       | 28        | 3.76%   |
| 8       | 27        | 3.63%   |
| 3       | 9         | 1.21%   |
| 12      | 7         | 0.94%   |
| 14      | 5         | 0.67%   |
| 16      | 3         | 0.4%    |
| Unknown | 2         | 0.27%   |
| 32      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 738       | 99.33%  |
| 2       | 4         | 0.54%   |
| Unknown | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 433       | 58.28%  |
| 1       | 308       | 41.45%  |
| Unknown | 2         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 718       | 96.51%  |
| Unknown        | 17        | 2.28%   |
| 32-bit         | 9         | 1.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 176       | 22.71%  |
| 0x206a7    | 47        | 6.06%   |
| 0x306a9    | 36        | 4.65%   |
| 0x1067a    | 34        | 4.39%   |
| 0x306c3    | 27        | 3.48%   |
| 0x406e3    | 19        | 2.45%   |
| 0x806ea    | 17        | 2.19%   |
| 0x906ea    | 16        | 2.06%   |
| 0x6fd      | 15        | 1.94%   |
| 0x906e9    | 14        | 1.81%   |
| 0x0800820d | 14        | 1.81%   |
| 0x08108109 | 13        | 1.68%   |
| 0x806ec    | 12        | 1.55%   |
| 0x506e3    | 12        | 1.55%   |
| 0x506c9    | 12        | 1.55%   |
| 0x010000c8 | 11        | 1.42%   |
| 0x706e5    | 10        | 1.29%   |
| 0x40651    | 10        | 1.29%   |
| 0x10676    | 10        | 1.29%   |
| 0x0a50000c | 10        | 1.29%   |
| 0x06001119 | 10        | 1.29%   |
| 0x806e9    | 9         | 1.16%   |
| 0x306d4    | 9         | 1.16%   |
| 0x08101016 | 8         | 1.03%   |
| 0x806c1    | 7         | 0.9%    |
| 0x406c4    | 7         | 0.9%    |
| 0x30678    | 7         | 0.9%    |
| 0x20655    | 7         | 0.9%    |
| 0x08701021 | 7         | 0.9%    |
| 0x08600106 | 7         | 0.9%    |
| 0x08108102 | 7         | 0.9%    |
| 0x806eb    | 6         | 0.77%   |
| 0x106e5    | 6         | 0.77%   |
| 0x06003106 | 6         | 0.77%   |
| 0xa0652    | 5         | 0.65%   |
| 0x6fb      | 5         | 0.65%   |
| 0x20652    | 5         | 0.65%   |
| 0x0a50000d | 5         | 0.65%   |
| 0x08608103 | 5         | 0.65%   |
| 0x906eb    | 4         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 91        | 12.25%  |
| SandyBridge      | 61        | 8.21%   |
| Haswell          | 51        | 6.86%   |
| Penryn           | 49        | 6.59%   |
| Zen+             | 47        | 6.33%   |
| IvyBridge        | 44        | 5.92%   |
| K10              | 39        | 5.25%   |
| Skylake          | 33        | 4.44%   |
| Core             | 30        | 4.04%   |
| Zen 3            | 25        | 3.36%   |
| Zen 2            | 25        | 3.36%   |
| Zen              | 24        | 3.23%   |
| Silvermont       | 24        | 3.23%   |
| Piledriver       | 23        | 3.1%    |
| Westmere         | 20        | 2.69%   |
| IceLake          | 16        | 2.15%   |
| Unknown          | 16        | 2.15%   |
| Goldmont         | 14        | 1.88%   |
| Broadwell        | 13        | 1.75%   |
| TigerLake        | 12        | 1.62%   |
| Nehalem          | 10        | 1.35%   |
| K8 Hammer        | 10        | 1.35%   |
| Steamroller      | 8         | 1.08%   |
| Goldmont plus    | 8         | 1.08%   |
| Alderlake Hybrid | 8         | 1.08%   |
| P6               | 7         | 0.94%   |
| Jaguar           | 7         | 0.94%   |
| CometLake        | 6         | 0.81%   |
| Bonnell          | 5         | 0.67%   |
| Puma             | 4         | 0.54%   |
| Excavator        | 4         | 0.54%   |
| Tremont          | 2         | 0.27%   |
| NetBurst         | 2         | 0.27%   |
| K8 & K10 hybrid  | 2         | 0.27%   |
| K10 Llano        | 2         | 0.27%   |
| Bulldozer        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 373       | 42.39%  |
| AMD                                          | 271       | 30.8%   |
| Nvidia                                       | 232       | 26.36%  |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.11%   |
| VIA Technologies                             | 1         | 0.11%   |
| Matrox Electronics Systems                   | 1         | 0.11%   |
| ASPEED Technology                            | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 43        | 4.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 28        | 3.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 23        | 2.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 2.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 1.53%   |
| AMD Renoir                                                                               | 14        | 1.53%   |
| Intel UHD Graphics 620                                                                   | 13        | 1.42%   |
| Intel HD Graphics 620                                                                    | 13        | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 1.2%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.09%   |
| Intel HD Graphics 630                                                                    | 10        | 1.09%   |
| Intel HD Graphics 5500                                                                   | 10        | 1.09%   |
| Intel HD Graphics 530                                                                    | 10        | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 1.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.98%   |
| Intel HD Graphics 500                                                                    | 9         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 0.87%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 8         | 0.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.87%   |
| AMD Lucienne                                                                             | 8         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.77%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7         | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.77%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7         | 0.77%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 0.66%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.55%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 5         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 248       | 33.11%  |
| 1 x AMD        | 212       | 28.3%   |
| 1 x Nvidia     | 127       | 16.96%  |
| Intel + Nvidia | 90        | 12.02%  |
| Intel + AMD    | 32        | 4.27%   |
| 2 x AMD        | 18        | 2.4%    |
| AMD + Nvidia   | 10        | 1.34%   |
| Other          | 5         | 0.67%   |
| 2 x Nvidia     | 3         | 0.4%    |
| 1 x VIA        | 1         | 0.13%   |
| Nvidia + XGI   | 1         | 0.13%   |
| 1 x Matrox     | 1         | 0.13%   |
| 1 x ASPEED     | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 612       | 80.95%  |
| Proprietary | 115       | 15.21%  |
| Unknown     | 29        | 3.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 361       | 46.64%  |
| 1.01-2.0   | 125       | 16.15%  |
| 0.01-0.5   | 114       | 14.73%  |
| 0.51-1.0   | 76        | 9.82%   |
| 3.01-4.0   | 63        | 8.14%   |
| 7.01-8.0   | 19        | 2.45%   |
| 5.01-6.0   | 9         | 1.16%   |
| 8.01-16.0  | 5         | 0.65%   |
| 2.01-3.0   | 2         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 106       | 13.4%   |
| AU Optronics            | 89        | 11.25%  |
| BOE                     | 73        | 9.23%   |
| LG Display              | 69        | 8.72%   |
| Chimei Innolux          | 63        | 7.96%   |
| Goldstar                | 52        | 6.57%   |
| Dell                    | 48        | 6.07%   |
| Philips                 | 36        | 4.55%   |
| Hewlett-Packard         | 24        | 3.03%   |
| Lenovo                  | 22        | 2.78%   |
| BenQ                    | 21        | 2.65%   |
| Acer                    | 17        | 2.15%   |
| ViewSonic               | 15        | 1.9%    |
| Ancor Communications    | 14        | 1.77%   |
| Chi Mei Optoelectronics | 13        | 1.64%   |
| AOC                     | 13        | 1.64%   |
| Sharp                   | 10        | 1.26%   |
| ASUSTek Computer        | 10        | 1.26%   |
| Apple                   | 10        | 1.26%   |
| PANDA                   | 9         | 1.14%   |
| LG Electronics          | 7         | 0.88%   |
| Toshiba                 | 5         | 0.63%   |
| Sony                    | 5         | 0.63%   |
| LG Philips              | 5         | 0.63%   |
| Unknown                 | 4         | 0.51%   |
| InfoVision              | 4         | 0.51%   |
| CPT                     | 4         | 0.51%   |
| Belinea                 | 4         | 0.51%   |
| OEM                     | 3         | 0.38%   |
| KTC                     | 3         | 0.38%   |
| Gigabyte Technology     | 3         | 0.38%   |
| Fujitsu Siemens         | 3         | 0.38%   |
| CHD                     | 3         | 0.38%   |
| SKY                     | 2         | 0.25%   |
| LED                     | 2         | 0.25%   |
| Hitachi                 | 2         | 0.25%   |
| HIC                     | 2         | 0.25%   |
| CSO                     | 2         | 0.25%   |
| Unknown                 | 2         | 0.25%   |
| Vestel Elektronik       | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 17        | 2.09%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 7         | 0.86%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 6         | 0.74%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 5         | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.62%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.62%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.62%   |
| Philips PHL 226E9Q PHLC17D 1920x1080 476x268mm 21.5-inch              | 4         | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.49%   |
| Goldstar W2240 GSM57A0 1920x1080 477x268mm 21.5-inch                  | 4         | 0.49%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.49%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.49%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.49%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 3         | 0.37%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 3         | 0.37%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 3         | 0.37%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.37%   |
| Samsung Electronics S22B300 SAM08AA 1920x1080 477x268mm 21.5-inch     | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.37%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.37%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 3         | 0.37%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.37%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 3         | 0.37%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                  | 3         | 0.37%   |
| Goldstar W2243 GSM56FE 1920x1080 480x270mm 21.7-inch                  | 3         | 0.37%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.37%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 3         | 0.37%   |
| Dell S2421HN DEL41F1 1920x1080 527x296mm 23.8-inch                    | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 3         | 0.37%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 375       | 50.13%  |
| 1366x768 (WXGA)    | 149       | 19.92%  |
| 1280x1024 (SXGA)   | 38        | 5.08%   |
| 3840x2160 (4K)     | 28        | 3.74%   |
| 1680x1050 (WSXGA+) | 23        | 3.07%   |
| 2560x1440 (QHD)    | 19        | 2.54%   |
| 1440x900 (WXGA+)   | 19        | 2.54%   |
| 1280x800 (WXGA)    | 16        | 2.14%   |
| 1600x900 (HD+)     | 15        | 2.01%   |
| 1920x1200 (WUXGA)  | 11        | 1.47%   |
| 1360x768           | 9         | 1.2%    |
| 1920x540           | 6         | 0.8%    |
| 2560x1600          | 5         | 0.67%   |
| Unknown            | 5         | 0.67%   |
| 2880x1800          | 4         | 0.53%   |
| 3840x1080          | 3         | 0.4%    |
| 2560x1080          | 3         | 0.4%    |
| 1600x1200          | 3         | 0.4%    |
| 1024x768 (XGA)     | 3         | 0.4%    |
| 1024x600           | 3         | 0.4%    |
| 1400x1050          | 2         | 0.27%   |
| 3440x1440          | 1         | 0.13%   |
| 3360x1200          | 1         | 0.13%   |
| 3280x1080          | 1         | 0.13%   |
| 2520x1680          | 1         | 0.13%   |
| 2160x1350          | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1834x1031          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 250       | 31.77%  |
| 21      | 71        | 9.02%   |
| 23      | 65        | 8.26%   |
| 24      | 64        | 8.13%   |
| 17      | 51        | 6.48%   |
| 13      | 44        | 5.59%   |
| 14      | 38        | 4.83%   |
| Unknown | 35        | 4.45%   |
| 27      | 33        | 4.19%   |
| 19      | 23        | 2.92%   |
| 18      | 20        | 2.54%   |
| 22      | 16        | 2.03%   |
| 12      | 14        | 1.78%   |
| 31      | 9         | 1.14%   |
| 20      | 8         | 1.02%   |
| 72      | 7         | 0.89%   |
| 16      | 6         | 0.76%   |
| 11      | 5         | 0.64%   |
| 84      | 4         | 0.51%   |
| 34      | 4         | 0.51%   |
| 40      | 3         | 0.38%   |
| 52      | 2         | 0.25%   |
| 46      | 2         | 0.25%   |
| 32      | 2         | 0.25%   |
| 26      | 2         | 0.25%   |
| 10      | 2         | 0.25%   |
| 65      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 43      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |
| 25      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 336       | 43.41%  |
| 501-600     | 156       | 20.16%  |
| 401-500     | 119       | 15.37%  |
| 351-400     | 49        | 6.33%   |
| 201-300     | 39        | 5.04%   |
| Unknown     | 35        | 4.52%   |
| 1501-2000   | 11        | 1.42%   |
| 601-700     | 10        | 1.29%   |
| 701-800     | 7         | 0.9%    |
| 1001-1500   | 6         | 0.78%   |
| 801-900     | 4         | 0.52%   |
| 101-200     | 1         | 0.13%   |
| 901-1000    | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 550       | 77.46%  |
| 16/10   | 67        | 9.44%   |
| 5/4     | 35        | 4.93%   |
| Unknown | 30        | 4.23%   |
| 4/3     | 12        | 1.69%   |
| 3/2     | 10        | 1.41%   |
| 21/9    | 4         | 0.56%   |
| 6/5     | 1         | 0.14%   |
| 32/9    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 249       | 31.92%  |
| 201-250        | 183       | 23.46%  |
| 81-90          | 66        | 8.46%   |
| 151-200        | 46        | 5.9%    |
| 141-150        | 40        | 5.13%   |
| 301-350        | 35        | 4.49%   |
| Unknown        | 35        | 4.49%   |
| 121-130        | 27        | 3.46%   |
| 71-80          | 18        | 2.31%   |
| 351-500        | 16        | 2.05%   |
| More than 1000 | 15        | 1.92%   |
| 251-300        | 15        | 1.92%   |
| 61-70          | 11        | 1.41%   |
| 501-1000       | 7         | 0.9%    |
| 111-120        | 6         | 0.77%   |
| 51-60          | 5         | 0.64%   |
| 41-50          | 2         | 0.26%   |
| 91-100         | 2         | 0.26%   |
| 1-40           | 1         | 0.13%   |
| 131-140        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 261       | 34.3%   |
| 101-120       | 221       | 29.04%  |
| 121-160       | 195       | 25.62%  |
| Unknown       | 35        | 4.6%    |
| 161-240       | 30        | 3.94%   |
| 1-50          | 13        | 1.71%   |
| More than 240 | 6         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 611       | 79.97%  |
| 2     | 109       | 14.27%  |
| 0     | 30        | 3.93%   |
| 3     | 14        | 1.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 468       | 42.82%  |
| Intel                             | 261       | 23.88%  |
| Qualcomm Atheros                  | 149       | 13.63%  |
| Broadcom                          | 60        | 5.49%   |
| Nvidia                            | 22        | 2.01%   |
| TP-Link                           | 15        | 1.37%   |
| Ralink Technology                 | 13        | 1.19%   |
| Qualcomm Atheros Communications   | 12        | 1.1%    |
| Ralink                            | 11        | 1.01%   |
| MediaTek                          | 11        | 1.01%   |
| Broadcom Limited                  | 10        | 0.91%   |
| Marvell Technology Group          | 7         | 0.64%   |
| Dell                              | 6         | 0.55%   |
| Sierra Wireless                   | 4         | 0.37%   |
| Ericsson Business Mobile Networks | 4         | 0.37%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.27%   |
| VIA Technologies                  | 3         | 0.27%   |
| Huawei Technologies               | 3         | 0.27%   |
| ASUSTek Computer                  | 3         | 0.27%   |
| Xiaomi                            | 2         | 0.18%   |
| OPPO Electronics                  | 2         | 0.18%   |
| JMicron Technology                | 2         | 0.18%   |
| Edimax Technology                 | 2         | 0.18%   |
| D-Link                            | 2         | 0.18%   |
| ZyXEL Communications              | 1         | 0.09%   |
| Texas Instruments                 | 1         | 0.09%   |
| Sundance Technology Inc / IC Plus | 1         | 0.09%   |
| Sigma Designs                     | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| LSI                               | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| Lenovo                            | 1         | 0.09%   |
| IMC Networks                      | 1         | 0.09%   |
| Hewlett-Packard                   | 1         | 0.09%   |
| DisplayLink                       | 1         | 0.09%   |
| D-Link System                     | 1         | 0.09%   |
| ASIX Electronics                  | 1         | 0.09%   |
| Arduino SA                        | 1         | 0.09%   |
| Aquantia                          | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 331       | 26.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74        | 5.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 31        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 22        | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 22        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 1.44%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 1.04%   |
| Intel Wireless 8260                                               | 13        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                     | 13        | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 12        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 0.96%   |
| Intel Wireless 7260                                               | 12        | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 10        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                   | 9         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 0.64%   |
| Intel Wireless 3165                                               | 8         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 8         | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 7         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 0.56%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.56%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 6         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 193       | 36.76%  |
| Qualcomm Atheros                  | 119       | 22.67%  |
| Realtek Semiconductor             | 88        | 16.76%  |
| Broadcom                          | 41        | 7.81%   |
| TP-Link                           | 14        | 2.67%   |
| Ralink Technology                 | 13        | 2.48%   |
| Qualcomm Atheros Communications   | 12        | 2.29%   |
| Ralink                            | 11        | 2.1%    |
| MediaTek                          | 10        | 1.9%    |
| Sierra Wireless                   | 4         | 0.76%   |
| Dell                              | 4         | 0.76%   |
| Broadcom Limited                  | 3         | 0.57%   |
| ASUSTek Computer                  | 3         | 0.57%   |
| Edimax Technology                 | 2         | 0.38%   |
| D-Link                            | 2         | 0.38%   |
| ZyXEL Communications              | 1         | 0.19%   |
| NetGear                           | 1         | 0.19%   |
| Linksys                           | 1         | 0.19%   |
| IMC Networks                      | 1         | 0.19%   |
| Hewlett-Packard                   | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 5.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 22        | 4.18%   |
| Intel Wireless 8265 / 8275                                              | 22        | 4.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 3.99%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 3.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 3.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 2.47%   |
| Intel Wireless 8260                                                     | 13        | 2.47%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 2.28%   |
| Intel Wireless 7260                                                     | 12        | 2.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.9%    |
| Qualcomm Atheros AR9271 802.11n                                         | 9         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 1.52%   |
| Intel Wireless 3165                                                     | 8         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 6         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.95%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 5         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 0.95%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 4         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.76%   |
| Intel Wireless 7265                                                     | 4         | 0.76%   |
| Intel Wireless 3160                                                     | 4         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 438       | 62.93%  |
| Intel                             | 132       | 18.97%  |
| Qualcomm Atheros                  | 41        | 5.89%   |
| Broadcom                          | 25        | 3.59%   |
| Nvidia                            | 22        | 3.16%   |
| Marvell Technology Group          | 7         | 1.01%   |
| Broadcom Limited                  | 7         | 1.01%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.43%   |
| VIA Technologies                  | 3         | 0.43%   |
| Xiaomi                            | 2         | 0.29%   |
| OPPO Electronics                  | 2         | 0.29%   |
| JMicron Technology                | 2         | 0.29%   |
| TP-Link                           | 1         | 0.14%   |
| Sundance Technology Inc / IC Plus | 1         | 0.14%   |
| Samsung Electronics               | 1         | 0.14%   |
| MediaTek                          | 1         | 0.14%   |
| Lenovo                            | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| DisplayLink                       | 1         | 0.14%   |
| D-Link System                     | 1         | 0.14%   |
| ASIX Electronics                  | 1         | 0.14%   |
| Aquantia                          | 1         | 0.14%   |
| Apple                             | 1         | 0.14%   |
| ADMtek                            | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 331       | 46.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74        | 10.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 2.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 1.7%    |
| Intel I211 Gigabit Network Connection                             | 10        | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.13%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 7         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.85%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.85%   |
| Nvidia MCP61 Ethernet                                             | 6         | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.71%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 4         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.57%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3         | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.42%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.42%   |
| ZTE WCDMA MSM SCSI CD-ROM 2.31                                    | 2         | 0.28%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 675       | 56.77%  |
| WiFi     | 502       | 42.22%  |
| Modem    | 12        | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 403       | 52.47%  |
| Ethernet | 365       | 47.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 388       | 52.08%  |
| 1     | 340       | 45.64%  |
| 3     | 7         | 0.94%   |
| 0     | 7         | 0.94%   |
| 5     | 2         | 0.27%   |
| 8     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 731       | 98.25%  |
| Yes  | 13        | 1.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 145       | 37.08%  |
| Realtek Semiconductor           | 54        | 13.81%  |
| Qualcomm Atheros Communications | 36        | 9.21%   |
| Lite-On Technology              | 28        | 7.16%   |
| Cambridge Silicon Radio         | 25        | 6.39%   |
| IMC Networks                    | 23        | 5.88%   |
| Broadcom                        | 20        | 5.12%   |
| Foxconn / Hon Hai               | 13        | 3.32%   |
| Apple                           | 10        | 2.56%   |
| Toshiba                         | 6         | 1.53%   |
| Hewlett-Packard                 | 6         | 1.53%   |
| Dell                            | 5         | 1.28%   |
| ASUSTek Computer                | 5         | 1.28%   |
| Ralink                          | 3         | 0.77%   |
| Foxconn International           | 3         | 0.77%   |
| USI                             | 2         | 0.51%   |
| Ralink Technology               | 2         | 0.51%   |
| Realtek                         | 1         | 0.26%   |
| Opticis                         | 1         | 0.26%   |
| MediaTek                        | 1         | 0.26%   |
| Askey Computer                  | 1         | 0.26%   |
| Alps Electric                   | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 60        | 15.35%  |
| Realtek Bluetooth Radio                             | 35        | 8.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 26        | 6.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 6.39%   |
| Intel AX201 Bluetooth                               | 19        | 4.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 4.6%    |
| Intel AX200 Bluetooth                               | 17        | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 3.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 3.07%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.3%    |
| Lite-On Bluetooth Device                            | 8         | 2.05%   |
| Intel Bluetooth Device                              | 8         | 2.05%   |
| Apple Bluetooth Host Controller                     | 6         | 1.53%   |
| Realtek RTL8821A Bluetooth                          | 5         | 1.28%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.02%   |
| Intel AX210 Bluetooth                               | 4         | 1.02%   |
| IMC Networks Wireless_Device                        | 4         | 1.02%   |
| IMC Networks Bluetooth Device                       | 4         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.02%   |
| Dell DW375 Bluetooth Module                         | 4         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 1.02%   |
| Ralink RT3290 Bluetooth                             | 3         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.77%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.77%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.77%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.77%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 3         | 0.77%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.77%   |
| USI Bluetooth Module BCM92070                       | 2         | 0.51%   |
| Toshiba Bluetooth Device                            | 2         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 490       | 49.05%  |
| AMD                                             | 275       | 27.53%  |
| Nvidia                                          | 170       | 17.02%  |
| C-Media Electronics                             | 8         | 0.8%    |
| Generalplus Technology                          | 5         | 0.5%    |
| Focusrite-Novation                              | 5         | 0.5%    |
| Creative Labs                                   | 5         | 0.5%    |
| Logitech                                        | 4         | 0.4%    |
| VIA Technologies                                | 3         | 0.3%    |
| RODE Microphones                                | 2         | 0.2%    |
| Plantronics                                     | 2         | 0.2%    |
| Native Instruments                              | 2         | 0.2%    |
| JMTek                                           | 2         | 0.2%    |
| Hewlett-Packard                                 | 2         | 0.2%    |
| GN Netcom                                       | 2         | 0.2%    |
| ASUSTek Computer                                | 2         | 0.2%    |
| Apple                                           | 2         | 0.2%    |
| XMOS                                            | 1         | 0.1%    |
| Veho                                            | 1         | 0.1%    |
| Unknown                                         | 1         | 0.1%    |
| Turtle Beach                                    | 1         | 0.1%    |
| Syntek                                          | 1         | 0.1%    |
| Sony                                            | 1         | 0.1%    |
| SAVITECH                                        | 1         | 0.1%    |
| Realtek Semiconductor                           | 1         | 0.1%    |
| Razer USA                                       | 1         | 0.1%    |
| Oculus VR                                       | 1         | 0.1%    |
| Microsoft                                       | 1         | 0.1%    |
| Micro Star International                        | 1         | 0.1%    |
| Meizu                                           | 1         | 0.1%    |
| M-Audio                                         | 1         | 0.1%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.1%    |
| Kingston Technology                             | 1         | 0.1%    |
| FiiO Electronics Technology                     | 1         | 0.1%    |
| Ensoniq                                         | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 84        | 6.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 57        | 4.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 3.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 45        | 3.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 38        | 3.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 36        | 2.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 2.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 36        | 2.95%   |
| AMD FCH Azalia Controller                                                                         | 35        | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 32        | 2.62%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 26        | 2.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 26        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 1.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 23        | 1.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 1.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 19        | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 16        | 1.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 14        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 1.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 1.07%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 1.07%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 1.07%   |
| Nvidia MCP61 High Definition Audio                                                                | 12        | 0.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 11        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11        | 0.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 11        | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 10        | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 101       | 21.4%   |
| Samsung Electronics | 93        | 19.7%   |
| SK hynix            | 74        | 15.68%  |
| Unknown             | 58        | 12.29%  |
| Micron Technology   | 41        | 8.69%   |
| Patriot             | 14        | 2.97%   |
| Ramaxel Technology  | 13        | 2.75%   |
| Transcend           | 12        | 2.54%   |
| Crucial             | 12        | 2.54%   |
| Corsair             | 8         | 1.69%   |
| Elpida              | 7         | 1.48%   |
| Apacer              | 7         | 1.48%   |
| A-DATA Technology   | 6         | 1.27%   |
| Nanya Technology    | 5         | 1.06%   |
| Unknown             | 4         | 0.85%   |
| GeIL                | 2         | 0.42%   |
| G.Skill             | 2         | 0.42%   |
| Unknown (06F1)      | 1         | 0.21%   |
| Unifosa             | 1         | 0.21%   |
| Swissbit            | 1         | 0.21%   |
| Silicon Power       | 1         | 0.21%   |
| SHARETRONIC         | 1         | 0.21%   |
| Ramos Technology    | 1         | 0.21%   |
| Qimonda             | 1         | 0.21%   |
| PNY                 | 1         | 0.21%   |
| Mushkin             | 1         | 0.21%   |
| Exceleram           | 1         | 0.21%   |
| CSX                 | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |
| 48spaces            | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 7         | 1.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 6         | 1.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 6         | 1.15%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 5         | 0.96%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 5         | 0.96%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s     | 5         | 0.96%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 4         | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 4         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 4         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 4         | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s       | 4         | 0.77%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 4         | 0.77%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s           | 4         | 0.77%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s     | 4         | 0.77%   |
| Unknown                                                     | 4         | 0.77%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                     | 3         | 0.57%   |
| Unknown RAM CL19-19-19 D4-2666 8192MB DIMM DDR4 2400MT/s    | 3         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 0.57%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s      | 3         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 3         | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 0.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 3         | 0.57%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 0.57%   |
| Samsung RAM M393B1K70CH0-CH9 8GB DIMM 1333MT/s              | 3         | 0.57%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 3         | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 3         | 0.57%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 3         | 0.57%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 3         | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s         | 3         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s       | 3         | 0.57%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                     | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                        | 2         | 0.38%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                      | 2         | 0.38%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                      | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 166       | 42.56%  |
| DDR3    | 139       | 35.64%  |
| DDR2    | 26        | 6.67%   |
| Unknown | 23        | 5.9%    |
| SDRAM   | 12        | 3.08%   |
| LPDDR4  | 7         | 1.79%   |
| DDR5    | 7         | 1.79%   |
| DDR     | 5         | 1.28%   |
| LPDDR3  | 3         | 0.77%   |
| LPDDR5  | 2         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 211       | 54.38%  |
| DIMM         | 153       | 39.43%  |
| Row Of Chips | 20        | 5.15%   |
| Chip         | 3         | 0.77%   |
| FB-DIMM      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 140       | 32.48%  |
| 4096  | 139       | 32.25%  |
| 2048  | 75        | 17.4%   |
| 16384 | 47        | 10.9%   |
| 1024  | 20        | 4.64%   |
| 32768 | 8         | 1.86%   |
| 512   | 2         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 88        | 20.05%  |
| 3200    | 62        | 14.12%  |
| 2667    | 58        | 13.21%  |
| 1333    | 39        | 8.88%   |
| 2400    | 29        | 6.61%   |
| 800     | 17        | 3.87%   |
| 667     | 16        | 3.64%   |
| 2133    | 15        | 3.42%   |
| 3600    | 14        | 3.19%   |
| 1334    | 14        | 3.19%   |
| 1067    | 11        | 2.51%   |
| Unknown | 9         | 2.05%   |
| 4800    | 5         | 1.14%   |
| 3400    | 5         | 1.14%   |
| 3266    | 5         | 1.14%   |
| 4199    | 4         | 0.91%   |
| 2048    | 4         | 0.91%   |
| 1867    | 4         | 0.91%   |
| 3466    | 3         | 0.68%   |
| 2666    | 3         | 0.68%   |
| 1866    | 3         | 0.68%   |
| 400     | 3         | 0.68%   |
| 6400    | 2         | 0.46%   |
| 4267    | 2         | 0.46%   |
| 3733    | 2         | 0.46%   |
| 3000    | 2         | 0.46%   |
| 2933    | 2         | 0.46%   |
| 1648    | 2         | 0.46%   |
| 975     | 2         | 0.46%   |
| 533     | 2         | 0.46%   |
| 5600    | 1         | 0.23%   |
| 5200    | 1         | 0.23%   |
| 4333    | 1         | 0.23%   |
| 3666    | 1         | 0.23%   |
| 3533    | 1         | 0.23%   |
| 3334    | 1         | 0.23%   |
| 3333    | 1         | 0.23%   |
| 3151    | 1         | 0.23%   |
| 2800    | 1         | 0.23%   |
| 2000    | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 14        | 51.85%  |
| Canon                 | 5         | 18.52%  |
| Samsung Electronics   | 3         | 11.11%  |
| Seiko Epson           | 2         | 7.41%   |
| Lexmark International | 2         | 7.41%   |
| Xerox                 | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP LaserJet 1018                           | 3         | 11.11%  |
| Seiko Epson L365 Series                    | 2         | 7.41%   |
| HP LaserJet 1010                           | 2         | 7.41%   |
| Xerox Phaser 3140 and 3155                 | 1         | 3.7%    |
| Samsung SCX-4623 Series                    | 1         | 3.7%    |
| Samsung SCX-3400 Series                    | 1         | 3.7%    |
| Samsung M2070 Series                       | 1         | 3.7%    |
| Lexmark International Lexmark MS312dn      | 1         | 3.7%    |
| Lexmark International InkJet Color Printer | 1         | 3.7%    |
| HP LaserJet P2015 series                   | 1         | 3.7%    |
| HP LaserJet P2014                          | 1         | 3.7%    |
| HP LaserJet P1005                          | 1         | 3.7%    |
| HP LaserJet M14-M17                        | 1         | 3.7%    |
| HP LaserJet M101-M106                      | 1         | 3.7%    |
| HP LaserJet CP 1025nw                      | 1         | 3.7%    |
| HP LaserJet 1200                           | 1         | 3.7%    |
| HP LaserJet 1020                           | 1         | 3.7%    |
| HP DeskJet 845c                            | 1         | 3.7%    |
| Canon LBP810                               | 1         | 3.7%    |
| Canon LBP6030w/6018w                       | 1         | 3.7%    |
| Canon LBP2900                              | 1         | 3.7%    |
| Canon iP7200 series                        | 1         | 3.7%    |
| Canon CanoScan LiDE 300                    | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 9         | 69.23%  |
| Ultima Electronics | 2         | 15.38%  |
| Mustek Systems     | 1         | 7.69%   |
| Hewlett-Packard    | 1         | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 15.38%  |
| Canon CanoScan LiDE 210                                                               | 2         | 15.38%  |
| Canon CanoScan LiDE 110                                                               | 2         | 15.38%  |
| Canon CanoScan LiDE 100                                                               | 2         | 15.38%  |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 7.69%   |
| HP ScanJet 2200c                                                                      | 1         | 7.69%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 1         | 7.69%   |
| Canon CanoScan LIDE 25                                                                | 1         | 7.69%   |
| Canon CanoScan LiDE 120                                                               | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 104       | 23.96%  |
| IMC Networks                           | 53        | 12.21%  |
| Realtek Semiconductor                  | 34        | 7.83%   |
| Microdia                               | 34        | 7.83%   |
| Logitech                               | 25        | 5.76%   |
| Quanta                                 | 23        | 5.3%    |
| Bison Electronics                      | 22        | 5.07%   |
| Sunplus Innovation Technology          | 19        | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 4.38%   |
| Suyin                                  | 17        | 3.92%   |
| Syntek                                 | 15        | 3.46%   |
| Apple                                  | 10        | 2.3%    |
| KYE Systems (Mouse Systems)            | 8         | 1.84%   |
| Lite-On Technology                     | 7         | 1.61%   |
| Acer                                   | 6         | 1.38%   |
| Silicon Motion                         | 3         | 0.69%   |
| Luxvisions Innotech Limited            | 3         | 0.69%   |
| Lenovo                                 | 3         | 0.69%   |
| Importek                               | 3         | 0.69%   |
| ALi                                    | 3         | 0.69%   |
| Alcor Micro                            | 3         | 0.69%   |
| Ricoh                                  | 2         | 0.46%   |
| Hewlett-Packard                        | 2         | 0.46%   |
| Aveo Technology                        | 2         | 0.46%   |
| Z-Star Microelectronics                | 1         | 0.23%   |
| Xiaomi                                 | 1         | 0.23%   |
| Sony                                   | 1         | 0.23%   |
| Samsung Electronics                    | 1         | 0.23%   |
| OmniVision Technologies                | 1         | 0.23%   |
| Nokia Mobile Phones                    | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |
| Generalplus Technology                 | 1         | 0.23%   |
| GEMBIRD                                | 1         | 0.23%   |
| DigiTech                               | 1         | 0.23%   |
| Cubeternet                             | 1         | 0.23%   |
| Asuscom Network                        | 1         | 0.23%   |
| Arkmicro Technologies                  | 1         | 0.23%   |
| ARC International                      | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 25        | 5.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 19        | 4.37%   |
| Realtek Integrated_Webcam_HD                        | 12        | 2.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 2.76%   |
| Syntek Integrated Camera                            | 10        | 2.3%    |
| Microdia Integrated_Webcam_HD                       | 9         | 2.07%   |
| IMC Networks Integrated Camera                      | 9         | 2.07%   |
| Bison Integrated Camera                             | 9         | 2.07%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 1.84%   |
| Logitech Webcam C270                                | 7         | 1.61%   |
| Microdia Camera                                     | 6         | 1.38%   |
| Chicony VGA Webcam                                  | 6         | 1.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 5         | 1.15%   |
| Quanta VGA WebCam                                   | 5         | 1.15%   |
| Quanta HD WebCam                                    | 5         | 1.15%   |
| Chicony TOSHIBA Web Camera - HD                     | 5         | 1.15%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 1.15%   |
| Chicony HP Webcam                                   | 5         | 1.15%   |
| Chicony EasyCamera                                  | 5         | 1.15%   |
| Syntek EasyCamera                                   | 4         | 0.92%   |
| Realtek USB Camera                                  | 4         | 0.92%   |
| Realtek Lenovo EasyCamera                           | 4         | 0.92%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.92%   |
| Microdia Integrated Webcam                          | 4         | 0.92%   |
| Logitech Webcam C170                                | 4         | 0.92%   |
| IMC Networks EasyCamera                             | 4         | 0.92%   |
| Chicony HP HD Camera                                | 4         | 0.92%   |
| Chicony HD User Facing                              | 4         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 0.92%   |
| Apple Built-in iSight                               | 4         | 0.92%   |
| Sunplus Asus Webcam                                 | 3         | 0.69%   |
| Realtek Integrated Webcam HD                        | 3         | 0.69%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 0.69%   |
| KYE Systems (Mouse Systems) FaceCam 1000X           | 3         | 0.69%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 0.69%   |
| Chicony USB 2.0 Camera                              | 3         | 0.69%   |
| Chicony Integrated HP HD Webcam                     | 3         | 0.69%   |
| Chicony HP Truevision HD                            | 3         | 0.69%   |
| Chicony HD WebCam                                   | 3         | 0.69%   |
| Chicony 1.3M HD WebCam                              | 3         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 35.71%  |
| Synaptics                  | 15        | 21.43%  |
| Shenzhen Goodix Technology | 12        | 17.14%  |
| AuthenTec                  | 6         | 8.57%   |
| Upek                       | 4         | 5.71%   |
| Elan Microelectronics      | 4         | 5.71%   |
| LighTuning Technology      | 2         | 2.86%   |
| STMicroelectronics         | 1         | 1.43%   |
| Microsoft                  | 1         | 1.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 12.86%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 8.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 8.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 7.14%   |
| Synaptics  WBDI                                                            | 4         | 5.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 4.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 4.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.29%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 4.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.86%   |
| Synaptics WBDI                                                             | 2         | 2.86%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.86%   |
| AuthenTec AES2810                                                          | 2         | 2.86%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.43%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.43%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.43%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.43%   |
| Synaptics UWP WBDI                                                         | 1         | 1.43%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.43%   |
| Microsoft Fingerprint Reader                                               | 1         | 1.43%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.43%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.43%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.43%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 15        | 31.25%  |
| Alcor Micro               | 12        | 25%     |
| Gemalto (was Gemplus)     | 10        | 20.83%  |
| OmniKey                   | 3         | 6.25%   |
| Upek                      | 2         | 4.17%   |
| O2 Micro                  | 2         | 4.17%   |
| Lenovo                    | 2         | 4.17%   |
| Precise Biometrics        | 1         | 2.08%   |
| Fujitsu Siemens Computers | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 10        | 20.83%  |
| Broadcom 5880                                                                | 5         | 10.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 8.33%   |
| Broadcom 58200                                                               | 4         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4.17%   |
| Precise Biometrics 200 MC FingerPrint and SmartCard Reader                   | 1         | 2.08%   |
| OmniKey CardMan 4321                                                         | 1         | 2.08%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 2.08%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 2.08%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 555       | 72.45%  |
| 1     | 172       | 22.45%  |
| 2     | 32        | 4.18%   |
| 4     | 3         | 0.39%   |
| 3     | 3         | 0.39%   |
| 8     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 27.67%  |
| Graphics card            | 63        | 24.9%   |
| Chipcard                 | 43        | 17%     |
| Net/wireless             | 27        | 10.67%  |
| Multimedia controller    | 10        | 3.95%   |
| Communication controller | 8         | 3.16%   |
| Bluetooth                | 7         | 2.77%   |
| Sound                    | 6         | 2.37%   |
| Camera                   | 6         | 2.37%   |
| Card reader              | 4         | 1.58%   |
| Unassigned class         | 2         | 0.79%   |
| Net/ethernet             | 2         | 0.79%   |
| Modem                    | 2         | 0.79%   |
| Storage/ide              | 1         | 0.4%    |
| Storage                  | 1         | 0.4%    |
| Dvb card                 | 1         | 0.4%    |

