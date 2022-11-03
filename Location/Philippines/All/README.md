Linux in Philippines - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Philippines/Desktop/README.md) and [notebooks](/Location/Philippines/Notebook/README.md).

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

Total: 685

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [452ec1a1ee](https://linux-hardware.org/?probe=452ec1a1ee) | Nov 02, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [881cd60670](https://linux-hardware.org/?probe=881cd60670) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e9ce57f1c1](https://linux-hardware.org/?probe=e9ce57f1c1) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f91daeac73](https://linux-hardware.org/?probe=f91daeac73) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [fc0a9a6b24](https://linux-hardware.org/?probe=fc0a9a6b24) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | Notebook    | [23adba19e0](https://linux-hardware.org/?probe=23adba19e0) | Oct 15, 2022 |
| Lenovo        | ThinkPad X230 2325CF6       | Notebook    | [622d37f892](https://linux-hardware.org/?probe=622d37f892) | Oct 15, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [5eafc7c12c](https://linux-hardware.org/?probe=5eafc7c12c) | Oct 13, 2022 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [1eb06e8e12](https://linux-hardware.org/?probe=1eb06e8e12) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [9f52e46640](https://linux-hardware.org/?probe=9f52e46640) | Oct 11, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa7d067a6f](https://linux-hardware.org/?probe=aa7d067a6f) | Oct 11, 2022 |
| Toshiba       | TECRA Z50-C                 | Notebook    | [fc6e63a30a](https://linux-hardware.org/?probe=fc6e63a30a) | Oct 11, 2022 |
| HP            | ENVY Sleekbook 4            | Notebook    | [c14c5b1ee3](https://linux-hardware.org/?probe=c14c5b1ee3) | Oct 10, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [379f85dfb3](https://linux-hardware.org/?probe=379f85dfb3) | Oct 09, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [f02be8db4c](https://linux-hardware.org/?probe=f02be8db4c) | Oct 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [ddb0e3fb81](https://linux-hardware.org/?probe=ddb0e3fb81) | Oct 05, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [700c5cc2bc](https://linux-hardware.org/?probe=700c5cc2bc) | Oct 05, 2022 |
| HP            | ENVY Sleekbook 4            | Notebook    | [0b820a1c7e](https://linux-hardware.org/?probe=0b820a1c7e) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [4ba3e28201](https://linux-hardware.org/?probe=4ba3e28201) | Oct 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Dell          | Latitude 5490               | Notebook    | [4c59654ea9](https://linux-hardware.org/?probe=4c59654ea9) | Sep 29, 2022 |
| Acer          | Aspire E3-111               | Notebook    | [6646e09597](https://linux-hardware.org/?probe=6646e09597) | Sep 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| Acer          | AOD257                      | Notebook    | [35ca1c0b33](https://linux-hardware.org/?probe=35ca1c0b33) | Sep 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [6c34753f58](https://linux-hardware.org/?probe=6c34753f58) | Sep 22, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4d460404c8](https://linux-hardware.org/?probe=4d460404c8) | Sep 16, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [0553290711](https://linux-hardware.org/?probe=0553290711) | Sep 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4b5a146dc9](https://linux-hardware.org/?probe=4b5a146dc9) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [34c1beb103](https://linux-hardware.org/?probe=34c1beb103) | Sep 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [7ce5d8e865](https://linux-hardware.org/?probe=7ce5d8e865) | Sep 12, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ec5f57ab65](https://linux-hardware.org/?probe=ec5f57ab65) | Sep 12, 2022 |
| Biostar       | A780L3B                     | Desktop     | [bc83f32ddf](https://linux-hardware.org/?probe=bc83f32ddf) | Sep 12, 2022 |
| Biostar       | A780L3B                     | Desktop     | [61057dc040](https://linux-hardware.org/?probe=61057dc040) | Sep 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ecadc5740](https://linux-hardware.org/?probe=1ecadc5740) | Sep 11, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [40f5cb1550](https://linux-hardware.org/?probe=40f5cb1550) | Sep 10, 2022 |
| Google        | Treeya                      | Notebook    | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Biostar       | A780L3B                     | Desktop     | [6463bcc136](https://linux-hardware.org/?probe=6463bcc136) | Sep 10, 2022 |
| Biostar       | A780L3B                     | Desktop     | [f65db263d7](https://linux-hardware.org/?probe=f65db263d7) | Sep 10, 2022 |
| Acer          | Aspire A314-22G             | Notebook    | [b6f9c0a0e7](https://linux-hardware.org/?probe=b6f9c0a0e7) | Sep 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [b77aa249c8](https://linux-hardware.org/?probe=b77aa249c8) | Sep 09, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [dc69b9dde6](https://linux-hardware.org/?probe=dc69b9dde6) | Sep 09, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [051ea3b002](https://linux-hardware.org/?probe=051ea3b002) | Sep 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [85d4f11486](https://linux-hardware.org/?probe=85d4f11486) | Sep 01, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [7d69c012fb](https://linux-hardware.org/?probe=7d69c012fb) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| HP            | 83F3                        | Desktop     | [71d62174e2](https://linux-hardware.org/?probe=71d62174e2) | Aug 27, 2022 |
| HP            | 1850                        | Desktop     | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [d9ff6dc8b4](https://linux-hardware.org/?probe=d9ff6dc8b4) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [65b569c23c](https://linux-hardware.org/?probe=65b569c23c) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| realme        | RMNBXXXX                    | Notebook    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| HP            | Laptop 14-bs1xx             | Notebook    | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [0ec4449fe2](https://linux-hardware.org/?probe=0ec4449fe2) | Aug 09, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [49ab4e0197](https://linux-hardware.org/?probe=49ab4e0197) | Aug 08, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [7a37d5e6a5](https://linux-hardware.org/?probe=7a37d5e6a5) | Aug 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [db237c843c](https://linux-hardware.org/?probe=db237c843c) | Aug 06, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [5251e7868a](https://linux-hardware.org/?probe=5251e7868a) | Aug 06, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [93ae3bfcfd](https://linux-hardware.org/?probe=93ae3bfcfd) | Aug 02, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [64da165357](https://linux-hardware.org/?probe=64da165357) | Aug 01, 2022 |
| Lenovo        | ThinkPad E590 20NB0032CD    | Notebook    | [502b0eeb39](https://linux-hardware.org/?probe=502b0eeb39) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a0e19ce405](https://linux-hardware.org/?probe=a0e19ce405) | Jul 26, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [f47a0ecbf5](https://linux-hardware.org/?probe=f47a0ecbf5) | Jul 25, 2022 |
| MSI           | CX62 6QD                    | Notebook    | [d0c23fefca](https://linux-hardware.org/?probe=d0c23fefca) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [37521f84c8](https://linux-hardware.org/?probe=37521f84c8) | Jul 20, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [2b7a37d662](https://linux-hardware.org/?probe=2b7a37d662) | Jul 16, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [24c803a5fc](https://linux-hardware.org/?probe=24c803a5fc) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| YANYU         | EPIC-C19                    | Desktop     | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [b6a7451086](https://linux-hardware.org/?probe=b6a7451086) | Jul 11, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [b9c939b2e2](https://linux-hardware.org/?probe=b9c939b2e2) | Jul 09, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [88cc242e02](https://linux-hardware.org/?probe=88cc242e02) | Jul 09, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [264b084b00](https://linux-hardware.org/?probe=264b084b00) | Jul 08, 2022 |
| Acer          | Aspire E5-473G              | Notebook    | [11b488a036](https://linux-hardware.org/?probe=11b488a036) | Jul 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [c9d2a76068](https://linux-hardware.org/?probe=c9d2a76068) | Jul 03, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [b7fedc25e4](https://linux-hardware.org/?probe=b7fedc25e4) | Jul 01, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [78eaeff700](https://linux-hardware.org/?probe=78eaeff700) | Jun 27, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [c23e943030](https://linux-hardware.org/?probe=c23e943030) | Jun 21, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [47f765c61f](https://linux-hardware.org/?probe=47f765c61f) | Jun 14, 2022 |
| MSI           | H81M-E33                    | Desktop     | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| MSI           | H81M-E33                    | Desktop     | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [512fb81a9b](https://linux-hardware.org/?probe=512fb81a9b) | May 31, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| MSI           | MS-7717                     | Desktop     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | Desktop     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [0656adeb11](https://linux-hardware.org/?probe=0656adeb11) | May 24, 2022 |
| Dell          | Vostro 5515                 | Notebook    | [b884e51280](https://linux-hardware.org/?probe=b884e51280) | May 21, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | Notebook    | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [e6f35b116a](https://linux-hardware.org/?probe=e6f35b116a) | May 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [debbc95647](https://linux-hardware.org/?probe=debbc95647) | May 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [915b95cae4](https://linux-hardware.org/?probe=915b95cae4) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [27f577ec86](https://linux-hardware.org/?probe=27f577ec86) | May 10, 2022 |
| ECS           | A68M-C4DL                   | Desktop     | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5b877349c1](https://linux-hardware.org/?probe=5b877349c1) | May 09, 2022 |
| HP            | 212A                        | Desktop     | [acd660910f](https://linux-hardware.org/?probe=acd660910f) | May 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [07ed7fd709](https://linux-hardware.org/?probe=07ed7fd709) | May 08, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | Notebook    | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [74323309f1](https://linux-hardware.org/?probe=74323309f1) | Apr 20, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | Notebook    | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | Notebook    | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Shenzhen B... | NBPC1078                    | Tablet      | [33e297566b](https://linux-hardware.org/?probe=33e297566b) | Mar 30, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [03b7f74d31](https://linux-hardware.org/?probe=03b7f74d31) | Mar 29, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [42e921877b](https://linux-hardware.org/?probe=42e921877b) | Mar 29, 2022 |
| HP            | 2B38                        | Desktop     | [99fd9bb200](https://linux-hardware.org/?probe=99fd9bb200) | Mar 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| MSI           | MS-7619                     | Desktop     | [65c73f26b0](https://linux-hardware.org/?probe=65c73f26b0) | Mar 22, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [111cf21b7f](https://linux-hardware.org/?probe=111cf21b7f) | Mar 21, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [95373e24b7](https://linux-hardware.org/?probe=95373e24b7) | Mar 16, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| MSI           | H510M PRO-E                 | Desktop     | [ad5840ceb1](https://linux-hardware.org/?probe=ad5840ceb1) | Mar 14, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [bd9b6ec157](https://linux-hardware.org/?probe=bd9b6ec157) | Mar 11, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [946300c067](https://linux-hardware.org/?probe=946300c067) | Mar 10, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [503d10d676](https://linux-hardware.org/?probe=503d10d676) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0K9T56 A00                  | All in one  | [206a6faf1c](https://linux-hardware.org/?probe=206a6faf1c) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [a1b757e234](https://linux-hardware.org/?probe=a1b757e234) | Mar 05, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [4f6714e804](https://linux-hardware.org/?probe=4f6714e804) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [70f59ecacf](https://linux-hardware.org/?probe=70f59ecacf) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [2bc13ee0e2](https://linux-hardware.org/?probe=2bc13ee0e2) | Feb 28, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [a8334fb3c3](https://linux-hardware.org/?probe=a8334fb3c3) | Feb 28, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [f269ebd3a2](https://linux-hardware.org/?probe=f269ebd3a2) | Feb 28, 2022 |
| Acer          | AOD270                      | Notebook    | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | Notebook    | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [3a6147e5db](https://linux-hardware.org/?probe=3a6147e5db) | Feb 16, 2022 |
| HP            | Unknown                     | Notebook    | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | Notebook    | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a25fea3795](https://linux-hardware.org/?probe=a25fea3795) | Feb 12, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [da8ce5d5b5](https://linux-hardware.org/?probe=da8ce5d5b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | Notebook    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [56bbe3562f](https://linux-hardware.org/?probe=56bbe3562f) | Jan 15, 2022 |
| HP            | Notebook                    | Notebook    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [b04287afb1](https://linux-hardware.org/?probe=b04287afb1) | Jan 11, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [266128f234](https://linux-hardware.org/?probe=266128f234) | Jan 06, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [900b250e00](https://linux-hardware.org/?probe=900b250e00) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | Notebook    | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [e0b5bc37a4](https://linux-hardware.org/?probe=e0b5bc37a4) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [60daadb8b0](https://linux-hardware.org/?probe=60daadb8b0) | Dec 18, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| EMAXX TECH... | EMX-A55GT-iCafe V1.0        | Desktop     | [d6d799c3d8](https://linux-hardware.org/?probe=d6d799c3d8) | Nov 28, 2021 |
| Dell          | MXG061                      | Notebook    | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [31e306a09d](https://linux-hardware.org/?probe=31e306a09d) | Nov 26, 2021 |
| Sony          | SVT13115FGS                 | Notebook    | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | Notebook    | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [2302fee654](https://linux-hardware.org/?probe=2302fee654) | Nov 09, 2021 |
| MSI           | Z97 GAMING 3                | Desktop     | [249f25308e](https://linux-hardware.org/?probe=249f25308e) | Nov 08, 2021 |
| MSI           | B350M PRO-VDH               | Desktop     | [7e77378fb3](https://linux-hardware.org/?probe=7e77378fb3) | Nov 07, 2021 |
| HP            | Unknown                     | Notebook    | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | Notebook    | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | Notebook    | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| ECS           | G41T-R3                     | Desktop     | [892069341e](https://linux-hardware.org/?probe=892069341e) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [0ac8e061f1](https://linux-hardware.org/?probe=0ac8e061f1) | Oct 31, 2021 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [655000678d](https://linux-hardware.org/?probe=655000678d) | Oct 30, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | Notebook    | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | Notebook    | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | Notebook    | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [cb279cfeaf](https://linux-hardware.org/?probe=cb279cfeaf) | Oct 09, 2021 |
| EMAXX TECH... | EMX-MCP61D3-iCafe V2.0      | Desktop     | [2444a742a8](https://linux-hardware.org/?probe=2444a742a8) | Oct 09, 2021 |
| HP            | Unknown                     | Notebook    | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e584636758](https://linux-hardware.org/?probe=e584636758) | Oct 04, 2021 |
| HP            | 14                          | Notebook    | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | Notebook    | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [9782c6bff5](https://linux-hardware.org/?probe=9782c6bff5) | Sep 25, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [a9a92c303c](https://linux-hardware.org/?probe=a9a92c303c) | Sep 24, 2021 |
| HP            | G60                         | Notebook    | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | Notebook    | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [54cc0ff25b](https://linux-hardware.org/?probe=54cc0ff25b) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | Notebook    | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [4f8d90f8ef](https://linux-hardware.org/?probe=4f8d90f8ef) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | Notebook    | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [9b620ade68](https://linux-hardware.org/?probe=9b620ade68) | Sep 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [f6388fb1b0](https://linux-hardware.org/?probe=f6388fb1b0) | Sep 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [a19fc44e26](https://linux-hardware.org/?probe=a19fc44e26) | Sep 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | Notebook    | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | Notebook    | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [8ea19cfa9d](https://linux-hardware.org/?probe=8ea19cfa9d) | Aug 25, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | Notebook    | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [07f3a8a2c9](https://linux-hardware.org/?probe=07f3a8a2c9) | Aug 13, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Unknown       | Ionics Carrier Board Adv... | Desktop     | [62a47a18c2](https://linux-hardware.org/?probe=62a47a18c2) | Aug 12, 2021 |
| Apple         | MacBookAir4,1               | Notebook    | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [a595ba80d3](https://linux-hardware.org/?probe=a595ba80d3) | Aug 08, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [90e7e1e008](https://linux-hardware.org/?probe=90e7e1e008) | Aug 05, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [4bf2729f88](https://linux-hardware.org/?probe=4bf2729f88) | Aug 04, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [57f0c24236](https://linux-hardware.org/?probe=57f0c24236) | Aug 03, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [4d9f134679](https://linux-hardware.org/?probe=4d9f134679) | Jul 30, 2021 |
| Biostar       | H110MHV3                    | Desktop     | [28344398db](https://linux-hardware.org/?probe=28344398db) | Jul 27, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | Notebook    | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Inspiron 7373               | Convertible | [5514ed070a](https://linux-hardware.org/?probe=5514ed070a) | Jul 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [2151a0b75d](https://linux-hardware.org/?probe=2151a0b75d) | Jul 13, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8165fc4d95](https://linux-hardware.org/?probe=8165fc4d95) | Jul 06, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | Notebook    | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [63055a9c60](https://linux-hardware.org/?probe=63055a9c60) | Jun 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [00ef418c43](https://linux-hardware.org/?probe=00ef418c43) | Jun 24, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Biostar       | A320MH                      | Desktop     | [16e2552ccc](https://linux-hardware.org/?probe=16e2552ccc) | Jun 20, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | Notebook    | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | Notebook    | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Dell          | 040DDP A01                  | Desktop     | [8a9bdad1fd](https://linux-hardware.org/?probe=8a9bdad1fd) | Jun 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [cc3c9e3798](https://linux-hardware.org/?probe=cc3c9e3798) | Jun 08, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [10ccc894a1](https://linux-hardware.org/?probe=10ccc894a1) | Jun 07, 2021 |
| Toshiba       | Satellite L515              | Notebook    | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| HP            | 82A5                        | Mini pc     | [08b98b6a88](https://linux-hardware.org/?probe=08b98b6a88) | May 29, 2021 |
| NEC Comput... | PC-VK25MXZCB                | Notebook    | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e31519274b](https://linux-hardware.org/?probe=e31519274b) | May 22, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [523ced455c](https://linux-hardware.org/?probe=523ced455c) | May 22, 2021 |
| Acer          | Aspire X1900                | Desktop     | [c4e0203ed9](https://linux-hardware.org/?probe=c4e0203ed9) | May 19, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [a14cf2a48e](https://linux-hardware.org/?probe=a14cf2a48e) | May 18, 2021 |
| Dell          | Inspiron 7373               | Convertible | [e4ffc93c6a](https://linux-hardware.org/?probe=e4ffc93c6a) | May 16, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | Notebook    | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | Notebook    | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [8467906058](https://linux-hardware.org/?probe=8467906058) | May 04, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [55bfc7d608](https://linux-hardware.org/?probe=55bfc7d608) | May 03, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| ASUSTek       | EX-B365M-V5                 | Desktop     | [c169d54571](https://linux-hardware.org/?probe=c169d54571) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b866ec6925](https://linux-hardware.org/?probe=b866ec6925) | Apr 20, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [ef9ba18b59](https://linux-hardware.org/?probe=ef9ba18b59) | Apr 11, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f66e7cbdfd](https://linux-hardware.org/?probe=f66e7cbdfd) | Apr 11, 2021 |
| HP            | Notebook                    | Notebook    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [23fdbd4caa](https://linux-hardware.org/?probe=23fdbd4caa) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d1b688c0a9](https://linux-hardware.org/?probe=d1b688c0a9) | Mar 31, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | Notebook    | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53f5f073d5](https://linux-hardware.org/?probe=53f5f073d5) | Mar 18, 2021 |
| MSI           | Z270 GAMING M7              | Desktop     | [b72439b299](https://linux-hardware.org/?probe=b72439b299) | Mar 17, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d9ec96bf45](https://linux-hardware.org/?probe=d9ec96bf45) | Mar 15, 2021 |
| Gigabyte      | GA-MA78GM-US2H              | Desktop     | [0f6037a19e](https://linux-hardware.org/?probe=0f6037a19e) | Mar 14, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | Notebook    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| eMachines     | eM250                       | Notebook    | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | Notebook    | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | Notebook    | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| HP            | 82A5                        | Mini pc     | [fa16fba963](https://linux-hardware.org/?probe=fa16fba963) | Feb 28, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c627833398](https://linux-hardware.org/?probe=c627833398) | Feb 23, 2021 |
| Acer          | TravelMate B113             | Notebook    | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3582928f83](https://linux-hardware.org/?probe=3582928f83) | Feb 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d392637e95](https://linux-hardware.org/?probe=d392637e95) | Feb 20, 2021 |
| Lenovo        | G450 20022                  | Notebook    | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | Notebook    | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | Notebook    | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| AMD           | A88                         | Desktop     | [11ecb6d298](https://linux-hardware.org/?probe=11ecb6d298) | Feb 14, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [3e5d4f837a](https://linux-hardware.org/?probe=3e5d4f837a) | Feb 10, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [6feab903f8](https://linux-hardware.org/?probe=6feab903f8) | Feb 05, 2021 |
| JOOYON        | IPM41-D3G                   | Desktop     | [5fa1dabba9](https://linux-hardware.org/?probe=5fa1dabba9) | Feb 05, 2021 |
| Acer          | TravelMate B113             | Notebook    | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Dell          | 0JP3NX A00                  | Desktop     | [1f5d53a4a2](https://linux-hardware.org/?probe=1f5d53a4a2) | Feb 03, 2021 |
| QTQD          | Unknown                     | Desktop     | [2912607416](https://linux-hardware.org/?probe=2912607416) | Jan 27, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [76f0201d14](https://linux-hardware.org/?probe=76f0201d14) | Jan 26, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [795b4f4c7b](https://linux-hardware.org/?probe=795b4f4c7b) | Jan 26, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [6e4545c96a](https://linux-hardware.org/?probe=6e4545c96a) | Jan 23, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [603bb5d8e4](https://linux-hardware.org/?probe=603bb5d8e4) | Jan 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [c108942b4e](https://linux-hardware.org/?probe=c108942b4e) | Jan 19, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d8720f796](https://linux-hardware.org/?probe=9d8720f796) | Jan 19, 2021 |
| Acer          | Aspire X1900                | Desktop     | [d0a0250e62](https://linux-hardware.org/?probe=d0a0250e62) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [15b8546bd4](https://linux-hardware.org/?probe=15b8546bd4) | Jan 11, 2021 |
| Gigabyte      | AM1M-S2P                    | Desktop     | [433295603d](https://linux-hardware.org/?probe=433295603d) | Jan 09, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [3f75d5f2e1](https://linux-hardware.org/?probe=3f75d5f2e1) | Jan 07, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [e6533b7b24](https://linux-hardware.org/?probe=e6533b7b24) | Jan 07, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [91ccfb9b5a](https://linux-hardware.org/?probe=91ccfb9b5a) | Jan 06, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [b5fa895a91](https://linux-hardware.org/?probe=b5fa895a91) | Jan 05, 2021 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5d05e8d607](https://linux-hardware.org/?probe=5d05e8d607) | Jan 04, 2021 |
| Toshiba       | dynabook R73/W              | Notebook    | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [031ad52398](https://linux-hardware.org/?probe=031ad52398) | Jan 01, 2021 |
| ASUSTek       | EX-H310M-V3 R2.0            | Desktop     | [11a5fd5bae](https://linux-hardware.org/?probe=11a5fd5bae) | Dec 30, 2020 |
| MSI           | IONA                        | Desktop     | [bfb84589dd](https://linux-hardware.org/?probe=bfb84589dd) | Dec 28, 2020 |
| MSI           | IONA                        | Desktop     | [0ec5c79eb8](https://linux-hardware.org/?probe=0ec5c79eb8) | Dec 26, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| ECS           | H110M-C3D/C3V               | Desktop     | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| ASRock        | N68-S3                      | Desktop     | [bfa6bd97d5](https://linux-hardware.org/?probe=bfa6bd97d5) | Dec 23, 2020 |
| MSI           | MS-7541                     | Desktop     | [a6e134920c](https://linux-hardware.org/?probe=a6e134920c) | Dec 22, 2020 |
| MSI           | MS-7541                     | Desktop     | [a44769cfd2](https://linux-hardware.org/?probe=a44769cfd2) | Dec 22, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | Notebook    | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [d186067403](https://linux-hardware.org/?probe=d186067403) | Dec 17, 2020 |
| ASRock        | N68-S3                      | Desktop     | [1d3067d8cb](https://linux-hardware.org/?probe=1d3067d8cb) | Dec 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | Notebook    | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [d942ed05b5](https://linux-hardware.org/?probe=d942ed05b5) | Dec 13, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| HP            | 8061                        | Desktop     | [0f0bc8b49a](https://linux-hardware.org/?probe=0f0bc8b49a) | Dec 04, 2020 |
| HP            | 8061                        | Desktop     | [a63c8237f1](https://linux-hardware.org/?probe=a63c8237f1) | Dec 04, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [57afeee773](https://linux-hardware.org/?probe=57afeee773) | Nov 30, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | Notebook    | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | Notebook    | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | Notebook    | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | Notebook    | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [354202e98e](https://linux-hardware.org/?probe=354202e98e) | Nov 19, 2020 |
| HP            | Unknown                     | Notebook    | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [f86e0d2af5](https://linux-hardware.org/?probe=f86e0d2af5) | Nov 11, 2020 |
| HP            | 3031h                       | Desktop     | [fb54f48959](https://linux-hardware.org/?probe=fb54f48959) | Nov 10, 2020 |
| HP            | 8061                        | Desktop     | [7936b223e9](https://linux-hardware.org/?probe=7936b223e9) | Nov 10, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [2c9a8f0838](https://linux-hardware.org/?probe=2c9a8f0838) | Nov 08, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [c812c2b6f9](https://linux-hardware.org/?probe=c812c2b6f9) | Nov 07, 2020 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [e21be2124d](https://linux-hardware.org/?probe=e21be2124d) | Nov 04, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| HP            | 8061                        | Desktop     | [d11b92ef18](https://linux-hardware.org/?probe=d11b92ef18) | Nov 01, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [a3cdedf351](https://linux-hardware.org/?probe=a3cdedf351) | Oct 30, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | Notebook    | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [3919d06624](https://linux-hardware.org/?probe=3919d06624) | Oct 25, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| Pegatron      | IPMSB-H61                   | Desktop     | [c569d86fff](https://linux-hardware.org/?probe=c569d86fff) | Oct 19, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| HP            | 8061                        | Desktop     | [b2cf684801](https://linux-hardware.org/?probe=b2cf684801) | Oct 13, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | Notebook    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | Notebook    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| MSI           | MAG B550M MORTAR            | Desktop     | [653a4a9f6e](https://linux-hardware.org/?probe=653a4a9f6e) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| HP            | 15                          | Notebook    | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [11b8e32835](https://linux-hardware.org/?probe=11b8e32835) | Oct 06, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | Notebook    | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [2d6256e8c5](https://linux-hardware.org/?probe=2d6256e8c5) | Oct 05, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | Notebook    | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | Notebook    | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [074fb7cc02](https://linux-hardware.org/?probe=074fb7cc02) | Sep 28, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [32556e96bf](https://linux-hardware.org/?probe=32556e96bf) | Sep 27, 2020 |
| MSI           | A88XM-E35                   | Desktop     | [7176092b12](https://linux-hardware.org/?probe=7176092b12) | Sep 27, 2020 |
| HP            | 8061                        | Desktop     | [1d3e0a6b3d](https://linux-hardware.org/?probe=1d3e0a6b3d) | Sep 25, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [bf1e06fe4f](https://linux-hardware.org/?probe=bf1e06fe4f) | Sep 23, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [337ba51577](https://linux-hardware.org/?probe=337ba51577) | Sep 23, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | Notebook    | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | Notebook    | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | Notebook    | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [546b3fec83](https://linux-hardware.org/?probe=546b3fec83) | Sep 16, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | OptiPlex 9010 AIO           | All in one  | [a2e7991749](https://linux-hardware.org/?probe=a2e7991749) | Sep 11, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [eaff730455](https://linux-hardware.org/?probe=eaff730455) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | Notebook    | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | Notebook    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9557e9d02c](https://linux-hardware.org/?probe=9557e9d02c) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | Notebook    | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | Notebook    | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | Notebook    | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [288f4f772c](https://linux-hardware.org/?probe=288f4f772c) | Sep 01, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | Notebook    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | Notebook    | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | Notebook    | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | Notebook    | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | Notebook    | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [ecd87de5e0](https://linux-hardware.org/?probe=ecd87de5e0) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | Notebook    | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [b5e17b6229](https://linux-hardware.org/?probe=b5e17b6229) | Aug 16, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | Notebook    | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6b5b2287e0](https://linux-hardware.org/?probe=6b5b2287e0) | Aug 07, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| MSI           | GV62 8RD                    | Notebook    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | Notebook    | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | Notebook    | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| HP            | 805D                        | Desktop     | [b0f200fe77](https://linux-hardware.org/?probe=b0f200fe77) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | Notebook    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | Notebook    | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | Notebook    | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | Notebook    | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | Notebook    | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [22963b821f](https://linux-hardware.org/?probe=22963b821f) | Jun 20, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [c5779593cc](https://linux-hardware.org/?probe=c5779593cc) | Jun 20, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [ec653ae1fc](https://linux-hardware.org/?probe=ec653ae1fc) | Jun 11, 2020 |
| HP            | 15                          | Notebook    | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | Notebook    | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | Notebook    | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [5cde7141d6](https://linux-hardware.org/?probe=5cde7141d6) | Jun 02, 2020 |
| Google        | Caroline                    | Notebook    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [6bdc484d30](https://linux-hardware.org/?probe=6bdc484d30) | May 25, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | Notebook    | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | 17E2                        | Mini pc     | [b62ca0352c](https://linux-hardware.org/?probe=b62ca0352c) | May 22, 2020 |
| HP            | EliteBook 745 G3            | Notebook    | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [a36437dc35](https://linux-hardware.org/?probe=a36437dc35) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | Notebook    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | Notebook    | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | Notebook    | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | Notebook    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [7ae56aa829](https://linux-hardware.org/?probe=7ae56aa829) | May 11, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | Notebook    | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [d4cbef0ab2](https://linux-hardware.org/?probe=d4cbef0ab2) | May 02, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [285c59f702](https://linux-hardware.org/?probe=285c59f702) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [36bb48017f](https://linux-hardware.org/?probe=36bb48017f) | Apr 29, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [1f91672dce](https://linux-hardware.org/?probe=1f91672dce) | Apr 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [6b07754d1d](https://linux-hardware.org/?probe=6b07754d1d) | Apr 27, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [e487e06d2c](https://linux-hardware.org/?probe=e487e06d2c) | Apr 26, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [390a1cbbb3](https://linux-hardware.org/?probe=390a1cbbb3) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [252b646f8b](https://linux-hardware.org/?probe=252b646f8b) | Apr 25, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [0fe6d54c09](https://linux-hardware.org/?probe=0fe6d54c09) | Apr 25, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [eec2e1e90f](https://linux-hardware.org/?probe=eec2e1e90f) | Apr 24, 2020 |
| Dell          | 0D28YY A03                  | Desktop     | [cb0a381ca1](https://linux-hardware.org/?probe=cb0a381ca1) | Apr 22, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | Notebook    | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [dbe36dfd4f](https://linux-hardware.org/?probe=dbe36dfd4f) | Apr 21, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [06c5a92500](https://linux-hardware.org/?probe=06c5a92500) | Apr 18, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b87b3feefd](https://linux-hardware.org/?probe=b87b3feefd) | Apr 18, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [d092c3db85](https://linux-hardware.org/?probe=d092c3db85) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | Notebook    | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [8eca04a69b](https://linux-hardware.org/?probe=8eca04a69b) | Apr 14, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | Notebook    | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [576c3b1853](https://linux-hardware.org/?probe=576c3b1853) | Apr 13, 2020 |
| TriGem Com... | DreamSys                    | Desktop     | [e5a22f4123](https://linux-hardware.org/?probe=e5a22f4123) | Apr 09, 2020 |
| Clevo         | E412X                       | Notebook    | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c00e4e1a0e](https://linux-hardware.org/?probe=c00e4e1a0e) | Apr 07, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [087a36a4bd](https://linux-hardware.org/?probe=087a36a4bd) | Apr 04, 2020 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [35b973ebbb](https://linux-hardware.org/?probe=35b973ebbb) | Apr 03, 2020 |
| HP            | EliteBook 745 G2            | Notebook    | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | Notebook    | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | Notebook    | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9355c0ff9e](https://linux-hardware.org/?probe=9355c0ff9e) | Apr 01, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c6dbdb971](https://linux-hardware.org/?probe=8c6dbdb971) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [70b408e2f0](https://linux-hardware.org/?probe=70b408e2f0) | Mar 25, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [be10de1b16](https://linux-hardware.org/?probe=be10de1b16) | Mar 24, 2020 |
| Dell          | Latitude E6430              | Notebook    | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | Notebook    | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [92e778ba2a](https://linux-hardware.org/?probe=92e778ba2a) | Mar 21, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f7cbec79e8](https://linux-hardware.org/?probe=f7cbec79e8) | Mar 15, 2020 |
| Gigabyte      | H310M DS2                   | Desktop     | [529f84f7d1](https://linux-hardware.org/?probe=529f84f7d1) | Mar 12, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [636f6029b4](https://linux-hardware.org/?probe=636f6029b4) | Mar 11, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [861919e59d](https://linux-hardware.org/?probe=861919e59d) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [dff3f373f6](https://linux-hardware.org/?probe=dff3f373f6) | Mar 08, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2b1b62332c](https://linux-hardware.org/?probe=2b1b62332c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [e52b770dff](https://linux-hardware.org/?probe=e52b770dff) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [a06909608c](https://linux-hardware.org/?probe=a06909608c) | Mar 08, 2020 |
| MSI           | MS-7309                     | Desktop     | [b3e1633a13](https://linux-hardware.org/?probe=b3e1633a13) | Mar 08, 2020 |
| Sony          | SVP13215CDB                 | Notebook    | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |
| Dell          | Precision 3540              | Notebook    | [b30c51350c](https://linux-hardware.org/?probe=b30c51350c) | Mar 05, 2020 |
| ASUSTek       | X441SA                      | Notebook    | [e06798387f](https://linux-hardware.org/?probe=e06798387f) | Mar 05, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [a1d3a510e8](https://linux-hardware.org/?probe=a1d3a510e8) | Mar 04, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [6e803cdc23](https://linux-hardware.org/?probe=6e803cdc23) | Mar 02, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [fb41a1d23f](https://linux-hardware.org/?probe=fb41a1d23f) | Mar 02, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [162a9b6da7](https://linux-hardware.org/?probe=162a9b6da7) | Feb 22, 2020 |
| Acer          | Aspire V5-471G              | Notebook    | [85eca92a3b](https://linux-hardware.org/?probe=85eca92a3b) | Feb 22, 2020 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [f5bb829dbb](https://linux-hardware.org/?probe=f5bb829dbb) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [e3c94b5684](https://linux-hardware.org/?probe=e3c94b5684) | Feb 22, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [c549e93013](https://linux-hardware.org/?probe=c549e93013) | Feb 21, 2020 |
| Acer          | Aspire ES1-132              | Notebook    | [7994c923a0](https://linux-hardware.org/?probe=7994c923a0) | Feb 21, 2020 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [3dc258b050](https://linux-hardware.org/?probe=3dc258b050) | Feb 20, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [5cce680c2e](https://linux-hardware.org/?probe=5cce680c2e) | Feb 20, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [75b9cc12a9](https://linux-hardware.org/?probe=75b9cc12a9) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [de6eba23f1](https://linux-hardware.org/?probe=de6eba23f1) | Feb 09, 2020 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [78d658fc64](https://linux-hardware.org/?probe=78d658fc64) | Feb 09, 2020 |
| EMAXX TECH... | EMX-A70FM2+iCafe            | Desktop     | [4f64209449](https://linux-hardware.org/?probe=4f64209449) | Feb 07, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [cb21aa111e](https://linux-hardware.org/?probe=cb21aa111e) | Jan 31, 2020 |
| Lenovo        | IdeaPad Y460                | Notebook    | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [973270aee7](https://linux-hardware.org/?probe=973270aee7) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [459627eda2](https://linux-hardware.org/?probe=459627eda2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [61dfac2df2](https://linux-hardware.org/?probe=61dfac2df2) | Jan 26, 2020 |
| Foxconn       | G31MX Series                | Desktop     | [880daf6c76](https://linux-hardware.org/?probe=880daf6c76) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [0d020faa5c](https://linux-hardware.org/?probe=0d020faa5c) | Jan 24, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [e3389e7b39](https://linux-hardware.org/?probe=e3389e7b39) | Jan 23, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | Notebook    | [298e5dbad9](https://linux-hardware.org/?probe=298e5dbad9) | Jan 20, 2020 |
| Dell          | Inspiron N4030              | Notebook    | [f3d828d4b1](https://linux-hardware.org/?probe=f3d828d4b1) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [600afa3fd4](https://linux-hardware.org/?probe=600afa3fd4) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [57c3c5d09b](https://linux-hardware.org/?probe=57c3c5d09b) | Jan 11, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [1e5c712f0b](https://linux-hardware.org/?probe=1e5c712f0b) | Jan 05, 2020 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d5df64e644](https://linux-hardware.org/?probe=d5df64e644) | Dec 29, 2019 |
| Acer          | Aspire A311-31              | Notebook    | [1db743caaf](https://linux-hardware.org/?probe=1db743caaf) | Dec 24, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [eecdfa47b7](https://linux-hardware.org/?probe=eecdfa47b7) | Dec 15, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [44ecc526a8](https://linux-hardware.org/?probe=44ecc526a8) | Dec 12, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [e4fecb44bc](https://linux-hardware.org/?probe=e4fecb44bc) | Dec 05, 2019 |
| HP            | ProBook 440 G6              | Notebook    | [20bcca591f](https://linux-hardware.org/?probe=20bcca591f) | Dec 03, 2019 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [777d549872](https://linux-hardware.org/?probe=777d549872) | Nov 22, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [c5d4684f24](https://linux-hardware.org/?probe=c5d4684f24) | Nov 11, 2019 |
| Acer          | AO722                       | Notebook    | [a54b8c9315](https://linux-hardware.org/?probe=a54b8c9315) | Nov 08, 2019 |
| Pegatron      | IPMSB-H61                   | Desktop     | [857c9bddda](https://linux-hardware.org/?probe=857c9bddda) | Nov 07, 2019 |
| Pegatron      | IPMSB-H61                   | Desktop     | [55e7a33a87](https://linux-hardware.org/?probe=55e7a33a87) | Nov 07, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [ac217a032c](https://linux-hardware.org/?probe=ac217a032c) | Nov 03, 2019 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [619b0ce294](https://linux-hardware.org/?probe=619b0ce294) | Oct 09, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [0f199af685](https://linux-hardware.org/?probe=0f199af685) | Sep 22, 2019 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [8d497813d1](https://linux-hardware.org/?probe=8d497813d1) | Sep 19, 2019 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [7c06f63670](https://linux-hardware.org/?probe=7c06f63670) | Sep 18, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [36b5c905d1](https://linux-hardware.org/?probe=36b5c905d1) | Sep 16, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [e5d5c98452](https://linux-hardware.org/?probe=e5d5c98452) | Sep 11, 2019 |
| Wacom         | Citiq Companion             | Tablet      | [5a97b2a1a7](https://linux-hardware.org/?probe=5a97b2a1a7) | Sep 10, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | Notebook    | [35b92b56a8](https://linux-hardware.org/?probe=35b92b56a8) | Sep 03, 2019 |
| Acer          | Aspire A315-51              | Notebook    | [eaadda80df](https://linux-hardware.org/?probe=eaadda80df) | Aug 25, 2019 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [6674277b6a](https://linux-hardware.org/?probe=6674277b6a) | Aug 23, 2019 |
| ASRock        | A780GM-LE                   | Desktop     | [80fb7e01aa](https://linux-hardware.org/?probe=80fb7e01aa) | Aug 22, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | Notebook    | [e57d7bb95a](https://linux-hardware.org/?probe=e57d7bb95a) | Aug 14, 2019 |
| Wacom         | Citiq Companion             | Tablet      | [ac4803b894](https://linux-hardware.org/?probe=ac4803b894) | Aug 11, 2019 |
| HP            | Pavilion dm4                | Notebook    | [42df53b120](https://linux-hardware.org/?probe=42df53b120) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | Desktop     | [1f7f86ed9e](https://linux-hardware.org/?probe=1f7f86ed9e) | Jul 13, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [ac8f1708fb](https://linux-hardware.org/?probe=ac8f1708fb) | Jun 30, 2019 |
| Acer          | Aspire 3935                 | Notebook    | [2288125313](https://linux-hardware.org/?probe=2288125313) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | Notebook    | [fbb934cec8](https://linux-hardware.org/?probe=fbb934cec8) | Jun 27, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [704346ee85](https://linux-hardware.org/?probe=704346ee85) | Jun 24, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3fb0bfffca](https://linux-hardware.org/?probe=3fb0bfffca) | Jun 24, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [c133935d4f](https://linux-hardware.org/?probe=c133935d4f) | Jun 19, 2019 |
| Acer          | Aspire 5516                 | Notebook    | [92691e9024](https://linux-hardware.org/?probe=92691e9024) | Jun 13, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [db39b4023e](https://linux-hardware.org/?probe=db39b4023e) | Jun 03, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [833afc1cd1](https://linux-hardware.org/?probe=833afc1cd1) | May 12, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [04903c40d9](https://linux-hardware.org/?probe=04903c40d9) | May 10, 2019 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1d29713c8b](https://linux-hardware.org/?probe=1d29713c8b) | May 02, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [d3769c3f4d](https://linux-hardware.org/?probe=d3769c3f4d) | Apr 16, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [31f0b418f9](https://linux-hardware.org/?probe=31f0b418f9) | Apr 16, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [3cfa230457](https://linux-hardware.org/?probe=3cfa230457) | Apr 12, 2019 |
| Dell          | 01TKCC A01                  | Desktop     | [94e2e60839](https://linux-hardware.org/?probe=94e2e60839) | Apr 11, 2019 |
| HP            | ENVY 4                      | Notebook    | [97135eda99](https://linux-hardware.org/?probe=97135eda99) | Mar 31, 2019 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ac265b9b6d](https://linux-hardware.org/?probe=ac265b9b6d) | Mar 27, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [d3d3b75d21](https://linux-hardware.org/?probe=d3d3b75d21) | Jan 04, 2019 |
| ASUSTek       | X540NA                      | Notebook    | [6f63118ade](https://linux-hardware.org/?probe=6f63118ade) | Jan 04, 2019 |
| Acer          | TravelMate B113             | Notebook    | [fea3b127ea](https://linux-hardware.org/?probe=fea3b127ea) | Dec 25, 2018 |
| ASUSTek       | GL553VD                     | Notebook    | [d43361263c](https://linux-hardware.org/?probe=d43361263c) | Dec 24, 2018 |
| ASUSTek       | X540NA                      | Notebook    | [03eadbe056](https://linux-hardware.org/?probe=03eadbe056) | Nov 20, 2018 |
| ASUSTek       | X540NA                      | Notebook    | [f06d9e94e9](https://linux-hardware.org/?probe=f06d9e94e9) | Nov 20, 2018 |
| Lenovo        | No DPK                      | Desktop     | [02bdd4779e](https://linux-hardware.org/?probe=02bdd4779e) | Oct 21, 2018 |
| Lenovo        | No DPK                      | Desktop     | [d98528c04e](https://linux-hardware.org/?probe=d98528c04e) | Oct 21, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [aee859c42b](https://linux-hardware.org/?probe=aee859c42b) | Jan 05, 2018 |
| MSI           | GT70 2PC                    | Notebook    | [020492bfa1](https://linux-hardware.org/?probe=020492bfa1) | Jul 04, 2017 |
| MSI           | GT70 2PC                    | Notebook    | [a5dafd1181](https://linux-hardware.org/?probe=a5dafd1181) | Jul 04, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Philippines/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 54        | 11.49%  |
| Pop!_OS 20.04      | 25        | 5.32%   |
| Ubuntu 18.04       | 22        | 4.68%   |
| Ubuntu 22.04       | 18        | 3.83%   |
| KDE neon 20.04     | 18        | 3.83%   |
| OpenMandriva 4.2   | 13        | 2.77%   |
| Zorin 15           | 11        | 2.34%   |
| Pop!_OS 21.04      | 10        | 2.13%   |
| Pop!_OS 22.04      | 9         | 1.91%   |
| Fedora 36          | 9         | 1.91%   |
| Manjaro            | 8         | 1.7%    |
| BlackPanther 18.1  | 8         | 1.7%    |
| Arch               | 8         | 1.7%    |
| Linux Mint 20.2    | 7         | 1.49%   |
| Pop!_OS 20.10      | 6         | 1.28%   |
| OpenMandriva 4.3   | 6         | 1.28%   |
| Linux Mint 20.1    | 6         | 1.28%   |
| Kubuntu 22.04      | 6         | 1.28%   |
| Fedora 33          | 6         | 1.28%   |
| Endless 3.7.7      | 6         | 1.28%   |
| Zorin 16           | 5         | 1.06%   |
| Ubuntu 20.10       | 5         | 1.06%   |
| Linux Mint 19.3    | 5         | 1.06%   |
| Fedora 35          | 5         | 1.06%   |
| Fedora 32          | 5         | 1.06%   |
| Endless 3.7.6      | 5         | 1.06%   |
| Debian 11          | 5         | 1.06%   |
| BlackPanther 16.2  | 5         | 1.06%   |
| Xubuntu 20.04      | 4         | 0.85%   |
| Ubuntu Unity 18.04 | 4         | 0.85%   |
| Ubuntu 21.10       | 4         | 0.85%   |
| Pop!_OS 21.10      | 4         | 0.85%   |
| LMDE 4             | 4         | 0.85%   |
| Linux Mint 20.3    | 4         | 0.85%   |
| Fedora 34          | 4         | 0.85%   |
| Ubuntu 19.10       | 3         | 0.64%   |
| Linux Mint 20      | 3         | 0.64%   |
| KDE neon 18.04     | 3         | 0.64%   |
| Fedora 31          | 3         | 0.64%   |
| Endless 3.9.1      | 3         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 108       | 24.32%  |
| Pop!_OS       | 54        | 12.16%  |
| Linux Mint    | 33        | 7.43%   |
| Endless       | 31        | 6.98%   |
| Fedora        | 30        | 6.76%   |
| KDE neon      | 21        | 4.73%   |
| OpenMandriva  | 20        | 4.5%    |
| Manjaro       | 17        | 3.83%   |
| Zorin         | 16        | 3.6%    |
| Arch          | 11        | 2.48%   |
| Debian        | 10        | 2.25%   |
| BlackPanther  | 10        | 2.25%   |
| Kubuntu       | 9         | 2.03%   |
| Xubuntu       | 8         | 1.8%    |
| Kali          | 8         | 1.8%    |
| Elementary    | 6         | 1.35%   |
| Ubuntu Unity  | 5         | 1.13%   |
| Ubuntu MATE   | 4         | 0.9%    |
| LMDE          | 4         | 0.9%    |
| EndeavourOS   | 4         | 0.9%    |
| ArcoLinux     | 4         | 0.9%    |
| ROSA          | 3         | 0.68%   |
| openSUSE      | 3         | 0.68%   |
| Lubuntu       | 3         | 0.68%   |
| Peppermint    | 2         | 0.45%   |
| Nobara        | 2         | 0.45%   |
| MX            | 2         | 0.45%   |
| Gentoo        | 2         | 0.45%   |
| Ubuntu Budgie | 1         | 0.23%   |
| Sparky        | 1         | 0.23%   |
| Solus         | 1         | 0.23%   |
| Slackware     | 1         | 0.23%   |
| Reborn OS     | 1         | 0.23%   |
| Raspbian      | 1         | 0.23%   |
| Parrot        | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| Hash Linux    | 1         | 0.23%   |
| Garuda Linux  | 1         | 0.23%   |
| Clear Linux   | 1         | 0.23%   |
| BunsenLabs    | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 18        | 3.56%   |
| 5.10.14-desktop-1omv4002 | 13        | 2.57%   |
| 5.3.0-28-generic         | 10        | 1.98%   |
| 5.4.0-7634-generic       | 8         | 1.58%   |
| 5.4.0-48-generic         | 8         | 1.58%   |
| 4.18.16-desktop-1bP      | 8         | 1.58%   |
| 5.3.0-23-generic         | 7         | 1.39%   |
| 5.8.0-7630-generic       | 6         | 1.19%   |
| 5.8.0-14-generic         | 6         | 1.19%   |
| 5.16.7-desktop-1omv4003  | 6         | 1.19%   |
| 5.15.0-41-generic        | 6         | 1.19%   |
| 5.4.0-58-generic         | 5         | 0.99%   |
| 5.4.0-47-generic         | 5         | 0.99%   |
| 5.15.0-50-generic        | 5         | 0.99%   |
| 5.11.0-7620-generic      | 5         | 0.99%   |
| 4.9.20-desktop-pae-1bP   | 5         | 0.99%   |
| 5.4.0-7642-generic       | 4         | 0.79%   |
| 5.4.0-73-generic         | 4         | 0.79%   |
| 5.4.0-19-generic         | 4         | 0.79%   |
| 5.15.0-52-generic        | 4         | 0.79%   |
| 5.15.0-48-generic        | 4         | 0.79%   |
| 5.13.0-7614-generic      | 4         | 0.79%   |
| 5.13.0-30-generic        | 4         | 0.79%   |
| 5.13.0-28-generic        | 4         | 0.79%   |
| 4.18.0-25-generic        | 4         | 0.79%   |
| 5.8.0-7642-generic       | 3         | 0.59%   |
| 5.4.0-80-generic         | 3         | 0.59%   |
| 5.4.0-52-generic         | 3         | 0.59%   |
| 5.4.0-45-generic         | 3         | 0.59%   |
| 5.4.0-31-generic         | 3         | 0.59%   |
| 5.3.0-46-generic         | 3         | 0.59%   |
| 5.17.5-76051705-generic  | 3         | 0.59%   |
| 5.15.0-47-generic        | 3         | 0.59%   |
| 5.15.0-46-generic        | 3         | 0.59%   |
| 5.15.0-43-generic        | 3         | 0.59%   |
| 5.15.0-40-generic        | 3         | 0.59%   |
| 5.13.0-40-generic        | 3         | 0.59%   |
| 5.13.0-35-generic        | 3         | 0.59%   |
| 5.11.0-7614-generic      | 3         | 0.59%   |
| 5.11.0-27-generic        | 3         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 96        | 19.83%  |
| 5.15.0  | 39        | 8.06%   |
| 5.3.0   | 32        | 6.61%   |
| 5.8.0   | 31        | 6.4%    |
| 5.13.0  | 30        | 6.2%    |
| 5.11.0  | 25        | 5.17%   |
| 4.15.0  | 21        | 4.34%   |
| 5.10.14 | 13        | 2.69%   |
| 5.0.0   | 11        | 2.27%   |
| 4.18.0  | 10        | 2.07%   |
| 4.19.0  | 8         | 1.65%   |
| 4.18.16 | 8         | 1.65%   |
| 5.17.5  | 6         | 1.24%   |
| 5.16.7  | 6         | 1.24%   |
| 5.10.0  | 6         | 1.24%   |
| 4.9.20  | 6         | 1.24%   |
| 5.19.0  | 4         | 0.83%   |
| 5.9.16  | 3         | 0.62%   |
| 5.18.13 | 3         | 0.62%   |
| 5.18.10 | 3         | 0.62%   |
| 5.18.0  | 3         | 0.62%   |
| 5.16.0  | 3         | 0.62%   |
| 5.11.16 | 3         | 0.62%   |
| 4.4.0   | 3         | 0.62%   |
| 5.9.11  | 2         | 0.41%   |
| 5.8.14  | 2         | 0.41%   |
| 5.4.20  | 2         | 0.41%   |
| 5.19.13 | 2         | 0.41%   |
| 5.19.12 | 2         | 0.41%   |
| 5.15.49 | 2         | 0.41%   |
| 5.15.21 | 2         | 0.41%   |
| 5.15.10 | 2         | 0.41%   |
| 5.14.0  | 2         | 0.41%   |
| 5.13.8  | 2         | 0.41%   |
| 5.11.12 | 2         | 0.41%   |
| 4.13.0  | 2         | 0.41%   |
| 6.0.5   | 1         | 0.21%   |
| 6.0.2   | 1         | 0.21%   |
| 6.0.1   | 1         | 0.21%   |
| 6.0.0   | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 107       | 22.38%  |
| 5.15    | 57        | 11.92%  |
| 5.8     | 38        | 7.95%   |
| 5.3     | 34        | 7.11%   |
| 5.13    | 33        | 6.9%    |
| 5.10    | 31        | 6.49%   |
| 5.11    | 30        | 6.28%   |
| 4.15    | 21        | 4.39%   |
| 4.18    | 18        | 3.77%   |
| 5.16    | 17        | 3.56%   |
| 5.19    | 14        | 2.93%   |
| 5.0     | 12        | 2.51%   |
| 5.18    | 11        | 2.3%    |
| 5.17    | 8         | 1.67%   |
| 4.9     | 8         | 1.67%   |
| 4.19    | 8         | 1.67%   |
| 5.9     | 7         | 1.46%   |
| 6.0     | 4         | 0.84%   |
| 5.14    | 4         | 0.84%   |
| 4.4     | 4         | 0.84%   |
| 5.6     | 3         | 0.63%   |
| 5.7     | 2         | 0.42%   |
| 5.12    | 2         | 0.42%   |
| 4.13    | 2         | 0.42%   |
| 5.2     | 1         | 0.21%   |
| 5.1     | 1         | 0.21%   |
| 3.8     | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 411       | 94.7%   |
| i686    | 15        | 3.46%   |
| armv7l  | 4         | 0.92%   |
| aarch64 | 4         | 0.92%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 212       | 47.22%  |
| KDE5            | 79        | 17.59%  |
| Unknown         | 37        | 8.24%   |
| XFCE            | 35        | 7.8%    |
| X-Cinnamon      | 28        | 6.24%   |
| KDE             | 17        | 3.79%   |
| MATE            | 11        | 2.45%   |
| Pantheon        | 5         | 1.11%   |
| LXQt            | 5         | 1.11%   |
| Unity           | 4         | 0.89%   |
| LXDE            | 3         | 0.67%   |
| openbox         | 2         | 0.45%   |
| Cinnamon        | 2         | 0.45%   |
| Budgie          | 2         | 0.45%   |
| sway            | 1         | 0.22%   |
| river           | 1         | 0.22%   |
| GNOME Flashback | 1         | 0.22%   |
| default         | 1         | 0.22%   |
| Deepin          | 1         | 0.22%   |
| Cutefish        | 1         | 0.22%   |
| awesome         | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 367       | 83.41%  |
| Wayland | 47        | 10.68%  |
| Unknown | 18        | 4.09%   |
| Tty     | 8         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 264       | 59.33%  |
| SDDM    | 61        | 13.71%  |
| GDM     | 44        | 9.89%   |
| LightDM | 34        | 7.64%   |
| GDM3    | 29        | 6.52%   |
| TDM     | 10        | 2.25%   |
| SLiM    | 1         | 0.22%   |
| MDM     | 1         | 0.22%   |
| LXDM    | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_PH   | 209       | 47.29%  |
| en_US   | 164       | 37.1%   |
| Unknown | 44        | 9.95%   |
| C       | 8         | 1.81%   |
| en_GB   | 5         | 1.13%   |
| de_DE   | 4         | 0.9%    |
| zh_CN   | 2         | 0.45%   |
| zh_HK   | 1         | 0.23%   |
| fil_PH  | 1         | 0.23%   |
| en_NZ   | 1         | 0.23%   |
| en_HK   | 1         | 0.23%   |
| en_CA   | 1         | 0.23%   |
| da_DK   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 227       | 51.47%  |
| EFI  | 214       | 48.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 346       | 77.75%  |
| Btrfs   | 42        | 9.44%   |
| Overlay | 37        | 8.31%   |
| Unknown | 11        | 2.47%   |
| Xfs     | 4         | 0.9%    |
| Ext2    | 3         | 0.67%   |
| Zfs     | 2         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 277       | 62.39%  |
| GPT     | 122       | 27.48%  |
| MBR     | 45        | 10.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 388       | 87.58%  |
| Yes       | 55        | 12.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 324       | 72.97%  |
| Yes       | 120       | 27.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 65        | 15.08%  |
| ASUSTek Computer          | 55        | 12.76%  |
| Acer                      | 53        | 12.3%   |
| Hewlett-Packard           | 49        | 11.37%  |
| Gigabyte Technology       | 40        | 9.28%   |
| Dell                      | 37        | 8.58%   |
| MSI                       | 35        | 8.12%   |
| Toshiba                   | 12        | 2.78%   |
| ASRock                    | 10        | 2.32%   |
| Apple                     | 9         | 2.09%   |
| Samsung Electronics       | 5         | 1.16%   |
| Raspberry Pi Foundation   | 5         | 1.16%   |
| Foxconn                   | 5         | 1.16%   |
| Biostar                   | 5         | 1.16%   |
| Sony                      | 4         | 0.93%   |
| ECS                       | 4         | 0.93%   |
| Clevo                     | 4         | 0.93%   |
| Unknown                   | 4         | 0.93%   |
| NEC Computers             | 3         | 0.7%    |
| EMAXX TECHNOLOGY          | 3         | 0.7%    |
| eMachines                 | 3         | 0.7%    |
| Pegatron                  | 2         | 0.46%   |
| Google                    | 2         | 0.46%   |
| YANYU                     | 1         | 0.23%   |
| Wacom                     | 1         | 0.23%   |
| TriGem Computer           | 1         | 0.23%   |
| Shenzhen Bmorn Technology | 1         | 0.23%   |
| realme                    | 1         | 0.23%   |
| QTQD                      | 1         | 0.23%   |
| PERSONA                   | 1         | 0.23%   |
| Notebook                  | 1         | 0.23%   |
| Microsoft                 | 1         | 0.23%   |
| Jumper                    | 1         | 0.23%   |
| JOOYON                    | 1         | 0.23%   |
| Intel                     | 1         | 0.23%   |
| HUAWEI                    | 1         | 0.23%   |
| HASEE Computer            | 1         | 0.23%   |
| Fujitsu                   | 1         | 0.23%   |
| Cubix                     | 1         | 0.23%   |
| AMD                       | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 8         | 1.86%   |
| Acer Aspire ES1-132        | 6         | 1.39%   |
| RPi Raspberry Pi           | 4         | 0.93%   |
| MSI MS-7721                | 4         | 0.93%   |
| MSI MS-7309                | 4         | 0.93%   |
| Gigabyte F2A68HM-S1        | 4         | 0.93%   |
| Gigabyte A320M-S2H V2      | 4         | 0.93%   |
| ASUS All Series            | 4         | 0.93%   |
| HP Notebook                | 3         | 0.7%    |
| Foxconn G31MX Series       | 3         | 0.7%    |
| Clevo M7x0S                | 3         | 0.7%    |
| ASUS P8H61-M LX3 PLUS R2.0 | 3         | 0.7%    |
| ASRock B450M Steel Legend  | 3         | 0.7%    |
| Pegatron IPMSB-H61         | 2         | 0.46%   |
| Lenovo Yoga 520-14IKB 81C8 | 2         | 0.46%   |
| Lenovo V110-14IAP 80TF     | 2         | 0.46%   |
| HP Pavilion Notebook       | 2         | 0.46%   |
| Gigabyte Z590 AORUS ULTRA  | 2         | 0.46%   |
| Foxconn 500B Microtower    | 2         | 0.46%   |
| eMachines eM350            | 2         | 0.46%   |
| Dell OptiPlex 9010 AIO     | 2         | 0.46%   |
| Dell Latitude E7450        | 2         | 0.46%   |
| Dell Inspiron 5567         | 2         | 0.46%   |
| ASUS X540NA                | 2         | 0.46%   |
| ASUS PRIME B250M-K         | 2         | 0.46%   |
| ASUS EX-H310M-V3 R2.0      | 2         | 0.46%   |
| Apple MacBookPro5,5        | 2         | 0.46%   |
| Acer TravelMate P249-G2-M  | 2         | 0.46%   |
| Acer TravelMate B113       | 2         | 0.46%   |
| Acer Swift SF314-57        | 2         | 0.46%   |
| Acer Aspire E5-551G        | 2         | 0.46%   |
| Acer Aspire E3-111         | 2         | 0.46%   |
| Acer Aspire A315-51        | 2         | 0.46%   |
| Acer Aspire A315-41G       | 2         | 0.46%   |
| YANYU EPIC-C19             | 1         | 0.23%   |
| Wacom Citiq Companion      | 1         | 0.23%   |
| TriGem DreamSys            | 1         | 0.23%   |
| Toshiba TECRA Z50-C        | 1         | 0.23%   |
| Toshiba TECRA R940         | 1         | 0.23%   |
| Toshiba Satellite Pro U400 | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Acer Aspire         | 36        | 8.35%   |
| Lenovo ThinkPad     | 29        | 6.73%   |
| Lenovo IdeaPad      | 23        | 5.34%   |
| Dell Inspiron       | 14        | 3.25%   |
| HP Pavilion         | 11        | 2.55%   |
| Dell OptiPlex       | 8         | 1.86%   |
| Unknown             | 8         | 1.86%   |
| Acer TravelMate     | 7         | 1.62%   |
| Toshiba Satellite   | 6         | 1.39%   |
| Dell Latitude       | 6         | 1.39%   |
| ASUS TUF            | 6         | 1.39%   |
| ASUS ROG            | 6         | 1.39%   |
| RPi Raspberry       | 5         | 1.16%   |
| Gigabyte A320M-S2H  | 5         | 1.16%   |
| ASUS PRIME          | 5         | 1.16%   |
| ASUS P8H61-M        | 5         | 1.16%   |
| MSI MS-7721         | 4         | 0.93%   |
| MSI MS-7309         | 4         | 0.93%   |
| HP ProDesk          | 4         | 0.93%   |
| HP Laptop           | 4         | 0.93%   |
| HP Compaq           | 4         | 0.93%   |
| Gigabyte F2A68HM-S1 | 4         | 0.93%   |
| ASUS VivoBook       | 4         | 0.93%   |
| ASUS All            | 4         | 0.93%   |
| Lenovo Legion       | 3         | 0.7%    |
| HP Notebook         | 3         | 0.7%    |
| HP ENVY             | 3         | 0.7%    |
| HP EliteBook        | 3         | 0.7%    |
| Gigabyte B450       | 3         | 0.7%    |
| Foxconn G31MX       | 3         | 0.7%    |
| Dell Vostro         | 3         | 0.7%    |
| Clevo M7x0S         | 3         | 0.7%    |
| ASRock B450M        | 3         | 0.7%    |
| Acer Swift          | 3         | 0.7%    |
| Acer Nitro          | 3         | 0.7%    |
| Toshiba TECRA       | 2         | 0.46%   |
| Toshiba dynabook    | 2         | 0.46%   |
| Pegatron IPMSB-H61  | 2         | 0.46%   |
| MSI CX62            | 2         | 0.46%   |
| Lenovo Yoga         | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 41        | 9.51%   |
| 2017    | 39        | 9.05%   |
| 2012    | 39        | 9.05%   |
| 2019    | 38        | 8.82%   |
| 2014    | 37        | 8.58%   |
| 2016    | 32        | 7.42%   |
| 2010    | 30        | 6.96%   |
| 2020    | 28        | 6.5%    |
| 2011    | 26        | 6.03%   |
| 2021    | 25        | 5.8%    |
| 2015    | 25        | 5.8%    |
| 2013    | 23        | 5.34%   |
| 2009    | 18        | 4.18%   |
| 2008    | 8         | 1.86%   |
| Unknown | 8         | 1.86%   |
| 2007    | 6         | 1.39%   |
| 2006    | 5         | 1.16%   |
| 2022    | 3         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 259       | 60.09%  |
| Desktop        | 148       | 34.34%  |
| Mini pc        | 7         | 1.62%   |
| System on chip | 5         | 1.16%   |
| Convertible    | 5         | 1.16%   |
| All in one     | 4         | 0.93%   |
| Tablet         | 3         | 0.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 387       | 89.58%  |
| Enabled  | 45        | 10.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 429       | 99.54%  |
| Yes  | 2         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 107       | 24.1%   |
| 4.01-8.0    | 104       | 23.42%  |
| 8.01-16.0   | 87        | 19.59%  |
| 16.01-24.0  | 57        | 12.84%  |
| 1.01-2.0    | 42        | 9.46%   |
| 32.01-64.0  | 20        | 4.5%    |
| 2.01-3.0    | 12        | 2.7%    |
| 64.01-256.0 | 6         | 1.35%   |
| 0.51-1.0    | 5         | 1.13%   |
| 24.01-32.0  | 4         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 176       | 36.74%  |
| 2.01-3.0   | 136       | 28.39%  |
| 4.01-8.0   | 51        | 10.65%  |
| 3.01-4.0   | 48        | 10.02%  |
| 0.51-1.0   | 41        | 8.56%   |
| 8.01-16.0  | 17        | 3.55%   |
| 0.01-0.5   | 8         | 1.67%   |
| 24.01-32.0 | 1         | 0.21%   |
| Unknown    | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 282       | 62.39%  |
| 2      | 117       | 25.88%  |
| 3      | 25        | 5.53%   |
| 4      | 14        | 3.1%    |
| 5      | 7         | 1.55%   |
| 0      | 5         | 1.11%   |
| 13     | 1         | 0.22%   |
| 6      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 307       | 69.77%  |
| Yes       | 133       | 30.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 371       | 86.08%  |
| No        | 60        | 13.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 332       | 76.5%   |
| No        | 102       | 23.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 253       | 58.16%  |
| No        | 182       | 41.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Philippines | 431       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Quezon City         | 80        | 16.84%  |
| Cebu City           | 30        | 6.32%   |
| Davao City          | 24        | 5.05%   |
| Angeles City        | 22        | 4.63%   |
| Cagayan de Oro      | 18        | 3.79%   |
| Pasig               | 16        | 3.37%   |
| Paranaque City      | 15        | 3.16%   |
| Manila              | 15        | 3.16%   |
| Bacolod City        | 13        | 2.74%   |
| San Miguel          | 11        | 2.32%   |
| Manajao             | 11        | 2.32%   |
| Makati City         | 11        | 2.32%   |
| Caloocan City       | 11        | 2.32%   |
| Bacoor              | 11        | 2.32%   |
| San Jose del Monte  | 10        | 2.11%   |
| Mandaluyong City    | 10        | 2.11%   |
| Imus                | 9         | 1.89%   |
| Santa Rosa          | 8         | 1.68%   |
| Iligan City         | 8         | 1.68%   |
| San Fernando City   | 6         | 1.26%   |
| Las Pinas           | 6         | 1.26%   |
| Zamboanga City      | 5         | 1.05%   |
| Malolos             | 5         | 1.05%   |
| Lahug               | 5         | 1.05%   |
| Iloilo City         | 5         | 1.05%   |
| Tarlac City         | 4         | 0.84%   |
| Lucena City         | 4         | 0.84%   |
| General Santos      | 4         | 0.84%   |
| Dasmarinas          | 4         | 0.84%   |
| City of Muntinglupa | 4         | 0.84%   |
| Baguio City         | 4         | 0.84%   |
| Antipolo City       | 4         | 0.84%   |
| San Pedro           | 3         | 0.63%   |
| Lipa City           | 3         | 0.63%   |
| Legazpi             | 3         | 0.63%   |
| Tuguegarao City     | 2         | 0.42%   |
| Taytay              | 2         | 0.42%   |
| Talisay City        | 2         | 0.42%   |
| Taguig              | 2         | 0.42%   |
| San Pablo City      | 2         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 114       | 165    | 18.3%   |
| WDC                       | 106       | 129    | 17.01%  |
| Toshiba                   | 67        | 87     | 10.75%  |
| Samsung Electronics       | 48        | 61     | 7.7%    |
| Kingston                  | 30        | 36     | 4.82%   |
| Hitachi                   | 30        | 49     | 4.82%   |
| Unknown                   | 27        | 35     | 4.33%   |
| SanDisk                   | 25        | 27     | 4.01%   |
| SK hynix                  | 16        | 30     | 2.57%   |
| HGST                      | 13        | 14     | 2.09%   |
| Micron Technology         | 9         | 13     | 1.44%   |
| Team                      | 8         | 12     | 1.28%   |
| Intel                     | 8         | 9      | 1.28%   |
| A-DATA Technology         | 8         | 11     | 1.28%   |
| Lexar                     | 7         | 8      | 1.12%   |
| Transcend                 | 6         | 6      | 0.96%   |
| Gigabyte Technology       | 6         | 7      | 0.96%   |
| Fujitsu                   | 6         | 7      | 0.96%   |
| Crucial                   | 6         | 8      | 0.96%   |
| Ramsta                    | 5         | 6      | 0.8%    |
| Phison                    | 4         | 4      | 0.64%   |
| HS-SSD-C100               | 4         | 5      | 0.64%   |
| Apple                     | 4         | 4      | 0.64%   |
| WALRAM                    | 3         | 3      | 0.48%   |
| LITEONIT                  | 3         | 4      | 0.48%   |
| Indilinx                  | 3         | 3      | 0.48%   |
| HS-SSD-E100               | 3         | 3      | 0.48%   |
| China                     | 3         | 3      | 0.48%   |
| XPG                       | 2         | 2      | 0.32%   |
| Silicon Motion            | 2         | 2      | 0.32%   |
| Micron/Crucial Technology | 2         | 2      | 0.32%   |
| Lite-On                   | 2         | 4      | 0.32%   |
| KingSpec                  | 2         | 2      | 0.32%   |
| Kingmax                   | 2         | 2      | 0.32%   |
| JMicron Technology        | 2         | 5      | 0.32%   |
| ZOTAC                     | 1         | 1      | 0.16%   |
| XrayDisk                  | 1         | 1      | 0.16%   |
| Voyager                   | 1         | 1      | 0.16%   |
| Vaseky                    | 1         | 1      | 0.16%   |
| USB                       | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB        | 15        | 2.23%   |
| Seagate ST500DM002-1BD142 500GB | 11        | 1.63%   |
| Seagate ST1000DM010-2EP102 1TB  | 11        | 1.63%   |
| Seagate ST1000LM035-1RK172 1TB  | 10        | 1.48%   |
| Toshiba MQ01ABD100 1TB          | 8         | 1.19%   |
| WDC WD5000LPCX-21VHAT0 500GB    | 7         | 1.04%   |
| Toshiba DT01ACA050 500GB        | 7         | 1.04%   |
| Kingston SA400S37120G 120GB SSD | 7         | 1.04%   |
| Unknown MMC Card  32GB          | 6         | 0.89%   |
| Toshiba MQ04ABF100 1TB          | 6         | 0.89%   |
| Seagate ST500LT012-1DG142 500GB | 6         | 0.89%   |
| Samsung SSD 860 EVO 500GB       | 6         | 0.89%   |
| Kingston SA400S37240G 240GB SSD | 6         | 0.89%   |
| WDC WD10JPVX-22JC3T0 1TB        | 5         | 0.74%   |
| WDC WD10EZEX-08WN4A0 1TB        | 5         | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB  | 5         | 0.74%   |
| Samsung SSD 860 EVO 250GB       | 5         | 0.74%   |
| Hitachi HTS543232A7A384 320GB   | 5         | 0.74%   |
| Hitachi HDS721050CLA362 500GB   | 5         | 0.74%   |
| Unknown MMC Card  64GB          | 4         | 0.59%   |
| Seagate ST500LT012-9WS142 500GB | 4         | 0.59%   |
| Seagate ST2000LM007-1R8174 2TB  | 4         | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB  | 4         | 0.59%   |
| Seagate BUP Slim 2TB            | 4         | 0.59%   |
| Hitachi HDS721616PLA380 160GB   | 4         | 0.59%   |
| HGST HTS725050A7E630 500GB      | 4         | 0.59%   |
| WDC WD5000LPVX-22V0TT0 500GB    | 3         | 0.45%   |
| WDC WD5000LPCX-60VHAT0 500GB    | 3         | 0.45%   |
| WDC WD5000LPCX-24VHAT0 500GB    | 3         | 0.45%   |
| WDC WD5000AZLX-60K2TA0 500GB    | 3         | 0.45%   |
| WDC WD10SPZX-21Z10T0 1TB        | 3         | 0.45%   |
| WDC WD10EZEX-22MFCA0 1TB        | 3         | 0.45%   |
| Toshiba MK2555GSX 250GB         | 3         | 0.45%   |
| Toshiba DT01ACA100 1TB          | 3         | 0.45%   |
| SK hynix NVMe SSD Drive 512GB   | 3         | 0.45%   |
| Seagate ST9500325AS 500GB       | 3         | 0.45%   |
| Seagate ST500LM030-2E717D 500GB | 3         | 0.45%   |
| Seagate ST500LM030-1RK17D 500GB | 3         | 0.45%   |
| Seagate ST500DM002-1ER14C 500GB | 3         | 0.45%   |
| Seagate ST3160812AS 160GB       | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 114       | 164    | 34.55%  |
| WDC                 | 98        | 116    | 29.7%   |
| Toshiba             | 59        | 74     | 17.88%  |
| Hitachi             | 30        | 49     | 9.09%   |
| HGST                | 13        | 14     | 3.94%   |
| Fujitsu             | 6         | 7      | 1.82%   |
| Samsung Electronics | 4         | 5      | 1.21%   |
| Unknown             | 3         | 4      | 0.91%   |
| SAGE                | 1         | 1      | 0.3%    |
| HGST HTS            | 1         | 1      | 0.3%    |
| ExcelStor           | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 35     | 15.88%  |
| Kingston            | 23        | 28     | 13.53%  |
| SanDisk             | 16        | 17     | 9.41%   |
| Team                | 8         | 12     | 4.71%   |
| WDC                 | 7         | 9      | 4.12%   |
| A-DATA Technology   | 7         | 10     | 4.12%   |
| Toshiba             | 6         | 9      | 3.53%   |
| SK hynix            | 6         | 18     | 3.53%   |
| Lexar               | 6         | 7      | 3.53%   |
| Transcend           | 5         | 5      | 2.94%   |
| Micron Technology   | 5         | 5      | 2.94%   |
| Ramsta              | 4         | 5      | 2.35%   |
| Intel               | 4         | 5      | 2.35%   |
| Apple               | 4         | 4      | 2.35%   |
| LITEONIT            | 3         | 4      | 1.76%   |
| HS-SSD-E100         | 3         | 3      | 1.76%   |
| Gigabyte Technology | 3         | 3      | 1.76%   |
| China               | 3         | 3      | 1.76%   |
| KingSpec            | 2         | 2      | 1.18%   |
| Kingmax             | 2         | 2      | 1.18%   |
| HS-SSD-C100         | 2         | 2      | 1.18%   |
| Crucial             | 2         | 3      | 1.18%   |
| ZOTAC               | 1         | 1      | 0.59%   |
| WALRAM              | 1         | 1      | 0.59%   |
| Vaseky              | 1         | 1      | 0.59%   |
| Unknown             | 1         | 2      | 0.59%   |
| Teclast             | 1         | 4      | 0.59%   |
| TAMMUZ              | 1         | 1      | 0.59%   |
| SKIHOTAR            | 1         | 1      | 0.59%   |
| PNY                 | 1         | 1      | 0.59%   |
| Plextor             | 1         | 1      | 0.59%   |
| Phison              | 1         | 1      | 0.59%   |
| Patriot             | 1         | 1      | 0.59%   |
| OCZ                 | 1         | 1      | 0.59%   |
| Kimtigo             | 1         | 2      | 0.59%   |
| Indilinx            | 1         | 1      | 0.59%   |
| Hikvision           | 1         | 2      | 0.59%   |
| GLOWAY              | 1         | 1      | 0.59%   |
| GALAX               | 1         | 1      | 0.59%   |
| FORESEE             | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 289       | 436    | 51.42%  |
| SSD     | 151       | 221    | 26.87%  |
| NVMe    | 83        | 107    | 14.77%  |
| MMC     | 24        | 30     | 4.27%   |
| Unknown | 15        | 19     | 2.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 372       | 638    | 73.81%  |
| NVMe | 82        | 106    | 16.27%  |
| SAS  | 26        | 39     | 5.16%   |
| MMC  | 24        | 30     | 4.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 296       | 450    | 67.43%  |
| 0.51-1.0   | 110       | 165    | 25.06%  |
| 1.01-2.0   | 21        | 28     | 4.78%   |
| 3.01-4.0   | 11        | 13     | 2.51%   |
| 4.01-10.0  | 1         | 1      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 135       | 29.28%  |
| 251-500        | 117       | 25.38%  |
| 501-1000       | 56        | 12.15%  |
| 1001-2000      | 36        | 7.81%   |
| 1-20           | 33        | 7.16%   |
| 51-100         | 32        | 6.94%   |
| 21-50          | 19        | 4.12%   |
| Unknown        | 12        | 2.6%    |
| More than 3000 | 11        | 2.39%   |
| 2001-3000      | 10        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 192       | 40.08%  |
| 21-50          | 92        | 19.21%  |
| 51-100         | 64        | 13.36%  |
| 101-250        | 60        | 12.53%  |
| 251-500        | 24        | 5.01%   |
| 501-1000       | 20        | 4.18%   |
| Unknown        | 12        | 2.51%   |
| 1001-2000      | 8         | 1.67%   |
| 2001-3000      | 5         | 1.04%   |
| More than 3000 | 2         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HDS721050CLA362 500GB                  | 5         | 10     | 10.2%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 5      | 6.12%   |
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 4.08%   |
| Seagate ST2000LM007-1R8174 2TB                 | 2         | 3      | 4.08%   |
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 2      | 4.08%   |
| WDC WD5003ABYZ-011FA0 500GB                    | 1         | 1      | 2.04%   |
| WDC WD5000LPVT-75G33T0 500GB                   | 1         | 1      | 2.04%   |
| WDC WD5000LPVT-22G33T0 500GB                   | 1         | 1      | 2.04%   |
| WDC WD5000AAKX-603CA0 500GB                    | 1         | 1      | 2.04%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 2.04%   |
| WDC WD3200AAJS-08L7A0 320GB                    | 1         | 1      | 2.04%   |
| WDC WD1600BEVT-24A23T0 160GB                   | 1         | 1      | 2.04%   |
| WDC WD10JPVX-60JC3T1 1TB                       | 1         | 1      | 2.04%   |
| WDC WD10EZEX-00MFCA0 1TB                       | 1         | 1      | 2.04%   |
| Unknown S050 Hard drive 500GB                  | 1         | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.04%   |
| Toshiba MK6465GSX 640GB                        | 1         | 1      | 2.04%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 2.04%   |
| Toshiba MK2555GSX 250GB                        | 1         | 1      | 2.04%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 2.04%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 2.04%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD          | 1         | 1      | 2.04%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.04%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 2.04%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 2      | 2.04%   |
| Seagate ST380815AS 80GB                        | 1         | 1      | 2.04%   |
| Seagate ST3500514NS 500GB                      | 1         | 1      | 2.04%   |
| Seagate ST3500418AS 500GB                      | 1         | 1      | 2.04%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 2.04%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.04%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 2.04%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 2      | 2.04%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 2.04%   |
| Hitachi HTS542525K9SA00 250GB                  | 1         | 1      | 2.04%   |
| Hitachi HDS721050CLA660 500GB                  | 1         | 1      | 2.04%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.04%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 2.04%   |
| Fujitsu MHY2120BH 120GB                        | 1         | 1      | 2.04%   |
| Colorful SL300 128GB SSD                       | 1         | 1      | 2.04%   |
| A-DATA Technology SX6000PNP 512GB              | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 10        | 12     | 22.22%  |
| WDC               | 9         | 9      | 20%     |
| Hitachi           | 9         | 20     | 20%     |
| Toshiba           | 7         | 8      | 15.56%  |
| HGST              | 2         | 2      | 4.44%   |
| Unknown           | 1         | 1      | 2.22%   |
| SK hynix          | 1         | 1      | 2.22%   |
| Ramsta            | 1         | 1      | 2.22%   |
| Micron Technology | 1         | 1      | 2.22%   |
| Kingston          | 1         | 1      | 2.22%   |
| Fujitsu           | 1         | 1      | 2.22%   |
| Colorful          | 1         | 1      | 2.22%   |
| A-DATA Technology | 1         | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 12     | 25.64%  |
| WDC     | 9         | 9      | 23.08%  |
| Hitachi | 9         | 20     | 23.08%  |
| Toshiba | 7         | 8      | 17.95%  |
| HGST    | 2         | 2      | 5.13%   |
| Unknown | 1         | 1      | 2.56%   |
| Fujitsu | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 53     | 85.37%  |
| SSD  | 5         | 5      | 12.2%   |
| NVMe | 1         | 1      | 2.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 290       | 543    | 63.04%  |
| Works    | 129       | 210    | 28.04%  |
| Malfunc  | 40        | 59     | 8.7%    |
| Failed   | 1         | 1      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 294       | 60.37%  |
| AMD                              | 87        | 17.86%  |
| Samsung Electronics              | 19        | 3.9%    |
| Nvidia                           | 14        | 2.87%   |
| SK hynix                         | 10        | 2.05%   |
| SanDisk                          | 9         | 1.85%   |
| Phison Electronics               | 8         | 1.64%   |
| Kingston Technology Company      | 7         | 1.44%   |
| Micron/Crucial Technology        | 6         | 1.23%   |
| Silicon Motion                   | 5         | 1.03%   |
| Toshiba America Info Systems     | 4         | 0.82%   |
| Micron Technology                | 4         | 0.82%   |
| Silicon Integrated Systems [SiS] | 3         | 0.62%   |
| Marvell Technology Group         | 3         | 0.62%   |
| Lite-On Technology               | 3         | 0.62%   |
| Solid State Storage Technology   | 2         | 0.41%   |
| Realtek Semiconductor            | 2         | 0.41%   |
| ADATA Technology                 | 2         | 0.41%   |
| Union Memory (Shenzhen)          | 1         | 0.21%   |
| Lenovo                           | 1         | 0.21%   |
| KIOXIA                           | 1         | 0.21%   |
| Broadcom / LSI                   | 1         | 0.21%   |
| ASMedia Technology               | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 59        | 10.26%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 32        | 5.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 25        | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 20        | 3.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 17        | 2.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 14        | 2.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 2.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13        | 2.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 1.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 1.74%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9         | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.57%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 9         | 1.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 8         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.39%   |
| Nvidia MCP61 SATA Controller                                                            | 7         | 1.22%   |
| Nvidia MCP61 IDE                                                                        | 7         | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 7         | 1.22%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 7         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6         | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 6         | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.04%   |
| AMD FCH IDE Controller                                                                  | 6         | 1.04%   |
| AMD 300 Series Chipset SATA Controller                                                  | 6         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5         | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 0.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 0.87%   |
| AMD FCH SATA Controller D                                                               | 5         | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 329       | 65.15%  |
| NVMe | 82        | 16.24%  |
| IDE  | 63        | 12.48%  |
| RAID | 30        | 5.94%   |
| SAS  | 1         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 317       | 73.55%  |
| AMD    | 106       | 24.59%  |
| ARM    | 8         | 1.86%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.62%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 1.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.39%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 6         | 1.39%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.16%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 5         | 1.16%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.16%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 5         | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.93%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.93%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.93%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.93%   |
| ARM Processor                                 | 4         | 0.93%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.93%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 4         | 0.93%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.93%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.7%    |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 0.7%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 3         | 0.7%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 0.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.7%    |
| AMD Sempron Processor LE-1100                 | 3         | 0.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.7%    |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 3         | 0.7%    |
| AMD A6-6400K APU with Radeon HD Graphics      | 3         | 0.7%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.46%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.46%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 2         | 0.46%   |
| Intel Genuine CPU T2060 @ 1.60GHz             | 2         | 0.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.46%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 102       | 23.67%  |
| Intel Core i7           | 63        | 14.62%  |
| Intel Core i3           | 38        | 8.82%   |
| Intel Celeron           | 38        | 8.82%   |
| AMD Ryzen 5             | 27        | 6.26%   |
| Other                   | 21        | 4.87%   |
| Intel Core 2 Duo        | 18        | 4.18%   |
| Intel Atom              | 12        | 2.78%   |
| Intel Pentium           | 11        | 2.55%   |
| AMD Ryzen 7             | 10        | 2.32%   |
| AMD Ryzen 3             | 10        | 2.32%   |
| AMD A6                  | 9         | 2.09%   |
| Intel Pentium Dual-Core | 8         | 1.86%   |
| AMD A8                  | 8         | 1.86%   |
| AMD FX                  | 5         | 1.16%   |
| AMD Athlon              | 5         | 1.16%   |
| AMD A10                 | 5         | 1.16%   |
| AMD A4                  | 4         | 0.93%   |
| Intel Core 2 Quad       | 3         | 0.7%    |
| AMD Sempron             | 3         | 0.7%    |
| AMD Ryzen 9             | 3         | 0.7%    |
| AMD Athlon II X2        | 3         | 0.7%    |
| Intel Pentium Gold      | 2         | 0.46%   |
| Intel Genuine           | 2         | 0.46%   |
| AMD Turion 64 X2 Mobile | 2         | 0.46%   |
| AMD Phenom II X4        | 2         | 0.46%   |
| Intel Xeon              | 1         | 0.23%   |
| Intel Pentium Silver    | 1         | 0.23%   |
| Intel Pentium Dual      | 1         | 0.23%   |
| Intel Core m3           | 1         | 0.23%   |
| Intel Core i9           | 1         | 0.23%   |
| Intel Core 2            | 1         | 0.23%   |
| Intel Celeron M         | 1         | 0.23%   |
| ARM BCM                 | 1         | 0.23%   |
| AMD Ryzen 7 PRO         | 1         | 0.23%   |
| AMD Quad-Core           | 1         | 0.23%   |
| AMD PRO A10             | 1         | 0.23%   |
| AMD Phenom II X2        | 1         | 0.23%   |
| AMD G                   | 1         | 0.23%   |
| AMD E2                  | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 203       | 47.1%   |
| 4      | 153       | 35.5%   |
| 6      | 33        | 7.66%   |
| 1      | 22        | 5.1%    |
| 8      | 14        | 3.25%   |
| 16     | 2         | 0.46%   |
| 14     | 1         | 0.23%   |
| 12     | 1         | 0.23%   |
| 10     | 1         | 0.23%   |
| 3      | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 430       | 99.77%  |
| 2      | 1         | 0.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 277       | 64.27%  |
| 1      | 154       | 35.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 414       | 95.39%  |
| Unknown        | 15        | 3.46%   |
| 32-bit         | 4         | 0.92%   |
| 64-bit         | 1         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 24.72%  |
| 0x306a9    | 29        | 6.58%   |
| 0x206a7    | 23        | 5.22%   |
| 0x1067a    | 20        | 4.54%   |
| 0x306c3    | 18        | 4.08%   |
| 0x806ea    | 13        | 2.95%   |
| 0x506c9    | 12        | 2.72%   |
| 0x906ea    | 11        | 2.49%   |
| 0x406e3    | 10        | 2.27%   |
| 0x806e9    | 9         | 2.04%   |
| 0x30678    | 9         | 2.04%   |
| 0x806ec    | 8         | 1.81%   |
| 0x40651    | 8         | 1.81%   |
| 0x906e9    | 7         | 1.59%   |
| 0x506e3    | 7         | 1.59%   |
| 0x306d4    | 7         | 1.59%   |
| 0x06003106 | 7         | 1.59%   |
| 0x06001119 | 7         | 1.59%   |
| 0x10676    | 6         | 1.36%   |
| 0x08701021 | 6         | 1.36%   |
| 0x08108109 | 6         | 1.36%   |
| 0x0800820d | 6         | 1.36%   |
| 0x706a1    | 5         | 1.13%   |
| 0x406c4    | 5         | 1.13%   |
| 0x106ca    | 5         | 1.13%   |
| 0x0a50000c | 5         | 1.13%   |
| 0xa0652    | 4         | 0.91%   |
| 0x806c1    | 4         | 0.91%   |
| 0x706e5    | 4         | 0.91%   |
| 0x20655    | 4         | 0.91%   |
| 0x08600106 | 4         | 0.91%   |
| 0x0810100b | 4         | 0.91%   |
| 0xa0671    | 3         | 0.68%   |
| 0x406c3    | 3         | 0.68%   |
| 0x20652    | 3         | 0.68%   |
| 0x07030105 | 3         | 0.68%   |
| 0x0700010f | 3         | 0.68%   |
| 0x6fb      | 2         | 0.45%   |
| 0x6ec      | 2         | 0.45%   |
| 0x30661    | 2         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 15.55%  |
| IvyBridge        | 39        | 9.05%   |
| Haswell          | 32        | 7.42%   |
| Penryn           | 29        | 6.73%   |
| SandyBridge      | 25        | 5.8%    |
| Skylake          | 22        | 5.1%    |
| Zen+             | 20        | 4.64%   |
| Silvermont       | 18        | 4.18%   |
| Zen 2            | 14        | 3.25%   |
| Piledriver       | 14        | 3.25%   |
| Goldmont         | 14        | 3.25%   |
| Unknown          | 12        | 2.78%   |
| CometLake        | 11        | 2.55%   |
| Zen              | 10        | 2.32%   |
| Broadwell        | 10        | 2.32%   |
| Westmere         | 9         | 2.09%   |
| Bonnell          | 9         | 2.09%   |
| Steamroller      | 8         | 1.86%   |
| Zen 3            | 7         | 1.62%   |
| K8 Hammer        | 7         | 1.62%   |
| TigerLake        | 6         | 1.39%   |
| K10              | 6         | 1.39%   |
| Icelake          | 6         | 1.39%   |
| Goldmont plus    | 6         | 1.39%   |
| Excavator        | 6         | 1.39%   |
| Puma             | 4         | 0.93%   |
| Core             | 4         | 0.93%   |
| P6               | 3         | 0.7%    |
| Jaguar           | 3         | 0.7%    |
| Alderlake Hybrid | 3         | 0.7%    |
| Nehalem          | 2         | 0.46%   |
| Bobcat           | 2         | 0.46%   |
| K8 & K10 hybrid  | 1         | 0.23%   |
| K10 Llano        | 1         | 0.23%   |
| Bulldozer        | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 270       | 51.33%  |
| Nvidia                           | 135       | 25.67%  |
| AMD                              | 118       | 22.43%  |
| Silicon Integrated Systems [SiS] | 3         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 5.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.25%   |
| Intel UHD Graphics 620                                                                   | 17        | 3.14%   |
| Intel HD Graphics 500                                                                    | 13        | 2.4%    |
| Intel HD Graphics 620                                                                    | 12        | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 1.85%   |
| Intel HD Graphics 630                                                                    | 10        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.85%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 1.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.48%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 1.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 1.29%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.11%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 6         | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.11%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.11%   |
| AMD Renoir                                                                               | 6         | 1.11%   |
| AMD Cezanne                                                                              | 6         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.92%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 5         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 0.92%   |
| Intel HD Graphics 530                                                                    | 5         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 4         | 0.74%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 185       | 42.24%  |
| 1 x AMD        | 81        | 18.49%  |
| 1 x Nvidia     | 62        | 14.16%  |
| Intel + Nvidia | 60        | 13.7%   |
| Intel + AMD    | 19        | 4.34%   |
| AMD + Nvidia   | 10        | 2.28%   |
| Other          | 8         | 1.83%   |
| 2 x AMD        | 8         | 1.83%   |
| 1 x SiS        | 3         | 0.68%   |
| 2 x Nvidia     | 2         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 338       | 77.52%  |
| Proprietary | 75        | 17.2%   |
| Unknown     | 23        | 5.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 267       | 59.87%  |
| 1.01-2.0   | 56        | 12.56%  |
| 0.01-0.5   | 41        | 9.19%   |
| 0.51-1.0   | 33        | 7.4%    |
| 3.01-4.0   | 26        | 5.83%   |
| 5.01-6.0   | 9         | 2.02%   |
| 7.01-8.0   | 8         | 1.79%   |
| 8.01-16.0  | 4         | 0.9%    |
| 2.01-3.0   | 2         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 55        | 12.01%  |
| AU Optronics            | 54        | 11.79%  |
| Chimei Innolux          | 50        | 10.92%  |
| BOE                     | 43        | 9.39%   |
| LG Display              | 33        | 7.21%   |
| Dell                    | 27        | 5.9%    |
| Acer                    | 19        | 4.15%   |
| AOC                     | 18        | 3.93%   |
| Lenovo                  | 14        | 3.06%   |
| Hewlett-Packard         | 10        | 2.18%   |
| Goldstar                | 10        | 2.18%   |
| Ancor Communications    | 10        | 2.18%   |
| Sony                    | 8         | 1.75%   |
| BenQ                    | 8         | 1.75%   |
| ASUSTek Computer        | 8         | 1.75%   |
| Sharp                   | 6         | 1.31%   |
| InfoVision              | 6         | 1.31%   |
| Apple                   | 6         | 1.31%   |
| Philips                 | 5         | 1.09%   |
| ViewSonic               | 4         | 0.87%   |
| PANDA                   | 4         | 0.87%   |
| Unknown                 | 3         | 0.66%   |
| IPS                     | 3         | 0.66%   |
| Chi Mei Optoelectronics | 3         | 0.66%   |
| VIE                     | 2         | 0.44%   |
| RTK                     | 2         | 0.44%   |
| Pixio                   | 2         | 0.44%   |
| MStar                   | 2         | 0.44%   |
| Mi                      | 2         | 0.44%   |
| LG Philips              | 2         | 0.44%   |
| InnoLux Display         | 2         | 0.44%   |
| GDH                     | 2         | 0.44%   |
| eMachines               | 2         | 0.44%   |
| Eizo                    | 2         | 0.44%   |
| CTV                     | 2         | 0.44%   |
| Unknown                 | 2         | 0.44%   |
| ___                     | 1         | 0.22%   |
| Unknown (XXX)           | 1         | 0.22%   |
| Toshiba                 | 1         | 0.22%   |
| TMX                     | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 1.5%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 5         | 1.07%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 5         | 1.07%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 5         | 1.07%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.85%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 4         | 0.85%   |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                    | 4         | 0.85%   |
| AOC 2060W AOC2060 1600x900 432x240mm 19.5-inch                        | 4         | 0.85%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 4         | 0.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3         | 0.64%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 3         | 0.64%   |
| Lenovo L1951p Wide LEN0990 1440x900 408x255mm 18.9-inch               | 3         | 0.64%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 3         | 0.64%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 0.64%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 3         | 0.64%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 0.64%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.64%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 0.64%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                      | 2         | 0.43%   |
| Sony TV SNYAB03 1920x1080                                             | 2         | 0.43%   |
| Sony TV SNYA301 1920x1080                                             | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 2         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 2         | 0.43%   |
| RTK 32V3H-H6A RTK4C54 1440x900 697x392mm 31.5-inch                    | 2         | 0.43%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 0.43%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.43%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.43%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.43%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.43%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 2         | 0.43%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.43%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2         | 0.43%   |
| Dell P2214H DELA097 1920x1080 477x268mm 21.5-inch                     | 2         | 0.43%   |
| Dell OptiPlex 9010 DEL1111 1920x1080 510x286mm 23.0-inch              | 2         | 0.43%   |
| Dell E207WFP DELD010 1680x1050 430x270mm 20.0-inch                    | 2         | 0.43%   |
| Dell E198FP DELA028 1280x1024 376x301mm 19.0-inch                     | 2         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 166       | 38.43%  |
| 1366x768 (WXGA)    | 156       | 36.11%  |
| 1600x900 (HD+)     | 23        | 5.32%   |
| 1280x1024 (SXGA)   | 20        | 4.63%   |
| 3840x2160 (4K)     | 15        | 3.47%   |
| 1440x900 (WXGA+)   | 9         | 2.08%   |
| 1024x600           | 7         | 1.62%   |
| 1280x800 (WXGA)    | 6         | 1.39%   |
| 1920x1200 (WUXGA)  | 5         | 1.16%   |
| 2560x1440 (QHD)    | 4         | 0.93%   |
| 1360x768           | 4         | 0.93%   |
| 2160x1440          | 3         | 0.69%   |
| 1920x540           | 3         | 0.69%   |
| 3440x1440          | 2         | 0.46%   |
| 1680x1050 (WSXGA+) | 2         | 0.46%   |
| 3200x1080          | 1         | 0.23%   |
| 2560x1600          | 1         | 0.23%   |
| 2400x1600          | 1         | 0.23%   |
| 2288x1287          | 1         | 0.23%   |
| 1600x1200          | 1         | 0.23%   |
| 1024x768 (XGA)     | 1         | 0.23%   |
| Unknown            | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 105       | 22.88%  |
| 13      | 55        | 11.98%  |
| 14      | 38        | 8.28%   |
| 23      | 33        | 7.19%   |
| 18      | 32        | 6.97%   |
| 17      | 28        | 6.1%    |
| 21      | 21        | 4.58%   |
| 11      | 19        | 4.14%   |
| 27      | 16        | 3.49%   |
| 24      | 16        | 3.49%   |
| 20      | 15        | 3.27%   |
| Unknown | 15        | 3.27%   |
| 19      | 14        | 3.05%   |
| 12      | 10        | 2.18%   |
| 72      | 8         | 1.74%   |
| 31      | 7         | 1.53%   |
| 10      | 7         | 1.53%   |
| 32      | 6         | 1.31%   |
| 52      | 4         | 0.87%   |
| 40      | 2         | 0.44%   |
| 142     | 1         | 0.22%   |
| 54      | 1         | 0.22%   |
| 50      | 1         | 0.22%   |
| 47      | 1         | 0.22%   |
| 39      | 1         | 0.22%   |
| 34      | 1         | 0.22%   |
| 22      | 1         | 0.22%   |
| 16      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 193       | 42.98%  |
| 401-500        | 76        | 16.93%  |
| 501-600        | 60        | 13.36%  |
| 201-300        | 53        | 11.8%   |
| 351-400        | 17        | 3.79%   |
| Unknown        | 15        | 3.34%   |
| 601-700        | 9         | 2%      |
| 1501-2000      | 8         | 1.78%   |
| 701-800        | 7         | 1.56%   |
| 1001-1500      | 7         | 1.56%   |
| 801-900        | 3         | 0.67%   |
| More than 2000 | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 349       | 84.5%   |
| 16/10   | 26        | 6.3%    |
| 5/4     | 17        | 4.12%   |
| Unknown | 14        | 3.39%   |
| 3/2     | 3         | 0.73%   |
| 6/5     | 1         | 0.24%   |
| 4/3     | 1         | 0.24%   |
| 21/9    | 1         | 0.24%   |
| 1.00    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 102       | 22.62%  |
| 81-90          | 79        | 17.52%  |
| 201-250        | 55        | 12.2%   |
| 141-150        | 45        | 9.98%   |
| 151-200        | 36        | 7.98%   |
| 51-60          | 19        | 4.21%   |
| 301-350        | 16        | 3.55%   |
| More than 1000 | 15        | 3.33%   |
| Unknown        | 15        | 3.33%   |
| 71-80          | 14        | 3.1%    |
| 351-500        | 14        | 3.1%    |
| 121-130        | 12        | 2.66%   |
| 61-70          | 10        | 2.22%   |
| 41-50          | 7         | 1.55%   |
| 501-1000       | 4         | 0.89%   |
| 251-300        | 3         | 0.67%   |
| 91-100         | 3         | 0.67%   |
| 131-140        | 1         | 0.22%   |
| 111-120        | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 152       | 34.31%  |
| 51-100        | 134       | 30.25%  |
| 121-160       | 110       | 24.83%  |
| 1-50          | 17        | 3.84%   |
| Unknown       | 15        | 3.39%   |
| 161-240       | 12        | 2.71%   |
| More than 240 | 3         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 361       | 81.67%  |
| 2     | 57        | 12.9%   |
| 0     | 21        | 4.75%   |
| 3     | 3         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 266       | 41.76%  |
| Intel                             | 153       | 24.02%  |
| Qualcomm Atheros                  | 90        | 14.13%  |
| Broadcom                          | 42        | 6.59%   |
| Ralink Technology                 | 21        | 3.3%    |
| Nvidia                            | 10        | 1.57%   |
| TP-Link                           | 7         | 1.1%    |
| Broadcom Limited                  | 7         | 1.1%    |
| Marvell Technology Group          | 4         | 0.63%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.47%   |
| Samsung Electronics               | 3         | 0.47%   |
| Linksys                           | 3         | 0.47%   |
| JMicron Technology                | 3         | 0.47%   |
| Huawei Technologies               | 3         | 0.47%   |
| Xiaomi                            | 2         | 0.31%   |
| Ralink                            | 2         | 0.31%   |
| Qualcomm Atheros Communications   | 2         | 0.31%   |
| OPPO Electronics                  | 2         | 0.31%   |
| D-Link                            | 2         | 0.31%   |
| Tenda                             | 1         | 0.16%   |
| Sundance Technology Inc / IC Plus | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| NetGear                           | 1         | 0.16%   |
| MediaTek                          | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Encore Electronics                | 1         | 0.16%   |
| Dell                              | 1         | 0.16%   |
| D-Link System                     | 1         | 0.16%   |
| BUFFALO                           | 1         | 0.16%   |
| ASIX Electronics                  | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 199       | 26.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 2.29%   |
| Intel Wireless 7265                                               | 15        | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 14        | 1.89%   |
| Ralink MT7601U Wireless Adapter                                   | 13        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.48%   |
| Intel Wireless 3165                                               | 11        | 1.48%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 9         | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.81%   |
| Intel Wireless 7260                                               | 6         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.67%   |
| Realtek 802.11ac NIC                                              | 5         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.67%   |
| Nvidia MCP61 Ethernet                                             | 5         | 0.67%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.67%   |
| Intel Wireless 8260                                               | 5         | 0.67%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.54%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.54%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 133       | 38.33%  |
| Qualcomm Atheros                | 72        | 20.75%  |
| Realtek Semiconductor           | 64        | 18.44%  |
| Broadcom                        | 29        | 8.36%   |
| Ralink Technology               | 21        | 6.05%   |
| TP-Link                         | 7         | 2.02%   |
| Broadcom Limited                | 4         | 1.15%   |
| Linksys                         | 3         | 0.86%   |
| Ralink                          | 2         | 0.58%   |
| Qualcomm Atheros Communications | 2         | 0.58%   |
| D-Link                          | 2         | 0.58%   |
| Tenda                           | 1         | 0.29%   |
| Samsung Electronics             | 1         | 0.29%   |
| NetGear                         | 1         | 0.29%   |
| MediaTek                        | 1         | 0.29%   |
| Marvell Technology Group        | 1         | 0.29%   |
| Encore Electronics              | 1         | 0.29%   |
| Dell                            | 1         | 0.29%   |
| BUFFALO                         | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter               | 17        | 4.87%   |
| Intel Wireless 7265                                                      | 15        | 4.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter               | 14        | 4.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                         | 14        | 4.01%   |
| Ralink MT7601U Wireless Adapter                                          | 13        | 3.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)           | 12        | 3.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                          | 11        | 3.15%   |
| Intel Wireless 3165                                                      | 11        | 3.15%   |
| Intel Wi-Fi 6 AX200                                                      | 10        | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                             | 9         | 2.58%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                      | 9         | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                         | 8         | 2.29%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                         | 8         | 2.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter               | 7         | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                          | 7         | 2.01%   |
| Broadcom BCM43142 802.11b/g/n                                            | 7         | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                 | 6         | 1.72%   |
| Intel Wireless 7260                                                      | 6         | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                           | 6         | 1.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                          | 5         | 1.43%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                 | 5         | 1.43%   |
| Realtek 802.11ac NIC                                                     | 5         | 1.43%   |
| Intel Wireless 8265 / 8275                                               | 5         | 1.43%   |
| Intel Wireless 8260                                                      | 5         | 1.43%   |
| Intel Wi-Fi 6 AX201                                                      | 5         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                        | 5         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                 | 4         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                      | 4         | 1.15%   |
| Intel Centrino Advanced-N 6235                                           | 4         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                       | 3         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                 | 3         | 0.86%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                    | 3         | 0.86%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                 | 3         | 0.86%   |
| Ralink RT5370 Wireless Adapter                                           | 3         | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                    | 3         | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)  | 3         | 0.86%   |
| Linksys WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3         | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                          | 3         | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                          | 3         | 0.86%   |
| Intel Centrino Wireless-N 2200                                           | 3         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 250       | 64.77%  |
| Intel                             | 61        | 15.8%   |
| Qualcomm Atheros                  | 26        | 6.74%   |
| Broadcom                          | 16        | 4.15%   |
| Nvidia                            | 10        | 2.59%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.78%   |
| Marvell Technology Group          | 3         | 0.78%   |
| JMicron Technology                | 3         | 0.78%   |
| Broadcom Limited                  | 3         | 0.78%   |
| Xiaomi                            | 2         | 0.52%   |
| OPPO Electronics                  | 2         | 0.52%   |
| Huawei Technologies               | 2         | 0.52%   |
| Sundance Technology Inc / IC Plus | 1         | 0.26%   |
| Qualcomm                          | 1         | 0.26%   |
| ICS Advent                        | 1         | 0.26%   |
| D-Link System                     | 1         | 0.26%   |
| ASIX Electronics                  | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 199       | 51.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 39        | 10.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 3.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.29%   |
| Nvidia MCP61 Ethernet                                             | 5         | 1.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 1.03%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.77%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.51%   |
| OPPO RMX2180                                                      | 2         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.51%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.51%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.51%   |
| Huawei LYA-L09                                                    | 2         | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.51%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.26%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 371       | 52.48%  |
| WiFi     | 332       | 46.96%  |
| Modem    | 4         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 265       | 60.36%  |
| Ethernet | 174       | 39.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 231       | 53.47%  |
| 1     | 181       | 41.9%   |
| 0     | 12        | 2.78%   |
| 3     | 8         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 399       | 91.72%  |
| Yes  | 36        | 8.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 39.76%  |
| Realtek Semiconductor           | 31        | 12.2%   |
| Qualcomm Atheros Communications | 20        | 7.87%   |
| Lite-On Technology              | 20        | 7.87%   |
| Broadcom                        | 19        | 7.48%   |
| IMC Networks                    | 14        | 5.51%   |
| Foxconn / Hon Hai               | 14        | 5.51%   |
| Cambridge Silicon Radio         | 14        | 5.51%   |
| Apple                           | 8         | 3.15%   |
| Toshiba                         | 3         | 1.18%   |
| Hewlett-Packard                 | 3         | 1.18%   |
| Dell                            | 2         | 0.79%   |
| Chicony Electronics             | 2         | 0.79%   |
| Ralink                          | 1         | 0.39%   |
| Marvell Semiconductor           | 1         | 0.39%   |
| Integrated System Solution      | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 41        | 16.14%  |
| Intel AX201 Bluetooth                               | 19        | 7.48%   |
| Realtek Bluetooth Radio                             | 18        | 7.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14        | 5.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 5.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 3.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 3.94%   |
| Intel AX200 Bluetooth                               | 9         | 3.54%   |
| IMC Networks Bluetooth Device                       | 8         | 3.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.36%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 2.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 1.97%   |
| Lite-On Bluetooth Device                            | 5         | 1.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.57%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.57%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.57%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.18%   |
| Realtek RTL8723B Bluetooth                          | 3         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.18%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 1.18%   |
| Apple Bluetooth Host Controller                     | 3         | 1.18%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.79%   |
| Lite-On BCM43142A0                                  | 2         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.79%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.79%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.79%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 0.79%   |
| Broadcom HP Portable Valentine                      | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.79%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.79%   |
| Broadcom BCM2035 Bluetooth                          | 2         | 0.79%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.79%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.39%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.39%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 305       | 54.66%  |
| AMD                              | 111       | 19.89%  |
| Nvidia                           | 93        | 16.67%  |
| Generalplus Technology           | 6         | 1.08%   |
| C-Media Electronics              | 6         | 1.08%   |
| Logitech                         | 4         | 0.72%   |
| SteelSeries ApS                  | 3         | 0.54%   |
| Silicon Integrated Systems [SiS] | 3         | 0.54%   |
| Plantronics                      | 3         | 0.54%   |
| Realtek Semiconductor            | 2         | 0.36%   |
| JMTek                            | 2         | 0.36%   |
| GN Netcom                        | 2         | 0.36%   |
| DCMT Technology                  | 2         | 0.36%   |
| ZOOM                             | 1         | 0.18%   |
| XMOS                             | 1         | 0.18%   |
| Razer USA                        | 1         | 0.18%   |
| OPPO Electronics                 | 1         | 0.18%   |
| Micronas                         | 1         | 0.18%   |
| Kingston Technology              | 1         | 0.18%   |
| Giga-Byte Technology             | 1         | 0.18%   |
| Focusrite-Novation               | 1         | 0.18%   |
| FiiO Electronics Technology      | 1         | 0.18%   |
| FIFINE 683 Microphone            | 1         | 0.18%   |
| Elgato Systems                   | 1         | 0.18%   |
| DEXP BK-20                       | 1         | 0.18%   |
| Creative Technology              | 1         | 0.18%   |
| Corsair                          | 1         | 0.18%   |
| Cooler Master                    | 1         | 0.18%   |
| ASUSTek Computer                 | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 43        | 6.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 36        | 5.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 34        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 30        | 4.5%    |
| AMD FCH Azalia Controller                                                                         | 29        | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 25        | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 2.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 2.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 2.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 1.65%   |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.35%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.2%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 8         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 1.05%   |
| Nvidia MCP61 High Definition Audio                                                                | 7         | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.9%    |
| Generalplus Technology USB Audio Device                                                           | 6         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 46        | 19.74%  |
| Samsung Electronics | 44        | 18.88%  |
| SK hynix            | 40        | 17.17%  |
| Unknown             | 21        | 9.01%   |
| Micron Technology   | 17        | 7.3%    |
| Team                | 11        | 4.72%   |
| Ramaxel Technology  | 8         | 3.43%   |
| G.Skill             | 8         | 3.43%   |
| Corsair             | 6         | 2.58%   |
| Crucial             | 5         | 2.15%   |
| Elpida              | 4         | 1.72%   |
| Transcend           | 3         | 1.29%   |
| Unknown             | 3         | 1.29%   |
| Unknown (ABCD)      | 2         | 0.86%   |
| Patriot             | 2         | 0.86%   |
| Nanya Technology    | 2         | 0.86%   |
| Kingmax             | 2         | 0.86%   |
| A-DATA Technology   | 2         | 0.86%   |
| Uroad               | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| Mitsubishi          | 1         | 0.43%   |
| Carry               | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| ASint Technology    | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 2.02%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 2.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 2.02%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 1.21%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.21%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.21%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 1.21%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.21%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 3         | 1.21%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.21%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 3         | 1.21%   |
| Unknown                                                          | 3         | 1.21%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.81%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 2         | 0.81%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 2         | 0.81%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.81%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                  | 2         | 0.81%   |
| Micron RAM Module 4GB Row Of Chips LPDDR4 4267MT/s               | 2         | 0.81%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.81%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 0.81%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.81%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Corsair RAM CMT128GX4M4C3200C16 32GB DIMM DDR4 3200MT/s          | 2         | 0.81%   |
| Corsair RAM CML8GX3M2A1600C9 4GB DIMM DDR3 1867MT/s              | 2         | 0.81%   |
| Uroad RAM WJD8G4M16P12800 8192MB DIMM DDR3 1600MT/s              | 1         | 0.4%    |
| Unknown RAM Module 8192MB DIMM                                   | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3 1866MT/s                      | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 95        | 49.74%  |
| DDR3    | 69        | 36.13%  |
| DDR2    | 11        | 5.76%   |
| LPDDR4  | 6         | 3.14%   |
| Unknown | 4         | 2.09%   |
| SDRAM   | 2         | 1.05%   |
| LPDDR3  | 1         | 0.52%   |
| DRAM    | 1         | 0.52%   |
| DDR5    | 1         | 0.52%   |
| DDR     | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 121       | 64.02%  |
| DIMM         | 60        | 31.75%  |
| Row Of Chips | 8         | 4.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 81        | 37.5%   |
| 4096  | 74        | 34.26%  |
| 2048  | 23        | 10.65%  |
| 16384 | 18        | 8.33%   |
| 1024  | 11        | 5.09%   |
| 32768 | 9         | 4.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 24.17%  |
| 2667    | 37        | 17.54%  |
| 3200    | 25        | 11.85%  |
| 2400    | 20        | 9.48%   |
| 2133    | 12        | 5.69%   |
| 667     | 10        | 4.74%   |
| 1333    | 9         | 4.27%   |
| 1334    | 7         | 3.32%   |
| 3600    | 5         | 2.37%   |
| Unknown | 4         | 1.9%    |
| 3866    | 3         | 1.42%   |
| 3266    | 3         | 1.42%   |
| 8400    | 2         | 0.95%   |
| 4267    | 2         | 0.95%   |
| 3800    | 2         | 0.95%   |
| 2666    | 2         | 0.95%   |
| 1867    | 2         | 0.95%   |
| 1800    | 2         | 0.95%   |
| 800     | 2         | 0.95%   |
| 4800    | 1         | 0.47%   |
| 4266    | 1         | 0.47%   |
| 3733    | 1         | 0.47%   |
| 3500    | 1         | 0.47%   |
| 3466    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 1067    | 1         | 0.47%   |
| 1066    | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| 400     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 4         | 44.44%  |
| Brother Industries | 3         | 33.33%  |
| Canon              | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L120 Series   | 2         | 22.22%  |
| Seiko Epson L3110 Series  | 1         | 11.11%  |
| Seiko Epson L222 Series   | 1         | 11.11%  |
| Canon PIXMA MG2500 Series | 1         | 11.11%  |
| Canon G2010 series        | 1         | 11.11%  |
| Brother DCP-T710W         | 1         | 11.11%  |
| Brother DCP-T700W         | 1         | 11.11%  |
| Brother DCP-T310          | 1         | 11.11%  |

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
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 68        | 24.2%   |
| Realtek Semiconductor                  | 25        | 8.9%    |
| Microdia                               | 22        | 7.83%   |
| IMC Networks                           | 21        | 7.47%   |
| Quanta                                 | 16        | 5.69%   |
| Acer                                   | 16        | 5.69%   |
| Sunplus Innovation Technology          | 12        | 4.27%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.56%   |
| Apple                                  | 9         | 3.2%    |
| Lite-On Technology                     | 8         | 2.85%   |
| Suyin                                  | 7         | 2.49%   |
| Logitech                               | 7         | 2.49%   |
| Silicon Motion                         | 6         | 2.14%   |
| Z-Star Microelectronics                | 5         | 1.78%   |
| Syntek                                 | 5         | 1.78%   |
| Alcor Micro                            | 5         | 1.78%   |
| Samsung Electronics                    | 4         | 1.42%   |
| Jieli Technology                       | 4         | 1.42%   |
| A4Tech                                 | 4         | 1.42%   |
| Pixart Imaging                         | 3         | 1.07%   |
| Luxvisions Innotech Limited            | 3         | 1.07%   |
| Cubeternet                             | 3         | 1.07%   |
| Generalplus Technology                 | 2         | 0.71%   |
| Alpha Imaging Technology               | 2         | 0.71%   |
| ALi                                    | 2         | 0.71%   |
| SunplusIT                              | 1         | 0.36%   |
| Ricoh                                  | 1         | 0.36%   |
| Razer USA                              | 1         | 0.36%   |
| OmniVision Technologies                | 1         | 0.36%   |
| Microsoft                              | 1         | 0.36%   |
| Lenovo                                 | 1         | 0.36%   |
| KYE Systems (Mouse Systems)            | 1         | 0.36%   |
| Importek                               | 1         | 0.36%   |
| Goertek Electronics                    | 1         | 0.36%   |
| GEMBIRD                                | 1         | 0.36%   |
| DigiTech                               | 1         | 0.36%   |
| Aveo Technology                        | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 16        | 5.65%   |
| Chicony HD WebCam                                               | 13        | 4.59%   |
| Realtek Acer 640 x 480 laptop camera                            | 7         | 2.47%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 7         | 2.47%   |
| Realtek Integrated_Webcam_HD                                    | 5         | 1.77%   |
| Quanta HD WebCam                                                | 5         | 1.77%   |
| Microdia Integrated_Webcam_HD                                   | 5         | 1.77%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 5         | 1.77%   |
| Quanta VGA WebCam                                               | 4         | 1.41%   |
| Jieli USB PHY 2.0                                               | 4         | 1.41%   |
| Chicony VGA WebCam                                              | 4         | 1.41%   |
| Z-Star Venus USB2.0 Camera                                      | 3         | 1.06%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 1.06%   |
| Quanta HD User Facing                                           | 3         | 1.06%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                            | 3         | 1.06%   |
| Microdia Sonix USB 2.0 Camera                                   | 3         | 1.06%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 3         | 1.06%   |
| Logitech Webcam C270                                            | 3         | 1.06%   |
| Lite-On Integrated Camera                                       | 3         | 1.06%   |
| IMC Networks Integrated Camera                                  | 3         | 1.06%   |
| Chicony Lenovo EasyCamera                                       | 3         | 1.06%   |
| Chicony HP Wide Vision HD Camera                                | 3         | 1.06%   |
| Chicony HP Truevision HD                                        | 3         | 1.06%   |
| Chicony EasyCamera                                              | 3         | 1.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 1.06%   |
| Apple Built-in iSight                                           | 3         | 1.06%   |
| Acer Lenovo EasyCamera                                          | 3         | 1.06%   |
| Acer Integrated Camera                                          | 3         | 1.06%   |
| Acer EasyCamera                                                 | 3         | 1.06%   |
| A4Tech FHD 1080P PC Camera                                      | 3         | 1.06%   |
| Syntek Lenovo EasyCamera                                        | 2         | 0.71%   |
| Syntek Integrated Camera                                        | 2         | 0.71%   |
| Suyin HP Webcam                                                 | 2         | 0.71%   |
| Sunplus Laptop Integrated WebCam HD                             | 2         | 0.71%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 0.71%   |
| Sunplus Integrated Webcam                                       | 2         | 0.71%   |
| Sunplus HP Truevision HD                                        | 2         | 0.71%   |
| Sunplus HD WebCam                                               | 2         | 0.71%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 0.71%   |
| Realtek Integrated Webcam                                       | 2         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 32.35%  |
| Shenzhen Goodix Technology | 8         | 23.53%  |
| Synaptics                  | 7         | 20.59%  |
| Upek                       | 3         | 8.82%   |
| LighTuning Technology      | 3         | 8.82%   |
| AuthenTec                  | 2         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                        | 5         | 14.71%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 8.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 3         | 8.82%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 5.88%   |
| Synaptics  WBDI                                            | 2         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 5.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.94%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 2.94%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 2.94%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 2.94%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.94%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 2.94%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.94%   |
| AuthenTec Fingerprint Sensor                               | 1         | 2.94%   |
| AuthenTec AES1600                                          | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 4         | 36.36%  |
| Upek             | 3         | 27.27%  |
| O2 Micro         | 2         | 18.18%  |
| SCM Microsystems | 1         | 9.09%   |
| Alcor Micro      | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Broadcom 5880                                                                | 2         | 18.18%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 9.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 337       | 76.42%  |
| 1     | 89        | 20.18%  |
| 2     | 14        | 3.17%   |
| 3     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 28.21%  |
| Graphics card            | 31        | 26.5%   |
| Net/wireless             | 20        | 17.09%  |
| Chipcard                 | 11        | 9.4%    |
| Multimedia controller    | 5         | 4.27%   |
| Net/ethernet             | 4         | 3.42%   |
| Camera                   | 4         | 3.42%   |
| Communication controller | 2         | 1.71%   |
| Unassigned class         | 1         | 0.85%   |
| Storage/raid             | 1         | 0.85%   |
| Storage                  | 1         | 0.85%   |
| Sound                    | 1         | 0.85%   |
| Network                  | 1         | 0.85%   |
| Modem                    | 1         | 0.85%   |
| Bluetooth                | 1         | 0.85%   |

