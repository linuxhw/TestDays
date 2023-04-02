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

Total: 183

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-43-generic     | 21        | 14.38%  |
| 5.15.0-56-generic     | 13        | 8.9%    |
| 5.15.0-58-generic     | 9         | 6.16%   |
| 5.15.0-25-generic     | 9         | 6.16%   |
| 5.15.0-60-generic     | 8         | 5.48%   |
| 5.15.0-30-generic     | 8         | 5.48%   |
| 5.15.0-47-generic     | 7         | 4.79%   |
| 5.15.0-46-generic     | 7         | 4.79%   |
| 5.15.0-52-generic     | 6         | 4.11%   |
| 5.15.0-27-generic     | 6         | 4.11%   |
| 5.19.0-35-generic     | 5         | 3.42%   |
| 5.15.0-53-generic     | 5         | 3.42%   |
| 5.15.0-57-generic     | 4         | 2.74%   |
| 5.15.0-50-generic     | 4         | 2.74%   |
| 5.15.0-41-generic     | 4         | 2.74%   |
| 5.15.0-67-generic     | 3         | 2.05%   |
| 5.15.0-48-generic     | 3         | 2.05%   |
| 5.15.0-40-generic     | 3         | 2.05%   |
| 5.15.0-35-generic     | 3         | 2.05%   |
| 5.19.0-32-generic     | 2         | 1.37%   |
| 5.15.0-37-generic     | 2         | 1.37%   |
| 5.15.0-33-generic     | 2         | 1.37%   |
| 6.1.12-060112-generic | 1         | 0.68%   |
| 6.0.12-x64v2-xanmod1  | 1         | 0.68%   |
| 5.4.0-139-generic     | 1         | 0.68%   |
| 5.19.8-xanmod1        | 1         | 0.68%   |
| 5.19.0-051900-generic | 1         | 0.68%   |
| 5.18.0-051800-generic | 1         | 0.68%   |
| 5.15.0-54-generic     | 1         | 0.68%   |
| 5.15.0-39-generic     | 1         | 0.68%   |
| 5.15.0-28-generic     | 1         | 0.68%   |
| 5.15.0-23-generic     | 1         | 0.68%   |
| 5.15.0-18-generic     | 1         | 0.68%   |
| 5.14.0-1040-oem       | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 123       | 90.44%  |
| 5.19.0  | 7         | 5.15%   |
| 6.1.12  | 1         | 0.74%   |
| 6.0.12  | 1         | 0.74%   |
| 5.4.0   | 1         | 0.74%   |
| 5.19.8  | 1         | 0.74%   |
| 5.18.0  | 1         | 0.74%   |
| 5.14.0  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 123       | 90.44%  |
| 5.19    | 8         | 5.88%   |
| 6.1     | 1         | 0.74%   |
| 6.0     | 1         | 0.74%   |
| 5.4     | 1         | 0.74%   |
| 5.18    | 1         | 0.74%   |
| 5.14    | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 132       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 128       | 96.97%  |
| X-Cinnamon | 2         | 1.52%   |
| LXDE       | 2         | 1.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 130       | 98.48%  |
| Tty  | 2         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 117       | 87.97%  |
| LightDM | 8         | 6.02%   |
| Unknown | 7         | 5.26%   |
| GDM3    | 1         | 0.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 35        | 26.32%  |
| fr_FR  | 11        | 8.27%   |
| it_IT  | 10        | 7.52%   |
| C      | 9         | 6.77%   |
| pt_BR  | 8         | 6.02%   |
| pl_PL  | 7         | 5.26%   |
| de_DE  | 7         | 5.26%   |
| en_AG  | 6         | 4.51%   |
| ru_RU  | 5         | 3.76%   |
| en_GB  | 5         | 3.76%   |
| nl_BE  | 3         | 2.26%   |
| es_MX  | 2         | 1.5%    |
| es_ES  | 2         | 1.5%    |
| es_CR  | 2         | 1.5%    |
| es_AR  | 2         | 1.5%    |
| en_CA  | 2         | 1.5%    |
| tr_TR  | 1         | 0.75%   |
| nl_NL  | 1         | 0.75%   |
| lzh_TW | 1         | 0.75%   |
| ja_JP  | 1         | 0.75%   |
| hu_HU  | 1         | 0.75%   |
| fr_CA  | 1         | 0.75%   |
| fi_FI  | 1         | 0.75%   |
| es_EC  | 1         | 0.75%   |
| es_CO  | 1         | 0.75%   |
| es_CL  | 1         | 0.75%   |
| en_ZA  | 1         | 0.75%   |
| en_PH  | 1         | 0.75%   |
| en_DE  | 1         | 0.75%   |
| en_AU  | 1         | 0.75%   |
| el_GR  | 1         | 0.75%   |
| de_CH  | 1         | 0.75%   |
| aa_DJ  | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 84        | 63.16%  |
| EFI  | 49        | 36.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 119       | 88.81%  |
| Overlay | 11        | 8.21%   |
| Btrfs   | 2         | 1.49%   |
| Xfs     | 1         | 0.75%   |
| Ext2    | 1         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 66        | 48.89%  |
| MBR     | 41        | 30.37%  |
| Unknown | 28        | 20.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 90.23%  |
| Yes       | 13        | 9.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 74.44%  |
| Yes       | 34        | 25.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 29        | 21.97%  |
| Hewlett-Packard     | 16        | 12.12%  |
| Dell                | 16        | 12.12%  |
| Acer                | 14        | 10.61%  |
| ASUSTek Computer    | 9         | 6.82%   |
| Google              | 6         | 4.55%   |
| Apple               | 6         | 4.55%   |
| Fujitsu             | 4         | 3.03%   |
| Sony                | 3         | 2.27%   |
| Unknown             | 3         | 2.27%   |
| Toshiba             | 2         | 1.52%   |
| Positivo            | 2         | 1.52%   |
| Mediacom            | 2         | 1.52%   |
| Intel               | 2         | 1.52%   |
| Gateway             | 2         | 1.52%   |
| Thomson             | 1         | 0.76%   |
| SGIN                | 1         | 0.76%   |
| Samsung Electronics | 1         | 0.76%   |
| Pretech             | 1         | 0.76%   |
| Prestigio           | 1         | 0.76%   |
| Packard Bell        | 1         | 0.76%   |
| OEM                 | 1         | 0.76%   |
| MSI                 | 1         | 0.76%   |
| Kiano               | 1         | 0.76%   |
| IFSA                | 1         | 0.76%   |
| HUAWEI              | 1         | 0.76%   |
| GPU Company         | 1         | 0.76%   |
| Getac               | 1         | 0.76%   |
| Fujitsu Siemens     | 1         | 0.76%   |
| Chuwi               | 1         | 0.76%   |
| Alienware           | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 3.03%   |
| Apple MacBookPro8,1                        | 3         | 2.27%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 2         | 1.52%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 1.52%   |
| Lenovo G50-30 80G0                         | 2         | 1.52%   |
| HP Pavilion g6                             | 2         | 1.52%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 1.52%   |
| Toshiba Satellite Pro S500                 | 1         | 0.76%   |
| Toshiba Satellite L40                      | 1         | 0.76%   |
| Thomson N14C4WH64                          | 1         | 0.76%   |
| Sony VPCEB15FM                             | 1         | 0.76%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.76%   |
| Sony SVE14A2V1EW                           | 1         | 0.76%   |
| SGIN laptop                                | 1         | 0.76%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.76%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.76%   |
| Prestigio PSB141C01BFH                     | 1         | 0.76%   |
| Positivo Q232A                             | 1         | 0.76%   |
| Positivo i500pro                           | 1         | 0.76%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.76%   |
| MSI S12T 3M/S12 3M                         | 1         | 0.76%   |
| Lenovo Z70-80 80FG                         | 1         | 0.76%   |
| Lenovo ThinkPad X230 Tablet 3437CTO        | 1         | 0.76%   |
| Lenovo ThinkPad X220 4291H82               | 1         | 0.76%   |
| Lenovo ThinkPad X201 3626AL3               | 1         | 0.76%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0WE02   | 1         | 0.76%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.76%   |
| Lenovo ThinkPad T410 2537CS0               | 1         | 0.76%   |
| Lenovo ThinkPad SL510 2847CXG              | 1         | 0.76%   |
| Lenovo ThinkPad P14s Gen 2a 21A1S00D00     | 1         | 0.76%   |
| Lenovo ThinkPad L520 5015AH2               | 1         | 0.76%   |
| Lenovo ThinkPad E550 20DF00CUFR            | 1         | 0.76%   |
| Lenovo IdeaPad S340-15IWL 81N8             | 1         | 0.76%   |
| Lenovo IdeaPad S145-15IGM 81MX             | 1         | 0.76%   |
| Lenovo IdeaPad L340-15IRH Gaming 81TR      | 1         | 0.76%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 1         | 0.76%   |
| Lenovo IdeaPad 5 14ABA7 82SE               | 1         | 0.76%   |
| Lenovo IdeaPad 330-15IKB Touch 81DJ        | 1         | 0.76%   |
| Lenovo IdeaPad 100S-14IBR 80R9             | 1         | 0.76%   |
| Lenovo IdeaPad 1 15AMN7 82VG               | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 11        | 8.33%   |
| Lenovo ThinkPad        | 10        | 7.58%   |
| Acer Aspire            | 9         | 6.82%   |
| Dell Latitude          | 8         | 6.06%   |
| HP Pavilion            | 5         | 3.79%   |
| Fujitsu LIFEBOOK       | 4         | 3.03%   |
| Unknown                | 4         | 3.03%   |
| HP ProBook             | 3         | 2.27%   |
| Apple MacBookPro8      | 3         | 2.27%   |
| Toshiba Satellite      | 2         | 1.52%   |
| Mediacom WinPad        | 2         | 1.52%   |
| Lenovo G50-30          | 2         | 1.52%   |
| HP Laptop              | 2         | 1.52%   |
| Dell XPS               | 2         | 1.52%   |
| Dell Precision         | 2         | 1.52%   |
| Thomson N14C4WH64      | 1         | 0.76%   |
| Sony VPCEB15FM         | 1         | 0.76%   |
| Sony VGN-SZ71WN        | 1         | 0.76%   |
| Sony SVE14A2V1EW       | 1         | 0.76%   |
| SGIN laptop            | 1         | 0.76%   |
| Samsung 300V3A         | 1         | 0.76%   |
| Pretech EVE            | 1         | 0.76%   |
| Prestigio PSB141C01BFH | 1         | 0.76%   |
| Positivo Q232A         | 1         | 0.76%   |
| Positivo i500pro       | 1         | 0.76%   |
| Packard Bell EasyNote  | 1         | 0.76%   |
| MSI S12T               | 1         | 0.76%   |
| Lenovo Z70-80          | 1         | 0.76%   |
| Lenovo G505s           | 1         | 0.76%   |
| Lenovo G500            | 1         | 0.76%   |
| Lenovo G50-70          | 1         | 0.76%   |
| Lenovo G50-45          | 1         | 0.76%   |
| Lenovo B590            | 1         | 0.76%   |
| Kiano SlimNote         | 1         | 0.76%   |
| Intel powered          | 1         | 0.76%   |
| Intel Infoway          | 1         | 0.76%   |
| IFSA Positivo          | 1         | 0.76%   |
| HUAWEI KLVD-WXX9       | 1         | 0.76%   |
| HP Notebook            | 1         | 0.76%   |
| HP Compaq              | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 18        | 13.64%  |
| 2013 | 14        | 10.61%  |
| 2012 | 12        | 9.09%   |
| 2021 | 10        | 7.58%   |
| 2019 | 9         | 6.82%   |
| 2015 | 9         | 6.82%   |
| 2014 | 9         | 6.82%   |
| 2020 | 8         | 6.06%   |
| 2016 | 8         | 6.06%   |
| 2008 | 7         | 5.3%    |
| 2010 | 6         | 4.55%   |
| 2009 | 6         | 4.55%   |
| 2022 | 5         | 3.79%   |
| 2007 | 4         | 3.03%   |
| 2018 | 3         | 2.27%   |
| 2017 | 3         | 2.27%   |
| 2023 | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 132       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 127       | 95.49%  |
| Enabled  | 6         | 4.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 125       | 94.7%   |
| Yes  | 7         | 5.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 54        | 40.6%   |
| 4.01-8.0   | 33        | 24.81%  |
| 1.01-2.0   | 18        | 13.53%  |
| 8.01-16.0  | 13        | 9.77%   |
| 16.01-24.0 | 8         | 6.02%   |
| 2.01-3.0   | 5         | 3.76%   |
| 32.01-64.0 | 2         | 1.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 66        | 47.48%  |
| 0.51-1.0 | 34        | 24.46%  |
| 2.01-3.0 | 27        | 19.42%  |
| 4.01-8.0 | 6         | 4.32%   |
| 3.01-4.0 | 6         | 4.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 81.34%  |
| 2      | 21        | 15.67%  |
| 3      | 2         | 1.49%   |
| 0      | 2         | 1.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 57.58%  |
| Yes       | 56        | 42.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 75.76%  |
| No        | 32        | 24.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 91.67%  |
| No        | 11        | 8.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 68.42%  |
| No        | 42        | 31.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 15.91%  |
| Italy        | 12        | 9.09%   |
| France       | 12        | 9.09%   |
| Germany      | 11        | 8.33%   |
| Russia       | 8         | 6.06%   |
| Poland       | 8         | 6.06%   |
| Brazil       | 8         | 6.06%   |
| Belgium      | 5         | 3.79%   |
| UK           | 4         | 3.03%   |
| Canada       | 4         | 3.03%   |
| Ukraine      | 3         | 2.27%   |
| Costa Rica   | 3         | 2.27%   |
| Vietnam      | 2         | 1.52%   |
| Turkey       | 2         | 1.52%   |
| Spain        | 2         | 1.52%   |
| Netherlands  | 2         | 1.52%   |
| Mexico       | 2         | 1.52%   |
| Hungary      | 2         | 1.52%   |
| Argentina    | 2         | 1.52%   |
| Thailand     | 1         | 0.76%   |
| Taiwan       | 1         | 0.76%   |
| Switzerland  | 1         | 0.76%   |
| Sweden       | 1         | 0.76%   |
| South Africa | 1         | 0.76%   |
| Portugal     | 1         | 0.76%   |
| Philippines  | 1         | 0.76%   |
| Latvia       | 1         | 0.76%   |
| Kenya        | 1         | 0.76%   |
| Japan        | 1         | 0.76%   |
| Indonesia    | 1         | 0.76%   |
| Greece       | 1         | 0.76%   |
| Finland      | 1         | 0.76%   |
| Ecuador      | 1         | 0.76%   |
| Colombia     | 1         | 0.76%   |
| Chile        | 1         | 0.76%   |
| Belarus      | 1         | 0.76%   |
| Australia    | 1         | 0.76%   |
| Armenia      | 1         | 0.76%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Paris                     | 4         | 2.9%    |
| Ghent                     | 3         | 2.17%   |
| Sarospatak                | 2         | 1.45%   |
| Porto Alegre              | 2         | 1.45%   |
| Milan                     | 2         | 1.45%   |
| Lansing                   | 2         | 1.45%   |
| Kyiv                      | 2         | 1.45%   |
| Heredia                   | 2         | 1.45%   |
| Zizur Mayor               | 1         | 0.72%   |
| Zawiercie                 | 1         | 0.72%   |
| Yoshkar-Ola               | 1         | 0.72%   |
| Yorkville                 | 1         | 0.72%   |
| Yerevan                   | 1         | 0.72%   |
| Yekaterinburg             | 1         | 0.72%   |
| Wolfhagen                 | 1         | 0.72%   |
| West Stockbridge          | 1         | 0.72%   |
| Warsaw                    | 1         | 0.72%   |
| Warendorf                 | 1         | 0.72%   |
| Volzhskiy                 | 1         | 0.72%   |
| Verona                    | 1         | 0.72%   |
| Uberlândia               | 1         | 0.72%   |
| Tychy                     | 1         | 0.72%   |
| Thornton Heath            | 1         | 0.72%   |
| Thessaloniki              | 1         | 0.72%   |
| Taipei                    | 1         | 0.72%   |
| Surabaya                  | 1         | 0.72%   |
| Stuttgart                 | 1         | 0.72%   |
| Strzyzow                  | 1         | 0.72%   |
| Stockholm                 | 1         | 0.72%   |
| Southampton               | 1         | 0.72%   |
| South Burlington          | 1         | 0.72%   |
| Sao Paulo                 | 1         | 0.72%   |
| Santiago de Compostela    | 1         | 0.72%   |
| Santiago                  | 1         | 0.72%   |
| Saint-Raymond-de-Portneuf | 1         | 0.72%   |
| Saint-Martin-Lacaussade   | 1         | 0.72%   |
| Roswell                   | 1         | 0.72%   |
| Rossano Veneto            | 1         | 0.72%   |
| Rome                      | 1         | 0.72%   |
| Rio de Janeiro            | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 22        | 32     | 15.38%  |
| WDC                       | 17        | 21     | 11.89%  |
| Seagate                   | 17        | 20     | 11.89%  |
| Toshiba                   | 12        | 13     | 8.39%   |
| Samsung Electronics       | 10        | 14     | 6.99%   |
| Kingston                  | 6         | 6      | 4.2%    |
| Hitachi                   | 6         | 8      | 4.2%    |
| SanDisk                   | 5         | 5      | 3.5%    |
| HGST                      | 4         | 4      | 2.8%    |
| A-DATA Technology         | 4         | 4      | 2.8%    |
| SK hynix                  | 3         | 3      | 2.1%    |
| Micron Technology         | 3         | 4      | 2.1%    |
| Crucial                   | 3         | 3      | 2.1%    |
| UMIS                      | 2         | 2      | 1.4%    |
| SPCC                      | 2         | 3      | 1.4%    |
| Intel                     | 2         | 2      | 1.4%    |
| GOODRAM                   | 2         | 2      | 1.4%    |
| Fujitsu                   | 2         | 2      | 1.4%    |
| Apacer                    | 2         | 2      | 1.4%    |
| W800S                     | 1         | 1      | 0.7%    |
| Transcend                 | 1         | 2      | 0.7%    |
| Teclast                   | 1         | 1      | 0.7%    |
| Rogueware                 | 1         | 1      | 0.7%    |
| Plextor                   | 1         | 1      | 0.7%    |
| Phison                    | 1         | 1      | 0.7%    |
| NGFF                      | 1         | 1      | 0.7%    |
| Micron/Crucial Technology | 1         | 1      | 0.7%    |
| LITEON                    | 1         | 1      | 0.7%    |
| Lexar                     | 1         | 1      | 0.7%    |
| Leqixiang                 | 1         | 1      | 0.7%    |
| Lenovo                    | 1         | 1      | 0.7%    |
| LDLC                      | 1         | 1      | 0.7%    |
| KINGPOWER                 | 1         | 1      | 0.7%    |
| Intenso                   | 1         | 1      | 0.7%    |
| HUSKY                     | 1         | 1      | 0.7%    |
| China                     | 1         | 1      | 0.7%    |
| Apple                     | 1         | 2      | 0.7%    |
| Unknown                   | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST9500325AS 500GB            | 5         | 3.27%   |
| Unknown MMC Card  32GB               | 4         | 2.61%   |
| Unknown MMC Card  64GB               | 3         | 1.96%   |
| SanDisk DF4032  32GB                 | 3         | 1.96%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 1.31%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 1.31%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 1.31%   |
| Unknown SD/MMC/MS PRO 64GB           | 2         | 1.31%   |
| Unknown SC64G  64GB                  | 2         | 1.31%   |
| Unknown NCard  32GB                  | 2         | 1.31%   |
| Unknown MMC64G  64GB                 | 2         | 1.31%   |
| Unknown DA4032  32GB                 | 2         | 1.31%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.31%   |
| Toshiba MQ01ABD050 500GB             | 2         | 1.31%   |
| SPCC Solid State Disk 120GB          | 2         | 1.31%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1.31%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.31%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 1.31%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.31%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.65%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.65%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.65%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.65%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.65%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.65%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.65%   |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.65%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.65%   |
| WDC PC SN730 SDBQNTY-256G-1006 256GB | 1         | 0.65%   |
| W800S 256GB SSD                      | 1         | 0.65%   |
| Unknown SF64G  64GB                  | 1         | 0.65%   |
| Unknown SC256  256GB                 | 1         | 0.65%   |
| Unknown MMC Card  16GB               | 1         | 0.65%   |
| Unknown ISOCOM  64GB                 | 1         | 0.65%   |
| Unknown HAG4a2  16GB                 | 1         | 0.65%   |
| Unknown ED2S5  128GB                 | 1         | 0.65%   |
| Unknown DA4064  64GB                 | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 20     | 30.36%  |
| WDC                 | 14        | 15     | 25%     |
| Toshiba             | 10        | 11     | 17.86%  |
| Hitachi             | 6         | 8      | 10.71%  |
| HGST                | 4         | 4      | 7.14%   |
| Unknown             | 2         | 2      | 3.57%   |
| Fujitsu             | 2         | 2      | 3.57%   |
| Samsung Electronics | 1         | 5      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 15.22%  |
| Kingston            | 5         | 5      | 10.87%  |
| A-DATA Technology   | 4         | 4      | 8.7%    |
| WDC                 | 2         | 3      | 4.35%   |
| Toshiba             | 2         | 2      | 4.35%   |
| SPCC                | 2         | 3      | 4.35%   |
| SanDisk             | 2         | 2      | 4.35%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| Intel               | 2         | 2      | 4.35%   |
| GOODRAM             | 2         | 2      | 4.35%   |
| Crucial             | 2         | 2      | 4.35%   |
| Apacer              | 2         | 2      | 4.35%   |
| W800S               | 1         | 1      | 2.17%   |
| Transcend           | 1         | 2      | 2.17%   |
| Teclast             | 1         | 1      | 2.17%   |
| Rogueware           | 1         | 1      | 2.17%   |
| Plextor             | 1         | 1      | 2.17%   |
| NGFF                | 1         | 1      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| Lexar               | 1         | 1      | 2.17%   |
| Leqixiang           | 1         | 1      | 2.17%   |
| Lenovo              | 1         | 1      | 2.17%   |
| KINGPOWER           | 1         | 1      | 2.17%   |
| HUSKY               | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 55        | 67     | 37.93%  |
| SSD     | 46        | 49     | 31.72%  |
| MMC     | 26        | 35     | 17.93%  |
| NVMe    | 15        | 17     | 10.34%  |
| Unknown | 3         | 3      | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 114    | 67.61%  |
| MMC  | 26        | 35     | 18.31%  |
| NVMe | 15        | 17     | 10.56%  |
| SAS  | 5         | 5      | 3.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 90     | 78.57%  |
| 0.51-1.0   | 19        | 24     | 19.39%  |
| 1.01-2.0   | 1         | 1      | 1.02%   |
| 4.01-10.0  | 1         | 1      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 34.81%  |
| 251-500        | 35        | 25.93%  |
| 1-20           | 15        | 11.11%  |
| 51-100         | 12        | 8.89%   |
| 21-50          | 11        | 8.15%   |
| 501-1000       | 11        | 8.15%   |
| More than 3000 | 1         | 0.74%   |
| 2001-3000      | 1         | 0.74%   |
| 1001-2000      | 1         | 0.74%   |
| Unknown        | 1         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 54.74%  |
| 21-50          | 28        | 20.44%  |
| 51-100         | 14        | 10.22%  |
| 101-250        | 11        | 8.03%   |
| 251-500        | 4         | 2.92%   |
| 501-1000       | 2         | 1.46%   |
| More than 3000 | 1         | 0.73%   |
| 1001-2000      | 1         | 0.73%   |
| Unknown        | 1         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 2         | 2      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 9.09%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 4.55%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 4.55%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 4.55%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 4.55%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 4.55%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 4.55%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 4.55%   |
| Samsung Electronics HM121HI 120GB  | 1         | 5      | 4.55%   |
| Plextor PX-128M6M 128GB SSD        | 1         | 1      | 4.55%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 4.55%   |
| Intel SSDSA2M080G2LE 80GB          | 1         | 1      | 4.55%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 4.55%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 4.55%   |
| HGST HTS725032A7E630 320GB         | 1         | 1      | 4.55%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 4.55%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 40.91%  |
| WDC                 | 2         | 2      | 9.09%   |
| Toshiba             | 2         | 2      | 9.09%   |
| Hitachi             | 2         | 2      | 9.09%   |
| Samsung Electronics | 1         | 5      | 4.55%   |
| Plextor             | 1         | 1      | 4.55%   |
| NGFF                | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |
| Apacer              | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 50%     |
| WDC                 | 2         | 2      | 11.11%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Hitachi             | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 5      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 22     | 81.82%  |
| SSD  | 4         | 4      | 18.18%  |

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
| Detected | 77        | 100    | 55.4%   |
| Works    | 40        | 45     | 28.78%  |
| Malfunc  | 22        | 26     | 15.83%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 94        | 74.02%  |
| AMD                              | 15        | 11.81%  |
| Union Memory (Shenzhen)          | 2         | 1.57%   |
| SK hynix                         | 2         | 1.57%   |
| SanDisk                          | 2         | 1.57%   |
| Samsung Electronics              | 2         | 1.57%   |
| Nvidia                           | 2         | 1.57%   |
| Micron/Crucial Technology        | 2         | 1.57%   |
| Micron Technology                | 2         | 1.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.79%   |
| Silicon Image                    | 1         | 0.79%   |
| Phison Electronics               | 1         | 0.79%   |
| Kingston Technology Company      | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 10%     |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 7.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 6.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 5.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 6         | 4.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 4.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 3.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 3.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 2.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 2.14%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 1.43%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.43%   |
| Micron NVMe Storage Controller                                                   | 2         | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.43%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 1.43%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.43%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.71%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.71%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.71%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.71%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.71%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                             | 1         | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.71%   |
| Kingston Company NVMe Controller                                                 | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 101       | 74.81%  |
| NVMe | 14        | 10.37%  |
| IDE  | 14        | 10.37%  |
| RAID | 6         | 4.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 87.88%  |
| AMD    | 16        | 12.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 3.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 3.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 3.03%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.27%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 3         | 2.27%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.52%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.52%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 2         | 1.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.52%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.52%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.52%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 1.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.52%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.52%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 2         | 1.52%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.52%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.52%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 1.52%   |
| AMD E-450 APU with Radeon HD Graphics         | 2         | 1.52%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 2         | 1.52%   |
| AMD A6-9220e RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.52%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.76%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.76%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.76%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.76%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.76%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.76%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.76%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 0.76%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 1         | 0.76%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.76%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 0.76%   |
| Intel Core i7 CPU L 620 @ 2.00GHz             | 1         | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 27        | 20.45%  |
| Intel Celeron      | 27        | 20.45%  |
| Intel Core i3      | 14        | 10.61%  |
| Intel Core 2 Duo   | 14        | 10.61%  |
| Intel Core i7      | 13        | 9.85%   |
| Intel Atom         | 10        | 7.58%   |
| Intel Pentium      | 7         | 5.3%    |
| AMD E1             | 3         | 2.27%   |
| AMD A6             | 3         | 2.27%   |
| Intel Core 2       | 2         | 1.52%   |
| AMD E              | 2         | 1.52%   |
| AMD A8             | 2         | 1.52%   |
| Other              | 1         | 0.76%   |
| Intel Pentium Dual | 1         | 0.76%   |
| AMD Ryzen 7 PRO    | 1         | 0.76%   |
| AMD Ryzen 7        | 1         | 0.76%   |
| AMD Ryzen 5        | 1         | 0.76%   |
| AMD E2             | 1         | 0.76%   |
| AMD C-60           | 1         | 0.76%   |
| AMD Athlon         | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 94        | 71.21%  |
| 4      | 32        | 24.24%  |
| 1      | 3         | 2.27%   |
| 8      | 2         | 1.52%   |
| 6      | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 69        | 52.27%  |
| 2      | 63        | 47.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 132       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 36.84%  |
| 0x206a7    | 9         | 6.77%   |
| 0x306a9    | 8         | 6.02%   |
| 0x406c4    | 5         | 3.76%   |
| 0x406c3    | 5         | 3.76%   |
| 0x6fd      | 4         | 3.01%   |
| 0x806ec    | 3         | 2.26%   |
| 0x806ea    | 3         | 2.26%   |
| 0x706a8    | 3         | 2.26%   |
| 0x40651    | 3         | 2.26%   |
| 0x30678    | 3         | 2.26%   |
| 0x20655    | 3         | 2.26%   |
| 0x1067a    | 3         | 2.26%   |
| 0x05000119 | 3         | 2.26%   |
| 0x906c0    | 2         | 1.5%    |
| 0x706e5    | 2         | 1.5%    |
| 0x0a50000c | 2         | 1.5%    |
| 0x0700010f | 2         | 1.5%    |
| 0x06006705 | 2         | 1.5%    |
| 0x906ed    | 1         | 0.75%   |
| 0x806eb    | 1         | 0.75%   |
| 0x806e9    | 1         | 0.75%   |
| 0x806c1    | 1         | 0.75%   |
| 0x706a1    | 1         | 0.75%   |
| 0x6fa      | 1         | 0.75%   |
| 0x6f6      | 1         | 0.75%   |
| 0x506e3    | 1         | 0.75%   |
| 0x506c9    | 1         | 0.75%   |
| 0x406e3    | 1         | 0.75%   |
| 0x306c3    | 1         | 0.75%   |
| 0x20652    | 1         | 0.75%   |
| 0x106ca    | 1         | 0.75%   |
| 0x10676    | 1         | 0.75%   |
| 0x08a00006 | 1         | 0.75%   |
| 0x08608102 | 1         | 0.75%   |
| 0x06006704 | 1         | 0.75%   |
| 0x06001119 | 1         | 0.75%   |
| 0x06001116 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Silvermont    | 24        | 18.18%  |
| SandyBridge   | 16        | 12.12%  |
| KabyLake      | 11        | 8.33%   |
| IvyBridge     | 11        | 8.33%   |
| Penryn        | 9         | 6.82%   |
| Haswell       | 8         | 6.06%   |
| Core          | 8         | 6.06%   |
| Westmere      | 7         | 5.3%    |
| Goldmont plus | 7         | 5.3%    |
| Skylake       | 3         | 2.27%   |
| Piledriver    | 3         | 2.27%   |
| Excavator     | 3         | 2.27%   |
| Broadwell     | 3         | 2.27%   |
| Bobcat        | 3         | 2.27%   |
| Zen 3         | 2         | 1.52%   |
| Tremont       | 2         | 1.52%   |
| Jaguar        | 2         | 1.52%   |
| IceLake       | 2         | 1.52%   |
| Goldmont      | 2         | 1.52%   |
| Bonnell       | 2         | 1.52%   |
| Unknown       | 2         | 1.52%   |
| TigerLake     | 1         | 0.76%   |
| Puma          | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 106       | 73.61%  |
| AMD    | 23        | 15.97%  |
| Nvidia | 15        | 10.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 10.26%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 9.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 7.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 5.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 4.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 4.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 4.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 3.85%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.92%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.92%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.28%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.28%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.28%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.28%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.28%   |
| Intel HD Graphics 500                                                                    | 2         | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.28%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.28%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 1.28%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.28%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 1.28%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.64%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.64%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.64%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 1         | 0.64%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.64%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.64%   |
| Nvidia G86M [GeForce 9300M G]                                                            | 1         | 0.64%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 92        | 69.7%   |
| 1 x AMD        | 14        | 10.61%  |
| 1 x Nvidia     | 9         | 6.82%   |
| Intel + Nvidia | 6         | 4.55%   |
| Intel + AMD    | 5         | 3.79%   |
| 2 x AMD        | 4         | 3.03%   |
| Other          | 2         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 127       | 96.21%  |
| Proprietary | 3         | 2.27%   |
| Unknown     | 2         | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 82.71%  |
| 0.01-0.5   | 12        | 9.02%   |
| 1.01-2.0   | 6         | 4.51%   |
| 0.51-1.0   | 2         | 1.5%    |
| 5.01-6.0   | 1         | 0.75%   |
| 3.01-4.0   | 1         | 0.75%   |
| 2.01-3.0   | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 20.15%  |
| LG Display              | 23        | 17.16%  |
| Chimei Innolux          | 18        | 13.43%  |
| BOE                     | 18        | 13.43%  |
| Samsung Electronics     | 12        | 8.96%   |
| Apple                   | 7         | 5.22%   |
| CPT                     | 5         | 3.73%   |
| Lenovo                  | 4         | 2.99%   |
| Chi Mei Optoelectronics | 3         | 2.24%   |
| Toshiba                 | 2         | 1.49%   |
| Sharp                   | 2         | 1.49%   |
| LG Philips              | 2         | 1.49%   |
| Hewlett-Packard         | 2         | 1.49%   |
| Goldstar                | 2         | 1.49%   |
| ViewSonic               | 1         | 0.75%   |
| JVC                     | 1         | 0.75%   |
| JDI                     | 1         | 0.75%   |
| CS_                     | 1         | 0.75%   |
| BenQ                    | 1         | 0.75%   |
| AOC                     | 1         | 0.75%   |
| Acer                    | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 5         | 3.73%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 1.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.49%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 1.49%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 1.49%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 1.49%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 2         | 1.49%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.75%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch              | 1         | 0.75%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.75%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.75%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 1         | 0.75%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x287mm 23.0-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3254 1366x768 293x165mm 13.2-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 1         | 0.75%   |
| LG Philips LCD Monitor LPLEC00 1280x800 331x207mm 15.4-inch           | 1         | 0.75%   |
| LG Philips LCD Monitor LPL1101 1280x800 304x190mm 14.1-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0680 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD044B 1366x768 344x194mm 15.5-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x174mm 14.0-inch          | 1         | 0.75%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 67        | 50.76%  |
| 1920x1080 (FHD)    | 24        | 18.18%  |
| 1280x800 (WXGA)    | 18        | 13.64%  |
| 1600x900 (HD+)     | 8         | 6.06%   |
| 2560x1440 (QHD)    | 3         | 2.27%   |
| 3200x1800 (QHD+)   | 2         | 1.52%   |
| 2160x1440          | 2         | 1.52%   |
| 1440x900 (WXGA+)   | 2         | 1.52%   |
| 3840x2160 (4K)     | 1         | 0.76%   |
| 3000x2000          | 1         | 0.76%   |
| 2560x1080          | 1         | 0.76%   |
| 1680x1050 (WSXGA+) | 1         | 0.76%   |
| 1528x1222          | 1         | 0.76%   |
| 1360x768           | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 43        | 32.09%  |
| 14      | 24        | 17.91%  |
| 13      | 19        | 14.18%  |
| 11      | 15        | 11.19%  |
| 17      | 8         | 5.97%   |
| 12      | 8         | 5.97%   |
| 23      | 3         | 2.24%   |
| 24      | 2         | 1.49%   |
| 21      | 2         | 1.49%   |
| 19      | 2         | 1.49%   |
| 10      | 2         | 1.49%   |
| 28      | 1         | 0.75%   |
| 27      | 1         | 0.75%   |
| 18      | 1         | 0.75%   |
| 16      | 1         | 0.75%   |
| 9       | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 74        | 55.22%  |
| 201-300     | 37        | 27.61%  |
| 351-400     | 9         | 6.72%   |
| 501-600     | 5         | 3.73%   |
| 401-500     | 5         | 3.73%   |
| 601-700     | 2         | 1.49%   |
| 101-200     | 1         | 0.75%   |
| Unknown     | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 98        | 77.78%  |
| 16/10 | 22        | 17.46%  |
| 3/2   | 4         | 3.17%   |
| 4/3   | 1         | 0.79%   |
| 21/9  | 1         | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 43        | 32.09%  |
| 81-90          | 40        | 29.85%  |
| 51-60          | 15        | 11.19%  |
| 61-70          | 8         | 5.97%   |
| 121-130        | 8         | 5.97%   |
| 201-250        | 6         | 4.48%   |
| 71-80          | 3         | 2.24%   |
| 41-50          | 3         | 2.24%   |
| 251-300        | 2         | 1.49%   |
| 151-200        | 2         | 1.49%   |
| 301-350        | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 131-140        | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 62        | 46.62%  |
| 121-160       | 44        | 33.08%  |
| 51-100        | 17        | 12.78%  |
| 161-240       | 7         | 5.26%   |
| More than 240 | 2         | 1.5%    |
| Unknown       | 1         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 120       | 90.91%  |
| 2     | 9         | 6.82%   |
| 0     | 2         | 1.52%   |
| 3     | 1         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 61        | 30.81%  |
| Intel                           | 53        | 26.77%  |
| Qualcomm Atheros                | 34        | 17.17%  |
| Broadcom                        | 15        | 7.58%   |
| Marvell Technology Group        | 5         | 2.53%   |
| TP-Link                         | 3         | 1.52%   |
| Samsung Electronics             | 3         | 1.52%   |
| Broadcom Limited                | 3         | 1.52%   |
| Ralink                          | 2         | 1.01%   |
| Qualcomm Atheros Communications | 2         | 1.01%   |
| Qualcomm                        | 2         | 1.01%   |
| MediaTek                        | 2         | 1.01%   |
| ASIX Electronics                | 2         | 1.01%   |
| Xiaomi                          | 1         | 0.51%   |
| Sierra Wireless                 | 1         | 0.51%   |
| Ralink Technology               | 1         | 0.51%   |
| Nvidia                          | 1         | 0.51%   |
| NetGear                         | 1         | 0.51%   |
| Motorola PCS                    | 1         | 0.51%   |
| Microsoft                       | 1         | 0.51%   |
| JMicron Technology              | 1         | 0.51%   |
| ICS Advent                      | 1         | 0.51%   |
| Dell                            | 1         | 0.51%   |
| ASUSTek Computer                | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 12.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 2.49%   |
| Intel Wireless 7265                                               | 6         | 2.49%   |
| Intel Wireless 7260                                               | 6         | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.66%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.24%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 1.24%   |
| Intel Wireless 3160                                               | 3         | 1.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.24%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.24%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 1.24%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.24%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.83%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 37.88%  |
| Qualcomm Atheros                | 32        | 24.24%  |
| Realtek Semiconductor           | 26        | 19.7%   |
| Broadcom                        | 9         | 6.82%   |
| TP-Link                         | 2         | 1.52%   |
| Ralink                          | 2         | 1.52%   |
| Qualcomm Atheros Communications | 2         | 1.52%   |
| MediaTek                        | 2         | 1.52%   |
| Sierra Wireless                 | 1         | 0.76%   |
| Ralink Technology               | 1         | 0.76%   |
| NetGear                         | 1         | 0.76%   |
| Microsoft                       | 1         | 0.76%   |
| Dell                            | 1         | 0.76%   |
| Broadcom Limited                | 1         | 0.76%   |
| ASUSTek Computer                | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 5.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4.55%   |
| Intel Wireless 7265                                            | 6         | 4.55%   |
| Intel Wireless 7260                                            | 6         | 4.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 3.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.03%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 2.27%   |
| Intel Wireless 3160                                            | 3         | 2.27%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 2.27%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 2.27%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 2.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.52%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.52%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.52%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.52%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.76%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.76%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.76%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 1         | 0.76%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 1         | 0.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 44.44%  |
| Intel                    | 21        | 19.44%  |
| Broadcom                 | 10        | 9.26%   |
| Qualcomm Atheros         | 9         | 8.33%   |
| Marvell Technology Group | 5         | 4.63%   |
| Samsung Electronics      | 3         | 2.78%   |
| Qualcomm                 | 2         | 1.85%   |
| Broadcom Limited         | 2         | 1.85%   |
| ASIX Electronics         | 2         | 1.85%   |
| Xiaomi                   | 1         | 0.93%   |
| TP-Link                  | 1         | 0.93%   |
| Nvidia                   | 1         | 0.93%   |
| Motorola PCS             | 1         | 0.93%   |
| JMicron Technology       | 1         | 0.93%   |
| ICS Advent               | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31        | 28.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 9.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 6.42%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 3.67%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 3.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 2.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 2.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 2.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 2.75%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 1.83%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.92%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.92%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.92%   |
| Qualcomm QM215-QRD _SN:E72764DE                                                | 1         | 0.92%   |
| Qualcomm Fairphone 4 5G                                                        | 1         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.92%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.92%   |
| Motorola PCS moto g pure                                                       | 1         | 0.92%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.92%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.92%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.92%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.92%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.92%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.92%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.92%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 1         | 0.92%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 1         | 0.92%   |
| Broadcom NetXtreme BCM5756ME Gigabit Ethernet PCI Express                      | 1         | 0.92%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 54.75%  |
| Ethernet | 100       | 45.25%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 71.54%  |
| Ethernet | 37        | 28.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 86        | 65.15%  |
| 1     | 32        | 24.24%  |
| 0     | 13        | 9.85%   |
| 3     | 1         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 78.36%  |
| Yes  | 29        | 21.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 34.07%  |
| Realtek Semiconductor           | 15        | 16.48%  |
| Qualcomm Atheros Communications | 11        | 12.09%  |
| Broadcom                        | 7         | 7.69%   |
| Apple                           | 5         | 5.49%   |
| Lite-On Technology              | 4         | 4.4%    |
| Foxconn / Hon Hai               | 4         | 4.4%    |
| IMC Networks                    | 3         | 3.3%    |
| Dell                            | 3         | 3.3%    |
| Cambridge Silicon Radio         | 2         | 2.2%    |
| Toshiba                         | 1         | 1.1%    |
| Syntek                          | 1         | 1.1%    |
| Ralink                          | 1         | 1.1%    |
| Hewlett-Packard                 | 1         | 1.1%    |
| ASUSTek Computer                | 1         | 1.1%    |
| Alps Electric                   | 1         | 1.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 20.88%  |
| Realtek Bluetooth Radio                                                             | 10        | 10.99%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 6.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 4.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 4.4%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 4.4%    |
| Realtek RTL8723B Bluetooth                                                          | 3         | 3.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 3.3%    |
| Apple Bluetooth Host Controller                                                     | 3         | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.2%    |
| Intel AX201 Bluetooth                                                               | 2         | 2.2%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 2.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.2%    |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.1%    |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 1.1%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.1%    |
| Qualcomm Atheros Bluetooth                                                          | 1         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.1%    |
| Lite-On Wireless_Device                                                             | 1         | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.1%    |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.1%    |
| IMC Networks Bluetooth Device                                                       | 1         | 1.1%    |
| IMC Networks Bluetooth                                                              | 1         | 1.1%    |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 1.1%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.1%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 1.1%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.1%    |
| Dell Wireless 360 Bluetooth                                                         | 1         | 1.1%    |
| Dell Wireless 355 Bluetooth                                                         | 1         | 1.1%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.1%    |
| Broadcom HP Portable Valentine                                                      | 1         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.1%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 1.1%    |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.1%    |
| Apple Bluetooth HCI                                                                 | 1         | 1.1%    |
| Alps Electric Bluetooth Adapter                                                     | 1         | 1.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 104       | 78.2%   |
| AMD                  | 18        | 13.53%  |
| Nvidia               | 7         | 5.26%   |
| MosArt Semiconductor | 1         | 0.75%   |
| JMTek                | 1         | 0.75%   |
| EGO SYStems          | 1         | 0.75%   |
| C-Media Electronics  | 1         | 0.75%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 10.69%  |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 6.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 5.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 4.4%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 3.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 3.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 3.77%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 3.77%   |
| AMD FCH Azalia Controller                                                                         | 6         | 3.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.52%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 2.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.89%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.89%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.26%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 1.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.26%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.26%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.26%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.63%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.63%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 25.25%  |
| SK hynix            | 23        | 23.23%  |
| Micron Technology   | 13        | 13.13%  |
| Unknown             | 10        | 10.1%   |
| Nanya Technology    | 4         | 4.04%   |
| Elpida              | 4         | 4.04%   |
| Kingston            | 3         | 3.03%   |
| Unknown (ABCD)      | 2         | 2.02%   |
| Smart               | 2         | 2.02%   |
| Corsair             | 2         | 2.02%   |
| A-DATA Technology   | 2         | 2.02%   |
| Transcend           | 1         | 1.01%   |
| Ramaxel Technology  | 1         | 1.01%   |
| Novatech            | 1         | 1.01%   |
| Kllisre             | 1         | 1.01%   |
| Kingmax             | 1         | 1.01%   |
| HMD                 | 1         | 1.01%   |
| Apacer              | 1         | 1.01%   |
| AMD                 | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 2.8%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.87%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 2         | 1.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.87%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.87%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.87%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.87%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.87%   |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.87%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM 1067MT/s                | 2         | 1.87%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.93%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.93%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 0.93%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 0.93%   |
| SK hynix RAM HT5SMRAP 2GB SODIMM DDR3 1600MT/s                   | 1         | 0.93%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s           | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.93%   |
| SK hynix RAM H9JCNNNBK3MLYR-N6E 2GB SODIMM LPDDR5 5500MT/s       | 1         | 0.93%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB LPDDR3 1600MT/s              | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 47        | 54.65%  |
| DDR4   | 22        | 25.58%  |
| DDR2   | 6         | 6.98%   |
| LPDDR4 | 5         | 5.81%   |
| SDRAM  | 3         | 3.49%   |
| LPDDR3 | 2         | 2.33%   |
| LPDDR5 | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 88.37%  |
| Row Of Chips | 7         | 8.14%   |
| Unknown      | 3         | 3.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 33.67%  |
| 2048  | 32        | 32.65%  |
| 8192  | 22        | 22.45%  |
| 1024  | 6         | 6.12%   |
| 16384 | 3         | 3.06%   |
| 32768 | 1         | 1.02%   |
| 512   | 1         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 32.26%  |
| 3200    | 9         | 9.68%   |
| 1334    | 7         | 7.53%   |
| 1333    | 7         | 7.53%   |
| 2667    | 6         | 6.45%   |
| 2400    | 6         | 6.45%   |
| 667     | 5         | 5.38%   |
| 1066    | 4         | 4.3%    |
| 3266    | 3         | 3.23%   |
| 1067    | 3         | 3.23%   |
| 1866    | 2         | 2.15%   |
| 975     | 2         | 2.15%   |
| Unknown | 2         | 2.15%   |
| 5500    | 1         | 1.08%   |
| 4199    | 1         | 1.08%   |
| 3733    | 1         | 1.08%   |
| 2133    | 1         | 1.08%   |
| 2048    | 1         | 1.08%   |
| 1867    | 1         | 1.08%   |
| 800     | 1         | 1.08%   |

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
| Chicony Electronics                    | 31        | 28.44%  |
| Realtek Semiconductor                  | 11        | 10.09%  |
| Microdia                               | 11        | 10.09%  |
| Sunplus Innovation Technology          | 8         | 7.34%   |
| Syntek                                 | 5         | 4.59%   |
| IMC Networks                           | 5         | 4.59%   |
| Apple                                  | 5         | 4.59%   |
| Quanta                                 | 4         | 3.67%   |
| Alcor Micro                            | 4         | 3.67%   |
| Acer                                   | 4         | 3.67%   |
| Suyin                                  | 3         | 2.75%   |
| Lenovo                                 | 3         | 2.75%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.75%   |
| Silicon Motion                         | 2         | 1.83%   |
| Lite-On Technology                     | 2         | 1.83%   |
| ALi                                    | 2         | 1.83%   |
| Y Media                                | 1         | 0.92%   |
| USB Camera CS                          | 1         | 0.92%   |
| SunplusIT                              | 1         | 0.92%   |
| Ricoh                                  | 1         | 0.92%   |
| Logitech                               | 1         | 0.92%   |
| Cubeternet                             | 1         | 0.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 7.27%   |
| Realtek Integrated_Webcam_HD                        | 4         | 3.64%   |
| Chicony HD WebCam                                   | 4         | 3.64%   |
| Sunplus HD WebCam                                   | 3         | 2.73%   |
| Microdia Integrated Webcam                          | 3         | 2.73%   |
| Chicony HP TrueVision HD Camera                     | 3         | 2.73%   |
| Apple FaceTime HD Camera                            | 3         | 2.73%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.82%   |
| Microdia Lenovo EasyCamera                          | 2         | 1.82%   |
| Microdia HP Webcam-50                               | 2         | 1.82%   |
| Lenovo Integrated Webcam                            | 2         | 1.82%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.82%   |
| Chicony VGA Webcam                                  | 2         | 1.82%   |
| Chicony HP Truevision HD                            | 2         | 1.82%   |
| Chicony FJ Camera                                   | 2         | 1.82%   |
| Chicony EasyCamera                                  | 2         | 1.82%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 1.82%   |
| ALi WebCam                                          | 2         | 1.82%   |
| Alcor Micro USB 2.0 Camera                          | 2         | 1.82%   |
| Alcor Micro HD Webcam                               | 2         | 1.82%   |
| Acer Lenovo EasyCamera                              | 2         | 1.82%   |
| Y Media USB Camera                                  | 1         | 0.91%   |
| USB Camera CS USB Camera CS                         | 1         | 0.91%   |
| Syntek USB2.0 Camera                                | 1         | 0.91%   |
| Syntek USB Camera Device                            | 1         | 0.91%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.91%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.91%   |
| Syntek HD WebCam                                    | 1         | 0.91%   |
| Suyin VGA Webcam                                    | 1         | 0.91%   |
| Suyin Intel Webcam                                  | 1         | 0.91%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.91%   |
| SunplusIT USB camera                                | 1         | 0.91%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.91%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.91%   |
| Sunplus HD User Facing                              | 1         | 0.91%   |
| Sunplus Dell Integrated HD Webcam                   | 1         | 0.91%   |
| Sunplus Asus Webcam                                 | 1         | 0.91%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.91%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.91%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.91%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 29.41%  |
| Upek                       | 4         | 23.53%  |
| AuthenTec                  | 4         | 23.53%  |
| STMicroelectronics         | 2         | 11.76%  |
| Shenzhen Goodix Technology | 1         | 5.88%   |
| LighTuning Technology      | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 23.53%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 11.76%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.88%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.88%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.88%   |
| AuthenTec AES2810                                      | 1         | 5.88%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.88%   |
| AuthenTec AES1600                                      | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| Alcor Micro | 2         | 25%     |
| O2 Micro    | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor | 2         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 12.5%   |
| Alcor Micro Watchdata W 1981                   | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 95        | 71.97%  |
| 1     | 31        | 23.48%  |
| 2     | 6         | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 17        | 40.48%  |
| Chipcard           | 8         | 19.05%  |
| Graphics card      | 7         | 16.67%  |
| Camera             | 4         | 9.52%   |
| Bluetooth          | 2         | 4.76%   |
| Storage            | 1         | 2.38%   |
| Network            | 1         | 2.38%   |
| Net/wireless       | 1         | 2.38%   |
| Dvb card           | 1         | 2.38%   |

