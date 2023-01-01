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

Total: 347

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-56-generic          | 34        | 11.45%  |
| 5.15.0-52-generic          | 34        | 11.45%  |
| 5.15.0-47-generic          | 31        | 10.44%  |
| 5.15.0-48-generic          | 25        | 8.42%   |
| 5.15.0-25-generic          | 19        | 6.4%    |
| 5.15.0-46-generic          | 17        | 5.72%   |
| 5.15.0-27-generic          | 14        | 4.71%   |
| 5.15.0-53-generic          | 13        | 4.38%   |
| 5.15.0-50-generic          | 9         | 3.03%   |
| 5.15.0-43-generic          | 9         | 3.03%   |
| 5.15.0-41-generic          | 9         | 3.03%   |
| 5.15.0-40-generic          | 9         | 3.03%   |
| 5.15.0-39-generic          | 6         | 2.02%   |
| 5.15.0-37-generic          | 5         | 1.68%   |
| 5.15.0-35-generic          | 5         | 1.68%   |
| 5.15.0-33-generic          | 4         | 1.35%   |
| 5.15.0-30-generic          | 4         | 1.35%   |
| 5.15.0-57-generic          | 3         | 1.01%   |
| 5.17.0-1020-oem            | 2         | 0.67%   |
| 5.17.0-1013-oem            | 2         | 0.67%   |
| 5.15.0-54-generic          | 2         | 0.67%   |
| 5.15.0-50-lowlatency       | 2         | 0.67%   |
| 5.15.0-48-lowlatency       | 2         | 0.67%   |
| 5.15.0-46-lowlatency       | 2         | 0.67%   |
| 6.1.0                      | 1         | 0.34%   |
| 6.0.9-060009-generic       | 1         | 0.34%   |
| 6.0.7-x64v3-xanmod1        | 1         | 0.34%   |
| 6.0.0-1007-oem             | 1         | 0.34%   |
| 6.0.0                      | 1         | 0.34%   |
| 5.4.0-126-generic          | 1         | 0.34%   |
| 5.4.0-122-generic          | 1         | 0.34%   |
| 5.19.5-051905-generic      | 1         | 0.34%   |
| 5.19.13-xanmod1            | 1         | 0.34%   |
| 5.19.1                     | 1         | 0.34%   |
| 5.19.0-8.2-liquorix-amd64  | 1         | 0.34%   |
| 5.19.0-15.2-liquorix-amd64 | 1         | 0.34%   |
| 5.19.0-051900-generic      | 1         | 0.34%   |
| 5.18.12-051812-generic     | 1         | 0.34%   |
| 5.18.0-10.1-liquorix-amd64 | 1         | 0.34%   |
| 5.18.0                     | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 252       | 88.11%  |
| 5.17.0   | 9         | 3.15%   |
| 5.19.0   | 3         | 1.05%   |
| 6.0.0    | 2         | 0.7%    |
| 5.4.0    | 2         | 0.7%    |
| 5.18.0   | 2         | 0.7%    |
| 6.1.0    | 1         | 0.35%   |
| 6.0.9    | 1         | 0.35%   |
| 6.0.7    | 1         | 0.35%   |
| 5.19.5   | 1         | 0.35%   |
| 5.19.13  | 1         | 0.35%   |
| 5.19.1   | 1         | 0.35%   |
| 5.18.12  | 1         | 0.35%   |
| 5.17.3   | 1         | 0.35%   |
| 5.16.9   | 1         | 0.35%   |
| 5.15.74  | 1         | 0.35%   |
| 5.15.68  | 1         | 0.35%   |
| 5.15.61  | 1         | 0.35%   |
| 5.15.59  | 1         | 0.35%   |
| 5.15.48  | 1         | 0.35%   |
| 5.15.23  | 1         | 0.35%   |
| 4.19.241 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 258       | 90.21%  |
| 5.17    | 10        | 3.5%    |
| 5.19    | 6         | 2.1%    |
| 6.0     | 4         | 1.4%    |
| 5.18    | 3         | 1.05%   |
| 5.4     | 2         | 0.7%    |
| 6.1     | 1         | 0.35%   |
| 5.16    | 1         | 0.35%   |
| 4.19    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 277       | 97.88%  |
| aarch64 | 4         | 1.41%   |
| armv7l  | 2         | 0.71%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 274       | 96.82%  |
| GNOME           | 7         | 2.47%   |
| i3              | 1         | 0.35%   |
| GNOME Flashback | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 275       | 96.49%  |
| Tty     | 7         | 2.46%   |
| Wayland | 3         | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 251       | 88.69%  |
| GDM3    | 16        | 5.65%   |
| Unknown | 13        | 4.59%   |
| SLiM    | 1         | 0.35%   |
| SDDM    | 1         | 0.35%   |
| GDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 111       | 39.22%  |
| fr_FR | 37        | 13.07%  |
| de_DE | 34        | 12.01%  |
| it_IT | 23        | 8.13%   |
| en_GB | 11        | 3.89%   |
| ru_RU | 9         | 3.18%   |
| pt_BR | 9         | 3.18%   |
| en_CA | 6         | 2.12%   |
| es_ES | 4         | 1.41%   |
| en_AU | 4         | 1.41%   |
| hu_HU | 3         | 1.06%   |
| cs_CZ | 3         | 1.06%   |
| tr_TR | 2         | 0.71%   |
| nl_NL | 2         | 0.71%   |
| ja_JP | 2         | 0.71%   |
| es_VE | 2         | 0.71%   |
| es_CO | 2         | 0.71%   |
| en_IN | 2         | 0.71%   |
| C     | 2         | 0.71%   |
| sv_SE | 1         | 0.35%   |
| ru_UA | 1         | 0.35%   |
| pl_PL | 1         | 0.35%   |
| nl_BE | 1         | 0.35%   |
| ko_KR | 1         | 0.35%   |
| fr_CA | 1         | 0.35%   |
| fr_BE | 1         | 0.35%   |
| fi_FI | 1         | 0.35%   |
| es_MX | 1         | 0.35%   |
| es_CL | 1         | 0.35%   |
| es_AR | 1         | 0.35%   |
| en_ZA | 1         | 0.35%   |
| en_IL | 1         | 0.35%   |
| de_CH | 1         | 0.35%   |
| bg_BG | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 149       | 52.46%  |
| BIOS | 135       | 47.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 258       | 91.17%  |
| Overlay | 13        | 4.59%   |
| Zfs     | 6         | 2.12%   |
| Btrfs   | 5         | 1.77%   |
| Ext3    | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 197       | 67.7%   |
| Unknown | 62        | 21.31%  |
| MBR     | 32        | 11%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 246       | 86.01%  |
| Yes       | 40        | 13.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 190       | 66.9%   |
| Yes       | 94        | 33.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 53        | 18.73%  |
| Lenovo                  | 45        | 15.9%   |
| Hewlett-Packard         | 44        | 15.55%  |
| Dell                    | 30        | 10.6%   |
| Acer                    | 18        | 6.36%   |
| MSI                     | 16        | 5.65%   |
| Gigabyte Technology     | 7         | 2.47%   |
| Google                  | 6         | 2.12%   |
| ASRock                  | 6         | 2.12%   |
| Supermicro              | 4         | 1.41%   |
| Apple                   | 4         | 1.41%   |
| Toshiba                 | 3         | 1.06%   |
| Sony                    | 3         | 1.06%   |
| Intel                   | 3         | 1.06%   |
| HUAWEI                  | 3         | 1.06%   |
| GPU Company             | 3         | 1.06%   |
| Unknown                 | 3         | 1.06%   |
| sunxi                   | 2         | 0.71%   |
| Rockchip                | 2         | 0.71%   |
| PCWare                  | 2         | 0.71%   |
| Packard Bell            | 2         | 0.71%   |
| VIT                     | 1         | 0.35%   |
| Tactus                  | 1         | 0.35%   |
| Standard                | 1         | 0.35%   |
| Schenker                | 1         | 0.35%   |
| Samsung Electronics     | 1         | 0.35%   |
| Raspberry Pi Foundation | 1         | 0.35%   |
| Pine Microsystems       | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| Microsoft               | 1         | 0.35%   |
| Medion                  | 1         | 0.35%   |
| Mediacom                | 1         | 0.35%   |
| MACHINIST               | 1         | 0.35%   |
| LG Electronics          | 1         | 0.35%   |
| Itautec                 | 1         | 0.35%   |
| HIGRADED                | 1         | 0.35%   |
| Hardkernel              | 1         | 0.35%   |
| Fusion5                 | 1         | 0.35%   |
| Fujitsu                 | 1         | 0.35%   |
| Foxconn                 | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| HP EliteBook 840 G3                | 4         | 1.41%   |
| ASUS All Series                    | 4         | 1.41%   |
| Unknown                            | 4         | 1.41%   |
| Dell OptiPlex 7010                 | 3         | 1.06%   |
| Rockchip RK3318 BOX                | 2         | 0.71%   |
| MSI MS-7D46                        | 2         | 0.71%   |
| MSI MS-7D43                        | 2         | 0.71%   |
| MSI MS-7C52                        | 2         | 0.71%   |
| HP Pavilion Notebook               | 2         | 0.71%   |
| HP 255 G8 Notebook PC              | 2         | 0.71%   |
| GPU Company GWTN116-3              | 2         | 0.71%   |
| Dell Latitude 7420                 | 2         | 0.71%   |
| ASUS K30AD_M31AD_M51AD             | 2         | 0.71%   |
| Acer Switch SW312-31               | 2         | 0.71%   |
| VIT Aptio CRB                      | 1         | 0.35%   |
| Toshiba Satellite Pro R50-C        | 1         | 0.35%   |
| Toshiba Satellite C650             | 1         | 0.35%   |
| Toshiba PT10F                      | 1         | 0.35%   |
| Tactus GeoBook 140                 | 1         | 0.35%   |
| Supermicro X10SRA                  | 1         | 0.35%   |
| Supermicro Super Server            | 1         | 0.35%   |
| Supermicro M12SWA-TF               | 1         | 0.35%   |
| Supermicro AS -5014A-TT            | 1         | 0.35%   |
| sunxi LeMaker Banana Pi            | 1         | 0.35%   |
| sunxi Allwinner sun7i (A20) Family | 1         | 0.35%   |
| Sony VPCS12V9E                     | 1         | 0.35%   |
| Sony VPCEH25EN                     | 1         | 0.35%   |
| Sony SVE1512C6EB                   | 1         | 0.35%   |
| Schenker WORK (Early 2021)         | 1         | 0.35%   |
| Samsung 370E4K                     | 1         | 0.35%   |
| RPi Raspberry Pi 4 Model B Rev 1.5 | 1         | 0.35%   |
| Pine Microsystems Pine64 Rock64    | 1         | 0.35%   |
| PCWare IPX1800E2                   | 1         | 0.35%   |
| PCWare IPMH81G1                    | 1         | 0.35%   |
| Panasonic CF-D1DVA06F3             | 1         | 0.35%   |
| Packard Bell IMEDIA X9305          | 1         | 0.35%   |
| Packard Bell EasyNote MH45         | 1         | 0.35%   |
| MSI MS-7D25                        | 1         | 0.35%   |
| MSI MS-7C91                        | 1         | 0.35%   |
| MSI MS-7C08                        | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 21        | 7.42%   |
| HP Pavilion           | 13        | 4.59%   |
| Acer Aspire           | 11        | 3.89%   |
| Dell Latitude         | 9         | 3.18%   |
| ASUS PRIME            | 8         | 2.83%   |
| HP EliteBook          | 7         | 2.47%   |
| Dell OptiPlex         | 7         | 2.47%   |
| Lenovo IdeaPad        | 6         | 2.12%   |
| Dell Inspiron         | 6         | 2.12%   |
| Lenovo ThinkCentre    | 5         | 1.77%   |
| HP Compaq             | 4         | 1.41%   |
| ASUS VivoBook         | 4         | 1.41%   |
| ASUS All              | 4         | 1.41%   |
| Unknown               | 4         | 1.41%   |
| HP Laptop             | 3         | 1.06%   |
| HP EliteDesk          | 3         | 1.06%   |
| HP 255                | 3         | 1.06%   |
| Dell Precision        | 3         | 1.06%   |
| ASUS TUF              | 3         | 1.06%   |
| ASUS ROG              | 3         | 1.06%   |
| Toshiba Satellite     | 2         | 0.71%   |
| Rockchip RK3318       | 2         | 0.71%   |
| MSI MS-7D46           | 2         | 0.71%   |
| MSI MS-7D43           | 2         | 0.71%   |
| MSI MS-7C52           | 2         | 0.71%   |
| Lenovo ThinkBook      | 2         | 0.71%   |
| HP ProBook            | 2         | 0.71%   |
| GPU Company GWTN116-3 | 2         | 0.71%   |
| Dell XPS              | 2         | 0.71%   |
| Dell PowerEdge        | 2         | 0.71%   |
| ASUS ZenBook          | 2         | 0.71%   |
| ASUS P8H61-M          | 2         | 0.71%   |
| ASUS K30AD            | 2         | 0.71%   |
| ASUS ASUS             | 2         | 0.71%   |
| Acer Veriton          | 2         | 0.71%   |
| Acer Switch           | 2         | 0.71%   |
| VIT Aptio             | 1         | 0.35%   |
| Toshiba PT10F         | 1         | 0.35%   |
| Tactus GeoBook        | 1         | 0.35%   |
| Supermicro X10SRA     | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 29        | 10.25%  |
| 2020    | 26        | 9.19%   |
| 2014    | 23        | 8.13%   |
| 2018    | 21        | 7.42%   |
| 2017    | 21        | 7.42%   |
| 2016    | 19        | 6.71%   |
| 2012    | 19        | 6.71%   |
| 2019    | 18        | 6.36%   |
| 2013    | 17        | 6.01%   |
| 2011    | 16        | 5.65%   |
| 2015    | 15        | 5.3%    |
| 2010    | 15        | 5.3%    |
| 2022    | 11        | 3.89%   |
| 2009    | 9         | 3.18%   |
| 2007    | 8         | 2.83%   |
| 2008    | 7         | 2.47%   |
| Unknown | 6         | 2.12%   |
| 2006    | 2         | 0.71%   |
| 2005    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 159       | 56.18%  |
| Desktop        | 96        | 33.92%  |
| Server         | 7         | 2.47%   |
| System on chip | 6         | 2.12%   |
| Convertible    | 5         | 1.77%   |
| Tablet         | 4         | 1.41%   |
| All in one     | 4         | 1.41%   |
| Mini pc        | 2         | 0.71%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 261       | 92.23%  |
| Enabled  | 22        | 7.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 277       | 97.88%  |
| Yes  | 6         | 2.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 77        | 27.11%  |
| 3.01-4.0        | 71        | 25%     |
| 16.01-24.0      | 52        | 18.31%  |
| 8.01-16.0       | 34        | 11.97%  |
| 1.01-2.0        | 18        | 6.34%   |
| 32.01-64.0      | 17        | 5.99%   |
| 64.01-256.0     | 5         | 1.76%   |
| 24.01-32.0      | 4         | 1.41%   |
| 0.51-1.0        | 3         | 1.06%   |
| 2.01-3.0        | 2         | 0.7%    |
| More than 256.0 | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 130       | 44.07%  |
| 2.01-3.0  | 72        | 24.41%  |
| 4.01-8.0  | 27        | 9.15%   |
| 3.01-4.0  | 27        | 9.15%   |
| 0.51-1.0  | 24        | 8.14%   |
| 8.01-16.0 | 12        | 4.07%   |
| 0.01-0.5  | 3         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 180       | 63.16%  |
| 2      | 62        | 21.75%  |
| 3      | 20        | 7.02%   |
| 4      | 13        | 4.56%   |
| 5      | 4         | 1.4%    |
| 6      | 3         | 1.05%   |
| 10     | 1         | 0.35%   |
| 7      | 1         | 0.35%   |
| 0      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 164       | 57.75%  |
| Yes       | 120       | 42.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 82.69%  |
| No        | 49        | 17.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 72.79%  |
| No        | 77        | 27.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 55.12%  |
| No        | 127       | 44.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 42        | 14.74%  |
| USA          | 40        | 14.04%  |
| France       | 38        | 13.33%  |
| Italy        | 26        | 9.12%   |
| Russia       | 12        | 4.21%   |
| UK           | 11        | 3.86%   |
| Brazil       | 9         | 3.16%   |
| Sweden       | 8         | 2.81%   |
| Canada       | 7         | 2.46%   |
| Netherlands  | 6         | 2.11%   |
| Poland       | 5         | 1.75%   |
| Czechia      | 5         | 1.75%   |
| Belgium      | 5         | 1.75%   |
| Mexico       | 4         | 1.4%    |
| Iran         | 4         | 1.4%    |
| India        | 4         | 1.4%    |
| Australia    | 4         | 1.4%    |
| Turkey       | 3         | 1.05%   |
| Spain        | 3         | 1.05%   |
| Portugal     | 3         | 1.05%   |
| Malaysia     | 3         | 1.05%   |
| Indonesia    | 3         | 1.05%   |
| Hungary      | 3         | 1.05%   |
| Colombia     | 3         | 1.05%   |
| Argentina    | 3         | 1.05%   |
| Venezuela    | 2         | 0.7%    |
| Taiwan       | 2         | 0.7%    |
| Japan        | 2         | 0.7%    |
| Israel       | 2         | 0.7%    |
| Greece       | 2         | 0.7%    |
| Finland      | 2         | 0.7%    |
| Belarus      | 2         | 0.7%    |
| Austria      | 2         | 0.7%    |
| Vietnam      | 1         | 0.35%   |
| Switzerland  | 1         | 0.35%   |
| South Korea  | 1         | 0.35%   |
| South Africa | 1         | 0.35%   |
| Slovenia     | 1         | 0.35%   |
| Sint Maarten | 1         | 0.35%   |
| Norway       | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Paris                | 7         | 2.41%   |
| Berlin               | 5         | 1.72%   |
| Munich               | 4         | 1.37%   |
| Melbourne            | 4         | 1.37%   |
| Uppsala              | 3         | 1.03%   |
| Stuttgart            | 3         | 1.03%   |
| Milan                | 3         | 1.03%   |
| Kuala Lumpur         | 3         | 1.03%   |
| Biella               | 3         | 1.03%   |
| Ankara               | 3         | 1.03%   |
| Washington           | 2         | 0.69%   |
| Warsaw               | 2         | 0.69%   |
| Västerås           | 2         | 0.69%   |
| Tehran               | 2         | 0.69%   |
| St Petersburg        | 2         | 0.69%   |
| Oklahoma City        | 2         | 0.69%   |
| Mumbai               | 2         | 0.69%   |
| Moscow               | 2         | 0.69%   |
| Leipzig              | 2         | 0.69%   |
| Lavras               | 2         | 0.69%   |
| Kazan’             | 2         | 0.69%   |
| Jakarta              | 2         | 0.69%   |
| Indianapolis         | 2         | 0.69%   |
| Helsinki             | 2         | 0.69%   |
| Hamburg              | 2         | 0.69%   |
| Farmington           | 2         | 0.69%   |
| Clermont-Ferrand     | 2         | 0.69%   |
| Budapest             | 2         | 0.69%   |
| Brest                | 2         | 0.69%   |
| Belfort              | 2         | 0.69%   |
| Auxerre              | 2         | 0.69%   |
| Żywiec              | 1         | 0.34%   |
| Yokohama             | 1         | 0.34%   |
| Wierden              | 1         | 0.34%   |
| Wettringen           | 1         | 0.34%   |
| Waghausel            | 1         | 0.34%   |
| Waarder              | 1         | 0.34%   |
| Vohenstrauss         | 1         | 0.34%   |
| Vohburg an der Donau | 1         | 0.34%   |
| Villavicencio        | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 62        | 83     | 15.31%  |
| Samsung Electronics | 61        | 78     | 15.06%  |
| Seagate             | 46        | 59     | 11.36%  |
| Unknown             | 29        | 32     | 7.16%   |
| Kingston            | 21        | 26     | 5.19%   |
| Toshiba             | 20        | 20     | 4.94%   |
| SanDisk             | 20        | 21     | 4.94%   |
| Hitachi             | 17        | 25     | 4.2%    |
| SK hynix            | 15        | 16     | 3.7%    |
| Crucial             | 14        | 18     | 3.46%   |
| Intel               | 11        | 11     | 2.72%   |
| HGST                | 9         | 10     | 2.22%   |
| PNY                 | 8         | 8      | 1.98%   |
| China               | 6         | 7      | 1.48%   |
| Unknown             | 5         | 5      | 1.23%   |
| Patriot             | 4         | 4      | 0.99%   |
| Transcend           | 3         | 4      | 0.74%   |
| Silicon Motion      | 3         | 3      | 0.74%   |
| Phison              | 3         | 10     | 0.74%   |
| Micron Technology   | 3         | 3      | 0.74%   |
| A-DATA Technology   | 3         | 5      | 0.74%   |
| USB3.0              | 2         | 4      | 0.49%   |
| TO Exter            | 2         | 2      | 0.49%   |
| TEXTORM             | 2         | 2      | 0.49%   |
| Maxtor              | 2         | 2      | 0.49%   |
| LITEON              | 2         | 2      | 0.49%   |
| KIOXIA              | 2         | 2      | 0.49%   |
| ASMT                | 2         | 5      | 0.49%   |
| Apacer              | 2         | 2      | 0.49%   |
| XPG                 | 1         | 1      | 0.25%   |
| Vaseky              | 1         | 1      | 0.25%   |
| SSSTC               | 1         | 1      | 0.25%   |
| SSK                 | 1         | 1      | 0.25%   |
| SSD0240S            | 1         | 1      | 0.25%   |
| SPCC                | 1         | 1      | 0.25%   |
| Phison Electronics  | 1         | 2      | 0.25%   |
| PHD 3.0             | 1         | 1      | 0.25%   |
| OCZ                 | 1         | 1      | 0.25%   |
| Netac               | 1         | 1      | 0.25%   |
| Linux               | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                        | 6         | 1.33%   |
| Crucial CT480BX500SSD1 480GB                     | 6         | 1.33%   |
| Samsung SSD 850 EVO 500GB                        | 5         | 1.11%   |
| Kingston SA400S37480G 480GB SSD                  | 5         | 1.11%   |
| Kingston SA400S37240G 240GB SSD                  | 5         | 1.11%   |
| Unknown                                          | 5         | 1.11%   |
| Unknown MMC Card  32GB                           | 3         | 0.67%   |
| Toshiba MQ01ABF050 500GB                         | 3         | 0.67%   |
| Toshiba HDWD110 1TB                              | 3         | 0.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 3         | 0.67%   |
| Seagate ST500LM000-1EJ162 500GB                  | 3         | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                  | 3         | 0.67%   |
| SanDisk DF4064  64GB                             | 3         | 0.67%   |
| Samsung SSD 840 Series 120GB                     | 3         | 0.67%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB           | 3         | 0.67%   |
| PNY CS900 120GB SSD                              | 3         | 0.67%   |
| HGST HTS541010A9E680 1TB                         | 3         | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 2         | 0.44%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 2         | 0.44%   |
| WDC WD10EZEX-00BBHA0 1TB                         | 2         | 0.44%   |
| Unknown SD/MMC/MS PRO 64GB                       | 2         | 0.44%   |
| Unknown SA08G  8GB                               | 2         | 0.44%   |
| Unknown MMC64G  64GB                             | 2         | 0.44%   |
| Toshiba DT01ACA200 2TB                           | 2         | 0.44%   |
| Toshiba DT01ACA100 1TB                           | 2         | 0.44%   |
| Toshiba DT01ACA050 500GB                         | 2         | 0.44%   |
| TO Exter nal USB 3.0 512GB                       | 2         | 0.44%   |
| TEXTORM BM5 240GB SSD                            | 2         | 0.44%   |
| SK hynix NVMe SSD Drive 1024GB                   | 2         | 0.44%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 0.44%   |
| Seagate ST4000DM004-2CV104 4TB                   | 2         | 0.44%   |
| Seagate ST31000528AS 1TB                         | 2         | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 0.44%   |
| Seagate ST1000DM003-1SB102 1TB                   | 2         | 0.44%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 2         | 0.44%   |
| SanDisk SDSSDA240G 240GB                         | 2         | 0.44%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD              | 2         | 0.44%   |
| SanDisk DF4032  32GB                             | 2         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB                     | 2         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 51        | 70     | 32.9%   |
| Seagate             | 46        | 58     | 29.68%  |
| Hitachi             | 17        | 25     | 10.97%  |
| Toshiba             | 16        | 16     | 10.32%  |
| HGST                | 9         | 10     | 5.81%   |
| Samsung Electronics | 8         | 12     | 5.16%   |
| USB3.0              | 2         | 4      | 1.29%   |
| Unknown             | 2         | 2      | 1.29%   |
| ASMT                | 2         | 5      | 1.29%   |
| PHD 3.0             | 1         | 1      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 43     | 25.71%  |
| Kingston            | 18        | 20     | 12.86%  |
| Crucial             | 13        | 17     | 9.29%   |
| SanDisk             | 10        | 11     | 7.14%   |
| WDC                 | 7         | 7      | 5%      |
| PNY                 | 7         | 7      | 5%      |
| China               | 6         | 7      | 4.29%   |
| Patriot             | 4         | 4      | 2.86%   |
| Intel               | 4         | 4      | 2.86%   |
| Transcend           | 3         | 3      | 2.14%   |
| Toshiba             | 3         | 3      | 2.14%   |
| A-DATA Technology   | 3         | 5      | 2.14%   |
| TO Exter            | 2         | 2      | 1.43%   |
| TEXTORM             | 2         | 2      | 1.43%   |
| SK hynix            | 2         | 2      | 1.43%   |
| LITEON              | 2         | 2      | 1.43%   |
| Apacer              | 2         | 2      | 1.43%   |
| Vaseky              | 1         | 1      | 0.71%   |
| SSSTC               | 1         | 1      | 0.71%   |
| SPCC                | 1         | 1      | 0.71%   |
| OCZ                 | 1         | 1      | 0.71%   |
| Netac               | 1         | 1      | 0.71%   |
| Micron Technology   | 1         | 1      | 0.71%   |
| Maxtor              | 1         | 1      | 0.71%   |
| Linux               | 1         | 1      | 0.71%   |
| KingFast            | 1         | 1      | 0.71%   |
| KingDian            | 1         | 1      | 0.71%   |
| Kimtigo             | 1         | 1      | 0.71%   |
| Intenso             | 1         | 1      | 0.71%   |
| INNOVATION IT       | 1         | 1      | 0.71%   |
| FORESEE             | 1         | 1      | 0.71%   |
| ASMedia             | 1         | 1      | 0.71%   |
| Unknown             | 1         | 1      | 0.71%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 126       | 204    | 34.71%  |
| SSD     | 121       | 157    | 33.33%  |
| NVMe    | 74        | 91     | 20.39%  |
| MMC     | 36        | 41     | 9.92%   |
| Unknown | 6         | 6      | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 205       | 341    | 61.93%  |
| NVMe | 74        | 91     | 22.36%  |
| MMC  | 36        | 41     | 10.88%  |
| SAS  | 16        | 26     | 4.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 163       | 234    | 60.82%  |
| 0.51-1.0   | 67        | 78     | 25%     |
| 1.01-2.0   | 15        | 17     | 5.6%    |
| 3.01-4.0   | 14        | 20     | 5.22%   |
| 2.01-3.0   | 4         | 5      | 1.49%   |
| 4.01-10.0  | 3         | 5      | 1.12%   |
| 10.01-20.0 | 2         | 2      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 75        | 26.13%  |
| 251-500        | 69        | 24.04%  |
| 501-1000       | 38        | 13.24%  |
| 51-100         | 27        | 9.41%   |
| 1001-2000      | 22        | 7.67%   |
| 1-20           | 20        | 6.97%   |
| More than 3000 | 15        | 5.23%   |
| 21-50          | 14        | 4.88%   |
| 2001-3000      | 6         | 2.09%   |
| Unknown        | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 100       | 34.6%   |
| 21-50          | 60        | 20.76%  |
| 101-250        | 35        | 12.11%  |
| 51-100         | 34        | 11.76%  |
| 251-500        | 31        | 10.73%  |
| 501-1000       | 11        | 3.81%   |
| 1001-2000      | 7         | 2.42%   |
| More than 3000 | 5         | 1.73%   |
| 2001-3000      | 5         | 1.73%   |
| Unknown        | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB                           | 2         | 2      | 4.44%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 4.44%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 2.22%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                 | 1         | 1      | 2.22%   |
| WDC WD5000AAKX-00ERMA0 500GB                     | 1         | 1      | 2.22%   |
| WDC WD3200AAKS-00L9A0 320GB                      | 1         | 1      | 2.22%   |
| WDC WD20EFRX-68AX9N0 2TB                         | 1         | 1      | 2.22%   |
| WDC WD2002FYPS-02W3B0 2TB                        | 1         | 1      | 2.22%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 2.22%   |
| WDC WD10EZEX-60ZF5A0 1TB                         | 1         | 1      | 2.22%   |
| WDC WD10EAVS-00D7B1 1TB                          | 1         | 1      | 2.22%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1         | 1      | 2.22%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1         | 1      | 2.22%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 2.22%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 2.22%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 2.22%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB                  | 1         | 1      | 2.22%   |
| Seagate ST3750840AS 752GB                        | 1         | 1      | 2.22%   |
| Seagate ST3250318AS 250GB                        | 1         | 2      | 2.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.22%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 2.22%   |
| Samsung Electronics SP2514N 250GB                | 1         | 1      | 2.22%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.22%   |
| Samsung Electronics HM321HI 320GB                | 1         | 2      | 2.22%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 2.22%   |
| Samsung Electronics HD250HJ 250GB                | 1         | 1      | 2.22%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 2.22%   |
| Maxtor STM3160215AS 160GB                        | 1         | 1      | 2.22%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 2.22%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 2.22%   |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 2.22%   |
| Intel SSDSC2BW080A4 80GB                         | 1         | 1      | 2.22%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 1      | 2.22%   |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 2.22%   |
| Hitachi HTS541080G9SA00 80GB                     | 1         | 1      | 2.22%   |
| Hitachi HDS722540VLAT20 40GB                     | 1         | 1      | 2.22%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 2.22%   |
| Hitachi HCP725032GLA380 320GB                    | 1         | 2      | 2.22%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 11     | 25%     |
| Seagate             | 9         | 10     | 20.45%  |
| Hitachi             | 6         | 7      | 13.64%  |
| Samsung Electronics | 5         | 7      | 11.36%  |
| Toshiba             | 2         | 2      | 4.55%   |
| Intel               | 2         | 2      | 4.55%   |
| HGST                | 2         | 2      | 4.55%   |
| SSSTC               | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 1      | 2.27%   |
| Maxtor              | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| Kingston            | 1         | 2      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |
| ASMT                | 1         | 4      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 26.47%  |
| Seagate             | 9         | 10     | 26.47%  |
| Hitachi             | 6         | 7      | 17.65%  |
| Samsung Electronics | 4         | 6      | 11.76%  |
| Toshiba             | 2         | 2      | 5.88%   |
| HGST                | 2         | 2      | 5.88%   |
| Maxtor              | 1         | 1      | 2.94%   |
| ASMT                | 1         | 4      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 41     | 77.5%   |
| SSD  | 9         | 11     | 22.5%   |

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
| Works    | 149       | 238    | 48.22%  |
| Detected | 121       | 209    | 39.16%  |
| Malfunc  | 39        | 52     | 12.62%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 187       | 57.36%  |
| AMD                          | 56        | 17.18%  |
| Samsung Electronics          | 20        | 6.13%   |
| SK hynix                     | 13        | 3.99%   |
| SanDisk                      | 9         | 2.76%   |
| Silicon Motion               | 6         | 1.84%   |
| Kingston Technology Company  | 5         | 1.53%   |
| ASMedia Technology           | 5         | 1.53%   |
| Phison Electronics           | 4         | 1.23%   |
| VIA Technologies             | 3         | 0.92%   |
| Nvidia                       | 3         | 0.92%   |
| JMicron Technology           | 3         | 0.92%   |
| KIOXIA                       | 2         | 0.61%   |
| Toshiba America Info Systems | 1         | 0.31%   |
| Shenzhen Longsys Electronics | 1         | 0.31%   |
| Realtek Semiconductor        | 1         | 0.31%   |
| Micron/Crucial Technology    | 1         | 0.31%   |
| Micron Technology            | 1         | 0.31%   |
| Marvell Technology Group     | 1         | 0.31%   |
| Lenovo                       | 1         | 0.31%   |
| Biwin Storage Technology     | 1         | 0.31%   |
| Apple                        | 1         | 0.31%   |
| Adaptec                      | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 44        | 11.4%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 3.37%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 2.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 2.59%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 2.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 8         | 2.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 2.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 8         | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 2.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8         | 2.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.81%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 6         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 1.55%   |
| AMD FCH SATA Controller D                                                               | 6         | 1.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 5         | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 1.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 5         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 1.3%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.04%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 0.78%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.78%   |
| Nvidia MCP61 IDE                                                                        | 3         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.78%   |
| Intel SSD 660P Series                                                                   | 3         | 0.78%   |
| Intel SATA Controller [RAID mode]                                                       | 3         | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 210       | 61.76%  |
| NVMe | 74        | 21.76%  |
| IDE  | 36        | 10.59%  |
| RAID | 19        | 5.59%   |
| SAS  | 1         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 211       | 74.56%  |
| AMD    | 66        | 23.32%  |
| ARM    | 6         | 2.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 1.41%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 4         | 1.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 4         | 1.41%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 4         | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.41%   |
| ARM Processor                           | 4         | 1.41%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 1.06%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 1.06%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 1.06%   |
| Intel Celeron CPU N3450 @ 1.10GHz       | 3         | 1.06%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 3         | 1.06%   |
| Intel Celeron CPU 847 @ 1.10GHz         | 3         | 1.06%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 3         | 1.06%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz | 3         | 1.06%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 1.06%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 3         | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 3         | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor       | 3         | 1.06%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 2         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz        | 2         | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.7%    |
| Intel Core i5-3570K CPU @ 3.40GHz       | 2         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 0.7%    |
| Intel Core i5-2400S CPU @ 2.50GHz       | 2         | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.7%    |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 0.7%    |
| Intel Core i5 CPU 750 @ 2.67GHz         | 2         | 0.7%    |
| Intel Core i3-9100 CPU @ 3.60GHz        | 2         | 0.7%    |
| Intel Core i3-3240 CPU @ 3.40GHz        | 2         | 0.7%    |
| Intel Core i3-2100 CPU @ 3.10GHz        | 2         | 0.7%    |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 60        | 21.13%  |
| Intel Celeron           | 34        | 11.97%  |
| Intel Core i7           | 27        | 9.51%   |
| Other                   | 26        | 9.15%   |
| Intel Core i3           | 22        | 7.75%   |
| AMD Ryzen 5             | 18        | 6.34%   |
| Intel Core 2 Duo        | 10        | 3.52%   |
| AMD Ryzen 7             | 9         | 3.17%   |
| Intel Xeon              | 8         | 2.82%   |
| Intel Pentium           | 8         | 2.82%   |
| Intel Atom              | 8         | 2.82%   |
| AMD A6                  | 5         | 1.76%   |
| AMD Ryzen 9             | 4         | 1.41%   |
| AMD FX                  | 3         | 1.06%   |
| AMD A8                  | 3         | 1.06%   |
| AMD A10                 | 3         | 1.06%   |
| Intel Pentium Dual      | 2         | 0.7%    |
| Intel Core 2 Quad       | 2         | 0.7%    |
| Intel Core 2            | 2         | 0.7%    |
| ARM Allwinner           | 2         | 0.7%    |
| AMD Ryzen Threadripper  | 2         | 0.7%    |
| AMD Ryzen 5 PRO         | 2         | 0.7%    |
| AMD Ryzen 3             | 2         | 0.7%    |
| AMD Phenom II X4        | 2         | 0.7%    |
| AMD E2                  | 2         | 0.7%    |
| AMD Athlon II X2        | 2         | 0.7%    |
| AMD Athlon              | 2         | 0.7%    |
| AMD A4                  | 2         | 0.7%    |
| Intel Xeon Gold         | 1         | 0.35%   |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Pentium Dual-Core | 1         | 0.35%   |
| Intel Pentium 4         | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core 2 Extreme    | 1         | 0.35%   |
| AMD Sempron             | 1         | 0.35%   |
| AMD Ryzen 7 PRO         | 1         | 0.35%   |
| AMD Phenom II X6        | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD Athlon II           | 1         | 0.35%   |
| AMD Athlon 64 X2        | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 123       | 43.16%  |
| 4       | 100       | 35.09%  |
| 6       | 26        | 9.12%   |
| 8       | 17        | 5.96%   |
| 12      | 4         | 1.4%    |
| 1       | 4         | 1.4%    |
| Unknown | 3         | 1.05%   |
| 64      | 2         | 0.7%    |
| 10      | 2         | 0.7%    |
| 3       | 2         | 0.7%    |
| 16      | 1         | 0.35%   |
| 14      | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 279       | 98.59%  |
| Unknown | 3         | 1.06%   |
| 2       | 1         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 163       | 57.6%   |
| 1       | 117       | 41.34%  |
| Unknown | 3         | 1.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 98.94%  |
| Unknown        | 3         | 1.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 32.04%  |
| 0x806c1    | 13        | 4.58%   |
| 0x306a9    | 11        | 3.87%   |
| 0x206a7    | 10        | 3.52%   |
| 0x306d4    | 7         | 2.46%   |
| 0x506c9    | 6         | 2.11%   |
| 0x406e3    | 6         | 2.11%   |
| 0x306c3    | 6         | 2.11%   |
| 0x806ec    | 5         | 1.76%   |
| 0x30678    | 5         | 1.76%   |
| 0x106e5    | 5         | 1.76%   |
| 0x08608103 | 5         | 1.76%   |
| 0xa0652    | 4         | 1.41%   |
| 0x906ea    | 4         | 1.41%   |
| 0x506e3    | 4         | 1.41%   |
| 0x406c4    | 4         | 1.41%   |
| 0x406c3    | 4         | 1.41%   |
| 0x1067a    | 4         | 1.41%   |
| 0x0800820d | 4         | 1.41%   |
| 0x706a8    | 3         | 1.06%   |
| 0x706a1    | 3         | 1.06%   |
| 0x6fd      | 3         | 1.06%   |
| 0x6fb      | 3         | 1.06%   |
| 0x40651    | 3         | 1.06%   |
| 0x20652    | 3         | 1.06%   |
| 0x10676    | 3         | 1.06%   |
| 0x0a50000c | 3         | 1.06%   |
| 0x08701021 | 3         | 1.06%   |
| 0x08108109 | 3         | 1.06%   |
| 0x010000c8 | 3         | 1.06%   |
| 0x90672    | 2         | 0.7%    |
| 0x806e9    | 2         | 0.7%    |
| 0x806d1    | 2         | 0.7%    |
| 0x6f6      | 2         | 0.7%    |
| 0x506ca    | 2         | 0.7%    |
| 0x306f2    | 2         | 0.7%    |
| 0x206d7    | 2         | 0.7%    |
| 0x20655    | 2         | 0.7%    |
| 0x08600106 | 2         | 0.7%    |
| 0x08600104 | 2         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 9.51%   |
| SandyBridge      | 22        | 7.75%   |
| IvyBridge        | 20        | 7.04%   |
| Silvermont       | 18        | 6.34%   |
| Skylake          | 17        | 5.99%   |
| Haswell          | 16        | 5.63%   |
| Unknown          | 16        | 5.63%   |
| TigerLake        | 15        | 5.28%   |
| Zen 2            | 13        | 4.58%   |
| Zen+             | 10        | 3.52%   |
| Penryn           | 10        | 3.52%   |
| Goldmont         | 9         | 3.17%   |
| Core             | 9         | 3.17%   |
| Broadwell        | 9         | 3.17%   |
| Westmere         | 8         | 2.82%   |
| Goldmont plus    | 7         | 2.46%   |
| Zen 3            | 6         | 2.11%   |
| Nehalem          | 6         | 2.11%   |
| K10              | 6         | 2.11%   |
| Puma             | 5         | 1.76%   |
| Piledriver       | 5         | 1.76%   |
| CometLake        | 5         | 1.76%   |
| Zen              | 4         | 1.41%   |
| Excavator        | 4         | 1.41%   |
| Icelake          | 3         | 1.06%   |
| Bonnell          | 3         | 1.06%   |
| K10 Llano        | 2         | 0.7%    |
| Bobcat           | 2         | 0.7%    |
| Alderlake Hybrid | 2         | 0.7%    |
| Tremont          | 1         | 0.35%   |
| Steamroller      | 1         | 0.35%   |
| NetBurst         | 1         | 0.35%   |
| K8 Hammer        | 1         | 0.35%   |
| Jaguar           | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 172       | 54.43%  |
| Nvidia                     | 74        | 23.42%  |
| AMD                        | 64        | 20.25%  |
| ASPEED Technology          | 4         | 1.27%   |
| Matrox Electronics Systems | 2         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 3.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.08%   |
| Intel HD Graphics 500                                                                    | 7         | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.54%   |
| Intel HD Graphics 620                                                                    | 5         | 1.54%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.54%   |
| AMD Lucienne                                                                             | 5         | 1.54%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.23%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.23%   |
| Intel HD Graphics 530                                                                    | 4         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.23%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 1.23%   |
| AMD Renoir                                                                               | 4         | 1.23%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.92%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.92%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.62%   |
| Nvidia TU117M                                                                            | 2         | 0.62%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2         | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.62%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.62%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.62%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.62%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 141       | 49.82%  |
| 1 x AMD         | 49        | 17.31%  |
| 1 x Nvidia      | 45        | 15.9%   |
| Intel + Nvidia  | 21        | 7.42%   |
| Other           | 7         | 2.47%   |
| 2 x AMD         | 5         | 1.77%   |
| AMD + Nvidia    | 5         | 1.77%   |
| Intel + AMD     | 4         | 1.41%   |
| Nvidia + ASPEED | 3         | 1.06%   |
| 1 x Matrox      | 1         | 0.35%   |
| 1 x ASPEED      | 1         | 0.35%   |
| AMD + Matrox    | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 228       | 80.57%  |
| Proprietary | 43        | 15.19%  |
| Unknown     | 12        | 4.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 69.01%  |
| 0.01-0.5   | 30        | 10.56%  |
| 1.01-2.0   | 22        | 7.75%   |
| 0.51-1.0   | 18        | 6.34%   |
| 3.01-4.0   | 11        | 3.87%   |
| 8.01-16.0  | 3         | 1.06%   |
| 7.01-8.0   | 2         | 0.7%    |
| 32.01-64.0 | 1         | 0.35%   |
| 5.01-6.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 13.09%  |
| Samsung Electronics     | 35        | 11.74%  |
| LG Display              | 29        | 9.73%   |
| BOE                     | 25        | 8.39%   |
| Dell                    | 20        | 6.71%   |
| Chimei Innolux          | 20        | 6.71%   |
| Hewlett-Packard         | 14        | 4.7%    |
| Goldstar                | 10        | 3.36%   |
| Acer                    | 9         | 3.02%   |
| ViewSonic               | 7         | 2.35%   |
| Lenovo                  | 7         | 2.35%   |
| Philips                 | 6         | 2.01%   |
| Iiyama                  | 6         | 2.01%   |
| Chi Mei Optoelectronics | 6         | 2.01%   |
| AOC                     | 6         | 2.01%   |
| PANDA                   | 5         | 1.68%   |
| InfoVision              | 4         | 1.34%   |
| BenQ                    | 4         | 1.34%   |
| Apple                   | 4         | 1.34%   |
| LG Philips              | 3         | 1.01%   |
| Toshiba                 | 2         | 0.67%   |
| KDC                     | 2         | 0.67%   |
| Fujitsu Siemens         | 2         | 0.67%   |
| Envision Peripherals    | 2         | 0.67%   |
| Ancor Communications    | 2         | 0.67%   |
| ___                     | 1         | 0.34%   |
| Vizio                   | 1         | 0.34%   |
| Vita                    | 1         | 0.34%   |
| Vestel Elektronik       | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| TEO                     | 1         | 0.34%   |
| TCL                     | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| Sharp                   | 1         | 0.34%   |
| Sceptre Tech            | 1         | 0.34%   |
| SAC                     | 1         | 0.34%   |
| RTK                     | 1         | 0.34%   |
| Panasonic               | 1         | 0.34%   |
| Packard Bell            | 1         | 0.34%   |
| Nixeus                  | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.99%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch     | 2         | 0.66%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                       | 2         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.66%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.66%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.66%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.66%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.66%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.66%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.66%   |
| ___ LCD Monitor ___1BBC 1920x540 140x90mm 6.6-inch                       | 1         | 0.33%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.33%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                       | 1         | 0.33%   |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.33%   |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch            | 1         | 0.33%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch               | 1         | 0.33%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.33%   |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch             | 1         | 0.33%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 1         | 0.33%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 1         | 0.33%   |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                        | 1         | 0.33%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.33%   |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                          | 1         | 0.33%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                         | 1         | 0.33%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.33%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.33%   |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0657 1920x1080                         | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                         | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM03E3 1680x1050 433x271mm 20.1-inch     | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch     | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch     | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch     | 1         | 0.33%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch        | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 128       | 45.07%  |
| 1366x768 (WXGA)    | 58        | 20.42%  |
| 1600x900 (HD+)     | 20        | 7.04%   |
| 3840x2160 (4K)     | 11        | 3.87%   |
| 1440x900 (WXGA+)   | 11        | 3.87%   |
| 1280x1024 (SXGA)   | 10        | 3.52%   |
| 1920x1200 (WUXGA)  | 7         | 2.46%   |
| 1280x800 (WXGA)    | 7         | 2.46%   |
| 2560x1440 (QHD)    | 6         | 2.11%   |
| 1680x1050 (WSXGA+) | 6         | 2.11%   |
| 1360x768           | 3         | 1.06%   |
| 3840x1600          | 2         | 0.7%    |
| 2160x1440          | 2         | 0.7%    |
| 1024x768 (XGA)     | 2         | 0.7%    |
| 1024x600           | 2         | 0.7%    |
| 3840x1080          | 1         | 0.35%   |
| 2880x1800          | 1         | 0.35%   |
| 2560x1600          | 1         | 0.35%   |
| 2560x1080          | 1         | 0.35%   |
| 1920x540           | 1         | 0.35%   |
| 1920x515           | 1         | 0.35%   |
| 1600x1200          | 1         | 0.35%   |
| 1366x912           | 1         | 0.35%   |
| Unknown            | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 72        | 24.08%  |
| 14      | 31        | 10.37%  |
| 13      | 29        | 9.7%    |
| 24      | 23        | 7.69%   |
| 23      | 21        | 7.02%   |
| 17      | 21        | 7.02%   |
| 27      | 16        | 5.35%   |
| 21      | 14        | 4.68%   |
| Unknown | 12        | 4.01%   |
| 19      | 11        | 3.68%   |
| 18      | 9         | 3.01%   |
| 20      | 6         | 2.01%   |
| 31      | 5         | 1.67%   |
| 26      | 5         | 1.67%   |
| 12      | 4         | 1.34%   |
| 11      | 4         | 1.34%   |
| 22      | 3         | 1%      |
| 37      | 2         | 0.67%   |
| 25      | 2         | 0.67%   |
| 10      | 2         | 0.67%   |
| 84      | 1         | 0.33%   |
| 72      | 1         | 0.33%   |
| 54      | 1         | 0.33%   |
| 32      | 1         | 0.33%   |
| 30      | 1         | 0.33%   |
| 16      | 1         | 0.33%   |
| 6       | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 129       | 44.18%  |
| 501-600     | 61        | 20.89%  |
| 401-500     | 40        | 13.7%   |
| 201-300     | 20        | 6.85%   |
| 351-400     | 17        | 5.82%   |
| Unknown     | 12        | 4.11%   |
| 601-700     | 6         | 2.05%   |
| 801-900     | 2         | 0.68%   |
| 1501-2000   | 2         | 0.68%   |
| 701-800     | 1         | 0.34%   |
| 101-200     | 1         | 0.34%   |
| 1001-1500   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 211       | 77.29%  |
| 16/10   | 37        | 13.55%  |
| 5/4     | 9         | 3.3%    |
| Unknown | 7         | 2.56%   |
| 4/3     | 4         | 1.47%   |
| 3/2     | 2         | 0.73%   |
| 21/9    | 2         | 0.73%   |
| 3.73    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 24.32%  |
| 81-90          | 52        | 17.57%  |
| 201-250        | 48        | 16.22%  |
| 151-200        | 25        | 8.45%   |
| 301-350        | 19        | 6.42%   |
| 141-150        | 14        | 4.73%   |
| Unknown        | 12        | 4.05%   |
| 121-130        | 10        | 3.38%   |
| 71-80          | 9         | 3.04%   |
| 251-300        | 9         | 3.04%   |
| 351-500        | 7         | 2.36%   |
| 51-60          | 4         | 1.35%   |
| 131-140        | 4         | 1.35%   |
| More than 1000 | 3         | 1.01%   |
| 61-70          | 3         | 1.01%   |
| 41-50          | 2         | 0.68%   |
| 1-40           | 1         | 0.34%   |
| 501-1000       | 1         | 0.34%   |
| 91-100         | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 106       | 36.81%  |
| 121-160       | 85        | 29.51%  |
| 101-120       | 75        | 26.04%  |
| Unknown       | 12        | 4.17%   |
| More than 240 | 4         | 1.39%   |
| 161-240       | 4         | 1.39%   |
| 1-50          | 2         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 238       | 84.1%   |
| 2     | 32        | 11.31%  |
| 0     | 8         | 2.83%   |
| 3     | 5         | 1.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 150       | 37.22%  |
| Intel                             | 138       | 34.24%  |
| Qualcomm Atheros                  | 39        | 9.68%   |
| Broadcom                          | 23        | 5.71%   |
| Ralink Technology                 | 5         | 1.24%   |
| MediaTek                          | 4         | 0.99%   |
| Nvidia                            | 3         | 0.74%   |
| Marvell Technology Group          | 3         | 0.74%   |
| Huawei Technologies               | 3         | 0.74%   |
| TP-Link                           | 2         | 0.5%    |
| Sierra Wireless                   | 2         | 0.5%    |
| Samsung Electronics               | 2         | 0.5%    |
| Ralink                            | 2         | 0.5%    |
| Qualcomm Atheros Communications   | 2         | 0.5%    |
| Microchip Technology              | 2         | 0.5%    |
| Insyde Software                   | 2         | 0.5%    |
| Hewlett-Packard                   | 2         | 0.5%    |
| Dell                              | 2         | 0.5%    |
| D-Link System                     | 2         | 0.5%    |
| Broadcom Limited                  | 2         | 0.5%    |
| Aquantia                          | 2         | 0.5%    |
| Xiaomi                            | 1         | 0.25%   |
| TRENDnet                          | 1         | 0.25%   |
| Qualcomm                          | 1         | 0.25%   |
| NetGear                           | 1         | 0.25%   |
| Microsoft                         | 1         | 0.25%   |
| LG Electronics                    | 1         | 0.25%   |
| Ericsson Business Mobile Networks | 1         | 0.25%   |
| D-Link                            | 1         | 0.25%   |
| BUFFALO                           | 1         | 0.25%   |
| Attansic Technology               | 1         | 0.25%   |
| Apple                             | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 21.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 2.71%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.88%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.67%   |
| Intel Wireless 8260                                               | 8         | 1.67%   |
| Intel Wireless 3165                                               | 7         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.25%   |
| Intel Wireless 7265                                               | 6         | 1.25%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.25%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.83%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.83%   |
| Intel Wireless 7260                                               | 4         | 0.83%   |
| Intel Wireless 3160                                               | 4         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 3         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.63%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 43.64%  |
| Realtek Semiconductor           | 49        | 22.27%  |
| Qualcomm Atheros                | 36        | 16.36%  |
| Broadcom                        | 13        | 5.91%   |
| Ralink Technology               | 5         | 2.27%   |
| MediaTek                        | 4         | 1.82%   |
| Sierra Wireless                 | 2         | 0.91%   |
| Ralink                          | 2         | 0.91%   |
| Qualcomm Atheros Communications | 2         | 0.91%   |
| Dell                            | 2         | 0.91%   |
| TRENDnet                        | 1         | 0.45%   |
| TP-Link                         | 1         | 0.45%   |
| Qualcomm                        | 1         | 0.45%   |
| NetGear                         | 1         | 0.45%   |
| Microsoft                       | 1         | 0.45%   |
| Marvell Technology Group        | 1         | 0.45%   |
| D-Link System                   | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |
| BUFFALO                         | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 12        | 5.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 4.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 4.04%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 4.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 3.59%   |
| Intel Wireless 8260                                            | 8         | 3.59%   |
| Intel Wireless 3165                                            | 7         | 3.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.69%   |
| Intel Wireless 7265                                            | 6         | 2.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.69%   |
| Intel Wireless 8265 / 8275                                     | 5         | 2.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 2.24%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.79%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.79%   |
| Intel Wireless 7260                                            | 4         | 1.79%   |
| Intel Wireless 3160                                            | 4         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 1.35%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.35%   |
| Sierra Wireless EM7455                                         | 2         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.9%    |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                         | 2         | 0.9%    |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.9%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 132       | 52.59%  |
| Intel                    | 76        | 30.28%  |
| Broadcom                 | 11        | 4.38%   |
| Qualcomm Atheros         | 7         | 2.79%   |
| Nvidia                   | 3         | 1.2%    |
| Huawei Technologies      | 3         | 1.2%    |
| Samsung Electronics      | 2         | 0.8%    |
| Marvell Technology Group | 2         | 0.8%    |
| Insyde Software          | 2         | 0.8%    |
| Hewlett-Packard          | 2         | 0.8%    |
| Broadcom Limited         | 2         | 0.8%    |
| Aquantia                 | 2         | 0.8%    |
| Xiaomi                   | 1         | 0.4%    |
| TP-Link                  | 1         | 0.4%    |
| Microchip Technology     | 1         | 0.4%    |
| LG Electronics           | 1         | 0.4%    |
| D-Link System            | 1         | 0.4%    |
| Attansic Technology      | 1         | 0.4%    |
| Apple                    | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 39.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 7.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 5.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.35%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.35%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.57%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.57%   |
| Nvidia MCP61 Ethernet                                             | 3         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.18%   |
| Huawei STK-L21                                                    | 3         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.78%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.78%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.78%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2         | 0.78%   |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.78%   |
| Aquantia Ethernet controller                                      | 2         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.39%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.39%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 233       | 52.83%  |
| WiFi     | 206       | 46.71%  |
| Modem    | 2         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 58.74%  |
| Ethernet | 118       | 41.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 149       | 52.65%  |
| 1     | 116       | 40.99%  |
| 0     | 13        | 4.59%   |
| 3     | 4         | 1.41%   |
| 4     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 65.51%  |
| Yes  | 99        | 34.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 46.84%  |
| Realtek Semiconductor           | 19        | 12.03%  |
| Cambridge Silicon Radio         | 11        | 6.96%   |
| Broadcom                        | 11        | 6.96%   |
| Lite-On Technology              | 8         | 5.06%   |
| Foxconn / Hon Hai               | 7         | 4.43%   |
| IMC Networks                    | 6         | 3.8%    |
| Qualcomm Atheros Communications | 5         | 3.16%   |
| Realtek                         | 3         | 1.9%    |
| Apple                           | 3         | 1.9%    |
| Hewlett-Packard                 | 2         | 1.27%   |
| Toshiba                         | 1         | 0.63%   |
| Ralink                          | 1         | 0.63%   |
| Marvell Semiconductor           | 1         | 0.63%   |
| Fujitsu                         | 1         | 0.63%   |
| Foxconn International           | 1         | 0.63%   |
| Dell                            | 1         | 0.63%   |
| Chicony Electronics             | 1         | 0.63%   |
| ASUSTek Computer                | 1         | 0.63%   |
| Alps Electric                   | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 33        | 20.89%  |
| Intel AX201 Bluetooth                                                               | 16        | 10.13%  |
| Realtek Bluetooth Radio                                                             | 14        | 8.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 6.96%   |
| Intel AX200 Bluetooth                                                               | 9         | 5.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 3.8%    |
| Intel AX210 Bluetooth                                                               | 5         | 3.16%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.53%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2.53%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.53%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.9%    |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.27%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.27%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.63%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.63%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.63%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.63%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.63%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.63%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.63%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.63%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.63%   |
| Fujitsu Bluetooth Device                                                            | 1         | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.63%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 202       | 56.74%  |
| AMD                         | 71        | 19.94%  |
| Nvidia                      | 54        | 15.17%  |
| C-Media Electronics         | 4         | 1.12%   |
| Texas Instruments           | 3         | 0.84%   |
| SAVITECH                    | 2         | 0.56%   |
| JMTek                       | 2         | 0.56%   |
| Generalplus Technology      | 2         | 0.56%   |
| ASUSTek Computer            | 2         | 0.56%   |
| VIA Technologies            | 1         | 0.28%   |
| Trust International         | 1         | 0.28%   |
| Tenx Technology             | 1         | 0.28%   |
| Samson Technologies         | 1         | 0.28%   |
| Plantronics                 | 1         | 0.28%   |
| Medeli Electronics          | 1         | 0.28%   |
| MAG Technology              | 1         | 0.28%   |
| Logitech                    | 1         | 0.28%   |
| Lenovo                      | 1         | 0.28%   |
| Kingston Technology         | 1         | 0.28%   |
| GN Netcom                   | 1         | 0.28%   |
| FiiO Electronics Technology | 1         | 0.28%   |
| Creative Labs               | 1         | 0.28%   |
| Corsair                     | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 5.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 4.31%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 3.59%   |
| AMD FCH Azalia Controller                                                                         | 14        | 3.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 3.11%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 3.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 2.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 2.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 1.91%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.44%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.44%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 5         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 0.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.72%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.72%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.72%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 57        | 24.36%  |
| Unknown                    | 41        | 17.52%  |
| SK hynix                   | 32        | 13.68%  |
| Kingston                   | 25        | 10.68%  |
| Micron Technology          | 22        | 9.4%    |
| Crucial                    | 18        | 7.69%   |
| Unknown (ABCD)             | 7         | 2.99%   |
| Ramaxel Technology         | 6         | 2.56%   |
| G.Skill                    | 5         | 2.14%   |
| Corsair                    | 5         | 2.14%   |
| Smart                      | 2         | 0.85%   |
| Nanya Technology           | 2         | 0.85%   |
| Elpida                     | 2         | 0.85%   |
| Unknown                    | 2         | 0.85%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.43%   |
| Transcend                  | 1         | 0.43%   |
| Qimonda                    | 1         | 0.43%   |
| GLOWAY                     | 1         | 0.43%   |
| Foxline                    | 1         | 0.43%   |
| fef5                       | 1         | 0.43%   |
| Essencore                  | 1         | 0.43%   |
| ASint Technology           | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.05%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 3         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.23%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 0.82%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                    | 2         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.82%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.82%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                       | 2         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.82%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s             | 2         | 0.82%   |
| Unknown                                                          | 2         | 0.82%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.41%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 41.87%  |
| DDR3    | 73        | 35.96%  |
| LPDDR4  | 18        | 8.87%   |
| DDR2    | 10        | 4.93%   |
| Unknown | 6         | 2.96%   |
| LPDDR3  | 5         | 2.46%   |
| SDRAM   | 4         | 1.97%   |
| DDR5    | 1         | 0.49%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 112       | 54.9%   |
| DIMM         | 71        | 34.8%   |
| Row Of Chips | 16        | 7.84%   |
| Chip         | 3         | 1.47%   |
| Unknown      | 2         | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 72        | 33.49%  |
| 4096  | 67        | 31.16%  |
| 2048  | 37        | 17.21%  |
| 16384 | 23        | 10.7%   |
| 1024  | 10        | 4.65%   |
| 32768 | 4         | 1.86%   |
| 65536 | 1         | 0.47%   |
| 1536  | 1         | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 23.36%  |
| 3200    | 34        | 15.89%  |
| 2667    | 25        | 11.68%  |
| 2400    | 19        | 8.88%   |
| 1333    | 15        | 7.01%   |
| 2133    | 11        | 5.14%   |
| 667     | 8         | 3.74%   |
| 4267    | 5         | 2.34%   |
| 1334    | 5         | 2.34%   |
| 3600    | 4         | 1.87%   |
| 1066    | 4         | 1.87%   |
| Unknown | 4         | 1.87%   |
| 3000    | 3         | 1.4%    |
| 2666    | 3         | 1.4%    |
| 1067    | 3         | 1.4%    |
| 3266    | 2         | 0.93%   |
| 1867    | 2         | 0.93%   |
| 800     | 2         | 0.93%   |
| 4800    | 1         | 0.47%   |
| 4266    | 1         | 0.47%   |
| 4199    | 1         | 0.47%   |
| 3733    | 1         | 0.47%   |
| 3466    | 1         | 0.47%   |
| 3400    | 1         | 0.47%   |
| 3020    | 1         | 0.47%   |
| 2800    | 1         | 0.47%   |
| 2134    | 1         | 0.47%   |
| 2000    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 1800    | 1         | 0.47%   |
| 1776    | 1         | 0.47%   |
| 1648    | 1         | 0.47%   |
| 533     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


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

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson GT-9800F [Perfection 3200] | 1         | 50%     |
| Canon CanoScan LiDE 100                | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 43        | 24.02%  |
| Realtek Semiconductor                  | 15        | 8.38%   |
| Quanta                                 | 14        | 7.82%   |
| Microdia                               | 14        | 7.82%   |
| IMC Networks                           | 11        | 6.15%   |
| Suyin                                  | 10        | 5.59%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.59%   |
| Sunplus Innovation Technology          | 8         | 4.47%   |
| Acer                                   | 7         | 3.91%   |
| Logitech                               | 6         | 3.35%   |
| Z-Star Microelectronics                | 3         | 1.68%   |
| Microsoft                              | 3         | 1.68%   |
| Luxvisions Innotech Limited            | 3         | 1.68%   |
| Lite-On Technology                     | 3         | 1.68%   |
| Apple                                  | 3         | 1.68%   |
| Alcor Micro                            | 3         | 1.68%   |
| USB Camera                             | 2         | 1.12%   |
| Silicon Motion                         | 2         | 1.12%   |
| Ricoh                                  | 2         | 1.12%   |
| Xiongmai                               | 1         | 0.56%   |
| Xiaomi                                 | 1         | 0.56%   |
| USB Camera CS                          | 1         | 0.56%   |
| Syntek                                 | 1         | 0.56%   |
| SunplusIT                              | 1         | 0.56%   |
| Sunplus Technology                     | 1         | 0.56%   |
| Sonix Technology                       | 1         | 0.56%   |
| Samsung Electronics                    | 1         | 0.56%   |
| Primax Electronics                     | 1         | 0.56%   |
| OYT Tech                               | 1         | 0.56%   |
| OmniVision Technologies                | 1         | 0.56%   |
| MacroSilicon                           | 1         | 0.56%   |
| Lenovo                                 | 1         | 0.56%   |
| KYE Systems (Mouse Systems)            | 1         | 0.56%   |
| Importek                               | 1         | 0.56%   |
| Guillemot                              | 1         | 0.56%   |
| Creative Technology                    | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 14        | 7.78%   |
| Realtek USB Camera                                  | 4         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.22%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.67%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 1.67%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.67%   |
| Quanta HD User Facing                               | 3         | 1.67%   |
| Microdia Sonix USB 2.0 Camera                       | 3         | 1.67%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.67%   |
| Acer Integrated Camera                              | 3         | 1.67%   |
| USB Camera USB Camera                               | 2         | 1.11%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 1.11%   |
| Realtek HP Truevision HD                            | 2         | 1.11%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 1.11%   |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 1.11%   |
| Quanta HP Webcam                                    | 2         | 1.11%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.11%   |
| Microdia Webcam Vitade AF                           | 2         | 1.11%   |
| Microdia Lenovo EasyCamera                          | 2         | 1.11%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.11%   |
| Logitech BRIO Ultra HD Webcam                       | 2         | 1.11%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 1.11%   |
| IMC Networks Integrated Camera                      | 2         | 1.11%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.11%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.11%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 1.11%   |
| Chicony HP Truevision HD                            | 2         | 1.11%   |
| Chicony HD WebCam                                   | 2         | 1.11%   |
| Chicony EasyCamera                                  | 2         | 1.11%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 1.11%   |
| Z-Star Vimicro USB Camera (Altair)                  | 1         | 0.56%   |
| Z-Star Traveler TV 6500 SF Dia-scanner              | 1         | 0.56%   |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 0.56%   |
| Xiongmai web camera                                 | 1         | 0.56%   |
| Xiaomi Mi/Redmi series (PTP)                        | 1         | 0.56%   |
| USB Camera CS USB Camera CS                         | 1         | 0.56%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.56%   |
| Suyin Webcam-101                                    | 1         | 0.56%   |
| Suyin VGA Webcam                                    | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 40%     |
| Shenzhen Goodix Technology | 5         | 20%     |
| Upek                       | 4         | 16%     |
| Synaptics                  | 3         | 12%     |
| STMicroelectronics         | 2         | 8%      |
| Elan Microelectronics      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 4         | 16%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 12%     |
| Shenzhen Goodix  Fingerprint Device                    | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 8%      |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 8%      |
| Validity Sensors Synaptics WBDI                        | 2         | 8%      |
| STMicroelectronics Fingerprint Reader                  | 2         | 8%      |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 8%      |
| Upek TCS5B Fingerprint sensor                          | 1         | 4%      |
| Synaptics  WBDI                                        | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4%      |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4%      |
| Elan ELAN:Fingerprint                                  | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 7         | 41.18%  |
| Alcor Micro              | 5         | 29.41%  |
| Lenovo                   | 2         | 11.76%  |
| Reiner SCT Kartensysteme | 1         | 5.88%   |
| O2 Micro                 | 1         | 5.88%   |
| In Focus Systems         | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 5         | 29.41%  |
| Broadcom 58200                                 | 3         | 17.65%  |
| Lenovo Integrated Smart Card Reader            | 2         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 11.76%  |
| Broadcom 5880                                  | 2         | 11.76%  |
| Reiner SCT Kartensysteme cyberJack one         | 1         | 5.88%   |
| O2 Micro Oz776 SmartCard Reader                | 1         | 5.88%   |
| In Focus Systems EMV Smartcard Reader          | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 207       | 72.63%  |
| 1     | 63        | 22.11%  |
| 2     | 13        | 4.56%   |
| 5     | 1         | 0.35%   |
| 3     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 26.67%  |
| Chipcard                 | 17        | 18.89%  |
| Graphics card            | 16        | 17.78%  |
| Camera                   | 8         | 8.89%   |
| Net/wireless             | 7         | 7.78%   |
| Multimedia controller    | 5         | 5.56%   |
| Unassigned class         | 3         | 3.33%   |
| Network                  | 3         | 3.33%   |
| Bluetooth                | 3         | 3.33%   |
| Card reader              | 2         | 2.22%   |
| Sound                    | 1         | 1.11%   |
| Communication controller | 1         | 1.11%   |

