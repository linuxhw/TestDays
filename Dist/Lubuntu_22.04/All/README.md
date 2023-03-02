Lubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Lubuntu_22.04/Notebook/README.md).

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

Total: 264

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [1406a26a6e](https://linux-hardware.org/?probe=1406a26a6e) | Apr 27, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [6dd79c7d6a](https://linux-hardware.org/?probe=6dd79c7d6a) | Apr 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [727b677ecb](https://linux-hardware.org/?probe=727b677ecb) | Apr 26, 2022 |
| Dell          | Latitude 7480               | Notebook    | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | Notebook    | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Intel         | W7650                       | Notebook    | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Intel         | W7650                       | Notebook    | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-43-generic           | 35        | 16.51%  |
| 5.15.0-56-generic           | 17        | 8.02%   |
| 5.15.0-25-generic           | 13        | 6.13%   |
| 5.15.0-47-generic           | 12        | 5.66%   |
| 5.15.0-58-generic           | 11        | 5.19%   |
| 5.15.0-60-generic           | 10        | 4.72%   |
| 5.15.0-30-generic           | 10        | 4.72%   |
| 5.15.0-46-generic           | 9         | 4.25%   |
| 5.15.0-41-generic           | 9         | 4.25%   |
| 5.15.0-27-generic           | 9         | 4.25%   |
| 5.15.0-53-generic           | 8         | 3.77%   |
| 5.15.0-52-generic           | 8         | 3.77%   |
| 5.15.0-50-generic           | 6         | 2.83%   |
| 5.15.0-48-generic           | 6         | 2.83%   |
| 5.15.0-40-generic           | 6         | 2.83%   |
| 5.15.0-57-generic           | 5         | 2.36%   |
| 5.15.0-39-generic           | 4         | 1.89%   |
| 5.15.0-35-generic           | 4         | 1.89%   |
| 5.15.0-33-generic           | 4         | 1.89%   |
| 5.19.0-32-generic           | 2         | 0.94%   |
| 5.15.0-37-generic           | 2         | 0.94%   |
| 5.15.0-23-generic           | 2         | 0.94%   |
| 5.15.0-18-generic           | 2         | 0.94%   |
| 6.1.12-060112-generic       | 1         | 0.47%   |
| 6.1.0-custom                | 1         | 0.47%   |
| 6.0.8-060008-generic        | 1         | 0.47%   |
| 6.0.12-x64v2-xanmod1        | 1         | 0.47%   |
| 6.0.10-rockchip64           | 1         | 0.47%   |
| 5.19.8-xanmod1              | 1         | 0.47%   |
| 5.19.11-ux360cak            | 1         | 0.47%   |
| 5.19.0-16.2-liquorix-amd64  | 1         | 0.47%   |
| 5.19.0-051900-generic       | 1         | 0.47%   |
| 5.18.0-051800-generic       | 1         | 0.47%   |
| 5.15.0-59-lowlatency        | 1         | 0.47%   |
| 5.15.0-58-lowlatency        | 1         | 0.47%   |
| 5.15.0-54-generic           | 1         | 0.47%   |
| 5.15.0-41-lowlatency        | 1         | 0.47%   |
| 5.15.0-362206031516-generic | 1         | 0.47%   |
| 5.15.0-28-generic           | 1         | 0.47%   |
| 5.15.0-1017-raspi           | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 188       | 93.53%  |
| 5.19.0  | 4         | 1.99%   |
| 6.1.12  | 1         | 0.5%    |
| 6.1.0   | 1         | 0.5%    |
| 6.0.8   | 1         | 0.5%    |
| 6.0.12  | 1         | 0.5%    |
| 6.0.10  | 1         | 0.5%    |
| 5.19.8  | 1         | 0.5%    |
| 5.19.11 | 1         | 0.5%    |
| 5.18.0  | 1         | 0.5%    |
| 5.14.0  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 188       | 93.53%  |
| 5.19    | 6         | 2.99%   |
| 6.0     | 3         | 1.49%   |
| 6.1     | 2         | 1%      |
| 5.18    | 1         | 0.5%    |
| 5.14    | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 195       | 98.98%  |
| aarch64 | 2         | 1.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 188       | 94.95%  |
| LXDE       | 5         | 2.53%   |
| X-Cinnamon | 2         | 1.01%   |
| GNOME      | 2         | 1.01%   |
| XFCE       | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 190       | 95.48%  |
| Tty         | 6         | 3.02%   |
| Wayland     | 2         | 1.01%   |
| Unspecified | 1         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 169       | 84.92%  |
| Unknown | 12        | 6.03%   |
| LightDM | 11        | 5.53%   |
| GDM3    | 4         | 2.01%   |
| XDM     | 1         | 0.5%    |
| SLiM    | 1         | 0.5%    |
| LXDM    | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 54        | 27.27%  |
| fr_FR  | 21        | 10.61%  |
| it_IT  | 16        | 8.08%   |
| de_DE  | 14        | 7.07%   |
| en_GB  | 10        | 5.05%   |
| C      | 10        | 5.05%   |
| pt_BR  | 8         | 4.04%   |
| pl_PL  | 8         | 4.04%   |
| en_AG  | 8         | 4.04%   |
| es_ES  | 6         | 3.03%   |
| nl_BE  | 4         | 2.02%   |
| es_CR  | 4         | 2.02%   |
| es_AR  | 4         | 2.02%   |
| ru_RU  | 3         | 1.52%   |
| es_MX  | 3         | 1.52%   |
| en_AU  | 3         | 1.52%   |
| tr_TR  | 2         | 1.01%   |
| en_CA  | 2         | 1.01%   |
| el_GR  | 2         | 1.01%   |
| sv_SE  | 1         | 0.51%   |
| ru_UA  | 1         | 0.51%   |
| lzh_TW | 1         | 0.51%   |
| ja_JP  | 1         | 0.51%   |
| hu_HU  | 1         | 0.51%   |
| fr_CA  | 1         | 0.51%   |
| fi_FI  | 1         | 0.51%   |
| es_EC  | 1         | 0.51%   |
| es_CO  | 1         | 0.51%   |
| es_CL  | 1         | 0.51%   |
| en_ZA  | 1         | 0.51%   |
| en_PH  | 1         | 0.51%   |
| en_DE  | 1         | 0.51%   |
| cv_RU  | 1         | 0.51%   |
| cs_CZ  | 1         | 0.51%   |
| aa_DJ  | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 129       | 65.15%  |
| EFI  | 69        | 34.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 182       | 91.46%  |
| Overlay | 12        | 6.03%   |
| Btrfs   | 3         | 1.51%   |
| XXX4    | 1         | 0.5%    |
| Ext2    | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 92        | 46%     |
| MBR     | 59        | 29.5%   |
| Unknown | 49        | 24.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 88.89%  |
| Yes       | 22        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 69.19%  |
| Yes       | 61        | 30.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 31        | 15.74%  |
| Dell                    | 23        | 11.68%  |
| ASUSTek Computer        | 22        | 11.17%  |
| Hewlett-Packard         | 20        | 10.15%  |
| Acer                    | 15        | 7.61%   |
| MSI                     | 12        | 6.09%   |
| Google                  | 6         | 3.05%   |
| Apple                   | 6         | 3.05%   |
| Unknown                 | 6         | 3.05%   |
| Fujitsu                 | 5         | 2.54%   |
| ASRock                  | 5         | 2.54%   |
| Intel                   | 4         | 2.03%   |
| AMI                     | 4         | 2.03%   |
| Sony                    | 3         | 1.52%   |
| Positivo                | 3         | 1.52%   |
| Gigabyte Technology     | 3         | 1.52%   |
| Toshiba                 | 2         | 1.02%   |
| Pegatron                | 2         | 1.02%   |
| OEM                     | 2         | 1.02%   |
| Mediacom                | 2         | 1.02%   |
| Gateway                 | 2         | 1.02%   |
| ZOTAC                   | 1         | 0.51%   |
| Thomson                 | 1         | 0.51%   |
| SGIN                    | 1         | 0.51%   |
| Samsung Electronics     | 1         | 0.51%   |
| Rockchip                | 1         | 0.51%   |
| Raspberry Pi Foundation | 1         | 0.51%   |
| Pretech                 | 1         | 0.51%   |
| Prestigio               | 1         | 0.51%   |
| Packard Bell            | 1         | 0.51%   |
| NEC Computers           | 1         | 0.51%   |
| Kiano                   | 1         | 0.51%   |
| IFSA                    | 1         | 0.51%   |
| HUAWEI                  | 1         | 0.51%   |
| GPU Company             | 1         | 0.51%   |
| Getac                   | 1         | 0.51%   |
| Fujitsu Siemens         | 1         | 0.51%   |
| ECS                     | 1         | 0.51%   |
| Chuwi                   | 1         | 0.51%   |
| Alienware               | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 3.55%   |
| Apple MacBookPro8,1                        | 3         | 1.52%   |
| MSI MS-7C37                                | 2         | 1.02%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.02%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.02%   |
| Lenovo G50-30 80G0                         | 2         | 1.02%   |
| HP Pavilion g6                             | 2         | 1.02%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.02%   |
| Dell Dimension 9100                        | 2         | 1.02%   |
| ZOTAC NM10                                 | 1         | 0.51%   |
| Toshiba Satellite Pro S500                 | 1         | 0.51%   |
| Toshiba Satellite L40                      | 1         | 0.51%   |
| Thomson N14C4WH64                          | 1         | 0.51%   |
| Sony VPCEB15FM                             | 1         | 0.51%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.51%   |
| Sony SVE14A2V1EW                           | 1         | 0.51%   |
| SGIN laptop                                | 1         | 0.51%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.51%   |
| Rockchip RK3318 BOX                        | 1         | 0.51%   |
| RPi Raspberry Pi                           | 1         | 0.51%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.51%   |
| Prestigio PSB141C01BFH                     | 1         | 0.51%   |
| Positivo Q232A                             | 1         | 0.51%   |
| Positivo POS-AG31AP                        | 1         | 0.51%   |
| Positivo i500pro                           | 1         | 0.51%   |
| Pegatron h8-1350ef                         | 1         | 0.51%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.51%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.51%   |
| OEM M882CWP                                | 1         | 0.51%   |
| NEC Computers ECS-945G                     | 1         | 0.51%   |
| MSI MS-7D09                                | 1         | 0.51%   |
| MSI MS-7C96                                | 1         | 0.51%   |
| MSI MS-7C56                                | 1         | 0.51%   |
| MSI MS-7C51                                | 1         | 0.51%   |
| MSI MS-7B86                                | 1         | 0.51%   |
| MSI MS-7978                                | 1         | 0.51%   |
| MSI MS-7641                                | 1         | 0.51%   |
| MSI MS-7501                                | 1         | 0.51%   |
| MSI MS-7267                                | 1         | 0.51%   |
| MSI MS-7032                                | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 4.57%   |
| Lenovo IdeaPad         | 9         | 4.57%   |
| Acer Aspire            | 9         | 4.57%   |
| Dell Latitude          | 7         | 3.55%   |
| Unknown                | 7         | 3.55%   |
| HP Pavilion            | 5         | 2.54%   |
| Fujitsu LIFEBOOK       | 4         | 2.03%   |
| HP ProBook             | 3         | 1.52%   |
| Dell Vostro            | 3         | 1.52%   |
| Dell OptiPlex          | 3         | 1.52%   |
| Apple MacBookPro8      | 3         | 1.52%   |
| Toshiba Satellite      | 2         | 1.02%   |
| MSI MS-7C37            | 2         | 1.02%   |
| Mediacom WinPad        | 2         | 1.02%   |
| Lenovo ThinkCentre     | 2         | 1.02%   |
| Lenovo G50-30          | 2         | 1.02%   |
| HP Compaq              | 2         | 1.02%   |
| Dell XPS               | 2         | 1.02%   |
| Dell Studio            | 2         | 1.02%   |
| Dell Precision         | 2         | 1.02%   |
| Dell Dimension         | 2         | 1.02%   |
| ASUS PRIME             | 2         | 1.02%   |
| ZOTAC NM10             | 1         | 0.51%   |
| Thomson N14C4WH64      | 1         | 0.51%   |
| Sony VPCEB15FM         | 1         | 0.51%   |
| Sony VGN-SZ71WN        | 1         | 0.51%   |
| Sony SVE14A2V1EW       | 1         | 0.51%   |
| SGIN laptop            | 1         | 0.51%   |
| Samsung 300V3A         | 1         | 0.51%   |
| Rockchip RK3318        | 1         | 0.51%   |
| RPi Raspberry          | 1         | 0.51%   |
| Pretech EVE            | 1         | 0.51%   |
| Prestigio PSB141C01BFH | 1         | 0.51%   |
| Positivo Q232A         | 1         | 0.51%   |
| Positivo POS-AG31AP    | 1         | 0.51%   |
| Positivo i500pro       | 1         | 0.51%   |
| Pegatron h8-1350ef     | 1         | 0.51%   |
| Pegatron AY748AA-ABA   | 1         | 0.51%   |
| Packard Bell EasyNote  | 1         | 0.51%   |
| OEM M882CWP            | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 23        | 11.68%  |
| 2019    | 15        | 7.61%   |
| 2021    | 14        | 7.11%   |
| 2014    | 14        | 7.11%   |
| 2013    | 14        | 7.11%   |
| 2020    | 13        | 6.6%    |
| 2015    | 13        | 6.6%    |
| 2008    | 13        | 6.6%    |
| 2012    | 12        | 6.09%   |
| 2016    | 11        | 5.58%   |
| 2010    | 11        | 5.58%   |
| 2009    | 11        | 5.58%   |
| 2017    | 8         | 4.06%   |
| 2007    | 8         | 4.06%   |
| 2022    | 7         | 3.55%   |
| 2018    | 5         | 2.54%   |
| 2006    | 2         | 1.02%   |
| Unknown | 2         | 1.02%   |
| 2001    | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 121       | 61.42%  |
| Desktop        | 62        | 31.47%  |
| Convertible    | 5         | 2.54%   |
| Tablet         | 3         | 1.52%   |
| Mini pc        | 3         | 1.52%   |
| System on chip | 2         | 1.02%   |
| All in one     | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 190       | 96.45%  |
| Enabled  | 7         | 3.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 190       | 96.45%  |
| Yes  | 7         | 3.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 70        | 35.35%  |
| 4.01-8.0    | 44        | 22.22%  |
| 8.01-16.0   | 24        | 12.12%  |
| 1.01-2.0    | 23        | 11.62%  |
| 16.01-24.0  | 18        | 9.09%   |
| 32.01-64.0  | 9         | 4.55%   |
| 2.01-3.0    | 6         | 3.03%   |
| 0.51-1.0    | 3         | 1.52%   |
| 64.01-256.0 | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 97        | 47.32%  |
| 0.51-1.0  | 49        | 23.9%   |
| 2.01-3.0  | 39        | 19.02%  |
| 4.01-8.0  | 10        | 4.88%   |
| 3.01-4.0  | 8         | 3.9%    |
| 8.01-16.0 | 1         | 0.49%   |
| 0.01-0.5  | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 69.35%  |
| 2      | 46        | 23.12%  |
| 3      | 5         | 2.51%   |
| 0      | 4         | 2.01%   |
| 5      | 2         | 1.01%   |
| 4      | 2         | 1.01%   |
| 7      | 1         | 0.5%    |
| 6      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 58.88%  |
| Yes       | 81        | 41.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 79.7%   |
| No        | 40        | 20.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 74.62%  |
| No        | 50        | 25.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 52.02%  |
| No        | 95        | 47.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 33        | 16.75%  |
| France       | 22        | 11.17%  |
| Germany      | 20        | 10.15%  |
| Italy        | 18        | 9.14%   |
| Poland       | 11        | 5.58%   |
| Brazil       | 9         | 4.57%   |
| UK           | 7         | 3.55%   |
| Spain        | 7         | 3.55%   |
| Russia       | 6         | 3.05%   |
| Belgium      | 6         | 3.05%   |
| Costa Rica   | 5         | 2.54%   |
| Ukraine      | 4         | 2.03%   |
| Canada       | 4         | 2.03%   |
| Argentina    | 4         | 2.03%   |
| Turkey       | 3         | 1.52%   |
| Mexico       | 3         | 1.52%   |
| Indonesia    | 3         | 1.52%   |
| Australia    | 3         | 1.52%   |
| Vietnam      | 2         | 1.02%   |
| Sweden       | 2         | 1.02%   |
| Latvia       | 2         | 1.02%   |
| Hungary      | 2         | 1.02%   |
| Greece       | 2         | 1.02%   |
| Thailand     | 1         | 0.51%   |
| Taiwan       | 1         | 0.51%   |
| South Africa | 1         | 0.51%   |
| Saudi Arabia | 1         | 0.51%   |
| Romania      | 1         | 0.51%   |
| Portugal     | 1         | 0.51%   |
| Philippines  | 1         | 0.51%   |
| Netherlands  | 1         | 0.51%   |
| Kenya        | 1         | 0.51%   |
| Japan        | 1         | 0.51%   |
| Ireland      | 1         | 0.51%   |
| Finland      | 1         | 0.51%   |
| Ecuador      | 1         | 0.51%   |
| Czechia      | 1         | 0.51%   |
| Colombia     | 1         | 0.51%   |
| Chile        | 1         | 0.51%   |
| Bulgaria     | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 7         | 3.45%   |
| Heredia          | 4         | 1.97%   |
| Melbourne        | 3         | 1.48%   |
| Kyiv             | 3         | 1.48%   |
| Ghent            | 3         | 1.48%   |
| Warsaw           | 2         | 0.99%   |
| Sarospatak       | 2         | 0.99%   |
| Porto Alegre     | 2         | 0.99%   |
| Novo Gama        | 2         | 0.99%   |
| Milan            | 2         | 0.99%   |
| Largo            | 2         | 0.99%   |
| Jakarta          | 2         | 0.99%   |
| Chicago          | 2         | 0.99%   |
| Zizur Mayor      | 1         | 0.49%   |
| Zawiercie        | 1         | 0.49%   |
| Yoshkar-Ola      | 1         | 0.49%   |
| Yorkville        | 1         | 0.49%   |
| Yerevan          | 1         | 0.49%   |
| Yekaterinburg    | 1         | 0.49%   |
| Wolfhagen        | 1         | 0.49%   |
| Wetteren         | 1         | 0.49%   |
| West Stockbridge | 1         | 0.49%   |
| Washington       | 1         | 0.49%   |
| Warendorf        | 1         | 0.49%   |
| Volzhskiy        | 1         | 0.49%   |
| Versailles       | 1         | 0.49%   |
| Verona           | 1         | 0.49%   |
| Varna            | 1         | 0.49%   |
| Valentigney      | 1         | 0.49%   |
| Valencia         | 1         | 0.49%   |
| Uberlândia      | 1         | 0.49%   |
| Tyler            | 1         | 0.49%   |
| Tychy            | 1         | 0.49%   |
| Turin            | 1         | 0.49%   |
| Thornton Heath   | 1         | 0.49%   |
| Thessaloniki     | 1         | 0.49%   |
| Texas City       | 1         | 0.49%   |
| Taylorsville     | 1         | 0.49%   |
| Tandil           | 1         | 0.49%   |
| Taipei           | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 37        | 45     | 15.04%  |
| WDC                       | 29        | 37     | 11.79%  |
| Unknown                   | 26        | 37     | 10.57%  |
| Samsung Electronics       | 24        | 31     | 9.76%   |
| Toshiba                   | 15        | 16     | 6.1%    |
| Hitachi                   | 13        | 16     | 5.28%   |
| Kingston                  | 12        | 13     | 4.88%   |
| SanDisk                   | 11        | 11     | 4.47%   |
| Crucial                   | 6         | 6      | 2.44%   |
| Micron Technology         | 5         | 6      | 2.03%   |
| HGST                      | 5         | 5      | 2.03%   |
| A-DATA Technology         | 5         | 5      | 2.03%   |
| GOODRAM                   | 4         | 4      | 1.63%   |
| Intel                     | 3         | 4      | 1.22%   |
| Apacer                    | 3         | 3      | 1.22%   |
| Transcend                 | 2         | 2      | 0.81%   |
| SPCC                      | 2         | 3      | 0.81%   |
| SK hynix                  | 2         | 2      | 0.81%   |
| Patriot                   | 2         | 2      | 0.81%   |
| Micron/Crucial Technology | 2         | 2      | 0.81%   |
| Maxtor                    | 2         | 2      | 0.81%   |
| Fujitsu                   | 2         | 2      | 0.81%   |
| Unknown                   | 2         | 2      | 0.81%   |
| WD MediaMax               | 1         | 1      | 0.41%   |
| W800S                     | 1         | 1      | 0.41%   |
| UMIS                      | 1         | 1      | 0.41%   |
| TO Exter                  | 1         | 1      | 0.41%   |
| Teclast                   | 1         | 1      | 0.41%   |
| Team                      | 1         | 1      | 0.41%   |
| T-FORCE                   | 1         | 1      | 0.41%   |
| RSH-319                   | 1         | 1      | 0.41%   |
| Rogueware                 | 1         | 1      | 0.41%   |
| PNY                       | 1         | 1      | 0.41%   |
| Phison                    | 1         | 1      | 0.41%   |
| NGFF                      | 1         | 1      | 0.41%   |
| LITEONIT                  | 1         | 1      | 0.41%   |
| LITEON                    | 1         | 1      | 0.41%   |
| Lexar                     | 1         | 1      | 0.41%   |
| Leqixiang                 | 1         | 1      | 0.41%   |
| Lenovo                    | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 6         | 2.23%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 2.23%   |
| Seagate ST9500325AS 500GB          | 5         | 1.86%   |
| Unknown MMC Card  32GB             | 4         | 1.49%   |
| SanDisk DF4032  32GB               | 4         | 1.49%   |
| Kingston SA400S37240G 240GB SSD    | 4         | 1.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 0.74%   |
| Unknown SD/MMC/MS PRO 16GB         | 2         | 0.74%   |
| Unknown SC64G  64GB                | 2         | 0.74%   |
| Unknown NCard  32GB                | 2         | 0.74%   |
| Unknown MMC64G  64GB               | 2         | 0.74%   |
| Unknown DA4032  32GB               | 2         | 0.74%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.74%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.74%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.74%   |
| SPCC Solid State Disk 120GB        | 2         | 0.74%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.74%   |
| Seagate ST3120213AS 120GB          | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.74%   |
| SanDisk DF4064  64GB               | 2         | 0.74%   |
| Samsung SSD 870 EVO 500GB          | 2         | 0.74%   |
| Samsung SSD 860 EVO 500GB          | 2         | 0.74%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.74%   |
| Samsung HD502HJ 500GB              | 2         | 0.74%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.74%   |
| Crucial CT500P3SSD8 500GB          | 2         | 0.74%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.74%   |
| Apacer 16GB SATA Flash Drive SSD   | 2         | 0.74%   |
| Unknown                            | 2         | 0.74%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.37%   |
| WDC WDS500G2B0A 500GB SSD          | 1         | 0.37%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.37%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1         | 0.37%   |
| WDC WD800BB-00CAA1 80GB            | 1         | 0.37%   |
| WDC WD5000LUCT-63RC2Y0 500GB       | 1         | 0.37%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-21VHAT0 500GB       | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 44     | 33.64%  |
| WDC                 | 25        | 28     | 22.73%  |
| Toshiba             | 13        | 14     | 11.82%  |
| Hitachi             | 13        | 16     | 11.82%  |
| Samsung Electronics | 7         | 11     | 6.36%   |
| HGST                | 5         | 5      | 4.55%   |
| Unknown             | 2         | 2      | 1.82%   |
| Maxtor              | 2         | 2      | 1.82%   |
| Fujitsu             | 2         | 2      | 1.82%   |
| WD MediaMax         | 1         | 1      | 0.91%   |
| RSH-319             | 1         | 1      | 0.91%   |
| External            | 1         | 1      | 0.91%   |
| Apricorn            | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 18.99%  |
| Kingston            | 10        | 11     | 12.66%  |
| A-DATA Technology   | 5         | 5      | 6.33%   |
| SanDisk             | 4         | 4      | 5.06%   |
| GOODRAM             | 4         | 4      | 5.06%   |
| Crucial             | 4         | 4      | 5.06%   |
| WDC                 | 3         | 4      | 3.8%    |
| Micron Technology   | 3         | 3      | 3.8%    |
| Apacer              | 3         | 3      | 3.8%    |
| Transcend           | 2         | 2      | 2.53%   |
| Toshiba             | 2         | 2      | 2.53%   |
| SPCC                | 2         | 3      | 2.53%   |
| Patriot             | 2         | 2      | 2.53%   |
| Intel               | 2         | 2      | 2.53%   |
| W800S               | 1         | 1      | 1.27%   |
| TO Exter            | 1         | 1      | 1.27%   |
| Teclast             | 1         | 1      | 1.27%   |
| Team                | 1         | 1      | 1.27%   |
| Rogueware           | 1         | 1      | 1.27%   |
| PNY                 | 1         | 1      | 1.27%   |
| NGFF                | 1         | 1      | 1.27%   |
| LITEONIT            | 1         | 1      | 1.27%   |
| LITEON              | 1         | 1      | 1.27%   |
| Lexar               | 1         | 1      | 1.27%   |
| Leqixiang           | 1         | 1      | 1.27%   |
| Lenovo              | 1         | 1      | 1.27%   |
| Kston               | 1         | 3      | 1.27%   |
| KINGPOWER           | 1         | 1      | 1.27%   |
| HUSKY               | 1         | 1      | 1.27%   |
| Gigabyte Technology | 1         | 1      | 1.27%   |
| Emtec               | 1         | 1      | 1.27%   |
| 2.5"                | 1         | 2      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 93        | 128    | 40.43%  |
| SSD     | 76        | 86     | 33.04%  |
| MMC     | 32        | 44     | 13.91%  |
| NVMe    | 25        | 29     | 10.87%  |
| Unknown | 4         | 6      | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 208    | 69.3%   |
| MMC  | 32        | 44     | 14.88%  |
| NVMe | 25        | 29     | 11.63%  |
| SAS  | 9         | 12     | 4.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 123       | 154    | 71.51%  |
| 0.51-1.0   | 32        | 39     | 18.6%   |
| 1.01-2.0   | 11        | 13     | 6.4%    |
| 2.01-3.0   | 3         | 4      | 1.74%   |
| 4.01-10.0  | 2         | 3      | 1.16%   |
| 3.01-4.0   | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 64        | 32%     |
| 251-500        | 45        | 22.5%   |
| 51-100         | 22        | 11%     |
| 1-20           | 18        | 9%      |
| 21-50          | 16        | 8%      |
| 501-1000       | 15        | 7.5%    |
| 1001-2000      | 9         | 4.5%    |
| More than 3000 | 5         | 2.5%    |
| 2001-3000      | 5         | 2.5%    |
| Unknown        | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 106       | 52.48%  |
| 21-50          | 36        | 17.82%  |
| 51-100         | 20        | 9.9%    |
| 101-250        | 16        | 7.92%   |
| 501-1000       | 8         | 3.96%   |
| 251-500        | 7         | 3.47%   |
| More than 3000 | 4         | 1.98%   |
| 1001-2000      | 3         | 1.49%   |
| 2001-3000      | 1         | 0.5%    |
| Unknown        | 1         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 6.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 2      | 6.67%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 6.67%   |
| WDC WD3200AACS-00M6B0 320GB               | 1         | 1      | 3.33%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 3.33%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 3.33%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 3.33%   |
| WDC WD10EACS-00D6B1 1TB                   | 1         | 1      | 3.33%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 3.33%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 3.33%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 3.33%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 3.33%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 3.33%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 3.33%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 3.33%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 3.33%   |
| Samsung Electronics HM121HI 120GB         | 1         | 4      | 3.33%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 3.33%   |
| NGFF 2280 512GB SSD                       | 1         | 1      | 3.33%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 3.33%   |
| Maxtor 6L200M0 208GB                      | 1         | 1      | 3.33%   |
| Hitachi HTS722080K9SA00 80GB              | 1         | 1      | 3.33%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 3.33%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 3.33%   |
| A-DATA Technology SP920SS 256GB SSD       | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 36.67%  |
| WDC                 | 5         | 5      | 16.67%  |
| Toshiba             | 3         | 3      | 10%     |
| Samsung Electronics | 2         | 5      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| Apacer              | 2         | 2      | 6.67%   |
| NGFF                | 1         | 1      | 3.33%   |
| Micron Technology   | 1         | 1      | 3.33%   |
| Maxtor              | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 44%     |
| WDC                 | 5         | 5      | 20%     |
| Toshiba             | 3         | 3      | 12%     |
| Samsung Electronics | 2         | 5      | 8%      |
| Hitachi             | 2         | 2      | 8%      |
| Maxtor              | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 28     | 83.33%  |
| SSD  | 5         | 5      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 108       | 164    | 51.92%  |
| Works    | 67        | 93     | 32.21%  |
| Malfunc  | 30        | 33     | 14.42%  |
| Failed   | 3         | 3      | 1.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 125       | 62.81%  |
| AMD                              | 36        | 18.09%  |
| Nvidia                           | 6         | 3.02%   |
| SanDisk                          | 4         | 2.01%   |
| Samsung Electronics              | 4         | 2.01%   |
| Micron/Crucial Technology        | 4         | 2.01%   |
| Micron Technology                | 3         | 1.51%   |
| JMicron Technology               | 3         | 1.51%   |
| SK hynix                         | 2         | 1.01%   |
| Kingston Technology Company      | 2         | 1.01%   |
| ASMedia Technology               | 2         | 1.01%   |
| VIA Technologies                 | 1         | 0.5%    |
| Union Memory (Shenzhen)          | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] | 1         | 0.5%    |
| Silicon Image                    | 1         | 0.5%    |
| Seagate Technology               | 1         | 0.5%    |
| Phison Electronics               | 1         | 0.5%    |
| Marvell Technology Group         | 1         | 0.5%    |
| KIOXIA                           | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 7.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 5.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 4.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 4.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 3.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 2.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 2.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 2.06%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.23%   |
| Micron Non-Volatile memory controller                                            | 3         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 1.23%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.23%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.82%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 2         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.82%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 2         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.82%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 2         | 0.82%   |
| AMD FCH SATA Controller [IDE mode]                                               | 2         | 0.82%   |
| AMD FCH IDE Controller                                                           | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 139       | 64.95%  |
| IDE  | 41        | 19.16%  |
| NVMe | 24        | 11.21%  |
| RAID | 10        | 4.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 154       | 78.17%  |
| AMD    | 41        | 20.81%  |
| ARM    | 2         | 1.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 3.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 2.54%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 2.03%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 2.03%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.52%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.52%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 3         | 1.52%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 2         | 1.02%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 1.02%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.02%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.02%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.02%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.02%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.02%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1.02%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.02%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.02%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.02%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 2         | 1.02%   |
| ARM Processor                                 | 2         | 1.02%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.02%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 1.02%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 2         | 1.02%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.02%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.51%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1         | 0.51%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.51%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.51%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.51%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.51%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.51%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.51%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 31        | 15.74%  |
| Intel Core i5           | 30        | 15.23%  |
| Intel Atom              | 19        | 9.64%   |
| Intel Core 2 Duo        | 18        | 9.14%   |
| Intel Core i3           | 17        | 8.63%   |
| Intel Core i7           | 15        | 7.61%   |
| Intel Pentium           | 8         | 4.06%   |
| AMD Ryzen 5             | 6         | 3.05%   |
| AMD Ryzen 7             | 5         | 2.54%   |
| Other                   | 4         | 2.03%   |
| Intel Pentium Dual      | 4         | 2.03%   |
| AMD FX                  | 3         | 1.52%   |
| AMD A8                  | 3         | 1.52%   |
| AMD A6                  | 3         | 1.52%   |
| Intel Xeon              | 2         | 1.02%   |
| Intel Pentium D         | 2         | 1.02%   |
| Intel Core 2 Quad       | 2         | 1.02%   |
| Intel Core 2            | 2         | 1.02%   |
| AMD Phenom II X4        | 2         | 1.02%   |
| AMD E1                  | 2         | 1.02%   |
| AMD E                   | 2         | 1.02%   |
| AMD Athlon 64 X2        | 2         | 1.02%   |
| Intel Pentium Dual-Core | 1         | 0.51%   |
| Intel Core m3           | 1         | 0.51%   |
| Intel Core i9           | 1         | 0.51%   |
| AMD Ryzen 9             | 1         | 0.51%   |
| AMD Ryzen 7 PRO         | 1         | 0.51%   |
| AMD Ryzen 5 PRO         | 1         | 0.51%   |
| AMD Phenom II X6        | 1         | 0.51%   |
| AMD GX                  | 1         | 0.51%   |
| AMD G                   | 1         | 0.51%   |
| AMD C-60                | 1         | 0.51%   |
| AMD Athlon II X3        | 1         | 0.51%   |
| AMD Athlon II X2        | 1         | 0.51%   |
| AMD Athlon              | 1         | 0.51%   |
| AMD A4                  | 1         | 0.51%   |
| AMD A10                 | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 113       | 57.36%  |
| 4       | 59        | 29.95%  |
| 8       | 7         | 3.55%   |
| 6       | 7         | 3.55%   |
| 1       | 6         | 3.05%   |
| 3       | 3         | 1.52%   |
| 10      | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 196       | 99.49%  |
| Unknown | 1         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 112       | 56.85%  |
| 2       | 84        | 42.64%  |
| Unknown | 1         | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 99.49%  |
| 64-bit         | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 40.91%  |
| 0x406c4    | 10        | 5.05%   |
| 0x206a7    | 10        | 5.05%   |
| 0x306a9    | 7         | 3.54%   |
| 0x1067a    | 7         | 3.54%   |
| 0x806ec    | 4         | 2.02%   |
| 0x706e5    | 4         | 2.02%   |
| 0x706a8    | 4         | 2.02%   |
| 0x6fd      | 4         | 2.02%   |
| 0x406c3    | 4         | 2.02%   |
| 0x40651    | 3         | 1.52%   |
| 0x306c3    | 3         | 1.52%   |
| 0x30678    | 3         | 1.52%   |
| 0x20655    | 3         | 1.52%   |
| 0x106ca    | 3         | 1.52%   |
| 0x0a50000c | 3         | 1.52%   |
| 0x05000119 | 3         | 1.52%   |
| 0x906c0    | 2         | 1.01%   |
| 0x806ea    | 2         | 1.01%   |
| 0x806e9    | 2         | 1.01%   |
| 0x6fb      | 2         | 1.01%   |
| 0x506e3    | 2         | 1.01%   |
| 0x0700010f | 2         | 1.01%   |
| 0x06006705 | 2         | 1.01%   |
| 0x06001119 | 2         | 1.01%   |
| 0x010000db | 2         | 1.01%   |
| 0xa0653    | 1         | 0.51%   |
| 0x906ed    | 1         | 0.51%   |
| 0x906ea    | 1         | 0.51%   |
| 0x806eb    | 1         | 0.51%   |
| 0x806c1    | 1         | 0.51%   |
| 0x706a1    | 1         | 0.51%   |
| 0x6fa      | 1         | 0.51%   |
| 0x6f6      | 1         | 0.51%   |
| 0x506c9    | 1         | 0.51%   |
| 0x406e3    | 1         | 0.51%   |
| 0x30679    | 1         | 0.51%   |
| 0x106a5    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x0a50000b | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 31        | 15.74%  |
| SandyBridge   | 19        | 9.64%   |
| Penryn        | 15        | 7.61%   |
| Core          | 13        | 6.6%    |
| KabyLake      | 12        | 6.09%   |
| IvyBridge     | 11        | 5.58%   |
| Haswell       | 10        | 5.08%   |
| Goldmont plus | 9         | 4.57%   |
| Zen 3         | 6         | 3.05%   |
| Westmere      | 6         | 3.05%   |
| Piledriver    | 6         | 3.05%   |
| Skylake       | 5         | 2.54%   |
| K10           | 5         | 2.54%   |
| Bonnell       | 5         | 2.54%   |
| IceLake       | 4         | 2.03%   |
| Bobcat        | 4         | 2.03%   |
| Zen+          | 3         | 1.52%   |
| Zen           | 3         | 1.52%   |
| K8 Hammer     | 3         | 1.52%   |
| Broadwell     | 3         | 1.52%   |
| Unknown       | 3         | 1.52%   |
| Zen 2         | 2         | 1.02%   |
| Tremont       | 2         | 1.02%   |
| NetBurst      | 2         | 1.02%   |
| Nehalem       | 2         | 1.02%   |
| Jaguar        | 2         | 1.02%   |
| Goldmont      | 2         | 1.02%   |
| Excavator     | 2         | 1.02%   |
| CometLake     | 2         | 1.02%   |
| TigerLake     | 1         | 0.51%   |
| Steamroller   | 1         | 0.51%   |
| Puma          | 1         | 0.51%   |
| K10 Llano     | 1         | 0.51%   |
| Bulldozer     | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 124       | 59.05%  |
| AMD    | 49        | 23.33%  |
| Nvidia | 37        | 17.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 9.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 7.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 4.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 3.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 3.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.76%   |
| Nvidia GT218 [ION]                                                                       | 3         | 1.32%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.32%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.32%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.32%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.88%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.88%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.88%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.88%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.88%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.88%   |
| Intel HD Graphics 500                                                                    | 2         | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.88%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.88%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.88%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.88%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.88%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.88%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.88%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 0.88%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.88%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 109       | 55.33%  |
| 1 x AMD            | 34        | 17.26%  |
| 1 x Nvidia         | 29        | 14.72%  |
| 2 x AMD            | 7         | 3.55%   |
| Intel + Nvidia     | 5         | 2.54%   |
| Intel + AMD        | 5         | 2.54%   |
| Other              | 4         | 2.03%   |
| AMD + Nvidia       | 2         | 1.02%   |
| Intel + 2 x Nvidia | 1         | 0.51%   |
| Intel + 2 x AMD    | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 178       | 90.36%  |
| Proprietary | 11        | 5.58%   |
| Unknown     | 8         | 4.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 77.27%  |
| 0.01-0.5   | 19        | 9.6%    |
| 0.51-1.0   | 7         | 3.54%   |
| 1.01-2.0   | 6         | 3.03%   |
| 7.01-8.0   | 5         | 2.53%   |
| 3.01-4.0   | 3         | 1.52%   |
| 2.01-3.0   | 2         | 1.01%   |
| 8.01-16.0  | 2         | 1.01%   |
| 5.01-6.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 13.68%  |
| Samsung Electronics     | 25        | 13.16%  |
| LG Display              | 23        | 12.11%  |
| Chimei Innolux          | 18        | 9.47%   |
| BOE                     | 15        | 7.89%   |
| Hewlett-Packard         | 8         | 4.21%   |
| Goldstar                | 8         | 4.21%   |
| Dell                    | 8         | 4.21%   |
| Apple                   | 6         | 3.16%   |
| CPT                     | 5         | 2.63%   |
| Philips                 | 4         | 2.11%   |
| Ancor Communications    | 4         | 2.11%   |
| Acer                    | 4         | 2.11%   |
| Lenovo                  | 3         | 1.58%   |
| Eizo                    | 3         | 1.58%   |
| Chi Mei Optoelectronics | 3         | 1.58%   |
| Toshiba                 | 2         | 1.05%   |
| Sharp                   | 2         | 1.05%   |
| LG Philips              | 2         | 1.05%   |
| BenQ                    | 2         | 1.05%   |
| Vizio                   | 1         | 0.53%   |
| ViewSonic               | 1         | 0.53%   |
| VHT                     | 1         | 0.53%   |
| Unknown                 | 1         | 0.53%   |
| Sony                    | 1         | 0.53%   |
| SNC                     | 1         | 0.53%   |
| Sampo                   | 1         | 0.53%   |
| Positivo                | 1         | 0.53%   |
| MSI                     | 1         | 0.53%   |
| LG Electronics          | 1         | 0.53%   |
| JVC                     | 1         | 0.53%   |
| JDI                     | 1         | 0.53%   |
| InfoVision              | 1         | 0.53%   |
| Iiyama                  | 1         | 0.53%   |
| HannStar                | 1         | 0.53%   |
| Daewoo                  | 1         | 0.53%   |
| CS_                     | 1         | 0.53%   |
| Compal                  | 1         | 0.53%   |
| AOC                     | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 4         | 2.09%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 2         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 1.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.05%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.05%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 1.05%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.05%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1         | 0.52%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.52%   |
| VHT Monitor VHTDDDD 1024x768                                          | 1         | 0.52%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.52%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch              | 1         | 0.52%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.52%   |
| Sony TV SNY9C01 1360x768                                              | 1         | 0.52%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1         | 0.52%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.52%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1         | 0.52%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.52%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch    | 1         | 0.52%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch     | 1         | 0.52%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3254 1600x900 367x230mm 17.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 67        | 36.02%  |
| 1920x1080 (FHD)    | 50        | 26.88%  |
| 1280x800 (WXGA)    | 16        | 8.6%    |
| 1600x900 (HD+)     | 12        | 6.45%   |
| 1680x1050 (WSXGA+) | 7         | 3.76%   |
| 1440x900 (WXGA+)   | 6         | 3.23%   |
| 1280x1024 (SXGA)   | 6         | 3.23%   |
| 2560x1440 (QHD)    | 5         | 2.69%   |
| 1360x768           | 3         | 1.61%   |
| 3840x2160 (4K)     | 2         | 1.08%   |
| 2160x1440          | 2         | 1.08%   |
| 800x600            | 1         | 0.54%   |
| 3200x1800 (QHD+)   | 1         | 0.54%   |
| 3000x2000          | 1         | 0.54%   |
| 2560x1600          | 1         | 0.54%   |
| 2560x1080          | 1         | 0.54%   |
| 1920x1200 (WUXGA)  | 1         | 0.54%   |
| 1528x1222          | 1         | 0.54%   |
| 1280x768           | 1         | 0.54%   |
| 1280x720 (HD)      | 1         | 0.54%   |
| 1024x768 (XGA)     | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 41        | 21.69%  |
| 14      | 26        | 13.76%  |
| 13      | 21        | 11.11%  |
| 11      | 13        | 6.88%   |
| 23      | 10        | 5.29%   |
| 17      | 10        | 5.29%   |
| 27      | 8         | 4.23%   |
| 18      | 8         | 4.23%   |
| 19      | 7         | 3.7%    |
| Unknown | 7         | 3.7%    |
| 24      | 6         | 3.17%   |
| 22      | 6         | 3.17%   |
| 21      | 6         | 3.17%   |
| 12      | 5         | 2.65%   |
| 20      | 4         | 2.12%   |
| 10      | 2         | 1.06%   |
| 72      | 1         | 0.53%   |
| 49      | 1         | 0.53%   |
| 47      | 1         | 0.53%   |
| 43      | 1         | 0.53%   |
| 34      | 1         | 0.53%   |
| 28      | 1         | 0.53%   |
| 16      | 1         | 0.53%   |
| 9       | 1         | 0.53%   |
| 8       | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 40.21%  |
| 201-300     | 34        | 17.99%  |
| 401-500     | 29        | 15.34%  |
| 501-600     | 23        | 12.17%  |
| 351-400     | 11        | 5.82%   |
| Unknown     | 7         | 3.7%    |
| 601-700     | 2         | 1.06%   |
| 101-200     | 2         | 1.06%   |
| 1001-1500   | 2         | 1.06%   |
| 701-800     | 1         | 0.53%   |
| 1501-2000   | 1         | 0.53%   |
| 901-1000    | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 131       | 72.78%  |
| 16/10   | 32        | 17.78%  |
| Unknown | 5         | 2.78%   |
| 5/4     | 4         | 2.22%   |
| 4/3     | 4         | 2.22%   |
| 3/2     | 3         | 1.67%   |
| 21/9    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 41        | 21.81%  |
| 101-110        | 40        | 21.28%  |
| 201-250        | 24        | 12.77%  |
| 51-60          | 13        | 6.91%   |
| 151-200        | 13        | 6.91%   |
| 141-150        | 9         | 4.79%   |
| 301-350        | 8         | 4.26%   |
| 121-130        | 7         | 3.72%   |
| Unknown        | 7         | 3.72%   |
| 71-80          | 6         | 3.19%   |
| 61-70          | 5         | 2.66%   |
| 41-50          | 3         | 1.6%    |
| 251-300        | 3         | 1.6%    |
| 501-1000       | 3         | 1.6%    |
| More than 1000 | 2         | 1.06%   |
| 131-140        | 2         | 1.06%   |
| 1-40           | 1         | 0.53%   |
| 111-120        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 68        | 36.76%  |
| 51-100        | 55        | 29.73%  |
| 121-160       | 37        | 20%     |
| 161-240       | 11        | 5.95%   |
| Unknown       | 7         | 3.78%   |
| 1-50          | 5         | 2.7%    |
| More than 240 | 2         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 177       | 89.85%  |
| 2     | 13        | 6.6%    |
| 0     | 6         | 3.05%   |
| 3     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 97        | 34.4%   |
| Intel                           | 71        | 25.18%  |
| Qualcomm Atheros                | 44        | 15.6%   |
| Broadcom                        | 17        | 6.03%   |
| TP-Link                         | 7         | 2.48%   |
| Marvell Technology Group        | 6         | 2.13%   |
| Samsung Electronics             | 5         | 1.77%   |
| Qualcomm Atheros Communications | 4         | 1.42%   |
| Nvidia                          | 4         | 1.42%   |
| MediaTek                        | 4         | 1.42%   |
| Broadcom Limited                | 4         | 1.42%   |
| Ralink                          | 3         | 1.06%   |
| Qualcomm                        | 2         | 0.71%   |
| NetGear                         | 2         | 0.71%   |
| ASIX Electronics                | 2         | 0.71%   |
| VIA Technologies                | 1         | 0.35%   |
| Trident Microsystems            | 1         | 0.35%   |
| Sierra Wireless                 | 1         | 0.35%   |
| Ralink Technology               | 1         | 0.35%   |
| Microsoft                       | 1         | 0.35%   |
| JMicron Technology              | 1         | 0.35%   |
| ICS Advent                      | 1         | 0.35%   |
| Belkin Components               | 1         | 0.35%   |
| ASUSTek Computer                | 1         | 0.35%   |
| Accton Technology               | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 19.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.13%   |
| Intel Wireless 7265                                               | 7         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.82%   |
| Intel Wireless 7260                                               | 6         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.91%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.91%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.91%   |
| Intel Wireless 3160                                               | 3         | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.91%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.91%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.91%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.91%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.61%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 35.63%  |
| Qualcomm Atheros                | 38        | 23.75%  |
| Realtek Semiconductor           | 30        | 18.75%  |
| Broadcom                        | 10        | 6.25%   |
| TP-Link                         | 6         | 3.75%   |
| Qualcomm Atheros Communications | 4         | 2.5%    |
| Ralink                          | 3         | 1.88%   |
| MediaTek                        | 3         | 1.88%   |
| NetGear                         | 2         | 1.25%   |
| Broadcom Limited                | 2         | 1.25%   |
| Sierra Wireless                 | 1         | 0.63%   |
| Ralink Technology               | 1         | 0.63%   |
| Microsoft                       | 1         | 0.63%   |
| Belkin Components               | 1         | 0.63%   |
| ASUSTek Computer                | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 7         | 4.38%   |
| Intel Wireless 7265                                                 | 7         | 4.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6         | 3.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 6         | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 3.75%   |
| Intel Wireless 7260                                                 | 6         | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 5         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 4         | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 4         | 2.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 4         | 2.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 4         | 2.5%    |
| Realtek 802.11n WLAN Adapter                                        | 3         | 1.88%   |
| Qualcomm Atheros AR9271 802.11n                                     | 3         | 1.88%   |
| Intel Wireless 3160                                                 | 3         | 1.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 3         | 1.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 3         | 1.88%   |
| Intel Centrino Wireless-N 2230                                      | 3         | 1.88%   |
| Intel Centrino Advanced-N 6235                                      | 3         | 1.88%   |
| Intel Centrino Advanced-N 6200                                      | 3         | 1.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2         | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.25%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 1.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 2         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 1.25%   |
| NetGear A6210                                                       | 2         | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 2         | 1.25%   |
| Intel Wireless 8260                                                 | 2         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2         | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                      | 2         | 1.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 1.25%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 1.25%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1         | 0.63%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1         | 0.63%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1         | 0.63%   |
| TP-Link 802.11ac NIC                                                | 1         | 0.63%   |
| Sierra Wireless EM7305 Modem                                        | 1         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1         | 0.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 50.6%   |
| Intel                    | 31        | 18.45%  |
| Qualcomm Atheros         | 14        | 8.33%   |
| Broadcom                 | 10        | 5.95%   |
| Marvell Technology Group | 6         | 3.57%   |
| Samsung Electronics      | 5         | 2.98%   |
| Nvidia                   | 4         | 2.38%   |
| Qualcomm                 | 2         | 1.19%   |
| Broadcom Limited         | 2         | 1.19%   |
| ASIX Electronics         | 2         | 1.19%   |
| VIA Technologies         | 1         | 0.6%    |
| Trident Microsystems     | 1         | 0.6%    |
| TP-Link                  | 1         | 0.6%    |
| MediaTek                 | 1         | 0.6%    |
| JMicron Technology       | 1         | 0.6%    |
| ICS Advent               | 1         | 0.6%    |
| Accton Technology        | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 64        | 37.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 7.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 5.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 2.37%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.78%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 1.78%   |
| Intel Ethernet Controller I225-V                                               | 3         | 1.78%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 1.18%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.18%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.18%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2         | 1.18%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.18%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.18%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.59%   |
| Trident Microsystems 4DWave DX                                                 | 1         | 0.59%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.59%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.59%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.59%   |
| Qualcomm Redmi Note 7                                                          | 1         | 0.59%   |
| Qualcomm Redmi 9T                                                              | 1         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.59%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.59%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.59%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.59%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.59%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.59%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 157       | 51.64%  |
| WiFi     | 147       | 48.36%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 57.73%  |
| Ethernet | 82        | 42.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 49.75%  |
| 1     | 77        | 39.09%  |
| 0     | 18        | 9.14%   |
| 3     | 3         | 1.52%   |
| 4     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 151       | 76.26%  |
| Yes  | 47        | 23.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 36.89%  |
| Realtek Semiconductor           | 14        | 13.59%  |
| Qualcomm Atheros Communications | 12        | 11.65%  |
| Broadcom                        | 7         | 6.8%    |
| Foxconn / Hon Hai               | 5         | 4.85%   |
| Apple                           | 5         | 4.85%   |
| Cambridge Silicon Radio         | 4         | 3.88%   |
| Lite-On Technology              | 3         | 2.91%   |
| IMC Networks                    | 3         | 2.91%   |
| Dell                            | 3         | 2.91%   |
| MediaTek                        | 2         | 1.94%   |
| Toshiba                         | 1         | 0.97%   |
| Syntek                          | 1         | 0.97%   |
| Ralink                          | 1         | 0.97%   |
| Logitech                        | 1         | 0.97%   |
| Hewlett-Packard                 | 1         | 0.97%   |
| ASUSTek Computer                | 1         | 0.97%   |
| Alps Electric                   | 1         | 0.97%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 19.42%  |
| Realtek Bluetooth Radio                                                             | 9         | 8.74%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 5.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 4.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.85%   |
| Intel AX201 Bluetooth                                                               | 4         | 3.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.88%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 2.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.91%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.91%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2.91%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.94%   |
| MediaTek Wireless_Device                                                            | 2         | 1.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.94%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.94%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.97%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.97%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.97%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.97%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.97%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.97%   |
| Lite-On Wireless_Device                                                             | 1         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.97%   |
| Intel AX200 Bluetooth                                                               | 1         | 0.97%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.97%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.97%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.97%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.97%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.97%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.97%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.97%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.97%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.97%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 136       | 60.44%  |
| AMD                                          | 46        | 20.44%  |
| Nvidia                                       | 28        | 12.44%  |
| C-Media Electronics                          | 3         | 1.33%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.44%   |
| VIA Technologies                             | 1         | 0.44%   |
| Sony                                         | 1         | 0.44%   |
| Razer USA                                    | 1         | 0.44%   |
| MosArt Semiconductor                         | 1         | 0.44%   |
| Logitech                                     | 1         | 0.44%   |
| JMTek                                        | 1         | 0.44%   |
| Focusrite-Novation                           | 1         | 0.44%   |
| Ensoniq                                      | 1         | 0.44%   |
| EGO SYStems                                  | 1         | 0.44%   |
| Creative Labs                                | 1         | 0.44%   |
| ASUSTek Computer                             | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 6.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 6.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 4.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 4.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 4.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 3.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 3.37%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 3.37%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 3%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 2.62%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 2.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.5%    |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.5%    |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.12%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.75%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 21.48%  |
| Unknown             | 23        | 17.04%  |
| SK hynix            | 22        | 16.3%   |
| Micron Technology   | 19        | 14.07%  |
| Kingston            | 8         | 5.93%   |
| Nanya Technology    | 5         | 3.7%    |
| Elpida              | 5         | 3.7%    |
| G.Skill             | 4         | 2.96%   |
| Corsair             | 4         | 2.96%   |
| Unknown             | 3         | 2.22%   |
| Unknown (ABCD)      | 2         | 1.48%   |
| Smart               | 2         | 1.48%   |
| Transcend           | 1         | 0.74%   |
| Ramaxel Technology  | 1         | 0.74%   |
| Novatech            | 1         | 0.74%   |
| Kllisre             | 1         | 0.74%   |
| HMD                 | 1         | 0.74%   |
| GOODRAM             | 1         | 0.74%   |
| Apacer              | 1         | 0.74%   |
| AMD                 | 1         | 0.74%   |
| A-DATA Technology   | 1         | 0.74%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 2.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.04%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.04%   |
| Unknown                                                          | 3         | 2.04%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.36%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.36%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.36%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.36%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.36%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.36%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.36%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.36%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.36%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.68%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.68%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.68%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.68%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.68%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.68%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.68%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.68%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 0.68%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.68%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.68%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.68%   |
| SK hynix RAM HT5SMRAP 2GB SODIMM DDR3 1600MT/s                   | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 57        | 46.72%  |
| DDR4    | 35        | 28.69%  |
| DDR2    | 11        | 9.02%   |
| LPDDR4  | 7         | 5.74%   |
| SDRAM   | 5         | 4.1%    |
| Unknown | 4         | 3.28%   |
| LPDDR3  | 3         | 2.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 82        | 67.21%  |
| DIMM         | 26        | 21.31%  |
| Row Of Chips | 11        | 9.02%   |
| Unknown      | 3         | 2.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 43        | 31.39%  |
| 2048  | 41        | 29.93%  |
| 8192  | 35        | 25.55%  |
| 16384 | 8         | 5.84%   |
| 1024  | 7         | 5.11%   |
| 32768 | 2         | 1.46%   |
| 512   | 1         | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 38        | 29.92%  |
| 3200    | 15        | 11.81%  |
| 1333    | 11        | 8.66%   |
| 2667    | 7         | 5.51%   |
| 667     | 7         | 5.51%   |
| 1334    | 6         | 4.72%   |
| 2400    | 5         | 3.94%   |
| 1066    | 5         | 3.94%   |
| 3266    | 4         | 3.15%   |
| Unknown | 4         | 3.15%   |
| 1067    | 3         | 2.36%   |
| 4267    | 2         | 1.57%   |
| 2133    | 2         | 1.57%   |
| 2048    | 2         | 1.57%   |
| 1867    | 2         | 1.57%   |
| 1866    | 2         | 1.57%   |
| 975     | 2         | 1.57%   |
| 800     | 2         | 1.57%   |
| 4199    | 1         | 0.79%   |
| 3733    | 1         | 0.79%   |
| 3666    | 1         | 0.79%   |
| 3400    | 1         | 0.79%   |
| 3066    | 1         | 0.79%   |
| 3000    | 1         | 0.79%   |
| 2800    | 1         | 0.79%   |
| 333     | 1         | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 16.67%  |
| HP LaserJet P1102       | 1         | 16.67%  |
| Canon PIXMA MP250       | 1         | 16.67%  |
| Canon MF3110            | 1         | 16.67%  |
| Canon CanoScan LiDE 300 | 1         | 16.67%  |
| Brother DCP-7055W       | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 32        | 28.07%  |
| Microdia                               | 11        | 9.65%   |
| Realtek Semiconductor                  | 9         | 7.89%   |
| Sunplus Innovation Technology          | 8         | 7.02%   |
| Syntek                                 | 6         | 5.26%   |
| IMC Networks                           | 5         | 4.39%   |
| Apple                                  | 5         | 4.39%   |
| Acer                                   | 5         | 4.39%   |
| Quanta                                 | 4         | 3.51%   |
| Logitech                               | 4         | 3.51%   |
| Alcor Micro                            | 4         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.63%   |
| Suyin                                  | 2         | 1.75%   |
| Silicon Motion                         | 2         | 1.75%   |
| Lenovo                                 | 2         | 1.75%   |
| ALi                                    | 2         | 1.75%   |
| Y Media                                | 1         | 0.88%   |
| WaveRider Communications               | 1         | 0.88%   |
| USB Camera CS                          | 1         | 0.88%   |
| SunplusIT                              | 1         | 0.88%   |
| Ricoh                                  | 1         | 0.88%   |
| Pixart Imaging                         | 1         | 0.88%   |
| Microsoft                              | 1         | 0.88%   |
| Lite-On Technology                     | 1         | 0.88%   |
| Cubeternet                             | 1         | 0.88%   |
| AVerMedia Technologies                 | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 8         | 6.96%   |
| Chicony HD WebCam                    | 4         | 3.48%   |
| Sunplus HD WebCam                    | 3         | 2.61%   |
| Realtek Lenovo EasyCamera            | 2         | 1.74%   |
| Realtek Integrated_Webcam_HD         | 2         | 1.74%   |
| Realtek Integrated Webcam HD         | 2         | 1.74%   |
| Microdia Lenovo EasyCamera           | 2         | 1.74%   |
| Microdia Integrated_Webcam_HD        | 2         | 1.74%   |
| Microdia Integrated Webcam           | 2         | 1.74%   |
| Microdia HP Webcam-50                | 2         | 1.74%   |
| Logitech Webcam C270                 | 2         | 1.74%   |
| IMC Networks USB2.0 HD UVC WebCam    | 2         | 1.74%   |
| Chicony VGA Webcam                   | 2         | 1.74%   |
| Chicony HP Truevision HD camera      | 2         | 1.74%   |
| Chicony HP Truevision HD             | 2         | 1.74%   |
| Chicony FJ Camera                    | 2         | 1.74%   |
| Chicony EasyCamera                   | 2         | 1.74%   |
| Chicony 2.0M UVC Webcam / CNF7129    | 2         | 1.74%   |
| Apple FaceTime HD Camera             | 2         | 1.74%   |
| ALi WebCam                           | 2         | 1.74%   |
| Alcor Micro USB Camera               | 2         | 1.74%   |
| Alcor Micro USB 2.0 Camera           | 2         | 1.74%   |
| Acer Lenovo EasyCamera               | 2         | 1.74%   |
| Acer Integrated Camera               | 2         | 1.74%   |
| Y Media USB Camera                   | 1         | 0.87%   |
| WaveRider USB 2.0 Camera             | 1         | 0.87%   |
| USB Camera CS USB Camera CS          | 1         | 0.87%   |
| Syntek USB2.0 Camera                 | 1         | 0.87%   |
| Syntek USB Camera Device             | 1         | 0.87%   |
| Syntek Sonix USB 2.0 Camera          | 1         | 0.87%   |
| Syntek Lenovo EasyCamera             | 1         | 0.87%   |
| Syntek Integrated Camera             | 1         | 0.87%   |
| Syntek HD WebCam                     | 1         | 0.87%   |
| Suyin Intel Webcam                   | 1         | 0.87%   |
| Suyin 1.3M HD WebCam                 | 1         | 0.87%   |
| SunplusIT USB camera                 | 1         | 0.87%   |
| Sunplus Laptop Integrated Webcam FHD | 1         | 0.87%   |
| Sunplus Integrated_Webcam_HD         | 1         | 0.87%   |
| Sunplus HD User Facing               | 1         | 0.87%   |
| Sunplus Dell Integrated HD Webcam    | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 25%     |
| Upek                       | 4         | 20%     |
| AuthenTec                  | 4         | 20%     |
| Synaptics                  | 2         | 10%     |
| STMicroelectronics         | 2         | 10%     |
| Shenzhen Goodix Technology | 1         | 5%      |
| LighTuning Technology      | 1         | 5%      |
| Elan Microelectronics      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 20%     |
| STMicroelectronics Fingerprint Reader                  | 2         | 10%     |
| Unknown                                                | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5%      |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5%      |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5%      |
| Elan ELAN:Fingerprint                                  | 1         | 5%      |
| AuthenTec Fingerprint Sensor                           | 1         | 5%      |
| AuthenTec AES2810                                      | 1         | 5%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5%      |
| AuthenTec AES1600                                      | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 55.56%  |
| Alcor Micro | 2         | 22.22%  |
| O2 Micro    | 1         | 11.11%  |
| Cherry      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 11.11%  |
| Cherry SmartCard Reader Keyboard KC 1000 SC    | 1         | 11.11%  |
| Alcor Micro Watchdata W 1981                   | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 152       | 76.77%  |
| 1     | 41        | 20.71%  |
| 2     | 5         | 2.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 20        | 40%     |
| Graphics card      | 10        | 20%     |
| Chipcard           | 8         | 16%     |
| Camera             | 4         | 8%      |
| Net/wireless       | 3         | 6%      |
| Bluetooth          | 2         | 4%      |
| Storage            | 1         | 2%      |
| Network            | 1         | 2%      |
| Dvb card           | 1         | 2%      |

