Ultramarine - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Ultramarine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ultramarine/Desktop/README.md) and [notebooks](/Dist/Ultramarine/Notebook/README.md).

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

Total: 180

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | MIIX 520-12IKB 81CG         | Tablet      | [bceaf7bae0](https://linux-hardware.org/?probe=bceaf7bae0) | Dec 31, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [67bb9cbc19](https://linux-hardware.org/?probe=67bb9cbc19) | Dec 29, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31d2df6ebd](https://linux-hardware.org/?probe=31d2df6ebd) | Dec 26, 2025 |
| Dell          | 0P4T42 A01                  | All in one  | [2b4bcdd03c](https://linux-hardware.org/?probe=2b4bcdd03c) | Dec 14, 2025 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [a0660684e4](https://linux-hardware.org/?probe=a0660684e4) | Dec 08, 2025 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [79e7d64686](https://linux-hardware.org/?probe=79e7d64686) | Dec 06, 2025 |
| Lenovo        | ThinkPad P50 20E0S1EWAT     | Notebook    | [44d5ebb962](https://linux-hardware.org/?probe=44d5ebb962) | Dec 04, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [6072000510](https://linux-hardware.org/?probe=6072000510) | Dec 03, 2025 |
| Microsoft     | Surface Pro                 | Tablet      | [7b03b0cca8](https://linux-hardware.org/?probe=7b03b0cca8) | Nov 28, 2025 |
| Microsoft     | Surface Pro                 | Tablet      | [44c9d753f5](https://linux-hardware.org/?probe=44c9d753f5) | Nov 28, 2025 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [423dfff653](https://linux-hardware.org/?probe=423dfff653) | Nov 09, 2025 |
| Lenovo        | ThinkPad T495s 20QKS0SD2... | Notebook    | [31f0f088d1](https://linux-hardware.org/?probe=31f0f088d1) | Nov 04, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | Notebook    | [3bb441a690](https://linux-hardware.org/?probe=3bb441a690) | Nov 02, 2025 |
| HP            | Elite Dragonfly G2 Noteb... | Convertible | [e2548eaed0](https://linux-hardware.org/?probe=e2548eaed0) | Oct 27, 2025 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [25bfed9f4c](https://linux-hardware.org/?probe=25bfed9f4c) | Oct 27, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | Notebook    | [c5aa7cd8dc](https://linux-hardware.org/?probe=c5aa7cd8dc) | Oct 27, 2025 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1f1707af0d](https://linux-hardware.org/?probe=1f1707af0d) | Oct 27, 2025 |
| Microsoft     | Surface Book 2              | Tablet      | [58f74ecb37](https://linux-hardware.org/?probe=58f74ecb37) | Oct 27, 2025 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [b0599db8d9](https://linux-hardware.org/?probe=b0599db8d9) | Oct 25, 2025 |
| Intel         | NUC7i5DNB J57626-514        | Mini pc     | [423c845dd8](https://linux-hardware.org/?probe=423c845dd8) | Oct 21, 2025 |
| Shenzhen M... | F7BSI                       | Mini pc     | [6463965649](https://linux-hardware.org/?probe=6463965649) | Oct 20, 2025 |
| LTD Delovo... | EVE 1494E ES1280EW          | Tablet      | [62a46a3326](https://linux-hardware.org/?probe=62a46a3326) | Oct 18, 2025 |
| Dell          | G3 3500                     | Notebook    | [ae0b29409e](https://linux-hardware.org/?probe=ae0b29409e) | Oct 17, 2025 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [45978809ad](https://linux-hardware.org/?probe=45978809ad) | Oct 12, 2025 |
| ASUSTek       | UX390UAK                    | Notebook    | [a94841922d](https://linux-hardware.org/?probe=a94841922d) | Oct 11, 2025 |
| Microsoft     | Surface Go 2                | Tablet      | [17c7c8441e](https://linux-hardware.org/?probe=17c7c8441e) | Oct 01, 2025 |
| Timi          | RedmiBook 15                | Notebook    | [38d56ec332](https://linux-hardware.org/?probe=38d56ec332) | Sep 23, 2025 |
| Lenovo        | ThinkPad P53 20QQS2J700     | Notebook    | [6a0202fe28](https://linux-hardware.org/?probe=6a0202fe28) | Sep 18, 2025 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4da7a6bf60](https://linux-hardware.org/?probe=4da7a6bf60) | Aug 13, 2025 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c36aa21ed8](https://linux-hardware.org/?probe=c36aa21ed8) | Aug 06, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f23b2e8d98](https://linux-hardware.org/?probe=f23b2e8d98) | Aug 05, 2025 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [daed7bd719](https://linux-hardware.org/?probe=daed7bd719) | Aug 05, 2025 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [b45b5ef988](https://linux-hardware.org/?probe=b45b5ef988) | Aug 03, 2025 |
| Google        | Eve                         | Notebook    | [39ccae56e7](https://linux-hardware.org/?probe=39ccae56e7) | Jun 26, 2025 |
| Shenzhen M... | F7BSI                       | Mini pc     | [485bb3d2eb](https://linux-hardware.org/?probe=485bb3d2eb) | Jun 08, 2025 |
| Intel         | powered classmate PC        | Tablet      | [d7119f4e70](https://linux-hardware.org/?probe=d7119f4e70) | May 30, 2025 |
| Intel         | powered classmate PC        | Tablet      | [44ad77f3e4](https://linux-hardware.org/?probe=44ad77f3e4) | May 30, 2025 |
| PELADN        | WI-6                        | Desktop     | [a3ea078afc](https://linux-hardware.org/?probe=a3ea078afc) | May 29, 2025 |
| PELADN        | WI-6                        | Desktop     | [256b2d9b96](https://linux-hardware.org/?probe=256b2d9b96) | May 28, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dca42e3352](https://linux-hardware.org/?probe=dca42e3352) | May 07, 2025 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [c4e87be5a7](https://linux-hardware.org/?probe=c4e87be5a7) | May 07, 2025 |
| Lenovo        | ThinkPad P1 Gen 7 21KWS0... | Notebook    | [b77577df42](https://linux-hardware.org/?probe=b77577df42) | May 06, 2025 |
| AMI           | Cherry Trail Tablet         | Desktop     | [a0cacce3e4](https://linux-hardware.org/?probe=a0cacce3e4) | Apr 08, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8139555f49](https://linux-hardware.org/?probe=8139555f49) | Mar 30, 2025 |
| Unknown       | HX90                        | Desktop     | [e215227e11](https://linux-hardware.org/?probe=e215227e11) | Mar 28, 2025 |
| HP            | 8055                        | Desktop     | [a2dd0c64ab](https://linux-hardware.org/?probe=a2dd0c64ab) | Mar 05, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [45733b1ef7](https://linux-hardware.org/?probe=45733b1ef7) | Mar 03, 2025 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [7fa12dfe91](https://linux-hardware.org/?probe=7fa12dfe91) | Feb 18, 2025 |
| Shenzhen M... | F7BSI                       | Mini pc     | [7223281a7f](https://linux-hardware.org/?probe=7223281a7f) | Feb 09, 2025 |
| Lenovo        | ThinkBook 14 G7 ARP 21MV    | Notebook    | [c5f8c776da](https://linux-hardware.org/?probe=c5f8c776da) | Jan 29, 2025 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b556ad5afc](https://linux-hardware.org/?probe=b556ad5afc) | Jan 27, 2025 |
| Unknown       | Unknown                     | Desktop     | [896ffe04a6](https://linux-hardware.org/?probe=896ffe04a6) | Jan 24, 2025 |
| Lenovo        | ThinkPad T60 2007WHH        | Notebook    | [12562aee82](https://linux-hardware.org/?probe=12562aee82) | Jan 04, 2025 |
| Toshiba       | QOSMIO X775                 | Notebook    | [339f01aea5](https://linux-hardware.org/?probe=339f01aea5) | Jan 03, 2025 |
| Intel         | NUC7i5DNB J57626-514        | Mini pc     | [ef0b742827](https://linux-hardware.org/?probe=ef0b742827) | Dec 26, 2024 |
| Toshiba       | QOSMIO X775                 | Notebook    | [23dbe1fbd6](https://linux-hardware.org/?probe=23dbe1fbd6) | Nov 26, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8640... | Notebook    | [746af80e1a](https://linux-hardware.org/?probe=746af80e1a) | Nov 01, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8640... | Notebook    | [3652f4d59d](https://linux-hardware.org/?probe=3652f4d59d) | Oct 31, 2024 |
| Dell          | Inspiron 15 3535            | Notebook    | [a4ce2a5ac9](https://linux-hardware.org/?probe=a4ce2a5ac9) | Oct 31, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d6dd06cfca](https://linux-hardware.org/?probe=d6dd06cfca) | Oct 28, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [1bcbbcf0d7](https://linux-hardware.org/?probe=1bcbbcf0d7) | Oct 26, 2024 |
| Dell          | Precision 5570              | Notebook    | [4f095c8d49](https://linux-hardware.org/?probe=4f095c8d49) | Oct 23, 2024 |
| Gigabyte      | B650 GAMING X AX V2         | Desktop     | [d1456149de](https://linux-hardware.org/?probe=d1456149de) | Oct 19, 2024 |
| Dell          | Latitude E5510              | Notebook    | [be1db31198](https://linux-hardware.org/?probe=be1db31198) | Oct 16, 2024 |
| Dell          | Inspiron 14 7435 2-in-1     | Convertible | [c5a73f63da](https://linux-hardware.org/?probe=c5a73f63da) | Oct 13, 2024 |
| Lenovo        | ThinkPad P52s 20LCS0MH00    | Notebook    | [07bbca04a0](https://linux-hardware.org/?probe=07bbca04a0) | Oct 06, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [cd854620f0](https://linux-hardware.org/?probe=cd854620f0) | Oct 06, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [72990baeb9](https://linux-hardware.org/?probe=72990baeb9) | Oct 06, 2024 |
| Dell          | Latitude 5410               | Notebook    | [91cbd5e4a0](https://linux-hardware.org/?probe=91cbd5e4a0) | Oct 05, 2024 |
| HP            | Pavilion 17                 | Notebook    | [19403f16a0](https://linux-hardware.org/?probe=19403f16a0) | Oct 05, 2024 |
| Dell          | Precision 5530              | Notebook    | [cdaacbe775](https://linux-hardware.org/?probe=cdaacbe775) | Oct 05, 2024 |
| Google        | Fleex                       | Notebook    | [05a6990467](https://linux-hardware.org/?probe=05a6990467) | Sep 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [c84318443d](https://linux-hardware.org/?probe=c84318443d) | Sep 25, 2024 |
| Dell          | 0J8G6F A02                  | Desktop     | [968e081763](https://linux-hardware.org/?probe=968e081763) | Sep 23, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [dde72fe9cf](https://linux-hardware.org/?probe=dde72fe9cf) | Sep 17, 2024 |
| Google        | Drobit                      | Notebook    | [2c312c592f](https://linux-hardware.org/?probe=2c312c592f) | Aug 31, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [47a7b5f3f3](https://linux-hardware.org/?probe=47a7b5f3f3) | Aug 26, 2024 |
| Lenovo        | Z710 20250                  | Notebook    | [a44ab1d0fd](https://linux-hardware.org/?probe=a44ab1d0fd) | Aug 24, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [50747463cb](https://linux-hardware.org/?probe=50747463cb) | Aug 21, 2024 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [4ab76c3030](https://linux-hardware.org/?probe=4ab76c3030) | Aug 20, 2024 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8154c94d2d](https://linux-hardware.org/?probe=8154c94d2d) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [c7919b571d](https://linux-hardware.org/?probe=c7919b571d) | Jul 31, 2024 |
| Google        | Nami                        | Notebook    | [c8a8ef90f9](https://linux-hardware.org/?probe=c8a8ef90f9) | Jul 17, 2024 |
| Acer          | Switch SA5-271              | Tablet      | [3275349eb1](https://linux-hardware.org/?probe=3275349eb1) | Jul 16, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [d8f579c579](https://linux-hardware.org/?probe=d8f579c579) | Jul 11, 2024 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [9217eb5455](https://linux-hardware.org/?probe=9217eb5455) | Jul 10, 2024 |
| MSI           | Creator M16 HX C14VFG       | Notebook    | [137c25b31b](https://linux-hardware.org/?probe=137c25b31b) | Jul 07, 2024 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [e3f4a68e11](https://linux-hardware.org/?probe=e3f4a68e11) | Jul 03, 2024 |
| Lenovo        | ThinkPad L570 20J9S34000    | Notebook    | [a600d8246f](https://linux-hardware.org/?probe=a600d8246f) | Jun 18, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [1e145ec645](https://linux-hardware.org/?probe=1e145ec645) | Jun 11, 2024 |
| Google        | Drobit                      | Notebook    | [0b0b8a096b](https://linux-hardware.org/?probe=0b0b8a096b) | Jun 10, 2024 |
| Dell          | 0NW73C A01                  | Desktop     | [2cc413a09c](https://linux-hardware.org/?probe=2cc413a09c) | Jun 10, 2024 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [d7a2a81328](https://linux-hardware.org/?probe=d7a2a81328) | Jun 09, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [40e2e9b9f4](https://linux-hardware.org/?probe=40e2e9b9f4) | Jun 07, 2024 |
| Samsung       | 950QDB                      | Convertible | [e3699f1d4c](https://linux-hardware.org/?probe=e3699f1d4c) | Jun 01, 2024 |
| Lenovo        | B40-80 80LS                 | Notebook    | [0630c37769](https://linux-hardware.org/?probe=0630c37769) | May 31, 2024 |
| Lenovo        | B40-80 80LS                 | Notebook    | [c0bbbf1450](https://linux-hardware.org/?probe=c0bbbf1450) | May 31, 2024 |
| LTD Delovo... | EVE 1494E ES1280EW          | Tablet      | [f9c62eb2b3](https://linux-hardware.org/?probe=f9c62eb2b3) | May 28, 2024 |
| Intel         | NUC7i5DNB J57626-514        | Mini pc     | [9c408725cf](https://linux-hardware.org/?probe=9c408725cf) | May 28, 2024 |
| Lenovo        | 330S-15ARR 81FB             | Notebook    | [7d5b244b02](https://linux-hardware.org/?probe=7d5b244b02) | May 22, 2024 |
| Timi          | RedmiBook 15                | Notebook    | [f86f533af7](https://linux-hardware.org/?probe=f86f533af7) | May 19, 2024 |
| Acer          | Aspire A315-31              | Notebook    | [e6b1ec681a](https://linux-hardware.org/?probe=e6b1ec681a) | May 17, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [cf3db9398d](https://linux-hardware.org/?probe=cf3db9398d) | Apr 22, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [6eeb53e317](https://linux-hardware.org/?probe=6eeb53e317) | Apr 22, 2024 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c7ceab8c20](https://linux-hardware.org/?probe=c7ceab8c20) | Apr 07, 2024 |
| Intel         | X99                         | Desktop     | [ce7d0c7c5d](https://linux-hardware.org/?probe=ce7d0c7c5d) | Apr 06, 2024 |
| HP            | 81B9 1000                   | All in one  | [cb43f1497c](https://linux-hardware.org/?probe=cb43f1497c) | Apr 05, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [5babc725b2](https://linux-hardware.org/?probe=5babc725b2) | Mar 30, 2024 |
| Dell          | 09M8Y8 A01                  | Desktop     | [c90acd6853](https://linux-hardware.org/?probe=c90acd6853) | Mar 29, 2024 |
| Infinix       | INBOOK X2 PLUS              | Notebook    | [823ba3ef42](https://linux-hardware.org/?probe=823ba3ef42) | Feb 21, 2024 |
| Gigabyte      | X79-UP4                     | Desktop     | [b3ef558527](https://linux-hardware.org/?probe=b3ef558527) | Feb 17, 2024 |
| Gigabyte      | X79-UP4                     | Desktop     | [3605afbba0](https://linux-hardware.org/?probe=3605afbba0) | Feb 16, 2024 |
| Lenovo        | ThinkPad T450s 20BWS1RT0... | Notebook    | [562ce94bd6](https://linux-hardware.org/?probe=562ce94bd6) | Feb 12, 2024 |
| AZW           | Gemini T45                  | Desktop     | [a07e2329bb](https://linux-hardware.org/?probe=a07e2329bb) | Feb 05, 2024 |
| AZW           | Gemini T45                  | Desktop     | [5caae813f4](https://linux-hardware.org/?probe=5caae813f4) | Feb 05, 2024 |
| Gigabyte      | X79-UP4                     | Desktop     | [32cafc74cf](https://linux-hardware.org/?probe=32cafc74cf) | Jan 28, 2024 |
| Sony          | VPCF215FX                   | Notebook    | [e7ac2326bd](https://linux-hardware.org/?probe=e7ac2326bd) | Jan 26, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [16e13e79b4](https://linux-hardware.org/?probe=16e13e79b4) | Jan 09, 2024 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [b811bdcbfd](https://linux-hardware.org/?probe=b811bdcbfd) | Jan 07, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [609aece6c1](https://linux-hardware.org/?probe=609aece6c1) | Dec 28, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [3acdabd584](https://linux-hardware.org/?probe=3acdabd584) | Dec 27, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7c88ff72d7](https://linux-hardware.org/?probe=7c88ff72d7) | Dec 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6533a19479](https://linux-hardware.org/?probe=6533a19479) | Dec 18, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [f4932d00ca](https://linux-hardware.org/?probe=f4932d00ca) | Dec 16, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [03b847bfea](https://linux-hardware.org/?probe=03b847bfea) | Dec 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [c04e33a35b](https://linux-hardware.org/?probe=c04e33a35b) | Dec 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8d856712c9](https://linux-hardware.org/?probe=8d856712c9) | Dec 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6be46afd51](https://linux-hardware.org/?probe=6be46afd51) | Dec 10, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [6364cca19b](https://linux-hardware.org/?probe=6364cca19b) | Dec 07, 2023 |
| Fujitsu       | LIFEBOOK UH554              | Notebook    | [cfdc07bd6d](https://linux-hardware.org/?probe=cfdc07bd6d) | Dec 05, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [4dee905c74](https://linux-hardware.org/?probe=4dee905c74) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [189d6b3a6f](https://linux-hardware.org/?probe=189d6b3a6f) | Nov 25, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [341114c78a](https://linux-hardware.org/?probe=341114c78a) | Oct 31, 2023 |
| HP            | 805E                        | All in one  | [94013a53b7](https://linux-hardware.org/?probe=94013a53b7) | Oct 22, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [9c4b6341e0](https://linux-hardware.org/?probe=9c4b6341e0) | Oct 18, 2023 |
| HP            | 805E                        | All in one  | [04d2314394](https://linux-hardware.org/?probe=04d2314394) | Oct 16, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [f0be6c3478](https://linux-hardware.org/?probe=f0be6c3478) | Oct 04, 2023 |
| Pegatron      | 2A9A                        | Desktop     | [f4c8507e2b](https://linux-hardware.org/?probe=f4c8507e2b) | Oct 02, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [aacbd7403c](https://linux-hardware.org/?probe=aacbd7403c) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [a7a57a8a56](https://linux-hardware.org/?probe=a7a57a8a56) | Aug 10, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [1764158bf6](https://linux-hardware.org/?probe=1764158bf6) | Aug 03, 2023 |
| Lenovo        | ThinkPad L570 20JRS06XGE    | Notebook    | [cae3db2f8d](https://linux-hardware.org/?probe=cae3db2f8d) | Jul 28, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [663261b61f](https://linux-hardware.org/?probe=663261b61f) | Jul 04, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dedc98e84e](https://linux-hardware.org/?probe=dedc98e84e) | Jun 10, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [dbb3f8fa6f](https://linux-hardware.org/?probe=dbb3f8fa6f) | Apr 14, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [83f4df6005](https://linux-hardware.org/?probe=83f4df6005) | Apr 12, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [35bfc8316b](https://linux-hardware.org/?probe=35bfc8316b) | Mar 23, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [170ebcea1c](https://linux-hardware.org/?probe=170ebcea1c) | Mar 22, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [23c3c64afa](https://linux-hardware.org/?probe=23c3c64afa) | Mar 17, 2023 |
| Foxconn       | 2AB1                        | Desktop     | [bc6f32a856](https://linux-hardware.org/?probe=bc6f32a856) | Mar 17, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [fbe7aabd96](https://linux-hardware.org/?probe=fbe7aabd96) | Mar 12, 2023 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [e61ebad4f6](https://linux-hardware.org/?probe=e61ebad4f6) | Mar 12, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [58bcb8bf04](https://linux-hardware.org/?probe=58bcb8bf04) | Feb 18, 2023 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [26fd2a9f6a](https://linux-hardware.org/?probe=26fd2a9f6a) | Jan 29, 2023 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [8bc1c22b23](https://linux-hardware.org/?probe=8bc1c22b23) | Jan 25, 2023 |
| Biostar       | H310MHP                     | Desktop     | [6495c0927b](https://linux-hardware.org/?probe=6495c0927b) | Jan 16, 2023 |
| Google        | Blooglet                    | Notebook    | [b3a163b99b](https://linux-hardware.org/?probe=b3a163b99b) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | Notebook    | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| HP            | 245 G5 Notebook PC          | Notebook    | [deed1dcf4d](https://linux-hardware.org/?probe=deed1dcf4d) | Nov 21, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [be6b59f511](https://linux-hardware.org/?probe=be6b59f511) | Oct 07, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [5e8d80eacc](https://linux-hardware.org/?probe=5e8d80eacc) | Sep 18, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [1eb939b09f](https://linux-hardware.org/?probe=1eb939b09f) | Sep 12, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [c1a16c7963](https://linux-hardware.org/?probe=c1a16c7963) | Sep 06, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [2ae4968612](https://linux-hardware.org/?probe=2ae4968612) | Sep 06, 2022 |
| HP            | Notebook                    | Notebook    | [2d11bc2975](https://linux-hardware.org/?probe=2d11bc2975) | Aug 26, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [cdee8ca864](https://linux-hardware.org/?probe=cdee8ca864) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [dfd7afda26](https://linux-hardware.org/?probe=dfd7afda26) | Jul 27, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [616a2b7524](https://linux-hardware.org/?probe=616a2b7524) | Jul 12, 2022 |
| Dell          | Latitude E7440              | Notebook    | [b57ab513eb](https://linux-hardware.org/?probe=b57ab513eb) | Jul 06, 2022 |
| HP            | 240 G7                      | Notebook    | [2af5911cf8](https://linux-hardware.org/?probe=2af5911cf8) | Jun 12, 2022 |
| ASUSTek       | D940MX                      | Desktop     | [bdc8831182](https://linux-hardware.org/?probe=bdc8831182) | Mar 28, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV02     | Notebook    | [7a7b9fa959](https://linux-hardware.org/?probe=7a7b9fa959) | Feb 13, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV02     | Notebook    | [96577868b7](https://linux-hardware.org/?probe=96577868b7) | Jan 28, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Ultramarine 40       | 44        | 30.34%  |
| Ultramarine 39       | 24        | 16.55%  |
| Ultramarine 42       | 18        | 12.41%  |
| Ultramarine 41       | 18        | 12.41%  |
| Ultramarine Linux 36 | 14        | 9.66%   |
| Ultramarine 38       | 10        | 6.9%    |
| Ultramarine 37       | 8         | 5.52%   |
| Ultramarine 43       | 7         | 4.83%   |
| Ultramarine Linux 35 | 2         | 1.38%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Ultramarine | 137       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.8.11-300.fc40.x86_64        | 17        | 10.97%  |
| 6.8.10-300.fc40.x86_64        | 4         | 2.58%   |
| 6.6.2-201.fc39.x86_64         | 4         | 2.58%   |
| 6.17.4-200.fc42.x86_64        | 4         | 2.58%   |
| 6.13.10-200.fc41.x86_64       | 4         | 2.58%   |
| 6.7.4-200.fc39.x86_64         | 3         | 1.94%   |
| 6.6.4-200.fc39.x86_64         | 3         | 1.94%   |
| 6.17.9-300.fc43.x86_64        | 3         | 1.94%   |
| 6.16.11-1.surface.fc42.x86_64 | 3         | 1.94%   |
| 5.19.4-200.fc36.x86_64        | 3         | 1.94%   |
| 6.9.8-200.fc40.x86_64         | 2         | 1.29%   |
| 6.9.7-200.fc40.x86_64         | 2         | 1.29%   |
| 6.9.5-200.fc40.x86_64         | 2         | 1.29%   |
| 6.8.4-200.fc39.x86_64         | 2         | 1.29%   |
| 6.6.9-200.fc39.x86_64         | 2         | 1.29%   |
| 6.6.3-200.fc39.x86_64         | 2         | 1.29%   |
| 6.6.13-200.fc39.x86_64        | 2         | 1.29%   |
| 6.5.6-200.fc38.x86_64         | 2         | 1.29%   |
| 6.17.12-300.fc43.x86_64       | 2         | 1.29%   |
| 6.16.10-200.fc42.x86_64       | 2         | 1.29%   |
| 6.12.6-200.fc41.x86_64        | 2         | 1.29%   |
| 6.12.10-200.fc41.x86_64       | 2         | 1.29%   |
| 6.11.3-200.fc40.x86_64        | 2         | 1.29%   |
| 6.10.9-200.fc40.x86_64        | 2         | 1.29%   |
| 6.10.12-200.fc40.x86_64       | 2         | 1.29%   |
| 6.1.7-200.fc37.x86_64         | 2         | 1.29%   |
| 6.1.18-200.fc37.x86_64        | 2         | 1.29%   |
| 6.0.8-200.fc36.x86_64         | 2         | 1.29%   |
| 5.17.7-300.fc36.x86_64        | 2         | 1.29%   |
| 6.9.4-200.fc40.x86_64         | 1         | 0.65%   |
| 6.9.12-200.fc40.x86_64        | 1         | 0.65%   |
| 6.9.11-200.fc40.x86_64        | 1         | 0.65%   |
| 6.8.9-300.fc40.x86_64         | 1         | 0.65%   |
| 6.8.9-200.fc39.x86_64         | 1         | 0.65%   |
| 6.8.8-300.fc40.x86_64         | 1         | 0.65%   |
| 6.8.6-200.fc39.x86_64         | 1         | 0.65%   |
| 6.8.2-300.fc40.x86_64         | 1         | 0.65%   |
| 6.8.12-300.fc40.x86_64        | 1         | 0.65%   |
| 6.8.11-200.fc39.x86_64        | 1         | 0.65%   |
| 6.7.11-200.fc39.x86_64        | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8.11  | 18        | 11.61%  |
| 6.8.10  | 4         | 2.58%   |
| 6.6.2   | 4         | 2.58%   |
| 6.17.4  | 4         | 2.58%   |
| 6.16.11 | 4         | 2.58%   |
| 6.13.10 | 4         | 2.58%   |
| 6.7.4   | 3         | 1.94%   |
| 6.6.4   | 3         | 1.94%   |
| 6.17.9  | 3         | 1.94%   |
| 6.16.10 | 3         | 1.94%   |
| 6.1.7   | 3         | 1.94%   |
| 5.19.4  | 3         | 1.94%   |
| 6.9.8   | 2         | 1.29%   |
| 6.9.7   | 2         | 1.29%   |
| 6.9.5   | 2         | 1.29%   |
| 6.8.9   | 2         | 1.29%   |
| 6.8.4   | 2         | 1.29%   |
| 6.6.9   | 2         | 1.29%   |
| 6.6.3   | 2         | 1.29%   |
| 6.6.13  | 2         | 1.29%   |
| 6.5.6   | 2         | 1.29%   |
| 6.17.12 | 2         | 1.29%   |
| 6.16.9  | 2         | 1.29%   |
| 6.12.6  | 2         | 1.29%   |
| 6.12.10 | 2         | 1.29%   |
| 6.11.4  | 2         | 1.29%   |
| 6.11.3  | 2         | 1.29%   |
| 6.10.9  | 2         | 1.29%   |
| 6.10.12 | 2         | 1.29%   |
| 6.1.5   | 2         | 1.29%   |
| 6.1.18  | 2         | 1.29%   |
| 6.0.8   | 2         | 1.29%   |
| 5.17.7  | 2         | 1.29%   |
| 6.9.4   | 1         | 0.65%   |
| 6.9.12  | 1         | 0.65%   |
| 6.9.11  | 1         | 0.65%   |
| 6.8.8   | 1         | 0.65%   |
| 6.8.6   | 1         | 0.65%   |
| 6.8.2   | 1         | 0.65%   |
| 6.8.12  | 1         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.8     | 30        | 19.74%  |
| 6.6     | 15        | 9.87%   |
| 6.16    | 13        | 8.55%   |
| 6.17    | 11        | 7.24%   |
| 6.10    | 9         | 5.92%   |
| 6.1     | 9         | 5.92%   |
| 6.9     | 8         | 5.26%   |
| 6.13    | 7         | 4.61%   |
| 6.12    | 7         | 4.61%   |
| 5.19    | 6         | 3.95%   |
| 6.5     | 5         | 3.29%   |
| 6.11    | 5         | 3.29%   |
| 6.7     | 4         | 2.63%   |
| 6.4     | 4         | 2.63%   |
| 5.18    | 3         | 1.97%   |
| 5.17    | 3         | 1.97%   |
| 6.3     | 2         | 1.32%   |
| 6.2     | 2         | 1.32%   |
| 6.15    | 2         | 1.32%   |
| 6.14    | 2         | 1.32%   |
| 6.0     | 2         | 1.32%   |
| 5.16    | 2         | 1.32%   |
| 5.15    | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 137       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 42        | 29.79%  |
| KDE6       | 39        | 27.66%  |
| Budgie     | 32        | 22.7%   |
| Pantheon   | 10        | 7.09%   |
| KDE5       | 10        | 7.09%   |
| KDE4       | 3         | 2.13%   |
| XFCE       | 2         | 1.42%   |
| X-Cinnamon | 1         | 0.71%   |
| sway       | 1         | 0.71%   |
| Cutefish   | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 82        | 58.57%  |
| X11     | 58        | 41.43%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 95        | 69.34%  |
| SDDM    | 20        | 14.6%   |
| LightDM | 11        | 8.03%   |
| GDM     | 11        | 8.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 88        | 63.31%  |
| en_GB | 8         | 5.76%   |
| en_CA | 7         | 5.04%   |
| de_DE | 7         | 5.04%   |
| es_ES | 4         | 2.88%   |
| ru_RU | 3         | 2.16%   |
| it_IT | 3         | 2.16%   |
| es_MX | 2         | 1.44%   |
| es_CL | 2         | 1.44%   |
| en_IN | 2         | 1.44%   |
| en_AU | 2         | 1.44%   |
| de_CH | 2         | 1.44%   |
| pt_PT | 1         | 0.72%   |
| pt_BR | 1         | 0.72%   |
| pl_PL | 1         | 0.72%   |
| nl_BE | 1         | 0.72%   |
| nb_NO | 1         | 0.72%   |
| hu_HU | 1         | 0.72%   |
| fr_FR | 1         | 0.72%   |
| fr_CA | 1         | 0.72%   |
| es_AR | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 74        | 53.24%  |
| EFI  | 65        | 46.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 116       | 84.06%  |
| Ext4    | 12        | 8.7%    |
| Tmpfs   | 6         | 4.35%   |
| Overlay | 3         | 2.17%   |
| Xfs     | 1         | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 95        | 69.34%  |
| GPT     | 42        | 30.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 94.16%  |
| Yes       | 8         | 5.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 91.24%  |
| Yes       | 12        | 8.76%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 25        | 18.25%  |
| Hewlett-Packard                      | 16        | 11.68%  |
| Dell                                 | 16        | 11.68%  |
| ASUSTek Computer                     | 15        | 10.95%  |
| Gigabyte Technology                  | 11        | 8.03%   |
| MSI                                  | 7         | 5.11%   |
| Microsoft                            | 5         | 3.65%   |
| Google                               | 5         | 3.65%   |
| Apple                                | 4         | 2.92%   |
| Acer                                 | 4         | 2.92%   |
| Intel                                | 3         | 2.19%   |
| Fujitsu                              | 3         | 2.19%   |
| Unknown                              | 3         | 2.19%   |
| Timi                                 | 2         | 1.46%   |
| Chuwi                                | 2         | 1.46%   |
| Toshiba                              | 1         | 0.73%   |
| Sony                                 | 1         | 0.73%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.73%   |
| Samsung Electronics                  | 1         | 0.73%   |
| Razer                                | 1         | 0.73%   |
| QIYIDA                               | 1         | 0.73%   |
| PELADN                               | 1         | 0.73%   |
| Pegatron                             | 1         | 0.73%   |
| LTD Delovoy Office                   | 1         | 0.73%   |
| Infinix                              | 1         | 0.73%   |
| GPU Company                          | 1         | 0.73%   |
| Framework                            | 1         | 0.73%   |
| Foxconn                              | 1         | 0.73%   |
| Biostar                              | 1         | 0.73%   |
| ASRock                               | 1         | 0.73%   |
| AMI                                  | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 3         | 2.19%   |
| Timi RedmiBook 15                                     | 2         | 1.46%   |
| Microsoft Surface Pro                                 | 2         | 1.46%   |
| Lenovo ThinkPad T480s 20L8S86400                      | 2         | 1.46%   |
| Toshiba QOSMIO X775                                   | 1         | 0.73%   |
| Sony VPCF215FX                                        | 1         | 0.73%   |
| Shenzhen Meigao Electronic Equipment EliteMini Series | 1         | 0.73%   |
| Samsung 950QDB                                        | 1         | 0.73%   |
| Razer Blade 15 Base Model (Mid 2021) - RZ09-0410      | 1         | 0.73%   |
| QIYIDA ED4 V1.1                                       | 1         | 0.73%   |
| PELADN WI-6                                           | 1         | 0.73%   |
| Pegatron 600-1352                                     | 1         | 0.73%   |
| MSI MS-7E06                                           | 1         | 0.73%   |
| MSI MS-7C91                                           | 1         | 0.73%   |
| MSI MS-7C87                                           | 1         | 0.73%   |
| MSI MS-7C56                                           | 1         | 0.73%   |
| MSI MS-7C52                                           | 1         | 0.73%   |
| MSI MS-7B84                                           | 1         | 0.73%   |
| MSI Creator M16 HX C14VFG                             | 1         | 0.73%   |
| Microsoft Surface Laptop Go                           | 1         | 0.73%   |
| Microsoft Surface Go 2                                | 1         | 0.73%   |
| Microsoft Surface Book 2                              | 1         | 0.73%   |
| LTD Delovoy Office EVE 1494E ES1280EW                 | 1         | 0.73%   |
| Lenovo Z710 20250                                     | 1         | 0.73%   |
| Lenovo ThinkPad T60 2007WHH                           | 1         | 0.73%   |
| Lenovo ThinkPad T495s 20QKS0SD23                      | 1         | 0.73%   |
| Lenovo ThinkPad T450s 20BWS1RT00                      | 1         | 0.73%   |
| Lenovo ThinkPad T430 2349L26                          | 1         | 0.73%   |
| Lenovo ThinkPad P53 20QQS2J700                        | 1         | 0.73%   |
| Lenovo ThinkPad P52s 20LCS0MH00                       | 1         | 0.73%   |
| Lenovo ThinkPad P50 20EQS0VV02                        | 1         | 0.73%   |
| Lenovo ThinkPad P50 20E0S1EWAT                        | 1         | 0.73%   |
| Lenovo ThinkPad P1 Gen 7 21KWS0X000                   | 1         | 0.73%   |
| Lenovo ThinkPad L570 20JRS06XGE                       | 1         | 0.73%   |
| Lenovo ThinkPad L570 20J9S34000                       | 1         | 0.73%   |
| Lenovo ThinkPad E15 Gen 2 20TD0018US                  | 1         | 0.73%   |
| Lenovo ThinkCentre M58 6258D3G                        | 1         | 0.73%   |
| Lenovo ThinkBook 14 G7 ARP 21MV                       | 1         | 0.73%   |
| Lenovo MIIX 520-12IKB 81CG                            | 1         | 0.73%   |
| Lenovo LOQ 15APH8 82XT                                | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo ThinkPad                                | 14        | 10.22%  |
| Microsoft Surface                              | 5         | 3.65%   |
| Dell XPS                                       | 4         | 2.92%   |
| Dell Inspiron                                  | 4         | 2.92%   |
| HP Pavilion                                    | 3         | 2.19%   |
| HP Laptop                                      | 3         | 2.19%   |
| Dell Precision                                 | 3         | 2.19%   |
| Dell Latitude                                  | 3         | 2.19%   |
| ASUS ROG                                       | 3         | 2.19%   |
| Unknown                                        | 3         | 2.19%   |
| Timi RedmiBook                                 | 2         | 1.46%   |
| Lenovo IdeaPad                                 | 2         | 1.46%   |
| Gigabyte B650                                  | 2         | 1.46%   |
| Fujitsu LIFEBOOK                               | 2         | 1.46%   |
| ASUS Zenbook                                   | 2         | 1.46%   |
| ASUS PRIME                                     | 2         | 1.46%   |
| Acer Aspire                                    | 2         | 1.46%   |
| Toshiba QOSMIO                                 | 1         | 0.73%   |
| Sony VPCF215FX                                 | 1         | 0.73%   |
| Shenzhen Meigao Electronic Equipment EliteMini | 1         | 0.73%   |
| Samsung 950QDB                                 | 1         | 0.73%   |
| Razer Blade                                    | 1         | 0.73%   |
| QIYIDA ED4                                     | 1         | 0.73%   |
| PELADN WI-6                                    | 1         | 0.73%   |
| Pegatron 600-1352                              | 1         | 0.73%   |
| MSI MS-7E06                                    | 1         | 0.73%   |
| MSI MS-7C91                                    | 1         | 0.73%   |
| MSI MS-7C87                                    | 1         | 0.73%   |
| MSI MS-7C56                                    | 1         | 0.73%   |
| MSI MS-7C52                                    | 1         | 0.73%   |
| MSI MS-7B84                                    | 1         | 0.73%   |
| MSI Creator                                    | 1         | 0.73%   |
| LTD Delovoy Office EVE                         | 1         | 0.73%   |
| Lenovo Z710                                    | 1         | 0.73%   |
| Lenovo ThinkCentre                             | 1         | 0.73%   |
| Lenovo ThinkBook                               | 1         | 0.73%   |
| Lenovo MIIX                                    | 1         | 0.73%   |
| Lenovo LOQ                                     | 1         | 0.73%   |
| Lenovo Flex                                    | 1         | 0.73%   |
| Lenovo B40-80                                  | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 17        | 12.41%  |
| 2022 | 14        | 10.22%  |
| 2021 | 13        | 9.49%   |
| 2012 | 13        | 9.49%   |
| 2018 | 12        | 8.76%   |
| 2019 | 11        | 8.03%   |
| 2024 | 10        | 7.3%    |
| 2023 | 10        | 7.3%    |
| 2014 | 8         | 5.84%   |
| 2017 | 7         | 5.11%   |
| 2015 | 6         | 4.38%   |
| 2016 | 4         | 2.92%   |
| 2010 | 4         | 2.92%   |
| 2013 | 3         | 2.19%   |
| 2009 | 2         | 1.46%   |
| 2011 | 1         | 0.73%   |
| 2008 | 1         | 0.73%   |
| 2006 | 1         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 74        | 54.01%  |
| Desktop     | 43        | 31.39%  |
| Tablet      | 9         | 6.57%   |
| Convertible | 5         | 3.65%   |
| All in one  | 4         | 2.92%   |
| Mini pc     | 2         | 1.46%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 121       | 88.32%  |
| Enabled  | 16        | 11.68%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 132       | 96.35%  |
| Yes  | 5         | 3.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 31        | 22.3%   |
| 16.01-24.0  | 29        | 20.86%  |
| 4.01-8.0    | 28        | 20.14%  |
| 32.01-64.0  | 22        | 15.83%  |
| 3.01-4.0    | 13        | 9.35%   |
| 64.01-256.0 | 9         | 6.47%   |
| 24.01-32.0  | 6         | 4.32%   |
| 2.01-3.0    | 1         | 0.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 54        | 36%     |
| 2.01-3.0    | 37        | 24.67%  |
| 3.01-4.0    | 29        | 19.33%  |
| 1.01-2.0    | 15        | 10%     |
| 8.01-16.0   | 11        | 7.33%   |
| 32.01-64.0  | 1         | 0.67%   |
| 24.01-32.0  | 1         | 0.67%   |
| 64.01-256.0 | 1         | 0.67%   |
| 16.01-24.0  | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 80        | 56.34%  |
| 2      | 38        | 26.76%  |
| 3      | 14        | 9.86%   |
| 4      | 7         | 4.93%   |
| 10     | 1         | 0.7%    |
| 6      | 1         | 0.7%    |
| 5      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 75.91%  |
| Yes       | 33        | 24.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 72.26%  |
| No        | 38        | 27.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 91.24%  |
| No        | 12        | 8.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 81.16%  |
| No        | 26        | 18.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country             | Computers | Percent |
|---------------------|-----------|---------|
| USA                 | 55        | 39.57%  |
| Germany             | 10        | 7.19%   |
| UK                  | 7         | 5.04%   |
| Canada              | 7         | 5.04%   |
| Thailand            | 6         | 4.32%   |
| Spain               | 5         | 3.6%    |
| Italy               | 5         | 3.6%    |
| Switzerland         | 3         | 2.16%   |
| Russia              | 3         | 2.16%   |
| India               | 3         | 2.16%   |
| Romania             | 2         | 1.44%   |
| Poland              | 2         | 1.44%   |
| Mexico              | 2         | 1.44%   |
| Malaysia            | 2         | 1.44%   |
| Japan               | 2         | 1.44%   |
| Indonesia           | 2         | 1.44%   |
| Chile               | 2         | 1.44%   |
| Belgium             | 2         | 1.44%   |
| Australia           | 2         | 1.44%   |
| Argentina           | 2         | 1.44%   |
| Vietnam             | 1         | 0.72%   |
| Trinidad and Tobago | 1         | 0.72%   |
| Syria               | 1         | 0.72%   |
| Puerto Rico         | 1         | 0.72%   |
| Portugal            | 1         | 0.72%   |
| Philippines         | 1         | 0.72%   |
| Norway              | 1         | 0.72%   |
| Hungary             | 1         | 0.72%   |
| Hong Kong           | 1         | 0.72%   |
| Georgia             | 1         | 0.72%   |
| France              | 1         | 0.72%   |
| Egypt               | 1         | 0.72%   |
| Czechia             | 1         | 0.72%   |
| Brazil              | 1         | 0.72%   |
| Austria             | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Rancho Cordova         | 5         | 3.4%    |
| Bangkok                | 5         | 3.4%    |
| Sacramento             | 4         | 2.72%   |
| Minneapolis            | 4         | 2.72%   |
| Chicago                | 3         | 2.04%   |
| Zollikofen             | 2         | 1.36%   |
| Toronto                | 2         | 1.36%   |
| Ocean Springs          | 2         | 1.36%   |
| Nashville              | 2         | 1.36%   |
| Jamestown              | 2         | 1.36%   |
| Braunschweig           | 2         | 1.36%   |
| Albuquerque            | 2         | 1.36%   |
| Zagazig                | 1         | 0.68%   |
| Wroclaw                | 1         | 0.68%   |
| Windsor                | 1         | 0.68%   |
| Warsaw                 | 1         | 0.68%   |
| Wallowa                | 1         | 0.68%   |
| Vohl                   | 1         | 0.68%   |
| Victoria               | 1         | 0.68%   |
| Vegreville             | 1         | 0.68%   |
| Turin                  | 1         | 0.68%   |
| Tokyo                  | 1         | 0.68%   |
| Terrassa               | 1         | 0.68%   |
| Tbilisi                | 1         | 0.68%   |
| Syktyvkar              | 1         | 0.68%   |
| Sydney                 | 1         | 0.68%   |
| Streamwood             | 1         | 0.68%   |
| Stoke-on-Trent         | 1         | 0.68%   |
| Southampton            | 1         | 0.68%   |
| South Jordan           | 1         | 0.68%   |
| Skudai                 | 1         | 0.68%   |
| Schwadorf              | 1         | 0.68%   |
| Schwäbisch Hall       | 1         | 0.68%   |
| Santiago               | 1         | 0.68%   |
| San Pedro              | 1         | 0.68%   |
| San Miguel de Tucumán | 1         | 0.68%   |
| San Julian de Muskiz   | 1         | 0.68%   |
| Saint Paul             | 1         | 0.68%   |
| Round Rock             | 1         | 0.68%   |
| Rome                   | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 37        | 50     | 16.52%  |
| WDC                          | 18        | 22     | 8.04%   |
| Seagate                      | 18        | 20     | 8.04%   |
| Toshiba                      | 16        | 18     | 7.14%   |
| Sandisk                      | 16        | 18     | 7.14%   |
| Kingston                     | 13        | 21     | 5.8%    |
| Crucial                      | 12        | 14     | 5.36%   |
| Unknown                      | 10        | 10     | 4.46%   |
| Intel                        | 8         | 9      | 3.57%   |
| Micron/Crucial Technology    | 6         | 12     | 2.68%   |
| SK hynix                     | 5         | 7      | 2.23%   |
| Micron Technology            | 5         | 8      | 2.23%   |
| KIOXIA                       | 5         | 5      | 2.23%   |
| China                        | 4         | 4      | 1.79%   |
| Shenzhen Longsys Electronics | 3         | 3      | 1.34%   |
| Phison Electronics           | 3         | 4      | 1.34%   |
| Hitachi                      | 3         | 4      | 1.34%   |
| USB                          | 2         | 2      | 0.89%   |
| Silicon Motion               | 2         | 2      | 0.89%   |
| Realtek Semiconductor        | 2         | 3      | 0.89%   |
| OCZ                          | 2         | 2      | 0.89%   |
| Kingston Technology Company  | 2         | 2      | 0.89%   |
| JMicron Technology           | 2         | 2      | 0.89%   |
| Acer                         | 2         | 2      | 0.89%   |
| A-DATA Technology            | 2         | 2      | 0.89%   |
| Zheino                       | 1         | 1      | 0.45%   |
| Wibtek                       | 1         | 1      | 0.45%   |
| Team                         | 1         | 1      | 0.45%   |
| SPCC                         | 1         | 1      | 0.45%   |
| SABRENT                      | 1         | 1      | 0.45%   |
| PNY                          | 1         | 1      | 0.45%   |
| Patriot                      | 1         | 1      | 0.45%   |
| Netac                        | 1         | 1      | 0.45%   |
| MicroDream                   | 1         | 1      | 0.45%   |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.45%   |
| Lexar                        | 1         | 1      | 0.45%   |
| Leven                        | 1         | 1      | 0.45%   |
| INTEL SS                     | 1         | 1      | 0.45%   |
| HS-SSD-WAVE(S)               | 1         | 1      | 0.45%   |
| Gigabyte Technology          | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 5         | 2.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 5         | 2.09%   |
| Unknown MMC Card  64GB                               | 4         | 1.67%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 4         | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB                       | 3         | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1.26%   |
| Samsung SSD 870 QVO 1TB                              | 3         | 1.26%   |
| Samsung SSD 860 EVO 500GB                            | 3         | 1.26%   |
| Kingston SA400S37480G 480GB SSD                      | 3         | 1.26%   |
| Kingston SA400S37240G 240GB SSD                      | 3         | 1.26%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 256GB        | 3         | 1.26%   |
| Crucial CT500MX500SSD1 500GB                         | 3         | 1.26%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 2         | 0.84%   |
| USB SanDisk 3.2Gen1 496GB                            | 2         | 0.84%   |
| Unknown MMC Card  128GB                              | 2         | 0.84%   |
| Toshiba MK1059GSM 1TB                                | 2         | 0.84%   |
| Shenzhen Longsys FORESEE XP1000F512G 512GB           | 2         | 0.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 2         | 0.84%   |
| Samsung SSD 840 EVO 250GB                            | 2         | 0.84%   |
| Samsung KUS020203M-B000 128GB                        | 2         | 0.84%   |
| Realtek SSD 4TB                                      | 2         | 0.84%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                  | 2         | 0.84%   |
| Micron/Crucial CT1000T500SSD8 1TB                    | 2         | 0.84%   |
| Hitachi HDS722020ALA330 2TB                          | 2         | 0.84%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 0.84%   |
| Crucial CT1000BX500SSD1 1TB                          | 2         | 0.84%   |
| Acer SSD SA100 1920GB                                | 2         | 0.84%   |
| Zheino CHN mSATAM3 512 512GB                         | 1         | 0.42%   |
| Wibtek W800S 512GB SSD                               | 1         | 0.42%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                     | 1         | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 1         | 0.42%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.42%   |
| WDC WDBNCE5000PNC 500GB SSD                          | 1         | 0.42%   |
| WDC WD5000LPCX-60VHAT0 500GB                         | 1         | 0.42%   |
| WDC WD5000AAKX-08U6AA0 500GB                         | 1         | 0.42%   |
| WDC WD4005FZBX-00K5WB0 4TB                           | 1         | 0.42%   |
| WDC WD20EARX-00PASB0 2TB                             | 1         | 0.42%   |
| WDC WD2000JD-22HBC0 200GB                            | 1         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB                               | 1         | 0.42%   |
| WDC WD10JFCX-68N6GN0 1TB                             | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 20     | 34.62%  |
| WDC                 | 15        | 18     | 28.85%  |
| Toshiba             | 13        | 15     | 25%     |
| Hitachi             | 3         | 4      | 5.77%   |
| Samsung Electronics | 1         | 2      | 1.92%   |
| JMicron Technology  | 1         | 1      | 1.92%   |
| Fujitsu             | 1         | 2      | 1.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 20.29%  |
| Crucial             | 12        | 14     | 17.39%  |
| Kingston            | 8         | 13     | 11.59%  |
| WDC                 | 4         | 4      | 5.8%    |
| China               | 4         | 4      | 5.8%    |
| SK hynix            | 2         | 2      | 2.9%    |
| OCZ                 | 2         | 2      | 2.9%    |
| Acer                | 2         | 2      | 2.9%    |
| A-DATA Technology   | 2         | 2      | 2.9%    |
| Wibtek              | 1         | 1      | 1.45%   |
| Toshiba             | 1         | 1      | 1.45%   |
| Team                | 1         | 1      | 1.45%   |
| SPCC                | 1         | 1      | 1.45%   |
| SanDisk             | 1         | 1      | 1.45%   |
| SABRENT             | 1         | 1      | 1.45%   |
| PNY                 | 1         | 1      | 1.45%   |
| Patriot             | 1         | 1      | 1.45%   |
| Netac               | 1         | 1      | 1.45%   |
| MicroDream          | 1         | 1      | 1.45%   |
| Leven               | 1         | 1      | 1.45%   |
| INTEL SS            | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| Gigabyte Technology | 1         | 1      | 1.45%   |
| EYOTA               | 1         | 1      | 1.45%   |
| ETOPSO              | 1         | 1      | 1.45%   |
| Emtec               | 1         | 1      | 1.45%   |
| Biostar             | 1         | 1      | 1.45%   |
| Actseno             | 1         | 2      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 80        | 113    | 41.03%  |
| SSD     | 56        | 81     | 28.72%  |
| HDD     | 41        | 62     | 21.03%  |
| MMC     | 10        | 10     | 5.13%   |
| Unknown | 8         | 8      | 4.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 80        | 112    | 44.2%   |
| SATA | 77        | 137    | 42.54%  |
| SAS  | 14        | 15     | 7.73%   |
| MMC  | 10        | 10     | 5.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 70     | 43.81%  |
| 0.51-1.0   | 40        | 51     | 38.1%   |
| 1.01-2.0   | 9         | 10     | 8.57%   |
| 3.01-4.0   | 4         | 5      | 3.81%   |
| 2.01-3.0   | 3         | 3      | 2.86%   |
| 4.01-10.0  | 2         | 3      | 1.9%    |
| 10.01-20.0 | 1         | 1      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1001-2000      | 38        | 26.21%  |
| 501-1000       | 28        | 19.31%  |
| 101-250        | 20        | 13.79%  |
| 251-500        | 14        | 9.66%   |
| Unknown        | 13        | 8.97%   |
| 1-20           | 12        | 8.28%   |
| More than 3000 | 8         | 5.52%   |
| 2001-3000      | 6         | 4.14%   |
| 51-100         | 4         | 2.76%   |
| 21-50          | 2         | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 34.67%  |
| 21-50     | 26        | 17.33%  |
| 101-250   | 16        | 10.67%  |
| 51-100    | 16        | 10.67%  |
| Unknown   | 13        | 8.67%   |
| 251-500   | 12        | 8%      |
| 501-1000  | 8         | 5.33%   |
| 1001-2000 | 5         | 3.33%   |
| 2001-3000 | 2         | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| China G521N256GB       | 1         | 1      | 50%     |
| Actseno MS02 128GB SSD | 1         | 2      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| China   | 1         | 1      | 50%     |
| Actseno | 1         | 2      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 100%    |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 103       | 209    | 72.03%  |
| Works    | 38        | 62     | 26.57%  |
| Malfunc  | 2         | 3      | 1.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 75        | 39.06%  |
| AMD                           | 31        | 16.15%  |
| Samsung Electronics           | 25        | 13.02%  |
| Sandisk                       | 15        | 7.81%   |
| Kingston Technology Company   | 8         | 4.17%   |
| Micron/Crucial Technology     | 6         | 3.13%   |
| Micron Technology             | 5         | 2.6%    |
| KIOXIA                        | 5         | 2.6%    |
| SK hynix                      | 4         | 2.08%   |
| Shenzhen Longsys Electronics  | 3         | 1.56%   |
| Phison Electronics            | 3         | 1.56%   |
| Toshiba America Info Systems  | 2         | 1.04%   |
| Silicon Motion                | 2         | 1.04%   |
| Realtek Semiconductor         | 2         | 1.04%   |
| Marvell Technology Group      | 2         | 1.04%   |
| Solidigm                      | 1         | 0.52%   |
| Nvidia                        | 1         | 0.52%   |
| MAXIO Technology (Hangzhou)   | 1         | 0.52%   |
| Integrated Technology Express | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 16        | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 7         | 3.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 6         | 2.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                                      | 5         | 2.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 5         | 2.4%    |
| Intel Volume Management Device NVMe RAID Controller                                                                | 5         | 2.4%    |
| AMD 500 Series Chipset SATA Controller                                                                             | 5         | 2.4%    |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                                                       | 4         | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]                                      | 4         | 1.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                                                         | 4         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 4         | 1.92%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 3         | 1.44%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 3         | 1.44%   |
| Samsung PM971 BGA PCIe x2 NVMe SSD                                                                                 | 3         | 1.44%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                                                     | 3         | 1.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 3         | 1.44%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 3         | 1.44%   |
| Intel SSD 670p Series [Keystone Harbor]                                                                            | 3         | 1.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 3         | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 3         | 1.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 3         | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]                                       | 3         | 1.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 3         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 1.44%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                                                       | 3         | 1.44%   |
| AMD 600 Series Chipset SATA Controller                                                                             | 3         | 1.44%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                                                 | 2         | 0.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 2         | 0.96%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                                              | 2         | 0.96%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                                                  | 2         | 0.96%   |
| Micron/Crucial T500 NVMe PCIe SSD                                                                                  | 2         | 0.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                                               | 2         | 0.96%   |
| Micron 2210 NVMe SSD [Cobain]                                                                                      | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller XG8                                                                                     | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 2         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 2         | 0.96%   |
| Intel Jasper Lake SATA AHCI Controller                                                                             | 2         | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 2         | 0.96%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                                                          | 2         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 91        | 48.4%   |
| NVMe | 80        | 42.55%  |
| RAID | 9         | 4.79%   |
| IDE  | 7         | 3.72%   |
| SAS  | 1         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 97        | 70.8%   |
| AMD    | 40        | 29.2%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 2.17%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 2         | 1.45%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 1.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.45%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 2         | 1.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 1.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.45%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 2         | 1.45%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 1.45%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 2         | 1.45%   |
| AMD Ryzen 7 7700X 8-Core Processor      | 2         | 1.45%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 1.45%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 1.45%   |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 0.72%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz     | 1         | 0.72%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.72%   |
| Intel Xeon CPU E5-2673 v2 @ 3.30GHz     | 1         | 0.72%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz      | 1         | 0.72%   |
| Intel Pentium CPU P6100 @ 2.00GHz       | 1         | 0.72%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 0.72%   |
| Intel Pentium CPU 4425Y @ 1.70GHz       | 1         | 0.72%   |
| Intel N100                              | 1         | 0.72%   |
| Intel Core Ultra 9 185H                 | 1         | 0.72%   |
| Intel Core i9-14900HX                   | 1         | 0.72%   |
| Intel Core i7-9850H CPU @ 2.60GHz       | 1         | 0.72%   |
| Intel Core i7-9700K CPU @ 3.60GHz       | 1         | 0.72%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 1         | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.72%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz        | 1         | 0.72%   |
| Intel Core i7-7820X CPU @ 3.60GHz       | 1         | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 0.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 1         | 0.72%   |
| Intel Core i7-6700T CPU @ 2.80GHz       | 1         | 0.72%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 1         | 0.72%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 27        | 19.71%  |
| Intel Core i5    | 26        | 18.98%  |
| Other            | 18        | 13.14%  |
| AMD Ryzen 5      | 13        | 9.49%   |
| AMD Ryzen 7      | 9         | 6.57%   |
| Intel Core i3    | 7         | 5.11%   |
| Intel Celeron    | 6         | 4.38%   |
| AMD Ryzen 9      | 6         | 4.38%   |
| Intel Xeon       | 4         | 2.92%   |
| Intel Pentium    | 3         | 2.19%   |
| AMD A6           | 3         | 2.19%   |
| Intel Core 2 Duo | 2         | 1.46%   |
| AMD Ryzen 7 PRO  | 2         | 1.46%   |
| Intel Core i9    | 1         | 0.73%   |
| Intel Core 2     | 1         | 0.73%   |
| Intel Core       | 1         | 0.73%   |
| Intel Atom       | 1         | 0.73%   |
| AMD Ryzen 3 PRO  | 1         | 0.73%   |
| AMD Ryzen 3      | 1         | 0.73%   |
| AMD FX           | 1         | 0.73%   |
| AMD Athlon II X4 | 1         | 0.73%   |
| AMD Athlon II X2 | 1         | 0.73%   |
| AMD A8           | 1         | 0.73%   |
| AMD A12          | 1         | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 48        | 34.78%  |
| 2      | 39        | 28.26%  |
| 6      | 20        | 14.49%  |
| 8      | 18        | 13.04%  |
| 12     | 4         | 2.9%    |
| 14     | 3         | 2.17%   |
| 16     | 2         | 1.45%   |
| 10     | 2         | 1.45%   |
| 32     | 1         | 0.72%   |
| 24     | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 99.27%  |
| 2      | 1         | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 108       | 78.83%  |
| 1      | 29        | 21.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 78.26%  |
| 0x806c1    | 2         | 1.45%   |
| 0x0a20120a | 2         | 1.45%   |
| 0x010000c8 | 2         | 1.45%   |
| 0x906ed    | 1         | 0.72%   |
| 0x906ea    | 1         | 0.72%   |
| 0x906a3    | 1         | 0.72%   |
| 0x806eb    | 1         | 0.72%   |
| 0x806ea    | 1         | 0.72%   |
| 0x706e5    | 1         | 0.72%   |
| 0x706a1    | 1         | 0.72%   |
| 0x506e3    | 1         | 0.72%   |
| 0x40651    | 1         | 0.72%   |
| 0x306c3    | 1         | 0.72%   |
| 0x306a9    | 1         | 0.72%   |
| 0x206a7    | 1         | 0.72%   |
| 0x20655    | 1         | 0.72%   |
| 0x1067a    | 1         | 0.72%   |
| 0x0a50000d | 1         | 0.72%   |
| 0x0a50000c | 1         | 0.72%   |
| 0x08701030 | 1         | 0.72%   |
| 0x08701021 | 1         | 0.72%   |
| 0x08600103 | 1         | 0.72%   |
| 0x08101016 | 1         | 0.72%   |
| 0x07030105 | 1         | 0.72%   |
| 0x06006705 | 1         | 0.72%   |
| 0x06006118 | 1         | 0.72%   |
| 0x0600081c | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 21.01%  |
| Unknown          | 17        | 12.32%  |
| Zen 3            | 13        | 9.42%   |
| TigerLake        | 10        | 7.25%   |
| Skylake          | 7         | 5.07%   |
| IvyBridge        | 7         | 5.07%   |
| Haswell          | 7         | 5.07%   |
| SandyBridge      | 6         | 4.35%   |
| Westmere         | 4         | 2.9%    |
| Alderlake Hybrid | 4         | 2.9%    |
| Zen 2            | 3         | 2.17%   |
| Zen              | 3         | 2.17%   |
| Goldmont plus    | 3         | 2.17%   |
| Excavator        | 3         | 2.17%   |
| Broadwell        | 3         | 2.17%   |
| Zen+             | 2         | 1.45%   |
| Tremont          | 2         | 1.45%   |
| Silvermont       | 2         | 1.45%   |
| Puma             | 2         | 1.45%   |
| Penryn           | 2         | 1.45%   |
| K10              | 2         | 1.45%   |
| IceLake          | 2         | 1.45%   |
| CometLake        | 2         | 1.45%   |
| Piledriver       | 1         | 0.72%   |
| Goldmont         | 1         | 0.72%   |
| Core             | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 50%     |
| Nvidia | 42        | 25.61%  |
| AMD    | 40        | 24.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 4.71%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 7         | 4.12%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 6         | 3.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 2.35%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 3         | 1.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 3         | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 1.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.76%   |
| AMD Raphael                                                               | 3         | 1.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3         | 1.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.76%   |
| AMD Barcelo                                                               | 3         | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 2         | 1.18%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 2         | 1.18%   |
| Nvidia GT218 [GeForce 210]                                                | 2         | 1.18%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 2         | 1.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.18%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 1.18%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 2         | 1.18%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                     | 2         | 1.18%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                     | 2         | 1.18%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 2         | 1.18%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.18%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.18%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.18%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 1.18%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 2         | 1.18%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 1.18%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                  | 2         | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.18%   |
| AMD Phoenix1                                                              | 2         | 1.18%   |
| AMD Navi 23 [Radeon RX 6650 XT / 6700S / 6800S]                           | 2         | 1.18%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 2         | 1.18%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.18%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 40.88%  |
| 1 x AMD        | 31        | 22.63%  |
| 1 x Nvidia     | 21        | 15.33%  |
| Intel + Nvidia | 18        | 13.14%  |
| 2 x AMD        | 4         | 2.92%   |
| AMD + Nvidia   | 3         | 2.19%   |
| Other          | 2         | 1.46%   |
| Intel + AMD    | 2         | 1.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 114       | 82.01%  |
| Proprietary | 18        | 12.95%  |
| Unknown     | 7         | 5.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 68.57%  |
| 0.01-0.5   | 12        | 8.57%   |
| 3.01-4.0   | 8         | 5.71%   |
| 1.01-2.0   | 8         | 5.71%   |
| 7.01-8.0   | 7         | 5%      |
| 0.51-1.0   | 5         | 3.57%   |
| 5.01-6.0   | 2         | 1.43%   |
| 8.01-16.0  | 2         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 12.41%  |
| BOE                     | 18        | 12.41%  |
| AU Optronics            | 18        | 12.41%  |
| LG Display              | 12        | 8.28%   |
| Chimei Innolux          | 10        | 6.9%    |
| Philips                 | 6         | 4.14%   |
| Dell                    | 6         | 4.14%   |
| Sharp                   | 5         | 3.45%   |
| Goldstar                | 5         | 3.45%   |
| Lenovo                  | 4         | 2.76%   |
| Apple                   | 4         | 2.76%   |
| AOC                     | 4         | 2.76%   |
| PANDA                   | 3         | 2.07%   |
| Panasonic               | 3         | 2.07%   |
| Hewlett-Packard         | 3         | 2.07%   |
| ASUSTek Computer        | 3         | 2.07%   |
| MSI                     | 2         | 1.38%   |
| InfoVision              | 2         | 1.38%   |
| BenQ                    | 2         | 1.38%   |
| WST                     | 1         | 0.69%   |
| Vizio                   | 1         | 0.69%   |
| VIE                     | 1         | 0.69%   |
| Unknown (XXX)           | 1         | 0.69%   |
| Toshiba                 | 1         | 0.69%   |
| Sceptre Tech            | 1         | 0.69%   |
| RTK                     | 1         | 0.69%   |
| KON                     | 1         | 0.69%   |
| InnoView                | 1         | 0.69%   |
| HannStar                | 1         | 0.69%   |
| Fujitsu Siemens         | 1         | 0.69%   |
| EXP                     | 1         | 0.69%   |
| Eizo                    | 1         | 0.69%   |
| CSOT                    | 1         | 0.69%   |
| Chi Mei Optoelectronics | 1         | 0.69%   |
| AOpen                   | 1         | 0.69%   |
| Ancor Communications    | 1         | 0.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch            | 3         | 2.07%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                 | 2         | 1.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2         | 1.38%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 2         | 1.38%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x174mm 14.0-inch         | 2         | 1.38%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                   | 2         | 1.38%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 2         | 1.38%   |
| AOC AG493UG7R4 AOC4930 3840x1080 1193x336mm 48.8-inch                   | 2         | 1.38%   |
| WST LCD Monitor WST2216 2160x1440 254x169mm 12.0-inch                   | 1         | 0.69%   |
| Vizio D50u-D1 VIZ1011 3840x2160 941x529mm 42.5-inch                     | 1         | 0.69%   |
| VIE D-GM215 VIEE003 1920x1080 480x260mm 21.5-inch                       | 1         | 0.69%   |
| Unknown (XXX) Beyo TV XXX9615 3840x2160 1210x680mm 54.6-inch            | 1         | 0.69%   |
| Toshiba TV TSB2017 3840x2160                                            | 1         | 0.69%   |
| Sharp LQ123P1JX32 SHP148A 2400x1600 259x173mm 12.3-inch                 | 1         | 0.69%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                 | 1         | 0.69%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                 | 1         | 0.69%   |
| Sceptre Tech Sceptre E22 SPT08D5 1920x1080 470x300mm 22.0-inch          | 1         | 0.69%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch       | 1         | 0.69%   |
| Samsung Electronics Odyssey G5 SAM7486 2560x1440 597x336mm 27.0-inch    | 1         | 0.69%   |
| Samsung Electronics LS24AG32x SAM71DA 1920x1080 527x296mm 23.8-inch     | 1         | 0.69%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch       | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3442 1366x768 344x194mm 15.5-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM7557 3840x2160 1872x1053mm 84.6-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 1         | 0.69%   |
| Samsung Electronics ATNA40CU05-0 SDC419C 2880x1800 302x189mm 14.0-inch  | 1         | 0.69%   |
| RTK HX150T RTK1920 1920x1080 344x195mm 15.6-inch                        | 1         | 0.69%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch               | 1         | 0.69%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                 | 1         | 0.69%   |
| Philips PHL 245B1 PHL094C 2560x1440 530x300mm 24.0-inch                 | 1         | 0.69%   |
| Philips PHL 240B9 PHL0966 1920x1200 518x324mm 24.1-inch                 | 1         | 0.69%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 1         | 0.69%   |
| Philips 190CW PHLC023 1440x900 408x255mm 18.9-inch                      | 1         | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.69%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                 | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 46.1%   |
| 3840x2160 (4K)     | 13        | 9.22%   |
| 1366x768 (WXGA)    | 13        | 9.22%   |
| 2560x1440 (QHD)    | 9         | 6.38%   |
| 1920x1200 (WUXGA)  | 5         | 3.55%   |
| 2160x1440          | 4         | 2.84%   |
| 1600x900 (HD+)     | 4         | 2.84%   |
| 2880x1920          | 3         | 2.13%   |
| 2560x1600          | 3         | 2.13%   |
| 3840x2400          | 2         | 1.42%   |
| 3840x1080          | 2         | 1.42%   |
| 2880x1800          | 2         | 1.42%   |
| 1280x800 (WXGA)    | 2         | 1.42%   |
| 3456x2160          | 1         | 0.71%   |
| 3440x1440          | 1         | 0.71%   |
| 3360x1440          | 1         | 0.71%   |
| 3072x1920          | 1         | 0.71%   |
| 2560x1080          | 1         | 0.71%   |
| 2400x1600          | 1         | 0.71%   |
| 2256x1504          | 1         | 0.71%   |
| 1920x540           | 1         | 0.71%   |
| 1920x1280          | 1         | 0.71%   |
| 1680x1050 (WSXGA+) | 1         | 0.71%   |
| 1440x900 (WXGA+)   | 1         | 0.71%   |
| 1280x720 (HD)      | 1         | 0.71%   |
| 1280x1024 (SXGA)   | 1         | 0.71%   |
| 1024x768 (XGA)     | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 32        | 22.38%  |
| 14     | 23        | 16.08%  |
| 13     | 11        | 7.69%   |
| 27     | 10        | 6.99%   |
| 24     | 10        | 6.99%   |
| 17     | 8         | 5.59%   |
| 21     | 7         | 4.9%    |
| 16     | 5         | 3.5%    |
| 31     | 4         | 2.8%    |
| 23     | 4         | 2.8%    |
| 18     | 3         | 2.1%    |
| 12     | 3         | 2.1%    |
| 84     | 2         | 1.4%    |
| 54     | 2         | 1.4%    |
| 48     | 2         | 1.4%    |
| 34     | 2         | 1.4%    |
| 32     | 2         | 1.4%    |
| 11     | 2         | 1.4%    |
| 10     | 2         | 1.4%    |
| 72     | 1         | 0.7%    |
| 65     | 1         | 0.7%    |
| 63     | 1         | 0.7%    |
| 44     | 1         | 0.7%    |
| 43     | 1         | 0.7%    |
| 37     | 1         | 0.7%    |
| 26     | 1         | 0.7%    |
| 22     | 1         | 0.7%    |
| 20     | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 59        | 42.14%  |
| 501-600     | 22        | 15.71%  |
| 201-300     | 18        | 12.86%  |
| 401-500     | 11        | 7.86%   |
| 351-400     | 9         | 6.43%   |
| 601-700     | 6         | 4.29%   |
| 1001-1500   | 6         | 4.29%   |
| 701-800     | 4         | 2.86%   |
| 1501-2000   | 3         | 2.14%   |
| 801-900     | 1         | 0.71%   |
| 901-1000    | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 99        | 72.79%  |
| 16/10 | 20        | 14.71%  |
| 3/2   | 9         | 6.62%   |
| 32/9  | 3         | 2.21%   |
| 4/3   | 2         | 1.47%   |
| 21/9  | 2         | 1.47%   |
| 5/4   | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 22.38%  |
| 81-90          | 28        | 19.58%  |
| 201-250        | 18        | 12.59%  |
| 301-350        | 10        | 6.99%   |
| 351-500        | 8         | 5.59%   |
| More than 1000 | 7         | 4.9%    |
| 121-130        | 6         | 4.2%    |
| 71-80          | 5         | 3.5%    |
| 111-120        | 5         | 3.5%    |
| 501-1000       | 5         | 3.5%    |
| 151-200        | 4         | 2.8%    |
| 61-70          | 3         | 2.1%    |
| 51-60          | 3         | 2.1%    |
| 251-300        | 3         | 2.1%    |
| 141-150        | 3         | 2.1%    |
| 41-50          | 1         | 0.7%    |
| 131-140        | 1         | 0.7%    |
| 91-100         | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 35.97%  |
| 51-100        | 38        | 27.34%  |
| 101-120       | 25        | 17.99%  |
| 161-240       | 15        | 10.79%  |
| More than 240 | 9         | 6.47%   |
| 1-50          | 2         | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 122       | 89.05%  |
| 2     | 12        | 8.76%   |
| 3     | 2         | 1.46%   |
| 0     | 1         | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 77        | 38.31%  |
| Realtek Semiconductor      | 75        | 37.31%  |
| Qualcomm Atheros           | 11        | 5.47%   |
| MediaTek                   | 9         | 4.48%   |
| Broadcom                   | 5         | 2.49%   |
| Samsung Electronics        | 3         | 1.49%   |
| NetGear                    | 3         | 1.49%   |
| Microsoft                  | 3         | 1.49%   |
| Marvell Technology Group   | 3         | 1.49%   |
| Ralink Technology          | 2         | 1%      |
| Ralink                     | 2         | 1%      |
| Broadcom Limited           | 2         | 1%      |
| Xiaomi                     | 1         | 0.5%    |
| TP-Link                    | 1         | 0.5%    |
| Sierra Wireless            | 1         | 0.5%    |
| Shenzhen Goodix Technology | 1         | 0.5%    |
| Nvidia                     | 1         | 0.5%    |
| Motorola PCS               | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 45        | 18.6%   |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 3.72%   |
| Intel Wireless 8265 / 8275                                             | 9         | 3.72%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 3.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 3.31%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 2.48%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 2.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 2.07%   |
| Intel Wireless 7265                                                    | 5         | 2.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 2.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1.65%   |
| Intel Wireless 8260                                                    | 4         | 1.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.24%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                      | 3         | 1.24%   |
| Intel Wireless 7260                                                    | 3         | 1.24%   |
| Intel Wireless 3165                                                    | 3         | 1.24%   |
| Intel Ethernet Controller I225-V                                       | 3         | 1.24%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3         | 1.24%   |
| Intel Centrino Wireless-N 2230                                         | 3         | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.83%   |
| Realtek 802.11ac NIC                                                   | 2         | 0.83%   |
| Ralink RT5370 Wireless Adapter                                         | 2         | 0.83%   |
| NetGear A6150                                                          | 2         | 0.83%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 2         | 0.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.83%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 68        | 51.13%  |
| Realtek Semiconductor    | 28        | 21.05%  |
| Qualcomm Atheros         | 10        | 7.52%   |
| MediaTek                 | 7         | 5.26%   |
| Broadcom                 | 4         | 3.01%   |
| NetGear                  | 3         | 2.26%   |
| Microsoft                | 3         | 2.26%   |
| Marvell Technology Group | 3         | 2.26%   |
| Ralink Technology        | 2         | 1.5%    |
| Ralink                   | 2         | 1.5%    |
| TP-Link                  | 1         | 0.75%   |
| Sierra Wireless          | 1         | 0.75%   |
| Broadcom Limited         | 1         | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 9         | 6.72%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 6.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.97%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 4.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 3.73%   |
| Intel Wireless 7265                                            | 5         | 3.73%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 5         | 3.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 2.99%   |
| Intel Wireless 8260                                            | 4         | 2.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 2.24%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 3         | 2.24%   |
| Intel Wireless 7260                                            | 3         | 2.24%   |
| Intel Wireless 3165                                            | 3         | 2.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 2.24%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 2.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.49%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.49%   |
| Realtek 802.11ac NIC                                           | 2         | 1.49%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.49%   |
| NetGear A6150                                                  | 2         | 1.49%   |
| Microsoft Xbox Wireless Adapter for Windows                    | 2         | 1.49%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.49%   |
| Intel 700 Series Chipset CNVi WiFi                             | 2         | 1.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 1.49%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.75%   |
| Sierra Wireless EM7455                                         | 1         | 0.75%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller    | 1         | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.75%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                      | 1         | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 62        | 59.62%  |
| Intel                 | 29        | 27.88%  |
| Samsung Electronics   | 3         | 2.88%   |
| Broadcom              | 3         | 2.88%   |
| MediaTek              | 2         | 1.92%   |
| Xiaomi                | 1         | 0.96%   |
| Qualcomm Atheros      | 1         | 0.96%   |
| Nvidia                | 1         | 0.96%   |
| Motorola PCS          | 1         | 0.96%   |
| Broadcom Limited      | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 45        | 42.06%  |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 8.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 4.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 3.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 2.8%    |
| Intel Ethernet Controller I225-V                                       | 3         | 2.8%    |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 2.8%    |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 2.8%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 1.87%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.93%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 1         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.93%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.93%   |
| Motorola PCS moto g100 pro                                             | 1         | 0.93%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.93%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.93%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 1         | 0.93%   |
| Intel 82573L Gigabit Ethernet Controller                               | 1         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe              | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 56.05%  |
| Ethernet | 97        | 43.5%   |
| Modem    | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 67.35%  |
| Ethernet | 48        | 32.65%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 72        | 52.55%  |
| 1     | 59        | 43.07%  |
| 3     | 4         | 2.92%   |
| 0     | 2         | 1.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 51.8%   |
| Yes  | 67        | 48.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 54.78%  |
| Realtek Semiconductor           | 17        | 14.78%  |
| Qualcomm Atheros Communications | 6         | 5.22%   |
| Foxconn / Hon Hai               | 6         | 5.22%   |
| Apple                           | 5         | 4.35%   |
| MediaTek                        | 4         | 3.48%   |
| Marvell Semiconductor           | 3         | 2.61%   |
| Realtek                         | 2         | 1.74%   |
| IMC Networks                    | 2         | 1.74%   |
| ASUSTek Computer                | 2         | 1.74%   |
| TP-Link                         | 1         | 0.87%   |
| Lite-On Technology              | 1         | 0.87%   |
| Cambridge Silicon Radio         | 1         | 0.87%   |
| Broadcom                        | 1         | 0.87%   |
| Belkin Components               | 1         | 0.87%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 18.97%  |
| Realtek Bluetooth Radio                                                             | 11        | 9.48%   |
| Intel AX201 Bluetooth                                                               | 10        | 8.62%   |
| Intel AX200 Bluetooth                                                               | 9         | 7.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 5.17%   |
| Intel Bluetooth Device                                                              | 5         | 4.31%   |
| MediaTek Wireless_Device                                                            | 4         | 3.45%   |
| Intel AX210 Bluetooth                                                               | 4         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.59%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 3         | 2.59%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.59%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 2.59%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.59%   |
| Realtek Bluetooth 5.3 Radio                                                         | 2         | 1.72%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.72%   |
| ASUS Bluetooth Radio                                                                | 2         | 1.72%   |
| TP-Link TP-T@- UB500 Adapter                                                        | 1         | 0.86%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.86%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.86%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.86%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.86%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.86%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.86%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.86%   |
| Belkin Components Bluetooth Mini Dongle                                             | 1         | 0.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.86%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 95        | 48.47%  |
| AMD                                          | 44        | 22.45%  |
| Nvidia                                       | 32        | 16.33%  |
| Texas Instruments                            | 3         | 1.53%   |
| Razer USA                                    | 3         | 1.53%   |
| Creative Technology                          | 3         | 1.53%   |
| C-Media Electronics                          | 3         | 1.53%   |
| Focusrite-Novation                           | 2         | 1.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.51%   |
| Solid State System                           | 1         | 0.51%   |
| SM950 Microphon                              | 1         | 0.51%   |
| RODE Microphones                             | 1         | 0.51%   |
| Realtek Semiconductor                        | 1         | 0.51%   |
| Plantronics                                  | 1         | 0.51%   |
| PC Mic                                       | 1         | 0.51%   |
| Logitech                                     | 1         | 0.51%   |
| JMTek                                        | 1         | 0.51%   |
| Elgato Systems                               | 1         | 0.51%   |
| BEHRINGER International                      | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 23        | 9.62%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 7.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 4.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 3.35%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 8         | 3.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.93%   |
| AMD Radeon High Definition Audio Controller                                | 7         | 2.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.67%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.26%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.26%   |
| Nvidia AD107 High Definition Audio Controller                              | 3         | 1.26%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.26%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.84%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.84%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.84%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2         | 0.84%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.84%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 0.84%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.84%   |
| Focusrite-Novation Scarlett Solo USB                                       | 2         | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.84%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 2         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 13        | 26.53%  |
| SK hynix            | 11        | 22.45%  |
| Micron Technology   | 8         | 16.33%  |
| Ramaxel Technology  | 3         | 6.12%   |
| Kingston            | 3         | 6.12%   |
| Crucial             | 2         | 4.08%   |
| Corsair             | 2         | 4.08%   |
| Unknown (ABCD)      | 1         | 2.04%   |
| Timetec             | 1         | 2.04%   |
| Silicon Power       | 1         | 2.04%   |
| PNY                 | 1         | 2.04%   |
| Patriot             | 1         | 2.04%   |
| Lexar               | 1         | 2.04%   |
| A-DATA Technology   | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 5.77%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 2         | 3.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.92%   |
| Timetec RAM 32NUS1R8-16 16GB SODIMM DDR4 3200MT/s                | 1         | 1.92%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.92%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 1.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMCG88AEBSA095N 32GB SODIMM DDR5 4800MT/s           | 1         | 1.92%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.92%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| SK hynix RAM HMA425S6BJR6N-UH 2GB DDR4 2400MT/s                  | 1         | 1.92%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 1.92%   |
| Silicon Power RAM Module 16GB DIMM DDR4 2133MT/s                 | 1         | 1.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.92%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 1         | 1.92%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.92%   |
| Samsung RAM K3KL8L80CM-MGCT 4GB SODIMM LPDDR5 7500MT/s           | 1         | 1.92%   |
| Ramaxel RAM RMSA3340MB88HBF-3200 16GB SODIMM DDR4 3200MT/s       | 1         | 1.92%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 1.92%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.92%   |
| PNY RAM M4S16S681LJJJ43-12 16GB SODIMM DDR4 2667MT/s             | 1         | 1.92%   |
| Patriot RAM 2666 C16 Series 16GB DIMM DDR4 3400MT/s              | 1         | 1.92%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.92%   |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s   | 1         | 1.92%   |
| Micron RAM 53D512M64D4RQ-046 8192MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.92%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.92%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| Lexar RAM LD4AS008G-3200ST 8GB SODIMM DDR4 3200MT/s              | 1         | 1.92%   |
| Kingston RAM KHX2400C14S4/8G 8GB SODIMM DDR4 2400MT/s            | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 25        | 56.82%  |
| DDR3   | 7         | 15.91%  |
| LPDDR4 | 6         | 13.64%  |
| DDR5   | 3         | 6.82%   |
| LPDDR3 | 2         | 4.55%   |
| LPDDR5 | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 72.09%  |
| Row Of Chips | 6         | 13.95%  |
| DIMM         | 5         | 11.63%  |
| Unknown      | 1         | 2.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 53.33%  |
| 16384 | 11        | 24.44%  |
| 4096  | 7         | 15.56%  |
| 2048  | 2         | 4.44%   |
| 32768 | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 25.53%  |
| 2667  | 10        | 21.28%  |
| 2400  | 5         | 10.64%  |
| 1600  | 5         | 10.64%  |
| 4267  | 3         | 6.38%   |
| 2133  | 2         | 4.26%   |
| 8400  | 1         | 2.13%   |
| 7500  | 1         | 2.13%   |
| 6000  | 1         | 2.13%   |
| 5600  | 1         | 2.13%   |
| 4800  | 1         | 2.13%   |
| 3400  | 1         | 2.13%   |
| 3266  | 1         | 2.13%   |
| 1867  | 1         | 2.13%   |
| 1800  | 1         | 2.13%   |
| 1066  | 1         | 2.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 33.33%  |
| Seiko Epson         | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| HP LaserJet 1012           | 2         | 33.33%  |
| Seiko Epson ET-2810 Series | 1         | 16.67%  |
| Samsung M2070 Series       | 1         | 16.67%  |
| Canon TS3300 series        | 1         | 16.67%  |
| Brother MFC-L2740DW        | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Microdia                               | 16        | 15.24%  |
| Chicony Electronics                    | 16        | 15.24%  |
| Quanta                                 | 10        | 9.52%   |
| Sunplus Innovation Technology          | 7         | 6.67%   |
| Realtek Semiconductor                  | 7         | 6.67%   |
| Bison Electronics                      | 7         | 6.67%   |
| IMC Networks                           | 6         | 5.71%   |
| Apple                                  | 6         | 5.71%   |
| Logitech                               | 5         | 4.76%   |
| Luxvisions Innotech Limited            | 4         | 3.81%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.81%   |
| Lite-On Technology                     | 2         | 1.9%    |
| USB Camera CS                          | 1         | 0.95%   |
| Unknown                                | 1         | 0.95%   |
| Syntek                                 | 1         | 0.95%   |
| Shinetech                              | 1         | 0.95%   |
| Shine-optics                           | 1         | 0.95%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.95%   |
| Samsung Electronics                    | 1         | 0.95%   |
| Ricoh                                  | 1         | 0.95%   |
| Primax Electronics                     | 1         | 0.95%   |
| Linux Foundation                       | 1         | 0.95%   |
| Lenovo                                 | 1         | 0.95%   |
| Elgato Systems                         | 1         | 0.95%   |
| ARC International                      | 1         | 0.95%   |
| Alcor Micro                            | 1         | 0.95%   |
| Acer                                   | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 6         | 5.71%   |
| Chicony Integrated Camera                           | 6         | 5.71%   |
| Bison Integrated Camera                             | 4         | 3.81%   |
| Sunplus USB 2.0 Camera                              | 2         | 1.9%    |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.9%    |
| Realtek Lenovo EasyCamera                           | 2         | 1.9%    |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 1.9%    |
| Quanta HP Wide Vision HD Camera                     | 2         | 1.9%    |
| Microdia Webcam Vitade AF                           | 2         | 1.9%    |
| Microdia USB 2.0 Camera                             | 2         | 1.9%    |
| Microdia Integrated_Webcam_FHD                      | 2         | 1.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.9%    |
| IMC Networks XiaoMi Webcam                          | 2         | 1.9%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.9%    |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.9%    |
| Chicony HP Truevision HD                            | 2         | 1.9%    |
| Chicony FJ Camera                                   | 2         | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 2         | 1.9%    |
| Apple FaceTime HD Camera                            | 2         | 1.9%    |
| Apple Built-in iSight                               | 2         | 1.9%    |
| USB Camera CS USB Camera CS                         | 1         | 0.95%   |
| Unknown HD camera                                   | 1         | 0.95%   |
| Syntek Integrated Camera                            | 1         | 0.95%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.95%   |
| Sunplus Integrated Camera                           | 1         | 0.95%   |
| Sunplus Full HD webcam                              | 1         | 0.95%   |
| Shinetech USB2.0 FHD UVC WebCam                     | 1         | 0.95%   |
| Shine-optics USB2.0 HD UVC WebCam                   | 1         | 0.95%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 1         | 0.95%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.95%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.95%   |
| Realtek WebCamera                                   | 1         | 0.95%   |
| Realtek USB Camera                                  | 1         | 0.95%   |
| Realtek Laptop Camera                               | 1         | 0.95%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.95%   |
| Realtek HP Wide Vision HD Camera                    | 1         | 0.95%   |
| Quanta VGA WebCam                                   | 1         | 0.95%   |
| Quanta HP True Vision FHD Camera                    | 1         | 0.95%   |
| Quanta HP HD Camera                                 | 1         | 0.95%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 46.67%  |
| Shenzhen Goodix Technology | 3         | 20%     |
| Validity Sensors           | 2         | 13.33%  |
| Elan Microelectronics      | 2         | 13.33%  |
| STMicroelectronics         | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 13.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 13.33%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 6.67%   |
| Synaptics Fingerprint scanner                            | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 6.67%   |
| Shenzhen Goodix  FingerPrint Device                      | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 6.67%   |
| Shenzhen Goodix FingerPrint                              | 1         | 6.67%   |
| Elan ELAN:Fingerprint                                    | 1         | 6.67%   |
| Elan ELAN:ARM-M4                                         | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Lenovo | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 110       | 78.57%  |
| 1     | 26        | 18.57%  |
| 2     | 4         | 2.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 45.16%  |
| Graphics card            | 8         | 25.81%  |
| Net/wireless             | 4         | 12.9%   |
| Multimedia controller    | 2         | 6.45%   |
| Unassigned class         | 1         | 3.23%   |
| Communication controller | 1         | 3.23%   |
| Camera                   | 1         | 3.23%   |

