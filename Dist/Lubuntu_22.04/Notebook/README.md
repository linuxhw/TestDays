Lubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 204

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Google        | Celes                       | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.0-43-generic      | 22        | 13.41%  |
| 5.15.0-56-generic      | 14        | 8.54%   |
| 5.15.0-58-generic      | 9         | 5.49%   |
| 5.15.0-25-generic      | 9         | 5.49%   |
| 5.15.0-60-generic      | 8         | 4.88%   |
| 5.15.0-30-generic      | 8         | 4.88%   |
| 5.15.0-47-generic      | 7         | 4.27%   |
| 5.15.0-46-generic      | 7         | 4.27%   |
| 5.19.0-35-generic      | 6         | 3.66%   |
| 5.15.0-52-generic      | 6         | 3.66%   |
| 5.15.0-27-generic      | 6         | 3.66%   |
| 5.15.0-53-generic      | 5         | 3.05%   |
| 5.19.0-40-generic      | 4         | 2.44%   |
| 5.19.0-38-generic      | 4         | 2.44%   |
| 5.15.0-57-generic      | 4         | 2.44%   |
| 5.15.0-50-generic      | 4         | 2.44%   |
| 5.15.0-41-generic      | 4         | 2.44%   |
| 5.19.0-32-generic      | 3         | 1.83%   |
| 5.15.0-67-generic      | 3         | 1.83%   |
| 5.15.0-48-generic      | 3         | 1.83%   |
| 5.15.0-40-generic      | 3         | 1.83%   |
| 5.15.0-35-generic      | 3         | 1.83%   |
| 5.15.0-70-generic      | 2         | 1.22%   |
| 5.15.0-37-generic      | 2         | 1.22%   |
| 5.15.0-33-generic      | 2         | 1.22%   |
| 6.1.12-060112-generic  | 1         | 0.61%   |
| 6.0.12-x64v2-xanmod1   | 1         | 0.61%   |
| 5.4.0-139-generic      | 1         | 0.61%   |
| 5.19.8-xanmod1         | 1         | 0.61%   |
| 5.19.0-41-generic      | 1         | 0.61%   |
| 5.19.0-1021-lowlatency | 1         | 0.61%   |
| 5.19.0-051900-generic  | 1         | 0.61%   |
| 5.18.0-051800-generic  | 1         | 0.61%   |
| 5.15.0-71-generic      | 1         | 0.61%   |
| 5.15.0-69-generic      | 1         | 0.61%   |
| 5.15.0-54-generic      | 1         | 0.61%   |
| 5.15.0-39-generic      | 1         | 0.61%   |
| 5.15.0-28-generic      | 1         | 0.61%   |
| 5.15.0-23-generic      | 1         | 0.61%   |
| 5.15.0-18-generic      | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 127       | 83.55%  |
| 5.19.0  | 19        | 12.5%   |
| 6.1.12  | 1         | 0.66%   |
| 6.0.12  | 1         | 0.66%   |
| 5.4.0   | 1         | 0.66%   |
| 5.19.8  | 1         | 0.66%   |
| 5.18.0  | 1         | 0.66%   |
| 5.14.0  | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 127       | 83.55%  |
| 5.19    | 20        | 13.16%  |
| 6.1     | 1         | 0.66%   |
| 6.0     | 1         | 0.66%   |
| 5.4     | 1         | 0.66%   |
| 5.18    | 1         | 0.66%   |
| 5.14    | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 148       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 144       | 97.3%   |
| X-Cinnamon | 2         | 1.35%   |
| LXDE       | 2         | 1.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 146       | 98.65%  |
| Tty  | 2         | 1.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 131       | 87.92%  |
| Unknown | 9         | 6.04%   |
| LightDM | 8         | 5.37%   |
| GDM3    | 1         | 0.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 42        | 28.19%  |
| fr_FR  | 13        | 8.72%   |
| it_IT  | 10        | 6.71%   |
| C      | 10        | 6.71%   |
| de_DE  | 9         | 6.04%   |
| pt_BR  | 8         | 5.37%   |
| pl_PL  | 7         | 4.7%    |
| en_GB  | 6         | 4.03%   |
| en_AG  | 6         | 4.03%   |
| ru_RU  | 5         | 3.36%   |
| nl_BE  | 3         | 2.01%   |
| en_AU  | 3         | 2.01%   |
| es_MX  | 2         | 1.34%   |
| es_ES  | 2         | 1.34%   |
| es_CR  | 2         | 1.34%   |
| es_CO  | 2         | 1.34%   |
| es_AR  | 2         | 1.34%   |
| en_CA  | 2         | 1.34%   |
| tr_TR  | 1         | 0.67%   |
| nl_NL  | 1         | 0.67%   |
| lzh_TW | 1         | 0.67%   |
| ja_JP  | 1         | 0.67%   |
| hu_HU  | 1         | 0.67%   |
| fr_CA  | 1         | 0.67%   |
| fi_FI  | 1         | 0.67%   |
| es_EC  | 1         | 0.67%   |
| es_CL  | 1         | 0.67%   |
| en_ZA  | 1         | 0.67%   |
| en_PH  | 1         | 0.67%   |
| en_DE  | 1         | 0.67%   |
| el_GR  | 1         | 0.67%   |
| de_CH  | 1         | 0.67%   |
| aa_DJ  | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 96        | 64.43%  |
| EFI  | 53        | 35.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 133       | 88.67%  |
| Overlay | 12        | 8%      |
| Btrfs   | 2         | 1.33%   |
| Xfs     | 1         | 0.67%   |
| Tmpfs   | 1         | 0.67%   |
| Ext2    | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 75        | 49.67%  |
| MBR     | 46        | 30.46%  |
| Unknown | 30        | 19.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 90.67%  |
| Yes       | 14        | 9.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 73.83%  |
| Yes       | 39        | 26.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 22.3%   |
| Hewlett-Packard     | 22        | 14.86%  |
| Dell                | 17        | 11.49%  |
| Acer                | 15        | 10.14%  |
| ASUSTek Computer    | 9         | 6.08%   |
| Google              | 6         | 4.05%   |
| Apple               | 6         | 4.05%   |
| Toshiba             | 4         | 2.7%    |
| Fujitsu             | 4         | 2.7%    |
| Sony                | 3         | 2.03%   |
| Unknown             | 3         | 2.03%   |
| Positivo            | 2         | 1.35%   |
| Mediacom            | 2         | 1.35%   |
| Intel               | 2         | 1.35%   |
| GPU Company         | 2         | 1.35%   |
| Gateway             | 2         | 1.35%   |
| Thomson             | 1         | 0.68%   |
| SGIN                | 1         | 0.68%   |
| Samsung Electronics | 1         | 0.68%   |
| Pretech             | 1         | 0.68%   |
| Prestigio           | 1         | 0.68%   |
| Packard Bell        | 1         | 0.68%   |
| OEM                 | 1         | 0.68%   |
| MSI                 | 1         | 0.68%   |
| Kiano               | 1         | 0.68%   |
| IFSA                | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| Getac               | 1         | 0.68%   |
| Fujitsu Siemens     | 1         | 0.68%   |
| Chuwi               | 1         | 0.68%   |
| AXIOO               | 1         | 0.68%   |
| Alienware           | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 2.7%    |
| Apple MacBookPro8,1                        | 3         | 2.03%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.35%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.35%   |
| Lenovo G50-30 80G0                         | 2         | 1.35%   |
| HP Pavilion g6                             | 2         | 1.35%   |
| HP Pavilion 15                             | 2         | 1.35%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.35%   |
| Toshiba Satellite Pro S500                 | 1         | 0.68%   |
| Toshiba Satellite P70-A                    | 1         | 0.68%   |
| Toshiba Satellite L40                      | 1         | 0.68%   |
| Toshiba Satellite C660                     | 1         | 0.68%   |
| Thomson N14C4WH64                          | 1         | 0.68%   |
| Sony VPCEB15FM                             | 1         | 0.68%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.68%   |
| Sony SVE14A2V1EW                           | 1         | 0.68%   |
| SGIN laptop                                | 1         | 0.68%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.68%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.68%   |
| Prestigio PSB141C01BFH                     | 1         | 0.68%   |
| Positivo Q232A                             | 1         | 0.68%   |
| Positivo i500pro                           | 1         | 0.68%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.68%   |
| MSI S12T 3M/S12 3M                         | 1         | 0.68%   |
| Lenovo Z70-80 80FG                         | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMS0RR00            | 1         | 0.68%   |
| Lenovo ThinkPad X230 Tablet 3437CTO        | 1         | 0.68%   |
| Lenovo ThinkPad X220 4291H82               | 1         | 0.68%   |
| Lenovo ThinkPad X201 3626AL3               | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 0.68%   |
| Lenovo ThinkPad T530 2394BF7               | 1         | 0.68%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.68%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 0.68%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 0.68%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S00D00     | 1         | 0.68%   |
| Lenovo ThinkPad L520 5015AH2               | 1         | 0.68%   |
| Lenovo ThinkPad E550 20DF00CUFR            | 1         | 0.68%   |
| Lenovo IdeaPad S340-15IWL 81N8             | 1         | 0.68%   |
| Lenovo IdeaPad S145-15IGM 81MX             | 1         | 0.68%   |
| Lenovo IdeaPad L340-15IRH Gaming 81TR      | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 13        | 8.78%   |
| Lenovo ThinkPad        | 12        | 8.11%   |
| Acer Aspire            | 10        | 6.76%   |
| Dell Latitude          | 8         | 5.41%   |
| HP Pavilion            | 7         | 4.73%   |
| Toshiba Satellite      | 4         | 2.7%    |
| Fujitsu LIFEBOOK       | 4         | 2.7%    |
| Unknown                | 4         | 2.7%    |
| HP ProBook             | 3         | 2.03%   |
| HP Laptop              | 3         | 2.03%   |
| Dell XPS               | 3         | 2.03%   |
| Apple MacBookPro8      | 3         | 2.03%   |
| Mediacom WinPad        | 2         | 1.35%   |
| Lenovo G50-30          | 2         | 1.35%   |
| Dell Precision         | 2         | 1.35%   |
| Thomson N14C4WH64      | 1         | 0.68%   |
| Sony VPCEB15FM         | 1         | 0.68%   |
| Sony VGN-SZ71WN        | 1         | 0.68%   |
| Sony SVE14A2V1EW       | 1         | 0.68%   |
| SGIN laptop            | 1         | 0.68%   |
| Samsung 300V3A         | 1         | 0.68%   |
| Pretech EVE            | 1         | 0.68%   |
| Prestigio PSB141C01BFH | 1         | 0.68%   |
| Positivo Q232A         | 1         | 0.68%   |
| Positivo i500pro       | 1         | 0.68%   |
| Packard Bell EasyNote  | 1         | 0.68%   |
| MSI S12T               | 1         | 0.68%   |
| Lenovo Z70-80          | 1         | 0.68%   |
| Lenovo G505s           | 1         | 0.68%   |
| Lenovo G500            | 1         | 0.68%   |
| Lenovo G50-70          | 1         | 0.68%   |
| Lenovo G50-45          | 1         | 0.68%   |
| Lenovo B590            | 1         | 0.68%   |
| Kiano SlimNote         | 1         | 0.68%   |
| Intel powered          | 1         | 0.68%   |
| Intel Infoway          | 1         | 0.68%   |
| IFSA Positivo          | 1         | 0.68%   |
| HUAWEI KLVD-WXX9       | 1         | 0.68%   |
| HP ZBook               | 1         | 0.68%   |
| HP Stream              | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 18        | 12.16%  |
| 2011 | 18        | 12.16%  |
| 2012 | 13        | 8.78%   |
| 2021 | 12        | 8.11%   |
| 2015 | 11        | 7.43%   |
| 2019 | 9         | 6.08%   |
| 2016 | 9         | 6.08%   |
| 2014 | 9         | 6.08%   |
| 2020 | 8         | 5.41%   |
| 2010 | 8         | 5.41%   |
| 2008 | 8         | 5.41%   |
| 2009 | 6         | 4.05%   |
| 2022 | 5         | 3.38%   |
| 2017 | 5         | 3.38%   |
| 2018 | 4         | 2.7%    |
| 2007 | 4         | 2.7%    |
| 2023 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 148       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 142       | 94.67%  |
| Enabled  | 8         | 5.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 141       | 95.27%  |
| Yes  | 7         | 4.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 58        | 38.93%  |
| 4.01-8.0   | 38        | 25.5%   |
| 1.01-2.0   | 19        | 12.75%  |
| 8.01-16.0  | 13        | 8.72%   |
| 16.01-24.0 | 11        | 7.38%   |
| 2.01-3.0   | 7         | 4.7%    |
| 32.01-64.0 | 2         | 1.34%   |
| 24.01-32.0 | 1         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 76        | 48.72%  |
| 0.51-1.0 | 36        | 23.08%  |
| 2.01-3.0 | 31        | 19.87%  |
| 3.01-4.0 | 7         | 4.49%   |
| 4.01-8.0 | 6         | 3.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 78.15%  |
| 2      | 27        | 17.88%  |
| 3      | 4         | 2.65%   |
| 0      | 2         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 57.43%  |
| Yes       | 63        | 42.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 77.03%  |
| No        | 34        | 22.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 92.57%  |
| No        | 11        | 7.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 68.46%  |
| No        | 47        | 31.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 25        | 16.89%  |
| France       | 14        | 9.46%   |
| Germany      | 13        | 8.78%   |
| Italy        | 12        | 8.11%   |
| Russia       | 8         | 5.41%   |
| Poland       | 8         | 5.41%   |
| Brazil       | 8         | 5.41%   |
| Belgium      | 5         | 3.38%   |
| UK           | 4         | 2.7%    |
| Canada       | 4         | 2.7%    |
| Ukraine      | 3         | 2.03%   |
| Costa Rica   | 3         | 2.03%   |
| Vietnam      | 2         | 1.35%   |
| UAE          | 2         | 1.35%   |
| Turkey       | 2         | 1.35%   |
| Spain        | 2         | 1.35%   |
| Portugal     | 2         | 1.35%   |
| Netherlands  | 2         | 1.35%   |
| Mexico       | 2         | 1.35%   |
| Indonesia    | 2         | 1.35%   |
| Hungary      | 2         | 1.35%   |
| Colombia     | 2         | 1.35%   |
| Australia    | 2         | 1.35%   |
| Argentina    | 2         | 1.35%   |
| Thailand     | 1         | 0.68%   |
| Taiwan       | 1         | 0.68%   |
| Switzerland  | 1         | 0.68%   |
| Sweden       | 1         | 0.68%   |
| South Africa | 1         | 0.68%   |
| Philippines  | 1         | 0.68%   |
| Latvia       | 1         | 0.68%   |
| Kenya        | 1         | 0.68%   |
| Japan        | 1         | 0.68%   |
| Greece       | 1         | 0.68%   |
| Finland      | 1         | 0.68%   |
| Ecuador      | 1         | 0.68%   |
| Croatia      | 1         | 0.68%   |
| Chile        | 1         | 0.68%   |
| Belarus      | 1         | 0.68%   |
| Bangladesh   | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Paris                  | 4         | 2.6%    |
| Ghent                  | 3         | 1.95%   |
| Sarospatak             | 2         | 1.3%    |
| Porto Alegre           | 2         | 1.3%    |
| Milan                  | 2         | 1.3%    |
| Lansing                | 2         | 1.3%    |
| Kyiv                   | 2         | 1.3%    |
| Heredia                | 2         | 1.3%    |
| Eberbach               | 2         | 1.3%    |
| Dubai                  | 2         | 1.3%    |
| Bogotá                | 2         | 1.3%    |
| Zizur Mayor            | 1         | 0.65%   |
| Zawiercie              | 1         | 0.65%   |
| Zagreb                 | 1         | 0.65%   |
| Yoshkar-Ola            | 1         | 0.65%   |
| Yorkville              | 1         | 0.65%   |
| Yerevan                | 1         | 0.65%   |
| Yekaterinburg          | 1         | 0.65%   |
| Wolfhagen              | 1         | 0.65%   |
| West Stockbridge       | 1         | 0.65%   |
| Warsaw                 | 1         | 0.65%   |
| Warendorf              | 1         | 0.65%   |
| Volzhskiy              | 1         | 0.65%   |
| Verona                 | 1         | 0.65%   |
| Valenciennes           | 1         | 0.65%   |
| Uberlândia            | 1         | 0.65%   |
| Tychy                  | 1         | 0.65%   |
| Thornton Heath         | 1         | 0.65%   |
| Thessaloniki           | 1         | 0.65%   |
| Taipei                 | 1         | 0.65%   |
| Sylhet                 | 1         | 0.65%   |
| Surabaya               | 1         | 0.65%   |
| Stuttgart              | 1         | 0.65%   |
| Strzyzow               | 1         | 0.65%   |
| Stockholm              | 1         | 0.65%   |
| Southampton            | 1         | 0.65%   |
| South Burlington       | 1         | 0.65%   |
| Sao Paulo              | 1         | 0.65%   |
| Santiago de Compostela | 1         | 0.65%   |
| Santiago               | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 26        | 37     | 15.76%  |
| WDC                       | 20        | 24     | 12.12%  |
| Seagate                   | 20        | 23     | 12.12%  |
| Toshiba                   | 14        | 15     | 8.48%   |
| Samsung Electronics       | 12        | 17     | 7.27%   |
| Hitachi                   | 7         | 9      | 4.24%   |
| SanDisk                   | 6         | 6      | 3.64%   |
| Kingston                  | 6         | 6      | 3.64%   |
| HGST                      | 5         | 5      | 3.03%   |
| Crucial                   | 4         | 4      | 2.42%   |
| A-DATA Technology         | 4         | 4      | 2.42%   |
| SK hynix                  | 3         | 3      | 1.82%   |
| Micron Technology         | 3         | 4      | 1.82%   |
| Intel                     | 3         | 3      | 1.82%   |
| UMIS                      | 2         | 2      | 1.21%   |
| Transcend                 | 2         | 3      | 1.21%   |
| SPCC                      | 2         | 3      | 1.21%   |
| GOODRAM                   | 2         | 2      | 1.21%   |
| Fujitsu                   | 2         | 2      | 1.21%   |
| Apacer                    | 2         | 2      | 1.21%   |
| W800S                     | 1         | 1      | 0.61%   |
| Teclast                   | 1         | 1      | 0.61%   |
| Silicon Motion            | 1         | 1      | 0.61%   |
| Rogueware                 | 1         | 1      | 0.61%   |
| PNY                       | 1         | 1      | 0.61%   |
| Plextor                   | 1         | 1      | 0.61%   |
| Phison                    | 1         | 1      | 0.61%   |
| NGFF                      | 1         | 1      | 0.61%   |
| Micron/Crucial Technology | 1         | 1      | 0.61%   |
| LITEON                    | 1         | 1      | 0.61%   |
| Lexar                     | 1         | 1      | 0.61%   |
| Leqixiang                 | 1         | 1      | 0.61%   |
| Lenovo                    | 1         | 1      | 0.61%   |
| LDLC                      | 1         | 2      | 0.61%   |
| KINGPOWER                 | 1         | 1      | 0.61%   |
| Intenso                   | 1         | 1      | 0.61%   |
| HUSKY                     | 1         | 1      | 0.61%   |
| China                     | 1         | 1      | 0.61%   |
| Apple                     | 1         | 2      | 0.61%   |
| Unknown                   | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 5         | 2.86%   |
| Seagate ST9500325AS 500GB            | 5         | 2.86%   |
| Unknown MMC Card  32GB               | 4         | 2.29%   |
| SanDisk DF4032  32GB                 | 3         | 1.71%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 1.14%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 1.14%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 1.14%   |
| Unknown SD/MMC/MS PRO 249GB          | 2         | 1.14%   |
| Unknown SC64G  64GB                  | 2         | 1.14%   |
| Unknown SC256  256GB                 | 2         | 1.14%   |
| Unknown NCard  32GB                  | 2         | 1.14%   |
| Unknown MMC64G  64GB                 | 2         | 1.14%   |
| Unknown DA4064  64GB                 | 2         | 1.14%   |
| Unknown DA4032  32GB                 | 2         | 1.14%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.14%   |
| Toshiba MQ01ABD075 752GB             | 2         | 1.14%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.14%   |
| SPCC Solid State Disk 120GB          | 2         | 1.14%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.14%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.14%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.14%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.14%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.57%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.57%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.57%   |
| WDC WDS250G2B0A 250GB SSD            | 1         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.57%   |
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 0.57%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.57%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.57%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.57%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.57%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.57%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.57%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.57%   |
| WDC PC SN730 SDBQNTY-256G-1006 256GB | 1         | 0.57%   |
| W800S 256GB SSD                      | 1         | 0.57%   |
| Unknown SF64G  64GB                  | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 23     | 31.25%  |
| WDC                 | 15        | 16     | 23.44%  |
| Toshiba             | 12        | 13     | 18.75%  |
| Hitachi             | 7         | 9      | 10.94%  |
| HGST                | 5         | 5      | 7.81%   |
| Unknown             | 2         | 2      | 3.13%   |
| Fujitsu             | 2         | 2      | 3.13%   |
| Samsung Electronics | 1         | 5      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 14.81%  |
| Kingston            | 5         | 5      | 9.26%   |
| WDC                 | 4         | 5      | 7.41%   |
| A-DATA Technology   | 4         | 4      | 7.41%   |
| SanDisk             | 3         | 3      | 5.56%   |
| Intel               | 3         | 3      | 5.56%   |
| Crucial             | 3         | 3      | 5.56%   |
| Transcend           | 2         | 3      | 3.7%    |
| Toshiba             | 2         | 2      | 3.7%    |
| SPCC                | 2         | 3      | 3.7%    |
| Micron Technology   | 2         | 2      | 3.7%    |
| GOODRAM             | 2         | 2      | 3.7%    |
| Apacer              | 2         | 2      | 3.7%    |
| W800S               | 1         | 1      | 1.85%   |
| Teclast             | 1         | 1      | 1.85%   |
| Rogueware           | 1         | 1      | 1.85%   |
| PNY                 | 1         | 1      | 1.85%   |
| Plextor             | 1         | 1      | 1.85%   |
| NGFF                | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| Lexar               | 1         | 1      | 1.85%   |
| Leqixiang           | 1         | 1      | 1.85%   |
| Lenovo              | 1         | 1      | 1.85%   |
| KINGPOWER           | 1         | 1      | 1.85%   |
| HUSKY               | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 63        | 75     | 38.18%  |
| SSD     | 52        | 58     | 31.52%  |
| MMC     | 30        | 40     | 18.18%  |
| NVMe    | 17        | 19     | 10.3%   |
| Unknown | 3         | 4      | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 109       | 132    | 67.7%   |
| MMC  | 30        | 40     | 18.63%  |
| NVMe | 17        | 19     | 10.56%  |
| SAS  | 5         | 5      | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 102    | 76.99%  |
| 0.51-1.0   | 24        | 29     | 21.24%  |
| 1.01-2.0   | 1         | 1      | 0.88%   |
| 4.01-10.0  | 1         | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 33.11%  |
| 251-500        | 40        | 26.49%  |
| 1-20           | 16        | 10.6%   |
| 51-100         | 16        | 10.6%   |
| 501-1000       | 14        | 9.27%   |
| 21-50          | 11        | 7.28%   |
| More than 3000 | 1         | 0.66%   |
| 2001-3000      | 1         | 0.66%   |
| 1001-2000      | 1         | 0.66%   |
| Unknown        | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 53.59%  |
| 21-50          | 33        | 21.57%  |
| 51-100         | 16        | 10.46%  |
| 101-250        | 13        | 8.5%    |
| 251-500        | 4         | 2.61%   |
| 501-1000       | 2         | 1.31%   |
| More than 3000 | 1         | 0.65%   |
| 1001-2000      | 1         | 0.65%   |
| Unknown        | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 2         | 2      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 7.69%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 3.85%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 3.85%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 3.85%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 3.85%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 3.85%   |
| Seagate ST320LT012-9WS14C 320GB    | 1         | 1      | 3.85%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 3.85%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 3.85%   |
| Samsung Electronics HM121HI 120GB  | 1         | 5      | 3.85%   |
| Plextor PX-128M6M 128GB SSD        | 1         | 1      | 3.85%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 3.85%   |
| Intel SSDSC2KW512G8 512GB          | 1         | 1      | 3.85%   |
| Intel SSDSA2M080G2LE 80GB          | 1         | 1      | 3.85%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 3.85%   |
| HGST HTS725032A7E630 320GB         | 1         | 1      | 3.85%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 3.85%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 38.46%  |
| WDC                 | 3         | 3      | 11.54%  |
| Toshiba             | 3         | 3      | 11.54%  |
| Intel               | 2         | 2      | 7.69%   |
| Hitachi             | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 5      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| NGFF                | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |
| Apacer              | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 47.62%  |
| WDC                 | 3         | 3      | 14.29%  |
| Toshiba             | 3         | 3      | 14.29%  |
| Hitachi             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 5      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |
| Fujitsu             | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 25     | 80.77%  |
| SSD  | 5         | 5      | 19.23%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 88        | 116    | 56.05%  |
| Works    | 43        | 50     | 27.39%  |
| Malfunc  | 26        | 30     | 16.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 106       | 74.13%  |
| AMD                              | 17        | 11.89%  |
| Samsung Electronics              | 3         | 2.1%    |
| Union Memory (Shenzhen)          | 2         | 1.4%    |
| SK hynix                         | 2         | 1.4%    |
| SanDisk                          | 2         | 1.4%    |
| Nvidia                           | 2         | 1.4%    |
| Micron/Crucial Technology        | 2         | 1.4%    |
| Micron Technology                | 2         | 1.4%    |
| Silicon Motion                   | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] | 1         | 0.7%    |
| Silicon Image                    | 1         | 0.7%    |
| Phison Electronics               | 1         | 0.7%    |
| Kingston Technology Company      | 1         | 0.7%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 10.26%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 5.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 5.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 5.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 4.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 4.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 3.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 3.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.92%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 1.28%   |
| Micron NVMe Storage Controller                                                   | 2         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.28%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.28%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.28%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.28%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.64%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.64%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.64%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.64%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.64%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.64%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.64%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 114       | 75.5%   |
| NVMe | 16        | 10.6%   |
| IDE  | 15        | 9.93%   |
| RAID | 6         | 3.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 130       | 87.84%  |
| AMD    | 18        | 12.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 4.05%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 3.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 2.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.03%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 2.03%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 3         | 2.03%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.35%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.35%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 1.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.35%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.35%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.35%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.35%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1.35%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.35%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.35%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 2         | 1.35%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.35%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.35%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 1.35%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 1.35%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 2         | 1.35%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.35%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.68%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.68%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.68%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.68%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.68%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.68%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.68%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 0.68%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 31        | 20.95%  |
| Intel Core i5           | 29        | 19.59%  |
| Intel Core i7           | 17        | 11.49%  |
| Intel Core i3           | 15        | 10.14%  |
| Intel Core 2 Duo        | 14        | 9.46%   |
| Intel Atom              | 10        | 6.76%   |
| Intel Pentium           | 7         | 4.73%   |
| AMD A6                  | 4         | 2.7%    |
| AMD E1                  | 3         | 2.03%   |
| Other                   | 2         | 1.35%   |
| Intel Pentium Dual      | 2         | 1.35%   |
| Intel Core 2            | 2         | 1.35%   |
| AMD E2                  | 2         | 1.35%   |
| AMD E                   | 2         | 1.35%   |
| AMD A8                  | 2         | 1.35%   |
| Intel Celeron Dual-Core | 1         | 0.68%   |
| AMD Ryzen 7 PRO         | 1         | 0.68%   |
| AMD Ryzen 7             | 1         | 0.68%   |
| AMD Ryzen 5             | 1         | 0.68%   |
| AMD C-60                | 1         | 0.68%   |
| AMD Athlon              | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 70.27%  |
| 4      | 38        | 25.68%  |
| 1      | 3         | 2.03%   |
| 8      | 2         | 1.35%   |
| 6      | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 77        | 52.03%  |
| 2      | 71        | 47.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 148       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 38.26%  |
| 0x306a9    | 9         | 6.04%   |
| 0x206a7    | 9         | 6.04%   |
| 0x406c4    | 5         | 3.36%   |
| 0x406c3    | 5         | 3.36%   |
| 0x706a8    | 4         | 2.68%   |
| 0x6fd      | 4         | 2.68%   |
| 0x40651    | 4         | 2.68%   |
| 0x1067a    | 4         | 2.68%   |
| 0x806ec    | 3         | 2.01%   |
| 0x806ea    | 3         | 2.01%   |
| 0x30678    | 3         | 2.01%   |
| 0x20655    | 3         | 2.01%   |
| 0x06006705 | 3         | 2.01%   |
| 0x05000119 | 3         | 2.01%   |
| 0x906c0    | 2         | 1.34%   |
| 0x806c1    | 2         | 1.34%   |
| 0x706e5    | 2         | 1.34%   |
| 0x706a1    | 2         | 1.34%   |
| 0x306c3    | 2         | 1.34%   |
| 0x0a50000c | 2         | 1.34%   |
| 0x0700010f | 2         | 1.34%   |
| 0x906ed    | 1         | 0.67%   |
| 0x806eb    | 1         | 0.67%   |
| 0x806e9    | 1         | 0.67%   |
| 0x6fa      | 1         | 0.67%   |
| 0x6f6      | 1         | 0.67%   |
| 0x506e3    | 1         | 0.67%   |
| 0x506c9    | 1         | 0.67%   |
| 0x406e3    | 1         | 0.67%   |
| 0x20652    | 1         | 0.67%   |
| 0x106ca    | 1         | 0.67%   |
| 0x10676    | 1         | 0.67%   |
| 0x08a00006 | 1         | 0.67%   |
| 0x08608102 | 1         | 0.67%   |
| 0x06006704 | 1         | 0.67%   |
| 0x06001119 | 1         | 0.67%   |
| 0x06001116 | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 25        | 16.89%  |
| SandyBridge   | 16        | 10.81%  |
| IvyBridge     | 13        | 8.78%   |
| Haswell       | 12        | 8.11%   |
| KabyLake      | 11        | 7.43%   |
| Penryn        | 10        | 6.76%   |
| Goldmont plus | 9         | 6.08%   |
| Core          | 9         | 6.08%   |
| Westmere      | 8         | 5.41%   |
| Excavator     | 4         | 2.7%    |
| Skylake       | 3         | 2.03%   |
| Piledriver    | 3         | 2.03%   |
| Jaguar        | 3         | 2.03%   |
| Goldmont      | 3         | 2.03%   |
| Broadwell     | 3         | 2.03%   |
| Bobcat        | 3         | 2.03%   |
| Zen 3         | 2         | 1.35%   |
| Tremont       | 2         | 1.35%   |
| TigerLake     | 2         | 1.35%   |
| IceLake       | 2         | 1.35%   |
| Bonnell       | 2         | 1.35%   |
| Unknown       | 2         | 1.35%   |
| Puma          | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 119       | 73.01%  |
| AMD    | 26        | 15.95%  |
| Nvidia | 18        | 11.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 9.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 9.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 7.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 5.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 5.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 4.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 4%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 4%      |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 4%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.29%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.71%   |
| Intel HD Graphics 500                                                                    | 3         | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.71%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.71%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 1.14%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 1.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.14%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.14%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.14%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.14%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.14%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.14%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 1.14%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.14%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.14%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 1.14%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.57%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.57%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.57%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.57%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.57%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.57%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.57%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 102       | 68.92%  |
| 1 x AMD        | 16        | 10.81%  |
| 1 x Nvidia     | 10        | 6.76%   |
| Intel + Nvidia | 8         | 5.41%   |
| Intel + AMD    | 6         | 4.05%   |
| 2 x AMD        | 4         | 2.7%    |
| Other          | 2         | 1.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 141       | 95.27%  |
| Proprietary | 5         | 3.38%   |
| Unknown     | 2         | 1.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 83.22%  |
| 0.01-0.5   | 13        | 8.72%   |
| 1.01-2.0   | 7         | 4.7%    |
| 0.51-1.0   | 2         | 1.34%   |
| 5.01-6.0   | 1         | 0.67%   |
| 3.01-4.0   | 1         | 0.67%   |
| 2.01-3.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 20.92%  |
| LG Display              | 25        | 16.34%  |
| BOE                     | 22        | 14.38%  |
| Chimei Innolux          | 19        | 12.42%  |
| Samsung Electronics     | 13        | 8.5%    |
| Apple                   | 7         | 4.58%   |
| CPT                     | 5         | 3.27%   |
| Lenovo                  | 4         | 2.61%   |
| Chi Mei Optoelectronics | 4         | 2.61%   |
| Toshiba                 | 3         | 1.96%   |
| Sharp                   | 3         | 1.96%   |
| Goldstar                | 3         | 1.96%   |
| LG Philips              | 2         | 1.31%   |
| Hewlett-Packard         | 2         | 1.31%   |
| ViewSonic               | 1         | 0.65%   |
| LLL                     | 1         | 0.65%   |
| JVC                     | 1         | 0.65%   |
| JDI                     | 1         | 0.65%   |
| CS_                     | 1         | 0.65%   |
| CMN                     | 1         | 0.65%   |
| BenQ                    | 1         | 0.65%   |
| AOC                     | 1         | 0.65%   |
| Acer                    | 1         | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 5         | 3.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 3         | 1.96%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 1.31%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 2         | 1.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.31%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 1.31%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                  | 2         | 1.31%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.31%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.31%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 2         | 1.31%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.65%   |
| Toshiba TV TSB0108 1360x768 576x324mm 26.0-inch                       | 1         | 0.65%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch              | 1         | 0.65%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.65%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.65%   |
| Sharp LCD Monitor SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.65%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 1         | 0.65%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3842 1366x768 309x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3254 1366x768 293x165mm 13.2-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.65%   |
| LLL LRK32G30RQ LLL4200 1920x1080 983x576mm 44.9-inch                  | 1         | 0.65%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 0.65%   |
| LG Philips LCD Monitor LPL1101 1280x800 304x190mm 14.1-inch           | 1         | 0.65%   |
| LG Display LCD Monitor LGD0680 1920x1080 344x194mm 15.5-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.65%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 79        | 52.32%  |
| 1920x1080 (FHD)    | 29        | 19.21%  |
| 1280x800 (WXGA)    | 18        | 11.92%  |
| 1600x900 (HD+)     | 9         | 5.96%   |
| 2560x1440 (QHD)    | 3         | 1.99%   |
| 3200x1800 (QHD+)   | 2         | 1.32%   |
| 2160x1440          | 2         | 1.32%   |
| 1440x900 (WXGA+)   | 2         | 1.32%   |
| 3840x2160 (4K)     | 1         | 0.66%   |
| 3000x2000          | 1         | 0.66%   |
| 2560x1080          | 1         | 0.66%   |
| 1920x540           | 1         | 0.66%   |
| 1680x1050 (WSXGA+) | 1         | 0.66%   |
| 1528x1222          | 1         | 0.66%   |
| 1360x768           | 1         | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 32.68%  |
| 14      | 25        | 16.34%  |
| 13      | 23        | 15.03%  |
| 11      | 16        | 10.46%  |
| 17      | 9         | 5.88%   |
| 12      | 9         | 5.88%   |
| 23      | 3         | 1.96%   |
| 21      | 3         | 1.96%   |
| 24      | 2         | 1.31%   |
| 19      | 2         | 1.31%   |
| 10      | 2         | 1.31%   |
| Unknown | 2         | 1.31%   |
| 72      | 1         | 0.65%   |
| 44      | 1         | 0.65%   |
| 28      | 1         | 0.65%   |
| 27      | 1         | 0.65%   |
| 18      | 1         | 0.65%   |
| 16      | 1         | 0.65%   |
| 9       | 1         | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 54.9%   |
| 201-300     | 41        | 26.8%   |
| 351-400     | 10        | 6.54%   |
| 401-500     | 6         | 3.92%   |
| 501-600     | 5         | 3.27%   |
| 601-700     | 2         | 1.31%   |
| Unknown     | 2         | 1.31%   |
| 1501-2000   | 1         | 0.65%   |
| 101-200     | 1         | 0.65%   |
| 901-1000    | 1         | 0.65%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 113       | 79.58%  |
| 16/10   | 22        | 15.49%  |
| 3/2     | 4         | 2.82%   |
| 4/3     | 1         | 0.7%    |
| 21/9    | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 32.68%  |
| 81-90          | 43        | 28.1%   |
| 51-60          | 16        | 10.46%  |
| 61-70          | 9         | 5.88%   |
| 121-130        | 8         | 5.23%   |
| 201-250        | 7         | 4.58%   |
| 71-80          | 5         | 3.27%   |
| 41-50          | 3         | 1.96%   |
| 251-300        | 2         | 1.31%   |
| 151-200        | 2         | 1.31%   |
| 131-140        | 2         | 1.31%   |
| Unknown        | 2         | 1.31%   |
| More than 1000 | 1         | 0.65%   |
| 301-350        | 1         | 0.65%   |
| 141-150        | 1         | 0.65%   |
| 501-1000       | 1         | 0.65%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 72        | 47.68%  |
| 121-160       | 46        | 30.46%  |
| 51-100        | 18        | 11.92%  |
| 161-240       | 9         | 5.96%   |
| More than 240 | 2         | 1.32%   |
| 1-50          | 2         | 1.32%   |
| Unknown       | 2         | 1.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 133       | 89.86%  |
| 2     | 12        | 8.11%   |
| 0     | 2         | 1.35%   |
| 3     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 72        | 32.43%  |
| Intel                             | 59        | 26.58%  |
| Qualcomm Atheros                  | 36        | 16.22%  |
| Broadcom                          | 15        | 6.76%   |
| Marvell Technology Group          | 6         | 2.7%    |
| Ralink                            | 4         | 1.8%    |
| TP-Link                           | 3         | 1.35%   |
| Samsung Electronics               | 3         | 1.35%   |
| Broadcom Limited                  | 3         | 1.35%   |
| Ralink Technology                 | 2         | 0.9%    |
| Qualcomm Atheros Communications   | 2         | 0.9%    |
| Qualcomm                          | 2         | 0.9%    |
| MediaTek                          | 2         | 0.9%    |
| ASIX Electronics                  | 2         | 0.9%    |
| Xiaomi                            | 1         | 0.45%   |
| Sierra Wireless                   | 1         | 0.45%   |
| Nvidia                            | 1         | 0.45%   |
| NetGear                           | 1         | 0.45%   |
| Motorola PCS                      | 1         | 0.45%   |
| Microsoft                         | 1         | 0.45%   |
| JMicron Technology                | 1         | 0.45%   |
| ICS Advent                        | 1         | 0.45%   |
| Ericsson Business Mobile Networks | 1         | 0.45%   |
| Dell                              | 1         | 0.45%   |
| ASUSTek Computer                  | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 11.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 5.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 2.91%   |
| Intel Wireless 7260                                               | 8         | 2.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.91%   |
| Intel Wireless 7265                                               | 7         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.82%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 1.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.09%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 1.09%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.09%   |
| Intel Wireless 3160                                               | 3         | 1.09%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.09%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.09%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 37.58%  |
| Qualcomm Atheros                | 34        | 22.82%  |
| Realtek Semiconductor           | 32        | 21.48%  |
| Broadcom                        | 9         | 6.04%   |
| Ralink                          | 4         | 2.68%   |
| TP-Link                         | 2         | 1.34%   |
| Ralink Technology               | 2         | 1.34%   |
| Qualcomm Atheros Communications | 2         | 1.34%   |
| MediaTek                        | 2         | 1.34%   |
| Sierra Wireless                 | 1         | 0.67%   |
| NetGear                         | 1         | 0.67%   |
| Microsoft                       | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| Broadcom Limited                | 1         | 0.67%   |
| ASUSTek Computer                | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 5.33%   |
| Intel Wireless 7260                                            | 8         | 5.33%   |
| Intel Wireless 7265                                            | 7         | 4.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 3.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.33%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 2.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 2%      |
| Intel Wireless 3160                                            | 3         | 2%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 2%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 2%      |
| Intel Centrino Wireless-N 2230                                 | 3         | 2%      |
| Intel Centrino Advanced-N 6200                                 | 3         | 2%      |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 2%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.33%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.33%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.33%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.33%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.33%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.67%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 58        | 47.54%  |
| Intel                    | 24        | 19.67%  |
| Qualcomm Atheros         | 10        | 8.2%    |
| Broadcom                 | 10        | 8.2%    |
| Marvell Technology Group | 6         | 4.92%   |
| Samsung Electronics      | 2         | 1.64%   |
| Qualcomm                 | 2         | 1.64%   |
| Broadcom Limited         | 2         | 1.64%   |
| ASIX Electronics         | 2         | 1.64%   |
| Xiaomi                   | 1         | 0.82%   |
| TP-Link                  | 1         | 0.82%   |
| Nvidia                   | 1         | 0.82%   |
| Motorola PCS             | 1         | 0.82%   |
| JMicron Technology       | 1         | 0.82%   |
| ICS Advent               | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 26.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 16        | 13.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 6.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.07%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 3.25%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 3.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 3.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 2.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 2.44%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 2.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 2.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.63%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.81%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.81%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.81%   |
| Qualcomm SM7250-PICASSO _SN:6897A937                                           | 1         | 0.81%   |
| Qualcomm Nokia XR20                                                            | 1         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.81%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.81%   |
| Motorola PCS motorola razr 2022                                                | 1         | 0.81%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.81%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.81%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.81%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.81%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.81%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.81%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.81%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.81%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.81%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express                      | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 54.15%  |
| Ethernet | 114       | 45.06%  |
| Modem    | 2         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 71.43%  |
| Ethernet | 42        | 28.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 98        | 66.22%  |
| 1     | 34        | 22.97%  |
| 0     | 15        | 10.14%  |
| 3     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 76.67%  |
| Yes  | 35        | 23.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 35.29%  |
| Realtek Semiconductor           | 17        | 16.67%  |
| Qualcomm Atheros Communications | 11        | 10.78%  |
| Broadcom                        | 7         | 6.86%   |
| Apple                           | 5         | 4.9%    |
| Lite-On Technology              | 4         | 3.92%   |
| Foxconn / Hon Hai               | 4         | 3.92%   |
| Ralink                          | 3         | 2.94%   |
| IMC Networks                    | 3         | 2.94%   |
| Dell                            | 3         | 2.94%   |
| Toshiba                         | 2         | 1.96%   |
| Hewlett-Packard                 | 2         | 1.96%   |
| Cambridge Silicon Radio         | 2         | 1.96%   |
| Syntek                          | 1         | 0.98%   |
| ASUSTek Computer                | 1         | 0.98%   |
| Alps Electric                   | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 21.36%  |
| Realtek Bluetooth Radio                                                             | 10        | 9.71%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 5.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.85%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 3.88%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.88%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.88%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.91%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.94%   |
| Intel AX201 Bluetooth                                                               | 2         | 1.94%   |
| Intel AX200 Bluetooth                                                               | 2         | 1.94%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.94%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.97%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.97%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.97%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.97%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.97%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.97%   |
| Lite-On Wireless_Device                                                             | 1         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.97%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.97%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.97%   |
| IMC Networks Bluetooth                                                              | 1         | 0.97%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.97%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.97%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.97%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.97%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.97%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.97%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.97%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 118       | 78.67%  |
| AMD                  | 20        | 13.33%  |
| Nvidia               | 8         | 5.33%   |
| MosArt Semiconductor | 1         | 0.67%   |
| JMTek                | 1         | 0.67%   |
| EGO SYStems          | 1         | 0.67%   |
| C-Media Electronics  | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 10.5%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 6.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 4.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 4.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 4.42%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 4.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 4.42%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 3.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 2.21%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 2.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.66%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.66%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.1%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.1%    |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.1%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.1%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.55%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.55%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.55%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 25.23%  |
| SK hynix            | 24        | 22.43%  |
| Micron Technology   | 13        | 12.15%  |
| Unknown             | 11        | 10.28%  |
| Nanya Technology    | 4         | 3.74%   |
| Elpida              | 4         | 3.74%   |
| Unknown (ABCD)      | 3         | 2.8%    |
| Kingston            | 3         | 2.8%    |
| Smart               | 2         | 1.87%   |
| Corsair             | 2         | 1.87%   |
| A-DATA Technology   | 2         | 1.87%   |
| Unknown             | 2         | 1.87%   |
| Transcend           | 1         | 0.93%   |
| Toshiba             | 1         | 0.93%   |
| Ramaxel Technology  | 1         | 0.93%   |
| Novatech            | 1         | 0.93%   |
| Kllisre             | 1         | 0.93%   |
| Kingmax             | 1         | 0.93%   |
| HMD                 | 1         | 0.93%   |
| G.Skill             | 1         | 0.93%   |
| Apacer              | 1         | 0.93%   |
| AMD                 | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 3.45%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 2.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.72%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.72%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.72%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.72%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.72%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1.72%   |
| Unknown                                                          | 2         | 1.72%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.86%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.86%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.86%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.86%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.86%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 0.86%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 0.86%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.86%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.86%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 0.86%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.86%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.86%   |
| SK hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.86%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.86%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s           | 1         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 50        | 53.19%  |
| DDR4   | 24        | 25.53%  |
| LPDDR4 | 7         | 7.45%   |
| DDR2   | 7         | 7.45%   |
| SDRAM  | 3         | 3.19%   |
| LPDDR3 | 2         | 2.13%   |
| LPDDR5 | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 88.3%   |
| Row Of Chips | 8         | 8.51%   |
| Unknown      | 3         | 3.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 35        | 33.02%  |
| 2048  | 32        | 30.19%  |
| 8192  | 27        | 25.47%  |
| 1024  | 7         | 6.6%    |
| 16384 | 3         | 2.83%   |
| 32768 | 1         | 0.94%   |
| 512   | 1         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 33        | 32.67%  |
| 3200    | 9         | 8.91%   |
| 2400    | 7         | 6.93%   |
| 1334    | 7         | 6.93%   |
| 1333    | 7         | 6.93%   |
| 2667    | 6         | 5.94%   |
| 1066    | 5         | 4.95%   |
| 667     | 5         | 4.95%   |
| 3266    | 4         | 3.96%   |
| 1866    | 3         | 2.97%   |
| 1067    | 3         | 2.97%   |
| 975     | 2         | 1.98%   |
| Unknown | 2         | 1.98%   |
| 5500    | 1         | 0.99%   |
| 4267    | 1         | 0.99%   |
| 4199    | 1         | 0.99%   |
| 3733    | 1         | 0.99%   |
| 2133    | 1         | 0.99%   |
| 2048    | 1         | 0.99%   |
| 1867    | 1         | 0.99%   |
| 800     | 1         | 0.99%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 50%     |
| Canon MF3110      | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 28.1%   |
| Realtek Semiconductor                  | 14        | 11.57%  |
| Microdia                               | 12        | 9.92%   |
| Sunplus Innovation Technology          | 8         | 6.61%   |
| Syntek                                 | 5         | 4.13%   |
| IMC Networks                           | 5         | 4.13%   |
| Apple                                  | 5         | 4.13%   |
| Suyin                                  | 4         | 3.31%   |
| Quanta                                 | 4         | 3.31%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.31%   |
| Alcor Micro                            | 4         | 3.31%   |
| Lenovo                                 | 3         | 2.48%   |
| Bison Electronics                      | 3         | 2.48%   |
| Silicon Motion                         | 2         | 1.65%   |
| Lite-On Technology                     | 2         | 1.65%   |
| ALi                                    | 2         | 1.65%   |
| Acer                                   | 2         | 1.65%   |
| Y Media                                | 1         | 0.83%   |
| USB Camera CS                          | 1         | 0.83%   |
| SunplusIT                              | 1         | 0.83%   |
| Ricoh                                  | 1         | 0.83%   |
| Logitech                               | 1         | 0.83%   |
| icSpring                               | 1         | 0.83%   |
| GEMBIRD                                | 1         | 0.83%   |
| Cubeternet                             | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 9         | 7.38%   |
| Chicony HD WebCam                    | 4         | 3.28%   |
| Sunplus HD WebCam                    | 3         | 2.46%   |
| Realtek Integrated_Webcam_HD         | 3         | 2.46%   |
| Microdia Integrated Webcam           | 3         | 2.46%   |
| Chicony HP TrueVision HD Camera      | 3         | 2.46%   |
| Apple FaceTime HD Camera             | 3         | 2.46%   |
| Realtek USB Camera                   | 2         | 1.64%   |
| Realtek Lenovo EasyCamera            | 2         | 1.64%   |
| Realtek Integrated Webcam HD         | 2         | 1.64%   |
| Microdia Lenovo EasyCamera           | 2         | 1.64%   |
| Microdia Integrated_Webcam_HD        | 2         | 1.64%   |
| Microdia HP Webcam-50                | 2         | 1.64%   |
| Lenovo Integrated Webcam             | 2         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam    | 2         | 1.64%   |
| Chicony VGA Webcam                   | 2         | 1.64%   |
| Chicony HP Truevision HD             | 2         | 1.64%   |
| Chicony FJ Camera                    | 2         | 1.64%   |
| Chicony EasyCamera                   | 2         | 1.64%   |
| Chicony 2.0M UVC Webcam / CNF7129    | 2         | 1.64%   |
| ALi WebCam                           | 2         | 1.64%   |
| Alcor Micro USB 2.0 HD Camera        | 2         | 1.64%   |
| Alcor Micro SHUNCCM2MP               | 2         | 1.64%   |
| Y Media USB Camera                   | 1         | 0.82%   |
| USB Camera CS USB Camera CS          | 1         | 0.82%   |
| Syntek USB2.0 Camera                 | 1         | 0.82%   |
| Syntek USB Camera Device             | 1         | 0.82%   |
| Syntek Sonix USB 2.0 Camera          | 1         | 0.82%   |
| Syntek Lenovo EasyCamera             | 1         | 0.82%   |
| Syntek HD WebCam                     | 1         | 0.82%   |
| Suyin VGA Webcam                     | 1         | 0.82%   |
| Suyin Intel Webcam                   | 1         | 0.82%   |
| Suyin HP Webcam-101                  | 1         | 0.82%   |
| Suyin 1.3M HD WebCam                 | 1         | 0.82%   |
| SunplusIT USB camera                 | 1         | 0.82%   |
| Sunplus Laptop Integrated Webcam FHD | 1         | 0.82%   |
| Sunplus Integrated_Webcam_HD         | 1         | 0.82%   |
| Sunplus HD User Facing               | 1         | 0.82%   |
| Sunplus Dell Integrated HD Webcam    | 1         | 0.82%   |
| Sunplus Asus Webcam                  | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 27.78%  |
| Upek                       | 4         | 22.22%  |
| AuthenTec                  | 4         | 22.22%  |
| STMicroelectronics         | 2         | 11.11%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| LighTuning Technology      | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 22.22%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 11.11%  |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.56%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.56%   |
| AuthenTec AES2810                                      | 1         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.56%   |
| AuthenTec AES1600                                      | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| Alcor Micro | 3         | 30%     |
| O2 Micro    | 1         | 10%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 10%     |
| Lenovo Integrated Smart Card Reader            | 1         | 10%     |
| Alcor Micro Watchdata W 1981                   | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 105       | 70.95%  |
| 1     | 36        | 24.32%  |
| 2     | 6         | 4.05%   |
| 3     | 1         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 17        | 34.69%  |
| Chipcard              | 10        | 20.41%  |
| Graphics card         | 8         | 16.33%  |
| Camera                | 4         | 8.16%   |
| Bluetooth             | 4         | 8.16%   |
| Network               | 2         | 4.08%   |
| Storage               | 1         | 2.04%   |
| Net/wireless          | 1         | 2.04%   |
| Multimedia controller | 1         | 2.04%   |
| Dvb card              | 1         | 2.04%   |

