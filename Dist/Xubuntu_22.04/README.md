Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

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

Total: 390

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | MZBSWMP-00                  | Desktop     | [894f632950](https://linux-hardware.org/?probe=894f632950) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3fac03d01d](https://linux-hardware.org/?probe=3fac03d01d) | Jan 30, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [0f2037dcd8](https://linux-hardware.org/?probe=0f2037dcd8) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [0e28b954b4](https://linux-hardware.org/?probe=0e28b954b4) | Jan 30, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10421fe598](https://linux-hardware.org/?probe=10421fe598) | Jan 30, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | Notebook    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7e91e49912](https://linux-hardware.org/?probe=7e91e49912) | Jan 23, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3324fafe5a](https://linux-hardware.org/?probe=3324fafe5a) | Jan 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b5e6a74fcb](https://linux-hardware.org/?probe=b5e6a74fcb) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Gigabyte      | 8I945GMF                    | Desktop     | [2971006e43](https://linux-hardware.org/?probe=2971006e43) | Jan 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | Notebook    | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d5ad4c9486](https://linux-hardware.org/?probe=d5ad4c9486) | Jan 17, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a49a3ddeaa](https://linux-hardware.org/?probe=a49a3ddeaa) | Jan 17, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d667bf6bb2](https://linux-hardware.org/?probe=d667bf6bb2) | Jan 15, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [0277ea7e50](https://linux-hardware.org/?probe=0277ea7e50) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| HP            | 873A A01                    | Mini pc     | [5c3be4e9aa](https://linux-hardware.org/?probe=5c3be4e9aa) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [07a6ffe405](https://linux-hardware.org/?probe=07a6ffe405) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [ef5e737fd6](https://linux-hardware.org/?probe=ef5e737fd6) | Jan 04, 2023 |
| MiPi PC       | Mini PC                     | Mini pc     | [776c827bdb](https://linux-hardware.org/?probe=776c827bdb) | Jan 03, 2023 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f809473b20](https://linux-hardware.org/?probe=f809473b20) | Jan 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [da1db1e278](https://linux-hardware.org/?probe=da1db1e278) | Jan 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | Notebook    | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-56-generic          | 43        | 12.87%  |
| 5.15.0-52-generic          | 35        | 10.48%  |
| 5.15.0-47-generic          | 31        | 9.28%   |
| 5.15.0-48-generic          | 25        | 7.49%   |
| 5.15.0-25-generic          | 20        | 5.99%   |
| 5.15.0-58-generic          | 18        | 5.39%   |
| 5.15.0-46-generic          | 17        | 5.09%   |
| 5.15.0-27-generic          | 14        | 4.19%   |
| 5.15.0-53-generic          | 13        | 3.89%   |
| 5.15.0-57-generic          | 9         | 2.69%   |
| 5.15.0-50-generic          | 9         | 2.69%   |
| 5.15.0-43-generic          | 9         | 2.69%   |
| 5.15.0-41-generic          | 9         | 2.69%   |
| 5.15.0-40-generic          | 9         | 2.69%   |
| 5.15.0-39-generic          | 6         | 1.8%    |
| 5.15.0-37-generic          | 5         | 1.5%    |
| 5.15.0-35-generic          | 5         | 1.5%    |
| 5.15.0-33-generic          | 4         | 1.2%    |
| 5.15.0-30-generic          | 4         | 1.2%    |
| 5.17.0-1020-oem            | 2         | 0.6%    |
| 5.17.0-1013-oem            | 2         | 0.6%    |
| 5.15.0-54-generic          | 2         | 0.6%    |
| 5.15.0-50-lowlatency       | 2         | 0.6%    |
| 5.15.0-48-lowlatency       | 2         | 0.6%    |
| 5.15.0-46-lowlatency       | 2         | 0.6%    |
| 6.1.6-060106-generic       | 1         | 0.3%    |
| 6.1.0                      | 1         | 0.3%    |
| 6.0.9-060009-generic       | 1         | 0.3%    |
| 6.0.7-x64v3-xanmod1        | 1         | 0.3%    |
| 6.0.0-1007-oem             | 1         | 0.3%    |
| 6.0.0                      | 1         | 0.3%    |
| 5.4.0-126-generic          | 1         | 0.3%    |
| 5.4.0-122-generic          | 1         | 0.3%    |
| 5.19.5-051905-generic      | 1         | 0.3%    |
| 5.19.13-xanmod1            | 1         | 0.3%    |
| 5.19.1                     | 1         | 0.3%    |
| 5.19.0-8.2-liquorix-amd64  | 1         | 0.3%    |
| 5.19.0-15.2-liquorix-amd64 | 1         | 0.3%    |
| 5.19.0-051900-generic      | 1         | 0.3%    |
| 5.18.12-051812-generic     | 1         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 286       | 89.1%   |
| 5.17.0   | 9         | 2.8%    |
| 5.19.0   | 3         | 0.93%   |
| 6.0.0    | 2         | 0.62%   |
| 5.4.0    | 2         | 0.62%   |
| 5.18.0   | 2         | 0.62%   |
| 6.1.6    | 1         | 0.31%   |
| 6.1.0    | 1         | 0.31%   |
| 6.0.9    | 1         | 0.31%   |
| 6.0.7    | 1         | 0.31%   |
| 5.19.5   | 1         | 0.31%   |
| 5.19.13  | 1         | 0.31%   |
| 5.19.1   | 1         | 0.31%   |
| 5.18.12  | 1         | 0.31%   |
| 5.17.3   | 1         | 0.31%   |
| 5.16.9   | 1         | 0.31%   |
| 5.15.74  | 1         | 0.31%   |
| 5.15.68  | 1         | 0.31%   |
| 5.15.61  | 1         | 0.31%   |
| 5.15.59  | 1         | 0.31%   |
| 5.15.48  | 1         | 0.31%   |
| 5.15.23  | 1         | 0.31%   |
| 4.19.241 | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 292       | 90.97%  |
| 5.17    | 10        | 3.12%   |
| 5.19    | 6         | 1.87%   |
| 6.0     | 4         | 1.25%   |
| 5.18    | 3         | 0.93%   |
| 6.1     | 2         | 0.62%   |
| 5.4     | 2         | 0.62%   |
| 5.16    | 1         | 0.31%   |
| 4.19    | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 312       | 98.11%  |
| aarch64 | 4         | 1.26%   |
| armv7l  | 2         | 0.63%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 307       | 96.54%  |
| GNOME           | 9         | 2.83%   |
| i3              | 1         | 0.31%   |
| GNOME Flashback | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 306       | 95.63%  |
| Tty     | 9         | 2.81%   |
| Wayland | 5         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 280       | 88.05%  |
| GDM3    | 19        | 5.97%   |
| Unknown | 16        | 5.03%   |
| SLiM    | 1         | 0.31%   |
| SDDM    | 1         | 0.31%   |
| GDM     | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 126       | 39.62%  |
| de_DE | 41        | 12.89%  |
| fr_FR | 39        | 12.26%  |
| it_IT | 24        | 7.55%   |
| ru_RU | 11        | 3.46%   |
| en_GB | 11        | 3.46%   |
| pt_BR | 9         | 2.83%   |
| en_CA | 6         | 1.89%   |
| es_ES | 5         | 1.57%   |
| cs_CZ | 5         | 1.57%   |
| en_AU | 4         | 1.26%   |
| hu_HU | 3         | 0.94%   |
| en_IN | 3         | 0.94%   |
| C     | 3         | 0.94%   |
| tr_TR | 2         | 0.63%   |
| nl_NL | 2         | 0.63%   |
| ja_JP | 2         | 0.63%   |
| es_VE | 2         | 0.63%   |
| es_CO | 2         | 0.63%   |
| es_AR | 2         | 0.63%   |
| sv_SE | 1         | 0.31%   |
| ru_UA | 1         | 0.31%   |
| ro_RO | 1         | 0.31%   |
| pl_PL | 1         | 0.31%   |
| nl_BE | 1         | 0.31%   |
| ko_KR | 1         | 0.31%   |
| fr_CA | 1         | 0.31%   |
| fr_BE | 1         | 0.31%   |
| fi_FI | 1         | 0.31%   |
| es_MX | 1         | 0.31%   |
| es_CL | 1         | 0.31%   |
| en_ZA | 1         | 0.31%   |
| en_IL | 1         | 0.31%   |
| el_GR | 1         | 0.31%   |
| de_CH | 1         | 0.31%   |
| bg_BG | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 170       | 53.13%  |
| BIOS | 150       | 46.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 289       | 90.88%  |
| Overlay | 14        | 4.4%    |
| Btrfs   | 8         | 2.52%   |
| Zfs     | 6         | 1.89%   |
| Ext3    | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 222       | 68.1%   |
| Unknown | 64        | 19.63%  |
| MBR     | 40        | 12.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 278       | 86.6%   |
| Yes       | 43        | 13.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 214       | 67.08%  |
| Yes       | 105       | 32.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 56        | 17.61%  |
| Lenovo                  | 50        | 15.72%  |
| Hewlett-Packard         | 47        | 14.78%  |
| Dell                    | 33        | 10.38%  |
| Acer                    | 22        | 6.92%   |
| MSI                     | 19        | 5.97%   |
| Gigabyte Technology     | 17        | 5.35%   |
| Google                  | 6         | 1.89%   |
| ASRock                  | 6         | 1.89%   |
| Supermicro              | 4         | 1.26%   |
| Apple                   | 4         | 1.26%   |
| Toshiba                 | 3         | 0.94%   |
| Sony                    | 3         | 0.94%   |
| Intel                   | 3         | 0.94%   |
| HUAWEI                  | 3         | 0.94%   |
| GPU Company             | 3         | 0.94%   |
| Unknown                 | 3         | 0.94%   |
| sunxi                   | 2         | 0.63%   |
| Samsung Electronics     | 2         | 0.63%   |
| Rockchip                | 2         | 0.63%   |
| PCWare                  | 2         | 0.63%   |
| Packard Bell            | 2         | 0.63%   |
| Notebook                | 2         | 0.63%   |
| VIT                     | 1         | 0.31%   |
| Tactus                  | 1         | 0.31%   |
| Standard                | 1         | 0.31%   |
| Schenker                | 1         | 0.31%   |
| Raspberry Pi Foundation | 1         | 0.31%   |
| Pine Microsystems       | 1         | 0.31%   |
| Panasonic               | 1         | 0.31%   |
| MiPi PC                 | 1         | 0.31%   |
| Microsoft               | 1         | 0.31%   |
| Medion                  | 1         | 0.31%   |
| Mediacom                | 1         | 0.31%   |
| MACHINIST               | 1         | 0.31%   |
| LG Electronics          | 1         | 0.31%   |
| Itautec                 | 1         | 0.31%   |
| HIGRADED                | 1         | 0.31%   |
| Hardkernel              | 1         | 0.31%   |
| Fusion5                 | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP EliteBook 840 G3                                                                      | 4         | 1.26%   |
| ASUS All Series                                                                          | 4         | 1.26%   |
| Unknown                                                                                  | 4         | 1.26%   |
| MSI MS-7D43                                                                              | 3         | 0.94%   |
| Dell OptiPlex 7010                                                                       | 3         | 0.94%   |
| Rockchip RK3318 BOX                                                                      | 2         | 0.63%   |
| MSI MS-7D46                                                                              | 2         | 0.63%   |
| MSI MS-7C52                                                                              | 2         | 0.63%   |
| HP Pavilion Notebook                                                                     | 2         | 0.63%   |
| HP 255 G8 Notebook PC                                                                    | 2         | 0.63%   |
| GPU Company GWTN116-3                                                                    | 2         | 0.63%   |
| Dell Latitude 7420                                                                       | 2         | 0.63%   |
| ASUS K30AD_M31AD_M51AD                                                                   | 2         | 0.63%   |
| Acer Switch SW312-31                                                                     | 2         | 0.63%   |
| VIT Aptio CRB                                                                            | 1         | 0.31%   |
| Toshiba Satellite Pro R50-C                                                              | 1         | 0.31%   |
| Toshiba Satellite C650                                                                   | 1         | 0.31%   |
| Toshiba PT10F                                                                            | 1         | 0.31%   |
| Tactus GeoBook 140                                                                       | 1         | 0.31%   |
| Supermicro X10SRA                                                                        | 1         | 0.31%   |
| Supermicro Super Server                                                                  | 1         | 0.31%   |
| Supermicro M12SWA-TF                                                                     | 1         | 0.31%   |
| Supermicro AS -5014A-TT                                                                  | 1         | 0.31%   |
| sunxi LeMaker Banana Pi                                                                  | 1         | 0.31%   |
| sunxi Allwinner sun7i (A20) Family                                                       | 1         | 0.31%   |
| Sony VPCS12V9E                                                                           | 1         | 0.31%   |
| Sony VPCEH25EN                                                                           | 1         | 0.31%   |
| Sony SVE1512C6EB                                                                         | 1         | 0.31%   |
| Schenker WORK (Early 2021)                                                               | 1         | 0.31%   |
| Samsung 370E4K                                                                           | 1         | 0.31%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.31%   |
| RPi Raspberry Pi 4 Model B Rev 1.5                                                       | 1         | 0.31%   |
| Pine Microsystems Pine64 Rock64                                                          | 1         | 0.31%   |
| PCWare IPX1800E2                                                                         | 1         | 0.31%   |
| PCWare IPMH81G1                                                                          | 1         | 0.31%   |
| Panasonic CF-D1DVA06F3                                                                   | 1         | 0.31%   |
| Packard Bell IMEDIA X9305                                                                | 1         | 0.31%   |
| Packard Bell EasyNote MH45                                                               | 1         | 0.31%   |
| Notebook W65_67SZ                                                                        | 1         | 0.31%   |
| Notebook NJx0MU                                                                          | 1         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 24        | 7.55%   |
| Acer Aspire           | 14        | 4.4%    |
| HP Pavilion           | 13        | 4.09%   |
| Dell Latitude         | 10        | 3.14%   |
| ASUS PRIME            | 8         | 2.52%   |
| HP EliteBook          | 7         | 2.2%    |
| Dell OptiPlex         | 7         | 2.2%    |
| Dell Inspiron         | 7         | 2.2%    |
| Lenovo IdeaPad        | 6         | 1.89%   |
| Lenovo ThinkCentre    | 5         | 1.57%   |
| HP Laptop             | 4         | 1.26%   |
| HP Compaq             | 4         | 1.26%   |
| ASUS VivoBook         | 4         | 1.26%   |
| ASUS All              | 4         | 1.26%   |
| Unknown               | 4         | 1.26%   |
| MSI MS-7D43           | 3         | 0.94%   |
| HP EliteDesk          | 3         | 0.94%   |
| HP 255                | 3         | 0.94%   |
| Dell Precision        | 3         | 0.94%   |
| ASUS TUF              | 3         | 0.94%   |
| ASUS ROG              | 3         | 0.94%   |
| Acer Veriton          | 3         | 0.94%   |
| Toshiba Satellite     | 2         | 0.63%   |
| Rockchip RK3318       | 2         | 0.63%   |
| MSI MS-7D46           | 2         | 0.63%   |
| MSI MS-7C52           | 2         | 0.63%   |
| Lenovo ThinkBook      | 2         | 0.63%   |
| HP Stream             | 2         | 0.63%   |
| HP ProBook            | 2         | 0.63%   |
| GPU Company GWTN116-3 | 2         | 0.63%   |
| Gigabyte B550         | 2         | 0.63%   |
| Dell XPS              | 2         | 0.63%   |
| Dell PowerEdge        | 2         | 0.63%   |
| ASUS ZenBook          | 2         | 0.63%   |
| ASUS P8H61-M          | 2         | 0.63%   |
| ASUS K30AD            | 2         | 0.63%   |
| ASUS ASUS             | 2         | 0.63%   |
| Acer Switch           | 2         | 0.63%   |
| VIT Aptio             | 1         | 0.31%   |
| Toshiba PT10F         | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 33        | 10.38%  |
| 2020    | 31        | 9.75%   |
| 2018    | 25        | 7.86%   |
| 2017    | 25        | 7.86%   |
| 2014    | 25        | 7.86%   |
| 2012    | 21        | 6.6%    |
| 2016    | 20        | 6.29%   |
| 2013    | 19        | 5.97%   |
| 2011    | 19        | 5.97%   |
| 2019    | 18        | 5.66%   |
| 2015    | 18        | 5.66%   |
| 2010    | 15        | 4.72%   |
| 2022    | 14        | 4.4%    |
| 2009    | 9         | 2.83%   |
| 2007    | 9         | 2.83%   |
| 2008    | 7         | 2.2%    |
| Unknown | 6         | 1.89%   |
| 2006    | 2         | 0.63%   |
| 2005    | 2         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 177       | 55.66%  |
| Desktop        | 111       | 34.91%  |
| Server         | 7         | 2.2%    |
| System on chip | 6         | 1.89%   |
| Convertible    | 5         | 1.57%   |
| Tablet         | 4         | 1.26%   |
| Mini pc        | 4         | 1.26%   |
| All in one     | 4         | 1.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 292       | 91.82%  |
| Enabled  | 26        | 8.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 312       | 98.11%  |
| Yes  | 6         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 85        | 26.65%  |
| 3.01-4.0        | 81        | 25.39%  |
| 16.01-24.0      | 59        | 18.5%   |
| 8.01-16.0       | 37        | 11.6%   |
| 32.01-64.0      | 22        | 6.9%    |
| 1.01-2.0        | 19        | 5.96%   |
| 24.01-32.0      | 5         | 1.57%   |
| 64.01-256.0     | 5         | 1.57%   |
| 0.51-1.0        | 3         | 0.94%   |
| 2.01-3.0        | 2         | 0.63%   |
| More than 256.0 | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 142       | 42.9%   |
| 2.01-3.0  | 87        | 26.28%  |
| 3.01-4.0  | 32        | 9.67%   |
| 4.01-8.0  | 28        | 8.46%   |
| 0.51-1.0  | 26        | 7.85%   |
| 8.01-16.0 | 13        | 3.93%   |
| 0.01-0.5  | 3         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 196       | 61.25%  |
| 2      | 78        | 24.38%  |
| 3      | 21        | 6.56%   |
| 4      | 15        | 4.69%   |
| 5      | 4         | 1.25%   |
| 6      | 3         | 0.94%   |
| 10     | 1         | 0.31%   |
| 7      | 1         | 0.31%   |
| 0      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 186       | 58.31%  |
| Yes       | 133       | 41.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 83.33%  |
| No        | 53        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 72.64%  |
| No        | 87        | 27.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 55.97%  |
| No        | 140       | 44.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 50        | 15.63%  |
| USA          | 47        | 14.69%  |
| France       | 41        | 12.81%  |
| Italy        | 27        | 8.44%   |
| Russia       | 14        | 4.38%   |
| UK           | 11        | 3.44%   |
| Brazil       | 10        | 3.13%   |
| Sweden       | 8         | 2.5%    |
| Netherlands  | 7         | 2.19%   |
| Czechia      | 7         | 2.19%   |
| Canada       | 7         | 2.19%   |
| Poland       | 5         | 1.56%   |
| Mexico       | 5         | 1.56%   |
| India        | 5         | 1.56%   |
| Belgium      | 5         | 1.56%   |
| Spain        | 4         | 1.25%   |
| Iran         | 4         | 1.25%   |
| Australia    | 4         | 1.25%   |
| Argentina    | 4         | 1.25%   |
| Turkey       | 3         | 0.94%   |
| Portugal     | 3         | 0.94%   |
| Malaysia     | 3         | 0.94%   |
| Indonesia    | 3         | 0.94%   |
| Hungary      | 3         | 0.94%   |
| Greece       | 3         | 0.94%   |
| Colombia     | 3         | 0.94%   |
| Belarus      | 3         | 0.94%   |
| Venezuela    | 2         | 0.63%   |
| Taiwan       | 2         | 0.63%   |
| Switzerland  | 2         | 0.63%   |
| Slovenia     | 2         | 0.63%   |
| Japan        | 2         | 0.63%   |
| Israel       | 2         | 0.63%   |
| Finland      | 2         | 0.63%   |
| Austria      | 2         | 0.63%   |
| Vietnam      | 1         | 0.31%   |
| Ukraine      | 1         | 0.31%   |
| South Korea  | 1         | 0.31%   |
| South Africa | 1         | 0.31%   |
| Sint Maarten | 1         | 0.31%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 9         | 2.75%   |
| Berlin           | 6         | 1.83%   |
| Munich           | 5         | 1.53%   |
| Milan            | 4         | 1.22%   |
| Melbourne        | 4         | 1.22%   |
| Uppsala          | 3         | 0.92%   |
| Stuttgart        | 3         | 0.92%   |
| Moscow           | 3         | 0.92%   |
| Kuala Lumpur     | 3         | 0.92%   |
| Biella           | 3         | 0.92%   |
| Ankara           | 3         | 0.92%   |
| Washington       | 2         | 0.61%   |
| Warsaw           | 2         | 0.61%   |
| Västerås       | 2         | 0.61%   |
| Tehran           | 2         | 0.61%   |
| St Petersburg    | 2         | 0.61%   |
| Oklahoma City    | 2         | 0.61%   |
| Mumbai           | 2         | 0.61%   |
| Leipzig          | 2         | 0.61%   |
| Lavras           | 2         | 0.61%   |
| Kazan’         | 2         | 0.61%   |
| Jakarta          | 2         | 0.61%   |
| Indianapolis     | 2         | 0.61%   |
| Helsinki         | 2         | 0.61%   |
| Hamburg          | 2         | 0.61%   |
| Farmington       | 2         | 0.61%   |
| Clermont-Ferrand | 2         | 0.61%   |
| Budapest         | 2         | 0.61%   |
| Brest            | 2         | 0.61%   |
| Bellevue         | 2         | 0.61%   |
| Belfort          | 2         | 0.61%   |
| Auxerre          | 2         | 0.61%   |
| Athens           | 2         | 0.61%   |
| Żywiec          | 1         | 0.31%   |
| Yokohama         | 1         | 0.31%   |
| Wierden          | 1         | 0.31%   |
| White House      | 1         | 0.31%   |
| Wettringen       | 1         | 0.31%   |
| Waghausel        | 1         | 0.31%   |
| Waarder          | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 71        | 89     | 15.47%  |
| WDC                         | 69        | 92     | 15.03%  |
| Seagate                     | 51        | 64     | 11.11%  |
| Unknown                     | 33        | 37     | 7.19%   |
| Kingston                    | 24        | 29     | 5.23%   |
| Toshiba                     | 23        | 23     | 5.01%   |
| SanDisk                     | 22        | 23     | 4.79%   |
| Hitachi                     | 19        | 27     | 4.14%   |
| SK hynix                    | 17        | 18     | 3.7%    |
| Crucial                     | 15        | 20     | 3.27%   |
| Intel                       | 12        | 12     | 2.61%   |
| HGST                        | 10        | 14     | 2.18%   |
| PNY                         | 9         | 9      | 1.96%   |
| China                       | 7         | 8      | 1.53%   |
| Unknown                     | 5         | 5      | 1.09%   |
| Patriot                     | 4         | 4      | 0.87%   |
| Micron Technology           | 4         | 4      | 0.87%   |
| A-DATA Technology           | 4         | 6      | 0.87%   |
| Transcend                   | 3         | 4      | 0.65%   |
| Silicon Motion              | 3         | 3      | 0.65%   |
| Phison                      | 3         | 10     | 0.65%   |
| USB3.0                      | 2         | 4      | 0.44%   |
| TO Exter                    | 2         | 2      | 0.44%   |
| TEXTORM                     | 2         | 2      | 0.44%   |
| Maxtor                      | 2         | 2      | 0.44%   |
| LITEON                      | 2         | 2      | 0.44%   |
| KIOXIA                      | 2         | 2      | 0.44%   |
| Kingston Technology Company | 2         | 2      | 0.44%   |
| Intenso                     | 2         | 2      | 0.44%   |
| Gigabyte Technology         | 2         | 2      | 0.44%   |
| ASMT                        | 2         | 5      | 0.44%   |
| Apacer                      | 2         | 2      | 0.44%   |
| XPG                         | 1         | 1      | 0.22%   |
| Veno                        | 1         | 1      | 0.22%   |
| Vaseky                      | 1         | 1      | 0.22%   |
| SSSTC                       | 1         | 1      | 0.22%   |
| SSK                         | 1         | 1      | 0.22%   |
| SSD0240S                    | 1         | 1      | 0.22%   |
| SPCC                        | 1         | 1      | 0.22%   |
| Realtek Semiconductor       | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 7         | 1.39%   |
| Samsung SSD 850 EVO 500GB              | 6         | 1.19%   |
| Crucial CT480BX500SSD1 480GB           | 6         | 1.19%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.99%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 0.99%   |
| Unknown                                | 5         | 0.99%   |
| Unknown MMC Card  32GB                 | 4         | 0.79%   |
| Unknown SD/MMC/MS PRO 2GB              | 3         | 0.59%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 0.59%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.59%   |
| Toshiba HDWD110 1TB                    | 3         | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 3         | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.59%   |
| Seagate ST500DM002-1BD142 500GB        | 3         | 0.59%   |
| SanDisk DF4064  64GB                   | 3         | 0.59%   |
| Samsung SSD 840 Series 120GB           | 3         | 0.59%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.59%   |
| PNY CS900 120GB SSD                    | 3         | 0.59%   |
| HGST HTS541010A9E680 1TB               | 3         | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.4%    |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 0.4%    |
| WDC WD10EZEX-00BBHA0 1TB               | 2         | 0.4%    |
| Unknown SA08G  8GB                     | 2         | 0.4%    |
| Unknown NCard  32GB                    | 2         | 0.4%    |
| Unknown MMC64G  64GB                   | 2         | 0.4%    |
| Toshiba DT01ACA200 2TB                 | 2         | 0.4%    |
| Toshiba DT01ACA100 1TB                 | 2         | 0.4%    |
| Toshiba DT01ACA050 500GB               | 2         | 0.4%    |
| TO Exter nal USB 3.0 500GB             | 2         | 0.4%    |
| TEXTORM BM5 240GB SSD                  | 2         | 0.4%    |
| SK hynix NVMe SSD Drive 1024GB         | 2         | 0.4%    |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.4%    |
| Seagate ST4000DM004-2CV104 4TB         | 2         | 0.4%    |
| Seagate ST31000528AS 1TB               | 2         | 0.4%    |
| Seagate ST3000DM008-2DM166 3TB         | 2         | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB         | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 57        | 78     | 32.76%  |
| Seagate             | 51        | 63     | 29.31%  |
| Toshiba             | 19        | 19     | 10.92%  |
| Hitachi             | 19        | 27     | 10.92%  |
| HGST                | 10        | 14     | 5.75%   |
| Samsung Electronics | 8         | 12     | 4.6%    |
| Unknown             | 3         | 3      | 1.72%   |
| USB3.0              | 2         | 4      | 1.15%   |
| ASMT                | 2         | 5      | 1.15%   |
| PHD 3.0             | 1         | 1      | 0.57%   |
| Maxtor              | 1         | 1      | 0.57%   |
| ASMedia             | 1         | 1      | 0.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 48     | 25.81%  |
| Kingston            | 20        | 22     | 12.9%   |
| Crucial             | 14        | 19     | 9.03%   |
| SanDisk             | 12        | 13     | 7.74%   |
| PNY                 | 8         | 8      | 5.16%   |
| WDC                 | 7         | 7      | 4.52%   |
| China               | 7         | 8      | 4.52%   |
| Patriot             | 4         | 4      | 2.58%   |
| Intel               | 4         | 4      | 2.58%   |
| A-DATA Technology   | 4         | 6      | 2.58%   |
| Transcend           | 3         | 3      | 1.94%   |
| Toshiba             | 3         | 3      | 1.94%   |
| TO Exter            | 2         | 2      | 1.29%   |
| TEXTORM             | 2         | 2      | 1.29%   |
| SK hynix            | 2         | 2      | 1.29%   |
| Micron Technology   | 2         | 2      | 1.29%   |
| LITEON              | 2         | 2      | 1.29%   |
| Intenso             | 2         | 2      | 1.29%   |
| Apacer              | 2         | 2      | 1.29%   |
| Veno                | 1         | 1      | 0.65%   |
| Vaseky              | 1         | 1      | 0.65%   |
| SSSTC               | 1         | 1      | 0.65%   |
| SPCC                | 1         | 1      | 0.65%   |
| OCZ                 | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| Linux               | 1         | 1      | 0.65%   |
| KingFast            | 1         | 1      | 0.65%   |
| KingDian            | 1         | 1      | 0.65%   |
| Kimtigo             | 1         | 1      | 0.65%   |
| INNOVATION IT       | 1         | 1      | 0.65%   |
| FORESEE             | 1         | 1      | 0.65%   |
| Unknown             | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 142       | 228    | 34.72%  |
| SSD     | 135       | 174    | 33.01%  |
| NVMe    | 87        | 108    | 21.27%  |
| MMC     | 39        | 45     | 9.54%   |
| Unknown | 6         | 6      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 230       | 381    | 61.66%  |
| NVMe | 87        | 108    | 23.32%  |
| MMC  | 39        | 45     | 10.46%  |
| SAS  | 17        | 27     | 4.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 183       | 262    | 61.2%   |
| 0.51-1.0   | 74        | 85     | 24.75%  |
| 1.01-2.0   | 18        | 21     | 6.02%   |
| 3.01-4.0   | 14        | 22     | 4.68%   |
| 2.01-3.0   | 5         | 6      | 1.67%   |
| 4.01-10.0  | 3         | 4      | 1%      |
| 10.01-20.0 | 2         | 2      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 27.95%  |
| 251-500        | 74        | 22.98%  |
| 501-1000       | 44        | 13.66%  |
| 51-100         | 27        | 8.39%   |
| 1001-2000      | 24        | 7.45%   |
| 1-20           | 21        | 6.52%   |
| 21-50          | 18        | 5.59%   |
| More than 3000 | 15        | 4.66%   |
| 2001-3000      | 8         | 2.48%   |
| Unknown        | 1         | 0.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 112       | 34.57%  |
| 21-50          | 67        | 20.68%  |
| 101-250        | 43        | 13.27%  |
| 51-100         | 37        | 11.42%  |
| 251-500        | 34        | 10.49%  |
| 501-1000       | 12        | 3.7%    |
| 1001-2000      | 8         | 2.47%   |
| More than 3000 | 5         | 1.54%   |
| 2001-3000      | 5         | 1.54%   |
| Unknown        | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB                           | 2         | 2      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 4.17%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 2.08%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                 | 1         | 1      | 2.08%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 2.08%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 2.08%   |
| WDC WD20EFRX-68AX9N0 2TB                         | 1         | 1      | 2.08%   |
| WDC WD2002FYPS-02W3B0 2TB                        | 1         | 1      | 2.08%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 2.08%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 2.08%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1         | 1      | 2.08%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1         | 1      | 2.08%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1         | 1      | 2.08%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 2.08%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 2.08%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 2.08%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.08%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 2.08%   |
| Seagate ST3750840AS 752GB                        | 1         | 1      | 2.08%   |
| Seagate ST3250318AS 249GB                        | 1         | 2      | 2.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.08%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 2.08%   |
| Samsung Electronics SP2514N 250GB                | 1         | 1      | 2.08%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.08%   |
| Samsung Electronics HM321HI 320GB                | 1         | 2      | 2.08%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 2.08%   |
| Samsung Electronics HD250HJ 250GB                | 1         | 1      | 2.08%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 2.08%   |
| PNY 69D03094-T 40GB SSD                          | 1         | 1      | 2.08%   |
| Maxtor STM3160215AS 160GB                        | 1         | 1      | 2.08%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 2.08%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 2.08%   |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 2.08%   |
| Intel SSDSC2BW080A4 80GB                         | 1         | 1      | 2.08%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 1      | 2.08%   |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 2.08%   |
| Hitachi HTS541080G9SA00 80GB                     | 1         | 1      | 2.08%   |
| Hitachi HDS722540VLAT20 40GB                     | 1         | 1      | 2.08%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 2.08%   |
| Hitachi HCP725032GLA380 320GB                    | 1         | 2      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 23.4%   |
| Seagate             | 9         | 10     | 19.15%  |
| Hitachi             | 6         | 7      | 12.77%  |
| Samsung Electronics | 5         | 7      | 10.64%  |
| HGST                | 3         | 5      | 6.38%   |
| Toshiba             | 2         | 2      | 4.26%   |
| Intel               | 2         | 2      | 4.26%   |
| SSSTC               | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 1      | 2.13%   |
| PNY                 | 1         | 1      | 2.13%   |
| Maxtor              | 1         | 1      | 2.13%   |
| LITEON              | 1         | 1      | 2.13%   |
| Kingston            | 1         | 2      | 2.13%   |
| Crucial             | 1         | 1      | 2.13%   |
| ASMT                | 1         | 4      | 2.13%   |
| Unknown             | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 25.71%  |
| Seagate             | 9         | 10     | 25.71%  |
| Hitachi             | 6         | 7      | 17.14%  |
| Samsung Electronics | 4         | 6      | 11.43%  |
| HGST                | 3         | 5      | 8.57%   |
| Toshiba             | 2         | 2      | 5.71%   |
| Maxtor              | 1         | 1      | 2.86%   |
| ASMT                | 1         | 4      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 44     | 74.42%  |
| SSD  | 11        | 13     | 25.58%  |

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
| Works    | 174       | 275    | 49.86%  |
| Detected | 133       | 229    | 38.11%  |
| Malfunc  | 42        | 57     | 12.03%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 206       | 55.23%  |
| AMD                          | 67        | 17.96%  |
| Samsung Electronics          | 26        | 6.97%   |
| SK hynix                     | 15        | 4.02%   |
| SanDisk                      | 10        | 2.68%   |
| Kingston Technology Company  | 8         | 2.14%   |
| Silicon Motion               | 6         | 1.61%   |
| Phison Electronics           | 6         | 1.61%   |
| ASMedia Technology           | 6         | 1.61%   |
| VIA Technologies             | 3         | 0.8%    |
| Nvidia                       | 3         | 0.8%    |
| JMicron Technology           | 3         | 0.8%    |
| Realtek Semiconductor        | 2         | 0.54%   |
| KIOXIA                       | 2         | 0.54%   |
| Toshiba America Info Systems | 1         | 0.27%   |
| Shenzhen Longsys Electronics | 1         | 0.27%   |
| Micron/Crucial Technology    | 1         | 0.27%   |
| Micron Technology            | 1         | 0.27%   |
| Marvell Technology Group     | 1         | 0.27%   |
| Lenovo                       | 1         | 0.27%   |
| INNOGRIT                     | 1         | 0.27%   |
| Biwin Storage Technology     | 1         | 0.27%   |
| Apple                        | 1         | 0.27%   |
| Adaptec                      | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 50        | 11.44%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 15        | 3.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 14        | 3.2%    |
| Samsung NVMe SSD Controller 980                                                         | 13        | 2.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 2.52%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 10        | 2.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 8         | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 7         | 1.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 6         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 6         | 1.37%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 1.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 1.37%   |
| AMD FCH SATA Controller D                                                               | 6         | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 5         | 1.14%   |
| Kingston Company A2000 NVMe SSD                                                         | 5         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 5         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 0.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 239       | 62.08%  |
| NVMe | 87        | 22.6%   |
| IDE  | 38        | 9.87%   |
| RAID | 20        | 5.19%   |
| SAS  | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 233       | 73.27%  |
| AMD    | 79        | 24.84%  |
| ARM    | 6         | 1.89%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 1.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.25%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 1.25%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 4         | 1.25%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 4         | 1.25%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 1.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.25%   |
| ARM Processor                               | 4         | 1.25%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4         | 1.25%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 0.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 3         | 0.94%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 0.94%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 0.94%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3         | 0.94%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.94%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 3         | 0.94%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 3         | 0.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3         | 0.94%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 0.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 3         | 0.94%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 3         | 0.94%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 2         | 0.63%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 0.63%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.63%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 2         | 0.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 0.63%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 66        | 20.69%  |
| Intel Celeron           | 40        | 12.54%  |
| Other                   | 30        | 9.4%    |
| Intel Core i7           | 28        | 8.78%   |
| Intel Core i3           | 24        | 7.52%   |
| AMD Ryzen 5             | 23        | 7.21%   |
| AMD Ryzen 7             | 12        | 3.76%   |
| Intel Core 2 Duo        | 11        | 3.45%   |
| Intel Atom              | 9         | 2.82%   |
| Intel Xeon              | 8         | 2.51%   |
| Intel Pentium           | 8         | 2.51%   |
| AMD A6                  | 5         | 1.57%   |
| AMD Ryzen 9             | 4         | 1.25%   |
| AMD FX                  | 4         | 1.25%   |
| AMD Ryzen 5 PRO         | 3         | 0.94%   |
| AMD Ryzen 3             | 3         | 0.94%   |
| AMD A8                  | 3         | 0.94%   |
| AMD A10                 | 3         | 0.94%   |
| Intel Pentium Dual      | 2         | 0.63%   |
| Intel Pentium 4         | 2         | 0.63%   |
| Intel Core 2 Quad       | 2         | 0.63%   |
| Intel Core 2            | 2         | 0.63%   |
| ARM Allwinner           | 2         | 0.63%   |
| AMD Ryzen Threadripper  | 2         | 0.63%   |
| AMD Phenom II X4        | 2         | 0.63%   |
| AMD E2                  | 2         | 0.63%   |
| AMD Athlon II X2        | 2         | 0.63%   |
| AMD Athlon              | 2         | 0.63%   |
| AMD A4                  | 2         | 0.63%   |
| Intel Xeon Gold         | 1         | 0.31%   |
| Intel Pentium Silver    | 1         | 0.31%   |
| Intel Pentium Dual-Core | 1         | 0.31%   |
| Intel Genuine           | 1         | 0.31%   |
| Intel Core m3           | 1         | 0.31%   |
| Intel Core 2 Extreme    | 1         | 0.31%   |
| AMD Sempron             | 1         | 0.31%   |
| AMD Ryzen Embedded      | 1         | 0.31%   |
| AMD Ryzen 7 PRO         | 1         | 0.31%   |
| AMD Phenom II X6        | 1         | 0.31%   |
| AMD E1                  | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 139       | 43.44%  |
| 4       | 109       | 34.06%  |
| 6       | 31        | 9.69%   |
| 8       | 20        | 6.25%   |
| 12      | 5         | 1.56%   |
| 1       | 5         | 1.56%   |
| Unknown | 3         | 0.94%   |
| 64      | 2         | 0.63%   |
| 10      | 2         | 0.63%   |
| 3       | 2         | 0.63%   |
| 16      | 1         | 0.31%   |
| 14      | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 314       | 98.74%  |
| Unknown | 3         | 0.94%   |
| 2       | 1         | 0.31%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 189       | 59.43%  |
| 1       | 126       | 39.62%  |
| Unknown | 3         | 0.94%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 315       | 99.06%  |
| Unknown        | 3         | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 32.5%   |
| 0x806c1    | 14        | 4.38%   |
| 0x306a9    | 12        | 3.75%   |
| 0x206a7    | 10        | 3.13%   |
| 0x406e3    | 7         | 2.19%   |
| 0x306d4    | 7         | 2.19%   |
| 0x306c3    | 7         | 2.19%   |
| 0x506c9    | 6         | 1.88%   |
| 0x406c4    | 6         | 1.88%   |
| 0x806ec    | 5         | 1.56%   |
| 0x406c3    | 5         | 1.56%   |
| 0x30678    | 5         | 1.56%   |
| 0x106e5    | 5         | 1.56%   |
| 0x08608103 | 5         | 1.56%   |
| 0x0800820d | 5         | 1.56%   |
| 0xa0652    | 4         | 1.25%   |
| 0x906ea    | 4         | 1.25%   |
| 0x6fb      | 4         | 1.25%   |
| 0x506e3    | 4         | 1.25%   |
| 0x40651    | 4         | 1.25%   |
| 0x1067a    | 4         | 1.25%   |
| 0x08701021 | 4         | 1.25%   |
| 0x08108109 | 4         | 1.25%   |
| 0x806ea    | 3         | 0.94%   |
| 0x706a8    | 3         | 0.94%   |
| 0x706a1    | 3         | 0.94%   |
| 0x6fd      | 3         | 0.94%   |
| 0x20652    | 3         | 0.94%   |
| 0x10676    | 3         | 0.94%   |
| 0x0a50000c | 3         | 0.94%   |
| 0x010000c8 | 3         | 0.94%   |
| 0x90672    | 2         | 0.63%   |
| 0x806e9    | 2         | 0.63%   |
| 0x806d1    | 2         | 0.63%   |
| 0x6f6      | 2         | 0.63%   |
| 0x506ca    | 2         | 0.63%   |
| 0x306f2    | 2         | 0.63%   |
| 0x206d7    | 2         | 0.63%   |
| 0x20655    | 2         | 0.63%   |
| 0x0a201016 | 2         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 9.4%    |
| SandyBridge      | 25        | 7.84%   |
| Silvermont       | 24        | 7.52%   |
| IvyBridge        | 21        | 6.58%   |
| Haswell          | 19        | 5.96%   |
| Unknown          | 19        | 5.96%   |
| Skylake          | 18        | 5.64%   |
| Zen 2            | 16        | 5.02%   |
| TigerLake        | 16        | 5.02%   |
| Zen+             | 12        | 3.76%   |
| Penryn           | 10        | 3.13%   |
| Core             | 10        | 3.13%   |
| Zen 3            | 9         | 2.82%   |
| Goldmont         | 9         | 2.82%   |
| Broadwell        | 9         | 2.82%   |
| Westmere         | 8         | 2.51%   |
| Goldmont plus    | 7         | 2.19%   |
| Piledriver       | 6         | 1.88%   |
| Nehalem          | 6         | 1.88%   |
| K10              | 6         | 1.88%   |
| Zen              | 5         | 1.57%   |
| Puma             | 5         | 1.57%   |
| Excavator        | 5         | 1.57%   |
| CometLake        | 5         | 1.57%   |
| Icelake          | 3         | 0.94%   |
| Bonnell          | 3         | 0.94%   |
| Alderlake Hybrid | 3         | 0.94%   |
| NetBurst         | 2         | 0.63%   |
| K10 Llano        | 2         | 0.63%   |
| Bobcat           | 2         | 0.63%   |
| Tremont          | 1         | 0.31%   |
| Steamroller      | 1         | 0.31%   |
| K8 Hammer        | 1         | 0.31%   |
| Jaguar           | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 191       | 53.8%   |
| Nvidia                     | 82        | 23.1%   |
| AMD                        | 76        | 21.41%  |
| ASPEED Technology          | 4         | 1.13%   |
| Matrox Electronics Systems | 2         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 4.4%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.2%    |
| Intel HD Graphics 500                                                                    | 7         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 1.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.65%   |
| Intel HD Graphics 620                                                                    | 6         | 1.65%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.65%   |
| AMD Lucienne                                                                             | 6         | 1.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.37%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.1%    |
| Intel UHD Graphics 620                                                                   | 4         | 1.1%    |
| Intel HD Graphics 530                                                                    | 4         | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.1%    |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.1%    |
| AMD Renoir                                                                               | 4         | 1.1%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.82%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.55%   |
| Nvidia TU117M                                                                            | 2         | 0.55%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2         | 0.55%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.55%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.55%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 156       | 49.06%  |
| 1 x AMD         | 60        | 18.87%  |
| 1 x Nvidia      | 50        | 15.72%  |
| Intel + Nvidia  | 24        | 7.55%   |
| Other           | 7         | 2.2%    |
| 2 x AMD         | 5         | 1.57%   |
| Intel + AMD     | 5         | 1.57%   |
| AMD + Nvidia    | 5         | 1.57%   |
| Nvidia + ASPEED | 3         | 0.94%   |
| 1 x Matrox      | 1         | 0.31%   |
| 1 x ASPEED      | 1         | 0.31%   |
| AMD + Matrox    | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 255       | 80.19%  |
| Proprietary | 50        | 15.72%  |
| Unknown     | 13        | 4.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 67.81%  |
| 0.01-0.5   | 34        | 10.63%  |
| 1.01-2.0   | 26        | 8.13%   |
| 0.51-1.0   | 19        | 5.94%   |
| 3.01-4.0   | 13        | 4.06%   |
| 7.01-8.0   | 4         | 1.25%   |
| 8.01-16.0  | 4         | 1.25%   |
| 32.01-64.0 | 1         | 0.31%   |
| 5.01-6.0   | 1         | 0.31%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 13.9%   |
| Samsung Electronics     | 38        | 11.48%  |
| LG Display              | 32        | 9.67%   |
| Dell                    | 26        | 7.85%   |
| BOE                     | 26        | 7.85%   |
| Chimei Innolux          | 24        | 7.25%   |
| Hewlett-Packard         | 14        | 4.23%   |
| Goldstar                | 12        | 3.63%   |
| Acer                    | 11        | 3.32%   |
| ViewSonic               | 8         | 2.42%   |
| AOC                     | 8         | 2.42%   |
| Lenovo                  | 7         | 2.11%   |
| Chi Mei Optoelectronics | 7         | 2.11%   |
| Philips                 | 6         | 1.81%   |
| Iiyama                  | 6         | 1.81%   |
| PANDA                   | 5         | 1.51%   |
| BenQ                    | 5         | 1.51%   |
| InfoVision              | 4         | 1.21%   |
| Apple                   | 4         | 1.21%   |
| LG Philips              | 3         | 0.91%   |
| Toshiba                 | 2         | 0.6%    |
| KDC                     | 2         | 0.6%    |
| Fujitsu Siemens         | 2         | 0.6%    |
| Envision Peripherals    | 2         | 0.6%    |
| Ancor Communications    | 2         | 0.6%    |
| ___                     | 1         | 0.3%    |
| Vizio                   | 1         | 0.3%    |
| Vita                    | 1         | 0.3%    |
| Vestel Elektronik       | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |
| TEO                     | 1         | 0.3%    |
| TCL                     | 1         | 0.3%    |
| Sony                    | 1         | 0.3%    |
| Sharp                   | 1         | 0.3%    |
| Sceptre Tech            | 1         | 0.3%    |
| SAC                     | 1         | 0.3%    |
| RTK                     | 1         | 0.3%    |
| Panasonic               | 1         | 0.3%    |
| Packard Bell            | 1         | 0.3%    |
| Nixeus                  | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.88%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch    | 2         | 0.59%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                       | 2         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.59%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.59%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.59%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.59%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.59%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.59%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.59%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.59%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                       | 1         | 0.29%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.29%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                       | 1         | 0.29%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.29%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch            | 1         | 0.29%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch               | 1         | 0.29%   |
| ViewSonic VP2365 SERIES VSC7C28 1920x1080 509x286mm 23.0-inch            | 1         | 0.29%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.29%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch             | 1         | 0.29%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 1         | 0.29%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.29%   |
| Toshiba TV TSB0109 1920x1080                                             | 1         | 0.29%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.29%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                          | 1         | 0.29%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                         | 1         | 0.29%   |
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch     | 1         | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.29%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0657 1920x1080                         | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                         | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 143       | 44.97%  |
| 1366x768 (WXGA)    | 64        | 20.13%  |
| 1600x900 (HD+)     | 24        | 7.55%   |
| 3840x2160 (4K)     | 11        | 3.46%   |
| 1440x900 (WXGA+)   | 11        | 3.46%   |
| 1280x1024 (SXGA)   | 10        | 3.14%   |
| 2560x1440 (QHD)    | 8         | 2.52%   |
| 1920x1200 (WUXGA)  | 8         | 2.52%   |
| 1280x800 (WXGA)    | 8         | 2.52%   |
| 1680x1050 (WSXGA+) | 7         | 2.2%    |
| 1360x768           | 3         | 0.94%   |
| 3840x1600          | 2         | 0.63%   |
| 3440x1440          | 2         | 0.63%   |
| 2560x1600          | 2         | 0.63%   |
| 2160x1440          | 2         | 0.63%   |
| 1600x1200          | 2         | 0.63%   |
| 1024x768 (XGA)     | 2         | 0.63%   |
| 1024x600           | 2         | 0.63%   |
| 3840x1080          | 1         | 0.31%   |
| 2880x1800          | 1         | 0.31%   |
| 2560x1080          | 1         | 0.31%   |
| 1920x540           | 1         | 0.31%   |
| 1920x515           | 1         | 0.31%   |
| 1366x912           | 1         | 0.31%   |
| Unknown            | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 77        | 23.05%  |
| 14      | 34        | 10.18%  |
| 13      | 32        | 9.58%   |
| 24      | 25        | 7.49%   |
| 17      | 25        | 7.49%   |
| 23      | 23        | 6.89%   |
| 27      | 18        | 5.39%   |
| 21      | 16        | 4.79%   |
| Unknown | 12        | 3.59%   |
| 19      | 11        | 3.29%   |
| 18      | 11        | 3.29%   |
| 20      | 8         | 2.4%    |
| 11      | 6         | 1.8%    |
| 31      | 5         | 1.5%    |
| 26      | 5         | 1.5%    |
| 22      | 4         | 1.2%    |
| 12      | 4         | 1.2%    |
| 40      | 2         | 0.6%    |
| 37      | 2         | 0.6%    |
| 34      | 2         | 0.6%    |
| 25      | 2         | 0.6%    |
| 10      | 2         | 0.6%    |
| 84      | 1         | 0.3%    |
| 72      | 1         | 0.3%    |
| 54      | 1         | 0.3%    |
| 32      | 1         | 0.3%    |
| 30      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 6       | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 139       | 42.51%  |
| 501-600     | 67        | 20.49%  |
| 401-500     | 47        | 14.37%  |
| 201-300     | 23        | 7.03%   |
| 351-400     | 21        | 6.42%   |
| Unknown     | 12        | 3.67%   |
| 601-700     | 7         | 2.14%   |
| 801-900     | 4         | 1.22%   |
| 701-800     | 3         | 0.92%   |
| 1501-2000   | 2         | 0.61%   |
| 101-200     | 1         | 0.31%   |
| 1001-1500   | 1         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 238       | 77.52%  |
| 16/10   | 41        | 13.36%  |
| 5/4     | 9         | 2.93%   |
| Unknown | 7         | 2.28%   |
| 4/3     | 5         | 1.63%   |
| 21/9    | 4         | 1.3%    |
| 3/2     | 2         | 0.65%   |
| 3.73    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 23.33%  |
| 81-90          | 57        | 17.27%  |
| 201-250        | 54        | 16.36%  |
| 151-200        | 27        | 8.18%   |
| 301-350        | 21        | 6.36%   |
| 141-150        | 16        | 4.85%   |
| 121-130        | 13        | 3.94%   |
| Unknown        | 12        | 3.64%   |
| 71-80          | 10        | 3.03%   |
| 351-500        | 10        | 3.03%   |
| 251-300        | 9         | 2.73%   |
| 51-60          | 6         | 1.82%   |
| 131-140        | 5         | 1.52%   |
| More than 1000 | 3         | 0.91%   |
| 61-70          | 3         | 0.91%   |
| 501-1000       | 3         | 0.91%   |
| 41-50          | 2         | 0.61%   |
| 1-40           | 1         | 0.3%    |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 118       | 36.65%  |
| 121-160       | 94        | 29.19%  |
| 101-120       | 86        | 26.71%  |
| Unknown       | 12        | 3.73%   |
| 161-240       | 6         | 1.86%   |
| More than 240 | 4         | 1.24%   |
| 1-50          | 2         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 269       | 84.59%  |
| 2     | 35        | 11.01%  |
| 0     | 9         | 2.83%   |
| 3     | 5         | 1.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 173       | 37.61%  |
| Intel                             | 153       | 33.26%  |
| Qualcomm Atheros                  | 48        | 10.43%  |
| Broadcom                          | 24        | 5.22%   |
| Ralink Technology                 | 5         | 1.09%   |
| MediaTek                          | 5         | 1.09%   |
| Marvell Technology Group          | 4         | 0.87%   |
| Dell                              | 4         | 0.87%   |
| TP-Link                           | 3         | 0.65%   |
| Nvidia                            | 3         | 0.65%   |
| Huawei Technologies               | 3         | 0.65%   |
| Sierra Wireless                   | 2         | 0.43%   |
| Samsung Electronics               | 2         | 0.43%   |
| Ralink                            | 2         | 0.43%   |
| Qualcomm Atheros Communications   | 2         | 0.43%   |
| Microchip Technology              | 2         | 0.43%   |
| Insyde Software                   | 2         | 0.43%   |
| Hewlett-Packard                   | 2         | 0.43%   |
| D-Link System                     | 2         | 0.43%   |
| Broadcom Limited                  | 2         | 0.43%   |
| ASIX Electronics                  | 2         | 0.43%   |
| Aquantia                          | 2         | 0.43%   |
| ZyDAS                             | 1         | 0.22%   |
| Xiaomi                            | 1         | 0.22%   |
| TRENDnet                          | 1         | 0.22%   |
| Qualcomm                          | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| NetGear                           | 1         | 0.22%   |
| Microsoft                         | 1         | 0.22%   |
| LG Electronics                    | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| D-Link                            | 1         | 0.22%   |
| BUFFALO                           | 1         | 0.22%   |
| Attansic Technology               | 1         | 0.22%   |
| Apple                             | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 117       | 21.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.57%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.39%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.65%   |
| Intel Wireless 8260                                               | 8         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.29%   |
| Intel Wireless 7265                                               | 7         | 1.29%   |
| Intel Wireless 3165                                               | 7         | 1.29%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.1%    |
| Intel Wireless 7260                                               | 6         | 1.1%    |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 0.92%   |
| Intel Wireless 8265 / 8275                                        | 5         | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.74%   |
| Realtek 802.11ac NIC                                              | 4         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.74%   |
| Intel Wireless 3160                                               | 4         | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.55%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.55%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 43.78%  |
| Realtek Semiconductor           | 52        | 20.88%  |
| Qualcomm Atheros                | 45        | 18.07%  |
| Broadcom                        | 13        | 5.22%   |
| Ralink Technology               | 5         | 2.01%   |
| MediaTek                        | 5         | 2.01%   |
| Dell                            | 3         | 1.2%    |
| TP-Link                         | 2         | 0.8%    |
| Sierra Wireless                 | 2         | 0.8%    |
| Ralink                          | 2         | 0.8%    |
| Qualcomm Atheros Communications | 2         | 0.8%    |
| ZyDAS                           | 1         | 0.4%    |
| TRENDnet                        | 1         | 0.4%    |
| Qualcomm                        | 1         | 0.4%    |
| NetGear                         | 1         | 0.4%    |
| Microsoft                       | 1         | 0.4%    |
| Marvell Technology Group        | 1         | 0.4%    |
| D-Link System                   | 1         | 0.4%    |
| D-Link                          | 1         | 0.4%    |
| BUFFALO                         | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 13        | 5.16%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.57%   |
| Intel Wireless 8260                                            | 8         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.78%   |
| Intel Wireless 7265                                            | 7         | 2.78%   |
| Intel Wireless 3165                                            | 7         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.38%   |
| Intel Wireless 7260                                            | 6         | 2.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.98%   |
| Intel Wireless 8265 / 8275                                     | 5         | 1.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 1.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.59%   |
| Realtek 802.11ac NIC                                           | 4         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.59%   |
| Intel Wireless 3160                                            | 4         | 1.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.59%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.19%   |
| Sierra Wireless EM7455                                         | 2         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 154       | 54.04%  |
| Intel                    | 82        | 28.77%  |
| Broadcom                 | 12        | 4.21%   |
| Qualcomm Atheros         | 8         | 2.81%   |
| Nvidia                   | 3         | 1.05%   |
| Marvell Technology Group | 3         | 1.05%   |
| Huawei Technologies      | 3         | 1.05%   |
| Samsung Electronics      | 2         | 0.7%    |
| Insyde Software          | 2         | 0.7%    |
| Hewlett-Packard          | 2         | 0.7%    |
| Broadcom Limited         | 2         | 0.7%    |
| ASIX Electronics         | 2         | 0.7%    |
| Aquantia                 | 2         | 0.7%    |
| Xiaomi                   | 1         | 0.35%   |
| TP-Link                  | 1         | 0.35%   |
| OPPO Electronics         | 1         | 0.35%   |
| Microchip Technology     | 1         | 0.35%   |
| LG Electronics           | 1         | 0.35%   |
| D-Link System            | 1         | 0.35%   |
| Attansic Technology      | 1         | 0.35%   |
| Apple                    | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 117       | 40.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 7.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 4.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 3.46%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.42%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.38%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.38%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.04%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.04%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.04%   |
| Huawei ELS-NX9                                                    | 3         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.69%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.69%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.69%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.69%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.69%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.69%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2         | 0.69%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.69%   |
| Aquantia Ethernet controller                                      | 2         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.35%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.35%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 264       | 53.01%  |
| WiFi     | 231       | 46.39%  |
| Modem    | 3         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 188       | 58.57%  |
| Ethernet | 133       | 41.43%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 168       | 52.83%  |
| 1     | 130       | 40.88%  |
| 0     | 14        | 4.4%    |
| 3     | 4         | 1.26%   |
| 4     | 2         | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 212       | 65.84%  |
| Yes  | 110       | 34.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 46.96%  |
| Realtek Semiconductor           | 21        | 11.6%   |
| Cambridge Silicon Radio         | 12        | 6.63%   |
| Broadcom                        | 12        | 6.63%   |
| Qualcomm Atheros Communications | 9         | 4.97%   |
| Lite-On Technology              | 9         | 4.97%   |
| IMC Networks                    | 7         | 3.87%   |
| Foxconn / Hon Hai               | 7         | 3.87%   |
| Realtek                         | 3         | 1.66%   |
| Apple                           | 3         | 1.66%   |
| Hewlett-Packard                 | 2         | 1.1%    |
| Dell                            | 2         | 1.1%    |
| Toshiba                         | 1         | 0.55%   |
| Ralink                          | 1         | 0.55%   |
| MediaTek                        | 1         | 0.55%   |
| Marvell Semiconductor           | 1         | 0.55%   |
| Fujitsu                         | 1         | 0.55%   |
| Foxconn International           | 1         | 0.55%   |
| Chicony Electronics             | 1         | 0.55%   |
| ASUSTek Computer                | 1         | 0.55%   |
| Alps Electric                   | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 37        | 20.44%  |
| Intel Bluetooth Device                              | 18        | 9.94%   |
| Realtek Bluetooth Radio                             | 14        | 7.73%   |
| Intel AX200 Bluetooth                               | 12        | 6.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 6.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 3.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 3.31%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 2.76%   |
| Intel AX210 Bluetooth                               | 5         | 2.76%   |
| Lite-On Bluetooth Device                            | 4         | 2.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.21%   |
| Realtek Bluetooth Radio                             | 3         | 1.66%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.1%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.1%    |
| IMC Networks Wireless_Device                        | 2         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.1%    |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.1%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.1%    |
| Toshiba Bluetooth Device                            | 1         | 0.55%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.55%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.55%   |
| MediaTek Wireless_Device                            | 1         | 0.55%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.55%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.55%   |
| Lite-On Bluetooth Radio                             | 1         | 0.55%   |
| Lite-On BCM43142A0                                  | 1         | 0.55%   |
| IMC Networks Bluetooth Device                       | 1         | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.55%   |
| Fujitsu Bluetooth Device                            | 1         | 0.55%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 223       | 56.17%  |
| AMD                         | 84        | 21.16%  |
| Nvidia                      | 59        | 14.86%  |
| C-Media Electronics         | 5         | 1.26%   |
| Texas Instruments           | 3         | 0.76%   |
| SAVITECH                    | 2         | 0.5%    |
| JMTek                       | 2         | 0.5%    |
| Generalplus Technology      | 2         | 0.5%    |
| ASUSTek Computer            | 2         | 0.5%    |
| VIA Technologies            | 1         | 0.25%   |
| Trust International         | 1         | 0.25%   |
| Tenx Technology             | 1         | 0.25%   |
| Samson Technologies         | 1         | 0.25%   |
| Plantronics                 | 1         | 0.25%   |
| Medeli Electronics          | 1         | 0.25%   |
| MAG Technology              | 1         | 0.25%   |
| Logitech                    | 1         | 0.25%   |
| Lenovo                      | 1         | 0.25%   |
| Kingston Technology         | 1         | 0.25%   |
| Hewlett-Packard             | 1         | 0.25%   |
| GN Netcom                   | 1         | 0.25%   |
| FiiO Electronics Technology | 1         | 0.25%   |
| Creative Labs               | 1         | 0.25%   |
| Corsair                     | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 4.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 4.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 4.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 3.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 3.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 2.97%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 2.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.7%    |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 8         | 1.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 6         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.85%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.64%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 60        | 22.64%  |
| Unknown                    | 44        | 16.6%   |
| SK hynix                   | 36        | 13.58%  |
| Kingston                   | 32        | 12.08%  |
| Micron Technology          | 23        | 8.68%   |
| Crucial                    | 20        | 7.55%   |
| Ramaxel Technology         | 8         | 3.02%   |
| G.Skill                    | 8         | 3.02%   |
| Unknown (ABCD)             | 7         | 2.64%   |
| Corsair                    | 5         | 1.89%   |
| Nanya Technology           | 3         | 1.13%   |
| Elpida                     | 3         | 1.13%   |
| Transcend                  | 2         | 0.75%   |
| Smart                      | 2         | 0.75%   |
| Unknown                    | 2         | 0.75%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.38%   |
| Timetec                    | 1         | 0.38%   |
| Qumo                       | 1         | 0.38%   |
| Qimonda                    | 1         | 0.38%   |
| GLOWAY                     | 1         | 0.38%   |
| Foxline                    | 1         | 0.38%   |
| fef5                       | 1         | 0.38%   |
| Essencore                  | 1         | 0.38%   |
| ASint Technology           | 1         | 0.38%   |
| A-DATA Technology          | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 1.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.45%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 3         | 1.09%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 1.09%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.09%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.09%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.72%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.72%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.72%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                    | 2         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.72%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.72%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.72%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.72%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.72%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.72%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.72%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.72%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.72%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8192MB SODIMM DDR4 3200MT/s          | 2         | 0.72%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s             | 2         | 0.72%   |
| Unknown                                                          | 2         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.36%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.36%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 98        | 42.79%  |
| DDR3    | 83        | 36.24%  |
| LPDDR4  | 18        | 7.86%   |
| DDR2    | 11        | 4.8%    |
| LPDDR3  | 6         | 2.62%   |
| Unknown | 6         | 2.62%   |
| SDRAM   | 4         | 1.75%   |
| DDR5    | 2         | 0.87%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 128       | 55.41%  |
| DIMM         | 81        | 35.06%  |
| Row Of Chips | 17        | 7.36%   |
| Chip         | 3         | 1.3%    |
| Unknown      | 2         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 80        | 32.92%  |
| 4096  | 74        | 30.45%  |
| 2048  | 42        | 17.28%  |
| 16384 | 31        | 12.76%  |
| 1024  | 10        | 4.12%   |
| 32768 | 4         | 1.65%   |
| 65536 | 1         | 0.41%   |
| 1536  | 1         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 23.46%  |
| 3200    | 40        | 16.46%  |
| 2667    | 27        | 11.11%  |
| 2400    | 20        | 8.23%   |
| 1333    | 19        | 7.82%   |
| 2133    | 12        | 4.94%   |
| 667     | 9         | 3.7%    |
| 4267    | 5         | 2.06%   |
| 1334    | 5         | 2.06%   |
| 3600    | 4         | 1.65%   |
| 3000    | 4         | 1.65%   |
| 1067    | 4         | 1.65%   |
| 1066    | 4         | 1.65%   |
| Unknown | 4         | 1.65%   |
| 2666    | 3         | 1.23%   |
| 1867    | 3         | 1.23%   |
| 3466    | 2         | 0.82%   |
| 3266    | 2         | 0.82%   |
| 800     | 2         | 0.82%   |
| 5600    | 1         | 0.41%   |
| 4800    | 1         | 0.41%   |
| 4266    | 1         | 0.41%   |
| 4199    | 1         | 0.41%   |
| 4000    | 1         | 0.41%   |
| 3866    | 1         | 0.41%   |
| 3733    | 1         | 0.41%   |
| 3400    | 1         | 0.41%   |
| 3020    | 1         | 0.41%   |
| 2800    | 1         | 0.41%   |
| 2134    | 1         | 0.41%   |
| 2000    | 1         | 0.41%   |
| 1866    | 1         | 0.41%   |
| 1800    | 1         | 0.41%   |
| 1776    | 1         | 0.41%   |
| 1648    | 1         | 0.41%   |
| 533     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 37.5%   |
| Brother Industries  | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| Minolta             | 1         | 12.5%   |
| Canon               | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SF-760 Series         | 1         | 12.5%   |
| Minolta PagePro 1300W         | 1         | 12.5%   |
| HP DeskJet D1360              | 1         | 12.5%   |
| HP DeskJet 840c               | 1         | 12.5%   |
| HP Deskjet 3070 B611 series   | 1         | 12.5%   |
| Canon TS3500 series           | 1         | 12.5%   |
| Brother HL-2030 Laser Printer | 1         | 12.5%   |
| Brother DCP-7040              | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 33.33%  |
| HP ScanJet 7400c                       | 1         | 33.33%  |
| Canon CanoScan LiDE 100                | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 46        | 23.47%  |
| Realtek Semiconductor                  | 17        | 8.67%   |
| Quanta                                 | 14        | 7.14%   |
| Microdia                               | 14        | 7.14%   |
| IMC Networks                           | 14        | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 6.12%   |
| Suyin                                  | 11        | 5.61%   |
| Sunplus Innovation Technology          | 10        | 5.1%    |
| Acer                                   | 8         | 4.08%   |
| Logitech                               | 7         | 3.57%   |
| Luxvisions Innotech Limited            | 4         | 2.04%   |
| Z-Star Microelectronics                | 3         | 1.53%   |
| Microsoft                              | 3         | 1.53%   |
| Lite-On Technology                     | 3         | 1.53%   |
| Apple                                  | 3         | 1.53%   |
| Alcor Micro                            | 3         | 1.53%   |
| Silicon Motion                         | 2         | 1.02%   |
| Ricoh                                  | 2         | 1.02%   |
| icSpring                               | 2         | 1.02%   |
| Xiongmai                               | 1         | 0.51%   |
| Xiaomi                                 | 1         | 0.51%   |
| USB Camera CS                          | 1         | 0.51%   |
| Syntek                                 | 1         | 0.51%   |
| SunplusIT                              | 1         | 0.51%   |
| Sunplus Technology                     | 1         | 0.51%   |
| Sonix Technology                       | 1         | 0.51%   |
| Samsung Electronics                    | 1         | 0.51%   |
| Primax Electronics                     | 1         | 0.51%   |
| OYT Tech                               | 1         | 0.51%   |
| OmniVision Technologies                | 1         | 0.51%   |
| MacroSilicon                           | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| KYE Systems (Mouse Systems)            | 1         | 0.51%   |
| Importek                               | 1         | 0.51%   |
| Guillemot                              | 1         | 0.51%   |
| Creative Technology                    | 1         | 0.51%   |
| Alpha Imaging Technology               | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 14        | 7.11%   |
| Realtek USB Camera                                  | 4         | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.03%   |
| IMC Networks Integrated Camera                      | 4         | 2.03%   |
| Chicony HD WebCam                                   | 4         | 2.03%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.52%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 1.52%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.52%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 1.52%   |
| Quanta HD User Facing                               | 3         | 1.52%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 1.52%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.52%   |
| Chicony EasyCamera                                  | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.52%   |
| Acer Integrated Camera                              | 3         | 1.52%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 1.02%   |
| Realtek HP Truevision HD                            | 2         | 1.02%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 1.02%   |
| Quanta HP Webcam                                    | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.02%   |
| Microdia Webcam Vitade AF                           | 2         | 1.02%   |
| Microdia Lenovo EasyCamera                          | 2         | 1.02%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.02%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.02%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 1.02%   |
| icSpring camera                                     | 2         | 1.02%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.02%   |
| Chicony USB2.0 Camera                               | 2         | 1.02%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 1.02%   |
| Chicony HP Truevision HD                            | 2         | 1.02%   |
| Alcor Micro USB Camera                              | 2         | 1.02%   |
| Acer SunplusIT Integrated Camera                    | 2         | 1.02%   |
| Z-Star Vimicro USB Camera (Altair)                  | 1         | 0.51%   |
| Z-Star Traveler TV 6500 SF Dia-scanner              | 1         | 0.51%   |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 0.51%   |
| Xiongmai web camera                                 | 1         | 0.51%   |
| Xiaomi Mi/Redmi series (PTP)                        | 1         | 0.51%   |
| USB Camera CS USB Camera CS                         | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 39.29%  |
| Synaptics                  | 5         | 17.86%  |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| Upek                       | 4         | 14.29%  |
| STMicroelectronics         | 2         | 7.14%   |
| Elan Microelectronics      | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 10.71%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 10.71%  |
| Shenzhen Goodix  Fingerprint Device                    | 3         | 10.71%  |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 2         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 7.14%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 7.14%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 3.57%   |
| Synaptics  WBDI                                        | 1         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.57%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.57%   |
| Unknown                                                | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 8         | 38.1%   |
| Alcor Micro              | 7         | 33.33%  |
| O2 Micro                 | 2         | 9.52%   |
| Lenovo                   | 2         | 9.52%   |
| Reiner SCT Kartensysteme | 1         | 4.76%   |
| In Focus Systems         | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 33.33%  |
| Broadcom 58200                                                               | 3         | 14.29%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 9.52%   |
| Broadcom 5880                                                                | 2         | 9.52%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 4.76%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 233       | 72.81%  |
| 1     | 68        | 21.25%  |
| 2     | 14        | 4.38%   |
| 3     | 4         | 1.25%   |
| 5     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 25.47%  |
| Graphics card            | 21        | 19.81%  |
| Chipcard                 | 21        | 19.81%  |
| Camera                   | 9         | 8.49%   |
| Net/wireless             | 7         | 6.6%    |
| Multimedia controller    | 5         | 4.72%   |
| Unassigned class         | 3         | 2.83%   |
| Network                  | 3         | 2.83%   |
| Card reader              | 3         | 2.83%   |
| Bluetooth                | 3         | 2.83%   |
| Storage                  | 1         | 0.94%   |
| Sound                    | 1         | 0.94%   |
| Net/ethernet             | 1         | 0.94%   |
| Communication controller | 1         | 0.94%   |

