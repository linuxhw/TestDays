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

Total: 7727

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15API 81UT     | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| HP            | ProBook 650 G8 Notebook ... | [b11a7b69f0](https://linux-hardware.org/?probe=b11a7b69f0) | Sep 07, 2023 |
| Dell          | Latitude 7420               | [77df1805f6](https://linux-hardware.org/?probe=77df1805f6) | Sep 07, 2023 |
| Dell          | XPS 15 9550                 | [c9f30a2b26](https://linux-hardware.org/?probe=c9f30a2b26) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [2505f514b1](https://linux-hardware.org/?probe=2505f514b1) | Sep 06, 2023 |
| MSI           | GS60 2PC Ghost              | [0b971b067a](https://linux-hardware.org/?probe=0b971b067a) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| Dell          | Inspiron 14 5420            | [70d0d79f77](https://linux-hardware.org/?probe=70d0d79f77) | Sep 05, 2023 |
| Samsung       | 950XED                      | [3d8ba5a34c](https://linux-hardware.org/?probe=3d8ba5a34c) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| eMachines     | Rhine V1.42                 | [c18c4d64bd](https://linux-hardware.org/?probe=c18c4d64bd) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d5f8d13304](https://linux-hardware.org/?probe=d5f8d13304) | Sep 04, 2023 |
| Dell          | Vostro 14 3435              | [d35ddd8539](https://linux-hardware.org/?probe=d35ddd8539) | Sep 04, 2023 |
| Dell          | Vostro 14 3435              | [34a27b9c29](https://linux-hardware.org/?probe=34a27b9c29) | Sep 04, 2023 |
| Dell          | Precision 3581              | [739b270d83](https://linux-hardware.org/?probe=739b270d83) | Sep 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ0E    | [c5cdf73aa5](https://linux-hardware.org/?probe=c5cdf73aa5) | Sep 04, 2023 |
| Dell          | XPS 13 9310                 | [e30eaf0d9a](https://linux-hardware.org/?probe=e30eaf0d9a) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [88a04ab4b8](https://linux-hardware.org/?probe=88a04ab4b8) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [56cc7d7a27](https://linux-hardware.org/?probe=56cc7d7a27) | Sep 03, 2023 |
| Samsung       | R510/P510                   | [fa457144d5](https://linux-hardware.org/?probe=fa457144d5) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | [89dcb5988f](https://linux-hardware.org/?probe=89dcb5988f) | Sep 03, 2023 |
| HP            | Pavilion x2 Detachable      | [c98b2d5aba](https://linux-hardware.org/?probe=c98b2d5aba) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASUSTek       | X550CC                      | [1468567e45](https://linux-hardware.org/?probe=1468567e45) | Sep 03, 2023 |
| Acer          | Swift SF314-42              | [8552bc9508](https://linux-hardware.org/?probe=8552bc9508) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [8146fce36b](https://linux-hardware.org/?probe=8146fce36b) | Sep 03, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [7ebd20a049](https://linux-hardware.org/?probe=7ebd20a049) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [9903b0fbea](https://linux-hardware.org/?probe=9903b0fbea) | Sep 03, 2023 |
| EUROCOM       | RAPTOR X17                  | [93827ff6f1](https://linux-hardware.org/?probe=93827ff6f1) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | [3a5fd5b62b](https://linux-hardware.org/?probe=3a5fd5b62b) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [88673d4088](https://linux-hardware.org/?probe=88673d4088) | Sep 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6ed47558ae](https://linux-hardware.org/?probe=6ed47558ae) | Sep 03, 2023 |
| Apple         | MacBookAir5,1               | [57bb5d91ab](https://linux-hardware.org/?probe=57bb5d91ab) | Sep 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [c5787921e3](https://linux-hardware.org/?probe=c5787921e3) | Sep 03, 2023 |
| Thomson       | N14C4WH64                   | [cdfa5060e6](https://linux-hardware.org/?probe=cdfa5060e6) | Sep 03, 2023 |
| Acer          | Aspire A517-51G             | [762498a914](https://linux-hardware.org/?probe=762498a914) | Sep 02, 2023 |
| Timi          | TM1612                      | [b78b28d40d](https://linux-hardware.org/?probe=b78b28d40d) | Sep 02, 2023 |
| Schenker      | VIA 15 Pro                  | [4a31ab4d2b](https://linux-hardware.org/?probe=4a31ab4d2b) | Sep 02, 2023 |
| MSI           | GP70 2OD                    | [4bc109f9a0](https://linux-hardware.org/?probe=4bc109f9a0) | Sep 02, 2023 |
| Sony          | SVE1513I4E                  | [a1009ff0be](https://linux-hardware.org/?probe=a1009ff0be) | Sep 02, 2023 |
| Dell          | Latitude 7480               | [6c5351c835](https://linux-hardware.org/?probe=6c5351c835) | Sep 01, 2023 |
| Dell          | Latitude 7480               | [41fb46fed8](https://linux-hardware.org/?probe=41fb46fed8) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | [24d0eafc15](https://linux-hardware.org/?probe=24d0eafc15) | Sep 01, 2023 |
| ASUSTek       | N550JV                      | [b2effdc956](https://linux-hardware.org/?probe=b2effdc956) | Sep 01, 2023 |
| Apple         | MacBookPro5,2               | [35df364c39](https://linux-hardware.org/?probe=35df364c39) | Sep 01, 2023 |
| Sony          | SVE1513I4E                  | [404c008e41](https://linux-hardware.org/?probe=404c008e41) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | [406d9fd5fc](https://linux-hardware.org/?probe=406d9fd5fc) | Sep 01, 2023 |
| HP            | ProBook 650 G1              | [b0f558c0a2](https://linux-hardware.org/?probe=b0f558c0a2) | Aug 31, 2023 |
| HP            | ZBook 17 G3                 | [43c2d13a44](https://linux-hardware.org/?probe=43c2d13a44) | Aug 31, 2023 |
| MSI           | Modern 15 A5M               | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| ASUSTek       | K501LX                      | [ca56f1b803](https://linux-hardware.org/?probe=ca56f1b803) | Aug 30, 2023 |
| HP            | EliteBook 840 G3            | [b8492993cf](https://linux-hardware.org/?probe=b8492993cf) | Aug 30, 2023 |
| HP            | Laptop 15-db0xxx            | [76eb125a56](https://linux-hardware.org/?probe=76eb125a56) | Aug 30, 2023 |
| ASUSTek       | Zenbook UX6404VV_UX6404V... | [b7be264a8d](https://linux-hardware.org/?probe=b7be264a8d) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| Toshiba       | Satellite P50-B-113         | [a9f21477c8](https://linux-hardware.org/?probe=a9f21477c8) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Dell          | Latitude E5510              | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | Precision 5480              | [5fd5bf187d](https://linux-hardware.org/?probe=5fd5bf187d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430 2349H86       | [6ed258911c](https://linux-hardware.org/?probe=6ed258911c) | Aug 29, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [9450749b35](https://linux-hardware.org/?probe=9450749b35) | Aug 29, 2023 |
| Toshiba       | PORTEGE Z930                | [b4acaedb21](https://linux-hardware.org/?probe=b4acaedb21) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0f3d530e12](https://linux-hardware.org/?probe=0f3d530e12) | Aug 29, 2023 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | [4fa3f56511](https://linux-hardware.org/?probe=4fa3f56511) | Aug 29, 2023 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | [9bf240bf4d](https://linux-hardware.org/?probe=9bf240bf4d) | Aug 29, 2023 |
| Dell          | Latitude E4310              | [03b37a1c55](https://linux-hardware.org/?probe=03b37a1c55) | Aug 28, 2023 |
| Packard Be... | EasyNote TJ65               | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| Dell          | Precision 3520              | [a87048ecac](https://linux-hardware.org/?probe=a87048ecac) | Aug 28, 2023 |
| Dell          | Precision 3520              | [6afb6bacac](https://linux-hardware.org/?probe=6afb6bacac) | Aug 28, 2023 |
| Corsair       | Voyager a1600               | [405bce7897](https://linux-hardware.org/?probe=405bce7897) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90474aa183](https://linux-hardware.org/?probe=90474aa183) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [97caef0e98](https://linux-hardware.org/?probe=97caef0e98) | Aug 27, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [3176d728c4](https://linux-hardware.org/?probe=3176d728c4) | Aug 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [cc91bf6584](https://linux-hardware.org/?probe=cc91bf6584) | Aug 27, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [4a3a5eb408](https://linux-hardware.org/?probe=4a3a5eb408) | Aug 27, 2023 |
| Corsair       | Voyager a1600               | [97a1c576f7](https://linux-hardware.org/?probe=97a1c576f7) | Aug 26, 2023 |
| HP            | Pavilion 17                 | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [211472aacc](https://linux-hardware.org/?probe=211472aacc) | Aug 26, 2023 |
| ASUSTek       | X550CL                      | [88ab580175](https://linux-hardware.org/?probe=88ab580175) | Aug 26, 2023 |
| ASUSTek       | X550CL                      | [c957b259a2](https://linux-hardware.org/?probe=c957b259a2) | Aug 26, 2023 |
| HP            | Pavilion dv7                | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| HP            | Laptop 15-bs0xx             | [7a522c6b71](https://linux-hardware.org/?probe=7a522c6b71) | Aug 25, 2023 |
| Lenovo        | ThinkPad L580 20LXS1D100    | [f30a161506](https://linux-hardware.org/?probe=f30a161506) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460 20FN003LFR    | [b6a67bea6a](https://linux-hardware.org/?probe=b6a67bea6a) | Aug 25, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| HP            | Notebook                    | [c3ae6b2ed1](https://linux-hardware.org/?probe=c3ae6b2ed1) | Aug 25, 2023 |
| Toshiba       | Satellite C70-B             | [2647e2edd8](https://linux-hardware.org/?probe=2647e2edd8) | Aug 24, 2023 |
| Dell          | Inspiron 5770               | [caecc0c140](https://linux-hardware.org/?probe=caecc0c140) | Aug 24, 2023 |
| Dell          | Inspiron 5770               | [0aaf8b7985](https://linux-hardware.org/?probe=0aaf8b7985) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [d3efd68f2f](https://linux-hardware.org/?probe=d3efd68f2f) | Aug 24, 2023 |
| LDLC          | SPC-I                       | [bb114215e6](https://linux-hardware.org/?probe=bb114215e6) | Aug 24, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [17525a9aef](https://linux-hardware.org/?probe=17525a9aef) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | [6f0e38b5e8](https://linux-hardware.org/?probe=6f0e38b5e8) | Aug 23, 2023 |
| MSI           | Stealth 17Studio A13VF      | [ca952946e9](https://linux-hardware.org/?probe=ca952946e9) | Aug 23, 2023 |
| HP            | Laptop 17-cp0xxx            | [be00a84105](https://linux-hardware.org/?probe=be00a84105) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [65747a7530](https://linux-hardware.org/?probe=65747a7530) | Aug 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [9ad109a4df](https://linux-hardware.org/?probe=9ad109a4df) | Aug 22, 2023 |
| Apple         | MacBookPro13,1              | [73c6fa6546](https://linux-hardware.org/?probe=73c6fa6546) | Aug 22, 2023 |
| Toshiba       | Satellite P500              | [41efb0cb7b](https://linux-hardware.org/?probe=41efb0cb7b) | Aug 22, 2023 |
| Lenovo        | G50-45 80E3                 | [044deb0ad2](https://linux-hardware.org/?probe=044deb0ad2) | Aug 22, 2023 |
| Dell          | Latitude E7270              | [9eaaeb2503](https://linux-hardware.org/?probe=9eaaeb2503) | Aug 22, 2023 |
| Dell          | Latitude 5400               | [2036f8dd50](https://linux-hardware.org/?probe=2036f8dd50) | Aug 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [210e9d3b38](https://linux-hardware.org/?probe=210e9d3b38) | Aug 21, 2023 |
| Dell          | Latitude 7310               | [f32da77ac4](https://linux-hardware.org/?probe=f32da77ac4) | Aug 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [43d120af0e](https://linux-hardware.org/?probe=43d120af0e) | Aug 21, 2023 |
| HP            | EliteBook 840 G3            | [87c6b8d057](https://linux-hardware.org/?probe=87c6b8d057) | Aug 21, 2023 |
| HP            | ProBook 4730s               | [5b4d88bc67](https://linux-hardware.org/?probe=5b4d88bc67) | Aug 21, 2023 |
| Acer          | Aspire 7750G                | [0bf0d8e338](https://linux-hardware.org/?probe=0bf0d8e338) | Aug 21, 2023 |
| Toshiba       | Satellite C70-B             | [d4f90e5eff](https://linux-hardware.org/?probe=d4f90e5eff) | Aug 21, 2023 |
| Acer          | Aspire E1-570               | [8cdca3eca4](https://linux-hardware.org/?probe=8cdca3eca4) | Aug 20, 2023 |
| ASUSTek       | X555YI                      | [76b5b9e85d](https://linux-hardware.org/?probe=76b5b9e85d) | Aug 20, 2023 |
| Dell          | Inspiron 15 3520            | [bd2639e592](https://linux-hardware.org/?probe=bd2639e592) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [30b645c7f4](https://linux-hardware.org/?probe=30b645c7f4) | Aug 20, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [47ed3b6bc8](https://linux-hardware.org/?probe=47ed3b6bc8) | Aug 20, 2023 |
| Dell          | Latitude E5520              | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| Danew         | Dbook 131                   | [35ea124809](https://linux-hardware.org/?probe=35ea124809) | Aug 19, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [f8c85e442f](https://linux-hardware.org/?probe=f8c85e442f) | Aug 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [fdc761a52c](https://linux-hardware.org/?probe=fdc761a52c) | Aug 18, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [590ac28f26](https://linux-hardware.org/?probe=590ac28f26) | Aug 18, 2023 |
| Dell          | Latitude 5420               | [6a758f4880](https://linux-hardware.org/?probe=6a758f4880) | Aug 18, 2023 |
| Dell          | Latitude 7300               | [607cb8c677](https://linux-hardware.org/?probe=607cb8c677) | Aug 18, 2023 |
| Dell          | Inspiron 7591               | [2e09db6501](https://linux-hardware.org/?probe=2e09db6501) | Aug 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [6fb9870620](https://linux-hardware.org/?probe=6fb9870620) | Aug 18, 2023 |
| ASUSTek       | X75VD                       | [b07665aa45](https://linux-hardware.org/?probe=b07665aa45) | Aug 17, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Apple         | MacBookAir6,1               | [ed669d11d8](https://linux-hardware.org/?probe=ed669d11d8) | Aug 17, 2023 |
| Dell          | XPS 13 9310                 | [680fae2274](https://linux-hardware.org/?probe=680fae2274) | Aug 17, 2023 |
| Google        | Coral                       | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [e56c46e8fe](https://linux-hardware.org/?probe=e56c46e8fe) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Toshiba       | Satellite L670              | [915e37b55d](https://linux-hardware.org/?probe=915e37b55d) | Aug 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [1b29161809](https://linux-hardware.org/?probe=1b29161809) | Aug 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fd91c311ff](https://linux-hardware.org/?probe=fd91c311ff) | Aug 16, 2023 |
| HP            | Laptop 15-db0xxx            | [73640f7f83](https://linux-hardware.org/?probe=73640f7f83) | Aug 16, 2023 |
| Dell          | Precision 7530              | [dfaa8829e1](https://linux-hardware.org/?probe=dfaa8829e1) | Aug 16, 2023 |
| Dell          | Latitude 7300               | [07c0414596](https://linux-hardware.org/?probe=07c0414596) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | [24cd5deaa3](https://linux-hardware.org/?probe=24cd5deaa3) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | [b42d5dec8e](https://linux-hardware.org/?probe=b42d5dec8e) | Aug 16, 2023 |
| Packard Be... | EasyNote TSX66HR            | [f1b16023fd](https://linux-hardware.org/?probe=f1b16023fd) | Aug 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d6925a9c7a](https://linux-hardware.org/?probe=d6925a9c7a) | Aug 15, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1f27d0f994](https://linux-hardware.org/?probe=1f27d0f994) | Aug 14, 2023 |
| ASUSTek       | UX303UA                     | [a34dfca1e3](https://linux-hardware.org/?probe=a34dfca1e3) | Aug 14, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | [61edf8f5ee](https://linux-hardware.org/?probe=61edf8f5ee) | Aug 14, 2023 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [57af1d89d6](https://linux-hardware.org/?probe=57af1d89d6) | Aug 14, 2023 |
| Acer          | Swift SF515-51T             | [9271029425](https://linux-hardware.org/?probe=9271029425) | Aug 13, 2023 |
| Tactus        | GeoBook 110                 | [b6897622f2](https://linux-hardware.org/?probe=b6897622f2) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [e934dcd506](https://linux-hardware.org/?probe=e934dcd506) | Aug 13, 2023 |
| HP            | EliteBook 840 G6            | [bcf7b9bd8f](https://linux-hardware.org/?probe=bcf7b9bd8f) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| Thomson       | X6-4.32GR                   | [454fdb4295](https://linux-hardware.org/?probe=454fdb4295) | Aug 13, 2023 |
| Dell          | XPS 13 9310                 | [11a7488d83](https://linux-hardware.org/?probe=11a7488d83) | Aug 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [1bb5ae3f67](https://linux-hardware.org/?probe=1bb5ae3f67) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [67f821bd4d](https://linux-hardware.org/?probe=67f821bd4d) | Aug 12, 2023 |
| Acer          | Aspire 5733Z                | [977c66cbc0](https://linux-hardware.org/?probe=977c66cbc0) | Aug 12, 2023 |
| Unknown       | Unknown                     | [2e76349d2c](https://linux-hardware.org/?probe=2e76349d2c) | Aug 12, 2023 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [361e073b5c](https://linux-hardware.org/?probe=361e073b5c) | Aug 11, 2023 |
| Sony          | SVE1513I4E                  | [6b8cb6d520](https://linux-hardware.org/?probe=6b8cb6d520) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Acer          | Aspire ES1-431              | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0caf17e079](https://linux-hardware.org/?probe=0caf17e079) | Aug 10, 2023 |
| HP            | Pavilion 17                 | [65733120b0](https://linux-hardware.org/?probe=65733120b0) | Aug 09, 2023 |
| Lenovo        | V145-15AST 81MT             | [304b175b3c](https://linux-hardware.org/?probe=304b175b3c) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [bf81bbf7b4](https://linux-hardware.org/?probe=bf81bbf7b4) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | [de8d362cb8](https://linux-hardware.org/?probe=de8d362cb8) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [5e79da69ed](https://linux-hardware.org/?probe=5e79da69ed) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [c761edfea1](https://linux-hardware.org/?probe=c761edfea1) | Aug 09, 2023 |
| Dell          | XPS 15 9520                 | [0620b6b11a](https://linux-hardware.org/?probe=0620b6b11a) | Aug 09, 2023 |
| Dell          | Latitude 7310               | [19646f8e46](https://linux-hardware.org/?probe=19646f8e46) | Aug 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T800     | [8316628b28](https://linux-hardware.org/?probe=8316628b28) | Aug 08, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T800     | [05d33f11b5](https://linux-hardware.org/?probe=05d33f11b5) | Aug 08, 2023 |
| Notebook      | W65_W67RZ1                  | [ab4b3c8f47](https://linux-hardware.org/?probe=ab4b3c8f47) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [187ac2792a](https://linux-hardware.org/?probe=187ac2792a) | Aug 08, 2023 |
| HP            | EliteBook 840 G3            | [bf56c08196](https://linux-hardware.org/?probe=bf56c08196) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | [c52b1e963f](https://linux-hardware.org/?probe=c52b1e963f) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4148b505d6](https://linux-hardware.org/?probe=4148b505d6) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | [211978450c](https://linux-hardware.org/?probe=211978450c) | Aug 08, 2023 |
| HP            | EliteBook 840 G3            | [132603d7e2](https://linux-hardware.org/?probe=132603d7e2) | Aug 08, 2023 |
| Dell          | Latitude 7310               | [baab866835](https://linux-hardware.org/?probe=baab866835) | Aug 08, 2023 |
| HP            | ZBook 14 G2                 | [23dd3e572c](https://linux-hardware.org/?probe=23dd3e572c) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [b00519fee7](https://linux-hardware.org/?probe=b00519fee7) | Aug 08, 2023 |
| Acer          | AO756                       | [1ea1658ac0](https://linux-hardware.org/?probe=1ea1658ac0) | Aug 07, 2023 |
| Notebook      | NLx0MU                      | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| HP            | G60                         | [7f3b9aec85](https://linux-hardware.org/?probe=7f3b9aec85) | Aug 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [a1b9b9fc2c](https://linux-hardware.org/?probe=a1b9b9fc2c) | Aug 07, 2023 |
| MSI           | GL72 7QF                    | [73f4a3b852](https://linux-hardware.org/?probe=73f4a3b852) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a3dd4fadf3](https://linux-hardware.org/?probe=a3dd4fadf3) | Aug 07, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [fe977cc0fe](https://linux-hardware.org/?probe=fe977cc0fe) | Aug 07, 2023 |
| Notebook      | NHxxRZQ                     | [0cd17c8b5c](https://linux-hardware.org/?probe=0cd17c8b5c) | Aug 07, 2023 |
| Micro Comp... | NUCXI7                      | [96d3ade9eb](https://linux-hardware.org/?probe=96d3ade9eb) | Aug 07, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [a3c7d29211](https://linux-hardware.org/?probe=a3c7d29211) | Aug 06, 2023 |
| Dell          | Latitude E5440              | [326ba9627a](https://linux-hardware.org/?probe=326ba9627a) | Aug 06, 2023 |
| Dell          | Latitude 5400               | [e788e3a534](https://linux-hardware.org/?probe=e788e3a534) | Aug 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [8c56195933](https://linux-hardware.org/?probe=8c56195933) | Aug 05, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [ae5361d56f](https://linux-hardware.org/?probe=ae5361d56f) | Aug 05, 2023 |
| ASUSTek       | K52Je                       | [34fa8887dd](https://linux-hardware.org/?probe=34fa8887dd) | Aug 05, 2023 |
| HP            | Notebook                    | [d86cc7b5ba](https://linux-hardware.org/?probe=d86cc7b5ba) | Aug 05, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [f4f8099774](https://linux-hardware.org/?probe=f4f8099774) | Aug 05, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [f1e284ec93](https://linux-hardware.org/?probe=f1e284ec93) | Aug 04, 2023 |
| Dell          | G5 5587                     | [320fffbb49](https://linux-hardware.org/?probe=320fffbb49) | Aug 04, 2023 |
| Acer          | Aspire 5738                 | [f5df04e0e6](https://linux-hardware.org/?probe=f5df04e0e6) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [87febc0242](https://linux-hardware.org/?probe=87febc0242) | Aug 04, 2023 |
| Dell          | Latitude 5480               | [c52baac4e0](https://linux-hardware.org/?probe=c52baac4e0) | Aug 03, 2023 |
| MSI           | Titan GT77HX 13VH           | [3acda608a1](https://linux-hardware.org/?probe=3acda608a1) | Aug 03, 2023 |
| Sony          | VGN-NS38E_S                 | [a21051f2a8](https://linux-hardware.org/?probe=a21051f2a8) | Aug 03, 2023 |
| Notebook      | N9x0TD_TF                   | [033c07e1d3](https://linux-hardware.org/?probe=033c07e1d3) | Aug 03, 2023 |
| Notebook      | N9x0TD_TF                   | [3ab98d3af1](https://linux-hardware.org/?probe=3ab98d3af1) | Aug 03, 2023 |
| HP            | EliteBook 8570p             | [9b2c783e20](https://linux-hardware.org/?probe=9b2c783e20) | Aug 03, 2023 |
| Toshiba       | Satellite C70-B             | [877d855f27](https://linux-hardware.org/?probe=877d855f27) | Aug 02, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | [18e29b97ac](https://linux-hardware.org/?probe=18e29b97ac) | Aug 02, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [251b811e9b](https://linux-hardware.org/?probe=251b811e9b) | Aug 02, 2023 |
| Dell          | XPS 15 9500                 | [5c8ad99a3c](https://linux-hardware.org/?probe=5c8ad99a3c) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5f2529e42b](https://linux-hardware.org/?probe=5f2529e42b) | Aug 02, 2023 |
| HP            | Pavilion 15                 | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| ASUSTek       | GL502VSK                    | [0ed7feaa05](https://linux-hardware.org/?probe=0ed7feaa05) | Aug 01, 2023 |
| Dell          | Precision 7520              | [b5addbb003](https://linux-hardware.org/?probe=b5addbb003) | Aug 01, 2023 |
| Acer          | AOD255                      | [bdaffcb2ef](https://linux-hardware.org/?probe=bdaffcb2ef) | Jul 31, 2023 |
| Packard Be... | H17HV                       | [de2003d390](https://linux-hardware.org/?probe=de2003d390) | Jul 31, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | [560cd8b4fb](https://linux-hardware.org/?probe=560cd8b4fb) | Jul 31, 2023 |
| Dell          | G15 5510                    | [8ab77abc2e](https://linux-hardware.org/?probe=8ab77abc2e) | Jul 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3daec696c7](https://linux-hardware.org/?probe=3daec696c7) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| MSI           | GT70 2PE                    | [d0ef2177c3](https://linux-hardware.org/?probe=d0ef2177c3) | Jul 29, 2023 |
| MSI           | GT70 2PE                    | [bc059e2204](https://linux-hardware.org/?probe=bc059e2204) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | [413fcf8114](https://linux-hardware.org/?probe=413fcf8114) | Jul 29, 2023 |
| Acer          | Swift SF315-52G             | [aca997f2b5](https://linux-hardware.org/?probe=aca997f2b5) | Jul 29, 2023 |
| Acer          | AOD255                      | [53c73b6ad3](https://linux-hardware.org/?probe=53c73b6ad3) | Jul 29, 2023 |
| HP            | ProBook 4525s               | [f1f6309860](https://linux-hardware.org/?probe=f1f6309860) | Jul 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [579d4eebb8](https://linux-hardware.org/?probe=579d4eebb8) | Jul 29, 2023 |
| ASUSTek       | X102BA                      | [488aa4c5b4](https://linux-hardware.org/?probe=488aa4c5b4) | Jul 29, 2023 |
| Sony          | VGN-NS38E_S                 | [703b459140](https://linux-hardware.org/?probe=703b459140) | Jul 28, 2023 |
| Chitech Sh... | Tibuta_MasterPad-W100       | [202a9be7b7](https://linux-hardware.org/?probe=202a9be7b7) | Jul 28, 2023 |
| Acer          | Aspire 4810T                | [4d3abb525e](https://linux-hardware.org/?probe=4d3abb525e) | Jul 28, 2023 |
| Dell          | Precision 3520              | [bc2e0ff018](https://linux-hardware.org/?probe=bc2e0ff018) | Jul 28, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [6e7d094f7f](https://linux-hardware.org/?probe=6e7d094f7f) | Jul 27, 2023 |
| Toshiba       | Satellite C70-B             | [56489a32b2](https://linux-hardware.org/?probe=56489a32b2) | Jul 27, 2023 |
| Dell          | Precision 3520              | [2502fbaef2](https://linux-hardware.org/?probe=2502fbaef2) | Jul 26, 2023 |
| Acer          | AOD255                      | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [f8720bbd07](https://linux-hardware.org/?probe=f8720bbd07) | Jul 25, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | [f22f51832b](https://linux-hardware.org/?probe=f22f51832b) | Jul 25, 2023 |
| Dell          | Studio 1537                 | [803a98f7e6](https://linux-hardware.org/?probe=803a98f7e6) | Jul 25, 2023 |
| HP            | 250 G5 Notebook PC          | [007f2e5957](https://linux-hardware.org/?probe=007f2e5957) | Jul 25, 2023 |
| Dell          | Inspiron 15-3552            | [3b317edaf6](https://linux-hardware.org/?probe=3b317edaf6) | Jul 25, 2023 |
| MSI           | GF63 Thin 10SCXR            | [b34b7fa5fb](https://linux-hardware.org/?probe=b34b7fa5fb) | Jul 25, 2023 |
| Acer          | Nitro AN515-57              | [d4b572d070](https://linux-hardware.org/?probe=d4b572d070) | Jul 24, 2023 |
| Dell          | Precision 7520              | [66922483cf](https://linux-hardware.org/?probe=66922483cf) | Jul 24, 2023 |
| Acer          | AOD255                      | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| Dell          | Inspiron 15 3511            | [980ed56abe](https://linux-hardware.org/?probe=980ed56abe) | Jul 24, 2023 |
| Valve         | Jupiter                     | [59b11daded](https://linux-hardware.org/?probe=59b11daded) | Jul 24, 2023 |
| Acer          | Aspire 5738                 | [3cc1d4a0cd](https://linux-hardware.org/?probe=3cc1d4a0cd) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Dell          | Inspiron 3541               | [0a146a40d9](https://linux-hardware.org/?probe=0a146a40d9) | Jul 23, 2023 |
| Lenovo        | ThinkPad L460 20FVS01J00    | [96fe0142cd](https://linux-hardware.org/?probe=96fe0142cd) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Dell          | Precision M2400             | [86913a26b4](https://linux-hardware.org/?probe=86913a26b4) | Jul 22, 2023 |
| Lenovo        | ThinkPad T420s 4174PEG      | [3bedb2ae12](https://linux-hardware.org/?probe=3bedb2ae12) | Jul 22, 2023 |
| ASUSTek       | B53E                        | [08012052d5](https://linux-hardware.org/?probe=08012052d5) | Jul 21, 2023 |
| ASUSTek       | K72Jr                       | [cdb9b29f94](https://linux-hardware.org/?probe=cdb9b29f94) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [3db32d6c63](https://linux-hardware.org/?probe=3db32d6c63) | Jul 21, 2023 |
| Lenovo        | ThinkPad T540p 20BFA06B0... | [15e3320bb0](https://linux-hardware.org/?probe=15e3320bb0) | Jul 21, 2023 |
| Toshiba       | Satellite C70-B             | [cf2d22469b](https://linux-hardware.org/?probe=cf2d22469b) | Jul 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5c4d93901b](https://linux-hardware.org/?probe=5c4d93901b) | Jul 20, 2023 |
| ASUSTek       | UX303LB                     | [901f80bb60](https://linux-hardware.org/?probe=901f80bb60) | Jul 20, 2023 |
| MSI           | CR700                       | [5cde06d6b9](https://linux-hardware.org/?probe=5cde06d6b9) | Jul 20, 2023 |
| MSI           | CR700                       | [2b2e403f78](https://linux-hardware.org/?probe=2b2e403f78) | Jul 20, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7527ca0197](https://linux-hardware.org/?probe=7527ca0197) | Jul 20, 2023 |
| HP            | Pavilion 15                 | [e1bfe97e63](https://linux-hardware.org/?probe=e1bfe97e63) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| Thomson       | N15C8BK2T                   | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| HP            | Pavilion 15                 | [a5485bb7e0](https://linux-hardware.org/?probe=a5485bb7e0) | Jul 18, 2023 |
| Acer          | Nitro AN515-57              | [9853a8cf46](https://linux-hardware.org/?probe=9853a8cf46) | Jul 18, 2023 |
| Thomson       | X15I5-8TU512                | [f2d5a7b0d5](https://linux-hardware.org/?probe=f2d5a7b0d5) | Jul 17, 2023 |
| Dell          | Inspiron 16 7610            | [6d77ef17a0](https://linux-hardware.org/?probe=6d77ef17a0) | Jul 17, 2023 |
| ASUSTek       | G551JM                      | [393e57db0c](https://linux-hardware.org/?probe=393e57db0c) | Jul 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [e2075c4a1e](https://linux-hardware.org/?probe=e2075c4a1e) | Jul 17, 2023 |
| Alienware     | m16 R1 AMD                  | [7ca76c0d32](https://linux-hardware.org/?probe=7ca76c0d32) | Jul 17, 2023 |
| Teclast       | F6 Plus                     | [c18a0b61ae](https://linux-hardware.org/?probe=c18a0b61ae) | Jul 16, 2023 |
| Teclast       | F6 Plus                     | [c95b1bb4f5](https://linux-hardware.org/?probe=c95b1bb4f5) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [c1de0cf4d1](https://linux-hardware.org/?probe=c1de0cf4d1) | Jul 16, 2023 |
| Dell          | Latitude E6320              | [0087a8e5cf](https://linux-hardware.org/?probe=0087a8e5cf) | Jul 16, 2023 |
| Toshiba       | Satellite P500              | [c72cbade9e](https://linux-hardware.org/?probe=c72cbade9e) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [8d3168b6c4](https://linux-hardware.org/?probe=8d3168b6c4) | Jul 15, 2023 |
| HP            | EliteBook 840 G1            | [420ffaec41](https://linux-hardware.org/?probe=420ffaec41) | Jul 15, 2023 |
| HP            | Pavilion 17                 | [c8775bcc36](https://linux-hardware.org/?probe=c8775bcc36) | Jul 15, 2023 |
| Acer          | Aspire E5-773G              | [a4a4102548](https://linux-hardware.org/?probe=a4a4102548) | Jul 15, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c36495481b](https://linux-hardware.org/?probe=c36495481b) | Jul 15, 2023 |
| SLIMBOOK      | PROX15-AMD                  | [7e088e838b](https://linux-hardware.org/?probe=7e088e838b) | Jul 15, 2023 |
| Dell          | Inspiron MP061              | [0a26ffe33b](https://linux-hardware.org/?probe=0a26ffe33b) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | [6e79cbdccc](https://linux-hardware.org/?probe=6e79cbdccc) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | [1c9da1be8b](https://linux-hardware.org/?probe=1c9da1be8b) | Jul 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | [41283a1f4e](https://linux-hardware.org/?probe=41283a1f4e) | Jul 15, 2023 |
| Dell          | Latitude 7490               | [6811ebe45a](https://linux-hardware.org/?probe=6811ebe45a) | Jul 15, 2023 |
| BESSTAR Te... | U820                        | [274b5bed12](https://linux-hardware.org/?probe=274b5bed12) | Jul 15, 2023 |
| Toshiba       | Satellite Pro L500          | [605c123888](https://linux-hardware.org/?probe=605c123888) | Jul 15, 2023 |
| Toshiba       | Satellite C70-B             | [9727ab2451](https://linux-hardware.org/?probe=9727ab2451) | Jul 14, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2f552150c5](https://linux-hardware.org/?probe=2f552150c5) | Jul 14, 2023 |
| Lenovo        | ThinkPad X260 20F5S04B00    | [ae8ecf10e7](https://linux-hardware.org/?probe=ae8ecf10e7) | Jul 13, 2023 |
| Unknown       | Unknown                     | [a67315ae3e](https://linux-hardware.org/?probe=a67315ae3e) | Jul 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| ASUSTek       | X456UV                      | [b0a9e3905f](https://linux-hardware.org/?probe=b0a9e3905f) | Jul 13, 2023 |
| Lenovo        | ThinkPad X280 20KES73S06    | [b301164e01](https://linux-hardware.org/?probe=b301164e01) | Jul 13, 2023 |
| Dell          | XPS 13 9343                 | [0ae6ff1386](https://linux-hardware.org/?probe=0ae6ff1386) | Jul 13, 2023 |
| HP            | ProBook 4525s               | [6bae89bb98](https://linux-hardware.org/?probe=6bae89bb98) | Jul 13, 2023 |
| Sony          | VPCEF4E1E                   | [32f1860a65](https://linux-hardware.org/?probe=32f1860a65) | Jul 12, 2023 |
| Acer          | Swift SF515-51T             | [9f8a8c63e6](https://linux-hardware.org/?probe=9f8a8c63e6) | Jul 12, 2023 |
| HP            | EliteBook 8440p             | [3ffdc0cd08](https://linux-hardware.org/?probe=3ffdc0cd08) | Jul 12, 2023 |
| ASUSTek       | GL553VW                     | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| Samsung       | 950XED                      | [2f8f9d9277](https://linux-hardware.org/?probe=2f8f9d9277) | Jul 12, 2023 |
| Dell          | Inspiron 1545               | [738fd58ef5](https://linux-hardware.org/?probe=738fd58ef5) | Jul 11, 2023 |
| HP            | Compaq 6730s                | [1c3f1f1005](https://linux-hardware.org/?probe=1c3f1f1005) | Jul 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | [c2a5a3534e](https://linux-hardware.org/?probe=c2a5a3534e) | Jul 10, 2023 |
| HP            | ENVY 17                     | [0d1714007f](https://linux-hardware.org/?probe=0d1714007f) | Jul 09, 2023 |
| Acer          | Aspire A515-51G             | [044dd1e5a7](https://linux-hardware.org/?probe=044dd1e5a7) | Jul 09, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [866af72fb6](https://linux-hardware.org/?probe=866af72fb6) | Jul 09, 2023 |
| TR            | ST Plus-KN                  | [3d549b50a3](https://linux-hardware.org/?probe=3d549b50a3) | Jul 09, 2023 |
| ASUSTek       | VivoBook S14 X430UA         | [fdb15c83de](https://linux-hardware.org/?probe=fdb15c83de) | Jul 09, 2023 |
| Dell          | Latitude 5320               | [55d5b4447a](https://linux-hardware.org/?probe=55d5b4447a) | Jul 09, 2023 |
| HP            | EliteBook 840 G5            | [8a798fe917](https://linux-hardware.org/?probe=8a798fe917) | Jul 09, 2023 |
| MSI           | Katana GF76 11UE            | [05c77752ce](https://linux-hardware.org/?probe=05c77752ce) | Jul 08, 2023 |
| MSI           | Katana GF76 11UE            | [be128325f8](https://linux-hardware.org/?probe=be128325f8) | Jul 08, 2023 |
| Acer          | Aspire A315-21              | [d6a3964ff7](https://linux-hardware.org/?probe=d6a3964ff7) | Jul 08, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| Acer          | Aspire E5-523G              | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Toshiba       | Satellite C870D-108         | [90207c9016](https://linux-hardware.org/?probe=90207c9016) | Jul 08, 2023 |
| Dell          | Vostro 1720                 | [0bd2fdf8a5](https://linux-hardware.org/?probe=0bd2fdf8a5) | Jul 08, 2023 |
| Sony          | VGN-NS38E_S                 | [eac09b82f8](https://linux-hardware.org/?probe=eac09b82f8) | Jul 07, 2023 |
| Sony          | VGN-NS38E_S                 | [4302a878d3](https://linux-hardware.org/?probe=4302a878d3) | Jul 07, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [25e1dec3b8](https://linux-hardware.org/?probe=25e1dec3b8) | Jul 07, 2023 |
| Thomson       | N15C4SL128                  | [96909a5157](https://linux-hardware.org/?probe=96909a5157) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4200c1e4](https://linux-hardware.org/?probe=0b4200c1e4) | Jul 07, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [702534e040](https://linux-hardware.org/?probe=702534e040) | Jul 07, 2023 |
| Medion        | Erazer P7643 MD60299        | [2c74ffe58f](https://linux-hardware.org/?probe=2c74ffe58f) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| ASUSTek       | K55VJ                       | [cb30ecfbff](https://linux-hardware.org/?probe=cb30ecfbff) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| HP            | 240 G7 Notebook PC          | [9a3f397986](https://linux-hardware.org/?probe=9a3f397986) | Jul 06, 2023 |
| Notebook      | NLx0MU                      | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Timi          | TM1612                      | [843293c28d](https://linux-hardware.org/?probe=843293c28d) | Jul 05, 2023 |
| Thomson       | N15C4SL128                  | [8ba4bb3685](https://linux-hardware.org/?probe=8ba4bb3685) | Jul 05, 2023 |
| Dell          | Latitude 5480               | [ac446902dd](https://linux-hardware.org/?probe=ac446902dd) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a3a67ab04c](https://linux-hardware.org/?probe=a3a67ab04c) | Jul 05, 2023 |
| ASUSTek       | TP300LA                     | [0954f1ace0](https://linux-hardware.org/?probe=0954f1ace0) | Jul 05, 2023 |
| eMachines     | Padus                       | [008b3a48cd](https://linux-hardware.org/?probe=008b3a48cd) | Jul 04, 2023 |
| Samsung       | 950XED                      | [e81ef31b14](https://linux-hardware.org/?probe=e81ef31b14) | Jul 03, 2023 |
| Dell          | Precision 3561              | [c7bd236006](https://linux-hardware.org/?probe=c7bd236006) | Jul 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f14a5888b6](https://linux-hardware.org/?probe=f14a5888b6) | Jul 03, 2023 |
| Dell          | Vostro 1220                 | [293d95dec2](https://linux-hardware.org/?probe=293d95dec2) | Jul 03, 2023 |
| HP            | Pavilion 17                 | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | [aae865deb7](https://linux-hardware.org/?probe=aae865deb7) | Jul 02, 2023 |
| Dell          | Latitude E6320              | [6f9335ddfd](https://linux-hardware.org/?probe=6f9335ddfd) | Jul 02, 2023 |
| Lenovo        | G50-45 80E3                 | [89db1a9656](https://linux-hardware.org/?probe=89db1a9656) | Jul 02, 2023 |
| HP            | Pavilion Gaming Notebook    | [0e9e13c4b5](https://linux-hardware.org/?probe=0e9e13c4b5) | Jul 02, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d703fd9378](https://linux-hardware.org/?probe=d703fd9378) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [b9d71582c0](https://linux-hardware.org/?probe=b9d71582c0) | Jul 01, 2023 |
| MSI           | GF63 Thin 11UC              | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| HP            | Pavilion dv7                | [e10b64716f](https://linux-hardware.org/?probe=e10b64716f) | Jul 01, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [46508a63f2](https://linux-hardware.org/?probe=46508a63f2) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [1cc2f89c1a](https://linux-hardware.org/?probe=1cc2f89c1a) | Jul 01, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| Acer          | Aspire E5-772               | [b33f11c7c9](https://linux-hardware.org/?probe=b33f11c7c9) | Jul 01, 2023 |
| ASUSTek       | K52Dr                       | [f97425ba5f](https://linux-hardware.org/?probe=f97425ba5f) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | [270e8b9fb7](https://linux-hardware.org/?probe=270e8b9fb7) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | [ca33cfbc67](https://linux-hardware.org/?probe=ca33cfbc67) | Jun 30, 2023 |
| HP            | EliteBook 830 G6            | [6c6741deb9](https://linux-hardware.org/?probe=6c6741deb9) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| ASUSTek       | X555LAB                     | [99e1623ea0](https://linux-hardware.org/?probe=99e1623ea0) | Jun 29, 2023 |
| HP            | ProBook 4530s               | [d1c3bf37ff](https://linux-hardware.org/?probe=d1c3bf37ff) | Jun 29, 2023 |
| MSI           | GT70                        | [7471aab8f7](https://linux-hardware.org/?probe=7471aab8f7) | Jun 29, 2023 |
| MSI           | GF75 Thin 9SC               | [1f2cf12e26](https://linux-hardware.org/?probe=1f2cf12e26) | Jun 29, 2023 |
| HP            | Pavilion 17                 | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| Dell          | Precision 3560              | [d7dfa3c472](https://linux-hardware.org/?probe=d7dfa3c472) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | [1025bf4027](https://linux-hardware.org/?probe=1025bf4027) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | [b8453a6830](https://linux-hardware.org/?probe=b8453a6830) | Jun 28, 2023 |
| ASUSTek       | N75SF                       | [eda2a0d726](https://linux-hardware.org/?probe=eda2a0d726) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| Dell          | Latitude E6530              | [f015f73aef](https://linux-hardware.org/?probe=f015f73aef) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | [dae5fc72df](https://linux-hardware.org/?probe=dae5fc72df) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | [c91c09307d](https://linux-hardware.org/?probe=c91c09307d) | Jun 27, 2023 |
| Toshiba       | Satellite L300              | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [465cc8968f](https://linux-hardware.org/?probe=465cc8968f) | Jun 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [3928ad0893](https://linux-hardware.org/?probe=3928ad0893) | Jun 27, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Timi          | TM1613                      | [e6b5bc59c2](https://linux-hardware.org/?probe=e6b5bc59c2) | Jun 26, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [ba30e1369c](https://linux-hardware.org/?probe=ba30e1369c) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L500          | [44e57dc97b](https://linux-hardware.org/?probe=44e57dc97b) | Jun 25, 2023 |
| Notebook      | PCX0DX                      | [d02e6a9fa6](https://linux-hardware.org/?probe=d02e6a9fa6) | Jun 25, 2023 |
| Acer          | Aspire F5-573G              | [b7bbc8246f](https://linux-hardware.org/?probe=b7bbc8246f) | Jun 24, 2023 |
| Dell          | Latitude E6410              | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Dell          | Precision 5510              | [38d61a4475](https://linux-hardware.org/?probe=38d61a4475) | Jun 24, 2023 |
| Toshiba       | Satellite Pro L300          | [96f79c634a](https://linux-hardware.org/?probe=96f79c634a) | Jun 24, 2023 |
| HP            | Pavilion dv7                | [ab7310809d](https://linux-hardware.org/?probe=ab7310809d) | Jun 24, 2023 |
| Toshiba       | Satellite L655              | [6ed0182e96](https://linux-hardware.org/?probe=6ed0182e96) | Jun 24, 2023 |
| Alienware     | 17                          | [63b34ffc64](https://linux-hardware.org/?probe=63b34ffc64) | Jun 24, 2023 |
| Toshiba       | Satellite P200              | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| eMachines     | eMG520                      | [2a33e0b985](https://linux-hardware.org/?probe=2a33e0b985) | Jun 23, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [649bcffd26](https://linux-hardware.org/?probe=649bcffd26) | Jun 23, 2023 |
| Packard Be... | EN Butterfly m              | [70bae75df2](https://linux-hardware.org/?probe=70bae75df2) | Jun 23, 2023 |
| Dell          | Precision 3581              | [2e960d89db](https://linux-hardware.org/?probe=2e960d89db) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [622462c1d1](https://linux-hardware.org/?probe=622462c1d1) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [117e92a397](https://linux-hardware.org/?probe=117e92a397) | Jun 23, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | [762add0eb1](https://linux-hardware.org/?probe=762add0eb1) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| Acer          | Nitro AN515-57              | [fc54744449](https://linux-hardware.org/?probe=fc54744449) | Jun 22, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | [3acd887212](https://linux-hardware.org/?probe=3acd887212) | Jun 21, 2023 |
| Timi          | RedmiBook Pro 14S           | [e6b0f20906](https://linux-hardware.org/?probe=e6b0f20906) | Jun 21, 2023 |
| Dell          | Latitude 5430               | [458a2111da](https://linux-hardware.org/?probe=458a2111da) | Jun 21, 2023 |
| ASUSTek       | K73SD                       | [2dcb7bb5c9](https://linux-hardware.org/?probe=2dcb7bb5c9) | Jun 21, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [386c32d302](https://linux-hardware.org/?probe=386c32d302) | Jun 21, 2023 |
| Dell          | Inspiron 5737               | [a7e4d1a6bd](https://linux-hardware.org/?probe=a7e4d1a6bd) | Jun 21, 2023 |
| Dell          | Latitude E5520              | [4c041a09f6](https://linux-hardware.org/?probe=4c041a09f6) | Jun 20, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [f84ddd7cac](https://linux-hardware.org/?probe=f84ddd7cac) | Jun 20, 2023 |
| HP            | Laptop 14s-dq2xxx           | [68d3aeda15](https://linux-hardware.org/?probe=68d3aeda15) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | [a881db7c2b](https://linux-hardware.org/?probe=a881db7c2b) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | [27bfb2de7d](https://linux-hardware.org/?probe=27bfb2de7d) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Dell          | Inspiron 5415               | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| HP            | Pavilion 17                 | [46ae665800](https://linux-hardware.org/?probe=46ae665800) | Jun 18, 2023 |
| Notebook      | NLx0MU                      | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| Dell          | Latitude 5430               | [7c591ed7d8](https://linux-hardware.org/?probe=7c591ed7d8) | Jun 18, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| HP            | Pavilion 17                 | [f0e1e5aae8](https://linux-hardware.org/?probe=f0e1e5aae8) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | [37b1f672d0](https://linux-hardware.org/?probe=37b1f672d0) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | ProBook 650 G2              | [8dc64586cc](https://linux-hardware.org/?probe=8dc64586cc) | Jun 18, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6fb60cf84a](https://linux-hardware.org/?probe=6fb60cf84a) | Jun 18, 2023 |
| Toshiba       | Satellite Pro L500          | [14765b8284](https://linux-hardware.org/?probe=14765b8284) | Jun 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS4840B     | [a60f1ae93e](https://linux-hardware.org/?probe=a60f1ae93e) | Jun 17, 2023 |
| Dell          | XPS 13 9370                 | [f008a78339](https://linux-hardware.org/?probe=f008a78339) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Gigabyte      | AORUS 15P XC                | [bc59248a6c](https://linux-hardware.org/?probe=bc59248a6c) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| MSI           | GT70                        | [3ccbd6cfb4](https://linux-hardware.org/?probe=3ccbd6cfb4) | Jun 17, 2023 |
| HP            | Laptop 17-bs0xx             | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| Dell          | Precision M2800             | [e9f259595a](https://linux-hardware.org/?probe=e9f259595a) | Jun 17, 2023 |
| Toshiba       | Satellite C870-199          | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [63cf4a0f41](https://linux-hardware.org/?probe=63cf4a0f41) | Jun 16, 2023 |
| HP            | EliteBook 820 G1            | [4c6361a099](https://linux-hardware.org/?probe=4c6361a099) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41d5c8b913](https://linux-hardware.org/?probe=41d5c8b913) | Jun 15, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [67b278ea0e](https://linux-hardware.org/?probe=67b278ea0e) | Jun 15, 2023 |
| Dell          | Precision 5570              | [76bbf6a26f](https://linux-hardware.org/?probe=76bbf6a26f) | Jun 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1858e12df4](https://linux-hardware.org/?probe=1858e12df4) | Jun 15, 2023 |
| MSI           | Modern 14 B10MW             | [c488929cdc](https://linux-hardware.org/?probe=c488929cdc) | Jun 15, 2023 |
| HP            | EliteBook 840 G5            | [a3990bdddb](https://linux-hardware.org/?probe=a3990bdddb) | Jun 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [23a8eeaa23](https://linux-hardware.org/?probe=23a8eeaa23) | Jun 15, 2023 |
| Lenovo        | ThinkPad L420 78545EG       | [bb42ee1009](https://linux-hardware.org/?probe=bb42ee1009) | Jun 14, 2023 |
| ASUSTek       | X541UAK                     | [5540ea0d6f](https://linux-hardware.org/?probe=5540ea0d6f) | Jun 14, 2023 |
| HP            | EliteBook 840 G5            | [ea8e583821](https://linux-hardware.org/?probe=ea8e583821) | Jun 14, 2023 |
| Dell          | Latitude E5570              | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | [40ec446343](https://linux-hardware.org/?probe=40ec446343) | Jun 14, 2023 |
| HP            | ENVY Notebook               | [6e714661f6](https://linux-hardware.org/?probe=6e714661f6) | Jun 14, 2023 |
| MSI           | GT75 Titan 8RG              | [9e25159fb6](https://linux-hardware.org/?probe=9e25159fb6) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Fujitsu       | LIFEBOOK U747               | [aea3f705ed](https://linux-hardware.org/?probe=aea3f705ed) | Jun 13, 2023 |
| HP            | Laptop 17-bs0xx             | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| Samsung       | R540/R538/SA41/E452         | [678c5510d3](https://linux-hardware.org/?probe=678c5510d3) | Jun 13, 2023 |
| Apple         | MacBookAir6,2               | [6a1f1e134c](https://linux-hardware.org/?probe=6a1f1e134c) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [a0b003c3b1](https://linux-hardware.org/?probe=a0b003c3b1) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| Dell          | Precision 7560              | [fc461aad87](https://linux-hardware.org/?probe=fc461aad87) | Jun 12, 2023 |
| HP            | EliteBook 640 14 inch G9... | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Dell          | Latitude 5520               | [f0fc9a8003](https://linux-hardware.org/?probe=f0fc9a8003) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [cacba08c72](https://linux-hardware.org/?probe=cacba08c72) | Jun 11, 2023 |
| Dell          | Precision 5570              | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| NEC Comput... | PC-LM550LS6R                | [695f9825a6](https://linux-hardware.org/?probe=695f9825a6) | Jun 11, 2023 |
| ASUSTek       | X751LD                      | [89aee96c82](https://linux-hardware.org/?probe=89aee96c82) | Jun 10, 2023 |
| Lenovo        | ThinkPad X240 20AMS5XY00    | [3b98c592e0](https://linux-hardware.org/?probe=3b98c592e0) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c768cfa03d](https://linux-hardware.org/?probe=c768cfa03d) | Jun 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Dell          | XPS 13 9370                 | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| Dell          | XPS 9320                    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Dell          | Precision 3551              | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| Dell          | Precision 5510              | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| HP            | EliteBook 840 G3            | [cd3bb98a1e](https://linux-hardware.org/?probe=cd3bb98a1e) | Jun 08, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| MSI           | CreatorPro X17 A12UKS       | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| Dell          | Latitude 5530               | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| MSI           | Crosshair 15 C12VF          | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Acer          | Aspire ES1-711              | [5534470ef5](https://linux-hardware.org/?probe=5534470ef5) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a06e6ab7ad](https://linux-hardware.org/?probe=a06e6ab7ad) | Jun 05, 2023 |
| ASUSTek       | G750JM                      | [cdb3539c93](https://linux-hardware.org/?probe=cdb3539c93) | Jun 05, 2023 |
| ASUSTek       | K95VJ                       | [9bbcec82c6](https://linux-hardware.org/?probe=9bbcec82c6) | Jun 05, 2023 |
| ASUSTek       | UX303UA                     | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Jumper        | EZbook                      | [950179fe29](https://linux-hardware.org/?probe=950179fe29) | Jun 04, 2023 |
| Toshiba       | Satellite L655              | [1b9656a4a1](https://linux-hardware.org/?probe=1b9656a4a1) | Jun 04, 2023 |
| ASUSTek       | G750JM                      | [f492ab6829](https://linux-hardware.org/?probe=f492ab6829) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| IP3 Tech      | AP1                         | [d24ecf10e2](https://linux-hardware.org/?probe=d24ecf10e2) | Jun 04, 2023 |
| Toshiba       | Satellite Pro L300          | [968005c798](https://linux-hardware.org/?probe=968005c798) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| Samsung       | 950XED                      | [185834c02e](https://linux-hardware.org/?probe=185834c02e) | Jun 04, 2023 |
| Schenker      | XMG FOCUS (M22)             | [31203c3645](https://linux-hardware.org/?probe=31203c3645) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Toshiba       | Satellite L655              | [9b83a4575b](https://linux-hardware.org/?probe=9b83a4575b) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Valve         | Jupiter                     | [d1fec35ece](https://linux-hardware.org/?probe=d1fec35ece) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d170e024e](https://linux-hardware.org/?probe=4d170e024e) | Jun 02, 2023 |
| Acer          | Aspire 7745G                | [7739f949e1](https://linux-hardware.org/?probe=7739f949e1) | Jun 02, 2023 |
| UNOWHY        | Y13G002S4EI                 | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| ASUSTek       | X751MA                      | [1b1a5c05ac](https://linux-hardware.org/?probe=1b1a5c05ac) | Jun 01, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [3ca0d2f1a7](https://linux-hardware.org/?probe=3ca0d2f1a7) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Acer          | Aspire 3830TG               | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Packard Be... | EasyNote LJ75               | [95c733d00f](https://linux-hardware.org/?probe=95c733d00f) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| MSI           | GE70 2QE                    | [a075b8b77d](https://linux-hardware.org/?probe=a075b8b77d) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| Dell          | Inspiron 3502               | [3c734d2900](https://linux-hardware.org/?probe=3c734d2900) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| Acer          | Aspire V3-574G              | [728459dd4a](https://linux-hardware.org/?probe=728459dd4a) | May 30, 2023 |
| Samsung       | R610                        | [4e3be533ba](https://linux-hardware.org/?probe=4e3be533ba) | May 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [86e04155f2](https://linux-hardware.org/?probe=86e04155f2) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [509bb7aae7](https://linux-hardware.org/?probe=509bb7aae7) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| Acer          | Aspire E5-772G              | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Dell          | XPS 9320                    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| Shuttle       | X50V5                       | [277cc7ca36](https://linux-hardware.org/?probe=277cc7ca36) | May 28, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [d62f60891d](https://linux-hardware.org/?probe=d62f60891d) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Dell          | Precision 3581              | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Dell          | Inspiron 5567               | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [efe0b55153](https://linux-hardware.org/?probe=efe0b55153) | May 27, 2023 |
| Dell          | Latitude 3520               | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| Dell          | G15 5510                    | [f9e862a5dd](https://linux-hardware.org/?probe=f9e862a5dd) | May 26, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [d86873ceab](https://linux-hardware.org/?probe=d86873ceab) | May 26, 2023 |
| Toshiba       | Satellite L300              | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| ASUSTek       | N75SF                       | [38840055c8](https://linux-hardware.org/?probe=38840055c8) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ab42ac444e](https://linux-hardware.org/?probe=ab42ac444e) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| ASUSTek       | K55VJ                       | [2b12b33767](https://linux-hardware.org/?probe=2b12b33767) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| HP            | Laptop 17-by3xxx            | [dcafbb2a69](https://linux-hardware.org/?probe=dcafbb2a69) | May 23, 2023 |
| HP            | Laptop 17-by3xxx            | [cbe27885cb](https://linux-hardware.org/?probe=cbe27885cb) | May 23, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| HP            | ProBook 450 G3              | [4400f1205b](https://linux-hardware.org/?probe=4400f1205b) | May 23, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| HP            | Pavilion 17                 | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| ASUSTek       | K73SD                       | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| ASUSTek       | UX301LAB                    | [69f7b4ae4f](https://linux-hardware.org/?probe=69f7b4ae4f) | May 22, 2023 |
| HUAWEI        | HLYL-WXX9                   | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| Dell          | Latitude E4200              | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| HP            | ProBook 4310s               | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| MSI           | PS63 Modern 8MO             | [5d6f78bfbb](https://linux-hardware.org/?probe=5d6f78bfbb) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| ASUSTek       | G752VY                      | [2762dac255](https://linux-hardware.org/?probe=2762dac255) | May 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [32e623c724](https://linux-hardware.org/?probe=32e623c724) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Toshiba       | Satellite P300              | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c5fee7bb50](https://linux-hardware.org/?probe=c5fee7bb50) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [c1089ff84e](https://linux-hardware.org/?probe=c1089ff84e) | May 20, 2023 |
| Dell          | Precision 5470              | [e600af2d5a](https://linux-hardware.org/?probe=e600af2d5a) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [73aafcfb9c](https://linux-hardware.org/?probe=73aafcfb9c) | May 19, 2023 |
| ASUSTek       | F7Se                        | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Toshiba       | PORTEGE Z830                | [f4548ca81b](https://linux-hardware.org/?probe=f4548ca81b) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| HP            | Compaq Presario CQ60        | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| Dell          | Precision 5520              | [6e4c751579](https://linux-hardware.org/?probe=6e4c751579) | May 18, 2023 |
| HP            | ProBook 4310s               | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| Dell          | Latitude 7490               | [392cde1432](https://linux-hardware.org/?probe=392cde1432) | May 17, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [baa1b942cf](https://linux-hardware.org/?probe=baa1b942cf) | May 17, 2023 |
| Dell          | Inspiron 5580               | [7ced5f9473](https://linux-hardware.org/?probe=7ced5f9473) | May 17, 2023 |
| Acer          | TravelMate X514-51          | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Acer          | Aspire 5742G                | [04a6fe63c1](https://linux-hardware.org/?probe=04a6fe63c1) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| SLIMBOOK      | Executive                   | [0a70f31ce9](https://linux-hardware.org/?probe=0a70f31ce9) | May 16, 2023 |
| Dell          | Precision 5530              | [16366ef886](https://linux-hardware.org/?probe=16366ef886) | May 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [05441101a8](https://linux-hardware.org/?probe=05441101a8) | May 16, 2023 |
| Lenovo        | ThinkPad T440 20B7S1MF0D    | [6173458650](https://linux-hardware.org/?probe=6173458650) | May 16, 2023 |
| ASUSTek       | T100TA                      | [050d9ad83f](https://linux-hardware.org/?probe=050d9ad83f) | May 16, 2023 |
| Toshiba       | Satellite L655              | [2fa63538ef](https://linux-hardware.org/?probe=2fa63538ef) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| Sony          | VPCF11M1E                   | [b42c56ac73](https://linux-hardware.org/?probe=b42c56ac73) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | [572b403a00](https://linux-hardware.org/?probe=572b403a00) | May 14, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [d200313f91](https://linux-hardware.org/?probe=d200313f91) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | [0b0cc4f60e](https://linux-hardware.org/?probe=0b0cc4f60e) | May 14, 2023 |
| HP            | EliteBook 8560w             | [d8735e3006](https://linux-hardware.org/?probe=d8735e3006) | May 14, 2023 |
| ASUSTek       | K55VJ                       | [bf3ff003f9](https://linux-hardware.org/?probe=bf3ff003f9) | May 14, 2023 |
| HP            | EliteBook 8560w             | [ffe7a5c97b](https://linux-hardware.org/?probe=ffe7a5c97b) | May 14, 2023 |
| HP            | Notebook                    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| Dell          | Latitude E5420              | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| AMI           | Intel                       | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [0f3a2fae1b](https://linux-hardware.org/?probe=0f3a2fae1b) | May 13, 2023 |
| Dell          | Latitude 7490               | [16cfe08da3](https://linux-hardware.org/?probe=16cfe08da3) | May 13, 2023 |
| Jumper        | EZbook                      | [56321a4f9c](https://linux-hardware.org/?probe=56321a4f9c) | May 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ef37458c10](https://linux-hardware.org/?probe=ef37458c10) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [804de32208](https://linux-hardware.org/?probe=804de32208) | May 13, 2023 |
| MSI           | GL73 8RC                    | [4eb76264f2](https://linux-hardware.org/?probe=4eb76264f2) | May 12, 2023 |
| ASUSTek       | X411UA                      | [bd54bb7c02](https://linux-hardware.org/?probe=bd54bb7c02) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Precision 5550              | [f6d4846655](https://linux-hardware.org/?probe=f6d4846655) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| HP            | Stream Notebook             | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Medion        | Crawler E40                 | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| Medion        | Crawler E40                 | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Dell          | Latitude 7400               | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a1cb5cae49](https://linux-hardware.org/?probe=a1cb5cae49) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Apple         | MacBookPro6,2               | [f56ecb2642](https://linux-hardware.org/?probe=f56ecb2642) | May 11, 2023 |
| Dell          | Latitude E4310              | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| ASUSTek       | X411UA                      | [bc27160391](https://linux-hardware.org/?probe=bc27160391) | May 10, 2023 |
| Toshiba       | Satellite C660D             | [0337ec13a6](https://linux-hardware.org/?probe=0337ec13a6) | May 10, 2023 |
| Dell          | Precision 5520              | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [7df7ca9fbf](https://linux-hardware.org/?probe=7df7ca9fbf) | May 10, 2023 |
| ASUSTek       | X550CC                      | [4d0b606423](https://linux-hardware.org/?probe=4d0b606423) | May 10, 2023 |
| HP            | Presario CQ62               | [7619e0cff9](https://linux-hardware.org/?probe=7619e0cff9) | May 10, 2023 |
| Sony          | SVE1713K1EB                 | [96244b73e7](https://linux-hardware.org/?probe=96244b73e7) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Notebook      | N150ZU                      | [bfd69adf4e](https://linux-hardware.org/?probe=bfd69adf4e) | May 10, 2023 |
| Thomson       | N14C64WF                    | [4e5a5f6e51](https://linux-hardware.org/?probe=4e5a5f6e51) | May 10, 2023 |
| Dell          | G5 5590                     | [c07c29d5de](https://linux-hardware.org/?probe=c07c29d5de) | May 09, 2023 |
| Apple         | MacBookPro6,2               | [db93afa653](https://linux-hardware.org/?probe=db93afa653) | May 09, 2023 |
| ASUSTek       | X200MA                      | [1f7840b315](https://linux-hardware.org/?probe=1f7840b315) | May 08, 2023 |
| Acer          | Swift SFA16-41              | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [4c3f70e8d3](https://linux-hardware.org/?probe=4c3f70e8d3) | May 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dc97e2fc43](https://linux-hardware.org/?probe=dc97e2fc43) | May 08, 2023 |
| Acer          | Aspire 7741                 | [995e6d9580](https://linux-hardware.org/?probe=995e6d9580) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| HP            | EliteBook 725 G4            | [bf3ce4741e](https://linux-hardware.org/?probe=bf3ce4741e) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [ea808c2e80](https://linux-hardware.org/?probe=ea808c2e80) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f4d1f788e1](https://linux-hardware.org/?probe=f4d1f788e1) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [382b81c0d1](https://linux-hardware.org/?probe=382b81c0d1) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | [395097d3a3](https://linux-hardware.org/?probe=395097d3a3) | May 08, 2023 |
| Acer          | Aspire V3-772G              | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| HP            | EliteBook 840 G5            | [48d87e5c6e](https://linux-hardware.org/?probe=48d87e5c6e) | May 08, 2023 |
| Sony          | VPCZ12C5E                   | [512da95fb0](https://linux-hardware.org/?probe=512da95fb0) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| Dell          | Precision 5510              | [9a4ba61d41](https://linux-hardware.org/?probe=9a4ba61d41) | May 07, 2023 |
| Dell          | MXG061                      | [8ef701b61d](https://linux-hardware.org/?probe=8ef701b61d) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [99ede66d8d](https://linux-hardware.org/?probe=99ede66d8d) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [816f9e047a](https://linux-hardware.org/?probe=816f9e047a) | May 07, 2023 |
| MSI           | Katana GF66 11UE            | [e69f8169fc](https://linux-hardware.org/?probe=e69f8169fc) | May 07, 2023 |
| Lenovo        | ThinkPad SL500 27464DG      | [f2bb35c6d3](https://linux-hardware.org/?probe=f2bb35c6d3) | May 07, 2023 |
| Sony          | VPCZ12C5E                   | [67e1fdf9c2](https://linux-hardware.org/?probe=67e1fdf9c2) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Valve         | Jupiter                     | [270eaa3e12](https://linux-hardware.org/?probe=270eaa3e12) | May 07, 2023 |
| HP            | Presario CQ57               | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Alienware     | 18                          | [4c6abf91cd](https://linux-hardware.org/?probe=4c6abf91cd) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| Dell          | Precision 7550              | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| Acer          | Aspire 7720                 | [e28510b64d](https://linux-hardware.org/?probe=e28510b64d) | May 06, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| Notebook      | N7x0WU                      | [985f971691](https://linux-hardware.org/?probe=985f971691) | May 06, 2023 |
| ASUSTek       | Strix GL504GS_GL504GS       | [cdb842cc09](https://linux-hardware.org/?probe=cdb842cc09) | May 06, 2023 |
| Acer          | NC-V3-772G-747A8G1TMAKK     | [58f420d816](https://linux-hardware.org/?probe=58f420d816) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| Acer          | Aspire E5-571G              | [4b45fabd96](https://linux-hardware.org/?probe=4b45fabd96) | May 05, 2023 |
| Acer          | Aspire 7720                 | [2e216b0830](https://linux-hardware.org/?probe=2e216b0830) | May 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS46900    | [523dce6a6d](https://linux-hardware.org/?probe=523dce6a6d) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| eMachines     | eMG620                      | [224dc7209e](https://linux-hardware.org/?probe=224dc7209e) | May 04, 2023 |
| Dell          | Latitude 7490               | [65d9b877b5](https://linux-hardware.org/?probe=65d9b877b5) | May 04, 2023 |
| Dell          | Latitude 7490               | [383b9d3aec](https://linux-hardware.org/?probe=383b9d3aec) | May 04, 2023 |
| Dell          | XPS 15 9550                 | [e31c30bd52](https://linux-hardware.org/?probe=e31c30bd52) | May 04, 2023 |
| ASUSTek       | K61IC                       | [727b9fae92](https://linux-hardware.org/?probe=727b9fae92) | May 03, 2023 |
| Notebook      | N7x0WU                      | [b11821f4a1](https://linux-hardware.org/?probe=b11821f4a1) | May 03, 2023 |
| HP            | Unknown                     | [b99510884b](https://linux-hardware.org/?probe=b99510884b) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| HP            | Pavilion dm4                | [cb567d8263](https://linux-hardware.org/?probe=cb567d8263) | May 03, 2023 |
| UNOWHY        | Y13G011S4EI                 | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| HP            | OMEN by Laptop              | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| Notebook      | NS5x_NS7xPU                 | [ee97e0f5f0](https://linux-hardware.org/?probe=ee97e0f5f0) | May 01, 2023 |
| ASUSTek       | ZenBook UX535LI             | [35adc352dd](https://linux-hardware.org/?probe=35adc352dd) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| Sony          | VGN-AW11M_H                 | [2c9f98ca31](https://linux-hardware.org/?probe=2c9f98ca31) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Valve         | Jupiter                     | [3bee1a3271](https://linux-hardware.org/?probe=3bee1a3271) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [2dd85470a0](https://linux-hardware.org/?probe=2dd85470a0) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | [00fbe71b59](https://linux-hardware.org/?probe=00fbe71b59) | Apr 30, 2023 |
| Samsung       | 950XED                      | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | EliteBook 840 G1            | [6f4c134615](https://linux-hardware.org/?probe=6f4c134615) | Apr 29, 2023 |
| Sony          | VPCF11M1E                   | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| MSI           | P65 Creator 9SF             | [4e682b2c20](https://linux-hardware.org/?probe=4e682b2c20) | Apr 29, 2023 |
| Acer          | Aspire E5-722               | [d02052aeab](https://linux-hardware.org/?probe=d02052aeab) | Apr 29, 2023 |
| Dell          | XPS 13 9310                 | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [09d6d7e570](https://linux-hardware.org/?probe=09d6d7e570) | Apr 28, 2023 |
| Lenovo        | ThinkPad L560 20F2S13L00    | [7695cef903](https://linux-hardware.org/?probe=7695cef903) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Dell          | Precision 3551              | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Dell          | Precision 3551              | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [990335263d](https://linux-hardware.org/?probe=990335263d) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| Dell          | Latitude E7270              | [5bacf4eea3](https://linux-hardware.org/?probe=5bacf4eea3) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| HP            | Pavilion g6                 | [716373f59a](https://linux-hardware.org/?probe=716373f59a) | Apr 27, 2023 |
| Timi          | TM1703                      | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| ASUSTek       | K73BR                       | [547b19cd2c](https://linux-hardware.org/?probe=547b19cd2c) | Apr 26, 2023 |
| Dell          | Latitude 5430               | [75ac9d10bf](https://linux-hardware.org/?probe=75ac9d10bf) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| LDLC          | SPC-I                       | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| Samsung       | 950XED                      | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Sony          | VPCEH3U1E                   | [6fa28ef21c](https://linux-hardware.org/?probe=6fa28ef21c) | Apr 23, 2023 |
| HP            | ProBook 6570b               | [4e2ba781e2](https://linux-hardware.org/?probe=4e2ba781e2) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [b4dfa57eea](https://linux-hardware.org/?probe=b4dfa57eea) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [1a45f96f80](https://linux-hardware.org/?probe=1a45f96f80) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Acer          | Swift SF314-42              | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9a6f040039](https://linux-hardware.org/?probe=9a6f040039) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [77a309dcf1](https://linux-hardware.org/?probe=77a309dcf1) | Apr 22, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [4c60675864](https://linux-hardware.org/?probe=4c60675864) | Apr 22, 2023 |
| Dell          | XPS 13 9333                 | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| Apple         | MacBookPro11,5              | [7a873a7baa](https://linux-hardware.org/?probe=7a873a7baa) | Apr 22, 2023 |
| MSI           | Prestige 15 A10SC           | [f64336848a](https://linux-hardware.org/?probe=f64336848a) | Apr 22, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Compal        | HEL81I                      | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Dell          | Precision 5510              | [94b5586a2c](https://linux-hardware.org/?probe=94b5586a2c) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | [f813e87465](https://linux-hardware.org/?probe=f813e87465) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | [53951da2d7](https://linux-hardware.org/?probe=53951da2d7) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [acbe851404](https://linux-hardware.org/?probe=acbe851404) | Apr 21, 2023 |
| PC Special... | TN1-156M                    | [ef6b57e807](https://linux-hardware.org/?probe=ef6b57e807) | Apr 21, 2023 |
| HP            | Notebook                    | [150b1d6ae7](https://linux-hardware.org/?probe=150b1d6ae7) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| Valve         | Jupiter                     | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| ASUSTek       | K61IC                       | [985a269b26](https://linux-hardware.org/?probe=985a269b26) | Apr 20, 2023 |
| MSI           | CR61 3M                     | [0ee98cd841](https://linux-hardware.org/?probe=0ee98cd841) | Apr 20, 2023 |
| Acer          | TravelMate 5320             | [fa41e30258](https://linux-hardware.org/?probe=fa41e30258) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| ASUSTek       | G771JW                      | [fd6d8a7cd7](https://linux-hardware.org/?probe=fd6d8a7cd7) | Apr 20, 2023 |
| Acer          | Aspire 5738                 | [fc12fc0a9d](https://linux-hardware.org/?probe=fc12fc0a9d) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| PC Special... | NV4XMB,ME,MZ                | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| ASUSTek       | X751BP                      | [0bea82acba](https://linux-hardware.org/?probe=0bea82acba) | Apr 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [ec0532e3e3](https://linux-hardware.org/?probe=ec0532e3e3) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| ASUSTek       | K55A                        | [99fe712761](https://linux-hardware.org/?probe=99fe712761) | Apr 17, 2023 |
| ASUSTek       | UX303LB                     | [48c19abe8c](https://linux-hardware.org/?probe=48c19abe8c) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d12e0064fc](https://linux-hardware.org/?probe=d12e0064fc) | Apr 17, 2023 |
| HP            | Pavilion 17                 | [b06b49ac95](https://linux-hardware.org/?probe=b06b49ac95) | Apr 17, 2023 |
| Dell          | Precision 3571              | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f3a91915df](https://linux-hardware.org/?probe=f3a91915df) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4296a1241d](https://linux-hardware.org/?probe=4296a1241d) | Apr 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| ASUSTek       | K53BE                       | [f21e7219ce](https://linux-hardware.org/?probe=f21e7219ce) | Apr 16, 2023 |
| Dell          | Vostro 15 7510              | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [da62023f35](https://linux-hardware.org/?probe=da62023f35) | Apr 15, 2023 |
| Dell          | Latitude E5520              | [5e04eeccae](https://linux-hardware.org/?probe=5e04eeccae) | Apr 15, 2023 |
| ASUSTek       | G771JW                      | [f534984150](https://linux-hardware.org/?probe=f534984150) | Apr 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0e89a3c19b](https://linux-hardware.org/?probe=0e89a3c19b) | Apr 15, 2023 |
| ASUSTek       | X540YA                      | [8de126d84d](https://linux-hardware.org/?probe=8de126d84d) | Apr 15, 2023 |
| ASUSTek       | X302LJ                      | [e045b269b1](https://linux-hardware.org/?probe=e045b269b1) | Apr 14, 2023 |
| Toshiba       | Satellite L655              | [c3c64a7016](https://linux-hardware.org/?probe=c3c64a7016) | Apr 14, 2023 |
| HP            | ProBook 640 G1              | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| HP            | ProBook 6570b               | [af45cce5b8](https://linux-hardware.org/?probe=af45cce5b8) | Apr 14, 2023 |
| Dell          | Inspiron 15 3511            | [6cfca82c2f](https://linux-hardware.org/?probe=6cfca82c2f) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| HP            | Pavilion dv6                | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b223f5fbf1](https://linux-hardware.org/?probe=b223f5fbf1) | Apr 13, 2023 |
| Dell          | G15 5510                    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| Dell          | XPS L322X                   | [cbf247e5a6](https://linux-hardware.org/?probe=cbf247e5a6) | Apr 13, 2023 |
| HP            | Pavilion TS 15              | [43b322dcf3](https://linux-hardware.org/?probe=43b322dcf3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Dell          | Precision 3571              | [e6e8267b6a](https://linux-hardware.org/?probe=e6e8267b6a) | Apr 12, 2023 |
| Dell          | Latitude 5420               | [248e22982d](https://linux-hardware.org/?probe=248e22982d) | Apr 12, 2023 |
| Dell          | Precision 7520              | [1d23894711](https://linux-hardware.org/?probe=1d23894711) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [905a2aee02](https://linux-hardware.org/?probe=905a2aee02) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| MSI           | GP72MVR 7RFX                | [17f60a29f5](https://linux-hardware.org/?probe=17f60a29f5) | Apr 11, 2023 |
| Valve         | Jupiter                     | [32bf664d90](https://linux-hardware.org/?probe=32bf664d90) | Apr 11, 2023 |
| HP            | Pavilion g6                 | [f4190d2c4e](https://linux-hardware.org/?probe=f4190d2c4e) | Apr 11, 2023 |
| ASUSTek       | UX303UA                     | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Gigabyte      | X7X7                        | [8f58573ff3](https://linux-hardware.org/?probe=8f58573ff3) | Apr 11, 2023 |
| MSI           | Prestige 14Evo B13M         | [a3967e84ad](https://linux-hardware.org/?probe=a3967e84ad) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| ASUSTek       | G751JY                      | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [704f5bcf78](https://linux-hardware.org/?probe=704f5bcf78) | Apr 10, 2023 |
| Sony          | VPCEB1M1E                   | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe939f268b](https://linux-hardware.org/?probe=fe939f268b) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [955a648772](https://linux-hardware.org/?probe=955a648772) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| Apple         | MacBook3,1                  | [ee2678d76f](https://linux-hardware.org/?probe=ee2678d76f) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| ASUSTek       | X756UQ                      | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12faf271f6](https://linux-hardware.org/?probe=12faf271f6) | Apr 08, 2023 |
| ASUSTek       | X751LN                      | [8bf4f37814](https://linux-hardware.org/?probe=8bf4f37814) | Apr 08, 2023 |
| HP            | ENVY dv6                    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| Acer          | Nitro AN517-54              | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Dell          | G3 3500                     | [cae0e09f03](https://linux-hardware.org/?probe=cae0e09f03) | Apr 07, 2023 |
| Dell          | G3 3500                     | [9f77f9158a](https://linux-hardware.org/?probe=9f77f9158a) | Apr 07, 2023 |
| HP            | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | S551LN                      | [2c731aefae](https://linux-hardware.org/?probe=2c731aefae) | Apr 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| MSI           | GL73 8RC                    | [c134ae92fc](https://linux-hardware.org/?probe=c134ae92fc) | Apr 06, 2023 |
| HP            | Sona                        | [64fa63647b](https://linux-hardware.org/?probe=64fa63647b) | Apr 06, 2023 |
| Dell          | Precision 7560              | [b474fb4429](https://linux-hardware.org/?probe=b474fb4429) | Apr 06, 2023 |
| ASUSTek       | S551LN                      | [bab2c0f0e4](https://linux-hardware.org/?probe=bab2c0f0e4) | Apr 06, 2023 |
| Dell          | Latitude E7470              | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| Acer          | Aspire E1-570               | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [5d0489d439](https://linux-hardware.org/?probe=5d0489d439) | Apr 05, 2023 |
| Toshiba       | Satellite C855D-12J         | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| HP            | Notebook                    | [99a9d4cae5](https://linux-hardware.org/?probe=99a9d4cae5) | Apr 05, 2023 |
| System76      | Lemur Pro                   | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| ASUSTek       | X71Q                        | [9a7d0f4b2b](https://linux-hardware.org/?probe=9a7d0f4b2b) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| Valve         | Jupiter                     | [2d32794500](https://linux-hardware.org/?probe=2d32794500) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [f04b34af52](https://linux-hardware.org/?probe=f04b34af52) | Apr 04, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [fa9fe4337a](https://linux-hardware.org/?probe=fa9fe4337a) | Apr 04, 2023 |
| Valve         | Jupiter                     | [9ef9150c8c](https://linux-hardware.org/?probe=9ef9150c8c) | Apr 04, 2023 |
| MSI           | PS42 Modern 8MO             | [60633671a2](https://linux-hardware.org/?probe=60633671a2) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [ceeafa59a2](https://linux-hardware.org/?probe=ceeafa59a2) | Apr 04, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [ec6a09a6ba](https://linux-hardware.org/?probe=ec6a09a6ba) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [1dbae9d685](https://linux-hardware.org/?probe=1dbae9d685) | Apr 04, 2023 |
| Dell          | XPS 15 9520                 | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | GL553VD                     | [1978d77ba2](https://linux-hardware.org/?probe=1978d77ba2) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | [ef04e5d464](https://linux-hardware.org/?probe=ef04e5d464) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | [f9eb684250](https://linux-hardware.org/?probe=f9eb684250) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [661283d296](https://linux-hardware.org/?probe=661283d296) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3c10c8c51a](https://linux-hardware.org/?probe=3c10c8c51a) | Apr 03, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [49b1cef736](https://linux-hardware.org/?probe=49b1cef736) | Apr 03, 2023 |
| HP            | Pavilion 17                 | [487bc77c07](https://linux-hardware.org/?probe=487bc77c07) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1c15668c5d](https://linux-hardware.org/?probe=1c15668c5d) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Dell          | Inspiron 7577               | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Sony          | SVF1521A6EW                 | [e382f0f4f1](https://linux-hardware.org/?probe=e382f0f4f1) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [892ffd1727](https://linux-hardware.org/?probe=892ffd1727) | Apr 02, 2023 |
| HP            | Laptop 17-ca0xxx            | [6399f19b22](https://linux-hardware.org/?probe=6399f19b22) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Notebook      | P15SM                       | [070f808c28](https://linux-hardware.org/?probe=070f808c28) | Apr 02, 2023 |
| ASUSTek       | G71V                        | [6594dac071](https://linux-hardware.org/?probe=6594dac071) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0941828bd0](https://linux-hardware.org/?probe=0941828bd0) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [95c5f574c9](https://linux-hardware.org/?probe=95c5f574c9) | Apr 01, 2023 |
| Lenovo        | ThinkPad L560 20F2S1AJ00    | [8987605dde](https://linux-hardware.org/?probe=8987605dde) | Apr 01, 2023 |
| Valve         | Jupiter                     | [f9083bca8d](https://linux-hardware.org/?probe=f9083bca8d) | Apr 01, 2023 |
| Google        | Lulu                        | [0183eadbc8](https://linux-hardware.org/?probe=0183eadbc8) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| ASUSTek       | N752VX                      | [d426499408](https://linux-hardware.org/?probe=d426499408) | Apr 01, 2023 |
| HP            | Presario CQ58               | [e8f8f289ac](https://linux-hardware.org/?probe=e8f8f289ac) | Apr 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [87bc2601f3](https://linux-hardware.org/?probe=87bc2601f3) | Apr 01, 2023 |
| ASUSTek       | S551LN                      | [916adbdf9f](https://linux-hardware.org/?probe=916adbdf9f) | Apr 01, 2023 |
| Acer          | Aspire 7720                 | [073d49ce6b](https://linux-hardware.org/?probe=073d49ce6b) | Mar 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Acer          | Nitro AN515-54              | [9e7aa15a9f](https://linux-hardware.org/?probe=9e7aa15a9f) | Mar 31, 2023 |
| Notebook      | NL40_50GU                   | [a46afd7246](https://linux-hardware.org/?probe=a46afd7246) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| Apple         | MacBookAir7,2               | [d9cbbe0a35](https://linux-hardware.org/?probe=d9cbbe0a35) | Mar 30, 2023 |
| Dell          | Precision 5510              | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0f8c22b288](https://linux-hardware.org/?probe=0f8c22b288) | Mar 30, 2023 |
| ASUSTek       | K55A                        | [cf40bdccfc](https://linux-hardware.org/?probe=cf40bdccfc) | Mar 30, 2023 |
| ASUSTek       | K55A                        | [b6c168d185](https://linux-hardware.org/?probe=b6c168d185) | Mar 30, 2023 |
| Lenovo        | V15-ADA 82C7                | [552ad08e05](https://linux-hardware.org/?probe=552ad08e05) | Mar 30, 2023 |
| Sony          | SVF1521C2EW                 | [978ae8afac](https://linux-hardware.org/?probe=978ae8afac) | Mar 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [0f273e6227](https://linux-hardware.org/?probe=0f273e6227) | Mar 30, 2023 |
| Lenovo        | G700 20251                  | [7580b631a9](https://linux-hardware.org/?probe=7580b631a9) | Mar 29, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [5c65763b9d](https://linux-hardware.org/?probe=5c65763b9d) | Mar 29, 2023 |
| Lenovo        | U41-70 80JV                 | [975da67142](https://linux-hardware.org/?probe=975da67142) | Mar 29, 2023 |
| HP            | Laptop 17-by0xxx            | [89a0332dfd](https://linux-hardware.org/?probe=89a0332dfd) | Mar 29, 2023 |
| HP            | EliteBook 8770w             | [46a3f1d497](https://linux-hardware.org/?probe=46a3f1d497) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [11c94aa91b](https://linux-hardware.org/?probe=11c94aa91b) | Mar 29, 2023 |
| Toshiba       | Satellite P200              | [c55a4d3166](https://linux-hardware.org/?probe=c55a4d3166) | Mar 29, 2023 |
| Notebook      | NL40_50CU                   | [fe471635fb](https://linux-hardware.org/?probe=fe471635fb) | Mar 29, 2023 |
| Dell          | Vostro 5568                 | [0004be15a4](https://linux-hardware.org/?probe=0004be15a4) | Mar 28, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| HP            | Compaq 6510b (GR680ET)      | [716c4212c7](https://linux-hardware.org/?probe=716c4212c7) | Mar 28, 2023 |
| Lenovo        | V145-15AST 81MT             | [7fff3bb217](https://linux-hardware.org/?probe=7fff3bb217) | Mar 28, 2023 |
| Acer          | Aspire E5-532G              | [35e076d9b5](https://linux-hardware.org/?probe=35e076d9b5) | Mar 28, 2023 |
| ASUSTek       | N61Jq                       | [0ca1f04770](https://linux-hardware.org/?probe=0ca1f04770) | Mar 28, 2023 |
| Sony          | SVF1521C2EW                 | [2bafb0a0e4](https://linux-hardware.org/?probe=2bafb0a0e4) | Mar 28, 2023 |
| HP            | Laptop 14s-fq2xxx           | [8b64ddb550](https://linux-hardware.org/?probe=8b64ddb550) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [08627c5990](https://linux-hardware.org/?probe=08627c5990) | Mar 27, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Acer          | Aspire 4820TG               | [e634227889](https://linux-hardware.org/?probe=e634227889) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c3dbea760e](https://linux-hardware.org/?probe=c3dbea760e) | Mar 26, 2023 |
| ASUSTek       | K50IE                       | [bde872583b](https://linux-hardware.org/?probe=bde872583b) | Mar 26, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| ASUSTek       | X75VD                       | [9997ce4485](https://linux-hardware.org/?probe=9997ce4485) | Mar 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [f9c5ae93de](https://linux-hardware.org/?probe=f9c5ae93de) | Mar 26, 2023 |
| Fujitsu Si... | AMILO Pi 3625               | [076352cb68](https://linux-hardware.org/?probe=076352cb68) | Mar 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [414c36eb9d](https://linux-hardware.org/?probe=414c36eb9d) | Mar 26, 2023 |
| Valve         | Jupiter                     | [b7c75f2713](https://linux-hardware.org/?probe=b7c75f2713) | Mar 26, 2023 |
| Dell          | Latitude 5520               | [47372d09fe](https://linux-hardware.org/?probe=47372d09fe) | Mar 25, 2023 |
| Dell          | Latitude 5520               | [0c69ef5724](https://linux-hardware.org/?probe=0c69ef5724) | Mar 25, 2023 |
| Packard Be... | EasyNote SB65               | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [22aa7f3036](https://linux-hardware.org/?probe=22aa7f3036) | Mar 25, 2023 |
| Dell          | XPS 9315                    | [050fede003](https://linux-hardware.org/?probe=050fede003) | Mar 25, 2023 |
| Toshiba       | KIRA                        | [e96de49ce8](https://linux-hardware.org/?probe=e96de49ce8) | Mar 25, 2023 |
| HP            | ProBook 645 G4              | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 983       | 17.08%  |
| Ubuntu 22.04       | 439       | 7.63%   |
| Ubuntu 18.04       | 311       | 5.4%    |
| Debian 11          | 216       | 3.75%   |
| OpenMandriva 4.2   | 178       | 3.09%   |
| OpenMandriva 4.3   | 154       | 2.68%   |
| Linux Mint 20.3    | 126       | 2.19%   |
| Xubuntu 20.04      | 108       | 1.88%   |
| Arch Rolling       | 100       | 1.74%   |
| Linux Mint 21.1    | 86        | 1.49%   |
| Arch               | 80        | 1.39%   |
| OpenMandriva 23.01 | 75        | 1.3%    |
| Ubuntu 21.10       | 71        | 1.23%   |
| Debian 10          | 69        | 1.2%    |
| Zorin 16           | 66        | 1.15%   |
| Linux Mint 20.2    | 65        | 1.13%   |
| Ubuntu 19.10       | 59        | 1.03%   |
| OpenMandriva 23.03 | 59        | 1.03%   |
| Ubuntu 21.04       | 57        | 0.99%   |
| Manjaro            | 55        | 0.96%   |
| Ubuntu 20.10       | 53        | 0.92%   |
| Pop!_OS 22.04      | 50        | 0.87%   |
| Linux Mint 19.3    | 50        | 0.87%   |
| Xubuntu 18.04      | 49        | 0.85%   |
| Fedora 33          | 49        | 0.85%   |
| Ubuntu 22.10       | 47        | 0.82%   |
| Linux Mint 21      | 47        | 0.82%   |
| Fedora 37          | 47        | 0.82%   |
| Fedora 34          | 45        | 0.78%   |
| Fedora 38          | 44        | 0.76%   |
| Linux Mint 20.1    | 43        | 0.75%   |
| Xubuntu 22.04      | 42        | 0.73%   |
| Kubuntu 20.04      | 42        | 0.73%   |
| Ubuntu 23.04       | 41        | 0.71%   |
| Fedora 32          | 40        | 0.7%    |
| Debian 12          | 40        | 0.7%    |
| Ubuntu 19.04       | 39        | 0.68%   |
| Linux Mint 20      | 39        | 0.68%   |
| Fedora 36          | 39        | 0.68%   |
| KDE neon 20.04     | 37        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2023      | 37.19%  |
| OpenMandriva  | 510       | 9.38%   |
| Linux Mint    | 473       | 8.7%    |
| Debian        | 379       | 6.97%   |
| Fedora        | 293       | 5.39%   |
| Xubuntu       | 219       | 4.03%   |
| Arch          | 178       | 3.27%   |
| Pop!_OS       | 152       | 2.79%   |
| Manjaro       | 145       | 2.67%   |
| Kubuntu       | 128       | 2.35%   |
| Zorin         | 95        | 1.75%   |
| ROSA          | 75        | 1.38%   |
| Ubuntu MATE   | 72        | 1.32%   |
| Lubuntu       | 72        | 1.32%   |
| KDE neon      | 59        | 1.08%   |
| openSUSE      | 50        | 0.92%   |
| Kali          | 44        | 0.81%   |
| Endless       | 43        | 0.79%   |
| Gentoo        | 37        | 0.68%   |
| ArcoLinux     | 37        | 0.68%   |
| Elementary    | 33        | 0.61%   |
| Ubuntu Budgie | 29        | 0.53%   |
| Ubuntu Unity  | 26        | 0.48%   |
| SteamOS       | 25        | 0.46%   |
| EndeavourOS   | 20        | 0.37%   |
| BlackPanther  | 20        | 0.37%   |
| Parrot        | 19        | 0.35%   |
| LMDE          | 16        | 0.29%   |
| Ubuntu Studio | 12        | 0.22%   |
| MX            | 11        | 0.2%    |
| CentOS        | 11        | 0.2%    |
| Kaisen        | 9         | 0.17%   |
| Clear Linux   | 8         | 0.15%   |
| NixOS         | 7         | 0.13%   |
| Linux Lite    | 7         | 0.13%   |
| Xero          | 6         | 0.11%   |
| Peppermint    | 6         | 0.11%   |
| Mageia        | 6         | 0.11%   |
| RHEL          | 5         | 0.09%   |
| Artix         | 5         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 168       | 2.68%   |
| 5.16.7-desktop-1omv4003  | 142       | 2.26%   |
| 5.15.0-56-generic        | 83        | 1.32%   |
| 5.4.0-42-generic         | 73        | 1.16%   |
| 6.1.1-desktop-1omv2290   | 66        | 1.05%   |
| 5.15.0-58-generic        | 60        | 0.96%   |
| 6.2.6-desktop-1omv2390   | 54        | 0.86%   |
| 5.15.0-52-generic        | 53        | 0.84%   |
| 5.11.0-38-generic        | 51        | 0.81%   |
| 5.4.0-58-generic         | 44        | 0.7%    |
| 5.4.0-52-generic         | 44        | 0.7%    |
| 5.15.0-48-generic        | 44        | 0.7%    |
| 5.11.0-27-generic        | 43        | 0.69%   |
| 5.4.0-26-generic         | 40        | 0.64%   |
| 5.4.0-48-generic         | 36        | 0.57%   |
| 5.8.0-50-generic         | 35        | 0.56%   |
| 5.15.0-46-generic        | 35        | 0.56%   |
| 5.11.0-37-generic        | 35        | 0.56%   |
| 6.2.0-26-generic         | 34        | 0.54%   |
| 5.8.0-43-generic         | 33        | 0.53%   |
| 5.4.0-91-generic         | 33        | 0.53%   |
| 5.4.0-65-generic         | 33        | 0.53%   |
| 5.8.0-44-generic         | 32        | 0.51%   |
| 5.19.0-35-generic        | 32        | 0.51%   |
| 5.15.0-47-generic        | 32        | 0.51%   |
| 5.13.0-30-generic        | 32        | 0.51%   |
| 5.11.0-43-generic        | 32        | 0.51%   |
| 5.4.0-37-generic         | 31        | 0.49%   |
| 5.15.0-43-generic        | 31        | 0.49%   |
| 5.11.0-40-generic        | 31        | 0.49%   |
| 5.19.0-41-generic        | 30        | 0.48%   |
| 5.15.0-60-generic        | 30        | 0.48%   |
| 5.13.0-40-generic        | 30        | 0.48%   |
| 5.19.0-38-generic        | 29        | 0.46%   |
| 5.15.0-53-generic        | 29        | 0.46%   |
| 5.11.0-34-generic        | 29        | 0.46%   |
| 5.8.0-59-generic         | 28        | 0.45%   |
| 5.8.0-48-generic         | 28        | 0.45%   |
| 5.4.0-54-generic         | 27        | 0.43%   |
| 5.15.0-41-generic        | 27        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 964       | 16.31%  |
| 5.15.0  | 681       | 11.52%  |
| 5.11.0  | 358       | 6.06%   |
| 5.8.0   | 351       | 5.94%   |
| 5.13.0  | 314       | 5.31%   |
| 5.19.0  | 253       | 4.28%   |
| 5.10.0  | 250       | 4.23%   |
| 4.15.0  | 227       | 3.84%   |
| 5.3.0   | 176       | 2.98%   |
| 5.10.14 | 169       | 2.86%   |
| 5.16.7  | 142       | 2.4%    |
| 5.0.0   | 99        | 1.67%   |
| 6.2.0   | 84        | 1.42%   |
| 6.1.1   | 76        | 1.29%   |
| 4.18.0  | 66        | 1.12%   |
| 4.19.0  | 64        | 1.08%   |
| 6.2.6   | 60        | 1.01%   |
| 6.1.0   | 45        | 0.76%   |
| 5.14.0  | 34        | 0.58%   |
| 6.0.0   | 29        | 0.49%   |
| 5.17.5  | 20        | 0.34%   |
| 5.16.13 | 19        | 0.32%   |
| 5.16.0  | 19        | 0.32%   |
| 5.11.12 | 19        | 0.32%   |
| 4.18.16 | 19        | 0.32%   |
| 5.18.0  | 17        | 0.29%   |
| 5.18.12 | 15        | 0.25%   |
| 4.9.20  | 15        | 0.25%   |
| 5.9.0   | 14        | 0.24%   |
| 5.6.0   | 14        | 0.24%   |
| 6.4.11  | 13        | 0.22%   |
| 6.3.5   | 13        | 0.22%   |
| 5.9.11  | 13        | 0.22%   |
| 5.17.0  | 13        | 0.22%   |
| 4.4.0   | 13        | 0.22%   |
| 6.2.8   | 12        | 0.2%    |
| 5.19.12 | 12        | 0.2%    |
| 6.0.9   | 11        | 0.19%   |
| 5.14.9  | 11        | 0.19%   |
| 4.9.0   | 11        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1013      | 17.37%  |
| 5.15    | 789       | 13.53%  |
| 5.10    | 499       | 8.56%   |
| 5.11    | 409       | 7.01%   |
| 5.8     | 392       | 6.72%   |
| 5.13    | 351       | 6.02%   |
| 5.19    | 306       | 5.25%   |
| 4.15    | 227       | 3.89%   |
| 5.16    | 216       | 3.7%    |
| 6.2     | 205       | 3.52%   |
| 5.3     | 201       | 3.45%   |
| 6.1     | 190       | 3.26%   |
| 5.0     | 103       | 1.77%   |
| 5.14    | 94        | 1.61%   |
| 6.0     | 91        | 1.56%   |
| 4.18    | 87        | 1.49%   |
| 5.9     | 71        | 1.22%   |
| 4.19    | 70        | 1.2%    |
| 5.18    | 67        | 1.15%   |
| 6.4     | 62        | 1.06%   |
| 5.17    | 62        | 1.06%   |
| 6.3     | 59        | 1.01%   |
| 5.6     | 50        | 0.86%   |
| 4.9     | 47        | 0.81%   |
| 5.7     | 42        | 0.72%   |
| 5.12    | 38        | 0.65%   |
| 5.5     | 23        | 0.39%   |
| 4.4     | 15        | 0.26%   |
| 4.1     | 11        | 0.19%   |
| 4.14    | 8         | 0.14%   |
| 5.2     | 7         | 0.12%   |
| 4.13    | 5         | 0.09%   |
| 4.12    | 5         | 0.09%   |
| 4.10    | 4         | 0.07%   |
| 3.10    | 3         | 0.05%   |
| 5.1     | 2         | 0.03%   |
| 4.20    | 2         | 0.03%   |
| 6.5     | 1         | 0.02%   |
| 6.3.3   | 1         | 0.02%   |
| 4.8     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5168      | 97.69%  |
| i686    | 119       | 2.25%   |
| aarch64 | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2551      | 46.47%  |
| KDE5              | 947       | 17.25%  |
| XFCE              | 503       | 9.16%   |
| Unknown           | 431       | 7.85%   |
| X-Cinnamon        | 318       | 5.79%   |
| MATE              | 212       | 3.86%   |
| Cinnamon          | 85        | 1.55%   |
| LXQt              | 84        | 1.53%   |
| KDE               | 62        | 1.13%   |
| i3                | 61        | 1.11%   |
| KDE4              | 50        | 0.91%   |
| Budgie            | 38        | 0.69%   |
| Pantheon          | 34        | 0.62%   |
| Unity             | 27        | 0.49%   |
| LXDE              | 21        | 0.38%   |
| GNOME Flashback   | 19        | 0.35%   |
| Deepin            | 9         | 0.16%   |
| sway              | 6         | 0.11%   |
| GNOME Classic     | 6         | 0.11%   |
| awesome           | 5         | 0.09%   |
| i3-with-shmlog    | 3         | 0.05%   |
| trinity           | 2         | 0.04%   |
| Hyprland          | 2         | 0.04%   |
| bspwm             | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| openbox           | 1         | 0.02%   |
| Lubuntu           | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| ICEWM             | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| Enlightenment     | 1         | 0.02%   |
| dwm-sc            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4173      | 76.33%  |
| Wayland | 985       | 18.02%  |
| Unknown | 226       | 4.13%   |
| Tty     | 82        | 1.5%    |
| Xcb     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1938      | 35.21%  |
| GDM     | 961       | 17.46%  |
| SDDM    | 932       | 16.93%  |
| GDM3    | 735       | 13.35%  |
| LightDM | 683       | 12.41%  |
| TDM     | 182       | 3.31%   |
| KDM     | 48        | 0.87%   |
| XDM     | 9         | 0.16%   |
| SLiM    | 7         | 0.13%   |
| NODM    | 2         | 0.04%   |
| Ly      | 2         | 0.04%   |
| LXDM    | 2         | 0.04%   |
| GREETD  | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| fr_FR       | 3703      | 68.69%  |
| en_US       | 1004      | 18.62%  |
| Unknown     | 400       | 7.42%   |
| en_GB       | 91        | 1.69%   |
| C           | 49        | 0.91%   |
| ru_RU       | 14        | 0.26%   |
| de_DE       | 14        | 0.26%   |
| it_IT       | 12        | 0.22%   |
| pl_PL       | 10        | 0.19%   |
| es_ES       | 9         | 0.17%   |
| fr_CH       | 8         | 0.15%   |
| POSIX       | 5         | 0.09%   |
| nl_NL       | 5         | 0.09%   |
| fr_CA       | 5         | 0.09%   |
| en_IE       | 5         | 0.09%   |
| fr_BE       | 4         | 0.07%   |
| en_IN       | 4         | 0.07%   |
| ru_UA       | 3         | 0.06%   |
| pt_PT       | 3         | 0.06%   |
| pt_BR       | 3         | 0.06%   |
| en_AU       | 3         | 0.06%   |
| sv_SE       | 2         | 0.04%   |
| ro_RO       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| fr_LU       | 2         | 0.04%   |
| en_DK       | 2         | 0.04%   |
| en_CA       | 2         | 0.04%   |
| en_AG       | 2         | 0.04%   |
| cs_CZ       | 2         | 0.04%   |
| C.UTF8      | 2         | 0.04%   |
| zh_CN       | 1         | 0.02%   |
| UTF-8       | 1         | 0.02%   |
| tr_TR       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| oc_FR       | 1         | 0.02%   |
| nb_NO       | 1         | 0.02%   |
| fr_FR@euro  | 1         | 0.02%   |
| fr_FR.UTF8  | 1         | 0.02%   |
| fr_FR.utf-8 | 1         | 0.02%   |
| es_VE       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3112      | 57.64%  |
| BIOS | 2287      | 42.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 4316      | 79.73%  |
| Overlay  | 424       | 7.83%   |
| Btrfs    | 379       | 7%      |
| Unknown  | 111       | 2.05%   |
| Tmpfs    | 80        | 1.48%   |
| Xfs      | 46        | 0.85%   |
| Zfs      | 25        | 0.46%   |
| F2fs     | 12        | 0.22%   |
| Ext3     | 9         | 0.17%   |
| Ext2     | 9         | 0.17%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2618      | 48.25%  |
| Unknown | 2095      | 38.61%  |
| MBR     | 713       | 13.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4636      | 86.14%  |
| Yes       | 746       | 13.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3749      | 69.93%  |
| Yes       | 1612      | 30.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 944       | 17.85%  |
| Hewlett-Packard     | 886       | 16.75%  |
| Lenovo              | 869       | 16.43%  |
| ASUSTek Computer    | 859       | 16.24%  |
| Acer                | 393       | 7.43%   |
| MSI                 | 197       | 3.72%   |
| Toshiba             | 178       | 3.37%   |
| Apple               | 111       | 2.1%    |
| Notebook            | 94        | 1.78%   |
| HUAWEI              | 83        | 1.57%   |
| Samsung Electronics | 71        | 1.34%   |
| Sony                | 67        | 1.27%   |
| Packard Bell        | 61        | 1.15%   |
| TUXEDO              | 29        | 0.55%   |
| Valve               | 27        | 0.51%   |
| Thomson             | 26        | 0.49%   |
| Timi                | 25        | 0.47%   |
| Unknown             | 25        | 0.47%   |
| eMachines           | 23        | 0.43%   |
| UNOWHY              | 22        | 0.42%   |
| Gigabyte Technology | 21        | 0.4%    |
| Clevo               | 20        | 0.38%   |
| Alienware           | 20        | 0.38%   |
| Fujitsu Siemens     | 18        | 0.34%   |
| Fujitsu             | 18        | 0.34%   |
| PC Specialist       | 15        | 0.28%   |
| Google              | 15        | 0.28%   |
| Razer               | 12        | 0.23%   |
| Medion              | 12        | 0.23%   |
| Chuwi               | 12        | 0.23%   |
| Teclast             | 10        | 0.19%   |
| Intel               | 7         | 0.13%   |
| HONOR               | 7         | 0.13%   |
| BESSTAR Tech        | 7         | 0.13%   |
| System76            | 5         | 0.09%   |
| Schenker            | 5         | 0.09%   |
| LDLC                | 5         | 0.09%   |
| Panasonic           | 4         | 0.08%   |
| NEC Computers       | 4         | 0.08%   |
| LG Electronics      | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Notebook                     | 42        | 0.79%   |
| Unknown                         | 42        | 0.79%   |
| HP Pavilion 17                  | 32        | 0.61%   |
| HP Pavilion dv6                 | 28        | 0.53%   |
| Valve Jupiter                   | 27        | 0.51%   |
| HP Pavilion dv7                 | 26        | 0.49%   |
| ASUS S551LN                     | 22        | 0.42%   |
| HP Pavilion g7                  | 18        | 0.34%   |
| Dell XPS 13 9310                | 18        | 0.34%   |
| HP Pavilion Notebook            | 15        | 0.28%   |
| HP EliteBook 840 G3             | 15        | 0.28%   |
| Dell XPS 13 9380                | 15        | 0.28%   |
| Dell XPS 13 7390                | 15        | 0.28%   |
| Dell Latitude E6420             | 15        | 0.28%   |
| HUAWEI HVY-WXX9                 | 14        | 0.26%   |
| HP Pavilion 15                  | 14        | 0.26%   |
| Dell XPS 15 9570                | 14        | 0.26%   |
| Dell Latitude 5420              | 14        | 0.26%   |
| Dell Latitude 5400              | 14        | 0.26%   |
| HP Pavilion g6                  | 13        | 0.25%   |
| HP EliteBook 840 G2             | 13        | 0.25%   |
| Dell XPS 15 9500                | 13        | 0.25%   |
| Dell XPS 15 7590                | 13        | 0.25%   |
| Dell Latitude E6400             | 13        | 0.25%   |
| HUAWEI NBLK-WAX9X               | 12        | 0.23%   |
| Dell Latitude 7490              | 12        | 0.23%   |
| HP ProBook 650 G1               | 11        | 0.21%   |
| HP OMEN by Laptop               | 11        | 0.21%   |
| Lenovo G50-30 80G0              | 10        | 0.19%   |
| HP EliteBook 840 G8 Notebook PC | 10        | 0.19%   |
| HP EliteBook 840 G1             | 10        | 0.19%   |
| Dell XPS 13 9370                | 10        | 0.19%   |
| Dell Precision 5570             | 10        | 0.19%   |
| UNOWHY Y13G010S4EI              | 9         | 0.17%   |
| Toshiba Satellite C660          | 9         | 0.17%   |
| Lenovo Legion 5 15ACH6H 82JU    | 9         | 0.17%   |
| Lenovo G50-45 80E3              | 9         | 0.17%   |
| HP ProBook 640 G1               | 9         | 0.17%   |
| HP Laptop 17-cp0xxx             | 9         | 0.17%   |
| HP Laptop 15-db0xxx             | 9         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 508       | 9.6%    |
| Dell Latitude         | 375       | 7.09%   |
| Acer Aspire           | 266       | 5.03%   |
| HP Pavilion           | 235       | 4.44%   |
| HP EliteBook          | 176       | 3.33%   |
| Lenovo IdeaPad        | 171       | 3.23%   |
| Dell XPS              | 166       | 3.14%   |
| Dell Precision        | 148       | 2.8%    |
| Toshiba Satellite     | 147       | 2.78%   |
| Dell Inspiron         | 141       | 2.67%   |
| ASUS VivoBook         | 132       | 2.5%    |
| HP ProBook            | 131       | 2.48%   |
| HP Laptop             | 84        | 1.59%   |
| Packard Bell EasyNote | 53        | 1%      |
| ASUS ZenBook          | 53        | 1%      |
| Acer Swift            | 50        | 0.95%   |
| Dell Vostro           | 46        | 0.87%   |
| Lenovo Legion         | 42        | 0.79%   |
| HP Notebook           | 42        | 0.79%   |
| Unknown               | 42        | 0.79%   |
| ASUS ROG              | 41        | 0.78%   |
| HP ZBook              | 38        | 0.72%   |
| HP Compaq             | 38        | 0.72%   |
| ASUS ASUS             | 34        | 0.64%   |
| Acer Nitro            | 29        | 0.55%   |
| Valve Jupiter         | 27        | 0.51%   |
| HP OMEN               | 24        | 0.45%   |
| HP ENVY               | 24        | 0.45%   |
| ASUS S551LN           | 22        | 0.42%   |
| MSI Modern            | 19        | 0.36%   |
| Lenovo Yoga           | 18        | 0.34%   |
| Lenovo ThinkBook      | 18        | 0.34%   |
| Dell G5               | 18        | 0.34%   |
| ASUS TUF              | 18        | 0.34%   |
| Acer TravelMate       | 18        | 0.34%   |
| Fujitsu LIFEBOOK      | 16        | 0.3%    |
| Dell G3               | 16        | 0.3%    |
| Toshiba PORTEGE       | 15        | 0.28%   |
| HUAWEI HVY-WXX9       | 14        | 0.26%   |
| Apple MacBookPro5     | 14        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 540       | 10.21%  |
| 2019    | 516       | 9.76%   |
| 2018    | 448       | 8.47%   |
| 2021    | 432       | 8.17%   |
| 2012    | 369       | 6.98%   |
| 2013    | 366       | 6.92%   |
| 2015    | 343       | 6.49%   |
| 2011    | 329       | 6.22%   |
| 2017    | 295       | 5.58%   |
| 2016    | 288       | 5.45%   |
| 2014    | 278       | 5.26%   |
| 2010    | 256       | 4.84%   |
| 2008    | 240       | 4.54%   |
| 2022    | 211       | 3.99%   |
| 2009    | 191       | 3.61%   |
| 2007    | 98        | 1.85%   |
| 2006    | 35        | 0.66%   |
| 2023    | 29        | 0.55%   |
| 2005    | 16        | 0.3%    |
| Unknown | 4         | 0.08%   |
| 2004    | 3         | 0.06%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5289      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4713      | 88.36%  |
| Enabled  | 621       | 11.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5267      | 99.57%  |
| Yes  | 23        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1466      | 27.44%  |
| 3.01-4.0    | 1276      | 23.88%  |
| 16.01-24.0  | 928       | 17.37%  |
| 8.01-16.0   | 845       | 15.82%  |
| 32.01-64.0  | 362       | 6.78%   |
| 1.01-2.0    | 215       | 4.02%   |
| 2.01-3.0    | 99        | 1.85%   |
| 64.01-256.0 | 60        | 1.12%   |
| 24.01-32.0  | 50        | 0.94%   |
| 0.51-1.0    | 34        | 0.64%   |
| 0.01-0.5    | 6         | 0.11%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2003      | 34.54%  |
| 2.01-3.0   | 1492      | 25.73%  |
| 4.01-8.0   | 856       | 14.76%  |
| 3.01-4.0   | 767       | 13.23%  |
| 0.51-1.0   | 353       | 6.09%   |
| 8.01-16.0  | 246       | 4.24%   |
| 0.01-0.5   | 48        | 0.83%   |
| 16.01-24.0 | 23        | 0.4%    |
| 24.01-32.0 | 7         | 0.12%   |
| 32.01-64.0 | 2         | 0.03%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3937      | 73.23%  |
| 2      | 1244      | 23.14%  |
| 3      | 125       | 2.33%   |
| 0      | 42        | 0.78%   |
| 4      | 17        | 0.32%   |
| 5      | 6         | 0.11%   |
| 6      | 3         | 0.06%   |
| 8      | 1         | 0.02%   |
| 7      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3291      | 61.95%  |
| Yes       | 2021      | 38.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4300      | 80.98%  |
| No        | 1010      | 19.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5202      | 98.24%  |
| No        | 93        | 1.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4079      | 76.21%  |
| No        | 1273      | 23.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 5289      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 894       | 15.5%   |
| Lyon             | 120       | 2.08%   |
| Marseille        | 107       | 1.86%   |
| Toulouse         | 103       | 1.79%   |
| Nantes           | 76        | 1.32%   |
| Montpellier      | 67        | 1.16%   |
| Bordeaux         | 56        | 0.97%   |
| Rennes           | 55        | 0.95%   |
| Lille            | 52        | 0.9%    |
| Strasbourg       | 50        | 0.87%   |
| Grenoble         | 44        | 0.76%   |
| Villeurbanne     | 34        | 0.59%   |
| Brest            | 32        | 0.55%   |
| Roubaix          | 31        | 0.54%   |
| Nice             | 30        | 0.52%   |
| Clichy-sous-Bois | 30        | 0.52%   |
| Caen             | 27        | 0.47%   |
| Rouen            | 26        | 0.45%   |
| Poitiers         | 22        | 0.38%   |
| Argenteuil       | 21        | 0.36%   |
| Cergy            | 20        | 0.35%   |
| Clermont-Ferrand | 19        | 0.33%   |
| Orléans         | 18        | 0.31%   |
| Nancy            | 18        | 0.31%   |
| Metz             | 18        | 0.31%   |
| La Rochelle      | 18        | 0.31%   |
| Aix-en-Provence  | 18        | 0.31%   |
| Toulon           | 17        | 0.29%   |
| Palaiseau        | 17        | 0.29%   |
| Limoges          | 17        | 0.29%   |
| Le Mans          | 17        | 0.29%   |
| Besançon        | 17        | 0.29%   |
| Versailles       | 16        | 0.28%   |
| Tours            | 16        | 0.28%   |
| Saint-Denis      | 16        | 0.28%   |
| Pau              | 16        | 0.28%   |
| Colmar           | 16        | 0.28%   |
| Angers           | 16        | 0.28%   |
| Valenciennes     | 15        | 0.26%   |
| Perpignan        | 15        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1023      | 1405   | 15.69%  |
| WDC                         | 704       | 886    | 10.8%   |
| Seagate                     | 670       | 857    | 10.27%  |
| Toshiba                     | 539       | 672    | 8.27%   |
| SanDisk                     | 395       | 499    | 6.06%   |
| Crucial                     | 385       | 497    | 5.9%    |
| SK hynix                    | 334       | 408    | 5.12%   |
| Unknown                     | 325       | 425    | 4.98%   |
| Kingston                    | 297       | 352    | 4.55%   |
| HGST                        | 277       | 333    | 4.25%   |
| Micron Technology           | 199       | 229    | 3.05%   |
| Intel                       | 197       | 238    | 3.02%   |
| Hitachi                     | 192       | 219    | 2.94%   |
| KIOXIA                      | 96        | 110    | 1.47%   |
| PNY                         | 55        | 61     | 0.84%   |
| Apple                       | 51        | 66     | 0.78%   |
| LDLC                        | 46        | 64     | 0.71%   |
| Fujitsu                     | 41        | 49     | 0.63%   |
| LITEON                      | 40        | 46     | 0.61%   |
| Transcend                   | 39        | 43     | 0.6%    |
| China                       | 39        | 46     | 0.6%    |
| Phison                      | 33        | 35     | 0.51%   |
| SPCC                        | 32        | 36     | 0.49%   |
| JMicron Technology          | 31        | 34     | 0.48%   |
| LITEONIT                    | 25        | 27     | 0.38%   |
| Unknown                     | 23        | 24     | 0.35%   |
| Micron/Crucial Technology   | 22        | 26     | 0.34%   |
| Kingston Technology Company | 20        | 22     | 0.31%   |
| Corsair                     | 19        | 23     | 0.29%   |
| Phison Electronics          | 17        | 18     | 0.26%   |
| SSSTC                       | 14        | 17     | 0.21%   |
| A-DATA Technology           | 14        | 20     | 0.21%   |
| Emtec                       | 13        | 14     | 0.2%    |
| Silicon Motion              | 12        | 15     | 0.18%   |
| Netac                       | 11        | 13     | 0.17%   |
| BHT                         | 10        | 14     | 0.15%   |
| YMTC                        | 9         | 10     | 0.14%   |
| OCZ                         | 9         | 13     | 0.14%   |
| Lite-On                     | 9         | 13     | 0.14%   |
| ASMT                        | 9         | 11     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 103       | 1.52%   |
| HGST HTS721010A9E630 1TB                              | 102       | 1.51%   |
| Toshiba MQ01ABD100 1TB                                | 88        | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 84        | 1.24%   |
| Crucial CT500MX500SSD1 500GB                          | 68        | 1.01%   |
| Crucial CT240BX500SSD1 240GB                          | 68        | 1.01%   |
| Unknown MMC Card  32GB                                | 63        | 0.93%   |
| Toshiba MQ04ABF100 1TB                                | 61        | 0.9%    |
| HGST HTS541010A9E680 1TB                              | 54        | 0.8%    |
| Samsung SSD 860 EVO 500GB                             | 53        | 0.78%   |
| Unknown MMC Card  64GB                                | 51        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                       | 44        | 0.65%   |
| SanDisk NVMe SSD Drive 512GB                          | 43        | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                       | 40        | 0.59%   |
| Samsung NVMe SSD Drive 512GB                          | 37        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                           | 37        | 0.55%   |
| Seagate ST9500325AS 500GB                             | 36        | 0.53%   |
| Toshiba MQ01ABF050 500GB                              | 34        | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB                        | 33        | 0.49%   |
| Samsung SSD 850 EVO 500GB                             | 32        | 0.47%   |
| HGST HTS725050A7E630 500GB                            | 31        | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 30        | 0.44%   |
| Samsung SSD 870 QVO 1TB                               | 30        | 0.44%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                        | 28        | 0.41%   |
| Samsung SSD 850 EVO 250GB                             | 27        | 0.4%    |
| Unknown MMC Card  128GB                               | 26        | 0.38%   |
| Crucial CT480BX500SSD1 480GB                          | 26        | 0.38%   |
| Crucial CT120BX500SSD1 120GB                          | 26        | 0.38%   |
| Toshiba NVMe SSD Drive 512GB                          | 25        | 0.37%   |
| Kingston SA400S37480G 480GB SSD                       | 25        | 0.37%   |
| Samsung SSD 860 EVO 1TB                               | 24        | 0.35%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 24        | 0.35%   |
| Seagate ST500LM021-1KJ152 500GB                       | 23        | 0.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 23        | 0.34%   |
| Intel NVMe SSD Drive 512GB                            | 23        | 0.34%   |
| Unknown                                               | 23        | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                         | 22        | 0.33%   |
| Seagate ST1000LM049-2GH172 1TB                        | 22        | 0.33%   |
| Samsung SSD 980 1TB                                   | 22        | 0.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 22        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 661       | 841    | 31.39%  |
| WDC                 | 470       | 599    | 22.32%  |
| Toshiba             | 370       | 446    | 17.57%  |
| HGST                | 277       | 333    | 13.15%  |
| Hitachi             | 192       | 219    | 9.12%   |
| Fujitsu             | 40        | 48     | 1.9%    |
| Samsung Electronics | 39        | 60     | 1.85%   |
| Unknown             | 14        | 15     | 0.66%   |
| Apple               | 7         | 7      | 0.33%   |
| SABRENT             | 5         | 5      | 0.24%   |
| IBM/Hitachi         | 5         | 6      | 0.24%   |
| HGST HTS            | 4         | 6      | 0.19%   |
| ASMT                | 4         | 6      | 0.19%   |
| JMicron Technology  | 3         | 4      | 0.14%   |
| Inateck             | 3         | 3      | 0.14%   |
| LaCie               | 2         | 2      | 0.09%   |
| ASMedia             | 2         | 2      | 0.09%   |
| USB3.0              | 1         | 1      | 0.05%   |
| SILICONMOTION       | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| Generic-            | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| APPLE HD            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 482       | 639    | 23.1%   |
| Crucial             | 352       | 455    | 16.87%  |
| SanDisk             | 243       | 305    | 11.64%  |
| Kingston            | 217       | 260    | 10.4%   |
| SK hynix            | 74        | 90     | 3.55%   |
| Micron Technology   | 69        | 90     | 3.31%   |
| WDC                 | 53        | 59     | 2.54%   |
| Intel               | 50        | 53     | 2.4%    |
| PNY                 | 48        | 53     | 2.3%    |
| Apple               | 39        | 51     | 1.87%   |
| Toshiba             | 38        | 45     | 1.82%   |
| LDLC                | 38        | 53     | 1.82%   |
| China               | 38        | 45     | 1.82%   |
| Transcend           | 37        | 41     | 1.77%   |
| LITEON              | 34        | 38     | 1.63%   |
| SPCC                | 28        | 32     | 1.34%   |
| LITEONIT            | 25        | 27     | 1.2%    |
| JMicron Technology  | 15        | 16     | 0.72%   |
| Emtec               | 12        | 13     | 0.57%   |
| A-DATA Technology   | 11        | 17     | 0.53%   |
| Corsair             | 10        | 13     | 0.48%   |
| BHT                 | 10        | 14     | 0.48%   |
| OCZ                 | 9         | 13     | 0.43%   |
| Netac               | 9         | 11     | 0.43%   |
| KingSpec            | 8         | 9      | 0.38%   |
| Dogfish             | 8         | 11     | 0.38%   |
| Teclast             | 7         | 9      | 0.34%   |
| Plextor             | 6         | 13     | 0.29%   |
| Patriot             | 6         | 6      | 0.29%   |
| Intenso             | 6         | 7      | 0.29%   |
| KingDian            | 5         | 6      | 0.24%   |
| Fanxiang            | 5         | 6      | 0.24%   |
| ASMT                | 5         | 5      | 0.24%   |
| Unknown             | 5         | 5      | 0.24%   |
| Verbatim            | 4         | 4      | 0.19%   |
| Unknown             | 3         | 4      | 0.14%   |
| TCSUNBOW            | 3         | 4      | 0.14%   |
| Gigabyte Technology | 3         | 4      | 0.14%   |
| BAITITON            | 3         | 3      | 0.14%   |
| Union Memory        | 2         | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2039      | 2610   | 32.74%  |
| SSD     | 1927      | 2612   | 30.94%  |
| NVMe    | 1855      | 2430   | 29.78%  |
| MMC     | 334       | 446    | 5.36%   |
| Unknown | 73        | 81     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3517      | 5038   | 59.44%  |
| NVMe | 1855      | 2425   | 31.35%  |
| MMC  | 334       | 446    | 5.64%   |
| SAS  | 211       | 270    | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2508      | 3355   | 63.43%  |
| 0.51-1.0   | 1306      | 1682   | 33.03%  |
| 1.01-2.0   | 120       | 159    | 3.03%   |
| 4.01-10.0  | 10        | 12     | 0.25%   |
| 3.01-4.0   | 7         | 10     | 0.18%   |
| 10.01-20.0 | 2         | 3      | 0.05%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1520      | 27.42%  |
| 251-500        | 1483      | 26.75%  |
| 501-1000       | 963       | 17.37%  |
| 1-20           | 413       | 7.45%   |
| 51-100         | 338       | 6.1%    |
| 1001-2000      | 293       | 5.28%   |
| 21-50          | 235       | 4.24%   |
| Unknown        | 136       | 2.45%   |
| 2001-3000      | 83        | 1.5%    |
| More than 3000 | 80        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2182      | 37.86%  |
| 21-50          | 1052      | 18.25%  |
| 101-250        | 816       | 14.16%  |
| 51-100         | 740       | 12.84%  |
| 251-500        | 455       | 7.9%    |
| 501-1000       | 256       | 4.44%   |
| Unknown        | 136       | 2.36%   |
| 1001-2000      | 76        | 1.32%   |
| 2001-3000      | 31        | 0.54%   |
| More than 3000 | 17        | 0.29%   |
| 0              | 2         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 20        | 23     | 4.09%   |
| HGST HTS541010A9E680 1TB                         | 14        | 15     | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 13        | 14     | 2.66%   |
| Seagate ST9500325AS 500GB                        | 11        | 12     | 2.25%   |
| Seagate ST500LM021-1KJ152 500GB                  | 11        | 13     | 2.25%   |
| Toshiba MQ01ABD100 1TB                           | 10        | 12     | 2.04%   |
| Seagate ST500LT012-1DG142 500GB                  | 8         | 8      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 7         | 7      | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB                   | 7         | 7      | 1.43%   |
| Toshiba MQ01ABF050 500GB                         | 6         | 6      | 1.23%   |
| Toshiba MQ01ABD050 500GB                         | 6         | 6      | 1.23%   |
| Seagate ST320LT007-9ZV142 320GB                  | 5         | 6      | 1.02%   |
| Hitachi HTS547575A9E384 752GB                    | 5         | 5      | 1.02%   |
| Hitachi HTS545050A7E380 500GB                    | 5         | 5      | 1.02%   |
| HGST HTS725050A7E630 500GB                       | 5         | 5      | 1.02%   |
| HGST HTS545050A7E380 500GB                       | 5         | 5      | 1.02%   |
| Toshiba MK3265GSX 320GB                          | 4         | 5      | 0.82%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 4         | 4      | 0.82%   |
| Hitachi HTS727575A9E364 752GB                    | 4         | 4      | 0.82%   |
| Hitachi HTS545050B9A300 500GB                    | 4         | 4      | 0.82%   |
| Hitachi HTS543232A7A384 320GB                    | 4         | 6      | 0.82%   |
| HGST HTS545050A7E680 500GB                       | 4         | 4      | 0.82%   |
| HGST HTS541075A9E680 752GB                       | 4         | 4      | 0.82%   |
| Crucial CT525MX300SSD1 528GB                     | 4         | 4      | 0.82%   |
| Toshiba MK7575GSX 752GB                          | 3         | 3      | 0.61%   |
| Toshiba MK5055GSX 500GB                          | 3         | 3      | 0.61%   |
| Toshiba MK3261GSYN 320GB                         | 3         | 3      | 0.61%   |
| SK hynix PC711 HFS512GDE9X073N 512GB             | 3         | 4      | 0.61%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 3         | 3      | 0.61%   |
| Seagate ST9250827AS 250GB                        | 3         | 4      | 0.61%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 3      | 0.61%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 3         | 3      | 0.61%   |
| Kingston RBU-SMSM151S324GD 24GB SSD              | 3         | 3      | 0.61%   |
| Hitachi HTS725032A9A364 320GB                    | 3         | 3      | 0.61%   |
| Hitachi HTS723232A7A364 320GB                    | 3         | 3      | 0.61%   |
| Hitachi HTS547550A9E384 500GB                    | 3         | 3      | 0.61%   |
| WDC WD5000BEVT-00A0RT0 500GB                     | 2         | 2      | 0.41%   |
| WDC WD5000BEKT-75KA9T0 500GB                     | 2         | 2      | 0.41%   |
| WDC WD3200BPVT-80ZEST0 320GB                     | 2         | 2      | 0.41%   |
| WDC WD3200BPVT-22ZEST0 320GB                     | 2         | 2      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 101       | 113    | 20.7%   |
| Toshiba             | 68        | 72     | 13.93%  |
| WDC                 | 56        | 59     | 11.48%  |
| Hitachi             | 56        | 58     | 11.48%  |
| HGST                | 56        | 61     | 11.48%  |
| Samsung Electronics | 26        | 29     | 5.33%   |
| SK hynix            | 21        | 24     | 4.3%    |
| SanDisk             | 18        | 22     | 3.69%   |
| Crucial             | 16        | 16     | 3.28%   |
| Kingston            | 13        | 13     | 2.66%   |
| Intel               | 13        | 14     | 2.66%   |
| Fujitsu             | 8         | 8      | 1.64%   |
| Micron Technology   | 4         | 4      | 0.82%   |
| Netac               | 2         | 2      | 0.41%   |
| LITEONIT            | 2         | 2      | 0.41%   |
| LITEON              | 2         | 2      | 0.41%   |
| LDLC                | 2         | 4      | 0.41%   |
| Intenso             | 2         | 2      | 0.41%   |
| Dogfish             | 2         | 2      | 0.41%   |
| Corsair             | 2         | 3      | 0.41%   |
| China               | 2         | 2      | 0.41%   |
| Apple               | 2         | 2      | 0.41%   |
| Unknown             | 1         | 1      | 0.2%    |
| TakeMS              | 1         | 1      | 0.2%    |
| SSSTC               | 1         | 1      | 0.2%    |
| SPCC                | 1         | 1      | 0.2%    |
| Phison              | 1         | 1      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| Magnetic Data       | 1         | 1      | 0.2%    |
| KingSpec            | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| ASMT                | 1         | 1      | 0.2%    |
| ASENNO              | 1         | 1      | 0.2%    |
| Apacer              | 1         | 1      | 0.2%    |
| A-DATA Technology   | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 101       | 113    | 28.77%  |
| Toshiba             | 64        | 68     | 18.23%  |
| Hitachi             | 56        | 58     | 15.95%  |
| HGST                | 56        | 61     | 15.95%  |
| WDC                 | 53        | 56     | 15.1%   |
| Samsung Electronics | 9         | 9      | 2.56%   |
| Fujitsu             | 8         | 8      | 2.28%   |
| Unknown             | 1         | 1      | 0.28%   |
| Magnetic Data       | 1         | 1      | 0.28%   |
| IBM/Hitachi         | 1         | 1      | 0.28%   |
| ASMT                | 1         | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 348       | 377    | 71.9%   |
| SSD     | 120       | 131    | 24.79%  |
| NVMe    | 15        | 19     | 3.1%    |
| Unknown | 1         | 1      | 0.21%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 3      | 11.76%  |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 11.76%  |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 5.88%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 5.88%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 5.88%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 5.88%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 5.88%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 5.88%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 5.88%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 5.88%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 5.88%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 5.88%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 35.29%  |
| Toshiba             | 6         | 7      | 35.29%  |
| HGST                | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 1      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2659      | 3571   | 46.72%  |
| Detected | 2540      | 4058   | 44.63%  |
| Malfunc  | 472       | 528    | 8.29%   |
| Failed   | 17        | 19     | 0.3%    |
| Fixed    | 2         | 2      | 0.04%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3747      | 59.91%  |
| AMD                                     | 583       | 9.32%   |
| Samsung Electronics                     | 554       | 8.86%   |
| SanDisk                                 | 316       | 5.05%   |
| SK hynix                                | 251       | 4.01%   |
| Toshiba America Info Systems            | 149       | 2.38%   |
| Micron Technology                       | 131       | 2.09%   |
| Kingston Technology Company             | 100       | 1.6%    |
| KIOXIA                                  | 90        | 1.44%   |
| Phison Electronics                      | 63        | 1.01%   |
| Nvidia                                  | 55        | 0.88%   |
| Micron/Crucial Technology               | 55        | 0.88%   |
| Silicon Motion                          | 17        | 0.27%   |
| Union Memory (Shenzhen)                 | 16        | 0.26%   |
| Lite-On Technology                      | 16        | 0.26%   |
| Solid State Storage Technology          | 15        | 0.24%   |
| Silicon Integrated Systems [SiS]        | 14        | 0.22%   |
| Marvell Technology Group                | 13        | 0.21%   |
| JMicron Technology                      | 12        | 0.19%   |
| Yangtze Memory Technologies             | 10        | 0.16%   |
| Lenovo                                  | 6         | 0.1%    |
| ASMedia Technology                      | 5         | 0.08%   |
| Apple                                   | 5         | 0.08%   |
| ADATA Technology                        | 5         | 0.08%   |
| Seagate Technology                      | 4         | 0.06%   |
| Realtek Semiconductor                   | 4         | 0.06%   |
| VIA Technologies                        | 3         | 0.05%   |
| Silicon Image                           | 3         | 0.05%   |
| Shenzhen Longsys Electronics            | 3         | 0.05%   |
| O2 Micro                                | 3         | 0.05%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.03%   |
| ULi Electronics                         | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |
| INNOGRIT                                | 1         | 0.02%   |
| Biwin Storage Technology                | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 477       | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 376       | 5.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 372       | 5.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 302       | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 233       | 3.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 229       | 3.43%   |
| Intel Volume Management Device NVMe RAID Controller                              | 221       | 3.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 215       | 3.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 206       | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 182       | 2.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 177       | 2.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 175       | 2.62%   |
| Samsung NVMe SSD Controller 980                                                  | 170       | 2.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 135       | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 133       | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 105       | 1.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 96        | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 94        | 1.41%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 85        | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 85        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 83        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 82        | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 73        | 1.09%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 71        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 70        | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 63        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 63        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 61        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 60        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 58        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 54        | 0.81%   |
| Intel SSD 660P Series                                                            | 52        | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 52        | 0.78%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 51        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 51        | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 47        | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 45        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 41        | 0.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 38        | 0.57%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 38        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3694      | 57.23%  |
| NVMe | 1872      | 29%     |
| RAID | 543       | 8.41%   |
| IDE  | 346       | 5.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4419      | 83.55%  |
| AMD    | 868       | 16.41%  |
| ARM    | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 104       | 1.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 73        | 1.38%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 72        | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 71        | 1.34%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 70        | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 63        | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 58        | 1.1%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 57        | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 52        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 51        | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 50        | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 50        | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 49        | 0.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 49        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 48        | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 47        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 44        | 0.83%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 41        | 0.77%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 39        | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 39        | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 38        | 0.72%   |
| Intel 12th Gen Core i7-12700H                 | 36        | 0.68%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 36        | 0.68%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 35        | 0.66%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 34        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 34        | 0.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 33        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 33        | 0.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 32        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 31        | 0.59%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 31        | 0.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 29        | 0.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 28        | 0.53%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 28        | 0.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 28        | 0.53%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 28        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1273      | 24.06%  |
| Intel Core i7           | 1118      | 21.13%  |
| Other                   | 531       | 10.03%  |
| Intel Core i3           | 446       | 8.43%   |
| Intel Celeron           | 306       | 5.78%   |
| Intel Core 2 Duo        | 282       | 5.33%   |
| AMD Ryzen 5             | 187       | 3.53%   |
| AMD Ryzen 7             | 173       | 3.27%   |
| Intel Pentium           | 146       | 2.76%   |
| Intel Atom              | 103       | 1.95%   |
| Intel Pentium Dual-Core | 58        | 1.1%    |
| AMD E1                  | 54        | 1.02%   |
| AMD A4                  | 43        | 0.81%   |
| AMD Ryzen 7 PRO         | 38        | 0.72%   |
| AMD E2                  | 38        | 0.72%   |
| Intel Pentium Dual      | 36        | 0.68%   |
| AMD A6                  | 34        | 0.64%   |
| AMD Ryzen 9             | 33        | 0.62%   |
| AMD E                   | 30        | 0.57%   |
| Intel Genuine           | 28        | 0.53%   |
| Intel Core i9           | 28        | 0.53%   |
| Intel Core 2            | 28        | 0.53%   |
| AMD Ryzen 5 PRO         | 26        | 0.49%   |
| AMD A8                  | 22        | 0.42%   |
| AMD Ryzen 3             | 18        | 0.34%   |
| Intel Pentium Silver    | 17        | 0.32%   |
| AMD Athlon              | 16        | 0.3%    |
| Intel Xeon              | 15        | 0.28%   |
| AMD Athlon II           | 14        | 0.26%   |
| Intel Celeron Dual-Core | 12        | 0.23%   |
| Intel Pentium M         | 11        | 0.21%   |
| AMD Athlon X2           | 11        | 0.21%   |
| Intel Core m3           | 9         | 0.17%   |
| AMD Turion 64 X2 Mobile | 9         | 0.17%   |
| Intel Celeron M         | 8         | 0.15%   |
| AMD Athlon II Dual-Core | 8         | 0.15%   |
| AMD A12                 | 8         | 0.15%   |
| AMD Athlon 64 X2        | 7         | 0.13%   |
| AMD C-60                | 6         | 0.11%   |
| AMD A10                 | 6         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2584      | 48.83%  |
| 4       | 1752      | 33.11%  |
| 6       | 389       | 7.35%   |
| 8       | 306       | 5.78%   |
| 1       | 119       | 2.25%   |
| 14      | 51        | 0.96%   |
| 12      | 43        | 0.81%   |
| 10      | 34        | 0.64%   |
| Unknown | 9         | 0.17%   |
| 24      | 2         | 0.04%   |
| 16      | 2         | 0.04%   |
| 3       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5287      | 99.94%  |
| 2      | 3         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3822      | 72.14%  |
| 1       | 1466      | 27.67%  |
| Unknown | 9         | 0.17%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5204      | 98.23%  |
| Unknown        | 48        | 0.91%   |
| 32-bit         | 44        | 0.83%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1215      | 22.16%  |
| 0x306a9    | 311       | 5.67%   |
| 0x206a7    | 293       | 5.34%   |
| 0x806c1    | 210       | 3.83%   |
| 0x1067a    | 194       | 3.54%   |
| 0x806ec    | 192       | 3.5%    |
| 0x906ea    | 177       | 3.23%   |
| 0x406e3    | 163       | 2.97%   |
| 0x40651    | 158       | 2.88%   |
| 0x306d4    | 157       | 2.86%   |
| 0x806ea    | 149       | 2.72%   |
| 0x306c3    | 145       | 2.64%   |
| 0x20655    | 125       | 2.28%   |
| 0x806e9    | 123       | 2.24%   |
| 0x6fd      | 94        | 1.71%   |
| 0x506e3    | 86        | 1.57%   |
| 0xa0652    | 85        | 1.55%   |
| 0x906e9    | 72        | 1.31%   |
| 0x08600106 | 68        | 1.24%   |
| 0x08108109 | 68        | 1.24%   |
| 0x30678    | 63        | 1.15%   |
| 0x10676    | 55        | 1%      |
| 0x806d1    | 54        | 0.98%   |
| 0x906a3    | 52        | 0.95%   |
| 0x706e5    | 52        | 0.95%   |
| 0x0a50000c | 52        | 0.95%   |
| 0x406c4    | 48        | 0.88%   |
| 0x07030105 | 47        | 0.86%   |
| 0x806eb    | 45        | 0.82%   |
| 0x506c9    | 45        | 0.82%   |
| 0x706a1    | 41        | 0.75%   |
| 0x406c3    | 41        | 0.75%   |
| 0x08608103 | 41        | 0.75%   |
| 0x08108102 | 41        | 0.75%   |
| 0x05000119 | 38        | 0.69%   |
| 0x20652    | 37        | 0.67%   |
| 0x06006705 | 37        | 0.67%   |
| 0x706a8    | 36        | 0.66%   |
| 0x906ed    | 34        | 0.62%   |
| 0x0700010f | 28        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1010      | 19.07%  |
| Haswell          | 403       | 7.61%   |
| IvyBridge        | 373       | 7.04%   |
| SandyBridge      | 341       | 6.44%   |
| Skylake          | 323       | 6.1%    |
| Penryn           | 288       | 5.44%   |
| TigerLake        | 269       | 5.08%   |
| Broadwell        | 199       | 3.76%   |
| Westmere         | 197       | 3.72%   |
| Silvermont       | 197       | 3.72%   |
| Unknown          | 178       | 3.36%   |
| Core             | 177       | 3.34%   |
| Zen 2            | 145       | 2.74%   |
| Zen+             | 121       | 2.28%   |
| Icelake          | 121       | 2.28%   |
| CometLake        | 117       | 2.21%   |
| Zen 3            | 104       | 1.96%   |
| Alderlake Hybrid | 97        | 1.83%   |
| Goldmont plus    | 96        | 1.81%   |
| Puma             | 70        | 1.32%   |
| Bobcat           | 68        | 1.28%   |
| Excavator        | 63        | 1.19%   |
| Goldmont         | 58        | 1.1%    |
| Bonnell          | 42        | 0.79%   |
| Jaguar           | 40        | 0.76%   |
| Zen              | 38        | 0.72%   |
| K10              | 35        | 0.66%   |
| K8 Hammer        | 27        | 0.51%   |
| P6               | 24        | 0.45%   |
| Nehalem          | 21        | 0.4%    |
| Piledriver       | 15        | 0.28%   |
| K8 & K10 hybrid  | 15        | 0.28%   |
| K10 Llano        | 12        | 0.23%   |
| Tremont          | 6         | 0.11%   |
| NetBurst         | 3         | 0.06%   |
| Steamroller      | 2         | 0.04%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3967      | 57.92%  |
| Nvidia                           | 1670      | 24.38%  |
| AMD                              | 1201      | 17.54%  |
| Silicon Integrated Systems [SiS] | 9         | 0.13%   |
| VIA Technologies                 | 2         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 344       | 4.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 303       | 4.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 251       | 3.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 237       | 3.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 199       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 186       | 2.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 177       | 2.52%   |
| Intel HD Graphics 5500                                                                   | 176       | 2.5%    |
| Intel UHD Graphics 620                                                                   | 172       | 2.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 168       | 2.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 156       | 2.22%   |
| Intel HD Graphics 620                                                                    | 154       | 2.19%   |
| AMD Renoir                                                                               | 141       | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 139       | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 123       | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 122       | 1.73%   |
| Intel HD Graphics 530                                                                    | 103       | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 103       | 1.46%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 98        | 1.39%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 96        | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 94        | 1.34%   |
| Intel HD Graphics 630                                                                    | 83        | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 80        | 1.14%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 79        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 79        | 1.12%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 75        | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 70        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 70        | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 62        | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 60        | 0.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 55        | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 53        | 0.75%   |
| AMD Lucienne                                                                             | 53        | 0.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 51        | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 48        | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 48        | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 47        | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 47        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 46        | 0.65%   |
| Intel HD Graphics 500                                                                    | 44        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2499      | 47.11%  |
| Intel + Nvidia     | 1255      | 23.66%  |
| 1 x AMD            | 818       | 15.42%  |
| 1 x Nvidia         | 308       | 5.81%   |
| Intel + AMD        | 199       | 3.75%   |
| AMD + Nvidia       | 101       | 1.9%    |
| 2 x AMD            | 84        | 1.58%   |
| 2 x Intel          | 17        | 0.32%   |
| 1 x SiS            | 9         | 0.17%   |
| 2 x Nvidia         | 7         | 0.13%   |
| Other              | 5         | 0.09%   |
| 1 x VIA            | 2         | 0.04%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4522      | 84.57%  |
| Proprietary | 694       | 12.98%  |
| Unknown     | 131       | 2.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3342      | 61.75%  |
| 0.01-0.5   | 702       | 12.97%  |
| 1.01-2.0   | 593       | 10.96%  |
| 0.51-1.0   | 321       | 5.93%   |
| 3.01-4.0   | 296       | 5.47%   |
| 5.01-6.0   | 87        | 1.61%   |
| 7.01-8.0   | 45        | 0.83%   |
| 2.01-3.0   | 23        | 0.42%   |
| 8.01-16.0  | 3         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1203      | 19.97%  |
| Chimei Innolux          | 809       | 13.43%  |
| LG Display              | 789       | 13.1%   |
| BOE                     | 737       | 12.23%  |
| Samsung Electronics     | 621       | 10.31%  |
| Sharp                   | 202       | 3.35%   |
| Dell                    | 162       | 2.69%   |
| Chi Mei Optoelectronics | 158       | 2.62%   |
| Iiyama                  | 119       | 1.98%   |
| Apple                   | 110       | 1.83%   |
| Lenovo                  | 96        | 1.59%   |
| PANDA                   | 82        | 1.36%   |
| Hewlett-Packard         | 77        | 1.28%   |
| Acer                    | 77        | 1.28%   |
| LG Philips              | 74        | 1.23%   |
| Goldstar                | 71        | 1.18%   |
| InfoVision              | 70        | 1.16%   |
| BenQ                    | 51        | 0.85%   |
| Ancor Communications    | 49        | 0.81%   |
| AOC                     | 45        | 0.75%   |
| Philips                 | 43        | 0.71%   |
| ViewSonic               | 35        | 0.58%   |
| CSO                     | 26        | 0.43%   |
| ASUSTek Computer        | 21        | 0.35%   |
| CPT                     | 19        | 0.32%   |
| Sony                    | 18        | 0.3%    |
| HannStar                | 15        | 0.25%   |
| Fujitsu Siemens         | 14        | 0.23%   |
| Valve                   | 12        | 0.2%    |
| Toshiba                 | 12        | 0.2%    |
| Analogix                | 11        | 0.18%   |
| Vestel Elektronik       | 10        | 0.17%   |
| Seiko/Epson             | 9         | 0.15%   |
| LGD                     | 9         | 0.15%   |
| Unknown                 | 7         | 0.12%   |
| TMX                     | 6         | 0.1%    |
| Panasonic               | 6         | 0.1%    |
| Quanta Display          | 5         | 0.08%   |
| MSI                     | 5         | 0.08%   |
| LPL                     | 5         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 48        | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 37        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 37        | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 34        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 29        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 29        | 0.48%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 28        | 0.46%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 27        | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 26        | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 26        | 0.43%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 26        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 25        | 0.41%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 24        | 0.39%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 24        | 0.39%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 23        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 22        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 21        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 21        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 19        | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 18        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 18        | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 18        | 0.3%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 17        | 0.28%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 17        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 17        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 17        | 0.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 17        | 0.28%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 17        | 0.28%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 17        | 0.28%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 16        | 0.26%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 16        | 0.26%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 15        | 0.25%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 15        | 0.25%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch              | 15        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 15        | 0.25%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 15        | 0.25%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 15        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2450      | 43.79%  |
| 1366x768 (WXGA)    | 1348      | 24.09%  |
| 1600x900 (HD+)     | 522       | 9.33%   |
| 1280x800 (WXGA)    | 199       | 3.56%   |
| 3840x2160 (4K)     | 184       | 3.29%   |
| 1920x1200 (WUXGA)  | 153       | 2.73%   |
| 1440x900 (WXGA+)   | 143       | 2.56%   |
| 2560x1440 (QHD)    | 139       | 2.48%   |
| 1680x1050 (WSXGA+) | 62        | 1.11%   |
| 2560x1600          | 39        | 0.7%    |
| 1024x600           | 34        | 0.61%   |
| 1280x1024 (SXGA)   | 33        | 0.59%   |
| 2880x1800          | 32        | 0.57%   |
| 3440x1440          | 30        | 0.54%   |
| 3840x2400          | 24        | 0.43%   |
| 800x1280           | 22        | 0.39%   |
| 2160x1440          | 20        | 0.36%   |
| 2560x1080          | 16        | 0.29%   |
| 3200x1800 (QHD+)   | 13        | 0.23%   |
| Unknown            | 12        | 0.21%   |
| 1360x768           | 10        | 0.18%   |
| 3840x1080          | 9         | 0.16%   |
| 3000x2000          | 9         | 0.16%   |
| 1920x540           | 9         | 0.16%   |
| 1680x945           | 8         | 0.14%   |
| 1600x1200          | 7         | 0.13%   |
| 1024x768 (XGA)     | 6         | 0.11%   |
| 3072x1920          | 5         | 0.09%   |
| 2520x1680          | 5         | 0.09%   |
| 2288x1287          | 5         | 0.09%   |
| 3840x1200          | 4         | 0.07%   |
| 2256x1504          | 4         | 0.07%   |
| 1920x515           | 4         | 0.07%   |
| 1400x1050          | 4         | 0.07%   |
| 1920x1280          | 3         | 0.05%   |
| 5760x2160          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3456x2160          | 2         | 0.04%   |
| 3286x1080          | 2         | 0.04%   |
| 2880x1620          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2220      | 36.9%   |
| 13      | 833       | 13.85%  |
| 17      | 829       | 13.78%  |
| 14      | 589       | 9.79%   |
| 24      | 256       | 4.26%   |
| 27      | 190       | 3.16%   |
| 23      | 184       | 3.06%   |
| 12      | 160       | 2.66%   |
| 21      | 118       | 1.96%   |
| 11      | 78        | 1.3%    |
| 16      | 77        | 1.28%   |
| Unknown | 73        | 1.21%   |
| 18      | 48        | 0.8%    |
| 10      | 47        | 0.78%   |
| 34      | 42        | 0.7%    |
| 22      | 40        | 0.66%   |
| 19      | 40        | 0.66%   |
| 31      | 23        | 0.38%   |
| 20      | 19        | 0.32%   |
| 84      | 17        | 0.28%   |
| 72      | 15        | 0.25%   |
| 7       | 12        | 0.2%    |
| 25      | 11        | 0.18%   |
| 3       | 11        | 0.18%   |
| 26      | 9         | 0.15%   |
| 54      | 8         | 0.13%   |
| 32      | 8         | 0.13%   |
| 40      | 7         | 0.12%   |
| 52      | 6         | 0.1%    |
| 33      | 6         | 0.1%    |
| 39      | 5         | 0.08%   |
| 49      | 4         | 0.07%   |
| 142     | 3         | 0.05%   |
| 65      | 3         | 0.05%   |
| 48      | 3         | 0.05%   |
| 43      | 3         | 0.05%   |
| 50      | 2         | 0.03%   |
| 46      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 35      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3166      | 53.19%  |
| 351-400        | 937       | 15.74%  |
| 201-300        | 739       | 12.42%  |
| 501-600        | 586       | 9.85%   |
| 401-500        | 244       | 4.1%    |
| Unknown        | 73        | 1.23%   |
| 701-800        | 57        | 0.96%   |
| 601-700        | 40        | 0.67%   |
| 1501-2000      | 33        | 0.55%   |
| 1001-1500      | 31        | 0.52%   |
| 1-100          | 22        | 0.37%   |
| 801-900        | 17        | 0.29%   |
| More than 2000 | 3         | 0.05%   |
| 101-200        | 3         | 0.05%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4381      | 82.91%  |
| 16/10   | 650       | 12.3%   |
| 3/2     | 53        | 1%      |
| 21/9    | 48        | 0.91%   |
| Unknown | 47        | 0.89%   |
| 5/4     | 35        | 0.66%   |
| 4/3     | 26        | 0.49%   |
| 0.67    | 12        | 0.23%   |
| 6/5     | 11        | 0.21%   |
| 32/9    | 7         | 0.13%   |
| 3.20    | 4         | 0.08%   |
| 3.73    | 3         | 0.06%   |
| 1.00    | 3         | 0.06%   |
| 3.88    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2222      | 37.04%  |
| 81-90          | 1046      | 17.44%  |
| 121-130        | 686       | 11.44%  |
| 201-250        | 484       | 8.07%   |
| 71-80          | 375       | 6.25%   |
| 301-350        | 198       | 3.3%    |
| 61-70          | 150       | 2.5%    |
| 131-140        | 130       | 2.17%   |
| 151-200        | 96        | 1.6%    |
| 351-500        | 82        | 1.37%   |
| 251-300        | 79        | 1.32%   |
| 51-60          | 78        | 1.3%    |
| Unknown        | 73        | 1.22%   |
| 111-120        | 70        | 1.17%   |
| More than 1000 | 57        | 0.95%   |
| 141-150        | 56        | 0.93%   |
| 41-50          | 48        | 0.8%    |
| 501-1000       | 27        | 0.45%   |
| 1-40           | 25        | 0.42%   |
| 91-100         | 17        | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2319      | 39.37%  |
| 101-120       | 1784      | 30.28%  |
| 51-100        | 1057      | 17.94%  |
| 161-240       | 453       | 7.69%   |
| More than 240 | 160       | 2.72%   |
| Unknown       | 73        | 1.24%   |
| 1-50          | 45        | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4295      | 79.26%  |
| 2     | 866       | 15.98%  |
| 0     | 139       | 2.57%   |
| 3     | 111       | 2.05%   |
| 4     | 6         | 0.11%   |
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
| Intel                             | 2895      | 34.45%  |
| Realtek Semiconductor             | 2705      | 32.19%  |
| Qualcomm Atheros                  | 1237      | 14.72%  |
| Broadcom                          | 556       | 6.62%   |
| Broadcom Limited                  | 117       | 1.39%   |
| MediaTek                          | 109       | 1.3%    |
| Marvell Technology Group          | 102       | 1.21%   |
| Ralink                            | 85        | 1.01%   |
| ASIX Electronics                  | 65        | 0.77%   |
| Dell                              | 46        | 0.55%   |
| Samsung Electronics               | 38        | 0.45%   |
| Nvidia                            | 35        | 0.42%   |
| Xiaomi                            | 31        | 0.37%   |
| DisplayLink                       | 30        | 0.36%   |
| Ericsson Business Mobile Networks | 29        | 0.35%   |
| Sierra Wireless                   | 25        | 0.3%    |
| Qualcomm                          | 23        | 0.27%   |
| TP-Link                           | 22        | 0.26%   |
| NetGear                           | 22        | 0.26%   |
| JMicron Technology                | 20        | 0.24%   |
| Ralink Technology                 | 19        | 0.23%   |
| Lenovo                            | 19        | 0.23%   |
| Huawei Technologies               | 18        | 0.21%   |
| Hewlett-Packard                   | 14        | 0.17%   |
| Attansic Technology               | 14        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.13%   |
| OPPO Electronics                  | 10        | 0.12%   |
| Google                            | 9         | 0.11%   |
| D-Link                            | 8         | 0.1%    |
| Toshiba                           | 6         | 0.07%   |
| Apple                             | 6         | 0.07%   |
| Fibocom                           | 5         | 0.06%   |
| D-Link System                     | 5         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.05%   |
| ICS Advent                        | 4         | 0.05%   |
| ASUSTek Computer                  | 4         | 0.05%   |
| Arduino SA                        | 4         | 0.05%   |
| VIA Technologies                  | 3         | 0.04%   |
| U-Blox                            | 3         | 0.04%   |
| Shenzhen Goodix Technology        | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1577      | 15.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 435       | 4.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 306       | 3.02%   |
| Intel Wi-Fi 6 AX200                                               | 241       | 2.38%   |
| Intel Wireless 8265 / 8275                                        | 212       | 2.09%   |
| Intel Wi-Fi 6 AX201                                               | 203       | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 201       | 1.98%   |
| Intel Wireless 7265                                               | 199       | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 180       | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 173       | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 167       | 1.65%   |
| Intel Wireless 8260                                               | 166       | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 158       | 1.56%   |
| Intel Wireless 7260                                               | 154       | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 150       | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 138       | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 126       | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 121       | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 119       | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 114       | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 105       | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 103       | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 103       | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 98        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 97        | 0.96%   |
| Intel Wireless 3165                                               | 89        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                     | 81        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 74        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 70        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 66        | 0.65%   |
| Intel WiFi Link 5100                                              | 64        | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 64        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 63        | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 61        | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 61        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 61        | 0.6%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 56        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 56        | 0.55%   |
| Intel Wireless 3160                                               | 54        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2755      | 50.82%  |
| Qualcomm Atheros                      | 1015      | 18.72%  |
| Realtek Semiconductor                 | 803       | 14.81%  |
| Broadcom                              | 404       | 7.45%   |
| MediaTek                              | 102       | 1.88%   |
| Ralink                                | 85        | 1.57%   |
| Broadcom Limited                      | 80        | 1.48%   |
| Sierra Wireless                       | 25        | 0.46%   |
| Dell                                  | 24        | 0.44%   |
| Ralink Technology                     | 19        | 0.35%   |
| NetGear                               | 19        | 0.35%   |
| TP-Link                               | 18        | 0.33%   |
| Qualcomm                              | 17        | 0.31%   |
| Ericsson Business Mobile Networks     | 8         | 0.15%   |
| D-Link                                | 7         | 0.13%   |
| Hewlett-Packard                       | 6         | 0.11%   |
| Fibocom                               | 5         | 0.09%   |
| D-Link System                         | 5         | 0.09%   |
| ASUSTek Computer                      | 4         | 0.07%   |
| Microsoft                             | 3         | 0.06%   |
| Belkin Components                     | 3         | 0.06%   |
| Qualcomm Atheros Communications       | 2         | 0.04%   |
| Guillemot                             | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| ZyDAS                                 | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Qualcomm Technologies                 | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 241       | 4.42%   |
| Intel Wireless 8265 / 8275                                              | 212       | 3.89%   |
| Intel Wi-Fi 6 AX201                                                     | 203       | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 201       | 3.69%   |
| Intel Wireless 7265                                                     | 199       | 3.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 180       | 3.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 167       | 3.06%   |
| Intel Wireless 8260                                                     | 166       | 3.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 158       | 2.9%    |
| Intel Wireless 7260                                                     | 154       | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 150       | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 138       | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 126       | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 119       | 2.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 114       | 2.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 105       | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 103       | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 103       | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 98        | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 97        | 1.78%   |
| Intel Wireless 3165                                                     | 89        | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 81        | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 74        | 1.36%   |
| Intel WiFi Link 5100                                                    | 64        | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 61        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 56        | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 56        | 1.03%   |
| Intel Wireless 3160                                                     | 54        | 0.99%   |
| Intel Wireless-AC 9260                                                  | 53        | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 50        | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 50        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 44        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 43        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 42        | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 41        | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 39        | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 38        | 0.7%    |
| Intel Centrino Advanced-N 6200                                          | 38        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2410      | 53.15%  |
| Intel                            | 1035      | 22.83%  |
| Qualcomm Atheros                 | 388       | 8.56%   |
| Broadcom                         | 213       | 4.7%    |
| Marvell Technology Group         | 102       | 2.25%   |
| ASIX Electronics                 | 65        | 1.43%   |
| Broadcom Limited                 | 40        | 0.88%   |
| Samsung Electronics              | 37        | 0.82%   |
| Nvidia                           | 35        | 0.77%   |
| Xiaomi                           | 31        | 0.68%   |
| DisplayLink                      | 30        | 0.66%   |
| JMicron Technology               | 20        | 0.44%   |
| Lenovo                           | 19        | 0.42%   |
| Attansic Technology              | 14        | 0.31%   |
| Huawei Technologies              | 12        | 0.26%   |
| Silicon Integrated Systems [SiS] | 11        | 0.24%   |
| OPPO Electronics                 | 10        | 0.22%   |
| Google                           | 9         | 0.2%    |
| MediaTek                         | 7         | 0.15%   |
| Qualcomm                         | 6         | 0.13%   |
| Apple                            | 6         | 0.13%   |
| TP-Link                          | 4         | 0.09%   |
| ICS Advent                       | 4         | 0.09%   |
| NetGear                          | 3         | 0.07%   |
| Aquantia                         | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.04%   |
| Motorola PCS                     | 2         | 0.04%   |
| Linksys                          | 2         | 0.04%   |
| Hisense                          | 2         | 0.04%   |
| Cypress Semiconductor            | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| T & A Mobile Phones              | 1         | 0.02%   |
| Microchip Technology             | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Davicom Semiconductor            | 1         | 0.02%   |
| D-Link                           | 1         | 0.02%   |
| Archos                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1577      | 34.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 435       | 9.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 306       | 6.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 173       | 3.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 70        | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 70        | 1.53%   |
| Intel Ethernet Connection I219-LM                                 | 66        | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 64        | 1.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 63        | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 61        | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 53        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 51        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                          | 44        | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 43        | 0.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 37        | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 37        | 0.81%   |
| Intel Ethernet Connection I219-V                                  | 36        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 35        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 34        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 33        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 32        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 32        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 30        | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 29        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 28        | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 28        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 28        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 26        | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 26        | 0.57%   |
| Intel Ethernet Connection (13) I219-LM                            | 26        | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 25        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 24        | 0.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 22        | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 22        | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 21        | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 21        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5203      | 54.21%  |
| Ethernet | 4294      | 44.74%  |
| Modem    | 93        | 0.97%   |
| Unknown  | 7         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4177      | 74.23%  |
| Ethernet | 1450      | 25.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3829      | 72.3%   |
| 1     | 1341      | 25.32%  |
| 0     | 76        | 1.44%   |
| 3     | 50        | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3383      | 61.93%  |
| Yes  | 2080      | 38.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2160      | 52.58%  |
| Realtek Semiconductor           | 345       | 8.4%    |
| IMC Networks                    | 314       | 7.64%   |
| Qualcomm Atheros Communications | 260       | 6.33%   |
| Broadcom                        | 211       | 5.14%   |
| Foxconn / Hon Hai               | 151       | 3.68%   |
| Lite-On Technology              | 145       | 3.53%   |
| Apple                           | 107       | 2.6%    |
| Dell                            | 88        | 2.14%   |
| Cambridge Silicon Radio         | 60        | 1.46%   |
| Realtek                         | 46        | 1.12%   |
| Hewlett-Packard                 | 44        | 1.07%   |
| Toshiba                         | 41        | 1%      |
| Ralink                          | 34        | 0.83%   |
| ASUSTek Computer                | 25        | 0.61%   |
| Ralink Technology               | 22        | 0.54%   |
| Foxconn International           | 14        | 0.34%   |
| Alps Electric                   | 14        | 0.34%   |
| Chicony Electronics             | 7         | 0.17%   |
| USI                             | 6         | 0.15%   |
| MediaTek                        | 5         | 0.12%   |
| TP-Link                         | 3         | 0.07%   |
| Syntek                          | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 836       | 20.34%  |
| Intel AX201 Bluetooth                               | 452       | 11%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 328       | 7.98%   |
| Realtek Bluetooth Radio                             | 242       | 5.89%   |
| Intel AX200 Bluetooth                               | 229       | 5.57%   |
| Intel Bluetooth Device                              | 126       | 3.07%   |
| IMC Networks Bluetooth Device                       | 115       | 2.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 106       | 2.58%   |
| IMC Networks Bluetooth Radio                        | 95        | 2.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 81        | 1.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 77        | 1.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 61        | 1.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 60        | 1.46%   |
| Apple Bluetooth Host Controller                     | 58        | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 53        | 1.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 46        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 46        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 43        | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 1%      |
| Realtek 802.11ac WLAN Adapter                       | 39        | 0.95%   |
| Lite-On Bluetooth Device                            | 37        | 0.9%    |
| Intel AX210 Bluetooth                               | 37        | 0.9%    |
| IMC Networks Wireless_Device                        | 37        | 0.9%    |
| Dell DW375 Bluetooth Module                         | 37        | 0.9%    |
| Ralink RT3290 Bluetooth                             | 34        | 0.83%   |
| Apple Bluetooth USB Host Controller                 | 31        | 0.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 30        | 0.73%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 30        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                         | 30        | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 28        | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 0.61%   |
| Broadcom BCM43142A0 Bluetooth Device                | 24        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 0.51%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 20        | 0.49%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                    | 18        | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 18        | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 18        | 0.44%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4302      | 65.23%  |
| AMD                                          | 1015      | 15.39%  |
| Nvidia                                       | 819       | 12.42%  |
| Realtek Semiconductor                        | 68        | 1.03%   |
| Logitech                                     | 42        | 0.64%   |
| GN Netcom                                    | 38        | 0.58%   |
| C-Media Electronics                          | 33        | 0.5%    |
| Plantronics                                  | 27        | 0.41%   |
| JMTek                                        | 21        | 0.32%   |
| Kingston Technology                          | 19        | 0.29%   |
| Lenovo                                       | 18        | 0.27%   |
| Hewlett-Packard                              | 15        | 0.23%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.2%    |
| Corsair                                      | 13        | 0.2%    |
| SteelSeries ApS                              | 8         | 0.12%   |
| Focusrite-Novation                           | 8         | 0.12%   |
| Sony                                         | 7         | 0.11%   |
| Generalplus Technology                       | 7         | 0.11%   |
| Texas Instruments                            | 6         | 0.09%   |
| Razer USA                                    | 5         | 0.08%   |
| VIA Technologies                             | 4         | 0.06%   |
| Sennheiser Communications                    | 4         | 0.06%   |
| ASUSTek Computer                             | 4         | 0.06%   |
| Apple                                        | 4         | 0.06%   |
| PreSonus Audio Electronics                   | 3         | 0.05%   |
| No brand                                     | 3         | 0.05%   |
| M-Audio                                      | 3         | 0.05%   |
| Elitegroup Computer Systems (ECS)            | 3         | 0.05%   |
| Conexant Systems                             | 3         | 0.05%   |
| Blue Microphones                             | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| ZOOM                                         | 2         | 0.03%   |
| Yamaha                                       | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| RODE Microphones                             | 2         | 0.03%   |
| ROCCAT                                       | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.03%   |
| Jieli Technology                             | 2         | 0.03%   |
| DSEA A/S                                     | 2         | 0.03%   |
| Dell                                         | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 551       | 6.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 469       | 5.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 439       | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 275       | 3.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 269       | 3.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 268       | 3.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 266       | 3.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 263       | 3.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 218       | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 203       | 2.56%   |
| Intel 8 Series HD Audio Controller                                                                | 201       | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 199       | 2.51%   |
| Intel Broadwell-U Audio Controller                                                                | 199       | 2.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 198       | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 170       | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 168       | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 160       | 2.02%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 147       | 1.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 146       | 1.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 123       | 1.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 115       | 1.45%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 111       | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 108       | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 108       | 1.36%   |
| Intel CM238 HD Audio Controller                                                                   | 104       | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 96        | 1.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 96        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 86        | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 81        | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 80        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 77        | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 76        | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 74        | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 68        | 0.86%   |
| Realtek Semiconductor USB Audio                                                                   | 67        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 63        | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 63        | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 61        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 60        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 59        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 1229      | 30.03%  |
| SK hynix                                         | 1062      | 25.95%  |
| Micron Technology                                | 506       | 12.36%  |
| Kingston                                         | 291       | 7.11%   |
| Unknown                                          | 269       | 6.57%   |
| Crucial                                          | 201       | 4.91%   |
| Elpida                                           | 78        | 1.91%   |
| Ramaxel Technology                               | 77        | 1.88%   |
| Corsair                                          | 61        | 1.49%   |
| Nanya Technology                                 | 56        | 1.37%   |
| A-DATA Technology                                | 50        | 1.22%   |
| Unknown (ABCD)                                   | 48        | 1.17%   |
| G.Skill                                          | 46        | 1.12%   |
| Unknown                                          | 21        | 0.51%   |
| Transcend                                        | 11        | 0.27%   |
| ASint Technology                                 | 7         | 0.17%   |
| Timetec                                          | 6         | 0.15%   |
| Patriot                                          | 5         | 0.12%   |
| Apacer                                           | 5         | 0.12%   |
| Toshiba                                          | 4         | 0.1%    |
| Team                                             | 4         | 0.1%    |
| V-Color                                          | 3         | 0.07%   |
| SHARETRONIC                                      | 3         | 0.07%   |
| Qimonda                                          | 3         | 0.07%   |
| PNY                                              | 3         | 0.07%   |
| TEXTORM                                          | 2         | 0.05%   |
| Neo Forza                                        | 2         | 0.05%   |
| Lexar                                            | 2         | 0.05%   |
| Goldkey                                          | 2         | 0.05%   |
| ChangXin Memory                                  | 2         | 0.05%   |
| 48spaces                                         | 2         | 0.05%   |
| Wilk                                             | 1         | 0.02%   |
| Unknown (F301)                                   | 1         | 0.02%   |
| Unknown (0x8634)                                 | 1         | 0.02%   |
| Unknown (0x7301)                                 | 1         | 0.02%   |
| Unknown (0x5846)                                 | 1         | 0.02%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.02%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.02%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.02%   |
| Unknown (0x0C97)                                 | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 62        | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 58        | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 58        | 1.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 57        | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 53        | 1.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 51        | 1.19%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 47        | 1.09%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 45        | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 44        | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 0.95%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 40        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 39        | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 38        | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 38        | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 37        | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 37        | 0.86%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 35        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 30        | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.58%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 24        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 23        | 0.54%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 23        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 22        | 0.51%   |
| Unknown                                                          | 21        | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.47%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 19        | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 0.44%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 19        | 0.44%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 19        | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 19        | 0.44%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 18        | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 18        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1612      | 46%     |
| DDR3    | 1228      | 35.05%  |
| DDR2    | 180       | 5.14%   |
| LPDDR4  | 157       | 4.48%   |
| LPDDR3  | 105       | 3%      |
| SDRAM   | 82        | 2.34%   |
| DDR5    | 50        | 1.43%   |
| LPDDR5  | 44        | 1.26%   |
| Unknown | 27        | 0.77%   |
| DDR     | 13        | 0.37%   |
| DRAM    | 6         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3135      | 89.65%  |
| Row Of Chips | 315       | 9.01%   |
| Chip         | 19        | 0.54%   |
| DIMM         | 15        | 0.43%   |
| Unknown      | 13        | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1452      | 38.03%  |
| 4096  | 1170      | 30.64%  |
| 2048  | 494       | 12.94%  |
| 16384 | 489       | 12.81%  |
| 1024  | 120       | 3.14%   |
| 32768 | 83        | 2.17%   |
| 512   | 9         | 0.24%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 890       | 23.73%  |
| 2667    | 714       | 19.04%  |
| 3200    | 687       | 18.32%  |
| 2400    | 242       | 6.45%   |
| 1334    | 194       | 5.17%   |
| 2133    | 187       | 4.99%   |
| 1333    | 113       | 3.01%   |
| 667     | 95        | 2.53%   |
| 4267    | 66        | 1.76%   |
| Unknown | 60        | 1.6%    |
| 3266    | 58        | 1.55%   |
| 1067    | 56        | 1.49%   |
| 4800    | 53        | 1.41%   |
| 6400    | 44        | 1.17%   |
| 800     | 43        | 1.15%   |
| 1867    | 42        | 1.12%   |
| 4199    | 40        | 1.07%   |
| 2048    | 36        | 0.96%   |
| 1066    | 26        | 0.69%   |
| 975     | 25        | 0.67%   |
| 533     | 19        | 0.51%   |
| 4266    | 15        | 0.4%    |
| 8400    | 10        | 0.27%   |
| 2933    | 7         | 0.19%   |
| 1866    | 6         | 0.16%   |
| 333     | 5         | 0.13%   |
| 3000    | 4         | 0.11%   |
| 3733    | 3         | 0.08%   |
| 1639    | 3         | 0.08%   |
| 5600    | 2         | 0.05%   |
| 400     | 2         | 0.05%   |
| 933     | 1         | 0.03%   |
| 666     | 1         | 0.03%   |
| 266     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 36.59%  |
| Canon               | 11        | 26.83%  |
| Seiko Epson         | 4         | 9.76%   |
| Samsung Electronics | 4         | 9.76%   |
| Brother Industries  | 4         | 9.76%   |
| Xiaomi              | 1         | 2.44%   |
| STMicroelectronics  | 1         | 2.44%   |
| QinHeng Electronics | 1         | 2.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 9.76%   |
| HP DeskJet 3630 series                                    | 3         | 7.32%   |
| Canon PIXMA MG2500 Series                                 | 3         | 7.32%   |
| Seiko Epson WF-2830 Series                                | 2         | 4.88%   |
| Canon PIXMA MG3600 Series                                 | 2         | 4.88%   |
| Xiaomi MiMouse 2                                          | 1         | 2.44%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.44%   |
| Seiko Epson XP-255 257 Series                             | 1         | 2.44%   |
| Seiko Epson XP-2150 Series                                | 1         | 2.44%   |
| Samsung SCX-3200 Series                                   | 1         | 2.44%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.44%   |
| Samsung M2070 Series                                      | 1         | 2.44%   |
| Samsung M2020 Series                                      | 1         | 2.44%   |
| QinHeng CH340S                                            | 1         | 2.44%   |
| HP Photosmart B010 series                                 | 1         | 2.44%   |
| HP OfficeJet Pro 69                                       | 1         | 2.44%   |
| HP OfficeJet 3830 series                                  | 1         | 2.44%   |
| HP ENVY Photo 6200 series                                 | 1         | 2.44%   |
| HP ENVY 5540 series                                       | 1         | 2.44%   |
| HP ENVY 4500 series                                       | 1         | 2.44%   |
| HP Deskjet F4500 series                                   | 1         | 2.44%   |
| HP DeskJet 2600 series                                    | 1         | 2.44%   |
| Canon TS6100 series                                       | 1         | 2.44%   |
| Canon TS3100 series                                       | 1         | 2.44%   |
| Canon PIXMA MP495                                         | 1         | 2.44%   |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.44%   |
| Canon PIXMA MG3500 Series                                 | 1         | 2.44%   |
| Canon MG2100 series                                       | 1         | 2.44%   |
| Brother MFC-L8690CDW series                               | 1         | 2.44%   |
| Brother MFC-L2710DW series                                | 1         | 2.44%   |
| Brother MFC-1810                                          | 1         | 2.44%   |
| Brother DCP-L3550CDW                                      | 1         | 2.44%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 58.33%  |
| Seiko Epson     | 4         | 33.33%  |
| Hewlett-Packard | 1         | 8.33%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 3         | 25%     |
| Seiko Epson Scanner                           | 1         | 8.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 8.33%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 8.33%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 8.33%   |
| HP ScanJet 3570c                              | 1         | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 8.33%   |
| Canon CanoScan N650U/N656U                    | 1         | 8.33%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 8.33%   |
| Canon CanoScan 8800F                          | 1         | 8.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1188      | 25.02%  |
| IMC Networks                           | 539       | 11.35%  |
| Microdia                               | 468       | 9.86%   |
| Realtek Semiconductor                  | 441       | 9.29%   |
| Bison Electronics                      | 315       | 6.63%   |
| Sunplus Innovation Technology          | 293       | 6.17%   |
| Suyin                                  | 198       | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 190       | 4%      |
| Quanta                                 | 178       | 3.75%   |
| Lite-On Technology                     | 121       | 2.55%   |
| Apple                                  | 102       | 2.15%   |
| Syntek                                 | 90        | 1.9%    |
| Acer                                   | 83        | 1.75%   |
| Alcor Micro                            | 64        | 1.35%   |
| Luxvisions Innotech Limited            | 60        | 1.26%   |
| Logitech                               | 58        | 1.22%   |
| Ricoh                                  | 49        | 1.03%   |
| Silicon Motion                         | 45        | 0.95%   |
| Samsung Electronics                    | 33        | 0.7%    |
| Sonix Technology                       | 26        | 0.55%   |
| Lenovo                                 | 22        | 0.46%   |
| Primax Electronics                     | 20        | 0.42%   |
| Z-Star Microelectronics                | 16        | 0.34%   |
| Importek                               | 16        | 0.34%   |
| DigiTech                               | 14        | 0.29%   |
| ALi                                    | 13        | 0.27%   |
| Y Media                                | 9         | 0.19%   |
| icSpring                               | 9         | 0.19%   |
| SunplusIT                              | 7         | 0.15%   |
| GEMBIRD                                | 7         | 0.15%   |
| OmniVision Technologies                | 6         | 0.13%   |
| Microsoft                              | 6         | 0.13%   |
| ShineTech                              | 4         | 0.08%   |
| Intel                                  | 4         | 0.08%   |
| Denron                                 | 4         | 0.08%   |
| Xiaomi                                 | 3         | 0.06%   |
| Sunplus Technology                     | 3         | 0.06%   |
| Pixart Imaging                         | 3         | 0.06%   |
| Generalplus Technology                 | 3         | 0.06%   |
| ARC International                      | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 248       | 5.2%    |
| Realtek Integrated_Webcam_HD                  | 194       | 4.07%   |
| Chicony Integrated Camera                     | 186       | 3.9%    |
| IMC Networks USB2.0 HD UVC WebCam             | 130       | 2.73%   |
| IMC Networks Integrated Camera                | 94        | 1.97%   |
| Chicony HD WebCam                             | 94        | 1.97%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 93        | 1.95%   |
| Sunplus Integrated_Webcam_HD                  | 78        | 1.64%   |
| Bison Integrated Camera                       | 73        | 1.53%   |
| Bison HD Webcam                               | 61        | 1.28%   |
| Realtek USB Camera                            | 59        | 1.24%   |
| Chicony USB2.0 Camera                         | 58        | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam                 | 54        | 1.13%   |
| Chicony HP HD Camera                          | 51        | 1.07%   |
| Microdia Integrated Webcam                    | 49        | 1.03%   |
| Chicony USB2.0 HD UVC WebCam                  | 45        | 0.94%   |
| Chicony TOSHIBA Web Camera - HD               | 45        | 0.94%   |
| Sunplus Asus Webcam                           | 44        | 0.92%   |
| Chicony HP Truevision HD                      | 43        | 0.9%    |
| Syntek Integrated Camera                      | 42        | 0.88%   |
| Chicony HP TrueVision HD Camera               | 42        | 0.88%   |
| Bison BisonCam,NB Pro                         | 41        | 0.86%   |
| Chicony USB 2.0 Camera                        | 39        | 0.82%   |
| Lite-On Integrated Camera                     | 38        | 0.8%    |
| Chicony HP HD Webcam                          | 36        | 0.76%   |
| Realtek USB2.0 HD UVC WebCam                  | 35        | 0.73%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 35        | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 34        | 0.71%   |
| Sunplus HD WebCam                             | 34        | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)       | 33        | 0.69%   |
| Quanta HP HD Camera                           | 32        | 0.67%   |
| Apple Built-in iSight                         | 32        | 0.67%   |
| Bison BisonCam, NB Pro                        | 31        | 0.65%   |
| Chicony VGA Webcam                            | 30        | 0.63%   |
| Quanta HD User Facing                         | 28        | 0.59%   |
| IMC Networks UVC VGA Webcam                   | 28        | 0.59%   |
| Chicony EasyCamera                            | 25        | 0.52%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 24        | 0.5%    |
| Lite-On HP HD Webcam                          | 23        | 0.48%   |
| IMC Networks ov9734_azurewave_camera          | 23        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 311       | 36.46%  |
| Synaptics                          | 179       | 20.98%  |
| Shenzhen Goodix Technology         | 159       | 18.64%  |
| AuthenTec                          | 66        | 7.74%   |
| LighTuning Technology              | 46        | 5.39%   |
| Elan Microelectronics              | 43        | 5.04%   |
| Upek                               | 36        | 4.22%   |
| STMicroelectronics                 | 11        | 1.29%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.12%   |
| Focal-systems.Corp                 | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 88        | 10.32%  |
| Shenzhen Goodix  Fingerprint Device                                        | 85        | 9.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 70        | 8.21%   |
| Shenzhen Goodix FingerPrint                                                | 44        | 5.16%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 40        | 4.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 3.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 3.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 3.05%   |
| Validity Sensors VFS491                                                    | 25        | 2.93%   |
| AuthenTec AES2810                                                          | 24        | 2.81%   |
| Elan ELAN:Fingerprint                                                      | 22        | 2.58%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.34%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 2.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.11%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 17        | 1.99%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 1.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 1.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 16        | 1.88%   |
| AuthenTec Fingerprint Sensor                                               | 15        | 1.76%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.64%   |
| AuthenTec AES1600                                                          | 14        | 1.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 13        | 1.52%   |
| Elan ELAN:ARM-M4                                                           | 12        | 1.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.29%   |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 1.29%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.29%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 1.06%   |
| Unknown                                                                    | 8         | 0.94%   |
| Synaptics UWP WBDI                                                         | 7         | 0.82%   |
| Elan WBF Fingerprint Sensor                                                | 7         | 0.82%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.59%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.59%   |
| Synaptics WBDI Device                                                      | 5         | 0.59%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 4         | 0.47%   |
| Synaptics WBDI                                                             | 4         | 0.47%   |
| Synaptics  WBDI                                                            | 4         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 258       | 58.37%  |
| Alcor Micro               | 92        | 20.81%  |
| O2 Micro                  | 39        | 8.82%   |
| Upek                      | 17        | 3.85%   |
| Lenovo                    | 17        | 3.85%   |
| Hewlett-Packard           | 5         | 1.13%   |
| Gemalto (was Gemplus)     | 4         | 0.9%    |
| Yubico.com                | 3         | 0.68%   |
| Clay Logic                | 2         | 0.45%   |
| Aladdin Knowledge Systems | 2         | 0.45%   |
| SpringCard                | 1         | 0.23%   |
| OmniKey                   | 1         | 0.23%   |
| Chicony Electronics       | 1         | 0.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 92        | 20.81%  |
| Broadcom BCM5880 Secure Applications Processor                               | 83        | 18.78%  |
| Broadcom 58200                                                               | 81        | 18.33%  |
| Broadcom 5880                                                                | 56        | 12.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 37        | 8.37%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 35        | 7.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 3.85%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 3.85%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.13%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.9%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.45%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.45%   |
| SpringCard Two                                                               | 1         | 0.23%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.23%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.23%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.23%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3333      | 61.12%  |
| 1     | 1686      | 30.92%  |
| 2     | 347       | 6.36%   |
| 3     | 68        | 1.25%   |
| 4     | 8         | 0.15%   |
| 5     | 5         | 0.09%   |
| 6     | 3         | 0.06%   |
| 7     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 844       | 32.92%  |
| Graphics card            | 585       | 22.82%  |
| Chipcard                 | 412       | 16.07%  |
| Net/wireless             | 212       | 8.27%   |
| Multimedia controller    | 110       | 4.29%   |
| Camera                   | 99        | 3.86%   |
| Bluetooth                | 73        | 2.85%   |
| Storage                  | 61        | 2.38%   |
| Communication controller | 45        | 1.76%   |
| Card reader              | 39        | 1.52%   |
| Sound                    | 27        | 1.05%   |
| Net/ethernet             | 19        | 0.74%   |
| Modem                    | 17        | 0.66%   |
| Network                  | 8         | 0.31%   |
| Flash memory             | 4         | 0.16%   |
| Wireless                 | 2         | 0.08%   |
| Unclassified device      | 2         | 0.08%   |
| Unassigned class         | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

