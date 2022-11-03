Linux - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [AlmaLinux](/Dist/AlmaLinux), [Alpine](/Dist/Alpine), [ALT_Linux](/Dist/ALT_Linux), [antiX](/Dist/antiX), [Artix](/Dist/Artix), [Chrome_OS](/Dist/Chrome_OS), [Clear_Linux](/Dist/Clear_Linux), [Deepin](/Dist/Deepin), [Devuan](/Dist/Devuan), [EndeavourOS](/Dist/EndeavourOS), [Garuda_Linux](/Dist/Garuda_Linux), [GNOME_OS](/Dist/GNOME_OS), [Kaisen](/Dist/Kaisen), [Mageia](/Dist/Mageia), [Makulu](/Dist/Makulu), [NixOS](/Dist/NixOS), [Nobara](/Dist/Nobara), [Oracle_Linux](/Dist/Oracle_Linux), [Pardus](/Dist/Pardus), [PureOS](/Dist/PureOS), [Q4OS](/Dist/Q4OS), [Reborn_OS](/Dist/Reborn_OS), [Rocky_Linux](/Dist/Rocky_Linux), [Sparky](/Dist/Sparky), [Void_Linux](/Dist/Void_Linux), [Xero](/Dist/Xero).

This report is for real hardware. Report for virtual hardware: [TestCoverage_VE](https://github.com/linuxhw/TestCoverage_VE)

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

Total: 259547

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [760c526784](https://linux-hardware.org/?probe=760c526784) | Nov 02, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [d4f08c71a6](https://linux-hardware.org/?probe=d4f08c71a6) | Nov 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| HP            | 3397                        | Desktop     | [24eb596bce](https://linux-hardware.org/?probe=24eb596bce) | Nov 02, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [fba864b37c](https://linux-hardware.org/?probe=fba864b37c) | Nov 02, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [0a598dc332](https://linux-hardware.org/?probe=0a598dc332) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [695b3d82a7](https://linux-hardware.org/?probe=695b3d82a7) | Nov 02, 2022 |
| Shenzhen a... | AC1-DP                      | Desktop     | [754335ffe9](https://linux-hardware.org/?probe=754335ffe9) | Nov 02, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [db83c146a6](https://linux-hardware.org/?probe=db83c146a6) | Nov 02, 2022 |
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| Intel         | NUC8i7HNB J68197-503        | Mini pc     | [6d946007b8](https://linux-hardware.org/?probe=6d946007b8) | Nov 02, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| HP            | 18E7                        | Desktop     | [c0d5c58895](https://linux-hardware.org/?probe=c0d5c58895) | Nov 02, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [9b9e55c471](https://linux-hardware.org/?probe=9b9e55c471) | Nov 02, 2022 |
| MSI           | MS-7392                     | Desktop     | [d453f89064](https://linux-hardware.org/?probe=d453f89064) | Nov 02, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [565ad502cc](https://linux-hardware.org/?probe=565ad502cc) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [23a62c3509](https://linux-hardware.org/?probe=23a62c3509) | Nov 02, 2022 |
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [2ece2f7351](https://linux-hardware.org/?probe=2ece2f7351) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [5d9743e91d](https://linux-hardware.org/?probe=5d9743e91d) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [7a421ed810](https://linux-hardware.org/?probe=7a421ed810) | Nov 02, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [ccaedd7155](https://linux-hardware.org/?probe=ccaedd7155) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [28d7daff10](https://linux-hardware.org/?probe=28d7daff10) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [d82227846b](https://linux-hardware.org/?probe=d82227846b) | Nov 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [a2af2980ad](https://linux-hardware.org/?probe=a2af2980ad) | Nov 02, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| ASUSTek       | H81T                        | Desktop     | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a3b1926b7e](https://linux-hardware.org/?probe=a3b1926b7e) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | Notebook    | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [d34ccf5e7a](https://linux-hardware.org/?probe=d34ccf5e7a) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [eb06593b9e](https://linux-hardware.org/?probe=eb06593b9e) | Nov 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [5da1d76cd5](https://linux-hardware.org/?probe=5da1d76cd5) | Nov 02, 2022 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [95ddb63cb1](https://linux-hardware.org/?probe=95ddb63cb1) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| GPD           | P3 MAX                      | Notebook    | [8b198da775](https://linux-hardware.org/?probe=8b198da775) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| Samsung       | 550XED                      | Notebook    | [6992db47be](https://linux-hardware.org/?probe=6992db47be) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [dd24c26ffa](https://linux-hardware.org/?probe=dd24c26ffa) | Nov 02, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [710ab678b2](https://linux-hardware.org/?probe=710ab678b2) | Nov 02, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| HP            | 1589                        | Desktop     | [81a347a6a7](https://linux-hardware.org/?probe=81a347a6a7) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [519fa92199](https://linux-hardware.org/?probe=519fa92199) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| HP            | 18E5                        | Desktop     | [3df38ade7e](https://linux-hardware.org/?probe=3df38ade7e) | Nov 02, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d8b066edcd](https://linux-hardware.org/?probe=d8b066edcd) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| GPD           | P3 MAX                      | Notebook    | [aea8f8bb50](https://linux-hardware.org/?probe=aea8f8bb50) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| Acer          | Aspire E5-522               | Notebook    | [32f73c64a6](https://linux-hardware.org/?probe=32f73c64a6) | Nov 02, 2022 |
| ASUSTek       | 1215B                       | Notebook    | [21694405a9](https://linux-hardware.org/?probe=21694405a9) | Nov 02, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [dbacfbd3b0](https://linux-hardware.org/?probe=dbacfbd3b0) | Nov 02, 2022 |
| Dell          | Latitude 5580               | Notebook    | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Acer          | Aspire E5-522               | Notebook    | [412b8c701e](https://linux-hardware.org/?probe=412b8c701e) | Nov 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| HP            | Laptop                      | Notebook    | [e1cd3de91a](https://linux-hardware.org/?probe=e1cd3de91a) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| Dell          | Precision 7550              | Notebook    | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [cdd5c3cca0](https://linux-hardware.org/?probe=cdd5c3cca0) | Nov 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b39c12a9a4](https://linux-hardware.org/?probe=b39c12a9a4) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [7d43f3c00b](https://linux-hardware.org/?probe=7d43f3c00b) | Nov 02, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [a0029fb797](https://linux-hardware.org/?probe=a0029fb797) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [732eaeede7](https://linux-hardware.org/?probe=732eaeede7) | Nov 02, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c693004e08](https://linux-hardware.org/?probe=c693004e08) | Nov 02, 2022 |
| Lenovo        | 361A SDK0K17763 WIN         | Desktop     | [5d34d86be3](https://linux-hardware.org/?probe=5d34d86be3) | Nov 02, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [fde67e1423](https://linux-hardware.org/?probe=fde67e1423) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [0666d8a154](https://linux-hardware.org/?probe=0666d8a154) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e4a7690a77](https://linux-hardware.org/?probe=e4a7690a77) | Nov 02, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [95e2a1e7d9](https://linux-hardware.org/?probe=95e2a1e7d9) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [706fb22c95](https://linux-hardware.org/?probe=706fb22c95) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [4a158afdfd](https://linux-hardware.org/?probe=4a158afdfd) | Nov 02, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b3613b84ad](https://linux-hardware.org/?probe=b3613b84ad) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | Desktop     | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| ASRock        | Q1900B-ITX                  | Desktop     | [6305a98777](https://linux-hardware.org/?probe=6305a98777) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| Dell          | Latitude 5420               | Notebook    | [679fbcb14f](https://linux-hardware.org/?probe=679fbcb14f) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [452ec1a1ee](https://linux-hardware.org/?probe=452ec1a1ee) | Nov 02, 2022 |
| Lenovo        | G560 0679                   | Notebook    | [c97e8f3436](https://linux-hardware.org/?probe=c97e8f3436) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [da6ecef3a7](https://linux-hardware.org/?probe=da6ecef3a7) | Nov 02, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| HP            | 18E5                        | Desktop     | [8204df7795](https://linux-hardware.org/?probe=8204df7795) | Nov 02, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | Desktop     | [f8708425a1](https://linux-hardware.org/?probe=f8708425a1) | Nov 02, 2022 |
| HP            | 8054                        | Desktop     | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [2c7d7e2c8a](https://linux-hardware.org/?probe=2c7d7e2c8a) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [1fb0a79791](https://linux-hardware.org/?probe=1fb0a79791) | Nov 02, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [41707b16d1](https://linux-hardware.org/?probe=41707b16d1) | Nov 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [bc4f9a5a35](https://linux-hardware.org/?probe=bc4f9a5a35) | Nov 02, 2022 |
| ASRock        | N68C-GS UCC                 | Desktop     | [9430ecf81c](https://linux-hardware.org/?probe=9430ecf81c) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [881cd60670](https://linux-hardware.org/?probe=881cd60670) | Nov 02, 2022 |
| Notebook      | P65xHP                      | Notebook    | [68d40fd2c7](https://linux-hardware.org/?probe=68d40fd2c7) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| HP            | G42                         | Notebook    | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [f6295954bc](https://linux-hardware.org/?probe=f6295954bc) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [3773260366](https://linux-hardware.org/?probe=3773260366) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Lenovo        | ThinkCentre A57 970274G     | Desktop     | [809e137f17](https://linux-hardware.org/?probe=809e137f17) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | Notebook    | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Dell          | 0TWFTR A02                  | All in one  | [21b78069dd](https://linux-hardware.org/?probe=21b78069dd) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Dell          | Latitude E6420              | Notebook    | [032920f109](https://linux-hardware.org/?probe=032920f109) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [0b91ee456b](https://linux-hardware.org/?probe=0b91ee456b) | Nov 02, 2022 |
| Jumper        | EZbook                      | Notebook    | [08ec434199](https://linux-hardware.org/?probe=08ec434199) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [93884d7e71](https://linux-hardware.org/?probe=93884d7e71) | Nov 02, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [075f628a80](https://linux-hardware.org/?probe=075f628a80) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [13e280e72f](https://linux-hardware.org/?probe=13e280e72f) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [46874cc0a1](https://linux-hardware.org/?probe=46874cc0a1) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [39cb4cb083](https://linux-hardware.org/?probe=39cb4cb083) | Nov 02, 2022 |
| HP            | Pavilion dv8                | Notebook    | [21af5313f0](https://linux-hardware.org/?probe=21af5313f0) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [40cedc7d2c](https://linux-hardware.org/?probe=40cedc7d2c) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| Cube          | i18-BL                      | Notebook    | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47c34f9269](https://linux-hardware.org/?probe=47c34f9269) | Nov 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [454939df34](https://linux-hardware.org/?probe=454939df34) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| Samsung       | 950XED                      | Notebook    | [821bc59c17](https://linux-hardware.org/?probe=821bc59c17) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [09c2704bb0](https://linux-hardware.org/?probe=09c2704bb0) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HP            | 625                         | Notebook    | [830c5c0d14](https://linux-hardware.org/?probe=830c5c0d14) | Nov 02, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [1a8c44ca83](https://linux-hardware.org/?probe=1a8c44ca83) | Nov 02, 2022 |
| HP            | 625                         | Notebook    | [4c627cab51](https://linux-hardware.org/?probe=4c627cab51) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [e4d29df724](https://linux-hardware.org/?probe=e4d29df724) | Nov 02, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [fe91c11062](https://linux-hardware.org/?probe=fe91c11062) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [b4d63f4835](https://linux-hardware.org/?probe=b4d63f4835) | Nov 02, 2022 |
| Lenovo        | H420                        | Desktop     | [3e3f04d875](https://linux-hardware.org/?probe=3e3f04d875) | Nov 02, 2022 |
| Dell          | Latitude 5591               | Notebook    | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [a9b57edf35](https://linux-hardware.org/?probe=a9b57edf35) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [5786a01590](https://linux-hardware.org/?probe=5786a01590) | Nov 02, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [1421a5a4e9](https://linux-hardware.org/?probe=1421a5a4e9) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Foxconn       | 2A92                        | Desktop     | [0898482b18](https://linux-hardware.org/?probe=0898482b18) | Nov 02, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87ab6daba5](https://linux-hardware.org/?probe=87ab6daba5) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6f89789444](https://linux-hardware.org/?probe=6f89789444) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [59c101934c](https://linux-hardware.org/?probe=59c101934c) | Nov 02, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [5f90d4e478](https://linux-hardware.org/?probe=5f90d4e478) | Nov 02, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fd4d484f61](https://linux-hardware.org/?probe=fd4d484f61) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | Notebook    | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Gigabyte      | EP45-DS4                    | Desktop     | [fa96a26c5a](https://linux-hardware.org/?probe=fa96a26c5a) | Nov 02, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [961f664871](https://linux-hardware.org/?probe=961f664871) | Nov 02, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [dcf7112b3d](https://linux-hardware.org/?probe=dcf7112b3d) | Nov 01, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a333f47ffa](https://linux-hardware.org/?probe=a333f47ffa) | Nov 01, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [f22ebdf694](https://linux-hardware.org/?probe=f22ebdf694) | Nov 01, 2022 |
| HP            | 1905                        | Desktop     | [df0d192970](https://linux-hardware.org/?probe=df0d192970) | Nov 01, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [a27142d25c](https://linux-hardware.org/?probe=a27142d25c) | Nov 01, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [0092b0ddaf](https://linux-hardware.org/?probe=0092b0ddaf) | Nov 01, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [2c63ff26e5](https://linux-hardware.org/?probe=2c63ff26e5) | Nov 01, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [d81e8b3ea2](https://linux-hardware.org/?probe=d81e8b3ea2) | Nov 01, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [dfe5dc3d95](https://linux-hardware.org/?probe=dfe5dc3d95) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [36387e4f11](https://linux-hardware.org/?probe=36387e4f11) | Nov 01, 2022 |
| HP            | ProBook 4530s               | Notebook    | [6490664312](https://linux-hardware.org/?probe=6490664312) | Nov 01, 2022 |
| Phoenix       | POULSBO                     | Desktop     | [177f05205b](https://linux-hardware.org/?probe=177f05205b) | Nov 01, 2022 |
| Dell          | Precision 7530              | Notebook    | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [fda7b35626](https://linux-hardware.org/?probe=fda7b35626) | Nov 01, 2022 |
| MSI           | H61M-P31                    | Desktop     | [819c124b25](https://linux-hardware.org/?probe=819c124b25) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [812c1bc398](https://linux-hardware.org/?probe=812c1bc398) | Nov 01, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [aad6abb936](https://linux-hardware.org/?probe=aad6abb936) | Nov 01, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [9d0e85aed7](https://linux-hardware.org/?probe=9d0e85aed7) | Nov 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [95d825cd94](https://linux-hardware.org/?probe=95d825cd94) | Nov 01, 2022 |
| HP            | ProBook 4530s               | Notebook    | [34682f3bfe](https://linux-hardware.org/?probe=34682f3bfe) | Nov 01, 2022 |
| ASUSTek       | N53Jg                       | Notebook    | [8e4782c668](https://linux-hardware.org/?probe=8e4782c668) | Nov 01, 2022 |
| HP            | 829B                        | All in one  | [23122cba32](https://linux-hardware.org/?probe=23122cba32) | Nov 01, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [b70c0aa20d](https://linux-hardware.org/?probe=b70c0aa20d) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Intel         | H61                         | Desktop     | [326fa40958](https://linux-hardware.org/?probe=326fa40958) | Nov 01, 2022 |
| ASUSTek       | Zephyrus S GX531GS_GX531... | Notebook    | [4823244248](https://linux-hardware.org/?probe=4823244248) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Gigabyte      | P55-UD6                     | Desktop     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [4c80b212c6](https://linux-hardware.org/?probe=4c80b212c6) | Nov 01, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [13bf376807](https://linux-hardware.org/?probe=13bf376807) | Nov 01, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [caffb9ebd7](https://linux-hardware.org/?probe=caffb9ebd7) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Dell          | Precision 5520              | Notebook    | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [4e92800709](https://linux-hardware.org/?probe=4e92800709) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | Notebook    | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| HP            | 3646h                       | Desktop     | [f88c9632b4](https://linux-hardware.org/?probe=f88c9632b4) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6a0d7d5f39](https://linux-hardware.org/?probe=6a0d7d5f39) | Nov 01, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | Desktop     | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [a27d97c026](https://linux-hardware.org/?probe=a27d97c026) | Nov 01, 2022 |
| Lenovo        | ThinkPad L590 20Q7001KIX    | Notebook    | [c8e545615f](https://linux-hardware.org/?probe=c8e545615f) | Nov 01, 2022 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b726668f90](https://linux-hardware.org/?probe=b726668f90) | Nov 01, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8f551aaa52](https://linux-hardware.org/?probe=8f551aaa52) | Nov 01, 2022 |
| Dell          | 06D7TR A02                  | Desktop     | [f8a4053db1](https://linux-hardware.org/?probe=f8a4053db1) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion dv5                | Notebook    | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [4b9071c932](https://linux-hardware.org/?probe=4b9071c932) | Nov 01, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [9704a12e23](https://linux-hardware.org/?probe=9704a12e23) | Nov 01, 2022 |
| Samsung       | 550XED                      | Notebook    | [3b04d21991](https://linux-hardware.org/?probe=3b04d21991) | Nov 01, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [efcbf8a2eb](https://linux-hardware.org/?probe=efcbf8a2eb) | Nov 01, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| HP            | 829E                        | Mini pc     | [f568895fbb](https://linux-hardware.org/?probe=f568895fbb) | Nov 01, 2022 |
| Toshiba       | Satellite L755              | Notebook    | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [64cb818993](https://linux-hardware.org/?probe=64cb818993) | Nov 01, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| ASUSTek       | BM2AD_D510MT_D310MT         | Desktop     | [8f2b0bc926](https://linux-hardware.org/?probe=8f2b0bc926) | Nov 01, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [921b1a7ebf](https://linux-hardware.org/?probe=921b1a7ebf) | Nov 01, 2022 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [4ecb047de3](https://linux-hardware.org/?probe=4ecb047de3) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [fd97cf3ecb](https://linux-hardware.org/?probe=fd97cf3ecb) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [69768228d4](https://linux-hardware.org/?probe=69768228d4) | Nov 01, 2022 |
| Gigabyte      | EP45-DS4                    | Desktop     | [2eb78b1c3d](https://linux-hardware.org/?probe=2eb78b1c3d) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [f0db98f6bb](https://linux-hardware.org/?probe=f0db98f6bb) | Nov 01, 2022 |
| ASUSTek       | CROSSBLADE RANGER           | Desktop     | [5f92247b16](https://linux-hardware.org/?probe=5f92247b16) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [fc832e8881](https://linux-hardware.org/?probe=fc832e8881) | Nov 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Intel         | NUC6i7KYB H90766-410        | Mini pc     | [9c17f472ee](https://linux-hardware.org/?probe=9c17f472ee) | Nov 01, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [115025ee59](https://linux-hardware.org/?probe=115025ee59) | Nov 01, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [74af46599e](https://linux-hardware.org/?probe=74af46599e) | Nov 01, 2022 |
| Dell          | G5 5587                     | Notebook    | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [65c885ec1f](https://linux-hardware.org/?probe=65c885ec1f) | Nov 01, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [cf394ed108](https://linux-hardware.org/?probe=cf394ed108) | Nov 01, 2022 |
| Dell          | 07C0H8 A00                  | Desktop     | [1b2cb018d0](https://linux-hardware.org/?probe=1b2cb018d0) | Nov 01, 2022 |
| Gigabyte      | B550 UD AC                  | Desktop     | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [06ea8207dc](https://linux-hardware.org/?probe=06ea8207dc) | Nov 01, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [245ec71478](https://linux-hardware.org/?probe=245ec71478) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [9efd2724b2](https://linux-hardware.org/?probe=9efd2724b2) | Nov 01, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [50d2f412f0](https://linux-hardware.org/?probe=50d2f412f0) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [f87c0b1010](https://linux-hardware.org/?probe=f87c0b1010) | Nov 01, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [fe23529093](https://linux-hardware.org/?probe=fe23529093) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [5fd845ca54](https://linux-hardware.org/?probe=5fd845ca54) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [b2229c56c4](https://linux-hardware.org/?probe=b2229c56c4) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [990a38ea87](https://linux-hardware.org/?probe=990a38ea87) | Nov 01, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [29a6bce4c0](https://linux-hardware.org/?probe=29a6bce4c0) | Nov 01, 2022 |
| HP            | 8591                        | Desktop     | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [ccf4e200fb](https://linux-hardware.org/?probe=ccf4e200fb) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7603f28400](https://linux-hardware.org/?probe=7603f28400) | Nov 01, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [76052b7756](https://linux-hardware.org/?probe=76052b7756) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [08649bd1e9](https://linux-hardware.org/?probe=08649bd1e9) | Nov 01, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a54d6876b6](https://linux-hardware.org/?probe=a54d6876b6) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [92fccb6716](https://linux-hardware.org/?probe=92fccb6716) | Nov 01, 2022 |
| ASUSTek       | P52F                        | Notebook    | [a83cb4c35d](https://linux-hardware.org/?probe=a83cb4c35d) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [4cdb36db63](https://linux-hardware.org/?probe=4cdb36db63) | Nov 01, 2022 |
| MSI           | H61M-P32/W8                 | Desktop     | [14df9c3c14](https://linux-hardware.org/?probe=14df9c3c14) | Nov 01, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| MSI           | 0A90                        | Desktop     | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| HP            | 339A                        | Desktop     | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a14fa00a56](https://linux-hardware.org/?probe=a14fa00a56) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bfa1db2eb1](https://linux-hardware.org/?probe=bfa1db2eb1) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| OEM           | H310MD4                     | Desktop     | [947bf0d86f](https://linux-hardware.org/?probe=947bf0d86f) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | Notebook    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| ASUSTek       | X501A                       | Notebook    | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| MS            | MPGIO                       | Notebook    | [4fc8637bf3](https://linux-hardware.org/?probe=4fc8637bf3) | Nov 01, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bbbf28359b](https://linux-hardware.org/?probe=bbbf28359b) | Nov 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [321eae8d23](https://linux-hardware.org/?probe=321eae8d23) | Nov 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6323d7e1b3](https://linux-hardware.org/?probe=6323d7e1b3) | Nov 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3eea020596](https://linux-hardware.org/?probe=3eea020596) | Nov 01, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [f7a9c5f382](https://linux-hardware.org/?probe=f7a9c5f382) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [1d24aac4ce](https://linux-hardware.org/?probe=1d24aac4ce) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [406aae2f66](https://linux-hardware.org/?probe=406aae2f66) | Nov 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [ca5a47c66a](https://linux-hardware.org/?probe=ca5a47c66a) | Nov 01, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [85c215eebf](https://linux-hardware.org/?probe=85c215eebf) | Nov 01, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [560d84828c](https://linux-hardware.org/?probe=560d84828c) | Nov 01, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2eb32b1bb3](https://linux-hardware.org/?probe=2eb32b1bb3) | Nov 01, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [6d994999c9](https://linux-hardware.org/?probe=6d994999c9) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [24203a87c9](https://linux-hardware.org/?probe=24203a87c9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [77ccdee0fe](https://linux-hardware.org/?probe=77ccdee0fe) | Nov 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [a3a55bf3e4](https://linux-hardware.org/?probe=a3a55bf3e4) | Nov 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [dab530a737](https://linux-hardware.org/?probe=dab530a737) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [8d99f1fb3b](https://linux-hardware.org/?probe=8d99f1fb3b) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1a88842782](https://linux-hardware.org/?probe=1a88842782) | Nov 01, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [49e1be474a](https://linux-hardware.org/?probe=49e1be474a) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [e4f3828910](https://linux-hardware.org/?probe=e4f3828910) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | Desktop     | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| HP            | 8054                        | Desktop     | [9e1b99d9bb](https://linux-hardware.org/?probe=9e1b99d9bb) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| ASUSTek       | K54C                        | Notebook    | [dd4f63b1e4](https://linux-hardware.org/?probe=dd4f63b1e4) | Nov 01, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46dd8d9b6](https://linux-hardware.org/?probe=c46dd8d9b6) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [689b5a4022](https://linux-hardware.org/?probe=689b5a4022) | Nov 01, 2022 |
| Samsung       | 950QED                      | Convertible | [3fa8caa72f](https://linux-hardware.org/?probe=3fa8caa72f) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [446799aa8e](https://linux-hardware.org/?probe=446799aa8e) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [d39c952932](https://linux-hardware.org/?probe=d39c952932) | Nov 01, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [2532d13f74](https://linux-hardware.org/?probe=2532d13f74) | Nov 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [da912b99f4](https://linux-hardware.org/?probe=da912b99f4) | Nov 01, 2022 |
| Dell          | 082WXT A03                  | Desktop     | [ab3dad5a31](https://linux-hardware.org/?probe=ab3dad5a31) | Nov 01, 2022 |
| HP            | 09F8h                       | Desktop     | [f1107e91f2](https://linux-hardware.org/?probe=f1107e91f2) | Nov 01, 2022 |
| Timi          | TM1701                      | Notebook    | [84a5a6ce39](https://linux-hardware.org/?probe=84a5a6ce39) | Nov 01, 2022 |
| Dell          | Precision 3510              | Notebook    | [a87bb1e8dd](https://linux-hardware.org/?probe=a87bb1e8dd) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0131299a9e](https://linux-hardware.org/?probe=0131299a9e) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d729001115](https://linux-hardware.org/?probe=d729001115) | Nov 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5fdb241389](https://linux-hardware.org/?probe=5fdb241389) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| Acer          | Aspire one                  | Notebook    | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| AOpen         | aVKx-DE R1.03 55DEL10001... | Desktop     | [b487a7aee3](https://linux-hardware.org/?probe=b487a7aee3) | Oct 31, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [0301f1ddf1](https://linux-hardware.org/?probe=0301f1ddf1) | Oct 31, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [22b1e93203](https://linux-hardware.org/?probe=22b1e93203) | Oct 31, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [834e3f17aa](https://linux-hardware.org/?probe=834e3f17aa) | Oct 31, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [acc007bae4](https://linux-hardware.org/?probe=acc007bae4) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [566d83485b](https://linux-hardware.org/?probe=566d83485b) | Oct 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| HP            | 1850                        | Desktop     | [b39eac8f74](https://linux-hardware.org/?probe=b39eac8f74) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| Acer          | Unknown                     | Notebook    | [284f534a6a](https://linux-hardware.org/?probe=284f534a6a) | Oct 31, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a233571587](https://linux-hardware.org/?probe=a233571587) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [7c94d16c1c](https://linux-hardware.org/?probe=7c94d16c1c) | Oct 31, 2022 |
| Acer          | Aspire TC-280               | Desktop     | [68679c6495](https://linux-hardware.org/?probe=68679c6495) | Oct 31, 2022 |
| Acer          | Aspire V5-561G              | Notebook    | [ea7f8f381b](https://linux-hardware.org/?probe=ea7f8f381b) | Oct 31, 2022 |
| Acer          | Unknown                     | Notebook    | [27b5267fa3](https://linux-hardware.org/?probe=27b5267fa3) | Oct 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [183545ed4e](https://linux-hardware.org/?probe=183545ed4e) | Oct 31, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [72467c5d61](https://linux-hardware.org/?probe=72467c5d61) | Oct 31, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [8769289ea5](https://linux-hardware.org/?probe=8769289ea5) | Oct 31, 2022 |
| Sony          | VPCZ12C5E                   | Notebook    | [b1e6524541](https://linux-hardware.org/?probe=b1e6524541) | Oct 31, 2022 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [18db43ffed](https://linux-hardware.org/?probe=18db43ffed) | Oct 31, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Lenovo        | ThinkPad E580 20KTA001GE    | Notebook    | [55dc6ac7ba](https://linux-hardware.org/?probe=55dc6ac7ba) | Oct 31, 2022 |
| SANTECH       | NL5xRU                      | Notebook    | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [adebd09dc4](https://linux-hardware.org/?probe=adebd09dc4) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| MSI           | H81M-P33                    | Desktop     | [29e4a4ec52](https://linux-hardware.org/?probe=29e4a4ec52) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [96d61ed3e1](https://linux-hardware.org/?probe=96d61ed3e1) | Oct 31, 2022 |
| MSI           | MEG Z590 ACE                | Desktop     | [1082f00d60](https://linux-hardware.org/?probe=1082f00d60) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [7edc0875ed](https://linux-hardware.org/?probe=7edc0875ed) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [973fc77891](https://linux-hardware.org/?probe=973fc77891) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| ASUSTek       | VM60                        | Desktop     | [2cb5cc2932](https://linux-hardware.org/?probe=2cb5cc2932) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8e480ded02](https://linux-hardware.org/?probe=8e480ded02) | Oct 31, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [f31f613901](https://linux-hardware.org/?probe=f31f613901) | Oct 31, 2022 |
| Pegatron      | 2AABh                       | Desktop     | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [d6bc77d638](https://linux-hardware.org/?probe=d6bc77d638) | Oct 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Dell          | Latitude E6330              | Notebook    | [51ded2feb1](https://linux-hardware.org/?probe=51ded2feb1) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | Notebook    | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | CG8480                      | Desktop     | [0f7c1dc1cf](https://linux-hardware.org/?probe=0f7c1dc1cf) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| LG Electro... | A560-T.BG77P1               | Notebook    | [cad4120a42](https://linux-hardware.org/?probe=cad4120a42) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [966eb5bb18](https://linux-hardware.org/?probe=966eb5bb18) | Oct 31, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [71eeeaef9e](https://linux-hardware.org/?probe=71eeeaef9e) | Oct 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [dcccad24af](https://linux-hardware.org/?probe=dcccad24af) | Oct 31, 2022 |
| HP            | 3397                        | Desktop     | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [2c42913712](https://linux-hardware.org/?probe=2c42913712) | Oct 31, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| ASUSTek       | K54L                        | Notebook    | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [7cce0a2867](https://linux-hardware.org/?probe=7cce0a2867) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [eaa9bcaadb](https://linux-hardware.org/?probe=eaa9bcaadb) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [2fdcf19b6d](https://linux-hardware.org/?probe=2fdcf19b6d) | Oct 31, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [2ccd56ee29](https://linux-hardware.org/?probe=2ccd56ee29) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [7b016c85d8](https://linux-hardware.org/?probe=7b016c85d8) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [860f45c4c1](https://linux-hardware.org/?probe=860f45c4c1) | Oct 31, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [0786ded6c8](https://linux-hardware.org/?probe=0786ded6c8) | Oct 31, 2022 |
| Avell High... | B.ON                        | Notebook    | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | Notebook    | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [678ca55a4c](https://linux-hardware.org/?probe=678ca55a4c) | Oct 31, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [92e9764aa0](https://linux-hardware.org/?probe=92e9764aa0) | Oct 31, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fb96cd8e21](https://linux-hardware.org/?probe=fb96cd8e21) | Oct 31, 2022 |
| Acer          | Aspire 5733                 | Notebook    | [bcc1836178](https://linux-hardware.org/?probe=bcc1836178) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | Desktop     | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| Foxconn       | RS690M2MA 0A                | Desktop     | [29605bcad9](https://linux-hardware.org/?probe=29605bcad9) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [778e6caf06](https://linux-hardware.org/?probe=778e6caf06) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [d6bf187cc9](https://linux-hardware.org/?probe=d6bf187cc9) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [91aef8cd0f](https://linux-hardware.org/?probe=91aef8cd0f) | Oct 31, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | Notebook    | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [2ae72e7e22](https://linux-hardware.org/?probe=2ae72e7e22) | Oct 31, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [fbe835b8ef](https://linux-hardware.org/?probe=fbe835b8ef) | Oct 31, 2022 |
| Gigabyte      | B660M GAMING X AX           | Desktop     | [d48fe55211](https://linux-hardware.org/?probe=d48fe55211) | Oct 31, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [1a5e57e9ef](https://linux-hardware.org/?probe=1a5e57e9ef) | Oct 31, 2022 |
| Supermicro    | X11SSM-F                    | Server      | [c54a576ec0](https://linux-hardware.org/?probe=c54a576ec0) | Oct 31, 2022 |
| Supermicro    | X11SSL-F                    | Server      | [c13d2d5610](https://linux-hardware.org/?probe=c13d2d5610) | Oct 31, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [e49d4af683](https://linux-hardware.org/?probe=e49d4af683) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Sony          | VPCZ12C5E                   | Notebook    | [85803f499a](https://linux-hardware.org/?probe=85803f499a) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| Lenovo        | G700                        | Notebook    | [9bf9b4e263](https://linux-hardware.org/?probe=9bf9b4e263) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ce59648f62](https://linux-hardware.org/?probe=ce59648f62) | Oct 31, 2022 |
| HP            | 1790                        | Desktop     | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | Notebook    | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| Dell          | 0NDYHG A00                  | Desktop     | [1542958ace](https://linux-hardware.org/?probe=1542958ace) | Oct 31, 2022 |
| Adlinktech    | SB-MLC                      | Notebook    | [203d95e012](https://linux-hardware.org/?probe=203d95e012) | Oct 31, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [4fa081a282](https://linux-hardware.org/?probe=4fa081a282) | Oct 31, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [a4e522270c](https://linux-hardware.org/?probe=a4e522270c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [ed3f906a17](https://linux-hardware.org/?probe=ed3f906a17) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| Biostar       | H310MHC2                    | Desktop     | [5ad5ba772f](https://linux-hardware.org/?probe=5ad5ba772f) | Oct 31, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| Intel         | DG41AN AAE92991-401         | Desktop     | [cd670cef3d](https://linux-hardware.org/?probe=cd670cef3d) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | Notebook    | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [cf2b620a60](https://linux-hardware.org/?probe=cf2b620a60) | Oct 31, 2022 |
| HP            | 18E4                        | Desktop     | [89b197e8a9](https://linux-hardware.org/?probe=89b197e8a9) | Oct 31, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [14e8385f99](https://linux-hardware.org/?probe=14e8385f99) | Oct 31, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [0a8043d206](https://linux-hardware.org/?probe=0a8043d206) | Oct 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [5e87d391a3](https://linux-hardware.org/?probe=5e87d391a3) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Sony          | VGN-AR71MR                  | Notebook    | [4ecd695b12](https://linux-hardware.org/?probe=4ecd695b12) | Oct 31, 2022 |
| Intel         | D946GZAB AAD66610-300       | Desktop     | [33c41323a3](https://linux-hardware.org/?probe=33c41323a3) | Oct 31, 2022 |
| Dell          | Latitude E6530              | Notebook    | [5f82f9b682](https://linux-hardware.org/?probe=5f82f9b682) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [38d0d0e32a](https://linux-hardware.org/?probe=38d0d0e32a) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| HP            | 2000                        | Notebook    | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b5098e9fe5](https://linux-hardware.org/?probe=b5098e9fe5) | Oct 31, 2022 |
| Samsung       | DeskTop System              | Desktop     | [56b4bb00b0](https://linux-hardware.org/?probe=56b4bb00b0) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [a3abf820e1](https://linux-hardware.org/?probe=a3abf820e1) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| MSI           | 990FXA-GD80                 | Desktop     | [baaa1111ec](https://linux-hardware.org/?probe=baaa1111ec) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| Sony          | SVT13118FXS                 | Notebook    | [13b4af9ec3](https://linux-hardware.org/?probe=13b4af9ec3) | Oct 31, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| MSI           | AM1I                        | Desktop     | [30014de18a](https://linux-hardware.org/?probe=30014de18a) | Oct 31, 2022 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | Notebook    | [95554a578b](https://linux-hardware.org/?probe=95554a578b) | Oct 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [0e92fb8c99](https://linux-hardware.org/?probe=0e92fb8c99) | Oct 31, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [8b8c978f0b](https://linux-hardware.org/?probe=8b8c978f0b) | Oct 31, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [e24bf2e31f](https://linux-hardware.org/?probe=e24bf2e31f) | Oct 31, 2022 |
| Alienware     | 15 R3                       | Notebook    | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [e4af6d51f3](https://linux-hardware.org/?probe=e4af6d51f3) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| WTM           | W-N95 B0                    | Desktop     | [56611d3c8f](https://linux-hardware.org/?probe=56611d3c8f) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-201        | Desktop     | [b3403874f4](https://linux-hardware.org/?probe=b3403874f4) | Oct 31, 2022 |
| ASUSTek       | V241DA                      | All in one  | [8a9451cb9c](https://linux-hardware.org/?probe=8a9451cb9c) | Oct 31, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [dfdf6532b6](https://linux-hardware.org/?probe=dfdf6532b6) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0c1875c94f](https://linux-hardware.org/?probe=0c1875c94f) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| HP            | ENVY 17                     | Notebook    | [5b845d9ee3](https://linux-hardware.org/?probe=5b845d9ee3) | Oct 31, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d4340d8d66](https://linux-hardware.org/?probe=d4340d8d66) | Oct 31, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [7f41a14301](https://linux-hardware.org/?probe=7f41a14301) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASRock        | X470 Taichi                 | Desktop     | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [deac1b706f](https://linux-hardware.org/?probe=deac1b706f) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [92b732ad9a](https://linux-hardware.org/?probe=92b732ad9a) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [00dae3fbc5](https://linux-hardware.org/?probe=00dae3fbc5) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [dea1724953](https://linux-hardware.org/?probe=dea1724953) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [0ef6be44d0](https://linux-hardware.org/?probe=0ef6be44d0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [073ba962ff](https://linux-hardware.org/?probe=073ba962ff) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [aa1f78db58](https://linux-hardware.org/?probe=aa1f78db58) | Oct 31, 2022 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [5eabf4c6b3](https://linux-hardware.org/?probe=5eabf4c6b3) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge E530 3259M... | Notebook    | [26b5f59993](https://linux-hardware.org/?probe=26b5f59993) | Oct 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [221710c9ea](https://linux-hardware.org/?probe=221710c9ea) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [b1027d78bc](https://linux-hardware.org/?probe=b1027d78bc) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| HP            | 14                          | Notebook    | [7611c14813](https://linux-hardware.org/?probe=7611c14813) | Oct 31, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [3cb8d29f84](https://linux-hardware.org/?probe=3cb8d29f84) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [296d9a0f38](https://linux-hardware.org/?probe=296d9a0f38) | Oct 31, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [07a165b373](https://linux-hardware.org/?probe=07a165b373) | Oct 31, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [4179fe16d6](https://linux-hardware.org/?probe=4179fe16d6) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c8970ae94a](https://linux-hardware.org/?probe=c8970ae94a) | Oct 31, 2022 |
| Acer          | Nitro AN517-55              | Notebook    | [9653f093e1](https://linux-hardware.org/?probe=9653f093e1) | Oct 31, 2022 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [674ced10f2](https://linux-hardware.org/?probe=674ced10f2) | Oct 31, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [d84f634b59](https://linux-hardware.org/?probe=d84f634b59) | Oct 31, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [1fb51cc10c](https://linux-hardware.org/?probe=1fb51cc10c) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | Notebook    | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| MSI           | MS-7309                     | Desktop     | [a6b1a7d329](https://linux-hardware.org/?probe=a6b1a7d329) | Oct 31, 2022 |
| ASRock        | Z97 Extreme3                | Desktop     | [c741e4ffe8](https://linux-hardware.org/?probe=c741e4ffe8) | Oct 31, 2022 |
| ASUSTek       | K73SV                       | Notebook    | [d505f0c0d0](https://linux-hardware.org/?probe=d505f0c0d0) | Oct 30, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | Notebook    | [d6fc7c48a1](https://linux-hardware.org/?probe=d6fc7c48a1) | Oct 30, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| MSI           | MS-7309                     | Desktop     | [3c519589ad](https://linux-hardware.org/?probe=3c519589ad) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [472a3f2707](https://linux-hardware.org/?probe=472a3f2707) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [416655ce7d](https://linux-hardware.org/?probe=416655ce7d) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [71de876615](https://linux-hardware.org/?probe=71de876615) | Oct 30, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d6c135685f](https://linux-hardware.org/?probe=d6c135685f) | Oct 30, 2022 |
| HP            | 18E7                        | Desktop     | [6393aa1211](https://linux-hardware.org/?probe=6393aa1211) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| ASUSTek       | PHOENIX                     | Desktop     | [d4f8ae717d](https://linux-hardware.org/?probe=d4f8ae717d) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [ae71fe1a19](https://linux-hardware.org/?probe=ae71fe1a19) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [9cf3beb13f](https://linux-hardware.org/?probe=9cf3beb13f) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [36b3303b35](https://linux-hardware.org/?probe=36b3303b35) | Oct 30, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [85389b6454](https://linux-hardware.org/?probe=85389b6454) | Oct 30, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0d67856d8a](https://linux-hardware.org/?probe=0d67856d8a) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [e427e48710](https://linux-hardware.org/?probe=e427e48710) | Oct 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [9845791d39](https://linux-hardware.org/?probe=9845791d39) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [08cf9e2ccd](https://linux-hardware.org/?probe=08cf9e2ccd) | Oct 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [224f9c8141](https://linux-hardware.org/?probe=224f9c8141) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [209fa66bb9](https://linux-hardware.org/?probe=209fa66bb9) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| Acer          | Swift SFX14-51G             | Notebook    | [6812d7cf22](https://linux-hardware.org/?probe=6812d7cf22) | Oct 30, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [d7c699118b](https://linux-hardware.org/?probe=d7c699118b) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [738569f811](https://linux-hardware.org/?probe=738569f811) | Oct 30, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [955ce84cf2](https://linux-hardware.org/?probe=955ce84cf2) | Oct 30, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b903c0e375](https://linux-hardware.org/?probe=b903c0e375) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [cb2a07da11](https://linux-hardware.org/?probe=cb2a07da11) | Oct 30, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| HP            | x2 210                      | Notebook    | [8ed0a97ee9](https://linux-hardware.org/?probe=8ed0a97ee9) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [f8c58b7061](https://linux-hardware.org/?probe=f8c58b7061) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Sony          | VAIO                        | All in one  | [b295b1cb6f](https://linux-hardware.org/?probe=b295b1cb6f) | Oct 30, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [078fd46e0a](https://linux-hardware.org/?probe=078fd46e0a) | Oct 30, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [91d1732515](https://linux-hardware.org/?probe=91d1732515) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [25805a13b0](https://linux-hardware.org/?probe=25805a13b0) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| Biostar       | PE24                        | Desktop     | [57ad96c14e](https://linux-hardware.org/?probe=57ad96c14e) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| AZW           | GTR V01                     | Mini pc     | [03b291b957](https://linux-hardware.org/?probe=03b291b957) | Oct 30, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f1eac2c0c3](https://linux-hardware.org/?probe=f1eac2c0c3) | Oct 30, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| HP            | 158B                        | Desktop     | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |
| Chuwi         | LarkBox X                   | Mini pc     | [5cd057be2a](https://linux-hardware.org/?probe=5cd057be2a) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4820bca604](https://linux-hardware.org/?probe=4820bca604) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cdca8a4d95](https://linux-hardware.org/?probe=cdca8a4d95) | Oct 30, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [fabbcc9035](https://linux-hardware.org/?probe=fabbcc9035) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [21aa0f31b3](https://linux-hardware.org/?probe=21aa0f31b3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [c54736f079](https://linux-hardware.org/?probe=c54736f079) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | Notebook    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Dell          | XPS L322X                   | Notebook    | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [e28a25b18a](https://linux-hardware.org/?probe=e28a25b18a) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| ASUSTek       | X501A1                      | Notebook    | [037e1402b1](https://linux-hardware.org/?probe=037e1402b1) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [ac82c6bda9](https://linux-hardware.org/?probe=ac82c6bda9) | Oct 30, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [a7bc380726](https://linux-hardware.org/?probe=a7bc380726) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d4552d84d5](https://linux-hardware.org/?probe=d4552d84d5) | Oct 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| Lenovo        | ThinkPad T510 4384WKU       | Notebook    | [86fee6e260](https://linux-hardware.org/?probe=86fee6e260) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [150c8ac0ac](https://linux-hardware.org/?probe=150c8ac0ac) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b3c0e501b](https://linux-hardware.org/?probe=1b3c0e501b) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [d58eb8b2f0](https://linux-hardware.org/?probe=d58eb8b2f0) | Oct 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a8b08a47aa](https://linux-hardware.org/?probe=a8b08a47aa) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [55be6f23ce](https://linux-hardware.org/?probe=55be6f23ce) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| WeiBu         | Aptio CRB                   | Mini pc     | [fa111a4799](https://linux-hardware.org/?probe=fa111a4799) | Oct 30, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [c039d4321b](https://linux-hardware.org/?probe=c039d4321b) | Oct 30, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [01d8b89e0d](https://linux-hardware.org/?probe=01d8b89e0d) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [cbdfd56f05](https://linux-hardware.org/?probe=cbdfd56f05) | Oct 30, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [02d23cb1b9](https://linux-hardware.org/?probe=02d23cb1b9) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [54c64976ee](https://linux-hardware.org/?probe=54c64976ee) | Oct 30, 2022 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [8a1d96274e](https://linux-hardware.org/?probe=8a1d96274e) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [f4c2d5224b](https://linux-hardware.org/?probe=f4c2d5224b) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [673c23713c](https://linux-hardware.org/?probe=673c23713c) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [51a91ba41f](https://linux-hardware.org/?probe=51a91ba41f) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6873e5b579](https://linux-hardware.org/?probe=6873e5b579) | Oct 30, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [f60d156dd3](https://linux-hardware.org/?probe=f60d156dd3) | Oct 30, 2022 |
| LG Electro... | 15Z980-HA76K                | Notebook    | [914156672d](https://linux-hardware.org/?probe=914156672d) | Oct 30, 2022 |
| Lenovo        | ThinkPad X200 Tablet 745... | Notebook    | [032bc01698](https://linux-hardware.org/?probe=032bc01698) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| Dell          | Studio 1735                 | Notebook    | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [183feb626d](https://linux-hardware.org/?probe=183feb626d) | Oct 30, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | Desktop     | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [89595b2fa9](https://linux-hardware.org/?probe=89595b2fa9) | Oct 30, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| HP            | 1495                        | Desktop     | [b62f9d83b9](https://linux-hardware.org/?probe=b62f9d83b9) | Oct 30, 2022 |
| Huanan        | H510-D4 V4.0                | Desktop     | [89b298973c](https://linux-hardware.org/?probe=89b298973c) | Oct 30, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [03d14141e4](https://linux-hardware.org/?probe=03d14141e4) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [416db8870a](https://linux-hardware.org/?probe=416db8870a) | Oct 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [80d6d99bcf](https://linux-hardware.org/?probe=80d6d99bcf) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [33df9c20bf](https://linux-hardware.org/?probe=33df9c20bf) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| Intel         | NUC7i7BNB J31145-314        | Mini pc     | [9fd1f28183](https://linux-hardware.org/?probe=9fd1f28183) | Oct 30, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [bf8945db85](https://linux-hardware.org/?probe=bf8945db85) | Oct 30, 2022 |
| Medion        | MS-7707                     | Desktop     | [4f018e8577](https://linux-hardware.org/?probe=4f018e8577) | Oct 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| Chuwi         | LarkBook                    | Notebook    | [3ff2ff69ce](https://linux-hardware.org/?probe=3ff2ff69ce) | Oct 30, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [bf96e5a0a1](https://linux-hardware.org/?probe=bf96e5a0a1) | Oct 30, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [2d540e06b9](https://linux-hardware.org/?probe=2d540e06b9) | Oct 30, 2022 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [4208d513b4](https://linux-hardware.org/?probe=4208d513b4) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | Notebook    | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| HP            | ProBook 6540b               | Notebook    | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c63ee0d1b7](https://linux-hardware.org/?probe=c63ee0d1b7) | Oct 30, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6bbea41ce5](https://linux-hardware.org/?probe=6bbea41ce5) | Oct 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [a517f2e2dd](https://linux-hardware.org/?probe=a517f2e2dd) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d381c1626](https://linux-hardware.org/?probe=2d381c1626) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| EVGA          | 122-CK-NF68 2               | Desktop     | [91b3144c5c](https://linux-hardware.org/?probe=91b3144c5c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9f43a68f81](https://linux-hardware.org/?probe=9f43a68f81) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [8e2ab3d61b](https://linux-hardware.org/?probe=8e2ab3d61b) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [666a829545](https://linux-hardware.org/?probe=666a829545) | Oct 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9991d15803](https://linux-hardware.org/?probe=9991d15803) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| HP            | ProBook 6560b               | Notebook    | [89feda4b09](https://linux-hardware.org/?probe=89feda4b09) | Oct 30, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [15690a2198](https://linux-hardware.org/?probe=15690a2198) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [031a5998a5](https://linux-hardware.org/?probe=031a5998a5) | Oct 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [3760efa49c](https://linux-hardware.org/?probe=3760efa49c) | Oct 30, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [1b614b2744](https://linux-hardware.org/?probe=1b614b2744) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Dell          | Latitude 7490               | Notebook    | [95d0006efb](https://linux-hardware.org/?probe=95d0006efb) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c11b330691](https://linux-hardware.org/?probe=c11b330691) | Oct 30, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [0a7776630f](https://linux-hardware.org/?probe=0a7776630f) | Oct 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [44eaa95ffc](https://linux-hardware.org/?probe=44eaa95ffc) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [da1b668449](https://linux-hardware.org/?probe=da1b668449) | Oct 30, 2022 |
| ASUSTek       | TP401CA                     | Convertible | [8d97908e58](https://linux-hardware.org/?probe=8d97908e58) | Oct 30, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [180622c3be](https://linux-hardware.org/?probe=180622c3be) | Oct 30, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [b7760774ca](https://linux-hardware.org/?probe=b7760774ca) | Oct 30, 2022 |
| HP            | Unknown                     | Notebook    | [6e024c825e](https://linux-hardware.org/?probe=6e024c825e) | Oct 30, 2022 |
| Dell          | Latitude E6510              | Notebook    | [84a61bf436](https://linux-hardware.org/?probe=84a61bf436) | Oct 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [4e4e0ac802](https://linux-hardware.org/?probe=4e4e0ac802) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [8887bce606](https://linux-hardware.org/?probe=8887bce606) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| HIPER         | WORKBOOK                    | Notebook    | [0a3eb12b15](https://linux-hardware.org/?probe=0a3eb12b15) | Oct 30, 2022 |
| ASRock        | B450M Pro4-F R2.0           | Desktop     | [5fb37123e0](https://linux-hardware.org/?probe=5fb37123e0) | Oct 30, 2022 |
| Dell          | 0G214D A00                  | Desktop     | [43b30d9a84](https://linux-hardware.org/?probe=43b30d9a84) | Oct 30, 2022 |
| Dell          | 0G214D A00                  | Desktop     | [2ee26099ae](https://linux-hardware.org/?probe=2ee26099ae) | Oct 30, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| MSI           | MS-7358                     | Desktop     | [3ddf4b8fff](https://linux-hardware.org/?probe=3ddf4b8fff) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7047610fd9](https://linux-hardware.org/?probe=7047610fd9) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f22f67754e](https://linux-hardware.org/?probe=f22f67754e) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [7f78f3451e](https://linux-hardware.org/?probe=7f78f3451e) | Oct 29, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5769997d2a](https://linux-hardware.org/?probe=5769997d2a) | Oct 29, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [23ad30db1a](https://linux-hardware.org/?probe=23ad30db1a) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| Dell          | Latitude 5501               | Notebook    | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| GEO           | GeoBook3                    | Notebook    | [133a4460f6](https://linux-hardware.org/?probe=133a4460f6) | Oct 29, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [b3e8975edf](https://linux-hardware.org/?probe=b3e8975edf) | Oct 29, 2022 |
| Acer          | Aspire ZC-605               | All in one  | [0b6c0b7a7c](https://linux-hardware.org/?probe=0b6c0b7a7c) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| ASUSTek       | G11CD                       | Desktop     | [2a9d64387c](https://linux-hardware.org/?probe=2a9d64387c) | Oct 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [47b5907eec](https://linux-hardware.org/?probe=47b5907eec) | Oct 29, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [763e5e0492](https://linux-hardware.org/?probe=763e5e0492) | Oct 29, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| ASRock        | Z690 Steel Legend           | Desktop     | [cbfd203fd4](https://linux-hardware.org/?probe=cbfd203fd4) | Oct 29, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [97425e2f52](https://linux-hardware.org/?probe=97425e2f52) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [69198e503e](https://linux-hardware.org/?probe=69198e503e) | Oct 29, 2022 |
| HP            | 0AECh D                     | Desktop     | [ee09a01e9e](https://linux-hardware.org/?probe=ee09a01e9e) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [7d576ac245](https://linux-hardware.org/?probe=7d576ac245) | Oct 29, 2022 |
| Notebook      | W230SD                      | Notebook    | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [768d0e85c9](https://linux-hardware.org/?probe=768d0e85c9) | Oct 29, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [c5955c7440](https://linux-hardware.org/?probe=c5955c7440) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [f700e495ba](https://linux-hardware.org/?probe=f700e495ba) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [f6b00cb10f](https://linux-hardware.org/?probe=f6b00cb10f) | Oct 29, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [53754d84e7](https://linux-hardware.org/?probe=53754d84e7) | Oct 29, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [d8321f617e](https://linux-hardware.org/?probe=d8321f617e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ba5da6b270](https://linux-hardware.org/?probe=ba5da6b270) | Oct 29, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7f67023fa9](https://linux-hardware.org/?probe=7f67023fa9) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [13a12cbd22](https://linux-hardware.org/?probe=13a12cbd22) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [957fc9af86](https://linux-hardware.org/?probe=957fc9af86) | Oct 29, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | Notebook    | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [68238274ff](https://linux-hardware.org/?probe=68238274ff) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| Toshiba       | Satellite L50-A-1D6         | Notebook    | [77f308d89c](https://linux-hardware.org/?probe=77f308d89c) | Oct 29, 2022 |
| Lenovo        | ThinkPad T510 43145GG       | Notebook    | [d1e2bf7f33](https://linux-hardware.org/?probe=d1e2bf7f33) | Oct 29, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [a750edc641](https://linux-hardware.org/?probe=a750edc641) | Oct 29, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [9371d71f6d](https://linux-hardware.org/?probe=9371d71f6d) | Oct 29, 2022 |
| ASUSTek       | M3N-HT DELUXE               | Desktop     | [290f3b115f](https://linux-hardware.org/?probe=290f3b115f) | Oct 29, 2022 |
| ASUSTek       | M3N-HT DELUXE               | Desktop     | [bf841b86f5](https://linux-hardware.org/?probe=bf841b86f5) | Oct 29, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [05b5af2e63](https://linux-hardware.org/?probe=05b5af2e63) | Oct 29, 2022 |
| Dell          | Latitude E6510              | Notebook    | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| HP            | 18E7                        | Desktop     | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [f54f6d6354](https://linux-hardware.org/?probe=f54f6d6354) | Oct 29, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [39d64a1014](https://linux-hardware.org/?probe=39d64a1014) | Oct 29, 2022 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ce9df2cf8f](https://linux-hardware.org/?probe=ce9df2cf8f) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d768cd4c66](https://linux-hardware.org/?probe=d768cd4c66) | Oct 29, 2022 |
| SANTECH       | PCx0Dx                      | Notebook    | [24462321e8](https://linux-hardware.org/?probe=24462321e8) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [03f3800569](https://linux-hardware.org/?probe=03f3800569) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [1753d78397](https://linux-hardware.org/?probe=1753d78397) | Oct 29, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [73eae83658](https://linux-hardware.org/?probe=73eae83658) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [16815dacc1](https://linux-hardware.org/?probe=16815dacc1) | Oct 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6549416d9d](https://linux-hardware.org/?probe=6549416d9d) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| Foxconn       | 2ACA                        | Desktop     | [69544f77d0](https://linux-hardware.org/?probe=69544f77d0) | Oct 29, 2022 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 24196     | 13.1%   |
| Ubuntu 18.04      | 12891     | 6.98%   |
| Debian 11         | 4606      | 2.49%   |
| OpenMandriva 4.2  | 4557      | 2.47%   |
| ROSA R10          | 4389      | 2.38%   |
| Ubuntu 22.04      | 4322      | 2.34%   |
| ROSA R11          | 4110      | 2.22%   |
| OpenMandriva 4.3  | 3684      | 1.99%   |
| ROSA R8           | 3637      | 1.97%   |
| ROSA R6           | 3496      | 1.89%   |
| ROSA R7           | 3301      | 1.79%   |
| Arch              | 2984      | 1.62%   |
| ROSA R8.1         | 2852      | 1.54%   |
| KDE neon 20.04    | 2846      | 1.54%   |
| BlackPanther 18.1 | 2701      | 1.46%   |
| Linux Mint 20.3   | 2584      | 1.4%    |
| ROSA R9           | 2548      | 1.38%   |
| Linux Mint 20.2   | 2338      | 1.27%   |
| Manjaro           | 2331      | 1.26%   |
| Linux Mint 20.1   | 2219      | 1.2%    |
| ROSA R11.1        | 2217      | 1.2%    |
| Ubuntu 20.10      | 2215      | 1.2%    |
| Arch Rolling      | 2182      | 1.18%   |
| Linux Mint 19.3   | 2145      | 1.16%   |
| Pop!_OS 20.04     | 2114      | 1.14%   |
| Zorin 16          | 2107      | 1.14%   |
| Ubuntu 21.10      | 2078      | 1.12%   |
| Ubuntu 19.10      | 2055      | 1.11%   |
| Linux Mint 20     | 1963      | 1.06%   |
| ROSA 12.2         | 1932      | 1.05%   |
| Ubuntu 19.04      | 1903      | 1.03%   |
| Xubuntu 20.04     | 1869      | 1.01%   |
| Fedora 36         | 1867      | 1.01%   |
| Pop!_OS 21.04     | 1798      | 0.97%   |
| Ubuntu 21.04      | 1764      | 0.95%   |
| Debian 10         | 1721      | 0.93%   |
| Pop!_OS 20.10     | 1649      | 0.89%   |
| Fedora 35         | 1624      | 0.88%   |
| Zorin 15          | 1582      | 0.86%   |
| Fedora 34         | 1582      | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 51004     | 29.6%   |
| ROSA          | 24917     | 14.46%  |
| Linux Mint    | 13389     | 7.77%   |
| OpenMandriva  | 9245      | 5.37%   |
| Fedora        | 8568      | 4.97%   |
| Pop!_OS       | 7674      | 4.45%   |
| Debian        | 7460      | 4.33%   |
| Manjaro       | 5708      | 3.31%   |
| Arch          | 5059      | 2.94%   |
| Zorin         | 3872      | 2.25%   |
| Xubuntu       | 3583      | 2.08%   |
| Endless       | 3280      | 1.9%    |
| KDE neon      | 3248      | 1.89%   |
| BlackPanther  | 2915      | 1.69%   |
| Kubuntu       | 2903      | 1.68%   |
| openSUSE      | 1493      | 0.87%   |
| ArcoLinux     | 1377      | 0.8%    |
| Elementary    | 1243      | 0.72%   |
| Gentoo        | 1189      | 0.69%   |
| Ubuntu MATE   | 1146      | 0.67%   |
| Kali          | 1062      | 0.62%   |
| Ubuntu Unity  | 1040      | 0.6%    |
| Lubuntu       | 993       | 0.58%   |
| Clear Linux   | 784       | 0.46%   |
| EndeavourOS   | 649       | 0.38%   |
| CentOS        | 637       | 0.37%   |
| LMDE          | 588       | 0.34%   |
| Ubuntu Budgie | 529       | 0.31%   |
| ALT Linux     | 408       | 0.24%   |
| MX            | 389       | 0.23%   |
| SteamOS       | 370       | 0.21%   |
| Parrot        | 349       | 0.2%    |
| Garuda Linux  | 312       | 0.18%   |
| Peppermint    | 279       | 0.16%   |
| RHEL          | 228       | 0.13%   |
| LinuxFX       | 210       | 0.12%   |
| Raspbian      | 204       | 0.12%   |
| RED           | 193       | 0.11%   |
| Deepin        | 179       | 0.1%    |
| Solus         | 161       | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002           | 4388      | 2.16%   |
| 5.4.0-42-generic                   | 3803      | 1.87%   |
| 5.16.7-desktop-1omv4003            | 3558      | 1.75%   |
| 4.18.16-desktop-1bP                | 2067      | 1.02%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 2053      | 1.01%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 1868      | 0.92%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 1839      | 0.91%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 1797      | 0.89%   |
| 5.4.0-58-generic                   | 1726      | 0.85%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 1681      | 0.83%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 1602      | 0.79%   |
| 5.4.0-48-generic                   | 1530      | 0.75%   |
| 5.4.0-52-generic                   | 1518      | 0.75%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 1381      | 0.68%   |
| 5.4.0-26-generic                   | 1324      | 0.65%   |
| 5.15.0-46-generic                  | 1170      | 0.58%   |
| 5.3.0-28-generic                   | 1134      | 0.56%   |
| 5.4.0-29-generic                   | 1125      | 0.55%   |
| 5.4.0-40-generic                   | 1101      | 0.54%   |
| 5.3.0-40-generic                   | 1090      | 0.54%   |
| 5.11.0-27-generic                  | 1056      | 0.52%   |
| 5.15.0-48-generic                  | 1031      | 0.51%   |
| 5.10.0-8-amd64                     | 1004      | 0.49%   |
| 5.3.0-46-generic                   | 998       | 0.49%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 972       | 0.48%   |
| 5.4.0-54-generic                   | 945       | 0.47%   |
| 5.8.0-43-generic                   | 929       | 0.46%   |
| 5.11.0-37-generic                  | 925       | 0.46%   |
| 5.4.0-37-generic                   | 922       | 0.45%   |
| 5.11.0-38-generic                  | 921       | 0.45%   |
| 5.4.0-91-generic                   | 914       | 0.45%   |
| 5.4.0-65-generic                   | 912       | 0.45%   |
| 5.4.0-47-generic                   | 881       | 0.43%   |
| 5.0.0-37-generic                   | 875       | 0.43%   |
| 5.13.0-39-generic                  | 872       | 0.43%   |
| 5.11.0-7620-generic                | 844       | 0.42%   |
| 3.14.44-nrj-desktop-2rosa-i586     | 833       | 0.41%   |
| 5.13.0-30-generic                  | 822       | 0.41%   |
| 5.11.0-40-generic                  | 811       | 0.4%    |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 802       | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 31956     | 16.68%  |
| 4.15.0  | 14137     | 7.38%   |
| 5.8.0   | 10590     | 5.53%   |
| 5.11.0  | 10133     | 5.29%   |
| 5.13.0  | 8526      | 4.45%   |
| 5.3.0   | 7853      | 4.1%    |
| 5.15.0  | 7740      | 4.04%   |
| 5.10.0  | 5303      | 2.77%   |
| 5.0.0   | 5248      | 2.74%   |
| 5.10.14 | 4440      | 2.32%   |
| 4.18.0  | 3911      | 2.04%   |
| 5.16.7  | 3624      | 1.89%   |
| 3.14.44 | 2697      | 1.41%   |
| 4.9.60  | 2595      | 1.35%   |
| 4.9.20  | 2580      | 1.35%   |
| 4.1.25  | 2174      | 1.13%   |
| 4.18.16 | 2123      | 1.11%   |
| 4.19.0  | 1916      | 1%      |
| 4.1.15  | 1836      | 0.96%   |
| 5.10.74 | 1740      | 0.91%   |
| 4.1.34  | 1350      | 0.7%    |
| 4.1.38  | 1110      | 0.58%   |
| 4.9.9   | 1003      | 0.52%   |
| 4.9.124 | 994       | 0.52%   |
| 5.6.14  | 854       | 0.45%   |
| 5.19.0  | 835       | 0.44%   |
| 5.17.5  | 808       | 0.42%   |
| 4.9.155 | 678       | 0.35%   |
| 4.9.76  | 648       | 0.34%   |
| 5.14.0  | 635       | 0.33%   |
| 4.1.16  | 633       | 0.33%   |
| 4.9.41  | 627       | 0.33%   |
| 4.4.0   | 590       | 0.31%   |
| 5.4.32  | 589       | 0.31%   |
| 5.4.83  | 506       | 0.26%   |
| 5.18.0  | 503       | 0.26%   |
| 5.9.16  | 495       | 0.26%   |
| 5.16.0  | 443       | 0.23%   |
| 5.16.11 | 434       | 0.23%   |
| 5.12.4  | 430       | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 35303     | 18.94%  |
| 5.10    | 15205     | 8.16%   |
| 4.15    | 14207     | 7.62%   |
| 5.8     | 12877     | 6.91%   |
| 5.15    | 12125     | 6.5%    |
| 5.11    | 12030     | 6.45%   |
| 5.13    | 10159     | 5.45%   |
| 4.9     | 9222      | 4.95%   |
| 5.3     | 8855      | 4.75%   |
| 4.1     | 7574      | 4.06%   |
| 5.16    | 6377      | 3.42%   |
| 4.18    | 6137      | 3.29%   |
| 5.0     | 5564      | 2.98%   |
| 3.14    | 3554      | 1.91%   |
| 5.18    | 2725      | 1.46%   |
| 5.17    | 2722      | 1.46%   |
| 5.19    | 2676      | 1.44%   |
| 5.6     | 2625      | 1.41%   |
| 4.19    | 2509      | 1.35%   |
| 5.9     | 2348      | 1.26%   |
| 5.14    | 2328      | 1.25%   |
| 5.12    | 1886      | 1.01%   |
| 5.7     | 1635      | 0.88%   |
| 5.5     | 981       | 0.53%   |
| 4.4     | 817       | 0.44%   |
| 6.0     | 592       | 0.32%   |
| 3.10    | 528       | 0.28%   |
| 4.13    | 404       | 0.22%   |
| 5.2     | 399       | 0.21%   |
| 5.1     | 389       | 0.21%   |
| 4.14    | 221       | 0.12%   |
| 4.12    | 187       | 0.1%    |
| 4.16    | 172       | 0.09%   |
| 4.10    | 156       | 0.08%   |
| 4.8     | 136       | 0.07%   |
| 4.20    | 127       | 0.07%   |
| 4.17    | 93        | 0.05%   |
| 4.7     | 66        | 0.04%   |
| 2.6     | 65        | 0.03%   |
| 3.18    | 58        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 155910    | 93.21%  |
| i686     | 9846      | 5.89%   |
| aarch64  | 1098      | 0.66%   |
| armv7l   | 309       | 0.18%   |
| armv8l   | 38        | 0.02%   |
| armv6l   | 25        | 0.01%   |
| riscv64  | 8         | 0.005%  |
| ppc      | 8         | 0.005%  |
| ppc64    | 7         | 0.004%  |
| Unknown  | 6         | 0.004%  |
| i586     | 5         | 0.003%  |
| ppc64le  | 3         | 0.002%  |
| e2k      | 3         | 0.002%  |
| mips64   | 2         | 0.001%  |
| mips     | 2         | 0.001%  |
| armv5tel | 2         | 0.001%  |
| unknow   | 1         | 0.001%  |
| sh4a     | 1         | 0.001%  |
| s390x    | 1         | 0.001%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 65315     | 37.29%  |
| KDE5              | 29297     | 16.73%  |
| Unknown           | 22072     | 12.6%   |
| KDE4              | 18264     | 10.43%  |
| XFCE              | 10722     | 6.12%   |
| X-Cinnamon        | 9396      | 5.36%   |
| KDE               | 4440      | 2.53%   |
| MATE              | 4313      | 2.46%   |
| Cinnamon          | 2304      | 1.32%   |
| LXQt              | 1840      | 1.05%   |
| Pantheon          | 1157      | 0.66%   |
| Unity             | 1064      | 0.61%   |
| LXDE              | 929       | 0.53%   |
| Budgie            | 825       | 0.47%   |
| i3                | 758       | 0.43%   |
| GNOME Flashback   | 448       | 0.26%   |
| Deepin            | 438       | 0.25%   |
| GNOME Classic     | 182       | 0.1%    |
| awesome           | 175       | 0.1%    |
| openbox           | 159       | 0.09%   |
| GNUstep           | 125       | 0.07%   |
| sway              | 123       | 0.07%   |
| bspwm             | 106       | 0.06%   |
| qtile             | 88        | 0.05%   |
| DWM               | 81        | 0.05%   |
| lightdm-xsession  | 72        | 0.04%   |
| xmonad            | 64        | 0.04%   |
| trinity           | 53        | 0.03%   |
| Enlightenment     | 51        | 0.03%   |
| icewm             | 38        | 0.02%   |
| LeftWM            | 27        | 0.02%   |
| i3-with-shmlog    | 19        | 0.01%   |
| UKUI              | 14        | 0.01%   |
| herbstluftwm      | 14        | 0.01%   |
| Hyprland          | 12        | 0.01%   |
| fly               | 12        | 0.01%   |
| fluxbox           | 12        | 0.01%   |
| Cutefish          | 10        | 0.01%   |
| Yaru:ubuntu:GNOME | 8         | 0.005%  |
| xubuntu           | 7         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 137729    | 80.6%   |
| Wayland     | 18292     | 10.7%   |
| Unknown     | 12030     | 7.04%   |
| Tty         | 2814      | 1.65%   |
| Web         | 19        | 0.01%   |
| Unspecified | 4         | 0.002%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 81139     | 46.66%  |
| SDDM    | 27499     | 15.81%  |
| GDM     | 18447     | 10.61%  |
| KDM     | 18399     | 10.58%  |
| LightDM | 11164     | 6.42%   |
| GDM3    | 10435     | 6%      |
| TDM     | 6002      | 3.45%   |
| XDM     | 310       | 0.18%   |
| SLiM    | 166       | 0.1%    |
| LXDM    | 110       | 0.06%   |
| MDM     | 87        | 0.05%   |
| Ly      | 74        | 0.04%   |
| NODM    | 26        | 0.01%   |
| GREETD  | 20        | 0.01%   |
| FLY-DM  | 7         | 0.004%  |
| SLIMSKI | 3         | 0.002%  |
| WDM     | 2         | 0.001%  |
| LDM     | 2         | 0.001%  |
| EMPTTY  | 2         | 0.001%  |
| XINIT   | 1         | 0.001%  |
| CDM     | 1         | 0.001%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 53573     | 31.31%  |
| Unknown | 41806     | 24.43%  |
| de_DE   | 10502     | 6.14%   |
| ru_RU   | 9896      | 5.78%   |
| pt_BR   | 7186      | 4.2%    |
| en_GB   | 6712      | 3.92%   |
| fr_FR   | 5660      | 3.31%   |
| it_IT   | 3701      | 2.16%   |
| es_ES   | 3076      | 1.8%    |
| en_CA   | 2565      | 1.5%    |
| C       | 2431      | 1.42%   |
| pl_PL   | 2316      | 1.35%   |
| en_IN   | 2266      | 1.32%   |
| en_AU   | 1977      | 1.16%   |
| nl_NL   | 1018      | 0.59%   |
| es_MX   | 974       | 0.57%   |
| cs_CZ   | 887       | 0.52%   |
| es_AR   | 850       | 0.5%    |
| hu_HU   | 793       | 0.46%   |
| pt_PT   | 618       | 0.36%   |
| en_ZA   | 598       | 0.35%   |
| de_AT   | 568       | 0.33%   |
| zh_CN   | 562       | 0.33%   |
| tr_TR   | 516       | 0.3%    |
| ru_UA   | 488       | 0.29%   |
| sv_SE   | 468       | 0.27%   |
| ja_JP   | 444       | 0.26%   |
| de_CH   | 408       | 0.24%   |
| es_CL   | 386       | 0.23%   |
| es_CO   | 374       | 0.22%   |
| fi_FI   | 367       | 0.21%   |
| en_NZ   | 350       | 0.2%    |
| fr_CA   | 328       | 0.19%   |
| en_IE   | 319       | 0.19%   |
| el_GR   | 307       | 0.18%   |
| ro_RO   | 299       | 0.17%   |
| fr_BE   | 277       | 0.16%   |
| nl_BE   | 249       | 0.15%   |
| da_DK   | 235       | 0.14%   |
| uk_UA   | 232       | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 95943     | 56.31%  |
| EFI  | 74426     | 43.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 120880    | 70.48%  |
| Unknown             | 21406     | 12.48%  |
| Overlay             | 14132     | 8.24%   |
| Btrfs               | 10585     | 6.17%   |
| Xfs                 | 2082      | 1.21%   |
| Zfs                 | 1015      | 0.59%   |
| Ext2                | 461       | 0.27%   |
| Ext3                | 365       | 0.21%   |
| F2fs                | 207       | 0.12%   |
| Tmpfs               | 167       | 0.1%    |
| Aufs                | 70        | 0.04%   |
| Reiserfs            | 38        | 0.02%   |
| Jfs                 | 28        | 0.02%   |
| XXXXXXX             | 16        | 0.01%   |
| Rootfs              | 16        | 0.01%   |
| XXXXX               | 6         | 0.003%  |
| SAMSUNG             | 6         | 0.003%  |
| Fuse.fuse-overlayfs | 4         | 0.002%  |
| XXXX                | 3         | 0.002%  |
| XXX4                | 3         | 0.002%  |
| ExX4                | 3         | 0.002%  |
| XXX                 | 2         | 0.001%  |
| Ubifs               | 2         | 0.001%  |
| XXXfs               | 1         | 0.001%  |
| Xtrfs               | 1         | 0.001%  |
| Ufs                 | 1         | 0.001%  |
| SquXshfs            | 1         | 0.001%  |
| SquasXfs            | 1         | 0.001%  |
| OveXlay             | 1         | 0.001%  |
| Ntfs                | 1         | 0.001%  |
| Nfs                 | 1         | 0.001%  |
| Lvm                 | 1         | 0.001%  |
| Fuse.sshfs          | 1         | 0.001%  |
| Fuse.snapfuse       | 1         | 0.001%  |
| Exfat               | 1         | 0.001%  |
| Bcachefs            | 1         | 0.001%  |
| 2G                  | 1         | 0.001%  |
| 20G                 | 1         | 0.001%  |
| 12G                 | 1         | 0.001%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 89457     | 52.15%  |
| GPT     | 49540     | 28.88%  |
| MBR     | 32535     | 18.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 145873    | 85.7%   |
| Yes       | 24341     | 14.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 121230    | 71.12%  |
| Yes       | 49221     | 28.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 29933     | 17.98%  |
| Hewlett-Packard         | 21271     | 12.77%  |
| Lenovo                  | 21155     | 12.71%  |
| Dell                    | 19583     | 11.76%  |
| Gigabyte Technology     | 12431     | 7.47%   |
| Acer                    | 10384     | 6.24%   |
| MSI                     | 9304      | 5.59%   |
| ASRock                  | 6511      | 3.91%   |
| Apple                   | 3552      | 2.13%   |
| Intel                   | 2948      | 1.77%   |
| Toshiba                 | 2872      | 1.72%   |
| Samsung Electronics     | 2598      | 1.56%   |
| Sony                    | 1527      | 0.92%   |
| Unknown                 | 1504      | 0.9%    |
| Fujitsu                 | 1171      | 0.7%    |
| Raspberry Pi Foundation | 971       | 0.58%   |
| Medion                  | 786       | 0.47%   |
| Pegatron                | 782       | 0.47%   |
| Packard Bell            | 771       | 0.46%   |
| HUAWEI                  | 751       | 0.45%   |
| ECS                     | 744       | 0.45%   |
| Foxconn                 | 719       | 0.43%   |
| Biostar                 | 687       | 0.41%   |
| Positivo                | 652       | 0.39%   |
| Supermicro              | 584       | 0.35%   |
| Notebook                | 578       | 0.35%   |
| Google                  | 535       | 0.32%   |
| Fujitsu Siemens         | 534       | 0.32%   |
| Microsoft               | 444       | 0.27%   |
| eMachines               | 406       | 0.24%   |
| Alienware               | 404       | 0.24%   |
| System76                | 317       | 0.19%   |
| Valve                   | 294       | 0.18%   |
| AMI                     | 289       | 0.17%   |
| Timi                    | 287       | 0.17%   |
| LG Electronics          | 265       | 0.16%   |
| Gateway                 | 265       | 0.16%   |
| TUXEDO                  | 251       | 0.15%   |
| Clevo                   | 247       | 0.15%   |
| Chuwi                   | 199       | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Unknown                   | 2114      | 1.27%   |
| ASUS All Series           | 1750      | 1.05%   |
| HP Notebook               | 623       | 0.37%   |
| HP Pavilion g6            | 472       | 0.28%   |
| HP Pavilion dv6           | 445       | 0.27%   |
| RPi Raspberry Pi          | 344       | 0.21%   |
| Apple MacBook5,2          | 330       | 0.2%    |
| Dell OptiPlex 7010        | 319       | 0.19%   |
| Valve Jupiter             | 294       | 0.18%   |
| MSI MS-7C37               | 287       | 0.17%   |
| Gigabyte B450M DS3H       | 281       | 0.17%   |
| HP Pavilion dv7           | 278       | 0.17%   |
| HP Pavilion 15            | 270       | 0.16%   |
| ASUS TUF Gaming X570-PLUS | 266       | 0.16%   |
| MSI MS-7C02               | 259       | 0.16%   |
| HP Pavilion Notebook      | 252       | 0.15%   |
| MSI MS-7817               | 250       | 0.15%   |
| Gigabyte 970A-DS3P        | 242       | 0.15%   |
| ASUS PRIME A320M-K        | 238       | 0.14%   |
| Dell Latitude E6420       | 220       | 0.13%   |
| Dell OptiPlex 9020        | 214       | 0.13%   |
| ASUS M5A78L-M/USB3        | 209       | 0.13%   |
| Dell OptiPlex 780         | 204       | 0.12%   |
| MSI MS-7B86               | 198       | 0.12%   |
| HP 15                     | 197       | 0.12%   |
| MSI MS-7721               | 193       | 0.12%   |
| MSI MS-7693               | 193       | 0.12%   |
| Dell Latitude E6430       | 193       | 0.12%   |
| Dell Latitude E6410       | 193       | 0.12%   |
| Dell OptiPlex 790         | 189       | 0.11%   |
| ASUS M5A97 R2.0           | 188       | 0.11%   |
| Acer Nitro AN515-54       | 188       | 0.11%   |
| Apple MacBookAir7,2       | 179       | 0.11%   |
| HP Laptop 15-bw0xx        | 177       | 0.11%   |
| Dell XPS 15 7590          | 173       | 0.1%    |
| MSI MS-7A38               | 171       | 0.1%    |
| Dell Inspiron 15-3567     | 168       | 0.1%    |
| Apple MacBookPro9,2       | 167       | 0.1%    |
| Dell Latitude E6400       | 165       | 0.1%    |
| ASRock B450M Pro4         | 165       | 0.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 8792      | 5.28%   |
| Acer Aspire           | 6991      | 4.2%    |
| Dell Inspiron         | 5493      | 3.3%    |
| Dell Latitude         | 4779      | 2.87%   |
| Lenovo IdeaPad        | 4253      | 2.55%   |
| HP Pavilion           | 4161      | 2.5%    |
| Dell OptiPlex         | 2819      | 1.69%   |
| ASUS PRIME            | 2576      | 1.55%   |
| Toshiba Satellite     | 2439      | 1.46%   |
| HP EliteBook          | 2437      | 1.46%   |
| HP Compaq             | 2403      | 1.44%   |
| Unknown               | 2114      | 1.27%   |
| HP ProBook            | 2103      | 1.26%   |
| Dell XPS              | 2102      | 1.26%   |
| ASUS ROG              | 2069      | 1.24%   |
| HP Laptop             | 1922      | 1.15%   |
| ASUS VivoBook         | 1834      | 1.1%    |
| ASUS All              | 1750      | 1.05%   |
| Dell Precision        | 1655      | 0.99%   |
| ASUS TUF              | 1338      | 0.8%    |
| Lenovo ThinkCentre    | 1250      | 0.75%   |
| Dell Vostro           | 1183      | 0.71%   |
| HP ENVY               | 978       | 0.59%   |
| RPi Raspberry         | 969       | 0.58%   |
| Lenovo Yoga           | 779       | 0.47%   |
| Acer Nitro            | 741       | 0.45%   |
| ASUS M5A78L-M         | 642       | 0.39%   |
| HP Notebook           | 626       | 0.38%   |
| Lenovo Legion         | 610       | 0.37%   |
| Acer Swift            | 549       | 0.33%   |
| Packard Bell EasyNote | 542       | 0.33%   |
| Fujitsu LIFEBOOK      | 523       | 0.31%   |
| Gigabyte X570         | 520       | 0.31%   |
| ASUS Zenbook          | 486       | 0.29%   |
| Gigabyte B450M        | 462       | 0.28%   |
| ASUS P8H61-M          | 461       | 0.28%   |
| HP ZBook              | 452       | 0.27%   |
| HP EliteDesk          | 447       | 0.27%   |
| ASUS M5A97            | 446       | 0.27%   |
| Microsoft Surface     | 444       | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 15168     | 9.11%   |
| 2018    | 14905     | 8.95%   |
| 2019    | 14124     | 8.48%   |
| 2011    | 14014     | 8.42%   |
| 2013    | 12376     | 7.43%   |
| 2020    | 12175     | 7.31%   |
| 2017    | 10596     | 6.36%   |
| 2010    | 10400     | 6.25%   |
| 2014    | 9570      | 5.75%   |
| 2009    | 8489      | 5.1%    |
| 2015    | 8468      | 5.09%   |
| 2016    | 8303      | 4.99%   |
| 2008    | 7939      | 4.77%   |
| 2021    | 7169      | 4.31%   |
| 2007    | 5666      | 3.4%    |
| 2006    | 2699      | 1.62%   |
| 2022    | 1559      | 0.94%   |
| Unknown | 1352      | 0.81%   |
| 2005    | 1006      | 0.6%    |
| 2004    | 302       | 0.18%   |
| 2003    | 158       | 0.09%   |
| 2002    | 38        | 0.02%   |
| 2001    | 18        | 0.01%   |
| 2000    | 10        | 0.01%   |
| 1999    | 3         | 0.002%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 89151     | 53.54%  |
| Desktop        | 66327     | 39.83%  |
| Convertible    | 3245      | 1.95%   |
| All in one     | 1954      | 1.17%   |
| Mini pc        | 1925      | 1.16%   |
| Server         | 1307      | 0.78%   |
| System on chip | 1257      | 0.75%   |
| Tablet         | 1210      | 0.73%   |
| Phone          | 109       | 0.07%   |
| Stick pc       | 12        | 0.01%   |
| Other          | 6         | 0.004%  |
| Firewall       | 4         | 0.002%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 156563    | 93.45%  |
| Enabled  | 10976     | 6.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 165685    | 99.51%  |
| Yes  | 824       | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 38355     | 22.53%  |
| 4.01-8.0        | 36988     | 21.73%  |
| 8.01-16.0       | 29760     | 17.48%  |
| 16.01-24.0      | 28981     | 17.02%  |
| 32.01-64.0      | 12363     | 7.26%   |
| 1.01-2.0        | 10564     | 6.21%   |
| 2.01-3.0        | 4932      | 2.9%    |
| 64.01-256.0     | 3509      | 2.06%   |
| 24.01-32.0      | 2100      | 1.23%   |
| 0.51-1.0        | 1861      | 1.09%   |
| Unknown         | 425       | 0.25%   |
| More than 256.0 | 224       | 0.13%   |
| 0.01-0.5        | 172       | 0.1%    |
| 0               | 1         | 0.001%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 69595     | 37.35%  |
| 2.01-3.0        | 40138     | 21.54%  |
| 0.51-1.0        | 25202     | 13.53%  |
| 4.01-8.0        | 20636     | 11.08%  |
| 3.01-4.0        | 19223     | 10.32%  |
| 8.01-16.0       | 5667      | 3.04%   |
| 0.01-0.5        | 3778      | 2.03%   |
| 16.01-24.0      | 836       | 0.45%   |
| Unknown         | 621       | 0.33%   |
| 24.01-32.0      | 311       | 0.17%   |
| 32.01-64.0      | 220       | 0.12%   |
| 64.01-256.0     | 77        | 0.04%   |
| More than 256.0 | 10        | 0.01%   |
| 0               | 6         | 0.003%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 104822    | 60.74%  |
| 2       | 42127     | 24.41%  |
| 3       | 12952     | 7.51%   |
| 4       | 5677      | 3.29%   |
| 5       | 2621      | 1.52%   |
| 0       | 1730      | 1%      |
| 6       | 1192      | 0.69%   |
| 7       | 586       | 0.34%   |
| 8       | 279       | 0.16%   |
| 9       | 163       | 0.09%   |
| Unknown | 118       | 0.07%   |
| 10      | 79        | 0.05%   |
| 11      | 69        | 0.04%   |
| 13      | 30        | 0.02%   |
| 12      | 30        | 0.02%   |
| 14      | 21        | 0.01%   |
| 16      | 10        | 0.01%   |
| 17      | 9         | 0.01%   |
| 15      | 9         | 0.01%   |
| 18      | 7         | 0.004%  |
| 20      | 5         | 0.003%  |
| 36      | 4         | 0.002%  |
| 24      | 4         | 0.002%  |
| 19      | 4         | 0.002%  |
| 27      | 3         | 0.002%  |
| 97      | 2         | 0.001%  |
| 93      | 2         | 0.001%  |
| 28      | 2         | 0.001%  |
| 25      | 2         | 0.001%  |
| 23      | 2         | 0.001%  |
| 22      | 2         | 0.001%  |
| 21      | 2         | 0.001%  |
| 209     | 1         | 0.001%  |
| 87      | 1         | 0.001%  |
| 71      | 1         | 0.001%  |
| 68      | 1         | 0.001%  |
| 51      | 1         | 0.001%  |
| 46      | 1         | 0.001%  |
| 45      | 1         | 0.001%  |
| 37      | 1         | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 92736     | 55.04%  |
| Yes       | 75749     | 44.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147493    | 88.37%  |
| No        | 19412     | 11.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 120782    | 71.99%  |
| No        | 47005     | 28.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89129     | 52.81%  |
| No        | 79650     | 47.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25906     | 15.35%  |
| Russia       | 22063     | 13.07%  |
| Germany      | 15212     | 9.01%   |
| Brazil       | 10609     | 6.29%   |
| Unknown      | 8072      | 4.78%   |
| France       | 7149      | 4.24%   |
| UK           | 5905      | 3.5%    |
| Italy        | 5659      | 3.35%   |
| Canada       | 4397      | 2.61%   |
| Spain        | 4200      | 2.49%   |
| Poland       | 3807      | 2.26%   |
| India        | 3564      | 2.11%   |
| Hungary      | 3330      | 1.97%   |
| Netherlands  | 3128      | 1.85%   |
| Ukraine      | 3043      | 1.8%    |
| Australia    | 2550      | 1.51%   |
| Mexico       | 1823      | 1.08%   |
| Switzerland  | 1668      | 0.99%   |
| Czechia      | 1613      | 0.96%   |
| Sweden       | 1595      | 0.95%   |
| Argentina    | 1484      | 0.88%   |
| Austria      | 1464      | 0.87%   |
| Romania      | 1438      | 0.85%   |
| Belgium      | 1436      | 0.85%   |
| Turkey       | 1314      | 0.78%   |
| Portugal     | 1222      | 0.72%   |
| Finland      | 1095      | 0.65%   |
| China        | 1033      | 0.61%   |
| Greece       | 1030      | 0.61%   |
| Indonesia    | 945       | 0.56%   |
| Japan        | 914       | 0.54%   |
| South Africa | 872       | 0.52%   |
| Belarus      | 834       | 0.49%   |
| Norway       | 816       | 0.48%   |
| Colombia     | 769       | 0.46%   |
| Bulgaria     | 768       | 0.46%   |
| Chile        | 713       | 0.42%   |
| Denmark      | 707       | 0.42%   |
| Slovakia     | 599       | 0.35%   |
| Serbia       | 589       | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 8112      | 4.52%   |
| Moscow            | 4354      | 2.43%   |
| St Petersburg     | 1847      | 1.03%   |
| Sao Paulo         | 1402      | 0.78%   |
| Berlin            | 1373      | 0.76%   |
| Budapest          | 1287      | 0.72%   |
| Paris             | 1134      | 0.63%   |
| Voronezh          | 997       | 0.56%   |
| Vienna            | 862       | 0.48%   |
| Warsaw            | 861       | 0.48%   |
| Milan             | 767       | 0.43%   |
| Pecherskoye       | 765       | 0.43%   |
| Sydney            | 725       | 0.4%    |
| Kyiv              | 719       | 0.4%    |
| Munich            | 718       | 0.4%    |
| Novosibirsk       | 706       | 0.39%   |
| Bangor            | 684       | 0.38%   |
| Rome              | 679       | 0.38%   |
| Madrid            | 676       | 0.38%   |
| Hamburg           | 639       | 0.36%   |
| Prague            | 635       | 0.35%   |
| Rio de Janeiro    | 632       | 0.35%   |
| Yekaterinburg     | 617       | 0.34%   |
| Krasnodar         | 602       | 0.34%   |
| Amsterdam         | 574       | 0.32%   |
| Athens            | 563       | 0.31%   |
| Melbourne         | 518       | 0.29%   |
| Istanbul          | 513       | 0.29%   |
| Frankfurt am Main | 501       | 0.28%   |
| Helsinki          | 496       | 0.28%   |
| Zurich            | 481       | 0.27%   |
| Barcelona         | 478       | 0.27%   |
| Bucharest         | 470       | 0.26%   |
| Toronto           | 459       | 0.26%   |
| Nizhniy Novgorod  | 458       | 0.26%   |
| Montreal          | 451       | 0.25%   |
| Samara            | 445       | 0.25%   |
| Bengaluru         | 440       | 0.25%   |
| Sofia             | 407       | 0.23%   |
| Rostov-on-Don     | 398       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 41164     | 63917  | 17.22%  |
| Seagate                   | 40610     | 62732  | 16.99%  |
| Samsung Electronics       | 33548     | 51180  | 14.04%  |
| Toshiba                   | 17347     | 23255  | 7.26%   |
| Kingston                  | 12744     | 16991  | 5.33%   |
| SanDisk                   | 10625     | 13955  | 4.45%   |
| Hitachi                   | 9961      | 13298  | 4.17%   |
| Unknown                   | 9387      | 12762  | 3.93%   |
| Crucial                   | 7262      | 10061  | 3.04%   |
| Intel                     | 5458      | 7678   | 2.28%   |
| HGST                      | 4957      | 7108   | 2.07%   |
| SK hynix                  | 4727      | 5873   | 1.98%   |
| A-DATA Technology         | 3409      | 4479   | 1.43%   |
| Micron Technology         | 2497      | 3146   | 1.04%   |
| Phison                    | 1812      | 2493   | 0.76%   |
| China                     | 1808      | 2329   | 0.76%   |
| Apple                     | 1517      | 1936   | 0.63%   |
| Fujitsu                   | 1465      | 1716   | 0.61%   |
| Maxtor                    | 1415      | 1866   | 0.59%   |
| SPCC                      | 1334      | 1754   | 0.56%   |
| OCZ                       | 1289      | 1684   | 0.54%   |
| PNY                       | 1163      | 1494   | 0.49%   |
| Transcend                 | 1011      | 1291   | 0.42%   |
| KIOXIA                    | 1011      | 1296   | 0.42%   |
| LITEON                    | 907       | 1085   | 0.38%   |
| Silicon Motion            | 881       | 1163   | 0.37%   |
| Patriot                   | 873       | 1145   | 0.37%   |
| Intenso                   | 868       | 1153   | 0.36%   |
| Corsair                   | 859       | 1128   | 0.36%   |
| GOODRAM                   | 673       | 913    | 0.28%   |
| JMicron Technology        | 609       | 728    | 0.25%   |
| Plextor                   | 605       | 859    | 0.25%   |
| Micron/Crucial Technology | 572       | 748    | 0.24%   |
| Apacer                    | 536       | 684    | 0.22%   |
| LITEONIT                  | 525       | 652    | 0.22%   |
| Hewlett-Packard           | 502       | 764    | 0.21%   |
| Unknown                   | 488       | 541    | 0.2%    |
| KingSpec                  | 481       | 619    | 0.2%    |
| Team                      | 439       | 576    | 0.18%   |
| XPG                       | 418       | 560    | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 2511      | 0.95%   |
| Seagate ST1000LM035-1RK172 1TB         | 2116      | 0.8%    |
| Seagate ST500DM002-1BD142 500GB        | 2100      | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 1908      | 0.72%   |
| Samsung SSD 860 EVO 500GB              | 1786      | 0.68%   |
| Samsung SSD 850 EVO 250GB              | 1696      | 0.64%   |
| Kingston SA400S37120G 120GB SSD        | 1678      | 0.64%   |
| Unknown MMC Card  32GB                 | 1605      | 0.61%   |
| Toshiba MQ01ABD100 1TB                 | 1595      | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB         | 1426      | 0.54%   |
| Toshiba MQ01ABF050 500GB               | 1421      | 0.54%   |
| Seagate ST500LT012-1DG142 500GB        | 1361      | 0.52%   |
| Kingston SV300S37A120G 120GB SSD       | 1335      | 0.51%   |
| Samsung SSD 850 EVO 500GB              | 1321      | 0.5%    |
| Toshiba DT01ACA100 1TB                 | 1251      | 0.47%   |
| Samsung NVMe SSD Drive 512GB           | 1248      | 0.47%   |
| Unknown MMC Card  64GB                 | 1221      | 0.46%   |
| Kingston SA400S37480G 480GB SSD        | 1175      | 0.45%   |
| Samsung NVMe SSD Drive 500GB           | 1154      | 0.44%   |
| HGST HTS721010A9E630 1TB               | 1118      | 0.42%   |
| Seagate ST9500325AS 500GB              | 1115      | 0.42%   |
| Samsung SSD 860 EVO 1TB                | 1096      | 0.42%   |
| Toshiba MQ04ABF100 1TB                 | 1089      | 0.41%   |
| Samsung SSD 860 EVO 250GB              | 1055      | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB               | 1054      | 0.4%    |
| Seagate ST3500418AS 500GB              | 1042      | 0.39%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 998       | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB         | 994       | 0.38%   |
| Samsung NVMe SSD Drive 1TB             | 990       | 0.38%   |
| Crucial CT500MX500SSD1 500GB           | 984       | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB         | 982       | 0.37%   |
| Crucial CT240BX500SSD1 240GB           | 900       | 0.34%   |
| SanDisk NVMe SSD Drive 512GB           | 848       | 0.32%   |
| Toshiba DT01ACA050 500GB               | 844       | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB         | 819       | 0.31%   |
| Intel NVMe SSD Drive 512GB             | 811       | 0.31%   |
| Unknown SD/MMC/MS PRO 1TB              | 796       | 0.3%    |
| Crucial CT1000MX500SSD1 1TB            | 778       | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 765       | 0.29%   |
| HGST HTS545050A7E680 500GB             | 763       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40012     | 61506  | 34.55%  |
| WDC                 | 34973     | 54217  | 30.2%   |
| Toshiba             | 14068     | 18807  | 12.15%  |
| Hitachi             | 9959      | 13295  | 8.6%    |
| Samsung Electronics | 6116      | 8601   | 5.28%   |
| HGST                | 4951      | 6962   | 4.28%   |
| Fujitsu             | 1448      | 1689   | 1.25%   |
| Maxtor              | 1364      | 1789   | 1.18%   |
| Unknown             | 880       | 1239   | 0.76%   |
| Apple               | 460       | 537    | 0.4%    |
| SABRENT             | 269       | 317    | 0.23%   |
| Hewlett-Packard     | 136       | 258    | 0.12%   |
| ASMT                | 106       | 202    | 0.09%   |
| Intenso             | 101       | 141    | 0.09%   |
| IBM/Hitachi         | 83        | 96     | 0.07%   |
| USB3.0              | 74        | 91     | 0.06%   |
| JMicron Technology  | 71        | 108    | 0.06%   |
| ExcelStor           | 54        | 66     | 0.05%   |
| ASMedia             | 45        | 58     | 0.04%   |
| WD MediaMax         | 43        | 60     | 0.04%   |
| HGST HTS            | 36        | 45     | 0.03%   |
| LaCie               | 31        | 52     | 0.03%   |
| USB                 | 30        | 35     | 0.03%   |
| HPE                 | 26        | 45     | 0.02%   |
| Inateck             | 23        | 28     | 0.02%   |
| ASMT109x            | 23        | 33     | 0.02%   |
| KESU                | 22        | 30     | 0.02%   |
| Quantum             | 20        | 21     | 0.02%   |
| PHD 3.0             | 19        | 20     | 0.02%   |
| MARVELL             | 18        | 25     | 0.02%   |
| Magnetic Data       | 16        | 18     | 0.01%   |
| IBM                 | 15        | 21     | 0.01%   |
| Maxone              | 13        | 16     | 0.01%   |
| Apricorn            | 13        | 16     | 0.01%   |
| SATAFIRM            | 12        | 13     | 0.01%   |
| SAGE                | 12        | 15     | 0.01%   |
| Unknown             | 11        | 14     | 0.01%   |
| External            | 10        | 10     | 0.01%   |
| Dell                | 10        | 16     | 0.01%   |
| USB 3.0             | 9         | 17     | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16602     | 24125  | 22.37%  |
| Kingston            | 10845     | 14411  | 14.62%  |
| SanDisk             | 7066      | 9359   | 9.52%   |
| Crucial             | 6704      | 9312   | 9.04%   |
| WDC                 | 4394      | 5763   | 5.92%   |
| A-DATA Technology   | 2807      | 3686   | 3.78%   |
| Intel               | 2231      | 3056   | 3.01%   |
| China               | 1785      | 2304   | 2.41%   |
| Micron Technology   | 1344      | 1737   | 1.81%   |
| OCZ                 | 1274      | 1643   | 1.72%   |
| Toshiba             | 1246      | 1659   | 1.68%   |
| SK hynix            | 1222      | 1527   | 1.65%   |
| SPCC                | 1213      | 1598   | 1.63%   |
| PNY                 | 1086      | 1398   | 1.46%   |
| Transcend           | 941       | 1196   | 1.27%   |
| Patriot             | 830       | 1094   | 1.12%   |
| LITEON              | 825       | 995    | 1.11%   |
| Apple               | 774       | 894    | 1.04%   |
| Intenso             | 654       | 846    | 0.88%   |
| GOODRAM             | 651       | 884    | 0.88%   |
| Corsair             | 612       | 793    | 0.82%   |
| Plextor             | 559       | 791    | 0.75%   |
| LITEONIT            | 525       | 652    | 0.71%   |
| Apacer              | 487       | 631    | 0.66%   |
| KingSpec            | 464       | 598    | 0.63%   |
| Team                | 397       | 514    | 0.54%   |
| Netac               | 303       | 417    | 0.41%   |
| Gigabyte Technology | 269       | 367    | 0.36%   |
| KingDian            | 262       | 349    | 0.35%   |
| ASMT                | 259       | 304    | 0.35%   |
| Hewlett-Packard     | 256       | 346    | 0.35%   |
| Seagate             | 251       | 348    | 0.34%   |
| Lexar               | 240       | 279    | 0.32%   |
| Smartbuy            | 216       | 273    | 0.29%   |
| Unknown             | 182       | 211    | 0.25%   |
| Unknown             | 179       | 203    | 0.24%   |
| Mushkin             | 172       | 254    | 0.23%   |
| AMD                 | 158       | 210    | 0.21%   |
| TO Exter            | 147       | 184    | 0.2%    |
| FORESEE             | 125       | 146    | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98196     | 170911 | 46.04%  |
| SSD     | 65297     | 99952  | 30.62%  |
| NVMe    | 38205     | 55106  | 17.91%  |
| MMC     | 8111      | 10910  | 3.8%    |
| Unknown | 3454      | 5008   | 1.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 135018    | 262838 | 71.18%  |
| NVMe | 37878     | 54514  | 19.97%  |
| SAS  | 8666      | 13625  | 4.57%   |
| MMC  | 8111      | 10910  | 4.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 104049    | 166118 | 61.19%  |
| 0.51-1.0        | 46283     | 69592  | 27.22%  |
| 1.01-2.0        | 11539     | 18751  | 6.79%   |
| 3.01-4.0        | 3345      | 6348   | 1.97%   |
| 2.01-3.0        | 2424      | 4322   | 1.43%   |
| 4.01-10.0       | 2045      | 4641   | 1.2%    |
| 10.01-20.0      | 327       | 1059   | 0.19%   |
| 20.01-50.0      | 9         | 20     | 0.01%   |
| 0               | 7         | 7      | 0.004%  |
| More than 100.0 | 1         | 1      | 0.001%  |
| 50.01-100.0     | 1         | 4      | 0.001%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 46423     | 25.89%  |
| 251-500        | 38930     | 21.71%  |
| 501-1000       | 25063     | 13.98%  |
| 1-20           | 14963     | 8.35%   |
| 51-100         | 13360     | 7.45%   |
| 1001-2000      | 12380     | 6.91%   |
| 21-50          | 8971      | 5%      |
| Unknown        | 7583      | 4.23%   |
| More than 3000 | 7064      | 3.94%   |
| 2001-3000      | 4544      | 2.53%   |
| 0              | 1         | 0.001%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 79128     | 42.82%  |
| 21-50          | 28784     | 15.57%  |
| 101-250        | 20430     | 11.05%  |
| 51-100         | 18665     | 10.1%   |
| 251-500        | 12360     | 6.69%   |
| 501-1000       | 8742      | 4.73%   |
| Unknown        | 7583      | 4.1%    |
| 1001-2000      | 4824      | 2.61%   |
| More than 3000 | 2549      | 1.38%   |
| 2001-3000      | 1710      | 0.93%   |
| 0              | 36        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 440       | 556    | 1.73%   |
| Seagate ST9500325AS 500GB           | 403       | 517    | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 282       | 346    | 1.11%   |
| Seagate ST500LT012-9WS142 500GB     | 278       | 357    | 1.1%    |
| Seagate ST3500418AS 500GB           | 274       | 362    | 1.08%   |
| HGST HTS545050A7E680 500GB          | 222       | 294    | 0.87%   |
| Seagate ST500LT012-1DG142 500GB     | 216       | 256    | 0.85%   |
| Seagate ST9320325AS 320GB           | 213       | 268    | 0.84%   |
| Seagate ST9250315AS 250GB           | 172       | 210    | 0.68%   |
| Toshiba MQ01ABD100 1TB              | 153       | 182    | 0.6%    |
| Kingston SV300S37A120G 120GB SSD    | 153       | 173    | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB      | 152       | 163    | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB         | 150       | 189    | 0.59%   |
| Seagate ST31000528AS 1TB            | 149       | 189    | 0.59%   |
| Seagate ST3250410AS 250GB           | 141       | 179    | 0.56%   |
| HGST HTS541010A9E680 1TB            | 140       | 171    | 0.55%   |
| Seagate ST3250310AS 250GB           | 129       | 184    | 0.51%   |
| HGST HTS721010A9E630 1TB            | 126       | 149    | 0.5%    |
| HGST HTS545050A7E380 500GB          | 126       | 176    | 0.5%    |
| Hitachi HTS543232A7A384 320GB       | 122       | 148    | 0.48%   |
| Toshiba MQ01ABF050 500GB            | 117       | 147    | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB      | 114       | 154    | 0.45%   |
| HGST HTS725050A7E630 500GB          | 112       | 136    | 0.44%   |
| Seagate ST9500420AS 500GB           | 111       | 139    | 0.44%   |
| Seagate ST31000524AS 1TB            | 111       | 143    | 0.44%   |
| Seagate ST320LT020-9YG142 320GB     | 108       | 154    | 0.43%   |
| Seagate ST1000DM003-9YN162 1TB      | 107       | 122    | 0.42%   |
| Toshiba MQ01ABD050 500GB            | 103       | 122    | 0.41%   |
| SanDisk SSD U100 256GB              | 103       | 103    | 0.41%   |
| Seagate ST3320613AS 320GB           | 100       | 130    | 0.39%   |
| Hitachi HTS547575A9E384 752GB       | 100       | 127    | 0.39%   |
| Hitachi HTS545050B9A300 500GB       | 98        | 125    | 0.39%   |
| Hitachi HTS545050A7E380 500GB       | 98        | 120    | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB             | 97        | 138    | 0.38%   |
| Seagate ST3160815AS 160GB           | 95        | 111    | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB         | 93        | 109    | 0.37%   |
| Hitachi HTS547550A9E384 500GB       | 91        | 120    | 0.36%   |
| Hitachi HTS545025B9A300 250GB       | 91        | 117    | 0.36%   |
| Hitachi HDS721050CLA362 500GB       | 91        | 115    | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 89        | 107    | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7461      | 9925   | 30.53%  |
| WDC                 | 5486      | 7324   | 22.45%  |
| Hitachi             | 2727      | 3465   | 11.16%  |
| Samsung Electronics | 1928      | 2500   | 7.89%   |
| Toshiba             | 1864      | 2303   | 7.63%   |
| HGST                | 903       | 1141   | 3.7%    |
| Kingston            | 541       | 642    | 2.21%   |
| Maxtor              | 449       | 552    | 1.84%   |
| SanDisk             | 447       | 498    | 1.83%   |
| Intel               | 336       | 423    | 1.37%   |
| Crucial             | 290       | 357    | 1.19%   |
| Fujitsu             | 259       | 301    | 1.06%   |
| A-DATA Technology   | 223       | 274    | 0.91%   |
| SK hynix            | 206       | 246    | 0.84%   |
| OCZ                 | 140       | 184    | 0.57%   |
| Micron Technology   | 131       | 157    | 0.54%   |
| SPCC                | 96        | 117    | 0.39%   |
| Corsair             | 88        | 115    | 0.36%   |
| China               | 61        | 72     | 0.25%   |
| LITEON              | 54        | 61     | 0.22%   |
| Apple               | 45        | 49     | 0.18%   |
| LITEONIT            | 42        | 52     | 0.17%   |
| IBM/Hitachi         | 38        | 43     | 0.16%   |
| Kingmax             | 37        | 61     | 0.15%   |
| KingSpec            | 36        | 46     | 0.15%   |
| Hewlett-Packard     | 33        | 37     | 0.14%   |
| Plextor             | 32        | 47     | 0.13%   |
| Transcend           | 26        | 34     | 0.11%   |
| ASMT                | 23        | 32     | 0.09%   |
| Intenso             | 20        | 26     | 0.08%   |
| Unknown             | 18        | 23     | 0.07%   |
| Apacer              | 17        | 25     | 0.07%   |
| Patriot             | 15        | 18     | 0.06%   |
| Mushkin             | 15        | 15     | 0.06%   |
| AMD                 | 13        | 17     | 0.05%   |
| ExcelStor           | 12        | 14     | 0.05%   |
| Unknown             | 12        | 15     | 0.05%   |
| WD MediaMax         | 11        | 16     | 0.05%   |
| PNY                 | 11        | 15     | 0.05%   |
| KingDian            | 11        | 16     | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7460      | 9922   | 36.02%  |
| WDC                 | 5363      | 7171   | 25.89%  |
| Hitachi             | 2727      | 3465   | 13.17%  |
| Toshiba             | 1812      | 2240   | 8.75%   |
| Samsung Electronics | 1550      | 2044   | 7.48%   |
| HGST                | 903       | 1141   | 4.36%   |
| Maxtor              | 449       | 552    | 2.17%   |
| Fujitsu             | 259       | 301    | 1.25%   |
| IBM/Hitachi         | 38        | 43     | 0.18%   |
| Apple               | 32        | 36     | 0.15%   |
| Hewlett-Packard     | 19        | 23     | 0.09%   |
| ExcelStor           | 12        | 14     | 0.06%   |
| WD MediaMax         | 11        | 16     | 0.05%   |
| IBM                 | 11        | 13     | 0.05%   |
| Unknown             | 10        | 15     | 0.05%   |
| ASMT                | 10        | 15     | 0.05%   |
| ASMedia             | 6         | 6      | 0.03%   |
| HGST HTS            | 5         | 7      | 0.02%   |
| MARSHAL             | 4         | 5      | 0.02%   |
| Quantum             | 3         | 3      | 0.01%   |
| HPE                 | 3         | 3      | 0.01%   |
| Unknown             | 3         | 4      | 0.01%   |
| USB3.0              | 2         | 3      | 0.01%   |
| MDT                 | 2         | 2      | 0.01%   |
| Magnetic Data       | 2         | 2      | 0.01%   |
| JMicron Technology  | 2         | 2      | 0.01%   |
| TPH00100500GB       | 1         | 1      | 0.005%  |
| SATAFIRM            | 1         | 1      | 0.005%  |
| SABRENT             | 1         | 1      | 0.005%  |
| RSH-339             | 1         | 1      | 0.005%  |
| MaxDigital          | 1         | 1      | 0.005%  |
| Initio              | 1         | 1      | 0.005%  |
| Inateck             | 1         | 1      | 0.005%  |
| ICY BOX             | 1         | 1      | 0.005%  |
| IB                  | 1         | 1      | 0.005%  |
| FEASSO              | 1         | 2      | 0.005%  |
| DAS                 | 1         | 3      | 0.005%  |
| China               | 1         | 1      | 0.005%  |
| Apricorn            | 1         | 1      | 0.005%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 19121     | 27064  | 83.79%  |
| SSD     | 3339      | 4086   | 14.63%  |
| NVMe    | 356       | 437    | 1.56%   |
| Unknown | 3         | 3      | 0.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 18        | 21     | 2.64%   |
| Seagate ST31000528AS 1TB           | 14        | 16     | 2.06%   |
| Samsung Electronics HD502HJ 500GB  | 10        | 12     | 1.47%   |
| Samsung Electronics HM321HI 320GB  | 9         | 11     | 1.32%   |
| Hitachi HDS721010DLE630 1TB        | 9         | 16     | 1.32%   |
| Seagate ST9500325AS 500GB          | 8         | 9      | 1.17%   |
| Seagate ST31000524AS 1TB           | 8         | 10     | 1.17%   |
| HGST HTS545050A7E680 500GB         | 8         | 8      | 1.17%   |
| Seagate ST9320325AS 320GB          | 7         | 8      | 1.03%   |
| Seagate ST500LT012-1DG142 500GB    | 7         | 7      | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 7      | 1.03%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 0.88%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 6         | 7      | 0.88%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 6      | 0.88%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 0.88%   |
| Samsung Electronics HD502IJ 500GB  | 6         | 6      | 0.88%   |
| Samsung Electronics HD103SJ 1TB    | 6         | 7      | 0.88%   |
| Hitachi HTS545050A7E380 500GB      | 6         | 6      | 0.88%   |
| HGST HTS721010A9E630 1TB           | 6         | 7      | 0.88%   |
| Toshiba MK6465GSX 640GB            | 5         | 7      | 0.73%   |
| Seagate ST3500410AS 500GB          | 5         | 6      | 0.73%   |
| Seagate ST3250318AS 250GB          | 5         | 9      | 0.73%   |
| Samsung Electronics HD322GJ 320GB  | 5         | 6      | 0.73%   |
| Samsung Electronics HD252HJ 250GB  | 5         | 9      | 0.73%   |
| Hitachi HTS547550A9E384 500GB      | 5         | 6      | 0.73%   |
| HGST HTS545050A7E380 500GB         | 5         | 5      | 0.73%   |
| Apple HDD HTS541010A9E662 1TB      | 5         | 5      | 0.73%   |
| Toshiba MQ01ABD100 1TB             | 4         | 4      | 0.59%   |
| Toshiba MQ01ABD050 500GB           | 4         | 4      | 0.59%   |
| Toshiba MK5065GSX 500GB            | 4         | 4      | 0.59%   |
| Toshiba MK3265GSX 320GB            | 4         | 4      | 0.59%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 0.59%   |
| Seagate ST31500341AS 1TB           | 4         | 5      | 0.59%   |
| Seagate ST31000333AS 1TB           | 4         | 4      | 0.59%   |
| Samsung Electronics SSD 980 500GB  | 4         | 5      | 0.59%   |
| Samsung Electronics SP0411N 40GB   | 4         | 5      | 0.59%   |
| Samsung Electronics HM160HI 160GB  | 4         | 4      | 0.59%   |
| Hitachi HTS547575A9E384 752GB      | 4         | 5      | 0.59%   |
| Hitachi HDS721010CLA332 1TB        | 4         | 4      | 0.59%   |
| HGST HTS541010A9E680 1TB           | 4         | 4      | 0.59%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 180       | 216    | 26.51%  |
| WDC                 | 172       | 200    | 25.33%  |
| Samsung Electronics | 114       | 135    | 16.79%  |
| Toshiba             | 72        | 79     | 10.6%   |
| Hitachi             | 57        | 67     | 8.39%   |
| HGST                | 28        | 30     | 4.12%   |
| Maxtor              | 12        | 12     | 1.77%   |
| Apple               | 7         | 8      | 1.03%   |
| Kingston            | 4         | 4      | 0.59%   |
| Intel               | 4         | 4      | 0.59%   |
| Crucial             | 4         | 4      | 0.59%   |
| Hewlett-Packard     | 3         | 6      | 0.44%   |
| Fujitsu             | 2         | 2      | 0.29%   |
| Zheino              | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |
| Transcend           | 1         | 1      | 0.15%   |
| TPH00800640GB       | 1         | 1      | 0.15%   |
| SK hynix            | 1         | 1      | 0.15%   |
| SanDisk             | 1         | 1      | 0.15%   |
| Phison              | 1         | 1      | 0.15%   |
| Patriot             | 1         | 2      | 0.15%   |
| OCZ-AGIL            | 1         | 1      | 0.15%   |
| OCZ                 | 1         | 1      | 0.15%   |
| Mushkin             | 1         | 1      | 0.15%   |
| Micron Technology   | 1         | 1      | 0.15%   |
| LITEON              | 1         | 2      | 0.15%   |
| KingDian            | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| Intenso             | 1         | 1      | 0.15%   |
| GOODRAM             | 1         | 1      | 0.15%   |
| External            | 1         | 1      | 0.15%   |
| Corsair             | 1         | 1      | 0.15%   |
| A-DATA Technology   | 1         | 1      | 0.15%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 92233     | 184114 | 50.46%  |
| Works    | 67600     | 125389 | 36.98%  |
| Malfunc  | 22268     | 31590  | 12.18%  |
| Failed   | 673       | 789    | 0.37%   |
| Limited  | 5         | 5      | 0.003%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 112883    | 56.23%  |
| AMD                              | 32691     | 16.28%  |
| Samsung Electronics              | 13977     | 6.96%   |
| SanDisk                          | 5963      | 2.97%   |
| Nvidia                           | 4536      | 2.26%   |
| SK hynix                         | 3377      | 1.68%   |
| JMicron Technology               | 3086      | 1.54%   |
| ASMedia Technology               | 3054      | 1.52%   |
| Marvell Technology Group         | 2697      | 1.34%   |
| Phison Electronics               | 2591      | 1.29%   |
| Toshiba America Info Systems     | 2184      | 1.09%   |
| Kingston Technology Company      | 2102      | 1.05%   |
| Silicon Motion                   | 1238      | 0.62%   |
| Micron Technology                | 1195      | 0.6%    |
| Micron/Crucial Technology        | 1122      | 0.56%   |
| KIOXIA                           | 1112      | 0.55%   |
| ADATA Technology                 | 1035      | 0.52%   |
| VIA Technologies                 | 923       | 0.46%   |
| LSI Logic / Symbios Logic        | 589       | 0.29%   |
| Silicon Integrated Systems [SiS] | 547       | 0.27%   |
| Realtek Semiconductor            | 505       | 0.25%   |
| Broadcom / LSI                   | 454       | 0.23%   |
| Union Memory (Shenzhen)          | 343       | 0.17%   |
| Silicon Image                    | 320       | 0.16%   |
| Apple                            | 292       | 0.15%   |
| Lite-On Technology               | 275       | 0.14%   |
| Solid State Storage Technology   | 262       | 0.13%   |
| Adaptec                          | 184       | 0.09%   |
| Seagate Technology               | 183       | 0.09%   |
| Hewlett-Packard                  | 177       | 0.09%   |
| Lenovo                           | 141       | 0.07%   |
| Integrated Technology Express    | 110       | 0.05%   |
| Shenzhen Longsys Electronics     | 82        | 0.04%   |
| Yangtze Memory Technologies      | 53        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 50        | 0.02%   |
| ULi Electronics                  | 41        | 0.02%   |
| OCZ Technology Group             | 39        | 0.02%   |
| Unknown                          | 35        | 0.02%   |
| Biwin Storage Technology         | 34        | 0.02%   |
| Promise Technology               | 30        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20437     | 8.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8205      | 3.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8094      | 3.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7798      | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7188      | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 5901      | 2.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5647      | 2.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5041      | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4960      | 2.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4863      | 2.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4529      | 1.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4064      | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3882      | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3763      | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3728      | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3679      | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3304      | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2981      | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2857      | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2756      | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2686      | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2607      | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2447      | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2395      | 1%      |
| Intel SATA Controller [RAID mode]                                                       | 2366      | 0.98%   |
| Samsung NVMe SSD Controller 980                                                         | 2255      | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2183      | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2121      | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2117      | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2044      | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2001      | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1964      | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1942      | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1851      | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1813      | 0.75%   |
| Nvidia MCP61 SATA Controller                                                            | 1688      | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 1682      | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1681      | 0.7%    |
| AMD 500 Series Chipset SATA Controller                                                  | 1622      | 0.67%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 1599      | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 120298    | 58.58%  |
| NVMe | 38374     | 18.69%  |
| IDE  | 33522     | 16.32%  |
| RAID | 12135     | 5.91%   |
| SAS  | 654       | 0.32%   |
| SCSI | 369       | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 125528    | 75.38%  |
| AMD                      | 39430     | 23.68%  |
| ARM                      | 1356      | 0.81%   |
| QUALCOMM                 | 54        | 0.03%   |
| CentaurHauls             | 51        | 0.03%   |
| Unknown                  | 41        | 0.02%   |
| Phytium                  | 15        | 0.01%   |
| HiSilicon                | 5         | 0.003%  |
| Marvell Semiconductor    | 4         | 0.002%  |
| sifive,u74-mc            | 3         | 0.002%  |
| sifive,bullet0           | 3         | 0.002%  |
| PowerNV C1P9S01 REV 1.01 | 2         | 0.001%  |
| MIPS                     | 2         | 0.001%  |
| CHRP IBM,9131-52A        | 2         | 0.001%  |
| CHRP IBM,8233-E8B        | 2         | 0.001%  |
| PowerNV FP5466G2         | 1         | 0.001%  |
| PowerMac8,1              | 1         | 0.001%  |
| PowerMac7,2              | 1         | 0.001%  |
| PowerMac3,6              | 1         | 0.001%  |
| PowerMac11,2             | 1         | 0.001%  |
| PowerMac10,2             | 1         | 0.001%  |
| PowerBook6,7             | 1         | 0.001%  |
| PowerBook5,6             | 1         | 0.001%  |
| PowerBook5,5             | 1         | 0.001%  |
| PowerBook5,4             | 1         | 0.001%  |
| PowerBook3,4             | 1         | 0.001%  |
| MBE8C-PC                 | 1         | 0.001%  |
| IBM/S390                 | 1         | 0.001%  |
| GenuineTMx86             | 1         | 0.001%  |
| FSP-1                    | 1         | 0.001%  |
| E8C/EATX                 | 1         | 0.001%  |
| E8C-SWTX                 | 1         | 0.001%  |
| AppliedMicro             | 1         | 0.001%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 1711      | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1463      | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1451      | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1273      | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1190      | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1156      | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1155      | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1020      | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1015      | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1012      | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 998       | 0.6%    |
| ARM Processor                                 | 986       | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 967       | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 950       | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 929       | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 926       | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 915       | 0.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 886       | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 879       | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 861       | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 846       | 0.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 835       | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 820       | 0.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 815       | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 774       | 0.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 755       | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 708       | 0.42%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 689       | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 684       | 0.41%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 671       | 0.4%    |
| AMD FX-8350 Eight-Core Processor              | 656       | 0.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 648       | 0.39%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 641       | 0.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 633       | 0.38%   |
| AMD FX-6300 Six-Core Processor                | 633       | 0.38%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 626       | 0.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 610       | 0.37%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 608       | 0.36%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 604       | 0.36%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 587       | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34531     | 20.69%  |
| Intel Core i7           | 28168     | 16.88%  |
| Intel Core i3           | 14110     | 8.45%   |
| Intel Core 2 Duo        | 8919      | 5.34%   |
| Intel Celeron           | 8728      | 5.23%   |
| AMD Ryzen 5             | 7787      | 4.67%   |
| Other                   | 6882      | 4.12%   |
| AMD Ryzen 7             | 5584      | 3.35%   |
| Intel Pentium           | 5536      | 3.32%   |
| Intel Xeon              | 4041      | 2.42%   |
| Intel Atom              | 3936      | 2.36%   |
| AMD FX                  | 3140      | 1.88%   |
| Intel Pentium Dual-Core | 2773      | 1.66%   |
| Intel Core 2 Quad       | 1876      | 1.12%   |
| AMD Ryzen 9             | 1729      | 1.04%   |
| AMD Ryzen 3             | 1700      | 1.02%   |
| AMD A6                  | 1569      | 0.94%   |
| AMD A8                  | 1551      | 0.93%   |
| AMD Athlon 64 X2        | 1422      | 0.85%   |
| Intel Core 2            | 1406      | 0.84%   |
| Intel Pentium Dual      | 1324      | 0.79%   |
| AMD A10                 | 1295      | 0.78%   |
| AMD A4                  | 1287      | 0.77%   |
| AMD Athlon II X2        | 1205      | 0.72%   |
| AMD Phenom II X4        | 1100      | 0.66%   |
| Intel Pentium 4         | 962       | 0.58%   |
| Intel Core i9           | 925       | 0.55%   |
| AMD E                   | 803       | 0.48%   |
| Intel Genuine           | 769       | 0.46%   |
| AMD E1                  | 650       | 0.39%   |
| AMD Athlon              | 598       | 0.36%   |
| Intel Pentium Silver    | 563       | 0.34%   |
| AMD Athlon II X4        | 561       | 0.34%   |
| AMD Ryzen 7 PRO         | 521       | 0.31%   |
| AMD E2                  | 496       | 0.3%    |
| Intel Pentium D         | 439       | 0.26%   |
| AMD Phenom II X6        | 405       | 0.24%   |
| AMD Ryzen Threadripper  | 371       | 0.22%   |
| AMD Sempron             | 361       | 0.22%   |
| AMD Phenom              | 339       | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 75031     | 44.79%  |
| 4       | 56732     | 33.87%  |
| 6       | 13270     | 7.92%   |
| 8       | 9012      | 5.38%   |
| 1       | 6094      | 3.64%   |
| Unknown | 2008      | 1.2%    |
| 12      | 1725      | 1.03%   |
| 3       | 1431      | 0.85%   |
| 16      | 883       | 0.53%   |
| 10      | 433       | 0.26%   |
| 14      | 242       | 0.14%   |
| 24      | 163       | 0.1%    |
| 32      | 140       | 0.08%   |
| 20      | 133       | 0.08%   |
| 28      | 32        | 0.02%   |
| 64      | 31        | 0.02%   |
| 18      | 31        | 0.02%   |
| 40      | 30        | 0.02%   |
| 48      | 17        | 0.01%   |
| 5       | 15        | 0.01%   |
| 36      | 8         | 0.005%  |
| 96      | 7         | 0.004%  |
| 44      | 7         | 0.004%  |
| 128     | 6         | 0.004%  |
| 56      | 5         | 0.003%  |
| 22      | 4         | 0.002%  |
| 80      | 3         | 0.002%  |
| 192     | 2         | 0.001%  |
| 52      | 2         | 0.001%  |
| 120     | 1         | 0.001%  |
| 104     | 1         | 0.001%  |
| 72      | 1         | 0.001%  |
| 68      | 1         | 0.001%  |
| 26      | 1         | 0.001%  |
| 15      | 1         | 0.001%  |
| 7       | 1         | 0.001%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 164634    | 98.81%  |
| 2       | 1639      | 0.98%   |
| Unknown | 271       | 0.16%   |
| 4       | 54        | 0.03%   |
| 3       | 18        | 0.01%   |
| 8       | 2         | 0.001%  |
| 6       | 1         | 0.001%  |
| 0       | 1         | 0.001%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 99838     | 59.62%  |
| 1       | 65571     | 39.16%  |
| Unknown | 2008      | 1.2%    |
| 4       | 14        | 0.01%   |
| 8       | 13        | 0.01%   |
| 112     | 1         | 0.001%  |
| 16      | 1         | 0.001%  |
| 6       | 1         | 0.001%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160036    | 95.67%  |
| Unknown        | 4641      | 2.77%   |
| 32-bit         | 2308      | 1.38%   |
| 64-bit         | 301       | 0.18%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31779     | 18.47%  |
| 0x206a7    | 11664     | 6.78%   |
| 0x306a9    | 10821     | 6.29%   |
| 0x1067a    | 8067      | 4.69%   |
| 0x306c3    | 7708      | 4.48%   |
| 0x906ea    | 4251      | 2.47%   |
| 0x806ea    | 3657      | 2.13%   |
| 0x40651    | 3481      | 2.02%   |
| 0x806ec    | 3366      | 1.96%   |
| 0x20655    | 3343      | 1.94%   |
| 0x506e3    | 3212      | 1.87%   |
| 0x806e9    | 3158      | 1.84%   |
| 0x406e3    | 3007      | 1.75%   |
| 0x6fd      | 2928      | 1.7%    |
| 0x906e9    | 2866      | 1.67%   |
| 0x306d4    | 2756      | 1.6%    |
| 0x806c1    | 2568      | 1.49%   |
| 0x010000c8 | 2292      | 1.33%   |
| 0x10676    | 2086      | 1.21%   |
| 0x30678    | 2003      | 1.16%   |
| 0x08701021 | 1889      | 1.1%    |
| 0x06001119 | 1665      | 0.97%   |
| 0x406c4    | 1648      | 0.96%   |
| 0x08108109 | 1611      | 0.94%   |
| 0x06000852 | 1492      | 0.87%   |
| 0x6fb      | 1450      | 0.84%   |
| 0x0800820d | 1400      | 0.81%   |
| 0x20652    | 1387      | 0.81%   |
| 0x706e5    | 1134      | 0.66%   |
| 0x08108102 | 1084      | 0.63%   |
| 0x706a1    | 1075      | 0.62%   |
| 0x106ca    | 1073      | 0.62%   |
| 0xa0652    | 1039      | 0.6%    |
| 0x106e5    | 1027      | 0.6%    |
| 0x0a50000c | 1008      | 0.59%   |
| 0x08701013 | 995       | 0.58%   |
| 0x806eb    | 972       | 0.56%   |
| 0x506c9    | 972       | 0.56%   |
| 0x08600106 | 963       | 0.56%   |
| 0x906ed    | 959       | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23981     | 14.37%  |
| Haswell          | 13989     | 8.38%   |
| SandyBridge      | 13855     | 8.3%    |
| IvyBridge        | 12915     | 7.74%   |
| Penryn           | 11453     | 6.86%   |
| Skylake          | 7967      | 4.77%   |
| Core             | 7157      | 4.29%   |
| Zen 2            | 6318      | 3.79%   |
| Westmere         | 5922      | 3.55%   |
| Silvermont       | 5464      | 3.27%   |
| Zen+             | 5247      | 3.14%   |
| K10              | 5131      | 3.07%   |
| Piledriver       | 4437      | 2.66%   |
| Unknown          | 3864      | 2.32%   |
| Broadwell        | 3572      | 2.14%   |
| Zen              | 3249      | 1.95%   |
| TigerLake        | 3188      | 1.91%   |
| CometLake        | 2868      | 1.72%   |
| Zen 3            | 2824      | 1.69%   |
| K8 Hammer        | 2628      | 1.57%   |
| Bonnell          | 2139      | 1.28%   |
| Excavator        | 2045      | 1.23%   |
| Goldmont plus    | 1980      | 1.19%   |
| IceLake          | 1972      | 1.18%   |
| Nehalem          | 1838      | 1.1%    |
| NetBurst         | 1724      | 1.03%   |
| Bobcat           | 1543      | 0.92%   |
| Goldmont         | 1225      | 0.73%   |
| Puma             | 1171      | 0.7%    |
| P6               | 1010      | 0.61%   |
| K10 Llano        | 882       | 0.53%   |
| Jaguar           | 834       | 0.5%    |
| Steamroller      | 797       | 0.48%   |
| Bulldozer        | 657       | 0.39%   |
| Alderlake Hybrid | 477       | 0.29%   |
| K8 & K10 hybrid  | 338       | 0.2%    |
| Tremont          | 180       | 0.11%   |
| K6               | 62        | 0.04%   |
| Sapphire Rapids  | 3         | 0.002%  |
| CannonLake       | 2         | 0.001%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 92207     | 47.49%  |
| Nvidia                                       | 55663     | 28.67%  |
| AMD                                          | 44244     | 22.79%  |
| Matrox Electronics Systems                   | 770       | 0.4%    |
| ASPEED Technology                            | 524       | 0.27%   |
| Silicon Integrated Systems [SiS]             | 344       | 0.18%   |
| VIA Technologies                             | 239       | 0.12%   |
| ATI Technologies                             | 67        | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 30        | 0.02%   |
| S3 Graphics                                  | 24        | 0.01%   |
| Silicon Motion                               | 11        | 0.01%   |
| Huawei Technologies                          | 9         | 0.005%  |
| Zhaoxin                                      | 7         | 0.004%  |
| Neomagic                                     | 5         | 0.003%  |
| Trident Microsystems                         | 2         | 0.001%  |
| Phytium Technology                           | 2         | 0.001%  |
| Loongson Technology                          | 2         | 0.001%  |
| NVidia / SGS Thomson (Joint Venture)         | 1         | 0.001%  |
| Moore Threads Technology                     | 1         | 0.001%  |
| Dome Imaging Systems                         | 1         | 0.001%  |
| Conexant Systems                             | 1         | 0.001%  |
| Cirrus Logic                                 | 1         | 0.001%  |
| Alliance Semiconductor                       | 1         | 0.001%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9974      | 4.95%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7286      | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4048      | 2.01%   |
| Intel UHD Graphics 620                                                                   | 4018      | 1.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3442      | 1.71%   |
| Intel HD Graphics 620                                                                    | 3247      | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3177      | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3163      | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3125      | 1.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3069      | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3055      | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2921      | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2878      | 1.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2875      | 1.43%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2869      | 1.42%   |
| Intel HD Graphics 5500                                                                   | 2611      | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2557      | 1.27%   |
| AMD Renoir                                                                               | 2481      | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2458      | 1.22%   |
| Intel HD Graphics 630                                                                    | 2146      | 1.06%   |
| Intel HD Graphics 530                                                                    | 2115      | 1.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2103      | 1.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 1807      | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1665      | 0.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1587      | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1587      | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1552      | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1540      | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1500      | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1484      | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1420      | 0.7%    |
| AMD Cezanne                                                                              | 1309      | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 1291      | 0.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1241      | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1200      | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1198      | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1191      | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1117      | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1063      | 0.53%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1046      | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 66424     | 39.54%  |
| 1 x AMD                           | 34571     | 20.58%  |
| 1 x Nvidia                        | 33717     | 20.07%  |
| Intel + Nvidia                    | 19415     | 11.56%  |
| Intel + AMD                       | 4625      | 2.75%   |
| 2 x AMD                           | 3176      | 1.89%   |
| AMD + Nvidia                      | 1872      | 1.11%   |
| Other                             | 1584      | 0.94%   |
| 1 x Matrox                        | 661       | 0.39%   |
| 2 x Nvidia                        | 429       | 0.26%   |
| 1 x ASPEED                        | 377       | 0.22%   |
| 1 x SiS                           | 343       | 0.2%    |
| 1 x VIA                           | 237       | 0.14%   |
| Nvidia + ASPEED                   | 111       | 0.07%   |
| Nvidia + Matrox                   | 71        | 0.04%   |
| 2 x Intel                         | 62        | 0.04%   |
| AMD + Matrox                      | 35        | 0.02%   |
| Intel + 2 x Nvidia                | 32        | 0.02%   |
| AMD + ASPEED                      | 29        | 0.02%   |
| 1 x XGI                           | 24        | 0.01%   |
| 1 x S3 Graphics                   | 21        | 0.01%   |
| Intel + AMD + 1 x Nvidia          | 19        | 0.01%   |
| 3 x AMD                           | 15        | 0.01%   |
| Intel + 2 x AMD                   | 12        | 0.01%   |
| 3 x Nvidia                        | 11        | 0.01%   |
| 2 x AMD + 1 x Nvidia              | 10        | 0.01%   |
| 1 x Silicon Motion                | 8         | 0.005%  |
| 1 x Huawei Technologies           | 8         | 0.005%  |
| AMD + 2 x Nvidia                  | 8         | 0.005%  |
| 2 x Nvidia + 1 x ASPEED           | 6         | 0.004%  |
| 1 x Zhaoxin                       | 6         | 0.004%  |
| 1 x Neomagic                      | 5         | 0.003%  |
| 2 x Nvidia + 1 x Matrox           | 4         | 0.002%  |
| Nvidia + XGI                      | 3         | 0.002%  |
| 1 x Intel + 3 x Nvidia            | 3         | 0.002%  |
| AMD + XGI                         | 3         | 0.002%  |
| 4 x Nvidia                        | 2         | 0.001%  |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 2         | 0.001%  |
| 1 x Trident Microsystems          | 2         | 0.001%  |
| 1 x Phytium Technology            | 2         | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 133766    | 78.63%  |
| Proprietary | 27714     | 16.29%  |
| Unknown     | 8641      | 5.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 84943     | 49.22%  |
| 1.01-2.0   | 26472     | 15.34%  |
| 0.01-0.5   | 23884     | 13.84%  |
| 0.51-1.0   | 15147     | 8.78%   |
| 3.01-4.0   | 10847     | 6.29%   |
| 7.01-8.0   | 5548      | 3.21%   |
| 5.01-6.0   | 3164      | 1.83%   |
| 8.01-16.0  | 1273      | 0.74%   |
| 2.01-3.0   | 1110      | 0.64%   |
| 16.01-24.0 | 121       | 0.07%   |
| 4.01-5.0   | 47        | 0.03%   |
| 32.01-64.0 | 8         | 0.005%  |
| 24.01-32.0 | 6         | 0.003%  |
| 0          | 2         | 0.001%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24889     | 14.06%  |
| AU Optronics            | 20537     | 11.6%   |
| LG Display              | 15784     | 8.91%   |
| Chimei Innolux          | 12651     | 7.14%   |
| BOE                     | 12191     | 6.88%   |
| Goldstar                | 10443     | 5.9%    |
| Dell                    | 9626      | 5.44%   |
| Acer                    | 6657      | 3.76%   |
| Hewlett-Packard         | 5731      | 3.24%   |
| BenQ                    | 4557      | 2.57%   |
| AOC                     | 4210      | 2.38%   |
| Philips                 | 4142      | 2.34%   |
| Ancor Communications    | 3941      | 2.23%   |
| Chi Mei Optoelectronics | 3423      | 1.93%   |
| Lenovo                  | 3170      | 1.79%   |
| Apple                   | 3159      | 1.78%   |
| Sharp                   | 2732      | 1.54%   |
| ViewSonic               | 2181      | 1.23%   |
| Iiyama                  | 1564      | 0.88%   |
| Sony                    | 1366      | 0.77%   |
| PANDA                   | 1329      | 0.75%   |
| LG Philips              | 1259      | 0.71%   |
| Unknown                 | 1130      | 0.64%   |
| InfoVision              | 1085      | 0.61%   |
| ASUSTek Computer        | 1073      | 0.61%   |
| LG Electronics          | 1049      | 0.59%   |
| HannStar                | 978       | 0.55%   |
| NEC Computers           | 883       | 0.5%    |
| Eizo                    | 633       | 0.36%   |
| CPT                     | 603       | 0.34%   |
| Fujitsu Siemens         | 587       | 0.33%   |
| Panasonic               | 558       | 0.32%   |
| Toshiba                 | 541       | 0.31%   |
| Vizio                   | 494       | 0.28%   |
| Sceptre Tech            | 364       | 0.21%   |
| MSI                     | 359       | 0.2%    |
| Medion                  | 335       | 0.19%   |
| CSO                     | 309       | 0.17%   |
| Vestel Elektronik       | 258       | 0.15%   |
| InnoLux Display         | 241       | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 891       | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 859       | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 804       | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 761       | 0.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 714       | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 704       | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 692       | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 578       | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 542       | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 523       | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 511       | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 510       | 0.28%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 474       | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 450       | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 399       | 0.22%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 383       | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 355       | 0.19%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 342       | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 331       | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 331       | 0.18%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 317       | 0.17%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 305       | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 301       | 0.16%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 295       | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 294       | 0.16%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 291       | 0.16%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 288       | 0.16%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 280       | 0.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 280       | 0.15%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 278       | 0.15%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 277       | 0.15%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 272       | 0.15%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 272       | 0.15%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 268       | 0.15%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 267       | 0.15%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 266       | 0.15%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 262       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 261       | 0.14%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 258       | 0.14%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 250       | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 67680     | 39.58%  |
| 1366x768 (WXGA)    | 36875     | 21.56%  |
| 1280x1024 (SXGA)   | 8513      | 4.98%   |
| 3840x2160 (4K)     | 8466      | 4.95%   |
| 1600x900 (HD+)     | 8081      | 4.73%   |
| 2560x1440 (QHD)    | 5737      | 3.36%   |
| 1280x800 (WXGA)    | 5364      | 3.14%   |
| 1680x1050 (WSXGA+) | 5306      | 3.1%    |
| 1440x900 (WXGA+)   | 4989      | 2.92%   |
| 1920x1200 (WUXGA)  | 3550      | 2.08%   |
| Unknown            | 1980      | 1.16%   |
| 1360x768           | 1669      | 0.98%   |
| 2560x1080          | 1437      | 0.84%   |
| 1024x600           | 1213      | 0.71%   |
| 3440x1440          | 1181      | 0.69%   |
| 1024x768 (XGA)     | 1008      | 0.59%   |
| 3840x1080          | 815       | 0.48%   |
| 2560x1600          | 728       | 0.43%   |
| 1920x540           | 585       | 0.34%   |
| 1600x1200          | 533       | 0.31%   |
| 2880x1800          | 392       | 0.23%   |
| 2160x1440          | 339       | 0.2%    |
| 3840x2400          | 336       | 0.2%    |
| 1280x720 (HD)      | 311       | 0.18%   |
| 800x1280           | 293       | 0.17%   |
| 3200x1800 (QHD+)   | 289       | 0.17%   |
| 2736x1824          | 198       | 0.12%   |
| 2288x1287          | 162       | 0.09%   |
| 1400x1050          | 145       | 0.08%   |
| 2256x1504          | 129       | 0.08%   |
| 3000x2000          | 120       | 0.07%   |
| 3840x1600          | 113       | 0.07%   |
| 2048x1152          | 102       | 0.06%   |
| 3840x1200          | 101       | 0.06%   |
| 4480x1440          | 96        | 0.06%   |
| 1920x1280          | 94        | 0.05%   |
| 1680x945           | 89        | 0.05%   |
| 1280x960           | 86        | 0.05%   |
| 3200x1080          | 80        | 0.05%   |
| 5760x1080          | 78        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46591     | 26.37%  |
| 13      | 14567     | 8.24%   |
| 14      | 11911     | 6.74%   |
| 17      | 11533     | 6.53%   |
| 24      | 11220     | 6.35%   |
| 23      | 11198     | 6.34%   |
| 27      | 10724     | 6.07%   |
| 21      | 10385     | 5.88%   |
| Unknown | 8774      | 4.97%   |
| 19      | 7026      | 3.98%   |
| 18      | 4309      | 2.44%   |
| 20      | 3347      | 1.89%   |
| 22      | 3328      | 1.88%   |
| 31      | 2961      | 1.68%   |
| 12      | 2860      | 1.62%   |
| 11      | 2291      | 1.3%    |
| 34      | 2144      | 1.21%   |
| 10      | 1449      | 0.82%   |
| 84      | 1098      | 0.62%   |
| 72      | 988       | 0.56%   |
| 32      | 889       | 0.5%    |
| 16      | 776       | 0.44%   |
| 54      | 751       | 0.43%   |
| 40      | 632       | 0.36%   |
| 25      | 629       | 0.36%   |
| 26      | 501       | 0.28%   |
| 52      | 302       | 0.17%   |
| 48      | 286       | 0.16%   |
| 46      | 283       | 0.16%   |
| 28      | 262       | 0.15%   |
| 37      | 223       | 0.13%   |
| 65      | 199       | 0.11%   |
| 29      | 196       | 0.11%   |
| 42      | 194       | 0.11%   |
| 49      | 193       | 0.11%   |
| 33      | 157       | 0.09%   |
| 39      | 145       | 0.08%   |
| 43      | 130       | 0.07%   |
| 47      | 129       | 0.07%   |
| 8       | 113       | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 68402     | 39.33%  |
| 501-600        | 30969     | 17.81%  |
| 401-500        | 23860     | 13.72%  |
| 201-300        | 14063     | 8.09%   |
| 351-400        | 13445     | 7.73%   |
| Unknown        | 8774      | 5.04%   |
| 601-700        | 4662      | 2.68%   |
| 701-800        | 3230      | 1.86%   |
| 1001-1500      | 2456      | 1.41%   |
| 1501-2000      | 2245      | 1.29%   |
| 801-900        | 1108      | 0.64%   |
| 901-1000       | 437       | 0.25%   |
| 101-200        | 137       | 0.08%   |
| More than 2000 | 103       | 0.06%   |
| 1-100          | 24        | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 118702    | 73.29%  |
| 16/10   | 20375     | 12.58%  |
| 5/4     | 7901      | 4.88%   |
| Unknown | 7222      | 4.46%   |
| 21/9    | 2507      | 1.55%   |
| 4/3     | 2404      | 1.48%   |
| 3/2     | 1624      | 1%      |
| 32/9    | 340       | 0.21%   |
| 6/5     | 295       | 0.18%   |
| 0.62    | 295       | 0.18%   |
| 1.00    | 104       | 0.06%   |
| 1.96    | 57        | 0.04%   |
| 0.45    | 22        | 0.01%   |
| 3.40    | 18        | 0.01%   |
| 3.20    | 17        | 0.01%   |
| 0.67    | 17        | 0.01%   |
| 3.73    | 11        | 0.01%   |
| 2.65    | 9         | 0.01%   |
| 2.00    | 5         | 0.003%  |
| 0.80    | 4         | 0.002%  |
| 0.58    | 4         | 0.002%  |
| 0.56    | 4         | 0.002%  |
| 11/10   | 3         | 0.002%  |
| 1.98    | 3         | 0.002%  |
| 2.01    | 2         | 0.001%  |
| 1.03    | 2         | 0.001%  |
| 0.75    | 2         | 0.001%  |
| 3.88    | 1         | 0.001%  |
| 3.76    | 1         | 0.001%  |
| 2.50    | 1         | 0.001%  |
| 2.21    | 1         | 0.001%  |
| 2.12    | 1         | 0.001%  |
| 0.89    | 1         | 0.001%  |
| 0.65    | 1         | 0.001%  |
| 0.57    | 1         | 0.001%  |
| 0.31    | 1         | 0.001%  |
| 0.00    | 1         | 0.001%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 46151     | 26.34%  |
| 201-250        | 29081     | 16.6%   |
| 81-90          | 20550     | 11.73%  |
| 151-200        | 13631     | 7.78%   |
| 301-350        | 11066     | 6.32%   |
| Unknown        | 8775      | 5.01%   |
| 141-150        | 7364      | 4.2%    |
| 351-500        | 6422      | 3.67%   |
| 121-130        | 6297      | 3.59%   |
| 71-80          | 5950      | 3.4%    |
| 251-300        | 4377      | 2.5%    |
| More than 1000 | 4118      | 2.35%   |
| 61-70          | 2540      | 1.45%   |
| 51-60          | 2329      | 1.33%   |
| 501-1000       | 2217      | 1.27%   |
| 41-50          | 1437      | 0.82%   |
| 131-140        | 1421      | 0.81%   |
| 111-120        | 836       | 0.48%   |
| 91-100         | 504       | 0.29%   |
| 1-40           | 157       | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 60445     | 35.43%  |
| 101-120       | 49432     | 28.98%  |
| 121-160       | 37625     | 22.06%  |
| Unknown       | 8775      | 5.14%   |
| 161-240       | 7224      | 4.23%   |
| 1-50          | 4146      | 2.43%   |
| More than 240 | 2944      | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 137997    | 80.96%  |
| 2     | 22056     | 12.94%  |
| 0     | 7948      | 4.66%   |
| 3     | 2252      | 1.32%   |
| 4     | 187       | 0.11%   |
| 5     | 11        | 0.01%   |
| 6     | 6         | 0.004%  |
| 7     | 1         | 0.001%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 91660     | 36.45%  |
| Intel                             | 69165     | 27.5%   |
| Qualcomm Atheros                  | 33832     | 13.45%  |
| Broadcom                          | 15431     | 6.14%   |
| Broadcom Limited                  | 3833      | 1.52%   |
| Marvell Technology Group          | 3812      | 1.52%   |
| Nvidia                            | 3758      | 1.49%   |
| Ralink Technology                 | 3544      | 1.41%   |
| Ralink                            | 3136      | 1.25%   |
| TP-Link                           | 2316      | 0.92%   |
| MediaTek                          | 1454      | 0.58%   |
| Huawei Technologies               | 1281      | 0.51%   |
| Samsung Electronics               | 1153      | 0.46%   |
| Qualcomm Atheros Communications   | 1046      | 0.42%   |
| ASIX Electronics                  | 898       | 0.36%   |
| D-Link                            | 726       | 0.29%   |
| D-Link System                     | 678       | 0.27%   |
| NetGear                           | 672       | 0.27%   |
| VIA Technologies                  | 670       | 0.27%   |
| Xiaomi                            | 659       | 0.26%   |
| ASUSTek Computer                  | 634       | 0.25%   |
| JMicron Technology                | 619       | 0.25%   |
| Dell                              | 614       | 0.24%   |
| Microsoft                         | 561       | 0.22%   |
| Sierra Wireless                   | 502       | 0.2%    |
| Ericsson Business Mobile Networks | 495       | 0.2%    |
| Lenovo                            | 452       | 0.18%   |
| DisplayLink                       | 448       | 0.18%   |
| Silicon Integrated Systems [SiS]  | 439       | 0.17%   |
| Aquantia                          | 383       | 0.15%   |
| Hewlett-Packard                   | 373       | 0.15%   |
| Edimax Technology                 | 317       | 0.13%   |
| Qualcomm                          | 307       | 0.12%   |
| Linksys                           | 277       | 0.11%   |
| Attansic Technology               | 257       | 0.1%    |
| Belkin Components                 | 243       | 0.1%    |
| Motorola PCS                      | 228       | 0.09%   |
| ZTE WCDMA Technologies MSM        | 220       | 0.09%   |
| Microchip Technology              | 194       | 0.08%   |
| Apple                             | 156       | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 63118     | 21.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13097     | 4.49%   |
| Intel Wi-Fi 6 AX200                                                     | 5977      | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5717      | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4902      | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4509      | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4399      | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4066      | 1.39%   |
| Intel Wireless 8265 / 8275                                              | 3941      | 1.35%   |
| Intel I211 Gigabit Network Connection                                   | 3445      | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3133      | 1.07%   |
| Intel Wireless 7260                                                     | 3061      | 1.05%   |
| Intel Wireless 7265                                                     | 3057      | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2848      | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2514      | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2432      | 0.83%   |
| Intel Wi-Fi 6 AX201                                                     | 2410      | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2299      | 0.79%   |
| Intel Wireless 8260                                                     | 2274      | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                    | 2262      | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2191      | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2120      | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2107      | 0.72%   |
| Intel Wireless 3165                                                     | 2090      | 0.72%   |
| Intel Ethernet Connection I217-LM                                       | 1979      | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1974      | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1897      | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1857      | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1838      | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1792      | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1762      | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 1637      | 0.56%   |
| Intel 82579V Gigabit Network Connection                                 | 1556      | 0.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1494      | 0.51%   |
| Nvidia MCP61 Ethernet                                                   | 1479      | 0.51%   |
| Ralink MT7601U Wireless Adapter                                         | 1458      | 0.5%    |
| Intel Wireless-AC 9260                                                  | 1429      | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1416      | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1345      | 0.46%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1340      | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 50639     | 39.75%  |
| Qualcomm Atheros                      | 26420     | 20.74%  |
| Realtek Semiconductor                 | 20630     | 16.19%  |
| Broadcom                              | 10253     | 8.05%   |
| Ralink Technology                     | 3544      | 2.78%   |
| Ralink                                | 3134      | 2.46%   |
| Broadcom Limited                      | 2242      | 1.76%   |
| TP-Link                               | 2087      | 1.64%   |
| MediaTek                              | 1184      | 0.93%   |
| Qualcomm Atheros Communications       | 1046      | 0.82%   |
| D-Link                                | 673       | 0.53%   |
| NetGear                               | 652       | 0.51%   |
| ASUSTek Computer                      | 597       | 0.47%   |
| Sierra Wireless                       | 502       | 0.39%   |
| Microsoft                             | 488       | 0.38%   |
| D-Link System                         | 420       | 0.33%   |
| Dell                                  | 350       | 0.27%   |
| Marvell Technology Group              | 339       | 0.27%   |
| Edimax Technology                     | 317       | 0.25%   |
| Linksys                               | 257       | 0.2%    |
| Belkin Components                     | 236       | 0.19%   |
| IMC Networks                          | 150       | 0.12%   |
| FIBOCOM                               | 124       | 0.1%    |
| Qualcomm                              | 120       | 0.09%   |
| AVM                                   | 111       | 0.09%   |
| Hewlett-Packard                       | 83        | 0.07%   |
| Sitecom Europe                        | 73        | 0.06%   |
| Gemtek                                | 59        | 0.05%   |
| ZyXEL Communications                  | 58        | 0.05%   |
| ZyDAS                                 | 57        | 0.04%   |
| Micro Star International              | 48        | 0.04%   |
| BUFFALO                               | 44        | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 44        | 0.03%   |
| Mercucys                              | 43        | 0.03%   |
| Wilocity                              | 32        | 0.03%   |
| TRENDnet                              | 26        | 0.02%   |
| Tenda                                 | 23        | 0.02%   |
| Xiaomi                                | 22        | 0.02%   |
| Wacom                                 | 21        | 0.02%   |
| Accton Technology                     | 21        | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 5977      | 4.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4902      | 3.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4509      | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4399      | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4066      | 3.17%   |
| Intel Wireless 8265 / 8275                                              | 3941      | 3.07%   |
| Intel Wireless 7260                                                     | 3061      | 2.38%   |
| Intel Wireless 7265                                                     | 3057      | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2848      | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2514      | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2432      | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 2410      | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2299      | 1.79%   |
| Intel Wireless 8260                                                     | 2274      | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2191      | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2120      | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2107      | 1.64%   |
| Intel Wireless 3165                                                     | 2090      | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1897      | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1792      | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1762      | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1637      | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1494      | 1.16%   |
| Ralink MT7601U Wireless Adapter                                         | 1458      | 1.14%   |
| Intel Wireless-AC 9260                                                  | 1429      | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1416      | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1345      | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1340      | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1328      | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1284      | 1%      |
| Intel Wireless 3160                                                     | 1230      | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1176      | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1000      | 0.78%   |
| Intel WiFi Link 5100                                                    | 995       | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 935       | 0.73%   |
| Intel Centrino Ultimate-N 6300                                          | 935       | 0.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 932       | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 911       | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                         | 879       | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 840       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 83629     | 53.38%  |
| Intel                             | 36091     | 23.04%  |
| Qualcomm Atheros                  | 10961     | 7%      |
| Broadcom                          | 6979      | 4.45%   |
| Nvidia                            | 3748      | 2.39%   |
| Marvell Technology Group          | 3475      | 2.22%   |
| Broadcom Limited                  | 1662      | 1.06%   |
| Samsung Electronics               | 1126      | 0.72%   |
| ASIX Electronics                  | 898       | 0.57%   |
| VIA Technologies                  | 651       | 0.42%   |
| Xiaomi                            | 636       | 0.41%   |
| JMicron Technology                | 619       | 0.4%    |
| Huawei Technologies               | 602       | 0.38%   |
| DisplayLink                       | 448       | 0.29%   |
| Lenovo                            | 443       | 0.28%   |
| Silicon Integrated Systems [SiS]  | 428       | 0.27%   |
| Aquantia                          | 383       | 0.24%   |
| D-Link System                     | 259       | 0.17%   |
| Attansic Technology               | 257       | 0.16%   |
| MediaTek                          | 253       | 0.16%   |
| TP-Link                           | 233       | 0.15%   |
| ZTE WCDMA Technologies MSM        | 196       | 0.13%   |
| Qualcomm                          | 178       | 0.11%   |
| Motorola PCS                      | 157       | 0.1%    |
| Google                            | 149       | 0.1%    |
| Apple                             | 147       | 0.09%   |
| Microchip Technology              | 130       | 0.08%   |
| ICS Advent                        | 125       | 0.08%   |
| 3Com                              | 120       | 0.08%   |
| OPPO Electronics                  | 112       | 0.07%   |
| Sundance Technology Inc / IC Plus | 106       | 0.07%   |
| Mellanox Technologies             | 98        | 0.06%   |
| Hewlett-Packard                   | 90        | 0.06%   |
| OnePlus                           | 74        | 0.05%   |
| HTC (High Tech Computer)          | 67        | 0.04%   |
| Microsoft                         | 66        | 0.04%   |
| IBM                               | 60        | 0.04%   |
| HMD Global                        | 55        | 0.04%   |
| T & A Mobile Phones               | 54        | 0.03%   |
| LG Electronics                    | 54        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63118     | 39.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13097     | 8.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5717      | 3.58%   |
| Intel I211 Gigabit Network Connection                             | 3445      | 2.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3133      | 1.96%   |
| Intel Ethernet Connection (2) I219-V                              | 2262      | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 1979      | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1973      | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1857      | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1838      | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 1556      | 0.97%   |
| Nvidia MCP61 Ethernet                                             | 1479      | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 1169      | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 1107      | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1024      | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 956       | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 911       | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 909       | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 901       | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 894       | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 893       | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 885       | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 875       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 840       | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 830       | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 811       | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 807       | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 806       | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 793       | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 788       | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 767       | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 744       | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 743       | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 740       | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 735       | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 725       | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 721       | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 697       | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 671       | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 666       | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 147267    | 54.27%  |
| WiFi     | 120702    | 44.48%  |
| Modem    | 2954      | 1.09%   |
| Unknown  | 426       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 93670     | 54.53%  |
| Ethernet | 78007     | 45.41%  |
| Unknown  | 67        | 0.04%   |
| Modem    | 27        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 91106     | 54.46%  |
| 1     | 68398     | 40.89%  |
| 0     | 3740      | 2.24%   |
| 3     | 2930      | 1.75%   |
| 4     | 696       | 0.42%   |
| 6     | 147       | 0.09%   |
| 5     | 145       | 0.09%   |
| 8     | 47        | 0.03%   |
| 7     | 21        | 0.01%   |
| 10    | 15        | 0.01%   |
| 12    | 9         | 0.01%   |
| 9     | 5         | 0.003%  |
| 18    | 3         | 0.002%  |
| 13    | 3         | 0.002%  |
| 14    | 2         | 0.001%  |
| 132   | 1         | 0.001%  |
| 66    | 1         | 0.001%  |
| 33    | 1         | 0.001%  |
| 32    | 1         | 0.001%  |
| 22    | 1         | 0.001%  |
| 21    | 1         | 0.001%  |
| 20    | 1         | 0.001%  |
| 17    | 1         | 0.001%  |
| 16    | 1         | 0.001%  |
| 11    | 1         | 0.001%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 140240    | 82.25%  |
| Yes     | 22197     | 13.02%  |
| Unknown | 8071      | 4.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38431     | 42.62%  |
| Qualcomm Atheros Communications | 8673      | 9.62%   |
| Realtek Semiconductor           | 8305      | 9.21%   |
| Cambridge Silicon Radio         | 5828      | 6.46%   |
| Broadcom                        | 5650      | 6.27%   |
| IMC Networks                    | 4113      | 4.56%   |
| Lite-On Technology              | 3741      | 4.15%   |
| Apple                           | 3340      | 3.7%    |
| Foxconn / Hon Hai               | 2653      | 2.94%   |
| ASUSTek Computer                | 1791      | 1.99%   |
| Dell                            | 1499      | 1.66%   |
| Hewlett-Packard                 | 1191      | 1.32%   |
| Ralink                          | 935       | 1.04%   |
| Toshiba                         | 887       | 0.98%   |
| Realtek                         | 459       | 0.51%   |
| Foxconn International           | 414       | 0.46%   |
| Marvell Semiconductor           | 309       | 0.34%   |
| Alps Electric                   | 298       | 0.33%   |
| Ralink Technology               | 227       | 0.25%   |
| MediaTek                        | 193       | 0.21%   |
| Integrated System Solution      | 170       | 0.19%   |
| Belkin Components               | 94        | 0.1%    |
| Askey Computer                  | 90        | 0.1%    |
| Dynex                           | 87        | 0.1%    |
| Chicony Electronics             | 83        | 0.09%   |
| Micro Star International        | 78        | 0.09%   |
| Edimax Technology               | 70        | 0.08%   |
| TP-Link                         | 67        | 0.07%   |
| Taiyo Yuden                     | 63        | 0.07%   |
| Qcom                            | 56        | 0.06%   |
| HTC (High Tech Computer)        | 51        | 0.06%   |
| Unknown                         | 50        | 0.06%   |
| Logitech                        | 37        | 0.04%   |
| Conwise Technology              | 34        | 0.04%   |
| USI                             | 30        | 0.03%   |
| Fujitsu                         | 20        | 0.02%   |
| Opticis                         | 19        | 0.02%   |
| Roper                           | 14        | 0.02%   |
| Primax Electronics              | 14        | 0.02%   |
| D-Link System                   | 13        | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15246     | 16.89%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5827      | 6.46%   |
| Intel AX200 Bluetooth                               | 5688      | 6.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5602      | 6.21%   |
| Intel AX201 Bluetooth                               | 5591      | 6.19%   |
| Realtek Bluetooth Radio                             | 4679      | 5.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 3736      | 4.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2354      | 2.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1701      | 1.88%   |
| IMC Networks Bluetooth Radio                        | 1553      | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1511      | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1489      | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1349      | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1327      | 1.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1319      | 1.46%   |
| IMC Networks Bluetooth Device                       | 1147      | 1.27%   |
| Apple Bluetooth Host Controller                     | 1068      | 1.18%   |
| Apple Bluetooth USB Host Controller                 | 1032      | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                  | 994       | 1.1%    |
| Lite-On Bluetooth Device                            | 992       | 1.1%    |
| Ralink RT3290 Bluetooth                             | 935       | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 844       | 0.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 769       | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 767       | 0.85%   |
| Intel AX210 Bluetooth                               | 747       | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 721       | 0.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 720       | 0.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 703       | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 603       | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 563       | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 527       | 0.58%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 510       | 0.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 500       | 0.55%   |
| Dell DW375 Bluetooth Module                         | 491       | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 488       | 0.54%   |
| Realtek Bluetooth Radio                             | 459       | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 457       | 0.51%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 413       | 0.46%   |
| Foxconn International BCM43142A0 Bluetooth module   | 412       | 0.46%   |
| Broadcom BCM2045 Bluetooth                          | 388       | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 118692    | 52.88%  |
| AMD                              | 46392     | 20.67%  |
| Nvidia                           | 38844     | 17.31%  |
| C-Media Electronics              | 3602      | 1.6%    |
| Creative Labs                    | 1679      | 0.75%   |
| Logitech                         | 1497      | 0.67%   |
| Texas Instruments                | 748       | 0.33%   |
| JMTek                            | 672       | 0.3%    |
| VIA Technologies                 | 670       | 0.3%    |
| Realtek Semiconductor            | 620       | 0.28%   |
| GN Netcom                        | 564       | 0.25%   |
| Creative Technology              | 551       | 0.25%   |
| Silicon Integrated Systems [SiS] | 538       | 0.24%   |
| Kingston Technology              | 499       | 0.22%   |
| Generalplus Technology           | 479       | 0.21%   |
| Plantronics                      | 454       | 0.2%    |
| Lenovo                           | 430       | 0.19%   |
| Focusrite-Novation               | 396       | 0.18%   |
| Corsair                          | 378       | 0.17%   |
| Razer USA                        | 369       | 0.16%   |
| SteelSeries ApS                  | 359       | 0.16%   |
| ASUSTek Computer                 | 284       | 0.13%   |
| Blue Microphones                 | 239       | 0.11%   |
| Sennheiser Communications        | 186       | 0.08%   |
| Apple                            | 174       | 0.08%   |
| Tenx Technology                  | 171       | 0.08%   |
| Samson Technologies              | 150       | 0.07%   |
| Hewlett-Packard                  | 149       | 0.07%   |
| BEHRINGER International          | 147       | 0.07%   |
| Dell                             | 145       | 0.06%   |
| Sony                             | 144       | 0.06%   |
| M-Audio                          | 138       | 0.06%   |
| GYROCOM C&C                      | 135       | 0.06%   |
| Yamaha                           | 125       | 0.06%   |
| Microsoft                        | 117       | 0.05%   |
| RODE Microphones                 | 106       | 0.05%   |
| XMOS                             | 105       | 0.05%   |
| SAVITECH                         | 91        | 0.04%   |
| Micro Star International         | 77        | 0.03%   |
| Cambridge Silicon Radio          | 76        | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12924     | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12474     | 4.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 11606     | 4.39%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9664      | 3.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 8615      | 3.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7884      | 2.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7792      | 2.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6345      | 2.4%    |
| AMD FCH Azalia Controller                                                  | 6198      | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6029      | 2.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5743      | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 5585      | 2.11%   |
| AMD Starship/Matisse HD Audio Controller                                   | 4854      | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4370      | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4354      | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4140      | 1.57%   |
| Intel 8 Series HD Audio Controller                                         | 4111      | 1.55%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4086      | 1.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3511      | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 3289      | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3267      | 1.24%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3249      | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3208      | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3183      | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                            | 3170      | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 2959      | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2895      | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 2830      | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2723      | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 2646      | 1%      |
| Nvidia High Definition Audio Controller                                    | 2627      | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2376      | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2332      | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2110      | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2110      | 0.8%    |
| Nvidia GP106 High Definition Audio Controller                              | 1974      | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1971      | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1966      | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 1829      | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1809      | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21516     | 19.65%  |
| SK hynix            | 17545     | 16.02%  |
| Unknown             | 17410     | 15.9%   |
| Kingston            | 13495     | 12.32%  |
| Micron Technology   | 8559      | 7.82%   |
| Crucial             | 5856      | 5.35%   |
| Corsair             | 4982      | 4.55%   |
| G.Skill             | 3019      | 2.76%   |
| Elpida              | 2105      | 1.92%   |
| A-DATA Technology   | 2090      | 1.91%   |
| Ramaxel Technology  | 1904      | 1.74%   |
| Nanya Technology    | 1713      | 1.56%   |
| Patriot             | 856       | 0.78%   |
| Unknown (ABCD)      | 668       | 0.61%   |
| Team                | 633       | 0.58%   |
| Smart               | 605       | 0.55%   |
| Transcend           | 505       | 0.46%   |
| Goodram             | 425       | 0.39%   |
| AMD                 | 419       | 0.38%   |
| Unknown             | 392       | 0.36%   |
| ASint Technology    | 301       | 0.27%   |
| Apacer              | 267       | 0.24%   |
| Goldkey             | 250       | 0.23%   |
| Kingmax             | 217       | 0.2%    |
| Silicon Power       | 216       | 0.2%    |
| Qimonda             | 181       | 0.17%   |
| 48spaces            | 173       | 0.16%   |
| Teikon              | 168       | 0.15%   |
| GeIL                | 139       | 0.13%   |
| Unifosa             | 134       | 0.12%   |
| PNY                 | 129       | 0.12%   |
| Avant               | 125       | 0.11%   |
| SHARETRONIC         | 113       | 0.1%    |
| Qumo                | 104       | 0.09%   |
| Smart Brazil        | 91        | 0.08%   |
| Kllisre             | 91        | 0.08%   |
| Toshiba             | 84        | 0.08%   |
| CSX                 | 84        | 0.08%   |
| Foxline             | 76        | 0.07%   |
| Hewlett-Packard     | 69        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 835       | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 835       | 0.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 797       | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 736       | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 705       | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 672       | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 638       | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 632       | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 616       | 0.51%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 612       | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 570       | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 568       | 0.47%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 566       | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 564       | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 546       | 0.46%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 514       | 0.43%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 489       | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 482       | 0.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 466       | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 464       | 0.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 455       | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 439       | 0.37%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 432       | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 424       | 0.35%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 414       | 0.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 394       | 0.33%   |
| Unknown                                                          | 392       | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 388       | 0.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 376       | 0.31%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                      | 375       | 0.31%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 369       | 0.31%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 365       | 0.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 362       | 0.3%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 358       | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 351       | 0.29%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 350       | 0.29%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 338       | 0.28%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 318       | 0.27%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 313       | 0.26%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 303       | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 37079     | 38.99%  |
| DDR4         | 34136     | 35.9%   |
| DDR2         | 7930      | 8.34%   |
| Unknown      | 5309      | 5.58%   |
| SDRAM        | 4403      | 4.63%   |
| LPDDR4       | 2429      | 2.55%   |
| LPDDR3       | 1845      | 1.94%   |
| DDR          | 1312      | 1.38%   |
| DRAM         | 346       | 0.36%   |
| DDR5         | 176       | 0.19%   |
| LPDDR5       | 111       | 0.12%   |
| EEPROM       | 6         | 0.01%   |
| RAM          | 4         | 0.004%  |
| DDR2 FB-DIMM | 2         | 0.002%  |
| SRAM         | 1         | 0.001%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 50947     | 54.24%  |
| DIMM            | 38049     | 40.5%   |
| Row Of Chips    | 4190      | 4.46%   |
| Chip            | 390       | 0.42%   |
| Unknown         | 197       | 0.21%   |
| FB-DIMM         | 97        | 0.1%    |
| RIMM            | 66        | 0.07%   |
| Proprietary Car | 1         | 0.001%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 33230     | 31.56%  |
| 8192    | 30101     | 28.59%  |
| 2048    | 20341     | 19.32%  |
| 16384   | 10200     | 9.69%   |
| 1024    | 7670      | 7.28%   |
| 32768   | 1986      | 1.89%   |
| 512     | 1351      | 1.28%   |
| 256     | 260       | 0.25%   |
| 65536   | 59        | 0.06%   |
| 128     | 18        | 0.02%   |
| 1536    | 17        | 0.02%   |
| Unknown | 17        | 0.02%   |
| 64      | 7         | 0.01%   |
| 32      | 7         | 0.01%   |
| 16      | 7         | 0.01%   |
| 1       | 6         | 0.01%   |
| 3072    | 4         | 0.004%  |
| 129408  | 3         | 0.003%  |
| 6144    | 2         | 0.002%  |
| 258496  | 1         | 0.001%  |
| 131072  | 1         | 0.001%  |
| 32767   | 1         | 0.001%  |
| 232     | 1         | 0.001%  |
| 13      | 1         | 0.001%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 22941     | 22.14%  |
| 2667    | 12115     | 11.69%  |
| 1333    | 9654      | 9.32%   |
| 3200    | 9463      | 9.13%   |
| 2400    | 6714      | 6.48%   |
| 1334    | 4533      | 4.37%   |
| 800     | 4518      | 4.36%   |
| 2133    | 4502      | 4.34%   |
| 667     | 4309      | 4.16%   |
| Unknown | 4217      | 4.07%   |
| 3600    | 2003      | 1.93%   |
| 1867    | 1770      | 1.71%   |
| 1067    | 1575      | 1.52%   |
| 1066    | 1185      | 1.14%   |
| 4267    | 935       | 0.9%    |
| 3266    | 905       | 0.87%   |
| 4199    | 880       | 0.85%   |
| 533     | 874       | 0.84%   |
| 400     | 774       | 0.75%   |
| 1866    | 767       | 0.74%   |
| 3000    | 670       | 0.65%   |
| 2666    | 614       | 0.59%   |
| 3400    | 613       | 0.59%   |
| 2048    | 610       | 0.59%   |
| 3466    | 526       | 0.51%   |
| 2933    | 514       | 0.5%    |
| 333     | 452       | 0.44%   |
| 1800    | 384       | 0.37%   |
| 975     | 358       | 0.35%   |
| 3733    | 348       | 0.34%   |
| 8400    | 273       | 0.26%   |
| 3866    | 259       | 0.25%   |
| 2800    | 247       | 0.24%   |
| 4800    | 231       | 0.22%   |
| 3800    | 216       | 0.21%   |
| 4266    | 168       | 0.16%   |
| 1639    | 168       | 0.16%   |
| 266     | 167       | 0.16%   |
| 2000    | 131       | 0.13%   |
| 6400    | 117       | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 1979      | 34.87%  |
| Canon                           | 998       | 17.58%  |
| Brother Industries              | 817       | 14.39%  |
| Samsung Electronics             | 703       | 12.39%  |
| Seiko Epson                     | 506       | 8.91%   |
| Xerox                           | 88        | 1.55%   |
| Prolific Technology             | 80        | 1.41%   |
| Kyocera                         | 55        | 0.97%   |
| Dymo-CoStar                     | 50        | 0.88%   |
| QinHeng Electronics             | 49        | 0.86%   |
| Lexmark International           | 49        | 0.86%   |
| Pantum                          | 47        | 0.83%   |
| Panasonic (Matsushita)          | 47        | 0.83%   |
| Ricoh                           | 41        | 0.72%   |
| Zebra                           | 20        | 0.35%   |
| STMicroelectronics              | 17        | 0.3%    |
| Oki Data                        | 17        | 0.3%    |
| Dell                            | 15        | 0.26%   |
| Fuji Xerox                      | 11        | 0.19%   |
| Konica Minolta                  | 7         | 0.12%   |
| Apple                           | 7         | 0.12%   |
| TSC Auto ID Technology          | 6         | 0.11%   |
| Star Micronics                  | 4         | 0.07%   |
| NXP Semiconductors              | 4         | 0.07%   |
| Datamax-O'Neil                  | 4         | 0.07%   |
| Xiaomi                          | 3         | 0.05%   |
| WinChipHead                     | 3         | 0.05%   |
| Sharp                           | 3         | 0.05%   |
| MIIIW                           | 3         | 0.05%   |
| Magic Control Technology        | 3         | 0.05%   |
| ICS Advent                      | 3         | 0.05%   |
| Citizen                         | 3         | 0.05%   |
| cab Produkttechnik GmbH & Co KG | 3         | 0.05%   |
| ATEN International              | 3         | 0.05%   |
| Zhuhai Poskey Technology        | 2         | 0.04%   |
| Toshiba TEC                     | 2         | 0.04%   |
| Seiko Instruments               | 2         | 0.04%   |
| SAT                             | 2         | 0.04%   |
| GODEX INTERNATIONAL             | 2         | 0.04%   |
| Custom Engineering SPA          | 2         | 0.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1020                      | 118       | 2.05%   |
| HP LaserJet 1018                      | 82        | 1.43%   |
| Prolific PL2305 Parallel Port         | 80        | 1.39%   |
| Samsung M2020 Series                  | 66        | 1.15%   |
| HP DeskJet 2620 All-in-One Printer    | 65        | 1.13%   |
| Samsung SCX-4200 series               | 62        | 1.08%   |
| HP LaserJet P1102                     | 62        | 1.08%   |
| Seiko Epson Printer                   | 58        | 1.01%   |
| Brother Printer                       | 57        | 0.99%   |
| Canon PIXMA MG2500 Series             | 56        | 0.97%   |
| Samsung M2070 Series                  | 55        | 0.96%   |
| HP DeskJet 2130 series                | 55        | 0.96%   |
| Samsung SCX-3400 Series               | 51        | 0.89%   |
| Canon LBP2900                         | 51        | 0.89%   |
| QinHeng CH340S                        | 49        | 0.85%   |
| HP ENVY 4520 series                   | 48        | 0.83%   |
| HP LaserJet P1005                     | 46        | 0.8%    |
| Brother HL-2030 Laser Printer         | 43        | 0.75%   |
| HP LaserJet 1010                      | 41        | 0.71%   |
| HP DeskJet 3630 series                | 38        | 0.66%   |
| Samsung SCX-3200 Series               | 36        | 0.63%   |
| HP Deskjet 2050 J510                  | 36        | 0.63%   |
| Samsung ML-1640 Series Laser Printer  | 35        | 0.61%   |
| HP Deskjet 2540 series                | 34        | 0.59%   |
| Brother HL-1110 series                | 34        | 0.59%   |
| Canon PIXMA MX920 Series              | 33        | 0.57%   |
| Panasonic (Matsushita) KX-MB1520G     | 32        | 0.56%   |
| HP Deskjet 1050 J410                  | 32        | 0.56%   |
| Canon iP7200 series                   | 32        | 0.56%   |
| Samsung ML-216x Series Laser Printer  | 31        | 0.54%   |
| Canon PIXMA MG3600 Series             | 31        | 0.54%   |
| HP LaserJet 1200                      | 29        | 0.5%    |
| HP DeskJet 2700 series                | 29        | 0.5%    |
| Canon MF4410                          | 29        | 0.5%    |
| Canon MF3010                          | 29        | 0.5%    |
| HP LaserJet Professional P1102w       | 28        | 0.49%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 27        | 0.47%   |
| HP LaserJet Professional P 1102w      | 27        | 0.47%   |
| Canon CanoScan LiDE 300               | 27        | 0.47%   |
| HP LaserJet 1022                      | 26        | 0.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 669       | 50.95%  |
| Seiko Epson                                    | 280       | 21.33%  |
| Hewlett-Packard                                | 183       | 13.94%  |
| Mustek Systems                                 | 81        | 6.17%   |
| Ultima Electronics                             | 27        | 2.06%   |
| Acer Peripherals (now BenQ)                    | 23        | 1.75%   |
| AGFA-Gevaert NV                                | 14        | 1.07%   |
| KYE Systems (Mouse Systems)                    | 8         | 0.61%   |
| Plustek                                        | 7         | 0.53%   |
| Microtek International                         | 4         | 0.3%    |
| Fujitsu                                        | 4         | 0.3%    |
| Visioneer                                      | 2         | 0.15%   |
| UMAX                                           | 2         | 0.15%   |
| Canon Electronics                              | 2         | 0.15%   |
| Avision                                        | 2         | 0.15%   |
| Syscan                                         | 1         | 0.08%   |
| Siemens Information and Communication Products | 1         | 0.08%   |
| Papillon Systems                               | 1         | 0.08%   |
| Nikon                                          | 1         | 0.08%   |
| Minolta                                        | 1         | 0.08%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 103       | 7.82%   |
| Canon CanoScan LIDE 25                                                                | 84        | 6.38%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 72        | 5.47%   |
| Canon CanoScan LiDE 210                                                               | 68        | 5.16%   |
| Canon CanoScan LiDE 220                                                               | 59        | 4.48%   |
| Canon CanoScan LiDE 120                                                               | 48        | 3.64%   |
| HP ScanJet 2400c                                                                      | 36        | 2.73%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 36        | 2.73%   |
| Canon CanoScan LiDE 100                                                               | 36        | 2.73%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 26        | 1.97%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 25        | 1.9%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 24        | 1.82%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 23        | 1.75%   |
| Canon CanoScan LiDE 60                                                                | 22        | 1.67%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 21        | 1.59%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 19        | 1.44%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 19        | 1.44%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 18        | 1.37%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 18        | 1.37%   |
| Canon CanoScan LiDE 200                                                               | 17        | 1.29%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 14        | 1.06%   |
| Mustek Systems SNAPSCAN e22                                                           | 14        | 1.06%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 13        | 0.99%   |
| Canon CanoScan LiDE 700F                                                              | 13        | 0.99%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 12        | 0.91%   |
| Canon CanoScan N650U/N656U                                                            | 11        | 0.84%   |
| Canon CanoScan LiDE 90                                                                | 11        | 0.84%   |
| Seiko Epson Scanner                                                                   | 10        | 0.76%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 10        | 0.76%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 10        | 0.76%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 9         | 0.68%   |
| Canon CanoScan 4400F                                                                  | 9         | 0.68%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 8         | 0.61%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 8         | 0.61%   |
| HP ScanJet 5590                                                                       | 8         | 0.61%   |
| HP ScanJet 3800c                                                                      | 8         | 0.61%   |
| HP Scanjet 200                                                                        | 8         | 0.61%   |
| Canon CanoScan LiDE 600F                                                              | 8         | 0.61%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 7         | 0.53%   |
| HP ScanJet 3970c                                                                      | 7         | 0.53%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21092     | 21.89%  |
| IMC Networks                           | 8492      | 8.81%   |
| Microdia                               | 7940      | 8.24%   |
| Realtek Semiconductor                  | 7315      | 7.59%   |
| Acer                                   | 6909      | 7.17%   |
| Logitech                               | 5774      | 5.99%   |
| Sunplus Innovation Technology          | 4984      | 5.17%   |
| Quanta                                 | 3895      | 4.04%   |
| Suyin                                  | 3737      | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 3440      | 3.57%   |
| Apple                                  | 2646      | 2.75%   |
| Syntek                                 | 2205      | 2.29%   |
| Silicon Motion                         | 1904      | 1.98%   |
| Lite-On Technology                     | 1826      | 1.89%   |
| Alcor Micro                            | 1503      | 1.56%   |
| Z-Star Microelectronics                | 1394      | 1.45%   |
| Microsoft                              | 1081      | 1.12%   |
| Ricoh                                  | 967       | 1%      |
| Samsung Electronics                    | 937       | 0.97%   |
| Luxvisions Innotech Limited            | 744       | 0.77%   |
| Lenovo                                 | 565       | 0.59%   |
| ALi                                    | 441       | 0.46%   |
| Importek                               | 391       | 0.41%   |
| Primax Electronics                     | 329       | 0.34%   |
| Generalplus Technology                 | 325       | 0.34%   |
| KYE Systems (Mouse Systems)            | 315       | 0.33%   |
| GEMBIRD                                | 305       | 0.32%   |
| Cubeternet                             | 268       | 0.28%   |
| Creative Technology                    | 258       | 0.27%   |
| DigiTech                               | 248       | 0.26%   |
| Aveo Technology                        | 202       | 0.21%   |
| OmniVision Technologies                | 199       | 0.21%   |
| Pixart Imaging                         | 188       | 0.2%    |
| ARC International                      | 186       | 0.19%   |
| Arkmicro Technologies                  | 184       | 0.19%   |
| Sonix Technology                       | 180       | 0.19%   |
| Unknown                                | 173       | 0.18%   |
| Genesys Logic                          | 144       | 0.15%   |
| MacroSilicon                           | 140       | 0.15%   |
| Jieli Technology                       | 127       | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 3383      | 3.48%   |
| Microdia Integrated_Webcam_HD           | 2819      | 2.9%    |
| Realtek Integrated_Webcam_HD            | 2287      | 2.36%   |
| Chicony HD WebCam                       | 2072      | 2.13%   |
| IMC Networks Integrated Camera          | 1893      | 1.95%   |
| IMC Networks USB2.0 HD UVC WebCam       | 1770      | 1.82%   |
| Acer Integrated Camera                  | 1586      | 1.63%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1427      | 1.47%   |
| Logitech Webcam C270                    | 1406      | 1.45%   |
| Sunplus Integrated_Webcam_HD            | 1349      | 1.39%   |
| Syntek Integrated Camera                | 960       | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode) | 917       | 0.94%   |
| Acer Lenovo EasyCamera                  | 880       | 0.91%   |
| Logitech HD Pro Webcam C920             | 846       | 0.87%   |
| Apple iPhone 5/5C/5S/6/SE               | 811       | 0.84%   |
| Chicony USB 2.0 Camera                  | 797       | 0.82%   |
| Sunplus HD WebCam                       | 755       | 0.78%   |
| Chicony Lenovo EasyCamera               | 737       | 0.76%   |
| Apple Built-in iSight                   | 711       | 0.73%   |
| Chicony USB2.0 HD UVC WebCam            | 708       | 0.73%   |
| Microdia Integrated Webcam              | 697       | 0.72%   |
| Quanta HD User Facing                   | 688       | 0.71%   |
| Chicony HP Truevision HD                | 678       | 0.7%    |
| Chicony HP HD Camera                    | 669       | 0.69%   |
| Acer BisonCam, NB Pro                   | 650       | 0.67%   |
| Realtek USB Camera                      | 641       | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam           | 637       | 0.66%   |
| Lite-On Integrated Camera               | 628       | 0.65%   |
| Acer Lenovo Integrated Webcam           | 591       | 0.61%   |
| Chicony EasyCamera                      | 582       | 0.6%    |
| Chicony TOSHIBA Web Camera - HD         | 555       | 0.57%   |
| Chicony HD User Facing                  | 541       | 0.56%   |
| Chicony VGA WebCam                      | 527       | 0.54%   |
| Chicony USB2.0 Camera                   | 522       | 0.54%   |
| Apple FaceTime HD Camera (Built-in)     | 516       | 0.53%   |
| Chicony HP Truevision HD camera         | 500       | 0.52%   |
| Quanta HP TrueVision HD Camera          | 495       | 0.51%   |
| Acer EasyCamera                         | 495       | 0.51%   |
| Quanta VGA WebCam                       | 490       | 0.5%    |
| Microdia Laptop_Integrated_Webcam_HD    | 490       | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 5684      | 35.24%  |
| Synaptics                          | 4111      | 25.49%  |
| Shenzhen Goodix Technology         | 2054      | 12.73%  |
| AuthenTec                          | 1243      | 7.71%   |
| Upek                               | 996       | 6.17%   |
| Elan Microelectronics              | 868       | 5.38%   |
| LighTuning Technology              | 708       | 4.39%   |
| STMicroelectronics                 | 322       | 2%      |
| Samsung Electronics                | 62        | 0.38%   |
| Focal-systems.Corp                 | 38        | 0.24%   |
| DigitalPersona                     | 14        | 0.09%   |
| HOLTEK                             | 10        | 0.06%   |
| Microsoft                          | 7         | 0.04%   |
| Dell                               | 6         | 0.04%   |
| Futronic Technology                | 3         | 0.02%   |
| Suprema                            | 2         | 0.01%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.01%   |
| Gingytech                          | 1         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1287      | 7.98%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1207      | 7.48%   |
| Unknown                                                                    | 1064      | 6.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 1010      | 6.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 923       | 5.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 670       | 4.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 635       | 3.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 631       | 3.91%   |
| Elan ELAN:Fingerprint                                                      | 558       | 3.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 542       | 3.36%   |
| Validity Sensors Fingerprint scanner                                       | 418       | 2.59%   |
| Validity Sensors VFS491                                                    | 394       | 2.44%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 392       | 2.43%   |
| AuthenTec AES2810                                                          | 390       | 2.42%   |
| Validity Sensors Synaptics WBDI                                            | 381       | 2.36%   |
| Shenzhen Goodix FingerPrint                                                | 374       | 2.32%   |
| Synaptics  WBDI                                                            | 372       | 2.31%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 365       | 2.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 329       | 2.04%   |
| STMicroelectronics Fingerprint Reader                                      | 320       | 1.98%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 288       | 1.79%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 271       | 1.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 263       | 1.63%   |
| Elan ELAN:ARM-M4                                                           | 263       | 1.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 243       | 1.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 241       | 1.49%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 234       | 1.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 227       | 1.41%   |
| AuthenTec AES1600                                                          | 208       | 1.29%   |
| LighTuning EgisTec_ES603                                                   | 206       | 1.28%   |
| AuthenTec Fingerprint Sensor                                               | 165       | 1.02%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 155       | 0.96%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 131       | 0.81%   |
| LighTuning Fingerprint Reader                                              | 120       | 0.74%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 103       | 0.64%   |
| Validity Sensors VFS Fingerprint sensor                                    | 93        | 0.58%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 83        | 0.51%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 81        | 0.5%    |
| Synaptics WBDI Device                                                      | 78        | 0.48%   |
| Upek TCS5B Fingerprint sensor                                              | 71        | 0.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 3021      | 44.86%  |
| Alcor Micro                       | 1697      | 25.2%   |
| O2 Micro                          | 537       | 7.97%   |
| Upek                              | 396       | 5.88%   |
| Lenovo                            | 374       | 5.55%   |
| Gemalto (was Gemplus)             | 111       | 1.65%   |
| SCM Microsystems                  | 87        | 1.29%   |
| Advanced Card Systems             | 71        | 1.05%   |
| OmniKey                           | 66        | 0.98%   |
| Realtek Semiconductor             | 43        | 0.64%   |
| Yubico.com                        | 41        | 0.61%   |
| Aladdin Knowledge Systems         | 41        | 0.61%   |
| Clay Logic                        | 27        | 0.4%    |
| Reiner SCT Kartensysteme          | 25        | 0.37%   |
| Cherry                            | 21        | 0.31%   |
| VASCO Data Security International | 20        | 0.3%    |
| Chicony Electronics               | 18        | 0.27%   |
| Hewlett-Packard                   | 17        | 0.25%   |
| BIT4ID                            | 16        | 0.24%   |
| Aktiv                             | 16        | 0.24%   |
| Giesecke & Devrient               | 12        | 0.18%   |
| Fujitsu Siemens Computers         | 12        | 0.18%   |
| Athena Smartcard Solutions        | 10        | 0.15%   |
| Aladdin R.D.                      | 9         | 0.13%   |
| Watchdata                         | 6         | 0.09%   |
| In Focus Systems                  | 5         | 0.07%   |
| C3PO                              | 5         | 0.07%   |
| Kobil Systems                     | 4         | 0.06%   |
| Purism, SPC                       | 3         | 0.04%   |
| NXP Semiconductors                | 3         | 0.04%   |
| Microchip Technology              | 3         | 0.04%   |
| Feitian Technologies              | 2         | 0.03%   |
| Castles Technology                | 2         | 0.03%   |
| Avtor                             | 2         | 0.03%   |
| ST-Ericsson                       | 1         | 0.01%   |
| SpringCard                        | 1         | 0.01%   |
| Precise Biometrics                | 1         | 0.01%   |
| Mako Technologies                 | 1         | 0.01%   |
| MagTek                            | 1         | 0.01%   |
| Jing-Mold Enterprise              | 1         | 0.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 1656      | 24.58%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1221      | 18.12%  |
| Broadcom 5880                                                                | 652       | 9.68%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 596       | 8.85%   |
| Broadcom 58200                                                               | 525       | 7.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 457       | 6.78%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 396       | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 372       | 5.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 80        | 1.19%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 62        | 0.92%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 43        | 0.64%   |
| Aladdin Knowledge Systems Token JC                                           | 41        | 0.61%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 40        | 0.59%   |
| Alcor Micro Watchdata W 1981                                                 | 39        | 0.58%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 36        | 0.53%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 35        | 0.52%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 29        | 0.43%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 29        | 0.43%   |
| OmniKey CardMan 3021 / 3121                                                  | 22        | 0.33%   |
| Clay Logic Nitrokey Pro                                                      | 19        | 0.28%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 18        | 0.27%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 17        | 0.25%   |
| OmniKey CardMan 1021                                                         | 17        | 0.25%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 17        | 0.25%   |
| BIT4ID miniLector EVO                                                        | 15        | 0.22%   |
| Aktiv Rutoken lite                                                           | 15        | 0.22%   |
| Advanced Card Systems ACR122U                                                | 14        | 0.21%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 12        | 0.18%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 12        | 0.18%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 12        | 0.18%   |
| OmniKey CardMan 4321                                                         | 11        | 0.16%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 11        | 0.16%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 10        | 0.15%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 10        | 0.15%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 9         | 0.13%   |
| Aladdin R.D. JaCarta                                                         | 9         | 0.13%   |
| VASCO Data Security International DIGIPASS 870                               | 8         | 0.12%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 8         | 0.12%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 7         | 0.1%    |
| Reiner SCT Kartensysteme cyberJack one                                       | 7         | 0.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 122309    | 71.48%  |
| 1     | 39340     | 22.99%  |
| 2     | 7544      | 4.41%   |
| 3     | 1248      | 0.73%   |
| 4     | 388       | 0.23%   |
| 5     | 144       | 0.08%   |
| 6     | 63        | 0.04%   |
| 7     | 37        | 0.02%   |
| 8     | 17        | 0.01%   |
| 9     | 6         | 0.004%  |
| 10    | 2         | 0.001%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15937     | 27.55%  |
| Graphics card            | 14047     | 24.28%  |
| Net/wireless             | 7237      | 12.51%  |
| Chipcard                 | 5950      | 10.29%  |
| Multimedia controller    | 3225      | 5.57%   |
| Communication controller | 2626      | 4.54%   |
| Bluetooth                | 1752      | 3.03%   |
| Camera                   | 1370      | 2.37%   |
| Unassigned class         | 1216      | 2.1%    |
| Storage                  | 969       | 1.68%   |
| Sound                    | 890       | 1.54%   |
| Net/ethernet             | 560       | 0.97%   |
| Card reader              | 557       | 0.96%   |
| Modem                    | 355       | 0.61%   |
| Network                  | 317       | 0.55%   |
| Flash memory             | 240       | 0.41%   |
| Storage/raid             | 135       | 0.23%   |
| Dvb card                 | 124       | 0.21%   |
| Storage/ide              | 103       | 0.18%   |
| Firewire controller      | 99        | 0.17%   |
| Storage/ata              | 34        | 0.06%   |
| Tv card                  | 32        | 0.06%   |
| Storage/nvme             | 31        | 0.05%   |
| Video                    | 16        | 0.03%   |
| Wireless                 | 14        | 0.02%   |
| Unclassified device      | 13        | 0.02%   |

