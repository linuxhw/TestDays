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

Total: 122

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Xero Rolling | 81        | 86.17%  |
| Xero         | 13        | 13.83%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 93        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.16.15-arch1-1    | 6         | 5.88%   |
| 5.18.16-arch1-1    | 4         | 3.92%   |
| 5.17.9-arch1-1     | 3         | 2.94%   |
| 5.16.2-arch1-1     | 3         | 2.94%   |
| 5.16.1-arch1-1     | 3         | 2.94%   |
| 5.15.33-1-lts      | 3         | 2.94%   |
| 5.14.14-arch1-1    | 3         | 2.94%   |
| 6.0.7-arch1-1      | 2         | 1.96%   |
| 5.19.13-arch1-1    | 2         | 1.96%   |
| 5.19.12-arch1-1    | 2         | 1.96%   |
| 5.18.3-arch1-1     | 2         | 1.96%   |
| 5.18.11-arch1-1    | 2         | 1.96%   |
| 5.17.5-arch1-1     | 2         | 1.96%   |
| 5.17.1-arch1-1     | 2         | 1.96%   |
| 5.16.8-arch1-1     | 2         | 1.96%   |
| 5.16.16-arch1-1    | 2         | 1.96%   |
| 5.16.13-arch1-1    | 2         | 1.96%   |
| 5.16.12-arch1-1    | 2         | 1.96%   |
| 5.15.10-arch1-1    | 2         | 1.96%   |
| 5.14.8-zen1-1-zen  | 2         | 1.96%   |
| 6.0.9-arch1-1      | 1         | 0.98%   |
| 6.0.8-zen1-1-zen   | 1         | 0.98%   |
| 6.0.8-arch1-1      | 1         | 0.98%   |
| 6.0.6-zen1-1-zen   | 1         | 0.98%   |
| 6.0.6-arch1-1      | 1         | 0.98%   |
| 6.0.2-zen1-1-zen   | 1         | 0.98%   |
| 6.0.2-arch1-1      | 1         | 0.98%   |
| 6.0.1-arch2-1      | 1         | 0.98%   |
| 5.19.9-arch1-1     | 1         | 0.98%   |
| 5.19.3-arch1-1     | 1         | 0.98%   |
| 5.19.2-zen1-1-zen  | 1         | 0.98%   |
| 5.19.13-zen1-1-zen | 1         | 0.98%   |
| 5.19.10-arch1-1    | 1         | 0.98%   |
| 5.19.1-arch2-1     | 1         | 0.98%   |
| 5.18.9-arch1-1     | 1         | 0.98%   |
| 5.18.6-arch1-1     | 1         | 0.98%   |
| 5.18.0-arch1-1     | 1         | 0.98%   |
| 5.17.7-arch1-1     | 1         | 0.98%   |
| 5.16.16-zen1-1-zen | 1         | 0.98%   |
| 5.16.14-arch1-1    | 1         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 5.88%   |
| 5.18.16 | 4         | 3.92%   |
| 5.14.14 | 4         | 3.92%   |
| 5.19.13 | 3         | 2.94%   |
| 5.17.9  | 3         | 2.94%   |
| 5.16.2  | 3         | 2.94%   |
| 5.16.16 | 3         | 2.94%   |
| 5.16.1  | 3         | 2.94%   |
| 5.15.33 | 3         | 2.94%   |
| 5.15.12 | 3         | 2.94%   |
| 5.14.8  | 3         | 2.94%   |
| 5.14.16 | 3         | 2.94%   |
| 6.0.8   | 2         | 1.96%   |
| 6.0.7   | 2         | 1.96%   |
| 6.0.6   | 2         | 1.96%   |
| 6.0.2   | 2         | 1.96%   |
| 5.19.12 | 2         | 1.96%   |
| 5.18.3  | 2         | 1.96%   |
| 5.18.11 | 2         | 1.96%   |
| 5.17.5  | 2         | 1.96%   |
| 5.17.1  | 2         | 1.96%   |
| 5.16.8  | 2         | 1.96%   |
| 5.16.13 | 2         | 1.96%   |
| 5.16.12 | 2         | 1.96%   |
| 5.15.13 | 2         | 1.96%   |
| 5.15.11 | 2         | 1.96%   |
| 5.15.10 | 2         | 1.96%   |
| 6.0.9   | 1         | 0.98%   |
| 6.0.1   | 1         | 0.98%   |
| 5.19.9  | 1         | 0.98%   |
| 5.19.3  | 1         | 0.98%   |
| 5.19.2  | 1         | 0.98%   |
| 5.19.10 | 1         | 0.98%   |
| 5.19.1  | 1         | 0.98%   |
| 5.18.9  | 1         | 0.98%   |
| 5.18.6  | 1         | 0.98%   |
| 5.18.0  | 1         | 0.98%   |
| 5.17.7  | 1         | 0.98%   |
| 5.16.14 | 1         | 0.98%   |
| 5.16.10 | 1         | 0.98%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 23%     |
| 5.15    | 18        | 18%     |
| 5.14    | 13        | 13%     |
| 5.18    | 11        | 11%     |
| 6.0     | 10        | 10%     |
| 5.19    | 10        | 10%     |
| 5.17    | 8         | 8%      |
| 5.10    | 3         | 3%      |
| 5.13    | 2         | 2%      |
| 5.12    | 1         | 1%      |
| 5.11    | 1         | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 93        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 88        | 92.63%  |
| XFCE   | 4         | 4.21%   |
| GNOME  | 2         | 2.11%   |
| LeftWM | 1         | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 80        | 86.02%  |
| Wayland | 11        | 11.83%  |
| Tty     | 2         | 2.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 63        | 64.95%  |
| Unknown | 17        | 17.53%  |
| LightDM | 15        | 15.46%  |
| TDM     | 1         | 1.03%   |
| GDM     | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 48        | 51.06%  |
| en_IN | 7         | 7.45%   |
| en_GB | 6         | 6.38%   |
| de_DE | 5         | 5.32%   |
| C     | 5         | 5.32%   |
| pl_PL | 4         | 4.26%   |
| it_IT | 3         | 3.19%   |
| en_AU | 3         | 3.19%   |
| ru_RU | 2         | 2.13%   |
| fr_FR | 2         | 2.13%   |
| es_MX | 2         | 2.13%   |
| vi_VN | 1         | 1.06%   |
| en_IL | 1         | 1.06%   |
| en_DK | 1         | 1.06%   |
| en_CA | 1         | 1.06%   |
| en_AG | 1         | 1.06%   |
| de_AT | 1         | 1.06%   |
| ba_RU | 1         | 1.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 61        | 64.89%  |
| BIOS | 33        | 35.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 54        | 56.84%  |
| Xfs     | 19        | 20%     |
| Ext4    | 16        | 16.84%  |
| Overlay | 6         | 6.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 64        | 68.09%  |
| Unknown | 17        | 18.09%  |
| MBR     | 13        | 13.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 75.26%  |
| Yes       | 24        | 24.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 64.52%  |
| Yes       | 33        | 35.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 28        | 30.11%  |
| Lenovo              | 17        | 18.28%  |
| Dell                | 13        | 13.98%  |
| Hewlett-Packard     | 9         | 9.68%   |
| MSI                 | 6         | 6.45%   |
| Gigabyte Technology | 4         | 4.3%    |
| Acer                | 4         | 4.3%    |
| ASRock              | 3         | 3.23%   |
| Pegatron            | 2         | 2.15%   |
| Toshiba             | 1         | 1.08%   |
| Medion              | 1         | 1.08%   |
| HUAWEI              | 1         | 1.08%   |
| BESSTAR Tech        | 1         | 1.08%   |
| Aquarius            | 1         | 1.08%   |
| Apple               | 1         | 1.08%   |
| Unknown             | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 3.23%   |
| MSI MS-7971                                | 2         | 2.15%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 2.15%   |
| Toshiba TECRA A11                          | 1         | 1.08%   |
| Pegatron p6-2026                           | 1         | 1.08%   |
| Pegatron D15K                              | 1         | 1.08%   |
| MSI MS-7B61                                | 1         | 1.08%   |
| MSI Katana GF66 11UE                       | 1         | 1.08%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.08%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.08%   |
| Medion P6816                               | 1         | 1.08%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 1.08%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.08%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 1.08%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.08%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.08%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.08%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.08%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.08%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 1.08%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.08%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.08%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.08%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.08%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.08%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.08%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.08%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.08%   |
| HUAWEI WRT-WX9                             | 1         | 1.08%   |
| HP Z230 SFF Workstation                    | 1         | 1.08%   |
| HP ProOne 400 G1 AiO                       | 1         | 1.08%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.08%   |
| HP Notebook                                | 1         | 1.08%   |
| HP Laptop 15s-fq2xxx                       | 1         | 1.08%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.08%   |
| HP Laptop 15-da0xxx                        | 1         | 1.08%   |
| HP ENVY Sleekbook 4                        | 1         | 1.08%   |
| HP Compaq Elite 8300 CMT                   | 1         | 1.08%   |
| Gigabyte Z170X-UD3                         | 1         | 1.08%   |
| Gigabyte X570 AORUS MASTER                 | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 7         | 7.53%   |
| ASUS ROG             | 7         | 7.53%   |
| Lenovo IdeaPad       | 5         | 5.38%   |
| ASUS TUF             | 5         | 5.38%   |
| Dell Precision       | 4         | 4.3%    |
| Dell Latitude        | 4         | 4.3%    |
| ASUS VivoBook        | 4         | 4.3%    |
| Acer Aspire          | 4         | 4.3%    |
| Lenovo Legion        | 3         | 3.23%   |
| HP Laptop            | 3         | 3.23%   |
| MSI MS-7971          | 2         | 2.15%   |
| Dell Inspiron        | 2         | 2.15%   |
| ASUS PRIME           | 2         | 2.15%   |
| ASUS ASUS            | 2         | 2.15%   |
| Toshiba TECRA        | 1         | 1.08%   |
| Pegatron p6-2026     | 1         | 1.08%   |
| Pegatron D15K        | 1         | 1.08%   |
| MSI MS-7B61          | 1         | 1.08%   |
| MSI Katana           | 1         | 1.08%   |
| MSI GP73             | 1         | 1.08%   |
| MSI GF63             | 1         | 1.08%   |
| Medion P6816         | 1         | 1.08%   |
| Lenovo Yoga          | 1         | 1.08%   |
| Lenovo Y520-15IKBN   | 1         | 1.08%   |
| HUAWEI WRT-WX9       | 1         | 1.08%   |
| HP Z230              | 1         | 1.08%   |
| HP ProOne            | 1         | 1.08%   |
| HP Pavilion          | 1         | 1.08%   |
| HP Notebook          | 1         | 1.08%   |
| HP ENVY              | 1         | 1.08%   |
| HP Compaq            | 1         | 1.08%   |
| Gigabyte Z170X-UD3   | 1         | 1.08%   |
| Gigabyte X570        | 1         | 1.08%   |
| Gigabyte B460MDS3HV2 | 1         | 1.08%   |
| Gigabyte A320M-S2H   | 1         | 1.08%   |
| Dell Vostro          | 1         | 1.08%   |
| Dell Venue           | 1         | 1.08%   |
| Dell OptiPlex        | 1         | 1.08%   |
| BESSTAR Tech X500    | 1         | 1.08%   |
| ASUS ZenBook         | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 18        | 19.35%  |
| 2020 | 13        | 13.98%  |
| 2018 | 10        | 10.75%  |
| 2017 | 9         | 9.68%   |
| 2021 | 8         | 8.6%    |
| 2012 | 8         | 8.6%    |
| 2013 | 6         | 6.45%   |
| 2015 | 5         | 5.38%   |
| 2016 | 3         | 3.23%   |
| 2014 | 3         | 3.23%   |
| 2011 | 3         | 3.23%   |
| 2010 | 3         | 3.23%   |
| 2009 | 2         | 2.15%   |
| 2022 | 1         | 1.08%   |
| 2008 | 1         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 54        | 58.06%  |
| Desktop     | 35        | 37.63%  |
| Convertible | 3         | 3.23%   |
| Server      | 1         | 1.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 93        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 30.11%  |
| 16.01-24.0  | 23        | 24.73%  |
| 8.01-16.0   | 17        | 18.28%  |
| 32.01-64.0  | 12        | 12.9%   |
| 3.01-4.0    | 9         | 9.68%   |
| 24.01-32.0  | 3         | 3.23%   |
| 64.01-256.0 | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 34        | 33.33%  |
| 1.01-2.0   | 24        | 23.53%  |
| 4.01-8.0   | 18        | 17.65%  |
| 3.01-4.0   | 13        | 12.75%  |
| 8.01-16.0  | 5         | 4.9%    |
| 16.01-24.0 | 4         | 3.92%   |
| 0.51-1.0   | 2         | 1.96%   |
| 0.01-0.5   | 2         | 1.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 50        | 53.76%  |
| 2      | 24        | 25.81%  |
| 3      | 9         | 9.68%   |
| 4      | 5         | 5.38%   |
| 6      | 2         | 2.15%   |
| 5      | 2         | 2.15%   |
| 7      | 1         | 1.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 76.6%   |
| Yes       | 22        | 23.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 80.65%  |
| No        | 18        | 19.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 80.65%  |
| No        | 18        | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 76.6%   |
| No        | 22        | 23.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 20        | 21.51%  |
| India                 | 9         | 9.68%   |
| Germany               | 7         | 7.53%   |
| Poland                | 5         | 5.38%   |
| Italy                 | 4         | 4.3%    |
| France                | 4         | 4.3%    |
| UK                    | 3         | 3.23%   |
| Russia                | 3         | 3.23%   |
| Greece                | 3         | 3.23%   |
| Australia             | 3         | 3.23%   |
| Norway                | 2         | 2.15%   |
| Netherlands           | 2         | 2.15%   |
| Mexico                | 2         | 2.15%   |
| Lebanon               | 2         | 2.15%   |
| Canada                | 2         | 2.15%   |
| Zambia                | 1         | 1.08%   |
| Vietnam               | 1         | 1.08%   |
| Turkey                | 1         | 1.08%   |
| Togo                  | 1         | 1.08%   |
| Sweden                | 1         | 1.08%   |
| Spain                 | 1         | 1.08%   |
| Romania               | 1         | 1.08%   |
| Portugal              | 1         | 1.08%   |
| Palestinian Territory | 1         | 1.08%   |
| Pakistan              | 1         | 1.08%   |
| Morocco               | 1         | 1.08%   |
| Mongolia              | 1         | 1.08%   |
| Malaysia              | 1         | 1.08%   |
| Israel                | 1         | 1.08%   |
| Hungary               | 1         | 1.08%   |
| Denmark               | 1         | 1.08%   |
| Cyprus                | 1         | 1.08%   |
| Colombia              | 1         | 1.08%   |
| Chile                 | 1         | 1.08%   |
| Brazil                | 1         | 1.08%   |
| Austria               | 1         | 1.08%   |
| Argentina             | 1         | 1.08%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Longmont       | 3         | 3.23%   |
| Madurai        | 2         | 2.15%   |
| Bremen         | 2         | 2.15%   |
| Beirut         | 2         | 2.15%   |
| Zell am See    | 1         | 1.08%   |
| Wroclaw        | 1         | 1.08%   |
| Wrexham        | 1         | 1.08%   |
| Wells          | 1         | 1.08%   |
| Warsaw         | 1         | 1.08%   |
| Ulan Bator     | 1         | 1.08%   |
| Toronto        | 1         | 1.08%   |
| Tel Aviv       | 1         | 1.08%   |
| Taranto        | 1         | 1.08%   |
| Stuttgart      | 1         | 1.08%   |
| Stavropol      | 1         | 1.08%   |
| Springfield    | 1         | 1.08%   |
| Silkeborg      | 1         | 1.08%   |
| Shadrinsk      | 1         | 1.08%   |
| Santa Cruz     | 1         | 1.08%   |
| Salt Lake City | 1         | 1.08%   |
| Ramallah       | 1         | 1.08%   |
| Pune           | 1         | 1.08%   |
| Poznan         | 1         | 1.08%   |
| Portland       | 1         | 1.08%   |
| Porcia         | 1         | 1.08%   |
| Pirmasens      | 1         | 1.08%   |
| Phoenix        | 1         | 1.08%   |
| Perth          | 1         | 1.08%   |
| Pavia          | 1         | 1.08%   |
| Passos         | 1         | 1.08%   |
| Paris          | 1         | 1.08%   |
| Oslo           | 1         | 1.08%   |
| Oberursel      | 1         | 1.08%   |
| Nicosia        | 1         | 1.08%   |
| New Haven      | 1         | 1.08%   |
| Neu-Ulm        | 1         | 1.08%   |
| Mumbai         | 1         | 1.08%   |
| Moscow         | 1         | 1.08%   |
| Monterrey      | 1         | 1.08%   |
| Milton Keynes  | 1         | 1.08%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 28        | 42     | 17.95%  |
| Samsung Electronics         | 27        | 38     | 17.31%  |
| WDC                         | 22        | 31     | 14.1%   |
| Kingston                    | 12        | 16     | 7.69%   |
| Toshiba                     | 8         | 10     | 5.13%   |
| Intel                       | 6         | 8      | 3.85%   |
| HGST                        | 6         | 6      | 3.85%   |
| Sandisk                     | 5         | 7      | 3.21%   |
| Micron Technology           | 4         | 6      | 2.56%   |
| China                       | 4         | 4      | 2.56%   |
| Unknown                     | 3         | 4      | 1.92%   |
| Phison                      | 3         | 3      | 1.92%   |
| Hitachi                     | 3         | 3      | 1.92%   |
| Transcend                   | 2         | 2      | 1.28%   |
| LITEON                      | 2         | 2      | 1.28%   |
| Crucial                     | 2         | 2      | 1.28%   |
| XPG                         | 1         | 1      | 0.64%   |
| SK hynix                    | 1         | 1      | 0.64%   |
| Silicon Motion              | 1         | 1      | 0.64%   |
| Realtek Semiconductor       | 1         | 1      | 0.64%   |
| PNY                         | 1         | 1      | 0.64%   |
| Plextor                     | 1         | 1      | 0.64%   |
| OSCOO                       | 1         | 1      | 0.64%   |
| Micron/Crucial Technology   | 1         | 1      | 0.64%   |
| LITEONIT                    | 1         | 1      | 0.64%   |
| KIOXIA                      | 1         | 1      | 0.64%   |
| Kingston Technology Company | 1         | 1      | 0.64%   |
| Intenso                     | 1         | 1      | 0.64%   |
| Inateck                     | 1         | 1      | 0.64%   |
| GOODRAM                     | 1         | 1      | 0.64%   |
| Biostar                     | 1         | 1      | 0.64%   |
| Apple                       | 1         | 1      | 0.64%   |
| Apacer                      | 1         | 1      | 0.64%   |
| A-DATA Technology           | 1         | 1      | 0.64%   |
| 2-Power                     | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.69%   |
| Seagate One Touch HDD 5TB            | 3         | 1.69%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.69%   |
| Toshiba MQ04ABF100 1TB               | 2         | 1.12%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.12%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 1.12%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.12%   |
| SanDisk NVMe SSD Drive 500GB         | 2         | 1.12%   |
| Samsung SSD 970 EVO 1TB              | 2         | 1.12%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.12%   |
| Samsung SSD 860 EVO 1TB              | 2         | 1.12%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.12%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.12%   |
| China SSD 1TB                        | 2         | 1.12%   |
| XPG GAMMIX S50 1TB                   | 1         | 0.56%   |
| WDC WDS512G1X0C-00ENX0 512GB         | 1         | 0.56%   |
| WDC WDS500G3XHC-00SJG0 500GB         | 1         | 0.56%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.56%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.56%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.56%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.56%   |
| WDC WD800JD-00MSA1 80GB              | 1         | 0.56%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.56%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.56%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1         | 0.56%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1         | 0.56%   |
| WDC WD40EZRZ-22GXCB0 4TB             | 1         | 0.56%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1         | 0.56%   |
| WDC WD20EZRZ-60Z5HB0 2TB             | 1         | 0.56%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.56%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1         | 0.56%   |
| WDC WD15EADS-11R6B1 1TB              | 1         | 0.56%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.56%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.56%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.56%   |
| WDC WD10EAVS-00D7B1 1TB              | 1         | 0.56%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 0.56%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB | 1         | 0.56%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 41     | 48.28%  |
| WDC                 | 13        | 19     | 22.41%  |
| Toshiba             | 6         | 8      | 10.34%  |
| HGST                | 6         | 6      | 10.34%  |
| Hitachi             | 3         | 3      | 5.17%   |
| Samsung Electronics | 2         | 2      | 3.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 27.66%  |
| Kingston            | 8         | 11     | 17.02%  |
| China               | 4         | 4      | 8.51%   |
| WDC                 | 3         | 3      | 6.38%   |
| Transcend           | 2         | 2      | 4.26%   |
| LITEON              | 2         | 2      | 4.26%   |
| Crucial             | 2         | 2      | 4.26%   |
| SanDisk             | 1         | 1      | 2.13%   |
| PNY                 | 1         | 1      | 2.13%   |
| Plextor             | 1         | 1      | 2.13%   |
| OSCOO               | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| LITEONIT            | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| GOODRAM             | 1         | 1      | 2.13%   |
| Biostar             | 1         | 1      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |
| Apacer              | 1         | 1      | 2.13%   |
| 2-Power             | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 79     | 35.04%  |
| NVMe | 46        | 67     | 33.58%  |
| SSD  | 40        | 53     | 29.2%   |
| MMC  | 3         | 4      | 2.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 124    | 53.66%  |
| NVMe | 46        | 66     | 37.4%   |
| SAS  | 8         | 9      | 6.5%    |
| MMC  | 3         | 4      | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 61     | 43.75%  |
| 0.51-1.0   | 36        | 47     | 37.5%   |
| 1.01-2.0   | 8         | 11     | 8.33%   |
| 4.01-10.0  | 8         | 11     | 8.33%   |
| 3.01-4.0   | 1         | 1      | 1.04%   |
| 2.01-3.0   | 1         | 1      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 26        | 26.53%  |
| 1001-2000      | 19        | 19.39%  |
| 251-500        | 14        | 14.29%  |
| 501-1000       | 12        | 12.24%  |
| 101-250        | 8         | 8.16%   |
| Unknown        | 6         | 6.12%   |
| 51-100         | 5         | 5.1%    |
| 1-20           | 4         | 4.08%   |
| 21-50          | 2         | 2.04%   |
| 2001-3000      | 2         | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 24.49%  |
| 1-20           | 18        | 18.37%  |
| 51-100         | 17        | 17.35%  |
| 251-500        | 8         | 8.16%   |
| 21-50          | 8         | 8.16%   |
| 501-1000       | 7         | 7.14%   |
| Unknown        | 6         | 6.12%   |
| 2001-3000      | 5         | 5.1%    |
| More than 3000 | 3         | 3.06%   |
| 1001-2000      | 2         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 1      | 5%      |
| WDC WD1002FAEX-00Z3A0 1TB        | 1         | 2      | 5%      |
| Toshiba MQ01ABF050M 500GB        | 1         | 1      | 5%      |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 5%      |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 5%      |
| Seagate ST9500420AS 500GB        | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB        | 1         | 1      | 5%      |
| Seagate ST500LM000-SSHD-8GB      | 1         | 1      | 5%      |
| Seagate ST31000524AS 1TB         | 1         | 1      | 5%      |
| Seagate ST2000VX000-1CU164 2TB   | 1         | 1      | 5%      |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 5%      |
| Seagate ST1000LM049-2GH172 1TB   | 1         | 1      | 5%      |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 1      | 5%      |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 5%      |
| Kingston SUV400S37240G 240GB SSD | 1         | 1      | 5%      |
| Hitachi HTS725050A9A364 500GB    | 1         | 1      | 5%      |
| Hitachi HCP725050GLA380 500GB    | 1         | 1      | 5%      |
| HGST HTS725032A7E630 320GB       | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 5%      |
| China SATA3 240GB SSD            | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 8         | 8      | 42.11%  |
| WDC      | 2         | 3      | 10.53%  |
| Toshiba  | 2         | 3      | 10.53%  |
| Kingston | 2         | 2      | 10.53%  |
| Hitachi  | 2         | 2      | 10.53%  |
| HGST     | 2         | 2      | 10.53%  |
| China    | 1         | 1      | 5.26%   |

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
| HDD  | 15        | 18     | 83.33%  |
| SSD  | 3         | 3      | 16.67%  |

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
| Works    | 71        | 128    | 64.55%  |
| Detected | 22        | 54     | 20%     |
| Malfunc  | 17        | 21     | 15.45%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 70        | 52.24%  |
| AMD                          | 16        | 11.94%  |
| Samsung Electronics          | 14        | 10.45%  |
| SanDisk                      | 11        | 8.21%   |
| Kingston Technology Company  | 5         | 3.73%   |
| Micron Technology            | 4         | 2.99%   |
| Phison Electronics           | 3         | 2.24%   |
| Toshiba America Info Systems | 2         | 1.49%   |
| Realtek Semiconductor        | 2         | 1.49%   |
| SK hynix                     | 1         | 0.75%   |
| Silicon Motion               | 1         | 0.75%   |
| Seagate Technology           | 1         | 0.75%   |
| Micron/Crucial Technology    | 1         | 0.75%   |
| KIOXIA                       | 1         | 0.75%   |
| ASMedia Technology           | 1         | 0.75%   |
| ADATA Technology             | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 10.27%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 4.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 3.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 2.74%   |
| Micron Non-Volatile memory controller                                          | 4         | 2.74%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 2.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 2.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 2.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 2.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.05%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 2.05%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 2.05%   |
| Intel SSD 660P Series                                                          | 3         | 2.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 2.05%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.37%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.37%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.37%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.37%   |
| AMD FCH SATA Controller D                                                      | 2         | 1.37%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.37%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.68%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.68%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.68%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.68%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.68%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.68%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.68%   |
| Samsung Apple PCIe SSD                                                         | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 73        | 54.89%  |
| NVMe | 46        | 34.59%  |
| RAID | 14        | 10.53%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 74        | 79.57%  |
| AMD    | 19        | 20.43%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 3         | 3.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 3.19%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 3.19%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 3.19%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 3.19%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 2.13%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 2.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2.13%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 2         | 2.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 2.13%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 2.13%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 2         | 2.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 2         | 2.13%   |
| AMD Ryzen 5 3600 6-Core Processor       | 2         | 2.13%   |
| Intel Genuine CPU 0000 @ 2.10GHz        | 1         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.06%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.06%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.06%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.06%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.06%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.06%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 1.06%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.06%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.06%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.06%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 1         | 1.06%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.06%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 1         | 1.06%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 1.06%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1         | 1.06%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 1.06%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1         | 1.06%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 1         | 1.06%   |
| Intel Core i5-6600 CPU @ 3.30GHz        | 1         | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 30        | 31.91%  |
| Intel Core i7     | 25        | 26.6%   |
| Other             | 8         | 8.51%   |
| AMD Ryzen 7       | 8         | 8.51%   |
| AMD Ryzen 5       | 7         | 7.45%   |
| Intel Core i3     | 6         | 6.38%   |
| Intel Celeron     | 2         | 2.13%   |
| Intel Genuine     | 1         | 1.06%   |
| Intel Core 2 Quad | 1         | 1.06%   |
| Intel Core 2 Duo  | 1         | 1.06%   |
| AMD Ryzen 9       | 1         | 1.06%   |
| AMD Ryzen 3       | 1         | 1.06%   |
| AMD Athlon        | 1         | 1.06%   |
| AMD A8            | 1         | 1.06%   |
| AMD A6            | 1         | 1.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 40        | 42.55%  |
| 2      | 28        | 29.79%  |
| 6      | 15        | 15.96%  |
| 8      | 10        | 10.64%  |
| 12     | 1         | 1.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 80.85%  |
| 1      | 18        | 19.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 20        | 20.83%  |
| 0x806c1    | 7         | 7.29%   |
| 0x906ea    | 6         | 6.25%   |
| 0x306a9    | 6         | 6.25%   |
| 0x806ec    | 5         | 5.21%   |
| 0x806e9    | 5         | 5.21%   |
| 0x506e3    | 4         | 4.17%   |
| 0x08701021 | 4         | 4.17%   |
| 0x306c3    | 3         | 3.13%   |
| 0x206a7    | 3         | 3.13%   |
| 0x0a201016 | 3         | 3.13%   |
| 0x906ed    | 2         | 2.08%   |
| 0x906eb    | 2         | 2.08%   |
| 0x906e9    | 2         | 2.08%   |
| 0x806eb    | 2         | 2.08%   |
| 0x40651    | 2         | 2.08%   |
| 0x1067a    | 2         | 2.08%   |
| 0xa0653    | 1         | 1.04%   |
| 0xa0652    | 1         | 1.04%   |
| 0x806d1    | 1         | 1.04%   |
| 0x706e5    | 1         | 1.04%   |
| 0x706a8    | 1         | 1.04%   |
| 0x406e3    | 1         | 1.04%   |
| 0x306d4    | 1         | 1.04%   |
| 0x20655    | 1         | 1.04%   |
| 0x20652    | 1         | 1.04%   |
| 0x106e5    | 1         | 1.04%   |
| 0x0a50000b | 1         | 1.04%   |
| 0x0a20120a | 1         | 1.04%   |
| 0x08701013 | 1         | 1.04%   |
| 0x08600106 | 1         | 1.04%   |
| 0x08108109 | 1         | 1.04%   |
| 0x0810100b | 1         | 1.04%   |
| 0x06006705 | 1         | 1.04%   |
| 0x0600611a | 1         | 1.04%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 29.79%  |
| Zen 2         | 9         | 9.57%   |
| Haswell       | 9         | 9.57%   |
| IvyBridge     | 8         | 8.51%   |
| TigerLake     | 7         | 7.45%   |
| Zen 3         | 5         | 5.32%   |
| Skylake       | 5         | 5.32%   |
| SandyBridge   | 4         | 4.26%   |
| Zen+          | 3         | 3.19%   |
| Westmere      | 2         | 2.13%   |
| Penryn        | 2         | 2.13%   |
| Nehalem       | 2         | 2.13%   |
| Icelake       | 2         | 2.13%   |
| Goldmont plus | 2         | 2.13%   |
| Excavator     | 2         | 2.13%   |
| CometLake     | 2         | 2.13%   |
| Zen           | 1         | 1.06%   |
| Broadwell     | 1         | 1.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 58        | 46.03%  |
| Nvidia | 48        | 38.1%   |
| AMD    | 20        | 15.87%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 5         | 3.94%   |
| Intel HD Graphics 620                                                     | 5         | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.15%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 2.36%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 3         | 2.36%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.36%   |
| Intel UHD Graphics 620                                                    | 3         | 2.36%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.36%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 3         | 2.36%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 2         | 1.57%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 1.57%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 1.57%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.57%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.57%   |
| AMD Renoir                                                                | 2         | 1.57%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                            | 2         | 1.57%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.79%   |
| Nvidia TU117M                                                             | 1         | 0.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.79%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.79%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.79%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.79%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 27        | 29.03%  |
| 1 x Intel      | 26        | 27.96%  |
| 1 x Nvidia     | 18        | 19.35%  |
| 1 x AMD        | 15        | 16.13%  |
| Intel + AMD    | 3         | 3.23%   |
| AMD + Nvidia   | 2         | 2.15%   |
| 2 x Nvidia     | 1         | 1.08%   |
| 2 x Intel      | 1         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 58        | 61.7%   |
| Proprietary | 34        | 36.17%  |
| Unknown     | 2         | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 59.57%  |
| 1.01-2.0   | 15        | 15.96%  |
| 7.01-8.0   | 6         | 6.38%   |
| 5.01-6.0   | 6         | 6.38%   |
| 0.01-0.5   | 4         | 4.26%   |
| 3.01-4.0   | 3         | 3.19%   |
| 8.01-16.0  | 3         | 3.19%   |
| 0.51-1.0   | 1         | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 17        | 15.74%  |
| AU Optronics         | 15        | 13.89%  |
| BOE                  | 11        | 10.19%  |
| LG Display           | 9         | 8.33%   |
| Chimei Innolux       | 9         | 8.33%   |
| Goldstar             | 5         | 4.63%   |
| Ancor Communications | 5         | 4.63%   |
| Acer                 | 5         | 4.63%   |
| Dell                 | 4         | 3.7%    |
| Sharp                | 3         | 2.78%   |
| AOC                  | 3         | 2.78%   |
| PANDA                | 2         | 1.85%   |
| Iiyama               | 2         | 1.85%   |
| Hewlett-Packard      | 2         | 1.85%   |
| Apple                | 2         | 1.85%   |
| Sceptre Tech         | 1         | 0.93%   |
| MSI                  | 1         | 0.93%   |
| LGD                  | 1         | 0.93%   |
| Lenovo               | 1         | 0.93%   |
| Kogan                | 1         | 0.93%   |
| KOC                  | 1         | 0.93%   |
| JRY                  | 1         | 0.93%   |
| Idek Iiyama          | 1         | 0.93%   |
| Hitachi              | 1         | 0.93%   |
| Gigabyte Technology  | 1         | 0.93%   |
| FOX                  | 1         | 0.93%   |
| CSO                  | 1         | 0.93%   |
| BenQ                 | 1         | 0.93%   |
| ASUSTek Computer     | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 1.8%    |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 1.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.8%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.8%    |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.9%    |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.9%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.9%    |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch    | 1         | 0.9%    |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.9%    |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.9%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM0B60 1680x1050 887x500mm 40.1-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM07D6 1920x1080 530x300mm 24.0-inch   | 1         | 0.9%    |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 0.9%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 0.9%    |
| Samsung Electronics C27R500 SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1         | 0.9%    |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.9%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.9%    |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                         | 1         | 0.9%    |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.9%    |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD0561 1920x1080 294x165mm 13.3-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.9%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD03D7 1366x768 309x174mm 14.0-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 0.9%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 0.9%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 0.9%    |
| Kogan HDMI1 KGN3400 3440x1440 796x334mm 34.0-inch                       | 1         | 0.9%    |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch                 | 1         | 0.9%    |
| JRY DP JRY2700 2560x1440 597x336mm 27.0-inch                            | 1         | 0.9%    |
| Iiyama PL3466WQ IVM761A 3440x1440 797x334mm 34.0-inch                   | 1         | 0.9%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 55.34%  |
| 1366x768 (WXGA)    | 12        | 11.65%  |
| 3840x2160 (4K)     | 8         | 7.77%   |
| 2560x1440 (QHD)    | 6         | 5.83%   |
| 3440x1440          | 5         | 4.85%   |
| 2560x1080          | 3         | 2.91%   |
| 1600x900 (HD+)     | 3         | 2.91%   |
| 3840x2400          | 1         | 0.97%   |
| 3840x1080          | 1         | 0.97%   |
| 3200x1800 (QHD+)   | 1         | 0.97%   |
| 2160x1440          | 1         | 0.97%   |
| 1920x540           | 1         | 0.97%   |
| 1920x1200 (WUXGA)  | 1         | 0.97%   |
| 1680x1050 (WSXGA+) | 1         | 0.97%   |
| 1440x900 (WXGA+)   | 1         | 0.97%   |
| 1280x1024 (SXGA)   | 1         | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 31.48%  |
| 27      | 10        | 9.26%   |
| 23      | 9         | 8.33%   |
| 14      | 9         | 8.33%   |
| 21      | 7         | 6.48%   |
| 13      | 7         | 6.48%   |
| 34      | 6         | 5.56%   |
| 84      | 4         | 3.7%    |
| 31      | 4         | 3.7%    |
| 24      | 4         | 3.7%    |
| 17      | 3         | 2.78%   |
| Unknown | 3         | 2.78%   |
| 28      | 2         | 1.85%   |
| 18      | 2         | 1.85%   |
| 54      | 1         | 0.93%   |
| 48      | 1         | 0.93%   |
| 20      | 1         | 0.93%   |
| 12      | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 42.59%  |
| 501-600     | 22        | 20.37%  |
| 401-500     | 10        | 9.26%   |
| 701-800     | 6         | 5.56%   |
| 601-700     | 6         | 5.56%   |
| 201-300     | 5         | 4.63%   |
| 351-400     | 4         | 3.7%    |
| 1501-2000   | 4         | 3.7%    |
| Unknown     | 3         | 2.78%   |
| 1001-1500   | 2         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 79        | 82.29%  |
| 21/9    | 8         | 8.33%   |
| 16/10   | 4         | 4.17%   |
| Unknown | 2         | 2.08%   |
| 5/4     | 1         | 1.04%   |
| 32/9    | 1         | 1.04%   |
| 3/2     | 1         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 31.78%  |
| 201-250        | 19        | 17.76%  |
| 81-90          | 13        | 12.15%  |
| 351-500        | 10        | 9.35%   |
| 301-350        | 10        | 9.35%   |
| More than 1000 | 5         | 4.67%   |
| 71-80          | 3         | 2.8%    |
| 121-130        | 3         | 2.8%    |
| Unknown        | 3         | 2.8%    |
| 251-300        | 2         | 1.87%   |
| 151-200        | 2         | 1.87%   |
| 61-70          | 1         | 0.93%   |
| 141-150        | 1         | 0.93%   |
| 501-1000       | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 37        | 35.92%  |
| 51-100        | 28        | 27.18%  |
| 101-120       | 25        | 24.27%  |
| 161-240       | 5         | 4.85%   |
| More than 240 | 3         | 2.91%   |
| Unknown       | 3         | 2.91%   |
| 1-50          | 2         | 1.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 72        | 76.6%   |
| 2     | 19        | 20.21%  |
| 0     | 2         | 2.13%   |
| 3     | 1         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 61        | 45.52%  |
| Realtek Semiconductor             | 47        | 35.07%  |
| Qualcomm Atheros                  | 6         | 4.48%   |
| MediaTek                          | 3         | 2.24%   |
| Broadcom Limited                  | 3         | 2.24%   |
| ASIX Electronics                  | 3         | 2.24%   |
| Ericsson Business Mobile Networks | 2         | 1.49%   |
| Broadcom                          | 2         | 1.49%   |
| TP-Link                           | 1         | 0.75%   |
| Samsung Electronics               | 1         | 0.75%   |
| Ralink Technology                 | 1         | 0.75%   |
| Qualcomm                          | 1         | 0.75%   |
| NetGear                           | 1         | 0.75%   |
| Microsoft                         | 1         | 0.75%   |
| Marvell Technology Group          | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 36        | 22.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 5.03%   |
| Intel Wi-Fi 6 AX200                                                | 7         | 4.4%    |
| Intel I211 Gigabit Network Connection                              | 6         | 3.77%   |
| Intel Wi-Fi 6 AX201                                                | 5         | 3.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 4         | 2.52%   |
| Realtek RTL8125 2.5GbE Controller                                  | 4         | 2.52%   |
| Intel Wireless 7260                                                | 4         | 2.52%   |
| Intel Ethernet Connection (2) I219-V                               | 4         | 2.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 2.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 4         | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 3         | 1.89%   |
| Intel Wireless 8265 / 8275                                         | 3         | 1.89%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 1.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 2         | 1.26%   |
| Intel Wireless-AC 9260                                             | 2         | 1.26%   |
| Intel Wireless 7265                                                | 2         | 1.26%   |
| Intel Ethernet Connection (7) I219-V                               | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 2         | 1.26%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.26%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 1.26%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 1.26%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 1         | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 1         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 1         | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 1         | 0.63%   |
| Ralink RT2501/RT2573 Wireless Adapter                              | 1         | 0.63%   |
| Qualcomm Redmi Note 8                                              | 1         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller          | 1         | 0.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 1         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet     | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 64.47%  |
| Realtek Semiconductor | 10        | 13.16%  |
| Qualcomm Atheros      | 5         | 6.58%   |
| MediaTek              | 3         | 3.95%   |
| Broadcom Limited      | 3         | 3.95%   |
| Broadcom              | 2         | 2.63%   |
| TP-Link               | 1         | 1.32%   |
| Ralink Technology     | 1         | 1.32%   |
| NetGear               | 1         | 1.32%   |
| Microsoft             | 1         | 1.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 7         | 9.21%   |
| Intel Wi-Fi 6 AX201                                                       | 5         | 6.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 6.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 4         | 5.26%   |
| Intel Wireless 7260                                                       | 4         | 5.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 5.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 4         | 5.26%   |
| Intel Wireless 8265 / 8275                                                | 3         | 3.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 2.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 2         | 2.63%   |
| Intel Wireless-AC 9260                                                    | 2         | 2.63%   |
| Intel Wireless 7265                                                       | 2         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 2.63%   |
| Intel Centrino Wireless-N 2230                                            | 2         | 2.63%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 2.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.32%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.32%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 1.32%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1         | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.32%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1         | 1.32%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.32%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.32%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 1.32%   |
| Intel Wireless 8260                                                       | 1         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.32%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 1.32%   |
| Intel Centrino Wireless-N 100                                             | 1         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                            | 1         | 1.32%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.32%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 53.75%  |
| Intel                    | 28        | 35%     |
| ASIX Electronics         | 3         | 3.75%   |
| Qualcomm Atheros         | 2         | 2.5%    |
| Samsung Electronics      | 1         | 1.25%   |
| Qualcomm                 | 1         | 1.25%   |
| Marvell Technology Group | 1         | 1.25%   |
| Broadcom                 | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 36        | 44.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 9.88%   |
| Intel I211 Gigabit Network Connection                             | 6         | 7.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.94%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 4.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 3.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.7%    |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.23%   |
| Qualcomm Redmi Note 8                                             | 1         | 1.23%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.23%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.23%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.23%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 49.34%  |
| Ethernet | 75        | 49.34%  |
| Modem    | 2         | 1.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 59        | 60.82%  |
| Ethernet | 38        | 39.18%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 48.39%  |
| 1     | 43        | 46.24%  |
| 3     | 4         | 4.3%    |
| 0     | 1         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 70.21%  |
| Yes  | 28        | 29.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 55.56%  |
| Broadcom                        | 7         | 9.72%   |
| Realtek Semiconductor           | 6         | 8.33%   |
| Cambridge Silicon Radio         | 6         | 8.33%   |
| IMC Networks                    | 4         | 5.56%   |
| Qualcomm Atheros Communications | 2         | 2.78%   |
| ASUSTek Computer                | 2         | 2.78%   |
| Toshiba                         | 1         | 1.39%   |
| MediaTek                        | 1         | 1.39%   |
| Lite-On Technology              | 1         | 1.39%   |
| Dell                            | 1         | 1.39%   |
| Apple                           | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 18.06%  |
| Intel Bluetooth wireless interface                  | 9         | 12.5%   |
| Intel AX200 Bluetooth                               | 7         | 9.72%   |
| Intel AX201 Bluetooth                               | 6         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 8.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.17%   |
| Realtek Bluetooth Radio                             | 3         | 4.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.78%   |
| IMC Networks Wireless_Device                        | 2         | 2.78%   |
| IMC Networks Bluetooth Radio                        | 2         | 2.78%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 2.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.78%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.39%   |
| MediaTek Wireless_Device                            | 1         | 1.39%   |
| Lite-On Bluetooth Device                            | 1         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.39%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.39%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.39%   |
| Broadcom BCM2045A0                                  | 1         | 1.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.39%   |
| ASUS Bluetooth Radio                                | 1         | 1.39%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 74        | 52.11%  |
| Nvidia                     | 28        | 19.72%  |
| AMD                        | 21        | 14.79%  |
| Corsair                    | 3         | 2.11%   |
| C-Media Electronics        | 3         | 2.11%   |
| Razer USA                  | 2         | 1.41%   |
| Kingston Technology        | 2         | 1.41%   |
| Tenx Technology            | 1         | 0.7%    |
| Samsung Electronics        | 1         | 0.7%    |
| Realtek Semiconductor      | 1         | 0.7%    |
| PreSonus Audio Electronics | 1         | 0.7%    |
| Plantronics                | 1         | 0.7%    |
| Logitech                   | 1         | 0.7%    |
| Hewlett-Packard            | 1         | 0.7%    |
| Generalplus Technology     | 1         | 0.7%    |
| Astro Gaming               | 1         | 0.7%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 5.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 5.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8         | 4.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 4.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6         | 3.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 2.99%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 2.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 2.4%    |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.8%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.8%    |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.2%    |
| Tenx Technology USB AUDIO                                                  | 1         | 0.6%    |
| Samsung Electronics USBC Headset                                           | 1         | 0.6%    |
| Realtek Semiconductor USB Audio                                            | 1         | 0.6%    |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1         | 0.6%    |
| Razer USA Razer Kraken X USB                                               | 1         | 0.6%    |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1         | 0.6%    |
| Plantronics C320-M                                                         | 1         | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 23        | 24.21%  |
| Samsung Electronics | 22        | 23.16%  |
| Corsair             | 10        | 10.53%  |
| Micron Technology   | 9         | 9.47%   |
| Crucial             | 7         | 7.37%   |
| Kingston            | 6         | 6.32%   |
| G.Skill             | 6         | 6.32%   |
| Unknown             | 4         | 4.21%   |
| Team                | 2         | 2.11%   |
| Ramaxel Technology  | 2         | 2.11%   |
| Unifosa             | 1         | 1.05%   |
| PNY                 | 1         | 1.05%   |
| Elpida              | 1         | 1.05%   |
| A-DATA Technology   | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 2.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.98%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 1.98%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.98%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 1.98%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s                 | 2         | 1.98%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 2         | 1.98%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 1         | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                           | 1         | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                            | 1         | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 1         | 0.99%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                   | 1         | 0.99%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                  | 1         | 0.99%   |
| Team RAM TEAMGROUP-UD3-1600 2GB DIMM DDR3 1600MT/s                  | 1         | 0.99%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.99%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 0.99%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s                | 1         | 0.99%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s              | 1         | 0.99%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.99%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.99%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s          | 1         | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.99%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.99%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                           | 1         | 0.99%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                           | 1         | 0.99%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.99%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s               | 1         | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 51        | 64.56%  |
| DDR3   | 20        | 25.32%  |
| LPDDR4 | 2         | 2.53%   |
| LPDDR3 | 2         | 2.53%   |
| DDR    | 2         | 2.53%   |
| SDRAM  | 1         | 1.27%   |
| DDR2   | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 56.25%  |
| DIMM         | 28        | 35%     |
| Row Of Chips | 7         | 8.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 38        | 44.19%  |
| 4096  | 29        | 33.72%  |
| 16384 | 15        | 17.44%  |
| 2048  | 4         | 4.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 18        | 20%     |
| 3200  | 17        | 18.89%  |
| 1600  | 14        | 15.56%  |
| 2400  | 4         | 4.44%   |
| 1333  | 4         | 4.44%   |
| 3600  | 3         | 3.33%   |
| 3266  | 3         | 3.33%   |
| 2933  | 3         | 3.33%   |
| 2133  | 3         | 3.33%   |
| 4267  | 2         | 2.22%   |
| 3400  | 2         | 2.22%   |
| 2666  | 2         | 2.22%   |
| 2176  | 2         | 2.22%   |
| 1800  | 2         | 2.22%   |
| 800   | 2         | 2.22%   |
| 4400  | 1         | 1.11%   |
| 4199  | 1         | 1.11%   |
| 4133  | 1         | 1.11%   |
| 3800  | 1         | 1.11%   |
| 3467  | 1         | 1.11%   |
| 2747  | 1         | 1.11%   |
| 1450  | 1         | 1.11%   |
| 1334  | 1         | 1.11%   |
| 1067  | 1         | 1.11%   |

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
| IMC Networks                           | 14        | 23.33%  |
| Chicony Electronics                    | 9         | 15%     |
| Acer                                   | 8         | 13.33%  |
| Realtek Semiconductor                  | 7         | 11.67%  |
| Microdia                               | 4         | 6.67%   |
| Syntek                                 | 3         | 5%      |
| Quanta                                 | 3         | 5%      |
| Sunplus Innovation Technology          | 2         | 3.33%   |
| Generalplus Technology                 | 2         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.33%   |
| Suyin                                  | 1         | 1.67%   |
| Ricoh                                  | 1         | 1.67%   |
| Luxvisions Innotech Limited            | 1         | 1.67%   |
| Logitech                               | 1         | 1.67%   |
| Lite-On Technology                     | 1         | 1.67%   |
| Alpha Imaging Technology               | 1         | 1.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                         | 4         | 6.67%   |
| IMC Networks USB2.0 HD UVC WebCam                                    | 4         | 6.67%   |
| Syntek Integrated Camera                                             | 3         | 5%      |
| Quanta HP TrueVision HD Camera                                       | 2         | 3.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                                   | 2         | 3.33%   |
| IMC Networks Integrated Camera                                       | 2         | 3.33%   |
| Chicony Integrated Camera                                            | 2         | 3.33%   |
| Chicony EasyCamera                                                   | 2         | 3.33%   |
| Acer ThinkPad Integrated Camera                                      | 2         | 3.33%   |
| Acer HD Webcam                                                       | 2         | 3.33%   |
| Suyin Asus Integrated Webcam                                         | 1         | 1.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1         | 1.67%   |
| Sunplus HP Truevision HD                                             | 1         | 1.67%   |
| Ricoh Integrated Webcam                                              | 1         | 1.67%   |
| Realtek Integrated Webcam_HD                                         | 1         | 1.67%   |
| Realtek Integrated Webcam                                            | 1         | 1.67%   |
| Realtek Built-In Video Camera                                        | 1         | 1.67%   |
| Quanta HD User Facing                                                | 1         | 1.67%   |
| Microdia Webcam Vitade AF                                            | 1         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_E4HD                               | 1         | 1.67%   |
| Microdia Integrated_Webcam_HD                                        | 1         | 1.67%   |
| Microdia Dell Integrated HD Webcam                                   | 1         | 1.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                  | 1         | 1.67%   |
| Logitech Webcam C600                                                 | 1         | 1.67%   |
| Lite-On Integrated Camera                                            | 1         | 1.67%   |
| IMC Networks VGA UVC WebCam                                          | 1         | 1.67%   |
| IMC Networks UVC VGA Webcam                                          | 1         | 1.67%   |
| IMC Networks USB2.0 UVC HD Webcam                                    | 1         | 1.67%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                 | 1         | 1.67%   |
| IMC Networks SunplusIT Integrated Camera                             | 1         | 1.67%   |
| IMC Networks EasyCamera                                              | 1         | 1.67%   |
| Generalplus GENERAL WEBCAM                                           | 1         | 1.67%   |
| Generalplus campark PC04                                             | 1         | 1.67%   |
| Chicony USB2.0 UVC WebCam                                            | 1         | 1.67%   |
| Chicony USB 2.0 Camera                                               | 1         | 1.67%   |
| Chicony HP Webcam                                                    | 1         | 1.67%   |
| Chicony HP High Definition 1MP Webcam                                | 1         | 1.67%   |
| Chicony HD User Facing                                               | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                     | 1         | 1.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 37.5%   |
| Shenzhen Goodix Technology | 2         | 25%     |
| Elan Microelectronics      | 2         | 25%     |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI             | 2         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader | 1         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device         | 1         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader          | 1         | 12.5%   |
| Elan fingerprint sensor [FeinTech FPS00200] | 1         | 12.5%   |
| Elan ELAN:Fingerprint                       | 1         | 12.5%   |
| AuthenTec Fingerprint Sensor                | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor     | Computers | Percent |
|------------|-----------|---------|
| Upek       | 2         | 33.33%  |
| Broadcom   | 2         | 33.33%  |
| Yubico.com | 1         | 16.67%  |
| Clay Logic | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 33.33%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 16.67%  |
| Clay Logic Nitrokey Pro                                    | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 68        | 72.34%  |
| 1     | 23        | 24.47%  |
| 2     | 3         | 3.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 27.59%  |
| Graphics card         | 7         | 24.14%  |
| Chipcard              | 4         | 13.79%  |
| Net/wireless          | 2         | 6.9%    |
| Multimedia controller | 2         | 6.9%    |
| Camera                | 2         | 6.9%    |
| Bluetooth             | 2         | 6.9%    |
| Storage               | 1         | 3.45%   |
| Network               | 1         | 3.45%   |

