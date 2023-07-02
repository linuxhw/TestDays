LMDE - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for LMDE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE/Desktop/README.md) and [notebooks](/Dist/LMDE/Notebook/README.md).

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

Total: 1255

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Q87M-D2H                    | Desktop     | [633c55d4ba](https://linux-hardware.org/?probe=633c55d4ba) | Jun 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [5cebe0a1d0](https://linux-hardware.org/?probe=5cebe0a1d0) | Jun 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [327794cb1a](https://linux-hardware.org/?probe=327794cb1a) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [67e8606837](https://linux-hardware.org/?probe=67e8606837) | Jun 29, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [95e5472f48](https://linux-hardware.org/?probe=95e5472f48) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4ae6c879aa](https://linux-hardware.org/?probe=4ae6c879aa) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [888133764a](https://linux-hardware.org/?probe=888133764a) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [67a44b0d84](https://linux-hardware.org/?probe=67a44b0d84) | Jun 20, 2023 |
| Intel         | X79                         | Desktop     | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [2344c78f90](https://linux-hardware.org/?probe=2344c78f90) | Jun 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [0173559ed0](https://linux-hardware.org/?probe=0173559ed0) | Jun 19, 2023 |
| Medion        | TJ4125                      | Desktop     | [4c6aec7e33](https://linux-hardware.org/?probe=4c6aec7e33) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| HP            | Compaq 15                   | Notebook    | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Medion        | E6214                       | Notebook    | [5547ea042f](https://linux-hardware.org/?probe=5547ea042f) | Jun 17, 2023 |
| Medion        | E6214                       | Notebook    | [98ddb6700a](https://linux-hardware.org/?probe=98ddb6700a) | Jun 17, 2023 |
| Medion        | TJ4125                      | Desktop     | [fc102c077c](https://linux-hardware.org/?probe=fc102c077c) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [59b855f1a1](https://linux-hardware.org/?probe=59b855f1a1) | Jun 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [3eb12fd9bc](https://linux-hardware.org/?probe=3eb12fd9bc) | Jun 10, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [56421d7b0f](https://linux-hardware.org/?probe=56421d7b0f) | Jun 09, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| AZW           | GK mini                     | Desktop     | [d9d37cb11a](https://linux-hardware.org/?probe=d9d37cb11a) | Jun 08, 2023 |
| Google        | Lick                        | Notebook    | [d220804cab](https://linux-hardware.org/?probe=d220804cab) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [ac442da472](https://linux-hardware.org/?probe=ac442da472) | Jun 08, 2023 |
| Dell          | G5 5587                     | Notebook    | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [05a3b3210a](https://linux-hardware.org/?probe=05a3b3210a) | Jun 06, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [eeaf6dbd4c](https://linux-hardware.org/?probe=eeaf6dbd4c) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [3faed0102f](https://linux-hardware.org/?probe=3faed0102f) | Jun 04, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [81caf6e8cf](https://linux-hardware.org/?probe=81caf6e8cf) | Jun 04, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [e27deb35b8](https://linux-hardware.org/?probe=e27deb35b8) | Jun 03, 2023 |
| Acer          | Spin SP111-32N              | Convertible | [60f94ec7f1](https://linux-hardware.org/?probe=60f94ec7f1) | Jun 03, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [0169222312](https://linux-hardware.org/?probe=0169222312) | Jun 03, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Intel         | B75                         | Desktop     | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Medion        | TJ4125                      | Desktop     | [6244ae0e43](https://linux-hardware.org/?probe=6244ae0e43) | Jun 02, 2023 |
| Unknown       | X99                         | Desktop     | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [8ededa47e6](https://linux-hardware.org/?probe=8ededa47e6) | Jun 02, 2023 |
| Intel         | DB85FL AAG89861-202         | Desktop     | [7bd893ebe1](https://linux-hardware.org/?probe=7bd893ebe1) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [c418655a3f](https://linux-hardware.org/?probe=c418655a3f) | Jun 02, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [309f368a92](https://linux-hardware.org/?probe=309f368a92) | Jun 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8f3525a119](https://linux-hardware.org/?probe=8f3525a119) | Jun 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7400ec0f1a](https://linux-hardware.org/?probe=7400ec0f1a) | May 31, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5e7eb5b41c](https://linux-hardware.org/?probe=5e7eb5b41c) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d38a3af9af](https://linux-hardware.org/?probe=d38a3af9af) | May 27, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [bca0574da6](https://linux-hardware.org/?probe=bca0574da6) | May 27, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2be29f15b4](https://linux-hardware.org/?probe=2be29f15b4) | May 27, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| Framework     | Laptop                      | Notebook    | [cdc855ea4c](https://linux-hardware.org/?probe=cdc855ea4c) | May 26, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bf6e9cf4d0](https://linux-hardware.org/?probe=bf6e9cf4d0) | May 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a3e5c89fe6](https://linux-hardware.org/?probe=a3e5c89fe6) | May 25, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | Notebook    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [9abb9659a8](https://linux-hardware.org/?probe=9abb9659a8) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3c82eec4d2](https://linux-hardware.org/?probe=3c82eec4d2) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ee4eca623f](https://linux-hardware.org/?probe=ee4eca623f) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [49e536226c](https://linux-hardware.org/?probe=49e536226c) | May 19, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [2abefd21ea](https://linux-hardware.org/?probe=2abefd21ea) | May 19, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [feb9ed8589](https://linux-hardware.org/?probe=feb9ed8589) | May 19, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [ce94bc6589](https://linux-hardware.org/?probe=ce94bc6589) | May 18, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [311799f80a](https://linux-hardware.org/?probe=311799f80a) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | Desktop     | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | E2100N                      | Desktop     | [cce0e87f11](https://linux-hardware.org/?probe=cce0e87f11) | May 17, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [98f104037a](https://linux-hardware.org/?probe=98f104037a) | May 15, 2023 |
| AZW           | MINI S                      | Desktop     | [72c9908514](https://linux-hardware.org/?probe=72c9908514) | May 14, 2023 |
| AZW           | MINI S                      | Desktop     | [788d932e58](https://linux-hardware.org/?probe=788d932e58) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [42db835c47](https://linux-hardware.org/?probe=42db835c47) | May 14, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [3f4eafaf9c](https://linux-hardware.org/?probe=3f4eafaf9c) | May 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [42d9eb5bf8](https://linux-hardware.org/?probe=42d9eb5bf8) | May 13, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [7c946d461d](https://linux-hardware.org/?probe=7c946d461d) | May 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [a0fcafbf70](https://linux-hardware.org/?probe=a0fcafbf70) | May 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [4d7467c0bc](https://linux-hardware.org/?probe=4d7467c0bc) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | Notebook    | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [99c9764b7e](https://linux-hardware.org/?probe=99c9764b7e) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a70e02af94](https://linux-hardware.org/?probe=a70e02af94) | May 09, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| AZW           | SEi                         | Notebook    | [4cd6ab54ba](https://linux-hardware.org/?probe=4cd6ab54ba) | May 08, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7d861acbd6](https://linux-hardware.org/?probe=7d861acbd6) | May 07, 2023 |
| Medion        | TJ4125                      | Desktop     | [583b49089e](https://linux-hardware.org/?probe=583b49089e) | May 07, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [eb82f6baa1](https://linux-hardware.org/?probe=eb82f6baa1) | May 06, 2023 |
| Medion        | E6214                       | Notebook    | [869c63244c](https://linux-hardware.org/?probe=869c63244c) | May 06, 2023 |
| Medion        | E6214                       | Notebook    | [64eeb6e165](https://linux-hardware.org/?probe=64eeb6e165) | May 06, 2023 |
| Medion        | TJ4125                      | Desktop     | [2255946fa5](https://linux-hardware.org/?probe=2255946fa5) | May 05, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c8347acd5d](https://linux-hardware.org/?probe=c8347acd5d) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd7043408f](https://linux-hardware.org/?probe=fd7043408f) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [3c7546e88a](https://linux-hardware.org/?probe=3c7546e88a) | May 02, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ae586408c4](https://linux-hardware.org/?probe=ae586408c4) | May 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Studio 1555                 | Notebook    | [4f9f0dc9bf](https://linux-hardware.org/?probe=4f9f0dc9bf) | May 01, 2023 |
| Lenovo        | 4068AGJ                     | Notebook    | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| HP            | Compaq 15                   | Notebook    | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [897fc61b8c](https://linux-hardware.org/?probe=897fc61b8c) | Apr 30, 2023 |
| ASUSTek       | P7Q57-M DO                  | Desktop     | [4f502dcb59](https://linux-hardware.org/?probe=4f502dcb59) | Apr 30, 2023 |
| Medion        | E6214                       | Notebook    | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | Notebook    | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [16279b3c8b](https://linux-hardware.org/?probe=16279b3c8b) | Apr 30, 2023 |
| Medion        | TJ4125                      | Desktop     | [ad46974b2a](https://linux-hardware.org/?probe=ad46974b2a) | Apr 29, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7c8260664a](https://linux-hardware.org/?probe=7c8260664a) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | Notebook    | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [73e11e9235](https://linux-hardware.org/?probe=73e11e9235) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | Notebook    | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| Medion        | TJ4125                      | Desktop     | [8f319cff50](https://linux-hardware.org/?probe=8f319cff50) | Apr 28, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [831cd8fa39](https://linux-hardware.org/?probe=831cd8fa39) | Apr 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [6503ed5a4c](https://linux-hardware.org/?probe=6503ed5a4c) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | Notebook    | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [60d207eb63](https://linux-hardware.org/?probe=60d207eb63) | Apr 27, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [df6b1e8e17](https://linux-hardware.org/?probe=df6b1e8e17) | Apr 26, 2023 |
| GPU Compan... | GWTN156-5                   | Notebook    | [a22605adc9](https://linux-hardware.org/?probe=a22605adc9) | Apr 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a3a13c5cb1](https://linux-hardware.org/?probe=a3a13c5cb1) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [1d5b5dcfc7](https://linux-hardware.org/?probe=1d5b5dcfc7) | Apr 24, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5827cd2604](https://linux-hardware.org/?probe=5827cd2604) | Apr 23, 2023 |
| Medion        | TJ4125                      | Desktop     | [faa241e4bc](https://linux-hardware.org/?probe=faa241e4bc) | Apr 23, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [93a6cb1a8a](https://linux-hardware.org/?probe=93a6cb1a8a) | Apr 22, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [3f172b49f2](https://linux-hardware.org/?probe=3f172b49f2) | Apr 21, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | Notebook    | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Medion        | E6214                       | Notebook    | [ff06e74c6d](https://linux-hardware.org/?probe=ff06e74c6d) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| Medion        | E6214                       | Notebook    | [ab33cd63b8](https://linux-hardware.org/?probe=ab33cd63b8) | Apr 16, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [c4b35f2a05](https://linux-hardware.org/?probe=c4b35f2a05) | Apr 16, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [12cb955c6f](https://linux-hardware.org/?probe=12cb955c6f) | Apr 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [3bb10a5574](https://linux-hardware.org/?probe=3bb10a5574) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d6f8675bc9](https://linux-hardware.org/?probe=d6f8675bc9) | Apr 11, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [4b50be64da](https://linux-hardware.org/?probe=4b50be64da) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d041ee40cc](https://linux-hardware.org/?probe=d041ee40cc) | Apr 11, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [2c83dbd3ef](https://linux-hardware.org/?probe=2c83dbd3ef) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1e9eaed8b](https://linux-hardware.org/?probe=d1e9eaed8b) | Apr 08, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [82a96ca347](https://linux-hardware.org/?probe=82a96ca347) | Apr 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [05aaab32ca](https://linux-hardware.org/?probe=05aaab32ca) | Apr 08, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| Dell          | Precision M4800             | Notebook    | [9283851416](https://linux-hardware.org/?probe=9283851416) | Apr 06, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [3ebdd0188a](https://linux-hardware.org/?probe=3ebdd0188a) | Apr 05, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4552b7c999](https://linux-hardware.org/?probe=4552b7c999) | Apr 01, 2023 |
| Medion        | E6214                       | Notebook    | [79f326e572](https://linux-hardware.org/?probe=79f326e572) | Apr 01, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [b627db43dd](https://linux-hardware.org/?probe=b627db43dd) | Apr 01, 2023 |
| Medion        | E6214                       | Notebook    | [5766389c97](https://linux-hardware.org/?probe=5766389c97) | Apr 01, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [b50f27ad05](https://linux-hardware.org/?probe=b50f27ad05) | Mar 31, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Dell          | 00F82W A02                  | Desktop     | [8bf22304e0](https://linux-hardware.org/?probe=8bf22304e0) | Mar 31, 2023 |
| Medion        | E6214                       | Notebook    | [298e2f9c69](https://linux-hardware.org/?probe=298e2f9c69) | Mar 31, 2023 |
| HP            | Pavilion dm4                | Notebook    | [b7f2f9e2ab](https://linux-hardware.org/?probe=b7f2f9e2ab) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [b53d1202dc](https://linux-hardware.org/?probe=b53d1202dc) | Mar 28, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [dd71be113d](https://linux-hardware.org/?probe=dd71be113d) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [e5cef530ff](https://linux-hardware.org/?probe=e5cef530ff) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [6ac9c53a7e](https://linux-hardware.org/?probe=6ac9c53a7e) | Mar 26, 2023 |
| Medion        | E6214                       | Notebook    | [8ff346be04](https://linux-hardware.org/?probe=8ff346be04) | Mar 26, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8690ae647e](https://linux-hardware.org/?probe=8690ae647e) | Mar 26, 2023 |
| Haier         | S15                         | Notebook    | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [ce4febfe16](https://linux-hardware.org/?probe=ce4febfe16) | Mar 25, 2023 |
| Haier         | S15                         | Notebook    | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| Star Labs     | StarBook                    | Notebook    | [b3957ad08f](https://linux-hardware.org/?probe=b3957ad08f) | Mar 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [7165e2c0d0](https://linux-hardware.org/?probe=7165e2c0d0) | Mar 21, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [79104099a5](https://linux-hardware.org/?probe=79104099a5) | Mar 20, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [fb5c67c585](https://linux-hardware.org/?probe=fb5c67c585) | Mar 19, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [7051e25dc0](https://linux-hardware.org/?probe=7051e25dc0) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| ASRock        | B365M Pro4                  | Desktop     | [e237668eb2](https://linux-hardware.org/?probe=e237668eb2) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [29f50579db](https://linux-hardware.org/?probe=29f50579db) | Mar 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bf2b5490ba](https://linux-hardware.org/?probe=bf2b5490ba) | Mar 15, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [b410a4c017](https://linux-hardware.org/?probe=b410a4c017) | Mar 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | Notebook    | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| Gigabyte      | Z87X-OC Force-CF            | Desktop     | [17deac9c67](https://linux-hardware.org/?probe=17deac9c67) | Mar 12, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [22dd14abae](https://linux-hardware.org/?probe=22dd14abae) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [93875c7518](https://linux-hardware.org/?probe=93875c7518) | Mar 09, 2023 |
| MSI           | 970A-G46                    | Desktop     | [8c3d20fa95](https://linux-hardware.org/?probe=8c3d20fa95) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z61m 9450HAG       | Notebook    | [5aa66edd35](https://linux-hardware.org/?probe=5aa66edd35) | Mar 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [fddb284e37](https://linux-hardware.org/?probe=fddb284e37) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| HIPER         | WORKBOOK                    | Notebook    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
| Supermicro    | X10SAE                      | Server      | [fff44d7132](https://linux-hardware.org/?probe=fff44d7132) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| Supermicro    | X10SAE                      | Server      | [b968ea6172](https://linux-hardware.org/?probe=b968ea6172) | Feb 25, 2023 |
| HP            | 2000                        | Notebook    | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | Desktop     | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| itel Mobil... | SPIRIT 2                    | Notebook    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Dell          | 0MF24N A03                  | Desktop     | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2d26056501](https://linux-hardware.org/?probe=2d26056501) | Feb 13, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [861c0d497e](https://linux-hardware.org/?probe=861c0d497e) | Feb 12, 2023 |
| Compaq        | 420                         | Notebook    | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| Star Labs     | StarBook                    | Notebook    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| HP            | 843C                        | Desktop     | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Dell          | Precision M4800             | Notebook    | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | Notebook    | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | Notebook    | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Intel         | H61M-DS2V                   | Desktop     | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| Compaq        | 420                         | Notebook    | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | Desktop     | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | Desktop     | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | Notebook    | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Fujitsu       | M2010                       | Notebook    | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Google        | Candy                       | Notebook    | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | Notebook    | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | Desktop     | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Google        | Ultima                      | Notebook    | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | Notebook    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | Notebook    | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [5a75bbfc48](https://linux-hardware.org/?probe=5a75bbfc48) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | 8299                        | Desktop     | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | Notebook    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | Notebook    | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | Notebook    | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Dell          | 0N826N A03                  | Desktop     | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [8d633d6712](https://linux-hardware.org/?probe=8d633d6712) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [d23c74b1f2](https://linux-hardware.org/?probe=d23c74b1f2) | Nov 05, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| HP            | 8299                        | Desktop     | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| Dell          | XPS L701X                   | Notebook    | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| HP            | 8299                        | Desktop     | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| AZW           | MINI S                      | Desktop     | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ff09bb4e1](https://linux-hardware.org/?probe=8ff09bb4e1) | Sep 22, 2022 |
| Gateway       | DX4870                      | Desktop     | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Medion        | P15648                      | Notebook    | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | Notebook    | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| ASRock        | G41M-S3                     | Desktop     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
| Dell          | 0FJ030                      | Desktop     | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | Desktop     | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | Desktop     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| ASUSTek       | P5B                         | Desktop     | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9ea782b1d2](https://linux-hardware.org/?probe=9ea782b1d2) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [2a3b9ad6cf](https://linux-hardware.org/?probe=2a3b9ad6cf) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Acer          | AOD270                      | Notebook    | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [eb751efc1f](https://linux-hardware.org/?probe=eb751efc1f) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| ASUSTek       | 901                         | Notebook    | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Acer          | EG43M                       | Desktop     | [28b4dd5236](https://linux-hardware.org/?probe=28b4dd5236) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | Notebook    | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | Notebook    | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [346857be22](https://linux-hardware.org/?probe=346857be22) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| ASUSTek       | P4P800                      | Desktop     | [0cb6a89491](https://linux-hardware.org/?probe=0cb6a89491) | Mar 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [b3507722e3](https://linux-hardware.org/?probe=b3507722e3) | Mar 19, 2022 |
| Acer          | TravelMate 420              | Notebook    | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | Notebook    | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | Notebook    | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [3533cd70af](https://linux-hardware.org/?probe=3533cd70af) | Feb 26, 2022 |
| Dell          | 0HR330                      | Desktop     | [e587783731](https://linux-hardware.org/?probe=e587783731) | Feb 26, 2022 |
| HP            | 0AA8h                       | Desktop     | [21de71cf71](https://linux-hardware.org/?probe=21de71cf71) | Feb 25, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | Notebook    | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0731118682](https://linux-hardware.org/?probe=0731118682) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5026ea812a](https://linux-hardware.org/?probe=5026ea812a) | Feb 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| Dell          | 0Y2K8N A01                  | Desktop     | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
| ASUSTek       | 901                         | Notebook    | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| EVGA          | 131-HE-E095                 | Desktop     | [6d45d47131](https://linux-hardware.org/?probe=6d45d47131) | Jan 31, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [00cd805015](https://linux-hardware.org/?probe=00cd805015) | Jan 23, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [be068c5a3a](https://linux-hardware.org/?probe=be068c5a3a) | Jan 21, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [a988797ac9](https://linux-hardware.org/?probe=a988797ac9) | Jan 16, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [311d594372](https://linux-hardware.org/?probe=311d594372) | Jan 13, 2022 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [4fac8e2cb1](https://linux-hardware.org/?probe=4fac8e2cb1) | Jan 11, 2022 |
| Wistron       | ProLiant ML110 G5           | Server      | [ea55ac1aab](https://linux-hardware.org/?probe=ea55ac1aab) | Jan 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [33457cde11](https://linux-hardware.org/?probe=33457cde11) | Jan 09, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | Notebook    | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [1d55cceee4](https://linux-hardware.org/?probe=1d55cceee4) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [43b421ad06](https://linux-hardware.org/?probe=43b421ad06) | Jan 08, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [bfcf287c09](https://linux-hardware.org/?probe=bfcf287c09) | Jan 08, 2022 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | Notebook    | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [1ba0b3e854](https://linux-hardware.org/?probe=1ba0b3e854) | Jan 01, 2022 |
| Unknown       | K7VM2                       | Desktop     | [06f13210ad](https://linux-hardware.org/?probe=06f13210ad) | Dec 29, 2021 |
| Unknown       | K7VM2                       | Desktop     | [be785b672c](https://linux-hardware.org/?probe=be785b672c) | Dec 29, 2021 |
| Wistron       | ProLiant ML110 G5           | Server      | [8526295a2f](https://linux-hardware.org/?probe=8526295a2f) | Dec 27, 2021 |
| Advent        | Monza T100                  | Notebook    | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | Notebook    | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | Notebook    | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [fb02077f16](https://linux-hardware.org/?probe=fb02077f16) | Dec 14, 2021 |
| HP            | 2AE3                        | Desktop     | [18efa559b9](https://linux-hardware.org/?probe=18efa559b9) | Dec 14, 2021 |
| ECS           | G41T-M7                     | Desktop     | [5a8641a9aa](https://linux-hardware.org/?probe=5a8641a9aa) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | Notebook    | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | Notebook    | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Acer          | RS880M05                    | Desktop     | [2ce9c25975](https://linux-hardware.org/?probe=2ce9c25975) | Nov 25, 2021 |
| NEC Comput... | GA-8I945PM                  | Desktop     | [3d3711b8cc](https://linux-hardware.org/?probe=3d3711b8cc) | Nov 22, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b4b709eb1b](https://linux-hardware.org/?probe=b4b709eb1b) | Nov 18, 2021 |
| Samsung       | 305U1A                      | Notebook    | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [18236d5a16](https://linux-hardware.org/?probe=18236d5a16) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | Notebook    | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Intel         | H61                         | Desktop     | [51f383b050](https://linux-hardware.org/?probe=51f383b050) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | Notebook    | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | Notebook    | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| HP            | 843C                        | Desktop     | [e7df8fecdd](https://linux-hardware.org/?probe=e7df8fecdd) | Oct 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [f0983027ee](https://linux-hardware.org/?probe=f0983027ee) | Oct 26, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [48187accde](https://linux-hardware.org/?probe=48187accde) | Oct 21, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [f1fcb9d1db](https://linux-hardware.org/?probe=f1fcb9d1db) | Oct 17, 2021 |
| EVGA          | 132-BL-E758 Tylersburg      | Desktop     | [a1820d8f0c](https://linux-hardware.org/?probe=a1820d8f0c) | Oct 17, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | Notebook    | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [940a27249a](https://linux-hardware.org/?probe=940a27249a) | Oct 12, 2021 |
| HP            | 520                         | Notebook    | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | Notebook    | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| HUAWEI        | MateBook HZ-W19             | Tablet      | [904decfd32](https://linux-hardware.org/?probe=904decfd32) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | Notebook    | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [012056e32d](https://linux-hardware.org/?probe=012056e32d) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Biostar       | G41D3C                      | Desktop     | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | Notebook    | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9c0ade7c9c](https://linux-hardware.org/?probe=9c0ade7c9c) | Sep 20, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [9eec34a3f2](https://linux-hardware.org/?probe=9eec34a3f2) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | Notebook    | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [623cb095f2](https://linux-hardware.org/?probe=623cb095f2) | Sep 12, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [3c335b37fa](https://linux-hardware.org/?probe=3c335b37fa) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | Notebook    | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| ASUSTek       | UN62                        | Desktop     | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | Notebook    | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| ASUSTek       | P5VD2-VM                    | Desktop     | [305d566f57](https://linux-hardware.org/?probe=305d566f57) | Sep 07, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [09cbb5b50e](https://linux-hardware.org/?probe=09cbb5b50e) | Sep 03, 2021 |
| Gigabyte      | M52LT-D3P                   | Desktop     | [949b2062ea](https://linux-hardware.org/?probe=949b2062ea) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | Notebook    | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | Notebook    | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | Notebook    | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | Notebook    | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | Notebook    | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | Notebook    | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [c34caa75e2](https://linux-hardware.org/?probe=c34caa75e2) | Aug 23, 2021 |
| ASUSTek       | M51Sn                       | Notebook    | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [2700c74bd9](https://linux-hardware.org/?probe=2700c74bd9) | Aug 21, 2021 |
| MSI           | MS-7142                     | Desktop     | [18ae0c1bb3](https://linux-hardware.org/?probe=18ae0c1bb3) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | Notebook    | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| HP            | 0AA8h                       | Desktop     | [d9a8fd3722](https://linux-hardware.org/?probe=d9a8fd3722) | Aug 15, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [0e9fd81caf](https://linux-hardware.org/?probe=0e9fd81caf) | Aug 11, 2021 |
| ASUSTek       | A7N8X-LA                    | Desktop     | [f14c99bbce](https://linux-hardware.org/?probe=f14c99bbce) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [cff87306ab](https://linux-hardware.org/?probe=cff87306ab) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | Desktop     | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [05c1703574](https://linux-hardware.org/?probe=05c1703574) | Aug 03, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [faf304d157](https://linux-hardware.org/?probe=faf304d157) | Aug 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| OEM           | 45CMX/45GMX/45CMX-K         | Desktop     | [65d8eb687e](https://linux-hardware.org/?probe=65d8eb687e) | Jul 30, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [33a6186148](https://linux-hardware.org/?probe=33a6186148) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | Notebook    | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | Notebook    | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| Intel         | BTC-T37                     | Desktop     | [bb5051b598](https://linux-hardware.org/?probe=bb5051b598) | Jul 27, 2021 |
| ASRock        | FM2A85X Extreme4-M          | Desktop     | [aa0030f094](https://linux-hardware.org/?probe=aa0030f094) | Jul 26, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [763cb39ac0](https://linux-hardware.org/?probe=763cb39ac0) | Jul 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [39037104b7](https://linux-hardware.org/?probe=39037104b7) | Jul 17, 2021 |
| Dell          | XPS M1330                   | Notebook    | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| Dell          | 08HPGT A01                  | Desktop     | [64d562d6ef](https://linux-hardware.org/?probe=64d562d6ef) | Jul 16, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| ASUSTek       | PRIME A320M-K 2021-06-11    | Desktop     | [a82245240b](https://linux-hardware.org/?probe=a82245240b) | Jul 15, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [3007b813c6](https://linux-hardware.org/?probe=3007b813c6) | Jul 13, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [5cfa1dcb4f](https://linux-hardware.org/?probe=5cfa1dcb4f) | Jul 12, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | Notebook    | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | Notebook    | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | Notebook    | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | Notebook    | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | Notebook    | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| MSI           | H81M-E34                    | Desktop     | [14c2f8a49d](https://linux-hardware.org/?probe=14c2f8a49d) | Jul 05, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [9d356e787a](https://linux-hardware.org/?probe=9d356e787a) | Jul 01, 2021 |
| Samsung       | R59/R60/R61                 | Notebook    | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | Notebook    | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | Notebook    | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | Notebook    | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | 0A98h                       | Desktop     | [40990f73a5](https://linux-hardware.org/?probe=40990f73a5) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | Notebook    | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | 0AA8h                       | Desktop     | [43103b39a5](https://linux-hardware.org/?probe=43103b39a5) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | Notebook    | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | 0AA8h                       | Desktop     | [9154911bc9](https://linux-hardware.org/?probe=9154911bc9) | Jun 13, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | Notebook    | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [699d10613e](https://linux-hardware.org/?probe=699d10613e) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | Notebook    | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | Notebook    | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | Notebook    | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| Unknown       | Unknown                     | Desktop     | [3e408e9ead](https://linux-hardware.org/?probe=3e408e9ead) | May 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [39b2780acf](https://linux-hardware.org/?probe=39b2780acf) | May 31, 2021 |
| Dell          | 0HY9JP A01                  | Desktop     | [3f6ddbd81d](https://linux-hardware.org/?probe=3f6ddbd81d) | May 30, 2021 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [7d2b37e6e1](https://linux-hardware.org/?probe=7d2b37e6e1) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [adc801308b](https://linux-hardware.org/?probe=adc801308b) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| ASRock        | G41M-S3                     | Desktop     | [47f6c3e962](https://linux-hardware.org/?probe=47f6c3e962) | May 28, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [cd3697bd15](https://linux-hardware.org/?probe=cd3697bd15) | May 25, 2021 |
| MSI           | Gamila/Giovani/Neon seri... | Desktop     | [7c520b0d6e](https://linux-hardware.org/?probe=7c520b0d6e) | May 25, 2021 |
| ASUSTek       | X555UJ                      | Notebook    | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d981b2ed](https://linux-hardware.org/?probe=55d981b2ed) | May 23, 2021 |
| Intel         | H61                         | Desktop     | [1954634de4](https://linux-hardware.org/?probe=1954634de4) | May 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Foxconn       | 945 7MC Series              | Desktop     | [f4634ec470](https://linux-hardware.org/?probe=f4634ec470) | May 17, 2021 |
| Dell          | 0FM586 A00                  | Desktop     | [8a955d2c5a](https://linux-hardware.org/?probe=8a955d2c5a) | May 16, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [a502e8842e](https://linux-hardware.org/?probe=a502e8842e) | May 12, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | Notebook    | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [3c0a297ede](https://linux-hardware.org/?probe=3c0a297ede) | May 08, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | Notebook    | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [0fd87c485e](https://linux-hardware.org/?probe=0fd87c485e) | May 07, 2021 |
| HP            | 530                         | Notebook    | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | Notebook    | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | Notebook    | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [46b0bab7d8](https://linux-hardware.org/?probe=46b0bab7d8) | Apr 27, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | Notebook    | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | Notebook    | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [3076a5bae3](https://linux-hardware.org/?probe=3076a5bae3) | Apr 24, 2021 |
| Unknown       | Phitronics N68C-M           | Desktop     | [d3a56832d9](https://linux-hardware.org/?probe=d3a56832d9) | Apr 23, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | Notebook    | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [761a9ce0e9](https://linux-hardware.org/?probe=761a9ce0e9) | Apr 21, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [2813977a91](https://linux-hardware.org/?probe=2813977a91) | Apr 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d6c3daff43](https://linux-hardware.org/?probe=d6c3daff43) | Apr 19, 2021 |
| HP            | Pavilion dv7                | Notebook    | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| ASUSTek       | V-P7H55E                    | Desktop     | [fb3b69b074](https://linux-hardware.org/?probe=fb3b69b074) | Apr 18, 2021 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [47deff8a39](https://linux-hardware.org/?probe=47deff8a39) | Apr 17, 2021 |
| Toshiba       | NI 1403                     | Notebook    | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | Notebook    | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [16d03cb92f](https://linux-hardware.org/?probe=16d03cb92f) | Apr 12, 2021 |
| Dell          | 0KP561                      | Desktop     | [3579bff9c4](https://linux-hardware.org/?probe=3579bff9c4) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | Desktop     | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| Pegatron      | 2ADC                        | Desktop     | [e4bfddb8d9](https://linux-hardware.org/?probe=e4bfddb8d9) | Apr 04, 2021 |
| MSI           | MS-7267                     | Desktop     | [d16e8a4364](https://linux-hardware.org/?probe=d16e8a4364) | Apr 03, 2021 |
| Supermicro    | X8DT3                       | Server      | [f645c4227c](https://linux-hardware.org/?probe=f645c4227c) | Apr 02, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | Notebook    | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | Notebook    | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | Notebook    | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | Notebook    | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| Intel         | H61                         | Desktop     | [d7c3f87e52](https://linux-hardware.org/?probe=d7c3f87e52) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [a9c3672597](https://linux-hardware.org/?probe=a9c3672597) | Mar 25, 2021 |
| HP            | Unknown                     | Notebook    | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| MSI           | MS-6785                     | Desktop     | [303c1ac636](https://linux-hardware.org/?probe=303c1ac636) | Mar 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | Notebook    | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | Notebook    | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| ECS           | A740GM-M                    | Desktop     | [442aa41981](https://linux-hardware.org/?probe=442aa41981) | Mar 08, 2021 |
| ASUSTek       | P7F-M                       | Desktop     | [a8d2e4fa56](https://linux-hardware.org/?probe=a8d2e4fa56) | Mar 07, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | Notebook    | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [ea6fbcd94e](https://linux-hardware.org/?probe=ea6fbcd94e) | Mar 02, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | Notebook    | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Acer          | EG43LMK                     | Desktop     | [249967a21a](https://linux-hardware.org/?probe=249967a21a) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | Notebook    | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [527b138b70](https://linux-hardware.org/?probe=527b138b70) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | Notebook    | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | Notebook    | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Acer          | EG43LMK                     | Desktop     | [1c1fdf43c0](https://linux-hardware.org/?probe=1c1fdf43c0) | Feb 17, 2021 |
| Google        | Gnawty                      | Notebook    | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | Notebook    | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| MSI           | MS-7267                     | Desktop     | [6bf114a22f](https://linux-hardware.org/?probe=6bf114a22f) | Feb 15, 2021 |
| MSI           | MS-7267                     | Desktop     | [78e4d03c89](https://linux-hardware.org/?probe=78e4d03c89) | Feb 15, 2021 |
| Dell          | Latitude E6520              | Notebook    | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [4b2befb0d2](https://linux-hardware.org/?probe=4b2befb0d2) | Feb 14, 2021 |
| Notebook      | WID2010                     | Notebook    | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | Notebook    | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c8e67a7d41](https://linux-hardware.org/?probe=c8e67a7d41) | Feb 07, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [6e605fd64d](https://linux-hardware.org/?probe=6e605fd64d) | Feb 06, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [ec667e7b35](https://linux-hardware.org/?probe=ec667e7b35) | Feb 05, 2021 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [b71d20e5de](https://linux-hardware.org/?probe=b71d20e5de) | Feb 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [3adb6d9dc1](https://linux-hardware.org/?probe=3adb6d9dc1) | Feb 05, 2021 |
| HP            | EliteBook 820 G3            | Notebook    | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [05c23c4247](https://linux-hardware.org/?probe=05c23c4247) | Feb 02, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [8c45cfc073](https://linux-hardware.org/?probe=8c45cfc073) | Feb 02, 2021 |
| ASUSTek       | P5E3 Deluxe                 | Desktop     | [47324765ec](https://linux-hardware.org/?probe=47324765ec) | Feb 02, 2021 |
| Unknown       | Unknown                     | Desktop     | [94d77e9dd0](https://linux-hardware.org/?probe=94d77e9dd0) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | Notebook    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9761a3446c](https://linux-hardware.org/?probe=9761a3446c) | Jan 30, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9c930ede42](https://linux-hardware.org/?probe=9c930ede42) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | Notebook    | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5bc80f882](https://linux-hardware.org/?probe=e5bc80f882) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d04b2d493f](https://linux-hardware.org/?probe=d04b2d493f) | Jan 20, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [08ac15e868](https://linux-hardware.org/?probe=08ac15e868) | Jan 15, 2021 |
| Matsushita... | CF-19CHB23BE                | Notebook    | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Dell          | 0TT708 A01                  | Desktop     | [d0da7a44f7](https://linux-hardware.org/?probe=d0da7a44f7) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Alienware     | 06G6JW A00                  | Desktop     | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | Notebook    | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| LMDE 4 | 389       | 48.93%  |
| LMDE 5 | 387       | 48.68%  |
| LMDE 3 | 14        | 1.76%   |
| LMDE 2 | 5         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| LMDE | 790       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.10.0-21-amd64        | 73        | 8.31%   |
| 5.10.0-12-amd64        | 56        | 6.38%   |
| 4.19.0-8-amd64         | 45        | 5.13%   |
| 4.19.0-18-amd64        | 45        | 5.13%   |
| 4.19.0-17-amd64        | 41        | 4.67%   |
| 4.19.0-16-amd64        | 40        | 4.56%   |
| 5.10.0-23-amd64        | 37        | 4.21%   |
| 5.10.0-19-amd64        | 37        | 4.21%   |
| 4.19.0-14-amd64        | 31        | 3.53%   |
| 5.10.0-14-amd64        | 30        | 3.42%   |
| 4.19.0-9-amd64         | 30        | 3.42%   |
| 4.19.0-13-amd64        | 30        | 3.42%   |
| 5.10.0-20-amd64        | 29        | 3.3%    |
| 5.10.0-13-amd64        | 27        | 3.08%   |
| 5.10.0-18-amd64        | 25        | 2.85%   |
| 5.10.0-17-amd64        | 21        | 2.39%   |
| 4.19.0-10-amd64        | 20        | 2.28%   |
| 5.10.0-15-amd64        | 19        | 2.16%   |
| 4.19.0-12-amd64        | 19        | 2.16%   |
| 4.19.0-8-686           | 17        | 1.94%   |
| 4.19.0-17-686          | 17        | 1.94%   |
| 5.10.0-16-amd64        | 14        | 1.59%   |
| 4.19.0-16-686          | 14        | 1.59%   |
| 5.10.0-22-amd64        | 13        | 1.48%   |
| 4.19.0-18-686          | 12        | 1.37%   |
| 4.19.0-11-amd64        | 11        | 1.25%   |
| 4.19.0-13-686          | 9         | 1.03%   |
| 4.9.0-8-amd64          | 8         | 0.91%   |
| 5.10.0-13-686          | 6         | 0.68%   |
| 4.19.0-14-686          | 6         | 0.68%   |
| 4.19.0-12-686          | 6         | 0.68%   |
| 4.19.0-19-686          | 5         | 0.57%   |
| 5.18.0-0.bpo.1-amd64   | 4         | 0.46%   |
| 5.16.0-0.bpo.4-amd64   | 4         | 0.46%   |
| 3.16.0-4-amd64         | 4         | 0.46%   |
| 5.4.0-0.bpo.4-amd64    | 3         | 0.34%   |
| 5.19.0-0.deb11.2-amd64 | 3         | 0.34%   |
| 4.19.0-20-amd64        | 3         | 0.34%   |
| 6.1.0-0.deb11.7-amd64  | 2         | 0.23%   |
| 6.1.0-0.deb11.6-amd64  | 2         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19.0  | 373       | 46.34%  |
| 5.10.0  | 371       | 46.09%  |
| 4.9.0   | 12        | 1.49%   |
| 6.1.0   | 7         | 0.87%   |
| 5.18.0  | 6         | 0.75%   |
| 3.16.0  | 5         | 0.62%   |
| 5.16.0  | 4         | 0.5%    |
| 5.6.0   | 3         | 0.37%   |
| 5.4.0   | 3         | 0.37%   |
| 5.19.0  | 3         | 0.37%   |
| 5.8.0   | 2         | 0.25%   |
| 5.15.59 | 2         | 0.25%   |
| 5.15.0  | 2         | 0.25%   |
| 6.1.11  | 1         | 0.12%   |
| 6.0.2   | 1         | 0.12%   |
| 6.0.0   | 1         | 0.12%   |
| 5.9.12  | 1         | 0.12%   |
| 5.9.0   | 1         | 0.12%   |
| 5.4.44  | 1         | 0.12%   |
| 5.19.10 | 1         | 0.12%   |
| 5.15.78 | 1         | 0.12%   |
| 5.15.70 | 1         | 0.12%   |
| 5.15.64 | 1         | 0.12%   |
| 5.15.56 | 1         | 0.12%   |
| 4.17.0  | 1         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.19    | 373       | 46.51%  |
| 5.10    | 371       | 46.26%  |
| 4.9     | 12        | 1.5%    |
| 6.1     | 8         | 1%      |
| 5.18    | 6         | 0.75%   |
| 5.15    | 5         | 0.62%   |
| 3.16    | 5         | 0.62%   |
| 5.4     | 4         | 0.5%    |
| 5.19    | 4         | 0.5%    |
| 5.16    | 4         | 0.5%    |
| 5.6     | 3         | 0.37%   |
| 6.0     | 2         | 0.25%   |
| 5.9     | 2         | 0.25%   |
| 5.8     | 2         | 0.25%   |
| 4.17    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 687       | 86.96%  |
| i686   | 103       | 13.04%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 687       | 85.98%  |
| Cinnamon   | 71        | 8.89%   |
| MATE       | 16        | 2%      |
| Unknown    | 9         | 1.13%   |
| XFCE       | 4         | 0.5%    |
| GNOME      | 3         | 0.38%   |
| LXDE       | 2         | 0.25%   |
| KDE        | 2         | 0.25%   |
| Trinity    | 1         | 0.13%   |
| LXQt       | 1         | 0.13%   |
| KDE5       | 1         | 0.13%   |
| i3         | 1         | 0.13%   |
| awesome    | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 790       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 577       | 72.67%  |
| LightDM | 175       | 22.04%  |
| TDM     | 32        | 4.03%   |
| MDM     | 5         | 0.63%   |
| SDDM    | 2         | 0.25%   |
| GDM     | 2         | 0.25%   |
| GDM3    | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 244       | 30.77%  |
| de_DE   | 95        | 11.98%  |
| pt_BR   | 67        | 8.45%   |
| ru_RU   | 54        | 6.81%   |
| en_GB   | 37        | 4.67%   |
| fr_FR   | 34        | 4.29%   |
| pl_PL   | 28        | 3.53%   |
| it_IT   | 25        | 3.15%   |
| es_ES   | 20        | 2.52%   |
| Unknown | 17        | 2.14%   |
| en_CA   | 13        | 1.64%   |
| es_AR   | 11        | 1.39%   |
| en_AU   | 11        | 1.39%   |
| es_MX   | 10        | 1.26%   |
| el_GR   | 7         | 0.88%   |
| sv_SE   | 6         | 0.76%   |
| de_CH   | 6         | 0.76%   |
| cs_CZ   | 6         | 0.76%   |
| pt_PT   | 5         | 0.63%   |
| de_AT   | 5         | 0.63%   |
| tr_TR   | 4         | 0.5%    |
| nl_BE   | 4         | 0.5%    |
| ja_JP   | 4         | 0.5%    |
| fr_CA   | 4         | 0.5%    |
| en_ZA   | 4         | 0.5%    |
| sk_SK   | 3         | 0.38%   |
| ru_UA   | 3         | 0.38%   |
| nl_NL   | 3         | 0.38%   |
| hu_HU   | 3         | 0.38%   |
| fr_BE   | 3         | 0.38%   |
| es_CL   | 3         | 0.38%   |
| en_NZ   | 3         | 0.38%   |
| en_IN   | 3         | 0.38%   |
| da_DK   | 3         | 0.38%   |
| bg_BG   | 3         | 0.38%   |
| zh_CN   | 2         | 0.25%   |
| unm_US  | 2         | 0.25%   |
| uk_UA   | 2         | 0.25%   |
| ko_KR   | 2         | 0.25%   |
| it_CH   | 2         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 443       | 55.79%  |
| EFI  | 351       | 44.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 734       | 92.68%  |
| Btrfs   | 19        | 2.4%    |
| Tmpfs   | 13        | 1.64%   |
| Overlay | 13        | 1.64%   |
| Unknown | 8         | 1.01%   |
| Xfs     | 3         | 0.38%   |
| Ext3    | 1         | 0.13%   |
| Aufs    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 573       | 72.17%  |
| GPT     | 144       | 18.14%  |
| MBR     | 77        | 9.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 736       | 92.81%  |
| Yes       | 57        | 7.19%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 714       | 90.27%  |
| Yes       | 77        | 9.73%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 128       | 16.2%   |
| ASUSTek Computer               | 108       | 13.67%  |
| Dell                           | 95        | 12.03%  |
| Lenovo                         | 89        | 11.27%  |
| Acer                           | 63        | 7.97%   |
| Gigabyte Technology            | 45        | 5.7%    |
| MSI                            | 36        | 4.56%   |
| Toshiba                        | 20        | 2.53%   |
| ASRock                         | 20        | 2.53%   |
| Apple                          | 16        | 2.03%   |
| Intel                          | 15        | 1.9%    |
| Samsung Electronics            | 11        | 1.39%   |
| Unknown                        | 11        | 1.39%   |
| Sony                           | 10        | 1.27%   |
| Fujitsu Siemens                | 7         | 0.89%   |
| Fujitsu                        | 7         | 0.89%   |
| Medion                         | 6         | 0.76%   |
| Positivo                       | 5         | 0.63%   |
| LG Electronics                 | 5         | 0.63%   |
| Google                         | 5         | 0.63%   |
| Pegatron                       | 4         | 0.51%   |
| Packard Bell                   | 4         | 0.51%   |
| Foxconn                        | 4         | 0.51%   |
| ECS                            | 4         | 0.51%   |
| AZW                            | 4         | 0.51%   |
| Gateway                        | 3         | 0.38%   |
| Alienware                      | 3         | 0.38%   |
| TUXEDO                         | 2         | 0.25%   |
| Supermicro                     | 2         | 0.25%   |
| Star Labs                      | 2         | 0.25%   |
| Semp Toshiba                   | 2         | 0.25%   |
| OEM                            | 2         | 0.25%   |
| Matsushita Electric Industrial | 2         | 0.25%   |
| HUAWEI                         | 2         | 0.25%   |
| EVGA                           | 2         | 0.25%   |
| eMachines                      | 2         | 0.25%   |
| Compaq                         | 2         | 0.25%   |
| Biostar                        | 2         | 0.25%   |
| Wortmann AG                    | 1         | 0.13%   |
| Wistron                        | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 18        | 2.28%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 4         | 0.51%   |
| HP Pavilion dv6                             | 4         | 0.51%   |
| HP Notebook                                 | 4         | 0.51%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.38%   |
| Dell OptiPlex 780                           | 3         | 0.38%   |
| Dell Latitude E6400                         | 3         | 0.38%   |
| ASUS All Series                             | 3         | 0.38%   |
| Acer Aspire E1-570G                         | 3         | 0.38%   |
| Acer Aspire 5930                            | 3         | 0.38%   |
| Acer AOD270                                 | 3         | 0.38%   |
| Star Labs StarBook                          | 2         | 0.25%   |
| MSI MS-7C52                                 | 2         | 0.25%   |
| MSI MS-7B79                                 | 2         | 0.25%   |
| MSI MS-7A38                                 | 2         | 0.25%   |
| LG A530-T.BE76P1                            | 2         | 0.25%   |
| Lenovo V145-15AST 81MT                      | 2         | 0.25%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 2         | 0.25%   |
| Lenovo G500 20236                           | 2         | 0.25%   |
| Lenovo G50-45 80E3                          | 2         | 0.25%   |
| Intel B75                                   | 2         | 0.25%   |
| HP Pavilion Notebook                        | 2         | 0.25%   |
| HP Pavilion dv7                             | 2         | 0.25%   |
| HP Pavilion Desktop 590-p0xxx               | 2         | 0.25%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.25%   |
| HP Laptop 15-dw3xxx                         | 2         | 0.25%   |
| HP Laptop 15-da0xxx                         | 2         | 0.25%   |
| HP Laptop 15-bw0xx                          | 2         | 0.25%   |
| HP Laptop 14-df0xxx                         | 2         | 0.25%   |
| HP EliteBook 8540w                          | 2         | 0.25%   |
| HP EliteBook 820 G3                         | 2         | 0.25%   |
| HP Compaq Presario CQ71                     | 2         | 0.25%   |
| HP Compaq Presario CQ60                     | 2         | 0.25%   |
| HP 290 G2 MT Business PC                    | 2         | 0.25%   |
| HP 255 G7 Notebook PC                       | 2         | 0.25%   |
| HP 250 G8 Notebook PC                       | 2         | 0.25%   |
| HP 250 G7 Notebook PC                       | 2         | 0.25%   |
| HP 14                                       | 2         | 0.25%   |
| Gigabyte X570 AORUS ULTRA                   | 2         | 0.25%   |
| Gigabyte B450M DS3H                         | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 50        | 6.33%   |
| Lenovo ThinkPad         | 36        | 4.56%   |
| Dell Latitude           | 25        | 3.16%   |
| HP Pavilion             | 23        | 2.91%   |
| Dell Inspiron           | 23        | 2.91%   |
| Lenovo IdeaPad          | 20        | 2.53%   |
| HP Laptop               | 20        | 2.53%   |
| Unknown                 | 18        | 2.28%   |
| Toshiba Satellite       | 16        | 2.03%   |
| HP Compaq               | 15        | 1.9%    |
| Dell OptiPlex           | 15        | 1.9%    |
| Dell Precision          | 14        | 1.77%   |
| HP EliteBook            | 13        | 1.65%   |
| ASUS PRIME              | 10        | 1.27%   |
| ASUS ROG                | 8         | 1.01%   |
| HP ProBook              | 7         | 0.89%   |
| ASUS VivoBook           | 7         | 0.89%   |
| HP 250                  | 5         | 0.63%   |
| Dell Vostro             | 5         | 0.63%   |
| Lenovo ThinkCentre      | 4         | 0.51%   |
| HP Notebook             | 4         | 0.51%   |
| Gigabyte X570           | 4         | 0.51%   |
| Dell XPS                | 4         | 0.51%   |
| Samsung RV411           | 3         | 0.38%   |
| Lenovo Yoga             | 3         | 0.38%   |
| HP ZBook                | 3         | 0.38%   |
| HP Presario             | 3         | 0.38%   |
| HP 255                  | 3         | 0.38%   |
| Gigabyte B450M          | 3         | 0.38%   |
| Gigabyte B450           | 3         | 0.38%   |
| Fujitsu Siemens ESPRIMO | 3         | 0.38%   |
| Fujitsu LIFEBOOK        | 3         | 0.38%   |
| ASUS All                | 3         | 0.38%   |
| Acer Veriton            | 3         | 0.38%   |
| Acer AOD270             | 3         | 0.38%   |
| Toshiba PORTEGE         | 2         | 0.25%   |
| Star Labs StarBook      | 2         | 0.25%   |
| Packard Bell EasyNote   | 2         | 0.25%   |
| MSI MS-7C52             | 2         | 0.25%   |
| MSI MS-7B79             | 2         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 73        | 9.24%   |
| 2018    | 67        | 8.48%   |
| 2010    | 58        | 7.34%   |
| 2009    | 58        | 7.34%   |
| 2013    | 52        | 6.58%   |
| 2011    | 52        | 6.58%   |
| 2021    | 45        | 5.7%    |
| 2019    | 45        | 5.7%    |
| 2007    | 44        | 5.57%   |
| 2008    | 43        | 5.44%   |
| 2020    | 42        | 5.32%   |
| 2014    | 41        | 5.19%   |
| 2017    | 38        | 4.81%   |
| 2016    | 35        | 4.43%   |
| 2015    | 29        | 3.67%   |
| 2006    | 26        | 3.29%   |
| 2022    | 18        | 2.28%   |
| 2005    | 11        | 1.39%   |
| 2003    | 5         | 0.63%   |
| 2023    | 4         | 0.51%   |
| 2004    | 2         | 0.25%   |
| 2002    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 472       | 59.75%  |
| Desktop     | 281       | 35.57%  |
| All in one  | 12        | 1.52%   |
| Convertible | 11        | 1.39%   |
| Tablet      | 6         | 0.76%   |
| Mini pc     | 4         | 0.51%   |
| Server      | 4         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 747       | 94.08%  |
| Enabled  | 47        | 5.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 782       | 98.99%  |
| Yes  | 8         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 192       | 24.12%  |
| 4.01-8.0        | 164       | 20.6%   |
| 16.01-24.0      | 123       | 15.45%  |
| 8.01-16.0       | 120       | 15.08%  |
| 2.01-3.0        | 64        | 8.04%   |
| 1.01-2.0        | 55        | 6.91%   |
| 32.01-64.0      | 45        | 5.65%   |
| 0.51-1.0        | 16        | 2.01%   |
| 64.01-256.0     | 10        | 1.26%   |
| 24.01-32.0      | 6         | 0.75%   |
| More than 256.0 | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 375       | 44.22%  |
| 2.01-3.0   | 212       | 25%     |
| 0.51-1.0   | 101       | 11.91%  |
| 3.01-4.0   | 86        | 10.14%  |
| 4.01-8.0   | 57        | 6.72%   |
| 8.01-16.0  | 9         | 1.06%   |
| 0.01-0.5   | 3         | 0.35%   |
| 32.01-64.0 | 2         | 0.24%   |
| 16.01-24.0 | 2         | 0.24%   |
| 24.01-32.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 503       | 62.25%  |
| 2      | 197       | 24.38%  |
| 3      | 51        | 6.31%   |
| 4      | 27        | 3.34%   |
| 5      | 12        | 1.49%   |
| 6      | 6         | 0.74%   |
| 0      | 6         | 0.74%   |
| 7      | 5         | 0.62%   |
| 8      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 420       | 52.57%  |
| Yes       | 379       | 47.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 709       | 89.75%  |
| No        | 81        | 10.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 618       | 77.64%  |
| No        | 178       | 22.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 402       | 50.69%  |
| Yes       | 391       | 49.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 123       | 15.53%  |
| Germany      | 105       | 13.26%  |
| Brazil       | 70        | 8.84%   |
| Russia       | 61        | 7.7%    |
| France       | 37        | 4.67%   |
| Italy        | 36        | 4.55%   |
| UK           | 30        | 3.79%   |
| Poland       | 28        | 3.54%   |
| Canada       | 24        | 3.03%   |
| Spain        | 23        | 2.9%    |
| Australia    | 15        | 1.89%   |
| Ukraine      | 13        | 1.64%   |
| Netherlands  | 13        | 1.64%   |
| Mexico       | 13        | 1.64%   |
| Argentina    | 11        | 1.39%   |
| Sweden       | 9         | 1.14%   |
| Bulgaria     | 9         | 1.14%   |
| Greece       | 8         | 1.01%   |
| Belgium      | 8         | 1.01%   |
| Austria      | 8         | 1.01%   |
| Turkey       | 7         | 0.88%   |
| Switzerland  | 7         | 0.88%   |
| Portugal     | 7         | 0.88%   |
| Belarus      | 7         | 0.88%   |
| South Africa | 5         | 0.63%   |
| Romania      | 5         | 0.63%   |
| Indonesia    | 5         | 0.63%   |
| India        | 5         | 0.63%   |
| Czechia      | 5         | 0.63%   |
| Chile        | 5         | 0.63%   |
| Philippines  | 4         | 0.51%   |
| Japan        | 4         | 0.51%   |
| Hungary      | 4         | 0.51%   |
| Finland      | 4         | 0.51%   |
| Ecuador      | 4         | 0.51%   |
| Venezuela    | 3         | 0.38%   |
| New Zealand  | 3         | 0.38%   |
| Denmark      | 3         | 0.38%   |
| China        | 3         | 0.38%   |
| Bolivia      | 3         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 12        | 1.45%   |
| Berlin               | 9         | 1.08%   |
| St Petersburg        | 7         | 0.84%   |
| Sao Paulo            | 6         | 0.72%   |
| Rio de Janeiro       | 6         | 0.72%   |
| Frankfurt am Main    | 6         | 0.72%   |
| Paris                | 5         | 0.6%    |
| Munich               | 5         | 0.6%    |
| Montreal             | 5         | 0.6%    |
| Milan                | 5         | 0.6%    |
| Madrid               | 5         | 0.6%    |
| Krakow               | 5         | 0.6%    |
| Hamburg              | 5         | 0.6%    |
| Athens               | 5         | 0.6%    |
| Wroclaw              | 4         | 0.48%   |
| Warsaw               | 4         | 0.48%   |
| Sofia                | 4         | 0.48%   |
| Rome                 | 4         | 0.48%   |
| Poznan               | 4         | 0.48%   |
| Perth                | 4         | 0.48%   |
| Miami                | 4         | 0.48%   |
| Guayaquil            | 4         | 0.48%   |
| Delligsen            | 4         | 0.48%   |
| Wohlen               | 3         | 0.36%   |
| Voronezh             | 3         | 0.36%   |
| Toronto              | 3         | 0.36%   |
| Seville              | 3         | 0.36%   |
| Rho                  | 3         | 0.36%   |
| Parma                | 3         | 0.36%   |
| Oxford               | 3         | 0.36%   |
| New York             | 3         | 0.36%   |
| Melbourne            | 3         | 0.36%   |
| Manama               | 3         | 0.36%   |
| London               | 3         | 0.36%   |
| Lisbon               | 3         | 0.36%   |
| Krefeld              | 3         | 0.36%   |
| Glasgow              | 3         | 0.36%   |
| Freiburg im Breisgau | 3         | 0.36%   |
| Florianópolis       | 3         | 0.36%   |
| Duisburg             | 3         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 192       | 281    | 17.36%  |
| Samsung Electronics | 156       | 213    | 14.1%   |
| Seagate             | 155       | 224    | 14.01%  |
| Kingston            | 61        | 78     | 5.52%   |
| Toshiba             | 60        | 71     | 5.42%   |
| Unknown             | 50        | 68     | 4.52%   |
| SanDisk             | 47        | 65     | 4.25%   |
| Hitachi             | 46        | 50     | 4.16%   |
| Crucial             | 37        | 45     | 3.35%   |
| Intel               | 22        | 24     | 1.99%   |
| SK hynix            | 21        | 24     | 1.9%    |
| A-DATA Technology   | 17        | 19     | 1.54%   |
| China               | 16        | 17     | 1.45%   |
| HGST                | 15        | 21     | 1.36%   |
| Phison              | 13        | 17     | 1.18%   |
| Micron Technology   | 12        | 13     | 1.08%   |
| Fujitsu             | 12        | 12     | 1.08%   |
| Patriot             | 8         | 9      | 0.72%   |
| Intenso             | 8         | 9      | 0.72%   |
| Apple               | 8         | 13     | 0.72%   |
| PNY                 | 7         | 8      | 0.63%   |
| Transcend           | 6         | 10     | 0.54%   |
| KingSpec            | 6         | 7      | 0.54%   |
| GOODRAM             | 6         | 6      | 0.54%   |
| Silicon Motion      | 5         | 6      | 0.45%   |
| Gigabyte Technology | 5         | 8      | 0.45%   |
| Unknown             | 5         | 6      | 0.45%   |
| Team                | 4         | 5      | 0.36%   |
| SPCC                | 4         | 4      | 0.36%   |
| OCZ                 | 4         | 6      | 0.36%   |
| ADATA Technology    | 4         | 4      | 0.36%   |
| Maxtor              | 3         | 5      | 0.27%   |
| KingDian            | 3         | 4      | 0.27%   |
| Hewlett-Packard     | 3         | 4      | 0.27%   |
| Emtec               | 3         | 3      | 0.27%   |
| TCSUNBOW            | 2         | 2      | 0.18%   |
| Star Drive          | 2         | 2      | 0.18%   |
| SABRENT             | 2         | 2      | 0.18%   |
| Plextor             | 2         | 3      | 0.18%   |
| Phison Electronics  | 2         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 11        | 0.91%   |
| Kingston SA400S37240G 240GB SSD                     | 11        | 0.91%   |
| Kingston SA400S37120G 120GB SSD                     | 11        | 0.91%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 0.83%   |
| Samsung SSD 850 EVO 500GB                           | 10        | 0.83%   |
| Kingston SA400S37480G 480GB SSD                     | 10        | 0.83%   |
| Seagate ST500LT012-1DG142 500GB                     | 9         | 0.75%   |
| Unknown SD/MMC/MS PRO 250GB                         | 8         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 0.66%   |
| Unknown MMC Card  32GB                              | 7         | 0.58%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 0.58%   |
| Unknown MMC Card  64GB                              | 6         | 0.5%    |
| Unknown MMC Card  128GB                             | 6         | 0.5%    |
| Seagate ST500DM002-1BD142 500GB                     | 6         | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 5         | 0.41%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 5         | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 5         | 0.41%   |
| Unknown MMC Card  7GB                               | 5         | 0.41%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.41%   |
| Toshiba DT01ACA100 1TB                              | 5         | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.41%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.41%   |
| Samsung SSD 860 EVO 1TB                             | 5         | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 0.41%   |
| Crucial CT240BX500SSD1 240GB                        | 5         | 0.41%   |
| Unknown                                             | 5         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4         | 0.33%   |
| Toshiba HDWD110 1TB                                 | 4         | 0.33%   |
| Seagate ST9250315AS 250GB                           | 4         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                      | 4         | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB                      | 4         | 0.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 0.33%   |
| Seagate Expansion 1TB                               | 4         | 0.33%   |
| Samsung SSD 980 PRO 1TB                             | 4         | 0.33%   |
| Samsung SSD 970 EVO 500GB                           | 4         | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 4         | 0.33%   |
| Samsung NVMe SSD Drive 500GB                        | 4         | 0.33%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 4         | 0.33%   |
| Kingston SV300S37A240G 240GB SSD                    | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 166       | 249    | 33.2%   |
| Seagate             | 154       | 221    | 30.8%   |
| Toshiba             | 49        | 56     | 9.8%    |
| Hitachi             | 46        | 50     | 9.2%    |
| Samsung Electronics | 36        | 47     | 7.2%    |
| HGST                | 15        | 21     | 3%      |
| Fujitsu             | 12        | 12     | 2.4%    |
| Unknown             | 8         | 8      | 1.6%    |
| Maxtor              | 3         | 5      | 0.6%    |
| Intenso             | 2         | 2      | 0.4%    |
| IBM/Hitachi         | 2         | 2      | 0.4%    |
| KESU                | 1         | 2      | 0.2%    |
| HPE                 | 1         | 4      | 0.2%    |
| ExcelStor           | 1         | 1      | 0.2%    |
| DAS                 | 1         | 4      | 0.2%    |
| ASMT                | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |
| Apple               | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 83        | 105    | 20.65%  |
| Kingston            | 52        | 68     | 12.94%  |
| Crucial             | 36        | 44     | 8.96%   |
| SanDisk             | 29        | 42     | 7.21%   |
| WDC                 | 18        | 19     | 4.48%   |
| A-DATA Technology   | 17        | 19     | 4.23%   |
| China               | 14        | 15     | 3.48%   |
| Intel               | 12        | 12     | 2.99%   |
| Toshiba             | 9         | 13     | 2.24%   |
| Patriot             | 8         | 9      | 1.99%   |
| PNY                 | 7         | 8      | 1.74%   |
| Micron Technology   | 7         | 8      | 1.74%   |
| Transcend           | 6         | 10     | 1.49%   |
| KingSpec            | 6         | 7      | 1.49%   |
| GOODRAM             | 6         | 6      | 1.49%   |
| Apple               | 6         | 6      | 1.49%   |
| SK hynix            | 5         | 6      | 1.24%   |
| Intenso             | 5         | 6      | 1.24%   |
| Gigabyte Technology | 5         | 8      | 1.24%   |
| Team                | 4         | 5      | 1%      |
| OCZ                 | 4         | 6      | 1%      |
| SPCC                | 3         | 3      | 0.75%   |
| KingDian            | 3         | 4      | 0.75%   |
| Hewlett-Packard     | 3         | 4      | 0.75%   |
| Unknown             | 3         | 4      | 0.75%   |
| Unknown             | 2         | 2      | 0.5%    |
| TCSUNBOW            | 2         | 2      | 0.5%    |
| Plextor             | 2         | 3      | 0.5%    |
| Netac               | 2         | 2      | 0.5%    |
| FORESEE             | 2         | 4      | 0.5%    |
| Emtec               | 2         | 2      | 0.5%    |
| CT500MX5            | 2         | 3      | 0.5%    |
| Corsair             | 2         | 2      | 0.5%    |
| WINTEC              | 1         | 1      | 0.25%   |
| Vaseky              | 1         | 1      | 0.25%   |
| USB30               | 1         | 2      | 0.25%   |
| TakeMS              | 1         | 1      | 0.25%   |
| T-FORCE             | 1         | 1      | 0.25%   |
| SSD PHIS            | 1         | 1      | 0.25%   |
| Smartbuy            | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 435       | 687    | 43.72%  |
| SSD     | 350       | 499    | 35.18%  |
| NVMe    | 146       | 195    | 14.67%  |
| MMC     | 42        | 57     | 4.22%   |
| Unknown | 22        | 27     | 2.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 671       | 1139   | 73.98%  |
| NVMe | 144       | 193    | 15.88%  |
| SAS  | 50        | 76     | 5.51%   |
| MMC  | 42        | 57     | 4.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 543       | 814    | 68.13%  |
| 0.51-1.0   | 180       | 261    | 22.58%  |
| 1.01-2.0   | 40        | 54     | 5.02%   |
| 4.01-10.0  | 13        | 17     | 1.63%   |
| 3.01-4.0   | 11        | 20     | 1.38%   |
| 2.01-3.0   | 10        | 20     | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 284       | 35.24%  |
| 251-500        | 190       | 23.57%  |
| 501-1000       | 91        | 11.29%  |
| 51-100         | 67        | 8.31%   |
| 1001-2000      | 64        | 7.94%   |
| More than 3000 | 37        | 4.59%   |
| 21-50          | 30        | 3.72%   |
| 2001-3000      | 21        | 2.61%   |
| 1-20           | 21        | 2.61%   |
| Unknown        | 1         | 0.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 347       | 41.16%  |
| 21-50          | 181       | 21.47%  |
| 51-100         | 95        | 11.27%  |
| 101-250        | 92        | 10.91%  |
| 251-500        | 44        | 5.22%   |
| 501-1000       | 37        | 4.39%   |
| 1001-2000      | 20        | 2.37%   |
| More than 3000 | 13        | 1.54%   |
| 2001-3000      | 13        | 1.54%   |
| Unknown        | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 2.22%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.22%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 2.22%   |
| WDC WD3200BEVT-26A23T0 320GB          | 1         | 1      | 2.22%   |
| WDC WD2500BEVT-24A23T0 250GB          | 1         | 1      | 2.22%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 2.22%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 2.22%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 2.22%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 2.22%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 2.22%   |
| Toshiba HDWD110 1TB                   | 1         | 1      | 2.22%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 2.22%   |
| Seagate STM9120817AS 120GB            | 1         | 1      | 2.22%   |
| Seagate ST98823AS 80GB                | 1         | 1      | 2.22%   |
| Seagate ST9640423AS 640GB             | 1         | 1      | 2.22%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 2.22%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 2.22%   |
| Seagate ST9120821AS 120GB             | 1         | 1      | 2.22%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 2.22%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 2.22%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 2.22%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 2.22%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 2.22%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 980 PRO 1TB   | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 2.22%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 2.22%   |
| Samsung Electronics SP2004C 200GB     | 1         | 1      | 2.22%   |
| Samsung Electronics MP0402H 40GB      | 1         | 1      | 2.22%   |
| Samsung Electronics HM500JI 500GB     | 1         | 1      | 2.22%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 2.22%   |
| Samsung Electronics HD153WI 1TB       | 1         | 1      | 2.22%   |
| Samsung Electronics HD103SJ 1TB       | 1         | 1      | 2.22%   |
| Phison ES 512GB                       | 1         | 1      | 2.22%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 2.22%   |
| Intenso SSD 256GB                     | 1         | 1      | 2.22%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 2.22%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 27.27%  |
| Samsung Electronics | 10        | 11     | 22.73%  |
| WDC                 | 6         | 7      | 13.64%  |
| Toshiba             | 3         | 3      | 6.82%   |
| Intel               | 2         | 2      | 4.55%   |
| Hitachi             | 2         | 2      | 4.55%   |
| WINTEC              | 1         | 1      | 2.27%   |
| SK hynix            | 1         | 1      | 2.27%   |
| SanDisk             | 1         | 1      | 2.27%   |
| Phison              | 1         | 1      | 2.27%   |
| Kingston            | 1         | 1      | 2.27%   |
| Intenso             | 1         | 1      | 2.27%   |
| HGST                | 1         | 1      | 2.27%   |
| Fujitsu             | 1         | 1      | 2.27%   |
| Crucial             | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 40%     |
| WDC                 | 6         | 7      | 20%     |
| Samsung Electronics | 6         | 6      | 20%     |
| Toshiba             | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| HGST                | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 31     | 67.44%  |
| SSD  | 10        | 10     | 23.26%  |
| NVMe | 4         | 5      | 9.3%    |

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
| Detected | 603       | 1089   | 72.3%   |
| Works    | 188       | 330    | 22.54%  |
| Malfunc  | 43        | 46     | 5.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 568       | 60.55%  |
| AMD                              | 136       | 14.5%   |
| Samsung Electronics              | 49        | 5.22%   |
| SanDisk                          | 26        | 2.77%   |
| Nvidia                           | 23        | 2.45%   |
| Phison Electronics               | 18        | 1.92%   |
| SK hynix                         | 16        | 1.71%   |
| ASMedia Technology               | 16        | 1.71%   |
| JMicron Technology               | 13        | 1.39%   |
| VIA Technologies                 | 9         | 0.96%   |
| Marvell Technology Group         | 9         | 0.96%   |
| Kingston Technology Company      | 9         | 0.96%   |
| Silicon Integrated Systems [SiS] | 8         | 0.85%   |
| Silicon Motion                   | 6         | 0.64%   |
| Micron Technology                | 5         | 0.53%   |
| Broadcom / LSI                   | 5         | 0.53%   |
| ADATA Technology                 | 4         | 0.43%   |
| Toshiba America Info Systems     | 3         | 0.32%   |
| Micron/Crucial Technology        | 3         | 0.32%   |
| KIOXIA                           | 3         | 0.32%   |
| Union Memory (Shenzhen)          | 2         | 0.21%   |
| Silicon Image                    | 2         | 0.21%   |
| LSI Logic / Symbios Logic        | 2         | 0.21%   |
| Solid State Storage Technology   | 1         | 0.11%   |
| Integrated Technology Express    | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 85        | 7.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 42        | 3.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 41        | 3.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 34        | 2.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 31        | 2.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 29        | 2.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 27        | 2.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 24        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 2.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 22        | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 22        | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 20        | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 19        | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 17        | 1.48%   |
| AMD 400 Series Chipset SATA Controller                                           | 17        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 16        | 1.4%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 16        | 1.4%    |
| Samsung NVMe SSD Controller 980                                                  | 15        | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 15        | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 15        | 1.31%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 15        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 13        | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 12        | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 11        | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 9         | 0.79%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 8         | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 0.7%    |
| Phison PS5013 E13 NVMe Controller                                                | 8         | 0.7%    |
| Phison E12 NVMe Controller                                                       | 8         | 0.7%    |
| Nvidia MCP61 SATA Controller                                                     | 8         | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                               | 8         | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 0.7%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 8         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 573       | 57.76%  |
| IDE  | 197       | 19.86%  |
| NVMe | 146       | 14.72%  |
| RAID | 68        | 6.85%   |
| SAS  | 5         | 0.5%    |
| SCSI | 3         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 616       | 77.97%  |
| AMD    | 174       | 22.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                | 10        | 1.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 1.14%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 8         | 1.01%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 8         | 1.01%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.76%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 6         | 0.76%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 0.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.63%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 5         | 0.63%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 5         | 0.63%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz          | 5         | 0.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.63%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 0.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 0.63%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 5         | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 0.51%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.51%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 4         | 0.51%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.51%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 4         | 0.51%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 4         | 0.51%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 4         | 0.51%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.51%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 0.51%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.51%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.51%   |
| Intel Pentium M processor 1.73GHz             | 3         | 0.38%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 3         | 0.38%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 3         | 0.38%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 3         | 0.38%   |
| Intel Pentium D CPU 2.80GHz                   | 3         | 0.38%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 131       | 16.56%  |
| Intel Core i7           | 101       | 12.77%  |
| Intel Core i3           | 73        | 9.23%   |
| Intel Core 2 Duo        | 60        | 7.59%   |
| Intel Celeron           | 48        | 6.07%   |
| Other                   | 37        | 4.68%   |
| AMD Ryzen 5             | 35        | 4.42%   |
| Intel Atom              | 32        | 4.05%   |
| Intel Pentium           | 29        | 3.67%   |
| AMD Ryzen 7             | 27        | 3.41%   |
| Intel Xeon              | 21        | 2.65%   |
| Intel Core 2            | 13        | 1.64%   |
| Intel Pentium Dual-Core | 12        | 1.52%   |
| Intel Core 2 Quad       | 12        | 1.52%   |
| Intel Pentium Dual      | 10        | 1.26%   |
| Intel Genuine           | 10        | 1.26%   |
| AMD Ryzen 3             | 10        | 1.26%   |
| AMD A4                  | 9         | 1.14%   |
| AMD FX                  | 8         | 1.01%   |
| Intel Pentium M         | 7         | 0.88%   |
| Intel Pentium D         | 7         | 0.88%   |
| AMD Athlon 64 X2        | 7         | 0.88%   |
| AMD Sempron             | 6         | 0.76%   |
| Intel Pentium 4         | 5         | 0.63%   |
| AMD E1                  | 5         | 0.63%   |
| AMD Athlon              | 5         | 0.63%   |
| AMD Ryzen 9             | 4         | 0.51%   |
| AMD Phenom II X4        | 4         | 0.51%   |
| AMD E2                  | 4         | 0.51%   |
| AMD A8                  | 4         | 0.51%   |
| AMD A10                 | 4         | 0.51%   |
| Intel Pentium Silver    | 3         | 0.38%   |
| Intel Pentium Gold      | 3         | 0.38%   |
| Intel Core i9           | 3         | 0.38%   |
| Intel Core Duo          | 3         | 0.38%   |
| AMD Turion 64 X2 Mobile | 3         | 0.38%   |
| AMD Phenom II X6        | 3         | 0.38%   |
| AMD E                   | 3         | 0.38%   |
| AMD Athlon XP           | 3         | 0.38%   |
| AMD Athlon II X2        | 3         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 414       | 52.27%  |
| 4      | 228       | 28.79%  |
| 1      | 57        | 7.2%    |
| 8      | 39        | 4.92%   |
| 6      | 38        | 4.8%    |
| 16     | 6         | 0.76%   |
| 12     | 5         | 0.63%   |
| 10     | 3         | 0.38%   |
| 3      | 2         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 780       | 98.73%  |
| 2      | 10        | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 439       | 55.5%   |
| 1      | 352       | 44.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 738       | 93.42%  |
| 32-bit         | 52        | 6.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 57        | 7.11%   |
| Unknown    | 54        | 6.73%   |
| 0x206a7    | 53        | 6.61%   |
| 0x1067a    | 47        | 5.86%   |
| 0x306c3    | 34        | 4.24%   |
| 0x6fd      | 25        | 3.12%   |
| 0x406e3    | 23        | 2.87%   |
| 0x40651    | 22        | 2.74%   |
| 0x806c1    | 20        | 2.49%   |
| 0x20655    | 20        | 2.49%   |
| 0x806ea    | 16        | 2%      |
| 0x08108109 | 15        | 1.87%   |
| 0x106c2    | 14        | 1.75%   |
| 0x806ec    | 13        | 1.62%   |
| 0x806e9    | 12        | 1.5%    |
| 0x506e3    | 12        | 1.5%    |
| 0x30661    | 12        | 1.5%    |
| 0x06006705 | 12        | 1.5%    |
| 0x6f6      | 11        | 1.37%   |
| 0x010000c8 | 11        | 1.37%   |
| 0x406c4    | 10        | 1.25%   |
| 0x106e5    | 10        | 1.25%   |
| 0x10676    | 10        | 1.25%   |
| 0x906ea    | 9         | 1.12%   |
| 0x6fb      | 9         | 1.12%   |
| 0x08608103 | 9         | 1.12%   |
| 0x906ed    | 8         | 1%      |
| 0x706a8    | 8         | 1%      |
| 0x30678    | 8         | 1%      |
| 0x20652    | 8         | 1%      |
| 0x0800820d | 8         | 1%      |
| 0x6ec      | 7         | 0.87%   |
| 0x306d4    | 7         | 0.87%   |
| 0x08701021 | 7         | 0.87%   |
| 0x06001119 | 7         | 0.87%   |
| 0x906c0    | 6         | 0.75%   |
| 0x806eb    | 6         | 0.75%   |
| 0x706e5    | 6         | 0.75%   |
| 0x6e8      | 6         | 0.75%   |
| 0x0a50000d | 6         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 75        | 9.47%   |
| Penryn           | 66        | 8.33%   |
| SandyBridge      | 62        | 7.83%   |
| IvyBridge        | 59        | 7.45%   |
| Haswell          | 59        | 7.45%   |
| Core             | 53        | 6.69%   |
| Skylake          | 35        | 4.42%   |
| Westmere         | 32        | 4.04%   |
| Bonnell          | 30        | 3.79%   |
| Zen+             | 28        | 3.54%   |
| Silvermont       | 24        | 3.03%   |
| TigerLake        | 22        | 2.78%   |
| P6               | 20        | 2.53%   |
| K10              | 20        | 2.53%   |
| K8 Hammer        | 18        | 2.27%   |
| Unknown          | 18        | 2.27%   |
| Zen 3            | 16        | 2.02%   |
| Zen              | 16        | 2.02%   |
| NetBurst         | 15        | 1.89%   |
| Excavator        | 15        | 1.89%   |
| Zen 2            | 13        | 1.64%   |
| Piledriver       | 13        | 1.64%   |
| Nehalem          | 13        | 1.64%   |
| Goldmont plus    | 13        | 1.64%   |
| Broadwell        | 9         | 1.14%   |
| Icelake          | 7         | 0.88%   |
| Tremont          | 6         | 0.76%   |
| Puma             | 6         | 0.76%   |
| Bobcat           | 6         | 0.76%   |
| CometLake        | 5         | 0.63%   |
| Jaguar           | 4         | 0.51%   |
| Goldmont         | 4         | 0.51%   |
| K6               | 3         | 0.38%   |
| Bulldozer        | 3         | 0.38%   |
| K8 & K10 hybrid  | 2         | 0.25%   |
| K10 Llano        | 1         | 0.13%   |
| Alderlake Hybrid | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 441       | 49.33%  |
| Nvidia                           | 242       | 27.07%  |
| AMD                              | 195       | 21.81%  |
| VIA Technologies                 | 5         | 0.56%   |
| Silicon Integrated Systems [SiS] | 5         | 0.56%   |
| Matrox Electronics Systems       | 4         | 0.45%   |
| S3 Graphics                      | 1         | 0.11%   |
| ASPEED Technology                | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 5.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 3.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 2.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 2.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 21        | 2.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 2.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.71%   |
| Intel UHD Graphics 620                                                                   | 15        | 1.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 1.49%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 1.39%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 1.28%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 12        | 1.28%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 11        | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.17%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 10        | 1.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 1.07%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.07%   |
| Nvidia GT218 [GeForce 210]                                                               | 9         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 0.96%   |
| Intel HD Graphics 620                                                                    | 9         | 0.96%   |
| AMD Lucienne                                                                             | 9         | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 0.85%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 0.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 0.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 0.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 0.64%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.64%   |
| Intel HD Graphics 530                                                                    | 6         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 348       | 43.88%  |
| 1 x Nvidia      | 167       | 21.06%  |
| 1 x AMD         | 157       | 19.8%   |
| Intel + Nvidia  | 65        | 8.2%    |
| Intel + AMD     | 18        | 2.27%   |
| 2 x AMD         | 12        | 1.51%   |
| AMD + Nvidia    | 8         | 1.01%   |
| 1 x VIA         | 5         | 0.63%   |
| 1 x SiS         | 5         | 0.63%   |
| 1 x Matrox      | 4         | 0.5%    |
| Other           | 1         | 0.13%   |
| 2 x Nvidia      | 1         | 0.13%   |
| 1 x S3 Graphics | 1         | 0.13%   |
| 1 x ASPEED      | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 641       | 80.33%  |
| Proprietary | 89        | 11.15%  |
| Unknown     | 68        | 8.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 448       | 56.07%  |
| 0.01-0.5   | 125       | 15.64%  |
| 1.01-2.0   | 94        | 11.76%  |
| 0.51-1.0   | 64        | 8.01%   |
| 3.01-4.0   | 34        | 4.26%   |
| 7.01-8.0   | 16        | 2%      |
| 5.01-6.0   | 10        | 1.25%   |
| 2.01-3.0   | 5         | 0.63%   |
| 8.01-16.0  | 2         | 0.25%   |
| 16.01-24.0 | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 105       | 13.44%  |
| AU Optronics            | 91        | 11.65%  |
| LG Display              | 76        | 9.73%   |
| BOE                     | 60        | 7.68%   |
| Chimei Innolux          | 58        | 7.43%   |
| Goldstar                | 41        | 5.25%   |
| Dell                    | 30        | 3.84%   |
| Acer                    | 30        | 3.84%   |
| Chi Mei Optoelectronics | 21        | 2.69%   |
| BenQ                    | 19        | 2.43%   |
| Hewlett-Packard         | 18        | 2.3%    |
| Apple                   | 17        | 2.18%   |
| Lenovo                  | 16        | 2.05%   |
| Philips                 | 15        | 1.92%   |
| AOC                     | 15        | 1.92%   |
| LG Philips              | 13        | 1.66%   |
| Ancor Communications    | 13        | 1.66%   |
| Unknown                 | 12        | 1.54%   |
| Sony                    | 10        | 1.28%   |
| HannStar                | 10        | 1.28%   |
| InfoVision              | 9         | 1.15%   |
| Sharp                   | 5         | 0.64%   |
| PANDA                   | 5         | 0.64%   |
| Iiyama                  | 5         | 0.64%   |
| ViewSonic               | 4         | 0.51%   |
| Sceptre Tech            | 4         | 0.51%   |
| Fujitsu Siemens         | 4         | 0.51%   |
| CPT                     | 4         | 0.51%   |
| Quanta Display          | 3         | 0.38%   |
| NEC Computers           | 3         | 0.38%   |
| Eizo                    | 3         | 0.38%   |
| DENON                   | 3         | 0.38%   |
| ___                     | 2         | 0.26%   |
| Toshiba                 | 2         | 0.26%   |
| SLD                     | 2         | 0.26%   |
| Panasonic               | 2         | 0.26%   |
| Medion                  | 2         | 0.26%   |
| LG Electronics          | 2         | 0.26%   |
| Insignia                | 2         | 0.26%   |
| IBM                     | 2         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 7         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.63%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 4         | 0.5%    |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 4         | 0.5%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.5%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.5%    |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 3         | 0.38%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.38%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 3         | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.38%   |
| Unknown LCD Monitor SAMSUNG                                              | 2         | 0.25%   |
| Sony LCD Monitor TV 3840x1080                                            | 2         | 0.25%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 2         | 0.25%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch           | 2         | 0.25%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch      | 2         | 0.25%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.25%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch    | 2         | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 2         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 287       | 37.71%  |
| 1366x768 (WXGA)    | 186       | 24.44%  |
| 1280x1024 (SXGA)   | 44        | 5.78%   |
| 1280x800 (WXGA)    | 37        | 4.86%   |
| 1600x900 (HD+)     | 35        | 4.6%    |
| 1680x1050 (WSXGA+) | 25        | 3.29%   |
| 3840x2160 (4K)     | 22        | 2.89%   |
| 1440x900 (WXGA+)   | 22        | 2.89%   |
| 1920x1200 (WUXGA)  | 18        | 2.37%   |
| 1024x600           | 17        | 2.23%   |
| 1360x768           | 10        | 1.31%   |
| 2560x1440 (QHD)    | 9         | 1.18%   |
| 3440x1440          | 7         | 0.92%   |
| 1024x768 (XGA)     | 7         | 0.92%   |
| Unknown            | 7         | 0.92%   |
| 2560x1080          | 6         | 0.79%   |
| 3840x1080          | 4         | 0.53%   |
| 1280x768           | 3         | 0.39%   |
| 2880x1800          | 2         | 0.26%   |
| 2560x1600          | 2         | 0.26%   |
| 1600x1200          | 2         | 0.26%   |
| 7680x2160          | 1         | 0.13%   |
| 4480x1440          | 1         | 0.13%   |
| 4240x1440          | 1         | 0.13%   |
| 2736x1824          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 1920x540           | 1         | 0.13%   |
| 1400x1050          | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |
| 1024x576           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 238       | 30.63%  |
| 13      | 64        | 8.24%   |
| Unknown | 55        | 7.08%   |
| 14      | 53        | 6.82%   |
| 17      | 47        | 6.05%   |
| 24      | 45        | 5.79%   |
| 23      | 37        | 4.76%   |
| 21      | 37        | 4.76%   |
| 19      | 28        | 3.6%    |
| 27      | 26        | 3.35%   |
| 18      | 24        | 3.09%   |
| 10      | 17        | 2.19%   |
| 20      | 16        | 2.06%   |
| 12      | 16        | 2.06%   |
| 11      | 13        | 1.67%   |
| 22      | 11        | 1.42%   |
| 34      | 9         | 1.16%   |
| 72      | 8         | 1.03%   |
| 31      | 8         | 1.03%   |
| 54      | 3         | 0.39%   |
| 32      | 3         | 0.39%   |
| 52      | 2         | 0.26%   |
| 48      | 2         | 0.26%   |
| 40      | 2         | 0.26%   |
| 33      | 2         | 0.26%   |
| 26      | 2         | 0.26%   |
| 16      | 2         | 0.26%   |
| 8       | 2         | 0.26%   |
| 84      | 1         | 0.13%   |
| 65      | 1         | 0.13%   |
| 64      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |
| 25      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 338       | 44.24%  |
| 501-600     | 101       | 13.22%  |
| 401-500     | 94        | 12.3%   |
| 201-300     | 73        | 9.55%   |
| 351-400     | 57        | 7.46%   |
| Unknown     | 55        | 7.2%    |
| 701-800     | 14        | 1.83%   |
| 601-700     | 11        | 1.44%   |
| 1501-2000   | 9         | 1.18%   |
| 1001-1500   | 8         | 1.05%   |
| 801-900     | 2         | 0.26%   |
| 101-200     | 2         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 508       | 69.3%   |
| 16/10   | 104       | 14.19%  |
| Unknown | 49        | 6.68%   |
| 5/4     | 38        | 5.18%   |
| 4/3     | 17        | 2.32%   |
| 21/9    | 11        | 1.5%    |
| 3/2     | 5         | 0.68%   |
| 32/9    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 235       | 30.36%  |
| 201-250        | 104       | 13.44%  |
| 81-90          | 95        | 12.27%  |
| 151-200        | 55        | 7.11%   |
| Unknown        | 55        | 7.11%   |
| 141-150        | 38        | 4.91%   |
| 301-350        | 28        | 3.62%   |
| 71-80          | 21        | 2.71%   |
| 351-500        | 21        | 2.71%   |
| 121-130        | 21        | 2.71%   |
| 251-300        | 19        | 2.45%   |
| 41-50          | 17        | 2.2%    |
| More than 1000 | 16        | 2.07%   |
| 61-70          | 15        | 1.94%   |
| 51-60          | 13        | 1.68%   |
| 131-140        | 7         | 0.9%    |
| 111-120        | 4         | 0.52%   |
| 501-1000       | 4         | 0.52%   |
| 91-100         | 4         | 0.52%   |
| 1-40           | 2         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 261       | 34.52%  |
| 101-120       | 231       | 30.56%  |
| 121-160       | 165       | 21.83%  |
| Unknown       | 55        | 7.28%   |
| 161-240       | 21        | 2.78%   |
| 1-50          | 16        | 2.12%   |
| More than 240 | 7         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 669       | 83.31%  |
| 2     | 86        | 10.71%  |
| 0     | 44        | 5.48%   |
| 3     | 4         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 432       | 35.18%  |
| Intel                             | 318       | 25.9%   |
| Qualcomm Atheros                  | 169       | 13.76%  |
| Broadcom                          | 89        | 7.25%   |
| Marvell Technology Group          | 25        | 2.04%   |
| Broadcom Limited                  | 23        | 1.87%   |
| Nvidia                            | 20        | 1.63%   |
| Ralink Technology                 | 18        | 1.47%   |
| TP-Link                           | 15        | 1.22%   |
| Ralink                            | 11        | 0.9%    |
| Samsung Electronics               | 10        | 0.81%   |
| MediaTek                          | 10        | 0.81%   |
| VIA Technologies                  | 6         | 0.49%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.49%   |
| Huawei Technologies               | 5         | 0.41%   |
| JMicron Technology                | 4         | 0.33%   |
| Ericsson Business Mobile Networks | 4         | 0.33%   |
| Xiaomi                            | 3         | 0.24%   |
| NetGear                           | 3         | 0.24%   |
| Microsoft                         | 3         | 0.24%   |
| Edimax Technology                 | 3         | 0.24%   |
| Dell                              | 3         | 0.24%   |
| ASUSTek Computer                  | 3         | 0.24%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.16%   |
| Spreadtrum Communications         | 2         | 0.16%   |
| Sitecom Europe                    | 2         | 0.16%   |
| Sierra Wireless                   | 2         | 0.16%   |
| Linksys                           | 2         | 0.16%   |
| Lenovo                            | 2         | 0.16%   |
| Hewlett-Packard                   | 2         | 0.16%   |
| Google                            | 2         | 0.16%   |
| DisplayLink                       | 2         | 0.16%   |
| AVM                               | 2         | 0.16%   |
| Attansic Technology               | 2         | 0.16%   |
| AMD                               | 2         | 0.16%   |
| ST-Ericsson                       | 1         | 0.08%   |
| Qualcomm Atheros Communications   | 1         | 0.08%   |
| Qualcomm                          | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.08%   |
| Microchip Technology              | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 260       | 17.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 79        | 5.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 31        | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 1.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 1.31%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 1.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 16        | 1.1%    |
| Intel Wireless 8265 / 8275                                              | 16        | 1.1%    |
| Intel Wireless 8260                                                     | 16        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.03%   |
| Intel Wireless 3165                                                     | 14        | 0.96%   |
| Intel I211 Gigabit Network Connection                                   | 14        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 0.89%   |
| Intel Wireless 7265                                                     | 11        | 0.76%   |
| Intel Wireless 7260                                                     | 11        | 0.76%   |
| Intel WiFi Link 5100                                                    | 11        | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                       | 10        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 9         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 0.62%   |
| Intel Ethernet Connection I217-LM                                       | 9         | 0.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.55%   |
| Nvidia MCP61 Ethernet                                                   | 8         | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 7         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 7         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 7         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 7         | 0.48%   |
| Intel Ethernet Connection I219-V                                        | 7         | 0.48%   |
| Intel 82579V Gigabit Network Connection                                 | 7         | 0.48%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 227       | 34.66%  |
| Realtek Semiconductor                 | 143       | 21.83%  |
| Qualcomm Atheros                      | 127       | 19.39%  |
| Broadcom                              | 63        | 9.62%   |
| Ralink Technology                     | 18        | 2.75%   |
| TP-Link                               | 14        | 2.14%   |
| Broadcom Limited                      | 12        | 1.83%   |
| Ralink                                | 11        | 1.68%   |
| MediaTek                              | 8         | 1.22%   |
| NetGear                               | 3         | 0.46%   |
| Microsoft                             | 3         | 0.46%   |
| Edimax Technology                     | 3         | 0.46%   |
| ASUSTek Computer                      | 3         | 0.46%   |
| Sitecom Europe                        | 2         | 0.31%   |
| Sierra Wireless                       | 2         | 0.31%   |
| Marvell Technology Group              | 2         | 0.31%   |
| Linksys                               | 2         | 0.31%   |
| AVM                                   | 2         | 0.31%   |
| Xiaomi                                | 1         | 0.15%   |
| Qualcomm Atheros Communications       | 1         | 0.15%   |
| Mercucys                              | 1         | 0.15%   |
| IMC Networks                          | 1         | 0.15%   |
| Fibocom                               | 1         | 0.15%   |
| Dell                                  | 1         | 0.15%   |
| D-Link System                         | 1         | 0.15%   |
| Cisco Aironet Wireless Communications | 1         | 0.15%   |
| Belkin Components                     | 1         | 0.15%   |
| Askey Computer                        | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 4.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 3.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 20        | 2.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 2.84%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 2.54%   |
| Intel Wireless 8265 / 8275                                              | 16        | 2.4%    |
| Intel Wireless 8260                                                     | 16        | 2.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 2.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 2.25%   |
| Intel Wireless 3165                                                     | 14        | 2.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 13        | 1.95%   |
| Intel Wireless 7265                                                     | 11        | 1.65%   |
| Intel Wireless 7260                                                     | 11        | 1.65%   |
| Intel WiFi Link 5100                                                    | 11        | 1.65%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 7         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.05%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 6         | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.9%    |
| Intel Wireless 3160                                                     | 6         | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.75%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.75%   |
| Realtek 802.11ac NIC                                                    | 5         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.75%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.75%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 378       | 50.33%  |
| Intel                            | 169       | 22.5%   |
| Qualcomm Atheros                 | 61        | 8.12%   |
| Broadcom                         | 34        | 4.53%   |
| Marvell Technology Group         | 23        | 3.06%   |
| Nvidia                           | 20        | 2.66%   |
| Broadcom Limited                 | 11        | 1.46%   |
| Samsung Electronics              | 9         | 1.2%    |
| VIA Technologies                 | 6         | 0.8%    |
| Silicon Integrated Systems [SiS] | 6         | 0.8%    |
| JMicron Technology               | 4         | 0.53%   |
| Huawei Technologies              | 4         | 0.53%   |
| Xiaomi                           | 2         | 0.27%   |
| Spreadtrum Communications        | 2         | 0.27%   |
| MediaTek                         | 2         | 0.27%   |
| Lenovo                           | 2         | 0.27%   |
| Hewlett-Packard                  | 2         | 0.27%   |
| Google                           | 2         | 0.27%   |
| DisplayLink                      | 2         | 0.27%   |
| Attansic Technology              | 2         | 0.27%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.13%   |
| TP-Link                          | 1         | 0.13%   |
| Qualcomm                         | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| HTC (High Tech Computer)         | 1         | 0.13%   |
| Gemtek                           | 1         | 0.13%   |
| Davicom Semiconductor            | 1         | 0.13%   |
| ADMtek                           | 1         | 0.13%   |
| 3Com                             | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 260       | 34.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 79        | 10.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 4.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16        | 2.1%    |
| Intel I211 Gigabit Network Connection                             | 14        | 1.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.05%   |
| Nvidia MCP61 Ethernet                                             | 8         | 1.05%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 7         | 0.92%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 7         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.92%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6         | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.79%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.79%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 6         | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 6         | 0.79%   |
| Intel 82573L Gigabit Ethernet Controller                          | 6         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.79%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 5         | 0.66%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 5         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4         | 0.52%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 3         | 0.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.39%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.39%   |
| Nvidia MCP77 Ethernet                                             | 3         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 708       | 52.44%  |
| WiFi     | 618       | 45.78%  |
| Modem    | 20        | 1.48%   |
| Unknown  | 4         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 445       | 54.67%  |
| Ethernet | 369       | 45.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 470       | 59.49%  |
| 1     | 294       | 37.22%  |
| 0     | 12        | 1.52%   |
| 3     | 10        | 1.27%   |
| 4     | 4         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 623       | 77.39%  |
| Yes  | 182       | 22.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 37.97%  |
| Realtek Semiconductor           | 57        | 14.43%  |
| Broadcom                        | 29        | 7.34%   |
| Qualcomm Atheros Communications | 27        | 6.84%   |
| Foxconn / Hon Hai               | 21        | 5.32%   |
| Cambridge Silicon Radio         | 21        | 5.32%   |
| Lite-On Technology              | 17        | 4.3%    |
| Apple                           | 15        | 3.8%    |
| Hewlett-Packard                 | 13        | 3.29%   |
| Dell                            | 10        | 2.53%   |
| IMC Networks                    | 9         | 2.28%   |
| ASUSTek Computer                | 5         | 1.27%   |
| Toshiba                         | 3         | 0.76%   |
| MediaTek                        | 3         | 0.76%   |
| Foxconn International           | 3         | 0.76%   |
| Askey Computer                  | 2         | 0.51%   |
| Taiyo Yuden                     | 1         | 0.25%   |
| Realtek                         | 1         | 0.25%   |
| Ralink Technology               | 1         | 0.25%   |
| Ralink                          | 1         | 0.25%   |
| Qcom                            | 1         | 0.25%   |
| Marvell Semiconductor           | 1         | 0.25%   |
| ISSC                            | 1         | 0.25%   |
| Dynex                           | 1         | 0.25%   |
| Chicony Electronics             | 1         | 0.25%   |
| Alps Electric                   | 1         | 0.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 70        | 17.72%  |
| Realtek Bluetooth Radio                                                             | 32        | 8.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 5.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 5.32%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 5.06%   |
| Intel AX201 Bluetooth                                                               | 18        | 4.56%   |
| Intel AX200 Bluetooth                                                               | 16        | 4.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 2.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 1.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 1.27%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.27%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.27%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.27%   |
| Lite-On Bluetooth Device                                                            | 4         | 1.01%   |
| Foxconn / Hon Hai Acer Module                                                       | 4         | 1.01%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.01%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 4         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 1.01%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.01%   |
| Apple Bluetooth HCI                                                                 | 4         | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.76%   |
| MediaTek Wireless_Device                                                            | 3         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.76%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 0.76%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.76%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.76%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 0.76%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.76%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.76%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.51%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 579       | 55.62%  |
| AMD                                  | 197       | 18.92%  |
| Nvidia                               | 176       | 16.91%  |
| C-Media Electronics                  | 19        | 1.83%   |
| VIA Technologies                     | 11        | 1.06%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.77%   |
| Generalplus Technology               | 6         | 0.58%   |
| GN Netcom                            | 5         | 0.48%   |
| Logitech                             | 4         | 0.38%   |
| JMTek                                | 4         | 0.38%   |
| Creative Labs                        | 4         | 0.38%   |
| Texas Instruments                    | 3         | 0.29%   |
| Yamaha                               | 2         | 0.19%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.19%   |
| Tenx Technology                      | 2         | 0.19%   |
| Plantronics                          | 2         | 0.19%   |
| KTMicro                              | 2         | 0.19%   |
| Creative Technology                  | 2         | 0.19%   |
| Xilinx                               | 1         | 0.1%    |
| Turtle Beach                         | 1         | 0.1%    |
| Sony                                 | 1         | 0.1%    |
| Realtek Semiconductor                | 1         | 0.1%    |
| Native Instruments                   | 1         | 0.1%    |
| Micro Star International             | 1         | 0.1%    |
| M-Audio                              | 1         | 0.1%    |
| GYROCOM C&C                          | 1         | 0.1%    |
| Focusrite-Novation                   | 1         | 0.1%    |
| Evolution Electronics                | 1         | 0.1%    |
| Dell                                 | 1         | 0.1%    |
| DCMT Technology                      | 1         | 0.1%    |
| Audioengine                          | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 66        | 5.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 59        | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 56        | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 55        | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 50        | 4.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 3.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 2.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 1.82%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 1.82%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 1.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 21        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 1.74%   |
| AMD FCH Azalia Controller                                                                         | 19        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 18        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 1.24%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 1.24%   |
| Nvidia High Definition Audio Controller                                                           | 14        | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 1.08%   |
| AMD High Definition Audio Controller                                                              | 13        | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 13        | 1.08%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 12        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.99%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 11        | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 10        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                                | 8         | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 8         | 0.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 0.66%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 60        | 22.06%  |
| Unknown                      | 44        | 16.18%  |
| SK hynix                     | 42        | 15.44%  |
| Kingston                     | 30        | 11.03%  |
| Micron Technology            | 19        | 6.99%   |
| Crucial                      | 13        | 4.78%   |
| Corsair                      | 10        | 3.68%   |
| G.Skill                      | 9         | 3.31%   |
| Nanya Technology             | 6         | 2.21%   |
| A-DATA Technology            | 5         | 1.84%   |
| Unknown (ABCD)               | 4         | 1.47%   |
| Ramaxel Technology           | 4         | 1.47%   |
| Smart                        | 3         | 1.1%    |
| Team                         | 2         | 0.74%   |
| Patriot                      | 2         | 0.74%   |
| GSkill                       | 2         | 0.74%   |
| Elpida                       | 2         | 0.74%   |
| Unknown                      | 2         | 0.74%   |
| Transcend                    | 1         | 0.37%   |
| Strontium                    | 1         | 0.37%   |
| PUSKILL                      | 1         | 0.37%   |
| PLEXHD                       | 1         | 0.37%   |
| Patriot Memory (PDP Systems) | 1         | 0.37%   |
| Lexar Co Limited             | 1         | 0.37%   |
| KLEVV                        | 1         | 0.37%   |
| Kingmax                      | 1         | 0.37%   |
| GeIL                         | 1         | 0.37%   |
| Exceleram                    | 1         | 0.37%   |
| AVEXIR                       | 1         | 0.37%   |
| AMD                          | 1         | 0.37%   |
| 4ea5                         | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.02%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.02%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.68%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.68%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR2 667MT/s         | 2         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.68%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Unknown                                                          | 2         | 0.68%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 0.34%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.34%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.34%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.34%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.34%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.34%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.34%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.34%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.34%   |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                       | 1         | 0.34%   |
| Unknown RAM Module 512MB DIMM 667MT/s                            | 1         | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 98        | 41.18%  |
| DDR3    | 84        | 35.29%  |
| DDR2    | 24        | 10.08%  |
| SDRAM   | 10        | 4.2%    |
| LPDDR4  | 8         | 3.36%   |
| DDR     | 6         | 2.52%   |
| Unknown | 6         | 2.52%   |
| LPDDR3  | 2         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 151       | 64.26%  |
| DIMM         | 73        | 31.06%  |
| Row Of Chips | 8         | 3.4%    |
| Unknown      | 2         | 0.85%   |
| Chip         | 1         | 0.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 89        | 34.23%  |
| 4096    | 65        | 25%     |
| 2048    | 52        | 20%     |
| 16384   | 26        | 10%     |
| 1024    | 15        | 5.77%   |
| 32768   | 6         | 2.31%   |
| 512     | 6         | 2.31%   |
| Unknown | 1         | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 49        | 19.22%  |
| 3200    | 37        | 14.51%  |
| 2667    | 37        | 14.51%  |
| 2400    | 21        | 8.24%   |
| 1333    | 17        | 6.67%   |
| Unknown | 12        | 4.71%   |
| 2133    | 11        | 4.31%   |
| 667     | 11        | 4.31%   |
| 800     | 9         | 3.53%   |
| 1334    | 7         | 2.75%   |
| 1067    | 7         | 2.75%   |
| 533     | 6         | 2.35%   |
| 3600    | 5         | 1.96%   |
| 3266    | 3         | 1.18%   |
| 4199    | 2         | 0.78%   |
| 2048    | 2         | 0.78%   |
| 1867    | 2         | 0.78%   |
| 1866    | 2         | 0.78%   |
| 1800    | 2         | 0.78%   |
| 975     | 2         | 0.78%   |
| 4267    | 1         | 0.39%   |
| 4266    | 1         | 0.39%   |
| 3800    | 1         | 0.39%   |
| 3733    | 1         | 0.39%   |
| 3533    | 1         | 0.39%   |
| 3500    | 1         | 0.39%   |
| 2267    | 1         | 0.39%   |
| 1200    | 1         | 0.39%   |
| 1066    | 1         | 0.39%   |
| 400     | 1         | 0.39%   |
| 266     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 40%     |
| Brother Industries  | 3         | 15%     |
| Seiko Epson         | 2         | 10%     |
| Samsung Electronics | 2         | 10%     |
| Canon               | 2         | 10%     |
| Ricoh               | 1         | 5%      |
| Minolta             | 1         | 5%      |
| Konica Minolta      | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Brother MFC-L2685DW              | 2         | 10%     |
| Seiko Epson XP-3100 Series       | 1         | 5%      |
| Seiko Epson ET-2820 Series       | 1         | 5%      |
| Samsung SCX-3400 Series          | 1         | 5%      |
| Samsung ML-1670 Series           | 1         | 5%      |
| Ricoh SP C260SFNw                | 1         | 5%      |
| Minolta PagePro 1200W            | 1         | 5%      |
| Konica Minolta 185               | 1         | 5%      |
| HP OfficeJet Pro 8730            | 1         | 5%      |
| HP LaserJet P1006                | 1         | 5%      |
| HP LaserJet 3050                 | 1         | 5%      |
| HP DeskJet F4200 series          | 1         | 5%      |
| HP DeskJet 2700 series           | 1         | 5%      |
| HP Deskjet 2540 series           | 1         | 5%      |
| HP DeskJet 2130 series           | 1         | 5%      |
| HP Deskjet 1050 J410             | 1         | 5%      |
| Canon LaserShot LBP-1120 Printer | 1         | 5%      |
| Canon iP4200                     | 1         | 5%      |
| Brother HL-L2300D series         | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| HP ScanJet 3800c                              | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 94        | 21.22%  |
| IMC Networks                           | 39        | 8.8%    |
| Microdia                               | 37        | 8.35%   |
| Suyin                                  | 30        | 6.77%   |
| Sunplus Innovation Technology          | 29        | 6.55%   |
| Realtek Semiconductor                  | 25        | 5.64%   |
| Quanta                                 | 24        | 5.42%   |
| Logitech                               | 17        | 3.84%   |
| Acer                                   | 17        | 3.84%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.39%   |
| Bison Electronics                      | 13        | 2.93%   |
| Apple                                  | 13        | 2.93%   |
| Syntek                                 | 10        | 2.26%   |
| Silicon Motion                         | 9         | 2.03%   |
| Luxvisions Innotech Limited            | 8         | 1.81%   |
| Z-Star Microelectronics                | 6         | 1.35%   |
| Ricoh                                  | 6         | 1.35%   |
| Importek                               | 6         | 1.35%   |
| Alcor Micro                            | 6         | 1.35%   |
| Lite-On Technology                     | 4         | 0.9%    |
| Microsoft                              | 3         | 0.68%   |
| Lenovo                                 | 3         | 0.68%   |
| ALi                                    | 3         | 0.68%   |
| Sunplus Technology                     | 2         | 0.45%   |
| Samsung Electronics                    | 2         | 0.45%   |
| OmniVision Technologies                | 2         | 0.45%   |
| Huawei Technologies                    | 2         | 0.45%   |
| Generalplus Technology                 | 2         | 0.45%   |
| Creative Technology                    | 2         | 0.45%   |
| Xiongmai                               | 1         | 0.23%   |
| WCM_USB                                | 1         | 0.23%   |
| USB Camera                             | 1         | 0.23%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.23%   |
| Service & Quality Technology           | 1         | 0.23%   |
| Pixart Imaging                         | 1         | 0.23%   |
| Nintendo                               | 1         | 0.23%   |
| MacroSilicon                           | 1         | 0.23%   |
| LG Electronics                         | 1         | 0.23%   |
| KYE Systems (Mouse Systems)            | 1         | 0.23%   |
| Intel                                  | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 19        | 4.25%   |
| Microdia Integrated_Webcam_HD                                  | 15        | 3.36%   |
| Chicony HD Webcam                                              | 9         | 2.01%   |
| IMC Networks Integrated Camera                                 | 8         | 1.79%   |
| Quanta HP Webcam                                               | 7         | 1.57%   |
| Apple Built-in iSight                                          | 7         | 1.57%   |
| Quanta HP TrueVision HD Camera                                 | 6         | 1.34%   |
| Logitech Webcam C270                                           | 6         | 1.34%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 6         | 1.34%   |
| Chicony HP TrueVision HD Camera                                | 6         | 1.34%   |
| Syntek Integrated Camera                                       | 5         | 1.12%   |
| Suyin HP TrueVision HD                                         | 5         | 1.12%   |
| Realtek USB2.0 camera                                          | 5         | 1.12%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 5         | 1.12%   |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 1.12%   |
| Acer Integrated Camera                                         | 5         | 1.12%   |
| Realtek Lenovo EasyCamera                                      | 4         | 0.89%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 0.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 0.89%   |
| IMC Networks EasyCamera                                        | 4         | 0.89%   |
| Chicony USB 2.0 Camera                                         | 4         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.89%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 4         | 0.89%   |
| Suyin HD WebCam                                                | 3         | 0.67%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 3         | 0.67%   |
| Suyin Acer HD Crystal Eye webcam                               | 3         | 0.67%   |
| Suyin 1.3M HD WebCam                                           | 3         | 0.67%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 3         | 0.67%   |
| Sunplus HP TrueVision HD Camera                                | 3         | 0.67%   |
| Sunplus HD WebCam                                              | 3         | 0.67%   |
| Sunplus FHD Camera Microphone                                  | 3         | 0.67%   |
| Silicon Motion WebCam SC-0311139N                              | 3         | 0.67%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 3         | 0.67%   |
| Quanta VGA WebCam                                              | 3         | 0.67%   |
| Microdia Sonix USB 2.0 Camera                                  | 3         | 0.67%   |
| Microdia REDRAGON Live Camera Audio                            | 3         | 0.67%   |
| Microdia Integrated Webcam HD                                  | 3         | 0.67%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 0.67%   |
| Logitech Webcam C310                                           | 3         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 40%     |
| AuthenTec                  | 12        | 18.46%  |
| Synaptics                  | 6         | 9.23%   |
| STMicroelectronics         | 5         | 7.69%   |
| Upek                       | 4         | 6.15%   |
| LighTuning Technology      | 4         | 6.15%   |
| Elan Microelectronics      | 3         | 4.62%   |
| Shenzhen Goodix Technology | 2         | 3.08%   |
| Samsung Electronics        | 1         | 1.54%   |
| Microsoft                  | 1         | 1.54%   |
| Focal-systems.Corp         | 1         | 1.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 5         | 7.69%   |
| STMicroelectronics Fingerprint Reader                    | 5         | 7.69%   |
| Validity Sensors VFS301 Fingerprint Reader               | 4         | 6.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 4         | 6.15%   |
| AuthenTec AES1600                                        | 4         | 6.15%   |
| Validity Sensors VFS451 Fingerprint Reader               | 3         | 4.62%   |
| Validity Sensors Fingerprint scanner                     | 3         | 4.62%   |
| Elan ELAN:Fingerprint                                    | 3         | 4.62%   |
| AuthenTec Fingerprint Sensor                             | 3         | 4.62%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 3         | 4.62%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 3.08%   |
| Validity Sensors VFS491                                  | 2         | 3.08%   |
| Validity Sensors Synaptics WBDI                          | 2         | 3.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 3.08%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 3.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 3.08%   |
| AuthenTec AES2810                                        | 2         | 3.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 1.54%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 1.54%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 1.54%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 1.54%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.54%   |
| Synaptics WBDI Fingerprint Reader USB 102                | 1         | 1.54%   |
| Synaptics WBDI                                           | 1         | 1.54%   |
| Synaptics UWP WBDI Device                                | 1         | 1.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.54%   |
| Samsung Fingerprint Sensor Device - 730B                 | 1         | 1.54%   |
| Microsoft Fingerprint Reader                             | 1         | 1.54%   |
| LighTuning Fingerprint Reader                            | 1         | 1.54%   |
| LighTuning ES603 Swipe Fingerprint Sensor                | 1         | 1.54%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 1.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 16        | 53.33%  |
| O2 Micro                          | 5         | 16.67%  |
| Alcor Micro                       | 3         | 10%     |
| VASCO Data Security International | 1         | 3.33%   |
| Upek                              | 1         | 3.33%   |
| OmniKey                           | 1         | 3.33%   |
| Lenovo                            | 1         | 3.33%   |
| Jing-Mold Enterprise              | 1         | 3.33%   |
| Gemalto (was Gemplus)             | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 26.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 10%     |
| Broadcom 5880                                                                | 2         | 6.67%   |
| Broadcom 58200                                                               | 2         | 6.67%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 3.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.33%   |
| OmniKey CardMan 1021                                                         | 1         | 3.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.33%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 3.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 536       | 66.42%  |
| 1     | 215       | 26.64%  |
| 2     | 40        | 4.96%   |
| 3     | 11        | 1.36%   |
| 4     | 4         | 0.5%    |
| 6     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 101       | 29.97%  |
| Net/wireless             | 74        | 21.96%  |
| Fingerprint reader       | 64        | 18.99%  |
| Multimedia controller    | 28        | 8.31%   |
| Chipcard                 | 26        | 7.72%   |
| Communication controller | 14        | 4.15%   |
| Storage                  | 7         | 2.08%   |
| Unassigned class         | 3         | 0.89%   |
| Network                  | 3         | 0.89%   |
| Flash memory             | 3         | 0.89%   |
| Bluetooth                | 3         | 0.89%   |
| Net/ethernet             | 2         | 0.59%   |
| Modem                    | 2         | 0.59%   |
| Camera                   | 2         | 0.59%   |
| Storage/raid             | 1         | 0.3%    |
| Storage/ide              | 1         | 0.3%    |
| Sound                    | 1         | 0.3%    |
| Dvb card                 | 1         | 0.3%    |
| Card reader              | 1         | 0.3%    |

