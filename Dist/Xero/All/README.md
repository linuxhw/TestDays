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

Total: 175

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Xero Rolling | 119       | 90.15%  |
| Xero         | 13        | 9.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 131       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.16.15-arch1-1       | 6         | 4.23%   |
| 6.1.12-arch1-1        | 5         | 3.52%   |
| 6.2.6-arch1-1         | 4         | 2.82%   |
| 6.0.12-arch1-1        | 4         | 2.82%   |
| 5.18.16-arch1-1       | 4         | 2.82%   |
| 6.1.1-arch1-1         | 3         | 2.11%   |
| 5.17.9-arch1-1        | 3         | 2.11%   |
| 5.16.2-arch1-1        | 3         | 2.11%   |
| 5.16.1-arch1-1        | 3         | 2.11%   |
| 5.15.33-1-lts         | 3         | 2.11%   |
| 5.14.14-arch1-1       | 3         | 2.11%   |
| 6.3.6-arch1-1         | 2         | 1.41%   |
| 6.2.8-arch1-1         | 2         | 1.41%   |
| 6.2.7-arch1-1         | 2         | 1.41%   |
| 6.2.12-arch1-1        | 2         | 1.41%   |
| 6.0.7-arch1-1         | 2         | 1.41%   |
| 5.19.9-arch1-1        | 2         | 1.41%   |
| 5.19.13-arch1-1       | 2         | 1.41%   |
| 5.19.12-arch1-1       | 2         | 1.41%   |
| 5.18.3-arch1-1        | 2         | 1.41%   |
| 5.18.11-arch1-1       | 2         | 1.41%   |
| 5.17.5-arch1-1        | 2         | 1.41%   |
| 5.17.1-arch1-1        | 2         | 1.41%   |
| 5.16.8-arch1-1        | 2         | 1.41%   |
| 5.16.16-arch1-1       | 2         | 1.41%   |
| 5.16.13-arch1-1       | 2         | 1.41%   |
| 5.16.12-arch1-1       | 2         | 1.41%   |
| 5.15.10-arch1-1       | 2         | 1.41%   |
| 5.14.8-zen1-1-zen     | 2         | 1.41%   |
| 6.3.4-arch1-1         | 1         | 0.7%    |
| 6.3.2-arch1-1         | 1         | 0.7%    |
| 6.3.1-arch1-1         | 1         | 0.7%    |
| 6.2.9-arch1-1         | 1         | 0.7%    |
| 6.2.2-arch2-1         | 1         | 0.7%    |
| 6.2.13-arch1-1        | 1         | 0.7%    |
| 6.2.1-x64v1-xanmod1-1 | 1         | 0.7%    |
| 6.1.8-arch1-1         | 1         | 0.7%    |
| 6.1.7-arch1-1         | 1         | 0.7%    |
| 6.1.6-arch1-3         | 1         | 0.7%    |
| 6.1.6-arch1-1         | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 4.23%   |
| 6.1.12  | 5         | 3.52%   |
| 6.2.6   | 4         | 2.82%   |
| 6.0.12  | 4         | 2.82%   |
| 5.18.16 | 4         | 2.82%   |
| 5.14.14 | 4         | 2.82%   |
| 6.1.1   | 3         | 2.11%   |
| 5.19.13 | 3         | 2.11%   |
| 5.17.9  | 3         | 2.11%   |
| 5.16.2  | 3         | 2.11%   |
| 5.16.16 | 3         | 2.11%   |
| 5.16.1  | 3         | 2.11%   |
| 5.15.33 | 3         | 2.11%   |
| 5.15.12 | 3         | 2.11%   |
| 5.14.8  | 3         | 2.11%   |
| 5.14.16 | 3         | 2.11%   |
| 6.3.6   | 2         | 1.41%   |
| 6.2.8   | 2         | 1.41%   |
| 6.2.7   | 2         | 1.41%   |
| 6.2.12  | 2         | 1.41%   |
| 6.1.6   | 2         | 1.41%   |
| 6.0.8   | 2         | 1.41%   |
| 6.0.7   | 2         | 1.41%   |
| 6.0.6   | 2         | 1.41%   |
| 6.0.2   | 2         | 1.41%   |
| 5.19.9  | 2         | 1.41%   |
| 5.19.12 | 2         | 1.41%   |
| 5.18.3  | 2         | 1.41%   |
| 5.18.11 | 2         | 1.41%   |
| 5.17.5  | 2         | 1.41%   |
| 5.17.1  | 2         | 1.41%   |
| 5.16.8  | 2         | 1.41%   |
| 5.16.13 | 2         | 1.41%   |
| 5.16.12 | 2         | 1.41%   |
| 5.15.13 | 2         | 1.41%   |
| 5.15.11 | 2         | 1.41%   |
| 5.15.10 | 2         | 1.41%   |
| 6.3.4   | 1         | 0.7%    |
| 6.3.2   | 1         | 0.7%    |
| 6.3.1   | 1         | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 16.55%  |
| 5.15    | 18        | 12.95%  |
| 6.0     | 15        | 10.79%  |
| 6.2     | 14        | 10.07%  |
| 6.1     | 14        | 10.07%  |
| 5.14    | 13        | 9.35%   |
| 5.19    | 11        | 7.91%   |
| 5.18    | 11        | 7.91%   |
| 5.17    | 8         | 5.76%   |
| 6.3     | 5         | 3.6%    |
| 5.10    | 3         | 2.16%   |
| 5.13    | 2         | 1.44%   |
| 5.12    | 1         | 0.72%   |
| 5.11    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 131       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| KDE5   | 123       | 92.48%  |
| XFCE   | 4         | 3.01%   |
| GNOME  | 4         | 3.01%   |
| LeftWM | 1         | 0.75%   |
| KDE    | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 117       | 88.64%  |
| Wayland | 13        | 9.85%   |
| Tty     | 2         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 91        | 67.41%  |
| Unknown | 26        | 19.26%  |
| LightDM | 15        | 11.11%  |
| GDM     | 2         | 1.48%   |
| TDM     | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 68        | 51.52%  |
| en_IN | 11        | 8.33%   |
| de_DE | 8         | 6.06%   |
| en_GB | 6         | 4.55%   |
| C     | 6         | 4.55%   |
| pl_PL | 5         | 3.79%   |
| ru_RU | 4         | 3.03%   |
| it_IT | 3         | 2.27%   |
| es_MX | 3         | 2.27%   |
| en_AU | 3         | 2.27%   |
| fr_FR | 2         | 1.52%   |
| vi_VN | 1         | 0.76%   |
| tr_TR | 1         | 0.76%   |
| sv_SE | 1         | 0.76%   |
| hu_HU | 1         | 0.76%   |
| es_CL | 1         | 0.76%   |
| en_ZA | 1         | 0.76%   |
| en_IL | 1         | 0.76%   |
| en_DK | 1         | 0.76%   |
| en_CA | 1         | 0.76%   |
| en_AG | 1         | 0.76%   |
| de_CH | 1         | 0.76%   |
| de_AT | 1         | 0.76%   |
| ba_RU | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 83        | 62.88%  |
| BIOS | 49        | 37.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 63        | 47.37%  |
| Xfs     | 41        | 30.83%  |
| Ext4    | 22        | 16.54%  |
| Overlay | 7         | 5.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 91        | 68.94%  |
| Unknown | 26        | 19.7%   |
| MBR     | 15        | 11.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 75.74%  |
| Yes       | 33        | 24.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 62.88%  |
| Yes       | 49        | 37.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 34        | 25.95%  |
| Lenovo              | 26        | 19.85%  |
| Dell                | 18        | 13.74%  |
| Hewlett-Packard     | 16        | 12.21%  |
| MSI                 | 7         | 5.34%   |
| Acer                | 7         | 5.34%   |
| Gigabyte Technology | 4         | 3.05%   |
| Pegatron            | 3         | 2.29%   |
| ASRock              | 3         | 2.29%   |
| HUAWEI              | 2         | 1.53%   |
| Apple               | 2         | 1.53%   |
| Unknown             | 2         | 1.53%   |
| Toshiba             | 1         | 0.76%   |
| Samsung Electronics | 1         | 0.76%   |
| Medion              | 1         | 0.76%   |
| JINGSHA             | 1         | 0.76%   |
| Biostar             | 1         | 0.76%   |
| BESSTAR Tech        | 1         | 0.76%   |
| Aquarius            | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 2.29%   |
| Unknown                                    | 3         | 2.29%   |
| MSI MS-7971                                | 2         | 1.53%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 1.53%   |
| Toshiba TECRA A11                          | 1         | 0.76%   |
| Samsung 950QED                             | 1         | 0.76%   |
| Pegatron p6-2026                           | 1         | 0.76%   |
| Pegatron D15K                              | 1         | 0.76%   |
| Pegatron 20-b010                           | 1         | 0.76%   |
| MSI MS-7C91                                | 1         | 0.76%   |
| MSI MS-7B61                                | 1         | 0.76%   |
| MSI Katana GF66 11UE                       | 1         | 0.76%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.76%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.76%   |
| Medion P6816                               | 1         | 0.76%   |
| Lenovo Yoga 730-15IKB 81CU                 | 1         | 0.76%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 0.76%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.76%   |
| Lenovo ThinkPad Yoga 370 20JJS0SB00        | 1         | 0.76%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.76%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.76%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.76%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 0.76%   |
| Lenovo ThinkPad T440 20B7A0CYMH            | 1         | 0.76%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 0.76%   |
| Lenovo ThinkPad P51 20HJS11Y00             | 1         | 0.76%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 0.76%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 0.76%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 0.76%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.76%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 0.76%   |
| Lenovo IdeaPad S540-15IML D 81NG           | 1         | 0.76%   |
| Lenovo IdeaPad S340-15IIL 81VW             | 1         | 0.76%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 0.76%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.76%   |
| Lenovo IdeaPad C340-14IML 81TK             | 1         | 0.76%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 0.76%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 0.76%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 10        | 7.63%   |
| Lenovo IdeaPad     | 9         | 6.87%   |
| ASUS ROG           | 8         | 6.11%   |
| Acer Aspire        | 7         | 5.34%   |
| ASUS TUF           | 6         | 4.58%   |
| Dell Latitude      | 5         | 3.82%   |
| Lenovo Legion      | 4         | 3.05%   |
| Dell Precision     | 4         | 3.05%   |
| ASUS VivoBook      | 4         | 3.05%   |
| HP Pavilion        | 3         | 2.29%   |
| HP Laptop          | 3         | 2.29%   |
| Dell Inspiron      | 3         | 2.29%   |
| ASUS PRIME         | 3         | 2.29%   |
| ASUS ASUS          | 3         | 2.29%   |
| Unknown            | 3         | 2.29%   |
| MSI MS-7971        | 2         | 1.53%   |
| Lenovo Yoga        | 2         | 1.53%   |
| Dell OptiPlex      | 2         | 1.53%   |
| Toshiba TECRA      | 1         | 0.76%   |
| Samsung 950QED     | 1         | 0.76%   |
| Pegatron p6-2026   | 1         | 0.76%   |
| Pegatron D15K      | 1         | 0.76%   |
| Pegatron 20-b010   | 1         | 0.76%   |
| MSI MS-7C91        | 1         | 0.76%   |
| MSI MS-7B61        | 1         | 0.76%   |
| MSI Katana         | 1         | 0.76%   |
| MSI GP73           | 1         | 0.76%   |
| MSI GF63           | 1         | 0.76%   |
| Medion P6816       | 1         | 0.76%   |
| Lenovo Y520-15IKBN | 1         | 0.76%   |
| HUAWEI WRT-WX9     | 1         | 0.76%   |
| HUAWEI BOM-WXX9    | 1         | 0.76%   |
| HP ZBook           | 1         | 0.76%   |
| HP Z230            | 1         | 0.76%   |
| HP Victus          | 1         | 0.76%   |
| HP ProOne          | 1         | 0.76%   |
| HP ProBook         | 1         | 0.76%   |
| HP Notebook        | 1         | 0.76%   |
| HP ENVY            | 1         | 0.76%   |
| HP Compaq          | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 26        | 19.85%  |
| 2020 | 18        | 13.74%  |
| 2018 | 14        | 10.69%  |
| 2017 | 13        | 9.92%   |
| 2021 | 12        | 9.16%   |
| 2013 | 9         | 6.87%   |
| 2012 | 9         | 6.87%   |
| 2015 | 8         | 6.11%   |
| 2014 | 5         | 3.82%   |
| 2011 | 4         | 3.05%   |
| 2010 | 4         | 3.05%   |
| 2022 | 3         | 2.29%   |
| 2016 | 3         | 2.29%   |
| 2009 | 2         | 1.53%   |
| 2008 | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 76        | 58.02%  |
| Desktop     | 48        | 36.64%  |
| Convertible | 6         | 4.58%   |
| Server      | 1         | 0.76%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 131       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 131       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 37        | 28.24%  |
| 16.01-24.0  | 36        | 27.48%  |
| 8.01-16.0   | 25        | 19.08%  |
| 32.01-64.0  | 15        | 11.45%  |
| 3.01-4.0    | 13        | 9.92%   |
| 24.01-32.0  | 3         | 2.29%   |
| 64.01-256.0 | 2         | 1.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 43        | 30.71%  |
| 4.01-8.0   | 32        | 22.86%  |
| 1.01-2.0   | 28        | 20%     |
| 3.01-4.0   | 21        | 15%     |
| 8.01-16.0  | 8         | 5.71%   |
| 16.01-24.0 | 4         | 2.86%   |
| 0.51-1.0   | 2         | 1.43%   |
| 0.01-0.5   | 2         | 1.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 72        | 54.55%  |
| 2      | 33        | 25%     |
| 3      | 13        | 9.85%   |
| 4      | 7         | 5.3%    |
| 5      | 4         | 3.03%   |
| 6      | 2         | 1.52%   |
| 7      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 78.63%  |
| Yes       | 28        | 21.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 80.92%  |
| No        | 25        | 19.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 80.92%  |
| No        | 25        | 19.08%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 72.73%  |
| No        | 36        | 27.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 27        | 20.45%  |
| India                 | 13        | 9.85%   |
| Germany               | 11        | 8.33%   |
| Poland                | 6         | 4.55%   |
| Russia                | 5         | 3.79%   |
| Italy                 | 5         | 3.79%   |
| France                | 5         | 3.79%   |
| Canada                | 4         | 3.03%   |
| UK                    | 3         | 2.27%   |
| Turkey                | 3         | 2.27%   |
| Mexico                | 3         | 2.27%   |
| Greece                | 3         | 2.27%   |
| Australia             | 3         | 2.27%   |
| Sweden                | 2         | 1.52%   |
| Spain                 | 2         | 1.52%   |
| Pakistan              | 2         | 1.52%   |
| Norway                | 2         | 1.52%   |
| Netherlands           | 2         | 1.52%   |
| Lebanon               | 2         | 1.52%   |
| Hungary               | 2         | 1.52%   |
| Colombia              | 2         | 1.52%   |
| Chile                 | 2         | 1.52%   |
| Zambia                | 1         | 0.76%   |
| Vietnam               | 1         | 0.76%   |
| Togo                  | 1         | 0.76%   |
| Switzerland           | 1         | 0.76%   |
| South Africa          | 1         | 0.76%   |
| Romania               | 1         | 0.76%   |
| Portugal              | 1         | 0.76%   |
| Palestinian Territory | 1         | 0.76%   |
| Morocco               | 1         | 0.76%   |
| Mongolia              | 1         | 0.76%   |
| Malaysia              | 1         | 0.76%   |
| Israel                | 1         | 0.76%   |
| Indonesia             | 1         | 0.76%   |
| Egypt                 | 1         | 0.76%   |
| Denmark               | 1         | 0.76%   |
| Czechia               | 1         | 0.76%   |
| Cyprus                | 1         | 0.76%   |
| Brazil                | 1         | 0.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Longmont              | 4         | 3.03%   |
| Warsaw                | 2         | 1.52%   |
| Pune                  | 2         | 1.52%   |
| Phoenix               | 2         | 1.52%   |
| Madurai               | 2         | 1.52%   |
| Istanbul              | 2         | 1.52%   |
| Bremen                | 2         | 1.52%   |
| Berlin                | 2         | 1.52%   |
| Beirut                | 2         | 1.52%   |
| Zenica                | 1         | 0.76%   |
| Zell am See           | 1         | 0.76%   |
| Wroclaw               | 1         | 0.76%   |
| Wrexham               | 1         | 0.76%   |
| Wells                 | 1         | 0.76%   |
| Wangen                | 1         | 0.76%   |
| Vredenburg            | 1         | 0.76%   |
| Ulan Bator            | 1         | 0.76%   |
| Ufa                   | 1         | 0.76%   |
| Toronto               | 1         | 0.76%   |
| Tel Aviv              | 1         | 0.76%   |
| Taranto               | 1         | 0.76%   |
| Tangerang             | 1         | 0.76%   |
| Stuttgart             | 1         | 0.76%   |
| Stow                  | 1         | 0.76%   |
| Stockholm             | 1         | 0.76%   |
| Stavropol             | 1         | 0.76%   |
| Stagno                | 1         | 0.76%   |
| Springfield           | 1         | 0.76%   |
| Sonora                | 1         | 0.76%   |
| Silkeborg             | 1         | 0.76%   |
| Shadrinsk             | 1         | 0.76%   |
| Seattle               | 1         | 0.76%   |
| Santa Cruz            | 1         | 0.76%   |
| Sant Boi de Llobregat | 1         | 0.76%   |
| Salt Lake City        | 1         | 0.76%   |
| Ramallah              | 1         | 0.76%   |
| Poznan                | 1         | 0.76%   |
| Portland              | 1         | 0.76%   |
| Porcia                | 1         | 0.76%   |
| Pirmasens             | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 40        | 52     | 18.02%  |
| Seagate                     | 35        | 49     | 15.77%  |
| WDC                         | 28        | 38     | 12.61%  |
| Toshiba                     | 14        | 16     | 6.31%   |
| Kingston                    | 14        | 18     | 6.31%   |
| SanDisk                     | 10        | 12     | 4.5%    |
| Intel                       | 9         | 11     | 4.05%   |
| Unknown                     | 8         | 9      | 3.6%    |
| HGST                        | 6         | 6      | 2.7%    |
| Crucial                     | 6         | 8      | 2.7%    |
| SK hynix                    | 4         | 4      | 1.8%    |
| Micron Technology           | 4         | 6      | 1.8%    |
| KIOXIA                      | 4         | 5      | 1.8%    |
| China                       | 4         | 4      | 1.8%    |
| Transcend                   | 3         | 3      | 1.35%   |
| Phison                      | 3         | 3      | 1.35%   |
| Hitachi                     | 3         | 3      | 1.35%   |
| Micron/Crucial Technology   | 2         | 2      | 0.9%    |
| LITEON                      | 2         | 2      | 0.9%    |
| Intenso                     | 2         | 2      | 0.9%    |
| Apple                       | 2         | 2      | 0.9%    |
| A-DATA Technology           | 2         | 2      | 0.9%    |
| XPG                         | 1         | 1      | 0.45%   |
| Vaseky                      | 1         | 1      | 0.45%   |
| SPCC                        | 1         | 1      | 0.45%   |
| Silicon Motion              | 1         | 1      | 0.45%   |
| Realtek Semiconductor       | 1         | 1      | 0.45%   |
| PNY                         | 1         | 1      | 0.45%   |
| Plextor                     | 1         | 1      | 0.45%   |
| Phison Electronics          | 1         | 1      | 0.45%   |
| OSCOO                       | 1         | 1      | 0.45%   |
| LITEONIT                    | 1         | 1      | 0.45%   |
| Leven                       | 1         | 1      | 0.45%   |
| Kingston Technology Company | 1         | 1      | 0.45%   |
| Inateck                     | 1         | 1      | 0.45%   |
| GOODRAM                     | 1         | 1      | 0.45%   |
| Biostar                     | 1         | 1      | 0.45%   |
| Apacer                      | 1         | 1      | 0.45%   |
| 2-Power                     | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 4         | 1.62%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 1.62%   |
| Unknown SD/MMC/MS PRO 64GB                          | 3         | 1.21%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.21%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 1.21%   |
| Seagate One Touch HDD 5TB                           | 3         | 1.21%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.21%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 2         | 0.81%   |
| Unknown MMC Card  64GB                              | 2         | 0.81%   |
| Toshiba DT01ACA300 3TB                              | 2         | 0.81%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.81%   |
| Seagate ST2000DM006-2DM164 2TB                      | 2         | 0.81%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.81%   |
| Seagate ST1000DM003-1SB102 1TB                      | 2         | 0.81%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.81%   |
| Samsung SSD 980 1TB                                 | 2         | 0.81%   |
| Samsung SSD 970 EVO 1TB                             | 2         | 0.81%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.81%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.81%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 0.81%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.81%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 1TB         | 2         | 0.81%   |
| HGST HTS545050A7E680 500GB                          | 2         | 0.81%   |
| China SSD 1TB                                       | 2         | 0.81%   |
| XPG GAMMIX S50 1TB                                  | 1         | 0.4%    |
| WDC WDS512G1X0C-00ENX0 512GB                        | 1         | 0.4%    |
| WDC WDS500G3XHC-00SJG0 500GB                        | 1         | 0.4%    |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.4%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 0.4%    |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.4%    |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.4%    |
| WDC WD800JD-00MSA1 80GB                             | 1         | 0.4%    |
| WDC WD7500BPKT-75PK4T0 752GB                        | 1         | 0.4%    |
| WDC WD6400AAKS-22A7B2 640GB                         | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 48     | 43.21%  |
| WDC                 | 19        | 25     | 23.46%  |
| Toshiba             | 11        | 13     | 13.58%  |
| HGST                | 6         | 6      | 7.41%   |
| Unknown             | 3         | 3      | 3.7%    |
| Samsung Electronics | 3         | 3      | 3.7%    |
| Hitachi             | 3         | 3      | 3.7%    |
| Intenso             | 1         | 1      | 1.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 24.62%  |
| Kingston            | 10        | 13     | 15.38%  |
| Crucial             | 6         | 8      | 9.23%   |
| WDC                 | 4         | 4      | 6.15%   |
| China               | 4         | 4      | 6.15%   |
| Transcend           | 3         | 3      | 4.62%   |
| SanDisk             | 3         | 3      | 4.62%   |
| LITEON              | 2         | 2      | 3.08%   |
| Apple               | 2         | 2      | 3.08%   |
| Vaseky              | 1         | 1      | 1.54%   |
| SPCC                | 1         | 1      | 1.54%   |
| PNY                 | 1         | 1      | 1.54%   |
| Plextor             | 1         | 1      | 1.54%   |
| OSCOO               | 1         | 1      | 1.54%   |
| Micron Technology   | 1         | 1      | 1.54%   |
| LITEONIT            | 1         | 1      | 1.54%   |
| Leven               | 1         | 1      | 1.54%   |
| Intenso             | 1         | 1      | 1.54%   |
| Intel               | 1         | 1      | 1.54%   |
| GOODRAM             | 1         | 1      | 1.54%   |
| Biostar             | 1         | 1      | 1.54%   |
| Apacer              | 1         | 1      | 1.54%   |
| A-DATA Technology   | 1         | 1      | 1.54%   |
| 2-Power             | 1         | 1      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 69        | 93     | 35.94%  |
| HDD  | 64        | 102    | 33.33%  |
| SSD  | 54        | 73     | 28.13%  |
| MMC  | 5         | 6      | 2.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 163    | 50.57%  |
| NVMe | 69        | 92     | 39.66%  |
| SAS  | 12        | 13     | 6.9%    |
| MMC  | 5         | 6      | 2.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 85     | 45.31%  |
| 0.51-1.0   | 49        | 62     | 38.28%  |
| 1.01-2.0   | 10        | 14     | 7.81%   |
| 4.01-10.0  | 8         | 11     | 6.25%   |
| 2.01-3.0   | 2         | 2      | 1.56%   |
| 3.01-4.0   | 1         | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 30        | 22.06%  |
| 1001-2000      | 24        | 17.65%  |
| 251-500        | 20        | 14.71%  |
| 101-250        | 16        | 11.76%  |
| 501-1000       | 15        | 11.03%  |
| 51-100         | 9         | 6.62%   |
| Unknown        | 9         | 6.62%   |
| 21-50          | 5         | 3.68%   |
| 1-20           | 5         | 3.68%   |
| 2001-3000      | 3         | 2.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 21.32%  |
| 1-20           | 26        | 19.12%  |
| 51-100         | 21        | 15.44%  |
| 21-50          | 17        | 12.5%   |
| 251-500        | 11        | 8.09%   |
| 501-1000       | 9         | 6.62%   |
| Unknown        | 9         | 6.62%   |
| 2001-3000      | 5         | 3.68%   |
| 1001-2000      | 5         | 3.68%   |
| More than 3000 | 4         | 2.94%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB                                    | 1         | 1      | 3.85%   |
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 3.85%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 1         | 1      | 3.85%   |
| WDC WD10EADS-00M2B0 1TB                                         | 1         | 1      | 3.85%   |
| WDC WD1002FAEX-00Z3A0 1TB                                       | 1         | 2      | 3.85%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 3.85%   |
| Toshiba MK4058GSX 400GB                                         | 1         | 1      | 3.85%   |
| Toshiba MK2555GSX 250GB                                         | 1         | 1      | 3.85%   |
| Seagate ST9500420AS 500GB                                       | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 3.85%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 3.85%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1         | 1      | 3.85%   |
| Seagate ST31000524AS 1TB                                        | 1         | 1      | 3.85%   |
| Seagate ST2000VX000-1CU164 2TB                                  | 1         | 1      | 3.85%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 1         | 1      | 3.85%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 3.85%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 3.85%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD                                | 1         | 1      | 3.85%   |
| Kingston SUV400S37240G 240GB SSD                                | 1         | 1      | 3.85%   |
| Hitachi HTS725050A9A364 500GB                                   | 1         | 1      | 3.85%   |
| Hitachi HCP725050GLA380 500GB                                   | 1         | 1      | 3.85%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 3.85%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 3.85%   |
| China SATA3 240GB SSD                                           | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 36%     |
| WDC                 | 5         | 6      | 20%     |
| Toshiba             | 3         | 4      | 12%     |
| Kingston            | 2         | 2      | 8%      |
| Hitachi             | 2         | 2      | 8%      |
| HGST                | 2         | 2      | 8%      |
| Samsung Electronics | 1         | 1      | 4%      |
| China               | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 9      | 42.86%  |
| WDC     | 5         | 6      | 23.81%  |
| Toshiba | 3         | 4      | 14.29%  |
| Hitachi | 2         | 2      | 9.52%   |
| HGST    | 2         | 2      | 9.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 23     | 83.33%  |
| SSD  | 3         | 3      | 12.5%   |
| NVMe | 1         | 1      | 4.17%   |

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
| Works    | 97        | 173    | 62.99%  |
| Detected | 34        | 74     | 22.08%  |
| Malfunc  | 23        | 27     | 14.94%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 93        | 49.21%  |
| AMD                          | 26        | 13.76%  |
| Samsung Electronics          | 24        | 12.7%   |
| SanDisk                      | 14        | 7.41%   |
| Kingston Technology Company  | 5         | 2.65%   |
| SK hynix                     | 4         | 2.12%   |
| Phison Electronics           | 4         | 2.12%   |
| Micron Technology            | 4         | 2.12%   |
| KIOXIA                       | 4         | 2.12%   |
| Toshiba America Info Systems | 3         | 1.59%   |
| Realtek Semiconductor        | 2         | 1.06%   |
| Micron/Crucial Technology    | 2         | 1.06%   |
| Silicon Motion               | 1         | 0.53%   |
| Seagate Technology           | 1         | 0.53%   |
| ASMedia Technology           | 1         | 0.53%   |
| ADATA Technology             | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 11.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 3.45%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.96%   |
| Intel SATA Controller [RAID mode]                                              | 6         | 2.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 2.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.97%   |
| Micron NVMe Storage Controller                                                 | 4         | 1.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.97%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 1.48%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 1.48%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.48%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.48%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.48%   |
| Intel SSD 660P Series                                                          | 3         | 1.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.48%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.99%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.99%   |
| SanDisk NVMe Controller                                                        | 2         | 0.99%   |
| Samsung Apple PCIe SSD                                                         | 2         | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.99%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.99%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.99%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.99%   |
| AMD FCH SATA Controller D                                                      | 2         | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 98        | 52.41%  |
| NVMe | 69        | 36.9%   |
| RAID | 19        | 10.16%  |
| IDE  | 1         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 99        | 75.57%  |
| AMD    | 32        | 24.43%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 3.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.27%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 2.27%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 3         | 2.27%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 1.52%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 1.52%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 1.52%   |
| Intel Core i7 CPU 870 @ 2.93GHz               | 2         | 1.52%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.52%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 1.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.52%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 2         | 1.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.52%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2         | 1.52%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.52%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.52%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.52%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz            | 1         | 0.76%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 1         | 0.76%   |
| Intel Genuine CPU 0000 @ 2.10GHz              | 1         | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.76%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.76%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.76%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.76%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.76%   |
| Intel Core i7-4960HQ CPU @ 2.60GHz            | 1         | 0.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.76%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i7     | 36        | 27.27%  |
| Intel Core i5     | 35        | 26.52%  |
| AMD Ryzen 5       | 15        | 11.36%  |
| Other             | 11        | 8.33%   |
| Intel Core i3     | 9         | 6.82%   |
| AMD Ryzen 7       | 9         | 6.82%   |
| Intel Celeron     | 3         | 2.27%   |
| Intel Xeon        | 2         | 1.52%   |
| AMD Ryzen 3       | 2         | 1.52%   |
| AMD A8            | 2         | 1.52%   |
| Intel Genuine     | 1         | 0.76%   |
| Intel Core 2 Quad | 1         | 0.76%   |
| Intel Core 2 Duo  | 1         | 0.76%   |
| AMD Ryzen 9       | 1         | 0.76%   |
| AMD E1            | 1         | 0.76%   |
| AMD Athlon        | 1         | 0.76%   |
| AMD A6            | 1         | 0.76%   |
| AMD A4            | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 55        | 41.67%  |
| 2      | 38        | 28.79%  |
| 6      | 23        | 17.42%  |
| 8      | 12        | 9.09%   |
| 12     | 2         | 1.52%   |
| 16     | 1         | 0.76%   |
| 14     | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 130       | 99.24%  |
| 2      | 1         | 0.76%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 110       | 83.33%  |
| 1      | 22        | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 131       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 29.1%   |
| 0x906ea    | 7         | 5.22%   |
| 0x806c1    | 7         | 5.22%   |
| 0x806ec    | 6         | 4.48%   |
| 0x306a9    | 6         | 4.48%   |
| 0x806e9    | 5         | 3.73%   |
| 0x506e3    | 5         | 3.73%   |
| 0x08701021 | 5         | 3.73%   |
| 0x906e9    | 4         | 2.99%   |
| 0x806eb    | 3         | 2.24%   |
| 0x306c3    | 3         | 2.24%   |
| 0x206a7    | 3         | 2.24%   |
| 0x0a201016 | 3         | 2.24%   |
| 0x08108109 | 3         | 2.24%   |
| 0x906ed    | 2         | 1.49%   |
| 0x906eb    | 2         | 1.49%   |
| 0x706a8    | 2         | 1.49%   |
| 0x40651    | 2         | 1.49%   |
| 0x106e5    | 2         | 1.49%   |
| 0x1067a    | 2         | 1.49%   |
| 0x0a20120a | 2         | 1.49%   |
| 0xa0653    | 1         | 0.75%   |
| 0xa0652    | 1         | 0.75%   |
| 0x906a3    | 1         | 0.75%   |
| 0x806d1    | 1         | 0.75%   |
| 0x706e5    | 1         | 0.75%   |
| 0x406e3    | 1         | 0.75%   |
| 0x40661    | 1         | 0.75%   |
| 0x306f2    | 1         | 0.75%   |
| 0x306d4    | 1         | 0.75%   |
| 0x20655    | 1         | 0.75%   |
| 0x20652    | 1         | 0.75%   |
| 0x0a50000b | 1         | 0.75%   |
| 0x08701013 | 1         | 0.75%   |
| 0x08608103 | 1         | 0.75%   |
| 0x08600106 | 1         | 0.75%   |
| 0x08108102 | 1         | 0.75%   |
| 0x0810100b | 1         | 0.75%   |
| 0x06006705 | 1         | 0.75%   |
| 0x0600611a | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 27.27%  |
| Haswell          | 14        | 10.61%  |
| Zen 2            | 10        | 7.58%   |
| Zen 3            | 8         | 6.06%   |
| TigerLake        | 8         | 6.06%   |
| IvyBridge        | 8         | 6.06%   |
| Zen+             | 7         | 5.3%    |
| Skylake          | 7         | 5.3%    |
| SandyBridge      | 5         | 3.79%   |
| Nehalem          | 3         | 2.27%   |
| IceLake          | 3         | 2.27%   |
| Goldmont plus    | 3         | 2.27%   |
| CometLake        | 3         | 2.27%   |
| Broadwell        | 3         | 2.27%   |
| Zen              | 2         | 1.52%   |
| Westmere         | 2         | 1.52%   |
| Penryn           | 2         | 1.52%   |
| Excavator        | 2         | 1.52%   |
| Unknown          | 2         | 1.52%   |
| Piledriver       | 1         | 0.76%   |
| K10 Llano        | 1         | 0.76%   |
| Bobcat           | 1         | 0.76%   |
| Alderlake Hybrid | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 77        | 44%     |
| Nvidia            | 66        | 37.71%  |
| AMD               | 31        | 17.71%  |
| ASPEED Technology | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 3.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 2.82%   |
| Intel HD Graphics 620                                                       | 5         | 2.82%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 2.82%   |
| Intel UHD Graphics 620                                                      | 4         | 2.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 2.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 2.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 3         | 1.69%   |
| Nvidia GP108M [GeForce MX250]                                               | 3         | 1.69%   |
| Nvidia GP108M [GeForce MX150]                                               | 3         | 1.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3         | 1.69%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 3         | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 3         | 1.69%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 3         | 1.69%   |
| Intel HD Graphics 630                                                       | 3         | 1.69%   |
| Intel HD Graphics 5500                                                      | 3         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.69%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2         | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2         | 1.13%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.13%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 1.13%   |
| Nvidia GM108M [GeForce 940MX]                                               | 2         | 1.13%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 2         | 1.13%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.13%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.13%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 2         | 1.13%   |
| AMD Renoir                                                                  | 2         | 1.13%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.56%   |
| Nvidia TU117M                                                               | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 38        | 29.01%  |
| Intel + Nvidia  | 34        | 25.95%  |
| 1 x Nvidia      | 25        | 19.08%  |
| 1 x AMD         | 22        | 16.79%  |
| AMD + Nvidia    | 5         | 3.82%   |
| Intel + AMD     | 3         | 2.29%   |
| 2 x Nvidia      | 1         | 0.76%   |
| 2 x Intel       | 1         | 0.76%   |
| 2 x AMD         | 1         | 0.76%   |
| Nvidia + ASPEED | 1         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 84        | 63.64%  |
| Proprietary | 46        | 34.85%  |
| Unknown     | 2         | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 59.85%  |
| 1.01-2.0   | 18        | 13.64%  |
| 7.01-8.0   | 9         | 6.82%   |
| 5.01-6.0   | 7         | 5.3%    |
| 0.01-0.5   | 7         | 5.3%    |
| 3.01-4.0   | 6         | 4.55%   |
| 8.01-16.0  | 4         | 3.03%   |
| 0.51-1.0   | 2         | 1.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 22        | 14.97%  |
| AU Optronics         | 20        | 13.61%  |
| Chimei Innolux       | 15        | 10.2%   |
| BOE                  | 15        | 10.2%   |
| LG Display           | 14        | 9.52%   |
| Acer                 | 6         | 4.08%   |
| Hewlett-Packard      | 5         | 3.4%    |
| Goldstar             | 4         | 2.72%   |
| Dell                 | 4         | 2.72%   |
| AOC                  | 4         | 2.72%   |
| Ancor Communications | 4         | 2.72%   |
| Sharp                | 3         | 2.04%   |
| PANDA                | 3         | 2.04%   |
| Lenovo               | 3         | 2.04%   |
| Apple                | 3         | 2.04%   |
| Iiyama               | 2         | 1.36%   |
| Toshiba              | 1         | 0.68%   |
| TMX                  | 1         | 0.68%   |
| Sony                 | 1         | 0.68%   |
| Sceptre Tech         | 1         | 0.68%   |
| Philips              | 1         | 0.68%   |
| MSI                  | 1         | 0.68%   |
| LGD                  | 1         | 0.68%   |
| Konka                | 1         | 0.68%   |
| Kogan                | 1         | 0.68%   |
| KOC                  | 1         | 0.68%   |
| JRY                  | 1         | 0.68%   |
| ITE                  | 1         | 0.68%   |
| Idek Iiyama          | 1         | 0.68%   |
| Hitachi              | 1         | 0.68%   |
| Gigabyte Technology  | 1         | 0.68%   |
| FOX                  | 1         | 0.68%   |
| CSO                  | 1         | 0.68%   |
| BenQ                 | 1         | 0.68%   |
| ASUSTek Computer     | 1         | 0.68%   |
| Unknown              | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 1.99%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 1.32%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 1.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.32%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.32%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.66%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.66%   |
| Sony LCD Monitor AVSYSTEM 1280x720                                      | 1         | 0.66%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 0.66%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.66%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.66%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.66%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch       | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch    | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 0.66%   |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 531x299mm 24.0-inch    | 1         | 0.66%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.66%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.66%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.66%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.66%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 0.66%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 0.66%   |
| Samsung Electronics LC24RG50 SAM0F91 1920x1080 532x304mm 24.1-inch      | 1         | 0.66%   |
| Samsung Electronics C27R50x SAM0F9E 1920x1080 598x336mm 27.0-inch       | 1         | 0.66%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch                 | 1         | 0.66%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.66%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.66%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.66%   |
| MSI G24C4 MSI3BA0 1920x1080 521x293mm 23.5-inch                         | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 81        | 58.27%  |
| 1366x768 (WXGA)    | 19        | 13.67%  |
| 3840x2160 (4K)     | 8         | 5.76%   |
| 2560x1440 (QHD)    | 6         | 4.32%   |
| 3440x1440          | 5         | 3.6%    |
| 1600x900 (HD+)     | 4         | 2.88%   |
| 2560x1080          | 3         | 2.16%   |
| 1680x1050 (WSXGA+) | 2         | 1.44%   |
| 3840x2400          | 1         | 0.72%   |
| 3840x1080          | 1         | 0.72%   |
| 3200x1800 (QHD+)   | 1         | 0.72%   |
| 2880x1800          | 1         | 0.72%   |
| 2160x1440          | 1         | 0.72%   |
| 1920x540           | 1         | 0.72%   |
| 1920x1200 (WUXGA)  | 1         | 0.72%   |
| 1440x900 (WXGA+)   | 1         | 0.72%   |
| 1360x768           | 1         | 0.72%   |
| 1280x720 (HD)      | 1         | 0.72%   |
| 1280x1024 (SXGA)   | 1         | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 51        | 34.69%  |
| 27      | 13        | 8.84%   |
| 14      | 12        | 8.16%   |
| 23      | 11        | 7.48%   |
| 13      | 10        | 6.8%    |
| 24      | 8         | 5.44%   |
| 21      | 8         | 5.44%   |
| 34      | 6         | 4.08%   |
| Unknown | 5         | 3.4%    |
| 84      | 4         | 2.72%   |
| 31      | 4         | 2.72%   |
| 17      | 3         | 2.04%   |
| 28      | 2         | 1.36%   |
| 20      | 2         | 1.36%   |
| 18      | 2         | 1.36%   |
| 72      | 1         | 0.68%   |
| 52      | 1         | 0.68%   |
| 48      | 1         | 0.68%   |
| 33      | 1         | 0.68%   |
| 16      | 1         | 0.68%   |
| 12      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 69        | 47.26%  |
| 501-600     | 30        | 20.55%  |
| 401-500     | 12        | 8.22%   |
| 701-800     | 7         | 4.79%   |
| 601-700     | 6         | 4.11%   |
| 351-400     | 5         | 3.42%   |
| 201-300     | 5         | 3.42%   |
| 1501-2000   | 5         | 3.42%   |
| Unknown     | 5         | 3.42%   |
| 1001-1500   | 2         | 1.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 109       | 84.5%   |
| 21/9    | 8         | 6.2%    |
| 16/10   | 5         | 3.88%   |
| Unknown | 4         | 3.1%    |
| 5/4     | 1         | 0.78%   |
| 32/9    | 1         | 0.78%   |
| 3/2     | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 35.86%  |
| 201-250        | 24        | 16.55%  |
| 81-90          | 19        | 13.1%   |
| 301-350        | 13        | 8.97%   |
| 351-500        | 11        | 7.59%   |
| More than 1000 | 6         | 4.14%   |
| Unknown        | 5         | 3.45%   |
| 71-80          | 3         | 2.07%   |
| 251-300        | 3         | 2.07%   |
| 151-200        | 3         | 2.07%   |
| 121-130        | 3         | 2.07%   |
| 61-70          | 1         | 0.69%   |
| 141-150        | 1         | 0.69%   |
| 501-1000       | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 37.86%  |
| 51-100        | 40        | 28.57%  |
| 101-120       | 30        | 21.43%  |
| 161-240       | 6         | 4.29%   |
| Unknown       | 5         | 3.57%   |
| More than 240 | 3         | 2.14%   |
| 1-50          | 3         | 2.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 104       | 78.79%  |
| 2     | 25        | 18.94%  |
| 0     | 2         | 1.52%   |
| 3     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 74        | 39.57%  |
| Realtek Semiconductor             | 72        | 38.5%   |
| Qualcomm Atheros                  | 11        | 5.88%   |
| Broadcom                          | 5         | 2.67%   |
| MediaTek                          | 4         | 2.14%   |
| Broadcom Limited                  | 4         | 2.14%   |
| ASIX Electronics                  | 3         | 1.6%    |
| Samsung Electronics               | 2         | 1.07%   |
| Ralink Technology                 | 2         | 1.07%   |
| Ralink                            | 2         | 1.07%   |
| Ericsson Business Mobile Networks | 2         | 1.07%   |
| TP-Link                           | 1         | 0.53%   |
| Qualcomm Atheros Communications   | 1         | 0.53%   |
| Qualcomm                          | 1         | 0.53%   |
| NetGear                           | 1         | 0.53%   |
| Microsoft                         | 1         | 0.53%   |
| Marvell Technology Group          | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 53        | 23.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 3.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 7         | 3.11%   |
| Intel Wi-Fi 6 AX200                                                | 7         | 3.11%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 2.67%   |
| Intel I211 Gigabit Network Connection                              | 6         | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 5         | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                  | 5         | 2.22%   |
| Intel Wireless 8265 / 8275                                         | 5         | 2.22%   |
| Intel Wireless 7260                                                | 5         | 2.22%   |
| Intel Ethernet Connection (2) I219-V                               | 5         | 2.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 2.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 4         | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 4         | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 3         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 3         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 1.33%   |
| Intel Wireless 7265                                                | 3         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 2         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 2         | 0.89%   |
| Intel Wireless-AC 9260                                             | 2         | 0.89%   |
| Intel Ethernet Connection I217-LM                                  | 2         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                               | 2         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                              | 2         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 2         | 0.89%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 2         | 0.89%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                    | 2         | 0.89%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 2         | 0.89%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1         | 0.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                    | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 56.07%  |
| Realtek Semiconductor           | 19        | 17.76%  |
| Qualcomm Atheros                | 10        | 9.35%   |
| MediaTek                        | 4         | 3.74%   |
| Broadcom Limited                | 4         | 3.74%   |
| Broadcom                        | 3         | 2.8%    |
| Ralink Technology               | 2         | 1.87%   |
| Ralink                          | 2         | 1.87%   |
| Qualcomm Atheros Communications | 1         | 0.93%   |
| NetGear                         | 1         | 0.93%   |
| Microsoft                       | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 7         | 6.54%   |
| Intel Wi-Fi 6 AX200                                                       | 7         | 6.54%   |
| Intel Wi-Fi 6 AX201                                                       | 6         | 5.61%   |
| Intel Wireless 8265 / 8275                                                | 5         | 4.67%   |
| Intel Wireless 7260                                                       | 5         | 4.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 5         | 4.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 4.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 4         | 3.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 3.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 3         | 2.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 3         | 2.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 3         | 2.8%    |
| Intel Wireless 7265                                                       | 3         | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 3         | 2.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 2         | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                  | 2         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 1.87%   |
| Intel Wireless-AC 9260                                                    | 2         | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 2         | 1.87%   |
| Intel Centrino Wireless-N 2230                                            | 2         | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                          | 2         | 1.87%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 1.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                  | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.93%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 0.93%   |
| Ralink RT2501/RT2573 Wireless Adapter                                     | 1         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                           | 1         | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                    | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                 | 1         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                           | 1         | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)            | 1         | 0.93%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.93%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 0.93%   |
| Intel Wireless 8260                                                       | 1         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                           | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 58.04%  |
| Intel                    | 36        | 32.14%  |
| Broadcom                 | 3         | 2.68%   |
| ASIX Electronics         | 3         | 2.68%   |
| Qualcomm Atheros         | 2         | 1.79%   |
| TP-Link                  | 1         | 0.89%   |
| Qualcomm                 | 1         | 0.89%   |
| Marvell Technology Group | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 53        | 46.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 7.02%   |
| Intel I211 Gigabit Network Connection                             | 6         | 5.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 4.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 4.39%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 4.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 3.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.63%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.75%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.75%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.88%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.88%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.88%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.88%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 49.07%  |
| Ethernet | 106       | 49.07%  |
| Modem    | 4         | 1.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 62.22%  |
| Ethernet | 51        | 37.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 67        | 51.15%  |
| 1     | 59        | 45.04%  |
| 3     | 4         | 3.05%   |
| 0     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 71.21%  |
| Yes  | 38        | 28.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 52.08%  |
| Realtek Semiconductor           | 11        | 11.46%  |
| Broadcom                        | 7         | 7.29%   |
| Cambridge Silicon Radio         | 6         | 6.25%   |
| Qualcomm Atheros Communications | 5         | 5.21%   |
| IMC Networks                    | 5         | 5.21%   |
| Lite-On Technology              | 2         | 2.08%   |
| Foxconn / Hon Hai               | 2         | 2.08%   |
| ASUSTek Computer                | 2         | 2.08%   |
| Apple                           | 2         | 2.08%   |
| Toshiba                         | 1         | 1.04%   |
| Realtek                         | 1         | 1.04%   |
| MediaTek                        | 1         | 1.04%   |
| Dell                            | 1         | 1.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 16.67%  |
| Intel Bluetooth wireless interface                  | 12        | 12.5%   |
| Intel AX201 Bluetooth                               | 8         | 8.33%   |
| Intel AX200 Bluetooth                               | 7         | 7.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 5.21%   |
| Realtek Bluetooth Radio                             | 5         | 5.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4.17%   |
| IMC Networks Bluetooth Radio                        | 3         | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 2.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.08%   |
| IMC Networks Wireless_Device                        | 2         | 2.08%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 2.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.08%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.04%   |
| Realtek Bluetooth Radio                             | 1         | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.04%   |
| MediaTek Wireless_Device                            | 1         | 1.04%   |
| Lite-On Bluetooth Device                            | 1         | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.04%   |
| Intel Bluetooth Device                              | 1         | 1.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.04%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.04%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.04%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.04%   |
| Broadcom BCM2045A0                                  | 1         | 1.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.04%   |
| ASUS Bluetooth Radio                                | 1         | 1.04%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.04%   |
| Apple Bluetooth Host Controller                     | 1         | 1.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 99        | 48.77%  |
| Nvidia                     | 44        | 21.67%  |
| AMD                        | 35        | 17.24%  |
| Corsair                    | 3         | 1.48%   |
| C-Media Electronics        | 3         | 1.48%   |
| Razer USA                  | 2         | 0.99%   |
| Kingston Technology        | 2         | 0.99%   |
| GN Netcom                  | 2         | 0.99%   |
| Tenx Technology            | 1         | 0.49%   |
| Samsung Electronics        | 1         | 0.49%   |
| Realtek Semiconductor      | 1         | 0.49%   |
| PreSonus Audio Electronics | 1         | 0.49%   |
| Plantronics                | 1         | 0.49%   |
| Logitech                   | 1         | 0.49%   |
| Lenovo                     | 1         | 0.49%   |
| Hewlett-Packard            | 1         | 0.49%   |
| Generalplus Technology     | 1         | 0.49%   |
| ELMCU                      | 1         | 0.49%   |
| Barco Display Systems      | 1         | 0.49%   |
| ASUSTek Computer           | 1         | 0.49%   |
| Astro Gaming               | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 5%      |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 4.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 3.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.33%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.08%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 2.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 2.08%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.08%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.67%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.25%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.25%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 1.25%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 1.25%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.83%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 26.15%  |
| SK hynix            | 30        | 23.08%  |
| Micron Technology   | 14        | 10.77%  |
| Crucial             | 11        | 8.46%   |
| Corsair             | 11        | 8.46%   |
| Kingston            | 7         | 5.38%   |
| G.Skill             | 6         | 4.62%   |
| Ramaxel Technology  | 5         | 3.85%   |
| Unknown             | 4         | 3.08%   |
| Team                | 2         | 1.54%   |
| Unifosa             | 1         | 0.77%   |
| Transcend           | 1         | 0.77%   |
| PNY                 | 1         | 0.77%   |
| Nanya Technology    | 1         | 0.77%   |
| Elpida              | 1         | 0.77%   |
| A-DATA Technology   | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 4         | 2.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 3         | 2.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 1.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.44%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.44%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.44%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 2         | 1.44%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s  | 2         | 1.44%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s          | 2         | 1.44%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 2         | 1.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                    | 1         | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                     | 1         | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 1         | 0.72%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s            | 1         | 0.72%   |
| Transcend RAM TS1GLK64V6H 8GB DIMM DDR3 1600MT/s             | 1         | 0.72%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s           | 1         | 0.72%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s           | 1         | 0.72%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 1         | 0.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                | 1         | 0.72%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 1         | 0.72%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1         | 0.72%   |
| SK hynix RAM HMT351U6BFR8C-H9 4096MB DIMM 1450MT/s           | 1         | 0.72%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 0.72%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.72%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 1         | 0.72%   |
| SK hynix RAM HMA81GU6MFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 70        | 63.64%  |
| DDR3   | 29        | 26.36%  |
| SDRAM  | 2         | 1.82%   |
| LPDDR4 | 2         | 1.82%   |
| LPDDR3 | 2         | 1.82%   |
| DDR    | 2         | 1.82%   |
| LPDDR5 | 1         | 0.91%   |
| DDR5   | 1         | 0.91%   |
| DDR2   | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 56.76%  |
| DIMM         | 37        | 33.33%  |
| Row Of Chips | 11        | 9.91%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 55        | 46.22%  |
| 4096  | 36        | 30.25%  |
| 16384 | 21        | 17.65%  |
| 2048  | 6         | 5.04%   |
| 1024  | 1         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 27        | 21.6%   |
| 3200  | 23        | 18.4%   |
| 1600  | 22        | 17.6%   |
| 2400  | 8         | 6.4%    |
| 2133  | 5         | 4%      |
| 1333  | 5         | 4%      |
| 3600  | 4         | 3.2%    |
| 3266  | 4         | 3.2%    |
| 2933  | 3         | 2.4%    |
| 1800  | 3         | 2.4%    |
| 4267  | 2         | 1.6%    |
| 3400  | 2         | 1.6%    |
| 2176  | 2         | 1.6%    |
| 800   | 2         | 1.6%    |
| 6400  | 1         | 0.8%    |
| 4800  | 1         | 0.8%    |
| 4400  | 1         | 0.8%    |
| 4199  | 1         | 0.8%    |
| 4133  | 1         | 0.8%    |
| 3800  | 1         | 0.8%    |
| 3467  | 1         | 0.8%    |
| 2747  | 1         | 0.8%    |
| 2666  | 1         | 0.8%    |
| 1867  | 1         | 0.8%    |
| 1450  | 1         | 0.8%    |
| 1334  | 1         | 0.8%    |
| 1067  | 1         | 0.8%    |

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
| IMC Networks                           | 21        | 24.71%  |
| Chicony Electronics                    | 16        | 18.82%  |
| Realtek Semiconductor                  | 7         | 8.24%   |
| Acer                                   | 6         | 7.06%   |
| Syntek                                 | 5         | 5.88%   |
| Microdia                               | 5         | 5.88%   |
| Sunplus Innovation Technology          | 4         | 4.71%   |
| Quanta                                 | 4         | 4.71%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.71%   |
| Bison Electronics                      | 3         | 3.53%   |
| Generalplus Technology                 | 2         | 2.35%   |
| Suyin                                  | 1         | 1.18%   |
| Sonix Technology                       | 1         | 1.18%   |
| Ricoh                                  | 1         | 1.18%   |
| Panasonic (Matsushita)                 | 1         | 1.18%   |
| Luxvisions Innotech Limited            | 1         | 1.18%   |
| Logitech                               | 1         | 1.18%   |
| Lite-On Technology                     | 1         | 1.18%   |
| Alpha Imaging Technology               | 1         | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 7         | 8.24%   |
| Syntek Integrated Camera                            | 5         | 5.88%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 5.88%   |
| Realtek Integrated_Webcam_HD                        | 4         | 4.71%   |
| Quanta HP TrueVision HD Camera                      | 3         | 3.53%   |
| Chicony Integrated Camera                           | 3         | 3.53%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 2.35%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 2.35%   |
| Chicony EasyCamera                                  | 2         | 2.35%   |
| Bison ThinkPad Integrated Camera                    | 2         | 2.35%   |
| Acer Integrated Camera                              | 2         | 2.35%   |
| Acer HD Webcam                                      | 2         | 2.35%   |
| Suyin Asus Integrated Webcam                        | 1         | 1.18%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.18%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.18%   |
| Sunplus HP Truevision HD                            | 1         | 1.18%   |
| Sunplus 1080p FHD Camera                            | 1         | 1.18%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.18%   |
| Ricoh Integrated Webcam                             | 1         | 1.18%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.18%   |
| Realtek Integrated Webcam                           | 1         | 1.18%   |
| Realtek Built-In Video Camera                       | 1         | 1.18%   |
| Quanta HD User Facing                               | 1         | 1.18%   |
| Panasonic (Matsushita) TY-CC20W                     | 1         | 1.18%   |
| Microdia Webcam Vitade AF                           | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 1.18%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.18%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.18%   |
| Logitech Webcam C600                                | 1         | 1.18%   |
| Lite-On Integrated Camera                           | 1         | 1.18%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.18%   |
| IMC Networks UVC VGA Webcam                         | 1         | 1.18%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.18%   |
| IMC Networks USB2.0 HD IR UVC WebCam                | 1         | 1.18%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 1.18%   |
| IMC Networks HD Camera                              | 1         | 1.18%   |
| IMC Networks EasyCamera                             | 1         | 1.18%   |
| Generalplus GENERAL WEBCAM                          | 1         | 1.18%   |
| Generalplus campark PC04                            | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 35.71%  |
| Synaptics                  | 3         | 21.43%  |
| Shenzhen Goodix Technology | 3         | 21.43%  |
| Elan Microelectronics      | 2         | 14.29%  |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI                   | 2         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.14%   |
| Synaptics WBDI                                    | 1         | 7.14%   |
| Synaptics  WBDI                                   | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 7.14%   |
| Elan fingerprint sensor [FeinTech FPS00200]       | 1         | 7.14%   |
| Elan ELAN:Fingerprint                             | 1         | 7.14%   |
| AuthenTec Fingerprint Sensor                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 33.33%  |
| Upek        | 2         | 22.22%  |
| Alcor Micro | 2         | 22.22%  |
| Yubico.com  | 1         | 11.11%  |
| Clay Logic  | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 22.22%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 22.22%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 11.11%  |
| Clay Logic Nitrokey Pro                                    | 1         | 11.11%  |
| Broadcom 58200                                             | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 94        | 71.21%  |
| 1     | 32        | 24.24%  |
| 2     | 6         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 31.82%  |
| Graphics card         | 10        | 22.73%  |
| Chipcard              | 7         | 15.91%  |
| Multimedia controller | 4         | 9.09%   |
| Net/wireless          | 2         | 4.55%   |
| Camera                | 2         | 4.55%   |
| Bluetooth             | 2         | 4.55%   |
| Unassigned class      | 1         | 2.27%   |
| Storage               | 1         | 2.27%   |
| Network               | 1         | 2.27%   |

