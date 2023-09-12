Debian 12 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 12.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_12/Desktop/README.md) and [notebooks](/Dist/Debian_12/Notebook/README.md).

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

Total: 1633

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Z790 UD                     | Desktop     | [3f67617c93](https://linux-hardware.org/?probe=3f67617c93) | Sep 07, 2023 |
| Dell          | 0R96K1 A00                  | Mini pc     | [3498c7ff1c](https://linux-hardware.org/?probe=3498c7ff1c) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | Desktop     | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASRock        | Z97M OC Formula             | Desktop     | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| Lenovo        | 3144                        | Mini pc     | [8dbb3d65e7](https://linux-hardware.org/?probe=8dbb3d65e7) | Sep 06, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [19dc657d04](https://linux-hardware.org/?probe=19dc657d04) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [f20b630cf8](https://linux-hardware.org/?probe=f20b630cf8) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [2b9d42ccc9](https://linux-hardware.org/?probe=2b9d42ccc9) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [4ae2ea34c2](https://linux-hardware.org/?probe=4ae2ea34c2) | Sep 06, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [faac131992](https://linux-hardware.org/?probe=faac131992) | Sep 05, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [1bcf7b95c6](https://linux-hardware.org/?probe=1bcf7b95c6) | Sep 05, 2023 |
| Lenovo        | ThinkPad T490 20N2001YUS    | Notebook    | [75c15ac2e8](https://linux-hardware.org/?probe=75c15ac2e8) | Sep 05, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [8415f054e5](https://linux-hardware.org/?probe=8415f054e5) | Sep 05, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [0874ee1444](https://linux-hardware.org/?probe=0874ee1444) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | Notebook    | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Unknown       | Unknown                     | Soc         | [ac8b7f6a77](https://linux-hardware.org/?probe=ac8b7f6a77) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| ASUSTek       | X541NC                      | Notebook    | [927ba04557](https://linux-hardware.org/?probe=927ba04557) | Sep 05, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| MSI           | Z370-A PRO                  | Desktop     | [b670e69634](https://linux-hardware.org/?probe=b670e69634) | Sep 04, 2023 |
| Dell          | 06FW8M A00                  | Server      | [afde437d5d](https://linux-hardware.org/?probe=afde437d5d) | Sep 04, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | Notebook    | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| HUAWEI        | BC11HGSC0 V100R003          | Server      | [6ce4aa2350](https://linux-hardware.org/?probe=6ce4aa2350) | Sep 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [326596a962](https://linux-hardware.org/?probe=326596a962) | Sep 04, 2023 |
| Dell          | 0CU409                      | Desktop     | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| ASUSTek       | X507UB                      | Notebook    | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| Dell          | Latitude 5414               | Notebook    | [704d861366](https://linux-hardware.org/?probe=704d861366) | Sep 03, 2023 |
| HP            | 1825                        | Desktop     | [38d038d2ad](https://linux-hardware.org/?probe=38d038d2ad) | Sep 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [526a6826ab](https://linux-hardware.org/?probe=526a6826ab) | Sep 03, 2023 |
| Google        | Droid                       | Notebook    | [da26431a82](https://linux-hardware.org/?probe=da26431a82) | Sep 03, 2023 |
| Google        | Droid                       | Notebook    | [278861e9e8](https://linux-hardware.org/?probe=278861e9e8) | Sep 03, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [435cb2d610](https://linux-hardware.org/?probe=435cb2d610) | Sep 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [7ba8b58ea7](https://linux-hardware.org/?probe=7ba8b58ea7) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [213b7c59de](https://linux-hardware.org/?probe=213b7c59de) | Sep 02, 2023 |
| Dell          | 02C2CP A01                  | Server      | [8928318f7a](https://linux-hardware.org/?probe=8928318f7a) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [3ea725d275](https://linux-hardware.org/?probe=3ea725d275) | Sep 02, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [0f1a250c7f](https://linux-hardware.org/?probe=0f1a250c7f) | Sep 02, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [8194030163](https://linux-hardware.org/?probe=8194030163) | Sep 02, 2023 |
| Dell          | Latitude 5430               | Notebook    | [7a9eb9995d](https://linux-hardware.org/?probe=7a9eb9995d) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | Desktop     | [0075af1992](https://linux-hardware.org/?probe=0075af1992) | Sep 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [062f19958d](https://linux-hardware.org/?probe=062f19958d) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [af78cafb1a](https://linux-hardware.org/?probe=af78cafb1a) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [25b3fed672](https://linux-hardware.org/?probe=25b3fed672) | Aug 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f98a2afc33](https://linux-hardware.org/?probe=f98a2afc33) | Aug 31, 2023 |
| Dell          | 0GM819                      | Desktop     | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| Dell          | 0GM819                      | Desktop     | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Google        | Enguarde                    | Notebook    | [d67a18c110](https://linux-hardware.org/?probe=d67a18c110) | Aug 30, 2023 |
| HP            | 8158 A01                    | Mini pc     | [9be38fb21f](https://linux-hardware.org/?probe=9be38fb21f) | Aug 30, 2023 |
| GPU Compan... | GWTN156-9                   | Notebook    | [4c8ea16ab2](https://linux-hardware.org/?probe=4c8ea16ab2) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | Desktop     | [1cea30e36a](https://linux-hardware.org/?probe=1cea30e36a) | Aug 30, 2023 |
| ASUSTek       | PRIME Z790-P D4             | Desktop     | [20b35a5d4f](https://linux-hardware.org/?probe=20b35a5d4f) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [52582bbad0](https://linux-hardware.org/?probe=52582bbad0) | Aug 30, 2023 |
| Google        | Enguarde                    | Notebook    | [08ff2764b2](https://linux-hardware.org/?probe=08ff2764b2) | Aug 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [3718299cea](https://linux-hardware.org/?probe=3718299cea) | Aug 29, 2023 |
| Google        | Enguarde                    | Notebook    | [e2e5a3dadc](https://linux-hardware.org/?probe=e2e5a3dadc) | Aug 29, 2023 |
| Google        | Enguarde                    | Notebook    | [e7a59ac286](https://linux-hardware.org/?probe=e7a59ac286) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [41ce572b6d](https://linux-hardware.org/?probe=41ce572b6d) | Aug 29, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [a41a08d4ae](https://linux-hardware.org/?probe=a41a08d4ae) | Aug 29, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [62ff88eaf7](https://linux-hardware.org/?probe=62ff88eaf7) | Aug 29, 2023 |
| Lenovo        | 102F SDK0Q40081 WIN 3305... | Desktop     | [b6478eb429](https://linux-hardware.org/?probe=b6478eb429) | Aug 29, 2023 |
| HP            | 82A2                        | Desktop     | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [816347743d](https://linux-hardware.org/?probe=816347743d) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2a473fdb4a](https://linux-hardware.org/?probe=2a473fdb4a) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [95128ee415](https://linux-hardware.org/?probe=95128ee415) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b54f472d37](https://linux-hardware.org/?probe=b54f472d37) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9d10db6fe6](https://linux-hardware.org/?probe=9d10db6fe6) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [03402979d2](https://linux-hardware.org/?probe=03402979d2) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2b71412aa1](https://linux-hardware.org/?probe=2b71412aa1) | Aug 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d816edb954](https://linux-hardware.org/?probe=d816edb954) | Aug 28, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [f52ee2433e](https://linux-hardware.org/?probe=f52ee2433e) | Aug 28, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [cea73826dc](https://linux-hardware.org/?probe=cea73826dc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [513140b0b6](https://linux-hardware.org/?probe=513140b0b6) | Aug 28, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [eef69bf730](https://linux-hardware.org/?probe=eef69bf730) | Aug 28, 2023 |
| langchao      | IPM41-D3                    | Desktop     | [a6b482f110](https://linux-hardware.org/?probe=a6b482f110) | Aug 27, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [b21ba1741e](https://linux-hardware.org/?probe=b21ba1741e) | Aug 27, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [e25e18e9b1](https://linux-hardware.org/?probe=e25e18e9b1) | Aug 27, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [5ef3048a11](https://linux-hardware.org/?probe=5ef3048a11) | Aug 26, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [5de726089b](https://linux-hardware.org/?probe=5de726089b) | Aug 26, 2023 |
| Unknown       | MediaTek kodama sku288      | Soc         | [7c4afe8e55](https://linux-hardware.org/?probe=7c4afe8e55) | Aug 26, 2023 |
| Alienware     | m16 R1                      | Notebook    | [75f20a1519](https://linux-hardware.org/?probe=75f20a1519) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| Unknown       | MediaTek kodama sku288      | Soc         | [1b7e6141b6](https://linux-hardware.org/?probe=1b7e6141b6) | Aug 26, 2023 |
| Alienware     | m16 R1                      | Notebook    | [89cffc75ea](https://linux-hardware.org/?probe=89cffc75ea) | Aug 26, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2e662cc73a](https://linux-hardware.org/?probe=2e662cc73a) | Aug 25, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1ec5f419d8](https://linux-hardware.org/?probe=1ec5f419d8) | Aug 25, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [4ca70b63ef](https://linux-hardware.org/?probe=4ca70b63ef) | Aug 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [3067310cf8](https://linux-hardware.org/?probe=3067310cf8) | Aug 25, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0cc7a0f138](https://linux-hardware.org/?probe=0cc7a0f138) | Aug 25, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [3ac1398c61](https://linux-hardware.org/?probe=3ac1398c61) | Aug 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e6d5fa7bc](https://linux-hardware.org/?probe=7e6d5fa7bc) | Aug 25, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [241fead3e6](https://linux-hardware.org/?probe=241fead3e6) | Aug 25, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [815a77392c](https://linux-hardware.org/?probe=815a77392c) | Aug 25, 2023 |
| HP            | 18E4                        | Desktop     | [e209d700ef](https://linux-hardware.org/?probe=e209d700ef) | Aug 25, 2023 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [b53212efce](https://linux-hardware.org/?probe=b53212efce) | Aug 24, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [172876d77a](https://linux-hardware.org/?probe=172876d77a) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| Lenovo        | ThinkServer RD450 70DC00... | Server      | [71859969f5](https://linux-hardware.org/?probe=71859969f5) | Aug 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [0e86c5864d](https://linux-hardware.org/?probe=0e86c5864d) | Aug 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d648900305](https://linux-hardware.org/?probe=d648900305) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [bb1402894c](https://linux-hardware.org/?probe=bb1402894c) | Aug 24, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9c25696a2d](https://linux-hardware.org/?probe=9c25696a2d) | Aug 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0ec42f4555](https://linux-hardware.org/?probe=0ec42f4555) | Aug 24, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [eeff109a12](https://linux-hardware.org/?probe=eeff109a12) | Aug 24, 2023 |
| HC Technol... | HCAR357-NR                  | Desktop     | [3cd017db11](https://linux-hardware.org/?probe=3cd017db11) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Lenovo        | ThinkServer RD450 70DC00... | Server      | [cfeb45f5a1](https://linux-hardware.org/?probe=cfeb45f5a1) | Aug 24, 2023 |
| HP            | Laptop 17-by4xxx            | Notebook    | [9fd582b91e](https://linux-hardware.org/?probe=9fd582b91e) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [a3ec958f0c](https://linux-hardware.org/?probe=a3ec958f0c) | Aug 23, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [fd352acae8](https://linux-hardware.org/?probe=fd352acae8) | Aug 23, 2023 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [79db65495a](https://linux-hardware.org/?probe=79db65495a) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | Notebook    | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| HP            | 8835                        | Desktop     | [6d48f6a632](https://linux-hardware.org/?probe=6d48f6a632) | Aug 23, 2023 |
| HP            | 8835                        | Desktop     | [01d495ff7c](https://linux-hardware.org/?probe=01d495ff7c) | Aug 23, 2023 |
| MSI           | Stealth 17Studio A13VF      | Notebook    | [ca952946e9](https://linux-hardware.org/?probe=ca952946e9) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | Notebook    | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [78bfc9060d](https://linux-hardware.org/?probe=78bfc9060d) | Aug 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [94440c6201](https://linux-hardware.org/?probe=94440c6201) | Aug 22, 2023 |
| Positivo      | Mobile                      | Notebook    | [e39dbd02a9](https://linux-hardware.org/?probe=e39dbd02a9) | Aug 22, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9df41d9b29](https://linux-hardware.org/?probe=9df41d9b29) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [8b219ffa3b](https://linux-hardware.org/?probe=8b219ffa3b) | Aug 22, 2023 |
| Supermicro    | H12SSL-i                    | Desktop     | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [b460d0aa2d](https://linux-hardware.org/?probe=b460d0aa2d) | Aug 22, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [5b3a30e3bc](https://linux-hardware.org/?probe=5b3a30e3bc) | Aug 22, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [ae599c9d4b](https://linux-hardware.org/?probe=ae599c9d4b) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | Notebook    | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Laptop 15z-ef3xxx           | Notebook    | [cf603a20c0](https://linux-hardware.org/?probe=cf603a20c0) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | Notebook    | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | Notebook    | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f144b0be1c](https://linux-hardware.org/?probe=f144b0be1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6a7f21ab63](https://linux-hardware.org/?probe=6a7f21ab63) | Aug 21, 2023 |
| Inspur        | H110H4-EM                   | Desktop     | [75ce94f0f9](https://linux-hardware.org/?probe=75ce94f0f9) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [31be3dd9f9](https://linux-hardware.org/?probe=31be3dd9f9) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [003f15dcd3](https://linux-hardware.org/?probe=003f15dcd3) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [c3207e25fd](https://linux-hardware.org/?probe=c3207e25fd) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dbf7a1d1a0](https://linux-hardware.org/?probe=dbf7a1d1a0) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f6d0755d11](https://linux-hardware.org/?probe=f6d0755d11) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9159447894](https://linux-hardware.org/?probe=9159447894) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [470aee52f3](https://linux-hardware.org/?probe=470aee52f3) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [69bd11ee78](https://linux-hardware.org/?probe=69bd11ee78) | Aug 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c9ea975568](https://linux-hardware.org/?probe=c9ea975568) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [4d4fcc02f3](https://linux-hardware.org/?probe=4d4fcc02f3) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | Notebook    | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [85ba56b138](https://linux-hardware.org/?probe=85ba56b138) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [692bd3fa37](https://linux-hardware.org/?probe=692bd3fa37) | Aug 20, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [6313b3f69e](https://linux-hardware.org/?probe=6313b3f69e) | Aug 20, 2023 |
| Dell          | Latitude E5550              | Notebook    | [0f3afef2ac](https://linux-hardware.org/?probe=0f3afef2ac) | Aug 20, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [109c0dbb17](https://linux-hardware.org/?probe=109c0dbb17) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | Notebook    | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [501ee4caf7](https://linux-hardware.org/?probe=501ee4caf7) | Aug 20, 2023 |
| MSI           | B450M BAZOOKA               | Desktop     | [569655b0f2](https://linux-hardware.org/?probe=569655b0f2) | Aug 20, 2023 |
| ASRockRack    | EP2C612D16C-4L              | Desktop     | [61802adf5b](https://linux-hardware.org/?probe=61802adf5b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [8b6ec2d9e2](https://linux-hardware.org/?probe=8b6ec2d9e2) | Aug 19, 2023 |
| ASRockRack    | EP2C612D16C-4L              | Desktop     | [52d818cdbd](https://linux-hardware.org/?probe=52d818cdbd) | Aug 19, 2023 |
| MSI           | KA790GX-M                   | Desktop     | [050157c33b](https://linux-hardware.org/?probe=050157c33b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [cf83ce90b0](https://linux-hardware.org/?probe=cf83ce90b0) | Aug 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ab5bc08964](https://linux-hardware.org/?probe=ab5bc08964) | Aug 19, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [9580f6451c](https://linux-hardware.org/?probe=9580f6451c) | Aug 19, 2023 |
| HP            | 8266                        | Desktop     | [22a06599a1](https://linux-hardware.org/?probe=22a06599a1) | Aug 19, 2023 |
| Dell          | 0PU052                      | Desktop     | [2b5816a194](https://linux-hardware.org/?probe=2b5816a194) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [9c749716e8](https://linux-hardware.org/?probe=9c749716e8) | Aug 18, 2023 |
| Acer          | Extensa 5235                | Notebook    | [1dc9843f33](https://linux-hardware.org/?probe=1dc9843f33) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [a6a9afac2a](https://linux-hardware.org/?probe=a6a9afac2a) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [762697d775](https://linux-hardware.org/?probe=762697d775) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [5f5f5280d8](https://linux-hardware.org/?probe=5f5f5280d8) | Aug 18, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1888a07128](https://linux-hardware.org/?probe=1888a07128) | Aug 18, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a732f9384c](https://linux-hardware.org/?probe=a732f9384c) | Aug 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [95c536cff4](https://linux-hardware.org/?probe=95c536cff4) | Aug 18, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [097825338b](https://linux-hardware.org/?probe=097825338b) | Aug 18, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7911ff1df6](https://linux-hardware.org/?probe=7911ff1df6) | Aug 18, 2023 |
| ASUSTek       | M3N                         | Notebook    | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| Lenovo        | ThinkPad T430s 2355C33      | Notebook    | [4c589a0320](https://linux-hardware.org/?probe=4c589a0320) | Aug 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e66c463188](https://linux-hardware.org/?probe=e66c463188) | Aug 18, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [c1fd29e307](https://linux-hardware.org/?probe=c1fd29e307) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| HP            | Laptop 15-dy0xxx            | Notebook    | [f938725821](https://linux-hardware.org/?probe=f938725821) | Aug 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [748298f0c8](https://linux-hardware.org/?probe=748298f0c8) | Aug 18, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5c79b899f3](https://linux-hardware.org/?probe=5c79b899f3) | Aug 17, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [24a295f95b](https://linux-hardware.org/?probe=24a295f95b) | Aug 17, 2023 |
| Intel         | X99H                        | Desktop     | [ee1fff7602](https://linux-hardware.org/?probe=ee1fff7602) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d78bb8f579](https://linux-hardware.org/?probe=d78bb8f579) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b54e97094d](https://linux-hardware.org/?probe=b54e97094d) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e12c89f151](https://linux-hardware.org/?probe=e12c89f151) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e299c08bce](https://linux-hardware.org/?probe=e299c08bce) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e2de45e4e9](https://linux-hardware.org/?probe=e2de45e4e9) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [bc68909e3a](https://linux-hardware.org/?probe=bc68909e3a) | Aug 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [14cab7625e](https://linux-hardware.org/?probe=14cab7625e) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | Notebook    | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [8c850ed196](https://linux-hardware.org/?probe=8c850ed196) | Aug 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4337d3d1e2](https://linux-hardware.org/?probe=4337d3d1e2) | Aug 17, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [1742c682fc](https://linux-hardware.org/?probe=1742c682fc) | Aug 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d727b73287](https://linux-hardware.org/?probe=d727b73287) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6db1970bd6](https://linux-hardware.org/?probe=6db1970bd6) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5d6f8fade6](https://linux-hardware.org/?probe=5d6f8fade6) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ee260f72ef](https://linux-hardware.org/?probe=ee260f72ef) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [280336fd4f](https://linux-hardware.org/?probe=280336fd4f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f4e527bf3c](https://linux-hardware.org/?probe=f4e527bf3c) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [e36ddd7ea0](https://linux-hardware.org/?probe=e36ddd7ea0) | Aug 16, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [2d38a6554a](https://linux-hardware.org/?probe=2d38a6554a) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2f24332f97](https://linux-hardware.org/?probe=2f24332f97) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8acff47e76](https://linux-hardware.org/?probe=8acff47e76) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b237d71268](https://linux-hardware.org/?probe=b237d71268) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [5b96fd204a](https://linux-hardware.org/?probe=5b96fd204a) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [57e50d645f](https://linux-hardware.org/?probe=57e50d645f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7574c3c944](https://linux-hardware.org/?probe=7574c3c944) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b41d66568b](https://linux-hardware.org/?probe=b41d66568b) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dda2263ded](https://linux-hardware.org/?probe=dda2263ded) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [97311bdbdc](https://linux-hardware.org/?probe=97311bdbdc) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1cc8cf3629](https://linux-hardware.org/?probe=1cc8cf3629) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [10afc68b3b](https://linux-hardware.org/?probe=10afc68b3b) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3b14ad433f](https://linux-hardware.org/?probe=3b14ad433f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ed03ef6d95](https://linux-hardware.org/?probe=ed03ef6d95) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6b1d961798](https://linux-hardware.org/?probe=6b1d961798) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b18cc3f558](https://linux-hardware.org/?probe=b18cc3f558) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [ea12c6311a](https://linux-hardware.org/?probe=ea12c6311a) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fe7f0f85d6](https://linux-hardware.org/?probe=fe7f0f85d6) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4b65151537](https://linux-hardware.org/?probe=4b65151537) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8812148df1](https://linux-hardware.org/?probe=8812148df1) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [86233e56c3](https://linux-hardware.org/?probe=86233e56c3) | Aug 16, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9da4d1f499](https://linux-hardware.org/?probe=9da4d1f499) | Aug 16, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [2db998a2ca](https://linux-hardware.org/?probe=2db998a2ca) | Aug 16, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [59b0f15b1d](https://linux-hardware.org/?probe=59b0f15b1d) | Aug 16, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | Notebook    | [69e443b8a8](https://linux-hardware.org/?probe=69e443b8a8) | Aug 16, 2023 |
| Google        | Phaser360                   | Notebook    | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [61eb0b10f6](https://linux-hardware.org/?probe=61eb0b10f6) | Aug 16, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0e1d37c108](https://linux-hardware.org/?probe=0e1d37c108) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a247bcbeb2](https://linux-hardware.org/?probe=a247bcbeb2) | Aug 16, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [38af025960](https://linux-hardware.org/?probe=38af025960) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1892ff601a](https://linux-hardware.org/?probe=1892ff601a) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [51bd33992e](https://linux-hardware.org/?probe=51bd33992e) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [fb27772f10](https://linux-hardware.org/?probe=fb27772f10) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f5d288873e](https://linux-hardware.org/?probe=f5d288873e) | Aug 15, 2023 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [a720060bf6](https://linux-hardware.org/?probe=a720060bf6) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b591f4e424](https://linux-hardware.org/?probe=b591f4e424) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [da662c67ac](https://linux-hardware.org/?probe=da662c67ac) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [38226abcf6](https://linux-hardware.org/?probe=38226abcf6) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1dfbda34b5](https://linux-hardware.org/?probe=1dfbda34b5) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [9ec7c6fd58](https://linux-hardware.org/?probe=9ec7c6fd58) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [327533783c](https://linux-hardware.org/?probe=327533783c) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f8a040871d](https://linux-hardware.org/?probe=f8a040871d) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c771b09d1c](https://linux-hardware.org/?probe=c771b09d1c) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dd87624b5c](https://linux-hardware.org/?probe=dd87624b5c) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [376348ff55](https://linux-hardware.org/?probe=376348ff55) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [d790ad0818](https://linux-hardware.org/?probe=d790ad0818) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [28d434fbf0](https://linux-hardware.org/?probe=28d434fbf0) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [65d7bccabe](https://linux-hardware.org/?probe=65d7bccabe) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b891f51d4a](https://linux-hardware.org/?probe=b891f51d4a) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [efc25af8ef](https://linux-hardware.org/?probe=efc25af8ef) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [dde26ee96a](https://linux-hardware.org/?probe=dde26ee96a) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0cd500df40](https://linux-hardware.org/?probe=0cd500df40) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [f5f3782d6d](https://linux-hardware.org/?probe=f5f3782d6d) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [285e864287](https://linux-hardware.org/?probe=285e864287) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b86696f203](https://linux-hardware.org/?probe=b86696f203) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6f734e32db](https://linux-hardware.org/?probe=6f734e32db) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8fb06d8886](https://linux-hardware.org/?probe=8fb06d8886) | Aug 15, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [268eeb2657](https://linux-hardware.org/?probe=268eeb2657) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [b0106d0388](https://linux-hardware.org/?probe=b0106d0388) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [4b47dc68a7](https://linux-hardware.org/?probe=4b47dc68a7) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a345b2f1a8](https://linux-hardware.org/?probe=a345b2f1a8) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [083c967c61](https://linux-hardware.org/?probe=083c967c61) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [79096a1042](https://linux-hardware.org/?probe=79096a1042) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [703775b071](https://linux-hardware.org/?probe=703775b071) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8a9369f769](https://linux-hardware.org/?probe=8a9369f769) | Aug 15, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6c6ed40614](https://linux-hardware.org/?probe=6c6ed40614) | Aug 15, 2023 |
| Supermicro    | X10DRH-i                    | Server      | [fe5b74afef](https://linux-hardware.org/?probe=fe5b74afef) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ec0576c5aa](https://linux-hardware.org/?probe=ec0576c5aa) | Aug 15, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [ae71874b8a](https://linux-hardware.org/?probe=ae71874b8a) | Aug 15, 2023 |
| Alienware     | m15 R4                      | Notebook    | [40d4ad1e4f](https://linux-hardware.org/?probe=40d4ad1e4f) | Aug 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [72e71d1afc](https://linux-hardware.org/?probe=72e71d1afc) | Aug 14, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [948fd89d33](https://linux-hardware.org/?probe=948fd89d33) | Aug 14, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [829ed67cb4](https://linux-hardware.org/?probe=829ed67cb4) | Aug 14, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3329b2a55b](https://linux-hardware.org/?probe=3329b2a55b) | Aug 14, 2023 |
| MSI           | Z790 GAMING WIFI            | Notebook    | [95e340d91b](https://linux-hardware.org/?probe=95e340d91b) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c5ad691377](https://linux-hardware.org/?probe=c5ad691377) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | Desktop     | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| Beelink       | Gemini X                    | Notebook    | [1610652627](https://linux-hardware.org/?probe=1610652627) | Aug 14, 2023 |
| Google        | Blooglet                    | Notebook    | [b9967e65c2](https://linux-hardware.org/?probe=b9967e65c2) | Aug 14, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | Notebook    | [57af1d89d6](https://linux-hardware.org/?probe=57af1d89d6) | Aug 14, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [493f1773eb](https://linux-hardware.org/?probe=493f1773eb) | Aug 13, 2023 |
| HP            | 829A                        | Mini pc     | [e404e2bd31](https://linux-hardware.org/?probe=e404e2bd31) | Aug 13, 2023 |
| HP            | 829A                        | Mini pc     | [80e284bcb5](https://linux-hardware.org/?probe=80e284bcb5) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| ASRock        | B550M PG Riptide            | Desktop     | [642c45af5d](https://linux-hardware.org/?probe=642c45af5d) | Aug 13, 2023 |
| HP            | Pavilion dv5                | Notebook    | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| HP            | 82A5                        | Mini pc     | [de3ae5a3fd](https://linux-hardware.org/?probe=de3ae5a3fd) | Aug 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [b0524c4203](https://linux-hardware.org/?probe=b0524c4203) | Aug 13, 2023 |
| Dell          | 0K2MN4 A01                  | All in one  | [b70bf5282e](https://linux-hardware.org/?probe=b70bf5282e) | Aug 12, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [108dae1eae](https://linux-hardware.org/?probe=108dae1eae) | Aug 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| CWWK          | CW-J6-6L                    | Desktop     | [8321dcc5ea](https://linux-hardware.org/?probe=8321dcc5ea) | Aug 12, 2023 |
| Dell          | 0FDT3J A01                  | Server      | [fce762afa4](https://linux-hardware.org/?probe=fce762afa4) | Aug 12, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [618857a4ae](https://linux-hardware.org/?probe=618857a4ae) | Aug 12, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [dad31fab00](https://linux-hardware.org/?probe=dad31fab00) | Aug 12, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4f6d84a4dd](https://linux-hardware.org/?probe=4f6d84a4dd) | Aug 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [8d7674c3b3](https://linux-hardware.org/?probe=8d7674c3b3) | Aug 11, 2023 |
| HP            | Pavilion dv5                | Notebook    | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| HP            | Pavilion dv5                | Notebook    | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [a064a2d5fd](https://linux-hardware.org/?probe=a064a2d5fd) | Aug 11, 2023 |
| MSI           | G33M                        | Desktop     | [65de454e8b](https://linux-hardware.org/?probe=65de454e8b) | Aug 11, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [91ecb8253e](https://linux-hardware.org/?probe=91ecb8253e) | Aug 11, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0384e8a950](https://linux-hardware.org/?probe=0384e8a950) | Aug 11, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [9bc62c7eec](https://linux-hardware.org/?probe=9bc62c7eec) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [a0350a164c](https://linux-hardware.org/?probe=a0350a164c) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | Notebook    | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 25372E6       | Notebook    | [69c4723b51](https://linux-hardware.org/?probe=69c4723b51) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | Notebook    | [a728658683](https://linux-hardware.org/?probe=a728658683) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Lenovo        | G460 20041                  | Notebook    | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| Unknown       | AB07H                       | Desktop     | [d0b6bc1fce](https://linux-hardware.org/?probe=d0b6bc1fce) | Aug 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [9fcf84ff7c](https://linux-hardware.org/?probe=9fcf84ff7c) | Aug 09, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [13099babf6](https://linux-hardware.org/?probe=13099babf6) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [72655a5d65](https://linux-hardware.org/?probe=72655a5d65) | Aug 08, 2023 |
| Dell          | Inspiron 7537               | Notebook    | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [965f96493c](https://linux-hardware.org/?probe=965f96493c) | Aug 08, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [c06b23398a](https://linux-hardware.org/?probe=c06b23398a) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [4022d66d9a](https://linux-hardware.org/?probe=4022d66d9a) | Aug 08, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | Notebook    | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | Notebook    | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [543719cf07](https://linux-hardware.org/?probe=543719cf07) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [f895d0afe3](https://linux-hardware.org/?probe=f895d0afe3) | Aug 07, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [f3bac278d5](https://linux-hardware.org/?probe=f3bac278d5) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | Notebook    | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | Notebook    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Supermicro    | X8DTU-LN4+                  | Server      | [4e56bb1720](https://linux-hardware.org/?probe=4e56bb1720) | Aug 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7e185ae211](https://linux-hardware.org/?probe=7e185ae211) | Aug 07, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | Notebook    | [55e9e43f37](https://linux-hardware.org/?probe=55e9e43f37) | Aug 06, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| ASRock        | Q1900M                      | Desktop     | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [d754d51977](https://linux-hardware.org/?probe=d754d51977) | Aug 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| BESSTAR Te... | GB1                         | Mini pc     | [2058978754](https://linux-hardware.org/?probe=2058978754) | Aug 06, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [d039bb9d5c](https://linux-hardware.org/?probe=d039bb9d5c) | Aug 06, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [39140ff7de](https://linux-hardware.org/?probe=39140ff7de) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [8511f4c245](https://linux-hardware.org/?probe=8511f4c245) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5a0ec66589](https://linux-hardware.org/?probe=5a0ec66589) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | Notebook    | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Shuttle       | DS47D                       | Notebook    | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [04a083671d](https://linux-hardware.org/?probe=04a083671d) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [76662ba2c9](https://linux-hardware.org/?probe=76662ba2c9) | Aug 05, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Acer          | Veriton M2632G V:1.0        | Desktop     | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [cd16d74fc1](https://linux-hardware.org/?probe=cd16d74fc1) | Aug 04, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [ac23fbd687](https://linux-hardware.org/?probe=ac23fbd687) | Aug 04, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [12948b89f6](https://linux-hardware.org/?probe=12948b89f6) | Aug 04, 2023 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [c125911c18](https://linux-hardware.org/?probe=c125911c18) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | Desktop     | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| HP            | 8620                        | Mini pc     | [3203f90412](https://linux-hardware.org/?probe=3203f90412) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | XPS 9320                    | Notebook    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [701c63b20d](https://linux-hardware.org/?probe=701c63b20d) | Aug 04, 2023 |
| Dell          | 0WXD1Y A00                  | Server      | [fab223d590](https://linux-hardware.org/?probe=fab223d590) | Aug 04, 2023 |
| Sony          | VGN-FW373D                  | Notebook    | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [51ad22a795](https://linux-hardware.org/?probe=51ad22a795) | Aug 03, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [a3f6a98176](https://linux-hardware.org/?probe=a3f6a98176) | Aug 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Google        | Enguarde                    | Notebook    | [663e44ce58](https://linux-hardware.org/?probe=663e44ce58) | Aug 03, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [de2d8bc0e8](https://linux-hardware.org/?probe=de2d8bc0e8) | Aug 03, 2023 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [341ea8b96e](https://linux-hardware.org/?probe=341ea8b96e) | Aug 03, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [3aa878541c](https://linux-hardware.org/?probe=3aa878541c) | Aug 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cef74aa3cb](https://linux-hardware.org/?probe=cef74aa3cb) | Aug 03, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [6d7ac5bfd2](https://linux-hardware.org/?probe=6d7ac5bfd2) | Aug 03, 2023 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [53976b8021](https://linux-hardware.org/?probe=53976b8021) | Aug 03, 2023 |
| Samsung       | 305U1A                      | Notebook    | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [909896213c](https://linux-hardware.org/?probe=909896213c) | Aug 02, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [fd259f2acd](https://linux-hardware.org/?probe=fd259f2acd) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Vostro 5515                 | Notebook    | [0e031a4729](https://linux-hardware.org/?probe=0e031a4729) | Aug 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [89f3f7544e](https://linux-hardware.org/?probe=89f3f7544e) | Aug 02, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9ce9b8ab52](https://linux-hardware.org/?probe=9ce9b8ab52) | Aug 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2d046d70cc](https://linux-hardware.org/?probe=2d046d70cc) | Aug 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [5f9df619f5](https://linux-hardware.org/?probe=5f9df619f5) | Aug 02, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [d4c5149060](https://linux-hardware.org/?probe=d4c5149060) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [dfb33be517](https://linux-hardware.org/?probe=dfb33be517) | Aug 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1abb46d019](https://linux-hardware.org/?probe=1abb46d019) | Aug 01, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7203f5ba4d](https://linux-hardware.org/?probe=7203f5ba4d) | Aug 01, 2023 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [ed16f197f0](https://linux-hardware.org/?probe=ed16f197f0) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [d3250ef8d7](https://linux-hardware.org/?probe=d3250ef8d7) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3367a6e149](https://linux-hardware.org/?probe=3367a6e149) | Aug 01, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [06279baf34](https://linux-hardware.org/?probe=06279baf34) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| Google        | Hanawl                      | Soc         | [08995c0e52](https://linux-hardware.org/?probe=08995c0e52) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [de727e7124](https://linux-hardware.org/?probe=de727e7124) | Jul 31, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3ea3ff2535](https://linux-hardware.org/?probe=3ea3ff2535) | Jul 31, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [7a8510c7fd](https://linux-hardware.org/?probe=7a8510c7fd) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| Dell          | Latitude E5270              | Notebook    | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [87a4b835cf](https://linux-hardware.org/?probe=87a4b835cf) | Jul 30, 2023 |
| MSI           | B250 PC MATE                | Desktop     | [9163341ff4](https://linux-hardware.org/?probe=9163341ff4) | Jul 30, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0YW0... | Notebook    | [3ff995e8b7](https://linux-hardware.org/?probe=3ff995e8b7) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | Notebook    | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | Notebook    | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [db0911c516](https://linux-hardware.org/?probe=db0911c516) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [7207a12cd1](https://linux-hardware.org/?probe=7207a12cd1) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [f591b4a83a](https://linux-hardware.org/?probe=f591b4a83a) | Jul 28, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [ec65662265](https://linux-hardware.org/?probe=ec65662265) | Jul 28, 2023 |
| Dell          | 05GD68 A00                  | Desktop     | [47759e14b4](https://linux-hardware.org/?probe=47759e14b4) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [4287f8186f](https://linux-hardware.org/?probe=4287f8186f) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | Notebook    | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [3a3d1b8e9e](https://linux-hardware.org/?probe=3a3d1b8e9e) | Jul 28, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [7adc21dcee](https://linux-hardware.org/?probe=7adc21dcee) | Jul 28, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | Desktop     | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2e2b9a12a6](https://linux-hardware.org/?probe=2e2b9a12a6) | Jul 28, 2023 |
| Gigabyte      | P55-UD3L                    | Desktop     | [82a3947c74](https://linux-hardware.org/?probe=82a3947c74) | Jul 28, 2023 |
| AZW           | MINI S 10                   | Desktop     | [3501ec2e9a](https://linux-hardware.org/?probe=3501ec2e9a) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Dell          | Precision 3520              | Notebook    | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d52776a0a8](https://linux-hardware.org/?probe=d52776a0a8) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Dell          | System XPS L702X            | Notebook    | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [83a69f246c](https://linux-hardware.org/?probe=83a69f246c) | Jul 28, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [23183da982](https://linux-hardware.org/?probe=23183da982) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [77d42f4b5c](https://linux-hardware.org/?probe=77d42f4b5c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [e8abbb213e](https://linux-hardware.org/?probe=e8abbb213e) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [bb4812527c](https://linux-hardware.org/?probe=bb4812527c) | Jul 27, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [2b7085bd2b](https://linux-hardware.org/?probe=2b7085bd2b) | Jul 27, 2023 |
| MSI           | Z97A GAMING 7               | Desktop     | [cf2d32f045](https://linux-hardware.org/?probe=cf2d32f045) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Google        | Vortininja                  | Notebook    | [70f9ee30d3](https://linux-hardware.org/?probe=70f9ee30d3) | Jul 27, 2023 |
| Intel         | X99H                        | Desktop     | [1e85498a86](https://linux-hardware.org/?probe=1e85498a86) | Jul 27, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [4d7b874be2](https://linux-hardware.org/?probe=4d7b874be2) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [a375e21964](https://linux-hardware.org/?probe=a375e21964) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [d0e6321772](https://linux-hardware.org/?probe=d0e6321772) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [28ea1c85d1](https://linux-hardware.org/?probe=28ea1c85d1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [3fd18c9a77](https://linux-hardware.org/?probe=3fd18c9a77) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [d974298840](https://linux-hardware.org/?probe=d974298840) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [b06f493001](https://linux-hardware.org/?probe=b06f493001) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [894bb319dc](https://linux-hardware.org/?probe=894bb319dc) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [7ec6d64d2f](https://linux-hardware.org/?probe=7ec6d64d2f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [09662b0f5d](https://linux-hardware.org/?probe=09662b0f5d) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [3c8721254c](https://linux-hardware.org/?probe=3c8721254c) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [7dfa96789f](https://linux-hardware.org/?probe=7dfa96789f) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [c538742db7](https://linux-hardware.org/?probe=c538742db7) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [9da53986f9](https://linux-hardware.org/?probe=9da53986f9) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [c950f7dbc1](https://linux-hardware.org/?probe=c950f7dbc1) | Jul 26, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [dcf4ead958](https://linux-hardware.org/?probe=dcf4ead958) | Jul 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [0552cb3e44](https://linux-hardware.org/?probe=0552cb3e44) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [759b0f997f](https://linux-hardware.org/?probe=759b0f997f) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [a1ef57fb8e](https://linux-hardware.org/?probe=a1ef57fb8e) | Jul 26, 2023 |
| ASRock        | A320M Pro4                  | Desktop     | [9ecdd1e4d3](https://linux-hardware.org/?probe=9ecdd1e4d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f45c4baaa3](https://linux-hardware.org/?probe=f45c4baaa3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7abbda5ed3](https://linux-hardware.org/?probe=7abbda5ed3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [67036356d3](https://linux-hardware.org/?probe=67036356d3) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5a134aede2](https://linux-hardware.org/?probe=5a134aede2) | Jul 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [28c92b6f8d](https://linux-hardware.org/?probe=28c92b6f8d) | Jul 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [0217675942](https://linux-hardware.org/?probe=0217675942) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [808dae186a](https://linux-hardware.org/?probe=808dae186a) | Jul 26, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [68ec8c0bdf](https://linux-hardware.org/?probe=68ec8c0bdf) | Jul 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [b45586c5cf](https://linux-hardware.org/?probe=b45586c5cf) | Jul 26, 2023 |
| Gigabyte      | GA-A55M-S2HP                | Other       | [5b1e00b374](https://linux-hardware.org/?probe=5b1e00b374) | Jul 26, 2023 |
| Dell          | Precision 3520              | Notebook    | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [725aae77c4](https://linux-hardware.org/?probe=725aae77c4) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Google        | Droid                       | Notebook    | [ae803483c2](https://linux-hardware.org/?probe=ae803483c2) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [835ca23b88](https://linux-hardware.org/?probe=835ca23b88) | Jul 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f01ec95642](https://linux-hardware.org/?probe=f01ec95642) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [321bdf6295](https://linux-hardware.org/?probe=321bdf6295) | Jul 25, 2023 |
| Acer          | Aspire 3610                 | Notebook    | [b40dd6ad17](https://linux-hardware.org/?probe=b40dd6ad17) | Jul 25, 2023 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9fbb932f79](https://linux-hardware.org/?probe=9fbb932f79) | Jul 25, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [b75ed54995](https://linux-hardware.org/?probe=b75ed54995) | Jul 25, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [d60f3de4c7](https://linux-hardware.org/?probe=d60f3de4c7) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [24b688cbfd](https://linux-hardware.org/?probe=24b688cbfd) | Jul 25, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c5960175bc](https://linux-hardware.org/?probe=c5960175bc) | Jul 25, 2023 |
| Dell          | Latitude 3420               | Notebook    | [18d920dab2](https://linux-hardware.org/?probe=18d920dab2) | Jul 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [fd441fa52f](https://linux-hardware.org/?probe=fd441fa52f) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [7076b096fd](https://linux-hardware.org/?probe=7076b096fd) | Jul 24, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [ae6caf81d7](https://linux-hardware.org/?probe=ae6caf81d7) | Jul 24, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e1de4fabc7](https://linux-hardware.org/?probe=e1de4fabc7) | Jul 24, 2023 |
| Timi          | A7S                         | Notebook    | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [15c9141aa3](https://linux-hardware.org/?probe=15c9141aa3) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [9f1e03d74d](https://linux-hardware.org/?probe=9f1e03d74d) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [17f482e878](https://linux-hardware.org/?probe=17f482e878) | Jul 23, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [8c41263814](https://linux-hardware.org/?probe=8c41263814) | Jul 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [d957d5efe0](https://linux-hardware.org/?probe=d957d5efe0) | Jul 22, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9d0eeb96a8](https://linux-hardware.org/?probe=9d0eeb96a8) | Jul 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [8dbf2477d3](https://linux-hardware.org/?probe=8dbf2477d3) | Jul 22, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4bd62a58b8](https://linux-hardware.org/?probe=4bd62a58b8) | Jul 22, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [18c7d0154b](https://linux-hardware.org/?probe=18c7d0154b) | Jul 22, 2023 |
| HP            | Presario CQ57               | Notebook    | [2c1bcfe898](https://linux-hardware.org/?probe=2c1bcfe898) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [06c9677557](https://linux-hardware.org/?probe=06c9677557) | Jul 22, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [7d88a01e49](https://linux-hardware.org/?probe=7d88a01e49) | Jul 22, 2023 |
| HP            | 635                         | Notebook    | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [08f1fe3568](https://linux-hardware.org/?probe=08f1fe3568) | Jul 20, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [cc299998bb](https://linux-hardware.org/?probe=cc299998bb) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [43cb18f0ee](https://linux-hardware.org/?probe=43cb18f0ee) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [cb0ad6375e](https://linux-hardware.org/?probe=cb0ad6375e) | Jul 20, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [311144e138](https://linux-hardware.org/?probe=311144e138) | Jul 20, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Notebook      | N650DU                      | Notebook    | [c04f4faa06](https://linux-hardware.org/?probe=c04f4faa06) | Jul 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Acer          | Aspire 7739Z                | Notebook    | [3e75dec5e0](https://linux-hardware.org/?probe=3e75dec5e0) | Jul 19, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [9672a393c9](https://linux-hardware.org/?probe=9672a393c9) | Jul 19, 2023 |
| Dell          | 05XKKK A05                  | Server      | [3e627de1a2](https://linux-hardware.org/?probe=3e627de1a2) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | Notebook    | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cdad3aa931](https://linux-hardware.org/?probe=cdad3aa931) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bddb3e26c1](https://linux-hardware.org/?probe=bddb3e26c1) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [ce80e4d17f](https://linux-hardware.org/?probe=ce80e4d17f) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [69cc1eb6f6](https://linux-hardware.org/?probe=69cc1eb6f6) | Jul 18, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [5facab887b](https://linux-hardware.org/?probe=5facab887b) | Jul 18, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [c68138ca5c](https://linux-hardware.org/?probe=c68138ca5c) | Jul 18, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [c6da4f3b1e](https://linux-hardware.org/?probe=c6da4f3b1e) | Jul 18, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [a6c81d2b9e](https://linux-hardware.org/?probe=a6c81d2b9e) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | Notebook    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9bd188ee9b](https://linux-hardware.org/?probe=9bd188ee9b) | Jul 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9d9ff78d29](https://linux-hardware.org/?probe=9d9ff78d29) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [539fb9855b](https://linux-hardware.org/?probe=539fb9855b) | Jul 18, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [58e48b61c2](https://linux-hardware.org/?probe=58e48b61c2) | Jul 17, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [d75cfffdca](https://linux-hardware.org/?probe=d75cfffdca) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [676f61f0c9](https://linux-hardware.org/?probe=676f61f0c9) | Jul 17, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [fc5b33ac00](https://linux-hardware.org/?probe=fc5b33ac00) | Jul 17, 2023 |
| Unknown       | TU-142                      | Notebook    | [d62ade82c2](https://linux-hardware.org/?probe=d62ade82c2) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [87dd24dabe](https://linux-hardware.org/?probe=87dd24dabe) | Jul 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Acer          | Aspire A515-57T             | Notebook    | [dd4a3bf595](https://linux-hardware.org/?probe=dd4a3bf595) | Jul 17, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [65a6e11166](https://linux-hardware.org/?probe=65a6e11166) | Jul 17, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [df26ae3dab](https://linux-hardware.org/?probe=df26ae3dab) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [29ed3e238d](https://linux-hardware.org/?probe=29ed3e238d) | Jul 16, 2023 |
| Lenovo        | Yoga 14sITL 2021 82G2       | Notebook    | [899c1452e4](https://linux-hardware.org/?probe=899c1452e4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [f10ee5f25d](https://linux-hardware.org/?probe=f10ee5f25d) | Jul 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [cd9bfc68b6](https://linux-hardware.org/?probe=cd9bfc68b6) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | Notebook    | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| Dell          | Latitude D610               | Notebook    | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [151797320d](https://linux-hardware.org/?probe=151797320d) | Jul 16, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e760f4570f](https://linux-hardware.org/?probe=e760f4570f) | Jul 16, 2023 |
| Google        | Guado                       | Desktop     | [4216aa46a6](https://linux-hardware.org/?probe=4216aa46a6) | Jul 16, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | Notebook    | [02af27da78](https://linux-hardware.org/?probe=02af27da78) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Google        | Guado                       | Desktop     | [9a3e217e78](https://linux-hardware.org/?probe=9a3e217e78) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | Notebook    | [b62ed55325](https://linux-hardware.org/?probe=b62ed55325) | Jul 15, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [ce378ce93b](https://linux-hardware.org/?probe=ce378ce93b) | Jul 15, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [b048c3ee50](https://linux-hardware.org/?probe=b048c3ee50) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| Biostar       | FX9830M                     | Desktop     | [db3c95d18d](https://linux-hardware.org/?probe=db3c95d18d) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | Notebook    | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [de6db92e0a](https://linux-hardware.org/?probe=de6db92e0a) | Jul 14, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [236c9f5565](https://linux-hardware.org/?probe=236c9f5565) | Jul 14, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [f3723937e1](https://linux-hardware.org/?probe=f3723937e1) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | Notebook    | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [9404c94281](https://linux-hardware.org/?probe=9404c94281) | Jul 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [a63f044df1](https://linux-hardware.org/?probe=a63f044df1) | Jul 14, 2023 |
| HP            | Pavilion dm1                | Notebook    | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Google        | Blorb                       | Notebook    | [6bbcc9b8f3](https://linux-hardware.org/?probe=6bbcc9b8f3) | Jul 14, 2023 |
| Supermicro    | X9DRT                       | Server      | [b95f28343e](https://linux-hardware.org/?probe=b95f28343e) | Jul 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [b52ebf4fc9](https://linux-hardware.org/?probe=b52ebf4fc9) | Jul 13, 2023 |
| Google        | Reks                        | Notebook    | [680b857c0d](https://linux-hardware.org/?probe=680b857c0d) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [7d2bb16563](https://linux-hardware.org/?probe=7d2bb16563) | Jul 13, 2023 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [b054249d03](https://linux-hardware.org/?probe=b054249d03) | Jul 13, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2551062f30](https://linux-hardware.org/?probe=2551062f30) | Jul 13, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [109d52a9be](https://linux-hardware.org/?probe=109d52a9be) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [34ec75d601](https://linux-hardware.org/?probe=34ec75d601) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [56b110f152](https://linux-hardware.org/?probe=56b110f152) | Jul 13, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ad9fd505fa](https://linux-hardware.org/?probe=ad9fd505fa) | Jul 13, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [1d6544e56b](https://linux-hardware.org/?probe=1d6544e56b) | Jul 12, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [603a591fcb](https://linux-hardware.org/?probe=603a591fcb) | Jul 12, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [66c5696981](https://linux-hardware.org/?probe=66c5696981) | Jul 12, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8b8ef12b03](https://linux-hardware.org/?probe=8b8ef12b03) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | Notebook    | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | Notebook    | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | Notebook    | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [15c5dec8dc](https://linux-hardware.org/?probe=15c5dec8dc) | Jul 12, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [ea706db679](https://linux-hardware.org/?probe=ea706db679) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [e49876314d](https://linux-hardware.org/?probe=e49876314d) | Jul 11, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| Dell          | Latitude 7275               | Notebook    | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| ASRock        | 4Core1600-GLAN              | Desktop     | [3e733151f2](https://linux-hardware.org/?probe=3e733151f2) | Jul 11, 2023 |
| HP            | ProBook 4730s               | Notebook    | [0b6a6c7260](https://linux-hardware.org/?probe=0b6a6c7260) | Jul 11, 2023 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| Foxconn       | G33M03                      | Desktop     | [487435e6e7](https://linux-hardware.org/?probe=487435e6e7) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ad7b13940b](https://linux-hardware.org/?probe=ad7b13940b) | Jul 11, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [e1700a0ab4](https://linux-hardware.org/?probe=e1700a0ab4) | Jul 11, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [cbcf43d3dd](https://linux-hardware.org/?probe=cbcf43d3dd) | Jul 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [84088522ca](https://linux-hardware.org/?probe=84088522ca) | Jul 11, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [a761bfffd2](https://linux-hardware.org/?probe=a761bfffd2) | Jul 11, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [47ea5a35cb](https://linux-hardware.org/?probe=47ea5a35cb) | Jul 11, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0ae95a7985](https://linux-hardware.org/?probe=0ae95a7985) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [ca0b773fe8](https://linux-hardware.org/?probe=ca0b773fe8) | Jul 10, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [de6111a05e](https://linux-hardware.org/?probe=de6111a05e) | Jul 10, 2023 |
| Loongson      | LS3A5000-7A2000-1w-EVB-V... | Desktop     | [97348ef480](https://linux-hardware.org/?probe=97348ef480) | Jul 10, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6593286092](https://linux-hardware.org/?probe=6593286092) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| ASUSTek       | Maximus VI IMPACT           | Desktop     | [ce682089cb](https://linux-hardware.org/?probe=ce682089cb) | Jul 10, 2023 |
| Unknown       | Generic RK322x Tv Box       | Other       | [a5da218315](https://linux-hardware.org/?probe=a5da218315) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [707f0b8eeb](https://linux-hardware.org/?probe=707f0b8eeb) | Jul 10, 2023 |
| HP            | 2B38                        | Desktop     | [94e5178425](https://linux-hardware.org/?probe=94e5178425) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Fujitsu       | LIFEBOOK U727               | Notebook    | [ce095d85c9](https://linux-hardware.org/?probe=ce095d85c9) | Jul 09, 2023 |
| HP            | Pro x2 612 G1 Tablet USA... | Notebook    | [c10c965a51](https://linux-hardware.org/?probe=c10c965a51) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | Notebook    | [566ff1d23e](https://linux-hardware.org/?probe=566ff1d23e) | Jul 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [64e129ec04](https://linux-hardware.org/?probe=64e129ec04) | Jul 09, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [c2e76ab704](https://linux-hardware.org/?probe=c2e76ab704) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [59f06e2baf](https://linux-hardware.org/?probe=59f06e2baf) | Jul 09, 2023 |
| Acer          | Aspire V3-372T              | Notebook    | [f2a9fbdf50](https://linux-hardware.org/?probe=f2a9fbdf50) | Jul 09, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [39fe220963](https://linux-hardware.org/?probe=39fe220963) | Jul 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1e27d93bb4](https://linux-hardware.org/?probe=1e27d93bb4) | Jul 09, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [89e81df1b9](https://linux-hardware.org/?probe=89e81df1b9) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [0eaaaced27](https://linux-hardware.org/?probe=0eaaaced27) | Jul 08, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [a208acb623](https://linux-hardware.org/?probe=a208acb623) | Jul 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [3bf9689ee5](https://linux-hardware.org/?probe=3bf9689ee5) | Jul 08, 2023 |
| Dell          | 0CU409                      | Desktop     | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| Unknown       | Unknown                     | Soc         | [e31f4bb359](https://linux-hardware.org/?probe=e31f4bb359) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [59c2893e1a](https://linux-hardware.org/?probe=59c2893e1a) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| ASRock        | B550 Taichi Razer Editio... | Desktop     | [c5578cae9e](https://linux-hardware.org/?probe=c5578cae9e) | Jul 07, 2023 |
| HP            | 2B4B                        | Desktop     | [9b9e0f8037](https://linux-hardware.org/?probe=9b9e0f8037) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [96d1578908](https://linux-hardware.org/?probe=96d1578908) | Jul 07, 2023 |
| HP            | 2B4B                        | Desktop     | [9198ca9615](https://linux-hardware.org/?probe=9198ca9615) | Jul 07, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [abb4e75faa](https://linux-hardware.org/?probe=abb4e75faa) | Jul 07, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5d03b4b2ad](https://linux-hardware.org/?probe=5d03b4b2ad) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [66d756d3c4](https://linux-hardware.org/?probe=66d756d3c4) | Jul 06, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| Dell          | Latitude 7430               | Notebook    | [743d41d534](https://linux-hardware.org/?probe=743d41d534) | Jul 06, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [71b3710ae4](https://linux-hardware.org/?probe=71b3710ae4) | Jul 06, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [5b085b711b](https://linux-hardware.org/?probe=5b085b711b) | Jul 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [f99a1ccf8f](https://linux-hardware.org/?probe=f99a1ccf8f) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [37f1a0082b](https://linux-hardware.org/?probe=37f1a0082b) | Jul 06, 2023 |
| HP            | 8860 A                      | Desktop     | [5bc7810c4b](https://linux-hardware.org/?probe=5bc7810c4b) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 20HES05500    | Notebook    | [12b31081e2](https://linux-hardware.org/?probe=12b31081e2) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [95d2ae1051](https://linux-hardware.org/?probe=95d2ae1051) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [4f6d2375a3](https://linux-hardware.org/?probe=4f6d2375a3) | Jul 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1d387dfc5](https://linux-hardware.org/?probe=c1d387dfc5) | Jul 06, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [f255433162](https://linux-hardware.org/?probe=f255433162) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [2d38e98c83](https://linux-hardware.org/?probe=2d38e98c83) | Jul 05, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [41366bcd54](https://linux-hardware.org/?probe=41366bcd54) | Jul 05, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [7e3ad6f5a7](https://linux-hardware.org/?probe=7e3ad6f5a7) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [4e61ff196e](https://linux-hardware.org/?probe=4e61ff196e) | Jul 05, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [696e4c24d1](https://linux-hardware.org/?probe=696e4c24d1) | Jul 05, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [7a15493631](https://linux-hardware.org/?probe=7a15493631) | Jul 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [3707ca3e1d](https://linux-hardware.org/?probe=3707ca3e1d) | Jul 05, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [fc1c7254b3](https://linux-hardware.org/?probe=fc1c7254b3) | Jul 04, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [8c224974f3](https://linux-hardware.org/?probe=8c224974f3) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [79c5344e62](https://linux-hardware.org/?probe=79c5344e62) | Jul 04, 2023 |
| Google        | Lick                        | Notebook    | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| Acer          | Aspire C24-1651             | All in one  | [d19d72db11](https://linux-hardware.org/?probe=d19d72db11) | Jul 04, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [ebd5d13804](https://linux-hardware.org/?probe=ebd5d13804) | Jul 04, 2023 |
| Acer          | Aspire 6930                 | Notebook    | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| HP            | Pavilion dv6                | Notebook    | [517e6b81c1](https://linux-hardware.org/?probe=517e6b81c1) | Jul 04, 2023 |
| iEi           | SAT3 V1.03                  | Desktop     | [fa5767b5f5](https://linux-hardware.org/?probe=fa5767b5f5) | Jul 03, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9330835392](https://linux-hardware.org/?probe=9330835392) | Jul 03, 2023 |
| HP            | 0AECh D                     | Desktop     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [73146ccba2](https://linux-hardware.org/?probe=73146ccba2) | Jul 03, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cac603cdf3](https://linux-hardware.org/?probe=cac603cdf3) | Jul 03, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [5f6fc07aaa](https://linux-hardware.org/?probe=5f6fc07aaa) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Unknown       | AB07H                       | Desktop     | [868ad2b334](https://linux-hardware.org/?probe=868ad2b334) | Jul 03, 2023 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [18230f7c64](https://linux-hardware.org/?probe=18230f7c64) | Jul 03, 2023 |
| Acer          | Aspire C24-1651             | All in one  | [b93a479e9b](https://linux-hardware.org/?probe=b93a479e9b) | Jul 02, 2023 |
| Intel         | NUC13ANBi7 M89645-202       | Mini pc     | [3482361f0c](https://linux-hardware.org/?probe=3482361f0c) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4055aa6f2b](https://linux-hardware.org/?probe=4055aa6f2b) | Jul 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [4708f2b480](https://linux-hardware.org/?probe=4708f2b480) | Jul 02, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [61bc4ee589](https://linux-hardware.org/?probe=61bc4ee589) | Jul 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [54987b03a1](https://linux-hardware.org/?probe=54987b03a1) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [12a82e799d](https://linux-hardware.org/?probe=12a82e799d) | Jul 01, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [eb4b65c767](https://linux-hardware.org/?probe=eb4b65c767) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [91e094e5c8](https://linux-hardware.org/?probe=91e094e5c8) | Jul 01, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| Supermicro    | X8ST3                       | Desktop     | [f1eddf9437](https://linux-hardware.org/?probe=f1eddf9437) | Jul 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [c55a78c98a](https://linux-hardware.org/?probe=c55a78c98a) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [55bfc9f544](https://linux-hardware.org/?probe=55bfc9f544) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Dell          | Latitude 3500               | Notebook    | [8e82f9abda](https://linux-hardware.org/?probe=8e82f9abda) | Jul 01, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [c111f0f4be](https://linux-hardware.org/?probe=c111f0f4be) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Dell          | Inspiron 7373               | Convertible | [e7edaad244](https://linux-hardware.org/?probe=e7edaad244) | Jun 30, 2023 |
| ASUSTek       | K52F                        | Notebook    | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | Notebook    | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| Dell          | Latitude 3500               | Notebook    | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [04d1ab025a](https://linux-hardware.org/?probe=04d1ab025a) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| OEM           | Unknown                     | Desktop     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [b4be8eaa80](https://linux-hardware.org/?probe=b4be8eaa80) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | Desktop     | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Supermicro    | X9DRT                       | Server      | [807e745cb1](https://linux-hardware.org/?probe=807e745cb1) | Jun 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| Dell          | 0PU052                      | Desktop     | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | Desktop     | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | Notebook    | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | Notebook    | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Leader        | SC8-PRO                     | Stick pc    | [ad54f075f6](https://linux-hardware.org/?probe=ad54f075f6) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | Notebook    | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | Desktop     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Biostar       | X370GTN                     | Desktop     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| Intel         | H55                         | Desktop     | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Dell          | Latitude E6430              | Notebook    | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| HP            | 872E                        | Mini pc     | [d59093e79e](https://linux-hardware.org/?probe=d59093e79e) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| Irbis         | NB131                       | Convertible | [9898b376fe](https://linux-hardware.org/?probe=9898b376fe) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | Notebook    | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [23723983da](https://linux-hardware.org/?probe=23723983da) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | Notebook    | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| ASUSTek       | X45U                        | Notebook    | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Acer          | Aspire X1700                | Desktop     | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | Desktop     | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | Desktop     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [197d2f4c7c](https://linux-hardware.org/?probe=197d2f4c7c) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [0aa3b8d433](https://linux-hardware.org/?probe=0aa3b8d433) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | Notebook    | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0RW203                      | Desktop     | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [9b75bc9f7e](https://linux-hardware.org/?probe=9b75bc9f7e) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| Intel         | H81                         | Desktop     | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| Xunlong       | Orange Pi Lite              | Soc         | [f7e41df8d6](https://linux-hardware.org/?probe=f7e41df8d6) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| HP            | 2B38                        | Desktop     | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | Notebook    | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Unknown       | Unknown                     | Soc         | [92f385e306](https://linux-hardware.org/?probe=92f385e306) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | Desktop     | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | Notebook    | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Dell          | 0XM089 A00                  | Server      | [c52b7c8444](https://linux-hardware.org/?probe=c52b7c8444) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | Notebook    | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| HP            | 2820h                       | Desktop     | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | Desktop     | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.1.0-9-amd64          | 286       | 21.82%  |
| 6.1.0-10-amd64         | 246       | 18.76%  |
| 6.1.0-11-amd64         | 224       | 17.09%  |
| 6.1.0-4-amd64          | 177       | 13.5%   |
| 6.1.0-7-amd64          | 91        | 6.94%   |
| 6.1.0-6-amd64          | 45        | 3.43%   |
| 6.1.0-3-amd64          | 36        | 2.75%   |
| 6.1.0-5-amd64          | 32        | 2.44%   |
| 6.1.0-8-amd64          | 16        | 1.22%   |
| 6.2.16-3-pve           | 12        | 0.92%   |
| 6.2.16-6-pve           | 9         | 0.69%   |
| 6.1.0-10-686-pae       | 7         | 0.53%   |
| 6.0.0-6-amd64          | 6         | 0.46%   |
| 6.0.0-2-amd64          | 5         | 0.38%   |
| 6.2.16-4-pve           | 4         | 0.31%   |
| 6.4.0-0.deb12.2-amd64  | 3         | 0.23%   |
| 6.2.16-8-pve           | 3         | 0.23%   |
| 6.2.16-10-pve          | 3         | 0.23%   |
| 6.1.0-7-rt-amd64       | 3         | 0.23%   |
| 5.15.0-starfive        | 3         | 0.23%   |
| 6.4.3-1-liquorix-amd64 | 2         | 0.15%   |
| 6.4.0-1-amd64          | 2         | 0.15%   |
| 6.3.0-1-amd64          | 2         | 0.15%   |
| 6.2.16-2-pve           | 2         | 0.15%   |
| 6.1.0-9-rt-amd64       | 2         | 0.15%   |
| 6.1.0-9-686-pae        | 2         | 0.15%   |
| 6.1.0-2-amd64          | 2         | 0.15%   |
| 6.0.0-4-amd64          | 2         | 0.15%   |
| 6.0.0-0.deb11.6-amd64  | 2         | 0.15%   |
| 5.15.94-starfive2      | 2         | 0.15%   |
| 5.10.0-23-amd64        | 2         | 0.15%   |
| 5.10.0-21-amd64        | 2         | 0.15%   |
| 6.5.0-rc5              | 1         | 0.08%   |
| 6.5.0-060500-generic   | 1         | 0.08%   |
| 6.4.9-1-liquorix-amd64 | 1         | 0.08%   |
| 6.4.7-1-liquorix-amd64 | 1         | 0.08%   |
| 6.4.6-1-liquorix-amd64 | 1         | 0.08%   |
| 6.4.2-surface          | 1         | 0.08%   |
| 6.4.2-rk322x           | 1         | 0.08%   |
| 6.4.2-edwardron-amd64  | 1         | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.0    | 1142      | 89.64%  |
| 6.2.16   | 35        | 2.75%   |
| 6.0.0    | 16        | 1.26%   |
| 5.10.0   | 10        | 0.78%   |
| 6.4.0    | 8         | 0.63%   |
| 6.3.0    | 5         | 0.39%   |
| 6.1.38   | 4         | 0.31%   |
| 6.1.11   | 4         | 0.31%   |
| 5.15.0   | 4         | 0.31%   |
| 6.4.2    | 3         | 0.24%   |
| 6.5.0    | 2         | 0.16%   |
| 6.4.3    | 2         | 0.16%   |
| 6.3.9    | 2         | 0.16%   |
| 6.2.8    | 2         | 0.16%   |
| 6.2.11   | 2         | 0.16%   |
| 6.1      | 2         | 0.16%   |
| 5.15.94  | 2         | 0.16%   |
| 5.10.113 | 2         | 0.16%   |
| 6.4.9    | 1         | 0.08%   |
| 6.4.7    | 1         | 0.08%   |
| 6.4.6    | 1         | 0.08%   |
| 6.4.11   | 1         | 0.08%   |
| 6.4.10   | 1         | 0.08%   |
| 6.3.8    | 1         | 0.08%   |
| 6.3.7    | 1         | 0.08%   |
| 6.3.5    | 1         | 0.08%   |
| 6.3.3    | 1         | 0.08%   |
| 6.3.10   | 1         | 0.08%   |
| 6.1.9    | 1         | 0.08%   |
| 6.1.27   | 1         | 0.08%   |
| 6.1.26   | 1         | 0.08%   |
| 6.1.25   | 1         | 0.08%   |
| 6.1.13   | 1         | 0.08%   |
| 6.1.12   | 1         | 0.08%   |
| 5.19.0   | 1         | 0.08%   |
| 5.16.0   | 1         | 0.08%   |
| 5.15.95  | 1         | 0.08%   |
| 5.15.90  | 1         | 0.08%   |
| 5.15.108 | 1         | 0.08%   |
| 5.10.142 | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 1156      | 90.81%  |
| 6.2     | 39        | 3.06%   |
| 6.4     | 18        | 1.41%   |
| 6.0     | 16        | 1.26%   |
| 5.10    | 15        | 1.18%   |
| 6.3     | 12        | 0.94%   |
| 5.15    | 8         | 0.63%   |
| 6.5     | 2         | 0.16%   |
| 6       | 2         | 0.16%   |
| 5.19    | 1         | 0.08%   |
| 5.16    | 1         | 0.08%   |
| 4.19    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.1     | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 1231      | 97.16%  |
| i686        | 13        | 1.03%   |
| aarch64     | 10        | 0.79%   |
| riscv64     | 6         | 0.47%   |
| armv7l      | 5         | 0.39%   |
| ppc64       | 1         | 0.08%   |
| loongarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 402       | 31.55%  |
| GNOME            | 369       | 28.96%  |
| KDE5             | 219       | 17.19%  |
| XFCE             | 103       | 8.08%   |
| X-Cinnamon       | 60        | 4.71%   |
| MATE             | 44        | 3.45%   |
| LXQt             | 17        | 1.33%   |
| LXDE             | 14        | 1.1%    |
| i3               | 12        | 0.94%   |
| GNOME Flashback  | 6         | 0.47%   |
| Cinnamon         | 6         | 0.47%   |
| GNOME Classic    | 3         | 0.24%   |
| GNUstep          | 2         | 0.16%   |
| Enlightenment    | 2         | 0.16%   |
| dwm              | 2         | 0.16%   |
| Budgie           | 2         | 0.16%   |
| xmonad           | 1         | 0.08%   |
| Trinity          | 1         | 0.08%   |
| sway             | 1         | 0.08%   |
| Phosh:GNOME      | 1         | 0.08%   |
| Pantheon         | 1         | 0.08%   |
| openbox          | 1         | 0.08%   |
| lightdm-xsession | 1         | 0.08%   |
| KDE              | 1         | 0.08%   |
| Cutefish         | 1         | 0.08%   |
| bspwm            | 1         | 0.08%   |
| awesome          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 474       | 37.06%  |
| Wayland | 382       | 29.87%  |
| Unknown | 340       | 26.58%  |
| Tty     | 83        | 6.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 628       | 49.25%  |
| GDM3    | 274       | 21.49%  |
| LightDM | 195       | 15.29%  |
| SDDM    | 164       | 12.86%  |
| Ly      | 3         | 0.24%   |
| LXDM    | 3         | 0.24%   |
| XDM     | 2         | 0.16%   |
| SLiM    | 2         | 0.16%   |
| GREETD  | 2         | 0.16%   |
| GDM     | 2         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 408       | 32.13%  |
| ru_RU   | 225       | 17.72%  |
| Unknown | 149       | 11.73%  |
| de_DE   | 86        | 6.77%   |
| en_GB   | 69        | 5.43%   |
| fr_FR   | 50        | 3.94%   |
| pt_BR   | 33        | 2.6%    |
| es_ES   | 23        | 1.81%   |
| en_CA   | 22        | 1.73%   |
| sv_SE   | 16        | 1.26%   |
| en_IN   | 16        | 1.26%   |
| zh_CN   | 14        | 1.1%    |
| it_IT   | 13        | 1.02%   |
| pl_PL   | 12        | 0.94%   |
| en_AU   | 12        | 0.94%   |
| C       | 12        | 0.94%   |
| es_CL   | 6         | 0.47%   |
| es_AR   | 6         | 0.47%   |
| es_VE   | 5         | 0.39%   |
| en_ZA   | 5         | 0.39%   |
| en_IE   | 5         | 0.39%   |
| ca_ES   | 5         | 0.39%   |
| nl_NL   | 4         | 0.31%   |
| hu_HU   | 4         | 0.31%   |
| fr_BE   | 4         | 0.31%   |
| en_NZ   | 4         | 0.31%   |
| de_CH   | 4         | 0.31%   |
| de_AT   | 4         | 0.31%   |
| fi_FI   | 3         | 0.24%   |
| es_MX   | 3         | 0.24%   |
| en_IL   | 3         | 0.24%   |
| en_DK   | 3         | 0.24%   |
| cs_CZ   | 3         | 0.24%   |
| be_BY   | 3         | 0.24%   |
| zh_TW   | 2         | 0.16%   |
| tr_TR   | 2         | 0.16%   |
| pt_PT   | 2         | 0.16%   |
| ko_KR   | 2         | 0.16%   |
| ja_JP   | 2         | 0.16%   |
| fr_CH   | 2         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 722       | 56.94%  |
| BIOS | 546       | 43.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 805       | 63.44%  |
| Overlay | 346       | 27.27%  |
| Btrfs   | 65        | 5.12%   |
| Tmpfs   | 21        | 1.65%   |
| Xfs     | 15        | 1.18%   |
| Zfs     | 13        | 1.02%   |
| Ext2    | 2         | 0.16%   |
| F2fs    | 1         | 0.08%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 781       | 61.5%   |
| MBR     | 259       | 20.39%  |
| Unknown | 230       | 18.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1124      | 88.23%  |
| Yes       | 150       | 11.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 863       | 68.01%  |
| Yes       | 406       | 31.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 283       | 22.34%  |
| ASUSTek Computer                     | 200       | 15.79%  |
| Hewlett-Packard                      | 127       | 10.02%  |
| Dell                                 | 119       | 9.39%   |
| Gigabyte Technology                  | 81        | 6.39%   |
| MSI                                  | 61        | 4.81%   |
| Acer                                 | 55        | 4.34%   |
| ASRock                               | 51        | 4.03%   |
| Aquarius                             | 29        | 2.29%   |
| Apple                                | 29        | 2.29%   |
| Unknown                              | 26        | 2.05%   |
| Intel                                | 24        | 1.89%   |
| Google                               | 14        | 1.1%    |
| HUAWEI                               | 12        | 0.95%   |
| Samsung Electronics                  | 9         | 0.71%   |
| Fujitsu                              | 9         | 0.71%   |
| Supermicro                           | 8         | 0.63%   |
| Sony                                 | 8         | 0.63%   |
| Toshiba                              | 6         | 0.47%   |
| HONOR                                | 6         | 0.47%   |
| Microsoft                            | 5         | 0.39%   |
| Foxconn                              | 5         | 0.39%   |
| Framework                            | 4         | 0.32%   |
| eMachines                            | 4         | 0.32%   |
| ECS                                  | 4         | 0.32%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.24%   |
| Biostar                              | 3         | 0.24%   |
| BESSTAR Tech                         | 3         | 0.24%   |
| AZW                                  | 3         | 0.24%   |
| ASRockRack                           | 3         | 0.24%   |
| Timi                                 | 2         | 0.16%   |
| Techvision                           | 2         | 0.16%   |
| Shuttle                              | 2         | 0.16%   |
| Schenker                             | 2         | 0.16%   |
| Raspberry Pi Foundation              | 2         | 0.16%   |
| PC Specialist                        | 2         | 0.16%   |
| Notebook                             | 2         | 0.16%   |
| LG Electronics                       | 2         | 0.16%   |
| HC Technology.                       | 2         | 0.16%   |
| GPU Company                          | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US       | 100       | 7.89%   |
| Unknown                                         | 30        | 2.37%   |
| Aquarius NS585                                  | 29        | 2.29%   |
| ASUS All Series                                 | 28        | 2.21%   |
| ASRock H470M-HVS                                | 20        | 1.58%   |
| Lenovo ThinkCentre M55p 8808D8U                 | 12        | 0.95%   |
| ASUS PRIME B450M-K                              | 10        | 0.79%   |
| Gigabyte H81M-S2V                               | 8         | 0.63%   |
| Gigabyte A320M-S2H V2                           | 7         | 0.55%   |
| MSI MS-7996                                     | 6         | 0.47%   |
| ASUS S20 K29                                    | 6         | 0.47%   |
| Apple MacBookAir7,2                             | 6         | 0.47%   |
| ASUS ProArt X670E-CREATOR WIFI                  | 5         | 0.39%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX            | 4         | 0.32%   |
| ECS G31T-M9                                     | 4         | 0.32%   |
| Dell Precision 5570                             | 4         | 0.32%   |
| Lenovo ThinkStation P520 30BFS44D00             | 3         | 0.24%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US           | 3         | 0.24%   |
| HUAWEI BOHK-WAX9X                               | 3         | 0.24%   |
| HONOR NMH-WCX9                                  | 3         | 0.24%   |
| HP Laptop 15s-eq2xxx                            | 3         | 0.24%   |
| HP EliteBook 845 G8 Notebook PC                 | 3         | 0.24%   |
| HP EliteBook 840 G5                             | 3         | 0.24%   |
| HP EliteBook 840 G3                             | 3         | 0.24%   |
| HP Elite x360 830 13 inch G9 2-in-1 Notebook PC | 3         | 0.24%   |
| Gigabyte M56S-S3                                | 3         | 0.24%   |
| Gigabyte B450 AORUS ELITE                       | 3         | 0.24%   |
| Framework Laptop (13th Gen Intel Core)          | 3         | 0.24%   |
| Dell Latitude 7480                              | 3         | 0.24%   |
| ASUS ROG STRIX X570-E GAMING                    | 3         | 0.24%   |
| ASUS PRIME B450M-A                              | 3         | 0.24%   |
| Acer Aspire A515-56                             | 3         | 0.24%   |
| Techvision TVI7309X                             | 2         | 0.16%   |
| Supermicro X8ST3                                | 2         | 0.16%   |
| MSI MS-7C37                                     | 2         | 0.16%   |
| MSI MS-7C02                                     | 2         | 0.16%   |
| Microsoft Surface Pro 6                         | 2         | 0.16%   |
| Microsoft Surface Go                            | 2         | 0.16%   |
| Lenovo Yoga 7 14ARB7 82QF                       | 2         | 0.16%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00            | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 200       | 15.79%  |
| ASUS PRIME          | 37        | 2.92%   |
| Dell Latitude       | 36        | 2.84%   |
| Acer Aspire         | 36        | 2.84%   |
| Unknown             | 30        | 2.37%   |
| Aquarius NS585      | 29        | 2.29%   |
| ASUS All            | 28        | 2.21%   |
| Lenovo ThinkCentre  | 23        | 1.82%   |
| Lenovo IdeaPad      | 22        | 1.74%   |
| HP EliteBook        | 22        | 1.74%   |
| Dell Inspiron       | 21        | 1.66%   |
| ASUS VivoBook       | 21        | 1.66%   |
| ASRock H470M-HVS    | 20        | 1.58%   |
| Dell XPS            | 17        | 1.34%   |
| ASUS ROG            | 16        | 1.26%   |
| HP ProBook          | 13        | 1.03%   |
| HP Laptop           | 13        | 1.03%   |
| HP Pavilion         | 12        | 0.95%   |
| Lenovo Yoga         | 11        | 0.87%   |
| ASUS TUF            | 11        | 0.87%   |
| Dell Precision      | 10        | 0.79%   |
| Dell OptiPlex       | 10        | 0.79%   |
| Dell Vostro         | 9         | 0.71%   |
| Gigabyte H81M-S2V   | 8         | 0.63%   |
| Dell PowerEdge      | 8         | 0.63%   |
| ASUS Zenbook        | 8         | 0.63%   |
| HP ProDesk          | 7         | 0.55%   |
| HP ENVY             | 7         | 0.55%   |
| Gigabyte A320M-S2H  | 7         | 0.55%   |
| Apple MacBookAir7   | 7         | 0.55%   |
| Toshiba Satellite   | 6         | 0.47%   |
| MSI MS-7996         | 6         | 0.47%   |
| HP ZBook            | 6         | 0.47%   |
| ASUS S20            | 6         | 0.47%   |
| Acer Nitro          | 6         | 0.47%   |
| Microsoft Surface   | 5         | 0.39%   |
| Lenovo ThinkStation | 5         | 0.39%   |
| HP EliteDesk        | 5         | 0.39%   |
| HP Elite            | 5         | 0.39%   |
| HP Compaq           | 5         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 209       | 16.5%   |
| 2021    | 149       | 11.76%  |
| 2022    | 143       | 11.29%  |
| 2019    | 111       | 8.76%   |
| 2018    | 96        | 7.58%   |
| 2012    | 63        | 4.97%   |
| 2017    | 57        | 4.5%    |
| 2014    | 50        | 3.95%   |
| 2013    | 49        | 3.87%   |
| 2016    | 48        | 3.79%   |
| 2023    | 43        | 3.39%   |
| 2009    | 41        | 3.24%   |
| 2015    | 40        | 3.16%   |
| 2011    | 39        | 3.08%   |
| 2010    | 39        | 3.08%   |
| 2008    | 32        | 2.53%   |
| 2007    | 28        | 2.21%   |
| Unknown | 24        | 1.89%   |
| 2005    | 3         | 0.24%   |
| 2006    | 1         | 0.08%   |
| 2004    | 1         | 0.08%   |
| 2002    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 587       | 46.33%  |
| Desktop        | 460       | 36.31%  |
| Convertible    | 132       | 10.42%  |
| Mini pc        | 33        | 2.6%    |
| System on chip | 17        | 1.34%   |
| Server         | 14        | 1.1%    |
| Tablet         | 10        | 0.79%   |
| All in one     | 10        | 0.79%   |
| Other          | 2         | 0.16%   |
| Phone          | 1         | 0.08%   |
| Stick pc       | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1168      | 91.97%  |
| Enabled  | 102       | 8.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1252      | 98.82%  |
| Yes  | 15        | 1.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 305       | 23.96%  |
| 4.01-8.0        | 284       | 22.31%  |
| 16.01-24.0      | 220       | 17.28%  |
| 32.01-64.0      | 174       | 13.67%  |
| 3.01-4.0        | 145       | 11.39%  |
| 64.01-256.0     | 57        | 4.48%   |
| 1.01-2.0        | 32        | 2.51%   |
| 24.01-32.0      | 24        | 1.89%   |
| 2.01-3.0        | 15        | 1.18%   |
| 0.51-1.0        | 9         | 0.71%   |
| More than 256.0 | 6         | 0.47%   |
| 0.01-0.5        | 1         | 0.08%   |
| Unknown         | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 361       | 27.75%  |
| 4.01-8.0    | 257       | 19.75%  |
| 2.01-3.0    | 240       | 18.45%  |
| 0.51-1.0    | 184       | 14.14%  |
| 3.01-4.0    | 145       | 11.15%  |
| 8.01-16.0   | 59        | 4.53%   |
| 0.01-0.5    | 33        | 2.54%   |
| 16.01-24.0  | 10        | 0.77%   |
| 24.01-32.0  | 4         | 0.31%   |
| 64.01-256.0 | 4         | 0.31%   |
| 32.01-64.0  | 3         | 0.23%   |
| Unknown     | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 859       | 67.37%  |
| 2      | 251       | 19.69%  |
| 3      | 83        | 6.51%   |
| 4      | 37        | 2.9%    |
| 5      | 14        | 1.1%    |
| 6      | 11        | 0.86%   |
| 0      | 8         | 0.63%   |
| 8      | 3         | 0.24%   |
| 7      | 3         | 0.24%   |
| 10     | 2         | 0.16%   |
| 32     | 1         | 0.08%   |
| 29     | 1         | 0.08%   |
| 27     | 1         | 0.08%   |
| 19     | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1021      | 80.39%  |
| Yes       | 249       | 19.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1073      | 84.62%  |
| No        | 195       | 15.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 927       | 72.99%  |
| No        | 343       | 27.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 819       | 64.39%  |
| No        | 453       | 35.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 275       | 21.6%   |
| Russia       | 243       | 19.09%  |
| Germany      | 125       | 9.82%   |
| France       | 56        | 4.4%    |
| Brazil       | 46        | 3.61%   |
| UK           | 39        | 3.06%   |
| Spain        | 36        | 2.83%   |
| Canada       | 36        | 2.83%   |
| Sweden       | 31        | 2.44%   |
| Italy        | 28        | 2.2%    |
| Poland       | 27        | 2.12%   |
| China        | 20        | 1.57%   |
| India        | 19        | 1.49%   |
| Netherlands  | 17        | 1.34%   |
| Australia    | 16        | 1.26%   |
| Switzerland  | 14        | 1.1%    |
| Austria      | 12        | 0.94%   |
| Turkey       | 11        | 0.86%   |
| Czechia      | 11        | 0.86%   |
| Hungary      | 9         | 0.71%   |
| Finland      | 9         | 0.71%   |
| Argentina    | 9         | 0.71%   |
| Mexico       | 8         | 0.63%   |
| Indonesia    | 8         | 0.63%   |
| Slovakia     | 7         | 0.55%   |
| Norway       | 7         | 0.55%   |
| Chile        | 7         | 0.55%   |
| Belgium      | 7         | 0.55%   |
| Venezuela    | 6         | 0.47%   |
| Romania      | 6         | 0.47%   |
| Portugal     | 6         | 0.47%   |
| New Zealand  | 6         | 0.47%   |
| Belarus      | 6         | 0.47%   |
| Ukraine      | 5         | 0.39%   |
| Singapore    | 5         | 0.39%   |
| Israel       | 5         | 0.39%   |
| Hong Kong    | 5         | 0.39%   |
| South Africa | 4         | 0.31%   |
| Latvia       | 4         | 0.31%   |
| Japan        | 4         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 174       | 13.48%  |
| Bangor            | 143       | 11.08%  |
| Moscow            | 32        | 2.48%   |
| Saltsjoe-Boo      | 16        | 1.24%   |
| Berlin            | 12        | 0.93%   |
| Paris             | 11        | 0.85%   |
| St Petersburg     | 10        | 0.77%   |
| Vienna            | 9         | 0.7%    |
| Toronto           | 9         | 0.7%    |
| Frankfurt am Main | 8         | 0.62%   |
| Stockholm         | 7         | 0.54%   |
| Sydney            | 6         | 0.46%   |
| Prague            | 6         | 0.46%   |
| Manchester        | 6         | 0.46%   |
| Madrid            | 6         | 0.46%   |
| London            | 6         | 0.46%   |
| Bonn              | 6         | 0.46%   |
| Beijing           | 6         | 0.46%   |
| Wroclaw           | 5         | 0.39%   |
| Vancouver         | 5         | 0.39%   |
| Singapore         | 5         | 0.39%   |
| Gladbeck          | 5         | 0.39%   |
| Brasília         | 5         | 0.39%   |
| Barcelona         | 5         | 0.39%   |
| Zurich            | 4         | 0.31%   |
| Seattle           | 4         | 0.31%   |
| Rozhanovce        | 4         | 0.31%   |
| Milan             | 4         | 0.31%   |
| Melbourne         | 4         | 0.31%   |
| Marseille         | 4         | 0.31%   |
| Istanbul          | 4         | 0.31%   |
| Helsinki          | 4         | 0.31%   |
| Hamburg           | 4         | 0.31%   |
| Dublin            | 4         | 0.31%   |
| Delhi             | 4         | 0.31%   |
| Cologne           | 4         | 0.31%   |
| Budapest          | 4         | 0.31%   |
| Strasbourg        | 3         | 0.23%   |
| Shenzhen          | 3         | 0.23%   |
| Santiago          | 3         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 361       | 448    | 20.55%  |
| WDC                         | 243       | 371    | 13.83%  |
| Seagate                     | 150       | 215    | 8.54%   |
| SanDisk                     | 95        | 111    | 5.41%   |
| Crucial                     | 91        | 111    | 5.18%   |
| Toshiba                     | 89        | 107    | 5.07%   |
| Kingston                    | 82        | 90     | 4.67%   |
| Unknown                     | 66        | 85     | 3.76%   |
| SK hynix                    | 54        | 58     | 3.07%   |
| A-DATA Technology           | 49        | 65     | 2.79%   |
| Intel                       | 40        | 44     | 2.28%   |
| Micron Technology           | 38        | 40     | 2.16%   |
| Hitachi                     | 37        | 42     | 2.11%   |
| Netac                       | 27        | 28     | 1.54%   |
| HGST                        | 21        | 55     | 1.2%    |
| Kingston Technology Company | 17        | 22     | 0.97%   |
| SPCC                        | 16        | 18     | 0.91%   |
| KIOXIA                      | 16        | 18     | 0.91%   |
| Apple                       | 15        | 19     | 0.85%   |
| China                       | 14        | 16     | 0.8%    |
| Unknown                     | 11        | 13     | 0.63%   |
| Transcend                   | 10        | 12     | 0.57%   |
| SSSTC                       | 9         | 9      | 0.51%   |
| Silicon Motion              | 9         | 11     | 0.51%   |
| Phison                      | 9         | 9      | 0.51%   |
| Intenso                     | 9         | 9      | 0.51%   |
| LITEON                      | 8         | 8      | 0.46%   |
| JMicron Technology          | 8         | 8      | 0.46%   |
| Phison Electronics          | 7         | 14     | 0.4%    |
| Micron/Crucial Technology   | 7         | 8      | 0.4%    |
| KIOXIA-EXCERIA              | 7         | 7      | 0.4%    |
| Hewlett-Packard             | 7         | 9      | 0.4%    |
| PNY                         | 6         | 7      | 0.34%   |
| Plextor                     | 6         | 6      | 0.34%   |
| Patriot                     | 6         | 6      | 0.34%   |
| Fujitsu                     | 5         | 5      | 0.28%   |
| ADATA Technology            | 5         | 5      | 0.28%   |
| OCZ                         | 4         | 4      | 0.23%   |
| Maxtor                      | 4         | 4      | 0.23%   |
| GOODRAM                     | 4         | 5      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung MZVLB512HBJQ-000L7 512GB                      | 101       | 5.24%   |
| A-DATA SU800 512GB SSD                                | 29        | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 21        | 1.09%   |
| Netac SSD 240GB                                       | 19        | 0.98%   |
| Crucial CT480BX500SSD1 480GB                          | 19        | 0.98%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 15        | 0.78%   |
| Kingston SA400S37480G 480GB SSD                       | 15        | 0.78%   |
| Toshiba HDWD110 1TB                                   | 14        | 0.73%   |
| Kingston SA400S37240G 240GB SSD                       | 14        | 0.73%   |
| Samsung SSD 980 PRO 1TB                               | 13        | 0.67%   |
| Crucial CT500MX500SSD1 500GB                          | 13        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                          | 13        | 0.67%   |
| Samsung SSD 980 1TB                                   | 12        | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 12        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                           | 12        | 0.62%   |
| Unknown                                               | 11        | 0.57%   |
| Samsung SSD 870 EVO 500GB                             | 10        | 0.52%   |
| Samsung SSD 860 EVO 500GB                             | 10        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB                        | 9         | 0.47%   |
| Samsung SSD 980 500GB                                 | 9         | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB                          | 9         | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 8         | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB                        | 8         | 0.41%   |
| SanDisk NVMe SSD Drive 1TB                            | 8         | 0.41%   |
| Kingston SA400S37120G 120GB SSD                       | 8         | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB                        | 7         | 0.36%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 7         | 0.36%   |
| Samsung SSD 850 EVO 500GB                             | 7         | 0.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 7         | 0.36%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                   | 7         | 0.36%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB               | 7         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 6         | 0.31%   |
| Unknown SD/MMC/MS PRO 1GB                             | 6         | 0.31%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 6         | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB                        | 6         | 0.31%   |
| SanDisk NVMe SSD Drive 500GB                          | 6         | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB                        | 6         | 0.31%   |
| Samsung SSD 860 EVO 250GB                             | 6         | 0.31%   |
| Kingston SV300S37A120G 120GB SSD                      | 6         | 0.31%   |
| Unknown MMC Card  64GB                                | 5         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 168       | 271    | 35.97%  |
| Seagate             | 145       | 209    | 31.05%  |
| Toshiba             | 63        | 79     | 13.49%  |
| Hitachi             | 37        | 42     | 7.92%   |
| HGST                | 21        | 55     | 4.5%    |
| Unknown             | 6         | 6      | 1.28%   |
| Fujitsu             | 5         | 5      | 1.07%   |
| Samsung Electronics | 4         | 5      | 0.86%   |
| Apple               | 4         | 4      | 0.86%   |
| SABRENT             | 3         | 3      | 0.64%   |
| Maxtor              | 3         | 3      | 0.64%   |
| Hewlett-Packard     | 2         | 3      | 0.43%   |
| WALRAM              | 1         | 1      | 0.21%   |
| USB                 | 1         | 1      | 0.21%   |
| SYMTEC              | 1         | 1      | 0.21%   |
| External            | 1         | 1      | 0.21%   |
| DELLBOSS            | 1         | 1      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 99        | 126    | 17.77%  |
| Crucial             | 76        | 86     | 13.64%  |
| Kingston            | 58        | 64     | 10.41%  |
| SanDisk             | 42        | 49     | 7.54%   |
| A-DATA Technology   | 37        | 50     | 6.64%   |
| WDC                 | 36        | 46     | 6.46%   |
| Netac               | 26        | 27     | 4.67%   |
| Intel               | 14        | 15     | 2.51%   |
| China               | 14        | 16     | 2.51%   |
| SPCC                | 13        | 14     | 2.33%   |
| SK hynix            | 9         | 9      | 1.62%   |
| Intenso             | 9         | 9      | 1.62%   |
| Apple               | 9         | 9      | 1.62%   |
| Transcend           | 8         | 10     | 1.44%   |
| Micron Technology   | 8         | 9      | 1.44%   |
| Toshiba             | 7         | 8      | 1.26%   |
| LITEON              | 6         | 6      | 1.08%   |
| PNY                 | 5         | 6      | 0.9%    |
| Plextor             | 5         | 5      | 0.9%    |
| Patriot             | 4         | 4      | 0.72%   |
| OCZ                 | 4         | 4      | 0.72%   |
| JMicron Technology  | 4         | 4      | 0.72%   |
| GOODRAM             | 4         | 5      | 0.72%   |
| TO Exter            | 3         | 4      | 0.54%   |
| Hewlett-Packard     | 3         | 3      | 0.54%   |
| Wibtek              | 2         | 2      | 0.36%   |
| Team                | 2         | 2      | 0.36%   |
| Seagate             | 2         | 2      | 0.36%   |
| LITEONIT            | 2         | 2      | 0.36%   |
| Lexar               | 2         | 2      | 0.36%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.36%   |
| Gigabyte Technology | 2         | 2      | 0.36%   |
| AMD                 | 2         | 2      | 0.36%   |
| Unknown             | 2         | 4      | 0.36%   |
| Wellcomm            | 1         | 1      | 0.18%   |
| V-GeN               | 1         | 1      | 0.18%   |
| TrekStor            | 1         | 1      | 0.18%   |
| Timetec             | 1         | 2      | 0.18%   |
| T-FORCE             | 1         | 2      | 0.18%   |
| SSSTC               | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 624       | 792    | 38.83%  |
| SSD     | 490       | 647    | 30.49%  |
| HDD     | 411       | 691    | 25.58%  |
| MMC     | 66        | 83     | 4.11%   |
| Unknown | 16        | 18     | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 741       | 1236   | 49.7%   |
| NVMe | 624       | 787    | 41.85%  |
| MMC  | 66        | 83     | 4.43%   |
| SAS  | 60        | 125    | 4.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 535       | 670    | 56.02%  |
| 0.51-1.0   | 263       | 344    | 27.54%  |
| 1.01-2.0   | 74        | 121    | 7.75%   |
| 3.01-4.0   | 35        | 72     | 3.66%   |
| 4.01-10.0  | 23        | 95     | 2.41%   |
| 2.01-3.0   | 19        | 25     | 1.99%   |
| 10.01-20.0 | 6         | 11     | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 334       | 26.03%  |
| 101-250        | 240       | 18.71%  |
| Unknown        | 216       | 16.84%  |
| 501-1000       | 154       | 12%     |
| 1001-2000      | 92        | 7.17%   |
| More than 3000 | 67        | 5.22%   |
| 51-100         | 58        | 4.52%   |
| 1-20           | 52        | 4.05%   |
| 21-50          | 42        | 3.27%   |
| 2001-3000      | 28        | 2.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 487       | 37.69%  |
| Unknown        | 216       | 16.72%  |
| 21-50          | 149       | 11.53%  |
| 101-250        | 139       | 10.76%  |
| 51-100         | 100       | 7.74%   |
| 251-500        | 73        | 5.65%   |
| 501-1000       | 54        | 4.18%   |
| 1001-2000      | 42        | 3.25%   |
| More than 3000 | 21        | 1.63%   |
| 2001-3000      | 11        | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB          | 12        | 12     | 8%      |
| WDC WD3200AAJS-00L7A0 320GB           | 3         | 3      | 2%      |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 3         | 3      | 2%      |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 3      | 2%      |
| Seagate ST9500325AS 500GB             | 3         | 3      | 2%      |
| Seagate ST3250410AS 250GB             | 3         | 3      | 2%      |
| WDC WD30EFRX-68EUZN0 3TB              | 2         | 2      | 1.33%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 1.33%   |
| Seagate ST2000DX001-1CM164 2TB        | 2         | 3      | 1.33%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 2      | 1.33%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 1.33%   |
| Maxtor STM3160815AS 160GB             | 2         | 2      | 1.33%   |
| LITEON CV8-8E128-HP 128GB SSD         | 2         | 2      | 1.33%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 1.33%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 2      | 1.33%   |
| Hitachi HDS721050CLA362 500GB         | 2         | 3      | 1.33%   |
| Hitachi HDS721010CLA332 1TB           | 2         | 2      | 1.33%   |
| ZHITAI TiPlus5000 512GB               | 1         | 1      | 0.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 2      | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.67%   |
| WDC WD80EMAZ-00WJTA0 8TB              | 1         | 11     | 0.67%   |
| WDC WD800AAJS-60WAA0 80GB             | 1         | 1      | 0.67%   |
| WDC WD7500BPKX-80HPJT0 752GB          | 1         | 1      | 0.67%   |
| WDC WD5000LPVT-08G33T1 500GB          | 1         | 1      | 0.67%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 1      | 0.67%   |
| WDC WD5000AAKS-00A7B0 500GB           | 1         | 1      | 0.67%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 1      | 0.67%   |
| WDC WD40EFRX-68N32N0 4TB              | 1         | 3      | 0.67%   |
| WDC WD400UE-22HCT0 40GB               | 1         | 1      | 0.67%   |
| WDC WD400BD-60LRA0 40GB               | 1         | 1      | 0.67%   |
| WDC WD400BB-75CAA0 40GB               | 1         | 1      | 0.67%   |
| WDC WD3200BPVT-80ZEST0 320GB          | 1         | 1      | 0.67%   |
| WDC WD3200BEVT-80A0RT0 320GB          | 1         | 1      | 0.67%   |
| WDC WD3200BEVT-00A0RT0 320GB          | 1         | 1      | 0.67%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 0.67%   |
| WDC WD2500BEVT-22A23T0 208GB          | 1         | 1      | 0.67%   |
| WDC WD2500AAKX-001CA0 250GB           | 1         | 1      | 0.67%   |
| WDC WD2500AAKS-00VSA0 250GB           | 1         | 2      | 0.67%   |
| WDC WD2500AAJS-00YZCA0 250GB          | 1         | 1      | 0.67%   |
| WDC WD2500AAJS-00B4A0 250GB           | 1         | 1      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 49        | 64     | 33.11%  |
| Seagate             | 25        | 28     | 16.89%  |
| Hitachi             | 11        | 12     | 7.43%   |
| SK hynix            | 9         | 9      | 6.08%   |
| Samsung Electronics | 8         | 9      | 5.41%   |
| Toshiba             | 6         | 6      | 4.05%   |
| Kingston            | 6         | 6      | 4.05%   |
| Intel               | 6         | 6      | 4.05%   |
| HGST                | 6         | 6      | 4.05%   |
| SanDisk             | 4         | 4      | 2.7%    |
| Crucial             | 4         | 4      | 2.7%    |
| Micron Technology   | 2         | 2      | 1.35%   |
| Maxtor              | 2         | 2      | 1.35%   |
| LITEON              | 2         | 2      | 1.35%   |
| A-DATA Technology   | 2         | 2      | 1.35%   |
| ZHITAI              | 1         | 1      | 0.68%   |
| SSSTC               | 1         | 1      | 0.68%   |
| ShiJi               | 1         | 3      | 0.68%   |
| Mushkin             | 1         | 1      | 0.68%   |
| KingSpec            | 1         | 1      | 0.68%   |
| JMicron Technology  | 1         | 1      | 0.68%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 60     | 46.94%  |
| Seagate             | 25        | 28     | 25.51%  |
| Hitachi             | 11        | 12     | 11.22%  |
| Toshiba             | 6         | 6      | 6.12%   |
| HGST                | 6         | 6      | 6.12%   |
| Samsung Electronics | 2         | 3      | 2.04%   |
| Maxtor              | 2         | 2      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 91        | 117    | 64.54%  |
| SSD  | 35        | 36     | 24.82%  |
| NVMe | 15        | 17     | 10.64%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 880       | 1392   | 63.77%  |
| Detected | 359       | 667    | 26.01%  |
| Malfunc  | 139       | 170    | 10.07%  |
| Failed   | 1         | 1      | 0.07%   |
| Limited  | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 684       | 41.5%   |
| Samsung Electronics            | 275       | 16.69%  |
| AMD                            | 225       | 13.65%  |
| SanDisk                        | 97        | 5.89%   |
| SK hynix                       | 44        | 2.67%   |
| Kingston Technology Company    | 41        | 2.49%   |
| Micron Technology              | 30        | 1.82%   |
| ASMedia Technology             | 27        | 1.64%   |
| Micron/Crucial Technology      | 25        | 1.52%   |
| Phison Electronics             | 24        | 1.46%   |
| Toshiba America Info Systems   | 21        | 1.27%   |
| ADATA Technology               | 20        | 1.21%   |
| KIOXIA                         | 18        | 1.09%   |
| Nvidia                         | 16        | 0.97%   |
| Silicon Motion                 | 12        | 0.73%   |
| JMicron Technology             | 12        | 0.73%   |
| Marvell Technology Group       | 11        | 0.67%   |
| Solid State Storage Technology | 9         | 0.55%   |
| Broadcom / LSI                 | 6         | 0.36%   |
| Yangtze Memory Technologies    | 5         | 0.3%    |
| MAXIO Technology (Hangzhou)    | 5         | 0.3%    |
| LSI Logic / Symbios Logic      | 5         | 0.3%    |
| INNOGRIT                       | 4         | 0.24%   |
| Adaptec                        | 4         | 0.24%   |
| Biwin Storage Technology       | 3         | 0.18%   |
| VIA Technologies               | 2         | 0.12%   |
| Union Memory (Shenzhen)        | 2         | 0.12%   |
| Transcend                      | 2         | 0.12%   |
| Silicon Image                  | 2         | 0.12%   |
| Seagate Technology             | 2         | 0.12%   |
| Realtek Semiconductor          | 2         | 0.12%   |
| Lite-On Technology             | 2         | 0.12%   |
| Apple                          | 2         | 0.12%   |
| Shenzhen Longsys Electronics   | 1         | 0.06%   |
| Radian Memory Systems          | 1         | 0.06%   |
| Netac Technology               | 1         | 0.06%   |
| Loongson Technology            | 1         | 0.06%   |
| Jiangsu Huacun Elec.           | 1         | 0.06%   |
| IBM                            | 1         | 0.06%   |
| HighPoint Technologies         | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 162       | 8.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 161       | 8.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 67        | 3.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 54        | 2.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 2.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 43        | 2.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 42        | 2.27%   |
| Intel Comet Lake SATA AHCI Controller                                          | 41        | 2.21%   |
| Samsung NVMe SSD Controller 980                                                | 40        | 2.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 34        | 1.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 31        | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 1.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 27        | 1.46%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 24        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 23        | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 21        | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 21        | 1.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 20        | 1.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 19        | 1.02%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 19        | 1.02%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 0.92%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 16        | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 16        | 0.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 0.76%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 14        | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 13        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.65%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 12        | 0.65%   |
| Kingston Company Company Non-Volatile memory controller                        | 12        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 11        | 0.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 0.59%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 11        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11        | 0.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 808       | 49.39%  |
| NVMe | 621       | 37.96%  |
| IDE  | 110       | 6.72%   |
| RAID | 88        | 5.38%   |
| SAS  | 7         | 0.43%   |
| SCSI | 2         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 932       | 73.56%  |
| AMD               | 311       | 24.55%  |
| ARM               | 12        | 0.95%   |
| sifive,u74-mc     | 4         | 0.32%   |
| Unknown           | 3         | 0.24%   |
| Qualcomm          | 2         | 0.16%   |
| Loongson          | 1         | 0.08%   |
| CHRP IBM,8233-E8B | 1         | 0.08%   |
| CentaurHauls      | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 109       | 8.59%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 29        | 2.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 28        | 2.21%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 21        | 1.65%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 16        | 1.26%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 1.1%    |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 12        | 0.95%   |
| Intel 12th Gen Core i5-1235U                  | 12        | 0.95%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.79%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 10        | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 0.79%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics   | 10        | 0.79%   |
| Intel 12th Gen Core i7-12700H                 | 9         | 0.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.71%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9         | 0.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 0.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 8         | 0.63%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.63%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 8         | 0.63%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 7         | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.55%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 7         | 0.55%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 7         | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.55%   |
| ARM Processor                                 | 7         | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 7         | 0.55%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 6         | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.47%   |
| Intel 13th Gen Core i7-1360P                  | 6         | 0.47%   |
| Intel 12th Gen Core i7-1260P                  | 6         | 0.47%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.47%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 0.47%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 6         | 0.47%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.47%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 291       | 22.95%  |
| Intel Core i5           | 184       | 14.51%  |
| Intel Core i7           | 159       | 12.54%  |
| AMD Ryzen 5             | 90        | 7.1%    |
| Intel Core i3           | 83        | 6.55%   |
| AMD Ryzen 7             | 78        | 6.15%   |
| Intel Pentium           | 54        | 4.26%   |
| Intel Celeron           | 51        | 4.02%   |
| Intel Xeon              | 36        | 2.84%   |
| Intel Core 2 Duo        | 36        | 2.84%   |
| AMD Ryzen 9             | 32        | 2.52%   |
| AMD Ryzen 3             | 16        | 1.26%   |
| Intel Pentium Dual-Core | 15        | 1.18%   |
| Intel Core 2            | 15        | 1.18%   |
| AMD Ryzen 5 PRO         | 13        | 1.03%   |
| AMD Ryzen 7 PRO         | 10        | 0.79%   |
| AMD E                   | 8         | 0.63%   |
| AMD FX                  | 7         | 0.55%   |
| Intel Pentium Silver    | 6         | 0.47%   |
| Intel Core 2 Quad       | 6         | 0.47%   |
| Intel Atom              | 6         | 0.47%   |
| AMD Athlon              | 5         | 0.39%   |
| AMD Athlon 64 X2        | 4         | 0.32%   |
| AMD A6                  | 4         | 0.32%   |
| Intel Pentium M         | 3         | 0.24%   |
| Intel Core i9           | 3         | 0.24%   |
| AMD Phenom II X3        | 3         | 0.24%   |
| AMD EPYC                | 3         | 0.24%   |
| AMD Athlon II X3        | 3         | 0.24%   |
| Intel Pentium Gold      | 2         | 0.16%   |
| Intel Pentium 4         | 2         | 0.16%   |
| Intel Genuine           | 2         | 0.16%   |
| ARM Allwinner           | 2         | 0.16%   |
| AMD Ryzen 3 PRO         | 2         | 0.16%   |
| AMD Phenom II X4        | 2         | 0.16%   |
| AMD GX                  | 2         | 0.16%   |
| AMD E2                  | 2         | 0.16%   |
| AMD E1                  | 2         | 0.16%   |
| AMD Athlon II X4        | 2         | 0.16%   |
| AMD Athlon II X2        | 2         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 476       | 37.57%  |
| 2       | 376       | 29.68%  |
| 8       | 131       | 10.34%  |
| 6       | 127       | 10.02%  |
| 12      | 43        | 3.39%   |
| 10      | 30        | 2.37%   |
| 16      | 21        | 1.66%   |
| 14      | 19        | 1.5%    |
| 1       | 17        | 1.34%   |
| Unknown | 9         | 0.71%   |
| 24      | 7         | 0.55%   |
| 3       | 7         | 0.55%   |
| 44      | 1         | 0.08%   |
| 28      | 1         | 0.08%   |
| 22      | 1         | 0.08%   |
| 20      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1244      | 98.18%  |
| 2       | 14        | 1.1%    |
| Unknown | 9         | 0.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 891       | 70.21%  |
| 1       | 368       | 29%     |
| Unknown | 9         | 0.71%   |
| 4       | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1247      | 98.42%  |
| Unknown        | 12        | 0.95%   |
| 32-bit         | 6         | 0.47%   |
| 64-bit         | 2         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 342       | 26.84%  |
| 0x806c1    | 142       | 11.15%  |
| 0x306c3    | 63        | 4.95%   |
| 0x1067a    | 35        | 2.75%   |
| 0x08108109 | 32        | 2.51%   |
| 0x906eb    | 30        | 2.35%   |
| 0x906a3    | 24        | 1.88%   |
| 0x306a9    | 24        | 1.88%   |
| 0xa0655    | 23        | 1.81%   |
| 0x906a4    | 23        | 1.81%   |
| 0x206a7    | 23        | 1.81%   |
| 0x0a50000d | 23        | 1.81%   |
| 0x806e9    | 22        | 1.73%   |
| 0x506e3    | 20        | 1.57%   |
| 0x806ec    | 19        | 1.49%   |
| 0x906ea    | 17        | 1.33%   |
| 0x806ea    | 17        | 1.33%   |
| 0x0a50000c | 16        | 1.26%   |
| 0x40651    | 14        | 1.1%    |
| 0x906e9    | 13        | 1.02%   |
| 0x20655    | 13        | 1.02%   |
| 0x0a601203 | 13        | 1.02%   |
| 0x706a8    | 12        | 0.94%   |
| 0x6f2      | 12        | 0.94%   |
| 0x406e3    | 12        | 0.94%   |
| 0x306d4    | 12        | 0.94%   |
| 0x08608103 | 12        | 0.94%   |
| 0x90672    | 10        | 0.78%   |
| 0x08600106 | 10        | 0.78%   |
| 0x30678    | 9         | 0.71%   |
| 0x0a20120a | 9         | 0.71%   |
| 0xb06a2    | 8         | 0.63%   |
| 0x10676    | 8         | 0.63%   |
| 0x0a404102 | 8         | 0.63%   |
| 0xb0671    | 7         | 0.55%   |
| 0x0810100b | 7         | 0.55%   |
| 0x0800820d | 7         | 0.55%   |
| 0x906c0    | 6         | 0.47%   |
| 0x08701021 | 6         | 0.47%   |
| 0x806c2    | 5         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 180       | 14.18%  |
| TigerLake        | 160       | 12.61%  |
| Unknown          | 103       | 8.12%   |
| Haswell          | 102       | 8.04%   |
| Zen 3            | 81        | 6.38%   |
| Alderlake Hybrid | 76        | 5.99%   |
| Skylake          | 58        | 4.57%   |
| Penryn           | 55        | 4.33%   |
| Zen+             | 53        | 4.18%   |
| IvyBridge        | 45        | 3.55%   |
| Zen 2            | 43        | 3.39%   |
| CometLake        | 42        | 3.31%   |
| SandyBridge      | 36        | 2.84%   |
| Westmere         | 26        | 2.05%   |
| Core             | 26        | 2.05%   |
| Broadwell        | 24        | 1.89%   |
| Zen              | 20        | 1.58%   |
| Goldmont plus    | 20        | 1.58%   |
| Silvermont       | 18        | 1.42%   |
| K10              | 16        | 1.26%   |
| Bobcat           | 12        | 0.95%   |
| Excavator        | 11        | 0.87%   |
| IceLake          | 10        | 0.79%   |
| Tremont          | 8         | 0.63%   |
| Piledriver       | 8         | 0.63%   |
| Nehalem          | 8         | 0.63%   |
| Jaguar           | 5         | 0.39%   |
| Goldmont         | 5         | 0.39%   |
| P6               | 4         | 0.32%   |
| K8 Hammer        | 4         | 0.32%   |
| NetBurst         | 3         | 0.24%   |
| K10 Llano        | 2         | 0.16%   |
| Bonnell          | 2         | 0.16%   |
| Steamroller      | 1         | 0.08%   |
| Puma             | 1         | 0.08%   |
| Gracemont        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 745       | 52.76%  |
| AMD                        | 335       | 23.73%  |
| Nvidia                     | 306       | 21.67%  |
| Matrox Electronics Systems | 14        | 0.99%   |
| ASPEED Technology          | 9         | 0.64%   |
| Zhaoxin                    | 1         | 0.07%   |
| Loongson Technology        | 1         | 0.07%   |
| Huawei Technologies        | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 154       | 10.69%  |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 43        | 2.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 41        | 2.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 38        | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 31        | 2.15%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 29        | 2.01%   |
| Intel UHD Graphics 620                                                      | 27        | 1.87%   |
| Intel HD Graphics 620                                                       | 25        | 1.73%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 25        | 1.73%   |
| AMD Renoir                                                                  | 23        | 1.6%    |
| AMD Lucienne                                                                | 23        | 1.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 22        | 1.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 21        | 1.46%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 20        | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20        | 1.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 19        | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 19        | 1.32%   |
| Nvidia GF108 [GeForce GT 730]                                               | 18        | 1.25%   |
| AMD Barcelo                                                                 | 17        | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 16        | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                         | 16        | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 16        | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 16        | 1.11%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 16        | 1.11%   |
| Intel HD Graphics 630                                                       | 15        | 1.04%   |
| Intel HD Graphics 530                                                       | 14        | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 13        | 0.9%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 13        | 0.9%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 13        | 0.9%    |
| AMD Rembrandt [Radeon 680M]                                                 | 13        | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 13        | 0.9%    |
| AMD Raphael                                                                 | 13        | 0.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 12        | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 11        | 0.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 11        | 0.76%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 10        | 0.69%   |
| ASPEED Technology ASPEED Graphics Family                                    | 9         | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 8         | 0.56%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 8         | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 8         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 592       | 46.61%  |
| 1 x AMD                 | 268       | 21.1%   |
| 1 x Nvidia              | 165       | 12.99%  |
| Intel + Nvidia          | 115       | 9.06%   |
| Other                   | 25        | 1.97%   |
| AMD + Nvidia            | 24        | 1.89%   |
| 2 x AMD                 | 21        | 1.65%   |
| Intel + AMD             | 19        | 1.5%    |
| 1 x Matrox              | 14        | 1.1%    |
| 2 x Intel               | 13        | 1.02%   |
| 1 x ASPEED              | 8         | 0.63%   |
| 2 x Nvidia              | 1         | 0.08%   |
| 1 x Zhaoxin             | 1         | 0.08%   |
| 1 x Loongson Technology | 1         | 0.08%   |
| 1 x Huawei Technologies | 1         | 0.08%   |
| AMD + Matrox            | 1         | 0.08%   |
| AMD + ASPEED            | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 941       | 74.09%  |
| Unknown     | 218       | 17.17%  |
| Proprietary | 111       | 8.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 944       | 74.21%  |
| 0.01-0.5   | 94        | 7.39%   |
| 1.01-2.0   | 62        | 4.87%   |
| 3.01-4.0   | 47        | 3.69%   |
| 7.01-8.0   | 45        | 3.54%   |
| 0.51-1.0   | 39        | 3.07%   |
| 5.01-6.0   | 12        | 0.94%   |
| 8.01-16.0  | 12        | 0.94%   |
| 2.01-3.0   | 8         | 0.63%   |
| 16.01-24.0 | 7         | 0.55%   |
| 4.01-5.0   | 1         | 0.08%   |
| 0          | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 224       | 19.15%  |
| Samsung Electronics     | 112       | 9.57%   |
| BOE                     | 102       | 8.72%   |
| Chimei Innolux          | 101       | 8.63%   |
| LG Display              | 73        | 6.24%   |
| Dell                    | 62        | 5.3%    |
| Goldstar                | 46        | 3.93%   |
| Hewlett-Packard         | 37        | 3.16%   |
| Ancor Communications    | 33        | 2.82%   |
| Lenovo                  | 31        | 2.65%   |
| BenQ                    | 30        | 2.56%   |
| Acer                    | 27        | 2.31%   |
| Sharp                   | 26        | 2.22%   |
| Apple                   | 24        | 2.05%   |
| AOC                     | 24        | 2.05%   |
| PANDA                   | 20        | 1.71%   |
| Philips                 | 19        | 1.62%   |
| InfoVision              | 15        | 1.28%   |
| ASUSTek Computer        | 14        | 1.2%    |
| Iiyama                  | 12        | 1.03%   |
| ViewSonic               | 8         | 0.68%   |
| CSO                     | 8         | 0.68%   |
| LG Electronics          | 7         | 0.6%    |
| Sony                    | 6         | 0.51%   |
| Sceptre Tech            | 6         | 0.51%   |
| Chi Mei Optoelectronics | 6         | 0.51%   |
| Unknown                 | 6         | 0.51%   |
| Vizio                   | 4         | 0.34%   |
| Unknown                 | 4         | 0.34%   |
| Mi                      | 4         | 0.34%   |
| LG Philips              | 4         | 0.34%   |
| HKC                     | 4         | 0.34%   |
| Toshiba                 | 3         | 0.26%   |
| RTK                     | 3         | 0.26%   |
| Fujitsu Siemens         | 3         | 0.26%   |
| SAC                     | 2         | 0.17%   |
| Panasonic               | 2         | 0.17%   |
| NEC Computers           | 2         | 0.17%   |
| MStar                   | 2         | 0.17%   |
| MSI                     | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 91        | 7.58%   |
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 17        | 1.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 11        | 0.92%   |
| Chimei Innolux LCD Monitor CMN1387 1920x1080 293x165mm 13.2-inch      | 7         | 0.58%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 6         | 0.5%    |
| Unknown                                                               | 6         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 5         | 0.42%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4         | 0.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.33%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.25%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 3         | 0.25%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3         | 0.25%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 3         | 0.25%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 3         | 0.25%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 3         | 0.25%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 3         | 0.25%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.25%   |
| Lenovo T22i-20 LEN61FE 1920x1080 476x268mm 21.5-inch                  | 3         | 0.25%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch             | 3         | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 0.25%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch            | 3         | 0.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3         | 0.25%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 3         | 0.25%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 3         | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN13C6 1920x1200 286x178mm 13.3-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 3         | 0.25%   |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                 | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 594       | 52.85%  |
| 1366x768 (WXGA)    | 131       | 11.65%  |
| 3840x2160 (4K)     | 66        | 5.87%   |
| 2560x1440 (QHD)    | 66        | 5.87%   |
| 1920x1200 (WUXGA)  | 42        | 3.74%   |
| 1600x900 (HD+)     | 34        | 3.02%   |
| 1440x900 (WXGA+)   | 19        | 1.69%   |
| Unknown            | 16        | 1.42%   |
| 1680x1050 (WSXGA+) | 15        | 1.33%   |
| 1280x800 (WXGA)    | 13        | 1.16%   |
| 1280x1024 (SXGA)   | 13        | 1.16%   |
| 2560x1600          | 12        | 1.07%   |
| 3440x1440          | 11        | 0.98%   |
| 3840x2400          | 10        | 0.89%   |
| 2880x1800          | 8         | 0.71%   |
| 2560x1080          | 8         | 0.71%   |
| 1360x768           | 6         | 0.53%   |
| 1920x540           | 5         | 0.44%   |
| 4480x1440          | 4         | 0.36%   |
| 3000x2000          | 4         | 0.36%   |
| 2256x1504          | 4         | 0.36%   |
| 3840x1600          | 3         | 0.27%   |
| 2736x1824          | 3         | 0.27%   |
| 2288x1287          | 3         | 0.27%   |
| 1920x1280          | 3         | 0.27%   |
| 7680x2160          | 2         | 0.18%   |
| 3840x1200          | 2         | 0.18%   |
| 3456x2160          | 2         | 0.18%   |
| 3072x1920          | 2         | 0.18%   |
| 2160x1440          | 2         | 0.18%   |
| 1800x1200          | 2         | 0.18%   |
| 800x1280           | 1         | 0.09%   |
| 7280x2160          | 1         | 0.09%   |
| 6400x2160          | 1         | 0.09%   |
| 6400x1440          | 1         | 0.09%   |
| 5760x2160          | 1         | 0.09%   |
| 3840x1100          | 1         | 0.09%   |
| 3840x1080          | 1         | 0.09%   |
| 3286x1080          | 1         | 0.09%   |
| 3200x2000          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 238       | 20.46%  |
| 15      | 230       | 19.78%  |
| 14      | 104       | 8.94%   |
| 27      | 85        | 7.31%   |
| 24      | 84        | 7.22%   |
| 21      | 69        | 5.93%   |
| 23      | 61        | 5.25%   |
| Unknown | 41        | 3.53%   |
| 17      | 37        | 3.18%   |
| 31      | 24        | 2.06%   |
| 12      | 22        | 1.89%   |
| 11      | 20        | 1.72%   |
| 16      | 18        | 1.55%   |
| 34      | 17        | 1.46%   |
| 19      | 16        | 1.38%   |
| 18      | 16        | 1.38%   |
| 20      | 12        | 1.03%   |
| 22      | 10        | 0.86%   |
| 32      | 7         | 0.6%    |
| 26      | 5         | 0.43%   |
| 84      | 4         | 0.34%   |
| 72      | 4         | 0.34%   |
| 40      | 4         | 0.34%   |
| 142     | 3         | 0.26%   |
| 52      | 3         | 0.26%   |
| 28      | 3         | 0.26%   |
| 10      | 3         | 0.26%   |
| 54      | 2         | 0.17%   |
| 48      | 2         | 0.17%   |
| 46      | 2         | 0.17%   |
| 43      | 2         | 0.17%   |
| 37      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 85      | 1         | 0.09%   |
| 75      | 1         | 0.09%   |
| 67      | 1         | 0.09%   |
| 49      | 1         | 0.09%   |
| 42      | 1         | 0.09%   |
| 39      | 1         | 0.09%   |
| 38      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 407       | 35.48%  |
| 201-300        | 224       | 19.53%  |
| 501-600        | 219       | 19.09%  |
| 401-500        | 114       | 9.94%   |
| 351-400        | 46        | 4.01%   |
| Unknown        | 41        | 3.57%   |
| 601-700        | 32        | 2.79%   |
| 701-800        | 27        | 2.35%   |
| 1501-2000      | 10        | 0.87%   |
| 1001-1500      | 10        | 0.87%   |
| 801-900        | 9         | 0.78%   |
| More than 2000 | 3         | 0.26%   |
| 901-1000       | 3         | 0.26%   |
| 101-200        | 1         | 0.09%   |
| 1-100          | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 824       | 78.18%  |
| 16/10   | 127       | 12.05%  |
| Unknown | 34        | 3.23%   |
| 21/9    | 21        | 1.99%   |
| 3/2     | 19        | 1.8%    |
| 5/4     | 13        | 1.23%   |
| 4/3     | 7         | 0.66%   |
| 1.00    | 3         | 0.28%   |
| 32/9    | 2         | 0.19%   |
| 3.40    | 1         | 0.09%   |
| 0.67    | 1         | 0.09%   |
| 0.58    | 1         | 0.09%   |
| 0.45    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 229       | 19.72%  |
| 81-90          | 180       | 15.5%   |
| 201-250        | 175       | 15.07%  |
| 71-80          | 160       | 13.78%  |
| 301-350        | 89        | 7.67%   |
| 351-500        | 54        | 4.65%   |
| 151-200        | 44        | 3.79%   |
| Unknown        | 41        | 3.53%   |
| 251-300        | 34        | 2.93%   |
| 121-130        | 28        | 2.41%   |
| More than 1000 | 22        | 1.89%   |
| 51-60          | 21        | 1.81%   |
| 61-70          | 20        | 1.72%   |
| 141-150        | 20        | 1.72%   |
| 111-120        | 20        | 1.72%   |
| 501-1000       | 13        | 1.12%   |
| 131-140        | 4         | 0.34%   |
| 41-50          | 3         | 0.26%   |
| 1-40           | 2         | 0.17%   |
| 91-100         | 2         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 350       | 30.84%  |
| 51-100        | 270       | 23.79%  |
| 101-120       | 219       | 19.3%   |
| 161-240       | 207       | 18.24%  |
| Unknown       | 41        | 3.61%   |
| More than 240 | 30        | 2.64%   |
| 1-50          | 18        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 870       | 68.08%  |
| 0     | 236       | 18.47%  |
| 2     | 153       | 11.97%  |
| 3     | 19        | 1.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 686       | 37.96%  |
| Realtek Semiconductor             | 650       | 35.97%  |
| Qualcomm Atheros                  | 118       | 6.53%   |
| Broadcom                          | 73        | 4.04%   |
| MediaTek                          | 52        | 2.88%   |
| ASIX Electronics                  | 23        | 1.27%   |
| Broadcom Limited                  | 19        | 1.05%   |
| Qualcomm                          | 17        | 0.94%   |
| Nvidia                            | 15        | 0.83%   |
| Marvell Technology Group          | 15        | 0.83%   |
| TP-Link                           | 14        | 0.77%   |
| Ralink Technology                 | 14        | 0.77%   |
| Aquantia                          | 9         | 0.5%    |
| Sierra Wireless                   | 8         | 0.44%   |
| ASUSTek Computer                  | 6         | 0.33%   |
| Xiaomi                            | 5         | 0.28%   |
| Microsoft                         | 5         | 0.28%   |
| Ralink                            | 4         | 0.22%   |
| Mellanox Technologies             | 4         | 0.22%   |
| Lenovo                            | 4         | 0.22%   |
| Google                            | 4         | 0.22%   |
| DisplayLink                       | 4         | 0.22%   |
| Dell                              | 4         | 0.22%   |
| D-Link                            | 4         | 0.22%   |
| Samsung Electronics               | 3         | 0.17%   |
| NetGear                           | 3         | 0.17%   |
| Texas Instruments                 | 2         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.11%   |
| Microchip Technology              | 2         | 0.11%   |
| JMicron Technology                | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| Emulex                            | 2         | 0.11%   |
| American Megatrends               | 2         | 0.11%   |
| 3Com                              | 2         | 0.11%   |
| Wacom                             | 1         | 0.06%   |
| U-Blox                            | 1         | 0.06%   |
| SysKonnect                        | 1         | 0.06%   |
| Spreadtrum Communications         | 1         | 0.06%   |
| Solarflare Communications         | 1         | 0.06%   |
| Raspberry Pi                      | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 445       | 20.17%  |
| Intel Wi-Fi 6 AX201                                               | 140       | 6.35%   |
| Intel Ethernet Connection (13) I219-V                             | 108       | 4.9%    |
| Intel Wi-Fi 6 AX200                                               | 54        | 2.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 2.22%   |
| Intel Wireless 8265 / 8275                                        | 49        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 48        | 2.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 44        | 1.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 37        | 1.68%   |
| Intel Ethernet Controller I225-V                                  | 29        | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 1.13%   |
| Intel Wireless 7260                                               | 24        | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22        | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 20        | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.91%   |
| Intel Wireless 8260                                               | 20        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 19        | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 0.86%   |
| Intel I211 Gigabit Network Connection                             | 19        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 17        | 0.77%   |
| Intel Wireless 7265                                               | 15        | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 12        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 0.54%   |
| Intel 82566DM Gigabit Network Connection                          | 12        | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 11        | 0.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 0.5%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 10        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.45%   |
| Realtek 802.11ac NIC                                              | 9         | 0.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 553       | 56.49%  |
| Realtek Semiconductor             | 138       | 14.1%   |
| Qualcomm Atheros                  | 93        | 9.5%    |
| MediaTek                          | 50        | 5.11%   |
| Broadcom                          | 49        | 5.01%   |
| Broadcom Limited                  | 17        | 1.74%   |
| Ralink Technology                 | 14        | 1.43%   |
| TP-Link                           | 13        | 1.33%   |
| Qualcomm                          | 12        | 1.23%   |
| Sierra Wireless                   | 8         | 0.82%   |
| ASUSTek Computer                  | 6         | 0.61%   |
| Ralink                            | 4         | 0.41%   |
| Marvell Technology Group          | 4         | 0.41%   |
| D-Link                            | 4         | 0.41%   |
| NetGear                           | 3         | 0.31%   |
| Microsoft                         | 3         | 0.31%   |
| Qualcomm Atheros Communications   | 2         | 0.2%    |
| Wacom                             | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |
| Belkin Components                 | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 140       | 14.21%  |
| Intel Wi-Fi 6 AX200                                            | 54        | 5.48%   |
| Intel Wireless 8265 / 8275                                     | 49        | 4.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 44        | 4.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 37        | 3.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 2.54%   |
| Intel Wireless 7260                                            | 24        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 2.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22        | 2.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 20        | 2.03%   |
| Intel Wireless 8260                                            | 20        | 2.03%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 19        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 19        | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 1.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 1.83%   |
| Intel Wireless 7265                                            | 15        | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 1.12%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 11        | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 11        | 1.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 10        | 1.02%   |
| Realtek 802.11ac NIC                                           | 9         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 0.91%   |
| Intel Wireless-AC 9260                                         | 9         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 0.91%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 9         | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 9         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 8         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 0.81%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 8         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6         | 0.61%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 6         | 0.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 597       | 50.9%   |
| Intel                     | 389       | 33.16%  |
| Qualcomm Atheros          | 35        | 2.98%   |
| Broadcom                  | 32        | 2.73%   |
| ASIX Electronics          | 23        | 1.96%   |
| Nvidia                    | 15        | 1.28%   |
| Marvell Technology Group  | 11        | 0.94%   |
| Aquantia                  | 9         | 0.77%   |
| Xiaomi                    | 5         | 0.43%   |
| Qualcomm                  | 5         | 0.43%   |
| Mellanox Technologies     | 4         | 0.34%   |
| Lenovo                    | 4         | 0.34%   |
| Google                    | 4         | 0.34%   |
| DisplayLink               | 4         | 0.34%   |
| Samsung Electronics       | 3         | 0.26%   |
| Microsoft                 | 2         | 0.17%   |
| Microchip Technology      | 2         | 0.17%   |
| MediaTek                  | 2         | 0.17%   |
| JMicron Technology        | 2         | 0.17%   |
| Emulex                    | 2         | 0.17%   |
| Dell                      | 2         | 0.17%   |
| Broadcom Limited          | 2         | 0.17%   |
| American Megatrends       | 2         | 0.17%   |
| 3Com                      | 2         | 0.17%   |
| TP-Link                   | 1         | 0.09%   |
| SysKonnect                | 1         | 0.09%   |
| Spreadtrum Communications | 1         | 0.09%   |
| Solarflare Communications | 1         | 0.09%   |
| OPPO Electronics          | 1         | 0.09%   |
| Motorola PCS              | 1         | 0.09%   |
| Loongson Technology       | 1         | 0.09%   |
| Insyde Software           | 1         | 0.09%   |
| IBM                       | 1         | 0.09%   |
| Huawei Technologies       | 1         | 0.09%   |
| Hewlett-Packard           | 1         | 0.09%   |
| D-Link System             | 1         | 0.09%   |
| Attansic Technology       | 1         | 0.09%   |
| Apple                     | 1         | 0.09%   |
| Accton Technology         | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 445       | 37.02%  |
| Intel Ethernet Connection (13) I219-V                               | 108       | 8.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 49        | 4.08%   |
| Realtek RTL8125 2.5GbE Controller                                   | 48        | 3.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 38        | 3.16%   |
| Intel Ethernet Controller I225-V                                    | 29        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 25        | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                               | 21        | 1.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 20        | 1.66%   |
| ASIX AX88179 Gigabit Ethernet                                       | 20        | 1.66%   |
| Intel I211 Gigabit Network Connection                               | 19        | 1.58%   |
| Intel Ethernet Connection I217-LM                                   | 17        | 1.41%   |
| Intel Ethernet Connection (2) I219-V                                | 12        | 1%      |
| Intel 82566DM Gigabit Network Connection                            | 12        | 1%      |
| Intel Ethernet Connection (4) I219-V                                | 10        | 0.83%   |
| Intel Ethernet Connection I219-LM                                   | 9         | 0.75%   |
| Intel I210 Gigabit Network Connection                               | 8         | 0.67%   |
| Intel Ethernet Connection I217-V                                    | 8         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                               | 8         | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                               | 7         | 0.58%   |
| Intel Ethernet Connection I218-LM                                   | 6         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                               | 6         | 0.5%    |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 6         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 5         | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 5         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 5         | 0.42%   |
| Intel I350 Gigabit Network Connection                               | 5         | 0.42%   |
| Intel Ethernet Controller I226-V                                    | 5         | 0.42%   |
| Intel Ethernet Connection (16) I219-V                               | 5         | 0.42%   |
| Intel 82579V Gigabit Network Connection                             | 5         | 0.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                   | 5         | 0.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                    | 5         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 4         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 4         | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 4         | 0.33%   |
| Nvidia MCP79 Ethernet                                               | 4         | 0.33%   |
| Nvidia MCP61 Ethernet                                               | 4         | 0.33%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 4         | 0.33%   |
| Intel Ethernet Connection I219-V                                    | 4         | 0.33%   |
| Intel Ethernet Connection (7) I219-V                                | 4         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1074      | 53.17%  |
| WiFi     | 927       | 45.89%  |
| Modem    | 15        | 0.74%   |
| Unknown  | 4         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 662       | 50.81%  |
| Ethernet | 641       | 49.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 658       | 51.81%  |
| 1     | 534       | 42.05%  |
| 3     | 32        | 2.52%   |
| 0     | 26        | 2.05%   |
| 4     | 14        | 1.1%    |
| 6     | 4         | 0.31%   |
| 9     | 1         | 0.08%   |
| 7     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 973       | 76.37%  |
| Yes  | 301       | 23.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 501       | 60.51%  |
| Realtek Semiconductor           | 85        | 10.27%  |
| Qualcomm Atheros Communications | 36        | 4.35%   |
| Foxconn / Hon Hai               | 31        | 3.74%   |
| Apple                           | 27        | 3.26%   |
| IMC Networks                    | 24        | 2.9%    |
| Broadcom                        | 22        | 2.66%   |
| Lite-On Technology              | 20        | 2.42%   |
| Cambridge Silicon Radio         | 20        | 2.42%   |
| MediaTek                        | 13        | 1.57%   |
| ASUSTek Computer                | 10        | 1.21%   |
| Realtek                         | 9         | 1.09%   |
| Dell                            | 5         | 0.6%    |
| TP-Link                         | 4         | 0.48%   |
| Hewlett-Packard                 | 4         | 0.48%   |
| Toshiba                         | 3         | 0.36%   |
| USI                             | 2         | 0.24%   |
| Micro Star International        | 2         | 0.24%   |
| Marvell Semiconductor           | 2         | 0.24%   |
| Ralink Technology               | 1         | 0.12%   |
| Integrated System Solution      | 1         | 0.12%   |
| HTC (High Tech Computer)        | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Dynex                           | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 174       | 21.01%  |
| Intel Bluetooth wireless interface                  | 113       | 13.65%  |
| Realtek Bluetooth Radio                             | 75        | 9.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 74        | 8.94%   |
| Intel Bluetooth Device                              | 54        | 6.52%   |
| Intel AX200 Bluetooth                               | 50        | 6.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 2.29%   |
| Intel AX210 Bluetooth                               | 19        | 2.29%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.69%   |
| MediaTek Wireless_Device                            | 13        | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 1.57%   |
| Apple Bluetooth Host Controller                     | 12        | 1.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 1.21%   |
| IMC Networks Wireless_Device                        | 10        | 1.21%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.21%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 0.97%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 0.97%   |
| Lite-On Wireless_Device                             | 7         | 0.85%   |
| Lite-On Bluetooth Device                            | 7         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 0.72%   |
| TP-Link UB5A Adapter                                | 4         | 0.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.48%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.36%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.36%   |
| USI Bluetooth Device                                | 2         | 0.24%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.24%   |
| IMC Networks Bluetooth Device                       | 2         | 0.24%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.24%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.24%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.24%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 890       | 54.17%  |
| AMD                                          | 346       | 21.06%  |
| Nvidia                                       | 231       | 14.06%  |
| C-Media Electronics                          | 29        | 1.77%   |
| Logitech                                     | 16        | 0.97%   |
| Realtek Semiconductor                        | 10        | 0.61%   |
| Lenovo                                       | 10        | 0.61%   |
| Creative Labs                                | 8         | 0.49%   |
| ASUSTek Computer                             | 7         | 0.43%   |
| Micro Star International                     | 6         | 0.37%   |
| Generalplus Technology                       | 6         | 0.37%   |
| JMTek                                        | 5         | 0.3%    |
| Hewlett-Packard                              | 5         | 0.3%    |
| GN Netcom                                    | 5         | 0.3%    |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.24%   |
| Texas Instruments                            | 4         | 0.24%   |
| Kingston Technology                          | 4         | 0.24%   |
| Focusrite-Novation                           | 4         | 0.24%   |
| Yamaha                                       | 3         | 0.18%   |
| SteelSeries ApS                              | 3         | 0.18%   |
| Plantronics                                  | 3         | 0.18%   |
| Creative Technology                          | 3         | 0.18%   |
| Blue Microphones                             | 3         | 0.18%   |
| Samson Technologies                          | 2         | 0.12%   |
| Razer USA                                    | 2         | 0.12%   |
| Microsoft                                    | 2         | 0.12%   |
| Jieli Technology                             | 2         | 0.12%   |
| Corsair                                      | 2         | 0.12%   |
| CMX Systems                                  | 2         | 0.12%   |
| Audient                                      | 2         | 0.12%   |
| Zhaoxin                                      | 1         | 0.06%   |
| VIA Technologies                             | 1         | 0.06%   |
| USB MICROPHONE                               | 1         | 0.06%   |
| Tdlasunnic                                   | 1         | 0.06%   |
| Schiit Audio                                 | 1         | 0.06%   |
| Phoenix Audio Technologies                   | 1         | 0.06%   |
| OPPO Electronics                             | 1         | 0.06%   |
| Loongson Technology                          | 1         | 0.06%   |
| Global Sun Technology                        | 1         | 0.06%   |
| Giga-Byte Technology                         | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 185       | 9.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 160       | 8.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 96        | 4.82%   |
| Intel Sunrise Point-LP HD Audio                                            | 80        | 4.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 72        | 3.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 54        | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 52        | 2.61%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 50        | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 45        | 2.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 43        | 2.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 39        | 1.96%   |
| Intel 200 Series PCH HD Audio                                              | 34        | 1.71%   |
| Intel Comet Lake PCH cAVS                                                  | 31        | 1.56%   |
| Nvidia GF108 High Definition Audio Controller                              | 30        | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 28        | 1.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 28        | 1.41%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 28        | 1.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 27        | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 25        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 25        | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 23        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 22        | 1.1%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21        | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 20        | 1%      |
| Intel 8 Series HD Audio Controller                                         | 20        | 1%      |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20        | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 17        | 0.85%   |
| Intel Broadwell-U Audio Controller                                         | 17        | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 0.75%   |
| Intel Alder Lake-S HD Audio Controller                                     | 15        | 0.75%   |
| AMD FCH Azalia Controller                                                  | 15        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                              | 14        | 0.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 0.7%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 14        | 0.7%    |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 13        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 314       | 27.64%  |
| SK hynix                                | 170       | 14.96%  |
| Kingston                                | 127       | 11.18%  |
| Crucial                                 | 108       | 9.51%   |
| Micron Technology                       | 101       | 8.89%   |
| Unknown                                 | 89        | 7.83%   |
| Corsair                                 | 33        | 2.9%    |
| G.Skill                                 | 28        | 2.46%   |
| A-DATA Technology                       | 24        | 2.11%   |
| Hikvision                               | 18        | 1.58%   |
| Elpida                                  | 16        | 1.41%   |
| Unknown                                 | 13        | 1.14%   |
| Patriot                                 | 10        | 0.88%   |
| Unknown (ABCD)                          | 9         | 0.79%   |
| Ramaxel Technology                      | 9         | 0.79%   |
| Micro Memory Bank                       | 8         | 0.7%    |
| Nanya Technology                        | 7         | 0.62%   |
| Team                                    | 6         | 0.53%   |
| Smart                                   | 5         | 0.44%   |
| ff                                      | 5         | 0.44%   |
| 4ea5                                    | 5         | 0.44%   |
| Transcend                               | 3         | 0.26%   |
| ASint Technology                        | 3         | 0.26%   |
| AMD                                     | 3         | 0.26%   |
| Toshiba                                 | 2         | 0.18%   |
| Silicon Power Computer & Communications | 2         | 0.18%   |
| V-Color                                 | 1         | 0.09%   |
| Unknown (768A)                          | 1         | 0.09%   |
| Unknown (0x7FFF)                        | 1         | 0.09%   |
| Unknown (0x198)                         | 1         | 0.09%   |
| Unknown (0x0E9D)                        | 1         | 0.09%   |
| Unknown (06CE)                          | 1         | 0.09%   |
| Shenzhen Mic                            | 1         | 0.09%   |
| PKI                                     | 1         | 0.09%   |
| Patriot Memory (PDP Systems)            | 1         | 0.09%   |
| Neo Forza                               | 1         | 0.09%   |
| KLEVV                                   | 1         | 0.09%   |
| GeIL                                    | 1         | 0.09%   |
| Asgard                                  | 1         | 0.09%   |
| ad8a                                    | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                            | 106       | 8.8%    |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s                          | 29        | 2.41%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s                          | 18        | 1.5%    |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s                            | 15        | 1.25%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                            | 14        | 1.16%   |
| Unknown                                                                          | 13        | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                           | 10        | 0.83%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                              | 10        | 0.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                            | 9         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                            | 8         | 0.66%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                             | 8         | 0.66%   |
| Micro Memory Bank RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 2GB DIMM DDR2 667MT/s | 8         | 0.66%   |
| Unknown RAM Module 2GB DIMM SDRAM                                                | 7         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s                 | 7         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                           | 7         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                            | 6         | 0.5%    |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                                   | 6         | 0.5%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                            | 6         | 0.5%    |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s                           | 6         | 0.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                                             | 5         | 0.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                           | 5         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                           | 5         | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                            | 5         | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                            | 5         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                            | 5         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                            | 5         | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                      | 5         | 0.42%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3266MT/s                           | 5         | 0.42%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s                          | 5         | 0.42%   |
| Unknown RAM Module 4GB SODIMM DDR3                                               | 4         | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                             | 4         | 0.33%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                             | 4         | 0.33%   |
| Unknown RAM Module 1GB DIMM SDRAM                                                | 4         | 0.33%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                                     | 4         | 0.33%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                                    | 4         | 0.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                           | 4         | 0.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s                     | 4         | 0.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                            | 4         | 0.33%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                            | 4         | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                             | 4         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 570       | 56.27%  |
| DDR3    | 206       | 20.34%  |
| DDR5    | 47        | 4.64%   |
| LPDDR4  | 44        | 4.34%   |
| DDR2    | 41        | 4.05%   |
| Unknown | 29        | 2.86%   |
| SDRAM   | 26        | 2.57%   |
| LPDDR3  | 25        | 2.47%   |
| LPDDR5  | 16        | 1.58%   |
| DDR     | 8         | 0.79%   |
| DRAM    | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 564       | 55.29%  |
| DIMM         | 357       | 35%     |
| Row Of Chips | 83        | 8.14%   |
| Unknown      | 9         | 0.88%   |
| Chip         | 4         | 0.39%   |
| RIMM         | 2         | 0.2%    |
| FB-DIMM      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 488       | 44.89%  |
| 4096  | 217       | 19.96%  |
| 16384 | 159       | 14.63%  |
| 2048  | 113       | 10.4%   |
| 32768 | 57        | 5.24%   |
| 1024  | 42        | 3.86%   |
| 512   | 8         | 0.74%   |
| 65536 | 1         | 0.09%   |
| 256   | 1         | 0.09%   |
| 64    | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 280       | 26.12%  |
| 2667    | 152       | 14.18%  |
| 1600    | 119       | 11.1%   |
| 2400    | 67        | 6.25%   |
| 2133    | 56        | 5.22%   |
| 1333    | 43        | 4.01%   |
| 667     | 28        | 2.61%   |
| 4800    | 27        | 2.52%   |
| 3600    | 27        | 2.52%   |
| Unknown | 27        | 2.52%   |
| 1334    | 22        | 2.05%   |
| 4267    | 21        | 1.96%   |
| 800     | 21        | 1.96%   |
| 6400    | 18        | 1.68%   |
| 1866    | 18        | 1.68%   |
| 1867    | 17        | 1.59%   |
| 1067    | 14        | 1.31%   |
| 1066    | 12        | 1.12%   |
| 4333    | 10        | 0.93%   |
| 3266    | 10        | 0.93%   |
| 2666    | 8         | 0.75%   |
| 6000    | 6         | 0.56%   |
| 5200    | 5         | 0.47%   |
| 3000    | 5         | 0.47%   |
| 5600    | 4         | 0.37%   |
| 4199    | 3         | 0.28%   |
| 3933    | 3         | 0.28%   |
| 3733    | 3         | 0.28%   |
| 3400    | 3         | 0.28%   |
| 2866    | 3         | 0.28%   |
| 8400    | 2         | 0.19%   |
| 4266    | 2         | 0.19%   |
| 3800    | 2         | 0.19%   |
| 3534    | 2         | 0.19%   |
| 3334    | 2         | 0.19%   |
| 2933    | 2         | 0.19%   |
| 2800    | 2         | 0.19%   |
| 2048    | 2         | 0.19%   |
| 1800    | 2         | 0.19%   |
| 1639    | 2         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 7         | 30.43%  |
| Canon               | 5         | 21.74%  |
| Hewlett-Packard     | 4         | 17.39%  |
| Samsung Electronics | 2         | 8.7%    |
| Dymo-CoStar         | 2         | 8.7%    |
| Zebra               | 1         | 4.35%   |
| Seiko Epson         | 1         | 4.35%   |
| Pantum              | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Canon MF3010                           | 2         | 8.7%    |
| Zebra Printer                          | 1         | 4.35%   |
| Seiko Epson ET-4850 Series             | 1         | 4.35%   |
| Samsung M2070 Series                   | 1         | 4.35%   |
| Samsung M2020 Series                   | 1         | 4.35%   |
| Pantum P2500W series                   | 1         | 4.35%   |
| HP Officejet 4500 G510a-f              | 1         | 4.35%   |
| HP LaserJet P2035                      | 1         | 4.35%   |
| HP LaserJet 1022                       | 1         | 4.35%   |
| HP ENVY 5540 series                    | 1         | 4.35%   |
| Dymo-CoStar DYMO LabelWriter DUO       | 1         | 4.35%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 4.35%   |
| Canon PIXMA iP4300 Printer             | 1         | 4.35%   |
| Canon MF4010 series                    | 1         | 4.35%   |
| Canon LiDE 400                         | 1         | 4.35%   |
| Brother MFC-L2710DW series             | 1         | 4.35%   |
| Brother HL-L2390DW                     | 1         | 4.35%   |
| Brother HL-3040CN series               | 1         | 4.35%   |
| Brother HL-1110 series                 | 1         | 4.35%   |
| Brother DCP-L8450CDW                   | 1         | 4.35%   |
| Brother DCP-7030                       | 1         | 4.35%   |
| Brother DCP-7010                       | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 37.5%   |
| Canon           | 3         | 37.5%   |
| Plustek         | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]       | 1         | 12.5%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1         | 12.5%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]     | 1         | 12.5%   |
| Plustek 1200dpi USB Scanner                       | 1         | 12.5%   |
| HP ScanJet 82x0C                                  | 1         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 12.5%   |
| Canon CanoScan LiDE 210                           | 1         | 12.5%   |
| Canon CanoScan LiDE 110                           | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 210       | 25.8%   |
| Bison Electronics                      | 161       | 19.78%  |
| IMC Networks                           | 71        | 8.72%   |
| Microdia                               | 46        | 5.65%   |
| Quanta                                 | 42        | 5.16%   |
| Realtek Semiconductor                  | 40        | 4.91%   |
| Logitech                               | 39        | 4.79%   |
| Sunplus Innovation Technology          | 25        | 3.07%   |
| Luxvisions Innotech Limited            | 25        | 3.07%   |
| Apple                                  | 18        | 2.21%   |
| Lite-On Technology                     | 15        | 1.84%   |
| Syntek                                 | 14        | 1.72%   |
| Microsoft                              | 14        | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 1.6%    |
| Suyin                                  | 10        | 1.23%   |
| Acer                                   | 8         | 0.98%   |
| Silicon Motion                         | 7         | 0.86%   |
| Sonix Technology                       | 5         | 0.61%   |
| Lenovo                                 | 5         | 0.61%   |
| Generalplus Technology                 | 5         | 0.61%   |
| Ricoh                                  | 4         | 0.49%   |
| Jieli Technology                       | 4         | 0.49%   |
| SunplusIT                              | 3         | 0.37%   |
| icSpring                               | 3         | 0.37%   |
| Alcor Micro                            | 3         | 0.37%   |
| Z-Star Microelectronics                | 2         | 0.25%   |
| Samsung Electronics                    | 2         | 0.25%   |
| KYE Systems (Mouse Systems)            | 2         | 0.25%   |
| ALi                                    | 2         | 0.25%   |
| ValueHD                                | 1         | 0.12%   |
| Tobii Technology AB                    | 1         | 0.12%   |
| Sony Electronics                       | 1         | 0.12%   |
| SN0002                                 | 1         | 0.12%   |
| Ruision                                | 1         | 0.12%   |
| Primax Electronics                     | 1         | 0.12%   |
| OmniVision Technologies                | 1         | 0.12%   |
| Magic Control Technology               | 1         | 0.12%   |
| Importek                               | 1         | 0.12%   |
| Image Processor                        | 1         | 0.12%   |
| HRY                                    | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Bison Integrated Camera                             | 77        | 9.02%   |
| Chicony Integrated Camera                           | 76        | 8.9%    |
| Bison Integrated 5M Camera                          | 61        | 7.14%   |
| Chicony Integrated 5M Camera                        | 39        | 4.57%   |
| Bison BisonCam, NB Pro                              | 29        | 3.4%    |
| Microdia Integrated_Webcam_HD                       | 27        | 3.16%   |
| IMC Networks Integrated Camera                      | 22        | 2.58%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 20        | 2.34%   |
| Realtek Integrated_Webcam_HD                        | 15        | 1.76%   |
| Chicony HP HD Camera                                | 13        | 1.52%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 1.41%   |
| Syntek Integrated Camera                            | 10        | 1.17%   |
| Logitech Webcam C270                                | 10        | 1.17%   |
| Logitech HD Pro Webcam C920                         | 10        | 1.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 10        | 1.17%   |
| Chicony HD Webcam                                   | 10        | 1.17%   |
| Chicony HD User Facing                              | 10        | 1.17%   |
| Quanta HD User Facing                               | 9         | 1.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 7         | 0.82%   |
| Lite-On Integrated Camera                           | 7         | 0.82%   |
| IMC Networks ov9734_azurewave_camera                | 6         | 0.7%    |
| Quanta HP TrueVision HD Camera                      | 5         | 0.59%   |
| Microsoft LifeCam HD-3000                           | 5         | 0.59%   |
| Chicony USB2.0 Camera                               | 5         | 0.59%   |
| Chicony Integrated Camera (1280x720@30)             | 5         | 0.59%   |
| Bison Integrated RGB Camera                         | 5         | 0.59%   |
| Apple FaceTime HD Camera (Built-in)                 | 5         | 0.59%   |
| Apple Built-in iSight                               | 5         | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.47%   |
| Quanta ov9734_techfront_camera                      | 4         | 0.47%   |
| Quanta HP HD Camera                                 | 4         | 0.47%   |
| Quanta ACER HD User Facing                          | 4         | 0.47%   |
| Luxvisions Innotech Limited Integrated Camera       | 4         | 0.47%   |
| Luxvisions Innotech Limited HP HD Camera            | 4         | 0.47%   |
| Logitech C922 Pro Stream Webcam                     | 4         | 0.47%   |
| Jieli USB PHY 2.0                                   | 4         | 0.47%   |
| Generalplus CAMERA - UVC                            | 4         | 0.47%   |
| Chicony USB 2.0 Camera                              | 4         | 0.47%   |
| Chicony HP Wide Vision HD Camera                    | 4         | 0.47%   |
| Chicony HP TrueVision HD Camera                     | 4         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 145       | 63.6%   |
| Validity Sensors                   | 39        | 17.11%  |
| Shenzhen Goodix Technology         | 21        | 9.21%   |
| Elan Microelectronics              | 6         | 2.63%   |
| Upek                               | 5         | 2.19%   |
| STMicroelectronics                 | 3         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.32%   |
| LighTuning Technology              | 2         | 0.88%   |
| Focal-systems.Corp                 | 2         | 0.88%   |
| AuthenTec                          | 2         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 118       | 51.75%  |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 7.46%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 2.19%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 1.75%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.32%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.32%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.88%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.88%   |
| Synaptics WBDI                                                             | 2         | 0.88%   |
| Synaptics UWP WBDI                                                         | 2         | 0.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.88%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.88%   |
| Unknown                                                                    | 2         | 0.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.44%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.44%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.44%   |
| AuthenTec AES1600                                                          | 1         | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 19        | 38.78%  |
| Alcor Micro           | 19        | 38.78%  |
| Lenovo                | 3         | 6.12%   |
| Upek                  | 2         | 4.08%   |
| Realtek Semiconductor | 2         | 4.08%   |
| Yubico.com            | 1         | 2.04%   |
| SCM Microsystems      | 1         | 2.04%   |
| O2 Micro              | 1         | 2.04%   |
| Cherry                | 1         | 2.04%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 36.73%  |
| Broadcom 58200                                                               | 7         | 14.29%  |
| Broadcom 5880                                                                | 6         | 12.24%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 8.16%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.12%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 4.08%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 4.08%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.04%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 2.04%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.04%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 2.04%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 656       | 51.33%  |
| 1     | 530       | 41.47%  |
| 2     | 76        | 5.95%   |
| 3     | 11        | 0.86%   |
| 5     | 2         | 0.16%   |
| 4     | 2         | 0.16%   |
| 6     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 248       | 36.31%  |
| Fingerprint reader       | 226       | 33.09%  |
| Net/wireless             | 46        | 6.73%   |
| Multimedia controller    | 40        | 5.86%   |
| Chipcard                 | 40        | 5.86%   |
| Camera                   | 32        | 4.69%   |
| Unassigned class         | 12        | 1.76%   |
| Communication controller | 12        | 1.76%   |
| Bluetooth                | 8         | 1.17%   |
| Sound                    | 6         | 0.88%   |
| Network                  | 3         | 0.44%   |
| Wireless                 | 2         | 0.29%   |
| Storage/raid             | 2         | 0.29%   |
| Storage                  | 2         | 0.29%   |
| Card reader              | 2         | 0.29%   |
| Storage/nvme             | 1         | 0.15%   |
| Net/ethernet             | 1         | 0.15%   |

