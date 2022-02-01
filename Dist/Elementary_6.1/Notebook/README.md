Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| HP            | ProBook 4540s               | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Dell          | Vostro 15 3515              | [a0fdaf761c](https://linux-hardware.org/?probe=a0fdaf761c) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [f7c8c966dc](https://linux-hardware.org/?probe=f7c8c966dc) | Jan 17, 2022 |
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [fae944592d](https://linux-hardware.org/?probe=fae944592d) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Star Labs     | StarBook                    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| Wortmann      | 1220729_1470271             | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| Dell          | Latitude 3580               | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| Dell          | Inspiron 5555               | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Lenovo        | V14-ADA 82C6                | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.11.0-43-generic      | 50        | 48.08%  |
| 5.13.0-27-generic      | 21        | 20.19%  |
| 5.11.0-44-generic      | 12        | 11.54%  |
| 5.11.0-46-generic      | 10        | 9.62%   |
| 5.11.0-41-generic      | 3         | 2.88%   |
| 5.8.0-50-generic       | 1         | 0.96%   |
| 5.15.3-xanmod1         | 1         | 0.96%   |
| 5.15.13-xanmod1        | 1         | 0.96%   |
| 5.15.12-xanmod1-tt     | 1         | 0.96%   |
| 5.15.11-t2-big-sur     | 1         | 0.96%   |
| 5.14.10-051410-generic | 1         | 0.96%   |
| 5.14.0-1011-oem        | 1         | 0.96%   |
| 5.11.0-40-generic      | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 76        | 73.08%  |
| 5.13.0  | 21        | 20.19%  |
| 5.8.0   | 1         | 0.96%   |
| 5.15.3  | 1         | 0.96%   |
| 5.15.13 | 1         | 0.96%   |
| 5.15.12 | 1         | 0.96%   |
| 5.15.11 | 1         | 0.96%   |
| 5.14.10 | 1         | 0.96%   |
| 5.14.0  | 1         | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 76        | 73.08%  |
| 5.13    | 21        | 20.19%  |
| 5.15    | 4         | 3.85%   |
| 5.14    | 2         | 1.92%   |
| 5.8     | 1         | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 104       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 104       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 69.23%  |
| LightDM | 31        | 29.81%  |
| GDM     | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 52        | 50%     |
| de_DE | 15        | 14.42%  |
| en_GB | 9         | 8.65%   |
| pt_BR | 6         | 5.77%   |
| ru_RU | 4         | 3.85%   |
| pl_PL | 3         | 2.88%   |
| pt_PT | 2         | 1.92%   |
| nl_NL | 2         | 1.92%   |
| it_IT | 2         | 1.92%   |
| fr_FR | 2         | 1.92%   |
| es_ES | 2         | 1.92%   |
| tr_TR | 1         | 0.96%   |
| hu_HU | 1         | 0.96%   |
| en_CA | 1         | 0.96%   |
| en_AU | 1         | 0.96%   |
| bg_BG | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 79        | 75.96%  |
| BIOS | 25        | 24.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 96.15%  |
| Btrfs   | 3         | 2.88%   |
| Overlay | 1         | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 76        | 73.08%  |
| GPT     | 25        | 24.04%  |
| MBR     | 3         | 2.88%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 95.19%  |
| Yes       | 5         | 4.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 89.42%  |
| Yes       | 11        | 10.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 25%     |
| Apple               | 17        | 16.35%  |
| Hewlett-Packard     | 11        | 10.58%  |
| Dell                | 11        | 10.58%  |
| ASUSTek Computer    | 11        | 10.58%  |
| Acer                | 6         | 5.77%   |
| HUAWEI              | 5         | 4.81%   |
| Star Labs           | 2         | 1.92%   |
| Sony                | 2         | 1.92%   |
| Notebook            | 2         | 1.92%   |
| MSI                 | 2         | 1.92%   |
| Monster             | 2         | 1.92%   |
| Wortmann AG         | 1         | 0.96%   |
| Timi                | 1         | 0.96%   |
| Teclast             | 1         | 0.96%   |
| Samsung Electronics | 1         | 0.96%   |
| Razer               | 1         | 0.96%   |
| LG Electronics      | 1         | 0.96%   |
| Fujitsu             | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HUAWEI MACHD-WXX9                          | 2         | 1.92%   |
| Apple MacBookPro8,2                        | 2         | 1.92%   |
| Apple MacBookPro5,5                        | 2         | 1.92%   |
| Apple MacBook5,1                           | 2         | 1.92%   |
| Wortmann AG 1220729_1470271                | 1         | 0.96%   |
| Timi TM1613                                | 1         | 0.96%   |
| Teclast F7                                 | 1         | 0.96%   |
| Star Labs StarBook                         | 1         | 0.96%   |
| Star Labs LabTop                           | 1         | 0.96%   |
| Sony VPCEA3S1E                             | 1         | 0.96%   |
| Sony SVE14A390X                            | 1         | 0.96%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D | 1         | 0.96%   |
| Razer Blade Stealth                        | 1         | 0.96%   |
| Notebook W65_67SJ                          | 1         | 0.96%   |
| Notebook P65xHP                            | 1         | 0.96%   |
| MSI PS63 Modern 8RD                        | 1         | 0.96%   |
| MSI GF63 Thin 9SCSR                        | 1         | 0.96%   |
| Monster MARKUT M7 V1.x                     | 1         | 0.96%   |
| Monster ABRA A5 V13.2                      | 1         | 0.96%   |
| LG A410-G.BC51P1                           | 1         | 0.96%   |
| Lenovo Yoga 300-11IBR 80M1                 | 1         | 0.96%   |
| Lenovo ThinkPad X270 W10DG 20K5S2VL00      | 1         | 0.96%   |
| Lenovo ThinkPad X13 Gen 1 20UFS00G00       | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1L200   | 1         | 0.96%   |
| Lenovo ThinkPad W541 20EGS1VV00            | 1         | 0.96%   |
| Lenovo ThinkPad T470 W10DG 20JNS08H00      | 1         | 0.96%   |
| Lenovo ThinkPad T470 20JNS08H00            | 1         | 0.96%   |
| Lenovo ThinkPad T430 23501M2               | 1         | 0.96%   |
| Lenovo ThinkPad T430 2347JC2               | 1         | 0.96%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00E00      | 1         | 0.96%   |
| Lenovo ThinkPad E495 20NE001RTX            | 1         | 0.96%   |
| Lenovo ThinkPad E14 20RAS0EQ00             | 1         | 0.96%   |
| Lenovo Legion Y530-15ICH 81GT              | 1         | 0.96%   |
| Lenovo Legion Y530-15ICH 81FV              | 1         | 0.96%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG       | 1         | 0.96%   |
| Lenovo IdeaPad 5 14ARE05 81YM              | 1         | 0.96%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.96%   |
| Lenovo IdeaPad 320-14AST 80XU              | 1         | 0.96%   |
| Lenovo IdeaPad 310-15ISK 80SM              | 1         | 0.96%   |
| Lenovo IdeaPad 310-15IKB 80TV              | 1         | 0.96%   |
| Lenovo IdeaPad 130-15AST 81H5              | 1         | 0.96%   |
| Lenovo G550 2958                           | 1         | 0.96%   |
| Lenovo G550 20023                          | 1         | 0.96%   |
| Lenovo G50-80 80E5                         | 1         | 0.96%   |
| Lenovo Flex 2-14D 20376                    | 1         | 0.96%   |
| HUAWEI NBLK-WAX9X                          | 1         | 0.96%   |
| HUAWEI MACHC-WAX9                          | 1         | 0.96%   |
| HUAWEI KPL-W0X                             | 1         | 0.96%   |
| HP ProBook 4540s                           | 1         | 0.96%   |
| HP ProBook 4430s                           | 1         | 0.96%   |
| HP Pavilion Laptop 15-eh0xxx               | 1         | 0.96%   |
| HP Pavilion Laptop 15-cs0xxx               | 1         | 0.96%   |
| HP Laptop 15s-eq1xxx                       | 1         | 0.96%   |
| HP Laptop 15-ef2xxx                        | 1         | 0.96%   |
| HP EliteBook Folio 1040 G2                 | 1         | 0.96%   |
| HP EliteBook 850 G2                        | 1         | 0.96%   |
| HP EliteBook 8460p                         | 1         | 0.96%   |
| HP EliteBook 840 G1                        | 1         | 0.96%   |
| HP Elite x2 1012 G1                        | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 11.54%  |
| Lenovo IdeaPad      | 7         | 6.73%   |
| HP EliteBook        | 4         | 3.85%   |
| Dell Precision      | 3         | 2.88%   |
| Dell Inspiron       | 3         | 2.88%   |
| ASUS VivoBook       | 3         | 2.88%   |
| Apple MacBookPro8   | 3         | 2.88%   |
| Apple MacBookPro5   | 3         | 2.88%   |
| Apple MacBook5      | 3         | 2.88%   |
| Acer Aspire         | 3         | 2.88%   |
| Lenovo Legion       | 2         | 1.92%   |
| Lenovo G550         | 2         | 1.92%   |
| HUAWEI MACHD-WXX9   | 2         | 1.92%   |
| HP ProBook          | 2         | 1.92%   |
| HP Pavilion         | 2         | 1.92%   |
| HP Laptop           | 2         | 1.92%   |
| Dell Vostro         | 2         | 1.92%   |
| Dell Latitude       | 2         | 1.92%   |
| ASUS ZenBook        | 2         | 1.92%   |
| Apple MacBookPro9   | 2         | 1.92%   |
| Acer Swift          | 2         | 1.92%   |
| Wortmann AG 1220729 | 1         | 0.96%   |
| Timi TM1613         | 1         | 0.96%   |
| Teclast F7          | 1         | 0.96%   |
| Star Labs StarBook  | 1         | 0.96%   |
| Star Labs LabTop    | 1         | 0.96%   |
| Sony VPCEA3S1E      | 1         | 0.96%   |
| Sony SVE14A390X     | 1         | 0.96%   |
| Samsung 900X3C      | 1         | 0.96%   |
| Razer Blade         | 1         | 0.96%   |
| Notebook W65        | 1         | 0.96%   |
| Notebook P65xHP     | 1         | 0.96%   |
| MSI PS63            | 1         | 0.96%   |
| MSI GF63            | 1         | 0.96%   |
| Monster MARKUT      | 1         | 0.96%   |
| Monster ABRA        | 1         | 0.96%   |
| LG A410-G.BC51P1    | 1         | 0.96%   |
| Lenovo Yoga         | 1         | 0.96%   |
| Lenovo G50-80       | 1         | 0.96%   |
| Lenovo Flex         | 1         | 0.96%   |
| HUAWEI NBLK-WAX9X   | 1         | 0.96%   |
| HUAWEI MACHC-WAX9   | 1         | 0.96%   |
| HUAWEI KPL-W0X      | 1         | 0.96%   |
| HP Elite            | 1         | 0.96%   |
| Fujitsu LIFEBOOK    | 1         | 0.96%   |
| Dell XPS            | 1         | 0.96%   |
| ASUS X555UB         | 1         | 0.96%   |
| ASUS X555LN         | 1         | 0.96%   |
| ASUS X550CA         | 1         | 0.96%   |
| ASUS X541NA         | 1         | 0.96%   |
| ASUS UX410UAK       | 1         | 0.96%   |
| ASUS E202SA         | 1         | 0.96%   |
| Apple MacBookPro16  | 1         | 0.96%   |
| Apple MacBookPro11  | 1         | 0.96%   |
| Apple MacBookAir7   | 1         | 0.96%   |
| Apple MacBookAir6   | 1         | 0.96%   |
| Apple MacBookAir1   | 1         | 0.96%   |
| Apple MacBook4      | 1         | 0.96%   |
| Acer TravelMate     | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 14        | 13.46%  |
| 2018 | 12        | 11.54%  |
| 2015 | 11        | 10.58%  |
| 2021 | 9         | 8.65%   |
| 2014 | 8         | 7.69%   |
| 2019 | 7         | 6.73%   |
| 2016 | 7         | 6.73%   |
| 2012 | 7         | 6.73%   |
| 2009 | 7         | 6.73%   |
| 2011 | 6         | 5.77%   |
| 2017 | 5         | 4.81%   |
| 2013 | 4         | 3.85%   |
| 2010 | 4         | 3.85%   |
| 2008 | 3         | 2.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 87        | 83.65%  |
| Enabled  | 17        | 16.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 102       | 98.08%  |
| Yes  | 2         | 1.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 46        | 44.23%  |
| 16.01-24.0  | 20        | 19.23%  |
| 3.01-4.0    | 16        | 15.38%  |
| 8.01-16.0   | 13        | 12.5%   |
| 1.01-2.0    | 4         | 3.85%   |
| 32.01-64.0  | 3         | 2.88%   |
| 24.01-32.0  | 1         | 0.96%   |
| 64.01-256.0 | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 34        | 32.69%  |
| 2.01-3.0  | 31        | 29.81%  |
| 3.01-4.0  | 16        | 15.38%  |
| 4.01-8.0  | 11        | 10.58%  |
| 8.01-16.0 | 6         | 5.77%   |
| 0.51-1.0  | 6         | 5.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 73.08%  |
| 2      | 24        | 23.08%  |
| 3      | 3         | 2.88%   |
| 5      | 1         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 67.31%  |
| Yes       | 34        | 32.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 71.15%  |
| No        | 30        | 28.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 91.35%  |
| No        | 9         | 8.65%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 14        | 13.46%  |
| USA         | 11        | 10.58%  |
| India       | 9         | 8.65%   |
| Brazil      | 9         | 8.65%   |
| Turkey      | 6         | 5.77%   |
| Poland      | 5         | 4.81%   |
| UK          | 4         | 3.85%   |
| Russia      | 4         | 3.85%   |
| Italy       | 4         | 3.85%   |
| Indonesia   | 3         | 2.88%   |
| Canada      | 3         | 2.88%   |
| Australia   | 3         | 2.88%   |
| Romania     | 2         | 1.92%   |
| Portugal    | 2         | 1.92%   |
| Mexico      | 2         | 1.92%   |
| France      | 2         | 1.92%   |
| Belgium     | 2         | 1.92%   |
| Belarus     | 2         | 1.92%   |
| Ukraine     | 1         | 0.96%   |
| Switzerland | 1         | 0.96%   |
| Sweden      | 1         | 0.96%   |
| Pakistan    | 1         | 0.96%   |
| New Zealand | 1         | 0.96%   |
| Netherlands | 1         | 0.96%   |
| Mozambique  | 1         | 0.96%   |
| Kenya       | 1         | 0.96%   |
| Japan       | 1         | 0.96%   |
| Hungary     | 1         | 0.96%   |
| Guyana      | 1         | 0.96%   |
| Greece      | 1         | 0.96%   |
| Czechia     | 1         | 0.96%   |
| Colombia    | 1         | 0.96%   |
| Chile       | 1         | 0.96%   |
| Bulgaria    | 1         | 0.96%   |
| Austria     | 1         | 0.96%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Sydney                 | 3         | 2.88%   |
| Ankara                 | 3         | 2.88%   |
| Munich                 | 2         | 1.92%   |
| Minsk                  | 2         | 1.92%   |
| Antalya                | 2         | 1.92%   |
| Wroclaw                | 1         | 0.96%   |
| Wriedel                | 1         | 0.96%   |
| Wellington             | 1         | 0.96%   |
| Warsaw                 | 1         | 0.96%   |
| Vit??ria da Conquista  | 1         | 0.96%   |
| Vinnytsia              | 1         | 0.96%   |
| Vila Nova de Gaia      | 1         | 0.96%   |
| Vienna                 | 1         | 0.96%   |
| Tongeren               | 1         | 0.96%   |
| Tecuci                 | 1         | 0.96%   |
| Surrey                 | 1         | 0.96%   |
| Surabaya               | 1         | 0.96%   |
| Soliera                | 1         | 0.96%   |
| Solapur                | 1         | 0.96%   |
| Siersburg              | 1         | 0.96%   |
| Shetland Islands       | 1         | 0.96%   |
| S??o Paulo             | 1         | 0.96%   |
| S??o Bernardo do Campo | 1         | 0.96%   |
| Sazava                 | 1         | 0.96%   |
| Santo Andr?©           | 1         | 0.96%   |
| San Antonio            | 1         | 0.96%   |
| Saltsjoe-Boo           | 1         | 0.96%   |
| Rostock                | 1         | 0.96%   |
| Rome                   | 1         | 0.96%   |
| Providencia            | 1         | 0.96%   |
| Porto                  | 1         | 0.96%   |
| Patna                  | 1         | 0.96%   |
| Osasco                 | 1         | 0.96%   |
| Osaka                  | 1         | 0.96%   |
| Orenburg               | 1         | 0.96%   |
| Oceanside              | 1         | 0.96%   |
| Novosibirsk            | 1         | 0.96%   |
| Nairobi                | 1         | 0.96%   |
| Mumbai                 | 1         | 0.96%   |
| Moscow                 | 1         | 0.96%   |
| Montm?©dy              | 1         | 0.96%   |
| Mississauga            | 1         | 0.96%   |
| Minerva                | 1         | 0.96%   |
| Mexico City            | 1         | 0.96%   |
| Marshfield             | 1         | 0.96%   |
| Mahemdavad             | 1         | 0.96%   |
| Mage                   | 1         | 0.96%   |
| Lyubertsy              | 1         | 0.96%   |
| Lydney                 | 1         | 0.96%   |
| Leduc                  | 1         | 0.96%   |
| Le Grand-Saconnex      | 1         | 0.96%   |
| Krakow                 | 1         | 0.96%   |
| Kobern-Gondorf         | 1         | 0.96%   |
| Kayseri                | 1         | 0.96%   |
| Kaufbeuren             | 1         | 0.96%   |
| Jember                 | 1         | 0.96%   |
| Jakarta                | 1         | 0.96%   |
| Itaquaquecetuba        | 1         | 0.96%   |
| Islamabad              | 1         | 0.96%   |
| Idaho Falls            | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 32     | 20.45%  |
| WDC                 | 13        | 13     | 9.85%   |
| Seagate             | 12        | 12     | 9.09%   |
| SanDisk             | 12        | 12     | 9.09%   |
| Kingston            | 11        | 12     | 8.33%   |
| Crucial             | 7         | 7      | 5.3%    |
| Unknown             | 5         | 5      | 3.79%   |
| SK Hynix            | 4         | 4      | 3.03%   |
| Intel               | 4         | 5      | 3.03%   |
| Hitachi             | 4         | 4      | 3.03%   |
| HGST                | 4         | 4      | 3.03%   |
| Apple               | 4         | 4      | 3.03%   |
| Unknown             | 4         | 4      | 3.03%   |
| Toshiba             | 3         | 3      | 2.27%   |
| KIOXIA              | 3         | 3      | 2.27%   |
| Micron Technology   | 2         | 2      | 1.52%   |
| A-DATA Technology   | 2         | 2      | 1.52%   |
| Transcend           | 1         | 1      | 0.76%   |
| Teclast             | 1         | 1      | 0.76%   |
| Star Drive          | 1         | 1      | 0.76%   |
| Star                | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| Silicon Motion      | 1         | 1      | 0.76%   |
| SABRENT             | 1         | 1      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| Fujitsu             | 1         | 1      | 0.76%   |
| China               | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 5         | 3.65%   |
| Samsung NVMe SSD Drive 512GB              | 4         | 2.92%   |
| Unknown                                   | 4         | 2.92%   |
| Samsung SSD 850 EVO 250GB                 | 3         | 2.19%   |
| Samsung NVMe SSD Drive 256GB              | 3         | 2.19%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 2.19%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 2         | 1.46%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.46%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD       | 2         | 1.46%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD       | 2         | 1.46%   |
| Samsung SSD 850 EVO 120GB                 | 2         | 1.46%   |
| Kingston SA400S37120G 120GB SSD           | 2         | 1.46%   |
| Kingston NVMe SSD Drive 500GB             | 2         | 1.46%   |
| Intel NVMe SSD Drive 512GB                | 2         | 1.46%   |
| HGST HTS545050A7E380 500GB                | 2         | 1.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 0.73%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 1         | 0.73%   |
| WDC WD7500BPVT-22A1YT0 752GB              | 1         | 0.73%   |
| WDC WD5000LPVX-80V0TT0 500GB              | 1         | 0.73%   |
| WDC WD5000BPVT-22HXZT1 500GB              | 1         | 0.73%   |
| WDC WD2500BEVS-22UST0 250GB               | 1         | 0.73%   |
| WDC WD20SPZX-22UA7T0 2TB                  | 1         | 0.73%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 0.73%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 1         | 0.73%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB      | 1         | 0.73%   |
| WDC PC SN520 SDAPNUW-512G                 | 1         | 0.73%   |
| Unknown USD00  16GB                       | 1         | 0.73%   |
| Unknown SL128  128GB                      | 1         | 0.73%   |
| Unknown SC128  128GB                      | 1         | 0.73%   |
| Unknown MMC Card  128GB                   | 1         | 0.73%   |
| Unknown GD2S5  128GB                      | 1         | 0.73%   |
| Transcend TS512GMTS430S 512GB SSD         | 1         | 0.73%   |
| Toshiba NVMe SSD Drive 512GB              | 1         | 0.73%   |
| Teclast 128GB NS550-2242 SSD              | 1         | 0.73%   |
| Star Drive SATA SSD 960GB                 | 1         | 0.73%   |
| Star Drive PCIe SSD 480GB                 | 1         | 0.73%   |
| SPCC Solid State Disk 256GB               | 1         | 0.73%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 0.73%   |
| SK Hynix NVMe SSD Drive 512GB             | 1         | 0.73%   |
| SK Hynix NVMe SSD Drive 256GB             | 1         | 0.73%   |
| SK Hynix HFM128GDHTNG-8510B 128GB         | 1         | 0.73%   |
| Silicon Motion NVMe SSD Drive 120GB       | 1         | 0.73%   |
| Seagate ST980313AS 80GB                   | 1         | 0.73%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.73%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 0.73%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 0.73%   |
| Seagate ST500LM030-2E717D 500GB           | 1         | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.73%   |
| Seagate Expansion Desk 8TB                | 1         | 0.73%   |
| SanDisk SD9SN8W256G1102 256GB SSD         | 1         | 0.73%   |
| SanDisk SD9SN8W256G1027 256GB SSD         | 1         | 0.73%   |
| SanDisk SD8SNAT128G1002 128GB SSD         | 1         | 0.73%   |
| SanDisk SD8SBAT128G1002 128GB SSD         | 1         | 0.73%   |
| Sandisk NVMe SSD Drive 2TB                | 1         | 0.73%   |
| Sandisk NVMe SSD Drive 250GB              | 1         | 0.73%   |
| Sandisk NVMe SSD Drive 1TB                | 1         | 0.73%   |
| SanDisk Extreme SSD 500GB                 | 1         | 0.73%   |
| Samsung SSD SM841 mSATA 512GB             | 1         | 0.73%   |
| Samsung SSD 980 PRO 2TB                   | 1         | 0.73%   |
| Samsung SSD 950 PRO 512GB                 | 1         | 0.73%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 12     | 36.36%  |
| WDC     | 9         | 9      | 27.27%  |
| Hitachi | 4         | 4      | 12.12%  |
| HGST    | 4         | 4      | 12.12%  |
| Toshiba | 2         | 2      | 6.06%   |
| Fujitsu | 1         | 1      | 3.03%   |
| Apple   | 1         | 1      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 18     | 28.07%  |
| SanDisk             | 9         | 9      | 15.79%  |
| Kingston            | 8         | 8      | 14.04%  |
| Crucial             | 7         | 7      | 12.28%  |
| WDC                 | 2         | 2      | 3.51%   |
| Micron Technology   | 2         | 2      | 3.51%   |
| Apple               | 2         | 2      | 3.51%   |
| A-DATA Technology   | 2         | 2      | 3.51%   |
| Transcend           | 1         | 1      | 1.75%   |
| Teclast             | 1         | 1      | 1.75%   |
| Star                | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| SABRENT             | 1         | 1      | 1.75%   |
| LITEON              | 1         | 1      | 1.75%   |
| KingSpec            | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| Unknown             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 52        | 59     | 40.63%  |
| NVMe    | 35        | 39     | 27.34%  |
| HDD     | 33        | 33     | 25.78%  |
| MMC     | 6         | 6      | 4.69%   |
| Unknown | 2         | 2      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 89     | 62.81%  |
| NVMe | 35        | 39     | 28.93%  |
| MMC  | 6         | 6      | 4.96%   |
| SAS  | 4         | 5      | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 64     | 70.37%  |
| 0.51-1.0   | 19        | 20     | 23.46%  |
| 1.01-2.0   | 4         | 7      | 4.94%   |
| 4.01-10.0  | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 46        | 44.23%  |
| 251-500        | 24        | 23.08%  |
| 501-1000       | 13        | 12.5%   |
| 51-100         | 9         | 8.65%   |
| 1001-2000      | 8         | 7.69%   |
| 21-50          | 3         | 2.88%   |
| More than 3000 | 1         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 43        | 41.35%  |
| 21-50     | 30        | 28.85%  |
| 101-250   | 10        | 9.62%   |
| 51-100    | 10        | 9.62%   |
| 251-500   | 6         | 5.77%   |
| 501-1000  | 3         | 2.88%   |
| 2001-3000 | 1         | 0.96%   |
| 1001-2000 | 1         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB          | 1         | 1      | 33.33%  |
| Seagate ST500LM030-2E717D 500GB | 1         | 1      | 33.33%  |
| Crucial CT512M550SSD3 512GB     | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Crucial | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 66.67%  |
| SSD  | 1         | 1      | 33.33%  |

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
| Detected | 86        | 103    | 74.78%  |
| Works    | 26        | 33     | 22.61%  |
| Malfunc  | 3         | 3      | 2.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 70        | 59.83%  |
| Samsung Electronics          | 13        | 11.11%  |
| AMD                          | 9         | 7.69%   |
| Nvidia                       | 6         | 5.13%   |
| Sandisk                      | 5         | 4.27%   |
| SK Hynix                     | 4         | 3.42%   |
| Kingston Technology Company  | 4         | 3.42%   |
| KIOXIA                       | 2         | 1.71%   |
| Toshiba America Info Systems | 1         | 0.85%   |
| Silicon Motion               | 1         | 0.85%   |
| Phison Electronics           | 1         | 0.85%   |
| Apple                        | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 9.6%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 7.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 8         | 6.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 6.4%    |
| Nvidia MCP79 AHCI Controller                                                     | 6         | 4.8%    |
| Samsung NVMe SSD Controller 980                                                  | 5         | 4%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 3.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 3.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 3.2%    |
| Intel SSD 660P Series                                                            | 3         | 2.4%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 3         | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.4%    |
| SK Hynix BC511                                                                   | 2         | 1.6%    |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.6%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.6%    |
| KIOXIA Non-Volatile memory controller                                            | 2         | 1.6%    |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 1.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.8%    |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.8%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.8%    |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.8%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.8%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.8%    |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.8%    |
| Samsung Electronics SATA controller                                              | 1         | 0.8%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.8%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.8%    |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.8%    |
| Kingston Company KC2000 NVMe SSD                                                 | 1         | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.8%    |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.8%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                            | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.8%    |
| Apple ANS2 NVMe Controller                                                       | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 78        | 64.46%  |
| NVMe | 34        | 28.1%   |
| RAID | 5         | 4.13%   |
| IDE  | 4         | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 82.69%  |
| AMD    | 18        | 17.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 3.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.92%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.92%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.92%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.92%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.92%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.96%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.96%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.96%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.96%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.96%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.96%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 1         | 0.96%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.96%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.96%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.96%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i7-2675QM CPU @ 2.20GHz            | 1         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.96%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 1         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.96%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.96%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 1         | 0.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 1         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.96%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.96%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 1         | 0.96%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.96%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 0.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 1         | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 0.96%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28        | 26.92%  |
| Intel Core i7           | 27        | 25.96%  |
| Intel Core 2 Duo        | 9         | 8.65%   |
| Other                   | 8         | 7.69%   |
| Intel Core i3           | 8         | 7.69%   |
| AMD Ryzen 5             | 8         | 7.69%   |
| Intel Celeron           | 3         | 2.88%   |
| Intel Pentium           | 2         | 1.92%   |
| AMD Ryzen 7 PRO         | 2         | 1.92%   |
| AMD Ryzen 7             | 2         | 1.92%   |
| AMD Ryzen 3             | 2         | 1.92%   |
| Intel Pentium Dual-Core | 1         | 0.96%   |
| Intel Core m5           | 1         | 0.96%   |
| Intel Celeron Dual-Core | 1         | 0.96%   |
| AMD A8                  | 1         | 0.96%   |
| AMD A6                  | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 52        | 50%     |
| 4      | 39        | 37.5%   |
| 6      | 9         | 8.65%   |
| 8      | 4         | 3.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 77.88%  |
| 1      | 23        | 22.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 104       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 9         | 8.65%   |
| 0x206a7    | 8         | 7.69%   |
| 0x406e3    | 7         | 6.73%   |
| 0x306a9    | 7         | 6.73%   |
| 0x806c1    | 6         | 5.77%   |
| 0x40651    | 5         | 4.81%   |
| 0x306d4    | 5         | 4.81%   |
| 0x1067a    | 5         | 4.81%   |
| 0x08600106 | 5         | 4.81%   |
| 0x10676    | 4         | 3.85%   |
| 0x906ea    | 3         | 2.88%   |
| 0x806ec    | 3         | 2.88%   |
| 0x806eb    | 3         | 2.88%   |
| 0x20655    | 3         | 2.88%   |
| 0x806ea    | 2         | 1.92%   |
| 0x806e9    | 2         | 1.92%   |
| 0x506c9    | 2         | 1.92%   |
| 0x406c3    | 2         | 1.92%   |
| 0x306c3    | 2         | 1.92%   |
| 0x08608103 | 2         | 1.92%   |
| 0x08108109 | 2         | 1.92%   |
| 0x08108102 | 2         | 1.92%   |
| 0x08101007 | 2         | 1.92%   |
| 0xa0660    | 1         | 0.96%   |
| 0xa0652    | 1         | 0.96%   |
| 0x906ed    | 1         | 0.96%   |
| 0x906e9    | 1         | 0.96%   |
| 0x6fd      | 1         | 0.96%   |
| 0x6fb      | 1         | 0.96%   |
| 0x506e3    | 1         | 0.96%   |
| 0x40661    | 1         | 0.96%   |
| 0x106e5    | 1         | 0.96%   |
| 0x07030105 | 1         | 0.96%   |
| 0x07030104 | 1         | 0.96%   |
| 0x06006705 | 1         | 0.96%   |
| 0x06006704 | 1         | 0.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 19        | 18.27%  |
| Skylake     | 9         | 8.65%   |
| SandyBridge | 9         | 8.65%   |
| Penryn      | 9         | 8.65%   |
| Haswell     | 9         | 8.65%   |
| IvyBridge   | 7         | 6.73%   |
| TigerLake   | 6         | 5.77%   |
| Zen 2       | 5         | 4.81%   |
| Broadwell   | 5         | 4.81%   |
| Zen+        | 4         | 3.85%   |
| Westmere    | 4         | 3.85%   |
| Unknown     | 3         | 2.88%   |
| Zen         | 2         | 1.92%   |
| Silvermont  | 2         | 1.92%   |
| Puma        | 2         | 1.92%   |
| Goldmont    | 2         | 1.92%   |
| Excavator   | 2         | 1.92%   |
| Core        | 2         | 1.92%   |
| CometLake   | 2         | 1.92%   |
| Nehalem     | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 57.69%  |
| Nvidia | 29        | 22.31%  |
| AMD    | 26        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 6.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 5.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 4.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 4.51%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 3.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 3.76%   |
| AMD Renoir                                                                               | 5         | 3.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 3.01%   |
| Intel HD Graphics 5500                                                                   | 4         | 3.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 3.01%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.26%   |
| AMD Lucienne                                                                             | 3         | 2.26%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.5%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.5%    |
| Intel HD Graphics 620                                                                    | 2         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.5%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.5%    |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia TU117M                                                                            | 1         | 0.75%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 0.75%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.75%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 0.75%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.75%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.75%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.75%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 1         | 0.75%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.75%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.75%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.75%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 0.75%   |
| Intel HD Graphics 630                                                                    | 1         | 0.75%   |
| Intel HD Graphics 6000                                                                   | 1         | 0.75%   |
| Intel HD Graphics 520                                                                    | 1         | 0.75%   |
| Intel HD Graphics 515                                                                    | 1         | 0.75%   |
| Intel HD Graphics 500                                                                    | 1         | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.75%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 0.75%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 0.75%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.75%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                          | 1         | 0.75%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 1         | 0.75%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 48.08%  |
| Intel + Nvidia | 21        | 20.19%  |
| 1 x AMD        | 21        | 20.19%  |
| 1 x Nvidia     | 6         | 5.77%   |
| Intel + AMD    | 4         | 3.85%   |
| 2 x Nvidia     | 1         | 0.96%   |
| AMD + Nvidia   | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 86.54%  |
| Proprietary | 14        | 13.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 54.81%  |
| 0.01-0.5   | 18        | 17.31%  |
| 1.01-2.0   | 15        | 14.42%  |
| 0.51-1.0   | 8         | 7.69%   |
| 3.01-4.0   | 5         | 4.81%   |
| 5.01-6.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 19.17%  |
| LG Display              | 19        | 15.83%  |
| Apple                   | 17        | 14.17%  |
| Chimei Innolux          | 16        | 13.33%  |
| BOE                     | 8         | 6.67%   |
| Sharp                   | 6         | 5%      |
| Samsung Electronics     | 6         | 5%      |
| Goldstar                | 4         | 3.33%   |
| Dell                    | 4         | 3.33%   |
| PANDA                   | 3         | 2.5%    |
| Lenovo                  | 3         | 2.5%    |
| Hewlett-Packard         | 3         | 2.5%    |
| CSO                     | 3         | 2.5%    |
| Sony                    | 1         | 0.83%   |
| JDI                     | 1         | 0.83%   |
| Chi Mei Optoelectronics | 1         | 0.83%   |
| BenQ                    | 1         | 0.83%   |
| Acer                    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 2.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.44%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 1.63%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 1.63%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 1.63%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 1.63%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 1.63%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 1.63%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 2         | 1.63%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 2         | 1.63%   |
| Sony Nvidia Defaul SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.81%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.81%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch               | 1         | 0.81%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.81%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch  | 1         | 0.81%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 1         | 0.81%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.81%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.81%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch               | 1         | 0.81%   |
| LG Display LCD Monitor LGD060A 1920x1080 294x165mm 13.3-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD04A5 1920x1280 253x169mm 12.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 1         | 0.81%   |
| LG Display LCD Monitor LGD03E9 1366x768 345x194mm 15.6-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 1         | 0.81%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch           | 1         | 0.81%   |
| Lenovo P24h-10 LEN61AE 2560x1440 527x296mm 23.8-inch                  | 1         | 0.81%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 527x296mm 23.8-inch              | 1         | 0.81%   |
| Lenovo LEN P24h-20 LEN61F4 2560x1440 527x296mm 23.8-inch              | 1         | 0.81%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 1         | 0.81%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 1         | 0.81%   |
| Hewlett-Packard V196bz HWP323E 1366x768 410x230mm 18.5-inch           | 1         | 0.81%   |
| Hewlett-Packard E273q HPN3475 2560x1440 597x336mm 27.0-inch           | 1         | 0.81%   |
| Hewlett-Packard 27fw HPN354A 1920x1080 600x340mm 27.2-inch            | 1         | 0.81%   |
| Goldstar E2442 GSM58C6 1920x1080 531x299mm 24.0-inch                  | 1         | 0.81%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch              | 1         | 0.81%   |
| Dell U2520DR DELA155 2560x1440 553x311mm 25.0-inch                    | 1         | 0.81%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                     | 1         | 0.81%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                     | 1         | 0.81%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 1         | 0.81%   |
| Dell E2418HN DELA105 1920x1080 527x296mm 23.8-inch                    | 1         | 0.81%   |
| Dell E2418HN DELA104 1920x1080 527x296mm 23.8-inch                    | 1         | 0.81%   |
| CSO LCD Monitor CSO1403 3840x2400 302x189mm 14.0-inch                 | 1         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 1         | 0.81%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 46        | 39.66%  |
| 1366x768 (WXGA)    | 32        | 27.59%  |
| 1280x800 (WXGA)    | 8         | 6.9%    |
| 2560x1440 (QHD)    | 5         | 4.31%   |
| 1600x900 (HD+)     | 5         | 4.31%   |
| 3840x2160 (4K)     | 4         | 3.45%   |
| 1440x900 (WXGA+)   | 4         | 3.45%   |
| 3000x2000          | 3         | 2.59%   |
| 2560x1080          | 2         | 1.72%   |
| 3840x2400          | 1         | 0.86%   |
| 3200x1800 (QHD+)   | 1         | 0.86%   |
| 3072x1920          | 1         | 0.86%   |
| 2880x1800          | 1         | 0.86%   |
| 1920x1280          | 1         | 0.86%   |
| 1920x1200 (WUXGA)  | 1         | 0.86%   |
| 1680x1050 (WSXGA+) | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 41.32%  |
| 13      | 26        | 21.49%  |
| 14      | 17        | 14.05%  |
| 27      | 4         | 3.31%   |
| 24      | 4         | 3.31%   |
| 23      | 3         | 2.48%   |
| 17      | 3         | 2.48%   |
| 11      | 3         | 2.48%   |
| 34      | 2         | 1.65%   |
| 25      | 2         | 1.65%   |
| 12      | 2         | 1.65%   |
| 47      | 1         | 0.83%   |
| 31      | 1         | 0.83%   |
| 18      | 1         | 0.83%   |
| 16      | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 75        | 62.5%   |
| 201-300     | 23        | 19.17%  |
| 501-600     | 12        | 10%     |
| 351-400     | 4         | 3.33%   |
| 701-800     | 2         | 1.67%   |
| 601-700     | 1         | 0.83%   |
| 401-500     | 1         | 0.83%   |
| 1001-1500   | 1         | 0.83%   |
| Unknown     | 1         | 0.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 82        | 77.36%  |
| 16/10 | 17        | 16.04%  |
| 3/2   | 5         | 4.72%   |
| 21/9  | 2         | 1.89%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 40%     |
| 81-90          | 33        | 27.5%   |
| 71-80          | 10        | 8.33%   |
| 201-250        | 5         | 4.17%   |
| 301-350        | 4         | 3.33%   |
| 51-60          | 3         | 2.5%    |
| 351-500        | 3         | 2.5%    |
| 251-300        | 3         | 2.5%    |
| 61-70          | 2         | 1.67%   |
| 121-130        | 2         | 1.67%   |
| 111-120        | 2         | 1.67%   |
| 141-150        | 1         | 0.83%   |
| 131-140        | 1         | 0.83%   |
| 501-1000       | 1         | 0.83%   |
| 91-100         | 1         | 0.83%   |
| Unknown        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 42.02%  |
| 101-120       | 38        | 31.93%  |
| 51-100        | 15        | 12.61%  |
| More than 240 | 7         | 5.88%   |
| 161-240       | 7         | 5.88%   |
| 1-50          | 1         | 0.84%   |
| Unknown       | 1         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 86        | 82.69%  |
| 2     | 15        | 14.42%  |
| 3     | 3         | 2.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 53        | 33.13%  |
| Realtek Semiconductor    | 45        | 28.13%  |
| Broadcom                 | 22        | 13.75%  |
| Qualcomm Atheros         | 15        | 9.38%   |
| Nvidia                   | 6         | 3.75%   |
| Broadcom Limited         | 4         | 2.5%    |
| TP-Link                  | 2         | 1.25%   |
| Ralink                   | 2         | 1.25%   |
| Marvell Technology Group | 2         | 1.25%   |
| Google                   | 2         | 1.25%   |
| Xiaomi                   | 1         | 0.63%   |
| Sitecom Europe           | 1         | 0.63%   |
| Sierra Wireless          | 1         | 0.63%   |
| OPPO Electronics         | 1         | 0.63%   |
| MEDIATEK                 | 1         | 0.63%   |
| Hewlett-Packard          | 1         | 0.63%   |
| Apple                    | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31        | 16.4%   |
| Intel Wireless 8260                                                            | 7         | 3.7%    |
| Nvidia MCP79 Ethernet                                                          | 6         | 3.17%   |
| Intel Wi-Fi 6 AX201                                                            | 6         | 3.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 6         | 3.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 6         | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 5         | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 2.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 2.12%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 2.12%   |
| Intel Wireless 7265                                                            | 4         | 2.12%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 2.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 4         | 2.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 4         | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 1.59%   |
| Intel Wireless 7260                                                            | 3         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 3         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 2         | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.06%   |
| Intel Wireless-AC 9260                                                         | 2         | 1.06%   |
| Intel Wireless 3165                                                            | 2         | 1.06%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.06%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 1.06%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.06%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                     | 2         | 1.06%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 2         | 1.06%   |
| Broadcom BCM4321 802.11a/b/g/n                                                 | 2         | 1.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.53%   |
| TP-Link 802.11n NIC                                                            | 1         | 0.53%   |
| TP-Link 802.11ac WLAN Adapter                                                  | 1         | 0.53%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N                       | 1         | 0.53%   |
| Sierra Wireless EM7455                                                         | 1         | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.53%   |
| Realtek Realtek Network controller                                             | 1         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.53%   |
| OPPO RMX3381                                                                   | 1         | 0.53%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.53%   |
| Intel Wireless Gigabit 17265                                                   | 1         | 0.53%   |
| Intel Wireless 3160                                                            | 1         | 0.53%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.53%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 48.15%  |
| Broadcom              | 22        | 20.37%  |
| Qualcomm Atheros      | 12        | 11.11%  |
| Realtek Semiconductor | 11        | 10.19%  |
| Broadcom Limited      | 4         | 3.7%    |
| TP-Link               | 2         | 1.85%   |
| Ralink                | 2         | 1.85%   |
| Sitecom Europe        | 1         | 0.93%   |
| Sierra Wireless       | 1         | 0.93%   |
| MEDIATEK              | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 7         | 6.42%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 5.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 5.5%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 5.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 3.67%   |
| Intel Wireless 8265 / 8275                                     | 4         | 3.67%   |
| Intel Wireless 7265                                            | 4         | 3.67%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 3.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 3.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.75%   |
| Intel Wireless 7260                                            | 3         | 2.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.83%   |
| Intel Wireless-AC 9260                                         | 2         | 1.83%   |
| Intel Wireless 3165                                            | 2         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.83%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.83%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 1.83%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.83%   |
| TP-Link 802.11n NIC                                            | 1         | 0.92%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.92%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N       | 1         | 0.92%   |
| Sierra Wireless EM7455                                         | 1         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.92%   |
| Realtek Realtek Network controller                             | 1         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.92%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.92%   |
| Intel Wireless Gigabit 17265                                   | 1         | 0.92%   |
| Intel Wireless 3160                                            | 1         | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.92%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 0.92%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 0.92%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter             | 1         | 0.92%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1         | 0.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 50.63%  |
| Intel                    | 13        | 16.46%  |
| Broadcom                 | 8         | 10.13%  |
| Nvidia                   | 6         | 7.59%   |
| Qualcomm Atheros         | 3         | 3.8%    |
| Marvell Technology Group | 2         | 2.53%   |
| Google                   | 2         | 2.53%   |
| Xiaomi                   | 1         | 1.27%   |
| OPPO Electronics         | 1         | 1.27%   |
| Hewlett-Packard          | 1         | 1.27%   |
| Broadcom Limited         | 1         | 1.27%   |
| Apple                    | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31        | 38.75%  |
| Nvidia MCP79 Ethernet                                                          | 6         | 7.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 6.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 6.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 3.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 2.5%    |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.5%    |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 2.5%    |
| Google Nexus/Pixel Device (tether)                                             | 2         | 2.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 1.25%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.25%   |
| OPPO RMX3381                                                                   | 1         | 1.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.25%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.25%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.25%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.25%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.25%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 1.25%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 1.25%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 1.25%   |
| Apple T2 Controller                                                            | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 58.99%  |
| Ethernet | 73        | 41.01%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 60%     |
| Ethernet | 68        | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 68        | 65.38%  |
| 1     | 35        | 33.65%  |
| 3     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 65        | 62.5%   |
| Yes  | 39        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 48.98%  |
| Apple                           | 17        | 17.35%  |
| Realtek Semiconductor           | 10        | 10.2%   |
| Qualcomm Atheros Communications | 6         | 6.12%   |
| Lite-On Technology              | 3         | 3.06%   |
| Foxconn / Hon Hai               | 3         | 3.06%   |
| Cambridge Silicon Radio         | 3         | 3.06%   |
| Broadcom                        | 3         | 3.06%   |
| IMC Networks                    | 2         | 2.04%   |
| Realtek                         | 1         | 1.02%   |
| Ralink                          | 1         | 1.02%   |
| Hewlett-Packard                 | 1         | 1.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 25        | 25.51%  |
| Intel Bluetooth wireless interface                                                  | 11        | 11.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 9.18%   |
| Apple Bluetooth Host Controller                                                     | 9         | 9.18%   |
| Realtek Bluetooth Radio                                                             | 6         | 6.12%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 5.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 3.06%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 2.04%   |
| Apple Bluetooth HCI                                                                 | 2         | 2.04%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.02%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.02%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.02%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 1.02%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.02%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.02%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.02%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.02%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.02%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.02%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 1.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 1.02%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 79        | 63.2%   |
| AMD                     | 25        | 20%     |
| Nvidia                  | 14        | 11.2%   |
| Texas Instruments       | 1         | 0.8%    |
| Realtek Semiconductor   | 1         | 0.8%    |
| Logitech                | 1         | 0.8%    |
| CalDigit                | 1         | 0.8%    |
| C-Media Electronics     | 1         | 0.8%    |
| BEHRINGER International | 1         | 0.8%    |
| Apple                   | 1         | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 14        | 8.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.13%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 3.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 3.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 3.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.21%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 3.21%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.21%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.56%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.28%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.28%   |
| AMD High Definition Audio Controller                                                              | 2         | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.28%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.28%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.64%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.64%   |
| Logitech 960 Headset                                                                              | 1         | 0.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.64%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.64%   |
| CalDigit Thunderbolt 3 Audio                                                                      | 1         | 0.64%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.64%   |
| BEHRINGER International UMC202HD 192k                                                             | 1         | 0.64%   |
| Apple Audio Device                                                                                | 1         | 0.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 1         | 0.64%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.64%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 1         | 0.64%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.64%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 12        | 40%     |
| Micron Technology   | 7         | 23.33%  |
| SK Hynix            | 6         | 20%     |
| G.Skill             | 2         | 6.67%   |
| Unknown             | 1         | 3.33%   |
| GSkill              | 1         | 3.33%   |
| Crucial             | 1         | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s       | 2         | 5.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 5.88%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s        | 2         | 5.88%   |
| Unknown RAM Module 8192MB SODIMM DDR3                           | 1         | 2.94%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 2.94%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s               | 1         | 2.94%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.94%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s            | 1         | 2.94%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s       | 1         | 2.94%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s       | 1         | 2.94%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 1         | 2.94%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 2.94%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 2.94%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 2.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 1         | 2.94%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 2.94%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s        | 1         | 2.94%   |
| Samsung RAM K4EBE304ED-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 2.94%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s       | 1         | 2.94%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 2.94%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s        | 1         | 2.94%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s         | 1         | 2.94%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s     | 1         | 2.94%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.94%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s        | 1         | 2.94%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s          | 1         | 2.94%   |
| G.Skill RAM F4-2666C18-16GRS 16384MB SODIMM DDR4 2667MT/s       | 1         | 2.94%   |
| G.Skill RAM F3-1600C11-8GSQ 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| G.Skill RAM F3-1600C11-8GSL 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.94%   |
| Crucial RAM CB8GS2400.C8D 8192MB SODIMM DDR4 2400MT/s           | 1         | 2.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 15        | 51.72%  |
| DDR3   | 10        | 34.48%  |
| LPDDR4 | 2         | 6.9%    |
| LPDDR3 | 2         | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 25        | 86.21%  |
| Row Of Chips | 3         | 10.34%  |
| Chip         | 1         | 3.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 48.39%  |
| 4096  | 9         | 29.03%  |
| 2048  | 4         | 12.9%   |
| 16384 | 3         | 9.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 8         | 26.67%  |
| 2667    | 7         | 23.33%  |
| 3200    | 5         | 16.67%  |
| 2133    | 3         | 10%     |
| 4267    | 2         | 6.67%   |
| 3266    | 1         | 3.33%   |
| 2400    | 1         | 3.33%   |
| 1867    | 1         | 3.33%   |
| 1334    | 1         | 3.33%   |
| Unknown | 1         | 3.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Canon PIXMA MG2500 Series | 1         | 100%    |

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
| Chicony Electronics                    | 17        | 17.17%  |
| IMC Networks                           | 16        | 16.16%  |
| Apple                                  | 14        | 14.14%  |
| Acer                                   | 10        | 10.1%   |
| Realtek Semiconductor                  | 8         | 8.08%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 7.07%   |
| Microdia                               | 5         | 5.05%   |
| Quanta                                 | 4         | 4.04%   |
| Suyin                                  | 3         | 3.03%   |
| Alcor Micro                            | 3         | 3.03%   |
| Luxvisions Innotech Limited            | 2         | 2.02%   |
| Y Media                                | 1         | 1.01%   |
| Syntek                                 | 1         | 1.01%   |
| Sunplus Innovation Technology          | 1         | 1.01%   |
| Sony                                   | 1         | 1.01%   |
| Silicon Motion                         | 1         | 1.01%   |
| Ricoh                                  | 1         | 1.01%   |
| Logitech                               | 1         | 1.01%   |
| Lite-On Technology                     | 1         | 1.01%   |
| kingcome                               | 1         | 1.01%   |
| Foxconn / Hon Hai                      | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                             | 6         | 5.94%   |
| Chicony Integrated Camera                                                  | 6         | 5.94%   |
| Apple Built-in iSight                                                      | 6         | 5.94%   |
| Apple FaceTime HD Camera                                                   | 5         | 4.95%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 4         | 3.96%   |
| Acer Lenovo EasyCamera                                                     | 4         | 3.96%   |
| Microdia Integrated_Webcam_HD                                              | 3         | 2.97%   |
| Chicony HD WebCam                                                          | 3         | 2.97%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.98%   |
| Realtek USB Camera                                                         | 2         | 1.98%   |
| Realtek Integrated_Webcam_HD                                               | 2         | 1.98%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 1.98%   |
| IMC Networks EasyCamera                                                    | 2         | 1.98%   |
| Chicony USB 2.0 Camera                                                     | 2         | 1.98%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 2         | 1.98%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 2         | 1.98%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 2         | 1.98%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 1.98%   |
| Acer EasyCamera                                                            | 2         | 1.98%   |
| Y Media USB Camera                                                         | 1         | 0.99%   |
| Syntek Integrated Camera                                                   | 1         | 0.99%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.99%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.99%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.99%   |
| Sunplus HP Universal Camera                                                | 1         | 0.99%   |
| Sony CEVCECM                                                               | 1         | 0.99%   |
| Silicon Motion WebCam SC-13HDL11624N                                       | 1         | 0.99%   |
| Ricoh Dell Laptop Integrated Webcam                                        | 1         | 0.99%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 0.99%   |
| Realtek Integrated Webcam                                                  | 1         | 0.99%   |
| Quanta VGA WebCam                                                          | 1         | 0.99%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 0.99%   |
| Quanta hm1091_techfront                                                    | 1         | 0.99%   |
| Quanta HD User Facing                                                      | 1         | 0.99%   |
| Microdia Webcam Vitade AF                                                  | 1         | 0.99%   |
| Microdia Laptop_Integrated_Webcam_2M                                       | 1         | 0.99%   |
| Logitech Webcam Pro 9000                                                   | 1         | 0.99%   |
| Lite-On HP HD Webcam                                                       | 1         | 0.99%   |
| kingcome HD Camera                                                         | 1         | 0.99%   |
| IMC Networks USB2.0-Camera                                                 | 1         | 0.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 0.99%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 1         | 0.99%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 0.99%   |
| Foxconn / Hon Hai USB2.0 Camera                                            | 1         | 0.99%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 0.99%   |
| Chicony USB2.0 Camera                                                      | 1         | 0.99%   |
| Chicony thinkpad t430s camera                                              | 1         | 0.99%   |
| Chicony Integrated IR Camera                                               | 1         | 0.99%   |
| Chicony Integrated HP HD Webcam                                            | 1         | 0.99%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 0.99%   |
| Chicony EasyCamera                                                         | 1         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 1         | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP Full HD Camera                   | 1         | 0.99%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 0.99%   |
| Apple Built-in iSight [Micron]                                             | 1         | 0.99%   |
| Alcor Micro USB 2.0 PC Camera                                              | 1         | 0.99%   |
| Acer SunplusIT Integrated Camera                                           | 1         | 0.99%   |
| Acer Integrated Camera                                                     | 1         | 0.99%   |
| Acer HD Webcam                                                             | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 30.77%  |
| Synaptics                  | 4         | 30.77%  |
| LighTuning Technology      | 3         | 23.08%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 2         | 15.38%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 15.38%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 15.38%  |
| LighTuning ES603 Swipe Fingerprint Sensor         | 2         | 15.38%  |
| Validity Sensors VFS491                           | 1         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 7.69%   |
| Unknown                                           | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader            | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 78        | 75%     |
| 1     | 24        | 23.08%  |
| 2     | 2         | 1.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 13        | 46.43%  |
| Multimedia controller | 4         | 14.29%  |
| Net/wireless          | 3         | 10.71%  |
| Chipcard              | 3         | 10.71%  |
| Graphics card         | 2         | 7.14%   |
| Camera                | 2         | 7.14%   |
| Bluetooth             | 1         | 3.57%   |

