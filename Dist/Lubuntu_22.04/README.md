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

Total: 291

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-43-generic          | 35        | 14.83%  |
| 5.15.0-56-generic          | 18        | 7.63%   |
| 5.15.0-25-generic          | 14        | 5.93%   |
| 5.15.0-60-generic          | 13        | 5.51%   |
| 5.15.0-47-generic          | 12        | 5.08%   |
| 5.15.0-58-generic          | 11        | 4.66%   |
| 5.15.0-30-generic          | 10        | 4.24%   |
| 5.15.0-46-generic          | 9         | 3.81%   |
| 5.15.0-41-generic          | 9         | 3.81%   |
| 5.15.0-27-generic          | 9         | 3.81%   |
| 5.15.0-53-generic          | 8         | 3.39%   |
| 5.15.0-52-generic          | 8         | 3.39%   |
| 5.19.0-35-generic          | 7         | 2.97%   |
| 5.15.0-67-generic          | 6         | 2.54%   |
| 5.15.0-50-generic          | 6         | 2.54%   |
| 5.15.0-48-generic          | 6         | 2.54%   |
| 5.15.0-40-generic          | 6         | 2.54%   |
| 5.19.0-32-generic          | 5         | 2.12%   |
| 5.15.0-57-generic          | 5         | 2.12%   |
| 5.15.0-39-generic          | 4         | 1.69%   |
| 5.15.0-35-generic          | 4         | 1.69%   |
| 5.15.0-33-generic          | 4         | 1.69%   |
| 5.15.0-37-generic          | 2         | 0.85%   |
| 5.15.0-23-generic          | 2         | 0.85%   |
| 5.15.0-18-generic          | 2         | 0.85%   |
| 6.2.8-x64v3-xanmod1        | 1         | 0.42%   |
| 6.1.12-060112-generic      | 1         | 0.42%   |
| 6.1.0-custom               | 1         | 0.42%   |
| 6.0.8-060008-generic       | 1         | 0.42%   |
| 6.0.14                     | 1         | 0.42%   |
| 6.0.12-x64v2-xanmod1       | 1         | 0.42%   |
| 6.0.10-rockchip64          | 1         | 0.42%   |
| 5.4.0-139-generic          | 1         | 0.42%   |
| 5.19.8-xanmod1             | 1         | 0.42%   |
| 5.19.11-ux360cak           | 1         | 0.42%   |
| 5.19.0-16.2-liquorix-amd64 | 1         | 0.42%   |
| 5.19.0-051900-generic      | 1         | 0.42%   |
| 5.18.0-051800-generic      | 1         | 0.42%   |
| 5.15.0-59-lowlatency       | 1         | 0.42%   |
| 5.15.0-58-lowlatency       | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 197       | 88.74%  |
| 5.19.0  | 13        | 5.86%   |
| 6.2.8   | 1         | 0.45%   |
| 6.1.12  | 1         | 0.45%   |
| 6.1.0   | 1         | 0.45%   |
| 6.0.8   | 1         | 0.45%   |
| 6.0.14  | 1         | 0.45%   |
| 6.0.12  | 1         | 0.45%   |
| 6.0.10  | 1         | 0.45%   |
| 5.4.0   | 1         | 0.45%   |
| 5.19.8  | 1         | 0.45%   |
| 5.19.11 | 1         | 0.45%   |
| 5.18.0  | 1         | 0.45%   |
| 5.14.0  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 197       | 88.74%  |
| 5.19    | 15        | 6.76%   |
| 6.0     | 4         | 1.8%    |
| 6.1     | 2         | 0.9%    |
| 6.2     | 1         | 0.45%   |
| 5.4     | 1         | 0.45%   |
| 5.18    | 1         | 0.45%   |
| 5.14    | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 214       | 99.07%  |
| aarch64 | 2         | 0.93%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 207       | 95.39%  |
| LXDE       | 5         | 2.3%    |
| X-Cinnamon | 2         | 0.92%   |
| GNOME      | 2         | 0.92%   |
| XFCE       | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 208       | 95.41%  |
| Tty         | 7         | 3.21%   |
| Wayland     | 2         | 0.92%   |
| Unspecified | 1         | 0.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 186       | 85.32%  |
| LightDM | 13        | 5.96%   |
| Unknown | 12        | 5.5%    |
| GDM3    | 4         | 1.83%   |
| XDM     | 1         | 0.46%   |
| SLiM    | 1         | 0.46%   |
| LXDM    | 1         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 60        | 27.65%  |
| fr_FR  | 22        | 10.14%  |
| it_IT  | 16        | 7.37%   |
| de_DE  | 16        | 7.37%   |
| C      | 11        | 5.07%   |
| pt_BR  | 10        | 4.61%   |
| en_GB  | 10        | 4.61%   |
| pl_PL  | 8         | 3.69%   |
| en_AG  | 8         | 3.69%   |
| es_ES  | 7         | 3.23%   |
| ru_RU  | 5         | 2.3%    |
| es_AR  | 5         | 2.3%    |
| nl_BE  | 4         | 1.84%   |
| es_CR  | 4         | 1.84%   |
| es_MX  | 3         | 1.38%   |
| en_AU  | 3         | 1.38%   |
| tr_TR  | 2         | 0.92%   |
| en_CA  | 2         | 0.92%   |
| el_GR  | 2         | 0.92%   |
| sv_SE  | 1         | 0.46%   |
| ru_UA  | 1         | 0.46%   |
| nl_NL  | 1         | 0.46%   |
| lzh_TW | 1         | 0.46%   |
| ja_JP  | 1         | 0.46%   |
| hu_HU  | 1         | 0.46%   |
| fr_CA  | 1         | 0.46%   |
| fi_FI  | 1         | 0.46%   |
| es_PE  | 1         | 0.46%   |
| es_EC  | 1         | 0.46%   |
| es_CO  | 1         | 0.46%   |
| es_CL  | 1         | 0.46%   |
| en_ZA  | 1         | 0.46%   |
| en_PH  | 1         | 0.46%   |
| en_DE  | 1         | 0.46%   |
| de_CH  | 1         | 0.46%   |
| cv_RU  | 1         | 0.46%   |
| cs_CZ  | 1         | 0.46%   |
| aa_DJ  | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 139       | 64.06%  |
| EFI  | 78        | 35.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 199       | 91.28%  |
| Overlay | 13        | 5.96%   |
| Btrfs   | 3         | 1.38%   |
| XXX4    | 1         | 0.46%   |
| Xfs     | 1         | 0.46%   |
| Ext2    | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 104       | 47.49%  |
| MBR     | 66        | 30.14%  |
| Unknown | 49        | 22.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 191       | 88.02%  |
| Yes       | 26        | 11.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 69.12%  |
| Yes       | 67        | 30.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 34        | 15.74%  |
| Dell                    | 26        | 12.04%  |
| ASUSTek Computer        | 23        | 10.65%  |
| Hewlett-Packard         | 21        | 9.72%   |
| Acer                    | 16        | 7.41%   |
| MSI                     | 13        | 6.02%   |
| Apple                   | 7         | 3.24%   |
| Google                  | 6         | 2.78%   |
| ASRock                  | 6         | 2.78%   |
| Unknown                 | 6         | 2.78%   |
| Intel                   | 5         | 2.31%   |
| Gigabyte Technology     | 5         | 2.31%   |
| Fujitsu                 | 5         | 2.31%   |
| Positivo                | 4         | 1.85%   |
| AMI                     | 4         | 1.85%   |
| Sony                    | 3         | 1.39%   |
| Pegatron                | 3         | 1.39%   |
| Toshiba                 | 2         | 0.93%   |
| OEM                     | 2         | 0.93%   |
| Mediacom                | 2         | 0.93%   |
| Gateway                 | 2         | 0.93%   |
| ZOTAC                   | 1         | 0.46%   |
| YANYU                   | 1         | 0.46%   |
| Thomson                 | 1         | 0.46%   |
| SGIN                    | 1         | 0.46%   |
| Samsung Electronics     | 1         | 0.46%   |
| Rockchip                | 1         | 0.46%   |
| Raspberry Pi Foundation | 1         | 0.46%   |
| Pretech                 | 1         | 0.46%   |
| Prestigio               | 1         | 0.46%   |
| Packard Bell            | 1         | 0.46%   |
| NEC Computers           | 1         | 0.46%   |
| Kiano                   | 1         | 0.46%   |
| IFSA                    | 1         | 0.46%   |
| HUAWEI                  | 1         | 0.46%   |
| GPU Company             | 1         | 0.46%   |
| Getac                   | 1         | 0.46%   |
| Fujitsu Siemens         | 1         | 0.46%   |
| ECS                     | 1         | 0.46%   |
| Chuwi                   | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 3.24%   |
| Apple MacBookPro8,1                        | 3         | 1.39%   |
| MSI MS-7C37                                | 2         | 0.93%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 0.93%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.93%   |
| Lenovo G50-30 80G0                         | 2         | 0.93%   |
| HP Pavilion g6                             | 2         | 0.93%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.93%   |
| Dell Dimension 9100                        | 2         | 0.93%   |
| ZOTAC NM10                                 | 1         | 0.46%   |
| YANYU ITX-S192                             | 1         | 0.46%   |
| Toshiba Satellite Pro S500                 | 1         | 0.46%   |
| Toshiba Satellite L40                      | 1         | 0.46%   |
| Thomson N14C4WH64                          | 1         | 0.46%   |
| Sony VPCEB15FM                             | 1         | 0.46%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.46%   |
| Sony SVE14A2V1EW                           | 1         | 0.46%   |
| SGIN laptop                                | 1         | 0.46%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.46%   |
| Rockchip RK3318 BOX                        | 1         | 0.46%   |
| RPi Raspberry Pi                           | 1         | 0.46%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.46%   |
| Prestigio PSB141C01BFH                     | 1         | 0.46%   |
| Positivo Q232A                             | 1         | 0.46%   |
| Positivo POS-AG31AP                        | 1         | 0.46%   |
| Positivo P5VD2-MX                          | 1         | 0.46%   |
| Positivo i500pro                           | 1         | 0.46%   |
| Pegatron NC689AA-ABA s3700y                | 1         | 0.46%   |
| Pegatron h8-1350ef                         | 1         | 0.46%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.46%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.46%   |
| OEM M882CWP                                | 1         | 0.46%   |
| NEC Computers ECS-945G                     | 1         | 0.46%   |
| MSI S12T 3M/S12 3M                         | 1         | 0.46%   |
| MSI MS-7D09                                | 1         | 0.46%   |
| MSI MS-7C96                                | 1         | 0.46%   |
| MSI MS-7C56                                | 1         | 0.46%   |
| MSI MS-7C51                                | 1         | 0.46%   |
| MSI MS-7B86                                | 1         | 0.46%   |
| MSI MS-7978                                | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 11        | 5.09%   |
| Lenovo ThinkPad        | 10        | 4.63%   |
| Acer Aspire            | 10        | 4.63%   |
| Dell Latitude          | 9         | 4.17%   |
| Unknown                | 7         | 3.24%   |
| HP Pavilion            | 5         | 2.31%   |
| Fujitsu LIFEBOOK       | 4         | 1.85%   |
| HP ProBook             | 3         | 1.39%   |
| Dell Vostro            | 3         | 1.39%   |
| Dell Precision         | 3         | 1.39%   |
| Dell OptiPlex          | 3         | 1.39%   |
| Apple MacBookPro8      | 3         | 1.39%   |
| Toshiba Satellite      | 2         | 0.93%   |
| MSI MS-7C37            | 2         | 0.93%   |
| Mediacom WinPad        | 2         | 0.93%   |
| Lenovo ThinkCentre     | 2         | 0.93%   |
| Lenovo G50-30          | 2         | 0.93%   |
| HP Laptop              | 2         | 0.93%   |
| HP Compaq              | 2         | 0.93%   |
| Dell XPS               | 2         | 0.93%   |
| Dell Studio            | 2         | 0.93%   |
| Dell Dimension         | 2         | 0.93%   |
| ASUS PRIME             | 2         | 0.93%   |
| ZOTAC NM10             | 1         | 0.46%   |
| YANYU ITX-S192         | 1         | 0.46%   |
| Thomson N14C4WH64      | 1         | 0.46%   |
| Sony VPCEB15FM         | 1         | 0.46%   |
| Sony VGN-SZ71WN        | 1         | 0.46%   |
| Sony SVE14A2V1EW       | 1         | 0.46%   |
| SGIN laptop            | 1         | 0.46%   |
| Samsung 300V3A         | 1         | 0.46%   |
| Rockchip RK3318        | 1         | 0.46%   |
| RPi Raspberry          | 1         | 0.46%   |
| Pretech EVE            | 1         | 0.46%   |
| Prestigio PSB141C01BFH | 1         | 0.46%   |
| Positivo Q232A         | 1         | 0.46%   |
| Positivo POS-AG31AP    | 1         | 0.46%   |
| Positivo P5VD2-MX      | 1         | 0.46%   |
| Positivo i500pro       | 1         | 0.46%   |
| Pegatron NC689AA-ABA   | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 23        | 10.65%  |
| 2019    | 18        | 8.33%   |
| 2013    | 17        | 7.87%   |
| 2021    | 15        | 6.94%   |
| 2020    | 14        | 6.48%   |
| 2015    | 14        | 6.48%   |
| 2014    | 14        | 6.48%   |
| 2012    | 14        | 6.48%   |
| 2008    | 14        | 6.48%   |
| 2010    | 12        | 5.56%   |
| 2016    | 11        | 5.09%   |
| 2009    | 11        | 5.09%   |
| 2017    | 9         | 4.17%   |
| 2007    | 9         | 4.17%   |
| 2018    | 8         | 3.7%    |
| 2022    | 7         | 3.24%   |
| 2006    | 2         | 0.93%   |
| Unknown | 2         | 0.93%   |
| 2023    | 1         | 0.46%   |
| 2001    | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 132       | 61.11%  |
| Desktop        | 70        | 32.41%  |
| Convertible    | 5         | 2.31%   |
| Tablet         | 3         | 1.39%   |
| Mini pc        | 3         | 1.39%   |
| System on chip | 2         | 0.93%   |
| All in one     | 1         | 0.46%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 208       | 95.85%  |
| Enabled  | 9         | 4.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 209       | 96.76%  |
| Yes  | 7         | 3.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 75        | 34.4%   |
| 4.01-8.0    | 48        | 22.02%  |
| 1.01-2.0    | 25        | 11.47%  |
| 8.01-16.0   | 25        | 11.47%  |
| 16.01-24.0  | 22        | 10.09%  |
| 32.01-64.0  | 10        | 4.59%   |
| 2.01-3.0    | 8         | 3.67%   |
| 0.51-1.0    | 3         | 1.38%   |
| 64.01-256.0 | 2         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 105       | 46.46%  |
| 0.51-1.0  | 54        | 23.89%  |
| 2.01-3.0  | 44        | 19.47%  |
| 4.01-8.0  | 13        | 5.75%   |
| 3.01-4.0  | 8         | 3.54%   |
| 8.01-16.0 | 1         | 0.44%   |
| 0.01-0.5  | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 152       | 69.72%  |
| 2      | 49        | 22.48%  |
| 3      | 6         | 2.75%   |
| 0      | 4         | 1.83%   |
| 5      | 2         | 0.92%   |
| 4      | 2         | 0.92%   |
| 12     | 1         | 0.46%   |
| 7      | 1         | 0.46%   |
| 6      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 131       | 60.65%  |
| Yes       | 85        | 39.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 80.09%  |
| No        | 43        | 19.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 74.54%  |
| No        | 55        | 25.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 51.83%  |
| No        | 105       | 48.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 38        | 17.59%  |
| France       | 23        | 10.65%  |
| Germany      | 22        | 10.19%  |
| Italy        | 18        | 8.33%   |
| Poland       | 12        | 5.56%   |
| Brazil       | 11        | 5.09%   |
| Spain        | 8         | 3.7%    |
| Russia       | 8         | 3.7%    |
| UK           | 7         | 3.24%   |
| Belgium      | 6         | 2.78%   |
| Costa Rica   | 5         | 2.31%   |
| Argentina    | 5         | 2.31%   |
| Ukraine      | 4         | 1.85%   |
| Canada       | 4         | 1.85%   |
| Turkey       | 3         | 1.39%   |
| Mexico       | 3         | 1.39%   |
| Indonesia    | 3         | 1.39%   |
| Australia    | 3         | 1.39%   |
| Vietnam      | 2         | 0.93%   |
| Sweden       | 2         | 0.93%   |
| Netherlands  | 2         | 0.93%   |
| Latvia       | 2         | 0.93%   |
| Hungary      | 2         | 0.93%   |
| Greece       | 2         | 0.93%   |
| Thailand     | 1         | 0.46%   |
| Taiwan       | 1         | 0.46%   |
| Switzerland  | 1         | 0.46%   |
| South Africa | 1         | 0.46%   |
| Saudi Arabia | 1         | 0.46%   |
| Romania      | 1         | 0.46%   |
| Portugal     | 1         | 0.46%   |
| Philippines  | 1         | 0.46%   |
| Peru         | 1         | 0.46%   |
| Kenya        | 1         | 0.46%   |
| Japan        | 1         | 0.46%   |
| Ireland      | 1         | 0.46%   |
| Iran         | 1         | 0.46%   |
| Finland      | 1         | 0.46%   |
| Ecuador      | 1         | 0.46%   |
| Czechia      | 1         | 0.46%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Paris              | 7         | 3.13%   |
| Heredia            | 4         | 1.79%   |
| Melbourne          | 3         | 1.34%   |
| Kyiv               | 3         | 1.34%   |
| Ghent              | 3         | 1.34%   |
| Warsaw             | 2         | 0.89%   |
| Sarospatak         | 2         | 0.89%   |
| Sao Paulo          | 2         | 0.89%   |
| Porto Alegre       | 2         | 0.89%   |
| Novo Gama          | 2         | 0.89%   |
| Milan              | 2         | 0.89%   |
| Largo              | 2         | 0.89%   |
| Lansing            | 2         | 0.89%   |
| Jakarta            | 2         | 0.89%   |
| Eberbach           | 2         | 0.89%   |
| Chicago            | 2         | 0.89%   |
| Zizur Mayor        | 1         | 0.45%   |
| Zawiercie          | 1         | 0.45%   |
| Yoshkar-Ola        | 1         | 0.45%   |
| Yorkville          | 1         | 0.45%   |
| Yerevan            | 1         | 0.45%   |
| Yekaterinburg      | 1         | 0.45%   |
| Wolfhagen          | 1         | 0.45%   |
| Wetteren           | 1         | 0.45%   |
| West Stockbridge   | 1         | 0.45%   |
| Washington         | 1         | 0.45%   |
| Warendorf          | 1         | 0.45%   |
| Volzhskiy          | 1         | 0.45%   |
| Versailles         | 1         | 0.45%   |
| Verona             | 1         | 0.45%   |
| Varna              | 1         | 0.45%   |
| Valentigney        | 1         | 0.45%   |
| Valencia           | 1         | 0.45%   |
| Uberlândia        | 1         | 0.45%   |
| Tyler              | 1         | 0.45%   |
| Tychy              | 1         | 0.45%   |
| Turin              | 1         | 0.45%   |
| Torrejón de Ardoz | 1         | 0.45%   |
| Thornton Heath     | 1         | 0.45%   |
| Thessaloniki       | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 39        | 50     | 14.34%  |
| WDC                       | 34        | 48     | 12.5%   |
| Unknown                   | 28        | 40     | 10.29%  |
| Samsung Electronics       | 27        | 36     | 9.93%   |
| Toshiba                   | 15        | 16     | 5.51%   |
| Kingston                  | 14        | 15     | 5.15%   |
| Hitachi                   | 14        | 18     | 5.15%   |
| SanDisk                   | 13        | 13     | 4.78%   |
| Crucial                   | 7         | 7      | 2.57%   |
| HGST                      | 6         | 6      | 2.21%   |
| A-DATA Technology         | 6         | 6      | 2.21%   |
| Micron Technology         | 5         | 6      | 1.84%   |
| Intel                     | 4         | 5      | 1.47%   |
| GOODRAM                   | 4         | 4      | 1.47%   |
| SK hynix                  | 3         | 3      | 1.1%    |
| Apacer                    | 3         | 3      | 1.1%    |
| UMIS                      | 2         | 2      | 0.74%   |
| Transcend                 | 2         | 3      | 0.74%   |
| SPCC                      | 2         | 3      | 0.74%   |
| Patriot                   | 2         | 2      | 0.74%   |
| Micron/Crucial Technology | 2         | 3      | 0.74%   |
| Maxtor                    | 2         | 2      | 0.74%   |
| Fujitsu                   | 2         | 2      | 0.74%   |
| China                     | 2         | 2      | 0.74%   |
| Unknown                   | 2         | 2      | 0.74%   |
| WD MediaMax               | 1         | 1      | 0.37%   |
| W800S                     | 1         | 1      | 0.37%   |
| TO Exter                  | 1         | 1      | 0.37%   |
| Teclast                   | 1         | 1      | 0.37%   |
| Team                      | 1         | 1      | 0.37%   |
| T-FORCE                   | 1         | 1      | 0.37%   |
| RSH-319                   | 1         | 1      | 0.37%   |
| Rogueware                 | 1         | 1      | 0.37%   |
| PNY                       | 1         | 1      | 0.37%   |
| Plextor                   | 1         | 1      | 0.37%   |
| Phison                    | 1         | 1      | 0.37%   |
| NGFF                      | 1         | 1      | 0.37%   |
| LITEONIT                  | 1         | 1      | 0.37%   |
| LITEON                    | 1         | 1      | 0.37%   |
| Lexar                     | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 6         | 1.99%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 1.99%   |
| Unknown MMC Card  32GB             | 5         | 1.66%   |
| Seagate ST9500325AS 500GB          | 5         | 1.66%   |
| SanDisk DF4032  32GB               | 5         | 1.66%   |
| Kingston SA400S37240G 240GB SSD    | 5         | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.99%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.66%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 0.66%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.66%   |
| Unknown SD/MMC/MS PRO 64GB         | 2         | 0.66%   |
| Unknown SC64G  64GB                | 2         | 0.66%   |
| Unknown NCard  32GB                | 2         | 0.66%   |
| Unknown MMC64G  64GB               | 2         | 0.66%   |
| Unknown DA4032  32GB               | 2         | 0.66%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.66%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.66%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.66%   |
| SPCC Solid State Disk 120GB        | 2         | 0.66%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.66%   |
| Seagate ST3120213AS 120GB          | 2         | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.66%   |
| SanDisk DF4064  64GB               | 2         | 0.66%   |
| Samsung SSD 870 EVO 500GB          | 2         | 0.66%   |
| Samsung SSD 860 EVO 500GB          | 2         | 0.66%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.66%   |
| Samsung HD502HJ 500GB              | 2         | 0.66%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.66%   |
| Crucial CT500P3SSD8 500GB          | 2         | 0.66%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.66%   |
| Apacer 16GB SATA Flash Drive SSD   | 2         | 0.66%   |
| A-DATA SU635 240GB SSD             | 2         | 0.66%   |
| Unknown                            | 2         | 0.66%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.33%   |
| WDC WDS500G2B0A 500GB SSD          | 1         | 0.33%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.33%   |
| WDC WDS100T1X0E-00AFY0 1TB         | 1         | 0.33%   |
| WDC WD800BB-00CAA1 80GB            | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 49     | 33.05%  |
| WDC                 | 29        | 37     | 24.58%  |
| Hitachi             | 14        | 18     | 11.86%  |
| Toshiba             | 13        | 14     | 11.02%  |
| Samsung Electronics | 7         | 12     | 5.93%   |
| HGST                | 6         | 6      | 5.08%   |
| Unknown             | 2         | 2      | 1.69%   |
| Maxtor              | 2         | 2      | 1.69%   |
| Fujitsu             | 2         | 2      | 1.69%   |
| WD MediaMax         | 1         | 1      | 0.85%   |
| RSH-319             | 1         | 1      | 0.85%   |
| External            | 1         | 1      | 0.85%   |
| Apricorn            | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 17.98%  |
| Kingston            | 12        | 13     | 13.48%  |
| A-DATA Technology   | 6         | 6      | 6.74%   |
| SanDisk             | 5         | 5      | 5.62%   |
| WDC                 | 4         | 5      | 4.49%   |
| GOODRAM             | 4         | 4      | 4.49%   |
| Crucial             | 4         | 4      | 4.49%   |
| Micron Technology   | 3         | 3      | 3.37%   |
| Intel               | 3         | 3      | 3.37%   |
| Apacer              | 3         | 3      | 3.37%   |
| Transcend           | 2         | 3      | 2.25%   |
| Toshiba             | 2         | 2      | 2.25%   |
| SPCC                | 2         | 3      | 2.25%   |
| Patriot             | 2         | 2      | 2.25%   |
| W800S               | 1         | 1      | 1.12%   |
| TO Exter            | 1         | 1      | 1.12%   |
| Teclast             | 1         | 1      | 1.12%   |
| Team                | 1         | 1      | 1.12%   |
| Rogueware           | 1         | 1      | 1.12%   |
| PNY                 | 1         | 1      | 1.12%   |
| Plextor             | 1         | 1      | 1.12%   |
| NGFF                | 1         | 1      | 1.12%   |
| LITEONIT            | 1         | 1      | 1.12%   |
| LITEON              | 1         | 1      | 1.12%   |
| Lexar               | 1         | 1      | 1.12%   |
| Leqixiang           | 1         | 1      | 1.12%   |
| Lenovo              | 1         | 1      | 1.12%   |
| Kston               | 1         | 3      | 1.12%   |
| KINGPOWER           | 1         | 1      | 1.12%   |
| HUSKY               | 1         | 1      | 1.12%   |
| Gigabyte Technology | 1         | 1      | 1.12%   |
| Emtec               | 1         | 1      | 1.12%   |
| China               | 1         | 1      | 1.12%   |
| BR                  | 1         | 1      | 1.12%   |
| 2.5"                | 1         | 2      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 146    | 39.22%  |
| SSD     | 86        | 98     | 33.73%  |
| MMC     | 36        | 49     | 14.12%  |
| NVMe    | 29        | 35     | 11.37%  |
| Unknown | 4         | 6      | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 164       | 238    | 68.91%  |
| MMC  | 36        | 49     | 15.13%  |
| NVMe | 29        | 35     | 12.18%  |
| SAS  | 9         | 12     | 3.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 168    | 70.53%  |
| 0.51-1.0   | 36        | 49     | 18.95%  |
| 1.01-2.0   | 12        | 15     | 6.32%   |
| 2.01-3.0   | 3         | 4      | 1.58%   |
| 4.01-10.0  | 3         | 6      | 1.58%   |
| 3.01-4.0   | 2         | 2      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 31.96%  |
| 251-500        | 48        | 21.92%  |
| 51-100         | 24        | 10.96%  |
| 21-50          | 21        | 9.59%   |
| 1-20           | 19        | 8.68%   |
| 501-1000       | 16        | 7.31%   |
| 1001-2000      | 10        | 4.57%   |
| More than 3000 | 5         | 2.28%   |
| 2001-3000      | 5         | 2.28%   |
| Unknown        | 1         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 114       | 51.12%  |
| 21-50          | 41        | 18.39%  |
| 51-100         | 24        | 10.76%  |
| 101-250        | 19        | 8.52%   |
| 501-1000       | 8         | 3.59%   |
| 251-500        | 7         | 3.14%   |
| More than 3000 | 4         | 1.79%   |
| 1001-2000      | 4         | 1.79%   |
| 2001-3000      | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB        | 3         | 4      | 8.11%   |
| Seagate ST9500325AS 500GB                 | 2         | 2      | 5.41%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 5.41%   |
| WDC WD60EFRX-68L0BN1 6TB                  | 1         | 2      | 2.7%    |
| WDC WD3200AACS-00M6B0 320GB               | 1         | 1      | 2.7%    |
| WDC WD2003FYYS-02W0B0 2TB                 | 1         | 1      | 2.7%    |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 2.7%    |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 1      | 2.7%    |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 2.7%    |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 2.7%    |
| WDC WD10EACS-00D6B1 1TB                   | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 2.7%    |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 2.7%    |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 2.7%    |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 2.7%    |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 2.7%    |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 2.7%    |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 2.7%    |
| Samsung Electronics HM121HI 120GB         | 1         | 5      | 2.7%    |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 2.7%    |
| Plextor PX-128M6M 128GB SSD               | 1         | 1      | 2.7%    |
| NGFF 2280 512GB SSD                       | 1         | 1      | 2.7%    |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.7%    |
| Maxtor 6L200M0 208GB                      | 1         | 1      | 2.7%    |
| Intel SSDSA2M080G2LE 80GB                 | 1         | 1      | 2.7%    |
| Hitachi HTS722080K9SA00 80GB              | 1         | 1      | 2.7%    |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 2.7%    |
| HGST HTS725032A7E630 320GB                | 1         | 1      | 2.7%    |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 2.7%    |
| A-DATA Technology SP920SS 256GB SSD       | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 34.29%  |
| WDC                 | 6         | 9      | 17.14%  |
| Toshiba             | 3         | 3      | 8.57%   |
| Samsung Electronics | 2         | 6      | 5.71%   |
| Hitachi             | 2         | 2      | 5.71%   |
| Apacer              | 2         | 2      | 5.71%   |
| Plextor             | 1         | 1      | 2.86%   |
| NGFF                | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| Maxtor              | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| A-DATA Technology   | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 42.86%  |
| WDC                 | 6         | 9      | 21.43%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Samsung Electronics | 2         | 6      | 7.14%   |
| Hitachi             | 2         | 2      | 7.14%   |
| Maxtor              | 1         | 1      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 36     | 79.41%  |
| SSD  | 7         | 7      | 20.59%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB       | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB | 1         | 1      | 33.33%  |
| HGST HTS725025A7 250GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 117       | 177    | 50.65%  |
| Works    | 77        | 111    | 33.33%  |
| Malfunc  | 34        | 43     | 14.72%  |
| Failed   | 3         | 3      | 1.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 137       | 61.43%  |
| AMD                              | 38        | 17.04%  |
| Nvidia                           | 7         | 3.14%   |
| Samsung Electronics              | 6         | 2.69%   |
| SanDisk                          | 5         | 2.24%   |
| Micron/Crucial Technology        | 5         | 2.24%   |
| Micron Technology                | 3         | 1.35%   |
| JMicron Technology               | 3         | 1.35%   |
| ASMedia Technology               | 3         | 1.35%   |
| VIA Technologies                 | 2         | 0.9%    |
| Union Memory (Shenzhen)          | 2         | 0.9%    |
| SK hynix                         | 2         | 0.9%    |
| Marvell Technology Group         | 2         | 0.9%    |
| Kingston Technology Company      | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Silicon Image                    | 1         | 0.45%   |
| Seagate Technology               | 1         | 0.45%   |
| Phison Electronics               | 1         | 0.45%   |
| LSI Logic / Symbios Logic        | 1         | 0.45%   |
| KIOXIA                           | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 7.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 5.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 4.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 3.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 2.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 2.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 2.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 2.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.6%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 1.86%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.12%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.12%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 1.12%   |
| Micron NVMe Storage Controller                                                   | 3         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.12%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 1.12%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 1.12%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.12%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.74%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.74%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.74%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.74%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 2         | 0.74%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.74%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 152       | 64.68%  |
| IDE  | 43        | 18.3%   |
| NVMe | 28        | 11.91%  |
| RAID | 11        | 4.68%   |
| SAS  | 1         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 169       | 78.24%  |
| AMD    | 45        | 20.83%  |
| ARM    | 2         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 2.78%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 2.31%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.85%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.85%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 1.85%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.39%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.39%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 3         | 1.39%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 2         | 0.93%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.93%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.93%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.93%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.93%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.93%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.93%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.93%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.93%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.93%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 2         | 0.93%   |
| ARM Processor                                 | 2         | 0.93%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 0.93%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 0.93%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 0.93%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+    | 2         | 0.93%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 2         | 0.93%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.93%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.46%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz           | 1         | 0.46%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 16.67%  |
| Intel Celeron           | 35        | 16.2%   |
| Intel Atom              | 20        | 9.26%   |
| Intel Core 2 Duo        | 19        | 8.8%    |
| Intel Core i7           | 17        | 7.87%   |
| Intel Core i3           | 17        | 7.87%   |
| Intel Pentium           | 8         | 3.7%    |
| AMD Ryzen 5             | 6         | 2.78%   |
| AMD Ryzen 7             | 5         | 2.31%   |
| Other                   | 4         | 1.85%   |
| Intel Pentium Dual      | 4         | 1.85%   |
| Intel Xeon              | 3         | 1.39%   |
| AMD FX                  | 3         | 1.39%   |
| AMD E1                  | 3         | 1.39%   |
| AMD Athlon 64 X2        | 3         | 1.39%   |
| AMD A8                  | 3         | 1.39%   |
| AMD A6                  | 3         | 1.39%   |
| Intel Pentium D         | 2         | 0.93%   |
| Intel Core 2 Quad       | 2         | 0.93%   |
| Intel Core 2            | 2         | 0.93%   |
| AMD Phenom II X4        | 2         | 0.93%   |
| AMD E                   | 2         | 0.93%   |
| AMD Athlon              | 2         | 0.93%   |
| Intel Pentium Dual-Core | 1         | 0.46%   |
| Intel Core m3           | 1         | 0.46%   |
| Intel Core i9           | 1         | 0.46%   |
| AMD Ryzen 9             | 1         | 0.46%   |
| AMD Ryzen 7 PRO         | 1         | 0.46%   |
| AMD Ryzen 5 PRO         | 1         | 0.46%   |
| AMD Phenom II X6        | 1         | 0.46%   |
| AMD GX                  | 1         | 0.46%   |
| AMD G                   | 1         | 0.46%   |
| AMD E2                  | 1         | 0.46%   |
| AMD C-60                | 1         | 0.46%   |
| AMD Athlon II X3        | 1         | 0.46%   |
| AMD Athlon II X2        | 1         | 0.46%   |
| AMD A4                  | 1         | 0.46%   |
| AMD A10                 | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 123       | 56.94%  |
| 4       | 66        | 30.56%  |
| 6       | 9         | 4.17%   |
| 8       | 7         | 3.24%   |
| 1       | 6         | 2.78%   |
| 3       | 3         | 1.39%   |
| 10      | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 215       | 99.54%  |
| Unknown | 1         | 0.46%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 123       | 56.94%  |
| 2       | 92        | 42.59%  |
| Unknown | 1         | 0.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 215       | 99.54%  |
| 64-bit         | 1         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 39.91%  |
| 0x206a7    | 11        | 5.05%   |
| 0x406c4    | 10        | 4.59%   |
| 0x306a9    | 8         | 3.67%   |
| 0x1067a    | 7         | 3.21%   |
| 0x6fd      | 5         | 2.29%   |
| 0x406c3    | 5         | 2.29%   |
| 0x806ec    | 4         | 1.83%   |
| 0x706e5    | 4         | 1.83%   |
| 0x706a8    | 4         | 1.83%   |
| 0x906c0    | 3         | 1.38%   |
| 0x806ea    | 3         | 1.38%   |
| 0x40651    | 3         | 1.38%   |
| 0x306c3    | 3         | 1.38%   |
| 0x30678    | 3         | 1.38%   |
| 0x20655    | 3         | 1.38%   |
| 0x106ca    | 3         | 1.38%   |
| 0x0a50000c | 3         | 1.38%   |
| 0x0700010f | 3         | 1.38%   |
| 0x05000119 | 3         | 1.38%   |
| 0x906ea    | 2         | 0.92%   |
| 0x806e9    | 2         | 0.92%   |
| 0x6fb      | 2         | 0.92%   |
| 0x506e3    | 2         | 0.92%   |
| 0x506c9    | 2         | 0.92%   |
| 0x30679    | 2         | 0.92%   |
| 0x06006705 | 2         | 0.92%   |
| 0x06001119 | 2         | 0.92%   |
| 0x010000db | 2         | 0.92%   |
| 0xa0653    | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x806eb    | 1         | 0.46%   |
| 0x806c1    | 1         | 0.46%   |
| 0x706a1    | 1         | 0.46%   |
| 0x6fa      | 1         | 0.46%   |
| 0x6f6      | 1         | 0.46%   |
| 0x406e3    | 1         | 0.46%   |
| 0x306e4    | 1         | 0.46%   |
| 0x20652    | 1         | 0.46%   |
| 0x106a5    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 34        | 15.74%  |
| SandyBridge   | 19        | 8.8%    |
| Penryn        | 15        | 6.94%   |
| KabyLake      | 15        | 6.94%   |
| IvyBridge     | 14        | 6.48%   |
| Core          | 14        | 6.48%   |
| Haswell       | 12        | 5.56%   |
| Goldmont plus | 9         | 4.17%   |
| Westmere      | 7         | 3.24%   |
| Zen 3         | 6         | 2.78%   |
| Piledriver    | 6         | 2.78%   |
| Skylake       | 5         | 2.31%   |
| K10           | 5         | 2.31%   |
| Bonnell       | 5         | 2.31%   |
| K8 Hammer     | 4         | 1.85%   |
| IceLake       | 4         | 1.85%   |
| Bobcat        | 4         | 1.85%   |
| Unknown       | 4         | 1.85%   |
| Zen+          | 3         | 1.39%   |
| Zen           | 3         | 1.39%   |
| Tremont       | 3         | 1.39%   |
| Jaguar        | 3         | 1.39%   |
| Goldmont      | 3         | 1.39%   |
| Excavator     | 3         | 1.39%   |
| Broadwell     | 3         | 1.39%   |
| Zen 2         | 2         | 0.93%   |
| NetBurst      | 2         | 0.93%   |
| Nehalem       | 2         | 0.93%   |
| CometLake     | 2         | 0.93%   |
| TigerLake     | 1         | 0.46%   |
| Steamroller   | 1         | 0.46%   |
| Puma          | 1         | 0.46%   |
| K10 Llano     | 1         | 0.46%   |
| Bulldozer     | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 135       | 58.44%  |
| AMD    | 53        | 22.94%  |
| Nvidia | 43        | 18.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 8.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 4.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 3.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 2.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 2.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.61%   |
| Nvidia GT218 [ION]                                                                       | 3         | 1.21%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.21%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.21%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.21%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.21%   |
| Intel HD Graphics 500                                                                    | 3         | 1.21%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.21%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.21%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.81%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.81%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.81%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.81%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.81%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.81%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.81%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2         | 0.81%   |
| AMD RV380 [Radeon X300/X550/X1050 Series] (Secondary)                                    | 2         | 0.81%   |
| AMD RV370 [Radeon X600/X600 SE]                                                          | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 118       | 54.63%  |
| 1 x AMD            | 38        | 17.59%  |
| 1 x Nvidia         | 34        | 15.74%  |
| 2 x AMD            | 7         | 3.24%   |
| Intel + Nvidia     | 6         | 2.78%   |
| Intel + AMD        | 5         | 2.31%   |
| Other              | 4         | 1.85%   |
| AMD + Nvidia       | 2         | 0.93%   |
| Intel + 2 x Nvidia | 1         | 0.46%   |
| Intel + 2 x AMD    | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 194       | 89.81%  |
| Proprietary | 14        | 6.48%   |
| Unknown     | 8         | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 165       | 75.69%  |
| 0.01-0.5   | 22        | 10.09%  |
| 1.01-2.0   | 9         | 4.13%   |
| 0.51-1.0   | 9         | 4.13%   |
| 7.01-8.0   | 5         | 2.29%   |
| 3.01-4.0   | 3         | 1.38%   |
| 2.01-3.0   | 2         | 0.92%   |
| 8.01-16.0  | 2         | 0.92%   |
| 5.01-6.0   | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 14.01%  |
| Samsung Electronics     | 25        | 12.08%  |
| LG Display              | 24        | 11.59%  |
| Chimei Innolux          | 19        | 9.18%   |
| BOE                     | 18        | 8.7%    |
| Hewlett-Packard         | 9         | 4.35%   |
| Goldstar                | 9         | 4.35%   |
| Dell                    | 8         | 3.86%   |
| Apple                   | 7         | 3.38%   |
| CPT                     | 5         | 2.42%   |
| Acer                    | 5         | 2.42%   |
| Philips                 | 4         | 1.93%   |
| Lenovo                  | 4         | 1.93%   |
| Ancor Communications    | 4         | 1.93%   |
| Sharp                   | 3         | 1.45%   |
| Eizo                    | 3         | 1.45%   |
| Chi Mei Optoelectronics | 3         | 1.45%   |
| Toshiba                 | 2         | 0.97%   |
| LG Philips              | 2         | 0.97%   |
| BenQ                    | 2         | 0.97%   |
| Westinghouse            | 1         | 0.48%   |
| Vizio                   | 1         | 0.48%   |
| ViewSonic               | 1         | 0.48%   |
| VHT                     | 1         | 0.48%   |
| Unknown (ADA)           | 1         | 0.48%   |
| Unknown                 | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| SNC                     | 1         | 0.48%   |
| Sampo                   | 1         | 0.48%   |
| Positivo                | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| LG Electronics          | 1         | 0.48%   |
| JVC                     | 1         | 0.48%   |
| Jean                    | 1         | 0.48%   |
| JDI                     | 1         | 0.48%   |
| InfoVision              | 1         | 0.48%   |
| Iiyama                  | 1         | 0.48%   |
| HannStar                | 1         | 0.48%   |
| Daewoo                  | 1         | 0.48%   |
| CS_                     | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 5         | 2.39%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.96%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.96%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.96%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.96%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 0.96%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 2         | 0.96%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch           | 1         | 0.48%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                    | 1         | 0.48%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.48%   |
| VHT Monitor VHTDDDD 1024x768                                          | 1         | 0.48%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                           | 1         | 0.48%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 1         | 0.48%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch              | 1         | 0.48%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.48%   |
| Sony TV SNY9C01 1360x768                                              | 1         | 0.48%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 1         | 0.48%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.48%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 1         | 0.48%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch              | 1         | 0.48%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.48%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch    | 1         | 0.48%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch     | 1         | 0.48%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SMT22A350 1920x1080                   | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 73        | 35.78%  |
| 1920x1080 (FHD)    | 53        | 25.98%  |
| 1280x800 (WXGA)    | 19        | 9.31%   |
| 1600x900 (HD+)     | 13        | 6.37%   |
| 1680x1050 (WSXGA+) | 9         | 4.41%   |
| 1280x1024 (SXGA)   | 7         | 3.43%   |
| 2560x1440 (QHD)    | 6         | 2.94%   |
| 1440x900 (WXGA+)   | 5         | 2.45%   |
| 1360x768           | 4         | 1.96%   |
| 3840x2160 (4K)     | 2         | 0.98%   |
| 3200x1800 (QHD+)   | 2         | 0.98%   |
| 2160x1440          | 2         | 0.98%   |
| 800x600            | 1         | 0.49%   |
| 3000x2000          | 1         | 0.49%   |
| 2560x1600          | 1         | 0.49%   |
| 2560x1080          | 1         | 0.49%   |
| 1920x1200 (WUXGA)  | 1         | 0.49%   |
| 1528x1222          | 1         | 0.49%   |
| 1280x768           | 1         | 0.49%   |
| 1280x720 (HD)      | 1         | 0.49%   |
| 1024x768 (XGA)     | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 44        | 21.36%  |
| 14      | 26        | 12.62%  |
| 13      | 22        | 10.68%  |
| 11      | 16        | 7.77%   |
| 23      | 11        | 5.34%   |
| 17      | 11        | 5.34%   |
| 18      | 9         | 4.37%   |
| 27      | 8         | 3.88%   |
| 22      | 8         | 3.88%   |
| 12      | 8         | 3.88%   |
| 24      | 7         | 3.4%    |
| 19      | 7         | 3.4%    |
| Unknown | 7         | 3.4%    |
| 21      | 6         | 2.91%   |
| 20      | 4         | 1.94%   |
| 10      | 2         | 0.97%   |
| 72      | 1         | 0.49%   |
| 49      | 1         | 0.49%   |
| 47      | 1         | 0.49%   |
| 43      | 1         | 0.49%   |
| 34      | 1         | 0.49%   |
| 28      | 1         | 0.49%   |
| 16      | 1         | 0.49%   |
| 9       | 1         | 0.49%   |
| 8       | 1         | 0.49%   |
| 7       | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 80        | 38.83%  |
| 201-300     | 41        | 19.9%   |
| 401-500     | 32        | 15.53%  |
| 501-600     | 25        | 12.14%  |
| 351-400     | 11        | 5.34%   |
| Unknown     | 7         | 3.4%    |
| 101-200     | 3         | 1.46%   |
| 601-700     | 2         | 0.97%   |
| 1001-1500   | 2         | 0.97%   |
| 701-800     | 1         | 0.49%   |
| 1501-2000   | 1         | 0.49%   |
| 901-1000    | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 142       | 72.45%  |
| 16/10   | 34        | 17.35%  |
| 5/4     | 5         | 2.55%   |
| 3/2     | 5         | 2.55%   |
| Unknown | 5         | 2.55%   |
| 4/3     | 4         | 2.04%   |
| 21/9    | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 20.98%  |
| 81-90          | 42        | 20.49%  |
| 201-250        | 27        | 13.17%  |
| 51-60          | 16        | 7.8%    |
| 151-200        | 13        | 6.34%   |
| 141-150        | 11        | 5.37%   |
| 61-70          | 8         | 3.9%    |
| 301-350        | 8         | 3.9%    |
| 121-130        | 8         | 3.9%    |
| Unknown        | 7         | 3.41%   |
| 71-80          | 6         | 2.93%   |
| 251-300        | 4         | 1.95%   |
| 41-50          | 3         | 1.46%   |
| 501-1000       | 3         | 1.46%   |
| More than 1000 | 2         | 0.98%   |
| 1-40           | 2         | 0.98%   |
| 131-140        | 1         | 0.49%   |
| 111-120        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 71        | 35.15%  |
| 51-100        | 59        | 29.21%  |
| 121-160       | 45        | 22.28%  |
| 161-240       | 13        | 6.44%   |
| Unknown       | 7         | 3.47%   |
| 1-50          | 5         | 2.48%   |
| More than 240 | 2         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 193       | 89.35%  |
| 2     | 15        | 6.94%   |
| 0     | 7         | 3.24%   |
| 3     | 1         | 0.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 108       | 34.5%   |
| Intel                           | 78        | 24.92%  |
| Qualcomm Atheros                | 47        | 15.02%  |
| Broadcom                        | 19        | 6.07%   |
| TP-Link                         | 7         | 2.24%   |
| Marvell Technology Group        | 6         | 1.92%   |
| Samsung Electronics             | 5         | 1.6%    |
| Nvidia                          | 5         | 1.6%    |
| Qualcomm Atheros Communications | 4         | 1.28%   |
| MediaTek                        | 4         | 1.28%   |
| Broadcom Limited                | 4         | 1.28%   |
| Ralink                          | 3         | 0.96%   |
| VIA Technologies                | 2         | 0.64%   |
| Qualcomm                        | 2         | 0.64%   |
| NetGear                         | 2         | 0.64%   |
| ICS Advent                      | 2         | 0.64%   |
| ASUSTek Computer                | 2         | 0.64%   |
| ASIX Electronics                | 2         | 0.64%   |
| Xiaomi                          | 1         | 0.32%   |
| Trident Microsystems            | 1         | 0.32%   |
| Texas Instruments               | 1         | 0.32%   |
| Sierra Wireless                 | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Motorola PCS                    | 1         | 0.32%   |
| Microsoft                       | 1         | 0.32%   |
| JMicron Technology              | 1         | 0.32%   |
| Dell                            | 1         | 0.32%   |
| Belkin Components               | 1         | 0.32%   |
| Accton Technology               | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 19.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.2%    |
| Intel Wireless 7265                                               | 7         | 1.92%   |
| Intel Wireless 7260                                               | 7         | 1.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 0.82%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.82%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.82%   |
| Intel Wireless 3160                                               | 3         | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.82%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.82%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.82%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.82%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 34.66%  |
| Qualcomm Atheros                | 40        | 22.73%  |
| Realtek Semiconductor           | 35        | 19.89%  |
| Broadcom                        | 12        | 6.82%   |
| TP-Link                         | 6         | 3.41%   |
| Qualcomm Atheros Communications | 4         | 2.27%   |
| MediaTek                        | 4         | 2.27%   |
| Ralink                          | 3         | 1.7%    |
| NetGear                         | 2         | 1.14%   |
| Broadcom Limited                | 2         | 1.14%   |
| ASUSTek Computer                | 2         | 1.14%   |
| Sierra Wireless                 | 1         | 0.57%   |
| Ralink Technology               | 1         | 0.57%   |
| Microsoft                       | 1         | 0.57%   |
| Dell                            | 1         | 0.57%   |
| Belkin Components               | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 8         | 4.55%   |
| Intel Wireless 7265                                                 | 7         | 3.98%   |
| Intel Wireless 7260                                                 | 7         | 3.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 6         | 3.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 6         | 3.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                    | 6         | 3.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)      | 6         | 3.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                     | 4         | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 4         | 2.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)      | 4         | 2.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                     | 4         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                        | 4         | 2.27%   |
| Realtek 802.11n WLAN Adapter                                        | 3         | 1.7%    |
| Qualcomm Atheros AR9271 802.11n                                     | 3         | 1.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 3         | 1.7%    |
| Intel Wireless 3160                                                 | 3         | 1.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection       | 3         | 1.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection               | 3         | 1.7%    |
| Intel Centrino Wireless-N 2230                                      | 3         | 1.7%    |
| Intel Centrino Advanced-N 6235                                      | 3         | 1.7%    |
| Intel Centrino Advanced-N 6200                                      | 3         | 1.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                      | 3         | 1.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 2         | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller         | 2         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter            | 2         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                          | 2         | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                              | 2         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2         | 1.14%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                           | 2         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter          | 2         | 1.14%   |
| NetGear A6210                                                       | 2         | 1.14%   |
| Intel Wireless 8265 / 8275                                          | 2         | 1.14%   |
| Intel Wireless 8260                                                 | 2         | 1.14%   |
| Intel Wireless 3165                                                 | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 2         | 1.14%   |
| Broadcom BCM43228 802.11a/b/g/n                                     | 2         | 1.14%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller | 2         | 1.14%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                               | 1         | 0.57%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                              | 1         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 92        | 49.46%  |
| Intel                    | 36        | 19.35%  |
| Qualcomm Atheros         | 15        | 8.06%   |
| Broadcom                 | 11        | 5.91%   |
| Marvell Technology Group | 6         | 3.23%   |
| Samsung Electronics      | 5         | 2.69%   |
| Nvidia                   | 5         | 2.69%   |
| VIA Technologies         | 2         | 1.08%   |
| Qualcomm                 | 2         | 1.08%   |
| ICS Advent               | 2         | 1.08%   |
| Broadcom Limited         | 2         | 1.08%   |
| ASIX Electronics         | 2         | 1.08%   |
| Xiaomi                   | 1         | 0.54%   |
| Trident Microsystems     | 1         | 0.54%   |
| TP-Link                  | 1         | 0.54%   |
| Motorola PCS             | 1         | 0.54%   |
| JMicron Technology       | 1         | 0.54%   |
| Accton Technology        | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 37.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 6.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.14%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.14%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.14%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.6%    |
| Intel Ethernet Controller I225-V                                  | 3         | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.07%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.07%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.07%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.07%   |
| Nvidia MCP77 Ethernet                                             | 2         | 1.07%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2         | 1.07%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.07%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.07%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.07%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.07%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.53%   |
| Trident Microsystems 4DWave DX                                    | 1         | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.53%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.53%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.53%   |
| Qualcomm QM215-QRD _SN:E72764DE                                   | 1         | 0.53%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.53%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 173       | 51.64%  |
| WiFi     | 161       | 48.06%  |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 122       | 57.55%  |
| Ethernet | 90        | 42.45%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 105       | 48.61%  |
| 1     | 87        | 40.28%  |
| 0     | 19        | 8.8%    |
| 3     | 4         | 1.85%   |
| 4     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 166       | 76.15%  |
| Yes  | 52        | 23.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 36.28%  |
| Realtek Semiconductor           | 16        | 14.16%  |
| Qualcomm Atheros Communications | 13        | 11.5%   |
| Broadcom                        | 8         | 7.08%   |
| Apple                           | 6         | 5.31%   |
| Foxconn / Hon Hai               | 5         | 4.42%   |
| Lite-On Technology              | 4         | 3.54%   |
| IMC Networks                    | 4         | 3.54%   |
| Cambridge Silicon Radio         | 4         | 3.54%   |
| Dell                            | 3         | 2.65%   |
| MediaTek                        | 2         | 1.77%   |
| Toshiba                         | 1         | 0.88%   |
| Syntek                          | 1         | 0.88%   |
| Ralink                          | 1         | 0.88%   |
| Logitech                        | 1         | 0.88%   |
| Hewlett-Packard                 | 1         | 0.88%   |
| ASUSTek Computer                | 1         | 0.88%   |
| Alps Electric                   | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 20.35%  |
| Realtek Bluetooth Radio                                                             | 10        | 8.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 6.19%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 4.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.42%   |
| Intel AX201 Bluetooth                                                               | 4         | 3.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.54%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.54%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 2.65%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.65%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.65%   |
| MediaTek Wireless_Device                                                            | 2         | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.77%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.77%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.88%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.88%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.88%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.88%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.88%   |
| Lite-On Wireless_Device                                                             | 1         | 0.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.88%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.88%   |
| Intel AX200 Bluetooth                                                               | 1         | 0.88%   |
| IMC Networks Bluetooth                                                              | 1         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.88%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.88%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.88%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.88%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.88%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.88%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 148       | 59.44%  |
| AMD                                          | 50        | 20.08%  |
| Nvidia                                       | 33        | 13.25%  |
| C-Media Electronics                          | 4         | 1.61%   |
| VIA Technologies                             | 3         | 1.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.4%    |
| Sony                                         | 1         | 0.4%    |
| Razer USA                                    | 1         | 0.4%    |
| MosArt Semiconductor                         | 1         | 0.4%    |
| Logitech                                     | 1         | 0.4%    |
| JMTek                                        | 1         | 0.4%    |
| Focusrite-Novation                           | 1         | 0.4%    |
| Ensoniq                                      | 1         | 0.4%    |
| EGO SYStems                                  | 1         | 0.4%    |
| Creative Labs                                | 1         | 0.4%    |
| ASUSTek Computer                             | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 6.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 5.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 4.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 3.73%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.39%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 3.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 3.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 3.05%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 2.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 2.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.36%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.36%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.36%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.02%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.02%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.02%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.02%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.02%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.02%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.68%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 20.26%  |
| SK hynix            | 27        | 17.65%  |
| Unknown             | 24        | 15.69%  |
| Micron Technology   | 21        | 13.73%  |
| Kingston            | 9         | 5.88%   |
| Nanya Technology    | 5         | 3.27%   |
| Elpida              | 5         | 3.27%   |
| Corsair             | 5         | 3.27%   |
| Unknown             | 5         | 3.27%   |
| G.Skill             | 4         | 2.61%   |
| Unknown (ABCD)      | 3         | 1.96%   |
| Smart               | 2         | 1.31%   |
| A-DATA Technology   | 2         | 1.31%   |
| Transcend           | 1         | 0.65%   |
| Ramaxel Technology  | 1         | 0.65%   |
| Novatech            | 1         | 0.65%   |
| Kllisre             | 1         | 0.65%   |
| Kingmax             | 1         | 0.65%   |
| HMD                 | 1         | 0.65%   |
| GOODRAM             | 1         | 0.65%   |
| Crucial             | 1         | 0.65%   |
| Apacer              | 1         | 0.65%   |
| AMD                 | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 3.01%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 1.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.81%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.81%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.81%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.2%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.2%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.2%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.2%    |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.2%    |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM 1067MT/s                | 2         | 1.2%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 2         | 1.2%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.6%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.6%    |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.6%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.6%    |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 1         | 0.6%    |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.6%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.6%    |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.6%    |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 66        | 47.83%  |
| DDR4    | 39        | 28.26%  |
| DDR2    | 12        | 8.7%    |
| LPDDR4  | 8         | 5.8%    |
| SDRAM   | 5         | 3.62%   |
| Unknown | 4         | 2.9%    |
| LPDDR3  | 3         | 2.17%   |
| LPDDR5  | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 90        | 65.69%  |
| DIMM         | 33        | 24.09%  |
| Row Of Chips | 11        | 8.03%   |
| Unknown      | 3         | 2.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 50        | 32.47%  |
| 2048  | 46        | 29.87%  |
| 8192  | 38        | 24.68%  |
| 16384 | 10        | 6.49%   |
| 1024  | 7         | 4.55%   |
| 32768 | 2         | 1.3%    |
| 512   | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 43        | 29.66%  |
| 3200    | 16        | 11.03%  |
| 1333    | 11        | 7.59%   |
| 2400    | 8         | 5.52%   |
| 2667    | 7         | 4.83%   |
| 1334    | 7         | 4.83%   |
| 667     | 7         | 4.83%   |
| 1066    | 5         | 3.45%   |
| 3266    | 4         | 2.76%   |
| 1866    | 4         | 2.76%   |
| 1067    | 4         | 2.76%   |
| Unknown | 4         | 2.76%   |
| 2133    | 3         | 2.07%   |
| 800     | 3         | 2.07%   |
| 4267    | 2         | 1.38%   |
| 3400    | 2         | 1.38%   |
| 2048    | 2         | 1.38%   |
| 1867    | 2         | 1.38%   |
| 975     | 2         | 1.38%   |
| 5500    | 1         | 0.69%   |
| 4199    | 1         | 0.69%   |
| 3733    | 1         | 0.69%   |
| 3666    | 1         | 0.69%   |
| 3066    | 1         | 0.69%   |
| 3000    | 1         | 0.69%   |
| 2800    | 1         | 0.69%   |
| 533     | 1         | 0.69%   |
| 333     | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 26.83%  |
| Microdia                               | 12        | 9.76%   |
| Realtek Semiconductor                  | 11        | 8.94%   |
| Sunplus Innovation Technology          | 8         | 6.5%    |
| Syntek                                 | 6         | 4.88%   |
| Apple                                  | 6         | 4.88%   |
| IMC Networks                           | 5         | 4.07%   |
| Acer                                   | 5         | 4.07%   |
| Quanta                                 | 4         | 3.25%   |
| Logitech                               | 4         | 3.25%   |
| Alcor Micro                            | 4         | 3.25%   |
| Suyin                                  | 3         | 2.44%   |
| Lenovo                                 | 3         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.44%   |
| Silicon Motion                         | 2         | 1.63%   |
| Lite-On Technology                     | 2         | 1.63%   |
| ALi                                    | 2         | 1.63%   |
| Y Media                                | 1         | 0.81%   |
| WaveRider Communications               | 1         | 0.81%   |
| USB Camera CS                          | 1         | 0.81%   |
| SunplusIT                              | 1         | 0.81%   |
| Ricoh                                  | 1         | 0.81%   |
| Pixart Imaging                         | 1         | 0.81%   |
| Microsoft                              | 1         | 0.81%   |
| Generalplus Technology                 | 1         | 0.81%   |
| Cubeternet                             | 1         | 0.81%   |
| AVerMedia Technologies                 | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 8         | 6.45%   |
| Realtek Integrated_Webcam_HD         | 4         | 3.23%   |
| Chicony HD WebCam                    | 4         | 3.23%   |
| Sunplus HD WebCam                    | 3         | 2.42%   |
| Microdia Integrated Webcam           | 3         | 2.42%   |
| Chicony HP TrueVision HD Camera      | 3         | 2.42%   |
| Apple FaceTime HD Camera             | 3         | 2.42%   |
| Realtek Lenovo EasyCamera            | 2         | 1.61%   |
| Microdia Lenovo EasyCamera           | 2         | 1.61%   |
| Microdia Integrated_Webcam_HD        | 2         | 1.61%   |
| Microdia HP Webcam-50                | 2         | 1.61%   |
| Logitech Webcam C270                 | 2         | 1.61%   |
| Lenovo Integrated Webcam             | 2         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam    | 2         | 1.61%   |
| Chicony VGA Webcam                   | 2         | 1.61%   |
| Chicony HP Truevision HD             | 2         | 1.61%   |
| Chicony FJ Camera                    | 2         | 1.61%   |
| Chicony EasyCamera                   | 2         | 1.61%   |
| Chicony 2.0M UVC Webcam / CNF7129    | 2         | 1.61%   |
| ALi WebCam                           | 2         | 1.61%   |
| Alcor Micro USB 2.0 Camera           | 2         | 1.61%   |
| Alcor Micro HD Webcam                | 2         | 1.61%   |
| Acer Lenovo EasyCamera               | 2         | 1.61%   |
| Acer Integrated Camera               | 2         | 1.61%   |
| Y Media USB Camera                   | 1         | 0.81%   |
| WaveRider USB 2.0 Camera             | 1         | 0.81%   |
| USB Camera CS USB Camera CS          | 1         | 0.81%   |
| Syntek USB2.0 Camera                 | 1         | 0.81%   |
| Syntek USB Camera Device             | 1         | 0.81%   |
| Syntek Sonix USB 2.0 Camera          | 1         | 0.81%   |
| Syntek Lenovo EasyCamera             | 1         | 0.81%   |
| Syntek Integrated Camera             | 1         | 0.81%   |
| Syntek HD WebCam                     | 1         | 0.81%   |
| Suyin VGA Webcam                     | 1         | 0.81%   |
| Suyin Intel Webcam                   | 1         | 0.81%   |
| Suyin 1.3M HD WebCam                 | 1         | 0.81%   |
| SunplusIT USB camera                 | 1         | 0.81%   |
| Sunplus Laptop Integrated Webcam FHD | 1         | 0.81%   |
| Sunplus Integrated_Webcam_HD         | 1         | 0.81%   |
| Sunplus HD User Facing               | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 20%     |
| STMicroelectronics Fingerprint Reader                  | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5%      |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5%      |
| Synaptics WBDI                                         | 1         | 5%      |
| Synaptics UWP WBDI                                     | 1         | 5%      |
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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 55.56%  |
| Alcor Micro | 2         | 22.22%  |
| O2 Micro    | 1         | 11.11%  |
| Cherry      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 167       | 76.96%  |
| 1     | 42        | 19.35%  |
| 2     | 8         | 3.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 35.09%  |
| Graphics card            | 12        | 21.05%  |
| Chipcard                 | 8         | 14.04%  |
| Net/wireless             | 5         | 8.77%   |
| Camera                   | 4         | 7.02%   |
| Bluetooth                | 2         | 3.51%   |
| Storage                  | 1         | 1.75%   |
| Sound                    | 1         | 1.75%   |
| Network                  | 1         | 1.75%   |
| Net/ethernet             | 1         | 1.75%   |
| Dvb card                 | 1         | 1.75%   |
| Communication controller | 1         | 1.75%   |

