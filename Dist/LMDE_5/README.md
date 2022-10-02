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

Total: 221

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Gigabyte      | B450 AORUS M                | Desktop     | [aca8d98967](https://linux-hardware.org/?probe=aca8d98967) | Jul 18, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Framework     | Laptop                      | Notebook    | [80ad33bb18](https://linux-hardware.org/?probe=80ad33bb18) | Jul 16, 2022 |
| Framework     | Laptop                      | Notebook    | [439e4aafa7](https://linux-hardware.org/?probe=439e4aafa7) | Jul 16, 2022 |
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
| Framework     | Laptop                      | Notebook    | [8a44001ebb](https://linux-hardware.org/?probe=8a44001ebb) | Jun 30, 2022 |
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


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.10.0-14-amd64      | 30        | 17.44%  |
| 5.10.0-12-amd64      | 30        | 17.44%  |
| 5.10.0-13-amd64      | 27        | 15.7%   |
| 5.10.0-17-amd64      | 20        | 11.63%  |
| 5.10.0-15-amd64      | 18        | 10.47%  |
| 5.10.0-18-amd64      | 13        | 7.56%   |
| 5.10.0-16-amd64      | 13        | 7.56%   |
| 5.10.0-13-686        | 6         | 3.49%   |
| 5.18.0-0.bpo.1-amd64 | 4         | 2.33%   |
| 5.16.0-0.bpo.4-amd64 | 3         | 1.74%   |
| 5.19.10-xanmod1      | 1         | 0.58%   |
| 5.18.0-4-amd64       | 1         | 0.58%   |
| 5.18.0-3-amd64       | 1         | 0.58%   |
| 5.16.0-0.bpo.3-amd64 | 1         | 0.58%   |
| 5.15.0-0.bpo.3-amd64 | 1         | 0.58%   |
| 5.10.0-17-686        | 1         | 0.58%   |
| 5.10.0-14-686        | 1         | 0.58%   |
| 5.10.0-11-686        | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 155       | 93.37%  |
| 5.18.0  | 6         | 3.61%   |
| 5.16.0  | 3         | 1.81%   |
| 5.19.10 | 1         | 0.6%    |
| 5.15.0  | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 155       | 93.37%  |
| 5.18    | 6         | 3.61%   |
| 5.16    | 3         | 1.81%   |
| 5.19    | 1         | 0.6%    |
| 5.15    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 155       | 94.51%  |
| i686   | 9         | 5.49%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 150       | 91.46%  |
| Cinnamon   | 10        | 6.1%    |
| MATE       | 2         | 1.22%   |
| XFCE       | 1         | 0.61%   |
| Unknown    | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 164       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 102       | 62.2%   |
| LightDM | 62        | 37.8%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 62        | 37.58%  |
| de_DE | 17        | 10.3%   |
| ru_RU | 14        | 8.48%   |
| pt_BR | 11        | 6.67%   |
| en_GB | 10        | 6.06%   |
| fr_FR | 9         | 5.45%   |
| es_ES | 7         | 4.24%   |
| pl_PL | 4         | 2.42%   |
| it_IT | 4         | 2.42%   |
| es_MX | 3         | 1.82%   |
| fr_CA | 2         | 1.21%   |
| es_BO | 2         | 1.21%   |
| en_IE | 2         | 1.21%   |
| en_CA | 2         | 1.21%   |
| sv_SE | 1         | 0.61%   |
| pt_PT | 1         | 0.61%   |
| nn_NO | 1         | 0.61%   |
| nl_AW | 1         | 0.61%   |
| ko_KR | 1         | 0.61%   |
| it_CH | 1         | 0.61%   |
| hu_HU | 1         | 0.61%   |
| fr_BE | 1         | 0.61%   |
| es_PE | 1         | 0.61%   |
| es_NI | 1         | 0.61%   |
| es_EC | 1         | 0.61%   |
| es_CR | 1         | 0.61%   |
| en_NZ | 1         | 0.61%   |
| en_AU | 1         | 0.61%   |
| da_DK | 1         | 0.61%   |
| ar_EG | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 102       | 62.2%   |
| BIOS | 62        | 37.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 151       | 92.07%  |
| Overlay | 6         | 3.66%   |
| Tmpfs   | 4         | 2.44%   |
| Btrfs   | 2         | 1.22%   |
| Xfs     | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 102       | 62.2%   |
| GPT     | 50        | 30.49%  |
| MBR     | 12        | 7.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 92.73%  |
| Yes       | 12        | 7.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 146       | 89.02%  |
| Yes       | 18        | 10.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 30        | 18.29%  |
| Dell                | 26        | 15.85%  |
| Lenovo              | 23        | 14.02%  |
| ASUSTek Computer    | 20        | 12.2%   |
| Acer                | 15        | 9.15%   |
| MSI                 | 10        | 6.1%    |
| Gigabyte Technology | 5         | 3.05%   |
| Apple               | 5         | 3.05%   |
| Toshiba             | 2         | 1.22%   |
| Sony                | 2         | 1.22%   |
| Medion              | 2         | 1.22%   |
| ASRock              | 2         | 1.22%   |
| Unknown             | 2         | 1.22%   |
| Wortmann AG         | 1         | 0.61%   |
| Samsung Electronics | 1         | 0.61%   |
| Philco              | 1         | 0.61%   |
| Pegatron            | 1         | 0.61%   |
| Panasonic           | 1         | 0.61%   |
| Packard Bell        | 1         | 0.61%   |
| Multilaser          | 1         | 0.61%   |
| Microtech           | 1         | 0.61%   |
| LincPlus            | 1         | 0.61%   |
| Intel               | 1         | 0.61%   |
| Howard Computers    | 1         | 0.61%   |
| Google              | 1         | 0.61%   |
| Gateway             | 1         | 0.61%   |
| Framework           | 1         | 0.61%   |
| eMachines           | 1         | 0.61%   |
| Dynabook            | 1         | 0.61%   |
| Dixonsxp            | 1         | 0.61%   |
| Digiboard           | 1         | 0.61%   |
| AMI                 | 1         | 0.61%   |
| Alienware           | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 3         | 1.83%   |
| HP Laptop 15z-ef2xxx                  | 2         | 1.22%   |
| Dell Latitude E6400                   | 2         | 1.22%   |
| Dell Latitude E5540                   | 2         | 1.22%   |
| Acer Aspire 5930                      | 2         | 1.22%   |
| Wortmann AG TERRA_MOBILE_1713A        | 1         | 0.61%   |
| Toshiba Satellite M55                 | 1         | 0.61%   |
| Toshiba Satellite L455                | 1         | 0.61%   |
| Sony SVE1713Y1RB                      | 1         | 0.61%   |
| Sony SVE1512G1RW                      | 1         | 0.61%   |
| Samsung 730QDA                        | 1         | 0.61%   |
| Philco 10D                            | 1         | 0.61%   |
| Pegatron Pro 3015 Microtower PC       | 1         | 0.61%   |
| Panasonic CF-H2BJJHZDE                | 1         | 0.61%   |
| Packard Bell DOT S                    | 1         | 0.61%   |
| Multilaser PC150                      | 1         | 0.61%   |
| MSI U180                              | 1         | 0.61%   |
| MSI MS-7B79                           | 1         | 0.61%   |
| MSI MS-7B23                           | 1         | 0.61%   |
| MSI MS-7B17                           | 1         | 0.61%   |
| MSI MS-7A40                           | 1         | 0.61%   |
| MSI MS-7984                           | 1         | 0.61%   |
| MSI MS-7977                           | 1         | 0.61%   |
| MSI MS-7974                           | 1         | 0.61%   |
| MSI MS-7851                           | 1         | 0.61%   |
| MSI GL73 8SE                          | 1         | 0.61%   |
| Microtech ebookPro                    | 1         | 0.61%   |
| Medion P15648                         | 1         | 0.61%   |
| Medion E6220                          | 1         | 0.61%   |
| LincPlus LINNCPLUS P1                 | 1         | 0.61%   |
| Lenovo Z50-70 20354                   | 1         | 0.61%   |
| Lenovo Yoga 7 15ITL5 82BJ             | 1         | 0.61%   |
| Lenovo Yoga 2 11 20332                | 1         | 0.61%   |
| Lenovo V55t-15ARE 11KJ0036TX          | 1         | 0.61%   |
| Lenovo ThinkPad X270 W10DG 20K5S3HG00 | 1         | 0.61%   |
| Lenovo ThinkPad T61 7661A16           | 1         | 0.61%   |
| Lenovo ThinkPad T480 20L6S1RN00       | 1         | 0.61%   |
| Lenovo ThinkPad T470s 20HF0047UK      | 1         | 0.61%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS | 1         | 0.61%   |
| Lenovo ThinkPad T450 20BUS0QT04       | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Acer Aspire            | 12        | 7.32%   |
| Lenovo ThinkPad        | 8         | 4.88%   |
| HP Laptop              | 8         | 4.88%   |
| Dell Latitude          | 8         | 4.88%   |
| Dell Inspiron          | 7         | 4.27%   |
| Lenovo IdeaPad         | 5         | 3.05%   |
| HP Pavilion            | 4         | 2.44%   |
| Dell Precision         | 4         | 2.44%   |
| ASUS PRIME             | 4         | 2.44%   |
| HP EliteBook           | 3         | 1.83%   |
| HP Compaq              | 3         | 1.83%   |
| ASUS VivoBook          | 3         | 1.83%   |
| ASUS ROG               | 3         | 1.83%   |
| Unknown                | 3         | 1.83%   |
| Toshiba Satellite      | 2         | 1.22%   |
| Lenovo Yoga            | 2         | 1.22%   |
| Lenovo ThinkCentre     | 2         | 1.22%   |
| HP ProBook             | 2         | 1.22%   |
| HP 255                 | 2         | 1.22%   |
| Dell XPS               | 2         | 1.22%   |
| Dell Vostro            | 2         | 1.22%   |
| Dell OptiPlex          | 2         | 1.22%   |
| Wortmann AG TERRA      | 1         | 0.61%   |
| Sony SVE1713Y1RB       | 1         | 0.61%   |
| Sony SVE1512G1RW       | 1         | 0.61%   |
| Samsung 730QDA         | 1         | 0.61%   |
| Philco 10D             | 1         | 0.61%   |
| Pegatron Pro           | 1         | 0.61%   |
| Panasonic CF-H2BJJHZDE | 1         | 0.61%   |
| Packard Bell DOT       | 1         | 0.61%   |
| Multilaser PC150       | 1         | 0.61%   |
| MSI U180               | 1         | 0.61%   |
| MSI MS-7B79            | 1         | 0.61%   |
| MSI MS-7B23            | 1         | 0.61%   |
| MSI MS-7B17            | 1         | 0.61%   |
| MSI MS-7A40            | 1         | 0.61%   |
| MSI MS-7984            | 1         | 0.61%   |
| MSI MS-7977            | 1         | 0.61%   |
| MSI MS-7974            | 1         | 0.61%   |
| MSI MS-7851            | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 22        | 13.41%  |
| 2012 | 18        | 10.98%  |
| 2020 | 14        | 8.54%   |
| 2018 | 13        | 7.93%   |
| 2013 | 13        | 7.93%   |
| 2019 | 11        | 6.71%   |
| 2017 | 11        | 6.71%   |
| 2010 | 10        | 6.1%    |
| 2016 | 8         | 4.88%   |
| 2015 | 8         | 4.88%   |
| 2009 | 7         | 4.27%   |
| 2014 | 6         | 3.66%   |
| 2008 | 6         | 3.66%   |
| 2007 | 6         | 3.66%   |
| 2022 | 5         | 3.05%   |
| 2011 | 3         | 1.83%   |
| 2006 | 3         | 1.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 107       | 65.24%  |
| Desktop     | 48        | 29.27%  |
| Convertible | 4         | 2.44%   |
| Tablet      | 2         | 1.22%   |
| All in one  | 2         | 1.22%   |
| Mini pc     | 1         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 147       | 88.55%  |
| Enabled  | 19        | 11.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 163       | 99.39%  |
| Yes  | 1         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 44        | 26.67%  |
| 3.01-4.0    | 34        | 20.61%  |
| 16.01-24.0  | 29        | 17.58%  |
| 8.01-16.0   | 27        | 16.36%  |
| 32.01-64.0  | 10        | 6.06%   |
| 1.01-2.0    | 10        | 6.06%   |
| 2.01-3.0    | 5         | 3.03%   |
| 24.01-32.0  | 3         | 1.82%   |
| 64.01-256.0 | 3         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 66        | 39.05%  |
| 2.01-3.0   | 60        | 35.5%   |
| 3.01-4.0   | 17        | 10.06%  |
| 4.01-8.0   | 14        | 8.28%   |
| 0.51-1.0   | 9         | 5.33%   |
| 8.01-16.0  | 2         | 1.18%   |
| 32.01-64.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 111       | 67.27%  |
| 2      | 30        | 18.18%  |
| 3      | 15        | 9.09%   |
| 4      | 6         | 3.64%   |
| 5      | 2         | 1.21%   |
| 6      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 64.02%  |
| Yes       | 59        | 35.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 81.71%  |
| No        | 30        | 18.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 81.71%  |
| No        | 30        | 18.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 59.15%  |
| No        | 67        | 40.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 32        | 19.28%  |
| Germany     | 17        | 10.24%  |
| Russia      | 15        | 9.04%   |
| Brazil      | 13        | 7.83%   |
| UK          | 11        | 6.63%   |
| France      | 10        | 6.02%   |
| Italy       | 8         | 4.82%   |
| Spain       | 7         | 4.22%   |
| Canada      | 7         | 4.22%   |
| Poland      | 6         | 3.61%   |
| Mexico      | 4         | 2.41%   |
| Vietnam     | 2         | 1.2%    |
| Sweden      | 2         | 1.2%    |
| Romania     | 2         | 1.2%    |
| Hungary     | 2         | 1.2%    |
| Chile       | 2         | 1.2%    |
| Bolivia     | 2         | 1.2%    |
| Belgium     | 2         | 1.2%    |
| Australia   | 2         | 1.2%    |
| Venezuela   | 1         | 0.6%    |
| Turkey      | 1         | 0.6%    |
| South Korea | 1         | 0.6%    |
| Portugal    | 1         | 0.6%    |
| Peru        | 1         | 0.6%    |
| Paraguay    | 1         | 0.6%    |
| Norway      | 1         | 0.6%    |
| Nicaragua   | 1         | 0.6%    |
| New Zealand | 1         | 0.6%    |
| Malaysia    | 1         | 0.6%    |
| Lithuania   | 1         | 0.6%    |
| Latvia      | 1         | 0.6%    |
| Kenya       | 1         | 0.6%    |
| Ireland     | 1         | 0.6%    |
| Finland     | 1         | 0.6%    |
| Ecuador     | 1         | 0.6%    |
| Denmark     | 1         | 0.6%    |
| Costa Rica  | 1         | 0.6%    |
| Belarus     | 1         | 0.6%    |
| Austria     | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 4         | 2.41%   |
| Rome                  | 2         | 1.2%    |
| Oruro                 | 2         | 1.2%    |
| Neasden               | 2         | 1.2%    |
| Montreal              | 2         | 1.2%    |
| Melbourne             | 2         | 1.2%    |
| Krakow                | 2         | 1.2%    |
| Berlin                | 2         | 1.2%    |
| Belém                | 2         | 1.2%    |
| Zaragoza              | 1         | 0.6%    |
| Wroclaw               | 1         | 0.6%    |
| Voronezh              | 1         | 0.6%    |
| Volta Redonda         | 1         | 0.6%    |
| Vitória da Conquista | 1         | 0.6%    |
| Vincennes             | 1         | 0.6%    |
| Vilshofen             | 1         | 0.6%    |
| Vilnius               | 1         | 0.6%    |
| Viet Tri              | 1         | 0.6%    |
| Vicente Guerrero      | 1         | 0.6%    |
| Veurne                | 1         | 0.6%    |
| Vaslui                | 1         | 0.6%    |
| Vancouver             | 1         | 0.6%    |
| Valsoyfjord           | 1         | 0.6%    |
| Uiwang                | 1         | 0.6%    |
| Turku                 | 1         | 0.6%    |
| Tula                  | 1         | 0.6%    |
| Troisdorf             | 1         | 0.6%    |
| Trieste               | 1         | 0.6%    |
| Toulouse              | 1         | 0.6%    |
| Toronto               | 1         | 0.6%    |
| Tolyatti              | 1         | 0.6%    |
| Toledo                | 1         | 0.6%    |
| Toccoa                | 1         | 0.6%    |
| Tipton                | 1         | 0.6%    |
| Tacoma                | 1         | 0.6%    |
| Stockbridge           | 1         | 0.6%    |
| St Petersburg         | 1         | 0.6%    |
| Spruce Grove          | 1         | 0.6%    |
| Spearfish             | 1         | 0.6%    |
| Sollentuna            | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 33        | 44     | 14.8%   |
| Seagate                        | 31        | 36     | 13.9%   |
| Samsung Electronics            | 29        | 38     | 13%     |
| SanDisk                        | 15        | 15     | 6.73%   |
| Unknown                        | 11        | 15     | 4.93%   |
| Toshiba                        | 11        | 12     | 4.93%   |
| Kingston                       | 11        | 11     | 4.93%   |
| Hitachi                        | 10        | 11     | 4.48%   |
| Intel                          | 7         | 7      | 3.14%   |
| Crucial                        | 7         | 7      | 3.14%   |
| PNY                            | 4         | 4      | 1.79%   |
| Micron Technology              | 4         | 4      | 1.79%   |
| Apple                          | 4         | 9      | 1.79%   |
| A-DATA Technology              | 4         | 5      | 1.79%   |
| Patriot                        | 3         | 3      | 1.35%   |
| Team                           | 2         | 2      | 0.9%    |
| SK hynix                       | 2         | 2      | 0.9%    |
| Phison                         | 2         | 2      | 0.9%    |
| KingSpec                       | 2         | 2      | 0.9%    |
| HGST                           | 2         | 2      | 0.9%    |
| China                          | 2         | 3      | 0.9%    |
| XrayDisk                       | 1         | 2      | 0.45%   |
| UMIS                           | 1         | 1      | 0.45%   |
| Transcend                      | 1         | 2      | 0.45%   |
| SSD PHIS                       | 1         | 1      | 0.45%   |
| SPCC                           | 1         | 1      | 0.45%   |
| Solid State Storage Technology | 1         | 1      | 0.45%   |
| ShiJi                          | 1         | 1      | 0.45%   |
| SABRENT                        | 1         | 1      | 0.45%   |
| Oyen                           | 1         | 1      | 0.45%   |
| ORICO                          | 1         | 1      | 0.45%   |
| OCZ-VERTEX                     | 1         | 1      | 0.45%   |
| Netac                          | 1         | 1      | 0.45%   |
| Microtech                      | 1         | 2      | 0.45%   |
| Micron/Crucial Technology      | 1         | 2      | 0.45%   |
| LITEON                         | 1         | 1      | 0.45%   |
| KIOXIA                         | 1         | 4      | 0.45%   |
| Initio                         | 1         | 1      | 0.45%   |
| HXY                            | 1         | 1      | 0.45%   |
| Hewlett-Packard                | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.65%   |
| Samsung SSD 850 EVO 250GB            | 4         | 1.65%   |
| Unknown SD/MMC/MS PRO 2GB            | 3         | 1.24%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.24%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 1.24%   |
| Samsung SSD 850 EVO 500GB            | 3         | 1.24%   |
| Micron NVMe SSD Drive 512GB          | 3         | 1.24%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.24%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.24%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 1.24%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.83%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.83%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.83%   |
| Unknown SC128  128GB                 | 2         | 0.83%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB       | 2         | 0.83%   |
| Seagate ST1000DM003-1CH162 1TB       | 2         | 0.83%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.83%   |
| Samsung SSD 980 PRO 1TB              | 2         | 0.83%   |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 0.83%   |
| Samsung PM991a NVMe 512GB            | 2         | 0.83%   |
| Samsung NVMe SSD Drive 500GB         | 2         | 0.83%   |
| Samsung NVMe SSD Drive 250GB         | 2         | 0.83%   |
| Patriot Burst 240GB SSD              | 2         | 0.83%   |
| Apple SSD SD0128F 121GB              | 2         | 0.83%   |
| A-DATA SU650 120GB SSD               | 2         | 0.83%   |
| XrayDisk 480GB                       | 1         | 0.41%   |
| XrayDisk 1TB                         | 1         | 0.41%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.41%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.41%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.41%   |
| WDC WD60EZAZ-00ZGHB0 6TB             | 1         | 0.41%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.41%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.41%   |
| WDC WD5000AZLX-08K2TA0 500GB         | 1         | 0.41%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 1         | 0.41%   |
| WDC WD5000AAKX-22ERMA0 500GB         | 1         | 0.41%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1         | 0.41%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 36     | 36.47%  |
| WDC                 | 26        | 36     | 30.59%  |
| Hitachi             | 10        | 11     | 11.76%  |
| Toshiba             | 9         | 10     | 10.59%  |
| Unknown             | 3         | 3      | 3.53%   |
| Samsung Electronics | 2         | 2      | 2.35%   |
| HGST                | 2         | 2      | 2.35%   |
| Fujitsu             | 1         | 1      | 1.18%   |
| ASMedia             | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 16%     |
| Kingston            | 9         | 9      | 12%     |
| Crucial             | 7         | 7      | 9.33%   |
| SanDisk             | 6         | 6      | 8%      |
| PNY                 | 4         | 4      | 5.33%   |
| A-DATA Technology   | 4         | 5      | 5.33%   |
| Patriot             | 3         | 3      | 4%      |
| Intel               | 3         | 3      | 4%      |
| Apple               | 3         | 3      | 4%      |
| Team                | 2         | 2      | 2.67%   |
| KingSpec            | 2         | 2      | 2.67%   |
| China               | 2         | 3      | 2.67%   |
| WDC                 | 1         | 1      | 1.33%   |
| Transcend           | 1         | 2      | 1.33%   |
| Toshiba             | 1         | 1      | 1.33%   |
| SSD PHIS            | 1         | 1      | 1.33%   |
| SK hynix            | 1         | 1      | 1.33%   |
| ORICO               | 1         | 1      | 1.33%   |
| OCZ-VERTEX          | 1         | 1      | 1.33%   |
| Netac               | 1         | 1      | 1.33%   |
| Microtech           | 1         | 2      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |
| HXY                 | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |
| GOODRAM             | 1         | 1      | 1.33%   |
| FORESEE             | 1         | 1      | 1.33%   |
| BHT                 | 1         | 2      | 1.33%   |
| Acer                | 1         | 1      | 1.33%   |
| 2.5''               | 1         | 1      | 1.33%   |
| Unknown             | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 78        | 102    | 37.5%   |
| SSD     | 69        | 84     | 33.17%  |
| NVMe    | 47        | 64     | 22.6%   |
| MMC     | 8         | 11     | 3.85%   |
| Unknown | 6         | 8      | 2.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 125       | 180    | 66.49%  |
| NVMe | 46        | 63     | 24.47%  |
| SAS  | 9         | 15     | 4.79%   |
| MMC  | 8         | 11     | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 124    | 66.44%  |
| 0.51-1.0   | 35        | 44     | 23.97%  |
| 1.01-2.0   | 7         | 8      | 4.79%   |
| 2.01-3.0   | 3         | 6      | 2.05%   |
| 3.01-4.0   | 2         | 2      | 1.37%   |
| 4.01-10.0  | 2         | 2      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 30.12%  |
| 251-500        | 40        | 24.1%   |
| 501-1000       | 20        | 12.05%  |
| 1001-2000      | 18        | 10.84%  |
| 51-100         | 12        | 7.23%   |
| 1-20           | 9         | 5.42%   |
| 21-50          | 8         | 4.82%   |
| More than 3000 | 5         | 3.01%   |
| 2001-3000      | 4         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 81        | 47.65%  |
| 21-50          | 30        | 17.65%  |
| 51-100         | 18        | 10.59%  |
| 101-250        | 13        | 7.65%   |
| 251-500        | 12        | 7.06%   |
| 501-1000       | 9         | 5.29%   |
| 1001-2000      | 4         | 2.35%   |
| 2001-3000      | 2         | 1.18%   |
| More than 3000 | 1         | 0.59%   |

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
| Detected | 111       | 178    | 62.71%  |
| Works    | 58        | 82     | 32.77%  |
| Malfunc  | 8         | 9      | 4.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 116       | 57.14%  |
| AMD                            | 28        | 13.79%  |
| Samsung Electronics            | 18        | 8.87%   |
| SanDisk                        | 12        | 5.91%   |
| Micron Technology              | 4         | 1.97%   |
| Phison Electronics             | 3         | 1.48%   |
| Marvell Technology Group       | 3         | 1.48%   |
| Nvidia                         | 2         | 0.99%   |
| KIOXIA                         | 2         | 0.99%   |
| Kingston Technology Company    | 2         | 0.99%   |
| JMicron Technology             | 2         | 0.99%   |
| Broadcom / LSI                 | 2         | 0.99%   |
| ASMedia Technology             | 2         | 0.99%   |
| Union Memory (Shenzhen)        | 1         | 0.49%   |
| Toshiba America Info Systems   | 1         | 0.49%   |
| Solid State Storage Technology | 1         | 0.49%   |
| SK hynix                       | 1         | 0.49%   |
| Micron/Crucial Technology      | 1         | 0.49%   |
| LSI Logic / Symbios Logic      | 1         | 0.49%   |
| Apple                          | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23        | 9.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 9         | 3.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 3.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 3.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 3.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 3.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 6         | 2.59%   |
| Samsung NVMe SSD Controller 980                                                         | 6         | 2.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 2.59%   |
| SanDisk Non-Volatile memory controller                                                  | 5         | 2.16%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 2.16%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 4         | 1.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.72%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.29%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.86%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 2         | 0.86%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 2         | 0.86%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.86%   |
| Intel SSD 660P Series                                                                   | 2         | 0.86%   |
| Intel SSD 600P Series                                                                   | 2         | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.86%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 2         | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 2         | 0.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 2         | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.86%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 117       | 55.98%  |
| NVMe | 47        | 22.49%  |
| IDE  | 23        | 11%     |
| RAID | 20        | 9.57%   |
| SAS  | 1         | 0.48%   |
| SCSI | 1         | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 127       | 77.44%  |
| AMD    | 37        | 22.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 3.05%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 2.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 2.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 1.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 1.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.83%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2         | 1.22%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.22%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 1.22%   |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 1.22%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 1.22%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.22%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.22%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.22%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.22%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.22%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.61%   |
| Intel Xeon CPU X5570 @ 2.93GHz              | 1         | 0.61%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz         | 1         | 0.61%   |
| Intel Xeon CPU 3.40GHz                      | 1         | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.61%   |
| Intel Pentium M processor 1.73GHz           | 1         | 0.61%   |
| Intel Pentium Gold G7400                    | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.61%   |
| Intel Pentium D CPU 3.40GHz                 | 1         | 0.61%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.61%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 0.61%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.61%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.61%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.61%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 19.51%  |
| Intel Core i7           | 19        | 11.59%  |
| Other                   | 15        | 9.15%   |
| Intel Core i3           | 12        | 7.32%   |
| AMD Ryzen 5             | 9         | 5.49%   |
| Intel Core 2 Duo        | 8         | 4.88%   |
| Intel Celeron           | 8         | 4.88%   |
| AMD Ryzen 7             | 8         | 4.88%   |
| Intel Pentium           | 7         | 4.27%   |
| Intel Atom              | 7         | 4.27%   |
| Intel Xeon              | 6         | 3.66%   |
| AMD Ryzen 3             | 5         | 3.05%   |
| Intel Pentium Dual-Core | 3         | 1.83%   |
| Intel Core 2            | 2         | 1.22%   |
| Intel Celeron M         | 2         | 1.22%   |
| AMD E2                  | 2         | 1.22%   |
| AMD E1                  | 2         | 1.22%   |
| AMD Athlon II X2        | 2         | 1.22%   |
| AMD Athlon              | 2         | 1.22%   |
| Intel Pentium Silver    | 1         | 0.61%   |
| Intel Pentium M         | 1         | 0.61%   |
| Intel Pentium Gold      | 1         | 0.61%   |
| Intel Pentium D         | 1         | 0.61%   |
| Intel Core i9           | 1         | 0.61%   |
| Intel Core 2 Quad       | 1         | 0.61%   |
| Intel Core 2 Extreme    | 1         | 0.61%   |
| AMD Ryzen 9             | 1         | 0.61%   |
| AMD FX                  | 1         | 0.61%   |
| AMD C-50                | 1         | 0.61%   |
| AMD A6                  | 1         | 0.61%   |
| AMD A4                  | 1         | 0.61%   |
| AMD A10                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 82        | 50%     |
| 4      | 51        | 31.1%   |
| 8      | 14        | 8.54%   |
| 6      | 10        | 6.1%    |
| 1      | 5         | 3.05%   |
| 16     | 2         | 1.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 160       | 97.56%  |
| 2      | 4         | 2.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 103       | 62.8%   |
| 1      | 61        | 37.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 160       | 97.56%  |
| 32-bit         | 4         | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 15        | 9.09%   |
| 0x806c1    | 11        | 6.67%   |
| 0x40651    | 7         | 4.24%   |
| 0x206a7    | 7         | 4.24%   |
| 0x08108109 | 7         | 4.24%   |
| 0x806ec    | 6         | 3.64%   |
| 0x1067a    | 6         | 3.64%   |
| 0x08608103 | 6         | 3.64%   |
| 0x806e9    | 5         | 3.03%   |
| 0x406e3    | 5         | 3.03%   |
| Unknown    | 5         | 3.03%   |
| 0x6fd      | 4         | 2.42%   |
| 0x506e3    | 4         | 2.42%   |
| 0x306c3    | 4         | 2.42%   |
| 0x30661    | 4         | 2.42%   |
| 0x906ed    | 3         | 1.82%   |
| 0x20652    | 3         | 1.82%   |
| 0x10676    | 3         | 1.82%   |
| 0x906ea    | 2         | 1.21%   |
| 0x90675    | 2         | 1.21%   |
| 0x806ea    | 2         | 1.21%   |
| 0x706e5    | 2         | 1.21%   |
| 0x706a1    | 2         | 1.21%   |
| 0x6f6      | 2         | 1.21%   |
| 0x406c4    | 2         | 1.21%   |
| 0x206d7    | 2         | 1.21%   |
| 0x0a50000c | 2         | 1.21%   |
| 0x08101016 | 2         | 1.21%   |
| 0x06006705 | 2         | 1.21%   |
| 0xf65      | 1         | 0.61%   |
| 0xf43      | 1         | 0.61%   |
| 0xa0671    | 1         | 0.61%   |
| 0xa0653    | 1         | 0.61%   |
| 0xa0652    | 1         | 0.61%   |
| 0x906c0    | 1         | 0.61%   |
| 0x806eb    | 1         | 0.61%   |
| 0x806d1    | 1         | 0.61%   |
| 0x706a8    | 1         | 0.61%   |
| 0x6f2      | 1         | 0.61%   |
| 0x6ec      | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 11.52%  |
| IvyBridge     | 16        | 9.7%    |
| TigerLake     | 11        | 6.67%   |
| Haswell       | 11        | 6.67%   |
| Unknown       | 11        | 6.67%   |
| Skylake       | 9         | 5.45%   |
| SandyBridge   | 9         | 5.45%   |
| Penryn        | 9         | 5.45%   |
| Zen+          | 8         | 4.85%   |
| Core          | 7         | 4.24%   |
| Bonnell       | 6         | 3.64%   |
| Westmere      | 5         | 3.03%   |
| Zen 3         | 4         | 2.42%   |
| Zen           | 4         | 2.42%   |
| Silvermont    | 4         | 2.42%   |
| Excavator     | 4         | 2.42%   |
| IceLake       | 3         | 1.82%   |
| Goldmont plus | 3         | 1.82%   |
| Zen 2         | 2         | 1.21%   |
| Puma          | 2         | 1.21%   |
| P6            | 2         | 1.21%   |
| NetBurst      | 2         | 1.21%   |
| Nehalem       | 2         | 1.21%   |
| K10           | 2         | 1.21%   |
| Jaguar        | 2         | 1.21%   |
| CometLake     | 2         | 1.21%   |
| Broadwell     | 2         | 1.21%   |
| Tremont       | 1         | 0.61%   |
| Piledriver    | 1         | 0.61%   |
| Goldmont      | 1         | 0.61%   |
| Bobcat        | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 95        | 50.8%   |
| Nvidia | 52        | 27.81%  |
| AMD    | 40        | 21.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 4.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 4.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 3.13%   |
| AMD Lucienne                                                                             | 6         | 3.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.6%    |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 2.08%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 2.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.08%   |
| Intel HD Graphics 620                                                                    | 4         | 2.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.08%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 2.08%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.56%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 1.04%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 1.04%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 1.04%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.04%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 1.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.04%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.04%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.04%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.04%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.04%   |
| AMD Cezanne                                                                              | 2         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.52%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 46.67%  |
| 1 x Nvidia     | 34        | 20.61%  |
| 1 x AMD        | 30        | 18.18%  |
| Intel + Nvidia | 14        | 8.48%   |
| AMD + Nvidia   | 5         | 3.03%   |
| Intel + AMD    | 3         | 1.82%   |
| 2 x AMD        | 2         | 1.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 140       | 84.85%  |
| Proprietary | 15        | 9.09%   |
| Unknown     | 10        | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 52.73%  |
| 0.01-0.5   | 30        | 18.18%  |
| 1.01-2.0   | 23        | 13.94%  |
| 3.01-4.0   | 13        | 7.88%   |
| 0.51-1.0   | 9         | 5.45%   |
| 5.01-6.0   | 3         | 1.82%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 17.2%   |
| BOE                     | 20        | 12.74%  |
| Chimei Innolux          | 16        | 10.19%  |
| LG Display              | 15        | 9.55%   |
| Samsung Electronics     | 13        | 8.28%   |
| Goldstar                | 6         | 3.82%   |
| BenQ                    | 6         | 3.82%   |
| Dell                    | 5         | 3.18%   |
| Apple                   | 5         | 3.18%   |
| LG Philips              | 4         | 2.55%   |
| InfoVision              | 4         | 2.55%   |
| Philips                 | 3         | 1.91%   |
| Ancor Communications    | 3         | 1.91%   |
| Acer                    | 3         | 1.91%   |
| Unknown                 | 2         | 1.27%   |
| Sharp                   | 2         | 1.27%   |
| PANDA                   | 2         | 1.27%   |
| Lenovo                  | 2         | 1.27%   |
| Hewlett-Packard         | 2         | 1.27%   |
| HannStar                | 2         | 1.27%   |
| Chi Mei Optoelectronics | 2         | 1.27%   |
| AOC                     | 2         | 1.27%   |
| ___                     | 1         | 0.64%   |
| TR_                     | 1         | 0.64%   |
| Quanta Display          | 1         | 0.64%   |
| PLN                     | 1         | 0.64%   |
| Planar                  | 1         | 0.64%   |
| MStar                   | 1         | 0.64%   |
| Medion                  | 1         | 0.64%   |
| Insignia                | 1         | 0.64%   |
| Iiyama                  | 1         | 0.64%   |
| DENON                   | 1         | 0.64%   |
| ASUSTek Computer        | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.86%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 1.24%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 1.24%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.24%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 2         | 1.24%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 1         | 0.62%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                    | 1         | 0.62%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                  | 1         | 0.62%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.62%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 290x180mm 13.4-inch               | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 380x300mm 19.1-inch  | 1         | 0.62%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch    | 1         | 0.62%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SMBX2331 1920x1080                    | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM065D 1920x1080                     | 1         | 0.62%   |
| Samsung Electronics LCD Monitor S27R65 3840x1080                      | 1         | 0.62%   |
| Samsung Electronics LCD Monitor S27R65                                | 1         | 0.62%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 1         | 0.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 0.62%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch       | 1         | 0.62%   |
| PLN LCD Monitor PXL2790MW 1920x1080                                   | 1         | 0.62%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                 | 1         | 0.62%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.62%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.62%   |
| Philips LCD Monitor PHL 242V8 1920x1080                               | 1         | 0.62%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.62%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| MStar OptiPlex 9010 MST1111 1920x1080 510x286mm 23.0-inch             | 1         | 0.62%   |
| Medion MD20328 MED3942 1600x900 462x272mm 21.1-inch                   | 1         | 0.62%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch           | 1         | 0.62%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch          | 1         | 0.62%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 47.33%  |
| 1366x768 (WXGA)    | 31        | 20.67%  |
| 1600x900 (HD+)     | 9         | 6%      |
| 1920x1200 (WUXGA)  | 6         | 4%      |
| 1440x900 (WXGA+)   | 6         | 4%      |
| 1680x1050 (WSXGA+) | 4         | 2.67%   |
| 1280x800 (WXGA)    | 4         | 2.67%   |
| 1024x600           | 4         | 2.67%   |
| 2560x1440 (QHD)    | 3         | 2%      |
| 3840x2160 (4K)     | 2         | 1.33%   |
| 2560x1080          | 2         | 1.33%   |
| 3840x1080          | 1         | 0.67%   |
| 2880x1800          | 1         | 0.67%   |
| 2560x1600          | 1         | 0.67%   |
| 2256x1504          | 1         | 0.67%   |
| 1280x768           | 1         | 0.67%   |
| 1280x720 (HD)      | 1         | 0.67%   |
| 1280x1024 (SXGA)   | 1         | 0.67%   |
| Unknown            | 1         | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 30.57%  |
| 13      | 22        | 14.01%  |
| 14      | 16        | 10.19%  |
| Unknown | 12        | 7.64%   |
| 17      | 11        | 7.01%   |
| 24      | 8         | 5.1%    |
| 21      | 7         | 4.46%   |
| 27      | 6         | 3.82%   |
| 23      | 5         | 3.18%   |
| 10      | 4         | 2.55%   |
| 20      | 3         | 1.91%   |
| 72      | 2         | 1.27%   |
| 22      | 2         | 1.27%   |
| 34      | 1         | 0.64%   |
| 32      | 1         | 0.64%   |
| 31      | 1         | 0.64%   |
| 28      | 1         | 0.64%   |
| 25      | 1         | 0.64%   |
| 19      | 1         | 0.64%   |
| 18      | 1         | 0.64%   |
| 16      | 1         | 0.64%   |
| 12      | 1         | 0.64%   |
| 11      | 1         | 0.64%   |
| 8       | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 48.05%  |
| 501-600     | 18        | 11.69%  |
| 201-300     | 17        | 11.04%  |
| 351-400     | 14        | 9.09%   |
| 401-500     | 12        | 7.79%   |
| Unknown     | 12        | 7.79%   |
| 701-800     | 2         | 1.3%    |
| 601-700     | 2         | 1.3%    |
| 1501-2000   | 2         | 1.3%    |
| 101-200     | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 110       | 75.86%  |
| 16/10   | 20        | 13.79%  |
| Unknown | 11        | 7.59%   |
| 21/9    | 2         | 1.38%   |
| 5/4     | 1         | 0.69%   |
| 3/2     | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 30.77%  |
| 81-90          | 28        | 17.95%  |
| 201-250        | 18        | 11.54%  |
| Unknown        | 12        | 7.69%   |
| 71-80          | 10        | 6.41%   |
| 121-130        | 7         | 4.49%   |
| 301-350        | 6         | 3.85%   |
| 251-300        | 5         | 3.21%   |
| 41-50          | 4         | 2.56%   |
| 151-200        | 4         | 2.56%   |
| 131-140        | 4         | 2.56%   |
| 351-500        | 3         | 1.92%   |
| More than 1000 | 2         | 1.28%   |
| 61-70          | 1         | 0.64%   |
| 51-60          | 1         | 0.64%   |
| 1-40           | 1         | 0.64%   |
| 141-150        | 1         | 0.64%   |
| 91-100         | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 51        | 32.9%   |
| 101-120       | 45        | 29.03%  |
| 51-100        | 36        | 23.23%  |
| Unknown       | 12        | 7.74%   |
| 161-240       | 8         | 5.16%   |
| 1-50          | 2         | 1.29%   |
| More than 240 | 1         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 85.45%  |
| 2     | 12        | 7.27%   |
| 0     | 9         | 5.45%   |
| 3     | 3         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 86        | 35.39%  |
| Intel                         | 74        | 30.45%  |
| Qualcomm Atheros              | 33        | 13.58%  |
| Broadcom                      | 16        | 6.58%   |
| Marvell Technology Group      | 5         | 2.06%   |
| Ralink Technology             | 4         | 1.65%   |
| Broadcom Limited              | 4         | 1.65%   |
| TP-Link                       | 2         | 0.82%   |
| Samsung Electronics           | 2         | 0.82%   |
| Nvidia                        | 2         | 0.82%   |
| Xiaomi                        | 1         | 0.41%   |
| Ralink                        | 1         | 0.41%   |
| OnePlus Technology (Shenzhen) | 1         | 0.41%   |
| NetGear                       | 1         | 0.41%   |
| Microchip Technology          | 1         | 0.41%   |
| Mercucys                      | 1         | 0.41%   |
| MediaTek                      | 1         | 0.41%   |
| JMicron Technology            | 1         | 0.41%   |
| Huawei Technologies           | 1         | 0.41%   |
| Google                        | 1         | 0.41%   |
| Fibocom                       | 1         | 0.41%   |
| Edimax Technology             | 1         | 0.41%   |
| Dell                          | 1         | 0.41%   |
| Davicom Semiconductor         | 1         | 0.41%   |
| Belkin Components             | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 15.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 2.37%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.69%   |
| Intel Wireless 3165                                               | 5         | 1.69%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.69%   |
| Realtek 802.11ac NIC                                              | 4         | 1.36%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.36%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.02%   |
| Intel Wireless 7260                                               | 3         | 1.02%   |
| Intel WiFi Link 5100                                              | 3         | 1.02%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.02%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.68%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.68%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.68%   |
| Intel Wireless 8260                                               | 2         | 0.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.68%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 36.11%  |
| Realtek Semiconductor | 39        | 27.08%  |
| Qualcomm Atheros      | 23        | 15.97%  |
| Broadcom              | 13        | 9.03%   |
| Ralink Technology     | 4         | 2.78%   |
| Broadcom Limited      | 4         | 2.78%   |
| TP-Link               | 2         | 1.39%   |
| Ralink                | 1         | 0.69%   |
| NetGear               | 1         | 0.69%   |
| Mercucys              | 1         | 0.69%   |
| MediaTek              | 1         | 0.69%   |
| Fibocom               | 1         | 0.69%   |
| Edimax Technology     | 1         | 0.69%   |
| Belkin Components     | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 8.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 4.73%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 4.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.38%   |
| Intel Wireless 3165                                            | 5         | 3.38%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.38%   |
| Realtek 802.11ac NIC                                           | 4         | 2.7%    |
| Intel Wireless 8265 / 8275                                     | 4         | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 2.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.03%   |
| Intel Wireless 7260                                            | 3         | 2.03%   |
| Intel WiFi Link 5100                                           | 3         | 2.03%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 2.03%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.35%   |
| Intel Wireless 8260                                            | 2         | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.35%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.35%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.68%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.68%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 69        | 48.59%  |
| Intel                         | 40        | 28.17%  |
| Qualcomm Atheros              | 14        | 9.86%   |
| Marvell Technology Group      | 5         | 3.52%   |
| Broadcom                      | 3         | 2.11%   |
| Samsung Electronics           | 2         | 1.41%   |
| Nvidia                        | 2         | 1.41%   |
| Xiaomi                        | 1         | 0.7%    |
| OnePlus Technology (Shenzhen) | 1         | 0.7%    |
| Microchip Technology          | 1         | 0.7%    |
| JMicron Technology            | 1         | 0.7%    |
| Huawei Technologies           | 1         | 0.7%    |
| Google                        | 1         | 0.7%    |
| Davicom Semiconductor         | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 32.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 8.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 6.9%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.07%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 2.07%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 2.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.38%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.38%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.38%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.38%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.69%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.69%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.69%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.69%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.69%   |
| Microchip LAN9500/LAN9500i                                        | 1         | 0.69%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.69%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.69%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.69%   |
| Intel I210 Gigabit Fiber Network Connection                       | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.69%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 134       | 49.81%  |
| Ethernet | 133       | 49.44%  |
| Modem    | 2         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 60.12%  |
| Ethernet | 67        | 39.88%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 93        | 56.71%  |
| 1     | 67        | 40.85%  |
| 0     | 4         | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 122       | 73.94%  |
| Yes  | 43        | 26.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 43.88%  |
| Realtek Semiconductor           | 20        | 20.41%  |
| Qualcomm Atheros Communications | 5         | 5.1%    |
| Foxconn / Hon Hai               | 5         | 5.1%    |
| Lite-On Technology              | 4         | 4.08%   |
| Dell                            | 4         | 4.08%   |
| Apple                           | 4         | 4.08%   |
| Hewlett-Packard                 | 3         | 3.06%   |
| Cambridge Silicon Radio         | 3         | 3.06%   |
| Broadcom                        | 3         | 3.06%   |
| IMC Networks                    | 2         | 2.04%   |
| Foxconn International           | 2         | 2.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 15.31%  |
| Realtek Bluetooth Radio                             | 13        | 13.27%  |
| Intel AX201 Bluetooth                               | 10        | 10.2%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 9.18%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 6.12%   |
| Intel AX200 Bluetooth                               | 5         | 5.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.04%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 2.04%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 2.04%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.04%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.02%   |
| Lite-On Bluetooth Device                            | 1         | 1.02%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.02%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.02%   |
| Intel AX210 Bluetooth                               | 1         | 1.02%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.02%   |
| IMC Networks Bluetooth Device                       | 1         | 1.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.02%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.02%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.02%   |
| Foxconn / Hon Hai Acer Module                       | 1         | 1.02%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.02%   |
| Dell BT Mini-Receiver                               | 1         | 1.02%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.02%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.02%   |
| Broadcom BCM92045B3 ROM                             | 1         | 1.02%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 1.02%   |
| Apple Bluetooth Host Controller                     | 1         | 1.02%   |
| Apple Bluetooth HCI                                 | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 123       | 58.02%  |
| AMD                   | 41        | 19.34%  |
| Nvidia                | 39        | 18.4%   |
| Texas Instruments     | 2         | 0.94%   |
| C-Media Electronics   | 2         | 0.94%   |
| Yamaha                | 1         | 0.47%   |
| Realtek Semiconductor | 1         | 0.47%   |
| JMTek                 | 1         | 0.47%   |
| GN Netcom             | 1         | 0.47%   |
| Audioengine           | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 8.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 4.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 4.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 4.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 4.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 3.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 3.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 2.72%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 2.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 2.33%   |
| Nvidia High Definition Audio Controller                                    | 5         | 1.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 1.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 1.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.56%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.56%   |
| Nvidia GM204 High Definition Audio Controller                              | 3         | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.17%   |
| AMD High Definition Audio Controller                                       | 3         | 1.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.78%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 2         | 0.78%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 20        | 28.99%  |
| SK hynix                     | 16        | 23.19%  |
| Unknown                      | 7         | 10.14%  |
| Micron Technology            | 5         | 7.25%   |
| Nanya Technology             | 3         | 4.35%   |
| Kingston                     | 3         | 4.35%   |
| Crucial                      | 3         | 4.35%   |
| A-DATA Technology            | 3         | 4.35%   |
| Unknown (ABCD)               | 2         | 2.9%    |
| Corsair                      | 2         | 2.9%    |
| Smart                        | 1         | 1.45%   |
| Ramaxel Technology           | 1         | 1.45%   |
| Patriot Memory (PDP Systems) | 1         | 1.45%   |
| G.Skill                      | 1         | 1.45%   |
| Unknown                      | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 2.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 2.74%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.74%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 1.37%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.37%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.37%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.37%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 1.37%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 1.37%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.37%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.37%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.37%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.37%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2666MT/s             | 1         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.37%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.37%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.37%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 33        | 52.38%  |
| DDR3    | 20        | 31.75%  |
| SDRAM   | 3         | 4.76%   |
| LPDDR4  | 3         | 4.76%   |
| DDR2    | 2         | 3.17%   |
| DDR     | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 76.56%  |
| DIMM         | 12        | 18.75%  |
| Row Of Chips | 3         | 4.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 38.24%  |
| 4096  | 18        | 26.47%  |
| 2048  | 11        | 16.18%  |
| 16384 | 7         | 10.29%  |
| 32768 | 3         | 4.41%   |
| 1024  | 2         | 2.94%   |
| 512   | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 18        | 27.27%  |
| 1600    | 17        | 25.76%  |
| 2667    | 8         | 12.12%  |
| 2400    | 6         | 9.09%   |
| 667     | 3         | 4.55%   |
| 1334    | 2         | 3.03%   |
| 1333    | 2         | 3.03%   |
| 4267    | 1         | 1.52%   |
| 4199    | 1         | 1.52%   |
| 3600    | 1         | 1.52%   |
| 3400    | 1         | 1.52%   |
| 2666    | 1         | 1.52%   |
| 2267    | 1         | 1.52%   |
| 2048    | 1         | 1.52%   |
| 1866    | 1         | 1.52%   |
| 1200    | 1         | 1.52%   |
| Unknown | 1         | 1.52%   |

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
| Chicony Electronics                    | 19        | 17.92%  |
| Microdia                               | 14        | 13.21%  |
| Acer                                   | 10        | 9.43%   |
| Suyin                                  | 9         | 8.49%   |
| IMC Networks                           | 9         | 8.49%   |
| Realtek Semiconductor                  | 7         | 6.6%    |
| Sunplus Innovation Technology          | 6         | 5.66%   |
| Quanta                                 | 6         | 5.66%   |
| Logitech                               | 4         | 3.77%   |
| Alcor Micro                            | 4         | 3.77%   |
| Luxvisions Innotech Limited            | 2         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.89%   |
| Z-Star Microelectronics                | 1         | 0.94%   |
| Unknown                                | 1         | 0.94%   |
| Syntek                                 | 1         | 0.94%   |
| Pixart Imaging                         | 1         | 0.94%   |
| OmniVision Technologies                | 1         | 0.94%   |
| MacroSilicon                           | 1         | 0.94%   |
| Lite-On Technology                     | 1         | 0.94%   |
| Lenovo                                 | 1         | 0.94%   |
| Intel                                  | 1         | 0.94%   |
| icSpring                               | 1         | 0.94%   |
| Creative Technology                    | 1         | 0.94%   |
| ARC International                      | 1         | 0.94%   |
| Apple                                  | 1         | 0.94%   |
| ALi                                    | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                  | 9         | 8.49%   |
| Chicony Integrated Camera                      | 6         | 5.66%   |
| Acer Integrated Camera                         | 4         | 3.77%   |
| Quanta HP TrueVision HD Camera                 | 3         | 2.83%   |
| Chicony HP TrueVision HD Camera                | 3         | 2.83%   |
| Chicony HD WebCam                              | 3         | 2.83%   |
| Suyin HP TrueVision HD                         | 2         | 1.89%   |
| Suyin Acer HD Crystal Eye webcam               | 2         | 1.89%   |
| Microdia Laptop_Integrated_Webcam_HD           | 2         | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam             | 2         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 1.89%   |
| IMC Networks Integrated Camera                 | 2         | 1.89%   |
| Alcor Micro SHUNCCM2MP                         | 2         | 1.89%   |
| Acer USB2.0 Camera                             | 2         | 1.89%   |
| Z-Star Venus USB2.0 Camera                     | 1         | 0.94%   |
| Unknown 720p HD Camera                         | 1         | 0.94%   |
| Syntek Integrated Camera                       | 1         | 0.94%   |
| Suyin HP Webcam-101                            | 1         | 0.94%   |
| Suyin HD WebCam                                | 1         | 0.94%   |
| Suyin Acer/Lenovo Webcam [CN0316]              | 1         | 0.94%   |
| Suyin Acer CrystalEye Webcam                   | 1         | 0.94%   |
| Suyin 1.3M HD WebCam                           | 1         | 0.94%   |
| Sunplus MTD Camera                             | 1         | 0.94%   |
| Sunplus Laptop Integrated Webcam FHD           | 1         | 0.94%   |
| Sunplus HP TrueVision HD Camera                | 1         | 0.94%   |
| Sunplus HD WebCam                              | 1         | 0.94%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1         | 0.94%   |
| Sunplus 1.3M HD WebCam                         | 1         | 0.94%   |
| Realtek USB2.0 camera                          | 1         | 0.94%   |
| Realtek Lenovo EasyCamera                      | 1         | 0.94%   |
| Realtek Integrated_Webcam_HD                   | 1         | 0.94%   |
| Realtek HP Wide Vision FHD Camera              | 1         | 0.94%   |
| Realtek HP Truevision HD integrated webcam     | 1         | 0.94%   |
| Realtek HP Truevision HD                       | 1         | 0.94%   |
| Realtek HP "Truevision HD" laptop camera       | 1         | 0.94%   |
| Quanta VGA WebCam                              | 1         | 0.94%   |
| Quanta HP Webcam                               | 1         | 0.94%   |
| Quanta HP HD Camera                            | 1         | 0.94%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro           | 1         | 0.94%   |
| OmniVision Integrated Webcam for Dell XPS 2010 | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 42.86%  |
| Synaptics                  | 2         | 14.29%  |
| STMicroelectronics         | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| Samsung Electronics        | 1         | 7.14%   |
| Focal-systems.Corp         | 1         | 7.14%   |
| Elan Microelectronics      | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader | 2         | 14.29%  |
| Validity Sensors Synaptics WBDI            | 2         | 14.29%  |
| Unknown                                    | 2         | 14.29%  |
| Validity Sensors VFS491                    | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor  | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader      | 1         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device        | 1         | 7.14%   |
| Samsung Fingerprint Sensor Device - 730B   | 1         | 7.14%   |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 7.14%   |
| Elan ELAN:Fingerprint                      | 1         | 7.14%   |
| AuthenTec AES1600                          | 1         | 7.14%   |

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
| 0     | 109       | 65.27%  |
| 1     | 51        | 30.54%  |
| 2     | 6         | 3.59%   |
| 4     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 17        | 25.76%  |
| Graphics card         | 15        | 22.73%  |
| Fingerprint reader    | 13        | 19.7%   |
| Multimedia controller | 12        | 18.18%  |
| Chipcard              | 6         | 9.09%   |
| Unassigned class      | 1         | 1.52%   |
| Dvb card              | 1         | 1.52%   |
| Camera                | 1         | 1.52%   |

