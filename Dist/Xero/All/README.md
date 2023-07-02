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

Total: 185

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T460s 20F90057M... | Notebook    | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | Notebook    | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c3118a3d89](https://linux-hardware.org/?probe=c3118a3d89) | Jun 29, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [895760e7db](https://linux-hardware.org/?probe=895760e7db) | Jun 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fa162784e0](https://linux-hardware.org/?probe=fa162784e0) | Jun 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| MSI           | Z77A-G41                    | Desktop     | [e7e4924bda](https://linux-hardware.org/?probe=e7e4924bda) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [284344e775](https://linux-hardware.org/?probe=284344e775) | Jun 14, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [859f1b3a88](https://linux-hardware.org/?probe=859f1b3a88) | Jun 13, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [89d6a4edd2](https://linux-hardware.org/?probe=89d6a4edd2) | May 13, 2023 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [5cfbeb30e0](https://linux-hardware.org/?probe=5cfbeb30e0) | May 10, 2023 |
| Unknown       | Intel X79                   | Desktop     | [6b1ddbd923](https://linux-hardware.org/?probe=6b1ddbd923) | May 03, 2023 |
| Biostar       | H110MHV3                    | Desktop     | [95b25ba480](https://linux-hardware.org/?probe=95b25ba480) | Apr 29, 2023 |
| Samsung       | 950QED                      | Convertible | [f2568c7949](https://linux-hardware.org/?probe=f2568c7949) | Apr 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [520ad2ca86](https://linux-hardware.org/?probe=520ad2ca86) | Mar 31, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP            | 8437                        | Desktop     | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | Desktop     | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell          | G5 5500                     | Notebook    | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [5d307f2d26](https://linux-hardware.org/?probe=5d307f2d26) | Mar 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS11Y00     | Notebook    | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Acer          | Aspire GX-281               | Desktop     | [d318df6931](https://linux-hardware.org/?probe=d318df6931) | Mar 04, 2023 |
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
| Xero Rolling | 125       | 90.58%  |
| Xero         | 13        | 9.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 137       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.16.15-arch1-1   | 6         | 4%      |
| 6.1.12-arch1-1    | 5         | 3.33%   |
| 6.2.6-arch1-1     | 4         | 2.67%   |
| 6.0.12-arch1-1    | 4         | 2.67%   |
| 5.18.16-arch1-1   | 4         | 2.67%   |
| 6.1.1-arch1-1     | 3         | 2%      |
| 5.17.9-arch1-1    | 3         | 2%      |
| 5.16.2-arch1-1    | 3         | 2%      |
| 5.16.1-arch1-1    | 3         | 2%      |
| 5.15.33-1-lts     | 3         | 2%      |
| 5.14.14-arch1-1   | 3         | 2%      |
| 6.3.9-arch1-1     | 2         | 1.33%   |
| 6.3.8-arch1-1     | 2         | 1.33%   |
| 6.3.6-arch1-1     | 2         | 1.33%   |
| 6.2.8-arch1-1     | 2         | 1.33%   |
| 6.2.7-arch1-1     | 2         | 1.33%   |
| 6.2.12-arch1-1    | 2         | 1.33%   |
| 6.0.7-arch1-1     | 2         | 1.33%   |
| 5.19.9-arch1-1    | 2         | 1.33%   |
| 5.19.13-arch1-1   | 2         | 1.33%   |
| 5.19.12-arch1-1   | 2         | 1.33%   |
| 5.18.3-arch1-1    | 2         | 1.33%   |
| 5.18.11-arch1-1   | 2         | 1.33%   |
| 5.17.5-arch1-1    | 2         | 1.33%   |
| 5.17.1-arch1-1    | 2         | 1.33%   |
| 5.16.8-arch1-1    | 2         | 1.33%   |
| 5.16.16-arch1-1   | 2         | 1.33%   |
| 5.16.13-arch1-1   | 2         | 1.33%   |
| 5.16.12-arch1-1   | 2         | 1.33%   |
| 5.15.10-arch1-1   | 2         | 1.33%   |
| 5.14.8-zen1-1-zen | 2         | 1.33%   |
| 6.3.9-zen1-1-zen  | 1         | 0.67%   |
| 6.3.9-lqx1-1-lqx  | 1         | 0.67%   |
| 6.3.8-zen1-1-zen  | 1         | 0.67%   |
| 6.3.7-arch1-1     | 1         | 0.67%   |
| 6.3.4-arch1-1     | 1         | 0.67%   |
| 6.3.2-arch1-1     | 1         | 0.67%   |
| 6.3.1-arch1-1     | 1         | 0.67%   |
| 6.2.9-arch1-1     | 1         | 0.67%   |
| 6.2.2-arch2-1     | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 4%      |
| 6.1.12  | 5         | 3.33%   |
| 6.3.9   | 4         | 2.67%   |
| 6.2.6   | 4         | 2.67%   |
| 6.0.12  | 4         | 2.67%   |
| 5.18.16 | 4         | 2.67%   |
| 5.14.14 | 4         | 2.67%   |
| 6.3.8   | 3         | 2%      |
| 6.1.1   | 3         | 2%      |
| 5.19.13 | 3         | 2%      |
| 5.17.9  | 3         | 2%      |
| 5.16.2  | 3         | 2%      |
| 5.16.16 | 3         | 2%      |
| 5.16.1  | 3         | 2%      |
| 5.15.33 | 3         | 2%      |
| 5.15.12 | 3         | 2%      |
| 5.14.8  | 3         | 2%      |
| 5.14.16 | 3         | 2%      |
| 6.3.6   | 2         | 1.33%   |
| 6.2.8   | 2         | 1.33%   |
| 6.2.7   | 2         | 1.33%   |
| 6.2.12  | 2         | 1.33%   |
| 6.1.6   | 2         | 1.33%   |
| 6.0.8   | 2         | 1.33%   |
| 6.0.7   | 2         | 1.33%   |
| 6.0.6   | 2         | 1.33%   |
| 6.0.2   | 2         | 1.33%   |
| 5.19.9  | 2         | 1.33%   |
| 5.19.12 | 2         | 1.33%   |
| 5.18.3  | 2         | 1.33%   |
| 5.18.11 | 2         | 1.33%   |
| 5.17.5  | 2         | 1.33%   |
| 5.17.1  | 2         | 1.33%   |
| 5.16.8  | 2         | 1.33%   |
| 5.16.13 | 2         | 1.33%   |
| 5.16.12 | 2         | 1.33%   |
| 5.15.13 | 2         | 1.33%   |
| 5.15.11 | 2         | 1.33%   |
| 5.15.10 | 2         | 1.33%   |
| 6.3.7   | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 15.65%  |
| 5.15    | 18        | 12.24%  |
| 6.0     | 15        | 10.2%   |
| 6.2     | 14        | 9.52%   |
| 6.1     | 14        | 9.52%   |
| 6.3     | 13        | 8.84%   |
| 5.14    | 13        | 8.84%   |
| 5.19    | 11        | 7.48%   |
| 5.18    | 11        | 7.48%   |
| 5.17    | 8         | 5.44%   |
| 5.10    | 3         | 2.04%   |
| 5.13    | 2         | 1.36%   |
| 5.12    | 1         | 0.68%   |
| 5.11    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 137       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 129       | 92.81%  |
| XFCE   | 4         | 2.88%   |
| GNOME  | 4         | 2.88%   |
| LeftWM | 1         | 0.72%   |
| KDE    | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 123       | 89.13%  |
| Wayland | 13        | 9.42%   |
| Tty     | 2         | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 96        | 68.09%  |
| Unknown | 27        | 19.15%  |
| LightDM | 15        | 10.64%  |
| GDM     | 2         | 1.42%   |
| TDM     | 1         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 70        | 50.72%  |
| en_IN | 11        | 7.97%   |
| de_DE | 9         | 6.52%   |
| en_GB | 6         | 4.35%   |
| C     | 6         | 4.35%   |
| pl_PL | 5         | 3.62%   |
| ru_RU | 4         | 2.9%    |
| it_IT | 3         | 2.17%   |
| es_MX | 3         | 2.17%   |
| en_CA | 3         | 2.17%   |
| en_AU | 3         | 2.17%   |
| fr_FR | 2         | 1.45%   |
| en_DK | 2         | 1.45%   |
| vi_VN | 1         | 0.72%   |
| tr_TR | 1         | 0.72%   |
| sv_SE | 1         | 0.72%   |
| hu_HU | 1         | 0.72%   |
| es_CL | 1         | 0.72%   |
| en_ZA | 1         | 0.72%   |
| en_IL | 1         | 0.72%   |
| en_AG | 1         | 0.72%   |
| de_CH | 1         | 0.72%   |
| de_AT | 1         | 0.72%   |
| ba_RU | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 86        | 62.32%  |
| BIOS | 52        | 37.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 65        | 46.76%  |
| Xfs     | 43        | 30.94%  |
| Ext4    | 24        | 17.27%  |
| Overlay | 7         | 5.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 94        | 68.12%  |
| Unknown | 27        | 19.57%  |
| MBR     | 17        | 12.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 108       | 76.06%  |
| Yes       | 34        | 23.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 63.77%  |
| Yes       | 50        | 36.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 35        | 25.55%  |
| Lenovo              | 29        | 21.17%  |
| Dell                | 18        | 13.14%  |
| Hewlett-Packard     | 16        | 11.68%  |
| MSI                 | 8         | 5.84%   |
| Acer                | 7         | 5.11%   |
| Gigabyte Technology | 4         | 2.92%   |
| Pegatron            | 3         | 2.19%   |
| ASRock              | 3         | 2.19%   |
| Medion              | 2         | 1.46%   |
| HUAWEI              | 2         | 1.46%   |
| Apple               | 2         | 1.46%   |
| Unknown             | 2         | 1.46%   |
| Toshiba             | 1         | 0.73%   |
| Samsung Electronics | 1         | 0.73%   |
| JINGSHA             | 1         | 0.73%   |
| Biostar             | 1         | 0.73%   |
| BESSTAR Tech        | 1         | 0.73%   |
| Aquarius            | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 2.19%   |
| Unknown                                    | 3         | 2.19%   |
| MSI MS-7971                                | 2         | 1.46%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 1.46%   |
| Toshiba TECRA A11                          | 1         | 0.73%   |
| Samsung 950QED                             | 1         | 0.73%   |
| Pegatron p6-2026                           | 1         | 0.73%   |
| Pegatron D15K                              | 1         | 0.73%   |
| Pegatron 20-b010                           | 1         | 0.73%   |
| MSI MS-7C91                                | 1         | 0.73%   |
| MSI MS-7B61                                | 1         | 0.73%   |
| MSI MS-7758                                | 1         | 0.73%   |
| MSI Katana GF66 11UE                       | 1         | 0.73%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.73%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.73%   |
| Medion P6816                               | 1         | 0.73%   |
| Medion Akoya P7818                         | 1         | 0.73%   |
| Lenovo Yoga 730-15IKB 81CU                 | 1         | 0.73%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 0.73%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.73%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 0.73%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.73%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.73%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.73%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.73%   |
| Lenovo ThinkPad T460s 20F90057MS           | 1         | 0.73%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 0.73%   |
| Lenovo ThinkPad T440 20B7A0CYMH            | 1         | 0.73%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 0.73%   |
| Lenovo ThinkPad P51 20HJS11Y00             | 1         | 0.73%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 0.73%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 0.73%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 0.73%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG           | 1         | 0.73%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.73%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 0.73%   |
| Lenovo IdeaPad S540-15IML D 81NG           | 1         | 0.73%   |
| Lenovo IdeaPad S340-15IIL 81VW             | 1         | 0.73%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 0.73%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 11        | 8.03%   |
| Lenovo IdeaPad     | 10        | 7.3%    |
| ASUS ROG           | 8         | 5.84%   |
| Acer Aspire        | 7         | 5.11%   |
| ASUS TUF           | 6         | 4.38%   |
| Lenovo Legion      | 5         | 3.65%   |
| Dell Latitude      | 5         | 3.65%   |
| Dell Precision     | 4         | 2.92%   |
| ASUS VivoBook      | 4         | 2.92%   |
| HP Pavilion        | 3         | 2.19%   |
| HP Laptop          | 3         | 2.19%   |
| Dell Inspiron      | 3         | 2.19%   |
| ASUS PRIME         | 3         | 2.19%   |
| ASUS ASUS          | 3         | 2.19%   |
| Unknown            | 3         | 2.19%   |
| MSI MS-7971        | 2         | 1.46%   |
| Lenovo Yoga        | 2         | 1.46%   |
| Dell OptiPlex      | 2         | 1.46%   |
| Toshiba TECRA      | 1         | 0.73%   |
| Samsung 950QED     | 1         | 0.73%   |
| Pegatron p6-2026   | 1         | 0.73%   |
| Pegatron D15K      | 1         | 0.73%   |
| Pegatron 20-b010   | 1         | 0.73%   |
| MSI MS-7C91        | 1         | 0.73%   |
| MSI MS-7B61        | 1         | 0.73%   |
| MSI MS-7758        | 1         | 0.73%   |
| MSI Katana         | 1         | 0.73%   |
| MSI GP73           | 1         | 0.73%   |
| MSI GF63           | 1         | 0.73%   |
| Medion P6816       | 1         | 0.73%   |
| Medion Akoya       | 1         | 0.73%   |
| Lenovo Y520-15IKBN | 1         | 0.73%   |
| HUAWEI WRT-WX9     | 1         | 0.73%   |
| HUAWEI BOM-WXX9    | 1         | 0.73%   |
| HP ZBook           | 1         | 0.73%   |
| HP Z230            | 1         | 0.73%   |
| HP Victus          | 1         | 0.73%   |
| HP ProOne          | 1         | 0.73%   |
| HP ProBook         | 1         | 0.73%   |
| HP Notebook        | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 26        | 18.98%  |
| 2020 | 18        | 13.14%  |
| 2018 | 14        | 10.22%  |
| 2017 | 14        | 10.22%  |
| 2021 | 12        | 8.76%   |
| 2012 | 11        | 8.03%   |
| 2015 | 9         | 6.57%   |
| 2013 | 9         | 6.57%   |
| 2014 | 5         | 3.65%   |
| 2022 | 4         | 2.92%   |
| 2016 | 4         | 2.92%   |
| 2011 | 4         | 2.92%   |
| 2010 | 4         | 2.92%   |
| 2009 | 2         | 1.46%   |
| 2008 | 1         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 80        | 58.39%  |
| Desktop     | 50        | 36.5%   |
| Convertible | 6         | 4.38%   |
| Server      | 1         | 0.73%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 137       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 137       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 29.2%   |
| 16.01-24.0  | 37        | 27.01%  |
| 8.01-16.0   | 25        | 18.25%  |
| 32.01-64.0  | 17        | 12.41%  |
| 3.01-4.0    | 13        | 9.49%   |
| 24.01-32.0  | 3         | 2.19%   |
| 64.01-256.0 | 2         | 1.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 44        | 29.93%  |
| 4.01-8.0   | 35        | 23.81%  |
| 1.01-2.0   | 29        | 19.73%  |
| 3.01-4.0   | 23        | 15.65%  |
| 8.01-16.0  | 8         | 5.44%   |
| 16.01-24.0 | 4         | 2.72%   |
| 0.51-1.0   | 2         | 1.36%   |
| 0.01-0.5   | 2         | 1.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 54.29%  |
| 2      | 36        | 25.71%  |
| 3      | 13        | 9.29%   |
| 4      | 8         | 5.71%   |
| 5      | 4         | 2.86%   |
| 6      | 2         | 1.43%   |
| 7      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 107       | 77.54%  |
| Yes       | 31        | 22.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 81.75%  |
| No        | 25        | 18.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 81.16%  |
| No        | 26        | 18.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 71.74%  |
| No        | 39        | 28.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 27        | 19.57%  |
| Germany               | 14        | 10.14%  |
| India                 | 13        | 9.42%   |
| Poland                | 6         | 4.35%   |
| Canada                | 6         | 4.35%   |
| Russia                | 5         | 3.62%   |
| Italy                 | 5         | 3.62%   |
| France                | 5         | 3.62%   |
| UK                    | 3         | 2.17%   |
| Turkey                | 3         | 2.17%   |
| Mexico                | 3         | 2.17%   |
| Greece                | 3         | 2.17%   |
| Australia             | 3         | 2.17%   |
| Sweden                | 2         | 1.45%   |
| Spain                 | 2         | 1.45%   |
| Pakistan              | 2         | 1.45%   |
| Norway                | 2         | 1.45%   |
| Netherlands           | 2         | 1.45%   |
| Lebanon               | 2         | 1.45%   |
| Hungary               | 2         | 1.45%   |
| Denmark               | 2         | 1.45%   |
| Colombia              | 2         | 1.45%   |
| Chile                 | 2         | 1.45%   |
| Zambia                | 1         | 0.72%   |
| Vietnam               | 1         | 0.72%   |
| Togo                  | 1         | 0.72%   |
| Switzerland           | 1         | 0.72%   |
| South Africa          | 1         | 0.72%   |
| Romania               | 1         | 0.72%   |
| Portugal              | 1         | 0.72%   |
| Palestinian Territory | 1         | 0.72%   |
| Morocco               | 1         | 0.72%   |
| Mongolia              | 1         | 0.72%   |
| Malaysia              | 1         | 0.72%   |
| Israel                | 1         | 0.72%   |
| Indonesia             | 1         | 0.72%   |
| Egypt                 | 1         | 0.72%   |
| Czechia               | 1         | 0.72%   |
| Cyprus                | 1         | 0.72%   |
| Brazil                | 1         | 0.72%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Longmont              | 4         | 2.9%    |
| Warsaw                | 2         | 1.45%   |
| Stuttgart             | 2         | 1.45%   |
| Red Lake              | 2         | 1.45%   |
| Pune                  | 2         | 1.45%   |
| Phoenix               | 2         | 1.45%   |
| Madurai               | 2         | 1.45%   |
| Istanbul              | 2         | 1.45%   |
| Bremen                | 2         | 1.45%   |
| Berlin                | 2         | 1.45%   |
| Beirut                | 2         | 1.45%   |
| Zenica                | 1         | 0.72%   |
| Zell am See           | 1         | 0.72%   |
| Wroclaw               | 1         | 0.72%   |
| Wrexham               | 1         | 0.72%   |
| Wells                 | 1         | 0.72%   |
| Wangen                | 1         | 0.72%   |
| Vredenburg            | 1         | 0.72%   |
| Vejle                 | 1         | 0.72%   |
| Ulan Bator            | 1         | 0.72%   |
| Ufa                   | 1         | 0.72%   |
| Toronto               | 1         | 0.72%   |
| Tel Aviv              | 1         | 0.72%   |
| Taranto               | 1         | 0.72%   |
| Tangerang             | 1         | 0.72%   |
| Stow                  | 1         | 0.72%   |
| Stockholm             | 1         | 0.72%   |
| Stavropol             | 1         | 0.72%   |
| Stagno                | 1         | 0.72%   |
| Springfield           | 1         | 0.72%   |
| Sonora                | 1         | 0.72%   |
| Silkeborg             | 1         | 0.72%   |
| Shadrinsk             | 1         | 0.72%   |
| Seattle               | 1         | 0.72%   |
| Santa Cruz            | 1         | 0.72%   |
| Sant Boi de Llobregat | 1         | 0.72%   |
| Salt Lake City        | 1         | 0.72%   |
| Ramallah              | 1         | 0.72%   |
| Poznan                | 1         | 0.72%   |
| Portland              | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 42        | 55     | 18.26%  |
| Seagate                     | 36        | 52     | 15.65%  |
| WDC                         | 28        | 38     | 12.17%  |
| Kingston                    | 15        | 19     | 6.52%   |
| Toshiba                     | 14        | 16     | 6.09%   |
| SanDisk                     | 11        | 14     | 4.78%   |
| Intel                       | 9         | 11     | 3.91%   |
| Unknown                     | 8         | 9      | 3.48%   |
| HGST                        | 6         | 6      | 2.61%   |
| Crucial                     | 6         | 9      | 2.61%   |
| SK hynix                    | 5         | 5      | 2.17%   |
| Micron Technology           | 4         | 6      | 1.74%   |
| KIOXIA                      | 4         | 5      | 1.74%   |
| China                       | 4         | 4      | 1.74%   |
| Transcend                   | 3         | 3      | 1.3%    |
| Phison                      | 3         | 3      | 1.3%    |
| Hitachi                     | 3         | 3      | 1.3%    |
| Micron/Crucial Technology   | 2         | 2      | 0.87%   |
| LITEON                      | 2         | 2      | 0.87%   |
| Intenso                     | 2         | 3      | 0.87%   |
| Apple                       | 2         | 2      | 0.87%   |
| A-DATA Technology           | 2         | 2      | 0.87%   |
| XPG                         | 1         | 1      | 0.43%   |
| Vaseky                      | 1         | 1      | 0.43%   |
| SPCC                        | 1         | 1      | 0.43%   |
| Silicon Motion              | 1         | 1      | 0.43%   |
| Realtek Semiconductor       | 1         | 1      | 0.43%   |
| PNY                         | 1         | 1      | 0.43%   |
| Plextor                     | 1         | 1      | 0.43%   |
| Phison Electronics          | 1         | 1      | 0.43%   |
| OSCOO                       | 1         | 1      | 0.43%   |
| LITEONIT                    | 1         | 1      | 0.43%   |
| Leven                       | 1         | 1      | 0.43%   |
| Kingston Technology Company | 1         | 1      | 0.43%   |
| Inateck                     | 1         | 1      | 0.43%   |
| Hewlett-Packard             | 1         | 1      | 0.43%   |
| GOODRAM                     | 1         | 1      | 0.43%   |
| Biostar                     | 1         | 1      | 0.43%   |
| ASMedia                     | 1         | 1      | 0.43%   |
| Apacer                      | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 1.57%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.57%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 1.57%   |
| Unknown SD/MMC/MS PRO 250GB                         | 3         | 1.18%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.18%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.18%   |
| Seagate One Touch HDD 2TB                           | 3         | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 3         | 1.18%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 2         | 0.78%   |
| Unknown MMC Card  64GB                              | 2         | 0.78%   |
| Toshiba DT01ACA300 3TB                              | 2         | 0.78%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.78%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2         | 0.78%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.78%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2         | 0.78%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.78%   |
| Samsung SSD 980 1TB                                 | 2         | 0.78%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.78%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.78%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.78%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.78%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.78%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 512GB       | 2         | 0.78%   |
| HGST HTS545050A7E680 500GB                          | 2         | 0.78%   |
| China SSD 1TB                                       | 2         | 0.78%   |
| XPG GAMMIX S50 1TB                                  | 1         | 0.39%   |
| WDC WDS512G1X0C-00ENX0 512GB                        | 1         | 0.39%   |
| WDC WDS500G3XHC-00SJG0 500GB                        | 1         | 0.39%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.39%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.39%   |
| WDC WDS120G2G0A-00JH30 128GB SSD                    | 1         | 0.39%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.39%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.39%   |
| WDC WD800JD-00MSA1 80GB                             | 1         | 0.39%   |
| WDC WD7500BPKT-75PK4T0 752GB                        | 1         | 0.39%   |
| WDC WD6400AAKS-22A7B2 640GB                         | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 51     | 43.37%  |
| WDC                 | 19        | 25     | 22.89%  |
| Toshiba             | 11        | 13     | 13.25%  |
| HGST                | 6         | 6      | 7.23%   |
| Unknown             | 3         | 3      | 3.61%   |
| Samsung Electronics | 3         | 3      | 3.61%   |
| Hitachi             | 3         | 3      | 3.61%   |
| Intenso             | 1         | 2      | 1.2%    |
| ASMedia             | 1         | 1      | 1.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 24.29%  |
| Kingston            | 11        | 14     | 15.71%  |
| Crucial             | 6         | 9      | 8.57%   |
| WDC                 | 4         | 4      | 5.71%   |
| SanDisk             | 4         | 4      | 5.71%   |
| China               | 4         | 4      | 5.71%   |
| Transcend           | 3         | 3      | 4.29%   |
| LITEON              | 2         | 2      | 2.86%   |
| Apple               | 2         | 2      | 2.86%   |
| Vaseky              | 1         | 1      | 1.43%   |
| SPCC                | 1         | 1      | 1.43%   |
| SK hynix            | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Plextor             | 1         | 1      | 1.43%   |
| OSCOO               | 1         | 1      | 1.43%   |
| Micron Technology   | 1         | 1      | 1.43%   |
| LITEONIT            | 1         | 1      | 1.43%   |
| Leven               | 1         | 1      | 1.43%   |
| Intenso             | 1         | 1      | 1.43%   |
| Intel               | 1         | 1      | 1.43%   |
| Hewlett-Packard     | 1         | 1      | 1.43%   |
| GOODRAM             | 1         | 1      | 1.43%   |
| Biostar             | 1         | 1      | 1.43%   |
| Apacer              | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 1      | 1.43%   |
| 2-Power             | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 70        | 96     | 35.18%  |
| HDD  | 65        | 107    | 32.66%  |
| SSD  | 59        | 79     | 29.65%  |
| MMC  | 5         | 6      | 2.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 170    | 51.93%  |
| NVMe | 70        | 95     | 38.67%  |
| SAS  | 12        | 17     | 6.63%   |
| MMC  | 5         | 6      | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 90     | 46.62%  |
| 0.51-1.0   | 47        | 61     | 35.34%  |
| 1.01-2.0   | 15        | 19     | 11.28%  |
| 4.01-10.0  | 6         | 13     | 4.51%   |
| 2.01-3.0   | 2         | 2      | 1.5%    |
| 3.01-4.0   | 1         | 1      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 31        | 21.83%  |
| 1001-2000      | 25        | 17.61%  |
| 251-500        | 20        | 14.08%  |
| 101-250        | 20        | 14.08%  |
| 501-1000       | 15        | 10.56%  |
| 51-100         | 9         | 6.34%   |
| Unknown        | 9         | 6.34%   |
| 21-50          | 5         | 3.52%   |
| 1-20           | 5         | 3.52%   |
| 2001-3000      | 3         | 2.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 30        | 21.13%  |
| 101-250        | 29        | 20.42%  |
| 51-100         | 21        | 14.79%  |
| 21-50          | 17        | 11.97%  |
| 251-500        | 12        | 8.45%   |
| 501-1000       | 9         | 6.34%   |
| Unknown        | 9         | 6.34%   |
| 2001-3000      | 6         | 4.23%   |
| 1001-2000      | 5         | 3.52%   |
| More than 3000 | 4         | 2.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 3.45%   |
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 3.45%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 1         | 1      | 3.45%   |
| WDC WD10EADS-00M2B0 1TB                                         | 1         | 1      | 3.45%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 1         | 2      | 3.45%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 3.45%   |
| Toshiba MK4058GSX 400GB                                         | 1         | 1      | 3.45%   |
| Toshiba MK2555GSX 250GB                                         | 1         | 1      | 3.45%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD                           | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 3.45%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 3.45%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 3.45%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1         | 1      | 3.45%   |
| Seagate ST31000524AS 1TB                                        | 1         | 1      | 3.45%   |
| Seagate ST2000VX000-1CU164 2TB                                  | 1         | 1      | 3.45%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 1         | 1      | 3.45%   |
| Seagate ST2000DL003-9VT166 2TB                                  | 1         | 1      | 3.45%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 3.45%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 3.45%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 3.45%   |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 3.45%   |
| Kingston SUV400S37240G 240GB SSD                                | 1         | 1      | 3.45%   |
| Hitachi HTS725050A9A364 500GB                                   | 1         | 1      | 3.45%   |
| Hitachi HCP725050GLA380 500GB                                   | 1         | 1      | 3.45%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 3.45%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 3.45%   |
| China SATA3 240GB SSD                                           | 1         | 1      | 3.45%   |
| ASMedia AS2115 8TB                                              | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 35.71%  |
| WDC                 | 5         | 6      | 17.86%  |
| Toshiba             | 3         | 4      | 10.71%  |
| Kingston            | 2         | 2      | 7.14%   |
| Hitachi             | 2         | 2      | 7.14%   |
| HGST                | 2         | 2      | 7.14%   |
| SK hynix            | 1         | 1      | 3.57%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| ASMedia             | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 10     | 43.48%  |
| WDC     | 5         | 6      | 21.74%  |
| Toshiba | 3         | 4      | 13.04%  |
| Hitachi | 2         | 2      | 8.7%    |
| HGST    | 2         | 2      | 8.7%    |
| ASMedia | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 25     | 81.48%  |
| SSD  | 4         | 4      | 14.81%  |
| NVMe | 1         | 1      | 3.7%    |

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
| Works    | 101       | 179    | 62.35%  |
| Detected | 35        | 79     | 21.6%   |
| Malfunc  | 26        | 30     | 16.05%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 98        | 50.26%  |
| AMD                          | 26        | 13.33%  |
| Samsung Electronics          | 25        | 12.82%  |
| SanDisk                      | 14        | 7.18%   |
| Kingston Technology Company  | 5         | 2.56%   |
| SK hynix                     | 4         | 2.05%   |
| Phison Electronics           | 4         | 2.05%   |
| Micron Technology            | 4         | 2.05%   |
| KIOXIA                       | 4         | 2.05%   |
| Toshiba America Info Systems | 3         | 1.54%   |
| Realtek Semiconductor        | 2         | 1.03%   |
| Micron/Crucial Technology    | 2         | 1.03%   |
| Silicon Motion               | 1         | 0.51%   |
| Seagate Technology           | 1         | 0.51%   |
| ASMedia Technology           | 1         | 0.51%   |
| ADATA Technology             | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 11%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 3.35%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.87%   |
| Intel SATA Controller [RAID mode]                                              | 6         | 2.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 2.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.44%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 1.44%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.44%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.44%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.44%   |
| Intel SSD 660P Series                                                          | 3         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.44%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.44%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.96%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.96%   |
| SanDisk PC SN530 NVMe SSD                                                      | 2         | 0.96%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.96%   |
| Samsung Apple PCIe SSD                                                         | 2         | 0.96%   |
| Micron NVMe Storage Controller                                                 | 2         | 0.96%   |
| Micron 2200S NVMe SSD                                                          | 2         | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.96%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 103       | 53.37%  |
| NVMe | 70        | 36.27%  |
| RAID | 19        | 9.84%   |
| IDE  | 1         | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 104       | 75.91%  |
| AMD    | 33        | 24.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.17%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 2.17%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 3         | 2.17%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 1.45%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 1.45%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 1.45%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 2         | 1.45%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.45%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 1.45%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 1.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.45%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 1.45%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.45%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 1.45%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.45%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.45%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.45%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz            | 1         | 0.72%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1         | 0.72%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.72%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1         | 0.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.72%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.72%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 37        | 26.81%  |
| Intel Core i5     | 37        | 26.81%  |
| AMD Ryzen 5       | 15        | 10.87%  |
| Other             | 11        | 7.97%   |
| Intel Core i3     | 10        | 7.25%   |
| AMD Ryzen 7       | 10        | 7.25%   |
| Intel Celeron     | 3         | 2.17%   |
| Intel Xeon        | 2         | 1.45%   |
| AMD Ryzen 3       | 2         | 1.45%   |
| AMD A8            | 2         | 1.45%   |
| Intel Pentium     | 1         | 0.72%   |
| Intel Genuine     | 1         | 0.72%   |
| Intel Core 2 Quad | 1         | 0.72%   |
| Intel Core 2 Duo  | 1         | 0.72%   |
| AMD Ryzen 9       | 1         | 0.72%   |
| AMD E1            | 1         | 0.72%   |
| AMD Athlon        | 1         | 0.72%   |
| AMD A6            | 1         | 0.72%   |
| AMD A4            | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 56        | 40.58%  |
| 2      | 42        | 30.43%  |
| 6      | 23        | 16.67%  |
| 8      | 13        | 9.42%   |
| 12     | 2         | 1.45%   |
| 16     | 1         | 0.72%   |
| 14     | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 99.27%  |
| 2      | 1         | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 115       | 83.33%  |
| 1      | 23        | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 31.21%  |
| 0x906ea    | 7         | 4.96%   |
| 0x806c1    | 7         | 4.96%   |
| 0x806ec    | 6         | 4.26%   |
| 0x306a9    | 6         | 4.26%   |
| 0x806e9    | 5         | 3.55%   |
| 0x506e3    | 5         | 3.55%   |
| 0x08701021 | 5         | 3.55%   |
| 0x906e9    | 4         | 2.84%   |
| 0x806eb    | 3         | 2.13%   |
| 0x306c3    | 3         | 2.13%   |
| 0x206a7    | 3         | 2.13%   |
| 0x0a201016 | 3         | 2.13%   |
| 0x08108109 | 3         | 2.13%   |
| 0x906ed    | 2         | 1.42%   |
| 0x906eb    | 2         | 1.42%   |
| 0x706a8    | 2         | 1.42%   |
| 0x40651    | 2         | 1.42%   |
| 0x106e5    | 2         | 1.42%   |
| 0x1067a    | 2         | 1.42%   |
| 0x0a20120a | 2         | 1.42%   |
| 0xa0653    | 1         | 0.71%   |
| 0xa0652    | 1         | 0.71%   |
| 0x906a3    | 1         | 0.71%   |
| 0x806d1    | 1         | 0.71%   |
| 0x706e5    | 1         | 0.71%   |
| 0x406e3    | 1         | 0.71%   |
| 0x40661    | 1         | 0.71%   |
| 0x306f2    | 1         | 0.71%   |
| 0x306d4    | 1         | 0.71%   |
| 0x20655    | 1         | 0.71%   |
| 0x20652    | 1         | 0.71%   |
| 0x0a50000b | 1         | 0.71%   |
| 0x0a404102 | 1         | 0.71%   |
| 0x08701030 | 1         | 0.71%   |
| 0x08701013 | 1         | 0.71%   |
| 0x08608103 | 1         | 0.71%   |
| 0x08600106 | 1         | 0.71%   |
| 0x08108102 | 1         | 0.71%   |
| 0x0810100b | 1         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 26.81%  |
| Haswell          | 14        | 10.14%  |
| Zen 2            | 10        | 7.25%   |
| IvyBridge        | 10        | 7.25%   |
| Skylake          | 9         | 6.52%   |
| Zen 3            | 8         | 5.8%    |
| TigerLake        | 8         | 5.8%    |
| Zen+             | 7         | 5.07%   |
| SandyBridge      | 5         | 3.62%   |
| Nehalem          | 3         | 2.17%   |
| Icelake          | 3         | 2.17%   |
| Goldmont plus    | 3         | 2.17%   |
| CometLake        | 3         | 2.17%   |
| Broadwell        | 3         | 2.17%   |
| Unknown          | 3         | 2.17%   |
| Zen              | 2         | 1.45%   |
| Westmere         | 2         | 1.45%   |
| Penryn           | 2         | 1.45%   |
| Excavator        | 2         | 1.45%   |
| Piledriver       | 1         | 0.72%   |
| K10 Llano        | 1         | 0.72%   |
| Bobcat           | 1         | 0.72%   |
| Alderlake Hybrid | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 80        | 43.48%  |
| Nvidia            | 70        | 38.04%  |
| AMD               | 33        | 17.93%  |
| ASPEED Technology | 1         | 0.54%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 2.69%   |
| Intel HD Graphics 620                                                       | 5         | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 2.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 2.15%   |
| Intel UHD Graphics 620                                                      | 4         | 2.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 2.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 2.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 3         | 1.61%   |
| Nvidia GP108M [GeForce MX250]                                               | 3         | 1.61%   |
| Nvidia GP108M [GeForce MX150]                                               | 3         | 1.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3         | 1.61%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 3         | 1.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 3         | 1.61%   |
| Intel HD Graphics 630                                                       | 3         | 1.61%   |
| Intel HD Graphics 5500                                                      | 3         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.61%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.61%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2         | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 1.08%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1.08%   |
| Nvidia GM108M [GeForce 940MX]                                               | 2         | 1.08%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 2         | 1.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 1.08%   |
| AMD Renoir                                                                  | 2         | 1.08%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 40        | 28.99%  |
| Intel + Nvidia  | 35        | 25.36%  |
| 1 x Nvidia      | 27        | 19.57%  |
| 1 x AMD         | 23        | 16.67%  |
| AMD + Nvidia    | 6         | 4.35%   |
| Intel + AMD     | 3         | 2.17%   |
| 2 x Nvidia      | 1         | 0.72%   |
| 2 x Intel       | 1         | 0.72%   |
| 2 x AMD         | 1         | 0.72%   |
| Nvidia + ASPEED | 1         | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 88        | 63.31%  |
| Proprietary | 49        | 35.25%  |
| Unknown     | 2         | 1.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 58.27%  |
| 1.01-2.0   | 19        | 13.67%  |
| 7.01-8.0   | 10        | 7.19%   |
| 3.01-4.0   | 9         | 6.47%   |
| 5.01-6.0   | 7         | 5.04%   |
| 0.01-0.5   | 7         | 5.04%   |
| 8.01-16.0  | 4         | 2.88%   |
| 0.51-1.0   | 2         | 1.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 22        | 14.38%  |
| AU Optronics         | 21        | 13.73%  |
| BOE                  | 17        | 11.11%  |
| LG Display           | 15        | 9.8%    |
| Chimei Innolux       | 15        | 9.8%    |
| Acer                 | 6         | 3.92%   |
| Hewlett-Packard      | 5         | 3.27%   |
| Goldstar             | 4         | 2.61%   |
| Dell                 | 4         | 2.61%   |
| AOC                  | 4         | 2.61%   |
| Ancor Communications | 4         | 2.61%   |
| Sharp                | 3         | 1.96%   |
| PANDA                | 3         | 1.96%   |
| Lenovo               | 3         | 1.96%   |
| Apple                | 3         | 1.96%   |
| Philips              | 2         | 1.31%   |
| Iiyama               | 2         | 1.31%   |
| Unknown              | 1         | 0.65%   |
| Toshiba              | 1         | 0.65%   |
| TMX                  | 1         | 0.65%   |
| Sony                 | 1         | 0.65%   |
| Sceptre Tech         | 1         | 0.65%   |
| MSI                  | 1         | 0.65%   |
| LGD                  | 1         | 0.65%   |
| Konka                | 1         | 0.65%   |
| Kogan                | 1         | 0.65%   |
| KOC                  | 1         | 0.65%   |
| JRY                  | 1         | 0.65%   |
| ITE                  | 1         | 0.65%   |
| Idek Iiyama          | 1         | 0.65%   |
| Hitachi              | 1         | 0.65%   |
| Gigabyte Technology  | 1         | 0.65%   |
| FOX                  | 1         | 0.65%   |
| CSO                  | 1         | 0.65%   |
| BenQ                 | 1         | 0.65%   |
| ASUSTek Computer     | 1         | 0.65%   |
| Unknown              | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 1.91%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch       | 2         | 1.27%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 1.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.27%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.27%   |
| Unknown LCD Monitor SAMSUNG 1360x768                                    | 1         | 0.64%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.64%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.64%   |
| Sony LCD Monitor AVSYSTEM 1280x720                                      | 1         | 0.64%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.64%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.64%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.64%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.64%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.64%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.64%   |
| Samsung Electronics SA300/350/360 SAM07D6 1920x1080 531x299mm 24.0-inch | 1         | 0.64%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.64%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.64%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.64%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 0.64%   |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch     | 1         | 0.64%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch      | 1         | 0.64%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1         | 0.64%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch                 | 1         | 0.64%   |
| Philips 224E PHLC053 1920x1080 480x270mm 21.7-inch                      | 1         | 0.64%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.64%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 57.93%  |
| 1366x768 (WXGA)    | 19        | 13.1%   |
| 3840x2160 (4K)     | 8         | 5.52%   |
| 2560x1440 (QHD)    | 6         | 4.14%   |
| 3440x1440          | 5         | 3.45%   |
| 1600x900 (HD+)     | 5         | 3.45%   |
| 2560x1080          | 3         | 2.07%   |
| 1680x1050 (WSXGA+) | 2         | 1.38%   |
| 1360x768           | 2         | 1.38%   |
| 3840x2400          | 1         | 0.69%   |
| 3840x1080          | 1         | 0.69%   |
| 3200x1800 (QHD+)   | 1         | 0.69%   |
| 2880x1800          | 1         | 0.69%   |
| 2560x1600          | 1         | 0.69%   |
| 2160x1440          | 1         | 0.69%   |
| 1920x540           | 1         | 0.69%   |
| 1920x1200 (WUXGA)  | 1         | 0.69%   |
| 1440x900 (WXGA+)   | 1         | 0.69%   |
| 1280x720 (HD)      | 1         | 0.69%   |
| 1280x1024 (SXGA)   | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 52        | 33.99%  |
| 27      | 13        | 8.5%    |
| 14      | 13        | 8.5%    |
| 23      | 11        | 7.19%   |
| 13      | 10        | 6.54%   |
| 21      | 9         | 5.88%   |
| 24      | 8         | 5.23%   |
| 34      | 6         | 3.92%   |
| Unknown | 6         | 3.92%   |
| 84      | 4         | 2.61%   |
| 31      | 4         | 2.61%   |
| 17      | 4         | 2.61%   |
| 28      | 2         | 1.31%   |
| 20      | 2         | 1.31%   |
| 18      | 2         | 1.31%   |
| 16      | 2         | 1.31%   |
| 72      | 1         | 0.65%   |
| 52      | 1         | 0.65%   |
| 48      | 1         | 0.65%   |
| 33      | 1         | 0.65%   |
| 12      | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 47.37%  |
| 501-600     | 30        | 19.74%  |
| 401-500     | 13        | 8.55%   |
| 701-800     | 7         | 4.61%   |
| 601-700     | 6         | 3.95%   |
| 351-400     | 6         | 3.95%   |
| Unknown     | 6         | 3.95%   |
| 201-300     | 5         | 3.29%   |
| 1501-2000   | 5         | 3.29%   |
| 1001-1500   | 2         | 1.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 83.7%   |
| 21/9    | 8         | 5.93%   |
| 16/10   | 6         | 4.44%   |
| Unknown | 5         | 3.7%    |
| 5/4     | 1         | 0.74%   |
| 32/9    | 1         | 0.74%   |
| 3/2     | 1         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 35.1%   |
| 201-250        | 25        | 16.56%  |
| 81-90          | 20        | 13.25%  |
| 301-350        | 13        | 8.61%   |
| 351-500        | 11        | 7.28%   |
| More than 1000 | 6         | 3.97%   |
| Unknown        | 6         | 3.97%   |
| 121-130        | 4         | 2.65%   |
| 71-80          | 3         | 1.99%   |
| 251-300        | 3         | 1.99%   |
| 151-200        | 3         | 1.99%   |
| 61-70          | 1         | 0.66%   |
| 141-150        | 1         | 0.66%   |
| 111-120        | 1         | 0.66%   |
| 501-1000       | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 55        | 37.67%  |
| 51-100        | 40        | 27.4%   |
| 101-120       | 32        | 21.92%  |
| 161-240       | 7         | 4.79%   |
| Unknown       | 6         | 4.11%   |
| More than 240 | 3         | 2.05%   |
| 1-50          | 3         | 2.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 79.71%  |
| 2     | 25        | 18.12%  |
| 0     | 2         | 1.45%   |
| 3     | 1         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 77        | 39.29%  |
| Intel                             | 76        | 38.78%  |
| Qualcomm Atheros                  | 11        | 5.61%   |
| Broadcom                          | 5         | 2.55%   |
| MediaTek                          | 4         | 2.04%   |
| Broadcom Limited                  | 4         | 2.04%   |
| ASIX Electronics                  | 3         | 1.53%   |
| TP-Link                           | 2         | 1.02%   |
| Samsung Electronics               | 2         | 1.02%   |
| Ralink Technology                 | 2         | 1.02%   |
| Ralink                            | 2         | 1.02%   |
| Ericsson Business Mobile Networks | 2         | 1.02%   |
| Sierra Wireless                   | 1         | 0.51%   |
| Qualcomm Atheros Communications   | 1         | 0.51%   |
| Qualcomm                          | 1         | 0.51%   |
| NetGear                           | 1         | 0.51%   |
| Microsoft                         | 1         | 0.51%   |
| Marvell Technology Group          | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 58        | 24.47%  |
| Intel Wi-Fi 6 AX200                                                | 8         | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 7         | 2.95%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 2.53%   |
| Intel I211 Gigabit Network Connection                              | 6         | 2.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 5         | 2.11%   |
| Realtek RTL8125 2.5GbE Controller                                  | 5         | 2.11%   |
| Intel Wireless 8265 / 8275                                         | 5         | 2.11%   |
| Intel Wireless 7260                                                | 5         | 2.11%   |
| Intel Ethernet Connection (2) I219-V                               | 5         | 2.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 4         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 3         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 3         | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 1.27%   |
| Intel Wireless 7265                                                | 3         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 1.27%   |
| Intel Centrino Wireless-N 2230                                     | 3         | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 2         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 0.84%   |
| Intel Wireless-AC 9260                                             | 2         | 0.84%   |
| Intel Wireless 8260                                                | 2         | 0.84%   |
| Intel Ethernet Connection I217-LM                                  | 2         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                               | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 2         | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 2         | 0.84%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 2         | 0.84%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 0.84%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1         | 0.42%   |
| TP-Link 802.11ac NIC                                               | 1         | 0.42%   |
| Sierra Wireless EM7455                                             | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 55.26%  |
| Realtek Semiconductor           | 20        | 17.54%  |
| Qualcomm Atheros                | 10        | 8.77%   |
| MediaTek                        | 4         | 3.51%   |
| Broadcom Limited                | 4         | 3.51%   |
| Broadcom                        | 3         | 2.63%   |
| TP-Link                         | 2         | 1.75%   |
| Ralink Technology               | 2         | 1.75%   |
| Ralink                          | 2         | 1.75%   |
| Sierra Wireless                 | 1         | 0.88%   |
| Qualcomm Atheros Communications | 1         | 0.88%   |
| NetGear                         | 1         | 0.88%   |
| Microsoft                       | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 8         | 7.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 7         | 6.14%   |
| Intel Wi-Fi 6 AX201                                                       | 6         | 5.26%   |
| Intel Wireless 8265 / 8275                                                | 5         | 4.39%   |
| Intel Wireless 7260                                                       | 5         | 4.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 5         | 4.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 4.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 4         | 3.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 3.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 3         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 3         | 2.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 3         | 2.63%   |
| Intel Wireless 7265                                                       | 3         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 3         | 2.63%   |
| Intel Centrino Wireless-N 2230                                            | 3         | 2.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 1.75%   |
| Intel Wireless-AC 9260                                                    | 2         | 1.75%   |
| Intel Wireless 8260                                                       | 2         | 1.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                          | 2         | 1.75%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 1.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 0.88%   |
| TP-Link 802.11ac NIC                                                      | 1         | 0.88%   |
| Sierra Wireless EM7455                                                    | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                  | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.88%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 0.88%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                           | 1         | 0.88%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.88%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 1         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 0.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1         | 0.88%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.88%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 59.83%  |
| Intel                    | 37        | 31.62%  |
| Broadcom                 | 3         | 2.56%   |
| ASIX Electronics         | 3         | 2.56%   |
| Qualcomm Atheros         | 2         | 1.71%   |
| Qualcomm                 | 1         | 0.85%   |
| Marvell Technology Group | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 48.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 6.72%   |
| Intel I211 Gigabit Network Connection                             | 6         | 5.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.2%    |
| Intel Ethernet Connection (2) I219-V                              | 5         | 4.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.36%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.52%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.68%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.68%   |
| Qualcomm Nokia G400 5G                                            | 1         | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.84%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.84%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.84%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.84%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.84%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.84%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.84%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.84%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.84%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.84%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 49.12%  |
| Ethernet | 112       | 49.12%  |
| Modem    | 4         | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 63.38%  |
| Ethernet | 52        | 36.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 71        | 51.45%  |
| 1     | 62        | 44.93%  |
| 3     | 4         | 2.9%    |
| 0     | 1         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 68.84%  |
| Yes  | 43        | 31.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 52%     |
| Realtek Semiconductor           | 12        | 12%     |
| Broadcom                        | 7         | 7%      |
| Cambridge Silicon Radio         | 6         | 6%      |
| Qualcomm Atheros Communications | 5         | 5%      |
| IMC Networks                    | 5         | 5%      |
| Foxconn / Hon Hai               | 3         | 3%      |
| Lite-On Technology              | 2         | 2%      |
| ASUSTek Computer                | 2         | 2%      |
| Apple                           | 2         | 2%      |
| Toshiba                         | 1         | 1%      |
| Realtek                         | 1         | 1%      |
| MediaTek                        | 1         | 1%      |
| Dell                            | 1         | 1%      |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 16%     |
| Intel Bluetooth wireless interface                  | 12        | 12%     |
| Intel AX201 Bluetooth                               | 8         | 8%      |
| Intel AX200 Bluetooth                               | 8         | 8%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 6%      |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5%      |
| Realtek Bluetooth Radio                             | 5         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 3%      |
| IMC Networks Bluetooth Radio                        | 3         | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2%      |
| IMC Networks Wireless_Device                        | 2         | 2%      |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2%      |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1%      |
| Realtek RTL8821A Bluetooth                          | 1         | 1%      |
| Realtek Bluetooth Radio                             | 1         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1%      |
| MediaTek Wireless_Device                            | 1         | 1%      |
| Lite-On Bluetooth Device                            | 1         | 1%      |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1%      |
| Intel Bluetooth Device                              | 1         | 1%      |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1%      |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1%      |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1%      |
| Broadcom HP Portable Bumble Bee                     | 1         | 1%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1%      |
| Broadcom BCM2045A0                                  | 1         | 1%      |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1%      |
| ASUS Bluetooth Radio                                | 1         | 1%      |
| Apple Bluetooth USB Host Controller                 | 1         | 1%      |
| Apple Bluetooth Host Controller                     | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 104       | 49.06%  |
| Nvidia                     | 47        | 22.17%  |
| AMD                        | 36        | 16.98%  |
| Corsair                    | 3         | 1.42%   |
| C-Media Electronics        | 3         | 1.42%   |
| Razer USA                  | 2         | 0.94%   |
| Kingston Technology        | 2         | 0.94%   |
| GN Netcom                  | 2         | 0.94%   |
| Tenx Technology            | 1         | 0.47%   |
| Samsung Electronics        | 1         | 0.47%   |
| Realtek Semiconductor      | 1         | 0.47%   |
| PreSonus Audio Electronics | 1         | 0.47%   |
| Plantronics                | 1         | 0.47%   |
| Logitech                   | 1         | 0.47%   |
| Lenovo                     | 1         | 0.47%   |
| Hewlett-Packard            | 1         | 0.47%   |
| Generalplus Technology     | 1         | 0.47%   |
| ELMCU                      | 1         | 0.47%   |
| Barco Display Systems      | 1         | 0.47%   |
| ASUSTek Computer           | 1         | 0.47%   |
| Astro Gaming               | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 5.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 4.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.38%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 3.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.19%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 2.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.99%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.2%    |
| Intel CM238 HD Audio Controller                                            | 3         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.2%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.2%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.2%    |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.2%    |
| AMD FCH Azalia Controller                                                  | 3         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 26.28%  |
| SK hynix            | 32        | 23.36%  |
| Micron Technology   | 14        | 10.22%  |
| Crucial             | 11        | 8.03%   |
| Corsair             | 11        | 8.03%   |
| Kingston            | 8         | 5.84%   |
| G.Skill             | 6         | 4.38%   |
| Unknown             | 5         | 3.65%   |
| Ramaxel Technology  | 5         | 3.65%   |
| Team                | 2         | 1.46%   |
| Unifosa             | 1         | 0.73%   |
| Transcend           | 1         | 0.73%   |
| PNY                 | 1         | 0.73%   |
| Nanya Technology    | 1         | 0.73%   |
| GeIL                | 1         | 0.73%   |
| Elpida              | 1         | 0.73%   |
| A-DATA Technology   | 1         | 0.73%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 4         | 2.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 2.05%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.37%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.37%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 1.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.37%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 2         | 1.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.37%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 2         | 1.37%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s  | 2         | 1.37%   |
| Kingston RAM KHX2133C14/16G 16384MB DIMM DDR4 2176MT/s       | 2         | 1.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s     | 2         | 1.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 0.68%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.68%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1         | 0.68%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s            | 1         | 0.68%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s             | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 1         | 0.68%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.68%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                | 1         | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s      | 1         | 0.68%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1         | 0.68%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 0.68%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1         | 0.68%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 73        | 62.93%  |
| DDR3   | 30        | 25.86%  |
| LPDDR4 | 3         | 2.59%   |
| SDRAM  | 2         | 1.72%   |
| LPDDR3 | 2         | 1.72%   |
| DDR5   | 2         | 1.72%   |
| DDR    | 2         | 1.72%   |
| LPDDR5 | 1         | 0.86%   |
| DDR2   | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 57.26%  |
| DIMM         | 38        | 32.48%  |
| Row Of Chips | 11        | 9.4%    |
| Chip         | 1         | 0.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 57        | 45.6%   |
| 4096  | 39        | 31.2%   |
| 16384 | 21        | 16.8%   |
| 2048  | 6         | 4.8%    |
| 32768 | 1         | 0.8%    |
| 1024  | 1         | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 29        | 22.14%  |
| 3200  | 23        | 17.56%  |
| 1600  | 22        | 16.79%  |
| 2400  | 9         | 6.87%   |
| 2133  | 6         | 4.58%   |
| 1333  | 6         | 4.58%   |
| 3600  | 4         | 3.05%   |
| 3266  | 4         | 3.05%   |
| 2933  | 3         | 2.29%   |
| 1800  | 3         | 2.29%   |
| 4800  | 2         | 1.53%   |
| 4267  | 2         | 1.53%   |
| 3400  | 2         | 1.53%   |
| 2176  | 2         | 1.53%   |
| 800   | 2         | 1.53%   |
| 6400  | 1         | 0.76%   |
| 4400  | 1         | 0.76%   |
| 4199  | 1         | 0.76%   |
| 4133  | 1         | 0.76%   |
| 3800  | 1         | 0.76%   |
| 3467  | 1         | 0.76%   |
| 2747  | 1         | 0.76%   |
| 2666  | 1         | 0.76%   |
| 1867  | 1         | 0.76%   |
| 1450  | 1         | 0.76%   |
| 1334  | 1         | 0.76%   |
| 1067  | 1         | 0.76%   |

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
| IMC Networks                           | 21        | 23.6%   |
| Chicony Electronics                    | 17        | 19.1%   |
| Realtek Semiconductor                  | 8         | 8.99%   |
| Microdia                               | 6         | 6.74%   |
| Syntek                                 | 5         | 5.62%   |
| Bison Electronics                      | 5         | 5.62%   |
| Sunplus Innovation Technology          | 4         | 4.49%   |
| Quanta                                 | 4         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.49%   |
| Acer                                   | 4         | 4.49%   |
| Lite-On Technology                     | 2         | 2.25%   |
| Generalplus Technology                 | 2         | 2.25%   |
| Suyin                                  | 1         | 1.12%   |
| Sonix Technology                       | 1         | 1.12%   |
| Ricoh                                  | 1         | 1.12%   |
| Panasonic (Matsushita)                 | 1         | 1.12%   |
| Luxvisions Innotech Limited            | 1         | 1.12%   |
| Logitech                               | 1         | 1.12%   |
| Alpha Imaging Technology               | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 7         | 7.87%   |
| Syntek Integrated Camera                            | 5         | 5.62%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 5.62%   |
| Realtek Integrated_Webcam_HD                        | 4         | 4.49%   |
| Chicony Integrated Camera                           | 4         | 4.49%   |
| Quanta HP TrueVision HD Camera                      | 3         | 3.37%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.25%   |
| Lite-On Integrated Camera                           | 2         | 2.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 2.25%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.25%   |
| Chicony EasyCamera                                  | 2         | 2.25%   |
| Bison ThinkPad Integrated Camera                    | 2         | 2.25%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.12%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.12%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.12%   |
| Sunplus HP Truevision HD                            | 1         | 1.12%   |
| Sunplus 1080p FHD Camera                            | 1         | 1.12%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.12%   |
| Ricoh Integrated Webcam                             | 1         | 1.12%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.12%   |
| Realtek Integrated Webcam                           | 1         | 1.12%   |
| Realtek EasyCamera                                  | 1         | 1.12%   |
| Realtek Built-In Video Camera                       | 1         | 1.12%   |
| Quanta HD User Facing                               | 1         | 1.12%   |
| Panasonic (Matsushita) TY-CC20W                     | 1         | 1.12%   |
| Microdia Webcam Vitade AF                           | 1         | 1.12%   |
| Microdia USB 2.0 Camera                             | 1         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 1.12%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.12%   |
| Logitech Webcam C600                                | 1         | 1.12%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.12%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.12%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.12%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 1         | 1.12%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.12%   |
| IMC Networks HD Camera                              | 1         | 1.12%   |
| IMC Networks EasyCamera                             | 1         | 1.12%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.12%   |
| Generalplus campark PC04                            | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 40%     |
| Synaptics                  | 3         | 20%     |
| Shenzhen Goodix Technology | 3         | 20%     |
| Elan Microelectronics      | 2         | 13.33%  |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI                   | 2         | 13.33%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 6.67%   |
| Synaptics WBDI                                    | 1         | 6.67%   |
| Synaptics  WBDI                                   | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 6.67%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 6.67%   |
| Elan fingerprint sensor [FeinTech FPS00200]       | 1         | 6.67%   |
| Elan ELAN:Fingerprint                             | 1         | 6.67%   |
| AuthenTec Fingerprint Sensor                      | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 30%     |
| Alcor Micro | 3         | 30%     |
| Upek        | 2         | 20%     |
| Yubico.com  | 1         | 10%     |
| Clay Logic  | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 20%     |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 10%     |
| Clay Logic Nitrokey Pro                                    | 1         | 10%     |
| Broadcom 58200                                             | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 98        | 71.01%  |
| 1     | 33        | 23.91%  |
| 2     | 7         | 5.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 15        | 32.61%  |
| Graphics card         | 10        | 21.74%  |
| Chipcard              | 8         | 17.39%  |
| Multimedia controller | 4         | 8.7%    |
| Net/wireless          | 2         | 4.35%   |
| Camera                | 2         | 4.35%   |
| Bluetooth             | 2         | 4.35%   |
| Unassigned class      | 1         | 2.17%   |
| Storage               | 1         | 2.17%   |
| Network               | 1         | 2.17%   |

