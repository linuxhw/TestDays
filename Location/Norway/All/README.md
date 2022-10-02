Linux in Norway - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Norway/Desktop/README.md) and [notebooks](/Location/Norway/Notebook/README.md).

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

Total: 1311

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fca2e4409a](https://linux-hardware.org/?probe=fca2e4409a) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [847283c85d](https://linux-hardware.org/?probe=847283c85d) | Oct 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [071194b58e](https://linux-hardware.org/?probe=071194b58e) | Sep 30, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [e29586cf56](https://linux-hardware.org/?probe=e29586cf56) | Sep 30, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7b0b80d00c](https://linux-hardware.org/?probe=7b0b80d00c) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [54bc787611](https://linux-hardware.org/?probe=54bc787611) | Sep 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [d4e346f990](https://linux-hardware.org/?probe=d4e346f990) | Sep 29, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [23142407b0](https://linux-hardware.org/?probe=23142407b0) | Sep 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [455bfad933](https://linux-hardware.org/?probe=455bfad933) | Sep 28, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [3553d42d14](https://linux-hardware.org/?probe=3553d42d14) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [1095e2f7f0](https://linux-hardware.org/?probe=1095e2f7f0) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [adb952e34b](https://linux-hardware.org/?probe=adb952e34b) | Sep 25, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a89311b338](https://linux-hardware.org/?probe=a89311b338) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [f8448323d1](https://linux-hardware.org/?probe=f8448323d1) | Sep 24, 2022 |
| HP            | Presario CQ56               | Notebook    | [ed937514cf](https://linux-hardware.org/?probe=ed937514cf) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3e88be3301](https://linux-hardware.org/?probe=3e88be3301) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [dd6c618f48](https://linux-hardware.org/?probe=dd6c618f48) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a0f2dedc00](https://linux-hardware.org/?probe=a0f2dedc00) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [926189f2ee](https://linux-hardware.org/?probe=926189f2ee) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [4fb85d59e0](https://linux-hardware.org/?probe=4fb85d59e0) | Sep 19, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c352d61c4e](https://linux-hardware.org/?probe=c352d61c4e) | Sep 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [38fa0eaf03](https://linux-hardware.org/?probe=38fa0eaf03) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [72c53fd3c8](https://linux-hardware.org/?probe=72c53fd3c8) | Sep 15, 2022 |
| HP            | 805D                        | Desktop     | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [d91d28cc52](https://linux-hardware.org/?probe=d91d28cc52) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [f3fe87a412](https://linux-hardware.org/?probe=f3fe87a412) | Sep 13, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [cb054f2964](https://linux-hardware.org/?probe=cb054f2964) | Sep 12, 2022 |
| MSI           | Z97M-G43                    | Desktop     | [706804a4e2](https://linux-hardware.org/?probe=706804a4e2) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [805f6366dc](https://linux-hardware.org/?probe=805f6366dc) | Sep 11, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [73bc6cd9e3](https://linux-hardware.org/?probe=73bc6cd9e3) | Sep 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3ce68aa737](https://linux-hardware.org/?probe=3ce68aa737) | Sep 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [fe1d0da2fc](https://linux-hardware.org/?probe=fe1d0da2fc) | Sep 10, 2022 |
| ASUSTek       | P9D-M Series                | Server      | [209be79723](https://linux-hardware.org/?probe=209be79723) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| MSI           | P67A-C45                    | Desktop     | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| ASUSTek       | P9D-M Series                | Server      | [04faeec9ab](https://linux-hardware.org/?probe=04faeec9ab) | Sep 06, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ad0d0e6994](https://linux-hardware.org/?probe=ad0d0e6994) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a84dbefc98](https://linux-hardware.org/?probe=a84dbefc98) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [9438d3a4fe](https://linux-hardware.org/?probe=9438d3a4fe) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | Notebook    | [5344528fa4](https://linux-hardware.org/?probe=5344528fa4) | Sep 03, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [6fa62e0277](https://linux-hardware.org/?probe=6fa62e0277) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5cf1e75ad4](https://linux-hardware.org/?probe=5cf1e75ad4) | Sep 01, 2022 |
| Acer          | Aspire X3400                | Desktop     | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | Desktop     | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [56a6f41ffa](https://linux-hardware.org/?probe=56a6f41ffa) | Aug 31, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d4de10030b](https://linux-hardware.org/?probe=d4de10030b) | Aug 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [09b6390c84](https://linux-hardware.org/?probe=09b6390c84) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [eba231b7db](https://linux-hardware.org/?probe=eba231b7db) | Aug 30, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | Notebook    | [1ffe55389e](https://linux-hardware.org/?probe=1ffe55389e) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | Notebook    | [46b40c3c67](https://linux-hardware.org/?probe=46b40c3c67) | Aug 27, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8b0ab8f988](https://linux-hardware.org/?probe=8b0ab8f988) | Aug 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ff55a7dbf1](https://linux-hardware.org/?probe=ff55a7dbf1) | Aug 26, 2022 |
| Acer          | Aspire X3400                | Desktop     | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ec4d28f5de](https://linux-hardware.org/?probe=ec4d28f5de) | Aug 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f80abd07f3](https://linux-hardware.org/?probe=f80abd07f3) | Aug 25, 2022 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [17260bd4fb](https://linux-hardware.org/?probe=17260bd4fb) | Aug 24, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [3df60311dc](https://linux-hardware.org/?probe=3df60311dc) | Aug 24, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [d287893b82](https://linux-hardware.org/?probe=d287893b82) | Aug 22, 2022 |
| Lenovo        | B570e 476022G               | Notebook    | [ad4a4c25d5](https://linux-hardware.org/?probe=ad4a4c25d5) | Aug 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [4adf6ab444](https://linux-hardware.org/?probe=4adf6ab444) | Aug 22, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [e663637449](https://linux-hardware.org/?probe=e663637449) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [da2ae510f9](https://linux-hardware.org/?probe=da2ae510f9) | Aug 17, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2b746c613f](https://linux-hardware.org/?probe=2b746c613f) | Aug 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3f83c9e402](https://linux-hardware.org/?probe=3f83c9e402) | Aug 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [f1a0029208](https://linux-hardware.org/?probe=f1a0029208) | Aug 16, 2022 |
| Dell          | 0H21J3 A04                  | Server      | [14f7add408](https://linux-hardware.org/?probe=14f7add408) | Aug 16, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [91a402ab9e](https://linux-hardware.org/?probe=91a402ab9e) | Aug 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1298facab1](https://linux-hardware.org/?probe=1298facab1) | Aug 15, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [c0ba049caf](https://linux-hardware.org/?probe=c0ba049caf) | Aug 14, 2022 |
| HP            | 829A                        | Mini pc     | [0e36f81a7b](https://linux-hardware.org/?probe=0e36f81a7b) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [91a2943c51](https://linux-hardware.org/?probe=91a2943c51) | Aug 09, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0318e6b173](https://linux-hardware.org/?probe=0318e6b173) | Aug 09, 2022 |
| Dell          | Latitude E5470              | Notebook    | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [29d3bf5483](https://linux-hardware.org/?probe=29d3bf5483) | Aug 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [244025d59e](https://linux-hardware.org/?probe=244025d59e) | Aug 08, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d55725824](https://linux-hardware.org/?probe=2d55725824) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d8a5d82c22](https://linux-hardware.org/?probe=d8a5d82c22) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [53e660f72b](https://linux-hardware.org/?probe=53e660f72b) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ecb313e10d](https://linux-hardware.org/?probe=ecb313e10d) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [284fd5ef07](https://linux-hardware.org/?probe=284fd5ef07) | Aug 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9320816ca5](https://linux-hardware.org/?probe=9320816ca5) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [48606f92a6](https://linux-hardware.org/?probe=48606f92a6) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [c55f1b0a46](https://linux-hardware.org/?probe=c55f1b0a46) | Aug 05, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [33c854adcd](https://linux-hardware.org/?probe=33c854adcd) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b224ef1b8d](https://linux-hardware.org/?probe=b224ef1b8d) | Aug 04, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [bf4a2c0e11](https://linux-hardware.org/?probe=bf4a2c0e11) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [f31ac48621](https://linux-hardware.org/?probe=f31ac48621) | Aug 03, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [2e6cf4c0bd](https://linux-hardware.org/?probe=2e6cf4c0bd) | Aug 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a56f943225](https://linux-hardware.org/?probe=a56f943225) | Aug 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [015ec264f5](https://linux-hardware.org/?probe=015ec264f5) | Aug 02, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5fe6f7eb57](https://linux-hardware.org/?probe=5fe6f7eb57) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [76a30e3042](https://linux-hardware.org/?probe=76a30e3042) | Jul 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ebfa3daff5](https://linux-hardware.org/?probe=ebfa3daff5) | Jul 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | Desktop     | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [d5034f5f52](https://linux-hardware.org/?probe=d5034f5f52) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7c25b2c2c7](https://linux-hardware.org/?probe=7c25b2c2c7) | Jul 28, 2022 |
| ASUSTek       | VC65                        | Desktop     | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [db30ba1d0e](https://linux-hardware.org/?probe=db30ba1d0e) | Jul 28, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [97bbabec13](https://linux-hardware.org/?probe=97bbabec13) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | Desktop     | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [aef89fc83f](https://linux-hardware.org/?probe=aef89fc83f) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [137d7c8701](https://linux-hardware.org/?probe=137d7c8701) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76bd6feebe](https://linux-hardware.org/?probe=76bd6feebe) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [3e2f9e1e86](https://linux-hardware.org/?probe=3e2f9e1e86) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [57beac41bc](https://linux-hardware.org/?probe=57beac41bc) | Jul 25, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [03bb89eced](https://linux-hardware.org/?probe=03bb89eced) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [d41e7515af](https://linux-hardware.org/?probe=d41e7515af) | Jul 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [79d402e1ff](https://linux-hardware.org/?probe=79d402e1ff) | Jul 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [fdada0c3a6](https://linux-hardware.org/?probe=fdada0c3a6) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7a33ccf211](https://linux-hardware.org/?probe=7a33ccf211) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [347ff14d90](https://linux-hardware.org/?probe=347ff14d90) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a671047cb4](https://linux-hardware.org/?probe=a671047cb4) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [05a5bc0fa8](https://linux-hardware.org/?probe=05a5bc0fa8) | Jul 20, 2022 |
| MSI           | MS-B090                     | All in one  | [b5df4140d1](https://linux-hardware.org/?probe=b5df4140d1) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ac616e6f37](https://linux-hardware.org/?probe=ac616e6f37) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7107c7c2eb](https://linux-hardware.org/?probe=7107c7c2eb) | Jul 13, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [108d31db10](https://linux-hardware.org/?probe=108d31db10) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [7ce0875267](https://linux-hardware.org/?probe=7ce0875267) | Jul 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [ae0184c434](https://linux-hardware.org/?probe=ae0184c434) | Jul 10, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [42158587b1](https://linux-hardware.org/?probe=42158587b1) | Jul 10, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Latitude D531               | Notebook    | [008236dd11](https://linux-hardware.org/?probe=008236dd11) | Jul 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [fec0786471](https://linux-hardware.org/?probe=fec0786471) | Jul 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [e6eeb4dfe6](https://linux-hardware.org/?probe=e6eeb4dfe6) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [6b1e1133e4](https://linux-hardware.org/?probe=6b1e1133e4) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [63508059d3](https://linux-hardware.org/?probe=63508059d3) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [b7aef43e9e](https://linux-hardware.org/?probe=b7aef43e9e) | Jul 01, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [e1c3d1dfad](https://linux-hardware.org/?probe=e1c3d1dfad) | Jul 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2da2ad735c](https://linux-hardware.org/?probe=2da2ad735c) | Jun 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b197a0fd35](https://linux-hardware.org/?probe=b197a0fd35) | Jun 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| MSI           | P67A-C45                    | Desktop     | [79a2dd2b27](https://linux-hardware.org/?probe=79a2dd2b27) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [184ad2670a](https://linux-hardware.org/?probe=184ad2670a) | Jun 17, 2022 |
| Dell          | Latitude E7240              | Notebook    | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [fd2fb2f646](https://linux-hardware.org/?probe=fd2fb2f646) | Jun 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [6b279160dc](https://linux-hardware.org/?probe=6b279160dc) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2f784679b0](https://linux-hardware.org/?probe=2f784679b0) | Jun 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| MSI           | P67A-C45                    | Desktop     | [86fc259ec4](https://linux-hardware.org/?probe=86fc259ec4) | Jun 07, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [34e068e6ad](https://linux-hardware.org/?probe=34e068e6ad) | Jun 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [5a835b2aa6](https://linux-hardware.org/?probe=5a835b2aa6) | Jun 07, 2022 |
| ASUSTek       | X55U                        | Notebook    | [66e1c7ed1d](https://linux-hardware.org/?probe=66e1c7ed1d) | Jun 06, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [9dc558e0e2](https://linux-hardware.org/?probe=9dc558e0e2) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [838e0b8e42](https://linux-hardware.org/?probe=838e0b8e42) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [cb07ae6e24](https://linux-hardware.org/?probe=cb07ae6e24) | Jun 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [97428f0f4d](https://linux-hardware.org/?probe=97428f0f4d) | Jun 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0b16a52ca1](https://linux-hardware.org/?probe=0b16a52ca1) | Jun 01, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [6f6f16ee08](https://linux-hardware.org/?probe=6f6f16ee08) | May 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| Notebook      | Multicom Xishan NL50        | Notebook    | [9ffa89c7a9](https://linux-hardware.org/?probe=9ffa89c7a9) | May 31, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8794ca2ca9](https://linux-hardware.org/?probe=8794ca2ca9) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| Notebook      | Multicom Xishan NL50        | Notebook    | [0c45263f11](https://linux-hardware.org/?probe=0c45263f11) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [e6fc3ad487](https://linux-hardware.org/?probe=e6fc3ad487) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [1783c56618](https://linux-hardware.org/?probe=1783c56618) | May 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [d83c99fb0e](https://linux-hardware.org/?probe=d83c99fb0e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [a07fb7cbcd](https://linux-hardware.org/?probe=a07fb7cbcd) | May 25, 2022 |
| Lenovo        | ThinkPad T490s 20NX0077M... | Notebook    | [cea81a1d63](https://linux-hardware.org/?probe=cea81a1d63) | May 24, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [428631aa4a](https://linux-hardware.org/?probe=428631aa4a) | May 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| Notebook      | N8xEJEK                     | Notebook    | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [c195f80f3c](https://linux-hardware.org/?probe=c195f80f3c) | May 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [47b730f9bd](https://linux-hardware.org/?probe=47b730f9bd) | May 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [afac7f7fb3](https://linux-hardware.org/?probe=afac7f7fb3) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2075bfcc02](https://linux-hardware.org/?probe=2075bfcc02) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [71f8f45765](https://linux-hardware.org/?probe=71f8f45765) | May 05, 2022 |
| HP            | ProBook 4330s               | Notebook    | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | Notebook    | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [01de94a143](https://linux-hardware.org/?probe=01de94a143) | May 02, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Acer          | Swift SF514-51              | Notebook    | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Acer          | Predator G3610              | Desktop     | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91bbf4068b](https://linux-hardware.org/?probe=91bbf4068b) | Apr 20, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [e595903b64](https://linux-hardware.org/?probe=e595903b64) | Apr 18, 2022 |
| Google        | Cave                        | Notebook    | [c762019e08](https://linux-hardware.org/?probe=c762019e08) | Apr 18, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b2fe9a09fd](https://linux-hardware.org/?probe=b2fe9a09fd) | Apr 17, 2022 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [19299bc16d](https://linux-hardware.org/?probe=19299bc16d) | Apr 14, 2022 |
| ASUSTek       | K52Dr                       | Notebook    | [29124147fe](https://linux-hardware.org/?probe=29124147fe) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490s 20NX003UM... | Notebook    | [60dca75a93](https://linux-hardware.org/?probe=60dca75a93) | Apr 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [7f83d03bf3](https://linux-hardware.org/?probe=7f83d03bf3) | Apr 13, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [2d44f4a10b](https://linux-hardware.org/?probe=2d44f4a10b) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [bbcb05781f](https://linux-hardware.org/?probe=bbcb05781f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | Notebook    | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| HP            | 87F9 A00                    | All in one  | [a5081405c2](https://linux-hardware.org/?probe=a5081405c2) | Apr 11, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [cf2e65caf4](https://linux-hardware.org/?probe=cf2e65caf4) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [dd511f4bf0](https://linux-hardware.org/?probe=dd511f4bf0) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [abc7562fb9](https://linux-hardware.org/?probe=abc7562fb9) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [79c6231f19](https://linux-hardware.org/?probe=79c6231f19) | Apr 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| Acer          | Aspire X3400                | Desktop     | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [ea012026c5](https://linux-hardware.org/?probe=ea012026c5) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [76ec39764b](https://linux-hardware.org/?probe=76ec39764b) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [eaaef17c19](https://linux-hardware.org/?probe=eaaef17c19) | Mar 25, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a68b0e55c](https://linux-hardware.org/?probe=0a68b0e55c) | Mar 24, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [b071309501](https://linux-hardware.org/?probe=b071309501) | Mar 23, 2022 |
| ASUSTek       | M2R-FVM                     | Desktop     | [eb934cc46a](https://linux-hardware.org/?probe=eb934cc46a) | Mar 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [6911af9ce1](https://linux-hardware.org/?probe=6911af9ce1) | Mar 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [f2fedaa3c3](https://linux-hardware.org/?probe=f2fedaa3c3) | Mar 18, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [56c1c58549](https://linux-hardware.org/?probe=56c1c58549) | Mar 15, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [ce34107bae](https://linux-hardware.org/?probe=ce34107bae) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [acef37559c](https://linux-hardware.org/?probe=acef37559c) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [884e853e6f](https://linux-hardware.org/?probe=884e853e6f) | Mar 14, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | Notebook    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d7fe091593](https://linux-hardware.org/?probe=d7fe091593) | Mar 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [0e4fb3e1fd](https://linux-hardware.org/?probe=0e4fb3e1fd) | Mar 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Dell          | Precision M6800             | Notebook    | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [5a711af850](https://linux-hardware.org/?probe=5a711af850) | Mar 07, 2022 |
| Lenovo        | ThinkPad T480 20L60033MX    | Notebook    | [fda7557aa0](https://linux-hardware.org/?probe=fda7557aa0) | Mar 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [54ae8c7668](https://linux-hardware.org/?probe=54ae8c7668) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ad43671e4c](https://linux-hardware.org/?probe=ad43671e4c) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [9670ab829e](https://linux-hardware.org/?probe=9670ab829e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [d61754bba9](https://linux-hardware.org/?probe=d61754bba9) | Feb 26, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [290919912c](https://linux-hardware.org/?probe=290919912c) | Feb 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [c332efa9f8](https://linux-hardware.org/?probe=c332efa9f8) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [69896e5117](https://linux-hardware.org/?probe=69896e5117) | Feb 23, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [7bb148611f](https://linux-hardware.org/?probe=7bb148611f) | Feb 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | Notebook    | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| ASUSTek       | A4110                       | All in one  | [8fd1f10c40](https://linux-hardware.org/?probe=8fd1f10c40) | Feb 18, 2022 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [0337480978](https://linux-hardware.org/?probe=0337480978) | Feb 17, 2022 |
| ASUSTek       | A4110                       | All in one  | [ede6469471](https://linux-hardware.org/?probe=ede6469471) | Feb 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| HP            | ProBook 4330s               | Notebook    | [3781146b1f](https://linux-hardware.org/?probe=3781146b1f) | Feb 14, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [2ad209abc4](https://linux-hardware.org/?probe=2ad209abc4) | Feb 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [68d863ab48](https://linux-hardware.org/?probe=68d863ab48) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | Notebook    | [ab580c3edd](https://linux-hardware.org/?probe=ab580c3edd) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | Notebook    | [c11f9d5c6d](https://linux-hardware.org/?probe=c11f9d5c6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0FJ0... | Notebook    | [6dc9215373](https://linux-hardware.org/?probe=6dc9215373) | Feb 07, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [ef92dfd4f1](https://linux-hardware.org/?probe=ef92dfd4f1) | Feb 03, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [9f7733e6ec](https://linux-hardware.org/?probe=9f7733e6ec) | Feb 03, 2022 |
| Dell          | Latitude E4200              | Notebook    | [35dbab3b2e](https://linux-hardware.org/?probe=35dbab3b2e) | Jan 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccd7847b28](https://linux-hardware.org/?probe=ccd7847b28) | Jan 30, 2022 |
| ASRock        | ION3D-HT                    | Desktop     | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Unknown       | OnePlus 6                   | Soc         | [d9aedf2258](https://linux-hardware.org/?probe=d9aedf2258) | Jan 28, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [d6498c16bb](https://linux-hardware.org/?probe=d6498c16bb) | Jan 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8b6b3d70bf](https://linux-hardware.org/?probe=8b6b3d70bf) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [698c80468a](https://linux-hardware.org/?probe=698c80468a) | Jan 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [29ce7637f6](https://linux-hardware.org/?probe=29ce7637f6) | Jan 23, 2022 |
| Intel         | NUC7i7DNB J83500-206        | Mini pc     | [65ae59d048](https://linux-hardware.org/?probe=65ae59d048) | Jan 23, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [cbf995ff80](https://linux-hardware.org/?probe=cbf995ff80) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [634d45ff9e](https://linux-hardware.org/?probe=634d45ff9e) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Dell          | Latitude 7280               | Notebook    | [6b9dcc88b7](https://linux-hardware.org/?probe=6b9dcc88b7) | Jan 21, 2022 |
| Dell          | Latitude 7280               | Notebook    | [beb9306791](https://linux-hardware.org/?probe=beb9306791) | Jan 21, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [c9587deb57](https://linux-hardware.org/?probe=c9587deb57) | Jan 19, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASRock        | Z87 Killer                  | Desktop     | [6931f1ca2f](https://linux-hardware.org/?probe=6931f1ca2f) | Jan 17, 2022 |
| MSI           | P67A-C45                    | Desktop     | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5a609ef492](https://linux-hardware.org/?probe=5a609ef492) | Jan 16, 2022 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7921e32637](https://linux-hardware.org/?probe=7921e32637) | Jan 14, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7b12fb3749](https://linux-hardware.org/?probe=7b12fb3749) | Jan 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Dell          | Precision 7560              | Notebook    | [a58a852902](https://linux-hardware.org/?probe=a58a852902) | Jan 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Samsung       | 950QDB                      | Convertible | [d2f65665cd](https://linux-hardware.org/?probe=d2f65665cd) | Jan 12, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [831591fe79](https://linux-hardware.org/?probe=831591fe79) | Jan 11, 2022 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [a38abf3dd0](https://linux-hardware.org/?probe=a38abf3dd0) | Jan 10, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c572bd1eac](https://linux-hardware.org/?probe=c572bd1eac) | Jan 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [b5bd2eca7d](https://linux-hardware.org/?probe=b5bd2eca7d) | Jan 07, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | Notebook    | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Dell          | Latitude E7440              | Notebook    | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Acer          | Aspire X3400                | Desktop     | [6833137bc8](https://linux-hardware.org/?probe=6833137bc8) | Jan 02, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [de0e6691cd](https://linux-hardware.org/?probe=de0e6691cd) | Jan 02, 2022 |
| MSI           | H110M PRO-VH                | Desktop     | [a32495b8e4](https://linux-hardware.org/?probe=a32495b8e4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T410s 2924W79      | Notebook    | [43fe13f2a4](https://linux-hardware.org/?probe=43fe13f2a4) | Dec 30, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e560c10eb8](https://linux-hardware.org/?probe=e560c10eb8) | Dec 29, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [ab9c63e097](https://linux-hardware.org/?probe=ab9c63e097) | Dec 28, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [04ebd359f1](https://linux-hardware.org/?probe=04ebd359f1) | Dec 28, 2021 |
| Acer          | Aspire E1-572               | Notebook    | [63f4428f24](https://linux-hardware.org/?probe=63f4428f24) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [0f7bd5b933](https://linux-hardware.org/?probe=0f7bd5b933) | Dec 26, 2021 |
| MSI           | GS66 Stealth 10UH           | Notebook    | [6246228e2d](https://linux-hardware.org/?probe=6246228e2d) | Dec 26, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| HP            | ZBook 15                    | Notebook    | [57cb28cc81](https://linux-hardware.org/?probe=57cb28cc81) | Dec 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [5c91ed91a8](https://linux-hardware.org/?probe=5c91ed91a8) | Dec 24, 2021 |
| Acer          | Aspire xxxx                 | Notebook    | [13b21c09d2](https://linux-hardware.org/?probe=13b21c09d2) | Dec 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [86789982ba](https://linux-hardware.org/?probe=86789982ba) | Dec 21, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [17fbd36a25](https://linux-hardware.org/?probe=17fbd36a25) | Dec 18, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | Notebook    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [3cd4b5c111](https://linux-hardware.org/?probe=3cd4b5c111) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [03115bdd2e](https://linux-hardware.org/?probe=03115bdd2e) | Dec 18, 2021 |
| Lenovo        | ThinkPad T410s 2924W79      | Notebook    | [f26b8b4f98](https://linux-hardware.org/?probe=f26b8b4f98) | Dec 17, 2021 |
| Acer          | Aspire xxxx                 | Notebook    | [dfa568d766](https://linux-hardware.org/?probe=dfa568d766) | Dec 17, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [af2732b8a5](https://linux-hardware.org/?probe=af2732b8a5) | Dec 15, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [dd9fb384ea](https://linux-hardware.org/?probe=dd9fb384ea) | Dec 13, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [711aa97225](https://linux-hardware.org/?probe=711aa97225) | Dec 13, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| HP            | ZBook 15                    | Notebook    | [cb2487cb67](https://linux-hardware.org/?probe=cb2487cb67) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| HP            | ZBook 15                    | Notebook    | [c0d2e24505](https://linux-hardware.org/?probe=c0d2e24505) | Dec 10, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [696dd578ab](https://linux-hardware.org/?probe=696dd578ab) | Dec 08, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [b44117a400](https://linux-hardware.org/?probe=b44117a400) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | Notebook    | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [87b9d0f1e5](https://linux-hardware.org/?probe=87b9d0f1e5) | Dec 04, 2021 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [071e272398](https://linux-hardware.org/?probe=071e272398) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | Notebook    | [c579de06b5](https://linux-hardware.org/?probe=c579de06b5) | Dec 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | Notebook    | [e85a481d36](https://linux-hardware.org/?probe=e85a481d36) | Dec 02, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [4b1553b16a](https://linux-hardware.org/?probe=4b1553b16a) | Dec 01, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [64005f7018](https://linux-hardware.org/?probe=64005f7018) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [a380d2a0c8](https://linux-hardware.org/?probe=a380d2a0c8) | Nov 29, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c0f6b8395](https://linux-hardware.org/?probe=5c0f6b8395) | Nov 28, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [fb92bb54af](https://linux-hardware.org/?probe=fb92bb54af) | Nov 28, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [7c0e3a92a5](https://linux-hardware.org/?probe=7c0e3a92a5) | Nov 26, 2021 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [846877b55f](https://linux-hardware.org/?probe=846877b55f) | Nov 25, 2021 |
| MSI           | H170 GAMING M3              | Desktop     | [e9a754ed5c](https://linux-hardware.org/?probe=e9a754ed5c) | Nov 24, 2021 |
| Gigabyte      | Z170-Gaming K3              | Desktop     | [496b525711](https://linux-hardware.org/?probe=496b525711) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [969dde57b0](https://linux-hardware.org/?probe=969dde57b0) | Nov 22, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| ASUSTek       | ET2002G                     | All in one  | [a31ccc8a05](https://linux-hardware.org/?probe=a31ccc8a05) | Nov 21, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [756684e469](https://linux-hardware.org/?probe=756684e469) | Nov 20, 2021 |
| Acer          | EG43M                       | Desktop     | [03dc3c8d61](https://linux-hardware.org/?probe=03dc3c8d61) | Nov 20, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [1d12ea147a](https://linux-hardware.org/?probe=1d12ea147a) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [c6e0003dcb](https://linux-hardware.org/?probe=c6e0003dcb) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | Notebook    | [6b485f4c9a](https://linux-hardware.org/?probe=6b485f4c9a) | Nov 20, 2021 |
| Acer          | Swift SF514-51              | Notebook    | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | Notebook    | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| HP            | 8056                        | Desktop     | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [f5d53e44ae](https://linux-hardware.org/?probe=f5d53e44ae) | Nov 15, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [b19a68b774](https://linux-hardware.org/?probe=b19a68b774) | Nov 13, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [4615791bf1](https://linux-hardware.org/?probe=4615791bf1) | Nov 04, 2021 |
| Lenovo        | ThinkPad W540 20BHS0NQ00    | Notebook    | [69f4b3d974](https://linux-hardware.org/?probe=69f4b3d974) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [0b7ae3ebf5](https://linux-hardware.org/?probe=0b7ae3ebf5) | Nov 03, 2021 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [39c0680056](https://linux-hardware.org/?probe=39c0680056) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Acer          | Aspire 5739G                | Notebook    | [9366122bdb](https://linux-hardware.org/?probe=9366122bdb) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | Notebook    | [aaf8f33249](https://linux-hardware.org/?probe=aaf8f33249) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | Notebook    | [7979c29593](https://linux-hardware.org/?probe=7979c29593) | Oct 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0cc8ca1a78](https://linux-hardware.org/?probe=0cc8ca1a78) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ccce1ad4e4](https://linux-hardware.org/?probe=ccce1ad4e4) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [a96916c86f](https://linux-hardware.org/?probe=a96916c86f) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f4442e94e7](https://linux-hardware.org/?probe=f4442e94e7) | Oct 21, 2021 |
| HP            | 1998                        | Desktop     | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Pegatron      | 2AC3                        | Desktop     | [ae8b02d9cb](https://linux-hardware.org/?probe=ae8b02d9cb) | Oct 21, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | Notebook    | [df466b506d](https://linux-hardware.org/?probe=df466b506d) | Oct 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | Notebook    | [748d3e56a7](https://linux-hardware.org/?probe=748d3e56a7) | Oct 20, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [fe7520a392](https://linux-hardware.org/?probe=fe7520a392) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8fab065f3b](https://linux-hardware.org/?probe=8fab065f3b) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8502c5d5f7](https://linux-hardware.org/?probe=8502c5d5f7) | Oct 13, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [d7f1b3f27e](https://linux-hardware.org/?probe=d7f1b3f27e) | Oct 12, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| Acer          | Aspire A515-45              | Notebook    | [4b45531984](https://linux-hardware.org/?probe=4b45531984) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| Packard Be... | IXTREME M5120               | Desktop     | [315bbefc53](https://linux-hardware.org/?probe=315bbefc53) | Oct 06, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c9022127a9](https://linux-hardware.org/?probe=c9022127a9) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [99b237ae08](https://linux-hardware.org/?probe=99b237ae08) | Oct 02, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [e1dc7a64a4](https://linux-hardware.org/?probe=e1dc7a64a4) | Sep 30, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6af7a7f851](https://linux-hardware.org/?probe=6af7a7f851) | Sep 27, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [eca410ddc4](https://linux-hardware.org/?probe=eca410ddc4) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| HP            | 8056                        | Desktop     | [2199f7a715](https://linux-hardware.org/?probe=2199f7a715) | Sep 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [bf5a5a2c74](https://linux-hardware.org/?probe=bf5a5a2c74) | Sep 26, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [a54466b990](https://linux-hardware.org/?probe=a54466b990) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | Notebook    | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3808823182](https://linux-hardware.org/?probe=3808823182) | Sep 23, 2021 |
| Dell          | Latitude E5470              | Notebook    | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| ASUSTek       | E402NA                      | Notebook    | [8262dd102f](https://linux-hardware.org/?probe=8262dd102f) | Sep 23, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f28906612f](https://linux-hardware.org/?probe=f28906612f) | Sep 21, 2021 |
| Lenovo        | ThinkPad E15 20RES6DF07     | Notebook    | [2f5045ab95](https://linux-hardware.org/?probe=2f5045ab95) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [17ad477c6f](https://linux-hardware.org/?probe=17ad477c6f) | Sep 21, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [333d881ec2](https://linux-hardware.org/?probe=333d881ec2) | Sep 20, 2021 |
| Acer          | Aspire A114-32              | Notebook    | [da860f1378](https://linux-hardware.org/?probe=da860f1378) | Sep 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a122cb5006](https://linux-hardware.org/?probe=a122cb5006) | Sep 19, 2021 |
| HUAWEI        | EUL-WX9                     | Notebook    | [4ab59b64df](https://linux-hardware.org/?probe=4ab59b64df) | Sep 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Latitude 5480               | Notebook    | [ac2c5649d3](https://linux-hardware.org/?probe=ac2c5649d3) | Sep 17, 2021 |
| Acer          | EG43M                       | Desktop     | [03cff58061](https://linux-hardware.org/?probe=03cff58061) | Sep 17, 2021 |
| Dell          | Latitude E5470              | Notebook    | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | Notebook    | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| HP            | ZBook 15u G5                | Notebook    | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a92f9c3457](https://linux-hardware.org/?probe=a92f9c3457) | Sep 15, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [cf1e0581f3](https://linux-hardware.org/?probe=cf1e0581f3) | Sep 15, 2021 |
| MSI           | Alpha 17 A4DE               | Notebook    | [0be8b0b607](https://linux-hardware.org/?probe=0be8b0b607) | Sep 14, 2021 |
| HP            | 8056                        | Desktop     | [61c50556d0](https://linux-hardware.org/?probe=61c50556d0) | Sep 13, 2021 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | Notebook    | [2b5735f34c](https://linux-hardware.org/?probe=2b5735f34c) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [630fec5a83](https://linux-hardware.org/?probe=630fec5a83) | Sep 11, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [74817fdcb8](https://linux-hardware.org/?probe=74817fdcb8) | Sep 10, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [0918a27e6a](https://linux-hardware.org/?probe=0918a27e6a) | Sep 08, 2021 |
| Acer          | Aspire 5745G                | Notebook    | [680d788d4b](https://linux-hardware.org/?probe=680d788d4b) | Sep 07, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f1b9bebe99](https://linux-hardware.org/?probe=f1b9bebe99) | Sep 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [94a243f26a](https://linux-hardware.org/?probe=94a243f26a) | Sep 07, 2021 |
| MSI           | Alpha 17 A4DE               | Notebook    | [3f0de31253](https://linux-hardware.org/?probe=3f0de31253) | Sep 06, 2021 |
| Dell          | Precision 5510              | Notebook    | [1339721ac0](https://linux-hardware.org/?probe=1339721ac0) | Sep 06, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [7bc3201683](https://linux-hardware.org/?probe=7bc3201683) | Sep 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [211ef30ef4](https://linux-hardware.org/?probe=211ef30ef4) | Sep 04, 2021 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [332124aa7f](https://linux-hardware.org/?probe=332124aa7f) | Sep 04, 2021 |
| Acer          | Aspire A515-45              | Notebook    | [16a250faf6](https://linux-hardware.org/?probe=16a250faf6) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | Notebook    | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| Dell          | Latitude E7270              | Notebook    | [1bd5f17116](https://linux-hardware.org/?probe=1bd5f17116) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | Notebook    | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [2bd5adb706](https://linux-hardware.org/?probe=2bd5adb706) | Aug 31, 2021 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [24bc89b42a](https://linux-hardware.org/?probe=24bc89b42a) | Aug 31, 2021 |
| HP            | 0B40h                       | Desktop     | [da95bc989c](https://linux-hardware.org/?probe=da95bc989c) | Aug 30, 2021 |
| Supermicro    | X10DAI                      | Desktop     | [078ab4c114](https://linux-hardware.org/?probe=078ab4c114) | Aug 24, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [bcb68ab6d0](https://linux-hardware.org/?probe=bcb68ab6d0) | Aug 21, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [5909ea8d8d](https://linux-hardware.org/?probe=5909ea8d8d) | Aug 20, 2021 |
| HP            | 802E                        | Desktop     | [35a2f000fd](https://linux-hardware.org/?probe=35a2f000fd) | Aug 19, 2021 |
| ASUSTek       | B150M-C                     | Desktop     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [eaac722778](https://linux-hardware.org/?probe=eaac722778) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a24db8e84d](https://linux-hardware.org/?probe=a24db8e84d) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [51b28dbd02](https://linux-hardware.org/?probe=51b28dbd02) | Aug 16, 2021 |
| Dell          | Studio 1747                 | Notebook    | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| Teclast       | F6 Plus                     | Notebook    | [a1df449dea](https://linux-hardware.org/?probe=a1df449dea) | Aug 13, 2021 |
| Acer          | Aspire X3400                | Desktop     | [0a158e8bce](https://linux-hardware.org/?probe=0a158e8bce) | Aug 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5742cb7dd7](https://linux-hardware.org/?probe=5742cb7dd7) | Aug 12, 2021 |
| Alienware     | x17 R1                      | Notebook    | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [034630b7f9](https://linux-hardware.org/?probe=034630b7f9) | Aug 11, 2021 |
| Acer          | Aspire X3400                | Desktop     | [6836f60d13](https://linux-hardware.org/?probe=6836f60d13) | Aug 11, 2021 |
| Clevo         | W55xEU                      | Notebook    | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | Notebook    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| HP            | 3397                        | Desktop     | [d5add95307](https://linux-hardware.org/?probe=d5add95307) | Aug 05, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [938ff270ef](https://linux-hardware.org/?probe=938ff270ef) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Wibtek        | TH61G-S                     | Desktop     | [346ae2c85d](https://linux-hardware.org/?probe=346ae2c85d) | Jul 29, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [77f9eee003](https://linux-hardware.org/?probe=77f9eee003) | Jul 28, 2021 |
| HP            | ProBook 4740s               | Notebook    | [624b649eb0](https://linux-hardware.org/?probe=624b649eb0) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| HP            | EliteBook 1040 G4           | Notebook    | [693137b6b8](https://linux-hardware.org/?probe=693137b6b8) | Jul 26, 2021 |
| Dell          | Latitude 5480               | Notebook    | [64665ed287](https://linux-hardware.org/?probe=64665ed287) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [563a58b492](https://linux-hardware.org/?probe=563a58b492) | Jul 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Presario CQ56               | Notebook    | [7148aa989e](https://linux-hardware.org/?probe=7148aa989e) | Jul 21, 2021 |
| Apple         | MacBook8,1                  | Notebook    | [1220a734d7](https://linux-hardware.org/?probe=1220a734d7) | Jul 20, 2021 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [788b497894](https://linux-hardware.org/?probe=788b497894) | Jul 19, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [6f026a93d1](https://linux-hardware.org/?probe=6f026a93d1) | Jul 17, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [af12b529b0](https://linux-hardware.org/?probe=af12b529b0) | Jul 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [610bb918de](https://linux-hardware.org/?probe=610bb918de) | Jul 14, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [eba2e6ade8](https://linux-hardware.org/?probe=eba2e6ade8) | Jul 13, 2021 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [35bf19b527](https://linux-hardware.org/?probe=35bf19b527) | Jul 13, 2021 |
| HP            | 872B                        | Desktop     | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| HP            | Presario CQ56               | Notebook    | [7a202a99e9](https://linux-hardware.org/?probe=7a202a99e9) | Jul 11, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [27fd4c16ae](https://linux-hardware.org/?probe=27fd4c16ae) | Jul 08, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1bd2963aa0](https://linux-hardware.org/?probe=1bd2963aa0) | Jul 06, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f1c608dcbd](https://linux-hardware.org/?probe=f1c608dcbd) | Jul 04, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [ef051fc485](https://linux-hardware.org/?probe=ef051fc485) | Jul 04, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [b8a40b6dbd](https://linux-hardware.org/?probe=b8a40b6dbd) | Jul 02, 2021 |
| HP            | 1998                        | Desktop     | [8f095c8449](https://linux-hardware.org/?probe=8f095c8449) | Jul 01, 2021 |
| ASUSTek       | P5G41T-M                    | Desktop     | [8553d8a919](https://linux-hardware.org/?probe=8553d8a919) | Jun 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [04c4ddf9b0](https://linux-hardware.org/?probe=04c4ddf9b0) | Jun 29, 2021 |
| Lenovo        | G50-80 80L0                 | Notebook    | [ca1d482329](https://linux-hardware.org/?probe=ca1d482329) | Jun 27, 2021 |
| Acer          | EG43LMK                     | Desktop     | [5df39d6ba0](https://linux-hardware.org/?probe=5df39d6ba0) | Jun 26, 2021 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [77c68fb077](https://linux-hardware.org/?probe=77c68fb077) | Jun 23, 2021 |
| MSI           | B85M-E45                    | Desktop     | [5508d6a84e](https://linux-hardware.org/?probe=5508d6a84e) | Jun 23, 2021 |
| Lenovo        | ThinkPad T460s 20FA0047M... | Notebook    | [eeb383631b](https://linux-hardware.org/?probe=eeb383631b) | Jun 20, 2021 |
| Lenovo        | ThinkPad T520 4243W83       | Notebook    | [b17a1f2c15](https://linux-hardware.org/?probe=b17a1f2c15) | Jun 19, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [09ff787c3f](https://linux-hardware.org/?probe=09ff787c3f) | Jun 17, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [b64bd1afcd](https://linux-hardware.org/?probe=b64bd1afcd) | Jun 17, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | Notebook    | [bbedefdee0](https://linux-hardware.org/?probe=bbedefdee0) | Jun 16, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [41972327e1](https://linux-hardware.org/?probe=41972327e1) | Jun 15, 2021 |
| MSI           | B75MA-P45                   | Desktop     | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [74a4b076a9](https://linux-hardware.org/?probe=74a4b076a9) | Jun 13, 2021 |
| Lenovo        | ThinkPad T440p 20AW0048G... | Notebook    | [8b1ba139f9](https://linux-hardware.org/?probe=8b1ba139f9) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | Notebook    | [9674952e07](https://linux-hardware.org/?probe=9674952e07) | Jun 11, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | Notebook    | [b39699b009](https://linux-hardware.org/?probe=b39699b009) | Jun 11, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [382c24055c](https://linux-hardware.org/?probe=382c24055c) | Jun 09, 2021 |
| Lenovo        | ThinkPad T410s 291236G      | Notebook    | [ebbdc74a27](https://linux-hardware.org/?probe=ebbdc74a27) | Jun 06, 2021 |
| HP            | EliteBook x360 1040 G5      | Convertible | [3af4716969](https://linux-hardware.org/?probe=3af4716969) | Jun 06, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9cfdd32388](https://linux-hardware.org/?probe=9cfdd32388) | Jun 04, 2021 |
| Acer          | Nitro AN515-42              | Notebook    | [28aadacd07](https://linux-hardware.org/?probe=28aadacd07) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | Notebook    | [aef8c27b50](https://linux-hardware.org/?probe=aef8c27b50) | May 31, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | Notebook    | [e67f4b0fd4](https://linux-hardware.org/?probe=e67f4b0fd4) | May 31, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| Dell          | 015C68 A02                  | Server      | [0335142464](https://linux-hardware.org/?probe=0335142464) | May 29, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [7fd687d091](https://linux-hardware.org/?probe=7fd687d091) | May 29, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f0145b568f](https://linux-hardware.org/?probe=f0145b568f) | May 27, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | Notebook    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| ASUSTek       | N53TK                       | Notebook    | [cee81adbaf](https://linux-hardware.org/?probe=cee81adbaf) | May 25, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8c072ea1c4](https://linux-hardware.org/?probe=8c072ea1c4) | May 24, 2021 |
| Acer          | Aspire 5745G                | Notebook    | [30f455f132](https://linux-hardware.org/?probe=30f455f132) | May 22, 2021 |
| HP            | Spectre Pro x360 G2         | Notebook    | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| Acer          | Aspire 5745G                | Notebook    | [cb987a733a](https://linux-hardware.org/?probe=cb987a733a) | May 15, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [4550202db3](https://linux-hardware.org/?probe=4550202db3) | May 15, 2021 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [1cf830acd9](https://linux-hardware.org/?probe=1cf830acd9) | May 13, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [633cde303a](https://linux-hardware.org/?probe=633cde303a) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [ec046b0e9c](https://linux-hardware.org/?probe=ec046b0e9c) | May 12, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [c4b7c3340c](https://linux-hardware.org/?probe=c4b7c3340c) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [50e2395959](https://linux-hardware.org/?probe=50e2395959) | May 11, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [3d2e6af706](https://linux-hardware.org/?probe=3d2e6af706) | May 10, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [87d92ce1b4](https://linux-hardware.org/?probe=87d92ce1b4) | May 08, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [766557aeb8](https://linux-hardware.org/?probe=766557aeb8) | May 07, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [4a03c325a9](https://linux-hardware.org/?probe=4a03c325a9) | May 06, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [7aa400cdbf](https://linux-hardware.org/?probe=7aa400cdbf) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [c381bf1a74](https://linux-hardware.org/?probe=c381bf1a74) | May 04, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [f83b83c1f0](https://linux-hardware.org/?probe=f83b83c1f0) | May 04, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [c016fc8897](https://linux-hardware.org/?probe=c016fc8897) | May 03, 2021 |
| Toshiba       | Satellite L510              | Notebook    | [01753d1f93](https://linux-hardware.org/?probe=01753d1f93) | May 02, 2021 |
| Acer          | TravelMate 8472             | Notebook    | [bdf53780fb](https://linux-hardware.org/?probe=bdf53780fb) | May 01, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [0e4a62b59f](https://linux-hardware.org/?probe=0e4a62b59f) | Apr 29, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [bd1254fe8d](https://linux-hardware.org/?probe=bd1254fe8d) | Apr 28, 2021 |
| Lenovo        | ThinkPad T490s 20NX0054M... | Notebook    | [4cc25622a5](https://linux-hardware.org/?probe=4cc25622a5) | Apr 28, 2021 |
| Acer          | TravelMate 8472             | Notebook    | [84fea7d029](https://linux-hardware.org/?probe=84fea7d029) | Apr 25, 2021 |
| Acer          | TravelMate 8472             | Notebook    | [a4aafc8541](https://linux-hardware.org/?probe=a4aafc8541) | Apr 25, 2021 |
| MSI           | MS-175A                     | Notebook    | [3e3f73559d](https://linux-hardware.org/?probe=3e3f73559d) | Apr 23, 2021 |
| MSI           | MS-175A                     | Notebook    | [22e9e676d9](https://linux-hardware.org/?probe=22e9e676d9) | Apr 23, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [58df3a61b0](https://linux-hardware.org/?probe=58df3a61b0) | Apr 21, 2021 |
| Dell          | Precision M4500             | Notebook    | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [afb9057dda](https://linux-hardware.org/?probe=afb9057dda) | Apr 16, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | Notebook    | [67c2373bdf](https://linux-hardware.org/?probe=67c2373bdf) | Apr 15, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | Notebook    | [db960abcdb](https://linux-hardware.org/?probe=db960abcdb) | Apr 15, 2021 |
| HP            | ENVY x360 NoteBook PC       | Convertible | [235d55372b](https://linux-hardware.org/?probe=235d55372b) | Apr 14, 2021 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [7ab07ae1e9](https://linux-hardware.org/?probe=7ab07ae1e9) | Apr 11, 2021 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [174dc97643](https://linux-hardware.org/?probe=174dc97643) | Apr 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2116d4313c](https://linux-hardware.org/?probe=2116d4313c) | Apr 11, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [59c7b4d6ff](https://linux-hardware.org/?probe=59c7b4d6ff) | Apr 10, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [cf23d87096](https://linux-hardware.org/?probe=cf23d87096) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | Notebook    | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [1631f6bb81](https://linux-hardware.org/?probe=1631f6bb81) | Apr 06, 2021 |
| ASUSTek       | F2A85-M                     | Desktop     | [9548d9f0c6](https://linux-hardware.org/?probe=9548d9f0c6) | Apr 06, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [6d2b17825a](https://linux-hardware.org/?probe=6d2b17825a) | Apr 05, 2021 |
| Dell          | Latitude E6530              | Notebook    | [0078b55697](https://linux-hardware.org/?probe=0078b55697) | Apr 05, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9db70676f4](https://linux-hardware.org/?probe=9db70676f4) | Apr 05, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1d9693a3dc](https://linux-hardware.org/?probe=1d9693a3dc) | Apr 05, 2021 |
| HP            | 1790                        | Desktop     | [d03e7a12c6](https://linux-hardware.org/?probe=d03e7a12c6) | Apr 04, 2021 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [5978e08085](https://linux-hardware.org/?probe=5978e08085) | Apr 02, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a5268098b2](https://linux-hardware.org/?probe=a5268098b2) | Apr 02, 2021 |
| Dell          | Studio 1747                 | Notebook    | [31c1b6a828](https://linux-hardware.org/?probe=31c1b6a828) | Apr 01, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [393b9a2647](https://linux-hardware.org/?probe=393b9a2647) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6a1ee4ca94](https://linux-hardware.org/?probe=6a1ee4ca94) | Mar 31, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [394a2510d4](https://linux-hardware.org/?probe=394a2510d4) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | Desktop     | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [6189b0e033](https://linux-hardware.org/?probe=6189b0e033) | Mar 27, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [df09bd2c58](https://linux-hardware.org/?probe=df09bd2c58) | Mar 25, 2021 |
| ASRock        | B450M Pro4-F                | Desktop     | [c7223020fe](https://linux-hardware.org/?probe=c7223020fe) | Mar 25, 2021 |
| Dell          | Latitude E6530              | Notebook    | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad X201 4492A23       | Notebook    | [0cace83a52](https://linux-hardware.org/?probe=0cace83a52) | Mar 23, 2021 |
| ASUSTek       | GL553VW                     | Notebook    | [7d8aed9645](https://linux-hardware.org/?probe=7d8aed9645) | Mar 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3e9c3b2719](https://linux-hardware.org/?probe=3e9c3b2719) | Mar 18, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [2ccff038d2](https://linux-hardware.org/?probe=2ccff038d2) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [79b5d4aed8](https://linux-hardware.org/?probe=79b5d4aed8) | Mar 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [980941367e](https://linux-hardware.org/?probe=980941367e) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [ac92ab9404](https://linux-hardware.org/?probe=ac92ab9404) | Mar 15, 2021 |
| HP            | 802F                        | Desktop     | [9ea8632891](https://linux-hardware.org/?probe=9ea8632891) | Mar 14, 2021 |
| MSI           | X99A RAIDER                 | Desktop     | [6f27ffd7aa](https://linux-hardware.org/?probe=6f27ffd7aa) | Mar 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [1725699a96](https://linux-hardware.org/?probe=1725699a96) | Mar 12, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [f55532e284](https://linux-hardware.org/?probe=f55532e284) | Mar 12, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e74933164b](https://linux-hardware.org/?probe=e74933164b) | Mar 10, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [406b41e802](https://linux-hardware.org/?probe=406b41e802) | Mar 10, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [45f8bdabb0](https://linux-hardware.org/?probe=45f8bdabb0) | Mar 09, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [de6b1ee9fe](https://linux-hardware.org/?probe=de6b1ee9fe) | Mar 09, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [d97eb7724a](https://linux-hardware.org/?probe=d97eb7724a) | Mar 04, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [9f523080d5](https://linux-hardware.org/?probe=9f523080d5) | Mar 03, 2021 |
| Dell          | Precision 5550              | Notebook    | [98abf3a7d0](https://linux-hardware.org/?probe=98abf3a7d0) | Mar 02, 2021 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [9625a9c184](https://linux-hardware.org/?probe=9625a9c184) | Feb 26, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8235a48b49](https://linux-hardware.org/?probe=8235a48b49) | Feb 26, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [22a4daed00](https://linux-hardware.org/?probe=22a4daed00) | Feb 25, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [7c24c07795](https://linux-hardware.org/?probe=7c24c07795) | Feb 25, 2021 |
| Dell          | 0NK70N A03                  | Desktop     | [5354c0cb90](https://linux-hardware.org/?probe=5354c0cb90) | Feb 22, 2021 |
| HP            | 2B35                        | Desktop     | [ab5c723699](https://linux-hardware.org/?probe=ab5c723699) | Feb 20, 2021 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [a2fdf109b0](https://linux-hardware.org/?probe=a2fdf109b0) | Feb 20, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [455cf08e86](https://linux-hardware.org/?probe=455cf08e86) | Feb 20, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [db4bc9fa7a](https://linux-hardware.org/?probe=db4bc9fa7a) | Feb 20, 2021 |
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [2bf00440b7](https://linux-hardware.org/?probe=2bf00440b7) | Feb 18, 2021 |
| Dell          | 0MN1TX A01                  | Desktop     | [ebc826cccc](https://linux-hardware.org/?probe=ebc826cccc) | Feb 18, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [01c84ea037](https://linux-hardware.org/?probe=01c84ea037) | Feb 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [84b15e21ec](https://linux-hardware.org/?probe=84b15e21ec) | Feb 17, 2021 |
| Acer          | Predator G3-605             | Desktop     | [f1a8ae2c26](https://linux-hardware.org/?probe=f1a8ae2c26) | Feb 17, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | Notebook    | [626009a335](https://linux-hardware.org/?probe=626009a335) | Feb 16, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | Desktop     | [c445cf637b](https://linux-hardware.org/?probe=c445cf637b) | Feb 15, 2021 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [d11dd1d1a0](https://linux-hardware.org/?probe=d11dd1d1a0) | Feb 14, 2021 |
| Packard Be... | SJV50MV                     | Notebook    | [aba113ee3f](https://linux-hardware.org/?probe=aba113ee3f) | Feb 14, 2021 |
| MSI           | X299 SLI PLUS               | Desktop     | [1499657b8c](https://linux-hardware.org/?probe=1499657b8c) | Feb 13, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [6af569fcf4](https://linux-hardware.org/?probe=6af569fcf4) | Feb 13, 2021 |
| Lenovo        | ThinkPad L450 20DT001NMN    | Notebook    | [9a71946a9e](https://linux-hardware.org/?probe=9a71946a9e) | Feb 13, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [743d5820cc](https://linux-hardware.org/?probe=743d5820cc) | Feb 13, 2021 |
| Lenovo        | ThinkPad L450 20DT001NMN    | Notebook    | [f43d50a826](https://linux-hardware.org/?probe=f43d50a826) | Feb 13, 2021 |
| ASUSTek       | X55U                        | Notebook    | [aea7a001db](https://linux-hardware.org/?probe=aea7a001db) | Feb 13, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [a514810ae0](https://linux-hardware.org/?probe=a514810ae0) | Feb 11, 2021 |
| Unknown       | T3 MRD                      | Notebook    | [a71b7acc18](https://linux-hardware.org/?probe=a71b7acc18) | Feb 10, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | Notebook    | [f26de119c9](https://linux-hardware.org/?probe=f26de119c9) | Feb 08, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | Notebook    | [670ce5270a](https://linux-hardware.org/?probe=670ce5270a) | Feb 07, 2021 |
| Acer          | NG-AN515-52-74W6            | Notebook    | [70574e752f](https://linux-hardware.org/?probe=70574e752f) | Feb 05, 2021 |
| Clevo         | P170EM                      | Notebook    | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| ASUSTek       | N501VW                      | Notebook    | [a5a63c6343](https://linux-hardware.org/?probe=a5a63c6343) | Feb 01, 2021 |
| Acer          | Aspire M3-581TG             | Notebook    | [f87979122a](https://linux-hardware.org/?probe=f87979122a) | Jan 31, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [c71286b553](https://linux-hardware.org/?probe=c71286b553) | Jan 31, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [590fdfe6bb](https://linux-hardware.org/?probe=590fdfe6bb) | Jan 30, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | Notebook    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Lenovo        | ThinkPad T500 22439AG       | Notebook    | [fe8ffb1fc3](https://linux-hardware.org/?probe=fe8ffb1fc3) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a2b88b8f9d](https://linux-hardware.org/?probe=a2b88b8f9d) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [29f9f04453](https://linux-hardware.org/?probe=29f9f04453) | Jan 27, 2021 |
| Lenovo        | ThinkPad T480 20L6002DMX    | Notebook    | [5dd69602d6](https://linux-hardware.org/?probe=5dd69602d6) | Jan 27, 2021 |
| HP            | ProLiant DL580 G7           | Server      | [e93d128090](https://linux-hardware.org/?probe=e93d128090) | Jan 25, 2021 |
| ASUSTek       | GL753VE                     | Notebook    | [af8e0933c0](https://linux-hardware.org/?probe=af8e0933c0) | Jan 24, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [897000022a](https://linux-hardware.org/?probe=897000022a) | Jan 22, 2021 |
| ASUSTek       | P8Z77-M                     | Desktop     | [d60b967710](https://linux-hardware.org/?probe=d60b967710) | Jan 22, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [3d8b11fbf3](https://linux-hardware.org/?probe=3d8b11fbf3) | Jan 20, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [7a840d41b2](https://linux-hardware.org/?probe=7a840d41b2) | Jan 19, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [daeea162bf](https://linux-hardware.org/?probe=daeea162bf) | Jan 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [aca39bcba0](https://linux-hardware.org/?probe=aca39bcba0) | Jan 18, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [0900f71645](https://linux-hardware.org/?probe=0900f71645) | Jan 17, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d3150c1175](https://linux-hardware.org/?probe=d3150c1175) | Jan 14, 2021 |
| MSI           | GE72VR 7RF                  | Notebook    | [1dfd19668d](https://linux-hardware.org/?probe=1dfd19668d) | Jan 14, 2021 |
| Acer          | NU-A515-44-R68D             | Notebook    | [f45afd1e14](https://linux-hardware.org/?probe=f45afd1e14) | Jan 12, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [0d39b0f1de](https://linux-hardware.org/?probe=0d39b0f1de) | Jan 10, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [69a7ec5b7c](https://linux-hardware.org/?probe=69a7ec5b7c) | Jan 07, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [5761cc2a05](https://linux-hardware.org/?probe=5761cc2a05) | Jan 06, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [69a5abe225](https://linux-hardware.org/?probe=69a5abe225) | Jan 05, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5bf107cf29](https://linux-hardware.org/?probe=5bf107cf29) | Jan 04, 2021 |
| ASUSTek       | GL552JX                     | Notebook    | [5dd9cde584](https://linux-hardware.org/?probe=5dd9cde584) | Jan 03, 2021 |
| ASUSTek       | GL552JX                     | Notebook    | [4dfc0f1909](https://linux-hardware.org/?probe=4dfc0f1909) | Jan 03, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [70d4988c38](https://linux-hardware.org/?probe=70d4988c38) | Dec 30, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [bef81325c0](https://linux-hardware.org/?probe=bef81325c0) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | Desktop     | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| TYAN Compu... | S2895 Thunder K8WE S2895    | Server      | [768571b831](https://linux-hardware.org/?probe=768571b831) | Dec 26, 2020 |
| ASUSTek       | G75VW                       | Notebook    | [d04692210c](https://linux-hardware.org/?probe=d04692210c) | Dec 23, 2020 |
| ASUSTek       | G75VW                       | Notebook    | [cc1a212c60](https://linux-hardware.org/?probe=cc1a212c60) | Dec 23, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [656256db83](https://linux-hardware.org/?probe=656256db83) | Dec 22, 2020 |
| TYAN Compu... | S2895 Thunder K8WE S2895    | Server      | [f879fd97f7](https://linux-hardware.org/?probe=f879fd97f7) | Dec 21, 2020 |
| ASUSTek       | N61Ja                       | Notebook    | [324c64905b](https://linux-hardware.org/?probe=324c64905b) | Dec 20, 2020 |
| Dell          | Latitude E6420              | Notebook    | [d4e4d15cf4](https://linux-hardware.org/?probe=d4e4d15cf4) | Dec 20, 2020 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [1520dcde71](https://linux-hardware.org/?probe=1520dcde71) | Dec 20, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [03fbf815fb](https://linux-hardware.org/?probe=03fbf815fb) | Dec 19, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [6cff41d0d5](https://linux-hardware.org/?probe=6cff41d0d5) | Dec 18, 2020 |
| Acer          | Swift SF514-51              | Notebook    | [f04b672d42](https://linux-hardware.org/?probe=f04b672d42) | Dec 15, 2020 |
| Acer          | Swift SF514-51              | Notebook    | [31b51cc2b0](https://linux-hardware.org/?probe=31b51cc2b0) | Dec 13, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [7a59304f76](https://linux-hardware.org/?probe=7a59304f76) | Dec 08, 2020 |
| ASUSTek       | ROG STRIX B460-F GAMING     | Desktop     | [3673aeec97](https://linux-hardware.org/?probe=3673aeec97) | Dec 07, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e9fb942639](https://linux-hardware.org/?probe=e9fb942639) | Dec 04, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [d164834ae1](https://linux-hardware.org/?probe=d164834ae1) | Dec 03, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [5031a2060f](https://linux-hardware.org/?probe=5031a2060f) | Dec 03, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [b30cae7041](https://linux-hardware.org/?probe=b30cae7041) | Dec 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [80b2a9b7a0](https://linux-hardware.org/?probe=80b2a9b7a0) | Dec 01, 2020 |
| Dell          | Precision 5530              | Notebook    | [2d3e299290](https://linux-hardware.org/?probe=2d3e299290) | Nov 29, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [c27456cd80](https://linux-hardware.org/?probe=c27456cd80) | Nov 28, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [38c026cbb9](https://linux-hardware.org/?probe=38c026cbb9) | Nov 28, 2020 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [0b39212390](https://linux-hardware.org/?probe=0b39212390) | Nov 26, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [cb0b2991f5](https://linux-hardware.org/?probe=cb0b2991f5) | Nov 26, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [29f9bd8133](https://linux-hardware.org/?probe=29f9bd8133) | Nov 26, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [c7a03e79d1](https://linux-hardware.org/?probe=c7a03e79d1) | Nov 26, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [44f18b2c9c](https://linux-hardware.org/?probe=44f18b2c9c) | Nov 25, 2020 |
| Lenovo        | 0800-E3G                    | Desktop     | [82f0cc6d73](https://linux-hardware.org/?probe=82f0cc6d73) | Nov 24, 2020 |
| Lenovo        | 0800-E3G                    | Desktop     | [f7a3cae158](https://linux-hardware.org/?probe=f7a3cae158) | Nov 24, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7911fae966](https://linux-hardware.org/?probe=7911fae966) | Nov 23, 2020 |
| HP            | 0AA8h                       | Desktop     | [5b9abc7e6e](https://linux-hardware.org/?probe=5b9abc7e6e) | Nov 21, 2020 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [4497d1907e](https://linux-hardware.org/?probe=4497d1907e) | Nov 21, 2020 |
| HP            | ENVY x360 NoteBook PC       | Convertible | [2481d41538](https://linux-hardware.org/?probe=2481d41538) | Nov 20, 2020 |
| Dell          | XPS 15 9530                 | Notebook    | [498a6352ca](https://linux-hardware.org/?probe=498a6352ca) | Nov 17, 2020 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [1945ae5a25](https://linux-hardware.org/?probe=1945ae5a25) | Nov 16, 2020 |
| HP            | Presario CQ56               | Notebook    | [dc13808697](https://linux-hardware.org/?probe=dc13808697) | Nov 15, 2020 |
| HP            | EliteBook 840 G4            | Notebook    | [5476e88101](https://linux-hardware.org/?probe=5476e88101) | Nov 13, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [94c7b24f6f](https://linux-hardware.org/?probe=94c7b24f6f) | Nov 12, 2020 |
| HP            | EliteBook 840 G4            | Notebook    | [365d184384](https://linux-hardware.org/?probe=365d184384) | Nov 12, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [b1d5b6d202](https://linux-hardware.org/?probe=b1d5b6d202) | Nov 11, 2020 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [8aaa52acfe](https://linux-hardware.org/?probe=8aaa52acfe) | Nov 11, 2020 |
| Samsung       | 870Z5G/880Z5F               | Notebook    | [1edba5531d](https://linux-hardware.org/?probe=1edba5531d) | Nov 11, 2020 |
| Samsung       | 870Z5G/880Z5F               | Notebook    | [c8f54522bc](https://linux-hardware.org/?probe=c8f54522bc) | Nov 11, 2020 |
| Lenovo        | ThinkPad L450 20DT001NMN    | Notebook    | [2c04018d8b](https://linux-hardware.org/?probe=2c04018d8b) | Nov 10, 2020 |
| Lenovo        | ThinkPad L450 20DT001NMN    | Notebook    | [e1bfa030b6](https://linux-hardware.org/?probe=e1bfa030b6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d80b3d6e1b](https://linux-hardware.org/?probe=d80b3d6e1b) | Nov 10, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [535bb960c8](https://linux-hardware.org/?probe=535bb960c8) | Nov 09, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [de48058cc4](https://linux-hardware.org/?probe=de48058cc4) | Nov 07, 2020 |
| Lenovo        | ThinkPad T470s 20HGS33N0... | Notebook    | [46e54eb12c](https://linux-hardware.org/?probe=46e54eb12c) | Nov 05, 2020 |
| ASUSTek       | E203NA                      | Notebook    | [83f3bbfada](https://linux-hardware.org/?probe=83f3bbfada) | Nov 05, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8cc1c3b402](https://linux-hardware.org/?probe=8cc1c3b402) | Nov 05, 2020 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [acabcd3fe5](https://linux-hardware.org/?probe=acabcd3fe5) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7cc067fb03](https://linux-hardware.org/?probe=7cc067fb03) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2a45f74eda](https://linux-hardware.org/?probe=2a45f74eda) | Nov 02, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [43a7cef240](https://linux-hardware.org/?probe=43a7cef240) | Nov 01, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [d44d323649](https://linux-hardware.org/?probe=d44d323649) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [1e3afeadf1](https://linux-hardware.org/?probe=1e3afeadf1) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [c36062c763](https://linux-hardware.org/?probe=c36062c763) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [509ec4584c](https://linux-hardware.org/?probe=509ec4584c) | Oct 31, 2020 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [5ec26083ab](https://linux-hardware.org/?probe=5ec26083ab) | Oct 31, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [2b56b5b407](https://linux-hardware.org/?probe=2b56b5b407) | Oct 30, 2020 |
| ASUSTek       | P8Z77-M                     | Desktop     | [ca7e76d821](https://linux-hardware.org/?probe=ca7e76d821) | Oct 30, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [01bfabd117](https://linux-hardware.org/?probe=01bfabd117) | Oct 29, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [4b0d12f5b0](https://linux-hardware.org/?probe=4b0d12f5b0) | Oct 29, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [aed3a57697](https://linux-hardware.org/?probe=aed3a57697) | Oct 28, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [22041bab6b](https://linux-hardware.org/?probe=22041bab6b) | Oct 28, 2020 |
| HP            | Pavilion g6                 | Notebook    | [de072f8297](https://linux-hardware.org/?probe=de072f8297) | Oct 26, 2020 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [95b9da5ba3](https://linux-hardware.org/?probe=95b9da5ba3) | Oct 26, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [d7a8999c8f](https://linux-hardware.org/?probe=d7a8999c8f) | Oct 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4c38164a20](https://linux-hardware.org/?probe=4c38164a20) | Oct 21, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [47c1ff9096](https://linux-hardware.org/?probe=47c1ff9096) | Oct 19, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [40e091c5f4](https://linux-hardware.org/?probe=40e091c5f4) | Oct 16, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [fbdc47c84f](https://linux-hardware.org/?probe=fbdc47c84f) | Oct 15, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [d246c4d7c9](https://linux-hardware.org/?probe=d246c4d7c9) | Oct 15, 2020 |
| ASRock        | FM2A75M-HD+                 | Desktop     | [eb66178779](https://linux-hardware.org/?probe=eb66178779) | Oct 13, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [cad3c5d0ba](https://linux-hardware.org/?probe=cad3c5d0ba) | Oct 13, 2020 |
| Gigabyte      | MQLP5AP-00                  | Desktop     | [bec4249ac9](https://linux-hardware.org/?probe=bec4249ac9) | Oct 12, 2020 |
| LAMINA        | T-1012B NORD                | Notebook    | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c547b7b23e](https://linux-hardware.org/?probe=c547b7b23e) | Oct 11, 2020 |
| Clevo         | W150HRM                     | Notebook    | [8859e15cb5](https://linux-hardware.org/?probe=8859e15cb5) | Oct 10, 2020 |
| Nokia         | N900                        | Notebook    | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [93f3a15a9e](https://linux-hardware.org/?probe=93f3a15a9e) | Oct 04, 2020 |
| Toshiba       | Satellite C55-A-1MW         | Notebook    | [a0a0d949d6](https://linux-hardware.org/?probe=a0a0d949d6) | Oct 03, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [80b8079281](https://linux-hardware.org/?probe=80b8079281) | Oct 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [06cc9298b0](https://linux-hardware.org/?probe=06cc9298b0) | Oct 02, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4fa10cd09d](https://linux-hardware.org/?probe=4fa10cd09d) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [07fab4cd26](https://linux-hardware.org/?probe=07fab4cd26) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [7e8f9659ac](https://linux-hardware.org/?probe=7e8f9659ac) | Sep 28, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [f3313ab891](https://linux-hardware.org/?probe=f3313ab891) | Sep 28, 2020 |
| Gigabyte      | H310N                       | Desktop     | [af0cc1312f](https://linux-hardware.org/?probe=af0cc1312f) | Sep 28, 2020 |
| MSI           | X99A RAIDER                 | Desktop     | [dad099d968](https://linux-hardware.org/?probe=dad099d968) | Sep 28, 2020 |
| Apple         | MacBook2,1                  | Notebook    | [a11af3313e](https://linux-hardware.org/?probe=a11af3313e) | Sep 28, 2020 |
| ASUSTek       | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [815a2e1378](https://linux-hardware.org/?probe=815a2e1378) | Sep 26, 2020 |
| ASRock        | X570 Taichi                 | Desktop     | [60d17efc7c](https://linux-hardware.org/?probe=60d17efc7c) | Sep 25, 2020 |
| HP            | ProBook 6550b               | Notebook    | [b5e0d7059d](https://linux-hardware.org/?probe=b5e0d7059d) | Sep 25, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [f58f907928](https://linux-hardware.org/?probe=f58f907928) | Sep 20, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [88f6a44ae4](https://linux-hardware.org/?probe=88f6a44ae4) | Sep 17, 2020 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [a7176bb601](https://linux-hardware.org/?probe=a7176bb601) | Sep 15, 2020 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [21f025a337](https://linux-hardware.org/?probe=21f025a337) | Sep 15, 2020 |
| ASUSTek       | P9X79 LE                    | Desktop     | [6cb5707322](https://linux-hardware.org/?probe=6cb5707322) | Sep 15, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | Desktop     | [576daf4d41](https://linux-hardware.org/?probe=576daf4d41) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [726f3b1370](https://linux-hardware.org/?probe=726f3b1370) | Sep 14, 2020 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [d6885cac52](https://linux-hardware.org/?probe=d6885cac52) | Sep 14, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c9adcfd59a](https://linux-hardware.org/?probe=c9adcfd59a) | Sep 13, 2020 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [5aaf924422](https://linux-hardware.org/?probe=5aaf924422) | Sep 13, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| ASUSTek       | NARRA2                      | Desktop     | [54160f4cb5](https://linux-hardware.org/?probe=54160f4cb5) | Sep 10, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [f604a231fa](https://linux-hardware.org/?probe=f604a231fa) | Sep 10, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [08210e360a](https://linux-hardware.org/?probe=08210e360a) | Sep 10, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [1b230fa054](https://linux-hardware.org/?probe=1b230fa054) | Sep 07, 2020 |
| Lenovo        | ThinkPad S2 20GKS03C00      | Notebook    | [3db4820f00](https://linux-hardware.org/?probe=3db4820f00) | Sep 05, 2020 |
| ASUSTek       | X99-E WS                    | Desktop     | [e37af5c1c2](https://linux-hardware.org/?probe=e37af5c1c2) | Sep 05, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b1248e2b3b](https://linux-hardware.org/?probe=b1248e2b3b) | Sep 05, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [fcce649648](https://linux-hardware.org/?probe=fcce649648) | Sep 04, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [cf16a05fb6](https://linux-hardware.org/?probe=cf16a05fb6) | Sep 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [d97dc026d9](https://linux-hardware.org/?probe=d97dc026d9) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f3f962b06](https://linux-hardware.org/?probe=8f3f962b06) | Sep 03, 2020 |
| Clevo         | P15xEMx                     | Notebook    | [6aa236976d](https://linux-hardware.org/?probe=6aa236976d) | Sep 03, 2020 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [62bf637d91](https://linux-hardware.org/?probe=62bf637d91) | Sep 02, 2020 |
| Lenovo        | ThinkPad X201 3323BSG       | Notebook    | [16840940a8](https://linux-hardware.org/?probe=16840940a8) | Sep 02, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [e87474d550](https://linux-hardware.org/?probe=e87474d550) | Aug 31, 2020 |
| Dell          | Latitude E7450              | Notebook    | [96a90e1ad3](https://linux-hardware.org/?probe=96a90e1ad3) | Aug 30, 2020 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [a0f29a4ba9](https://linux-hardware.org/?probe=a0f29a4ba9) | Aug 30, 2020 |
| Dell          | 0WPG9H A01                  | All in one  | [3db3c89532](https://linux-hardware.org/?probe=3db3c89532) | Aug 27, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [b3bb6fe3dc](https://linux-hardware.org/?probe=b3bb6fe3dc) | Aug 27, 2020 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [c4b10f778e](https://linux-hardware.org/?probe=c4b10f778e) | Aug 25, 2020 |
| ASUSTek       | X99-E WS                    | Desktop     | [ed9d8c885d](https://linux-hardware.org/?probe=ed9d8c885d) | Aug 25, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d045f2314f](https://linux-hardware.org/?probe=d045f2314f) | Aug 24, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [a59b0acdfe](https://linux-hardware.org/?probe=a59b0acdfe) | Aug 24, 2020 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [904934805a](https://linux-hardware.org/?probe=904934805a) | Aug 19, 2020 |
| Lenovo        | ThinkPad X250 20CLS8MD00    | Notebook    | [cdc5a7009e](https://linux-hardware.org/?probe=cdc5a7009e) | Aug 18, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [b15339e143](https://linux-hardware.org/?probe=b15339e143) | Aug 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a83273e54](https://linux-hardware.org/?probe=2a83273e54) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [c6d5a14495](https://linux-hardware.org/?probe=c6d5a14495) | Aug 12, 2020 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [143846fb82](https://linux-hardware.org/?probe=143846fb82) | Aug 12, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [e0855b4bf3](https://linux-hardware.org/?probe=e0855b4bf3) | Aug 09, 2020 |
| HP            | G62                         | Notebook    | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [9b4f4dc28b](https://linux-hardware.org/?probe=9b4f4dc28b) | Aug 07, 2020 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5eed133928](https://linux-hardware.org/?probe=5eed133928) | Aug 05, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [edfa113106](https://linux-hardware.org/?probe=edfa113106) | Aug 03, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [d89e8704d1](https://linux-hardware.org/?probe=d89e8704d1) | Aug 03, 2020 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | Notebook    | [58887ecbe5](https://linux-hardware.org/?probe=58887ecbe5) | Jul 28, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [917bed383b](https://linux-hardware.org/?probe=917bed383b) | Jul 26, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [552295571e](https://linux-hardware.org/?probe=552295571e) | Jul 26, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [c91081e069](https://linux-hardware.org/?probe=c91081e069) | Jul 26, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [475dbf0ad7](https://linux-hardware.org/?probe=475dbf0ad7) | Jul 25, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cd32144f93](https://linux-hardware.org/?probe=cd32144f93) | Jul 25, 2020 |
| Notebook      | W230SD                      | Notebook    | [17334fe86e](https://linux-hardware.org/?probe=17334fe86e) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [2617c14fa9](https://linux-hardware.org/?probe=2617c14fa9) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [16ae7ff56d](https://linux-hardware.org/?probe=16ae7ff56d) | Jul 23, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c6f296962b](https://linux-hardware.org/?probe=c6f296962b) | Jul 23, 2020 |
| Packard Be... | EasyNote_BU45               | Notebook    | [8e4b6e270b](https://linux-hardware.org/?probe=8e4b6e270b) | Jul 21, 2020 |
| Dell          | Latitude 7400               | Notebook    | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| HP            | EliteBook 850 G3            | Notebook    | [6bdfab8f44](https://linux-hardware.org/?probe=6bdfab8f44) | Jul 19, 2020 |
| HP            | Notebook                    | Notebook    | [47c49601e5](https://linux-hardware.org/?probe=47c49601e5) | Jul 17, 2020 |
| Dell          | Latitude 7400               | Notebook    | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Norway/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 126       | 14.79%  |
| Ubuntu 18.04                 | 61        | 7.16%   |
| Debian 11                    | 23        | 2.7%    |
| OpenMandriva 4.2             | 20        | 2.35%   |
| Fedora 35                    | 20        | 2.35%   |
| Ubuntu 22.04                 | 19        | 2.23%   |
| Ubuntu 20.10                 | 19        | 2.23%   |
| Pop!_OS 22.04                | 19        | 2.23%   |
| Zorin 16                     | 18        | 2.11%   |
| Arch                         | 18        | 2.11%   |
| Pop!_OS 21.04                | 15        | 1.76%   |
| Arch Rolling                 | 15        | 1.76%   |
| Pop!_OS 21.10                | 14        | 1.64%   |
| OpenMandriva 4.3             | 14        | 1.64%   |
| Fedora 36                    | 14        | 1.64%   |
| Fedora 34                    | 14        | 1.64%   |
| Fedora 31                    | 14        | 1.64%   |
| ArcoLinux Rolling            | 14        | 1.64%   |
| Ubuntu 19.10                 | 13        | 1.53%   |
| Ubuntu 19.04                 | 13        | 1.53%   |
| KDE neon 20.04               | 13        | 1.53%   |
| Ubuntu 18.10                 | 12        | 1.41%   |
| Pop!_OS 20.10                | 12        | 1.41%   |
| Pop!_OS 20.04                | 12        | 1.41%   |
| Linux Mint 20.2              | 12        | 1.41%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 1.29%   |
| Manjaro                      | 11        | 1.29%   |
| Ubuntu 21.10                 | 9         | 1.06%   |
| Linux Mint 20.1              | 9         | 1.06%   |
| Fedora 32                    | 9         | 1.06%   |
| Debian 10                    | 9         | 1.06%   |
| Zorin 15                     | 8         | 0.94%   |
| Xubuntu 20.04                | 8         | 0.94%   |
| Linux Mint 20.3              | 8         | 0.94%   |
| Fedora 33                    | 8         | 0.94%   |
| Ubuntu 21.04                 | 7         | 0.82%   |
| Linux Mint 19.3              | 7         | 0.82%   |
| Linux Mint 19.1              | 7         | 0.82%   |
| RHEL 7                       | 6         | 0.7%    |
| Manjaro 20.2.1               | 6         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 272       | 33.29%  |
| Fedora        | 78        | 9.55%   |
| Pop!_OS       | 66        | 8.08%   |
| Linux Mint    | 50        | 6.12%   |
| Manjaro       | 41        | 5.02%   |
| Debian        | 40        | 4.9%    |
| OpenMandriva  | 38        | 4.65%   |
| Arch          | 33        | 4.04%   |
| Zorin         | 27        | 3.3%    |
| KDE neon      | 16        | 1.96%   |
| openSUSE      | 15        | 1.84%   |
| ArcoLinux     | 15        | 1.84%   |
| Xubuntu       | 14        | 1.71%   |
| Kubuntu       | 10        | 1.22%   |
| Gentoo        | 9         | 1.1%    |
| Kali          | 8         | 0.98%   |
| Elementary    | 8         | 0.98%   |
| Clear Linux   | 8         | 0.98%   |
| RHEL          | 7         | 0.86%   |
| CentOS        | 7         | 0.86%   |
| Ubuntu MATE   | 6         | 0.73%   |
| Ubuntu Budgie | 6         | 0.73%   |
| ROSA          | 6         | 0.73%   |
| EndeavourOS   | 5         | 0.61%   |
| Solus         | 4         | 0.49%   |
| Ubuntu Unity  | 3         | 0.37%   |
| Lubuntu       | 3         | 0.37%   |
| Xero          | 2         | 0.24%   |
| Ubuntu Studio | 2         | 0.24%   |
| Nobara        | 2         | 0.24%   |
| MX            | 2         | 0.24%   |
| LMDE          | 2         | 0.24%   |
| Alpine        | 2         | 0.24%   |
| Void Linux    | 1         | 0.12%   |
| Rocky Linux   | 1         | 0.12%   |
| PostmarketOS  | 1         | 0.12%   |
| Peppermint    | 1         | 0.12%   |
| Garuda Linux  | 1         | 0.12%   |
| Feren OS      | 1         | 0.12%   |
| Devuan        | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 19        | 2.04%   |
| 5.4.0-42-generic            | 14        | 1.5%    |
| 5.16.7-desktop-1omv4003     | 13        | 1.39%   |
| 5.4.0-58-generic            | 9         | 0.96%   |
| 5.3.0-46-generic            | 9         | 0.96%   |
| 5.15.0-46-generic           | 9         | 0.96%   |
| 4.18.0-16-generic           | 9         | 0.96%   |
| 3.10.0-1062.12.1.el7.x86_64 | 9         | 0.96%   |
| 5.4.0-74-generic            | 8         | 0.86%   |
| 5.4.0-48-generic            | 8         | 0.86%   |
| 5.11.0-40-generic           | 8         | 0.86%   |
| 5.11.0-38-generic           | 8         | 0.86%   |
| 5.8.0-7630-generic          | 7         | 0.75%   |
| 5.8.0-44-generic            | 7         | 0.75%   |
| 5.8.0-43-generic            | 7         | 0.75%   |
| 5.4.0-91-generic            | 7         | 0.75%   |
| 5.4.0-26-generic            | 7         | 0.75%   |
| 5.3.0-40-generic            | 7         | 0.75%   |
| 5.11.0-7620-generic         | 7         | 0.75%   |
| 5.4.0-47-generic            | 6         | 0.64%   |
| 5.4.0-45-generic            | 6         | 0.64%   |
| 5.4.0-29-generic            | 6         | 0.64%   |
| 5.3.0-28-generic            | 6         | 0.64%   |
| 5.15.0-41-generic           | 6         | 0.64%   |
| 5.11.0-27-generic           | 6         | 0.64%   |
| 5.10.0-8-amd64              | 6         | 0.64%   |
| 5.0.0-20-generic            | 6         | 0.64%   |
| 5.8.0-48-generic            | 5         | 0.54%   |
| 5.4.0-72-generic            | 5         | 0.54%   |
| 5.4.0-33-generic            | 5         | 0.54%   |
| 5.3.0-42-generic            | 5         | 0.54%   |
| 5.19.0-76051900-generic     | 5         | 0.54%   |
| 5.18.10-76051810-generic    | 5         | 0.54%   |
| 5.17.5-76051705-generic     | 5         | 0.54%   |
| 5.13.0-7620-generic         | 5         | 0.54%   |
| 5.13.0-39-generic           | 5         | 0.54%   |
| 5.13.0-28-generic           | 5         | 0.54%   |
| 4.18.0-25-generic           | 5         | 0.54%   |
| 5.9.16-1-MANJARO            | 4         | 0.43%   |
| 5.5.5-200.fc31.x86_64       | 4         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 160       | 18.1%   |
| 5.8.0   | 54        | 6.11%   |
| 5.11.0  | 54        | 6.11%   |
| 5.3.0   | 42        | 4.75%   |
| 5.13.0  | 39        | 4.41%   |
| 4.15.0  | 38        | 4.3%    |
| 4.18.0  | 30        | 3.39%   |
| 5.10.0  | 27        | 3.05%   |
| 5.15.0  | 26        | 2.94%   |
| 5.0.0   | 25        | 2.83%   |
| 5.10.14 | 19        | 2.15%   |
| 5.16.7  | 13        | 1.47%   |
| 3.10.0  | 10        | 1.13%   |
| 4.19.0  | 9         | 1.02%   |
| 5.17.5  | 8         | 0.9%    |
| 5.16.0  | 7         | 0.79%   |
| 5.19.0  | 6         | 0.68%   |
| 5.16.11 | 6         | 0.68%   |
| 5.9.16  | 5         | 0.57%   |
| 5.5.5   | 5         | 0.57%   |
| 5.18.10 | 5         | 0.57%   |
| 5.18.0  | 5         | 0.57%   |
| 5.12.4  | 5         | 0.57%   |
| 5.17.15 | 4         | 0.45%   |
| 5.16.15 | 4         | 0.45%   |
| 5.15.8  | 4         | 0.45%   |
| 5.15.5  | 4         | 0.45%   |
| 5.15.4  | 4         | 0.45%   |
| 5.12.9  | 4         | 0.45%   |
| 5.9.8   | 3         | 0.34%   |
| 5.9.11  | 3         | 0.34%   |
| 5.9.0   | 3         | 0.34%   |
| 5.8.16  | 3         | 0.34%   |
| 5.8.12  | 3         | 0.34%   |
| 5.6.0   | 3         | 0.34%   |
| 5.4.14  | 3         | 0.34%   |
| 5.3.11  | 3         | 0.34%   |
| 5.19.11 | 3         | 0.34%   |
| 5.17.9  | 3         | 0.34%   |
| 5.17.6  | 3         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 177       | 20.23%  |
| 5.8     | 70        | 8%      |
| 5.11    | 63        | 7.2%    |
| 5.15    | 61        | 6.97%   |
| 5.13    | 61        | 6.97%   |
| 5.10    | 59        | 6.74%   |
| 5.3     | 51        | 5.83%   |
| 5.16    | 45        | 5.14%   |
| 4.15    | 38        | 4.34%   |
| 4.18    | 33        | 3.77%   |
| 5.17    | 30        | 3.43%   |
| 5.0     | 27        | 3.09%   |
| 5.9     | 21        | 2.4%    |
| 5.19    | 19        | 2.17%   |
| 5.14    | 19        | 2.17%   |
| 5.18    | 18        | 2.06%   |
| 5.12    | 15        | 1.71%   |
| 5.5     | 12        | 1.37%   |
| 5.7     | 11        | 1.26%   |
| 4.19    | 11        | 1.26%   |
| 3.10    | 10        | 1.14%   |
| 5.6     | 8         | 0.91%   |
| 4.9     | 4         | 0.46%   |
| 5.1     | 3         | 0.34%   |
| 5.2     | 2         | 0.23%   |
| 4.4     | 2         | 0.23%   |
| 6.0     | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |
| 4.12    | 1         | 0.11%   |
| 4.10    | 1         | 0.11%   |
| 4.1     | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 772       | 97.11%  |
| i686    | 14        | 1.76%   |
| aarch64 | 8         | 1.01%   |
| armv7l  | 1         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 392       | 47.57%  |
| Unknown           | 129       | 15.66%  |
| KDE5              | 111       | 13.47%  |
| XFCE              | 64        | 7.77%   |
| X-Cinnamon        | 35        | 4.25%   |
| KDE               | 24        | 2.91%   |
| MATE              | 11        | 1.33%   |
| Cinnamon          | 9         | 1.09%   |
| Budgie            | 9         | 1.09%   |
| i3                | 8         | 0.97%   |
| Pantheon          | 6         | 0.73%   |
| GNOME Flashback   | 5         | 0.61%   |
| LXDE              | 4         | 0.49%   |
| Unity             | 3         | 0.36%   |
| LXQt              | 3         | 0.36%   |
| KDE4              | 3         | 0.36%   |
| Yaru:ubuntu:GNOME | 1         | 0.12%   |
| xinit-compat      | 1         | 0.12%   |
| qtile             | 1         | 0.12%   |
| LeftWM            | 1         | 0.12%   |
| i3-with-shmlog    | 1         | 0.12%   |
| GNOME:Phosh       | 1         | 0.12%   |
| Deepin            | 1         | 0.12%   |
| bspwm             | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 626       | 76.25%  |
| Wayland | 107       | 13.03%  |
| Unknown | 68        | 8.28%   |
| Tty     | 20        | 2.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 446       | 54.19%  |
| GDM     | 123       | 14.95%  |
| SDDM    | 99        | 12.03%  |
| LightDM | 66        | 8.02%   |
| GDM3    | 56        | 6.8%    |
| TDM     | 28        | 3.4%    |
| KDM     | 4         | 0.49%   |
| XDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 416       | 51.11%  |
| nb_NO       | 181       | 22.24%  |
| Unknown     | 107       | 13.14%  |
| en_GB       | 47        | 5.77%   |
| C           | 17        | 2.09%   |
| nn_NO       | 13        | 1.6%    |
| en_DK       | 7         | 0.86%   |
| pl_PL       | 5         | 0.61%   |
| de_DE       | 5         | 0.61%   |
| en_IE       | 3         | 0.37%   |
| pt_PT       | 2         | 0.25%   |
| fr_FR       | 2         | 0.25%   |
| ru_RU       | 1         | 0.12%   |
| fi_FI       | 1         | 0.12%   |
| es_ES       | 1         | 0.12%   |
| en_US.utf-8 | 1         | 0.12%   |
| en_CA       | 1         | 0.12%   |
| en_AG       | 1         | 0.12%   |
| en_150      | 1         | 0.12%   |
| en_001      | 1         | 0.12%   |
| el_GR       | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 425       | 52.86%  |
| BIOS | 379       | 47.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 628       | 77.82%  |
| Btrfs   | 78        | 9.67%   |
| Overlay | 43        | 5.33%   |
| Xfs     | 24        | 2.97%   |
| Unknown | 24        | 2.97%   |
| Zfs     | 5         | 0.62%   |
| Ext2    | 4         | 0.5%    |
| Ext3    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 458       | 56.89%  |
| GPT     | 280       | 34.78%  |
| MBR     | 67        | 8.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 697       | 86.26%  |
| Yes       | 111       | 13.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 596       | 73.67%  |
| Yes       | 213       | 26.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 171       | 21.51%  |
| Lenovo                  | 156       | 19.62%  |
| Hewlett-Packard         | 115       | 14.47%  |
| Dell                    | 97        | 12.2%   |
| MSI                     | 47        | 5.91%   |
| Gigabyte Technology     | 40        | 5.03%   |
| Acer                    | 40        | 5.03%   |
| Apple                   | 23        | 2.89%   |
| ASRock                  | 19        | 2.39%   |
| HUAWEI                  | 13        | 1.64%   |
| Toshiba                 | 8         | 1.01%   |
| Samsung Electronics     | 7         | 0.88%   |
| Raspberry Pi Foundation | 7         | 0.88%   |
| Packard Bell            | 7         | 0.88%   |
| Intel                   | 7         | 0.88%   |
| Notebook                | 5         | 0.63%   |
| Unknown                 | 5         | 0.63%   |
| Clevo                   | 4         | 0.5%    |
| Pegatron                | 3         | 0.38%   |
| Microsoft               | 3         | 0.38%   |
| ZOTAC                   | 1         | 0.13%   |
| Wibtek                  | 1         | 0.13%   |
| TYAN Computer           | 1         | 0.13%   |
| Teclast                 | 1         | 0.13%   |
| Supermicro              | 1         | 0.13%   |
| Shuttle                 | 1         | 0.13%   |
| Razer                   | 1         | 0.13%   |
| Nokia                   | 1         | 0.13%   |
| Lenovo Product          | 1         | 0.13%   |
| LAMINA                  | 1         | 0.13%   |
| Intel Client Systems    | 1         | 0.13%   |
| Google                  | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| Fujitsu                 | 1         | 0.13%   |
| Cisco Systems           | 1         | 0.13%   |
| ASRockRack              | 1         | 0.13%   |
| Alienware               | 1         | 0.13%   |
| Acidanthera             | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 13        | 1.64%   |
| HUAWEI MACH-WX9                          | 6         | 0.75%   |
| Unknown                                  | 6         | 0.75%   |
| Dell Precision 5530                      | 5         | 0.63%   |
| Dell PowerEdge R230                      | 5         | 0.63%   |
| HP ProBook 430 G2                        | 4         | 0.5%    |
| ASUS ROG STRIX X570-F GAMING             | 4         | 0.5%    |
| ASUS ROG STRIX B360-F GAMING             | 4         | 0.5%    |
| ASUS M2R-FVM                             | 4         | 0.5%    |
| MSI MS-7885                              | 3         | 0.38%   |
| HUAWEI WRT-WX9                           | 3         | 0.38%   |
| HP OMEN by Laptop                        | 3         | 0.38%   |
| HP EliteBook 8470p                       | 3         | 0.38%   |
| HP EliteBook 840 G6                      | 3         | 0.38%   |
| Gigabyte GA-970A-UD3                     | 3         | 0.38%   |
| Dell XPS 15 9570                         | 3         | 0.38%   |
| Dell XPS 15 9500                         | 3         | 0.38%   |
| Dell XPS 13 9380                         | 3         | 0.38%   |
| Dell OptiPlex 9020                       | 3         | 0.38%   |
| Dell OptiPlex 7010                       | 3         | 0.38%   |
| Dell Latitude E7240                      | 3         | 0.38%   |
| Dell Latitude E5470                      | 3         | 0.38%   |
| ASUS SABERTOOTH P67                      | 3         | 0.38%   |
| ASUS ROG STRIX B550-I GAMING             | 3         | 0.38%   |
| ASUS PRIME X570-P                        | 3         | 0.38%   |
| ASUS P9X79 LE                            | 3         | 0.38%   |
| Apple MacBookPro12,1                     | 3         | 0.38%   |
| RPi Raspberry Pi 4 Model B Rev 1.1       | 2         | 0.25%   |
| RPi Raspberry Pi                         | 2         | 0.25%   |
| MSI MS-7A37                              | 2         | 0.25%   |
| MSI GF63 Thin 11UD                       | 2         | 0.25%   |
| Microsoft Surface Pro 2                  | 2         | 0.25%   |
| Lenovo Z50-70 20354                      | 2         | 0.25%   |
| Lenovo Yoga Slim 7 Pro 14IAH7 82UT       | 2         | 0.25%   |
| Lenovo Yoga Slim 7 14ARE05 82A2          | 2         | 0.25%   |
| Lenovo Y520-15IKBN 80WK                  | 2         | 0.25%   |
| Lenovo ThinkPad X230 23252EG             | 2         | 0.25%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1MX | 2         | 0.25%   |
| Lenovo ThinkPad L450 20DT001NMN          | 2         | 0.25%   |
| HP ProBook 6550b                         | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 102       | 12.83%  |
| HP EliteBook          | 37        | 4.65%   |
| ASUS ROG              | 30        | 3.77%   |
| Dell Latitude         | 27        | 3.4%    |
| Acer Aspire           | 25        | 3.14%   |
| HP ProBook            | 19        | 2.39%   |
| Dell XPS              | 18        | 2.26%   |
| Dell Precision        | 17        | 2.14%   |
| ASUS PRIME            | 17        | 2.14%   |
| Dell OptiPlex         | 15        | 1.89%   |
| Lenovo Yoga           | 13        | 1.64%   |
| ASUS All              | 13        | 1.64%   |
| Dell PowerEdge        | 12        | 1.51%   |
| Lenovo IdeaPad        | 9         | 1.13%   |
| HP ZBook              | 9         | 1.13%   |
| ASUS TUF              | 9         | 1.13%   |
| Lenovo ThinkCentre    | 8         | 1.01%   |
| ASUS VivoBook         | 8         | 1.01%   |
| RPi Raspberry         | 7         | 0.88%   |
| HP Pavilion           | 7         | 0.88%   |
| Toshiba Satellite     | 6         | 0.75%   |
| HUAWEI MACH-WX9       | 6         | 0.75%   |
| Gigabyte X570         | 6         | 0.75%   |
| Dell Inspiron         | 6         | 0.75%   |
| ASUS SABERTOOTH       | 6         | 0.75%   |
| Unknown               | 6         | 0.75%   |
| Packard Bell EasyNote | 5         | 0.63%   |
| HP OMEN               | 5         | 0.63%   |
| HP ENVY               | 5         | 0.63%   |
| HP EliteDesk          | 5         | 0.63%   |
| Acer Swift            | 5         | 0.63%   |
| HP Spectre            | 4         | 0.5%    |
| HP Compaq             | 4         | 0.5%    |
| Gigabyte B550         | 4         | 0.5%    |
| Gigabyte B450         | 4         | 0.5%    |
| ASUS STRIX            | 4         | 0.5%    |
| ASUS P9X79            | 4         | 0.5%    |
| ASUS P8Z77-V          | 4         | 0.5%    |
| ASUS M2R-FVM          | 4         | 0.5%    |
| ASUS CROSSHAIR        | 4         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 93        | 11.7%   |
| 2019    | 92        | 11.57%  |
| 2020    | 79        | 9.94%   |
| 2012    | 65        | 8.18%   |
| 2015    | 63        | 7.92%   |
| 2017    | 62        | 7.8%    |
| 2016    | 53        | 6.67%   |
| 2013    | 50        | 6.29%   |
| 2011    | 49        | 6.16%   |
| 2014    | 46        | 5.79%   |
| 2021    | 36        | 4.53%   |
| 2010    | 36        | 4.53%   |
| 2009    | 24        | 3.02%   |
| 2007    | 12        | 1.51%   |
| 2008    | 11        | 1.38%   |
| 2022    | 7         | 0.88%   |
| Unknown | 7         | 0.88%   |
| 2006    | 6         | 0.75%   |
| 2005    | 3         | 0.38%   |
| 2001    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 440       | 55.35%  |
| Desktop        | 279       | 35.09%  |
| Convertible    | 22        | 2.77%   |
| Server         | 14        | 1.76%   |
| Mini pc        | 13        | 1.64%   |
| All in one     | 12        | 1.51%   |
| System on chip | 8         | 1.01%   |
| Tablet         | 7         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 724       | 90.61%  |
| Enabled  | 75        | 9.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 793       | 99.75%  |
| Yes  | 2         | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 211       | 26.28%  |
| 4.01-8.0        | 177       | 22.04%  |
| 32.01-64.0      | 123       | 15.32%  |
| 8.01-16.0       | 123       | 15.32%  |
| 3.01-4.0        | 103       | 12.83%  |
| 64.01-256.0     | 30        | 3.74%   |
| 1.01-2.0        | 16        | 1.99%   |
| 24.01-32.0      | 8         | 1%      |
| 2.01-3.0        | 4         | 0.5%    |
| More than 256.0 | 3         | 0.37%   |
| 0.51-1.0        | 3         | 0.37%   |
| 0.01-0.5        | 2         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 249       | 28.26%  |
| 2.01-3.0    | 199       | 22.59%  |
| 4.01-8.0    | 177       | 20.09%  |
| 3.01-4.0    | 141       | 16%     |
| 8.01-16.0   | 47        | 5.33%   |
| 0.51-1.0    | 41        | 4.65%   |
| 16.01-24.0  | 11        | 1.25%   |
| 0.01-0.5    | 8         | 0.91%   |
| 32.01-64.0  | 4         | 0.45%   |
| 24.01-32.0  | 3         | 0.34%   |
| 64.01-256.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 489       | 60.37%  |
| 2      | 159       | 19.63%  |
| 3      | 67        | 8.27%   |
| 4      | 39        | 4.81%   |
| 6      | 15        | 1.85%   |
| 5      | 15        | 1.85%   |
| 0      | 11        | 1.36%   |
| 7      | 6         | 0.74%   |
| 11     | 3         | 0.37%   |
| 9      | 3         | 0.37%   |
| 8      | 3         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 584       | 73%     |
| Yes       | 216       | 27%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 679       | 85.19%  |
| No        | 118       | 14.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 626       | 78.64%  |
| No        | 170       | 21.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 508       | 63.03%  |
| No        | 298       | 36.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Norway  | 795       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Oslo                 | 228       | 27.44%  |
| Trondheim            | 55        | 6.62%   |
| Bergen               | 33        | 3.97%   |
| Kristiansand         | 26        | 3.13%   |
| Stavanger            | 23        | 2.77%   |
| Tromsø              | 17        | 2.05%   |
| Skien                | 12        | 1.44%   |
| Sandefjord           | 11        | 1.32%   |
| Drammen              | 11        | 1.32%   |
| Ålesund             | 11        | 1.32%   |
| Røyken Municipality | 8         | 0.96%   |
| Nesttun              | 8         | 0.96%   |
| Fornebu              | 8         | 0.96%   |
| Sandnes              | 7         | 0.84%   |
| Fredrikstad          | 7         | 0.84%   |
| Sarpsborg            | 6         | 0.72%   |
| Lillehammer          | 6         | 0.72%   |
| Kongsberg            | 6         | 0.72%   |
| Honefoss             | 6         | 0.72%   |
| Bodø                | 6         | 0.72%   |
| Moss                 | 5         | 0.6%    |
| Haugesund            | 5         | 0.6%    |
| Harstad              | 5         | 0.6%    |
| Drobak               | 5         | 0.6%    |
| Asker                | 5         | 0.6%    |
| Arendal              | 5         | 0.6%    |
| Tønsberg            | 4         | 0.48%   |
| Stjordal             | 4         | 0.48%   |
| Larvik               | 4         | 0.48%   |
| Heimdal              | 4         | 0.48%   |
| Fetsund              | 4         | 0.48%   |
| Vollen               | 3         | 0.36%   |
| Vennesla             | 3         | 0.36%   |
| Vear                 | 3         | 0.36%   |
| Saetre               | 3         | 0.36%   |
| Notteroy             | 3         | 0.36%   |
| Mo i Rana            | 3         | 0.36%   |
| Mjondalen            | 3         | 0.36%   |
| Lunner               | 3         | 0.36%   |
| Lorenskog            | 3         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 285       | 420    | 24.46%  |
| Seagate                        | 149       | 266    | 12.79%  |
| WDC                            | 130       | 259    | 11.16%  |
| Kingston                       | 75        | 107    | 6.44%   |
| Toshiba                        | 71        | 85     | 6.09%   |
| SanDisk                        | 57        | 72     | 4.89%   |
| Intel                          | 47        | 57     | 4.03%   |
| Crucial                        | 44        | 64     | 3.78%   |
| SK hynix                       | 39        | 41     | 3.35%   |
| Unknown                        | 36        | 45     | 3.09%   |
| Hitachi                        | 29        | 41     | 2.49%   |
| Micron Technology              | 24        | 34     | 2.06%   |
| HGST                           | 22        | 29     | 1.89%   |
| Corsair                        | 19        | 27     | 1.63%   |
| Phison                         | 17        | 22     | 1.46%   |
| Apple                          | 16        | 18     | 1.37%   |
| OCZ                            | 13        | 14     | 1.12%   |
| LITEON                         | 12        | 16     | 1.03%   |
| PNY                            | 8         | 11     | 0.69%   |
| LITEONIT                       | 8         | 8      | 0.69%   |
| A-DATA Technology              | 8         | 10     | 0.69%   |
| KIOXIA                         | 5         | 12     | 0.43%   |
| Lenovo                         | 4         | 4      | 0.34%   |
| Intenso                        | 4         | 4      | 0.34%   |
| Fujitsu                        | 4         | 4      | 0.34%   |
| Unknown                        | 3         | 4      | 0.26%   |
| XPG                            | 2         | 2      | 0.17%   |
| Transcend                      | 2         | 2      | 0.17%   |
| Silicon Motion                 | 2         | 3      | 0.17%   |
| Lexar                          | 2         | 2      | 0.17%   |
| GOODRAM                        | 2         | 2      | 0.17%   |
| China                          | 2         | 2      | 0.17%   |
| ASMT                           | 2         | 2      | 0.17%   |
| Ugreen                         | 1         | 1      | 0.09%   |
| Teclast                        | 1         | 1      | 0.09%   |
| Team                           | 1         | 1      | 0.09%   |
| STEC                           | 1         | 1      | 0.09%   |
| SPCC                           | 1         | 1      | 0.09%   |
| Solid State Storage Technology | 1         | 1      | 0.09%   |
| SandForce                      | 1         | 2      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 256GB         | 22        | 1.66%   |
| Samsung SSD 850 EVO 250GB            | 14        | 1.06%   |
| Kingston SV300S37A120G 120GB SSD     | 13        | 0.98%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 12        | 0.91%   |
| Samsung SSD 860 EVO 1TB              | 11        | 0.83%   |
| Samsung SSD 840 EVO 250GB            | 11        | 0.83%   |
| Samsung NVMe SSD Drive 500GB         | 11        | 0.83%   |
| Samsung SSD 850 EVO 500GB            | 10        | 0.75%   |
| Toshiba NVMe SSD Drive 256GB         | 9         | 0.68%   |
| Samsung NVMe SSD Drive 512GB         | 9         | 0.68%   |
| Samsung NVMe SSD Drive 1TB           | 9         | 0.68%   |
| Seagate ST4000DM004-2CV104 4TB       | 8         | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB         | 8         | 0.6%    |
| Samsung SSD 860 EVO 500GB            | 8         | 0.6%    |
| WDC WD30EFRX-68EUZN0 3TB             | 7         | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB       | 7         | 0.53%   |
| Samsung SSD 840 EVO 120GB            | 7         | 0.53%   |
| Kingston NVMe SSD Drive 1TB          | 7         | 0.53%   |
| HGST HTS721010A9E630 1TB             | 7         | 0.53%   |
| Seagate ST1000DM003-1CH162 1TB       | 6         | 0.45%   |
| Seagate Expansion 1TB                | 6         | 0.45%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD | 6         | 0.45%   |
| Kingston SV300S37A240G 240GB SSD     | 6         | 0.45%   |
| Unknown MMC Card  64GB               | 5         | 0.38%   |
| Unknown MMC Card  16GB               | 5         | 0.38%   |
| Toshiba NVMe SSD Drive 512GB         | 5         | 0.38%   |
| Toshiba MG04ACA100NY 1TB             | 5         | 0.38%   |
| Seagate ST4000VN008-2DR166 4TB       | 5         | 0.38%   |
| Seagate ST1000DM010-2EP102 1TB       | 5         | 0.38%   |
| Seagate Backup+ Hub BK 8TB           | 5         | 0.38%   |
| SanDisk NVMe SSD Drive 512GB         | 5         | 0.38%   |
| SanDisk NVMe SSD Drive 500GB         | 5         | 0.38%   |
| SanDisk NVMe SSD Drive 256GB         | 5         | 0.38%   |
| SanDisk NVMe SSD Drive 1TB           | 5         | 0.38%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.38%   |
| Samsung NVMe SSD Drive 1024GB        | 5         | 0.38%   |
| Phison NVMe SSD Drive 1TB            | 5         | 0.38%   |
| Kingston SUV400S37240G 240GB SSD     | 5         | 0.38%   |
| Kingston SA400S37120G 120GB SSD      | 5         | 0.38%   |
| Intel SSDPEKNW010T8 1TB              | 5         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 261    | 40.06%  |
| WDC                 | 92        | 196    | 25.41%  |
| Toshiba             | 36        | 45     | 9.94%   |
| Hitachi             | 29        | 41     | 8.01%   |
| Samsung Electronics | 23        | 37     | 6.35%   |
| HGST                | 22        | 29     | 6.08%   |
| Fujitsu             | 4         | 4      | 1.1%    |
| Apple               | 4         | 4      | 1.1%    |
| Intenso             | 2         | 2      | 0.55%   |
| Unknown             | 1         | 1      | 0.28%   |
| LaCie               | 1         | 1      | 0.28%   |
| IET                 | 1         | 2      | 0.28%   |
| ASMT                | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 156       | 212    | 34.67%  |
| Kingston            | 54        | 68     | 12%     |
| Crucial             | 41        | 61     | 9.11%   |
| SanDisk             | 31        | 35     | 6.89%   |
| Intel               | 28        | 37     | 6.22%   |
| WDC                 | 19        | 34     | 4.22%   |
| Micron Technology   | 14        | 20     | 3.11%   |
| OCZ                 | 13        | 14     | 2.89%   |
| Corsair             | 13        | 17     | 2.89%   |
| SK hynix            | 12        | 13     | 2.67%   |
| LITEON              | 10        | 14     | 2.22%   |
| Apple               | 10        | 12     | 2.22%   |
| Toshiba             | 8         | 8      | 1.78%   |
| PNY                 | 8         | 11     | 1.78%   |
| LITEONIT            | 8         | 8      | 1.78%   |
| A-DATA Technology   | 6         | 8      | 1.33%   |
| Transcend           | 2         | 2      | 0.44%   |
| GOODRAM             | 2         | 2      | 0.44%   |
| China               | 2         | 2      | 0.44%   |
| Teclast             | 1         | 1      | 0.22%   |
| Team                | 1         | 1      | 0.22%   |
| SPCC                | 1         | 1      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| SandForce           | 1         | 2      | 0.22%   |
| Radeon              | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| LDLC                | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 2      | 0.22%   |
| Intenso             | 1         | 1      | 0.22%   |
| BIWIN               | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| Unknown             | 1         | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 388       | 594    | 36.88%  |
| NVMe    | 310       | 436    | 29.47%  |
| HDD     | 304       | 625    | 28.9%   |
| MMC     | 35        | 44     | 3.33%   |
| Unknown | 15        | 14     | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 543       | 1168   | 58.14%  |
| NVMe | 310       | 436    | 33.19%  |
| SAS  | 46        | 65     | 4.93%   |
| MMC  | 35        | 44     | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 439       | 685    | 58.53%  |
| 0.51-1.0   | 175       | 254    | 23.33%  |
| 1.01-2.0   | 52        | 88     | 6.93%   |
| 3.01-4.0   | 31        | 63     | 4.13%   |
| 2.01-3.0   | 29        | 60     | 3.87%   |
| 4.01-10.0  | 24        | 69     | 3.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 257       | 30.93%  |
| 251-500        | 172       | 20.7%   |
| 501-1000       | 110       | 13.24%  |
| 1001-2000      | 67        | 8.06%   |
| More than 3000 | 63        | 7.58%   |
| 1-20           | 54        | 6.5%    |
| 51-100         | 34        | 4.09%   |
| 2001-3000      | 30        | 3.61%   |
| Unknown        | 24        | 2.89%   |
| 21-50          | 20        | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 311       | 35.91%  |
| 21-50          | 117       | 13.51%  |
| 101-250        | 112       | 12.93%  |
| 51-100         | 103       | 11.89%  |
| 251-500        | 72        | 8.31%   |
| 501-1000       | 48        | 5.54%   |
| 1001-2000      | 43        | 4.97%   |
| More than 3000 | 27        | 3.12%   |
| Unknown        | 24        | 2.77%   |
| 2001-3000      | 8         | 0.92%   |
| 0              | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB                | 2         | 5      | 3.08%   |
| WDC WD30EFRX-68EUZN0 3TB                    | 2         | 2      | 3.08%   |
| Seagate ST31000524AS 1TB                    | 2         | 2      | 3.08%   |
| WDC WD800JB-00CRA1 80GB                     | 1         | 1      | 1.54%   |
| WDC WD800BB-00CAA1 80GB                     | 1         | 1      | 1.54%   |
| WDC WD7500BPVX-22JC3T0 752GB                | 1         | 1      | 1.54%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.54%   |
| WDC WD5000AAJS-00YFA0 500GB                 | 1         | 1      | 1.54%   |
| WDC WD40EFRX-68WT0N0 4TB                    | 1         | 4      | 1.54%   |
| WDC WD3200AAKS-00V1A0 320GB                 | 1         | 1      | 1.54%   |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 1.54%   |
| WDC WD10EALX-009BA0 1TB                     | 1         | 1      | 1.54%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.54%   |
| Toshiba MK5055GSX 500GB                     | 1         | 2      | 1.54%   |
| Toshiba HDWD110 1TB                         | 1         | 1      | 1.54%   |
| SK hynix SH920 2.5 7MM 128GB SSD            | 1         | 1      | 1.54%   |
| SK hynix SC210 2.5 7MM 256GB SSD            | 1         | 1      | 1.54%   |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.54%   |
| Seagate ST9750420AS 752GB                   | 1         | 1      | 1.54%   |
| Seagate ST9250827AS 250GB                   | 1         | 1      | 1.54%   |
| Seagate ST9250315AS 250GB                   | 1         | 1      | 1.54%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 1.54%   |
| Seagate ST500LM000-SSHD-8GB                 | 1         | 1      | 1.54%   |
| Seagate ST4000VN008-2DR166 4TB              | 1         | 1      | 1.54%   |
| Seagate ST4000LM024-2AN17V 4TB              | 1         | 1      | 1.54%   |
| Seagate ST3500418AS 500GB                   | 1         | 1      | 1.54%   |
| Seagate ST31000528AS 1TB                    | 1         | 1      | 1.54%   |
| Seagate ST3000DM008-2DM166 3TB              | 1         | 1      | 1.54%   |
| Seagate ST3000DM001-1CH166 3TB              | 1         | 9      | 1.54%   |
| Seagate ST2000DM001-1E6164 2TB              | 1         | 1      | 1.54%   |
| Seagate ST1000LM014-SSHD-8GB                | 1         | 1      | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB              | 1         | 1      | 1.54%   |
| Seagate ST1000DM003-1CH162 1TB              | 1         | 1      | 1.54%   |
| SanDisk SSD PLUS 1000GB                     | 1         | 1      | 1.54%   |
| SanDisk SD8TN8U-256G-1006 256GB SSD         | 1         | 1      | 1.54%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB | 1         | 1      | 1.54%   |
| Samsung Electronics SSD 970 EVO 500GB       | 1         | 1      | 1.54%   |
| Samsung Electronics SSD 840 EVO 250GB       | 1         | 1      | 1.54%   |
| Samsung Electronics SP1614C 160GB           | 1         | 1      | 1.54%   |
| OCZ VERTEX3 240GB SSD                       | 1         | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 25     | 25.4%   |
| WDC                 | 13        | 20     | 20.63%  |
| Intel               | 5         | 6      | 7.94%   |
| Samsung Electronics | 4         | 4      | 6.35%   |
| Hitachi             | 4         | 4      | 6.35%   |
| SK hynix            | 3         | 3      | 4.76%   |
| Micron Technology   | 3         | 6      | 4.76%   |
| Toshiba             | 2         | 3      | 3.17%   |
| SanDisk             | 2         | 2      | 3.17%   |
| LITEON              | 2         | 2      | 3.17%   |
| HGST                | 2         | 3      | 3.17%   |
| Crucial             | 2         | 2      | 3.17%   |
| Corsair             | 2         | 2      | 3.17%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Lenovo              | 1         | 1      | 1.59%   |
| Kingston            | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 25     | 42.11%  |
| WDC                 | 13        | 20     | 34.21%  |
| Hitachi             | 4         | 4      | 10.53%  |
| Toshiba             | 2         | 3      | 5.26%   |
| HGST                | 2         | 3      | 5.26%   |
| Samsung Electronics | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 56     | 59.02%  |
| SSD  | 20        | 24     | 32.79%  |
| NVMe | 5         | 5      | 8.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB    | 3         | 3      | 75%     |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Apple    | 3         | 3      | 75%     |
| Kingston | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 482       | 1018   | 55.98%  |
| Works    | 315       | 606    | 36.59%  |
| Malfunc  | 60        | 85     | 6.97%   |
| Failed   | 4         | 4      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 516       | 49.19%  |
| AMD                              | 145       | 13.82%  |
| Samsung Electronics              | 140       | 13.35%  |
| SanDisk                          | 50        | 4.77%   |
| Toshiba America Info Systems     | 28        | 2.67%   |
| SK hynix                         | 27        | 2.57%   |
| Kingston Technology Company      | 23        | 2.19%   |
| Phison Electronics               | 22        | 2.1%    |
| ASMedia Technology               | 22        | 2.1%    |
| Nvidia                           | 11        | 1.05%   |
| LSI Logic / Symbios Logic        | 11        | 1.05%   |
| Micron Technology                | 10        | 0.95%   |
| Broadcom / LSI                   | 8         | 0.76%   |
| Marvell Technology Group         | 5         | 0.48%   |
| JMicron Technology               | 5         | 0.48%   |
| Lenovo                           | 4         | 0.38%   |
| ADATA Technology                 | 4         | 0.38%   |
| Micron/Crucial Technology        | 3         | 0.29%   |
| Lite-On Technology               | 3         | 0.29%   |
| KIOXIA                           | 3         | 0.29%   |
| Silicon Motion                   | 2         | 0.19%   |
| Solid State Storage Technology   | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Silicon Image                    | 1         | 0.1%    |
| Seagate Technology               | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |
| 3ware                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 93        | 7.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 73        | 6.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 47        | 4.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 44        | 3.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 36        | 3.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 31        | 2.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 29        | 2.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 2.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 27        | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 27        | 2.31%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 21        | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 20        | 1.71%   |
| Intel SATA Controller [RAID mode]                                                | 19        | 1.62%   |
| AMD 400 Series Chipset SATA Controller                                           | 19        | 1.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 18        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 18        | 1.54%   |
| AMD 500 Series Chipset SATA Controller                                           | 18        | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 1.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 16        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 16        | 1.37%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 14        | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 13        | 1.11%   |
| Kingston Company A2000 NVMe SSD                                                  | 13        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 12        | 1.02%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 11        | 0.94%   |
| Intel SSD 660P Series                                                            | 11        | 0.94%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 11        | 0.94%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 11        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 11        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 11        | 0.94%   |
| Micron Non-Volatile memory controller                                            | 10        | 0.85%   |
| Samsung NVMe SSD Controller 980                                                  | 9         | 0.77%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 9         | 0.77%   |
| Phison E12 NVMe Controller                                                       | 9         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 0.77%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 8         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 580       | 55.88%  |
| NVMe | 310       | 29.87%  |
| RAID | 79        | 7.61%   |
| IDE  | 62        | 5.97%   |
| SAS  | 4         | 0.39%   |
| SCSI | 3         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 611       | 76.86%  |
| AMD      | 175       | 22.01%  |
| ARM      | 8         | 1.01%   |
| QUALCOMM | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 2.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 16        | 2.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 1.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 10        | 1.26%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 10        | 1.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 9         | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 1.13%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 1.13%   |
| AMD Ryzen 7 2700X Eight-Core Processor  | 8         | 1.01%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 7         | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 7         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 7         | 0.88%   |
| ARM Processor                           | 7         | 0.88%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 7         | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 7         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 0.75%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 6         | 0.75%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 6         | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 0.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 6         | 0.75%   |
| AMD Ryzen 5 3600 6-Core Processor       | 6         | 0.75%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz     | 5         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 5         | 0.63%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 5         | 0.63%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 5         | 0.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 5         | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.63%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 5         | 0.63%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 5         | 0.63%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 5         | 0.63%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 4         | 0.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz       | 4         | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 0.5%    |
| Intel Core i7-5820K CPU @ 3.30GHz       | 4         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 225       | 28.27%  |
| Intel Core i5           | 198       | 24.87%  |
| AMD Ryzen 7             | 45        | 5.65%   |
| Other                   | 40        | 5.03%   |
| Intel Core i3           | 38        | 4.77%   |
| AMD Ryzen 5             | 35        | 4.4%    |
| Intel Xeon              | 22        | 2.76%   |
| AMD Ryzen 9             | 21        | 2.64%   |
| Intel Celeron           | 20        | 2.51%   |
| Intel Core i9           | 16        | 2.01%   |
| Intel Core 2 Duo        | 16        | 2.01%   |
| Intel Pentium           | 11        | 1.38%   |
| AMD FX                  | 11        | 1.38%   |
| Intel Atom              | 10        | 1.26%   |
| AMD Athlon 64 X2        | 7         | 0.88%   |
| Intel Core 2            | 6         | 0.75%   |
| Intel Pentium Dual-Core | 5         | 0.63%   |
| AMD Ryzen 7 PRO         | 5         | 0.63%   |
| AMD A8                  | 5         | 0.63%   |
| AMD A10                 | 5         | 0.63%   |
| Intel Genuine           | 4         | 0.5%    |
| AMD A6                  | 4         | 0.5%    |
| AMD Ryzen 3             | 3         | 0.38%   |
| AMD Phenom II X4        | 3         | 0.38%   |
| AMD Athlon              | 3         | 0.38%   |
| Intel Xeon Silver       | 2         | 0.25%   |
| Intel Pentium Silver    | 2         | 0.25%   |
| AMD Turion 64 X2 Mobile | 2         | 0.25%   |
| AMD Ryzen Threadripper  | 2         | 0.25%   |
| AMD Phenom II           | 2         | 0.25%   |
| AMD E2                  | 2         | 0.25%   |
| AMD E                   | 2         | 0.25%   |
| AMD Dual Core Opteron   | 2         | 0.25%   |
| AMD Athlon II X4        | 2         | 0.25%   |
| AMD A4                  | 2         | 0.25%   |
| Intel Pentium III       | 1         | 0.13%   |
| Intel Pentium Gold      | 1         | 0.13%   |
| Intel Pentium Dual      | 1         | 0.13%   |
| Intel Core m7           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 287       | 36.06%  |
| 2      | 282       | 35.43%  |
| 6      | 96        | 12.06%  |
| 8      | 68        | 8.54%   |
| 12     | 19        | 2.39%   |
| 1      | 13        | 1.63%   |
| 16     | 8         | 1.01%   |
| 3      | 7         | 0.88%   |
| 10     | 6         | 0.75%   |
| 20     | 3         | 0.38%   |
| 28     | 2         | 0.25%   |
| 14     | 2         | 0.25%   |
| 40     | 1         | 0.13%   |
| 32     | 1         | 0.13%   |
| 24     | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 782       | 98.36%  |
| 2      | 12        | 1.51%   |
| 4      | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 595       | 74.75%  |
| 1      | 200       | 25.13%  |
| 8      | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 770       | 96.73%  |
| Unknown        | 18        | 2.26%   |
| 32-bit         | 6         | 0.75%   |
| 64-bit         | 2         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 215       | 26.35%  |
| 0x306a9    | 43        | 5.27%   |
| 0x206a7    | 37        | 4.53%   |
| 0x306c3    | 36        | 4.41%   |
| 0x906ea    | 32        | 3.92%   |
| 0x506e3    | 28        | 3.43%   |
| 0x806ea    | 24        | 2.94%   |
| 0x406e3    | 24        | 2.94%   |
| 0x40651    | 23        | 2.82%   |
| 0x906e9    | 20        | 2.45%   |
| 0x806ec    | 19        | 2.33%   |
| 0x806e9    | 19        | 2.33%   |
| 0x306d4    | 15        | 1.84%   |
| 0x1067a    | 15        | 1.84%   |
| 0x08701021 | 15        | 1.84%   |
| 0x20655    | 12        | 1.47%   |
| 0xa0652    | 11        | 1.35%   |
| 0x806c1    | 9         | 1.1%    |
| 0x806eb    | 8         | 0.98%   |
| 0x08701013 | 8         | 0.98%   |
| 0x906ed    | 7         | 0.86%   |
| 0x306f2    | 7         | 0.86%   |
| 0x806d1    | 6         | 0.74%   |
| 0x20652    | 6         | 0.74%   |
| 0x06001119 | 6         | 0.74%   |
| 0x06000852 | 6         | 0.74%   |
| 0x010000c8 | 6         | 0.74%   |
| 0x0a201016 | 5         | 0.61%   |
| 0x0a201009 | 5         | 0.61%   |
| 0x08600106 | 5         | 0.61%   |
| 0x08600104 | 5         | 0.61%   |
| 0x08600103 | 5         | 0.61%   |
| 0x6f6      | 4         | 0.49%   |
| 0x506c9    | 4         | 0.49%   |
| 0x406f1    | 4         | 0.49%   |
| 0x206d7    | 4         | 0.49%   |
| 0x106e5    | 4         | 0.49%   |
| 0x106ca    | 4         | 0.49%   |
| 0x0a50000c | 4         | 0.49%   |
| 0x08108109 | 4         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 167       | 20.93%  |
| Haswell          | 88        | 11.03%  |
| Skylake          | 75        | 9.4%    |
| IvyBridge        | 55        | 6.89%   |
| Zen 2            | 50        | 6.27%   |
| SandyBridge      | 49        | 6.14%   |
| Broadwell        | 29        | 3.63%   |
| Zen 3            | 27        | 3.38%   |
| Zen+             | 22        | 2.76%   |
| Westmere         | 22        | 2.76%   |
| Penryn           | 22        | 2.76%   |
| CometLake        | 20        | 2.51%   |
| Unknown          | 18        | 2.26%   |
| TigerLake        | 17        | 2.13%   |
| Piledriver       | 16        | 2.01%   |
| Zen              | 13        | 1.63%   |
| K8 Hammer        | 13        | 1.63%   |
| Silvermont       | 11        | 1.38%   |
| K10              | 11        | 1.38%   |
| Core             | 11        | 1.38%   |
| Icelake          | 9         | 1.13%   |
| Goldmont plus    | 7         | 0.88%   |
| Bonnell          | 7         | 0.88%   |
| Nehalem          | 6         | 0.75%   |
| Alderlake Hybrid | 5         | 0.63%   |
| P6               | 4         | 0.5%    |
| Goldmont         | 4         | 0.5%    |
| Excavator        | 4         | 0.5%    |
| Bulldozer        | 4         | 0.5%    |
| Bobcat           | 4         | 0.5%    |
| Steamroller      | 3         | 0.38%   |
| K10 Llano        | 2         | 0.25%   |
| Jaguar           | 2         | 0.25%   |
| Puma             | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 459       | 48.88%  |
| Nvidia                     | 283       | 30.14%  |
| AMD                        | 183       | 19.49%  |
| Matrox Electronics Systems | 13        | 1.38%   |
| ASPEED Technology          | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 3.87%   |
| Intel UHD Graphics 620                                                                   | 32        | 3.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 3.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 27        | 2.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 2.82%   |
| Intel HD Graphics 620                                                                    | 23        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 2.41%   |
| AMD Renoir                                                                               | 22        | 2.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 21        | 2.2%    |
| Intel HD Graphics 530                                                                    | 21        | 2.2%    |
| Intel HD Graphics 5500                                                                   | 18        | 1.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 1.78%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 1.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 14        | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.46%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 11        | 1.15%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 11        | 1.15%   |
| Intel HD Graphics 630                                                                    | 10        | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.94%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 9         | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.84%   |
| Matrox Electronics Systems G200eR2                                                       | 8         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.73%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.63%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 6         | 0.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 6         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.63%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 6         | 0.63%   |
| AMD Cezanne                                                                              | 6         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.52%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 5         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 320       | 40%     |
| 1 x Nvidia      | 155       | 19.38%  |
| 1 x AMD         | 149       | 18.63%  |
| Intel + Nvidia  | 115       | 14.38%  |
| Intel + AMD     | 17        | 2.13%   |
| 1 x Matrox      | 13        | 1.63%   |
| Other           | 10        | 1.25%   |
| 2 x AMD         | 9         | 1.13%   |
| AMD + Nvidia    | 8         | 1%      |
| 2 x Nvidia      | 3         | 0.38%   |
| Nvidia + ASPEED | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 599       | 74.04%  |
| Proprietary | 177       | 21.88%  |
| Unknown     | 33        | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 457       | 56.42%  |
| 1.01-2.0   | 89        | 10.99%  |
| 0.01-0.5   | 68        | 8.4%    |
| 7.01-8.0   | 57        | 7.04%   |
| 3.01-4.0   | 54        | 6.67%   |
| 0.51-1.0   | 32        | 3.95%   |
| 5.01-6.0   | 23        | 2.84%   |
| 8.01-16.0  | 13        | 1.6%    |
| 2.01-3.0   | 12        | 1.48%   |
| 16.01-24.0 | 3         | 0.37%   |
| 4.01-5.0   | 2         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 128       | 14.07%  |
| LG Display              | 94        | 10.33%  |
| AU Optronics            | 93        | 10.22%  |
| Dell                    | 64        | 7.03%   |
| Chimei Innolux          | 63        | 6.92%   |
| BOE                     | 54        | 5.93%   |
| AOC                     | 39        | 4.29%   |
| BenQ                    | 38        | 4.18%   |
| Acer                    | 35        | 3.85%   |
| Hewlett-Packard         | 31        | 3.41%   |
| Lenovo                  | 29        | 3.19%   |
| Philips                 | 28        | 3.08%   |
| Ancor Communications    | 28        | 3.08%   |
| Sharp                   | 27        | 2.97%   |
| Apple                   | 19        | 2.09%   |
| InfoVision              | 13        | 1.43%   |
| Goldstar                | 13        | 1.43%   |
| ASUSTek Computer        | 11        | 1.21%   |
| Chi Mei Optoelectronics | 8         | 0.88%   |
| JDI                     | 7         | 0.77%   |
| PANDA                   | 6         | 0.66%   |
| Sony                    | 5         | 0.55%   |
| Grundig                 | 5         | 0.55%   |
| CSO                     | 5         | 0.55%   |
| NEC Computers           | 4         | 0.44%   |
| VOXICON                 | 3         | 0.33%   |
| LG Electronics          | 3         | 0.33%   |
| Iiyama                  | 3         | 0.33%   |
| HVR                     | 3         | 0.33%   |
| Eizo                    | 3         | 0.33%   |
| AUS                     | 3         | 0.33%   |
| Vestel Elektronik       | 2         | 0.22%   |
| Unknown                 | 2         | 0.22%   |
| Toshiba                 | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| MSI                     | 2         | 0.22%   |
| MiTAC                   | 2         | 0.22%   |
| HannStar                | 2         | 0.22%   |
| Gigabyte Technology     | 2         | 0.22%   |
| Denver                  | 2         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 7         | 0.74%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                | 6         | 0.63%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch   | 5         | 0.53%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 5         | 0.53%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch           | 5         | 0.53%   |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                    | 5         | 0.53%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                   | 5         | 0.53%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 5         | 0.53%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                   | 5         | 0.53%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 5         | 0.53%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                   | 5         | 0.53%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch | 4         | 0.42%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 4         | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 4         | 0.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.42%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch       | 4         | 0.42%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch         | 4         | 0.42%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                      | 4         | 0.42%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                     | 4         | 0.42%   |
| Sony TV SNYEE01 1920x1080                                            | 3         | 0.32%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 3         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch | 3         | 0.32%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch | 3         | 0.32%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 3         | 0.32%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 3         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 3         | 0.32%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch          | 3         | 0.32%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch          | 3         | 0.32%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 3         | 0.32%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch              | 3         | 0.32%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch         | 3         | 0.32%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                       | 3         | 0.32%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                    | 3         | 0.32%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                    | 3         | 0.32%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D8 1920x1080 344x193mm 15.5-inch     | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 3         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 397       | 45.48%  |
| 1366x768 (WXGA)    | 94        | 10.77%  |
| 3840x2160 (4K)     | 88        | 10.08%  |
| 2560x1440 (QHD)    | 61        | 6.99%   |
| 1920x1200 (WUXGA)  | 37        | 4.24%   |
| 1600x900 (HD+)     | 30        | 3.44%   |
| 3440x1440          | 21        | 2.41%   |
| Unknown            | 15        | 1.72%   |
| 1280x800 (WXGA)    | 13        | 1.49%   |
| 3840x1080          | 12        | 1.37%   |
| 1280x1024 (SXGA)   | 12        | 1.37%   |
| 1680x1050 (WSXGA+) | 9         | 1.03%   |
| 3000x2000          | 7         | 0.8%    |
| 2560x1600          | 7         | 0.8%    |
| 1440x900 (WXGA+)   | 7         | 0.8%    |
| 3840x2400          | 6         | 0.69%   |
| 2880x1800          | 6         | 0.69%   |
| 2160x1440          | 6         | 0.69%   |
| 3840x1600          | 5         | 0.57%   |
| 2560x1080          | 4         | 0.46%   |
| 1360x768           | 4         | 0.46%   |
| 1024x600           | 4         | 0.46%   |
| 2160x1200          | 3         | 0.34%   |
| 1600x1200          | 3         | 0.34%   |
| 5120x1440          | 2         | 0.23%   |
| 4480x1440          | 2         | 0.23%   |
| 1920x540           | 2         | 0.23%   |
| 1280x720 (HD)      | 2         | 0.23%   |
| 9600x2160          | 1         | 0.11%   |
| 7680x1440          | 1         | 0.11%   |
| 7680x1080          | 1         | 0.11%   |
| 6880x1440          | 1         | 0.11%   |
| 5760x2160          | 1         | 0.11%   |
| 5520x1080          | 1         | 0.11%   |
| 5360x1440          | 1         | 0.11%   |
| 3840x1200          | 1         | 0.11%   |
| 3840x1100          | 1         | 0.11%   |
| 3840x1024          | 1         | 0.11%   |
| 2736x1824          | 1         | 0.11%   |
| 2646x1024          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 179       | 19.87%  |
| 24      | 107       | 11.88%  |
| 27      | 105       | 11.65%  |
| 13      | 100       | 11.1%   |
| 14      | 88        | 9.77%   |
| Unknown | 56        | 6.22%   |
| 23      | 37        | 4.11%   |
| 17      | 34        | 3.77%   |
| 12      | 34        | 3.77%   |
| 31      | 23        | 2.55%   |
| 34      | 19        | 2.11%   |
| 21      | 12        | 1.33%   |
| 84      | 11        | 1.22%   |
| 48      | 10        | 1.11%   |
| 19      | 9         | 1%      |
| 22      | 8         | 0.89%   |
| 54      | 7         | 0.78%   |
| 25      | 7         | 0.78%   |
| 72      | 5         | 0.55%   |
| 37      | 5         | 0.55%   |
| 32      | 5         | 0.55%   |
| 20      | 4         | 0.44%   |
| 43      | 3         | 0.33%   |
| 40      | 3         | 0.33%   |
| 35      | 3         | 0.33%   |
| 26      | 3         | 0.33%   |
| 11      | 3         | 0.33%   |
| 10      | 3         | 0.33%   |
| 55      | 2         | 0.22%   |
| 39      | 2         | 0.22%   |
| 33      | 2         | 0.22%   |
| 18      | 2         | 0.22%   |
| 65      | 1         | 0.11%   |
| 60      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 44      | 1         | 0.11%   |
| 42      | 1         | 0.11%   |
| 36      | 1         | 0.11%   |
| 30      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 307       | 35.13%  |
| 501-600     | 222       | 25.4%   |
| 201-300     | 96        | 10.98%  |
| Unknown     | 56        | 6.41%   |
| 351-400     | 49        | 5.61%   |
| 601-700     | 38        | 4.35%   |
| 701-800     | 26        | 2.97%   |
| 401-500     | 24        | 2.75%   |
| 1001-1500   | 22        | 2.52%   |
| 1501-2000   | 15        | 1.72%   |
| 801-900     | 14        | 1.6%    |
| 901-1000    | 4         | 0.46%   |
| 101-200     | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 593       | 74.31%  |
| 16/10   | 87        | 10.9%   |
| Unknown | 45        | 5.64%   |
| 21/9    | 28        | 3.51%   |
| 3/2     | 19        | 2.38%   |
| 5/4     | 12        | 1.5%    |
| 32/9    | 9         | 1.13%   |
| 4/3     | 2         | 0.25%   |
| 6/5     | 1         | 0.13%   |
| 3.76    | 1         | 0.13%   |
| 3.40    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 176       | 19.82%  |
| 81-90          | 143       | 16.1%   |
| 201-250        | 120       | 13.51%  |
| 301-350        | 106       | 11.94%  |
| Unknown        | 56        | 6.31%   |
| 351-500        | 53        | 5.97%   |
| 71-80          | 46        | 5.18%   |
| 251-300        | 42        | 4.73%   |
| 61-70          | 32        | 3.6%    |
| 121-130        | 30        | 3.38%   |
| More than 1000 | 27        | 3.04%   |
| 501-1000       | 23        | 2.59%   |
| 151-200        | 16        | 1.8%    |
| 51-60          | 4         | 0.45%   |
| 41-50          | 3         | 0.34%   |
| 141-150        | 3         | 0.34%   |
| 131-140        | 3         | 0.34%   |
| 111-120        | 3         | 0.34%   |
| 1-40           | 1         | 0.11%   |
| 91-100         | 1         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 274       | 31.53%  |
| 51-100        | 257       | 29.57%  |
| 101-120       | 165       | 18.99%  |
| 161-240       | 60        | 6.9%    |
| Unknown       | 56        | 6.44%   |
| More than 240 | 38        | 4.37%   |
| 1-50          | 19        | 2.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 587       | 72.47%  |
| 2     | 154       | 19.01%  |
| 0     | 39        | 4.81%   |
| 3     | 28        | 3.46%   |
| 4     | 2         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 501       | 42.46%  |
| Realtek Semiconductor                  | 299       | 25.34%  |
| Qualcomm Atheros                       | 97        | 8.22%   |
| Broadcom                               | 73        | 6.19%   |
| Broadcom Limited                       | 20        | 1.69%   |
| Ericsson Business Mobile Networks      | 14        | 1.19%   |
| Sierra Wireless                        | 13        | 1.1%    |
| NetGear                                | 13        | 1.1%    |
| Ralink                                 | 12        | 1.02%   |
| Dell                                   | 11        | 0.93%   |
| ASUSTek Computer                       | 11        | 0.93%   |
| Nvidia                                 | 10        | 0.85%   |
| Ralink Technology                      | 9         | 0.76%   |
| Marvell Technology Group               | 7         | 0.59%   |
| TP-Link                                | 6         | 0.51%   |
| Samsung Electronics                    | 6         | 0.51%   |
| Lenovo                                 | 6         | 0.51%   |
| Hewlett-Packard                        | 6         | 0.51%   |
| Linksys                                | 5         | 0.42%   |
| DisplayLink                            | 5         | 0.42%   |
| Motorola PCS                           | 4         | 0.34%   |
| Microsoft                              | 4         | 0.34%   |
| MediaTek                               | 4         | 0.34%   |
| FIBOCOM                                | 4         | 0.34%   |
| Aquantia                               | 4         | 0.34%   |
| Qualcomm Atheros Communications        | 3         | 0.25%   |
| Qualcomm                               | 3         | 0.25%   |
| Microchip Technology                   | 3         | 0.25%   |
| Huawei Technologies                    | 3         | 0.25%   |
| Chu Yuen Enterprise                    | 3         | 0.25%   |
| ASIX Electronics                       | 3         | 0.25%   |
| Sigma Designs                          | 2         | 0.17%   |
| JMicron Technology                     | 2         | 0.17%   |
| Arduino SA                             | 2         | 0.17%   |
| Winbond Electronics                    | 1         | 0.08%   |
| Wacom                                  | 1         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| SEGGER                                 | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 217       | 14.91%  |
| Intel Wi-Fi 6 AX200                                               | 66        | 4.54%   |
| Intel Wireless 8265 / 8275                                        | 48        | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 2.96%   |
| Intel I211 Gigabit Network Connection                             | 38        | 2.61%   |
| Intel Wireless 7265                                               | 30        | 2.06%   |
| Intel Wireless 8260                                               | 27        | 1.86%   |
| Intel Wireless 7260                                               | 26        | 1.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 17        | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 15        | 1.03%   |
| Intel Wireless-AC 9260                                            | 15        | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 15        | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 0.89%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                    | 12        | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.76%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 10        | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.69%   |
| Sierra Wireless EM7455                                            | 9         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.62%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.55%   |
| Intel WiFi Link 5100                                              | 8         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 384       | 56.64%  |
| Qualcomm Atheros                | 76        | 11.21%  |
| Realtek Semiconductor           | 54        | 7.96%   |
| Broadcom                        | 50        | 7.37%   |
| Broadcom Limited                | 17        | 2.51%   |
| Sierra Wireless                 | 13        | 1.92%   |
| NetGear                         | 13        | 1.92%   |
| Ralink                          | 12        | 1.77%   |
| ASUSTek Computer                | 11        | 1.62%   |
| Ralink Technology               | 9         | 1.33%   |
| TP-Link                         | 6         | 0.88%   |
| Dell                            | 6         | 0.88%   |
| MediaTek                        | 4         | 0.59%   |
| Linksys                         | 4         | 0.59%   |
| FIBOCOM                         | 4         | 0.59%   |
| Qualcomm Atheros Communications | 3         | 0.44%   |
| Qualcomm                        | 3         | 0.44%   |
| Microsoft                       | 3         | 0.44%   |
| Chu Yuen Enterprise             | 3         | 0.44%   |
| Hewlett-Packard                 | 2         | 0.29%   |
| Wacom                           | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 66        | 9.73%   |
| Intel Wireless 8265 / 8275                                     | 48        | 7.08%   |
| Intel Wireless 7265                                            | 30        | 4.42%   |
| Intel Wireless 8260                                            | 27        | 3.98%   |
| Intel Wireless 7260                                            | 26        | 3.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 2.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 17        | 2.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 17        | 2.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 2.21%   |
| Intel Wireless-AC 9260                                         | 15        | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.77%   |
| Intel Centrino Ultimate-N 6300                                 | 12        | 1.77%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 10        | 1.47%   |
| Sierra Wireless EM7455                                         | 9         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 1.33%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 1.18%   |
| Intel WiFi Link 5100                                           | 8         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 8         | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 1.03%   |
| Intel Wireless 3160                                            | 7         | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.03%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7         | 1.03%   |
| Intel Wireless 3165                                            | 6         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 0.88%   |
| Intel Centrino Advanced-N 6235                                 | 6         | 0.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 6         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 5         | 0.74%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.59%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 313       | 43.47%  |
| Realtek Semiconductor         | 274       | 38.06%  |
| Qualcomm Atheros              | 36        | 5%      |
| Broadcom                      | 36        | 5%      |
| Nvidia                        | 10        | 1.39%   |
| Marvell Technology Group      | 7         | 0.97%   |
| Samsung Electronics           | 6         | 0.83%   |
| Lenovo                        | 6         | 0.83%   |
| DisplayLink                   | 5         | 0.69%   |
| Broadcom Limited              | 5         | 0.69%   |
| Aquantia                      | 4         | 0.56%   |
| Huawei Technologies           | 3         | 0.42%   |
| ASIX Electronics              | 3         | 0.42%   |
| JMicron Technology            | 2         | 0.28%   |
| T & A Mobile Phones           | 1         | 0.14%   |
| OnePlus Technology (Shenzhen) | 1         | 0.14%   |
| NetXen Incorporated           | 1         | 0.14%   |
| Microsoft                     | 1         | 0.14%   |
| Linksys                       | 1         | 0.14%   |
| Hewlett-Packard               | 1         | 0.14%   |
| D-Link                        | 1         | 0.14%   |
| Cisco Systems                 | 1         | 0.14%   |
| ATEN International            | 1         | 0.14%   |
| 3Com                          | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 217       | 29.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 43        | 5.81%   |
| Intel I211 Gigabit Network Connection                             | 38        | 5.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 2.97%   |
| Intel Ethernet Connection (2) I219-V                              | 20        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 2.3%    |
| Intel Ethernet Connection I217-LM                                 | 16        | 2.16%   |
| Intel Ethernet Controller I225-V                                  | 15        | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13        | 1.76%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.62%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 1.62%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 1.49%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 1.49%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 1.35%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 1.22%   |
| Intel Ethernet Connection (2) I218-V                              | 8         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 1.08%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.95%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.95%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.68%   |
| Intel I350 Gigabit Network Connection                             | 5         | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 5         | 0.68%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 675       | 50.45%  |
| WiFi     | 626       | 46.79%  |
| Modem    | 30        | 2.24%   |
| Unknown  | 7         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 499       | 61.08%  |
| Ethernet | 317       | 38.8%   |
| Unknown  | 1         | 0.12%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 459       | 57.59%  |
| 1     | 295       | 37.01%  |
| 3     | 21        | 2.63%   |
| 0     | 15        | 1.88%   |
| 4     | 5         | 0.63%   |
| 6     | 2         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 727       | 89.86%  |
| Yes  | 82        | 10.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 294       | 57.42%  |
| Broadcom                        | 44        | 8.59%   |
| Cambridge Silicon Radio         | 23        | 4.49%   |
| Qualcomm Atheros Communications | 20        | 3.91%   |
| Apple                           | 20        | 3.91%   |
| Realtek Semiconductor           | 19        | 3.71%   |
| ASUSTek Computer                | 16        | 3.13%   |
| Lite-On Technology              | 14        | 2.73%   |
| IMC Networks                    | 13        | 2.54%   |
| Foxconn / Hon Hai               | 12        | 2.34%   |
| Hewlett-Packard                 | 11        | 2.15%   |
| Dell                            | 10        | 1.95%   |
| Belkin Components               | 4         | 0.78%   |
| HTC (High Tech Computer)        | 3         | 0.59%   |
| Realtek                         | 2         | 0.39%   |
| MediaTek                        | 2         | 0.39%   |
| Marvell Semiconductor           | 2         | 0.39%   |
| Ralink Technology               | 1         | 0.2%    |
| Ralink                          | 1         | 0.2%    |
| Integrated System Solution      | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 127       | 24.76%  |
| Intel AX200 Bluetooth                                                | 60        | 11.7%   |
| Intel AX201 Bluetooth                                                | 36        | 7.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 30        | 5.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 23        | 4.48%   |
| Realtek Bluetooth Radio                                              | 16        | 3.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 15        | 2.92%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 12        | 2.34%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 1.75%   |
| Apple Bluetooth Host Controller                                      | 9         | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 8         | 1.56%   |
| Intel AX210 Bluetooth                                                | 8         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 8         | 1.56%   |
| Lite-On Bluetooth Device                                             | 7         | 1.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 7         | 1.36%   |
| Qualcomm Atheros  Bluetooth Device                                   | 6         | 1.17%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 6         | 1.17%   |
| IMC Networks Bluetooth Radio                                         | 6         | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 6         | 1.17%   |
| Apple Bluetooth USB Host Controller                                  | 6         | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 5         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 5         | 0.97%   |
| Intel Bluetooth Device                                               | 5         | 0.97%   |
| IMC Networks Bluetooth Device                                        | 4         | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                                     | 4         | 0.78%   |
| Broadcom BCM20702A0                                                  | 4         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 4         | 0.78%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.58%   |
| Dell DW375 Bluetooth Module                                          | 3         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth Device                                 | 3         | 0.58%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3         | 0.58%   |
| Realtek Bluetooth Radio                                              | 2         | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth                                    | 2         | 0.39%   |
| Marvell Bluetooth and Wireless LAN Composite Device                  | 2         | 0.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 2         | 0.39%   |
| Foxconn / Hon Hai Acer Bluetooth module                              | 2         | 0.39%   |
| Broadcom HP Portable SoftSailing                                     | 2         | 0.39%   |
| Broadcom Bluetooth 2.1 Device                                        | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 582       | 48.54%  |
| AMD                                          | 219       | 18.27%  |
| Nvidia                                       | 206       | 17.18%  |
| C-Media Electronics                          | 21        | 1.75%   |
| Logitech                                     | 16        | 1.33%   |
| SteelSeries ApS                              | 15        | 1.25%   |
| Realtek Semiconductor                        | 13        | 1.08%   |
| Kingston Technology                          | 12        | 1%      |
| Lenovo                                       | 9         | 0.75%   |
| GN Netcom                                    | 7         | 0.58%   |
| Blue Microphones                             | 7         | 0.58%   |
| Focusrite-Novation                           | 6         | 0.5%    |
| Creative Labs                                | 6         | 0.5%    |
| Corsair                                      | 6         | 0.5%    |
| Razer USA                                    | 5         | 0.42%   |
| Texas Instruments                            | 4         | 0.33%   |
| SAVITECH                                     | 4         | 0.33%   |
| ASUSTek Computer                             | 4         | 0.33%   |
| Sony                                         | 3         | 0.25%   |
| FiiO Electronics Technology                  | 3         | 0.25%   |
| Creative Technology                          | 3         | 0.25%   |
| Yamaha                                       | 2         | 0.17%   |
| XMOS                                         | 2         | 0.17%   |
| Roland                                       | 2         | 0.17%   |
| RODE Microphones                             | 2         | 0.17%   |
| ROCCAT                                       | 2         | 0.17%   |
| M-Audio                                      | 2         | 0.17%   |
| JMTek                                        | 2         | 0.17%   |
| GYROCOM C&C                                  | 2         | 0.17%   |
| Asahi Kasei Microsystems                     | 2         | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.08%   |
| ZOOM                                         | 1         | 0.08%   |
| www.hirestech.com 2010 REV 1.4               | 1         | 0.08%   |
| Sonicstar                                    | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.08%   |
| Shenzhen Riitek Technology                   | 1         | 0.08%   |
| Schiit Audio                                 | 1         | 0.08%   |
| Samson Technologies                          | 1         | 0.08%   |
| PS Audio                                     | 1         | 0.08%   |
| Plantronics                                  | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 89        | 6.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 56        | 4.01%   |
| AMD Starship/Matisse HD Audio Controller                                   | 48        | 3.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 45        | 3.22%   |
| AMD Family 17h/19h HD Audio Controller                                     | 44        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42        | 3%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 34        | 2.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 34        | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 2.29%   |
| Intel 8 Series HD Audio Controller                                         | 31        | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 30        | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 28        | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 28        | 2%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 25        | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 24        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 23        | 1.65%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 1.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21        | 1.5%    |
| Nvidia GP106 High Definition Audio Controller                              | 20        | 1.43%   |
| Intel 200 Series PCH HD Audio                                              | 19        | 1.36%   |
| AMD FCH Azalia Controller                                                  | 19        | 1.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 17        | 1.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17        | 1.22%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 1.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 14        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 0.86%   |
| Realtek Semiconductor USB Audio                                            | 11        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11        | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 10        | 0.72%   |
| Kingston Technology HyperX 7.1 Audio                                       | 10        | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10        | 0.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 0.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10        | 0.72%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 9         | 0.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 119       | 24.9%   |
| SK hynix            | 102       | 21.34%  |
| Kingston            | 65        | 13.6%   |
| Micron Technology   | 42        | 8.79%   |
| Corsair             | 39        | 8.16%   |
| Crucial             | 32        | 6.69%   |
| Unknown             | 30        | 6.28%   |
| G.Skill             | 14        | 2.93%   |
| Elpida              | 10        | 2.09%   |
| Ramaxel Technology  | 6         | 1.26%   |
| A-DATA Technology   | 6         | 1.26%   |
| Team                | 2         | 0.42%   |
| Unknown (ABCD)      | 1         | 0.21%   |
| Transcend           | 1         | 0.21%   |
| Toshiba             | 1         | 0.21%   |
| SK_Hynix            | 1         | 0.21%   |
| Patriot             | 1         | 0.21%   |
| Nanya Technology    | 1         | 0.21%   |
| GeIL                | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| Apacer              | 1         | 0.21%   |
| 48spaces            | 1         | 0.21%   |
| Unknown             | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 1.2%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 5         | 1%      |
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s          | 5         | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1%      |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s | 5         | 1%      |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 1%      |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 4         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.8%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.8%    |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 4         | 0.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 0.8%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.6%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.6%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.6%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 3         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Kingston RAM KN2M64-ETB 8GB SODIMM DDR3 1600MT/s                 | 3         | 0.6%    |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 3         | 0.6%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 3         | 0.6%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 3         | 0.6%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.4%    |
| SK hynix RAM HMT41GU6BFR8A-PB 8192MB DIMM DDR3 2000MT/s          | 2         | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.4%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 217       | 51.54%  |
| DDR3    | 132       | 31.35%  |
| LPDDR3  | 28        | 6.65%   |
| DDR2    | 15        | 3.56%   |
| LPDDR4  | 13        | 3.09%   |
| SDRAM   | 6         | 1.43%   |
| Unknown | 6         | 1.43%   |
| LPDDR5  | 2         | 0.48%   |
| DDR5    | 1         | 0.24%   |
| DDR     | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 222       | 52.24%  |
| DIMM         | 149       | 35.06%  |
| Row Of Chips | 42        | 9.88%   |
| Chip         | 9         | 2.12%   |
| Unknown      | 2         | 0.47%   |
| FB-DIMM      | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 187       | 42.31%  |
| 4096  | 121       | 27.38%  |
| 16384 | 83        | 18.78%  |
| 2048  | 30        | 6.79%   |
| 32768 | 14        | 3.17%   |
| 1024  | 6         | 1.36%   |
| 128   | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 89        | 19.65%  |
| 2667  | 72        | 15.89%  |
| 2133  | 51        | 11.26%  |
| 3200  | 47        | 10.38%  |
| 2400  | 33        | 7.28%   |
| 1333  | 22        | 4.86%   |
| 3600  | 18        | 3.97%   |
| 1867  | 15        | 3.31%   |
| 667   | 13        | 2.87%   |
| 1334  | 10        | 2.21%   |
| 3400  | 7         | 1.55%   |
| 3466  | 6         | 1.32%   |
| 2933  | 6         | 1.32%   |
| 4267  | 4         | 0.88%   |
| 3000  | 4         | 0.88%   |
| 1067  | 4         | 0.88%   |
| 1066  | 4         | 0.88%   |
| 8400  | 3         | 0.66%   |
| 4800  | 3         | 0.66%   |
| 4199  | 3         | 0.66%   |
| 3733  | 3         | 0.66%   |
| 2800  | 3         | 0.66%   |
| 2666  | 3         | 0.66%   |
| 1800  | 3         | 0.66%   |
| 6400  | 2         | 0.44%   |
| 4266  | 2         | 0.44%   |
| 3866  | 2         | 0.44%   |
| 3333  | 2         | 0.44%   |
| 3266  | 2         | 0.44%   |
| 3151  | 2         | 0.44%   |
| 3100  | 2         | 0.44%   |
| 2000  | 2         | 0.44%   |
| 800   | 2         | 0.44%   |
| 4000  | 1         | 0.22%   |
| 3533  | 1         | 0.22%   |
| 2733  | 1         | 0.22%   |
| 2187  | 1         | 0.22%   |
| 2048  | 1         | 0.22%   |
| 1866  | 1         | 0.22%   |
| 975   | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 42.86%  |
| Brother Industries  | 5         | 35.71%  |
| Samsung Electronics | 1         | 7.14%   |
| Pantum              | 1         | 7.14%   |
| Canon               | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series            | 2         | 14.29%  |
| Samsung M2020 Series                 | 1         | 7.14%   |
| Pantum P2500W series                 | 1         | 7.14%   |
| HP Printing Support                  | 1         | 7.14%   |
| HP LaserJet Professional P 1102w     | 1         | 7.14%   |
| HP DeskJet F300 series               | 1         | 7.14%   |
| HP Deskjet 2540 series               | 1         | 7.14%   |
| Canon PIXMA MX530 Series             | 1         | 7.14%   |
| Brother QL-800 P-touch Label Printer | 1         | 7.14%   |
| Brother QL-550 printer               | 1         | 7.14%   |
| Brother PT-2450DX                    | 1         | 7.14%   |
| Brother HL-1210W series              | 1         | 7.14%   |
| Brother DCP-8085DN                   | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 113       | 21.81%  |
| Acer                                   | 53        | 10.23%  |
| IMC Networks                           | 50        | 9.65%   |
| Logitech                               | 46        | 8.88%   |
| Microdia                               | 37        | 7.14%   |
| Sunplus Innovation Technology          | 30        | 5.79%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 4.25%   |
| Realtek Semiconductor                  | 21        | 4.05%   |
| Quanta                                 | 18        | 3.47%   |
| Lite-On Technology                     | 18        | 3.47%   |
| Apple                                  | 18        | 3.47%   |
| Suyin                                  | 13        | 2.51%   |
| Microsoft                              | 10        | 1.93%   |
| Lenovo                                 | 10        | 1.93%   |
| Creative Technology                    | 6         | 1.16%   |
| Alcor Micro                            | 6         | 1.16%   |
| Samsung Electronics                    | 5         | 0.97%   |
| Luxvisions Innotech Limited            | 5         | 0.97%   |
| Primax Electronics                     | 4         | 0.77%   |
| Silicon Motion                         | 3         | 0.58%   |
| Omnivision                             | 3         | 0.58%   |
| MacroSilicon                           | 3         | 0.58%   |
| Z-Star Microelectronics                | 2         | 0.39%   |
| Unknown                                | 2         | 0.39%   |
| Sunplus Technology                     | 2         | 0.39%   |
| Sonix Technology                       | 2         | 0.39%   |
| Ricoh                                  | 2         | 0.39%   |
| Razer USA                              | 2         | 0.39%   |
| Generalplus Technology                 | 2         | 0.39%   |
| Cubeternet                             | 2         | 0.39%   |
| ALi                                    | 2         | 0.39%   |
| Technologies                           | 1         | 0.19%   |
| Syntek                                 | 1         | 0.19%   |
| Novatek Microelectronics               | 1         | 0.19%   |
| Mustek Systems                         | 1         | 0.19%   |
| Intel                                  | 1         | 0.19%   |
| Elgato Systems                         | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 36        | 6.81%   |
| Microdia Integrated_Webcam_HD                           | 21        | 3.97%   |
| IMC Networks Integrated Camera                          | 18        | 3.4%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 15        | 2.84%   |
| Chicony HP HD Camera                                    | 12        | 2.27%   |
| Sunplus Integrated_Webcam_HD                            | 10        | 1.89%   |
| Acer Integrated Camera                                  | 10        | 1.89%   |
| Logitech C922 Pro Stream Webcam                         | 9         | 1.7%    |
| Chicony HP HD Webcam                                    | 9         | 1.7%    |
| Lite-On Integrated Camera                               | 8         | 1.51%   |
| Chicony HD Webcam                                       | 8         | 1.51%   |
| Realtek Integrated_Webcam_HD                            | 7         | 1.32%   |
| Logitech HD Pro Webcam C920                             | 7         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera        | 7         | 1.32%   |
| Acer Lenovo EasyCamera                                  | 7         | 1.32%   |
| Acer BisonCam, NB Pro                                   | 7         | 1.32%   |
| Apple iPhone5/5C/5S/6                                   | 6         | 1.13%   |
| Sunplus HD WebCam                                       | 5         | 0.95%   |
| Samsung Galaxy A5 (MTP)                                 | 5         | 0.95%   |
| Quanta HD User Facing                                   | 5         | 0.95%   |
| Microsoft LifeCam Cinema                                | 5         | 0.95%   |
| Microdia Integrated Webcam                              | 5         | 0.95%   |
| Logitech Webcam C270                                    | 5         | 0.95%   |
| Lite-On HP HD Camera                                    | 5         | 0.95%   |
| Lenovo Integrated Webcam [R5U877]                       | 5         | 0.95%   |
| Creative Live! Cam Chat HD [VF0700]                     | 5         | 0.95%   |
| Chicony Integrated HP HD Webcam                         | 5         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 5         | 0.95%   |
| Apple FaceTime HD Camera (Built-in)                     | 5         | 0.95%   |
| Acer SunplusIT Integrated Camera                        | 5         | 0.95%   |
| Acer Lenovo Integrated Webcam                           | 5         | 0.95%   |
| Primax HP HD Webcam [Fixed]                             | 4         | 0.76%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 0.76%   |
| Logitech Webcam C930e                                   | 4         | 0.76%   |
| Lite-On HP HD Webcam                                    | 4         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 0.76%   |
| Acer HD Webcam                                          | 4         | 0.76%   |
| Sunplus Laptop Integrated Webcam HD                     | 3         | 0.57%   |
| Quanta HP TrueVision HD Camera                          | 3         | 0.57%   |
| Quanta HP HD Camera                                     | 3         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 56        | 42.11%  |
| Synaptics                  | 42        | 31.58%  |
| Upek                       | 14        | 10.53%  |
| Shenzhen Goodix Technology | 10        | 7.52%   |
| Elan Microelectronics      | 5         | 3.76%   |
| AuthenTec                  | 3         | 2.26%   |
| LighTuning Technology      | 2         | 1.5%    |
| Samsung Electronics        | 1         | 0.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 13.53%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 9.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 9.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 8.27%   |
| Unknown                                                                    | 8         | 6.02%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 5.26%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 4.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 3.76%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.76%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.01%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 3.01%   |
| Validity Sensors VFS491                                                    | 3         | 2.26%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 2.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.5%    |
| AuthenTec AES2810                                                          | 2         | 1.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.75%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.75%   |
| Synaptics  WBDI                                                            | 1         | 0.75%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.75%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.75%   |
| AuthenTec AES1600                                                          | 1         | 0.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 22        | 38.6%   |
| Broadcom              | 20        | 35.09%  |
| Upek                  | 7         | 12.28%  |
| Lenovo                | 4         | 7.02%   |
| OmniKey               | 2         | 3.51%   |
| Yubico.com            | 1         | 1.75%   |
| Gemalto (was Gemplus) | 1         | 1.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 38.6%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 12.28%  |
| Broadcom 5880                                                                | 6         | 10.53%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 7.02%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 5.26%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 3.51%   |
| Broadcom 58200                                                               | 2         | 3.51%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 1.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 520       | 64.2%   |
| 1     | 219       | 27.04%  |
| 2     | 56        | 6.91%   |
| 3     | 15        | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 133       | 37.46%  |
| Graphics card            | 54        | 15.21%  |
| Chipcard                 | 49        | 13.8%   |
| Net/wireless             | 46        | 12.96%  |
| Unassigned class         | 19        | 5.35%   |
| Multimedia controller    | 14        | 3.94%   |
| Camera                   | 8         | 2.25%   |
| Communication controller | 7         | 1.97%   |
| Card reader              | 6         | 1.69%   |
| Sound                    | 5         | 1.41%   |
| Net/ethernet             | 4         | 1.13%   |
| Wireless                 | 3         | 0.85%   |
| Storage                  | 3         | 0.85%   |
| Bluetooth                | 3         | 0.85%   |
| Dvb card                 | 1         | 0.28%   |

