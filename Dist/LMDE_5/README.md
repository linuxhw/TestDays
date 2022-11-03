LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 248

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| HP            | 8299                        | Desktop     | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| Dell          | XPS L701X                   | Notebook    | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| HP            | 8299                        | Desktop     | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| AZW           | MINI S                      | Desktop     | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ff09bb4e1](https://linux-hardware.org/?probe=8ff09bb4e1) | Sep 22, 2022 |
| Gateway       | DX4870                      | Desktop     | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Medion        | P15648                      | Notebook    | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | Notebook    | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | Desktop     | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | Desktop     | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | Desktop     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-12-amd64          | 35        | 17.86%  |
| 5.10.0-14-amd64          | 30        | 15.31%  |
| 5.10.0-13-amd64          | 27        | 13.78%  |
| 5.10.0-18-amd64          | 24        | 12.24%  |
| 5.10.0-17-amd64          | 20        | 10.2%   |
| 5.10.0-15-amd64          | 18        | 9.18%   |
| 5.10.0-16-amd64          | 13        | 6.63%   |
| 5.10.0-19-amd64          | 6         | 3.06%   |
| 5.10.0-13-686            | 6         | 3.06%   |
| 5.18.0-0.bpo.1-amd64     | 4         | 2.04%   |
| 5.16.0-0.bpo.4-amd64     | 3         | 1.53%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1         | 0.51%   |
| 5.19.10-xanmod1          | 1         | 0.51%   |
| 5.18.0-4-amd64           | 1         | 0.51%   |
| 5.18.0-3-amd64           | 1         | 0.51%   |
| 5.16.0-0.bpo.3-amd64     | 1         | 0.51%   |
| 5.15.70-xanmod1          | 1         | 0.51%   |
| 5.15.0-0.bpo.3-amd64     | 1         | 0.51%   |
| 5.10.0-17-686            | 1         | 0.51%   |
| 5.10.0-14-686            | 1         | 0.51%   |
| 5.10.0-11-686            | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 175       | 93.09%  |
| 5.18.0  | 6         | 3.19%   |
| 5.16.0  | 3         | 1.6%    |
| 6.0.2   | 1         | 0.53%   |
| 5.19.10 | 1         | 0.53%   |
| 5.15.70 | 1         | 0.53%   |
| 5.15.0  | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 175       | 93.09%  |
| 5.18    | 6         | 3.19%   |
| 5.16    | 3         | 1.6%    |
| 5.15    | 2         | 1.06%   |
| 6.0     | 1         | 0.53%   |
| 5.19    | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 176       | 95.14%  |
| i686   | 9         | 4.86%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 168       | 90.81%  |
| Cinnamon   | 12        | 6.49%   |
| XFCE       | 2         | 1.08%   |
| MATE       | 2         | 1.08%   |
| Unknown    | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 185       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 118       | 63.78%  |
| LightDM | 67        | 36.22%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 69        | 37.1%   |
| de_DE | 20        | 10.75%  |
| ru_RU | 18        | 9.68%   |
| pt_BR | 11        | 5.91%   |
| en_GB | 10        | 5.38%   |
| fr_FR | 9         | 4.84%   |
| es_ES | 7         | 3.76%   |
| it_IT | 5         | 2.69%   |
| pl_PL | 4         | 2.15%   |
| es_MX | 3         | 1.61%   |
| en_CA | 3         | 1.61%   |
| ko_KR | 2         | 1.08%   |
| fr_CA | 2         | 1.08%   |
| es_BO | 2         | 1.08%   |
| en_IE | 2         | 1.08%   |
| sv_SE | 1         | 0.54%   |
| sk_SK | 1         | 0.54%   |
| pt_PT | 1         | 0.54%   |
| nn_NO | 1         | 0.54%   |
| nl_AW | 1         | 0.54%   |
| it_CH | 1         | 0.54%   |
| hu_HU | 1         | 0.54%   |
| fr_BE | 1         | 0.54%   |
| es_PE | 1         | 0.54%   |
| es_NI | 1         | 0.54%   |
| es_EC | 1         | 0.54%   |
| es_CR | 1         | 0.54%   |
| en_NZ | 1         | 0.54%   |
| en_IN | 1         | 0.54%   |
| en_AU | 1         | 0.54%   |
| de_AT | 1         | 0.54%   |
| da_DK | 1         | 0.54%   |
| cs_CZ | 1         | 0.54%   |
| ar_EG | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 112       | 60.22%  |
| BIOS | 74        | 39.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 170       | 91.89%  |
| Overlay | 6         | 3.24%   |
| Tmpfs   | 5         | 2.7%    |
| Btrfs   | 3         | 1.62%   |
| Xfs     | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 118       | 63.78%  |
| GPT     | 54        | 29.19%  |
| MBR     | 13        | 7.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 93.01%  |
| Yes       | 13        | 6.99%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 90.27%  |
| Yes       | 18        | 9.73%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 17.84%  |
| Dell                | 28        | 15.14%  |
| Lenovo              | 26        | 14.05%  |
| ASUSTek Computer    | 25        | 13.51%  |
| Acer                | 15        | 8.11%   |
| MSI                 | 11        | 5.95%   |
| Gigabyte Technology | 5         | 2.7%    |
| Apple               | 5         | 2.7%    |
| Toshiba             | 3         | 1.62%   |
| Sony                | 3         | 1.62%   |
| Samsung Electronics | 3         | 1.62%   |
| ASRock              | 3         | 1.62%   |
| Medion              | 2         | 1.08%   |
| Unknown             | 2         | 1.08%   |
| Wortmann AG         | 1         | 0.54%   |
| Philco              | 1         | 0.54%   |
| Pegatron            | 1         | 0.54%   |
| Panasonic           | 1         | 0.54%   |
| Packard Bell        | 1         | 0.54%   |
| Multilaser          | 1         | 0.54%   |
| Microtech           | 1         | 0.54%   |
| LincPlus            | 1         | 0.54%   |
| Intel               | 1         | 0.54%   |
| Howard Computers    | 1         | 0.54%   |
| Google              | 1         | 0.54%   |
| Gateway             | 1         | 0.54%   |
| Fujitsu             | 1         | 0.54%   |
| Framework           | 1         | 0.54%   |
| eMachines           | 1         | 0.54%   |
| Dynabook            | 1         | 0.54%   |
| Dixonsxp            | 1         | 0.54%   |
| Digiboard           | 1         | 0.54%   |
| AZW                 | 1         | 0.54%   |
| AMI                 | 1         | 0.54%   |
| Alienware           | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 3         | 1.62%   |
| Lenovo IdeaPad 3 15ADA05 81W1       | 2         | 1.08%   |
| HP Laptop 15z-ef2xxx                | 2         | 1.08%   |
| Dell Latitude E6400                 | 2         | 1.08%   |
| Dell Latitude E5540                 | 2         | 1.08%   |
| Acer Aspire 5930                    | 2         | 1.08%   |
| Wortmann AG TERRA_MOBILE_1713A      | 1         | 0.54%   |
| Toshiba Satellite M55               | 1         | 0.54%   |
| Toshiba Satellite L855D             | 1         | 0.54%   |
| Toshiba Satellite L455              | 1         | 0.54%   |
| Sony SVF1532W4E                     | 1         | 0.54%   |
| Sony SVE1713Y1RB                    | 1         | 0.54%   |
| Sony SVE1512G1RW                    | 1         | 0.54%   |
| Samsung DeskTop System              | 1         | 0.54%   |
| Samsung 730QDA                      | 1         | 0.54%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.54%   |
| Philco 10D                          | 1         | 0.54%   |
| Pegatron Pro 3015 Microtower PC     | 1         | 0.54%   |
| Panasonic CF-H2BJJHZDE              | 1         | 0.54%   |
| Packard Bell DOT S                  | 1         | 0.54%   |
| Multilaser PC150                    | 1         | 0.54%   |
| MSI U180                            | 1         | 0.54%   |
| MSI MS-7C52                         | 1         | 0.54%   |
| MSI MS-7B79                         | 1         | 0.54%   |
| MSI MS-7B23                         | 1         | 0.54%   |
| MSI MS-7B17                         | 1         | 0.54%   |
| MSI MS-7A40                         | 1         | 0.54%   |
| MSI MS-7984                         | 1         | 0.54%   |
| MSI MS-7977                         | 1         | 0.54%   |
| MSI MS-7974                         | 1         | 0.54%   |
| MSI MS-7851                         | 1         | 0.54%   |
| MSI GL73 8SE                        | 1         | 0.54%   |
| Microtech ebookPro                  | 1         | 0.54%   |
| Medion P15648                       | 1         | 0.54%   |
| Medion E6220                        | 1         | 0.54%   |
| LincPlus LINNCPLUS P1               | 1         | 0.54%   |
| Lenovo Z50-70 20354                 | 1         | 0.54%   |
| Lenovo Yoga 7 15ITL5 82BJ           | 1         | 0.54%   |
| Lenovo Yoga 2 11 20332              | 1         | 0.54%   |
| Lenovo V55t-15ARE 11KJ0036TX        | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 12        | 6.49%   |
| HP Laptop              | 9         | 4.86%   |
| Lenovo ThinkPad        | 8         | 4.32%   |
| Dell Latitude          | 8         | 4.32%   |
| Lenovo IdeaPad         | 7         | 3.78%   |
| Dell Inspiron          | 7         | 3.78%   |
| HP Pavilion            | 5         | 2.7%    |
| ASUS VivoBook          | 5         | 2.7%    |
| Dell Precision         | 4         | 2.16%   |
| ASUS PRIME             | 4         | 2.16%   |
| Toshiba Satellite      | 3         | 1.62%   |
| HP EliteBook           | 3         | 1.62%   |
| HP Compaq              | 3         | 1.62%   |
| Dell XPS               | 3         | 1.62%   |
| Dell Vostro            | 3         | 1.62%   |
| ASUS ROG               | 3         | 1.62%   |
| Unknown                | 3         | 1.62%   |
| Lenovo Yoga            | 2         | 1.08%   |
| Lenovo ThinkCentre     | 2         | 1.08%   |
| Lenovo Legion          | 2         | 1.08%   |
| HP ProBook             | 2         | 1.08%   |
| HP 255                 | 2         | 1.08%   |
| Dell OptiPlex          | 2         | 1.08%   |
| Wortmann AG TERRA      | 1         | 0.54%   |
| Sony SVF1532W4E        | 1         | 0.54%   |
| Sony SVE1713Y1RB       | 1         | 0.54%   |
| Sony SVE1512G1RW       | 1         | 0.54%   |
| Samsung DeskTop        | 1         | 0.54%   |
| Samsung 730QDA         | 1         | 0.54%   |
| Samsung 355V4C         | 1         | 0.54%   |
| Philco 10D             | 1         | 0.54%   |
| Pegatron Pro           | 1         | 0.54%   |
| Panasonic CF-H2BJJHZDE | 1         | 0.54%   |
| Packard Bell DOT       | 1         | 0.54%   |
| Multilaser PC150       | 1         | 0.54%   |
| MSI U180               | 1         | 0.54%   |
| MSI MS-7C52            | 1         | 0.54%   |
| MSI MS-7B79            | 1         | 0.54%   |
| MSI MS-7B23            | 1         | 0.54%   |
| MSI MS-7B17            | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 23        | 12.43%  |
| 2012 | 21        | 11.35%  |
| 2020 | 16        | 8.65%   |
| 2018 | 15        | 8.11%   |
| 2019 | 14        | 7.57%   |
| 2017 | 13        | 7.03%   |
| 2013 | 13        | 7.03%   |
| 2010 | 11        | 5.95%   |
| 2015 | 9         | 4.86%   |
| 2016 | 8         | 4.32%   |
| 2009 | 8         | 4.32%   |
| 2014 | 7         | 3.78%   |
| 2008 | 7         | 3.78%   |
| 2022 | 6         | 3.24%   |
| 2007 | 6         | 3.24%   |
| 2011 | 5         | 2.7%    |
| 2006 | 3         | 1.62%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 120       | 64.86%  |
| Desktop     | 56        | 30.27%  |
| Convertible | 4         | 2.16%   |
| Tablet      | 2         | 1.08%   |
| All in one  | 2         | 1.08%   |
| Mini pc     | 1         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 167       | 89.3%   |
| Enabled  | 20        | 10.7%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 99.46%  |
| Yes  | 1         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 48        | 25.81%  |
| 3.01-4.0    | 36        | 19.35%  |
| 16.01-24.0  | 36        | 19.35%  |
| 8.01-16.0   | 34        | 18.28%  |
| 1.01-2.0    | 11        | 5.91%   |
| 32.01-64.0  | 10        | 5.38%   |
| 2.01-3.0    | 5         | 2.69%   |
| 24.01-32.0  | 3         | 1.61%   |
| 64.01-256.0 | 3         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 75        | 39.06%  |
| 2.01-3.0   | 67        | 34.9%   |
| 3.01-4.0   | 20        | 10.42%  |
| 4.01-8.0   | 17        | 8.85%   |
| 0.51-1.0   | 9         | 4.69%   |
| 8.01-16.0  | 3         | 1.56%   |
| 32.01-64.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 66.84%  |
| 2      | 39        | 20.86%  |
| 3      | 15        | 8.02%   |
| 4      | 6         | 3.21%   |
| 6      | 1         | 0.53%   |
| 5      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 63.24%  |
| Yes       | 68        | 36.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 153       | 82.7%   |
| No        | 32        | 17.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 80.54%  |
| No        | 36        | 19.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 58.92%  |
| No        | 76        | 41.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 35        | 18.72%  |
| Russia      | 20        | 10.7%   |
| Germany     | 20        | 10.7%   |
| Brazil      | 13        | 6.95%   |
| UK          | 11        | 5.88%   |
| France      | 10        | 5.35%   |
| Italy       | 9         | 4.81%   |
| Canada      | 8         | 4.28%   |
| Spain       | 7         | 3.74%   |
| Poland      | 6         | 3.21%   |
| Mexico      | 4         | 2.14%   |
| Sweden      | 3         | 1.6%    |
| Belgium     | 3         | 1.6%    |
| Vietnam     | 2         | 1.07%   |
| South Korea | 2         | 1.07%   |
| Romania     | 2         | 1.07%   |
| Hungary     | 2         | 1.07%   |
| Chile       | 2         | 1.07%   |
| Bolivia     | 2         | 1.07%   |
| Austria     | 2         | 1.07%   |
| Australia   | 2         | 1.07%   |
| Venezuela   | 1         | 0.53%   |
| Turkey      | 1         | 0.53%   |
| Slovenia    | 1         | 0.53%   |
| Slovakia    | 1         | 0.53%   |
| Portugal    | 1         | 0.53%   |
| Peru        | 1         | 0.53%   |
| Paraguay    | 1         | 0.53%   |
| Norway      | 1         | 0.53%   |
| Nicaragua   | 1         | 0.53%   |
| New Zealand | 1         | 0.53%   |
| Malaysia    | 1         | 0.53%   |
| Lithuania   | 1         | 0.53%   |
| Latvia      | 1         | 0.53%   |
| Kenya       | 1         | 0.53%   |
| Ireland     | 1         | 0.53%   |
| India       | 1         | 0.53%   |
| Finland     | 1         | 0.53%   |
| Ecuador     | 1         | 0.53%   |
| Denmark     | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 6         | 3.17%   |
| St Petersburg         | 2         | 1.06%   |
| Rome                  | 2         | 1.06%   |
| Oruro                 | 2         | 1.06%   |
| Neasden               | 2         | 1.06%   |
| Montreal              | 2         | 1.06%   |
| Melbourne             | 2         | 1.06%   |
| London                | 2         | 1.06%   |
| Krakow                | 2         | 1.06%   |
| Freiburg im Breisgau  | 2         | 1.06%   |
| Berlin                | 2         | 1.06%   |
| Bend                  | 2         | 1.06%   |
| Belém                | 2         | 1.06%   |
| Zaragoza              | 1         | 0.53%   |
| Wroclaw               | 1         | 0.53%   |
| Voronezh              | 1         | 0.53%   |
| Volta Redonda         | 1         | 0.53%   |
| Vitória da Conquista | 1         | 0.53%   |
| Vincennes             | 1         | 0.53%   |
| Vilshofen             | 1         | 0.53%   |
| Vilnius               | 1         | 0.53%   |
| Viggianello           | 1         | 0.53%   |
| Viet Tri              | 1         | 0.53%   |
| Vicente Guerrero      | 1         | 0.53%   |
| Veurne                | 1         | 0.53%   |
| Vaslui                | 1         | 0.53%   |
| Vancouver             | 1         | 0.53%   |
| Valsoyfjord           | 1         | 0.53%   |
| Ulyanovsk             | 1         | 0.53%   |
| Uiwang                | 1         | 0.53%   |
| Turku                 | 1         | 0.53%   |
| Tula                  | 1         | 0.53%   |
| Troisdorf             | 1         | 0.53%   |
| Trieste               | 1         | 0.53%   |
| Toulouse              | 1         | 0.53%   |
| Toronto               | 1         | 0.53%   |
| Tolyatti              | 1         | 0.53%   |
| Toledo                | 1         | 0.53%   |
| Toccoa                | 1         | 0.53%   |
| Tipton                | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 39        | 51     | 15.6%   |
| Seagate                        | 35        | 42     | 14%     |
| Samsung Electronics            | 29        | 42     | 11.6%   |
| SanDisk                        | 16        | 18     | 6.4%    |
| Kingston                       | 13        | 13     | 5.2%    |
| Unknown                        | 11        | 15     | 4.4%    |
| Toshiba                        | 11        | 12     | 4.4%    |
| Hitachi                        | 10        | 11     | 4%      |
| Crucial                        | 10        | 10     | 4%      |
| Intel                          | 7         | 7      | 2.8%    |
| SK hynix                       | 6         | 6      | 2.4%    |
| Micron Technology              | 5         | 5      | 2%      |
| Apple                          | 5         | 10     | 2%      |
| PNY                            | 4         | 4      | 1.6%    |
| A-DATA Technology              | 4         | 5      | 1.6%    |
| Patriot                        | 3         | 3      | 1.2%    |
| Team                           | 2         | 2      | 0.8%    |
| Phison                         | 2         | 2      | 0.8%    |
| KingSpec                       | 2         | 2      | 0.8%    |
| HGST                           | 2         | 2      | 0.8%    |
| China                          | 2         | 3      | 0.8%    |
| Unknown                        | 2         | 2      | 0.8%    |
| XrayDisk                       | 1         | 2      | 0.4%    |
| Union Memory                   | 1         | 1      | 0.4%    |
| UMIS                           | 1         | 1      | 0.4%    |
| Transcend                      | 1         | 2      | 0.4%    |
| SSD PHIS                       | 1         | 1      | 0.4%    |
| SPCC                           | 1         | 1      | 0.4%    |
| Solid State Storage Technology | 1         | 1      | 0.4%    |
| ShiJi                          | 1         | 1      | 0.4%    |
| SABRENT                        | 1         | 1      | 0.4%    |
| Phison Electronics             | 1         | 1      | 0.4%    |
| Oyen                           | 1         | 1      | 0.4%    |
| ORICO                          | 1         | 1      | 0.4%    |
| OCZ-VERTEX                     | 1         | 1      | 0.4%    |
| Netac                          | 1         | 1      | 0.4%    |
| Microtech                      | 1         | 2      | 0.4%    |
| Micron/Crucial Technology      | 1         | 2      | 0.4%    |
| LITEON                         | 1         | 1      | 0.4%    |
| KIOXIA                         | 1         | 4      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB          | 6         | 2.22%   |
| Samsung SSD 850 EVO 250GB               | 4         | 1.48%   |
| Unknown SD/MMC/MS PRO 1TB               | 3         | 1.11%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 1.11%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 1.11%   |
| Samsung SSD 850 EVO 500GB               | 3         | 1.11%   |
| Micron NVMe SSD Drive 512GB             | 3         | 1.11%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 1.11%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 1.11%   |
| Crucial CT480BX500SSD1 480GB            | 3         | 1.11%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 0.74%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 2         | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 0.74%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB    | 2         | 0.74%   |
| Unknown SC128  128GB                    | 2         | 0.74%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.74%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.74%   |
| Seagate ST3320418AS 320GB               | 2         | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB          | 2         | 0.74%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.74%   |
| SanDisk SDSSDA240G 240GB                | 2         | 0.74%   |
| Samsung SSD 980 PRO 1TB                 | 2         | 0.74%   |
| Samsung SSD 970 EVO Plus 1TB            | 2         | 0.74%   |
| Samsung PM991a NVMe 512GB               | 2         | 0.74%   |
| Samsung NVMe SSD Drive 500GB            | 2         | 0.74%   |
| Samsung NVMe SSD Drive 250GB            | 2         | 0.74%   |
| Patriot Burst 240GB SSD                 | 2         | 0.74%   |
| Crucial CT525MX300SSD1 528GB            | 2         | 0.74%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 0.74%   |
| Apple SSD SD0128F 121GB                 | 2         | 0.74%   |
| A-DATA SU650 120GB SSD                  | 2         | 0.74%   |
| Unknown                                 | 2         | 0.74%   |
| XrayDisk 480GB                          | 1         | 0.37%   |
| XrayDisk 1TB                            | 1         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.37%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD        | 1         | 0.37%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.37%   |
| WDC WDBNCE5000PNC 500GB SSD             | 1         | 0.37%   |
| WDC WD7500BPVT-22HXZT3 752GB            | 1         | 0.37%   |
| WDC WD60EZAZ-00ZGHB0 6TB                | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 42     | 36.84%  |
| WDC                 | 30        | 41     | 31.58%  |
| Hitachi             | 10        | 11     | 10.53%  |
| Toshiba             | 9         | 10     | 9.47%   |
| Unknown             | 3         | 3      | 3.16%   |
| Samsung Electronics | 2         | 2      | 2.11%   |
| HGST                | 2         | 2      | 2.11%   |
| SABRENT             | 1         | 1      | 1.05%   |
| Initio              | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |
| ASMedia             | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 18     | 13.79%  |
| Kingston            | 11        | 11     | 12.64%  |
| Crucial             | 10        | 10     | 11.49%  |
| SanDisk             | 7         | 7      | 8.05%   |
| PNY                 | 4         | 4      | 4.6%    |
| Apple               | 4         | 4      | 4.6%    |
| A-DATA Technology   | 4         | 5      | 4.6%    |
| WDC                 | 3         | 3      | 3.45%   |
| Patriot             | 3         | 3      | 3.45%   |
| Intel               | 3         | 3      | 3.45%   |
| Team                | 2         | 2      | 2.3%    |
| KingSpec            | 2         | 2      | 2.3%    |
| China               | 2         | 3      | 2.3%    |
| Unknown             | 2         | 2      | 2.3%    |
| Transcend           | 1         | 2      | 1.15%   |
| Toshiba             | 1         | 1      | 1.15%   |
| SSD PHIS            | 1         | 1      | 1.15%   |
| SK hynix            | 1         | 1      | 1.15%   |
| ORICO               | 1         | 1      | 1.15%   |
| OCZ-VERTEX          | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Microtech           | 1         | 2      | 1.15%   |
| Micron Technology   | 1         | 1      | 1.15%   |
| LITEON              | 1         | 1      | 1.15%   |
| HXY                 | 1         | 1      | 1.15%   |
| Hewlett-Packard     | 1         | 1      | 1.15%   |
| GOODRAM             | 1         | 1      | 1.15%   |
| Gigabyte Technology | 1         | 1      | 1.15%   |
| FORESEE             | 1         | 1      | 1.15%   |
| BHT                 | 1         | 2      | 1.15%   |
| Acer                | 1         | 1      | 1.15%   |
| 2.5''               | 1         | 1      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 87        | 115    | 37.5%   |
| SSD     | 79        | 98     | 34.05%  |
| NVMe    | 52        | 73     | 22.41%  |
| MMC     | 8         | 11     | 3.45%   |
| Unknown | 6         | 8      | 2.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 205    | 66.98%  |
| NVMe | 52        | 73     | 24.53%  |
| SAS  | 10        | 16     | 4.72%   |
| MMC  | 8         | 11     | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 106       | 137    | 64.63%  |
| 0.51-1.0   | 42        | 56     | 25.61%  |
| 1.01-2.0   | 8         | 9      | 4.88%   |
| 2.01-3.0   | 3         | 6      | 1.83%   |
| 4.01-10.0  | 3         | 3      | 1.83%   |
| 3.01-4.0   | 2         | 2      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 53        | 28.34%  |
| 251-500        | 47        | 25.13%  |
| 501-1000       | 24        | 12.83%  |
| 1001-2000      | 18        | 9.63%   |
| 51-100         | 14        | 7.49%   |
| 1-20           | 10        | 5.35%   |
| More than 3000 | 8         | 4.28%   |
| 21-50          | 8         | 4.28%   |
| 2001-3000      | 5         | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 89        | 46.35%  |
| 21-50          | 36        | 18.75%  |
| 51-100         | 19        | 9.9%    |
| 101-250        | 15        | 7.81%   |
| 251-500        | 13        | 6.77%   |
| 501-1000       | 11        | 5.73%   |
| 1001-2000      | 5         | 2.6%    |
| 2001-3000      | 3         | 1.56%   |
| More than 3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB    | 1         | 1      | 11.11%  |
| WDC WD3200BEVT-60ZCT1 320GB     | 1         | 1      | 11.11%  |
| Seagate ST500LT032-1E9142 500GB | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 11.11%  |
| Seagate ST3250318AS 250GB       | 1         | 1      | 11.11%  |
| Phison ES 512GB                 | 1         | 1      | 11.11%  |
| Intel SSDSCKKF256G8 SATA 256GB  | 1         | 1      | 11.11%  |
| Hitachi HTS547575A9E384 752GB   | 1         | 1      | 11.11%  |
| HGST HTS545050A7E680 500GB      | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| WDC     | 1         | 2      | 12.5%   |
| Phison  | 1         | 1      | 12.5%   |
| Intel   | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |
| HGST    | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 1         | 2      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 75%     |
| NVMe | 1         | 1      | 12.5%   |
| SSD  | 1         | 1      | 12.5%   |

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
| Detected | 127       | 207    | 64.14%  |
| Works    | 63        | 89     | 31.82%  |
| Malfunc  | 8         | 9      | 4.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 129       | 56.09%  |
| AMD                            | 35        | 15.22%  |
| Samsung Electronics            | 18        | 7.83%   |
| SanDisk                        | 12        | 5.22%   |
| SK hynix                       | 5         | 2.17%   |
| Phison Electronics             | 4         | 1.74%   |
| Micron Technology              | 4         | 1.74%   |
| Marvell Technology Group       | 3         | 1.3%    |
| ASMedia Technology             | 3         | 1.3%    |
| Union Memory (Shenzhen)        | 2         | 0.87%   |
| Nvidia                         | 2         | 0.87%   |
| KIOXIA                         | 2         | 0.87%   |
| Kingston Technology Company    | 2         | 0.87%   |
| JMicron Technology             | 2         | 0.87%   |
| Broadcom / LSI                 | 2         | 0.87%   |
| Toshiba America Info Systems   | 1         | 0.43%   |
| Solid State Storage Technology | 1         | 0.43%   |
| Micron/Crucial Technology      | 1         | 0.43%   |
| LSI Logic / Symbios Logic      | 1         | 0.43%   |
| Apple                          | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 11.07%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 4.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 3.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 3.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 2.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 6         | 2.29%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 2.29%   |
| SanDisk Non-Volatile memory controller                                         | 5         | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 1.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.91%   |
| Phison PS5013 E13 NVMe Controller                                              | 4         | 1.53%   |
| Micron Non-Volatile memory controller                                          | 4         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.53%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.53%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.15%   |
| AMD FCH SATA Controller D                                                      | 3         | 1.15%   |
| SK hynix Gold P31 SSD                                                          | 2         | 0.76%   |
| SK hynix BC511                                                                 | 2         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.76%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 2         | 0.76%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 0.76%   |
| Intel SSD 660P Series                                                          | 2         | 0.76%   |
| Intel SSD 600P Series                                                          | 2         | 0.76%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 135       | 57.2%   |
| NVMe | 53        | 22.46%  |
| RAID | 23        | 9.75%   |
| IDE  | 23        | 9.75%   |
| SAS  | 1         | 0.42%   |
| SCSI | 1         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 140       | 75.68%  |
| AMD    | 45        | 24.32%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 2.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 2.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 2.16%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 2.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 2.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 1.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.62%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2         | 1.08%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.08%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 1.08%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 1.08%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.08%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.08%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.08%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2         | 1.08%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 2         | 1.08%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2         | 1.08%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.08%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.54%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1         | 0.54%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.54%   |
| Intel Xeon CPU 3.40GHz                      | 1         | 0.54%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.54%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.54%   |
| Intel Pentium Gold G7400                    | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.54%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.54%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.54%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.54%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.54%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 34        | 18.38%  |
| Intel Core i7           | 26        | 14.05%  |
| Other                   | 16        | 8.65%   |
| Intel Core i3           | 14        | 7.57%   |
| AMD Ryzen 5             | 11        | 5.95%   |
| Intel Celeron           | 9         | 4.86%   |
| AMD Ryzen 7             | 9         | 4.86%   |
| Intel Core 2 Duo        | 8         | 4.32%   |
| Intel Pentium           | 7         | 3.78%   |
| Intel Atom              | 7         | 3.78%   |
| AMD Ryzen 3             | 7         | 3.78%   |
| Intel Xeon              | 6         | 3.24%   |
| Intel Pentium Dual-Core | 3         | 1.62%   |
| Intel Core 2            | 2         | 1.08%   |
| Intel Celeron M         | 2         | 1.08%   |
| AMD E2                  | 2         | 1.08%   |
| AMD E1                  | 2         | 1.08%   |
| AMD Athlon II X2        | 2         | 1.08%   |
| AMD Athlon              | 2         | 1.08%   |
| AMD A10                 | 2         | 1.08%   |
| Intel Pentium Silver    | 1         | 0.54%   |
| Intel Pentium M         | 1         | 0.54%   |
| Intel Pentium Gold      | 1         | 0.54%   |
| Intel Pentium D         | 1         | 0.54%   |
| Intel Core i9           | 1         | 0.54%   |
| Intel Core 2 Quad       | 1         | 0.54%   |
| Intel Core 2 Extreme    | 1         | 0.54%   |
| AMD Ryzen 9             | 1         | 0.54%   |
| AMD FX                  | 1         | 0.54%   |
| AMD C-50                | 1         | 0.54%   |
| AMD Athlon II           | 1         | 0.54%   |
| AMD A8                  | 1         | 0.54%   |
| AMD A6                  | 1         | 0.54%   |
| AMD A4                  | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 88        | 47.57%  |
| 4      | 64        | 34.59%  |
| 8      | 14        | 7.57%   |
| 6      | 12        | 6.49%   |
| 1      | 5         | 2.7%    |
| 16     | 2         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 181       | 97.84%  |
| 2      | 4         | 2.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 119       | 64.32%  |
| 1      | 66        | 35.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 181       | 97.84%  |
| 32-bit         | 4         | 2.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 16        | 8.56%   |
| 0x806c1    | 12        | 6.42%   |
| 0x08108109 | 11        | 5.88%   |
| 0x206a7    | 9         | 4.81%   |
| 0x40651    | 7         | 3.74%   |
| Unknown    | 7         | 3.74%   |
| 0x806ec    | 6         | 3.21%   |
| 0x1067a    | 6         | 3.21%   |
| 0x08608103 | 6         | 3.21%   |
| 0x806e9    | 5         | 2.67%   |
| 0x406e3    | 5         | 2.67%   |
| 0x306c3    | 5         | 2.67%   |
| 0x6fd      | 4         | 2.14%   |
| 0x506e3    | 4         | 2.14%   |
| 0x30661    | 4         | 2.14%   |
| 0x906ed    | 3         | 1.6%    |
| 0x906ea    | 3         | 1.6%    |
| 0x806ea    | 3         | 1.6%    |
| 0x20652    | 3         | 1.6%    |
| 0x106e5    | 3         | 1.6%    |
| 0x10676    | 3         | 1.6%    |
| 0x0a50000c | 3         | 1.6%    |
| 0x906c0    | 2         | 1.07%   |
| 0x90675    | 2         | 1.07%   |
| 0x806eb    | 2         | 1.07%   |
| 0x706e5    | 2         | 1.07%   |
| 0x706a1    | 2         | 1.07%   |
| 0x6f6      | 2         | 1.07%   |
| 0x406c4    | 2         | 1.07%   |
| 0x206d7    | 2         | 1.07%   |
| 0x08101016 | 2         | 1.07%   |
| 0x06006705 | 2         | 1.07%   |
| 0x06001119 | 2         | 1.07%   |
| 0x010000c8 | 2         | 1.07%   |
| 0xf65      | 1         | 0.53%   |
| 0xf43      | 1         | 0.53%   |
| 0xa0671    | 1         | 0.53%   |
| 0xa0653    | 1         | 0.53%   |
| 0xa0652    | 1         | 0.53%   |
| 0x906e9    | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 12.37%  |
| IvyBridge     | 17        | 9.14%   |
| Haswell       | 13        | 6.99%   |
| Zen+          | 12        | 6.45%   |
| TigerLake     | 12        | 6.45%   |
| SandyBridge   | 11        | 5.91%   |
| Unknown       | 11        | 5.91%   |
| Skylake       | 9         | 4.84%   |
| Penryn        | 9         | 4.84%   |
| Core          | 7         | 3.76%   |
| Bonnell       | 6         | 3.23%   |
| Zen 3         | 5         | 2.69%   |
| Westmere      | 5         | 2.69%   |
| Zen           | 4         | 2.15%   |
| Silvermont    | 4         | 2.15%   |
| Nehalem       | 4         | 2.15%   |
| Excavator     | 4         | 2.15%   |
| Piledriver    | 3         | 1.61%   |
| K10           | 3         | 1.61%   |
| IceLake       | 3         | 1.61%   |
| Goldmont plus | 3         | 1.61%   |
| Zen 2         | 2         | 1.08%   |
| Tremont       | 2         | 1.08%   |
| Puma          | 2         | 1.08%   |
| P6            | 2         | 1.08%   |
| NetBurst      | 2         | 1.08%   |
| Jaguar        | 2         | 1.08%   |
| CometLake     | 2         | 1.08%   |
| Broadwell     | 2         | 1.08%   |
| Goldmont      | 1         | 0.54%   |
| Bobcat        | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 47.89%  |
| Nvidia | 61        | 28.64%  |
| AMD    | 50        | 23.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 5.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 2.73%   |
| AMD Lucienne                                                                             | 6         | 2.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.27%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 1.82%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.82%   |
| Intel HD Graphics 620                                                                    | 4         | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.82%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.36%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.36%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.36%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.36%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.91%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.91%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.91%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.91%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.91%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.91%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.91%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.91%   |
| AMD Cezanne                                                                              | 2         | 0.91%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 79        | 42.47%  |
| 1 x Nvidia     | 38        | 20.43%  |
| 1 x AMD        | 38        | 20.43%  |
| Intel + Nvidia | 19        | 10.22%  |
| AMD + Nvidia   | 5         | 2.69%   |
| 2 x AMD        | 4         | 2.15%   |
| Intel + AMD    | 3         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 155       | 82.89%  |
| Proprietary | 20        | 10.7%   |
| Unknown     | 12        | 6.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 50.27%  |
| 0.01-0.5   | 35        | 18.72%  |
| 1.01-2.0   | 29        | 15.51%  |
| 3.01-4.0   | 14        | 7.49%   |
| 0.51-1.0   | 11        | 5.88%   |
| 5.01-6.0   | 3         | 1.6%    |
| 2.01-3.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 16.57%  |
| LG Display              | 20        | 11.05%  |
| BOE                     | 20        | 11.05%  |
| Chimei Innolux          | 17        | 9.39%   |
| Samsung Electronics     | 16        | 8.84%   |
| Goldstar                | 7         | 3.87%   |
| Hewlett-Packard         | 6         | 3.31%   |
| BenQ                    | 6         | 3.31%   |
| Dell                    | 5         | 2.76%   |
| Apple                   | 5         | 2.76%   |
| Philips                 | 4         | 2.21%   |
| LG Philips              | 4         | 2.21%   |
| InfoVision              | 4         | 2.21%   |
| Unknown                 | 3         | 1.66%   |
| Chi Mei Optoelectronics | 3         | 1.66%   |
| Ancor Communications    | 3         | 1.66%   |
| Acer                    | 3         | 1.66%   |
| Sharp                   | 2         | 1.1%    |
| PANDA                   | 2         | 1.1%    |
| Lenovo                  | 2         | 1.1%    |
| HannStar                | 2         | 1.1%    |
| AOC                     | 2         | 1.1%    |
| ___                     | 1         | 0.55%   |
| ViewSonic               | 1         | 0.55%   |
| Vestel Elektronik       | 1         | 0.55%   |
| TR_                     | 1         | 0.55%   |
| Sony                    | 1         | 0.55%   |
| Quanta Display          | 1         | 0.55%   |
| PLN                     | 1         | 0.55%   |
| Planar                  | 1         | 0.55%   |
| MStar                   | 1         | 0.55%   |
| Medion                  | 1         | 0.55%   |
| Lenovo Group Limited    | 1         | 0.55%   |
| Insignia                | 1         | 0.55%   |
| Iiyama                  | 1         | 0.55%   |
| DENON                   | 1         | 0.55%   |
| ASUSTek Computer        | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.62%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch            | 2         | 1.08%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 2         | 1.08%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch           | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch        | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch          | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch         | 2         | 1.08%   |
| ___ LCD TV ___0101 1366x768                                            | 1         | 0.54%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch               | 1         | 0.54%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.54%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                     | 1         | 0.54%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                   | 1         | 0.54%   |
| Unknown LCD Monitor SAMSUNG                                            | 1         | 0.54%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                   | 1         | 0.54%   |
| Sony LCD Monitor TV 3840x1080                                          | 1         | 0.54%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.54%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch                | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch   | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch   | 1         | 0.54%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch     | 1         | 0.54%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                       | 1         | 0.54%   |
| Samsung Electronics LCD Monitor S27R65                                 | 1         | 0.54%   |
| Samsung Electronics LCD Monitor C27F390                                | 1         | 0.54%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch     | 1         | 0.54%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 0.54%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch        | 1         | 0.54%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                    | 1         | 0.54%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                  | 1         | 0.54%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch              | 1         | 0.54%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                | 1         | 0.54%   |
| Philips LCD Monitor PHL 242V8 1920x1080                                | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 79        | 45.4%   |
| 1366x768 (WXGA)    | 36        | 20.69%  |
| 1600x900 (HD+)     | 10        | 5.75%   |
| 1440x900 (WXGA+)   | 7         | 4.02%   |
| 1920x1200 (WUXGA)  | 6         | 3.45%   |
| 1680x1050 (WSXGA+) | 6         | 3.45%   |
| 3840x2160 (4K)     | 4         | 2.3%    |
| 1280x800 (WXGA)    | 4         | 2.3%    |
| 1024x600           | 4         | 2.3%    |
| 2560x1440 (QHD)    | 3         | 1.72%   |
| Unknown            | 3         | 1.72%   |
| 3840x1080          | 2         | 1.15%   |
| 2560x1080          | 2         | 1.15%   |
| 1280x1024 (SXGA)   | 2         | 1.15%   |
| 4480x1440          | 1         | 0.57%   |
| 2880x1800          | 1         | 0.57%   |
| 2560x1600          | 1         | 0.57%   |
| 2256x1504          | 1         | 0.57%   |
| 1280x768           | 1         | 0.57%   |
| 1280x720 (HD)      | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 31.84%  |
| 13      | 22        | 12.29%  |
| 14      | 16        | 8.94%   |
| Unknown | 15        | 8.38%   |
| 17      | 13        | 7.26%   |
| 24      | 9         | 5.03%   |
| 21      | 9         | 5.03%   |
| 27      | 7         | 3.91%   |
| 23      | 6         | 3.35%   |
| 10      | 4         | 2.23%   |
| 22      | 3         | 1.68%   |
| 20      | 3         | 1.68%   |
| 72      | 2         | 1.12%   |
| 19      | 2         | 1.12%   |
| 84      | 1         | 0.56%   |
| 34      | 1         | 0.56%   |
| 32      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 28      | 1         | 0.56%   |
| 25      | 1         | 0.56%   |
| 18      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |
| 12      | 1         | 0.56%   |
| 11      | 1         | 0.56%   |
| 8       | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 47.7%   |
| 501-600     | 21        | 12.07%  |
| 201-300     | 17        | 9.77%   |
| 401-500     | 15        | 8.62%   |
| 351-400     | 15        | 8.62%   |
| Unknown     | 15        | 8.62%   |
| 1501-2000   | 3         | 1.72%   |
| 701-800     | 2         | 1.15%   |
| 601-700     | 2         | 1.15%   |
| 101-200     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 124       | 75.15%  |
| 16/10   | 22        | 13.33%  |
| Unknown | 14        | 8.48%   |
| 5/4     | 2         | 1.21%   |
| 21/9    | 2         | 1.21%   |
| 3/2     | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 32.02%  |
| 81-90          | 28        | 15.73%  |
| 201-250        | 23        | 12.92%  |
| Unknown        | 15        | 8.43%   |
| 71-80          | 10        | 5.62%   |
| 121-130        | 8         | 4.49%   |
| 301-350        | 7         | 3.93%   |
| 251-300        | 5         | 2.81%   |
| 151-200        | 5         | 2.81%   |
| 41-50          | 4         | 2.25%   |
| 131-140        | 4         | 2.25%   |
| More than 1000 | 3         | 1.69%   |
| 351-500        | 3         | 1.69%   |
| 141-150        | 2         | 1.12%   |
| 61-70          | 1         | 0.56%   |
| 51-60          | 1         | 0.56%   |
| 1-40           | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 31.82%  |
| 101-120       | 51        | 28.98%  |
| 51-100        | 43        | 24.43%  |
| Unknown       | 15        | 8.52%   |
| 161-240       | 8         | 4.55%   |
| 1-50          | 2         | 1.14%   |
| More than 240 | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 156       | 83.87%  |
| 2     | 16        | 8.6%    |
| 0     | 11        | 5.91%   |
| 3     | 3         | 1.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 101       | 37%     |
| Intel                    | 82        | 30.04%  |
| Qualcomm Atheros         | 36        | 13.19%  |
| Broadcom                 | 19        | 6.96%   |
| Ralink Technology        | 5         | 1.83%   |
| Marvell Technology Group | 5         | 1.83%   |
| Broadcom Limited         | 4         | 1.47%   |
| TP-Link                  | 2         | 0.73%   |
| Samsung Electronics      | 2         | 0.73%   |
| Nvidia                   | 2         | 0.73%   |
| Xiaomi                   | 1         | 0.37%   |
| Ralink                   | 1         | 0.37%   |
| OnePlus                  | 1         | 0.37%   |
| NetGear                  | 1         | 0.37%   |
| Microchip Technology     | 1         | 0.37%   |
| Mercucys                 | 1         | 0.37%   |
| MediaTek                 | 1         | 0.37%   |
| JMicron Technology       | 1         | 0.37%   |
| Huawei Technologies      | 1         | 0.37%   |
| Google                   | 1         | 0.37%   |
| Fibocom                  | 1         | 0.37%   |
| Edimax Technology        | 1         | 0.37%   |
| Dell                     | 1         | 0.37%   |
| Davicom Semiconductor    | 1         | 0.37%   |
| Belkin Components        | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 17.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 2.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.82%   |
| Intel Wireless 3165                                               | 6         | 1.82%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.52%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4         | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.21%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.91%   |
| Intel Wireless 7260                                               | 3         | 0.91%   |
| Intel WiFi Link 5100                                              | 3         | 0.91%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.91%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.61%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.61%   |
| Realtek 802.11ac NIC                                              | 2         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 35.85%  |
| Realtek Semiconductor | 44        | 27.67%  |
| Qualcomm Atheros      | 25        | 15.72%  |
| Broadcom              | 15        | 9.43%   |
| Ralink Technology     | 5         | 3.14%   |
| Broadcom Limited      | 4         | 2.52%   |
| TP-Link               | 2         | 1.26%   |
| Ralink                | 1         | 0.63%   |
| NetGear               | 1         | 0.63%   |
| Mercucys              | 1         | 0.63%   |
| MediaTek              | 1         | 0.63%   |
| Fibocom               | 1         | 0.63%   |
| Edimax Technology     | 1         | 0.63%   |
| Belkin Components     | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 7.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 4.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.66%   |
| Intel Wireless 3165                                            | 6         | 3.66%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.05%   |
| Intel Wireless 8265 / 8275                                     | 5         | 3.05%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 3.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 2.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.83%   |
| Intel Wireless 7260                                            | 3         | 1.83%   |
| Intel WiFi Link 5100                                           | 3         | 1.83%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.83%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.22%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 1.22%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.22%   |
| Realtek 802.11ac NIC                                           | 2         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.22%   |
| Intel Wireless 8260                                            | 2         | 1.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.22%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.22%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.61%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.61%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 82        | 50.93%  |
| Intel                    | 43        | 26.71%  |
| Qualcomm Atheros         | 16        | 9.94%   |
| Marvell Technology Group | 5         | 3.11%   |
| Broadcom                 | 4         | 2.48%   |
| Samsung Electronics      | 2         | 1.24%   |
| Nvidia                   | 2         | 1.24%   |
| Xiaomi                   | 1         | 0.62%   |
| OnePlus                  | 1         | 0.62%   |
| Microchip Technology     | 1         | 0.62%   |
| JMicron Technology       | 1         | 0.62%   |
| Huawei Technologies      | 1         | 0.62%   |
| Google                   | 1         | 0.62%   |
| Davicom Semiconductor    | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 35.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 7.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 6.71%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.83%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.83%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.22%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.22%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.22%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.22%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.22%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.22%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.22%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.61%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.61%   |
| OnePlus OnePlus                                                   | 1         | 0.61%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.61%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 0.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.61%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.61%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.61%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 152       | 50.17%  |
| WiFi     | 149       | 49.17%  |
| Modem    | 2         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 59.16%  |
| Ethernet | 78        | 40.84%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 104       | 56.22%  |
| 1     | 77        | 41.62%  |
| 0     | 4         | 2.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 140       | 75.27%  |
| Yes  | 46        | 24.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 42.34%  |
| Realtek Semiconductor           | 24        | 21.62%  |
| Foxconn / Hon Hai               | 6         | 5.41%   |
| Qualcomm Atheros Communications | 5         | 4.5%    |
| Lite-On Technology              | 5         | 4.5%    |
| Cambridge Silicon Radio         | 5         | 4.5%    |
| Dell                            | 4         | 3.6%    |
| Broadcom                        | 4         | 3.6%    |
| Apple                           | 4         | 3.6%    |
| Hewlett-Packard                 | 3         | 2.7%    |
| IMC Networks                    | 2         | 1.8%    |
| Foxconn International           | 2         | 1.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 15.32%  |
| Realtek Bluetooth Radio                             | 15        | 13.51%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 9.91%   |
| Intel AX201 Bluetooth                               | 10        | 9.01%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 5.41%   |
| Intel AX200 Bluetooth                               | 5         | 4.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 4.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.8%    |
| Lite-On Bluetooth Device                            | 2         | 1.8%    |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.8%    |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 1.8%    |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 1.8%    |
| Apple Bluetooth USB Host Controller                 | 2         | 1.8%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.9%    |
| Realtek RTL8821A Bluetooth                          | 1         | 0.9%    |
| Realtek RTL8723B Bluetooth                          | 1         | 0.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.9%    |
| Intel AX210 Bluetooth                               | 1         | 0.9%    |
| IMC Networks Bluetooth Radio                        | 1         | 0.9%    |
| IMC Networks Bluetooth Device                       | 1         | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.9%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.9%    |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.9%    |
| Foxconn / Hon Hai Acer Module                       | 1         | 0.9%    |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.9%    |
| Dell BT Mini-Receiver                               | 1         | 0.9%    |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 1         | 0.9%    |
| Broadcom BCM92045B3 ROM                             | 1         | 0.9%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.9%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.9%    |
| Apple Bluetooth Host Controller                     | 1         | 0.9%    |
| Apple Bluetooth HCI                                 | 1         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 136       | 56.43%  |
| AMD                   | 52        | 21.58%  |
| Nvidia                | 43        | 17.84%  |
| C-Media Electronics   | 3         | 1.24%   |
| Texas Instruments     | 2         | 0.83%   |
| Yamaha                | 1         | 0.41%   |
| Realtek Semiconductor | 1         | 0.41%   |
| JMTek                 | 1         | 0.41%   |
| GN Netcom             | 1         | 0.41%   |
| Audioengine           | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 9.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 5.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15        | 5.1%    |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 4.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 4.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 3.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 3.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 2.72%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.04%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.04%   |
| Nvidia High Definition Audio Controller                                    | 5         | 1.7%    |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 1.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.36%   |
| Nvidia GM204 High Definition Audio Controller                              | 3         | 1.02%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 1.02%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.02%   |
| AMD High Definition Audio Controller                                       | 3         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.68%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.68%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 23        | 29.87%  |
| SK hynix                     | 17        | 22.08%  |
| Unknown                      | 10        | 12.99%  |
| Micron Technology            | 5         | 6.49%   |
| Nanya Technology             | 3         | 3.9%    |
| Kingston                     | 3         | 3.9%    |
| Crucial                      | 3         | 3.9%    |
| Corsair                      | 3         | 3.9%    |
| A-DATA Technology            | 3         | 3.9%    |
| Unknown (ABCD)               | 2         | 2.6%    |
| Smart                        | 1         | 1.3%    |
| Ramaxel Technology           | 1         | 1.3%    |
| Patriot Memory (PDP Systems) | 1         | 1.3%    |
| G.Skill                      | 1         | 1.3%    |
| Unknown                      | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 2.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 2.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.47%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.23%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 1.23%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.23%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.23%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 1.23%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.23%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.23%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.23%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.23%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.23%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 1.23%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.23%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                        | 1         | 1.23%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.23%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.23%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 53.62%  |
| DDR3    | 22        | 31.88%  |
| SDRAM   | 3         | 4.35%   |
| LPDDR4  | 3         | 4.35%   |
| DDR2    | 2         | 2.9%    |
| DDR     | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 75.71%  |
| DIMM         | 14        | 20%     |
| Row Of Chips | 3         | 4.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 30        | 40.54%  |
| 4096  | 20        | 27.03%  |
| 2048  | 11        | 14.86%  |
| 16384 | 7         | 9.46%   |
| 32768 | 3         | 4.05%   |
| 1024  | 2         | 2.7%    |
| 512   | 1         | 1.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 18        | 24.66%  |
| 1600    | 18        | 24.66%  |
| 2667    | 10        | 13.7%   |
| 2400    | 8         | 10.96%  |
| 667     | 3         | 4.11%   |
| 1334    | 2         | 2.74%   |
| 1333    | 2         | 2.74%   |
| Unknown | 2         | 2.74%   |
| 4267    | 1         | 1.37%   |
| 4199    | 1         | 1.37%   |
| 3600    | 1         | 1.37%   |
| 3400    | 1         | 1.37%   |
| 3266    | 1         | 1.37%   |
| 2666    | 1         | 1.37%   |
| 2267    | 1         | 1.37%   |
| 2048    | 1         | 1.37%   |
| 1866    | 1         | 1.37%   |
| 1200    | 1         | 1.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Konica Minolta     | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Konica Minolta 185    | 1         | 33.33%  |
| HP OfficeJet Pro 8730 | 1         | 33.33%  |
| Brother MFC-L2685DW   | 1         | 33.33%  |

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
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 16.67%  |
| Microdia                               | 14        | 11.67%  |
| IMC Networks                           | 13        | 10.83%  |
| Acer                                   | 12        | 10%     |
| Suyin                                  | 9         | 7.5%    |
| Quanta                                 | 8         | 6.67%   |
| Sunplus Innovation Technology          | 7         | 5.83%   |
| Realtek Semiconductor                  | 7         | 5.83%   |
| Logitech                               | 4         | 3.33%   |
| Alcor Micro                            | 4         | 3.33%   |
| Luxvisions Innotech Limited            | 3         | 2.5%    |
| Z-Star Microelectronics                | 2         | 1.67%   |
| Syntek                                 | 2         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.67%   |
| Unknown                                | 1         | 0.83%   |
| Pixart Imaging                         | 1         | 0.83%   |
| OmniVision Technologies                | 1         | 0.83%   |
| MacroSilicon                           | 1         | 0.83%   |
| Lite-On Technology                     | 1         | 0.83%   |
| Lenovo                                 | 1         | 0.83%   |
| Intel                                  | 1         | 0.83%   |
| Importek                               | 1         | 0.83%   |
| icSpring                               | 1         | 0.83%   |
| Creative Technology                    | 1         | 0.83%   |
| ARC International                      | 1         | 0.83%   |
| Apple                                  | 1         | 0.83%   |
| ALi                                    | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD              | 8         | 6.67%   |
| Chicony Integrated Camera                  | 6         | 5%      |
| Acer Integrated Camera                     | 6         | 5%      |
| Quanta HP TrueVision HD Camera             | 3         | 2.5%    |
| IMC Networks USB2.0 VGA UVC WebCam         | 3         | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam          | 3         | 2.5%    |
| Chicony HP TrueVision HD Camera            | 3         | 2.5%    |
| Chicony HD WebCam                          | 3         | 2.5%    |
| Syntek Integrated Camera                   | 2         | 1.67%   |
| Suyin HP TrueVision HD                     | 2         | 1.67%   |
| Suyin HD Video WebCam                      | 2         | 1.67%   |
| Quanta HP Webcam                           | 2         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_HD       | 2         | 1.67%   |
| IMC Networks Integrated Camera             | 2         | 1.67%   |
| Alcor Micro USB 2.0 WebCamera              | 2         | 1.67%   |
| Acer USB2.0 Camera                         | 2         | 1.67%   |
| Z-Star WebCam SC-03FFL11739P               | 1         | 0.83%   |
| Z-Star Venus USB2.0 Camera                 | 1         | 0.83%   |
| Unknown 720p HD Camera                     | 1         | 0.83%   |
| Suyin HP Webcam-101                        | 1         | 0.83%   |
| Suyin HD WebCam                            | 1         | 0.83%   |
| Suyin Acer/Lenovo Webcam [CN0316]          | 1         | 0.83%   |
| Suyin Acer CrystalEye Webcam               | 1         | 0.83%   |
| Suyin 1.3M HD WebCam                       | 1         | 0.83%   |
| Sunplus MTD Camera                         | 1         | 0.83%   |
| Sunplus Laptop Integrated Webcam FHD       | 1         | 0.83%   |
| Sunplus HP TrueVision HD Camera            | 1         | 0.83%   |
| Sunplus HD WebCam                          | 1         | 0.83%   |
| Sunplus EKACOM-K30                         | 1         | 0.83%   |
| Sunplus Aukey-PC-LM1E Camera               | 1         | 0.83%   |
| Sunplus 1.3M HD WebCam                     | 1         | 0.83%   |
| Realtek MTD camera                         | 1         | 0.83%   |
| Realtek Lenovo EasyCamera                  | 1         | 0.83%   |
| Realtek Integrated_Webcam_HD               | 1         | 0.83%   |
| Realtek HP Wide Vision FHD Camera          | 1         | 0.83%   |
| Realtek HP Truevision HD integrated webcam | 1         | 0.83%   |
| Realtek HP Truevision HD                   | 1         | 0.83%   |
| Realtek HP "Truevision HD" laptop camera   | 1         | 0.83%   |
| Quanta VGA WebCam                          | 1         | 0.83%   |
| Quanta Laptop_Integrated_Webcam_2HDM       | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 46.67%  |
| Synaptics                  | 2         | 13.33%  |
| STMicroelectronics         | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| Samsung Electronics        | 1         | 6.67%   |
| Focal-systems.Corp         | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 13.33%  |
| Validity Sensors Synaptics WBDI            | 2         | 13.33%  |
| Unknown                                    | 2         | 13.33%  |
| Validity Sensors VFS491                    | 1         | 6.67%   |
| Validity Sensors VFS301 Fingerprint Reader | 1         | 6.67%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader      | 1         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 6.67%   |
| Samsung Fingerprint Sensor Device - 730B   | 1         | 6.67%   |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 6.67%   |
| Elan ELAN:Fingerprint                      | 1         | 6.67%   |
| AuthenTec AES1600                          | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| Lenovo      | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 42.86%  |
| Lenovo Integrated Smart Card Reader            | 1         | 14.29%  |
| Broadcom 5880                                  | 1         | 14.29%  |
| Broadcom 58200                                 | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 127       | 67.2%   |
| 1     | 54        | 28.57%  |
| 2     | 6         | 3.17%   |
| 4     | 1         | 0.53%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 18        | 25.35%  |
| Graphics card         | 16        | 22.54%  |
| Multimedia controller | 14        | 19.72%  |
| Fingerprint reader    | 14        | 19.72%  |
| Chipcard              | 6         | 8.45%   |
| Unassigned class      | 1         | 1.41%   |
| Dvb card              | 1         | 1.41%   |
| Camera                | 1         | 1.41%   |

