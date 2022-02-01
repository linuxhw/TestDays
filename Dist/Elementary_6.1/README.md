Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| FIRICH        | J1900                       | Desktop     | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [a0fdaf761c](https://linux-hardware.org/?probe=a0fdaf761c) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [f7c8c966dc](https://linux-hardware.org/?probe=f7c8c966dc) | Jan 17, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Dell          | Latitude E5400              | Notebook    | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | Notebook    | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [fae944592d](https://linux-hardware.org/?probe=fae944592d) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [352c62bd8f](https://linux-hardware.org/?probe=352c62bd8f) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-43-generic      | 71        | 46.71%  |
| 5.13.0-27-generic      | 28        | 18.42%  |
| 5.11.0-44-generic      | 16        | 10.53%  |
| 5.11.0-46-generic      | 12        | 7.89%   |
| 5.11.0-41-generic      | 8         | 5.26%   |
| 5.13.0-25-generic      | 2         | 1.32%   |
| 5.11.0-40-generic      | 2         | 1.32%   |
| 5.8.0-50-generic       | 1         | 0.66%   |
| 5.15.6-surface         | 1         | 0.66%   |
| 5.15.3-xanmod1         | 1         | 0.66%   |
| 5.15.13-xanmod1        | 1         | 0.66%   |
| 5.15.12-xanmod1-tt     | 1         | 0.66%   |
| 5.15.11-t2-big-sur     | 1         | 0.66%   |
| 5.15.10-xanmod1        | 1         | 0.66%   |
| 5.14.10-051410-generic | 1         | 0.66%   |
| 5.14.0-1011-oem        | 1         | 0.66%   |
| 5.13.0-28-generic      | 1         | 0.66%   |
| 5.13.0-22-generic      | 1         | 0.66%   |
| 5.11.0-43-lowlatency   | 1         | 0.66%   |
| 5.11.0-37-generic      | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 109       | 72.67%  |
| 5.13.0  | 32        | 21.33%  |
| 5.8.0   | 1         | 0.67%   |
| 5.15.6  | 1         | 0.67%   |
| 5.15.3  | 1         | 0.67%   |
| 5.15.13 | 1         | 0.67%   |
| 5.15.12 | 1         | 0.67%   |
| 5.15.11 | 1         | 0.67%   |
| 5.15.10 | 1         | 0.67%   |
| 5.14.10 | 1         | 0.67%   |
| 5.14.0  | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 109       | 72.67%  |
| 5.13    | 32        | 21.33%  |
| 5.15    | 6         | 4%      |
| 5.14    | 2         | 1.33%   |
| 5.8     | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 150       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 150       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 150       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 70.67%  |
| LightDM | 43        | 28.67%  |
| GDM     | 1         | 0.67%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 70        | 46.67%  |
| de_DE | 24        | 16%     |
| en_GB | 14        | 9.33%   |
| ru_RU | 6         | 4%      |
| pt_BR | 6         | 4%      |
| pl_PL | 5         | 3.33%   |
| fr_FR | 4         | 2.67%   |
| es_ES | 4         | 2.67%   |
| pt_PT | 3         | 2%      |
| it_IT | 3         | 2%      |
| nl_NL | 2         | 1.33%   |
| en_CA | 2         | 1.33%   |
| tr_TR | 1         | 0.67%   |
| sv_SE | 1         | 0.67%   |
| hu_HU | 1         | 0.67%   |
| hr_HR | 1         | 0.67%   |
| fr_CA | 1         | 0.67%   |
| en_AU | 1         | 0.67%   |
| bg_BG | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 108       | 72%     |
| BIOS | 42        | 28%     |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 141       | 94%     |
| Btrfs   | 7         | 4.67%   |
| Xfs     | 1         | 0.67%   |
| Overlay | 1         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 112       | 74.67%  |
| GPT     | 34        | 22.67%  |
| MBR     | 4         | 2.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 94.67%  |
| Yes       | 8         | 5.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 135       | 90%     |
| Yes       | 15        | 10%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 18.67%  |
| ASUSTek Computer    | 21        | 14%     |
| Apple               | 20        | 13.33%  |
| Hewlett-Packard     | 15        | 10%     |
| Dell                | 12        | 8%      |
| MSI                 | 8         | 5.33%   |
| Gigabyte Technology | 8         | 5.33%   |
| Acer                | 7         | 4.67%   |
| HUAWEI              | 5         | 3.33%   |
| ASRock              | 3         | 2%      |
| Teclast             | 2         | 1.33%   |
| Star Labs           | 2         | 1.33%   |
| Sony                | 2         | 1.33%   |
| Notebook            | 2         | 1.33%   |
| Monster             | 2         | 1.33%   |
| Microsoft           | 2         | 1.33%   |
| Wortmann AG         | 1         | 0.67%   |
| Timi                | 1         | 0.67%   |
| Samsung Electronics | 1         | 0.67%   |
| Razer               | 1         | 0.67%   |
| LG Electronics      | 1         | 0.67%   |
| Intel               | 1         | 0.67%   |
| Fujitsu             | 1         | 0.67%   |
| Foxconn             | 1         | 0.67%   |
| FIRICH              | 1         | 0.67%   |
| Acidanthera         | 1         | 0.67%   |
| Unknown             | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI MACHD-WXX9                          | 2         | 1.33%   |
| ASUS TUF GAMING B550M-PLUS                 | 2         | 1.33%   |
| Apple MacBookPro8,2                        | 2         | 1.33%   |
| Apple MacBookPro5,5                        | 2         | 1.33%   |
| Apple MacBook5,1                           | 2         | 1.33%   |
| Wortmann AG 1220729_1470271                | 1         | 0.67%   |
| Timi TM1613                                | 1         | 0.67%   |
| Teclast X6 plus                            | 1         | 0.67%   |
| Teclast F7                                 | 1         | 0.67%   |
| Star Labs StarBook                         | 1         | 0.67%   |
| Star Labs LabTop                           | 1         | 0.67%   |
| Sony VPCEA3S1E                             | 1         | 0.67%   |
| Sony SVE14A390X                            | 1         | 0.67%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D | 1         | 0.67%   |
| Razer Blade Stealth                        | 1         | 0.67%   |
| Notebook W65_67SJ                          | 1         | 0.67%   |
| Notebook P65xHP                            | 1         | 0.67%   |
| MSI PS63 Modern 8RD                        | 1         | 0.67%   |
| MSI PPPPP-CCC#MMMMMMMM                     | 1         | 0.67%   |
| MSI MS-7C52                                | 1         | 0.67%   |
| MSI MS-7C02                                | 1         | 0.67%   |
| MSI MS-7B86                                | 1         | 0.67%   |
| MSI MS-7B79                                | 1         | 0.67%   |
| MSI MS-7A59                                | 1         | 0.67%   |
| MSI GF63 Thin 9SCSR                        | 1         | 0.67%   |
| Monster MARKUT M7 V1.x                     | 1         | 0.67%   |
| Monster ABRA A5 V13.2                      | 1         | 0.67%   |
| Microsoft Surface Go                       | 1         | 0.67%   |
| Microsoft Surface Book 2                   | 1         | 0.67%   |
| LG A410-G.BC51P1                           | 1         | 0.67%   |
| Lenovo Yoga 300-11IBR 80M1                 | 1         | 0.67%   |
| Lenovo ThinkPad X270 W10DG 20K5S2VL00      | 1         | 0.67%   |
| Lenovo ThinkPad X13 Gen 1 20UFS00G00       | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 0.67%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1L200   | 1         | 0.67%   |
| Lenovo ThinkPad W541 20EGS1VV00            | 1         | 0.67%   |
| Lenovo ThinkPad T470 W10DG 20JNS08H00      | 1         | 0.67%   |
| Lenovo ThinkPad T470 20JNS08H00            | 1         | 0.67%   |
| Lenovo ThinkPad T430 23501M2               | 1         | 0.67%   |
| Lenovo ThinkPad T430 2347JC2               | 1         | 0.67%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00E00      | 1         | 0.67%   |
| Lenovo ThinkPad L390 Yoga 20NT001KGE       | 1         | 0.67%   |
| Lenovo ThinkPad E495 20NE001RTX            | 1         | 0.67%   |
| Lenovo ThinkPad E14 20RAS0EQ00             | 1         | 0.67%   |
| Lenovo Legion Y530-15ICH 81GT              | 1         | 0.67%   |
| Lenovo Legion Y530-15ICH 81FV              | 1         | 0.67%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG       | 1         | 0.67%   |
| Lenovo IdeaPad 5 14ARE05 81YM              | 1         | 0.67%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.67%   |
| Lenovo IdeaPad 320-14AST 80XU              | 1         | 0.67%   |
| Lenovo IdeaPad 310-15ISK 80SM              | 1         | 0.67%   |
| Lenovo IdeaPad 310-15IKB 80TV              | 1         | 0.67%   |
| Lenovo IdeaPad 130-15AST 81H5              | 1         | 0.67%   |
| Lenovo IdeaCentre AIO 3 24ARE05 F0EW00FLSC | 1         | 0.67%   |
| Lenovo G550 2958                           | 1         | 0.67%   |
| Lenovo G550 20023                          | 1         | 0.67%   |
| Lenovo G50-80 80E5                         | 1         | 0.67%   |
| Lenovo Flex 2-14D 20376                    | 1         | 0.67%   |
| Intel NUC10i3FNH                           | 1         | 0.67%   |
| HUAWEI NBLK-WAX9X                          | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 8.67%   |
| Lenovo IdeaPad         | 7         | 4.67%   |
| HP EliteBook           | 4         | 2.67%   |
| Dell Inspiron          | 4         | 2.67%   |
| Dell Precision         | 3         | 2%      |
| ASUS VivoBook          | 3         | 2%      |
| ASUS TUF               | 3         | 2%      |
| Apple MacBookPro8      | 3         | 2%      |
| Apple MacBookPro5      | 3         | 2%      |
| Apple MacBook5         | 3         | 2%      |
| Acer Aspire            | 3         | 2%      |
| Microsoft Surface      | 2         | 1.33%   |
| Lenovo Legion          | 2         | 1.33%   |
| Lenovo G550            | 2         | 1.33%   |
| HUAWEI MACHD-WXX9      | 2         | 1.33%   |
| HP ProBook             | 2         | 1.33%   |
| HP Pavilion            | 2         | 1.33%   |
| HP Laptop              | 2         | 1.33%   |
| Dell Vostro            | 2         | 1.33%   |
| Dell Latitude          | 2         | 1.33%   |
| ASUS ZenBook           | 2         | 1.33%   |
| ASUS ROG               | 2         | 1.33%   |
| Apple MacBookPro9      | 2         | 1.33%   |
| Acer Swift             | 2         | 1.33%   |
| Wortmann AG 1220729    | 1         | 0.67%   |
| Timi TM1613            | 1         | 0.67%   |
| Teclast X6             | 1         | 0.67%   |
| Teclast F7             | 1         | 0.67%   |
| Star Labs StarBook     | 1         | 0.67%   |
| Star Labs LabTop       | 1         | 0.67%   |
| Sony VPCEA3S1E         | 1         | 0.67%   |
| Sony SVE14A390X        | 1         | 0.67%   |
| Samsung 900X3C         | 1         | 0.67%   |
| Razer Blade            | 1         | 0.67%   |
| Notebook W65           | 1         | 0.67%   |
| Notebook P65xHP        | 1         | 0.67%   |
| MSI PS63               | 1         | 0.67%   |
| MSI PPPPP-CCC#MMMMMMMM | 1         | 0.67%   |
| MSI MS-7C52            | 1         | 0.67%   |
| MSI MS-7C02            | 1         | 0.67%   |
| MSI MS-7B86            | 1         | 0.67%   |
| MSI MS-7B79            | 1         | 0.67%   |
| MSI MS-7A59            | 1         | 0.67%   |
| MSI GF63               | 1         | 0.67%   |
| Monster MARKUT         | 1         | 0.67%   |
| Monster ABRA           | 1         | 0.67%   |
| LG A410-G.BC51P1       | 1         | 0.67%   |
| Lenovo Yoga            | 1         | 0.67%   |
| Lenovo IdeaCentre      | 1         | 0.67%   |
| Lenovo G50-80          | 1         | 0.67%   |
| Lenovo Flex            | 1         | 0.67%   |
| Intel NUC10i3FNH       | 1         | 0.67%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.67%   |
| HUAWEI MACHC-WAX9      | 1         | 0.67%   |
| HUAWEI KPL-W0X         | 1         | 0.67%   |
| HP Z420                | 1         | 0.67%   |
| HP ProLiant            | 1         | 0.67%   |
| HP ProDesk             | 1         | 0.67%   |
| HP Elite               | 1         | 0.67%   |
| HP Compaq              | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 22        | 14.67%  |
| 2018 | 18        | 12%     |
| 2021 | 14        | 9.33%   |
| 2019 | 14        | 9.33%   |
| 2015 | 13        | 8.67%   |
| 2012 | 11        | 7.33%   |
| 2014 | 10        | 6.67%   |
| 2011 | 9         | 6%      |
| 2016 | 8         | 5.33%   |
| 2009 | 8         | 5.33%   |
| 2017 | 6         | 4%      |
| 2013 | 6         | 4%      |
| 2010 | 6         | 4%      |
| 2008 | 4         | 2.67%   |
| 2007 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 104       | 69.33%  |
| Desktop     | 35        | 23.33%  |
| All in one  | 4         | 2.67%   |
| Tablet      | 3         | 2%      |
| Convertible | 2         | 1.33%   |
| Mini pc     | 1         | 0.67%   |
| Server      | 1         | 0.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 133       | 88.67%  |
| Enabled  | 17        | 11.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 148       | 98.67%  |
| Yes  | 2         | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 34.67%  |
| 16.01-24.0  | 31        | 20.67%  |
| 8.01-16.0   | 22        | 14.67%  |
| 3.01-4.0    | 21        | 14%     |
| 32.01-64.0  | 16        | 10.67%  |
| 1.01-2.0    | 4         | 2.67%   |
| 24.01-32.0  | 2         | 1.33%   |
| 64.01-256.0 | 2         | 1.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 49        | 32.45%  |
| 2.01-3.0  | 43        | 28.48%  |
| 3.01-4.0  | 23        | 15.23%  |
| 4.01-8.0  | 21        | 13.91%  |
| 8.01-16.0 | 8         | 5.3%    |
| 0.51-1.0  | 7         | 4.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 93        | 62%     |
| 2      | 39        | 26%     |
| 3      | 11        | 7.33%   |
| 4      | 3         | 2%      |
| 5      | 2         | 1.33%   |
| 7      | 1         | 0.67%   |
| 6      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 100       | 66.67%  |
| Yes       | 50        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 77.33%  |
| No        | 34        | 22.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 86.67%  |
| No        | 20        | 13.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 79.33%  |
| No        | 31        | 20.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 23        | 15.33%  |
| USA          | 16        | 10.67%  |
| India        | 11        | 7.33%   |
| Brazil       | 10        | 6.67%   |
| UK           | 7         | 4.67%   |
| Poland       | 7         | 4.67%   |
| Turkey       | 6         | 4%      |
| Canada       | 6         | 4%      |
| Russia       | 5         | 3.33%   |
| Italy        | 5         | 3.33%   |
| France       | 4         | 2.67%   |
| Sweden       | 3         | 2%      |
| Indonesia    | 3         | 2%      |
| Austria      | 3         | 2%      |
| Australia    | 3         | 2%      |
| Spain        | 2         | 1.33%   |
| Romania      | 2         | 1.33%   |
| Portugal     | 2         | 1.33%   |
| New Zealand  | 2         | 1.33%   |
| Mexico       | 2         | 1.33%   |
| Czechia      | 2         | 1.33%   |
| Belgium      | 2         | 1.33%   |
| Belarus      | 2         | 1.33%   |
| Ukraine      | 1         | 0.67%   |
| Thailand     | 1         | 0.67%   |
| Switzerland  | 1         | 0.67%   |
| Sri Lanka    | 1         | 0.67%   |
| South Africa | 1         | 0.67%   |
| Pakistan     | 1         | 0.67%   |
| Netherlands  | 1         | 0.67%   |
| Mozambique   | 1         | 0.67%   |
| Malaysia     | 1         | 0.67%   |
| Lithuania    | 1         | 0.67%   |
| Kenya        | 1         | 0.67%   |
| Japan        | 1         | 0.67%   |
| Iran         | 1         | 0.67%   |
| Hungary      | 1         | 0.67%   |
| Hong Kong    | 1         | 0.67%   |
| Guyana       | 1         | 0.67%   |
| Greece       | 1         | 0.67%   |
| Croatia      | 1         | 0.67%   |
| Colombia     | 1         | 0.67%   |
| Chile        | 1         | 0.67%   |
| Bulgaria     | 1         | 0.67%   |
| Argentina    | 1         | 0.67%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Warsaw                        | 3         | 1.97%   |
| Sydney                        | 3         | 1.97%   |
| Munich                        | 3         | 1.97%   |
| Ankara                        | 3         | 1.97%   |
| Vienna                        | 2         | 1.32%   |
| Minsk                         | 2         | 1.32%   |
| Hamburg                       | 2         | 1.32%   |
| Antalya                       | 2         | 1.32%   |
| Znojmo                        | 1         | 0.66%   |
| Wroclaw                       | 1         | 0.66%   |
| Wriedel                       | 1         | 0.66%   |
| Wellington                    | 1         | 0.66%   |
| Wattala                       | 1         | 0.66%   |
| Vit??ria da Conquista         | 1         | 0.66%   |
| Vinnytsia                     | 1         | 0.66%   |
| Vilanova i la Geltr??         | 1         | 0.66%   |
| Vila Nova de Gaia             | 1         | 0.66%   |
| Uppsala                       | 1         | 0.66%   |
| Tongeren                      | 1         | 0.66%   |
| Thrissur                      | 1         | 0.66%   |
| Tehran                        | 1         | 0.66%   |
| Tecuci                        | 1         | 0.66%   |
| Surrey                        | 1         | 0.66%   |
| Surabaya                      | 1         | 0.66%   |
| Stockholm                     | 1         | 0.66%   |
| Steinbach                     | 1         | 0.66%   |
| Southampton                   | 1         | 0.66%   |
| Sornay                        | 1         | 0.66%   |
| Soliera                       | 1         | 0.66%   |
| Solapur                       | 1         | 0.66%   |
| Siersburg                     | 1         | 0.66%   |
| Shetland Islands              | 1         | 0.66%   |
| S??o Paulo                    | 1         | 0.66%   |
| S??o Bernardo do Campo        | 1         | 0.66%   |
| Sazava                        | 1         | 0.66%   |
| Santo Andr?�                  | 1         | 0.66%   |
| San Antonio                   | 1         | 0.66%   |
| Samobor                       | 1         | 0.66%   |
| Saltsjoe-Boo                  | 1         | 0.66%   |
| Saguenay                      | 1         | 0.66%   |
| Saalfelden am Steinernen Meer | 1         | 0.66%   |
| Russell                       | 1         | 0.66%   |
| Rueso                         | 1         | 0.66%   |
| Rostock                       | 1         | 0.66%   |
| Rome                          | 1         | 0.66%   |
| Pune                          | 1         | 0.66%   |
| Providencia                   | 1         | 0.66%   |
| Porto                         | 1         | 0.66%   |
| Petaling Jaya                 | 1         | 0.66%   |
| Patna                         | 1         | 0.66%   |
| Osasco                        | 1         | 0.66%   |
| Osaka                         | 1         | 0.66%   |
| Orenburg                      | 1         | 0.66%   |
| Oldham                        | 1         | 0.66%   |
| Oldenburg                     | 1         | 0.66%   |
| Oceanside                     | 1         | 0.66%   |
| Novosibirsk                   | 1         | 0.66%   |
| Napier City                   | 1         | 0.66%   |
| Nairobi                       | 1         | 0.66%   |
| Mumbai                        | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 40        | 47     | 18.43%  |
| WDC                 | 28        | 36     | 12.9%   |
| Seagate             | 21        | 22     | 9.68%   |
| Kingston            | 19        | 20     | 8.76%   |
| SanDisk             | 14        | 14     | 6.45%   |
| Crucial             | 13        | 14     | 5.99%   |
| Unknown             | 8         | 10     | 3.69%   |
| Toshiba             | 8         | 10     | 3.69%   |
| SK Hynix            | 6         | 6      | 2.76%   |
| Intel               | 5         | 6      | 2.3%    |
| Hitachi             | 5         | 5      | 2.3%    |
| A-DATA Technology   | 5         | 5      | 2.3%    |
| Unknown             | 5         | 6      | 2.3%    |
| HGST                | 4         | 4      | 1.84%   |
| Apple               | 4         | 4      | 1.84%   |
| Micron Technology   | 3         | 3      | 1.38%   |
| KIOXIA              | 3         | 3      | 1.38%   |
| Transcend           | 2         | 2      | 0.92%   |
| Teclast             | 2         | 2      | 0.92%   |
| Phison              | 2         | 2      | 0.92%   |
| ASMT                | 2         | 2      | 0.92%   |
| Team                | 1         | 1      | 0.46%   |
| Star Drive          | 1         | 1      | 0.46%   |
| Star                | 1         | 1      | 0.46%   |
| SPCC                | 1         | 1      | 0.46%   |
| Silicon Motion      | 1         | 1      | 0.46%   |
| SABRENT             | 1         | 1      | 0.46%   |
| PNY                 | 1         | 1      | 0.46%   |
| OCZ                 | 1         | 1      | 0.46%   |
| MAXTOR              | 1         | 1      | 0.46%   |
| LITEON              | 1         | 1      | 0.46%   |
| KingSpec            | 1         | 1      | 0.46%   |
| JMicron             | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| GOODRAM             | 1         | 1      | 0.46%   |
| Fujitsu             | 1         | 1      | 0.46%   |
| Ext Hard            | 1         | 1      | 0.46%   |
| China               | 1         | 1      | 0.46%   |
| Apacer              | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 5         | 2.16%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 2.16%   |
| Kingston SA400S37240G 240GB SSD      | 5         | 2.16%   |
| Unknown                              | 5         | 2.16%   |
| Samsung SSD 850 EVO 250GB            | 3         | 1.3%    |
| Samsung NVMe SSD Drive 500GB         | 3         | 1.3%    |
| Samsung NVMe SSD Drive 256GB         | 3         | 1.3%    |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.3%    |
| Kingston NVMe SSD Drive 500GB        | 3         | 1.3%    |
| Intel NVMe SSD Drive 512GB           | 3         | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.87%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.87%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.87%   |
| SK Hynix NVMe SSD Drive 512GB        | 2         | 0.87%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 0.87%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 0.87%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD  | 2         | 0.87%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.87%   |
| Samsung SSD 850 EVO 120GB            | 2         | 0.87%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.87%   |
| Kingston NVMe SSD Drive 1TB          | 2         | 0.87%   |
| Hitachi HTS547575A9E384 752GB        | 2         | 0.87%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.87%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.87%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.43%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.43%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.43%   |
| WDC WD7500BPVT-22A1YT0 752GB         | 1         | 0.43%   |
| WDC WD6401AALS-00L3B2 640GB          | 1         | 0.43%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.43%   |
| WDC WD5000BPVT-22HXZT1 500GB         | 1         | 0.43%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.43%   |
| WDC WD5000AAKS-00UU3A0 500GB         | 1         | 0.43%   |
| WDC WD40EZAZ-00SF3B0 4TB             | 1         | 0.43%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 0.43%   |
| WDC WD3200AAJS-40RYA0 320GB          | 1         | 0.43%   |
| WDC WD3003FZEX-00Z4SA0 3TB           | 1         | 0.43%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.43%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.43%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 0.43%   |
| WDC WD1600JS-55NCB1 160GB            | 1         | 0.43%   |
| WDC WD15EARX-00PASB0 1TB             | 1         | 0.43%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1         | 0.43%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.43%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.43%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 0.43%   |
| WDC PC SN730 SDBQNTY-1T00-1014 1TB   | 1         | 0.43%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 1         | 0.43%   |
| WDC PC SN520 SDAPNUW-512G            | 1         | 0.43%   |
| Unknown USD00  16GB                  | 1         | 0.43%   |
| Unknown SL128  128GB                 | 1         | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 0.43%   |
| Unknown SD/MMC/M.S.PRO 32GB          | 1         | 0.43%   |
| Unknown SD/MMC 16GB                  | 1         | 0.43%   |
| Unknown SC128  128GB                 | 1         | 0.43%   |
| Unknown MMC Card  128GB              | 1         | 0.43%   |
| Unknown M.S./M.S.Pro/HG 16GB         | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 24     | 33.9%   |
| Seagate             | 20        | 21     | 33.9%   |
| Toshiba             | 5         | 6      | 8.47%   |
| Hitachi             | 5         | 5      | 8.47%   |
| HGST                | 4         | 4      | 6.78%   |
| Unknown             | 1         | 1      | 1.69%   |
| Samsung Electronics | 1         | 2      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |
| Ext Hard            | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 24     | 24.18%  |
| Crucial             | 13        | 14     | 14.29%  |
| Kingston            | 12        | 12     | 13.19%  |
| SanDisk             | 10        | 10     | 10.99%  |
| WDC                 | 5         | 9      | 5.49%   |
| A-DATA Technology   | 4         | 4      | 4.4%    |
| Micron Technology   | 3         | 3      | 3.3%    |
| Transcend           | 2         | 2      | 2.2%    |
| Teclast             | 2         | 2      | 2.2%    |
| Apple               | 2         | 2      | 2.2%    |
| Toshiba             | 1         | 1      | 1.1%    |
| Team                | 1         | 1      | 1.1%    |
| Star                | 1         | 1      | 1.1%    |
| SPCC                | 1         | 1      | 1.1%    |
| SABRENT             | 1         | 1      | 1.1%    |
| PNY                 | 1         | 1      | 1.1%    |
| OCZ                 | 1         | 1      | 1.1%    |
| MAXTOR              | 1         | 1      | 1.1%    |
| LITEON              | 1         | 1      | 1.1%    |
| KingSpec            | 1         | 1      | 1.1%    |
| Intenso             | 1         | 1      | 1.1%    |
| GOODRAM             | 1         | 1      | 1.1%    |
| China               | 1         | 1      | 1.1%    |
| ASMT                | 1         | 1      | 1.1%    |
| Apacer              | 1         | 1      | 1.1%    |
| Unknown             | 1         | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 81        | 98     | 40.5%   |
| NVMe    | 53        | 61     | 26.5%   |
| HDD     | 53        | 66     | 26.5%   |
| MMC     | 8         | 9      | 4%      |
| Unknown | 5         | 7      | 2.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 111       | 158    | 60.99%  |
| NVMe | 53        | 61     | 29.12%  |
| SAS  | 10        | 13     | 5.49%   |
| MMC  | 8         | 9      | 4.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 101    | 61.72%  |
| 0.51-1.0   | 33        | 42     | 25.78%  |
| 1.01-2.0   | 8         | 12     | 6.25%   |
| 3.01-4.0   | 4         | 4      | 3.13%   |
| 4.01-10.0  | 3         | 3      | 2.34%   |
| 2.01-3.0   | 1         | 2      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 41.33%  |
| 251-500        | 34        | 22.67%  |
| 501-1000       | 20        | 13.33%  |
| 1001-2000      | 12        | 8%      |
| 51-100         | 12        | 8%      |
| More than 3000 | 6         | 4%      |
| 21-50          | 4         | 2.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 58        | 38.16%  |
| 21-50          | 41        | 26.97%  |
| 101-250        | 18        | 11.84%  |
| 51-100         | 15        | 9.87%   |
| 251-500        | 9         | 5.92%   |
| 501-1000       | 5         | 3.29%   |
| 1001-2000      | 3         | 1.97%   |
| 2001-3000      | 2         | 1.32%   |
| More than 3000 | 1         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB          | 1         | 1      | 20%     |
| Toshiba KBG30ZPZ128G 128GB      | 1         | 1      | 20%     |
| Seagate ST500LM030-2E717D 500GB | 1         | 1      | 20%     |
| Seagate ST3500312CS 500GB       | 1         | 1      | 20%     |
| Crucial CT512M550SSD3 512GB     | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Crucial | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 124       | 187    | 76.07%  |
| Works    | 34        | 49     | 20.86%  |
| Malfunc  | 5         | 5      | 3.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 53.3%   |
| AMD                          | 23        | 12.64%  |
| Samsung Electronics          | 20        | 10.99%  |
| Kingston Technology Company  | 8         | 4.4%    |
| Sandisk                      | 7         | 3.85%   |
| Nvidia                       | 7         | 3.85%   |
| SK Hynix                     | 6         | 3.3%    |
| Phison Electronics           | 3         | 1.65%   |
| Toshiba America Info Systems | 2         | 1.1%    |
| KIOXIA                       | 2         | 1.1%    |
| Silicon Motion               | 1         | 0.55%   |
| Seagate Technology           | 1         | 0.55%   |
| Realtek Semiconductor        | 1         | 0.55%   |
| Marvell Technology Group     | 1         | 0.55%   |
| Hewlett-Packard              | 1         | 0.55%   |
| ASMedia Technology           | 1         | 0.55%   |
| Apple                        | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 7.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 5.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 3.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 8         | 3.96%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 3.47%   |
| Nvidia MCP79 AHCI Controller                                                            | 7         | 3.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.48%   |
| Kingston Company A2000 NVMe SSD                                                         | 4         | 1.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.98%   |
| Intel SSD 660P Series                                                                   | 4         | 1.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.98%   |
| SK Hynix BC511                                                                          | 3         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.49%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 2         | 0.99%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.99%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.99%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.99%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.99%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 2         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 0.99%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.5%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.5%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.5%    |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 0.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.5%    |
| Silicon Motion Non-Volatile memory controller                                           | 1         | 0.5%    |
| Seagate FireCuda 530 SSD                                                                | 1         | 0.5%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.5%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.5%    |
| Sandisk Non-Volatile memory controller                                                  | 1         | 0.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.5%    |
| Samsung Electronics SATA controller                                                     | 1         | 0.5%    |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.5%    |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1         | 0.5%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 1         | 0.5%    |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1         | 0.5%    |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 116       | 61.7%   |
| NVMe | 52        | 27.66%  |
| IDE  | 12        | 6.38%   |
| RAID | 7         | 3.72%   |
| SAS  | 1         | 0.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 118       | 78.67%  |
| AMD    | 32        | 21.33%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2%      |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 1.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.33%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 1.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.33%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.33%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 1.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.33%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2         | 1.33%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.33%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.33%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.33%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.33%   |
| Intel Xeon CPU E5462 @ 2.80GHz                | 1         | 0.67%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.67%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.67%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.67%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.67%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.67%   |
| Intel Pentium CPU 4415Y @ 1.60GHz             | 1         | 0.67%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.67%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.67%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.67%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.67%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.67%   |
| Intel Core i7-4930K CPU @ 3.40GHz             | 1         | 0.67%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.67%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 1         | 0.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.67%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.67%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.67%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.67%   |
| Intel Core i7-2675QM CPU @ 2.20GHz            | 1         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.67%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.67%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.67%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.67%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 0.67%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 36        | 24%     |
| Intel Core i5           | 35        | 23.33%  |
| Intel Core i3           | 12        | 8%      |
| Intel Core 2 Duo        | 11        | 7.33%   |
| AMD Ryzen 5             | 10        | 6.67%   |
| Other                   | 9         | 6%      |
| AMD Ryzen 7             | 8         | 5.33%   |
| Intel Celeron           | 7         | 4.67%   |
| Intel Xeon              | 3         | 2%      |
| Intel Pentium           | 3         | 2%      |
| AMD Ryzen 9             | 2         | 1.33%   |
| AMD Ryzen 7 PRO         | 2         | 1.33%   |
| AMD Ryzen 3             | 2         | 1.33%   |
| AMD Phenom II X4        | 2         | 1.33%   |
| Intel Pentium Dual-Core | 1         | 0.67%   |
| Intel Core m5           | 1         | 0.67%   |
| Intel Celeron Dual-Core | 1         | 0.67%   |
| Intel Atom              | 1         | 0.67%   |
| AMD FX                  | 1         | 0.67%   |
| AMD Athlon              | 1         | 0.67%   |
| AMD A8                  | 1         | 0.67%   |
| AMD A6                  | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 40.67%  |
| 4      | 54        | 36%     |
| 8      | 16        | 10.67%  |
| 6      | 15        | 10%     |
| 12     | 2         | 1.33%   |
| 16     | 1         | 0.67%   |
| 1      | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 148       | 98.67%  |
| 2      | 2         | 1.33%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 105       | 70%     |
| 1      | 45        | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 150       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 8.67%   |
| 0x206a7    | 11        | 7.33%   |
| 0x306a9    | 9         | 6%      |
| 0x406e3    | 7         | 4.67%   |
| 0x906ea    | 6         | 4%      |
| 0x806c1    | 6         | 4%      |
| 0x1067a    | 6         | 4%      |
| 0x806ec    | 5         | 3.33%   |
| 0x40651    | 5         | 3.33%   |
| 0x306d4    | 5         | 3.33%   |
| 0x306c3    | 5         | 3.33%   |
| 0x10676    | 5         | 3.33%   |
| 0x08600106 | 5         | 3.33%   |
| 0x20655    | 4         | 2.67%   |
| 0x08701021 | 4         | 2.67%   |
| 0x806eb    | 3         | 2%      |
| 0x806e9    | 3         | 2%      |
| 0x906ed    | 2         | 1.33%   |
| 0x906e9    | 2         | 1.33%   |
| 0x806ea    | 2         | 1.33%   |
| 0x506e3    | 2         | 1.33%   |
| 0x506c9    | 2         | 1.33%   |
| 0x406c3    | 2         | 1.33%   |
| 0x206d7    | 2         | 1.33%   |
| 0x08608103 | 2         | 1.33%   |
| 0x08108109 | 2         | 1.33%   |
| 0x08108102 | 2         | 1.33%   |
| 0x08101007 | 2         | 1.33%   |
| 0xa0671    | 1         | 0.67%   |
| 0xa0660    | 1         | 0.67%   |
| 0xa0652    | 1         | 0.67%   |
| 0x906ec    | 1         | 0.67%   |
| 0x906eb    | 1         | 0.67%   |
| 0x706a1    | 1         | 0.67%   |
| 0x6fd      | 1         | 0.67%   |
| 0x6fb      | 1         | 0.67%   |
| 0x6fa      | 1         | 0.67%   |
| 0x406c4    | 1         | 0.67%   |
| 0x40661    | 1         | 0.67%   |
| 0x306e4    | 1         | 0.67%   |
| 0x30678    | 1         | 0.67%   |
| 0x106e5    | 1         | 0.67%   |
| 0x0a201009 | 1         | 0.67%   |
| 0x08701013 | 1         | 0.67%   |
| 0x08600104 | 1         | 0.67%   |
| 0x08101016 | 1         | 0.67%   |
| 0x0800820d | 1         | 0.67%   |
| 0x07030105 | 1         | 0.67%   |
| 0x07030104 | 1         | 0.67%   |
| 0x06006705 | 1         | 0.67%   |
| 0x06006704 | 1         | 0.67%   |
| 0x0600063e | 1         | 0.67%   |
| 0x010000db | 1         | 0.67%   |
| 0x010000c8 | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 31        | 20.67%  |
| SandyBridge   | 14        | 9.33%   |
| Zen 2         | 13        | 8.67%   |
| Haswell       | 12        | 8%      |
| Penryn        | 11        | 7.33%   |
| Skylake       | 10        | 6.67%   |
| IvyBridge     | 10        | 6.67%   |
| TigerLake     | 6         | 4%      |
| Zen+          | 5         | 3.33%   |
| Westmere      | 5         | 3.33%   |
| Broadwell     | 5         | 3.33%   |
| Silvermont    | 4         | 2.67%   |
| Zen           | 3         | 2%      |
| Core          | 3         | 2%      |
| Unknown       | 3         | 2%      |
| Puma          | 2         | 1.33%   |
| K10           | 2         | 1.33%   |
| Goldmont      | 2         | 1.33%   |
| Excavator     | 2         | 1.33%   |
| CometLake     | 2         | 1.33%   |
| Zen 3         | 1         | 0.67%   |
| Nehalem       | 1         | 0.67%   |
| Icelake       | 1         | 0.67%   |
| Goldmont plus | 1         | 0.67%   |
| Bulldozer     | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 92        | 51.11%  |
| Nvidia                     | 49        | 27.22%  |
| AMD                        | 38        | 21.11%  |
| Matrox Electronics Systems | 1         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 6.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.8%    |
| AMD Renoir                                                                               | 7         | 3.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 3.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.26%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 2.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.72%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.17%   |
| Intel HD Graphics 5500                                                                   | 4         | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.63%   |
| AMD Lucienne                                                                             | 3         | 1.63%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 1.09%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.09%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.09%   |
| Intel HD Graphics 620                                                                    | 2         | 1.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.09%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.09%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 1.09%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.54%   |
| Nvidia TU117M                                                                            | 1         | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.54%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.54%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.54%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.54%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 0.54%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.54%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 0.54%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.54%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 0.54%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 0.54%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.54%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.54%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.54%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.54%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.54%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.54%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.54%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.54%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 0.54%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.54%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 42%     |
| 1 x AMD        | 30        | 20%     |
| 1 x Nvidia     | 25        | 16.67%  |
| Intel + Nvidia | 22        | 14.67%  |
| Intel + AMD    | 6         | 4%      |
| 2 x Nvidia     | 1         | 0.67%   |
| 2 x AMD        | 1         | 0.67%   |
| 1 x Matrox     | 1         | 0.67%   |
| AMD + Nvidia   | 1         | 0.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 123       | 82%     |
| Proprietary | 27        | 18%     |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 48.67%  |
| 0.01-0.5   | 22        | 14.67%  |
| 1.01-2.0   | 20        | 13.33%  |
| 3.01-4.0   | 14        | 9.33%   |
| 0.51-1.0   | 11        | 7.33%   |
| 7.01-8.0   | 4         | 2.67%   |
| 5.01-6.0   | 3         | 2%      |
| 8.01-16.0  | 2         | 1.33%   |
| 2.01-3.0   | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 13.37%  |
| LG Display              | 20        | 11.63%  |
| Apple                   | 19        | 11.05%  |
| Chimei Innolux          | 16        | 9.3%    |
| Samsung Electronics     | 15        | 8.72%   |
| BOE                     | 10        | 5.81%   |
| Goldstar                | 8         | 4.65%   |
| Acer                    | 8         | 4.65%   |
| Sharp                   | 7         | 4.07%   |
| Hewlett-Packard         | 6         | 3.49%   |
| Lenovo                  | 5         | 2.91%   |
| Dell                    | 5         | 2.91%   |
| PANDA                   | 3         | 1.74%   |
| CSO                     | 3         | 1.74%   |
| BenQ                    | 3         | 1.74%   |
| AOC                     | 3         | 1.74%   |
| Philips                 | 2         | 1.16%   |
| ViewSonic               | 1         | 0.58%   |
| Sony                    | 1         | 0.58%   |
| Panasonic               | 1         | 0.58%   |
| MSI                     | 1         | 0.58%   |
| LG Electronics          | 1         | 0.58%   |
| JDI                     | 1         | 0.58%   |
| InfoVision              | 1         | 0.58%   |
| Iiyama                  | 1         | 0.58%   |
| HPN                     | 1         | 0.58%   |
| Element                 | 1         | 0.58%   |
| Eizo                    | 1         | 0.58%   |
| CHR                     | 1         | 0.58%   |
| Chi Mei Optoelectronics | 1         | 0.58%   |
| CHD                     | 1         | 0.58%   |
| AUS                     | 1         | 0.58%   |
| Unknown                 | 1         | 0.58%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.68%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.12%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 1.12%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 1.12%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 1.12%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 2         | 1.12%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 2         | 1.12%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                              | 1         | 0.56%   |
| ViewSonic LCD Monitor VX2260WM                                        | 1         | 0.56%   |
| Sony Nvidia Defaul SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.56%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.56%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.56%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.56%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.56%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch     | 1         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch  | 1         | 0.56%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1         | 0.56%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor S22D300                               | 1         | 0.56%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch    | 1         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.56%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch               | 1         | 0.56%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                              | 1         | 0.56%   |
| Philips LCD Monitor PHL 276E8V                                        | 1         | 0.56%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.56%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.56%   |
| MSI MAG341CQ MSI1462 3440x1440 800x330mm 34.1-inch                    | 1         | 0.56%   |
| LG Electronics LCD Monitor 2D FHD LG TV 3840x1080                     | 1         | 0.56%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD05F3 1920x1080 309x174mm 14.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 0.56%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 1         | 0.56%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 38.46%  |
| 1366x768 (WXGA)    | 34        | 20.12%  |
| 2560x1440 (QHD)    | 13        | 7.69%   |
| 3840x2160 (4K)     | 11        | 6.51%   |
| 1280x800 (WXGA)    | 8         | 4.73%   |
| 1600x900 (HD+)     | 7         | 4.14%   |
| 1440x900 (WXGA+)   | 5         | 2.96%   |
| 3000x2000          | 3         | 1.78%   |
| 1680x1050 (WSXGA+) | 3         | 1.78%   |
| Unknown            | 3         | 1.78%   |
| 3840x1080          | 2         | 1.18%   |
| 2560x1080          | 2         | 1.18%   |
| 1920x1200 (WUXGA)  | 2         | 1.18%   |
| 1360x768           | 2         | 1.18%   |
| 7680x2160          | 1         | 0.59%   |
| 3840x2400          | 1         | 0.59%   |
| 3440x1440          | 1         | 0.59%   |
| 3200x1800 (QHD+)   | 1         | 0.59%   |
| 3072x1920          | 1         | 0.59%   |
| 2880x1920          | 1         | 0.59%   |
| 2880x1800          | 1         | 0.59%   |
| 1920x1280          | 1         | 0.59%   |
| 1800x1200          | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 51        | 29.65%  |
| 13      | 27        | 15.7%   |
| 14      | 18        | 10.47%  |
| 24      | 11        | 6.4%    |
| Unknown | 11        | 6.4%    |
| 27      | 8         | 4.65%   |
| 23      | 8         | 4.65%   |
| 21      | 6         | 3.49%   |
| 31      | 4         | 2.33%   |
| 20      | 4         | 2.33%   |
| 17      | 4         | 2.33%   |
| 34      | 3         | 1.74%   |
| 12      | 3         | 1.74%   |
| 11      | 3         | 1.74%   |
| 32      | 2         | 1.16%   |
| 25      | 2         | 1.16%   |
| 47      | 1         | 0.58%   |
| 26      | 1         | 0.58%   |
| 22      | 1         | 0.58%   |
| 19      | 1         | 0.58%   |
| 18      | 1         | 0.58%   |
| 16      | 1         | 0.58%   |
| 10      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 45.56%  |
| 501-600     | 26        | 15.38%  |
| 201-300     | 26        | 15.38%  |
| 401-500     | 12        | 7.1%    |
| Unknown     | 11        | 6.51%   |
| 601-700     | 6         | 3.55%   |
| 701-800     | 5         | 2.96%   |
| 351-400     | 5         | 2.96%   |
| 1001-1500   | 1         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 111       | 72.55%  |
| 16/10   | 23        | 15.03%  |
| Unknown | 9         | 5.88%   |
| 3/2     | 7         | 4.58%   |
| 21/9    | 3         | 1.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 28.24%  |
| 81-90          | 34        | 20%     |
| 201-250        | 18        | 10.59%  |
| 71-80          | 12        | 7.06%   |
| Unknown        | 11        | 6.47%   |
| 351-500        | 9         | 5.29%   |
| 301-350        | 9         | 5.29%   |
| 251-300        | 7         | 4.12%   |
| 151-200        | 6         | 3.53%   |
| 51-60          | 3         | 1.76%   |
| 121-130        | 3         | 1.76%   |
| 61-70          | 2         | 1.18%   |
| 111-120        | 2         | 1.18%   |
| 91-100         | 2         | 1.18%   |
| 41-50          | 1         | 0.59%   |
| 141-150        | 1         | 0.59%   |
| 131-140        | 1         | 0.59%   |
| 501-1000       | 1         | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 31.55%  |
| 101-120       | 47        | 27.98%  |
| 51-100        | 37        | 22.02%  |
| Unknown       | 11        | 6.55%   |
| 161-240       | 10        | 5.95%   |
| More than 240 | 9         | 5.36%   |
| 1-50          | 1         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 122       | 81.33%  |
| 2     | 24        | 16%     |
| 3     | 4         | 2.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 73        | 32.16%  |
| Intel                    | 70        | 30.84%  |
| Broadcom                 | 29        | 12.78%  |
| Qualcomm Atheros         | 18        | 7.93%   |
| Nvidia                   | 7         | 3.08%   |
| Marvell Technology Group | 4         | 1.76%   |
| Broadcom Limited         | 4         | 1.76%   |
| TP-Link                  | 3         | 1.32%   |
| Ralink Technology        | 3         | 1.32%   |
| Ralink                   | 3         | 1.32%   |
| Google                   | 2         | 0.88%   |
| Xiaomi                   | 1         | 0.44%   |
| Sitecom Europe           | 1         | 0.44%   |
| Sierra Wireless          | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| OPPO Electronics         | 1         | 0.44%   |
| Motorola PCS             | 1         | 0.44%   |
| Microsoft                | 1         | 0.44%   |
| MEDIATEK                 | 1         | 0.44%   |
| Linksys                  | 1         | 0.44%   |
| Hewlett-Packard          | 1         | 0.44%   |
| Apple                    | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 19.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.65%   |
| Nvidia MCP79 Ethernet                                             | 7         | 2.65%   |
| Intel Wireless 8260                                               | 7         | 2.65%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 7         | 2.65%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.52%   |
| Intel Wireless 7265                                               | 4         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.14%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.14%   |
| Intel Wireless-AC 9260                                            | 3         | 1.14%   |
| Intel Wireless 7260                                               | 3         | 1.14%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.14%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 1.14%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.76%   |
| Realtek 802.11ac NIC                                              | 2         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.76%   |
| Intel Wireless 3165                                               | 2         | 0.76%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.76%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 0.76%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 2         | 0.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2         | 0.76%   |
| Broadcom BCM43227 802.11b/g/n                                     | 2         | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.38%   |
| TP-Link 802.11n NIC                                               | 1         | 0.38%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.38%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.38%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N          | 1         | 0.38%   |
| Sierra Wireless EM7455                                            | 1         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.38%   |
| Realtek Realtek Network controller                                | 1         | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 60        | 43.8%   |
| Broadcom                 | 28        | 20.44%  |
| Realtek Semiconductor    | 16        | 11.68%  |
| Qualcomm Atheros         | 14        | 10.22%  |
| Broadcom Limited         | 4         | 2.92%   |
| TP-Link                  | 3         | 2.19%   |
| Ralink Technology        | 3         | 2.19%   |
| Ralink                   | 3         | 2.19%   |
| Sitecom Europe           | 1         | 0.73%   |
| Sierra Wireless          | 1         | 0.73%   |
| Microsoft                | 1         | 0.73%   |
| MEDIATEK                 | 1         | 0.73%   |
| Marvell Technology Group | 1         | 0.73%   |
| Linksys                  | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 7         | 5.07%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 5.07%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 7         | 5.07%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 4.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 4.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 3.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 3.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.9%    |
| Intel Wireless 8265 / 8275                                     | 4         | 2.9%    |
| Intel Wireless 7265                                            | 4         | 2.9%    |
| Ralink MT7601U Wireless Adapter                                | 3         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.17%   |
| Intel Wireless-AC 9260                                         | 3         | 2.17%   |
| Intel Wireless 7260                                            | 3         | 2.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 2.17%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.45%   |
| Realtek 802.11ac NIC                                           | 2         | 1.45%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.45%   |
| Intel Wireless 3165                                            | 2         | 1.45%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 1.45%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 1.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.45%   |
| TP-Link 802.11n NIC                                            | 1         | 0.72%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.72%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.72%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N       | 1         | 0.72%   |
| Sierra Wireless EM7455                                         | 1         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek Realtek Network controller                             | 1         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.72%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 0.72%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.72%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 0.72%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                      | 1         | 0.72%   |
| Intel Wireless Gigabit 17265                                   | 1         | 0.72%   |
| Intel Wireless 3160                                            | 1         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.72%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.72%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 0.72%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 1         | 0.72%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 67        | 53.6%   |
| Intel                    | 26        | 20.8%   |
| Broadcom                 | 9         | 7.2%    |
| Nvidia                   | 7         | 5.6%    |
| Qualcomm Atheros         | 4         | 3.2%    |
| Marvell Technology Group | 3         | 2.4%    |
| Google                   | 2         | 1.6%    |
| Xiaomi                   | 1         | 0.8%    |
| Samsung Electronics      | 1         | 0.8%    |
| OPPO Electronics         | 1         | 0.8%    |
| Motorola PCS             | 1         | 0.8%    |
| Hewlett-Packard          | 1         | 0.8%    |
| Broadcom Limited         | 1         | 0.8%    |
| Apple                    | 1         | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 52        | 41.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 5.56%   |
| Nvidia MCP79 Ethernet                                                          | 7         | 5.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 3.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 3.97%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 3.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 2.38%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 2.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.59%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.59%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.59%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 1.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.79%   |
| OPPO RMX3381                                                                   | 1         | 0.79%   |
| Motorola PCS Moto G (4)                                                        | 1         | 0.79%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.79%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.79%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.79%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.79%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 1         | 0.79%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.79%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.79%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 0.79%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.79%   |
| Apple T2 Controller                                                            | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 53.25%  |
| Ethernet | 115       | 46.75%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 126       | 53.62%  |
| Ethernet | 109       | 46.38%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 83        | 55.33%  |
| 1     | 63        | 42%     |
| 3     | 3         | 2%      |
| 4     | 1         | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 66.23%  |
| Yes  | 51        | 33.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 45.9%   |
| Apple                           | 21        | 17.21%  |
| Realtek Semiconductor           | 12        | 9.84%   |
| Cambridge Silicon Radio         | 8         | 6.56%   |
| Qualcomm Atheros Communications | 7         | 5.74%   |
| IMC Networks                    | 4         | 3.28%   |
| Lite-On Technology              | 3         | 2.46%   |
| Foxconn / Hon Hai               | 3         | 2.46%   |
| Broadcom                        | 3         | 2.46%   |
| Realtek                         | 1         | 0.82%   |
| Ralink                          | 1         | 0.82%   |
| Marvell Semiconductor           | 1         | 0.82%   |
| Hewlett-Packard                 | 1         | 0.82%   |
| ASUSTek Computer                | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 30        | 24.59%  |
| Intel Bluetooth wireless interface                                                  | 11        | 9.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 9.02%   |
| Apple Bluetooth Host Controller                                                     | 10        | 8.2%    |
| Realtek Bluetooth Radio                                                             | 8         | 6.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 6.56%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 4.1%    |
| Apple Bluetooth HCI                                                                 | 4         | 3.28%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 2.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.64%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.82%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.82%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.82%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.82%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.82%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.82%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.82%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.82%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.82%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.82%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.82%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.82%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.82%   |
| ASUS BCM20702A0                                                                     | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 106       | 54.36%  |
| AMD                     | 41        | 21.03%  |
| Nvidia                  | 32        | 16.41%  |
| C-Media Electronics     | 5         | 2.56%   |
| Logitech                | 2         | 1.03%   |
| Creative Labs           | 2         | 1.03%   |
| Texas Instruments       | 1         | 0.51%   |
| Realtek Semiconductor   | 1         | 0.51%   |
| Razer USA               | 1         | 0.51%   |
| Focusrite-Novation      | 1         | 0.51%   |
| CalDigit                | 1         | 0.51%   |
| BEHRINGER International | 1         | 0.51%   |
| Apple                   | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 17        | 7.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 6.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 4.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.83%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 2.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 2.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.13%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.13%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 2.13%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.28%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.28%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.28%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.85%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.85%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.85%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.85%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.85%   |
| AMD FCH Azalia Controller                                                                         | 2         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.85%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.43%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.43%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]                        | 1         | 0.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.43%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Logitech G733 Gaming Headset                                                                      | 1         | 0.43%   |
| Logitech 960 Headset                                                                              | 1         | 0.43%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.43%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.43%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 15        | 34.88%  |
| SK Hynix            | 7         | 16.28%  |
| Micron Technology   | 7         | 16.28%  |
| Unknown             | 2         | 4.65%   |
| Kingston            | 2         | 4.65%   |
| G.Skill             | 2         | 4.65%   |
| Unknown (ABCD)      | 1         | 2.33%   |
| Ramaxel Technology  | 1         | 2.33%   |
| PNY                 | 1         | 2.33%   |
| Patriot             | 1         | 2.33%   |
| Hewlett-Packard     | 1         | 2.33%   |
| GSkill              | 1         | 2.33%   |
| Crucial             | 1         | 2.33%   |
| Corsair             | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 4.26%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 2         | 4.26%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 4.26%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 4.26%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 2.13%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                     | 1         | 2.13%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR3 2400MT/s | 1         | 2.13%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.13%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 2.13%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 2.13%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 2.13%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 2.13%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                     | 1         | 2.13%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 2.13%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 2.13%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.13%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 2.13%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.13%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 1         | 2.13%   |
| Samsung RAM K4EBE304ED-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s  | 1         | 2.13%   |
| Samsung RAM K3QF4F40BM-AGCF 4096MB Row Of Chips LPDDR3 1867MT/s  | 1         | 2.13%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s        | 1         | 2.13%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s           | 1         | 2.13%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s              | 1         | 2.13%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 1         | 2.13%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 1         | 2.13%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.13%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.13%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s         | 1         | 2.13%   |
| Kingston RAM 9905625-030.A00G 8192MB DIMM DDR4 2133MT/s          | 1         | 2.13%   |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s         | 1         | 2.13%   |
| HP RAM 647650-071 8192MB DIMM DDR3 1333MT/s                      | 1         | 2.13%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s           | 1         | 2.13%   |
| G.Skill RAM F4-2666C18-16GRS 16384MB SODIMM DDR4 2667MT/s        | 1         | 2.13%   |
| G.Skill RAM F3-1600C11-8GSQ 8192MB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| G.Skill RAM F3-1600C11-8GSL 8192MB SODIMM DDR3 1600MT/s          | 1         | 2.13%   |
| Crucial RAM CB8GS2400.C8D 8192MB SODIMM DDR4 2400MT/s            | 1         | 2.13%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s             | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 53.66%  |
| DDR3   | 13        | 31.71%  |
| LPDDR4 | 3         | 7.32%   |
| LPDDR3 | 3         | 7.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 68.29%  |
| DIMM         | 8         | 19.51%  |
| Row Of Chips | 4         | 9.76%   |
| Chip         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 22        | 51.16%  |
| 4096  | 12        | 27.91%  |
| 16384 | 4         | 9.3%    |
| 2048  | 4         | 9.3%    |
| 32768 | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 8         | 19.05%  |
| 2667    | 8         | 19.05%  |
| 1600    | 8         | 19.05%  |
| 2133    | 4         | 9.52%   |
| 4267    | 2         | 4.76%   |
| 2400    | 2         | 4.76%   |
| 1867    | 2         | 4.76%   |
| 1333    | 2         | 4.76%   |
| 3266    | 1         | 2.38%   |
| 2800    | 1         | 2.38%   |
| 2666    | 1         | 2.38%   |
| 1334    | 1         | 2.38%   |
| 1066    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Canon PIXMA MG3600 Series | 1         | 50%     |
| Canon PIXMA MG2500 Series | 1         | 50%     |

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
| Chicony Electronics                    | 18        | 16.22%  |
| Apple                                  | 17        | 15.32%  |
| IMC Networks                           | 16        | 14.41%  |
| Acer                                   | 10        | 9.01%   |
| Realtek Semiconductor                  | 9         | 8.11%   |
| Microdia                               | 7         | 6.31%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 6.31%   |
| Quanta                                 | 4         | 3.6%    |
| Suyin                                  | 3         | 2.7%    |
| Logitech                               | 3         | 2.7%    |
| Alcor Micro                            | 3         | 2.7%    |
| Syntek                                 | 2         | 1.8%    |
| Luxvisions Innotech Limited            | 2         | 1.8%    |
| Y Media                                | 1         | 0.9%    |
| Sunplus Innovation Technology          | 1         | 0.9%    |
| Sony                                   | 1         | 0.9%    |
| Silicon Motion                         | 1         | 0.9%    |
| Ricoh                                  | 1         | 0.9%    |
| Microsoft                              | 1         | 0.9%    |
| Lite-On Technology                     | 1         | 0.9%    |
| kingcome                               | 1         | 0.9%    |
| Generalplus Technology                 | 1         | 0.9%    |
| Foxconn / Hon Hai                      | 1         | 0.9%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 8         | 7.02%   |
| IMC Networks Integrated Camera                                             | 6         | 5.26%   |
| Chicony Integrated Camera                                                  | 6         | 5.26%   |
| Apple FaceTime HD Camera                                                   | 5         | 4.39%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 4         | 3.51%   |
| Acer Lenovo EasyCamera                                                     | 4         | 3.51%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 2.63%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.63%   |
| Chicony HD WebCam                                                          | 3         | 2.63%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 2.63%   |
| Syntek Integrated Camera                                                   | 2         | 1.75%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.75%   |
| Realtek USB Camera                                                         | 2         | 1.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 1.75%   |
| IMC Networks EasyCamera                                                    | 2         | 1.75%   |
| Chicony USB 2.0 Camera                                                     | 2         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 2         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 2         | 1.75%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 1.75%   |
| Acer EasyCamera                                                            | 2         | 1.75%   |
| Y Media USB Camera                                                         | 1         | 0.88%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.88%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.88%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.88%   |
| Sunplus HP Universal Camera                                                | 1         | 0.88%   |
| Sony CEVCECM                                                               | 1         | 0.88%   |
| Silicon Motion WebCam SC-13HDL11624N                                       | 1         | 0.88%   |
| Ricoh Dell Laptop Integrated Webcam                                        | 1         | 0.88%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 0.88%   |
| Realtek Integrated Webcam                                                  | 1         | 0.88%   |
| Quanta VGA WebCam                                                          | 1         | 0.88%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 0.88%   |
| Quanta hm1091_techfront                                                    | 1         | 0.88%   |
| Quanta HD User Facing                                                      | 1         | 0.88%   |
| Microsoft LifeCam VX-800                                                   | 1         | 0.88%   |
| Microdia Webcam Vitade AF                                                  | 1         | 0.88%   |
| Microdia Sonix USB 2.0 Camera                                              | 1         | 0.88%   |
| Microdia OV5648                                                            | 1         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 0.88%   |
| Microdia HUE HD Pro camera                                                 | 1         | 0.88%   |
| Logitech Webcam Pro 9000                                                   | 1         | 0.88%   |
| Logitech BRIO 4K Stream Edition                                            | 1         | 0.88%   |
| Logitech B525 HD Webcam                                                    | 1         | 0.88%   |
| Lite-On HP HD Webcam                                                       | 1         | 0.88%   |
| kingcome HD Camera                                                         | 1         | 0.88%   |
| IMC Networks USB2.0-Camera                                                 | 1         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 0.88%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 0.88%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.88%   |
| Generalplus GENERAL WEBCAM                                                 | 1         | 0.88%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 0.88%   |
| Chicony USB2.0 Camera                                                      | 1         | 0.88%   |
| Chicony thinkpad t430s camera                                              | 1         | 0.88%   |
| Chicony Integrated IR Camera                                               | 1         | 0.88%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 0.88%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 0.88%   |
| Chicony EasyCamera                                                         | 1         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 35.71%  |
| Validity Sensors           | 4         | 28.57%  |
| LighTuning Technology      | 3         | 21.43%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 14.29%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 2         | 14.29%  |
| Validity Sensors VFS491                           | 1         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 7.14%   |
| Unknown                                           | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 122       | 81.33%  |
| 1     | 26        | 17.33%  |
| 2     | 2         | 1.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 46.67%  |
| Net/wireless          | 4         | 13.33%  |
| Multimedia controller | 4         | 13.33%  |
| Chipcard              | 3         | 10%     |
| Graphics card         | 2         | 6.67%   |
| Camera                | 2         | 6.67%   |
| Bluetooth             | 1         | 3.33%   |

