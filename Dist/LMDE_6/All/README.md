LMDE 6 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_6/Desktop/README.md) and [notebooks](/Dist/LMDE_6/Notebook/README.md).

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

Total: 1292

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Precision 7540              | Notebook    | [96cf560abd](https://linux-hardware.org/?probe=96cf560abd) | Jan 03, 2026 |
| American M... | K7S41GX                     | Desktop     | [1e5ee9ad40](https://linux-hardware.org/?probe=1e5ee9ad40) | Jan 01, 2026 |
| ASUSTek       | L1N64-SLI WS                | Desktop     | [68a8fcbc78](https://linux-hardware.org/?probe=68a8fcbc78) | Dec 25, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [069cac2fda](https://linux-hardware.org/?probe=069cac2fda) | Dec 23, 2025 |
| Dell          | Precision 7540              | Notebook    | [08e0c78abb](https://linux-hardware.org/?probe=08e0c78abb) | Dec 22, 2025 |
| ASUSTek       | H110M-K                     | Desktop     | [c2430d1ead](https://linux-hardware.org/?probe=c2430d1ead) | Dec 06, 2025 |
| ASUSTek       | H110M-K                     | Desktop     | [0c3f148abd](https://linux-hardware.org/?probe=0c3f148abd) | Dec 05, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [b2bec9189d](https://linux-hardware.org/?probe=b2bec9189d) | Dec 03, 2025 |
| Gigabyte      | H310M A-CF                  | Desktop     | [9868d596d4](https://linux-hardware.org/?probe=9868d596d4) | Dec 03, 2025 |
| HP            | 8455                        | Desktop     | [77c23b390e](https://linux-hardware.org/?probe=77c23b390e) | Dec 01, 2025 |
| Lenovo        | ThinkPad L512 2550A13       | Notebook    | [0732fea7b0](https://linux-hardware.org/?probe=0732fea7b0) | Nov 26, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [1a099284d2](https://linux-hardware.org/?probe=1a099284d2) | Nov 21, 2025 |
| Apple         | MacBookPro11,4              | Notebook    | [959f7e1234](https://linux-hardware.org/?probe=959f7e1234) | Nov 21, 2025 |
| Apple         | MacBookPro11,4              | Notebook    | [a5aa6d514c](https://linux-hardware.org/?probe=a5aa6d514c) | Nov 21, 2025 |
| Dell          | Precision 7550              | Notebook    | [92fdce3c99](https://linux-hardware.org/?probe=92fdce3c99) | Nov 14, 2025 |
| Dell          | Precision 7550              | Notebook    | [c82fd028db](https://linux-hardware.org/?probe=c82fd028db) | Nov 14, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [ab65cb01ed](https://linux-hardware.org/?probe=ab65cb01ed) | Nov 08, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [77512f6e1f](https://linux-hardware.org/?probe=77512f6e1f) | Nov 07, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [682862ada2](https://linux-hardware.org/?probe=682862ada2) | Nov 07, 2025 |
| ASUSTek       | T100TAS                     | Notebook    | [44f1476d60](https://linux-hardware.org/?probe=44f1476d60) | Nov 06, 2025 |
| AZW           | SER V2.0                    | Mini pc     | [ec84ec19dc](https://linux-hardware.org/?probe=ec84ec19dc) | Nov 06, 2025 |
| Medion        | TJ4125                      | Desktop     | [63e42ef2ef](https://linux-hardware.org/?probe=63e42ef2ef) | Nov 04, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [bd7305e1ab](https://linux-hardware.org/?probe=bd7305e1ab) | Nov 04, 2025 |
| MSI           | Z77A-G43                    | Desktop     | [830f7ec089](https://linux-hardware.org/?probe=830f7ec089) | Nov 04, 2025 |
| Medion        | TJ4125                      | Desktop     | [92b1b520f0](https://linux-hardware.org/?probe=92b1b520f0) | Nov 03, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [56648b4b3e](https://linux-hardware.org/?probe=56648b4b3e) | Nov 02, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [5f6b3561d2](https://linux-hardware.org/?probe=5f6b3561d2) | Nov 01, 2025 |
| G7-2011       | X79                         | Desktop     | [cb93f5ed68](https://linux-hardware.org/?probe=cb93f5ed68) | Nov 01, 2025 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [c02b5b750f](https://linux-hardware.org/?probe=c02b5b750f) | Oct 25, 2025 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [139f361957](https://linux-hardware.org/?probe=139f361957) | Oct 24, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [700d0a69be](https://linux-hardware.org/?probe=700d0a69be) | Oct 23, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [2fd274af0a](https://linux-hardware.org/?probe=2fd274af0a) | Oct 23, 2025 |
| HP            | 8768 A                      | Desktop     | [31a76f1737](https://linux-hardware.org/?probe=31a76f1737) | Oct 23, 2025 |
| ASRock        | N68C-S UCC                  | Desktop     | [a33d72f651](https://linux-hardware.org/?probe=a33d72f651) | Oct 22, 2025 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [a1a196668e](https://linux-hardware.org/?probe=a1a196668e) | Oct 21, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [44c57a362b](https://linux-hardware.org/?probe=44c57a362b) | Oct 21, 2025 |
| HP            | ENVY 17                     | Notebook    | [84498b0f36](https://linux-hardware.org/?probe=84498b0f36) | Oct 20, 2025 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [9af9b0e592](https://linux-hardware.org/?probe=9af9b0e592) | Oct 20, 2025 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [7aa22f1005](https://linux-hardware.org/?probe=7aa22f1005) | Oct 19, 2025 |
| Microsoft     | Surface Laptop              | Tablet      | [4c342b30fc](https://linux-hardware.org/?probe=4c342b30fc) | Oct 19, 2025 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [98d85b2c6b](https://linux-hardware.org/?probe=98d85b2c6b) | Oct 18, 2025 |
| HP            | 8455                        | Desktop     | [d1afecec96](https://linux-hardware.org/?probe=d1afecec96) | Oct 16, 2025 |
| TongFang      | GX5HRXG                     | Notebook    | [ea52c6a754](https://linux-hardware.org/?probe=ea52c6a754) | Oct 15, 2025 |
| Apple         | MacBookPro11,4              | Notebook    | [be9ba7ee72](https://linux-hardware.org/?probe=be9ba7ee72) | Oct 15, 2025 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [0eade221fb](https://linux-hardware.org/?probe=0eade221fb) | Oct 15, 2025 |
| ASUSTek       | GL752VW                     | Notebook    | [563d682a8d](https://linux-hardware.org/?probe=563d682a8d) | Oct 15, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [0085b5dcc3](https://linux-hardware.org/?probe=0085b5dcc3) | Oct 14, 2025 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4ae992ea39](https://linux-hardware.org/?probe=4ae992ea39) | Oct 13, 2025 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [e814c82d53](https://linux-hardware.org/?probe=e814c82d53) | Oct 13, 2025 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [300fd752ee](https://linux-hardware.org/?probe=300fd752ee) | Oct 13, 2025 |
| Gigabyte      | 965P-DS3                    | Desktop     | [b787c8b019](https://linux-hardware.org/?probe=b787c8b019) | Oct 13, 2025 |
| HP            | Notebook                    | Notebook    | [131259ee12](https://linux-hardware.org/?probe=131259ee12) | Oct 12, 2025 |
| Medion        | TJ4125                      | Desktop     | [79e6dbfaac](https://linux-hardware.org/?probe=79e6dbfaac) | Oct 12, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [5feecdba0a](https://linux-hardware.org/?probe=5feecdba0a) | Oct 12, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [3540b90b4e](https://linux-hardware.org/?probe=3540b90b4e) | Oct 11, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [1082b4c4f5](https://linux-hardware.org/?probe=1082b4c4f5) | Oct 11, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2d44f8fc4d](https://linux-hardware.org/?probe=2d44f8fc4d) | Oct 11, 2025 |
| Lenovo        | ThinkPad P52 20MAS44K00     | Notebook    | [069fdf17c0](https://linux-hardware.org/?probe=069fdf17c0) | Oct 11, 2025 |
| Medion        | TJ4125                      | Desktop     | [2d80da577e](https://linux-hardware.org/?probe=2d80da577e) | Oct 11, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [ed6187b48a](https://linux-hardware.org/?probe=ed6187b48a) | Oct 10, 2025 |
| Lenovo        | ThinkPad T420 4178B8G       | Notebook    | [e55c91c220](https://linux-hardware.org/?probe=e55c91c220) | Oct 10, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [e0697dccac](https://linux-hardware.org/?probe=e0697dccac) | Oct 08, 2025 |
| Toshiba       | Satellite C55-C             | Notebook    | [b5a81e32ac](https://linux-hardware.org/?probe=b5a81e32ac) | Oct 08, 2025 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [2b8de78673](https://linux-hardware.org/?probe=2b8de78673) | Oct 08, 2025 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [0597cfadf8](https://linux-hardware.org/?probe=0597cfadf8) | Oct 06, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [0e4fc5a6c1](https://linux-hardware.org/?probe=0e4fc5a6c1) | Oct 05, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [7e8aa7cb9b](https://linux-hardware.org/?probe=7e8aa7cb9b) | Oct 05, 2025 |
| HP            | 1587h                       | Desktop     | [d7614e4788](https://linux-hardware.org/?probe=d7614e4788) | Oct 05, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [e403afa6ba](https://linux-hardware.org/?probe=e403afa6ba) | Oct 05, 2025 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [9ecb50c5f0](https://linux-hardware.org/?probe=9ecb50c5f0) | Oct 04, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [68bceb1ac9](https://linux-hardware.org/?probe=68bceb1ac9) | Oct 03, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [f51c3ead9c](https://linux-hardware.org/?probe=f51c3ead9c) | Oct 03, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [8539e30e49](https://linux-hardware.org/?probe=8539e30e49) | Oct 02, 2025 |
| HP            | 18E7                        | Desktop     | [99ee0a97ed](https://linux-hardware.org/?probe=99ee0a97ed) | Oct 02, 2025 |
| HP            | 86F3 00100                  | All in one  | [1e5d9be6b7](https://linux-hardware.org/?probe=1e5d9be6b7) | Sep 30, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [6b58f6c9ca](https://linux-hardware.org/?probe=6b58f6c9ca) | Sep 30, 2025 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [ac6df1261a](https://linux-hardware.org/?probe=ac6df1261a) | Sep 30, 2025 |
| HP            | 86F3 00100                  | All in one  | [8dcc4f730d](https://linux-hardware.org/?probe=8dcc4f730d) | Sep 30, 2025 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [c2431dbbc0](https://linux-hardware.org/?probe=c2431dbbc0) | Sep 29, 2025 |
| GEEKOM        | AE8                         | Desktop     | [09521a14be](https://linux-hardware.org/?probe=09521a14be) | Sep 28, 2025 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [66ce917656](https://linux-hardware.org/?probe=66ce917656) | Sep 28, 2025 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [a90d4a2020](https://linux-hardware.org/?probe=a90d4a2020) | Sep 27, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [fc5652c4d3](https://linux-hardware.org/?probe=fc5652c4d3) | Sep 26, 2025 |
| Medion        | TJ4125                      | Desktop     | [69fb618207](https://linux-hardware.org/?probe=69fb618207) | Sep 26, 2025 |
| Dell          | Latitude 5540               | Notebook    | [97cf132dce](https://linux-hardware.org/?probe=97cf132dce) | Sep 26, 2025 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | Notebook    | [aca9926bd9](https://linux-hardware.org/?probe=aca9926bd9) | Sep 26, 2025 |
| Dell          | 076YDP A00                  | All in one  | [3d7fc4235c](https://linux-hardware.org/?probe=3d7fc4235c) | Sep 26, 2025 |
| Acer          | Aspire 5738                 | Notebook    | [901ebde97b](https://linux-hardware.org/?probe=901ebde97b) | Sep 26, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [d1af2b6bdc](https://linux-hardware.org/?probe=d1af2b6bdc) | Sep 24, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [7e96e10431](https://linux-hardware.org/?probe=7e96e10431) | Sep 24, 2025 |
| Unknown       | Unknown                     | Notebook    | [3c9e8fc339](https://linux-hardware.org/?probe=3c9e8fc339) | Sep 22, 2025 |
| Unknown       | Unknown                     | Notebook    | [a8e6ab6d44](https://linux-hardware.org/?probe=a8e6ab6d44) | Sep 22, 2025 |
| Apple         | MacBookPro5,1               | Notebook    | [924643daa8](https://linux-hardware.org/?probe=924643daa8) | Sep 22, 2025 |
| Apple         | MacBookPro5,1               | Notebook    | [8085f1eaac](https://linux-hardware.org/?probe=8085f1eaac) | Sep 22, 2025 |
| Acer          | Aspire one                  | Notebook    | [8a24f5fbdc](https://linux-hardware.org/?probe=8a24f5fbdc) | Sep 22, 2025 |
| Toshiba       | Satellite M70               | Notebook    | [54d441b3fa](https://linux-hardware.org/?probe=54d441b3fa) | Sep 21, 2025 |
| Toshiba       | Satellite M70               | Notebook    | [9cf9562359](https://linux-hardware.org/?probe=9cf9562359) | Sep 21, 2025 |
| GMKtec        | NucBoxG9                    | Other       | [fe29d7a39c](https://linux-hardware.org/?probe=fe29d7a39c) | Sep 17, 2025 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [be8df43d21](https://linux-hardware.org/?probe=be8df43d21) | Sep 17, 2025 |
| Gigabyte      | A520M K V2                  | Desktop     | [5423a2a6a0](https://linux-hardware.org/?probe=5423a2a6a0) | Sep 16, 2025 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [855c81f6be](https://linux-hardware.org/?probe=855c81f6be) | Sep 15, 2025 |
| ASUSTek       | A5402WVAR                   | All in one  | [a386586b25](https://linux-hardware.org/?probe=a386586b25) | Sep 13, 2025 |
| ASUSTek       | K73SV                       | Notebook    | [9e6145f8df](https://linux-hardware.org/?probe=9e6145f8df) | Sep 11, 2025 |
| Lenovo        | 317C SDK0J40697 WIN 3305... | Desktop     | [4ac7b0be11](https://linux-hardware.org/?probe=4ac7b0be11) | Sep 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [3200ccfa92](https://linux-hardware.org/?probe=3200ccfa92) | Sep 09, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [2c3909ea86](https://linux-hardware.org/?probe=2c3909ea86) | Sep 08, 2025 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [d195da9d7f](https://linux-hardware.org/?probe=d195da9d7f) | Sep 07, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [668b4fbb96](https://linux-hardware.org/?probe=668b4fbb96) | Sep 07, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [e52a856e67](https://linux-hardware.org/?probe=e52a856e67) | Sep 07, 2025 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [ee552d56cc](https://linux-hardware.org/?probe=ee552d56cc) | Sep 06, 2025 |
| Medion        | TJ4125                      | Desktop     | [19d5d8b4f0](https://linux-hardware.org/?probe=19d5d8b4f0) | Sep 06, 2025 |
| Medion        | TJ4125                      | Desktop     | [c020fb32c9](https://linux-hardware.org/?probe=c020fb32c9) | Sep 06, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [b5bc73ae4d](https://linux-hardware.org/?probe=b5bc73ae4d) | Sep 05, 2025 |
| Acer          | Nitro AN515-51              | Notebook    | [cfe2b75b50](https://linux-hardware.org/?probe=cfe2b75b50) | Sep 04, 2025 |
| AZW           | SER V2.0                    | Mini pc     | [8d404bbb9c](https://linux-hardware.org/?probe=8d404bbb9c) | Sep 04, 2025 |
| Dell          | 0F0TGN A00                  | Desktop     | [028e8ba4e0](https://linux-hardware.org/?probe=028e8ba4e0) | Sep 03, 2025 |
| ASUSTek       | X441SA                      | Notebook    | [f8ec81dd03](https://linux-hardware.org/?probe=f8ec81dd03) | Sep 02, 2025 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [bae7ced05f](https://linux-hardware.org/?probe=bae7ced05f) | Sep 02, 2025 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [4b033155c6](https://linux-hardware.org/?probe=4b033155c6) | Sep 01, 2025 |
| Dell          | 0RY007                      | Desktop     | [a9cda38b58](https://linux-hardware.org/?probe=a9cda38b58) | Sep 01, 2025 |
| ASUSTek       | Z77-A                       | Desktop     | [d14cd8d02c](https://linux-hardware.org/?probe=d14cd8d02c) | Sep 01, 2025 |
| HP            | Laptop 15-bw0xx             | Notebook    | [97b6eff50d](https://linux-hardware.org/?probe=97b6eff50d) | Sep 01, 2025 |
| Lenovo        | ThinkPad Yoga 370 20JJS3... | Convertible | [eb921b0fd8](https://linux-hardware.org/?probe=eb921b0fd8) | Aug 30, 2025 |
| Dell          | 0F0TGN A00                  | Desktop     | [df4aec1d37](https://linux-hardware.org/?probe=df4aec1d37) | Aug 30, 2025 |
| Dell          | Precision M6300             | Notebook    | [dabf8d0fbb](https://linux-hardware.org/?probe=dabf8d0fbb) | Aug 27, 2025 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1adf3a3841](https://linux-hardware.org/?probe=1adf3a3841) | Aug 26, 2025 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e7930bbade](https://linux-hardware.org/?probe=e7930bbade) | Aug 24, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d507e6e482](https://linux-hardware.org/?probe=d507e6e482) | Aug 24, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [a35db4cb96](https://linux-hardware.org/?probe=a35db4cb96) | Aug 23, 2025 |
| Acer          | Aspire ES1-533              | Notebook    | [124b4313d4](https://linux-hardware.org/?probe=124b4313d4) | Aug 22, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [acb936e5c4](https://linux-hardware.org/?probe=acb936e5c4) | Aug 22, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [29307b6ba6](https://linux-hardware.org/?probe=29307b6ba6) | Aug 19, 2025 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [bb49be6acb](https://linux-hardware.org/?probe=bb49be6acb) | Aug 19, 2025 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [c2cf331637](https://linux-hardware.org/?probe=c2cf331637) | Aug 19, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [45339db027](https://linux-hardware.org/?probe=45339db027) | Aug 19, 2025 |
| Dell          | Latitude E7470              | Notebook    | [8f1a6f7728](https://linux-hardware.org/?probe=8f1a6f7728) | Aug 18, 2025 |
| ASUSTek       | 1005PE                      | Notebook    | [998f306138](https://linux-hardware.org/?probe=998f306138) | Aug 17, 2025 |
| AZW           | SER V2.0                    | Mini pc     | [6f887a5aa0](https://linux-hardware.org/?probe=6f887a5aa0) | Aug 15, 2025 |
| HP            | 0B40h                       | Desktop     | [32f5bb2fc7](https://linux-hardware.org/?probe=32f5bb2fc7) | Aug 14, 2025 |
| HP            | 2820h                       | Desktop     | [7fe6722bde](https://linux-hardware.org/?probe=7fe6722bde) | Aug 13, 2025 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [2a8cb6a696](https://linux-hardware.org/?probe=2a8cb6a696) | Aug 13, 2025 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [3bcd7f432c](https://linux-hardware.org/?probe=3bcd7f432c) | Aug 12, 2025 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [ecbc9c69f6](https://linux-hardware.org/?probe=ecbc9c69f6) | Aug 10, 2025 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [3ec1ab5846](https://linux-hardware.org/?probe=3ec1ab5846) | Aug 08, 2025 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [2009872cd3](https://linux-hardware.org/?probe=2009872cd3) | Aug 08, 2025 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2fe929814c](https://linux-hardware.org/?probe=2fe929814c) | Aug 07, 2025 |
| Lenovo        | IdeaPad Duet 3 10IGL5-LT... | Tablet      | [4bc7509f04](https://linux-hardware.org/?probe=4bc7509f04) | Aug 06, 2025 |
| ASUSTek       | TUF Gaming B850-BTF WIFI... | Desktop     | [d1eafaf49b](https://linux-hardware.org/?probe=d1eafaf49b) | Aug 06, 2025 |
| ASUSTek       | TUF Gaming B850-BTF WIFI... | Desktop     | [2578e8015b](https://linux-hardware.org/?probe=2578e8015b) | Aug 06, 2025 |
| Supermicro    | H8SGL                       | Server      | [c7b434e119](https://linux-hardware.org/?probe=c7b434e119) | Aug 06, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [425a790738](https://linux-hardware.org/?probe=425a790738) | Aug 06, 2025 |
| Dell          | 0F756F A00                  | Desktop     | [4c88458a84](https://linux-hardware.org/?probe=4c88458a84) | Aug 06, 2025 |
| Valve         | Jupiter                     | Notebook    | [18ac09384e](https://linux-hardware.org/?probe=18ac09384e) | Aug 06, 2025 |
| Dell          | 076YDP A00                  | All in one  | [0ef0b582e3](https://linux-hardware.org/?probe=0ef0b582e3) | Aug 05, 2025 |
| Dell          | 0F756F A00                  | Desktop     | [053f2e82d8](https://linux-hardware.org/?probe=053f2e82d8) | Aug 05, 2025 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [b55f8909e0](https://linux-hardware.org/?probe=b55f8909e0) | Aug 04, 2025 |
| Dell          | Latitude E5510              | Notebook    | [40d2478a7b](https://linux-hardware.org/?probe=40d2478a7b) | Aug 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [086db7ca95](https://linux-hardware.org/?probe=086db7ca95) | Aug 02, 2025 |
| Dell          | Inspiron 15-3567            | Notebook    | [b3cf0f28d3](https://linux-hardware.org/?probe=b3cf0f28d3) | Aug 02, 2025 |
| Acer          | TravelMate P216-51-G2-TC... | Notebook    | [8124f73595](https://linux-hardware.org/?probe=8124f73595) | Aug 02, 2025 |
| ASRock        | Z690 Phantom Gaming 4/D5    | Desktop     | [76f7babeb1](https://linux-hardware.org/?probe=76f7babeb1) | Aug 01, 2025 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [a6588b8d70](https://linux-hardware.org/?probe=a6588b8d70) | Aug 01, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [7584be8edb](https://linux-hardware.org/?probe=7584be8edb) | Jul 31, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [46aca721ed](https://linux-hardware.org/?probe=46aca721ed) | Jul 31, 2025 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0aeaebbf0c](https://linux-hardware.org/?probe=0aeaebbf0c) | Jul 31, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [0f6bfa377d](https://linux-hardware.org/?probe=0f6bfa377d) | Jul 30, 2025 |
| Acer          | Spin SP514-51N              | Convertible | [0c1b2eb8dd](https://linux-hardware.org/?probe=0c1b2eb8dd) | Jul 29, 2025 |
| Lenovo        | ThinkPad T530 24293N0       | Notebook    | [9f1aa28371](https://linux-hardware.org/?probe=9f1aa28371) | Jul 28, 2025 |
| ASUSTek       | H97M-E                      | Desktop     | [abfde43d99](https://linux-hardware.org/?probe=abfde43d99) | Jul 28, 2025 |
| Dell          | Precision M4600             | Notebook    | [60f441636b](https://linux-hardware.org/?probe=60f441636b) | Jul 27, 2025 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f4d167f83f](https://linux-hardware.org/?probe=f4d167f83f) | Jul 27, 2025 |
| HP            | ProBook 6570b               | Notebook    | [90b528b791](https://linux-hardware.org/?probe=90b528b791) | Jul 26, 2025 |
| HP            | 0B40h                       | Desktop     | [876fc49961](https://linux-hardware.org/?probe=876fc49961) | Jul 23, 2025 |
| Framework     | Laptop 13 (AMD Ryzen AI ... | Notebook    | [cc3237f47d](https://linux-hardware.org/?probe=cc3237f47d) | Jul 23, 2025 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [5ceced75d6](https://linux-hardware.org/?probe=5ceced75d6) | Jul 22, 2025 |
| Dell          | 076YDP A00                  | All in one  | [f6a1788684](https://linux-hardware.org/?probe=f6a1788684) | Jul 22, 2025 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [66ba6920a3](https://linux-hardware.org/?probe=66ba6920a3) | Jul 22, 2025 |
| HP            | ENVY 17                     | Notebook    | [04fa992d5b](https://linux-hardware.org/?probe=04fa992d5b) | Jul 20, 2025 |
| Medion        | TJ4125                      | Desktop     | [19aff278e5](https://linux-hardware.org/?probe=19aff278e5) | Jul 19, 2025 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [f9716af58a](https://linux-hardware.org/?probe=f9716af58a) | Jul 18, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [4c843ee634](https://linux-hardware.org/?probe=4c843ee634) | Jul 17, 2025 |
| Shenzhen M... | F8BAC                       | Mini pc     | [b8db3bfed6](https://linux-hardware.org/?probe=b8db3bfed6) | Jul 15, 2025 |
| Shenzhen M... | F8BAC                       | Mini pc     | [aac3e5069d](https://linux-hardware.org/?probe=aac3e5069d) | Jul 14, 2025 |
| Shenzhen M... | F8BAC                       | Mini pc     | [1e1266d98c](https://linux-hardware.org/?probe=1e1266d98c) | Jul 13, 2025 |
| ASUSTek       | G501JW                      | Notebook    | [c6434731d2](https://linux-hardware.org/?probe=c6434731d2) | Jul 13, 2025 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [fcc02de185](https://linux-hardware.org/?probe=fcc02de185) | Jul 13, 2025 |
| Medion        | TJ4125                      | Desktop     | [ead4f97792](https://linux-hardware.org/?probe=ead4f97792) | Jul 12, 2025 |
| Dell          | Latitude 5420               | Notebook    | [593603f373](https://linux-hardware.org/?probe=593603f373) | Jul 12, 2025 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [527cda9f0c](https://linux-hardware.org/?probe=527cda9f0c) | Jul 11, 2025 |
| Dell          | Latitude 5440               | Notebook    | [d3762293d9](https://linux-hardware.org/?probe=d3762293d9) | Jul 11, 2025 |
| Lenovo        | ThinkPad T480s 20L8S3UA0... | Notebook    | [6083f0e5aa](https://linux-hardware.org/?probe=6083f0e5aa) | Jul 11, 2025 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d6bf310e6c](https://linux-hardware.org/?probe=d6bf310e6c) | Jul 10, 2025 |
| Schenker      | XMG EVO (M24)               | Notebook    | [cb1a0c987d](https://linux-hardware.org/?probe=cb1a0c987d) | Jul 09, 2025 |
| GEEKOM        | A7                          | Desktop     | [51b9dc5acd](https://linux-hardware.org/?probe=51b9dc5acd) | Jul 09, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [17f31ff9bc](https://linux-hardware.org/?probe=17f31ff9bc) | Jul 09, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [5dff61ea79](https://linux-hardware.org/?probe=5dff61ea79) | Jul 08, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [0b30c94223](https://linux-hardware.org/?probe=0b30c94223) | Jul 07, 2025 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [1ed63f1f9c](https://linux-hardware.org/?probe=1ed63f1f9c) | Jul 07, 2025 |
| Intel         | powered classmate PC        | Tablet      | [c75ef36c1f](https://linux-hardware.org/?probe=c75ef36c1f) | Jul 07, 2025 |
| Lenovo        | ThinkPad T480s 20L8S3UA0... | Notebook    | [8bcf8ee7ac](https://linux-hardware.org/?probe=8bcf8ee7ac) | Jul 06, 2025 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2bb00a50d0](https://linux-hardware.org/?probe=2bb00a50d0) | Jul 06, 2025 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6c0adbaf73](https://linux-hardware.org/?probe=6c0adbaf73) | Jul 06, 2025 |
| Intel         | powered classmate PC        | Tablet      | [af0c2ee3ff](https://linux-hardware.org/?probe=af0c2ee3ff) | Jul 06, 2025 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b13b85172c](https://linux-hardware.org/?probe=b13b85172c) | Jul 04, 2025 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4c9772035e](https://linux-hardware.org/?probe=4c9772035e) | Jul 04, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [512cb2c3a5](https://linux-hardware.org/?probe=512cb2c3a5) | Jul 03, 2025 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [131602d786](https://linux-hardware.org/?probe=131602d786) | Jul 02, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [89f53b6c82](https://linux-hardware.org/?probe=89f53b6c82) | Jul 01, 2025 |
| Samsung       | 520U4C/520U4X               | Notebook    | [2f28b67d07](https://linux-hardware.org/?probe=2f28b67d07) | Jul 01, 2025 |
| MSI           | Sword 17 A11UD              | Notebook    | [087c4348c3](https://linux-hardware.org/?probe=087c4348c3) | Jun 30, 2025 |
| HP            | Compaq nx6310 (ES466EA#A... | Notebook    | [a60cf74a4a](https://linux-hardware.org/?probe=a60cf74a4a) | Jun 30, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [061c2763cd](https://linux-hardware.org/?probe=061c2763cd) | Jun 30, 2025 |
| DEXP          | C14-ICW300                  | Notebook    | [3b21a105d8](https://linux-hardware.org/?probe=3b21a105d8) | Jun 29, 2025 |
| Panasonic     | CFSX4-1L                    | Notebook    | [b9e6070def](https://linux-hardware.org/?probe=b9e6070def) | Jun 29, 2025 |
| Panasonic     | CFSX4-1L                    | Notebook    | [3d133a6d15](https://linux-hardware.org/?probe=3d133a6d15) | Jun 29, 2025 |
| Dell          | Inspiron 5402               | Notebook    | [137113f9c1](https://linux-hardware.org/?probe=137113f9c1) | Jun 29, 2025 |
| Acer          | Aspire E5-571P              | Notebook    | [d079ed8ee5](https://linux-hardware.org/?probe=d079ed8ee5) | Jun 28, 2025 |
| HP            | EliteBook x360 1030 G2      | Convertible | [05d3d438b3](https://linux-hardware.org/?probe=05d3d438b3) | Jun 28, 2025 |
| ASRock        | B250M Pro4                  | Desktop     | [23c030fc52](https://linux-hardware.org/?probe=23c030fc52) | Jun 27, 2025 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | Notebook    | [48d3541d4a](https://linux-hardware.org/?probe=48d3541d4a) | Jun 26, 2025 |
| MSI           | H110M PRO-D                 | Desktop     | [9677fb0820](https://linux-hardware.org/?probe=9677fb0820) | Jun 26, 2025 |
| Dell          | 0WR1RF A05                  | Desktop     | [c935ad3bd9](https://linux-hardware.org/?probe=c935ad3bd9) | Jun 25, 2025 |
| Lenovo        | IdeaCentre K330B            | Desktop     | [baa79dad9b](https://linux-hardware.org/?probe=baa79dad9b) | Jun 24, 2025 |
| Dell          | Latitude 5500               | Notebook    | [7fe46a5914](https://linux-hardware.org/?probe=7fe46a5914) | Jun 23, 2025 |
| Acer          | Aspire ES1-533              | Notebook    | [b165f29e68](https://linux-hardware.org/?probe=b165f29e68) | Jun 23, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [d0170c2403](https://linux-hardware.org/?probe=d0170c2403) | Jun 22, 2025 |
| Intel         | D54250WYK H13922-303        | Desktop     | [a4f86ce7fb](https://linux-hardware.org/?probe=a4f86ce7fb) | Jun 22, 2025 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [274069e10a](https://linux-hardware.org/?probe=274069e10a) | Jun 21, 2025 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [783a6ca047](https://linux-hardware.org/?probe=783a6ca047) | Jun 21, 2025 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [07026815a1](https://linux-hardware.org/?probe=07026815a1) | Jun 19, 2025 |
| Dell          | Latitude 5500               | Notebook    | [801b8856dc](https://linux-hardware.org/?probe=801b8856dc) | Jun 19, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [73e9ad5501](https://linux-hardware.org/?probe=73e9ad5501) | Jun 16, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [797a0b684c](https://linux-hardware.org/?probe=797a0b684c) | Jun 16, 2025 |
| Dell          | 00V62H A01                  | Desktop     | [89f331ee71](https://linux-hardware.org/?probe=89f331ee71) | Jun 15, 2025 |
| Dell          | 09M8Y8 A01                  | Desktop     | [66b19b8b8b](https://linux-hardware.org/?probe=66b19b8b8b) | Jun 15, 2025 |
| ASRock        | Z690 Phantom Gaming 4/D5    | Desktop     | [0aeec37aa0](https://linux-hardware.org/?probe=0aeec37aa0) | Jun 15, 2025 |
| AZW           | EQ                          | Mini pc     | [c6b26ff8b9](https://linux-hardware.org/?probe=c6b26ff8b9) | Jun 15, 2025 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [5d1855fa5e](https://linux-hardware.org/?probe=5d1855fa5e) | Jun 13, 2025 |
| Lenovo        | IdeaPad Slim 3 15IRH8 83... | Notebook    | [a37077f308](https://linux-hardware.org/?probe=a37077f308) | Jun 12, 2025 |
| Dell          | System Vostro 3750          | Notebook    | [e0bbb882ff](https://linux-hardware.org/?probe=e0bbb882ff) | Jun 12, 2025 |
| Acer          | Nitro AN515-45              | Notebook    | [5b7027d695](https://linux-hardware.org/?probe=5b7027d695) | Jun 12, 2025 |
| Samsung       | 550XBE/350XBE               | Notebook    | [31725cb1b4](https://linux-hardware.org/?probe=31725cb1b4) | Jun 12, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | Notebook    | [bfa62fbc5f](https://linux-hardware.org/?probe=bfa62fbc5f) | Jun 12, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2a2a5d6f61](https://linux-hardware.org/?probe=2a2a5d6f61) | Jun 11, 2025 |
| HP            | 15                          | Notebook    | [a5cf3fe553](https://linux-hardware.org/?probe=a5cf3fe553) | Jun 10, 2025 |
| LG Electro... | 16Z90TP-K.AA78D             | Notebook    | [70d6df6d52](https://linux-hardware.org/?probe=70d6df6d52) | Jun 10, 2025 |
| Dell          | System Vostro 3750          | Notebook    | [57eae340a3](https://linux-hardware.org/?probe=57eae340a3) | Jun 09, 2025 |
| HP            | EliteBook 735 G5            | Notebook    | [94f0330ec0](https://linux-hardware.org/?probe=94f0330ec0) | Jun 09, 2025 |
| ECS           | H61H2-CM                    | Desktop     | [9541786163](https://linux-hardware.org/?probe=9541786163) | Jun 09, 2025 |
| ASUSTek       | X556UQK                     | Notebook    | [f4bbaaee73](https://linux-hardware.org/?probe=f4bbaaee73) | Jun 08, 2025 |
| Gigabyte      | B460M DS3H AC-Y1            | Desktop     | [e0c47af925](https://linux-hardware.org/?probe=e0c47af925) | Jun 08, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7 I... | Desktop     | [ca5fc3e6bf](https://linux-hardware.org/?probe=ca5fc3e6bf) | Jun 07, 2025 |
| Acer          | Predator PHN16-72           | Notebook    | [f215640dea](https://linux-hardware.org/?probe=f215640dea) | Jun 07, 2025 |
| Medion        | TJ4125                      | Desktop     | [ac1165f893](https://linux-hardware.org/?probe=ac1165f893) | Jun 05, 2025 |
| HP            | 255 15.6 inch G10           | Notebook    | [0e44b7fa50](https://linux-hardware.org/?probe=0e44b7fa50) | Jun 05, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [e7c9ed17e6](https://linux-hardware.org/?probe=e7c9ed17e6) | Jun 04, 2025 |
| Acer          | Aspire A515-51              | Notebook    | [e53301c24f](https://linux-hardware.org/?probe=e53301c24f) | Jun 02, 2025 |
| ASUSTek       | D520MT_D520SF_D320MT        | Desktop     | [8130f151f8](https://linux-hardware.org/?probe=8130f151f8) | Jun 02, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [275d75f10a](https://linux-hardware.org/?probe=275d75f10a) | Jun 02, 2025 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a4dafa5bf4](https://linux-hardware.org/?probe=a4dafa5bf4) | Jun 02, 2025 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [9e73bc5209](https://linux-hardware.org/?probe=9e73bc5209) | Jun 01, 2025 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [7b4176a222](https://linux-hardware.org/?probe=7b4176a222) | Jun 01, 2025 |
| Dell          | Latitude E6410              | Notebook    | [a382aa51d1](https://linux-hardware.org/?probe=a382aa51d1) | May 31, 2025 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [51666db7c9](https://linux-hardware.org/?probe=51666db7c9) | May 31, 2025 |
| MSI           | Z270M MORTAR                | Desktop     | [0d97e1ec7f](https://linux-hardware.org/?probe=0d97e1ec7f) | May 30, 2025 |
| Dell          | Inspiron M5010              | Notebook    | [b671d6afa9](https://linux-hardware.org/?probe=b671d6afa9) | May 29, 2025 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [668bebd807](https://linux-hardware.org/?probe=668bebd807) | May 28, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [069b1c0d9f](https://linux-hardware.org/?probe=069b1c0d9f) | May 28, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [7be3decb5f](https://linux-hardware.org/?probe=7be3decb5f) | May 27, 2025 |
| WeiBu         | ADL-N Prod                  | Desktop     | [443f7decd6](https://linux-hardware.org/?probe=443f7decd6) | May 27, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [2a9de6c241](https://linux-hardware.org/?probe=2a9de6c241) | May 27, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [adca73142b](https://linux-hardware.org/?probe=adca73142b) | May 26, 2025 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [3fb1bae7c8](https://linux-hardware.org/?probe=3fb1bae7c8) | May 25, 2025 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [269f39bab1](https://linux-hardware.org/?probe=269f39bab1) | May 25, 2025 |
| HP            | 339A                        | Desktop     | [0adea6e20d](https://linux-hardware.org/?probe=0adea6e20d) | May 25, 2025 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [ae3778d8ee](https://linux-hardware.org/?probe=ae3778d8ee) | May 25, 2025 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [1756e42bfe](https://linux-hardware.org/?probe=1756e42bfe) | May 25, 2025 |
| Dell          | 02DXT3 A00                  | Mini pc     | [6137e6fe3e](https://linux-hardware.org/?probe=6137e6fe3e) | May 25, 2025 |
| ASUSTek       | 1000HG                      | Notebook    | [b1a314182d](https://linux-hardware.org/?probe=b1a314182d) | May 24, 2025 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f26af33f47](https://linux-hardware.org/?probe=f26af33f47) | May 24, 2025 |
| Intel         | DQ965GF AAD41676-402        | Desktop     | [cbcd411d7c](https://linux-hardware.org/?probe=cbcd411d7c) | May 23, 2025 |
| ASUSTek       | 1000HG                      | Notebook    | [080a23593a](https://linux-hardware.org/?probe=080a23593a) | May 22, 2025 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [479c35845a](https://linux-hardware.org/?probe=479c35845a) | May 21, 2025 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b4c54b9c8b](https://linux-hardware.org/?probe=b4c54b9c8b) | May 19, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [6ae6d2a1e9](https://linux-hardware.org/?probe=6ae6d2a1e9) | May 18, 2025 |
| Fujitsu       | FMVNE4NE                    | Notebook    | [fcaceaf278](https://linux-hardware.org/?probe=fcaceaf278) | May 17, 2025 |
| Dell          | 0X4H68 A00                  | Desktop     | [1a74d03045](https://linux-hardware.org/?probe=1a74d03045) | May 17, 2025 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [ce93cc89b1](https://linux-hardware.org/?probe=ce93cc89b1) | May 17, 2025 |
| Dell          | Latitude E6220              | Notebook    | [d99e1c6942](https://linux-hardware.org/?probe=d99e1c6942) | May 17, 2025 |
| HP            | Pavilion 15                 | Notebook    | [fd5d83e8ec](https://linux-hardware.org/?probe=fd5d83e8ec) | May 15, 2025 |
| HP            | ENVY Notebook               | Notebook    | [211eb100f8](https://linux-hardware.org/?probe=211eb100f8) | May 14, 2025 |
| Irbis         | NB211                       | Notebook    | [626be4dc62](https://linux-hardware.org/?probe=626be4dc62) | May 14, 2025 |
| Dell          | 00V62H A01                  | Desktop     | [f42972c0cd](https://linux-hardware.org/?probe=f42972c0cd) | May 14, 2025 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [5873f9e355](https://linux-hardware.org/?probe=5873f9e355) | May 13, 2025 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [fff2a96d4a](https://linux-hardware.org/?probe=fff2a96d4a) | May 13, 2025 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [f72c58cc29](https://linux-hardware.org/?probe=f72c58cc29) | May 13, 2025 |
| ASUSTek       | H81M-C                      | Desktop     | [11dd2b44ab](https://linux-hardware.org/?probe=11dd2b44ab) | May 12, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [7d60f79865](https://linux-hardware.org/?probe=7d60f79865) | May 12, 2025 |
| Dell          | Latitude 7490               | Notebook    | [81baa645f5](https://linux-hardware.org/?probe=81baa645f5) | May 12, 2025 |
| Lenovo        | IdeaCentre K330B            | Desktop     | [f68a264591](https://linux-hardware.org/?probe=f68a264591) | May 12, 2025 |
| Dell          | 04YP6J A02                  | Desktop     | [533d3b1997](https://linux-hardware.org/?probe=533d3b1997) | May 10, 2025 |
| GEEKOM        | Mini IT11                   | Desktop     | [421d3aae29](https://linux-hardware.org/?probe=421d3aae29) | May 10, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [763b7d4246](https://linux-hardware.org/?probe=763b7d4246) | May 10, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [881f07d761](https://linux-hardware.org/?probe=881f07d761) | May 10, 2025 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [02537d8195](https://linux-hardware.org/?probe=02537d8195) | May 09, 2025 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [c78cb02587](https://linux-hardware.org/?probe=c78cb02587) | May 09, 2025 |
| Apple         | MacBookPro8,2               | Notebook    | [b4d56f61ab](https://linux-hardware.org/?probe=b4d56f61ab) | May 09, 2025 |
| ASUSTek       | X55VD                       | Notebook    | [3a8dc80da2](https://linux-hardware.org/?probe=3a8dc80da2) | May 09, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20T70... | Notebook    | [8c571cb4a2](https://linux-hardware.org/?probe=8c571cb4a2) | May 07, 2025 |
| HP            | ENVY 17                     | Notebook    | [1aca5ec809](https://linux-hardware.org/?probe=1aca5ec809) | May 07, 2025 |
| HP            | ENVY 17                     | Notebook    | [4e1cddaf81](https://linux-hardware.org/?probe=4e1cddaf81) | May 07, 2025 |
| Dell          | 0GX297                      | Desktop     | [36fa47b8bf](https://linux-hardware.org/?probe=36fa47b8bf) | May 06, 2025 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [68105a3ed7](https://linux-hardware.org/?probe=68105a3ed7) | May 06, 2025 |
| NZXT          | N7 B550                     | Desktop     | [db31437e07](https://linux-hardware.org/?probe=db31437e07) | May 05, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [39f23cc47f](https://linux-hardware.org/?probe=39f23cc47f) | May 04, 2025 |
| Sony          | VGN-NS11M_S                 | Notebook    | [a9ee2967aa](https://linux-hardware.org/?probe=a9ee2967aa) | May 04, 2025 |
| Dell          | 09M8Y8 A01                  | Desktop     | [9c14f33700](https://linux-hardware.org/?probe=9c14f33700) | May 04, 2025 |
| Dell          | 09M8Y8 A01                  | Desktop     | [494ce1a7d0](https://linux-hardware.org/?probe=494ce1a7d0) | May 04, 2025 |
| GEEKOM        | AE8                         | Desktop     | [9158c70300](https://linux-hardware.org/?probe=9158c70300) | May 04, 2025 |
| ASRock        | Z690 Phantom Gaming 4/D5    | Desktop     | [8c7b8e24fc](https://linux-hardware.org/?probe=8c7b8e24fc) | May 03, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [47aa3a80b3](https://linux-hardware.org/?probe=47aa3a80b3) | May 03, 2025 |
| GEEKOM        | AE8                         | Desktop     | [7cdc357a94](https://linux-hardware.org/?probe=7cdc357a94) | May 03, 2025 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [1dd652fa65](https://linux-hardware.org/?probe=1dd652fa65) | May 02, 2025 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [ea0bc65f32](https://linux-hardware.org/?probe=ea0bc65f32) | May 02, 2025 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [834a57c287](https://linux-hardware.org/?probe=834a57c287) | May 02, 2025 |
| Lenovo        | ThinkPad T480s 20L8SAWM0... | Notebook    | [eff24ac691](https://linux-hardware.org/?probe=eff24ac691) | May 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [275f7cff84](https://linux-hardware.org/?probe=275f7cff84) | Apr 30, 2025 |
| Gigabyte      | B760M DS3H AX               | Desktop     | [d2dabf6705](https://linux-hardware.org/?probe=d2dabf6705) | Apr 29, 2025 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | Desktop     | [3ec993fcb1](https://linux-hardware.org/?probe=3ec993fcb1) | Apr 28, 2025 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [69a71355b4](https://linux-hardware.org/?probe=69a71355b4) | Apr 28, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a3a7e67460](https://linux-hardware.org/?probe=a3a7e67460) | Apr 28, 2025 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [9adcab1856](https://linux-hardware.org/?probe=9adcab1856) | Apr 27, 2025 |
| Clientron ... | L700                        | Desktop     | [eed16cfff6](https://linux-hardware.org/?probe=eed16cfff6) | Apr 27, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [63c2b4fc77](https://linux-hardware.org/?probe=63c2b4fc77) | Apr 26, 2025 |
| DEXP          | C14-ICW300                  | Notebook    | [6e4fa6bb9c](https://linux-hardware.org/?probe=6e4fa6bb9c) | Apr 26, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [2fbf4c139c](https://linux-hardware.org/?probe=2fbf4c139c) | Apr 25, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [0ee593b4f2](https://linux-hardware.org/?probe=0ee593b4f2) | Apr 25, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [3e459dab89](https://linux-hardware.org/?probe=3e459dab89) | Apr 25, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [dd487cf2a9](https://linux-hardware.org/?probe=dd487cf2a9) | Apr 25, 2025 |
| Lenovo        | ThinkPad X230 23252R0       | Notebook    | [ebb1f88303](https://linux-hardware.org/?probe=ebb1f88303) | Apr 24, 2025 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [9ddbf43336](https://linux-hardware.org/?probe=9ddbf43336) | Apr 24, 2025 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [a4ffee729b](https://linux-hardware.org/?probe=a4ffee729b) | Apr 24, 2025 |
| Acer          | Predator G9-593             | Notebook    | [d7f0f6c780](https://linux-hardware.org/?probe=d7f0f6c780) | Apr 22, 2025 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [05f864bfdf](https://linux-hardware.org/?probe=05f864bfdf) | Apr 21, 2025 |
| KUU           | Andes                       | Tablet      | [87a983be89](https://linux-hardware.org/?probe=87a983be89) | Apr 21, 2025 |
| HP            | ProBook 450 G1              | Notebook    | [300ad9d16a](https://linux-hardware.org/?probe=300ad9d16a) | Apr 21, 2025 |
| ASUSTek       | X551CA                      | Notebook    | [a29b2b2d6d](https://linux-hardware.org/?probe=a29b2b2d6d) | Apr 20, 2025 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c64b2890b9](https://linux-hardware.org/?probe=c64b2890b9) | Apr 19, 2025 |
| Unknown       | RX16                        | Notebook    | [1c672dbb34](https://linux-hardware.org/?probe=1c672dbb34) | Apr 19, 2025 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [eecc516f02](https://linux-hardware.org/?probe=eecc516f02) | Apr 18, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [3cf36ba352](https://linux-hardware.org/?probe=3cf36ba352) | Apr 17, 2025 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d9c64bab83](https://linux-hardware.org/?probe=d9c64bab83) | Apr 17, 2025 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [d1296e658b](https://linux-hardware.org/?probe=d1296e658b) | Apr 17, 2025 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [50069c6280](https://linux-hardware.org/?probe=50069c6280) | Apr 17, 2025 |
| ASRock        | B85 Pro4                    | Desktop     | [6cea1e7a20](https://linux-hardware.org/?probe=6cea1e7a20) | Apr 16, 2025 |
| ASRock        | B85 Pro4                    | Desktop     | [824c2a3efb](https://linux-hardware.org/?probe=824c2a3efb) | Apr 16, 2025 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5f5a576b99](https://linux-hardware.org/?probe=5f5a576b99) | Apr 16, 2025 |
| HP            | Bloog                       | Notebook    | [53877958f6](https://linux-hardware.org/?probe=53877958f6) | Apr 16, 2025 |
| HP            | Bloog                       | Notebook    | [2a169eec95](https://linux-hardware.org/?probe=2a169eec95) | Apr 16, 2025 |
| Lenovo        | ThinkStation S20 4105J6G    | Desktop     | [dcca17605e](https://linux-hardware.org/?probe=dcca17605e) | Apr 15, 2025 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [63e7cb0712](https://linux-hardware.org/?probe=63e7cb0712) | Apr 15, 2025 |
| Lenovo        | ThinkPad Edge E530 62722... | Notebook    | [8994427db1](https://linux-hardware.org/?probe=8994427db1) | Apr 15, 2025 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [11213d9da0](https://linux-hardware.org/?probe=11213d9da0) | Apr 15, 2025 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [5238125a52](https://linux-hardware.org/?probe=5238125a52) | Apr 15, 2025 |
| Dell          | 0WWJRX A00                  | Desktop     | [5cb44e756c](https://linux-hardware.org/?probe=5cb44e756c) | Apr 14, 2025 |
| Dell          | 0WWJRX A00                  | Desktop     | [9e0233cc61](https://linux-hardware.org/?probe=9e0233cc61) | Apr 14, 2025 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ddb0b76533](https://linux-hardware.org/?probe=ddb0b76533) | Apr 14, 2025 |
| Unknown       | RX16                        | Notebook    | [44adf0c721](https://linux-hardware.org/?probe=44adf0c721) | Apr 14, 2025 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7522f8f475](https://linux-hardware.org/?probe=7522f8f475) | Apr 14, 2025 |
| Acer          | Nitro AN515-45              | Notebook    | [4e87a1956a](https://linux-hardware.org/?probe=4e87a1956a) | Apr 14, 2025 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [944fb85015](https://linux-hardware.org/?probe=944fb85015) | Apr 13, 2025 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [cc4bab3b31](https://linux-hardware.org/?probe=cc4bab3b31) | Apr 13, 2025 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [81b8aee7da](https://linux-hardware.org/?probe=81b8aee7da) | Apr 13, 2025 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [33006cb0cd](https://linux-hardware.org/?probe=33006cb0cd) | Apr 13, 2025 |
| Dell          | Latitude E5520              | Notebook    | [578c98ac9b](https://linux-hardware.org/?probe=578c98ac9b) | Apr 12, 2025 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [56f4429990](https://linux-hardware.org/?probe=56f4429990) | Apr 12, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [5673cbf22f](https://linux-hardware.org/?probe=5673cbf22f) | Apr 11, 2025 |
| Biostar       | H310MHC2                    | Desktop     | [1ab3c7b926](https://linux-hardware.org/?probe=1ab3c7b926) | Apr 08, 2025 |
| MSI           | C847MS-E33                  | Desktop     | [46cd07a997](https://linux-hardware.org/?probe=46cd07a997) | Apr 07, 2025 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [719ad29e5f](https://linux-hardware.org/?probe=719ad29e5f) | Apr 03, 2025 |
| HP            | EliteBook x360 1030 G3      | Convertible | [690a2b1396](https://linux-hardware.org/?probe=690a2b1396) | Apr 03, 2025 |
| HP            | EliteBook x360 1030 G3      | Convertible | [be771b7f18](https://linux-hardware.org/?probe=be771b7f18) | Apr 03, 2025 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [c0eaeaab84](https://linux-hardware.org/?probe=c0eaeaab84) | Apr 02, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [a48cc302b6](https://linux-hardware.org/?probe=a48cc302b6) | Apr 02, 2025 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [ca0dcab902](https://linux-hardware.org/?probe=ca0dcab902) | Apr 02, 2025 |
| ASUSTek       | N50Vn                       | Notebook    | [6a86db3c24](https://linux-hardware.org/?probe=6a86db3c24) | Apr 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [cc9aef254d](https://linux-hardware.org/?probe=cc9aef254d) | Apr 02, 2025 |
| ASUSTek       | P7P55D LE                   | Desktop     | [a5bf5753af](https://linux-hardware.org/?probe=a5bf5753af) | Apr 02, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [7fbaf978ab](https://linux-hardware.org/?probe=7fbaf978ab) | Mar 31, 2025 |
| Lenovo        | V14 G2 IJL 82QX             | Notebook    | [93926c39df](https://linux-hardware.org/?probe=93926c39df) | Mar 31, 2025 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [73732a2f7c](https://linux-hardware.org/?probe=73732a2f7c) | Mar 30, 2025 |
| Dell          | Latitude E6410              | Notebook    | [5e17eea694](https://linux-hardware.org/?probe=5e17eea694) | Mar 30, 2025 |
| Dell          | Latitude E6410              | Notebook    | [f252509fe9](https://linux-hardware.org/?probe=f252509fe9) | Mar 30, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [bbf10c5775](https://linux-hardware.org/?probe=bbf10c5775) | Mar 29, 2025 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [8699e5c8bf](https://linux-hardware.org/?probe=8699e5c8bf) | Mar 29, 2025 |
| Lenovo        | SHARKBAY 31900003 STD       | Desktop     | [b767cf4f14](https://linux-hardware.org/?probe=b767cf4f14) | Mar 29, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [8b9aa62385](https://linux-hardware.org/?probe=8b9aa62385) | Mar 28, 2025 |
| HP            | 1497                        | Desktop     | [a6252a2fea](https://linux-hardware.org/?probe=a6252a2fea) | Mar 28, 2025 |
| Apple         | MacBookAir5,1               | Notebook    | [7a3d380989](https://linux-hardware.org/?probe=7a3d380989) | Mar 28, 2025 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [6c2e466d8e](https://linux-hardware.org/?probe=6c2e466d8e) | Mar 27, 2025 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1686a17e4a](https://linux-hardware.org/?probe=1686a17e4a) | Mar 27, 2025 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [e7b070821e](https://linux-hardware.org/?probe=e7b070821e) | Mar 27, 2025 |
| ASUSTek       | E402SA                      | Notebook    | [cb7ef7d9b4](https://linux-hardware.org/?probe=cb7ef7d9b4) | Mar 26, 2025 |
| ASRock        | B250M Pro4                  | Desktop     | [d80d521a9d](https://linux-hardware.org/?probe=d80d521a9d) | Mar 25, 2025 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [8509906ade](https://linux-hardware.org/?probe=8509906ade) | Mar 25, 2025 |
| ECS           | A780GM-A                    | Desktop     | [12d6f63d69](https://linux-hardware.org/?probe=12d6f63d69) | Mar 24, 2025 |
| ECS           | A780GM-A                    | Desktop     | [036a7b9176](https://linux-hardware.org/?probe=036a7b9176) | Mar 24, 2025 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [03e61d8837](https://linux-hardware.org/?probe=03e61d8837) | Mar 23, 2025 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [98c1501794](https://linux-hardware.org/?probe=98c1501794) | Mar 22, 2025 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d1d8d4c0ea](https://linux-hardware.org/?probe=d1d8d4c0ea) | Mar 22, 2025 |
| MSI           | Bravo 15 B5DD               | Notebook    | [8071d8697d](https://linux-hardware.org/?probe=8071d8697d) | Mar 22, 2025 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [cd0ee8a653](https://linux-hardware.org/?probe=cd0ee8a653) | Mar 22, 2025 |
| Notebook      | W65_67SZ                    | Notebook    | [bdef705981](https://linux-hardware.org/?probe=bdef705981) | Mar 21, 2025 |
| Dell          | 0Y2MRG A00                  | Desktop     | [d43df1600f](https://linux-hardware.org/?probe=d43df1600f) | Mar 21, 2025 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [6d433888f2](https://linux-hardware.org/?probe=6d433888f2) | Mar 20, 2025 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [c419030a03](https://linux-hardware.org/?probe=c419030a03) | Mar 18, 2025 |
| Apple         | Mac-F2268DC8                | All in one  | [be3dd9a863](https://linux-hardware.org/?probe=be3dd9a863) | Mar 18, 2025 |
| ASRock        | H110M-HG4                   | Desktop     | [33b8554985](https://linux-hardware.org/?probe=33b8554985) | Mar 18, 2025 |
| ASUSTek       | E402SA                      | Notebook    | [dfa5a3ebc3](https://linux-hardware.org/?probe=dfa5a3ebc3) | Mar 18, 2025 |
| Dell          | 0Y2MRG A00                  | Desktop     | [1cb24fc1b0](https://linux-hardware.org/?probe=1cb24fc1b0) | Mar 18, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [7e072f0213](https://linux-hardware.org/?probe=7e072f0213) | Mar 17, 2025 |
| Infinix       | INBook X1                   | Notebook    | [58b1fcaeeb](https://linux-hardware.org/?probe=58b1fcaeeb) | Mar 16, 2025 |
| Samsung       | 950XED                      | Notebook    | [0ef4486b16](https://linux-hardware.org/?probe=0ef4486b16) | Mar 16, 2025 |
| Samsung       | 950XED                      | Notebook    | [0b5113ecd8](https://linux-hardware.org/?probe=0b5113ecd8) | Mar 16, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [ecc64e6edd](https://linux-hardware.org/?probe=ecc64e6edd) | Mar 15, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [7322d63795](https://linux-hardware.org/?probe=7322d63795) | Mar 15, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [a3314aa5b6](https://linux-hardware.org/?probe=a3314aa5b6) | Mar 15, 2025 |
| ASUSTek       | T101HA                      | Notebook    | [720e41ab07](https://linux-hardware.org/?probe=720e41ab07) | Mar 15, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [89fbf1d072](https://linux-hardware.org/?probe=89fbf1d072) | Mar 14, 2025 |
| Dell          | 0TP406                      | Desktop     | [2b332802b6](https://linux-hardware.org/?probe=2b332802b6) | Mar 14, 2025 |
| ASUSTek       | P5B-MX                      | Desktop     | [35cb44c5c5](https://linux-hardware.org/?probe=35cb44c5c5) | Mar 12, 2025 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [ed38c68aea](https://linux-hardware.org/?probe=ed38c68aea) | Mar 12, 2025 |
| HP            | EliteBook 8530w             | Notebook    | [09c73a1fa8](https://linux-hardware.org/?probe=09c73a1fa8) | Mar 11, 2025 |
| HP            | EliteBook 8530w             | Notebook    | [af6d86b56c](https://linux-hardware.org/?probe=af6d86b56c) | Mar 11, 2025 |
| Dell          | 0X4H68 A00                  | Desktop     | [2cc90f7a43](https://linux-hardware.org/?probe=2cc90f7a43) | Mar 10, 2025 |
| HP            | 255 15.6 inch G10           | Notebook    | [455f0f016b](https://linux-hardware.org/?probe=455f0f016b) | Mar 10, 2025 |
| Lenovo        | IdeaCentre K330B            | Desktop     | [34aa7baafc](https://linux-hardware.org/?probe=34aa7baafc) | Mar 10, 2025 |
| Dell          | Inspiron 1501               | Notebook    | [b48488a2dc](https://linux-hardware.org/?probe=b48488a2dc) | Mar 09, 2025 |
| Dell          | Inspiron 1501               | Notebook    | [2e3724cf78](https://linux-hardware.org/?probe=2e3724cf78) | Mar 09, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [36c2b32c38](https://linux-hardware.org/?probe=36c2b32c38) | Mar 08, 2025 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [101d1b41e6](https://linux-hardware.org/?probe=101d1b41e6) | Mar 08, 2025 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [cbf9d9810a](https://linux-hardware.org/?probe=cbf9d9810a) | Mar 08, 2025 |
| Unknown       | RX16                        | Notebook    | [6c5e935c08](https://linux-hardware.org/?probe=6c5e935c08) | Mar 07, 2025 |
| Dell          | G15 5530                    | Notebook    | [d2c9a3ff2d](https://linux-hardware.org/?probe=d2c9a3ff2d) | Mar 05, 2025 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [e4731d0c0d](https://linux-hardware.org/?probe=e4731d0c0d) | Mar 05, 2025 |
| HP            | Compaq nx7300 (GB853ES#A... | Notebook    | [79dbded025](https://linux-hardware.org/?probe=79dbded025) | Mar 04, 2025 |
| ASUSTek       | 1000HG                      | Notebook    | [57f026924b](https://linux-hardware.org/?probe=57f026924b) | Mar 04, 2025 |
| Acer          | Predator PHN16-72           | Notebook    | [a02d2c9599](https://linux-hardware.org/?probe=a02d2c9599) | Mar 04, 2025 |
| Dell          | G15 5530                    | Notebook    | [68ff312a0a](https://linux-hardware.org/?probe=68ff312a0a) | Mar 03, 2025 |
| Acer          | Aspire GX-781               | Desktop     | [aa719f1093](https://linux-hardware.org/?probe=aa719f1093) | Mar 03, 2025 |
| Fujitsu       | LIFEBOOK A544               | Notebook    | [c9b2d3e644](https://linux-hardware.org/?probe=c9b2d3e644) | Mar 02, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [79f6a57ef0](https://linux-hardware.org/?probe=79f6a57ef0) | Feb 28, 2025 |
| ASUSTek       | B85M-G                      | Desktop     | [5aee5aae1b](https://linux-hardware.org/?probe=5aee5aae1b) | Feb 28, 2025 |
| ASUSTek       | B85M-G                      | Desktop     | [5c7a810ab7](https://linux-hardware.org/?probe=5c7a810ab7) | Feb 27, 2025 |
| Samsung       | 535U3C                      | Notebook    | [7f38a96ed8](https://linux-hardware.org/?probe=7f38a96ed8) | Feb 27, 2025 |
| Fujitsu       | CELSIUS H7510               | Notebook    | [8a63782ebb](https://linux-hardware.org/?probe=8a63782ebb) | Feb 26, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [f810c98a11](https://linux-hardware.org/?probe=f810c98a11) | Feb 26, 2025 |
| Toshiba       | Satellite P200              | Notebook    | [79f1233b4b](https://linux-hardware.org/?probe=79f1233b4b) | Feb 24, 2025 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [2bab9341c4](https://linux-hardware.org/?probe=2bab9341c4) | Feb 23, 2025 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [e80a15fdad](https://linux-hardware.org/?probe=e80a15fdad) | Feb 23, 2025 |
| HC Technol... | HCAR4000-MI                 | Desktop     | [54e76aa36e](https://linux-hardware.org/?probe=54e76aa36e) | Feb 23, 2025 |
| ASUSTek       | P5Q                         | Desktop     | [2f5cc472e4](https://linux-hardware.org/?probe=2f5cc472e4) | Feb 23, 2025 |
| ASUSTek       | P5Q                         | Desktop     | [dfc1e4f83f](https://linux-hardware.org/?probe=dfc1e4f83f) | Feb 23, 2025 |
| Acer          | Aspire E5-573               | Notebook    | [b362b69e32](https://linux-hardware.org/?probe=b362b69e32) | Feb 23, 2025 |
| MSI           | B75MA-P45                   | Desktop     | [7474b49f5c](https://linux-hardware.org/?probe=7474b49f5c) | Feb 22, 2025 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [b4ce5d02e0](https://linux-hardware.org/?probe=b4ce5d02e0) | Feb 22, 2025 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [4cbb50c8f2](https://linux-hardware.org/?probe=4cbb50c8f2) | Feb 20, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [773c1163d0](https://linux-hardware.org/?probe=773c1163d0) | Feb 19, 2025 |
| ASUSTek       | PN53-G                      | Mini pc     | [82ef044807](https://linux-hardware.org/?probe=82ef044807) | Feb 17, 2025 |
| Dell          | Inspiron 3537               | Notebook    | [a1f51e4a67](https://linux-hardware.org/?probe=a1f51e4a67) | Feb 16, 2025 |
| HP            | Pavilion TS 11              | Notebook    | [7130ad4767](https://linux-hardware.org/?probe=7130ad4767) | Feb 16, 2025 |
| PELADN        | WI-6                        | Desktop     | [7e0e77a962](https://linux-hardware.org/?probe=7e0e77a962) | Feb 16, 2025 |
| Lenovo        | ThinkPad P16s Gen 3 21KS... | Notebook    | [ecd10f4617](https://linux-hardware.org/?probe=ecd10f4617) | Feb 16, 2025 |
| Medion        | MS-7707                     | Desktop     | [6e36b94a5a](https://linux-hardware.org/?probe=6e36b94a5a) | Feb 15, 2025 |
| HP            | mt41                        | Notebook    | [e86336a7aa](https://linux-hardware.org/?probe=e86336a7aa) | Feb 15, 2025 |
| HP            | mt41                        | Notebook    | [c44051311f](https://linux-hardware.org/?probe=c44051311f) | Feb 15, 2025 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [b176c27a0b](https://linux-hardware.org/?probe=b176c27a0b) | Feb 13, 2025 |
| Lenovo        | G770 20089                  | Notebook    | [deba23359c](https://linux-hardware.org/?probe=deba23359c) | Feb 13, 2025 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [80933a92d7](https://linux-hardware.org/?probe=80933a92d7) | Feb 13, 2025 |
| Dell          | 0X9M3X A04                  | Desktop     | [394e03fa0e](https://linux-hardware.org/?probe=394e03fa0e) | Feb 12, 2025 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [0ee5279781](https://linux-hardware.org/?probe=0ee5279781) | Feb 11, 2025 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [e57097c61d](https://linux-hardware.org/?probe=e57097c61d) | Feb 11, 2025 |
| MSI           | B75MA-P45                   | Desktop     | [491c8852e9](https://linux-hardware.org/?probe=491c8852e9) | Feb 10, 2025 |
| Medion        | MS-7707                     | Desktop     | [bd0176f563](https://linux-hardware.org/?probe=bd0176f563) | Feb 09, 2025 |
| Dell          | Vostro 1540                 | Notebook    | [a702d17147](https://linux-hardware.org/?probe=a702d17147) | Feb 08, 2025 |
| Acer          | Predator G3-571             | Notebook    | [b3d30f19c8](https://linux-hardware.org/?probe=b3d30f19c8) | Feb 08, 2025 |
| Acer          | Aspire 5755G                | Notebook    | [99ea4fe230](https://linux-hardware.org/?probe=99ea4fe230) | Feb 06, 2025 |
| Acer          | Aspire E1-572G              | Notebook    | [a4e087418a](https://linux-hardware.org/?probe=a4e087418a) | Feb 06, 2025 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [94bd213028](https://linux-hardware.org/?probe=94bd213028) | Feb 06, 2025 |
| Unknown       | RX16                        | Notebook    | [d18998d57f](https://linux-hardware.org/?probe=d18998d57f) | Feb 05, 2025 |
| Acer          | Aspire AV15-51              | Notebook    | [73d9fa49d9](https://linux-hardware.org/?probe=73d9fa49d9) | Feb 03, 2025 |
| HP            | Notebook                    | Notebook    | [3f6fe250f9](https://linux-hardware.org/?probe=3f6fe250f9) | Feb 03, 2025 |
| Dell          | Precision M6300             | Notebook    | [3d805eb7e5](https://linux-hardware.org/?probe=3d805eb7e5) | Feb 03, 2025 |
| Acer          | Switch SW312-31             | Tablet      | [63d2cbdb2b](https://linux-hardware.org/?probe=63d2cbdb2b) | Feb 03, 2025 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8ae6092e4f](https://linux-hardware.org/?probe=8ae6092e4f) | Feb 03, 2025 |
| Dynabook      | SZ/LSB                      | Notebook    | [e3fd312c56](https://linux-hardware.org/?probe=e3fd312c56) | Feb 02, 2025 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [8dd154f3a9](https://linux-hardware.org/?probe=8dd154f3a9) | Feb 02, 2025 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4f0e755a4a](https://linux-hardware.org/?probe=4f0e755a4a) | Feb 02, 2025 |
| Acer          | Aspire A315-58              | Notebook    | [266aec89b0](https://linux-hardware.org/?probe=266aec89b0) | Feb 02, 2025 |
| Samsung       | 950XED                      | Notebook    | [b65bde59ad](https://linux-hardware.org/?probe=b65bde59ad) | Feb 01, 2025 |
| Samsung       | 950XED                      | Notebook    | [0dfee1d2d9](https://linux-hardware.org/?probe=0dfee1d2d9) | Feb 01, 2025 |
| ASRock        | Z390 Phantom Gaming 4/AC    | Desktop     | [b570c6d606](https://linux-hardware.org/?probe=b570c6d606) | Jan 31, 2025 |
| Foxconn       | ETON                        | Desktop     | [19ce5c04c2](https://linux-hardware.org/?probe=19ce5c04c2) | Jan 31, 2025 |
| Acer          | Aspire A315-51              | Notebook    | [81ad0672bc](https://linux-hardware.org/?probe=81ad0672bc) | Jan 30, 2025 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [70479fdb19](https://linux-hardware.org/?probe=70479fdb19) | Jan 29, 2025 |
| Lenovo        | IdeaCentre K330B            | Desktop     | [9253c594fc](https://linux-hardware.org/?probe=9253c594fc) | Jan 29, 2025 |
| HP            | 15                          | Notebook    | [aa73d28293](https://linux-hardware.org/?probe=aa73d28293) | Jan 29, 2025 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [0a1d93ac75](https://linux-hardware.org/?probe=0a1d93ac75) | Jan 28, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [187d0b2b35](https://linux-hardware.org/?probe=187d0b2b35) | Jan 28, 2025 |
| PELADN        | WI-6                        | Desktop     | [bb87fb47ce](https://linux-hardware.org/?probe=bb87fb47ce) | Jan 26, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [a001b7a5d8](https://linux-hardware.org/?probe=a001b7a5d8) | Jan 25, 2025 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [ec028380c5](https://linux-hardware.org/?probe=ec028380c5) | Jan 25, 2025 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d5242ec865](https://linux-hardware.org/?probe=d5242ec865) | Jan 25, 2025 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [a700fbd0ed](https://linux-hardware.org/?probe=a700fbd0ed) | Jan 25, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [11506df915](https://linux-hardware.org/?probe=11506df915) | Jan 25, 2025 |
| ASUSTek       | GL752VW                     | Notebook    | [f63f2eb417](https://linux-hardware.org/?probe=f63f2eb417) | Jan 25, 2025 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [8aad6328bf](https://linux-hardware.org/?probe=8aad6328bf) | Jan 25, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [8022414bf2](https://linux-hardware.org/?probe=8022414bf2) | Jan 25, 2025 |
| HP            | ProBook 645 G4              | Notebook    | [a6dcb4b4b6](https://linux-hardware.org/?probe=a6dcb4b4b6) | Jan 25, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [c56cc4eefb](https://linux-hardware.org/?probe=c56cc4eefb) | Jan 24, 2025 |
| PELADN        | WI-6                        | Desktop     | [c97c817643](https://linux-hardware.org/?probe=c97c817643) | Jan 23, 2025 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [2b5ea4e149](https://linux-hardware.org/?probe=2b5ea4e149) | Jan 20, 2025 |
| HP            | Pavilion g6                 | Notebook    | [2c86f90e14](https://linux-hardware.org/?probe=2c86f90e14) | Jan 19, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [964ba8e057](https://linux-hardware.org/?probe=964ba8e057) | Jan 19, 2025 |
| HP            | EliteBook 820 G3            | Notebook    | [75db49fa08](https://linux-hardware.org/?probe=75db49fa08) | Jan 19, 2025 |
| HP            | EliteBook 820 G3            | Notebook    | [ac8637b405](https://linux-hardware.org/?probe=ac8637b405) | Jan 19, 2025 |
| HP            | 82B4                        | Desktop     | [b97dc50326](https://linux-hardware.org/?probe=b97dc50326) | Jan 19, 2025 |
| Dell          | 0HHV7N A00                  | Desktop     | [bdf33bafff](https://linux-hardware.org/?probe=bdf33bafff) | Jan 19, 2025 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [6c8a0015ef](https://linux-hardware.org/?probe=6c8a0015ef) | Jan 18, 2025 |
| HP            | 1587h                       | Desktop     | [74cc78a058](https://linux-hardware.org/?probe=74cc78a058) | Jan 18, 2025 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [cb87984b34](https://linux-hardware.org/?probe=cb87984b34) | Jan 18, 2025 |
| Acer          | Aspire 5738                 | Notebook    | [f71cd4f718](https://linux-hardware.org/?probe=f71cd4f718) | Jan 15, 2025 |
| ECS           | H61H2-TI                    | All in one  | [9eafd96f42](https://linux-hardware.org/?probe=9eafd96f42) | Jan 15, 2025 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [2024201637](https://linux-hardware.org/?probe=2024201637) | Jan 15, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [76e836d071](https://linux-hardware.org/?probe=76e836d071) | Jan 15, 2025 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [61a6bb5195](https://linux-hardware.org/?probe=61a6bb5195) | Jan 15, 2025 |
| HP            | Notebook                    | Notebook    | [a2ac96399e](https://linux-hardware.org/?probe=a2ac96399e) | Jan 14, 2025 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [d650a6d175](https://linux-hardware.org/?probe=d650a6d175) | Jan 14, 2025 |
| Medion        | E6214                       | Notebook    | [d28b1f13ab](https://linux-hardware.org/?probe=d28b1f13ab) | Jan 14, 2025 |
| Chuwi         | HeroBox                     | Mini pc     | [0656891c8d](https://linux-hardware.org/?probe=0656891c8d) | Jan 14, 2025 |
| Lenovo        | ThinkPad X250 20CLS3LU00    | Notebook    | [218a63bf4d](https://linux-hardware.org/?probe=218a63bf4d) | Jan 14, 2025 |
| Medion        | E6214                       | Notebook    | [c06acb2f71](https://linux-hardware.org/?probe=c06acb2f71) | Jan 13, 2025 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [fac00c4aaa](https://linux-hardware.org/?probe=fac00c4aaa) | Jan 13, 2025 |
| Acer          | Aspire M3400                | Desktop     | [f6d8d35f2d](https://linux-hardware.org/?probe=f6d8d35f2d) | Jan 13, 2025 |
| HP            | 1587h                       | Desktop     | [512209ee9a](https://linux-hardware.org/?probe=512209ee9a) | Jan 12, 2025 |
| HP            | Pavilion dv8000 (EZ224EA... | Notebook    | [d715c5ba3c](https://linux-hardware.org/?probe=d715c5ba3c) | Jan 12, 2025 |
| HP            | Pavilion dv8000 (EZ224EA... | Notebook    | [3b7191f11a](https://linux-hardware.org/?probe=3b7191f11a) | Jan 12, 2025 |
| Acer          | Aspire X1420                | Desktop     | [80abd0c20b](https://linux-hardware.org/?probe=80abd0c20b) | Jan 12, 2025 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [4b9ab9476e](https://linux-hardware.org/?probe=4b9ab9476e) | Jan 12, 2025 |
| Dell          | Latitude 3540               | Notebook    | [9855bc7a05](https://linux-hardware.org/?probe=9855bc7a05) | Jan 11, 2025 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a8e5651581](https://linux-hardware.org/?probe=a8e5651581) | Jan 11, 2025 |
| Dell          | Latitude E6420              | Notebook    | [bc82dd1a02](https://linux-hardware.org/?probe=bc82dd1a02) | Jan 10, 2025 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [e414e5e76e](https://linux-hardware.org/?probe=e414e5e76e) | Jan 10, 2025 |
| Lenovo        | ThinkPad T540p 20BF005RB... | Notebook    | [b77e1c0a8b](https://linux-hardware.org/?probe=b77e1c0a8b) | Jan 10, 2025 |
| Unknown       | RX16                        | Notebook    | [aabcb7b2e8](https://linux-hardware.org/?probe=aabcb7b2e8) | Jan 10, 2025 |
| Unknown       | RX16                        | Notebook    | [51698e7933](https://linux-hardware.org/?probe=51698e7933) | Jan 10, 2025 |
| Intel         | NUC13ANBi5 M89647-203       | Mini pc     | [0db4ab3434](https://linux-hardware.org/?probe=0db4ab3434) | Jan 08, 2025 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [93d0ec3ead](https://linux-hardware.org/?probe=93d0ec3ead) | Jan 07, 2025 |
| Pegatron      | 2AD5                        | Desktop     | [83c81f49c1](https://linux-hardware.org/?probe=83c81f49c1) | Jan 07, 2025 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | Notebook    | [a33786d633](https://linux-hardware.org/?probe=a33786d633) | Jan 06, 2025 |
| PELADN        | WI-6                        | Desktop     | [4eb39eba20](https://linux-hardware.org/?probe=4eb39eba20) | Jan 06, 2025 |
| Lenovo        | ThinkPad P16v Gen 1 21FC... | Notebook    | [613d717a90](https://linux-hardware.org/?probe=613d717a90) | Jan 06, 2025 |
| Schenker      | XMG EVO (M24)               | Notebook    | [de8c09c39e](https://linux-hardware.org/?probe=de8c09c39e) | Jan 06, 2025 |
| PELADN        | WI-6                        | Desktop     | [537a11ae44](https://linux-hardware.org/?probe=537a11ae44) | Jan 06, 2025 |
| Medion        | E6214                       | Notebook    | [e72344f20c](https://linux-hardware.org/?probe=e72344f20c) | Jan 05, 2025 |
| Medion        | E6214                       | Notebook    | [1abed4b52d](https://linux-hardware.org/?probe=1abed4b52d) | Jan 05, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [2a0e5e8dee](https://linux-hardware.org/?probe=2a0e5e8dee) | Jan 04, 2025 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [d6e8f1ee6c](https://linux-hardware.org/?probe=d6e8f1ee6c) | Jan 04, 2025 |
| HP            | Laptop 15-ef3xxx            | Notebook    | [990ef26285](https://linux-hardware.org/?probe=990ef26285) | Jan 04, 2025 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [88d10a1126](https://linux-hardware.org/?probe=88d10a1126) | Jan 04, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [ba9cefc697](https://linux-hardware.org/?probe=ba9cefc697) | Jan 03, 2025 |
| PELADN        | WI-6                        | Desktop     | [ed403a09ce](https://linux-hardware.org/?probe=ed403a09ce) | Jan 01, 2025 |
| PELADN        | WI-6                        | Desktop     | [9961c80013](https://linux-hardware.org/?probe=9961c80013) | Dec 31, 2024 |
| PELADN        | WI-6                        | Desktop     | [ad75e2844c](https://linux-hardware.org/?probe=ad75e2844c) | Dec 31, 2024 |
| PELADN        | WI-6                        | Desktop     | [a4d452eb65](https://linux-hardware.org/?probe=a4d452eb65) | Dec 31, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [a91c16b9c4](https://linux-hardware.org/?probe=a91c16b9c4) | Dec 31, 2024 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [176c7dc908](https://linux-hardware.org/?probe=176c7dc908) | Dec 29, 2024 |
| Dell          | 0MWYPT A02                  | Desktop     | [3a7c58054c](https://linux-hardware.org/?probe=3a7c58054c) | Dec 29, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f680af729c](https://linux-hardware.org/?probe=f680af729c) | Dec 28, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [0ac54971da](https://linux-hardware.org/?probe=0ac54971da) | Dec 28, 2024 |
| Dell          | Inspiron 5577               | Notebook    | [dabaffa853](https://linux-hardware.org/?probe=dabaffa853) | Dec 25, 2024 |
| Dell          | 0DT021 A02                  | Server      | [5de4c4a538](https://linux-hardware.org/?probe=5de4c4a538) | Dec 23, 2024 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [43e003f874](https://linux-hardware.org/?probe=43e003f874) | Dec 22, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8144311954](https://linux-hardware.org/?probe=8144311954) | Dec 22, 2024 |
| HP            | 2820h                       | Desktop     | [64ccd9e1f2](https://linux-hardware.org/?probe=64ccd9e1f2) | Dec 22, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [edb35a4953](https://linux-hardware.org/?probe=edb35a4953) | Dec 17, 2024 |
| Sony          | VPCM12M1E                   | Notebook    | [eca3984533](https://linux-hardware.org/?probe=eca3984533) | Dec 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [68a46993af](https://linux-hardware.org/?probe=68a46993af) | Dec 15, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [ebcaaa33b0](https://linux-hardware.org/?probe=ebcaaa33b0) | Dec 15, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [787e3a402c](https://linux-hardware.org/?probe=787e3a402c) | Dec 14, 2024 |
| ASUSTek       | N551JK                      | Notebook    | [10b918146d](https://linux-hardware.org/?probe=10b918146d) | Dec 13, 2024 |
| Dell          | Precision 3551              | Notebook    | [598abdb472](https://linux-hardware.org/?probe=598abdb472) | Dec 13, 2024 |
| Acer          | Extensa 5220                | Notebook    | [864e664760](https://linux-hardware.org/?probe=864e664760) | Dec 10, 2024 |
| Lenovo        | ThinkPad E495 20NE0002US    | Notebook    | [690a841928](https://linux-hardware.org/?probe=690a841928) | Dec 10, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | Notebook    | [132e6e2862](https://linux-hardware.org/?probe=132e6e2862) | Dec 09, 2024 |
| Sony          | VPCM12M1E                   | Notebook    | [e7896a9326](https://linux-hardware.org/?probe=e7896a9326) | Dec 08, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [4c7c8cc298](https://linux-hardware.org/?probe=4c7c8cc298) | Dec 08, 2024 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [ecbb2dfb26](https://linux-hardware.org/?probe=ecbb2dfb26) | Dec 07, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [041abf44b0](https://linux-hardware.org/?probe=041abf44b0) | Dec 07, 2024 |
| Lenovo        | ThinkPad X240 20AM001JUS    | Notebook    | [1ac27908e6](https://linux-hardware.org/?probe=1ac27908e6) | Dec 06, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [5fd88a9482](https://linux-hardware.org/?probe=5fd88a9482) | Dec 04, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [8456ee2251](https://linux-hardware.org/?probe=8456ee2251) | Dec 03, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [d085327361](https://linux-hardware.org/?probe=d085327361) | Dec 02, 2024 |
| Lenovo        | ThinkPad T60 2007YQY        | Notebook    | [8d792cc626](https://linux-hardware.org/?probe=8d792cc626) | Dec 02, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [146d9d897a](https://linux-hardware.org/?probe=146d9d897a) | Dec 02, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [5dd8a1851e](https://linux-hardware.org/?probe=5dd8a1851e) | Dec 02, 2024 |
| Insyde        | BayTrail                    | Notebook    | [101b76beeb](https://linux-hardware.org/?probe=101b76beeb) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb5d35bd4b](https://linux-hardware.org/?probe=fb5d35bd4b) | Dec 01, 2024 |
| Lenovo        | ThinkCentre M58p 7220AVG    | Desktop     | [9d47a500ed](https://linux-hardware.org/?probe=9d47a500ed) | Dec 01, 2024 |
| Acer          | Aspire AV15-51              | Notebook    | [c98b2b5898](https://linux-hardware.org/?probe=c98b2b5898) | Dec 01, 2024 |
| Unknown       | Unknown                     | Notebook    | [678e33b8ed](https://linux-hardware.org/?probe=678e33b8ed) | Dec 01, 2024 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [e36fbc49ec](https://linux-hardware.org/?probe=e36fbc49ec) | Dec 01, 2024 |
| Lenovo        | ThinkPad X270 20HN001MUS    | Notebook    | [6c580a86e2](https://linux-hardware.org/?probe=6c580a86e2) | Nov 30, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [245be0630e](https://linux-hardware.org/?probe=245be0630e) | Nov 29, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [ca8808db77](https://linux-hardware.org/?probe=ca8808db77) | Nov 29, 2024 |
| Acer          | Spin SP514-51N              | Convertible | [ff213eb067](https://linux-hardware.org/?probe=ff213eb067) | Nov 29, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [fb2858b084](https://linux-hardware.org/?probe=fb2858b084) | Nov 28, 2024 |
| Lenovo        | ThinkPad neo 14 21DN0009... | Notebook    | [63a0ee38c2](https://linux-hardware.org/?probe=63a0ee38c2) | Nov 27, 2024 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [612c9b02a8](https://linux-hardware.org/?probe=612c9b02a8) | Nov 26, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [7cf2df4c2d](https://linux-hardware.org/?probe=7cf2df4c2d) | Nov 25, 2024 |
| PELADN        | WI-6                        | Desktop     | [deec076d09](https://linux-hardware.org/?probe=deec076d09) | Nov 24, 2024 |
| PELADN        | WI-6                        | Desktop     | [f1daf75b91](https://linux-hardware.org/?probe=f1daf75b91) | Nov 24, 2024 |
| HP            | Laptop 17z-cp300            | Notebook    | [be49e0c290](https://linux-hardware.org/?probe=be49e0c290) | Nov 23, 2024 |
| HP            | Laptop 17z-cp300            | Notebook    | [4090b82a10](https://linux-hardware.org/?probe=4090b82a10) | Nov 23, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [99993b0f3e](https://linux-hardware.org/?probe=99993b0f3e) | Nov 21, 2024 |
| TUXEDO        | InfinityBook S Gen8         | Notebook    | [ac4e85e111](https://linux-hardware.org/?probe=ac4e85e111) | Nov 21, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [c7eb463249](https://linux-hardware.org/?probe=c7eb463249) | Nov 20, 2024 |
| Toshiba       | Satellite P105              | Notebook    | [74a9b7015c](https://linux-hardware.org/?probe=74a9b7015c) | Nov 18, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [a087a2818f](https://linux-hardware.org/?probe=a087a2818f) | Nov 18, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [3f6a95ad11](https://linux-hardware.org/?probe=3f6a95ad11) | Nov 18, 2024 |
| Fujitsu Si... | AMILO Li 2735               | Notebook    | [afbab1e78c](https://linux-hardware.org/?probe=afbab1e78c) | Nov 17, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [da064fe75f](https://linux-hardware.org/?probe=da064fe75f) | Nov 16, 2024 |
| Dell          | 073MMW A03                  | Desktop     | [715ccc808c](https://linux-hardware.org/?probe=715ccc808c) | Nov 16, 2024 |
| Toshiba       | Satellite M100              | Notebook    | [655a407dd2](https://linux-hardware.org/?probe=655a407dd2) | Nov 15, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bd75bc63f7](https://linux-hardware.org/?probe=bd75bc63f7) | Nov 15, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [7ac1792400](https://linux-hardware.org/?probe=7ac1792400) | Nov 14, 2024 |
| Lenovo        | ThinkPad T450 20BUS1110E    | Notebook    | [c6bc9a84e4](https://linux-hardware.org/?probe=c6bc9a84e4) | Nov 14, 2024 |
| Gigabyte      | A520M S2H                   | Desktop     | [53fa642cd5](https://linux-hardware.org/?probe=53fa642cd5) | Nov 13, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [70007038ab](https://linux-hardware.org/?probe=70007038ab) | Nov 13, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [97617e7ac0](https://linux-hardware.org/?probe=97617e7ac0) | Nov 10, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [2aa1d5261d](https://linux-hardware.org/?probe=2aa1d5261d) | Nov 09, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [5ed52c1fdc](https://linux-hardware.org/?probe=5ed52c1fdc) | Nov 09, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [acecc3bec2](https://linux-hardware.org/?probe=acecc3bec2) | Nov 09, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [db16e5b334](https://linux-hardware.org/?probe=db16e5b334) | Nov 09, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [01063d0f9e](https://linux-hardware.org/?probe=01063d0f9e) | Nov 08, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [856f712b05](https://linux-hardware.org/?probe=856f712b05) | Nov 08, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [40be935ed5](https://linux-hardware.org/?probe=40be935ed5) | Nov 06, 2024 |
| Conectar I... | SF20GM7                     | Notebook    | [1c43877e91](https://linux-hardware.org/?probe=1c43877e91) | Nov 06, 2024 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fb25b57170](https://linux-hardware.org/?probe=fb25b57170) | Nov 06, 2024 |
| ASUSTek       | P8H67-M                     | Desktop     | [d7ef318b8e](https://linux-hardware.org/?probe=d7ef318b8e) | Nov 06, 2024 |
| MSI           | Prestige 15 A12SC           | Notebook    | [403f475ebb](https://linux-hardware.org/?probe=403f475ebb) | Nov 03, 2024 |
| ASUSTek       | X450LN                      | Notebook    | [029f170b3e](https://linux-hardware.org/?probe=029f170b3e) | Nov 02, 2024 |
| Conectar I... | SF20GM7                     | Notebook    | [95da818f37](https://linux-hardware.org/?probe=95da818f37) | Nov 02, 2024 |
| Intel         | H110D4-P1                   | Desktop     | [65e304fcef](https://linux-hardware.org/?probe=65e304fcef) | Nov 02, 2024 |
| AZW           | MINI S 10                   | Desktop     | [a76f3d4f56](https://linux-hardware.org/?probe=a76f3d4f56) | Nov 01, 2024 |
| AZW           | MINI S 10                   | Desktop     | [eae99fa9a9](https://linux-hardware.org/?probe=eae99fa9a9) | Nov 01, 2024 |
| HP            | Pavilion dv6000 (RY645EA... | Notebook    | [a9cb45608f](https://linux-hardware.org/?probe=a9cb45608f) | Nov 01, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [159bac7506](https://linux-hardware.org/?probe=159bac7506) | Nov 01, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [bd1050484e](https://linux-hardware.org/?probe=bd1050484e) | Oct 31, 2024 |
| Lenovo        | Unknown                     | Notebook    | [0fdc4e7dac](https://linux-hardware.org/?probe=0fdc4e7dac) | Oct 31, 2024 |
| HP            | 2820h                       | Desktop     | [940082e5de](https://linux-hardware.org/?probe=940082e5de) | Oct 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [cb80f674ac](https://linux-hardware.org/?probe=cb80f674ac) | Oct 30, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [9cc00f993a](https://linux-hardware.org/?probe=9cc00f993a) | Oct 29, 2024 |
| HP            | 1906                        | Desktop     | [2d314c1b57](https://linux-hardware.org/?probe=2d314c1b57) | Oct 28, 2024 |
| Lenovo        | ThinkPad T550 20CK004QUS    | Notebook    | [d4d5181e4f](https://linux-hardware.org/?probe=d4d5181e4f) | Oct 28, 2024 |
| Lenovo        | ThinkPad T550 20CK004QUS    | Notebook    | [c7b77b3285](https://linux-hardware.org/?probe=c7b77b3285) | Oct 27, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [7ae06e5667](https://linux-hardware.org/?probe=7ae06e5667) | Oct 27, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [91631ac2c3](https://linux-hardware.org/?probe=91631ac2c3) | Oct 27, 2024 |
| Dell          | Latitude D820               | Notebook    | [e8052d5ecd](https://linux-hardware.org/?probe=e8052d5ecd) | Oct 26, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [a62e77d2a5](https://linux-hardware.org/?probe=a62e77d2a5) | Oct 26, 2024 |
| Dell          | Latitude D820               | Notebook    | [69777b44d3](https://linux-hardware.org/?probe=69777b44d3) | Oct 25, 2024 |
| Dell          | Latitude E6430              | Notebook    | [7aa1bdef3c](https://linux-hardware.org/?probe=7aa1bdef3c) | Oct 25, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [38e3efc950](https://linux-hardware.org/?probe=38e3efc950) | Oct 24, 2024 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [60f87c4f6d](https://linux-hardware.org/?probe=60f87c4f6d) | Oct 24, 2024 |
| HP            | 2AFB                        | Desktop     | [c7b44337e2](https://linux-hardware.org/?probe=c7b44337e2) | Oct 23, 2024 |
| HP            | 2AFB                        | Desktop     | [cedecd78de](https://linux-hardware.org/?probe=cedecd78de) | Oct 23, 2024 |
| Lenovo        | ThinkPad T400s 28153VG      | Notebook    | [312c0a0fb9](https://linux-hardware.org/?probe=312c0a0fb9) | Oct 22, 2024 |
| Dell          | Latitude 5350               | Notebook    | [58f8fa615d](https://linux-hardware.org/?probe=58f8fa615d) | Oct 21, 2024 |
| Dell          | Latitude 5350               | Notebook    | [b2d8fecadb](https://linux-hardware.org/?probe=b2d8fecadb) | Oct 21, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402FEA... | Convertible | [9477b439b9](https://linux-hardware.org/?probe=9477b439b9) | Oct 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402FEA... | Convertible | [c7769abd75](https://linux-hardware.org/?probe=c7769abd75) | Oct 20, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [ca83f1cc2d](https://linux-hardware.org/?probe=ca83f1cc2d) | Oct 19, 2024 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [50d12895aa](https://linux-hardware.org/?probe=50d12895aa) | Oct 18, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [2c7a8f6c86](https://linux-hardware.org/?probe=2c7a8f6c86) | Oct 17, 2024 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [fed82bdfb6](https://linux-hardware.org/?probe=fed82bdfb6) | Oct 17, 2024 |
| AZW           | GTR V01                     | Mini pc     | [e9502fa314](https://linux-hardware.org/?probe=e9502fa314) | Oct 13, 2024 |
| Toshiba       | Satellite L50D-B            | Notebook    | [a2287ef876](https://linux-hardware.org/?probe=a2287ef876) | Oct 12, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [eb50a1a3c6](https://linux-hardware.org/?probe=eb50a1a3c6) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [475cbc4d32](https://linux-hardware.org/?probe=475cbc4d32) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [26845b5304](https://linux-hardware.org/?probe=26845b5304) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [0531287d03](https://linux-hardware.org/?probe=0531287d03) | Oct 12, 2024 |
| PELADN        | WI-6                        | Desktop     | [ab803d1e89](https://linux-hardware.org/?probe=ab803d1e89) | Oct 12, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [b7da389696](https://linux-hardware.org/?probe=b7da389696) | Oct 12, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [cc8c1d6778](https://linux-hardware.org/?probe=cc8c1d6778) | Oct 11, 2024 |
| Medion        | TJ4125                      | Desktop     | [a371c066fd](https://linux-hardware.org/?probe=a371c066fd) | Oct 11, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | Desktop     | [31774f82cc](https://linux-hardware.org/?probe=31774f82cc) | Oct 11, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402FEA... | Convertible | [6e7991ae99](https://linux-hardware.org/?probe=6e7991ae99) | Oct 11, 2024 |
| Lenovo        | B50-70 80EU                 | Notebook    | [5c0fd8834f](https://linux-hardware.org/?probe=5c0fd8834f) | Oct 11, 2024 |
| Fujitsu       | D3427-A1 S26361-D3427-A1    | Desktop     | [f42bacdfa7](https://linux-hardware.org/?probe=f42bacdfa7) | Oct 11, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [46275a960a](https://linux-hardware.org/?probe=46275a960a) | Oct 11, 2024 |
| AZW           | GTR V01                     | Mini pc     | [df73bf01cd](https://linux-hardware.org/?probe=df73bf01cd) | Oct 10, 2024 |
| Acer          | Aspire E5-521G              | Notebook    | [63755713f4](https://linux-hardware.org/?probe=63755713f4) | Oct 10, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [c1fdcf2050](https://linux-hardware.org/?probe=c1fdcf2050) | Oct 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S0EY00    | Notebook    | [123b9ee07a](https://linux-hardware.org/?probe=123b9ee07a) | Oct 09, 2024 |
| Medion        | TJ4125                      | Desktop     | [24e446e7a7](https://linux-hardware.org/?probe=24e446e7a7) | Oct 08, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [5aadf01aae](https://linux-hardware.org/?probe=5aadf01aae) | Oct 06, 2024 |
| Chuwi         | CoreBook X                  | Notebook    | [c2905b1bd7](https://linux-hardware.org/?probe=c2905b1bd7) | Oct 06, 2024 |
| ASUSTek       | NUC13ANB-M 60AS0040-MB3A... | Mini pc     | [b0bd2a93c2](https://linux-hardware.org/?probe=b0bd2a93c2) | Oct 04, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [f216dafbba](https://linux-hardware.org/?probe=f216dafbba) | Oct 04, 2024 |
| Lenovo        | ThinkPad X61 Tablet 7764... | Notebook    | [4a002c0f20](https://linux-hardware.org/?probe=4a002c0f20) | Oct 04, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [060b69d0b3](https://linux-hardware.org/?probe=060b69d0b3) | Oct 01, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [bc7fdf7279](https://linux-hardware.org/?probe=bc7fdf7279) | Oct 01, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [df3520af77](https://linux-hardware.org/?probe=df3520af77) | Oct 01, 2024 |
| Lenovo        | ThinkPad T400s 28153VG      | Notebook    | [508b12a75b](https://linux-hardware.org/?probe=508b12a75b) | Oct 01, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [1eafc27f9d](https://linux-hardware.org/?probe=1eafc27f9d) | Sep 30, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e9bbaa808d](https://linux-hardware.org/?probe=e9bbaa808d) | Sep 30, 2024 |
| Notebook      | N2x0WU                      | Notebook    | [7e061af782](https://linux-hardware.org/?probe=7e061af782) | Sep 29, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [51fe2ae08f](https://linux-hardware.org/?probe=51fe2ae08f) | Sep 29, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [4559019bac](https://linux-hardware.org/?probe=4559019bac) | Sep 28, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [ce28e0de6c](https://linux-hardware.org/?probe=ce28e0de6c) | Sep 27, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [dc7fdc65d6](https://linux-hardware.org/?probe=dc7fdc65d6) | Sep 26, 2024 |
| ASRock        | A320M-HDV                   | Desktop     | [23c6bbe37a](https://linux-hardware.org/?probe=23c6bbe37a) | Sep 25, 2024 |
| ASUSTek       | ZenBook UX434FAC_UX433FA... | Notebook    | [76bce69bcf](https://linux-hardware.org/?probe=76bce69bcf) | Sep 24, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [4c04674392](https://linux-hardware.org/?probe=4c04674392) | Sep 23, 2024 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [d2315eef29](https://linux-hardware.org/?probe=d2315eef29) | Sep 22, 2024 |
| HP            | Pavilion dv5000 (RG937EA... | Notebook    | [a022208bc5](https://linux-hardware.org/?probe=a022208bc5) | Sep 22, 2024 |
| HP            | Pavilion dv5000 (RG937EA... | Notebook    | [ce20a826eb](https://linux-hardware.org/?probe=ce20a826eb) | Sep 22, 2024 |
| Biostar       | P31-A7                      | Desktop     | [8f249ff212](https://linux-hardware.org/?probe=8f249ff212) | Sep 22, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [10e3fce76a](https://linux-hardware.org/?probe=10e3fce76a) | Sep 21, 2024 |
| HP            | Laptop                      | Notebook    | [fa20696672](https://linux-hardware.org/?probe=fa20696672) | Sep 21, 2024 |
| MSI           | B350 TOMAHAWK               | Desktop     | [f87173b8b2](https://linux-hardware.org/?probe=f87173b8b2) | Sep 20, 2024 |
| Toshiba       | Satellite L745              | Notebook    | [b60f22f240](https://linux-hardware.org/?probe=b60f22f240) | Sep 19, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | Notebook    | [186c21f29f](https://linux-hardware.org/?probe=186c21f29f) | Sep 19, 2024 |
| Dell          | 0T568R A00                  | Desktop     | [1e475fbe85](https://linux-hardware.org/?probe=1e475fbe85) | Sep 18, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [8f68843f40](https://linux-hardware.org/?probe=8f68843f40) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8S9JE0... | Notebook    | [9ef5814db9](https://linux-hardware.org/?probe=9ef5814db9) | Sep 17, 2024 |
| ASUSTek       | V241EA                      | All in one  | [e02555bd07](https://linux-hardware.org/?probe=e02555bd07) | Sep 15, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [af848409fc](https://linux-hardware.org/?probe=af848409fc) | Sep 15, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4815c901f0](https://linux-hardware.org/?probe=4815c901f0) | Sep 15, 2024 |
| Lenovo        | Yoga 500-14IBD 80N4         | Notebook    | [09dda9115e](https://linux-hardware.org/?probe=09dda9115e) | Sep 12, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [60a485333f](https://linux-hardware.org/?probe=60a485333f) | Sep 11, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [47ffb7c0c0](https://linux-hardware.org/?probe=47ffb7c0c0) | Sep 11, 2024 |
| Fujitsu       | LIFEBOOK U7512              | Notebook    | [fefdfd4982](https://linux-hardware.org/?probe=fefdfd4982) | Sep 10, 2024 |
| Dell          | Latitude 5550               | Notebook    | [b409cdf8ab](https://linux-hardware.org/?probe=b409cdf8ab) | Sep 09, 2024 |
| PELADN        | WI-6                        | Desktop     | [1a20712dde](https://linux-hardware.org/?probe=1a20712dde) | Sep 08, 2024 |
| PELADN        | WI-6                        | Desktop     | [c250dba9ae](https://linux-hardware.org/?probe=c250dba9ae) | Sep 07, 2024 |
| Acer          | Spin SP514-51N              | Convertible | [0bf8c23be2](https://linux-hardware.org/?probe=0bf8c23be2) | Sep 07, 2024 |
| Dell          | XPS 15 9510                 | Notebook    | [c36d4de7b4](https://linux-hardware.org/?probe=c36d4de7b4) | Sep 06, 2024 |
| HP            | Pavilion dv2700             | Notebook    | [dae4a490a7](https://linux-hardware.org/?probe=dae4a490a7) | Sep 06, 2024 |
| HP            | Pavilion dv2700             | Notebook    | [3dd25c19fb](https://linux-hardware.org/?probe=3dd25c19fb) | Sep 06, 2024 |
| HP            | Notebook                    | Notebook    | [03bdb73471](https://linux-hardware.org/?probe=03bdb73471) | Sep 05, 2024 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [3e79035d31](https://linux-hardware.org/?probe=3e79035d31) | Sep 03, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [fcdcfb0dc3](https://linux-hardware.org/?probe=fcdcfb0dc3) | Sep 03, 2024 |
| HP            | 829A                        | Mini pc     | [3183148718](https://linux-hardware.org/?probe=3183148718) | Sep 02, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [386d564b97](https://linux-hardware.org/?probe=386d564b97) | Aug 31, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [db7197814c](https://linux-hardware.org/?probe=db7197814c) | Aug 31, 2024 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [f45acc7e20](https://linux-hardware.org/?probe=f45acc7e20) | Aug 31, 2024 |
| MSI           | A68HM GRENADE               | Desktop     | [d823f74970](https://linux-hardware.org/?probe=d823f74970) | Aug 29, 2024 |
| MSI           | A68HM GRENADE               | Desktop     | [10f8a9b965](https://linux-hardware.org/?probe=10f8a9b965) | Aug 29, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a33c000c3c](https://linux-hardware.org/?probe=a33c000c3c) | Aug 29, 2024 |
| ASUSTek       | G11CD-K                     | Desktop     | [97151fcf68](https://linux-hardware.org/?probe=97151fcf68) | Aug 27, 2024 |
| MSI           | GP60 2QE                    | Notebook    | [fe42ba85a4](https://linux-hardware.org/?probe=fe42ba85a4) | Aug 24, 2024 |
| Framework     | Laptop                      | Notebook    | [ec6fd2129b](https://linux-hardware.org/?probe=ec6fd2129b) | Aug 23, 2024 |
| Samsung       | 370E4J/370E4Q               | Notebook    | [5627935947](https://linux-hardware.org/?probe=5627935947) | Aug 21, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [1782abff4d](https://linux-hardware.org/?probe=1782abff4d) | Aug 20, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [29bb2038d4](https://linux-hardware.org/?probe=29bb2038d4) | Aug 20, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [bc5d967ee2](https://linux-hardware.org/?probe=bc5d967ee2) | Aug 20, 2024 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [c771260335](https://linux-hardware.org/?probe=c771260335) | Aug 19, 2024 |
| Acer          | Swift SF315-52G             | Notebook    | [7e4cececee](https://linux-hardware.org/?probe=7e4cececee) | Aug 16, 2024 |
| PELADN        | WI-6                        | Desktop     | [862128760a](https://linux-hardware.org/?probe=862128760a) | Aug 15, 2024 |
| Acer          | Aspire 5732Z                | Notebook    | [399dfa9617](https://linux-hardware.org/?probe=399dfa9617) | Aug 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [1647e0bf63](https://linux-hardware.org/?probe=1647e0bf63) | Aug 14, 2024 |
| Shenzhen M... | DNBIB                       | Desktop     | [b96a88e34c](https://linux-hardware.org/?probe=b96a88e34c) | Aug 13, 2024 |
| PELADN        | WI-6                        | Desktop     | [e23677d993](https://linux-hardware.org/?probe=e23677d993) | Aug 13, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [586288c72b](https://linux-hardware.org/?probe=586288c72b) | Aug 13, 2024 |
| ASRock        | X370 Killer SLI             | Desktop     | [e2b748b24a](https://linux-hardware.org/?probe=e2b748b24a) | Aug 11, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [fd08f80e3b](https://linux-hardware.org/?probe=fd08f80e3b) | Aug 10, 2024 |
| Olidata       | REGLO LIVE                  | Other       | [4fd22e0e76](https://linux-hardware.org/?probe=4fd22e0e76) | Aug 09, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [f351efafd1](https://linux-hardware.org/?probe=f351efafd1) | Aug 08, 2024 |
| Fujitsu       | CELSIUS H7510               | Notebook    | [ece1093c90](https://linux-hardware.org/?probe=ece1093c90) | Aug 08, 2024 |
| HP            | ENVY 15                     | Notebook    | [969779119a](https://linux-hardware.org/?probe=969779119a) | Aug 08, 2024 |
| Olidata       | REGLO LIVE                  | Other       | [335ce4e028](https://linux-hardware.org/?probe=335ce4e028) | Aug 08, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [57987db9cf](https://linux-hardware.org/?probe=57987db9cf) | Aug 08, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [ac8d4298ad](https://linux-hardware.org/?probe=ac8d4298ad) | Aug 06, 2024 |
| HP            | ProBook 4720s               | Notebook    | [f017d85cdb](https://linux-hardware.org/?probe=f017d85cdb) | Aug 06, 2024 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [f65ee4168b](https://linux-hardware.org/?probe=f65ee4168b) | Aug 06, 2024 |
| HP            | x2 210 G2                   | Tablet      | [b4f46406f5](https://linux-hardware.org/?probe=b4f46406f5) | Aug 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [8902556150](https://linux-hardware.org/?probe=8902556150) | Aug 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [da35f8a43c](https://linux-hardware.org/?probe=da35f8a43c) | Aug 04, 2024 |
| GEEKOM        | A7                          | Desktop     | [a642de18b4](https://linux-hardware.org/?probe=a642de18b4) | Aug 03, 2024 |
| GEEKOM        | A7                          | Desktop     | [5e4d479deb](https://linux-hardware.org/?probe=5e4d479deb) | Aug 03, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [802e2c494e](https://linux-hardware.org/?probe=802e2c494e) | Aug 01, 2024 |
| ASUSTek       | X540LA                      | Notebook    | [5db4299943](https://linux-hardware.org/?probe=5db4299943) | Aug 01, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [e822834efe](https://linux-hardware.org/?probe=e822834efe) | Jul 31, 2024 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [59769429e0](https://linux-hardware.org/?probe=59769429e0) | Jul 31, 2024 |
| Lenovo        | ThinkPad T520 4243W63       | Notebook    | [1e8c2ea6ef](https://linux-hardware.org/?probe=1e8c2ea6ef) | Jul 31, 2024 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [a7c539d689](https://linux-hardware.org/?probe=a7c539d689) | Jul 27, 2024 |
| AWOW          | PC BOX                      | Mini pc     | [e529565d58](https://linux-hardware.org/?probe=e529565d58) | Jul 27, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [9a733fe6d3](https://linux-hardware.org/?probe=9a733fe6d3) | Jul 26, 2024 |
| Medion        | TJ4125                      | Desktop     | [8a4a376199](https://linux-hardware.org/?probe=8a4a376199) | Jul 25, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [5261c040c3](https://linux-hardware.org/?probe=5261c040c3) | Jul 25, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [9f6655b549](https://linux-hardware.org/?probe=9f6655b549) | Jul 25, 2024 |
| Unknown       | Unknown                     | Desktop     | [9f21efbdc8](https://linux-hardware.org/?probe=9f21efbdc8) | Jul 24, 2024 |
| Acer          | Aspire E1-531               | Notebook    | [07ce6ddc7c](https://linux-hardware.org/?probe=07ce6ddc7c) | Jul 24, 2024 |
| Lenovo        | 334A NOK                    | Mini pc     | [96bc976697](https://linux-hardware.org/?probe=96bc976697) | Jul 24, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [c031d1b6ab](https://linux-hardware.org/?probe=c031d1b6ab) | Jul 22, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [ae9443b715](https://linux-hardware.org/?probe=ae9443b715) | Jul 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0300a1940](https://linux-hardware.org/?probe=a0300a1940) | Jul 21, 2024 |
| Medion        | TJ4125                      | Desktop     | [50af4fbfc4](https://linux-hardware.org/?probe=50af4fbfc4) | Jul 20, 2024 |
| Toshiba       | TECRA X40-D                 | Notebook    | [cf856c7d5f](https://linux-hardware.org/?probe=cf856c7d5f) | Jul 18, 2024 |
| Intel         | H81                         | Desktop     | [22d5bf41a9](https://linux-hardware.org/?probe=22d5bf41a9) | Jul 17, 2024 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [ae5c5e7f74](https://linux-hardware.org/?probe=ae5c5e7f74) | Jul 16, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [b0be759962](https://linux-hardware.org/?probe=b0be759962) | Jul 16, 2024 |
| ASRock        | H270M Pro4                  | Desktop     | [0098f75d27](https://linux-hardware.org/?probe=0098f75d27) | Jul 16, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [95700ccdf3](https://linux-hardware.org/?probe=95700ccdf3) | Jul 14, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [885ee058e5](https://linux-hardware.org/?probe=885ee058e5) | Jul 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [af6036e896](https://linux-hardware.org/?probe=af6036e896) | Jul 11, 2024 |
| PELADN        | WI-6                        | Desktop     | [5bf72a6fb4](https://linux-hardware.org/?probe=5bf72a6fb4) | Jul 07, 2024 |
| Medion        | TJ4125                      | Desktop     | [d6eea34c91](https://linux-hardware.org/?probe=d6eea34c91) | Jul 06, 2024 |
| PELADN        | WI-6                        | Desktop     | [bf8f9bc3b3](https://linux-hardware.org/?probe=bf8f9bc3b3) | Jul 06, 2024 |
| Medion        | TJ4125                      | Desktop     | [01eef112d6](https://linux-hardware.org/?probe=01eef112d6) | Jul 06, 2024 |
| ASUSTek       | X551CA                      | Notebook    | [c1d5a9a08d](https://linux-hardware.org/?probe=c1d5a9a08d) | Jul 06, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [11c7e97835](https://linux-hardware.org/?probe=11c7e97835) | Jul 05, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [b5c7b17e9f](https://linux-hardware.org/?probe=b5c7b17e9f) | Jul 05, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [873d00bade](https://linux-hardware.org/?probe=873d00bade) | Jul 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [f600a1f5e7](https://linux-hardware.org/?probe=f600a1f5e7) | Jul 04, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [7e78c3299d](https://linux-hardware.org/?probe=7e78c3299d) | Jul 03, 2024 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [6773aae4ed](https://linux-hardware.org/?probe=6773aae4ed) | Jun 30, 2024 |
| Intel         | H61                         | Desktop     | [0373caa5cc](https://linux-hardware.org/?probe=0373caa5cc) | Jun 28, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [4070fa9d3e](https://linux-hardware.org/?probe=4070fa9d3e) | Jun 28, 2024 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [3ef6295470](https://linux-hardware.org/?probe=3ef6295470) | Jun 27, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [e58ec4ab82](https://linux-hardware.org/?probe=e58ec4ab82) | Jun 27, 2024 |
| Dell          | 0T568R A00                  | Desktop     | [be28ff899b](https://linux-hardware.org/?probe=be28ff899b) | Jun 25, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [250352499d](https://linux-hardware.org/?probe=250352499d) | Jun 24, 2024 |
| Lenovo        | ThinkCentre M900 10FLS19... | Notebook    | [75050a724c](https://linux-hardware.org/?probe=75050a724c) | Jun 24, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [3b720bff42](https://linux-hardware.org/?probe=3b720bff42) | Jun 22, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31708d14fb](https://linux-hardware.org/?probe=31708d14fb) | Jun 22, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [2eb9b0bf9b](https://linux-hardware.org/?probe=2eb9b0bf9b) | Jun 22, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [286891ce23](https://linux-hardware.org/?probe=286891ce23) | Jun 22, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [43ddc59145](https://linux-hardware.org/?probe=43ddc59145) | Jun 22, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [b044c0600b](https://linux-hardware.org/?probe=b044c0600b) | Jun 22, 2024 |
| Lenovo        | ThinkCentre M71e 3133A8S    | Desktop     | [e73d8477a0](https://linux-hardware.org/?probe=e73d8477a0) | Jun 21, 2024 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [fcc5c05273](https://linux-hardware.org/?probe=fcc5c05273) | Jun 20, 2024 |
| HP            | 3397                        | Desktop     | [6156808fc9](https://linux-hardware.org/?probe=6156808fc9) | Jun 20, 2024 |
| HP            | 3397                        | Desktop     | [28f359e68a](https://linux-hardware.org/?probe=28f359e68a) | Jun 20, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [86fb4cb7e8](https://linux-hardware.org/?probe=86fb4cb7e8) | Jun 18, 2024 |
| ASUSTek       | P7P55 LX                    | Desktop     | [a8754caf68](https://linux-hardware.org/?probe=a8754caf68) | Jun 17, 2024 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [cb0f2121d5](https://linux-hardware.org/?probe=cb0f2121d5) | Jun 14, 2024 |
| Shenzhen M... | F7BRC                       | Desktop     | [c5fa0bb59b](https://linux-hardware.org/?probe=c5fa0bb59b) | Jun 10, 2024 |
| HP            | Pavilion dv6                | Notebook    | [0010ed731f](https://linux-hardware.org/?probe=0010ed731f) | Jun 08, 2024 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [3ef8d7d35a](https://linux-hardware.org/?probe=3ef8d7d35a) | Jun 08, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [7bd7c51885](https://linux-hardware.org/?probe=7bd7c51885) | Jun 07, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [55b98015cb](https://linux-hardware.org/?probe=55b98015cb) | Jun 06, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [bec9de1440](https://linux-hardware.org/?probe=bec9de1440) | Jun 06, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [d82bb98114](https://linux-hardware.org/?probe=d82bb98114) | Jun 06, 2024 |
| ASUSTek       | A7F                         | Notebook    | [d2c993325b](https://linux-hardware.org/?probe=d2c993325b) | Jun 05, 2024 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7c63ac7810](https://linux-hardware.org/?probe=7c63ac7810) | Jun 04, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [0707d81b82](https://linux-hardware.org/?probe=0707d81b82) | Jun 03, 2024 |
| TENKU         | Mobile S10                  | Convertible | [e9016f6223](https://linux-hardware.org/?probe=e9016f6223) | Jun 02, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [187d6649ae](https://linux-hardware.org/?probe=187d6649ae) | Jun 02, 2024 |
| Medion        | E6214                       | Notebook    | [a67672f4f1](https://linux-hardware.org/?probe=a67672f4f1) | Jun 01, 2024 |
| Medion        | E6214                       | Notebook    | [3e6d7287eb](https://linux-hardware.org/?probe=3e6d7287eb) | Jun 01, 2024 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [b56aaa479c](https://linux-hardware.org/?probe=b56aaa479c) | May 28, 2024 |
| ASUSTek       | 1201N                       | Notebook    | [6466d5ce59](https://linux-hardware.org/?probe=6466d5ce59) | May 27, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [02fb324096](https://linux-hardware.org/?probe=02fb324096) | May 23, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [7c07d6eceb](https://linux-hardware.org/?probe=7c07d6eceb) | May 23, 2024 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ee19bbcc37](https://linux-hardware.org/?probe=ee19bbcc37) | May 19, 2024 |
| Dell          | Latitude 5590               | Notebook    | [4b5982bff4](https://linux-hardware.org/?probe=4b5982bff4) | May 19, 2024 |
| Notebook      | W65_67SZ                    | Notebook    | [47bb1315ce](https://linux-hardware.org/?probe=47bb1315ce) | May 19, 2024 |
| ASUSTek       | P8H61-M                     | Desktop     | [451e286c21](https://linux-hardware.org/?probe=451e286c21) | May 18, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [2736095341](https://linux-hardware.org/?probe=2736095341) | May 18, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [9ae2bfab73](https://linux-hardware.org/?probe=9ae2bfab73) | May 18, 2024 |
| ASUSTek       | 900                         | Notebook    | [770a3f0d8d](https://linux-hardware.org/?probe=770a3f0d8d) | May 17, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f0f7c823e6](https://linux-hardware.org/?probe=f0f7c823e6) | May 17, 2024 |
| Notebook      | P65xHP                      | Notebook    | [809f680e12](https://linux-hardware.org/?probe=809f680e12) | May 16, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [57e0f5eb29](https://linux-hardware.org/?probe=57e0f5eb29) | May 13, 2024 |
| Samsung       | RV415/RV515                 | Notebook    | [9ae57537b3](https://linux-hardware.org/?probe=9ae57537b3) | May 13, 2024 |
| PELADN        | WI-6                        | Desktop     | [4cabf19872](https://linux-hardware.org/?probe=4cabf19872) | May 13, 2024 |
| Dell          | Latitude E6510              | Notebook    | [c1d8e78181](https://linux-hardware.org/?probe=c1d8e78181) | May 12, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [180ba77304](https://linux-hardware.org/?probe=180ba77304) | May 12, 2024 |
| Notebook      | W250EGQ / W270EGQ           | Notebook    | [50c20659c5](https://linux-hardware.org/?probe=50c20659c5) | May 11, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [1f7c62ca20](https://linux-hardware.org/?probe=1f7c62ca20) | May 11, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [0a49b531a8](https://linux-hardware.org/?probe=0a49b531a8) | May 10, 2024 |
| Maibenben     | Perfectum Series            | Notebook    | [d6d3c7760c](https://linux-hardware.org/?probe=d6d3c7760c) | May 10, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [2f7ab2437f](https://linux-hardware.org/?probe=2f7ab2437f) | May 09, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [0a6d61d9f6](https://linux-hardware.org/?probe=0a6d61d9f6) | May 09, 2024 |
| GEEKOM        | Mini Air12                  | Server      | [c02c2be45e](https://linux-hardware.org/?probe=c02c2be45e) | May 08, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [fc4db570af](https://linux-hardware.org/?probe=fc4db570af) | May 08, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [cf126cd087](https://linux-hardware.org/?probe=cf126cd087) | May 08, 2024 |
| PELADN        | WI-6                        | Desktop     | [73069ab9f5](https://linux-hardware.org/?probe=73069ab9f5) | May 07, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [9176ad5eb1](https://linux-hardware.org/?probe=9176ad5eb1) | May 04, 2024 |
| Dell          | 0V0D45 A01                  | All in one  | [8ac266bc9b](https://linux-hardware.org/?probe=8ac266bc9b) | May 03, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2837d61bc4](https://linux-hardware.org/?probe=2837d61bc4) | May 03, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [9d375acdb0](https://linux-hardware.org/?probe=9d375acdb0) | May 03, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [1ae07ba421](https://linux-hardware.org/?probe=1ae07ba421) | May 01, 2024 |
| HP            | Compaq 6730s                | Notebook    | [ab6d479788](https://linux-hardware.org/?probe=ab6d479788) | May 01, 2024 |
| ASUSTek       | H81-PLUS                    | Desktop     | [efe7c01899](https://linux-hardware.org/?probe=efe7c01899) | May 01, 2024 |
| ASUSTek       | H81-PLUS                    | Desktop     | [512660cdbc](https://linux-hardware.org/?probe=512660cdbc) | May 01, 2024 |
| Unknown       | Unknown                     | Notebook    | [a677f40065](https://linux-hardware.org/?probe=a677f40065) | Apr 30, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [5f5030ef83](https://linux-hardware.org/?probe=5f5030ef83) | Apr 29, 2024 |
| Medion        | TJ4125                      | Desktop     | [5107c56945](https://linux-hardware.org/?probe=5107c56945) | Apr 29, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [a52ce5dea5](https://linux-hardware.org/?probe=a52ce5dea5) | Apr 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [bc0e0ae6b8](https://linux-hardware.org/?probe=bc0e0ae6b8) | Apr 25, 2024 |
| ASUSTek       | X541UVK                     | Notebook    | [422fd329a8](https://linux-hardware.org/?probe=422fd329a8) | Apr 25, 2024 |
| Pegatron      | 2A94                        | Desktop     | [3673d4e290](https://linux-hardware.org/?probe=3673d4e290) | Apr 25, 2024 |
| Lenovo        | V15 G4 IAH 83FS             | Notebook    | [b922fc6d5e](https://linux-hardware.org/?probe=b922fc6d5e) | Apr 24, 2024 |
| Acer          | TravelMate 4070             | Notebook    | [99e797eb28](https://linux-hardware.org/?probe=99e797eb28) | Apr 23, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b7a4824162](https://linux-hardware.org/?probe=b7a4824162) | Apr 23, 2024 |
| HP            | 8876 11                     | Desktop     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| AMI           | Intel                       | Desktop     | [7f5a03f6a3](https://linux-hardware.org/?probe=7f5a03f6a3) | Apr 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [2be166cff9](https://linux-hardware.org/?probe=2be166cff9) | Apr 22, 2024 |
| Unknown       | Unknown                     | Desktop     | [9bce7f48fb](https://linux-hardware.org/?probe=9bce7f48fb) | Apr 22, 2024 |
| Packard Be... | EasyNote_MX45               | Notebook    | [2af5864c3c](https://linux-hardware.org/?probe=2af5864c3c) | Apr 22, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [46d23f3585](https://linux-hardware.org/?probe=46d23f3585) | Apr 21, 2024 |
| HP            | 1495                        | Desktop     | [0eb85fb716](https://linux-hardware.org/?probe=0eb85fb716) | Apr 20, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [4aabe77962](https://linux-hardware.org/?probe=4aabe77962) | Apr 20, 2024 |
| HP            | 1495                        | Desktop     | [f3b383fe91](https://linux-hardware.org/?probe=f3b383fe91) | Apr 20, 2024 |
| Acer          | Aspire E1-571G              | Notebook    | [cfb1f06070](https://linux-hardware.org/?probe=cfb1f06070) | Apr 20, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [703372f7ac](https://linux-hardware.org/?probe=703372f7ac) | Apr 19, 2024 |
| Medion        | E6214                       | Notebook    | [fef41424b0](https://linux-hardware.org/?probe=fef41424b0) | Apr 19, 2024 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [028ee7ca9d](https://linux-hardware.org/?probe=028ee7ca9d) | Apr 19, 2024 |
| Medion        | E6214                       | Notebook    | [f6e648f8a4](https://linux-hardware.org/?probe=f6e648f8a4) | Apr 19, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7cfe6d651b](https://linux-hardware.org/?probe=7cfe6d651b) | Apr 18, 2024 |
| Medion        | TJ4125                      | Desktop     | [283e08c36b](https://linux-hardware.org/?probe=283e08c36b) | Apr 18, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [0bf4de97cf](https://linux-hardware.org/?probe=0bf4de97cf) | Apr 17, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [39e93654ec](https://linux-hardware.org/?probe=39e93654ec) | Apr 13, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [562a3aa8fe](https://linux-hardware.org/?probe=562a3aa8fe) | Apr 13, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a996f7b2e9](https://linux-hardware.org/?probe=a996f7b2e9) | Apr 12, 2024 |
| GMKtec        | M5 Pro                      | Mini pc     | [1545f1ad9f](https://linux-hardware.org/?probe=1545f1ad9f) | Apr 11, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [d3be5bf008](https://linux-hardware.org/?probe=d3be5bf008) | Apr 10, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [cbc8162b5a](https://linux-hardware.org/?probe=cbc8162b5a) | Apr 10, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3d748511c8](https://linux-hardware.org/?probe=3d748511c8) | Apr 08, 2024 |
| ASUSTek       | G752VSK                     | Notebook    | [49116bb834](https://linux-hardware.org/?probe=49116bb834) | Apr 08, 2024 |
| Dell          | Latitude E7250              | Notebook    | [3979d6a4a1](https://linux-hardware.org/?probe=3979d6a4a1) | Apr 07, 2024 |
| PELADN        | WI-6                        | Desktop     | [16b9fe150d](https://linux-hardware.org/?probe=16b9fe150d) | Apr 07, 2024 |
| Google        | Voxel                       | Notebook    | [5242e65363](https://linux-hardware.org/?probe=5242e65363) | Apr 06, 2024 |
| Medion        | E6214                       | Notebook    | [5ddeb441b9](https://linux-hardware.org/?probe=5ddeb441b9) | Apr 06, 2024 |
| Medion        | E6214                       | Notebook    | [20d0838443](https://linux-hardware.org/?probe=20d0838443) | Apr 06, 2024 |
| PELADN        | WI-6                        | Desktop     | [e3e158c12c](https://linux-hardware.org/?probe=e3e158c12c) | Apr 05, 2024 |
| Medion        | TJ4125                      | Desktop     | [9d159ef9de](https://linux-hardware.org/?probe=9d159ef9de) | Apr 04, 2024 |
| Medion        | TJ4125                      | Desktop     | [3133554055](https://linux-hardware.org/?probe=3133554055) | Apr 04, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [e075d81601](https://linux-hardware.org/?probe=e075d81601) | Apr 04, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [43a27413f2](https://linux-hardware.org/?probe=43a27413f2) | Mar 31, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [1dd2fa7d48](https://linux-hardware.org/?probe=1dd2fa7d48) | Mar 31, 2024 |
| HP            | Pavilion 15                 | Notebook    | [69bc35a5b1](https://linux-hardware.org/?probe=69bc35a5b1) | Mar 30, 2024 |
| HP            | Pavilion 15                 | Notebook    | [69293f7635](https://linux-hardware.org/?probe=69293f7635) | Mar 30, 2024 |
| Quanta        | 2AC7 011                    | Desktop     | [ee7988e621](https://linux-hardware.org/?probe=ee7988e621) | Mar 29, 2024 |
| Lenovo        | V15 G4 IAH 83FS             | Notebook    | [ec668db660](https://linux-hardware.org/?probe=ec668db660) | Mar 28, 2024 |
| ASRock        | J3455-ITX                   | Desktop     | [a0f0f8fc52](https://linux-hardware.org/?probe=a0f0f8fc52) | Mar 26, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [14cbf1cf7d](https://linux-hardware.org/?probe=14cbf1cf7d) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [0cee79fd45](https://linux-hardware.org/?probe=0cee79fd45) | Mar 24, 2024 |
| PELADN        | WI-6                        | Desktop     | [76b4088a9e](https://linux-hardware.org/?probe=76b4088a9e) | Mar 23, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [e88e880d21](https://linux-hardware.org/?probe=e88e880d21) | Mar 23, 2024 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [153847bfc0](https://linux-hardware.org/?probe=153847bfc0) | Mar 23, 2024 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [c5e27f31fa](https://linux-hardware.org/?probe=c5e27f31fa) | Mar 23, 2024 |
| HP            | ProBook 470 G0              | Notebook    | [7947b2c132](https://linux-hardware.org/?probe=7947b2c132) | Mar 22, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [07889f98fc](https://linux-hardware.org/?probe=07889f98fc) | Mar 22, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [dfa8ff45b7](https://linux-hardware.org/?probe=dfa8ff45b7) | Mar 21, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [5c0de1313b](https://linux-hardware.org/?probe=5c0de1313b) | Mar 21, 2024 |
| Lenovo        | IdeaPad Pro 5 16IRH8 83A... | Notebook    | [a4c78f511d](https://linux-hardware.org/?probe=a4c78f511d) | Mar 21, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [3d42d3e1f9](https://linux-hardware.org/?probe=3d42d3e1f9) | Mar 19, 2024 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [230ed44a0f](https://linux-hardware.org/?probe=230ed44a0f) | Mar 18, 2024 |
| Dell          | Inspiron 3585               | Notebook    | [2378788f88](https://linux-hardware.org/?probe=2378788f88) | Mar 18, 2024 |
| Lenovo        | IdeaPad U160 08946JG        | Notebook    | [62adedc3dc](https://linux-hardware.org/?probe=62adedc3dc) | Mar 17, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [d1f4d3e711](https://linux-hardware.org/?probe=d1f4d3e711) | Mar 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [25c1a0e7d3](https://linux-hardware.org/?probe=25c1a0e7d3) | Mar 16, 2024 |
| ASUSTek       | T103HAF                     | Tablet      | [cae2c37148](https://linux-hardware.org/?probe=cae2c37148) | Mar 14, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e5bf526b80](https://linux-hardware.org/?probe=e5bf526b80) | Mar 13, 2024 |
| Lenovo        | IdeaPad U160 08946JG        | Notebook    | [0d6bea90e0](https://linux-hardware.org/?probe=0d6bea90e0) | Mar 11, 2024 |
| Unknown       | G31T-M7                     | Desktop     | [1bf4ded8e3](https://linux-hardware.org/?probe=1bf4ded8e3) | Mar 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1dda71290f](https://linux-hardware.org/?probe=1dda71290f) | Mar 08, 2024 |
| ASUSTek       | M3702WFA                    | All in one  | [9d1db96cef](https://linux-hardware.org/?probe=9d1db96cef) | Mar 07, 2024 |
| Monster       | TULPAR T7 V20.3             | Notebook    | [df8b4e385a](https://linux-hardware.org/?probe=df8b4e385a) | Mar 06, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [b4f3b9c879](https://linux-hardware.org/?probe=b4f3b9c879) | Mar 06, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5f7a226ed8](https://linux-hardware.org/?probe=5f7a226ed8) | Mar 06, 2024 |
| Acer          | Aspire 5570Z                | Notebook    | [16e46c8657](https://linux-hardware.org/?probe=16e46c8657) | Mar 05, 2024 |
| Acer          | Aspire 5570Z                | Notebook    | [4471c4987a](https://linux-hardware.org/?probe=4471c4987a) | Mar 05, 2024 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [fc21a2b0e2](https://linux-hardware.org/?probe=fc21a2b0e2) | Mar 04, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [08453be623](https://linux-hardware.org/?probe=08453be623) | Feb 28, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [8bb6693e8a](https://linux-hardware.org/?probe=8bb6693e8a) | Feb 28, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [d67a754532](https://linux-hardware.org/?probe=d67a754532) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S2CB00    | Notebook    | [eff836bcb1](https://linux-hardware.org/?probe=eff836bcb1) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S2CB00    | Notebook    | [a78eb227db](https://linux-hardware.org/?probe=a78eb227db) | Feb 26, 2024 |
| Dell          | Vostro 1510                 | Notebook    | [c2b1496073](https://linux-hardware.org/?probe=c2b1496073) | Feb 24, 2024 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9f6a95d5b4](https://linux-hardware.org/?probe=9f6a95d5b4) | Feb 23, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [dad4fdcceb](https://linux-hardware.org/?probe=dad4fdcceb) | Feb 22, 2024 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | Notebook    | [309bc99f27](https://linux-hardware.org/?probe=309bc99f27) | Feb 22, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [6bbe163c4b](https://linux-hardware.org/?probe=6bbe163c4b) | Feb 21, 2024 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [954a5c5822](https://linux-hardware.org/?probe=954a5c5822) | Feb 20, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [54eb218a18](https://linux-hardware.org/?probe=54eb218a18) | Feb 20, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [383bb58584](https://linux-hardware.org/?probe=383bb58584) | Feb 20, 2024 |
| Lenovo        | ThinkPad E470 20H2S00500    | Notebook    | [3c24c9be66](https://linux-hardware.org/?probe=3c24c9be66) | Feb 20, 2024 |
| MSI           | Z370-A PRO                  | Desktop     | [3715fac015](https://linux-hardware.org/?probe=3715fac015) | Feb 20, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [29958a239f](https://linux-hardware.org/?probe=29958a239f) | Feb 19, 2024 |
| MSI           | Z170A SLI PLUS              | Desktop     | [5dff40d28c](https://linux-hardware.org/?probe=5dff40d28c) | Feb 19, 2024 |
| ASRock        | B760M Pro RS/D4             | Desktop     | [f0f36877ea](https://linux-hardware.org/?probe=f0f36877ea) | Feb 19, 2024 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [5cc2223e2a](https://linux-hardware.org/?probe=5cc2223e2a) | Feb 18, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [0867cf376f](https://linux-hardware.org/?probe=0867cf376f) | Feb 18, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [741292eb40](https://linux-hardware.org/?probe=741292eb40) | Feb 18, 2024 |
| HP            | Pavilion 15                 | Notebook    | [55af31fd66](https://linux-hardware.org/?probe=55af31fd66) | Feb 17, 2024 |
| Gigabyte      | B560M D3H                   | Desktop     | [dd40636963](https://linux-hardware.org/?probe=dd40636963) | Feb 17, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE_6/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.1.0-12-amd64         | 112       | 12.06%  |
| 6.1.0-37-amd64         | 79        | 8.5%    |
| 6.1.0-13-amd64         | 68        | 7.32%   |
| 6.1.0-17-amd64         | 48        | 5.17%   |
| 6.1.0-18-amd64         | 42        | 4.52%   |
| 6.1.0-28-amd64         | 38        | 4.09%   |
| 6.1.0-31-amd64         | 37        | 3.98%   |
| 6.1.0-23-amd64         | 35        | 3.77%   |
| 6.1.0-26-amd64         | 33        | 3.55%   |
| 6.1.0-21-amd64         | 32        | 3.44%   |
| 6.1.0-34-amd64         | 30        | 3.23%   |
| 6.1.0-30-amd64         | 30        | 3.23%   |
| 6.1.0-40-amd64         | 29        | 3.12%   |
| 6.1.0-25-amd64         | 27        | 2.91%   |
| 6.1.0-32-amd64         | 26        | 2.8%    |
| 6.1.0-38-amd64         | 22        | 2.37%   |
| 6.1.0-20-amd64         | 21        | 2.26%   |
| 6.1.0-16-amd64         | 20        | 2.15%   |
| 6.1.0-33-amd64         | 19        | 2.05%   |
| 6.1.0-12-686           | 14        | 1.51%   |
| 6.1.0-39-amd64         | 11        | 1.18%   |
| 6.1.0-27-amd64         | 10        | 1.08%   |
| 6.1.0-22-amd64         | 9         | 0.97%   |
| 6.1.0-29-amd64         | 8         | 0.86%   |
| 6.1.0-15-amd64         | 7         | 0.75%   |
| 6.12.12+bpo-amd64      | 6         | 0.65%   |
| 6.12.22+bpo-amd64      | 5         | 0.54%   |
| 6.1.0-41-amd64         | 5         | 0.54%   |
| 6.12.9+bpo-amd64       | 4         | 0.43%   |
| 6.10.11+bpo-amd64      | 4         | 0.43%   |
| 6.1.0-14-amd64         | 4         | 0.43%   |
| 6.5.0-0.deb12.4-amd64  | 3         | 0.32%   |
| 6.14.0-061400-generic  | 3         | 0.32%   |
| 6.1.0-35-amd64         | 3         | 0.32%   |
| 6.1.0-28-686           | 3         | 0.32%   |
| 6.1.0-27-686           | 3         | 0.32%   |
| 6.1.0-20-686           | 3         | 0.32%   |
| 6.1.0-18-686           | 3         | 0.32%   |
| 6.9.7+bpo-amd64        | 2         | 0.22%   |
| 6.9.5-1-liquorix-amd64 | 2         | 0.22%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 750       | 91.13%  |
| 6.12.12 | 8         | 0.97%   |
| 6.5.0   | 5         | 0.61%   |
| 6.12.9  | 5         | 0.61%   |
| 6.12.22 | 5         | 0.61%   |
| 6.14.0  | 4         | 0.49%   |
| 6.10.11 | 4         | 0.49%   |
| 6.9.7   | 3         | 0.36%   |
| 6.6.13  | 3         | 0.36%   |
| 6.9.5   | 2         | 0.24%   |
| 6.12.43 | 2         | 0.24%   |
| 6.12.33 | 2         | 0.24%   |
| 6.12.32 | 2         | 0.24%   |
| 6.11.5  | 2         | 0.24%   |
| 6.11.10 | 2         | 0.24%   |
| 6.10.6  | 2         | 0.24%   |
| 5.10.0  | 2         | 0.24%   |
| 6.9.10  | 1         | 0.12%   |
| 6.7.12  | 1         | 0.12%   |
| 6.7.10  | 1         | 0.12%   |
| 6.6.2   | 1         | 0.12%   |
| 6.6.15  | 1         | 0.12%   |
| 6.6.11  | 1         | 0.12%   |
| 6.6.10  | 1         | 0.12%   |
| 6.5.11  | 1         | 0.12%   |
| 6.5.10  | 1         | 0.12%   |
| 6.4.0   | 1         | 0.12%   |
| 6.16.7  | 1         | 0.12%   |
| 6.15.4  | 1         | 0.12%   |
| 6.14.2  | 1         | 0.12%   |
| 6.13.8  | 1         | 0.12%   |
| 6.12.6  | 1         | 0.12%   |
| 6.12.57 | 1         | 0.12%   |
| 6.12.28 | 1         | 0.12%   |
| 6.12.10 | 1         | 0.12%   |
| 6.10.5  | 1         | 0.12%   |
| 6.1.139 | 1         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 750       | 91.46%  |
| 6.12    | 27        | 3.29%   |
| 6.6     | 7         | 0.85%   |
| 6.10    | 7         | 0.85%   |
| 6.9     | 6         | 0.73%   |
| 6.5     | 6         | 0.73%   |
| 6.14    | 5         | 0.61%   |
| 6.11    | 4         | 0.49%   |
| 6.7     | 2         | 0.24%   |
| 5.10    | 2         | 0.24%   |
| 6.4     | 1         | 0.12%   |
| 6.16    | 1         | 0.12%   |
| 6.15    | 1         | 0.12%   |
| 6.13    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 771       | 94.83%  |
| i686   | 42        | 5.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 762       | 92.81%  |
| Cinnamon   | 16        | 1.95%   |
| Unknown    | 13        | 1.58%   |
| XFCE       | 9         | 1.1%    |
| KDE5       | 8         | 0.97%   |
| MATE       | 5         | 0.61%   |
| LXDE       | 4         | 0.49%   |
| GNOME      | 4         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 797       | 97.91%  |
| Wayland | 13        | 1.6%    |
| Tty     | 4         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 493       | 60.2%   |
| Unknown | 319       | 38.95%  |
| GDM3    | 5         | 0.61%   |
| SDDM    | 2         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 284       | 34.8%   |
| de_DE   | 127       | 15.56%  |
| it_IT   | 104       | 12.75%  |
| en_GB   | 55        | 6.74%   |
| fr_FR   | 45        | 5.51%   |
| ru_RU   | 23        | 2.82%   |
| pt_BR   | 22        | 2.7%    |
| es_ES   | 13        | 1.59%   |
| Unknown | 13        | 1.59%   |
| pl_PL   | 11        | 1.35%   |
| nl_NL   | 8         | 0.98%   |
| en_AU   | 8         | 0.98%   |
| cs_CZ   | 8         | 0.98%   |
| en_CA   | 7         | 0.86%   |
| ja_JP   | 6         | 0.74%   |
| sv_SE   | 5         | 0.61%   |
| es_AR   | 5         | 0.61%   |
| tr_TR   | 4         | 0.49%   |
| nl_BE   | 4         | 0.49%   |
| hu_HU   | 4         | 0.49%   |
| fr_CA   | 4         | 0.49%   |
| fi_FI   | 3         | 0.37%   |
| es_UY   | 3         | 0.37%   |
| en_NZ   | 3         | 0.37%   |
| de_CH   | 3         | 0.37%   |
| de_AT   | 3         | 0.37%   |
| ro_RO   | 2         | 0.25%   |
| hr_HR   | 2         | 0.25%   |
| fr_BE   | 2         | 0.25%   |
| es_PA   | 2         | 0.25%   |
| es_MX   | 2         | 0.25%   |
| es_HN   | 2         | 0.25%   |
| es_DO   | 2         | 0.25%   |
| es_CR   | 2         | 0.25%   |
| es_BO   | 2         | 0.25%   |
| en_IN   | 2         | 0.25%   |
| en_DK   | 2         | 0.25%   |
| zh_CN   | 1         | 0.12%   |
| sr_RS   | 1         | 0.12%   |
| pt_PT   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 547       | 66.71%  |
| BIOS | 273       | 33.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 706       | 86.2%   |
| Overlay | 47        | 5.74%   |
| Btrfs   | 37        | 4.52%   |
| Tmpfs   | 27        | 3.3%    |
| Zfs     | 1         | 0.12%   |
| Xfs     | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 390       | 47.74%  |
| Unknown | 305       | 37.33%  |
| MBR     | 122       | 14.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 729       | 89.23%  |
| Yes       | 88        | 10.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 639       | 78.12%  |
| Yes       | 179       | 21.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 146       | 17.98%  |
| Lenovo                               | 122       | 15.02%  |
| Hewlett-Packard                      | 115       | 14.16%  |
| Dell                                 | 82        | 10.1%   |
| MSI                                  | 41        | 5.05%   |
| Acer                                 | 41        | 5.05%   |
| Apple                                | 38        | 4.68%   |
| Gigabyte Technology                  | 37        | 4.56%   |
| ASRock                               | 28        | 3.45%   |
| Fujitsu                              | 22        | 2.71%   |
| Toshiba                              | 11        | 1.35%   |
| Intel                                | 11        | 1.35%   |
| Unknown                              | 9         | 1.11%   |
| Samsung Electronics                  | 7         | 0.86%   |
| HUAWEI                               | 6         | 0.74%   |
| GEEKOM                               | 6         | 0.74%   |
| Notebook                             | 5         | 0.62%   |
| AZW                                  | 5         | 0.62%   |
| Sony                                 | 4         | 0.49%   |
| Shenzhen Meigao Electronic Equipment | 4         | 0.49%   |
| Medion                               | 4         | 0.49%   |
| Fujitsu Siemens                      | 3         | 0.37%   |
| ECS                                  | 3         | 0.37%   |
| Chuwi                                | 3         | 0.37%   |
| TUXEDO                               | 2         | 0.25%   |
| PELADN                               | 2         | 0.25%   |
| Pegatron                             | 2         | 0.25%   |
| Packard Bell                         | 2         | 0.25%   |
| Microsoft                            | 2         | 0.25%   |
| Inventec                             | 2         | 0.25%   |
| Google                               | 2         | 0.25%   |
| GMKtec                               | 2         | 0.25%   |
| Framework                            | 2         | 0.25%   |
| Alienware                            | 2         | 0.25%   |
| WeiBu                                | 1         | 0.12%   |
| Valve                                | 1         | 0.12%   |
| VALE                                 | 1         | 0.12%   |
| Trigkey                              | 1         | 0.12%   |
| TongFang                             | 1         | 0.12%   |
| Timi                                 | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown                                             | 11        | 1.35%   |
| ASUS All Series                                     | 5         | 0.62%   |
| HP Notebook                                         | 4         | 0.49%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA            | 4         | 0.49%   |
| Apple MacBookAir7,2                                 | 4         | 0.49%   |
| HP Pavilion 15                                      | 3         | 0.37%   |
| HP Laptop 15-dw1xxx                                 | 3         | 0.37%   |
| Dell OptiPlex 3020                                  | 3         | 0.37%   |
| ASRock A320M-HDV R4.0                               | 3         | 0.37%   |
| Apple MacBookAir6,2                                 | 3         | 0.37%   |
| Apple iMac8,1                                       | 3         | 0.37%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 2         | 0.25%   |
| PELADN WI-6                                         | 2         | 0.25%   |
| Notebook W65_67SZ                                   | 2         | 0.25%   |
| MSI MS-7D91                                         | 2         | 0.25%   |
| MSI MS-7C95                                         | 2         | 0.25%   |
| MSI MS-7C56                                         | 2         | 0.25%   |
| MSI MS-7798                                         | 2         | 0.25%   |
| Lenovo ThinkCentre M93p 10A8S4B200                  | 2         | 0.25%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU                   | 2         | 0.25%   |
| Lenovo IdeaPad 3 15IML05 82BS                       | 2         | 0.25%   |
| HUAWEI NBLK-WAX9X                                   | 2         | 0.25%   |
| HUAWEI CREM-WXX9                                    | 2         | 0.25%   |
| HP Pavilion dv6                                     | 2         | 0.25%   |
| HP Laptop 15-dy2xxx                                 | 2         | 0.25%   |
| HP EliteDesk 800 G3 DM 65W                          | 2         | 0.25%   |
| HP EliteBook 8470p                                  | 2         | 0.25%   |
| HP EliteBook 845 G8 Notebook PC                     | 2         | 0.25%   |
| HP EliteBook 8440p                                  | 2         | 0.25%   |
| HP Compaq dc5800 Microtower                         | 2         | 0.25%   |
| HP 15                                               | 2         | 0.25%   |
| Gigabyte B360 AORUS GAMING 3 WIFI                   | 2         | 0.25%   |
| Gigabyte A520M S2H                                  | 2         | 0.25%   |
| Gigabyte 970A-DS3P                                  | 2         | 0.25%   |
| GEEKOM AE8                                          | 2         | 0.25%   |
| GEEKOM A7                                           | 2         | 0.25%   |
| Dell XPS 13 9360                                    | 2         | 0.25%   |
| Dell System Vostro 3750                             | 2         | 0.25%   |
| Dell Precision Tower 5810                           | 2         | 0.25%   |
| Dell Precision T3610                                | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 63        | 7.76%   |
| Acer Aspire        | 29        | 3.57%   |
| Dell Latitude      | 24        | 2.96%   |
| ASUS VivoBook      | 24        | 2.96%   |
| Lenovo IdeaPad     | 19        | 2.34%   |
| HP EliteBook       | 19        | 2.34%   |
| HP Pavilion        | 17        | 2.09%   |
| Dell Precision     | 15        | 1.85%   |
| HP Laptop          | 14        | 1.72%   |
| Dell Inspiron      | 14        | 1.72%   |
| Dell OptiPlex      | 12        | 1.48%   |
| ASUS ROG           | 12        | 1.48%   |
| HP Compaq          | 11        | 1.35%   |
| ASUS TUF           | 11        | 1.35%   |
| ASUS PRIME         | 11        | 1.35%   |
| Unknown            | 11        | 1.35%   |
| Toshiba Satellite  | 10        | 1.23%   |
| Lenovo ThinkCentre | 10        | 1.23%   |
| HP ProBook         | 9         | 1.11%   |
| HP ENVY            | 8         | 0.99%   |
| Fujitsu LIFEBOOK   | 8         | 0.99%   |
| Fujitsu ESPRIMO    | 8         | 0.99%   |
| ASUS ASUS          | 8         | 0.99%   |
| Dell XPS           | 7         | 0.86%   |
| Lenovo Yoga        | 6         | 0.74%   |
| ASUS Zenbook       | 6         | 0.74%   |
| ASUS All           | 5         | 0.62%   |
| Apple MacBookAir7  | 5         | 0.62%   |
| Lenovo IdeaPadFlex | 4         | 0.49%   |
| HP ProDesk         | 4         | 0.49%   |
| HP Notebook        | 4         | 0.49%   |
| ASRock A320M-HDV   | 4         | 0.49%   |
| Acer Predator      | 4         | 0.49%   |
| Lenovo V15         | 3         | 0.37%   |
| Gigabyte A520M     | 3         | 0.37%   |
| Fujitsu CELSIUS    | 3         | 0.37%   |
| Dell Vostro        | 3         | 0.37%   |
| ASUS P8H61-M       | 3         | 0.37%   |
| ASUS P5G41T-M      | 3         | 0.37%   |
| ASRock X670E       | 3         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 64        | 7.88%   |
| 2012    | 59        | 7.27%   |
| 2022    | 55        | 6.77%   |
| 2020    | 55        | 6.77%   |
| 2018    | 55        | 6.77%   |
| 2021    | 54        | 6.65%   |
| 2017    | 48        | 5.91%   |
| 2013    | 47        | 5.79%   |
| 2019    | 45        | 5.54%   |
| 2011    | 44        | 5.42%   |
| 2016    | 41        | 5.05%   |
| 2015    | 39        | 4.8%    |
| 2010    | 38        | 4.68%   |
| 2014    | 31        | 3.82%   |
| 2008    | 31        | 3.82%   |
| 2024    | 30        | 3.69%   |
| 2009    | 25        | 3.08%   |
| 2007    | 24        | 2.96%   |
| 2006    | 16        | 1.97%   |
| 2025    | 3         | 0.37%   |
| Unknown | 3         | 0.37%   |
| 2005    | 2         | 0.25%   |
| 2004    | 2         | 0.25%   |
| 2003    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 438       | 53.94%  |
| Desktop     | 294       | 36.21%  |
| Mini pc     | 25        | 3.08%   |
| All in one  | 23        | 2.83%   |
| Convertible | 18        | 2.22%   |
| Tablet      | 9         | 1.11%   |
| Server      | 3         | 0.37%   |
| Other       | 2         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 744       | 91.51%  |
| Enabled  | 69        | 8.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 809       | 99.63%  |
| Yes  | 3         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 209       | 25.46%  |
| 16.01-24.0  | 165       | 20.1%   |
| 8.01-16.0   | 122       | 14.86%  |
| 32.01-64.0  | 106       | 12.91%  |
| 3.01-4.0    | 106       | 12.91%  |
| 64.01-256.0 | 40        | 4.87%   |
| 24.01-32.0  | 27        | 3.29%   |
| 2.01-3.0    | 21        | 2.56%   |
| 1.01-2.0    | 20        | 2.44%   |
| 0.51-1.0    | 5         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 275       | 31.57%  |
| 1.01-2.0   | 215       | 24.68%  |
| 4.01-8.0   | 166       | 19.06%  |
| 3.01-4.0   | 150       | 17.22%  |
| 8.01-16.0  | 39        | 4.48%   |
| 0.51-1.0   | 19        | 2.18%   |
| 16.01-24.0 | 3         | 0.34%   |
| 24.01-32.0 | 2         | 0.23%   |
| 0.01-0.5   | 2         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 492       | 59.42%  |
| 2      | 201       | 24.28%  |
| 3      | 65        | 7.85%   |
| 4      | 39        | 4.71%   |
| 5      | 11        | 1.33%   |
| 6      | 8         | 0.97%   |
| 0      | 5         | 0.6%    |
| 7      | 4         | 0.48%   |
| 8      | 2         | 0.24%   |
| 10     | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 532       | 65.2%   |
| Yes       | 284       | 34.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 686       | 84.38%  |
| No        | 127       | 15.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 638       | 78.28%  |
| No        | 177       | 21.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 549       | 67.11%  |
| No        | 269       | 32.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Germany            | 150       | 18.47%  |
| USA                | 145       | 17.86%  |
| Italy              | 129       | 15.89%  |
| France             | 39        | 4.8%    |
| UK                 | 30        | 3.69%   |
| Russia             | 25        | 3.08%   |
| Brazil             | 24        | 2.96%   |
| Canada             | 19        | 2.34%   |
| Spain              | 17        | 2.09%   |
| Poland             | 15        | 1.85%   |
| Netherlands        | 14        | 1.72%   |
| Malaysia           | 11        | 1.35%   |
| Belgium            | 10        | 1.23%   |
| Australia          | 10        | 1.23%   |
| Austria            | 9         | 1.11%   |
| Argentina          | 9         | 1.11%   |
| Turkey             | 8         | 0.99%   |
| Sweden             | 8         | 0.99%   |
| Japan              | 8         | 0.99%   |
| Czechia            | 8         | 0.99%   |
| Switzerland        | 7         | 0.86%   |
| Romania            | 6         | 0.74%   |
| Norway             | 6         | 0.74%   |
| Mexico             | 6         | 0.74%   |
| India              | 6         | 0.74%   |
| Hungary            | 6         | 0.74%   |
| Finland            | 6         | 0.74%   |
| New Zealand        | 5         | 0.62%   |
| Portugal           | 4         | 0.49%   |
| Croatia            | 4         | 0.49%   |
| Uruguay            | 3         | 0.37%   |
| Saudi Arabia       | 3         | 0.37%   |
| Indonesia          | 3         | 0.37%   |
| Greece             | 3         | 0.37%   |
| Dominican Republic | 3         | 0.37%   |
| Denmark            | 3         | 0.37%   |
| Bulgaria           | 3         | 0.37%   |
| Ukraine            | 2         | 0.25%   |
| Thailand           | 2         | 0.25%   |
| Réunion           | 2         | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Milan        | 19        | 2.2%    |
| Berlin       | 16        | 1.86%   |
| Rome         | 10        | 1.16%   |
| Bologna      | 9         | 1.04%   |
| Traunstein   | 8         | 0.93%   |
| Vienna       | 7         | 0.81%   |
| Moscow       | 7         | 0.81%   |
| Milano       | 7         | 0.81%   |
| Kuala Lumpur | 7         | 0.81%   |
| Florence     | 7         | 0.81%   |
| Turin        | 6         | 0.7%    |
| Hamburg      | 6         | 0.7%    |
| Delligsen    | 6         | 0.7%    |
| Sydney       | 5         | 0.58%   |
| Leipzig      | 5         | 0.58%   |
| Dallas       | 5         | 0.58%   |
| Paris        | 4         | 0.46%   |
| Mannheim     | 4         | 0.46%   |
| Jacksonville | 4         | 0.46%   |
| Cologne      | 4         | 0.46%   |
| Bucharest    | 4         | 0.46%   |
| Auckland     | 4         | 0.46%   |
| Warsaw       | 3         | 0.35%   |
| Toronto      | 3         | 0.35%   |
| Sochi        | 3         | 0.35%   |
| San Antonio  | 3         | 0.35%   |
| Pilsen       | 3         | 0.35%   |
| Panama City  | 3         | 0.35%   |
| Padova       | 3         | 0.35%   |
| Oslo         | 3         | 0.35%   |
| Novara       | 3         | 0.35%   |
| Munich       | 3         | 0.35%   |
| Montreal     | 3         | 0.35%   |
| Montevideo   | 3         | 0.35%   |
| Mexico City  | 3         | 0.35%   |
| Melbourne    | 3         | 0.35%   |
| Malmo        | 3         | 0.35%   |
| Madrid       | 3         | 0.35%   |
| Los Angeles  | 3         | 0.35%   |
| Istanbul     | 3         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 183       | 280    | 14.6%   |
| WDC                         | 137       | 187    | 10.93%  |
| Seagate                     | 113       | 169    | 9.02%   |
| SanDisk                     | 83        | 113    | 6.62%   |
| Kingston                    | 69        | 106    | 5.51%   |
| Crucial                     | 63        | 77     | 5.03%   |
| Toshiba                     | 53        | 61     | 4.23%   |
| Unknown                     | 43        | 61     | 3.43%   |
| Micron Technology           | 32        | 36     | 2.55%   |
| Intel                       | 28        | 38     | 2.23%   |
| Hitachi                     | 24        | 30     | 1.92%   |
| China                       | 24        | 26     | 1.92%   |
| SK hynix                    | 23        | 25     | 1.84%   |
| Apple                       | 19        | 21     | 1.52%   |
| Intenso                     | 16        | 18     | 1.28%   |
| HGST                        | 16        | 18     | 1.28%   |
| SPCC                        | 14        | 14     | 1.12%   |
| A-DATA Technology           | 14        | 15     | 1.12%   |
| PNY                         | 13        | 19     | 1.04%   |
| Unknown                     | 13        | 24     | 1.04%   |
| KIOXIA                      | 12        | 15     | 0.96%   |
| Phison Electronics          | 11        | 12     | 0.88%   |
| Micron/Crucial Technology   | 11        | 17     | 0.88%   |
| MAXIO Technology (Hangzhou) | 10        | 11     | 0.8%    |
| Kingston Technology Company | 10        | 13     | 0.8%    |
| JMicron Technology          | 10        | 10     | 0.8%    |
| Patriot                     | 9         | 9      | 0.72%   |
| Verbatim                    | 8         | 12     | 0.64%   |
| Lexar                       | 8         | 9      | 0.64%   |
| Apacer                      | 8         | 12     | 0.64%   |
| ADATA Technology            | 8         | 13     | 0.64%   |
| Transcend                   | 7         | 7      | 0.56%   |
| Team                        | 7         | 8      | 0.56%   |
| Fujitsu                     | 7         | 7      | 0.56%   |
| Silicon Motion              | 6         | 6      | 0.48%   |
| Phison                      | 5         | 15     | 0.4%    |
| GOODRAM                     | 5         | 5      | 0.4%    |
| Gigabyte Technology         | 5         | 5      | 0.4%    |
| XrayDisk                    | 4         | 4      | 0.32%   |
| TO Exter                    | 4         | 4      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD                                    | 17        | 1.24%   |
| SanDisk NVMe SSD Drive 1TB                                         | 14        | 1.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 14        | 1.02%   |
| Kingston SA400S37240G 240GB SSD                                    | 14        | 1.02%   |
| Unknown                                                            | 13        | 0.95%   |
| SanDisk NVMe SSD Drive 2TB                                         | 12        | 0.88%   |
| Crucial CT500MX500SSD1 500GB                                       | 10        | 0.73%   |
| Unknown SD/MMC/MS PRO 2GB                                          | 9         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                              | 9         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                                        | 9         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                                     | 8         | 0.58%   |
| Samsung SSD 860 EVO 500GB                                          | 8         | 0.58%   |
| Samsung SSD 990 PRO 2TB                                            | 7         | 0.51%   |
| Samsung SSD 850 EVO 250GB                                          | 7         | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 7         | 0.51%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 7         | 0.51%   |
| Unknown MMC Card  64GB                                             | 6         | 0.44%   |
| Unknown MMC Card  128GB                                            | 6         | 0.44%   |
| Seagate ST500DM002-1BD142 500GB                                    | 6         | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB                                     | 6         | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                                       | 6         | 0.44%   |
| Samsung SSD 980 1TB                                                | 6         | 0.44%   |
| Samsung SSD 870 EVO 500GB                                          | 6         | 0.44%   |
| Kingston SA400S37120G 120GB SSD                                    | 6         | 0.44%   |
| JMicron Generic 320GB                                              | 6         | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB                                       | 5         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                                           | 5         | 0.36%   |
| Toshiba MQ01ABD100 1TB                                             | 5         | 0.36%   |
| Toshiba DT01ACA100 1TB                                             | 5         | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                                     | 5         | 0.36%   |
| SanDisk SSD PLUS 1000GB                                            | 5         | 0.36%   |
| Samsung SSD 990 PRO 1TB                                            | 5         | 0.36%   |
| Samsung SSD 860 EVO 250GB                                          | 5         | 0.36%   |
| Samsung MZVLQ1T0HALB-00000 1TB                                     | 5         | 0.36%   |
| Phison PCIe SSD 500GB                                              | 5         | 0.36%   |
| MAXIO (Hangzhou) NVMe SSD Drive 512GB                              | 5         | 0.36%   |
| Crucial CT250MX500SSD1 250GB                                       | 5         | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB                                           | 4         | 0.29%   |
| Verbatim Vi550 S3 1024GB                                           | 4         | 0.29%   |
| Unknown MMC Card  32GB                                             | 4         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 111       | 164    | 31.27%  |
| WDC                 | 100       | 139    | 28.17%  |
| Toshiba             | 41        | 49     | 11.55%  |
| Hitachi             | 24        | 30     | 6.76%   |
| HGST                | 16        | 18     | 4.51%   |
| Samsung Electronics | 12        | 14     | 3.38%   |
| Unknown             | 10        | 11     | 2.82%   |
| Fujitsu             | 7         | 7      | 1.97%   |
| Apple               | 7         | 7      | 1.97%   |
| JMicron Technology  | 6         | 6      | 1.69%   |
| TO Exter            | 4         | 4      | 1.13%   |
| Maxtor              | 3         | 3      | 0.85%   |
| External            | 3         | 3      | 0.85%   |
| USB3.0              | 2         | 2      | 0.56%   |
| Intenso             | 2         | 2      | 0.56%   |
| TrueNAS             | 1         | 2      | 0.28%   |
| T-FORCE             | 1         | 1      | 0.28%   |
| IBM/Hitachi         | 1         | 1      | 0.28%   |
| DC-624e             | 1         | 1      | 0.28%   |
| ASMT                | 1         | 2      | 0.28%   |
| ASMedia             | 1         | 1      | 0.28%   |
| Unknown             | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 104    | 17.29%  |
| Kingston            | 53        | 82     | 11.6%   |
| Crucial             | 46        | 59     | 10.07%  |
| SanDisk             | 30        | 33     | 6.56%   |
| China               | 24        | 26     | 5.25%   |
| WDC                 | 23        | 29     | 5.03%   |
| Apple               | 13        | 13     | 2.84%   |
| SPCC                | 12        | 12     | 2.63%   |
| PNY                 | 12        | 18     | 2.63%   |
| Intenso             | 12        | 14     | 2.63%   |
| A-DATA Technology   | 11        | 12     | 2.41%   |
| Micron Technology   | 10        | 11     | 2.19%   |
| Intel               | 9         | 11     | 1.97%   |
| Patriot             | 8         | 8      | 1.75%   |
| Verbatim            | 7         | 11     | 1.53%   |
| Transcend           | 7         | 7      | 1.53%   |
| Team                | 6         | 7      | 1.31%   |
| Apacer              | 6         | 10     | 1.31%   |
| Unknown             | 5         | 13     | 1.09%   |
| Toshiba             | 4         | 4      | 0.88%   |
| SABRENT             | 4         | 4      | 0.88%   |
| OCZ                 | 4         | 4      | 0.88%   |
| KingSpec            | 4         | 4      | 0.88%   |
| GOODRAM             | 4         | 4      | 0.88%   |
| Phison              | 3         | 13     | 0.66%   |
| Lexar               | 3         | 3      | 0.66%   |
| Integral            | 3         | 3      | 0.66%   |
| Hewlett-Packard     | 3         | 5      | 0.66%   |
| Gigabyte Technology | 3         | 3      | 0.66%   |
| XrayDisk            | 2         | 2      | 0.44%   |
| T-FORCE             | 2         | 2      | 0.44%   |
| SK hynix            | 2         | 2      | 0.44%   |
| Seagate             | 2         | 2      | 0.44%   |
| LITEON              | 2         | 2      | 0.44%   |
| KingDian            | 2         | 2      | 0.44%   |
| Fanxiang            | 2         | 3      | 0.44%   |
| AMD                 | 2         | 2      | 0.44%   |
| X12                 | 1         | 1      | 0.22%   |
| Vi550               | 1         | 2      | 0.22%   |
| V Series            | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 388       | 580    | 35.24%  |
| NVMe    | 350       | 541    | 31.79%  |
| HDD     | 303       | 468    | 27.52%  |
| MMC     | 35        | 46     | 3.18%   |
| Unknown | 25        | 36     | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 556       | 993    | 54.72%  |
| NVMe | 348       | 532    | 34.25%  |
| SAS  | 77        | 100    | 7.58%   |
| MMC  | 35        | 46     | 3.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 421       | 608    | 57.99%  |
| 0.51-1.0   | 183       | 253    | 25.21%  |
| 1.01-2.0   | 63        | 98     | 8.68%   |
| 3.01-4.0   | 36        | 54     | 4.96%   |
| 4.01-10.0  | 12        | 21     | 1.65%   |
| 2.01-3.0   | 6         | 8      | 0.83%   |
| 10.01-20.0 | 5         | 6      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 215       | 25.56%  |
| 251-500        | 177       | 21.05%  |
| 501-1000       | 168       | 19.98%  |
| 1001-2000      | 82        | 9.75%   |
| More than 3000 | 58        | 6.9%    |
| 1-20           | 45        | 5.35%   |
| 51-100         | 37        | 4.4%    |
| 2001-3000      | 30        | 3.57%   |
| 21-50          | 16        | 1.9%    |
| Unknown        | 13        | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 261       | 29.93%  |
| 21-50          | 162       | 18.58%  |
| 101-250        | 128       | 14.68%  |
| 51-100         | 105       | 12.04%  |
| 251-500        | 78        | 8.94%   |
| 501-1000       | 63        | 7.22%   |
| 1001-2000      | 26        | 2.98%   |
| More than 3000 | 23        | 2.64%   |
| 2001-3000      | 13        | 1.49%   |
| Unknown        | 13        | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 3         | 3      | 3.49%   |
| Samsung Electronics HD502IJ 500GB     | 2         | 3      | 2.33%   |
| Intel SSDSA2M160G2GC 160GB            | 2         | 2      | 2.33%   |
| Hitachi HTS543232L9A300 320GB         | 2         | 2      | 2.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 1.16%   |
| WDC WD7500BPVT-00HXZT3 752GB          | 1         | 1      | 1.16%   |
| WDC WD5000LPVX-60V0TT0 500GB          | 1         | 1      | 1.16%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.16%   |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 1.16%   |
| WDC WD1600JS-60MHB5 160GB             | 1         | 1      | 1.16%   |
| WDC WD15EADS-00P8B0 1TB               | 1         | 1      | 1.16%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 1      | 1.16%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 1.16%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 1      | 1.16%   |
| WDC WD10EFRX-68PJCN0 1TB              | 1         | 1      | 1.16%   |
| WDC WD Green 2.5 240GB                | 1         | 1      | 1.16%   |
| Unknown MMC Card  128GB               | 1         | 1      | 1.16%   |
| Transcend TS512GMTS430S 512GB SSD     | 1         | 1      | 1.16%   |
| Toshiba MK1652GSX 160GB               | 1         | 1      | 1.16%   |
| Toshiba MK1637GSX 160GB               | 1         | 1      | 1.16%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.16%   |
| SSSTC CV8-8E128-HP 128GB SSD          | 1         | 1      | 1.16%   |
| Solid SSD0256S00 256GB                | 1         | 1      | 1.16%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 1.16%   |
| SK hynix HFS060G32MNB-2000A 64GB SSD  | 1         | 1      | 1.16%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 1.16%   |
| Seagate ST910021AS 100GB              | 1         | 1      | 1.16%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.16%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 1.16%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.16%   |
| Seagate ST31000524AS 1TB              | 1         | 1      | 1.16%   |
| Seagate ST2000DM006-2DM164 2TB        | 1         | 1      | 1.16%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.16%   |
| Seagate ST1000DX001-1NS162 1TB        | 1         | 1      | 1.16%   |
| Seagate ST1000DM003-1SB102 1TB        | 1         | 1      | 1.16%   |
| SanDisk SSD PLUS 480 GB               | 1         | 1      | 1.16%   |
| SanDisk SDSSDHII120G 120GB            | 1         | 2      | 1.16%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 1.16%   |
| Samsung Electronics SSD 870 EVO 2TB   | 1         | 1      | 1.16%   |
| Samsung Electronics SSD 850 PRO 256GB | 1         | 1      | 1.16%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 15.29%  |
| WDC                 | 12        | 12     | 14.12%  |
| Samsung Electronics | 10        | 11     | 11.76%  |
| Hitachi             | 6         | 7      | 7.06%   |
| Intel               | 4         | 4      | 4.71%   |
| Toshiba             | 3         | 3      | 3.53%   |
| Kingston            | 3         | 3      | 3.53%   |
| HGST                | 3         | 3      | 3.53%   |
| Fujitsu             | 3         | 3      | 3.53%   |
| China               | 3         | 4      | 3.53%   |
| Apple               | 3         | 3      | 3.53%   |
| A-DATA Technology   | 3         | 3      | 3.53%   |
| SK hynix            | 2         | 2      | 2.35%   |
| SanDisk             | 2         | 3      | 2.35%   |
| Micron Technology   | 2         | 2      | 2.35%   |
| Maxtor              | 2         | 2      | 2.35%   |
| Crucial             | 2         | 3      | 2.35%   |
| Unknown             | 1         | 1      | 1.18%   |
| Transcend           | 1         | 1      | 1.18%   |
| SSSTC               | 1         | 1      | 1.18%   |
| Solid               | 1         | 1      | 1.18%   |
| Lexar               | 1         | 1      | 1.18%   |
| Leven               | 1         | 1      | 1.18%   |
| KUU                 | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| IBM/Hitachi         | 1         | 1      | 1.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 27.08%  |
| WDC                 | 10        | 10     | 20.83%  |
| Hitachi             | 6         | 7      | 12.5%   |
| Samsung Electronics | 5         | 6      | 10.42%  |
| Toshiba             | 3         | 3      | 6.25%   |
| HGST                | 3         | 3      | 6.25%   |
| Fujitsu             | 3         | 3      | 6.25%   |
| Maxtor              | 2         | 2      | 4.17%   |
| Apple               | 2         | 2      | 4.17%   |
| IBM/Hitachi         | 1         | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 50     | 55.95%  |
| SSD  | 31        | 34     | 36.9%   |
| NVMe | 5         | 5      | 5.95%   |
| MMC  | 1         | 1      | 1.19%   |

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
| Works    | 432       | 751    | 47.21%  |
| Detected | 400       | 830    | 43.72%  |
| Malfunc  | 83        | 90     | 9.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 513       | 46.81%  |
| AMD                                     | 142       | 12.96%  |
| Samsung Electronics                     | 112       | 10.22%  |
| SanDisk                                 | 65        | 5.93%   |
| Kingston Technology Company             | 27        | 2.46%   |
| Micron Technology                       | 25        | 2.28%   |
| Micron/Crucial Technology               | 24        | 2.19%   |
| Phison Electronics                      | 23        | 2.1%    |
| SK hynix                                | 21        | 1.92%   |
| ASMedia Technology                      | 17        | 1.55%   |
| MAXIO Technology (Hangzhou)             | 13        | 1.19%   |
| KIOXIA                                  | 13        | 1.19%   |
| Marvell Technology Group                | 12        | 1.09%   |
| ADATA Technology                        | 11        | 1%      |
| Nvidia                                  | 10        | 0.91%   |
| JMicron Technology                      | 10        | 0.91%   |
| Toshiba America Info Systems            | 9         | 0.82%   |
| Silicon Motion                          | 8         | 0.73%   |
| VIA Technologies                        | 5         | 0.46%   |
| Shenzhen Longsys Electronics            | 4         | 0.36%   |
| Solidigm                                | 3         | 0.27%   |
| Solid State Storage Technology          | 3         | 0.27%   |
| Hosin Global Electronics                | 3         | 0.27%   |
| Union Memory (Shenzhen)                 | 2         | 0.18%   |
| Silicon Image                           | 2         | 0.18%   |
| Realtek Semiconductor                   | 2         | 0.18%   |
| Netac Technology                        | 2         | 0.18%   |
| INNOGRIT                                | 2         | 0.18%   |
| Yangtze Memory Technologies             | 1         | 0.09%   |
| TenaFe                                  | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.09%   |
| Shenzhen Unionmemory Information System | 1         | 0.09%   |
| Seagate Technology                      | 1         | 0.09%   |
| LSI Logic / Symbios Logic               | 1         | 0.09%   |
| Integrated Technology Express           | 1         | 0.09%   |
| Dell                                    | 1         | 0.09%   |
| Chelsio Communications                  | 1         | 0.09%   |
| Broadcom / LSI                          | 1         | 0.09%   |
| Apple                                   | 1         | 0.09%   |
| Adaptec                                 | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 73        | 5.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 38        | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 36        | 2.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 29        | 2.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 26        | 2.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 2.11%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 2.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 25        | 2.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 25        | 2.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 21        | 1.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 21        | 1.7%    |
| AMD 500 Series Chipset SATA Controller                                         | 21        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 19        | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 1.46%   |
| AMD 400 Series Chipset SATA Controller                                         | 16        | 1.3%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 15        | 1.21%   |
| Intel SATA Controller [RAID mode]                                              | 15        | 1.21%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 15        | 1.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 15        | 1.21%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 15        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 15        | 1.21%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14        | 1.13%   |
| AMD 600 Series Chipset SATA Controller                                         | 14        | 1.13%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 12        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 0.97%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 12        | 0.97%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 12        | 0.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 0.97%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 11        | 0.89%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 0.89%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 11        | 0.89%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 11        | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11        | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 0.81%   |
| Intel RST Volume Management Device Controller                                  | 10        | 0.81%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 0.73%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 9         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 531       | 49.67%  |
| NVMe | 344       | 32.18%  |
| IDE  | 107       | 10.01%  |
| RAID | 84        | 7.86%   |
| SCSI | 2         | 0.19%   |
| SAS  | 1         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 607       | 74.75%  |
| AMD          | 204       | 25.12%  |
| CentaurHauls | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel N100                              | 11        | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 7         | 0.86%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 7         | 0.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 6         | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 6         | 0.74%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 5         | 0.61%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 5         | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 5         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 5         | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 5         | 0.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 0.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 0.49%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 4         | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 4         | 0.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 4         | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 0.49%   |
| Intel Core i5-7500 CPU @ 3.40GHz        | 4         | 0.49%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 0.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 0.49%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 4         | 0.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 4         | 0.49%   |
| Intel Celeron N4500 @ 1.10GHz           | 4         | 0.49%   |
| Intel 13th Gen Core i9-13900H           | 4         | 0.49%   |
| Intel 13th Gen Core i7-1355U            | 4         | 0.49%   |
| Intel 13th Gen Core i5-1340P            | 4         | 0.49%   |
| Intel 12th Gen Core i7-12700H           | 4         | 0.49%   |
| Intel 12th Gen Core i7-1260P            | 4         | 0.49%   |
| Intel 12th Gen Core i5-1240P            | 4         | 0.49%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 4         | 0.49%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 4         | 0.49%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 4         | 0.49%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 4         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 174       | 21.38%  |
| Intel Core i7           | 116       | 14.25%  |
| Other                   | 107       | 13.14%  |
| AMD Ryzen 7             | 53        | 6.51%   |
| Intel Core i3           | 47        | 5.77%   |
| AMD Ryzen 5             | 47        | 5.77%   |
| Intel Celeron           | 32        | 3.93%   |
| Intel Core 2 Duo        | 30        | 3.69%   |
| AMD Ryzen 9             | 24        | 2.95%   |
| Intel Xeon              | 22        | 2.7%    |
| Intel Atom              | 14        | 1.72%   |
| Intel Genuine           | 12        | 1.47%   |
| Intel Pentium Dual-Core | 11        | 1.35%   |
| Intel Pentium           | 11        | 1.35%   |
| AMD Ryzen 3             | 9         | 1.11%   |
| Intel Core 2 Quad       | 6         | 0.74%   |
| AMD Ryzen 7 PRO         | 6         | 0.74%   |
| AMD Phenom II X6        | 6         | 0.74%   |
| Intel Core 2            | 5         | 0.61%   |
| AMD FX                  | 5         | 0.61%   |
| AMD A8                  | 5         | 0.61%   |
| AMD A6                  | 5         | 0.61%   |
| Intel Pentium Silver    | 4         | 0.49%   |
| Intel Pentium M         | 4         | 0.49%   |
| Intel Core i9           | 4         | 0.49%   |
| Intel Core              | 4         | 0.49%   |
| AMD Ryzen 5 PRO         | 4         | 0.49%   |
| AMD Athlon              | 4         | 0.49%   |
| AMD A4                  | 4         | 0.49%   |
| Intel Core Duo          | 3         | 0.37%   |
| AMD E2                  | 3         | 0.37%   |
| Intel Pentium 4         | 2         | 0.25%   |
| Intel Celeron M         | 2         | 0.25%   |
| AMD Sempron             | 2         | 0.25%   |
| AMD Phenom II X4        | 2         | 0.25%   |
| AMD Opteron             | 2         | 0.25%   |
| AMD G                   | 2         | 0.25%   |
| AMD E1                  | 2         | 0.25%   |
| AMD E                   | 2         | 0.25%   |
| AMD Athlon II X4        | 2         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 285       | 35.06%  |
| 4      | 268       | 32.96%  |
| 6      | 83        | 10.21%  |
| 8      | 78        | 9.59%   |
| 12     | 28        | 3.44%   |
| 1      | 24        | 2.95%   |
| 10     | 15        | 1.85%   |
| 16     | 14        | 1.72%   |
| 14     | 12        | 1.48%   |
| 24     | 3         | 0.37%   |
| 3      | 3         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 807       | 99.38%  |
| 2      | 4         | 0.49%   |
| 16     | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 535       | 65.89%  |
| 1      | 277       | 34.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 786       | 96.8%   |
| 32-bit         | 26        | 3.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 14.77%  |
| 0x206a7    | 45        | 5.45%   |
| 0x306a9    | 43        | 5.21%   |
| 0x306c3    | 35        | 4.24%   |
| 0x1067a    | 24        | 2.91%   |
| 0x906e9    | 22        | 2.66%   |
| 0x40651    | 21        | 2.54%   |
| 0x806ec    | 18        | 2.18%   |
| 0x506e3    | 17        | 2.06%   |
| 0x806e9    | 16        | 1.94%   |
| 0x806c1    | 14        | 1.69%   |
| 0x306d4    | 14        | 1.69%   |
| 0xb06e0    | 13        | 1.57%   |
| 0x806ea    | 13        | 1.57%   |
| 0x906a3    | 12        | 1.45%   |
| 0x20655    | 11        | 1.33%   |
| 0x10676    | 11        | 1.33%   |
| 0x6e8      | 9         | 1.09%   |
| 0x08108109 | 9         | 1.09%   |
| 0xb06a3    | 8         | 0.97%   |
| 0xb06a2    | 8         | 0.97%   |
| 0xb0671    | 8         | 0.97%   |
| 0x706a8    | 8         | 0.97%   |
| 0x406e3    | 8         | 0.97%   |
| 0x0a50000c | 8         | 0.97%   |
| 0x906ea    | 7         | 0.85%   |
| 0x906a4    | 7         | 0.85%   |
| 0x6fd      | 7         | 0.85%   |
| 0x0a50000d | 7         | 0.85%   |
| 0x010000c8 | 7         | 0.85%   |
| 0x906c0    | 6         | 0.73%   |
| 0x806d1    | 6         | 0.73%   |
| 0x706e5    | 6         | 0.73%   |
| 0x6ec      | 6         | 0.73%   |
| 0x306e4    | 6         | 0.73%   |
| 0x30678    | 6         | 0.73%   |
| 0x0a20120e | 6         | 0.73%   |
| 0x08608103 | 6         | 0.73%   |
| 0x08600106 | 6         | 0.73%   |
| 0xa0652    | 5         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 105       | 12.92%  |
| Haswell          | 69        | 8.49%   |
| Unknown          | 62        | 7.63%   |
| Alderlake Hybrid | 56        | 6.89%   |
| IvyBridge        | 55        | 6.77%   |
| SandyBridge      | 48        | 5.9%    |
| Zen 3            | 44        | 5.41%   |
| Penryn           | 38        | 4.67%   |
| Skylake          | 30        | 3.69%   |
| Zen 2            | 22        | 2.71%   |
| TigerLake        | 21        | 2.58%   |
| Core             | 21        | 2.58%   |
| P6               | 20        | 2.46%   |
| Broadwell        | 20        | 2.46%   |
| Zen+             | 19        | 2.34%   |
| Silvermont       | 18        | 2.21%   |
| Westmere         | 16        | 1.97%   |
| Zen              | 15        | 1.85%   |
| K10              | 15        | 1.85%   |
| Gracemont        | 15        | 1.85%   |
| Icelake          | 13        | 1.6%    |
| Goldmont plus    | 11        | 1.35%   |
| CometLake        | 11        | 1.35%   |
| Piledriver       | 9         | 1.11%   |
| Excavator        | 9         | 1.11%   |
| Puma             | 7         | 0.86%   |
| Nehalem          | 7         | 0.86%   |
| Bonnell          | 7         | 0.86%   |
| Tremont          | 6         | 0.74%   |
| Goldmont         | 6         | 0.74%   |
| NetBurst         | 4         | 0.49%   |
| Jaguar           | 3         | 0.37%   |
| Bobcat           | 3         | 0.37%   |
| K8 Hammer        | 2         | 0.25%   |
| Bulldozer        | 2         | 0.25%   |
| Steamroller      | 1         | 0.12%   |
| K8 & K10 hybrid  | 1         | 0.12%   |
| K6               | 1         | 0.12%   |
| K10 Llano        | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 475       | 51.8%   |
| AMD              | 235       | 25.63%  |
| Nvidia           | 206       | 22.46%  |
| VIA Technologies | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 37        | 3.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 2.28%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 18        | 1.87%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 16        | 1.66%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 16        | 1.66%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 15        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.45%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 14        | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.35%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 13        | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.25%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 12        | 1.25%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 12        | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 1.14%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 11        | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.14%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 11        | 1.14%   |
| AMD Rembrandt [Radeon 680M]                                                              | 11        | 1.14%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 1.04%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 10        | 1.04%   |
| AMD Raphael                                                                              | 10        | 1.04%   |
| AMD Lucienne                                                                             | 10        | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.83%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 8         | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.73%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 7         | 0.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.62%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 0.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 348       | 42.8%   |
| 1 x AMD        | 191       | 23.49%  |
| 1 x Nvidia     | 122       | 15.01%  |
| Intel + Nvidia | 73        | 8.98%   |
| 2 x Intel      | 30        | 3.69%   |
| 2 x AMD        | 23        | 2.83%   |
| Intel + AMD    | 14        | 1.72%   |
| AMD + Nvidia   | 8         | 0.98%   |
| 2 x Nvidia     | 3         | 0.37%   |
| 1 x VIA        | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 725       | 89.07%  |
| Proprietary | 72        | 8.85%   |
| Unknown     | 17        | 2.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 451       | 54.93%  |
| 0.01-0.5   | 116       | 14.13%  |
| 1.01-2.0   | 68        | 8.28%   |
| 0.51-1.0   | 51        | 6.21%   |
| 3.01-4.0   | 47        | 5.72%   |
| 7.01-8.0   | 34        | 4.14%   |
| 5.01-6.0   | 22        | 2.68%   |
| 8.01-16.0  | 18        | 2.19%   |
| 2.01-3.0   | 10        | 1.22%   |
| 16.01-24.0 | 4         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 104       | 11.93%  |
| AU Optronics            | 101       | 11.58%  |
| BOE                     | 81        | 9.29%   |
| Chimei Innolux          | 68        | 7.8%    |
| LG Display              | 65        | 7.45%   |
| Goldstar                | 48        | 5.5%    |
| Dell                    | 43        | 4.93%   |
| Apple                   | 30        | 3.44%   |
| Hewlett-Packard         | 26        | 2.98%   |
| Acer                    | 24        | 2.75%   |
| Philips                 | 22        | 2.52%   |
| AOC                     | 21        | 2.41%   |
| Lenovo                  | 16        | 1.83%   |
| BenQ                    | 14        | 1.61%   |
| Ancor Communications    | 14        | 1.61%   |
| Iiyama                  | 11        | 1.26%   |
| Eizo                    | 11        | 1.26%   |
| ASUSTek Computer        | 11        | 1.26%   |
| Sharp                   | 10        | 1.15%   |
| HUAWEI                  | 10        | 1.15%   |
| Chi Mei Optoelectronics | 10        | 1.15%   |
| LG Philips              | 8         | 0.92%   |
| MSI                     | 7         | 0.8%    |
| Mi                      | 6         | 0.69%   |
| HannStar                | 6         | 0.69%   |
| Fujitsu Siemens         | 6         | 0.69%   |
| PANDA                   | 5         | 0.57%   |
| Panasonic               | 5         | 0.57%   |
| InfoVision              | 5         | 0.57%   |
| NEC Computers           | 4         | 0.46%   |
| CPT                     | 4         | 0.46%   |
| Belinea                 | 4         | 0.46%   |
| Vizio                   | 3         | 0.34%   |
| ViewSonic               | 3         | 0.34%   |
| Toshiba                 | 3         | 0.34%   |
| RTK                     | 3         | 0.34%   |
| HKC                     | 3         | 0.34%   |
| GreenWood               | 3         | 0.34%   |
| CSO                     | 3         | 0.34%   |
| VIZTA                   | 2         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                 | 8         | 0.9%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 5         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch     | 5         | 0.56%   |
| Panasonic VVX11F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch         | 4         | 0.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.45%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch | 3         | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.34%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 3         | 0.34%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 3         | 0.34%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 0.34%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                | 3         | 0.34%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch       | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.34%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                 | 3         | 0.34%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 3         | 0.34%   |
| Vizio D43f-F1 VIZ1027 1920x1080 940x529mm 42.5-inch                  | 2         | 0.22%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 2         | 0.22%   |
| Samsung Electronics SyncMaster SAM0456 1360x768 410x230mm 18.5-inch  | 2         | 0.22%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.22%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch | 2         | 0.22%   |
| Philips PHL 244E5 PHLC0C0 1920x1080 527x296mm 23.8-inch              | 2         | 0.22%   |
| PANDA LCD Monitor NCP0061 2560x1600 302x189mm 14.0-inch              | 2         | 0.22%   |
| NEC Computers PA271W NEC67DA 2560x1440 596x335mm 26.9-inch           | 2         | 0.22%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                     | 2         | 0.22%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 2         | 0.22%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 2         | 0.22%   |
| LG Display LCD Monitor LGD0303 1600x900 382x215mm 17.3-inch          | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 345       | 40.88%  |
| 1366x768 (WXGA)    | 128       | 15.17%  |
| 3840x2160 (4K)     | 77        | 9.12%   |
| 2560x1440 (QHD)    | 37        | 4.38%   |
| 1920x1200 (WUXGA)  | 36        | 4.27%   |
| 1600x900 (HD+)     | 35        | 4.15%   |
| 1680x1050 (WSXGA+) | 31        | 3.67%   |
| 1440x900 (WXGA+)   | 26        | 3.08%   |
| 1280x800 (WXGA)    | 19        | 2.25%   |
| 1280x1024 (SXGA)   | 18        | 2.13%   |
| 3440x1440          | 14        | 1.66%   |
| 2560x1600          | 13        | 1.54%   |
| Unknown            | 8         | 0.95%   |
| 3840x1080          | 6         | 0.71%   |
| 2560x1080          | 6         | 0.71%   |
| 1360x768           | 5         | 0.59%   |
| 1024x768 (XGA)     | 5         | 0.59%   |
| 1024x600           | 4         | 0.47%   |
| 2880x1800          | 3         | 0.36%   |
| 2256x1504          | 3         | 0.36%   |
| 2160x1440          | 3         | 0.36%   |
| 2520x1680          | 2         | 0.24%   |
| 1920x540           | 2         | 0.24%   |
| 1920x1280          | 2         | 0.24%   |
| 9600x2160          | 1         | 0.12%   |
| 800x1280           | 1         | 0.12%   |
| 4480x1440          | 1         | 0.12%   |
| 3840x2400          | 1         | 0.12%   |
| 3840x1600          | 1         | 0.12%   |
| 3200x2000          | 1         | 0.12%   |
| 2880x1620          | 1         | 0.12%   |
| 2560x1024          | 1         | 0.12%   |
| 2240x1400          | 1         | 0.12%   |
| 2160x1350          | 1         | 0.12%   |
| 1680x945           | 1         | 0.12%   |
| 1600x2560          | 1         | 0.12%   |
| 1600x1200          | 1         | 0.12%   |
| 1400x1050          | 1         | 0.12%   |
| 1366x912           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 221       | 25.52%  |
| 27      | 70        | 8.08%   |
| 14      | 67        | 7.74%   |
| 13      | 62        | 7.16%   |
| 24      | 61        | 7.04%   |
| 23      | 49        | 5.66%   |
| 17      | 46        | 5.31%   |
| 21      | 33        | 3.81%   |
| 31      | 31        | 3.58%   |
| 34      | 25        | 2.89%   |
| 22      | 25        | 2.89%   |
| Unknown | 25        | 2.89%   |
| 19      | 21        | 2.42%   |
| 16      | 18        | 2.08%   |
| 12      | 15        | 1.73%   |
| 18      | 14        | 1.62%   |
| 20      | 12        | 1.39%   |
| 11      | 10        | 1.15%   |
| 32      | 7         | 0.81%   |
| 84      | 6         | 0.69%   |
| 54      | 6         | 0.69%   |
| 26      | 5         | 0.58%   |
| 10      | 5         | 0.58%   |
| 42      | 4         | 0.46%   |
| 72      | 3         | 0.35%   |
| 49      | 3         | 0.35%   |
| 86      | 2         | 0.23%   |
| 63      | 2         | 0.23%   |
| 48      | 2         | 0.23%   |
| 46      | 2         | 0.23%   |
| 40      | 2         | 0.23%   |
| 95      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 57      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 50      | 1         | 0.12%   |
| 38      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 35      | 1         | 0.12%   |
| 30      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 330       | 38.6%   |
| 501-600     | 171       | 20%     |
| 401-500     | 92        | 10.76%  |
| 201-300     | 69        | 8.07%   |
| 351-400     | 55        | 6.43%   |
| 601-700     | 39        | 4.56%   |
| 701-800     | 32        | 3.74%   |
| Unknown     | 25        | 2.92%   |
| 1001-1500   | 19        | 2.22%   |
| 1501-2000   | 11        | 1.29%   |
| 801-900     | 6         | 0.7%    |
| 901-1000    | 4         | 0.47%   |
| 101-200     | 1         | 0.12%   |
| 1-100       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 583       | 72.15%  |
| 16/10   | 132       | 16.34%  |
| 21/9    | 27        | 3.34%   |
| Unknown | 22        | 2.72%   |
| 5/4     | 18        | 2.23%   |
| 3/2     | 13        | 1.61%   |
| 4/3     | 8         | 0.99%   |
| 32/9    | 2         | 0.25%   |
| 0.56    | 2         | 0.25%   |
| 0.67    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 218       | 25.56%  |
| 201-250        | 125       | 14.65%  |
| 81-90          | 104       | 12.19%  |
| 301-350        | 72        | 8.44%   |
| 351-500        | 65        | 7.62%   |
| 151-200        | 42        | 4.92%   |
| 121-130        | 32        | 3.75%   |
| More than 1000 | 27        | 3.17%   |
| 251-300        | 26        | 3.05%   |
| 71-80          | 25        | 2.93%   |
| Unknown        | 25        | 2.93%   |
| 141-150        | 20        | 2.34%   |
| 111-120        | 19        | 2.23%   |
| 61-70          | 13        | 1.52%   |
| 501-1000       | 12        | 1.41%   |
| 51-60          | 11        | 1.29%   |
| 131-140        | 7         | 0.82%   |
| 41-50          | 4         | 0.47%   |
| 91-100         | 4         | 0.47%   |
| 1-40           | 2         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 289       | 34.4%   |
| 121-160       | 232       | 27.62%  |
| 101-120       | 202       | 24.05%  |
| 161-240       | 65        | 7.74%   |
| Unknown       | 25        | 2.98%   |
| 1-50          | 21        | 2.5%    |
| More than 240 | 6         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 703       | 85.94%  |
| 2     | 90        | 11%     |
| 0     | 13        | 1.59%   |
| 3     | 9         | 1.1%    |
| 4     | 3         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 434       | 35.96%  |
| Intel                                  | 387       | 32.06%  |
| Qualcomm Atheros                       | 93        | 7.71%   |
| Broadcom                               | 70        | 5.8%    |
| MediaTek                               | 43        | 3.56%   |
| Broadcom Limited                       | 27        | 2.24%   |
| TP-Link                                | 20        | 1.66%   |
| Marvell Technology Group               | 19        | 1.57%   |
| ASIX Electronics                       | 14        | 1.16%   |
| Ralink Technology                      | 13        | 1.08%   |
| Ralink                                 | 12        | 0.99%   |
| Nvidia                                 | 9         | 0.75%   |
| Samsung Electronics                    | 5         | 0.41%   |
| Sierra Wireless                        | 4         | 0.33%   |
| Qualcomm                               | 4         | 0.33%   |
| Ericsson Business Mobile Networks      | 4         | 0.33%   |
| Dell                                   | 4         | 0.33%   |
| QinHeng Electronics                    | 3         | 0.25%   |
| JMicron Technology                     | 3         | 0.25%   |
| D-Link System                          | 3         | 0.25%   |
| VIA Technologies                       | 2         | 0.17%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.17%   |
| NetGear                                | 2         | 0.17%   |
| Microsoft                              | 2         | 0.17%   |
| Mercucys                               | 2         | 0.17%   |
| Lenovo                                 | 2         | 0.17%   |
| Hewlett-Packard                        | 2         | 0.17%   |
| Edimax Technology                      | 2         | 0.17%   |
| D-Link                                 | 2         | 0.17%   |
| Xiaomi                                 | 1         | 0.08%   |
| Winbond Electronics                    | 1         | 0.08%   |
| U-Blox                                 | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.08%   |
| Shenzhen Goodix Technology             | 1         | 0.08%   |
| OPPO Electronics                       | 1         | 0.08%   |
| MicroPython                            | 1         | 0.08%   |
| Mellanox Technologies                  | 1         | 0.08%   |
| IMC Networks                           | 1         | 0.08%   |
| Huawei Technologies                    | 1         | 0.08%   |
| DisplayLink                            | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 259       | 17.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 46        | 3.15%   |
| Realtek RTL8125 2.5GbE Controller                                      | 40        | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35        | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 33        | 2.26%   |
| Intel Wi-Fi 6 AX200                                                    | 26        | 1.78%   |
| Intel Wireless 8265 / 8275                                             | 22        | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 20        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 18        | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 18        | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 16        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 16        | 1.1%    |
| Intel Wireless 7265                                                    | 15        | 1.03%   |
| Intel Wireless 7260                                                    | 15        | 1.03%   |
| Intel Ethernet Connection I217-LM                                      | 15        | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 13        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                                   | 13        | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 13        | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 12        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 0.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 12        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 11        | 0.75%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 11        | 0.75%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.75%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 10        | 0.69%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 10        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.62%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 9         | 0.62%   |
| Intel Ethernet Controller I225-V                                       | 9         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 9         | 0.62%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 8         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 0.55%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 8         | 0.55%   |
| Intel Wireless 8260                                                    | 8         | 0.55%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 8         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 287       | 42.33%  |
| Realtek Semiconductor                 | 136       | 20.06%  |
| Qualcomm Atheros                      | 75        | 11.06%  |
| Broadcom                              | 49        | 7.23%   |
| MediaTek                              | 38        | 5.6%    |
| Broadcom Limited                      | 21        | 3.1%    |
| TP-Link                               | 19        | 2.8%    |
| Ralink Technology                     | 13        | 1.92%   |
| Ralink                                | 12        | 1.77%   |
| Sierra Wireless                       | 4         | 0.59%   |
| Qualcomm                              | 4         | 0.59%   |
| NetGear                               | 2         | 0.29%   |
| Microsoft                             | 2         | 0.29%   |
| Mercucys                              | 2         | 0.29%   |
| Edimax Technology                     | 2         | 0.29%   |
| Dell                                  | 2         | 0.29%   |
| D-Link System                         | 2         | 0.29%   |
| D-Link                                | 2         | 0.29%   |
| Marvell Technology Group              | 1         | 0.15%   |
| IMC Networks                          | 1         | 0.15%   |
| Hewlett-Packard                       | 1         | 0.15%   |
| Cisco Aironet Wireless Communications | 1         | 0.15%   |
| AVM                                   | 1         | 0.15%   |
| ASUSTek Computer                      | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 33        | 4.79%   |
| Intel Wi-Fi 6 AX200                                                  | 26        | 3.77%   |
| Intel Wireless 8265 / 8275                                           | 22        | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 20        | 2.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 18        | 2.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 16        | 2.32%   |
| Intel Wireless 7265                                                  | 15        | 2.18%   |
| Intel Wireless 7260                                                  | 15        | 2.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 15        | 2.18%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 13        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 13        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 12        | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 12        | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 11        | 1.6%    |
| Intel Wi-Fi 6 AX201                                                  | 11        | 1.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 11        | 1.6%    |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 10        | 1.45%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 10        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 9         | 1.31%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 9         | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 9         | 1.31%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 8         | 1.16%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 8         | 1.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 8         | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 8         | 1.16%   |
| Intel Wireless 8260                                                  | 8         | 1.16%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 8         | 1.16%   |
| Intel 700 Series Chipset CNVi WiFi                                   | 8         | 1.16%   |
| Realtek 802.11ac NIC                                                 | 7         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 1.02%   |
| Intel Wireless 3165                                                  | 7         | 1.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 7         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 7         | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 7         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 6         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 6         | 0.87%   |
| Intel Alder Lake-N PCH CNVi WiFi                                     | 6         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 5         | 0.73%   |
| Ralink RT5370 Wireless Adapter                                       | 5         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                      | 5         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 374       | 51.23%  |
| Intel                                  | 214       | 29.32%  |
| Broadcom                               | 36        | 4.93%   |
| Qualcomm Atheros                       | 28        | 3.84%   |
| Marvell Technology Group               | 18        | 2.47%   |
| ASIX Electronics                       | 14        | 1.92%   |
| Nvidia                                 | 9         | 1.23%   |
| Broadcom Limited                       | 6         | 0.82%   |
| Samsung Electronics                    | 5         | 0.68%   |
| MediaTek                               | 5         | 0.68%   |
| JMicron Technology                     | 3         | 0.41%   |
| VIA Technologies                       | 2         | 0.27%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.27%   |
| Lenovo                                 | 2         | 0.27%   |
| Xiaomi                                 | 1         | 0.14%   |
| TP-Link                                | 1         | 0.14%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.14%   |
| QinHeng Electronics                    | 1         | 0.14%   |
| OPPO Electronics                       | 1         | 0.14%   |
| Mellanox Technologies                  | 1         | 0.14%   |
| Hewlett-Packard                        | 1         | 0.14%   |
| DisplayLink                            | 1         | 0.14%   |
| D-Link System                          | 1         | 0.14%   |
| Chelsio Communications                 | 1         | 0.14%   |
| Belkin Components                      | 1         | 0.14%   |
| Aquantia                               | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 259       | 34.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 46        | 6.1%    |
| Realtek RTL8125 2.5GbE Controller                                      | 40        | 5.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35        | 4.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 18        | 2.39%   |
| Intel Ethernet Connection I217-LM                                      | 15        | 1.99%   |
| Intel Ethernet Connection (2) I219-V                                   | 13        | 1.72%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 1.59%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 1.46%   |
| Intel Ethernet Controller I225-V                                       | 9         | 1.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 8         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 8         | 1.06%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.06%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.8%    |
| Intel Ethernet Controller I226-V                                       | 6         | 0.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.66%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 0.66%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 5         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                                  | 5         | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 5         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.53%   |
| Intel Ethernet Connection I217-V                                       | 4         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                  | 4         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 687       | 51.23%  |
| WiFi     | 638       | 47.58%  |
| Modem    | 16        | 1.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 474       | 55.18%  |
| Ethernet | 385       | 44.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 450       | 55.28%  |
| 1     | 330       | 40.54%  |
| 3     | 27        | 3.32%   |
| 0     | 6         | 0.74%   |
| 7     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 547       | 66.06%  |
| Yes  | 281       | 33.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 235       | 42.34%  |
| Realtek Semiconductor           | 73        | 13.15%  |
| IMC Networks                    | 45        | 8.11%   |
| Apple                           | 37        | 6.67%   |
| Qualcomm Atheros Communications | 26        | 4.68%   |
| Broadcom                        | 26        | 4.68%   |
| Cambridge Silicon Radio         | 23        | 4.14%   |
| MediaTek                        | 16        | 2.88%   |
| Lite-On Technology              | 11        | 1.98%   |
| Foxconn / Hon Hai               | 11        | 1.98%   |
| Dell                            | 9         | 1.62%   |
| ASUSTek Computer                | 8         | 1.44%   |
| Hewlett-Packard                 | 7         | 1.26%   |
| Ralink                          | 6         | 1.08%   |
| Realtek                         | 5         | 0.9%    |
| Integrated System Solution      | 3         | 0.54%   |
| USI                             | 2         | 0.36%   |
| TP-Link                         | 2         | 0.36%   |
| Toshiba                         | 2         | 0.36%   |
| Askey Computer                  | 2         | 0.36%   |
| Marvell Semiconductor           | 1         | 0.18%   |
| Logitech                        | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |
| Dynex                           | 1         | 0.18%   |
| D-Link                          | 1         | 0.18%   |
| Unknown                         | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 67        | 12.07%  |
| Realtek Bluetooth Radio                             | 60        | 10.81%  |
| Intel AX201 Bluetooth                               | 38        | 6.85%   |
| Intel Bluetooth Device                              | 37        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 5.41%   |
| Intel AX200 Bluetooth                               | 25        | 4.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 4.14%   |
| IMC Networks Wireless_Device                        | 18        | 3.24%   |
| IMC Networks Bluetooth Radio                        | 17        | 3.06%   |
| MediaTek Wireless_Device                            | 16        | 2.88%   |
| Intel AX210 Bluetooth                               | 16        | 2.88%   |
| Apple Bluetooth Host Controller                     | 16        | 2.88%   |
| Apple Bluetooth USB Host Controller                 | 11        | 1.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 1.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.26%   |
| IMC Networks Bluetooth Device                       | 7         | 1.26%   |
| Apple Bluetooth HCI                                 | 7         | 1.26%   |
| Ralink RT3290 Bluetooth                             | 6         | 1.08%   |
| Dell DW375 Bluetooth Module                         | 6         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.08%   |
| Realtek Bluetooth Radio                             | 5         | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.72%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.54%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.54%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.54%   |
| USI Bluetooth Device                                | 2         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 587       | 53.27%  |
| AMD                                          | 245       | 22.23%  |
| Nvidia                                       | 157       | 14.25%  |
| C-Media Electronics                          | 17        | 1.54%   |
| Creative Technology                          | 10        | 0.91%   |
| Creative Labs                                | 8         | 0.73%   |
| Logitech                                     | 6         | 0.54%   |
| Texas Instruments                            | 5         | 0.45%   |
| Micro Star International                     | 4         | 0.36%   |
| JMTek                                        | 4         | 0.36%   |
| Generalplus Technology                       | 4         | 0.36%   |
| Fujitsu                                      | 4         | 0.36%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.27%   |
| VIA Technologies                             | 3         | 0.27%   |
| GN Netcom                                    | 3         | 0.27%   |
| Walmart                                      | 2         | 0.18%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.18%   |
| Mark of the Unicorn                          | 2         | 0.18%   |
| Jieli Technology                             | 2         | 0.18%   |
| Hewlett-Packard                              | 2         | 0.18%   |
| Focusrite-Novation                           | 2         | 0.18%   |
| DSEA A/S                                     | 2         | 0.18%   |
| BEHRINGER International                      | 2         | 0.18%   |
| ASRock                                       | 2         | 0.18%   |
| ZOOM                                         | 1         | 0.09%   |
| XMOS                                         | 1         | 0.09%   |
| Tenx Technology                              | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.09%   |
| Samson Technologies                          | 1         | 0.09%   |
| Realtek Semiconductor                        | 1         | 0.09%   |
| Razer USA                                    | 1         | 0.09%   |
| M-Audio                                      | 1         | 0.09%   |
| Lenovo                                       | 1         | 0.09%   |
| Kingston Technology                          | 1         | 0.09%   |
| JBL                                          | 1         | 0.09%   |
| Guillemot                                    | 1         | 0.09%   |
| Google                                       | 1         | 0.09%   |
| Earth Computer Technologies                  | 1         | 0.09%   |
| Bluetrum                                     | 1         | 0.09%   |
| Blue Microphones                             | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 115       | 8.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 52        | 3.87%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 48        | 3.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 47        | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 46        | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 42        | 3.12%   |
| AMD Radeon High Definition Audio Controller                                | 38        | 2.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 34        | 2.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29        | 2.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 26        | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23        | 1.71%   |
| Intel Haswell-ULT HD Audio Controller                                      | 22        | 1.64%   |
| Intel 8 Series HD Audio Controller                                         | 22        | 1.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 22        | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 21        | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 21        | 1.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20        | 1.49%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 20        | 1.49%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 19        | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 19        | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 17        | 1.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 1.26%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                    | 17        | 1.26%   |
| Intel 200 Series PCH HD Audio                                              | 16        | 1.19%   |
| AMD FCH Azalia Controller                                                  | 16        | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 14        | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 13        | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 13        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 0.89%   |
| Intel Raptor Lake High Definition Audio Controller                         | 12        | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 11        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.74%   |
| Nvidia GP106 High Definition Audio Controller                              | 9         | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 9         | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 0.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 125       | 21.51%  |
| SK hynix                     | 93        | 16.01%  |
| Kingston                     | 66        | 11.36%  |
| Unknown                      | 63        | 10.84%  |
| Micron Technology            | 55        | 9.47%   |
| Crucial                      | 31        | 5.34%   |
| Corsair                      | 30        | 5.16%   |
| G.Skill                      | 27        | 4.65%   |
| Elpida                       | 12        | 2.07%   |
| A-DATA Technology            | 12        | 2.07%   |
| Unknown                      | 12        | 2.07%   |
| Ramaxel Technology           | 8         | 1.38%   |
| Team                         | 5         | 0.86%   |
| Patriot                      | 5         | 0.86%   |
| Nanya Technology             | 5         | 0.86%   |
| Avant                        | 3         | 0.52%   |
| Unknown (ABCD)               | 2         | 0.34%   |
| Unknown (0x0CC7)             | 2         | 0.34%   |
| Timetec                      | 2         | 0.34%   |
| Silicon Power                | 2         | 0.34%   |
| PNY                          | 2         | 0.34%   |
| Apacer                       | 2         | 0.34%   |
| V-Color                      | 1         | 0.17%   |
| Unknown (87CE)               | 1         | 0.17%   |
| Unknown (0x0E9D)             | 1         | 0.17%   |
| Unknown (0x0B45)             | 1         | 0.17%   |
| Transcend                    | 1         | 0.17%   |
| Super Talent                 | 1         | 0.17%   |
| Smart                        | 1         | 0.17%   |
| Shenzhen Longsys             | 1         | 0.17%   |
| SHARETRONIC                  | 1         | 0.17%   |
| Qimonda                      | 1         | 0.17%   |
| Patriot Memory (PDP Systems) | 1         | 0.17%   |
| Mushkin                      | 1         | 0.17%   |
| Lexar Co Limited             | 1         | 0.17%   |
| Goldkey                      | 1         | 0.17%   |
| GeIL                         | 1         | 0.17%   |
| ASint Technology             | 1         | 0.17%   |
| 48spaces                     | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 12        | 1.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 1.11%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.11%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 6         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 5         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 4         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.63%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s             | 4         | 0.63%   |
| Crucial RAM CT16G4SFRA32A.C16FT 16GB SODIMM DDR4 3200MT/s        | 4         | 0.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.47%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.47%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 1GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.47%   |
| Samsung RAM M471A1K43BB0-CPB 8GiB SODIMM DDR4 2133MT/s           | 3         | 0.47%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.47%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 3         | 0.47%   |
| Kingston RAM 9905700-122.A00G 16GB SODIMM DDR4 3200MT/s          | 3         | 0.47%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 2         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 2         | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.32%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 2         | 0.32%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 2         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 2         | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.32%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                             | 2         | 0.32%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 0.32%   |
| Unknown (0x0CC7) RAM DDR4 NB 8G 3200 8GB SODIMM DDR4 3200MT/s    | 2         | 0.32%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 2         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 206       | 40.31%  |
| DDR3    | 143       | 27.98%  |
| DDR2    | 39        | 7.63%   |
| DDR5    | 34        | 6.65%   |
| LPDDR5  | 27        | 5.28%   |
| SDRAM   | 21        | 4.11%   |
| LPDDR4  | 15        | 2.94%   |
| Unknown | 9         | 1.76%   |
| DDR     | 8         | 1.57%   |
| LPDDR3  | 6         | 1.17%   |
| DRAM    | 2         | 0.39%   |
| RAM     | 1         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 310       | 61.63%  |
| DIMM         | 144       | 28.63%  |
| Row Of Chips | 42        | 8.35%   |
| Chip         | 4         | 0.8%    |
| Unknown      | 2         | 0.4%    |
| RIMM         | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 177       | 31.89%  |
| 4096  | 144       | 25.95%  |
| 16384 | 88        | 15.86%  |
| 2048  | 74        | 13.33%  |
| 1024  | 33        | 5.95%   |
| 32768 | 27        | 4.86%   |
| 512   | 8         | 1.44%   |
| 49152 | 4         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 100       | 18.38%  |
| 1600    | 95        | 17.46%  |
| 2667    | 46        | 8.46%   |
| 1333    | 25        | 4.6%    |
| 6400    | 24        | 4.41%   |
| 2133    | 23        | 4.23%   |
| Unknown | 23        | 4.23%   |
| 2400    | 22        | 4.04%   |
| 667     | 20        | 3.68%   |
| 5600    | 17        | 3.13%   |
| 3600    | 17        | 3.13%   |
| 1334    | 11        | 2.02%   |
| 533     | 9         | 1.65%   |
| 1867    | 8         | 1.47%   |
| 1067    | 7         | 1.29%   |
| 6000    | 6         | 1.1%    |
| 4800    | 6         | 1.1%    |
| 2048    | 6         | 1.1%    |
| 800     | 6         | 1.1%    |
| 4267    | 5         | 0.92%   |
| 4199    | 5         | 0.92%   |
| 3266    | 5         | 0.92%   |
| 2800    | 5         | 0.92%   |
| 1066    | 5         | 0.92%   |
| 8400    | 4         | 0.74%   |
| 3733    | 4         | 0.74%   |
| 3400    | 4         | 0.74%   |
| 1866    | 4         | 0.74%   |
| 6200    | 3         | 0.55%   |
| 3000    | 3         | 0.55%   |
| 5500    | 2         | 0.37%   |
| 4266    | 2         | 0.37%   |
| 2666    | 2         | 0.37%   |
| 2448    | 2         | 0.37%   |
| 1800    | 2         | 0.37%   |
| 7467    | 1         | 0.18%   |
| 7400    | 1         | 0.18%   |
| 7200    | 1         | 0.18%   |
| 4000    | 1         | 0.18%   |
| 3500    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 47.83%  |
| Canon                 | 5         | 21.74%  |
| Seiko Epson           | 3         | 13.04%  |
| Lexmark International | 2         | 8.7%    |
| Samsung Electronics   | 1         | 4.35%   |
| Brother Industries    | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP ENVY 5000 series                    | 2         | 8.7%    |
| Seiko Epson L210 Series                | 1         | 4.35%   |
| Seiko Epson L1250 Series               | 1         | 4.35%   |
| Seiko Epson ET-2820 Series             | 1         | 4.35%   |
| Samsung M283x Series                   | 1         | 4.35%   |
| Lexmark International Printing Support | 1         | 4.35%   |
| Lexmark International MX310dn          | 1         | 4.35%   |
| HP OfficeJet Pro 7740 series           | 1         | 4.35%   |
| HP LaserJet P2015 series               | 1         | 4.35%   |
| HP LaserJet P1005                      | 1         | 4.35%   |
| HP LaserJet M14-M17                    | 1         | 4.35%   |
| HP HP LaserJet Pro M404-M405           | 1         | 4.35%   |
| HP ENVY 4520 series                    | 1         | 4.35%   |
| HP DeskJet F4200 series                | 1         | 4.35%   |
| HP DeskJet 4100 series                 | 1         | 4.35%   |
| HP Color LaserJet CP2025dn             | 1         | 4.35%   |
| Canon TS9100 series                    | 1         | 4.35%   |
| Canon TR4600 series                    | 1         | 4.35%   |
| Canon PIXMA MG3500 Series              | 1         | 4.35%   |
| Canon LiDE 300                         | 1         | 4.35%   |
| Canon D570 UFRII LT                    | 1         | 4.35%   |
| Brother MFC-T4500DW                    | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 33.33%  |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]  | 1         | 33.33%  |
| Canon CanoScan LiDE 210                     | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 114       | 25.05%  |
| IMC Networks                           | 51        | 11.21%  |
| Microdia                               | 29        | 6.37%   |
| Sunplus Innovation Technology          | 28        | 6.15%   |
| Bison Electronics                      | 27        | 5.93%   |
| Realtek Semiconductor                  | 25        | 5.49%   |
| Quanta                                 | 25        | 5.49%   |
| Apple                                  | 22        | 4.84%   |
| Logitech                               | 21        | 4.62%   |
| Luxvisions Innotech Limited            | 18        | 3.96%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.3%    |
| Suyin                                  | 7         | 1.54%   |
| Sonix Technology                       | 7         | 1.54%   |
| ShineTech                              | 6         | 1.32%   |
| Syntek                                 | 5         | 1.1%    |
| Silicon Motion                         | 5         | 1.1%    |
| Ricoh                                  | 5         | 1.1%    |
| Lite-On Technology                     | 5         | 1.1%    |
| Alcor Micro                            | 5         | 1.1%    |
| Microsoft                              | 4         | 0.88%   |
| MacroSilicon                           | 4         | 0.88%   |
| SunplusIT                              | 2         | 0.44%   |
| Shine-optics                           | 2         | 0.44%   |
| Samsung Electronics                    | 2         | 0.44%   |
| kingcome                               | 2         | 0.44%   |
| Acer                                   | 2         | 0.44%   |
| Z-Star Microelectronics                | 1         | 0.22%   |
| Web Camera                             | 1         | 0.22%   |
| OmniVision Technologies                | 1         | 0.22%   |
| Magic Control Technology               | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |
| KYE Systems (Mouse Systems)            | 1         | 0.22%   |
| Jieli Technology                       | 1         | 0.22%   |
| HYGD-221208-J                          | 1         | 0.22%   |
| HYGD-220831-A                          | 1         | 0.22%   |
| globaloptics                           | 1         | 0.22%   |
| Genesys Logic                          | 1         | 0.22%   |
| Generalplus Technology                 | 1         | 0.22%   |
| Framework                              | 1         | 0.22%   |
| Elgato Systems                         | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony integrated camera                               | 33        | 7.14%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 18        | 3.9%    |
| Realtek Integrated_Webcam_HD                            | 11        | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 11        | 2.38%   |
| Chicony HD WebCam                                       | 11        | 2.38%   |
| Bison Integrated Camera                                 | 10        | 2.16%   |
| IMC Networks Integrated Camera                          | 9         | 1.95%   |
| Microdia Integrated_Webcam_HD                           | 8         | 1.73%   |
| Apple Built-in iSight                                   | 7         | 1.52%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 6         | 1.3%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 6         | 1.3%    |
| Apple FaceTime HD Camera (Built-in)                     | 6         | 1.3%    |
| Chicony USB2.0 HD UVC WebCam                            | 5         | 1.08%   |
| Chicony HP HD Camera                                    | 5         | 1.08%   |
| Chicony FJ Camera                                       | 5         | 1.08%   |
| Syntek Integrated Camera                                | 4         | 0.87%   |
| Sonix USB2.0 HD UVC WebCam                              | 4         | 0.87%   |
| Quanta VGA Webcam                                       | 4         | 0.87%   |
| Quanta HP TrueVision HD Camera                          | 4         | 0.87%   |
| Quanta HP HD Camera                                     | 4         | 0.87%   |
| Luxvisions Innotech Limited Integrated Camera           | 4         | 0.87%   |
| Logitech HD Pro Webcam C920                             | 4         | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                         | 4         | 0.87%   |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 0.87%   |
| Chicony HP Wide Vision HD Camera                        | 4         | 0.87%   |
| Chicony HP Truevision HD                                | 4         | 0.87%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 4         | 0.87%   |
| Sunplus USB 2.0 Camera                                  | 3         | 0.65%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 0.65%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 0.65%   |
| Microdia Integrated_Webcam_FHD                          | 3         | 0.65%   |
| MacroSilicon USB Video                                  | 3         | 0.65%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 3         | 0.65%   |
| Lite-On Integrated Camera                               | 3         | 0.65%   |
| IMC Networks Integrated Webcam                          | 3         | 0.65%   |
| Chicony Lenovo EasyCamera                               | 3         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 0.65%   |
| Bison SunplusIT Integrated Camera                       | 3         | 0.65%   |
| Bison HD Webcam                                         | 3         | 0.65%   |
| Apple FaceTime HD Camera                                | 3         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 30.23%  |
| Synaptics                  | 24        | 27.91%  |
| Shenzhen Goodix Technology | 11        | 12.79%  |
| Upek                       | 6         | 6.98%   |
| Elan Microelectronics      | 6         | 6.98%   |
| STMicroelectronics         | 5         | 5.81%   |
| LighTuning Technology      | 4         | 4.65%   |
| AuthenTec                  | 3         | 3.49%   |
| Microsoft                  | 1         | 1.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 8.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 6.98%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 6.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 5.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 5.81%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 5.81%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 4.65%   |
| Elan ELAN:ARM-M4                                                           | 4         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 3.49%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 3.49%   |
| Synaptics UWP WBDI Device                                                  | 3         | 3.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 3.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.33%   |
| Validity Sensors VFS491                                                    | 2         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.33%   |
| Synaptics UWP WBDI                                                         | 2         | 2.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 2.33%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.16%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.16%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.16%   |
| Synaptics WBDI                                                             | 1         | 1.16%   |
| Synaptics  WBDI                                                            | 1         | 1.16%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.16%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.16%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.16%   |
| Microsoft Fingerprint Reader                                               | 1         | 1.16%   |
| LighTuning Fingerprint Sensor                                              | 1         | 1.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.16%   |
| AuthenTec AES3500 TruePrint Sensor                                         | 1         | 1.16%   |
| AuthenTec AES2810                                                          | 1         | 1.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 40%     |
| Alcor Micro | 11        | 27.5%   |
| O2 Micro    | 4         | 10%     |
| Lenovo      | 4         | 10%     |
| Upek        | 3         | 7.5%    |
| Swissbit    | 1         | 2.5%    |
| OmniKey     | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 27.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 12.5%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 7.5%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 7.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 7.5%    |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 7.5%    |
| Broadcom 58200                                                               | 3         | 7.5%    |
| Broadcom 5880                                                                | 2         | 5%      |
| Swissbit iShield Key FIDO2                                                   | 1         | 2.5%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 2.5%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 558       | 67.72%  |
| 1     | 219       | 26.58%  |
| 2     | 41        | 4.98%   |
| 3     | 5         | 0.61%   |
| 5     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 85        | 27.07%  |
| Net/wireless             | 60        | 19.11%  |
| Graphics card            | 54        | 17.2%   |
| Chipcard                 | 38        | 12.1%   |
| Multimedia controller    | 28        | 8.92%   |
| Camera                   | 10        | 3.18%   |
| Bluetooth                | 10        | 3.18%   |
| Storage                  | 6         | 1.91%   |
| Communication controller | 6         | 1.91%   |
| Unassigned class         | 4         | 1.27%   |
| Network                  | 4         | 1.27%   |
| Card reader              | 3         | 0.96%   |
| Sound                    | 2         | 0.64%   |
| Tv card                  | 1         | 0.32%   |
| Storage/nvme             | 1         | 0.32%   |
| Net/ethernet             | 1         | 0.32%   |
| Dvb card                 | 1         | 0.32%   |

