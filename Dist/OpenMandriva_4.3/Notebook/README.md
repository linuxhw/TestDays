OpenMandriva 4.3 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

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

Total: 1631

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1545               | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| Dell          | Inspiron 11-3162            | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Dell          | Latitude E6520              | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3310               | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | Compaq 6720s                | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Dell          | XPS 13 9360                 | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| Dell          | Latitude 3310               | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Sony          | VPCEH1S1R                   | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3310               | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3420               | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| HP            | Laptop 17-by3xxx            | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| HP            | Pavilion 15                 | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | Latitude 3310               | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 7480               | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Dell          | G5 5505                     | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| Acer          | Aspire A315-23              | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3310               | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Dell          | Latitude 3300               | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| HP            | Notebook                    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Apple         | MacBook6,1                  | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Chuwi         | HeroBook Pro                | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Dell          | Latitude E7470              | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Compal        | NCL60/61                    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASUSTek       | UX31E                       | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| HP            | Notebook                    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| Lenovo        | Unknown                     | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Samsung       | SX60P                       | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Dell          | Precision 7560              | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| Positivo      | H14BT58                     | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Dell          | Latitude E6220              | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| ASUSTek       | X45C                        | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Apple         | MacBookPro8,1               | [113f737135](https://linux-hardware.org/?probe=113f737135) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| ASUSTek       | X540LA                      | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| MSI           | MS-168B                     | [a0a6645eef](https://linux-hardware.org/?probe=a0a6645eef) | Sep 04, 2022 |
| Jumper        | EZbook                      | [d67fae436c](https://linux-hardware.org/?probe=d67fae436c) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Samsung       | 300E5M/300E5L               | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Acer          | Extensa 5635ZG              | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| HP            | Compaq Presario CQ60        | [c2251f33ef](https://linux-hardware.org/?probe=c2251f33ef) | Sep 03, 2022 |
| HP            | 620                         | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| ASUSTek       | UX31E                       | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Getac         | B300-X                      | [927b99c2e0](https://linux-hardware.org/?probe=927b99c2e0) | Sep 02, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| Dell          | Latitude 3120               | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| HP            | Laptop 15-ef1xxx            | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Dell          | Latitude 3190               | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| Dell          | Precision M6400             | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| Dell          | Latitude 3300               | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| HP            | 620                         | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Acer          | AO722                       | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| HP            | 15                          | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | Laptop 15-dy1xxx            | [b201192ebb](https://linux-hardware.org/?probe=b201192ebb) | Aug 25, 2022 |
| Dell          | Latitude E5510              | [c237161d31](https://linux-hardware.org/?probe=c237161d31) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f20e68e820](https://linux-hardware.org/?probe=f20e68e820) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Acer          | Aspire A315-54K             | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| Dell          | Latitude E5470              | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| Google        | Galtic                      | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Acer          | Enduro EUN314-51WG          | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Dell          | Latitude 3300               | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Pavilion dv6                | [0aae35eb95](https://linux-hardware.org/?probe=0aae35eb95) | Aug 19, 2022 |
| Dell          | XPS 13 9360                 | [74b0bedd54](https://linux-hardware.org/?probe=74b0bedd54) | Aug 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c954da96ad](https://linux-hardware.org/?probe=c954da96ad) | Aug 18, 2022 |
| ASUSTek       | X75A1                       | [870fcf0f3c](https://linux-hardware.org/?probe=870fcf0f3c) | Aug 18, 2022 |
| Dell          | Latitude E5510              | [c7defb71d5](https://linux-hardware.org/?probe=c7defb71d5) | Aug 18, 2022 |
| Medion        | Akoya E6418 MD99620         | [6817b38103](https://linux-hardware.org/?probe=6817b38103) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| Acer          | Nitro AN515-31              | [471659ffff](https://linux-hardware.org/?probe=471659ffff) | Aug 17, 2022 |
| Dell          | Latitude 3380               | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [9bdceca056](https://linux-hardware.org/?probe=9bdceca056) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| Dell          | Latitude 3310               | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [a880d764be](https://linux-hardware.org/?probe=a880d764be) | Aug 16, 2022 |
| Lenovo        | ThinkPad L412 0585A84       | [637fa23dca](https://linux-hardware.org/?probe=637fa23dca) | Aug 16, 2022 |
| Dell          | Latitude 3310               | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| Acer          | Aspire ES1-532G             | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| Dell          | Latitude E6430              | [6c31827147](https://linux-hardware.org/?probe=6c31827147) | Aug 15, 2022 |
| Dell          | Inspiron 1501               | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [4b1440875b](https://linux-hardware.org/?probe=4b1440875b) | Aug 14, 2022 |
| ASUSTek       | X540LA                      | [15ffff65c0](https://linux-hardware.org/?probe=15ffff65c0) | Aug 14, 2022 |
| HP            | ProBook 4330s               | [62ff6ffc08](https://linux-hardware.org/?probe=62ff6ffc08) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Acer          | Aspire VN7-571G             | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion dv9500             | [fd3bd18049](https://linux-hardware.org/?probe=fd3bd18049) | Aug 14, 2022 |
| Toshiba       | Satellite P200              | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Positivo      | Mobile                      | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| ASUSTek       | K73BR                       | [67f5d3f176](https://linux-hardware.org/?probe=67f5d3f176) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| Lenovo        | Unknown                     | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Dell          | G5 5505                     | [cbbcb7c9a2](https://linux-hardware.org/?probe=cbbcb7c9a2) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| HP            | Pavilion dm3                | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| HP            | 240 G3                      | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| Toshiba       | Satellite A300              | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| HP            | 630                         | [fc9bc69e9a](https://linux-hardware.org/?probe=fc9bc69e9a) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Acer          | Nitro AN515-31              | [0dbab56588](https://linux-hardware.org/?probe=0dbab56588) | Aug 08, 2022 |
| HP            | 15                          | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| Dell          | Latitude E7240              | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Dell          | Latitude E6420              | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Compaq 15                   | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| Timi          | RedmiBook Pro 15S           | [4e36acba35](https://linux-hardware.org/?probe=4e36acba35) | Aug 07, 2022 |
| Dell          | Latitude 3189               | [63c2818521](https://linux-hardware.org/?probe=63c2818521) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [810a9d1c2c](https://linux-hardware.org/?probe=810a9d1c2c) | Aug 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | [bfceb8ba35](https://linux-hardware.org/?probe=bfceb8ba35) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| ASUSTek       | X555LN                      | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [b9a68ae76c](https://linux-hardware.org/?probe=b9a68ae76c) | Aug 06, 2022 |
| Acer          | E1-510                      | [05ea3ff386](https://linux-hardware.org/?probe=05ea3ff386) | Aug 05, 2022 |
| Dell          | Latitude 3310               | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Dell          | Latitude 3410               | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| Dell          | Precision M4700             | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| HP            | ProBook 6450b               | [699b27e34f](https://linux-hardware.org/?probe=699b27e34f) | Aug 05, 2022 |
| Lenovo        | ThinkPad X230 2325U9T       | [0f0e8ec24f](https://linux-hardware.org/?probe=0f0e8ec24f) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Dell          | Latitude 3490               | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3310               | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Lenovo        | ThinkPad T530 2429W4Z       | [2d95f7cc7e](https://linux-hardware.org/?probe=2d95f7cc7e) | Aug 03, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [f1d5a6ab3f](https://linux-hardware.org/?probe=f1d5a6ab3f) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| Dell          | Latitude E6430              | [15e26c7cc5](https://linux-hardware.org/?probe=15e26c7cc5) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude E7450              | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Toshiba       | Satellite-C845              | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Acer          | TravelMate B118-M           | [490edd75cf](https://linux-hardware.org/?probe=490edd75cf) | Jul 31, 2022 |
| HP            | ProBook 6570b               | [333a24bdee](https://linux-hardware.org/?probe=333a24bdee) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| eMachines     | Unknown                     | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| Compaq        | Presario CQ-23              | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Apple         | MacBookPro7,1               | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| ASUSTek       | K501LX                      | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| ASUSTek       | K53E                        | [3ca340212e](https://linux-hardware.org/?probe=3ca340212e) | Jul 30, 2022 |
| Lenovo        | G570 4334                   | [a29c1c816a](https://linux-hardware.org/?probe=a29c1c816a) | Jul 30, 2022 |
| Fujitsu       | LIFEBOOK V1020              | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| MSI           | GF63 8RD                    | [fdb72c3ec3](https://linux-hardware.org/?probe=fdb72c3ec3) | Jul 29, 2022 |
| Acer          | Aspire A317-33              | [ab07e43574](https://linux-hardware.org/?probe=ab07e43574) | Jul 29, 2022 |
| Sony          | VPCEA45FL                   | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| HP            | ProBook 6570b               | [231ebd2edc](https://linux-hardware.org/?probe=231ebd2edc) | Jul 29, 2022 |
| Acer          | Aspire 7741                 | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| Google        | Candy                       | [cba2906cfd](https://linux-hardware.org/?probe=cba2906cfd) | Jul 29, 2022 |
| HP            | ProBook 430 G5              | [f424705bd7](https://linux-hardware.org/?probe=f424705bd7) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Lenovo        | G50-45 80E3                 | [61a6277614](https://linux-hardware.org/?probe=61a6277614) | Jul 28, 2022 |
| ASUSTek       | X551MA                      | [668a02296d](https://linux-hardware.org/?probe=668a02296d) | Jul 28, 2022 |
| HP            | ProBook 4515s               | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| ASUSTek       | K53U                        | [7db28a1538](https://linux-hardware.org/?probe=7db28a1538) | Jul 28, 2022 |
| Acer          | Aspire 3100                 | [26c6af2a55](https://linux-hardware.org/?probe=26c6af2a55) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| HP            | 2000                        | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [7bcdc30be3](https://linux-hardware.org/?probe=7bcdc30be3) | Jul 28, 2022 |
| Digibras      | NH4CU03                     | [bf8a8c589a](https://linux-hardware.org/?probe=bf8a8c589a) | Jul 28, 2022 |
| Positivo      | H14BT58                     | [7f271e5d68](https://linux-hardware.org/?probe=7f271e5d68) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94a6b79798](https://linux-hardware.org/?probe=94a6b79798) | Jul 27, 2022 |
| Samsung       | 550XBE/350XBE               | [b7fabad758](https://linux-hardware.org/?probe=b7fabad758) | Jul 27, 2022 |
| HP            | Pavilion g7                 | [75fa7f0ce4](https://linux-hardware.org/?probe=75fa7f0ce4) | Jul 27, 2022 |
| Dell          | XPS 13 9300                 | [8f0daaf341](https://linux-hardware.org/?probe=8f0daaf341) | Jul 27, 2022 |
| ASUSTek       | S551LB                      | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Dell          | Latitude E6330              | [5ee8d985ed](https://linux-hardware.org/?probe=5ee8d985ed) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [17f64584bb](https://linux-hardware.org/?probe=17f64584bb) | Jul 27, 2022 |
| HP            | Compaq 6720s                | [d8546f791c](https://linux-hardware.org/?probe=d8546f791c) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| Acer          | TravelMate P633-M           | [7d346db799](https://linux-hardware.org/?probe=7d346db799) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| HP            | Compaq Presario CQ60        | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| Dell          | Latitude E7240              | [6af993caf7](https://linux-hardware.org/?probe=6af993caf7) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| HP            | ProBook 645 G1              | [457c35707a](https://linux-hardware.org/?probe=457c35707a) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Dell          | Latitude 131L               | [ec8717bc3f](https://linux-hardware.org/?probe=ec8717bc3f) | Jul 26, 2022 |
| Dell          | Latitude 3300               | [64cf4b87d9](https://linux-hardware.org/?probe=64cf4b87d9) | Jul 26, 2022 |
| Toshiba       | dynabook R734/K             | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| Dell          | Vostro 15-3568              | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| Dell          | Latitude 3310               | [0fe12d0d48](https://linux-hardware.org/?probe=0fe12d0d48) | Jul 25, 2022 |
| Acer          | Aspire 5741G                | [a4f8482423](https://linux-hardware.org/?probe=a4f8482423) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | [e6b9106560](https://linux-hardware.org/?probe=e6b9106560) | Jul 24, 2022 |
| Lenovo        | ThinkPad P50 20EN0008GE     | [93ec0d85ab](https://linux-hardware.org/?probe=93ec0d85ab) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| HP            | Notebook                    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| Dell          | Latitude E6430              | [8bc3b0f962](https://linux-hardware.org/?probe=8bc3b0f962) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| AZW           | GT-R                        | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T61 6458W4B        | [3d51bdb900](https://linux-hardware.org/?probe=3d51bdb900) | Jul 22, 2022 |
| Acer          | Aspire 5738                 | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Lenovo        | ThinkPad Helix 36986EU      | [294d96aff6](https://linux-hardware.org/?probe=294d96aff6) | Jul 22, 2022 |
| Positivo      | J14AL11                     | [7510e905d8](https://linux-hardware.org/?probe=7510e905d8) | Jul 22, 2022 |
| HP            | Notebook                    | [e859de5718](https://linux-hardware.org/?probe=e859de5718) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [bc6103f96b](https://linux-hardware.org/?probe=bc6103f96b) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [abe159e82a](https://linux-hardware.org/?probe=abe159e82a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [d90f147df3](https://linux-hardware.org/?probe=d90f147df3) | Jul 21, 2022 |
| Dell          | Latitude 3310               | [324b95a49a](https://linux-hardware.org/?probe=324b95a49a) | Jul 21, 2022 |
| METAPHYUNI    | MetamechBook                | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Dell          | Latitude E5450              | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Lenovo        | V130-15IKB 81HN             | [fe2f5a993c](https://linux-hardware.org/?probe=fe2f5a993c) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [086f88be40](https://linux-hardware.org/?probe=086f88be40) | Jul 20, 2022 |
| Dell          | Inspiron 5579               | [52e88ad171](https://linux-hardware.org/?probe=52e88ad171) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [0cb2abc6bc](https://linux-hardware.org/?probe=0cb2abc6bc) | Jul 20, 2022 |
| Dell          | Latitude 3310               | [dbd9b101c2](https://linux-hardware.org/?probe=dbd9b101c2) | Jul 20, 2022 |
| Dell          | Latitude 5285               | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |
| HP            | Dev One Notebook PC         | [e386bc211b](https://linux-hardware.org/?probe=e386bc211b) | Jul 20, 2022 |
| HP            | Laptop 14-ck0xxx            | [78c2b82b87](https://linux-hardware.org/?probe=78c2b82b87) | Jul 19, 2022 |
| HP            | 250 G6 Notebook PC          | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Gateway       | NV53A                       | [2674f3160f](https://linux-hardware.org/?probe=2674f3160f) | Jul 19, 2022 |
| Acer          | Aspire A515-51G             | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| Samsung       | 270E5G/270E5U               | [c26ed846e9](https://linux-hardware.org/?probe=c26ed846e9) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Acer          | Aspire ES1-411              | [5d551a94bd](https://linux-hardware.org/?probe=5d551a94bd) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Teclast       | F15 Plus                    | [6201934176](https://linux-hardware.org/?probe=6201934176) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [14d23344e2](https://linux-hardware.org/?probe=14d23344e2) | Jul 17, 2022 |
| HP            | ProBook 4441s               | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| Digibras      | NH4CU03                     | [803b7d3211](https://linux-hardware.org/?probe=803b7d3211) | Jul 16, 2022 |
| Sony          | VPCEA3M1R                   | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| Digibras      | NH4CU53                     | [f6b402afe8](https://linux-hardware.org/?probe=f6b402afe8) | Jul 16, 2022 |
| MSI           | GP62 6QE                    | [7e7c05c6b6](https://linux-hardware.org/?probe=7e7c05c6b6) | Jul 16, 2022 |
| Acer          | Nitro AN517-54              | [68f6109054](https://linux-hardware.org/?probe=68f6109054) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [eb5b940f17](https://linux-hardware.org/?probe=eb5b940f17) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| HP            | ProBook 4545s               | [12575a32d1](https://linux-hardware.org/?probe=12575a32d1) | Jul 15, 2022 |
| MSI           | GE72 6QL                    | [7c22c38989](https://linux-hardware.org/?probe=7c22c38989) | Jul 15, 2022 |
| Dell          | Latitude E6530              | [67eec0ba19](https://linux-hardware.org/?probe=67eec0ba19) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [7e9ba006f3](https://linux-hardware.org/?probe=7e9ba006f3) | Jul 15, 2022 |
| HP            | Pavilion dv7                | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| HP            | Pavilion dv6700             | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| ASUSTek       | UX301LA                     | [3d4655e7cf](https://linux-hardware.org/?probe=3d4655e7cf) | Jul 14, 2022 |
| Purism        | Librem 14                   | [5a0337506b](https://linux-hardware.org/?probe=5a0337506b) | Jul 14, 2022 |
| Notebook      | NL40_50GU                   | [d4e652dc65](https://linux-hardware.org/?probe=d4e652dc65) | Jul 13, 2022 |
| Toshiba       | Satellite Pro R50-C         | [25d6e4de23](https://linux-hardware.org/?probe=25d6e4de23) | Jul 13, 2022 |
| HP            | Dev One Notebook PC         | [24c64c6221](https://linux-hardware.org/?probe=24c64c6221) | Jul 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Predator PH315-51           | [37b04a8093](https://linux-hardware.org/?probe=37b04a8093) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [b0b89af62e](https://linux-hardware.org/?probe=b0b89af62e) | Jul 12, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [bbb311969a](https://linux-hardware.org/?probe=bbb311969a) | Jul 12, 2022 |
| Lenovo        | G575 4383                   | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1599e9e013](https://linux-hardware.org/?probe=1599e9e013) | Jul 11, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [d088d6021c](https://linux-hardware.org/?probe=d088d6021c) | Jul 11, 2022 |
| Apple         | MacBookAir3,2               | [e3f89d4d16](https://linux-hardware.org/?probe=e3f89d4d16) | Jul 10, 2022 |
| HP            | Laptop 15-dy1xxx            | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Acer          | Aspire A515-44              | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| Acer          | Swift SF114-34              | [cf0d8e217c](https://linux-hardware.org/?probe=cf0d8e217c) | Jul 09, 2022 |
| Lenovo        | V15-ADA 82C7                | [3324f369f7](https://linux-hardware.org/?probe=3324f369f7) | Jul 09, 2022 |
| Lenovo        | G40-30 80FY                 | [35d55776f6](https://linux-hardware.org/?probe=35d55776f6) | Jul 09, 2022 |
| Framework     | Laptop                      | [09fa73cc57](https://linux-hardware.org/?probe=09fa73cc57) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| HP            | ProBook 4510s               | [ae51b4e466](https://linux-hardware.org/?probe=ae51b4e466) | Jul 08, 2022 |
| ASUSTek       | S551LN                      | [1e64e5d64e](https://linux-hardware.org/?probe=1e64e5d64e) | Jul 08, 2022 |
| HP            | Notebook                    | [0dc44e8da9](https://linux-hardware.org/?probe=0dc44e8da9) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4f02f261b3](https://linux-hardware.org/?probe=4f02f261b3) | Jul 08, 2022 |
| Toshiba       | Satellite C75D-B            | [3624ac1024](https://linux-hardware.org/?probe=3624ac1024) | Jul 08, 2022 |
| Acer          | Aspire ES1-512              | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| HP            | EliteBook 8460p             | [4f0cf74fe4](https://linux-hardware.org/?probe=4f0cf74fe4) | Jul 07, 2022 |
| HP            | ProBook 4310s               | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| ASUSTek       | GL553VD                     | [6b5e1735a7](https://linux-hardware.org/?probe=6b5e1735a7) | Jul 07, 2022 |
| HP            | G56                         | [5c38722298](https://linux-hardware.org/?probe=5c38722298) | Jul 07, 2022 |
| Acer          | Aspire V3-471               | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0KE0... | [2d63b4ba76](https://linux-hardware.org/?probe=2d63b4ba76) | Jul 06, 2022 |
| Unknown       | Unknown                     | [e4a8ad0984](https://linux-hardware.org/?probe=e4a8ad0984) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [498f4edafb](https://linux-hardware.org/?probe=498f4edafb) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Acer          | Aspire 3100                 | [1264fab131](https://linux-hardware.org/?probe=1264fab131) | Jul 05, 2022 |
| HP            | Compaq CQ58                 | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| HP            | EliteBook 8570p             | [8782b09be9](https://linux-hardware.org/?probe=8782b09be9) | Jul 05, 2022 |
| Dell          | Inspiron 14-3467            | [b9a61ec06d](https://linux-hardware.org/?probe=b9a61ec06d) | Jul 05, 2022 |
| HP            | Laptop 15-da0xxx            | [5c39c57896](https://linux-hardware.org/?probe=5c39c57896) | Jul 04, 2022 |
| ASUSTek       | GL703VD                     | [dc966787de](https://linux-hardware.org/?probe=dc966787de) | Jul 04, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Pavilion dv4                | [d40a5bd13e](https://linux-hardware.org/?probe=d40a5bd13e) | Jul 04, 2022 |
| Dell          | Latitude E7450              | [6dc8d46993](https://linux-hardware.org/?probe=6dc8d46993) | Jul 02, 2022 |
| Dell          | Precision M6800             | [ba446bde45](https://linux-hardware.org/?probe=ba446bde45) | Jul 02, 2022 |
| Samsung       | 300E5M/300E5L               | [497939c649](https://linux-hardware.org/?probe=497939c649) | Jul 02, 2022 |
| Samsung       | Q210/P210                   | [dfc97062be](https://linux-hardware.org/?probe=dfc97062be) | Jul 01, 2022 |
| Acer          | Extensa 5220                | [1ee1e31b52](https://linux-hardware.org/?probe=1ee1e31b52) | Jul 01, 2022 |
| Apple         | MacBookPro8,1               | [88e0a63fab](https://linux-hardware.org/?probe=88e0a63fab) | Jun 30, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| Dell          | Precision M6800             | [1eccdbb04e](https://linux-hardware.org/?probe=1eccdbb04e) | Jun 30, 2022 |
| Acer          | Aspire 5735                 | [b930fd3fcd](https://linux-hardware.org/?probe=b930fd3fcd) | Jun 29, 2022 |
| Dell          | Precision M6800             | [5b30cb4b9a](https://linux-hardware.org/?probe=5b30cb4b9a) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| HP            | Compaq CQ45                 | [74948790d0](https://linux-hardware.org/?probe=74948790d0) | Jun 29, 2022 |
| Dell          | Precision M6800             | [49b1b7edec](https://linux-hardware.org/?probe=49b1b7edec) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ed40a2bae5](https://linux-hardware.org/?probe=ed40a2bae5) | Jun 28, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [a767fd4cb1](https://linux-hardware.org/?probe=a767fd4cb1) | Jun 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [6932a00eed](https://linux-hardware.org/?probe=6932a00eed) | Jun 28, 2022 |
| Lenovo        | Z40-75 80DW                 | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| Acer          | Aspire A515-41G             | [cbb6f48321](https://linux-hardware.org/?probe=cbb6f48321) | Jun 27, 2022 |
| Dell          | Latitude E6430              | [76c22c2645](https://linux-hardware.org/?probe=76c22c2645) | Jun 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [240018e48a](https://linux-hardware.org/?probe=240018e48a) | Jun 26, 2022 |
| Lenovo        | S20-30 Touch 20434          | [b4ebe70967](https://linux-hardware.org/?probe=b4ebe70967) | Jun 26, 2022 |
| Toshiba       | Satellite C855-2CF          | [9e062a8425](https://linux-hardware.org/?probe=9e062a8425) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| Toshiba       | Satellite C660D             | [fc25883979](https://linux-hardware.org/?probe=fc25883979) | Jun 25, 2022 |
| ASUSTek       | X555QG                      | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASUSTek       | X551MA                      | [e5780aff8c](https://linux-hardware.org/?probe=e5780aff8c) | Jun 24, 2022 |
| Dell          | Latitude 3420               | [027b943645](https://linux-hardware.org/?probe=027b943645) | Jun 24, 2022 |
| ASUSTek       | N61Vn                       | [72d62f755d](https://linux-hardware.org/?probe=72d62f755d) | Jun 24, 2022 |
| HP            | ZBook 15 G2                 | [cfa8a05299](https://linux-hardware.org/?probe=cfa8a05299) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Latitude E5570              | [7f3b4b77f7](https://linux-hardware.org/?probe=7f3b4b77f7) | Jun 23, 2022 |
| Shuttle       | DS47D                       | [685a228ad8](https://linux-hardware.org/?probe=685a228ad8) | Jun 23, 2022 |
| Acer          | Aspire E1-531               | [415b93724e](https://linux-hardware.org/?probe=415b93724e) | Jun 22, 2022 |
| Dell          | Latitude 3300               | [5275529516](https://linux-hardware.org/?probe=5275529516) | Jun 22, 2022 |
| HP            | Spectre x2 Detachable       | [f42403915a](https://linux-hardware.org/?probe=f42403915a) | Jun 22, 2022 |
| eMachines     | E527                        | [a987a6cac2](https://linux-hardware.org/?probe=a987a6cac2) | Jun 22, 2022 |
| Dell          | Vostro 15 3515              | [f8a037663f](https://linux-hardware.org/?probe=f8a037663f) | Jun 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| HP            | Laptop 15-bs1xx             | [11f173103f](https://linux-hardware.org/?probe=11f173103f) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Acer          | Extensa 5635ZG              | [d1c48399ae](https://linux-hardware.org/?probe=d1c48399ae) | Jun 20, 2022 |
| Dell          | Latitude 3190               | [14521bc3eb](https://linux-hardware.org/?probe=14521bc3eb) | Jun 20, 2022 |
| HP            | Laptop 17-by4xxx            | [13fd86fd67](https://linux-hardware.org/?probe=13fd86fd67) | Jun 20, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Acer          | Swift SF314-41              | [735d7a92b5](https://linux-hardware.org/?probe=735d7a92b5) | Jun 18, 2022 |
| HP            | Laptop 14-fq0xxx            | [bc61209d78](https://linux-hardware.org/?probe=bc61209d78) | Jun 18, 2022 |
| Dell          | Latitude 3380               | [0ccd773de6](https://linux-hardware.org/?probe=0ccd773de6) | Jun 17, 2022 |
| Lenovo        | ThinkPad T460s 20FAS76R0... | [21d6816b13](https://linux-hardware.org/?probe=21d6816b13) | Jun 17, 2022 |
| Dell          | Latitude 3420               | [178e3cbcba](https://linux-hardware.org/?probe=178e3cbcba) | Jun 17, 2022 |
| Dell          | Latitude 3300               | [ed133c13de](https://linux-hardware.org/?probe=ed133c13de) | Jun 17, 2022 |
| Dell          | Latitude 3310               | [4715235090](https://linux-hardware.org/?probe=4715235090) | Jun 17, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| Acer          | Aspire A515-44              | [5da40d4fd6](https://linux-hardware.org/?probe=5da40d4fd6) | Jun 16, 2022 |
| Dell          | Latitude 3310               | [549b7595b7](https://linux-hardware.org/?probe=549b7595b7) | Jun 16, 2022 |
| ASUSTek       | ET2040I                     | [45273f0675](https://linux-hardware.org/?probe=45273f0675) | Jun 15, 2022 |
| Unknown       | Unknown                     | [00090936e8](https://linux-hardware.org/?probe=00090936e8) | Jun 15, 2022 |
| HP            | Laptop 14-fq0xxx            | [d7cccd8f1d](https://linux-hardware.org/?probe=d7cccd8f1d) | Jun 14, 2022 |
| HP            | Compaq Presario CQ41        | [95ffc69f82](https://linux-hardware.org/?probe=95ffc69f82) | Jun 14, 2022 |
| Acer          | AO722                       | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| Dell          | Latitude E5450              | [b8d806d8a4](https://linux-hardware.org/?probe=b8d806d8a4) | Jun 13, 2022 |
| ASUSTek       | N53SV                       | [fa9f250b51](https://linux-hardware.org/?probe=fa9f250b51) | Jun 13, 2022 |
| TUXEDO        | Unknown                     | [c351e553d3](https://linux-hardware.org/?probe=c351e553d3) | Jun 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b65abaf14a](https://linux-hardware.org/?probe=b65abaf14a) | Jun 12, 2022 |
| Dell          | Inspiron N4050              | [32f413134f](https://linux-hardware.org/?probe=32f413134f) | Jun 12, 2022 |
| ASUSTek       | X553MA                      | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Acer          | Aspire ES1-523              | [89fbabafb5](https://linux-hardware.org/?probe=89fbabafb5) | Jun 12, 2022 |
| Fujitsu Si... | AMILO Li3910                | [4abeebc707](https://linux-hardware.org/?probe=4abeebc707) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| Dell          | Vostro 3500                 | [1eda18f249](https://linux-hardware.org/?probe=1eda18f249) | Jun 12, 2022 |
| HP            | Pavilion dv6                | [0bf35c5293](https://linux-hardware.org/?probe=0bf35c5293) | Jun 11, 2022 |
| Dell          | Latitude E6410              | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| HP            | ProBook 450 G0              | [2d87379b89](https://linux-hardware.org/?probe=2d87379b89) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| HUAWEI        | HN-WX9X                     | [d57d295c58](https://linux-hardware.org/?probe=d57d295c58) | Jun 10, 2022 |
| Dell          | Latitude 5290               | [930e34a606](https://linux-hardware.org/?probe=930e34a606) | Jun 10, 2022 |
| HP            | Pavilion g6                 | [63dcba0c57](https://linux-hardware.org/?probe=63dcba0c57) | Jun 10, 2022 |
| Dell          | Latitude E5550              | [95baf2f400](https://linux-hardware.org/?probe=95baf2f400) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Dell          | Inspiron 1545               | [7ed42ed0a1](https://linux-hardware.org/?probe=7ed42ed0a1) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ff7b51ffc8](https://linux-hardware.org/?probe=ff7b51ffc8) | Jun 08, 2022 |
| HP            | ProBook 640 G1              | [34ecb184f9](https://linux-hardware.org/?probe=34ecb184f9) | Jun 08, 2022 |
| Sony          | VGN-Z71JB                   | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 2767AL9       | [8084a9ed95](https://linux-hardware.org/?probe=8084a9ed95) | Jun 08, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c6975f2914](https://linux-hardware.org/?probe=c6975f2914) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [a610c5537a](https://linux-hardware.org/?probe=a610c5537a) | Jun 07, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [cc464203ff](https://linux-hardware.org/?probe=cc464203ff) | Jun 07, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4eb8e0924d](https://linux-hardware.org/?probe=4eb8e0924d) | Jun 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| HP            | Laptop 14-fq0xxx            | [d88feaaf5e](https://linux-hardware.org/?probe=d88feaaf5e) | Jun 06, 2022 |
| Unknown       | Unknown                     | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| DNS           | MB50II1                     | [b4882bff99](https://linux-hardware.org/?probe=b4882bff99) | Jun 06, 2022 |
| HP            | ProBook 4530s               | [0ff1032a69](https://linux-hardware.org/?probe=0ff1032a69) | Jun 06, 2022 |
| Alienware     | 13 R3                       | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| TUXEDO        | Unknown                     | [ef40511693](https://linux-hardware.org/?probe=ef40511693) | Jun 05, 2022 |
| Dell          | Inspiron 15 3511            | [8f0924eb80](https://linux-hardware.org/?probe=8f0924eb80) | Jun 05, 2022 |
| Acer          | Aspire ES1-572              | [9c48d4f977](https://linux-hardware.org/?probe=9c48d4f977) | Jun 05, 2022 |
| AZW           | GT-R                        | [d86ab00f24](https://linux-hardware.org/?probe=d86ab00f24) | Jun 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ff882995b0](https://linux-hardware.org/?probe=ff882995b0) | Jun 05, 2022 |
| Dell          | Latitude D630               | [fb28805860](https://linux-hardware.org/?probe=fb28805860) | Jun 05, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| Dell          | Latitude E7450              | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| HYPA          | FLUX                        | [76b0337ef8](https://linux-hardware.org/?probe=76b0337ef8) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| HP            | Laptop 14-fq0xxx            | [3ebcdc19fa](https://linux-hardware.org/?probe=3ebcdc19fa) | Jun 04, 2022 |
| Acer          | Swift SF314-41G             | [aad6ae85d1](https://linux-hardware.org/?probe=aad6ae85d1) | Jun 04, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Sony          | VPCSB4AFX                   | [b676e37b94](https://linux-hardware.org/?probe=b676e37b94) | Jun 04, 2022 |
| Dell          | Latitude 3189               | [f1899ceede](https://linux-hardware.org/?probe=f1899ceede) | Jun 03, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [e073539ce5](https://linux-hardware.org/?probe=e073539ce5) | Jun 02, 2022 |
| Acer          | AO722                       | [73850c23ac](https://linux-hardware.org/?probe=73850c23ac) | Jun 02, 2022 |
| LG Electro... | 15Z970-E.BH71P1             | [3b5f142164](https://linux-hardware.org/?probe=3b5f142164) | Jun 02, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [a27fbb040b](https://linux-hardware.org/?probe=a27fbb040b) | Jun 02, 2022 |
| Acer          | AOD260                      | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [ee8d9751b0](https://linux-hardware.org/?probe=ee8d9751b0) | Jun 01, 2022 |
| Lenovo        | Yoga 2 11 20332             | [ad92325747](https://linux-hardware.org/?probe=ad92325747) | Jun 01, 2022 |
| Lenovo        | IdeaPad S300 20197          | [fcb07ac9aa](https://linux-hardware.org/?probe=fcb07ac9aa) | May 31, 2022 |
| HYPA          | FLUX                        | [8a69e3a34e](https://linux-hardware.org/?probe=8a69e3a34e) | May 31, 2022 |
| Philco        | 10D                         | [b4fc893791](https://linux-hardware.org/?probe=b4fc893791) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| Dell          | Vostro 5468                 | [551400dba1](https://linux-hardware.org/?probe=551400dba1) | May 29, 2022 |
| System76      | Lemur Pro                   | [4a6174b7a4](https://linux-hardware.org/?probe=4a6174b7a4) | May 29, 2022 |
| Toshiba       | Satellite C850-1KN          | [60b2c12831](https://linux-hardware.org/?probe=60b2c12831) | May 29, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [8e577a4a1a](https://linux-hardware.org/?probe=8e577a4a1a) | May 29, 2022 |
| AZW           | GT-R                        | [7823df6a86](https://linux-hardware.org/?probe=7823df6a86) | May 29, 2022 |
| Acer          | Aspire 4349                 | [3d1051c72e](https://linux-hardware.org/?probe=3d1051c72e) | May 29, 2022 |
| TUXEDO        | Unknown                     | [6bda60151b](https://linux-hardware.org/?probe=6bda60151b) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [d1c3a33e75](https://linux-hardware.org/?probe=d1c3a33e75) | May 28, 2022 |
| Dell          | Inspiron 15-3567            | [ba66fccfa1](https://linux-hardware.org/?probe=ba66fccfa1) | May 28, 2022 |
| Lenovo        | G50-70 20351                | [1150f03cf0](https://linux-hardware.org/?probe=1150f03cf0) | May 28, 2022 |
| ASUSTek       | Strix 17 GL703GE            | [5d5ba64239](https://linux-hardware.org/?probe=5d5ba64239) | May 28, 2022 |
| HP            | EliteBook 840 G2            | [eeab3d23c4](https://linux-hardware.org/?probe=eeab3d23c4) | May 27, 2022 |
| TUXEDO        | Unknown                     | [2d5566dd3f](https://linux-hardware.org/?probe=2d5566dd3f) | May 27, 2022 |
| Apple         | MacBookPro5,5               | [75eebad111](https://linux-hardware.org/?probe=75eebad111) | May 27, 2022 |
| ASUSTek       | U31Jg                       | [b761173e5e](https://linux-hardware.org/?probe=b761173e5e) | May 26, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [36d7baa56d](https://linux-hardware.org/?probe=36d7baa56d) | May 26, 2022 |
| Dell          | Latitude E5410              | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-571               | [b43bf0505e](https://linux-hardware.org/?probe=b43bf0505e) | May 25, 2022 |
| HP            | Pavilion g4                 | [0c943e458a](https://linux-hardware.org/?probe=0c943e458a) | May 25, 2022 |
| ASUSTek       | X540LJ                      | [dbbcdcd2b5](https://linux-hardware.org/?probe=dbbcdcd2b5) | May 25, 2022 |
| Lenovo        | ThinkPad W520 428223G       | [5672a27a7e](https://linux-hardware.org/?probe=5672a27a7e) | May 24, 2022 |
| HP            | 255 G3                      | [a6e7ea804b](https://linux-hardware.org/?probe=a6e7ea804b) | May 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [4a88ea0c1f](https://linux-hardware.org/?probe=4a88ea0c1f) | May 24, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Acer          | Aspire E5-411               | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Compaq 15                   | [262d99131a](https://linux-hardware.org/?probe=262d99131a) | May 23, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [db944454c8](https://linux-hardware.org/?probe=db944454c8) | May 23, 2022 |
| HP            | 240 G7                      | [687546391a](https://linux-hardware.org/?probe=687546391a) | May 23, 2022 |
| HP            | ProBook 6475b               | [5202cf8c75](https://linux-hardware.org/?probe=5202cf8c75) | May 23, 2022 |
| Toshiba       | Satellite A100              | [a789d51565](https://linux-hardware.org/?probe=a789d51565) | May 23, 2022 |
| HP            | Laptop 14-dk1xxx            | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| Acer          | Aspire E1-530               | [48747611a5](https://linux-hardware.org/?probe=48747611a5) | May 22, 2022 |
| MSI           | GF63 Thin 8RCS              | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| Dell          | Latitude E6320              | [7f2af32493](https://linux-hardware.org/?probe=7f2af32493) | May 21, 2022 |
| Unknown       | Unknown                     | [261a0bf179](https://linux-hardware.org/?probe=261a0bf179) | May 21, 2022 |
| Lenovo        | Z50-75 80EC                 | [adddbe7947](https://linux-hardware.org/?probe=adddbe7947) | May 21, 2022 |
| Lenovo        | G50-70 20351                | [b6f469418c](https://linux-hardware.org/?probe=b6f469418c) | May 21, 2022 |
| Medion        | P6624                       | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1c63e5e513](https://linux-hardware.org/?probe=1c63e5e513) | May 21, 2022 |
| Lenovo        | Z710 20250                  | [ce719211e5](https://linux-hardware.org/?probe=ce719211e5) | May 21, 2022 |
| ASUSTek       | F7L                         | [f5bcd583ac](https://linux-hardware.org/?probe=f5bcd583ac) | May 21, 2022 |
| ASUSTek       | K73SD                       | [8c77e10639](https://linux-hardware.org/?probe=8c77e10639) | May 21, 2022 |
| Notebook      | N8xxEP6                     | [ae2202ea9e](https://linux-hardware.org/?probe=ae2202ea9e) | May 21, 2022 |
| ASUSTek       | K42Jc                       | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Acer          | Aspire 7750G                | [0fd6c8569c](https://linux-hardware.org/?probe=0fd6c8569c) | May 20, 2022 |
| Positivo      | S15KL                       | [71fffe977a](https://linux-hardware.org/?probe=71fffe977a) | May 20, 2022 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | [a3e1bf045d](https://linux-hardware.org/?probe=a3e1bf045d) | May 20, 2022 |
| Acer          | Aspire A314-22              | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Dell          | Inspiron 3502               | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| Dell          | Inspiron 5520               | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| Lenovo        | V15-ADA 82C7                | [b42178398a](https://linux-hardware.org/?probe=b42178398a) | May 19, 2022 |
| Compaq        | Presario CQ-25              | [4412b90950](https://linux-hardware.org/?probe=4412b90950) | May 19, 2022 |
| Dell          | Latitude 7400               | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Positivo      | Mobile                      | [1ef43bb988](https://linux-hardware.org/?probe=1ef43bb988) | May 19, 2022 |
| Dell          | Inspiron 3437               | [fcd1a7ae14](https://linux-hardware.org/?probe=fcd1a7ae14) | May 19, 2022 |
| Sony          | VGN-NR32L_S                 | [2709583292](https://linux-hardware.org/?probe=2709583292) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a18c103de9](https://linux-hardware.org/?probe=a18c103de9) | May 18, 2022 |
| ASUSTek       | UX305FA                     | [5ec0821cdf](https://linux-hardware.org/?probe=5ec0821cdf) | May 18, 2022 |
| ASUSTek       | 1015PE                      | [3ca5e4d427](https://linux-hardware.org/?probe=3ca5e4d427) | May 18, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [3b3d6ba1e3](https://linux-hardware.org/?probe=3b3d6ba1e3) | May 18, 2022 |
| Dell          | Latitude E7450              | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| HP            | EliteBook 8570p             | [703787dd00](https://linux-hardware.org/?probe=703787dd00) | May 17, 2022 |
| Toshiba       | Satellite L350D             | [ff1e87338a](https://linux-hardware.org/?probe=ff1e87338a) | May 17, 2022 |
| Dell          | Studio 1555                 | [2f84ca8885](https://linux-hardware.org/?probe=2f84ca8885) | May 17, 2022 |
| Toshiba       | Satellite C850              | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| Dell          | Inspiron 3459               | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude E6400              | [d89696196c](https://linux-hardware.org/?probe=d89696196c) | May 16, 2022 |
| Lenovo        | ThinkPad T530 23594LU       | [cbed91f90e](https://linux-hardware.org/?probe=cbed91f90e) | May 16, 2022 |
| Sony          | VPCCB3S1E                   | [e6451d9a9a](https://linux-hardware.org/?probe=e6451d9a9a) | May 15, 2022 |
| Dell          | Inspiron 1750               | [b37b4cdbbb](https://linux-hardware.org/?probe=b37b4cdbbb) | May 15, 2022 |
| Dell          | Inspiron 3520               | [a045c6d50f](https://linux-hardware.org/?probe=a045c6d50f) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [8586a581d0](https://linux-hardware.org/?probe=8586a581d0) | May 15, 2022 |
| Packard Be... | EasyNote ENTF71BM           | [e8808a770a](https://linux-hardware.org/?probe=e8808a770a) | May 14, 2022 |
| Lenovo        | ThinkPad T410 2522W6S       | [79cd5bf620](https://linux-hardware.org/?probe=79cd5bf620) | May 14, 2022 |
| Dell          | Studio 1558                 | [ccffb59f97](https://linux-hardware.org/?probe=ccffb59f97) | May 13, 2022 |
| Dell          | Precision M2800             | [266af2c2b7](https://linux-hardware.org/?probe=266af2c2b7) | May 13, 2022 |
| Lenovo        | B70-80 80MR                 | [73a1a28362](https://linux-hardware.org/?probe=73a1a28362) | May 12, 2022 |
| Lenovo        | ThinkPad T510 43147UG       | [e4f5ef2c77](https://linux-hardware.org/?probe=e4f5ef2c77) | May 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [ed11a30da0](https://linux-hardware.org/?probe=ed11a30da0) | May 12, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Samsung       | R519/R719                   | [8deee99c2d](https://linux-hardware.org/?probe=8deee99c2d) | May 11, 2022 |
| Compaq        | 420                         | [1525a9b616](https://linux-hardware.org/?probe=1525a9b616) | May 10, 2022 |
| Alienware     | 17                          | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ee9f39e915](https://linux-hardware.org/?probe=ee9f39e915) | May 10, 2022 |
| Acer          | AO722                       | [645156f92d](https://linux-hardware.org/?probe=645156f92d) | May 10, 2022 |
| Apple         | MacBookPro7,1               | [e2430a36a4](https://linux-hardware.org/?probe=e2430a36a4) | May 09, 2022 |
| Fujitsu       | FMVNTCAKB                   | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | [324d23305d](https://linux-hardware.org/?probe=324d23305d) | May 09, 2022 |
| Dell          | Latitude E6410              | [0cac068895](https://linux-hardware.org/?probe=0cac068895) | May 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [877b9a8dea](https://linux-hardware.org/?probe=877b9a8dea) | May 08, 2022 |
| Dell          | Latitude E6220              | [f5ba7cbb31](https://linux-hardware.org/?probe=f5ba7cbb31) | May 08, 2022 |
| Lenovo        | ThinkPad T530 24296G9       | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| ASUSTek       | N501VW                      | [71d02059fa](https://linux-hardware.org/?probe=71d02059fa) | May 06, 2022 |
| Dell          | Latitude 3120               | [0da044ae6c](https://linux-hardware.org/?probe=0da044ae6c) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Compaq 15                   | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a49301cdaf](https://linux-hardware.org/?probe=a49301cdaf) | May 05, 2022 |
| Toshiba       | Satellite C670D             | [3eedd8ce6b](https://linux-hardware.org/?probe=3eedd8ce6b) | May 05, 2022 |
| ASUSTek       | X551MA                      | [4a12d6b5d9](https://linux-hardware.org/?probe=4a12d6b5d9) | May 05, 2022 |
| Dell          | Latitude E7440              | [8496c35f54](https://linux-hardware.org/?probe=8496c35f54) | May 05, 2022 |
| Apple         | MacBookAir7,2               | [c08ef3e666](https://linux-hardware.org/?probe=c08ef3e666) | May 04, 2022 |
| HP            | ProBook 470 G0              | [17a1e97761](https://linux-hardware.org/?probe=17a1e97761) | May 04, 2022 |
| ASUSTek       | X75A1                       | [78e4325ae6](https://linux-hardware.org/?probe=78e4325ae6) | May 04, 2022 |
| HP            | ProBook 6560b               | [10ed31948a](https://linux-hardware.org/?probe=10ed31948a) | May 04, 2022 |
| Lenovo        | IdeaPad Z370                | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| HP            | Compaq CQ58                 | [e42824ac37](https://linux-hardware.org/?probe=e42824ac37) | May 03, 2022 |
| Dell          | Latitude E7470              | [7991dfd7a5](https://linux-hardware.org/?probe=7991dfd7a5) | May 03, 2022 |
| Lenovo        | ThinkPad R500 27326FG       | [1ed6992177](https://linux-hardware.org/?probe=1ed6992177) | May 03, 2022 |
| Dell          | Latitude 3310               | [2b74207996](https://linux-hardware.org/?probe=2b74207996) | May 02, 2022 |
| Acer          | Nitro AN515-45              | [8115992c41](https://linux-hardware.org/?probe=8115992c41) | May 02, 2022 |
| HP            | 255 G1                      | [48c43a229d](https://linux-hardware.org/?probe=48c43a229d) | May 01, 2022 |
| Lenovo        | G710 20252                  | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Sony          | VGN-FZ31Z                   | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | Pavilion g6                 | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| Dell          | Latitude E5550              | [42a576bd39](https://linux-hardware.org/?probe=42a576bd39) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| Dell          | Inspiron 3793               | [9d2383d1f8](https://linux-hardware.org/?probe=9d2383d1f8) | Apr 30, 2022 |
| HP            | 650                         | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Dell          | Latitude 3330               | [1843c62895](https://linux-hardware.org/?probe=1843c62895) | Apr 30, 2022 |
| Lenovo        | Z50-70 20354                | [f253fe8221](https://linux-hardware.org/?probe=f253fe8221) | Apr 30, 2022 |
| Apple         | MacBookAir5,1               | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Philco        | 14I                         | [03bb0fdeef](https://linux-hardware.org/?probe=03bb0fdeef) | Apr 30, 2022 |
| HP            | Laptop 17-by4xxx            | [767590ac38](https://linux-hardware.org/?probe=767590ac38) | Apr 29, 2022 |
| ASUSTek       | S551LN                      | [a5f0e1cee7](https://linux-hardware.org/?probe=a5f0e1cee7) | Apr 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2c8a1c2444](https://linux-hardware.org/?probe=2c8a1c2444) | Apr 29, 2022 |
| TUXEDO        | Book BM15 Gen10             | [45b5b1bba9](https://linux-hardware.org/?probe=45b5b1bba9) | Apr 29, 2022 |
| Dell          | Inspiron 3593               | [54087491d8](https://linux-hardware.org/?probe=54087491d8) | Apr 28, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HUAWEI        | NBM-WXX9                    | [4f15ab06cc](https://linux-hardware.org/?probe=4f15ab06cc) | Apr 28, 2022 |
| Dell          | Latitude E4310              | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | X505BA                      | [30972759d1](https://linux-hardware.org/?probe=30972759d1) | Apr 27, 2022 |
| Notebook      | W130SV                      | [a88535a3a5](https://linux-hardware.org/?probe=a88535a3a5) | Apr 27, 2022 |
| Positivo      | S14SL01                     | [f8bdbe707d](https://linux-hardware.org/?probe=f8bdbe707d) | Apr 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [14f1d071ae](https://linux-hardware.org/?probe=14f1d071ae) | Apr 26, 2022 |
| HP            | ZBook 17 G3                 | [133232a304](https://linux-hardware.org/?probe=133232a304) | Apr 26, 2022 |
| Intel         | Unknown                     | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [64cd863479](https://linux-hardware.org/?probe=64cd863479) | Apr 26, 2022 |
| Medion        | S17402 MD63000              | [fe73d0023a](https://linux-hardware.org/?probe=fe73d0023a) | Apr 25, 2022 |
| Dell          | Latitude E6410              | [bc9515e4a7](https://linux-hardware.org/?probe=bc9515e4a7) | Apr 25, 2022 |
| Dell          | Inspiron 3537               | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| Dell          | Latitude E7270              | [d8dedbd4f6](https://linux-hardware.org/?probe=d8dedbd4f6) | Apr 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [7423afe5a1](https://linux-hardware.org/?probe=7423afe5a1) | Apr 25, 2022 |
| Dell          | Inspiron 7460               | [6a67f6de58](https://linux-hardware.org/?probe=6a67f6de58) | Apr 25, 2022 |
| Fujitsu       | FMVA06004                   | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [2fcb2f9b19](https://linux-hardware.org/?probe=2fcb2f9b19) | Apr 24, 2022 |
| Lenovo        | ThinkPad W520 4284BL9       | [a7dd5a566e](https://linux-hardware.org/?probe=a7dd5a566e) | Apr 24, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | [6748d74892](https://linux-hardware.org/?probe=6748d74892) | Apr 24, 2022 |
| Lenovo        | ThinkPad E460 20ET000YLM    | [c82beac367](https://linux-hardware.org/?probe=c82beac367) | Apr 23, 2022 |
| ASUSTek       | X705UQR                     | [e4a27bf740](https://linux-hardware.org/?probe=e4a27bf740) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3e3f727deb](https://linux-hardware.org/?probe=3e3f727deb) | Apr 23, 2022 |
| Acer          | Aspire V5-571G              | [e76a1e5467](https://linux-hardware.org/?probe=e76a1e5467) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad X220 42875TU       | [2dd8baa591](https://linux-hardware.org/?probe=2dd8baa591) | Apr 23, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [7988499108](https://linux-hardware.org/?probe=7988499108) | Apr 23, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| HP            | Pavilion 15                 | [a1b094c360](https://linux-hardware.org/?probe=a1b094c360) | Apr 22, 2022 |
| Acer          | Aspire A515-54G             | [9eeb0ced39](https://linux-hardware.org/?probe=9eeb0ced39) | Apr 22, 2022 |
| Dell          | Precision 3560              | [cc7a9c5fe2](https://linux-hardware.org/?probe=cc7a9c5fe2) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| Dell          | Inspiron 1545               | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| Toshiba       | Satellite C850-A786         | [e57aca482e](https://linux-hardware.org/?probe=e57aca482e) | Apr 22, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| Apple         | MacBookAir4,2               | [1535fd1e85](https://linux-hardware.org/?probe=1535fd1e85) | Apr 21, 2022 |
| Dell          | Latitude 3310               | [3130a4d7c3](https://linux-hardware.org/?probe=3130a4d7c3) | Apr 21, 2022 |
| Acer          | Aspire E5-551G              | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| Philco        | Unknown                     | [16719246ff](https://linux-hardware.org/?probe=16719246ff) | Apr 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [9adfada605](https://linux-hardware.org/?probe=9adfada605) | Apr 20, 2022 |
| Dell          | G3 3579                     | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b1eb98dd6a](https://linux-hardware.org/?probe=b1eb98dd6a) | Apr 19, 2022 |
| Toshiba       | dynabook Satellite B552/... | [60e6d780aa](https://linux-hardware.org/?probe=60e6d780aa) | Apr 19, 2022 |
| Dell          | Latitude E5470              | [da9241c331](https://linux-hardware.org/?probe=da9241c331) | Apr 19, 2022 |
| HP            | Compaq 6720s                | [23c39d626c](https://linux-hardware.org/?probe=23c39d626c) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Acer          | Aspire E5-571G              | [f37cea6c6f](https://linux-hardware.org/?probe=f37cea6c6f) | Apr 18, 2022 |
| Toshiba       | Satellite P200              | [f7726b9903](https://linux-hardware.org/?probe=f7726b9903) | Apr 17, 2022 |
| HP            | Unknown                     | [7732ecb02d](https://linux-hardware.org/?probe=7732ecb02d) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| Dell          | Precision M6800             | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Dell          | Latitude E6320              | [84523d9bd9](https://linux-hardware.org/?probe=84523d9bd9) | Apr 16, 2022 |
| Acer          | Nitro AN517-41              | [e955d40057](https://linux-hardware.org/?probe=e955d40057) | Apr 16, 2022 |
| ASUSTek       | P52F                        | [0cb00534d0](https://linux-hardware.org/?probe=0cb00534d0) | Apr 16, 2022 |
| Acer          | Aspire R3-131T              | [776575ecdb](https://linux-hardware.org/?probe=776575ecdb) | Apr 16, 2022 |
| Gigabyte      | G5 GD                       | [2b2833576e](https://linux-hardware.org/?probe=2b2833576e) | Apr 16, 2022 |
| Acer          | Aspire 5750G                | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Acer          | Aspire 5735                 | [e43434e15c](https://linux-hardware.org/?probe=e43434e15c) | Apr 15, 2022 |
| Samsung       | 700T                        | [ff97fa9856](https://linux-hardware.org/?probe=ff97fa9856) | Apr 15, 2022 |
| Dell          | Latitude E6530              | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Sony          | VPCEE23FX                   | [4c7634a096](https://linux-hardware.org/?probe=4c7634a096) | Apr 15, 2022 |
| Fujitsu       | LIFEBOOK E743               | [43ee1b9237](https://linux-hardware.org/?probe=43ee1b9237) | Apr 14, 2022 |
| Sony          | VGN-FZ11M                   | [23731be3a1](https://linux-hardware.org/?probe=23731be3a1) | Apr 14, 2022 |
| HP            | ProBook 650 G5              | [db89b961c4](https://linux-hardware.org/?probe=db89b961c4) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Acer          | Aspire A717-71G             | [7bf2eeb5cc](https://linux-hardware.org/?probe=7bf2eeb5cc) | Apr 14, 2022 |
| Dell          | Latitude E6500              | [d88c77328a](https://linux-hardware.org/?probe=d88c77328a) | Apr 13, 2022 |
| Sony          | SVE1713A1EW                 | [fda4c51d3c](https://linux-hardware.org/?probe=fda4c51d3c) | Apr 13, 2022 |
| HP            | Pavilion dv6500             | [31d34f3d2d](https://linux-hardware.org/?probe=31d34f3d2d) | Apr 13, 2022 |
| Acer          | Aspire R3-131T              | [44a4c66cfe](https://linux-hardware.org/?probe=44a4c66cfe) | Apr 13, 2022 |
| Lenovo        | G405 20239                  | [ab55cb1e13](https://linux-hardware.org/?probe=ab55cb1e13) | Apr 13, 2022 |
| Acer          | Nitro AN515-41              | [b938e715f4](https://linux-hardware.org/?probe=b938e715f4) | Apr 13, 2022 |
| HP            | Laptop 15-db0xxx            | [5adcbc1b64](https://linux-hardware.org/?probe=5adcbc1b64) | Apr 13, 2022 |
| Samsung       | 750XDA                      | [e2c10772c0](https://linux-hardware.org/?probe=e2c10772c0) | Apr 13, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| Acer          | Extensa 5635Z               | [641be7bf1b](https://linux-hardware.org/?probe=641be7bf1b) | Apr 12, 2022 |
| HP            | Presario CQ57               | [ece28d4d57](https://linux-hardware.org/?probe=ece28d4d57) | Apr 12, 2022 |
| Positivo      | Mobile                      | [1bd294322c](https://linux-hardware.org/?probe=1bd294322c) | Apr 12, 2022 |
| Lenovo        | 3000 V200 076472G           | [11a06d9b03](https://linux-hardware.org/?probe=11a06d9b03) | Apr 10, 2022 |
| ASUSTek       | GL702VM                     | [70ff5129b4](https://linux-hardware.org/?probe=70ff5129b4) | Apr 10, 2022 |
| Apple         | MacBookPro9,2               | [9ec146cb7c](https://linux-hardware.org/?probe=9ec146cb7c) | Apr 10, 2022 |
| HP            | 15                          | [43254accc2](https://linux-hardware.org/?probe=43254accc2) | Apr 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [34b32b5b14](https://linux-hardware.org/?probe=34b32b5b14) | Apr 10, 2022 |
| Acer          | Aspire E5-575G              | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [eb69184ad7](https://linux-hardware.org/?probe=eb69184ad7) | Apr 10, 2022 |
| HP            | Notebook                    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| ASUSTek       | X555LJ                      | [e7e9bc2b60](https://linux-hardware.org/?probe=e7e9bc2b60) | Apr 09, 2022 |
| Apple         | MacBook5,1                  | [dc76bbdce6](https://linux-hardware.org/?probe=dc76bbdce6) | Apr 09, 2022 |
| Acer          | Aspire R3-131T              | [15f16fd968](https://linux-hardware.org/?probe=15f16fd968) | Apr 08, 2022 |
| HP            | ProBook 650 G1              | [a7d004962f](https://linux-hardware.org/?probe=a7d004962f) | Apr 08, 2022 |
| Apple         | MacBookPro9,2               | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| Dell          | Latitude E5500              | [485521f38b](https://linux-hardware.org/?probe=485521f38b) | Apr 08, 2022 |
| ASUSTek       | X541SA                      | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Acer          | Aspire A315-54              | [596a2a878c](https://linux-hardware.org/?probe=596a2a878c) | Apr 08, 2022 |
| Positivo      | NB50TH                      | [8b6dbaa2a6](https://linux-hardware.org/?probe=8b6dbaa2a6) | Apr 08, 2022 |
| Toshiba       | TECRA A10                   | [b062d23fb7](https://linux-hardware.org/?probe=b062d23fb7) | Apr 07, 2022 |
| Dell          | Latitude E4310              | [e89d84e0dd](https://linux-hardware.org/?probe=e89d84e0dd) | Apr 07, 2022 |
| HP            | Laptop 17-by0xxx            | [40d9656aec](https://linux-hardware.org/?probe=40d9656aec) | Apr 07, 2022 |
| ASUSTek       | X556UQ                      | [ee38be8ddd](https://linux-hardware.org/?probe=ee38be8ddd) | Apr 07, 2022 |
| HP            | Laptop 14q-cy0xxx           | [625bad986e](https://linux-hardware.org/?probe=625bad986e) | Apr 07, 2022 |
| Positivo      | S14SL01                     | [092f7c7d2b](https://linux-hardware.org/?probe=092f7c7d2b) | Apr 07, 2022 |
| HP            | 2000                        | [e4610bcc0e](https://linux-hardware.org/?probe=e4610bcc0e) | Apr 07, 2022 |
| ARKA          | BOOK                        | [44809cec7b](https://linux-hardware.org/?probe=44809cec7b) | Apr 06, 2022 |
| Toshiba       | Satellite A350D             | [ea021d7947](https://linux-hardware.org/?probe=ea021d7947) | Apr 06, 2022 |
| ASUSTek       | K52Jc                       | [645adad8a7](https://linux-hardware.org/?probe=645adad8a7) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Positivo B... | VJFE41F11X-XXXXXX           | [7ba2d85c09](https://linux-hardware.org/?probe=7ba2d85c09) | Apr 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3719a80289](https://linux-hardware.org/?probe=3719a80289) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Apple         | MacBookAir4,2               | [0c1f8b4efe](https://linux-hardware.org/?probe=0c1f8b4efe) | Apr 05, 2022 |
| Lenovo        | V145-15AST 81MT             | [ee0a7bc711](https://linux-hardware.org/?probe=ee0a7bc711) | Apr 05, 2022 |
| Dell          | Latitude 3189               | [326c734059](https://linux-hardware.org/?probe=326c734059) | Apr 05, 2022 |
| Dell          | Latitude 3310               | [69ee7c1eaf](https://linux-hardware.org/?probe=69ee7c1eaf) | Apr 05, 2022 |
| Philco        | 14H                         | [4408057803](https://linux-hardware.org/?probe=4408057803) | Apr 04, 2022 |
| Fujitsu       | LIFEBOOK S752               | [307e875610](https://linux-hardware.org/?probe=307e875610) | Apr 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [952a71b37e](https://linux-hardware.org/?probe=952a71b37e) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [4fdc33f1a2](https://linux-hardware.org/?probe=4fdc33f1a2) | Apr 04, 2022 |
| HP            | Pavilion 14                 | [136105017c](https://linux-hardware.org/?probe=136105017c) | Apr 04, 2022 |
| AWOW          | AK41                        | [f491f6f0fa](https://linux-hardware.org/?probe=f491f6f0fa) | Apr 04, 2022 |
| HP            | ProBook 450 G5              | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Dell          | Inspiron N5110              | [cd682e107d](https://linux-hardware.org/?probe=cd682e107d) | Apr 03, 2022 |
| Lenovo        | ThinkPad X100e 0022CTO      | [ad4b7e6509](https://linux-hardware.org/?probe=ad4b7e6509) | Apr 03, 2022 |
| Toshiba       | Satellite S855D             | [45b97d03ed](https://linux-hardware.org/?probe=45b97d03ed) | Apr 03, 2022 |
| Dell          | XPS 15 9510                 | [ca9b5c03cb](https://linux-hardware.org/?probe=ca9b5c03cb) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Dell          | Latitude E6420              | [41c4a5b886](https://linux-hardware.org/?probe=41c4a5b886) | Apr 02, 2022 |
| Fujitsu       | LIFEBOOK P701               | [5789c0842c](https://linux-hardware.org/?probe=5789c0842c) | Apr 02, 2022 |
| HP            | 255 G7 Notebook PC          | [a7d794c2d8](https://linux-hardware.org/?probe=a7d794c2d8) | Apr 02, 2022 |
| HP            | Elite x2 1012 G1            | [6c5dee9e74](https://linux-hardware.org/?probe=6c5dee9e74) | Apr 02, 2022 |
| Lenovo        | ThinkPad X61 7675LG2        | [bcbd5eb3f6](https://linux-hardware.org/?probe=bcbd5eb3f6) | Apr 01, 2022 |
| HP            | 255 G7 Notebook PC          | [290217f248](https://linux-hardware.org/?probe=290217f248) | Apr 01, 2022 |
| HP            | Laptop 15-da0xxx            | [b73099e091](https://linux-hardware.org/?probe=b73099e091) | Apr 01, 2022 |
| Acer          | Aspire E5-773G              | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| Dell          | Latitude 3189               | [36115f4eb5](https://linux-hardware.org/?probe=36115f4eb5) | Mar 31, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| Packard Be... | EasyNote ENTG71BM           | [f236b5007a](https://linux-hardware.org/?probe=f236b5007a) | Mar 31, 2022 |
| Lenovo        | V15-IIL 82C5                | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| HP            | Pavilion g7                 | [a162ae9ffa](https://linux-hardware.org/?probe=a162ae9ffa) | Mar 30, 2022 |
| HP            | Pavilion dv5                | [29096b57ad](https://linux-hardware.org/?probe=29096b57ad) | Mar 30, 2022 |
| Fujitsu Si... | LIFEBOOK E8420              | [1f81c3ef0a](https://linux-hardware.org/?probe=1f81c3ef0a) | Mar 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7abb97f630](https://linux-hardware.org/?probe=7abb97f630) | Mar 30, 2022 |
| Philco        | 14I                         | [f49a55854c](https://linux-hardware.org/?probe=f49a55854c) | Mar 30, 2022 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [0befbade0d](https://linux-hardware.org/?probe=0befbade0d) | Mar 29, 2022 |
| HP            | Pavilion 17                 | [da4b84712e](https://linux-hardware.org/?probe=da4b84712e) | Mar 29, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [fc7ebbef4e](https://linux-hardware.org/?probe=fc7ebbef4e) | Mar 29, 2022 |
| Dell          | Inspiron N5110              | [ce630f6abb](https://linux-hardware.org/?probe=ce630f6abb) | Mar 29, 2022 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [60aa56878d](https://linux-hardware.org/?probe=60aa56878d) | Mar 28, 2022 |
| Dell          | Latitude E5550              | [f01dc93afc](https://linux-hardware.org/?probe=f01dc93afc) | Mar 28, 2022 |
| Toshiba       | PORTEGE R935                | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 6464W4J        | [5f73680acf](https://linux-hardware.org/?probe=5f73680acf) | Mar 28, 2022 |
| HP            | 250 G5 Notebook PC          | [a9ce7cfa0b](https://linux-hardware.org/?probe=a9ce7cfa0b) | Mar 27, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Positivo      | Z100                        | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| ASUSTek       | N76VJ                       | [53ec863214](https://linux-hardware.org/?probe=53ec863214) | Mar 26, 2022 |
| Lenovo        | ThinkPad A485 20MU0007CD    | [1e231d6b08](https://linux-hardware.org/?probe=1e231d6b08) | Mar 26, 2022 |
| Toshiba       | Satellite C855-2G8          | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Apple         | MacBookPro7,1               | [ca93a32a4b](https://linux-hardware.org/?probe=ca93a32a4b) | Mar 25, 2022 |
| Dell          | Latitude E7450              | [db931ebb1f](https://linux-hardware.org/?probe=db931ebb1f) | Mar 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| HP            | Pavilion dv6                | [c7dff2cc50](https://linux-hardware.org/?probe=c7dff2cc50) | Mar 25, 2022 |
| Dell          | Latitude 3300               | [0dbed1a827](https://linux-hardware.org/?probe=0dbed1a827) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1cf6ad2e8e](https://linux-hardware.org/?probe=1cf6ad2e8e) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [57c51a1a1c](https://linux-hardware.org/?probe=57c51a1a1c) | Mar 25, 2022 |
| Lenovo        | ThinkPad X61s 7667CB5       | [05a3f6eba9](https://linux-hardware.org/?probe=05a3f6eba9) | Mar 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [73c4a3b7b4](https://linux-hardware.org/?probe=73c4a3b7b4) | Mar 24, 2022 |
| HP            | Pavilion 11 x360 PC         | [7c506671a1](https://linux-hardware.org/?probe=7c506671a1) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5170bfb594](https://linux-hardware.org/?probe=5170bfb594) | Mar 24, 2022 |
| HP            | Pavilion g6                 | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| ASUSTek       | N56JN                       | [8302116452](https://linux-hardware.org/?probe=8302116452) | Mar 24, 2022 |
| Dell          | Inspiron 3543               | [e2163528af](https://linux-hardware.org/?probe=e2163528af) | Mar 24, 2022 |
| Lenovo        | ThinkPad X260 20F5S2C600    | [12df54f389](https://linux-hardware.org/?probe=12df54f389) | Mar 24, 2022 |
| MSI           | Alpha 15 A3DDK              | [ba7e272251](https://linux-hardware.org/?probe=ba7e272251) | Mar 23, 2022 |
| Dell          | XPS 13 9360                 | [30003161fe](https://linux-hardware.org/?probe=30003161fe) | Mar 23, 2022 |
| MSI           | GE72VR 6RF                  | [b957669e37](https://linux-hardware.org/?probe=b957669e37) | Mar 23, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [c923ffc942](https://linux-hardware.org/?probe=c923ffc942) | Mar 23, 2022 |
| Sony          | SVE1711G1RB                 | [f6c732711b](https://linux-hardware.org/?probe=f6c732711b) | Mar 23, 2022 |
| Dell          | Latitude E6220              | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Unknown       | Unknown                     | [e0dc423b2a](https://linux-hardware.org/?probe=e0dc423b2a) | Mar 23, 2022 |
| HP            | Elite x2 1012 G1            | [d8c3d46ad9](https://linux-hardware.org/?probe=d8c3d46ad9) | Mar 23, 2022 |
| Dell          | Latitude 7490               | [46726fbceb](https://linux-hardware.org/?probe=46726fbceb) | Mar 23, 2022 |
| Dell          | Latitude 3189               | [1ba82561d5](https://linux-hardware.org/?probe=1ba82561d5) | Mar 22, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [35488c8cce](https://linux-hardware.org/?probe=35488c8cce) | Mar 22, 2022 |
| MSI           | GE72VR 6RF                  | [73be3ca633](https://linux-hardware.org/?probe=73be3ca633) | Mar 22, 2022 |
| HP            | ProBook 450 G6              | [e8072f850f](https://linux-hardware.org/?probe=e8072f850f) | Mar 22, 2022 |
| Packard Be... | DOT S                       | [591be1d465](https://linux-hardware.org/?probe=591be1d465) | Mar 22, 2022 |
| Dell          | Inspiron 5423               | [ea335b5e3b](https://linux-hardware.org/?probe=ea335b5e3b) | Mar 21, 2022 |
| ASUSTek       | N752VX                      | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| ASUSTek       | K40IJ                       | [dbc0e61f47](https://linux-hardware.org/?probe=dbc0e61f47) | Mar 21, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| HP            | 255 G8 Notebook PC          | [5adc6f4d6b](https://linux-hardware.org/?probe=5adc6f4d6b) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| Dell          | System XPS L322X            | [ee172af23a](https://linux-hardware.org/?probe=ee172af23a) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| VIT           | P2402                       | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| eMachines     | E525                        | [269a5e5794](https://linux-hardware.org/?probe=269a5e5794) | Mar 20, 2022 |
| Apple         | MacBook5,2                  | [26c6fa4da4](https://linux-hardware.org/?probe=26c6fa4da4) | Mar 20, 2022 |
| Lenovo        | B560 43308VG                | [f1e07e69d0](https://linux-hardware.org/?probe=f1e07e69d0) | Mar 20, 2022 |
| Lenovo        | ThinkPad T520 4243M75       | [d7a393fd7b](https://linux-hardware.org/?probe=d7a393fd7b) | Mar 20, 2022 |
| Lenovo        | G50-45 80E3                 | [9ffca5e95b](https://linux-hardware.org/?probe=9ffca5e95b) | Mar 20, 2022 |
| Dell          | Precision M4800             | [71dd646f94](https://linux-hardware.org/?probe=71dd646f94) | Mar 20, 2022 |
| Lenovo        | ThinkPad X230 2325BA3       | [d4170940f0](https://linux-hardware.org/?probe=d4170940f0) | Mar 20, 2022 |
| Acer          | Acadia V1.21                | [e6541adef3](https://linux-hardware.org/?probe=e6541adef3) | Mar 20, 2022 |
| Dell          | XPS 13 9360                 | [f350633b4c](https://linux-hardware.org/?probe=f350633b4c) | Mar 20, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [93eefcdc91](https://linux-hardware.org/?probe=93eefcdc91) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | [66de21a937](https://linux-hardware.org/?probe=66de21a937) | Mar 19, 2022 |
| ASUSTek       | X555LJ                      | [9e38b0860e](https://linux-hardware.org/?probe=9e38b0860e) | Mar 19, 2022 |
| Fujitsu       | FMVA05003                   | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 8470p             | [0207f22677](https://linux-hardware.org/?probe=0207f22677) | Mar 19, 2022 |
| Positivo      | Mobile                      | [a1eb18d712](https://linux-hardware.org/?probe=a1eb18d712) | Mar 18, 2022 |
| Dell          | Latitude 3189               | [89ec672f05](https://linux-hardware.org/?probe=89ec672f05) | Mar 18, 2022 |
| Sony          | VPCEB4E1E                   | [51c7b5aa1a](https://linux-hardware.org/?probe=51c7b5aa1a) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [2072cd9c30](https://linux-hardware.org/?probe=2072cd9c30) | Mar 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [0833c34819](https://linux-hardware.org/?probe=0833c34819) | Mar 18, 2022 |
| HP            | Pavilion dv6                | [e039f6eb58](https://linux-hardware.org/?probe=e039f6eb58) | Mar 17, 2022 |
| Acer          | Aspire 5820                 | [5288ae7fc8](https://linux-hardware.org/?probe=5288ae7fc8) | Mar 17, 2022 |
| Dell          | Precision M4600             | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad X230 23331D9       | [6edcc3117e](https://linux-hardware.org/?probe=6edcc3117e) | Mar 16, 2022 |
| Toshiba       | Satellite C55D-A            | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| Acer          | Aspire 7741                 | [abbf6e7e7b](https://linux-hardware.org/?probe=abbf6e7e7b) | Mar 16, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2bb6b8bfd0](https://linux-hardware.org/?probe=2bb6b8bfd0) | Mar 16, 2022 |
| Acer          | Predator G9-793             | [c8068717f8](https://linux-hardware.org/?probe=c8068717f8) | Mar 16, 2022 |
| Acer          | Swift SF314-52              | [24c4fad70d](https://linux-hardware.org/?probe=24c4fad70d) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| MSI           | GE72VR 6RF                  | [b64205ca2e](https://linux-hardware.org/?probe=b64205ca2e) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1829c59f64](https://linux-hardware.org/?probe=1829c59f64) | Mar 14, 2022 |
| Lenovo        | ThinkPad R61 7733B46        | [d2220c6c2e](https://linux-hardware.org/?probe=d2220c6c2e) | Mar 14, 2022 |
| ASUSTek       | G75VX                       | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Dell          | Latitude E5440              | [cc385d8327](https://linux-hardware.org/?probe=cc385d8327) | Mar 14, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| HP            | Laptop 15s-eq2xxx           | [189e272099](https://linux-hardware.org/?probe=189e272099) | Mar 13, 2022 |
| Acer          | Aspire E5-571               | [824c5eb97d](https://linux-hardware.org/?probe=824c5eb97d) | Mar 13, 2022 |
| Lenovo        | G40-30 80FY                 | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Toshiba       | Satellite Pro S500          | [9976a7321c](https://linux-hardware.org/?probe=9976a7321c) | Mar 13, 2022 |
| Lenovo        | ThinkPad X230 2325DV5       | [c622952988](https://linux-hardware.org/?probe=c622952988) | Mar 13, 2022 |
| Toshiba       | Satellite Pro C660          | [2a2400c148](https://linux-hardware.org/?probe=2a2400c148) | Mar 13, 2022 |
| HP            | Laptop 15-bs0xx             | [2dd60fe836](https://linux-hardware.org/?probe=2dd60fe836) | Mar 13, 2022 |
| HP            | Presario CQ62               | [143eade9bc](https://linux-hardware.org/?probe=143eade9bc) | Mar 13, 2022 |
| HP            | Pavilion Notebook           | [1de76aac69](https://linux-hardware.org/?probe=1de76aac69) | Mar 12, 2022 |
| Philco        | 10D                         | [c983be3bb0](https://linux-hardware.org/?probe=c983be3bb0) | Mar 11, 2022 |
| ASUSTek       | K53U                        | [7f78b941ce](https://linux-hardware.org/?probe=7f78b941ce) | Mar 11, 2022 |
| ASUSTek       | UX303LAB                    | [f3d0e8fbea](https://linux-hardware.org/?probe=f3d0e8fbea) | Mar 11, 2022 |
| Dell          | Latitude 3310               | [d0f00ace6c](https://linux-hardware.org/?probe=d0f00ace6c) | Mar 11, 2022 |
| Dell          | Latitude 3390 2-in-1        | [b482b781bd](https://linux-hardware.org/?probe=b482b781bd) | Mar 11, 2022 |
| Medion        | E6228                       | [47099a8c6c](https://linux-hardware.org/?probe=47099a8c6c) | Mar 11, 2022 |
| Dell          | Latitude E5470              | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Toshiba       | QOSMIO X770                 | [86f68b585b](https://linux-hardware.org/?probe=86f68b585b) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [05b4cceab2](https://linux-hardware.org/?probe=05b4cceab2) | Mar 10, 2022 |
| Dell          | Latitude 5411               | [b56bb115a0](https://linux-hardware.org/?probe=b56bb115a0) | Mar 10, 2022 |
| Acer          | Aspire A317-33              | [a4c0271977](https://linux-hardware.org/?probe=a4c0271977) | Mar 10, 2022 |
| Acer          | Aspire S3                   | [6ae9c3b307](https://linux-hardware.org/?probe=6ae9c3b307) | Mar 10, 2022 |
| Lenovo        | B590 20208                  | [46d63f7527](https://linux-hardware.org/?probe=46d63f7527) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Fujitsu       | LIFEBOOK S792               | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| ASUSTek       | UX305FA                     | [f1641a436c](https://linux-hardware.org/?probe=f1641a436c) | Mar 09, 2022 |
| Acer          | Extensa 5220                | [fa85be94b2](https://linux-hardware.org/?probe=fa85be94b2) | Mar 09, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| Acer          | AO722                       | [fc0bccc42d](https://linux-hardware.org/?probe=fc0bccc42d) | Mar 09, 2022 |
| Toshiba       | Satellite L450D             | [343578bf21](https://linux-hardware.org/?probe=343578bf21) | Mar 09, 2022 |
| Toshiba       | Satellite L350D             | [8023f07e6c](https://linux-hardware.org/?probe=8023f07e6c) | Mar 09, 2022 |
| Apple         | MacBookPro9,2               | [ef06c07ea8](https://linux-hardware.org/?probe=ef06c07ea8) | Mar 08, 2022 |
| ASUSTek       | F3Sr                        | [ab9d32a3ff](https://linux-hardware.org/?probe=ab9d32a3ff) | Mar 08, 2022 |
| HP            | EliteBook 840 G3            | [ce025d2364](https://linux-hardware.org/?probe=ce025d2364) | Mar 08, 2022 |
| Intel         | Unknown                     | [9390bef13c](https://linux-hardware.org/?probe=9390bef13c) | Mar 08, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [bd22f532ef](https://linux-hardware.org/?probe=bd22f532ef) | Mar 08, 2022 |
| Dell          | Inspiron 3493               | [dcefffbbbf](https://linux-hardware.org/?probe=dcefffbbbf) | Mar 08, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| Lenovo        | Unknown                     | [4308edfd8d](https://linux-hardware.org/?probe=4308edfd8d) | Mar 07, 2022 |
| Toshiba       | Satellite U400              | [e21b12ca9f](https://linux-hardware.org/?probe=e21b12ca9f) | Mar 07, 2022 |
| Lenovo        | Flex 2-15 20405             | [3e4ac3a045](https://linux-hardware.org/?probe=3e4ac3a045) | Mar 07, 2022 |
| Dell          | Latitude 3310               | [0268bb19d1](https://linux-hardware.org/?probe=0268bb19d1) | Mar 07, 2022 |
| Toshiba       | Satellite C70               | [d8f6f051b3](https://linux-hardware.org/?probe=d8f6f051b3) | Mar 07, 2022 |
| HP            | Pavilion dv7                | [eda63a0bb2](https://linux-hardware.org/?probe=eda63a0bb2) | Mar 07, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 1564      | 96.31%  |
| 5.16.13-desktop-1omv4003      | 37        | 2.28%   |
| 5.17.1-desktop-2omv4050       | 12        | 0.74%   |
| 5.14.14-desktop-1omv4050      | 4         | 0.25%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.12%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.12%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.06%   |
| 5.16.5-desktop-2omv4003       | 1         | 0.06%   |
| 5.15.14-1-lts                 | 1         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16.7  | 1564      | 96.31%  |
| 5.16.13 | 37        | 2.28%   |
| 5.17.1  | 14        | 0.86%   |
| 5.14.14 | 4         | 0.25%   |
| 5.16.9  | 3         | 0.18%   |
| 5.16.5  | 1         | 0.06%   |
| 5.15.14 | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 1605      | 98.83%  |
| 5.17    | 14        | 0.86%   |
| 5.14    | 4         | 0.25%   |
| 5.15    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1624      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDE5    | 1617      | 99.57%  |
| LXQt    | 5         | 0.31%   |
| Unknown | 2         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1621      | 99.82%  |
| Wayland | 3         | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 1624      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 898       | 55.3%   |
| de_DE | 150       | 9.24%   |
| fr_FR | 84        | 5.17%   |
| pt_BR | 68        | 4.19%   |
| it_IT | 59        | 3.63%   |
| pl_PL | 52        | 3.2%    |
| ru_RU | 51        | 3.14%   |
| en_GB | 39        | 2.4%    |
| es_ES | 31        | 1.91%   |
| es_MX | 19        | 1.17%   |
| de_AT | 15        | 0.92%   |
| cs_CZ | 14        | 0.86%   |
| pt_PT | 11        | 0.68%   |
| es_CO | 10        | 0.62%   |
| es_AR | 10        | 0.62%   |
| tr_TR | 9         | 0.55%   |
| hu_HU | 9         | 0.55%   |
| es_CL | 8         | 0.49%   |
| en_CA | 8         | 0.49%   |
| nl_NL | 7         | 0.43%   |
| nl_BE | 7         | 0.43%   |
| en_IN | 7         | 0.43%   |
| de_CH | 7         | 0.43%   |
| fr_BE | 5         | 0.31%   |
| fr_CH | 4         | 0.25%   |
| en_AU | 4         | 0.25%   |
| ro_RO | 3         | 0.18%   |
| fr_CA | 3         | 0.18%   |
| es_VE | 3         | 0.18%   |
| es_PE | 3         | 0.18%   |
| ru_UA | 2         | 0.12%   |
| nb_NO | 2         | 0.12%   |
| es_EC | 2         | 0.12%   |
| es_CR | 2         | 0.12%   |
| es_BO | 2         | 0.12%   |
| en_NZ | 2         | 0.12%   |
| da_DK | 2         | 0.12%   |
| uk_UA | 1         | 0.06%   |
| tr_CY | 1         | 0.06%   |
| es_UY | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 894       | 55.05%  |
| BIOS | 730       | 44.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 1293      | 79.62%  |
| Ext4    | 325       | 20.01%  |
| Xfs     | 3         | 0.18%   |
| Btrfs   | 2         | 0.12%   |
| Jfs     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 1118      | 68.84%  |
| MBR  | 506       | 31.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 840       | 51.72%  |
| No        | 784       | 48.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 964       | 59.36%  |
| Yes       | 660       | 40.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 314       | 19.33%  |
| Hewlett-Packard       | 301       | 18.53%  |
| Dell                  | 267       | 16.44%  |
| Acer                  | 172       | 10.59%  |
| ASUSTek Computer      | 170       | 10.47%  |
| Toshiba               | 81        | 4.99%   |
| Sony                  | 36        | 2.22%   |
| Samsung Electronics   | 34        | 2.09%   |
| Fujitsu               | 30        | 1.85%   |
| Apple                 | 28        | 1.72%   |
| MSI                   | 21        | 1.29%   |
| Positivo              | 16        | 0.99%   |
| Packard Bell          | 14        | 0.86%   |
| TUXEDO                | 10        | 0.62%   |
| Medion                | 10        | 0.62%   |
| HUAWEI                | 8         | 0.49%   |
| Philco                | 7         | 0.43%   |
| Unknown               | 7         | 0.43%   |
| Notebook              | 6         | 0.37%   |
| LG Electronics        | 5         | 0.31%   |
| Fujitsu Siemens       | 5         | 0.31%   |
| eMachines             | 5         | 0.31%   |
| Positivo Bahia - VAIO | 4         | 0.25%   |
| Digibras              | 4         | 0.25%   |
| Compaq                | 4         | 0.25%   |
| Chuwi                 | 4         | 0.25%   |
| AZW                   | 4         | 0.25%   |
| Alienware             | 4         | 0.25%   |
| Gateway               | 3         | 0.18%   |
| Wortmann AG           | 2         | 0.12%   |
| UMAX                  | 2         | 0.12%   |
| Timi                  | 2         | 0.12%   |
| PC Specialist         | 2         | 0.12%   |
| NEC Computers         | 2         | 0.12%   |
| Intel                 | 2         | 0.12%   |
| HYPA                  | 2         | 0.12%   |
| Google                | 2         | 0.12%   |
| Gigabyte Technology   | 2         | 0.12%   |
| Framework             | 2         | 0.12%   |
| Clevo                 | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Dell Latitude 3310                     | 29        | 1.79%   |
| Unknown                                | 21        | 1.29%   |
| HP Notebook                            | 14        | 0.86%   |
| HP Pavilion g6                         | 9         | 0.55%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 8         | 0.49%   |
| Dell Latitude 3300                     | 8         | 0.49%   |
| HP Pavilion dv6                        | 7         | 0.43%   |
| Dell Latitude E7450                    | 7         | 0.43%   |
| Sony VGN-FZ31Z                         | 6         | 0.37%   |
| Positivo Mobile                        | 6         | 0.37%   |
| HP Laptop 14-fq0xxx                    | 6         | 0.37%   |
| Dell Latitude 3189                     | 6         | 0.37%   |
| Acer Aspire A515-51G                   | 6         | 0.37%   |
| Lenovo IdeaPad S340-14API 81NB         | 5         | 0.31%   |
| HP Pavilion dv7                        | 5         | 0.31%   |
| HP Pavilion 15                         | 5         | 0.31%   |
| HP Compaq 15                           | 5         | 0.31%   |
| Dell XPS 13 9360                       | 5         | 0.31%   |
| Dell Precision M6800                   | 5         | 0.31%   |
| Dell Latitude E7240                    | 5         | 0.31%   |
| Dell Latitude E6430                    | 5         | 0.31%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA | 5         | 0.31%   |
| Acer AO722                             | 5         | 0.31%   |
| Toshiba Satellite P200                 | 4         | 0.25%   |
| Lenovo IdeaPad S145-15AST 81N3         | 4         | 0.25%   |
| HP Pavilion Laptop 15-eh0xxx           | 4         | 0.25%   |
| HP Pavilion g7                         | 4         | 0.25%   |
| HP Laptop 15s-eq1xxx                   | 4         | 0.25%   |
| HP Laptop 15-da0xxx                    | 4         | 0.25%   |
| HP Compaq CQ58                         | 4         | 0.25%   |
| HP 2000                                | 4         | 0.25%   |
| HP 15                                  | 4         | 0.25%   |
| Dell Latitude E6420                    | 4         | 0.25%   |
| Dell Latitude E6220                    | 4         | 0.25%   |
| Dell Latitude E5450                    | 4         | 0.25%   |
| Dell Latitude E5410                    | 4         | 0.25%   |
| Dell Latitude D630                     | 4         | 0.25%   |
| ASUS X551MA                            | 4         | 0.25%   |
| Apple MacBookPro9,2                    | 4         | 0.25%   |
| Apple MacBookPro8,1                    | 4         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 165       | 10.16%  |
| Lenovo ThinkPad       | 133       | 8.19%   |
| Acer Aspire           | 115       | 7.08%   |
| Lenovo IdeaPad        | 102       | 6.28%   |
| HP Pavilion           | 71        | 4.37%   |
| Toshiba Satellite     | 67        | 4.13%   |
| HP Laptop             | 52        | 3.2%    |
| Dell Inspiron         | 47        | 2.89%   |
| HP ProBook            | 42        | 2.59%   |
| ASUS VivoBook         | 36        | 2.22%   |
| HP EliteBook          | 23        | 1.42%   |
| HP Compaq             | 23        | 1.42%   |
| Fujitsu LIFEBOOK      | 21        | 1.29%   |
| Unknown               | 21        | 1.29%   |
| HP Notebook           | 14        | 0.86%   |
| Dell XPS              | 13        | 0.8%    |
| Dell Vostro           | 13        | 0.8%    |
| Dell Precision        | 13        | 0.8%    |
| Acer Swift            | 13        | 0.8%    |
| Packard Bell EasyNote | 12        | 0.74%   |
| Acer Nitro            | 11        | 0.68%   |
| Acer Extensa          | 10        | 0.62%   |
| HP 250                | 8         | 0.49%   |
| HP 255                | 7         | 0.43%   |
| Acer TravelMate       | 7         | 0.43%   |
| Sony VGN-FZ31Z        | 6         | 0.37%   |
| Positivo Mobile       | 6         | 0.37%   |
| HP Stream             | 6         | 0.37%   |
| HP OMEN               | 6         | 0.37%   |
| Dell System           | 6         | 0.37%   |
| ASUS ZenBook          | 6         | 0.37%   |
| Toshiba dynabook      | 5         | 0.31%   |
| Lenovo Yoga           | 5         | 0.31%   |
| Lenovo Legion         | 5         | 0.31%   |
| HP ZBook              | 5         | 0.31%   |
| HP ENVY               | 5         | 0.31%   |
| Dell Studio           | 5         | 0.31%   |
| Acer AO722            | 5         | 0.31%   |
| Toshiba TECRA         | 4         | 0.25%   |
| Medion Akoya          | 4         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 167       | 10.28%  |
| 2012    | 166       | 10.22%  |
| 2019    | 140       | 8.62%   |
| 2013    | 128       | 7.88%   |
| 2020    | 122       | 7.51%   |
| 2014    | 112       | 6.9%    |
| 2021    | 105       | 6.47%   |
| 2016    | 105       | 6.47%   |
| 2010    | 105       | 6.47%   |
| 2015    | 91        | 5.6%    |
| 2017    | 85        | 5.23%   |
| 2018    | 82        | 5.05%   |
| 2008    | 71        | 4.37%   |
| 2009    | 70        | 4.31%   |
| 2007    | 54        | 3.33%   |
| 2006    | 11        | 0.68%   |
| 2022    | 6         | 0.37%   |
| Unknown | 4         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1624      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1624      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1619      | 99.69%  |
| Yes  | 5         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 569       | 35.04%  |
| 3.01-4.0    | 545       | 33.56%  |
| 8.01-16.0   | 215       | 13.24%  |
| 16.01-24.0  | 149       | 9.17%   |
| 1.01-2.0    | 67        | 4.13%   |
| 32.01-64.0  | 33        | 2.03%   |
| 2.01-3.0    | 28        | 1.72%   |
| 24.01-32.0  | 8         | 0.49%   |
| 0.51-1.0    | 6         | 0.37%   |
| 64.01-256.0 | 4         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 1309      | 80.6%   |
| 0.51-1.0  | 185       | 11.39%  |
| 2.01-3.0  | 105       | 6.47%   |
| 0.01-0.5  | 10        | 0.62%   |
| 3.01-4.0  | 7         | 0.43%   |
| 4.01-8.0  | 5         | 0.31%   |
| 8.01-16.0 | 3         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1186      | 73.03%  |
| 2      | 361       | 22.23%  |
| 3      | 39        | 2.4%    |
| 0      | 26        | 1.6%    |
| 4      | 11        | 0.68%   |
| 5      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 879       | 54.13%  |
| Yes       | 745       | 45.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1369      | 84.3%   |
| No        | 255       | 15.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1613      | 99.32%  |
| No        | 11        | 0.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1214      | 74.75%  |
| No        | 410       | 25.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 203       | 12.5%   |
| USA         | 174       | 10.71%  |
| Brazil      | 112       | 6.9%    |
| France      | 105       | 6.47%   |
| Poland      | 79        | 4.86%   |
| Netherlands | 79        | 4.86%   |
| Italy       | 79        | 4.86%   |
| Russia      | 65        | 4%      |
| UK          | 63        | 3.88%   |
| Spain       | 43        | 2.65%   |
| Canada      | 39        | 2.4%    |
| Indonesia   | 32        | 1.97%   |
| Mexico      | 31        | 1.91%   |
| Portugal    | 26        | 1.6%    |
| India       | 23        | 1.42%   |
| Colombia    | 23        | 1.42%   |
| Switzerland | 21        | 1.29%   |
| Japan       | 21        | 1.29%   |
| Australia   | 21        | 1.29%   |
| Turkey      | 20        | 1.23%   |
| Czechia     | 19        | 1.17%   |
| Austria     | 19        | 1.17%   |
| Sweden      | 18        | 1.11%   |
| Romania     | 17        | 1.05%   |
| Argentina   | 17        | 1.05%   |
| Belgium     | 15        | 0.92%   |
| Ukraine     | 13        | 0.8%    |
| Greece      | 13        | 0.8%    |
| Bulgaria    | 13        | 0.8%    |
| Slovakia    | 12        | 0.74%   |
| Hungary     | 12        | 0.74%   |
| New Zealand | 11        | 0.68%   |
| Finland     | 11        | 0.68%   |
| Serbia      | 10        | 0.62%   |
| China       | 10        | 0.62%   |
| Chile       | 10        | 0.62%   |
| Peru        | 8         | 0.49%   |
| Croatia     | 7         | 0.43%   |
| Norway      | 6         | 0.37%   |
| Venezuela   | 5         | 0.31%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Schagen              | 56        | 3.45%   |
| Paris                | 19        | 1.17%   |
| Berlin               | 18        | 1.11%   |
| Sao Paulo            | 16        | 0.99%   |
| Moscow               | 16        | 0.99%   |
| Milan                | 14        | 0.86%   |
| Warsaw               | 12        | 0.74%   |
| Vienna               | 10        | 0.62%   |
| Sydney               | 9         | 0.55%   |
| Hamburg              | 9         | 0.55%   |
| Prague               | 8         | 0.49%   |
| Krakow               | 8         | 0.49%   |
| Istanbul             | 8         | 0.49%   |
| Cascais              | 8         | 0.49%   |
| Belgrade             | 8         | 0.49%   |
| Mexico City          | 7         | 0.43%   |
| Bengaluru            | 7         | 0.43%   |
| Surabaya             | 6         | 0.37%   |
| Salach               | 6         | 0.37%   |
| Rio de Janeiro       | 6         | 0.37%   |
| Munich               | 6         | 0.37%   |
| Jakarta              | 6         | 0.37%   |
| Gorzów Wielkopolski | 6         | 0.37%   |
| Funchal              | 6         | 0.37%   |
| Curitiba             | 6         | 0.37%   |
| Barranquilla         | 6         | 0.37%   |
| Auckland             | 6         | 0.37%   |
| Zagreb               | 5         | 0.31%   |
| Wroclaw              | 5         | 0.31%   |
| Thessaloniki         | 5         | 0.31%   |
| Montreal             | 5         | 0.31%   |
| Madrid               | 5         | 0.31%   |
| Lima                 | 5         | 0.31%   |
| Helsinki             | 5         | 0.31%   |
| Dortmund             | 5         | 0.31%   |
| Cologne              | 5         | 0.31%   |
| Bratislava           | 5         | 0.31%   |
| Athens               | 5         | 0.31%   |
| Vancouver            | 4         | 0.25%   |
| Spring Hill          | 4         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 262       | 268    | 13.63%  |
| Samsung Electronics | 228       | 240    | 11.86%  |
| Seagate             | 210       | 218    | 10.93%  |
| Toshiba             | 182       | 187    | 9.47%   |
| Kingston            | 110       | 111    | 5.72%   |
| Hitachi             | 90        | 90     | 4.68%   |
| Unknown             | 87        | 88     | 4.53%   |
| SK hynix            | 82        | 86     | 4.27%   |
| Crucial             | 77        | 83     | 4.01%   |
| SanDisk             | 66        | 66     | 3.43%   |
| HGST                | 64        | 64     | 3.33%   |
| Intel               | 36        | 40     | 1.87%   |
| A-DATA Technology   | 35        | 35     | 1.82%   |
| Micron Technology   | 32        | 32     | 1.66%   |
| LITEON              | 21        | 21     | 1.09%   |
| KIOXIA              | 21        | 21     | 1.09%   |
| Fujitsu             | 19        | 19     | 0.99%   |
| Unknown             | 18        | 18     | 0.94%   |
| Intenso             | 15        | 15     | 0.78%   |
| GOODRAM             | 15        | 15     | 0.78%   |
| PNY                 | 14        | 14     | 0.73%   |
| China               | 14        | 14     | 0.73%   |
| ASMT                | 13        | 13     | 0.68%   |
| Patriot             | 11        | 11     | 0.57%   |
| JMicron Technology  | 10        | 10     | 0.52%   |
| Apple               | 10        | 10     | 0.52%   |
| SSSTC               | 9         | 9      | 0.47%   |
| Transcend           | 8         | 8      | 0.42%   |
| SPCC                | 8         | 8      | 0.42%   |
| KingSpec            | 8         | 8      | 0.42%   |
| Silicon Motion      | 7         | 8      | 0.36%   |
| Gigabyte Technology | 7         | 7      | 0.36%   |
| Corsair             | 7         | 7      | 0.36%   |
| Apacer              | 7         | 7      | 0.36%   |
| Phison              | 6         | 6      | 0.31%   |
| Hewlett-Packard     | 6         | 6      | 0.31%   |
| UMIS                | 5         | 5      | 0.26%   |
| SABRENT             | 5         | 5      | 0.26%   |
| LITEONIT            | 5         | 5      | 0.26%   |
| Lexar               | 5         | 5      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 32        | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 26        | 1.33%   |
| Kingston SA400S37240G 240GB SSD     | 26        | 1.33%   |
| Toshiba MQ01ABD100 1TB              | 24        | 1.23%   |
| Seagate ST500LT012-1DG142 500GB     | 23        | 1.18%   |
| Toshiba MQ04ABF100 1TB              | 21        | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB      | 21        | 1.07%   |
| Unknown                             | 18        | 0.92%   |
| Unknown SD/MMC/MS PRO 2GB           | 13        | 0.66%   |
| Kingston SA400S37480G 480GB SSD     | 13        | 0.66%   |
| HGST HTS721010A9E630 1TB            | 13        | 0.66%   |
| HGST HTS541010A9E680 1TB            | 13        | 0.66%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 12        | 0.61%   |
| Seagate ST9500325AS 500GB           | 12        | 0.61%   |
| Samsung SSD 860 EVO 500GB           | 12        | 0.61%   |
| Samsung SSD 850 EVO 250GB           | 12        | 0.61%   |
| Crucial CT240BX500SSD1 240GB        | 12        | 0.61%   |
| Kingston SA400S37120G 120GB SSD     | 11        | 0.56%   |
| HGST HTS545050A7E680 500GB          | 11        | 0.56%   |
| Seagate ST2000LM015-2E8174 2TB      | 10        | 0.51%   |
| Samsung SSD 860 EVO 250GB           | 10        | 0.51%   |
| Hitachi HTS547550A9E384 500GB       | 10        | 0.51%   |
| Hitachi HTS543232A7A384 320GB       | 10        | 0.51%   |
| Unknown DA4064  64GB                | 9         | 0.46%   |
| SK hynix BC511 NVMe 256GB           | 9         | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 9         | 0.46%   |
| Samsung SSD 850 EVO 500GB           | 9         | 0.46%   |
| JMicron Generic 120GB               | 9         | 0.46%   |
| Unknown MMC64G  64GB                | 8         | 0.41%   |
| Hitachi HTS547575A9E384 752GB       | 8         | 0.41%   |
| Crucial CT1000BX500SSD1 1TB         | 8         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 7         | 0.36%   |
| WDC WD10JPCX-24UE4T0 1TB            | 7         | 0.36%   |
| Seagate ST9320325AS 320GB           | 7         | 0.36%   |
| Samsung SSD 860 QVO 1TB             | 7         | 0.36%   |
| Samsung PM991a NVMe 256GB           | 7         | 0.36%   |
| HGST HTS545050A7E380 500GB          | 7         | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 0.31%   |
| SanDisk SSD PLUS 480GB              | 6         | 0.31%   |
| SanDisk DF4032  32GB                | 6         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 207       | 214    | 26.64%  |
| WDC                 | 193       | 195    | 24.84%  |
| Toshiba             | 159       | 161    | 20.46%  |
| Hitachi             | 90        | 90     | 11.58%  |
| HGST                | 64        | 64     | 8.24%   |
| Fujitsu             | 19        | 19     | 2.45%   |
| Samsung Electronics | 16        | 16     | 2.06%   |
| Unknown             | 13        | 13     | 1.67%   |
| ASMedia             | 3         | 3      | 0.39%   |
| Apple               | 3         | 3      | 0.39%   |
| SAGE                | 2         | 2      | 0.26%   |
| ASMT                | 2         | 2      | 0.26%   |
| WD MediaMax         | 1         | 1      | 0.13%   |
| SATAFIRM            | 1         | 1      | 0.13%   |
| QC-FT-D             | 1         | 1      | 0.13%   |
| Magnetic Data       | 1         | 1      | 0.13%   |
| HGST HTS            | 1         | 1      | 0.13%   |
| Hewlett-Packard     | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 150       | 155    | 20.89%  |
| Kingston            | 88        | 89     | 12.26%  |
| Crucial             | 70        | 76     | 9.75%   |
| SanDisk             | 57        | 57     | 7.94%   |
| WDC                 | 33        | 33     | 4.6%    |
| A-DATA Technology   | 25        | 25     | 3.48%   |
| SK hynix            | 24        | 25     | 3.34%   |
| Micron Technology   | 23        | 23     | 3.2%    |
| LITEON              | 19        | 19     | 2.65%   |
| Toshiba             | 16        | 17     | 2.23%   |
| GOODRAM             | 15        | 15     | 2.09%   |
| PNY                 | 14        | 14     | 1.95%   |
| China               | 14        | 14     | 1.95%   |
| Intenso             | 13        | 13     | 1.81%   |
| Patriot             | 11        | 11     | 1.53%   |
| Intel               | 9         | 9      | 1.25%   |
| Transcend           | 8         | 8      | 1.11%   |
| KingSpec            | 8         | 8      | 1.11%   |
| ASMT                | 8         | 8      | 1.11%   |
| Unknown             | 8         | 8      | 1.11%   |
| Apacer              | 7         | 7      | 0.97%   |
| SPCC                | 6         | 6      | 0.84%   |
| Apple               | 6         | 6      | 0.84%   |
| LITEONIT            | 5         | 5      | 0.7%    |
| Lexar               | 5         | 5      | 0.7%    |
| Corsair             | 5         | 5      | 0.7%    |
| OCZ                 | 4         | 4      | 0.56%   |
| TCSUNBOW            | 3         | 3      | 0.42%   |
| Plextor             | 3         | 3      | 0.42%   |
| Netac               | 3         | 3      | 0.42%   |
| KingDian            | 3         | 3      | 0.42%   |
| Hewlett-Packard     | 3         | 3      | 0.42%   |
| Gigabyte Technology | 3         | 3      | 0.42%   |
| V-GeN               | 2         | 2      | 0.28%   |
| Leven               | 2         | 2      | 0.28%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.28%   |
| INNOVATION IT       | 2         | 2      | 0.28%   |
| Drevo               | 2         | 2      | 0.28%   |
| Dogfish             | 2         | 2      | 0.28%   |
| BHT                 | 2         | 2      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 757       | 788    | 40.9%   |
| SSD     | 674       | 732    | 36.41%  |
| NVMe    | 308       | 334    | 16.64%  |
| MMC     | 93        | 96     | 5.02%   |
| Unknown | 19        | 20     | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1305      | 1459   | 73.36%  |
| NVMe | 298       | 320    | 16.75%  |
| MMC  | 93        | 96     | 5.23%   |
| SAS  | 83        | 95     | 4.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1045      | 1139   | 74.06%  |
| 0.51-1.0   | 322       | 335    | 22.82%  |
| 1.01-2.0   | 38        | 40     | 2.69%   |
| 3.01-4.0   | 5         | 5      | 0.35%   |
| 4.01-10.0  | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 956       | 58.87%  |
| 101-250        | 250       | 15.39%  |
| 251-500        | 157       | 9.67%   |
| 501-1000       | 72        | 4.43%   |
| 51-100         | 67        | 4.13%   |
| 21-50          | 54        | 3.33%   |
| Unknown        | 46        | 2.83%   |
| 1001-2000      | 18        | 1.11%   |
| More than 3000 | 2         | 0.12%   |
| 2001-3000      | 2         | 0.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1465      | 90.21%  |
| Unknown        | 46        | 2.83%   |
| 51-100         | 32        | 1.97%   |
| 101-250        | 30        | 1.85%   |
| 21-50          | 29        | 1.79%   |
| 251-500        | 14        | 0.86%   |
| 1001-2000      | 4         | 0.25%   |
| 501-1000       | 2         | 0.12%   |
| More than 3000 | 1         | 0.06%   |
| 2001-3000      | 1         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 12        | 12     | 3.14%   |
| Toshiba MQ01ABF050 500GB                | 11        | 11     | 2.88%   |
| HGST HTS541010A9E680 1TB                | 10        | 10     | 2.62%   |
| Hitachi HTS543232A7A384 320GB           | 8         | 8      | 2.09%   |
| HGST HTS545050A7E680 500GB              | 8         | 8      | 2.09%   |
| Seagate ST500LT012-1DG142 500GB         | 7         | 7      | 1.83%   |
| Seagate ST9500325AS 500GB               | 6         | 6      | 1.57%   |
| Seagate ST9320325AS 320GB               | 6         | 6      | 1.57%   |
| HGST HTS721010A9E630 1TB                | 6         | 6      | 1.57%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 5      | 1.31%   |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 5      | 1.31%   |
| HGST HTS545050A7E380 500GB              | 5         | 5      | 1.31%   |
| Crucial CT240M500SSD1 240GB             | 5         | 5      | 1.31%   |
| Toshiba MK1246GSX 120GB                 | 4         | 4      | 1.05%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 4         | 4      | 1.05%   |
| Hitachi HTS547575A9E384 752GB           | 4         | 4      | 1.05%   |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 1.05%   |
| Crucial M4-CT256M4SSD3 256GB            | 4         | 4      | 1.05%   |
| WDC WD3200BPVT-24JJ5T0 320GB            | 3         | 3      | 0.79%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 3      | 0.79%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 3         | 3      | 0.79%   |
| Seagate ST9250410AS 250GB               | 3         | 3      | 0.79%   |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 3      | 0.79%   |
| Seagate ST500LM000-1EJ162 500GB         | 3         | 3      | 0.79%   |
| Kingston SV300S37A120G 120GB SSD        | 3         | 3      | 0.79%   |
| Hitachi HTS725032A7E630 320GB           | 3         | 3      | 0.79%   |
| Hitachi HTS547550A9E384 500GB           | 3         | 3      | 0.79%   |
| Hitachi HTS545050A7E380 500GB           | 3         | 3      | 0.79%   |
| Hitachi HTS541612J9SA00 120GB           | 3         | 3      | 0.79%   |
| HGST HTS541075A9E680 752GB              | 3         | 3      | 0.79%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 2      | 0.52%   |
| WDC WD5000BEVT-22A0RT0 500GB            | 2         | 2      | 0.52%   |
| WDC WD5000BEKT-75KA9T0 500GB            | 2         | 2      | 0.52%   |
| WDC WD3200BEVT-22A23T0 320GB            | 2         | 2      | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 2      | 0.52%   |
| Toshiba MQ01ABF032 320GB                | 2         | 2      | 0.52%   |
| Toshiba MK5061GSYN 500GB                | 2         | 2      | 0.52%   |
| Toshiba MK3265GSX 320GB                 | 2         | 2      | 0.52%   |
| Toshiba MK3256GSY 320GB                 | 2         | 2      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 83     | 21.52%  |
| Toshiba             | 66        | 66     | 17.32%  |
| Hitachi             | 56        | 56     | 14.7%   |
| WDC                 | 45        | 45     | 11.81%  |
| HGST                | 39        | 39     | 10.24%  |
| Samsung Electronics | 14        | 14     | 3.67%   |
| Crucial             | 13        | 13     | 3.41%   |
| Fujitsu             | 9         | 9      | 2.36%   |
| SK hynix            | 8         | 9      | 2.1%    |
| SanDisk             | 8         | 8      | 2.1%    |
| Kingston            | 7         | 7      | 1.84%   |
| A-DATA Technology   | 7         | 7      | 1.84%   |
| Micron Technology   | 4         | 4      | 1.05%   |
| Intel               | 4         | 4      | 1.05%   |
| China               | 3         | 3      | 0.79%   |
| LITEON              | 2         | 2      | 0.52%   |
| Corsair             | 2         | 2      | 0.52%   |
| ASMedia             | 2         | 2      | 0.52%   |
| Apple               | 2         | 2      | 0.52%   |
| Vaseky              | 1         | 1      | 0.26%   |
| Transcend           | 1         | 1      | 0.26%   |
| PNY                 | 1         | 1      | 0.26%   |
| Magnetic Data       | 1         | 1      | 0.26%   |
| KingSpec            | 1         | 1      | 0.26%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| Drevo               | 1         | 1      | 0.26%   |
| Dogfish             | 1         | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 83     | 27.06%  |
| Toshiba             | 63        | 63     | 20.79%  |
| Hitachi             | 56        | 56     | 18.48%  |
| WDC                 | 43        | 43     | 14.19%  |
| HGST                | 39        | 39     | 12.87%  |
| Fujitsu             | 9         | 9      | 2.97%   |
| Samsung Electronics | 7         | 7      | 2.31%   |
| ASMedia             | 2         | 2      | 0.66%   |
| Magnetic Data       | 1         | 1      | 0.33%   |
| Apple               | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 301       | 304    | 79.42%  |
| SSD  | 73        | 74     | 19.26%  |
| NVMe | 5         | 5      | 1.32%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB         | 2         | 2      | 15.38%  |
| WDC WD5000BEVT-22ZAT0 500GB         | 1         | 1      | 7.69%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 1      | 7.69%   |
| WDC WD2500BEVT-60ZCT1 250GB         | 1         | 1      | 7.69%   |
| WDC WD1600BEVT-75A23T0 160GB        | 1         | 1      | 7.69%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 7.69%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 7.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 7.69%   |
| Intel SSDSA2BW160G3 160GB           | 1         | 1      | 7.69%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 7.69%   |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 7      | 53.85%  |
| Toshiba | 2         | 2      | 15.38%  |
| Seagate | 1         | 1      | 7.69%   |
| Intel   | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| Apple   | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1210      | 1396   | 68.95%  |
| Malfunc  | 375       | 383    | 21.37%  |
| Detected | 157       | 178    | 8.95%   |
| Failed   | 13        | 13     | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1209      | 68.77%  |
| AMD                              | 241       | 13.71%  |
| Samsung Electronics              | 69        | 3.92%   |
| SK hynix                         | 54        | 3.07%   |
| SanDisk                          | 38        | 2.16%   |
| Kingston Technology Company      | 22        | 1.25%   |
| KIOXIA                           | 21        | 1.19%   |
| Nvidia                           | 16        | 0.91%   |
| Phison Electronics               | 14        | 0.8%    |
| Silicon Motion                   | 10        | 0.57%   |
| Micron Technology                | 10        | 0.57%   |
| Toshiba America Info Systems     | 8         | 0.46%   |
| Solid State Storage Technology   | 8         | 0.46%   |
| ADATA Technology                 | 8         | 0.46%   |
| Micron/Crucial Technology        | 6         | 0.34%   |
| Union Memory (Shenzhen)          | 5         | 0.28%   |
| Silicon Integrated Systems [SiS] | 4         | 0.23%   |
| ASMedia Technology               | 4         | 0.23%   |
| Realtek Semiconductor            | 3         | 0.17%   |
| Lite-On Technology               | 2         | 0.11%   |
| Yangtze Memory Technologies      | 1         | 0.06%   |
| Seagate Technology               | 1         | 0.06%   |
| Marvell Technology Group         | 1         | 0.06%   |
| JMicron Technology               | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 182       | 9.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 177       | 9.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 134       | 6.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 107       | 5.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 102       | 5.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 89        | 4.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 62        | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 58        | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 54        | 2.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 48        | 2.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 48        | 2.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 44        | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 43        | 2.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 36        | 1.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 34        | 1.77%   |
| Samsung NVMe SSD Controller 980                                                  | 28        | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 28        | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 26        | 1.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 25        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 23        | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 21        | 1.1%    |
| SK hynix Gold P31 SSD                                                            | 20        | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                              | 19        | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 19        | 0.99%   |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 18        | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 17        | 0.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 17        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 16        | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 15        | 0.78%   |
| SK hynix BC511                                                                   | 14        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 13        | 0.68%   |
| Intel Non-Volatile memory controller                                             | 11        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 10        | 0.52%   |
| Micron Non-Volatile memory controller                                            | 10        | 0.52%   |
| Intel SSD 660P Series                                                            | 10        | 0.52%   |
| Intel Comet Lake SATA AHCI Controller                                            | 10        | 0.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 0.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 0.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 9         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1281      | 69.09%  |
| NVMe | 297       | 16.02%  |
| IDE  | 151       | 8.14%   |
| RAID | 125       | 6.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1309      | 80.6%   |
| AMD    | 315       | 19.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 27        | 1.66%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 1.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 25        | 1.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 1.29%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 1.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 1.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 18        | 1.11%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 17        | 1.05%   |
| AMD 3020e with Radeon Graphics                | 17        | 1.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 16        | 0.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 15        | 0.92%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.8%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 13        | 0.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 13        | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 12        | 0.74%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 12        | 0.74%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 12        | 0.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 11        | 0.68%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.68%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 11        | 0.68%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 11        | 0.68%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.68%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 11        | 0.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 10        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 10        | 0.62%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 10        | 0.62%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 10        | 0.62%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 10        | 0.62%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 10        | 0.62%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 10        | 0.62%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 10        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 0.62%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 0.62%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 9         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 427       | 26.29%  |
| Intel Core i7           | 202       | 12.44%  |
| Intel Core i3           | 196       | 12.07%  |
| Intel Celeron           | 161       | 9.91%   |
| Intel Core 2 Duo        | 116       | 7.14%   |
| Intel Pentium           | 72        | 4.43%   |
| Other                   | 58        | 3.57%   |
| AMD Ryzen 5             | 45        | 2.77%   |
| AMD Ryzen 7             | 41        | 2.52%   |
| AMD E1                  | 25        | 1.54%   |
| Intel Pentium Dual-Core | 24        | 1.48%   |
| AMD A6                  | 24        | 1.48%   |
| AMD Ryzen 3             | 19        | 1.17%   |
| AMD E                   | 19        | 1.17%   |
| AMD A8                  | 17        | 1.05%   |
| Intel Pentium Silver    | 15        | 0.92%   |
| AMD A4                  | 15        | 0.92%   |
| Intel Atom              | 14        | 0.86%   |
| AMD A10                 | 14        | 0.86%   |
| Intel Pentium Dual      | 11        | 0.68%   |
| AMD E2                  | 9         | 0.55%   |
| AMD C-60                | 9         | 0.55%   |
| Intel Genuine           | 8         | 0.49%   |
| Intel Core 2            | 8         | 0.49%   |
| AMD Athlon              | 8         | 0.49%   |
| AMD Ryzen 9             | 5         | 0.31%   |
| Intel Celeron Dual-Core | 4         | 0.25%   |
| AMD Turion 64 X2 Mobile | 4         | 0.25%   |
| AMD Ryzen 7 PRO         | 4         | 0.25%   |
| Intel Core m5           | 3         | 0.18%   |
| Intel Core m3           | 3         | 0.18%   |
| Intel Core M            | 3         | 0.18%   |
| AMD Sempron             | 3         | 0.18%   |
| AMD Phenom II           | 3         | 0.18%   |
| AMD FX                  | 3         | 0.18%   |
| AMD Athlon II           | 3         | 0.18%   |
| Intel Core i9           | 2         | 0.12%   |
| Intel Core 2 Quad       | 2         | 0.12%   |
| Intel Celeron M         | 2         | 0.12%   |
| AMD Mobile Sempron      | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1126      | 69.33%  |
| 4      | 358       | 22.04%  |
| 6      | 50        | 3.08%   |
| 8      | 47        | 2.89%   |
| 1      | 41        | 2.52%   |
| 10     | 1         | 0.06%   |
| 3      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1624      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1004      | 61.82%  |
| 1      | 612       | 37.68%  |
| 8      | 8         | 0.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1623      | 99.94%  |
| Unknown        | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 159       | 9.79%   |
| 0x306a9    | 154       | 9.48%   |
| 0x1067a    | 89        | 5.48%   |
| 0x406e3    | 66        | 4.06%   |
| 0x20655    | 66        | 4.06%   |
| 0x306d4    | 64        | 3.94%   |
| 0x806e9    | 56        | 3.45%   |
| 0x806ec    | 51        | 3.14%   |
| 0x40651    | 51        | 3.14%   |
| 0x806ea    | 49        | 3.02%   |
| Unknown    | 49        | 3.02%   |
| 0x306c3    | 46        | 2.83%   |
| 0x6fd      | 45        | 2.77%   |
| 0x30678    | 39        | 2.4%    |
| 0x08108109 | 35        | 2.16%   |
| 0x706e5    | 30        | 1.85%   |
| 0x406c4    | 29        | 1.79%   |
| 0x20652    | 26        | 1.6%    |
| 0x10676    | 25        | 1.54%   |
| 0x06006705 | 25        | 1.54%   |
| 0x806c1    | 24        | 1.48%   |
| 0x906ea    | 23        | 1.42%   |
| 0x506e3    | 22        | 1.35%   |
| 0x706a8    | 21        | 1.29%   |
| 0x506c9    | 18        | 1.11%   |
| 0x07030105 | 18        | 1.11%   |
| 0x0500010d | 18        | 1.11%   |
| 0x08608103 | 17        | 1.05%   |
| 0x706a1    | 16        | 0.99%   |
| 0x08200103 | 16        | 0.99%   |
| 0x0a50000c | 14        | 0.86%   |
| 0x08108102 | 14        | 0.86%   |
| 0x906e9    | 12        | 0.74%   |
| 0x906c0    | 11        | 0.68%   |
| 0x08600106 | 11        | 0.68%   |
| 0x05000101 | 11        | 0.68%   |
| 0xa0652    | 10        | 0.62%   |
| 0x806eb    | 10        | 0.62%   |
| 0x406c3    | 10        | 0.62%   |
| 0x0700010b | 10        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 209       | 12.87%  |
| SandyBridge     | 160       | 9.85%   |
| IvyBridge       | 156       | 9.61%   |
| Penryn          | 114       | 7.02%   |
| Haswell         | 99        | 6.1%    |
| Westmere        | 93        | 5.73%   |
| Skylake         | 93        | 5.73%   |
| Silvermont      | 86        | 5.3%    |
| Core            | 74        | 4.56%   |
| Broadwell       | 66        | 4.06%   |
| Zen+            | 50        | 3.08%   |
| Bobcat          | 41        | 2.52%   |
| Goldmont plus   | 37        | 2.28%   |
| Excavator       | 34        | 2.09%   |
| IceLake         | 32        | 1.97%   |
| Unknown         | 28        | 1.72%   |
| TigerLake       | 26        | 1.6%    |
| Puma            | 26        | 1.6%    |
| Zen 2           | 25        | 1.54%   |
| Zen             | 21        | 1.29%   |
| Zen 3           | 20        | 1.23%   |
| Goldmont        | 19        | 1.17%   |
| Piledriver      | 17        | 1.05%   |
| Jaguar          | 16        | 0.99%   |
| K8 Hammer       | 13        | 0.8%    |
| CometLake       | 13        | 0.8%    |
| Bonnell         | 13        | 0.8%    |
| Tremont         | 11        | 0.68%   |
| K10             | 10        | 0.62%   |
| K10 Llano       | 9         | 0.55%   |
| K8 & K10 hybrid | 6         | 0.37%   |
| Steamroller     | 4         | 0.25%   |
| Nehalem         | 3         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1171      | 61.09%  |
| AMD                              | 400       | 20.87%  |
| Nvidia                           | 342       | 17.84%  |
| Silicon Integrated Systems [SiS] | 4         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 150       | 7.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 147       | 7.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 74        | 3.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 67        | 3.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 67        | 3.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 61        | 3.07%   |
| Intel HD Graphics 5500                                                                   | 57        | 2.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 50        | 2.52%   |
| Intel HD Graphics 620                                                                    | 48        | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47        | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 44        | 2.22%   |
| Intel UHD Graphics 620                                                                   | 44        | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 39        | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 39        | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 35        | 1.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 35        | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 31        | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 27        | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 1.16%   |
| AMD Renoir                                                                               | 23        | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 21        | 1.06%   |
| AMD Lucienne                                                                             | 21        | 1.06%   |
| Intel HD Graphics 530                                                                    | 19        | 0.96%   |
| AMD Cezanne                                                                              | 19        | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 0.86%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 17        | 0.86%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 13        | 0.65%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 13        | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 12        | 0.6%    |
| Intel HD Graphics 500                                                                    | 12        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.55%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 11        | 0.55%   |
| Intel JasperLake [UHD Graphics]                                                          | 11        | 0.55%   |
| Intel HD Graphics 630                                                                    | 11        | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                                             | 10        | 0.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.5%    |
| AMD Wrestler [Radeon HD 6320]                                                            | 9         | 0.45%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 9         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 891       | 54.86%  |
| 1 x AMD        | 308       | 18.97%  |
| Intel + Nvidia | 231       | 14.22%  |
| 1 x Nvidia     | 97        | 5.97%   |
| Intel + AMD    | 48        | 2.96%   |
| 2 x AMD        | 31        | 1.91%   |
| AMD + Nvidia   | 13        | 0.8%    |
| 1 x SiS        | 4         | 0.25%   |
| 2 x Nvidia     | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1604      | 98.77%  |
| Unknown     | 19        | 1.17%   |
| Proprietary | 1         | 0.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 947       | 58.31%  |
| 0.01-0.5   | 292       | 17.98%  |
| 1.01-2.0   | 160       | 9.85%   |
| 0.51-1.0   | 128       | 7.88%   |
| 3.01-4.0   | 59        | 3.63%   |
| 5.01-6.0   | 21        | 1.29%   |
| 7.01-8.0   | 11        | 0.68%   |
| 2.01-3.0   | 5         | 0.31%   |
| 8.01-16.0  | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 357       | 21.33%  |
| LG Display              | 311       | 18.58%  |
| Chimei Innolux          | 254       | 15.17%  |
| BOE                     | 214       | 12.78%  |
| Samsung Electronics     | 182       | 10.87%  |
| Chi Mei Optoelectronics | 60        | 3.58%   |
| Lenovo                  | 38        | 2.27%   |
| Apple                   | 26        | 1.55%   |
| Sharp                   | 20        | 1.19%   |
| LG Philips              | 19        | 1.14%   |
| InfoVision              | 17        | 1.02%   |
| Hewlett-Packard         | 16        | 0.96%   |
| Dell                    | 16        | 0.96%   |
| Goldstar                | 15        | 0.9%    |
| PANDA                   | 11        | 0.66%   |
| Toshiba                 | 9         | 0.54%   |
| Philips                 | 9         | 0.54%   |
| BenQ                    | 9         | 0.54%   |
| Sony                    | 8         | 0.48%   |
| CPT                     | 7         | 0.42%   |
| AOC                     | 7         | 0.42%   |
| Iiyama                  | 6         | 0.36%   |
| CSO                     | 5         | 0.3%    |
| Acer                    | 5         | 0.3%    |
| Eizo                    | 4         | 0.24%   |
| ___                     | 3         | 0.18%   |
| Unknown                 | 3         | 0.18%   |
| HannStar                | 3         | 0.18%   |
| Ancor Communications    | 3         | 0.18%   |
| Vizio                   | 2         | 0.12%   |
| ViewSonic               | 2         | 0.12%   |
| Vestel Elektronik       | 2         | 0.12%   |
| Quanta Display          | 2         | 0.12%   |
| NEC Computers           | 2         | 0.12%   |
| KDC                     | 2         | 0.12%   |
| InnoLux Display         | 2         | 0.12%   |
| IBM                     | 2         | 0.12%   |
| ASUSTek Computer        | 2         | 0.12%   |
| Xiaomi                  | 1         | 0.06%   |
| TMX                     | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 1.19%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 17        | 1.01%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.95%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 14        | 0.83%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.77%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.66%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 10        | 0.6%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 10        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 9         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.54%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 9         | 0.54%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 9         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 8         | 0.48%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 8         | 0.48%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 8         | 0.48%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                    | 8         | 0.48%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.48%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 7         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 7         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 7         | 0.42%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 7         | 0.42%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 7         | 0.42%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 7         | 0.42%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch             | 6         | 0.36%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 6         | 0.36%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 6         | 0.36%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 6         | 0.36%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 6         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.36%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 764       | 46.87%  |
| 1920x1080 (FHD)    | 512       | 31.41%  |
| 1600x900 (HD+)     | 112       | 6.87%   |
| 1280x800 (WXGA)    | 87        | 5.34%   |
| 1440x900 (WXGA+)   | 34        | 2.09%   |
| 3840x2160 (4K)     | 27        | 1.66%   |
| 2560x1440 (QHD)    | 16        | 0.98%   |
| 1920x1200 (WUXGA)  | 15        | 0.92%   |
| 1680x1050 (WSXGA+) | 13        | 0.8%    |
| 3200x1800 (QHD+)   | 7         | 0.43%   |
| 2560x1600          | 6         | 0.37%   |
| 1280x1024 (SXGA)   | 6         | 0.37%   |
| 1920x1280          | 4         | 0.25%   |
| 1360x768           | 4         | 0.25%   |
| 1024x600           | 4         | 0.25%   |
| 2880x1800          | 3         | 0.18%   |
| 2160x1440          | 3         | 0.18%   |
| 2256x1504          | 2         | 0.12%   |
| 1680x945           | 2         | 0.12%   |
| 1024x768 (XGA)     | 2         | 0.12%   |
| 3840x2400          | 1         | 0.06%   |
| 3840x1080          | 1         | 0.06%   |
| 3456x2160          | 1         | 0.06%   |
| 3200x2000          | 1         | 0.06%   |
| 2560x1080          | 1         | 0.06%   |
| 2288x1287          | 1         | 0.06%   |
| 1400x1050          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 750       | 44.75%  |
| 13      | 281       | 16.77%  |
| 14      | 180       | 10.74%  |
| 17      | 160       | 9.55%   |
| 12      | 69        | 4.12%   |
| 11      | 53        | 3.16%   |
| 24      | 26        | 1.55%   |
| 23      | 24        | 1.43%   |
| 27      | 22        | 1.31%   |
| 21      | 17        | 1.01%   |
| 18      | 13        | 0.78%   |
| 16      | 11        | 0.66%   |
| 31      | 10        | 0.6%    |
| 19      | 9         | 0.54%   |
| 10      | 7         | 0.42%   |
| 84      | 4         | 0.24%   |
| 54      | 4         | 0.24%   |
| 32      | 4         | 0.24%   |
| 22      | 4         | 0.24%   |
| 20      | 4         | 0.24%   |
| 65      | 3         | 0.18%   |
| 74      | 2         | 0.12%   |
| 72      | 2         | 0.12%   |
| 26      | 2         | 0.12%   |
| Unknown | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 55      | 1         | 0.06%   |
| 50      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 34      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |
| 25      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1061      | 63.38%  |
| 201-300        | 263       | 15.71%  |
| 351-400        | 192       | 11.47%  |
| 501-600        | 69        | 4.12%   |
| 401-500        | 42        | 2.51%   |
| 601-700        | 15        | 0.9%    |
| 1001-1500      | 12        | 0.72%   |
| 1501-2000      | 8         | 0.48%   |
| 701-800        | 6         | 0.36%   |
| 801-900        | 3         | 0.18%   |
| Unknown        | 2         | 0.12%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 1393      | 88.16%  |
| 16/10 | 160       | 10.13%  |
| 3/2   | 13        | 0.82%   |
| 5/4   | 6         | 0.38%   |
| 4/3   | 5         | 0.32%   |
| 32/9  | 1         | 0.06%   |
| 21/9  | 1         | 0.06%   |
| 1.00  | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 752       | 44.84%  |
| 81-90          | 344       | 20.51%  |
| 121-130        | 133       | 7.93%   |
| 71-80          | 118       | 7.04%   |
| 61-70          | 67        | 4%      |
| 201-250        | 60        | 3.58%   |
| 51-60          | 53        | 3.16%   |
| 131-140        | 27        | 1.61%   |
| 301-350        | 24        | 1.43%   |
| More than 1000 | 19        | 1.13%   |
| 351-500        | 16        | 0.95%   |
| 151-200        | 14        | 0.83%   |
| 141-150        | 13        | 0.78%   |
| 251-300        | 12        | 0.72%   |
| 41-50          | 7         | 0.42%   |
| 501-1000       | 6         | 0.36%   |
| 111-120        | 5         | 0.3%    |
| 91-100         | 5         | 0.3%    |
| Unknown        | 2         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 741       | 44.58%  |
| 121-160       | 558       | 33.57%  |
| 51-100        | 240       | 14.44%  |
| 161-240       | 88        | 5.29%   |
| More than 240 | 17        | 1.02%   |
| 1-50          | 16        | 0.96%   |
| Unknown       | 2         | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1482      | 91.26%  |
| 2     | 130       | 8%      |
| 0     | 7         | 0.43%   |
| 3     | 5         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 921       | 35.51%  |
| Intel                             | 747       | 28.8%   |
| Qualcomm Atheros                  | 474       | 18.27%  |
| Broadcom                          | 162       | 6.25%   |
| Ralink                            | 45        | 1.73%   |
| Marvell Technology Group          | 42        | 1.62%   |
| Broadcom Limited                  | 32        | 1.23%   |
| MediaTek                          | 17        | 0.66%   |
| Ericsson Business Mobile Networks | 16        | 0.62%   |
| Dell                              | 15        | 0.58%   |
| JMicron Technology                | 13        | 0.5%    |
| TP-Link                           | 12        | 0.46%   |
| Nvidia                            | 12        | 0.46%   |
| Ralink Technology                 | 10        | 0.39%   |
| Huawei Technologies               | 9         | 0.35%   |
| Samsung Electronics               | 8         | 0.31%   |
| Sierra Wireless                   | 7         | 0.27%   |
| Hewlett-Packard                   | 7         | 0.27%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.15%   |
| ASIX Electronics                  | 4         | 0.15%   |
| Xiaomi                            | 3         | 0.12%   |
| Motorola PCS                      | 3         | 0.12%   |
| Google                            | 3         | 0.12%   |
| D-Link                            | 3         | 0.12%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.08%   |
| NetGear                           | 2         | 0.08%   |
| Linksys                           | 2         | 0.08%   |
| AVM                               | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| U-Blox                            | 1         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.04%   |
| Spreadtrum Communications         | 1         | 0.04%   |
| Sigma Sport                       | 1         | 0.04%   |
| Shenzhen Goodix Technology        | 1         | 0.04%   |
| Qualcomm                          | 1         | 0.04%   |
| OPPO Electronics                  | 1         | 0.04%   |
| Lenovo                            | 1         | 0.04%   |
| ICS Advent                        | 1         | 0.04%   |
| HTC (High Tech Computer)          | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 528       | 16.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 214       | 6.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 86        | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 77        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 74        | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 74        | 2.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 71        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 62        | 1.99%   |
| Intel Wireless 7265                                               | 59        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 59        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 48        | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 46        | 1.48%   |
| Intel Wireless 8265 / 8275                                        | 42        | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 42        | 1.35%   |
| Intel Wireless 8260                                               | 37        | 1.19%   |
| Intel Wireless 7260                                               | 37        | 1.19%   |
| Intel Wireless 3165                                               | 36        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 36        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 32        | 1.03%   |
| Intel Wireless 3160                                               | 30        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 29        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 0.71%   |
| Intel Centrino Wireless-N 2230                                    | 22        | 0.71%   |
| Intel Centrino Ultimate-N 6300                                    | 22        | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 21        | 0.67%   |
| Intel WiFi Link 5100                                              | 21        | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 21        | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 20        | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 19        | 0.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 19        | 0.61%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 19        | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 18        | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 18        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18        | 0.58%   |
| Intel Centrino Advanced-N 6200                                    | 18        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 708       | 42.34%  |
| Qualcomm Atheros                  | 408       | 24.4%   |
| Realtek Semiconductor             | 308       | 18.42%  |
| Broadcom                          | 123       | 7.36%   |
| Ralink                            | 45        | 2.69%   |
| Broadcom Limited                  | 19        | 1.14%   |
| MediaTek                          | 17        | 1.02%   |
| Ralink Technology                 | 10        | 0.6%    |
| Dell                              | 8         | 0.48%   |
| Sierra Wireless                   | 7         | 0.42%   |
| Hewlett-Packard                   | 3         | 0.18%   |
| Ericsson Business Mobile Networks | 3         | 0.18%   |
| D-Link                            | 3         | 0.18%   |
| TP-Link                           | 2         | 0.12%   |
| Qualcomm Atheros Communications   | 2         | 0.12%   |
| Linksys                           | 2         | 0.12%   |
| AVM                               | 2         | 0.12%   |
| D-Link System                     | 1         | 0.06%   |
| ASUSTek Computer                  | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 77        | 4.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 74        | 4.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 74        | 4.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 71        | 4.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 62        | 3.7%    |
| Intel Wireless 7265                                                     | 59        | 3.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 59        | 3.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 48        | 2.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 46        | 2.75%   |
| Intel Wireless 8265 / 8275                                              | 42        | 2.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 2.51%   |
| Intel Wireless 8260                                                     | 37        | 2.21%   |
| Intel Wireless 7260                                                     | 37        | 2.21%   |
| Intel Wireless 3165                                                     | 36        | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 2.03%   |
| Intel Wi-Fi 6 AX200                                                     | 32        | 1.91%   |
| Intel Wireless 3160                                                     | 30        | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 29        | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 22        | 1.31%   |
| Intel Centrino Wireless-N 2230                                          | 22        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                          | 22        | 1.31%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 21        | 1.25%   |
| Intel WiFi Link 5100                                                    | 21        | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 21        | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 20        | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 19        | 1.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 19        | 1.13%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 18        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 18        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 18        | 1.07%   |
| Intel Centrino Advanced-N 6200                                          | 18        | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 17        | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 0.84%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 14        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 13        | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 13        | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 12        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 791       | 56.46%  |
| Intel                            | 281       | 20.06%  |
| Qualcomm Atheros                 | 125       | 8.92%   |
| Broadcom                         | 69        | 4.93%   |
| Marvell Technology Group         | 42        | 3%      |
| JMicron Technology               | 13        | 0.93%   |
| Broadcom Limited                 | 13        | 0.93%   |
| Nvidia                           | 12        | 0.86%   |
| TP-Link                          | 10        | 0.71%   |
| Samsung Electronics              | 8         | 0.57%   |
| Huawei Technologies              | 5         | 0.36%   |
| Silicon Integrated Systems [SiS] | 4         | 0.29%   |
| ASIX Electronics                 | 4         | 0.29%   |
| Xiaomi                           | 3         | 0.21%   |
| Hewlett-Packard                  | 3         | 0.21%   |
| Google                           | 3         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.14%   |
| NetGear                          | 2         | 0.14%   |
| Motorola PCS                     | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.07%   |
| T & A Mobile Phones              | 1         | 0.07%   |
| Spreadtrum Communications        | 1         | 0.07%   |
| Qualcomm                         | 1         | 0.07%   |
| OPPO Electronics                 | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |
| HTC (High Tech Computer)         | 1         | 0.07%   |
| DisplayLink                      | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 528       | 37.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 214       | 15.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 86        | 6.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 34        | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 23        | 1.63%   |
| Intel 82577LM Gigabit Network Connection                                       | 20        | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                                          | 19        | 1.35%   |
| Intel Ethernet Connection I219-LM                                              | 18        | 1.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 17        | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 17        | 1.2%    |
| Intel 82567LM Gigabit Network Connection                                       | 17        | 1.2%    |
| Intel 82579V Gigabit Network Connection                                        | 14        | 0.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 13        | 0.92%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 0.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 11        | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 11        | 0.78%   |
| Intel 82566MM Gigabit Network Connection                                       | 11        | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 11        | 0.78%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 10        | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 10        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 10        | 0.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 9         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.64%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 9         | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 9         | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.5%    |
| Nvidia MCP79 Ethernet                                                          | 7         | 0.5%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 7         | 0.5%    |
| Intel Ethernet Connection I219-V                                               | 7         | 0.5%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 7         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 7         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 0.43%   |
| Intel WiMAX Connection 2400m                                                   | 6         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 5         | 0.35%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 5         | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1613      | 53.53%  |
| Ethernet | 1369      | 45.44%  |
| Modem    | 28        | 0.93%   |
| Unknown  | 3         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1137      | 71.51%  |
| Ethernet | 453       | 28.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1282      | 78.94%  |
| 1     | 319       | 19.64%  |
| 0     | 14        | 0.86%   |
| 3     | 9         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1151      | 70.87%  |
| Yes  | 473       | 29.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 475       | 38.93%  |
| Realtek Semiconductor           | 137       | 11.23%  |
| Qualcomm Atheros Communications | 135       | 11.07%  |
| Broadcom                        | 101       | 8.28%   |
| Lite-On Technology              | 77        | 6.31%   |
| IMC Networks                    | 57        | 4.67%   |
| Foxconn / Hon Hai               | 49        | 4.02%   |
| Dell                            | 33        | 2.7%    |
| Toshiba                         | 28        | 2.3%    |
| Apple                           | 27        | 2.21%   |
| Hewlett-Packard                 | 21        | 1.72%   |
| Ralink                          | 20        | 1.64%   |
| Cambridge Silicon Radio         | 16        | 1.31%   |
| ASUSTek Computer                | 8         | 0.66%   |
| Realtek                         | 6         | 0.49%   |
| Ralink Technology               | 6         | 0.49%   |
| Alps Electric                   | 6         | 0.49%   |
| Fujitsu                         | 3         | 0.25%   |
| Foxconn International           | 3         | 0.25%   |
| MediaTek                        | 2         | 0.16%   |
| Chicony Electronics             | 2         | 0.16%   |
| Askey Computer                  | 2         | 0.16%   |
| USI                             | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |
| Taiyo Yuden                     | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 248       | 20.33%  |
| Realtek Bluetooth Radio                                                             | 84        | 6.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 75        | 6.15%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 53        | 4.34%   |
| Intel AX201 Bluetooth                                                               | 45        | 3.69%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 43        | 3.52%   |
| Intel AX200 Bluetooth                                                               | 32        | 2.62%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 30        | 2.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 25        | 2.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 25        | 2.05%   |
| IMC Networks Bluetooth Radio                                                        | 25        | 2.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 25        | 2.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 23        | 1.89%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 23        | 1.89%   |
| Lite-On Bluetooth Device                                                            | 22        | 1.8%    |
| IMC Networks Bluetooth Device                                                       | 21        | 1.72%   |
| Ralink RT3290 Bluetooth                                                             | 20        | 1.64%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 20        | 1.64%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 18        | 1.48%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 18        | 1.48%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 1.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 1.31%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 15        | 1.23%   |
| Apple Bluetooth Host Controller                                                     | 14        | 1.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 10        | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 0.82%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 9         | 0.74%   |
| Toshiba RT Bluetooth Radio                                                          | 8         | 0.66%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.66%   |
| Broadcom BCM2045 Bluetooth                                                          | 8         | 0.66%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 0.66%   |
| Realtek RTL8723B Bluetooth                                                          | 7         | 0.57%   |
| Intel AX210 Bluetooth                                                               | 7         | 0.57%   |
| Toshiba Integrated Bluetooth HCI                                                    | 6         | 0.49%   |
| Realtek Bluetooth Radio                                                             | 6         | 0.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 0.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 6         | 0.49%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 6         | 0.49%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 6         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1292      | 69.05%  |
| AMD                                          | 352       | 18.81%  |
| Nvidia                                       | 186       | 9.94%   |
| Logitech                                     | 6         | 0.32%   |
| Generalplus Technology                       | 5         | 0.27%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.21%   |
| Realtek Semiconductor                        | 3         | 0.16%   |
| C-Media Electronics                          | 3         | 0.16%   |
| Texas Instruments                            | 2         | 0.11%   |
| Lenovo                                       | 2         | 0.11%   |
| JMTek                                        | 2         | 0.11%   |
| Conexant Systems                             | 2         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.05%   |
| XMOS                                         | 1         | 0.05%   |
| Schiit Audio                                 | 1         | 0.05%   |
| Samsung Electronics                          | 1         | 0.05%   |
| Samson Technologies                          | 1         | 0.05%   |
| Plantronics                                  | 1         | 0.05%   |
| Native Instruments                           | 1         | 0.05%   |
| M-Audio                                      | 1         | 0.05%   |
| Focusrite-Novation                           | 1         | 0.05%   |
| Creative Technology                          | 1         | 0.05%   |
| Cambridge Audio                              | 1         | 0.05%   |
| Apple                                        | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 195       | 8.43%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 173       | 7.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 138       | 5.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 121       | 5.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 103       | 4.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 96        | 4.15%   |
| AMD FCH Azalia Controller                                                                         | 83        | 3.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 67        | 2.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 66        | 2.85%   |
| Intel Broadwell-U Audio Controller                                                                | 66        | 2.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 61        | 2.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 53        | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 51        | 2.2%    |
| Intel 8 Series HD Audio Controller                                                                | 51        | 2.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 51        | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 49        | 2.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 49        | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 48        | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 47        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 38        | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 37        | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 36        | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 34        | 1.47%   |
| AMD Wrestler HDMI Audio                                                                           | 33        | 1.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 1.25%   |
| AMD High Definition Audio Controller                                                              | 27        | 1.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 26        | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 25        | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 25        | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 19        | 0.82%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 16        | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 0.52%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 11        | 0.48%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 11        | 0.48%   |
| Intel Jasper Lake HD Audio                                                                        | 11        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 533       | 27.24%  |
| SK hynix            | 441       | 22.53%  |
| Micron Technology   | 214       | 10.94%  |
| Unknown             | 168       | 8.58%   |
| Kingston            | 152       | 7.77%   |
| Crucial             | 63        | 3.22%   |
| A-DATA Technology   | 49        | 2.5%    |
| Ramaxel Technology  | 48        | 2.45%   |
| Elpida              | 43        | 2.2%    |
| Smart               | 31        | 1.58%   |
| Nanya Technology    | 28        | 1.43%   |
| Corsair             | 22        | 1.12%   |
| Unknown (ABCD)      | 18        | 0.92%   |
| Unknown             | 13        | 0.66%   |
| Teikon              | 12        | 0.61%   |
| G.Skill             | 9         | 0.46%   |
| Team                | 8         | 0.41%   |
| ASint Technology    | 8         | 0.41%   |
| Patriot             | 7         | 0.36%   |
| Smart Brazil        | 6         | 0.31%   |
| Qimonda             | 5         | 0.26%   |
| CSX                 | 5         | 0.26%   |
| Apacer              | 5         | 0.26%   |
| AMD                 | 5         | 0.26%   |
| Multilaser          | 4         | 0.2%    |
| High Bridge         | 4         | 0.2%    |
| Goodram             | 4         | 0.2%    |
| Goldkey             | 4         | 0.2%    |
| Toshiba             | 3         | 0.15%   |
| 48spaces            | 3         | 0.15%   |
| Timetec             | 2         | 0.1%    |
| Silicon Power       | 2         | 0.1%    |
| Sesame              | 2         | 0.1%    |
| Netlist             | 2         | 0.1%    |
| HT Micron           | 2         | 0.1%    |
| Avant               | 2         | 0.1%    |
| V-Color             | 1         | 0.05%   |
| Unknown (8A02)      | 1         | 0.05%   |
| Unknown (0xAD0A)    | 1         | 0.05%   |
| Unknown (0x89AD)    | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 43        | 2.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 43        | 2.05%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 39        | 1.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 1.81%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 36        | 1.71%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 25        | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 23        | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 21        | 1%      |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 20        | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 18        | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 18        | 0.86%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.86%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.81%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 16        | 0.76%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.76%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 16        | 0.76%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.71%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 15        | 0.71%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 15        | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 14        | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.62%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 13        | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.62%   |
| Unknown                                                          | 13        | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 12        | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.57%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 12        | 0.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 11        | 0.52%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 11        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 11        | 0.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 821       | 50.49%  |
| DDR4    | 515       | 31.67%  |
| DDR2    | 135       | 8.3%    |
| LPDDR4  | 57        | 3.51%   |
| SDRAM   | 44        | 2.71%   |
| LPDDR3  | 22        | 1.35%   |
| Unknown | 15        | 0.92%   |
| DRAM    | 9         | 0.55%   |
| DDR     | 6         | 0.37%   |
| DDR5    | 2         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1532      | 94.74%  |
| Row Of Chips | 68        | 4.21%   |
| Chip         | 10        | 0.62%   |
| Unknown      | 4         | 0.25%   |
| DIMM         | 3         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 815       | 45.38%  |
| 8192  | 468       | 26.06%  |
| 2048  | 360       | 20.04%  |
| 1024  | 69        | 3.84%   |
| 16384 | 64        | 3.56%   |
| 32768 | 17        | 0.95%   |
| 512   | 3         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 552       | 30.72%  |
| 2667    | 255       | 14.19%  |
| 3200    | 162       | 9.02%   |
| 1334    | 155       | 8.63%   |
| 2400    | 128       | 7.12%   |
| 1333    | 104       | 5.79%   |
| 667     | 71        | 3.95%   |
| 1067    | 57        | 3.17%   |
| Unknown | 49        | 2.73%   |
| 2133    | 43        | 2.39%   |
| 800     | 43        | 2.39%   |
| 1867    | 25        | 1.39%   |
| 3266    | 23        | 1.28%   |
| 4199    | 21        | 1.17%   |
| 2048    | 19        | 1.06%   |
| 975     | 16        | 0.89%   |
| 1066    | 13        | 0.72%   |
| 4267    | 12        | 0.67%   |
| 533     | 10        | 0.56%   |
| 1866    | 9         | 0.5%    |
| 8400    | 7         | 0.39%   |
| 4266    | 7         | 0.39%   |
| 333     | 4         | 0.22%   |
| 2933    | 3         | 0.17%   |
| 1639    | 3         | 0.17%   |
| 4800    | 2         | 0.11%   |
| 3733    | 2         | 0.11%   |
| 2267    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 41.67%  |
| Brother Industries | 4         | 33.33%  |
| Canon              | 3         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother DCP-7055W   | 4         | 33.33%  |
| HP OfficeJet Pro 69 | 1         | 8.33%   |
| HP OfficeJet 4300   | 1         | 8.33%   |
| HP LaserJet 1018    | 1         | 8.33%   |
| HP DeskJet D1360    | 1         | 8.33%   |
| HP DeskJet 6122     | 1         | 8.33%   |
| Canon PIXMA MP280   | 1         | 8.33%   |
| Canon MP160         | 1         | 8.33%   |
| Canon G3000 series  | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 50%     |
| Canon CanoScan LiDE 600F                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 383       | 27.26%  |
| Realtek Semiconductor                  | 146       | 10.39%  |
| Microdia                               | 143       | 10.18%  |
| IMC Networks                           | 101       | 7.19%   |
| Acer                                   | 87        | 6.19%   |
| Sunplus Innovation Technology          | 74        | 5.27%   |
| Suyin                                  | 65        | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 4.56%   |
| Quanta                                 | 60        | 4.27%   |
| Syntek                                 | 42        | 2.99%   |
| Lite-On Technology                     | 37        | 2.63%   |
| Silicon Motion                         | 31        | 2.21%   |
| Ricoh                                  | 27        | 1.92%   |
| Apple                                  | 23        | 1.64%   |
| Alcor Micro                            | 21        | 1.49%   |
| ALi                                    | 17        | 1.21%   |
| Lenovo                                 | 13        | 0.93%   |
| Importek                               | 12        | 0.85%   |
| Luxvisions Innotech Limited            | 11        | 0.78%   |
| Primax Electronics                     | 9         | 0.64%   |
| Sonix Technology                       | 8         | 0.57%   |
| Z-Star Microelectronics                | 5         | 0.36%   |
| DigiTech                               | 5         | 0.36%   |
| Sunplus Technology                     | 3         | 0.21%   |
| Logitech                               | 3         | 0.21%   |
| Nebraska Furniture Mart                | 2         | 0.14%   |
| GEMBIRD                                | 2         | 0.14%   |
| WaveRider Communications               | 1         | 0.07%   |
| Unknown                                | 1         | 0.07%   |
| Tobii Technology AB                    | 1         | 0.07%   |
| SunplusIT                              | 1         | 0.07%   |
| OmniVision Technologies                | 1         | 0.07%   |
| Novatek Microelectronics               | 1         | 0.07%   |
| LG Electronics                         | 1         | 0.07%   |
| Intel                                  | 1         | 0.07%   |
| HRY                                    | 1         | 0.07%   |
| Cubeternet                             | 1         | 0.07%   |
| BUFFALO                                | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 52        | 3.69%   |
| Chicony Integrated Camera                           | 51        | 3.62%   |
| Chicony HD WebCam                                   | 42        | 2.98%   |
| Realtek Integrated_Webcam_HD                        | 36        | 2.56%   |
| Microdia Integrated Webcam                          | 23        | 1.63%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 22        | 1.56%   |
| Sunplus Integrated_Webcam_HD                        | 19        | 1.35%   |
| IMC Networks Integrated Camera                      | 19        | 1.35%   |
| Chicony USB 2.0 Camera                              | 19        | 1.35%   |
| Syntek Integrated Camera                            | 17        | 1.21%   |
| Realtek USB Camera                                  | 17        | 1.21%   |
| Chicony VGA WebCam                                  | 17        | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam                       | 17        | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                     | 17        | 1.21%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 16        | 1.14%   |
| Chicony Lenovo EasyCamera                           | 15        | 1.06%   |
| Chicony FJ Camera                                   | 15        | 1.06%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 13        | 0.92%   |
| Acer Lenovo EasyCamera                              | 13        | 0.92%   |
| Acer Integrated Camera                              | 13        | 0.92%   |
| Realtek Lenovo EasyCamera                           | 12        | 0.85%   |
| Realtek EasyCamera                                  | 12        | 0.85%   |
| Quanta HD User Facing                               | 12        | 0.85%   |
| Chicony HP Truevision HD camera                     | 12        | 0.85%   |
| Sunplus HD WebCam                                   | 11        | 0.78%   |
| Realtek USB2.0 HD UVC WebCam                        | 11        | 0.78%   |
| Microdia USB 2.0 Camera                             | 11        | 0.78%   |
| Lite-On Integrated Camera                           | 11        | 0.78%   |
| Lite-On HP HD Webcam                                | 11        | 0.78%   |
| Chicony USB2.0 HD UVC WebCam                        | 11        | 0.78%   |
| Chicony HD User Facing                              | 11        | 0.78%   |
| Apple Built-in iSight                               | 11        | 0.78%   |
| ALi Gateway Webcam                                  | 11        | 0.78%   |
| Syntek Lenovo EasyCamera                            | 10        | 0.71%   |
| Quanta HP TrueVision HD Camera                      | 10        | 0.71%   |
| Quanta HD Webcam                                    | 10        | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 10        | 0.71%   |
| Chicony HP Webcam                                   | 10        | 0.71%   |
| Chicony HP Truevision HD                            | 10        | 0.71%   |
| Chicony EasyCamera                                  | 10        | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 57        | 37.01%  |
| AuthenTec                  | 23        | 14.94%  |
| Upek                       | 16        | 10.39%  |
| Elan Microelectronics      | 15        | 9.74%   |
| Synaptics                  | 13        | 8.44%   |
| Shenzhen Goodix Technology | 11        | 7.14%   |
| STMicroelectronics         | 8         | 5.19%   |
| LighTuning Technology      | 8         | 5.19%   |
| Samsung Electronics        | 1         | 0.65%   |
| HOLTEK                     | 1         | 0.65%   |
| Focal-systems.Corp         | 1         | 0.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                  | 15        | 9.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 15        | 9.74%   |
| Shenzhen Goodix  FingerPrint Device                         | 9         | 5.84%   |
| STMicroelectronics Fingerprint Reader                       | 8         | 5.19%   |
| Elan ELAN:ARM-M4                                            | 8         | 5.19%   |
| Validity Sensors VFS491                                     | 7         | 4.55%   |
| Elan ELAN:Fingerprint                                       | 7         | 4.55%   |
| AuthenTec AES2810                                           | 6         | 3.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 5         | 3.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 3.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 5         | 3.25%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 5         | 3.25%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 5         | 3.25%   |
| AuthenTec AES1600                                           | 5         | 3.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 2.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 4         | 2.6%    |
| Unknown                                                     | 4         | 2.6%    |
| Validity Sensors VFS471 Fingerprint Reader                  | 3         | 1.95%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.95%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 3         | 1.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                   | 3         | 1.95%   |
| AuthenTec Fingerprint Sensor                                | 3         | 1.95%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.95%   |
| Validity Sensors Fingerprint scanner                        | 2         | 1.3%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.65%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 1         | 0.65%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 0.65%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.65%   |
| Synaptics WBDI Device                                       | 1         | 0.65%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 1         | 0.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 0.65%   |
| Shenzhen Goodix Fingerprint Reader                          | 1         | 0.65%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 0.65%   |
| Samsung Fingerprint Sensor Device - 730B                    | 1         | 0.65%   |
| LighTuning Fingerprint Reader                               | 1         | 0.65%   |
| HOLTEK FocalTech Fingerprint Device                         | 1         | 0.65%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 0.65%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 61        | 54.46%  |
| O2 Micro              | 15        | 13.39%  |
| Alcor Micro           | 14        | 12.5%   |
| Upek                  | 11        | 9.82%   |
| Lenovo                | 8         | 7.14%   |
| SCM Microsystems      | 2         | 1.79%   |
| Gemalto (was Gemplus) | 1         | 0.89%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 28        | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 16.07%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 11.61%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 9.82%   |
| Broadcom 5880                                                                | 10        | 8.93%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 7.14%   |
| Broadcom 58200                                                               | 5         | 4.46%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.89%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.89%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.89%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1247      | 76.79%  |
| 1     | 316       | 19.46%  |
| 2     | 54        | 3.33%   |
| 3     | 6         | 0.37%   |
| 6     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 154       | 35.08%  |
| Chipcard                 | 110       | 25.06%  |
| Graphics card            | 51        | 11.62%  |
| Bluetooth                | 37        | 8.43%   |
| Net/wireless             | 29        | 6.61%   |
| Storage                  | 20        | 4.56%   |
| Multimedia controller    | 14        | 3.19%   |
| Camera                   | 10        | 2.28%   |
| Communication controller | 5         | 1.14%   |
| Sound                    | 3         | 0.68%   |
| Network                  | 3         | 0.68%   |
| Flash memory             | 3         | 0.68%   |

