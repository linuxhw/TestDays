Linux in Peru - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Peru/Desktop/README.md) and [notebooks](/Location/Peru/Notebook/README.md).

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

Total: 818

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B75M-D3H                    | Desktop     | [fd8023f83c](https://linux-hardware.org/?probe=fd8023f83c) | Dec 23, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [a076c3dca9](https://linux-hardware.org/?probe=a076c3dca9) | Dec 20, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [11dc169e95](https://linux-hardware.org/?probe=11dc169e95) | Dec 15, 2024 |
| Gigabyte      | MKLP7AP-00                  | Desktop     | [3468d571f4](https://linux-hardware.org/?probe=3468d571f4) | Dec 12, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [e3ff832ae6](https://linux-hardware.org/?probe=e3ff832ae6) | Dec 11, 2024 |
| HP            | Pavilion g4                 | Notebook    | [be7deb3d00](https://linux-hardware.org/?probe=be7deb3d00) | Dec 10, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [9b636f440a](https://linux-hardware.org/?probe=9b636f440a) | Dec 09, 2024 |
| MSI           | GL72M 7REX                  | Notebook    | [fbeb721328](https://linux-hardware.org/?probe=fbeb721328) | Dec 05, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [9da8aa84aa](https://linux-hardware.org/?probe=9da8aa84aa) | Dec 03, 2024 |
| HP            | Pavilion g4                 | Notebook    | [42bd25b20f](https://linux-hardware.org/?probe=42bd25b20f) | Dec 02, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [6b626eb981](https://linux-hardware.org/?probe=6b626eb981) | Dec 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7af06c00e5](https://linux-hardware.org/?probe=7af06c00e5) | Dec 01, 2024 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [c5069f8fa7](https://linux-hardware.org/?probe=c5069f8fa7) | Nov 29, 2024 |
| HP            | 8954                        | Desktop     | [58001c585c](https://linux-hardware.org/?probe=58001c585c) | Nov 19, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [5bc6ff3fa8](https://linux-hardware.org/?probe=5bc6ff3fa8) | Nov 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JU0... | Notebook    | [9fdbbb1b89](https://linux-hardware.org/?probe=9fdbbb1b89) | Nov 17, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JU0... | Notebook    | [49190049b9](https://linux-hardware.org/?probe=49190049b9) | Nov 17, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [24a60bb59c](https://linux-hardware.org/?probe=24a60bb59c) | Nov 09, 2024 |
| Acer          | Aspire E5-774               | Notebook    | [b81d46ef22](https://linux-hardware.org/?probe=b81d46ef22) | Nov 05, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [f2fb29214a](https://linux-hardware.org/?probe=f2fb29214a) | Nov 05, 2024 |
| ASUSTek       | H81M-A                      | Desktop     | [04eef716a6](https://linux-hardware.org/?probe=04eef716a6) | Nov 01, 2024 |
| Acer          | Aspire E5-774               | Notebook    | [24b5385ac1](https://linux-hardware.org/?probe=24b5385ac1) | Oct 30, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [c7d24d0288](https://linux-hardware.org/?probe=c7d24d0288) | Oct 26, 2024 |
| Dell          | Latitude E7440              | Notebook    | [59f882ef98](https://linux-hardware.org/?probe=59f882ef98) | Oct 25, 2024 |
| Dell          | Latitude E7440              | Notebook    | [48182c2497](https://linux-hardware.org/?probe=48182c2497) | Oct 25, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [0642feaea1](https://linux-hardware.org/?probe=0642feaea1) | Oct 22, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [b13668c203](https://linux-hardware.org/?probe=b13668c203) | Oct 22, 2024 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1c61630c00](https://linux-hardware.org/?probe=1c61630c00) | Oct 20, 2024 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [90eddc4513](https://linux-hardware.org/?probe=90eddc4513) | Oct 20, 2024 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [7bbaac259d](https://linux-hardware.org/?probe=7bbaac259d) | Oct 20, 2024 |
| Dell          | Latitude 5540               | Notebook    | [ba75f2134f](https://linux-hardware.org/?probe=ba75f2134f) | Oct 19, 2024 |
| HP            | 0A60h                       | Desktop     | [382484402a](https://linux-hardware.org/?probe=382484402a) | Oct 07, 2024 |
| Acer          | Aspire A315-59G             | Notebook    | [3c57995295](https://linux-hardware.org/?probe=3c57995295) | Oct 05, 2024 |
| Lenovo        | G585 20137                  | Notebook    | [379f6e6fef](https://linux-hardware.org/?probe=379f6e6fef) | Oct 05, 2024 |
| HP            | Pavilion g4                 | Notebook    | [c705d7afa6](https://linux-hardware.org/?probe=c705d7afa6) | Oct 05, 2024 |
| Foxconn       | M61PMV FAB                  | Desktop     | [1d1eff2e7b](https://linux-hardware.org/?probe=1d1eff2e7b) | Oct 05, 2024 |
| MSI           | 2A9C                        | Desktop     | [61b9b2ee38](https://linux-hardware.org/?probe=61b9b2ee38) | Oct 05, 2024 |
| MSI           | H410M PRO                   | Desktop     | [50719966e4](https://linux-hardware.org/?probe=50719966e4) | Oct 05, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [f216dafbba](https://linux-hardware.org/?probe=f216dafbba) | Oct 04, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9d076b194d](https://linux-hardware.org/?probe=9d076b194d) | Oct 02, 2024 |
| LG Electro... | 22V280 FAB1                 | All in one  | [ea5f223ff6](https://linux-hardware.org/?probe=ea5f223ff6) | Oct 02, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [16c5519c67](https://linux-hardware.org/?probe=16c5519c67) | Sep 30, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a67a357e0a](https://linux-hardware.org/?probe=a67a357e0a) | Sep 29, 2024 |
| Acer          | Aspire A315-55G             | Notebook    | [3f77776e4c](https://linux-hardware.org/?probe=3f77776e4c) | Sep 24, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [6c6276672b](https://linux-hardware.org/?probe=6c6276672b) | Sep 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b73138fbf5](https://linux-hardware.org/?probe=b73138fbf5) | Sep 23, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1eafa59d7a](https://linux-hardware.org/?probe=1eafa59d7a) | Sep 23, 2024 |
| ECS           | Nettle3                     | Desktop     | [805686f76b](https://linux-hardware.org/?probe=805686f76b) | Sep 21, 2024 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [4b0bf4e08e](https://linux-hardware.org/?probe=4b0bf4e08e) | Sep 18, 2024 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [5fa1966f45](https://linux-hardware.org/?probe=5fa1966f45) | Sep 18, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [82245bc2ce](https://linux-hardware.org/?probe=82245bc2ce) | Sep 17, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6e992b017a](https://linux-hardware.org/?probe=6e992b017a) | Sep 17, 2024 |
| Gateway       | NV55C                       | Notebook    | [151ce02b0c](https://linux-hardware.org/?probe=151ce02b0c) | Sep 16, 2024 |
| Gateway       | NV55C                       | Notebook    | [f7170c1236](https://linux-hardware.org/?probe=f7170c1236) | Sep 16, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [54ce0b3d34](https://linux-hardware.org/?probe=54ce0b3d34) | Sep 16, 2024 |
| Google        | Storo                       | Notebook    | [fff45fd343](https://linux-hardware.org/?probe=fff45fd343) | Sep 13, 2024 |
| ECS           | Nettle3                     | Desktop     | [578c7331e4](https://linux-hardware.org/?probe=578c7331e4) | Sep 13, 2024 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [c1712b4ef5](https://linux-hardware.org/?probe=c1712b4ef5) | Sep 12, 2024 |
| Google        | Storo                       | Notebook    | [f39c3f92b1](https://linux-hardware.org/?probe=f39c3f92b1) | Sep 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ac4846a16](https://linux-hardware.org/?probe=1ac4846a16) | Sep 03, 2024 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [8c28139d23](https://linux-hardware.org/?probe=8c28139d23) | Sep 02, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a14eb52976](https://linux-hardware.org/?probe=a14eb52976) | Aug 29, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d0ff8dd9e3](https://linux-hardware.org/?probe=d0ff8dd9e3) | Aug 29, 2024 |
| HP            | Pavilion g4                 | Notebook    | [cee1aebcc0](https://linux-hardware.org/?probe=cee1aebcc0) | Aug 28, 2024 |
| Valve         | Galileo                     | Notebook    | [71ce12da6b](https://linux-hardware.org/?probe=71ce12da6b) | Aug 27, 2024 |
| ASRock        | B760M PG Lightning/D4       | Desktop     | [48b5227623](https://linux-hardware.org/?probe=48b5227623) | Aug 27, 2024 |
| Toshiba       | Satellite C45-A             | Notebook    | [1a81d7fa5c](https://linux-hardware.org/?probe=1a81d7fa5c) | Aug 26, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [b8adeadb11](https://linux-hardware.org/?probe=b8adeadb11) | Aug 25, 2024 |
| Intel         | H61                         | Desktop     | [1fe94737e9](https://linux-hardware.org/?probe=1fe94737e9) | Aug 09, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [d1f86fd641](https://linux-hardware.org/?probe=d1f86fd641) | Aug 08, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [476a7f88c7](https://linux-hardware.org/?probe=476a7f88c7) | Aug 06, 2024 |
| Lenovo        | 3000 N500 4233A14           | Notebook    | [ae44dcd68e](https://linux-hardware.org/?probe=ae44dcd68e) | Aug 01, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [2144af0c60](https://linux-hardware.org/?probe=2144af0c60) | Jul 30, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [df4775b9f4](https://linux-hardware.org/?probe=df4775b9f4) | Jul 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [7cc5cb201a](https://linux-hardware.org/?probe=7cc5cb201a) | Jul 29, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [365d877167](https://linux-hardware.org/?probe=365d877167) | Jul 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9186d6890f](https://linux-hardware.org/?probe=9186d6890f) | Jul 23, 2024 |
| Dell          | G3 3779                     | Notebook    | [20366c590d](https://linux-hardware.org/?probe=20366c590d) | Jul 22, 2024 |
| Dell          | G3 3779                     | Notebook    | [7c990f5b0f](https://linux-hardware.org/?probe=7c990f5b0f) | Jul 22, 2024 |
| ASRock        | Z590 Taichi                 | Desktop     | [34c8d95eb6](https://linux-hardware.org/?probe=34c8d95eb6) | Jul 21, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [96a15691d5](https://linux-hardware.org/?probe=96a15691d5) | Jul 20, 2024 |
| Gigabyte      | H470M H                     | Desktop     | [b76a4fcc5a](https://linux-hardware.org/?probe=b76a4fcc5a) | Jul 17, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [aa85d8c32a](https://linux-hardware.org/?probe=aa85d8c32a) | Jul 15, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [4a98de88bd](https://linux-hardware.org/?probe=4a98de88bd) | Jul 14, 2024 |
| Lenovo        | ThinkPad W540 20BH002NLM    | Notebook    | [98a58c738f](https://linux-hardware.org/?probe=98a58c738f) | Jul 14, 2024 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [23bb574c8c](https://linux-hardware.org/?probe=23bb574c8c) | Jul 11, 2024 |
| Dell          | Precision 3541              | Notebook    | [fd3dbaf3d6](https://linux-hardware.org/?probe=fd3dbaf3d6) | Jul 09, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [2740ab422f](https://linux-hardware.org/?probe=2740ab422f) | Jul 05, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [3a38699cac](https://linux-hardware.org/?probe=3a38699cac) | Jul 03, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3a1445300b](https://linux-hardware.org/?probe=3a1445300b) | Jun 28, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [35390b11ef](https://linux-hardware.org/?probe=35390b11ef) | Jun 25, 2024 |
| Lenovo        | 3138 SDK0Q40104 WIN 3305... | Desktop     | [ddc5da5ba5](https://linux-hardware.org/?probe=ddc5da5ba5) | Jun 20, 2024 |
| Acer          | One S1003                   | Tablet      | [95011328a5](https://linux-hardware.org/?probe=95011328a5) | Jun 20, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [b63a668d43](https://linux-hardware.org/?probe=b63a668d43) | Jun 19, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [484309983e](https://linux-hardware.org/?probe=484309983e) | Jun 18, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [205d7ccbae](https://linux-hardware.org/?probe=205d7ccbae) | Jun 12, 2024 |
| Lenovo        | ThinkPad P1 20MES0E900      | Notebook    | [4343f5b4ad](https://linux-hardware.org/?probe=4343f5b4ad) | Jun 12, 2024 |
| Lenovo        | ThinkPad P1 20MES0E900      | Notebook    | [c711f7f5e2](https://linux-hardware.org/?probe=c711f7f5e2) | Jun 12, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [68667d6b61](https://linux-hardware.org/?probe=68667d6b61) | Jun 09, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [deab23a295](https://linux-hardware.org/?probe=deab23a295) | Jun 08, 2024 |
| Gigabyte      | H110M-DS2V DDR3-CF          | Desktop     | [5ee5f69fb9](https://linux-hardware.org/?probe=5ee5f69fb9) | Jun 05, 2024 |
| TMAX          | TM800W610L                  | Tablet      | [05804e16cc](https://linux-hardware.org/?probe=05804e16cc) | Jun 03, 2024 |
| HP            | Stream x360 Convertible ... | Convertible | [73e7382a8d](https://linux-hardware.org/?probe=73e7382a8d) | Jun 02, 2024 |
| Lenovo        | 31900059 STD                | All in one  | [462e531e2a](https://linux-hardware.org/?probe=462e531e2a) | May 25, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [750c40c84c](https://linux-hardware.org/?probe=750c40c84c) | May 22, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [7b5e2f5c2e](https://linux-hardware.org/?probe=7b5e2f5c2e) | May 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [972388da07](https://linux-hardware.org/?probe=972388da07) | May 13, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f0bc418296](https://linux-hardware.org/?probe=f0bc418296) | May 08, 2024 |
| Lenovo        | Unknown                     | Notebook    | [dae6c8e749](https://linux-hardware.org/?probe=dae6c8e749) | May 06, 2024 |
| HP            | 8245 001                    | All in one  | [ce7de2b377](https://linux-hardware.org/?probe=ce7de2b377) | May 03, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [120440b735](https://linux-hardware.org/?probe=120440b735) | May 01, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [66fc7bf95a](https://linux-hardware.org/?probe=66fc7bf95a) | Apr 30, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [da659a0ae5](https://linux-hardware.org/?probe=da659a0ae5) | Apr 23, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9db655d8b6](https://linux-hardware.org/?probe=9db655d8b6) | Apr 23, 2024 |
| Intel         | MAHOBAY                     | Desktop     | [9cd8f52e56](https://linux-hardware.org/?probe=9cd8f52e56) | Apr 23, 2024 |
| Lenovo        | ThinkPad T440 20B7000CLM    | Notebook    | [49c44d3355](https://linux-hardware.org/?probe=49c44d3355) | Apr 21, 2024 |
| Lenovo        | ThinkPad T440 20B7000CLM    | Notebook    | [b6124fdf94](https://linux-hardware.org/?probe=b6124fdf94) | Apr 21, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [50de89d752](https://linux-hardware.org/?probe=50de89d752) | Apr 18, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d60ebaaa13](https://linux-hardware.org/?probe=d60ebaaa13) | Apr 15, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [323bf9fa10](https://linux-hardware.org/?probe=323bf9fa10) | Apr 04, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [c41823fc76](https://linux-hardware.org/?probe=c41823fc76) | Apr 04, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfb77127c6](https://linux-hardware.org/?probe=bfb77127c6) | Mar 31, 2024 |
| Toshiba       | Satellite L45-B             | Notebook    | [7a6b9a0b7b](https://linux-hardware.org/?probe=7a6b9a0b7b) | Mar 28, 2024 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [77bf8490e6](https://linux-hardware.org/?probe=77bf8490e6) | Mar 28, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [de162db434](https://linux-hardware.org/?probe=de162db434) | Mar 27, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e5c5d49216](https://linux-hardware.org/?probe=e5c5d49216) | Mar 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c6499bbbb9](https://linux-hardware.org/?probe=c6499bbbb9) | Mar 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [d6d2c95a7a](https://linux-hardware.org/?probe=d6d2c95a7a) | Mar 17, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [cd9270ccb4](https://linux-hardware.org/?probe=cd9270ccb4) | Mar 14, 2024 |
| AZW           | GK mini                     | Mini pc     | [25bfa2f671](https://linux-hardware.org/?probe=25bfa2f671) | Mar 08, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9d3648dfb3](https://linux-hardware.org/?probe=9d3648dfb3) | Mar 04, 2024 |
| Quanta        | 2AC7 011                    | Desktop     | [b4886173ba](https://linux-hardware.org/?probe=b4886173ba) | Feb 24, 2024 |
| MSI           | MAG B550M MORTAR            | Desktop     | [01b17246ec](https://linux-hardware.org/?probe=01b17246ec) | Feb 23, 2024 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [c0d8b37026](https://linux-hardware.org/?probe=c0d8b37026) | Feb 21, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [48be70ca91](https://linux-hardware.org/?probe=48be70ca91) | Feb 18, 2024 |
| HP            | ZBook 15                    | Notebook    | [bcb41f3b4c](https://linux-hardware.org/?probe=bcb41f3b4c) | Feb 14, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f8f33cacdf](https://linux-hardware.org/?probe=f8f33cacdf) | Feb 13, 2024 |
| Quanta        | 2AC7 011                    | Desktop     | [2fbec21ee5](https://linux-hardware.org/?probe=2fbec21ee5) | Feb 12, 2024 |
| Apple         | MacBookPro16,1              | Notebook    | [da438018c3](https://linux-hardware.org/?probe=da438018c3) | Feb 10, 2024 |
| ASRock        | Z390 Pro4                   | Desktop     | [aa34bf9cf1](https://linux-hardware.org/?probe=aa34bf9cf1) | Feb 07, 2024 |
| ASRock        | Z390 Pro4                   | Desktop     | [3ced2256f7](https://linux-hardware.org/?probe=3ced2256f7) | Feb 07, 2024 |
| Dell          | 05XGC8 A01                  | Desktop     | [29ae38936a](https://linux-hardware.org/?probe=29ae38936a) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [6f80a7214c](https://linux-hardware.org/?probe=6f80a7214c) | Feb 01, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [3f4325d337](https://linux-hardware.org/?probe=3f4325d337) | Jan 29, 2024 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [8c1fb214b8](https://linux-hardware.org/?probe=8c1fb214b8) | Jan 25, 2024 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [f3512d75e9](https://linux-hardware.org/?probe=f3512d75e9) | Jan 24, 2024 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [ff5718cb34](https://linux-hardware.org/?probe=ff5718cb34) | Jan 20, 2024 |
| Dell          | Latitude 7430               | Notebook    | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell          | Latitude 7430               | Notebook    | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [947096fa7f](https://linux-hardware.org/?probe=947096fa7f) | Jan 16, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [89b8dbd2bb](https://linux-hardware.org/?probe=89b8dbd2bb) | Jan 13, 2024 |
| System76      | Adder WS                    | Notebook    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| ASUSTek       | UX510UXK                    | Notebook    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Toshiba       | Satellite P55-B             | Notebook    | [9a1e5dc1f6](https://linux-hardware.org/?probe=9a1e5dc1f6) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [08d900cdbb](https://linux-hardware.org/?probe=08d900cdbb) | Dec 27, 2023 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [1594f8077b](https://linux-hardware.org/?probe=1594f8077b) | Dec 27, 2023 |
| Sony          | SVS13A25PLB                 | Notebook    | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [c4fe258ada](https://linux-hardware.org/?probe=c4fe258ada) | Dec 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| Dell          | Latitude E5470              | Notebook    | [9aa1f53217](https://linux-hardware.org/?probe=9aa1f53217) | Dec 18, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [f306ab4590](https://linux-hardware.org/?probe=f306ab4590) | Dec 17, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASRock        | B560M Pro4/ac               | Notebook    | [0dd2927c25](https://linux-hardware.org/?probe=0dd2927c25) | Dec 14, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [5dcf20cb88](https://linux-hardware.org/?probe=5dcf20cb88) | Dec 04, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2f07094763](https://linux-hardware.org/?probe=2f07094763) | Dec 04, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [4b91971e62](https://linux-hardware.org/?probe=4b91971e62) | Dec 01, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5be7c208c3](https://linux-hardware.org/?probe=5be7c208c3) | Nov 20, 2023 |
| Gigabyte      | B550M K                     | Notebook    | [989886ee56](https://linux-hardware.org/?probe=989886ee56) | Nov 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [f4de613bd5](https://linux-hardware.org/?probe=f4de613bd5) | Nov 15, 2023 |
| Dell          | Latitude 5490               | Notebook    | [ac938f1435](https://linux-hardware.org/?probe=ac938f1435) | Nov 08, 2023 |
| Dell          | Latitude E5470              | Notebook    | [bbbdcac07b](https://linux-hardware.org/?probe=bbbdcac07b) | Nov 07, 2023 |
| Dell          | Latitude E5470              | Notebook    | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| HP            | 18E7                        | Desktop     | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [8a9f37b293](https://linux-hardware.org/?probe=8a9f37b293) | Oct 31, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [8f20a345e3](https://linux-hardware.org/?probe=8f20a345e3) | Oct 24, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [dbc150b2b5](https://linux-hardware.org/?probe=dbc150b2b5) | Oct 13, 2023 |
| HP            | 14                          | Notebook    | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| GIADA         | Braswell JHS60S             | Desktop     | [ed113a0bc0](https://linux-hardware.org/?probe=ed113a0bc0) | Oct 08, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| HP            | Pavilion dv4                | Notebook    | [b1ee39c175](https://linux-hardware.org/?probe=b1ee39c175) | Sep 24, 2023 |
| ASRock        | G31M-S                      | Desktop     | [f1325a7f15](https://linux-hardware.org/?probe=f1325a7f15) | Sep 23, 2023 |
| ASUSTek       | V230IC                      | Desktop     | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [9d8e946b59](https://linux-hardware.org/?probe=9d8e946b59) | Sep 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [18a02021f6](https://linux-hardware.org/?probe=18a02021f6) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| ASUSTek       | G752VY                      | Notebook    | [7d3353b537](https://linux-hardware.org/?probe=7d3353b537) | Sep 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [9d3a7e1014](https://linux-hardware.org/?probe=9d3a7e1014) | Sep 14, 2023 |
| HP            | 8433 11                     | Desktop     | [6160c13209](https://linux-hardware.org/?probe=6160c13209) | Sep 12, 2023 |
| HP            | 8433 11                     | Desktop     | [2fbe297e6c](https://linux-hardware.org/?probe=2fbe297e6c) | Sep 12, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| Google        | Treeya                      | Notebook    | [a4db63abbe](https://linux-hardware.org/?probe=a4db63abbe) | Sep 10, 2023 |
| HP            | Pavilion dv4                | Notebook    | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Google        | Treeya                      | Notebook    | [fcc8d7d8a1](https://linux-hardware.org/?probe=fcc8d7d8a1) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [865ce7b55b](https://linux-hardware.org/?probe=865ce7b55b) | Sep 04, 2023 |
| HP            | Notebook                    | Notebook    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [392d7335ed](https://linux-hardware.org/?probe=392d7335ed) | Sep 03, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [89e3ba3d7d](https://linux-hardware.org/?probe=89e3ba3d7d) | Aug 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0150e826ac](https://linux-hardware.org/?probe=0150e826ac) | Aug 28, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [c3b97aa105](https://linux-hardware.org/?probe=c3b97aa105) | Aug 27, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [82923ee337](https://linux-hardware.org/?probe=82923ee337) | Aug 18, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| HP            | ZBook 15                    | Notebook    | [97923a8762](https://linux-hardware.org/?probe=97923a8762) | Aug 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [66f1fd8cc5](https://linux-hardware.org/?probe=66f1fd8cc5) | Aug 07, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [87d27d2a99](https://linux-hardware.org/?probe=87d27d2a99) | Aug 04, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8cde0390c4](https://linux-hardware.org/?probe=8cde0390c4) | Jul 26, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [71ca83faee](https://linux-hardware.org/?probe=71ca83faee) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [1917d24a87](https://linux-hardware.org/?probe=1917d24a87) | Jul 15, 2023 |
| HP            | 83EE                        | Desktop     | [af63e7b8fd](https://linux-hardware.org/?probe=af63e7b8fd) | Jul 12, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [477ec4d403](https://linux-hardware.org/?probe=477ec4d403) | Jul 11, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [32659f379c](https://linux-hardware.org/?probe=32659f379c) | Jul 09, 2023 |
| HP            | 240 G7 Notebook PC          | Notebook    | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [99c60820c5](https://linux-hardware.org/?probe=99c60820c5) | Jul 05, 2023 |
| HP            | 1493                        | Desktop     | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [99341c9ba0](https://linux-hardware.org/?probe=99341c9ba0) | Jun 23, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP            | 14                          | Notebook    | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [d981de6f45](https://linux-hardware.org/?probe=d981de6f45) | Jun 06, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [a1bcda2245](https://linux-hardware.org/?probe=a1bcda2245) | Jun 05, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [a2c31cdc69](https://linux-hardware.org/?probe=a2c31cdc69) | Jun 05, 2023 |
| HP            | 1493                        | Desktop     | [b7432a020a](https://linux-hardware.org/?probe=b7432a020a) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [24775c04a5](https://linux-hardware.org/?probe=24775c04a5) | May 30, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [d6a2216b0f](https://linux-hardware.org/?probe=d6a2216b0f) | May 30, 2023 |
| HP            | 14                          | Notebook    | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| Lenovo        | 3111 NOK                    | Mini pc     | [00e1812234](https://linux-hardware.org/?probe=00e1812234) | May 28, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [e52868c107](https://linux-hardware.org/?probe=e52868c107) | May 25, 2023 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Sony          | VPCEL36FJ                   | Notebook    | [c372bac204](https://linux-hardware.org/?probe=c372bac204) | May 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | Notebook    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [cb96fcfaff](https://linux-hardware.org/?probe=cb96fcfaff) | May 12, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| MSI           | PS42 Modern 8RA             | Notebook    | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [f79b5c8672](https://linux-hardware.org/?probe=f79b5c8672) | May 08, 2023 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [223431f202](https://linux-hardware.org/?probe=223431f202) | May 08, 2023 |
| Dell          | G5 5505                     | Notebook    | [94e01ce854](https://linux-hardware.org/?probe=94e01ce854) | May 07, 2023 |
| Dell          | G5 5505                     | Notebook    | [b484646926](https://linux-hardware.org/?probe=b484646926) | May 07, 2023 |
| HP            | Pavilion 11                 | Notebook    | [696ac990d2](https://linux-hardware.org/?probe=696ac990d2) | May 07, 2023 |
| HP            | Pavilion g4                 | Notebook    | [5e3bd3ea22](https://linux-hardware.org/?probe=5e3bd3ea22) | May 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [d1dc588f69](https://linux-hardware.org/?probe=d1dc588f69) | May 05, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [9d3ea79ded](https://linux-hardware.org/?probe=9d3ea79ded) | May 04, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [7c32eb6bf9](https://linux-hardware.org/?probe=7c32eb6bf9) | Apr 11, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [cabf7adac2](https://linux-hardware.org/?probe=cabf7adac2) | Apr 11, 2023 |
| HP            | 86F3 00100                  | All in one  | [5ed7d0b86c](https://linux-hardware.org/?probe=5ed7d0b86c) | Apr 06, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [8c33d7498d](https://linux-hardware.org/?probe=8c33d7498d) | Apr 05, 2023 |
| eMachines     | D725                        | Notebook    | [f3cdf26e60](https://linux-hardware.org/?probe=f3cdf26e60) | Apr 04, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [a6c0f30f2f](https://linux-hardware.org/?probe=a6c0f30f2f) | Apr 03, 2023 |
| HP            | 1850                        | Desktop     | [162ec03859](https://linux-hardware.org/?probe=162ec03859) | Apr 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [871c53d3f3](https://linux-hardware.org/?probe=871c53d3f3) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| HP            | 2B3B                        | All in one  | [cb25c51987](https://linux-hardware.org/?probe=cb25c51987) | Mar 11, 2023 |
| Lenovo        | ThinkPad T450 20BUA05K00    | Notebook    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0ac521beb](https://linux-hardware.org/?probe=a0ac521beb) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [e05606240c](https://linux-hardware.org/?probe=e05606240c) | Feb 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [9f543932d2](https://linux-hardware.org/?probe=9f543932d2) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [b929a8ff3c](https://linux-hardware.org/?probe=b929a8ff3c) | Feb 24, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| HP            | 14                          | Notebook    | [0244e880e1](https://linux-hardware.org/?probe=0244e880e1) | Feb 19, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [4bcd17d5a6](https://linux-hardware.org/?probe=4bcd17d5a6) | Feb 17, 2023 |
| Intel         | H61                         | Desktop     | [90e4a9358f](https://linux-hardware.org/?probe=90e4a9358f) | Feb 17, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U3S... | Notebook    | [ad0b876d84](https://linux-hardware.org/?probe=ad0b876d84) | Feb 10, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [d693442f27](https://linux-hardware.org/?probe=d693442f27) | Feb 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2e458676e4](https://linux-hardware.org/?probe=2e458676e4) | Feb 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7b08eeb50c](https://linux-hardware.org/?probe=7b08eeb50c) | Jan 29, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [72b9753b42](https://linux-hardware.org/?probe=72b9753b42) | Jan 26, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [2bc6c62201](https://linux-hardware.org/?probe=2bc6c62201) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| HP            | 1850                        | Desktop     | [ccad003ff4](https://linux-hardware.org/?probe=ccad003ff4) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [07b3eb6453](https://linux-hardware.org/?probe=07b3eb6453) | Jan 20, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| MSI           | B350M GAMING PRO            | Desktop     | [df317ef3c8](https://linux-hardware.org/?probe=df317ef3c8) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [1e3f42b7d1](https://linux-hardware.org/?probe=1e3f42b7d1) | Jan 10, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [d35d765c2f](https://linux-hardware.org/?probe=d35d765c2f) | Jan 09, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [afd3f452a1](https://linux-hardware.org/?probe=afd3f452a1) | Jan 07, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [88e5718807](https://linux-hardware.org/?probe=88e5718807) | Jan 03, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [8525777743](https://linux-hardware.org/?probe=8525777743) | Dec 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [951b5a453d](https://linux-hardware.org/?probe=951b5a453d) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Lenovo        | IdeaPad U400 099342G        | Notebook    | [9ecbde32ab](https://linux-hardware.org/?probe=9ecbde32ab) | Dec 06, 2022 |
| HP            | 8767 A                      | Desktop     | [1d4dc77fa3](https://linux-hardware.org/?probe=1d4dc77fa3) | Dec 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [763f309094](https://linux-hardware.org/?probe=763f309094) | Nov 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8600d864a4](https://linux-hardware.org/?probe=8600d864a4) | Nov 13, 2022 |
| Deltron       | H81H3-M4                    | Desktop     | [49530f2e0b](https://linux-hardware.org/?probe=49530f2e0b) | Nov 13, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [b97ba1d3f0](https://linux-hardware.org/?probe=b97ba1d3f0) | Nov 07, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4de6b7bdb8](https://linux-hardware.org/?probe=4de6b7bdb8) | Nov 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a977f9c3e9](https://linux-hardware.org/?probe=a977f9c3e9) | Oct 26, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| Dell          | Latitude E5470              | Notebook    | [11ad7cd084](https://linux-hardware.org/?probe=11ad7cd084) | Oct 20, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [0dd7c3989e](https://linux-hardware.org/?probe=0dd7c3989e) | Oct 12, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [5e33c2b674](https://linux-hardware.org/?probe=5e33c2b674) | Oct 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [6fec6456bc](https://linux-hardware.org/?probe=6fec6456bc) | Oct 07, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fb954f84b4](https://linux-hardware.org/?probe=fb954f84b4) | Oct 07, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d56cf9868c](https://linux-hardware.org/?probe=d56cf9868c) | Oct 07, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [acf2f9d381](https://linux-hardware.org/?probe=acf2f9d381) | Sep 25, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [21407ce4a8](https://linux-hardware.org/?probe=21407ce4a8) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Intel         | D945GCNL AAD97184-106       | Desktop     | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| AZW           | GK mini                     | Mini pc     | [b2d573f8e2](https://linux-hardware.org/?probe=b2d573f8e2) | Sep 10, 2022 |
| AZW           | GK mini                     | Mini pc     | [58c74cb934](https://linux-hardware.org/?probe=58c74cb934) | Sep 09, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [e6a9f975ae](https://linux-hardware.org/?probe=e6a9f975ae) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Lenovo        | Yoga 9 15IMH5 82DE          | Convertible | [c1e007def0](https://linux-hardware.org/?probe=c1e007def0) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | 1493                        | Desktop     | [2ac16ddc1f](https://linux-hardware.org/?probe=2ac16ddc1f) | Aug 03, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [e5b05f8e39](https://linux-hardware.org/?probe=e5b05f8e39) | Aug 02, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [1c92a49cd4](https://linux-hardware.org/?probe=1c92a49cd4) | Aug 01, 2022 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [8d52662820](https://linux-hardware.org/?probe=8d52662820) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f0952d8c25](https://linux-hardware.org/?probe=f0952d8c25) | Jul 13, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI           | GL65 Leopard 10SEK          | Notebook    | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [67c7179045](https://linux-hardware.org/?probe=67c7179045) | Jun 15, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell          | Latitude E7450              | Notebook    | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c1db97e482](https://linux-hardware.org/?probe=c1db97e482) | May 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c274a43a82](https://linux-hardware.org/?probe=c274a43a82) | May 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek       | X555UQ                      | Notebook    | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2ce35a0cba](https://linux-hardware.org/?probe=2ce35a0cba) | May 30, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Intel         | DP67BA AAG10219-300         | Desktop     | [005b9cdb8e](https://linux-hardware.org/?probe=005b9cdb8e) | May 26, 2022 |
| Acer          | TravelMate 5320             | Notebook    | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | Notebook    | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| HP            | 8056                        | Desktop     | [e9d15128a7](https://linux-hardware.org/?probe=e9d15128a7) | May 16, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [03581837bc](https://linux-hardware.org/?probe=03581837bc) | May 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e436a62479](https://linux-hardware.org/?probe=e436a62479) | May 13, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [358cadc7df](https://linux-hardware.org/?probe=358cadc7df) | May 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [9b0f684d99](https://linux-hardware.org/?probe=9b0f684d99) | May 09, 2022 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo        | ThinkPad T530 24296G9       | Notebook    | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP            | ZBook 15                    | Notebook    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [f68946f3d4](https://linux-hardware.org/?probe=f68946f3d4) | May 06, 2022 |
| Compal        | QAQXX                       | Notebook    | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cbe76ee3d3](https://linux-hardware.org/?probe=cbe76ee3d3) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP            | ENVY dv6                    | Notebook    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [80f3ccadb9](https://linux-hardware.org/?probe=80f3ccadb9) | May 02, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U3S... | Notebook    | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek       | X556UR                      | Notebook    | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | Desktop     | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| Foxconn       | H61MXE                      | Desktop     | [d8168e72e7](https://linux-hardware.org/?probe=d8168e72e7) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [ed62d97841](https://linux-hardware.org/?probe=ed62d97841) | Apr 18, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | Notebook    | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| ASUSTek       | A68HM-E                     | Desktop     | [af6b7df94c](https://linux-hardware.org/?probe=af6b7df94c) | Apr 06, 2022 |
| Lenovo        | ThinkPad X140e 20BLA00C0... | Notebook    | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [1ab5b833d9](https://linux-hardware.org/?probe=1ab5b833d9) | Mar 12, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 340 G2                      | Notebook    | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [91e577540a](https://linux-hardware.org/?probe=91e577540a) | Feb 11, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [15dd0e4767](https://linux-hardware.org/?probe=15dd0e4767) | Feb 08, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba       | Satellite C645              | Notebook    | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50fae55964](https://linux-hardware.org/?probe=50fae55964) | Jan 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f679efaa1](https://linux-hardware.org/?probe=5f679efaa1) | Jan 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6a7e71141](https://linux-hardware.org/?probe=f6a7e71141) | Jan 18, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony          | VGN-FW56M                   | Notebook    | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba       | Satellite E205              | Notebook    | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo        | G400 20235                  | Notebook    | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3c85ddcb3](https://linux-hardware.org/?probe=a3c85ddcb3) | Dec 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [9dccdb1f45](https://linux-hardware.org/?probe=9dccdb1f45) | Nov 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [180b98585e](https://linux-hardware.org/?probe=180b98585e) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e995b26637](https://linux-hardware.org/?probe=e995b26637) | Nov 11, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [83ce5b471d](https://linux-hardware.org/?probe=83ce5b471d) | Nov 10, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [140cf1defc](https://linux-hardware.org/?probe=140cf1defc) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| ASRock        | B460M-HDV                   | Desktop     | [f343673932](https://linux-hardware.org/?probe=f343673932) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e071387ed6](https://linux-hardware.org/?probe=e071387ed6) | Oct 22, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [9343a7aac0](https://linux-hardware.org/?probe=9343a7aac0) | Oct 13, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [2a068afc0c](https://linux-hardware.org/?probe=2a068afc0c) | Oct 11, 2021 |
| Lenovo        | 3098 SDK0E50510 PRO or W... | Desktop     | [57fb928b65](https://linux-hardware.org/?probe=57fb928b65) | Oct 03, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP            | Notebook                    | Notebook    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [72114a075d](https://linux-hardware.org/?probe=72114a075d) | Sep 24, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [5b63f0fc0a](https://linux-hardware.org/?probe=5b63f0fc0a) | Sep 16, 2021 |
| Advance       | AN-5431                     | Notebook    | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP            | Notebook                    | Notebook    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [72a24d0b34](https://linux-hardware.org/?probe=72a24d0b34) | Sep 01, 2021 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [92fb750c2f](https://linux-hardware.org/?probe=92fb750c2f) | Sep 01, 2021 |
| Lenovo        | ThinkPad T440 20B7A08500    | Notebook    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP            | 450                         | Notebook    | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Intel         | DG33BU AAD79951-413         | Desktop     | [9824fedcc4](https://linux-hardware.org/?probe=9824fedcc4) | Aug 16, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [46cd16e708](https://linux-hardware.org/?probe=46cd16e708) | Aug 13, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Gigabyte      | B550M H                     | Desktop     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| Advance       | AN-5431                     | Notebook    | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS0XD00    | Notebook    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [5b80d3040f](https://linux-hardware.org/?probe=5b80d3040f) | Jul 25, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [771ef872d9](https://linux-hardware.org/?probe=771ef872d9) | Jul 25, 2021 |
| Dell          | Latitude E5540              | Notebook    | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo        | ThinkPad L460 20FVA0G400    | Notebook    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [95fcf3868f](https://linux-hardware.org/?probe=95fcf3868f) | Jun 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek       | ROG Strix G532LW_G532LWI    | Notebook    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cebf94c181](https://linux-hardware.org/?probe=cebf94c181) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| HP            | 8054                        | Desktop     | [b0662fd84b](https://linux-hardware.org/?probe=b0662fd84b) | May 30, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| HP            | 8054                        | Desktop     | [37f65c4171](https://linux-hardware.org/?probe=37f65c4171) | May 27, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP            | 2B2F MVB,A                  | All in one  | [093f49b44c](https://linux-hardware.org/?probe=093f49b44c) | May 20, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a1959c22e0](https://linux-hardware.org/?probe=a1959c22e0) | May 20, 2021 |
| HP            | 240 G7                      | Notebook    | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [930993fd14](https://linux-hardware.org/?probe=930993fd14) | May 16, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [f7a3ab5c2f](https://linux-hardware.org/?probe=f7a3ab5c2f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [6eb605ae36](https://linux-hardware.org/?probe=6eb605ae36) | Apr 21, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [642a8e122e](https://linux-hardware.org/?probe=642a8e122e) | Apr 18, 2021 |
| Toshiba       | Satellite L35               | Notebook    | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| ASUSTek       | Z97-P                       | Desktop     | [4bd5425a6b](https://linux-hardware.org/?probe=4bd5425a6b) | Apr 11, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| HP            | 14                          | Notebook    | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [b02d3fa1c0](https://linux-hardware.org/?probe=b02d3fa1c0) | Apr 04, 2021 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [91ae7f221c](https://linux-hardware.org/?probe=91ae7f221c) | Apr 01, 2021 |
| Toshiba       | Satellite C655D             | Notebook    | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell          | Latitude E5470              | Notebook    | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [860e86fde0](https://linux-hardware.org/?probe=860e86fde0) | Mar 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [4d1099b04c](https://linux-hardware.org/?probe=4d1099b04c) | Mar 18, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba       | Satellite A665              | Notebook    | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [96dd155871](https://linux-hardware.org/?probe=96dd155871) | Mar 07, 2021 |
| Intel         | H61                         | Desktop     | [77b62ac54a](https://linux-hardware.org/?probe=77b62ac54a) | Mar 05, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [ccb97bb311](https://linux-hardware.org/?probe=ccb97bb311) | Feb 23, 2021 |
| HP            | ProBook 5330m               | Notebook    | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer         | Blade                       | Notebook    | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| PCChips       | P49G                        | Desktop     | [a2f19ae622](https://linux-hardware.org/?probe=a2f19ae622) | Feb 17, 2021 |
| MSI           | A88X-G45 GAMING             | Desktop     | [05d5a888d4](https://linux-hardware.org/?probe=05d5a888d4) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c4f6a52387](https://linux-hardware.org/?probe=c4f6a52387) | Feb 13, 2021 |
| Intel         | D945GTP AAC97834-305        | Desktop     | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP            | Pavilion dv7                | Notebook    | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell          | Inspiron 14-3467            | Notebook    | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Intel         | DP965LT AAD41694-209        | Desktop     | [c577103201](https://linux-hardware.org/?probe=c577103201) | Jan 02, 2021 |
| Dell          | G5 5505                     | Notebook    | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell          | Latitude E5470              | Notebook    | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [35757b1c8c](https://linux-hardware.org/?probe=35757b1c8c) | Dec 06, 2020 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [228dc321d9](https://linux-hardware.org/?probe=228dc321d9) | Dec 05, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [f0c3c358a0](https://linux-hardware.org/?probe=f0c3c358a0) | Dec 03, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5837b78f0c](https://linux-hardware.org/?probe=5837b78f0c) | Nov 26, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP            | 14                          | Notebook    | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell          | Latitude 3440               | Notebook    | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [751f746aaf](https://linux-hardware.org/?probe=751f746aaf) | Nov 09, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [9a0e5bd73b](https://linux-hardware.org/?probe=9a0e5bd73b) | Oct 31, 2020 |
| Lenovo        | Larne CRB SDK0J40679 WIN... | All in one  | [8d1e7af345](https://linux-hardware.org/?probe=8d1e7af345) | Oct 31, 2020 |
| Dell          | 0DR845                      | Desktop     | [80aa8797b0](https://linux-hardware.org/?probe=80aa8797b0) | Oct 29, 2020 |
| MSI           | B360M PRO-VH                | Desktop     | [d8eb2de621](https://linux-hardware.org/?probe=d8eb2de621) | Oct 21, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [943240cc2a](https://linux-hardware.org/?probe=943240cc2a) | Oct 09, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [8987176239](https://linux-hardware.org/?probe=8987176239) | Sep 28, 2020 |
| HP            | 240 G7                      | Notebook    | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Lenovo        | ThinkPad T470 20HES0JQ00    | Notebook    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| MSI           | H81M-E33                    | Desktop     | [313883253c](https://linux-hardware.org/?probe=313883253c) | Sep 07, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430 2349LRS       | Notebook    | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [47c7bf1c93](https://linux-hardware.org/?probe=47c7bf1c93) | Aug 30, 2020 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [3ac15dbee9](https://linux-hardware.org/?probe=3ac15dbee9) | Aug 28, 2020 |
| Lenovo        | G475 20080                  | Notebook    | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | Notebook    | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba       | Satellite C845              | Notebook    | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [31a8ca3766](https://linux-hardware.org/?probe=31a8ca3766) | Aug 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2098b09526](https://linux-hardware.org/?probe=2098b09526) | Aug 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [39ccf30487](https://linux-hardware.org/?probe=39ccf30487) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [2adefb78ad](https://linux-hardware.org/?probe=2adefb78ad) | Aug 13, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo        | ThinkPad P50 20EQA09900     | Notebook    | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba       | Satellite L45-B             | Notebook    | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo        | ThinkPad T60 1953D9U        | Notebook    | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [02c231ca67](https://linux-hardware.org/?probe=02c231ca67) | Jul 27, 2020 |
| HP            | 245 G3                      | Notebook    | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fda411a3d7](https://linux-hardware.org/?probe=fda411a3d7) | Jul 24, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4e0fee8549](https://linux-hardware.org/?probe=4e0fee8549) | Jul 20, 2020 |
| Intel         | DG31PR AAD97573-305         | Desktop     | [e3bd0984ee](https://linux-hardware.org/?probe=e3bd0984ee) | Jul 17, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [2e847ac1d0](https://linux-hardware.org/?probe=2e847ac1d0) | Jul 16, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b0f11672bb](https://linux-hardware.org/?probe=b0f11672bb) | Jul 05, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4716a84af9](https://linux-hardware.org/?probe=4716a84af9) | Jul 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP            | 09E8h                       | Desktop     | [d9b1f1bf60](https://linux-hardware.org/?probe=d9b1f1bf60) | Jun 28, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [f073723231](https://linux-hardware.org/?probe=f073723231) | Jun 27, 2020 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [7f8abda42c](https://linux-hardware.org/?probe=7f8abda42c) | Jun 27, 2020 |
| Intel         | H61M-DS2                    | Desktop     | [aef4861ab1](https://linux-hardware.org/?probe=aef4861ab1) | Jun 25, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP            | 3397                        | Desktop     | [3421ad000d](https://linux-hardware.org/?probe=3421ad000d) | Jun 21, 2020 |
| HP            | 09E8h                       | Desktop     | [14e6514858](https://linux-hardware.org/?probe=14e6514858) | Jun 20, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [3b021c1b62](https://linux-hardware.org/?probe=3b021c1b62) | Jun 17, 2020 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [821a7a7b85](https://linux-hardware.org/?probe=821a7a7b85) | Jun 17, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP            | ProBook 645 G4              | Notebook    | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Dell          | 0DR845                      | Desktop     | [cb4b80e381](https://linux-hardware.org/?probe=cb4b80e381) | Jun 14, 2020 |
| Dell          | 0DR845                      | Desktop     | [107ec57e94](https://linux-hardware.org/?probe=107ec57e94) | Jun 13, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [615d9bbafb](https://linux-hardware.org/?probe=615d9bbafb) | Jun 07, 2020 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [db6aa4b6fa](https://linux-hardware.org/?probe=db6aa4b6fa) | Jun 07, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b803424e29](https://linux-hardware.org/?probe=b803424e29) | May 31, 2020 |
| HP            | ENVY 15                     | Notebook    | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [ea48f46d27](https://linux-hardware.org/?probe=ea48f46d27) | May 27, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [3d5fc4df20](https://linux-hardware.org/?probe=3d5fc4df20) | May 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| Biostar       | GF7025-M2                   | Desktop     | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [4c93d3634b](https://linux-hardware.org/?probe=4c93d3634b) | May 24, 2020 |
| HP            | ENVY 15                     | Notebook    | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Gigabyte      | G41MT-S2                    | Desktop     | [f8702707c6](https://linux-hardware.org/?probe=f8702707c6) | May 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Intel         | D945GCNL AAD97184-102       | Desktop     | [72691e43eb](https://linux-hardware.org/?probe=72691e43eb) | May 14, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [404ef9032e](https://linux-hardware.org/?probe=404ef9032e) | May 12, 2020 |
| Dell          | Precision M4600             | Notebook    | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP            | 0A58h                       | Desktop     | [a3a4679ef9](https://linux-hardware.org/?probe=a3a4679ef9) | May 05, 2020 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [08c0779e95](https://linux-hardware.org/?probe=08c0779e95) | May 02, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [d5880c1076](https://linux-hardware.org/?probe=d5880c1076) | May 02, 2020 |
| HP            | 450                         | Notebook    | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP            | 450                         | Notebook    | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [eb77b46e2f](https://linux-hardware.org/?probe=eb77b46e2f) | Apr 30, 2020 |
| Dell          | System XPS L502X            | Notebook    | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [e2ab73d9cf](https://linux-hardware.org/?probe=e2ab73d9cf) | Apr 26, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [32546cbd9d](https://linux-hardware.org/?probe=32546cbd9d) | Apr 26, 2020 |
| Dell          | System XPS L502X            | Notebook    | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [d88e072663](https://linux-hardware.org/?probe=d88e072663) | Apr 15, 2020 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [71673b2f86](https://linux-hardware.org/?probe=71673b2f86) | Apr 09, 2020 |
| MSI           | A68HM-E33 V2                | Desktop     | [6277a6ec0b](https://linux-hardware.org/?probe=6277a6ec0b) | Apr 08, 2020 |
| HP            | 0A60h                       | Desktop     | [e929430fd0](https://linux-hardware.org/?probe=e929430fd0) | Apr 08, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba       | NB505                       | Notebook    | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| PCChips       | P49G                        | Desktop     | [57f11f5c76](https://linux-hardware.org/?probe=57f11f5c76) | Apr 04, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony          | SVF15A17CLB                 | Notebook    | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| HP            | 3397                        | Desktop     | [71764f18dd](https://linux-hardware.org/?probe=71764f18dd) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [57904c47e1](https://linux-hardware.org/?probe=57904c47e1) | Mar 21, 2020 |
| HP            | 09E8h                       | Desktop     | [4c44586ba9](https://linux-hardware.org/?probe=4c44586ba9) | Mar 21, 2020 |
| PCChips       | P49G                        | Desktop     | [1cedc0a4f7](https://linux-hardware.org/?probe=1cedc0a4f7) | Mar 17, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Gigabyte      | B450 GAMING X               | Desktop     | [145e6998fc](https://linux-hardware.org/?probe=145e6998fc) | Mar 06, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [baaf155c68](https://linux-hardware.org/?probe=baaf155c68) | Mar 04, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [651d7ac7be](https://linux-hardware.org/?probe=651d7ac7be) | Feb 28, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [5b33f9565a](https://linux-hardware.org/?probe=5b33f9565a) | Feb 28, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Gigabyte      | M68MT-S2                    | Desktop     | [6a5c6cf0dc](https://linux-hardware.org/?probe=6a5c6cf0dc) | Feb 23, 2020 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [8a4a2a6066](https://linux-hardware.org/?probe=8a4a2a6066) | Feb 21, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [4ba8cd9ca2](https://linux-hardware.org/?probe=4ba8cd9ca2) | Feb 16, 2020 |
| Intel         | CM8V5CB8N K53774-201        | Desktop     | [19086b2ac2](https://linux-hardware.org/?probe=19086b2ac2) | Feb 16, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba       | QOSMIO X775                 | Notebook    | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [7ae91dcf15](https://linux-hardware.org/?probe=7ae91dcf15) | Jan 21, 2020 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [12b760b696](https://linux-hardware.org/?probe=12b760b696) | Jan 20, 2020 |
| ASUSTek       | M5A97                       | Desktop     | [a381f0be23](https://linux-hardware.org/?probe=a381f0be23) | Jan 17, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5b67f6ed83](https://linux-hardware.org/?probe=5b67f6ed83) | Dec 26, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [c05b5b48de](https://linux-hardware.org/?probe=c05b5b48de) | Dec 05, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [3862b040a2](https://linux-hardware.org/?probe=3862b040a2) | Dec 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| Dell          | 0G261D A00                  | Desktop     | [50ef5c54ef](https://linux-hardware.org/?probe=50ef5c54ef) | Nov 29, 2019 |
| HP            | Pavilion g4                 | Notebook    | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell          | Latitude 5580               | Notebook    | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell          | Latitude 5580               | Notebook    | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba       | Satellite C55-B             | Notebook    | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Foxconn       | A76GMV                      | Desktop     | [ddfa1ad143](https://linux-hardware.org/?probe=ddfa1ad143) | Oct 22, 2019 |
| Dell          | Inspiron 3443               | Notebook    | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony          | VPCEC2JFX                   | Notebook    | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer          | Aspire ES1-572              | Notebook    | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP            | ProBook 440 G4              | Notebook    | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [048c1a4f90](https://linux-hardware.org/?probe=048c1a4f90) | Jun 25, 2019 |
| Gigabyte      | A55M-DS2                    | Desktop     | [9e2c603e49](https://linux-hardware.org/?probe=9e2c603e49) | Jun 23, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [07dd5b8424](https://linux-hardware.org/?probe=07dd5b8424) | Jun 14, 2019 |
| Toshiba       | Satellite P755              | Notebook    | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP            | ProBook 645 G4              | Notebook    | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [5ca60ce3ac](https://linux-hardware.org/?probe=5ca60ce3ac) | Apr 06, 2019 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [c7dd2b6e26](https://linux-hardware.org/?probe=c7dd2b6e26) | Mar 26, 2019 |
| Lenovo        | B50-80 80EW                 | Notebook    | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo        | B50-80 80EW                 | Notebook    | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| AMI           | Cherry Trail CR             | Desktop     | [e248592999](https://linux-hardware.org/?probe=e248592999) | Nov 03, 2018 |
| HP            | 1000                        | Notebook    | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| MSI           | A68HM-E33 V2                | Desktop     | [765c79328e](https://linux-hardware.org/?probe=765c79328e) | Jun 26, 2018 |
| ECS           | MCP61M-M3                   | Desktop     | [a51a8c96df](https://linux-hardware.org/?probe=a51a8c96df) | Apr 08, 2018 |
| HP            | Stream x360 Convertible ... | Convertible | [be4128010b](https://linux-hardware.org/?probe=be4128010b) | Feb 12, 2018 |
| HP            | 1000                        | Notebook    | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony          | VGN-FW170J                  | Notebook    | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP            | 1000                        | Notebook    | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony          | VGN-FW170J                  | Notebook    | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer          | Aspire S3                   | Notebook    | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer          | Aspire S3                   | Notebook    | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |
| HP            | Stream x360 Convertible ... | Convertible | [e721d571fe](https://linux-hardware.org/?probe=e721d571fe) | May 15, 2017 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4d498130d3](https://linux-hardware.org/?probe=4d498130d3) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [58bc94c592](https://linux-hardware.org/?probe=58bc94c592) | Dec 24, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [7201ee94b8](https://linux-hardware.org/?probe=7201ee94b8) | Nov 07, 2016 |
| Intel         | DH55PJ AAE93812-303         | Desktop     | [4567d9bca4](https://linux-hardware.org/?probe=4567d9bca4) | Nov 02, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Peru/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 59        | 9.67%   |
| Ubuntu 22.04                 | 32        | 5.25%   |
| Ubuntu 18.04                 | 22        | 3.61%   |
| Arch Rolling                 | 22        | 3.61%   |
| OpenMandriva 4.3             | 20        | 3.28%   |
| Fedora 40                    | 15        | 2.46%   |
| OpenMandriva 4.2             | 12        | 1.97%   |
| Manjaro                      | 12        | 1.97%   |
| Debian 12                    | 12        | 1.97%   |
| Zorin 15                     | 10        | 1.64%   |
| OpenMandriva 23.03           | 10        | 1.64%   |
| Linux Mint 21.1              | 10        | 1.64%   |
| Fedora 38                    | 10        | 1.64%   |
| Debian 11                    | 10        | 1.64%   |
| Ubuntu 19.10                 | 9         | 1.48%   |
| Ubuntu 24.04                 | 8         | 1.31%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 1.31%   |
| OpenMandriva 24.07           | 8         | 1.31%   |
| Zorin 17                     | 7         | 1.15%   |
| Mageia 9                     | 7         | 1.15%   |
| Linux Mint 20.3              | 7         | 1.15%   |
| OpenMandriva 23.01           | 6         | 0.98%   |
| KDE neon 22.04               | 6         | 0.98%   |
| KDE neon 20.04               | 6         | 0.98%   |
| Fedora 37                    | 6         | 0.98%   |
| Arch                         | 6         | 0.98%   |
| Zorin 16                     | 5         | 0.82%   |
| Xubuntu 20.04                | 5         | 0.82%   |
| ROSA R9                      | 5         | 0.82%   |
| Pop!_OS 22.04                | 5         | 0.82%   |
| OpenMandriva 23.08           | 5         | 0.82%   |
| Linux Mint 21.2              | 5         | 0.82%   |
| Linux Mint 20.1              | 5         | 0.82%   |
| Kubuntu 20.04                | 5         | 0.82%   |
| Fedora 39                    | 5         | 0.82%   |
| Debian 10                    | 5         | 0.82%   |
| ArcoLinux Rolling            | 5         | 0.82%   |
| Ubuntu 23.04                 | 4         | 0.66%   |
| Ubuntu 21.10                 | 4         | 0.66%   |
| Ubuntu 21.04                 | 4         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 139       | 24.01%  |
| OpenMandriva  | 68        | 11.74%  |
| Fedora        | 50        | 8.64%   |
| Linux Mint    | 40        | 6.91%   |
| Debian        | 31        | 5.35%   |
| Arch          | 29        | 5.01%   |
| Manjaro       | 24        | 4.15%   |
| ROSA          | 23        | 3.97%   |
| Zorin         | 22        | 3.8%    |
| Pop!_OS       | 15        | 2.59%   |
| Kubuntu       | 13        | 2.25%   |
| KDE neon      | 12        | 2.07%   |
| openSUSE      | 11        | 1.9%    |
| Xubuntu       | 9         | 1.55%   |
| Ubuntu MATE   | 9         | 1.55%   |
| Mageia        | 7         | 1.21%   |
| Lubuntu       | 7         | 1.21%   |
| Parrot        | 6         | 1.04%   |
| Elementary    | 6         | 1.04%   |
| Endless       | 5         | 0.86%   |
| ArcoLinux     | 5         | 0.86%   |
| SteamOS       | 4         | 0.69%   |
| Kali          | 4         | 0.69%   |
| CentOS        | 4         | 0.69%   |
| LMDE          | 3         | 0.52%   |
| Linux Lite    | 3         | 0.52%   |
| EndeavourOS   | 3         | 0.52%   |
| ChimeraOS     | 3         | 0.52%   |
| Ubuntu Unity  | 2         | 0.35%   |
| Ubuntu Budgie | 2         | 0.35%   |
| Peppermint    | 2         | 0.35%   |
| Xero          | 1         | 0.17%   |
| Void Linux    | 1         | 0.17%   |
| Ubuntu Studio | 1         | 0.17%   |
| Solus         | 1         | 0.17%   |
| Q4OS          | 1         | 0.17%   |
| Oracle Linux  | 1         | 0.17%   |
| Nobara        | 1         | 0.17%   |
| NixOS         | 1         | 0.17%   |
| MX            | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 19        | 2.87%   |
| 5.10.14-desktop-1omv4002           | 10        | 1.51%   |
| 6.2.6-desktop-1omv2390             | 9         | 1.36%   |
| 5.3.0-40-generic                   | 8         | 1.21%   |
| 6.6.52-desktop-1.mga9              | 7         | 1.06%   |
| 6.5.0-15-generic                   | 6         | 0.9%    |
| 6.10.0-desktop-1omv2490            | 6         | 0.9%    |
| 5.4.0-66-generic                   | 5         | 0.75%   |
| 5.4.0-28-generic                   | 5         | 0.75%   |
| 5.13.0-40-generic                  | 5         | 0.75%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 5         | 0.75%   |
| 6.6.2-desktop-1omv2390             | 4         | 0.6%    |
| 6.1.1-desktop-1omv2290             | 4         | 0.6%    |
| 5.4.0-70-generic                   | 4         | 0.6%    |
| 5.4.0-58-generic                   | 4         | 0.6%    |
| 5.4.0-52-generic                   | 4         | 0.6%    |
| 5.4.0-42-generic                   | 4         | 0.6%    |
| 5.4.0-37-generic                   | 4         | 0.6%    |
| 5.4.0-31-generic                   | 4         | 0.6%    |
| 5.4.0-26-generic                   | 4         | 0.6%    |
| 5.15.0-52-generic                  | 4         | 0.6%    |
| 5.11.0-40-generic                  | 4         | 0.6%    |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 0.6%    |
| 5.10.0-13-amd64                    | 4         | 0.6%    |
| 6.8.0-31-generic                   | 3         | 0.45%   |
| 6.4.11-desktop-1omv2390            | 3         | 0.45%   |
| 6.3.5-desktop-3omv2390             | 3         | 0.45%   |
| 6.3.5-200.fc38.x86_64              | 3         | 0.45%   |
| 6.2.0-20-generic                   | 3         | 0.45%   |
| 6.12.1-desktop-1omv2490            | 3         | 0.45%   |
| 5.4.0-73-generic                   | 3         | 0.45%   |
| 5.4.0-40-generic                   | 3         | 0.45%   |
| 5.4.0-39-generic                   | 3         | 0.45%   |
| 5.4.0-33-generic                   | 3         | 0.45%   |
| 5.3.0-46-generic                   | 3         | 0.45%   |
| 5.3.0-42-generic                   | 3         | 0.45%   |
| 5.3.0-26-generic                   | 3         | 0.45%   |
| 5.18.12-desktop-3omv4090           | 3         | 0.45%   |
| 5.17.5-arch1-1                     | 3         | 0.45%   |
| 5.15.0-91-generic                  | 3         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 74        | 11.71%  |
| 5.15.0  | 47        | 7.44%   |
| 6.5.0   | 26        | 4.11%   |
| 5.3.0   | 23        | 3.64%   |
| 5.13.0  | 21        | 3.32%   |
| 5.11.0  | 20        | 3.16%   |
| 5.16.7  | 19        | 3.01%   |
| 4.15.0  | 19        | 3.01%   |
| 6.2.0   | 17        | 2.69%   |
| 6.8.0   | 13        | 2.06%   |
| 5.8.0   | 13        | 2.06%   |
| 5.10.0  | 12        | 1.9%    |
| 4.18.0  | 12        | 1.9%    |
| 6.2.6   | 11        | 1.74%   |
| 6.1.0   | 10        | 1.58%   |
| 5.10.14 | 10        | 1.58%   |
| 5.19.0  | 9         | 1.42%   |
| 5.0.0   | 8         | 1.27%   |
| 6.6.52  | 7         | 1.11%   |
| 6.3.5   | 7         | 1.11%   |
| 6.10.0  | 6         | 0.95%   |
| 6.1.1   | 5         | 0.79%   |
| 4.9.20  | 5         | 0.79%   |
| 6.9.7   | 4         | 0.63%   |
| 6.6.2   | 4         | 0.63%   |
| 6.4.11  | 4         | 0.63%   |
| 6.3.6   | 4         | 0.63%   |
| 5.17.5  | 4         | 0.63%   |
| 5.10.74 | 4         | 0.63%   |
| 4.9.60  | 4         | 0.63%   |
| 6.6.6   | 3         | 0.47%   |
| 6.4.6   | 3         | 0.47%   |
| 6.12.1  | 3         | 0.47%   |
| 6.0.0   | 3         | 0.47%   |
| 5.18.12 | 3         | 0.47%   |
| 5.17.1  | 3         | 0.47%   |
| 6.9.9   | 2         | 0.32%   |
| 6.9.5   | 2         | 0.32%   |
| 6.9.12  | 2         | 0.32%   |
| 6.8.7   | 2         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 80        | 12.84%  |
| 5.15    | 62        | 9.95%   |
| 6.2     | 34        | 5.46%   |
| 6.5     | 33        | 5.3%    |
| 5.10    | 33        | 5.3%    |
| 6.1     | 31        | 4.98%   |
| 5.3     | 25        | 4.01%   |
| 5.16    | 25        | 4.01%   |
| 5.11    | 24        | 3.85%   |
| 6.6     | 23        | 3.69%   |
| 5.13    | 22        | 3.53%   |
| 6.8     | 20        | 3.21%   |
| 4.15    | 19        | 3.05%   |
| 6.4     | 17        | 2.73%   |
| 5.8     | 17        | 2.73%   |
| 6.10    | 16        | 2.57%   |
| 6.3     | 15        | 2.41%   |
| 6.0     | 14        | 2.25%   |
| 5.19    | 13        | 2.09%   |
| 6.9     | 12        | 1.93%   |
| 4.18    | 12        | 1.93%   |
| 6.11    | 10        | 1.61%   |
| 5.17    | 10        | 1.61%   |
| 5.0     | 8         | 1.28%   |
| 4.9     | 8         | 1.28%   |
| 5.18    | 7         | 1.12%   |
| 5.6     | 5         | 0.8%    |
| 5.7     | 4         | 0.64%   |
| 5.14    | 4         | 0.64%   |
| 5.12    | 4         | 0.64%   |
| 6.12    | 3         | 0.48%   |
| 5.9     | 3         | 0.48%   |
| 6.7     | 2         | 0.32%   |
| 4.19    | 2         | 0.32%   |
| 4.1     | 2         | 0.32%   |
| 5.1     | 1         | 0.16%   |
| 4.8     | 1         | 0.16%   |
| 4.4     | 1         | 0.16%   |
| 4.16    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 539       | 96.42%  |
| i686    | 17        | 3.04%   |
| aarch64 | 3         | 0.54%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 244       | 41.85%  |
| KDE5            | 125       | 21.44%  |
| XFCE            | 46        | 7.89%   |
| Unknown         | 38        | 6.52%   |
| X-Cinnamon      | 36        | 6.17%   |
| MATE            | 23        | 3.95%   |
| KDE4            | 9         | 1.54%   |
| KDE             | 9         | 1.54%   |
| LXQt            | 8         | 1.37%   |
| Pantheon        | 6         | 1.03%   |
| i3              | 6         | 1.03%   |
| LXDE            | 5         | 0.86%   |
| Budgie          | 5         | 0.86%   |
| KDE6            | 3         | 0.51%   |
| Hyprland        | 3         | 0.51%   |
| Unity           | 2         | 0.34%   |
| sway            | 2         | 0.34%   |
| qtile           | 2         | 0.34%   |
| GNOME Flashback | 2         | 0.34%   |
| fluxbox         | 2         | 0.34%   |
| Deepin          | 2         | 0.34%   |
| spectrwm        | 1         | 0.17%   |
| LXDE-pi-wayfire | 1         | 0.17%   |
| icewm           | 1         | 0.17%   |
| GNOME Classic   | 1         | 0.17%   |
| awesome         | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 403       | 69.6%   |
| Wayland | 147       | 25.39%  |
| Unknown | 24        | 4.15%   |
| Tty     | 5         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 250       | 43.18%  |
| SDDM    | 116       | 20.03%  |
| GDM     | 67        | 11.57%  |
| GDM3    | 64        | 11.05%  |
| LightDM | 62        | 10.71%  |
| KDM     | 9         | 1.55%   |
| TDM     | 6         | 1.04%   |
| XDM     | 1         | 0.17%   |
| SLIMSKI | 1         | 0.17%   |
| LY-DM   | 1         | 0.17%   |
| Ly      | 1         | 0.17%   |
| LXDM    | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_PE   | 284       | 49.31%  |
| en_US   | 147       | 25.52%  |
| es_ES   | 64        | 11.11%  |
| Unknown | 28        | 4.86%   |
| es_MX   | 16        | 2.78%   |
| C       | 8         | 1.39%   |
| en_GB   | 6         | 1.04%   |
| es_AR   | 3         | 0.52%   |
| en_CA   | 3         | 0.52%   |
| it_IT   | 2         | 0.35%   |
| fr_FR   | 2         | 0.35%   |
| de_DE   | 2         | 0.35%   |
| ca_ES   | 2         | 0.35%   |
| ru_RU   | 1         | 0.17%   |
| POSIX   | 1         | 0.17%   |
| es_VE   | 1         | 0.17%   |
| es_US   | 1         | 0.17%   |
| es_HN   | 1         | 0.17%   |
| es_CO   | 1         | 0.17%   |
| en_NZ   | 1         | 0.17%   |
| en_DK   | 1         | 0.17%   |
| Default | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 287       | 50.44%  |
| BIOS | 282       | 49.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 400       | 69.2%   |
| Btrfs   | 76        | 13.15%  |
| Overlay | 53        | 9.17%   |
| Tmpfs   | 19        | 3.29%   |
| Unknown | 15        | 2.6%    |
| Xfs     | 12        | 2.08%   |
| Ext3    | 3         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 273       | 47.73%  |
| GPT     | 241       | 42.13%  |
| MBR     | 58        | 10.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 486       | 84.38%  |
| Yes       | 90        | 15.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 351       | 61.47%  |
| Yes       | 220       | 38.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 109       | 19.53%  |
| Lenovo                  | 94        | 16.85%  |
| ASUSTek Computer        | 84        | 15.05%  |
| Gigabyte Technology     | 47        | 8.42%   |
| Dell                    | 40        | 7.17%   |
| MSI                     | 34        | 6.09%   |
| Intel                   | 27        | 4.84%   |
| Toshiba                 | 21        | 3.76%   |
| Acer                    | 20        | 3.58%   |
| ASRock                  | 13        | 2.33%   |
| Foxconn                 | 7         | 1.25%   |
| Chuwi                   | 7         | 1.25%   |
| Apple                   | 7         | 1.25%   |
| Sony                    | 6         | 1.08%   |
| HUAWEI                  | 6         | 1.08%   |
| Raspberry Pi Foundation | 3         | 0.54%   |
| ECS                     | 3         | 0.54%   |
| Unknown                 | 3         | 0.54%   |
| Samsung Electronics     | 2         | 0.36%   |
| Quanta                  | 2         | 0.36%   |
| Google                  | 2         | 0.36%   |
| AMI                     | 2         | 0.36%   |
| ADVANCE                 | 2         | 0.36%   |
| Valve                   | 1         | 0.18%   |
| TMAX                    | 1         | 0.18%   |
| SZMZ                    | 1         | 0.18%   |
| System76                | 1         | 0.18%   |
| Razer                   | 1         | 0.18%   |
| PCChips                 | 1         | 0.18%   |
| Microsoft               | 1         | 0.18%   |
| LG Electronics          | 1         | 0.18%   |
| GIADA                   | 1         | 0.18%   |
| Gateway                 | 1         | 0.18%   |
| eMachines               | 1         | 0.18%   |
| efirstview              | 1         | 0.18%   |
| Deltron                 | 1         | 0.18%   |
| Compal                  | 1         | 0.18%   |
| Biostar                 | 1         | 0.18%   |
| AZW                     | 1         | 0.18%   |
| Acidanthera             | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                       | 6         | 1.08%   |
| HP Pavilion g4                           | 5         | 0.9%    |
| MSI MS-7721                              | 4         | 0.72%   |
| Lenovo V330-15IKB 81AX                   | 4         | 0.72%   |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 0.72%   |
| HP 14                                    | 4         | 0.72%   |
| Gigabyte B75M-D3H                        | 4         | 0.72%   |
| Gigabyte 970A-DS3P                       | 4         | 0.72%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 4         | 0.72%   |
| ASUS All Series                          | 4         | 0.72%   |
| Unknown                                  | 4         | 0.72%   |
| Toshiba Satellite L45-B                  | 3         | 0.54%   |
| Lenovo V310-15ISK 80SY                   | 3         | 0.54%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 3         | 0.54%   |
| Intel H61                                | 3         | 0.54%   |
| HUAWEI NBLB-WAX9N                        | 3         | 0.54%   |
| Gigabyte F2A68HM-H                       | 3         | 0.54%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 0.54%   |
| ASUS ROG STRIX B550-F GAMING             | 3         | 0.54%   |
| ASUS PRIME A320M-K                       | 3         | 0.54%   |
| Apple MacBookPro9,2                      | 3         | 0.54%   |
| Toshiba Satellite C45-A                  | 2         | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.2       | 2         | 0.36%   |
| Quanta 120-1016la                        | 2         | 0.36%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 2         | 0.36%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.36%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.36%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.36%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 2         | 0.36%   |
| Lenovo G400 20235                        | 2         | 0.36%   |
| Intel DH55PJ AAE93812-303                | 2         | 0.36%   |
| HP ProBook 645 G4                        | 2         | 0.36%   |
| HP Pavilion Gaming Laptop 15-dk1xxx      | 2         | 0.36%   |
| HP Pavilion dv4                          | 2         | 0.36%   |
| HP Notebook                              | 2         | 0.36%   |
| HP Laptop 15-fc0xxx                      | 2         | 0.36%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.36%   |
| HP Laptop 14-ck0xxx                      | 2         | 0.36%   |
| HP Compaq Presario C700                  | 2         | 0.36%   |
| HP Compaq dc5700 Small Form Factor       | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 29        | 5.2%    |
| HP Pavilion        | 26        | 4.66%   |
| Lenovo ThinkPad    | 23        | 4.12%   |
| Toshiba Satellite  | 18        | 3.23%   |
| ASUS VivoBook      | 18        | 3.23%   |
| ASUS PRIME         | 18        | 3.23%   |
| HP Laptop          | 16        | 2.87%   |
| Acer Aspire        | 16        | 2.87%   |
| Dell Latitude      | 15        | 2.69%   |
| HP Compaq          | 11        | 1.97%   |
| HP ProBook         | 10        | 1.79%   |
| ASUS ROG           | 10        | 1.79%   |
| Dell Inspiron      | 9         | 1.61%   |
| Lenovo Legion      | 7         | 1.25%   |
| Dell OptiPlex      | 7         | 1.25%   |
| Chuwi GemiBook     | 6         | 1.08%   |
| ASUS TUF           | 6         | 1.08%   |
| Lenovo ThinkCentre | 5         | 0.9%    |
| MSI MS-7721        | 4         | 0.72%   |
| Lenovo V330-15IKB  | 4         | 0.72%   |
| HP 250             | 4         | 0.72%   |
| HP 14              | 4         | 0.72%   |
| Gigabyte B75M-D3H  | 4         | 0.72%   |
| Gigabyte 970A-DS3P | 4         | 0.72%   |
| ASUS All           | 4         | 0.72%   |
| Unknown            | 4         | 0.72%   |
| RPi Raspberry      | 3         | 0.54%   |
| Lenovo V310-15ISK  | 3         | 0.54%   |
| Intel H61          | 3         | 0.54%   |
| HUAWEI NBLB-WAX9N  | 3         | 0.54%   |
| HP Stream          | 3         | 0.54%   |
| HP OMEN            | 3         | 0.54%   |
| HP ENVY            | 3         | 0.54%   |
| HP EliteBook       | 3         | 0.54%   |
| Gigabyte X570      | 3         | 0.54%   |
| Gigabyte F2A68HM-H | 3         | 0.54%   |
| ASUS ASUS          | 3         | 0.54%   |
| ASRock X570        | 3         | 0.54%   |
| Apple MacBookPro9  | 3         | 0.54%   |
| Toshiba QOSMIO     | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 68        | 12.19%  |
| 2018    | 48        | 8.6%    |
| 2019    | 46        | 8.24%   |
| 2012    | 42        | 7.53%   |
| 2014    | 41        | 7.35%   |
| 2017    | 38        | 6.81%   |
| 2016    | 38        | 6.81%   |
| 2013    | 38        | 6.81%   |
| 2021    | 37        | 6.63%   |
| 2011    | 32        | 5.73%   |
| 2022    | 24        | 4.3%    |
| 2010    | 24        | 4.3%    |
| 2015    | 23        | 4.12%   |
| 2008    | 16        | 2.87%   |
| 2023    | 13        | 2.33%   |
| 2007    | 11        | 1.97%   |
| 2009    | 10        | 1.79%   |
| 2006    | 5         | 0.9%    |
| Unknown | 3         | 0.54%   |
| 2004    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 328       | 58.78%  |
| Desktop        | 203       | 36.38%  |
| All in one     | 9         | 1.61%   |
| Convertible    | 6         | 1.08%   |
| Tablet         | 4         | 0.72%   |
| System on chip | 3         | 0.54%   |
| Mini pc        | 3         | 0.54%   |
| Server         | 2         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 523       | 93.39%  |
| Enabled  | 37        | 6.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 555       | 99.46%  |
| Yes  | 3         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 144       | 25.17%  |
| 4.01-8.0    | 137       | 23.95%  |
| 3.01-4.0    | 101       | 17.66%  |
| 16.01-24.0  | 95        | 16.61%  |
| 32.01-64.0  | 32        | 5.59%   |
| 1.01-2.0    | 23        | 4.02%   |
| 64.01-256.0 | 15        | 2.62%   |
| 24.01-32.0  | 12        | 2.1%    |
| 2.01-3.0    | 10        | 1.75%   |
| 0.51-1.0    | 3         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 197       | 31.47%  |
| 2.01-3.0   | 161       | 25.72%  |
| 4.01-8.0   | 102       | 16.29%  |
| 3.01-4.0   | 88        | 14.06%  |
| 0.51-1.0   | 41        | 6.55%   |
| 8.01-16.0  | 29        | 4.63%   |
| 16.01-24.0 | 4         | 0.64%   |
| 0.01-0.5   | 2         | 0.32%   |
| 32.01-64.0 | 1         | 0.16%   |
| 24.01-32.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 357       | 62.52%  |
| 2      | 159       | 27.85%  |
| 3      | 34        | 5.95%   |
| 4      | 12        | 2.1%    |
| 6      | 3         | 0.53%   |
| 5      | 3         | 0.53%   |
| 0      | 2         | 0.35%   |
| 9      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 369       | 65.78%  |
| Yes       | 192       | 34.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 489       | 87.17%  |
| No        | 72        | 12.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 421       | 74.38%  |
| No        | 145       | 25.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 60.85%  |
| No        | 220       | 39.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Peru    | 558       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lima                  | 379       | 65.57%  |
| Arequipa              | 42        | 7.27%   |
| Trujillo              | 31        | 5.36%   |
| Huancayo              | 13        | 2.25%   |
| Cusco                 | 12        | 2.08%   |
| Piura                 | 11        | 1.9%    |
| Chiclayo              | 11        | 1.9%    |
| Tacna                 | 8         | 1.38%   |
| Ica                   | 6         | 1.04%   |
| San Isidro            | 4         | 0.69%   |
| Moquegua              | 4         | 0.69%   |
| Santiago de Surco     | 3         | 0.52%   |
| Puno                  | 3         | 0.52%   |
| La Victoria           | 3         | 0.52%   |
| Huaraz                | 3         | 0.52%   |
| Chimbote              | 3         | 0.52%   |
| Villa                 | 2         | 0.35%   |
| Tarapoto              | 2         | 0.35%   |
| Lima region           | 2         | 0.35%   |
| Junin                 | 2         | 0.35%   |
| Juliaca               | 2         | 0.35%   |
| Iquitos               | 2         | 0.35%   |
| Ilo                   | 2         | 0.35%   |
| Distrito de Lima      | 2         | 0.35%   |
| Callao                | 2         | 0.35%   |
| Cajamarca             | 2         | 0.35%   |
| Barranco              | 2         | 0.35%   |
| Abancay               | 2         | 0.35%   |
| Tumbes                | 1         | 0.17%   |
| Surquillo             | 1         | 0.17%   |
| Sullana               | 1         | 0.17%   |
| San Vicente de Canete | 1         | 0.17%   |
| San Borja             | 1         | 0.17%   |
| Punta Colorada        | 1         | 0.17%   |
| Pucallpa              | 1         | 0.17%   |
| Pisco                 | 1         | 0.17%   |
| Oxapampa              | 1         | 0.17%   |
| Miraflores District   | 1         | 0.17%   |
| Mala                  | 1         | 0.17%   |
| Machupicchu           | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 141       | 215    | 18.31%  |
| WDC                         | 137       | 199    | 17.79%  |
| Kingston                    | 90        | 115    | 11.69%  |
| Toshiba                     | 69        | 83     | 8.96%   |
| Samsung Electronics         | 59        | 78     | 7.66%   |
| SanDisk                     | 37        | 43     | 4.81%   |
| Crucial                     | 26        | 36     | 3.38%   |
| Unknown                     | 25        | 34     | 3.25%   |
| Hewlett-Packard             | 17        | 21     | 2.21%   |
| Kingston Technology Company | 13        | 16     | 1.69%   |
| Intel                       | 13        | 15     | 1.69%   |
| Micron Technology           | 11        | 12     | 1.43%   |
| SK hynix                    | 10        | 14     | 1.3%    |
| Hitachi                     | 10        | 14     | 1.3%    |
| HGST                        | 9         | 10     | 1.17%   |
| Netac                       | 8         | 8      | 1.04%   |
| KIOXIA                      | 8         | 9      | 1.04%   |
| Phison Electronics          | 7         | 7      | 0.91%   |
| A-DATA Technology           | 7         | 7      | 0.91%   |
| Gigabyte Technology         | 6         | 6      | 0.78%   |
| Micron/Crucial Technology   | 5         | 11     | 0.65%   |
| China                       | 5         | 5      | 0.65%   |
| Silicon Motion              | 4         | 4      | 0.52%   |
| LITEON                      | 4         | 4      | 0.52%   |
| Apple                       | 4         | 4      | 0.52%   |
| Unknown                     | 4         | 6      | 0.52%   |
| TO Exter                    | 3         | 7      | 0.39%   |
| Team                        | 3         | 4      | 0.39%   |
| PNY                         | 3         | 3      | 0.39%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.26%   |
| UMIS                        | 2         | 2      | 0.26%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.26%   |
| Lenovo                      | 2         | 3      | 0.26%   |
| Biwin Storage Technology    | 2         | 4      | 0.26%   |
| Zheino                      | 1         | 1      | 0.13%   |
| YMTC                        | 1         | 1      | 0.13%   |
| Yangtze Memory Technologies | 1         | 1      | 0.13%   |
| WD MediaMax                 | 1         | 1      | 0.13%   |
| T-FORCE                     | 1         | 1      | 0.13%   |
| SSSTC                       | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 29        | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB                      | 22        | 2.62%   |
| Seagate ST500DM002-1BD142 500GB                     | 18        | 2.14%   |
| Kingston SA400S37480G 480GB SSD                     | 15        | 1.78%   |
| Seagate ST1000DM010-2EP102 1TB                      | 14        | 1.66%   |
| Toshiba MQ04ABF100 1TB                              | 11        | 1.31%   |
| Toshiba MQ01ABD100 1TB                              | 11        | 1.31%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 1.31%   |
| Kingston Company SNV2S1000G 1TB                     | 10        | 1.19%   |
| Unknown MMC Card  32GB                              | 9         | 1.07%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 8         | 0.95%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 8         | 0.95%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 7         | 0.83%   |
| Toshiba MQ01ABF050 500GB                            | 7         | 0.83%   |
| Toshiba DT01ACA100 1TB                              | 7         | 0.83%   |
| Seagate ST3500418AS 500GB                           | 7         | 0.83%   |
| HP SSD S700 500GB                                   | 7         | 0.83%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 6         | 0.71%   |
| Seagate ST2000DM001-1ER164 2TB                      | 6         | 0.71%   |
| Seagate ST1000LM049-2GH172 1TB                      | 6         | 0.71%   |
| Seagate ST1000DM003-1CH162 1TB                      | 6         | 0.71%   |
| Netac SSD 256GB                                     | 6         | 0.71%   |
| Kingston SA400S37960G 960GB SSD                     | 6         | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 5         | 0.59%   |
| Seagate ST9500325AS 500GB                           | 5         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 0.59%   |
| SanDisk NVMe SSD Drive 1TB                          | 5         | 0.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 5         | 0.59%   |
| Kingston SNVS250G 250GB                             | 5         | 0.59%   |
| Intel SSDPEKNU512GZ 512GB                           | 5         | 0.59%   |
| Crucial CT500MX500SSD4 500GB                        | 5         | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 4         | 0.48%   |
| WDC WDS100T3X0C-00SJG0 1TB                          | 4         | 0.48%   |
| WDC WD10SPZX-24Z10 1TB                              | 4         | 0.48%   |
| Unknown SD32G  32GB                                 | 4         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.48%   |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 0.48%   |
| Seagate ST3500413AS 500GB                           | 4         | 0.48%   |
| Seagate ST3500312CS 500GB                           | 4         | 0.48%   |
| Seagate ST2000DM006-2DM164 2TB                      | 4         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 139       | 206    | 40.17%  |
| WDC                 | 97        | 127    | 28.03%  |
| Toshiba             | 66        | 78     | 19.08%  |
| Samsung Electronics | 13        | 17     | 3.76%   |
| Hitachi             | 10        | 14     | 2.89%   |
| HGST                | 9         | 10     | 2.6%    |
| TO Exter            | 3         | 7      | 0.87%   |
| Hewlett-Packard     | 2         | 5      | 0.58%   |
| Apple               | 2         | 2      | 0.58%   |
| Unknown             | 1         | 1      | 0.29%   |
| KESU                | 1         | 1      | 0.29%   |
| JMicron Technology  | 1         | 1      | 0.29%   |
| Fujitsu             | 1         | 1      | 0.29%   |
| ACASIS              | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 74        | 90     | 33.18%  |
| WDC                 | 38        | 51     | 17.04%  |
| Crucial             | 21        | 28     | 9.42%   |
| Hewlett-Packard     | 15        | 15     | 6.73%   |
| Samsung Electronics | 11        | 14     | 4.93%   |
| SanDisk             | 10        | 12     | 4.48%   |
| Netac               | 7         | 7      | 3.14%   |
| A-DATA Technology   | 7         | 7      | 3.14%   |
| China               | 5         | 5      | 2.24%   |
| Seagate             | 4         | 8      | 1.79%   |
| LITEON              | 4         | 4      | 1.79%   |
| Gigabyte Technology | 4         | 4      | 1.79%   |
| Team                | 3         | 4      | 1.35%   |
| PNY                 | 3         | 3      | 1.35%   |
| Intel               | 3         | 3      | 1.35%   |
| Lenovo              | 2         | 3      | 0.9%    |
| Toshiba             | 1         | 1      | 0.45%   |
| SSSTC               | 1         | 1      | 0.45%   |
| SK hynix            | 1         | 4      | 0.45%   |
| Reletech-P400       | 1         | 2      | 0.45%   |
| NGFF                | 1         | 2      | 0.45%   |
| MSI                 | 1         | 1      | 0.45%   |
| Maxone              | 1         | 2      | 0.45%   |
| KingSpec            | 1         | 1      | 0.45%   |
| GLOWAY              | 1         | 1      | 0.45%   |
| Dogfish             | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| Unknown             | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 312       | 471    | 43.39%  |
| SSD     | 202       | 276    | 28.09%  |
| NVMe    | 172       | 237    | 23.92%  |
| MMC     | 25        | 32     | 3.48%   |
| Unknown | 8         | 13     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 426       | 733    | 66.56%  |
| NVMe | 172       | 237    | 26.88%  |
| MMC  | 25        | 32     | 3.91%   |
| SAS  | 17        | 27     | 2.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 291       | 436    | 56.4%   |
| 0.51-1.0   | 184       | 241    | 35.66%  |
| 1.01-2.0   | 28        | 50     | 5.43%   |
| 3.01-4.0   | 6         | 8      | 1.16%   |
| 4.01-10.0  | 4         | 8      | 0.78%   |
| 2.01-3.0   | 3         | 4      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 147       | 24.92%  |
| 101-250        | 127       | 21.53%  |
| 501-1000       | 107       | 18.14%  |
| 1001-2000      | 46        | 7.8%    |
| 51-100         | 44        | 7.46%   |
| 1-20           | 38        | 6.44%   |
| 21-50          | 36        | 6.1%    |
| More than 3000 | 19        | 3.22%   |
| 2001-3000      | 17        | 2.88%   |
| Unknown        | 9         | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 233       | 38.13%  |
| 21-50          | 106       | 17.35%  |
| 101-250        | 83        | 13.58%  |
| 251-500        | 58        | 9.49%   |
| 51-100         | 57        | 9.33%   |
| 501-1000       | 36        | 5.89%   |
| 1001-2000      | 18        | 2.95%   |
| Unknown        | 9         | 1.47%   |
| More than 3000 | 7         | 1.15%   |
| 2001-3000      | 4         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 5         | 5      | 6.94%   |
| Seagate ST3500418AS 500GB            | 4         | 4      | 5.56%   |
| WDC WD3200AAJS-56M0A0 320GB          | 3         | 5      | 4.17%   |
| Seagate ST1000DM003-9YN162 1TB       | 3         | 3      | 4.17%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 5      | 4.17%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 3      | 2.78%   |
| WDC WD5000AAKX-083CA1 500GB          | 2         | 2      | 2.78%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 2.78%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 3      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 2      | 2.78%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 4      | 2.78%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 1      | 1.39%   |
| WDC WD800BD-00MRA1 80GB              | 1         | 1      | 1.39%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 1.39%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1      | 1.39%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 1.39%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 1      | 1.39%   |
| WDC WD1600AAJS-75M0A0 160GB          | 1         | 1      | 1.39%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 1.39%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.39%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 1.39%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 1.39%   |
| Toshiba MK5065GSXN 500GB             | 1         | 1      | 1.39%   |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 1.39%   |
| Toshiba MK4058GSX 400GB              | 1         | 1      | 1.39%   |
| Toshiba MK2035GSS 200GB              | 1         | 1      | 1.39%   |
| Toshiba HDWJ110 1TB                  | 1         | 1      | 1.39%   |
| Toshiba DT01ACA100 1TB               | 1         | 1      | 1.39%   |
| SSSTC CVB-8D128-HP 128GB SSD         | 1         | 1      | 1.39%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 1.39%   |
| Seagate ST980811AS 80GB              | 1         | 1      | 1.39%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.39%   |
| Seagate ST500DM002-9YN14C 500GB      | 1         | 2      | 1.39%   |
| Seagate ST3500312CS 500GB            | 1         | 1      | 1.39%   |
| Seagate ST3320820SCE 320GB           | 1         | 2      | 1.39%   |
| Seagate ST3250820AS 250GB            | 1         | 1      | 1.39%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 1      | 1.39%   |
| SanDisk SSD U110 16GB                | 1         | 1      | 1.39%   |
| Samsung Electronics SP1644N 160GB    | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 33     | 39.44%  |
| WDC                 | 16        | 19     | 22.54%  |
| Toshiba             | 9         | 10     | 12.68%  |
| Hitachi             | 6         | 8      | 8.45%   |
| Samsung Electronics | 2         | 3      | 2.82%   |
| Kingston            | 2         | 2      | 2.82%   |
| HGST                | 2         | 2      | 2.82%   |
| Hewlett-Packard     | 2         | 2      | 2.82%   |
| SSSTC               | 1         | 1      | 1.41%   |
| SK hynix            | 1         | 1      | 1.41%   |
| SanDisk             | 1         | 1      | 1.41%   |
| A-DATA Technology   | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 33     | 46.67%  |
| WDC                 | 13        | 15     | 21.67%  |
| Toshiba             | 9         | 10     | 15%     |
| Hitachi             | 6         | 8      | 10%     |
| Samsung Electronics | 2         | 3      | 3.33%   |
| HGST                | 2         | 2      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 71     | 82.81%  |
| SSD  | 10        | 11     | 15.63%  |
| NVMe | 1         | 1      | 1.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 329       | 573    | 53.32%  |
| Works    | 224       | 371    | 36.3%   |
| Malfunc  | 63        | 83     | 10.21%  |
| Failed   | 1         | 2      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 361       | 52.86%  |
| AMD                              | 125       | 18.3%   |
| SanDisk                          | 40        | 5.86%   |
| Samsung Electronics              | 36        | 5.27%   |
| Kingston Technology Company      | 31        | 4.54%   |
| Micron Technology                | 11        | 1.61%   |
| SK hynix                         | 9         | 1.32%   |
| Micron/Crucial Technology        | 9         | 1.32%   |
| Phison Electronics               | 8         | 1.17%   |
| KIOXIA                           | 8         | 1.17%   |
| Nvidia                           | 7         | 1.02%   |
| Silicon Motion                   | 6         | 0.88%   |
| Marvell Technology Group         | 6         | 0.88%   |
| JMicron Technology               | 4         | 0.59%   |
| Union Memory (Shenzhen)          | 3         | 0.44%   |
| Yangtze Memory Technologies      | 2         | 0.29%   |
| Toshiba America Info Systems     | 2         | 0.29%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.29%   |
| Hewlett-Packard                  | 2         | 0.29%   |
| Biwin Storage Technology         | 2         | 0.29%   |
| ASMedia Technology               | 2         | 0.29%   |
| Solid State Storage Technology   | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Realtek Semiconductor            | 1         | 0.15%   |
| LSI Logic / Symbios Logic        | 1         | 0.15%   |
| INNOGRIT                         | 1         | 0.15%   |
| Broadcom / LSI                   | 1         | 0.15%   |
| Apple                            | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 80        | 10.36%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 38        | 4.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 28        | 3.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 25        | 3.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 21        | 2.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 2.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 18        | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 14        | 1.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 13        | 1.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 1.55%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 12        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 1.55%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 11        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 11        | 1.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 11        | 1.42%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 10        | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 10        | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 1.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 1.17%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 8         | 1.04%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 8         | 1.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 8         | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 7         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 7         | 0.91%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 6         | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 6         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 0.65%   |
| Nvidia MCP61 SATA Controller                                                   | 5         | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                     | 5         | 0.65%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 402       | 58.01%  |
| NVMe | 172       | 24.82%  |
| IDE  | 64        | 9.24%   |
| RAID | 52        | 7.5%    |
| SAS  | 2         | 0.29%   |
| SCSI | 1         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 396       | 70.97%  |
| AMD    | 159       | 28.49%  |
| ARM    | 3         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 1.25%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.07%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.07%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 6         | 1.07%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 1.07%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 0.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.89%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.89%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.89%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 0.89%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.89%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.72%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.72%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 0.72%   |
| Intel 13th Gen Core i9-13900H                 | 4         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 0.72%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 3         | 0.54%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 3         | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.54%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.54%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 0.54%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.54%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.54%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 3         | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.54%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.54%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 3         | 0.54%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 111       | 19.89%  |
| Intel Core i5           | 106       | 19%     |
| Intel Core i3           | 55        | 9.86%   |
| AMD Ryzen 5             | 43        | 7.71%   |
| Other                   | 40        | 7.17%   |
| AMD Ryzen 7             | 37        | 6.63%   |
| Intel Celeron           | 23        | 4.12%   |
| Intel Core 2 Duo        | 14        | 2.51%   |
| Intel Atom              | 11        | 1.97%   |
| Intel Xeon              | 10        | 1.79%   |
| AMD FX                  | 8         | 1.43%   |
| Intel Pentium           | 7         | 1.25%   |
| AMD Ryzen 9             | 7         | 1.25%   |
| AMD Ryzen 3             | 7         | 1.25%   |
| Intel Pentium Dual-Core | 6         | 1.08%   |
| AMD A8                  | 6         | 1.08%   |
| AMD A10                 | 6         | 1.08%   |
| Intel Pentium Dual      | 5         | 0.9%    |
| AMD E                   | 5         | 0.9%    |
| AMD A6                  | 5         | 0.9%    |
| AMD A4                  | 5         | 0.9%    |
| AMD Athlon              | 4         | 0.72%   |
| Intel Core 2 Quad       | 3         | 0.54%   |
| AMD Phenom II X4        | 3         | 0.54%   |
| AMD E1                  | 3         | 0.54%   |
| Intel Pentium Gold      | 2         | 0.36%   |
| Intel Pentium 4         | 2         | 0.36%   |
| Intel Core i9           | 2         | 0.36%   |
| Intel Core 2            | 2         | 0.36%   |
| AMD Sempron             | 2         | 0.36%   |
| AMD Ryzen 7 PRO         | 2         | 0.36%   |
| AMD Phenom              | 2         | 0.36%   |
| Intel Pentium D         | 1         | 0.18%   |
| Intel Genuine           | 1         | 0.18%   |
| Intel Celeron M         | 1         | 0.18%   |
| AMD Ryzen 5 PRO         | 1         | 0.18%   |
| AMD Quad-Core           | 1         | 0.18%   |
| AMD Phenom II X3        | 1         | 0.18%   |
| AMD Phenom II X2        | 1         | 0.18%   |
| AMD E2                  | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 214       | 38.35%  |
| 4       | 196       | 35.13%  |
| 6       | 50        | 8.96%   |
| 8       | 48        | 8.6%    |
| 1       | 15        | 2.69%   |
| 16      | 6         | 1.08%   |
| 10      | 6         | 1.08%   |
| 3       | 6         | 1.08%   |
| 14      | 5         | 0.9%    |
| 12      | 5         | 0.9%    |
| Unknown | 3         | 0.54%   |
| 24      | 2         | 0.36%   |
| 28      | 1         | 0.18%   |
| 20      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 554       | 99.28%  |
| 2       | 3         | 0.54%   |
| Unknown | 1         | 0.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 403       | 72.09%  |
| 1       | 153       | 27.37%  |
| Unknown | 3         | 0.54%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 547       | 97.33%  |
| 64-bit         | 6         | 1.07%   |
| Unknown        | 6         | 1.07%   |
| 32-bit         | 3         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 223       | 38.51%  |
| 0x306a9    | 26        | 4.49%   |
| 0x206a7    | 23        | 3.97%   |
| 0x306c3    | 15        | 2.59%   |
| 0x806ec    | 12        | 2.07%   |
| 0x806ea    | 11        | 1.9%    |
| 0x406e3    | 11        | 1.9%    |
| 0x40651    | 11        | 1.9%    |
| 0x08108109 | 11        | 1.9%    |
| 0x806e9    | 10        | 1.73%   |
| 0x1067a    | 10        | 1.73%   |
| 0x306d4    | 9         | 1.55%   |
| 0x906ea    | 7         | 1.21%   |
| 0x506e3    | 7         | 1.21%   |
| 0x0a50000c | 7         | 1.21%   |
| 0x08701021 | 7         | 1.21%   |
| 0x08108102 | 7         | 1.21%   |
| 0x906e9    | 6         | 1.04%   |
| 0x6fd      | 6         | 1.04%   |
| 0x20655    | 6         | 1.04%   |
| 0x806c1    | 5         | 0.86%   |
| 0x706e5    | 5         | 0.86%   |
| 0x06003106 | 5         | 0.86%   |
| 0x06000852 | 5         | 0.86%   |
| 0x010000c8 | 5         | 0.86%   |
| 0xa0652    | 4         | 0.69%   |
| 0x406c4    | 4         | 0.69%   |
| 0x30678    | 4         | 0.69%   |
| 0x20652    | 4         | 0.69%   |
| 0x08600106 | 4         | 0.69%   |
| 0x0810100b | 4         | 0.69%   |
| 0x07030105 | 4         | 0.69%   |
| 0xa0655    | 3         | 0.52%   |
| 0x806eb    | 3         | 0.52%   |
| 0x6fb      | 3         | 0.52%   |
| 0x10676    | 3         | 0.52%   |
| 0x10661    | 3         | 0.52%   |
| 0x0a50000d | 3         | 0.52%   |
| 0x08608103 | 3         | 0.52%   |
| 0x0800820d | 3         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 93        | 16.64%  |
| Haswell          | 44        | 7.87%   |
| IvyBridge        | 40        | 7.16%   |
| SandyBridge      | 31        | 5.55%   |
| Skylake          | 30        | 5.37%   |
| Zen+             | 29        | 5.19%   |
| Unknown          | 28        | 5.01%   |
| Zen 2            | 26        | 4.65%   |
| Zen 3            | 22        | 3.94%   |
| Penryn           | 20        | 3.58%   |
| Silvermont       | 18        | 3.22%   |
| Westmere         | 16        | 2.86%   |
| Core             | 15        | 2.68%   |
| Broadwell        | 15        | 2.68%   |
| Alderlake Hybrid | 14        | 2.5%    |
| Piledriver       | 13        | 2.33%   |
| CometLake        | 13        | 2.33%   |
| K10              | 12        | 2.15%   |
| IceLake          | 12        | 2.15%   |
| Zen              | 10        | 1.79%   |
| Goldmont plus    | 9         | 1.61%   |
| Excavator        | 8         | 1.43%   |
| TigerLake        | 7         | 1.25%   |
| Steamroller      | 7         | 1.25%   |
| Puma             | 6         | 1.07%   |
| Bobcat           | 6         | 1.07%   |
| NetBurst         | 3         | 0.54%   |
| Jaguar           | 3         | 0.54%   |
| P6               | 2         | 0.36%   |
| Nehalem          | 2         | 0.36%   |
| Bonnell          | 2         | 0.36%   |
| K8 Hammer        | 1         | 0.18%   |
| K10 Llano        | 1         | 0.18%   |
| Bulldozer        | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 326       | 48.37%  |
| AMD                              | 177       | 26.26%  |
| Nvidia                           | 167       | 24.78%  |
| Matrox Electronics Systems       | 2         | 0.3%    |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| ATI Technologies                 | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 3.89%   |
| Intel UHD Graphics 620                                                                   | 22        | 3.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 3.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 3.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 2.02%   |
| Intel HD Graphics 620                                                                    | 14        | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 2.02%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 1.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 1.59%   |
| Intel HD Graphics 530                                                                    | 10        | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.44%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10        | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.3%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 1.15%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 1.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.01%   |
| Intel HD Graphics 630                                                                    | 7         | 1.01%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 0.86%   |
| AMD Lucienne                                                                             | 6         | 0.86%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.72%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 5         | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.72%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 5         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 222       | 39.57%  |
| 1 x AMD        | 126       | 22.46%  |
| 1 x Nvidia     | 81        | 14.44%  |
| Intel + Nvidia | 71        | 12.66%  |
| Intel + AMD    | 25        | 4.46%   |
| AMD + Nvidia   | 16        | 2.85%   |
| 2 x AMD        | 11        | 1.96%   |
| Other          | 3         | 0.53%   |
| 2 x Intel      | 3         | 0.53%   |
| 1 x Matrox     | 2         | 0.36%   |
| 1 x SiS        | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 467       | 82.36%  |
| Proprietary | 84        | 14.81%  |
| Unknown     | 16        | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 318       | 55.4%   |
| 1.01-2.0   | 82        | 14.29%  |
| 0.01-0.5   | 67        | 11.67%  |
| 0.51-1.0   | 35        | 6.1%    |
| 3.01-4.0   | 33        | 5.75%   |
| 7.01-8.0   | 20        | 3.48%   |
| 5.01-6.0   | 12        | 2.09%   |
| 8.01-16.0  | 6         | 1.05%   |
| 2.01-3.0   | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 102       | 16.75%  |
| Chimei Innolux          | 83        | 13.63%  |
| BOE                     | 67        | 11%     |
| Goldstar                | 63        | 10.34%  |
| AU Optronics            | 63        | 10.34%  |
| LG Display              | 43        | 7.06%   |
| Hewlett-Packard         | 32        | 5.25%   |
| AOC                     | 20        | 3.28%   |
| Dell                    | 12        | 1.97%   |
| ViewSonic               | 10        | 1.64%   |
| Lenovo                  | 9         | 1.48%   |
| PANDA                   | 7         | 1.15%   |
| BenQ                    | 7         | 1.15%   |
| Apple                   | 7         | 1.15%   |
| Sony                    | 5         | 0.82%   |
| ASUSTek Computer        | 5         | 0.82%   |
| Unknown                 | 4         | 0.66%   |
| JRY                     | 4         | 0.66%   |
| Ancor Communications    | 4         | 0.66%   |
| Sharp                   | 3         | 0.49%   |
| MSD                     | 3         | 0.49%   |
| LG Philips              | 3         | 0.49%   |
| LG Electronics          | 3         | 0.49%   |
| Unknown                 | 3         | 0.49%   |
| Unknown (XXX)           | 2         | 0.33%   |
| TMX                     | 2         | 0.33%   |
| RGT                     | 2         | 0.33%   |
| Panasonic               | 2         | 0.33%   |
| Lenovo Group Limited    | 2         | 0.33%   |
| Hyundai ImageQuest      | 2         | 0.33%   |
| HannStar                | 2         | 0.33%   |
| Gigabyte Technology     | 2         | 0.33%   |
| CSO                     | 2         | 0.33%   |
| Chi Mei Optoelectronics | 2         | 0.33%   |
| AXV                     | 2         | 0.33%   |
| AGO                     | 2         | 0.33%   |
| Acer                    | 2         | 0.33%   |
| ZSC                     | 1         | 0.16%   |
| Yuraku                  | 1         | 0.16%   |
| Viotek                  | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 13        | 2.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 12        | 1.92%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 10        | 1.6%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 6         | 0.96%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.8%    |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch        | 5         | 0.8%    |
| Samsung Electronics SA300/SA350 SAM078D 1600x900 443x249mm 20.0-inch  | 4         | 0.64%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.64%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.64%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 4         | 0.64%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 4         | 0.64%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch  | 3         | 0.48%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.48%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.48%   |
| JRY DP JRY2380 1920x1080 527x297mm 23.8-inch                          | 3         | 0.48%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 3         | 0.48%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 3         | 0.48%   |
| Goldstar E1951 GSM4BFD 1366x768 410x230mm 18.5-inch                   | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 3         | 0.48%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.48%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 3         | 0.48%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 3         | 0.48%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.48%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 3         | 0.48%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 3         | 0.48%   |
| Unknown                                                               | 3         | 0.48%   |
| ViewSonic VA2246 Series VSC6F2E 1920x1080 477x268mm 21.5-inch         | 2         | 0.32%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 2         | 0.32%   |
| Samsung Electronics SyncMaster SAM0272 1280x1024 338x270mm 17.0-inch  | 2         | 0.32%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch      | 2         | 0.32%   |
| Samsung Electronics S22A33x SAM7122 1920x1080 479x260mm 21.5-inch     | 2         | 0.32%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 443x249mm 20.0-inch      | 2         | 0.32%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch      | 2         | 0.32%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 2         | 0.32%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch     | 2         | 0.32%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 2         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 226       | 38.31%  |
| 1366x768 (WXGA)    | 186       | 31.53%  |
| 1600x900 (HD+)     | 37        | 6.27%   |
| 3840x2160 (4K)     | 21        | 3.56%   |
| 1360x768           | 16        | 2.71%   |
| 1920x1200 (WUXGA)  | 15        | 2.54%   |
| 2560x1440 (QHD)    | 13        | 2.2%    |
| 1440x900 (WXGA+)   | 11        | 1.86%   |
| 1280x800 (WXGA)    | 11        | 1.86%   |
| 3840x1080          | 6         | 1.02%   |
| 2160x1440          | 6         | 1.02%   |
| Unknown            | 6         | 1.02%   |
| 2560x1600          | 5         | 0.85%   |
| 1280x1024 (SXGA)   | 5         | 0.85%   |
| 1024x768 (XGA)     | 5         | 0.85%   |
| 1680x1050 (WSXGA+) | 4         | 0.68%   |
| 2560x1080          | 3         | 0.51%   |
| 3200x1800 (QHD+)   | 2         | 0.34%   |
| 1280x720 (HD)      | 2         | 0.34%   |
| 1024x600           | 2         | 0.34%   |
| 800x1280           | 1         | 0.17%   |
| 640x480            | 1         | 0.17%   |
| 3440x1440          | 1         | 0.17%   |
| 3200x2000          | 1         | 0.17%   |
| 3072x1920          | 1         | 0.17%   |
| 2880x1920          | 1         | 0.17%   |
| 2880x1800          | 1         | 0.17%   |
| 2520x1680          | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 176       | 29.04%  |
| 13      | 65        | 10.73%  |
| 21      | 52        | 8.58%   |
| 23      | 49        | 8.09%   |
| 14      | 49        | 8.09%   |
| 18      | 26        | 4.29%   |
| 20      | 23        | 3.8%    |
| 31      | 20        | 3.3%    |
| 27      | 20        | 3.3%    |
| Unknown | 20        | 3.3%    |
| 17      | 19        | 3.14%   |
| 24      | 17        | 2.81%   |
| 19      | 15        | 2.48%   |
| 16      | 13        | 2.15%   |
| 11      | 9         | 1.49%   |
| 48      | 4         | 0.66%   |
| 12      | 4         | 0.66%   |
| 32      | 3         | 0.5%    |
| 84      | 2         | 0.33%   |
| 72      | 2         | 0.33%   |
| 54      | 2         | 0.33%   |
| 46      | 2         | 0.33%   |
| 34      | 2         | 0.33%   |
| 30      | 2         | 0.33%   |
| 22      | 2         | 0.33%   |
| 10      | 2         | 0.33%   |
| 60      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 43      | 1         | 0.17%   |
| 39      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 7       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 285       | 47.74%  |
| 401-500     | 113       | 18.93%  |
| 501-600     | 85        | 14.24%  |
| 201-300     | 33        | 5.53%   |
| 601-700     | 22        | 3.69%   |
| Unknown     | 20        | 3.35%   |
| 351-400     | 17        | 2.85%   |
| 1001-1500   | 10        | 1.68%   |
| 701-800     | 5         | 0.84%   |
| 1501-2000   | 4         | 0.67%   |
| 801-900     | 1         | 0.17%   |
| 901-1000    | 1         | 0.17%   |
| 1-100       | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 448       | 82.66%  |
| 16/10   | 49        | 9.04%   |
| Unknown | 18        | 3.32%   |
| 5/4     | 8         | 1.48%   |
| 4/3     | 8         | 1.48%   |
| 3/2     | 8         | 1.48%   |
| 21/9    | 2         | 0.37%   |
| 0.62    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 176       | 29.33%  |
| 81-90          | 97        | 16.17%  |
| 201-250        | 97        | 16.17%  |
| 151-200        | 53        | 8.83%   |
| 141-150        | 30        | 5%      |
| 351-500        | 27        | 4.5%    |
| 301-350        | 21        | 3.5%    |
| Unknown        | 20        | 3.33%   |
| 71-80          | 16        | 2.67%   |
| 111-120        | 13        | 2.17%   |
| More than 1000 | 12        | 2%      |
| 121-130        | 10        | 1.67%   |
| 51-60          | 9         | 1.5%    |
| 251-300        | 4         | 0.67%   |
| 131-140        | 4         | 0.67%   |
| 501-1000       | 4         | 0.67%   |
| 61-70          | 2         | 0.33%   |
| 41-50          | 2         | 0.33%   |
| 91-100         | 2         | 0.33%   |
| 1-40           | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 227       | 38.41%  |
| 51-100        | 176       | 29.78%  |
| 121-160       | 125       | 21.15%  |
| Unknown       | 20        | 3.38%   |
| 161-240       | 19        | 3.21%   |
| 1-50          | 18        | 3.05%   |
| More than 240 | 6         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 461       | 80.59%  |
| 2     | 87        | 15.21%  |
| 0     | 16        | 2.8%    |
| 3     | 8         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 351       | 43.01%  |
| Intel                            | 203       | 24.88%  |
| Qualcomm Atheros                 | 104       | 12.75%  |
| Broadcom                         | 33        | 4.04%   |
| TP-Link                          | 20        | 2.45%   |
| MediaTek                         | 16        | 1.96%   |
| Xiaomi                           | 11        | 1.35%   |
| Ralink                           | 10        | 1.23%   |
| Ralink Technology                | 8         | 0.98%   |
| Nvidia                           | 7         | 0.86%   |
| Microsoft                        | 6         | 0.74%   |
| Marvell Technology Group         | 6         | 0.74%   |
| Broadcom Limited                 | 5         | 0.61%   |
| ASIX Electronics                 | 5         | 0.61%   |
| Qualcomm Atheros Communications  | 4         | 0.49%   |
| ICS Advent                       | 4         | 0.49%   |
| Motorola PCS                     | 3         | 0.37%   |
| D-Link System                    | 3         | 0.37%   |
| Samsung Electronics              | 2         | 0.25%   |
| Qualcomm                         | 2         | 0.25%   |
| OPPO Electronics                 | 2         | 0.25%   |
| Huawei Technologies              | 2         | 0.25%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.12%   |
| T & A Mobile Phones              | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| Google                           | 1         | 0.12%   |
| Emulex                           | 1         | 0.12%   |
| DisplayLink                      | 1         | 0.12%   |
| D-Link                           | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 232       | 24.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 53        | 5.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 31        | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 23        | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 19        | 1.97%   |
| Intel Wi-Fi 6 AX200                                                    | 16        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 14        | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 13        | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 1.24%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 1.04%   |
| Intel Wireless 8260                                                    | 10        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 10        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                          | 10        | 1.04%   |
| Intel Wireless 8265 / 8275                                             | 9         | 0.93%   |
| Intel Wireless 7260                                                    | 9         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.83%   |
| Intel Wireless 7265                                                    | 8         | 0.83%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.83%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 7         | 0.73%   |
| Realtek 802.11ac NIC                                                   | 7         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7         | 0.73%   |
| Intel 82579V Gigabit Network Connection                                | 7         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 6         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 6         | 0.62%   |
| Ralink MT7601U Wireless Adapter                                        | 6         | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.62%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 6         | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.62%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 6         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 6         | 0.62%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                    | 5         | 0.52%   |
| Nvidia MCP61 Ethernet                                                  | 5         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                  | 5         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 146       | 33.41%  |
| Realtek Semiconductor           | 109       | 24.94%  |
| Qualcomm Atheros                | 90        | 20.59%  |
| Broadcom                        | 29        | 6.64%   |
| TP-Link                         | 17        | 3.89%   |
| MediaTek                        | 14        | 3.2%    |
| Ralink                          | 10        | 2.29%   |
| Ralink Technology               | 8         | 1.83%   |
| Microsoft                       | 5         | 1.14%   |
| Qualcomm Atheros Communications | 4         | 0.92%   |
| Qualcomm                        | 1         | 0.23%   |
| Marvell Technology Group        | 1         | 0.23%   |
| D-Link System                   | 1         | 0.23%   |
| D-Link                          | 1         | 0.23%   |
| Broadcom Limited                | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 7.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 3.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 3.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 3.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 2.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 12        | 2.75%   |
| Intel Wireless 8260                                                     | 10        | 2.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 10        | 2.29%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 2.29%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.06%   |
| Intel Wireless 7260                                                     | 9         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.83%   |
| Intel Wireless 7265                                                     | 8         | 1.83%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 1.6%    |
| Realtek 802.11ac NIC                                                    | 7         | 1.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.37%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 1.37%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.37%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 6         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.37%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 6         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.37%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 5         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.92%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 4         | 0.92%   |
| TP-Link 802.11n NIC                                                     | 3         | 0.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.69%   |
| Microsoft Xbox Wireless Adapter for Windows                             | 3         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 314       | 60.5%   |
| Intel                            | 110       | 21.19%  |
| Qualcomm Atheros                 | 26        | 5.01%   |
| Xiaomi                           | 11        | 2.12%   |
| Broadcom                         | 8         | 1.54%   |
| Nvidia                           | 7         | 1.35%   |
| Marvell Technology Group         | 5         | 0.96%   |
| ASIX Electronics                 | 5         | 0.96%   |
| ICS Advent                       | 4         | 0.77%   |
| Broadcom Limited                 | 4         | 0.77%   |
| TP-Link                          | 3         | 0.58%   |
| Motorola PCS                     | 3         | 0.58%   |
| OPPO Electronics                 | 2         | 0.39%   |
| MediaTek                         | 2         | 0.39%   |
| Huawei Technologies              | 2         | 0.39%   |
| D-Link System                    | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.19%   |
| T & A Mobile Phones              | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| Samsung Electronics              | 1         | 0.19%   |
| Qualcomm                         | 1         | 0.19%   |
| Microsoft                        | 1         | 0.19%   |
| Lenovo                           | 1         | 0.19%   |
| Google                           | 1         | 0.19%   |
| Emulex                           | 1         | 0.19%   |
| DisplayLink                      | 1         | 0.19%   |
| Apple                            | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 232       | 44.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 53        | 10.06%  |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 2.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 11        | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 1.9%    |
| Intel I211 Gigabit Network Connection                                  | 8         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                                   | 8         | 1.52%   |
| Intel 82579V Gigabit Network Connection                                | 7         | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.14%   |
| Nvidia MCP61 Ethernet                                                  | 5         | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                  | 5         | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.76%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.76%   |
| Intel Ethernet Connection (12) I219-V                                  | 4         | 0.76%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 4         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.57%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.57%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.57%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.57%   |
| Intel 82578DC Gigabit Network Connection                               | 3         | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.57%   |
| TP-Link USB 10/100 LAN                                                 | 2         | 0.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]     | 2         | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 0.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.38%   |
| OPPO OnePlus Nord 4                                                    | 2         | 0.38%   |
| Motorola PCS moto g84 5G                                               | 2         | 0.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 489       | 53.68%  |
| WiFi     | 421       | 46.21%  |
| Modem    | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 312       | 53.7%   |
| Ethernet | 269       | 46.3%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 305       | 54.56%  |
| 1     | 233       | 41.68%  |
| 0     | 13        | 2.33%   |
| 3     | 6         | 1.07%   |
| 6     | 1         | 0.18%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 434       | 75.74%  |
| Yes  | 139       | 24.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 36.15%  |
| Realtek Semiconductor           | 65        | 18.95%  |
| Qualcomm Atheros Communications | 40        | 11.66%  |
| IMC Networks                    | 27        | 7.87%   |
| Cambridge Silicon Radio         | 18        | 5.25%   |
| Lite-On Technology              | 14        | 4.08%   |
| Broadcom                        | 11        | 3.21%   |
| Toshiba                         | 8         | 2.33%   |
| TP-Link                         | 6         | 1.75%   |
| Ralink                          | 6         | 1.75%   |
| Apple                           | 6         | 1.75%   |
| Foxconn / Hon Hai               | 5         | 1.46%   |
| Hewlett-Packard                 | 3         | 0.87%   |
| Realtek                         | 2         | 0.58%   |
| MediaTek                        | 2         | 0.58%   |
| Dell                            | 2         | 0.58%   |
| TRENDnet                        | 1         | 0.29%   |
| Integrated System Solution      | 1         | 0.29%   |
| Foxconn International           | 1         | 0.29%   |
| Alps Electric                   | 1         | 0.29%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 40        | 11.66%  |
| Realtek Bluetooth Radio                             | 30        | 8.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 8.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 28        | 8.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 7%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 5.25%   |
| Intel AX200 Bluetooth                               | 16        | 4.66%   |
| Intel AX201 Bluetooth                               | 14        | 4.08%   |
| IMC Networks Wireless_Device                        | 12        | 3.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 2.33%   |
| IMC Networks Bluetooth Radio                        | 8         | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 2.04%   |
| Intel AX211 Bluetooth                               | 7         | 2.04%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 6         | 1.75%   |
| Ralink RT3290 Bluetooth                             | 6         | 1.75%   |
| Toshiba Bluetooth Device                            | 5         | 1.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.17%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 1.17%   |
| IMC Networks Bluetooth Device                       | 4         | 1.17%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.87%   |
| Lite-On Bluetooth Radio                             | 3         | 0.87%   |
| Lite-On Bluetooth Device                            | 3         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.87%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.87%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.87%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.58%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.58%   |
| Realtek Bluetooth Radio                             | 2         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.58%   |
| MediaTek Wireless_Device                            | 2         | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.58%   |
| Intel AX210 Bluetooth                               | 2         | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.58%   |
| Broadcom HP Portable Valentine                      | 2         | 0.58%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 378       | 51.43%  |
| AMD                              | 182       | 24.76%  |
| Nvidia                           | 127       | 17.28%  |
| C-Media Electronics              | 10        | 1.36%   |
| Generalplus Technology           | 4         | 0.54%   |
| Microsoft                        | 3         | 0.41%   |
| Logitech                         | 3         | 0.41%   |
| Kingston Technology              | 3         | 0.41%   |
| Texas Instruments                | 2         | 0.27%   |
| Sony                             | 2         | 0.27%   |
| JMTek                            | 2         | 0.27%   |
| GN Netcom                        | 2         | 0.27%   |
| BEHRINGER International          | 2         | 0.27%   |
| Tenx Technology                  | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Samson Technologies              | 1         | 0.14%   |
| Razer USA                        | 1         | 0.14%   |
| Pixart Imaging                   | 1         | 0.14%   |
| Panasonic (Matsushita)           | 1         | 0.14%   |
| Micro Star International         | 1         | 0.14%   |
| JBL                              | 1         | 0.14%   |
| Hewlett-Packard                  | 1         | 0.14%   |
| Creative Technology              | 1         | 0.14%   |
| Creative Labs                    | 1         | 0.14%   |
| Chicony Electronics              | 1         | 0.14%   |
| ATI Technologies                 | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |
| Unknown                          | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 70        | 7.74%   |
| Intel Sunrise Point-LP HD Audio                                            | 52        | 5.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 4.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 31        | 3.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 30        | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 3.1%    |
| AMD FCH Azalia Controller                                                  | 25        | 2.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 22        | 2.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 21        | 2.32%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17        | 1.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 1.55%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 1.55%   |
| Nvidia GF108 High Definition Audio Controller                              | 13        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 1.44%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 1.44%   |
| AMD Kabini HDMI/DP Audio                                                   | 12        | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 1.11%   |
| Nvidia GA104 High Definition Audio Controller                              | 9         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 9         | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 1%      |
| Intel 200 Series PCH HD Audio                                              | 9         | 1%      |
| AMD Navi 10 HDMI Audio                                                     | 9         | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 0.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 0.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7         | 0.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 97        | 24.31%  |
| Kingston                     | 86        | 21.55%  |
| SK hynix                     | 65        | 16.29%  |
| Micron Technology            | 42        | 10.53%  |
| Unknown                      | 20        | 5.01%   |
| Ramaxel Technology           | 14        | 3.51%   |
| Corsair                      | 13        | 3.26%   |
| Team                         | 12        | 3.01%   |
| Crucial                      | 12        | 3.01%   |
| Unknown (ABCD)               | 6         | 1.5%    |
| Hewlett-Packard              | 6         | 1.5%    |
| A-DATA Technology            | 5         | 1.25%   |
| Elpida                       | 3         | 0.75%   |
| Patriot                      | 2         | 0.5%    |
| Nanya Technology             | 2         | 0.5%    |
| CSX                          | 2         | 0.5%    |
| Unknown (0x7FA8000000000000) | 1         | 0.25%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.25%   |
| S                            | 1         | 0.25%   |
| Qumo                         | 1         | 0.25%   |
| Princeton                    | 1         | 0.25%   |
| M                            | 1         | 0.25%   |
| Kllisre                      | 1         | 0.25%   |
| Goldkey                      | 1         | 0.25%   |
| GeIL                         | 1         | 0.25%   |
| Apacer                       | 1         | 0.25%   |
| 80540000802C                 | 1         | 0.25%   |
| Unknown                      | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 1.59%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 1.37%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 1.14%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 5         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.14%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.14%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.14%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.14%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.91%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.91%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 4         | 0.91%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 3         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.68%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s              | 3         | 0.68%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 3         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.46%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 0.46%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 2         | 0.46%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 149       | 47.3%   |
| DDR3    | 116       | 36.83%  |
| LPDDR4  | 14        | 4.44%   |
| DDR2    | 14        | 4.44%   |
| DDR5    | 6         | 1.9%    |
| LPDDR3  | 5         | 1.59%   |
| SDRAM   | 4         | 1.27%   |
| Unknown | 4         | 1.27%   |
| LPDDR5  | 3         | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 192       | 61.15%  |
| DIMM         | 108       | 34.39%  |
| Row Of Chips | 11        | 3.5%    |
| Unknown      | 2         | 0.64%   |
| Chip         | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 146       | 39.89%  |
| 4096  | 109       | 29.78%  |
| 16384 | 46        | 12.57%  |
| 2048  | 38        | 10.38%  |
| 32768 | 16        | 4.37%   |
| 1024  | 8         | 2.19%   |
| 512   | 3         | 0.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 76        | 21.05%  |
| 3200    | 62        | 17.17%  |
| 2667    | 60        | 16.62%  |
| 1333    | 26        | 7.2%    |
| 2400    | 25        | 6.93%   |
| 2133    | 17        | 4.71%   |
| 3466    | 8         | 2.22%   |
| 3266    | 7         | 1.94%   |
| 1334    | 7         | 1.94%   |
| Unknown | 6         | 1.66%   |
| 3800    | 5         | 1.39%   |
| 3000    | 5         | 1.39%   |
| 1867    | 5         | 1.39%   |
| 800     | 5         | 1.39%   |
| 3733    | 4         | 1.11%   |
| 533     | 4         | 1.11%   |
| 4800    | 3         | 0.83%   |
| 3600    | 3         | 0.83%   |
| 1067    | 3         | 0.83%   |
| 667     | 3         | 0.83%   |
| 5500    | 2         | 0.55%   |
| 3534    | 2         | 0.55%   |
| 3400    | 2         | 0.55%   |
| 1800    | 2         | 0.55%   |
| 1066    | 2         | 0.55%   |
| 6400    | 1         | 0.28%   |
| 6000    | 1         | 0.28%   |
| 5600    | 1         | 0.28%   |
| 5200    | 1         | 0.28%   |
| 4267    | 1         | 0.28%   |
| 4199    | 1         | 0.28%   |
| 3151    | 1         | 0.28%   |
| 3100    | 1         | 0.28%   |
| 3066    | 1         | 0.28%   |
| 2933    | 1         | 0.28%   |
| 2733    | 1         | 0.28%   |
| 2666    | 1         | 0.28%   |
| 2200    | 1         | 0.28%   |
| 2134    | 1         | 0.28%   |
| 1866    | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Brother Industries            | 4         | 23.53%  |
| Seiko Epson                   | 3         | 17.65%  |
| Hewlett-Packard               | 3         | 17.65%  |
| Canon                         | 3         | 17.65%  |
| Samsung Info. Systems America | 2         | 11.76%  |
| Star Micronics                | 1         | 5.88%   |
| Prolific Technology           | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Samsung Info. Systems America SAMSUNG SRP-270 | 2         | 11.76%  |
| Brother DCP-T310                              | 2         | 11.76%  |
| Star Micronics TUP592 (STR_T-001)             | 1         | 5.88%   |
| Seiko Epson L3150 Series                      | 1         | 5.88%   |
| Seiko Epson ET-2850 Series                    | 1         | 5.88%   |
| Seiko Epson ET-2810 Series                    | 1         | 5.88%   |
| Prolific PL2305 Parallel Port                 | 1         | 5.88%   |
| HP PSC 1400                                   | 1         | 5.88%   |
| HP LaserJet Professional P 1102w              | 1         | 5.88%   |
| HP DeskJet 2700 series                        | 1         | 5.88%   |
| Canon PIXMA MG3600 Series                     | 1         | 5.88%   |
| Canon G2010 series                            | 1         | 5.88%   |
| Canon E400 series                             | 1         | 5.88%   |
| Brother DCP-T300                              | 1         | 5.88%   |
| Brother DCP-9020CDW                           | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 2         | 66.67%  |
| HP ScanJet 2400c       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 75        | 20.11%  |
| Microdia                               | 33        | 8.85%   |
| IMC Networks                           | 32        | 8.58%   |
| Realtek Semiconductor                  | 28        | 7.51%   |
| Quanta                                 | 20        | 5.36%   |
| Bison Electronics                      | 20        | 5.36%   |
| Syntek                                 | 19        | 5.09%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 5.09%   |
| Sunplus Innovation Technology          | 16        | 4.29%   |
| Lite-On Technology                     | 16        | 4.29%   |
| Suyin                                  | 15        | 4.02%   |
| Logitech                               | 11        | 2.95%   |
| Generalplus Technology                 | 9         | 2.41%   |
| Apple                                  | 7         | 1.88%   |
| Acer                                   | 7         | 1.88%   |
| Microsoft                              | 6         | 1.61%   |
| ShineTech                              | 5         | 1.34%   |
| Luxvisions Innotech Limited            | 5         | 1.34%   |
| Z-Star Microelectronics                | 4         | 1.07%   |
| Sonix Technology                       | 4         | 1.07%   |
| Importek                               | 4         | 1.07%   |
| Samsung Electronics                    | 3         | 0.8%    |
| Alcor Micro                            | 3         | 0.8%    |
| Ricoh                                  | 2         | 0.54%   |
| Jieli Technology                       | 2         | 0.54%   |
| Cubeternet                             | 2         | 0.54%   |
| Xiongmai                               | 1         | 0.27%   |
| Silicon Motion                         | 1         | 0.27%   |
| Huawei Technologies                    | 1         | 0.27%   |
| Aveo Technology                        | 1         | 0.27%   |
| ASUSTek Computer                       | 1         | 0.27%   |
| ANYKA                                  | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 12        | 3.19%   |
| Chicony Integrated Camera                                                  | 11        | 2.93%   |
| Bison Integrated Camera                                                    | 10        | 2.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 2.13%   |
| Microdia Webcam Vitade AF                                                  | 7         | 1.86%   |
| Lite-On Integrated Camera                                                  | 7         | 1.86%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 1.86%   |
| Generalplus GENERAL WEBCAM                                                 | 7         | 1.86%   |
| Chicony EasyCamera                                                         | 7         | 1.86%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 1.6%    |
| IMC Networks Integrated Camera                                             | 6         | 1.6%    |
| Chicony HP Truevision HD                                                   | 6         | 1.6%    |
| Sunplus Integrated_Webcam_HD                                               | 5         | 1.33%   |
| ShineTech USB2.0 HD UVC WebCam                                             | 5         | 1.33%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 1.33%   |
| IMC Networks HP TrueVision HD Camera                                       | 5         | 1.33%   |
| Chicony Lenovo EasyCamera                                                  | 5         | 1.33%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.06%   |
| Quanta HD Camera                                                           | 4         | 1.06%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.06%   |
| Chicony HP Wide Vision HD Camera                                           | 4         | 1.06%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.06%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 3         | 0.8%    |
| Lite-On HP HD Camera                                                       | 3         | 0.8%    |
| Chicony HP Webcam                                                          | 3         | 0.8%    |
| Chicony HP HD Webcam                                                       | 3         | 0.8%    |
| Chicony HD WebCam                                                          | 3         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.8%    |
| Apple FaceTime HD Camera                                                   | 3         | 0.8%    |
| Suyin HP Truevision HD                                                     | 2         | 0.53%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 2         | 0.53%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.53%   |
| Sunplus Integrated Webcam                                                  | 2         | 0.53%   |
| Sunplus Asus Webcam                                                        | 2         | 0.53%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.53%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 46.43%  |
| Synaptics                  | 15        | 26.79%  |
| Shenzhen Goodix Technology | 7         | 12.5%   |
| Elan Microelectronics      | 5         | 8.93%   |
| AuthenTec                  | 2         | 3.57%   |
| STMicroelectronics         | 1         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 8         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 7         | 12.5%   |
| Synaptics  WBDI                                           | 4         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                       | 4         | 7.14%   |
| Elan ELAN:Fingerprint                                     | 4         | 7.14%   |
| Validity Sensors Synaptics WBDI                           | 3         | 5.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 3         | 5.36%   |
| Shenzhen Goodix Fingerprint Reader                        | 3         | 5.36%   |
| Validity Sensors Fingerprint scanner                      | 2         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 3.57%   |
| Synaptics WBDI                                            | 2         | 3.57%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 3.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 1.79%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 1.79%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 1.79%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.79%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1.79%   |
| Synaptics UWP WBDI Device                                 | 1         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.79%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 1.79%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 1.79%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 1.79%   |
| Elan ELAN:ARM-M4                                          | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 45%     |
| Alcor Micro | 6         | 30%     |
| Upek        | 3         | 15%     |
| Yubico.com  | 1         | 5%      |
| O2 Micro    | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 15%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15%     |
| Broadcom 5880                                                                | 3         | 15%     |
| Broadcom 58200                                                               | 2         | 10%     |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 406       | 71.35%  |
| 1     | 133       | 23.37%  |
| 2     | 23        | 4.04%   |
| 3     | 5         | 0.88%   |
| 5     | 1         | 0.18%   |
| 4     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 29.32%  |
| Graphics card            | 47        | 24.61%  |
| Net/wireless             | 29        | 15.18%  |
| Chipcard                 | 16        | 8.38%   |
| Bluetooth                | 9         | 4.71%   |
| Sound                    | 6         | 3.14%   |
| Multimedia controller    | 6         | 3.14%   |
| Camera                   | 5         | 2.62%   |
| Net/ethernet             | 4         | 2.09%   |
| Communication controller | 4         | 2.09%   |
| Card reader              | 3         | 1.57%   |
| Unassigned class         | 2         | 1.05%   |
| Storage                  | 2         | 1.05%   |
| Network                  | 1         | 0.52%   |
| Firewire controller      | 1         | 0.52%   |

