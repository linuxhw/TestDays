LMDE 5 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

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

Total: 349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [3eb12fd9bc](https://linux-hardware.org/?probe=3eb12fd9bc) | Jun 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| Google        | Lick                        | [d220804cab](https://linux-hardware.org/?probe=d220804cab) | Jun 08, 2023 |
| Dell          | G5 5587                     | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| Acer          | Aspire 7745G                | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Dell          | Inspiron N4030              | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | G50-45 80E3                 | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Framework     | Laptop                      | [cdc855ea4c](https://linux-hardware.org/?probe=cdc855ea4c) | May 26, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| Dell          | Latitude E6520              | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Timi          | RedmiBook 14-APCS           | [04d3c59d2c](https://linux-hardware.org/?probe=04d3c59d2c) | May 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Acer          | Aspire A515-56              | [feb9ed8589](https://linux-hardware.org/?probe=feb9ed8589) | May 19, 2023 |
| Acer          | Aspire A515-56              | [42d9eb5bf8](https://linux-hardware.org/?probe=42d9eb5bf8) | May 13, 2023 |
| Acer          | Aspire A515-56              | [7c946d461d](https://linux-hardware.org/?probe=7c946d461d) | May 13, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| Dell          | Latitude 7400               | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| AZW           | SEi                         | [4cd6ab54ba](https://linux-hardware.org/?probe=4cd6ab54ba) | May 08, 2023 |
| Medion        | E6214                       | [869c63244c](https://linux-hardware.org/?probe=869c63244c) | May 06, 2023 |
| Medion        | E6214                       | [64eeb6e165](https://linux-hardware.org/?probe=64eeb6e165) | May 06, 2023 |
| HP            | Compaq Presario CQ60        | [c8347acd5d](https://linux-hardware.org/?probe=c8347acd5d) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Dell          | Latitude 7480               | [fd7043408f](https://linux-hardware.org/?probe=fd7043408f) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [3e42d222a0](https://linux-hardware.org/?probe=3e42d222a0) | May 02, 2023 |
| Dell          | Studio 1555                 | [4f9f0dc9bf](https://linux-hardware.org/?probe=4f9f0dc9bf) | May 01, 2023 |
| Lenovo        | 4068AGJ                     | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| HP            | Compaq 15                   | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| Medion        | E6214                       | [7bb9f39d76](https://linux-hardware.org/?probe=7bb9f39d76) | Apr 30, 2023 |
| Medion        | E6214                       | [39747632e6](https://linux-hardware.org/?probe=39747632e6) | Apr 30, 2023 |
| Toshiba       | Satellite C850-D8K          | [a27eb72e94](https://linux-hardware.org/?probe=a27eb72e94) | Apr 29, 2023 |
| HP            | 250 G7 Notebook PC          | [e5fe9aa407](https://linux-hardware.org/?probe=e5fe9aa407) | Apr 29, 2023 |
| Insyde        | CherryTrail                 | [73e11e9235](https://linux-hardware.org/?probe=73e11e9235) | Apr 29, 2023 |
| Toshiba       | Satellite C850-D8K          | [f2f50094ba](https://linux-hardware.org/?probe=f2f50094ba) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| GPU Compan... | GWTN156-5                   | [60d207eb63](https://linux-hardware.org/?probe=60d207eb63) | Apr 27, 2023 |
| GPU Compan... | GWTN156-5                   | [df6b1e8e17](https://linux-hardware.org/?probe=df6b1e8e17) | Apr 26, 2023 |
| GPU Compan... | GWTN156-5                   | [a22605adc9](https://linux-hardware.org/?probe=a22605adc9) | Apr 25, 2023 |
| Acer          | Aspire A515-56              | [a3a13c5cb1](https://linux-hardware.org/?probe=a3a13c5cb1) | Apr 24, 2023 |
| Acer          | Aspire A515-56              | [1d5b5dcfc7](https://linux-hardware.org/?probe=1d5b5dcfc7) | Apr 24, 2023 |
| LG Electro... | A530-T.BE76P1               | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| GPU Compan... | GWTN156-2BK                 | [3f172b49f2](https://linux-hardware.org/?probe=3f172b49f2) | Apr 21, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [ac404082b4](https://linux-hardware.org/?probe=ac404082b4) | Apr 18, 2023 |
| Apple         | MacBookPro9,2               | [9f2a7943c7](https://linux-hardware.org/?probe=9f2a7943c7) | Apr 17, 2023 |
| Gear          | Geranium                    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Medion        | E6214                       | [ff06e74c6d](https://linux-hardware.org/?probe=ff06e74c6d) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| Medion        | E6214                       | [ab33cd63b8](https://linux-hardware.org/?probe=ab33cd63b8) | Apr 16, 2023 |
| Apple         | MacBookPro11,1              | [12cb955c6f](https://linux-hardware.org/?probe=12cb955c6f) | Apr 15, 2023 |
| Unknown       | Unknown                     | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HP            | ZBook 15 G4                 | [816bb7a55c](https://linux-hardware.org/?probe=816bb7a55c) | Apr 06, 2023 |
| Dell          | Precision M4800             | [9283851416](https://linux-hardware.org/?probe=9283851416) | Apr 06, 2023 |
| Kruger&Mat... | KM1406                      | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| GPU Compan... | GWTN156-2BK                 | [3ebdd0188a](https://linux-hardware.org/?probe=3ebdd0188a) | Apr 05, 2023 |
| HP            | 250 G7 Notebook PC          | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Medion        | E6214                       | [79f326e572](https://linux-hardware.org/?probe=79f326e572) | Apr 01, 2023 |
| Medion        | E6214                       | [5766389c97](https://linux-hardware.org/?probe=5766389c97) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Medion        | E6214                       | [298e2f9c69](https://linux-hardware.org/?probe=298e2f9c69) | Mar 31, 2023 |
| HP            | Pavilion dm4                | [b7f2f9e2ab](https://linux-hardware.org/?probe=b7f2f9e2ab) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [6ac9c53a7e](https://linux-hardware.org/?probe=6ac9c53a7e) | Mar 26, 2023 |
| Medion        | E6214                       | [8ff346be04](https://linux-hardware.org/?probe=8ff346be04) | Mar 26, 2023 |
| Haier         | S15                         | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| Acer          | Aspire E1-572G              | [ce4febfe16](https://linux-hardware.org/?probe=ce4febfe16) | Mar 25, 2023 |
| Haier         | S15                         | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| Toshiba       | Satellite Pro A50-C         | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| Star Labs     | StarBook                    | [b3957ad08f](https://linux-hardware.org/?probe=b3957ad08f) | Mar 22, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| Acer          | Swift SF314-51              | [b410a4c017](https://linux-hardware.org/?probe=b410a4c017) | Mar 14, 2023 |
| HP            | Pavilion dv6                | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| Dell          | Inspiron 5515               | [22dd14abae](https://linux-hardware.org/?probe=22dd14abae) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z61m 9450HAG       | [5aa66edd35](https://linux-hardware.org/?probe=5aa66edd35) | Mar 04, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| HIPER         | WORKBOOK                    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
| Toshiba       | Satellite L300              | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | 2000                        | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| itel Mobil... | SPIRIT 2                    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Compaq        | 420                         | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Star Labs     | StarBook                    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| Dell          | Precision M4800             | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Samsung       | RV415/RV515                 | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Compaq        | 420                         | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| Fujitsu       | M2010                       | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| Google        | Candy                       | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| Chuwi         | GemiBook Pro                | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| Google        | Ultima                      | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| Apple         | MacBookPro13,3              | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| HP            | Laptop 15s-fq2xxx           | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| HP            | 250 G8 Notebook PC          | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| Acer          | Aspire E1-570G              | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | EliteBook 820 G3            | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Sony          | SVF1532W4E                  | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Toshiba       | Satellite L855D             | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| Dell          | XPS L701X                   | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| HP            | Laptop 14-cf3xxx            | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Medion        | P15648                      | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Lenovo        | Yoga 2 11 20332             | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| Acer          | Aspire 5930                 | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | Latitude E6330              | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Lenovo        | G500 20236                  | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| Microtech     | ebookPro                    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Framework     | Laptop                      | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | Laptop 14-dk1xxx            | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| AMI           | T3 MRD                      | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| HP            | 255 G5 Notebook PC          | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Multilaser    | PC150                       | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron 5566               | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.0-21-amd64          | 43        | 16.54%  |
| 5.10.0-12-amd64          | 32        | 12.31%  |
| 5.10.0-19-amd64          | 29        | 11.15%  |
| 5.10.0-14-amd64          | 20        | 7.69%   |
| 5.10.0-20-amd64          | 17        | 6.54%   |
| 5.10.0-15-amd64          | 16        | 6.15%   |
| 5.10.0-18-amd64          | 14        | 5.38%   |
| 5.10.0-13-amd64          | 14        | 5.38%   |
| 5.10.0-23-amd64          | 12        | 4.62%   |
| 5.10.0-16-amd64          | 11        | 4.23%   |
| 5.10.0-17-amd64          | 9         | 3.46%   |
| 5.10.0-22-amd64          | 7         | 2.69%   |
| 5.10.0-13-686            | 5         | 1.92%   |
| 5.18.0-0.bpo.1-amd64     | 4         | 1.54%   |
| 5.16.0-0.bpo.4-amd64     | 4         | 1.54%   |
| 6.1.0-0.deb11.6-amd64    | 2         | 0.77%   |
| 5.19.0-0.deb11.2-amd64   | 2         | 0.77%   |
| 5.10.0-12-686            | 2         | 0.77%   |
| 6.1.11-x64v1-xanmod1     | 1         | 0.38%   |
| 6.1.0-0.deb11.6-rt-amd64 | 1         | 0.38%   |
| 6.1.0-0.deb11.5-amd64    | 1         | 0.38%   |
| 5.19.10-xanmod1          | 1         | 0.38%   |
| 5.18.0-4-amd64           | 1         | 0.38%   |
| 5.18.0-3-amd64           | 1         | 0.38%   |
| 5.16.0-0.bpo.3-amd64     | 1         | 0.38%   |
| 5.15.78-xanmod1          | 1         | 0.38%   |
| 5.15.70-xanmod1          | 1         | 0.38%   |
| 5.15.0-0.bpo.3-amd64     | 1         | 0.38%   |
| 5.10.0-22-686            | 1         | 0.38%   |
| 5.10.0-21-686            | 1         | 0.38%   |
| 5.10.0-20-686            | 1         | 0.38%   |
| 5.10.0-19-686            | 1         | 0.38%   |
| 5.10.0-17-686            | 1         | 0.38%   |
| 5.10.0-14-686            | 1         | 0.38%   |
| 4.19.0-23-amd64          | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 222       | 90.98%  |
| 5.18.0  | 6         | 2.46%   |
| 6.1.0   | 4         | 1.64%   |
| 5.16.0  | 4         | 1.64%   |
| 5.19.0  | 2         | 0.82%   |
| 6.1.11  | 1         | 0.41%   |
| 5.19.10 | 1         | 0.41%   |
| 5.15.78 | 1         | 0.41%   |
| 5.15.70 | 1         | 0.41%   |
| 5.15.0  | 1         | 0.41%   |
| 4.19.0  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 222       | 91.36%  |
| 5.18    | 6         | 2.47%   |
| 6.1     | 5         | 2.06%   |
| 5.16    | 4         | 1.65%   |
| 5.19    | 3         | 1.23%   |
| 5.15    | 2         | 0.82%   |
| 4.19    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 225       | 94.54%  |
| i686   | 13        | 5.46%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 202       | 84.17%  |
| Cinnamon   | 30        | 12.5%   |
| MATE       | 3         | 1.25%   |
| XFCE       | 1         | 0.42%   |
| i3         | 1         | 0.42%   |
| GNOME      | 1         | 0.42%   |
| awesome    | 1         | 0.42%   |
| Unknown    | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 238       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 133       | 55.42%  |
| LightDM | 107       | 44.58%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 81        | 33.89%  |
| de_DE | 35        | 14.64%  |
| ru_RU | 23        | 9.62%   |
| pt_BR | 14        | 5.86%   |
| en_GB | 13        | 5.44%   |
| fr_FR | 9         | 3.77%   |
| it_IT | 8         | 3.35%   |
| pl_PL | 7         | 2.93%   |
| es_ES | 6         | 2.51%   |
| es_MX | 4         | 1.67%   |
| el_GR | 3         | 1.26%   |
| tr_TR | 2         | 0.84%   |
| pt_PT | 2         | 0.84%   |
| ko_KR | 2         | 0.84%   |
| es_BO | 2         | 0.84%   |
| en_NZ | 2         | 0.84%   |
| en_IE | 2         | 0.84%   |
| da_DK | 2         | 0.84%   |
| cs_CZ | 2         | 0.84%   |
| zh_CN | 1         | 0.42%   |
| sv_SE | 1         | 0.42%   |
| sl_SI | 1         | 0.42%   |
| nn_NO | 1         | 0.42%   |
| nl_AW | 1         | 0.42%   |
| ja_JP | 1         | 0.42%   |
| hu_HU | 1         | 0.42%   |
| fr_BE | 1         | 0.42%   |
| fi_FI | 1         | 0.42%   |
| es_VE | 1         | 0.42%   |
| es_PE | 1         | 0.42%   |
| es_EC | 1         | 0.42%   |
| es_CR | 1         | 0.42%   |
| es_CL | 1         | 0.42%   |
| es_AR | 1         | 0.42%   |
| en_SG | 1         | 0.42%   |
| en_IN | 1         | 0.42%   |
| en_CA | 1         | 0.42%   |
| de_CH | 1         | 0.42%   |
| de_AT | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 155       | 64.85%  |
| BIOS | 84        | 35.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 218       | 91.21%  |
| Overlay | 9         | 3.77%   |
| Btrfs   | 6         | 2.51%   |
| Tmpfs   | 4         | 1.67%   |
| Xfs     | 2         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 132       | 55%     |
| GPT     | 77        | 32.08%  |
| MBR     | 31        | 12.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 92.05%  |
| Yes       | 19        | 7.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 207       | 86.61%  |
| Yes       | 32        | 13.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 52        | 21.85%  |
| Lenovo              | 49        | 20.59%  |
| Dell                | 33        | 13.87%  |
| Acer                | 21        | 8.82%   |
| ASUSTek Computer    | 15        | 6.3%    |
| Toshiba             | 10        | 4.2%    |
| Apple               | 9         | 3.78%   |
| Google              | 4         | 1.68%   |
| Sony                | 3         | 1.26%   |
| Medion              | 3         | 1.26%   |
| Fujitsu             | 3         | 1.26%   |
| Unknown             | 3         | 1.26%   |
| Star Labs           | 2         | 0.84%   |
| Samsung Electronics | 2         | 0.84%   |
| MSI                 | 2         | 0.84%   |
| Compaq              | 2         | 0.84%   |
| Alienware           | 2         | 0.84%   |
| Wortmann AG         | 1         | 0.42%   |
| TUXEDO              | 1         | 0.42%   |
| Timi                | 1         | 0.42%   |
| Philco              | 1         | 0.42%   |
| Packard Bell        | 1         | 0.42%   |
| Multilaser          | 1         | 0.42%   |
| Microtech           | 1         | 0.42%   |
| LincPlus            | 1         | 0.42%   |
| LG Electronics      | 1         | 0.42%   |
| Kruger&Matz         | 1         | 0.42%   |
| itel Mobile Limited | 1         | 0.42%   |
| Insyde              | 1         | 0.42%   |
| HUAWEI              | 1         | 0.42%   |
| Howard Computers    | 1         | 0.42%   |
| HIPER               | 1         | 0.42%   |
| GPU Company         | 1         | 0.42%   |
| Gear                | 1         | 0.42%   |
| Fujitsu Siemens     | 1         | 0.42%   |
| Framework           | 1         | 0.42%   |
| Dynabook            | 1         | 0.42%   |
| Dixonsxp            | 1         | 0.42%   |
| AZW                 | 1         | 0.42%   |
| AMI                 | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 5         | 2.1%    |
| Star Labs StarBook                  | 2         | 0.84%   |
| Lenovo IdeaPad 3 15ITL6 82H8        | 2         | 0.84%   |
| Lenovo IdeaPad 3 15ADA05 81W1       | 2         | 0.84%   |
| Lenovo G500 20236                   | 2         | 0.84%   |
| HP Pavilion Notebook                | 2         | 0.84%   |
| HP Pavilion dv6                     | 2         | 0.84%   |
| HP Notebook                         | 2         | 0.84%   |
| HP Laptop 15z-ef2xxx                | 2         | 0.84%   |
| HP Laptop 15-dw3xxx                 | 2         | 0.84%   |
| HP 250 G8 Notebook PC               | 2         | 0.84%   |
| HP 250 G7 Notebook PC               | 2         | 0.84%   |
| Dell Latitude E6400                 | 2         | 0.84%   |
| Dell Latitude E5540                 | 2         | 0.84%   |
| Compaq 420                          | 2         | 0.84%   |
| Apple MacBookPro11,1                | 2         | 0.84%   |
| Acer Aspire E1-570G                 | 2         | 0.84%   |
| Acer Aspire 7745G                   | 2         | 0.84%   |
| Acer Aspire 5930                    | 2         | 0.84%   |
| Wortmann AG TERRA_MOBILE_1713A      | 1         | 0.42%   |
| TUXEDO N8xxEZ                       | 1         | 0.42%   |
| Toshiba Satellite Pro A50-C         | 1         | 0.42%   |
| Toshiba Satellite M55               | 1         | 0.42%   |
| Toshiba Satellite L855D             | 1         | 0.42%   |
| Toshiba Satellite L455              | 1         | 0.42%   |
| Toshiba Satellite L305              | 1         | 0.42%   |
| Toshiba Satellite L300D             | 1         | 0.42%   |
| Toshiba Satellite L300              | 1         | 0.42%   |
| Toshiba Satellite C850-D8K          | 1         | 0.42%   |
| Toshiba PORTEGE Z30-B               | 1         | 0.42%   |
| Toshiba PORTEGE M780                | 1         | 0.42%   |
| Timi RedmiBook 14-APCS              | 1         | 0.42%   |
| Sony SVF1532W4E                     | 1         | 0.42%   |
| Sony SVE1713Y1RB                    | 1         | 0.42%   |
| Sony SVE1512G1RW                    | 1         | 0.42%   |
| Samsung RV415/RV515                 | 1         | 0.42%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.42%   |
| Philco 10D                          | 1         | 0.42%   |
| Packard Bell DOT S                  | 1         | 0.42%   |
| Multilaser PC150                    | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 22        | 9.24%   |
| Acer Aspire        | 18        | 7.56%   |
| Lenovo IdeaPad     | 12        | 5.04%   |
| Dell Latitude      | 12        | 5.04%   |
| HP Laptop          | 11        | 4.62%   |
| Toshiba Satellite  | 8         | 3.36%   |
| Dell Inspiron      | 8         | 3.36%   |
| HP Pavilion        | 7         | 2.94%   |
| HP EliteBook       | 6         | 2.52%   |
| ASUS VivoBook      | 5         | 2.1%    |
| Unknown            | 5         | 2.1%    |
| HP ProBook         | 4         | 1.68%   |
| HP 250             | 4         | 1.68%   |
| Dell Precision     | 4         | 1.68%   |
| HP ZBook           | 3         | 1.26%   |
| HP Compaq          | 3         | 1.26%   |
| Dell Vostro        | 3         | 1.26%   |
| Toshiba PORTEGE    | 2         | 0.84%   |
| Star Labs StarBook | 2         | 0.84%   |
| Lenovo ThinkBook   | 2         | 0.84%   |
| Lenovo Legion      | 2         | 0.84%   |
| Lenovo G500        | 2         | 0.84%   |
| HP Notebook        | 2         | 0.84%   |
| HP 255             | 2         | 0.84%   |
| Fujitsu LIFEBOOK   | 2         | 0.84%   |
| Dell XPS           | 2         | 0.84%   |
| Compaq 420         | 2         | 0.84%   |
| ASUS ROG           | 2         | 0.84%   |
| Apple MacBookPro11 | 2         | 0.84%   |
| Wortmann AG TERRA  | 1         | 0.42%   |
| TUXEDO N8xxEZ      | 1         | 0.42%   |
| Timi RedmiBook     | 1         | 0.42%   |
| Sony SVF1532W4E    | 1         | 0.42%   |
| Sony SVE1713Y1RB   | 1         | 0.42%   |
| Sony SVE1512G1RW   | 1         | 0.42%   |
| Samsung RV415      | 1         | 0.42%   |
| Samsung 355V4C     | 1         | 0.42%   |
| Philco 10D         | 1         | 0.42%   |
| Packard Bell DOT   | 1         | 0.42%   |
| Multilaser PC150   | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 32        | 13.45%  |
| 2020 | 22        | 9.24%   |
| 2013 | 18        | 7.56%   |
| 2010 | 18        | 7.56%   |
| 2012 | 16        | 6.72%   |
| 2019 | 15        | 6.3%    |
| 2016 | 15        | 6.3%    |
| 2017 | 14        | 5.88%   |
| 2018 | 13        | 5.46%   |
| 2022 | 11        | 4.62%   |
| 2015 | 11        | 4.62%   |
| 2011 | 11        | 4.62%   |
| 2008 | 11        | 4.62%   |
| 2009 | 10        | 4.2%    |
| 2014 | 8         | 3.36%   |
| 2007 | 5         | 2.1%    |
| 2023 | 4         | 1.68%   |
| 2006 | 4         | 1.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 238       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 215       | 89.96%  |
| Enabled  | 24        | 10.04%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 231       | 97.06%  |
| Yes  | 7         | 2.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 71        | 29.83%  |
| 3.01-4.0    | 57        | 23.95%  |
| 16.01-24.0  | 37        | 15.55%  |
| 8.01-16.0   | 35        | 14.71%  |
| 1.01-2.0    | 13        | 5.46%   |
| 32.01-64.0  | 10        | 4.2%    |
| 2.01-3.0    | 9         | 3.78%   |
| 64.01-256.0 | 5         | 2.1%    |
| 0.51-1.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 106       | 42.06%  |
| 2.01-3.0   | 84        | 33.33%  |
| 3.01-4.0   | 26        | 10.32%  |
| 4.01-8.0   | 20        | 7.94%   |
| 0.51-1.0   | 14        | 5.56%   |
| 32.01-64.0 | 1         | 0.4%    |
| 8.01-16.0  | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 181       | 75.1%   |
| 2      | 49        | 20.33%  |
| 3      | 9         | 3.73%   |
| 4      | 1         | 0.41%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 160       | 66.95%  |
| Yes       | 79        | 33.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 78.99%  |
| No        | 50        | 21.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 235       | 98.74%  |
| No        | 3         | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 69.46%  |
| No        | 73        | 30.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 39        | 16.25%  |
| Germany      | 38        | 15.83%  |
| Russia       | 25        | 10.42%  |
| Italy        | 15        | 6.25%   |
| Brazil       | 14        | 5.83%   |
| UK           | 9         | 3.75%   |
| Poland       | 9         | 3.75%   |
| France       | 9         | 3.75%   |
| Spain        | 7         | 2.92%   |
| Mexico       | 5         | 2.08%   |
| Belarus      | 4         | 1.67%   |
| Sweden       | 3         | 1.25%   |
| Portugal     | 3         | 1.25%   |
| Greece       | 3         | 1.25%   |
| Chile        | 3         | 1.25%   |
| Canada       | 3         | 1.25%   |
| Belgium      | 3         | 1.25%   |
| Turkey       | 2         | 0.83%   |
| South Korea  | 2         | 0.83%   |
| Slovenia     | 2         | 0.83%   |
| Romania      | 2         | 0.83%   |
| Peru         | 2         | 0.83%   |
| Paraguay     | 2         | 0.83%   |
| New Zealand  | 2         | 0.83%   |
| Japan        | 2         | 0.83%   |
| Indonesia    | 2         | 0.83%   |
| Hungary      | 2         | 0.83%   |
| Finland      | 2         | 0.83%   |
| Denmark      | 2         | 0.83%   |
| Czechia      | 2         | 0.83%   |
| Bolivia      | 2         | 0.83%   |
| Austria      | 2         | 0.83%   |
| Vietnam      | 1         | 0.42%   |
| Venezuela    | 1         | 0.42%   |
| Serbia       | 1         | 0.42%   |
| Saudi Arabia | 1         | 0.42%   |
| Norway       | 1         | 0.42%   |
| Netherlands  | 1         | 0.42%   |
| Malaysia     | 1         | 0.42%   |
| Lithuania    | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 7         | 2.82%   |
| St Petersburg        | 4         | 1.61%   |
| Berlin               | 4         | 1.61%   |
| Rome                 | 3         | 1.21%   |
| Munich               | 3         | 1.21%   |
| Santiago             | 2         | 0.81%   |
| San Jose             | 2         | 0.81%   |
| Oruro                | 2         | 0.81%   |
| Neasden              | 2         | 0.81%   |
| Milan                | 2         | 0.81%   |
| Miami                | 2         | 0.81%   |
| Malmo                | 2         | 0.81%   |
| Madrid               | 2         | 0.81%   |
| Lisbon               | 2         | 0.81%   |
| Lima                 | 2         | 0.81%   |
| Krefeld              | 2         | 0.81%   |
| Krakow               | 2         | 0.81%   |
| Jakarta              | 2         | 0.81%   |
| Freiburg im Breisgau | 2         | 0.81%   |
| Delligsen            | 2         | 0.81%   |
| Ciudad Juárez       | 2         | 0.81%   |
| Auckland             | 2         | 0.81%   |
| Zenica               | 1         | 0.4%    |
| Zaragoza             | 1         | 0.4%    |
| Yekaterinburg        | 1         | 0.4%    |
| Wroclaw              | 1         | 0.4%    |
| West Hartford        | 1         | 0.4%    |
| Weimar               | 1         | 0.4%    |
| Warsaw               | 1         | 0.4%    |
| Voronezh             | 1         | 0.4%    |
| Volos                | 1         | 0.4%    |
| Vitebsk              | 1         | 0.4%    |
| Vilshofen            | 1         | 0.4%    |
| Vilnius              | 1         | 0.4%    |
| Viggianello          | 1         | 0.4%    |
| Viet Tri             | 1         | 0.4%    |
| Vienna               | 1         | 0.4%    |
| Veurne               | 1         | 0.4%    |
| Vaslui               | 1         | 0.4%    |
| Vancouver            | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 38        | 42     | 13.01%  |
| WDC                            | 30        | 34     | 10.27%  |
| Seagate                        | 28        | 33     | 9.59%   |
| Unknown                        | 22        | 34     | 7.53%   |
| Sandisk                        | 19        | 27     | 6.51%   |
| Kingston                       | 14        | 17     | 4.79%   |
| Toshiba                        | 12        | 13     | 4.11%   |
| SK hynix                       | 12        | 12     | 4.11%   |
| Hitachi                        | 9         | 9      | 3.08%   |
| Intel                          | 8         | 9      | 2.74%   |
| Crucial                        | 7         | 8      | 2.4%    |
| Apple                          | 6         | 11     | 2.05%   |
| A-DATA Technology              | 6         | 7      | 2.05%   |
| Micron Technology              | 5         | 5      | 1.71%   |
| China                          | 5         | 6      | 1.71%   |
| PNY                            | 4         | 5      | 1.37%   |
| HGST                           | 4         | 7      | 1.37%   |
| Phison                         | 3         | 3      | 1.03%   |
| Patriot                        | 3         | 3      | 1.03%   |
| KingSpec                       | 3         | 3      | 1.03%   |
| Fujitsu                        | 3         | 3      | 1.03%   |
| Unknown                        | 3         | 3      | 1.03%   |
| UMIS                           | 2         | 2      | 0.68%   |
| Transcend                      | 2         | 3      | 0.68%   |
| Team                           | 2         | 2      | 0.68%   |
| Star Drive                     | 2         | 2      | 0.68%   |
| KIOXIA                         | 2         | 5      | 0.68%   |
| Intenso                        | 2         | 2      | 0.68%   |
| GOODRAM                        | 2         | 2      | 0.68%   |
| Fanxiang                       | 2         | 2      | 0.68%   |
| Emtec                          | 2         | 2      | 0.68%   |
| WINTEC                         | 1         | 1      | 0.34%   |
| WD MediaMax                    | 1         | 1      | 0.34%   |
| Union Memory                   | 1         | 1      | 0.34%   |
| SSD PHIS                       | 1         | 1      | 0.34%   |
| Solid State Storage Technology | 1         | 1      | 0.34%   |
| Silicon Motion                 | 1         | 1      | 0.34%   |
| ShiJi                          | 1         | 1      | 0.34%   |
| SCCTS-603-001T                 | 1         | 1      | 0.34%   |
| SABRENT                        | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB              | 8         | 2.66%   |
| Unknown SD/MMC/MS PRO 64GB                  | 3         | 1%      |
| Seagate ST500LT012-1DG142 500GB             | 3         | 1%      |
| SanDisk NVMe SSD Drive 256GB                | 3         | 1%      |
| Samsung SSD 850 EVO 500GB                   | 3         | 1%      |
| Kingston SA400S37480G 480GB SSD             | 3         | 1%      |
| Kingston SA400S37120G 120GB SSD             | 3         | 1%      |
| Crucial CT1000BX500SSD1 1TB                 | 3         | 1%      |
| Unknown                                     | 3         | 1%      |
| WDC WD3200BPVT-22JJ5T0 320GB                | 2         | 0.66%   |
| WDC WD3200BEVT-60ZCT1 320GB                 | 2         | 0.66%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB        | 2         | 0.66%   |
| Unknown SC128  128GB                        | 2         | 0.66%   |
| Unknown MMC Card  64GB                      | 2         | 0.66%   |
| Unknown MMC Card  32GB                      | 2         | 0.66%   |
| Toshiba MQ01ABD100 1TB                      | 2         | 0.66%   |
| Star Drive PCIe SSD 480GB                   | 2         | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 2         | 0.66%   |
| Seagate ST9250315AS 250GB                   | 2         | 0.66%   |
| Seagate ST500LM012 HN-M500MBB 500GB         | 2         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB        | 2         | 0.66%   |
| Samsung SSD 980 PRO 1TB                     | 2         | 0.66%   |
| Samsung SSD 980 1TB                         | 2         | 0.66%   |
| Samsung SSD 840 EVO 250GB                   | 2         | 0.66%   |
| Samsung PM991a NVMe 512GB                   | 2         | 0.66%   |
| Patriot Burst 240GB SSD                     | 2         | 0.66%   |
| Micron NVMe SSD Drive 512GB                 | 2         | 0.66%   |
| KingSpec MT-128 128GB                       | 2         | 0.66%   |
| Fujitsu MHZ2160BH G2 160GB                  | 2         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                 | 2         | 0.66%   |
| Apple SSD SD0128F 121GB                     | 2         | 0.66%   |
| A-DATA SU650 240GB SSD                      | 2         | 0.66%   |
| A-DATA ED600 1TB SSD                        | 2         | 0.66%   |
| WINTEC 240GB SATA3 SF2281 SSD               | 1         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 0.33%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD            | 1         | 0.33%   |
| WDC WDS100T3X0C-00SJG0 1TB                  | 1         | 0.33%   |
| WDC WDBNCE5000PNC 500GB SSD                 | 1         | 0.33%   |
| WDC WD7500BPVT-22HXZT3 752GB                | 1         | 0.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 33     | 35.9%   |
| WDC                 | 19        | 21     | 24.36%  |
| Hitachi             | 9         | 9      | 11.54%  |
| Toshiba             | 8         | 9      | 10.26%  |
| HGST                | 4         | 7      | 5.13%   |
| Unknown             | 3         | 3      | 3.85%   |
| Fujitsu             | 3         | 3      | 3.85%   |
| Samsung Electronics | 2         | 2      | 2.56%   |
| Intenso             | 1         | 1      | 1.28%   |
| ASMT                | 1         | 1      | 1.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 18     | 14.02%  |
| Kingston            | 11        | 13     | 10.28%  |
| SanDisk             | 9         | 14     | 8.41%   |
| Crucial             | 7         | 8      | 6.54%   |
| A-DATA Technology   | 6         | 7      | 5.61%   |
| Apple               | 5         | 5      | 4.67%   |
| PNY                 | 4         | 5      | 3.74%   |
| Intel               | 4         | 4      | 3.74%   |
| China               | 4         | 5      | 3.74%   |
| WDC                 | 3         | 3      | 2.8%    |
| Patriot             | 3         | 3      | 2.8%    |
| KingSpec            | 3         | 3      | 2.8%    |
| Transcend           | 2         | 3      | 1.87%   |
| Toshiba             | 2         | 2      | 1.87%   |
| Team                | 2         | 2      | 1.87%   |
| GOODRAM             | 2         | 2      | 1.87%   |
| Emtec               | 2         | 2      | 1.87%   |
| Unknown             | 2         | 2      | 1.87%   |
| WINTEC              | 1         | 1      | 0.93%   |
| SSD PHIS            | 1         | 1      | 0.93%   |
| SK hynix            | 1         | 1      | 0.93%   |
| SCCTS-603-001T      | 1         | 1      | 0.93%   |
| SABRENT             | 1         | 1      | 0.93%   |
| ORICO               | 1         | 1      | 0.93%   |
| Microtech           | 1         | 2      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| LITEON              | 1         | 1      | 0.93%   |
| Lexar               | 1         | 1      | 0.93%   |
| KODAK               | 1         | 1      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |
| Initio              | 1         | 1      | 0.93%   |
| HXY                 | 1         | 1      | 0.93%   |
| Hanye               | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 2      | 0.93%   |
| FORESEE             | 1         | 3      | 0.93%   |
| Fanxiang            | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| BHT                 | 1         | 2      | 0.93%   |
| Acer                | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 99        | 127    | 35.74%  |
| HDD     | 76        | 89     | 27.44%  |
| NVMe    | 72        | 94     | 25.99%  |
| MMC     | 20        | 30     | 7.22%   |
| Unknown | 10        | 12     | 3.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 211    | 61.13%  |
| NVMe | 72        | 94     | 27.17%  |
| MMC  | 20        | 30     | 7.55%   |
| SAS  | 11        | 17     | 4.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 123       | 154    | 72.35%  |
| 0.51-1.0   | 40        | 54     | 23.53%  |
| 1.01-2.0   | 4         | 5      | 2.35%   |
| 2.01-3.0   | 1         | 1      | 0.59%   |
| 10.01-20.0 | 1         | 1      | 0.59%   |
| 4.01-10.0  | 1         | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 88        | 36.51%  |
| 251-500        | 64        | 26.56%  |
| 501-1000       | 29        | 12.03%  |
| 51-100         | 17        | 7.05%   |
| 1001-2000      | 15        | 6.22%   |
| 21-50          | 11        | 4.56%   |
| 1-20           | 10        | 4.15%   |
| 2001-3000      | 5         | 2.07%   |
| More than 3000 | 2         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 116       | 45.85%  |
| 21-50     | 54        | 21.34%  |
| 51-100    | 31        | 12.25%  |
| 101-250   | 29        | 11.46%  |
| 501-1000  | 12        | 4.74%   |
| 251-500   | 10        | 3.95%   |
| 2001-3000 | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 4.76%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 4.76%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 4.76%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 1      | 4.76%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 4.76%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 4.76%   |
| Seagate ST98823AS 80GB                | 1         | 1      | 4.76%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 4.76%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 980 PRO 1TB   | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 4.76%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 4.76%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 4.76%   |
| Phison ES 512GB                       | 1         | 1      | 4.76%   |
| Intenso SSD 256GB                     | 1         | 1      | 4.76%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 4.76%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 4.76%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 4.76%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 6      | 25%     |
| Seagate             | 3         | 3      | 15%     |
| WDC                 | 2         | 3      | 10%     |
| Intel               | 2         | 2      | 10%     |
| Hitachi             | 2         | 2      | 10%     |
| WINTEC              | 1         | 1      | 5%      |
| Toshiba             | 1         | 1      | 5%      |
| SK hynix            | 1         | 1      | 5%      |
| Phison              | 1         | 1      | 5%      |
| Intenso             | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 3      | 22.22%  |
| Hitachi             | 2         | 2      | 22.22%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| HGST                | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 45%     |
| SSD  | 7         | 7      | 35%     |
| NVMe | 4         | 5      | 20%     |

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
| Detected | 152       | 214    | 58.24%  |
| Works    | 89        | 116    | 34.1%   |
| Malfunc  | 20        | 22     | 7.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 165       | 59.78%  |
| AMD                            | 33        | 11.96%  |
| Samsung Electronics            | 23        | 8.33%   |
| SanDisk                        | 15        | 5.43%   |
| SK hynix                       | 11        | 3.99%   |
| Phison Electronics             | 6         | 2.17%   |
| Micron Technology              | 4         | 1.45%   |
| Union Memory (Shenzhen)        | 3         | 1.09%   |
| KIOXIA                         | 3         | 1.09%   |
| Kingston Technology Company    | 3         | 1.09%   |
| Toshiba America Info Systems   | 2         | 0.72%   |
| Marvell Technology Group       | 2         | 0.72%   |
| Solid State Storage Technology | 1         | 0.36%   |
| Silicon Motion                 | 1         | 0.36%   |
| Nvidia                         | 1         | 0.36%   |
| Micron/Crucial Technology      | 1         | 0.36%   |
| Apple                          | 1         | 0.36%   |
| ADATA Technology               | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 9.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 5.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 5.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 5.3%    |
| Intel Volume Management Device NVMe RAID Controller                              | 14        | 4.64%   |
| Samsung NVMe SSD Controller 980                                                  | 11        | 3.64%   |
| Intel Tiger Lake-LP SATA Controller                                              | 11        | 3.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 3.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 2.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 2.98%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 1.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 6         | 1.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 1.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.66%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.66%   |
| Phison PS5013 E13 NVMe Controller                                                | 4         | 1.32%   |
| Micron NVMe Storage Controller                                                   | 4         | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.32%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.32%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.99%   |
| SanDisk NVMe Controller                                                          | 3         | 0.99%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.99%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.99%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.66%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.66%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 170       | 58.02%  |
| NVMe | 73        | 24.91%  |
| RAID | 31        | 10.58%  |
| IDE  | 19        | 6.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 190       | 79.83%  |
| AMD    | 48        | 20.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 3.36%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 2.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 2.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 2.1%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 5         | 2.1%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 2.1%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 1.68%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 1.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.26%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.26%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.26%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 3         | 1.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.26%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.26%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 1.26%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.26%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.84%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.84%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 2         | 0.84%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 2         | 0.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.84%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.84%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.84%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.84%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 2         | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.84%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.84%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.84%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.84%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.84%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 0.84%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.84%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 2         | 0.84%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.84%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.84%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 0.84%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 0.84%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.84%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 51        | 21.43%  |
| Intel Core i7           | 30        | 12.61%  |
| Intel Core i3           | 25        | 10.5%   |
| Other                   | 23        | 9.66%   |
| Intel Celeron           | 14        | 5.88%   |
| AMD Ryzen 5             | 13        | 5.46%   |
| Intel Core 2 Duo        | 11        | 4.62%   |
| Intel Atom              | 11        | 4.62%   |
| AMD Ryzen 7             | 10        | 4.2%    |
| Intel Pentium           | 9         | 3.78%   |
| AMD Ryzen 3             | 4         | 1.68%   |
| Intel Pentium Silver    | 3         | 1.26%   |
| Intel Pentium Dual-Core | 3         | 1.26%   |
| AMD E1                  | 3         | 1.26%   |
| AMD A10                 | 3         | 1.26%   |
| Intel Pentium M         | 2         | 0.84%   |
| Intel Genuine           | 2         | 0.84%   |
| Intel Core 2            | 2         | 0.84%   |
| Intel Celeron M         | 2         | 0.84%   |
| AMD Ryzen 9             | 2         | 0.84%   |
| AMD E2                  | 2         | 0.84%   |
| AMD A4                  | 2         | 0.84%   |
| Intel Pentium Gold      | 1         | 0.42%   |
| Intel Pentium Dual      | 1         | 0.42%   |
| Intel Core i9           | 1         | 0.42%   |
| Intel Core 2 Extreme    | 1         | 0.42%   |
| AMD E                   | 1         | 0.42%   |
| AMD C-50                | 1         | 0.42%   |
| AMD Athlon II           | 1         | 0.42%   |
| AMD Athlon 64 X2        | 1         | 0.42%   |
| AMD Athlon              | 1         | 0.42%   |
| AMD A8                  | 1         | 0.42%   |
| AMD A6                  | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 136       | 57.14%  |
| 4      | 64        | 26.89%  |
| 6      | 15        | 6.3%    |
| 8      | 11        | 4.62%   |
| 1      | 9         | 3.78%   |
| 12     | 2         | 0.84%   |
| 10     | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 238       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 167       | 70.17%  |
| 1      | 71        | 29.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 229       | 96.22%  |
| 32-bit         | 9         | 3.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 17        | 7.02%   |
| 0x306a9    | 17        | 7.02%   |
| 0x206a7    | 13        | 5.37%   |
| 0x40651    | 12        | 4.96%   |
| 0x406e3    | 11        | 4.55%   |
| 0x806ec    | 10        | 4.13%   |
| Unknown    | 10        | 4.13%   |
| 0x08608103 | 9         | 3.72%   |
| 0x1067a    | 8         | 3.31%   |
| 0x806e9    | 7         | 2.89%   |
| 0x406c4    | 7         | 2.89%   |
| 0x08108109 | 7         | 2.89%   |
| 0x6fd      | 6         | 2.48%   |
| 0x20655    | 6         | 2.48%   |
| 0x306c3    | 5         | 2.07%   |
| 0x906ea    | 4         | 1.65%   |
| 0x806ea    | 4         | 1.65%   |
| 0x706e5    | 4         | 1.65%   |
| 0x30661    | 4         | 1.65%   |
| 0x20652    | 4         | 1.65%   |
| 0x106c2    | 4         | 1.65%   |
| 0x0a50000c | 4         | 1.65%   |
| 0x06006705 | 4         | 1.65%   |
| 0x706a8    | 3         | 1.24%   |
| 0x706a1    | 3         | 1.24%   |
| 0x6f6      | 3         | 1.24%   |
| 0x30678    | 3         | 1.24%   |
| 0x106e5    | 3         | 1.24%   |
| 0x10676    | 3         | 1.24%   |
| 0x0a50000d | 3         | 1.24%   |
| 0xa0652    | 2         | 0.83%   |
| 0x906e9    | 2         | 0.83%   |
| 0x906c0    | 2         | 0.83%   |
| 0x806eb    | 2         | 0.83%   |
| 0x6d8      | 2         | 0.83%   |
| 0x506e3    | 2         | 0.83%   |
| 0x406c3    | 2         | 0.83%   |
| 0x306d4    | 2         | 0.83%   |
| 0x08600103 | 2         | 0.83%   |
| 0x08108102 | 2         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 12.55%  |
| TigerLake        | 18        | 7.53%   |
| IvyBridge        | 17        | 7.11%   |
| Haswell          | 17        | 7.11%   |
| Skylake          | 13        | 5.44%   |
| Silvermont       | 13        | 5.44%   |
| SandyBridge      | 13        | 5.44%   |
| Unknown          | 13        | 5.44%   |
| Westmere         | 11        | 4.6%    |
| Penryn           | 11        | 4.6%    |
| Zen+             | 9         | 3.77%   |
| Core             | 9         | 3.77%   |
| Bonnell          | 9         | 3.77%   |
| Zen 3            | 8         | 3.35%   |
| Excavator        | 7         | 2.93%   |
| Goldmont plus    | 6         | 2.51%   |
| IceLake          | 5         | 2.09%   |
| P6               | 4         | 1.67%   |
| Zen 2            | 3         | 1.26%   |
| Puma             | 3         | 1.26%   |
| Nehalem          | 3         | 1.26%   |
| Broadwell        | 3         | 1.26%   |
| Tremont          | 2         | 0.84%   |
| Piledriver       | 2         | 0.84%   |
| Jaguar           | 2         | 0.84%   |
| CometLake        | 2         | 0.84%   |
| Bobcat           | 2         | 0.84%   |
| K8 Hammer        | 1         | 0.42%   |
| K10              | 1         | 0.42%   |
| Goldmont         | 1         | 0.42%   |
| Alderlake Hybrid | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 60.42%  |
| AMD    | 60        | 21.2%   |
| Nvidia | 52        | 18.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 5.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.04%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 4.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 3.03%   |
| AMD Lucienne                                                                             | 9         | 3.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 2.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 2.36%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 6         | 2.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.02%   |
| Intel HD Graphics 620                                                                    | 6         | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.68%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.35%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 1.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.35%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.35%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.35%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.35%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 1.01%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.01%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.01%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.01%   |
| AMD Renoir                                                                               | 3         | 1.01%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.67%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.67%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.67%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.67%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 131       | 55.04%  |
| 1 x AMD        | 43        | 18.07%  |
| Intel + Nvidia | 33        | 13.87%  |
| 1 x Nvidia     | 13        | 5.46%   |
| Intel + AMD    | 6         | 2.52%   |
| AMD + Nvidia   | 6         | 2.52%   |
| 2 x AMD        | 5         | 2.1%    |
| Other          | 1         | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 214       | 88.8%   |
| Proprietary | 18        | 7.47%   |
| Unknown     | 9         | 3.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 152       | 62.81%  |
| 0.01-0.5   | 41        | 16.94%  |
| 1.01-2.0   | 28        | 11.57%  |
| 0.51-1.0   | 11        | 4.55%   |
| 3.01-4.0   | 7         | 2.89%   |
| 5.01-6.0   | 2         | 0.83%   |
| 2.01-3.0   | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 49        | 20%     |
| LG Display              | 43        | 17.55%  |
| Chimei Innolux          | 35        | 14.29%  |
| BOE                     | 30        | 12.24%  |
| Samsung Electronics     | 16        | 6.53%   |
| Apple                   | 9         | 3.67%   |
| Chi Mei Optoelectronics | 8         | 3.27%   |
| InfoVision              | 6         | 2.45%   |
| Sharp                   | 5         | 2.04%   |
| LG Philips              | 5         | 2.04%   |
| PANDA                   | 4         | 1.63%   |
| Lenovo                  | 4         | 1.63%   |
| Goldstar                | 4         | 1.63%   |
| Dell                    | 4         | 1.63%   |
| HannStar                | 3         | 1.22%   |
| SLD                     | 2         | 0.82%   |
| Panasonic               | 2         | 0.82%   |
| ViewSonic               | 1         | 0.41%   |
| Vestel Elektronik       | 1         | 0.41%   |
| TR_                     | 1         | 0.41%   |
| Sceptre Tech            | 1         | 0.41%   |
| Quanta Display          | 1         | 0.41%   |
| Planar                  | 1         | 0.41%   |
| Philips                 | 1         | 0.41%   |
| Packard Bell            | 1         | 0.41%   |
| Insignia                | 1         | 0.41%   |
| IBM                     | 1         | 0.41%   |
| HKC                     | 1         | 0.41%   |
| Hewlett-Packard         | 1         | 0.41%   |
| DENON                   | 1         | 0.41%   |
| CPT                     | 1         | 0.41%   |
| BenQ                    | 1         | 0.41%   |
| Acer                    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 1.22%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.81%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch             | 2         | 0.81%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.81%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.81%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.81%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 0.81%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 2         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.81%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.81%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 2         | 0.81%   |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                    | 2         | 0.81%   |
| ViewSonic VG2756-4K VSC553A 3840x2160 597x336mm 27.0-inch                | 1         | 0.41%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch     | 1         | 0.41%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 0.41%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.41%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                  | 1         | 0.41%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 1         | 0.41%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch           | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch     | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 96        | 40.34%  |
| 1366x768 (WXGA)    | 83        | 34.87%  |
| 1600x900 (HD+)     | 11        | 4.62%   |
| 1280x800 (WXGA)    | 10        | 4.2%    |
| 3840x2160 (4K)     | 7         | 2.94%   |
| 1920x1200 (WUXGA)  | 7         | 2.94%   |
| 1024x600           | 6         | 2.52%   |
| 1440x900 (WXGA+)   | 4         | 1.68%   |
| 2880x1800          | 2         | 0.84%   |
| 2560x1600          | 2         | 0.84%   |
| 2560x1440 (QHD)    | 2         | 0.84%   |
| 1280x1024 (SXGA)   | 2         | 0.84%   |
| 2560x1080          | 1         | 0.42%   |
| 2256x1504          | 1         | 0.42%   |
| 1680x1050 (WSXGA+) | 1         | 0.42%   |
| 1280x768           | 1         | 0.42%   |
| 1280x720 (HD)      | 1         | 0.42%   |
| 1024x576           | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 120       | 48.78%  |
| 13      | 39        | 15.85%  |
| 14      | 24        | 9.76%   |
| 17      | 16        | 6.5%    |
| 24      | 9         | 3.66%   |
| 10      | 7         | 2.85%   |
| 12      | 6         | 2.44%   |
| 11      | 6         | 2.44%   |
| 27      | 3         | 1.22%   |
| 23      | 3         | 1.22%   |
| Unknown | 3         | 1.22%   |
| 21      | 2         | 0.81%   |
| 84      | 1         | 0.41%   |
| 72      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 31      | 1         | 0.41%   |
| 18      | 1         | 0.41%   |
| 16      | 1         | 0.41%   |
| 8       | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 67.49%  |
| 201-300     | 36        | 14.81%  |
| 351-400     | 17        | 7%      |
| 501-600     | 14        | 5.76%   |
| 401-500     | 3         | 1.23%   |
| Unknown     | 3         | 1.23%   |
| 1501-2000   | 2         | 0.82%   |
| 801-900     | 1         | 0.41%   |
| 701-800     | 1         | 0.41%   |
| 601-700     | 1         | 0.41%   |
| 101-200     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 198       | 85.34%  |
| 16/10   | 28        | 12.07%  |
| 5/4     | 2         | 0.86%   |
| Unknown | 2         | 0.86%   |
| 3/2     | 1         | 0.43%   |
| 21/9    | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 120       | 48.78%  |
| 81-90          | 49        | 19.92%  |
| 71-80          | 14        | 5.69%   |
| 201-250        | 10        | 4.07%   |
| 121-130        | 10        | 4.07%   |
| 41-50          | 7         | 2.85%   |
| 61-70          | 6         | 2.44%   |
| 51-60          | 6         | 2.44%   |
| 251-300        | 4         | 1.63%   |
| 131-140        | 4         | 1.63%   |
| 301-350        | 3         | 1.22%   |
| 141-150        | 3         | 1.22%   |
| Unknown        | 3         | 1.22%   |
| More than 1000 | 2         | 0.81%   |
| 351-500        | 2         | 0.81%   |
| 1-40           | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |
| 91-100         | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 101       | 41.22%  |
| 101-120       | 87        | 35.51%  |
| 51-100        | 34        | 13.88%  |
| 161-240       | 15        | 6.12%   |
| More than 240 | 4         | 1.63%   |
| Unknown       | 3         | 1.22%   |
| 1-50          | 1         | 0.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 213       | 88.38%  |
| 2     | 18        | 7.47%   |
| 0     | 9         | 3.73%   |
| 3     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 119       | 33.15%  |
| Intel                           | 113       | 31.48%  |
| Qualcomm Atheros                | 51        | 14.21%  |
| Broadcom                        | 30        | 8.36%   |
| Broadcom Limited                | 9         | 2.51%   |
| MediaTek                        | 6         | 1.67%   |
| TP-Link                         | 4         | 1.11%   |
| Marvell Technology Group        | 4         | 1.11%   |
| Xiaomi                          | 2         | 0.56%   |
| Spreadtrum Communications       | 2         | 0.56%   |
| Ralink Technology               | 2         | 0.56%   |
| Ralink                          | 2         | 0.56%   |
| Google                          | 2         | 0.56%   |
| Dell                            | 2         | 0.56%   |
| Sierra Wireless                 | 1         | 0.28%   |
| Samsung Electronics             | 1         | 0.28%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.28%   |
| Nvidia                          | 1         | 0.28%   |
| Lenovo                          | 1         | 0.28%   |
| JMicron Technology              | 1         | 0.28%   |
| Hewlett-Packard                 | 1         | 0.28%   |
| Foxconn / Hon Hai               | 1         | 0.28%   |
| Edimax Technology               | 1         | 0.28%   |
| Davicom Semiconductor           | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 59        | 13.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 5.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 3.54%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.21%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.77%   |
| Intel Wireless 8260                                                     | 8         | 1.77%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 1.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.77%   |
| Intel Wireless 3165                                                     | 7         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.33%   |
| Intel Wireless 7260                                                     | 6         | 1.33%   |
| Intel Ethernet Connection I219-V                                        | 6         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 5         | 1.11%   |
| Intel Wireless 7265                                                     | 5         | 1.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.11%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.88%   |
| Intel WiFi Link 5100                                                    | 4         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 4         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.66%   |
| Realtek RTL8187B Wireless Adapter                                       | 3         | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.66%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                           | 3         | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 44.49%  |
| Realtek Semiconductor           | 55        | 22.45%  |
| Qualcomm Atheros                | 35        | 14.29%  |
| Broadcom                        | 24        | 9.8%    |
| Broadcom Limited                | 6         | 2.45%   |
| MediaTek                        | 5         | 2.04%   |
| TP-Link                         | 2         | 0.82%   |
| Ralink Technology               | 2         | 0.82%   |
| Ralink                          | 2         | 0.82%   |
| Xiaomi                          | 1         | 0.41%   |
| Sierra Wireless                 | 1         | 0.41%   |
| Qualcomm Atheros Communications | 1         | 0.41%   |
| Edimax Technology               | 1         | 0.41%   |
| Dell                            | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 16        | 6.35%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.97%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 3.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.17%   |
| Intel Wireless 8260                                                     | 8         | 3.17%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 3.17%   |
| Intel Wireless 3165                                                     | 7         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.38%   |
| Intel Wireless 7260                                                     | 6         | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.98%   |
| Intel Wireless 7265                                                     | 5         | 1.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.98%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.59%   |
| Intel WiFi Link 5100                                                    | 4         | 1.59%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.19%   |
| Realtek RTL8187B Wireless Adapter                                       | 3         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.19%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.19%   |
| Broadcom BCM43225 802.11b/g/n                                           | 3         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 98        | 49.49%  |
| Intel                         | 43        | 21.72%  |
| Qualcomm Atheros              | 25        | 12.63%  |
| Broadcom                      | 9         | 4.55%   |
| Marvell Technology Group      | 4         | 2.02%   |
| Broadcom Limited              | 3         | 1.52%   |
| TP-Link                       | 2         | 1.01%   |
| Spreadtrum Communications     | 2         | 1.01%   |
| Google                        | 2         | 1.01%   |
| Xiaomi                        | 1         | 0.51%   |
| Samsung Electronics           | 1         | 0.51%   |
| OnePlus Technology (Shenzhen) | 1         | 0.51%   |
| Nvidia                        | 1         | 0.51%   |
| MediaTek                      | 1         | 0.51%   |
| Lenovo                        | 1         | 0.51%   |
| JMicron Technology            | 1         | 0.51%   |
| Hewlett-Packard               | 1         | 0.51%   |
| Foxconn / Hon Hai             | 1         | 0.51%   |
| Davicom Semiconductor         | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 29.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 13.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 4.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.03%   |
| Intel Ethernet Connection I219-V                                  | 6         | 3.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 2.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.02%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.02%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 2.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 3         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.52%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 1.01%   |
| Spreadtrum Spreadtrum Phone                                       | 2         | 1.01%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.01%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.01%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.51%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.51%   |
| MediaTek CPH2211                                                  | 1         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.51%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.51%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.51%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 234       | 55.32%  |
| Ethernet | 187       | 44.21%  |
| Modem    | 2         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 179       | 72.18%  |
| Ethernet | 69        | 27.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 170       | 71.43%  |
| 1     | 58        | 24.37%  |
| 0     | 9         | 3.78%   |
| 3     | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 162       | 67.22%  |
| Yes  | 79        | 32.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 77        | 46.39%  |
| Realtek Semiconductor           | 32        | 19.28%  |
| Foxconn / Hon Hai               | 10        | 6.02%   |
| Broadcom                        | 9         | 5.42%   |
| Lite-On Technology              | 8         | 4.82%   |
| Qualcomm Atheros Communications | 7         | 4.22%   |
| Apple                           | 7         | 4.22%   |
| Hewlett-Packard                 | 4         | 2.41%   |
| Dell                            | 4         | 2.41%   |
| IMC Networks                    | 3         | 1.81%   |
| Foxconn International           | 2         | 1.2%    |
| Chicony Electronics             | 1         | 0.6%    |
| Cambridge Silicon Radio         | 1         | 0.6%    |
| Askey Computer                  | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 33        | 19.88%  |
| Realtek Bluetooth Radio                                     | 22        | 13.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 14        | 8.43%   |
| Intel AX201 Bluetooth                                       | 13        | 7.83%   |
| Intel AX200 Bluetooth                                       | 9         | 5.42%   |
| Realtek  Bluetooth 4.2 Adapter                              | 6         | 3.61%   |
| Intel AX210 Bluetooth                                       | 4         | 2.41%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 2.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 1.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 1.81%   |
| Intel Bluetooth Device                                      | 3         | 1.81%   |
| Apple Bluetooth USB Host Controller                         | 3         | 1.81%   |
| Apple Bluetooth Host Controller                             | 3         | 1.81%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.2%    |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.2%    |
| Lite-On Bluetooth Device                                    | 2         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.2%    |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.2%    |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.2%    |
| Foxconn / Hon Hai Wireless_Device                           | 2         | 1.2%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                          | 2         | 1.2%    |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.2%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 2         | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.6%    |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.6%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.6%    |
| Lite-On Wireless_Device                                     | 1         | 0.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.6%    |
| IMC Networks Bluetooth Radio                                | 1         | 0.6%    |
| IMC Networks Bluetooth Device                               | 1         | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.6%    |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.6%    |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.6%    |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.6%    |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.6%    |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 186       | 66.67%  |
| AMD                   | 58        | 20.79%  |
| Nvidia                | 28        | 10.04%  |
| Texas Instruments     | 3         | 1.08%   |
| Yamaha                | 1         | 0.36%   |
| Realtek Semiconductor | 1         | 0.36%   |
| GN Netcom             | 1         | 0.36%   |
| Audioengine           | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 8.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 5.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 5.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 4.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 4.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 3.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 3.53%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 2.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.06%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.06%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.47%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.88%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.88%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.88%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.88%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.59%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 34        | 27.42%  |
| SK hynix                     | 25        | 20.16%  |
| Unknown                      | 15        | 12.1%   |
| Micron Technology            | 13        | 10.48%  |
| Kingston                     | 9         | 7.26%   |
| G.Skill                      | 4         | 3.23%   |
| Nanya Technology             | 3         | 2.42%   |
| Corsair                      | 3         | 2.42%   |
| A-DATA Technology            | 3         | 2.42%   |
| Unknown (ABCD)               | 2         | 1.61%   |
| Ramaxel Technology           | 2         | 1.61%   |
| GSkill                       | 2         | 1.61%   |
| Crucial                      | 2         | 1.61%   |
| Strontium                    | 1         | 0.81%   |
| Patriot Memory (PDP Systems) | 1         | 0.81%   |
| Lexar Co Limited             | 1         | 0.81%   |
| Elpida                       | 1         | 0.81%   |
| AMD                          | 1         | 0.81%   |
| 4ea5                         | 1         | 0.81%   |
| Unknown                      | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 1.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 1.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.49%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.49%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.49%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.49%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 1.49%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.75%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.75%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.75%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.75%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.75%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.75%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.75%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.75%   |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s             | 1         | 0.75%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.75%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.75%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 0.75%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 0.75%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.75%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 52        | 47.71%  |
| DDR3   | 37        | 33.94%  |
| DDR2   | 9         | 8.26%   |
| SDRAM  | 4         | 3.67%   |
| LPDDR4 | 4         | 3.67%   |
| LPDDR3 | 2         | 1.83%   |
| DDR    | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 93.64%  |
| Row Of Chips | 5         | 4.55%   |
| Unknown      | 2         | 1.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 41        | 34.45%  |
| 4096  | 28        | 23.53%  |
| 2048  | 26        | 21.85%  |
| 16384 | 14        | 11.76%  |
| 32768 | 4         | 3.36%   |
| 1024  | 3         | 2.52%   |
| 512   | 3         | 2.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 30        | 26.09%  |
| 1600    | 22        | 19.13%  |
| 2667    | 18        | 15.65%  |
| 2400    | 8         | 6.96%   |
| 1334    | 6         | 5.22%   |
| Unknown | 6         | 5.22%   |
| 1067    | 5         | 4.35%   |
| 2133    | 4         | 3.48%   |
| 667     | 4         | 3.48%   |
| 4199    | 2         | 1.74%   |
| 1333    | 2         | 1.74%   |
| 533     | 2         | 1.74%   |
| 4267    | 1         | 0.87%   |
| 3266    | 1         | 0.87%   |
| 2267    | 1         | 0.87%   |
| 2048    | 1         | 0.87%   |
| 1867    | 1         | 0.87%   |
| 1200    | 1         | 0.87%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 45        | 22.61%  |
| Microdia                               | 26        | 13.07%  |
| IMC Networks                           | 20        | 10.05%  |
| Suyin                                  | 15        | 7.54%   |
| Realtek Semiconductor                  | 12        | 6.03%   |
| Quanta                                 | 12        | 6.03%   |
| Sunplus Innovation Technology          | 10        | 5.03%   |
| Acer                                   | 10        | 5.03%   |
| Luxvisions Innotech Limited            | 8         | 4.02%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.02%   |
| Bison Electronics                      | 7         | 3.52%   |
| Syntek                                 | 4         | 2.01%   |
| Apple                                  | 4         | 2.01%   |
| Alcor Micro                            | 4         | 2.01%   |
| Importek                               | 3         | 1.51%   |
| Silicon Motion                         | 2         | 1.01%   |
| Lenovo                                 | 2         | 1.01%   |
| Z-Star Microelectronics                | 1         | 0.5%    |
| Lite-On Technology                     | 1         | 0.5%    |
| Intel                                  | 1         | 0.5%    |
| icSpring                               | 1         | 0.5%    |
| eMPIA Technology                       | 1         | 0.5%    |
| Alpha Imaging Technology               | 1         | 0.5%    |
| ALi                                    | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 15        | 7.46%   |
| Microdia Integrated_Webcam_HD                                  | 14        | 6.97%   |
| IMC Networks Integrated Camera                                 | 5         | 2.49%   |
| Chicony HD Webcam                                              | 5         | 2.49%   |
| Realtek USB Camera                                             | 4         | 1.99%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 1.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 4         | 1.99%   |
| Chicony HP TrueVision HD Camera                                | 4         | 1.99%   |
| Acer Integrated Camera                                         | 4         | 1.99%   |
| Syntek Integrated Camera                                       | 3         | 1.49%   |
| Realtek Lenovo EasyCamera                                      | 3         | 1.49%   |
| Microdia CameraA                                               | 3         | 1.49%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 3         | 1.49%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 3         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 3         | 1.49%   |
| Bison Integrated Camera                                        | 3         | 1.49%   |
| Suyin HP TrueVision HD                                         | 2         | 1%      |
| Suyin HD WebCam                                                | 2         | 1%      |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 2         | 1%      |
| Suyin Acer HD Crystal Eye webcam                               | 2         | 1%      |
| Sunplus HD WebCam                                              | 2         | 1%      |
| Quanta HP Webcam                                               | 2         | 1%      |
| Quanta HP HD Camera                                            | 2         | 1%      |
| Microdia Lenovo EasyCamera                                     | 2         | 1%      |
| IMC Networks EasyCamera                                        | 2         | 1%      |
| Chicony TOSHIBA Web Camera - FHD                               | 2         | 1%      |
| Chicony HP HD Camera                                           | 2         | 1%      |
| Chicony Camera                                                 | 2         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 2         | 1%      |
| Bison USB2.0 Camera                                            | 2         | 1%      |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1%      |
| Acer BisonCam, NB Pro                                          | 2         | 1%      |
| Z-Star WebCam SC-03FFL11739P                                   | 1         | 0.5%    |
| Syntek HD WebCam                                               | 1         | 0.5%    |
| Suyin Lenovo EasyCamera                                        | 1         | 0.5%    |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.5%    |
| Suyin HP Webcam-101                                            | 1         | 0.5%    |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 43.75%  |
| AuthenTec                  | 4         | 12.5%   |
| Upek                       | 3         | 9.38%   |
| Synaptics                  | 3         | 9.38%   |
| STMicroelectronics         | 2         | 6.25%   |
| Shenzhen Goodix Technology | 2         | 6.25%   |
| Microsoft                  | 1         | 3.13%   |
| LighTuning Technology      | 1         | 3.13%   |
| Focal-systems.Corp         | 1         | 3.13%   |
| Elan Microelectronics      | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 9.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 9.38%   |
| Validity Sensors Synaptics WBDI                          | 2         | 6.25%   |
| Validity Sensors Fingerprint scanner                     | 2         | 6.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 6.25%   |
| STMicroelectronics Fingerprint Reader                    | 2         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 6.25%   |
| AuthenTec AES1600                                        | 2         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 3.13%   |
| Validity Sensors VFS491                                  | 1         | 3.13%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 3.13%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 3.13%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 3.13%   |
| Synaptics UWP WBDI Device                                | 1         | 3.13%   |
| Microsoft Fingerprint Reader                             | 1         | 3.13%   |
| LighTuning Fingerprint Reader                            | 1         | 3.13%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.13%   |
| Elan ELAN:Fingerprint                                    | 1         | 3.13%   |
| AuthenTec Fingerprint Sensor                             | 1         | 3.13%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
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


| Model                                                      | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 158       | 64.49%  |
| 1     | 68        | 27.76%  |
| 2     | 14        | 5.71%   |
| 3     | 3         | 1.22%   |
| 4     | 2         | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 27.93%  |
| Net/wireless             | 25        | 22.52%  |
| Graphics card            | 19        | 17.12%  |
| Multimedia controller    | 15        | 13.51%  |
| Chipcard                 | 13        | 11.71%  |
| Communication controller | 2         | 1.8%    |
| Bluetooth                | 2         | 1.8%    |
| Storage                  | 1         | 0.9%    |
| Flash memory             | 1         | 0.9%    |
| Dvb card                 | 1         | 0.9%    |
| Card reader              | 1         | 0.9%    |

