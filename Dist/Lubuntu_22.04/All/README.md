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

Total: 315

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-43-generic          | 36        | 14.01%  |
| 5.15.0-56-generic          | 19        | 7.39%   |
| 5.15.0-60-generic          | 14        | 5.45%   |
| 5.15.0-25-generic          | 14        | 5.45%   |
| 5.15.0-47-generic          | 12        | 4.67%   |
| 5.15.0-58-generic          | 11        | 4.28%   |
| 5.15.0-30-generic          | 10        | 3.89%   |
| 5.15.0-46-generic          | 9         | 3.5%    |
| 5.15.0-41-generic          | 9         | 3.5%    |
| 5.15.0-27-generic          | 9         | 3.5%    |
| 5.19.0-35-generic          | 8         | 3.11%   |
| 5.15.0-53-generic          | 8         | 3.11%   |
| 5.15.0-52-generic          | 8         | 3.11%   |
| 5.19.0-32-generic          | 6         | 2.33%   |
| 5.15.0-67-generic          | 6         | 2.33%   |
| 5.15.0-50-generic          | 6         | 2.33%   |
| 5.15.0-48-generic          | 6         | 2.33%   |
| 5.15.0-40-generic          | 6         | 2.33%   |
| 5.15.0-57-generic          | 5         | 1.95%   |
| 5.19.0-40-generic          | 4         | 1.56%   |
| 5.19.0-38-generic          | 4         | 1.56%   |
| 5.15.0-39-generic          | 4         | 1.56%   |
| 5.15.0-35-generic          | 4         | 1.56%   |
| 5.15.0-33-generic          | 4         | 1.56%   |
| 5.19.0-41-generic          | 2         | 0.78%   |
| 5.15.0-70-generic          | 2         | 0.78%   |
| 5.15.0-37-generic          | 2         | 0.78%   |
| 5.15.0-23-generic          | 2         | 0.78%   |
| 5.15.0-18-generic          | 2         | 0.78%   |
| 6.2.8-x64v3-xanmod1        | 1         | 0.39%   |
| 6.1.12-060112-generic      | 1         | 0.39%   |
| 6.1.0-custom               | 1         | 0.39%   |
| 6.0.8-060008-generic       | 1         | 0.39%   |
| 6.0.14                     | 1         | 0.39%   |
| 6.0.12-x64v2-xanmod1       | 1         | 0.39%   |
| 6.0.10-rockchip64          | 1         | 0.39%   |
| 5.4.0-139-generic          | 1         | 0.39%   |
| 5.19.8-xanmod1             | 1         | 0.39%   |
| 5.19.11-ux360cak           | 1         | 0.39%   |
| 5.19.0-16.2-liquorix-amd64 | 1         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 203       | 84.23%  |
| 5.19.0  | 26        | 10.79%  |
| 6.2.8   | 1         | 0.41%   |
| 6.1.12  | 1         | 0.41%   |
| 6.1.0   | 1         | 0.41%   |
| 6.0.8   | 1         | 0.41%   |
| 6.0.14  | 1         | 0.41%   |
| 6.0.12  | 1         | 0.41%   |
| 6.0.10  | 1         | 0.41%   |
| 5.4.0   | 1         | 0.41%   |
| 5.19.8  | 1         | 0.41%   |
| 5.19.11 | 1         | 0.41%   |
| 5.18.0  | 1         | 0.41%   |
| 5.14.0  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 203       | 84.23%  |
| 5.19    | 28        | 11.62%  |
| 6.0     | 4         | 1.66%   |
| 6.1     | 2         | 0.83%   |
| 6.2     | 1         | 0.41%   |
| 5.4     | 1         | 0.41%   |
| 5.18    | 1         | 0.41%   |
| 5.14    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 233       | 99.15%  |
| aarch64 | 2         | 0.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXQt       | 226       | 95.76%  |
| LXDE       | 5         | 2.12%   |
| X-Cinnamon | 2         | 0.85%   |
| GNOME      | 2         | 0.85%   |
| XFCE       | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 227       | 95.78%  |
| Tty         | 7         | 2.95%   |
| Wayland     | 2         | 0.84%   |
| Unspecified | 1         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 203       | 85.65%  |
| Unknown | 14        | 5.91%   |
| LightDM | 13        | 5.49%   |
| GDM3    | 4         | 1.69%   |
| XDM     | 1         | 0.42%   |
| SLiM    | 1         | 0.42%   |
| LXDM    | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 68        | 28.81%  |
| fr_FR  | 24        | 10.17%  |
| de_DE  | 18        | 7.63%   |
| it_IT  | 17        | 7.2%    |
| en_GB  | 12        | 5.08%   |
| C      | 12        | 5.08%   |
| pt_BR  | 10        | 4.24%   |
| pl_PL  | 8         | 3.39%   |
| en_AG  | 8         | 3.39%   |
| es_ES  | 7         | 2.97%   |
| ru_RU  | 5         | 2.12%   |
| es_AR  | 5         | 2.12%   |
| en_AU  | 5         | 2.12%   |
| nl_BE  | 4         | 1.69%   |
| es_CR  | 4         | 1.69%   |
| es_MX  | 3         | 1.27%   |
| tr_TR  | 2         | 0.85%   |
| es_CO  | 2         | 0.85%   |
| en_CA  | 2         | 0.85%   |
| el_GR  | 2         | 0.85%   |
| sv_SE  | 1         | 0.42%   |
| ru_UA  | 1         | 0.42%   |
| nl_NL  | 1         | 0.42%   |
| lzh_TW | 1         | 0.42%   |
| ja_JP  | 1         | 0.42%   |
| hu_HU  | 1         | 0.42%   |
| fr_CA  | 1         | 0.42%   |
| fi_FI  | 1         | 0.42%   |
| es_PE  | 1         | 0.42%   |
| es_EC  | 1         | 0.42%   |
| es_CL  | 1         | 0.42%   |
| en_ZA  | 1         | 0.42%   |
| en_PH  | 1         | 0.42%   |
| en_DE  | 1         | 0.42%   |
| de_CH  | 1         | 0.42%   |
| cv_RU  | 1         | 0.42%   |
| cs_CZ  | 1         | 0.42%   |
| aa_DJ  | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 153       | 64.83%  |
| EFI  | 83        | 35.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 216       | 91.14%  |
| Overlay | 14        | 5.91%   |
| Btrfs   | 3         | 1.27%   |
| XXX4    | 1         | 0.42%   |
| Xfs     | 1         | 0.42%   |
| Tmpfs   | 1         | 0.42%   |
| Ext2    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 115       | 48.32%  |
| MBR     | 72        | 30.25%  |
| Unknown | 51        | 21.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 88.19%  |
| Yes       | 28        | 11.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 69.07%  |
| Yes       | 73        | 30.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 38        | 16.17%  |
| Hewlett-Packard         | 28        | 11.91%  |
| Dell                    | 27        | 11.49%  |
| ASUSTek Computer        | 23        | 9.79%   |
| Acer                    | 17        | 7.23%   |
| MSI                     | 14        | 5.96%   |
| Apple                   | 8         | 3.4%    |
| Google                  | 6         | 2.55%   |
| ASRock                  | 6         | 2.55%   |
| Unknown                 | 6         | 2.55%   |
| Intel                   | 5         | 2.13%   |
| Gigabyte Technology     | 5         | 2.13%   |
| Fujitsu                 | 5         | 2.13%   |
| Toshiba                 | 4         | 1.7%    |
| Positivo                | 4         | 1.7%    |
| AMI                     | 4         | 1.7%    |
| Sony                    | 3         | 1.28%   |
| Pegatron                | 3         | 1.28%   |
| OEM                     | 2         | 0.85%   |
| Mediacom                | 2         | 0.85%   |
| GPU Company             | 2         | 0.85%   |
| Gateway                 | 2         | 0.85%   |
| ZOTAC                   | 1         | 0.43%   |
| YANYU                   | 1         | 0.43%   |
| Thomson                 | 1         | 0.43%   |
| SGIN                    | 1         | 0.43%   |
| Samsung Electronics     | 1         | 0.43%   |
| Rockchip                | 1         | 0.43%   |
| Raspberry Pi Foundation | 1         | 0.43%   |
| Pretech                 | 1         | 0.43%   |
| Prestigio               | 1         | 0.43%   |
| Packard Bell            | 1         | 0.43%   |
| NEC Computers           | 1         | 0.43%   |
| Kiano                   | 1         | 0.43%   |
| IFSA                    | 1         | 0.43%   |
| HUAWEI                  | 1         | 0.43%   |
| Getac                   | 1         | 0.43%   |
| Fujitsu Siemens         | 1         | 0.43%   |
| ECS                     | 1         | 0.43%   |
| Chuwi                   | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 2.98%   |
| Apple MacBookPro8,1                        | 3         | 1.28%   |
| MSI MS-7C37                                | 2         | 0.85%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 0.85%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.85%   |
| Lenovo G50-30 80G0                         | 2         | 0.85%   |
| HP Pavilion g6                             | 2         | 0.85%   |
| HP Pavilion 15                             | 2         | 0.85%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.85%   |
| Dell Dimension 9100                        | 2         | 0.85%   |
| ZOTAC NM10                                 | 1         | 0.43%   |
| YANYU ITX-S192                             | 1         | 0.43%   |
| Toshiba Satellite Pro S500                 | 1         | 0.43%   |
| Toshiba Satellite P70-A                    | 1         | 0.43%   |
| Toshiba Satellite L40                      | 1         | 0.43%   |
| Toshiba Satellite C660                     | 1         | 0.43%   |
| Thomson N14C4WH64                          | 1         | 0.43%   |
| Sony VPCEB15FM                             | 1         | 0.43%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.43%   |
| Sony SVE14A2V1EW                           | 1         | 0.43%   |
| SGIN laptop                                | 1         | 0.43%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.43%   |
| Rockchip RK3318 BOX                        | 1         | 0.43%   |
| RPi Raspberry Pi                           | 1         | 0.43%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.43%   |
| Prestigio PSB141C01BFH                     | 1         | 0.43%   |
| Positivo Q232A                             | 1         | 0.43%   |
| Positivo POS-AG31AP                        | 1         | 0.43%   |
| Positivo P5VD2-MX                          | 1         | 0.43%   |
| Positivo i500pro                           | 1         | 0.43%   |
| Pegatron NC689AA-ABA s3700y                | 1         | 0.43%   |
| Pegatron h8-1350ef                         | 1         | 0.43%   |
| Pegatron AY748AA-ABA p6320y                | 1         | 0.43%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.43%   |
| OEM M882CWP                                | 1         | 0.43%   |
| NEC Computers ECS-945G                     | 1         | 0.43%   |
| MSI S12T 3M/S12 3M                         | 1         | 0.43%   |
| MSI MS-7D09                                | 1         | 0.43%   |
| MSI MS-7C96                                | 1         | 0.43%   |
| MSI MS-7C56                                | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 13        | 5.53%   |
| Lenovo ThinkPad        | 12        | 5.11%   |
| Acer Aspire            | 11        | 4.68%   |
| Dell Latitude          | 9         | 3.83%   |
| HP Pavilion            | 7         | 2.98%   |
| Unknown                | 7         | 2.98%   |
| Toshiba Satellite      | 4         | 1.7%    |
| Fujitsu LIFEBOOK       | 4         | 1.7%    |
| HP ProBook             | 3         | 1.28%   |
| HP Laptop              | 3         | 1.28%   |
| Dell XPS               | 3         | 1.28%   |
| Dell Vostro            | 3         | 1.28%   |
| Dell Precision         | 3         | 1.28%   |
| Dell OptiPlex          | 3         | 1.28%   |
| Apple MacBookPro8      | 3         | 1.28%   |
| MSI MS-7C37            | 2         | 0.85%   |
| Mediacom WinPad        | 2         | 0.85%   |
| Lenovo ThinkCentre     | 2         | 0.85%   |
| Lenovo G50-30          | 2         | 0.85%   |
| HP Compaq              | 2         | 0.85%   |
| Dell Studio            | 2         | 0.85%   |
| Dell Dimension         | 2         | 0.85%   |
| ASUS PRIME             | 2         | 0.85%   |
| ZOTAC NM10             | 1         | 0.43%   |
| YANYU ITX-S192         | 1         | 0.43%   |
| Thomson N14C4WH64      | 1         | 0.43%   |
| Sony VPCEB15FM         | 1         | 0.43%   |
| Sony VGN-SZ71WN        | 1         | 0.43%   |
| Sony SVE14A2V1EW       | 1         | 0.43%   |
| SGIN laptop            | 1         | 0.43%   |
| Samsung 300V3A         | 1         | 0.43%   |
| Rockchip RK3318        | 1         | 0.43%   |
| RPi Raspberry          | 1         | 0.43%   |
| Pretech EVE            | 1         | 0.43%   |
| Prestigio PSB141C01BFH | 1         | 0.43%   |
| Positivo Q232A         | 1         | 0.43%   |
| Positivo POS-AG31AP    | 1         | 0.43%   |
| Positivo P5VD2-MX      | 1         | 0.43%   |
| Positivo i500pro       | 1         | 0.43%   |
| Pegatron NC689AA-ABA   | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 23        | 9.79%   |
| 2013    | 21        | 8.94%   |
| 2021    | 18        | 7.66%   |
| 2019    | 18        | 7.66%   |
| 2015    | 16        | 6.81%   |
| 2012    | 15        | 6.38%   |
| 2008    | 15        | 6.38%   |
| 2020    | 14        | 5.96%   |
| 2014    | 14        | 5.96%   |
| 2010    | 14        | 5.96%   |
| 2017    | 12        | 5.11%   |
| 2016    | 12        | 5.11%   |
| 2009    | 11        | 4.68%   |
| 2018    | 10        | 4.26%   |
| 2007    | 9         | 3.83%   |
| 2022    | 7         | 2.98%   |
| 2006    | 2         | 0.85%   |
| Unknown | 2         | 0.85%   |
| 2023    | 1         | 0.43%   |
| 2001    | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 148       | 62.98%  |
| Desktop        | 71        | 30.21%  |
| Convertible    | 6         | 2.55%   |
| Tablet         | 3         | 1.28%   |
| Mini pc        | 3         | 1.28%   |
| System on chip | 2         | 0.85%   |
| All in one     | 2         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 225       | 94.94%  |
| Enabled  | 12        | 5.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 97.02%  |
| Yes  | 7         | 2.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 79        | 33.33%  |
| 4.01-8.0    | 55        | 23.21%  |
| 16.01-24.0  | 26        | 10.97%  |
| 1.01-2.0    | 26        | 10.97%  |
| 8.01-16.0   | 25        | 10.55%  |
| 32.01-64.0  | 10        | 4.22%   |
| 2.01-3.0    | 10        | 4.22%   |
| 0.51-1.0    | 3         | 1.27%   |
| 64.01-256.0 | 2         | 0.84%   |
| 24.01-32.0  | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 116       | 47.15%  |
| 0.51-1.0  | 56        | 22.76%  |
| 2.01-3.0  | 50        | 20.33%  |
| 4.01-8.0  | 13        | 5.28%   |
| 3.01-4.0  | 9         | 3.66%   |
| 8.01-16.0 | 1         | 0.41%   |
| 0.01-0.5  | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 163       | 68.49%  |
| 2      | 55        | 23.11%  |
| 3      | 9         | 3.78%   |
| 0      | 4         | 1.68%   |
| 5      | 2         | 0.84%   |
| 4      | 2         | 0.84%   |
| 12     | 1         | 0.42%   |
| 7      | 1         | 0.42%   |
| 6      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 60.85%  |
| Yes       | 92        | 39.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 80.43%  |
| No        | 46        | 19.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 76.17%  |
| No        | 56        | 23.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 53.16%  |
| No        | 111       | 46.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 43        | 18.3%   |
| France       | 25        | 10.64%  |
| Germany      | 24        | 10.21%  |
| Italy        | 19        | 8.09%   |
| Poland       | 12        | 5.11%   |
| Brazil       | 11        | 4.68%   |
| UK           | 8         | 3.4%    |
| Spain        | 8         | 3.4%    |
| Russia       | 8         | 3.4%    |
| Belgium      | 6         | 2.55%   |
| Costa Rica   | 5         | 2.13%   |
| Argentina    | 5         | 2.13%   |
| Ukraine      | 4         | 1.7%    |
| Indonesia    | 4         | 1.7%    |
| Canada       | 4         | 1.7%    |
| Australia    | 4         | 1.7%    |
| Turkey       | 3         | 1.28%   |
| Mexico       | 3         | 1.28%   |
| Vietnam      | 2         | 0.85%   |
| UAE          | 2         | 0.85%   |
| Sweden       | 2         | 0.85%   |
| Portugal     | 2         | 0.85%   |
| Netherlands  | 2         | 0.85%   |
| Latvia       | 2         | 0.85%   |
| Hungary      | 2         | 0.85%   |
| Greece       | 2         | 0.85%   |
| Colombia     | 2         | 0.85%   |
| Thailand     | 1         | 0.43%   |
| Taiwan       | 1         | 0.43%   |
| Switzerland  | 1         | 0.43%   |
| South Africa | 1         | 0.43%   |
| Saudi Arabia | 1         | 0.43%   |
| Romania      | 1         | 0.43%   |
| Philippines  | 1         | 0.43%   |
| Peru         | 1         | 0.43%   |
| Kenya        | 1         | 0.43%   |
| Japan        | 1         | 0.43%   |
| Ireland      | 1         | 0.43%   |
| Iran         | 1         | 0.43%   |
| Finland      | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 7         | 2.88%   |
| Heredia          | 4         | 1.65%   |
| Melbourne        | 3         | 1.23%   |
| Kyiv             | 3         | 1.23%   |
| Ghent            | 3         | 1.23%   |
| Eberbach         | 3         | 1.23%   |
| Warsaw           | 2         | 0.82%   |
| Sarospatak       | 2         | 0.82%   |
| Sao Paulo        | 2         | 0.82%   |
| Porto Alegre     | 2         | 0.82%   |
| Novo Gama        | 2         | 0.82%   |
| Milan            | 2         | 0.82%   |
| Largo            | 2         | 0.82%   |
| Lansing          | 2         | 0.82%   |
| Jakarta          | 2         | 0.82%   |
| Dubai            | 2         | 0.82%   |
| Chicago          | 2         | 0.82%   |
| Bogotá          | 2         | 0.82%   |
| Zizur Mayor      | 1         | 0.41%   |
| Zawiercie        | 1         | 0.41%   |
| Zagreb           | 1         | 0.41%   |
| Yoshkar-Ola      | 1         | 0.41%   |
| Yorkville        | 1         | 0.41%   |
| Yerevan          | 1         | 0.41%   |
| Yekaterinburg    | 1         | 0.41%   |
| Wolfhagen        | 1         | 0.41%   |
| Wetteren         | 1         | 0.41%   |
| West Stockbridge | 1         | 0.41%   |
| Waterlooville    | 1         | 0.41%   |
| Washington       | 1         | 0.41%   |
| Warendorf        | 1         | 0.41%   |
| Volzhskiy        | 1         | 0.41%   |
| Versailles       | 1         | 0.41%   |
| Verona           | 1         | 0.41%   |
| Varna            | 1         | 0.41%   |
| Valentigney      | 1         | 0.41%   |
| Valenciennes     | 1         | 0.41%   |
| Valencia         | 1         | 0.41%   |
| Uberlândia      | 1         | 0.41%   |
| Tyler            | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 43        | 54     | 14.38%  |
| WDC                       | 37        | 51     | 12.37%  |
| Unknown                   | 32        | 45     | 10.7%   |
| Samsung Electronics       | 30        | 40     | 10.03%  |
| Toshiba                   | 17        | 18     | 5.69%   |
| Hitachi                   | 16        | 20     | 5.35%   |
| SanDisk                   | 15        | 15     | 5.02%   |
| Kingston                  | 15        | 16     | 5.02%   |
| Crucial                   | 8         | 8      | 2.68%   |
| HGST                      | 7         | 7      | 2.34%   |
| A-DATA Technology         | 6         | 6      | 2.01%   |
| Micron Technology         | 5         | 6      | 1.67%   |
| Intel                     | 5         | 6      | 1.67%   |
| GOODRAM                   | 4         | 4      | 1.34%   |
| Transcend                 | 3         | 4      | 1%      |
| SK hynix                  | 3         | 3      | 1%      |
| Apacer                    | 3         | 3      | 1%      |
| UMIS                      | 2         | 2      | 0.67%   |
| SPCC                      | 2         | 3      | 0.67%   |
| PNY                       | 2         | 2      | 0.67%   |
| Patriot                   | 2         | 2      | 0.67%   |
| Micron/Crucial Technology | 2         | 3      | 0.67%   |
| Maxtor                    | 2         | 2      | 0.67%   |
| Fujitsu                   | 2         | 2      | 0.67%   |
| China                     | 2         | 2      | 0.67%   |
| Unknown                   | 2         | 2      | 0.67%   |
| WD MediaMax               | 1         | 1      | 0.33%   |
| W800S                     | 1         | 1      | 0.33%   |
| TO Exter                  | 1         | 1      | 0.33%   |
| Teclast                   | 1         | 1      | 0.33%   |
| Team                      | 1         | 1      | 0.33%   |
| T-FORCE                   | 1         | 1      | 0.33%   |
| Silicon Motion            | 1         | 1      | 0.33%   |
| RSH-319                   | 1         | 1      | 0.33%   |
| Rogueware                 | 1         | 1      | 0.33%   |
| Plextor                   | 1         | 1      | 0.33%   |
| Phison                    | 1         | 1      | 0.33%   |
| NGFF                      | 1         | 1      | 0.33%   |
| LITEONIT                  | 1         | 1      | 0.33%   |
| LITEON                    | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 8         | 2.43%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 1.82%   |
| Kingston SA400S37240G 240GB SSD    | 6         | 1.82%   |
| Unknown MMC Card  32GB             | 5         | 1.52%   |
| Seagate ST9500325AS 500GB          | 5         | 1.52%   |
| SanDisk DF4032  32GB               | 5         | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.91%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.61%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 2         | 0.61%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.61%   |
| Unknown SD/MMC/MS PRO 249GB        | 2         | 0.61%   |
| Unknown SC64G  64GB                | 2         | 0.61%   |
| Unknown SC256  256GB               | 2         | 0.61%   |
| Unknown NCard  32GB                | 2         | 0.61%   |
| Unknown MMC64G  64GB               | 2         | 0.61%   |
| Unknown DA4064  64GB               | 2         | 0.61%   |
| Unknown DA4032  32GB               | 2         | 0.61%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.61%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.61%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.61%   |
| Toshiba DT01ACA100 1TB             | 2         | 0.61%   |
| SPCC Solid State Disk 120GB        | 2         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.61%   |
| Seagate ST3120213AS 120GB          | 2         | 0.61%   |
| Seagate ST1000LM035-1RK172 970GB   | 2         | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.61%   |
| SanDisk SDSSDA480G 480GB           | 2         | 0.61%   |
| SanDisk DF4064  64GB               | 2         | 0.61%   |
| Samsung SSD 870 EVO 500GB          | 2         | 0.61%   |
| Samsung SSD 860 EVO 500GB          | 2         | 0.61%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.61%   |
| Samsung MZVLQ256HAJD-000H1 256GB   | 2         | 0.61%   |
| Samsung HD502HJ 500GB              | 2         | 0.61%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.61%   |
| Crucial CT500P3SSD8 500GB          | 2         | 0.61%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 0.61%   |
| Apacer 16GB SATA Flash Drive SSD   | 2         | 0.61%   |
| A-DATA SU635 240GB SSD             | 2         | 0.61%   |
| Unknown                            | 2         | 0.61%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 53     | 33.59%  |
| WDC                 | 30        | 38     | 23.44%  |
| Hitachi             | 16        | 20     | 12.5%   |
| Toshiba             | 15        | 16     | 11.72%  |
| Samsung Electronics | 7         | 12     | 5.47%   |
| HGST                | 7         | 7      | 5.47%   |
| Unknown             | 2         | 2      | 1.56%   |
| Maxtor              | 2         | 2      | 1.56%   |
| Fujitsu             | 2         | 2      | 1.56%   |
| WD MediaMax         | 1         | 1      | 0.78%   |
| RSH-319             | 1         | 1      | 0.78%   |
| External            | 1         | 1      | 0.78%   |
| Apricorn            | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 20     | 17.17%  |
| Kingston            | 13        | 14     | 13.13%  |
| SanDisk             | 7         | 7      | 7.07%   |
| WDC                 | 6         | 7      | 6.06%   |
| A-DATA Technology   | 6         | 6      | 6.06%   |
| Crucial             | 5         | 5      | 5.05%   |
| Intel               | 4         | 4      | 4.04%   |
| GOODRAM             | 4         | 4      | 4.04%   |
| Transcend           | 3         | 4      | 3.03%   |
| Micron Technology   | 3         | 3      | 3.03%   |
| Apacer              | 3         | 3      | 3.03%   |
| Toshiba             | 2         | 2      | 2.02%   |
| SPCC                | 2         | 3      | 2.02%   |
| PNY                 | 2         | 2      | 2.02%   |
| Patriot             | 2         | 2      | 2.02%   |
| W800S               | 1         | 1      | 1.01%   |
| TO Exter            | 1         | 1      | 1.01%   |
| Teclast             | 1         | 1      | 1.01%   |
| Team                | 1         | 1      | 1.01%   |
| Rogueware           | 1         | 1      | 1.01%   |
| Plextor             | 1         | 1      | 1.01%   |
| NGFF                | 1         | 1      | 1.01%   |
| LITEONIT            | 1         | 1      | 1.01%   |
| LITEON              | 1         | 1      | 1.01%   |
| Lexar               | 1         | 1      | 1.01%   |
| Leqixiang           | 1         | 1      | 1.01%   |
| Lenovo              | 1         | 1      | 1.01%   |
| Kston               | 1         | 3      | 1.01%   |
| KINGPOWER           | 1         | 1      | 1.01%   |
| HUSKY               | 1         | 1      | 1.01%   |
| Gigabyte Technology | 1         | 1      | 1.01%   |
| Emtec               | 1         | 1      | 1.01%   |
| China               | 1         | 1      | 1.01%   |
| BR                  | 1         | 1      | 1.01%   |
| 2.5"                | 1         | 2      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 109       | 156    | 39.07%  |
| SSD     | 94        | 109    | 33.69%  |
| MMC     | 40        | 54     | 14.34%  |
| NVMe    | 32        | 38     | 11.47%  |
| Unknown | 4         | 7      | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 179       | 260    | 68.85%  |
| MMC  | 40        | 54     | 15.38%  |
| NVMe | 32        | 38     | 12.31%  |
| SAS  | 9         | 12     | 3.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 185    | 70.33%  |
| 0.51-1.0   | 40        | 52     | 19.14%  |
| 1.01-2.0   | 12        | 15     | 5.74%   |
| 3.01-4.0   | 3         | 3      | 1.44%   |
| 2.01-3.0   | 3         | 4      | 1.44%   |
| 4.01-10.0  | 3         | 5      | 1.44%   |
| 10.01-20.0 | 1         | 1      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 31.09%  |
| 251-500        | 55        | 23.11%  |
| 51-100         | 28        | 11.76%  |
| 21-50          | 21        | 8.82%   |
| 1-20           | 20        | 8.4%    |
| 501-1000       | 19        | 7.98%   |
| 1001-2000      | 10        | 4.2%    |
| More than 3000 | 5         | 2.1%    |
| 2001-3000      | 5         | 2.1%    |
| Unknown        | 1         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 123       | 50.83%  |
| 21-50          | 47        | 19.42%  |
| 51-100         | 26        | 10.74%  |
| 101-250        | 21        | 8.68%   |
| 501-1000       | 8         | 3.31%   |
| 251-500        | 7         | 2.89%   |
| More than 3000 | 4         | 1.65%   |
| 1001-2000      | 4         | 1.65%   |
| 2001-3000      | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB        | 3         | 4      | 7.14%   |
| Seagate ST9500325AS 500GB                 | 2         | 2      | 4.76%   |
| Apacer 16GB SATA Flash Drive SSD          | 2         | 2      | 4.76%   |
| WDC WD60EFRX-68L0BN1 6TB                  | 1         | 2      | 2.38%   |
| WDC WD5000LPCX-60VHAT1 500GB              | 1         | 1      | 2.38%   |
| WDC WD3200AACS-00M6B0 320GB               | 1         | 1      | 2.38%   |
| WDC WD2003FYYS-02W0B0 2TB                 | 1         | 1      | 2.38%   |
| WDC WD10SPZX-24Z10T0 1TB                  | 1         | 1      | 2.38%   |
| WDC WD10SPZX-08Z10 1TB                    | 1         | 1      | 2.38%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 2.38%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1         | 1      | 2.38%   |
| WDC WD10EACS-00D6B1 1TB                   | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 2.38%   |
| Toshiba MK6465GSX 640GB                   | 1         | 1      | 2.38%   |
| Seagate ST9320325AS 320GB                 | 1         | 1      | 2.38%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 2.38%   |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1      | 2.38%   |
| Seagate ST320LT020-9YG142 320GB           | 1         | 1      | 2.38%   |
| Seagate ST320LT012-9WS14C 320GB           | 1         | 1      | 2.38%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 2.38%   |
| Seagate ST1000DM003-1SB102 1TB            | 1         | 1      | 2.38%   |
| Samsung Electronics HM121HI 120GB         | 1         | 5      | 2.38%   |
| Samsung Electronics HD161HJ 160GB         | 1         | 1      | 2.38%   |
| Plextor PX-128M6M 128GB SSD               | 1         | 1      | 2.38%   |
| NGFF 2280 512GB SSD                       | 1         | 1      | 2.38%   |
| Micron Technology MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.38%   |
| Maxtor 6L200M0 208GB                      | 1         | 1      | 2.38%   |
| Intel SSDSC2KW512G8 512GB                 | 1         | 1      | 2.38%   |
| Intel SSDSA2M080G2LE 80GB                 | 1         | 1      | 2.38%   |
| Hitachi HTS722080K9SA00 80GB              | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB             | 1         | 1      | 2.38%   |
| Hitachi HTE545050B9A300 500GB             | 1         | 1      | 2.38%   |
| HGST HTS725032A7E630 320GB                | 1         | 1      | 2.38%   |
| Fujitsu MHY2120BH 120GB                   | 1         | 1      | 2.38%   |
| A-DATA Technology SP920SS 256GB SSD       | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 32.5%   |
| WDC                 | 7         | 10     | 17.5%   |
| Toshiba             | 4         | 4      | 10%     |
| Hitachi             | 3         | 3      | 7.5%    |
| Samsung Electronics | 2         | 6      | 5%      |
| Intel               | 2         | 2      | 5%      |
| Apacer              | 2         | 2      | 5%      |
| Plextor             | 1         | 1      | 2.5%    |
| NGFF                | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 40.63%  |
| WDC                 | 7         | 10     | 21.88%  |
| Toshiba             | 4         | 4      | 12.5%   |
| Hitachi             | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 6      | 6.25%   |
| Maxtor              | 1         | 1      | 3.13%   |
| HGST                | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 40     | 79.49%  |
| SSD  | 8         | 8      | 20.51%  |

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
| Detected | 129       | 194    | 50.99%  |
| Works    | 82        | 119    | 32.41%  |
| Malfunc  | 39        | 48     | 15.42%  |
| Failed   | 3         | 3      | 1.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 62.55%  |
| AMD                              | 40        | 16.46%  |
| Samsung Electronics              | 8         | 3.29%   |
| Nvidia                           | 7         | 2.88%   |
| SanDisk                          | 5         | 2.06%   |
| Micron/Crucial Technology        | 5         | 2.06%   |
| Micron Technology                | 3         | 1.23%   |
| JMicron Technology               | 3         | 1.23%   |
| ASMedia Technology               | 3         | 1.23%   |
| VIA Technologies                 | 2         | 0.82%   |
| Union Memory (Shenzhen)          | 2         | 0.82%   |
| SK hynix                         | 2         | 0.82%   |
| Marvell Technology Group         | 2         | 0.82%   |
| Kingston Technology Company      | 2         | 0.82%   |
| Silicon Motion                   | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Silicon Image                    | 1         | 0.41%   |
| Seagate Technology               | 1         | 0.41%   |
| Phison Electronics               | 1         | 0.41%   |
| LSI Logic / Symbios Logic        | 1         | 0.41%   |
| KIOXIA                           | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 7.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 5.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 3.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 10        | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 3.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 3.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 3.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 2.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 7         | 2.42%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 2.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.42%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 2.08%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 5         | 1.73%   |
| Intel SATA Controller [RAID mode]                                                | 4         | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 1.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 3         | 1.04%   |
| Micron NVMe Storage Controller                                                   | 3         | 1.04%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.04%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 3         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                           | 3         | 1.04%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 2         | 0.69%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.69%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.69%   |
| Nvidia MCP61 SATA Controller                                                     | 2         | 0.69%   |
| Nvidia MCP61 IDE                                                                 | 2         | 0.69%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 2         | 0.69%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                 | 2         | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 167       | 65.49%  |
| IDE  | 44        | 17.25%  |
| NVMe | 31        | 12.16%  |
| RAID | 12        | 4.71%   |
| SAS  | 1         | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 186       | 79.15%  |
| AMD    | 47        | 20%     |
| ARM    | 2         | 0.85%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 2.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 2.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 2.13%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.7%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 1.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.28%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.28%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.28%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 1.28%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.28%   |
| Intel Atom CPU D525 @ 1.80GHz                 | 3         | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.28%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz        | 2         | 0.85%   |
| Intel Pentium D CPU 2.80GHz                   | 2         | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.85%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.85%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.85%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.85%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 0.85%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 2         | 0.85%   |
| ARM Processor                                 | 2         | 0.85%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 0.85%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 0.85%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 0.85%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+    | 2         | 0.85%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 2         | 0.85%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 0.85%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.43%   |
| Intel Xeon CPU E5-2630 v2 @ 2.60GHz           | 1         | 0.43%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 40        | 17.02%  |
| Intel Celeron           | 39        | 16.6%   |
| Intel Core i7           | 21        | 8.94%   |
| Intel Atom              | 20        | 8.51%   |
| Intel Core 2 Duo        | 19        | 8.09%   |
| Intel Core i3           | 18        | 7.66%   |
| Intel Pentium           | 8         | 3.4%    |
| Other                   | 6         | 2.55%   |
| AMD Ryzen 5             | 6         | 2.55%   |
| Intel Pentium Dual      | 5         | 2.13%   |
| AMD Ryzen 7             | 5         | 2.13%   |
| AMD A6                  | 4         | 1.7%    |
| Intel Xeon              | 3         | 1.28%   |
| AMD FX                  | 3         | 1.28%   |
| AMD E1                  | 3         | 1.28%   |
| AMD Athlon 64 X2        | 3         | 1.28%   |
| AMD A8                  | 3         | 1.28%   |
| Intel Pentium D         | 2         | 0.85%   |
| Intel Core 2 Quad       | 2         | 0.85%   |
| Intel Core 2            | 2         | 0.85%   |
| AMD Phenom II X4        | 2         | 0.85%   |
| AMD E2                  | 2         | 0.85%   |
| AMD E                   | 2         | 0.85%   |
| AMD Athlon              | 2         | 0.85%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Core m3           | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| Intel Celeron Dual-Core | 1         | 0.43%   |
| AMD Ryzen 9             | 1         | 0.43%   |
| AMD Ryzen 7 PRO         | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD Phenom II X6        | 1         | 0.43%   |
| AMD GX                  | 1         | 0.43%   |
| AMD G                   | 1         | 0.43%   |
| AMD C-60                | 1         | 0.43%   |
| AMD Athlon II X3        | 1         | 0.43%   |
| AMD Athlon II X2        | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 134       | 57.02%  |
| 4       | 73        | 31.06%  |
| 6       | 10        | 4.26%   |
| 8       | 7         | 2.98%   |
| 1       | 6         | 2.55%   |
| 3       | 3         | 1.28%   |
| 10      | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 234       | 99.57%  |
| Unknown | 1         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 132       | 56.17%  |
| 2       | 102       | 43.4%   |
| Unknown | 1         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 234       | 99.57%  |
| 64-bit         | 1         | 0.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 40.51%  |
| 0x206a7    | 11        | 4.64%   |
| 0x406c4    | 10        | 4.22%   |
| 0x306a9    | 9         | 3.8%    |
| 0x1067a    | 8         | 3.38%   |
| 0x706a8    | 5         | 2.11%   |
| 0x6fd      | 5         | 2.11%   |
| 0x406c3    | 5         | 2.11%   |
| 0x806ec    | 4         | 1.69%   |
| 0x706e5    | 4         | 1.69%   |
| 0x40651    | 4         | 1.69%   |
| 0x306c3    | 4         | 1.69%   |
| 0x906ea    | 3         | 1.27%   |
| 0x906c0    | 3         | 1.27%   |
| 0x806ea    | 3         | 1.27%   |
| 0x806c1    | 3         | 1.27%   |
| 0x30678    | 3         | 1.27%   |
| 0x20655    | 3         | 1.27%   |
| 0x106ca    | 3         | 1.27%   |
| 0x0a50000c | 3         | 1.27%   |
| 0x0700010f | 3         | 1.27%   |
| 0x06006705 | 3         | 1.27%   |
| 0x05000119 | 3         | 1.27%   |
| 0x806e9    | 2         | 0.84%   |
| 0x706a1    | 2         | 0.84%   |
| 0x6fb      | 2         | 0.84%   |
| 0x506e3    | 2         | 0.84%   |
| 0x506c9    | 2         | 0.84%   |
| 0x30679    | 2         | 0.84%   |
| 0x06001119 | 2         | 0.84%   |
| 0x010000db | 2         | 0.84%   |
| 0xa0653    | 1         | 0.42%   |
| 0x906ed    | 1         | 0.42%   |
| 0x806eb    | 1         | 0.42%   |
| 0x6fa      | 1         | 0.42%   |
| 0x6f6      | 1         | 0.42%   |
| 0x406e3    | 1         | 0.42%   |
| 0x306e4    | 1         | 0.42%   |
| 0x20652    | 1         | 0.42%   |
| 0x106a5    | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Silvermont    | 35        | 14.89%  |
| SandyBridge   | 19        | 8.09%   |
| Haswell       | 17        | 7.23%   |
| Penryn        | 16        | 6.81%   |
| KabyLake      | 16        | 6.81%   |
| IvyBridge     | 16        | 6.81%   |
| Core          | 15        | 6.38%   |
| Goldmont plus | 11        | 4.68%   |
| Westmere      | 8         | 3.4%    |
| Zen 3         | 6         | 2.55%   |
| Piledriver    | 6         | 2.55%   |
| Skylake       | 5         | 2.13%   |
| K10           | 5         | 2.13%   |
| Bonnell       | 5         | 2.13%   |
| K8 Hammer     | 4         | 1.7%    |
| Jaguar        | 4         | 1.7%    |
| IceLake       | 4         | 1.7%    |
| Goldmont      | 4         | 1.7%    |
| Excavator     | 4         | 1.7%    |
| Bobcat        | 4         | 1.7%    |
| Unknown       | 4         | 1.7%    |
| Zen+          | 3         | 1.28%   |
| Zen           | 3         | 1.28%   |
| Tremont       | 3         | 1.28%   |
| TigerLake     | 3         | 1.28%   |
| Broadwell     | 3         | 1.28%   |
| Zen 2         | 2         | 0.85%   |
| NetBurst      | 2         | 0.85%   |
| Nehalem       | 2         | 0.85%   |
| CometLake     | 2         | 0.85%   |
| Steamroller   | 1         | 0.43%   |
| Puma          | 1         | 0.43%   |
| K10 Llano     | 1         | 0.43%   |
| Bulldozer     | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 151       | 59.68%  |
| AMD    | 56        | 22.13%  |
| Nvidia | 46        | 18.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 8.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 4.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 4.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 2.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 2.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.48%   |
| Intel HD Graphics 500                                                                    | 4         | 1.48%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.48%   |
| Nvidia GT218 [ION]                                                                       | 3         | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.11%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.11%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.11%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.11%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.11%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.74%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.74%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.74%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.74%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.74%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.74%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 2         | 0.74%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 131       | 55.74%  |
| 1 x AMD            | 40        | 17.02%  |
| 1 x Nvidia         | 35        | 14.89%  |
| Intel + Nvidia     | 8         | 3.4%    |
| 2 x AMD            | 7         | 2.98%   |
| Intel + AMD        | 6         | 2.55%   |
| Other              | 4         | 1.7%    |
| AMD + Nvidia       | 2         | 0.85%   |
| Intel + 2 x Nvidia | 1         | 0.43%   |
| Intel + 2 x AMD    | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 211       | 89.79%  |
| Proprietary | 16        | 6.81%   |
| Unknown     | 8         | 3.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 182       | 76.79%  |
| 0.01-0.5   | 23        | 9.7%    |
| 1.01-2.0   | 10        | 4.22%   |
| 0.51-1.0   | 9         | 3.8%    |
| 7.01-8.0   | 5         | 2.11%   |
| 3.01-4.0   | 3         | 1.27%   |
| 2.01-3.0   | 2         | 0.84%   |
| 8.01-16.0  | 2         | 0.84%   |
| 5.01-6.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 14.85%  |
| Samsung Electronics     | 26        | 11.35%  |
| LG Display              | 26        | 11.35%  |
| BOE                     | 23        | 10.04%  |
| Chimei Innolux          | 20        | 8.73%   |
| Goldstar                | 10        | 4.37%   |
| Hewlett-Packard         | 9         | 3.93%   |
| Dell                    | 8         | 3.49%   |
| Apple                   | 8         | 3.49%   |
| CPT                     | 5         | 2.18%   |
| Acer                    | 5         | 2.18%   |
| Sharp                   | 4         | 1.75%   |
| Philips                 | 4         | 1.75%   |
| Lenovo                  | 4         | 1.75%   |
| Chi Mei Optoelectronics | 4         | 1.75%   |
| Ancor Communications    | 4         | 1.75%   |
| Toshiba                 | 3         | 1.31%   |
| Eizo                    | 3         | 1.31%   |
| LG Philips              | 2         | 0.87%   |
| HannStar                | 2         | 0.87%   |
| BenQ                    | 2         | 0.87%   |
| Westinghouse            | 1         | 0.44%   |
| Vizio                   | 1         | 0.44%   |
| ViewSonic               | 1         | 0.44%   |
| VHT                     | 1         | 0.44%   |
| Unknown (ADA)           | 1         | 0.44%   |
| Unknown                 | 1         | 0.44%   |
| Sony                    | 1         | 0.44%   |
| SNC                     | 1         | 0.44%   |
| Sampo                   | 1         | 0.44%   |
| Positivo                | 1         | 0.44%   |
| MSI                     | 1         | 0.44%   |
| LLL                     | 1         | 0.44%   |
| LG Electronics          | 1         | 0.44%   |
| JVC                     | 1         | 0.44%   |
| Jean                    | 1         | 0.44%   |
| JDI                     | 1         | 0.44%   |
| InfoVision              | 1         | 0.44%   |
| Iiyama                  | 1         | 0.44%   |
| Daewoo                  | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 5         | 2.16%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 3         | 1.3%    |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch   | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 2         | 0.87%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch          | 2         | 0.87%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.87%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 2         | 0.87%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                 | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 2         | 0.87%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                 | 2         | 0.87%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch        | 2         | 0.87%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 2         | 0.87%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch          | 1         | 0.43%   |
| Vizio VO420E VIZ0050 1920x1080 930x520mm 41.9-inch                   | 1         | 0.43%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch        | 1         | 0.43%   |
| VHT Monitor VHTDDDD 1024x768                                         | 1         | 0.43%   |
| Unknown LCD Monitor DELL3007WFPHC 2560x1600                          | 1         | 0.43%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch        | 1         | 0.43%   |
| Toshiba TV TSB0108 1360x768 576x324mm 26.0-inch                      | 1         | 0.43%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch             | 1         | 0.43%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch             | 1         | 0.43%   |
| Sony TV SNY9C01 1360x768                                             | 1         | 0.43%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                  | 1         | 0.43%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP141B 1920x1080 294x165mm 13.3-inch              | 1         | 0.43%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch              | 1         | 0.43%   |
| Sharp LC-50LB481U SHP5063 1920x1080 1100x620mm 49.7-inch             | 1         | 0.43%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch    | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM03D2 1680x1050 474x296mm 22.0-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1         | 0.43%   |
| Samsung Electronics SMS19A450 SAM0833 1440x900 408x255mm 18.9-inch   | 1         | 0.43%   |
| Samsung Electronics S27B350 SAM08DC 1920x1080 598x336mm 27.0-inch    | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 85        | 37.61%  |
| 1920x1080 (FHD)    | 60        | 26.55%  |
| 1280x800 (WXGA)    | 19        | 8.41%   |
| 1600x900 (HD+)     | 14        | 6.19%   |
| 1680x1050 (WSXGA+) | 9         | 3.98%   |
| 1280x1024 (SXGA)   | 8         | 3.54%   |
| 2560x1440 (QHD)    | 6         | 2.65%   |
| 1440x900 (WXGA+)   | 5         | 2.21%   |
| 1360x768           | 4         | 1.77%   |
| 3840x2160 (4K)     | 2         | 0.88%   |
| 3200x1800 (QHD+)   | 2         | 0.88%   |
| 2160x1440          | 2         | 0.88%   |
| 800x600            | 1         | 0.44%   |
| 3000x2000          | 1         | 0.44%   |
| 2560x1600          | 1         | 0.44%   |
| 2560x1080          | 1         | 0.44%   |
| 1920x540           | 1         | 0.44%   |
| 1920x1200 (WUXGA)  | 1         | 0.44%   |
| 1528x1222          | 1         | 0.44%   |
| 1280x768           | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |
| 1024x768 (XGA)     | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 52        | 22.81%  |
| 14      | 27        | 11.84%  |
| 13      | 26        | 11.4%   |
| 11      | 17        | 7.46%   |
| 17      | 12        | 5.26%   |
| 23      | 11        | 4.82%   |
| 18      | 9         | 3.95%   |
| 12      | 9         | 3.95%   |
| 27      | 8         | 3.51%   |
| 22      | 8         | 3.51%   |
| 21      | 8         | 3.51%   |
| 19      | 8         | 3.51%   |
| Unknown | 8         | 3.51%   |
| 24      | 7         | 3.07%   |
| 20      | 4         | 1.75%   |
| 72      | 2         | 0.88%   |
| 10      | 2         | 0.88%   |
| 49      | 1         | 0.44%   |
| 47      | 1         | 0.44%   |
| 44      | 1         | 0.44%   |
| 43      | 1         | 0.44%   |
| 34      | 1         | 0.44%   |
| 28      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |
| 9       | 1         | 0.44%   |
| 8       | 1         | 0.44%   |
| 7       | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 39.91%  |
| 201-300     | 45        | 19.74%  |
| 401-500     | 34        | 14.91%  |
| 501-600     | 25        | 10.96%  |
| 351-400     | 13        | 5.7%    |
| Unknown     | 8         | 3.51%   |
| 101-200     | 3         | 1.32%   |
| 601-700     | 2         | 0.88%   |
| 1501-2000   | 2         | 0.88%   |
| 1001-1500   | 2         | 0.88%   |
| 901-1000    | 2         | 0.88%   |
| 701-800     | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 159       | 73.95%  |
| 16/10   | 34        | 15.81%  |
| 5/4     | 6         | 2.79%   |
| Unknown | 6         | 2.79%   |
| 3/2     | 5         | 2.33%   |
| 4/3     | 4         | 1.86%   |
| 21/9    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 22.47%  |
| 81-90          | 45        | 19.82%  |
| 201-250        | 29        | 12.78%  |
| 51-60          | 17        | 7.49%   |
| 151-200        | 14        | 6.17%   |
| 141-150        | 11        | 4.85%   |
| 61-70          | 9         | 3.96%   |
| 71-80          | 8         | 3.52%   |
| 301-350        | 8         | 3.52%   |
| 121-130        | 8         | 3.52%   |
| Unknown        | 8         | 3.52%   |
| 251-300        | 4         | 1.76%   |
| 501-1000       | 4         | 1.76%   |
| More than 1000 | 3         | 1.32%   |
| 41-50          | 3         | 1.32%   |
| 1-40           | 2         | 0.88%   |
| 131-140        | 2         | 0.88%   |
| 111-120        | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 82        | 36.77%  |
| 51-100        | 61        | 27.35%  |
| 121-160       | 48        | 21.52%  |
| 161-240       | 15        | 6.73%   |
| Unknown       | 8         | 3.59%   |
| 1-50          | 7         | 3.14%   |
| More than 240 | 2         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 208       | 88.51%  |
| 2     | 19        | 8.09%   |
| 0     | 7         | 2.98%   |
| 3     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 120       | 35.29%  |
| Intel                             | 85        | 25%     |
| Qualcomm Atheros                  | 49        | 14.41%  |
| Broadcom                          | 20        | 5.88%   |
| TP-Link                           | 7         | 2.06%   |
| Marvell Technology Group          | 7         | 2.06%   |
| Samsung Electronics               | 5         | 1.47%   |
| Ralink                            | 5         | 1.47%   |
| Nvidia                            | 5         | 1.47%   |
| Qualcomm Atheros Communications   | 4         | 1.18%   |
| MediaTek                          | 4         | 1.18%   |
| Broadcom Limited                  | 4         | 1.18%   |
| VIA Technologies                  | 2         | 0.59%   |
| Ralink Technology                 | 2         | 0.59%   |
| Qualcomm                          | 2         | 0.59%   |
| NetGear                           | 2         | 0.59%   |
| ICS Advent                        | 2         | 0.59%   |
| ASUSTek Computer                  | 2         | 0.59%   |
| ASIX Electronics                  | 2         | 0.59%   |
| Xiaomi                            | 1         | 0.29%   |
| Trident Microsystems              | 1         | 0.29%   |
| Texas Instruments                 | 1         | 0.29%   |
| Sierra Wireless                   | 1         | 0.29%   |
| Motorola PCS                      | 1         | 0.29%   |
| Microsoft                         | 1         | 0.29%   |
| JMicron Technology                | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| Belkin Components                 | 1         | 0.29%   |
| Accton Technology                 | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 17.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 2.24%   |
| Intel Wireless 7260                                               | 9         | 2.24%   |
| Intel Wireless 7265                                               | 8         | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.24%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 5         | 1.24%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.75%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.75%   |
| Intel Wireless 3160                                               | 3         | 0.75%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.75%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.75%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.75%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 34.87%  |
| Qualcomm Atheros                | 42        | 21.54%  |
| Realtek Semiconductor           | 41        | 21.03%  |
| Broadcom                        | 13        | 6.67%   |
| TP-Link                         | 6         | 3.08%   |
| Ralink                          | 5         | 2.56%   |
| Qualcomm Atheros Communications | 4         | 2.05%   |
| MediaTek                        | 4         | 2.05%   |
| Ralink Technology               | 2         | 1.03%   |
| NetGear                         | 2         | 1.03%   |
| Broadcom Limited                | 2         | 1.03%   |
| ASUSTek Computer                | 2         | 1.03%   |
| Sierra Wireless                 | 1         | 0.51%   |
| Microsoft                       | 1         | 0.51%   |
| Dell                            | 1         | 0.51%   |
| Belkin Components               | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 4.59%   |
| Intel Wireless 7260                                            | 9         | 4.59%   |
| Intel Wireless 7265                                            | 8         | 4.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 3.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5         | 2.55%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 2.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.53%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 1.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.53%   |
| Intel Wireless 3160                                            | 3         | 1.53%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 1.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.53%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.53%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.53%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 1.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 1.02%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.02%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.02%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.02%   |
| NetGear A6210                                                  | 2         | 1.02%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.02%   |
| Intel Wireless 8260                                            | 2         | 1.02%   |
| Intel Wireless 3165                                            | 2         | 1.02%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.02%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 103       | 51.24%  |
| Intel                    | 39        | 19.4%   |
| Qualcomm Atheros         | 16        | 7.96%   |
| Broadcom                 | 12        | 5.97%   |
| Marvell Technology Group | 7         | 3.48%   |
| Nvidia                   | 5         | 2.49%   |
| Samsung Electronics      | 3         | 1.49%   |
| VIA Technologies         | 2         | 1%      |
| Qualcomm                 | 2         | 1%      |
| ICS Advent               | 2         | 1%      |
| Broadcom Limited         | 2         | 1%      |
| ASIX Electronics         | 2         | 1%      |
| Xiaomi                   | 1         | 0.5%    |
| Trident Microsystems     | 1         | 0.5%    |
| TP-Link                  | 1         | 0.5%    |
| Motorola PCS             | 1         | 0.5%    |
| JMicron Technology       | 1         | 0.5%    |
| Accton Technology        | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72        | 35.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 8.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 2.97%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.49%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.99%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.99%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2         | 0.99%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.5%    |
| Trident Microsystems 4DWave DX                                    | 1         | 0.5%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.5%    |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.5%    |
| Qualcomm SM7250-PICASSO _SN:6897A937                              | 1         | 0.5%    |
| Qualcomm Nokia XR20                                               | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.5%    |
| Nvidia MCP89 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.5%    |
| Motorola PCS motorola razr 2022                                   | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189       | 50.81%  |
| WiFi     | 179       | 48.12%  |
| Modem    | 4         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 58.19%  |
| Ethernet | 97        | 41.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 118       | 50.21%  |
| 1     | 91        | 38.72%  |
| 0     | 21        | 8.94%   |
| 3     | 4         | 1.7%    |
| 4     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 75.53%  |
| Yes  | 58        | 24.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 37.3%   |
| Realtek Semiconductor           | 18        | 14.29%  |
| Qualcomm Atheros Communications | 13        | 10.32%  |
| Broadcom                        | 8         | 6.35%   |
| Apple                           | 7         | 5.56%   |
| Foxconn / Hon Hai               | 5         | 3.97%   |
| Lite-On Technology              | 4         | 3.17%   |
| IMC Networks                    | 4         | 3.17%   |
| Cambridge Silicon Radio         | 4         | 3.17%   |
| Ralink                          | 3         | 2.38%   |
| Dell                            | 3         | 2.38%   |
| Toshiba                         | 2         | 1.59%   |
| MediaTek                        | 2         | 1.59%   |
| Hewlett-Packard                 | 2         | 1.59%   |
| Syntek                          | 1         | 0.79%   |
| Logitech                        | 1         | 0.79%   |
| ASUSTek Computer                | 1         | 0.79%   |
| Alps Electric                   | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 26        | 20.47%  |
| Realtek Bluetooth Radio                                                             | 10        | 7.87%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 6.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 4.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.94%   |
| Intel AX201 Bluetooth                                                               | 5         | 3.94%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 3.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.15%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.15%   |
| Apple Bluetooth Host Controller                                                     | 4         | 3.15%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.36%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.36%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.36%   |
| Intel AX200 Bluetooth                                                               | 3         | 2.36%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.36%   |
| MediaTek Wireless_Device                                                            | 2         | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.57%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.57%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.79%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.79%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.79%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.79%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.79%   |
| Logitech BT Mini-Receiver (HCI mode)                                                | 1         | 0.79%   |
| Lite-On Wireless_Device                                                             | 1         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.79%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.79%   |
| IMC Networks Bluetooth                                                              | 1         | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.79%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.79%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.79%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.79%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.79%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 165       | 61.34%  |
| AMD                                          | 52        | 19.33%  |
| Nvidia                                       | 34        | 12.64%  |
| C-Media Electronics                          | 4         | 1.49%   |
| VIA Technologies                             | 3         | 1.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.37%   |
| Sony                                         | 1         | 0.37%   |
| Razer USA                                    | 1         | 0.37%   |
| MosArt Semiconductor                         | 1         | 0.37%   |
| Logitech                                     | 1         | 0.37%   |
| JMTek                                        | 1         | 0.37%   |
| Focusrite-Novation                           | 1         | 0.37%   |
| Ensoniq                                      | 1         | 0.37%   |
| EGO SYStems                                  | 1         | 0.37%   |
| Creative Labs                                | 1         | 0.37%   |
| ASUSTek Computer                             | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 6.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 5.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 3.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 3.43%   |
| AMD FCH Azalia Controller                                                                         | 11        | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 3.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.8%    |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.8%    |
| Nvidia High Definition Audio Controller                                                           | 8         | 2.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.49%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 2.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.25%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.25%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 1.25%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.93%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.93%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.93%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.93%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 20.73%  |
| SK hynix            | 28        | 17.07%  |
| Unknown             | 25        | 15.24%  |
| Micron Technology   | 22        | 13.41%  |
| Kingston            | 9         | 5.49%   |
| Unknown             | 6         | 3.66%   |
| Nanya Technology    | 5         | 3.05%   |
| G.Skill             | 5         | 3.05%   |
| Elpida              | 5         | 3.05%   |
| Corsair             | 5         | 3.05%   |
| Unknown (ABCD)      | 4         | 2.44%   |
| Smart               | 2         | 1.22%   |
| A-DATA Technology   | 2         | 1.22%   |
| Transcend           | 1         | 0.61%   |
| Toshiba             | 1         | 0.61%   |
| Ramaxel Technology  | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |
| Novatech            | 1         | 0.61%   |
| Kllisre             | 1         | 0.61%   |
| Kingmax             | 1         | 0.61%   |
| HMD                 | 1         | 0.61%   |
| GOODRAM             | 1         | 0.61%   |
| Crucial             | 1         | 0.61%   |
| Apacer              | 1         | 0.61%   |
| AMD                 | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 6         | 3.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.12%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.12%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.12%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.12%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.12%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.12%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1.12%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 2         | 1.12%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                             | 1         | 0.56%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM                                      | 1         | 0.56%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.56%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.56%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.56%   |
| Unknown RAM GSA8G4SCL156P-21 8192MB SODIMM DDR4 2133MT/s         | 1         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.56%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.56%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 0.56%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 46.62%  |
| DDR4    | 43        | 29.05%  |
| DDR2    | 13        | 8.78%   |
| LPDDR4  | 10        | 6.76%   |
| SDRAM   | 5         | 3.38%   |
| Unknown | 4         | 2.7%    |
| LPDDR3  | 3         | 2.03%   |
| LPDDR5  | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 66.67%  |
| DIMM         | 34        | 23.13%  |
| Row Of Chips | 12        | 8.16%   |
| Unknown      | 3         | 2.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 52        | 31.71%  |
| 2048  | 46        | 28.05%  |
| 8192  | 45        | 27.44%  |
| 16384 | 10        | 6.1%    |
| 1024  | 8         | 4.88%   |
| 32768 | 2         | 1.22%   |
| 512   | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 46        | 29.49%  |
| 3200    | 18        | 11.54%  |
| 1333    | 11        | 7.05%   |
| 2400    | 9         | 5.77%   |
| 2667    | 8         | 5.13%   |
| 1334    | 7         | 4.49%   |
| 667     | 7         | 4.49%   |
| 1066    | 6         | 3.85%   |
| 1866    | 5         | 3.21%   |
| 3266    | 4         | 2.56%   |
| 1067    | 4         | 2.56%   |
| Unknown | 4         | 2.56%   |
| 4267    | 3         | 1.92%   |
| 2133    | 3         | 1.92%   |
| 800     | 3         | 1.92%   |
| 3400    | 2         | 1.28%   |
| 2800    | 2         | 1.28%   |
| 2048    | 2         | 1.28%   |
| 1867    | 2         | 1.28%   |
| 975     | 2         | 1.28%   |
| 5500    | 1         | 0.64%   |
| 4199    | 1         | 0.64%   |
| 3933    | 1         | 0.64%   |
| 3733    | 1         | 0.64%   |
| 3666    | 1         | 0.64%   |
| 3066    | 1         | 0.64%   |
| 533     | 1         | 0.64%   |
| 333     | 1         | 0.64%   |

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
| Canon LiDE 300          | 1         | 16.67%  |
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
| Chicony Electronics                    | 36        | 26.28%  |
| Realtek Semiconductor                  | 14        | 10.22%  |
| Microdia                               | 13        | 9.49%   |
| Sunplus Innovation Technology          | 8         | 5.84%   |
| Apple                                  | 7         | 5.11%   |
| Syntek                                 | 6         | 4.38%   |
| Quanta                                 | 5         | 3.65%   |
| IMC Networks                           | 5         | 3.65%   |
| Suyin                                  | 4         | 2.92%   |
| Logitech                               | 4         | 2.92%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.92%   |
| Bison Electronics                      | 4         | 2.92%   |
| Alcor Micro                            | 4         | 2.92%   |
| Lenovo                                 | 3         | 2.19%   |
| Silicon Motion                         | 2         | 1.46%   |
| Lite-On Technology                     | 2         | 1.46%   |
| ALi                                    | 2         | 1.46%   |
| Acer                                   | 2         | 1.46%   |
| Y Media                                | 1         | 0.73%   |
| WaveRider Communications               | 1         | 0.73%   |
| USB Camera CS                          | 1         | 0.73%   |
| SunplusIT                              | 1         | 0.73%   |
| Ricoh                                  | 1         | 0.73%   |
| Pixart Imaging                         | 1         | 0.73%   |
| Microsoft                              | 1         | 0.73%   |
| icSpring                               | 1         | 0.73%   |
| Generalplus Technology                 | 1         | 0.73%   |
| GEMBIRD                                | 1         | 0.73%   |
| Cubeternet                             | 1         | 0.73%   |
| AVerMedia Technologies                 | 1         | 0.73%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 9         | 6.52%   |
| Chicony HD WebCam                    | 4         | 2.9%    |
| Sunplus HD WebCam                    | 3         | 2.17%   |
| Realtek Integrated_Webcam_HD         | 3         | 2.17%   |
| Microdia Integrated_Webcam_HD        | 3         | 2.17%   |
| Microdia Integrated Webcam           | 3         | 2.17%   |
| Chicony HP TrueVision HD Camera      | 3         | 2.17%   |
| Apple FaceTime HD Camera             | 3         | 2.17%   |
| Realtek USB Camera                   | 2         | 1.45%   |
| Realtek Lenovo EasyCamera            | 2         | 1.45%   |
| Realtek Integrated Webcam HD         | 2         | 1.45%   |
| Microdia Lenovo EasyCamera           | 2         | 1.45%   |
| Microdia HP Webcam-50                | 2         | 1.45%   |
| Logitech Webcam C270                 | 2         | 1.45%   |
| Lenovo Integrated Webcam             | 2         | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam    | 2         | 1.45%   |
| Chicony VGA Webcam                   | 2         | 1.45%   |
| Chicony HP Truevision HD             | 2         | 1.45%   |
| Chicony FJ Camera                    | 2         | 1.45%   |
| Chicony EasyCamera                   | 2         | 1.45%   |
| Chicony 2.0M UVC Webcam / CNF7129    | 2         | 1.45%   |
| Bison Integrated Camera              | 2         | 1.45%   |
| ALi WebCam                           | 2         | 1.45%   |
| Alcor Micro USB 2.0 HD Camera        | 2         | 1.45%   |
| Alcor Micro SHUNCCM2MP               | 2         | 1.45%   |
| Y Media USB Camera                   | 1         | 0.72%   |
| WaveRider USB 2.0 Camera             | 1         | 0.72%   |
| USB Camera CS USB Camera CS          | 1         | 0.72%   |
| Syntek USB2.0 Camera                 | 1         | 0.72%   |
| Syntek USB Camera Device             | 1         | 0.72%   |
| Syntek Sonix USB 2.0 Camera          | 1         | 0.72%   |
| Syntek Lenovo EasyCamera             | 1         | 0.72%   |
| Syntek Integrated Camera             | 1         | 0.72%   |
| Syntek HD WebCam                     | 1         | 0.72%   |
| Suyin VGA Webcam                     | 1         | 0.72%   |
| Suyin Intel Webcam                   | 1         | 0.72%   |
| Suyin HP Webcam-101                  | 1         | 0.72%   |
| Suyin 1.3M HD WebCam                 | 1         | 0.72%   |
| SunplusIT USB camera                 | 1         | 0.72%   |
| Sunplus Laptop Integrated Webcam FHD | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 23.81%  |
| Upek                       | 4         | 19.05%  |
| AuthenTec                  | 4         | 19.05%  |
| Synaptics                  | 2         | 9.52%   |
| STMicroelectronics         | 2         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 9.52%   |
| LighTuning Technology      | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 19.05%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 9.52%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 9.52%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.76%   |
| Synaptics WBDI                                         | 1         | 4.76%   |
| Synaptics UWP WBDI                                     | 1         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.76%   |
| AuthenTec AES2810                                      | 1         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.76%   |
| AuthenTec AES1600                                      | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 45.45%  |
| Alcor Micro | 3         | 27.27%  |
| O2 Micro    | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |
| Cherry      | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor | 2         | 18.18%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader            | 1         | 9.09%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC    | 1         | 9.09%   |
| Alcor Micro Watchdata W 1981                   | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 180       | 76.27%  |
| 1     | 47        | 19.92%  |
| 2     | 8         | 3.39%   |
| 3     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 20        | 31.25%  |
| Graphics card            | 13        | 20.31%  |
| Chipcard                 | 10        | 15.63%  |
| Net/wireless             | 5         | 7.81%   |
| Camera                   | 4         | 6.25%   |
| Bluetooth                | 4         | 6.25%   |
| Network                  | 2         | 3.13%   |
| Storage                  | 1         | 1.56%   |
| Sound                    | 1         | 1.56%   |
| Net/ethernet             | 1         | 1.56%   |
| Multimedia controller    | 1         | 1.56%   |
| Dvb card                 | 1         | 1.56%   |
| Communication controller | 1         | 1.56%   |

