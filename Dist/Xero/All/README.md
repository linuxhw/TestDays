Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 147

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| JINGSHA       | Unknown                     | Desktop     | [c8bd846b63](https://linux-hardware.org/?probe=c8bd846b63) | Feb 26, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [33723c8b80](https://linux-hardware.org/?probe=33723c8b80) | Feb 25, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d76b048134](https://linux-hardware.org/?probe=d76b048134) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP            | ProBook 6565b               | Notebook    | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| HP            | 828A                        | Desktop     | [5f430ba8d1](https://linux-hardware.org/?probe=5f430ba8d1) | Jan 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| HP            | 86EE                        | All in one  | [1fc671302e](https://linux-hardware.org/?probe=1fc671302e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [77768feff6](https://linux-hardware.org/?probe=77768feff6) | Jan 01, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion        | P6816                       | Notebook    | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [f074ef2e7c](https://linux-hardware.org/?probe=f074ef2e7c) | Nov 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | Notebook    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [711e95b72e](https://linux-hardware.org/?probe=711e95b72e) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ff0c19c661](https://linux-hardware.org/?probe=ff0c19c661) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf4fa1baf](https://linux-hardware.org/?probe=bcf4fa1baf) | Oct 18, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [07b256f333](https://linux-hardware.org/?probe=07b256f333) | Oct 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fc1ec464bf](https://linux-hardware.org/?probe=fc1ec464bf) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bf0e112f9a](https://linux-hardware.org/?probe=bf0e112f9a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [00ab764924](https://linux-hardware.org/?probe=00ab764924) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e037086b30](https://linux-hardware.org/?probe=e037086b30) | Oct 14, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [a11de13c4f](https://linux-hardware.org/?probe=a11de13c4f) | Oct 04, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [6de76ddb0e](https://linux-hardware.org/?probe=6de76ddb0e) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | Notebook    | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | Notebook    | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | Desktop     | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | Desktop     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP            | 2179                        | Desktop     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell          | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 97        | 88.18%  |
| Xero         | 13        | 11.82%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 109       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.16.15-arch1-1   | 6         | 5%      |
| 6.1.12-arch1-1    | 5         | 4.17%   |
| 5.18.16-arch1-1   | 4         | 3.33%   |
| 6.1.1-arch1-1     | 3         | 2.5%    |
| 5.17.9-arch1-1    | 3         | 2.5%    |
| 5.16.2-arch1-1    | 3         | 2.5%    |
| 5.16.1-arch1-1    | 3         | 2.5%    |
| 5.15.33-1-lts     | 3         | 2.5%    |
| 5.14.14-arch1-1   | 3         | 2.5%    |
| 6.0.7-arch1-1     | 2         | 1.67%   |
| 6.0.12-arch1-1    | 2         | 1.67%   |
| 5.19.9-arch1-1    | 2         | 1.67%   |
| 5.19.13-arch1-1   | 2         | 1.67%   |
| 5.19.12-arch1-1   | 2         | 1.67%   |
| 5.18.3-arch1-1    | 2         | 1.67%   |
| 5.18.11-arch1-1   | 2         | 1.67%   |
| 5.17.5-arch1-1    | 2         | 1.67%   |
| 5.17.1-arch1-1    | 2         | 1.67%   |
| 5.16.8-arch1-1    | 2         | 1.67%   |
| 5.16.16-arch1-1   | 2         | 1.67%   |
| 5.16.13-arch1-1   | 2         | 1.67%   |
| 5.16.12-arch1-1   | 2         | 1.67%   |
| 5.15.10-arch1-1   | 2         | 1.67%   |
| 5.14.8-zen1-1-zen | 2         | 1.67%   |
| 6.1.8-arch1-1     | 1         | 0.83%   |
| 6.1.7-arch1-1     | 1         | 0.83%   |
| 6.1.6-arch1-3     | 1         | 0.83%   |
| 6.1.6-arch1-1     | 1         | 0.83%   |
| 6.1.4-arch1-1     | 1         | 0.83%   |
| 6.1.3-zen1-1-zen  | 1         | 0.83%   |
| 6.0.9-arch1-1     | 1         | 0.83%   |
| 6.0.8-zen1-1-zen  | 1         | 0.83%   |
| 6.0.8-arch1-1     | 1         | 0.83%   |
| 6.0.6-zen1-1-zen  | 1         | 0.83%   |
| 6.0.6-arch1-1     | 1         | 0.83%   |
| 6.0.2-zen1-1-zen  | 1         | 0.83%   |
| 6.0.2-arch1-1     | 1         | 0.83%   |
| 6.0.11-arch1-1    | 1         | 0.83%   |
| 6.0.1-arch2-1     | 1         | 0.83%   |
| 5.19.3-arch1-1    | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 5%      |
| 6.1.12  | 5         | 4.17%   |
| 5.18.16 | 4         | 3.33%   |
| 5.14.14 | 4         | 3.33%   |
| 6.1.1   | 3         | 2.5%    |
| 5.19.13 | 3         | 2.5%    |
| 5.17.9  | 3         | 2.5%    |
| 5.16.2  | 3         | 2.5%    |
| 5.16.16 | 3         | 2.5%    |
| 5.16.1  | 3         | 2.5%    |
| 5.15.33 | 3         | 2.5%    |
| 5.15.12 | 3         | 2.5%    |
| 5.14.8  | 3         | 2.5%    |
| 5.14.16 | 3         | 2.5%    |
| 6.1.6   | 2         | 1.67%   |
| 6.0.8   | 2         | 1.67%   |
| 6.0.7   | 2         | 1.67%   |
| 6.0.6   | 2         | 1.67%   |
| 6.0.2   | 2         | 1.67%   |
| 6.0.12  | 2         | 1.67%   |
| 5.19.9  | 2         | 1.67%   |
| 5.19.12 | 2         | 1.67%   |
| 5.18.3  | 2         | 1.67%   |
| 5.18.11 | 2         | 1.67%   |
| 5.17.5  | 2         | 1.67%   |
| 5.17.1  | 2         | 1.67%   |
| 5.16.8  | 2         | 1.67%   |
| 5.16.13 | 2         | 1.67%   |
| 5.16.12 | 2         | 1.67%   |
| 5.15.13 | 2         | 1.67%   |
| 5.15.11 | 2         | 1.67%   |
| 5.15.10 | 2         | 1.67%   |
| 6.1.8   | 1         | 0.83%   |
| 6.1.7   | 1         | 0.83%   |
| 6.1.4   | 1         | 0.83%   |
| 6.1.3   | 1         | 0.83%   |
| 6.0.9   | 1         | 0.83%   |
| 6.0.11  | 1         | 0.83%   |
| 6.0.1   | 1         | 0.83%   |
| 5.19.3  | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 19.66%  |
| 5.15    | 18        | 15.38%  |
| 6.1     | 13        | 11.11%  |
| 6.0     | 13        | 11.11%  |
| 5.14    | 13        | 11.11%  |
| 5.19    | 11        | 9.4%    |
| 5.18    | 11        | 9.4%    |
| 5.17    | 8         | 6.84%   |
| 5.10    | 3         | 2.56%   |
| 5.13    | 2         | 1.71%   |
| 5.12    | 1         | 0.85%   |
| 5.11    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 102       | 91.89%  |
| XFCE   | 4         | 3.6%    |
| GNOME  | 3         | 2.7%    |
| LeftWM | 1         | 0.9%    |
| KDE    | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 96        | 87.27%  |
| Wayland | 12        | 10.91%  |
| Tty     | 2         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 76        | 67.26%  |
| Unknown | 19        | 16.81%  |
| LightDM | 15        | 13.27%  |
| GDM     | 2         | 1.77%   |
| TDM     | 1         | 0.88%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 60        | 54.55%  |
| en_IN | 8         | 7.27%   |
| en_GB | 6         | 5.45%   |
| de_DE | 6         | 5.45%   |
| C     | 5         | 4.55%   |
| pl_PL | 4         | 3.64%   |
| ru_RU | 3         | 2.73%   |
| it_IT | 3         | 2.73%   |
| es_MX | 3         | 2.73%   |
| en_AU | 3         | 2.73%   |
| fr_FR | 2         | 1.82%   |
| vi_VN | 1         | 0.91%   |
| en_IL | 1         | 0.91%   |
| en_DK | 1         | 0.91%   |
| en_CA | 1         | 0.91%   |
| en_AG | 1         | 0.91%   |
| de_AT | 1         | 0.91%   |
| ba_RU | 1         | 0.91%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 70        | 63.64%  |
| BIOS | 40        | 36.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 58        | 52.25%  |
| Xfs     | 28        | 25.23%  |
| Ext4    | 19        | 17.12%  |
| Overlay | 6         | 5.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 77        | 70%     |
| Unknown | 19        | 17.27%  |
| MBR     | 14        | 12.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 73.68%  |
| Yes       | 30        | 26.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 63.64%  |
| Yes       | 40        | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 31        | 28.44%  |
| Lenovo              | 19        | 17.43%  |
| Dell                | 15        | 13.76%  |
| Hewlett-Packard     | 14        | 12.84%  |
| MSI                 | 7         | 6.42%   |
| Gigabyte Technology | 4         | 3.67%   |
| Acer                | 4         | 3.67%   |
| Pegatron            | 3         | 2.75%   |
| ASRock              | 3         | 2.75%   |
| HUAWEI              | 2         | 1.83%   |
| Toshiba             | 1         | 0.92%   |
| Medion              | 1         | 0.92%   |
| JINGSHA             | 1         | 0.92%   |
| BESSTAR Tech        | 1         | 0.92%   |
| Aquarius            | 1         | 0.92%   |
| Apple               | 1         | 0.92%   |
| Unknown             | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 2.75%   |
| MSI MS-7971                                | 2         | 1.83%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 1.83%   |
| Unknown                                    | 2         | 1.83%   |
| Toshiba TECRA A11                          | 1         | 0.92%   |
| Pegatron p6-2026                           | 1         | 0.92%   |
| Pegatron D15K                              | 1         | 0.92%   |
| Pegatron 20-b010                           | 1         | 0.92%   |
| MSI MS-7C91                                | 1         | 0.92%   |
| MSI MS-7B61                                | 1         | 0.92%   |
| MSI Katana GF66 11UE                       | 1         | 0.92%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.92%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.92%   |
| Medion P6816                               | 1         | 0.92%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 0.92%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.92%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 0.92%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.92%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.92%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.92%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.92%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 0.92%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 0.92%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 0.92%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 0.92%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 0.92%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.92%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 0.92%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.92%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 0.92%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 0.92%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 0.92%   |
| Lenovo IdeaPad 3 14IGL05 81WH              | 1         | 0.92%   |
| HUAWEI WRT-WX9                             | 1         | 0.92%   |
| HUAWEI BOM-WXX9                            | 1         | 0.92%   |
| HP ZBook 15 G4                             | 1         | 0.92%   |
| HP Z230 SFF Workstation                    | 1         | 0.92%   |
| HP ProOne 400 G1 AiO                       | 1         | 0.92%   |
| HP ProBook 6565b                           | 1         | 0.92%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 8         | 7.34%   |
| ASUS ROG           | 8         | 7.34%   |
| Lenovo IdeaPad     | 6         | 5.5%    |
| ASUS TUF           | 5         | 4.59%   |
| Dell Precision     | 4         | 3.67%   |
| Dell Latitude      | 4         | 3.67%   |
| ASUS VivoBook      | 4         | 3.67%   |
| Acer Aspire        | 4         | 3.67%   |
| Lenovo Legion      | 3         | 2.75%   |
| HP Laptop          | 3         | 2.75%   |
| Dell Inspiron      | 3         | 2.75%   |
| ASUS ASUS          | 3         | 2.75%   |
| MSI MS-7971        | 2         | 1.83%   |
| HP Pavilion        | 2         | 1.83%   |
| ASUS PRIME         | 2         | 1.83%   |
| Unknown            | 2         | 1.83%   |
| Toshiba TECRA      | 1         | 0.92%   |
| Pegatron p6-2026   | 1         | 0.92%   |
| Pegatron D15K      | 1         | 0.92%   |
| Pegatron 20-b010   | 1         | 0.92%   |
| MSI MS-7C91        | 1         | 0.92%   |
| MSI MS-7B61        | 1         | 0.92%   |
| MSI Katana         | 1         | 0.92%   |
| MSI GP73           | 1         | 0.92%   |
| MSI GF63           | 1         | 0.92%   |
| Medion P6816       | 1         | 0.92%   |
| Lenovo Yoga        | 1         | 0.92%   |
| Lenovo Y520-15IKBN | 1         | 0.92%   |
| HUAWEI WRT-WX9     | 1         | 0.92%   |
| HUAWEI BOM-WXX9    | 1         | 0.92%   |
| HP ZBook           | 1         | 0.92%   |
| HP Z230            | 1         | 0.92%   |
| HP ProOne          | 1         | 0.92%   |
| HP ProBook         | 1         | 0.92%   |
| HP Notebook        | 1         | 0.92%   |
| HP ENVY            | 1         | 0.92%   |
| HP Compaq          | 1         | 0.92%   |
| HP 750-424         | 1         | 0.92%   |
| HP 245             | 1         | 0.92%   |
| Gigabyte Z170X-UD3 | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 20        | 18.35%  |
| 2020 | 16        | 14.68%  |
| 2017 | 12        | 11.01%  |
| 2018 | 11        | 10.09%  |
| 2021 | 10        | 9.17%   |
| 2012 | 9         | 8.26%   |
| 2015 | 6         | 5.5%    |
| 2013 | 6         | 5.5%    |
| 2011 | 4         | 3.67%   |
| 2010 | 4         | 3.67%   |
| 2016 | 3         | 2.75%   |
| 2014 | 3         | 2.75%   |
| 2022 | 2         | 1.83%   |
| 2009 | 2         | 1.83%   |
| 2008 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 64        | 58.72%  |
| Desktop     | 41        | 37.61%  |
| Convertible | 3         | 2.75%   |
| Server      | 1         | 0.92%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 109       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 26.61%  |
| 16.01-24.0  | 26        | 23.85%  |
| 8.01-16.0   | 22        | 20.18%  |
| 32.01-64.0  | 14        | 12.84%  |
| 3.01-4.0    | 13        | 11.93%  |
| 24.01-32.0  | 3         | 2.75%   |
| 64.01-256.0 | 2         | 1.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 39        | 33.05%  |
| 1.01-2.0   | 27        | 22.88%  |
| 4.01-8.0   | 24        | 20.34%  |
| 3.01-4.0   | 15        | 12.71%  |
| 8.01-16.0  | 5         | 4.24%   |
| 16.01-24.0 | 4         | 3.39%   |
| 0.51-1.0   | 2         | 1.69%   |
| 0.01-0.5   | 2         | 1.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 54.55%  |
| 2      | 28        | 25.45%  |
| 3      | 10        | 9.09%   |
| 4      | 5         | 4.55%   |
| 5      | 4         | 3.64%   |
| 6      | 2         | 1.82%   |
| 7      | 1         | 0.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 77.06%  |
| Yes       | 25        | 22.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 81.65%  |
| No        | 20        | 18.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 81.65%  |
| No        | 20        | 18.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 71.82%  |
| No        | 31        | 28.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 24        | 21.82%  |
| India                  | 10        | 9.09%   |
| Germany                | 9         | 8.18%   |
| Poland                 | 5         | 4.55%   |
| Russia                 | 4         | 3.64%   |
| Italy                  | 4         | 3.64%   |
| France                 | 4         | 3.64%   |
| UK                     | 3         | 2.73%   |
| Mexico                 | 3         | 2.73%   |
| Greece                 | 3         | 2.73%   |
| Canada                 | 3         | 2.73%   |
| Australia              | 3         | 2.73%   |
| Turkey                 | 2         | 1.82%   |
| Sweden                 | 2         | 1.82%   |
| Pakistan               | 2         | 1.82%   |
| Norway                 | 2         | 1.82%   |
| Netherlands            | 2         | 1.82%   |
| Lebanon                | 2         | 1.82%   |
| Zambia                 | 1         | 0.91%   |
| Vietnam                | 1         | 0.91%   |
| Togo                   | 1         | 0.91%   |
| Spain                  | 1         | 0.91%   |
| Romania                | 1         | 0.91%   |
| Portugal               | 1         | 0.91%   |
| Palestinian Territory  | 1         | 0.91%   |
| Morocco                | 1         | 0.91%   |
| Mongolia               | 1         | 0.91%   |
| Malaysia               | 1         | 0.91%   |
| Israel                 | 1         | 0.91%   |
| Indonesia              | 1         | 0.91%   |
| Hungary                | 1         | 0.91%   |
| Denmark                | 1         | 0.91%   |
| Czechia                | 1         | 0.91%   |
| Cyprus                 | 1         | 0.91%   |
| Colombia               | 1         | 0.91%   |
| Chile                  | 1         | 0.91%   |
| Brazil                 | 1         | 0.91%   |
| Bosnia and Herzegovina | 1         | 0.91%   |
| Bahrain                | 1         | 0.91%   |
| Austria                | 1         | 0.91%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Longmont       | 3         | 2.73%   |
| Phoenix        | 2         | 1.82%   |
| Madurai        | 2         | 1.82%   |
| Istanbul       | 2         | 1.82%   |
| Bremen         | 2         | 1.82%   |
| Beirut         | 2         | 1.82%   |
| Zenica         | 1         | 0.91%   |
| Zell am See    | 1         | 0.91%   |
| Wroclaw        | 1         | 0.91%   |
| Wrexham        | 1         | 0.91%   |
| Wells          | 1         | 0.91%   |
| Warsaw         | 1         | 0.91%   |
| Ulan Bator     | 1         | 0.91%   |
| Ufa            | 1         | 0.91%   |
| Toronto        | 1         | 0.91%   |
| Tel Aviv       | 1         | 0.91%   |
| Taranto        | 1         | 0.91%   |
| Tangerang      | 1         | 0.91%   |
| Stuttgart      | 1         | 0.91%   |
| Stow           | 1         | 0.91%   |
| Stockholm      | 1         | 0.91%   |
| Stavropol      | 1         | 0.91%   |
| Springfield    | 1         | 0.91%   |
| Sonora         | 1         | 0.91%   |
| Silkeborg      | 1         | 0.91%   |
| Shadrinsk      | 1         | 0.91%   |
| Seattle        | 1         | 0.91%   |
| Santa Cruz     | 1         | 0.91%   |
| Salt Lake City | 1         | 0.91%   |
| Ramallah       | 1         | 0.91%   |
| Pune           | 1         | 0.91%   |
| Poznan         | 1         | 0.91%   |
| Portland       | 1         | 0.91%   |
| Porcia         | 1         | 0.91%   |
| Pirmasens      | 1         | 0.91%   |
| Perth          | 1         | 0.91%   |
| Pavia          | 1         | 0.91%   |
| Passos         | 1         | 0.91%   |
| Paris          | 1         | 0.91%   |
| Oslo           | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 32        | 46     | 17.39%  |
| Samsung Electronics         | 32        | 44     | 17.39%  |
| WDC                         | 25        | 34     | 13.59%  |
| Kingston                    | 12        | 16     | 6.52%   |
| Toshiba                     | 11        | 13     | 5.98%   |
| Sandisk                     | 8         | 10     | 4.35%   |
| Intel                       | 7         | 9      | 3.8%    |
| HGST                        | 6         | 6      | 3.26%   |
| Unknown                     | 5         | 6      | 2.72%   |
| Micron Technology           | 4         | 6      | 2.17%   |
| Crucial                     | 4         | 6      | 2.17%   |
| China                       | 4         | 4      | 2.17%   |
| Phison                      | 3         | 3      | 1.63%   |
| Hitachi                     | 3         | 3      | 1.63%   |
| Transcend                   | 2         | 2      | 1.09%   |
| SK hynix                    | 2         | 2      | 1.09%   |
| LITEON                      | 2         | 2      | 1.09%   |
| KIOXIA                      | 2         | 3      | 1.09%   |
| A-DATA Technology           | 2         | 2      | 1.09%   |
| XPG                         | 1         | 1      | 0.54%   |
| Vaseky                      | 1         | 1      | 0.54%   |
| SPCC                        | 1         | 1      | 0.54%   |
| Silicon Motion              | 1         | 1      | 0.54%   |
| Realtek Semiconductor       | 1         | 1      | 0.54%   |
| PNY                         | 1         | 1      | 0.54%   |
| Plextor                     | 1         | 1      | 0.54%   |
| OSCOO                       | 1         | 1      | 0.54%   |
| Micron/Crucial Technology   | 1         | 1      | 0.54%   |
| LITEONIT                    | 1         | 1      | 0.54%   |
| Kingston Technology Company | 1         | 1      | 0.54%   |
| Intenso                     | 1         | 1      | 0.54%   |
| Inateck                     | 1         | 1      | 0.54%   |
| GOODRAM                     | 1         | 1      | 0.54%   |
| Biostar                     | 1         | 1      | 0.54%   |
| Apple                       | 1         | 1      | 0.54%   |
| Apacer                      | 1         | 1      | 0.54%   |
| 2-Power                     | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.44%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.44%   |
| Seagate One Touch HDD 2TB                           | 3         | 1.44%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.44%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 2         | 0.96%   |
| Unknown MMC Card  64GB                              | 2         | 0.96%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.96%   |
| Toshiba DT01ACA300 3TB                              | 2         | 0.96%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.96%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2         | 0.96%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.96%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.96%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.96%   |
| Samsung SSD 980 1TB                                 | 2         | 0.96%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.96%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.96%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.96%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB | 2         | 0.96%   |
| HGST HTS545050A7E680 500GB                          | 2         | 0.96%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.96%   |
| China SSD 1TB                                       | 2         | 0.96%   |
| XPG GAMMIX S50 2TB                                  | 1         | 0.48%   |
| WDC WDS512G1X0C-00ENX0 512GB                        | 1         | 0.48%   |
| WDC WDS500G3XHC-00SJG0 500GB                        | 1         | 0.48%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.48%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.48%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.48%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.48%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.48%   |
| WDC WD800JD-00MSA1 80GB                             | 1         | 0.48%   |
| WDC WD7500BPKT-75PK4T0 752GB                        | 1         | 0.48%   |
| WDC WD6400AAKS-22A7B2 640GB                         | 1         | 0.48%   |
| WDC WD5000AAVS-00ZTB0 500GB                         | 1         | 0.48%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.48%   |
| WDC WD40EZRZ-22GXCB0 4TB                            | 1         | 0.48%   |
| WDC WD2500BEVT-60ZCT1 250GB                         | 1         | 0.48%   |
| WDC WD20EZRZ-60Z5HB0 2TB                            | 1         | 0.48%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1         | 0.48%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 45     | 47.06%  |
| WDC                 | 16        | 22     | 23.53%  |
| Toshiba             | 8         | 10     | 11.76%  |
| HGST                | 6         | 6      | 8.82%   |
| Hitachi             | 3         | 3      | 4.41%   |
| Samsung Electronics | 2         | 2      | 2.94%   |
| Unknown             | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 17     | 25.45%  |
| Kingston            | 8         | 11     | 14.55%  |
| Crucial             | 4         | 6      | 7.27%   |
| China               | 4         | 4      | 7.27%   |
| WDC                 | 3         | 3      | 5.45%   |
| SanDisk             | 3         | 3      | 5.45%   |
| Transcend           | 2         | 2      | 3.64%   |
| LITEON              | 2         | 2      | 3.64%   |
| Vaseky              | 1         | 1      | 1.82%   |
| SPCC                | 1         | 1      | 1.82%   |
| PNY                 | 1         | 1      | 1.82%   |
| Plextor             | 1         | 1      | 1.82%   |
| OSCOO               | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| LITEONIT            | 1         | 1      | 1.82%   |
| Intenso             | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| GOODRAM             | 1         | 1      | 1.82%   |
| Biostar             | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |
| Apacer              | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |
| 2-Power             | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 89     | 34.78%  |
| NVMe | 55        | 78     | 34.16%  |
| SSD  | 46        | 63     | 28.57%  |
| MMC  | 4         | 5      | 2.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 143    | 52.78%  |
| NVMe | 55        | 77     | 38.19%  |
| SAS  | 9         | 10     | 6.25%   |
| MMC  | 4         | 5      | 2.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 72     | 43.75%  |
| 0.51-1.0   | 43        | 54     | 38.39%  |
| 1.01-2.0   | 13        | 17     | 11.61%  |
| 4.01-10.0  | 4         | 6      | 3.57%   |
| 2.01-3.0   | 2         | 2      | 1.79%   |
| 3.01-4.0   | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 29        | 25.44%  |
| 1001-2000      | 21        | 18.42%  |
| 251-500        | 15        | 13.16%  |
| 501-1000       | 13        | 11.4%   |
| 101-250        | 11        | 9.65%   |
| Unknown        | 9         | 7.89%   |
| 51-100         | 6         | 5.26%   |
| 21-50          | 4         | 3.51%   |
| 1-20           | 4         | 3.51%   |
| 2001-3000      | 2         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 22.81%  |
| 1-20           | 24        | 21.05%  |
| 51-100         | 17        | 14.91%  |
| 251-500        | 10        | 8.77%   |
| 21-50          | 9         | 7.89%   |
| Unknown        | 9         | 7.89%   |
| 501-1000       | 7         | 6.14%   |
| 2001-3000      | 5         | 4.39%   |
| 1001-2000      | 4         | 3.51%   |
| More than 3000 | 3         | 2.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 4.55%   |
| WDC WD10EADS-00M2B0 1TB                                         | 1         | 1      | 4.55%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 1         | 2      | 4.55%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 4.55%   |
| Toshiba MK4058GSX 400GB                                         | 1         | 1      | 4.55%   |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 4.55%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 4.55%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 4.55%   |
| Seagate ST31000524AS 1TB                                        | 1         | 1      | 4.55%   |
| Seagate ST2000VX000-1CU164 2TB                                  | 1         | 1      | 4.55%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 1         | 1      | 4.55%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 4.55%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 4.55%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 512GB | 1         | 1      | 4.55%   |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 4.55%   |
| Kingston SUV400S37240G 240GB SSD                                | 1         | 1      | 4.55%   |
| Hitachi HTS725050A9A364 500GB                                   | 1         | 1      | 4.55%   |
| Hitachi HCP725050GLA380 500GB                                   | 1         | 1      | 4.55%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 4.55%   |
| China SATA3 240GB SSD                                           | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 38.1%   |
| WDC                 | 3         | 4      | 14.29%  |
| Toshiba             | 2         | 3      | 9.52%   |
| Kingston            | 2         | 2      | 9.52%   |
| Hitachi             | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| China               | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 47.06%  |
| WDC     | 3         | 4      | 17.65%  |
| Toshiba | 2         | 3      | 11.76%  |
| Hitachi | 2         | 2      | 11.76%  |
| HGST    | 2         | 2      | 11.76%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 80%     |
| SSD  | 3         | 3      | 15%     |
| NVMe | 1         | 1      | 5%      |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 84        | 154    | 65.12%  |
| Detected | 26        | 58     | 20.16%  |
| Malfunc  | 19        | 23     | 14.73%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 79        | 50.64%  |
| AMD                          | 21        | 13.46%  |
| Samsung Electronics          | 18        | 11.54%  |
| SanDisk                      | 12        | 7.69%   |
| Kingston Technology Company  | 5         | 3.21%   |
| Micron Technology            | 4         | 2.56%   |
| Toshiba America Info Systems | 3         | 1.92%   |
| Phison Electronics           | 3         | 1.92%   |
| SK hynix                     | 2         | 1.28%   |
| Realtek Semiconductor        | 2         | 1.28%   |
| KIOXIA                       | 2         | 1.28%   |
| Silicon Motion               | 1         | 0.64%   |
| Seagate Technology           | 1         | 0.64%   |
| Micron/Crucial Technology    | 1         | 0.64%   |
| ASMedia Technology           | 1         | 0.64%   |
| ADATA Technology             | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 11.24%  |
| Samsung NVMe SSD Controller 980                                                | 6         | 3.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.55%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 3.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.96%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 2.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.96%   |
| Micron Non-Volatile memory controller                                          | 4         | 2.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.37%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 1.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.78%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.78%   |
| Intel SSD 660P Series                                                          | 3         | 1.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.78%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.18%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.18%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.18%   |
| AMD FCH SATA Controller D                                                      | 2         | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.59%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.59%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 83        | 53.55%  |
| NVMe | 55        | 35.48%  |
| RAID | 16        | 10.32%  |
| IDE  | 1         | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 83        | 76.15%  |
| AMD    | 26        | 23.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 3.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 2.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 2.73%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 2.73%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 2.73%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 2         | 1.82%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 1.82%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 2         | 1.82%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 1.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 1.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.82%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 1.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.82%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 2         | 1.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 1.82%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 1.82%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 1         | 0.91%   |
| Intel Genuine CPU 0000 @ 2.10GHz        | 1         | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.91%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 0.91%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 0.91%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.91%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 0.91%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 0.91%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 0.91%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 0.91%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 0.91%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 0.91%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 0.91%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 0.91%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 0.91%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 0.91%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1         | 0.91%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 30        | 27.27%  |
| Intel Core i5     | 30        | 27.27%  |
| AMD Ryzen 5       | 10        | 9.09%   |
| Other             | 9         | 8.18%   |
| AMD Ryzen 7       | 9         | 8.18%   |
| Intel Core i3     | 7         | 6.36%   |
| Intel Celeron     | 3         | 2.73%   |
| AMD Ryzen 3       | 2         | 1.82%   |
| Intel Xeon        | 1         | 0.91%   |
| Intel Genuine     | 1         | 0.91%   |
| Intel Core 2 Quad | 1         | 0.91%   |
| Intel Core 2 Duo  | 1         | 0.91%   |
| AMD Ryzen 9       | 1         | 0.91%   |
| AMD E1            | 1         | 0.91%   |
| AMD Athlon        | 1         | 0.91%   |
| AMD A8            | 1         | 0.91%   |
| AMD A6            | 1         | 0.91%   |
| AMD A4            | 1         | 0.91%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 46        | 41.82%  |
| 2      | 33        | 30%     |
| 6      | 17        | 15.45%  |
| 8      | 11        | 10%     |
| 16     | 1         | 0.91%   |
| 14     | 1         | 0.91%   |
| 12     | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 108       | 99.08%  |
| 2      | 1         | 0.92%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 89        | 80.91%  |
| 1      | 21        | 19.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 19.64%  |
| 0x906ea    | 7         | 6.25%   |
| 0x806c1    | 7         | 6.25%   |
| 0x306a9    | 6         | 5.36%   |
| 0x806ec    | 5         | 4.46%   |
| 0x806e9    | 5         | 4.46%   |
| 0x506e3    | 5         | 4.46%   |
| 0x08701021 | 5         | 4.46%   |
| 0x906e9    | 3         | 2.68%   |
| 0x806eb    | 3         | 2.68%   |
| 0x306c3    | 3         | 2.68%   |
| 0x206a7    | 3         | 2.68%   |
| 0x0a201016 | 3         | 2.68%   |
| 0x08108109 | 3         | 2.68%   |
| 0x906ed    | 2         | 1.79%   |
| 0x906eb    | 2         | 1.79%   |
| 0x706a8    | 2         | 1.79%   |
| 0x40651    | 2         | 1.79%   |
| 0x106e5    | 2         | 1.79%   |
| 0x1067a    | 2         | 1.79%   |
| 0xa0653    | 1         | 0.89%   |
| 0xa0652    | 1         | 0.89%   |
| 0x906a3    | 1         | 0.89%   |
| 0x806d1    | 1         | 0.89%   |
| 0x706e5    | 1         | 0.89%   |
| 0x406e3    | 1         | 0.89%   |
| 0x306f2    | 1         | 0.89%   |
| 0x306d4    | 1         | 0.89%   |
| 0x20655    | 1         | 0.89%   |
| 0x20652    | 1         | 0.89%   |
| 0x0a50000b | 1         | 0.89%   |
| 0x0a20120a | 1         | 0.89%   |
| 0x08701013 | 1         | 0.89%   |
| 0x08608103 | 1         | 0.89%   |
| 0x08600106 | 1         | 0.89%   |
| 0x0810100b | 1         | 0.89%   |
| 0x06006705 | 1         | 0.89%   |
| 0x0600611a | 1         | 0.89%   |
| 0x0500010d | 1         | 0.89%   |
| 0x03000027 | 1         | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 28.18%  |
| Zen 2            | 10        | 9.09%   |
| Haswell          | 10        | 9.09%   |
| IvyBridge        | 8         | 7.27%   |
| TigerLake        | 7         | 6.36%   |
| Zen+             | 6         | 5.45%   |
| Skylake          | 6         | 5.45%   |
| Zen 3            | 5         | 4.55%   |
| SandyBridge      | 4         | 3.64%   |
| Nehalem          | 3         | 2.73%   |
| Goldmont plus    | 3         | 2.73%   |
| Westmere         | 2         | 1.82%   |
| Penryn           | 2         | 1.82%   |
| Icelake          | 2         | 1.82%   |
| Excavator        | 2         | 1.82%   |
| CometLake        | 2         | 1.82%   |
| Broadwell        | 2         | 1.82%   |
| Zen              | 1         | 0.91%   |
| K10 Llano        | 1         | 0.91%   |
| Bobcat           | 1         | 0.91%   |
| Alderlake Hybrid | 1         | 0.91%   |
| Unknown          | 1         | 0.91%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 64        | 43.84%  |
| Nvidia            | 54        | 36.99%  |
| AMD               | 27        | 18.49%  |
| ASPEED Technology | 1         | 0.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 4.08%   |
| Intel HD Graphics 620                                                     | 5         | 3.4%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.72%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 2.04%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 3         | 2.04%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.04%   |
| Intel UHD Graphics 620                                                    | 3         | 2.04%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.04%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 3         | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.36%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 2         | 1.36%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.36%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 1.36%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 1.36%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.36%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.36%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.36%   |
| Intel HD Graphics 630                                                     | 2         | 1.36%   |
| Intel HD Graphics 5500                                                    | 2         | 1.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.36%   |
| AMD Renoir                                                                | 2         | 1.36%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2         | 1.36%   |
| Nvidia TU117M                                                             | 1         | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.68%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.68%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.68%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                     | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 30        | 27.52%  |
| Intel + Nvidia  | 29        | 26.61%  |
| 1 x AMD         | 21        | 19.27%  |
| 1 x Nvidia      | 20        | 18.35%  |
| Intel + AMD     | 3         | 2.75%   |
| AMD + Nvidia    | 3         | 2.75%   |
| 2 x Nvidia      | 1         | 0.92%   |
| 2 x Intel       | 1         | 0.92%   |
| Nvidia + ASPEED | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 64.55%  |
| Proprietary | 37        | 33.64%  |
| Unknown     | 2         | 1.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 57.27%  |
| 1.01-2.0   | 17        | 15.45%  |
| 7.01-8.0   | 7         | 6.36%   |
| 5.01-6.0   | 7         | 6.36%   |
| 0.01-0.5   | 7         | 6.36%   |
| 3.01-4.0   | 4         | 3.64%   |
| 8.01-16.0  | 3         | 2.73%   |
| 0.51-1.0   | 2         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 20        | 16%     |
| AU Optronics         | 19        | 15.2%   |
| Chimei Innolux       | 12        | 9.6%    |
| BOE                  | 12        | 9.6%    |
| LG Display           | 10        | 8%      |
| Goldstar             | 5         | 4%      |
| Ancor Communications | 5         | 4%      |
| Acer                 | 5         | 4%      |
| Dell                 | 4         | 3.2%    |
| AOC                  | 4         | 3.2%    |
| Sharp                | 3         | 2.4%    |
| Hewlett-Packard      | 3         | 2.4%    |
| PANDA                | 2         | 1.6%    |
| Lenovo               | 2         | 1.6%    |
| Iiyama               | 2         | 1.6%    |
| Apple                | 2         | 1.6%    |
| TMX                  | 1         | 0.8%    |
| Sceptre Tech         | 1         | 0.8%    |
| MSI                  | 1         | 0.8%    |
| LGD                  | 1         | 0.8%    |
| Konka                | 1         | 0.8%    |
| Kogan                | 1         | 0.8%    |
| KOC                  | 1         | 0.8%    |
| JRY                  | 1         | 0.8%    |
| Idek Iiyama          | 1         | 0.8%    |
| Hitachi              | 1         | 0.8%    |
| Gigabyte Technology  | 1         | 0.8%    |
| FOX                  | 1         | 0.8%    |
| CSO                  | 1         | 0.8%    |
| BenQ                 | 1         | 0.8%    |
| ASUSTek Computer     | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.34%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 1.56%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch   | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.56%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.78%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.78%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.78%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.78%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.78%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1         | 0.78%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.78%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch       | 1         | 0.78%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.78%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.78%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 0.78%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch     | 1         | 0.78%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1         | 0.78%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.78%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.78%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                         | 1         | 0.78%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.78%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD0561 1920x1080 294x165mm 13.3-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.78%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch             | 1         | 0.78%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 55.46%  |
| 1366x768 (WXGA)    | 16        | 13.45%  |
| 3840x2160 (4K)     | 8         | 6.72%   |
| 2560x1440 (QHD)    | 7         | 5.88%   |
| 3440x1440          | 5         | 4.2%    |
| 1600x900 (HD+)     | 4         | 3.36%   |
| 2560x1080          | 3         | 2.52%   |
| 1680x1050 (WSXGA+) | 2         | 1.68%   |
| 3840x2400          | 1         | 0.84%   |
| 3840x1080          | 1         | 0.84%   |
| 3200x1800 (QHD+)   | 1         | 0.84%   |
| 2160x1440          | 1         | 0.84%   |
| 1920x540           | 1         | 0.84%   |
| 1920x1200 (WUXGA)  | 1         | 0.84%   |
| 1440x900 (WXGA+)   | 1         | 0.84%   |
| 1280x1024 (SXGA)   | 1         | 0.84%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 41        | 32.8%   |
| 27      | 11        | 8.8%    |
| 23      | 10        | 8%      |
| 14      | 10        | 8%      |
| 13      | 9         | 7.2%    |
| 21      | 8         | 6.4%    |
| 34      | 6         | 4.8%    |
| 24      | 5         | 4%      |
| 84      | 4         | 3.2%    |
| 31      | 4         | 3.2%    |
| 17      | 3         | 2.4%    |
| Unknown | 3         | 2.4%    |
| 28      | 2         | 1.6%    |
| 20      | 2         | 1.6%    |
| 18      | 2         | 1.6%    |
| 54      | 1         | 0.8%    |
| 52      | 1         | 0.8%    |
| 48      | 1         | 0.8%    |
| 33      | 1         | 0.8%    |
| 12      | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 44.8%   |
| 501-600     | 25        | 20%     |
| 401-500     | 12        | 9.6%    |
| 701-800     | 7         | 5.6%    |
| 601-700     | 6         | 4.8%    |
| 201-300     | 5         | 4%      |
| 351-400     | 4         | 3.2%    |
| 1501-2000   | 4         | 3.2%    |
| 1001-1500   | 3         | 2.4%    |
| Unknown     | 3         | 2.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 94        | 84.68%  |
| 21/9    | 8         | 7.21%   |
| 16/10   | 4         | 3.6%    |
| Unknown | 2         | 1.8%    |
| 5/4     | 1         | 0.9%    |
| 32/9    | 1         | 0.9%    |
| 3/2     | 1         | 0.9%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 33.33%  |
| 201-250        | 21        | 17.07%  |
| 81-90          | 16        | 13.01%  |
| 351-500        | 11        | 8.94%   |
| 301-350        | 11        | 8.94%   |
| More than 1000 | 6         | 4.88%   |
| 71-80          | 3         | 2.44%   |
| 151-200        | 3         | 2.44%   |
| 121-130        | 3         | 2.44%   |
| Unknown        | 3         | 2.44%   |
| 251-300        | 2         | 1.63%   |
| 61-70          | 1         | 0.81%   |
| 141-150        | 1         | 0.81%   |
| 501-1000       | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 36.13%  |
| 51-100        | 33        | 27.73%  |
| 101-120       | 29        | 24.37%  |
| 161-240       | 5         | 4.2%    |
| More than 240 | 3         | 2.52%   |
| 1-50          | 3         | 2.52%   |
| Unknown       | 3         | 2.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 86        | 78.18%  |
| 2     | 20        | 18.18%  |
| 0     | 3         | 2.73%   |
| 3     | 1         | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 67        | 42.41%  |
| Realtek Semiconductor             | 58        | 36.71%  |
| Qualcomm Atheros                  | 6         | 3.8%    |
| Broadcom Limited                  | 4         | 2.53%   |
| MediaTek                          | 3         | 1.9%    |
| Broadcom                          | 3         | 1.9%    |
| ASIX Electronics                  | 3         | 1.9%    |
| Samsung Electronics               | 2         | 1.27%   |
| Ralink Technology                 | 2         | 1.27%   |
| Ralink                            | 2         | 1.27%   |
| Ericsson Business Mobile Networks | 2         | 1.27%   |
| TP-Link                           | 1         | 0.63%   |
| Qualcomm Atheros Communications   | 1         | 0.63%   |
| Qualcomm                          | 1         | 0.63%   |
| NetGear                           | 1         | 0.63%   |
| Microsoft                         | 1         | 0.63%   |
| Marvell Technology Group          | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 42        | 22.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 4.21%   |
| Intel Wi-Fi 6 AX200                                                | 7         | 3.68%   |
| Intel I211 Gigabit Network Connection                              | 6         | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 5         | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                  | 5         | 2.63%   |
| Intel Wi-Fi 6 AX201                                                | 5         | 2.63%   |
| Intel Ethernet Connection (2) I219-V                               | 5         | 2.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 4         | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4         | 2.11%   |
| Intel Wireless 8265 / 8275                                         | 4         | 2.11%   |
| Intel Wireless 7260                                                | 4         | 2.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.11%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 2         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.05%   |
| Intel Wireless-AC 9260                                             | 2         | 1.05%   |
| Intel Wireless 7265                                                | 2         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                               | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 2         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.05%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.05%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 2         | 1.05%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.05%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1         | 0.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 1         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.53%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 1         | 0.53%   |
| Ralink RT2501/RT2573 Wireless Adapter                              | 1         | 0.53%   |
| Ralink MT7601U Wireless Adapter                                    | 1         | 0.53%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter             | 1         | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 60%     |
| Realtek Semiconductor           | 14        | 15.56%  |
| Qualcomm Atheros                | 5         | 5.56%   |
| Broadcom Limited                | 4         | 4.44%   |
| MediaTek                        | 3         | 3.33%   |
| Ralink Technology               | 2         | 2.22%   |
| Ralink                          | 2         | 2.22%   |
| Broadcom                        | 2         | 2.22%   |
| TP-Link                         | 1         | 1.11%   |
| Qualcomm Atheros Communications | 1         | 1.11%   |
| NetGear                         | 1         | 1.11%   |
| Microsoft                       | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 7         | 7.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 5         | 5.56%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 5.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 5         | 5.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 5.56%   |
| Intel Wireless 8265 / 8275                                                | 4         | 4.44%   |
| Intel Wireless 7260                                                       | 4         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2         | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 2.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 2.22%   |
| Intel Wireless-AC 9260                                                    | 2         | 2.22%   |
| Intel Wireless 7265                                                       | 2         | 2.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 2.22%   |
| Intel Centrino Wireless-N 2230                                            | 2         | 2.22%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 2.22%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 1.11%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.11%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 1.11%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1         | 1.11%   |
| Ralink MT7601U Wireless Adapter                                           | 1         | 1.11%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 1.11%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 1.11%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1         | 1.11%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.11%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 1.11%   |
| Intel Wireless 8260                                                       | 1         | 1.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.11%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 55.21%  |
| Intel                    | 32        | 33.33%  |
| ASIX Electronics         | 3         | 3.13%   |
| Samsung Electronics      | 2         | 2.08%   |
| Qualcomm Atheros         | 2         | 2.08%   |
| Broadcom                 | 2         | 2.08%   |
| Qualcomm                 | 1         | 1.04%   |
| Marvell Technology Group | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 42.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 8.16%   |
| Intel I211 Gigabit Network Connection                             | 6         | 6.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 5.1%    |
| Intel Ethernet Connection (2) I219-V                              | 5         | 5.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 4.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.06%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.04%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.04%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 2.04%   |
| Qualcomm Redmi 9T                                                 | 1         | 1.02%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.02%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.02%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.02%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.02%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 89        | 49.44%  |
| Ethernet | 89        | 49.44%  |
| Modem    | 2         | 1.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 61.06%  |
| Ethernet | 44        | 38.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 51.38%  |
| 1     | 48        | 44.04%  |
| 3     | 4         | 3.67%   |
| 0     | 1         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 71.82%  |
| Yes  | 31        | 28.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 55.7%   |
| Realtek Semiconductor           | 8         | 10.13%  |
| Broadcom                        | 7         | 8.86%   |
| Cambridge Silicon Radio         | 6         | 7.59%   |
| IMC Networks                    | 4         | 5.06%   |
| Qualcomm Atheros Communications | 2         | 2.53%   |
| ASUSTek Computer                | 2         | 2.53%   |
| Toshiba                         | 1         | 1.27%   |
| Realtek                         | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| Lite-On Technology              | 1         | 1.27%   |
| Dell                            | 1         | 1.27%   |
| Apple                           | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 18.99%  |
| Intel Bluetooth wireless interface                  | 9         | 11.39%  |
| Intel AX201 Bluetooth                               | 7         | 8.86%   |
| Intel AX200 Bluetooth                               | 7         | 8.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 7.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.06%   |
| Realtek Bluetooth Radio                             | 4         | 5.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.53%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.53%   |
| IMC Networks Wireless_Device                        | 2         | 2.53%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.53%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 2.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.53%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.27%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.27%   |
| MediaTek Wireless_Device                            | 1         | 1.27%   |
| Lite-On Bluetooth Device                            | 1         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.27%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.27%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.27%   |
| Broadcom BCM2045A0                                  | 1         | 1.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.27%   |
| ASUS Bluetooth Radio                                | 1         | 1.27%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 83        | 50%     |
| Nvidia                     | 33        | 19.88%  |
| AMD                        | 29        | 17.47%  |
| Corsair                    | 3         | 1.81%   |
| C-Media Electronics        | 3         | 1.81%   |
| Razer USA                  | 2         | 1.2%    |
| Kingston Technology        | 2         | 1.2%    |
| Tenx Technology            | 1         | 0.6%    |
| Samsung Electronics        | 1         | 0.6%    |
| Realtek Semiconductor      | 1         | 0.6%    |
| PreSonus Audio Electronics | 1         | 0.6%    |
| Plantronics                | 1         | 0.6%    |
| Logitech                   | 1         | 0.6%    |
| Hewlett-Packard            | 1         | 0.6%    |
| Generalplus Technology     | 1         | 0.6%    |
| Barco Display Systems      | 1         | 0.6%    |
| ASUSTek Computer           | 1         | 0.6%    |
| Astro Gaming               | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 4.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.62%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 4.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 4.62%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 3.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.08%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.08%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 3.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 2.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.05%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.54%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.03%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.03%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.03%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.03%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.03%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.03%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.51%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.51%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 25.45%  |
| SK hynix            | 27        | 24.55%  |
| Corsair             | 10        | 9.09%   |
| Micron Technology   | 9         | 8.18%   |
| Crucial             | 9         | 8.18%   |
| Kingston            | 7         | 6.36%   |
| G.Skill             | 6         | 5.45%   |
| Unknown             | 4         | 3.64%   |
| Ramaxel Technology  | 3         | 2.73%   |
| Team                | 2         | 1.82%   |
| Unifosa             | 1         | 0.91%   |
| PNY                 | 1         | 0.91%   |
| Nanya Technology    | 1         | 0.91%   |
| Elpida              | 1         | 0.91%   |
| A-DATA Technology   | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 2.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.68%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 1.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.68%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s                 | 2         | 1.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 2         | 1.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                           | 1         | 0.84%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                            | 1         | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.84%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                   | 1         | 0.84%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                  | 1         | 0.84%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s               | 1         | 0.84%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                       | 1         | 0.84%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s             | 1         | 0.84%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.84%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.84%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 1         | 0.84%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s                  | 1         | 0.84%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.84%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 0.84%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.84%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.84%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.84%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.84%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.84%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.84%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.84%   |
| SK hynix RAM HMA451R7MFR8N-TFTD 4GB DIMM DDR4 2133MT/s              | 1         | 0.84%   |
| SK hynix RAM HMA451R7MFR8N-TF 4GB DIMM DDR4 2133MT/s                | 1         | 0.84%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.84%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.84%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                           | 1         | 0.84%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                           | 1         | 0.84%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 61        | 64.89%  |
| DDR3   | 23        | 24.47%  |
| SDRAM  | 2         | 2.13%   |
| LPDDR4 | 2         | 2.13%   |
| LPDDR3 | 2         | 2.13%   |
| DDR    | 2         | 2.13%   |
| DDR5   | 1         | 1.06%   |
| DDR2   | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 55.32%  |
| DIMM         | 33        | 35.11%  |
| Row Of Chips | 9         | 9.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 44.12%  |
| 4096  | 33        | 32.35%  |
| 16384 | 18        | 17.65%  |
| 2048  | 6         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 23        | 21.7%   |
| 3200  | 18        | 16.98%  |
| 1600  | 16        | 15.09%  |
| 2400  | 7         | 6.6%    |
| 2133  | 5         | 4.72%   |
| 1333  | 5         | 4.72%   |
| 3600  | 4         | 3.77%   |
| 3266  | 3         | 2.83%   |
| 2933  | 3         | 2.83%   |
| 4267  | 2         | 1.89%   |
| 3400  | 2         | 1.89%   |
| 2176  | 2         | 1.89%   |
| 1800  | 2         | 1.89%   |
| 800   | 2         | 1.89%   |
| 4800  | 1         | 0.94%   |
| 4400  | 1         | 0.94%   |
| 4199  | 1         | 0.94%   |
| 4133  | 1         | 0.94%   |
| 3800  | 1         | 0.94%   |
| 3467  | 1         | 0.94%   |
| 2747  | 1         | 0.94%   |
| 2666  | 1         | 0.94%   |
| 1867  | 1         | 0.94%   |
| 1450  | 1         | 0.94%   |
| 1334  | 1         | 0.94%   |
| 1067  | 1         | 0.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 16        | 22.54%  |
| Chicony Electronics                    | 12        | 16.9%   |
| Acer                                   | 8         | 11.27%  |
| Realtek Semiconductor                  | 7         | 9.86%   |
| Microdia                               | 5         | 7.04%   |
| Syntek                                 | 4         | 5.63%   |
| Quanta                                 | 4         | 5.63%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.63%   |
| Sunplus Innovation Technology          | 2         | 2.82%   |
| Generalplus Technology                 | 2         | 2.82%   |
| Suyin                                  | 1         | 1.41%   |
| Sonix Technology                       | 1         | 1.41%   |
| Ricoh                                  | 1         | 1.41%   |
| Luxvisions Innotech Limited            | 1         | 1.41%   |
| Logitech                               | 1         | 1.41%   |
| Lite-On Technology                     | 1         | 1.41%   |
| Alpha Imaging Technology               | 1         | 1.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 4         | 5.63%   |
| Realtek Integrated_Webcam_HD                        | 4         | 5.63%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 5.63%   |
| Quanta HP TrueVision HD Camera                      | 3         | 4.23%   |
| IMC Networks Integrated Camera                      | 3         | 4.23%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 2.82%   |
| Chicony Integrated Camera                           | 2         | 2.82%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.82%   |
| Chicony EasyCamera                                  | 2         | 2.82%   |
| Acer ThinkPad Integrated Camera                     | 2         | 2.82%   |
| Acer HD Webcam                                      | 2         | 2.82%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.41%   |
| Sunplus HP Truevision HD                            | 1         | 1.41%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.41%   |
| Ricoh Integrated Webcam                             | 1         | 1.41%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.41%   |
| Realtek Integrated Webcam                           | 1         | 1.41%   |
| Realtek Built-In Video Camera                       | 1         | 1.41%   |
| Quanta HD User Facing                               | 1         | 1.41%   |
| Microdia Webcam Vitade AF                           | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 1.41%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.41%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.41%   |
| Logitech Webcam C600                                | 1         | 1.41%   |
| Lite-On Integrated Camera                           | 1         | 1.41%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.41%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.41%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.41%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 1         | 1.41%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.41%   |
| IMC Networks HD Camera                              | 1         | 1.41%   |
| IMC Networks EasyCamera                             | 1         | 1.41%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.41%   |
| Generalplus campark PC04                            | 1         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.41%   |
| Chicony USB2.0 UVC WebCam                           | 1         | 1.41%   |
| Chicony USB 2.0 Camera                              | 1         | 1.41%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Shenzhen Goodix Technology | 3         | 27.27%  |
| Elan Microelectronics      | 2         | 18.18%  |
| Synaptics                  | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 2         | 18.18%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 18.18%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 9.09%   |
| Elan fingerprint sensor [FeinTech FPS00200]       | 1         | 9.09%   |
| Elan ELAN:Fingerprint                             | 1         | 9.09%   |
| AuthenTec Fingerprint Sensor                      | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 28.57%  |
| Broadcom    | 2         | 28.57%  |
| Yubico.com  | 1         | 14.29%  |
| Clay Logic  | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 28.57%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 14.29%  |
| Clay Logic Nitrokey Pro                                    | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 79        | 71.82%  |
| 1     | 27        | 24.55%  |
| 2     | 4         | 3.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 31.43%  |
| Graphics card         | 8         | 22.86%  |
| Chipcard              | 5         | 14.29%  |
| Net/wireless          | 2         | 5.71%   |
| Multimedia controller | 2         | 5.71%   |
| Camera                | 2         | 5.71%   |
| Bluetooth             | 2         | 5.71%   |
| Unassigned class      | 1         | 2.86%   |
| Storage               | 1         | 2.86%   |
| Network               | 1         | 2.86%   |

