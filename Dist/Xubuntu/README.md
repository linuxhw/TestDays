Xubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Xubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu/Desktop/README.md) and [notebooks](/Dist/Xubuntu/Notebook/README.md).

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

Total: 5702

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| TrekStor      | Primebook C11B              | Convertible | [e96819bd00](https://linux-hardware.org/?probe=e96819bd00) | Dec 31, 2022 |
| Dell          | Latitude E5440              | Notebook    | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [3548fd618d](https://linux-hardware.org/?probe=3548fd618d) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9bfeb5727a](https://linux-hardware.org/?probe=9bfeb5727a) | Dec 26, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | Desktop     | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Khadas        | VIM2                        | Soc         | [2ead7fb94b](https://linux-hardware.org/?probe=2ead7fb94b) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | Notebook    | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Clevo         | P170EM                      | Notebook    | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | Notebook    | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [3dc25592eb](https://linux-hardware.org/?probe=3dc25592eb) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [7f18d05353](https://linux-hardware.org/?probe=7f18d05353) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | Notebook    | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8862992776](https://linux-hardware.org/?probe=8862992776) | Dec 20, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [52b5b53173](https://linux-hardware.org/?probe=52b5b53173) | Dec 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [64972eb902](https://linux-hardware.org/?probe=64972eb902) | Dec 19, 2022 |
| Sony          | VPCS12V9E                   | Notebook    | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | Notebook    | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| Lenovo        | FLEX-14IWL Laptop 81SQ      | Convertible | [f64e5ab064](https://linux-hardware.org/?probe=f64e5ab064) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fdb9e278dd](https://linux-hardware.org/?probe=fdb9e278dd) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | Notebook    | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| ECS           | CMPC                        | Notebook    | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [282ef194e5](https://linux-hardware.org/?probe=282ef194e5) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [51acd303f0](https://linux-hardware.org/?probe=51acd303f0) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [d65a8640af](https://linux-hardware.org/?probe=d65a8640af) | Dec 11, 2022 |
| HP            | 1497                        | Desktop     | [475049bb79](https://linux-hardware.org/?probe=475049bb79) | Dec 10, 2022 |
| Fusion5       | Lapbook T90B                | Notebook    | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7968282240](https://linux-hardware.org/?probe=7968282240) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ce802653d4](https://linux-hardware.org/?probe=ce802653d4) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| HP            | 2B34                        | Desktop     | [18ec4a2e66](https://linux-hardware.org/?probe=18ec4a2e66) | Dec 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [db5a886817](https://linux-hardware.org/?probe=db5a886817) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [bd30397e24](https://linux-hardware.org/?probe=bd30397e24) | Nov 29, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3b4f834c63](https://linux-hardware.org/?probe=3b4f834c63) | Nov 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [dfc381d411](https://linux-hardware.org/?probe=dfc381d411) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | Notebook    | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | Notebook    | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | Notebook    | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| sunxi         | LeMaker Banana Pi           | Soc         | [56f65f30b3](https://linux-hardware.org/?probe=56f65f30b3) | Nov 24, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [199ed733ad](https://linux-hardware.org/?probe=199ed733ad) | Nov 24, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| Positivo      | Mobile                      | Notebook    | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [8eb4e40bf5](https://linux-hardware.org/?probe=8eb4e40bf5) | Nov 22, 2022 |
| Supermicro    | M12SWA-TF                   | Server      | [b1e3f41ed1](https://linux-hardware.org/?probe=b1e3f41ed1) | Nov 22, 2022 |
| Intel         | AB2L .A004                  | Mini pc     | [6124722e1f](https://linux-hardware.org/?probe=6124722e1f) | Nov 22, 2022 |
| HP            | 8540w                       | Notebook    | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | Notebook    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | Notebook    | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [8ff2384625](https://linux-hardware.org/?probe=8ff2384625) | Nov 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [c9a4863d1f](https://linux-hardware.org/?probe=c9a4863d1f) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| HP            | 1495                        | Desktop     | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | Notebook    | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [b042e75495](https://linux-hardware.org/?probe=b042e75495) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [38f39ebccd](https://linux-hardware.org/?probe=38f39ebccd) | Nov 11, 2022 |
| VIT           | Aptio CRB                   | Mini pc     | [d3bbc5ba4f](https://linux-hardware.org/?probe=d3bbc5ba4f) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | Notebook    | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [ac93b84c08](https://linux-hardware.org/?probe=ac93b84c08) | Nov 10, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [27af8e61c5](https://linux-hardware.org/?probe=27af8e61c5) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | Desktop     | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Dell          | 06FW8M A03                  | Server      | [2d4eead63b](https://linux-hardware.org/?probe=2d4eead63b) | Nov 08, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [70ba1bf558](https://linux-hardware.org/?probe=70ba1bf558) | Nov 08, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | Notebook    | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | Notebook    | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | Desktop     | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2bf5248261](https://linux-hardware.org/?probe=2bf5248261) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | Desktop     | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | Notebook    | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| HP            | 8054                        | Desktop     | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| ASUSTek       | P8H61-M LX PLUS R2.0        | Desktop     | [423d3158cd](https://linux-hardware.org/?probe=423d3158cd) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | Notebook    | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [37f3d75177](https://linux-hardware.org/?probe=37f3d75177) | Oct 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [8fad928e72](https://linux-hardware.org/?probe=8fad928e72) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | Desktop     | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | Notebook    | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| MSI           | A320M PRO-VH                | Desktop     | [5f1aeaf170](https://linux-hardware.org/?probe=5f1aeaf170) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Dell          | 500                         | Notebook    | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | MS-7309                     | Desktop     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Samsung       | NC10                        | Notebook    | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Lenovo        | ThinkCentre M58 7373A5G     | Desktop     | [ed6ebf5f98](https://linux-hardware.org/?probe=ed6ebf5f98) | Oct 16, 2022 |
| HP            | 198E                        | Desktop     | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [3598f82c1e](https://linux-hardware.org/?probe=3598f82c1e) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6580d55237](https://linux-hardware.org/?probe=6580d55237) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| HP            | 1589                        | Desktop     | [d50afd3db1](https://linux-hardware.org/?probe=d50afd3db1) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | Notebook    | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | Notebook    | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | Notebook    | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fc4e415fe4](https://linux-hardware.org/?probe=fc4e415fe4) | Oct 02, 2022 |
| Dell          | 500                         | Notebook    | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| Gigabyte      | H81M-D2W                    | Desktop     | [467845e1c1](https://linux-hardware.org/?probe=467845e1c1) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| ASRock        | 775Dual-VSTA                | Desktop     | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | Desktop     | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Nvidia        | Tegra                       | Soc         | [bf3fee013b](https://linux-hardware.org/?probe=bf3fee013b) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [31fdd16d2f](https://linux-hardware.org/?probe=31fdd16d2f) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [24647846ee](https://linux-hardware.org/?probe=24647846ee) | Sep 06, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
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
| HP            | 844C                        | Desktop     | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [3f06afc812](https://linux-hardware.org/?probe=3f06afc812) | Aug 21, 2022 |
| Acer          | Unknown                     | Notebook    | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | Notebook    | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c4336ae88d](https://linux-hardware.org/?probe=c4336ae88d) | Aug 17, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| Dell          | 0RY007                      | Desktop     | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | Notebook    | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Dell          | 0RY007                      | Desktop     | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Dell          | 0RY007                      | Desktop     | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| eMachines     | EL1358G                     | Desktop     | [eebc968f87](https://linux-hardware.org/?probe=eebc968f87) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | Notebook    | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | Notebook    | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| Alienware     | 17 R4                       | Notebook    | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| LG Electro... | LE50-5BC6H1                 | Notebook    | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cc16c01563](https://linux-hardware.org/?probe=cc16c01563) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b841f9332](https://linux-hardware.org/?probe=9b841f9332) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| Toshiba       | NB205                       | Notebook    | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | P4B-M                       | Desktop     | [a193b562fa](https://linux-hardware.org/?probe=a193b562fa) | Jul 22, 2022 |
| ASUSTek       | P4B-M                       | Desktop     | [5128fcd55d](https://linux-hardware.org/?probe=5128fcd55d) | Jul 22, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | Notebook    | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | Notebook    | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | Notebook    | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | 1496                        | Desktop     | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [8a5a5a0987](https://linux-hardware.org/?probe=8a5a5a0987) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| Toshiba       | NB205                       | Notebook    | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Dell          | 07T4MC A02                  | Desktop     | [88de707c31](https://linux-hardware.org/?probe=88de707c31) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | Notebook    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | Notebook    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| Dell          | 500                         | Notebook    | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | Notebook    | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | Notebook    | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [47cddfb141](https://linux-hardware.org/?probe=47cddfb141) | Jun 25, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [ad5514340b](https://linux-hardware.org/?probe=ad5514340b) | Jun 25, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [5e9cdd75c7](https://linux-hardware.org/?probe=5e9cdd75c7) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | Notebook    | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Intel         | D102GGC2 AAD42789-204       | Desktop     | [3ed07edb6a](https://linux-hardware.org/?probe=3ed07edb6a) | Jun 21, 2022 |
| HP            | 15                          | Notebook    | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [fc761acd97](https://linux-hardware.org/?probe=fc761acd97) | Jun 18, 2022 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [89d99d840f](https://linux-hardware.org/?probe=89d99d840f) | Jun 17, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | Desktop     | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | Notebook    | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | Notebook    | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [535126df2b](https://linux-hardware.org/?probe=535126df2b) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | Notebook    | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | Notebook    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [5eaef9db5a](https://linux-hardware.org/?probe=5eaef9db5a) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [0ce0f27bac](https://linux-hardware.org/?probe=0ce0f27bac) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | Notebook    | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Unknown       | Unknown                     | Soc         | [0c5a37efd2](https://linux-hardware.org/?probe=0c5a37efd2) | Jun 05, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [63b4cd5c56](https://linux-hardware.org/?probe=63b4cd5c56) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | Notebook    | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| HP            | 3397                        | Desktop     | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | Notebook    | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| Medion        | E15407                      | Notebook    | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | Notebook    | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| HP            | 2B29                        | Desktop     | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Notebook    | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| HP            | 1497                        | Desktop     | [4b9a65b621](https://linux-hardware.org/?probe=4b9a65b621) | May 23, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| ASUSTek       | X510UA                      | Notebook    | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | Notebook    | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | Notebook    | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | Notebook    | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| IBM           | ThinkPad T43 2668F5G        | Notebook    | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | Notebook    | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | Notebook    | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| Dell          | Latitude E6410              | Notebook    | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | Notebook    | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [2df08f807d](https://linux-hardware.org/?probe=2df08f807d) | May 15, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | A7K                         | Notebook    | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | Notebook    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Gigabyte      | X48-DS5                     | Desktop     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [6dbe28a107](https://linux-hardware.org/?probe=6dbe28a107) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| HP            | 09F8h                       | Desktop     | [5042a34dcd](https://linux-hardware.org/?probe=5042a34dcd) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | Notebook    | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| eMachines     | MCP61PM-GM                  | Desktop     | [16c4522843](https://linux-hardware.org/?probe=16c4522843) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | Notebook    | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [4df90e6250](https://linux-hardware.org/?probe=4df90e6250) | Apr 18, 2022 |
| HP            | 18E5                        | Desktop     | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | Notebook    | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [521cf503e2](https://linux-hardware.org/?probe=521cf503e2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| HP            | Compaq 6730s                | Notebook    | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | Notebook    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | Notebook    | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | Notebook    | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0123ade8f7](https://linux-hardware.org/?probe=0123ade8f7) | Apr 13, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fe40f7c199](https://linux-hardware.org/?probe=fe40f7c199) | Apr 13, 2022 |
| Dell          | Precision 7550              | Notebook    | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | Notebook    | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [6280e20fbe](https://linux-hardware.org/?probe=6280e20fbe) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [14ae36ec3e](https://linux-hardware.org/?probe=14ae36ec3e) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Toshiba       | NB505                       | Notebook    | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Dell          | Latitude 5521               | Notebook    | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | MXG061                      | Notebook    | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [1f1a2dbacc](https://linux-hardware.org/?probe=1f1a2dbacc) | Apr 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [c081f43e18](https://linux-hardware.org/?probe=c081f43e18) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [0a0a02bac3](https://linux-hardware.org/?probe=0a0a02bac3) | Apr 04, 2022 |
| Wortmann      | M7x0S                       | Notebook    | [364f9cbe89](https://linux-hardware.org/?probe=364f9cbe89) | Apr 03, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | Notebook    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | Desktop     | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Dell          | 0WM839 A00                  | All in one  | [b5edf6760d](https://linux-hardware.org/?probe=b5edf6760d) | Apr 02, 2022 |
| Shuttle       | FH61V                       | Desktop     | [05c1b046da](https://linux-hardware.org/?probe=05c1b046da) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [b89bd4d737](https://linux-hardware.org/?probe=b89bd4d737) | Apr 01, 2022 |
| Shuttle       | FH61V                       | Desktop     | [65009176b4](https://linux-hardware.org/?probe=65009176b4) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [d3f3139ac2](https://linux-hardware.org/?probe=d3f3139ac2) | Apr 01, 2022 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [647fd89862](https://linux-hardware.org/?probe=647fd89862) | Apr 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Acer          | Aspire one                  | Notebook    | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da62c7238d](https://linux-hardware.org/?probe=da62c7238d) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| HP            | 21B4 A01                    | Desktop     | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Lenovo        | 36FD SDK0J40709 WIN 3259... | All in one  | [75410d5871](https://linux-hardware.org/?probe=75410d5871) | Mar 27, 2022 |
| Toshiba       | NB505                       | Notebook    | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [d5a1c13ab1](https://linux-hardware.org/?probe=d5a1c13ab1) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| Pegatron      | Benicia                     | Desktop     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | Notebook    | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| Dell          | Latitude E6400              | Notebook    | [49b4e17d7a](https://linux-hardware.org/?probe=49b4e17d7a) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d755a1a962](https://linux-hardware.org/?probe=d755a1a962) | Mar 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2cfe733664](https://linux-hardware.org/?probe=2cfe733664) | Mar 22, 2022 |
| ASUSTek       | X501A                       | Notebook    | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | Desktop     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| Samsung       | R510/P510                   | Notebook    | [5ec1b197a4](https://linux-hardware.org/?probe=5ec1b197a4) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | Notebook    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [ec7dd9aba3](https://linux-hardware.org/?probe=ec7dd9aba3) | Mar 17, 2022 |
| Toshiba       | NB205                       | Notebook    | [ffef19b228](https://linux-hardware.org/?probe=ffef19b228) | Mar 17, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [97ebb0ca74](https://linux-hardware.org/?probe=97ebb0ca74) | Mar 16, 2022 |
| Teclast       | F15 Plus                    | Notebook    | [9d3b8151f2](https://linux-hardware.org/?probe=9d3b8151f2) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [69cae65bf4](https://linux-hardware.org/?probe=69cae65bf4) | Mar 16, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [db613d4f60](https://linux-hardware.org/?probe=db613d4f60) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | Notebook    | [67a1970f50](https://linux-hardware.org/?probe=67a1970f50) | Mar 16, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | Notebook    | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Acer          | Aspire X1920                | Desktop     | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| Gigabyte      | 8IPE775/-G                  | Desktop     | [7888ddbc2b](https://linux-hardware.org/?probe=7888ddbc2b) | Mar 13, 2022 |
| Dell          | 0RW199                      | Desktop     | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2c17897902](https://linux-hardware.org/?probe=2c17897902) | Mar 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Dell          | Latitude E6400              | Notebook    | [bcacefe427](https://linux-hardware.org/?probe=bcacefe427) | Mar 08, 2022 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [aa341bdff4](https://linux-hardware.org/?probe=aa341bdff4) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [10c87bed94](https://linux-hardware.org/?probe=10c87bed94) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [2b3ba9a762](https://linux-hardware.org/?probe=2b3ba9a762) | Mar 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [4e626b238b](https://linux-hardware.org/?probe=4e626b238b) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | Notebook    | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | Notebook    | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS0LW00    | Notebook    | [c781fc668f](https://linux-hardware.org/?probe=c781fc668f) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Dell          | 0Y958C A00                  | Desktop     | [e2abde1282](https://linux-hardware.org/?probe=e2abde1282) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | Notebook    | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| LG Electro... | 22V240 FAB3                 | All in one  | [23b20c26f2](https://linux-hardware.org/?probe=23b20c26f2) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| HP            | 15                          | Notebook    | [fa8d20b53f](https://linux-hardware.org/?probe=fa8d20b53f) | Feb 23, 2022 |
| MSI           | G41M-P25                    | Desktop     | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | Notebook    | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [e7013b772d](https://linux-hardware.org/?probe=e7013b772d) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | Notebook    | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| Gateway       | M-6307                      | Notebook    | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [2734c5a939](https://linux-hardware.org/?probe=2734c5a939) | Feb 19, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Fujitsu Si... | D1784 S26361-D1784          | Desktop     | [7baecb9fce](https://linux-hardware.org/?probe=7baecb9fce) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| ASUSTek       | A2D                         | Notebook    | [6fbba6195d](https://linux-hardware.org/?probe=6fbba6195d) | Feb 17, 2022 |
| Lenovo        | ThinkPad R500 2716A54       | Notebook    | [9aa87e9270](https://linux-hardware.org/?probe=9aa87e9270) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [354434e81d](https://linux-hardware.org/?probe=354434e81d) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| HP            | x2 210 G2                   | Tablet      | [6cab74e68a](https://linux-hardware.org/?probe=6cab74e68a) | Feb 14, 2022 |
| Sony          | VPCEB3E1E                   | Notebook    | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| Khadas        | VIM2                        | Soc         | [c3e2b43e74](https://linux-hardware.org/?probe=c3e2b43e74) | Feb 13, 2022 |
| Dell          | 0FH884                      | Desktop     | [bd2aa894cc](https://linux-hardware.org/?probe=bd2aa894cc) | Feb 13, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [33d5b7046b](https://linux-hardware.org/?probe=33d5b7046b) | Feb 13, 2022 |
| Samsung       | 900X1B                      | Notebook    | [c609dfc310](https://linux-hardware.org/?probe=c609dfc310) | Feb 13, 2022 |
| HP            | 3031h                       | Desktop     | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| HP            | ProBook 655 G1              | Notebook    | [1c6a5c6e55](https://linux-hardware.org/?probe=1c6a5c6e55) | Feb 11, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [d455b09330](https://linux-hardware.org/?probe=d455b09330) | Feb 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [935de1698b](https://linux-hardware.org/?probe=935de1698b) | Feb 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Xubuntu 20.04 | 1896      | 49.49%  |
| Xubuntu 18.04 | 1014      | 26.47%  |
| Xubuntu 22.04 | 283       | 7.39%   |
| Xubuntu 19.10 | 199       | 5.19%   |
| Xubuntu 21.10 | 96        | 2.51%   |
| Xubuntu 16.04 | 95        | 2.48%   |
| Xubuntu 20.10 | 93        | 2.43%   |
| Xubuntu 21.04 | 79        | 2.06%   |
| Xubuntu 19.04 | 26        | 0.68%   |
| Xubuntu 22.10 | 21        | 0.55%   |
| Xubuntu 18.10 | 11        | 0.29%   |
| Xubuntu 17.10 | 6         | 0.16%   |
| Xubuntu       | 6         | 0.16%   |
| Xubuntu 14.04 | 3         | 0.08%   |
| Xubuntu 17.04 | 2         | 0.05%   |
| Xubuntu 23.04 | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Xubuntu | 3707      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 155       | 3.54%   |
| 5.4.0-48-generic    | 65        | 1.49%   |
| 5.4.0-58-generic    | 60        | 1.37%   |
| 5.4.0-52-generic    | 59        | 1.35%   |
| 5.3.0-46-generic    | 59        | 1.35%   |
| 5.11.0-27-generic   | 50        | 1.14%   |
| 5.4.0-65-generic    | 48        | 1.1%    |
| 5.3.0-40-generic    | 48        | 1.1%    |
| 5.4.0-29-generic    | 46        | 1.05%   |
| 5.4.0-54-generic    | 45        | 1.03%   |
| 5.4.0-47-generic    | 42        | 0.96%   |
| 5.15.0-52-generic   | 42        | 0.96%   |
| 5.4.0-42-lowlatency | 40        | 0.91%   |
| 5.4.0-26-generic    | 38        | 0.87%   |
| 5.3.0-42-generic    | 38        | 0.87%   |
| 5.15.0-56-generic   | 38        | 0.87%   |
| 5.3.0-28-generic    | 36        | 0.82%   |
| 5.4.0-40-generic    | 35        | 0.8%    |
| 5.0.0-37-generic    | 35        | 0.8%    |
| 5.3.0-51-generic    | 34        | 0.78%   |
| 5.4.0-37-generic    | 33        | 0.75%   |
| 5.4.0-66-generic    | 31        | 0.71%   |
| 5.15.0-47-generic   | 31        | 0.71%   |
| 4.15.0-99-generic   | 31        | 0.71%   |
| 5.4.0-89-generic    | 30        | 0.69%   |
| 5.4.0-31-generic    | 30        | 0.69%   |
| 5.15.0-48-generic   | 30        | 0.69%   |
| 5.4.0-72-generic    | 28        | 0.64%   |
| 5.3.0-53-generic    | 28        | 0.64%   |
| 5.15.0-46-generic   | 28        | 0.64%   |
| 5.4.0-29-lowlatency | 27        | 0.62%   |
| 5.4.0-91-generic    | 26        | 0.59%   |
| 5.4.0-81-generic    | 26        | 0.59%   |
| 5.13.0-39-generic   | 26        | 0.59%   |
| 5.8.0-53-generic    | 25        | 0.57%   |
| 5.4.0-33-generic    | 25        | 0.57%   |
| 5.8.0-43-generic    | 24        | 0.55%   |
| 5.4.0-56-generic    | 24        | 0.55%   |
| 5.13.0-30-generic   | 24        | 0.55%   |
| 5.11.0-37-generic   | 24        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1553      | 39.78%  |
| 4.15.0  | 471       | 12.06%  |
| 5.3.0   | 438       | 11.22%  |
| 5.15.0  | 309       | 7.91%   |
| 5.11.0  | 275       | 7.04%   |
| 5.8.0   | 255       | 6.53%   |
| 5.13.0  | 222       | 5.69%   |
| 5.0.0   | 107       | 2.74%   |
| 4.4.0   | 46        | 1.18%   |
| 4.18.0  | 25        | 0.64%   |
| 5.19.0  | 24        | 0.61%   |
| 5.17.0  | 10        | 0.26%   |
| 4.13.0  | 9         | 0.23%   |
| 4.10.0  | 6         | 0.15%   |
| 5.6.0   | 5         | 0.13%   |
| 5.14.0  | 5         | 0.13%   |
| 5.10.0  | 5         | 0.13%   |
| 5.9.8   | 3         | 0.08%   |
| 5.9.16  | 3         | 0.08%   |
| 5.18.0  | 3         | 0.08%   |
| 5.15.1  | 3         | 0.08%   |
| 5.11.16 | 3         | 0.08%   |
| 4.8.0   | 3         | 0.08%   |
| 6.0.9   | 2         | 0.05%   |
| 6.0.0   | 2         | 0.05%   |
| 5.9.0   | 2         | 0.05%   |
| 5.7.7   | 2         | 0.05%   |
| 5.7.6   | 2         | 0.05%   |
| 5.7.1   | 2         | 0.05%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.19  | 2         | 0.05%   |
| 5.5.19  | 2         | 0.05%   |
| 5.16.9  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.13.7  | 2         | 0.05%   |
| 5.12.12 | 2         | 0.05%   |
| 5.12.10 | 2         | 0.05%   |
| 5.11.6  | 2         | 0.05%   |
| 5.11.11 | 2         | 0.05%   |
| 4.9.253 | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1560      | 40%     |
| 4.15    | 471       | 12.08%  |
| 5.3     | 440       | 11.28%  |
| 5.15    | 320       | 8.21%   |
| 5.11    | 282       | 7.23%   |
| 5.8     | 260       | 6.67%   |
| 5.13    | 226       | 5.79%   |
| 5.0     | 109       | 2.79%   |
| 4.4     | 49        | 1.26%   |
| 5.19    | 27        | 0.69%   |
| 4.18    | 25        | 0.64%   |
| 5.10    | 15        | 0.38%   |
| 5.9     | 11        | 0.28%   |
| 5.17    | 11        | 0.28%   |
| 5.7     | 10        | 0.26%   |
| 5.14    | 10        | 0.26%   |
| 5.6     | 9         | 0.23%   |
| 4.13    | 9         | 0.23%   |
| 5.12    | 8         | 0.21%   |
| 4.19    | 7         | 0.18%   |
| 4.10    | 6         | 0.15%   |
| 6.0     | 5         | 0.13%   |
| 5.18    | 5         | 0.13%   |
| 5.16    | 5         | 0.13%   |
| 4.9     | 4         | 0.1%    |
| 5.5     | 3         | 0.08%   |
| 4.8     | 3         | 0.08%   |
| 5.2     | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.11    | 2         | 0.05%   |
| 6.1     | 1         | 0.03%   |
| 4.20    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3183      | 85.73%  |
| i686    | 493       | 13.28%  |
| aarch64 | 29        | 0.78%   |
| armv7l  | 8         | 0.22%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 3581      | 96.42%  |
| GNOME           | 92        | 2.48%   |
| i3              | 8         | 0.22%   |
| KDE5            | 7         | 0.19%   |
| Cinnamon        | 7         | 0.19%   |
| Unity           | 4         | 0.11%   |
| GNOME Flashback | 4         | 0.11%   |
| X-Cinnamon      | 2         | 0.05%   |
| MATE            | 2         | 0.05%   |
| LXQt            | 2         | 0.05%   |
| xmonad          | 1         | 0.03%   |
| ICEWM           | 1         | 0.03%   |
| GNUstep         | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |
| Unknown         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3645      | 98.25%  |
| Tty     | 45        | 1.21%   |
| Wayland | 15        | 0.4%    |
| Web     | 3         | 0.08%   |
| Unknown | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2074      | 54.19%  |
| LightDM | 1140      | 29.79%  |
| TDM     | 508       | 13.27%  |
| GDM     | 47        | 1.23%   |
| GDM3    | 45        | 1.18%   |
| SDDM    | 7         | 0.18%   |
| XDM     | 4         | 0.1%    |
| SLiM    | 1         | 0.03%   |
| NODM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1193      | 32.02%  |
| de_DE   | 384       | 10.31%  |
| fr_FR   | 322       | 8.64%   |
| it_IT   | 256       | 6.87%   |
| pt_BR   | 190       | 5.1%    |
| ru_RU   | 177       | 4.75%   |
| en_GB   | 138       | 3.7%    |
| C       | 130       | 3.49%   |
| es_ES   | 101       | 2.71%   |
| en_CA   | 86        | 2.31%   |
| Unknown | 81        | 2.17%   |
| en_AU   | 68        | 1.83%   |
| pl_PL   | 56        | 1.5%    |
| es_AR   | 40        | 1.07%   |
| nl_NL   | 37        | 0.99%   |
| hu_HU   | 37        | 0.99%   |
| ja_JP   | 35        | 0.94%   |
| cs_CZ   | 30        | 0.81%   |
| en_IN   | 22        | 0.59%   |
| es_MX   | 20        | 0.54%   |
| pt_PT   | 16        | 0.43%   |
| fr_BE   | 16        | 0.43%   |
| fi_FI   | 16        | 0.43%   |
| ru_UA   | 15        | 0.4%    |
| sv_SE   | 14        | 0.38%   |
| sk_SK   | 14        | 0.38%   |
| tr_TR   | 13        | 0.35%   |
| en_ZA   | 13        | 0.35%   |
| es_CO   | 12        | 0.32%   |
| el_GR   | 12        | 0.32%   |
| de_CH   | 12        | 0.32%   |
| de_AT   | 12        | 0.32%   |
| zh_TW   | 11        | 0.3%    |
| fr_CA   | 11        | 0.3%    |
| nl_BE   | 9         | 0.24%   |
| es_VE   | 9         | 0.24%   |
| zh_CN   | 8         | 0.21%   |
| ca_ES   | 7         | 0.19%   |
| bg_BG   | 7         | 0.19%   |
| es_PE   | 6         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2474      | 66.01%  |
| EFI  | 1274      | 33.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3414      | 91.82%  |
| Overlay | 149       | 4.01%   |
| Btrfs   | 63        | 1.69%   |
| Zfs     | 33        | 0.89%   |
| Unknown | 24        | 0.65%   |
| Xfs     | 15        | 0.4%    |
| Ext2    | 11        | 0.3%    |
| Ext3    | 7         | 0.19%   |
| Ufs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2464      | 65.78%  |
| GPT     | 825       | 22.02%  |
| MBR     | 457       | 12.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3153      | 83.35%  |
| Yes       | 630       | 16.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2490      | 65.96%  |
| Yes       | 1285      | 34.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 587       | 15.83%  |
| ASUSTek Computer        | 565       | 15.24%  |
| Dell                    | 451       | 12.17%  |
| Lenovo                  | 433       | 11.68%  |
| Acer                    | 249       | 6.72%   |
| Gigabyte Technology     | 207       | 5.58%   |
| MSI                     | 167       | 4.5%    |
| ASRock                  | 141       | 3.8%    |
| Toshiba                 | 96        | 2.59%   |
| Apple                   | 67        | 1.81%   |
| Intel                   | 63        | 1.7%    |
| Samsung Electronics     | 55        | 1.48%   |
| Sony                    | 46        | 1.24%   |
| Medion                  | 42        | 1.13%   |
| Unknown                 | 39        | 1.05%   |
| Fujitsu Siemens         | 30        | 0.81%   |
| Fujitsu                 | 30        | 0.81%   |
| ECS                     | 29        | 0.78%   |
| Packard Bell            | 26        | 0.7%    |
| Foxconn                 | 20        | 0.54%   |
| Positivo                | 16        | 0.43%   |
| Raspberry Pi Foundation | 15        | 0.4%    |
| Notebook                | 15        | 0.4%    |
| Google                  | 15        | 0.4%    |
| Clevo                   | 14        | 0.38%   |
| Pegatron                | 13        | 0.35%   |
| eMachines               | 13        | 0.35%   |
| IBM                     | 12        | 0.32%   |
| HUAWEI                  | 11        | 0.3%    |
| Supermicro              | 10        | 0.27%   |
| AMI                     | 9         | 0.24%   |
| LG Electronics          | 8         | 0.22%   |
| Gateway                 | 8         | 0.22%   |
| Biostar                 | 8         | 0.22%   |
| ZOTAC                   | 7         | 0.19%   |
| NEC Computers           | 6         | 0.16%   |
| GPU Company             | 6         | 0.16%   |
| Alienware               | 6         | 0.16%   |
| Semp Toshiba            | 5         | 0.13%   |
| OEM                     | 5         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 59        | 1.59%   |
| ASUS All Series                        | 25        | 0.67%   |
| HP Pavilion dv6                        | 17        | 0.46%   |
| HP Notebook                            | 17        | 0.46%   |
| Gigabyte H410M S2H                     | 15        | 0.4%    |
| Dell OptiPlex 7010                     | 15        | 0.4%    |
| Dell OptiPlex 755                      | 11        | 0.3%    |
| Dell Latitude D630                     | 11        | 0.3%    |
| HP 15                                  | 10        | 0.27%   |
| HP Pavilion 15                         | 9         | 0.24%   |
| ECS G31T-M9                            | 9         | 0.24%   |
| Dell Latitude E6430                    | 9         | 0.24%   |
| Dell OptiPlex 780                      | 8         | 0.22%   |
| Dell OptiPlex 760                      | 8         | 0.22%   |
| Dell OptiPlex 390                      | 8         | 0.22%   |
| ASRock N68C-S UCC                      | 8         | 0.22%   |
| HP Pavilion dv7                        | 7         | 0.19%   |
| HP Pavilion dv6500                     | 7         | 0.19%   |
| MSI MS-7C37                            | 6         | 0.16%   |
| HP Pavilion g6                         | 6         | 0.16%   |
| HP EliteDesk 800 G1 SFF                | 6         | 0.16%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.16%   |
| ASUS TUF Gaming X570-PLUS              | 6         | 0.16%   |
| MSI MS-7B89                            | 5         | 0.13%   |
| MSI MS-7B79                            | 5         | 0.13%   |
| MSI MS-7A38                            | 5         | 0.13%   |
| MSI MS-7721                            | 5         | 0.13%   |
| HP EliteBook 840 G3                    | 5         | 0.13%   |
| HP Compaq Elite 8300 SFF               | 5         | 0.13%   |
| HP Compaq dc7600 Small Form Factor     | 5         | 0.13%   |
| Dell OptiPlex GX620                    | 5         | 0.13%   |
| Dell OptiPlex 3020                     | 5         | 0.13%   |
| Dell Latitude E6520                    | 5         | 0.13%   |
| ASUS M5A78L-M/USB3                     | 5         | 0.13%   |
| ASUS 1005HA                            | 5         | 0.13%   |
| Acer Aspire one                        | 5         | 0.13%   |
| Acer AO751h                            | 5         | 0.13%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 4         | 0.11%   |
| RPi Raspberry Pi 4 Model B Rev 1.1     | 4         | 0.11%   |
| Positivo Mobile                        | 4         | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 214       | 5.77%   |
| Acer Aspire           | 157       | 4.24%   |
| Dell Inspiron         | 122       | 3.29%   |
| Dell Latitude         | 113       | 3.05%   |
| HP Pavilion           | 110       | 2.97%   |
| HP Compaq             | 107       | 2.89%   |
| Dell OptiPlex         | 94        | 2.54%   |
| Toshiba Satellite     | 81        | 2.19%   |
| Lenovo IdeaPad        | 64        | 1.73%   |
| Unknown               | 59        | 1.59%   |
| HP EliteBook          | 56        | 1.51%   |
| ASUS PRIME            | 44        | 1.19%   |
| HP ProBook            | 43        | 1.16%   |
| Lenovo ThinkCentre    | 39        | 1.05%   |
| HP Laptop             | 37        | 1%      |
| Dell Precision        | 35        | 0.94%   |
| ASUS VivoBook         | 33        | 0.89%   |
| ASUS All              | 25        | 0.67%   |
| ASUS TUF              | 20        | 0.54%   |
| Dell Vostro           | 19        | 0.51%   |
| HP Notebook           | 18        | 0.49%   |
| Dell XPS              | 18        | 0.49%   |
| HP ProDesk            | 17        | 0.46%   |
| Acer Veriton          | 16        | 0.43%   |
| Acer Extensa          | 16        | 0.43%   |
| RPi Raspberry         | 15        | 0.4%    |
| Gigabyte H410M        | 15        | 0.4%    |
| Fujitsu Siemens AMILO | 15        | 0.4%    |
| ASUS ROG              | 15        | 0.4%    |
| Packard Bell EasyNote | 14        | 0.38%   |
| HP EliteDesk          | 14        | 0.38%   |
| Dell PowerEdge        | 14        | 0.38%   |
| HP ENVY               | 13        | 0.35%   |
| Fujitsu LIFEBOOK      | 12        | 0.32%   |
| Dell Studio           | 12        | 0.32%   |
| HP Presario           | 11        | 0.3%    |
| HP Mini               | 11        | 0.3%    |
| HP 255                | 11        | 0.3%    |
| HP 15                 | 11        | 0.3%    |
| Fujitsu ESPRIMO       | 11        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 319       | 8.61%   |
| 2011    | 312       | 8.42%   |
| 2008    | 283       | 7.63%   |
| 2010    | 282       | 7.61%   |
| 2013    | 273       | 7.36%   |
| 2009    | 260       | 7.01%   |
| 2007    | 254       | 6.85%   |
| 2019    | 225       | 6.07%   |
| 2018    | 207       | 5.58%   |
| 2014    | 204       | 5.5%    |
| 2017    | 195       | 5.26%   |
| 2020    | 191       | 5.15%   |
| 2015    | 150       | 4.05%   |
| 2016    | 144       | 3.88%   |
| 2006    | 142       | 3.83%   |
| 2021    | 109       | 2.94%   |
| 2005    | 68        | 1.83%   |
| Unknown | 34        | 0.92%   |
| 2022    | 17        | 0.46%   |
| 2004    | 16        | 0.43%   |
| 2003    | 15        | 0.4%    |
| 2001    | 4         | 0.11%   |
| 2002    | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2025      | 54.63%  |
| Desktop        | 1475      | 39.79%  |
| Mini pc        | 47        | 1.27%   |
| All in one     | 41        | 1.11%   |
| Convertible    | 36        | 0.97%   |
| System on chip | 35        | 0.94%   |
| Server         | 31        | 0.84%   |
| Tablet         | 16        | 0.43%   |
| Firewall       | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3521      | 94.57%  |
| Enabled  | 202       | 5.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3691      | 99.57%  |
| Yes  | 16        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 998       | 26.51%  |
| 4.01-8.0        | 710       | 18.86%  |
| 8.01-16.0       | 507       | 13.47%  |
| 16.01-24.0      | 476       | 12.65%  |
| 1.01-2.0        | 460       | 12.22%  |
| 32.01-64.0      | 191       | 5.07%   |
| 0.51-1.0        | 146       | 3.88%   |
| 2.01-3.0        | 145       | 3.85%   |
| 64.01-256.0     | 75        | 1.99%   |
| 24.01-32.0      | 42        | 1.12%   |
| 0.01-0.5        | 12        | 0.32%   |
| More than 256.0 | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1734      | 42.27%  |
| 0.51-1.0   | 830       | 20.23%  |
| 2.01-3.0   | 730       | 17.8%   |
| 4.01-8.0   | 323       | 7.87%   |
| 3.01-4.0   | 261       | 6.36%   |
| 0.01-0.5   | 115       | 2.8%    |
| 8.01-16.0  | 89        | 2.17%   |
| 16.01-24.0 | 10        | 0.24%   |
| 24.01-32.0 | 7         | 0.17%   |
| 32.01-64.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2371      | 62.25%  |
| 2      | 910       | 23.89%  |
| 3      | 286       | 7.51%   |
| 4      | 111       | 2.91%   |
| 5      | 47        | 1.23%   |
| 0      | 44        | 1.16%   |
| 6      | 19        | 0.5%    |
| 7      | 12        | 0.32%   |
| 10     | 4         | 0.11%   |
| 8      | 3         | 0.08%   |
| 9      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1968      | 52.69%  |
| No        | 1767      | 47.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3377      | 91.05%  |
| No        | 332       | 8.95%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2679      | 71.73%  |
| No        | 1056      | 28.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2140      | 57.02%  |
| Yes       | 1613      | 42.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 582       | 15.62%  |
| Germany      | 465       | 12.48%  |
| France       | 338       | 9.07%   |
| Italy        | 285       | 7.65%   |
| Russia       | 227       | 6.09%   |
| Brazil       | 215       | 5.77%   |
| Canada       | 141       | 3.78%   |
| UK           | 139       | 3.73%   |
| Spain        | 120       | 3.22%   |
| Netherlands  | 90        | 2.42%   |
| Australia    | 77        | 2.07%   |
| Poland       | 68        | 1.83%   |
| Ukraine      | 54        | 1.45%   |
| Argentina    | 53        | 1.42%   |
| Belgium      | 48        | 1.29%   |
| Hungary      | 43        | 1.15%   |
| Czechia      | 42        | 1.13%   |
| Mexico       | 41        | 1.1%    |
| Japan        | 41        | 1.1%    |
| Finland      | 39        | 1.05%   |
| Sweden       | 38        | 1.02%   |
| Portugal     | 34        | 0.91%   |
| India        | 32        | 0.86%   |
| Greece       | 32        | 0.86%   |
| Indonesia    | 27        | 0.72%   |
| Bulgaria     | 25        | 0.67%   |
| Austria      | 24        | 0.64%   |
| Turkey       | 21        | 0.56%   |
| Romania      | 21        | 0.56%   |
| Slovakia     | 18        | 0.48%   |
| Switzerland  | 17        | 0.46%   |
| Iran         | 17        | 0.46%   |
| Taiwan       | 15        | 0.4%    |
| Norway       | 15        | 0.4%    |
| Colombia     | 15        | 0.4%    |
| South Africa | 13        | 0.35%   |
| Venezuela    | 12        | 0.32%   |
| Israel       | 12        | 0.32%   |
| Slovenia     | 10        | 0.27%   |
| Denmark      | 10        | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 49        | 1.25%   |
| Berlin            | 43        | 1.09%   |
| Moscow            | 39        | 0.99%   |
| Rome              | 33        | 0.84%   |
| Milan             | 31        | 0.79%   |
| Voronezh          | 28        | 0.71%   |
| Sao Paulo         | 25        | 0.64%   |
| Sydney            | 24        | 0.61%   |
| Amsterdam         | 23        | 0.58%   |
| Athens            | 22        | 0.56%   |
| Warsaw            | 21        | 0.53%   |
| Munich            | 21        | 0.53%   |
| Madrid            | 21        | 0.53%   |
| St Petersburg     | 20        | 0.51%   |
| Hamburg           | 20        | 0.51%   |
| Budapest          | 20        | 0.51%   |
| Québec           | 19        | 0.48%   |
| Rio de Janeiro    | 17        | 0.43%   |
| Helsinki          | 17        | 0.43%   |
| Genoa             | 16        | 0.41%   |
| Barcelona         | 16        | 0.41%   |
| Oryol             | 15        | 0.38%   |
| Montreal          | 15        | 0.38%   |
| Melbourne         | 15        | 0.38%   |
| Kyiv              | 15        | 0.38%   |
| Turin             | 13        | 0.33%   |
| Prague            | 13        | 0.33%   |
| Buenos Aires      | 13        | 0.33%   |
| Vancouver         | 12        | 0.31%   |
| Tehran            | 12        | 0.31%   |
| Sofia             | 12        | 0.31%   |
| Leipzig           | 12        | 0.31%   |
| Toronto           | 11        | 0.28%   |
| Frankfurt am Main | 11        | 0.28%   |
| Belo Horizonte    | 11        | 0.28%   |
| Yokohama          | 10        | 0.25%   |
| Vienna            | 10        | 0.25%   |
| Stuttgart         | 10        | 0.25%   |
| Lisbon            | 10        | 0.25%   |
| Cologne           | 10        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 936       | 1361   | 18.37%  |
| WDC                 | 878       | 1265   | 17.23%  |
| Samsung Electronics | 678       | 954    | 13.3%   |
| Toshiba             | 362       | 451    | 7.1%    |
| Hitachi             | 306       | 403    | 6%      |
| Unknown             | 247       | 312    | 4.85%   |
| Kingston            | 225       | 288    | 4.42%   |
| SanDisk             | 177       | 219    | 3.47%   |
| Crucial             | 136       | 182    | 2.67%   |
| HGST                | 104       | 121    | 2.04%   |
| Intel               | 93        | 134    | 1.82%   |
| SK hynix            | 77        | 89     | 1.51%   |
| A-DATA Technology   | 69        | 88     | 1.35%   |
| Fujitsu             | 66        | 83     | 1.3%    |
| Maxtor              | 59        | 84     | 1.16%   |
| China               | 52        | 62     | 1.02%   |
| Micron Technology   | 37        | 41     | 0.73%   |
| PNY                 | 33        | 43     | 0.65%   |
| Patriot             | 30        | 35     | 0.59%   |
| OCZ                 | 27        | 34     | 0.53%   |
| Transcend           | 26        | 28     | 0.51%   |
| Phison              | 24        | 36     | 0.47%   |
| Intenso             | 24        | 31     | 0.47%   |
| KIOXIA              | 18        | 23     | 0.35%   |
| Apple               | 18        | 26     | 0.35%   |
| SPCC                | 16        | 24     | 0.31%   |
| LITEON              | 16        | 18     | 0.31%   |
| Apacer              | 16        | 22     | 0.31%   |
| Silicon Motion      | 15        | 16     | 0.29%   |
| LITEONIT            | 15        | 18     | 0.29%   |
| Unknown             | 14        | 14     | 0.27%   |
| KingDian            | 12        | 18     | 0.24%   |
| ASMT                | 12        | 18     | 0.24%   |
| JMicron Technology  | 10        | 10     | 0.2%    |
| Hewlett-Packard     | 10        | 14     | 0.2%    |
| Lexar               | 9         | 9      | 0.18%   |
| KingSpec            | 8         | 10     | 0.16%   |
| USB3.0              | 7         | 10     | 0.14%   |
| Smartbuy            | 7         | 7      | 0.14%   |
| Plextor             | 7         | 8      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 64        | 1.15%   |
| Unknown MMC Card  32GB                 | 50        | 0.9%    |
| Seagate ST500DM002-1BD142 500GB        | 48        | 0.86%   |
| Samsung SSD 860 EVO 500GB              | 41        | 0.73%   |
| Kingston SA400S37480G 480GB SSD        | 37        | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 32        | 0.57%   |
| Samsung SSD 850 EVO 250GB              | 31        | 0.56%   |
| Unknown MMC Card  64GB                 | 30        | 0.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 30        | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB         | 30        | 0.54%   |
| Seagate ST500LT012-1DG142 500GB        | 29        | 0.52%   |
| Toshiba MQ01ABF050 500GB               | 27        | 0.48%   |
| Toshiba MQ01ABD100 1TB                 | 26        | 0.47%   |
| Samsung SSD 850 EVO 500GB              | 26        | 0.47%   |
| Seagate ST3500418AS 500GB              | 24        | 0.43%   |
| Kingston SA400S37120G 120GB SSD        | 24        | 0.43%   |
| Unknown SD/MMC/MS PRO 64GB             | 23        | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB         | 23        | 0.41%   |
| Toshiba DT01ACA100 1TB                 | 22        | 0.39%   |
| Seagate Expansion 4TB                  | 22        | 0.39%   |
| HGST HTS721010A9E630 1TB               | 21        | 0.38%   |
| HGST HTS541010A9E680 1TB               | 21        | 0.38%   |
| Seagate ST9500325AS 500GB              | 19        | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB         | 19        | 0.34%   |
| Unknown MMC Card  128GB                | 18        | 0.32%   |
| Seagate ST31000528AS 1TB               | 18        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB         | 18        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB         | 18        | 0.32%   |
| Samsung SSD 860 EVO 1TB                | 18        | 0.32%   |
| Unknown MMC Card  16GB                 | 17        | 0.3%    |
| Seagate ST500LT012-9WS142 500GB        | 17        | 0.3%    |
| Samsung SSD 860 EVO 250GB              | 17        | 0.3%    |
| Kingston SV300S37A120G 120GB SSD       | 17        | 0.3%    |
| WDC WD10JPVX-22JC3T0 1TB               | 16        | 0.29%   |
| Seagate ST9320325AS 320GB              | 16        | 0.29%   |
| Seagate ST4000DM004-2CV104 4TB         | 16        | 0.29%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 16        | 0.29%   |
| Hitachi HDS721010CLA332 1TB            | 16        | 0.29%   |
| Crucial CT240BX500SSD1 240GB           | 16        | 0.29%   |
| Seagate ST31000524AS 1TB               | 15        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 919       | 1334   | 32.88%  |
| WDC                 | 770       | 1106   | 27.55%  |
| Toshiba             | 307       | 386    | 10.98%  |
| Hitachi             | 306       | 403    | 10.95%  |
| Samsung Electronics | 184       | 258    | 6.58%   |
| HGST                | 104       | 121    | 3.72%   |
| Fujitsu             | 64        | 81     | 2.29%   |
| Maxtor              | 57        | 82     | 2.04%   |
| Unknown             | 24        | 26     | 0.86%   |
| ASMT                | 12        | 18     | 0.43%   |
| USB3.0              | 7         | 10     | 0.25%   |
| IBM/Hitachi         | 7         | 7      | 0.25%   |
| Intenso             | 5         | 6      | 0.18%   |
| Pioneer             | 3         | 3      | 0.11%   |
| Apple               | 3         | 4      | 0.11%   |
| WD MediaMax         | 2         | 2      | 0.07%   |
| PHD 3.0             | 2         | 2      | 0.07%   |
| Inateck             | 2         | 2      | 0.07%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| Hewlett-Packard     | 2         | 2      | 0.07%   |
| ExcelStor           | 2         | 2      | 0.07%   |
| Apricorn            | 2         | 3      | 0.07%   |
| SAGE                | 1         | 1      | 0.04%   |
| LaCie               | 1         | 4      | 0.04%   |
| ICY BOX             | 1         | 1      | 0.04%   |
| HPE                 | 1         | 4      | 0.04%   |
| Ext Hard            | 1         | 1      | 0.04%   |
| CLOVER              | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |
| ACASIS              | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 353       | 472    | 23.42%  |
| Kingston            | 202       | 256    | 13.4%   |
| SanDisk             | 136       | 174    | 9.02%   |
| Crucial             | 126       | 172    | 8.36%   |
| WDC                 | 76        | 97     | 5.04%   |
| A-DATA Technology   | 58        | 76     | 3.85%   |
| China               | 52        | 62     | 3.45%   |
| Intel               | 49        | 73     | 3.25%   |
| PNY                 | 32        | 42     | 2.12%   |
| Patriot             | 30        | 35     | 1.99%   |
| Toshiba             | 27        | 34     | 1.79%   |
| Micron Technology   | 27        | 30     | 1.79%   |
| OCZ                 | 26        | 32     | 1.73%   |
| Transcend           | 24        | 24     | 1.59%   |
| SK hynix            | 21        | 21     | 1.39%   |
| Intenso             | 17        | 19     | 1.13%   |
| SPCC                | 16        | 24     | 1.06%   |
| LITEON              | 16        | 18     | 1.06%   |
| LITEONIT            | 15        | 18     | 1%      |
| Apacer              | 15        | 21     | 1%      |
| KingDian            | 12        | 18     | 0.8%    |
| Apple               | 10        | 14     | 0.66%   |
| Unknown             | 8         | 9      | 0.53%   |
| Lexar               | 8         | 8      | 0.53%   |
| Smartbuy            | 7         | 7      | 0.46%   |
| Plextor             | 7         | 8      | 0.46%   |
| KingSpec            | 7         | 9      | 0.46%   |
| Hewlett-Packard     | 6         | 9      | 0.4%    |
| Goodram             | 6         | 8      | 0.4%    |
| Corsair             | 6         | 6      | 0.4%    |
| TO Exter            | 5         | 6      | 0.33%   |
| Team                | 5         | 9      | 0.33%   |
| Mushkin             | 5         | 5      | 0.33%   |
| JMicron Technology  | 5         | 5      | 0.33%   |
| Netac               | 4         | 6      | 0.27%   |
| FORESEE             | 4         | 5      | 0.27%   |
| Drevo               | 4         | 4      | 0.27%   |
| Vaseky              | 3         | 4      | 0.2%    |
| Seagate             | 3         | 3      | 0.2%    |
| Kingmax             | 3         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2356      | 3875   | 51.91%  |
| SSD     | 1353      | 1932   | 29.81%  |
| NVMe    | 530       | 688    | 11.68%  |
| MMC     | 226       | 290    | 4.98%   |
| Unknown | 74        | 95     | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3188      | 5630   | 76.86%  |
| NVMe | 524       | 680    | 12.63%  |
| MMC  | 226       | 290    | 5.45%   |
| SAS  | 210       | 280    | 5.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2626      | 3958   | 67.68%  |
| 0.51-1.0   | 844       | 1187   | 21.75%  |
| 1.01-2.0   | 210       | 335    | 5.41%   |
| 3.01-4.0   | 94        | 148    | 2.42%   |
| 2.01-3.0   | 54        | 96     | 1.39%   |
| 4.01-10.0  | 47        | 77     | 1.21%   |
| 10.01-20.0 | 4         | 5      | 0.1%    |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1210      | 31.32%  |
| 251-500        | 865       | 22.39%  |
| 501-1000       | 491       | 12.71%  |
| 51-100         | 361       | 9.35%   |
| 21-50          | 260       | 6.73%   |
| 1001-2000      | 246       | 6.37%   |
| 1-20           | 176       | 4.56%   |
| More than 3000 | 140       | 3.62%   |
| 2001-3000      | 89        | 2.3%    |
| Unknown        | 25        | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1659      | 41.33%  |
| 21-50          | 683       | 17.02%  |
| 101-250        | 499       | 12.43%  |
| 51-100         | 471       | 11.73%  |
| 251-500        | 278       | 6.93%   |
| 501-1000       | 198       | 4.93%   |
| 1001-2000      | 102       | 2.54%   |
| More than 3000 | 59        | 1.47%   |
| 2001-3000      | 40        | 1%      |
| Unknown        | 25        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 7      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 6      | 2.09%   |
| Toshiba MQ01ABD100 1TB              | 5         | 6      | 1.74%   |
| Seagate ST9500325AS 500GB           | 5         | 7      | 1.74%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 1.74%   |
| Seagate ST3500418AS 500GB           | 3         | 4      | 1.05%   |
| Seagate ST2000DM001-1CH164 2TB      | 3         | 4      | 1.05%   |
| Samsung Electronics HM321HI 320GB   | 3         | 4      | 1.05%   |
| Maxtor STM3160215AS 160GB           | 3         | 3      | 1.05%   |
| Hitachi HDS721050CLA362 500GB       | 3         | 3      | 1.05%   |
| HGST HTS545050A7E680 500GB          | 3         | 3      | 1.05%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 1.05%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 2         | 2      | 0.7%    |
| WDC WD7500BPKX-00HPJT0 752GB        | 2         | 2      | 0.7%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.7%    |
| WDC WD4000FYYZ-01UL1B1 4TB          | 2         | 3      | 0.7%    |
| WDC WD3200AAKS-00L9A0 320GB         | 2         | 2      | 0.7%    |
| WDC WD1002FAEX-00Z3A0 1TB           | 2         | 2      | 0.7%    |
| Toshiba MK2552GSX 250GB             | 2         | 2      | 0.7%    |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.7%    |
| Seagate ST9500423AS 500GB           | 2         | 2      | 0.7%    |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.7%    |
| Seagate ST9320325AS 320GB           | 2         | 2      | 0.7%    |
| Seagate ST9250410AS 250GB           | 2         | 2      | 0.7%    |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 0.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 0.7%    |
| Seagate ST3250318AS 250GB           | 2         | 4      | 0.7%    |
| Seagate ST31000528AS 1TB            | 2         | 2      | 0.7%    |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 2      | 0.7%    |
| Samsung Electronics HD753LJ 752GB   | 2         | 3      | 0.7%    |
| Samsung Electronics HD103SJ 1TB     | 2         | 3      | 0.7%    |
| Samsung Electronics HD103SI 1TB     | 2         | 2      | 0.7%    |
| Samsung Electronics HD081GJ 80GB    | 2         | 2      | 0.7%    |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 0.7%    |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.7%    |
| KingDian S100 32GB SSD              | 2         | 4      | 0.7%    |
| Hitachi HTS725050A9A364 500GB       | 2         | 3      | 0.7%    |
| Hitachi HTS725032A9A364 320GB       | 2         | 2      | 0.7%    |
| Hitachi HTS545050A7E380 500GB       | 2         | 2      | 0.7%    |
| Hitachi HTS543232A7A384 320GB       | 2         | 3      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 95     | 29.29%  |
| WDC                 | 58        | 66     | 20.71%  |
| Toshiba             | 28        | 34     | 10%     |
| Hitachi             | 27        | 34     | 9.64%   |
| Samsung Electronics | 21        | 28     | 7.5%    |
| HGST                | 9         | 10     | 3.21%   |
| Maxtor              | 6         | 6      | 2.14%   |
| Kingston            | 6         | 8      | 2.14%   |
| SK hynix            | 5         | 5      | 1.79%   |
| Intel               | 4         | 5      | 1.43%   |
| Fujitsu             | 4         | 5      | 1.43%   |
| Crucial             | 3         | 3      | 1.07%   |
| A-DATA Technology   | 3         | 4      | 1.07%   |
| SanDisk             | 2         | 2      | 0.71%   |
| OCZ                 | 2         | 2      | 0.71%   |
| Micron Technology   | 2         | 2      | 0.71%   |
| KingDian            | 2         | 4      | 0.71%   |
| Unknown             | 1         | 1      | 0.36%   |
| SSSTC               | 1         | 1      | 0.36%   |
| SPCC                | 1         | 1      | 0.36%   |
| Neo Forza           | 1         | 1      | 0.36%   |
| Mushkin             | 1         | 1      | 0.36%   |
| LITEON              | 1         | 1      | 0.36%   |
| LDLC                | 1         | 1      | 0.36%   |
| ICY BOX             | 1         | 1      | 0.36%   |
| FORESEE             | 1         | 1      | 0.36%   |
| Drevo               | 1         | 1      | 0.36%   |
| Corsair             | 1         | 1      | 0.36%   |
| China               | 1         | 1      | 0.36%   |
| Avant               | 1         | 1      | 0.36%   |
| ASMT                | 1         | 4      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |
| Apacer              | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 95     | 35.81%  |
| WDC                 | 55        | 63     | 24.02%  |
| Toshiba             | 27        | 33     | 11.79%  |
| Hitachi             | 27        | 34     | 11.79%  |
| Samsung Electronics | 17        | 23     | 7.42%   |
| HGST                | 9         | 10     | 3.93%   |
| Maxtor              | 6         | 6      | 2.62%   |
| Fujitsu             | 4         | 5      | 1.75%   |
| ICY BOX             | 1         | 1      | 0.44%   |
| ASMT                | 1         | 4      | 0.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 216       | 274    | 81.51%  |
| SSD  | 47        | 56     | 17.74%  |
| NVMe | 2         | 2      | 0.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J99B0 2TB         | 1         | 2      | 25%     |
| Toshiba DT01ACA200 2TB           | 1         | 1      | 25%     |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 25%     |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 1         | 2      | 25%     |
| Toshiba           | 1         | 1      | 25%     |
| Seagate           | 1         | 1      | 25%     |
| A-DATA Technology | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2614      | 4850   | 67.16%  |
| Works    | 1015      | 1693   | 26.08%  |
| Malfunc  | 259       | 332    | 6.65%   |
| Failed   | 4         | 5      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2579      | 61.71%  |
| AMD                              | 637       | 15.24%  |
| Samsung Electronics              | 184       | 4.4%    |
| Nvidia                           | 139       | 3.33%   |
| SanDisk                          | 78        | 1.87%   |
| JMicron Technology               | 63        | 1.51%   |
| ASMedia Technology               | 62        | 1.48%   |
| VIA Technologies                 | 53        | 1.27%   |
| SK hynix                         | 49        | 1.17%   |
| Marvell Technology Group         | 45        | 1.08%   |
| Silicon Integrated Systems [SiS] | 38        | 0.91%   |
| Phison Electronics               | 29        | 0.69%   |
| Kingston Technology Company      | 27        | 0.65%   |
| Toshiba America Info Systems     | 26        | 0.62%   |
| Silicon Motion                   | 21        | 0.5%    |
| KIOXIA                           | 20        | 0.48%   |
| ADATA Technology                 | 15        | 0.36%   |
| LSI Logic / Symbios Logic        | 14        | 0.34%   |
| Micron/Crucial Technology        | 12        | 0.29%   |
| Micron Technology                | 11        | 0.26%   |
| Silicon Image                    | 9         | 0.22%   |
| Realtek Semiconductor            | 8         | 0.19%   |
| Broadcom / LSI                   | 8         | 0.19%   |
| Adaptec                          | 7         | 0.17%   |
| ULi Electronics                  | 6         | 0.14%   |
| Hewlett-Packard                  | 6         | 0.14%   |
| Apple                            | 5         | 0.12%   |
| Union Memory (Shenzhen)          | 4         | 0.1%    |
| Promise Technology               | 4         | 0.1%    |
| Integrated Technology Express    | 4         | 0.1%    |
| Seagate Technology               | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| Lite-On Technology               | 2         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 377       | 7.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 168       | 3.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 168       | 3.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 151       | 2.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 138       | 2.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 125       | 2.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 123       | 2.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 115       | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 112       | 2.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 106       | 2.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 103       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 102       | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 92        | 1.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 91        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 86        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 76        | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 72        | 1.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 66        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 64        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 61        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 60        | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 60        | 1.14%   |
| AMD 400 Series Chipset SATA Controller                                                  | 60        | 1.14%   |
| Nvidia MCP61 SATA Controller                                                            | 59        | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 58        | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 57        | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 53        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 52        | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 50        | 0.95%   |
| Nvidia MCP61 IDE                                                                        | 48        | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 44        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42        | 0.8%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 40        | 0.76%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 38        | 0.72%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 37        | 0.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 37        | 0.7%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 36        | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 36        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 36        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2503      | 56.23%  |
| IDE  | 1162      | 26.11%  |
| NVMe | 519       | 11.66%  |
| RAID | 243       | 5.46%   |
| SAS  | 13        | 0.29%   |
| SCSI | 11        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2870      | 77.42%  |
| AMD          | 796       | 21.47%  |
| ARM          | 37        | 1%      |
| CentaurHauls | 4         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz           | 31        | 0.83%   |
| ARM Processor                           | 29        | 0.78%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 27        | 0.73%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 25        | 0.67%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 23        | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 22        | 0.59%   |
| Intel Pentium 4 CPU 3.00GHz             | 21        | 0.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 0.56%   |
| Intel Atom CPU N450 @ 1.66GHz           | 21        | 0.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 20        | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 20        | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 19        | 0.51%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 19        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 19        | 0.51%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 19        | 0.51%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 18        | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 18        | 0.48%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 18        | 0.48%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 18        | 0.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 17        | 0.46%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 17        | 0.46%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 17        | 0.46%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 17        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 16        | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 16        | 0.43%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 16        | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 15        | 0.4%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 15        | 0.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 0.38%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 14        | 0.38%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 14        | 0.38%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 14        | 0.38%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 14        | 0.38%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 14        | 0.38%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 14        | 0.38%   |
| AMD Ryzen 5 3600 6-Core Processor       | 14        | 0.38%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 14        | 0.38%   |
| Intel Pentium M processor 1.73GHz       | 13        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 621       | 16.69%  |
| Intel Core i7           | 469       | 12.6%   |
| Intel Core 2 Duo        | 305       | 8.2%    |
| Intel Core i3           | 289       | 7.77%   |
| Intel Celeron           | 239       | 6.42%   |
| Intel Atom              | 175       | 4.7%    |
| Intel Pentium           | 119       | 3.2%    |
| Other                   | 113       | 3.04%   |
| AMD Ryzen 5             | 107       | 2.88%   |
| Intel Xeon              | 94        | 2.53%   |
| Intel Pentium Dual-Core | 84        | 2.26%   |
| AMD Ryzen 7             | 77        | 2.07%   |
| Intel Pentium Dual      | 64        | 1.72%   |
| Intel Pentium 4         | 62        | 1.67%   |
| Intel Genuine           | 57        | 1.53%   |
| Intel Core 2 Quad       | 51        | 1.37%   |
| Intel Core 2            | 51        | 1.37%   |
| AMD FX                  | 49        | 1.32%   |
| AMD A8                  | 45        | 1.21%   |
| AMD Athlon 64 X2        | 41        | 1.1%    |
| AMD E1                  | 31        | 0.83%   |
| AMD A6                  | 30        | 0.81%   |
| Intel Pentium M         | 28        | 0.75%   |
| AMD Ryzen 9             | 27        | 0.73%   |
| AMD Ryzen 3             | 27        | 0.73%   |
| AMD Phenom II X4        | 27        | 0.73%   |
| AMD Athlon II X2        | 27        | 0.73%   |
| Intel Celeron M         | 24        | 0.64%   |
| AMD A4                  | 22        | 0.59%   |
| AMD A10                 | 22        | 0.59%   |
| AMD Turion 64 X2 Mobile | 20        | 0.54%   |
| AMD Sempron             | 19        | 0.51%   |
| AMD E                   | 19        | 0.51%   |
| AMD Athlon              | 18        | 0.48%   |
| Intel Pentium D         | 17        | 0.46%   |
| AMD E2                  | 16        | 0.43%   |
| AMD Athlon 64           | 16        | 0.43%   |
| Intel Core i9           | 15        | 0.4%    |
| AMD Ryzen 7 PRO         | 14        | 0.38%   |
| Intel Pentium Silver    | 11        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1830      | 49.23%  |
| 4       | 1137      | 30.59%  |
| 1       | 336       | 9.04%   |
| 6       | 188       | 5.06%   |
| 8       | 142       | 3.82%   |
| 12      | 31        | 0.83%   |
| 16      | 18        | 0.48%   |
| 3       | 17        | 0.46%   |
| 10      | 6         | 0.16%   |
| Unknown | 4         | 0.11%   |
| 64      | 2         | 0.05%   |
| 24      | 2         | 0.05%   |
| 20      | 2         | 0.05%   |
| 14      | 2         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3663      | 98.81%  |
| 2       | 41        | 1.11%   |
| Unknown | 3         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1879      | 50.62%  |
| 2       | 1829      | 49.27%  |
| Unknown | 4         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3492      | 94.17%  |
| 32-bit         | 189       | 5.1%    |
| Unknown        | 26        | 0.7%    |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 626       | 16.45%  |
| 0x206a7    | 256       | 6.73%   |
| 0x306a9    | 235       | 6.18%   |
| 0x1067a    | 230       | 6.04%   |
| 0x306c3    | 148       | 3.89%   |
| 0x6fd      | 141       | 3.71%   |
| 0x20655    | 83        | 2.18%   |
| 0x10676    | 80        | 2.1%    |
| 0x40651    | 66        | 1.73%   |
| 0x506e3    | 60        | 1.58%   |
| 0x30678    | 60        | 1.58%   |
| 0x906ea    | 59        | 1.55%   |
| 0x406c4    | 55        | 1.45%   |
| 0x106ca    | 52        | 1.37%   |
| 0x6fb      | 51        | 1.34%   |
| 0x010000c8 | 50        | 1.31%   |
| 0x406e3    | 49        | 1.29%   |
| 0x806ea    | 46        | 1.21%   |
| 0x6f6      | 46        | 1.21%   |
| 0x20652    | 45        | 1.18%   |
| 0x106c2    | 45        | 1.18%   |
| 0x806ec    | 43        | 1.13%   |
| 0x306d4    | 42        | 1.1%    |
| 0x806e9    | 39        | 1.02%   |
| 0x806c1    | 39        | 1.02%   |
| 0x906e9    | 38        | 1%      |
| 0x06000852 | 36        | 0.95%   |
| 0x6e8      | 35        | 0.92%   |
| 0x6d8      | 34        | 0.89%   |
| 0x08108109 | 34        | 0.89%   |
| 0x406c3    | 32        | 0.84%   |
| 0x106e5    | 31        | 0.81%   |
| 0x0800820d | 31        | 0.81%   |
| 0x05000119 | 31        | 0.81%   |
| 0x08701021 | 30        | 0.79%   |
| 0x07030105 | 28        | 0.74%   |
| 0x0700010f | 26        | 0.68%   |
| 0x06001119 | 26        | 0.68%   |
| 0xa0652    | 24        | 0.63%   |
| 0x03000027 | 24        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 345       | 9.28%   |
| KabyLake         | 319       | 8.58%   |
| SandyBridge      | 299       | 8.04%   |
| Core             | 290       | 7.8%    |
| IvyBridge        | 275       | 7.4%    |
| Haswell          | 254       | 6.83%   |
| Silvermont       | 168       | 4.52%   |
| Westmere         | 162       | 4.36%   |
| Skylake          | 135       | 3.63%   |
| K8 Hammer        | 125       | 3.36%   |
| Bonnell          | 123       | 3.31%   |
| K10              | 108       | 2.91%   |
| P6               | 98        | 2.64%   |
| Zen 2            | 94        | 2.53%   |
| Zen+             | 90        | 2.42%   |
| NetBurst         | 88        | 2.37%   |
| Piledriver       | 70        | 1.88%   |
| Unknown          | 63        | 1.69%   |
| Broadwell        | 54        | 1.45%   |
| CometLake        | 53        | 1.43%   |
| Zen              | 51        | 1.37%   |
| TigerLake        | 50        | 1.35%   |
| Nehalem          | 48        | 1.29%   |
| Bobcat           | 46        | 1.24%   |
| Puma             | 37        | 1%      |
| Goldmont plus    | 36        | 0.97%   |
| Excavator        | 35        | 0.94%   |
| Zen 3            | 34        | 0.91%   |
| Goldmont         | 34        | 0.91%   |
| Jaguar           | 30        | 0.81%   |
| IceLake          | 29        | 0.78%   |
| K10 Llano        | 26        | 0.7%    |
| Steamroller      | 13        | 0.35%   |
| K8 & K10 hybrid  | 11        | 0.3%    |
| Bulldozer        | 10        | 0.27%   |
| K6               | 6         | 0.16%   |
| Alderlake Hybrid | 5         | 0.13%   |
| Tremont          | 3         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2076      | 50.47%  |
| Nvidia                           | 1053      | 25.6%   |
| AMD                              | 912       | 22.17%  |
| Silicon Integrated Systems [SiS] | 24        | 0.58%   |
| Matrox Electronics Systems       | 21        | 0.51%   |
| VIA Technologies                 | 18        | 0.44%   |
| ASPEED Technology                | 7         | 0.17%   |
| S3 Graphics                      | 1         | 0.02%   |
| Alliance Semiconductor           | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 219       | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 145       | 3.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 115       | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 99        | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 94        | 2.15%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 85        | 1.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 1.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 73        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 71        | 1.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 70        | 1.6%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 60        | 1.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 55        | 1.26%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 55        | 1.26%   |
| Intel UHD Graphics 620                                                                   | 54        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 54        | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 52        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 1.14%   |
| Intel HD Graphics 620                                                                    | 47        | 1.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 45        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 44        | 1%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 44        | 1%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 42        | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 0.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 0.91%   |
| Intel HD Graphics 5500                                                                   | 38        | 0.87%   |
| AMD Renoir                                                                               | 37        | 0.84%   |
| Intel HD Graphics 530                                                                    | 36        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 34        | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.66%   |
| Intel HD Graphics 500                                                                    | 27        | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 27        | 0.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 0.62%   |
| Intel HD Graphics 630                                                                    | 26        | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 24        | 0.55%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 24        | 0.55%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 22        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 1691      | 45.35%  |
| 1 x Nvidia                           | 744       | 19.95%  |
| 1 x AMD                              | 731       | 19.6%   |
| Intel + Nvidia                       | 264       | 7.08%   |
| Intel + AMD                          | 83        | 2.23%   |
| 2 x AMD                              | 65        | 1.74%   |
| Other                                | 44        | 1.18%   |
| AMD + Nvidia                         | 25        | 0.67%   |
| 1 x SiS                              | 24        | 0.64%   |
| 1 x VIA                              | 18        | 0.48%   |
| 1 x Matrox                           | 15        | 0.4%    |
| 2 x Nvidia                           | 5         | 0.13%   |
| Nvidia + ASPEED                      | 5         | 0.13%   |
| Nvidia + Matrox                      | 3         | 0.08%   |
| 1 x ASPEED                           | 2         | 0.05%   |
| AMD + Matrox                         | 2         | 0.05%   |
| 3 x AMD                              | 1         | 0.03%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.03%   |
| 2 x Intel                            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia                 | 1         | 0.03%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.03%   |
| 1 x S3 Graphics                      | 1         | 0.03%   |
| Intel + 2 x AMD                      | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2989      | 80.05%  |
| Proprietary | 566       | 15.16%  |
| Unknown     | 179       | 4.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1881      | 49.7%   |
| 0.01-0.5   | 772       | 20.4%   |
| 1.01-2.0   | 438       | 11.57%  |
| 0.51-1.0   | 347       | 9.17%   |
| 3.01-4.0   | 191       | 5.05%   |
| 7.01-8.0   | 72        | 1.9%    |
| 5.01-6.0   | 46        | 1.22%   |
| 8.01-16.0  | 18        | 0.48%   |
| 2.01-3.0   | 15        | 0.4%    |
| 4.01-5.0   | 2         | 0.05%   |
| 16.01-24.0 | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 562       | 14.76%  |
| AU Optronics            | 419       | 11%     |
| LG Display              | 327       | 8.59%   |
| Chimei Innolux          | 212       | 5.57%   |
| Dell                    | 205       | 5.38%   |
| BOE                     | 195       | 5.12%   |
| Goldstar                | 184       | 4.83%   |
| Hewlett-Packard         | 144       | 3.78%   |
| Acer                    | 138       | 3.62%   |
| Philips                 | 100       | 2.63%   |
| Chi Mei Optoelectronics | 98        | 2.57%   |
| AOC                     | 96        | 2.52%   |
| Lenovo                  | 92        | 2.42%   |
| Ancor Communications    | 72        | 1.89%   |
| BenQ                    | 70        | 1.84%   |
| LG Philips              | 68        | 1.79%   |
| Apple                   | 53        | 1.39%   |
| ViewSonic               | 50        | 1.31%   |
| HannStar                | 50        | 1.31%   |
| Iiyama                  | 39        | 1.02%   |
| Unknown                 | 37        | 0.97%   |
| Sony                    | 36        | 0.95%   |
| LG Electronics          | 34        | 0.89%   |
| InfoVision              | 31        | 0.81%   |
| Sharp                   | 29        | 0.76%   |
| Fujitsu Siemens         | 26        | 0.68%   |
| CPT                     | 24        | 0.63%   |
| Panasonic               | 22        | 0.58%   |
| NEC Computers           | 21        | 0.55%   |
| PANDA                   | 18        | 0.47%   |
| Toshiba                 | 17        | 0.45%   |
| Eizo                    | 16        | 0.42%   |
| Medion                  | 14        | 0.37%   |
| ASUSTek Computer        | 14        | 0.37%   |
| Vizio                   | 13        | 0.34%   |
| Quanta Display          | 10        | 0.26%   |
| Vestel Elektronik       | 9         | 0.24%   |
| Lenovo Group Limited    | 8         | 0.21%   |
| DENON                   | 8         | 0.21%   |
| CSO                     | 8         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.56%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 20        | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 18        | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.41%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 16        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.28%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                       | 10        | 0.25%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.25%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 10        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.25%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 9         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.2%    |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.18%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.18%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.18%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.18%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                     | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.18%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 7         | 0.18%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 6         | 0.15%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 6         | 0.15%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.15%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 6         | 0.15%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 6         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1248      | 33.61%  |
| 1366x768 (WXGA)    | 825       | 22.22%  |
| 1280x800 (WXGA)    | 241       | 6.49%   |
| 1280x1024 (SXGA)   | 218       | 5.87%   |
| 1600x900 (HD+)     | 185       | 4.98%   |
| 1440x900 (WXGA+)   | 174       | 4.69%   |
| 1680x1050 (WSXGA+) | 145       | 3.91%   |
| 3840x2160 (4K)     | 139       | 3.74%   |
| 1920x1200 (WUXGA)  | 79        | 2.13%   |
| 2560x1440 (QHD)    | 76        | 2.05%   |
| 1024x600           | 66        | 1.78%   |
| Unknown            | 58        | 1.56%   |
| 1024x768 (XGA)     | 42        | 1.13%   |
| 1360x768           | 41        | 1.1%    |
| 3840x1080          | 22        | 0.59%   |
| 1920x540           | 14        | 0.38%   |
| 1600x1200          | 13        | 0.35%   |
| 2560x1080          | 12        | 0.32%   |
| 2560x1600          | 11        | 0.3%    |
| 3440x1440          | 9         | 0.24%   |
| 1280x720 (HD)      | 9         | 0.24%   |
| 2288x1287          | 7         | 0.19%   |
| 3200x1080          | 6         | 0.16%   |
| 1400x1050          | 5         | 0.13%   |
| 5120x1440          | 4         | 0.11%   |
| 3840x1200          | 4         | 0.11%   |
| 3200x1800 (QHD+)   | 4         | 0.11%   |
| 2880x1800          | 4         | 0.11%   |
| 2160x1440          | 4         | 0.11%   |
| 2048x1152          | 3         | 0.08%   |
| 4480x1440          | 2         | 0.05%   |
| 3840x2400          | 2         | 0.05%   |
| 3840x1600          | 2         | 0.05%   |
| 3286x1080          | 2         | 0.05%   |
| 3200x900           | 2         | 0.05%   |
| 2960x1050          | 2         | 0.05%   |
| 2048x1536          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 800x600            | 1         | 0.03%   |
| 800x480            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 929       | 24.51%  |
| 14      | 288       | 7.6%    |
| 17      | 286       | 7.55%   |
| Unknown | 285       | 7.52%   |
| 13      | 252       | 6.65%   |
| 23      | 222       | 5.86%   |
| 24      | 202       | 5.33%   |
| 21      | 200       | 5.28%   |
| 19      | 185       | 4.88%   |
| 27      | 152       | 4.01%   |
| 18      | 118       | 3.11%   |
| 20      | 93        | 2.45%   |
| 22      | 81        | 2.14%   |
| 10      | 74        | 1.95%   |
| 12      | 72        | 1.9%    |
| 31      | 69        | 1.82%   |
| 11      | 62        | 1.64%   |
| 84      | 29        | 0.77%   |
| 72      | 21        | 0.55%   |
| 54      | 20        | 0.53%   |
| 26      | 17        | 0.45%   |
| 40      | 14        | 0.37%   |
| 32      | 14        | 0.37%   |
| 16      | 14        | 0.37%   |
| 25      | 13        | 0.34%   |
| 34      | 12        | 0.32%   |
| 52      | 8         | 0.21%   |
| 48      | 8         | 0.21%   |
| 28      | 8         | 0.21%   |
| 37      | 6         | 0.16%   |
| 8       | 4         | 0.11%   |
| 49      | 3         | 0.08%   |
| 47      | 3         | 0.08%   |
| 29      | 3         | 0.08%   |
| 142     | 2         | 0.05%   |
| 74      | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 60      | 2         | 0.05%   |
| 57      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1429      | 38.18%  |
| 401-500        | 556       | 14.85%  |
| 501-600        | 555       | 14.83%  |
| 201-300        | 337       | 9%      |
| 351-400        | 318       | 8.5%    |
| Unknown        | 285       | 7.61%   |
| 601-700        | 101       | 2.7%    |
| 1501-2000      | 53        | 1.42%   |
| 1001-1500      | 50        | 1.34%   |
| 701-800        | 27        | 0.72%   |
| 801-900        | 23        | 0.61%   |
| 101-200        | 5         | 0.13%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2313      | 65.65%  |
| 16/10   | 610       | 17.31%  |
| Unknown | 259       | 7.35%   |
| 5/4     | 208       | 5.9%    |
| 4/3     | 73        | 2.07%   |
| 3/2     | 22        | 0.62%   |
| 21/9    | 17        | 0.48%   |
| 6/5     | 9         | 0.26%   |
| 32/9    | 4         | 0.11%   |
| 1.00    | 4         | 0.11%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 927       | 24.6%   |
| 201-250        | 573       | 15.2%   |
| 81-90          | 431       | 11.44%  |
| 151-200        | 359       | 9.53%   |
| Unknown        | 285       | 7.56%   |
| 141-150        | 197       | 5.23%   |
| 301-350        | 161       | 4.27%   |
| 121-130        | 133       | 3.53%   |
| 351-500        | 103       | 2.73%   |
| More than 1000 | 97        | 2.57%   |
| 71-80          | 93        | 2.47%   |
| 251-300        | 90        | 2.39%   |
| 41-50          | 73        | 1.94%   |
| 61-70          | 67        | 1.78%   |
| 51-60          | 63        | 1.67%   |
| 131-140        | 46        | 1.22%   |
| 501-1000       | 33        | 0.88%   |
| 91-100         | 23        | 0.61%   |
| 111-120        | 10        | 0.27%   |
| 1-40           | 5         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1430      | 39.17%  |
| 101-120       | 1045      | 28.62%  |
| 121-160       | 687       | 18.82%  |
| Unknown       | 285       | 7.81%   |
| 161-240       | 89        | 2.44%   |
| 1-50          | 85        | 2.33%   |
| More than 240 | 30        | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3123      | 82.79%  |
| 2     | 447       | 11.85%  |
| 0     | 167       | 4.43%   |
| 3     | 31        | 0.82%   |
| 4     | 4         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1914      | 33.57%  |
| Intel                             | 1508      | 26.45%  |
| Qualcomm Atheros                  | 735       | 12.89%  |
| Broadcom                          | 422       | 7.4%    |
| Marvell Technology Group          | 133       | 2.33%   |
| Nvidia                            | 114       | 2%      |
| Broadcom Limited                  | 114       | 2%      |
| Ralink Technology                 | 87        | 1.53%   |
| Ralink                            | 80        | 1.4%    |
| TP-Link                           | 63        | 1.11%   |
| VIA Technologies                  | 39        | 0.68%   |
| Qualcomm Atheros Communications   | 36        | 0.63%   |
| Silicon Integrated Systems [SiS]  | 32        | 0.56%   |
| Samsung Electronics               | 30        | 0.53%   |
| Huawei Technologies               | 28        | 0.49%   |
| MediaTek                          | 27        | 0.47%   |
| D-Link System                     | 26        | 0.46%   |
| NetGear                           | 22        | 0.39%   |
| JMicron Technology                | 21        | 0.37%   |
| Sierra Wireless                   | 16        | 0.28%   |
| D-Link                            | 16        | 0.28%   |
| Ericsson Business Mobile Networks | 15        | 0.26%   |
| Attansic Technology               | 15        | 0.26%   |
| ASIX Electronics                  | 12        | 0.21%   |
| ASUSTek Computer                  | 11        | 0.19%   |
| Xiaomi                            | 10        | 0.18%   |
| Edimax Technology                 | 10        | 0.18%   |
| Lenovo                            | 9         | 0.16%   |
| DisplayLink                       | 9         | 0.16%   |
| Aquantia                          | 9         | 0.16%   |
| Dell                              | 8         | 0.14%   |
| AMD                               | 8         | 0.14%   |
| Belkin Components                 | 7         | 0.12%   |
| Qualcomm                          | 6         | 0.11%   |
| Microsoft                         | 6         | 0.11%   |
| Fibocom                           | 6         | 0.11%   |
| ULi Electronics                   | 5         | 0.09%   |
| Sitecom Europe                    | 5         | 0.09%   |
| Linksys                           | 5         | 0.09%   |
| HTC (High Tech Computer)          | 5         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1208      | 18.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 323       | 4.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 166       | 2.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 109       | 1.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 91        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 89        | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 87        | 1.32%   |
| Intel Wi-Fi 6 AX200                                                     | 86        | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 70        | 1.06%   |
| Intel Wireless 7260                                                     | 67        | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 58        | 0.88%   |
| Intel Wireless 8265 / 8275                                              | 56        | 0.85%   |
| Intel Wireless 7265                                                     | 56        | 0.85%   |
| Intel Ethernet Connection I217-LM                                       | 55        | 0.83%   |
| Nvidia MCP61 Ethernet                                                   | 52        | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 0.77%   |
| Intel Wireless 3165                                                     | 47        | 0.71%   |
| Intel I211 Gigabit Network Connection                                   | 46        | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 44        | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 0.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 40        | 0.61%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 38        | 0.57%   |
| Intel Wireless 8260                                                     | 38        | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 38        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                 | 37        | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 34        | 0.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                            | 32        | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 32        | 0.48%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 31        | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 30        | 0.45%   |
| Intel Ethernet Connection (2) I219-V                                    | 30        | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                       | 29        | 0.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1024      | 35.85%  |
| Qualcomm Atheros                      | 595       | 20.83%  |
| Realtek Semiconductor                 | 486       | 17.02%  |
| Broadcom                              | 255       | 8.93%   |
| Ralink Technology                     | 87        | 3.05%   |
| Ralink                                | 80        | 2.8%    |
| TP-Link                               | 59        | 2.07%   |
| Broadcom Limited                      | 55        | 1.93%   |
| Qualcomm Atheros Communications       | 36        | 1.26%   |
| NetGear                               | 22        | 0.77%   |
| MediaTek                              | 18        | 0.63%   |
| D-Link System                         | 18        | 0.63%   |
| Sierra Wireless                       | 16        | 0.56%   |
| D-Link                                | 15        | 0.53%   |
| Edimax Technology                     | 10        | 0.35%   |
| ASUSTek Computer                      | 10        | 0.35%   |
| Belkin Components                     | 7         | 0.25%   |
| Microsoft                             | 6         | 0.21%   |
| Fibocom                               | 6         | 0.21%   |
| Sitecom Europe                        | 5         | 0.18%   |
| Linksys                               | 5         | 0.18%   |
| Dell                                  | 5         | 0.18%   |
| ZyDAS                                 | 4         | 0.14%   |
| Marvell Technology Group              | 4         | 0.14%   |
| IMC Networks                          | 4         | 0.14%   |
| AVM                                   | 4         | 0.14%   |
| TRENDnet                              | 3         | 0.11%   |
| Qualcomm                              | 3         | 0.11%   |
| Hewlett-Packard                       | 2         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.07%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Xiaomi                                | 1         | 0.04%   |
| Winbond Electronics                   | 1         | 0.04%   |
| Texas Instruments                     | 1         | 0.04%   |
| Philips (or NXP)                      | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |
| AboCom Systems                        | 1         | 0.04%   |
| 3Com                                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 109       | 3.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 91        | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 89        | 3.08%   |
| Intel Wi-Fi 6 AX200                                                     | 86        | 2.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 70        | 2.43%   |
| Intel Wireless 7260                                                     | 67        | 2.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 64        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 58        | 2.01%   |
| Intel Wireless 8265 / 8275                                              | 56        | 1.94%   |
| Intel Wireless 7265                                                     | 56        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 1.77%   |
| Intel Wireless 3165                                                     | 47        | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 44        | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 43        | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 38        | 1.32%   |
| Intel Wireless 8260                                                     | 38        | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 34        | 1.18%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 32        | 1.11%   |
| Ralink MT7601U Wireless Adapter                                         | 32        | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 31        | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 29        | 1%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 28        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 27        | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 27        | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 26        | 0.9%    |
| Intel Centrino Advanced-N 6200                                          | 26        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 0.9%    |
| Intel Wireless-AC 9260                                                  | 25        | 0.87%   |
| Intel Wireless 3160                                                     | 25        | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 0.87%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 24        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 23        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 23        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1705      | 47.73%  |
| Intel                            | 863       | 24.16%  |
| Qualcomm Atheros                 | 228       | 6.38%   |
| Broadcom                         | 208       | 5.82%   |
| Marvell Technology Group         | 129       | 3.61%   |
| Nvidia                           | 113       | 3.16%   |
| Broadcom Limited                 | 60        | 1.68%   |
| VIA Technologies                 | 39        | 1.09%   |
| Silicon Integrated Systems [SiS] | 30        | 0.84%   |
| Samsung Electronics              | 29        | 0.81%   |
| JMicron Technology               | 21        | 0.59%   |
| Huawei Technologies              | 18        | 0.5%    |
| Attansic Technology              | 15        | 0.42%   |
| ASIX Electronics                 | 12        | 0.34%   |
| MediaTek                         | 10        | 0.28%   |
| Xiaomi                           | 9         | 0.25%   |
| Lenovo                           | 9         | 0.25%   |
| DisplayLink                      | 9         | 0.25%   |
| Aquantia                         | 9         | 0.25%   |
| D-Link System                    | 8         | 0.22%   |
| HTC (High Tech Computer)         | 5         | 0.14%   |
| TP-Link                          | 4         | 0.11%   |
| LG Electronics                   | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 3         | 0.08%   |
| Qualcomm                         | 3         | 0.08%   |
| IBM                              | 3         | 0.08%   |
| Apple                            | 3         | 0.08%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| National Semiconductor           | 2         | 0.06%   |
| Motorola PCS                     | 2         | 0.06%   |
| Insyde Software                  | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| 3Com                             | 2         | 0.06%   |
| ULi Electronics                  | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| Mellanox Technologies            | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| Hangzhou Silan Microelectronics  | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1208      | 33.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 323       | 8.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 166       | 4.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 87        | 2.4%    |
| Intel Ethernet Connection I217-LM                                 | 55        | 1.52%   |
| Nvidia MCP61 Ethernet                                             | 52        | 1.44%   |
| Intel I211 Gigabit Network Connection                             | 46        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 1.1%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 37        | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 32        | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 30        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 28        | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 27        | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 27        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 25        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 19        | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 18        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 18        | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 17        | 0.47%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.47%   |
| Intel 82573L Gigabit Ethernet Controller                          | 17        | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 17        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 16        | 0.44%   |
| Intel PRO/100 VE Network Connection                               | 16        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 16        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 15        | 0.41%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 15        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3372      | 54.82%  |
| WiFi     | 2676      | 43.51%  |
| Modem    | 97        | 1.58%   |
| Unknown  | 6         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2122      | 55.46%  |
| Ethernet | 1703      | 44.51%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2083      | 55.95%  |
| 1     | 1458      | 39.16%  |
| 0     | 105       | 2.82%   |
| 3     | 55        | 1.48%   |
| 4     | 17        | 0.46%   |
| 5     | 2         | 0.05%   |
| 10    | 1         | 0.03%   |
| 8     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3220      | 85.57%  |
| Yes  | 543       | 14.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 620       | 37.9%   |
| Broadcom                        | 165       | 10.09%  |
| Qualcomm Atheros Communications | 151       | 9.23%   |
| Realtek Semiconductor           | 143       | 8.74%   |
| Cambridge Silicon Radio         | 109       | 6.66%   |
| Apple                           | 59        | 3.61%   |
| Lite-On Technology              | 58        | 3.55%   |
| IMC Networks                    | 52        | 3.18%   |
| Foxconn / Hon Hai               | 52        | 3.18%   |
| Dell                            | 52        | 3.18%   |
| Hewlett-Packard                 | 47        | 2.87%   |
| ASUSTek Computer                | 26        | 1.59%   |
| Toshiba                         | 20        | 1.22%   |
| Ralink                          | 17        | 1.04%   |
| Alps Electric                   | 13        | 0.79%   |
| Realtek                         | 7         | 0.43%   |
| Integrated System Solution      | 7         | 0.43%   |
| Ralink Technology               | 6         | 0.37%   |
| Foxconn International           | 6         | 0.37%   |
| MediaTek                        | 5         | 0.31%   |
| Chicony Electronics             | 4         | 0.24%   |
| Edimax Technology               | 3         | 0.18%   |
| Qcom                            | 2         | 0.12%   |
| Fujitsu                         | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Syntek                          | 1         | 0.06%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Marvell Semiconductor           | 1         | 0.06%   |
| Logitech                        | 1         | 0.06%   |
| Conwise Technology              | 1         | 0.06%   |
| Askey Computer                  | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 274       | 16.74%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 109       | 6.66%   |
| Intel AX201 Bluetooth                                                               | 87        | 5.31%   |
| Intel AX200 Bluetooth                                                               | 86        | 5.25%   |
| Realtek Bluetooth Radio                                                             | 83        | 5.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 65        | 3.97%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 62        | 3.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 40        | 2.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 33        | 2.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 30        | 1.83%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 28        | 1.71%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 28        | 1.71%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 25        | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 22        | 1.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 22        | 1.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 19        | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 19        | 1.16%   |
| Apple Bluetooth HCI                                                                 | 19        | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 18        | 1.1%    |
| Ralink RT3290 Bluetooth                                                             | 17        | 1.04%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 17        | 1.04%   |
| Lite-On Bluetooth Device                                                            | 17        | 1.04%   |
| IMC Networks Bluetooth Device                                                       | 16        | 0.98%   |
| Apple Bluetooth Host Controller                                                     | 16        | 0.98%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 0.92%   |
| Broadcom BCM2045 Bluetooth                                                          | 15        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 14        | 0.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 14        | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 13        | 0.79%   |
| Intel AX210 Bluetooth                                                               | 13        | 0.79%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.79%   |
| Realtek RTL8723B Bluetooth                                                          | 12        | 0.73%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 11        | 0.67%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.61%   |
| Dell DW375 Bluetooth Module                                                         | 10        | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2655      | 55.39%  |
| AMD                                  | 871       | 18.17%  |
| Nvidia                               | 759       | 15.84%  |
| C-Media Electronics                  | 70        | 1.46%   |
| Creative Labs                        | 51        | 1.06%   |
| VIA Technologies                     | 47        | 0.98%   |
| Silicon Integrated Systems [SiS]     | 38        | 0.79%   |
| Logitech                             | 27        | 0.56%   |
| Texas Instruments                    | 25        | 0.52%   |
| GN Netcom                            | 15        | 0.31%   |
| M-Audio                              | 12        | 0.25%   |
| Focusrite-Novation                   | 12        | 0.25%   |
| Plantronics                          | 10        | 0.21%   |
| JMTek                                | 10        | 0.21%   |
| Generalplus Technology               | 10        | 0.21%   |
| Yamaha                               | 9         | 0.19%   |
| Lenovo                               | 9         | 0.19%   |
| Creative Technology                  | 9         | 0.19%   |
| Realtek Semiconductor                | 7         | 0.15%   |
| ULi Electronics                      | 6         | 0.13%   |
| BEHRINGER International              | 6         | 0.13%   |
| Sennheiser Communications            | 5         | 0.1%    |
| ASUSTek Computer                     | 5         | 0.1%    |
| SAVITECH                             | 4         | 0.08%   |
| Ensoniq                              | 4         | 0.08%   |
| AKAI Professional M.I.               | 4         | 0.08%   |
| Xilinx                               | 3         | 0.06%   |
| Tenx Technology                      | 3         | 0.06%   |
| TEAC                                 | 3         | 0.06%   |
| Roland                               | 3         | 0.06%   |
| Kingston Technology                  | 3         | 0.06%   |
| Elite Silicon                        | 3         | 0.06%   |
| EGO SYStems                          | 3         | 0.06%   |
| DigiTech                             | 3         | 0.06%   |
| Digidesign                           | 3         | 0.06%   |
| Corsair                              | 3         | 0.06%   |
| ZOOM                                 | 2         | 0.04%   |
| XMOS                                 | 2         | 0.04%   |
| Unknown                              | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 325       | 5.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 275       | 4.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 262       | 4.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 203       | 3.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 177       | 3.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 176       | 3.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 170       | 3.08%   |
| AMD FCH Azalia Controller                                                                         | 158       | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 149       | 2.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 145       | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 145       | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 115       | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 78        | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 78        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 78        | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 71        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 71        | 1.29%   |
| Intel 8 Series HD Audio Controller                                                                | 71        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 70        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 69        | 1.25%   |
| Nvidia High Definition Audio Controller                                                           | 65        | 1.18%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 64        | 1.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 64        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 61        | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 57        | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                                | 56        | 1.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 53        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 50        | 0.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 0.91%   |
| Intel Broadwell-U Audio Controller                                                                | 49        | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 48        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 46        | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 44        | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 41        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 40        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 39        | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 36        | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 36        | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 36        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 35        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 383       | 20.93%  |
| SK hynix                                         | 315       | 17.21%  |
| Unknown                                          | 301       | 16.45%  |
| Kingston                                         | 199       | 10.87%  |
| Micron Technology                                | 149       | 8.14%   |
| Crucial                                          | 106       | 5.79%   |
| Corsair                                          | 69        | 3.77%   |
| G.Skill                                          | 48        | 2.62%   |
| Elpida                                           | 42        | 2.3%    |
| Ramaxel Technology                               | 29        | 1.58%   |
| Nanya Technology                                 | 27        | 1.48%   |
| A-DATA Technology                                | 25        | 1.37%   |
| Unknown (ABCD)                                   | 20        | 1.09%   |
| Smart                                            | 12        | 0.66%   |
| Transcend                                        | 11        | 0.6%    |
| Team                                             | 10        | 0.55%   |
| Goodram                                          | 9         | 0.49%   |
| Apacer                                           | 5         | 0.27%   |
| Unknown                                          | 5         | 0.27%   |
| Patriot                                          | 4         | 0.22%   |
| Avant                                            | 4         | 0.22%   |
| Unifosa                                          | 3         | 0.16%   |
| Qimonda                                          | 3         | 0.16%   |
| 48spaces                                         | 3         | 0.16%   |
| Timetec                                          | 2         | 0.11%   |
| Teikon                                           | 2         | 0.11%   |
| Super Talent                                     | 2         | 0.11%   |
| PNY                                              | 2         | 0.11%   |
| Neo Forza                                        | 2         | 0.11%   |
| High Bridge                                      | 2         | 0.11%   |
| GeIL                                             | 2         | 0.11%   |
| ASint Technology                                 | 2         | 0.11%   |
| Walton Chaintech                                 | 1         | 0.05%   |
| V-GeN                                            | 1         | 0.05%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.05%   |
| Unknown (0x7FA8000000000000)                     | 1         | 0.05%   |
| Unknown (0x7F7FB5FFFFFFFFFF)                     | 1         | 0.05%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.05%   |
| Unknown (0x0043415455000000)                     | 1         | 0.05%   |
| Toshiba                                          | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 16        | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.81%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 15        | 0.76%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 0.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 13        | 0.66%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 12        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 11        | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 11        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 10        | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 9         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 9         | 0.46%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 9         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 7         | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 7         | 0.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 7         | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.35%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.3%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.3%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 6         | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.3%    |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 6         | 0.3%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 6         | 0.3%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 639       | 39.81%  |
| DDR4    | 556       | 34.64%  |
| DDR2    | 164       | 10.22%  |
| SDRAM   | 74        | 4.61%   |
| Unknown | 55        | 3.43%   |
| LPDDR4  | 54        | 3.36%   |
| LPDDR3  | 29        | 1.81%   |
| DDR     | 24        | 1.5%    |
| DRAM    | 7         | 0.44%   |
| DDR5    | 2         | 0.12%   |
| EEPROM  | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 930       | 59.05%  |
| DIMM         | 567       | 36%     |
| Row Of Chips | 60        | 3.81%   |
| Chip         | 10        | 0.63%   |
| Unknown      | 5         | 0.32%   |
| FB-DIMM      | 3         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 531       | 30.64%  |
| 8192    | 488       | 28.16%  |
| 2048    | 368       | 21.23%  |
| 16384   | 185       | 10.68%  |
| 1024    | 113       | 6.52%   |
| 32768   | 29        | 1.67%   |
| 512     | 13        | 0.75%   |
| 1536    | 2         | 0.12%   |
| 65536   | 1         | 0.06%   |
| 256     | 1         | 0.06%   |
| 1       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 395       | 23.18%  |
| 2667    | 230       | 13.5%   |
| 3200    | 146       | 8.57%   |
| 1333    | 134       | 7.86%   |
| 2400    | 113       | 6.63%   |
| 667     | 90        | 5.28%   |
| 800     | 74        | 4.34%   |
| Unknown | 71        | 4.17%   |
| 2133    | 63        | 3.7%    |
| 1334    | 61        | 3.58%   |
| 1066    | 30        | 1.76%   |
| 3600    | 28        | 1.64%   |
| 1067    | 26        | 1.53%   |
| 1867    | 25        | 1.47%   |
| 1866    | 18        | 1.06%   |
| 4199    | 17        | 1%      |
| 3266    | 16        | 0.94%   |
| 533     | 16        | 0.94%   |
| 4267    | 14        | 0.82%   |
| 3000    | 14        | 0.82%   |
| 2666    | 14        | 0.82%   |
| 2048    | 12        | 0.7%    |
| 1800    | 11        | 0.65%   |
| 975     | 8         | 0.47%   |
| 400     | 7         | 0.41%   |
| 3400    | 5         | 0.29%   |
| 49926   | 4         | 0.23%   |
| 3800    | 4         | 0.23%   |
| 3733    | 4         | 0.23%   |
| 2733    | 4         | 0.23%   |
| 2200    | 4         | 0.23%   |
| 2000    | 4         | 0.23%   |
| 333     | 4         | 0.23%   |
| 4800    | 3         | 0.18%   |
| 4266    | 3         | 0.18%   |
| 2800    | 3         | 0.18%   |
| 2448    | 3         | 0.18%   |
| 3466    | 2         | 0.12%   |
| 2187    | 2         | 0.12%   |
| 2134    | 2         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 51        | 40.48%  |
| Brother Industries    | 25        | 19.84%  |
| Canon                 | 21        | 16.67%  |
| Samsung Electronics   | 10        | 7.94%   |
| Seiko Epson           | 5         | 3.97%   |
| Zebra                 | 4         | 3.17%   |
| QinHeng Electronics   | 2         | 1.59%   |
| Prolific Technology   | 2         | 1.59%   |
| STMicroelectronics    | 1         | 0.79%   |
| Pantum                | 1         | 0.79%   |
| Minolta               | 1         | 0.79%   |
| Lexmark International | 1         | 0.79%   |
| Kyocera               | 1         | 0.79%   |
| Dymo-CoStar           | 1         | 0.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1005                                                     | 4         | 3.15%   |
| HP LaserJet 400 M401n                                                 | 4         | 3.15%   |
| Zebra ZP 450 Printer                                                  | 3         | 2.36%   |
| HP ENVY 4520 series                                                   | 3         | 2.36%   |
| Brother HL-5370DW series                                              | 3         | 2.36%   |
| Seiko Epson L220 Series                                               | 2         | 1.57%   |
| QinHeng CH340S                                                        | 2         | 1.57%   |
| Prolific PL2305 Parallel Port                                         | 2         | 1.57%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 1.57%   |
| HP LaserJet P1006                                                     | 2         | 1.57%   |
| HP LaserJet 1320                                                      | 2         | 1.57%   |
| HP LaserJet 1020                                                      | 2         | 1.57%   |
| HP LaserJet 1015                                                      | 2         | 1.57%   |
| HP DeskJet 3700 series                                                | 2         | 1.57%   |
| HP Deskjet 3050A                                                      | 2         | 1.57%   |
| Canon PIXMA MX530 Series                                              | 2         | 1.57%   |
| Canon LBP6000                                                         | 2         | 1.57%   |
| Brother HL-L2320D series                                              | 2         | 1.57%   |
| Brother HL-5340 series                                                | 2         | 1.57%   |
| Brother HL-2270DW Laser Printer                                       | 2         | 1.57%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.79%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 0.79%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.79%   |
| Seiko Epson L3160 Series                                              | 1         | 0.79%   |
| Seiko Epson ET-2600 Series                                            | 1         | 0.79%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 0.79%   |
| Samsung SF-760 Series                                                 | 1         | 0.79%   |
| Samsung SCX-4200 series                                               | 1         | 0.79%   |
| Samsung SCX-4100 Scanner                                              | 1         | 0.79%   |
| Samsung SCX-3400 Series                                               | 1         | 0.79%   |
| Samsung ML-2525W Series                                               | 1         | 0.79%   |
| Samsung ML-1740 Printer                                               | 1         | 0.79%   |
| Samsung M2070 Series                                                  | 1         | 0.79%   |
| Samsung M2020 Series                                                  | 1         | 0.79%   |
| Samsung C48x Series                                                   | 1         | 0.79%   |
| Pantum P2000                                                          | 1         | 0.79%   |
| Minolta PagePro 1300W                                                 | 1         | 0.79%   |
| Lexmark International E360d                                           | 1         | 0.79%   |
| Kyocera Mita FS-920                                                   | 1         | 0.79%   |
| HP PSC 750xi                                                          | 1         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 21        | 67.74%  |
| Seiko Epson     | 5         | 16.13%  |
| Hewlett-Packard | 5         | 16.13%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 9.68%   |
| Canon CanoScan LIDE 25                                      | 3         | 9.68%   |
| Canon CanoScan N650U/N656U                                  | 2         | 6.45%   |
| Canon CanoScan LiDE 220                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 210                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 120                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 110                                     | 2         | 6.45%   |
| Canon CanoScan LiDE 100                                     | 2         | 6.45%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 3.23%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 3.23%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1         | 3.23%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 3.23%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 3.23%   |
| HP ScanJet 82x0C                                            | 1         | 3.23%   |
| HP ScanJet 5590                                             | 1         | 3.23%   |
| HP ScanJet 3570c                                            | 1         | 3.23%   |
| HP Scanjet 200                                              | 1         | 3.23%   |
| HP PSC 1200                                                 | 1         | 3.23%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 3.23%   |
| Canon CanoScan LiDE 90                                      | 1         | 3.23%   |
| Canon CanoScan LiDE 200                                     | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 482       | 25.09%  |
| Microdia                               | 151       | 7.86%   |
| Realtek Semiconductor                  | 126       | 6.56%   |
| Acer                                   | 124       | 6.45%   |
| IMC Networks                           | 123       | 6.4%    |
| Suyin                                  | 115       | 5.99%   |
| Logitech                               | 98        | 5.1%    |
| Sunplus Innovation Technology          | 90        | 4.69%   |
| Quanta                                 | 67        | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 60        | 3.12%   |
| Apple                                  | 49        | 2.55%   |
| Alcor Micro                            | 44        | 2.29%   |
| Silicon Motion                         | 43        | 2.24%   |
| Syntek                                 | 38        | 1.98%   |
| Ricoh                                  | 38        | 1.98%   |
| Lite-On Technology                     | 35        | 1.82%   |
| Z-Star Microelectronics                | 22        | 1.15%   |
| Samsung Electronics                    | 22        | 1.15%   |
| Microsoft                              | 20        | 1.04%   |
| Lenovo                                 | 14        | 0.73%   |
| ALi                                    | 13        | 0.68%   |
| Luxvisions Innotech Limited            | 10        | 0.52%   |
| Importek                               | 10        | 0.52%   |
| Primax Electronics                     | 9         | 0.47%   |
| OmniVision Technologies                | 7         | 0.36%   |
| MacroSilicon                           | 7         | 0.36%   |
| Generalplus Technology                 | 7         | 0.36%   |
| GEMBIRD                                | 7         | 0.36%   |
| USB Camera                             | 6         | 0.31%   |
| DigiTech                               | 6         | 0.31%   |
| Jieli Technology                       | 5         | 0.26%   |
| Cubeternet                             | 5         | 0.26%   |
| Creative Technology                    | 5         | 0.26%   |
| Sunplus Technology                     | 4         | 0.21%   |
| KYE Systems (Mouse Systems)            | 4         | 0.21%   |
| ARC International                      | 4         | 0.21%   |
| Unknown                                | 3         | 0.16%   |
| Trust                                  | 3         | 0.16%   |
| Genesys Logic                          | 3         | 0.16%   |
| DJJHFA1BIF5595                         | 3         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 71        | 3.68%   |
| Realtek Integrated_Webcam_HD                     | 34        | 1.76%   |
| Microdia Integrated_Webcam_HD                    | 31        | 1.61%   |
| Chicony USB 2.0 Camera                           | 31        | 1.61%   |
| Chicony HD WebCam                                | 25        | 1.3%    |
| IMC Networks USB2.0 HD UVC WebCam                | 24        | 1.24%   |
| Acer Integrated Camera                           | 24        | 1.24%   |
| Logitech Webcam C270                             | 23        | 1.19%   |
| Realtek USB Camera                               | 22        | 1.14%   |
| Sunplus Integrated_Webcam_HD                     | 21        | 1.09%   |
| Samsung Galaxy A5 (MTP)                          | 21        | 1.09%   |
| IMC Networks Integrated Camera                   | 20        | 1.04%   |
| Alcor Micro USB 2.0 Camera                       | 20        | 1.04%   |
| Microdia Sonix USB 2.0 Camera                    | 19        | 0.99%   |
| Chicony TOSHIBA Web Camera - HD                  | 19        | 0.99%   |
| Logitech HD Pro Webcam C920                      | 18        | 0.93%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.93%   |
| Chicony HP Truevision HD                         | 18        | 0.93%   |
| Apple iPhone5/5C/5S/6                            | 18        | 0.93%   |
| Suyin HP TrueVision HD                           | 17        | 0.88%   |
| Acer Lenovo EasyCamera                           | 17        | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 16        | 0.83%   |
| Apple Built-in iSight                            | 16        | 0.83%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 15        | 0.78%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.78%   |
| Microdia Integrated Webcam                       | 14        | 0.73%   |
| Lite-On Integrated Camera                        | 14        | 0.73%   |
| IMC Networks UVC VGA Webcam                      | 13        | 0.67%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.62%   |
| Suyin Acer CrystalEye Webcam                     | 12        | 0.62%   |
| Sunplus HD WebCam                                | 12        | 0.62%   |
| Quanta HP Webcam                                 | 12        | 0.62%   |
| Acer SunplusIT Integrated Camera                 | 12        | 0.62%   |
| Acer BisonCam, NB Pro                            | 12        | 0.62%   |
| Microdia USB 2.0 Camera                          | 11        | 0.57%   |
| Lite-On HP HD Camera                             | 11        | 0.57%   |
| Chicony HP HD Camera                             | 11        | 0.57%   |
| Acer HD Webcam                                   | 11        | 0.57%   |
| Syntek Integrated Camera                         | 10        | 0.52%   |
| Quanta HP TrueVision HD Camera                   | 10        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 120       | 37.38%  |
| Synaptics                  | 62        | 19.31%  |
| AuthenTec                  | 52        | 16.2%   |
| Upek                       | 28        | 8.72%   |
| Shenzhen Goodix Technology | 19        | 5.92%   |
| STMicroelectronics         | 18        | 5.61%   |
| LighTuning Technology      | 11        | 3.43%   |
| Elan Microelectronics      | 8         | 2.49%   |
| Samsung Electronics        | 2         | 0.62%   |
| DigitalPersona             | 1         | 0.31%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 28        | 8.72%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 8.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 25        | 7.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 21        | 6.54%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 5.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 4.36%   |
| AuthenTec AES2810                                                          | 14        | 4.36%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 4.05%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 3.74%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.43%   |
| Validity Sensors VFS491                                                    | 11        | 3.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 3.12%   |
| Unknown                                                                    | 9         | 2.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.49%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.49%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.49%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.18%   |
| AuthenTec AES1600                                                          | 7         | 2.18%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.87%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 1.87%   |
| Elan ELAN:Fingerprint                                                      | 6         | 1.87%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.25%   |
| Synaptics  WBDI                                                            | 4         | 1.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.93%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.93%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.93%   |
| LighTuning Fingerprint Reader                                              | 3         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.93%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.62%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.62%   |
| Synaptics WBDI Device                                                      | 2         | 0.62%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.62%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.62%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.31%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.31%   |
| Samsung Fingerprint Device                                                 | 1         | 0.31%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 61        | 34.27%  |
| Alcor Micro               | 46        | 25.84%  |
| O2 Micro                  | 27        | 15.17%  |
| Upek                      | 15        | 8.43%   |
| Lenovo                    | 15        | 8.43%   |
| OmniKey                   | 3         | 1.69%   |
| Reiner SCT Kartensysteme  | 2         | 1.12%   |
| Gemalto (was Gemplus)     | 2         | 1.12%   |
| In Focus Systems          | 1         | 0.56%   |
| Fujitsu Siemens Computers | 1         | 0.56%   |
| Chicony Electronics       | 1         | 0.56%   |
| Cherry                    | 1         | 0.56%   |
| C3PO                      | 1         | 0.56%   |
| Aktiv                     | 1         | 0.56%   |
| Advanced Card Systems     | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 46        | 25.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 28        | 15.73%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 11.8%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 15        | 8.43%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 7.87%   |
| Broadcom 5880                                                                | 14        | 7.87%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 5.06%   |
| Broadcom 58200                                                               | 9         | 5.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 6         | 3.37%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.12%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.56%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 1         | 0.56%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.56%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.56%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.56%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.56%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.56%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.56%   |
| Aktiv Rutoken lite                                                           | 1         | 0.56%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2769      | 73.58%  |
| 1     | 789       | 20.97%  |
| 2     | 165       | 4.38%   |
| 3     | 24        | 0.64%   |
| 4     | 11        | 0.29%   |
| 5     | 3         | 0.08%   |
| 10    | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 320       | 26.96%  |
| Graphics card            | 245       | 20.64%  |
| Chipcard                 | 170       | 14.32%  |
| Net/wireless             | 136       | 11.46%  |
| Communication controller | 51        | 4.3%    |
| Modem                    | 47        | 3.96%   |
| Camera                   | 35        | 2.95%   |
| Multimedia controller    | 33        | 2.78%   |
| Unassigned class         | 25        | 2.11%   |
| Bluetooth                | 25        | 2.11%   |
| Storage                  | 22        | 1.85%   |
| Sound                    | 21        | 1.77%   |
| Card reader              | 19        | 1.6%    |
| Flash memory             | 16        | 1.35%   |
| Network                  | 8         | 0.67%   |
| Net/ethernet             | 6         | 0.51%   |
| Dvb card                 | 3         | 0.25%   |
| Storage/raid             | 2         | 0.17%   |
| Video                    | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |
| Firewire controller      | 1         | 0.08%   |

