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

Total: 140

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 92        | 87.62%  |
| Xero         | 13        | 12.38%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 104       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.16.15-arch1-1   | 6         | 5.22%   |
| 5.18.16-arch1-1   | 4         | 3.48%   |
| 6.1.1-arch1-1     | 3         | 2.61%   |
| 5.17.9-arch1-1    | 3         | 2.61%   |
| 5.16.2-arch1-1    | 3         | 2.61%   |
| 5.16.1-arch1-1    | 3         | 2.61%   |
| 5.15.33-1-lts     | 3         | 2.61%   |
| 5.14.14-arch1-1   | 3         | 2.61%   |
| 6.0.7-arch1-1     | 2         | 1.74%   |
| 6.0.12-arch1-1    | 2         | 1.74%   |
| 5.19.9-arch1-1    | 2         | 1.74%   |
| 5.19.13-arch1-1   | 2         | 1.74%   |
| 5.19.12-arch1-1   | 2         | 1.74%   |
| 5.18.3-arch1-1    | 2         | 1.74%   |
| 5.18.11-arch1-1   | 2         | 1.74%   |
| 5.17.5-arch1-1    | 2         | 1.74%   |
| 5.17.1-arch1-1    | 2         | 1.74%   |
| 5.16.8-arch1-1    | 2         | 1.74%   |
| 5.16.16-arch1-1   | 2         | 1.74%   |
| 5.16.13-arch1-1   | 2         | 1.74%   |
| 5.16.12-arch1-1   | 2         | 1.74%   |
| 5.15.10-arch1-1   | 2         | 1.74%   |
| 5.14.8-zen1-1-zen | 2         | 1.74%   |
| 6.1.8-arch1-1     | 1         | 0.87%   |
| 6.1.7-arch1-1     | 1         | 0.87%   |
| 6.1.6-arch1-3     | 1         | 0.87%   |
| 6.1.6-arch1-1     | 1         | 0.87%   |
| 6.1.4-arch1-1     | 1         | 0.87%   |
| 6.1.3-zen1-1-zen  | 1         | 0.87%   |
| 6.0.9-arch1-1     | 1         | 0.87%   |
| 6.0.8-zen1-1-zen  | 1         | 0.87%   |
| 6.0.8-arch1-1     | 1         | 0.87%   |
| 6.0.6-zen1-1-zen  | 1         | 0.87%   |
| 6.0.6-arch1-1     | 1         | 0.87%   |
| 6.0.2-zen1-1-zen  | 1         | 0.87%   |
| 6.0.2-arch1-1     | 1         | 0.87%   |
| 6.0.11-arch1-1    | 1         | 0.87%   |
| 6.0.1-arch2-1     | 1         | 0.87%   |
| 5.19.3-arch1-1    | 1         | 0.87%   |
| 5.19.2-zen1-1-zen | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 5.22%   |
| 5.18.16 | 4         | 3.48%   |
| 5.14.14 | 4         | 3.48%   |
| 6.1.1   | 3         | 2.61%   |
| 5.19.13 | 3         | 2.61%   |
| 5.17.9  | 3         | 2.61%   |
| 5.16.2  | 3         | 2.61%   |
| 5.16.16 | 3         | 2.61%   |
| 5.16.1  | 3         | 2.61%   |
| 5.15.33 | 3         | 2.61%   |
| 5.15.12 | 3         | 2.61%   |
| 5.14.8  | 3         | 2.61%   |
| 5.14.16 | 3         | 2.61%   |
| 6.1.6   | 2         | 1.74%   |
| 6.0.8   | 2         | 1.74%   |
| 6.0.7   | 2         | 1.74%   |
| 6.0.6   | 2         | 1.74%   |
| 6.0.2   | 2         | 1.74%   |
| 6.0.12  | 2         | 1.74%   |
| 5.19.9  | 2         | 1.74%   |
| 5.19.12 | 2         | 1.74%   |
| 5.18.3  | 2         | 1.74%   |
| 5.18.11 | 2         | 1.74%   |
| 5.17.5  | 2         | 1.74%   |
| 5.17.1  | 2         | 1.74%   |
| 5.16.8  | 2         | 1.74%   |
| 5.16.13 | 2         | 1.74%   |
| 5.16.12 | 2         | 1.74%   |
| 5.15.13 | 2         | 1.74%   |
| 5.15.11 | 2         | 1.74%   |
| 5.15.10 | 2         | 1.74%   |
| 6.1.8   | 1         | 0.87%   |
| 6.1.7   | 1         | 0.87%   |
| 6.1.4   | 1         | 0.87%   |
| 6.1.3   | 1         | 0.87%   |
| 6.0.9   | 1         | 0.87%   |
| 6.0.11  | 1         | 0.87%   |
| 6.0.1   | 1         | 0.87%   |
| 5.19.3  | 1         | 0.87%   |
| 5.19.2  | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 20.54%  |
| 5.15    | 18        | 16.07%  |
| 6.0     | 13        | 11.61%  |
| 5.14    | 13        | 11.61%  |
| 5.19    | 11        | 9.82%   |
| 5.18    | 11        | 9.82%   |
| 6.1     | 8         | 7.14%   |
| 5.17    | 8         | 7.14%   |
| 5.10    | 3         | 2.68%   |
| 5.13    | 2         | 1.79%   |
| 5.12    | 1         | 0.89%   |
| 5.11    | 1         | 0.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 97        | 91.51%  |
| XFCE   | 4         | 3.77%   |
| GNOME  | 3         | 2.83%   |
| LeftWM | 1         | 0.94%   |
| KDE    | 1         | 0.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 91        | 86.67%  |
| Wayland | 12        | 11.43%  |
| Tty     | 2         | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 72        | 66.67%  |
| Unknown | 18        | 16.67%  |
| LightDM | 15        | 13.89%  |
| GDM     | 2         | 1.85%   |
| TDM     | 1         | 0.93%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 56        | 53.33%  |
| en_IN | 8         | 7.62%   |
| en_GB | 6         | 5.71%   |
| de_DE | 5         | 4.76%   |
| C     | 5         | 4.76%   |
| pl_PL | 4         | 3.81%   |
| ru_RU | 3         | 2.86%   |
| it_IT | 3         | 2.86%   |
| es_MX | 3         | 2.86%   |
| en_AU | 3         | 2.86%   |
| fr_FR | 2         | 1.9%    |
| vi_VN | 1         | 0.95%   |
| en_IL | 1         | 0.95%   |
| en_DK | 1         | 0.95%   |
| en_CA | 1         | 0.95%   |
| en_AG | 1         | 0.95%   |
| de_AT | 1         | 0.95%   |
| ba_RU | 1         | 0.95%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 68        | 64.76%  |
| BIOS | 37        | 35.24%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 57        | 53.77%  |
| Xfs     | 24        | 22.64%  |
| Ext4    | 19        | 17.92%  |
| Overlay | 6         | 5.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 73        | 69.52%  |
| Unknown | 18        | 17.14%  |
| MBR     | 14        | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 75.23%  |
| Yes       | 27        | 24.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 63.81%  |
| Yes       | 38        | 36.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 30        | 28.85%  |
| Lenovo              | 19        | 18.27%  |
| Hewlett-Packard     | 14        | 13.46%  |
| Dell                | 13        | 12.5%   |
| MSI                 | 6         | 5.77%   |
| Gigabyte Technology | 4         | 3.85%   |
| Acer                | 4         | 3.85%   |
| Pegatron            | 3         | 2.88%   |
| ASRock              | 3         | 2.88%   |
| HUAWEI              | 2         | 1.92%   |
| Toshiba             | 1         | 0.96%   |
| Medion              | 1         | 0.96%   |
| BESSTAR Tech        | 1         | 0.96%   |
| Aquarius            | 1         | 0.96%   |
| Apple               | 1         | 0.96%   |
| Unknown             | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 2.88%   |
| MSI MS-7971                                | 2         | 1.92%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 1.92%   |
| Toshiba TECRA A11                          | 1         | 0.96%   |
| Pegatron p6-2026                           | 1         | 0.96%   |
| Pegatron D15K                              | 1         | 0.96%   |
| Pegatron 20-b010                           | 1         | 0.96%   |
| MSI MS-7B61                                | 1         | 0.96%   |
| MSI Katana GF66 11UE                       | 1         | 0.96%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.96%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.96%   |
| Medion P6816                               | 1         | 0.96%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 0.96%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.96%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 0.96%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.96%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.96%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.96%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 0.96%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 0.96%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 0.96%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 0.96%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 0.96%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.96%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 0.96%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.96%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 0.96%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 0.96%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 0.96%   |
| Lenovo IdeaPad 3 14IGL05 81WH              | 1         | 0.96%   |
| HUAWEI WRT-WX9                             | 1         | 0.96%   |
| HUAWEI BOM-WXX9                            | 1         | 0.96%   |
| HP ZBook 15 G4                             | 1         | 0.96%   |
| HP Z230 SFF Workstation                    | 1         | 0.96%   |
| HP ProOne 400 G1 AiO                       | 1         | 0.96%   |
| HP ProBook 6565b                           | 1         | 0.96%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 1         | 0.96%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 0.96%   |
| HP Notebook                                | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 8         | 7.69%   |
| ASUS ROG             | 7         | 6.73%   |
| Lenovo IdeaPad       | 6         | 5.77%   |
| ASUS TUF             | 5         | 4.81%   |
| Dell Precision       | 4         | 3.85%   |
| Dell Latitude        | 4         | 3.85%   |
| ASUS VivoBook        | 4         | 3.85%   |
| Acer Aspire          | 4         | 3.85%   |
| Lenovo Legion        | 3         | 2.88%   |
| HP Laptop            | 3         | 2.88%   |
| ASUS ASUS            | 3         | 2.88%   |
| MSI MS-7971          | 2         | 1.92%   |
| HP Pavilion          | 2         | 1.92%   |
| Dell Inspiron        | 2         | 1.92%   |
| ASUS PRIME           | 2         | 1.92%   |
| Toshiba TECRA        | 1         | 0.96%   |
| Pegatron p6-2026     | 1         | 0.96%   |
| Pegatron D15K        | 1         | 0.96%   |
| Pegatron 20-b010     | 1         | 0.96%   |
| MSI MS-7B61          | 1         | 0.96%   |
| MSI Katana           | 1         | 0.96%   |
| MSI GP73             | 1         | 0.96%   |
| MSI GF63             | 1         | 0.96%   |
| Medion P6816         | 1         | 0.96%   |
| Lenovo Yoga          | 1         | 0.96%   |
| Lenovo Y520-15IKBN   | 1         | 0.96%   |
| HUAWEI WRT-WX9       | 1         | 0.96%   |
| HUAWEI BOM-WXX9      | 1         | 0.96%   |
| HP ZBook             | 1         | 0.96%   |
| HP Z230              | 1         | 0.96%   |
| HP ProOne            | 1         | 0.96%   |
| HP ProBook           | 1         | 0.96%   |
| HP Notebook          | 1         | 0.96%   |
| HP ENVY              | 1         | 0.96%   |
| HP Compaq            | 1         | 0.96%   |
| HP 750-424           | 1         | 0.96%   |
| HP 245               | 1         | 0.96%   |
| Gigabyte Z170X-UD3   | 1         | 0.96%   |
| Gigabyte X570        | 1         | 0.96%   |
| Gigabyte B460MDS3HV2 | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 20        | 19.23%  |
| 2020 | 13        | 12.5%   |
| 2018 | 11        | 10.58%  |
| 2017 | 11        | 10.58%  |
| 2021 | 10        | 9.62%   |
| 2012 | 9         | 8.65%   |
| 2015 | 6         | 5.77%   |
| 2013 | 6         | 5.77%   |
| 2011 | 4         | 3.85%   |
| 2016 | 3         | 2.88%   |
| 2014 | 3         | 2.88%   |
| 2010 | 3         | 2.88%   |
| 2022 | 2         | 1.92%   |
| 2009 | 2         | 1.92%   |
| 2008 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 63        | 60.58%  |
| Desktop     | 37        | 35.58%  |
| Convertible | 3         | 2.88%   |
| Server      | 1         | 0.96%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 104       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 27.88%  |
| 16.01-24.0  | 25        | 24.04%  |
| 8.01-16.0   | 20        | 19.23%  |
| 3.01-4.0    | 13        | 12.5%   |
| 32.01-64.0  | 12        | 11.54%  |
| 24.01-32.0  | 3         | 2.88%   |
| 64.01-256.0 | 2         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 37        | 32.74%  |
| 1.01-2.0   | 27        | 23.89%  |
| 4.01-8.0   | 21        | 18.58%  |
| 3.01-4.0   | 15        | 13.27%  |
| 8.01-16.0  | 5         | 4.42%   |
| 16.01-24.0 | 4         | 3.54%   |
| 0.51-1.0   | 2         | 1.77%   |
| 0.01-0.5   | 2         | 1.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 55.24%  |
| 2      | 27        | 25.71%  |
| 3      | 10        | 9.52%   |
| 4      | 5         | 4.76%   |
| 6      | 2         | 1.9%    |
| 5      | 2         | 1.9%    |
| 7      | 1         | 0.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 80        | 76.19%  |
| Yes       | 25        | 23.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 80.77%  |
| No        | 20        | 19.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 82.69%  |
| No        | 18        | 17.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 74.29%  |
| No        | 27        | 25.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 23        | 21.9%   |
| India                  | 10        | 9.52%   |
| Germany                | 8         | 7.62%   |
| Poland                 | 5         | 4.76%   |
| Russia                 | 4         | 3.81%   |
| Italy                  | 4         | 3.81%   |
| France                 | 4         | 3.81%   |
| UK                     | 3         | 2.86%   |
| Mexico                 | 3         | 2.86%   |
| Greece                 | 3         | 2.86%   |
| Australia              | 3         | 2.86%   |
| Turkey                 | 2         | 1.9%    |
| Sweden                 | 2         | 1.9%    |
| Pakistan               | 2         | 1.9%    |
| Norway                 | 2         | 1.9%    |
| Netherlands            | 2         | 1.9%    |
| Lebanon                | 2         | 1.9%    |
| Canada                 | 2         | 1.9%    |
| Zambia                 | 1         | 0.95%   |
| Vietnam                | 1         | 0.95%   |
| Togo                   | 1         | 0.95%   |
| Spain                  | 1         | 0.95%   |
| Romania                | 1         | 0.95%   |
| Portugal               | 1         | 0.95%   |
| Palestinian Territory  | 1         | 0.95%   |
| Morocco                | 1         | 0.95%   |
| Mongolia               | 1         | 0.95%   |
| Malaysia               | 1         | 0.95%   |
| Israel                 | 1         | 0.95%   |
| Indonesia              | 1         | 0.95%   |
| Hungary                | 1         | 0.95%   |
| Denmark                | 1         | 0.95%   |
| Cyprus                 | 1         | 0.95%   |
| Colombia               | 1         | 0.95%   |
| Chile                  | 1         | 0.95%   |
| Brazil                 | 1         | 0.95%   |
| Bosnia and Herzegovina | 1         | 0.95%   |
| Austria                | 1         | 0.95%   |
| Argentina              | 1         | 0.95%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Longmont       | 3         | 2.86%   |
| Madurai        | 2         | 1.9%    |
| Istanbul       | 2         | 1.9%    |
| Bremen         | 2         | 1.9%    |
| Beirut         | 2         | 1.9%    |
| Zenica         | 1         | 0.95%   |
| Zell am See    | 1         | 0.95%   |
| Wroclaw        | 1         | 0.95%   |
| Wrexham        | 1         | 0.95%   |
| Wells          | 1         | 0.95%   |
| Warsaw         | 1         | 0.95%   |
| Ulan Bator     | 1         | 0.95%   |
| Ufa            | 1         | 0.95%   |
| Toronto        | 1         | 0.95%   |
| Tel Aviv       | 1         | 0.95%   |
| Taranto        | 1         | 0.95%   |
| Tangerang      | 1         | 0.95%   |
| Stuttgart      | 1         | 0.95%   |
| Stow           | 1         | 0.95%   |
| Stockholm      | 1         | 0.95%   |
| Stavropol      | 1         | 0.95%   |
| Springfield    | 1         | 0.95%   |
| Sonora         | 1         | 0.95%   |
| Silkeborg      | 1         | 0.95%   |
| Shadrinsk      | 1         | 0.95%   |
| Seattle        | 1         | 0.95%   |
| Santa Cruz     | 1         | 0.95%   |
| Salt Lake City | 1         | 0.95%   |
| Ramallah       | 1         | 0.95%   |
| Pune           | 1         | 0.95%   |
| Poznan         | 1         | 0.95%   |
| Portland       | 1         | 0.95%   |
| Porcia         | 1         | 0.95%   |
| Pirmasens      | 1         | 0.95%   |
| Phoenix        | 1         | 0.95%   |
| Perth          | 1         | 0.95%   |
| Pavia          | 1         | 0.95%   |
| Passos         | 1         | 0.95%   |
| Paris          | 1         | 0.95%   |
| Oslo           | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 31        | 45     | 18.02%  |
| Samsung Electronics         | 30        | 42     | 17.44%  |
| WDC                         | 24        | 33     | 13.95%  |
| Kingston                    | 12        | 16     | 6.98%   |
| Toshiba                     | 9         | 11     | 5.23%   |
| Sandisk                     | 7         | 9      | 4.07%   |
| Intel                       | 7         | 9      | 4.07%   |
| HGST                        | 6         | 6      | 3.49%   |
| Unknown                     | 5         | 6      | 2.91%   |
| Micron Technology           | 4         | 6      | 2.33%   |
| China                       | 4         | 4      | 2.33%   |
| Phison                      | 3         | 3      | 1.74%   |
| Hitachi                     | 3         | 3      | 1.74%   |
| Transcend                   | 2         | 2      | 1.16%   |
| LITEON                      | 2         | 2      | 1.16%   |
| KIOXIA                      | 2         | 3      | 1.16%   |
| Crucial                     | 2         | 2      | 1.16%   |
| XPG                         | 1         | 1      | 0.58%   |
| Vaseky                      | 1         | 1      | 0.58%   |
| SK hynix                    | 1         | 1      | 0.58%   |
| Silicon Motion              | 1         | 1      | 0.58%   |
| Realtek Semiconductor       | 1         | 1      | 0.58%   |
| PNY                         | 1         | 1      | 0.58%   |
| Plextor                     | 1         | 1      | 0.58%   |
| OSCOO                       | 1         | 1      | 0.58%   |
| Micron/Crucial Technology   | 1         | 1      | 0.58%   |
| LITEONIT                    | 1         | 1      | 0.58%   |
| Kingston Technology Company | 1         | 1      | 0.58%   |
| Intenso                     | 1         | 1      | 0.58%   |
| Inateck                     | 1         | 1      | 0.58%   |
| GOODRAM                     | 1         | 1      | 0.58%   |
| Biostar                     | 1         | 1      | 0.58%   |
| Apple                       | 1         | 1      | 0.58%   |
| Apacer                      | 1         | 1      | 0.58%   |
| A-DATA Technology           | 1         | 1      | 0.58%   |
| 2-Power                     | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.55%   |
| Seagate One Touch HDD 5TB                           | 3         | 1.55%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.55%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 2         | 1.03%   |
| Unknown MMC Card  64GB                              | 2         | 1.03%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.03%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 1.03%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 1.03%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 1.03%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 1.03%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 1.03%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 1.03%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 1.03%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 1.03%   |
| HGST HTS545050A7E680 500GB                          | 2         | 1.03%   |
| China SSD 1TB                                       | 2         | 1.03%   |
| XPG GAMMIX S50 1TB                                  | 1         | 0.52%   |
| WDC WDS512G1X0C-00ENX0 512GB                        | 1         | 0.52%   |
| WDC WDS500G3XHC-00SJG0 500GB                        | 1         | 0.52%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.52%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.52%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.52%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.52%   |
| WDC WD800JD-00MSA1 80GB                             | 1         | 0.52%   |
| WDC WD7500BPKT-75PK4T0 752GB                        | 1         | 0.52%   |
| WDC WD6400AAKS-22A7B2 640GB                         | 1         | 0.52%   |
| WDC WD5000AAVS-00ZTB0 500GB                         | 1         | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 1         | 0.52%   |
| WDC WD40EZRZ-22GXCB0 4TB                            | 1         | 0.52%   |
| WDC WD2500BEVT-60ZCT1 250GB                         | 1         | 0.52%   |
| WDC WD20EZRZ-60Z5HB0 2TB                            | 1         | 0.52%   |
| WDC WD20EZBX-00AYRA0 2TB                            | 1         | 0.52%   |
| WDC WD2003FZEX-00SRLA0 2TB                          | 1         | 0.52%   |
| WDC WD15EADS-11R6B1 1TB                             | 1         | 0.52%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.52%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 1         | 0.52%   |
| WDC WD10EZEX-00KUWA0 1TB                            | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 44     | 48.44%  |
| WDC                 | 15        | 21     | 23.44%  |
| Toshiba             | 6         | 8      | 9.38%   |
| HGST                | 6         | 6      | 9.38%   |
| Hitachi             | 3         | 3      | 4.69%   |
| Samsung Electronics | 2         | 2      | 3.13%   |
| Unknown             | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 26%     |
| Kingston            | 8         | 11     | 16%     |
| China               | 4         | 4      | 8%      |
| WDC                 | 3         | 3      | 6%      |
| SanDisk             | 3         | 3      | 6%      |
| Transcend           | 2         | 2      | 4%      |
| LITEON              | 2         | 2      | 4%      |
| Crucial             | 2         | 2      | 4%      |
| Vaseky              | 1         | 1      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| Plextor             | 1         | 1      | 2%      |
| OSCOO               | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| LITEONIT            | 1         | 1      | 2%      |
| Intenso             | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| GOODRAM             | 1         | 1      | 2%      |
| Biostar             | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |
| Apacer              | 1         | 1      | 2%      |
| 2-Power             | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 85     | 35.1%   |
| NVMe | 52        | 75     | 34.44%  |
| SSD  | 42        | 56     | 27.81%  |
| MMC  | 4         | 5      | 2.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 132    | 52.55%  |
| NVMe | 52        | 74     | 37.96%  |
| SAS  | 9         | 10     | 6.57%   |
| MMC  | 4         | 5      | 2.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 67     | 44.66%  |
| 0.51-1.0   | 39        | 50     | 37.86%  |
| 1.01-2.0   | 8         | 11     | 7.77%   |
| 4.01-10.0  | 8         | 11     | 7.77%   |
| 3.01-4.0   | 1         | 1      | 0.97%   |
| 2.01-3.0   | 1         | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 27        | 24.77%  |
| 1001-2000      | 21        | 19.27%  |
| 251-500        | 15        | 13.76%  |
| 501-1000       | 13        | 11.93%  |
| 101-250        | 10        | 9.17%   |
| Unknown        | 8         | 7.34%   |
| 51-100         | 6         | 5.5%    |
| 1-20           | 4         | 3.67%   |
| 21-50          | 3         | 2.75%   |
| 2001-3000      | 2         | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 22.94%  |
| 1-20           | 22        | 20.18%  |
| 51-100         | 17        | 15.6%   |
| 251-500        | 10        | 9.17%   |
| 21-50          | 9         | 8.26%   |
| Unknown        | 8         | 7.34%   |
| 501-1000       | 7         | 6.42%   |
| 2001-3000      | 5         | 4.59%   |
| More than 3000 | 3         | 2.75%   |
| 1001-2000      | 3         | 2.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 4.76%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 1         | 2      | 4.76%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 4.76%   |
| Toshiba MK4058GSX 400GB                                         | 1         | 1      | 4.76%   |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 4.76%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 4.76%   |
| Seagate ST31000524AS 1TB                                        | 1         | 1      | 4.76%   |
| Seagate ST2000VX000-1CU164 2TB                                  | 1         | 1      | 4.76%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 1         | 1      | 4.76%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 4.76%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 4.76%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 4.76%   |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 4.76%   |
| Kingston SUV400S37240G 240GB SSD                                | 1         | 1      | 4.76%   |
| Hitachi HTS725050A9A364 500GB                                   | 1         | 1      | 4.76%   |
| Hitachi HCP725050GLA380 500GB                                   | 1         | 1      | 4.76%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 4.76%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 4.76%   |
| China SATA3 240GB SSD                                           | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 40%     |
| WDC                 | 2         | 3      | 10%     |
| Toshiba             | 2         | 3      | 10%     |
| Kingston            | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| HGST                | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |
| China               | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 50%     |
| WDC     | 2         | 3      | 12.5%   |
| Toshiba | 2         | 3      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| HGST    | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 78.95%  |
| SSD  | 3         | 3      | 15.79%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Works    | 80        | 142    | 65.04%  |
| Detected | 25        | 57     | 20.33%  |
| Malfunc  | 18        | 22     | 14.63%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 76        | 51.01%  |
| AMD                          | 20        | 13.42%  |
| Samsung Electronics          | 17        | 11.41%  |
| SanDisk                      | 11        | 7.38%   |
| Kingston Technology Company  | 5         | 3.36%   |
| Micron Technology            | 4         | 2.68%   |
| Toshiba America Info Systems | 3         | 2.01%   |
| Phison Electronics           | 3         | 2.01%   |
| Realtek Semiconductor        | 2         | 1.34%   |
| KIOXIA                       | 2         | 1.34%   |
| SK hynix                     | 1         | 0.67%   |
| Silicon Motion               | 1         | 0.67%   |
| Seagate Technology           | 1         | 0.67%   |
| Micron/Crucial Technology    | 1         | 0.67%   |
| ASMedia Technology           | 1         | 0.67%   |
| ADATA Technology             | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 11.8%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 3.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 3.11%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.11%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 3.11%   |
| Micron Non-Volatile memory controller                                          | 4         | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 2.48%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.48%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 1.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.86%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.86%   |
| Intel SSD 660P Series                                                          | 3         | 1.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.86%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.24%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.24%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.24%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.24%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.24%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.24%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.24%   |
| AMD FCH SATA Controller D                                                      | 2         | 1.24%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.24%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.62%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.62%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.62%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.62%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.62%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 80        | 54.05%  |
| NVMe | 52        | 35.14%  |
| RAID | 16        | 10.81%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 80        | 76.92%  |
| AMD    | 24        | 23.08%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 3.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 2.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 2.86%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 2.86%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 2.86%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 1.9%    |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 1.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 1.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 1.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 1.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 1.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.9%    |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 1.9%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.9%    |
| AMD Ryzen 7 5800X 8-Core Processor      | 2         | 1.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 1.9%    |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 1.9%    |
| Intel Genuine CPU 0000 @ 2.10GHz        | 1         | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 0.95%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.95%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 1         | 0.95%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 0.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 0.95%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.95%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 0.95%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 1         | 0.95%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 0.95%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 0.95%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 0.95%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 0.95%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 0.95%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 0.95%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 0.95%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 1         | 0.95%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 0.95%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1         | 0.95%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 0.95%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1         | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 30        | 28.57%  |
| Intel Core i7     | 28        | 26.67%  |
| AMD Ryzen 5       | 10        | 9.52%   |
| Other             | 9         | 8.57%   |
| AMD Ryzen 7       | 8         | 7.62%   |
| Intel Core i3     | 7         | 6.67%   |
| Intel Celeron     | 3         | 2.86%   |
| Intel Genuine     | 1         | 0.95%   |
| Intel Core 2 Quad | 1         | 0.95%   |
| Intel Core 2 Duo  | 1         | 0.95%   |
| AMD Ryzen 9       | 1         | 0.95%   |
| AMD Ryzen 3       | 1         | 0.95%   |
| AMD E1            | 1         | 0.95%   |
| AMD Athlon        | 1         | 0.95%   |
| AMD A8            | 1         | 0.95%   |
| AMD A6            | 1         | 0.95%   |
| AMD A4            | 1         | 0.95%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 45        | 42.86%  |
| 2      | 32        | 30.48%  |
| 6      | 16        | 15.24%  |
| 8      | 10        | 9.52%   |
| 14     | 1         | 0.95%   |
| 12     | 1         | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 84        | 80%     |
| 1      | 21        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 104       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 20.37%  |
| 0x806c1    | 7         | 6.48%   |
| 0x906ea    | 6         | 5.56%   |
| 0x306a9    | 6         | 5.56%   |
| 0x806ec    | 5         | 4.63%   |
| 0x806e9    | 5         | 4.63%   |
| 0x506e3    | 5         | 4.63%   |
| 0x08701021 | 4         | 3.7%    |
| 0x906e9    | 3         | 2.78%   |
| 0x806eb    | 3         | 2.78%   |
| 0x306c3    | 3         | 2.78%   |
| 0x206a7    | 3         | 2.78%   |
| 0x0a201016 | 3         | 2.78%   |
| 0x08108109 | 3         | 2.78%   |
| 0x906ed    | 2         | 1.85%   |
| 0x906eb    | 2         | 1.85%   |
| 0x706a8    | 2         | 1.85%   |
| 0x40651    | 2         | 1.85%   |
| 0x1067a    | 2         | 1.85%   |
| 0xa0653    | 1         | 0.93%   |
| 0xa0652    | 1         | 0.93%   |
| 0x906a3    | 1         | 0.93%   |
| 0x806d1    | 1         | 0.93%   |
| 0x706e5    | 1         | 0.93%   |
| 0x406e3    | 1         | 0.93%   |
| 0x306d4    | 1         | 0.93%   |
| 0x20655    | 1         | 0.93%   |
| 0x20652    | 1         | 0.93%   |
| 0x106e5    | 1         | 0.93%   |
| 0x0a50000b | 1         | 0.93%   |
| 0x0a20120a | 1         | 0.93%   |
| 0x08701013 | 1         | 0.93%   |
| 0x08608103 | 1         | 0.93%   |
| 0x08600106 | 1         | 0.93%   |
| 0x0810100b | 1         | 0.93%   |
| 0x06006705 | 1         | 0.93%   |
| 0x0600611a | 1         | 0.93%   |
| 0x0500010d | 1         | 0.93%   |
| 0x03000027 | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 28.57%  |
| Zen 2            | 9         | 8.57%   |
| Haswell          | 9         | 8.57%   |
| IvyBridge        | 8         | 7.62%   |
| TigerLake        | 7         | 6.67%   |
| Skylake          | 6         | 5.71%   |
| Zen+             | 5         | 4.76%   |
| Zen 3            | 5         | 4.76%   |
| SandyBridge      | 4         | 3.81%   |
| Goldmont plus    | 3         | 2.86%   |
| Westmere         | 2         | 1.9%    |
| Penryn           | 2         | 1.9%    |
| Nehalem          | 2         | 1.9%    |
| IceLake          | 2         | 1.9%    |
| Excavator        | 2         | 1.9%    |
| CometLake        | 2         | 1.9%    |
| Broadwell        | 2         | 1.9%    |
| Zen              | 1         | 0.95%   |
| K10 Llano        | 1         | 0.95%   |
| Bobcat           | 1         | 0.95%   |
| Alderlake Hybrid | 1         | 0.95%   |
| Unknown          | 1         | 0.95%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 64        | 45.71%  |
| Nvidia | 51        | 36.43%  |
| AMD    | 25        | 17.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 4.26%   |
| Intel HD Graphics 620                                                     | 5         | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 2.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.84%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 2.13%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 3         | 2.13%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.13%   |
| Intel UHD Graphics 620                                                    | 3         | 2.13%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 3         | 2.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.42%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 2         | 1.42%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 1.42%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 1.42%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.42%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.42%   |
| Intel HD Graphics 630                                                     | 2         | 1.42%   |
| Intel HD Graphics 5500                                                    | 2         | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.42%   |
| AMD Renoir                                                                | 2         | 1.42%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2         | 1.42%   |
| Nvidia TU117M                                                             | 1         | 0.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.71%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 30        | 28.85%  |
| Intel + Nvidia | 29        | 27.88%  |
| 1 x AMD        | 19        | 18.27%  |
| 1 x Nvidia     | 18        | 17.31%  |
| Intel + AMD    | 3         | 2.88%   |
| AMD + Nvidia   | 3         | 2.88%   |
| 2 x Nvidia     | 1         | 0.96%   |
| 2 x Intel      | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 67        | 63.81%  |
| Proprietary | 36        | 34.29%  |
| Unknown     | 2         | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 59.05%  |
| 1.01-2.0   | 15        | 14.29%  |
| 5.01-6.0   | 7         | 6.67%   |
| 0.01-0.5   | 7         | 6.67%   |
| 7.01-8.0   | 6         | 5.71%   |
| 3.01-4.0   | 4         | 3.81%   |
| 8.01-16.0  | 3         | 2.86%   |
| 0.51-1.0   | 1         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 19        | 15.83%  |
| AU Optronics         | 18        | 15%     |
| Chimei Innolux       | 12        | 10%     |
| BOE                  | 12        | 10%     |
| LG Display           | 10        | 8.33%   |
| Goldstar             | 5         | 4.17%   |
| Ancor Communications | 5         | 4.17%   |
| Acer                 | 5         | 4.17%   |
| Dell                 | 4         | 3.33%   |
| Sharp                | 3         | 2.5%    |
| Hewlett-Packard      | 3         | 2.5%    |
| AOC                  | 3         | 2.5%    |
| PANDA                | 2         | 1.67%   |
| Iiyama               | 2         | 1.67%   |
| Apple                | 2         | 1.67%   |
| TMX                  | 1         | 0.83%   |
| Sceptre Tech         | 1         | 0.83%   |
| MSI                  | 1         | 0.83%   |
| LGD                  | 1         | 0.83%   |
| Lenovo               | 1         | 0.83%   |
| Kogan                | 1         | 0.83%   |
| KOC                  | 1         | 0.83%   |
| JRY                  | 1         | 0.83%   |
| Idek Iiyama          | 1         | 0.83%   |
| Hitachi              | 1         | 0.83%   |
| Gigabyte Technology  | 1         | 0.83%   |
| FOX                  | 1         | 0.83%   |
| CSO                  | 1         | 0.83%   |
| BenQ                 | 1         | 0.83%   |
| ASUSTek Computer     | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.44%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 1.63%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch   | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.63%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.81%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.81%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.81%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.81%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 0.81%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.81%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1         | 0.81%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.81%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch       | 1         | 0.81%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.81%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 0.81%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 0.81%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1         | 0.81%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.81%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.81%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                         | 1         | 0.81%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.81%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD0561 1920x1080 294x165mm 13.3-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.81%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 0.81%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 55.26%  |
| 1366x768 (WXGA)    | 16        | 14.04%  |
| 3840x2160 (4K)     | 8         | 7.02%   |
| 2560x1440 (QHD)    | 6         | 5.26%   |
| 3440x1440          | 5         | 4.39%   |
| 1600x900 (HD+)     | 4         | 3.51%   |
| 2560x1080          | 3         | 2.63%   |
| 3840x2400          | 1         | 0.88%   |
| 3840x1080          | 1         | 0.88%   |
| 3200x1800 (QHD+)   | 1         | 0.88%   |
| 2160x1440          | 1         | 0.88%   |
| 1920x540           | 1         | 0.88%   |
| 1920x1200 (WUXGA)  | 1         | 0.88%   |
| 1680x1050 (WSXGA+) | 1         | 0.88%   |
| 1440x900 (WXGA+)   | 1         | 0.88%   |
| 1280x1024 (SXGA)   | 1         | 0.88%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 33.33%  |
| 27      | 11        | 9.17%   |
| 23      | 10        | 8.33%   |
| 14      | 10        | 8.33%   |
| 13      | 9         | 7.5%    |
| 21      | 7         | 5.83%   |
| 34      | 6         | 5%      |
| 84      | 4         | 3.33%   |
| 31      | 4         | 3.33%   |
| 24      | 4         | 3.33%   |
| 17      | 3         | 2.5%    |
| Unknown | 3         | 2.5%    |
| 28      | 2         | 1.67%   |
| 20      | 2         | 1.67%   |
| 18      | 2         | 1.67%   |
| 54      | 1         | 0.83%   |
| 48      | 1         | 0.83%   |
| 12      | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 45.83%  |
| 501-600     | 24        | 20%     |
| 401-500     | 11        | 9.17%   |
| 701-800     | 6         | 5%      |
| 601-700     | 6         | 5%      |
| 201-300     | 5         | 4.17%   |
| 351-400     | 4         | 3.33%   |
| 1501-2000   | 4         | 3.33%   |
| Unknown     | 3         | 2.5%    |
| 1001-1500   | 2         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 84.11%  |
| 21/9    | 8         | 7.48%   |
| 16/10   | 4         | 3.74%   |
| Unknown | 2         | 1.87%   |
| 5/4     | 1         | 0.93%   |
| 32/9    | 1         | 0.93%   |
| 3/2     | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 33.61%  |
| 201-250        | 20        | 16.81%  |
| 81-90          | 16        | 13.45%  |
| 301-350        | 11        | 9.24%   |
| 351-500        | 10        | 8.4%    |
| More than 1000 | 5         | 4.2%    |
| 71-80          | 3         | 2.52%   |
| 151-200        | 3         | 2.52%   |
| 121-130        | 3         | 2.52%   |
| Unknown        | 3         | 2.52%   |
| 251-300        | 2         | 1.68%   |
| 61-70          | 1         | 0.84%   |
| 141-150        | 1         | 0.84%   |
| 501-1000       | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 36.52%  |
| 51-100        | 31        | 26.96%  |
| 101-120       | 29        | 25.22%  |
| 161-240       | 5         | 4.35%   |
| More than 240 | 3         | 2.61%   |
| Unknown       | 3         | 2.61%   |
| 1-50          | 2         | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 78.3%   |
| 2     | 20        | 18.87%  |
| 0     | 2         | 1.89%   |
| 3     | 1         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 43.71%  |
| Realtek Semiconductor             | 55        | 36.42%  |
| Qualcomm Atheros                  | 6         | 3.97%   |
| Broadcom Limited                  | 4         | 2.65%   |
| MediaTek                          | 3         | 1.99%   |
| ASIX Electronics                  | 3         | 1.99%   |
| Samsung Electronics               | 2         | 1.32%   |
| Ralink                            | 2         | 1.32%   |
| Ericsson Business Mobile Networks | 2         | 1.32%   |
| Broadcom                          | 2         | 1.32%   |
| TP-Link                           | 1         | 0.66%   |
| Ralink Technology                 | 1         | 0.66%   |
| Qualcomm                          | 1         | 0.66%   |
| NetGear                           | 1         | 0.66%   |
| Microsoft                         | 1         | 0.66%   |
| Marvell Technology Group          | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 40        | 22.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 4.42%   |
| Intel Wi-Fi 6 AX200                                                | 7         | 3.87%   |
| Intel I211 Gigabit Network Connection                              | 6         | 3.31%   |
| Intel Wi-Fi 6 AX201                                                | 5         | 2.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 2.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 4         | 2.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 4         | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                  | 4         | 2.21%   |
| Intel Wireless 8265 / 8275                                         | 4         | 2.21%   |
| Intel Wireless 7260                                                | 4         | 2.21%   |
| Intel Ethernet Connection (2) I219-V                               | 4         | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 3         | 1.66%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 2         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.1%    |
| Intel Wireless-AC 9260                                             | 2         | 1.1%    |
| Intel Wireless 7265                                                | 2         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                               | 2         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 2         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.1%    |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.1%    |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.1%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.1%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1         | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 1         | 0.55%   |
| Ralink RT2501/RT2573 Wireless Adapter                              | 1         | 0.55%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter             | 1         | 0.55%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.55%   |
| Qualcomm FP3                                                       | 1         | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 62.07%  |
| Realtek Semiconductor | 13        | 14.94%  |
| Qualcomm Atheros      | 5         | 5.75%   |
| Broadcom Limited      | 4         | 4.6%    |
| MediaTek              | 3         | 3.45%   |
| Ralink                | 2         | 2.3%    |
| Broadcom              | 2         | 2.3%    |
| TP-Link               | 1         | 1.15%   |
| Ralink Technology     | 1         | 1.15%   |
| NetGear               | 1         | 1.15%   |
| Microsoft             | 1         | 1.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 7         | 8.05%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 5.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 5         | 5.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 5.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 4         | 4.6%    |
| Intel Wireless 8265 / 8275                                                | 4         | 4.6%    |
| Intel Wireless 7260                                                       | 4         | 4.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 4.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 2.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 2         | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 2.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 2.3%    |
| Intel Wireless-AC 9260                                                    | 2         | 2.3%    |
| Intel Wireless 7265                                                       | 2         | 2.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2         | 2.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 2.3%    |
| Intel Centrino Wireless-N 2230                                            | 2         | 2.3%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 2.3%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 1.15%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.15%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 1.15%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1         | 1.15%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 1.15%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.15%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1         | 1.15%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.15%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 1.15%   |
| Intel Wireless 8260                                                       | 1         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.15%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.15%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 1.15%   |
| Intel Centrino Wireless-N 100                                             | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 50        | 54.95%  |
| Intel                    | 31        | 34.07%  |
| ASIX Electronics         | 3         | 3.3%    |
| Samsung Electronics      | 2         | 2.2%    |
| Qualcomm Atheros         | 2         | 2.2%    |
| Qualcomm                 | 1         | 1.1%    |
| Marvell Technology Group | 1         | 1.1%    |
| Broadcom                 | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 43.48%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 8.7%    |
| Intel I211 Gigabit Network Connection                             | 6         | 6.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 4.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.35%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 4.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 3.26%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 2.17%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.17%   |
| Qualcomm FP3                                                      | 1         | 1.09%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.09%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.09%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.09%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.09%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.09%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.09%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.09%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 50%     |
| Ethernet | 84        | 48.84%  |
| Modem    | 2         | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 66        | 61.68%  |
| Ethernet | 41        | 38.32%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 53        | 50.96%  |
| 1     | 46        | 44.23%  |
| 3     | 4         | 3.85%   |
| 0     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 71.43%  |
| Yes  | 30        | 28.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 56.41%  |
| Realtek Semiconductor           | 7         | 8.97%   |
| Broadcom                        | 7         | 8.97%   |
| Cambridge Silicon Radio         | 6         | 7.69%   |
| IMC Networks                    | 4         | 5.13%   |
| Qualcomm Atheros Communications | 2         | 2.56%   |
| ASUSTek Computer                | 2         | 2.56%   |
| Toshiba                         | 1         | 1.28%   |
| Realtek                         | 1         | 1.28%   |
| MediaTek                        | 1         | 1.28%   |
| Lite-On Technology              | 1         | 1.28%   |
| Dell                            | 1         | 1.28%   |
| Apple                           | 1         | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 15        | 19.23%  |
| Intel Bluetooth wireless interface                  | 9         | 11.54%  |
| Intel Bluetooth Device                              | 7         | 8.97%   |
| Intel AX200 Bluetooth                               | 7         | 8.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 7.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.13%   |
| Realtek Bluetooth Radio                             | 3         | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.56%   |
| IMC Networks Wireless_Device                        | 2         | 2.56%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.56%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 2.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.56%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.28%   |
| Realtek Bluetooth Radio                             | 1         | 1.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.28%   |
| MediaTek Wireless_Device                            | 1         | 1.28%   |
| Lite-On Bluetooth Device                            | 1         | 1.28%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.28%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.28%   |
| Broadcom BCM2045A0                                  | 1         | 1.28%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.28%   |
| ASUS Bluetooth Radio                                | 1         | 1.28%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 80        | 50.63%  |
| Nvidia                     | 31        | 19.62%  |
| AMD                        | 26        | 16.46%  |
| Corsair                    | 3         | 1.9%    |
| C-Media Electronics        | 3         | 1.9%    |
| Razer USA                  | 2         | 1.27%   |
| Kingston Technology        | 2         | 1.27%   |
| Tenx Technology            | 1         | 0.63%   |
| Samsung Electronics        | 1         | 0.63%   |
| Realtek Semiconductor      | 1         | 0.63%   |
| PreSonus Audio Electronics | 1         | 0.63%   |
| Plantronics                | 1         | 0.63%   |
| Logitech                   | 1         | 0.63%   |
| Hewlett-Packard            | 1         | 0.63%   |
| Generalplus Technology     | 1         | 0.63%   |
| Barco Display Systems      | 1         | 0.63%   |
| ASUSTek Computer           | 1         | 0.63%   |
| Astro Gaming               | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 4.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 4.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 8         | 4.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 3.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.69%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 2.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.61%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.61%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.08%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.08%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.08%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.08%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.54%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.54%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 26        | 24.76%  |
| Samsung Electronics | 26        | 24.76%  |
| Corsair             | 10        | 9.52%   |
| Micron Technology   | 9         | 8.57%   |
| Crucial             | 8         | 7.62%   |
| Kingston            | 6         | 5.71%   |
| G.Skill             | 6         | 5.71%   |
| Unknown             | 4         | 3.81%   |
| Ramaxel Technology  | 3         | 2.86%   |
| Team                | 2         | 1.9%    |
| Unifosa             | 1         | 0.95%   |
| PNY                 | 1         | 0.95%   |
| Nanya Technology    | 1         | 0.95%   |
| Elpida              | 1         | 0.95%   |
| A-DATA Technology   | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 2.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.68%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.79%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.79%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.79%   |
| Kingston RAM KHX2133C14/16G 16384MB DIMM DDR4 2176MT/s           | 2         | 1.79%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.79%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.89%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 0.89%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.89%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 0.89%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.89%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s               | 1         | 0.89%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.89%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.89%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.89%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s               | 1         | 0.89%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.89%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.89%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.89%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.89%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.89%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.89%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.89%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.89%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.89%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.89%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 0.89%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.89%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.89%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                | 1         | 0.89%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 1         | 0.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 58        | 65.17%  |
| DDR3   | 22        | 24.72%  |
| LPDDR4 | 2         | 2.25%   |
| LPDDR3 | 2         | 2.25%   |
| DDR    | 2         | 2.25%   |
| SDRAM  | 1         | 1.12%   |
| DDR5   | 1         | 1.12%   |
| DDR2   | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 57.78%  |
| DIMM         | 29        | 32.22%  |
| Row Of Chips | 9         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 46.39%  |
| 4096  | 31        | 31.96%  |
| 16384 | 16        | 16.49%  |
| 2048  | 5         | 5.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 22        | 21.78%  |
| 3200  | 17        | 16.83%  |
| 1600  | 15        | 14.85%  |
| 2400  | 7         | 6.93%   |
| 1333  | 5         | 4.95%   |
| 2133  | 4         | 3.96%   |
| 3600  | 3         | 2.97%   |
| 3266  | 3         | 2.97%   |
| 2933  | 3         | 2.97%   |
| 4267  | 2         | 1.98%   |
| 3400  | 2         | 1.98%   |
| 2666  | 2         | 1.98%   |
| 2176  | 2         | 1.98%   |
| 1800  | 2         | 1.98%   |
| 800   | 2         | 1.98%   |
| 4800  | 1         | 0.99%   |
| 4400  | 1         | 0.99%   |
| 4199  | 1         | 0.99%   |
| 4133  | 1         | 0.99%   |
| 3800  | 1         | 0.99%   |
| 3467  | 1         | 0.99%   |
| 2747  | 1         | 0.99%   |
| 1450  | 1         | 0.99%   |
| 1334  | 1         | 0.99%   |
| 1067  | 1         | 0.99%   |

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

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 16        | 22.86%  |
| Chicony Electronics                    | 12        | 17.14%  |
| Acer                                   | 8         | 11.43%  |
| Realtek Semiconductor                  | 7         | 10%     |
| Syntek                                 | 4         | 5.71%   |
| Quanta                                 | 4         | 5.71%   |
| Microdia                               | 4         | 5.71%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.71%   |
| Sunplus Innovation Technology          | 2         | 2.86%   |
| Generalplus Technology                 | 2         | 2.86%   |
| Suyin                                  | 1         | 1.43%   |
| Sonix Technology                       | 1         | 1.43%   |
| Ricoh                                  | 1         | 1.43%   |
| Luxvisions Innotech Limited            | 1         | 1.43%   |
| Logitech                               | 1         | 1.43%   |
| Lite-On Technology                     | 1         | 1.43%   |
| Alpha Imaging Technology               | 1         | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 4         | 5.71%   |
| Realtek Integrated_Webcam_HD                        | 4         | 5.71%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 5.71%   |
| Quanta HP TrueVision HD Camera                      | 3         | 4.29%   |
| IMC Networks Integrated Camera                      | 3         | 4.29%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 2.86%   |
| Chicony Integrated Camera                           | 2         | 2.86%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.86%   |
| Chicony EasyCamera                                  | 2         | 2.86%   |
| Acer ThinkPad Integrated Camera                     | 2         | 2.86%   |
| Acer HD Webcam                                      | 2         | 2.86%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.43%   |
| Sunplus HP Truevision HD                            | 1         | 1.43%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.43%   |
| Ricoh Integrated Webcam                             | 1         | 1.43%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.43%   |
| Realtek Integrated Webcam                           | 1         | 1.43%   |
| Realtek Built-In Video Camera                       | 1         | 1.43%   |
| Quanta HD User Facing                               | 1         | 1.43%   |
| Microdia Webcam Vitade AF                           | 1         | 1.43%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 1.43%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.43%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.43%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.43%   |
| Logitech Webcam C600                                | 1         | 1.43%   |
| Lite-On Integrated Camera                           | 1         | 1.43%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.43%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.43%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.43%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 1         | 1.43%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.43%   |
| IMC Networks HD Camera                              | 1         | 1.43%   |
| IMC Networks EasyCamera                             | 1         | 1.43%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.43%   |
| Generalplus campark PC04                            | 1         | 1.43%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.43%   |
| Chicony USB2.0 UVC WebCam                           | 1         | 1.43%   |
| Chicony USB 2.0 Camera                              | 1         | 1.43%   |
| Chicony Integrated HP HD Webcam                     | 1         | 1.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 75        | 71.43%  |
| 1     | 26        | 24.76%  |
| 2     | 4         | 3.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 11        | 32.35%  |
| Graphics card         | 8         | 23.53%  |
| Chipcard              | 5         | 14.71%  |
| Net/wireless          | 2         | 5.88%   |
| Multimedia controller | 2         | 5.88%   |
| Camera                | 2         | 5.88%   |
| Bluetooth             | 2         | 5.88%   |
| Storage               | 1         | 2.94%   |
| Network               | 1         | 2.94%   |

