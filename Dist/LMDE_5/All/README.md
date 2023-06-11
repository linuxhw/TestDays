LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 587

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
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
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
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
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
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
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
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
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE_5/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-21-amd64          | 73        | 17.59%  |
| 5.10.0-12-amd64          | 57        | 13.73%  |
| 5.10.0-19-amd64          | 37        | 8.92%   |
| 5.10.0-14-amd64          | 30        | 7.23%   |
| 5.10.0-20-amd64          | 29        | 6.99%   |
| 5.10.0-23-amd64          | 28        | 6.75%   |
| 5.10.0-13-amd64          | 27        | 6.51%   |
| 5.10.0-18-amd64          | 25        | 6.02%   |
| 5.10.0-17-amd64          | 21        | 5.06%   |
| 5.10.0-15-amd64          | 19        | 4.58%   |
| 5.10.0-16-amd64          | 14        | 3.37%   |
| 5.10.0-22-amd64          | 12        | 2.89%   |
| 5.10.0-13-686            | 6         | 1.45%   |
| 5.18.0-0.bpo.1-amd64     | 4         | 0.96%   |
| 5.16.0-0.bpo.4-amd64     | 4         | 0.96%   |
| 5.19.0-0.deb11.2-amd64   | 3         | 0.72%   |
| 6.1.0-0.deb11.6-amd64    | 2         | 0.48%   |
| 6.1.0-0.deb11.5-amd64    | 2         | 0.48%   |
| 5.10.0-12-686            | 2         | 0.48%   |
| 6.1.11-x64v1-xanmod1     | 1         | 0.24%   |
| 6.1.0-0.deb11.7-amd64    | 1         | 0.24%   |
| 6.1.0-0.deb11.6-rt-amd64 | 1         | 0.24%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1         | 0.24%   |
| 6.0.0-0.deb11.2-amd64    | 1         | 0.24%   |
| 5.19.10-xanmod1          | 1         | 0.24%   |
| 5.18.0-4-amd64           | 1         | 0.24%   |
| 5.18.0-3-amd64           | 1         | 0.24%   |
| 5.16.0-0.bpo.3-amd64     | 1         | 0.24%   |
| 5.15.78-xanmod1          | 1         | 0.24%   |
| 5.15.70-xanmod1          | 1         | 0.24%   |
| 5.15.0-0.bpo.3-amd64     | 1         | 0.24%   |
| 5.10.0-22-686            | 1         | 0.24%   |
| 5.10.0-21-686            | 1         | 0.24%   |
| 5.10.0-20-686            | 1         | 0.24%   |
| 5.10.0-19-686            | 1         | 0.24%   |
| 5.10.0-17-686            | 1         | 0.24%   |
| 5.10.0-14-686            | 1         | 0.24%   |
| 5.10.0-11-686            | 1         | 0.24%   |
| 4.19.0-23-amd64          | 1         | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 359       | 93.01%  |
| 6.1.0   | 6         | 1.55%   |
| 5.18.0  | 6         | 1.55%   |
| 5.16.0  | 4         | 1.04%   |
| 5.19.0  | 3         | 0.78%   |
| 6.1.11  | 1         | 0.26%   |
| 6.0.2   | 1         | 0.26%   |
| 6.0.0   | 1         | 0.26%   |
| 5.19.10 | 1         | 0.26%   |
| 5.15.78 | 1         | 0.26%   |
| 5.15.70 | 1         | 0.26%   |
| 5.15.0  | 1         | 0.26%   |
| 4.19.0  | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 359       | 93.25%  |
| 6.1     | 7         | 1.82%   |
| 5.18    | 6         | 1.56%   |
| 5.19    | 4         | 1.04%   |
| 5.16    | 4         | 1.04%   |
| 6.0     | 2         | 0.52%   |
| 5.15    | 2         | 0.52%   |
| 4.19    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 364       | 96.04%  |
| i686   | 15        | 3.96%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 326       | 85.34%  |
| Cinnamon   | 42        | 10.99%  |
| MATE       | 6         | 1.57%   |
| XFCE       | 2         | 0.52%   |
| KDE5       | 1         | 0.26%   |
| KDE        | 1         | 0.26%   |
| i3         | 1         | 0.26%   |
| GNOME      | 1         | 0.26%   |
| awesome    | 1         | 0.26%   |
| Unknown    | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 379       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 226       | 59.32%  |
| LightDM | 152       | 39.9%   |
| SDDM    | 2         | 0.52%   |
| GDM     | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 134       | 35.26%  |
| de_DE | 53        | 13.95%  |
| ru_RU | 34        | 8.95%   |
| pt_BR | 25        | 6.58%   |
| en_GB | 19        | 5%      |
| fr_FR | 17        | 4.47%   |
| it_IT | 13        | 3.42%   |
| es_ES | 10        | 2.63%   |
| pl_PL | 9         | 2.37%   |
| es_MX | 4         | 1.05%   |
| en_CA | 4         | 1.05%   |
| sv_SE | 3         | 0.79%   |
| fr_CA | 3         | 0.79%   |
| el_GR | 3         | 0.79%   |
| cs_CZ | 3         | 0.79%   |
| tr_TR | 2         | 0.53%   |
| ru_UA | 2         | 0.53%   |
| pt_PT | 2         | 0.53%   |
| ko_KR | 2         | 0.53%   |
| fr_BE | 2         | 0.53%   |
| es_BO | 2         | 0.53%   |
| es_AR | 2         | 0.53%   |
| en_NZ | 2         | 0.53%   |
| en_IE | 2         | 0.53%   |
| en_AU | 2         | 0.53%   |
| de_AT | 2         | 0.53%   |
| da_DK | 2         | 0.53%   |
| zh_CN | 1         | 0.26%   |
| sl_SI | 1         | 0.26%   |
| sk_SK | 1         | 0.26%   |
| nn_NO | 1         | 0.26%   |
| nl_AW | 1         | 0.26%   |
| ja_JP | 1         | 0.26%   |
| it_CH | 1         | 0.26%   |
| hu_HU | 1         | 0.26%   |
| fi_FI | 1         | 0.26%   |
| es_VE | 1         | 0.26%   |
| es_PE | 1         | 0.26%   |
| es_PA | 1         | 0.26%   |
| es_NI | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 229       | 60.26%  |
| BIOS | 151       | 39.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 345       | 90.79%  |
| Overlay | 12        | 3.16%   |
| Tmpfs   | 10        | 2.63%   |
| Btrfs   | 10        | 2.63%   |
| Xfs     | 3         | 0.79%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 226       | 59.32%  |
| GPT     | 109       | 28.61%  |
| MBR     | 46        | 12.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 345       | 90.79%  |
| Yes       | 35        | 9.21%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 328       | 86.32%  |
| Yes       | 52        | 13.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 60        | 15.83%  |
| Lenovo              | 57        | 15.04%  |
| Dell                | 49        | 12.93%  |
| ASUSTek Computer    | 43        | 11.35%  |
| Acer                | 27        | 7.12%   |
| Gigabyte Technology | 21        | 5.54%   |
| MSI                 | 17        | 4.49%   |
| Apple               | 13        | 3.43%   |
| Toshiba             | 10        | 2.64%   |
| ASRock              | 7         | 1.85%   |
| Intel               | 6         | 1.58%   |
| Medion              | 5         | 1.32%   |
| Fujitsu             | 5         | 1.32%   |
| Samsung Electronics | 4         | 1.06%   |
| Google              | 4         | 1.06%   |
| AZW                 | 4         | 1.06%   |
| Unknown             | 4         | 1.06%   |
| Sony                | 3         | 0.79%   |
| Star Labs           | 2         | 0.53%   |
| Packard Bell        | 2         | 0.53%   |
| Compaq              | 2         | 0.53%   |
| Alienware           | 2         | 0.53%   |
| Wortmann AG         | 1         | 0.26%   |
| TUXEDO              | 1         | 0.26%   |
| Timi                | 1         | 0.26%   |
| Supermicro          | 1         | 0.26%   |
| SiYW                | 1         | 0.26%   |
| Philco              | 1         | 0.26%   |
| Pegatron            | 1         | 0.26%   |
| Panasonic           | 1         | 0.26%   |
| Multilaser          | 1         | 0.26%   |
| Microtech           | 1         | 0.26%   |
| LincPlus            | 1         | 0.26%   |
| LG Electronics      | 1         | 0.26%   |
| Kruger&Matz         | 1         | 0.26%   |
| itel Mobile Limited | 1         | 0.26%   |
| Insyde              | 1         | 0.26%   |
| HUAWEI              | 1         | 0.26%   |
| Howard Computers    | 1         | 0.26%   |
| HIPER               | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 6         | 1.58%   |
| Star Labs StarBook             | 2         | 0.53%   |
| MSI MS-7B79                    | 2         | 0.53%   |
| Lenovo IdeaPad 3 15ITL6 82H8   | 2         | 0.53%   |
| Lenovo IdeaPad 3 15ADA05 81W1  | 2         | 0.53%   |
| Lenovo G500 20236              | 2         | 0.53%   |
| Intel B75                      | 2         | 0.53%   |
| HP Pavilion Notebook           | 2         | 0.53%   |
| HP Pavilion dv6                | 2         | 0.53%   |
| HP Notebook                    | 2         | 0.53%   |
| HP Laptop 15z-ef2xxx           | 2         | 0.53%   |
| HP Laptop 15-dw3xxx            | 2         | 0.53%   |
| HP 250 G8 Notebook PC          | 2         | 0.53%   |
| HP 250 G7 Notebook PC          | 2         | 0.53%   |
| Gigabyte B450 AORUS M          | 2         | 0.53%   |
| Dell Latitude E6400            | 2         | 0.53%   |
| Dell Latitude E5540            | 2         | 0.53%   |
| Compaq 420                     | 2         | 0.53%   |
| AZW MINI S                     | 2         | 0.53%   |
| ASUS ROG STRIX B450-F GAMING   | 2         | 0.53%   |
| ASUS PRIME B350M-A             | 2         | 0.53%   |
| Apple MacBookPro11,1           | 2         | 0.53%   |
| Apple iMac7,1                  | 2         | 0.53%   |
| Acer Aspire E1-570G            | 2         | 0.53%   |
| Acer Aspire 7745G              | 2         | 0.53%   |
| Acer Aspire 5930               | 2         | 0.53%   |
| Wortmann AG TERRA_MOBILE_1713A | 1         | 0.26%   |
| TUXEDO N8xxEZ                  | 1         | 0.26%   |
| Toshiba Satellite Pro A50-C    | 1         | 0.26%   |
| Toshiba Satellite M55          | 1         | 0.26%   |
| Toshiba Satellite L855D        | 1         | 0.26%   |
| Toshiba Satellite L455         | 1         | 0.26%   |
| Toshiba Satellite L305         | 1         | 0.26%   |
| Toshiba Satellite L300D        | 1         | 0.26%   |
| Toshiba Satellite L300         | 1         | 0.26%   |
| Toshiba Satellite C850-D8K     | 1         | 0.26%   |
| Toshiba PORTEGE Z30-B          | 1         | 0.26%   |
| Toshiba PORTEGE M780           | 1         | 0.26%   |
| Timi RedmiBook 14-APCS         | 1         | 0.26%   |
| Supermicro X10SAE              | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 23        | 6.07%   |
| Acer Aspire        | 22        | 5.8%    |
| Lenovo IdeaPad     | 13        | 3.43%   |
| Dell Latitude      | 13        | 3.43%   |
| HP Laptop          | 11        | 2.9%    |
| HP Pavilion        | 10        | 2.64%   |
| Dell Inspiron      | 10        | 2.64%   |
| Toshiba Satellite  | 8         | 2.11%   |
| Dell Precision     | 8         | 2.11%   |
| ASUS PRIME         | 7         | 1.85%   |
| HP EliteBook       | 6         | 1.58%   |
| ASUS ROG           | 6         | 1.58%   |
| Unknown            | 6         | 1.58%   |
| Dell Vostro        | 5         | 1.32%   |
| Dell OptiPlex      | 5         | 1.32%   |
| ASUS VivoBook      | 5         | 1.32%   |
| HP ProBook         | 4         | 1.06%   |
| HP Compaq          | 4         | 1.06%   |
| HP 250             | 4         | 1.06%   |
| HP ZBook           | 3         | 0.79%   |
| Gigabyte B450      | 3         | 0.79%   |
| Dell XPS           | 3         | 0.79%   |
| Toshiba PORTEGE    | 2         | 0.53%   |
| Star Labs StarBook | 2         | 0.53%   |
| MSI MS-7B79        | 2         | 0.53%   |
| Lenovo Yoga        | 2         | 0.53%   |
| Lenovo ThinkCentre | 2         | 0.53%   |
| Lenovo ThinkBook   | 2         | 0.53%   |
| Lenovo Legion      | 2         | 0.53%   |
| Lenovo G500        | 2         | 0.53%   |
| Intel B75          | 2         | 0.53%   |
| HP Notebook        | 2         | 0.53%   |
| HP 255             | 2         | 0.53%   |
| Gigabyte B450M     | 2         | 0.53%   |
| Gigabyte A520M     | 2         | 0.53%   |
| Fujitsu LIFEBOOK   | 2         | 0.53%   |
| Compaq 420         | 2         | 0.53%   |
| AZW MINI           | 2         | 0.53%   |
| Apple MacBookPro11 | 2         | 0.53%   |
| Apple iMac7        | 2         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 43        | 11.35%  |
| 2018 | 37        | 9.76%   |
| 2012 | 32        | 8.44%   |
| 2020 | 30        | 7.92%   |
| 2013 | 26        | 6.86%   |
| 2017 | 25        | 6.6%    |
| 2019 | 23        | 6.07%   |
| 2010 | 23        | 6.07%   |
| 2022 | 19        | 5.01%   |
| 2016 | 19        | 5.01%   |
| 2015 | 18        | 4.75%   |
| 2009 | 18        | 4.75%   |
| 2011 | 17        | 4.49%   |
| 2014 | 13        | 3.43%   |
| 2008 | 13        | 3.43%   |
| 2007 | 11        | 2.9%    |
| 2006 | 8         | 2.11%   |
| 2023 | 4         | 1.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 238       | 62.8%   |
| Desktop     | 120       | 31.66%  |
| Convertible | 8         | 2.11%   |
| All in one  | 6         | 1.58%   |
| Tablet      | 3         | 0.79%   |
| Mini pc     | 3         | 0.79%   |
| Server      | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 348       | 91.34%  |
| Enabled  | 33        | 8.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 372       | 98.15%  |
| Yes  | 7         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 100       | 26.25%  |
| 3.01-4.0        | 74        | 19.42%  |
| 16.01-24.0      | 70        | 18.37%  |
| 8.01-16.0       | 60        | 15.75%  |
| 32.01-64.0      | 32        | 8.4%    |
| 1.01-2.0        | 19        | 4.99%   |
| 2.01-3.0        | 12        | 3.15%   |
| 64.01-256.0     | 7         | 1.84%   |
| 24.01-32.0      | 4         | 1.05%   |
| 0.51-1.0        | 2         | 0.52%   |
| More than 256.0 | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 159       | 39.45%  |
| 2.01-3.0   | 130       | 32.26%  |
| 3.01-4.0   | 45        | 11.17%  |
| 4.01-8.0   | 39        | 9.68%   |
| 0.51-1.0   | 21        | 5.21%   |
| 8.01-16.0  | 6         | 1.49%   |
| 32.01-64.0 | 1         | 0.25%   |
| 24.01-32.0 | 1         | 0.25%   |
| 16.01-24.0 | 1         | 0.25%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 249       | 65.01%  |
| 2      | 83        | 21.67%  |
| 3      | 29        | 7.57%   |
| 4      | 11        | 2.87%   |
| 5      | 7         | 1.83%   |
| 6      | 3         | 0.78%   |
| 0      | 1         | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 246       | 64.57%  |
| Yes       | 135       | 35.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 319       | 84.17%  |
| No        | 60        | 15.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 312       | 82.11%  |
| No        | 68        | 17.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 57.63%  |
| No        | 161       | 42.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 74        | 19.42%  |
| Germany      | 58        | 15.22%  |
| Russia       | 37        | 9.71%   |
| Brazil       | 26        | 6.82%   |
| Italy        | 22        | 5.77%   |
| France       | 19        | 4.99%   |
| UK           | 14        | 3.67%   |
| Spain        | 12        | 3.15%   |
| Poland       | 11        | 2.89%   |
| Canada       | 11        | 2.89%   |
| Sweden       | 6         | 1.57%   |
| Mexico       | 6         | 1.57%   |
| Belgium      | 4         | 1.05%   |
| Belarus      | 4         | 1.05%   |
| Australia    | 4         | 1.05%   |
| Turkey       | 3         | 0.79%   |
| Portugal     | 3         | 0.79%   |
| Greece       | 3         | 0.79%   |
| Chile        | 3         | 0.79%   |
| Bolivia      | 3         | 0.79%   |
| Austria      | 3         | 0.79%   |
| Vietnam      | 2         | 0.52%   |
| Venezuela    | 2         | 0.52%   |
| Ukraine      | 2         | 0.52%   |
| South Korea  | 2         | 0.52%   |
| South Africa | 2         | 0.52%   |
| Slovenia     | 2         | 0.52%   |
| Romania      | 2         | 0.52%   |
| Peru         | 2         | 0.52%   |
| Paraguay     | 2         | 0.52%   |
| New Zealand  | 2         | 0.52%   |
| Netherlands  | 2         | 0.52%   |
| Kazakhstan   | 2         | 0.52%   |
| Japan        | 2         | 0.52%   |
| Indonesia    | 2         | 0.52%   |
| Hungary      | 2         | 0.52%   |
| Finland      | 2         | 0.52%   |
| Denmark      | 2         | 0.52%   |
| Czechia      | 2         | 0.52%   |
| Argentina    | 2         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 8         | 2.04%   |
| Berlin               | 7         | 1.78%   |
| St Petersburg        | 4         | 1.02%   |
| Rome                 | 4         | 1.02%   |
| Munich               | 4         | 1.02%   |
| Madrid               | 4         | 1.02%   |
| Delligsen            | 4         | 1.02%   |
| Montreal             | 3         | 0.76%   |
| Milan                | 3         | 0.76%   |
| Miami                | 3         | 0.76%   |
| Krakow               | 3         | 0.76%   |
| Frankfurt am Main    | 3         | 0.76%   |
| Belém               | 3         | 0.76%   |
| Vancouver            | 2         | 0.51%   |
| Toronto              | 2         | 0.51%   |
| Santiago             | 2         | 0.51%   |
| San Jose             | 2         | 0.51%   |
| Rio de Janeiro       | 2         | 0.51%   |
| Parma                | 2         | 0.51%   |
| Oruro                | 2         | 0.51%   |
| Oklahoma City        | 2         | 0.51%   |
| New York             | 2         | 0.51%   |
| Neasden              | 2         | 0.51%   |
| Nashville            | 2         | 0.51%   |
| Melbourne            | 2         | 0.51%   |
| Malmo                | 2         | 0.51%   |
| London               | 2         | 0.51%   |
| Lisbon               | 2         | 0.51%   |
| Lima                 | 2         | 0.51%   |
| Krefeld              | 2         | 0.51%   |
| Jakarta              | 2         | 0.51%   |
| Hamburg              | 2         | 0.51%   |
| Freiburg im Breisgau | 2         | 0.51%   |
| Columbia City        | 2         | 0.51%   |
| Ciudad Juárez       | 2         | 0.51%   |
| Boynton Beach        | 2         | 0.51%   |
| Birmingham           | 2         | 0.51%   |
| Bend                 | 2         | 0.51%   |
| Auckland             | 2         | 0.51%   |
| Astana               | 2         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 74        | 105    | 13.91%  |
| Samsung Electronics       | 73        | 106    | 13.72%  |
| Seagate                   | 66        | 85     | 12.41%  |
| Kingston                  | 34        | 45     | 6.39%   |
| SanDisk                   | 30        | 38     | 5.64%   |
| Unknown                   | 28        | 43     | 5.26%   |
| Toshiba                   | 26        | 29     | 4.89%   |
| Crucial                   | 20        | 23     | 3.76%   |
| SK hynix                  | 15        | 16     | 2.82%   |
| Hitachi                   | 14        | 15     | 2.63%   |
| Intel                     | 9         | 10     | 1.69%   |
| China                     | 9         | 10     | 1.69%   |
| Apple                     | 8         | 13     | 1.5%    |
| A-DATA Technology         | 8         | 9      | 1.5%    |
| Micron Technology         | 7         | 7      | 1.32%   |
| PNY                       | 6         | 7      | 1.13%   |
| Phison                    | 5         | 7      | 0.94%   |
| Patriot                   | 5         | 5      | 0.94%   |
| SPCC                      | 4         | 4      | 0.75%   |
| Silicon Motion            | 4         | 5      | 0.75%   |
| HGST                      | 4         | 7      | 0.75%   |
| Unknown                   | 4         | 5      | 0.75%   |
| Transcend                 | 3         | 5      | 0.56%   |
| Team                      | 3         | 3      | 0.56%   |
| KingSpec                  | 3         | 3      | 0.56%   |
| Intenso                   | 3         | 3      | 0.56%   |
| GOODRAM                   | 3         | 3      | 0.56%   |
| Fujitsu                   | 3         | 3      | 0.56%   |
| Emtec                     | 3         | 3      | 0.56%   |
| ADATA Technology          | 3         | 3      | 0.56%   |
| UMIS                      | 2         | 2      | 0.38%   |
| Star Drive                | 2         | 2      | 0.38%   |
| Phison Electronics        | 2         | 2      | 0.38%   |
| Micron/Crucial Technology | 2         | 3      | 0.38%   |
| KIOXIA                    | 2         | 5      | 0.38%   |
| Gigabyte Technology       | 2         | 4      | 0.38%   |
| Fanxiang                  | 2         | 2      | 0.38%   |
| ASMT                      | 2         | 2      | 0.38%   |
| XrayDisk                  | 1         | 2      | 0.19%   |
| WINTEC                    | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 1.38%   |
| Samsung SSD 850 EVO 250GB                           | 7         | 1.21%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 1.21%   |
| Samsung SSD 850 EVO 500GB                           | 6         | 1.04%   |
| Kingston SA400S37480G 480GB SSD                     | 6         | 1.04%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 1.04%   |
| Unknown SD/MMC/MS PRO 64GB                          | 5         | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 5         | 0.86%   |
| Unknown MMC Card  64GB                              | 4         | 0.69%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.69%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 0.69%   |
| Samsung SSD 980 PRO 1TB                             | 4         | 0.69%   |
| Samsung SSD 970 EVO 500GB                           | 4         | 0.69%   |
| Unknown                                             | 4         | 0.69%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 0.52%   |
| Unknown MMC Card  128GB                             | 3         | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.52%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB   | 3         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 3         | 0.52%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.52%   |
| Samsung SSD 980 1TB                                 | 3         | 0.52%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.52%   |
| Crucial CT480BX500SSD1 480GB                        | 3         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.52%   |
| Crucial CT1000BX500SSD1 1TB                         | 3         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.35%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 2         | 0.35%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 2         | 0.35%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 2         | 0.35%   |
| WDC WD3003FZEX-00Z4SA0 3TB                          | 2         | 0.35%   |
| WDC WD1600BEVT-22ZCT0 160GB                         | 2         | 0.35%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB                | 2         | 0.35%   |
| Unknown SC128  128GB                                | 2         | 0.35%   |
| Unknown MMC Card  32GB                              | 2         | 0.35%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.35%   |
| Toshiba MQ01ACF050 500GB                            | 2         | 0.35%   |
| Toshiba HDWD110 1TB                                 | 2         | 0.35%   |
| Star Drive PCIe SSD 480GB                           | 2         | 0.35%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB             | 2         | 0.35%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 84     | 35.11%  |
| WDC                 | 61        | 89     | 32.45%  |
| Toshiba             | 21        | 24     | 11.17%  |
| Hitachi             | 14        | 15     | 7.45%   |
| Samsung Electronics | 9         | 12     | 4.79%   |
| Unknown             | 5         | 5      | 2.66%   |
| HGST                | 4         | 7      | 2.13%   |
| Fujitsu             | 3         | 3      | 1.6%    |
| Intenso             | 2         | 2      | 1.06%   |
| ASMT                | 1         | 1      | 0.53%   |
| ASMedia             | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 47     | 17.09%  |
| Kingston            | 28        | 38     | 14.07%  |
| Crucial             | 19        | 22     | 9.55%   |
| SanDisk             | 15        | 20     | 7.54%   |
| China               | 8         | 9      | 4.02%   |
| A-DATA Technology   | 8         | 9      | 4.02%   |
| WDC                 | 6         | 6      | 3.02%   |
| PNY                 | 6         | 7      | 3.02%   |
| Apple               | 6         | 6      | 3.02%   |
| Patriot             | 5         | 5      | 2.51%   |
| Intel               | 4         | 4      | 2.01%   |
| Transcend           | 3         | 5      | 1.51%   |
| Toshiba             | 3         | 3      | 1.51%   |
| Team                | 3         | 3      | 1.51%   |
| SPCC                | 3         | 3      | 1.51%   |
| SK hynix            | 3         | 3      | 1.51%   |
| KingSpec            | 3         | 3      | 1.51%   |
| GOODRAM             | 3         | 3      | 1.51%   |
| Unknown             | 3         | 4      | 1.51%   |
| Micron Technology   | 2         | 2      | 1.01%   |
| Gigabyte Technology | 2         | 4      | 1.01%   |
| Emtec               | 2         | 2      | 1.01%   |
| WINTEC              | 1         | 1      | 0.5%    |
| TakeMS              | 1         | 1      | 0.5%    |
| T-FORCE             | 1         | 1      | 0.5%    |
| SSD PHIS            | 1         | 1      | 0.5%    |
| SCCTS-603-001T      | 1         | 1      | 0.5%    |
| SABRENT             | 1         | 1      | 0.5%    |
| Phison              | 1         | 3      | 0.5%    |
| ORICO               | 1         | 1      | 0.5%    |
| OCZ-VERTEX          | 1         | 1      | 0.5%    |
| OCZ                 | 1         | 1      | 0.5%    |
| NGFF                | 1         | 1      | 0.5%    |
| Netac               | 1         | 1      | 0.5%    |
| Microtech           | 1         | 2      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| LITEON              | 1         | 1      | 0.5%    |
| Lexar               | 1         | 1      | 0.5%    |
| KODAK               | 1         | 1      | 0.5%    |
| Intenso             | 1         | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 176       | 244    | 36.14%  |
| HDD     | 164       | 244    | 33.68%  |
| NVMe    | 108       | 143    | 22.18%  |
| MMC     | 24        | 37     | 4.93%   |
| Unknown | 15        | 18     | 3.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 287       | 475    | 65.08%  |
| NVMe | 108       | 143    | 24.49%  |
| MMC  | 24        | 37     | 5.44%   |
| SAS  | 22        | 31     | 4.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 217       | 309    | 63.64%  |
| 0.51-1.0   | 88        | 130    | 25.81%  |
| 1.01-2.0   | 17        | 20     | 4.99%   |
| 3.01-4.0   | 6         | 9      | 1.76%   |
| 2.01-3.0   | 6         | 11     | 1.76%   |
| 4.01-10.0  | 6         | 8      | 1.76%   |
| 10.01-20.0 | 1         | 1      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 126       | 32.81%  |
| 251-500        | 93        | 24.22%  |
| 501-1000       | 49        | 12.76%  |
| 1001-2000      | 36        | 9.38%   |
| 51-100         | 25        | 6.51%   |
| 1-20           | 19        | 4.95%   |
| More than 3000 | 13        | 3.39%   |
| 21-50          | 12        | 3.13%   |
| 2001-3000      | 11        | 2.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 167       | 41.85%  |
| 21-50          | 79        | 19.8%   |
| 101-250        | 46        | 11.53%  |
| 51-100         | 46        | 11.53%  |
| 251-500        | 25        | 6.27%   |
| 501-1000       | 21        | 5.26%   |
| 1001-2000      | 7         | 1.75%   |
| 2001-3000      | 5         | 1.25%   |
| More than 3000 | 3         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 3.23%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 3.23%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 3.23%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 3.23%   |
| WDC WD10EZEX-60WN4A0 1TB              | 1         | 1      | 3.23%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 3.23%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 3.23%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 3.23%   |
| Toshiba HDWD110 1TB                   | 1         | 1      | 3.23%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 3.23%   |
| Seagate ST98823AS 80GB                | 1         | 1      | 3.23%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 3.23%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 3.23%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 3.23%   |
| Seagate ST3250318AS 250GB             | 1         | 1      | 3.23%   |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 3.23%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 980 PRO 1TB   | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 3.23%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 3.23%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 3.23%   |
| Samsung Electronics HD153WI 1TB       | 1         | 1      | 3.23%   |
| Phison ES 512GB                       | 1         | 1      | 3.23%   |
| Intenso SSD 256GB                     | 1         | 1      | 3.23%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 3.23%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 3.23%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 3.23%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.23%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 26.67%  |
| Samsung Electronics | 6         | 7      | 20%     |
| WDC                 | 4         | 5      | 13.33%  |
| Toshiba             | 3         | 3      | 10%     |
| Intel               | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| WINTEC              | 1         | 1      | 3.33%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Phison              | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 42.11%  |
| WDC                 | 4         | 5      | 21.05%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 20     | 62.07%  |
| SSD  | 7         | 7      | 24.14%  |
| NVMe | 4         | 5      | 13.79%  |

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
| Detected | 252       | 432    | 60.87%  |
| Works    | 133       | 222    | 32.13%  |
| Malfunc  | 29        | 32     | 7%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 259       | 55.58%  |
| AMD                            | 73        | 15.67%  |
| Samsung Electronics            | 38        | 8.15%   |
| SanDisk                        | 20        | 4.29%   |
| SK hynix                       | 12        | 2.58%   |
| Phison Electronics             | 10        | 2.15%   |
| Kingston Technology Company    | 6         | 1.29%   |
| Micron Technology              | 5         | 1.07%   |
| ASMedia Technology             | 5         | 1.07%   |
| Silicon Motion                 | 4         | 0.86%   |
| Nvidia                         | 4         | 0.86%   |
| Marvell Technology Group       | 4         | 0.86%   |
| JMicron Technology             | 4         | 0.86%   |
| Union Memory (Shenzhen)        | 3         | 0.64%   |
| Micron/Crucial Technology      | 3         | 0.64%   |
| KIOXIA                         | 3         | 0.64%   |
| Broadcom / LSI                 | 3         | 0.64%   |
| ADATA Technology               | 3         | 0.64%   |
| VIA Technologies               | 2         | 0.43%   |
| Toshiba America Info Systems   | 2         | 0.43%   |
| Solid State Storage Technology | 1         | 0.21%   |
| LSI Logic / Symbios Logic      | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 53        | 9.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 4.03%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 3.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 3.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 2.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 2.75%   |
| Samsung NVMe SSD Controller 980                                                  | 14        | 2.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 13        | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                           | 13        | 2.38%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 2.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10        | 1.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 9         | 1.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.47%   |
| Phison PS5013 E13 NVMe Controller                                                | 7         | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 1.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.28%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 1.1%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.92%   |
| Micron NVMe Storage Controller                                                   | 5         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 5         | 0.92%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 5         | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 0.92%   |
| AMD FCH SATA Controller D                                                        | 5         | 0.92%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 0.73%   |
| AMD 300 Series Chipset SATA Controller                                           | 4         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.55%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 288       | 58.42%  |
| NVMe | 109       | 22.11%  |
| IDE  | 51        | 10.34%  |
| RAID | 41        | 8.32%   |
| SAS  | 3         | 0.61%   |
| SCSI | 1         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 289       | 76.25%  |
| AMD    | 90        | 23.75%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 2.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 1.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6         | 1.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 1.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.32%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 1.32%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.32%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.05%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 1.05%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 1.05%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4         | 1.05%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 3         | 0.79%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.79%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.79%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.79%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 3         | 0.79%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.79%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.79%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 3         | 0.79%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz           | 2         | 0.53%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.53%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 2         | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.53%   |
| Intel Pentium CPU G645 @ 2.90GHz              | 2         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.53%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.53%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.53%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.53%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 0.53%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.53%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 74        | 19.47%  |
| Intel Core i7           | 49        | 12.89%  |
| Intel Core i3           | 32        | 8.42%   |
| Other                   | 31        | 8.16%   |
| AMD Ryzen 5             | 25        | 6.58%   |
| Intel Celeron           | 23        | 6.05%   |
| AMD Ryzen 7             | 21        | 5.53%   |
| Intel Core 2 Duo        | 18        | 4.74%   |
| Intel Pentium           | 14        | 3.68%   |
| Intel Atom              | 11        | 2.89%   |
| Intel Xeon              | 10        | 2.63%   |
| AMD Ryzen 3             | 8         | 2.11%   |
| Intel Pentium Dual-Core | 5         | 1.32%   |
| Intel Core 2            | 4         | 1.05%   |
| AMD E1                  | 4         | 1.05%   |
| AMD A4                  | 4         | 1.05%   |
| Intel Pentium Silver    | 3         | 0.79%   |
| Intel Pentium Gold      | 3         | 0.79%   |
| Intel Core 2 Quad       | 3         | 0.79%   |
| AMD Ryzen 9             | 3         | 0.79%   |
| AMD FX                  | 3         | 0.79%   |
| AMD Athlon              | 3         | 0.79%   |
| AMD A10                 | 3         | 0.79%   |
| Intel Pentium M         | 2         | 0.53%   |
| Intel Pentium Dual      | 2         | 0.53%   |
| Intel Pentium D         | 2         | 0.53%   |
| Intel Genuine           | 2         | 0.53%   |
| Intel Celeron M         | 2         | 0.53%   |
| AMD E2                  | 2         | 0.53%   |
| AMD Athlon II X2        | 2         | 0.53%   |
| AMD A8                  | 2         | 0.53%   |
| Intel Core i9           | 1         | 0.26%   |
| Intel Core 2 Extreme    | 1         | 0.26%   |
| AMD Phenom II X6        | 1         | 0.26%   |
| AMD Phenom II X4        | 1         | 0.26%   |
| AMD G                   | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD C-50                | 1         | 0.26%   |
| AMD Athlon II           | 1         | 0.26%   |
| AMD Athlon 64 X2        | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 177       | 46.58%  |
| 4      | 127       | 33.42%  |
| 8      | 29        | 7.63%   |
| 6      | 27        | 7.11%   |
| 1      | 11        | 2.89%   |
| 16     | 5         | 1.32%   |
| 12     | 2         | 0.53%   |
| 10     | 2         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 373       | 98.42%  |
| 2      | 6         | 1.58%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 246       | 64.74%  |
| 1      | 134       | 35.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 370       | 97.63%  |
| 32-bit         | 9         | 2.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 30        | 7.79%   |
| 0x206a7    | 22        | 5.71%   |
| 0x806c1    | 20        | 5.19%   |
| 0x306c3    | 16        | 4.16%   |
| 0x1067a    | 14        | 3.64%   |
| Unknown    | 14        | 3.64%   |
| 0x406e3    | 12        | 3.12%   |
| 0x40651    | 12        | 3.12%   |
| 0x08108109 | 12        | 3.12%   |
| 0x806ec    | 10        | 2.6%    |
| 0x6fd      | 9         | 2.34%   |
| 0x08608103 | 9         | 2.34%   |
| 0x20655    | 8         | 2.08%   |
| 0x806ea    | 7         | 1.82%   |
| 0x806e9    | 7         | 1.82%   |
| 0x706a8    | 7         | 1.82%   |
| 0x506e3    | 7         | 1.82%   |
| 0x406c4    | 7         | 1.82%   |
| 0x906ea    | 6         | 1.56%   |
| 0x906c0    | 6         | 1.56%   |
| 0x0a50000d | 6         | 1.56%   |
| 0x0800820d | 6         | 1.56%   |
| 0x106e5    | 5         | 1.3%    |
| 0x0a50000c | 5         | 1.3%    |
| 0x906ed    | 4         | 1.04%   |
| 0x906e9    | 4         | 1.04%   |
| 0x706e5    | 4         | 1.04%   |
| 0x6f6      | 4         | 1.04%   |
| 0x30661    | 4         | 1.04%   |
| 0x20652    | 4         | 1.04%   |
| 0x106c2    | 4         | 1.04%   |
| 0x10676    | 4         | 1.04%   |
| 0x08701021 | 4         | 1.04%   |
| 0x06006705 | 4         | 1.04%   |
| 0x06001119 | 4         | 1.04%   |
| 0xa0671    | 3         | 0.78%   |
| 0x806eb    | 3         | 0.78%   |
| 0x706a1    | 3         | 0.78%   |
| 0x6fb      | 3         | 0.78%   |
| 0x30678    | 3         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 41        | 10.76%  |
| IvyBridge        | 32        | 8.4%    |
| Haswell          | 29        | 7.61%   |
| SandyBridge      | 25        | 6.56%   |
| TigerLake        | 22        | 5.77%   |
| Zen+             | 20        | 5.25%   |
| Skylake          | 19        | 4.99%   |
| Penryn           | 18        | 4.72%   |
| Unknown          | 18        | 4.72%   |
| Core             | 17        | 4.46%   |
| Zen 3            | 15        | 3.94%   |
| Westmere         | 14        | 3.67%   |
| Silvermont       | 13        | 3.41%   |
| Goldmont plus    | 10        | 2.62%   |
| Bonnell          | 9         | 2.36%   |
| Zen              | 8         | 2.1%    |
| Zen 2            | 7         | 1.84%   |
| Piledriver       | 7         | 1.84%   |
| Excavator        | 7         | 1.84%   |
| Tremont          | 6         | 1.57%   |
| Nehalem          | 6         | 1.57%   |
| K10              | 5         | 1.31%   |
| IceLake          | 5         | 1.31%   |
| P6               | 4         | 1.05%   |
| CometLake        | 4         | 1.05%   |
| Puma             | 3         | 0.79%   |
| NetBurst         | 3         | 0.79%   |
| Jaguar           | 3         | 0.79%   |
| Broadwell        | 3         | 0.79%   |
| Bobcat           | 3         | 0.79%   |
| Goldmont         | 2         | 0.52%   |
| K8 Hammer        | 1         | 0.26%   |
| Bulldozer        | 1         | 0.26%   |
| Alderlake Hybrid | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 221       | 50.69%  |
| Nvidia | 119       | 27.29%  |
| AMD    | 96        | 22.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.19%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 3.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 3.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 3.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 1.99%   |
| AMD Lucienne                                                                             | 9         | 1.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 1.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.55%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 6         | 1.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 6         | 1.32%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.32%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.32%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.32%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 1.32%   |
| Intel HD Graphics 620                                                                    | 6         | 1.32%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.88%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.88%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 4         | 0.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 0.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 3         | 0.66%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.66%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.66%   |
| Intel HD Graphics 630                                                                    | 3         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 175       | 45.93%  |
| 1 x Nvidia     | 73        | 19.16%  |
| 1 x AMD        | 72        | 18.9%   |
| Intel + Nvidia | 36        | 9.45%   |
| AMD + Nvidia   | 9         | 2.36%   |
| 2 x AMD        | 8         | 2.1%    |
| Intel + AMD    | 7         | 1.84%   |
| Other          | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 314       | 81.98%  |
| Proprietary | 46        | 12.01%  |
| Unknown     | 23        | 6.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 207       | 53.77%  |
| 0.01-0.5   | 62        | 16.1%   |
| 1.01-2.0   | 55        | 14.29%  |
| 0.51-1.0   | 24        | 6.23%   |
| 3.01-4.0   | 18        | 4.68%   |
| 7.01-8.0   | 7         | 1.82%   |
| 5.01-6.0   | 7         | 1.82%   |
| 2.01-3.0   | 2         | 0.52%   |
| 8.01-16.0  | 2         | 0.52%   |
| 16.01-24.0 | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 13.71%  |
| LG Display              | 43        | 11.56%  |
| Samsung Electronics     | 39        | 10.48%  |
| Chimei Innolux          | 36        | 9.68%   |
| BOE                     | 33        | 8.87%   |
| Goldstar                | 16        | 4.3%    |
| Apple                   | 13        | 3.49%   |
| Dell                    | 12        | 3.23%   |
| Acer                    | 12        | 3.23%   |
| Hewlett-Packard         | 8         | 2.15%   |
| Chi Mei Optoelectronics | 8         | 2.15%   |
| BenQ                    | 8         | 2.15%   |
| Philips                 | 7         | 1.88%   |
| InfoVision              | 7         | 1.88%   |
| Unknown                 | 5         | 1.34%   |
| Sharp                   | 5         | 1.34%   |
| LG Philips              | 5         | 1.34%   |
| Lenovo                  | 5         | 1.34%   |
| Sony                    | 4         | 1.08%   |
| PANDA                   | 4         | 1.08%   |
| HannStar                | 4         | 1.08%   |
| Ancor Communications    | 4         | 1.08%   |
| ViewSonic               | 3         | 0.81%   |
| AOC                     | 3         | 0.81%   |
| SLD                     | 2         | 0.54%   |
| Sceptre Tech            | 2         | 0.54%   |
| Panasonic               | 2         | 0.54%   |
| Insignia                | 2         | 0.54%   |
| Iiyama                  | 2         | 0.54%   |
| DENON                   | 2         | 0.54%   |
| ___                     | 1         | 0.27%   |
| Vestel Elektronik       | 1         | 0.27%   |
| Unknown (XXX)           | 1         | 0.27%   |
| TR_                     | 1         | 0.27%   |
| SKY                     | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| PLN                     | 1         | 0.27%   |
| Planar                  | 1         | 0.27%   |
| Pioneer                 | 1         | 0.27%   |
| Packard Bell            | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 1.05%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.79%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 2         | 0.52%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch           | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.52%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch                  | 2         | 0.52%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch             | 2         | 0.52%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.52%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.52%   |
| InfoVision LCD Monitor IVO04E5 1366x768 276x155mm 12.5-inch              | 2         | 0.52%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 0.52%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.52%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 2         | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.52%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.52%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 2         | 0.52%   |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                    | 2         | 0.52%   |
| ___ LCDTV16 ___0101 1920x1080                                            | 1         | 0.26%   |
| ViewSonic VX3276-FHD VSCE735 1920x1080 698x393mm 31.5-inch               | 1         | 0.26%   |
| ViewSonic VG2756-4K VSC553A 3840x2160 597x336mm 27.0-inch                | 1         | 0.26%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch                 | 1         | 0.26%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch     | 1         | 0.26%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                       | 1         | 0.26%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                    | 1         | 0.26%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                     | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 151       | 41.83%  |
| 1366x768 (WXGA)    | 90        | 24.93%  |
| 1600x900 (HD+)     | 16        | 4.43%   |
| 3840x2160 (4K)     | 14        | 3.88%   |
| 1920x1200 (WUXGA)  | 12        | 3.32%   |
| 1680x1050 (WSXGA+) | 11        | 3.05%   |
| 1280x800 (WXGA)    | 10        | 2.77%   |
| 1440x900 (WXGA+)   | 8         | 2.22%   |
| 1280x1024 (SXGA)   | 7         | 1.94%   |
| 2560x1440 (QHD)    | 6         | 1.66%   |
| 1024x600           | 6         | 1.66%   |
| 3440x1440          | 5         | 1.39%   |
| 2560x1080          | 5         | 1.39%   |
| 1360x768           | 3         | 0.83%   |
| Unknown            | 3         | 0.83%   |
| 3840x1080          | 2         | 0.55%   |
| 2880x1800          | 2         | 0.55%   |
| 2560x1600          | 2         | 0.55%   |
| 1280x768           | 2         | 0.55%   |
| 4480x1440          | 1         | 0.28%   |
| 2256x1504          | 1         | 0.28%   |
| 1600x1200          | 1         | 0.28%   |
| 1280x720 (HD)      | 1         | 0.28%   |
| 1024x768 (XGA)     | 1         | 0.28%   |
| 1024x576           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 123       | 32.89%  |
| 13      | 42        | 11.23%  |
| Unknown | 27        | 7.22%   |
| 24      | 26        | 6.95%   |
| 14      | 25        | 6.68%   |
| 17      | 18        | 4.81%   |
| 21      | 15        | 4.01%   |
| 23      | 13        | 3.48%   |
| 27      | 11        | 2.94%   |
| 20      | 8         | 2.14%   |
| 34      | 7         | 1.87%   |
| 12      | 7         | 1.87%   |
| 11      | 7         | 1.87%   |
| 10      | 7         | 1.87%   |
| 18      | 6         | 1.6%    |
| 72      | 5         | 1.34%   |
| 22      | 5         | 1.34%   |
| 31      | 4         | 1.07%   |
| 19      | 4         | 1.07%   |
| 40      | 2         | 0.53%   |
| 32      | 2         | 0.53%   |
| 84      | 1         | 0.27%   |
| 64      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 33      | 1         | 0.27%   |
| 28      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |
| 8       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 171       | 46.85%  |
| 501-600     | 49        | 13.42%  |
| 201-300     | 39        | 10.68%  |
| 401-500     | 32        | 8.77%   |
| Unknown     | 27        | 7.4%    |
| 351-400     | 20        | 5.48%   |
| 701-800     | 10        | 2.74%   |
| 601-700     | 6         | 1.64%   |
| 1501-2000   | 6         | 1.64%   |
| 801-900     | 2         | 0.55%   |
| 1001-1500   | 2         | 0.55%   |
| 101-200     | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 260       | 74.71%  |
| 16/10   | 45        | 12.93%  |
| Unknown | 24        | 6.9%    |
| 21/9    | 9         | 2.59%   |
| 5/4     | 5         | 1.44%   |
| 4/3     | 4         | 1.15%   |
| 3/2     | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 122       | 32.88%  |
| 81-90          | 52        | 14.02%  |
| 201-250        | 46        | 12.4%   |
| Unknown        | 27        | 7.28%   |
| 71-80          | 15        | 4.04%   |
| 351-500        | 14        | 3.77%   |
| 251-300        | 13        | 3.5%    |
| 301-350        | 12        | 3.23%   |
| 151-200        | 12        | 3.23%   |
| 121-130        | 11        | 2.96%   |
| 141-150        | 9         | 2.43%   |
| More than 1000 | 8         | 2.16%   |
| 61-70          | 7         | 1.89%   |
| 51-60          | 7         | 1.89%   |
| 41-50          | 7         | 1.89%   |
| 131-140        | 4         | 1.08%   |
| 501-1000       | 2         | 0.54%   |
| 1-40           | 1         | 0.27%   |
| 111-120        | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 108       | 29.51%  |
| 101-120       | 104       | 28.42%  |
| 51-100        | 101       | 27.6%   |
| Unknown       | 27        | 7.38%   |
| 161-240       | 16        | 4.37%   |
| 1-50          | 6         | 1.64%   |
| More than 240 | 4         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 322       | 83.85%  |
| 2     | 38        | 9.9%    |
| 0     | 21        | 5.47%   |
| 3     | 3         | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 197       | 34.99%  |
| Intel                           | 181       | 32.15%  |
| Qualcomm Atheros                | 62        | 11.01%  |
| Broadcom                        | 37        | 6.57%   |
| TP-Link                         | 10        | 1.78%   |
| Broadcom Limited                | 10        | 1.78%   |
| MediaTek                        | 9         | 1.6%    |
| Marvell Technology Group        | 9         | 1.6%    |
| Ralink Technology               | 6         | 1.07%   |
| Ralink                          | 4         | 0.71%   |
| Nvidia                          | 4         | 0.71%   |
| Samsung Electronics             | 3         | 0.53%   |
| Xiaomi                          | 2         | 0.36%   |
| Spreadtrum Communications       | 2         | 0.36%   |
| NetGear                         | 2         | 0.36%   |
| Huawei Technologies             | 2         | 0.36%   |
| Google                          | 2         | 0.36%   |
| Dell                            | 2         | 0.36%   |
| VIA Technologies                | 1         | 0.18%   |
| Sierra Wireless                 | 1         | 0.18%   |
| Qualcomm Atheros Communications | 1         | 0.18%   |
| Qualcomm                        | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.18%   |
| Microsoft                       | 1         | 0.18%   |
| Microchip Technology            | 1         | 0.18%   |
| Mercucys                        | 1         | 0.18%   |
| Lenovo                          | 1         | 0.18%   |
| JMicron Technology              | 1         | 0.18%   |
| IMC Networks                    | 1         | 0.18%   |
| HTC (High Tech Computer)        | 1         | 0.18%   |
| Hewlett-Packard                 | 1         | 0.18%   |
| Foxconn / Hon Hai               | 1         | 0.18%   |
| Fibocom                         | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |
| Davicom Semiconductor           | 1         | 0.18%   |
| Belkin Components               | 1         | 0.18%   |
| ASUSTek Computer                | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 17.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 2.48%   |
| Intel Wireless 3165                                               | 13        | 1.9%    |
| Intel Wi-Fi 6 AX200                                               | 12        | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.6%    |
| Intel Wireless 8260                                               | 11        | 1.6%    |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.02%   |
| Intel Wireless 7265                                               | 7         | 1.02%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.02%   |
| Intel Ethernet Connection I219-V                                  | 7         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.87%   |
| Intel Wireless 7260                                               | 6         | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 0.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.73%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 4         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4         | 0.58%   |
| Intel WiFi Link 5100                                              | 4         | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 41.64%  |
| Realtek Semiconductor           | 76        | 23.1%   |
| Qualcomm Atheros                | 41        | 12.46%  |
| Broadcom                        | 29        | 8.81%   |
| MediaTek                        | 8         | 2.43%   |
| TP-Link                         | 7         | 2.13%   |
| Broadcom Limited                | 7         | 2.13%   |
| Ralink Technology               | 6         | 1.82%   |
| Ralink                          | 4         | 1.22%   |
| NetGear                         | 2         | 0.61%   |
| Xiaomi                          | 1         | 0.3%    |
| Sierra Wireless                 | 1         | 0.3%    |
| Qualcomm Atheros Communications | 1         | 0.3%    |
| Microsoft                       | 1         | 0.3%    |
| Mercucys                        | 1         | 0.3%    |
| Marvell Technology Group        | 1         | 0.3%    |
| IMC Networks                    | 1         | 0.3%    |
| Fibocom                         | 1         | 0.3%    |
| Edimax Technology               | 1         | 0.3%    |
| Dell                            | 1         | 0.3%    |
| Belkin Components               | 1         | 0.3%    |
| ASUSTek Computer                | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 5.01%   |
| Intel Wireless 3165                                                     | 13        | 3.83%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 3.54%   |
| Intel Wireless 8265 / 8275                                              | 11        | 3.24%   |
| Intel Wireless 8260                                                     | 11        | 3.24%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 3.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.36%   |
| Intel Wireless 7265                                                     | 7         | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 6         | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.77%   |
| Intel Wireless 7260                                                     | 6         | 1.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.47%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.18%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4         | 1.18%   |
| Intel WiFi Link 5100                                                    | 4         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.18%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.88%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.88%   |
| Realtek RTL8187B Wireless Adapter                                       | 3         | 0.88%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.88%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.88%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 168       | 49.56%  |
| Intel                         | 91        | 26.84%  |
| Qualcomm Atheros              | 30        | 8.85%   |
| Broadcom                      | 11        | 3.24%   |
| Marvell Technology Group      | 8         | 2.36%   |
| Nvidia                        | 4         | 1.18%   |
| TP-Link                       | 3         | 0.88%   |
| Samsung Electronics           | 3         | 0.88%   |
| Broadcom Limited              | 3         | 0.88%   |
| Spreadtrum Communications     | 2         | 0.59%   |
| Huawei Technologies           | 2         | 0.59%   |
| Google                        | 2         | 0.59%   |
| Xiaomi                        | 1         | 0.29%   |
| VIA Technologies              | 1         | 0.29%   |
| Qualcomm                      | 1         | 0.29%   |
| OnePlus Technology (Shenzhen) | 1         | 0.29%   |
| Microchip Technology          | 1         | 0.29%   |
| MediaTek                      | 1         | 0.29%   |
| Lenovo                        | 1         | 0.29%   |
| JMicron Technology            | 1         | 0.29%   |
| HTC (High Tech Computer)      | 1         | 0.29%   |
| Hewlett-Packard               | 1         | 0.29%   |
| Foxconn / Hon Hai             | 1         | 0.29%   |
| Davicom Semiconductor         | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 34.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 8.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 5.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 2.03%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.03%   |
| Intel Ethernet Connection I219-V                                  | 7         | 2.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.16%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.16%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.16%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.87%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 3         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.87%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.87%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.87%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.58%   |
| Spreadtrum Spreadtrum Phone                                       | 2         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.58%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.58%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.58%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 318       | 50.4%   |
| WiFi     | 311       | 49.29%  |
| Modem    | 2         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 223       | 56.31%  |
| Ethernet | 173       | 43.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 217       | 57.26%  |
| 1     | 148       | 39.05%  |
| 0     | 10        | 2.64%   |
| 3     | 4         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 265       | 69.01%  |
| Yes  | 119       | 30.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 47.73%  |
| Realtek Semiconductor           | 34        | 15.45%  |
| Lite-On Technology              | 11        | 5%      |
| Foxconn / Hon Hai               | 11        | 5%      |
| Broadcom                        | 11        | 5%      |
| Apple                           | 11        | 5%      |
| Cambridge Silicon Radio         | 9         | 4.09%   |
| Qualcomm Atheros Communications | 8         | 3.64%   |
| Dell                            | 5         | 2.27%   |
| Hewlett-Packard                 | 4         | 1.82%   |
| IMC Networks                    | 3         | 1.36%   |
| MediaTek                        | 2         | 0.91%   |
| Foxconn International           | 2         | 0.91%   |
| ISSC                            | 1         | 0.45%   |
| Dynex                           | 1         | 0.45%   |
| Chicony Electronics             | 1         | 0.45%   |
| Askey Computer                  | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 20.45%  |
| Realtek Bluetooth Radio                             | 23        | 10.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 8.18%   |
| Intel AX201 Bluetooth                               | 17        | 7.73%   |
| Intel AX200 Bluetooth                               | 11        | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 4.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 3.18%   |
| Intel AX210 Bluetooth                               | 5         | 2.27%   |
| Lite-On Bluetooth Device                            | 4         | 1.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.36%   |
| Intel Bluetooth Device                              | 3         | 1.36%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.36%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.36%   |
| Apple Bluetooth Host Controller                     | 3         | 1.36%   |
| Apple Bluetooth HCI                                 | 3         | 1.36%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.91%   |
| MediaTek Wireless_Device                            | 2         | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.91%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.91%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.91%   |
| Dell Wireless 370 Bluetooth Mini-card               | 2         | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.91%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.91%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.45%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.45%   |
| Lite-On Wireless_Device                             | 1         | 0.45%   |
| ISSC Bluetooth Device                               | 1         | 0.45%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.45%   |
| IMC Networks Bluetooth Device                       | 1         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 279       | 55.69%  |
| AMD                                  | 104       | 20.76%  |
| Nvidia                               | 89        | 17.76%  |
| C-Media Electronics                  | 6         | 1.2%    |
| Texas Instruments                    | 3         | 0.6%    |
| VIA Technologies                     | 2         | 0.4%    |
| Thesycon Systemsoftware & Consulting | 2         | 0.4%    |
| KTMicro                              | 2         | 0.4%    |
| JMTek                                | 2         | 0.4%    |
| GN Netcom                            | 2         | 0.4%    |
| Yamaha                               | 1         | 0.2%    |
| Turtle Beach                         | 1         | 0.2%    |
| Sony                                 | 1         | 0.2%    |
| Realtek Semiconductor                | 1         | 0.2%    |
| Native Instruments                   | 1         | 0.2%    |
| Micro Star International             | 1         | 0.2%    |
| Logitech                             | 1         | 0.2%    |
| Generalplus Technology               | 1         | 0.2%    |
| DCMT Technology                      | 1         | 0.2%    |
| Audioengine                          | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 44        | 7.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 5.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 4.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 21        | 3.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 20        | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 3.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 2.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 2.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.02%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.02%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.18%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.01%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.01%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.01%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 0.84%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 4         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 47        | 25.41%  |
| SK hynix                     | 29        | 15.68%  |
| Unknown                      | 24        | 12.97%  |
| Micron Technology            | 17        | 9.19%   |
| Kingston                     | 15        | 8.11%   |
| Corsair                      | 10        | 5.41%   |
| G.Skill                      | 7         | 3.78%   |
| Crucial                      | 7         | 3.78%   |
| Nanya Technology             | 4         | 2.16%   |
| A-DATA Technology            | 4         | 2.16%   |
| Unknown (ABCD)               | 3         | 1.62%   |
| Team                         | 2         | 1.08%   |
| Ramaxel Technology           | 2         | 1.08%   |
| GSkill                       | 2         | 1.08%   |
| Elpida                       | 2         | 1.08%   |
| Strontium                    | 1         | 0.54%   |
| Smart                        | 1         | 0.54%   |
| Patriot Memory (PDP Systems) | 1         | 0.54%   |
| Lexar Co Limited             | 1         | 0.54%   |
| KLEVV                        | 1         | 0.54%   |
| GeIL                         | 1         | 0.54%   |
| AVEXIR                       | 1         | 0.54%   |
| AMD                          | 1         | 0.54%   |
| 4ea5                         | 1         | 0.54%   |
| Unknown                      | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 1%      |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1%      |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1%      |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1%      |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1%      |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1%      |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1%      |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1%      |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 1%      |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 2         | 1%      |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.5%    |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.5%    |
| Unknown RAM Module 512MB DIMM DDR2 266MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 266MT/s                         | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 76        | 47.2%   |
| DDR3    | 54        | 33.54%  |
| DDR2    | 13        | 8.07%   |
| LPDDR4  | 7         | 4.35%   |
| SDRAM   | 6         | 3.73%   |
| LPDDR3  | 2         | 1.24%   |
| Unknown | 2         | 1.24%   |
| DDR     | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 110       | 68.32%  |
| DIMM         | 40        | 24.84%  |
| Row Of Chips | 8         | 4.97%   |
| Unknown      | 2         | 1.24%   |
| Chip         | 1         | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 62        | 34.83%  |
| 4096  | 43        | 24.16%  |
| 2048  | 34        | 19.1%   |
| 16384 | 23        | 12.92%  |
| 32768 | 6         | 3.37%   |
| 1024  | 6         | 3.37%   |
| 512   | 4         | 2.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 36        | 20.93%  |
| 1600    | 33        | 19.19%  |
| 2667    | 23        | 13.37%  |
| 2400    | 13        | 7.56%   |
| 2133    | 9         | 5.23%   |
| 1333    | 8         | 4.65%   |
| 1334    | 7         | 4.07%   |
| 1067    | 6         | 3.49%   |
| 667     | 6         | 3.49%   |
| Unknown | 6         | 3.49%   |
| 3600    | 5         | 2.91%   |
| 533     | 3         | 1.74%   |
| 4199    | 2         | 1.16%   |
| 1867    | 2         | 1.16%   |
| 1866    | 2         | 1.16%   |
| 4267    | 1         | 0.58%   |
| 3733    | 1         | 0.58%   |
| 3533    | 1         | 0.58%   |
| 3266    | 1         | 0.58%   |
| 2267    | 1         | 0.58%   |
| 2048    | 1         | 0.58%   |
| 1800    | 1         | 0.58%   |
| 1200    | 1         | 0.58%   |
| 1066    | 1         | 0.58%   |
| 800     | 1         | 0.58%   |
| 266     | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Seiko Epson        | 1         | 20%     |
| Konica Minolta     | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson ET-2820 Series | 1         | 20%     |
| Konica Minolta 185         | 1         | 20%     |
| HP OfficeJet Pro 8730      | 1         | 20%     |
| HP DeskJet 2130 series     | 1         | 20%     |
| Brother MFC-L2685DW        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 47        | 20%     |
| Microdia                               | 27        | 11.49%  |
| IMC Networks                           | 21        | 8.94%   |
| Suyin                                  | 15        | 6.38%   |
| Realtek Semiconductor                  | 15        | 6.38%   |
| Sunplus Innovation Technology          | 14        | 5.96%   |
| Quanta                                 | 12        | 5.11%   |
| Acer                                   | 10        | 4.26%   |
| Luxvisions Innotech Limited            | 8         | 3.4%    |
| Logitech                               | 8         | 3.4%    |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.4%    |
| Bison Electronics                      | 8         | 3.4%    |
| Apple                                  | 7         | 2.98%   |
| Syntek                                 | 5         | 2.13%   |
| Alcor Micro                            | 5         | 2.13%   |
| Importek                               | 3         | 1.28%   |
| Z-Star Microelectronics                | 2         | 0.85%   |
| Silicon Motion                         | 2         | 0.85%   |
| Lenovo                                 | 2         | 0.85%   |
| Huawei Technologies                    | 2         | 0.85%   |
| Creative Technology                    | 2         | 0.85%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.43%   |
| Samsung Electronics                    | 1         | 0.43%   |
| Pixart Imaging                         | 1         | 0.43%   |
| OmniVision Technologies                | 1         | 0.43%   |
| MacroSilicon                           | 1         | 0.43%   |
| Lite-On Technology                     | 1         | 0.43%   |
| Intel                                  | 1         | 0.43%   |
| icSpring                               | 1         | 0.43%   |
| eMPIA Technology                       | 1         | 0.43%   |
| ARC International                      | 1         | 0.43%   |
| Alpha Imaging Technology               | 1         | 0.43%   |
| ALi                                    | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 15        | 6.3%    |
| Microdia Integrated_Webcam_HD                                  | 14        | 5.88%   |
| IMC Networks Integrated Camera                                 | 6         | 2.52%   |
| Realtek USB Camera                                             | 5         | 2.1%    |
| Chicony HD Webcam                                              | 5         | 2.1%    |
| Syntek Integrated Camera                                       | 4         | 1.68%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 1.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 1.68%   |
| Chicony HP TrueVision HD Camera                                | 4         | 1.68%   |
| Bison Integrated Camera                                        | 4         | 1.68%   |
| Apple Built-in iSight                                          | 4         | 1.68%   |
| Acer Integrated Camera                                         | 4         | 1.68%   |
| Sunplus FHD Camera Microphone                                  | 3         | 1.26%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.26%   |
| Microdia CameraA                                               | 3         | 1.26%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 1.26%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 3         | 1.26%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 1.26%   |
| Suyin HP TrueVision HD                                         | 2         | 0.84%   |
| Suyin HD WebCam                                                | 2         | 0.84%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 2         | 0.84%   |
| Suyin Acer HD Crystal Eye webcam                               | 2         | 0.84%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 0.84%   |
| Sunplus HD WebCam                                              | 2         | 0.84%   |
| Quanta HP Webcam                                               | 2         | 0.84%   |
| Quanta HP HD Camera                                            | 2         | 0.84%   |
| Microdia Lenovo EasyCamera                                     | 2         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_E4HD                         | 2         | 0.84%   |
| Logitech Webcam C270                                           | 2         | 0.84%   |
| IMC Networks EasyCamera                                        | 2         | 0.84%   |
| Huawei UVC Camera                                              | 2         | 0.84%   |
| Chicony TOSHIBA Web Camera - FHD                               | 2         | 0.84%   |
| Chicony HP HD Camera                                           | 2         | 0.84%   |
| Chicony Camera                                                 | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 0.84%   |
| Bison USB2.0 Camera                                            | 2         | 0.84%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 0.84%   |
| Acer BisonCam, NB Pro                                          | 2         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 42.86%  |
| Synaptics                  | 4         | 11.43%  |
| AuthenTec                  | 4         | 11.43%  |
| Upek                       | 3         | 8.57%   |
| STMicroelectronics         | 2         | 5.71%   |
| Shenzhen Goodix Technology | 2         | 5.71%   |
| Samsung Electronics        | 1         | 2.86%   |
| Microsoft                  | 1         | 2.86%   |
| LighTuning Technology      | 1         | 2.86%   |
| Focal-systems.Corp         | 1         | 2.86%   |
| Elan Microelectronics      | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 8.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 8.57%   |
| Validity Sensors Synaptics WBDI                          | 2         | 5.71%   |
| Validity Sensors Fingerprint scanner                     | 2         | 5.71%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 5.71%   |
| STMicroelectronics Fingerprint Reader                    | 2         | 5.71%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 5.71%   |
| AuthenTec AES1600                                        | 2         | 5.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 2.86%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 2.86%   |
| Validity Sensors VFS491                                  | 1         | 2.86%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 2.86%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 2.86%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 2.86%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 2.86%   |
| Synaptics WBDI                                           | 1         | 2.86%   |
| Synaptics UWP WBDI Device                                | 1         | 2.86%   |
| Samsung Fingerprint Sensor Device - 730B                 | 1         | 2.86%   |
| Microsoft Fingerprint Reader                             | 1         | 2.86%   |
| LighTuning Fingerprint Reader                            | 1         | 2.86%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 2.86%   |
| Elan ELAN:Fingerprint                                    | 1         | 2.86%   |
| AuthenTec Fingerprint Sensor                             | 1         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 57.14%  |
| O2 Micro    | 2         | 14.29%  |
| Alcor Micro | 2         | 14.29%  |
| Upek        | 1         | 7.14%   |
| Lenovo      | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 4         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 14.29%  |
| Broadcom 5880                                              | 2         | 14.29%  |
| Broadcom 58200                                             | 2         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.14%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 260       | 67.01%  |
| 1     | 106       | 27.32%  |
| 2     | 17        | 4.38%   |
| 3     | 3         | 0.77%   |
| 4     | 2         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 39        | 25%     |
| Graphics card            | 38        | 24.36%  |
| Fingerprint reader       | 34        | 21.79%  |
| Multimedia controller    | 19        | 12.18%  |
| Chipcard                 | 13        | 8.33%   |
| Communication controller | 4         | 2.56%   |
| Bluetooth                | 2         | 1.28%   |
| Unassigned class         | 1         | 0.64%   |
| Storage/raid             | 1         | 0.64%   |
| Storage                  | 1         | 0.64%   |
| Flash memory             | 1         | 0.64%   |
| Dvb card                 | 1         | 0.64%   |
| Card reader              | 1         | 0.64%   |
| Camera                   | 1         | 0.64%   |

