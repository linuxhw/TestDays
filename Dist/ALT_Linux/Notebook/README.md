ALT Linux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 248

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 255 G4                      | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Samsung       | R560                        | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Timi          | TM1701                      | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Acer          | TravelMate 6292             | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| Toshiba       | dynabook Satellite T87/8... | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Acer          | AOA150                      | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| ASUSTek       | T100TAM                     | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| HUAWEI        | BOD-WXX9                    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | X550ZE                      | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| HP            | Pavilion g7                 | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| Lenovo        | G570 20079                  | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| HP            | Pavilion dv7                | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| Kraftway      | ACCORD                      | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| Panasonic     | CF-20-1                     | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| ICL           | Unknown                     | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| Lenovo        | V130-15IKB 81HN             | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| Apple         | MacBook7,1                  | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| ICL           | NJ50_70CU                   | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| Notebook      | NLx0MU                      | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Lenovo        | G570 20079                  | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| HP            | ZBook 17 G5                 | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| HP            | EliteBook 840 G4            | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| HP            | 250 G7 Notebook PC          | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| HP            | ProBook 440 G5              | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Timi          | TM1701                      | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| HP            | EliteBook 840 G4            | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Dell          | Latitude 3420               | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| ASUSTek       | X200MA                      | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| Dell          | Latitude 3590               | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASUSTek       | N46VZ                       | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Timi          | TM1701                      | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | N46VZ                       | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Durabook      | Z14                         | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| Aquarius      | NS585                       | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Dell          | G3 3779                     | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| Samsung       | RV413/RV513/E3413           | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| Acer          | Aspire ES1-523              | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | 1001PXD                     | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Acer          | Aspire ES1-523              | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 54        | 29.19%  |
| ALT Linux 10.0     | 29        | 15.68%  |
| ALT Linux 10.1     | 26        | 14.05%  |
| ALT Linux 9.1      | 22        | 11.89%  |
| MOS 10             | 10        | 5.41%   |
| ALT Linux 9.2      | 10        | 5.41%   |
| ALT Linux 9.0      | 9         | 4.86%   |
| ALT Linux P10      | 5         | 2.7%    |
| ALT Linux 10.0.900 | 3         | 1.62%   |
| ALT Linux P9       | 2         | 1.08%   |
| ALT Linux P8       | 2         | 1.08%   |
| ALT Linux 8.2      | 2         | 1.08%   |
| ALT Linux 20201124 | 2         | 1.08%   |
| ALT Linux 20191026 | 2         | 1.08%   |
| ALT Linux 9        | 1         | 0.54%   |
| ALT Linux 8.990    | 1         | 0.54%   |
| ALT Linux 8.920    | 1         | 0.54%   |
| ALT Linux 8.3      | 1         | 0.54%   |
| ALT Linux 8.0.0    | 1         | 0.54%   |
| ALT Linux 20190624 | 1         | 0.54%   |
| ALT Linux          | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 172       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.10.102-std-def-alt1 | 36        | 18.27%  |
| 5.10.109-std-def-alt1 | 19        | 9.64%   |
| 5.15.34-un-def-alt1   | 7         | 3.55%   |
| 5.10.88-std-def-alt1  | 7         | 3.55%   |
| 5.10.139-std-def-alt1 | 5         | 2.54%   |
| 5.10.123-std-def-alt1 | 5         | 2.54%   |
| 5.15.76-un-def-alt1   | 4         | 2.03%   |
| 5.10.82-std-def-alt1  | 4         | 2.03%   |
| 5.4.68-std-def-alt1.1 | 3         | 1.52%   |
| 5.4.28-std-def-alt1   | 3         | 1.52%   |
| 5.15.73-un-def-alt1   | 3         | 1.52%   |
| 5.10.152-std-def-alt1 | 3         | 1.52%   |
| 5.4.62-std-def-alt1   | 2         | 1.02%   |
| 5.4.51-std-def-alt1   | 2         | 1.02%   |
| 5.15.79-un-def-alt1   | 2         | 1.02%   |
| 5.15.63-un-def-alt1   | 2         | 1.02%   |
| 5.15.52-un-def-alt1   | 2         | 1.02%   |
| 5.15.33-un-def-alt1   | 2         | 1.02%   |
| 5.15.25-un-def-alt1   | 2         | 1.02%   |
| 5.10.62-un-def-alt1   | 2         | 1.02%   |
| 5.10.61-un-def-alt1   | 2         | 1.02%   |
| 5.10.37-un-def-alt1   | 2         | 1.02%   |
| 5.10.32-un-def-alt1   | 2         | 1.02%   |
| 5.10.17-un-def-alt1   | 2         | 1.02%   |
| 5.10.113-std-def-alt1 | 2         | 1.02%   |
| 5.10.111-std-def-alt1 | 2         | 1.02%   |
| 4.19.79-std-def-alt1  | 2         | 1.02%   |
| 4.19.66-std-def-alt1  | 2         | 1.02%   |
| 4.19.102-std-def-alt1 | 2         | 1.02%   |
| 5.7.19-un-def-alt1    | 1         | 0.51%   |
| 5.4.98-std-def-alt1   | 1         | 0.51%   |
| 5.4.87-std-def-alt1   | 1         | 0.51%   |
| 5.4.85-std-def-alt1   | 1         | 0.51%   |
| 5.4.84-std-def-alt1   | 1         | 0.51%   |
| 5.4.44-std-def-alt1   | 1         | 0.51%   |
| 5.4.41-std-def-alt1   | 1         | 0.51%   |
| 5.4.3-un-def-alt1     | 1         | 0.51%   |
| 5.4.171-std-def-alt1  | 1         | 0.51%   |
| 5.4.144-std-def-alt1  | 1         | 0.51%   |
| 5.4.127-std-def-alt1  | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.102 | 36        | 18.27%  |
| 5.10.109 | 19        | 9.64%   |
| 5.15.34  | 7         | 3.55%   |
| 5.10.88  | 7         | 3.55%   |
| 5.10.139 | 5         | 2.54%   |
| 5.10.123 | 5         | 2.54%   |
| 5.15.76  | 4         | 2.03%   |
| 5.10.82  | 4         | 2.03%   |
| 5.4.68   | 3         | 1.52%   |
| 5.4.28   | 3         | 1.52%   |
| 5.15.73  | 3         | 1.52%   |
| 5.10.152 | 3         | 1.52%   |
| 5.4.62   | 2         | 1.02%   |
| 5.4.51   | 2         | 1.02%   |
| 5.4.107  | 2         | 1.02%   |
| 5.15.79  | 2         | 1.02%   |
| 5.15.63  | 2         | 1.02%   |
| 5.15.52  | 2         | 1.02%   |
| 5.15.33  | 2         | 1.02%   |
| 5.15.25  | 2         | 1.02%   |
| 5.10.62  | 2         | 1.02%   |
| 5.10.61  | 2         | 1.02%   |
| 5.10.37  | 2         | 1.02%   |
| 5.10.32  | 2         | 1.02%   |
| 5.10.17  | 2         | 1.02%   |
| 5.10.118 | 2         | 1.02%   |
| 5.10.113 | 2         | 1.02%   |
| 5.10.111 | 2         | 1.02%   |
| 4.19.79  | 2         | 1.02%   |
| 4.19.66  | 2         | 1.02%   |
| 4.19.102 | 2         | 1.02%   |
| 5.7.19   | 1         | 0.51%   |
| 5.4.98   | 1         | 0.51%   |
| 5.4.87   | 1         | 0.51%   |
| 5.4.85   | 1         | 0.51%   |
| 5.4.84   | 1         | 0.51%   |
| 5.4.44   | 1         | 0.51%   |
| 5.4.41   | 1         | 0.51%   |
| 5.4.3    | 1         | 0.51%   |
| 5.4.171  | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 109       | 60.56%  |
| 5.15    | 29        | 16.11%  |
| 5.4     | 20        | 11.11%  |
| 4.19    | 11        | 6.11%   |
| 4.9     | 3         | 1.67%   |
| 5.18    | 2         | 1.11%   |
| 5.13    | 2         | 1.11%   |
| 5.7     | 1         | 0.56%   |
| 5.3     | 1         | 0.56%   |
| 5.16    | 1         | 0.56%   |
| 4.4     | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 162       | 94.19%  |
| i686   | 10        | 5.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 114       | 64.77%  |
| XFCE            | 26        | 14.77%  |
| Unknown         | 21        | 11.93%  |
| LXQt            | 7         | 3.98%   |
| Cinnamon        | 4         | 2.27%   |
| GNOME           | 3         | 1.7%    |
| GNOME Flashback | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 168       | 97.11%  |
| Wayland | 3         | 1.73%   |
| Tty     | 2         | 1.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 96        | 54.24%  |
| LightDM | 45        | 25.42%  |
| TDM     | 22        | 12.43%  |
| Unknown | 12        | 6.78%   |
| XDM     | 1         | 0.56%   |
| GDM     | 1         | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| ru_RU      | 140       | 79.1%   |
| Unknown    | 26        | 14.69%  |
| en_US      | 8         | 4.52%   |
| POSIX      | 1         | 0.56%   |
| it_IT@euro | 1         | 0.56%   |
| C          | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 128       | 73.56%  |
| BIOS | 46        | 26.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 151       | 86.78%  |
| Overlay | 17        | 9.77%   |
| Btrfs   | 4         | 2.3%    |
| Unknown | 2         | 1.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 125       | 71.43%  |
| MBR     | 35        | 20%     |
| Unknown | 15        | 8.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 92.05%  |
| Yes       | 14        | 7.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 54.91%  |
| Yes       | 78        | 45.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 55        | 31.98%  |
| Lenovo              | 20        | 11.63%  |
| ASUSTek Computer    | 19        | 11.05%  |
| Acer                | 15        | 8.72%   |
| ICL                 | 10        | 5.81%   |
| HUAWEI              | 8         | 4.65%   |
| Dell                | 8         | 4.65%   |
| Samsung Electronics | 6         | 3.49%   |
| Clevo               | 4         | 2.33%   |
| 3Logic Group        | 4         | 2.33%   |
| MSI                 | 3         | 1.74%   |
| DEPO Computers      | 3         | 1.74%   |
| Apple               | 3         | 1.74%   |
| Toshiba             | 2         | 1.16%   |
| Panasonic           | 2         | 1.16%   |
| Timi                | 1         | 0.58%   |
| Sony                | 1         | 0.58%   |
| Kraftway            | 1         | 0.58%   |
| IP3 Technology      | 1         | 0.58%   |
| IP3 Tech            | 1         | 0.58%   |
| eMachines           | 1         | 0.58%   |
| Durabook            | 1         | 0.58%   |
| Compumax Computer   | 1         | 0.58%   |
| Aquarius            | 1         | 0.58%   |
| Unknown             | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP 250 G7 Notebook PC                     | 12        | 6.98%   |
| HP ZBook 17 G5                            | 9         | 5.23%   |
| HP ProBook 440 G5                         | 8         | 4.65%   |
| ICL RAYbook Si1512                        | 6         | 3.49%   |
| Clevo NL41MU2                             | 4         | 2.33%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 3         | 1.74%   |
| HUAWEI NBD-WXX9                           | 3         | 1.74%   |
| HP EliteBook 840 G4                       | 3         | 1.74%   |
| HP 250 G6 Notebook PC                     | 3         | 1.74%   |
| DEPO Computers DPC156                     | 3         | 1.74%   |
| Dell Latitude 3420                        | 3         | 1.74%   |
| Unknown                                   | 3         | 1.74%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 1.16%   |
| ICL NJ50_70CU                             | 2         | 1.16%   |
| HUAWEI KLVL-WXXW                          | 2         | 1.16%   |
| HP EliteBook 8470p                        | 2         | 1.16%   |
| ASUS N46VZ                                | 2         | 1.16%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 1.16%   |
| Acer TravelMate 5760                      | 2         | 1.16%   |
| 3Logic Group Graviton N15i-K2             | 2         | 1.16%   |
| 3Logic Group Graviton N15i                | 2         | 1.16%   |
| Toshiba Satellite A100                    | 1         | 0.58%   |
| Toshiba dynabook Satellite T87/87M        | 1         | 0.58%   |
| Timi TM1701                               | 1         | 0.58%   |
| Sony SVE1512H1RB                          | 1         | 0.58%   |
| Samsung SR70S/SR71S                       | 1         | 0.58%   |
| Samsung RV413/RV513/E3413                 | 1         | 0.58%   |
| Samsung R560                              | 1         | 0.58%   |
| Samsung R510/P510                         | 1         | 0.58%   |
| Samsung R509                              | 1         | 0.58%   |
| Samsung 750XDA                            | 1         | 0.58%   |
| Panasonic CF-C2CH2CBMG                    | 1         | 0.58%   |
| Panasonic CF-20-1                         | 1         | 0.58%   |
| MSI X300/X340/X400 series                 | 1         | 0.58%   |
| MSI MEGA BOOK S430                        | 1         | 0.58%   |
| MSI GE72 7RE                              | 1         | 0.58%   |
| Lenovo V510-15IKB 80WQ                    | 1         | 0.58%   |
| Lenovo V130-15IKB 81HN                    | 1         | 0.58%   |
| Lenovo ThinkPad X220 4291M85              | 1         | 0.58%   |
| Lenovo ThinkPad 13 2nd Gen 20J1S0EU00     | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| HP 250                 | 16        | 9.3%    |
| HP ProBook             | 10        | 5.81%   |
| HP ZBook               | 9         | 5.23%   |
| HP Pavilion            | 7         | 4.07%   |
| Acer Aspire            | 7         | 4.07%   |
| ICL RAYbook            | 6         | 3.49%   |
| HP EliteBook           | 6         | 3.49%   |
| Lenovo IdeaPad         | 5         | 2.91%   |
| ASUS ASUS              | 5         | 2.91%   |
| Lenovo ThinkPad        | 4         | 2.33%   |
| HP Laptop              | 4         | 2.33%   |
| Dell Latitude          | 4         | 2.33%   |
| Clevo NL41MU2          | 4         | 2.33%   |
| ASUS VivoBook          | 4         | 2.33%   |
| Acer TravelMate        | 4         | 2.33%   |
| 3Logic Group Graviton  | 4         | 2.33%   |
| Lenovo ThinkBook       | 3         | 1.74%   |
| HUAWEI NBD-WXX9        | 3         | 1.74%   |
| DEPO Computers DPC156  | 3         | 1.74%   |
| Unknown                | 3         | 1.74%   |
| ICL NJ50               | 2         | 1.16%   |
| HUAWEI KLVL-WXXW       | 2         | 1.16%   |
| HP 255                 | 2         | 1.16%   |
| ASUS N46VZ             | 2         | 1.16%   |
| Toshiba Satellite      | 1         | 0.58%   |
| Toshiba dynabook       | 1         | 0.58%   |
| Timi TM1701            | 1         | 0.58%   |
| Sony SVE1512H1RB       | 1         | 0.58%   |
| Samsung SR70S          | 1         | 0.58%   |
| Samsung RV413          | 1         | 0.58%   |
| Samsung R560           | 1         | 0.58%   |
| Samsung R510           | 1         | 0.58%   |
| Samsung R509           | 1         | 0.58%   |
| Samsung 750XDA         | 1         | 0.58%   |
| Panasonic CF-C2CH2CBMG | 1         | 0.58%   |
| Panasonic CF-20-1      | 1         | 0.58%   |
| MSI X300               | 1         | 0.58%   |
| MSI MEGA               | 1         | 0.58%   |
| MSI GE72               | 1         | 0.58%   |
| Lenovo V510-15IKB      | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 26        | 15.12%  |
| 2018 | 26        | 15.12%  |
| 2017 | 19        | 11.05%  |
| 2020 | 17        | 9.88%   |
| 2019 | 16        | 9.3%    |
| 2022 | 10        | 5.81%   |
| 2011 | 9         | 5.23%   |
| 2014 | 7         | 4.07%   |
| 2008 | 7         | 4.07%   |
| 2016 | 6         | 3.49%   |
| 2012 | 6         | 3.49%   |
| 2010 | 6         | 3.49%   |
| 2009 | 5         | 2.91%   |
| 2015 | 4         | 2.33%   |
| 2007 | 4         | 2.33%   |
| 2013 | 2         | 1.16%   |
| 2006 | 2         | 1.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 172       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 144       | 82.29%  |
| Enabled  | 31        | 17.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 91        | 52.6%   |
| 3.01-4.0    | 31        | 17.92%  |
| 16.01-24.0  | 22        | 12.72%  |
| 8.01-16.0   | 12        | 6.94%   |
| 1.01-2.0    | 11        | 6.36%   |
| 2.01-3.0    | 3         | 1.73%   |
| 32.01-64.0  | 1         | 0.58%   |
| 64.01-256.0 | 1         | 0.58%   |
| 0.51-1.0    | 1         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 89        | 47.59%  |
| 2.01-3.0  | 33        | 17.65%  |
| 0.51-1.0  | 29        | 15.51%  |
| 4.01-8.0  | 15        | 8.02%   |
| 3.01-4.0  | 15        | 8.02%   |
| 0.01-0.5  | 5         | 2.67%   |
| 8.01-16.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 135       | 76.27%  |
| 2      | 36        | 20.34%  |
| 3      | 3         | 1.69%   |
| 0      | 2         | 1.13%   |
| 4      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 113       | 64.94%  |
| Yes       | 61        | 35.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 86.05%  |
| No        | 24        | 13.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 99.42%  |
| No        | 1         | 0.58%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 80.35%  |
| No        | 34        | 19.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Russia     | 159       | 92.44%  |
| Greece     | 4         | 2.33%   |
| Uzbekistan | 1         | 0.58%   |
| Ukraine    | 1         | 0.58%   |
| Italy      | 1         | 0.58%   |
| France     | 1         | 0.58%   |
| Egypt      | 1         | 0.58%   |
| Czechia    | 1         | 0.58%   |
| Costa Rica | 1         | 0.58%   |
| Colombia   | 1         | 0.58%   |
| Belarus    | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 107       | 60.45%  |
| St Petersburg     | 9         | 5.08%   |
| Barnaul           | 4         | 2.26%   |
| Samara            | 3         | 1.69%   |
| Novosibirsk       | 3         | 1.69%   |
| Astrakhan         | 3         | 1.69%   |
| Tyumen            | 2         | 1.13%   |
| Perm              | 2         | 1.13%   |
| Korolyov          | 2         | 1.13%   |
| Belgorod          | 2         | 1.13%   |
| Yekaterinburg     | 1         | 0.56%   |
| Voronezh          | 1         | 0.56%   |
| Vladimir          | 1         | 0.56%   |
| Verkhnyaya Pyshma | 1         | 0.56%   |
| Vergina           | 1         | 0.56%   |
| Troitsk           | 1         | 0.56%   |
| Thessaloniki      | 1         | 0.56%   |
| Tashkent          | 1         | 0.56%   |
| Surgut            | 1         | 0.56%   |
| Suez              | 1         | 0.56%   |
| Sevastopol        | 1         | 0.56%   |
| Saratov           | 1         | 0.56%   |
| San José         | 1         | 0.56%   |
| Rubtsovsk         | 1         | 0.56%   |
| Roubaix           | 1         | 0.56%   |
| Rostov-on-Don     | 1         | 0.56%   |
| Prague            | 1         | 0.56%   |
| Omsk              | 1         | 0.56%   |
| Obninsk           | 1         | 0.56%   |
| Novorossiysk      | 1         | 0.56%   |
| Novichikha        | 1         | 0.56%   |
| Nizhny Tagil      | 1         | 0.56%   |
| Milan             | 1         | 0.56%   |
| Lesosibirsk       | 1         | 0.56%   |
| Krasnoyarsk       | 1         | 0.56%   |
| Kostroma          | 1         | 0.56%   |
| Kirov             | 1         | 0.56%   |
| Khabarovsk        | 1         | 0.56%   |
| Kemerovo          | 1         | 0.56%   |
| Kazan’          | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 28        | 33     | 13.46%  |
| Samsung Electronics         | 26        | 37     | 12.5%   |
| Intel                       | 23        | 26     | 11.06%  |
| WDC                         | 21        | 25     | 10.1%   |
| SK hynix                    | 19        | 20     | 9.13%   |
| Toshiba                     | 9         | 13     | 4.33%   |
| Foxline                     | 9         | 9      | 4.33%   |
| Phison                      | 7         | 8      | 3.37%   |
| Hitachi                     | 7         | 7      | 3.37%   |
| Kingston                    | 6         | 6      | 2.88%   |
| BIWIN                       | 5         | 6      | 2.4%    |
| HGST                        | 4         | 4      | 1.92%   |
| Fujitsu                     | 4         | 4      | 1.92%   |
| A-DATA Technology           | 4         | 4      | 1.92%   |
| XPG                         | 3         | 4      | 1.44%   |
| Unknown                     | 3         | 7      | 1.44%   |
| Gigabyte Technology         | 3         | 3      | 1.44%   |
| Apacer                      | 3         | 3      | 1.44%   |
| Transcend                   | 2         | 2      | 0.96%   |
| SSSTC                       | 2         | 2      | 0.96%   |
| SanDisk                     | 2         | 2      | 0.96%   |
| KingSpec                    | 2         | 2      | 0.96%   |
| Crucial                     | 2         | 2      | 0.96%   |
| Unknown                     | 2         | 2      | 0.96%   |
| Yangtze Memory Technologies | 1         | 1      | 0.48%   |
| PNY                         | 1         | 1      | 0.48%   |
| Plextor                     | 1         | 1      | 0.48%   |
| Micron Technology           | 1         | 1      | 0.48%   |
| LuminouTek                  | 1         | 1      | 0.48%   |
| KIOXIA                      | 1         | 1      | 0.48%   |
| KingDian                    | 1         | 1      | 0.48%   |
| External                    | 1         | 2      | 0.48%   |
| BaseTech                    | 1         | 1      | 0.48%   |
| Apple                       | 1         | 1      | 0.48%   |
| AMD                         | 1         | 1      | 0.48%   |
| ADATA Technology            | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 12        | 5.56%   |
| Foxline FLSSD256M80E13TCX5 256GB        | 9         | 4.17%   |
| Seagate ST1000LM049-2GH172 1TB          | 8         | 3.7%    |
| Intel SSDPEMKF256G8H 256GB              | 8         | 3.7%    |
| Intel SSDPEKKF256G7H 256GB              | 8         | 3.7%    |
| Phison 311CD0512GB                      | 5         | 2.31%   |
| BIWIN CE480T5D101-256 256GB             | 5         | 2.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 1.85%   |
| Samsung MZALQ256HAJD-000L2 256GB        | 4         | 1.85%   |
| XPG SPECTRIX S40G 512GB                 | 2         | 0.93%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 2         | 0.93%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 0.93%   |
| Transcend TS240GSSD220S 240GB           | 2         | 0.93%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.93%   |
| Toshiba KXG50ZNV256G 256GB              | 2         | 0.93%   |
| SSSTC CL1-3D256-Q11 NVMe 256GB          | 2         | 0.93%   |
| Seagate ST9250315AS 250GB               | 2         | 0.93%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.93%   |
| Samsung SSD 860 EVO M.2 250GB           | 2         | 0.93%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.93%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.93%   |
| Samsung MZVLQ512HALU-000H1 512GB        | 2         | 0.93%   |
| Intel SSDPEKNW512G8H 512GB              | 2         | 0.93%   |
| Intel SSDPEKNU512GZ 512GB               | 2         | 0.93%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.93%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB        | 2         | 0.93%   |
| Crucial CT120BX500SSD1 120GB            | 2         | 0.93%   |
| Unknown                                 | 2         | 0.93%   |
| Yangtze Memory NVMe SSD Drive 256GB     | 1         | 0.46%   |
| XPG NVMe SSD Drive 256GB                | 1         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.46%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.46%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.46%   |
| WDC WD5000LPZX-22Z10T0 500GB            | 1         | 0.46%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 0.46%   |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 0.46%   |
| WDC WD5000LPLX-60ZNTT1 500GB            | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 33     | 43.75%  |
| WDC     | 14        | 15     | 21.88%  |
| Toshiba | 7         | 11     | 10.94%  |
| Hitachi | 7         | 7      | 10.94%  |
| HGST    | 4         | 4      | 6.25%   |
| Fujitsu | 4         | 4      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 22.5%   |
| WDC                 | 4         | 7      | 10%     |
| Kingston            | 4         | 4      | 10%     |
| Transcend           | 2         | 2      | 5%      |
| SK hynix            | 2         | 2      | 5%      |
| KingSpec            | 2         | 2      | 5%      |
| Crucial             | 2         | 2      | 5%      |
| A-DATA Technology   | 2         | 2      | 5%      |
| SanDisk             | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| Plextor             | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| LuminouTek          | 1         | 1      | 2.5%    |
| KingDian            | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| Foxline             | 1         | 1      | 2.5%    |
| BaseTech            | 1         | 1      | 2.5%    |
| Apacer              | 1         | 1      | 2.5%    |
| AMD                 | 1         | 1      | 2.5%    |
| Unknown             | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 94        | 116    | 46.53%  |
| HDD  | 63        | 74     | 31.19%  |
| SSD  | 39        | 44     | 19.31%  |
| MMC  | 6         | 10     | 2.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 93        | 114    | 48.44%  |
| SATA | 88        | 114    | 45.83%  |
| MMC  | 6         | 10     | 3.13%   |
| SAS  | 5         | 6      | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 76     | 68.37%  |
| 0.51-1.0   | 27        | 38     | 27.55%  |
| 1.01-2.0   | 3         | 3      | 3.06%   |
| 4.01-10.0  | 1         | 1      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 90        | 50%     |
| 251-500    | 28        | 15.56%  |
| 51-100     | 21        | 11.67%  |
| 21-50      | 13        | 7.22%   |
| 1-20       | 11        | 6.11%   |
| 501-1000   | 10        | 5.56%   |
| 1001-2000  | 5         | 2.78%   |
| 2001-3000  | 2         | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 113       | 61.08%  |
| 21-50     | 30        | 16.22%  |
| 101-250   | 14        | 7.57%   |
| 51-100    | 14        | 7.57%   |
| 251-500   | 8         | 4.32%   |
| 501-1000  | 4         | 2.16%   |
| 1001-2000 | 2         | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB               | 2         | 2      | 10.53%  |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 7      | 10.53%  |
| WDC WD5000LPVX-60V0TT0 500GB            | 1         | 1      | 5.26%   |
| WDC WD5000LPLX-60ZNTT2 500GB            | 1         | 1      | 5.26%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 5.26%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 5.26%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1      | 5.26%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB | 1         | 1      | 5.26%   |
| Seagate ST9640320AS 640GB               | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 5.26%   |
| Hitachi HTS725050A9A364 500GB           | 1         | 1      | 5.26%   |
| Hitachi HTS543225L9A300 250GB           | 1         | 1      | 5.26%   |
| Hitachi HTS542525K9A300 250GB           | 1         | 1      | 5.26%   |
| Hitachi HTS541610J9SA00 100GB           | 1         | 1      | 5.26%   |
| HGST HTS545050A7E680 500GB              | 1         | 1      | 5.26%   |
| Fujitsu MHW2160BH PL 160GB              | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 11     | 31.58%  |
| Hitachi  | 4         | 4      | 21.05%  |
| WDC      | 3         | 3      | 15.79%  |
| Toshiba  | 2         | 2      | 10.53%  |
| SK hynix | 2         | 2      | 10.53%  |
| HGST     | 1         | 1      | 5.26%   |
| Fujitsu  | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 11     | 35.29%  |
| Hitachi | 4         | 4      | 23.53%  |
| WDC     | 3         | 3      | 17.65%  |
| Toshiba | 2         | 2      | 11.76%  |
| HGST    | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 22     | 89.47%  |
| NVMe | 1         | 1      | 5.26%   |
| SSD  | 1         | 1      | 5.26%   |

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
| Works    | 142       | 179    | 78.02%  |
| Detected | 21        | 41     | 11.54%  |
| Malfunc  | 19        | 24     | 10.44%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 133       | 58.59%  |
| Samsung Electronics            | 17        | 7.49%   |
| Phison Electronics             | 17        | 7.49%   |
| SK hynix                       | 16        | 7.05%   |
| AMD                            | 15        | 6.61%   |
| INNOGRIT                       | 5         | 2.2%    |
| SanDisk                        | 4         | 1.76%   |
| Nvidia                         | 4         | 1.76%   |
| Toshiba America Info Systems   | 2         | 0.88%   |
| Solid State Storage Technology | 2         | 0.88%   |
| Realtek Semiconductor          | 2         | 0.88%   |
| Kingston Technology Company    | 2         | 0.88%   |
| ADATA Technology               | 2         | 0.88%   |
| Yangtze Memory Technologies    | 1         | 0.44%   |
| VIA Technologies               | 1         | 0.44%   |
| Shenzhen Longsys Electronics   | 1         | 0.44%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.44%   |
| KIOXIA                         | 1         | 0.44%   |
| Apple                          | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 23        | 8.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 17        | 6.59%   |
| Phison PS5013 E13 NVMe Controller                                            | 16        | 6.2%    |
| Intel Tiger Lake-LP SATA Controller                                          | 14        | 5.43%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 13        | 5.04%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 13        | 5.04%   |
| Intel Comet Lake SATA AHCI Controller                                        | 11        | 4.26%   |
| Samsung NVMe SSD Controller 980                                              | 10        | 3.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 10        | 3.88%   |
| Intel SSD 600P Series                                                        | 9         | 3.49%   |
| Intel Volume Management Device NVMe RAID Controller                          | 8         | 3.1%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 8         | 3.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 7         | 2.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 7         | 2.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 7         | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 7         | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 5         | 1.94%   |
| INNOGRIT Non-Volatile memory controller                                      | 5         | 1.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 4         | 1.55%   |
| Intel Non-Volatile memory controller                                         | 3         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 3         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 3         | 1.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 3         | 1.16%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 2         | 0.78%   |
| Solid State Storage Non-Volatile memory controller                           | 2         | 0.78%   |
| SK hynix BC511                                                               | 2         | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 2         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 2         | 0.78%   |
| Realtek RTS5763DL NVMe SSD Controller                                        | 2         | 0.78%   |
| Intel SSD 660P Series                                                        | 2         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                  | 2         | 0.78%   |
| Yangtze Memory Non-Volatile memory controller                                | 1         | 0.39%   |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 0.39%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 0.39%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                             | 1         | 0.39%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.39%   |
| Nvidia MCP89 SATA Controller                                                 | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 121       | 48.02%  |
| NVMe | 93        | 36.9%   |
| RAID | 25        | 9.92%   |
| IDE  | 13        | 5.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 148       | 86.05%  |
| AMD          | 23        | 13.37%  |
| CentaurHauls | 1         | 0.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 10.47%  |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 7.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 5.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 5.81%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 9         | 5.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 3.49%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 2.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 1.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.74%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 1.16%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 2         | 1.16%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.16%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.16%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.16%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.58%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.58%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 1         | 0.58%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.58%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.58%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.58%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.58%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.58%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.58%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.58%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.58%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 1         | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 48        | 27.91%  |
| Intel Core i3           | 28        | 16.28%  |
| Other                   | 24        | 13.95%  |
| Intel Core i7           | 19        | 11.05%  |
| Intel Core 2 Duo        | 7         | 4.07%   |
| Intel Celeron           | 6         | 3.49%   |
| AMD Ryzen 7             | 6         | 3.49%   |
| AMD Ryzen 5             | 6         | 3.49%   |
| Intel Atom              | 4         | 2.33%   |
| AMD A8                  | 3         | 1.74%   |
| Intel Pentium Silver    | 2         | 1.16%   |
| Intel Pentium Gold      | 2         | 1.16%   |
| AMD E1                  | 2         | 1.16%   |
| Intel Pentium Dual-Core | 1         | 0.58%   |
| Intel Pentium Dual      | 1         | 0.58%   |
| Intel Pentium           | 1         | 0.58%   |
| Intel Genuine           | 1         | 0.58%   |
| Intel Core m5           | 1         | 0.58%   |
| Intel Core Duo          | 1         | 0.58%   |
| Intel Core 2 Solo       | 1         | 0.58%   |
| Intel Celeron Dual-Core | 1         | 0.58%   |
| CentaurHauls VIA C7     | 1         | 0.58%   |
| AMD Turion 64 X2 Mobile | 1         | 0.58%   |
| AMD FX                  | 1         | 0.58%   |
| AMD E                   | 1         | 0.58%   |
| AMD C-60                | 1         | 0.58%   |
| AMD Athlon 64 X2        | 1         | 0.58%   |
| AMD A6                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 76        | 44.19%  |
| 4      | 73        | 42.44%  |
| 6      | 13        | 7.56%   |
| 8      | 5         | 2.91%   |
| 1      | 5         | 2.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 172       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 139       | 80.81%  |
| 1      | 33        | 19.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 166       | 96.51%  |
| 32-bit         | 5         | 2.91%   |
| Unknown        | 1         | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 14.37%  |
| 0x806c1    | 21        | 12.07%  |
| 0x806e9    | 16        | 9.2%    |
| 0x806ec    | 13        | 7.47%   |
| 0x806ea    | 12        | 6.9%    |
| 0x906ea    | 11        | 6.32%   |
| 0xa0660    | 8         | 4.6%    |
| 0x306a9    | 6         | 3.45%   |
| 0x1067a    | 6         | 3.45%   |
| 0x706e5    | 5         | 2.87%   |
| 0x406e3    | 4         | 2.3%    |
| 0x206a7    | 4         | 2.3%    |
| 0x40651    | 3         | 1.72%   |
| 0x08600106 | 3         | 1.72%   |
| 0x08108109 | 3         | 1.72%   |
| 0x706a8    | 2         | 1.15%   |
| 0x6fd      | 2         | 1.15%   |
| 0x30678    | 2         | 1.15%   |
| 0x106c2    | 2         | 1.15%   |
| 0x08608102 | 2         | 1.15%   |
| 0x0700010f | 2         | 1.15%   |
| 0xa0652    | 1         | 0.57%   |
| 0x806c2    | 1         | 0.57%   |
| 0x706a1    | 1         | 0.57%   |
| 0x6fa      | 1         | 0.57%   |
| 0x6ec      | 1         | 0.57%   |
| 0x6e8      | 1         | 0.57%   |
| 0x506c9    | 1         | 0.57%   |
| 0x406c3    | 1         | 0.57%   |
| 0x306c3    | 1         | 0.57%   |
| 0x20655    | 1         | 0.57%   |
| 0x20652    | 1         | 0.57%   |
| 0x106e5    | 1         | 0.57%   |
| 0x106ca    | 1         | 0.57%   |
| 0x10676    | 1         | 0.57%   |
| 0x0a50000c | 1         | 0.57%   |
| 0x0a404101 | 1         | 0.57%   |
| 0x08600104 | 1         | 0.57%   |
| 0x08108102 | 1         | 0.57%   |
| 0x07030105 | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 59        | 34.3%   |
| TigerLake     | 25        | 14.53%  |
| CometLake     | 9         | 5.23%   |
| SandyBridge   | 7         | 4.07%   |
| Penryn        | 7         | 4.07%   |
| IvyBridge     | 6         | 3.49%   |
| IceLake       | 5         | 2.91%   |
| Zen+          | 4         | 2.33%   |
| Zen 2         | 4         | 2.33%   |
| Skylake       | 4         | 2.33%   |
| Silvermont    | 4         | 2.33%   |
| Haswell       | 4         | 2.33%   |
| Goldmont plus | 4         | 2.33%   |
| Core          | 4         | 2.33%   |
| Unknown       | 4         | 2.33%   |
| Westmere      | 3         | 1.74%   |
| Bonnell       | 3         | 1.74%   |
| P6            | 2         | 1.16%   |
| K8 Hammer     | 2         | 1.16%   |
| Jaguar        | 2         | 1.16%   |
| Bobcat        | 2         | 1.16%   |
| Zen 3         | 1         | 0.58%   |
| Steamroller   | 1         | 0.58%   |
| Puma          | 1         | 0.58%   |
| Piledriver    | 1         | 0.58%   |
| Nehalem       | 1         | 0.58%   |
| K10 Llano     | 1         | 0.58%   |
| Goldmont      | 1         | 0.58%   |
| Excavator     | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 136       | 67.66%  |
| Nvidia           | 37        | 18.41%  |
| AMD              | 27        | 13.43%  |
| VIA Technologies | 1         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 21        | 10.1%   |
| Intel HD Graphics 620                                                         | 20        | 9.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 13        | 6.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 10        | 4.81%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 9         | 4.33%   |
| Intel Comet Lake UHD Graphics                                                 | 8         | 3.85%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                              | 7         | 3.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 3.37%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 2.88%   |
| Intel UHD Graphics 620                                                        | 4         | 1.92%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                     | 4         | 1.92%   |
| AMD Renoir                                                                    | 4         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 1.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 2         | 0.96%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 2         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 0.96%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 2         | 0.96%   |
| Intel Iris Plus Graphics G7                                                   | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 0.96%   |
| AMD Robson CE [Radeon HD 6370M/7370M]                                         | 2         | 0.96%   |
| AMD Lucienne                                                                  | 2         | 0.96%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 2         | 0.96%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                             | 1         | 0.48%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 1         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.48%   |
| Nvidia TU117M                                                                 | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 1         | 0.48%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.48%   |
| Nvidia GT218M [GeForce 310M]                                                  | 1         | 0.48%   |
| Nvidia GT216M [GeForce GT 330M]                                               | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 64.53%  |
| Intel + Nvidia | 22        | 12.79%  |
| 1 x AMD        | 16        | 9.3%    |
| 1 x Nvidia     | 11        | 6.4%    |
| 2 x AMD        | 4         | 2.33%   |
| AMD + Nvidia   | 4         | 2.33%   |
| Intel + AMD    | 3         | 1.74%   |
| 1 x VIA        | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 158       | 90.8%   |
| Proprietary | 13        | 7.47%   |
| Unknown     | 3         | 1.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 131       | 74.86%  |
| 0.01-0.5   | 19        | 10.86%  |
| 3.01-4.0   | 10        | 5.71%   |
| 0.51-1.0   | 9         | 5.14%   |
| 1.01-2.0   | 6         | 3.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 45        | 24.32%  |
| Chimei Innolux          | 35        | 18.92%  |
| AU Optronics            | 30        | 16.22%  |
| LG Display              | 19        | 10.27%  |
| Samsung Electronics     | 13        | 7.03%   |
| PANDA                   | 7         | 3.78%   |
| Chi Mei Optoelectronics | 6         | 3.24%   |
| Sharp                   | 5         | 2.7%    |
| BenQ                    | 3         | 1.62%   |
| Apple                   | 3         | 1.62%   |
| AOC                     | 3         | 1.62%   |
| VIE                     | 2         | 1.08%   |
| STA                     | 2         | 1.08%   |
| PRM                     | 2         | 1.08%   |
| TR_                     | 1         | 0.54%   |
| Toshiba                 | 1         | 0.54%   |
| Panasonic               | 1         | 0.54%   |
| KDC                     | 1         | 0.54%   |
| InfoVision              | 1         | 0.54%   |
| Hitachi                 | 1         | 0.54%   |
| Goldstar                | 1         | 0.54%   |
| CS_                     | 1         | 0.54%   |
| CPT                     | 1         | 0.54%   |
| Acer                    | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 12        | 6.45%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 9         | 4.84%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                 | 6         | 3.23%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch        | 5         | 2.69%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch               | 3         | 1.61%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 3         | 1.61%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch          | 3         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.61%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 3         | 1.61%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                 | 3         | 1.61%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 1.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 1.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.61%   |
| VIE IM27VL1 VIE2120 1920x1080 600x330mm 27.0-inch                     | 2         | 1.08%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                 | 2         | 1.08%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 330x210mm 15.4-inch | 2         | 1.08%   |
| PRM 35 PRM2733 1280x1024                                              | 2         | 1.08%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D7 1920x1080 309x173mm 13.9-inch      | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 1.08%   |
| BOE LCD Monitor BOE09CC 1920x1080 344x194mm 15.5-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO133C 1366x768 309x173mm 13.9-inch         | 2         | 1.08%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.54%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch              | 1         | 0.54%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.54%   |
| Sharp LCD Monitor SHP13CA 1280x800 331x207mm 15.4-inch                | 1         | 0.54%   |
| Samsung Electronics S24D590 SAM0B46 1920x1080 521x293mm 23.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4754 1280x800 261x163mm 12.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 110       | 62.5%   |
| 1366x768 (WXGA)    | 35        | 19.89%  |
| 1280x800 (WXGA)    | 9         | 5.11%   |
| 1600x900 (HD+)     | 6         | 3.41%   |
| 1280x1024 (SXGA)   | 3         | 1.7%    |
| 2160x1440          | 2         | 1.14%   |
| 1680x1050 (WSXGA+) | 2         | 1.14%   |
| 1440x900 (WXGA+)   | 2         | 1.14%   |
| 3200x1800 (QHD+)   | 1         | 0.57%   |
| 2880x1620          | 1         | 0.57%   |
| 2560x1600          | 1         | 0.57%   |
| 2560x1440 (QHD)    | 1         | 0.57%   |
| 1920x1200 (WUXGA)  | 1         | 0.57%   |
| 1400x1050          | 1         | 0.57%   |
| 1024x600           | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 87        | 47.03%  |
| 14      | 27        | 14.59%  |
| 13      | 23        | 12.43%  |
| 17      | 20        | 10.81%  |
| 27      | 4         | 2.16%   |
| 24      | 4         | 2.16%   |
| 23      | 4         | 2.16%   |
| 11      | 4         | 2.16%   |
| 19      | 3         | 1.62%   |
| 12      | 3         | 1.62%   |
| Unknown | 2         | 1.08%   |
| 59      | 1         | 0.54%   |
| 21      | 1         | 0.54%   |
| 10      | 1         | 0.54%   |
| 8       | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 127       | 68.65%  |
| 351-400     | 21        | 11.35%  |
| 201-300     | 18        | 9.73%   |
| 501-600     | 11        | 5.95%   |
| 401-500     | 3         | 1.62%   |
| Unknown     | 2         | 1.08%   |
| 601-700     | 1         | 0.54%   |
| 101-200     | 1         | 0.54%   |
| 1001-1500   | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 152       | 86.86%  |
| 16/10 | 15        | 8.57%   |
| 3/2   | 4         | 2.29%   |
| 5/4   | 2         | 1.14%   |
| 6/5   | 1         | 0.57%   |
| 4/3   | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 47.03%  |
| 81-90          | 44        | 23.78%  |
| 121-130        | 19        | 10.27%  |
| 201-250        | 7         | 3.78%   |
| 71-80          | 6         | 3.24%   |
| 51-60          | 4         | 2.16%   |
| 301-350        | 4         | 2.16%   |
| 61-70          | 3         | 1.62%   |
| 151-200        | 3         | 1.62%   |
| 251-300        | 2         | 1.08%   |
| Unknown        | 2         | 1.08%   |
| More than 1000 | 1         | 0.54%   |
| 41-50          | 1         | 0.54%   |
| 1-40           | 1         | 0.54%   |
| 131-140        | 1         | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 116       | 63.04%  |
| 101-120       | 35        | 19.02%  |
| 51-100        | 21        | 11.41%  |
| 161-240       | 8         | 4.35%   |
| Unknown       | 2         | 1.09%   |
| More than 240 | 1         | 0.54%   |
| 1-50          | 1         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 158       | 90.29%  |
| 2     | 15        | 8.57%   |
| 3     | 1         | 0.57%   |
| 0     | 1         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 37.94%  |
| Realtek Semiconductor           | 80        | 31.62%  |
| Qualcomm Atheros                | 30        | 11.86%  |
| Broadcom                        | 18        | 7.11%   |
| D-Link                          | 6         | 2.37%   |
| Marvell Technology Group        | 5         | 1.98%   |
| Nvidia                          | 4         | 1.58%   |
| MediaTek                        | 3         | 1.19%   |
| Sierra Wireless                 | 2         | 0.79%   |
| ASUSTek Computer                | 2         | 0.79%   |
| Ralink                          | 1         | 0.4%    |
| Qualcomm Atheros Communications | 1         | 0.4%    |
| Micro Star International        | 1         | 0.4%    |
| JMicron Technology              | 1         | 0.4%    |
| Huawei Technologies             | 1         | 0.4%    |
| DisplayLink                     | 1         | 0.4%    |
| Broadcom Limited                | 1         | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 58        | 17.31%  |
| Intel Wi-Fi 6 AX201                                                     | 22        | 6.57%   |
| Intel Wireless 8265 / 8275                                              | 15        | 4.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 3.58%   |
| Intel Ethernet Connection (13) I219-V                                   | 12        | 3.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 3.28%   |
| Intel Ethernet Connection (10) I219-V                                   | 10        | 2.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 2.69%   |
| Intel Ethernet Connection (7) I219-LM                                   | 9         | 2.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 2.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.79%   |
| Intel Wireless 7265                                                     | 6         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                                    | 6         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.19%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 4         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.19%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.19%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                                | 4         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.9%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.9%    |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.6%    |
| Intel Wireless 3165                                                     | 2         | 0.6%    |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.6%    |
| Intel WiMAX Connection 2400m                                            | 2         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 52.81%  |
| Realtek Semiconductor           | 32        | 17.98%  |
| Qualcomm Atheros                | 28        | 15.73%  |
| Broadcom                        | 14        | 7.87%   |
| MediaTek                        | 3         | 1.69%   |
| Sierra Wireless                 | 2         | 1.12%   |
| ASUSTek Computer                | 2         | 1.12%   |
| Ralink                          | 1         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.56%   |
| Micro Star International        | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 22        | 12.29%  |
| Intel Wireless 8265 / 8275                                              | 15        | 8.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 6.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 6.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 5.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 3.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.35%   |
| Intel Wireless 7265                                                     | 6         | 3.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 2.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.68%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.12%   |
| Intel Wireless 3165                                                     | 2         | 1.12%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 1.12%   |
| Intel WiFi Link 5100                                                    | 2         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.12%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.56%   |
| Realtek Realtek Network controller                                      | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.56%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.56%   |
| Micro Star International RT2573                                         | 1         | 0.56%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.56%   |
| Intel Wireless 8260                                                     | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 45.45%  |
| Intel                    | 50        | 32.47%  |
| Qualcomm Atheros         | 9         | 5.84%   |
| D-Link                   | 6         | 3.9%    |
| Broadcom                 | 6         | 3.9%    |
| Marvell Technology Group | 5         | 3.25%   |
| Nvidia                   | 4         | 2.6%    |
| JMicron Technology       | 1         | 0.65%   |
| Huawei Technologies      | 1         | 0.65%   |
| DisplayLink              | 1         | 0.65%   |
| Broadcom Limited         | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 58        | 37.18%  |
| Intel Ethernet Connection (13) I219-V                             | 12        | 7.69%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 6.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 5.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 5.77%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 3.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 2.56%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.56%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.28%   |
| Intel WiMAX Connection 2400m                                      | 2         | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.28%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 2         | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.64%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.64%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.64%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.64%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.64%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.64%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.64%   |
| Huawei SNE-LX1                                                    | 1         | 0.64%   |
| DisplayLink USB 3.0 DOCK                                          | 1         | 0.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.64%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 1         | 0.64%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 53.61%  |
| Ethernet | 148       | 46.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 78.77%  |
| Ethernet | 38        | 21.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 140       | 81.4%   |
| 1     | 28        | 16.28%  |
| 0     | 3         | 1.74%   |
| 3     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 95.35%  |
| Yes  | 8         | 4.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 84        | 60%     |
| Realtek Semiconductor           | 10        | 7.14%   |
| IMC Networks                    | 9         | 6.43%   |
| Broadcom                        | 8         | 5.71%   |
| Qualcomm Atheros Communications | 5         | 3.57%   |
| Lite-On Technology              | 5         | 3.57%   |
| Foxconn / Hon Hai               | 4         | 2.86%   |
| Realtek                         | 3         | 2.14%   |
| Hewlett-Packard                 | 3         | 2.14%   |
| ASUSTek Computer                | 2         | 1.43%   |
| Apple                           | 2         | 1.43%   |
| USI                             | 1         | 0.71%   |
| Toshiba                         | 1         | 0.71%   |
| Ralink                          | 1         | 0.71%   |
| Chicony Electronics             | 1         | 0.71%   |
| Cambridge Silicon Radio         | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 28        | 20%     |
| Intel AX201 Bluetooth                               | 25        | 17.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 16.43%  |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 5%      |
| Realtek Bluetooth Radio                             | 5         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.86%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 2.86%   |
| Realtek Bluetooth Radio                             | 3         | 2.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.14%   |
| IMC Networks Wireless_Device                        | 3         | 2.14%   |
| IMC Networks Bluetooth Device                       | 3         | 2.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 2.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.43%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 1.43%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.43%   |
| Apple Bluetooth Host Controller                     | 2         | 1.43%   |
| USI Bluetooth Module BCM92070                       | 1         | 0.71%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.71%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.71%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.71%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.71%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.71%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.71%   |
| Lite-On Bluetooth Radio                             | 1         | 0.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.71%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.71%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.71%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.71%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.71%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.71%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.71%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 145       | 71.08%  |
| Nvidia                | 24        | 11.76%  |
| AMD                   | 23        | 11.27%  |
| C-Media Electronics   | 7         | 3.43%   |
| VIA Technologies      | 1         | 0.49%   |
| Realtek Semiconductor | 1         | 0.49%   |
| Promethean Limited    | 1         | 0.49%   |
| ASUSTek Computer      | 1         | 0.49%   |
| Apple                 | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 28        | 12.44%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 11.11%  |
| Intel Cannon Point-LP High Definition Audio Controller                     | 20        | 8.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 11        | 4.89%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 4.89%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 4%      |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 3.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 2.67%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.67%   |
| C-Media Electronics USB Advanced Audio Device                              | 5         | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.78%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.33%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.89%   |
| Nvidia Audio device                                                        | 2         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 0.89%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller             | 1         | 0.44%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.44%   |
| Promethean Limited Audio                                                   | 1         | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.44%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia MCP67 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia MCP51 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.44%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.44%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 29.45%  |
| SK hynix            | 37        | 22.7%   |
| Unknown             | 15        | 9.2%    |
| Crucial             | 13        | 7.98%   |
| Micron Technology   | 11        | 6.75%   |
| Kingston            | 11        | 6.75%   |
| Foxline             | 5         | 3.07%   |
| ACPI Digital        | 5         | 3.07%   |
| A-DATA Technology   | 4         | 2.45%   |
| Elpida              | 3         | 1.84%   |
| ChangXin Memory     | 3         | 1.84%   |
| Unknown (ABCD)      | 2         | 1.23%   |
| Ramaxel Technology  | 2         | 1.23%   |
| Unknown             | 2         | 1.23%   |
| SHARETRONIC         | 1         | 0.61%   |
| Patriot             | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 7.83%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 5.42%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 3.01%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 3.01%   |
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 5         | 3.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.41%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 4         | 2.41%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 2.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 1.81%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 1.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 1.81%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 3         | 1.81%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.2%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.2%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.2%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.2%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.2%    |
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s          | 2         | 1.2%    |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s          | 2         | 1.2%    |
| Crucial RAM CB8GS2666.C8ET 8GB SODIMM DDR4 2667MT/s              | 2         | 1.2%    |
| Unknown                                                          | 2         | 1.2%    |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                     | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.6%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                    | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.6%    |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.6%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 98        | 64.05%  |
| DDR3    | 29        | 18.95%  |
| DDR2    | 14        | 9.15%   |
| LPDDR4  | 8         | 5.23%   |
| Unknown | 2         | 1.31%   |
| SDRAM   | 1         | 0.65%   |
| LPDDR3  | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 136       | 88.89%  |
| Row Of Chips | 16        | 10.46%  |
| DIMM         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 66        | 41.77%  |
| 4096  | 47        | 29.75%  |
| 16384 | 18        | 11.39%  |
| 2048  | 15        | 9.49%   |
| 1024  | 8         | 5.06%   |
| 512   | 2         | 1.27%   |
| 32768 | 1         | 0.63%   |
| 1536  | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 51        | 31.68%  |
| 3200    | 30        | 18.63%  |
| 1600    | 20        | 12.42%  |
| 2133    | 13        | 8.07%   |
| 2400    | 8         | 4.97%   |
| 667     | 7         | 4.35%   |
| 1334    | 6         | 3.73%   |
| Unknown | 6         | 3.73%   |
| 3266    | 4         | 2.48%   |
| 3733    | 3         | 1.86%   |
| 4267    | 2         | 1.24%   |
| 1333    | 2         | 1.24%   |
| 1067    | 2         | 1.24%   |
| 4800    | 1         | 0.62%   |
| 4199    | 1         | 0.62%   |
| 2933    | 1         | 0.62%   |
| 1867    | 1         | 0.62%   |
| 800     | 1         | 0.62%   |
| 533     | 1         | 0.62%   |
| 333     | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Canon MF4010 series      | 1         | 50%     |
| Brother HL-L2300D series | 1         | 50%     |

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
| Chicony Electronics                    | 40        | 24.69%  |
| Cheng Uei Precision Industry (Foxlink) | 30        | 18.52%  |
| IMC Networks                           | 20        | 12.35%  |
| Acer                                   | 13        | 8.02%   |
| Sunplus Innovation Technology          | 10        | 6.17%   |
| Quanta                                 | 10        | 6.17%   |
| Syntek                                 | 6         | 3.7%    |
| Suyin                                  | 6         | 3.7%    |
| Realtek Semiconductor                  | 4         | 2.47%   |
| Microdia                               | 4         | 2.47%   |
| Z-Star Microelectronics                | 3         | 1.85%   |
| Sonix Technology                       | 2         | 1.23%   |
| Lite-On Technology                     | 2         | 1.23%   |
| Apple                                  | 2         | 1.23%   |
| Y Media                                | 1         | 0.62%   |
| USB Camera                             | 1         | 0.62%   |
| Unknown                                | 1         | 0.62%   |
| SunplusIT                              | 1         | 0.62%   |
| Silicon Motion                         | 1         | 0.62%   |
| Ricoh                                  | 1         | 0.62%   |
| Primax Electronics                     | 1         | 0.62%   |
| Importek                               | 1         | 0.62%   |
| ALi                                    | 1         | 0.62%   |
| Alcor Micro                            | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 9.2%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 12        | 7.36%   |
| Chicony HP HD Camera                                           | 9         | 5.52%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 4.29%   |
| Acer BisonCam,NB Pro                                           | 7         | 4.29%   |
| Chicony USB2.0 Camera                                          | 6         | 3.68%   |
| Sunplus Integrated_Webcam_HD                                   | 5         | 3.07%   |
| IMC Networks Integrated Camera                                 | 4         | 2.45%   |
| IMC Networks HD Camera                                         | 4         | 2.45%   |
| Chicony USB camera                                             | 4         | 2.45%   |
| Syntek Integrated Camera                                       | 3         | 1.84%   |
| Sunplus BKX Usb FHD Camera                                     | 3         | 1.84%   |
| Quanta ov9734_techfront_camera                                 | 3         | 1.84%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.84%   |
| Chicony Integrated Camera                                      | 3         | 1.84%   |
| Z-Star Vega USB 2.0 Camera                                     | 2         | 1.23%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.23%   |
| Suyin 1.3M HD WebCam                                           | 2         | 1.23%   |
| Sunplus Asus Webcam                                            | 2         | 1.23%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 1.23%   |
| Chicony VGA Webcam                                             | 2         | 1.23%   |
| Chicony Lenovo EasyCamera                                      | 2         | 1.23%   |
| Chicony HD WebCam                                              | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 1.23%   |
| Apple Built-in iSight                                          | 2         | 1.23%   |
| Acer USB HD Webcam                                             | 2         | 1.23%   |
| Acer BisonCam, NB Pro                                          | 2         | 1.23%   |
| Z-Star Namuga 1.3M Webcam                                      | 1         | 0.61%   |
| Y Media USB Camera                                             | 1         | 0.61%   |
| USB Camera USB Camera                                          | 1         | 0.61%   |
| Unknown USB2.0 Webcam                                          | 1         | 0.61%   |
| Syntek USB2.0 UVC PC Camera                                    | 1         | 0.61%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.61%   |
| Suyin HP Truevision HD                                         | 1         | 0.61%   |
| Suyin Acer CrystalEye Webcam                                   | 1         | 0.61%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 0.61%   |
| SunplusIT USB camera                                           | 1         | 0.61%   |
| Silicon Motion WebCam SC-0311139N                              | 1         | 0.61%   |
| Ricoh USB2.0 Camera                                            | 1         | 0.61%   |
| Realtek USB Camera                                             | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 8         | 34.78%  |
| Validity Sensors           | 6         | 26.09%  |
| Synaptics                  | 3         | 13.04%  |
| Elan Microelectronics      | 3         | 13.04%  |
| LighTuning Technology      | 2         | 8.7%    |
| Upek                       | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 8         | 34.78%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 8.7%    |
| Validity Sensors VFS491                                | 2         | 8.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 8.7%    |
| Elan ELAN:Fingerprint                                  | 2         | 8.7%    |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.35%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.35%   |
| LighTuning Fingerprint Reader                          | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.35%   |
| Elan ELAN:ARM-M4                                       | 1         | 4.35%   |
| Unknown                                                | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 132       | 75.43%  |
| 1     | 31        | 17.71%  |
| 2     | 10        | 5.71%   |
| 3     | 2         | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 46%     |
| Graphics card            | 7         | 14%     |
| Communication controller | 7         | 14%     |
| Net/ethernet             | 3         | 6%      |
| Chipcard                 | 3         | 6%      |
| Multimedia controller    | 2         | 4%      |
| Sound                    | 1         | 2%      |
| Net/wireless             | 1         | 2%      |
| Flash memory             | 1         | 2%      |
| Camera                   | 1         | 2%      |
| Bluetooth                | 1         | 2%      |

