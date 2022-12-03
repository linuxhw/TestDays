Linux in France - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 5924

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| AZW           | SEi                         | [3cd2f7f657](https://linux-hardware.org/?probe=3cd2f7f657) | Dec 01, 2022 |
| Samsung       | R540/R538/SA41/E452         | [afad3c8828](https://linux-hardware.org/?probe=afad3c8828) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| Samsung       | 930XED                      | [38584fa129](https://linux-hardware.org/?probe=38584fa129) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| ASUSTek       | S551LN                      | [b21b106fdf](https://linux-hardware.org/?probe=b21b106fdf) | Dec 01, 2022 |
| HP            | EliteBook 840 G3            | [e17d8c1694](https://linux-hardware.org/?probe=e17d8c1694) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Packard Be... | EasyNote TE69CXP            | [919275eb73](https://linux-hardware.org/?probe=919275eb73) | Nov 30, 2022 |
| HP            | ZBook 15v G5                | [aabc35ae2a](https://linux-hardware.org/?probe=aabc35ae2a) | Nov 30, 2022 |
| ASUSTek       | E403SA                      | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Lenovo        | G70-80 80FF                 | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| HP            | Pavilion 17                 | [431ce9bd18](https://linux-hardware.org/?probe=431ce9bd18) | Nov 29, 2022 |
| Dell          | Latitude E6410              | [d7abefea4b](https://linux-hardware.org/?probe=d7abefea4b) | Nov 29, 2022 |
| Dell          | Latitude E6410              | [bac3e8c250](https://linux-hardware.org/?probe=bac3e8c250) | Nov 29, 2022 |
| Dell          | Latitude 5330               | [b8d907f2e8](https://linux-hardware.org/?probe=b8d907f2e8) | Nov 29, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Dell          | System Vostro 3750          | [ed88e2ae0c](https://linux-hardware.org/?probe=ed88e2ae0c) | Nov 29, 2022 |
| Thomson       | N17V3C8WH512                | [b89cd0328a](https://linux-hardware.org/?probe=b89cd0328a) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Dell          | Inspiron 16 5625            | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| ASUSTek       | X756UVK                     | [4745940cf9](https://linux-hardware.org/?probe=4745940cf9) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2d1a576ee6](https://linux-hardware.org/?probe=2d1a576ee6) | Nov 27, 2022 |
| HP            | Compaq Presario CQ60        | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Jumper        | EZbook                      | [a93aa75e5f](https://linux-hardware.org/?probe=a93aa75e5f) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude 7310               | [46ed677d40](https://linux-hardware.org/?probe=46ed677d40) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [694d1d5e96](https://linux-hardware.org/?probe=694d1d5e96) | Nov 26, 2022 |
| MSI           | GL62M 7RDX                  | [1aa67b30d4](https://linux-hardware.org/?probe=1aa67b30d4) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion 15                 | [b294971fc6](https://linux-hardware.org/?probe=b294971fc6) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| Dell          | Latitude 7310               | [0f9c2a5623](https://linux-hardware.org/?probe=0f9c2a5623) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| Dell          | Latitude 7310               | [d7448aaff8](https://linux-hardware.org/?probe=d7448aaff8) | Nov 24, 2022 |
| Acer          | Aspire ES1-523              | [333d3583b1](https://linux-hardware.org/?probe=333d3583b1) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [4b6212908f](https://linux-hardware.org/?probe=4b6212908f) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [69c89370b7](https://linux-hardware.org/?probe=69c89370b7) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| Dell          | Latitude 7310               | [836fbd119c](https://linux-hardware.org/?probe=836fbd119c) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [9e1f0c4898](https://linux-hardware.org/?probe=9e1f0c4898) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| ASUSTek       | K70IJ                       | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| MSI           | Modern 14 C12M              | [51088606f5](https://linux-hardware.org/?probe=51088606f5) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f1d8974d71](https://linux-hardware.org/?probe=f1d8974d71) | Nov 23, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| HP            | ENVY dv6                    | [0d28d09c70](https://linux-hardware.org/?probe=0d28d09c70) | Nov 22, 2022 |
| Dell          | Latitude E6520              | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| HP            | ProBook 450 G1              | [c8d71bb807](https://linux-hardware.org/?probe=c8d71bb807) | Nov 22, 2022 |
| Timi          | TM1612                      | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| Dell          | Precision 5510              | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [c3048ea26d](https://linux-hardware.org/?probe=c3048ea26d) | Nov 21, 2022 |
| HP            | Pavilion Notebook           | [9599fd68a9](https://linux-hardware.org/?probe=9599fd68a9) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [eb43c3d5c0](https://linux-hardware.org/?probe=eb43c3d5c0) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6a51b20cd4](https://linux-hardware.org/?probe=6a51b20cd4) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion g7                 | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Google        | Rammus                      | [23ed7badd5](https://linux-hardware.org/?probe=23ed7badd5) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| HP            | EliteBook 840 G3            | [a5151a0db4](https://linux-hardware.org/?probe=a5151a0db4) | Nov 18, 2022 |
| Dell          | Latitude 7300               | [5ff7502b3e](https://linux-hardware.org/?probe=5ff7502b3e) | Nov 18, 2022 |
| Dell          | Latitude 7310               | [525543a3dc](https://linux-hardware.org/?probe=525543a3dc) | Nov 18, 2022 |
| Dell          | Latitude 7300               | [5c7f8f6d8c](https://linux-hardware.org/?probe=5c7f8f6d8c) | Nov 18, 2022 |
| HP            | Pavilion 17                 | [ab34ec642d](https://linux-hardware.org/?probe=ab34ec642d) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [94bd888b25](https://linux-hardware.org/?probe=94bd888b25) | Nov 18, 2022 |
| Acer          | Aspire S5-371               | [6274604555](https://linux-hardware.org/?probe=6274604555) | Nov 18, 2022 |
| Acer          | Swift SF314-42              | [12e2119f1c](https://linux-hardware.org/?probe=12e2119f1c) | Nov 18, 2022 |
| Dell          | Latitude 5520               | [72bcc12409](https://linux-hardware.org/?probe=72bcc12409) | Nov 18, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [88336d65e7](https://linux-hardware.org/?probe=88336d65e7) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | [17a064a3c3](https://linux-hardware.org/?probe=17a064a3c3) | Nov 17, 2022 |
| MSI           | Prestige 14 A12SC           | [008c444627](https://linux-hardware.org/?probe=008c444627) | Nov 17, 2022 |
| HP            | EliteBook 840 G3            | [cd753ace10](https://linux-hardware.org/?probe=cd753ace10) | Nov 17, 2022 |
| Apple         | MacBookAir7,2               | [6901439af7](https://linux-hardware.org/?probe=6901439af7) | Nov 17, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Dell          | Latitude 7300               | [462f090e8c](https://linux-hardware.org/?probe=462f090e8c) | Nov 17, 2022 |
| Dell          | Latitude 7380               | [c34f569e5a](https://linux-hardware.org/?probe=c34f569e5a) | Nov 17, 2022 |
| Dell          | Latitude 7380               | [ff8bc9f174](https://linux-hardware.org/?probe=ff8bc9f174) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | [c084bd4b99](https://linux-hardware.org/?probe=c084bd4b99) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | [e687234452](https://linux-hardware.org/?probe=e687234452) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | [5d138b93b6](https://linux-hardware.org/?probe=5d138b93b6) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| MSI           | Katana GF76 11UC            | [24ba2f8b12](https://linux-hardware.org/?probe=24ba2f8b12) | Nov 16, 2022 |
| ASUSTek       | T100TA                      | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| HUAWEI        | HLYL-WXX9                   | [f863546b0f](https://linux-hardware.org/?probe=f863546b0f) | Nov 16, 2022 |
| Google        | Rammus                      | [ef0f440314](https://linux-hardware.org/?probe=ef0f440314) | Nov 16, 2022 |
| AMI           | Intel                       | [36327e3aca](https://linux-hardware.org/?probe=36327e3aca) | Nov 16, 2022 |
| HP            | Notebook                    | [d40f2df5a8](https://linux-hardware.org/?probe=d40f2df5a8) | Nov 16, 2022 |
| HP            | 250 G6 Notebook PC          | [439fe62e2e](https://linux-hardware.org/?probe=439fe62e2e) | Nov 15, 2022 |
| LDLC          | SPC-N                       | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| HP            | Pavilion 17                 | [de4e2c6446](https://linux-hardware.org/?probe=de4e2c6446) | Nov 15, 2022 |
| Acer          | Aspire E5-722               | [7e26ae7fe8](https://linux-hardware.org/?probe=7e26ae7fe8) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [d8e3815f50](https://linux-hardware.org/?probe=d8e3815f50) | Nov 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f532c6bdb1](https://linux-hardware.org/?probe=f532c6bdb1) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2dddaa52cd](https://linux-hardware.org/?probe=2dddaa52cd) | Nov 13, 2022 |
| Dell          | Vostro 3578                 | [1fa1c16736](https://linux-hardware.org/?probe=1fa1c16736) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | [9a214b41ec](https://linux-hardware.org/?probe=9a214b41ec) | Nov 13, 2022 |
| Alienware     | M17xR4                      | [9dbd88c02e](https://linux-hardware.org/?probe=9dbd88c02e) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | [51a7b4fca7](https://linux-hardware.org/?probe=51a7b4fca7) | Nov 12, 2022 |
| Lenovo        | Yoga 2 13 20344             | [deb10be02b](https://linux-hardware.org/?probe=deb10be02b) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| Dell          | Inspiron 3543               | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| SHENZHEN Y... | A8S PRO                     | [354471ab24](https://linux-hardware.org/?probe=354471ab24) | Nov 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [1fa4637d27](https://linux-hardware.org/?probe=1fa4637d27) | Nov 10, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [cd4796484a](https://linux-hardware.org/?probe=cd4796484a) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [e77f7ce44e](https://linux-hardware.org/?probe=e77f7ce44e) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| SHENZHEN Y... | A8S PRO                     | [e6b195843f](https://linux-hardware.org/?probe=e6b195843f) | Nov 09, 2022 |
| Dell          | Precision 5540              | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Dell          | Latitude 5420               | [2eba4932bf](https://linux-hardware.org/?probe=2eba4932bf) | Nov 09, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [97ed2f1140](https://linux-hardware.org/?probe=97ed2f1140) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [9fe97ad66f](https://linux-hardware.org/?probe=9fe97ad66f) | Nov 08, 2022 |
| HP            | Laptop 14s-dq2xxx           | [6c277d54f9](https://linux-hardware.org/?probe=6c277d54f9) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| HP            | EliteBook 8470p             | [e94c6ad334](https://linux-hardware.org/?probe=e94c6ad334) | Nov 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | [29fd694ada](https://linux-hardware.org/?probe=29fd694ada) | Nov 07, 2022 |
| Dell          | G3 3500                     | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Acer          | Nitro AN515-52              | [cbfa344eaa](https://linux-hardware.org/?probe=cbfa344eaa) | Nov 07, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [08c701b06d](https://linux-hardware.org/?probe=08c701b06d) | Nov 06, 2022 |
| Dell          | Latitude E7470              | [1bd39e96d2](https://linux-hardware.org/?probe=1bd39e96d2) | Nov 06, 2022 |
| HP            | Unknown                     | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d1bcd9dd18](https://linux-hardware.org/?probe=d1bcd9dd18) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [2c0e88be3e](https://linux-hardware.org/?probe=2c0e88be3e) | Nov 06, 2022 |
| Thomson       | N17V3C8WH512                | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7e97bace0c](https://linux-hardware.org/?probe=7e97bace0c) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [d793aac21d](https://linux-hardware.org/?probe=d793aac21d) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| Thomson       | NEO14A-4SL128               | [5f6993914c](https://linux-hardware.org/?probe=5f6993914c) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | [0df719375b](https://linux-hardware.org/?probe=0df719375b) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Lenovo        | ThinkPad E570 20H50078FR    | [156f337a82](https://linux-hardware.org/?probe=156f337a82) | Nov 05, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | [94abd977de](https://linux-hardware.org/?probe=94abd977de) | Nov 04, 2022 |
| ASUSTek       | X556URK                     | [c26a3705d3](https://linux-hardware.org/?probe=c26a3705d3) | Nov 04, 2022 |
| HP            | ProBook 6470b               | [78aa59a89a](https://linux-hardware.org/?probe=78aa59a89a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [17bac11f6f](https://linux-hardware.org/?probe=17bac11f6f) | Nov 04, 2022 |
| HP            | 470 G7 Notebook PC          | [ae68dc3b2d](https://linux-hardware.org/?probe=ae68dc3b2d) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| Notebook      | NL40_50GU                   | [c74ffe668a](https://linux-hardware.org/?probe=c74ffe668a) | Nov 03, 2022 |
| Notebook      | NL40_50GU                   | [b3001401db](https://linux-hardware.org/?probe=b3001401db) | Nov 03, 2022 |
| HP            | ProBook 6470b               | [ea7c42479d](https://linux-hardware.org/?probe=ea7c42479d) | Nov 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [7e09b1e9bd](https://linux-hardware.org/?probe=7e09b1e9bd) | Nov 03, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ce4f615c70](https://linux-hardware.org/?probe=ce4f615c70) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fe4a007f99](https://linux-hardware.org/?probe=fe4a007f99) | Nov 03, 2022 |
| HP            | EliteBook 8470p             | [d754cc7217](https://linux-hardware.org/?probe=d754cc7217) | Nov 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [dfe209bf08](https://linux-hardware.org/?probe=dfe209bf08) | Nov 03, 2022 |
| Dell          | G15 5511                    | [6965880757](https://linux-hardware.org/?probe=6965880757) | Nov 02, 2022 |
| HP            | Laptop 15-db0xxx            | [14184ac3d9](https://linux-hardware.org/?probe=14184ac3d9) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | [7a421ed810](https://linux-hardware.org/?probe=7a421ed810) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | [d82227846b](https://linux-hardware.org/?probe=d82227846b) | Nov 02, 2022 |
| Dell          | G3 3500                     | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Dell          | Latitude 5420               | [679fbcb14f](https://linux-hardware.org/?probe=679fbcb14f) | Nov 02, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Acer          | Swift SF314-42              | [6a0d7d5f39](https://linux-hardware.org/?probe=6a0d7d5f39) | Nov 01, 2022 |
| HP            | Pavilion dv5                | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Toshiba       | Satellite C70D-B            | [ccf4e200fb](https://linux-hardware.org/?probe=ccf4e200fb) | Nov 01, 2022 |
| Valve         | Jupiter                     | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Valve         | Jupiter                     | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| Dell          | Latitude E5500              | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| HP            | Compaq Presario CQ71        | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ce59648f62](https://linux-hardware.org/?probe=ce59648f62) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | [d6fc7c48a1](https://linux-hardware.org/?probe=d6fc7c48a1) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| Dell          | XPS L322X                   | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d4552d84d5](https://linux-hardware.org/?probe=d4552d84d5) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | [6873e5b579](https://linux-hardware.org/?probe=6873e5b579) | Oct 30, 2022 |
| Valve         | Jupiter                     | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | [da1b668449](https://linux-hardware.org/?probe=da1b668449) | Oct 30, 2022 |
| ASUSTek       | E200HA                      | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| HP            | Compaq 615                  | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| IP3 Tech      | AP1                         | [0562a6a46d](https://linux-hardware.org/?probe=0562a6a46d) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | [2a9c0ff1c5](https://linux-hardware.org/?probe=2a9c0ff1c5) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [05ff2d32fa](https://linux-hardware.org/?probe=05ff2d32fa) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [403a99d8b2](https://linux-hardware.org/?probe=403a99d8b2) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| Acer          | Extensa 2509                | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Alienware     | m17 R4                      | [14770101cf](https://linux-hardware.org/?probe=14770101cf) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | [8c9d6eb128](https://linux-hardware.org/?probe=8c9d6eb128) | Oct 27, 2022 |
| Dell          | Latitude 5310               | [10b8371dbd](https://linux-hardware.org/?probe=10b8371dbd) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | [6aaeaf667c](https://linux-hardware.org/?probe=6aaeaf667c) | Oct 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [9564d50ef8](https://linux-hardware.org/?probe=9564d50ef8) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| Valve         | Jupiter                     | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Dell          | Precision 7560              | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| Dell          | XPS 13 9305                 | [6062baa35c](https://linux-hardware.org/?probe=6062baa35c) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [34be38a48b](https://linux-hardware.org/?probe=34be38a48b) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| ASUSTek       | GL753VD                     | [08b067d2cf](https://linux-hardware.org/?probe=08b067d2cf) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a128f79c0a](https://linux-hardware.org/?probe=a128f79c0a) | Oct 25, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [eadb224c05](https://linux-hardware.org/?probe=eadb224c05) | Oct 25, 2022 |
| Dell          | Inspiron 7737               | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8f246bccb1](https://linux-hardware.org/?probe=8f246bccb1) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [bc5adf7f4b](https://linux-hardware.org/?probe=bc5adf7f4b) | Oct 25, 2022 |
| Valve         | Jupiter                     | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ec7f3834d1](https://linux-hardware.org/?probe=ec7f3834d1) | Oct 25, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | G50-45 80MQ                 | [1c6d041ce2](https://linux-hardware.org/?probe=1c6d041ce2) | Oct 25, 2022 |
| Valve         | Jupiter                     | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Dell          | Studio 1737                 | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Sony          | VGN-SZ3XP_C                 | [72f83141a0](https://linux-hardware.org/?probe=72f83141a0) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| Dell          | Latitude E6510              | [73cd1082f8](https://linux-hardware.org/?probe=73cd1082f8) | Oct 22, 2022 |
| Dell          | Latitude 5420               | [dd9b95a216](https://linux-hardware.org/?probe=dd9b95a216) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX534FAC_UX534FA    | [928997f65c](https://linux-hardware.org/?probe=928997f65c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [57bfd1e0e9](https://linux-hardware.org/?probe=57bfd1e0e9) | Oct 22, 2022 |
| HP            | ProBook 6550b               | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| Radxa         | ROCK Pi X v1.4              | [133d713246](https://linux-hardware.org/?probe=133d713246) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [47ca27793e](https://linux-hardware.org/?probe=47ca27793e) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Valve         | Jupiter                     | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| HP            | ProBook 6550b               | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Dell          | Precision 5510              | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Alienware     | x15 R2                      | [39d9f7988a](https://linux-hardware.org/?probe=39d9f7988a) | Oct 20, 2022 |
| Dell          | Latitude 5420               | [a6ef44d08a](https://linux-hardware.org/?probe=a6ef44d08a) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| Dell          | Latitude 7300               | [5674456b5d](https://linux-hardware.org/?probe=5674456b5d) | Oct 19, 2022 |
| HP            | 620                         | [263e2a0ba9](https://linux-hardware.org/?probe=263e2a0ba9) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [2df95e6892](https://linux-hardware.org/?probe=2df95e6892) | Oct 19, 2022 |
| HP            | 620                         | [ad17206515](https://linux-hardware.org/?probe=ad17206515) | Oct 18, 2022 |
| Dell          | Precision 7750              | [93dcf0527b](https://linux-hardware.org/?probe=93dcf0527b) | Oct 18, 2022 |
| Dell          | Precision 7750              | [d32782f149](https://linux-hardware.org/?probe=d32782f149) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| Insyde        | WindTab89                   | [8eb81874bb](https://linux-hardware.org/?probe=8eb81874bb) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Dell          | Latitude 7300               | [c9bc03da26](https://linux-hardware.org/?probe=c9bc03da26) | Oct 18, 2022 |
| HP            | ZBook 14 G2                 | [fde830d956](https://linux-hardware.org/?probe=fde830d956) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [bb650e8400](https://linux-hardware.org/?probe=bb650e8400) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| ASUSTek       | F9S                         | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bbff53957f](https://linux-hardware.org/?probe=bbff53957f) | Oct 17, 2022 |
| Dell          | G3 3500                     | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| UNOWHY        | Y13G010S4EI                 | [fca234fc49](https://linux-hardware.org/?probe=fca234fc49) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| ASUSTek       | M70Vn                       | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| Dell          | Latitude 3500               | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| UNOWHY        | Y13G011S4EI                 | [c210cda35b](https://linux-hardware.org/?probe=c210cda35b) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Valve         | Jupiter                     | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| Dell          | Latitude 5400               | [645c7a01da](https://linux-hardware.org/?probe=645c7a01da) | Oct 15, 2022 |
| Acer          | AOD257                      | [41a717913c](https://linux-hardware.org/?probe=41a717913c) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| Acer          | Aspire 7740                 | [a68780a6fd](https://linux-hardware.org/?probe=a68780a6fd) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| Dell          | G3 3500                     | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d1c1c4adea](https://linux-hardware.org/?probe=d1c1c4adea) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34481... | [adce18affa](https://linux-hardware.org/?probe=adce18affa) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Dell          | Latitude E5550              | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | [4eacf977db](https://linux-hardware.org/?probe=4eacf977db) | Oct 11, 2022 |
| Lenovo        | G50-30 80G0                 | [f96c4889db](https://linux-hardware.org/?probe=f96c4889db) | Oct 10, 2022 |
| Letni         | Z156                        | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| Dell          | Latitude 5400               | [ff8eb160c9](https://linux-hardware.org/?probe=ff8eb160c9) | Oct 10, 2022 |
| HP            | Notebook                    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Notebook      | NLx0MU                      | [900e75392f](https://linux-hardware.org/?probe=900e75392f) | Oct 09, 2022 |
| Dell          | Inspiron 16 7610            | [fddf8f17bd](https://linux-hardware.org/?probe=fddf8f17bd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [1b720b4302](https://linux-hardware.org/?probe=1b720b4302) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | [f8bf937f1e](https://linux-hardware.org/?probe=f8bf937f1e) | Oct 08, 2022 |
| Apple         | MacBookAir6,2               | [9f434d86be](https://linux-hardware.org/?probe=9f434d86be) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Acer          | Swift SF314-51              | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| HP            | Laptop 15s-fq2xxx           | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| Clevo         | W2xxHSQ                     | [3a05b61e0b](https://linux-hardware.org/?probe=3a05b61e0b) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8901403de4](https://linux-hardware.org/?probe=8901403de4) | Oct 07, 2022 |
| MSI           | Modern 14 A10M              | [ae56e506c3](https://linux-hardware.org/?probe=ae56e506c3) | Oct 06, 2022 |
| Dell          | Latitude 7300               | [3eb18574b3](https://linux-hardware.org/?probe=3eb18574b3) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| Dell          | Latitude 7480               | [aa3f8d08a6](https://linux-hardware.org/?probe=aa3f8d08a6) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| PC Special... | PCX0DX                      | [35e44699ff](https://linux-hardware.org/?probe=35e44699ff) | Oct 06, 2022 |
| Sony          | VGN-SZ3XP_C                 | [f4fd751216](https://linux-hardware.org/?probe=f4fd751216) | Oct 05, 2022 |
| Dell          | Latitude 7300               | [a57bc6e1a5](https://linux-hardware.org/?probe=a57bc6e1a5) | Oct 05, 2022 |
| HP            | Compaq 15                   | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Lenovo        | ThinkPad L430 24641J9       | [4f4932300b](https://linux-hardware.org/?probe=4f4932300b) | Oct 05, 2022 |
| HP            | Compaq 15                   | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| ASUSTek       | S551LN                      | [bdb441bda7](https://linux-hardware.org/?probe=bdb441bda7) | Oct 04, 2022 |
| ASUSTek       | S551LN                      | [b56c08cbcf](https://linux-hardware.org/?probe=b56c08cbcf) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| HP            | ZBook 14u G6                | [87437a85a7](https://linux-hardware.org/?probe=87437a85a7) | Oct 04, 2022 |
| MSI           | CR61 3M                     | [496910c25b](https://linux-hardware.org/?probe=496910c25b) | Oct 04, 2022 |
| Medion        | E7214                       | [c4ee9367cf](https://linux-hardware.org/?probe=c4ee9367cf) | Oct 04, 2022 |
| Medion        | E7214                       | [e8e78221ca](https://linux-hardware.org/?probe=e8e78221ca) | Oct 04, 2022 |
| Dell          | Latitude E6230              | [a4af37beac](https://linux-hardware.org/?probe=a4af37beac) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Notebook      | W54_55SU1,SUW               | [54083a4f07](https://linux-hardware.org/?probe=54083a4f07) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [84fbbaf62c](https://linux-hardware.org/?probe=84fbbaf62c) | Oct 04, 2022 |
| Lenovo        | B590 62743BG                | [8c120b5fea](https://linux-hardware.org/?probe=8c120b5fea) | Oct 03, 2022 |
| Apple         | MacBookPro5,5               | [5a5aada87f](https://linux-hardware.org/?probe=5a5aada87f) | Oct 03, 2022 |
| Dell          | Latitude E6420              | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| HP            | EliteBook 840 G1            | [5bcba21765](https://linux-hardware.org/?probe=5bcba21765) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Sony          | VPCSB1S1E                   | [b85b92339b](https://linux-hardware.org/?probe=b85b92339b) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Dell          | Latitude 7490               | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Dell          | Latitude E6410              | [7f89aefd99](https://linux-hardware.org/?probe=7f89aefd99) | Oct 02, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | [1c968e44cb](https://linux-hardware.org/?probe=1c968e44cb) | Oct 02, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [80a2948ff1](https://linux-hardware.org/?probe=80a2948ff1) | Oct 02, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| Dell          | Latitude E6510              | [71b8d3743e](https://linux-hardware.org/?probe=71b8d3743e) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [d0a30f35b6](https://linux-hardware.org/?probe=d0a30f35b6) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [e192869dc8](https://linux-hardware.org/?probe=e192869dc8) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | [5c4c517651](https://linux-hardware.org/?probe=5c4c517651) | Oct 02, 2022 |
| HP            | EliteBook 840 G1            | [3f70868547](https://linux-hardware.org/?probe=3f70868547) | Oct 02, 2022 |
| MSI           | CR61 3M                     | [818a721825](https://linux-hardware.org/?probe=818a721825) | Oct 02, 2022 |
| HP            | Pavilion dv7                | [2da8f083a7](https://linux-hardware.org/?probe=2da8f083a7) | Oct 01, 2022 |
| MSI           | GF65 Thin 9SEXR             | [537828a21f](https://linux-hardware.org/?probe=537828a21f) | Oct 01, 2022 |
| UNOWHY        | Y13G012S4EI                 | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [462f9bbdbe](https://linux-hardware.org/?probe=462f9bbdbe) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [571271ed93](https://linux-hardware.org/?probe=571271ed93) | Sep 30, 2022 |
| MSI           | Modern 14 A10M              | [9da1f3fe66](https://linux-hardware.org/?probe=9da1f3fe66) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| HP            | ProBook 6570b               | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Toshiba       | Satellite L670              | [3b3e7965a5](https://linux-hardware.org/?probe=3b3e7965a5) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [0cbacebb95](https://linux-hardware.org/?probe=0cbacebb95) | Sep 29, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [27c854b1a0](https://linux-hardware.org/?probe=27c854b1a0) | Sep 27, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Dell          | Latitude E5250              | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| Timi          | TM1604                      | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| MSI           | GS73 Stealth 8RF            | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
| ASUSTek       | X580VD                      | [378e1d3133](https://linux-hardware.org/?probe=378e1d3133) | Sep 26, 2022 |
| Packard Be... | EasyNote LS44SB             | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [0073af9597](https://linux-hardware.org/?probe=0073af9597) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [6935ebecaa](https://linux-hardware.org/?probe=6935ebecaa) | Sep 26, 2022 |
| HP            | Spectre Pro x360 G2         | [d9248f7b2e](https://linux-hardware.org/?probe=d9248f7b2e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| Acer          | Aspire 3810T                | [de19c5a7e9](https://linux-hardware.org/?probe=de19c5a7e9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| HP            | Laptop 17-bs0xx             | [33398b1a21](https://linux-hardware.org/?probe=33398b1a21) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Dell          | XPS 9320                    | [959d1406dd](https://linux-hardware.org/?probe=959d1406dd) | Sep 23, 2022 |
| Dell          | Precision 3561              | [78b8d776ed](https://linux-hardware.org/?probe=78b8d776ed) | Sep 23, 2022 |
| Notebook      | NL40_50GU                   | [da07f4c223](https://linux-hardware.org/?probe=da07f4c223) | Sep 23, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| Dell          | Precision 5540              | [0f09e447ea](https://linux-hardware.org/?probe=0f09e447ea) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| ASUSTek       | UX510UXK                    | [baa57d8e16](https://linux-hardware.org/?probe=baa57d8e16) | Sep 21, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | [869b076838](https://linux-hardware.org/?probe=869b076838) | Sep 21, 2022 |
| Acer          | Aspire E1-572               | [ba47323a29](https://linux-hardware.org/?probe=ba47323a29) | Sep 21, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [e234a2b52a](https://linux-hardware.org/?probe=e234a2b52a) | Sep 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [982931b71f](https://linux-hardware.org/?probe=982931b71f) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98d21fb774](https://linux-hardware.org/?probe=98d21fb774) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [a454bf3aa7](https://linux-hardware.org/?probe=a454bf3aa7) | Sep 20, 2022 |
| Valve         | Jupiter                     | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [5d42a6abab](https://linux-hardware.org/?probe=5d42a6abab) | Sep 20, 2022 |
| Toshiba       | Satellite L875-11M          | [42f3498e9e](https://linux-hardware.org/?probe=42f3498e9e) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Valve         | Jupiter                     | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| PC Special... | NS50MU                      | [1843dfbb66](https://linux-hardware.org/?probe=1843dfbb66) | Sep 19, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [89894daeb7](https://linux-hardware.org/?probe=89894daeb7) | Sep 19, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [be279328b1](https://linux-hardware.org/?probe=be279328b1) | Sep 19, 2022 |
| HP            | 470 G7 Notebook PC          | [a9f6ad0c32](https://linux-hardware.org/?probe=a9f6ad0c32) | Sep 19, 2022 |
| Lenovo        | ThinkPad X200 7458VL3       | [700ff6630e](https://linux-hardware.org/?probe=700ff6630e) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| MSI           | Katana GF66 12UD            | [fde2d03f98](https://linux-hardware.org/?probe=fde2d03f98) | Sep 17, 2022 |
| Dell          | Latitude E5540              | [8e44a11e6c](https://linux-hardware.org/?probe=8e44a11e6c) | Sep 16, 2022 |
| Dell          | Latitude E5540              | [c2d57deba4](https://linux-hardware.org/?probe=c2d57deba4) | Sep 16, 2022 |
| Valve         | Jupiter                     | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7a390e81b1](https://linux-hardware.org/?probe=7a390e81b1) | Sep 16, 2022 |
| HP            | ZBook Firefly 14 inch G9... | [f543e0852f](https://linux-hardware.org/?probe=f543e0852f) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0CN1... | [2f9eaf5711](https://linux-hardware.org/?probe=2f9eaf5711) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| ASUSTek       | X550JK                      | [5c399f4fb0](https://linux-hardware.org/?probe=5c399f4fb0) | Sep 15, 2022 |
| ASUSTek       | X550JK                      | [59df382a23](https://linux-hardware.org/?probe=59df382a23) | Sep 15, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [1a1ae1e398](https://linux-hardware.org/?probe=1a1ae1e398) | Sep 15, 2022 |
| Acer          | Aspire A515-51G             | [bc275a0476](https://linux-hardware.org/?probe=bc275a0476) | Sep 15, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [84dee7df6c](https://linux-hardware.org/?probe=84dee7df6c) | Sep 15, 2022 |
| Dell          | Precision 3571              | [01f5d7f7f8](https://linux-hardware.org/?probe=01f5d7f7f8) | Sep 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [000eb38ea7](https://linux-hardware.org/?probe=000eb38ea7) | Sep 15, 2022 |
| HP            | OMEN by Laptop              | [282afe0352](https://linux-hardware.org/?probe=282afe0352) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude E7470              | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Dell          | Precision 7550              | [f6a8b38020](https://linux-hardware.org/?probe=f6a8b38020) | Sep 14, 2022 |
| Dell          | Inspiron 15 3520            | [1d74f86789](https://linux-hardware.org/?probe=1d74f86789) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [c05d80959b](https://linux-hardware.org/?probe=c05d80959b) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5784c0a7e3](https://linux-hardware.org/?probe=5784c0a7e3) | Sep 14, 2022 |
| Dell          | Precision 7520              | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| HP            | Pavilion dv7                | [f94d6a4e8f](https://linux-hardware.org/?probe=f94d6a4e8f) | Sep 14, 2022 |
| Dell          | Latitude E5550              | [90674e3069](https://linux-hardware.org/?probe=90674e3069) | Sep 13, 2022 |
| ASUSTek       | X750JB                      | [dd6137189b](https://linux-hardware.org/?probe=dd6137189b) | Sep 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P5440FA_... | [d441c68f40](https://linux-hardware.org/?probe=d441c68f40) | Sep 13, 2022 |
| Samsung       | 950XED                      | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [3e00c86066](https://linux-hardware.org/?probe=3e00c86066) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [999cbe4e8f](https://linux-hardware.org/?probe=999cbe4e8f) | Sep 13, 2022 |
| Apple         | MacBookPro5,3               | [9211f5de76](https://linux-hardware.org/?probe=9211f5de76) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0e6413e94b](https://linux-hardware.org/?probe=0e6413e94b) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |
| HP            | 470 G7 Notebook PC          | [f1c4e72e54](https://linux-hardware.org/?probe=f1c4e72e54) | Sep 12, 2022 |
| Dell          | Vostro 5620                 | [6c88032385](https://linux-hardware.org/?probe=6c88032385) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [3d1d8301c3](https://linux-hardware.org/?probe=3d1d8301c3) | Sep 12, 2022 |
| Dell          | Vostro 3400                 | [06c0b65315](https://linux-hardware.org/?probe=06c0b65315) | Sep 11, 2022 |
| Dell          | Vostro 3400                 | [59d8ed6557](https://linux-hardware.org/?probe=59d8ed6557) | Sep 11, 2022 |
| Dell          | Latitude E7240              | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Apple         | MacBookPro13,1              | [4b7f579852](https://linux-hardware.org/?probe=4b7f579852) | Sep 11, 2022 |
| HP            | Laptop 17-bs0xx             | [512a6bd927](https://linux-hardware.org/?probe=512a6bd927) | Sep 11, 2022 |
| Framework     | Laptop                      | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8df1767beb](https://linux-hardware.org/?probe=8df1767beb) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d946b5e886](https://linux-hardware.org/?probe=d946b5e886) | Sep 09, 2022 |
| Dell          | Precision 7560              | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [e42f779622](https://linux-hardware.org/?probe=e42f779622) | Sep 09, 2022 |
| ASUSTek       | GL702VSK                    | [5001a76a0e](https://linux-hardware.org/?probe=5001a76a0e) | Sep 09, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| HP            | ZBook 15                    | [89a1ed226b](https://linux-hardware.org/?probe=89a1ed226b) | Sep 08, 2022 |
| System76      | Lemur                       | [5993c130bc](https://linux-hardware.org/?probe=5993c130bc) | Sep 07, 2022 |
| Dell          | Precision M4800             | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Dell          | Precision M4800             | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| Dell          | Latitude 9520               | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| HP            | EliteBook 850 G6            | [7c202a088d](https://linux-hardware.org/?probe=7c202a088d) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| HP            | ProBook 450 G1              | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| ASUSTek       | X302LA                      | [bc5ccb7df4](https://linux-hardware.org/?probe=bc5ccb7df4) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [e61768b292](https://linux-hardware.org/?probe=e61768b292) | Sep 04, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [0a729ebdd9](https://linux-hardware.org/?probe=0a729ebdd9) | Sep 04, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| ASUSTek       | X756UAM                     | [23f0391963](https://linux-hardware.org/?probe=23f0391963) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [be1fece9bd](https://linux-hardware.org/?probe=be1fece9bd) | Sep 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8e1f677318](https://linux-hardware.org/?probe=8e1f677318) | Sep 02, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| HP            | 250 G7 Notebook PC          | [45ff2a4622](https://linux-hardware.org/?probe=45ff2a4622) | Sep 02, 2022 |
| Acer          | Aspire 5715Z                | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [525a1bd6b6](https://linux-hardware.org/?probe=525a1bd6b6) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| Acer          | Aspire V3-571G              | [8f4a2b603a](https://linux-hardware.org/?probe=8f4a2b603a) | Aug 31, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| Toshiba       | Satellite Pro L500          | [7f523718cf](https://linux-hardware.org/?probe=7f523718cf) | Aug 31, 2022 |
| Dell          | Inspiron 7720               | [97883c54a3](https://linux-hardware.org/?probe=97883c54a3) | Aug 31, 2022 |
| Dell          | Precision 3551              | [c9ffa625ad](https://linux-hardware.org/?probe=c9ffa625ad) | Aug 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [193310218d](https://linux-hardware.org/?probe=193310218d) | Aug 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d36b7bb077](https://linux-hardware.org/?probe=d36b7bb077) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| ASUSTek       | K501LX                      | [993e5d9848](https://linux-hardware.org/?probe=993e5d9848) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| Dell          | Precision 3570              | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| ASUSTek       | X751LJC                     | [36c35406c9](https://linux-hardware.org/?probe=36c35406c9) | Aug 29, 2022 |
| ASUSTek       | N71Jv                       | [b30a3030ae](https://linux-hardware.org/?probe=b30a3030ae) | Aug 28, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [a66f7c7a3a](https://linux-hardware.org/?probe=a66f7c7a3a) | Aug 28, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [3d1138a71c](https://linux-hardware.org/?probe=3d1138a71c) | Aug 27, 2022 |
| Dell          | Latitude E5470              | [7d49878b0d](https://linux-hardware.org/?probe=7d49878b0d) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3f94d521d4](https://linux-hardware.org/?probe=3f94d521d4) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Apple         | MacBookPro9,2               | [49b01e516c](https://linux-hardware.org/?probe=49b01e516c) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Notebook      | W65_67SZ                    | [0bf839f496](https://linux-hardware.org/?probe=0bf839f496) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| Dell          | Precision M4800             | [b00f73e4a3](https://linux-hardware.org/?probe=b00f73e4a3) | Aug 24, 2022 |
| HP            | Compaq CQ58                 | [c4f7e439a9](https://linux-hardware.org/?probe=c4f7e439a9) | Aug 24, 2022 |
| Dell          | Latitude E7240              | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| HP            | ZBook 15 G6                 | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | [4306baa541](https://linux-hardware.org/?probe=4306baa541) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| Dell          | XPS L421X                   | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [2aa681b773](https://linux-hardware.org/?probe=2aa681b773) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a51a82210b](https://linux-hardware.org/?probe=a51a82210b) | Aug 22, 2022 |
| ASUSTek       | X751LN                      | [68cd0152fb](https://linux-hardware.org/?probe=68cd0152fb) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [838dcef1f9](https://linux-hardware.org/?probe=838dcef1f9) | Aug 21, 2022 |
| ASUSTek       | K53SD                       | [1b2c4f25a7](https://linux-hardware.org/?probe=1b2c4f25a7) | Aug 21, 2022 |
| HP            | Compaq CQ58                 | [59fadaa084](https://linux-hardware.org/?probe=59fadaa084) | Aug 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Lenovo        | ThinkPad T520 4239CTO       | [c88fbf8cc5](https://linux-hardware.org/?probe=c88fbf8cc5) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bdb88a532f](https://linux-hardware.org/?probe=bdb88a532f) | Aug 19, 2022 |
| Dell          | Latitude 5500               | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f9ec8eaac3](https://linux-hardware.org/?probe=f9ec8eaac3) | Aug 18, 2022 |
| Packard Be... | EasyNote TJ65               | [df3b457c00](https://linux-hardware.org/?probe=df3b457c00) | Aug 18, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Packard Be... | EasyNote TK37               | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| ASUSTek       | X556UQ                      | [cc792932e6](https://linux-hardware.org/?probe=cc792932e6) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e9d1b72a88](https://linux-hardware.org/?probe=e9d1b72a88) | Aug 17, 2022 |
| Toshiba       | Satellite C870-1F3          | [6738afe025](https://linux-hardware.org/?probe=6738afe025) | Aug 17, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [dd79ae2b92](https://linux-hardware.org/?probe=dd79ae2b92) | Aug 17, 2022 |
| MSI           | PS63 Modern 8RD             | [ad3134e010](https://linux-hardware.org/?probe=ad3134e010) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| ASUSTek       | UX303LN                     | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [da0503d5dd](https://linux-hardware.org/?probe=da0503d5dd) | Aug 15, 2022 |
| ASUSTek       | X541UV                      | [d5b4217f4a](https://linux-hardware.org/?probe=d5b4217f4a) | Aug 15, 2022 |
| Dell          | G3 3500                     | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| UNOWHY        | Y13G010S4EI                 | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | ThinkPad W540 20BHS0F206    | [7f24672b73](https://linux-hardware.org/?probe=7f24672b73) | Aug 14, 2022 |
| Toshiba       | Satellite C55-C             | [44a8059d13](https://linux-hardware.org/?probe=44a8059d13) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| HP            | 470 G7 Notebook PC          | [adae536639](https://linux-hardware.org/?probe=adae536639) | Aug 13, 2022 |
| MSI           | GE75 Raider 10SF            | [0fafeaaa76](https://linux-hardware.org/?probe=0fafeaaa76) | Aug 13, 2022 |
| Panasonic     | CF-31XEUAXMF                | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| HP            | 15                          | [30a35c4e04](https://linux-hardware.org/?probe=30a35c4e04) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX534FAC            | [419660b78b](https://linux-hardware.org/?probe=419660b78b) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [2c76534231](https://linux-hardware.org/?probe=2c76534231) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| Notebook      | N141CU                      | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Toshiba       | Satellite L875-11M          | [5a01928c94](https://linux-hardware.org/?probe=5a01928c94) | Aug 10, 2022 |
| HP            | Laptop 17-ca1xxx            | [f57b28ff2c](https://linux-hardware.org/?probe=f57b28ff2c) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | XPS 9320                    | [f1ce1578ed](https://linux-hardware.org/?probe=f1ce1578ed) | Aug 10, 2022 |
| Dell          | Inspiron 5523               | [6a6928a8a5](https://linux-hardware.org/?probe=6a6928a8a5) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [2ac0968200](https://linux-hardware.org/?probe=2ac0968200) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Toshiba       | Satellite L875-11M          | [1b423f639e](https://linux-hardware.org/?probe=1b423f639e) | Aug 09, 2022 |
| HUAWEI        | KLVC-WXX9                   | [fa0e4ba168](https://linux-hardware.org/?probe=fa0e4ba168) | Aug 09, 2022 |
| Notebook      | N230WU                      | [f00a446001](https://linux-hardware.org/?probe=f00a446001) | Aug 09, 2022 |
| Sony          | VPCYB3V1E                   | [a6cd208cf2](https://linux-hardware.org/?probe=a6cd208cf2) | Aug 09, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [66235597aa](https://linux-hardware.org/?probe=66235597aa) | Aug 09, 2022 |
| Lenovo        | ThinkPad X230 23259T0       | [04b33f4a65](https://linux-hardware.org/?probe=04b33f4a65) | Aug 08, 2022 |
| ASUSTek       | X751LD                      | [e9d631e886](https://linux-hardware.org/?probe=e9d631e886) | Aug 08, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| Dell          | Precision 5510              | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [21e646de39](https://linux-hardware.org/?probe=21e646de39) | Aug 08, 2022 |
| Intel         | JV10_CS                     | [07ca100ab3](https://linux-hardware.org/?probe=07ca100ab3) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | [1c4298ff33](https://linux-hardware.org/?probe=1c4298ff33) | Aug 08, 2022 |
| Acer          | Swift SF113-31              | [0f1ad8ccf7](https://linux-hardware.org/?probe=0f1ad8ccf7) | Aug 08, 2022 |
| HP            | Compaq 15                   | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [977159d1d8](https://linux-hardware.org/?probe=977159d1d8) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [13a118ae0b](https://linux-hardware.org/?probe=13a118ae0b) | Aug 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [89b2da04d8](https://linux-hardware.org/?probe=89b2da04d8) | Aug 06, 2022 |
| Acer          | Aspire V3-372T              | [9dc2882992](https://linux-hardware.org/?probe=9dc2882992) | Aug 06, 2022 |
| Lenovo        | ThinkPad R500 27148UG       | [1b7557ac14](https://linux-hardware.org/?probe=1b7557ac14) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [237cf11989](https://linux-hardware.org/?probe=237cf11989) | Aug 05, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [aec2ac880f](https://linux-hardware.org/?probe=aec2ac880f) | Aug 05, 2022 |
| Notebook      | NJ50_70CU                   | [fc31dfa99e](https://linux-hardware.org/?probe=fc31dfa99e) | Aug 04, 2022 |
| ASUSTek       | X75VC                       | [f293c53dec](https://linux-hardware.org/?probe=f293c53dec) | Aug 04, 2022 |
| Dell          | Latitude E5520              | [1e3f6832b1](https://linux-hardware.org/?probe=1e3f6832b1) | Aug 04, 2022 |
| HP            | Pavilion 17                 | [cbbaa8f0db](https://linux-hardware.org/?probe=cbbaa8f0db) | Aug 03, 2022 |
| HUAWEI        | NBLBZ-WAX9N                 | [0aa70716b7](https://linux-hardware.org/?probe=0aa70716b7) | Aug 03, 2022 |
| HP            | ZBook 15 G3                 | [06e06f9c67](https://linux-hardware.org/?probe=06e06f9c67) | Aug 03, 2022 |
| Dell          | Latitude E7440              | [4d132a5fd7](https://linux-hardware.org/?probe=4d132a5fd7) | Aug 03, 2022 |
| ASUSTek       | 1225B                       | [a5fb38b287](https://linux-hardware.org/?probe=a5fb38b287) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| ASUSTek       | K50IE                       | [0472e4609b](https://linux-hardware.org/?probe=0472e4609b) | Aug 03, 2022 |
| HP            | Notebook                    | [5320991330](https://linux-hardware.org/?probe=5320991330) | Aug 02, 2022 |
| Toshiba       | PORTEGE R30-A               | [89d09548e4](https://linux-hardware.org/?probe=89d09548e4) | Aug 02, 2022 |
| ASUSTek       | X751LJC                     | [e71a9f6a85](https://linux-hardware.org/?probe=e71a9f6a85) | Aug 02, 2022 |
| Acidanther... | MacBookPro13,1              | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| Dell          | XPS 13 9380                 | [d4524b40db](https://linux-hardware.org/?probe=d4524b40db) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [41b26f984c](https://linux-hardware.org/?probe=41b26f984c) | Aug 01, 2022 |
| ASUSTek       | GL553VE                     | [d67cc48957](https://linux-hardware.org/?probe=d67cc48957) | Aug 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | [7137ca1923](https://linux-hardware.org/?probe=7137ca1923) | Aug 01, 2022 |
| HP            | Laptop 14s-dq2xxx           | [9a5e39bf87](https://linux-hardware.org/?probe=9a5e39bf87) | Aug 01, 2022 |
| Acer          | Aspire 7741                 | [4e266f6d7f](https://linux-hardware.org/?probe=4e266f6d7f) | Jul 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7ae6c1826c](https://linux-hardware.org/?probe=7ae6c1826c) | Jul 31, 2022 |
| Acer          | Aspire 7741                 | [932a460553](https://linux-hardware.org/?probe=932a460553) | Jul 31, 2022 |
| HP            | Pavilion Notebook           | [f312865dc0](https://linux-hardware.org/?probe=f312865dc0) | Jul 31, 2022 |
| ASUSTek       | E200HA                      | [86ef744d76](https://linux-hardware.org/?probe=86ef744d76) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Sony          | SVE1511Y1ESI                | [7e5ced1b91](https://linux-hardware.org/?probe=7e5ced1b91) | Jul 30, 2022 |
| HP            | Pavilion dm4                | [2bde69365c](https://linux-hardware.org/?probe=2bde69365c) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | [fca54dfc19](https://linux-hardware.org/?probe=fca54dfc19) | Jul 29, 2022 |
| ASUSTek       | T100TAM                     | [4321f0776b](https://linux-hardware.org/?probe=4321f0776b) | Jul 29, 2022 |
| Dell          | Latitude E6410              | [f2220a772e](https://linux-hardware.org/?probe=f2220a772e) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [74626c2a4d](https://linux-hardware.org/?probe=74626c2a4d) | Jul 29, 2022 |
| Dell          | Latitude 9420               | [1ee70bdfc6](https://linux-hardware.org/?probe=1ee70bdfc6) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Latitude 5480               | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| ASUSTek       | X75A                        | [646a5239a8](https://linux-hardware.org/?probe=646a5239a8) | Jul 28, 2022 |
| HP            | 245 G8 Notebook PC          | [7922ab1018](https://linux-hardware.org/?probe=7922ab1018) | Jul 28, 2022 |
| Notebook      | NL4x_NL5xLU                 | [12d6dbed8b](https://linux-hardware.org/?probe=12d6dbed8b) | Jul 28, 2022 |
| Acer          | Aspire 5755G                | [ba944df1b9](https://linux-hardware.org/?probe=ba944df1b9) | Jul 28, 2022 |
| HP            | EliteBook 820 G2            | [0735a357ee](https://linux-hardware.org/?probe=0735a357ee) | Jul 28, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [7356bc9abc](https://linux-hardware.org/?probe=7356bc9abc) | Jul 28, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [50da53281b](https://linux-hardware.org/?probe=50da53281b) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Dell          | Latitude E6430              | [f04523ef5a](https://linux-hardware.org/?probe=f04523ef5a) | Jul 27, 2022 |
| HP            | Pavilion dv5                | [5e73f42d72](https://linux-hardware.org/?probe=5e73f42d72) | Jul 27, 2022 |
| Acer          | Aspire V3-371               | [0da78400c9](https://linux-hardware.org/?probe=0da78400c9) | Jul 27, 2022 |
| Lenovo        | V145-15AST 81MT             | [ee800b1d9e](https://linux-hardware.org/?probe=ee800b1d9e) | Jul 27, 2022 |
| Notebook      | P7xxDM(-G)                  | [5ec2e8ed2b](https://linux-hardware.org/?probe=5ec2e8ed2b) | Jul 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4f4bdfefd](https://linux-hardware.org/?probe=f4f4bdfefd) | Jul 27, 2022 |
| HP            | Notebook                    | [9a4fc65b6a](https://linux-hardware.org/?probe=9a4fc65b6a) | Jul 26, 2022 |
| ASUSTek       | K50IJ                       | [0d908da71a](https://linux-hardware.org/?probe=0d908da71a) | Jul 26, 2022 |
| Dell          | Latitude E6540              | [d5f66c66fa](https://linux-hardware.org/?probe=d5f66c66fa) | Jul 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3073b497ce](https://linux-hardware.org/?probe=3073b497ce) | Jul 26, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [a1605eaae0](https://linux-hardware.org/?probe=a1605eaae0) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASUSTek       | X751LD                      | [0c7a0b98b4](https://linux-hardware.org/?probe=0c7a0b98b4) | Jul 25, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| Notebook      | N150ZU                      | [6956315543](https://linux-hardware.org/?probe=6956315543) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| MSI           | Modern 14 B10MW             | [b9cde08864](https://linux-hardware.org/?probe=b9cde08864) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | GL502VMZ                    | [5fbc1992e5](https://linux-hardware.org/?probe=5fbc1992e5) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| HP            | EliteBook 2560p             | [6493da2069](https://linux-hardware.org/?probe=6493da2069) | Jul 23, 2022 |
| HP            | Compaq CQ58                 | [73199f32a4](https://linux-hardware.org/?probe=73199f32a4) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Toshiba       | Satellite Pro L500          | [5dd6e66215](https://linux-hardware.org/?probe=5dd6e66215) | Jul 22, 2022 |
| Dell          | XPS 15 9510                 | [6b6e8fd2da](https://linux-hardware.org/?probe=6b6e8fd2da) | Jul 21, 2022 |
| Dell          | Latitude 5420               | [51cf24b119](https://linux-hardware.org/?probe=51cf24b119) | Jul 21, 2022 |
| HP            | ZBook 15 G3                 | [758ce4f6b4](https://linux-hardware.org/?probe=758ce4f6b4) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [29847a6864](https://linux-hardware.org/?probe=29847a6864) | Jul 20, 2022 |
| Dell          | XPS 13 9370                 | [3222136926](https://linux-hardware.org/?probe=3222136926) | Jul 19, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| ASUSTek       | K50IJ                       | [c1d4ce2667](https://linux-hardware.org/?probe=c1d4ce2667) | Jul 19, 2022 |
| HP            | EliteBook 850 G5            | [753ec36553](https://linux-hardware.org/?probe=753ec36553) | Jul 18, 2022 |
| HUAWEI        | HVY-WXX9                    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| HP            | ProBook 6570b               | [db3db082b6](https://linux-hardware.org/?probe=db3db082b6) | Jul 18, 2022 |
| Apple         | MacBookPro9,1               | [ced057bb18](https://linux-hardware.org/?probe=ced057bb18) | Jul 17, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [f9f25bbbfe](https://linux-hardware.org/?probe=f9f25bbbfe) | Jul 17, 2022 |
| Lenovo        | ThinkPad Edge 0328A11       | [4305889043](https://linux-hardware.org/?probe=4305889043) | Jul 17, 2022 |
| Dell          | System Vostro 3450          | [8c0f346c80](https://linux-hardware.org/?probe=8c0f346c80) | Jul 17, 2022 |
| Valve         | Jupiter                     | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| ASUSTek       | N73SV                       | [db493240aa](https://linux-hardware.org/?probe=db493240aa) | Jul 17, 2022 |
| Toshiba       | PORTEGE R930                | [0e8e3b5a24](https://linux-hardware.org/?probe=0e8e3b5a24) | Jul 17, 2022 |
| Google        | Coral                       | [ebf34e57e6](https://linux-hardware.org/?probe=ebf34e57e6) | Jul 17, 2022 |
| Acer          | Nitro AN515-55              | [c9e61ec6c4](https://linux-hardware.org/?probe=c9e61ec6c4) | Jul 16, 2022 |
| HP            | Laptop 17-cp0xxx            | [17803a39aa](https://linux-hardware.org/?probe=17803a39aa) | Jul 16, 2022 |
| Acer          | Aspire A317-53              | [020dfc5580](https://linux-hardware.org/?probe=020dfc5580) | Jul 16, 2022 |
| Acer          | Aspire A317-53              | [d8838cbae7](https://linux-hardware.org/?probe=d8838cbae7) | Jul 16, 2022 |
| HP            | 350 G1                      | [a95c89dfa1](https://linux-hardware.org/?probe=a95c89dfa1) | Jul 16, 2022 |
| HP            | 350 G1                      | [9a154ddcf2](https://linux-hardware.org/?probe=9a154ddcf2) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| ASUSTek       | X751MA                      | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| Toshiba       | Satellite Pro C660          | [9196a0ceb8](https://linux-hardware.org/?probe=9196a0ceb8) | Jul 16, 2022 |
| Toshiba       | Satellite Pro C660          | [fe173bf190](https://linux-hardware.org/?probe=fe173bf190) | Jul 15, 2022 |
| HP            | Laptop 17-ca1xxx            | [68e5da78cd](https://linux-hardware.org/?probe=68e5da78cd) | Jul 15, 2022 |
| MSI           | GE72 6QL                    | [7c22c38989](https://linux-hardware.org/?probe=7c22c38989) | Jul 15, 2022 |
| Dell          | Latitude E6530              | [67eec0ba19](https://linux-hardware.org/?probe=67eec0ba19) | Jul 15, 2022 |
| Acer          | Aspire 7740                 | [243f8e0be2](https://linux-hardware.org/?probe=243f8e0be2) | Jul 14, 2022 |
| Chuwi         | LarkBook                    | [501967d2e1](https://linux-hardware.org/?probe=501967d2e1) | Jul 14, 2022 |
| HP            | 250 G6 Notebook PC          | [00deb1f759](https://linux-hardware.org/?probe=00deb1f759) | Jul 13, 2022 |
| Lenovo        | G50-45 80E3                 | [10f3f2b135](https://linux-hardware.org/?probe=10f3f2b135) | Jul 13, 2022 |
| Notebook      | NL40_50GU                   | [d4e652dc65](https://linux-hardware.org/?probe=d4e652dc65) | Jul 13, 2022 |
| Toshiba       | Satellite Pro R50-C         | [25d6e4de23](https://linux-hardware.org/?probe=25d6e4de23) | Jul 13, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b9a6630267](https://linux-hardware.org/?probe=b9a6630267) | Jul 12, 2022 |
| HP            | ProBook 640 G1              | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Jumper        | EZbook                      | [4b0935af93](https://linux-hardware.org/?probe=4b0935af93) | Jul 11, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1599e9e013](https://linux-hardware.org/?probe=1599e9e013) | Jul 11, 2022 |
| Dell          | Latitude E5440              | [2b94e70ac9](https://linux-hardware.org/?probe=2b94e70ac9) | Jul 11, 2022 |
| ASUSTek       | UX310UAK                    | [2574834337](https://linux-hardware.org/?probe=2574834337) | Jul 10, 2022 |
| ASUSTek       | UX310UAK                    | [9cc9bae948](https://linux-hardware.org/?probe=9cc9bae948) | Jul 10, 2022 |
| Dell          | Latitude 5420               | [1cc724cf75](https://linux-hardware.org/?probe=1cc724cf75) | Jul 10, 2022 |
| HP            | Pavilion dv7                | [0dcf6b98e8](https://linux-hardware.org/?probe=0dcf6b98e8) | Jul 10, 2022 |
| HP            | ProBook 470 G2              | [318374978e](https://linux-hardware.org/?probe=318374978e) | Jul 10, 2022 |
| Lenovo        | V15-ADA 82C7                | [3324f369f7](https://linux-hardware.org/?probe=3324f369f7) | Jul 09, 2022 |
| Toshiba       | Satellite L655              | [d8990c4f88](https://linux-hardware.org/?probe=d8990c4f88) | Jul 09, 2022 |
| HP            | ProBook 6570b               | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Packard Be... | EasyNote TS44HR             | [2961959421](https://linux-hardware.org/?probe=2961959421) | Jul 09, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [82ddcf66ec](https://linux-hardware.org/?probe=82ddcf66ec) | Jul 08, 2022 |
| HP            | ProBook 4510s               | [ae51b4e466](https://linux-hardware.org/?probe=ae51b4e466) | Jul 08, 2022 |
| ASUSTek       | S551LN                      | [1e64e5d64e](https://linux-hardware.org/?probe=1e64e5d64e) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4f02f261b3](https://linux-hardware.org/?probe=4f02f261b3) | Jul 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| HP            | Notebook                    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| Dell          | Vostro 5625                 | [b2fde3bdef](https://linux-hardware.org/?probe=b2fde3bdef) | Jul 07, 2022 |
| ASUSTek       | X705UAP                     | [cf63a63e99](https://linux-hardware.org/?probe=cf63a63e99) | Jul 07, 2022 |
| ASUSTek       | GL553VD                     | [6b5e1735a7](https://linux-hardware.org/?probe=6b5e1735a7) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [e8806ee656](https://linux-hardware.org/?probe=e8806ee656) | Jul 07, 2022 |
| HP            | ProBook 455 G7              | [ddb273e392](https://linux-hardware.org/?probe=ddb273e392) | Jul 07, 2022 |
| ASUSTek       | ROG Strix G733ZS_G733ZS     | [3df6db337d](https://linux-hardware.org/?probe=3df6db337d) | Jul 06, 2022 |
| HP            | Laptop 17-cp0xxx            | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| Acer          | Aspire E1-531               | [ead9f24980](https://linux-hardware.org/?probe=ead9f24980) | Jul 06, 2022 |
| Alienware     | x17 R2                      | [1ab946220b](https://linux-hardware.org/?probe=1ab946220b) | Jul 05, 2022 |
| Dell          | Inspiron 3558               | [09fd55b256](https://linux-hardware.org/?probe=09fd55b256) | Jul 05, 2022 |
| Acer          | Aspire F5-573G              | [c1978d81c7](https://linux-hardware.org/?probe=c1978d81c7) | Jul 05, 2022 |
| HP            | EliteBook 8570p             | [8782b09be9](https://linux-hardware.org/?probe=8782b09be9) | Jul 05, 2022 |
| ASUSTek       | FX503VD                     | [3f26062c31](https://linux-hardware.org/?probe=3f26062c31) | Jul 04, 2022 |
| ASUSTek       | FX503VD                     | [3749a75218](https://linux-hardware.org/?probe=3749a75218) | Jul 04, 2022 |
| Packard Be... | H17HV                       | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [582d281a5c](https://linux-hardware.org/?probe=582d281a5c) | Jul 04, 2022 |
| Thomson       | N17CSL512                   | [11d0b3229b](https://linux-hardware.org/?probe=11d0b3229b) | Jul 04, 2022 |
| Lenovo        | ThinkPad Edge E320 1298A... | [842be4aea2](https://linux-hardware.org/?probe=842be4aea2) | Jul 04, 2022 |
| Acer          | Predator PT516-52s          | [3992d41a65](https://linux-hardware.org/?probe=3992d41a65) | Jul 04, 2022 |
| HP            | 470 G7 Notebook PC          | [49d49283d6](https://linux-hardware.org/?probe=49d49283d6) | Jul 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Thomson       | N17V3C8WH512                | [118835a499](https://linux-hardware.org/?probe=118835a499) | Jul 03, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [172847b24c](https://linux-hardware.org/?probe=172847b24c) | Jul 03, 2022 |
| Dell          | Venue 10 Pro 5056           | [7676cdf093](https://linux-hardware.org/?probe=7676cdf093) | Jul 02, 2022 |
| Dell          | Inspiron 5415               | [d906735fe5](https://linux-hardware.org/?probe=d906735fe5) | Jul 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7cdf221ced](https://linux-hardware.org/?probe=7cdf221ced) | Jul 01, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| Framework     | Laptop                      | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Dell          | G5 5500                     | [edfdebf28d](https://linux-hardware.org/?probe=edfdebf28d) | Jun 30, 2022 |
| Thomson       | N17V3C8WH512                | [518a227ae9](https://linux-hardware.org/?probe=518a227ae9) | Jun 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [03854f8307](https://linux-hardware.org/?probe=03854f8307) | Jun 29, 2022 |
| Notebook      | P7xxDM3(-G)                 | [6abdc9b40d](https://linux-hardware.org/?probe=6abdc9b40d) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| HP            | EliteBook 840 G2            | [79a978476b](https://linux-hardware.org/?probe=79a978476b) | Jun 28, 2022 |
| Dell          | Latitude 5420               | [58838b9e58](https://linux-hardware.org/?probe=58838b9e58) | Jun 28, 2022 |
| Acer          | Aspire E5-722               | [eda8e07df0](https://linux-hardware.org/?probe=eda8e07df0) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| MSI           | VR630                       | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [3fd9c5042f](https://linux-hardware.org/?probe=3fd9c5042f) | Jun 27, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [bde3725b5d](https://linux-hardware.org/?probe=bde3725b5d) | Jun 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [409ca4eba4](https://linux-hardware.org/?probe=409ca4eba4) | Jun 27, 2022 |
| Dell          | Latitude 5510               | [06199cdfe6](https://linux-hardware.org/?probe=06199cdfe6) | Jun 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [aa51c70192](https://linux-hardware.org/?probe=aa51c70192) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4d0e23962a](https://linux-hardware.org/?probe=4d0e23962a) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [78d7beacec](https://linux-hardware.org/?probe=78d7beacec) | Jun 27, 2022 |
| Intel Clie... | LAPKC71F                    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| Toshiba       | Satellite C855-2CF          | [9e062a8425](https://linux-hardware.org/?probe=9e062a8425) | Jun 26, 2022 |
| Acer          | Aspire A114-31              | [8fd4467dfd](https://linux-hardware.org/?probe=8fd4467dfd) | Jun 25, 2022 |
| MSI           | Stealth GS66 12UHS          | [4cee5507af](https://linux-hardware.org/?probe=4cee5507af) | Jun 25, 2022 |
| Dell          | Latitude D630               | [9b1cf4028b](https://linux-hardware.org/?probe=9b1cf4028b) | Jun 25, 2022 |
| Dell          | Latitude D630               | [b3eef0f278](https://linux-hardware.org/?probe=b3eef0f278) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6b59bd5d](https://linux-hardware.org/?probe=8a6b59bd5d) | Jun 25, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [9d53805c9a](https://linux-hardware.org/?probe=9d53805c9a) | Jun 25, 2022 |
| HP            | Pavilion dv7                | [a0c6c78c33](https://linux-hardware.org/?probe=a0c6c78c33) | Jun 25, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ce17a478c3](https://linux-hardware.org/?probe=ce17a478c3) | Jun 24, 2022 |
| HP            | Pavilion dv7                | [334a6079e5](https://linux-hardware.org/?probe=334a6079e5) | Jun 24, 2022 |
| Fujitsu       | LIFEBOOK U7411              | [2bbef77636](https://linux-hardware.org/?probe=2bbef77636) | Jun 23, 2022 |
| Sony          | SVS1312J3EW                 | [95e0cb21c4](https://linux-hardware.org/?probe=95e0cb21c4) | Jun 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [69e0965863](https://linux-hardware.org/?probe=69e0965863) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [13d9478b12](https://linux-hardware.org/?probe=13d9478b12) | Jun 22, 2022 |
| Dell          | XPS 13 9360                 | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Dell          | Precision 7560              | [760bb908b9](https://linux-hardware.org/?probe=760bb908b9) | Jun 22, 2022 |
| Toshiba       | Satellite Pro L500          | [e745bcf24b](https://linux-hardware.org/?probe=e745bcf24b) | Jun 22, 2022 |
| Dell          | G15 5510                    | [cfd6e8f4d6](https://linux-hardware.org/?probe=cfd6e8f4d6) | Jun 21, 2022 |
| Dell          | Latitude E7270              | [5b1c572f56](https://linux-hardware.org/?probe=5b1c572f56) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [926b001aa9](https://linux-hardware.org/?probe=926b001aa9) | Jun 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ff5ed1835c](https://linux-hardware.org/?probe=ff5ed1835c) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [87abe6b88c](https://linux-hardware.org/?probe=87abe6b88c) | Jun 20, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Notebook      | NL40_50CU                   | [b0b1068b47](https://linux-hardware.org/?probe=b0b1068b47) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [9bffffd652](https://linux-hardware.org/?probe=9bffffd652) | Jun 20, 2022 |
| MSI           | Pulse GL66 12UEK            | [a8d859700b](https://linux-hardware.org/?probe=a8d859700b) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [e6bb96869e](https://linux-hardware.org/?probe=e6bb96869e) | Jun 19, 2022 |
| Toshiba       | Satellite Click 10 LX5W-... | [b8f87c8ede](https://linux-hardware.org/?probe=b8f87c8ede) | Jun 19, 2022 |
| MSI           | GE75 Raider 10SF            | [eee0889229](https://linux-hardware.org/?probe=eee0889229) | Jun 19, 2022 |
| ASUSTek       | N550JV                      | [d1d647724c](https://linux-hardware.org/?probe=d1d647724c) | Jun 19, 2022 |
| Packard Be... | H17HV                       | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| Dell          | Latitude 5420               | [14f75e40fd](https://linux-hardware.org/?probe=14f75e40fd) | Jun 18, 2022 |
| Dell          | Latitude E6540              | [e023336620](https://linux-hardware.org/?probe=e023336620) | Jun 18, 2022 |
| MSI           | Creator Z16 A11UET          | [0a6d214b2e](https://linux-hardware.org/?probe=0a6d214b2e) | Jun 18, 2022 |
| Packard Be... | EasyNote TS44HR             | [bc731a2920](https://linux-hardware.org/?probe=bc731a2920) | Jun 18, 2022 |
| ASUSTek       | N71Vg                       | [6926193d76](https://linux-hardware.org/?probe=6926193d76) | Jun 18, 2022 |
| Dell          | G3 3500                     | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| Dell          | Inspiron 7590               | [2e4fc22b64](https://linux-hardware.org/?probe=2e4fc22b64) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| Lenovo        | ThinkPad T460s 20FAS76R0... | [21d6816b13](https://linux-hardware.org/?probe=21d6816b13) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| ASUSTek       | X411UA                      | [da7deca26c](https://linux-hardware.org/?probe=da7deca26c) | Jun 16, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cc3a77a798](https://linux-hardware.org/?probe=cc3a77a798) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d2ec826b81](https://linux-hardware.org/?probe=d2ec826b81) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e889572d35](https://linux-hardware.org/?probe=e889572d35) | Jun 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [5a762627ab](https://linux-hardware.org/?probe=5a762627ab) | Jun 16, 2022 |
| Dell          | Vostro 3525                 | [97e8f44feb](https://linux-hardware.org/?probe=97e8f44feb) | Jun 15, 2022 |
| Lenovo        | ThinkPad E490 20N8002APB    | [3a17ac0192](https://linux-hardware.org/?probe=3a17ac0192) | Jun 15, 2022 |
| HP            | ProBook 430 G6              | [c7b3318ac4](https://linux-hardware.org/?probe=c7b3318ac4) | Jun 14, 2022 |
| Acer          | Aspire E5-722               | [3085e9b7ad](https://linux-hardware.org/?probe=3085e9b7ad) | Jun 14, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [2570d889fd](https://linux-hardware.org/?probe=2570d889fd) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | ENVY m6                     | [f8a6325caa](https://linux-hardware.org/?probe=f8a6325caa) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| ASUSTek       | UX303LN                     | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | [c29e79e22d](https://linux-hardware.org/?probe=c29e79e22d) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | [02e4c63249](https://linux-hardware.org/?probe=02e4c63249) | Jun 12, 2022 |
| Acer          | Aspire ES1-523              | [89fbabafb5](https://linux-hardware.org/?probe=89fbabafb5) | Jun 12, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| HP            | Laptop 17-bs0xx             | [a4587cc1de](https://linux-hardware.org/?probe=a4587cc1de) | Jun 10, 2022 |
| HUAWEI        | HN-WX9X                     | [d57d295c58](https://linux-hardware.org/?probe=d57d295c58) | Jun 10, 2022 |
| Dell          | Latitude 5290               | [930e34a606](https://linux-hardware.org/?probe=930e34a606) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [e33e73a70f](https://linux-hardware.org/?probe=e33e73a70f) | Jun 10, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [e20ce4899d](https://linux-hardware.org/?probe=e20ce4899d) | Jun 09, 2022 |
| Dell          | Latitude 7389               | [88dad6a75c](https://linux-hardware.org/?probe=88dad6a75c) | Jun 09, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Acer          | Aspire V5-531               | [3a462d28a4](https://linux-hardware.org/?probe=3a462d28a4) | Jun 08, 2022 |
| Lenovo        | G50-30 80G0                 | [0de0854560](https://linux-hardware.org/?probe=0de0854560) | Jun 08, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [6d9c3da618](https://linux-hardware.org/?probe=6d9c3da618) | Jun 08, 2022 |
| HP            | ProBook 640 G1              | [34ecb184f9](https://linux-hardware.org/?probe=34ecb184f9) | Jun 08, 2022 |
| Fujitsu       | CELSIUS H730                | [734b6c125f](https://linux-hardware.org/?probe=734b6c125f) | Jun 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [7e3c31382f](https://linux-hardware.org/?probe=7e3c31382f) | Jun 08, 2022 |
| Acer          | Aspire E5-722               | [10fbd3326b](https://linux-hardware.org/?probe=10fbd3326b) | Jun 08, 2022 |
| HP            | EliteBook 8740w             | [a835c8f6c8](https://linux-hardware.org/?probe=a835c8f6c8) | Jun 07, 2022 |
| Lenovo        | ThinkPad T495 20NJ0007US    | [2b3ee11cad](https://linux-hardware.org/?probe=2b3ee11cad) | Jun 07, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Toshiba       | Satellite C850D-115         | [35f95dcc1c](https://linux-hardware.org/?probe=35f95dcc1c) | Jun 06, 2022 |
| Dell          | Latitude E5530 non-vPro     | [e4ba25767a](https://linux-hardware.org/?probe=e4ba25767a) | Jun 06, 2022 |
| Notebook      | NS50MU                      | [d54906a6c5](https://linux-hardware.org/?probe=d54906a6c5) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [9400ad4984](https://linux-hardware.org/?probe=9400ad4984) | Jun 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [3281dce7d5](https://linux-hardware.org/?probe=3281dce7d5) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e7e658bc95](https://linux-hardware.org/?probe=e7e658bc95) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e51b9086bd](https://linux-hardware.org/?probe=e51b9086bd) | Jun 06, 2022 |
| Notebook      | NS50MU                      | [bf6d177bf1](https://linux-hardware.org/?probe=bf6d177bf1) | Jun 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [91abfe378e](https://linux-hardware.org/?probe=91abfe378e) | Jun 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [228fe8f3f1](https://linux-hardware.org/?probe=228fe8f3f1) | Jun 06, 2022 |
| MSI           | Bravo 15 A4DDR              | [f1bad1050e](https://linux-hardware.org/?probe=f1bad1050e) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| Dell          | G3 3500                     | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| AZW           | GT-R                        | [d86ab00f24](https://linux-hardware.org/?probe=d86ab00f24) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [721f0da2de](https://linux-hardware.org/?probe=721f0da2de) | Jun 05, 2022 |
| HP            | Pavilion 17                 | [b2a29d34f0](https://linux-hardware.org/?probe=b2a29d34f0) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| HP            | Pavilion dv6                | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Valve         | Jupiter                     | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| HP            | ProBook 6550b               | [005fa13ca2](https://linux-hardware.org/?probe=005fa13ca2) | Jun 04, 2022 |
| Lenovo        | ThinkPad X230 23259T0       | [d0bb09f4ee](https://linux-hardware.org/?probe=d0bb09f4ee) | Jun 04, 2022 |
| Lenovo        | ThinkPad E470 20H2S01A00    | [b98fdbbd2b](https://linux-hardware.org/?probe=b98fdbbd2b) | Jun 04, 2022 |
| Packard Be... | EasyNote LS11HR             | [78cae55082](https://linux-hardware.org/?probe=78cae55082) | Jun 04, 2022 |
| Lenovo        | Z51-70 80K6                 | [b29848facc](https://linux-hardware.org/?probe=b29848facc) | Jun 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 930       | 21.23%  |
| Ubuntu 18.04      | 305       | 6.96%   |
| Ubuntu 22.04      | 171       | 3.9%    |
| OpenMandriva 4.2  | 169       | 3.86%   |
| Debian 11         | 142       | 3.24%   |
| OpenMandriva 4.3  | 120       | 2.74%   |
| Linux Mint 20.3   | 107       | 2.44%   |
| Xubuntu 20.04     | 105       | 2.4%    |
| Arch              | 80        | 1.83%   |
| Ubuntu 21.10      | 70        | 1.6%    |
| Debian 10         | 69        | 1.58%   |
| Linux Mint 20.2   | 62        | 1.42%   |
| Ubuntu 19.10      | 59        | 1.35%   |
| Ubuntu 21.04      | 56        | 1.28%   |
| Ubuntu 20.10      | 53        | 1.21%   |
| Arch Rolling      | 53        | 1.21%   |
| Xubuntu 18.04     | 48        | 1.1%    |
| Manjaro           | 48        | 1.1%    |
| Linux Mint 19.3   | 48        | 1.1%    |
| Fedora 33         | 48        | 1.1%    |
| Fedora 34         | 44        | 1%      |
| Linux Mint 20.1   | 42        | 0.96%   |
| Kubuntu 20.04     | 41        | 0.94%   |
| Fedora 32         | 40        | 0.91%   |
| Zorin 16          | 39        | 0.89%   |
| Ubuntu 19.04      | 39        | 0.89%   |
| KDE neon 20.04    | 37        | 0.84%   |
| Pop!_OS 20.04     | 36        | 0.82%   |
| Linux Mint 20     | 36        | 0.82%   |
| Fedora 36         | 34        | 0.78%   |
| Fedora 35         | 34        | 0.78%   |
| Ubuntu MATE 20.04 | 33        | 0.75%   |
| Lubuntu 20.04     | 32        | 0.73%   |
| Linux Mint 21     | 30        | 0.68%   |
| Pop!_OS 20.10     | 29        | 0.66%   |
| Pop!_OS 21.04     | 28        | 0.64%   |
| Debian Testing    | 28        | 0.64%   |
| Fedora 31         | 27        | 0.62%   |
| Pop!_OS 22.04     | 26        | 0.59%   |
| Zorin 15          | 24        | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1643      | 39.39%  |
| Linux Mint    | 342       | 8.2%    |
| OpenMandriva  | 324       | 7.77%   |
| Debian        | 265       | 6.35%   |
| Fedora        | 213       | 5.11%   |
| Xubuntu       | 183       | 4.39%   |
| Arch          | 131       | 3.14%   |
| Pop!_OS       | 129       | 3.09%   |
| Manjaro       | 120       | 2.88%   |
| Kubuntu       | 96        | 2.3%    |
| ROSA          | 73        | 1.75%   |
| Zorin         | 64        | 1.53%   |
| Ubuntu MATE   | 57        | 1.37%   |
| Lubuntu       | 51        | 1.22%   |
| KDE neon      | 45        | 1.08%   |
| Endless       | 39        | 0.94%   |
| openSUSE      | 37        | 0.89%   |
| Kali          | 32        | 0.77%   |
| Gentoo        | 30        | 0.72%   |
| Elementary    | 25        | 0.6%    |
| ArcoLinux     | 25        | 0.6%    |
| Ubuntu Budgie | 23        | 0.55%   |
| Ubuntu Unity  | 21        | 0.5%    |
| BlackPanther  | 18        | 0.43%   |
| EndeavourOS   | 16        | 0.38%   |
| Parrot        | 14        | 0.34%   |
| LMDE          | 14        | 0.34%   |
| SteamOS       | 12        | 0.29%   |
| Ubuntu Studio | 10        | 0.24%   |
| Kaisen        | 9         | 0.22%   |
| CentOS        | 8         | 0.19%   |
| NixOS         | 7         | 0.17%   |
| MX            | 7         | 0.17%   |
| Clear Linux   | 7         | 0.17%   |
| RHEL          | 5         | 0.12%   |
| Peppermint    | 5         | 0.12%   |
| Linux Lite    | 5         | 0.12%   |
| Xero          | 4         | 0.1%    |
| Mageia        | 4         | 0.1%    |
| LinuxFX       | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 159       | 3.33%   |
| 5.16.7-desktop-1omv4003  | 116       | 2.43%   |
| 5.4.0-42-generic         | 73        | 1.53%   |
| 5.15.0-52-generic        | 50        | 1.05%   |
| 5.11.0-38-generic        | 50        | 1.05%   |
| 5.4.0-58-generic         | 44        | 0.92%   |
| 5.15.0-48-generic        | 44        | 0.92%   |
| 5.4.0-52-generic         | 43        | 0.9%    |
| 5.11.0-27-generic        | 42        | 0.88%   |
| 5.4.0-26-generic         | 39        | 0.82%   |
| 5.4.0-48-generic         | 36        | 0.75%   |
| 5.8.0-50-generic         | 35        | 0.73%   |
| 5.15.0-46-generic        | 35        | 0.73%   |
| 5.11.0-37-generic        | 35        | 0.73%   |
| 5.8.0-43-generic         | 33        | 0.69%   |
| 5.4.0-65-generic         | 33        | 0.69%   |
| 5.8.0-44-generic         | 32        | 0.67%   |
| 5.4.0-91-generic         | 32        | 0.67%   |
| 5.11.0-43-generic        | 32        | 0.67%   |
| 5.4.0-37-generic         | 31        | 0.65%   |
| 5.13.0-30-generic        | 31        | 0.65%   |
| 5.11.0-40-generic        | 31        | 0.65%   |
| 5.13.0-40-generic        | 30        | 0.63%   |
| 5.15.0-47-generic        | 29        | 0.61%   |
| 5.11.0-34-generic        | 29        | 0.61%   |
| 5.8.0-59-generic         | 28        | 0.59%   |
| 5.8.0-48-generic         | 28        | 0.59%   |
| 5.4.0-54-generic         | 27        | 0.57%   |
| 5.15.0-41-generic        | 27        | 0.57%   |
| 5.13.0-28-generic        | 27        | 0.57%   |
| 5.4.0-31-generic         | 26        | 0.54%   |
| 5.4.0-81-generic         | 25        | 0.52%   |
| 5.15.0-43-generic        | 25        | 0.52%   |
| 5.13.0-39-generic        | 25        | 0.52%   |
| 5.8.0-55-generic         | 24        | 0.5%    |
| 5.8.0-53-generic         | 24        | 0.5%    |
| 5.8.0-41-generic         | 24        | 0.5%    |
| 5.4.0-47-generic         | 24        | 0.5%    |
| 5.3.0-40-generic         | 24        | 0.5%    |
| 5.10.0-8-amd64           | 24        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 921       | 20.51%  |
| 5.11.0  | 351       | 7.82%   |
| 5.8.0   | 349       | 7.77%   |
| 5.15.0  | 324       | 7.22%   |
| 5.13.0  | 299       | 6.66%   |
| 4.15.0  | 218       | 4.86%   |
| 5.10.0  | 178       | 3.96%   |
| 5.3.0   | 176       | 3.92%   |
| 5.10.14 | 160       | 3.56%   |
| 5.16.7  | 116       | 2.58%   |
| 5.0.0   | 99        | 2.2%    |
| 4.18.0  | 66        | 1.47%   |
| 4.19.0  | 64        | 1.43%   |
| 5.19.0  | 31        | 0.69%   |
| 5.14.0  | 27        | 0.6%    |
| 5.17.5  | 19        | 0.42%   |
| 5.16.0  | 19        | 0.42%   |
| 5.11.12 | 19        | 0.42%   |
| 4.18.16 | 17        | 0.38%   |
| 4.9.20  | 15        | 0.33%   |
| 5.9.0   | 14        | 0.31%   |
| 5.6.0   | 14        | 0.31%   |
| 5.18.12 | 14        | 0.31%   |
| 5.9.11  | 13        | 0.29%   |
| 5.18.0  | 13        | 0.29%   |
| 4.4.0   | 12        | 0.27%   |
| 5.14.9  | 11        | 0.24%   |
| 4.9.0   | 11        | 0.24%   |
| 5.9.16  | 10        | 0.22%   |
| 5.7.0   | 10        | 0.22%   |
| 5.17.1  | 10        | 0.22%   |
| 5.17.0  | 10        | 0.22%   |
| 5.12.4  | 10        | 0.22%   |
| 5.8.18  | 9         | 0.2%    |
| 5.19.12 | 9         | 0.2%    |
| 5.10.74 | 9         | 0.2%    |
| 5.9.14  | 8         | 0.18%   |
| 5.15.10 | 8         | 0.18%   |
| 5.14.14 | 8         | 0.18%   |
| 5.13.12 | 8         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 969       | 21.85%  |
| 5.15    | 424       | 9.56%   |
| 5.10    | 418       | 9.43%   |
| 5.11    | 402       | 9.06%   |
| 5.8     | 390       | 8.79%   |
| 5.13    | 336       | 7.58%   |
| 4.15    | 218       | 4.92%   |
| 5.3     | 200       | 4.51%   |
| 5.16    | 179       | 4.04%   |
| 5.0     | 103       | 2.32%   |
| 4.18    | 85        | 1.92%   |
| 5.14    | 82        | 1.85%   |
| 5.19    | 78        | 1.76%   |
| 5.9     | 71        | 1.6%    |
| 4.19    | 70        | 1.58%   |
| 5.18    | 61        | 1.38%   |
| 5.17    | 57        | 1.29%   |
| 5.6     | 50        | 1.13%   |
| 4.9     | 46        | 1.04%   |
| 5.7     | 42        | 0.95%   |
| 5.12    | 38        | 0.86%   |
| 6.0     | 30        | 0.68%   |
| 5.5     | 23        | 0.52%   |
| 4.4     | 14        | 0.32%   |
| 4.1     | 11        | 0.25%   |
| 4.14    | 8         | 0.18%   |
| 5.2     | 7         | 0.16%   |
| 4.13    | 5         | 0.11%   |
| 4.12    | 5         | 0.11%   |
| 4.10    | 4         | 0.09%   |
| 5.1     | 2         | 0.05%   |
| 4.20    | 2         | 0.05%   |
| 3.10    | 2         | 0.05%   |
| 4.8     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3955      | 97.2%   |
| i686    | 111       | 2.73%   |
| aarch64 | 2         | 0.05%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1986      | 47.1%   |
| KDE5              | 635       | 15.06%  |
| Unknown           | 405       | 9.6%    |
| XFCE              | 393       | 9.32%   |
| X-Cinnamon        | 216       | 5.12%   |
| MATE              | 157       | 3.72%   |
| Cinnamon          | 75        | 1.78%   |
| KDE               | 61        | 1.45%   |
| LXQt              | 53        | 1.26%   |
| KDE4              | 50        | 1.19%   |
| i3                | 47        | 1.11%   |
| Budgie            | 28        | 0.66%   |
| Pantheon          | 25        | 0.59%   |
| Unity             | 22        | 0.52%   |
| LXDE              | 19        | 0.45%   |
| GNOME Flashback   | 13        | 0.31%   |
| Deepin            | 8         | 0.19%   |
| i3-with-shmlog    | 3         | 0.07%   |
| GNOME Classic     | 3         | 0.07%   |
| Trinity           | 2         | 0.05%   |
| sway              | 2         | 0.05%   |
| bspwm             | 2         | 0.05%   |
| awesome           | 2         | 0.05%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| openbox           | 1         | 0.02%   |
| Lubuntu           | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| ICEWM             | 1         | 0.02%   |
| Enlightenment     | 1         | 0.02%   |
| dwm-sc            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3348      | 80.06%  |
| Wayland | 563       | 13.46%  |
| Unknown | 208       | 4.97%   |
| Tty     | 63        | 1.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1709      | 40.56%  |
| GDM     | 820       | 19.46%  |
| SDDM    | 639       | 15.16%  |
| LightDM | 438       | 10.39%  |
| GDM3    | 364       | 8.64%   |
| TDM     | 182       | 4.32%   |
| KDM     | 48        | 1.14%   |
| XDM     | 8         | 0.19%   |
| SLiM    | 3         | 0.07%   |
| NODM    | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| fr_FR      | 2801      | 67.72%  |
| en_US      | 728       | 17.6%   |
| Unknown    | 390       | 9.43%   |
| en_GB      | 68        | 1.64%   |
| C          | 37        | 0.89%   |
| ru_RU      | 11        | 0.27%   |
| pl_PL      | 10        | 0.24%   |
| it_IT      | 10        | 0.24%   |
| de_DE      | 9         | 0.22%   |
| es_ES      | 8         | 0.19%   |
| fr_CH      | 7         | 0.17%   |
| nl_NL      | 5         | 0.12%   |
| fr_CA      | 5         | 0.12%   |
| POSIX      | 4         | 0.1%    |
| fr_BE      | 4         | 0.1%    |
| pt_PT      | 3         | 0.07%   |
| pt_BR      | 3         | 0.07%   |
| en_IN      | 3         | 0.07%   |
| en_AU      | 3         | 0.07%   |
| ru_UA      | 2         | 0.05%   |
| hu_HU      | 2         | 0.05%   |
| en_IE      | 2         | 0.05%   |
| en_CA      | 2         | 0.05%   |
| cs_CZ      | 2         | 0.05%   |
| sv_SE      | 1         | 0.02%   |
| sk_SK      | 1         | 0.02%   |
| ro_RO      | 1         | 0.02%   |
| nb_NO      | 1         | 0.02%   |
| fr_LU      | 1         | 0.02%   |
| fr_FR.UTF8 | 1         | 0.02%   |
| es_VE      | 1         | 0.02%   |
| es_UY      | 1         | 0.02%   |
| es_AR      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_FR      | 1         | 0.02%   |
| en_AG      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| de_BE      | 1         | 0.02%   |
| de_AT      | 1         | 0.02%   |
| da_DK      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2336      | 56.34%  |
| BIOS | 1810      | 43.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3383      | 81.85%  |
| Overlay  | 316       | 7.65%   |
| Btrfs    | 249       | 6.02%   |
| Unknown  | 109       | 2.64%   |
| Xfs      | 31        | 0.75%   |
| Zfs      | 21        | 0.51%   |
| Ext2     | 8         | 0.19%   |
| F2fs     | 7         | 0.17%   |
| Ext3     | 7         | 0.17%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1874      | 45.15%  |
| GPT     | 1733      | 41.75%  |
| MBR     | 544       | 13.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3563      | 86.19%  |
| Yes       | 571       | 13.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2861      | 69.46%  |
| Yes       | 1258      | 30.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 737       | 18.12%  |
| Hewlett-Packard     | 684       | 16.81%  |
| Lenovo              | 667       | 16.4%   |
| ASUSTek Computer    | 659       | 16.2%   |
| Acer                | 294       | 7.23%   |
| MSI                 | 152       | 3.74%   |
| Toshiba             | 132       | 3.24%   |
| Apple               | 89        | 2.19%   |
| Notebook            | 78        | 1.92%   |
| Samsung Electronics | 60        | 1.47%   |
| HUAWEI              | 60        | 1.47%   |
| Packard Bell        | 53        | 1.3%    |
| Sony                | 51        | 1.25%   |
| TUXEDO              | 24        | 0.59%   |
| Timi                | 20        | 0.49%   |
| Clevo               | 20        | 0.49%   |
| Unknown             | 18        | 0.44%   |
| UNOWHY              | 17        | 0.42%   |
| Thomson             | 17        | 0.42%   |
| eMachines           | 17        | 0.42%   |
| Gigabyte Technology | 16        | 0.39%   |
| Fujitsu Siemens     | 15        | 0.37%   |
| Valve               | 13        | 0.32%   |
| PC Specialist       | 13        | 0.32%   |
| Fujitsu             | 13        | 0.32%   |
| Alienware           | 13        | 0.32%   |
| Razer               | 12        | 0.29%   |
| Medion              | 10        | 0.25%   |
| Chuwi               | 10        | 0.25%   |
| Google              | 9         | 0.22%   |
| Teclast             | 8         | 0.2%    |
| Intel               | 6         | 0.15%   |
| Panasonic           | 4         | 0.1%    |
| BESSTAR Tech        | 4         | 0.1%    |
| AZW                 | 4         | 0.1%    |
| System76            | 3         | 0.07%   |
| SCHNEIDER           | 3         | 0.07%   |
| NEC Computers       | 3         | 0.07%   |
| LDLC                | 3         | 0.07%   |
| Insyde              | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 33        | 0.81%   |
| HP Notebook                            | 30        | 0.74%   |
| HP Pavilion DV6                        | 24        | 0.59%   |
| HP Pavilion dv7                        | 22        | 0.54%   |
| HP Pavilion 17                         | 19        | 0.47%   |
| HP Pavilion g7                         | 17        | 0.42%   |
| Dell XPS 13 9310                       | 17        | 0.42%   |
| Dell XPS 13 7390                       | 14        | 0.34%   |
| Valve Jupiter                          | 13        | 0.32%   |
| HP Pavilion Notebook                   | 13        | 0.32%   |
| HP EliteBook 840 G2                    | 13        | 0.32%   |
| Dell XPS 15 7590                       | 13        | 0.32%   |
| ASUS S551LN                            | 13        | 0.32%   |
| Dell XPS 15 9570                       | 12        | 0.29%   |
| Dell XPS 13 9380                       | 12        | 0.29%   |
| Dell Latitude E6420                    | 12        | 0.29%   |
| HUAWEI HVY-WXX9                        | 11        | 0.27%   |
| HP Pavilion g6                         | 11        | 0.27%   |
| HP Pavilion 15                         | 11        | 0.27%   |
| HP EliteBook 840 G3                    | 11        | 0.27%   |
| Dell Latitude 5420                     | 11        | 0.27%   |
| Lenovo G50-30 80G0                     | 10        | 0.25%   |
| HUAWEI NBLK-WAX9X                      | 10        | 0.25%   |
| HP ProBook 650 G1                      | 10        | 0.25%   |
| HP OMEN by Laptop                      | 10        | 0.25%   |
| Dell Latitude E6400                    | 10        | 0.25%   |
| Dell Latitude 7490                     | 9         | 0.22%   |
| Dell Latitude 5400                     | 9         | 0.22%   |
| Acer Aspire ES1-523                    | 9         | 0.22%   |
| UNOWHY Y13G010S4EI                     | 8         | 0.2%    |
| Lenovo G50-45 80E3                     | 8         | 0.2%    |
| HP ProBook 640 G1                      | 8         | 0.2%    |
| HP EliteBook 840 G1                    | 8         | 0.2%    |
| Dell XPS 15 9500                       | 8         | 0.2%    |
| Dell XPS 13 9370                       | 8         | 0.2%    |
| Dell Precision 5540                    | 8         | 0.2%    |
| Dell Latitude E6520                    | 8         | 0.2%    |
| Dell Latitude E5500                    | 8         | 0.2%    |
| ASUS VivoBook_ASUSLaptop X570ZD_X570ZD | 8         | 0.2%    |
| Toshiba Satellite C660                 | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 387       | 9.51%   |
| Dell Latitude         | 304       | 7.47%   |
| Acer Aspire           | 201       | 4.94%   |
| HP Pavilion           | 192       | 4.72%   |
| Dell XPS              | 134       | 3.29%   |
| HP EliteBook          | 127       | 3.12%   |
| Lenovo IdeaPad        | 125       | 3.07%   |
| Toshiba Satellite     | 113       | 2.78%   |
| HP ProBook            | 113       | 2.78%   |
| Dell Precision        | 106       | 2.61%   |
| Dell Inspiron         | 104       | 2.56%   |
| ASUS VivoBook         | 92        | 2.26%   |
| HP Laptop             | 57        | 1.4%    |
| Packard Bell EasyNote | 46        | 1.13%   |
| ASUS ZenBook          | 40        | 0.98%   |
| Acer Swift            | 40        | 0.98%   |
| Dell Vostro           | 36        | 0.88%   |
| Unknown               | 33        | 0.81%   |
| HP Compaq             | 32        | 0.79%   |
| Lenovo Legion         | 31        | 0.76%   |
| ASUS ROG              | 31        | 0.76%   |
| HP Notebook           | 30        | 0.74%   |
| HP ZBook              | 27        | 0.66%   |
| HP OMEN               | 19        | 0.47%   |
| HP ENVY               | 18        | 0.44%   |
| ASUS ASUS             | 18        | 0.44%   |
| Dell G5               | 17        | 0.42%   |
| Acer Nitro            | 17        | 0.42%   |
| MSI Modern            | 16        | 0.39%   |
| Lenovo ThinkBook      | 16        | 0.39%   |
| ASUS TUF              | 16        | 0.39%   |
| Acer TravelMate       | 14        | 0.34%   |
| Valve Jupiter         | 13        | 0.32%   |
| ASUS S551LN           | 13        | 0.32%   |
| Razer Blade           | 12        | 0.29%   |
| Lenovo Yoga           | 12        | 0.29%   |
| Fujitsu LIFEBOOK      | 12        | 0.29%   |
| Dell G3               | 12        | 0.29%   |
| HUAWEI HVY-WXX9       | 11        | 0.27%   |
| Apple MacBookPro5     | 11        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 437       | 10.74%  |
| 2020    | 428       | 10.52%  |
| 2018    | 369       | 9.07%   |
| 2012    | 305       | 7.5%    |
| 2013    | 287       | 7.06%   |
| 2021    | 274       | 6.74%   |
| 2015    | 271       | 6.66%   |
| 2011    | 268       | 6.59%   |
| 2017    | 236       | 5.8%    |
| 2016    | 224       | 5.51%   |
| 2014    | 208       | 5.11%   |
| 2010    | 205       | 5.04%   |
| 2008    | 192       | 4.72%   |
| 2009    | 152       | 3.74%   |
| 2007    | 85        | 2.09%   |
| 2022    | 73        | 1.79%   |
| 2006    | 31        | 0.76%   |
| 2005    | 14        | 0.34%   |
| Unknown | 4         | 0.1%    |
| 2004    | 3         | 0.07%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4068      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3622      | 88.34%  |
| Enabled  | 478       | 11.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4054      | 99.63%  |
| Yes  | 15        | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1128      | 27.5%   |
| 3.01-4.0    | 1021      | 24.89%  |
| 16.01-24.0  | 721       | 17.58%  |
| 8.01-16.0   | 614       | 14.97%  |
| 32.01-64.0  | 250       | 6.09%   |
| 1.01-2.0    | 185       | 4.51%   |
| 2.01-3.0    | 75        | 1.83%   |
| 64.01-256.0 | 39        | 0.95%   |
| 24.01-32.0  | 31        | 0.76%   |
| 0.51-1.0    | 30        | 0.73%   |
| 0.01-0.5    | 6         | 0.15%   |
| Unknown     | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1610      | 36.38%  |
| 2.01-3.0   | 1129      | 25.51%  |
| 4.01-8.0   | 605       | 13.67%  |
| 3.01-4.0   | 552       | 12.47%  |
| 0.51-1.0   | 291       | 6.57%   |
| 8.01-16.0  | 176       | 3.98%   |
| 0.01-0.5   | 42        | 0.95%   |
| 16.01-24.0 | 12        | 0.27%   |
| 24.01-32.0 | 6         | 0.14%   |
| Unknown    | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3040      | 73.7%   |
| 2      | 933       | 22.62%  |
| 3      | 96        | 2.33%   |
| 0      | 35        | 0.85%   |
| 4      | 13        | 0.32%   |
| 5      | 5         | 0.12%   |
| 6      | 2         | 0.05%   |
| 7      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2466      | 60.35%  |
| Yes       | 1620      | 39.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3360      | 82.31%  |
| No        | 722       | 17.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3998      | 98.18%  |
| No        | 74        | 1.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3089      | 75.03%  |
| No        | 1028      | 24.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 4068      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 697       | 15.93%  |
| Lyon             | 98        | 2.24%   |
| Toulouse         | 79        | 1.81%   |
| Marseille        | 74        | 1.69%   |
| Nantes           | 57        | 1.3%    |
| Montpellier      | 49        | 1.12%   |
| Lille            | 44        | 1.01%   |
| Rennes           | 38        | 0.87%   |
| Bordeaux         | 37        | 0.85%   |
| Strasbourg       | 36        | 0.82%   |
| Grenoble         | 33        | 0.75%   |
| Clichy-sous-Bois | 28        | 0.64%   |
| Brest            | 27        | 0.62%   |
| Roubaix          | 25        | 0.57%   |
| Villeurbanne     | 24        | 0.55%   |
| Nice             | 21        | 0.48%   |
| Caen             | 19        | 0.43%   |
| Rouen            | 17        | 0.39%   |
| Cergy            | 17        | 0.39%   |
| Nancy            | 16        | 0.37%   |
| Tours            | 15        | 0.34%   |
| Toulon           | 15        | 0.34%   |
| Poitiers         | 15        | 0.34%   |
| Metz             | 15        | 0.34%   |
| Besançon        | 15        | 0.34%   |
| Aix-en-Provence  | 15        | 0.34%   |
| La Rochelle      | 14        | 0.32%   |
| Villejuif        | 13        | 0.3%    |
| Saint-Denis      | 13        | 0.3%    |
| Orléans         | 13        | 0.3%    |
| Le Mans          | 13        | 0.3%    |
| Colmar           | 13        | 0.3%    |
| Clermont-Ferrand | 13        | 0.3%    |
| Versailles       | 12        | 0.27%   |
| Perpignan        | 12        | 0.27%   |
| Pau              | 12        | 0.27%   |
| Palaiseau        | 12        | 0.27%   |
| Ivry-sur-Seine   | 12        | 0.27%   |
| Annecy           | 12        | 0.27%   |
| Valenciennes     | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 742       | 1007   | 14.91%  |
| WDC                       | 557       | 687    | 11.19%  |
| Seagate                   | 549       | 699    | 11.03%  |
| Toshiba                   | 435       | 548    | 8.74%   |
| SanDisk                   | 309       | 378    | 6.21%   |
| Crucial                   | 305       | 383    | 6.13%   |
| SK hynix                  | 252       | 301    | 5.06%   |
| Unknown                   | 241       | 319    | 4.84%   |
| Kingston                  | 231       | 273    | 4.64%   |
| HGST                      | 220       | 268    | 4.42%   |
| Hitachi                   | 165       | 185    | 3.31%   |
| Intel                     | 142       | 171    | 2.85%   |
| Micron Technology         | 134       | 156    | 2.69%   |
| KIOXIA                    | 63        | 71     | 1.27%   |
| Apple                     | 42        | 56     | 0.84%   |
| PNY                       | 41        | 43     | 0.82%   |
| LDLC                      | 38        | 53     | 0.76%   |
| Fujitsu                   | 37        | 45     | 0.74%   |
| LITEON                    | 32        | 37     | 0.64%   |
| Transcend                 | 31        | 34     | 0.62%   |
| Phison                    | 23        | 25     | 0.46%   |
| China                     | 22        | 25     | 0.44%   |
| LITEONIT                  | 20        | 20     | 0.4%    |
| JMicron Technology        | 17        | 19     | 0.34%   |
| Corsair                   | 16        | 19     | 0.32%   |
| SPCC                      | 15        | 17     | 0.3%    |
| Unknown                   | 15        | 16     | 0.3%    |
| Micron/Crucial Technology | 14        | 15     | 0.28%   |
| A-DATA Technology         | 14        | 19     | 0.28%   |
| Silicon Motion            | 10        | 12     | 0.2%    |
| Netac                     | 9         | 10     | 0.18%   |
| Lite-On                   | 9         | 13     | 0.18%   |
| BHT                       | 9         | 12     | 0.18%   |
| SSSTC                     | 8         | 10     | 0.16%   |
| Patriot                   | 7         | 8      | 0.14%   |
| OCZ                       | 7         | 11     | 0.14%   |
| Lenovo                    | 7         | 9      | 0.14%   |
| KingSpec                  | 7         | 8      | 0.14%   |
| Dogfish                   | 7         | 9      | 0.14%   |
| YMTC                      | 6         | 7      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 87        | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB         | 86        | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 75        | 1.46%   |
| Toshiba MQ01ABD100 1TB                 | 71        | 1.38%   |
| Crucial CT500MX500SSD1 500GB           | 61        | 1.18%   |
| Crucial CT240BX500SSD1 240GB           | 53        | 1.03%   |
| Unknown MMC Card  32GB                 | 49        | 0.95%   |
| Toshiba MQ04ABF100 1TB                 | 48        | 0.93%   |
| Samsung SSD 860 EVO 500GB              | 47        | 0.91%   |
| HGST HTS541010A9E680 1TB               | 41        | 0.8%    |
| Samsung NVMe SSD Drive 512GB           | 37        | 0.72%   |
| Unknown MMC Card  64GB                 | 36        | 0.7%    |
| SanDisk NVMe SSD Drive 512GB           | 36        | 0.7%    |
| Kingston SA400S37240G 240GB SSD        | 34        | 0.66%   |
| Seagate ST500LT012-1DG142 500GB        | 32        | 0.62%   |
| Seagate ST9500325AS 500GB              | 29        | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB         | 28        | 0.54%   |
| Toshiba MQ01ABF050 500GB               | 26        | 0.5%    |
| Toshiba NVMe SSD Drive 512GB           | 25        | 0.49%   |
| HGST HTS725050A7E630 500GB             | 25        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB            | 25        | 0.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 24        | 0.47%   |
| Samsung SSD 870 QVO 1TB                | 23        | 0.45%   |
| Samsung SSD 850 EVO 500GB              | 23        | 0.45%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 23        | 0.45%   |
| Intel NVMe SSD Drive 512GB             | 23        | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB               | 22        | 0.43%   |
| SK hynix NVMe SSD Drive 512GB          | 22        | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB         | 22        | 0.43%   |
| Crucial CT120BX500SSD1 120GB           | 21        | 0.41%   |
| Samsung SSD 860 EVO 1TB                | 20        | 0.39%   |
| Samsung SSD 850 EVO 250GB              | 20        | 0.39%   |
| Samsung NVMe SSD Drive 1TB             | 20        | 0.39%   |
| Crucial CT480BX500SSD1 480GB           | 20        | 0.39%   |
| SanDisk NVMe SSD Drive 256GB           | 19        | 0.37%   |
| Unknown MMC Card  128GB                | 18        | 0.35%   |
| Kingston SA400S37120G 120GB SSD        | 18        | 0.35%   |
| Intel SSDPEKNW512G8 512GB              | 18        | 0.35%   |
| Seagate ST500LM021-1KJ152 500GB        | 17        | 0.33%   |
| Seagate Expansion 1TB                  | 16        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 543       | 688    | 31.57%  |
| WDC                 | 379       | 470    | 22.03%  |
| Toshiba             | 301       | 366    | 17.5%   |
| HGST                | 220       | 268    | 12.79%  |
| Hitachi             | 165       | 185    | 9.59%   |
| Samsung Electronics | 37        | 52     | 2.15%   |
| Fujitsu             | 36        | 44     | 2.09%   |
| Unknown             | 8         | 9      | 0.47%   |
| Apple               | 7         | 7      | 0.41%   |
| IBM/Hitachi         | 5         | 6      | 0.29%   |
| ASMT                | 4         | 5      | 0.23%   |
| JMicron Technology  | 3         | 4      | 0.17%   |
| Inateck             | 2         | 2      | 0.12%   |
| HGST HTS            | 2         | 2      | 0.12%   |
| SILICONMOTION       | 1         | 1      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| Magnetic Data       | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| Generic-            | 1         | 1      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| APPLE HD            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 371       | 490    | 22.86%  |
| Crucial             | 284       | 360    | 17.5%   |
| SanDisk             | 203       | 248    | 12.51%  |
| Kingston            | 175       | 208    | 10.78%  |
| SK hynix            | 56        | 70     | 3.45%   |
| Micron Technology   | 56        | 74     | 3.45%   |
| Intel               | 41        | 42     | 2.53%   |
| WDC                 | 38        | 44     | 2.34%   |
| PNY                 | 36        | 38     | 2.22%   |
| LDLC                | 32        | 45     | 1.97%   |
| Apple               | 32        | 44     | 1.97%   |
| Transcend           | 29        | 32     | 1.79%   |
| LITEON              | 27        | 30     | 1.66%   |
| Toshiba             | 23        | 30     | 1.42%   |
| China               | 21        | 24     | 1.29%   |
| LITEONIT            | 20        | 20     | 1.23%   |
| SPCC                | 14        | 16     | 0.86%   |
| A-DATA Technology   | 11        | 16     | 0.68%   |
| BHT                 | 9         | 12     | 0.55%   |
| JMicron Technology  | 8         | 8      | 0.49%   |
| Corsair             | 8         | 10     | 0.49%   |
| Unknown             | 8         | 9      | 0.49%   |
| OCZ                 | 7         | 11     | 0.43%   |
| Netac               | 7         | 8      | 0.43%   |
| KingSpec            | 7         | 8      | 0.43%   |
| Dogfish             | 7         | 9      | 0.43%   |
| Patriot             | 6         | 6      | 0.37%   |
| Emtec               | 6         | 6      | 0.37%   |
| Plextor             | 5         | 6      | 0.31%   |
| KingDian            | 4         | 4      | 0.25%   |
| Unknown             | 3         | 4      | 0.18%   |
| Teclast             | 3         | 5      | 0.18%   |
| TCSUNBOW            | 3         | 4      | 0.18%   |
| Intenso             | 3         | 3      | 0.18%   |
| BAITITON            | 3         | 3      | 0.18%   |
| Verbatim            | 2         | 2      | 0.12%   |
| Union Memory        | 2         | 2      | 0.12%   |
| Seagate             | 2         | 2      | 0.12%   |
| ORICO               | 2         | 2      | 0.12%   |
| NMICRO              | 2         | 2      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1670      | 2116   | 34.89%  |
| SSD     | 1506      | 2011   | 31.46%  |
| NVMe    | 1313      | 1667   | 27.43%  |
| MMC     | 243       | 329    | 5.08%   |
| Unknown | 55        | 60     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2826      | 4004   | 62.38%  |
| NVMe | 1310      | 1660   | 28.92%  |
| MMC  | 243       | 329    | 5.36%   |
| SAS  | 151       | 190    | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2027      | 2688   | 64.19%  |
| 0.51-1.0   | 1047      | 1322   | 33.15%  |
| 1.01-2.0   | 68        | 96     | 2.15%   |
| 4.01-10.0  | 8         | 10     | 0.25%   |
| 3.01-4.0   | 3         | 5      | 0.09%   |
| 10.01-20.0 | 3         | 4      | 0.09%   |
| 2.01-3.0   | 2         | 2      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1196      | 28.17%  |
| 251-500        | 1118      | 26.33%  |
| 501-1000       | 716       | 16.86%  |
| 1-20           | 328       | 7.72%   |
| 51-100         | 264       | 6.22%   |
| 1001-2000      | 210       | 4.95%   |
| 21-50          | 190       | 4.47%   |
| Unknown        | 113       | 2.66%   |
| 2001-3000      | 56        | 1.32%   |
| More than 3000 | 55        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1738      | 39.39%  |
| 21-50          | 786       | 17.82%  |
| 101-250        | 612       | 13.87%  |
| 51-100         | 564       | 12.78%  |
| 251-500        | 333       | 7.55%   |
| 501-1000       | 177       | 4.01%   |
| Unknown        | 113       | 2.56%   |
| 1001-2000      | 51        | 1.16%   |
| 2001-3000      | 25        | 0.57%   |
| More than 3000 | 11        | 0.25%   |
| 0              | 2         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 16        | 19     | 4.36%   |
| HGST HTS541010A9E680 1TB                         | 10        | 10     | 2.72%   |
| Toshiba MQ01ABD100 1TB                           | 8         | 10     | 2.18%   |
| Seagate ST9500325AS 500GB                        | 8         | 9      | 2.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 8         | 8      | 2.18%   |
| Seagate ST500LM021-1KJ152 500GB                  | 7         | 9      | 1.91%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 6         | 6      | 1.63%   |
| Seagate ST1000LM035-1RK172 1TB                   | 6         | 6      | 1.63%   |
| Toshiba MQ01ABD050 500GB                         | 5         | 5      | 1.36%   |
| Toshiba MK3265GSX 320GB                          | 4         | 5      | 1.09%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 4         | 4      | 1.09%   |
| Seagate ST500LT012-1DG142 500GB                  | 4         | 4      | 1.09%   |
| Hitachi HTS727575A9E364 752GB                    | 4         | 4      | 1.09%   |
| Hitachi HTS547575A9E384 752GB                    | 4         | 4      | 1.09%   |
| Hitachi HTS545050B9A300 500GB                    | 4         | 4      | 1.09%   |
| Hitachi HTS545050A7E380 500GB                    | 4         | 4      | 1.09%   |
| Hitachi HTS543232A7A384 320GB                    | 4         | 6      | 1.09%   |
| HGST HTS725050A7E630 500GB                       | 4         | 4      | 1.09%   |
| Crucial CT525MX300SSD1 528GB                     | 4         | 4      | 1.09%   |
| Toshiba MQ01ABF050 500GB                         | 3         | 3      | 0.82%   |
| Toshiba MK5055GSX 500GB                          | 3         | 3      | 0.82%   |
| Toshiba MK3261GSYN 320GB                         | 3         | 3      | 0.82%   |
| Seagate ST9250827AS 250GB                        | 3         | 3      | 0.82%   |
| Seagate ST320LT007-9ZV142 320GB                  | 3         | 4      | 0.82%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 3      | 0.82%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 3         | 3      | 0.82%   |
| Hitachi HTS547550A9E384 500GB                    | 3         | 3      | 0.82%   |
| WDC WD5000BEKT-75KA9T0 500GB                     | 2         | 2      | 0.54%   |
| WDC WD3200BPVT-80ZEST0 320GB                     | 2         | 2      | 0.54%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 2         | 2      | 0.54%   |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 0.54%   |
| Toshiba MK8052GSX 80GB                           | 2         | 2      | 0.54%   |
| Toshiba MK7575GSX 752GB                          | 2         | 2      | 0.54%   |
| Toshiba MK5059GSXP 500GB                         | 2         | 2      | 0.54%   |
| Toshiba MK3252GSX 320GB                          | 2         | 2      | 0.54%   |
| Toshiba MK2552GSX 250GB                          | 2         | 2      | 0.54%   |
| Seagate ST9500420AS 500GB                        | 2         | 2      | 0.54%   |
| Seagate ST9320325AS 320GB                        | 2         | 2      | 0.54%   |
| Seagate ST9250410AS 250GB                        | 2         | 2      | 0.54%   |
| Seagate ST750LM022 HN-M750MBB 752GB              | 2         | 2      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 85     | 20.49%  |
| Toshiba             | 47        | 51     | 12.84%  |
| Hitachi             | 46        | 48     | 12.57%  |
| WDC                 | 42        | 43     | 11.48%  |
| HGST                | 39        | 42     | 10.66%  |
| Samsung Electronics | 19        | 22     | 5.19%   |
| SanDisk             | 15        | 16     | 4.1%    |
| SK hynix            | 14        | 16     | 3.83%   |
| Crucial             | 14        | 14     | 3.83%   |
| Intel               | 12        | 12     | 3.28%   |
| Kingston            | 9         | 9      | 2.46%   |
| Fujitsu             | 6         | 6      | 1.64%   |
| Micron Technology   | 3         | 3      | 0.82%   |
| LITEONIT            | 2         | 2      | 0.55%   |
| LITEON              | 2         | 2      | 0.55%   |
| LDLC                | 2         | 4      | 0.55%   |
| Dogfish             | 2         | 2      | 0.55%   |
| Corsair             | 2         | 2      | 0.55%   |
| Unknown             | 1         | 1      | 0.27%   |
| TakeMS              | 1         | 1      | 0.27%   |
| Phison              | 1         | 1      | 0.27%   |
| OCZ                 | 1         | 1      | 0.27%   |
| Netac               | 1         | 1      | 0.27%   |
| Magnetic Data       | 1         | 1      | 0.27%   |
| KingSpec            | 1         | 1      | 0.27%   |
| JMicron Technology  | 1         | 1      | 0.27%   |
| Intenso             | 1         | 1      | 0.27%   |
| IBM/Hitachi         | 1         | 1      | 0.27%   |
| China               | 1         | 1      | 0.27%   |
| ASENNO              | 1         | 1      | 0.27%   |
| Apple               | 1         | 1      | 0.27%   |
| Apacer              | 1         | 1      | 0.27%   |
| A-DATA Technology   | 1         | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 85     | 28.63%  |
| Hitachi             | 46        | 48     | 17.56%  |
| Toshiba             | 44        | 48     | 16.79%  |
| WDC                 | 41        | 42     | 15.65%  |
| HGST                | 39        | 42     | 14.89%  |
| Samsung Electronics | 8         | 8      | 3.05%   |
| Fujitsu             | 6         | 6      | 2.29%   |
| Unknown             | 1         | 1      | 0.38%   |
| Magnetic Data       | 1         | 1      | 0.38%   |
| IBM/Hitachi         | 1         | 1      | 0.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 259       | 282    | 71.55%  |
| SSD     | 94        | 100    | 25.97%  |
| NVMe    | 8         | 11     | 2.21%   |
| Unknown | 1         | 1      | 0.28%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 2      | 12.5%   |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 12.5%   |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 6.25%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 6.25%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 6.25%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 6.25%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 6.25%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 6.25%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 6.25%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 37.5%   |
| Toshiba             | 5         | 5      | 31.25%  |
| HGST                | 2         | 2      | 12.5%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2066      | 3241   | 47.48%  |
| Works    | 1914      | 2531   | 43.99%  |
| Malfunc  | 354       | 394    | 8.14%   |
| Failed   | 16        | 16     | 0.37%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2915      | 61.6%   |
| AMD                              | 459       | 9.7%    |
| Samsung Electronics              | 371       | 7.84%   |
| SanDisk                          | 232       | 4.9%    |
| SK hynix                         | 191       | 4.04%   |
| Toshiba America Info Systems     | 128       | 2.7%    |
| Micron Technology                | 79        | 1.67%   |
| Kingston Technology Company      | 63        | 1.33%   |
| KIOXIA                           | 58        | 1.23%   |
| Nvidia                           | 44        | 0.93%   |
| Phison Electronics               | 42        | 0.89%   |
| Micron/Crucial Technology        | 35        | 0.74%   |
| Union Memory (Shenzhen)          | 13        | 0.27%   |
| Silicon Motion                   | 13        | 0.27%   |
| Lite-On Technology               | 13        | 0.27%   |
| Silicon Integrated Systems [SiS] | 11        | 0.23%   |
| Marvell Technology Group         | 11        | 0.23%   |
| Solid State Storage Technology   | 9         | 0.19%   |
| JMicron Technology               | 9         | 0.19%   |
| Yangtze Memory Technologies      | 7         | 0.15%   |
| Lenovo                           | 6         | 0.13%   |
| Apple                            | 4         | 0.08%   |
| ADATA Technology                 | 4         | 0.08%   |
| VIA Technologies                 | 3         | 0.06%   |
| Silicon Image                    | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| ASMedia Technology               | 3         | 0.06%   |
| ULi Electronics                  | 1         | 0.02%   |
| Realtek Semiconductor            | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 376       | 7.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 301       | 5.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 285       | 5.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 250       | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 188       | 3.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 177       | 3.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 171       | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 170       | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 148       | 2.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 128       | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 127       | 2.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 125       | 2.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 113       | 2.24%   |
| Samsung NVMe SSD Controller 980                                                  | 105       | 2.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 104       | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 91        | 1.8%    |
| Micron Non-Volatile memory controller                                            | 79        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 78        | 1.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 69        | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 69        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 62        | 1.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 61        | 1.21%   |
| SK hynix Non-Volatile memory controller                                          | 56        | 1.11%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 55        | 1.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 55        | 1.09%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 52        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                            | 52        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 52        | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 46        | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 46        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 44        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 41        | 0.81%   |
| Intel SSD 660P Series                                                            | 41        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 40        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 40        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 40        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                              | 38        | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 37        | 0.73%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 34        | 0.67%   |
| SK hynix BC511                                                                   | 33        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2888      | 58.93%  |
| NVMe | 1326      | 27.06%  |
| RAID | 391       | 7.98%   |
| IDE  | 296       | 6.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3426      | 84.22%  |
| AMD    | 640       | 15.73%  |
| ARM    | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 85        | 2.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 1.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 60        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 57        | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 55        | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 53        | 1.3%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 49        | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 47        | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 47        | 1.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 45        | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 42        | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 42        | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 41        | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 41        | 1.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 41        | 1.01%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 40        | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 39        | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 38        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 37        | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 34        | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 33        | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 31        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 31        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 28        | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 28        | 0.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 28        | 0.69%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 27        | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 26        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 26        | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 26        | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 26        | 0.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 25        | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 25        | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 25        | 0.61%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 24        | 0.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 23        | 0.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 23        | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 22        | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 22        | 0.54%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 22        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1000      | 24.57%  |
| Intel Core i7           | 913       | 22.43%  |
| Intel Core i3           | 347       | 8.53%   |
| Other                   | 309       | 7.59%   |
| Intel Celeron           | 234       | 5.75%   |
| Intel Core 2 Duo        | 227       | 5.58%   |
| AMD Ryzen 5             | 141       | 3.46%   |
| Intel Pentium           | 121       | 2.97%   |
| AMD Ryzen 7             | 109       | 2.68%   |
| Intel Atom              | 89        | 2.19%   |
| Intel Pentium Dual-Core | 49        | 1.2%    |
| AMD E1                  | 48        | 1.18%   |
| AMD A4                  | 36        | 0.88%   |
| AMD E2                  | 31        | 0.76%   |
| AMD A6                  | 30        | 0.74%   |
| Intel Pentium Dual      | 29        | 0.71%   |
| AMD Ryzen 7 PRO         | 28        | 0.69%   |
| Intel Core 2            | 25        | 0.61%   |
| Intel Core i9           | 23        | 0.57%   |
| AMD Ryzen 9             | 23        | 0.57%   |
| AMD E                   | 23        | 0.57%   |
| Intel Genuine           | 20        | 0.49%   |
| AMD A8                  | 17        | 0.42%   |
| AMD Ryzen 3             | 15        | 0.37%   |
| AMD Athlon              | 14        | 0.34%   |
| Intel Pentium Silver    | 13        | 0.32%   |
| Intel Xeon              | 11        | 0.27%   |
| AMD Ryzen 5 PRO         | 11        | 0.27%   |
| Intel Celeron Dual-Core | 10        | 0.25%   |
| Intel Pentium M         | 9         | 0.22%   |
| Intel Core m3           | 9         | 0.22%   |
| AMD Athlon II           | 9         | 0.22%   |
| Intel Celeron M         | 8         | 0.2%    |
| AMD Athlon X2           | 8         | 0.2%    |
| AMD Athlon II Dual-Core | 8         | 0.2%    |
| AMD Turion 64 X2 Mobile | 7         | 0.17%   |
| AMD Athlon 64 X2        | 7         | 0.17%   |
| AMD A12                 | 7         | 0.17%   |
| AMD A10                 | 6         | 0.15%   |
| AMD C-60                | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2037      | 50.06%  |
| 4       | 1399      | 34.38%  |
| 6       | 279       | 6.86%   |
| 8       | 202       | 4.96%   |
| 1       | 102       | 2.51%   |
| 12      | 20        | 0.49%   |
| 14      | 13        | 0.32%   |
| Unknown | 9         | 0.22%   |
| 10      | 8         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4066      | 99.93%  |
| 2      | 3         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2898      | 71.12%  |
| 1       | 1168      | 28.66%  |
| Unknown | 9         | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3985      | 97.79%  |
| Unknown        | 48        | 1.18%   |
| 32-bit         | 40        | 0.98%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 709       | 16.95%  |
| 0x306a9    | 261       | 6.24%   |
| 0x206a7    | 252       | 6.02%   |
| 0x806ec    | 169       | 4.04%   |
| 0x906ea    | 161       | 3.85%   |
| 0x806c1    | 157       | 3.75%   |
| 0x1067a    | 155       | 3.7%    |
| 0x406e3    | 130       | 3.11%   |
| 0x306c3    | 129       | 3.08%   |
| 0x306d4    | 125       | 2.99%   |
| 0x40651    | 124       | 2.96%   |
| 0x806ea    | 123       | 2.94%   |
| 0x806e9    | 108       | 2.58%   |
| 0x20655    | 108       | 2.58%   |
| 0x6fd      | 79        | 1.89%   |
| 0x506e3    | 72        | 1.72%   |
| 0xa0652    | 63        | 1.51%   |
| 0x906e9    | 63        | 1.51%   |
| 0x08108109 | 58        | 1.39%   |
| 0x08600106 | 55        | 1.31%   |
| 0x10676    | 51        | 1.22%   |
| 0x706e5    | 48        | 1.15%   |
| 0x406c4    | 46        | 1.1%    |
| 0x30678    | 46        | 1.1%    |
| 0x806d1    | 41        | 0.98%   |
| 0x07030105 | 39        | 0.93%   |
| 0x806eb    | 38        | 0.91%   |
| 0x706a1    | 37        | 0.88%   |
| 0x406c3    | 37        | 0.88%   |
| 0x08108102 | 37        | 0.88%   |
| 0x506c9    | 34        | 0.81%   |
| 0x20652    | 33        | 0.79%   |
| 0x0a50000c | 31        | 0.74%   |
| 0x05000119 | 31        | 0.74%   |
| 0x06006705 | 29        | 0.69%   |
| 0x906ed    | 28        | 0.67%   |
| 0x906a3    | 28        | 0.67%   |
| 0x0700010f | 25        | 0.6%    |
| 0x706a8    | 22        | 0.53%   |
| 0x08608103 | 21        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 834       | 20.49%  |
| Haswell          | 312       | 7.67%   |
| IvyBridge        | 301       | 7.4%    |
| SandyBridge      | 279       | 6.86%   |
| Skylake          | 243       | 5.97%   |
| Penryn           | 233       | 5.72%   |
| TigerLake        | 187       | 4.59%   |
| Silvermont       | 161       | 3.96%   |
| Westmere         | 159       | 3.91%   |
| Broadwell        | 146       | 3.59%   |
| Core             | 145       | 3.56%   |
| Zen 2            | 114       | 2.8%    |
| Zen+             | 106       | 2.6%    |
| Icelake          | 97        | 2.38%   |
| CometLake        | 84        | 2.06%   |
| Unknown          | 74        | 1.82%   |
| Goldmont plus    | 69        | 1.7%    |
| Puma             | 59        | 1.45%   |
| Bobcat           | 56        | 1.38%   |
| Zen 3            | 52        | 1.28%   |
| Excavator        | 49        | 1.2%    |
| Goldmont         | 42        | 1.03%   |
| Bonnell          | 38        | 0.93%   |
| Jaguar           | 34        | 0.84%   |
| Zen              | 31        | 0.76%   |
| Alderlake Hybrid | 31        | 0.76%   |
| K8 Hammer        | 24        | 0.59%   |
| K10              | 24        | 0.59%   |
| P6               | 21        | 0.52%   |
| Nehalem          | 18        | 0.44%   |
| Piledriver       | 14        | 0.34%   |
| K10 Llano        | 12        | 0.29%   |
| K8 & K10 hybrid  | 11        | 0.27%   |
| Tremont          | 4         | 0.1%    |
| NetBurst         | 3         | 0.07%   |
| Steamroller      | 2         | 0.05%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3063      | 58.45%  |
| Nvidia                           | 1265      | 24.14%  |
| AMD                              | 903       | 17.23%  |
| Silicon Integrated Systems [SiS] | 7         | 0.13%   |
| VIA Technologies                 | 2         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 278       | 5.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 248       | 4.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 203       | 3.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 177       | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 146       | 2.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 141       | 2.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 140       | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 139       | 2.58%   |
| Intel UHD Graphics 620                                                                   | 132       | 2.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 130       | 2.41%   |
| Intel HD Graphics 5500                                                                   | 129       | 2.39%   |
| Intel HD Graphics 620                                                                    | 125       | 2.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 119       | 2.21%   |
| AMD Renoir                                                                               | 111       | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 107       | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 91        | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 84        | 1.56%   |
| Intel HD Graphics 530                                                                    | 79        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 70        | 1.3%    |
| Intel HD Graphics 630                                                                    | 68        | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 67        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 59        | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 59        | 1.09%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 57        | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 48        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 48        | 0.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 47        | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 46        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 43        | 0.8%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 42        | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 40        | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 39        | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 37        | 0.69%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 36        | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 33        | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 33        | 0.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 33        | 0.61%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 33        | 0.61%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 32        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1960      | 48.05%  |
| Intel + Nvidia | 946       | 23.19%  |
| 1 x AMD        | 616       | 15.1%   |
| 1 x Nvidia     | 247       | 6.06%   |
| Intel + AMD    | 155       | 3.8%    |
| AMD + Nvidia   | 67        | 1.64%   |
| 2 x AMD        | 66        | 1.62%   |
| 1 x SiS        | 7         | 0.17%   |
| 2 x Nvidia     | 6         | 0.15%   |
| Other          | 4         | 0.1%    |
| 2 x Intel      | 3         | 0.07%   |
| 1 x VIA        | 2         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3467      | 84.4%   |
| Proprietary | 536       | 13.05%  |
| Unknown     | 105       | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2490      | 60.07%  |
| 0.01-0.5   | 563       | 13.58%  |
| 1.01-2.0   | 486       | 11.72%  |
| 0.51-1.0   | 243       | 5.86%   |
| 3.01-4.0   | 238       | 5.74%   |
| 5.01-6.0   | 68        | 1.64%   |
| 7.01-8.0   | 35        | 0.84%   |
| 2.01-3.0   | 20        | 0.48%   |
| 8.01-16.0  | 2         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 955       | 20.58%  |
| Chimei Innolux          | 609       | 13.13%  |
| LG Display              | 605       | 13.04%  |
| BOE                     | 548       | 11.81%  |
| Samsung Electronics     | 499       | 10.75%  |
| Sharp                   | 155       | 3.34%   |
| Chi Mei Optoelectronics | 128       | 2.76%   |
| Dell                    | 122       | 2.63%   |
| Iiyama                  | 97        | 2.09%   |
| Apple                   | 87        | 1.88%   |
| Lenovo                  | 81        | 1.75%   |
| Acer                    | 63        | 1.36%   |
| PANDA                   | 61        | 1.31%   |
| LG Philips              | 58        | 1.25%   |
| Hewlett-Packard         | 54        | 1.16%   |
| Goldstar                | 48        | 1.03%   |
| InfoVision              | 47        | 1.01%   |
| BenQ                    | 39        | 0.84%   |
| Ancor Communications    | 38        | 0.82%   |
| AOC                     | 34        | 0.73%   |
| Philips                 | 33        | 0.71%   |
| ViewSonic               | 25        | 0.54%   |
| CPT                     | 18        | 0.39%   |
| CSO                     | 16        | 0.34%   |
| ASUSTek Computer        | 15        | 0.32%   |
| HannStar                | 14        | 0.3%    |
| Sony                    | 13        | 0.28%   |
| Fujitsu Siemens         | 13        | 0.28%   |
| Vestel Elektronik       | 9         | 0.19%   |
| Toshiba                 | 8         | 0.17%   |
| Seiko/Epson             | 8         | 0.17%   |
| ANX                     | 7         | 0.15%   |
| LGD                     | 6         | 0.13%   |
| Analogix                | 6         | 0.13%   |
| Unknown                 | 5         | 0.11%   |
| TMX                     | 5         | 0.11%   |
| Panasonic               | 5         | 0.11%   |
| LPL                     | 5         | 0.11%   |
| Packard Bell            | 4         | 0.09%   |
| JDI                     | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 41        | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 32        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 32        | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 28        | 0.6%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 24        | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 24        | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 23        | 0.49%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 23        | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 23        | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 23        | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 21        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 20        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 20        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 20        | 0.43%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 18        | 0.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 18        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 17        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 17        | 0.36%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 17        | 0.36%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 15        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 15        | 0.32%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 14        | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 14        | 0.3%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 13        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 13        | 0.28%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 12        | 0.26%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 12        | 0.26%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 12        | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 12        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1855      | 43.1%   |
| 1366x768 (WXGA)    | 1092      | 25.37%  |
| 1600x900 (HD+)     | 420       | 9.76%   |
| 1280x800 (WXGA)    | 167       | 3.88%   |
| 3840x2160 (4K)     | 140       | 3.25%   |
| 1440x900 (WXGA+)   | 108       | 2.51%   |
| 1920x1200 (WUXGA)  | 101       | 2.35%   |
| 2560x1440 (QHD)    | 92        | 2.14%   |
| 1680x1050 (WSXGA+) | 50        | 1.16%   |
| 1024x600           | 30        | 0.7%    |
| 1280x1024 (SXGA)   | 28        | 0.65%   |
| 2560x1600          | 22        | 0.51%   |
| 2880x1800          | 19        | 0.44%   |
| 3440x1440          | 18        | 0.42%   |
| 2160x1440          | 17        | 0.39%   |
| 3840x2400          | 14        | 0.33%   |
| 800x1280           | 13        | 0.3%    |
| 3200x1800 (QHD+)   | 11        | 0.26%   |
| 2560x1080          | 11        | 0.26%   |
| Unknown            | 10        | 0.23%   |
| 1360x768           | 9         | 0.21%   |
| 1920x540           | 8         | 0.19%   |
| 3840x1080          | 6         | 0.14%   |
| 3000x2000          | 6         | 0.14%   |
| 1680x945           | 6         | 0.14%   |
| 1600x1200          | 6         | 0.14%   |
| 1024x768 (XGA)     | 5         | 0.12%   |
| 3840x1200          | 4         | 0.09%   |
| 1920x515           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 3072x1920          | 3         | 0.07%   |
| 2288x1287          | 3         | 0.07%   |
| 5760x2160          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 2048x1152          | 2         | 0.05%   |
| 720x1280           | 1         | 0.02%   |
| 4480x1600          | 1         | 0.02%   |
| 4480x1440          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1724      | 37.2%   |
| 13      | 651       | 14.05%  |
| 17      | 646       | 13.94%  |
| 14      | 453       | 9.78%   |
| 24      | 195       | 4.21%   |
| 23      | 143       | 3.09%   |
| 27      | 129       | 2.78%   |
| 12      | 124       | 2.68%   |
| 21      | 98        | 2.11%   |
| Unknown | 77        | 1.66%   |
| 11      | 62        | 1.34%   |
| 16      | 43        | 0.93%   |
| 18      | 41        | 0.88%   |
| 10      | 41        | 0.88%   |
| 19      | 33        | 0.71%   |
| 22      | 30        | 0.65%   |
| 34      | 28        | 0.6%    |
| 20      | 19        | 0.41%   |
| 31      | 16        | 0.35%   |
| 84      | 13        | 0.28%   |
| 72      | 13        | 0.28%   |
| 25      | 8         | 0.17%   |
| 54      | 6         | 0.13%   |
| 32      | 6         | 0.13%   |
| 33      | 4         | 0.09%   |
| 26      | 4         | 0.09%   |
| 52      | 3         | 0.06%   |
| 49      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 40      | 3         | 0.06%   |
| 48      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 142     | 1         | 0.02%   |
| 74      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 38      | 1         | 0.02%   |
| 37      | 1         | 0.02%   |
| 35      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2440      | 53.15%  |
| 351-400        | 733       | 15.97%  |
| 201-300        | 579       | 12.61%  |
| 501-600        | 432       | 9.41%   |
| 401-500        | 205       | 4.47%   |
| Unknown        | 77        | 1.68%   |
| 701-800        | 37        | 0.81%   |
| 601-700        | 30        | 0.65%   |
| 1501-2000      | 27        | 0.59%   |
| 1001-1500      | 21        | 0.46%   |
| 801-900        | 7         | 0.15%   |
| 101-200        | 2         | 0.04%   |
| More than 2000 | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3407      | 83.83%  |
| 16/10   | 472       | 11.61%  |
| Unknown | 40        | 0.98%   |
| 3/2     | 35        | 0.86%   |
| 21/9    | 31        | 0.76%   |
| 5/4     | 28        | 0.69%   |
| 4/3     | 22        | 0.54%   |
| 0.62    | 14        | 0.34%   |
| 32/9    | 5         | 0.12%   |
| 3.20    | 4         | 0.1%    |
| 3.73    | 3         | 0.07%   |
| 3.88    | 1         | 0.02%   |
| 1.00    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1741      | 37.64%  |
| 81-90          | 806       | 17.42%  |
| 121-130        | 539       | 11.65%  |
| 201-250        | 376       | 8.13%   |
| 71-80          | 299       | 6.46%   |
| 301-350        | 132       | 2.85%   |
| 61-70          | 117       | 2.53%   |
| 131-140        | 96        | 2.08%   |
| 151-200        | 84        | 1.82%   |
| Unknown        | 77        | 1.66%   |
| 251-300        | 64        | 1.38%   |
| 51-60          | 62        | 1.34%   |
| 351-500        | 56        | 1.21%   |
| 141-150        | 46        | 0.99%   |
| 41-50          | 42        | 0.91%   |
| More than 1000 | 39        | 0.84%   |
| 111-120        | 21        | 0.45%   |
| 501-1000       | 15        | 0.32%   |
| 91-100         | 12        | 0.26%   |
| 1-40           | 2         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1762      | 38.78%  |
| 101-120       | 1432      | 31.51%  |
| 51-100        | 826       | 18.18%  |
| 161-240       | 302       | 6.65%   |
| More than 240 | 115       | 2.53%   |
| Unknown       | 77        | 1.69%   |
| 1-50          | 30        | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3302      | 79.34%  |
| 2     | 658       | 15.81%  |
| 0     | 115       | 2.76%   |
| 3     | 81        | 1.95%   |
| 4     | 4         | 0.1%    |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2220      | 34.25%  |
| Realtek Semiconductor             | 2078      | 32.06%  |
| Qualcomm Atheros                  | 1021      | 15.75%  |
| Broadcom                          | 436       | 6.73%   |
| Broadcom Limited                  | 89        | 1.37%   |
| Marvell Technology Group          | 86        | 1.33%   |
| Ralink                            | 71        | 1.1%    |
| MediaTek                          | 55        | 0.85%   |
| Dell                              | 40        | 0.62%   |
| ASIX Electronics                  | 33        | 0.51%   |
| Nvidia                            | 30        | 0.46%   |
| Samsung Electronics               | 26        | 0.4%    |
| Ericsson Business Mobile Networks | 24        | 0.37%   |
| Xiaomi                            | 21        | 0.32%   |
| DisplayLink                       | 21        | 0.32%   |
| TP-Link                           | 18        | 0.28%   |
| Sierra Wireless                   | 18        | 0.28%   |
| JMicron Technology                | 16        | 0.25%   |
| Huawei Technologies               | 16        | 0.25%   |
| Ralink Technology                 | 14        | 0.22%   |
| Lenovo                            | 14        | 0.22%   |
| Qualcomm                          | 13        | 0.2%    |
| NetGear                           | 13        | 0.2%    |
| Attansic Technology               | 13        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 10        | 0.15%   |
| Hewlett-Packard                   | 10        | 0.15%   |
| OPPO Electronics                  | 6         | 0.09%   |
| Google                            | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.06%   |
| ICS Advent                        | 4         | 0.06%   |
| Fibocom                           | 4         | 0.06%   |
| D-Link                            | 4         | 0.06%   |
| Apple                             | 4         | 0.06%   |
| VIA Technologies                  | 3         | 0.05%   |
| U-Blox                            | 3         | 0.05%   |
| Toshiba                           | 3         | 0.05%   |
| D-Link System                     | 3         | 0.05%   |
| Belkin Components                 | 3         | 0.05%   |
| Arduino SA                        | 3         | 0.05%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1258      | 16.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 339       | 4.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 226       | 2.89%   |
| Intel Wi-Fi 6 AX200                                                     | 200       | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 171       | 2.19%   |
| Intel Wireless 8265 / 8275                                              | 167       | 2.14%   |
| Intel Wireless 7265                                                     | 157       | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 148       | 1.89%   |
| Intel Wi-Fi 6 AX201                                                     | 145       | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 142       | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 134       | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 129       | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 127       | 1.63%   |
| Intel Wireless 8260                                                     | 119       | 1.52%   |
| Intel Wireless 7260                                                     | 118       | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 99        | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 98        | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 98        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 94        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 86        | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 83        | 1.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 70        | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 62        | 0.79%   |
| Intel Wireless 3165                                                     | 62        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 59        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 55        | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 54        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 53        | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                   | 51        | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 49        | 0.63%   |
| Intel Wireless-AC 9260                                                  | 49        | 0.63%   |
| Intel WiFi Link 5100                                                    | 48        | 0.61%   |
| Intel Ethernet Connection I219-LM                                       | 45        | 0.58%   |
| Intel Ethernet Connection I217-LM                                       | 45        | 0.58%   |
| Intel Wireless 3160                                                     | 44        | 0.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 0.54%   |
| Intel Centrino Wireless-N 2230                                          | 42        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2105      | 50.76%  |
| Qualcomm Atheros                      | 841       | 20.28%  |
| Realtek Semiconductor                 | 591       | 14.25%  |
| Broadcom                              | 315       | 7.6%    |
| Ralink                                | 71        | 1.71%   |
| Broadcom Limited                      | 59        | 1.42%   |
| MediaTek                              | 49        | 1.18%   |
| Dell                                  | 21        | 0.51%   |
| Sierra Wireless                       | 18        | 0.43%   |
| TP-Link                               | 15        | 0.36%   |
| Ralink Technology                     | 14        | 0.34%   |
| NetGear                               | 10        | 0.24%   |
| Qualcomm                              | 8         | 0.19%   |
| Hewlett-Packard                       | 6         | 0.14%   |
| Fibocom                               | 4         | 0.1%    |
| D-Link System                         | 3         | 0.07%   |
| D-Link                                | 3         | 0.07%   |
| Belkin Components                     | 3         | 0.07%   |
| ASUSTek Computer                      | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qualcomm Atheros Communications       | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| Edimax Technology                     | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 200       | 4.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 171       | 4.1%    |
| Intel Wireless 8265 / 8275                                              | 167       | 4%      |
| Intel Wireless 7265                                                     | 157       | 3.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 148       | 3.55%   |
| Intel Wi-Fi 6 AX201                                                     | 145       | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 134       | 3.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 129       | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 127       | 3.05%   |
| Intel Wireless 8260                                                     | 119       | 2.85%   |
| Intel Wireless 7260                                                     | 118       | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 99        | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 98        | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 98        | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 94        | 2.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 86        | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 83        | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 1.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 83        | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 70        | 1.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 62        | 1.49%   |
| Intel Wireless 3165                                                     | 62        | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 53        | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 49        | 1.18%   |
| Intel Wireless-AC 9260                                                  | 49        | 1.18%   |
| Intel WiFi Link 5100                                                    | 48        | 1.15%   |
| Intel Wireless 3160                                                     | 44        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 42        | 1.01%   |
| Intel Centrino Wireless-N 2230                                          | 42        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 37        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 37        | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 36        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 36        | 0.86%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 33        | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 33        | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 30        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 30        | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 30        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1875      | 53.27%  |
| Intel                            | 797       | 22.64%  |
| Qualcomm Atheros                 | 317       | 9.01%   |
| Broadcom                         | 167       | 4.74%   |
| Marvell Technology Group         | 86        | 2.44%   |
| Broadcom Limited                 | 33        | 0.94%   |
| ASIX Electronics                 | 33        | 0.94%   |
| Nvidia                           | 30        | 0.85%   |
| Samsung Electronics              | 25        | 0.71%   |
| Xiaomi                           | 21        | 0.6%    |
| DisplayLink                      | 21        | 0.6%    |
| JMicron Technology               | 16        | 0.45%   |
| Lenovo                           | 14        | 0.4%    |
| Attansic Technology              | 13        | 0.37%   |
| Silicon Integrated Systems [SiS] | 10        | 0.28%   |
| Huawei Technologies              | 10        | 0.28%   |
| OPPO Electronics                 | 6         | 0.17%   |
| MediaTek                         | 6         | 0.17%   |
| Qualcomm                         | 5         | 0.14%   |
| Google                           | 5         | 0.14%   |
| ICS Advent                       | 4         | 0.11%   |
| Apple                            | 4         | 0.11%   |
| TP-Link                          | 3         | 0.09%   |
| NetGear                          | 3         | 0.09%   |
| VIA Technologies                 | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.06%   |
| Cypress Semiconductor            | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| ULi Electronics                  | 1         | 0.03%   |
| Motorola PCS                     | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| Hisense                          | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| Archos                           | 1         | 0.03%   |
| Aquantia                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1258      | 35.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 339       | 9.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 226       | 6.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 142       | 3.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 59        | 1.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 55        | 1.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 54        | 1.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 51        | 1.43%   |
| Intel Ethernet Connection I219-LM                                 | 45        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.27%   |
| Intel Ethernet Connection I218-LM                                 | 37        | 1.04%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 1.01%   |
| Intel 82567LM Gigabit Network Connection                          | 34        | 0.96%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 30        | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 30        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 29        | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 26        | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 26        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 24        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 23        | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 23        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 22        | 0.62%   |
| Intel Ethernet Connection (13) I219-V                             | 22        | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 22        | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 21        | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 17        | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 17        | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.45%   |
| Intel Ethernet Connection (13) I219-LM                            | 16        | 0.45%   |
| Intel Ethernet Connection (11) I219-LM                            | 16        | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 16        | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3998      | 53.73%  |
| Ethernet | 3355      | 45.09%  |
| Modem    | 82        | 1.1%    |
| Unknown  | 6         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3223      | 74.61%  |
| Ethernet | 1097      | 25.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3021      | 74.19%  |
| 1     | 957       | 23.5%   |
| 0     | 56        | 1.38%   |
| 3     | 38        | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2849      | 68.14%  |
| Yes  | 1332      | 31.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1618      | 52.04%  |
| Realtek Semiconductor           | 252       | 8.11%   |
| IMC Networks                    | 231       | 7.43%   |
| Qualcomm Atheros Communications | 218       | 7.01%   |
| Broadcom                        | 156       | 5.02%   |
| Lite-On Technology              | 113       | 3.63%   |
| Foxconn / Hon Hai               | 95        | 3.06%   |
| Apple                           | 86        | 2.77%   |
| Dell                            | 76        | 2.44%   |
| Cambridge Silicon Radio         | 50        | 1.61%   |
| Realtek                         | 36        | 1.16%   |
| Hewlett-Packard                 | 36        | 1.16%   |
| Toshiba                         | 33        | 1.06%   |
| Ralink                          | 30        | 0.96%   |
| ASUSTek Computer                | 20        | 0.64%   |
| Ralink Technology               | 19        | 0.61%   |
| Alps Electric                   | 13        | 0.42%   |
| Foxconn International           | 12        | 0.39%   |
| MediaTek                        | 5         | 0.16%   |
| Chicony Electronics             | 5         | 0.16%   |
| USI                             | 2         | 0.06%   |
| TP-Link                         | 1         | 0.03%   |
| Syntek                          | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 634       | 20.39%  |
| Intel AX201 Bluetooth                               | 331       | 10.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 268       | 8.62%   |
| Intel AX200 Bluetooth                               | 190       | 6.11%   |
| Realtek Bluetooth Radio                             | 155       | 4.98%   |
| IMC Networks Bluetooth Device                       | 97        | 3.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 88        | 2.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 66        | 2.12%   |
| IMC Networks Bluetooth Radio                        | 62        | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 61        | 1.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 47        | 1.51%   |
| Apple Bluetooth Host Controller                     | 46        | 1.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 42        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 41        | 1.32%   |
| Realtek Bluetooth Radio                             | 36        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 36        | 1.16%   |
| Lite-On Bluetooth Device                            | 34        | 1.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 32        | 1.03%   |
| Dell DW375 Bluetooth Module                         | 32        | 1.03%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.96%   |
| Intel Bluetooth Device                              | 28        | 0.9%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 24        | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 24        | 0.77%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 23        | 0.74%   |
| Intel AX210 Bluetooth                               | 21        | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.64%   |
| IMC Networks Wireless_Device                        | 19        | 0.61%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 17        | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.55%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 16        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 15        | 0.48%   |
| IMC Networks Bluetooth                              | 14        | 0.45%   |
| Toshiba Bluetooth Device                            | 13        | 0.42%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 13        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3327      | 66.08%  |
| AMD                                          | 758       | 15.05%  |
| Nvidia                                       | 618       | 12.27%  |
| Realtek Semiconductor                        | 56        | 1.11%   |
| GN Netcom                                    | 30        | 0.6%    |
| C-Media Electronics                          | 27        | 0.54%   |
| Logitech                                     | 26        | 0.52%   |
| Plantronics                                  | 20        | 0.4%    |
| Kingston Technology                          | 18        | 0.36%   |
| JMTek                                        | 18        | 0.36%   |
| Lenovo                                       | 13        | 0.26%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.22%   |
| Corsair                                      | 10        | 0.2%    |
| Hewlett-Packard                              | 9         | 0.18%   |
| SteelSeries ApS                              | 6         | 0.12%   |
| Sennheiser Communications                    | 5         | 0.1%    |
| Focusrite-Novation                           | 5         | 0.1%    |
| Texas Instruments                            | 4         | 0.08%   |
| VIA Technologies                             | 3         | 0.06%   |
| M-Audio                                      | 3         | 0.06%   |
| Elitegroup Computer Systems (ECS)            | 3         | 0.06%   |
| Conexant Systems                             | 3         | 0.06%   |
| Blue Microphones                             | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| ZOOM                                         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |
| Razer USA                                    | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.04%   |
| No brand                                     | 2         | 0.04%   |
| Generalplus Technology                       | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Cambridge Audio                              | 2         | 0.04%   |
| Barco Display Systems                        | 2         | 0.04%   |
| Avid Technology                              | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| Yealink Network Technology                   | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| WL80                                         | 1         | 0.02%   |
| ULi Electronics                              | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 428       | 7.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 355       | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 323       | 5.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 226       | 3.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 225       | 3.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 213       | 3.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 186       | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 177       | 2.93%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 166       | 2.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 166       | 2.75%   |
| Intel 8 Series HD Audio Controller                                                                | 147       | 2.44%   |
| AMD FCH Azalia Controller                                                                         | 147       | 2.44%   |
| Intel Broadwell-U Audio Controller                                                                | 146       | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 145       | 2.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 145       | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 141       | 2.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 132       | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 127       | 2.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 126       | 2.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 104       | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 97        | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 85        | 1.41%   |
| Intel CM238 HD Audio Controller                                                                   | 82        | 1.36%   |
| Intel Comet Lake PCH cAVS                                                                         | 76        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 73        | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 73        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 69        | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 65        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 63        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 63        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 58        | 0.96%   |
| Realtek Semiconductor USB Audio                                                                   | 55        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 54        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 53        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 53        | 0.88%   |
| AMD Wrestler HDMI Audio                                                                           | 52        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 50        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 49        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 42        | 0.7%    |
| AMD High Definition Audio Controller                                                              | 39        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 894       | 29.66%  |
| SK hynix                                         | 804       | 26.68%  |
| Micron Technology                                | 361       | 11.98%  |
| Unknown                                          | 215       | 7.13%   |
| Kingston                                         | 205       | 6.8%    |
| Crucial                                          | 149       | 4.94%   |
| Elpida                                           | 63        | 2.09%   |
| Corsair                                          | 52        | 1.73%   |
| Ramaxel Technology                               | 50        | 1.66%   |
| A-DATA Technology                                | 39        | 1.29%   |
| Nanya Technology                                 | 38        | 1.26%   |
| G.Skill                                          | 35        | 1.16%   |
| Unknown (ABCD)                                   | 32        | 1.06%   |
| Transcend                                        | 10        | 0.33%   |
| Unknown                                          | 7         | 0.23%   |
| Patriot                                          | 5         | 0.17%   |
| ASint Technology                                 | 5         | 0.17%   |
| V-Color                                          | 3         | 0.1%    |
| Toshiba                                          | 3         | 0.1%    |
| SHARETRONIC                                      | 3         | 0.1%    |
| PNY                                              | 3         | 0.1%    |
| Apacer                                           | 3         | 0.1%    |
| Timetec                                          | 2         | 0.07%   |
| TEXTORM                                          | 2         | 0.07%   |
| Team                                             | 2         | 0.07%   |
| Goldkey                                          | 2         | 0.07%   |
| Unknown (F301)                                   | 1         | 0.03%   |
| Unknown (0x8634)                                 | 1         | 0.03%   |
| Unknown (0x7301)                                 | 1         | 0.03%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.03%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.03%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.03%   |
| Unknown (07FB)                                   | 1         | 0.03%   |
| Unknown (01F3)                                   | 1         | 0.03%   |
| Silicon Power                                    | 1         | 0.03%   |
| Qimonda                                          | 1         | 0.03%   |
| PKI                                              | 1         | 0.03%   |
| OnBoard                                          | 1         | 0.03%   |
| Netlist                                          | 1         | 0.03%   |
| Neo Forza                                        | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 46        | 1.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 45        | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 44        | 1.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 1.3%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 40        | 1.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 39        | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 32        | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 31        | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 31        | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 31        | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 30        | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 0.95%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 29        | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.85%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 24        | 0.76%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 22        | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.7%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 17        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 17        | 0.54%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.51%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.51%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 16        | 0.51%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 16        | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 15        | 0.47%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 15        | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 14        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 13        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 13        | 0.41%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 13        | 0.41%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 13        | 0.41%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 13        | 0.41%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 13        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1184      | 45.82%  |
| DDR3    | 934       | 36.15%  |
| DDR2    | 131       | 5.07%   |
| LPDDR4  | 120       | 4.64%   |
| LPDDR3  | 93        | 3.6%    |
| SDRAM   | 56        | 2.17%   |
| Unknown | 21        | 0.81%   |
| LPDDR5  | 15        | 0.58%   |
| DDR     | 13        | 0.5%    |
| DDR5    | 11        | 0.43%   |
| DRAM    | 6         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2313      | 89.62%  |
| Row Of Chips | 237       | 9.18%   |
| Chip         | 14        | 0.54%   |
| DIMM         | 11        | 0.43%   |
| Unknown      | 6         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 996       | 35.83%  |
| 4096  | 917       | 32.99%  |
| 2048  | 368       | 13.24%  |
| 16384 | 351       | 12.63%  |
| 1024  | 88        | 3.17%   |
| 32768 | 51        | 1.83%   |
| 512   | 8         | 0.29%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 671       | 24.21%  |
| 2667    | 568       | 20.49%  |
| 3200    | 441       | 15.91%  |
| 2400    | 194       | 7%      |
| 2133    | 146       | 5.27%   |
| 1334    | 145       | 5.23%   |
| 1333    | 96        | 3.46%   |
| 667     | 76        | 2.74%   |
| 4267    | 57        | 2.06%   |
| Unknown | 47        | 1.7%    |
| 3266    | 45        | 1.62%   |
| 1067    | 42        | 1.52%   |
| 1867    | 36        | 1.3%    |
| 800     | 33        | 1.19%   |
| 4199    | 28        | 1.01%   |
| 2048    | 24        | 0.87%   |
| 1066    | 21        | 0.76%   |
| 4800    | 16        | 0.58%   |
| 6400    | 15        | 0.54%   |
| 975     | 15        | 0.54%   |
| 533     | 13        | 0.47%   |
| 4266    | 10        | 0.36%   |
| 8400    | 8         | 0.29%   |
| 1866    | 5         | 0.18%   |
| 2933    | 4         | 0.14%   |
| 3000    | 3         | 0.11%   |
| 333     | 3         | 0.11%   |
| 3733    | 2         | 0.07%   |
| 1777    | 2         | 0.07%   |
| 1639    | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 933     | 1         | 0.04%   |
| 266     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 38.46%  |
| Canon               | 9         | 23.08%  |
| Seiko Epson         | 4         | 10.26%  |
| Samsung Electronics | 4         | 10.26%  |
| Brother Industries  | 4         | 10.26%  |
| Xiaomi              | 1         | 2.56%   |
| STMicroelectronics  | 1         | 2.56%   |
| QinHeng Electronics | 1         | 2.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 10.26%  |
| HP DeskJet 3630 series                                    | 3         | 7.69%   |
| Seiko Epson WF-2830 Series                                | 2         | 5.13%   |
| Canon PIXMA MG3600 Series                                 | 2         | 5.13%   |
| Canon PIXMA MG2500 Series                                 | 2         | 5.13%   |
| Xiaomi MiMouse 2                                          | 1         | 2.56%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.56%   |
| Seiko Epson XP-255 257 Series                             | 1         | 2.56%   |
| Seiko Epson XP-2150 Series                                | 1         | 2.56%   |
| Samsung SCX-3200 Series                                   | 1         | 2.56%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.56%   |
| Samsung M2070 Series                                      | 1         | 2.56%   |
| Samsung M2020 Series                                      | 1         | 2.56%   |
| QinHeng CH340S                                            | 1         | 2.56%   |
| HP Photosmart B010 series                                 | 1         | 2.56%   |
| HP OfficeJet Pro 69                                       | 1         | 2.56%   |
| HP OfficeJet 3830 series                                  | 1         | 2.56%   |
| HP ENVY Photo 6200 series                                 | 1         | 2.56%   |
| HP ENVY 5540 series                                       | 1         | 2.56%   |
| HP ENVY 4500 series                                       | 1         | 2.56%   |
| HP Deskjet F4500 series                                   | 1         | 2.56%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2.56%   |
| Canon TS6100 series                                       | 1         | 2.56%   |
| Canon PIXMA MP495                                         | 1         | 2.56%   |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.56%   |
| Canon PIXMA MG3500 Series                                 | 1         | 2.56%   |
| Canon MG2100 series                                       | 1         | 2.56%   |
| Brother MFC-L8690CDW series                               | 1         | 2.56%   |
| Brother MFC-L2710DW series                                | 1         | 2.56%   |
| Brother MFC-1810                                          | 1         | 2.56%   |
| Brother DCP-L3550CDW series                               | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 50%     |
| Seiko Epson     | 4         | 40%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 2         | 20%     |
| Seiko Epson Scanner                           | 1         | 10%     |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 10%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 10%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 10%     |
| HP ScanJet 3570c                              | 1         | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 10%     |
| Canon CanoScan N650U/N656U                    | 1         | 10%     |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 894       | 24.67%  |
| IMC Networks                           | 426       | 11.75%  |
| Microdia                               | 362       | 9.99%   |
| Realtek Semiconductor                  | 340       | 9.38%   |
| Acer                                   | 311       | 8.58%   |
| Sunplus Innovation Technology          | 227       | 6.26%   |
| Suyin                                  | 157       | 4.33%   |
| Cheng Uei Precision Industry (Foxlink) | 152       | 4.19%   |
| Quanta                                 | 119       | 3.28%   |
| Lite-On Technology                     | 103       | 2.84%   |
| Apple                                  | 79        | 2.18%   |
| Syntek                                 | 66        | 1.82%   |
| Alcor Micro                            | 49        | 1.35%   |
| Ricoh                                  | 43        | 1.19%   |
| Silicon Motion                         | 40        | 1.1%    |
| Logitech                               | 37        | 1.02%   |
| Luxvisions Innotech Limited            | 28        | 0.77%   |
| Samsung Electronics                    | 22        | 0.61%   |
| Lenovo                                 | 20        | 0.55%   |
| Primax Electronics                     | 18        | 0.5%    |
| Importek                               | 13        | 0.36%   |
| DigiTech                               | 13        | 0.36%   |
| Z-Star Microelectronics                | 11        | 0.3%    |
| ALi                                    | 10        | 0.28%   |
| Sonix Technology                       | 7         | 0.19%   |
| GEMBIRD                                | 7         | 0.19%   |
| OmniVision Technologies                | 6         | 0.17%   |
| DJKANA19IDX53W                         | 6         | 0.17%   |
| USB Camera                             | 5         | 0.14%   |
| Y Media                                | 4         | 0.11%   |
| Denron                                 | 4         | 0.11%   |
| Pixart Imaging                         | 3         | 0.08%   |
| Microsoft                              | 3         | 0.08%   |
| Intel                                  | 3         | 0.08%   |
| Xiaomi                                 | 2         | 0.06%   |
| SunplusIT                              | 2         | 0.06%   |
| Sunplus Technology                     | 2         | 0.06%   |
| Novatek Microelectronics               | 2         | 0.06%   |
| Jieli Technology                       | 2         | 0.06%   |
| Guillemot                              | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 195       | 5.36%   |
| Realtek Integrated_Webcam_HD             | 149       | 4.09%   |
| Chicony Integrated Camera                | 136       | 3.74%   |
| IMC Networks USB2.0 HD UVC WebCam        | 97        | 2.67%   |
| Chicony HD WebCam                        | 95        | 2.61%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 77        | 2.12%   |
| IMC Networks Integrated Camera           | 75        | 2.06%   |
| Acer Integrated Camera                   | 66        | 1.81%   |
| Sunplus Integrated_Webcam_HD             | 59        | 1.62%   |
| Realtek USB Camera                       | 50        | 1.37%   |
| Acer HD Webcam                           | 47        | 1.29%   |
| Chicony USB2.0 VGA UVC WebCam            | 44        | 1.21%   |
| Chicony USB2.0 Camera                    | 42        | 1.15%   |
| Chicony USB2.0 HD UVC WebCam             | 38        | 1.04%   |
| Sunplus Asus Webcam                      | 36        | 0.99%   |
| Microdia Integrated Webcam               | 36        | 0.99%   |
| Acer BisonCam,NB Pro                     | 36        | 0.99%   |
| Chicony TOSHIBA Web Camera - HD          | 35        | 0.96%   |
| Chicony HP HD Webcam                     | 34        | 0.93%   |
| Chicony HP HD Camera                     | 34        | 0.93%   |
| Lite-On Integrated Camera                | 31        | 0.85%   |
| Chicony USB 2.0 Camera                   | 31        | 0.85%   |
| Chicony HP Truevision HD                 | 29        | 0.8%    |
| Realtek USB2.0 HD UVC WebCam             | 28        | 0.77%   |
| Apple Built-in iSight                    | 28        | 0.77%   |
| Acer BisonCam, NB Pro                    | 28        | 0.77%   |
| Syntek Integrated Camera                 | 27        | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 26        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE                | 26        | 0.71%   |
| Chicony VGA Webcam                       | 25        | 0.69%   |
| Alcor Micro USB 2.0 Camera               | 25        | 0.69%   |
| Acer Lenovo EasyCamera                   | 25        | 0.69%   |
| IMC Networks UVC VGA Webcam              | 24        | 0.66%   |
| Chicony HP TrueVision HD Camera          | 24        | 0.66%   |
| Sunplus HD WebCam                        | 23        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)  | 22        | 0.6%    |
| IMC Networks ov9734_azurewave_camera     | 21        | 0.58%   |
| Quanta HP HD Camera                      | 20        | 0.55%   |
| Lite-On HP HD Webcam                     | 20        | 0.55%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 20        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 248       | 36.96%  |
| Synaptics                  | 139       | 20.72%  |
| Shenzhen Goodix Technology | 127       | 18.93%  |
| AuthenTec                  | 52        | 7.75%   |
| LighTuning Technology      | 35        | 5.22%   |
| Elan Microelectronics      | 35        | 5.22%   |
| Upek                       | 26        | 3.87%   |
| STMicroelectronics         | 8         | 1.19%   |
| Focal-systems.Corp         | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 71        | 10.58%  |
| Shenzhen Goodix  Fingerprint Device                                        | 65        | 9.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 58        | 8.64%   |
| Shenzhen Goodix FingerPrint                                                | 35        | 5.22%   |
| Unknown                                                                    | 34        | 5.07%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 32        | 4.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 4.02%   |
| Elan ELAN:Fingerprint                                                      | 26        | 3.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 3.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.13%   |
| Validity Sensors VFS491                                                    | 20        | 2.98%   |
| AuthenTec AES2810                                                          | 20        | 2.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 2.53%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 16        | 2.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.38%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.38%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.79%   |
| AuthenTec AES1600                                                          | 12        | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 11        | 1.64%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 1.49%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.49%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 1.49%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.19%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.19%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.89%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.75%   |
| Synaptics WBDI Device                                                      | 5         | 0.75%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.6%    |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.6%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.45%   |
| Synaptics  WBDI                                                            | 3         | 0.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.3%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.3%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.15%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 195       | 57.35%  |
| Alcor Micro               | 72        | 21.18%  |
| O2 Micro                  | 30        | 8.82%   |
| Upek                      | 15        | 4.41%   |
| Lenovo                    | 12        | 3.53%   |
| Hewlett-Packard           | 5         | 1.47%   |
| Gemalto (was Gemplus)     | 4         | 1.18%   |
| Yubico.com                | 2         | 0.59%   |
| Clay Logic                | 2         | 0.59%   |
| SpringCard                | 1         | 0.29%   |
| OmniKey                   | 1         | 0.29%   |
| Aladdin Knowledge Systems | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 72        | 21.18%  |
| Broadcom BCM5880 Secure Applications Processor                               | 68        | 20%     |
| Broadcom 58200                                                               | 55        | 16.18%  |
| Broadcom 5880                                                                | 42        | 12.35%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 29        | 8.53%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 27        | 7.94%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 4.41%   |
| Lenovo Integrated Smart Card Reader                                          | 12        | 3.53%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.88%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.59%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.59%   |
| SpringCard Two                                                               | 1         | 0.29%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.29%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.29%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.29%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.29%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.29%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2606      | 62.33%  |
| 1     | 1256      | 30.04%  |
| 2     | 256       | 6.12%   |
| 3     | 47        | 1.12%   |
| 5     | 5         | 0.12%   |
| 4     | 5         | 0.12%   |
| 6     | 3         | 0.07%   |
| 7     | 2         | 0.05%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 662       | 34.77%  |
| Graphics card            | 370       | 19.43%  |
| Chipcard                 | 318       | 16.7%   |
| Net/wireless             | 166       | 8.72%   |
| Multimedia controller    | 77        | 4.04%   |
| Camera                   | 67        | 3.52%   |
| Bluetooth                | 59        | 3.1%    |
| Storage                  | 48        | 2.52%   |
| Communication controller | 39        | 2.05%   |
| Card reader              | 31        | 1.63%   |
| Sound                    | 21        | 1.1%    |
| Modem                    | 16        | 0.84%   |
| Net/ethernet             | 14        | 0.74%   |
| Network                  | 5         | 0.26%   |
| Flash memory             | 3         | 0.16%   |
| Unclassified device      | 2         | 0.11%   |
| Wireless                 | 1         | 0.05%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

