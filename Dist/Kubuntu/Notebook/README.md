Kubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 2855

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Carbon Sys... | Iridium 14                  | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | X510UAR                     | [d96138627b](https://linux-hardware.org/?probe=d96138627b) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| HP            | 630                         | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Unknown       | Unknown                     | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| HP            | EliteBook 6930p             | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| Acer          | Aspire A515-45              | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Acer          | Aspire A515-57              | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Dell          | Vostro 15-3568              | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| MSI           | Modern 15 A5M               | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | Vostro 5620                 | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Avell High... | C62 MOB                     | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| Dell          | Latitude E6420              | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| System76      | Gazelle                     | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Acer          | Aspire A515-46              | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| Dell          | Inspiron 5593               | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Dell          | Latitude 5491               | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Dell          | Vostro 1014                 | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Notebook                    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Dell          | Inspiron 5570               | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| HP            | Pavilion g7                 | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Dell          | G3 3779                     | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e7152e6cb3](https://linux-hardware.org/?probe=e7152e6cb3) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a30ec58d99](https://linux-hardware.org/?probe=a30ec58d99) | Nov 16, 2022 |
| Dell          | Latitude E7250              | [907a7245b4](https://linux-hardware.org/?probe=907a7245b4) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Dell          | Precision 7510              | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ffa33ab238](https://linux-hardware.org/?probe=ffa33ab238) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a72c604f03](https://linux-hardware.org/?probe=a72c604f03) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8ba7f1aa17](https://linux-hardware.org/?probe=8ba7f1aa17) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Acer          | Aspire 5750                 | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Dell          | Latitude E6320              | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| Acer          | Aspire 5732Z                | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| HP            | 470 G8 Notebook PC          | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Haier         | A1420EM                     | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Latitude E6420              | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| HP            | Compaq 15                   | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | Compaq 15                   | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| Intel         | W7645                       | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Apple         | MacBookPro9,1               | [08db9e8d75](https://linux-hardware.org/?probe=08db9e8d75) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | N56VZ                       | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| ASUSTek       | K93SV                       | [541a21ceb8](https://linux-hardware.org/?probe=541a21ceb8) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| Dell          | Latitude E5400              | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| Lenovo        | G50-45 80E3                 | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | Latitude 7430               | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| Dell          | Precision M4800             | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Dell          | Precision M4800             | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| HP            | 255 G8 Notebook PC          | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [d496e01f0e](https://linux-hardware.org/?probe=d496e01f0e) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| ASUSTek       | UX51VZA                     | [e93c1732ec](https://linux-hardware.org/?probe=e93c1732ec) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Dell          | Latitude E6400              | [8517e82248](https://linux-hardware.org/?probe=8517e82248) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| HP            | ProBook 4540s               | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Acer          | Nitro AN515-57              | [bdc4179004](https://linux-hardware.org/?probe=bdc4179004) | Aug 21, 2022 |
| HP            | ProBook 6570b               | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Timi          | TM1709                      | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | ProBook 6570b               | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Lenovo        | V15-ADA 82C7                | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| Dell          | Precision 7530              | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| VIT           | P2402                       | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Apple         | MacBookPro11,1              | [9814fa3bca](https://linux-hardware.org/?probe=9814fa3bca) | Aug 03, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | Inspiron 15-3567            | [3e40b1abe6](https://linux-hardware.org/?probe=3e40b1abe6) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | G50-45 80E3                 | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Latitude E5520              | [e04cdad7b7](https://linux-hardware.org/?probe=e04cdad7b7) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| HP            | G42                         | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | 620                         | [cc970fdd77](https://linux-hardware.org/?probe=cc970fdd77) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| GPU Compan... | GWTC116-2                   | [183f3e59fb](https://linux-hardware.org/?probe=183f3e59fb) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Acer          | Nitro AN515-57              | [10d0c2a6ea](https://linux-hardware.org/?probe=10d0c2a6ea) | Jun 24, 2022 |
| Dell          | Latitude XT3                | [87377f03e2](https://linux-hardware.org/?probe=87377f03e2) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Clevo         | Modified by dsanke          | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| ASUSTek       | GR8                         | [90afe7bdd7](https://linux-hardware.org/?probe=90afe7bdd7) | Jun 20, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Packard Be... | H17HV                       | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Acer          | Aspire E1-570G              | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | 620                         | [fe1a420f17](https://linux-hardware.org/?probe=fe1a420f17) | Jun 13, 2022 |
| HP            | EliteBook 2570p             | [8b6f8e8952](https://linux-hardware.org/?probe=8b6f8e8952) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 1428               | [e47c98983f](https://linux-hardware.org/?probe=e47c98983f) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Dell          | Inspiron 3521               | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| HP            | Pavilion dv7                | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Pavilion dv7                | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| HP            | 620                         | [1adcb99573](https://linux-hardware.org/?probe=1adcb99573) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [42aaad44bc](https://linux-hardware.org/?probe=42aaad44bc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Toshiba       | Satellite C75D-A            | [a5aee20b56](https://linux-hardware.org/?probe=a5aee20b56) | Jun 06, 2022 |
| Positivo      | Q464C                       | [e00b91e529](https://linux-hardware.org/?probe=e00b91e529) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| Dell          | Latitude E5470              | [e858488f6f](https://linux-hardware.org/?probe=e858488f6f) | Jun 03, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [0436371728](https://linux-hardware.org/?probe=0436371728) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [20d1a7e37b](https://linux-hardware.org/?probe=20d1a7e37b) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Vostro 5481                 | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| Google        | Coral                       | [c517ad03c1](https://linux-hardware.org/?probe=c517ad03c1) | May 30, 2022 |
| Dell          | Precision 7710              | [f24e29d104](https://linux-hardware.org/?probe=f24e29d104) | May 30, 2022 |
| Dell          | Precision 7710              | [1bae5a0bf0](https://linux-hardware.org/?probe=1bae5a0bf0) | May 30, 2022 |
| ASUSTek       | X540LA                      | [57e0b15d17](https://linux-hardware.org/?probe=57e0b15d17) | May 30, 2022 |
| HP            | Pavilion g4                 | [39cdebfff4](https://linux-hardware.org/?probe=39cdebfff4) | May 29, 2022 |
| Medion        | S6445 MD61489               | [a933286b06](https://linux-hardware.org/?probe=a933286b06) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Aspire M5-581TG             | [c6ffc6271c](https://linux-hardware.org/?probe=c6ffc6271c) | May 23, 2022 |
| HP            | 15                          | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| Acer          | Aspire A515-55              | [52dce4d0c3](https://linux-hardware.org/?probe=52dce4d0c3) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | [06ec4e94a2](https://linux-hardware.org/?probe=06ec4e94a2) | May 22, 2022 |
| Acer          | Aspire E5-573               | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [8266843e53](https://linux-hardware.org/?probe=8266843e53) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | Inspiron 5593               | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | Predator PH315-53           | [eb5d08e402](https://linux-hardware.org/?probe=eb5d08e402) | May 18, 2022 |
| Lenovo        | G780 20138                  | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [2ba7ecdb55](https://linux-hardware.org/?probe=2ba7ecdb55) | May 10, 2022 |
| Dell          | Latitude E6540              | [a5bb9f2b58](https://linux-hardware.org/?probe=a5bb9f2b58) | May 10, 2022 |
| HP            | ProBook 470 G1              | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| Acer          | Nitro AN515-45              | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 742       | 35.67%  |
| Kubuntu 22.04   | 446       | 21.44%  |
| Kubuntu 22.10   | 153       | 7.36%   |
| Kubuntu 21.10   | 151       | 7.26%   |
| Kubuntu 20.10   | 141       | 6.78%   |
| Kubuntu 21.04   | 126       | 6.06%   |
| Kubuntu 19.10   | 105       | 5.05%   |
| Kubuntu 18.04   | 102       | 4.9%    |
| Kubuntu 11      | 45        | 2.16%   |
| Kubuntu 23.04   | 23        | 1.11%   |
| Kubuntu 11.1    | 18        | 0.87%   |
| Kubuntu 19.04   | 9         | 0.43%   |
| Kubuntu 2.0     | 4         | 0.19%   |
| Kubuntu 16.04   | 4         | 0.19%   |
| Kubuntu 18.10   | 3         | 0.14%   |
| Kubuntu         | 3         | 0.14%   |
| Kubuntu 14.04   | 2         | 0.1%    |
| Kubuntu 20.08.3 | 1         | 0.05%   |
| Kubuntu 17.10   | 1         | 0.05%   |
| Kubuntu 17.04   | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Kubuntu | 2003      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 55        | 2.42%   |
| 5.15.0-52-generic | 51        | 2.25%   |
| 5.15.0-56-generic | 43        | 1.9%    |
| 5.19.0-35-generic | 38        | 1.67%   |
| 5.4.0-52-generic  | 35        | 1.54%   |
| 5.13.0-39-generic | 35        | 1.54%   |
| 5.4.0-48-generic  | 34        | 1.5%    |
| 5.15.0-48-generic | 30        | 1.32%   |
| 5.19.0-26-generic | 28        | 1.23%   |
| 5.15.0-58-generic | 28        | 1.23%   |
| 5.4.0-58-generic  | 27        | 1.19%   |
| 5.13.0-28-generic | 27        | 1.19%   |
| 5.15.0-46-generic | 26        | 1.15%   |
| 5.13.0-30-generic | 26        | 1.15%   |
| 5.19.0-23-generic | 25        | 1.1%    |
| 5.11.0-25-generic | 25        | 1.1%    |
| 5.4.0-40-generic  | 24        | 1.06%   |
| 5.19.0-38-generic | 24        | 1.06%   |
| 5.15.0-53-generic | 24        | 1.06%   |
| 5.3.0-40-generic  | 22        | 0.97%   |
| 5.19.0-31-generic | 22        | 0.97%   |
| 5.15.0-60-generic | 21        | 0.93%   |
| 5.15.0-47-generic | 21        | 0.93%   |
| 5.15.0-43-generic | 21        | 0.93%   |
| 5.11.0-37-generic | 21        | 0.93%   |
| 5.15.0-41-generic | 20        | 0.88%   |
| 5.4.0-47-generic  | 19        | 0.84%   |
| 5.4.0-29-generic  | 19        | 0.84%   |
| 5.13.0-22-generic | 19        | 0.84%   |
| 5.4.0-37-generic  | 18        | 0.79%   |
| 5.13.0-27-generic | 18        | 0.79%   |
| 5.4.0-65-generic  | 17        | 0.75%   |
| 5.3.0-42-generic  | 17        | 0.75%   |
| 5.13.0-40-generic | 17        | 0.75%   |
| 5.11.0-38-generic | 17        | 0.75%   |
| 5.8.0-63-generic  | 16        | 0.71%   |
| 5.8.0-48-generic  | 16        | 0.71%   |
| 5.8.0-44-generic  | 16        | 0.71%   |
| 5.15.0-50-generic | 16        | 0.71%   |
| 5.15.0-25-generic | 16        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 479       | 22.59%  |
| 5.15.0  | 423       | 19.95%  |
| 5.13.0  | 258       | 12.17%  |
| 5.8.0   | 220       | 10.38%  |
| 5.11.0  | 185       | 8.73%   |
| 5.19.0  | 182       | 8.58%   |
| 5.3.0   | 129       | 6.08%   |
| 4.15.0  | 38        | 1.79%   |
| 5.0.0   | 17        | 0.8%    |
| 6.2.0   | 16        | 0.75%   |
| 5.10.0  | 13        | 0.61%   |
| 5.17.0  | 11        | 0.52%   |
| 5.6.0   | 7         | 0.33%   |
| 5.14.0  | 7         | 0.33%   |
| 6.0.0   | 6         | 0.28%   |
| 6.1.0   | 5         | 0.24%   |
| 6.0.9   | 4         | 0.19%   |
| 5.7.0   | 4         | 0.19%   |
| 4.4.0   | 4         | 0.19%   |
| 4.18.0  | 4         | 0.19%   |
| 5.12.0  | 3         | 0.14%   |
| 6.2.2   | 2         | 0.09%   |
| 6.1.8   | 2         | 0.09%   |
| 6.1.12  | 2         | 0.09%   |
| 6.0.7   | 2         | 0.09%   |
| 5.9.10  | 2         | 0.09%   |
| 5.9.0   | 2         | 0.09%   |
| 5.19.5  | 2         | 0.09%   |
| 5.18.10 | 2         | 0.09%   |
| 5.15.5  | 2         | 0.09%   |
| 5.15.34 | 2         | 0.09%   |
| 5.13.1  | 2         | 0.09%   |
| 5.12.8  | 2         | 0.09%   |
| 4.10.0  | 2         | 0.09%   |
| 6.2.8   | 1         | 0.05%   |
| 6.2.5   | 1         | 0.05%   |
| 6.2.10  | 1         | 0.05%   |
| 6.1.9   | 1         | 0.05%   |
| 6.1.7   | 1         | 0.05%   |
| 6.1.6   | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 482       | 22.78%  |
| 5.15    | 433       | 20.46%  |
| 5.13    | 264       | 12.48%  |
| 5.8     | 228       | 10.78%  |
| 5.11    | 189       | 8.93%   |
| 5.19    | 186       | 8.79%   |
| 5.3     | 130       | 6.14%   |
| 4.15    | 38        | 1.8%    |
| 6.2     | 21        | 0.99%   |
| 5.10    | 17        | 0.8%    |
| 5.0     | 17        | 0.8%    |
| 6.1     | 14        | 0.66%   |
| 5.17    | 14        | 0.66%   |
| 6.0     | 13        | 0.61%   |
| 5.14    | 13        | 0.61%   |
| 5.12    | 9         | 0.43%   |
| 5.6     | 8         | 0.38%   |
| 5.9     | 7         | 0.33%   |
| 5.7     | 6         | 0.28%   |
| 5.18    | 5         | 0.24%   |
| 5.16    | 5         | 0.24%   |
| 4.18    | 5         | 0.24%   |
| 4.4     | 4         | 0.19%   |
| 5.5     | 3         | 0.14%   |
| 4.10    | 2         | 0.09%   |
| 5.1     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2000      | 99.85%  |
| i686   | 3         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 1519      | 74.61%  |
| KDE        | 488       | 23.97%  |
| GNOME      | 11        | 0.54%   |
| Cinnamon   | 4         | 0.2%    |
| MATE       | 3         | 0.15%   |
| Budgie     | 3         | 0.15%   |
| KDE4       | 2         | 0.1%    |
| XFCE       | 1         | 0.05%   |
| X-Cinnamon | 1         | 0.05%   |
| LXQt       | 1         | 0.05%   |
| i3         | 1         | 0.05%   |
| GNUstep    | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1923      | 95.2%   |
| Wayland | 82        | 4.06%   |
| Tty     | 15        | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1218      | 59.88%  |
| Unknown | 683       | 33.58%  |
| GDM     | 59        | 2.9%    |
| GDM3    | 35        | 1.72%   |
| LightDM | 26        | 1.28%   |
| TDM     | 11        | 0.54%   |
| SLiM    | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 852       | 42.18%  |
| de_DE   | 149       | 7.38%   |
| ru_RU   | 107       | 5.3%    |
| pt_BR   | 95        | 4.7%    |
| it_IT   | 89        | 4.41%   |
| fr_FR   | 86        | 4.26%   |
| en_GB   | 82        | 4.06%   |
| en_IN   | 54        | 2.67%   |
| en_CA   | 46        | 2.28%   |
| es_ES   | 45        | 2.23%   |
| Unknown | 43        | 2.13%   |
| pl_PL   | 36        | 1.78%   |
| en_AU   | 30        | 1.49%   |
| C       | 18        | 0.89%   |
| hu_HU   | 16        | 0.79%   |
| es_MX   | 16        | 0.79%   |
| cs_CZ   | 14        | 0.69%   |
| tr_TR   | 13        | 0.64%   |
| ru_UA   | 13        | 0.64%   |
| en_ZA   | 12        | 0.59%   |
| nl_NL   | 10        | 0.5%    |
| en_NZ   | 10        | 0.5%    |
| en_IE   | 9         | 0.45%   |
| zh_CN   | 8         | 0.4%    |
| es_AR   | 7         | 0.35%   |
| de_CH   | 7         | 0.35%   |
| sv_SE   | 6         | 0.3%    |
| pt_PT   | 6         | 0.3%    |
| fr_BE   | 6         | 0.3%    |
| es_VE   | 6         | 0.3%    |
| es_CO   | 6         | 0.3%    |
| es_CL   | 6         | 0.3%    |
| ca_ES   | 6         | 0.3%    |
| sk_SK   | 5         | 0.25%   |
| nl_BE   | 5         | 0.25%   |
| fr_CH   | 5         | 0.25%   |
| en_SG   | 5         | 0.25%   |
| de_AT   | 5         | 0.25%   |
| ro_RO   | 4         | 0.2%    |
| en_PH   | 4         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1250      | 61.46%  |
| BIOS | 784       | 38.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1843      | 91.55%  |
| Btrfs   | 78        | 3.87%   |
| Overlay | 53        | 2.63%   |
| Xfs     | 13        | 0.65%   |
| Zfs     | 10        | 0.5%    |
| Unknown | 6         | 0.3%    |
| Tmpfs   | 5         | 0.25%   |
| Ext2    | 3         | 0.15%   |
| Ext3    | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1068      | 52.66%  |
| Unknown | 801       | 39.5%   |
| MBR     | 159       | 7.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1815      | 90.16%  |
| Yes       | 198       | 9.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1248      | 61.9%   |
| Yes       | 768       | 38.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 460       | 22.97%  |
| Dell                   | 371       | 18.52%  |
| Hewlett-Packard        | 351       | 17.52%  |
| ASUSTek Computer       | 199       | 9.94%   |
| Acer                   | 149       | 7.44%   |
| MSI                    | 57        | 2.85%   |
| HUAWEI                 | 40        | 2%      |
| Samsung Electronics    | 39        | 1.95%   |
| Apple                  | 27        | 1.35%   |
| Toshiba                | 25        | 1.25%   |
| Notebook               | 23        | 1.15%   |
| Sony                   | 20        | 1%      |
| TUXEDO                 | 19        | 0.95%   |
| Google                 | 15        | 0.75%   |
| Unknown                | 14        | 0.7%    |
| Timi                   | 13        | 0.65%   |
| Gigabyte Technology    | 12        | 0.6%    |
| Alienware              | 11        | 0.55%   |
| Positivo               | 10        | 0.5%    |
| System76               | 7         | 0.35%   |
| Chuwi                  | 7         | 0.35%   |
| PC Specialist          | 6         | 0.3%    |
| Medion                 | 6         | 0.3%    |
| Intel                  | 6         | 0.3%    |
| GPU Company            | 6         | 0.3%    |
| Fujitsu                | 6         | 0.3%    |
| Razer                  | 5         | 0.25%   |
| Panasonic              | 5         | 0.25%   |
| Packard Bell           | 5         | 0.25%   |
| LG Electronics         | 5         | 0.25%   |
| Schenker               | 4         | 0.2%    |
| HONOR                  | 4         | 0.2%    |
| Framework              | 4         | 0.2%    |
| Avell High Performance | 4         | 0.2%    |
| Haier                  | 3         | 0.15%   |
| Fujitsu Siemens        | 3         | 0.15%   |
| Digma                  | 3         | 0.15%   |
| Clevo                  | 3         | 0.15%   |
| Thomson                | 2         | 0.1%    |
| Standard               | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 25        | 1.25%   |
| HP Notebook                     | 10        | 0.5%    |
| HP Pavilion g6                  | 9         | 0.45%   |
| HP Pavilion dv6                 | 9         | 0.45%   |
| Dell XPS 15 9560                | 9         | 0.45%   |
| HUAWEI NBLK-WAX9X               | 8         | 0.4%    |
| HP Pavilion dv7                 | 7         | 0.35%   |
| Dell XPS 15 9570                | 7         | 0.35%   |
| HUAWEI HVY-WXX9                 | 6         | 0.3%    |
| HP Pavilion 15                  | 6         | 0.3%    |
| HP EliteBook 840 G5             | 6         | 0.3%    |
| HP EliteBook 840 G3             | 6         | 0.3%    |
| HP EliteBook 840 G6             | 5         | 0.25%   |
| HP 255 G8 Notebook PC           | 5         | 0.25%   |
| GPU Company GWTC116-2           | 5         | 0.25%   |
| Dell XPS 15 7590                | 5         | 0.25%   |
| Dell XPS 13 9310                | 5         | 0.25%   |
| Dell Latitude E6540             | 5         | 0.25%   |
| Dell Latitude 5480              | 5         | 0.25%   |
| Dell Inspiron 5570              | 5         | 0.25%   |
| Dell Inspiron 15-3567           | 5         | 0.25%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 4         | 0.2%    |
| Lenovo Legion Y530-15ICH 81FV   | 4         | 0.2%    |
| Lenovo IdeaPad S145-15API 81V7  | 4         | 0.2%    |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 4         | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81DE   | 4         | 0.2%    |
| Lenovo G50-70 20351             | 4         | 0.2%    |
| HUAWEI KLVL-WXX9                | 4         | 0.2%    |
| HUAWEI CREM-WXX9                | 4         | 0.2%    |
| HP ProBook 6470b                | 4         | 0.2%    |
| HP Pavilion Notebook            | 4         | 0.2%    |
| HP Laptop 15s-eq0xxx            | 4         | 0.2%    |
| HP Laptop 15-da0xxx             | 4         | 0.2%    |
| HP EliteBook 845 G7 Notebook PC | 4         | 0.2%    |
| HP EliteBook 2570p              | 4         | 0.2%    |
| HP 2000                         | 4         | 0.2%    |
| HP 15                           | 4         | 0.2%    |
| Dell XPS 17 9700                | 4         | 0.2%    |
| Dell XPS 15 9500                | 4         | 0.2%    |
| Dell Vostro 5481                | 4         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 243       | 12.13%  |
| Dell Latitude       | 127       | 6.34%   |
| Lenovo IdeaPad      | 96        | 4.79%   |
| Dell Inspiron       | 94        | 4.69%   |
| Acer Aspire         | 92        | 4.59%   |
| HP Pavilion         | 81        | 4.04%   |
| Dell XPS            | 62        | 3.1%    |
| HP ProBook          | 59        | 2.95%   |
| HP EliteBook        | 53        | 2.65%   |
| HP Laptop           | 52        | 2.6%    |
| ASUS VivoBook       | 44        | 2.2%    |
| Dell Precision      | 34        | 1.7%    |
| Dell Vostro         | 26        | 1.3%    |
| Unknown             | 25        | 1.25%   |
| Acer Nitro          | 24        | 1.2%    |
| Lenovo Legion       | 23        | 1.15%   |
| Toshiba Satellite   | 21        | 1.05%   |
| Lenovo ThinkBook    | 21        | 1.05%   |
| ASUS ASUS           | 19        | 0.95%   |
| Acer Swift          | 17        | 0.85%   |
| HP ENVY             | 14        | 0.7%    |
| ASUS Zenbook        | 14        | 0.7%    |
| ASUS ROG            | 14        | 0.7%    |
| HP ZBook            | 13        | 0.65%   |
| ASUS TUF            | 11        | 0.55%   |
| HP Notebook         | 10        | 0.5%    |
| HP 255              | 9         | 0.45%   |
| Dell G3             | 9         | 0.45%   |
| HUAWEI NBLK-WAX9X   | 8         | 0.4%    |
| HP 250              | 8         | 0.4%    |
| MSI Prestige        | 7         | 0.35%   |
| Lenovo Yoga         | 7         | 0.35%   |
| HP OMEN             | 7         | 0.35%   |
| MSI Modern          | 6         | 0.3%    |
| HUAWEI HVY-WXX9     | 6         | 0.3%    |
| HP 15               | 6         | 0.3%    |
| Dell System         | 6         | 0.3%    |
| Acer Predator       | 6         | 0.3%    |
| TUXEDO InfinityBook | 5         | 0.25%   |
| Razer Blade         | 5         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 273       | 13.63%  |
| 2020 | 271       | 13.53%  |
| 2021 | 218       | 10.88%  |
| 2018 | 186       | 9.29%   |
| 2017 | 139       | 6.94%   |
| 2012 | 135       | 6.74%   |
| 2011 | 127       | 6.34%   |
| 2013 | 123       | 6.14%   |
| 2014 | 122       | 6.09%   |
| 2016 | 99        | 4.94%   |
| 2022 | 84        | 4.19%   |
| 2015 | 74        | 3.69%   |
| 2008 | 54        | 2.7%    |
| 2010 | 49        | 2.45%   |
| 2009 | 28        | 1.4%    |
| 2007 | 17        | 0.85%   |
| 2023 | 4         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2003      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1778      | 87.93%  |
| Enabled  | 244       | 12.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1982      | 98.95%  |
| Yes  | 21        | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 578       | 28.71%  |
| 16.01-24.0  | 466       | 23.15%  |
| 8.01-16.0   | 383       | 19.03%  |
| 3.01-4.0    | 278       | 13.81%  |
| 32.01-64.0  | 188       | 9.34%   |
| 1.01-2.0    | 40        | 1.99%   |
| 64.01-256.0 | 35        | 1.74%   |
| 24.01-32.0  | 30        | 1.49%   |
| 2.01-3.0    | 15        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 585       | 27.16%  |
| 1.01-2.0   | 511       | 23.72%  |
| 4.01-8.0   | 471       | 21.87%  |
| 3.01-4.0   | 370       | 17.18%  |
| 8.01-16.0  | 151       | 7.01%   |
| 0.51-1.0   | 44        | 2.04%   |
| 16.01-24.0 | 16        | 0.74%   |
| 24.01-32.0 | 4         | 0.19%   |
| 32.01-64.0 | 2         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1414      | 69.66%  |
| 2      | 526       | 25.91%  |
| 3      | 64        | 3.15%   |
| 4      | 16        | 0.79%   |
| 0      | 8         | 0.39%   |
| 6      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1475      | 73.35%  |
| Yes       | 536       | 26.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1569      | 78.18%  |
| No        | 438       | 21.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1985      | 99.1%   |
| No        | 18        | 0.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1687      | 83.64%  |
| No        | 330       | 16.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 329       | 16.4%   |
| Germany      | 206       | 10.27%  |
| Russia       | 145       | 7.23%   |
| Brazil       | 122       | 6.08%   |
| France       | 121       | 6.03%   |
| Italy        | 116       | 5.78%   |
| UK           | 75        | 3.74%   |
| Spain        | 66        | 3.29%   |
| India        | 54        | 2.69%   |
| Poland       | 52        | 2.59%   |
| Canada       | 49        | 2.44%   |
| Netherlands  | 41        | 2.04%   |
| Ukraine      | 35        | 1.74%   |
| Mexico       | 33        | 1.65%   |
| Australia    | 29        | 1.45%   |
| Hungary      | 26        | 1.3%    |
| Belgium      | 25        | 1.25%   |
| Switzerland  | 23        | 1.15%   |
| Indonesia    | 23        | 1.15%   |
| Czechia      | 23        | 1.15%   |
| Turkey       | 22        | 1.1%    |
| Romania      | 15        | 0.75%   |
| Bulgaria     | 15        | 0.75%   |
| Sweden       | 14        | 0.7%    |
| South Africa | 14        | 0.7%    |
| Slovenia     | 14        | 0.7%    |
| China        | 13        | 0.65%   |
| Slovakia     | 12        | 0.6%    |
| Portugal     | 12        | 0.6%    |
| Ireland      | 12        | 0.6%    |
| Denmark      | 12        | 0.6%    |
| Belarus      | 12        | 0.6%    |
| Austria      | 12        | 0.6%    |
| Greece       | 11        | 0.55%   |
| Argentina    | 11        | 0.55%   |
| Croatia      | 10        | 0.5%    |
| Colombia     | 10        | 0.5%    |
| New Zealand  | 9         | 0.45%   |
| Iran         | 9         | 0.45%   |
| Finland      | 9         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 44        | 2.1%    |
| Berlin            | 23        | 1.1%    |
| Milan             | 22        | 1.05%   |
| St Petersburg     | 19        | 0.91%   |
| Paris             | 18        | 0.86%   |
| Madrid            | 17        | 0.81%   |
| Warsaw            | 15        | 0.71%   |
| Sao Paulo         | 12        | 0.57%   |
| Rome              | 12        | 0.57%   |
| Hamburg           | 12        | 0.57%   |
| Cologne           | 12        | 0.57%   |
| Budapest          | 12        | 0.57%   |
| Zurich            | 11        | 0.52%   |
| Sofia             | 11        | 0.52%   |
| Minsk             | 11        | 0.52%   |
| Jakarta           | 10        | 0.48%   |
| Kyiv              | 9         | 0.43%   |
| Frankfurt am Main | 9         | 0.43%   |
| Amsterdam         | 9         | 0.43%   |
| Vienna            | 8         | 0.38%   |
| Sydney            | 8         | 0.38%   |
| Rio de Janeiro    | 8         | 0.38%   |
| Prague            | 8         | 0.38%   |
| Phoenix           | 8         | 0.38%   |
| Dublin            | 8         | 0.38%   |
| Bengaluru         | 8         | 0.38%   |
| Munich            | 7         | 0.33%   |
| Los Angeles       | 7         | 0.33%   |
| Istanbul          | 7         | 0.33%   |
| Birmingham        | 7         | 0.33%   |
| Zagreb            | 6         | 0.29%   |
| Wroclaw           | 6         | 0.29%   |
| Singapore         | 6         | 0.29%   |
| Seattle           | 6         | 0.29%   |
| Montreal          | 6         | 0.29%   |
| Melbourne         | 6         | 0.29%   |
| Marseille         | 6         | 0.29%   |
| Dallas            | 6         | 0.29%   |
| Chennai           | 6         | 0.29%   |
| Cape Town         | 6         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 502       | 662    | 19.45%  |
| WDC                            | 288       | 348    | 11.16%  |
| Seagate                        | 231       | 281    | 8.95%   |
| Toshiba                        | 178       | 220    | 6.9%    |
| Kingston                       | 155       | 175    | 6.01%   |
| SanDisk                        | 151       | 186    | 5.85%   |
| Unknown                        | 124       | 154    | 4.8%    |
| SK hynix                       | 117       | 142    | 4.53%   |
| Intel                          | 108       | 137    | 4.18%   |
| Crucial                        | 98        | 116    | 3.8%    |
| Micron Technology              | 67        | 72     | 2.6%    |
| HGST                           | 67        | 77     | 2.6%    |
| Hitachi                        | 42        | 45     | 1.63%   |
| A-DATA Technology              | 40        | 41     | 1.55%   |
| KIOXIA                         | 39        | 43     | 1.51%   |
| Apple                          | 21        | 27     | 0.81%   |
| LITEON                         | 20        | 21     | 0.77%   |
| China                          | 19        | 26     | 0.74%   |
| SPCC                           | 16        | 17     | 0.62%   |
| Silicon Motion                 | 14        | 17     | 0.54%   |
| Unknown                        | 13        | 14     | 0.5%    |
| PNY                            | 12        | 12     | 0.46%   |
| Phison                         | 12        | 12     | 0.46%   |
| Transcend                      | 10        | 10     | 0.39%   |
| Phison Electronics             | 9         | 9      | 0.35%   |
| LITEONIT                       | 9         | 11     | 0.35%   |
| Intenso                        | 9         | 10     | 0.35%   |
| Micron/Crucial Technology      | 8         | 11     | 0.31%   |
| SSSTC                          | 7         | 7      | 0.27%   |
| JMicron Technology             | 7         | 8      | 0.27%   |
| Apacer                         | 7         | 7      | 0.27%   |
| UMIS                           | 6         | 6      | 0.23%   |
| Goodram                        | 6         | 6      | 0.23%   |
| Corsair                        | 6         | 6      | 0.23%   |
| Union Memory                   | 5         | 5      | 0.19%   |
| Solid State Storage Technology | 5         | 9      | 0.19%   |
| SABRENT                        | 5         | 8      | 0.19%   |
| Patriot                        | 5         | 5      | 0.19%   |
| Netac                          | 5         | 5      | 0.19%   |
| KingSpec                       | 5         | 5      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB    | 35        | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 25        | 0.93%   |
| Samsung SSD 860 EVO 500GB           | 25        | 0.93%   |
| HGST HTS721010A9E630 1TB            | 24        | 0.89%   |
| Toshiba MQ04ABF100 1TB              | 23        | 0.85%   |
| Toshiba MQ01ABD100 1TB              | 23        | 0.85%   |
| Unknown MMC Card  32GB              | 22        | 0.82%   |
| Samsung NVMe SSD Drive 512GB        | 21        | 0.78%   |
| Unknown MMC Card  64GB              | 20        | 0.74%   |
| Kingston SA400S37240G 240GB SSD     | 19        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB     | 15        | 0.56%   |
| Samsung SSD 850 EVO 500GB           | 15        | 0.56%   |
| Samsung SSD 850 EVO 250GB           | 15        | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB      | 14        | 0.52%   |
| Samsung NVMe SSD Drive 1TB          | 14        | 0.52%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 0.52%   |
| Seagate ST2000LM007-1R8174 2TB      | 13        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB        | 13        | 0.48%   |
| SanDisk NVMe SSD Drive 256GB        | 13        | 0.48%   |
| Samsung SSD 860 EVO M.2 500GB       | 13        | 0.48%   |
| Unknown                             | 13        | 0.48%   |
| WDC WD10SPZX-21Z10T0 1TB            | 12        | 0.45%   |
| SK hynix NVMe SSD Drive 512GB       | 12        | 0.45%   |
| SanDisk SSD PLUS 240GB              | 12        | 0.45%   |
| Intel SSDPEKNW512G8 512GB           | 12        | 0.45%   |
| Unknown MMC Card  128GB             | 11        | 0.41%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.41%   |
| Samsung SSD 860 EVO 1TB             | 11        | 0.41%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 11        | 0.41%   |
| Crucial CT500MX500SSD1 500GB        | 11        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB         | 11        | 0.41%   |
| WDC WD10SPZX-24Z10 1TB              | 10        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10        | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB      | 10        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD    | 10        | 0.37%   |
| HGST HTS541010A9E680 1TB            | 10        | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 9         | 0.33%   |
| Samsung SSD 970 EVO Plus 250GB      | 9         | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB        | 9         | 0.33%   |
| WDC WD10SPZX-60Z10T0 1TB            | 8         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 228       | 277    | 36.36%  |
| WDC                 | 155       | 182    | 24.72%  |
| Toshiba             | 101       | 125    | 16.11%  |
| HGST                | 66        | 76     | 10.53%  |
| Hitachi             | 42        | 45     | 6.7%    |
| Samsung Electronics | 12        | 15     | 1.91%   |
| Unknown             | 5         | 7      | 0.8%    |
| JMicron Technology  | 5         | 5      | 0.8%    |
| Fujitsu             | 5         | 7      | 0.8%    |
| Apple               | 4         | 4      | 0.64%   |
| USB3.0              | 1         | 1      | 0.16%   |
| KESU                | 1         | 1      | 0.16%   |
| ipTIME              | 1         | 1      | 0.16%   |
| HGST HTS            | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 235       | 311    | 27.61%  |
| Kingston            | 101       | 114    | 11.87%  |
| SanDisk             | 92        | 112    | 10.81%  |
| Crucial             | 83        | 101    | 9.75%   |
| WDC                 | 41        | 58     | 4.82%   |
| A-DATA Technology   | 22        | 22     | 2.59%   |
| Intel               | 21        | 24     | 2.47%   |
| Toshiba             | 20        | 30     | 2.35%   |
| SK hynix            | 18        | 18     | 2.12%   |
| China               | 18        | 25     | 2.12%   |
| Micron Technology   | 17        | 18     | 2%      |
| LITEON              | 15        | 15     | 1.76%   |
| SPCC                | 13        | 14     | 1.53%   |
| PNY                 | 10        | 10     | 1.18%   |
| Transcend           | 9         | 9      | 1.06%   |
| LITEONIT            | 9         | 11     | 1.06%   |
| Apple               | 9         | 9      | 1.06%   |
| Intenso             | 7         | 8      | 0.82%   |
| Apacer              | 7         | 7      | 0.82%   |
| GOODRAM             | 6         | 6      | 0.71%   |
| Patriot             | 5         | 5      | 0.59%   |
| KingSpec            | 5         | 5      | 0.59%   |
| Dogfish             | 5         | 5      | 0.59%   |
| Netac               | 4         | 4      | 0.47%   |
| Emtec               | 4         | 4      | 0.47%   |
| Corsair             | 4         | 4      | 0.47%   |
| Zheino              | 3         | 5      | 0.35%   |
| TO Exter            | 3         | 3      | 0.35%   |
| Team                | 3         | 3      | 0.35%   |
| External            | 3         | 4      | 0.35%   |
| ASMT                | 3         | 4      | 0.35%   |
| Unknown             | 3         | 3      | 0.35%   |
| Verbatim            | 2         | 3      | 0.24%   |
| Smart               | 2         | 2      | 0.24%   |
| RZX                 | 2         | 3      | 0.24%   |
| Plextor             | 2         | 2      | 0.24%   |
| Mushkin             | 2         | 2      | 0.24%   |
| Lexar               | 2         | 2      | 0.24%   |
| FORESEE             | 2         | 2      | 0.24%   |
| Drevo               | 2         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 914       | 1159   | 37.2%   |
| SSD     | 777       | 1034   | 31.62%  |
| HDD     | 613       | 747    | 24.95%  |
| MMC     | 127       | 155    | 5.17%   |
| Unknown | 26        | 30     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1199      | 1716   | 51.82%  |
| NVMe | 909       | 1151   | 39.28%  |
| MMC  | 127       | 155    | 5.49%   |
| SAS  | 79        | 103    | 3.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 838       | 1096   | 60.86%  |
| 0.51-1.0   | 452       | 571    | 32.82%  |
| 1.01-2.0   | 70        | 92     | 5.08%   |
| 3.01-4.0   | 10        | 11     | 0.73%   |
| 4.01-10.0  | 6         | 10     | 0.44%   |
| 2.01-3.0   | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 598       | 29.02%  |
| 251-500        | 589       | 28.58%  |
| 501-1000       | 383       | 18.58%  |
| 1001-2000      | 167       | 8.1%    |
| 51-100         | 119       | 5.77%   |
| 1-20           | 59        | 2.86%   |
| 21-50          | 57        | 2.77%   |
| 2001-3000      | 41        | 1.99%   |
| More than 3000 | 39        | 1.89%   |
| Unknown        | 9         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 550       | 25.72%  |
| 101-250        | 419       | 19.6%   |
| 21-50          | 374       | 17.49%  |
| 51-100         | 304       | 14.22%  |
| 251-500        | 260       | 12.16%  |
| 501-1000       | 140       | 6.55%   |
| 1001-2000      | 57        | 2.67%   |
| More than 3000 | 16        | 0.75%   |
| 2001-3000      | 9         | 0.42%   |
| Unknown        | 9         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 11     | 3.5%    |
| HGST HTS721010A9E630 1TB                 | 5         | 6      | 3.5%    |
| Toshiba MQ04ABF100 1TB                   | 3         | 3      | 2.1%    |
| Toshiba MQ01ABD100 1TB                   | 3         | 5      | 2.1%    |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 2.1%    |
| Seagate ST1000LM048-2E7172 1TB           | 3         | 3      | 2.1%    |
| Seagate ST1000LM035-1RK172 970GB         | 3         | 3      | 2.1%    |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 2.1%    |
| Hitachi HTS547564A9E384 640GB            | 3         | 3      | 2.1%    |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.1%    |
| SK hynix SC401 SATA 512GB SSD            | 2         | 2      | 1.4%    |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.4%    |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.4%    |
| Seagate ST2000LM007-1R8174 2TB           | 2         | 2      | 1.4%    |
| SanDisk SSD PLUS 240GB                   | 2         | 2      | 1.4%    |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.4%    |
| Hitachi HTS545050B9A300 500GB            | 2         | 2      | 1.4%    |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 1.4%    |
| Crucial CT500P1SSD8 500GB                | 2         | 2      | 1.4%    |
| Zheino CHN mSATA02M 256 256GB SSD        | 1         | 2      | 0.7%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1      | 0.7%    |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.7%    |
| WDC WD6400BEVT-00A0RT0 640GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVX-55V0TT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.7%    |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.7%    |
| WDC PC SN520 SDAPMUW-512G-1001 512GB     | 1         | 1      | 0.7%    |
| VISIPRO SSD 256GB                        | 1         | 2      | 0.7%    |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.7%    |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.7%    |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.7%    |
| Toshiba MQ01ABD075 752GB                 | 1         | 2      | 0.7%    |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.7%    |
| Toshiba MK7559GSXP 752GB                 | 1         | 2      | 0.7%    |
| Toshiba MK6476GSX 640GB                  | 1         | 1      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 22.38%  |
| Toshiba             | 20        | 24     | 13.99%  |
| Hitachi             | 12        | 12     | 8.39%   |
| HGST                | 12        | 13     | 8.39%   |
| WDC                 | 11        | 11     | 7.69%   |
| Samsung Electronics | 10        | 11     | 6.99%   |
| SK hynix            | 9         | 9      | 6.29%   |
| Crucial             | 9         | 10     | 6.29%   |
| SanDisk             | 6         | 6      | 4.2%    |
| Kingston            | 6         | 6      | 4.2%    |
| A-DATA Technology   | 5         | 5      | 3.5%    |
| Micron Technology   | 3         | 3      | 2.1%    |
| Zheino              | 1         | 2      | 0.7%    |
| VISIPRO             | 1         | 2      | 0.7%    |
| R580                | 1         | 1      | 0.7%    |
| Mushkin             | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| Drevo               | 1         | 1      | 0.7%    |
| BAITITON            | 1         | 3      | 0.7%    |
| ASENNO              | 1         | 1      | 0.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 38.1%   |
| Toshiba             | 17        | 21     | 20.24%  |
| Hitachi             | 12        | 12     | 14.29%  |
| HGST                | 12        | 13     | 14.29%  |
| WDC                 | 9         | 9      | 10.71%  |
| Samsung Electronics | 2         | 2      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 97     | 58.87%  |
| SSD  | 44        | 51     | 31.21%  |
| NVMe | 14        | 14     | 9.93%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 33.33%  |
| Intel SSDSC2KB960G8 960GB | 1         | 1      | 33.33%  |
| Acer SSD FA100 256GB      | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Acer    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1078      | 1480   | 49.56%  |
| Detected | 954       | 1480   | 43.86%  |
| Malfunc  | 140       | 162    | 6.44%   |
| Failed   | 3         | 3      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1361      | 54.16%  |
| Samsung Electronics              | 276       | 10.98%  |
| AMD                              | 251       | 9.99%   |
| SanDisk                          | 156       | 6.21%   |
| SK hynix                         | 99        | 3.94%   |
| Toshiba America Info Systems     | 64        | 2.55%   |
| Kingston Technology Company      | 57        | 2.27%   |
| Micron Technology                | 50        | 1.99%   |
| KIOXIA                           | 36        | 1.43%   |
| Phison Electronics               | 25        | 0.99%   |
| Micron/Crucial Technology        | 23        | 0.92%   |
| ADATA Technology                 | 22        | 0.88%   |
| Silicon Motion                   | 19        | 0.76%   |
| Union Memory (Shenzhen)          | 13        | 0.52%   |
| Solid State Storage Technology   | 13        | 0.52%   |
| Realtek Semiconductor            | 11        | 0.44%   |
| Lite-On Technology               | 8         | 0.32%   |
| Apple                            | 6         | 0.24%   |
| Nvidia                           | 5         | 0.2%    |
| Lenovo                           | 4         | 0.16%   |
| Marvell Technology Group         | 3         | 0.12%   |
| Zhaoxin                          | 1         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| Seagate Technology               | 1         | 0.04%   |
| Netac Technology                 | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| ASMedia Technology               | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 234       | 8.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 165       | 6.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 151       | 5.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 142       | 5.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 135       | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 93        | 3.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 91        | 3.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 84        | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 75        | 2.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 73        | 2.74%   |
| Samsung NVMe SSD Controller 980                                                | 63        | 2.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 51        | 1.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 50        | 1.87%   |
| Micron NVMe Storage Controller                                                 | 50        | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 47        | 1.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 46        | 1.72%   |
| Intel SSD 660P Series                                                          | 45        | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 42        | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                          | 37        | 1.39%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 34        | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 34        | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                            | 32        | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 31        | 1.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 30        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 30        | 1.12%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 27        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 27        | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 26        | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 23        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 22        | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 21        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 21        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.75%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 19        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 19        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 18        | 0.67%   |
| SK hynix Non-Volatile memory controller                                        | 16        | 0.6%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 16        | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 16        | 0.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 15        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1371      | 53.47%  |
| NVMe | 908       | 35.41%  |
| RAID | 223       | 8.7%    |
| IDE  | 62        | 2.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1604      | 80.08%  |
| AMD          | 398       | 19.87%  |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 47        | 2.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 40        | 2%      |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 39        | 1.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 37        | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 36        | 1.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 1.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 1.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 32        | 1.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 30        | 1.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.45%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 29        | 1.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 28        | 1.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 1.25%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 25        | 1.25%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 1%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 0.95%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 18        | 0.9%    |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.8%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 16        | 0.8%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 16        | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 0.75%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 0.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 14        | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 13        | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.65%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 13        | 0.65%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 13        | 0.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.65%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 0.65%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 12        | 0.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 12        | 0.6%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.6%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 559       | 27.91%  |
| Intel Core i5           | 497       | 24.81%  |
| Other                   | 197       | 9.84%   |
| AMD Ryzen 7             | 119       | 5.94%   |
| AMD Ryzen 5             | 110       | 5.49%   |
| Intel Core i3           | 109       | 5.44%   |
| Intel Celeron           | 88        | 4.39%   |
| Intel Core 2 Duo        | 49        | 2.45%   |
| Intel Pentium           | 30        | 1.5%    |
| AMD A6                  | 23        | 1.15%   |
| AMD Ryzen 3             | 21        | 1.05%   |
| AMD Ryzen 7 PRO         | 19        | 0.95%   |
| AMD Ryzen 9             | 15        | 0.75%   |
| Intel Pentium Dual-Core | 14        | 0.7%    |
| Intel Core i9           | 14        | 0.7%    |
| AMD A10                 | 14        | 0.7%    |
| Intel Atom              | 13        | 0.65%   |
| Intel Pentium Silver    | 11        | 0.55%   |
| AMD A8                  | 10        | 0.5%    |
| AMD Ryzen 5 PRO         | 9         | 0.45%   |
| Intel Genuine           | 7         | 0.35%   |
| AMD E1                  | 7         | 0.35%   |
| AMD E                   | 7         | 0.35%   |
| AMD E2                  | 6         | 0.3%    |
| AMD A4                  | 6         | 0.3%    |
| Intel Pentium Dual      | 5         | 0.25%   |
| Intel Core m3           | 5         | 0.25%   |
| Intel Celeron Dual-Core | 5         | 0.25%   |
| AMD FX                  | 5         | 0.25%   |
| AMD Athlon              | 4         | 0.2%    |
| Intel Xeon              | 3         | 0.15%   |
| Intel Core 2            | 3         | 0.15%   |
| AMD A12                 | 3         | 0.15%   |
| AMD C-50                | 2         | 0.1%    |
| AMD Athlon II           | 2         | 0.1%    |
| Intel Pentium Gold      | 1         | 0.05%   |
| Intel Core M            | 1         | 0.05%   |
| Intel Core 2 Quad       | 1         | 0.05%   |
| AMD Z                   | 1         | 0.05%   |
| AMD Turion II           | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 813       | 40.57%  |
| 4      | 753       | 37.57%  |
| 6      | 217       | 10.83%  |
| 8      | 163       | 8.13%   |
| 14     | 24        | 1.2%    |
| 1      | 13        | 0.65%   |
| 12     | 10        | 0.5%    |
| 10     | 8         | 0.4%    |
| 24     | 1         | 0.05%   |
| 16     | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2003      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1653      | 82.4%   |
| 1      | 353       | 17.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2003      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 496       | 24.16%  |
| 0x306a9    | 108       | 5.26%   |
| 0x206a7    | 95        | 4.63%   |
| 0x906ea    | 88        | 4.29%   |
| 0x806ec    | 88        | 4.29%   |
| 0x806c1    | 81        | 3.95%   |
| 0x806ea    | 77        | 3.75%   |
| 0x40651    | 71        | 3.46%   |
| 0x306c3    | 59        | 2.87%   |
| 0x806e9    | 58        | 2.83%   |
| 0x406e3    | 53        | 2.58%   |
| 0x306d4    | 43        | 2.09%   |
| 0x08600106 | 38        | 1.85%   |
| 0x08108109 | 38        | 1.85%   |
| 0xa0652    | 36        | 1.75%   |
| 0x1067a    | 36        | 1.75%   |
| 0x906e9    | 35        | 1.7%    |
| 0x0a50000c | 35        | 1.7%    |
| 0x08108102 | 33        | 1.61%   |
| 0x706e5    | 30        | 1.46%   |
| 0x906a3    | 29        | 1.41%   |
| 0x806eb    | 26        | 1.27%   |
| 0x506e3    | 23        | 1.12%   |
| 0x08608103 | 21        | 1.02%   |
| 0x706a1    | 20        | 0.97%   |
| 0x20655    | 19        | 0.93%   |
| 0x806d1    | 18        | 0.88%   |
| 0x706a8    | 18        | 0.88%   |
| 0x406c4    | 18        | 0.88%   |
| 0x30678    | 16        | 0.78%   |
| 0x08600104 | 15        | 0.73%   |
| 0x906ed    | 14        | 0.68%   |
| 0x08600103 | 13        | 0.63%   |
| 0x07030105 | 13        | 0.63%   |
| 0x6fd      | 12        | 0.58%   |
| 0x03000027 | 12        | 0.58%   |
| 0x20652    | 11        | 0.54%   |
| 0x06006705 | 11        | 0.54%   |
| 0x506c9    | 9         | 0.44%   |
| 0x10676    | 8         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 490       | 24.45%  |
| Haswell          | 168       | 8.38%   |
| IvyBridge        | 150       | 7.49%   |
| SandyBridge      | 119       | 5.94%   |
| TigerLake        | 117       | 5.84%   |
| Skylake          | 93        | 4.64%   |
| Zen 2            | 87        | 4.34%   |
| Zen+             | 83        | 4.14%   |
| Unknown          | 73        | 3.64%   |
| Zen 3            | 61        | 3.04%   |
| Penryn           | 59        | 2.94%   |
| CometLake        | 57        | 2.84%   |
| Icelake          | 55        | 2.74%   |
| Broadwell        | 52        | 2.59%   |
| Goldmont plus    | 51        | 2.54%   |
| Silvermont       | 46        | 2.3%    |
| Westmere         | 42        | 2.1%    |
| Alderlake Hybrid | 36        | 1.8%    |
| Excavator        | 31        | 1.55%   |
| Core             | 29        | 1.45%   |
| Zen              | 18        | 0.9%    |
| Puma             | 17        | 0.85%   |
| K10 Llano        | 13        | 0.65%   |
| Bobcat           | 12        | 0.6%    |
| Goldmont         | 11        | 0.55%   |
| Piledriver       | 8         | 0.4%    |
| Jaguar           | 8         | 0.4%    |
| Steamroller      | 4         | 0.2%    |
| Nehalem          | 4         | 0.2%    |
| K10              | 4         | 0.2%    |
| Bonnell          | 3         | 0.15%   |
| K8 & K10 hybrid  | 2         | 0.1%    |
| Tremont          | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1504      | 56.41%  |
| Nvidia                           | 647       | 24.27%  |
| AMD                              | 512       | 19.2%   |
| Zhaoxin                          | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 137       | 5.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 119       | 4.36%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 111       | 4.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 107       | 3.92%   |
| Intel UHD Graphics 620                                                                   | 88        | 3.23%   |
| AMD Renoir                                                                               | 86        | 3.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 86        | 3.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 80        | 2.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 78        | 2.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 77        | 2.82%   |
| Intel HD Graphics 620                                                                    | 72        | 2.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 61        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 60        | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 50        | 1.83%   |
| Intel HD Graphics 5500                                                                   | 49        | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 45        | 1.65%   |
| Intel HD Graphics 630                                                                    | 41        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 36        | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 1.32%   |
| AMD Lucienne                                                                             | 34        | 1.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 31        | 1.14%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 1.03%   |
| Intel HD Graphics 530                                                                    | 26        | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 0.88%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 22        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 22        | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 22        | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 20        | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 18        | 0.66%   |
| Intel Iris Plus Graphics G7                                                              | 18        | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 17        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 16        | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 16        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 901       | 44.89%  |
| Intel + Nvidia | 512       | 25.51%  |
| 1 x AMD        | 321       | 15.99%  |
| Intel + AMD    | 89        | 4.43%   |
| 1 x Nvidia     | 74        | 3.69%   |
| AMD + Nvidia   | 59        | 2.94%   |
| 2 x AMD        | 44        | 2.19%   |
| Other          | 2         | 0.1%    |
| 2 x Nvidia     | 2         | 0.1%    |
| 2 x Intel      | 1         | 0.05%   |
| 1 x Zhaoxin    | 1         | 0.05%   |
| 1 x SiS        | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1565      | 77.21%  |
| Proprietary | 430       | 21.21%  |
| Unknown     | 32        | 1.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1296      | 63.25%  |
| 1.01-2.0   | 234       | 11.42%  |
| 0.01-0.5   | 209       | 10.2%   |
| 3.01-4.0   | 128       | 6.25%   |
| 0.51-1.0   | 105       | 5.12%   |
| 5.01-6.0   | 37        | 1.81%   |
| 7.01-8.0   | 26        | 1.27%   |
| 2.01-3.0   | 12        | 0.59%   |
| 8.01-16.0  | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 420       | 17.51%  |
| BOE                     | 345       | 14.38%  |
| LG Display              | 342       | 14.26%  |
| Chimei Innolux          | 332       | 13.84%  |
| Samsung Electronics     | 227       | 9.46%   |
| Sharp                   | 98        | 4.09%   |
| Dell                    | 83        | 3.46%   |
| Goldstar                | 65        | 2.71%   |
| Lenovo                  | 45        | 1.88%   |
| PANDA                   | 42        | 1.75%   |
| Chi Mei Optoelectronics | 38        | 1.58%   |
| Hewlett-Packard         | 36        | 1.5%    |
| Apple                   | 30        | 1.25%   |
| Acer                    | 30        | 1.25%   |
| Philips                 | 26        | 1.08%   |
| InfoVision              | 21        | 0.88%   |
| BenQ                    | 21        | 0.88%   |
| Ancor Communications    | 20        | 0.83%   |
| AOC                     | 17        | 0.71%   |
| ViewSonic               | 12        | 0.5%    |
| ASUSTek Computer        | 12        | 0.5%    |
| CSO                     | 11        | 0.46%   |
| Iiyama                  | 9         | 0.38%   |
| Toshiba                 | 6         | 0.25%   |
| Panasonic               | 6         | 0.25%   |
| LG Philips              | 6         | 0.25%   |
| Sceptre Tech            | 5         | 0.21%   |
| CPT                     | 5         | 0.21%   |
| Sony                    | 4         | 0.17%   |
| Seiko/Epson             | 4         | 0.17%   |
| NEC Computers           | 4         | 0.17%   |
| MSI                     | 4         | 0.17%   |
| HannStar                | 4         | 0.17%   |
| Vizio                   | 3         | 0.13%   |
| Vestel Elektronik       | 3         | 0.13%   |
| Unknown                 | 3         | 0.13%   |
| SLD                     | 3         | 0.13%   |
| LGD                     | 3         | 0.13%   |
| HKC                     | 3         | 0.13%   |
| MiTAC                   | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 20        | 0.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 19        | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 19        | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 18        | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 15        | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 14        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 14        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 12        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 12        | 0.49%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 11        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 10        | 0.41%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 10        | 0.41%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 9         | 0.37%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 9         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 8         | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 8         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 8         | 0.33%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 7         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 7         | 0.29%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 7         | 0.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 6         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 6         | 0.25%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch              | 6         | 0.25%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 6         | 0.25%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch               | 6         | 0.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 6         | 0.25%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 6         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.25%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 6         | 0.25%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 6         | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1094      | 49.35%  |
| 1366x768 (WXGA)    | 529       | 23.86%  |
| 1600x900 (HD+)     | 110       | 4.96%   |
| 3840x2160 (4K)     | 106       | 4.78%   |
| 2560x1440 (QHD)    | 85        | 3.83%   |
| 1920x1200 (WUXGA)  | 45        | 2.03%   |
| 1280x800 (WXGA)    | 37        | 1.67%   |
| 2560x1600          | 22        | 0.99%   |
| 1440x900 (WXGA+)   | 21        | 0.95%   |
| 2880x1800          | 20        | 0.9%    |
| 3840x2400          | 16        | 0.72%   |
| 1680x1050 (WSXGA+) | 15        | 0.68%   |
| 2160x1440          | 14        | 0.63%   |
| 3440x1440          | 13        | 0.59%   |
| 2560x1080          | 13        | 0.59%   |
| 1280x1024 (SXGA)   | 13        | 0.59%   |
| 1360x768           | 8         | 0.36%   |
| 3200x1800 (QHD+)   | 7         | 0.32%   |
| 3840x1080          | 5         | 0.23%   |
| 2256x1504          | 5         | 0.23%   |
| 2520x1680          | 4         | 0.18%   |
| 2240x1400          | 4         | 0.18%   |
| Unknown            | 4         | 0.18%   |
| 3456x2160          | 3         | 0.14%   |
| 1600x1200          | 3         | 0.14%   |
| 1024x768 (XGA)     | 3         | 0.14%   |
| 3072x1920          | 2         | 0.09%   |
| 1920x540           | 2         | 0.09%   |
| 1920x1280          | 2         | 0.09%   |
| 1024x600           | 2         | 0.09%   |
| 5760x2160          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 3000x1920          | 1         | 0.05%   |
| 2560x1700          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 2160x1350          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |
| 1080x1920          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 980       | 40.75%  |
| 13      | 304       | 12.64%  |
| 14      | 286       | 11.89%  |
| 17      | 205       | 8.52%   |
| 27      | 102       | 4.24%   |
| 24      | 88        | 3.66%   |
| 23      | 78        | 3.24%   |
| 21      | 60        | 2.49%   |
| 12      | 40        | 1.66%   |
| 11      | 40        | 1.66%   |
| 16      | 39        | 1.62%   |
| 34      | 24        | 1%      |
| Unknown | 24        | 1%      |
| 31      | 19        | 0.79%   |
| 18      | 16        | 0.67%   |
| 20      | 13        | 0.54%   |
| 19      | 10        | 0.42%   |
| 84      | 8         | 0.33%   |
| 22      | 8         | 0.33%   |
| 32      | 7         | 0.29%   |
| 72      | 6         | 0.25%   |
| 25      | 6         | 0.25%   |
| 40      | 5         | 0.21%   |
| 54      | 4         | 0.17%   |
| 47      | 3         | 0.12%   |
| 42      | 3         | 0.12%   |
| 26      | 3         | 0.12%   |
| 10      | 3         | 0.12%   |
| 49      | 2         | 0.08%   |
| 48      | 2         | 0.08%   |
| 46      | 2         | 0.08%   |
| 78      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 61      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1427      | 60.11%  |
| 501-600     | 248       | 10.45%  |
| 351-400     | 243       | 10.24%  |
| 201-300     | 221       | 9.31%   |
| 401-500     | 103       | 4.34%   |
| 701-800     | 31        | 1.31%   |
| 601-700     | 30        | 1.26%   |
| Unknown     | 24        | 1.01%   |
| 1001-1500   | 19        | 0.8%    |
| 1501-2000   | 16        | 0.67%   |
| 801-900     | 7         | 0.29%   |
| 901-1000    | 3         | 0.13%   |
| 101-200     | 1         | 0.04%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1761      | 86.28%  |
| 16/10   | 184       | 9.02%   |
| 3/2     | 30        | 1.47%   |
| 21/9    | 26        | 1.27%   |
| Unknown | 16        | 0.78%   |
| 5/4     | 11        | 0.54%   |
| 4/3     | 7         | 0.34%   |
| 32/9    | 3         | 0.15%   |
| 3.40    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 986       | 41.24%  |
| 81-90          | 472       | 19.74%  |
| 201-250        | 185       | 7.74%   |
| 121-130        | 179       | 7.49%   |
| 71-80          | 120       | 5.02%   |
| 301-350        | 106       | 4.43%   |
| 351-500        | 48        | 2.01%   |
| 51-60          | 41        | 1.71%   |
| 151-200        | 40        | 1.67%   |
| 61-70          | 36        | 1.51%   |
| 251-300        | 30        | 1.25%   |
| More than 1000 | 27        | 1.13%   |
| 111-120        | 26        | 1.09%   |
| Unknown        | 24        | 1%      |
| 141-150        | 19        | 0.79%   |
| 131-140        | 19        | 0.79%   |
| 501-1000       | 19        | 0.79%   |
| 91-100         | 9         | 0.38%   |
| 41-50          | 3         | 0.13%   |
| 1-40           | 2         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1061      | 45.19%  |
| 101-120       | 601       | 25.6%   |
| 51-100        | 357       | 15.2%   |
| 161-240       | 177       | 7.54%   |
| More than 240 | 99        | 4.22%   |
| 1-50          | 29        | 1.24%   |
| Unknown       | 24        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1559      | 76.16%  |
| 2     | 392       | 19.15%  |
| 3     | 55        | 2.69%   |
| 0     | 34        | 1.66%   |
| 4     | 7         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1143      | 35.95%  |
| Realtek Semiconductor             | 1140      | 35.86%  |
| Qualcomm Atheros                  | 404       | 12.71%  |
| Broadcom                          | 153       | 4.81%   |
| MediaTek                          | 66        | 2.08%   |
| Broadcom Limited                  | 26        | 0.82%   |
| Ralink                            | 23        | 0.72%   |
| Marvell Technology Group          | 20        | 0.63%   |
| ASIX Electronics                  | 15        | 0.47%   |
| TP-Link                           | 14        | 0.44%   |
| Sierra Wireless                   | 13        | 0.41%   |
| Qualcomm                          | 13        | 0.41%   |
| Samsung Electronics               | 12        | 0.38%   |
| Lenovo                            | 12        | 0.38%   |
| DisplayLink                       | 12        | 0.38%   |
| Ralink Technology                 | 11        | 0.35%   |
| Ericsson Business Mobile Networks | 10        | 0.31%   |
| Dell                              | 10        | 0.31%   |
| Huawei Technologies               | 9         | 0.28%   |
| Xiaomi                            | 8         | 0.25%   |
| JMicron Technology                | 7         | 0.22%   |
| Hewlett-Packard                   | 5         | 0.16%   |
| D-Link                            | 5         | 0.16%   |
| Apple                             | 5         | 0.16%   |
| Nvidia                            | 4         | 0.13%   |
| T & A Mobile Phones               | 3         | 0.09%   |
| Qualcomm Atheros Communications   | 3         | 0.09%   |
| NetGear                           | 3         | 0.09%   |
| Motorola PCS                      | 3         | 0.09%   |
| Google                            | 3         | 0.09%   |
| Fibocom                           | 3         | 0.09%   |
| ZyDAS                             | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| Texas Instruments                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |
| SEGGER                            | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 710       | 18.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 158       | 4.17%   |
| Intel Wi-Fi 6 AX200                                               | 136       | 3.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 98        | 2.58%   |
| Intel Wireless 8265 / 8275                                        | 96        | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82        | 2.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 81        | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 80        | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 79        | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 77        | 2.03%   |
| Intel Wireless 7260                                               | 76        | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 70        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 66        | 1.74%   |
| Intel Wireless 7265                                               | 59        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 1.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 56        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 53        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 52        | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 50        | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 45        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 40        | 1.05%   |
| Intel Wireless 8260                                               | 39        | 1.03%   |
| Intel Wireless 3165                                               | 36        | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 36        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 35        | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 33        | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 30        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 25        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 0.63%   |
| Intel Wireless 3160                                               | 23        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 22        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 22        | 0.58%   |
| Intel Wireless-AC 9260                                            | 21        | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 20        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 19        | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 19        | 0.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1093      | 52.93%  |
| Qualcomm Atheros                      | 339       | 16.42%  |
| Realtek Semiconductor                 | 337       | 16.32%  |
| Broadcom                              | 115       | 5.57%   |
| MediaTek                              | 64        | 3.1%    |
| Ralink                                | 23        | 1.11%   |
| Broadcom Limited                      | 23        | 1.11%   |
| TP-Link                               | 11        | 0.53%   |
| Ralink Technology                     | 11        | 0.53%   |
| Qualcomm                              | 10        | 0.48%   |
| Sierra Wireless                       | 8         | 0.39%   |
| Dell                                  | 5         | 0.24%   |
| D-Link                                | 5         | 0.24%   |
| Qualcomm Atheros Communications       | 3         | 0.15%   |
| NetGear                               | 3         | 0.15%   |
| Fibocom                               | 3         | 0.15%   |
| ZyDAS                                 | 2         | 0.1%    |
| Wacom                                 | 1         | 0.05%   |
| Texas Instruments                     | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| Edimax Technology                     | 1         | 0.05%   |
| D-Link System                         | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| ASUSTek Computer                      | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 136       | 6.54%   |
| Intel Wireless 8265 / 8275                                     | 96        | 4.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 81        | 3.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 80        | 3.84%   |
| Intel Wi-Fi 6 AX201                                            | 79        | 3.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 77        | 3.7%    |
| Intel Wireless 7260                                            | 76        | 3.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 70        | 3.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 66        | 3.17%   |
| Intel Wireless 7265                                            | 59        | 2.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58        | 2.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 56        | 2.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 53        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 52        | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 50        | 2.4%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 45        | 2.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 40        | 1.92%   |
| Intel Wireless 8260                                            | 39        | 1.87%   |
| Intel Wireless 3165                                            | 36        | 1.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 36        | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 35        | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 33        | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 30        | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 25        | 1.2%    |
| Intel Wireless 3160                                            | 23        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 22        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 22        | 1.06%   |
| Intel Wireless-AC 9260                                         | 21        | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 20        | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 19        | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 19        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 0.86%   |
| Intel Centrino Advanced-N 6235                                 | 18        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 16        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 13        | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 13        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 0.62%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 13        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 997       | 60.61%  |
| Intel                            | 381       | 23.16%  |
| Qualcomm Atheros                 | 94        | 5.71%   |
| Broadcom                         | 49        | 2.98%   |
| Marvell Technology Group         | 20        | 1.22%   |
| ASIX Electronics                 | 15        | 0.91%   |
| Lenovo                           | 12        | 0.73%   |
| DisplayLink                      | 12        | 0.73%   |
| Xiaomi                           | 8         | 0.49%   |
| JMicron Technology               | 7         | 0.43%   |
| Samsung Electronics              | 6         | 0.36%   |
| Huawei Technologies              | 6         | 0.36%   |
| Sierra Wireless                  | 5         | 0.3%    |
| Apple                            | 5         | 0.3%    |
| Nvidia                           | 4         | 0.24%   |
| Broadcom Limited                 | 4         | 0.24%   |
| TP-Link                          | 3         | 0.18%   |
| T & A Mobile Phones              | 3         | 0.18%   |
| Qualcomm                         | 3         | 0.18%   |
| Google                           | 3         | 0.18%   |
| Motorola PCS                     | 2         | 0.12%   |
| MediaTek                         | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 710       | 42.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 158       | 9.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 98        | 5.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 82        | 4.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 2.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 0.95%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.84%   |
| Intel Ethernet Connection (10) I219-V                             | 14        | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.66%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.6%    |
| Intel Ethernet Connection (7) I219-V                              | 9         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.48%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 8         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.36%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.3%    |
| Sierra Wireless EM7345 4G LTE                                     | 5         | 0.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1984      | 55.33%  |
| Ethernet | 1567      | 43.7%   |
| Modem    | 31        | 0.86%   |
| Unknown  | 4         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1671      | 78.16%  |
| Ethernet | 466       | 21.8%   |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1446      | 72.19%  |
| 1     | 506       | 25.26%  |
| 0     | 36        | 1.8%    |
| 3     | 15        | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1655      | 81.85%  |
| Yes  | 367       | 18.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 904       | 53.08%  |
| Realtek Semiconductor           | 184       | 10.8%   |
| Qualcomm Atheros Communications | 162       | 9.51%   |
| IMC Networks                    | 84        | 4.93%   |
| Broadcom                        | 83        | 4.87%   |
| Lite-On Technology              | 74        | 4.35%   |
| Foxconn / Hon Hai               | 59        | 3.46%   |
| Dell                            | 31        | 1.82%   |
| Realtek                         | 25        | 1.47%   |
| Apple                           | 20        | 1.17%   |
| Hewlett-Packard                 | 13        | 0.76%   |
| Cambridge Silicon Radio         | 12        | 0.7%    |
| Toshiba                         | 10        | 0.59%   |
| Ralink                          | 10        | 0.59%   |
| Foxconn International           | 8         | 0.47%   |
| Ralink Technology               | 5         | 0.29%   |
| ASUSTek Computer                | 4         | 0.23%   |
| Alps Electric                   | 4         | 0.23%   |
| TP-Link                         | 2         | 0.12%   |
| Taiyo Yuden                     | 2         | 0.12%   |
| Smart Modular Technologies      | 2         | 0.12%   |
| USI                             | 1         | 0.06%   |
| SINO WEALTH                     | 1         | 0.06%   |
| MediaTek                        | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 317       | 18.59%  |
| Intel AX201 Bluetooth                               | 195       | 11.44%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 144       | 8.45%   |
| Intel AX200 Bluetooth                               | 132       | 7.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 114       | 6.69%   |
| Realtek Bluetooth Radio                             | 109       | 6.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 3.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.58%   |
| IMC Networks Bluetooth Radio                        | 27        | 1.58%   |
| Lite-On Bluetooth Device                            | 26        | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 1.52%   |
| Intel Bluetooth Device                              | 24        | 1.41%   |
| IMC Networks Wireless_Device                        | 23        | 1.35%   |
| Realtek 802.11ac WLAN Adapter                       | 22        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.11%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 1.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.06%   |
| Intel AX210 Bluetooth                               | 17        | 1%      |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.94%   |
| Lite-On Wireless_Device                             | 15        | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.82%   |
| IMC Networks Bluetooth Device                       | 14        | 0.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 0.7%    |
| Apple Bluetooth Host Controller                     | 12        | 0.7%    |
| Realtek RTL8723B Bluetooth                          | 11        | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.65%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 10        | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.47%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.47%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.41%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.41%   |
| Lite-On Bluetooth Radio                             | 6         | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1588      | 62.54%  |
| AMD                              | 434       | 17.09%  |
| Nvidia                           | 331       | 13.04%  |
| Realtek Semiconductor            | 22        | 0.87%   |
| GN Netcom                        | 17        | 0.67%   |
| C-Media Electronics              | 16        | 0.63%   |
| Logitech                         | 14        | 0.55%   |
| Lenovo                           | 12        | 0.47%   |
| Hewlett-Packard                  | 10        | 0.39%   |
| Plantronics                      | 9         | 0.35%   |
| Texas Instruments                | 6         | 0.24%   |
| JMTek                            | 6         | 0.24%   |
| Generalplus Technology           | 6         | 0.24%   |
| Razer USA                        | 5         | 0.2%    |
| Creative Technology              | 5         | 0.2%    |
| Sony                             | 4         | 0.16%   |
| Dell                             | 4         | 0.16%   |
| Focusrite-Novation               | 3         | 0.12%   |
| CMX Systems                      | 3         | 0.12%   |
| ZOOM                             | 2         | 0.08%   |
| Microsoft                        | 2         | 0.08%   |
| Kingston Technology              | 2         | 0.08%   |
| GYROCOM C&C                      | 2         | 0.08%   |
| Google                           | 2         | 0.08%   |
| Corsair                          | 2         | 0.08%   |
| Conexant Systems                 | 2         | 0.08%   |
| Blue Microphones                 | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Zhaoxin                          | 1         | 0.04%   |
| YZ Technology                    | 1         | 0.04%   |
| Winbond Electronics              | 1         | 0.04%   |
| Trust                            | 1         | 0.04%   |
| TerraTec Electronic              | 1         | 0.04%   |
| SteelSeries ApS                  | 1         | 0.04%   |
| Silicon Motion                   | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| Princeton Technology             | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 288       | 9.26%   |
| Intel Sunrise Point-LP HD Audio                                            | 236       | 7.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 166       | 5.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 151       | 4.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 131       | 4.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 117       | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 103       | 3.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 96        | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 88        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 79        | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 79        | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 79        | 2.54%   |
| Intel 8 Series HD Audio Controller                                         | 79        | 2.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 66        | 2.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 56        | 1.8%    |
| Intel Comet Lake PCH cAVS                                                  | 53        | 1.7%    |
| AMD FCH Azalia Controller                                                  | 53        | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 52        | 1.67%   |
| Intel Broadwell-U Audio Controller                                         | 52        | 1.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 51        | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 51        | 1.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 46        | 1.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 43        | 1.38%   |
| Intel CM238 HD Audio Controller                                            | 41        | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                   | 40        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 38        | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 37        | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 34        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 30        | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 28        | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 23        | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 23        | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 22        | 0.71%   |
| Realtek Semiconductor USB Audio                                            | 21        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 21        | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 20        | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 19        | 0.61%   |
| Nvidia Audio device                                                        | 19        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 470       | 29.14%  |
| SK hynix            | 335       | 20.77%  |
| Micron Technology   | 213       | 13.21%  |
| Kingston            | 158       | 9.8%    |
| Crucial             | 99        | 6.14%   |
| Unknown             | 62        | 3.84%   |
| Ramaxel Technology  | 37        | 2.29%   |
| A-DATA Technology   | 37        | 2.29%   |
| Unknown (ABCD)      | 28        | 1.74%   |
| Elpida              | 28        | 1.74%   |
| Nanya Technology    | 21        | 1.3%    |
| Corsair             | 19        | 1.18%   |
| Smart               | 10        | 0.62%   |
| Unknown             | 10        | 0.62%   |
| Transcend           | 9         | 0.56%   |
| G.Skill             | 8         | 0.5%    |
| Wilk                | 5         | 0.31%   |
| Smart Brazil        | 5         | 0.31%   |
| Teikon              | 4         | 0.25%   |
| Team                | 4         | 0.25%   |
| Silicon Power       | 4         | 0.25%   |
| GOODRAM             | 4         | 0.25%   |
| Apacer              | 4         | 0.25%   |
| SHARETRONIC         | 3         | 0.19%   |
| Goldkey             | 3         | 0.19%   |
| ASint Technology    | 3         | 0.19%   |
| CSX                 | 2         | 0.12%   |
| AMD                 | 2         | 0.12%   |
| V-GeN               | 1         | 0.06%   |
| V-Color             | 1         | 0.06%   |
| Unknown (8AD6)      | 1         | 0.06%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (08AE)      | 1         | 0.06%   |
| Super Talent        | 1         | 0.06%   |
| Shenzhen Zhongteng  | 1         | 0.06%   |
| Shenzhen WODPOSIT   | 1         | 0.06%   |
| Reboto              | 1         | 0.06%   |
| Qimonda             | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Patriot             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 25        | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 1.36%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 1.24%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.94%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.77%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.71%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.71%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.65%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 11        | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 11        | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.59%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.59%   |
| Unknown                                                          | 10        | 0.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.47%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 8         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 8         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 800       | 59.79%  |
| DDR3    | 355       | 26.53%  |
| LPDDR4  | 70        | 5.23%   |
| LPDDR3  | 41        | 3.06%   |
| DDR5    | 19        | 1.42%   |
| DDR2    | 19        | 1.42%   |
| SDRAM   | 14        | 1.05%   |
| LPDDR5  | 13        | 0.97%   |
| Unknown | 5         | 0.37%   |
| DDR     | 2         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1195      | 88.32%  |
| Row Of Chips | 133       | 9.83%   |
| Chip         | 12        | 0.89%   |
| Unknown      | 7         | 0.52%   |
| DIMM         | 6         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 668       | 45.69%  |
| 4096  | 402       | 27.5%   |
| 16384 | 252       | 17.24%  |
| 2048  | 86        | 5.88%   |
| 32768 | 40        | 2.74%   |
| 1024  | 14        | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 381       | 26.37%  |
| 3200    | 307       | 21.25%  |
| 1600    | 265       | 18.34%  |
| 2400    | 144       | 9.97%   |
| 2133    | 65        | 4.5%    |
| 1334    | 55        | 3.81%   |
| 1333    | 41        | 2.84%   |
| 4267    | 25        | 1.73%   |
| 4800    | 19        | 1.31%   |
| 1867    | 19        | 1.31%   |
| 3266    | 18        | 1.25%   |
| 6400    | 13        | 0.9%    |
| 8400    | 12        | 0.83%   |
| 1067    | 11        | 0.76%   |
| 667     | 11        | 0.76%   |
| Unknown | 11        | 0.76%   |
| 4199    | 10        | 0.69%   |
| 800     | 9         | 0.62%   |
| 4266    | 7         | 0.48%   |
| 2048    | 4         | 0.28%   |
| 1066    | 3         | 0.21%   |
| 975     | 3         | 0.21%   |
| 3000    | 2         | 0.14%   |
| 2933    | 2         | 0.14%   |
| 1866    | 2         | 0.14%   |
| 2666    | 1         | 0.07%   |
| 2000    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |
| 533     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 23.53%  |
| Brother Industries  | 4         | 23.53%  |
| Samsung Electronics | 3         | 17.65%  |
| Canon               | 3         | 17.65%  |
| Seiko Epson         | 2         | 11.76%  |
| Xerox               | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Xerox Phaser 6500DN                             | 1         | 5.88%   |
| Seiko Epson L3110 Series                        | 1         | 5.88%   |
| Seiko Epson ET-2700 Series                      | 1         | 5.88%   |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 5.88%   |
| Samsung SCX-3200 Series                         | 1         | 5.88%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5.88%   |
| HP LaserJet Professional P 1102w                | 1         | 5.88%   |
| HP LaserJet 1020                                | 1         | 5.88%   |
| HP DeskJet F300 series                          | 1         | 5.88%   |
| HP DeskJet 2300 series                          | 1         | 5.88%   |
| Canon PIXMA MP250                               | 1         | 5.88%   |
| Canon MF4800 Series                             | 1         | 5.88%   |
| Canon iP2600 series                             | 1         | 5.88%   |
| Brother MFC-J4340DW                             | 1         | 5.88%   |
| Brother HL-L2390DW                              | 1         | 5.88%   |
| Brother HL-5450DN series                        | 1         | 5.88%   |
| Brother HL-2230 series                          | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 410       | 21.51%  |
| IMC Networks                           | 221       | 11.59%  |
| Microdia                               | 181       | 9.5%    |
| Realtek Semiconductor                  | 160       | 8.39%   |
| Quanta                                 | 126       | 6.61%   |
| Sunplus Innovation Technology          | 107       | 5.61%   |
| Acer                                   | 101       | 5.3%    |
| Bison Electronics                      | 91        | 4.77%   |
| Cheng Uei Precision Industry (Foxlink) | 87        | 4.56%   |
| Suyin                                  | 45        | 2.36%   |
| Syntek                                 | 44        | 2.31%   |
| Lite-On Technology                     | 39        | 2.05%   |
| Silicon Motion                         | 38        | 1.99%   |
| Logitech                               | 33        | 1.73%   |
| Luxvisions Innotech Limited            | 31        | 1.63%   |
| Apple                                  | 26        | 1.36%   |
| Alcor Micro                            | 19        | 1%      |
| Ricoh                                  | 15        | 0.79%   |
| Samsung Electronics                    | 14        | 0.73%   |
| Lenovo                                 | 11        | 0.58%   |
| Sonix Technology                       | 10        | 0.52%   |
| SunplusIT                              | 7         | 0.37%   |
| Y Media                                | 6         | 0.31%   |
| Sunplus Technology                     | 5         | 0.26%   |
| Importek                               | 5         | 0.26%   |
| Microsoft                              | 4         | 0.21%   |
| icSpring                               | 4         | 0.21%   |
| Generalplus Technology                 | 4         | 0.21%   |
| Z-Star Microelectronics                | 3         | 0.16%   |
| ShineTech                              | 3         | 0.16%   |
| Primax Electronics                     | 3         | 0.16%   |
| Intel                                  | 3         | 0.16%   |
| Genesys Logic                          | 3         | 0.16%   |
| GEMBIRD                                | 3         | 0.16%   |
| USB Camera CS                          | 2         | 0.1%    |
| Novatek Microelectronics               | 2         | 0.1%    |
| MacroSilicon                           | 2         | 0.1%    |
| LG Electronics                         | 2         | 0.1%    |
| Google                                 | 2         | 0.1%    |
| DigiTech                               | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 93        | 4.86%   |
| Microdia Integrated_Webcam_HD                                              | 88        | 4.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 67        | 3.5%    |
| IMC Networks Integrated Camera                                             | 66        | 3.45%   |
| Realtek Integrated_Webcam_HD                                               | 61        | 3.19%   |
| Sunplus Integrated_Webcam_HD                                               | 53        | 2.77%   |
| Chicony HD Webcam                                                          | 46        | 2.4%    |
| Acer Integrated Camera                                                     | 32        | 1.67%   |
| Chicony USB2.0 Camera                                                      | 31        | 1.62%   |
| Syntek Integrated Camera                                                   | 29        | 1.52%   |
| Quanta HD User Facing                                                      | 26        | 1.36%   |
| Bison Integrated Camera                                                    | 25        | 1.31%   |
| Chicony HP HD Camera                                                       | 24        | 1.25%   |
| Chicony HD User Facing                                                     | 22        | 1.15%   |
| Microdia Integrated Webcam                                                 | 21        | 1.1%    |
| Bison HD Webcam                                                            | 21        | 1.1%    |
| Acer Lenovo EasyCamera                                                     | 19        | 0.99%   |
| Quanta HP TrueVision HD Camera                                             | 18        | 0.94%   |
| Quanta HP HD Camera                                                        | 18        | 0.94%   |
| Chicony Integrated Camera (1280x720@30)                                    | 17        | 0.89%   |
| Lite-On Integrated Camera                                                  | 16        | 0.84%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 14        | 0.73%   |
| Quanta HD Webcam                                                           | 14        | 0.73%   |
| Chicony HP Wide Vision HD Camera                                           | 14        | 0.73%   |
| Realtek Integrated Webcam                                                  | 13        | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.68%   |
| Chicony HP Truevision HD                                                   | 13        | 0.68%   |
| Realtek Integrated Webcam HD                                               | 12        | 0.63%   |
| IMC Networks ov9734_azurewave_camera                                       | 12        | 0.63%   |
| Chicony HP TrueVision HD Camera                                            | 12        | 0.63%   |
| Sunplus HD WebCam                                                          | 11        | 0.57%   |
| Microdia Webcam Vitade AF                                                  | 11        | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 11        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 11        | 0.57%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 11        | 0.57%   |
| Realtek USB Camera                                                         | 10        | 0.52%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 10        | 0.52%   |
| Logitech HD Pro Webcam C920                                                | 10        | 0.52%   |
| IMC Networks HD Camera                                                     | 10        | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 10        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 124       | 28.9%   |
| Validity Sensors                   | 115       | 26.81%  |
| Shenzhen Goodix Technology         | 89        | 20.75%  |
| Elan Microelectronics              | 35        | 8.16%   |
| Upek                               | 21        | 4.9%    |
| AuthenTec                          | 19        | 4.43%   |
| LighTuning Technology              | 17        | 3.96%   |
| STMicroelectronics                 | 5         | 1.17%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.47%   |
| Focal-systems.Corp                 | 2         | 0.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 55        | 12.82%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 49        | 11.42%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 4.9%    |
| Elan ELAN:Fingerprint                                                      | 21        | 4.9%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 4.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4.2%    |
| Shenzhen Goodix FingerPrint                                                | 16        | 3.73%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.03%   |
| Elan ELAN:ARM-M4                                                           | 13        | 3.03%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 2.8%    |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 2.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 2.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.1%    |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.63%   |
| Synaptics UWP WBDI                                                         | 7         | 1.63%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 1.63%   |
| AuthenTec AES2810                                                          | 7         | 1.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.17%   |
| Validity Sensors VFS491                                                    | 5         | 1.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.17%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.17%   |
| Unknown                                                                    | 5         | 1.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.93%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.7%    |
| Synaptics UWP WBDI Device                                                  | 3         | 0.7%    |
| Synaptics  WBDI                                                            | 3         | 0.7%    |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.7%    |
| Synaptics WBDI Device                                                      | 2         | 0.47%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.47%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.47%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.47%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 87        | 46.28%  |
| Alcor Micro               | 55        | 29.26%  |
| Upek                      | 14        | 7.45%   |
| O2 Micro                  | 9         | 4.79%   |
| Lenovo                    | 7         | 3.72%   |
| Yubico.com                | 2         | 1.06%   |
| Realtek Semiconductor     | 2         | 1.06%   |
| Clay Logic                | 2         | 1.06%   |
| Advanced Card Systems     | 2         | 1.06%   |
| Watchdata                 | 1         | 0.53%   |
| SCM Microsystems          | 1         | 0.53%   |
| In Focus Systems          | 1         | 0.53%   |
| Giesecke & Devrient       | 1         | 0.53%   |
| Fujitsu Siemens Computers | 1         | 0.53%   |
| Chicony Electronics       | 1         | 0.53%   |
| Bit4id                    | 1         | 0.53%   |
| Aladdin Knowledge Systems | 1         | 0.53%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 55        | 29.26%  |
| Broadcom 5880                                                                | 24        | 12.77%  |
| Broadcom 58200                                                               | 24        | 12.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 11.7%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 7.98%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 7.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 4.79%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.72%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 1.06%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.06%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 1.06%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.06%   |
| Advanced Card Systems ACR39U                                                 | 2         | 1.06%   |
| Watchdata USB Key                                                            | 1         | 0.53%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.53%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.53%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.53%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.53%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.53%   |
| Bit4id miniLector EVO                                                        | 1         | 0.53%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.53%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1201      | 58.67%  |
| 1     | 672       | 32.83%  |
| 2     | 152       | 7.43%   |
| 3     | 11        | 0.54%   |
| 4     | 5         | 0.24%   |
| 7     | 3         | 0.15%   |
| 6     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 421       | 40.72%  |
| Chipcard                 | 170       | 16.44%  |
| Graphics card            | 167       | 16.15%  |
| Net/wireless             | 90        | 8.7%    |
| Camera                   | 45        | 4.35%   |
| Multimedia controller    | 34        | 3.29%   |
| Bluetooth                | 27        | 2.61%   |
| Sound                    | 18        | 1.74%   |
| Card reader              | 16        | 1.55%   |
| Storage                  | 15        | 1.45%   |
| Communication controller | 14        | 1.35%   |
| Net/ethernet             | 7         | 0.68%   |
| Network                  | 5         | 0.48%   |
| Modem                    | 4         | 0.39%   |
| Firewire controller      | 1         | 0.1%    |

