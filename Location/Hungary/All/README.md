Linux in Hungary - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hungary/Desktop/README.md) and [notebooks](/Location/Hungary/Notebook/README.md).

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

Total: 9001

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sony          | VPCS13V9E                   | Notebook    | [61230cc69b](https://linux-hardware.org/?probe=61230cc69b) | Dec 24, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [63306d22b2](https://linux-hardware.org/?probe=63306d22b2) | Dec 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a32ea319ca](https://linux-hardware.org/?probe=a32ea319ca) | Dec 23, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [fd501fc946](https://linux-hardware.org/?probe=fd501fc946) | Dec 23, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | Notebook    | [1947533de1](https://linux-hardware.org/?probe=1947533de1) | Dec 23, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [05f387de9b](https://linux-hardware.org/?probe=05f387de9b) | Dec 23, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [7d9fabde46](https://linux-hardware.org/?probe=7d9fabde46) | Dec 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [bf31061d97](https://linux-hardware.org/?probe=bf31061d97) | Dec 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a4ecaaf236](https://linux-hardware.org/?probe=a4ecaaf236) | Dec 23, 2023 |
| Dell          | Latitude E6410              | Notebook    | [7e14c30601](https://linux-hardware.org/?probe=7e14c30601) | Dec 23, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [2cc486fed2](https://linux-hardware.org/?probe=2cc486fed2) | Dec 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [852693eb71](https://linux-hardware.org/?probe=852693eb71) | Dec 22, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [acab7c340a](https://linux-hardware.org/?probe=acab7c340a) | Dec 22, 2023 |
| HP            | Notebook                    | Notebook    | [bb4cdbdf05](https://linux-hardware.org/?probe=bb4cdbdf05) | Dec 22, 2023 |
| HP            | Notebook                    | Notebook    | [1b95abcc1b](https://linux-hardware.org/?probe=1b95abcc1b) | Dec 22, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [00781519db](https://linux-hardware.org/?probe=00781519db) | Dec 22, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [e4c0a2d0d7](https://linux-hardware.org/?probe=e4c0a2d0d7) | Dec 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [b8f11e5aeb](https://linux-hardware.org/?probe=b8f11e5aeb) | Dec 22, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [41b209e906](https://linux-hardware.org/?probe=41b209e906) | Dec 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7d521242f4](https://linux-hardware.org/?probe=7d521242f4) | Dec 22, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | Notebook    | [e7c2d69943](https://linux-hardware.org/?probe=e7c2d69943) | Dec 22, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [476ef9075c](https://linux-hardware.org/?probe=476ef9075c) | Dec 21, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [b5d6e26b97](https://linux-hardware.org/?probe=b5d6e26b97) | Dec 21, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [544fdd3054](https://linux-hardware.org/?probe=544fdd3054) | Dec 21, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [7666e1047d](https://linux-hardware.org/?probe=7666e1047d) | Dec 21, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [3b149d0e20](https://linux-hardware.org/?probe=3b149d0e20) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [0f7957917e](https://linux-hardware.org/?probe=0f7957917e) | Dec 21, 2023 |
| eMachines     | E725                        | Notebook    | [7b9f0ee917](https://linux-hardware.org/?probe=7b9f0ee917) | Dec 20, 2023 |
| eMachines     | E725                        | Notebook    | [950542e12b](https://linux-hardware.org/?probe=950542e12b) | Dec 20, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [ae2fef5c99](https://linux-hardware.org/?probe=ae2fef5c99) | Dec 20, 2023 |
| Dell          | Latitude E5540              | Notebook    | [af5e30a046](https://linux-hardware.org/?probe=af5e30a046) | Dec 20, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [e696fd9ae0](https://linux-hardware.org/?probe=e696fd9ae0) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ff06842733](https://linux-hardware.org/?probe=ff06842733) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| Dell          | Latitude D630               | Notebook    | [914826699f](https://linux-hardware.org/?probe=914826699f) | Dec 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [5eca78aa43](https://linux-hardware.org/?probe=5eca78aa43) | Dec 19, 2023 |
| Mediacom      | GTZS                        | Notebook    | [f326507469](https://linux-hardware.org/?probe=f326507469) | Dec 19, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [3cc3621576](https://linux-hardware.org/?probe=3cc3621576) | Dec 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [02d834a147](https://linux-hardware.org/?probe=02d834a147) | Dec 19, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [da996ce093](https://linux-hardware.org/?probe=da996ce093) | Dec 18, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [ee0f91ec22](https://linux-hardware.org/?probe=ee0f91ec22) | Dec 18, 2023 |
| HP            | Compaq 6710b                | Notebook    | [8a4026815f](https://linux-hardware.org/?probe=8a4026815f) | Dec 18, 2023 |
| HP            | Compaq 6710b                | Notebook    | [01324b2772](https://linux-hardware.org/?probe=01324b2772) | Dec 18, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [d688c80ef7](https://linux-hardware.org/?probe=d688c80ef7) | Dec 18, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [dec9660b8e](https://linux-hardware.org/?probe=dec9660b8e) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [a7d805aa7c](https://linux-hardware.org/?probe=a7d805aa7c) | Dec 18, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [da0af8ac25](https://linux-hardware.org/?probe=da0af8ac25) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [72663c66da](https://linux-hardware.org/?probe=72663c66da) | Dec 18, 2023 |
| Samsung       | RV409/RV509/RV709           | Notebook    | [7f55b490b8](https://linux-hardware.org/?probe=7f55b490b8) | Dec 18, 2023 |
| Lenovo        | G70-70 80HW                 | Notebook    | [dc86fb0437](https://linux-hardware.org/?probe=dc86fb0437) | Dec 18, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [b4c4267477](https://linux-hardware.org/?probe=b4c4267477) | Dec 17, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [1333627761](https://linux-hardware.org/?probe=1333627761) | Dec 17, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [96b31f90ac](https://linux-hardware.org/?probe=96b31f90ac) | Dec 17, 2023 |
| ASUSTek       | K53BY                       | Notebook    | [db6b177a99](https://linux-hardware.org/?probe=db6b177a99) | Dec 17, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [4302968166](https://linux-hardware.org/?probe=4302968166) | Dec 17, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0eb62b79e1](https://linux-hardware.org/?probe=0eb62b79e1) | Dec 17, 2023 |
| HP            | 1497                        | Desktop     | [20ba1e3df2](https://linux-hardware.org/?probe=20ba1e3df2) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [2262526770](https://linux-hardware.org/?probe=2262526770) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [ed366a10ca](https://linux-hardware.org/?probe=ed366a10ca) | Dec 17, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [9b32bafcb5](https://linux-hardware.org/?probe=9b32bafcb5) | Dec 17, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [6d3774729f](https://linux-hardware.org/?probe=6d3774729f) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [24522df925](https://linux-hardware.org/?probe=24522df925) | Dec 16, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [528bd3903d](https://linux-hardware.org/?probe=528bd3903d) | Dec 16, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4a12bf0db8](https://linux-hardware.org/?probe=4a12bf0db8) | Dec 16, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [e93c46f2e9](https://linux-hardware.org/?probe=e93c46f2e9) | Dec 16, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [25eb2af58f](https://linux-hardware.org/?probe=25eb2af58f) | Dec 16, 2023 |
| Lenovo        | ThinkPad T410 2537AL8       | Notebook    | [8749a1d67d](https://linux-hardware.org/?probe=8749a1d67d) | Dec 16, 2023 |
| Lenovo        | ThinkPad T410 2537AL8       | Notebook    | [9e40928011](https://linux-hardware.org/?probe=9e40928011) | Dec 15, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5c1d3d831c](https://linux-hardware.org/?probe=5c1d3d831c) | Dec 15, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [08f10e4a70](https://linux-hardware.org/?probe=08f10e4a70) | Dec 15, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [106c5c6ec4](https://linux-hardware.org/?probe=106c5c6ec4) | Dec 15, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [7701847681](https://linux-hardware.org/?probe=7701847681) | Dec 15, 2023 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [470281aedd](https://linux-hardware.org/?probe=470281aedd) | Dec 15, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [89a318eaa6](https://linux-hardware.org/?probe=89a318eaa6) | Dec 14, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [1160e51426](https://linux-hardware.org/?probe=1160e51426) | Dec 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e40498b1d1](https://linux-hardware.org/?probe=e40498b1d1) | Dec 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [bb8a731dab](https://linux-hardware.org/?probe=bb8a731dab) | Dec 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9d0aff4b01](https://linux-hardware.org/?probe=9d0aff4b01) | Dec 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [02b6b32440](https://linux-hardware.org/?probe=02b6b32440) | Dec 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [016f269490](https://linux-hardware.org/?probe=016f269490) | Dec 13, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a3ef12171e](https://linux-hardware.org/?probe=a3ef12171e) | Dec 13, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3cfb1663a2](https://linux-hardware.org/?probe=3cfb1663a2) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [d55fed29c1](https://linux-hardware.org/?probe=d55fed29c1) | Dec 13, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [fc0fe04fab](https://linux-hardware.org/?probe=fc0fe04fab) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e196db2480](https://linux-hardware.org/?probe=e196db2480) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [00de2ee3d8](https://linux-hardware.org/?probe=00de2ee3d8) | Dec 12, 2023 |
| ASUSTek       | K51AE                       | Notebook    | [382bc13632](https://linux-hardware.org/?probe=382bc13632) | Dec 12, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [13c7114723](https://linux-hardware.org/?probe=13c7114723) | Dec 12, 2023 |
| HP            | 1495                        | Desktop     | [9fb4cb4ac8](https://linux-hardware.org/?probe=9fb4cb4ac8) | Dec 12, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [2199e3dc0f](https://linux-hardware.org/?probe=2199e3dc0f) | Dec 12, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [3184d3c38b](https://linux-hardware.org/?probe=3184d3c38b) | Dec 11, 2023 |
| HP            | 3033h                       | Desktop     | [3dddd6881a](https://linux-hardware.org/?probe=3dddd6881a) | Dec 11, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [446bcccc18](https://linux-hardware.org/?probe=446bcccc18) | Dec 11, 2023 |
| ASUSTek       | K54L                        | Notebook    | [a50a95f076](https://linux-hardware.org/?probe=a50a95f076) | Dec 11, 2023 |
| HP            | 802E                        | Desktop     | [606309324b](https://linux-hardware.org/?probe=606309324b) | Dec 11, 2023 |
| Dell          | Latitude 5480               | Notebook    | [cdc50c85ce](https://linux-hardware.org/?probe=cdc50c85ce) | Dec 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [853bcfa739](https://linux-hardware.org/?probe=853bcfa739) | Dec 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [354a9cc9b6](https://linux-hardware.org/?probe=354a9cc9b6) | Dec 10, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [5c9d12b2c0](https://linux-hardware.org/?probe=5c9d12b2c0) | Dec 10, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [5ad98ef7f6](https://linux-hardware.org/?probe=5ad98ef7f6) | Dec 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [4c72e88035](https://linux-hardware.org/?probe=4c72e88035) | Dec 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [9f822d68bb](https://linux-hardware.org/?probe=9f822d68bb) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [2c8df80a5f](https://linux-hardware.org/?probe=2c8df80a5f) | Dec 09, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [65223dfc53](https://linux-hardware.org/?probe=65223dfc53) | Dec 09, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [1b2d2135d4](https://linux-hardware.org/?probe=1b2d2135d4) | Dec 09, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [a319465535](https://linux-hardware.org/?probe=a319465535) | Dec 09, 2023 |
| eMachines     | E525                        | Notebook    | [0b83a89d59](https://linux-hardware.org/?probe=0b83a89d59) | Dec 09, 2023 |
| Dell          | Latitude 5480               | Notebook    | [0dd9110b39](https://linux-hardware.org/?probe=0dd9110b39) | Dec 09, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [bdff414c43](https://linux-hardware.org/?probe=bdff414c43) | Dec 09, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [a691f52012](https://linux-hardware.org/?probe=a691f52012) | Dec 08, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [aa3ae99bf2](https://linux-hardware.org/?probe=aa3ae99bf2) | Dec 08, 2023 |
| eMachines     | E725                        | Notebook    | [7c8234f296](https://linux-hardware.org/?probe=7c8234f296) | Dec 08, 2023 |
| HP            | Notebook                    | Notebook    | [4d688ddd0c](https://linux-hardware.org/?probe=4d688ddd0c) | Dec 08, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [0ce9d18c51](https://linux-hardware.org/?probe=0ce9d18c51) | Dec 08, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [6be53926db](https://linux-hardware.org/?probe=6be53926db) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [1c2750202f](https://linux-hardware.org/?probe=1c2750202f) | Dec 08, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [ba4f3255bc](https://linux-hardware.org/?probe=ba4f3255bc) | Dec 08, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [b848110f65](https://linux-hardware.org/?probe=b848110f65) | Dec 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae2fdd9470](https://linux-hardware.org/?probe=ae2fdd9470) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [dc50493c88](https://linux-hardware.org/?probe=dc50493c88) | Dec 08, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [9f5a520013](https://linux-hardware.org/?probe=9f5a520013) | Dec 08, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [82c95b312a](https://linux-hardware.org/?probe=82c95b312a) | Dec 07, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [a6f429594d](https://linux-hardware.org/?probe=a6f429594d) | Dec 07, 2023 |
| Dell          | 0TY565                      | Desktop     | [f037c10bc9](https://linux-hardware.org/?probe=f037c10bc9) | Dec 07, 2023 |
| HP            | 09F8h                       | Desktop     | [c988ff1e96](https://linux-hardware.org/?probe=c988ff1e96) | Dec 07, 2023 |
| MSI           | B460M PRO                   | Desktop     | [107b14c2d9](https://linux-hardware.org/?probe=107b14c2d9) | Dec 06, 2023 |
| Medion        | MS-7748                     | Desktop     | [1f11eab8f8](https://linux-hardware.org/?probe=1f11eab8f8) | Dec 06, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e9436c2809](https://linux-hardware.org/?probe=e9436c2809) | Dec 06, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ba710398bd](https://linux-hardware.org/?probe=ba710398bd) | Dec 06, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [2ebb7abc4c](https://linux-hardware.org/?probe=2ebb7abc4c) | Dec 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [d658b900e7](https://linux-hardware.org/?probe=d658b900e7) | Dec 05, 2023 |
| HP            | 1495                        | Desktop     | [626fcfb788](https://linux-hardware.org/?probe=626fcfb788) | Dec 05, 2023 |
| Medion        | MS-7748                     | Desktop     | [8c5106d00b](https://linux-hardware.org/?probe=8c5106d00b) | Dec 05, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [2d85fb4799](https://linux-hardware.org/?probe=2d85fb4799) | Dec 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [c72f209121](https://linux-hardware.org/?probe=c72f209121) | Dec 05, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [4389884ac0](https://linux-hardware.org/?probe=4389884ac0) | Dec 05, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [84cbb3e6b5](https://linux-hardware.org/?probe=84cbb3e6b5) | Dec 05, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [524de55da0](https://linux-hardware.org/?probe=524de55da0) | Dec 04, 2023 |
| HP            | 339A                        | Desktop     | [b596b82bf1](https://linux-hardware.org/?probe=b596b82bf1) | Dec 04, 2023 |
| Dell          | 0PU052                      | Desktop     | [a436be0e88](https://linux-hardware.org/?probe=a436be0e88) | Dec 04, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [5817017508](https://linux-hardware.org/?probe=5817017508) | Dec 04, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [1bf52989ef](https://linux-hardware.org/?probe=1bf52989ef) | Dec 03, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [77472c25c8](https://linux-hardware.org/?probe=77472c25c8) | Dec 03, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [e21f4b08b1](https://linux-hardware.org/?probe=e21f4b08b1) | Dec 03, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [5726a3acac](https://linux-hardware.org/?probe=5726a3acac) | Dec 03, 2023 |
| Dell          | Latitude E6230              | Notebook    | [4c2a286dd8](https://linux-hardware.org/?probe=4c2a286dd8) | Dec 03, 2023 |
| Dell          | Latitude E6230              | Notebook    | [6ac9013399](https://linux-hardware.org/?probe=6ac9013399) | Dec 03, 2023 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [3f49a16307](https://linux-hardware.org/?probe=3f49a16307) | Dec 02, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [62cff9080d](https://linux-hardware.org/?probe=62cff9080d) | Dec 02, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [f41b4f3bd4](https://linux-hardware.org/?probe=f41b4f3bd4) | Dec 02, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [fc1e5f26f3](https://linux-hardware.org/?probe=fc1e5f26f3) | Dec 02, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [5f4856fdab](https://linux-hardware.org/?probe=5f4856fdab) | Dec 01, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [0ae66633bc](https://linux-hardware.org/?probe=0ae66633bc) | Dec 01, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [b70c84adcf](https://linux-hardware.org/?probe=b70c84adcf) | Dec 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [71ecd72ded](https://linux-hardware.org/?probe=71ecd72ded) | Dec 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [dd5b07ee50](https://linux-hardware.org/?probe=dd5b07ee50) | Dec 01, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [6578e9c195](https://linux-hardware.org/?probe=6578e9c195) | Dec 01, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [116d65dc76](https://linux-hardware.org/?probe=116d65dc76) | Dec 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [49c6f0b57f](https://linux-hardware.org/?probe=49c6f0b57f) | Dec 01, 2023 |
| Blue Bird     | Bluebird PC                 | Tablet      | [efcf788f14](https://linux-hardware.org/?probe=efcf788f14) | Nov 30, 2023 |
| Acer          | Aspire V5-591G              | Notebook    | [fcb901f377](https://linux-hardware.org/?probe=fcb901f377) | Nov 30, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [ff4348f86f](https://linux-hardware.org/?probe=ff4348f86f) | Nov 30, 2023 |
| HP            | 620                         | Notebook    | [3b69da88c5](https://linux-hardware.org/?probe=3b69da88c5) | Nov 30, 2023 |
| Dell          | Latitude E5470              | Notebook    | [7b9aba2d2c](https://linux-hardware.org/?probe=7b9aba2d2c) | Nov 30, 2023 |
| Dell          | Latitude E5470              | Notebook    | [83a0b4f237](https://linux-hardware.org/?probe=83a0b4f237) | Nov 30, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [dab859b1f5](https://linux-hardware.org/?probe=dab859b1f5) | Nov 30, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [6115cb75f9](https://linux-hardware.org/?probe=6115cb75f9) | Nov 30, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [9eab855ea7](https://linux-hardware.org/?probe=9eab855ea7) | Nov 30, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [cdfe1883bc](https://linux-hardware.org/?probe=cdfe1883bc) | Nov 30, 2023 |
| HP            | 18E7                        | Desktop     | [845881d2cd](https://linux-hardware.org/?probe=845881d2cd) | Nov 30, 2023 |
| HP            | 18E7                        | Desktop     | [f09d697221](https://linux-hardware.org/?probe=f09d697221) | Nov 30, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [ca91d466bf](https://linux-hardware.org/?probe=ca91d466bf) | Nov 29, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [2ad6007c7f](https://linux-hardware.org/?probe=2ad6007c7f) | Nov 29, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [c0e81cdc2c](https://linux-hardware.org/?probe=c0e81cdc2c) | Nov 29, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [1d9149c4e9](https://linux-hardware.org/?probe=1d9149c4e9) | Nov 28, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [5f18814bd9](https://linux-hardware.org/?probe=5f18814bd9) | Nov 28, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | Notebook    | [ce03712596](https://linux-hardware.org/?probe=ce03712596) | Nov 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [18ce09355c](https://linux-hardware.org/?probe=18ce09355c) | Nov 28, 2023 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [b3de42156e](https://linux-hardware.org/?probe=b3de42156e) | Nov 28, 2023 |
| HP            | Presario CQ57               | Notebook    | [d8178138ad](https://linux-hardware.org/?probe=d8178138ad) | Nov 28, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [d75b3fd958](https://linux-hardware.org/?probe=d75b3fd958) | Nov 28, 2023 |
| HP            | 250 G1                      | Notebook    | [01e4d8a87b](https://linux-hardware.org/?probe=01e4d8a87b) | Nov 28, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [988c87ee59](https://linux-hardware.org/?probe=988c87ee59) | Nov 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [875f72f0f7](https://linux-hardware.org/?probe=875f72f0f7) | Nov 28, 2023 |
| HP            | 1495                        | Desktop     | [17732cf790](https://linux-hardware.org/?probe=17732cf790) | Nov 28, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [d5440204b6](https://linux-hardware.org/?probe=d5440204b6) | Nov 28, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [05686c86bb](https://linux-hardware.org/?probe=05686c86bb) | Nov 28, 2023 |
| eMachines     | E725                        | Notebook    | [5035b9380f](https://linux-hardware.org/?probe=5035b9380f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ee62c7d97a](https://linux-hardware.org/?probe=ee62c7d97a) | Nov 28, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [b67bf4064d](https://linux-hardware.org/?probe=b67bf4064d) | Nov 28, 2023 |
| HP            | 620                         | Notebook    | [80b7a22522](https://linux-hardware.org/?probe=80b7a22522) | Nov 28, 2023 |
| MSI           | P43i                        | Desktop     | [3291b84f5e](https://linux-hardware.org/?probe=3291b84f5e) | Nov 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [5e1e9b6a9e](https://linux-hardware.org/?probe=5e1e9b6a9e) | Nov 27, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [ada0d60fb5](https://linux-hardware.org/?probe=ada0d60fb5) | Nov 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [77e8b3479a](https://linux-hardware.org/?probe=77e8b3479a) | Nov 27, 2023 |
| MSI           | CR620                       | Notebook    | [336d403e1b](https://linux-hardware.org/?probe=336d403e1b) | Nov 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cd7362b85e](https://linux-hardware.org/?probe=cd7362b85e) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [159ce7eba2](https://linux-hardware.org/?probe=159ce7eba2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | Notebook    | [f6574b2aaa](https://linux-hardware.org/?probe=f6574b2aaa) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [bfc194ba14](https://linux-hardware.org/?probe=bfc194ba14) | Nov 27, 2023 |
| ASRock        | B85M                        | Desktop     | [0d3f6ceeea](https://linux-hardware.org/?probe=0d3f6ceeea) | Nov 27, 2023 |
| HP            | 250 G1                      | Notebook    | [16a3ccd98e](https://linux-hardware.org/?probe=16a3ccd98e) | Nov 27, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [d828fc6b62](https://linux-hardware.org/?probe=d828fc6b62) | Nov 27, 2023 |
| MSI           | H61M-P21                    | Desktop     | [5c106c49f4](https://linux-hardware.org/?probe=5c106c49f4) | Nov 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [1e0fa8c965](https://linux-hardware.org/?probe=1e0fa8c965) | Nov 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [a83678b03b](https://linux-hardware.org/?probe=a83678b03b) | Nov 27, 2023 |
| eMachines     | E725                        | Notebook    | [fd646483cd](https://linux-hardware.org/?probe=fd646483cd) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [bb7da237ac](https://linux-hardware.org/?probe=bb7da237ac) | Nov 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [0da1cb9f68](https://linux-hardware.org/?probe=0da1cb9f68) | Nov 26, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [c9dd5240c4](https://linux-hardware.org/?probe=c9dd5240c4) | Nov 26, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [4618c61b6c](https://linux-hardware.org/?probe=4618c61b6c) | Nov 26, 2023 |
| HP            | 250 G1                      | Notebook    | [1d14f29955](https://linux-hardware.org/?probe=1d14f29955) | Nov 26, 2023 |
| Dell          | Latitude 5480               | Notebook    | [748c349ec3](https://linux-hardware.org/?probe=748c349ec3) | Nov 26, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [4ded3f7409](https://linux-hardware.org/?probe=4ded3f7409) | Nov 26, 2023 |
| Dell          | Latitude 7390               | Notebook    | [b68d99c176](https://linux-hardware.org/?probe=b68d99c176) | Nov 26, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [c2e61e0cf9](https://linux-hardware.org/?probe=c2e61e0cf9) | Nov 26, 2023 |
| ASUSTek       | X55U                        | Notebook    | [ba9269363a](https://linux-hardware.org/?probe=ba9269363a) | Nov 26, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [200ddef2b0](https://linux-hardware.org/?probe=200ddef2b0) | Nov 26, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [250bd9f1df](https://linux-hardware.org/?probe=250bd9f1df) | Nov 26, 2023 |
| HP            | 650                         | Notebook    | [00a115705f](https://linux-hardware.org/?probe=00a115705f) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [78b8e2f560](https://linux-hardware.org/?probe=78b8e2f560) | Nov 26, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [557aba57b5](https://linux-hardware.org/?probe=557aba57b5) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [332eec50ca](https://linux-hardware.org/?probe=332eec50ca) | Nov 26, 2023 |
| ASRock        | B365 Phantom Gaming 4       | Desktop     | [97dfb05d56](https://linux-hardware.org/?probe=97dfb05d56) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [189d6b3a6f](https://linux-hardware.org/?probe=189d6b3a6f) | Nov 25, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | Notebook    | [3b6eaf2c6e](https://linux-hardware.org/?probe=3b6eaf2c6e) | Nov 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [3e59300230](https://linux-hardware.org/?probe=3e59300230) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | Desktop     | [61b5003420](https://linux-hardware.org/?probe=61b5003420) | Nov 25, 2023 |
| HP            | 339A                        | Desktop     | [35c70dde9e](https://linux-hardware.org/?probe=35c70dde9e) | Nov 25, 2023 |
| Lenovo        | ThinkCentre M58 9960ALU     | Desktop     | [c02d4a69b7](https://linux-hardware.org/?probe=c02d4a69b7) | Nov 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [efa6660bf5](https://linux-hardware.org/?probe=efa6660bf5) | Nov 25, 2023 |
| ASUSTek       | X55U                        | Notebook    | [02daf65c45](https://linux-hardware.org/?probe=02daf65c45) | Nov 24, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [04b5574c35](https://linux-hardware.org/?probe=04b5574c35) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [86b63c1acf](https://linux-hardware.org/?probe=86b63c1acf) | Nov 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [8c071d6cda](https://linux-hardware.org/?probe=8c071d6cda) | Nov 24, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [4a05411844](https://linux-hardware.org/?probe=4a05411844) | Nov 24, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [74b3fd6470](https://linux-hardware.org/?probe=74b3fd6470) | Nov 24, 2023 |
| Dell          | Latitude E6220              | Notebook    | [c252669c37](https://linux-hardware.org/?probe=c252669c37) | Nov 24, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [5d6b4323e5](https://linux-hardware.org/?probe=5d6b4323e5) | Nov 24, 2023 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [c66c77566e](https://linux-hardware.org/?probe=c66c77566e) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [cbdb153211](https://linux-hardware.org/?probe=cbdb153211) | Nov 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [73f8815e36](https://linux-hardware.org/?probe=73f8815e36) | Nov 24, 2023 |
| Sony          | SVS13118GBB                 | Notebook    | [2eb3722ea1](https://linux-hardware.org/?probe=2eb3722ea1) | Nov 24, 2023 |
| Sony          | SVS13118GBB                 | Notebook    | [65ac45c622](https://linux-hardware.org/?probe=65ac45c622) | Nov 24, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | Desktop     | [aed927ecb5](https://linux-hardware.org/?probe=aed927ecb5) | Nov 24, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [cdd0c24ab1](https://linux-hardware.org/?probe=cdd0c24ab1) | Nov 23, 2023 |
| HP            | Notebook                    | Notebook    | [a4488a0c34](https://linux-hardware.org/?probe=a4488a0c34) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fd89a2eed5](https://linux-hardware.org/?probe=fd89a2eed5) | Nov 23, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [977d9e09f1](https://linux-hardware.org/?probe=977d9e09f1) | Nov 23, 2023 |
| Dell          | Latitude E5520              | Notebook    | [603704ca41](https://linux-hardware.org/?probe=603704ca41) | Nov 23, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [b99f6e4f94](https://linux-hardware.org/?probe=b99f6e4f94) | Nov 23, 2023 |
| HP            | 1494                        | Desktop     | [3ff4bec1f2](https://linux-hardware.org/?probe=3ff4bec1f2) | Nov 23, 2023 |
| HP            | 1495                        | Desktop     | [630e59993e](https://linux-hardware.org/?probe=630e59993e) | Nov 23, 2023 |
| HP            | Presario CQ57               | Notebook    | [1aaa046b20](https://linux-hardware.org/?probe=1aaa046b20) | Nov 22, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [ce2d61136c](https://linux-hardware.org/?probe=ce2d61136c) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [3e89253fa2](https://linux-hardware.org/?probe=3e89253fa2) | Nov 22, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [9d2f710119](https://linux-hardware.org/?probe=9d2f710119) | Nov 22, 2023 |
| Dell          | 0TY565                      | Desktop     | [bf643a514f](https://linux-hardware.org/?probe=bf643a514f) | Nov 22, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [c5551bb38d](https://linux-hardware.org/?probe=c5551bb38d) | Nov 22, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [667c79209d](https://linux-hardware.org/?probe=667c79209d) | Nov 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7c048e0f1a](https://linux-hardware.org/?probe=7c048e0f1a) | Nov 21, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [feccf655c5](https://linux-hardware.org/?probe=feccf655c5) | Nov 21, 2023 |
| ASUSTek       | X540NV                      | Notebook    | [c4d533ed88](https://linux-hardware.org/?probe=c4d533ed88) | Nov 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [c34bec8c5f](https://linux-hardware.org/?probe=c34bec8c5f) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [32e985afeb](https://linux-hardware.org/?probe=32e985afeb) | Nov 21, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [d2a213e349](https://linux-hardware.org/?probe=d2a213e349) | Nov 21, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [2964062ee1](https://linux-hardware.org/?probe=2964062ee1) | Nov 21, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [d5cdc3089f](https://linux-hardware.org/?probe=d5cdc3089f) | Nov 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [91a346655b](https://linux-hardware.org/?probe=91a346655b) | Nov 21, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [e1e3a4bb80](https://linux-hardware.org/?probe=e1e3a4bb80) | Nov 20, 2023 |
| Dell          | 0XPDFK A00                  | Desktop     | [280e97cc34](https://linux-hardware.org/?probe=280e97cc34) | Nov 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C4S... | Notebook    | [e5d9227cf4](https://linux-hardware.org/?probe=e5d9227cf4) | Nov 20, 2023 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [7920ff517f](https://linux-hardware.org/?probe=7920ff517f) | Nov 20, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6269fd26e0](https://linux-hardware.org/?probe=6269fd26e0) | Nov 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6a2ddf8e53](https://linux-hardware.org/?probe=6a2ddf8e53) | Nov 19, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [d17022be69](https://linux-hardware.org/?probe=d17022be69) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [08f1313c20](https://linux-hardware.org/?probe=08f1313c20) | Nov 19, 2023 |
| Intel         | S5500HCV E40912-458         | Server      | [4a100d6164](https://linux-hardware.org/?probe=4a100d6164) | Nov 19, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [488ac4cac6](https://linux-hardware.org/?probe=488ac4cac6) | Nov 18, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [cbdd99c4fc](https://linux-hardware.org/?probe=cbdd99c4fc) | Nov 18, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [d086db0563](https://linux-hardware.org/?probe=d086db0563) | Nov 18, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [f73e299a89](https://linux-hardware.org/?probe=f73e299a89) | Nov 18, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [7b41cb7d1e](https://linux-hardware.org/?probe=7b41cb7d1e) | Nov 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [82eedfb8be](https://linux-hardware.org/?probe=82eedfb8be) | Nov 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c00a7584bf](https://linux-hardware.org/?probe=c00a7584bf) | Nov 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [dbf835efbb](https://linux-hardware.org/?probe=dbf835efbb) | Nov 17, 2023 |
| Lenovo        | ThinkPad X220 4290KV8       | Notebook    | [cb34220afb](https://linux-hardware.org/?probe=cb34220afb) | Nov 17, 2023 |
| Dell          | Latitude E6230              | Notebook    | [230d462f11](https://linux-hardware.org/?probe=230d462f11) | Nov 17, 2023 |
| Dell          | Latitude E6230              | Notebook    | [0e87890c4c](https://linux-hardware.org/?probe=0e87890c4c) | Nov 17, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [2c22b9f725](https://linux-hardware.org/?probe=2c22b9f725) | Nov 16, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [795b0f6741](https://linux-hardware.org/?probe=795b0f6741) | Nov 16, 2023 |
| Dell          | 0TY565                      | Desktop     | [bd5ec5457e](https://linux-hardware.org/?probe=bd5ec5457e) | Nov 16, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [4b06d87b96](https://linux-hardware.org/?probe=4b06d87b96) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [373b5a5156](https://linux-hardware.org/?probe=373b5a5156) | Nov 15, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [c79a431698](https://linux-hardware.org/?probe=c79a431698) | Nov 15, 2023 |
| Dell          | 05WXFV A03                  | Desktop     | [ecab18e943](https://linux-hardware.org/?probe=ecab18e943) | Nov 14, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [55665c76e2](https://linux-hardware.org/?probe=55665c76e2) | Nov 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [39186e5754](https://linux-hardware.org/?probe=39186e5754) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [22c504ad97](https://linux-hardware.org/?probe=22c504ad97) | Nov 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [aa66857d17](https://linux-hardware.org/?probe=aa66857d17) | Nov 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [d5cb68f63d](https://linux-hardware.org/?probe=d5cb68f63d) | Nov 12, 2023 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [134168eaaf](https://linux-hardware.org/?probe=134168eaaf) | Nov 12, 2023 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [15fa930dc4](https://linux-hardware.org/?probe=15fa930dc4) | Nov 12, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [2f9f860b8f](https://linux-hardware.org/?probe=2f9f860b8f) | Nov 12, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [84d60633b1](https://linux-hardware.org/?probe=84d60633b1) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [988c1c2454](https://linux-hardware.org/?probe=988c1c2454) | Nov 12, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [bf78e4de12](https://linux-hardware.org/?probe=bf78e4de12) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [9aa30be183](https://linux-hardware.org/?probe=9aa30be183) | Nov 12, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4d1bb1f947](https://linux-hardware.org/?probe=4d1bb1f947) | Nov 11, 2023 |
| Dell          | Latitude 3540               | Notebook    | [a28b72369b](https://linux-hardware.org/?probe=a28b72369b) | Nov 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [8ab7ca4fa6](https://linux-hardware.org/?probe=8ab7ca4fa6) | Nov 11, 2023 |
| Dell          | Latitude E6520              | Notebook    | [ecbec01a36](https://linux-hardware.org/?probe=ecbec01a36) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [85c42caa7f](https://linux-hardware.org/?probe=85c42caa7f) | Nov 11, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [6de94ed555](https://linux-hardware.org/?probe=6de94ed555) | Nov 11, 2023 |
| Teclast       | F6 Pro                      | Notebook    | [81d39ab601](https://linux-hardware.org/?probe=81d39ab601) | Nov 11, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [543d2a5108](https://linux-hardware.org/?probe=543d2a5108) | Nov 11, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [dbd9eda227](https://linux-hardware.org/?probe=dbd9eda227) | Nov 10, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [e02cd94d67](https://linux-hardware.org/?probe=e02cd94d67) | Nov 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [e55b3ab6db](https://linux-hardware.org/?probe=e55b3ab6db) | Nov 10, 2023 |
| Lenovo        | ThinkPad E470 20H1006NHV    | Notebook    | [a43db58ab7](https://linux-hardware.org/?probe=a43db58ab7) | Nov 10, 2023 |
| Lenovo        | ThinkPad T480s 20L7001MH... | Notebook    | [f5c3846dce](https://linux-hardware.org/?probe=f5c3846dce) | Nov 10, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [a1ba3b47c2](https://linux-hardware.org/?probe=a1ba3b47c2) | Nov 10, 2023 |
| MSI           | H81M-E33                    | Desktop     | [2a5463be7c](https://linux-hardware.org/?probe=2a5463be7c) | Nov 10, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [b6ce2c01d3](https://linux-hardware.org/?probe=b6ce2c01d3) | Nov 10, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [2106c14823](https://linux-hardware.org/?probe=2106c14823) | Nov 10, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [ce2c43cb86](https://linux-hardware.org/?probe=ce2c43cb86) | Nov 10, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [f45397a161](https://linux-hardware.org/?probe=f45397a161) | Nov 09, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [8dda111b6a](https://linux-hardware.org/?probe=8dda111b6a) | Nov 09, 2023 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [5e0d19391e](https://linux-hardware.org/?probe=5e0d19391e) | Nov 09, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [1399a1f267](https://linux-hardware.org/?probe=1399a1f267) | Nov 09, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [7cdb83cd7a](https://linux-hardware.org/?probe=7cdb83cd7a) | Nov 09, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [d67c8b1bbc](https://linux-hardware.org/?probe=d67c8b1bbc) | Nov 09, 2023 |
| Medion        | E7220                       | Notebook    | [2a13846d8f](https://linux-hardware.org/?probe=2a13846d8f) | Nov 09, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [4c8dc5f59a](https://linux-hardware.org/?probe=4c8dc5f59a) | Nov 08, 2023 |
| Medion        | E7220                       | Notebook    | [f0e0b97ea6](https://linux-hardware.org/?probe=f0e0b97ea6) | Nov 08, 2023 |
| Gigabyte      | Z97MX-Gaming 5              | Desktop     | [420d0d1ddc](https://linux-hardware.org/?probe=420d0d1ddc) | Nov 08, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [e475e8c7d9](https://linux-hardware.org/?probe=e475e8c7d9) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a48d1ad818](https://linux-hardware.org/?probe=a48d1ad818) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [b8a00231d6](https://linux-hardware.org/?probe=b8a00231d6) | Nov 08, 2023 |
| Dell          | Latitude D520               | Notebook    | [de71d8ccf8](https://linux-hardware.org/?probe=de71d8ccf8) | Nov 08, 2023 |
| Dell          | Latitude D520               | Notebook    | [5beff5a82d](https://linux-hardware.org/?probe=5beff5a82d) | Nov 08, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [396f92d0c1](https://linux-hardware.org/?probe=396f92d0c1) | Nov 08, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [f4ca40f3c9](https://linux-hardware.org/?probe=f4ca40f3c9) | Nov 08, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [ae88c578fa](https://linux-hardware.org/?probe=ae88c578fa) | Nov 08, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [9c7020c9cc](https://linux-hardware.org/?probe=9c7020c9cc) | Nov 08, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [72a7ba6dde](https://linux-hardware.org/?probe=72a7ba6dde) | Nov 08, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [02f177cbd8](https://linux-hardware.org/?probe=02f177cbd8) | Nov 08, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [813b0c06e0](https://linux-hardware.org/?probe=813b0c06e0) | Nov 08, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [eecf9896e7](https://linux-hardware.org/?probe=eecf9896e7) | Nov 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [a8792eb2aa](https://linux-hardware.org/?probe=a8792eb2aa) | Nov 07, 2023 |
| Acer          | Aspire 7738                 | Notebook    | [06df3c94e1](https://linux-hardware.org/?probe=06df3c94e1) | Nov 07, 2023 |
| HP            | HDX 16                      | Notebook    | [faeb7886e4](https://linux-hardware.org/?probe=faeb7886e4) | Nov 07, 2023 |
| HP            | HDX 16                      | Notebook    | [321b191f5f](https://linux-hardware.org/?probe=321b191f5f) | Nov 07, 2023 |
| Dell          | Latitude 5540               | Notebook    | [9ff5e6f1e6](https://linux-hardware.org/?probe=9ff5e6f1e6) | Nov 07, 2023 |
| Dell          | 0TY565                      | Desktop     | [086bd4ec8f](https://linux-hardware.org/?probe=086bd4ec8f) | Nov 06, 2023 |
| Lenovo        | ThinkPad E14 20RA002UHV     | Notebook    | [79a037e80b](https://linux-hardware.org/?probe=79a037e80b) | Nov 06, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [6e0b8b9df9](https://linux-hardware.org/?probe=6e0b8b9df9) | Nov 06, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c4d9d2cd13](https://linux-hardware.org/?probe=c4d9d2cd13) | Nov 06, 2023 |
| Dell          | Latitude E6410              | Notebook    | [ebdd852a85](https://linux-hardware.org/?probe=ebdd852a85) | Nov 05, 2023 |
| Dell          | Latitude D520               | Notebook    | [99c85f2153](https://linux-hardware.org/?probe=99c85f2153) | Nov 05, 2023 |
| Dell          | Latitude D520               | Notebook    | [d56819f452](https://linux-hardware.org/?probe=d56819f452) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [038e8719ec](https://linux-hardware.org/?probe=038e8719ec) | Nov 05, 2023 |
| HP            | 650                         | Notebook    | [5b72d0e471](https://linux-hardware.org/?probe=5b72d0e471) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [1e59a67f24](https://linux-hardware.org/?probe=1e59a67f24) | Nov 05, 2023 |
| Medion        | E7220                       | Notebook    | [a8643a8082](https://linux-hardware.org/?probe=a8643a8082) | Nov 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b1c2db4297](https://linux-hardware.org/?probe=b1c2db4297) | Nov 05, 2023 |
| Medion        | E7220                       | Notebook    | [f093abab73](https://linux-hardware.org/?probe=f093abab73) | Nov 05, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a424739d4f](https://linux-hardware.org/?probe=a424739d4f) | Nov 05, 2023 |
| HP            | Pavilion dv5                | Notebook    | [6a122b29a9](https://linux-hardware.org/?probe=6a122b29a9) | Nov 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [a9f0b015d5](https://linux-hardware.org/?probe=a9f0b015d5) | Nov 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [08d79042a7](https://linux-hardware.org/?probe=08d79042a7) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [d11250217c](https://linux-hardware.org/?probe=d11250217c) | Nov 04, 2023 |
| HP            | 650                         | Notebook    | [c472e54502](https://linux-hardware.org/?probe=c472e54502) | Nov 04, 2023 |
| ASUSTek       | K53U                        | Notebook    | [eb44961984](https://linux-hardware.org/?probe=eb44961984) | Nov 04, 2023 |
| HP            | 8265                        | Desktop     | [f6b38e869b](https://linux-hardware.org/?probe=f6b38e869b) | Nov 04, 2023 |
| HP            | 8265                        | Desktop     | [49cb61db2e](https://linux-hardware.org/?probe=49cb61db2e) | Nov 04, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [f36f4e888c](https://linux-hardware.org/?probe=f36f4e888c) | Nov 04, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [7663b608dd](https://linux-hardware.org/?probe=7663b608dd) | Nov 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [3b14b40bc9](https://linux-hardware.org/?probe=3b14b40bc9) | Nov 02, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [41d5ec4633](https://linux-hardware.org/?probe=41d5ec4633) | Nov 02, 2023 |
| Lenovo        | Annapurna CRB 0B98401 PR... | Desktop     | [dacdb79776](https://linux-hardware.org/?probe=dacdb79776) | Nov 01, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [3d5b8068af](https://linux-hardware.org/?probe=3d5b8068af) | Nov 01, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [135443bd2d](https://linux-hardware.org/?probe=135443bd2d) | Nov 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [877ab8782b](https://linux-hardware.org/?probe=877ab8782b) | Nov 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f8a1a5a5fa](https://linux-hardware.org/?probe=f8a1a5a5fa) | Nov 01, 2023 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [0a33a8b925](https://linux-hardware.org/?probe=0a33a8b925) | Nov 01, 2023 |
| MSI           | P43i                        | Desktop     | [847f1890e2](https://linux-hardware.org/?probe=847f1890e2) | Nov 01, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [ad5e8f91e5](https://linux-hardware.org/?probe=ad5e8f91e5) | Nov 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c0617fe23d](https://linux-hardware.org/?probe=c0617fe23d) | Nov 01, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [1d5b98622d](https://linux-hardware.org/?probe=1d5b98622d) | Oct 31, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [1a0da2bf85](https://linux-hardware.org/?probe=1a0da2bf85) | Oct 31, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [5f6ce5dbfb](https://linux-hardware.org/?probe=5f6ce5dbfb) | Oct 31, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUA... | Notebook    | [701a08bdb6](https://linux-hardware.org/?probe=701a08bdb6) | Oct 31, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [a6c79e3211](https://linux-hardware.org/?probe=a6c79e3211) | Oct 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [9749e20de1](https://linux-hardware.org/?probe=9749e20de1) | Oct 31, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [2327e785db](https://linux-hardware.org/?probe=2327e785db) | Oct 31, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | Desktop     | [4cf4e845eb](https://linux-hardware.org/?probe=4cf4e845eb) | Oct 30, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b1394cc278](https://linux-hardware.org/?probe=b1394cc278) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [1813899897](https://linux-hardware.org/?probe=1813899897) | Oct 30, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [6cf499a771](https://linux-hardware.org/?probe=6cf499a771) | Oct 30, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [bc3acc8006](https://linux-hardware.org/?probe=bc3acc8006) | Oct 30, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [abd35a7e37](https://linux-hardware.org/?probe=abd35a7e37) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | Desktop     | [2a5fda7baf](https://linux-hardware.org/?probe=2a5fda7baf) | Oct 30, 2023 |
| Lenovo        | 1730-A1G                    | Desktop     | [7d99dba1af](https://linux-hardware.org/?probe=7d99dba1af) | Oct 30, 2023 |
| HP            | Notebook                    | Notebook    | [dae22f458b](https://linux-hardware.org/?probe=dae22f458b) | Oct 30, 2023 |
| HP            | Notebook                    | Notebook    | [373777c65a](https://linux-hardware.org/?probe=373777c65a) | Oct 30, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [b48b015b4c](https://linux-hardware.org/?probe=b48b015b4c) | Oct 29, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [9902963d1d](https://linux-hardware.org/?probe=9902963d1d) | Oct 29, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [39c5db1614](https://linux-hardware.org/?probe=39c5db1614) | Oct 29, 2023 |
| ASRock        | AM1B-M                      | Desktop     | [098a155bab](https://linux-hardware.org/?probe=098a155bab) | Oct 29, 2023 |
| Lenovo        | ThinkPad X250 20CMS04J00    | Notebook    | [773098b9e5](https://linux-hardware.org/?probe=773098b9e5) | Oct 29, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [85e507b8b2](https://linux-hardware.org/?probe=85e507b8b2) | Oct 29, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [de8470b056](https://linux-hardware.org/?probe=de8470b056) | Oct 29, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [f3fe5293ae](https://linux-hardware.org/?probe=f3fe5293ae) | Oct 29, 2023 |
| ASUSTek       | K54C                        | Notebook    | [d36a0a583b](https://linux-hardware.org/?probe=d36a0a583b) | Oct 29, 2023 |
| Lenovo        | ThinkPad T420 4236W1Y       | Notebook    | [2ff5cba7a7](https://linux-hardware.org/?probe=2ff5cba7a7) | Oct 29, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [db205eed37](https://linux-hardware.org/?probe=db205eed37) | Oct 29, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [5d047c6d80](https://linux-hardware.org/?probe=5d047c6d80) | Oct 28, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [67aa25e9ff](https://linux-hardware.org/?probe=67aa25e9ff) | Oct 28, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [27d90e68ae](https://linux-hardware.org/?probe=27d90e68ae) | Oct 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [2c3cefb71a](https://linux-hardware.org/?probe=2c3cefb71a) | Oct 28, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [feabc7e111](https://linux-hardware.org/?probe=feabc7e111) | Oct 28, 2023 |
| ASUSTek       | X101                        | Notebook    | [dab1a6368d](https://linux-hardware.org/?probe=dab1a6368d) | Oct 27, 2023 |
| MSI           | MS-7817                     | Desktop     | [06344ac320](https://linux-hardware.org/?probe=06344ac320) | Oct 27, 2023 |
| MSI           | MS-7817                     | Desktop     | [dc9cc99096](https://linux-hardware.org/?probe=dc9cc99096) | Oct 27, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5d60a750af](https://linux-hardware.org/?probe=5d60a750af) | Oct 27, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [6ca7ed2683](https://linux-hardware.org/?probe=6ca7ed2683) | Oct 27, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0306fca319](https://linux-hardware.org/?probe=0306fca319) | Oct 27, 2023 |
| HP            | HDX 16                      | Notebook    | [e2c3147b80](https://linux-hardware.org/?probe=e2c3147b80) | Oct 27, 2023 |
| Dell          | Latitude 3590               | Notebook    | [2d288fa42e](https://linux-hardware.org/?probe=2d288fa42e) | Oct 27, 2023 |
| HP            | HDX 16                      | Notebook    | [9ec532aa3c](https://linux-hardware.org/?probe=9ec532aa3c) | Oct 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [181d68d988](https://linux-hardware.org/?probe=181d68d988) | Oct 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [200d747791](https://linux-hardware.org/?probe=200d747791) | Oct 27, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [efe15b2600](https://linux-hardware.org/?probe=efe15b2600) | Oct 26, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [9d4b52edfe](https://linux-hardware.org/?probe=9d4b52edfe) | Oct 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [b58a3b7e3a](https://linux-hardware.org/?probe=b58a3b7e3a) | Oct 26, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [220d49592e](https://linux-hardware.org/?probe=220d49592e) | Oct 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [5e16db7192](https://linux-hardware.org/?probe=5e16db7192) | Oct 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [a2731cd16e](https://linux-hardware.org/?probe=a2731cd16e) | Oct 26, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [64693f6b03](https://linux-hardware.org/?probe=64693f6b03) | Oct 26, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [7a96d2e495](https://linux-hardware.org/?probe=7a96d2e495) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [f6b735de42](https://linux-hardware.org/?probe=f6b735de42) | Oct 25, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [676f3b81ce](https://linux-hardware.org/?probe=676f3b81ce) | Oct 25, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [828dbad92c](https://linux-hardware.org/?probe=828dbad92c) | Oct 25, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4bc0dc73b1](https://linux-hardware.org/?probe=4bc0dc73b1) | Oct 25, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | Desktop     | [4f6c606196](https://linux-hardware.org/?probe=4f6c606196) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7e2c80a1d7](https://linux-hardware.org/?probe=7e2c80a1d7) | Oct 24, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [3deed5f633](https://linux-hardware.org/?probe=3deed5f633) | Oct 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [410e22edf0](https://linux-hardware.org/?probe=410e22edf0) | Oct 24, 2023 |
| HP            | 339A                        | Desktop     | [119fec0a9d](https://linux-hardware.org/?probe=119fec0a9d) | Oct 24, 2023 |
| HP            | 339A                        | Desktop     | [b35bc69c82](https://linux-hardware.org/?probe=b35bc69c82) | Oct 24, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [50bdbf100d](https://linux-hardware.org/?probe=50bdbf100d) | Oct 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3824135292](https://linux-hardware.org/?probe=3824135292) | Oct 23, 2023 |
| Gigabyte      | F2A88XN-WIFI                | Desktop     | [875d62cbac](https://linux-hardware.org/?probe=875d62cbac) | Oct 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b838b1d016](https://linux-hardware.org/?probe=b838b1d016) | Oct 23, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b834df3a83](https://linux-hardware.org/?probe=b834df3a83) | Oct 23, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [a62011100d](https://linux-hardware.org/?probe=a62011100d) | Oct 23, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [86dc35496a](https://linux-hardware.org/?probe=86dc35496a) | Oct 23, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [d1f12415b9](https://linux-hardware.org/?probe=d1f12415b9) | Oct 23, 2023 |
| HP            | Notebook                    | Notebook    | [d06318071f](https://linux-hardware.org/?probe=d06318071f) | Oct 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2ae3b33ae8](https://linux-hardware.org/?probe=2ae3b33ae8) | Oct 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [5f54128707](https://linux-hardware.org/?probe=5f54128707) | Oct 22, 2023 |
| Dell          | Latitude E6540              | Notebook    | [5249645843](https://linux-hardware.org/?probe=5249645843) | Oct 22, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [e681e567ad](https://linux-hardware.org/?probe=e681e567ad) | Oct 22, 2023 |
| HP            | Pavilion 17                 | Notebook    | [f72b1f8c83](https://linux-hardware.org/?probe=f72b1f8c83) | Oct 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [3eafc2c647](https://linux-hardware.org/?probe=3eafc2c647) | Oct 21, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [3543df08ee](https://linux-hardware.org/?probe=3543df08ee) | Oct 21, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [79d3058ad1](https://linux-hardware.org/?probe=79d3058ad1) | Oct 21, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [f687230e43](https://linux-hardware.org/?probe=f687230e43) | Oct 21, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [0d9d598232](https://linux-hardware.org/?probe=0d9d598232) | Oct 21, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [b5bf9b7639](https://linux-hardware.org/?probe=b5bf9b7639) | Oct 21, 2023 |
| Lenovo        | ThinkPad X201 3680V5T       | Notebook    | [b30e261022](https://linux-hardware.org/?probe=b30e261022) | Oct 20, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [d3036ca319](https://linux-hardware.org/?probe=d3036ca319) | Oct 20, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | Notebook    | [6e43e8e97a](https://linux-hardware.org/?probe=6e43e8e97a) | Oct 20, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | Notebook    | [1ba3f61a85](https://linux-hardware.org/?probe=1ba3f61a85) | Oct 20, 2023 |
| Lenovo        | E50-80 80J2                 | Notebook    | [539584b79f](https://linux-hardware.org/?probe=539584b79f) | Oct 20, 2023 |
| HP            | 3397                        | Desktop     | [7622910000](https://linux-hardware.org/?probe=7622910000) | Oct 20, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [ba440cffa8](https://linux-hardware.org/?probe=ba440cffa8) | Oct 20, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [91503bb9a7](https://linux-hardware.org/?probe=91503bb9a7) | Oct 19, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [2cff132417](https://linux-hardware.org/?probe=2cff132417) | Oct 19, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [74d8675dfc](https://linux-hardware.org/?probe=74d8675dfc) | Oct 19, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [a3bc73fa83](https://linux-hardware.org/?probe=a3bc73fa83) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [dad965a109](https://linux-hardware.org/?probe=dad965a109) | Oct 19, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [0733e9c4ae](https://linux-hardware.org/?probe=0733e9c4ae) | Oct 19, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ca65eabee](https://linux-hardware.org/?probe=8ca65eabee) | Oct 19, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [af74c8aeff](https://linux-hardware.org/?probe=af74c8aeff) | Oct 19, 2023 |
| MSI           | H61M-P21                    | Desktop     | [ba5fb8f49c](https://linux-hardware.org/?probe=ba5fb8f49c) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [330170d5d7](https://linux-hardware.org/?probe=330170d5d7) | Oct 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e6840ccb2f](https://linux-hardware.org/?probe=e6840ccb2f) | Oct 19, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [e57b8986ab](https://linux-hardware.org/?probe=e57b8986ab) | Oct 18, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [0994d6d9a2](https://linux-hardware.org/?probe=0994d6d9a2) | Oct 18, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [23efcaf7a2](https://linux-hardware.org/?probe=23efcaf7a2) | Oct 18, 2023 |
| Dell          | Latitude E6230              | Notebook    | [6b95eceb6d](https://linux-hardware.org/?probe=6b95eceb6d) | Oct 18, 2023 |
| Dell          | Latitude E6230              | Notebook    | [80ef815864](https://linux-hardware.org/?probe=80ef815864) | Oct 18, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [ce65c73e40](https://linux-hardware.org/?probe=ce65c73e40) | Oct 18, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [0c5f7a1b92](https://linux-hardware.org/?probe=0c5f7a1b92) | Oct 18, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [6495c7be9b](https://linux-hardware.org/?probe=6495c7be9b) | Oct 18, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [9cf2098fd0](https://linux-hardware.org/?probe=9cf2098fd0) | Oct 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [c9f674352d](https://linux-hardware.org/?probe=c9f674352d) | Oct 17, 2023 |
| Dell          | Latitude E6430              | Notebook    | [54d411b12d](https://linux-hardware.org/?probe=54d411b12d) | Oct 17, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [64e28141f8](https://linux-hardware.org/?probe=64e28141f8) | Oct 17, 2023 |
| HP            | Notebook                    | Notebook    | [62bc59c216](https://linux-hardware.org/?probe=62bc59c216) | Oct 17, 2023 |
| HP            | Notebook                    | Notebook    | [4ee408f659](https://linux-hardware.org/?probe=4ee408f659) | Oct 17, 2023 |
| HP            | 8265                        | Desktop     | [4e8e0ea26a](https://linux-hardware.org/?probe=4e8e0ea26a) | Oct 17, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a0dc919ac2](https://linux-hardware.org/?probe=a0dc919ac2) | Oct 17, 2023 |
| Lenovo        | ThinkPad T61 889855G        | Notebook    | [d2cf744079](https://linux-hardware.org/?probe=d2cf744079) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [9e3034f710](https://linux-hardware.org/?probe=9e3034f710) | Oct 17, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [4f8ecd431c](https://linux-hardware.org/?probe=4f8ecd431c) | Oct 17, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [ea34b890ed](https://linux-hardware.org/?probe=ea34b890ed) | Oct 17, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B7402FVA... | Convertible | [70797c08d1](https://linux-hardware.org/?probe=70797c08d1) | Oct 17, 2023 |
| HP            | 8265                        | Desktop     | [8f4c84f4f4](https://linux-hardware.org/?probe=8f4c84f4f4) | Oct 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [58d5c291fc](https://linux-hardware.org/?probe=58d5c291fc) | Oct 16, 2023 |
| Gigabyte      | MFLP3CP-00                  | Desktop     | [e2ddb858a9](https://linux-hardware.org/?probe=e2ddb858a9) | Oct 16, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [f04e1a56a4](https://linux-hardware.org/?probe=f04e1a56a4) | Oct 16, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b7fb2c5300](https://linux-hardware.org/?probe=b7fb2c5300) | Oct 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [707b8c0acd](https://linux-hardware.org/?probe=707b8c0acd) | Oct 15, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [59a2975041](https://linux-hardware.org/?probe=59a2975041) | Oct 15, 2023 |
| Dell          | Latitude E7470              | Notebook    | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | 2820h                       | Desktop     | [6b9bbe3a64](https://linux-hardware.org/?probe=6b9bbe3a64) | Oct 15, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [031455773c](https://linux-hardware.org/?probe=031455773c) | Oct 14, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [23a48d0873](https://linux-hardware.org/?probe=23a48d0873) | Oct 13, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [da6b006c58](https://linux-hardware.org/?probe=da6b006c58) | Oct 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [7af22eb528](https://linux-hardware.org/?probe=7af22eb528) | Oct 12, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [7fba4999fa](https://linux-hardware.org/?probe=7fba4999fa) | Oct 12, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [df2e146cf0](https://linux-hardware.org/?probe=df2e146cf0) | Oct 12, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [1ae8fcd28c](https://linux-hardware.org/?probe=1ae8fcd28c) | Oct 12, 2023 |
| Medion        | MS-7748                     | Desktop     | [8b625acaae](https://linux-hardware.org/?probe=8b625acaae) | Oct 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [50fbeed34d](https://linux-hardware.org/?probe=50fbeed34d) | Oct 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [e97e82006c](https://linux-hardware.org/?probe=e97e82006c) | Oct 11, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [d1e2846467](https://linux-hardware.org/?probe=d1e2846467) | Oct 11, 2023 |
| ASUSTek       | X55U                        | Notebook    | [82866b3b8b](https://linux-hardware.org/?probe=82866b3b8b) | Oct 11, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | Notebook    | [55e5cd7abc](https://linux-hardware.org/?probe=55e5cd7abc) | Oct 11, 2023 |
| HP            | 0AA8h                       | Desktop     | [5b821194a7](https://linux-hardware.org/?probe=5b821194a7) | Oct 11, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [83ed978b53](https://linux-hardware.org/?probe=83ed978b53) | Oct 11, 2023 |
| HP            | 0AA8h                       | Desktop     | [d88c5dced7](https://linux-hardware.org/?probe=d88c5dced7) | Oct 11, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [da6724b430](https://linux-hardware.org/?probe=da6724b430) | Oct 11, 2023 |
| eMachines     | E725                        | Notebook    | [1efc1e7a3a](https://linux-hardware.org/?probe=1efc1e7a3a) | Oct 10, 2023 |
| MSI           | MS-7817                     | Desktop     | [ed5e21c562](https://linux-hardware.org/?probe=ed5e21c562) | Oct 10, 2023 |
| Dell          | Latitude 5531               | Notebook    | [1a27e5ee19](https://linux-hardware.org/?probe=1a27e5ee19) | Oct 10, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [602dbf9ee0](https://linux-hardware.org/?probe=602dbf9ee0) | Oct 10, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [abca75fa11](https://linux-hardware.org/?probe=abca75fa11) | Oct 10, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | Desktop     | [2cba957b98](https://linux-hardware.org/?probe=2cba957b98) | Oct 09, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [731177232b](https://linux-hardware.org/?probe=731177232b) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [be9975c532](https://linux-hardware.org/?probe=be9975c532) | Oct 09, 2023 |
| ASUSTek       | K51AE                       | Notebook    | [9c3d05354e](https://linux-hardware.org/?probe=9c3d05354e) | Oct 09, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [c3d3003248](https://linux-hardware.org/?probe=c3d3003248) | Oct 09, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [d3bd6d1c84](https://linux-hardware.org/?probe=d3bd6d1c84) | Oct 08, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [4438e4ffc0](https://linux-hardware.org/?probe=4438e4ffc0) | Oct 08, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [d935714c39](https://linux-hardware.org/?probe=d935714c39) | Oct 08, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [af810081c9](https://linux-hardware.org/?probe=af810081c9) | Oct 08, 2023 |
| eMachines     | E525                        | Notebook    | [4eb2312418](https://linux-hardware.org/?probe=4eb2312418) | Oct 08, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [870f54c9bf](https://linux-hardware.org/?probe=870f54c9bf) | Oct 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [1c7c472122](https://linux-hardware.org/?probe=1c7c472122) | Oct 07, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [ffb2b71ce7](https://linux-hardware.org/?probe=ffb2b71ce7) | Oct 07, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [5fad8d4e39](https://linux-hardware.org/?probe=5fad8d4e39) | Oct 07, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [047ec55668](https://linux-hardware.org/?probe=047ec55668) | Oct 07, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | Desktop     | [29adc32704](https://linux-hardware.org/?probe=29adc32704) | Oct 07, 2023 |
| ASRock        | 775i945GZ                   | Desktop     | [ef1dd349c2](https://linux-hardware.org/?probe=ef1dd349c2) | Oct 07, 2023 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | Notebook    | [584a2bec33](https://linux-hardware.org/?probe=584a2bec33) | Oct 07, 2023 |
| ASRock        | 775i945GZ                   | Desktop     | [168713fd05](https://linux-hardware.org/?probe=168713fd05) | Oct 07, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2043b1ed85](https://linux-hardware.org/?probe=2043b1ed85) | Oct 07, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [53f61c91bf](https://linux-hardware.org/?probe=53f61c91bf) | Oct 07, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [ceaac5726a](https://linux-hardware.org/?probe=ceaac5726a) | Oct 07, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [996c50cad3](https://linux-hardware.org/?probe=996c50cad3) | Oct 07, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a2cc2d051e](https://linux-hardware.org/?probe=a2cc2d051e) | Oct 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [c585e7e5c4](https://linux-hardware.org/?probe=c585e7e5c4) | Oct 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [276b8cea5f](https://linux-hardware.org/?probe=276b8cea5f) | Oct 06, 2023 |
| Medion        | MS-7748                     | Desktop     | [01b345394a](https://linux-hardware.org/?probe=01b345394a) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [9e00c6f4b0](https://linux-hardware.org/?probe=9e00c6f4b0) | Oct 06, 2023 |
| HP            | 8265                        | Desktop     | [6fffe02648](https://linux-hardware.org/?probe=6fffe02648) | Oct 05, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [92cc269d09](https://linux-hardware.org/?probe=92cc269d09) | Oct 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B7402FVA... | Convertible | [0145cc500f](https://linux-hardware.org/?probe=0145cc500f) | Oct 05, 2023 |
| HP            | 8265                        | Desktop     | [fe09b6a8e0](https://linux-hardware.org/?probe=fe09b6a8e0) | Oct 04, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [d247c129c4](https://linux-hardware.org/?probe=d247c129c4) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| HP            | 1825                        | Desktop     | [d326bc59ff](https://linux-hardware.org/?probe=d326bc59ff) | Oct 04, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [d6cc456788](https://linux-hardware.org/?probe=d6cc456788) | Oct 04, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [78c456d55d](https://linux-hardware.org/?probe=78c456d55d) | Oct 04, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [74c8e5eadf](https://linux-hardware.org/?probe=74c8e5eadf) | Oct 03, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [aefdc00927](https://linux-hardware.org/?probe=aefdc00927) | Oct 03, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | Desktop     | [2c0427d154](https://linux-hardware.org/?probe=2c0427d154) | Oct 03, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [0a765bb242](https://linux-hardware.org/?probe=0a765bb242) | Oct 03, 2023 |
| HP            | ProBook 6570b               | Notebook    | [77a44e0363](https://linux-hardware.org/?probe=77a44e0363) | Oct 03, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [ee08a8d73a](https://linux-hardware.org/?probe=ee08a8d73a) | Oct 02, 2023 |
| Gigabyte      | GA-MA78GPM-DS2H             | Desktop     | [913fafd8a7](https://linux-hardware.org/?probe=913fafd8a7) | Oct 02, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [c64f3bbdbd](https://linux-hardware.org/?probe=c64f3bbdbd) | Oct 02, 2023 |
| HP            | 1494                        | Desktop     | [1c5842d2b7](https://linux-hardware.org/?probe=1c5842d2b7) | Oct 01, 2023 |
| HP            | 1494                        | Desktop     | [4ffbf86079](https://linux-hardware.org/?probe=4ffbf86079) | Oct 01, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b091100361](https://linux-hardware.org/?probe=b091100361) | Oct 01, 2023 |
| HP            | 8298                        | Desktop     | [0f73d73d00](https://linux-hardware.org/?probe=0f73d73d00) | Oct 01, 2023 |
| ASUSTek       | X55U                        | Notebook    | [029b7ab708](https://linux-hardware.org/?probe=029b7ab708) | Oct 01, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [5ba74bb868](https://linux-hardware.org/?probe=5ba74bb868) | Oct 01, 2023 |
| HP            | 339A                        | Desktop     | [cd104d3996](https://linux-hardware.org/?probe=cd104d3996) | Oct 01, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [fa948b8e32](https://linux-hardware.org/?probe=fa948b8e32) | Oct 01, 2023 |
| HP            | 1494                        | Desktop     | [5250e1dc1c](https://linux-hardware.org/?probe=5250e1dc1c) | Oct 01, 2023 |
| Lenovo        | ThinkCentre M55p 8811ZD4    | Desktop     | [710dea5f88](https://linux-hardware.org/?probe=710dea5f88) | Sep 30, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [4567599161](https://linux-hardware.org/?probe=4567599161) | Sep 29, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [526458167b](https://linux-hardware.org/?probe=526458167b) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [9d618e345a](https://linux-hardware.org/?probe=9d618e345a) | Sep 29, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [3513d5bcf3](https://linux-hardware.org/?probe=3513d5bcf3) | Sep 28, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [a355202f8a](https://linux-hardware.org/?probe=a355202f8a) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [ea6622fcde](https://linux-hardware.org/?probe=ea6622fcde) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [a7e3c38a52](https://linux-hardware.org/?probe=a7e3c38a52) | Sep 28, 2023 |
| eMachines     | E725                        | Notebook    | [2c76723d59](https://linux-hardware.org/?probe=2c76723d59) | Sep 28, 2023 |
| Zebra Tech... | 10-WLAN-1                   | Notebook    | [9959efdb76](https://linux-hardware.org/?probe=9959efdb76) | Sep 27, 2023 |
| ASUSTek       | D700MD                      | Desktop     | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| HP            | 250 G1                      | Notebook    | [0ec87fea6c](https://linux-hardware.org/?probe=0ec87fea6c) | Sep 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [e8577ce363](https://linux-hardware.org/?probe=e8577ce363) | Sep 27, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [390c16a341](https://linux-hardware.org/?probe=390c16a341) | Sep 26, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [11efb68800](https://linux-hardware.org/?probe=11efb68800) | Sep 26, 2023 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [4cbe33187c](https://linux-hardware.org/?probe=4cbe33187c) | Sep 26, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [a3fc0915cd](https://linux-hardware.org/?probe=a3fc0915cd) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [3ffed1f144](https://linux-hardware.org/?probe=3ffed1f144) | Sep 26, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [e6eff7d60d](https://linux-hardware.org/?probe=e6eff7d60d) | Sep 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [6b0a58d94c](https://linux-hardware.org/?probe=6b0a58d94c) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [263bf34c40](https://linux-hardware.org/?probe=263bf34c40) | Sep 25, 2023 |
| HP            | 250 G1                      | Notebook    | [1aa0ca441a](https://linux-hardware.org/?probe=1aa0ca441a) | Sep 25, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9a2c66690c](https://linux-hardware.org/?probe=9a2c66690c) | Sep 25, 2023 |
| MSI           | B85M-E33                    | Desktop     | [1e246dda8b](https://linux-hardware.org/?probe=1e246dda8b) | Sep 25, 2023 |
| HP            | 09F8h                       | Desktop     | [3d8c4a9ace](https://linux-hardware.org/?probe=3d8c4a9ace) | Sep 25, 2023 |
| HP            | 09F8h                       | Desktop     | [f844e52238](https://linux-hardware.org/?probe=f844e52238) | Sep 25, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [137fbb8afb](https://linux-hardware.org/?probe=137fbb8afb) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [dc76c26d4e](https://linux-hardware.org/?probe=dc76c26d4e) | Sep 24, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [dc6cea804c](https://linux-hardware.org/?probe=dc6cea804c) | Sep 24, 2023 |
| HP            | 09F8h                       | Desktop     | [d2ade2ea70](https://linux-hardware.org/?probe=d2ade2ea70) | Sep 24, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f94c540fde](https://linux-hardware.org/?probe=f94c540fde) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [fcdc931f2b](https://linux-hardware.org/?probe=fcdc931f2b) | Sep 24, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [2d441ed803](https://linux-hardware.org/?probe=2d441ed803) | Sep 24, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [1dd60939d2](https://linux-hardware.org/?probe=1dd60939d2) | Sep 24, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [0c9651a144](https://linux-hardware.org/?probe=0c9651a144) | Sep 24, 2023 |
| HP            | Notebook                    | Notebook    | [b222ca41de](https://linux-hardware.org/?probe=b222ca41de) | Sep 24, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [b4a2e6cb0a](https://linux-hardware.org/?probe=b4a2e6cb0a) | Sep 24, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [22a7b0cc9c](https://linux-hardware.org/?probe=22a7b0cc9c) | Sep 24, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [ce1b08cdf9](https://linux-hardware.org/?probe=ce1b08cdf9) | Sep 23, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | Notebook    | [8d4bdbafa8](https://linux-hardware.org/?probe=8d4bdbafa8) | Sep 23, 2023 |
| Gigabyte      | H110N-CF                    | Desktop     | [7655a31997](https://linux-hardware.org/?probe=7655a31997) | Sep 23, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [d967e2d2a3](https://linux-hardware.org/?probe=d967e2d2a3) | Sep 23, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [477998353b](https://linux-hardware.org/?probe=477998353b) | Sep 23, 2023 |
| HP            | 1497                        | Desktop     | [cbbd6a0182](https://linux-hardware.org/?probe=cbbd6a0182) | Sep 23, 2023 |
| HP            | Compaq 6710b (KE121EA#AK... | Notebook    | [a5b9ab6a07](https://linux-hardware.org/?probe=a5b9ab6a07) | Sep 23, 2023 |
| MSI           | MS-7309                     | Desktop     | [356be353d5](https://linux-hardware.org/?probe=356be353d5) | Sep 23, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b519a4adea](https://linux-hardware.org/?probe=b519a4adea) | Sep 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [8d7c00fcd2](https://linux-hardware.org/?probe=8d7c00fcd2) | Sep 23, 2023 |
| HP            | 650                         | Notebook    | [3c45902b7c](https://linux-hardware.org/?probe=3c45902b7c) | Sep 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [134cfff173](https://linux-hardware.org/?probe=134cfff173) | Sep 22, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [c933242918](https://linux-hardware.org/?probe=c933242918) | Sep 22, 2023 |
| Dell          | Latitude 7390               | Notebook    | [1aab1b313f](https://linux-hardware.org/?probe=1aab1b313f) | Sep 22, 2023 |
| HP            | 250 G1                      | Notebook    | [44dde35a76](https://linux-hardware.org/?probe=44dde35a76) | Sep 22, 2023 |
| Dell          | Latitude E5520              | Notebook    | [ae034f7a6b](https://linux-hardware.org/?probe=ae034f7a6b) | Sep 22, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [18581b1af5](https://linux-hardware.org/?probe=18581b1af5) | Sep 22, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [daa9128e32](https://linux-hardware.org/?probe=daa9128e32) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [bb5eff384a](https://linux-hardware.org/?probe=bb5eff384a) | Sep 22, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [61ce9ed478](https://linux-hardware.org/?probe=61ce9ed478) | Sep 22, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [96ba82f38e](https://linux-hardware.org/?probe=96ba82f38e) | Sep 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [942f5325d2](https://linux-hardware.org/?probe=942f5325d2) | Sep 22, 2023 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [701abaeb8f](https://linux-hardware.org/?probe=701abaeb8f) | Sep 22, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [ff935c4dbe](https://linux-hardware.org/?probe=ff935c4dbe) | Sep 22, 2023 |
| ASRock        | B85M                        | Desktop     | [5b78620442](https://linux-hardware.org/?probe=5b78620442) | Sep 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [c71bb49dcd](https://linux-hardware.org/?probe=c71bb49dcd) | Sep 21, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [60976010ac](https://linux-hardware.org/?probe=60976010ac) | Sep 21, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [25e14aaf2b](https://linux-hardware.org/?probe=25e14aaf2b) | Sep 21, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [b21f53b9e1](https://linux-hardware.org/?probe=b21f53b9e1) | Sep 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [d1b966125a](https://linux-hardware.org/?probe=d1b966125a) | Sep 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3e8e36e3ea](https://linux-hardware.org/?probe=3e8e36e3ea) | Sep 21, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [8552d31b3c](https://linux-hardware.org/?probe=8552d31b3c) | Sep 21, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [32e2046699](https://linux-hardware.org/?probe=32e2046699) | Sep 21, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [22733fb7ba](https://linux-hardware.org/?probe=22733fb7ba) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d348acd6c8](https://linux-hardware.org/?probe=d348acd6c8) | Sep 21, 2023 |
| Dell          | Latitude E6220              | Notebook    | [dd26ec3c45](https://linux-hardware.org/?probe=dd26ec3c45) | Sep 21, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6b9f9348c0](https://linux-hardware.org/?probe=6b9f9348c0) | Sep 21, 2023 |
| HP            | 1495                        | Desktop     | [9c5926d73b](https://linux-hardware.org/?probe=9c5926d73b) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [cff5fbdefd](https://linux-hardware.org/?probe=cff5fbdefd) | Sep 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9f1f1562ed](https://linux-hardware.org/?probe=9f1f1562ed) | Sep 21, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f3deee7792](https://linux-hardware.org/?probe=f3deee7792) | Sep 20, 2023 |
| Lenovo        | 1730-A1G                    | Desktop     | [9f9580c81f](https://linux-hardware.org/?probe=9f9580c81f) | Sep 19, 2023 |
| Lenovo        | Aptio CRB SDK0G00599 WIN    | Mini pc     | [d7f55df5b8](https://linux-hardware.org/?probe=d7f55df5b8) | Sep 19, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [14714d058e](https://linux-hardware.org/?probe=14714d058e) | Sep 19, 2023 |
| HP            | 8298                        | Desktop     | [006592d87f](https://linux-hardware.org/?probe=006592d87f) | Sep 19, 2023 |
| Lenovo        | 1730-A1G                    | Desktop     | [e58cd05ca6](https://linux-hardware.org/?probe=e58cd05ca6) | Sep 19, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d83d7bbfa8](https://linux-hardware.org/?probe=d83d7bbfa8) | Sep 18, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [12a4225b04](https://linux-hardware.org/?probe=12a4225b04) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [851a7301bc](https://linux-hardware.org/?probe=851a7301bc) | Sep 18, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [8ee590e888](https://linux-hardware.org/?probe=8ee590e888) | Sep 18, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [42ade99539](https://linux-hardware.org/?probe=42ade99539) | Sep 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [60e5e9a3db](https://linux-hardware.org/?probe=60e5e9a3db) | Sep 18, 2023 |
| HP            | 1494                        | Desktop     | [f7dcc5924c](https://linux-hardware.org/?probe=f7dcc5924c) | Sep 17, 2023 |
| HP            | 1494                        | Desktop     | [35c90d3fb2](https://linux-hardware.org/?probe=35c90d3fb2) | Sep 17, 2023 |
| AZW           | U59                         | Desktop     | [2bc9b4b184](https://linux-hardware.org/?probe=2bc9b4b184) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [92ff22e072](https://linux-hardware.org/?probe=92ff22e072) | Sep 17, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [7d679bbf7f](https://linux-hardware.org/?probe=7d679bbf7f) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [c34520d1c2](https://linux-hardware.org/?probe=c34520d1c2) | Sep 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [15e259376e](https://linux-hardware.org/?probe=15e259376e) | Sep 16, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [fb0eee9917](https://linux-hardware.org/?probe=fb0eee9917) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [ae9c2e3978](https://linux-hardware.org/?probe=ae9c2e3978) | Sep 16, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [8076be0adb](https://linux-hardware.org/?probe=8076be0adb) | Sep 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [bd0a13e867](https://linux-hardware.org/?probe=bd0a13e867) | Sep 16, 2023 |
| Dell          | Latitude E6220              | Notebook    | [8a341bd0e2](https://linux-hardware.org/?probe=8a341bd0e2) | Sep 16, 2023 |
| HP            | 650                         | Notebook    | [f648ca59f3](https://linux-hardware.org/?probe=f648ca59f3) | Sep 16, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | Notebook    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [bd5fae0639](https://linux-hardware.org/?probe=bd5fae0639) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [781590255d](https://linux-hardware.org/?probe=781590255d) | Sep 15, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [601a3eed6e](https://linux-hardware.org/?probe=601a3eed6e) | Sep 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [382acd4186](https://linux-hardware.org/?probe=382acd4186) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c2529c08a4](https://linux-hardware.org/?probe=c2529c08a4) | Sep 14, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [04d9ccd10f](https://linux-hardware.org/?probe=04d9ccd10f) | Sep 14, 2023 |
| HP            | 250 G1                      | Notebook    | [05483d5695](https://linux-hardware.org/?probe=05483d5695) | Sep 14, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [14a4828110](https://linux-hardware.org/?probe=14a4828110) | Sep 14, 2023 |
| Insyde        | Braswell                    | Notebook    | [1fb0864056](https://linux-hardware.org/?probe=1fb0864056) | Sep 14, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [8ffd465a75](https://linux-hardware.org/?probe=8ffd465a75) | Sep 14, 2023 |
| HP            | 8265                        | Desktop     | [1e16a47683](https://linux-hardware.org/?probe=1e16a47683) | Sep 13, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [bc19e0cdbb](https://linux-hardware.org/?probe=bc19e0cdbb) | Sep 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [8dba4d978a](https://linux-hardware.org/?probe=8dba4d978a) | Sep 13, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [9bd19e6fbf](https://linux-hardware.org/?probe=9bd19e6fbf) | Sep 12, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [ef0bc2bd79](https://linux-hardware.org/?probe=ef0bc2bd79) | Sep 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [79cf77c6ba](https://linux-hardware.org/?probe=79cf77c6ba) | Sep 12, 2023 |
| Dell          | Latitude E6220              | Notebook    | [f34fd65819](https://linux-hardware.org/?probe=f34fd65819) | Sep 12, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ec4efd4d4d](https://linux-hardware.org/?probe=ec4efd4d4d) | Sep 11, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Intel         | S5500HCV E40912-455         | Server      | [1f7dfe194c](https://linux-hardware.org/?probe=1f7dfe194c) | Sep 11, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [60b271e896](https://linux-hardware.org/?probe=60b271e896) | Sep 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [7835af6517](https://linux-hardware.org/?probe=7835af6517) | Sep 11, 2023 |
| HP            | 8265                        | Desktop     | [f7e98e0f58](https://linux-hardware.org/?probe=f7e98e0f58) | Sep 10, 2023 |
| HP            | 3047h                       | Desktop     | [1070c2f57a](https://linux-hardware.org/?probe=1070c2f57a) | Sep 10, 2023 |
| HP            | 3047h                       | Desktop     | [746e154eaf](https://linux-hardware.org/?probe=746e154eaf) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | Desktop     | [31f5d64453](https://linux-hardware.org/?probe=31f5d64453) | Sep 10, 2023 |
| ASRock        | 775i945GZ                   | Desktop     | [625c711748](https://linux-hardware.org/?probe=625c711748) | Sep 10, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [933a72acff](https://linux-hardware.org/?probe=933a72acff) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [9c9441fa1c](https://linux-hardware.org/?probe=9c9441fa1c) | Sep 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2706096498](https://linux-hardware.org/?probe=2706096498) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| HP            | Notebook                    | Notebook    | [231eb17318](https://linux-hardware.org/?probe=231eb17318) | Sep 10, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [5fc8984800](https://linux-hardware.org/?probe=5fc8984800) | Sep 10, 2023 |
| HP            | 339A                        | Desktop     | [f19d37b028](https://linux-hardware.org/?probe=f19d37b028) | Sep 10, 2023 |
| HP            | 339A                        | Desktop     | [794685ff75](https://linux-hardware.org/?probe=794685ff75) | Sep 10, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [06e4b83617](https://linux-hardware.org/?probe=06e4b83617) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| AZW           | U59                         | Desktop     | [e199a9df01](https://linux-hardware.org/?probe=e199a9df01) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| HP            | 1497                        | Desktop     | [e420bbd661](https://linux-hardware.org/?probe=e420bbd661) | Sep 09, 2023 |
| Intel         | S5500HCV E40912-455         | Server      | [f034939e2e](https://linux-hardware.org/?probe=f034939e2e) | Sep 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0f8249e50f](https://linux-hardware.org/?probe=0f8249e50f) | Sep 09, 2023 |
| HP            | 1497                        | Desktop     | [6de463b204](https://linux-hardware.org/?probe=6de463b204) | Sep 09, 2023 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | Notebook    | [b3697e5a7e](https://linux-hardware.org/?probe=b3697e5a7e) | Sep 09, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [aa332cc883](https://linux-hardware.org/?probe=aa332cc883) | Sep 09, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [5c050dd160](https://linux-hardware.org/?probe=5c050dd160) | Sep 08, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [7f678086c3](https://linux-hardware.org/?probe=7f678086c3) | Sep 08, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [8a383606e3](https://linux-hardware.org/?probe=8a383606e3) | Sep 08, 2023 |
| MSI           | FM2-A85XMA-E35              | Desktop     | [ea1d2d5910](https://linux-hardware.org/?probe=ea1d2d5910) | Sep 08, 2023 |
| Toshiba       | Satellite C55-A-1NV         | Notebook    | [d0f37c70e7](https://linux-hardware.org/?probe=d0f37c70e7) | Sep 08, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [598ed8c100](https://linux-hardware.org/?probe=598ed8c100) | Sep 08, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [49adfda956](https://linux-hardware.org/?probe=49adfda956) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [9c672d2801](https://linux-hardware.org/?probe=9c672d2801) | Sep 07, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [898930f2b1](https://linux-hardware.org/?probe=898930f2b1) | Sep 07, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [132fa17be7](https://linux-hardware.org/?probe=132fa17be7) | Sep 06, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [36e10816ea](https://linux-hardware.org/?probe=36e10816ea) | Sep 06, 2023 |
| Dell          | Latitude E6540              | Notebook    | [2832b1dd0d](https://linux-hardware.org/?probe=2832b1dd0d) | Sep 06, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [e5a99beac7](https://linux-hardware.org/?probe=e5a99beac7) | Sep 06, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [c19df6a939](https://linux-hardware.org/?probe=c19df6a939) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [86a4e0d5b8](https://linux-hardware.org/?probe=86a4e0d5b8) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d729a17611](https://linux-hardware.org/?probe=d729a17611) | Sep 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [857d41cc6a](https://linux-hardware.org/?probe=857d41cc6a) | Sep 06, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [65bbed09ce](https://linux-hardware.org/?probe=65bbed09ce) | Sep 06, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [b9dddc1ef8](https://linux-hardware.org/?probe=b9dddc1ef8) | Sep 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [abad0fc559](https://linux-hardware.org/?probe=abad0fc559) | Sep 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [999a713227](https://linux-hardware.org/?probe=999a713227) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [8f2ba921b5](https://linux-hardware.org/?probe=8f2ba921b5) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [6d7631e83a](https://linux-hardware.org/?probe=6d7631e83a) | Sep 05, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [304ccb5f7e](https://linux-hardware.org/?probe=304ccb5f7e) | Sep 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [6d1d81c7b3](https://linux-hardware.org/?probe=6d1d81c7b3) | Sep 05, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [ce571e2d16](https://linux-hardware.org/?probe=ce571e2d16) | Sep 05, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [4297e9f110](https://linux-hardware.org/?probe=4297e9f110) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e6eb36b583](https://linux-hardware.org/?probe=e6eb36b583) | Sep 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [4d913a8444](https://linux-hardware.org/?probe=4d913a8444) | Sep 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [7647c25446](https://linux-hardware.org/?probe=7647c25446) | Sep 05, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9051992ac5](https://linux-hardware.org/?probe=9051992ac5) | Sep 05, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [6a1b31cf59](https://linux-hardware.org/?probe=6a1b31cf59) | Sep 05, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [cafe064514](https://linux-hardware.org/?probe=cafe064514) | Sep 05, 2023 |
| Lenovo        | ThinkPad T520 4243WCR       | Notebook    | [181ef642cd](https://linux-hardware.org/?probe=181ef642cd) | Sep 05, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2fe06014b3](https://linux-hardware.org/?probe=2fe06014b3) | Sep 05, 2023 |
| HP            | 1495                        | Desktop     | [272f11edff](https://linux-hardware.org/?probe=272f11edff) | Sep 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [2c6e7f955b](https://linux-hardware.org/?probe=2c6e7f955b) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| HP            | Notebook                    | Notebook    | [76a4d54b3b](https://linux-hardware.org/?probe=76a4d54b3b) | Sep 04, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [8e4830d581](https://linux-hardware.org/?probe=8e4830d581) | Sep 04, 2023 |
| MSI           | H61M-P21                    | Desktop     | [9eddb8442b](https://linux-hardware.org/?probe=9eddb8442b) | Sep 04, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cdee70b142](https://linux-hardware.org/?probe=cdee70b142) | Sep 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [435d20add8](https://linux-hardware.org/?probe=435d20add8) | Sep 04, 2023 |
| Dell          | 0TY565                      | Desktop     | [c1a456e342](https://linux-hardware.org/?probe=c1a456e342) | Sep 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [daeb81e2f6](https://linux-hardware.org/?probe=daeb81e2f6) | Sep 04, 2023 |
| MSI           | B85M-E33                    | Desktop     | [13b7edd351](https://linux-hardware.org/?probe=13b7edd351) | Sep 04, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [6dd9f72144](https://linux-hardware.org/?probe=6dd9f72144) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| eMachines     | E725                        | Notebook    | [cb1c5bd673](https://linux-hardware.org/?probe=cb1c5bd673) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [90fb74ac63](https://linux-hardware.org/?probe=90fb74ac63) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [3e196c9509](https://linux-hardware.org/?probe=3e196c9509) | Sep 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [a6957d8672](https://linux-hardware.org/?probe=a6957d8672) | Sep 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [8bbf469df8](https://linux-hardware.org/?probe=8bbf469df8) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [c450c306b1](https://linux-hardware.org/?probe=c450c306b1) | Sep 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [a9a436edee](https://linux-hardware.org/?probe=a9a436edee) | Sep 03, 2023 |
| Fujitsu Si... | D2721-A1 S26361-D2721-A1    | Desktop     | [f56611f610](https://linux-hardware.org/?probe=f56611f610) | Sep 03, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [55bb236bde](https://linux-hardware.org/?probe=55bb236bde) | Sep 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S2KV20    | Notebook    | [248ef69016](https://linux-hardware.org/?probe=248ef69016) | Sep 03, 2023 |
| AZW           | U59                         | Desktop     | [98e1e109a5](https://linux-hardware.org/?probe=98e1e109a5) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [29553c1c51](https://linux-hardware.org/?probe=29553c1c51) | Sep 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [87cb36af8d](https://linux-hardware.org/?probe=87cb36af8d) | Sep 03, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| HP            | 255 G2                      | Notebook    | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [adaa4a1718](https://linux-hardware.org/?probe=adaa4a1718) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [c1ad093dbb](https://linux-hardware.org/?probe=c1ad093dbb) | Sep 02, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [b6a5325068](https://linux-hardware.org/?probe=b6a5325068) | Sep 02, 2023 |
| Dell          | Inspiron 5379               | Notebook    | [1cbc463a43](https://linux-hardware.org/?probe=1cbc463a43) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [ab9746582a](https://linux-hardware.org/?probe=ab9746582a) | Sep 02, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [091c787432](https://linux-hardware.org/?probe=091c787432) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f8bb43e243](https://linux-hardware.org/?probe=f8bb43e243) | Sep 01, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e705d0ef10](https://linux-hardware.org/?probe=e705d0ef10) | Sep 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [5e95785b8e](https://linux-hardware.org/?probe=5e95785b8e) | Sep 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c37cbe9bd9](https://linux-hardware.org/?probe=c37cbe9bd9) | Sep 01, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [e1eb9c4b56](https://linux-hardware.org/?probe=e1eb9c4b56) | Sep 01, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [d5df2de977](https://linux-hardware.org/?probe=d5df2de977) | Sep 01, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e3bd6a8273](https://linux-hardware.org/?probe=e3bd6a8273) | Aug 31, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [37523b5aa3](https://linux-hardware.org/?probe=37523b5aa3) | Aug 31, 2023 |
| MSI           | MS-7817                     | Desktop     | [badd4016f3](https://linux-hardware.org/?probe=badd4016f3) | Aug 31, 2023 |
| HP            | 339A                        | Desktop     | [4b43fa6951](https://linux-hardware.org/?probe=4b43fa6951) | Aug 31, 2023 |
| MSI           | P43i                        | Desktop     | [b7c88acd7e](https://linux-hardware.org/?probe=b7c88acd7e) | Aug 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0c18cf228](https://linux-hardware.org/?probe=e0c18cf228) | Aug 31, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [47cb0a10f7](https://linux-hardware.org/?probe=47cb0a10f7) | Aug 31, 2023 |
| Dell          | 0TY915                      | Desktop     | [5ad1572cf2](https://linux-hardware.org/?probe=5ad1572cf2) | Aug 31, 2023 |
| Dell          | 0TY915                      | Desktop     | [e66372d79b](https://linux-hardware.org/?probe=e66372d79b) | Aug 31, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [458b3b6310](https://linux-hardware.org/?probe=458b3b6310) | Aug 31, 2023 |
| Dell          | 0XPDFK A00                  | Desktop     | [b7df67e39a](https://linux-hardware.org/?probe=b7df67e39a) | Aug 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4d1e47297b](https://linux-hardware.org/?probe=4d1e47297b) | Aug 30, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | EB1035                      | All in one  | [ea73e26c86](https://linux-hardware.org/?probe=ea73e26c86) | Aug 30, 2023 |
| HP            | 8265                        | Desktop     | [2c26b2823c](https://linux-hardware.org/?probe=2c26b2823c) | Aug 30, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [0eddf6dfcd](https://linux-hardware.org/?probe=0eddf6dfcd) | Aug 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ba4d78320f](https://linux-hardware.org/?probe=ba4d78320f) | Aug 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8e595f3214](https://linux-hardware.org/?probe=8e595f3214) | Aug 30, 2023 |
| Dell          | 0DR845                      | Desktop     | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41797b2df4](https://linux-hardware.org/?probe=41797b2df4) | Aug 30, 2023 |
| HP            | 250 G1                      | Notebook    | [6821396f96](https://linux-hardware.org/?probe=6821396f96) | Aug 29, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [ebfb32e1a8](https://linux-hardware.org/?probe=ebfb32e1a8) | Aug 29, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [cc92a730bc](https://linux-hardware.org/?probe=cc92a730bc) | Aug 29, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [33fbfa4413](https://linux-hardware.org/?probe=33fbfa4413) | Aug 29, 2023 |
| Intel         | S5500HCV E40912-455         | Server      | [d6f93cea95](https://linux-hardware.org/?probe=d6f93cea95) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8a109f7691](https://linux-hardware.org/?probe=8a109f7691) | Aug 29, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [c806d70c9d](https://linux-hardware.org/?probe=c806d70c9d) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0f7047f2c2](https://linux-hardware.org/?probe=0f7047f2c2) | Aug 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [9c733aac9d](https://linux-hardware.org/?probe=9c733aac9d) | Aug 28, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3869234a03](https://linux-hardware.org/?probe=3869234a03) | Aug 28, 2023 |
| GPD           | G1619-01                    | Notebook    | [0e12028a4d](https://linux-hardware.org/?probe=0e12028a4d) | Aug 28, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [ebf28922af](https://linux-hardware.org/?probe=ebf28922af) | Aug 28, 2023 |
| Lenovo        | ThinkStation D20 4158AF8    | Desktop     | [39db55a5e2](https://linux-hardware.org/?probe=39db55a5e2) | Aug 28, 2023 |
| HP            | 339A                        | Desktop     | [56775507f8](https://linux-hardware.org/?probe=56775507f8) | Aug 28, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [21b85ec9f3](https://linux-hardware.org/?probe=21b85ec9f3) | Aug 28, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [635743c7d4](https://linux-hardware.org/?probe=635743c7d4) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [9b898e43e7](https://linux-hardware.org/?probe=9b898e43e7) | Aug 28, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [43c8f5f7bd](https://linux-hardware.org/?probe=43c8f5f7bd) | Aug 28, 2023 |
| Intel         | NUC13SBBi9 M58736-303       | Mini pc     | [513140b0b6](https://linux-hardware.org/?probe=513140b0b6) | Aug 28, 2023 |
| Lenovo        | ThinkPad X220 4291C84       | Notebook    | [623b0f76d1](https://linux-hardware.org/?probe=623b0f76d1) | Aug 28, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [cb57dd666e](https://linux-hardware.org/?probe=cb57dd666e) | Aug 28, 2023 |
| eMachines     | E725                        | Notebook    | [415b4166b9](https://linux-hardware.org/?probe=415b4166b9) | Aug 27, 2023 |
| eMachines     | E725                        | Notebook    | [edb02e1501](https://linux-hardware.org/?probe=edb02e1501) | Aug 27, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [c7ee25be08](https://linux-hardware.org/?probe=c7ee25be08) | Aug 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0MN0A    | Notebook    | [4cfb3bf1b1](https://linux-hardware.org/?probe=4cfb3bf1b1) | Aug 27, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [579e64039e](https://linux-hardware.org/?probe=579e64039e) | Aug 27, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [28217feff7](https://linux-hardware.org/?probe=28217feff7) | Aug 27, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [7f67a243d7](https://linux-hardware.org/?probe=7f67a243d7) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | Notebook    | [3f742c8393](https://linux-hardware.org/?probe=3f742c8393) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | Notebook    | [3b462ade1a](https://linux-hardware.org/?probe=3b462ade1a) | Aug 27, 2023 |
| ASRock        | B85M                        | Desktop     | [e1030ad449](https://linux-hardware.org/?probe=e1030ad449) | Aug 27, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [bfaf77795d](https://linux-hardware.org/?probe=bfaf77795d) | Aug 27, 2023 |
| HP            | 250 G1                      | Notebook    | [27baf9b755](https://linux-hardware.org/?probe=27baf9b755) | Aug 27, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [6641de7018](https://linux-hardware.org/?probe=6641de7018) | Aug 27, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [f153f48649](https://linux-hardware.org/?probe=f153f48649) | Aug 27, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [7a3378b6eb](https://linux-hardware.org/?probe=7a3378b6eb) | Aug 27, 2023 |
| HP            | 650                         | Notebook    | [ed399f8cfb](https://linux-hardware.org/?probe=ed399f8cfb) | Aug 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [679808ec60](https://linux-hardware.org/?probe=679808ec60) | Aug 26, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [e8e1a3d429](https://linux-hardware.org/?probe=e8e1a3d429) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | Notebook    | [b1fe190515](https://linux-hardware.org/?probe=b1fe190515) | Aug 26, 2023 |
| HP            | 3047h                       | Desktop     | [28037f3ded](https://linux-hardware.org/?probe=28037f3ded) | Aug 26, 2023 |
| HP            | 3047h                       | Desktop     | [dd6e5ce100](https://linux-hardware.org/?probe=dd6e5ce100) | Aug 26, 2023 |
| HP            | 8265                        | Desktop     | [39f6952188](https://linux-hardware.org/?probe=39f6952188) | Aug 26, 2023 |
| ASRock        | B85M                        | Desktop     | [70af81b1a1](https://linux-hardware.org/?probe=70af81b1a1) | Aug 26, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [56f9a82624](https://linux-hardware.org/?probe=56f9a82624) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | Notebook    | [bc1cdf2ce7](https://linux-hardware.org/?probe=bc1cdf2ce7) | Aug 26, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [855ad99ea5](https://linux-hardware.org/?probe=855ad99ea5) | Aug 26, 2023 |
| MSI           | P43i                        | Desktop     | [3f3ea5ff94](https://linux-hardware.org/?probe=3f3ea5ff94) | Aug 26, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [e226d45872](https://linux-hardware.org/?probe=e226d45872) | Aug 26, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [7db44bc8af](https://linux-hardware.org/?probe=7db44bc8af) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | Notebook    | [d8b8b7565b](https://linux-hardware.org/?probe=d8b8b7565b) | Aug 26, 2023 |
| HP            | 250 G1                      | Notebook    | [d2989d3be0](https://linux-hardware.org/?probe=d2989d3be0) | Aug 26, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [b1e5815ba9](https://linux-hardware.org/?probe=b1e5815ba9) | Aug 26, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [8a59de1138](https://linux-hardware.org/?probe=8a59de1138) | Aug 26, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [55da0d1667](https://linux-hardware.org/?probe=55da0d1667) | Aug 26, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [5e884e12a0](https://linux-hardware.org/?probe=5e884e12a0) | Aug 26, 2023 |
| Dell          | Latitude E6410              | Notebook    | [20134aee31](https://linux-hardware.org/?probe=20134aee31) | Aug 25, 2023 |
| MSI           | MS-7817                     | Desktop     | [9b7cfe20df](https://linux-hardware.org/?probe=9b7cfe20df) | Aug 25, 2023 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [675c426397](https://linux-hardware.org/?probe=675c426397) | Aug 25, 2023 |
| Dell          | Latitude E5520              | Notebook    | [6e27e77275](https://linux-hardware.org/?probe=6e27e77275) | Aug 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [de7752b138](https://linux-hardware.org/?probe=de7752b138) | Aug 25, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [1dc34b7cc5](https://linux-hardware.org/?probe=1dc34b7cc5) | Aug 25, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [7d90deb5b1](https://linux-hardware.org/?probe=7d90deb5b1) | Aug 25, 2023 |
| Mediacom      | GTZS                        | Notebook    | [8b40b2b9fc](https://linux-hardware.org/?probe=8b40b2b9fc) | Aug 24, 2023 |
| Dell          | Latitude E6220              | Notebook    | [6afbb8e146](https://linux-hardware.org/?probe=6afbb8e146) | Aug 24, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [1bb6f8d738](https://linux-hardware.org/?probe=1bb6f8d738) | Aug 24, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [74fe0374b3](https://linux-hardware.org/?probe=74fe0374b3) | Aug 23, 2023 |
| Dell          | Precision M6600             | Notebook    | [60acc9bcb0](https://linux-hardware.org/?probe=60acc9bcb0) | Aug 23, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [9d18657882](https://linux-hardware.org/?probe=9d18657882) | Aug 22, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [4cb50f9265](https://linux-hardware.org/?probe=4cb50f9265) | Aug 22, 2023 |
| HP            | Presario CQ57               | Notebook    | [bfc59ff9cd](https://linux-hardware.org/?probe=bfc59ff9cd) | Aug 22, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [54ce83065f](https://linux-hardware.org/?probe=54ce83065f) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | K55A                        | Notebook    | [090e4d0a73](https://linux-hardware.org/?probe=090e4d0a73) | Aug 20, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [76d74daf52](https://linux-hardware.org/?probe=76d74daf52) | Aug 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [2f0cd6e6d3](https://linux-hardware.org/?probe=2f0cd6e6d3) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [25fbe59866](https://linux-hardware.org/?probe=25fbe59866) | Aug 19, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [a6cf8bf5f2](https://linux-hardware.org/?probe=a6cf8bf5f2) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [97a587e6ad](https://linux-hardware.org/?probe=97a587e6ad) | Aug 19, 2023 |
| Dell          | Latitude E6230              | Notebook    | [7888184dd0](https://linux-hardware.org/?probe=7888184dd0) | Aug 19, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1672d92536](https://linux-hardware.org/?probe=1672d92536) | Aug 19, 2023 |
| HP            | Notebook                    | Notebook    | [661cb258ef](https://linux-hardware.org/?probe=661cb258ef) | Aug 19, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5ac356a22f](https://linux-hardware.org/?probe=5ac356a22f) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [c6f3f044c9](https://linux-hardware.org/?probe=c6f3f044c9) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [9734816ff1](https://linux-hardware.org/?probe=9734816ff1) | Aug 19, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [9f5242decc](https://linux-hardware.org/?probe=9f5242decc) | Aug 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [53a81617e7](https://linux-hardware.org/?probe=53a81617e7) | Aug 19, 2023 |
| Dell          | Precision M6600             | Notebook    | [15df8fbaaf](https://linux-hardware.org/?probe=15df8fbaaf) | Aug 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [68bfd376a0](https://linux-hardware.org/?probe=68bfd376a0) | Aug 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [84cbd742a1](https://linux-hardware.org/?probe=84cbd742a1) | Aug 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [0edbb9bdf1](https://linux-hardware.org/?probe=0edbb9bdf1) | Aug 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [645171b203](https://linux-hardware.org/?probe=645171b203) | Aug 17, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c093ae6eb5](https://linux-hardware.org/?probe=c093ae6eb5) | Aug 17, 2023 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [79d8f79efe](https://linux-hardware.org/?probe=79d8f79efe) | Aug 17, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [b48511c64c](https://linux-hardware.org/?probe=b48511c64c) | Aug 16, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [810d33b380](https://linux-hardware.org/?probe=810d33b380) | Aug 16, 2023 |
| HP            | 1495                        | Desktop     | [1d04585fac](https://linux-hardware.org/?probe=1d04585fac) | Aug 16, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [529613b5c7](https://linux-hardware.org/?probe=529613b5c7) | Aug 15, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [8f1803298d](https://linux-hardware.org/?probe=8f1803298d) | Aug 15, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [7b48c318ed](https://linux-hardware.org/?probe=7b48c318ed) | Aug 15, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [0d11484b59](https://linux-hardware.org/?probe=0d11484b59) | Aug 15, 2023 |
| Dell          | Latitude E6410              | Notebook    | [9cc0b91505](https://linux-hardware.org/?probe=9cc0b91505) | Aug 14, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [aa3414ebdc](https://linux-hardware.org/?probe=aa3414ebdc) | Aug 14, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d5b2c3b80a](https://linux-hardware.org/?probe=d5b2c3b80a) | Aug 14, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [013e2fdac5](https://linux-hardware.org/?probe=013e2fdac5) | Aug 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [72977f6f8a](https://linux-hardware.org/?probe=72977f6f8a) | Aug 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [b718d1c1f8](https://linux-hardware.org/?probe=b718d1c1f8) | Aug 13, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| HP            | 3395                        | All in one  | [1dc6b38792](https://linux-hardware.org/?probe=1dc6b38792) | Aug 12, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [84cbdf027b](https://linux-hardware.org/?probe=84cbdf027b) | Aug 12, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8037585070](https://linux-hardware.org/?probe=8037585070) | Aug 12, 2023 |
| HP            | 1495                        | Desktop     | [837afb7bfa](https://linux-hardware.org/?probe=837afb7bfa) | Aug 12, 2023 |
| ASUSTek       | K55A                        | Notebook    | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| HP            | 1495                        | Desktop     | [9e8b73f16e](https://linux-hardware.org/?probe=9e8b73f16e) | Aug 11, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [3c7140c389](https://linux-hardware.org/?probe=3c7140c389) | Aug 11, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [17e503622d](https://linux-hardware.org/?probe=17e503622d) | Aug 11, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [485a8bf15d](https://linux-hardware.org/?probe=485a8bf15d) | Aug 10, 2023 |
| HP            | 1495                        | Desktop     | [6c458bf059](https://linux-hardware.org/?probe=6c458bf059) | Aug 10, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [ae87c6938f](https://linux-hardware.org/?probe=ae87c6938f) | Aug 10, 2023 |
| HP            | 0AA4h                       | Desktop     | [e4da6a6aaf](https://linux-hardware.org/?probe=e4da6a6aaf) | Aug 09, 2023 |
| HP            | Notebook                    | Notebook    | [59e006f729](https://linux-hardware.org/?probe=59e006f729) | Aug 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [4081f7bbda](https://linux-hardware.org/?probe=4081f7bbda) | Aug 09, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [e28870563c](https://linux-hardware.org/?probe=e28870563c) | Aug 09, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [45d7954a65](https://linux-hardware.org/?probe=45d7954a65) | Aug 08, 2023 |
| Google        | Dragonair                   | Notebook    | [d78af70cf3](https://linux-hardware.org/?probe=d78af70cf3) | Aug 08, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [6601d0d136](https://linux-hardware.org/?probe=6601d0d136) | Aug 07, 2023 |
| HP            | Notebook                    | Notebook    | [5cfbf14023](https://linux-hardware.org/?probe=5cfbf14023) | Aug 07, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [64dc45c007](https://linux-hardware.org/?probe=64dc45c007) | Aug 07, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [b62c8c40f5](https://linux-hardware.org/?probe=b62c8c40f5) | Aug 07, 2023 |
| Gigabyte      | J4005ND2P-CF                | Desktop     | [f3644b56ad](https://linux-hardware.org/?probe=f3644b56ad) | Aug 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [35bb5f3e65](https://linux-hardware.org/?probe=35bb5f3e65) | Aug 06, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [9aaaaec131](https://linux-hardware.org/?probe=9aaaaec131) | Aug 05, 2023 |
| HP            | 1588h                       | Desktop     | [1e041c2365](https://linux-hardware.org/?probe=1e041c2365) | Aug 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [96b8677500](https://linux-hardware.org/?probe=96b8677500) | Aug 05, 2023 |
| HP            | 1495                        | Desktop     | [17ae98cda8](https://linux-hardware.org/?probe=17ae98cda8) | Aug 05, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [cf49ab1496](https://linux-hardware.org/?probe=cf49ab1496) | Aug 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [49e694bb22](https://linux-hardware.org/?probe=49e694bb22) | Aug 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [effe3c3d6d](https://linux-hardware.org/?probe=effe3c3d6d) | Aug 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [4f67a219dc](https://linux-hardware.org/?probe=4f67a219dc) | Aug 04, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [91b8e07f0d](https://linux-hardware.org/?probe=91b8e07f0d) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [30b14bc4f6](https://linux-hardware.org/?probe=30b14bc4f6) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0e36ac41e4](https://linux-hardware.org/?probe=0e36ac41e4) | Aug 04, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 2100      | 47.48%  |
| Ubuntu 20.04                 | 273       | 6.17%   |
| BlackPanther 16.2            | 223       | 5.04%   |
| Ubuntu 18.04                 | 156       | 3.53%   |
| Ubuntu 22.04                 | 129       | 2.92%   |
| OpenMandriva 4.2             | 59        | 1.33%   |
| Debian 11                    | 51        | 1.15%   |
| OpenMandriva 4.3             | 39        | 0.88%   |
| Arch Rolling                 | 38        | 0.86%   |
| BlackPanther 22.1            | 35        | 0.79%   |
| Zorin 16                     | 33        | 0.75%   |
| Linux Mint 20.2              | 32        | 0.72%   |
| Linux Mint 21.1              | 30        | 0.68%   |
| Fedora 38                    | 25        | 0.57%   |
| Arch                         | 25        | 0.57%   |
| Linux Mint 19.3              | 24        | 0.54%   |
| ArcoLinux Rolling            | 24        | 0.54%   |
| Ubuntu 19.10                 | 23        | 0.52%   |
| OpenMandriva 23.03           | 22        | 0.5%    |
| Linux Mint 20.3              | 21        | 0.47%   |
| Linux Mint 20                | 21        | 0.47%   |
| Debian 10                    | 21        | 0.47%   |
| Xubuntu 20.04                | 20        | 0.45%   |
| Pop!_OS 22.04                | 20        | 0.45%   |
| Manjaro                      | 20        | 0.45%   |
| Kubuntu 20.04                | 20        | 0.45%   |
| Fedora 36                    | 20        | 0.45%   |
| Ubuntu 21.10                 | 19        | 0.43%   |
| Ubuntu 19.04                 | 19        | 0.43%   |
| OpenMandriva 23.08           | 19        | 0.43%   |
| KDE neon 20.04               | 19        | 0.43%   |
| Debian 12                    | 19        | 0.43%   |
| Ubuntu 21.04                 | 18        | 0.41%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 0.41%   |
| Xubuntu 18.04                | 17        | 0.38%   |
| Linux Mint 20.1              | 16        | 0.36%   |
| Fedora 37                    | 16        | 0.36%   |
| Ubuntu 23.04                 | 15        | 0.34%   |
| OpenMandriva 4.50            | 15        | 0.34%   |
| Kubuntu 22.04                | 15        | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| BlackPanther  | 2308      | 54.67%  |
| Ubuntu        | 660       | 15.63%  |
| OpenMandriva  | 183       | 4.33%   |
| Linux Mint    | 169       | 4%      |
| Fedora        | 112       | 2.65%   |
| Debian        | 104       | 2.46%   |
| Endless       | 85        | 2.01%   |
| Arch          | 62        | 1.47%   |
| Manjaro       | 58        | 1.37%   |
| Kubuntu       | 55        | 1.3%    |
| Xubuntu       | 47        | 1.11%   |
| Zorin         | 45        | 1.07%   |
| Pop!_OS       | 43        | 1.02%   |
| ArcoLinux     | 28        | 0.66%   |
| KDE neon      | 27        | 0.64%   |
| openSUSE      | 26        | 0.62%   |
| ROSA          | 22        | 0.52%   |
| Ubuntu MATE   | 19        | 0.45%   |
| Lubuntu       | 19        | 0.45%   |
| Ubuntu Unity  | 15        | 0.36%   |
| Kali          | 11        | 0.26%   |
| EndeavourOS   | 11        | 0.26%   |
| Elementary    | 11        | 0.26%   |
| Gentoo        | 10        | 0.24%   |
| SteamOS       | 9         | 0.21%   |
| Xero          | 7         | 0.17%   |
| Ubuntu Budgie | 6         | 0.14%   |
| LMDE          | 6         | 0.14%   |
| Raspbian      | 5         | 0.12%   |
| Nobara        | 5         | 0.12%   |
| MX            | 4         | 0.09%   |
| Clear Linux   | 4         | 0.09%   |
| Rocky Linux   | 3         | 0.07%   |
| Q4OS          | 3         | 0.07%   |
| Devuan        | 3         | 0.07%   |
| AlmaLinux     | 3         | 0.07%   |
| UbuntuDDE     | 2         | 0.05%   |
| Reborn OS     | 2         | 0.05%   |
| NixOS         | 2         | 0.05%   |
| Garuda Linux  | 2         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 1522      | 30.82%  |
| 5.6.14-desktop-2bP       | 690       | 13.97%  |
| 4.9.20-desktop-pae-1bP   | 206       | 4.17%   |
| 5.15.85-desktop-1bP      | 85        | 1.72%   |
| 5.1.15-desktop-1bP       | 85        | 1.72%   |
| 5.10.14-desktop-1omv4002 | 55        | 1.11%   |
| 5.4.0-42-generic         | 42        | 0.85%   |
| 5.16.7-desktop-1omv4003  | 37        | 0.75%   |
| 5.4.0-58-generic         | 27        | 0.55%   |
| 5.8.0-14-generic         | 25        | 0.51%   |
| 6.2.6-desktop-1omv2390   | 21        | 0.43%   |
| 5.4.0-52-generic         | 21        | 0.43%   |
| 6.3.8-desktop-1bP        | 19        | 0.38%   |
| 5.4.0-48-generic         | 19        | 0.38%   |
| 5.11.0-27-generic        | 19        | 0.38%   |
| 6.4.11-desktop-1omv2390  | 17        | 0.34%   |
| 5.3.0-28-generic         | 15        | 0.3%    |
| 5.15.0-58-generic        | 15        | 0.3%    |
| 5.15.0-56-generic        | 15        | 0.3%    |
| 6.1.1-desktop-1omv2290   | 14        | 0.28%   |
| 5.15.0-52-generic        | 14        | 0.28%   |
| 5.15.0-43-generic        | 14        | 0.28%   |
| 4.18.0-15-generic        | 14        | 0.28%   |
| 6.6.2-desktop-1omv2390   | 13        | 0.26%   |
| 5.4.0-54-generic         | 13        | 0.26%   |
| 5.4.0-40-generic         | 13        | 0.26%   |
| 5.4.0-19-generic         | 13        | 0.26%   |
| 5.11.0-34-generic        | 13        | 0.26%   |
| 5.4.0-29-generic         | 12        | 0.24%   |
| 4.15.0-43-generic        | 12        | 0.24%   |
| 6.3.3-desktop-1bP        | 11        | 0.22%   |
| 5.4.0-91-generic         | 11        | 0.22%   |
| 5.4.0-26-generic         | 11        | 0.22%   |
| 5.15.0-76-generic        | 11        | 0.22%   |
| 5.15.0-46-generic        | 11        | 0.22%   |
| 5.15.0-41-generic        | 11        | 0.22%   |
| 5.11.0-43-generic        | 11        | 0.22%   |
| 6.2.0-26-generic         | 10        | 0.2%    |
| 5.8.0-43-generic         | 10        | 0.2%    |
| 5.3.0-46-generic         | 10        | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.16 | 1522      | 31.74%  |
| 5.6.14  | 692       | 14.43%  |
| 5.4.0   | 343       | 7.15%   |
| 4.9.20  | 217       | 4.53%   |
| 5.15.0  | 191       | 3.98%   |
| 4.15.0  | 117       | 2.44%   |
| 5.11.0  | 104       | 2.17%   |
| 5.8.0   | 103       | 2.15%   |
| 5.15.85 | 86        | 1.79%   |
| 5.1.15  | 86        | 1.79%   |
| 5.13.0  | 84        | 1.75%   |
| 5.3.0   | 82        | 1.71%   |
| 5.10.0  | 62        | 1.29%   |
| 5.0.0   | 56        | 1.17%   |
| 5.10.14 | 55        | 1.15%   |
| 6.2.0   | 54        | 1.13%   |
| 5.19.0  | 50        | 1.04%   |
| 4.18.0  | 40        | 0.83%   |
| 5.16.7  | 38        | 0.79%   |
| 6.2.6   | 27        | 0.56%   |
| 6.1.0   | 25        | 0.52%   |
| 4.19.0  | 22        | 0.46%   |
| 6.3.8   | 21        | 0.44%   |
| 6.4.11  | 19        | 0.4%    |
| 6.1.1   | 18        | 0.38%   |
| 6.6.2   | 16        | 0.33%   |
| 6.2.9   | 12        | 0.25%   |
| 5.14.0  | 12        | 0.25%   |
| 6.5.0   | 11        | 0.23%   |
| 6.4.3   | 11        | 0.23%   |
| 6.3.3   | 11        | 0.23%   |
| 6.0.12  | 9         | 0.19%   |
| 5.16.0  | 9         | 0.19%   |
| 5.12.4  | 9         | 0.19%   |
| 4.13.0  | 9         | 0.19%   |
| 5.18.12 | 8         | 0.17%   |
| 4.4.0   | 8         | 0.17%   |
| 6.5.5   | 7         | 0.15%   |
| 5.13.13 | 7         | 0.15%   |
| 6.5.3   | 6         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 1561      | 32.8%   |
| 5.6     | 707       | 14.86%  |
| 5.4     | 366       | 7.69%   |
| 5.15    | 315       | 6.62%   |
| 4.9     | 230       | 4.83%   |
| 5.10    | 144       | 3.03%   |
| 5.11    | 124       | 2.61%   |
| 5.8     | 119       | 2.5%    |
| 6.2     | 117       | 2.46%   |
| 4.15    | 117       | 2.46%   |
| 5.13    | 96        | 2.02%   |
| 5.1     | 89        | 1.87%   |
| 5.3     | 88        | 1.85%   |
| 6.1     | 78        | 1.64%   |
| 5.19    | 73        | 1.53%   |
| 5.16    | 66        | 1.39%   |
| 5.0     | 56        | 1.18%   |
| 6.4     | 55        | 1.16%   |
| 6.3     | 44        | 0.92%   |
| 6.5     | 42        | 0.88%   |
| 6.6     | 30        | 0.63%   |
| 6.0     | 30        | 0.63%   |
| 5.18    | 29        | 0.61%   |
| 5.14    | 29        | 0.61%   |
| 5.9     | 25        | 0.53%   |
| 4.19    | 24        | 0.5%    |
| 5.12    | 23        | 0.48%   |
| 5.17    | 17        | 0.36%   |
| 5.7     | 16        | 0.34%   |
| 4.13    | 9         | 0.19%   |
| 4.4     | 8         | 0.17%   |
| 5.5     | 7         | 0.15%   |
| 4.7     | 5         | 0.11%   |
| 4.16    | 4         | 0.08%   |
| 6.7     | 2         | 0.04%   |
| 4.5     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |
| 6       | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3823      | 92.9%   |
| i686    | 281       | 6.83%   |
| armv7l  | 4         | 0.1%    |
| aarch64 | 4         | 0.1%    |
| armv6l  | 2         | 0.05%   |
| unknow  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 2586      | 61.35%  |
| GNOME           | 806       | 19.12%  |
| Unknown         | 289       | 6.86%   |
| XFCE            | 146       | 3.46%   |
| X-Cinnamon      | 134       | 3.18%   |
| MATE            | 69        | 1.64%   |
| KDE             | 40        | 0.95%   |
| LXQt            | 32        | 0.76%   |
| Cinnamon        | 30        | 0.71%   |
| Unity           | 15        | 0.36%   |
| KDE4            | 14        | 0.33%   |
| Pantheon        | 10        | 0.24%   |
| i3              | 8         | 0.19%   |
| Budgie          | 8         | 0.19%   |
| Deepin          | 7         | 0.17%   |
| LXDE            | 6         | 0.14%   |
| GNOME Flashback | 5         | 0.12%   |
| GNOME Classic   | 2         | 0.05%   |
| Trinity         | 1         | 0.02%   |
| sway            | 1         | 0.02%   |
| qtile           | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| Hyprland        | 1         | 0.02%   |
| Enlightenment   | 1         | 0.02%   |
| bspwm           | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3629      | 87.34%  |
| Wayland | 339       | 8.16%   |
| Unknown | 149       | 3.59%   |
| Tty     | 36        | 0.87%   |
| Web     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2600      | 61.92%  |
| Unknown | 878       | 20.91%  |
| GDM3    | 234       | 5.57%   |
| LightDM | 200       | 4.76%   |
| GDM     | 200       | 4.76%   |
| TDM     | 64        | 1.52%   |
| KDM     | 14        | 0.33%   |
| SLiM    | 6         | 0.14%   |
| XDM     | 3         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2481      | 59.27%  |
| hu_HU      | 1000      | 23.89%  |
| en_US      | 566       | 13.52%  |
| en_GB      | 59        | 1.41%   |
| C          | 33        | 0.79%   |
| de_DE      | 18        | 0.43%   |
| POSIX      | 4         | 0.1%    |
| ru_UA      | 3         | 0.07%   |
| ru_RU      | 3         | 0.07%   |
| en_AU      | 3         | 0.07%   |
| nl_NL      | 2         | 0.05%   |
| it_IT      | 2         | 0.05%   |
| hu_HU.UTF8 | 2         | 0.05%   |
| C.UTF8     | 2         | 0.05%   |
| fr_FR      | 1         | 0.02%   |
| fr_BE      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_IN      | 1         | 0.02%   |
| en_IL      | 1         | 0.02%   |
| en_AG      | 1         | 0.02%   |
| el_GR      | 1         | 0.02%   |
| de_AT      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2618      | 61.53%  |
| EFI  | 1637      | 38.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2387      | 53.2%   |
| Overlay | 1750      | 39%     |
| Btrfs   | 163       | 3.63%   |
| Unknown | 81        | 1.81%   |
| Tmpfs   | 57        | 1.27%   |
| Xfs     | 19        | 0.42%   |
| Zfs     | 11        | 0.25%   |
| Ext2    | 9         | 0.2%    |
| Ext3    | 7         | 0.16%   |
| F2fs    | 2         | 0.04%   |
| XXXXXXX | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 1844      | 42.85%  |
| GPT     | 1524      | 35.42%  |
| Unknown | 935       | 21.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3265      | 73.95%  |
| Yes       | 1150      | 26.05%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2392      | 55.05%  |
| Yes       | 1953      | 44.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 679       | 16.67%  |
| Hewlett-Packard         | 619       | 15.2%   |
| Dell                    | 579       | 14.22%  |
| Lenovo                  | 570       | 13.99%  |
| Gigabyte Technology     | 340       | 8.35%   |
| Acer                    | 272       | 6.68%   |
| ASRock                  | 269       | 6.6%    |
| MSI                     | 135       | 3.31%   |
| Fujitsu                 | 92        | 2.26%   |
| Fujitsu Siemens         | 67        | 1.64%   |
| Toshiba                 | 60        | 1.47%   |
| Samsung Electronics     | 42        | 1.03%   |
| Intel                   | 34        | 0.83%   |
| Packard Bell            | 30        | 0.74%   |
| Apple                   | 26        | 0.64%   |
| Medion                  | 23        | 0.56%   |
| eMachines               | 23        | 0.56%   |
| Unknown                 | 20        | 0.49%   |
| Sony                    | 17        | 0.42%   |
| Foxconn                 | 15        | 0.37%   |
| Valve                   | 9         | 0.22%   |
| Microsoft               | 8         | 0.2%    |
| Alcor                   | 8         | 0.2%    |
| Raspberry Pi Foundation | 7         | 0.17%   |
| Hungaro Flotta Kft      | 7         | 0.17%   |
| HUAWEI                  | 7         | 0.17%   |
| Pegatron                | 6         | 0.15%   |
| Supermicro              | 4         | 0.1%    |
| Insyde                  | 4         | 0.1%    |
| Biostar                 | 4         | 0.1%    |
| ZOTAC                   | 3         | 0.07%   |
| Timi                    | 3         | 0.07%   |
| Shuttle                 | 3         | 0.07%   |
| Huanan                  | 3         | 0.07%   |
| Clevo                   | 3         | 0.07%   |
| AOpen                   | 3         | 0.07%   |
| AMI                     | 3         | 0.07%   |
| ABIT                    | 3         | 0.07%   |
| VXL                     | 2         | 0.05%   |
| TUXEDO                  | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| HP 250 G1                        | 41        | 1.01%   |
| ASRock FM2A75M Pro4+             | 33        | 0.81%   |
| Unknown                          | 30        | 0.74%   |
| ASUS All Series                  | 28        | 0.69%   |
| Dell OptiPlex 3020               | 23        | 0.56%   |
| Dell Latitude E6410              | 19        | 0.47%   |
| HP Notebook                      | 14        | 0.34%   |
| HP 650                           | 13        | 0.32%   |
| Gigabyte G31M-ES2L               | 13        | 0.32%   |
| Dell OptiPlex 755                | 13        | 0.32%   |
| ASUS P5KPL-AM EPU                | 12        | 0.29%   |
| Lenovo IdeaPad 330-15IKB 81DE    | 11        | 0.27%   |
| Lenovo IdeaPad 100-15IBD 80QQ    | 11        | 0.27%   |
| Lenovo G50-45 80E3               | 11        | 0.27%   |
| HP 620                           | 11        | 0.27%   |
| Dell OptiPlex 780                | 11        | 0.27%   |
| Dell Latitude E6400              | 10        | 0.25%   |
| Valve Jupiter                    | 9         | 0.22%   |
| Lenovo ThinkPad T400 2768WGB     | 9         | 0.22%   |
| HP EliteBook 8460p               | 9         | 0.22%   |
| Gigabyte H61M-S1                 | 9         | 0.22%   |
| Dell Precision WorkStation T3500 | 9         | 0.22%   |
| Dell OptiPlex 760                | 9         | 0.22%   |
| Dell OptiPlex 7010               | 9         | 0.22%   |
| Dell Latitude 5480               | 9         | 0.22%   |
| MSI MS-7817                      | 8         | 0.2%    |
| HP Pavilion 15                   | 8         | 0.2%    |
| HP EliteBook 6930p               | 8         | 0.2%    |
| Dell Latitude E6530              | 8         | 0.2%    |
| Dell Latitude E6430              | 8         | 0.2%    |
| Dell Latitude E6420              | 8         | 0.2%    |
| Dell Inspiron 3542               | 8         | 0.2%    |
| Dell Inspiron 15-3567            | 8         | 0.2%    |
| ASUS X541NA                      | 8         | 0.2%    |
| ASRock G41M-VS3                  | 8         | 0.2%    |
| MSI MS-7C02                      | 7         | 0.17%   |
| Lenovo Z50-75 80EC               | 7         | 0.17%   |
| Lenovo G580 20150                | 7         | 0.17%   |
| Lenovo G550 20023                | 7         | 0.17%   |
| HP ProDesk 600 G2 SFF            | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 220       | 5.4%    |
| Dell Latitude           | 205       | 5.03%   |
| Acer Aspire             | 177       | 4.35%   |
| HP Compaq               | 146       | 3.58%   |
| Dell OptiPlex           | 137       | 3.36%   |
| Dell Inspiron           | 131       | 3.22%   |
| Lenovo IdeaPad          | 117       | 2.87%   |
| HP EliteBook            | 98        | 2.41%   |
| ASUS VivoBook           | 70        | 1.72%   |
| HP 250                  | 64        | 1.57%   |
| HP ProBook              | 60        | 1.47%   |
| Lenovo ThinkCentre      | 54        | 1.33%   |
| HP Pavilion             | 53        | 1.3%    |
| Toshiba Satellite       | 52        | 1.28%   |
| ASUS PRIME              | 49        | 1.2%    |
| Fujitsu ESPRIMO         | 41        | 1.01%   |
| Dell Vostro             | 38        | 0.93%   |
| Fujitsu LIFEBOOK        | 34        | 0.83%   |
| ASUS ROG                | 34        | 0.83%   |
| Fujitsu Siemens ESPRIMO | 33        | 0.81%   |
| ASRock FM2A75M          | 33        | 0.81%   |
| Packard Bell EasyNote   | 30        | 0.74%   |
| Dell Precision          | 30        | 0.74%   |
| Unknown                 | 30        | 0.74%   |
| ASUS All                | 28        | 0.69%   |
| ASUS TUF                | 25        | 0.61%   |
| Fujitsu Siemens AMILO   | 23        | 0.56%   |
| Acer TravelMate         | 23        | 0.56%   |
| HP Laptop               | 18        | 0.44%   |
| ASUS P5KPL-AM           | 18        | 0.44%   |
| HP EliteDesk            | 17        | 0.42%   |
| Acer Swift              | 17        | 0.42%   |
| ASUS ASUS               | 16        | 0.39%   |
| Acer Veriton            | 16        | 0.39%   |
| Gigabyte B450           | 15        | 0.37%   |
| HP Notebook             | 14        | 0.34%   |
| HP 650                  | 13        | 0.32%   |
| Gigabyte G31M-ES2L      | 13        | 0.32%   |
| ASUS ZenBook            | 13        | 0.32%   |
| Lenovo Yoga             | 12        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 371       | 9.11%   |
| 2013    | 367       | 9.01%   |
| 2012    | 350       | 8.59%   |
| 2010    | 342       | 8.4%    |
| 2018    | 306       | 7.51%   |
| 2014    | 298       | 7.32%   |
| 2009    | 276       | 6.78%   |
| 2008    | 272       | 6.68%   |
| 2017    | 227       | 5.57%   |
| 2015    | 221       | 5.43%   |
| 2007    | 201       | 4.93%   |
| 2016    | 196       | 4.81%   |
| 2019    | 170       | 4.17%   |
| 2020    | 155       | 3.81%   |
| 2021    | 106       | 2.6%    |
| 2006    | 84        | 2.06%   |
| 2022    | 61        | 1.5%    |
| 2005    | 30        | 0.74%   |
| 2023    | 20        | 0.49%   |
| Unknown | 13        | 0.32%   |
| 2004    | 4         | 0.1%    |
| 2003    | 3         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2281      | 56%     |
| Desktop        | 1665      | 40.88%  |
| Convertible    | 34        | 0.83%   |
| All in one     | 29        | 0.71%   |
| Mini pc        | 26        | 0.64%   |
| Tablet         | 15        | 0.37%   |
| Server         | 13        | 0.32%   |
| System on chip | 9         | 0.22%   |
| Phone          | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3946      | 96.46%  |
| Enabled  | 145       | 3.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4071      | 99.95%  |
| Yes  | 2         | 0.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1270      | 30.08%  |
| 4.01-8.0    | 924       | 21.89%  |
| 8.01-16.0   | 728       | 17.24%  |
| 16.01-24.0  | 476       | 11.27%  |
| 1.01-2.0    | 378       | 8.95%   |
| 32.01-64.0  | 185       | 4.38%   |
| 2.01-3.0    | 136       | 3.22%   |
| 24.01-32.0  | 46        | 1.09%   |
| 0.51-1.0    | 41        | 0.97%   |
| 64.01-256.0 | 34        | 0.81%   |
| 0.01-0.5    | 3         | 0.07%   |
| Unknown     | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1467      | 30.23%  |
| 0.51-1.0    | 1423      | 29.32%  |
| 0.01-0.5    | 721       | 14.86%  |
| 2.01-3.0    | 590       | 12.16%  |
| 3.01-4.0    | 284       | 5.85%   |
| 4.01-8.0    | 279       | 5.75%   |
| 8.01-16.0   | 72        | 1.48%   |
| 16.01-24.0  | 11        | 0.23%   |
| 32.01-64.0  | 2         | 0.04%   |
| 64.01-256.0 | 2         | 0.04%   |
| Unknown     | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2797      | 64.45%  |
| 2       | 980       | 22.58%  |
| 3       | 299       | 6.89%   |
| 4       | 122       | 2.81%   |
| 0       | 54        | 1.24%   |
| 5       | 50        | 1.15%   |
| 6       | 14        | 0.32%   |
| 8       | 7         | 0.16%   |
| 7       | 7         | 0.16%   |
| 9       | 4         | 0.09%   |
| 11      | 2         | 0.05%   |
| 10      | 2         | 0.05%   |
| 14      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2221      | 53.26%  |
| No        | 1949      | 46.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3764      | 92.3%   |
| No        | 314       | 7.7%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2803      | 68.08%  |
| No        | 1314      | 31.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2075      | 50.02%  |
| Yes       | 2073      | 49.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Hungary | 4073      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Budapest          | 1605      | 33.41%  |
| Pécs             | 98        | 2.04%   |
| Szeged            | 97        | 2.02%   |
| Debrecen          | 89        | 1.85%   |
| Miskolc           | 88        | 1.83%   |
| Győr             | 88        | 1.83%   |
| Tatabánya        | 83        | 1.73%   |
| Székesfehérvár | 61        | 1.27%   |
| Szombathely       | 60        | 1.25%   |
| Szigetszentmiklos | 58        | 1.21%   |
| Kecskemét        | 57        | 1.19%   |
| Zalaegerszeg      | 54        | 1.12%   |
| Érd              | 50        | 1.04%   |
| Nyiregyhaza       | 42        | 0.87%   |
| Veszprém         | 40        | 0.83%   |
| Szolnok           | 40        | 0.83%   |
| Szekszárd        | 38        | 0.79%   |
| Karcag            | 33        | 0.69%   |
| Gödöllő        | 32        | 0.67%   |
| Eger              | 30        | 0.62%   |
| Oroshaza          | 29        | 0.6%    |
| Toeroekbalint     | 27        | 0.56%   |
| Dunaújváros     | 27        | 0.56%   |
| Berettyóújfalu  | 26        | 0.54%   |
| Nagykanizsa       | 24        | 0.5%    |
| Salgotarjan       | 23        | 0.48%   |
| Hodmezovasarhely  | 22        | 0.46%   |
| Sopron            | 21        | 0.44%   |
| Gyomro            | 21        | 0.44%   |
| Siófok           | 20        | 0.42%   |
| Pomaz             | 20        | 0.42%   |
| Mosonmagyaróvár | 20        | 0.42%   |
| Hatvan            | 20        | 0.42%   |
| Toekoel           | 19        | 0.4%    |
| Szentendre        | 19        | 0.4%    |
| Esztergom         | 19        | 0.4%    |
| Cegled            | 19        | 0.4%    |
| Ajka              | 19        | 0.4%    |
| Papa              | 17        | 0.35%   |
| Békéscsaba      | 17        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 974       | 1858   | 16.32%  |
| Samsung Electronics         | 848       | 1437   | 14.21%  |
| Seagate                     | 822       | 1311   | 13.77%  |
| Kingston                    | 715       | 1239   | 11.98%  |
| Toshiba                     | 512       | 846    | 8.58%   |
| Hitachi                     | 265       | 377    | 4.44%   |
| HGST                        | 170       | 288    | 2.85%   |
| SanDisk                     | 162       | 241    | 2.71%   |
| Unknown                     | 149       | 217    | 2.5%    |
| A-DATA Technology           | 131       | 211    | 2.19%   |
| Intel                       | 110       | 167    | 1.84%   |
| SK hynix                    | 99        | 144    | 1.66%   |
| Crucial                     | 82        | 141    | 1.37%   |
| SPCC                        | 71        | 101    | 1.19%   |
| Fujitsu                     | 68        | 82     | 1.14%   |
| Micron Technology           | 62        | 87     | 1.04%   |
| Maxtor                      | 53        | 69     | 0.89%   |
| Apacer                      | 51        | 76     | 0.85%   |
| JMicron Technology          | 34        | 39     | 0.57%   |
| Intenso                     | 33        | 60     | 0.55%   |
| China                       | 33        | 53     | 0.55%   |
| OCZ                         | 27        | 33     | 0.45%   |
| LITEON                      | 27        | 35     | 0.45%   |
| Patriot                     | 25        | 50     | 0.42%   |
| Kingston Technology Company | 25        | 26     | 0.42%   |
| PNY                         | 24        | 43     | 0.4%    |
| Kingmax                     | 22        | 43     | 0.37%   |
| Gigabyte Technology         | 21        | 53     | 0.35%   |
| Transcend                   | 20        | 26     | 0.34%   |
| KIOXIA                      | 19        | 23     | 0.32%   |
| KingSpec                    | 16        | 18     | 0.27%   |
| Apple                       | 15        | 24     | 0.25%   |
| Verbatim                    | 13        | 27     | 0.22%   |
| Hewlett-Packard             | 13        | 17     | 0.22%   |
| Unknown                     | 13        | 18     | 0.22%   |
| Phison                      | 12        | 16     | 0.2%    |
| Team                        | 11        | 18     | 0.18%   |
| Silicon Motion              | 10        | 12     | 0.17%   |
| LITEONIT                    | 10        | 15     | 0.17%   |
| GOODRAM                     | 10        | 11     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 165       | 2.52%   |
| Kingston SA400S37120G 120GB SSD                     | 133       | 2.03%   |
| Kingston SV300S37A120G 120GB SSD                    | 93        | 1.42%   |
| Kingston SA400S37480G 480GB SSD                     | 76        | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 63        | 0.96%   |
| Toshiba DT01ACA100 1TB                              | 57        | 0.87%   |
| Seagate ST500DM002-1BD142 500GB                     | 55        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 54        | 0.82%   |
| Toshiba MQ01ABF050 500GB                            | 52        | 0.79%   |
| Samsung SSD 850 EVO 250GB                           | 49        | 0.75%   |
| Toshiba MQ01ABD100 1TB                              | 46        | 0.7%    |
| Seagate ST500LT012-1DG142 500GB                     | 41        | 0.63%   |
| Kingston SUV400S37120G 120GB SSD                    | 41        | 0.63%   |
| Toshiba DT01ACA050 500GB                            | 39        | 0.6%    |
| HGST HTS545032A7E380 320GB                          | 34        | 0.52%   |
| Samsung SSD 860 EVO 500GB                           | 32        | 0.49%   |
| A-DATA SU630 240GB SSD                              | 32        | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 31        | 0.47%   |
| Toshiba MQ04ABF100 1TB                              | 31        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 30        | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 30        | 0.46%   |
| Toshiba HDWD130 3TB                                 | 25        | 0.38%   |
| SPCC Solid State Disk 256GB                         | 25        | 0.38%   |
| HGST HTS721010A9E630 1TB                            | 25        | 0.38%   |
| Seagate ST9320325AS 320GB                           | 24        | 0.37%   |
| Seagate ST380815AS 80GB                             | 24        | 0.37%   |
| Samsung HD502HJ 500GB                               | 24        | 0.37%   |
| JMicron Generic 250GB                               | 23        | 0.35%   |
| Toshiba HDWD110 1TB                                 | 22        | 0.34%   |
| Toshiba DT01ACA200 2TB                              | 22        | 0.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 22        | 0.34%   |
| A-DATA SU700 120GB SSD                              | 22        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 21        | 0.32%   |
| Kingston SHFS37A120G 120GB SSD                      | 21        | 0.32%   |
| Samsung SSD 850 EVO 500GB                           | 20        | 0.31%   |
| Kingston SV300S37A240G 240GB SSD                    | 20        | 0.31%   |
| SPCC Solid State Disk 128GB                         | 19        | 0.29%   |
| Seagate ST9500325AS 500GB                           | 19        | 0.29%   |
| Unknown MMC Card  32GB                              | 18        | 0.27%   |
| Kingston SV300S37A60G 64GB SSD                      | 18        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 865       | 1628   | 28.68%  |
| Seagate             | 806       | 1284   | 26.72%  |
| Toshiba             | 441       | 735    | 14.62%  |
| Samsung Electronics | 287       | 453    | 9.52%   |
| Hitachi             | 265       | 377    | 8.79%   |
| HGST                | 170       | 288    | 5.64%   |
| Fujitsu             | 68        | 82     | 2.25%   |
| Maxtor              | 53        | 69     | 1.76%   |
| Unknown             | 14        | 21     | 0.46%   |
| Hewlett-Packard     | 7         | 7      | 0.23%   |
| HGST HTS            | 6         | 11     | 0.2%    |
| USB3.0              | 4         | 8      | 0.13%   |
| QUANTUM             | 4         | 4      | 0.13%   |
| IBM/Hitachi         | 4         | 5      | 0.13%   |
| Apple               | 3         | 5      | 0.1%    |
| WD MediaMax         | 2         | 4      | 0.07%   |
| TO Exter            | 2         | 2      | 0.07%   |
| Initio              | 2         | 3      | 0.07%   |
| ICY BOX             | 2         | 4      | 0.07%   |
| External            | 2         | 3      | 0.07%   |
| USB                 | 1         | 1      | 0.03%   |
| Space ke            | 1         | 1      | 0.03%   |
| JMicron Technology  | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| CSD                 | 1         | 2      | 0.03%   |
| AXAGON              | 1         | 1      | 0.03%   |
| ASMT                | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 652       | 1112   | 30.51%  |
| Samsung Electronics | 388       | 644    | 18.16%  |
| A-DATA Technology   | 120       | 193    | 5.62%   |
| SanDisk             | 105       | 148    | 4.91%   |
| WDC                 | 100       | 180    | 4.68%   |
| Crucial             | 76        | 133    | 3.56%   |
| Intel               | 72        | 113    | 3.37%   |
| SPCC                | 59        | 87     | 2.76%   |
| Apacer              | 49        | 72     | 2.29%   |
| SK hynix            | 43        | 71     | 2.01%   |
| Micron Technology   | 42        | 61     | 1.97%   |
| China               | 33        | 53     | 1.54%   |
| Toshiba             | 30        | 45     | 1.4%    |
| Intenso             | 30        | 56     | 1.4%    |
| OCZ                 | 27        | 33     | 1.26%   |
| LITEON              | 26        | 32     | 1.22%   |
| PNY                 | 24        | 43     | 1.12%   |
| JMicron Technology  | 24        | 28     | 1.12%   |
| Patriot             | 22        | 45     | 1.03%   |
| Kingmax             | 22        | 43     | 1.03%   |
| Transcend           | 19        | 21     | 0.89%   |
| Gigabyte Technology | 17        | 47     | 0.8%    |
| KingSpec            | 15        | 17     | 0.7%    |
| Verbatim            | 12        | 26     | 0.56%   |
| Team                | 10        | 17     | 0.47%   |
| LITEONIT            | 10        | 15     | 0.47%   |
| GOODRAM             | 10        | 11     | 0.47%   |
| Corsair             | 9         | 11     | 0.42%   |
| ASMT                | 7         | 9      | 0.33%   |
| Apple               | 7         | 12     | 0.33%   |
| Netac               | 6         | 12     | 0.28%   |
| Hewlett-Packard     | 4         | 5      | 0.19%   |
| Unknown             | 3         | 6      | 0.14%   |
| SATAFIRM            | 3         | 3      | 0.14%   |
| Leven               | 3         | 3      | 0.14%   |
| KingDian            | 3         | 3      | 0.14%   |
| HS-SSD-C100         | 3         | 3      | 0.14%   |
| BHT                 | 3         | 3      | 0.14%   |
| AMD                 | 3         | 3      | 0.14%   |
| 2-Power             | 3         | 5      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2540      | 5003   | 48.35%  |
| SSD     | 1870      | 3492   | 35.6%   |
| NVMe    | 639       | 1050   | 12.16%  |
| MMC     | 143       | 216    | 2.72%   |
| Unknown | 61        | 83     | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3568      | 8281   | 78.75%  |
| NVMe | 639       | 1049   | 14.1%   |
| SAS  | 181       | 298    | 3.99%   |
| MMC  | 143       | 216    | 3.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 3079      | 6002   | 70.81%  |
| 0.51-1.0        | 935       | 1708   | 21.5%   |
| 1.01-2.0        | 184       | 332    | 4.23%   |
| 2.01-3.0        | 64        | 211    | 1.47%   |
| 3.01-4.0        | 52        | 149    | 1.2%    |
| 4.01-10.0       | 25        | 58     | 0.57%   |
| 10.01-20.0      | 7         | 33     | 0.16%   |
| More than 100.0 | 2         | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1595      | 33.54%  |
| 101-250        | 1040      | 21.87%  |
| 251-500        | 676       | 14.21%  |
| 501-1000       | 347       | 7.3%    |
| 51-100         | 339       | 7.13%   |
| 1-20           | 229       | 4.81%   |
| 1001-2000      | 190       | 3.99%   |
| 21-50          | 185       | 3.89%   |
| More than 3000 | 86        | 1.81%   |
| 2001-3000      | 69        | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1662      | 34.35%  |
| Unknown        | 1595      | 32.97%  |
| 21-50          | 472       | 9.76%   |
| 51-100         | 354       | 7.32%   |
| 101-250        | 311       | 6.43%   |
| 251-500        | 172       | 3.56%   |
| 501-1000       | 143       | 2.96%   |
| 1001-2000      | 82        | 1.69%   |
| More than 3000 | 31        | 0.64%   |
| 2001-3000      | 16        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB         | 31        | 50     | 2.69%   |
| Kingston SV300S37A120G 120GB SSD   | 23        | 27     | 1.99%   |
| HGST HTS545050A7E680 500GB         | 20        | 30     | 1.73%   |
| Seagate ST500DM002-1BD142 500GB    | 19        | 35     | 1.65%   |
| A-DATA Technology SU630 240GB SSD  | 19        | 29     | 1.65%   |
| Seagate ST500LT012-9WS142 500GB    | 13        | 15     | 1.13%   |
| Seagate ST500LT012-1DG142 500GB    | 13        | 20     | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 13        | 18     | 1.13%   |
| Seagate ST9320325AS 320GB          | 12        | 26     | 1.04%   |
| Toshiba MQ01ABF050 500GB           | 11        | 28     | 0.95%   |
| Toshiba DT01ACA050 500GB           | 11        | 14     | 0.95%   |
| Samsung Electronics HD103UJ 1TB    | 10        | 23     | 0.87%   |
| Seagate ST9500325AS 500GB          | 9         | 18     | 0.78%   |
| Seagate ST9250315AS 250GB          | 9         | 14     | 0.78%   |
| Seagate ST9320423AS 320GB          | 8         | 9      | 0.69%   |
| Hitachi HTS545050B9A300 500GB      | 8         | 13     | 0.69%   |
| HGST HTS545050A7E380 500GB         | 8         | 12     | 0.69%   |
| HGST HTS541010A9E680 1TB           | 8         | 19     | 0.69%   |
| WDC WD5000AADS-00S9B0 500GB        | 7         | 8      | 0.61%   |
| Toshiba MQ01ABD100 1TB             | 7         | 9      | 0.61%   |
| Toshiba DT01ACA100 1TB             | 7         | 14     | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB     | 7         | 8      | 0.61%   |
| Samsung Electronics HM160HI 160GB  | 7         | 8      | 0.61%   |
| Hitachi HTS545050A7E380 500GB      | 7         | 10     | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB        | 6         | 6      | 0.52%   |
| Toshiba MQ01ABD050 500GB           | 6         | 6      | 0.52%   |
| Samsung Electronics HD321KJ 320GB  | 6         | 6      | 0.52%   |
| Samsung Electronics HD161HJ 160GB  | 6         | 6      | 0.52%   |
| Hitachi HTS545016B9A300 160GB      | 6         | 6      | 0.52%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 5         | 9      | 0.43%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 5         | 11     | 0.43%   |
| Seagate ST980811AS 80GB            | 5         | 5      | 0.43%   |
| Seagate ST500LM000-SSHD-8GB        | 5         | 6      | 0.43%   |
| Seagate ST3250318AS 250GB          | 5         | 9      | 0.43%   |
| Seagate ST3160815AS 160GB          | 5         | 6      | 0.43%   |
| Samsung Electronics HD502HJ 500GB  | 5         | 8      | 0.43%   |
| Samsung Electronics HD103SI 1TB    | 5         | 5      | 0.43%   |
| Maxtor 6Y080M0 82GB                | 5         | 6      | 0.43%   |
| Kingston SA400S37120G 120GB SSD    | 5         | 9      | 0.43%   |
| Hitachi HTS723232A7A364 320GB      | 5         | 5      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 247       | 359    | 22.07%  |
| WDC                 | 228       | 364    | 20.38%  |
| Samsung Electronics | 124       | 191    | 11.08%  |
| Hitachi             | 117       | 177    | 10.46%  |
| Toshiba             | 110       | 173    | 9.83%   |
| HGST                | 81        | 129    | 7.24%   |
| Kingston            | 56        | 72     | 5%      |
| Maxtor              | 29        | 43     | 2.59%   |
| A-DATA Technology   | 28        | 44     | 2.5%    |
| Fujitsu             | 25        | 33     | 2.23%   |
| Intel               | 21        | 36     | 1.88%   |
| SK hynix            | 10        | 14     | 0.89%   |
| SanDisk             | 4         | 5      | 0.36%   |
| Intenso             | 4         | 4      | 0.36%   |
| IBM/Hitachi         | 3         | 3      | 0.27%   |
| Hewlett-Packard     | 3         | 3      | 0.27%   |
| WD MediaMax         | 2         | 4      | 0.18%   |
| LITEON              | 2         | 2      | 0.18%   |
| KingSpec            | 2         | 2      | 0.18%   |
| Kingmax             | 2         | 2      | 0.18%   |
| China               | 2         | 2      | 0.18%   |
| Apacer              | 2         | 3      | 0.18%   |
| SPCC                | 1         | 1      | 0.09%   |
| SATAFIRM            | 1         | 1      | 0.09%   |
| R580                | 1         | 1      | 0.09%   |
| QUANTUM             | 1         | 1      | 0.09%   |
| Patriot             | 1         | 1      | 0.09%   |
| OCZ-AGIL            | 1         | 1      | 0.09%   |
| OCZ                 | 1         | 3      | 0.09%   |
| Micron Technology   | 1         | 1      | 0.09%   |
| Leven               | 1         | 1      | 0.09%   |
| JMicron Technology  | 1         | 1      | 0.09%   |
| Initio              | 1         | 2      | 0.09%   |
| ICY BOX             | 1         | 2      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| CSD                 | 1         | 2      | 0.09%   |
| Crucial             | 1         | 1      | 0.09%   |
| ASMT                | 1         | 1      | 0.09%   |
| Apple               | 1         | 6      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 247       | 359    | 26%     |
| WDC                 | 222       | 357    | 23.37%  |
| Hitachi             | 117       | 177    | 12.32%  |
| Samsung Electronics | 113       | 168    | 11.89%  |
| Toshiba             | 103       | 158    | 10.84%  |
| HGST                | 81        | 129    | 8.53%   |
| Maxtor              | 29        | 43     | 3.05%   |
| Fujitsu             | 25        | 33     | 2.63%   |
| IBM/Hitachi         | 3         | 3      | 0.32%   |
| WD MediaMax         | 2         | 4      | 0.21%   |
| Hewlett-Packard     | 2         | 2      | 0.21%   |
| QUANTUM             | 1         | 1      | 0.11%   |
| Initio              | 1         | 2      | 0.11%   |
| ICY BOX             | 1         | 2      | 0.11%   |
| ExcelStor           | 1         | 1      | 0.11%   |
| CSD                 | 1         | 2      | 0.11%   |
| ASMT                | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 868       | 1442   | 83.86%  |
| SSD     | 158       | 240    | 15.27%  |
| NVMe    | 8         | 9      | 0.77%   |
| Unknown | 1         | 1      | 0.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB  | 2         | 3      | 8.33%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 3      | 8.33%   |
| Zheino CHN-NGFFNV2280-256 256GB    | 1         | 1      | 4.17%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.17%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.17%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.17%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.17%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.17%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.17%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 4.17%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.17%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 4.17%   |
| Seagate ST380815AS 80GB            | 1         | 3      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.17%   |
| Samsung Electronics SP0802N 80GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.17%   |
| Samsung Electronics HD204UI 2TB    | 1         | 1      | 4.17%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 4.17%   |
| Hitachi HDS721075CLA332 752GB      | 1         | 1      | 4.17%   |
| Hewlett-Packard SSD EX900 250GB    | 1         | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 9      | 29.17%  |
| WDC                 | 6         | 12     | 25%     |
| Toshiba             | 3         | 3      | 12.5%   |
| Seagate             | 3         | 5      | 12.5%   |
| Hitachi             | 2         | 2      | 8.33%   |
| Zheino              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| Hewlett-Packard     | 1         | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2446      | 5641   | 51.89%  |
| Detected | 1240      | 2477   | 26.3%   |
| Malfunc  | 1004      | 1692   | 21.3%   |
| Failed   | 24        | 34     | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3010      | 63.18%  |
| AMD                              | 737       | 15.47%  |
| Samsung Electronics              | 229       | 4.81%   |
| Kingston Technology Company      | 97        | 2.04%   |
| SanDisk                          | 85        | 1.78%   |
| JMicron Technology               | 84        | 1.76%   |
| Nvidia                           | 79        | 1.66%   |
| ASMedia Technology               | 67        | 1.41%   |
| SK hynix                         | 53        | 1.11%   |
| Toshiba America Info Systems     | 39        | 0.82%   |
| Marvell Technology Group         | 39        | 0.82%   |
| Phison Electronics               | 37        | 0.78%   |
| KIOXIA                           | 25        | 0.52%   |
| VIA Technologies                 | 21        | 0.44%   |
| Silicon Motion                   | 21        | 0.44%   |
| Micron Technology                | 21        | 0.44%   |
| ADATA Technology                 | 16        | 0.34%   |
| Silicon Integrated Systems [SiS] | 15        | 0.31%   |
| Silicon Image                    | 15        | 0.31%   |
| LSI Logic / Symbios Logic        | 12        | 0.25%   |
| Micron/Crucial Technology        | 8         | 0.17%   |
| Solid State Storage Technology   | 7         | 0.15%   |
| Realtek Semiconductor            | 7         | 0.15%   |
| Integrated Technology Express    | 5         | 0.1%    |
| Seagate Technology               | 4         | 0.08%   |
| Broadcom / LSI                   | 4         | 0.08%   |
| Apple                            | 4         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| Union Memory (Shenzhen)          | 2         | 0.04%   |
| Solidigm                         | 2         | 0.04%   |
| Lite-On Technology               | 2         | 0.04%   |
| HighPoint Technologies           | 2         | 0.04%   |
| Hewlett-Packard                  | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| TenaFe                           | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 440       | 7.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 213       | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 204       | 3.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 197       | 3.32%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 188       | 3.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 174       | 2.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 159       | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 140       | 2.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 131       | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 123       | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 109       | 1.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 104       | 1.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 101       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 97        | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 95        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 88        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 83        | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 82        | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 81        | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 81        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 75        | 1.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 74        | 1.25%   |
| AMD FCH IDE Controller                                                                  | 73        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 68        | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 65        | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 59        | 1%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 58        | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 54        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 54        | 0.91%   |
| Intel SATA Controller [RAID mode]                                                       | 53        | 0.89%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 53        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 52        | 0.88%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 51        | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 49        | 0.83%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 48        | 0.81%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 48        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 48        | 0.81%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 41        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 40        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 40        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3030      | 59.96%  |
| IDE  | 1078      | 21.33%  |
| NVMe | 646       | 12.78%  |
| RAID | 279       | 5.52%   |
| SAS  | 12        | 0.24%   |
| SCSI | 8         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3188      | 78.27%  |
| AMD          | 871       | 21.38%  |
| ARM          | 10        | 0.25%   |
| CentaurHauls | 4         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 50        | 1.22%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 1.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 41        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz           | 40        | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 38        | 0.93%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 36        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 30        | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 28        | 0.68%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 28        | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 0.66%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 25        | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 24        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 23        | 0.56%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 23        | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 23        | 0.56%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 22        | 0.54%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 22        | 0.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 21        | 0.51%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 21        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 21        | 0.51%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 21        | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 20        | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 19        | 0.46%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 19        | 0.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 19        | 0.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 19        | 0.46%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 18        | 0.44%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 18        | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 17        | 0.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 17        | 0.42%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 17        | 0.42%   |
| AMD FX-6300 Six-Core Processor              | 17        | 0.42%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 16        | 0.39%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16        | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 16        | 0.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 16        | 0.39%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16        | 0.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 16        | 0.39%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 16        | 0.39%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 862       | 21.09%  |
| Intel Core i3           | 467       | 11.43%  |
| Intel Core i7           | 387       | 9.47%   |
| Intel Core 2 Duo        | 350       | 8.56%   |
| Intel Celeron           | 287       | 7.02%   |
| Intel Pentium           | 165       | 4.04%   |
| AMD Ryzen 5             | 126       | 3.08%   |
| Other                   | 121       | 2.96%   |
| Intel Pentium Dual-Core | 104       | 2.54%   |
| Intel Atom              | 99        | 2.42%   |
| Intel Xeon              | 86        | 2.1%    |
| AMD A8                  | 81        | 1.98%   |
| AMD Ryzen 7             | 77        | 1.88%   |
| Intel Core 2 Quad       | 58        | 1.42%   |
| AMD FX                  | 58        | 1.42%   |
| AMD A4                  | 52        | 1.27%   |
| Intel Pentium Dual      | 49        | 1.2%    |
| Intel Core 2            | 49        | 1.2%    |
| AMD Ryzen 3             | 43        | 1.05%   |
| AMD Athlon II X2        | 42        | 1.03%   |
| AMD Athlon 64 X2        | 33        | 0.81%   |
| AMD A6                  | 33        | 0.81%   |
| AMD A10                 | 30        | 0.73%   |
| AMD Phenom II X4        | 23        | 0.56%   |
| AMD E                   | 23        | 0.56%   |
| Intel Pentium 4         | 22        | 0.54%   |
| Intel Genuine           | 22        | 0.54%   |
| AMD E1                  | 19        | 0.46%   |
| AMD Ryzen 9             | 18        | 0.44%   |
| Intel Pentium Silver    | 17        | 0.42%   |
| AMD E2                  | 17        | 0.42%   |
| Intel Celeron Dual-Core | 14        | 0.34%   |
| Intel Celeron M         | 13        | 0.32%   |
| Intel Pentium D         | 12        | 0.29%   |
| AMD Athlon              | 12        | 0.29%   |
| AMD Sempron             | 11        | 0.27%   |
| AMD Athlon II X4        | 11        | 0.27%   |
| AMD Athlon Dual Core    | 11        | 0.27%   |
| Intel Pentium M         | 9         | 0.22%   |
| AMD Athlon X4           | 9         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2328      | 56.82%  |
| 4       | 1082      | 26.41%  |
| 1       | 239       | 5.83%   |
| 6       | 236       | 5.76%   |
| 8       | 120       | 2.93%   |
| 3       | 30        | 0.73%   |
| 12      | 22        | 0.54%   |
| 10      | 15        | 0.37%   |
| 16      | 10        | 0.24%   |
| 14      | 6         | 0.15%   |
| 18      | 2         | 0.05%   |
| Unknown | 2         | 0.05%   |
| 36      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 9       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4054      | 99.48%  |
| 2       | 20        | 0.49%   |
| Unknown | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2093      | 51.09%  |
| 1       | 2002      | 48.87%  |
| Unknown | 2         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3976      | 97.31%  |
| 32-bit         | 62        | 1.52%   |
| Unknown        | 48        | 1.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 667       | 15.71%  |
| 0x1067a    | 339       | 7.99%   |
| 0x206a7    | 314       | 7.4%    |
| 0x306a9    | 277       | 6.53%   |
| 0x306c3    | 199       | 4.69%   |
| 0x20655    | 125       | 2.94%   |
| 0x6fd      | 106       | 2.5%    |
| 0x40651    | 92        | 2.17%   |
| 0x06001119 | 91        | 2.14%   |
| 0x406e3    | 82        | 1.93%   |
| 0x10676    | 82        | 1.93%   |
| 0x306d4    | 80        | 1.88%   |
| 0x506e3    | 72        | 1.7%    |
| 0x806e9    | 71        | 1.67%   |
| 0x906ea    | 69        | 1.63%   |
| 0x010000c8 | 64        | 1.51%   |
| 0x906e9    | 60        | 1.41%   |
| 0x806ea    | 58        | 1.37%   |
| 0x6fb      | 54        | 1.27%   |
| 0x406c4    | 53        | 1.25%   |
| 0x806ec    | 44        | 1.04%   |
| 0x20652    | 44        | 1.04%   |
| 0x30678    | 39        | 0.92%   |
| 0x106ca    | 38        | 0.9%    |
| 0x806c1    | 36        | 0.85%   |
| 0x706a1    | 36        | 0.85%   |
| 0x05000119 | 34        | 0.8%    |
| 0x0800820d | 33        | 0.78%   |
| 0x506c9    | 31        | 0.73%   |
| 0x6f2      | 28        | 0.66%   |
| 0x06000852 | 27        | 0.64%   |
| 0x07030105 | 26        | 0.61%   |
| 0x06003106 | 26        | 0.61%   |
| 0x406c3    | 25        | 0.59%   |
| 0x0700010f | 25        | 0.59%   |
| 0x6f6      | 24        | 0.57%   |
| 0x0a50000c | 24        | 0.57%   |
| 0x106c2    | 23        | 0.54%   |
| 0x806eb    | 22        | 0.52%   |
| 0x706e5    | 22        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 449       | 11.01%  |
| KabyLake         | 439       | 10.77%  |
| SandyBridge      | 349       | 8.56%   |
| Haswell          | 345       | 8.46%   |
| IvyBridge        | 306       | 7.51%   |
| Core             | 247       | 6.06%   |
| Westmere         | 200       | 4.91%   |
| Skylake          | 196       | 4.81%   |
| Piledriver       | 141       | 3.46%   |
| Silvermont       | 132       | 3.24%   |
| K10              | 126       | 3.09%   |
| Broadwell        | 95        | 2.33%   |
| Zen 2            | 80        | 1.96%   |
| K8 Hammer        | 70        | 1.72%   |
| Bonnell          | 69        | 1.69%   |
| Zen+             | 66        | 1.62%   |
| Unknown          | 64        | 1.57%   |
| Zen 3            | 61        | 1.5%    |
| Bobcat           | 54        | 1.32%   |
| Zen              | 51        | 1.25%   |
| Goldmont plus    | 50        | 1.23%   |
| NetBurst         | 48        | 1.18%   |
| TigerLake        | 46        | 1.13%   |
| Puma             | 43        | 1.05%   |
| Excavator        | 41        | 1.01%   |
| IceLake          | 40        | 0.98%   |
| Goldmont         | 39        | 0.96%   |
| Steamroller      | 38        | 0.93%   |
| P6               | 33        | 0.81%   |
| Nehalem          | 32        | 0.78%   |
| Jaguar           | 30        | 0.74%   |
| CometLake        | 30        | 0.74%   |
| Alderlake Hybrid | 26        | 0.64%   |
| K10 Llano        | 19        | 0.47%   |
| Bulldozer        | 9         | 0.22%   |
| K8 & K10 hybrid  | 7         | 0.17%   |
| Tremont          | 4         | 0.1%    |
| K6               | 1         | 0.02%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2414      | 51.21%  |
| Nvidia                                       | 1159      | 24.59%  |
| AMD                                          | 1107      | 23.48%  |
| VIA Technologies                             | 13        | 0.28%   |
| Silicon Integrated Systems [SiS]             | 8         | 0.17%   |
| ASPEED Technology                            | 5         | 0.11%   |
| Matrox Electronics Systems                   | 4         | 0.08%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.04%   |
| ATI Technologies                             | 2         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 258       | 5.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 185       | 3.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 158       | 3.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 116       | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 102       | 2.05%   |
| Intel HD Graphics 620                                                                    | 91        | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 90        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 88        | 1.77%   |
| Intel HD Graphics 5500                                                                   | 84        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 82        | 1.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 77        | 1.55%   |
| Intel UHD Graphics 620                                                                   | 68        | 1.37%   |
| Intel HD Graphics 530                                                                    | 68        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 64        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 60        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 60        | 1.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 59        | 1.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 57        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 55        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 53        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 50        | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 44        | 0.88%   |
| Nvidia GT218 [GeForce 210]                                                               | 42        | 0.84%   |
| Intel HD Graphics 630                                                                    | 41        | 0.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 40        | 0.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 38        | 0.76%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 38        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 37        | 0.74%   |
| AMD Richland [Radeon HD 8570D]                                                           | 37        | 0.74%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 37        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 0.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 36        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 35        | 0.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 0.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 35        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 33        | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 32        | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 0.62%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 31        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1848      | 44.73%  |
| 1 x AMD                  | 845       | 20.46%  |
| 1 x Nvidia               | 701       | 16.97%  |
| Intel + Nvidia           | 413       | 10%     |
| Intel + AMD              | 115       | 2.78%   |
| 2 x AMD                  | 109       | 2.64%   |
| AMD + Nvidia             | 39        | 0.94%   |
| 1 x VIA                  | 13        | 0.31%   |
| Other                    | 11        | 0.27%   |
| 2 x Intel                | 9         | 0.22%   |
| 1 x SiS                  | 8         | 0.19%   |
| 2 x Nvidia               | 6         | 0.15%   |
| 1 x Matrox               | 4         | 0.1%    |
| 1 x ASPEED               | 4         | 0.1%    |
| AMD + XGI                | 2         | 0.05%   |
| 1 x Intel + 3 x AMD      | 1         | 0.02%   |
| Intel + 2 x Nvidia       | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |
| AMD + ASPEED             | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3692      | 89.52%  |
| Proprietary | 301       | 7.3%    |
| Unknown     | 131       | 3.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2122      | 50.02%  |
| 0.01-0.5   | 730       | 17.21%  |
| 1.01-2.0   | 544       | 12.82%  |
| 0.51-1.0   | 469       | 11.06%  |
| 3.01-4.0   | 209       | 4.93%   |
| 7.01-8.0   | 80        | 1.89%   |
| 5.01-6.0   | 52        | 1.23%   |
| 2.01-3.0   | 23        | 0.54%   |
| 8.01-16.0  | 10        | 0.24%   |
| 16.01-24.0 | 3         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 736       | 17.33%  |
| LG Display              | 493       | 11.61%  |
| AU Optronics            | 469       | 11.05%  |
| Goldstar                | 349       | 8.22%   |
| Chimei Innolux          | 304       | 7.16%   |
| BOE                     | 263       | 6.19%   |
| Dell                    | 164       | 3.86%   |
| Chi Mei Optoelectronics | 116       | 2.73%   |
| Lenovo                  | 112       | 2.64%   |
| Philips                 | 108       | 2.54%   |
| BenQ                    | 108       | 2.54%   |
| Ancor Communications    | 105       | 2.47%   |
| Hewlett-Packard         | 98        | 2.31%   |
| Acer                    | 98        | 2.31%   |
| Fujitsu Siemens         | 53        | 1.25%   |
| AOC                     | 50        | 1.18%   |
| LG Philips              | 38        | 0.89%   |
| HannStar                | 33        | 0.78%   |
| InfoVision              | 29        | 0.68%   |
| Sony                    | 27        | 0.64%   |
| ASUSTek Computer        | 26        | 0.61%   |
| LG Electronics          | 25        | 0.59%   |
| Eizo                    | 25        | 0.59%   |
| Vestel Elektronik       | 23        | 0.54%   |
| Apple                   | 23        | 0.54%   |
| PANDA                   | 21        | 0.49%   |
| NEC Computers           | 20        | 0.47%   |
| HKC                     | 17        | 0.4%    |
| ViewSonic               | 16        | 0.38%   |
| Toshiba                 | 15        | 0.35%   |
| Medion                  | 14        | 0.33%   |
| IBM                     | 14        | 0.33%   |
| CPT                     | 14        | 0.33%   |
| Unknown                 | 13        | 0.31%   |
| Sharp                   | 13        | 0.31%   |
| Panasonic               | 12        | 0.28%   |
| Belinea                 | 12        | 0.28%   |
| InnoLux Display         | 10        | 0.24%   |
| Arnos Instruments       | 10        | 0.24%   |
| Quanta Display          | 8         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 50        | 1.15%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 41        | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 38        | 0.87%   |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 32        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 26        | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.55%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 23        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 23        | 0.53%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 23        | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 20        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 0.41%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 17        | 0.39%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 16        | 0.37%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 15        | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 15        | 0.34%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 14        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.32%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 13        | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 13        | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 13        | 0.3%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 13        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 13        | 0.3%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 12        | 0.28%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 12        | 0.28%   |
| HKC '' HKC1850 1360x768 304x228mm 15.0-inch                              | 12        | 0.28%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.28%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 12        | 0.28%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.25%   |
| HannStar Hanns.G HQ191 HSD0013 1280x1024 376x301mm 19.0-inch             | 11        | 0.25%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 11        | 0.25%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.25%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 11        | 0.25%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 11        | 0.25%   |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch          | 11        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1482      | 36.01%  |
| 1366x768 (WXGA)    | 1003      | 24.37%  |
| 1280x1024 (SXGA)   | 301       | 7.31%   |
| 1280x800 (WXGA)    | 183       | 4.45%   |
| 1600x900 (HD+)     | 180       | 4.37%   |
| 1440x900 (WXGA+)   | 179       | 4.35%   |
| 1680x1050 (WSXGA+) | 164       | 3.99%   |
| 3840x2160 (4K)     | 143       | 3.48%   |
| 1920x1200 (WUXGA)  | 67        | 1.63%   |
| 2560x1440 (QHD)    | 65        | 1.58%   |
| 1360x768           | 43        | 1.04%   |
| 1024x768 (XGA)     | 43        | 1.04%   |
| 2560x1080          | 42        | 1.02%   |
| 1024x600           | 41        | 1%      |
| Unknown            | 22        | 0.53%   |
| 1920x540           | 18        | 0.44%   |
| 2880x1800          | 15        | 0.36%   |
| 2560x1600          | 15        | 0.36%   |
| 3840x1080          | 10        | 0.24%   |
| 1600x1200          | 10        | 0.24%   |
| 800x1280           | 8         | 0.19%   |
| 3440x1440          | 8         | 0.19%   |
| 1280x720 (HD)      | 7         | 0.17%   |
| 2288x1287          | 6         | 0.15%   |
| 1920x1280          | 5         | 0.12%   |
| 1400x1050          | 5         | 0.12%   |
| 3840x2400          | 4         | 0.1%    |
| 2736x1824          | 4         | 0.1%    |
| 2160x1440          | 4         | 0.1%    |
| 3200x2000          | 3         | 0.07%   |
| 2880x1620          | 3         | 0.07%   |
| 1680x945           | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 5760x2160          | 2         | 0.05%   |
| 3840x1200          | 2         | 0.05%   |
| 3280x1080          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1152x864           | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1343      | 31.53%  |
| 14      | 312       | 7.32%   |
| 21      | 308       | 7.23%   |
| 17      | 290       | 6.81%   |
| 19      | 257       | 6.03%   |
| 23      | 231       | 5.42%   |
| 24      | 210       | 4.93%   |
| 13      | 209       | 4.91%   |
| 27      | 172       | 4.04%   |
| Unknown | 123       | 2.89%   |
| 22      | 118       | 2.77%   |
| 18      | 117       | 2.75%   |
| 12      | 107       | 2.51%   |
| 20      | 52        | 1.22%   |
| 10      | 51        | 1.2%    |
| 34      | 49        | 1.15%   |
| 31      | 45        | 1.06%   |
| 84      | 42        | 0.99%   |
| 11      | 42        | 0.99%   |
| 72      | 20        | 0.47%   |
| 40      | 20        | 0.47%   |
| 16      | 18        | 0.42%   |
| 54      | 15        | 0.35%   |
| 32      | 14        | 0.33%   |
| 65      | 11        | 0.26%   |
| 42      | 8         | 0.19%   |
| 7       | 8         | 0.19%   |
| 52      | 7         | 0.16%   |
| 25      | 7         | 0.16%   |
| 60      | 5         | 0.12%   |
| 46      | 5         | 0.12%   |
| 58      | 4         | 0.09%   |
| 49      | 4         | 0.09%   |
| 48      | 4         | 0.09%   |
| 8       | 4         | 0.09%   |
| 142     | 3         | 0.07%   |
| 64      | 3         | 0.07%   |
| 39      | 3         | 0.07%   |
| 26      | 3         | 0.07%   |
| 85      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1869      | 44.4%   |
| 401-500        | 674       | 16.01%  |
| 501-600        | 594       | 14.11%  |
| 351-400        | 357       | 8.48%   |
| 201-300        | 294       | 6.99%   |
| Unknown        | 123       | 2.92%   |
| 701-800        | 64        | 1.52%   |
| 1501-2000      | 64        | 1.52%   |
| 1001-1500      | 63        | 1.5%    |
| 601-700        | 54        | 1.28%   |
| 801-900        | 24        | 0.57%   |
| 901-1000       | 12        | 0.29%   |
| 1-100          | 8         | 0.19%   |
| 101-200        | 6         | 0.14%   |
| More than 2000 | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2788      | 70.65%  |
| 16/10   | 594       | 15.05%  |
| 5/4     | 291       | 7.37%   |
| Unknown | 91        | 2.31%   |
| 4/3     | 83        | 2.1%    |
| 21/9    | 49        | 1.24%   |
| 3/2     | 31        | 0.79%   |
| 0.67    | 7         | 0.18%   |
| 6/5     | 5         | 0.13%   |
| 32/9    | 3         | 0.08%   |
| 1.00    | 3         | 0.08%   |
| 0.63    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1328      | 31.39%  |
| 201-250        | 712       | 16.83%  |
| 81-90          | 436       | 10.3%   |
| 151-200        | 395       | 9.34%   |
| 141-150        | 239       | 5.65%   |
| 301-350        | 174       | 4.11%   |
| Unknown        | 123       | 2.91%   |
| More than 1000 | 120       | 2.84%   |
| 121-130        | 113       | 2.67%   |
| 351-500        | 109       | 2.58%   |
| 61-70          | 93        | 2.2%    |
| 71-80          | 89        | 2.1%    |
| 251-300        | 77        | 1.82%   |
| 41-50          | 48        | 1.13%   |
| 51-60          | 45        | 1.06%   |
| 501-1000       | 44        | 1.04%   |
| 131-140        | 33        | 0.78%   |
| 111-120        | 25        | 0.59%   |
| 1-40           | 14        | 0.33%   |
| 91-100         | 14        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1603      | 39%     |
| 101-120       | 1260      | 30.66%  |
| 121-160       | 882       | 21.46%  |
| 161-240       | 126       | 3.07%   |
| Unknown       | 123       | 2.99%   |
| 1-50          | 84        | 2.04%   |
| More than 240 | 32        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3603      | 85.87%  |
| 2     | 431       | 10.27%  |
| 0     | 122       | 2.91%   |
| 3     | 35        | 0.83%   |
| 4     | 5         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2134      | 35.33%  |
| Intel                             | 1624      | 26.89%  |
| Qualcomm Atheros                  | 866       | 14.34%  |
| Broadcom                          | 382       | 6.32%   |
| Broadcom Limited                  | 149       | 2.47%   |
| Ralink                            | 123       | 2.04%   |
| Marvell Technology Group          | 83        | 1.37%   |
| Qualcomm Atheros Communications   | 72        | 1.19%   |
| Ralink Technology                 | 70        | 1.16%   |
| TP-Link                           | 64        | 1.06%   |
| MediaTek                          | 58        | 0.96%   |
| Nvidia                            | 53        | 0.88%   |
| Dell                              | 29        | 0.48%   |
| Samsung Electronics               | 27        | 0.45%   |
| Huawei Technologies               | 22        | 0.36%   |
| Hewlett-Packard                   | 22        | 0.36%   |
| Ericsson Business Mobile Networks | 20        | 0.33%   |
| Sierra Wireless                   | 19        | 0.31%   |
| Xiaomi                            | 18        | 0.3%    |
| VIA Technologies                  | 17        | 0.28%   |
| JMicron Technology                | 14        | 0.23%   |
| ASUSTek Computer                  | 14        | 0.23%   |
| Silicon Integrated Systems [SiS]  | 13        | 0.22%   |
| DisplayLink                       | 13        | 0.22%   |
| Attansic Technology               | 13        | 0.22%   |
| ASIX Electronics                  | 10        | 0.17%   |
| Aquantia                          | 10        | 0.17%   |
| Microsoft                         | 7         | 0.12%   |
| Belkin Components                 | 7         | 0.12%   |
| Lenovo                            | 6         | 0.1%    |
| Edimax Technology                 | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| D-Link                            | 6         | 0.1%    |
| Qualcomm                          | 5         | 0.08%   |
| IMC Networks                      | 5         | 0.08%   |
| NetGear                           | 4         | 0.07%   |
| Accton Technology                 | 4         | 0.07%   |
| Microchip Technology              | 3         | 0.05%   |
| ZyDAS                             | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1495      | 21.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 364       | 5.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 215       | 3.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 134       | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 118       | 1.69%   |
| Intel Wireless 8265 / 8275                                              | 98        | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 93        | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 81        | 1.16%   |
| Intel Wireless 7260                                                     | 80        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 1.06%   |
| Intel Wireless 7265                                                     | 71        | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 69        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                | 67        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 66        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                         | 62        | 0.89%   |
| Intel Ethernet Connection I217-LM                                       | 59        | 0.84%   |
| Intel Wireless 3165                                                     | 56        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 56        | 0.8%    |
| Intel 82567LM Gigabit Network Connection                                | 55        | 0.79%   |
| Intel Centrino Advanced-N 6200                                          | 54        | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 53        | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                    | 51        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 51        | 0.73%   |
| Intel Wi-Fi 6 AX200                                                     | 50        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 49        | 0.7%    |
| Intel Wireless 8260                                                     | 43        | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 42        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 42        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 41        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 40        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 0.57%   |
| Intel Wireless 3160                                                     | 39        | 0.56%   |
| Intel I211 Gigabit Network Connection                                   | 39        | 0.56%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 0.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 37        | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                   | 37        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 36        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1146      | 38.98%  |
| Qualcomm Atheros                  | 665       | 22.62%  |
| Realtek Semiconductor             | 385       | 13.1%   |
| Broadcom                          | 204       | 6.94%   |
| Ralink                            | 123       | 4.18%   |
| Qualcomm Atheros Communications   | 72        | 2.45%   |
| Ralink Technology                 | 70        | 2.38%   |
| TP-Link                           | 58        | 1.97%   |
| MediaTek                          | 55        | 1.87%   |
| Broadcom Limited                  | 49        | 1.67%   |
| Dell                              | 21        | 0.71%   |
| Sierra Wireless                   | 19        | 0.65%   |
| ASUSTek Computer                  | 14        | 0.48%   |
| Microsoft                         | 7         | 0.24%   |
| Belkin Components                 | 7         | 0.24%   |
| Edimax Technology                 | 6         | 0.2%    |
| IMC Networks                      | 5         | 0.17%   |
| D-Link                            | 5         | 0.17%   |
| NetGear                           | 4         | 0.14%   |
| Marvell Technology Group          | 4         | 0.14%   |
| Ericsson Business Mobile Networks | 4         | 0.14%   |
| Hewlett-Packard                   | 3         | 0.1%    |
| ZyDAS                             | 2         | 0.07%   |
| Qualcomm                          | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| VIA Technologies                  | 1         | 0.03%   |
| TRENDnet                          | 1         | 0.03%   |
| Texas Instruments                 | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| Mercucys                          | 1         | 0.03%   |
| Fujitsu Siemens Computers         | 1         | 0.03%   |
| Accton Technology                 | 1         | 0.03%   |
| AboCom Systems                    | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 134       | 4.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 121       | 4.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 118       | 3.99%   |
| Intel Wireless 8265 / 8275                                              | 98        | 3.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 93        | 3.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 81        | 2.74%   |
| Intel Wireless 7260                                                     | 80        | 2.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 2.51%   |
| Intel Wireless 7265                                                     | 71        | 2.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 69        | 2.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 66        | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                         | 62        | 2.1%    |
| Intel Wireless 3165                                                     | 56        | 1.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 56        | 1.9%    |
| Intel Centrino Advanced-N 6200                                          | 54        | 1.83%   |
| Intel Wi-Fi 6 AX200                                                     | 50        | 1.69%   |
| Intel Wireless 8260                                                     | 43        | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 42        | 1.42%   |
| Intel Centrino Ultimate-N 6300                                          | 42        | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 41        | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 40        | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 40        | 1.35%   |
| Intel Wireless 3160                                                     | 39        | 1.32%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 1.29%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 37        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 36        | 1.22%   |
| Ralink MT7601U Wireless Adapter                                         | 33        | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 1.12%   |
| Intel WiFi Link 5100                                                    | 32        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 31        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 31        | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 28        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 28        | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 25        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 25        | 0.85%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 24        | 0.81%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 23        | 0.78%   |
| Intel Ultimate N WiFi Link 5300                                         | 20        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2002      | 51.02%  |
| Intel                                  | 994       | 25.33%  |
| Qualcomm Atheros                       | 295       | 7.52%   |
| Broadcom                               | 204       | 5.2%    |
| Broadcom Limited                       | 101       | 2.57%   |
| Marvell Technology Group               | 79        | 2.01%   |
| Nvidia                                 | 53        | 1.35%   |
| Huawei Technologies                    | 19        | 0.48%   |
| Xiaomi                                 | 18        | 0.46%   |
| Samsung Electronics                    | 17        | 0.43%   |
| VIA Technologies                       | 15        | 0.38%   |
| JMicron Technology                     | 14        | 0.36%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.33%   |
| DisplayLink                            | 13        | 0.33%   |
| Attansic Technology                    | 13        | 0.33%   |
| ASIX Electronics                       | 10        | 0.25%   |
| Aquantia                               | 10        | 0.25%   |
| TP-Link                                | 6         | 0.15%   |
| Lenovo                                 | 6         | 0.15%   |
| D-Link System                          | 4         | 0.1%    |
| Qualcomm                               | 3         | 0.08%   |
| Microchip Technology                   | 3         | 0.08%   |
| MediaTek                               | 3         | 0.08%   |
| Hewlett-Packard                        | 3         | 0.08%   |
| Accton Technology                      | 3         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| TOMTOM                                 | 1         | 0.03%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| QLogic                                 | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |
| LG Electronics                         | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |
| HMD Global                             | 1         | 0.03%   |
| Hangzhou Silan Microelectronics        | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1495      | 37.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 364       | 9.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 215       | 5.41%   |
| Intel 82577LM Gigabit Network Connection                          | 67        | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 59        | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 55        | 1.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 53        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1.28%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 51        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 49        | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 39        | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 0.93%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 36        | 0.91%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 35        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 33        | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32        | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 31        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 30        | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 29        | 0.73%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 28        | 0.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 26        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 26        | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 23        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.58%   |
| Intel 82566MM Gigabit Network Connection                          | 22        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 21        | 0.53%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 19        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18        | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 17        | 0.43%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 17        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.4%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 15        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3759      | 56.69%  |
| WiFi     | 2798      | 42.2%   |
| Modem    | 71        | 1.07%   |
| Unknown  | 3         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2221      | 51.48%  |
| Ethernet | 2092      | 48.49%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2271      | 55.5%   |
| 1     | 1700      | 41.54%  |
| 0     | 72        | 1.76%   |
| 3     | 42        | 1.03%   |
| 4     | 6         | 0.15%   |
| 5     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3446      | 80.82%  |
| Yes  | 818       | 19.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 730       | 35%     |
| Qualcomm Atheros Communications | 200       | 9.59%   |
| Broadcom                        | 173       | 8.29%   |
| Realtek Semiconductor           | 157       | 7.53%   |
| Cambridge Silicon Radio         | 147       | 7.05%   |
| IMC Networks                    | 108       | 5.18%   |
| Lite-On Technology              | 103       | 4.94%   |
| Dell                            | 87        | 4.17%   |
| Hewlett-Packard                 | 77        | 3.69%   |
| Foxconn / Hon Hai               | 74        | 3.55%   |
| Ralink                          | 69        | 3.31%   |
| ASUSTek Computer                | 29        | 1.39%   |
| Toshiba                         | 25        | 1.2%    |
| Apple                           | 20        | 0.96%   |
| Ralink Technology               | 10        | 0.48%   |
| Realtek                         | 8         | 0.38%   |
| Askey Computer                  | 8         | 0.38%   |
| MediaTek                        | 7         | 0.34%   |
| Conwise Technology              | 7         | 0.34%   |
| Chicony Electronics             | 6         | 0.29%   |
| Belkin Components               | 6         | 0.29%   |
| TP-Link                         | 5         | 0.24%   |
| Taiyo Yuden                     | 4         | 0.19%   |
| Logitech                        | 4         | 0.19%   |
| Integrated System Solution      | 4         | 0.19%   |
| Foxconn International           | 4         | 0.19%   |
| Micro Star International        | 3         | 0.14%   |
| Marvell Semiconductor           | 3         | 0.14%   |
| Alps Electric                   | 3         | 0.14%   |
| Edimax Technology               | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 389       | 18.62%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 147       | 7.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 97        | 4.64%   |
| Realtek Bluetooth Radio                             | 95        | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 84        | 4.02%   |
| Intel AX201 Bluetooth                               | 82        | 3.93%   |
| Ralink RT3290 Bluetooth                             | 69        | 3.3%    |
| Intel AX200 Bluetooth                               | 46        | 2.2%    |
| Dell DW375 Bluetooth Module                         | 43        | 2.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 38        | 1.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 38        | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 1.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 1.63%   |
| IMC Networks Bluetooth Radio                        | 34        | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 30        | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 28        | 1.34%   |
| IMC Networks Bluetooth Device                       | 28        | 1.34%   |
| IMC Networks Wireless_Device                        | 27        | 1.29%   |
| Broadcom HP Portable SoftSailing                    | 25        | 1.2%    |
| Realtek RTL8723B Bluetooth                          | 23        | 1.1%    |
| Lite-On Bluetooth Device                            | 23        | 1.1%    |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 18        | 0.86%   |
| Intel Bluetooth Device                              | 16        | 0.77%   |
| Realtek 802.11ac WLAN Adapter                       | 15        | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 0.72%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.67%   |
| Broadcom BCM2070 Bluetooth Device                   | 14        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 14        | 0.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 0.62%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 12        | 0.57%   |
| Toshiba Bluetooth Device                            | 11        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 11        | 0.53%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 10        | 0.48%   |
| Foxconn / Hon Hai BCM20702A0                        | 10        | 0.48%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3056      | 58.25%  |
| AMD                                  | 1077      | 20.53%  |
| Nvidia                               | 756       | 14.41%  |
| C-Media Electronics                  | 96        | 1.83%   |
| Creative Labs                        | 42        | 0.8%    |
| Logitech                             | 20        | 0.38%   |
| Texas Instruments                    | 18        | 0.34%   |
| VIA Technologies                     | 17        | 0.32%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.29%   |
| ASUSTek Computer                     | 14        | 0.27%   |
| Generalplus Technology               | 12        | 0.23%   |
| JMTek                                | 9         | 0.17%   |
| Plantronics                          | 8         | 0.15%   |
| Kingston Technology                  | 8         | 0.15%   |
| Creative Technology                  | 7         | 0.13%   |
| BEHRINGER International              | 6         | 0.11%   |
| Lenovo                               | 5         | 0.1%    |
| GN Netcom                            | 5         | 0.1%    |
| SteelSeries ApS                      | 4         | 0.08%   |
| Samson Technologies                  | 4         | 0.08%   |
| Realtek Semiconductor                | 4         | 0.08%   |
| Hewlett-Packard                      | 4         | 0.08%   |
| Focusrite-Novation                   | 4         | 0.08%   |
| Ensoniq                              | 3         | 0.06%   |
| Apple                                | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| Tenx Technology                      | 2         | 0.04%   |
| Promethean Limited                   | 2         | 0.04%   |
| ELMCU                                | 2         | 0.04%   |
| DSEA A/S                             | 2         | 0.04%   |
| D&M Holdings (Denon/Marantz)         | 2         | 0.04%   |
| Cooler Master                        | 2         | 0.04%   |
| ATI Technologies                     | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |
| TEAC                                 | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |
| Superlux digit                       | 1         | 0.02%   |
| Sunplus Technology                   | 1         | 0.02%   |
| Sony                                 | 1         | 0.02%   |
| SM950T Microphone                    | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 328       | 5.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 306       | 4.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 276       | 4.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 266       | 4.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 263       | 4.2%    |
| AMD FCH Azalia Controller                                                                         | 248       | 3.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 213       | 3.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 212       | 3.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 194       | 3.1%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 162       | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 159       | 2.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 121       | 1.93%   |
| Intel 8 Series HD Audio Controller                                                                | 105       | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 104       | 1.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 101       | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 100       | 1.6%    |
| Intel Broadwell-U Audio Controller                                                                | 95        | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 94        | 1.5%    |
| AMD Kabini HDMI/DP Audio                                                                          | 93        | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 84        | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 83        | 1.33%   |
| AMD Trinity HDMI Audio Controller                                                                 | 82        | 1.31%   |
| Intel 200 Series PCH HD Audio                                                                     | 72        | 1.15%   |
| Nvidia High Definition Audio Controller                                                           | 71        | 1.13%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 65        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 64        | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 62        | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 60        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 59        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 59        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 57        | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 57        | 0.91%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 53        | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 52        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 51        | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 50        | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 49        | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 47        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 46        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 770       | 19.86%  |
| SK hynix                   | 728       | 18.78%  |
| Unknown                    | 656       | 16.92%  |
| Kingston                   | 632       | 16.3%   |
| Micron Technology          | 321       | 8.28%   |
| Nanya Technology           | 109       | 2.81%   |
| Elpida                     | 89        | 2.3%    |
| Crucial                    | 87        | 2.24%   |
| Kingmax                    | 84        | 2.17%   |
| Corsair                    | 67        | 1.73%   |
| Ramaxel Technology         | 60        | 1.55%   |
| G.Skill                    | 55        | 1.42%   |
| A-DATA Technology          | 40        | 1.03%   |
| CSX                        | 18        | 0.46%   |
| Team                       | 17        | 0.44%   |
| Patriot                    | 13        | 0.34%   |
| Transcend                  | 12        | 0.31%   |
| Qimonda                    | 12        | 0.31%   |
| ASint Technology           | 10        | 0.26%   |
| 48spaces                   | 10        | 0.26%   |
| Unknown (ABCD)             | 9         | 0.23%   |
| Melco                      | 8         | 0.21%   |
| Apacer                     | 8         | 0.21%   |
| Kingmax Semiconductor      | 7         | 0.18%   |
| Unknown                    | 7         | 0.18%   |
| Toshiba                    | 4         | 0.1%    |
| OCZ                        | 4         | 0.1%    |
| GeIL                       | 4         | 0.1%    |
| PUSKILL                    | 3         | 0.08%   |
| Unknown (09D5)             | 2         | 0.05%   |
| Silicon Power              | 2         | 0.05%   |
| Intersil                   | 2         | 0.05%   |
| Infineon                   | 2         | 0.05%   |
| Hikvision                  | 2         | 0.05%   |
| H                          | 2         | 0.05%   |
| Golden Empire              | 2         | 0.05%   |
| ZION                       | 1         | 0.03%   |
| Unknown (8A5B)             | 1         | 0.03%   |
| Unknown (7F7F7F7F7F970000) | 1         | 0.03%   |
| Unigen                     | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s       | 44        | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 43        | 1%      |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 40        | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 39        | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 38        | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 37        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 36        | 0.84%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 34        | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 33        | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 33        | 0.77%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 26        | 0.6%    |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 25        | 0.58%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 23        | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 23        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s  | 23        | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 22        | 0.51%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 22        | 0.51%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1648MT/s       | 22        | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 21        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 21        | 0.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 21        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 20        | 0.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 20        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 19        | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 19        | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 19        | 0.44%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 19        | 0.44%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 18        | 0.42%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 17        | 0.4%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 17        | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.37%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 16        | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 16        | 0.37%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 16        | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 15        | 0.35%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.35%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 15        | 0.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 14        | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 13        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1505      | 45.43%  |
| DDR4    | 767       | 23.15%  |
| DDR2    | 426       | 12.86%  |
| SDRAM   | 239       | 7.21%   |
| Unknown | 197       | 5.95%   |
| DDR     | 62        | 1.87%   |
| LPDDR4  | 54        | 1.63%   |
| LPDDR3  | 26        | 0.78%   |
| DDR5    | 18        | 0.54%   |
| DRAM    | 11        | 0.33%   |
| LPDDR5  | 8         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1806      | 56.38%  |
| DIMM         | 1324      | 41.34%  |
| Row Of Chips | 57        | 1.78%   |
| Chip         | 8         | 0.25%   |
| RIMM         | 4         | 0.12%   |
| Unknown      | 3         | 0.09%   |
| FB-DIMM      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 1269      | 34.78%  |
| 2048    | 950       | 26.03%  |
| 8192    | 777       | 21.29%  |
| 1024    | 354       | 9.7%    |
| 16384   | 191       | 5.23%   |
| 512     | 53        | 1.45%   |
| 32768   | 49        | 1.34%   |
| 256     | 4         | 0.11%   |
| Unknown | 2         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 924       | 25.14%  |
| 1333    | 343       | 9.33%   |
| 2667    | 279       | 7.59%   |
| 667     | 242       | 6.59%   |
| 800     | 228       | 6.2%    |
| 1334    | 197       | 5.36%   |
| 3200    | 185       | 5.03%   |
| 2400    | 180       | 4.9%    |
| Unknown | 144       | 3.92%   |
| 2133    | 127       | 3.46%   |
| 1067    | 94        | 2.56%   |
| 1866    | 69        | 1.88%   |
| 1867    | 61        | 1.66%   |
| 533     | 51        | 1.39%   |
| 1066    | 50        | 1.36%   |
| 2048    | 49        | 1.33%   |
| 4199    | 46        | 1.25%   |
| 3600    | 36        | 0.98%   |
| 400     | 35        | 0.95%   |
| 975     | 23        | 0.63%   |
| 3266    | 20        | 0.54%   |
| 3733    | 19        | 0.52%   |
| 1800    | 19        | 0.52%   |
| 1639    | 18        | 0.49%   |
| 2666    | 17        | 0.46%   |
| 333     | 16        | 0.44%   |
| 2933    | 15        | 0.41%   |
| 3400    | 14        | 0.38%   |
| 3000    | 14        | 0.38%   |
| 3466    | 13        | 0.35%   |
| 4800    | 11        | 0.3%    |
| 4267    | 10        | 0.27%   |
| 4266    | 10        | 0.27%   |
| 2000    | 9         | 0.24%   |
| 49926   | 8         | 0.22%   |
| 6400    | 8         | 0.22%   |
| 3151    | 8         | 0.22%   |
| 1648    | 7         | 0.19%   |
| 5808    | 5         | 0.14%   |
| 1400    | 5         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 65        | 50.39%  |
| Samsung Electronics   | 26        | 20.16%  |
| Canon                 | 14        | 10.85%  |
| Brother Industries    | 9         | 6.98%   |
| Seiko Epson           | 6         | 4.65%   |
| QinHeng Electronics   | 2         | 1.55%   |
| Lexmark International | 2         | 1.55%   |
| Xerox                 | 1         | 0.78%   |
| STMicroelectronics    | 1         | 0.78%   |
| Ricoh                 | 1         | 0.78%   |
| Prolific Technology   | 1         | 0.78%   |
| Oki Data              | 1         | 0.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer                        | 9         | 6.87%   |
| HP LaserJet 1020                                          | 6         | 4.58%   |
| Samsung ML-2010P Mono Laser Printer                       | 5         | 3.82%   |
| Samsung M2020 Series                                      | 5         | 3.82%   |
| Samsung ML-1640 Series Laser Printer                      | 4         | 3.05%   |
| HP DeskJet 2130 series                                    | 4         | 3.05%   |
| HP LaserJet P1005                                         | 3         | 2.29%   |
| HP LaserJet 1018                                          | 3         | 2.29%   |
| HP Deskjet 2050 J510                                      | 3         | 2.29%   |
| Canon LiDE 400                                            | 3         | 2.29%   |
| Brother HL-1110 series                                    | 3         | 2.29%   |
| Samsung SCX-3400 Series                                   | 2         | 1.53%   |
| QinHeng CH340S                                            | 2         | 1.53%   |
| HP Officejet J4500 series                                 | 2         | 1.53%   |
| HP OfficeJet 6950                                         | 2         | 1.53%   |
| HP LaserJet P1102                                         | 2         | 1.53%   |
| HP LaserJet 1022                                          | 2         | 1.53%   |
| HP LaserJet 1010                                          | 2         | 1.53%   |
| HP LaserJet 1000                                          | 2         | 1.53%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.53%   |
| HP Deskjet F2280 series                                   | 2         | 1.53%   |
| HP DeskJet F2100 Printer series                           | 2         | 1.53%   |
| HP DeskJet 840c                                           | 2         | 1.53%   |
| HP Deskjet 3520 series                                    | 2         | 1.53%   |
| Canon TS5100 series                                       | 2         | 1.53%   |
| Brother HL-L2300D series                                  | 2         | 1.53%   |
| Xerox WorkCentre 3119 Series                              | 1         | 0.76%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.76%   |
| Seiko Epson XP-240 Series                                 | 1         | 0.76%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.76%   |
| Seiko Epson Printer                                       | 1         | 0.76%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.76%   |
| Seiko Epson L120 Series                                   | 1         | 0.76%   |
| Seiko Epson ET-2600 Series                                | 1         | 0.76%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 0.76%   |
| Samsung SCX-4650 4x21S Series                             | 1         | 0.76%   |
| Samsung SCX-4623 Series                                   | 1         | 0.76%   |
| Samsung SCX-4200 series                                   | 1         | 0.76%   |
| Samsung ML-1660 Series                                    | 1         | 0.76%   |
| Samsung ML-1630 Series                                    | 1         | 0.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 17        | 62.96%  |
| Hewlett-Packard                                | 4         | 14.81%  |
| Mustek Systems                                 | 2         | 7.41%   |
| UMAX                                           | 1         | 3.7%    |
| Siemens Information and Communication Products | 1         | 3.7%    |
| Seiko Epson                                    | 1         | 3.7%    |
| KYE Systems (Mouse Systems)                    | 1         | 3.7%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                                              | 5         | 18.52%  |
| Canon CanoScan LIDE 25                                                          | 3         | 11.11%  |
| Canon CanoScan LiDE 110                                                         | 3         | 11.11%  |
| Mustek Systems SNAPSCAN e22                                                     | 2         | 7.41%   |
| HP Scanjet 300                                                                  | 2         | 7.41%   |
| Canon CanoScan LiDE 120                                                         | 2         | 7.41%   |
| UMAX Astra 4400/4450                                                            | 1         | 3.7%    |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 3.7%    |
| Seiko Epson Stylus Photo RX500/510                                              | 1         | 3.7%    |
| KYE Systems (Mouse Systems) ColorPage-SF600                                     | 1         | 3.7%    |
| HP ScanJet 3770                                                                 | 1         | 3.7%    |
| HP ScanJet 2400c                                                                | 1         | 3.7%    |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 3.7%    |
| Canon CanoScan LiDE 220                                                         | 1         | 3.7%    |
| Canon CanoScan LiDE 100                                                         | 1         | 3.7%    |
| Canon CanoScan 4200F                                                            | 1         | 3.7%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 537       | 24.05%  |
| Microdia                               | 221       | 9.9%    |
| IMC Networks                           | 215       | 9.63%   |
| Realtek Semiconductor                  | 184       | 8.24%   |
| Sunplus Innovation Technology          | 137       | 6.14%   |
| Bison Electronics                      | 102       | 4.57%   |
| Suyin                                  | 96        | 4.3%    |
| Quanta                                 | 86        | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 74        | 3.31%   |
| Logitech                               | 66        | 2.96%   |
| Syntek                                 | 54        | 2.42%   |
| Silicon Motion                         | 40        | 1.79%   |
| Lite-On Technology                     | 40        | 1.79%   |
| Lenovo                                 | 34        | 1.52%   |
| Acer                                   | 29        | 1.3%    |
| Z-Star Microelectronics                | 27        | 1.21%   |
| Apple                                  | 27        | 1.21%   |
| Alcor Micro                            | 25        | 1.12%   |
| Ricoh                                  | 22        | 0.99%   |
| Primax Electronics                     | 21        | 0.94%   |
| Microsoft                              | 19        | 0.85%   |
| KYE Systems (Mouse Systems)            | 19        | 0.85%   |
| Luxvisions Innotech Limited            | 16        | 0.72%   |
| Samsung Electronics                    | 15        | 0.67%   |
| GEMBIRD                                | 15        | 0.67%   |
| Sonix Technology                       | 12        | 0.54%   |
| ALi                                    | 11        | 0.49%   |
| Importek                               | 9         | 0.4%    |
| OmniVision Technologies                | 7         | 0.31%   |
| Trust                                  | 6         | 0.27%   |
| Generalplus Technology                 | 5         | 0.22%   |
| Aveo Technology                        | 5         | 0.22%   |
| Arkmicro Technologies                  | 5         | 0.22%   |
| Pixart Imaging                         | 4         | 0.18%   |
| MacroSilicon                           | 4         | 0.18%   |
| LG Electronics                         | 4         | 0.18%   |
| Jieli Technology                       | 3         | 0.13%   |
| icSpring                               | 3         | 0.13%   |
| DigiTech                               | 3         | 0.13%   |
| Cubeternet                             | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 65        | 2.9%    |
| IMC Networks USB2.0 VGA UVC WebCam            | 60        | 2.68%   |
| Microdia Integrated_Webcam_HD                 | 52        | 2.32%   |
| IMC Networks USB2.0 HD UVC WebCam             | 49        | 2.19%   |
| Chicony HP Truevision HD                      | 40        | 1.78%   |
| Chicony HD WebCam                             | 40        | 1.78%   |
| Sunplus Integrated_Webcam_HD                  | 34        | 1.52%   |
| Realtek Integrated_Webcam_HD                  | 32        | 1.43%   |
| Realtek USB Camera                            | 30        | 1.34%   |
| Chicony USB2.0 VGA UVC WebCam                 | 30        | 1.34%   |
| Bison Integrated Camera                       | 27        | 1.2%    |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 26        | 1.16%   |
| Microdia Integrated Webcam                    | 26        | 1.16%   |
| Bison Lenovo EasyCamera                       | 26        | 1.16%   |
| Sunplus HP Truevision HD                      | 24        | 1.07%   |
| Chicony Lenovo EasyCamera                     | 24        | 1.07%   |
| Chicony FJ Camera                             | 22        | 0.98%   |
| Logitech Webcam C270                          | 21        | 0.94%   |
| IMC Networks Integrated Camera                | 20        | 0.89%   |
| IMC Networks EasyCamera                       | 20        | 0.89%   |
| Sunplus HD WebCam                             | 19        | 0.85%   |
| Lenovo Integrated Webcam                      | 19        | 0.85%   |
| Chicony USB2.0 HD UVC WebCam                  | 19        | 0.85%   |
| Chicony Integrated HP HD Webcam               | 19        | 0.85%   |
| Microdia Sonix USB 2.0 Camera                 | 18        | 0.8%    |
| Chicony VGA Webcam                            | 18        | 0.8%    |
| Chicony EasyCamera                            | 18        | 0.8%    |
| Realtek Integrated Webcam                     | 17        | 0.76%   |
| Quanta VGA Webcam                             | 17        | 0.76%   |
| Microdia Camera                               | 17        | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 16        | 0.71%   |
| Syntek Integrated Camera                      | 15        | 0.67%   |
| Realtek Lenovo EasyCamera                     | 15        | 0.67%   |
| Primax HP HD Webcam [Fixed]                   | 15        | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD          | 15        | 0.67%   |
| Lite-On Integrated Camera                     | 15        | 0.67%   |
| Syntek Lenovo EasyCamera                      | 14        | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode)       | 14        | 0.62%   |
| Lenovo Integrated Webcam [R5U877]             | 14        | 0.62%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 115       | 35.94%  |
| AuthenTec                          | 58        | 18.13%  |
| Synaptics                          | 47        | 14.69%  |
| Upek                               | 29        | 9.06%   |
| Shenzhen Goodix Technology         | 26        | 8.13%   |
| LighTuning Technology              | 18        | 5.63%   |
| STMicroelectronics                 | 12        | 3.75%   |
| Elan Microelectronics              | 11        | 3.44%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 8.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 8.13%   |
| AuthenTec AES2810                                                          | 24        | 7.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 5.94%   |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 5%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 13        | 4.06%   |
| Validity Sensors VFS491                                                    | 12        | 3.75%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 3.75%   |
| STMicroelectronics Fingerprint Reader                                      | 12        | 3.75%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 2.81%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 2.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 2.81%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 2.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.19%   |
| LighTuning Fingerprint Reader                                              | 7         | 2.19%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.19%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 2.19%   |
| Synaptics  WBDI                                                            | 5         | 1.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.56%   |
| AuthenTec AES1600                                                          | 5         | 1.56%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.25%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.94%   |
| Synaptics WBDI                                                             | 3         | 0.94%   |
| Synaptics Fingerprint scanner                                              | 3         | 0.94%   |
| Elan ELAN:ARM-M4                                                           | 3         | 0.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.63%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.63%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.63%   |
| Synaptics UWP WBDI                                                         | 2         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.31%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 131       | 53.91%  |
| Alcor Micro               | 37        | 15.23%  |
| O2 Micro                  | 30        | 12.35%  |
| Lenovo                    | 30        | 12.35%  |
| Gemalto (was Gemplus)     | 5         | 2.06%   |
| Upek                      | 3         | 1.23%   |
| Reiner SCT Kartensysteme  | 2         | 0.82%   |
| Yubico.com                | 1         | 0.41%   |
| OmniKey                   | 1         | 0.41%   |
| Chicony Electronics       | 1         | 0.41%   |
| Aladdin Knowledge Systems | 1         | 0.41%   |
| Advanced Card Systems     | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 65        | 26.75%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 15.23%  |
| Lenovo Integrated Smart Card Reader                                          | 30        | 12.35%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 29        | 11.93%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 10.7%   |
| Broadcom 5880                                                                | 21        | 8.64%   |
| Broadcom 58200                                                               | 19        | 7.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.23%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.82%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.82%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.41%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.41%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.41%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.41%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3046      | 72.54%  |
| 1     | 957       | 22.79%  |
| 2     | 170       | 4.05%   |
| 3     | 18        | 0.43%   |
| 4     | 4         | 0.1%    |
| 5     | 2         | 0.05%   |
| 10    | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 366       | 27.48%  |
| Fingerprint reader       | 318       | 23.87%  |
| Chipcard                 | 223       | 16.74%  |
| Net/wireless             | 106       | 7.96%   |
| Bluetooth                | 82        | 6.16%   |
| Multimedia controller    | 54        | 4.05%   |
| Communication controller | 40        | 3%      |
| Storage                  | 39        | 2.93%   |
| Camera                   | 30        | 2.25%   |
| Flash memory             | 18        | 1.35%   |
| Unassigned class         | 14        | 1.05%   |
| Sound                    | 10        | 0.75%   |
| Card reader              | 9         | 0.68%   |
| Net/ethernet             | 6         | 0.45%   |
| Storage/raid             | 4         | 0.3%    |
| Network                  | 3         | 0.23%   |
| Dvb card                 | 3         | 0.23%   |
| Storage/ide              | 2         | 0.15%   |
| Storage/ata              | 2         | 0.15%   |
| Modem                    | 2         | 0.15%   |
| Firewire controller      | 1         | 0.08%   |

