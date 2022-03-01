Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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
| Philco        | O E M                       | [47cc99022d](https://linux-hardware.org/?probe=47cc99022d) | Mar 01, 2022 |
| Dell          | Inspiron N5110              | [6cec0db416](https://linux-hardware.org/?probe=6cec0db416) | Mar 01, 2022 |
| Dell          | Inspiron N5110              | [c88c351a35](https://linux-hardware.org/?probe=c88c351a35) | Mar 01, 2022 |
| HP            | Laptop 15-db1xxx            | [03394e745c](https://linux-hardware.org/?probe=03394e745c) | Feb 28, 2022 |
| Acer          | Swift SF314-41              | [23c2a93047](https://linux-hardware.org/?probe=23c2a93047) | Feb 28, 2022 |
| Acer          | TravelMate P215-41-G2       | [5485738b5a](https://linux-hardware.org/?probe=5485738b5a) | Feb 28, 2022 |
| ASUSTek       | X401A                       | [e97f529634](https://linux-hardware.org/?probe=e97f529634) | Feb 28, 2022 |
| Acer          | Aspire A315-23G             | [21165232d6](https://linux-hardware.org/?probe=21165232d6) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Acer          | Aspire A515-56              | [bedf3d3105](https://linux-hardware.org/?probe=bedf3d3105) | Feb 26, 2022 |
| Acer          | Aspire E1-571               | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| ASUSTek       | N82JV                       | [30b9ccdcc9](https://linux-hardware.org/?probe=30b9ccdcc9) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [279a26d7e5](https://linux-hardware.org/?probe=279a26d7e5) | Feb 25, 2022 |
| HP            | Laptop 14s-fq0xxx           | [8e06c09393](https://linux-hardware.org/?probe=8e06c09393) | Feb 25, 2022 |
| Lenovo        | B50-80 80LT                 | [b5dd44876a](https://linux-hardware.org/?probe=b5dd44876a) | Feb 25, 2022 |
| Lenovo        | B50-80 80LT                 | [d4775df51b](https://linux-hardware.org/?probe=d4775df51b) | Feb 25, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [b3086480e5](https://linux-hardware.org/?probe=b3086480e5) | Feb 25, 2022 |
| Apple         | MacBook8,1                  | [b7b8d7f677](https://linux-hardware.org/?probe=b7b8d7f677) | Feb 24, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | [ec01c23749](https://linux-hardware.org/?probe=ec01c23749) | Feb 24, 2022 |
| ASUSTek       | BU203UA                     | [20764e8ede](https://linux-hardware.org/?probe=20764e8ede) | Feb 24, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Dell          | Latitude E4300              | [bfa3fa7218](https://linux-hardware.org/?probe=bfa3fa7218) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK E752               | [f82673bb20](https://linux-hardware.org/?probe=f82673bb20) | Feb 24, 2022 |
| HP            | Laptop 15-db1xxx            | [ad30c9f5ed](https://linux-hardware.org/?probe=ad30c9f5ed) | Feb 23, 2022 |
| Dell          | Inspiron 3721               | [da9c47ddfc](https://linux-hardware.org/?probe=da9c47ddfc) | Feb 22, 2022 |
| ASUSTek       | M70Vn                       | [ae56cd459a](https://linux-hardware.org/?probe=ae56cd459a) | Feb 22, 2022 |
| HP            | ZBook Studio G3             | [4d97cb439b](https://linux-hardware.org/?probe=4d97cb439b) | Feb 22, 2022 |
| Google        | Barla                       | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| HP            | EliteBook Revolve 810 G1    | [838f13e574](https://linux-hardware.org/?probe=838f13e574) | Feb 21, 2022 |
| ASUSTek       | X555LD                      | [6921a2b793](https://linux-hardware.org/?probe=6921a2b793) | Feb 21, 2022 |
| ASUSTek       | K52F                        | [51504b5b77](https://linux-hardware.org/?probe=51504b5b77) | Feb 21, 2022 |
| Timi          | RedmiBook 16                | [cca94f2eda](https://linux-hardware.org/?probe=cca94f2eda) | Feb 21, 2022 |
| Toshiba       | Satellite L775D             | [29f68fd73c](https://linux-hardware.org/?probe=29f68fd73c) | Feb 21, 2022 |
| ASUSTek       | X751LK                      | [59056d9df8](https://linux-hardware.org/?probe=59056d9df8) | Feb 20, 2022 |
| Unknown       | Unknown                     | [129c8a24d9](https://linux-hardware.org/?probe=129c8a24d9) | Feb 20, 2022 |
| Notebook      | W65_W670SR                  | [53c885fa6e](https://linux-hardware.org/?probe=53c885fa6e) | Feb 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [06b52bc271](https://linux-hardware.org/?probe=06b52bc271) | Feb 20, 2022 |
| Lenovo        | ThinkPad T410 2537A12       | [7326d20b88](https://linux-hardware.org/?probe=7326d20b88) | Feb 19, 2022 |
| ASUSTek       | X751LD                      | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| ASUSTek       | X756UXK                     | [b71ec18dba](https://linux-hardware.org/?probe=b71ec18dba) | Feb 19, 2022 |
| Lenovo        | ThinkPad X220 4291Q50       | [600a3137e2](https://linux-hardware.org/?probe=600a3137e2) | Feb 19, 2022 |
| HP            | Compaq CQ58                 | [fc3b92e02f](https://linux-hardware.org/?probe=fc3b92e02f) | Feb 19, 2022 |
| Dell          | XPS L521X                   | [1826f26221](https://linux-hardware.org/?probe=1826f26221) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ef345f036b](https://linux-hardware.org/?probe=ef345f036b) | Feb 19, 2022 |
| Acer          | Swift SF314-41              | [0c75e0962a](https://linux-hardware.org/?probe=0c75e0962a) | Feb 18, 2022 |
| HP            | Laptop 15-db0xxx            | [a59f3617da](https://linux-hardware.org/?probe=a59f3617da) | Feb 18, 2022 |
| Acer          | Aspire F5-771G              | [056c9c48f6](https://linux-hardware.org/?probe=056c9c48f6) | Feb 18, 2022 |
| HP            | Presario CQ61               | [92054824d8](https://linux-hardware.org/?probe=92054824d8) | Feb 18, 2022 |
| HP            | Presario CQ61               | [bb314dee54](https://linux-hardware.org/?probe=bb314dee54) | Feb 18, 2022 |
| VIT           | P3400                       | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| ASUSTek       | TP550LAB                    | [96c969a4b4](https://linux-hardware.org/?probe=96c969a4b4) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [eb1d4cf9d8](https://linux-hardware.org/?probe=eb1d4cf9d8) | Feb 17, 2022 |
| ASUSTek       | T200TAC                     | [ffd9891203](https://linux-hardware.org/?probe=ffd9891203) | Feb 17, 2022 |
| Acer          | Aspire E5-573G              | [e162c17653](https://linux-hardware.org/?probe=e162c17653) | Feb 17, 2022 |
| Lenovo        | ThinkPad X200 7459ZC2       | [897152c39c](https://linux-hardware.org/?probe=897152c39c) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [1fa5e259f5](https://linux-hardware.org/?probe=1fa5e259f5) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [92ccebcc90](https://linux-hardware.org/?probe=92ccebcc90) | Feb 16, 2022 |
| HP            | Laptop 15-da0xxx            | [84171dc3cd](https://linux-hardware.org/?probe=84171dc3cd) | Feb 16, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| HP            | Pavilion TS 15              | [6248023e72](https://linux-hardware.org/?probe=6248023e72) | Feb 15, 2022 |
| System76      | Gazelle Professional        | [bd2eeafecc](https://linux-hardware.org/?probe=bd2eeafecc) | Feb 15, 2022 |
| MSI           | GP72M 7RDX                  | [2a55fc3b23](https://linux-hardware.org/?probe=2a55fc3b23) | Feb 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a533f0d469](https://linux-hardware.org/?probe=a533f0d469) | Feb 14, 2022 |
| GPU Compan... | GWTC116-2                   | [84d678da21](https://linux-hardware.org/?probe=84d678da21) | Feb 14, 2022 |
| GPU Compan... | GWTC116-2                   | [9e7bbafd9c](https://linux-hardware.org/?probe=9e7bbafd9c) | Feb 13, 2022 |
| HP            | Pavilion g6                 | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-553G              | [0303c5a132](https://linux-hardware.org/?probe=0303c5a132) | Feb 13, 2022 |
| Packard Be... | EasyNote TE11HC             | [e7c108139b](https://linux-hardware.org/?probe=e7c108139b) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [068bd73cb9](https://linux-hardware.org/?probe=068bd73cb9) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [daa132c040](https://linux-hardware.org/?probe=daa132c040) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Dell          | Latitude 3410               | [5dfcbcab80](https://linux-hardware.org/?probe=5dfcbcab80) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| HP            | EliteBook 8570p             | [9db0010267](https://linux-hardware.org/?probe=9db0010267) | Feb 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [7ffdca7ea4](https://linux-hardware.org/?probe=7ffdca7ea4) | Feb 11, 2022 |
| Lenovo        | ThinkPad X230 2325V4D       | [a6d2aed78b](https://linux-hardware.org/?probe=a6d2aed78b) | Feb 11, 2022 |
| Lenovo        | ThinkPad X230 2325V4D       | [48f266c11e](https://linux-hardware.org/?probe=48f266c11e) | Feb 11, 2022 |
| HP            | Laptop 15-dw0xxx            | [16157beba6](https://linux-hardware.org/?probe=16157beba6) | Feb 11, 2022 |
| Acer          | Aspire F5-573G              | [de6408497a](https://linux-hardware.org/?probe=de6408497a) | Feb 10, 2022 |
| Lenovo        | ThinkPad L530 24813QG       | [c051e2ad9b](https://linux-hardware.org/?probe=c051e2ad9b) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | [7360a72c44](https://linux-hardware.org/?probe=7360a72c44) | Feb 09, 2022 |
| Dell          | XPS 13 9370                 | [d0bfe3fa56](https://linux-hardware.org/?probe=d0bfe3fa56) | Feb 09, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| eMachines     | eME728                      | [345b9ef3cd](https://linux-hardware.org/?probe=345b9ef3cd) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Dell          | XPS L421X                   | [f84aa1d978](https://linux-hardware.org/?probe=f84aa1d978) | Feb 09, 2022 |
| Dell          | XPS L421X                   | [e869731d45](https://linux-hardware.org/?probe=e869731d45) | Feb 09, 2022 |
| eMachines     | eME728                      | [c04471203f](https://linux-hardware.org/?probe=c04471203f) | Feb 08, 2022 |
| Lenovo        | G580 20157                  | [e159605a22](https://linux-hardware.org/?probe=e159605a22) | Feb 08, 2022 |
| HP            | Pavilion 17                 | [6343416eef](https://linux-hardware.org/?probe=6343416eef) | Feb 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3ce22a5559](https://linux-hardware.org/?probe=3ce22a5559) | Feb 07, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [c329b2c380](https://linux-hardware.org/?probe=c329b2c380) | Feb 07, 2022 |
| Lenovo        | G580 20157                  | [c0ddaf9205](https://linux-hardware.org/?probe=c0ddaf9205) | Feb 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [05e8132fd3](https://linux-hardware.org/?probe=05e8132fd3) | Feb 07, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [136f9d4c89](https://linux-hardware.org/?probe=136f9d4c89) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| Acer          | Aspire A315-23G             | [09e661535f](https://linux-hardware.org/?probe=09e661535f) | Feb 07, 2022 |
| HP            | 250 G3                      | [c54f59d942](https://linux-hardware.org/?probe=c54f59d942) | Feb 06, 2022 |
| Acer          | Aspire E5-553G              | [d6f8f41bc5](https://linux-hardware.org/?probe=d6f8f41bc5) | Feb 06, 2022 |
| Dell          | Latitude E6410              | [e8e62d3cde](https://linux-hardware.org/?probe=e8e62d3cde) | Feb 06, 2022 |
| Dell          | Inspiron 15 5510            | [3dbd4103ce](https://linux-hardware.org/?probe=3dbd4103ce) | Feb 06, 2022 |
| Lenovo        | B590 20206                  | [6d6a3d2ac4](https://linux-hardware.org/?probe=6d6a3d2ac4) | Feb 06, 2022 |
| Dell          | Latitude D630               | [b2d5d4aa5a](https://linux-hardware.org/?probe=b2d5d4aa5a) | Feb 05, 2022 |
| Dell          | Latitude E6330              | [41ba1619f5](https://linux-hardware.org/?probe=41ba1619f5) | Feb 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a11c55e55](https://linux-hardware.org/?probe=5a11c55e55) | Feb 05, 2022 |
| HP            | EliteBook 840 G2            | [711d2a668d](https://linux-hardware.org/?probe=711d2a668d) | Feb 05, 2022 |
| Toshiba       | Satellite E45DW-C           | [e106d541e5](https://linux-hardware.org/?probe=e106d541e5) | Feb 05, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [5520691017](https://linux-hardware.org/?probe=5520691017) | Feb 05, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [09f190d4b4](https://linux-hardware.org/?probe=09f190d4b4) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | [37c0fc9564](https://linux-hardware.org/?probe=37c0fc9564) | Feb 04, 2022 |
| Acer          | Nitro AN515-44              | [417bb2f526](https://linux-hardware.org/?probe=417bb2f526) | Feb 04, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [abe18af5e7](https://linux-hardware.org/?probe=abe18af5e7) | Feb 04, 2022 |
| Acer          | Aspire A315-23G             | [ebc65d68d9](https://linux-hardware.org/?probe=ebc65d68d9) | Feb 03, 2022 |
| Chuwi         | GemiBook                    | [8a892ea268](https://linux-hardware.org/?probe=8a892ea268) | Feb 03, 2022 |
| Acer          | Aspire E5-553G              | [a7b8841235](https://linux-hardware.org/?probe=a7b8841235) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | [f8f690a2b4](https://linux-hardware.org/?probe=f8f690a2b4) | Feb 02, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7808ed67c3](https://linux-hardware.org/?probe=7808ed67c3) | Feb 02, 2022 |
| Acer          | Aspire E5-553G              | [9d8d2dafa1](https://linux-hardware.org/?probe=9d8d2dafa1) | Feb 02, 2022 |
| Lenovo        | ThinkPad R61e 7649AL6       | [e7595e9b45](https://linux-hardware.org/?probe=e7595e9b45) | Feb 02, 2022 |
| Samsung       | RC530/RC730                 | [d541cf4375](https://linux-hardware.org/?probe=d541cf4375) | Feb 01, 2022 |
| Lenovo        | V14-ARE 82DQ                | [b3cfaa23eb](https://linux-hardware.org/?probe=b3cfaa23eb) | Feb 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| Dell          | XPS 15 9560                 | [2a3b959f49](https://linux-hardware.org/?probe=2a3b959f49) | Feb 01, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [512c8c256a](https://linux-hardware.org/?probe=512c8c256a) | Jan 31, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [98dc82b4af](https://linux-hardware.org/?probe=98dc82b4af) | Jan 31, 2022 |
| Acer          | Aspire ES1-411              | [8d478b1936](https://linux-hardware.org/?probe=8d478b1936) | Jan 31, 2022 |
| ASUSTek       | ZenBook 13 UX331UAL         | [1202dc6569](https://linux-hardware.org/?probe=1202dc6569) | Jan 31, 2022 |
| Acer          | Aspire A315-23G             | [d60beb8456](https://linux-hardware.org/?probe=d60beb8456) | Jan 31, 2022 |
| MSI           | GE70 2OC\2OD\2OE            | [f9efba7bbf](https://linux-hardware.org/?probe=f9efba7bbf) | Jan 30, 2022 |
| HP            | Laptop 15-db0xxx            | [aa29a61907](https://linux-hardware.org/?probe=aa29a61907) | Jan 30, 2022 |
| Toshiba       | Satellite L775D             | [6f8044dd04](https://linux-hardware.org/?probe=6f8044dd04) | Jan 30, 2022 |
| Toshiba       | Satellite L775D             | [b7b77abd4a](https://linux-hardware.org/?probe=b7b77abd4a) | Jan 30, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | [9c94c598d3](https://linux-hardware.org/?probe=9c94c598d3) | Jan 30, 2022 |
| Toshiba       | TECRA R950                  | [53fc5e9542](https://linux-hardware.org/?probe=53fc5e9542) | Jan 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [6158642c8d](https://linux-hardware.org/?probe=6158642c8d) | Jan 29, 2022 |
| Lenovo        | ThinkPad T430 2349GCG       | [79073707f7](https://linux-hardware.org/?probe=79073707f7) | Jan 29, 2022 |
| Packard Be... | EasyNote LM98               | [92ea2431b4](https://linux-hardware.org/?probe=92ea2431b4) | Jan 29, 2022 |
| Apple         | MacBookPro11,1              | [c6bbc9eee8](https://linux-hardware.org/?probe=c6bbc9eee8) | Jan 29, 2022 |
| HP            | Laptop 15-db0xxx            | [5dbc003da9](https://linux-hardware.org/?probe=5dbc003da9) | Jan 28, 2022 |
| HP            | Laptop 15-db0xxx            | [64400dd3d5](https://linux-hardware.org/?probe=64400dd3d5) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5e934e6551](https://linux-hardware.org/?probe=5e934e6551) | Jan 28, 2022 |
| Acer          | Aspire A315-23G             | [f741575389](https://linux-hardware.org/?probe=f741575389) | Jan 27, 2022 |
| Toshiba       | Satellite P850              | [9fed64bb7e](https://linux-hardware.org/?probe=9fed64bb7e) | Jan 27, 2022 |
| Dell          | Inspiron 3505               | [343ab23f97](https://linux-hardware.org/?probe=343ab23f97) | Jan 27, 2022 |
| Positivo      | Harrison                    | [320f20f33d](https://linux-hardware.org/?probe=320f20f33d) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [dc0ea304b7](https://linux-hardware.org/?probe=dc0ea304b7) | Jan 26, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [2d908d8204](https://linux-hardware.org/?probe=2d908d8204) | Jan 26, 2022 |
| Acer          | Swift SF314-43              | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f7c5fb7450](https://linux-hardware.org/?probe=f7c5fb7450) | Jan 26, 2022 |
| Sony          | SVE15127CDS                 | [b3908594f0](https://linux-hardware.org/?probe=b3908594f0) | Jan 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [04c45929e9](https://linux-hardware.org/?probe=04c45929e9) | Jan 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f38245d80d](https://linux-hardware.org/?probe=f38245d80d) | Jan 25, 2022 |
| Acer          | Aspire A515-56              | [718b441098](https://linux-hardware.org/?probe=718b441098) | Jan 25, 2022 |
| HP            | ProBook 650 G5              | [fe61272ae2](https://linux-hardware.org/?probe=fe61272ae2) | Jan 25, 2022 |
| Lenovo        | B475 Sabine                 | [2093f6f299](https://linux-hardware.org/?probe=2093f6f299) | Jan 25, 2022 |
| Unknown       | T3 MRD                      | [2a812850f1](https://linux-hardware.org/?probe=2a812850f1) | Jan 25, 2022 |
| Acer          | Aspire 1640                 | [f46c03801f](https://linux-hardware.org/?probe=f46c03801f) | Jan 24, 2022 |
| Acer          | Aspire A515-56              | [bda0e1f7eb](https://linux-hardware.org/?probe=bda0e1f7eb) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | [1364acf470](https://linux-hardware.org/?probe=1364acf470) | Jan 24, 2022 |
| HP            | Laptop 14s-dq0xxx           | [095fa0909e](https://linux-hardware.org/?probe=095fa0909e) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | [032ee6d6c0](https://linux-hardware.org/?probe=032ee6d6c0) | Jan 24, 2022 |
| Dell          | Inspiron 3583               | [9ea2007217](https://linux-hardware.org/?probe=9ea2007217) | Jan 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | [b552b967e4](https://linux-hardware.org/?probe=b552b967e4) | Jan 24, 2022 |
| HP            | 250 G7 Notebook PC          | [9f5905c095](https://linux-hardware.org/?probe=9f5905c095) | Jan 24, 2022 |
| HP            | 250 G6 Notebook PC          | [dae0e58890](https://linux-hardware.org/?probe=dae0e58890) | Jan 23, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| HP            | 250 G7 Notebook PC          | [739904e65c](https://linux-hardware.org/?probe=739904e65c) | Jan 23, 2022 |
| Dell          | XPS 15 7590                 | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| Dell          | Latitude 5310               | [424fadc888](https://linux-hardware.org/?probe=424fadc888) | Jan 23, 2022 |
| Dell          | Inspiron 5559               | [5832d766ab](https://linux-hardware.org/?probe=5832d766ab) | Jan 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [586c28a98a](https://linux-hardware.org/?probe=586c28a98a) | Jan 23, 2022 |
| Acer          | Aspire A315-23G             | [310b719b15](https://linux-hardware.org/?probe=310b719b15) | Jan 23, 2022 |
| Dell          | Inspiron 5580               | [515465fd5a](https://linux-hardware.org/?probe=515465fd5a) | Jan 22, 2022 |
| Dell          | Inspiron 6000               | [9bbb0b47c9](https://linux-hardware.org/?probe=9bbb0b47c9) | Jan 22, 2022 |
| Unknown       | Unknown                     | [05e17dc297](https://linux-hardware.org/?probe=05e17dc297) | Jan 21, 2022 |
| Acer          | Aspire A315-23G             | [164b959848](https://linux-hardware.org/?probe=164b959848) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [f9deb1d329](https://linux-hardware.org/?probe=f9deb1d329) | Jan 20, 2022 |
| Lenovo        | B475 Sabine                 | [4f40d723c5](https://linux-hardware.org/?probe=4f40d723c5) | Jan 20, 2022 |
| HP            | Pavilion g7                 | [f789fa0e4b](https://linux-hardware.org/?probe=f789fa0e4b) | Jan 20, 2022 |
| Dell          | Latitude E6410              | [2e43a65524](https://linux-hardware.org/?probe=2e43a65524) | Jan 20, 2022 |
| Acer          | Aspire A315-23G             | [c1b18abd63](https://linux-hardware.org/?probe=c1b18abd63) | Jan 20, 2022 |
| HP            | Pavilion g7                 | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| Alienware     | 17 R3                       | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| Dell          | Latitude E6330              | [2c94023cca](https://linux-hardware.org/?probe=2c94023cca) | Jan 19, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a311bab4a](https://linux-hardware.org/?probe=6a311bab4a) | Jan 19, 2022 |
| Dell          | Precision 3561              | [05b06d8c48](https://linux-hardware.org/?probe=05b06d8c48) | Jan 19, 2022 |
| HP            | Pavilion g6                 | [2acc56ff71](https://linux-hardware.org/?probe=2acc56ff71) | Jan 19, 2022 |
| Dell          | Precision 5560              | [4404c43852](https://linux-hardware.org/?probe=4404c43852) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | [c4465062c7](https://linux-hardware.org/?probe=c4465062c7) | Jan 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [efdc064669](https://linux-hardware.org/?probe=efdc064669) | Jan 19, 2022 |
| Sony          | VPCF12C5E                   | [7c8ee2ed3b](https://linux-hardware.org/?probe=7c8ee2ed3b) | Jan 19, 2022 |
| Samsung       | N150P/N210P/N220P           | [53b6312ff6](https://linux-hardware.org/?probe=53b6312ff6) | Jan 18, 2022 |
| Lenovo        | B475 Sabine                 | [68b04eef9d](https://linux-hardware.org/?probe=68b04eef9d) | Jan 18, 2022 |
| Apple         | MacBookAir7,1               | [1d5ac9894a](https://linux-hardware.org/?probe=1d5ac9894a) | Jan 18, 2022 |
| Lenovo        | G580                        | [b575a14a10](https://linux-hardware.org/?probe=b575a14a10) | Jan 18, 2022 |
| HP            | EliteBook 8440p             | [eea8c3a5c3](https://linux-hardware.org/?probe=eea8c3a5c3) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| HP            | Notebook                    | [782c51f796](https://linux-hardware.org/?probe=782c51f796) | Jan 17, 2022 |
| Dell          | Latitude 5420               | [dd45d8465d](https://linux-hardware.org/?probe=dd45d8465d) | Jan 17, 2022 |
| HP            | EliteBook 8440p             | [a3133c9aab](https://linux-hardware.org/?probe=a3133c9aab) | Jan 17, 2022 |
| Lenovo        | G580                        | [554ee0ef82](https://linux-hardware.org/?probe=554ee0ef82) | Jan 17, 2022 |
| IBM           | 2647QU6                     | [41283220a2](https://linux-hardware.org/?probe=41283220a2) | Jan 17, 2022 |
| Dell          | Latitude E5570              | [5c4c02c6f4](https://linux-hardware.org/?probe=5c4c02c6f4) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Toshiba       | Satellite L50-B             | [c0f3709a57](https://linux-hardware.org/?probe=c0f3709a57) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [dae8d10589](https://linux-hardware.org/?probe=dae8d10589) | Jan 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [fb799bb9f5](https://linux-hardware.org/?probe=fb799bb9f5) | Jan 15, 2022 |
| ASUSTek       | X550VX                      | [96b0a9dbdc](https://linux-hardware.org/?probe=96b0a9dbdc) | Jan 14, 2022 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [5c41a54599](https://linux-hardware.org/?probe=5c41a54599) | Jan 14, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [9f0d682171](https://linux-hardware.org/?probe=9f0d682171) | Jan 14, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [53c16c3d57](https://linux-hardware.org/?probe=53c16c3d57) | Jan 14, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [eb4e0295d3](https://linux-hardware.org/?probe=eb4e0295d3) | Jan 14, 2022 |
| MSI           | MS-1454                     | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| Acer          | Aspire V3-772               | [79e884f81e](https://linux-hardware.org/?probe=79e884f81e) | Jan 14, 2022 |
| Lex BayTra... | 3I380A                      | [7f59432801](https://linux-hardware.org/?probe=7f59432801) | Jan 14, 2022 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [9d63aff476](https://linux-hardware.org/?probe=9d63aff476) | Jan 14, 2022 |
| HP            | Mini 110-1100               | [10271759b0](https://linux-hardware.org/?probe=10271759b0) | Jan 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3050abff3a](https://linux-hardware.org/?probe=3050abff3a) | Jan 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [a68454eff9](https://linux-hardware.org/?probe=a68454eff9) | Jan 13, 2022 |
| Acer          | AOD255E                     | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| Samsung       | 535U3C                      | [c18e5d660d](https://linux-hardware.org/?probe=c18e5d660d) | Jan 12, 2022 |
| Dell          | Inspiron 3593               | [9c5f9bb3c6](https://linux-hardware.org/?probe=9c5f9bb3c6) | Jan 12, 2022 |
| Apple         | MacBookPro5,5               | [46d42db225](https://linux-hardware.org/?probe=46d42db225) | Jan 12, 2022 |
| Apple         | MacBookPro5,5               | [5c58aa5b86](https://linux-hardware.org/?probe=5c58aa5b86) | Jan 12, 2022 |
| Compal        | NCL60/61                    | [3f71d0d088](https://linux-hardware.org/?probe=3f71d0d088) | Jan 12, 2022 |
| Lenovo        | G50-70 20351                | [fb5417c823](https://linux-hardware.org/?probe=fb5417c823) | Jan 12, 2022 |
| Lenovo        | G50-70 20351                | [d0e05a158d](https://linux-hardware.org/?probe=d0e05a158d) | Jan 11, 2022 |
| ASUSTek       | X510UAR                     | [fa5b04fccd](https://linux-hardware.org/?probe=fa5b04fccd) | Jan 11, 2022 |
| Dell          | Inspiron 13 5310            | [f45f45197a](https://linux-hardware.org/?probe=f45f45197a) | Jan 11, 2022 |
| Aquarius      | NS585                       | [05fa3aee01](https://linux-hardware.org/?probe=05fa3aee01) | Jan 11, 2022 |
| Aquarius      | NS585                       | [00bdbd3175](https://linux-hardware.org/?probe=00bdbd3175) | Jan 11, 2022 |
| Aquarius      | NS585                       | [ff9e56cc49](https://linux-hardware.org/?probe=ff9e56cc49) | Jan 11, 2022 |
| Aquarius      | NS585                       | [fc09ae03e2](https://linux-hardware.org/?probe=fc09ae03e2) | Jan 11, 2022 |
| Aquarius      | NS585                       | [4225f64fae](https://linux-hardware.org/?probe=4225f64fae) | Jan 11, 2022 |
| Toshiba       | Satellite C660D             | [99758d2a73](https://linux-hardware.org/?probe=99758d2a73) | Jan 11, 2022 |
| Aquarius      | NS585                       | [e892be3b29](https://linux-hardware.org/?probe=e892be3b29) | Jan 11, 2022 |
| Dell          | Inspiron 13 5310            | [fd57c1981b](https://linux-hardware.org/?probe=fd57c1981b) | Jan 11, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [f21bede8f0](https://linux-hardware.org/?probe=f21bede8f0) | Jan 11, 2022 |
| MOTION        | KEX00                       | [8ff3554d7d](https://linux-hardware.org/?probe=8ff3554d7d) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [e9f4084086](https://linux-hardware.org/?probe=e9f4084086) | Jan 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a046d0cd96](https://linux-hardware.org/?probe=a046d0cd96) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| Lenovo        | B490 37722LP                | [c36fa4c158](https://linux-hardware.org/?probe=c36fa4c158) | Jan 10, 2022 |
| HP            | Presario CQ56               | [17e7a9c9d1](https://linux-hardware.org/?probe=17e7a9c9d1) | Jan 09, 2022 |
| Sony          | VPCS13V9E                   | [609e1c504a](https://linux-hardware.org/?probe=609e1c504a) | Jan 09, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [4df70f0938](https://linux-hardware.org/?probe=4df70f0938) | Jan 09, 2022 |
| Acer          | Aspire 5755G                | [2bb43fbbb1](https://linux-hardware.org/?probe=2bb43fbbb1) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | [5de9fddbf7](https://linux-hardware.org/?probe=5de9fddbf7) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | [29f18e6869](https://linux-hardware.org/?probe=29f18e6869) | Jan 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [99a245965c](https://linux-hardware.org/?probe=99a245965c) | Jan 09, 2022 |
| Dell          | Latitude E5420              | [28c33b9e71](https://linux-hardware.org/?probe=28c33b9e71) | Jan 09, 2022 |
| Lenovo        | V130-15IGM 81HL             | [c6da06ae31](https://linux-hardware.org/?probe=c6da06ae31) | Jan 09, 2022 |
| Sony          | SVS13A1C5E                  | [891a2d4782](https://linux-hardware.org/?probe=891a2d4782) | Jan 09, 2022 |
| Dell          | Latitude E6330              | [da29c6f100](https://linux-hardware.org/?probe=da29c6f100) | Jan 08, 2022 |
| Acer          | Aspire 5755G                | [e96ad6257b](https://linux-hardware.org/?probe=e96ad6257b) | Jan 08, 2022 |
| Sony          | VPCEB3S1E                   | [6f78e2d423](https://linux-hardware.org/?probe=6f78e2d423) | Jan 07, 2022 |
| Acer          | Aspire 7720G                | [61e120f622](https://linux-hardware.org/?probe=61e120f622) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ee6b48f115](https://linux-hardware.org/?probe=ee6b48f115) | Jan 07, 2022 |
| Dell          | Latitude E5420              | [89617aa917](https://linux-hardware.org/?probe=89617aa917) | Jan 07, 2022 |
| ASUSTek       | K53U                        | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| Notebook      | W65_67SZ                    | [a38592dcaf](https://linux-hardware.org/?probe=a38592dcaf) | Jan 06, 2022 |
| Acer          | Aspire A315-23G             | [d22f32f071](https://linux-hardware.org/?probe=d22f32f071) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| Dell          | Inspiron 3793               | [78ea49cf6a](https://linux-hardware.org/?probe=78ea49cf6a) | Jan 05, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [f691531281](https://linux-hardware.org/?probe=f691531281) | Jan 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| ASUSTek       | X751LK                      | [c155fbdd7b](https://linux-hardware.org/?probe=c155fbdd7b) | Jan 04, 2022 |
| Medion        | P6620                       | [dbf6822c89](https://linux-hardware.org/?probe=dbf6822c89) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d7ed8aaee8](https://linux-hardware.org/?probe=d7ed8aaee8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [2d698abe0e](https://linux-hardware.org/?probe=2d698abe0e) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [1cdd36f612](https://linux-hardware.org/?probe=1cdd36f612) | Jan 04, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [36f0adee44](https://linux-hardware.org/?probe=36f0adee44) | Jan 04, 2022 |
| Dell          | Inspiron 5570               | [3e6d1befd6](https://linux-hardware.org/?probe=3e6d1befd6) | Jan 03, 2022 |
| Compal        | QAL51                       | [28d555a161](https://linux-hardware.org/?probe=28d555a161) | Jan 03, 2022 |
| Dell          | Vostro 3500                 | [da4d6def3d](https://linux-hardware.org/?probe=da4d6def3d) | Jan 03, 2022 |
| HUAWEI        | HKD-WXX                     | [19b1fdc5cd](https://linux-hardware.org/?probe=19b1fdc5cd) | Jan 02, 2022 |
| Lenovo        | ThinkPad W530 24382HU       | [5a4cc794e4](https://linux-hardware.org/?probe=5a4cc794e4) | Jan 02, 2022 |
| HP            | 15 TS                       | [f65f0315ec](https://linux-hardware.org/?probe=f65f0315ec) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [86824eb8ff](https://linux-hardware.org/?probe=86824eb8ff) | Jan 02, 2022 |
| Jumper        | EZbook                      | [2a9ea409b3](https://linux-hardware.org/?probe=2a9ea409b3) | Jan 01, 2022 |
| Medion        | Akoya P7818                 | [3fcc005174](https://linux-hardware.org/?probe=3fcc005174) | Jan 01, 2022 |
| Samsung       | 750XDA                      | [2b99263c43](https://linux-hardware.org/?probe=2b99263c43) | Jan 01, 2022 |
| HP            | ProBook 650 G5              | [10c33cbcd2](https://linux-hardware.org/?probe=10c33cbcd2) | Jan 01, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [eede59cbf0](https://linux-hardware.org/?probe=eede59cbf0) | Jan 01, 2022 |
| ASUSTek       | X756UXK                     | [3f565d70fe](https://linux-hardware.org/?probe=3f565d70fe) | Jan 01, 2022 |
| ASUSTek       | X555LD                      | [1fbd5a6a63](https://linux-hardware.org/?probe=1fbd5a6a63) | Jan 01, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| HP            | Presario CQ56               | [aacf56218d](https://linux-hardware.org/?probe=aacf56218d) | Dec 31, 2021 |
| HP            | ProBook 650 G5              | [668c6a4644](https://linux-hardware.org/?probe=668c6a4644) | Dec 31, 2021 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [4302dae812](https://linux-hardware.org/?probe=4302dae812) | Dec 31, 2021 |
| Dell          | Inspiron 7520               | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [dc28d41913](https://linux-hardware.org/?probe=dc28d41913) | Dec 30, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8a1a113e52](https://linux-hardware.org/?probe=8a1a113e52) | Dec 30, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [a38b433d5e](https://linux-hardware.org/?probe=a38b433d5e) | Dec 30, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [9d363caf9e](https://linux-hardware.org/?probe=9d363caf9e) | Dec 29, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [a7f26d9823](https://linux-hardware.org/?probe=a7f26d9823) | Dec 29, 2021 |
| Lenovo        | ThinkPad A485 20MU000CMH    | [ec36ac81a4](https://linux-hardware.org/?probe=ec36ac81a4) | Dec 29, 2021 |
| ASUSTek       | UX303LAB                    | [196ff1f41f](https://linux-hardware.org/?probe=196ff1f41f) | Dec 29, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [51d4addbb3](https://linux-hardware.org/?probe=51d4addbb3) | Dec 29, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [b44ab55a4d](https://linux-hardware.org/?probe=b44ab55a4d) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [9679415e5e](https://linux-hardware.org/?probe=9679415e5e) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10ec2e2912](https://linux-hardware.org/?probe=10ec2e2912) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [47497df950](https://linux-hardware.org/?probe=47497df950) | Dec 28, 2021 |
| Lenovo        | B50-30 20382                | [896ea31fe5](https://linux-hardware.org/?probe=896ea31fe5) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [98bccb86b2](https://linux-hardware.org/?probe=98bccb86b2) | Dec 28, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [f0d7556c6b](https://linux-hardware.org/?probe=f0d7556c6b) | Dec 28, 2021 |
| ASUSTek       | A7V                         | [33b743a9bc](https://linux-hardware.org/?probe=33b743a9bc) | Dec 28, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [34bc7aa429](https://linux-hardware.org/?probe=34bc7aa429) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8fdd3d78c9](https://linux-hardware.org/?probe=8fdd3d78c9) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [a2eed27aed](https://linux-hardware.org/?probe=a2eed27aed) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [f022aa3706](https://linux-hardware.org/?probe=f022aa3706) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [252503762f](https://linux-hardware.org/?probe=252503762f) | Dec 27, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [5be0d36fa8](https://linux-hardware.org/?probe=5be0d36fa8) | Dec 27, 2021 |
| Acer          | Aspire A315-23G             | [8262ba8f4a](https://linux-hardware.org/?probe=8262ba8f4a) | Dec 27, 2021 |
| Acer          | Aspire E5-511               | [86bd37c584](https://linux-hardware.org/?probe=86bd37c584) | Dec 27, 2021 |
| Acer          | Aspire A515-56              | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad T450 20BUS09X01    | [acce80e775](https://linux-hardware.org/?probe=acce80e775) | Dec 26, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | [e3a3030886](https://linux-hardware.org/?probe=e3a3030886) | Dec 26, 2021 |
| Lenovo        | IdeaPad S540-13API 81XC     | [c7612aac66](https://linux-hardware.org/?probe=c7612aac66) | Dec 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [2c33c2931e](https://linux-hardware.org/?probe=2c33c2931e) | Dec 26, 2021 |
| Toshiba       | Satellite L775D             | [1ad6310748](https://linux-hardware.org/?probe=1ad6310748) | Dec 26, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | [73d605f4e5](https://linux-hardware.org/?probe=73d605f4e5) | Dec 26, 2021 |
| Dell          | Vostro 3560                 | [7bd51b12d6](https://linux-hardware.org/?probe=7bd51b12d6) | Dec 25, 2021 |
| Dell          | Vostro 3560                 | [0929a4f988](https://linux-hardware.org/?probe=0929a4f988) | Dec 25, 2021 |
| HUAWEI        | HKD-WXX                     | [9e77c08b95](https://linux-hardware.org/?probe=9e77c08b95) | Dec 24, 2021 |
| ASUSTek       | X542UA                      | [c103fc5e33](https://linux-hardware.org/?probe=c103fc5e33) | Dec 24, 2021 |
| Acer          | Aspire 5733Z                | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Toshiba       | Satellite E205              | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Framework     | Laptop                      | [eac24b722b](https://linux-hardware.org/?probe=eac24b722b) | Dec 22, 2021 |
| HP            | G61                         | [d3f48fd2b2](https://linux-hardware.org/?probe=d3f48fd2b2) | Dec 22, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [302a05ab29](https://linux-hardware.org/?probe=302a05ab29) | Dec 22, 2021 |
| Advent        | Tacto Purple                | [ac9fd78933](https://linux-hardware.org/?probe=ac9fd78933) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [0a0df8aeb4](https://linux-hardware.org/?probe=0a0df8aeb4) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [d57782238c](https://linux-hardware.org/?probe=d57782238c) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [00603cca0e](https://linux-hardware.org/?probe=00603cca0e) | Dec 22, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [6f933f3515](https://linux-hardware.org/?probe=6f933f3515) | Dec 21, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [0f65d7798c](https://linux-hardware.org/?probe=0f65d7798c) | Dec 21, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [d2e57452db](https://linux-hardware.org/?probe=d2e57452db) | Dec 21, 2021 |
| Google        | Barla                       | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Lenovo        | V130-15IGM 81HL             | [541618076f](https://linux-hardware.org/?probe=541618076f) | Dec 21, 2021 |
| Google        | Barla                       | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | Laptop 15-db0xxx            | [450425f52d](https://linux-hardware.org/?probe=450425f52d) | Dec 20, 2021 |
| HP            | Laptop 15-db0xxx            | [95261c40a2](https://linux-hardware.org/?probe=95261c40a2) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [18fbcba790](https://linux-hardware.org/?probe=18fbcba790) | Dec 20, 2021 |
| Acer          | Aspire A515-56              | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [619d113667](https://linux-hardware.org/?probe=619d113667) | Dec 20, 2021 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [8032915451](https://linux-hardware.org/?probe=8032915451) | Dec 20, 2021 |
| ASUSTek       | 1015CX                      | [e146dc65ee](https://linux-hardware.org/?probe=e146dc65ee) | Dec 19, 2021 |
| Toshiba       | Satellite L755D             | [1f2f21825c](https://linux-hardware.org/?probe=1f2f21825c) | Dec 19, 2021 |
| Dell          | Inspiron N4050              | [069b0b5d94](https://linux-hardware.org/?probe=069b0b5d94) | Dec 19, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| Lenovo        | ThinkPad T450 20BV000EUS    | [cb3d066fe3](https://linux-hardware.org/?probe=cb3d066fe3) | Dec 17, 2021 |
| HP            | Laptop 15-db0xxx            | [52f6aa4a91](https://linux-hardware.org/?probe=52f6aa4a91) | Dec 17, 2021 |
| HP            | ZBook 15u G6                | [78134b6880](https://linux-hardware.org/?probe=78134b6880) | Dec 17, 2021 |
| HP            | ZBook 15u G6                | [5a2146eb12](https://linux-hardware.org/?probe=5a2146eb12) | Dec 17, 2021 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [7328745d31](https://linux-hardware.org/?probe=7328745d31) | Dec 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a77249c08b](https://linux-hardware.org/?probe=a77249c08b) | Dec 16, 2021 |
| Maibenben     | E5100                       | [862244e859](https://linux-hardware.org/?probe=862244e859) | Dec 16, 2021 |
| Maibenben     | E5100                       | [cb5e47da58](https://linux-hardware.org/?probe=cb5e47da58) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [7d95335599](https://linux-hardware.org/?probe=7d95335599) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [81c5e26bcf](https://linux-hardware.org/?probe=81c5e26bcf) | Dec 16, 2021 |
| Toshiba       | Satellite L775D             | [6f85a331cc](https://linux-hardware.org/?probe=6f85a331cc) | Dec 15, 2021 |
| HP            | Notebook                    | [28a73cd53a](https://linux-hardware.org/?probe=28a73cd53a) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| HONOR         | HLYL-WXX9                   | [0b6a9394b4](https://linux-hardware.org/?probe=0b6a9394b4) | Dec 15, 2021 |
| CSL-Comput... | R Evolve C14i               | [63c7f1d48e](https://linux-hardware.org/?probe=63c7f1d48e) | Dec 14, 2021 |
| HP            | EliteBook 8560p             | [6a1aefdd40](https://linux-hardware.org/?probe=6a1aefdd40) | Dec 14, 2021 |
| ASUSTek       | X756UQ                      | [04d25be08d](https://linux-hardware.org/?probe=04d25be08d) | Dec 13, 2021 |
| ASUSTek       | X756UQ                      | [21aac3ed33](https://linux-hardware.org/?probe=21aac3ed33) | Dec 13, 2021 |
| HP            | ProBook 440 G6              | [bf19b30902](https://linux-hardware.org/?probe=bf19b30902) | Dec 13, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | [73ba7a03d3](https://linux-hardware.org/?probe=73ba7a03d3) | Dec 13, 2021 |
| ASUSTek       | X542UA                      | [920ca90cbe](https://linux-hardware.org/?probe=920ca90cbe) | Dec 13, 2021 |
| Dell          | Precision M6500             | [5b825d4133](https://linux-hardware.org/?probe=5b825d4133) | Dec 11, 2021 |
| Lenovo        | Z51-70 80K6                 | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| Dell          | XPS 17 9700                 | [d5ec843ea7](https://linux-hardware.org/?probe=d5ec843ea7) | Dec 11, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [f2bfaaf185](https://linux-hardware.org/?probe=f2bfaaf185) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | [8c952bfc3d](https://linux-hardware.org/?probe=8c952bfc3d) | Dec 11, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | [7d2780ae1a](https://linux-hardware.org/?probe=7d2780ae1a) | Dec 11, 2021 |
| HP            | EliteBook 2540p (VB841AV... | [c0406366e7](https://linux-hardware.org/?probe=c0406366e7) | Dec 10, 2021 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [e4f3353735](https://linux-hardware.org/?probe=e4f3353735) | Dec 10, 2021 |
| ASUSTek       | X542UA                      | [e463e37acd](https://linux-hardware.org/?probe=e463e37acd) | Dec 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [f53267338f](https://linux-hardware.org/?probe=f53267338f) | Dec 10, 2021 |
| Packard Be... | EasyNote TM85               | [6a064fb13c](https://linux-hardware.org/?probe=6a064fb13c) | Dec 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | [3b7e64aebf](https://linux-hardware.org/?probe=3b7e64aebf) | Dec 10, 2021 |
| Dell          | Precision M6500             | [eff4bd68bc](https://linux-hardware.org/?probe=eff4bd68bc) | Dec 10, 2021 |
| IBM           | ThinkPad T43 2668BU7        | [30bc16722a](https://linux-hardware.org/?probe=30bc16722a) | Dec 10, 2021 |
| Lenovo        | G585 2181                   | [392cee4b42](https://linux-hardware.org/?probe=392cee4b42) | Dec 09, 2021 |
| Dell          | Latitude 5500               | [d293fa8753](https://linux-hardware.org/?probe=d293fa8753) | Dec 09, 2021 |
| Dell          | Latitude 5500               | [a2b09ae92d](https://linux-hardware.org/?probe=a2b09ae92d) | Dec 09, 2021 |
| Lenovo        | ThinkPad W520 4284D47       | [a48239fba8](https://linux-hardware.org/?probe=a48239fba8) | Dec 08, 2021 |
| HP            | EliteBook 840 G2            | [fbc33ca9af](https://linux-hardware.org/?probe=fbc33ca9af) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| Apple         | MacBookAir7,1               | [0a1d0c4e9b](https://linux-hardware.org/?probe=0a1d0c4e9b) | Dec 07, 2021 |
| Google        | Enguarde                    | [75bc922bae](https://linux-hardware.org/?probe=75bc922bae) | Dec 07, 2021 |
| Lenovo        | G585 2181                   | [9f1eb2ede7](https://linux-hardware.org/?probe=9f1eb2ede7) | Dec 07, 2021 |
| Dell          | Latitude 7490               | [187ce36374](https://linux-hardware.org/?probe=187ce36374) | Dec 07, 2021 |
| Lenovo        | G585 2181                   | [c03b3fab75](https://linux-hardware.org/?probe=c03b3fab75) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4173a9406a](https://linux-hardware.org/?probe=4173a9406a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [45c6fce683](https://linux-hardware.org/?probe=45c6fce683) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [b630c2b983](https://linux-hardware.org/?probe=b630c2b983) | Dec 07, 2021 |
| HP            | Laptop 15                   | [da76eec83a](https://linux-hardware.org/?probe=da76eec83a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [0a6e6fb2e6](https://linux-hardware.org/?probe=0a6e6fb2e6) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [f2a731f5bc](https://linux-hardware.org/?probe=f2a731f5bc) | Dec 07, 2021 |
| HP            | Laptop 15-db0xxx            | [c2e3c75ed0](https://linux-hardware.org/?probe=c2e3c75ed0) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [438e75161a](https://linux-hardware.org/?probe=438e75161a) | Dec 07, 2021 |
| HP            | Laptop 15-db1xxx            | [8e20af97d9](https://linux-hardware.org/?probe=8e20af97d9) | Dec 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| HP            | Laptop 15-db0xxx            | [2df4a34321](https://linux-hardware.org/?probe=2df4a34321) | Dec 07, 2021 |
| Acer          | Aspire 5741G                | [885dd449b6](https://linux-hardware.org/?probe=885dd449b6) | Dec 07, 2021 |
| Google        | Enguarde                    | [310a80f4c5](https://linux-hardware.org/?probe=310a80f4c5) | Dec 06, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [caaaef312c](https://linux-hardware.org/?probe=caaaef312c) | Dec 06, 2021 |
| HUAWEI        | BOHB-WAX9                   | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| Apple         | MacBookAir7,1               | [ee3ed8982f](https://linux-hardware.org/?probe=ee3ed8982f) | Dec 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [be3e1f65e6](https://linux-hardware.org/?probe=be3e1f65e6) | Dec 06, 2021 |
| Dell          | Inspiron 5580               | [29d56d5a5e](https://linux-hardware.org/?probe=29d56d5a5e) | Dec 06, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [2694c27280](https://linux-hardware.org/?probe=2694c27280) | Dec 05, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [4a20a593d0](https://linux-hardware.org/?probe=4a20a593d0) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | [a859413f86](https://linux-hardware.org/?probe=a859413f86) | Dec 05, 2021 |
| Apple         | MacBookPro12,1              | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| Lenovo        | ThinkPad T450 20BUS46900    | [980d2b1409](https://linux-hardware.org/?probe=980d2b1409) | Dec 04, 2021 |
| HP            | EliteBook 8460p             | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5f7a6857d1](https://linux-hardware.org/?probe=5f7a6857d1) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2522Y15       | [8b9bc362b3](https://linux-hardware.org/?probe=8b9bc362b3) | Dec 04, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [ec05196354](https://linux-hardware.org/?probe=ec05196354) | Dec 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1adcfe3e5e](https://linux-hardware.org/?probe=1adcfe3e5e) | Dec 03, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ae648efae](https://linux-hardware.org/?probe=0ae648efae) | Dec 03, 2021 |
| Dell          | Latitude E6400              | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| HP            | Laptop 15-db0xxx            | [b7a0fe35eb](https://linux-hardware.org/?probe=b7a0fe35eb) | Dec 03, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | [0da495ab3b](https://linux-hardware.org/?probe=0da495ab3b) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f102e6537d](https://linux-hardware.org/?probe=f102e6537d) | Dec 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [92c4d0059f](https://linux-hardware.org/?probe=92c4d0059f) | Dec 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [42575594c3](https://linux-hardware.org/?probe=42575594c3) | Dec 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4459608572](https://linux-hardware.org/?probe=4459608572) | Dec 02, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [37d28d8425](https://linux-hardware.org/?probe=37d28d8425) | Dec 02, 2021 |
| Dell          | Inspiron 3793               | [bdd0f25735](https://linux-hardware.org/?probe=bdd0f25735) | Dec 01, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [933ffd0145](https://linux-hardware.org/?probe=933ffd0145) | Dec 01, 2021 |
| Lenovo        | ThinkPad T410 2522Y15       | [c57f5d2453](https://linux-hardware.org/?probe=c57f5d2453) | Nov 30, 2021 |
| ASUSTek       | N56VM                       | [4ae50a5146](https://linux-hardware.org/?probe=4ae50a5146) | Nov 30, 2021 |
| Tablet        | 8                           | [36164d26c8](https://linux-hardware.org/?probe=36164d26c8) | Nov 30, 2021 |
| Celestica     | D4040                       | [109f886f1d](https://linux-hardware.org/?probe=109f886f1d) | Nov 30, 2021 |
| Dell          | XPS 15 7590                 | [22d048c93d](https://linux-hardware.org/?probe=22d048c93d) | Nov 30, 2021 |
| AXDIA Inte... | MYBOOK 14 PRO               | [1bc2e1056c](https://linux-hardware.org/?probe=1bc2e1056c) | Nov 30, 2021 |
| HP            | EliteBook 840 G2            | [81e0d1f84c](https://linux-hardware.org/?probe=81e0d1f84c) | Nov 30, 2021 |
| Acer          | Swift SF314-56              | [6c60445d08](https://linux-hardware.org/?probe=6c60445d08) | Nov 29, 2021 |
| Panasonic     | CF-54-1                     | [8f2224d84d](https://linux-hardware.org/?probe=8f2224d84d) | Nov 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [12b910d10b](https://linux-hardware.org/?probe=12b910d10b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [cca6a99387](https://linux-hardware.org/?probe=cca6a99387) | Nov 29, 2021 |
| MSI           | MS-N014                     | [f98cf89699](https://linux-hardware.org/?probe=f98cf89699) | Nov 29, 2021 |
| MSI           | MS-N014                     | [a90d5979be](https://linux-hardware.org/?probe=a90d5979be) | Nov 29, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [2360f50367](https://linux-hardware.org/?probe=2360f50367) | Nov 29, 2021 |
| IBM           | ThinkPad T43 2668BU7        | [594b3488d6](https://linux-hardware.org/?probe=594b3488d6) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| Acer          | Aspire 5610                 | [853aee060d](https://linux-hardware.org/?probe=853aee060d) | Nov 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4fa0a94620](https://linux-hardware.org/?probe=4fa0a94620) | Nov 28, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [6e1ecfa79e](https://linux-hardware.org/?probe=6e1ecfa79e) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Toshiba       | Satellite L40               | [d031ddee30](https://linux-hardware.org/?probe=d031ddee30) | Nov 28, 2021 |
| Acer          | TravelMate P214-52          | [bea2d6c254](https://linux-hardware.org/?probe=bea2d6c254) | Nov 27, 2021 |
| HP            | ZBook Studio G4             | [eb3da87330](https://linux-hardware.org/?probe=eb3da87330) | Nov 27, 2021 |
| HP            | Pavilion dv6                | [e81d5a7298](https://linux-hardware.org/?probe=e81d5a7298) | Nov 27, 2021 |
| HP            | Pavilion dv6                | [02376f3101](https://linux-hardware.org/?probe=02376f3101) | Nov 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [c6289480ca](https://linux-hardware.org/?probe=c6289480ca) | Nov 27, 2021 |
| Acer          | Aspire E5-521               | [7984741863](https://linux-hardware.org/?probe=7984741863) | Nov 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [16be623c84](https://linux-hardware.org/?probe=16be623c84) | Nov 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [f08b8241b0](https://linux-hardware.org/?probe=f08b8241b0) | Nov 26, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [bef33ffa93](https://linux-hardware.org/?probe=bef33ffa93) | Nov 26, 2021 |
| Dell          | XPS 13 9310                 | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Lenovo        | B50-10 80QR                 | [5e57df0c06](https://linux-hardware.org/?probe=5e57df0c06) | Nov 26, 2021 |
| HUAWEI        | HVY-WXX9                    | [7569ef6338](https://linux-hardware.org/?probe=7569ef6338) | Nov 26, 2021 |
| AXDIA Inte... | Wintab 10                   | [9db3481488](https://linux-hardware.org/?probe=9db3481488) | Nov 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [5f3cfbdd91](https://linux-hardware.org/?probe=5f3cfbdd91) | Nov 25, 2021 |
| HP            | Presario CQ56               | [a9203b72bb](https://linux-hardware.org/?probe=a9203b72bb) | Nov 25, 2021 |
| Compal        | QAL51                       | [d7e7cedc5c](https://linux-hardware.org/?probe=d7e7cedc5c) | Nov 25, 2021 |
| AXDIA Inte... | Wintab 10                   | [04f77c36b0](https://linux-hardware.org/?probe=04f77c36b0) | Nov 24, 2021 |
| Lenovo        | ThinkPad W540 20BG0042FR    | [02b8528d76](https://linux-hardware.org/?probe=02b8528d76) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| Dell          | Latitude 7480               | [75937fb177](https://linux-hardware.org/?probe=75937fb177) | Nov 24, 2021 |
| Dell          | Latitude 7480               | [019d4a4604](https://linux-hardware.org/?probe=019d4a4604) | Nov 24, 2021 |
| HP            | Presario CQ56               | [b50968704d](https://linux-hardware.org/?probe=b50968704d) | Nov 24, 2021 |
| Lenovo        | V330-15IKB 81AX             | [6d61fe8c06](https://linux-hardware.org/?probe=6d61fe8c06) | Nov 24, 2021 |
| Dell          | XPS 15 9560                 | [d13563df7f](https://linux-hardware.org/?probe=d13563df7f) | Nov 24, 2021 |
| Acer          | Aspire 5610                 | [8fa3c5f33c](https://linux-hardware.org/?probe=8fa3c5f33c) | Nov 23, 2021 |
| Dell          | Inspiron 11-3168            | [b7b3b8ef38](https://linux-hardware.org/?probe=b7b3b8ef38) | Nov 23, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | [d279b3f946](https://linux-hardware.org/?probe=d279b3f946) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d5a663555f](https://linux-hardware.org/?probe=d5a663555f) | Nov 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2b69fd787e](https://linux-hardware.org/?probe=2b69fd787e) | Nov 21, 2021 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [2e109e9059](https://linux-hardware.org/?probe=2e109e9059) | Nov 21, 2021 |
| Dell          | Latitude E6330              | [843131a308](https://linux-hardware.org/?probe=843131a308) | Nov 21, 2021 |
| HP            | ENVY m7                     | [97fae6afa0](https://linux-hardware.org/?probe=97fae6afa0) | Nov 21, 2021 |
| Lenovo        | ThinkPad T480s 20L8S31E0... | [5015d88753](https://linux-hardware.org/?probe=5015d88753) | Nov 21, 2021 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [f66705283e](https://linux-hardware.org/?probe=f66705283e) | Nov 21, 2021 |
| HP            | ProBook 650 G1              | [9a66408c2e](https://linux-hardware.org/?probe=9a66408c2e) | Nov 21, 2021 |
| IBM           | ThinkPad T43 2668BU7        | [12017f88c5](https://linux-hardware.org/?probe=12017f88c5) | Nov 21, 2021 |
| Sony          | VGN-NS30E_S                 | [a36535818d](https://linux-hardware.org/?probe=a36535818d) | Nov 20, 2021 |
| IBM           | ThinkPad T43 26686ZG        | [837bd8895e](https://linux-hardware.org/?probe=837bd8895e) | Nov 20, 2021 |
| Lenovo        | ThinkPad T440s 20AR003RM... | [2c0279ade5](https://linux-hardware.org/?probe=2c0279ade5) | Nov 20, 2021 |
| Dell          | Precision 5520              | [0ca00fe3e9](https://linux-hardware.org/?probe=0ca00fe3e9) | Nov 20, 2021 |
| IBM           | ThinkPad T43 26688AG        | [f0e357cf85](https://linux-hardware.org/?probe=f0e357cf85) | Nov 20, 2021 |
| IBM           | ThinkPad T43 26688AG        | [26b7c2dab9](https://linux-hardware.org/?probe=26b7c2dab9) | Nov 20, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581LV_... | [065770fe24](https://linux-hardware.org/?probe=065770fe24) | Nov 19, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | [d68e11bb6f](https://linux-hardware.org/?probe=d68e11bb6f) | Nov 19, 2021 |
| Acer          | TravelMate 4220             | [154009efd2](https://linux-hardware.org/?probe=154009efd2) | Nov 19, 2021 |
| Acer          | TravelMate 4220             | [b437a6cdee](https://linux-hardware.org/?probe=b437a6cdee) | Nov 19, 2021 |
| HP            | ProBook 4530s               | [de11d1bb53](https://linux-hardware.org/?probe=de11d1bb53) | Nov 19, 2021 |
| Compal        | QAL51                       | [9922147938](https://linux-hardware.org/?probe=9922147938) | Nov 19, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [15916ce478](https://linux-hardware.org/?probe=15916ce478) | Nov 19, 2021 |
| Apple         | MacBookAir7,2               | [4a24670ff6](https://linux-hardware.org/?probe=4a24670ff6) | Nov 19, 2021 |
| Lenovo        | G50-30 80G0                 | [1604bcdd0d](https://linux-hardware.org/?probe=1604bcdd0d) | Nov 19, 2021 |
| HP            | EliteBook 840 G2            | [736657999a](https://linux-hardware.org/?probe=736657999a) | Nov 18, 2021 |
| Lenovo        | V14-IIL 82C4                | [7f0992aae9](https://linux-hardware.org/?probe=7f0992aae9) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6da7601574](https://linux-hardware.org/?probe=6da7601574) | Nov 18, 2021 |
| Dell          | Inspiron 3793               | [bc9da19934](https://linux-hardware.org/?probe=bc9da19934) | Nov 18, 2021 |
| Google        | Stout                       | [2201cceced](https://linux-hardware.org/?probe=2201cceced) | Nov 17, 2021 |
| Lenovo        | ThinkPad 20J10046US         | [1597db42c1](https://linux-hardware.org/?probe=1597db42c1) | Nov 17, 2021 |
| Dell          | Inspiron 3793               | [a1c2626420](https://linux-hardware.org/?probe=a1c2626420) | Nov 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [3025843274](https://linux-hardware.org/?probe=3025843274) | Nov 17, 2021 |
| Sony          | SVE1712E1RB                 | [4be9dde00d](https://linux-hardware.org/?probe=4be9dde00d) | Nov 17, 2021 |
| Dell          | System XPS L502X            | [8d247d71f2](https://linux-hardware.org/?probe=8d247d71f2) | Nov 17, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | [66fd774069](https://linux-hardware.org/?probe=66fd774069) | Nov 17, 2021 |
| Sony          | SVE1712E1RB                 | [2416868324](https://linux-hardware.org/?probe=2416868324) | Nov 17, 2021 |
| ASUSTek       | 1015PE                      | [9735619dd6](https://linux-hardware.org/?probe=9735619dd6) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | [72ac73a219](https://linux-hardware.org/?probe=72ac73a219) | Nov 16, 2021 |
| Apple         | MacBookPro5,5               | [706587b8f3](https://linux-hardware.org/?probe=706587b8f3) | Nov 16, 2021 |
| Lenovo        | ThinkPad T430 2347G61       | [12ee1cee2b](https://linux-hardware.org/?probe=12ee1cee2b) | Nov 16, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [f65310e00b](https://linux-hardware.org/?probe=f65310e00b) | Nov 16, 2021 |
| Acer          | TravelMate 8371             | [312ed52708](https://linux-hardware.org/?probe=312ed52708) | Nov 16, 2021 |
| Acer          | TravelMate 8371             | [78b196a98c](https://linux-hardware.org/?probe=78b196a98c) | Nov 16, 2021 |
| MSI           | GE60 2PL                    | [7287f7a1ae](https://linux-hardware.org/?probe=7287f7a1ae) | Nov 15, 2021 |
| HP            | EliteBook 2560p             | [fc04d52b16](https://linux-hardware.org/?probe=fc04d52b16) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [74ce7d98c6](https://linux-hardware.org/?probe=74ce7d98c6) | Nov 15, 2021 |
| Acer          | Aspire A715-72G             | [2a2d9fc8f1](https://linux-hardware.org/?probe=2a2d9fc8f1) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [180bbba91c](https://linux-hardware.org/?probe=180bbba91c) | Nov 15, 2021 |
| Acer          | Aspire A517-51G             | [a580b8a73f](https://linux-hardware.org/?probe=a580b8a73f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [8c23aaf339](https://linux-hardware.org/?probe=8c23aaf339) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | [ce5eb49ae7](https://linux-hardware.org/?probe=ce5eb49ae7) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | [5574978db2](https://linux-hardware.org/?probe=5574978db2) | Nov 14, 2021 |
| HP            | EliteBook 2740p             | [8406ced05c](https://linux-hardware.org/?probe=8406ced05c) | Nov 14, 2021 |
| HP            | EliteBook 2740p             | [f035cd561e](https://linux-hardware.org/?probe=f035cd561e) | Nov 14, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [4d129ac049](https://linux-hardware.org/?probe=4d129ac049) | Nov 14, 2021 |
| Dell          | Latitude E6330              | [a03858cc87](https://linux-hardware.org/?probe=a03858cc87) | Nov 13, 2021 |
| MSI           | Prestige 15 A10SC           | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [c1a976d644](https://linux-hardware.org/?probe=c1a976d644) | Nov 13, 2021 |
| Lenovo        | ThinkPad X201 3626GG3       | [78619d2639](https://linux-hardware.org/?probe=78619d2639) | Nov 12, 2021 |
| Compal        | QAL51                       | [431d587da7](https://linux-hardware.org/?probe=431d587da7) | Nov 12, 2021 |
| Acer          | Aspire F5-573G              | [768c187f40](https://linux-hardware.org/?probe=768c187f40) | Nov 12, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [79e78d0c90](https://linux-hardware.org/?probe=79e78d0c90) | Nov 11, 2021 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | [edb83bd184](https://linux-hardware.org/?probe=edb83bd184) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [00e34bc46e](https://linux-hardware.org/?probe=00e34bc46e) | Nov 11, 2021 |
| ASUSTek       | T100TA                      | [867e0388ae](https://linux-hardware.org/?probe=867e0388ae) | Nov 11, 2021 |
| HP            | EliteBook 8440p             | [1bdbee29eb](https://linux-hardware.org/?probe=1bdbee29eb) | Nov 10, 2021 |
| HP            | EliteBook 8440p             | [e4961a7cfc](https://linux-hardware.org/?probe=e4961a7cfc) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| ASUSTek       | 1011PX                      | [2d96503388](https://linux-hardware.org/?probe=2d96503388) | Nov 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [6e415a1506](https://linux-hardware.org/?probe=6e415a1506) | Nov 10, 2021 |
| Dell          | Inspiron 7472               | [2508fadf63](https://linux-hardware.org/?probe=2508fadf63) | Nov 10, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [606263f5e9](https://linux-hardware.org/?probe=606263f5e9) | Nov 10, 2021 |
| MSI           | GS65 Stealth 9SE            | [bef876576b](https://linux-hardware.org/?probe=bef876576b) | Nov 09, 2021 |
| Lenovo        | 14w 81MQ00AHAR              | [17785cda04](https://linux-hardware.org/?probe=17785cda04) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [107c6e9840](https://linux-hardware.org/?probe=107c6e9840) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [006454048e](https://linux-hardware.org/?probe=006454048e) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [466c86045e](https://linux-hardware.org/?probe=466c86045e) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [e9818fe37e](https://linux-hardware.org/?probe=e9818fe37e) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [eeb1d38579](https://linux-hardware.org/?probe=eeb1d38579) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [deab410735](https://linux-hardware.org/?probe=deab410735) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [1ab4a1aebc](https://linux-hardware.org/?probe=1ab4a1aebc) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [6d39af3a58](https://linux-hardware.org/?probe=6d39af3a58) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [e8bbdb29d1](https://linux-hardware.org/?probe=e8bbdb29d1) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [ccd62944b4](https://linux-hardware.org/?probe=ccd62944b4) | Nov 09, 2021 |
| Apple         | MacBookAir7,1               | [125724b6a0](https://linux-hardware.org/?probe=125724b6a0) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | [beada5c26b](https://linux-hardware.org/?probe=beada5c26b) | Nov 09, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HP            | ProBook 645 G2              | [64b38adff8](https://linux-hardware.org/?probe=64b38adff8) | Nov 09, 2021 |
| Dell          | Latitude E5570              | [b2398623fc](https://linux-hardware.org/?probe=b2398623fc) | Nov 09, 2021 |
| Dell          | Vostro 5568                 | [8efc2ed27a](https://linux-hardware.org/?probe=8efc2ed27a) | Nov 08, 2021 |
| Lenovo        | ThinkPad E450 20DCS01J00    | [ee83aa5751](https://linux-hardware.org/?probe=ee83aa5751) | Nov 08, 2021 |
| Dell          | Vostro 5568                 | [b247ac9f61](https://linux-hardware.org/?probe=b247ac9f61) | Nov 08, 2021 |
| Fujitsu Si... | AMILO Si 2636               | [ca32959cf7](https://linux-hardware.org/?probe=ca32959cf7) | Nov 08, 2021 |
| Dell          | Precision M4800             | [30a32fb8df](https://linux-hardware.org/?probe=30a32fb8df) | Nov 08, 2021 |
| Acer          | Nitro AN515-52              | [4b834a3bff](https://linux-hardware.org/?probe=4b834a3bff) | Nov 07, 2021 |
| Acer          | Nitro AN515-52              | [8c6816916c](https://linux-hardware.org/?probe=8c6816916c) | Nov 07, 2021 |
| Dell          | Inspiron 15-3567            | [9c14e4d461](https://linux-hardware.org/?probe=9c14e4d461) | Nov 06, 2021 |
| Dell          | Latitude E6330              | [cafb5e6e80](https://linux-hardware.org/?probe=cafb5e6e80) | Nov 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [31f91364c1](https://linux-hardware.org/?probe=31f91364c1) | Nov 04, 2021 |
| HP            | Laptop 14-ck0xxx            | [8d24d56a03](https://linux-hardware.org/?probe=8d24d56a03) | Nov 04, 2021 |
| HP            | EliteBook 840 G2            | [cd9efb14b2](https://linux-hardware.org/?probe=cd9efb14b2) | Nov 04, 2021 |
| Aquarius      | NS585                       | [8d7faba1cb](https://linux-hardware.org/?probe=8d7faba1cb) | Nov 04, 2021 |
| Aquarius      | NS585                       | [99b57214d1](https://linux-hardware.org/?probe=99b57214d1) | Nov 04, 2021 |
| Dell          | Latitude 5511               | [6dca737664](https://linux-hardware.org/?probe=6dca737664) | Nov 04, 2021 |
| Dell          | Latitude 5511               | [f2ef4f8e35](https://linux-hardware.org/?probe=f2ef4f8e35) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460s 20FACTO1W... | [1d6e8a6521](https://linux-hardware.org/?probe=1d6e8a6521) | Nov 04, 2021 |
| HP            | Pavilion dv4                | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [a7629cdfd1](https://linux-hardware.org/?probe=a7629cdfd1) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480 20L50009MX    | [349faf5242](https://linux-hardware.org/?probe=349faf5242) | Nov 03, 2021 |
| HP            | EliteBook 840 G2            | [2e08c10fec](https://linux-hardware.org/?probe=2e08c10fec) | Nov 02, 2021 |
| Dell          | Vostro 3500                 | [6eb01124a7](https://linux-hardware.org/?probe=6eb01124a7) | Nov 02, 2021 |
| HP            | Laptop 15-bw0xx             | [1869db225e](https://linux-hardware.org/?probe=1869db225e) | Nov 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8b2a91de37](https://linux-hardware.org/?probe=8b2a91de37) | Nov 01, 2021 |
| ASUSTek       | X555LD                      | [5de4d7d11a](https://linux-hardware.org/?probe=5de4d7d11a) | Nov 01, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3040be6e81](https://linux-hardware.org/?probe=3040be6e81) | Nov 01, 2021 |
| Dell          | Vostro 5471                 | [8182230d1d](https://linux-hardware.org/?probe=8182230d1d) | Nov 01, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [69a252ccd6](https://linux-hardware.org/?probe=69a252ccd6) | Oct 31, 2021 |
| Dell          | Inspiron 5502               | [e58d33df6b](https://linux-hardware.org/?probe=e58d33df6b) | Oct 31, 2021 |
| Unknown       | MT8117                      | [b579146661](https://linux-hardware.org/?probe=b579146661) | Oct 31, 2021 |
| Dell          | Inspiron 1525               | [38b4ba227c](https://linux-hardware.org/?probe=38b4ba227c) | Oct 30, 2021 |
| Dell          | Inspiron 1525               | [b6302b710d](https://linux-hardware.org/?probe=b6302b710d) | Oct 30, 2021 |
| Dell          | Vostro 3500                 | [60f4ac8cc5](https://linux-hardware.org/?probe=60f4ac8cc5) | Oct 30, 2021 |
| Apple         | MacBookAir7,2               | [5be083edab](https://linux-hardware.org/?probe=5be083edab) | Oct 29, 2021 |
| Dell          | Latitude E7240              | [dbf0fd04c3](https://linux-hardware.org/?probe=dbf0fd04c3) | Oct 28, 2021 |
| Compal        | QAL51                       | [ffffaf4799](https://linux-hardware.org/?probe=ffffaf4799) | Oct 28, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [085ef9e58d](https://linux-hardware.org/?probe=085ef9e58d) | Oct 28, 2021 |
| Acer          | Nitro AN515-54              | [d85a5ada85](https://linux-hardware.org/?probe=d85a5ada85) | Oct 28, 2021 |
| HP            | EliteBook 840 G2            | [a7cc3183f2](https://linux-hardware.org/?probe=a7cc3183f2) | Oct 28, 2021 |
| HP            | Notebook                    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| HP            | Laptop 17-by1xxx            | [e6406f34f8](https://linux-hardware.org/?probe=e6406f34f8) | Oct 27, 2021 |
| Dell          | Latitude E6330              | [872cfff7da](https://linux-hardware.org/?probe=872cfff7da) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | [5026826dbe](https://linux-hardware.org/?probe=5026826dbe) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | [f644310091](https://linux-hardware.org/?probe=f644310091) | Oct 26, 2021 |
| Dell          | Latitude E6330              | [c3e7f97c42](https://linux-hardware.org/?probe=c3e7f97c42) | Oct 25, 2021 |
| Dell          | Latitude E6330              | [0e88df3ae7](https://linux-hardware.org/?probe=0e88df3ae7) | Oct 25, 2021 |
| HP            | Pavilion g6                 | [2c2d7620f9](https://linux-hardware.org/?probe=2c2d7620f9) | Oct 25, 2021 |
| Acer          | AOA150                      | [1380638bb1](https://linux-hardware.org/?probe=1380638bb1) | Oct 25, 2021 |
| Dell          | Latitude E6540              | [df9262f810](https://linux-hardware.org/?probe=df9262f810) | Oct 25, 2021 |
| Acer          | Swift SF314-59              | [1e4856a770](https://linux-hardware.org/?probe=1e4856a770) | Oct 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [be67e01a7d](https://linux-hardware.org/?probe=be67e01a7d) | Oct 24, 2021 |
| Acer          | Aspire A315-23G             | [09f6196e70](https://linux-hardware.org/?probe=09f6196e70) | Oct 23, 2021 |
| Dell          | Latitude E6330              | [e7a19ad923](https://linux-hardware.org/?probe=e7a19ad923) | Oct 23, 2021 |
| HP            | ProBook 430 G5              | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c8f19e95d8](https://linux-hardware.org/?probe=c8f19e95d8) | Oct 23, 2021 |
| Dell          | Inspiron 11 - 3147          | [7354eacfc5](https://linux-hardware.org/?probe=7354eacfc5) | Oct 23, 2021 |
| Jumper        | EZbook                      | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HP            | EliteBook 840 Aero G8 No... | [713c29aa23](https://linux-hardware.org/?probe=713c29aa23) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [bcc008e381](https://linux-hardware.org/?probe=bcc008e381) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [55dcb690c5](https://linux-hardware.org/?probe=55dcb690c5) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | [85a514f622](https://linux-hardware.org/?probe=85a514f622) | Oct 22, 2021 |
| LG Electro... | X120-L.C7L1A9               | [42b7007a7e](https://linux-hardware.org/?probe=42b7007a7e) | Oct 21, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [fe4c73ce24](https://linux-hardware.org/?probe=fe4c73ce24) | Oct 21, 2021 |
| HP            | 250 G1                      | [b34fa14c55](https://linux-hardware.org/?probe=b34fa14c55) | Oct 21, 2021 |
| Dell          | Inspiron 11 - 3147          | [7039c3e31f](https://linux-hardware.org/?probe=7039c3e31f) | Oct 20, 2021 |
| Acer          | Aspire A315-23              | [e8b00fa29b](https://linux-hardware.org/?probe=e8b00fa29b) | Oct 20, 2021 |
| HP            | Laptop 15-db0xxx            | [cd4a22e83b](https://linux-hardware.org/?probe=cd4a22e83b) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2c5f518cc8](https://linux-hardware.org/?probe=2c5f518cc8) | Oct 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Lenovo        | ThinkPad 20J10046US         | [cad3a5eb69](https://linux-hardware.org/?probe=cad3a5eb69) | Oct 18, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [ea23d24f90](https://linux-hardware.org/?probe=ea23d24f90) | Oct 18, 2021 |
| Aquarius      | NS585                       | [ea22908ff7](https://linux-hardware.org/?probe=ea22908ff7) | Oct 18, 2021 |
| Aquarius      | NS585                       | [daf0f8d357](https://linux-hardware.org/?probe=daf0f8d357) | Oct 18, 2021 |
| MSI           | GF75 Thin 9SC               | [1f4a66b99a](https://linux-hardware.org/?probe=1f4a66b99a) | Oct 18, 2021 |
| Aquarius      | NS585                       | [0f5ea2eb9a](https://linux-hardware.org/?probe=0f5ea2eb9a) | Oct 18, 2021 |
| Aquarius      | NS585                       | [08f117fdcb](https://linux-hardware.org/?probe=08f117fdcb) | Oct 18, 2021 |
| Aquarius      | NS585                       | [3921dda159](https://linux-hardware.org/?probe=3921dda159) | Oct 18, 2021 |
| Aquarius      | NS585                       | [22c808750d](https://linux-hardware.org/?probe=22c808750d) | Oct 18, 2021 |
| Acer          | Aspire A315-23G             | [66d1015de7](https://linux-hardware.org/?probe=66d1015de7) | Oct 17, 2021 |
| Acer          | Aspire A515-51G             | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Lenovo        | S10-3                       | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Dell          | XPS 13 9305                 | [d13426531e](https://linux-hardware.org/?probe=d13426531e) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite A205              | [68ac15eeda](https://linux-hardware.org/?probe=68ac15eeda) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| Lenovo        | S10-3                       | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | G50-45 80E3                 | [5e79417ff5](https://linux-hardware.org/?probe=5e79417ff5) | Oct 16, 2021 |
| Apple         | MacBook3,1                  | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| Acer          | TravelMate P215-53          | [3d398d4b58](https://linux-hardware.org/?probe=3d398d4b58) | Oct 16, 2021 |
| Lenovo        | ThinkPad X60 17068GG        | [2f3b34aac4](https://linux-hardware.org/?probe=2f3b34aac4) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | [dc7e454319](https://linux-hardware.org/?probe=dc7e454319) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | [bf9482b190](https://linux-hardware.org/?probe=bf9482b190) | Oct 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [a7045defdf](https://linux-hardware.org/?probe=a7045defdf) | Oct 15, 2021 |
| Dell          | XPS 15 7590                 | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9005e4d86d](https://linux-hardware.org/?probe=9005e4d86d) | Oct 15, 2021 |
| Lenovo        | ThinkPad 20J10046US         | [2d46a44cca](https://linux-hardware.org/?probe=2d46a44cca) | Oct 14, 2021 |
| Apple         | MacBookAir7,2               | [f78b91b7de](https://linux-hardware.org/?probe=f78b91b7de) | Oct 14, 2021 |
| Acer          | Aspire A315-23G             | [f8f343d12b](https://linux-hardware.org/?probe=f8f343d12b) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| Aquarius      | NS585                       | [7345eddec4](https://linux-hardware.org/?probe=7345eddec4) | Oct 14, 2021 |
| Apple         | MacBookAir7,1               | [22a831db3d](https://linux-hardware.org/?probe=22a831db3d) | Oct 14, 2021 |
| Aquarius      | NS585                       | [d42e0a77d4](https://linux-hardware.org/?probe=d42e0a77d4) | Oct 14, 2021 |
| Aquarius      | NS585                       | [7b0dd9fe28](https://linux-hardware.org/?probe=7b0dd9fe28) | Oct 14, 2021 |
| Aquarius      | NS585                       | [ea53e809fd](https://linux-hardware.org/?probe=ea53e809fd) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| Aquarius      | NS585                       | [aaca557699](https://linux-hardware.org/?probe=aaca557699) | Oct 14, 2021 |
| Sony          | VAIO                        | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [2ae81cd94f](https://linux-hardware.org/?probe=2ae81cd94f) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [69b1046c6e](https://linux-hardware.org/?probe=69b1046c6e) | Oct 13, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cdb34ca184](https://linux-hardware.org/?probe=cdb34ca184) | Oct 13, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [923479d039](https://linux-hardware.org/?probe=923479d039) | Oct 13, 2021 |
| ASUSTek       | TP201SA                     | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| ASUSTek       | UX303LAB                    | [97b9f51735](https://linux-hardware.org/?probe=97b9f51735) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | [db0ef927e0](https://linux-hardware.org/?probe=db0ef927e0) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | [be82875929](https://linux-hardware.org/?probe=be82875929) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| HP            | G62                         | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [b01543c6b8](https://linux-hardware.org/?probe=b01543c6b8) | Oct 12, 2021 |
| Acer          | Aspire ES1-531              | [2a96c0566a](https://linux-hardware.org/?probe=2a96c0566a) | Oct 12, 2021 |
| Dell          | XPS 15 9560                 | [69938c221e](https://linux-hardware.org/?probe=69938c221e) | Oct 12, 2021 |
| Dell          | Vostro 3500                 | [4e86b85a4d](https://linux-hardware.org/?probe=4e86b85a4d) | Oct 12, 2021 |
| Acer          | Aspire A315-23G             | [6476999787](https://linux-hardware.org/?probe=6476999787) | Oct 12, 2021 |
| Lenovo        | ThinkPad T520 4242W9B       | [3947636b4d](https://linux-hardware.org/?probe=3947636b4d) | Oct 12, 2021 |
| Dell          | Inspiron 5567               | [e551d622a8](https://linux-hardware.org/?probe=e551d622a8) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [dce9cc60d3](https://linux-hardware.org/?probe=dce9cc60d3) | Oct 11, 2021 |
| HP            | EliteBook 8460p             | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| Acer          | Aspire A315-23G             | [c97f94ce2f](https://linux-hardware.org/?probe=c97f94ce2f) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [598d90e6b6](https://linux-hardware.org/?probe=598d90e6b6) | Oct 10, 2021 |
| HP            | TouchSmart tm2              | [4a04d297c6](https://linux-hardware.org/?probe=4a04d297c6) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| Dell          | Inspiron 5559               | [3ab285ffb2](https://linux-hardware.org/?probe=3ab285ffb2) | Oct 09, 2021 |
| ASUSTek       | GL553VE                     | [cbbb88337f](https://linux-hardware.org/?probe=cbbb88337f) | Oct 09, 2021 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [00a9d32484](https://linux-hardware.org/?probe=00a9d32484) | Oct 08, 2021 |
| ASUSTek       | N501VW                      | [40231fbffa](https://linux-hardware.org/?probe=40231fbffa) | Oct 08, 2021 |
| Dell          | Latitude 7480               | [e4d0ecb120](https://linux-hardware.org/?probe=e4d0ecb120) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d76a0d7ff1](https://linux-hardware.org/?probe=d76a0d7ff1) | Oct 07, 2021 |
| Dell          | Latitude E6520              | [18591f972c](https://linux-hardware.org/?probe=18591f972c) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9ed170f601](https://linux-hardware.org/?probe=9ed170f601) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [97f69ae3fa](https://linux-hardware.org/?probe=97f69ae3fa) | Oct 07, 2021 |
| Dell          | Vostro A860                 | [02a4dade57](https://linux-hardware.org/?probe=02a4dade57) | Oct 07, 2021 |
| Dell          | Vostro A860                 | [67da5c585b](https://linux-hardware.org/?probe=67da5c585b) | Oct 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| MSI           | GF63 8RD                    | [42dfecd0fb](https://linux-hardware.org/?probe=42dfecd0fb) | Oct 06, 2021 |
| ASUSTek       | 1015PE                      | [1a2d7bc306](https://linux-hardware.org/?probe=1a2d7bc306) | Oct 06, 2021 |
| MSI           | GF63 8RD                    | [1c72d1e5d7](https://linux-hardware.org/?probe=1c72d1e5d7) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Dell          | Latitude 7480               | [89d642f54a](https://linux-hardware.org/?probe=89d642f54a) | Oct 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [eb4d94004c](https://linux-hardware.org/?probe=eb4d94004c) | Oct 06, 2021 |
| Apple         | MacBook3,1                  | [1e7ca025e2](https://linux-hardware.org/?probe=1e7ca025e2) | Oct 06, 2021 |
| HP            | EliteBook 2170p             | [b5e3aaff19](https://linux-hardware.org/?probe=b5e3aaff19) | Oct 06, 2021 |
| MSI           | Bravo 15 A4DDR              | [3c8835ecc1](https://linux-hardware.org/?probe=3c8835ecc1) | Oct 05, 2021 |
| HP            | 650                         | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [555befb01f](https://linux-hardware.org/?probe=555befb01f) | Oct 05, 2021 |
| Apple         | MacBookAir7,2               | [9a8833b9c4](https://linux-hardware.org/?probe=9a8833b9c4) | Oct 04, 2021 |
| Dell          | Latitude 7480               | [e8c50a7dbb](https://linux-hardware.org/?probe=e8c50a7dbb) | Oct 04, 2021 |
| Dell          | Latitude E6520              | [b9f0ad8ced](https://linux-hardware.org/?probe=b9f0ad8ced) | Oct 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [bcdf58bee3](https://linux-hardware.org/?probe=bcdf58bee3) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| Acer          | Aspire A315-23G             | [9622936906](https://linux-hardware.org/?probe=9622936906) | Oct 04, 2021 |
| HP            | EliteBook 830 G6            | [ccc383c91f](https://linux-hardware.org/?probe=ccc383c91f) | Oct 03, 2021 |
| HP            | EliteBook 830 G6            | [8a9c0fa053](https://linux-hardware.org/?probe=8a9c0fa053) | Oct 03, 2021 |
| Acer          | TMP645-M                    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [52d91383da](https://linux-hardware.org/?probe=52d91383da) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| HP            | Laptop 15-ra0xx             | [f053eed9e5](https://linux-hardware.org/?probe=f053eed9e5) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | [5dff50e4bf](https://linux-hardware.org/?probe=5dff50e4bf) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | [eae46e3544](https://linux-hardware.org/?probe=eae46e3544) | Oct 02, 2021 |
| Dell          | Inspiron 3421               | [8169f29a6a](https://linux-hardware.org/?probe=8169f29a6a) | Oct 02, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [f5565dfb2a](https://linux-hardware.org/?probe=f5565dfb2a) | Oct 01, 2021 |
| HP            | ProBook 430 G6              | [f248667e17](https://linux-hardware.org/?probe=f248667e17) | Oct 01, 2021 |
| HP            | Pavilion g6                 | [ca85ba36e3](https://linux-hardware.org/?probe=ca85ba36e3) | Oct 01, 2021 |
| Lenovo        | B50-30 20382                | [85242c59b6](https://linux-hardware.org/?probe=85242c59b6) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [090eee57b7](https://linux-hardware.org/?probe=090eee57b7) | Oct 01, 2021 |
| TrekStor      | Surfbook A13                | [e393d9bc10](https://linux-hardware.org/?probe=e393d9bc10) | Oct 01, 2021 |
| MSI           | GF75 Thin 9SC               | [b62cc852e9](https://linux-hardware.org/?probe=b62cc852e9) | Oct 01, 2021 |
| Apple         | MacBookAir7,2               | [8fa4158350](https://linux-hardware.org/?probe=8fa4158350) | Sep 30, 2021 |
| Dell          | Latitude 7480               | [edecedab9c](https://linux-hardware.org/?probe=edecedab9c) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Intel Clie... | LAPBC710                    | [f2535939a1](https://linux-hardware.org/?probe=f2535939a1) | Sep 29, 2021 |
| Timi          | TM1613                      | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Dell          | Precision 3561              | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [885bbac853](https://linux-hardware.org/?probe=885bbac853) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8e7519557](https://linux-hardware.org/?probe=b8e7519557) | Sep 29, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [d277db28c5](https://linux-hardware.org/?probe=d277db28c5) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Latitude D630               | [5e7edac95e](https://linux-hardware.org/?probe=5e7edac95e) | Sep 29, 2021 |
| Apple         | MacBookPro14,1              | [01ccd7b321](https://linux-hardware.org/?probe=01ccd7b321) | Sep 28, 2021 |
| Google        | Enguarde                    | [36df7d61be](https://linux-hardware.org/?probe=36df7d61be) | Sep 28, 2021 |
| Google        | Enguarde                    | [4514b06137](https://linux-hardware.org/?probe=4514b06137) | Sep 28, 2021 |
| Google        | Enguarde                    | [ac6c9be38a](https://linux-hardware.org/?probe=ac6c9be38a) | Sep 28, 2021 |
| Google        | Enguarde                    | [36532b595e](https://linux-hardware.org/?probe=36532b595e) | Sep 28, 2021 |
| HP            | Pavilion g6                 | [a349ae4420](https://linux-hardware.org/?probe=a349ae4420) | Sep 28, 2021 |
| Google        | Enguarde                    | [b4273a32be](https://linux-hardware.org/?probe=b4273a32be) | Sep 28, 2021 |
| Google        | Enguarde                    | [0b6cac4bce](https://linux-hardware.org/?probe=0b6cac4bce) | Sep 28, 2021 |
| Google        | Enguarde                    | [3ebd210998](https://linux-hardware.org/?probe=3ebd210998) | Sep 28, 2021 |
| Google        | Enguarde                    | [8ad08b2012](https://linux-hardware.org/?probe=8ad08b2012) | Sep 28, 2021 |
| Apple         | MacBookAir7,1               | [b8706044ce](https://linux-hardware.org/?probe=b8706044ce) | Sep 28, 2021 |
| ASUSTek       | N550JV                      | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | X556UAK                     | [6cd310a2c4](https://linux-hardware.org/?probe=6cd310a2c4) | Sep 27, 2021 |
| Lenovo        | ThinkPad T430 2349N7G       | [d82d96a0ce](https://linux-hardware.org/?probe=d82d96a0ce) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | G50-45 80E3                 | [a01dd88bfb](https://linux-hardware.org/?probe=a01dd88bfb) | Sep 27, 2021 |
| Lenovo        | IdeaPad U510 4941           | [f0f189cfc9](https://linux-hardware.org/?probe=f0f189cfc9) | Sep 27, 2021 |
| HP            | G61                         | [348bab0a1b](https://linux-hardware.org/?probe=348bab0a1b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| MSI           | Bravo 15 A4DDR              | [5236361305](https://linux-hardware.org/?probe=5236361305) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f8f724934](https://linux-hardware.org/?probe=8f8f724934) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| Packard Be... | EasyNote TS11HR             | [abf2c60d3f](https://linux-hardware.org/?probe=abf2c60d3f) | Sep 26, 2021 |
| Acer          | Aspire F5-573G              | [97a2a90138](https://linux-hardware.org/?probe=97a2a90138) | Sep 26, 2021 |
| Toshiba       | Satellite C655D             | [7742f4cfe0](https://linux-hardware.org/?probe=7742f4cfe0) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [1f56f02f1d](https://linux-hardware.org/?probe=1f56f02f1d) | Sep 26, 2021 |
| Acer          | TravelMate 2490             | [b09a0d7779](https://linux-hardware.org/?probe=b09a0d7779) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [0c67accead](https://linux-hardware.org/?probe=0c67accead) | Sep 25, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [3b61d0a304](https://linux-hardware.org/?probe=3b61d0a304) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [2762c5237d](https://linux-hardware.org/?probe=2762c5237d) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [7a1202630f](https://linux-hardware.org/?probe=7a1202630f) | Sep 25, 2021 |
| Apple         | MacBookPro12,1              | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| HP            | Pavilion dv6                | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| Dell          | G3 3590                     | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [11ebd06d5f](https://linux-hardware.org/?probe=11ebd06d5f) | Sep 25, 2021 |
| HP            | ProBook 4530s               | [0fc1845cd7](https://linux-hardware.org/?probe=0fc1845cd7) | Sep 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e9d692e16d](https://linux-hardware.org/?probe=e9d692e16d) | Sep 24, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [c654d6756a](https://linux-hardware.org/?probe=c654d6756a) | Sep 24, 2021 |
| Dell          | Inspiron 5515               | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Dell          | Precision M4800             | [1d4a25cfec](https://linux-hardware.org/?probe=1d4a25cfec) | Sep 24, 2021 |
| Toshiba       | PORTEGE R830                | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| Acer          | TravelMate P273             | [125707a56f](https://linux-hardware.org/?probe=125707a56f) | Sep 24, 2021 |
| MSI           | GE70 2QE                    | [b1cbbbd78f](https://linux-hardware.org/?probe=b1cbbbd78f) | Sep 23, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Dell          | Inspiron 5593               | [5ddd391946](https://linux-hardware.org/?probe=5ddd391946) | Sep 23, 2021 |
| HP            | 15                          | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Apple         | MacBookAir7,1               | [e36127ceb6](https://linux-hardware.org/?probe=e36127ceb6) | Sep 22, 2021 |
| HP            | Pavilion dv6                | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8858844a](https://linux-hardware.org/?probe=1e8858844a) | Sep 22, 2021 |
| Dell          | Latitude E7240              | [7048aa6e8b](https://linux-hardware.org/?probe=7048aa6e8b) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [ff5e9a45c3](https://linux-hardware.org/?probe=ff5e9a45c3) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [64b5e6acaf](https://linux-hardware.org/?probe=64b5e6acaf) | Sep 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5e6cd3a827](https://linux-hardware.org/?probe=5e6cd3a827) | Sep 21, 2021 |
| Dell          | Vostro 5471                 | [4ce9cddd8f](https://linux-hardware.org/?probe=4ce9cddd8f) | Sep 21, 2021 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [65802f1a29](https://linux-hardware.org/?probe=65802f1a29) | Sep 21, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [14ea1aaa38](https://linux-hardware.org/?probe=14ea1aaa38) | Sep 21, 2021 |
| Lenovo        | ThinkPad T480S 20L7002HC... | [18b74e9f12](https://linux-hardware.org/?probe=18b74e9f12) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | [ab40e7b1de](https://linux-hardware.org/?probe=ab40e7b1de) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | [13687ea608](https://linux-hardware.org/?probe=13687ea608) | Sep 21, 2021 |
| ASUSTek       | K50IN                       | [7cdaef32aa](https://linux-hardware.org/?probe=7cdaef32aa) | Sep 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [203ccd91be](https://linux-hardware.org/?probe=203ccd91be) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | [e8748906aa](https://linux-hardware.org/?probe=e8748906aa) | Sep 20, 2021 |
| MSI           | GE70 2QE                    | [a8b9147ea7](https://linux-hardware.org/?probe=a8b9147ea7) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | [22262e98a5](https://linux-hardware.org/?probe=22262e98a5) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | [c266841471](https://linux-hardware.org/?probe=c266841471) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | [81802596f8](https://linux-hardware.org/?probe=81802596f8) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [d7ce22ebcb](https://linux-hardware.org/?probe=d7ce22ebcb) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [3c060f3910](https://linux-hardware.org/?probe=3c060f3910) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | [bcb44edae6](https://linux-hardware.org/?probe=bcb44edae6) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | [d623d8381b](https://linux-hardware.org/?probe=d623d8381b) | Sep 20, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [72c81ecb73](https://linux-hardware.org/?probe=72c81ecb73) | Sep 19, 2021 |
| MSI           | U270 series                 | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| Acer          | AOA110                      | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| MSI           | U270 series                 | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Lenovo        | G70-35 80Q5                 | [6ce6f8e7f7](https://linux-hardware.org/?probe=6ce6f8e7f7) | Sep 17, 2021 |
| Lenovo        | IdeaPad U510 4941           | [f5774645c1](https://linux-hardware.org/?probe=f5774645c1) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | [0f6db66354](https://linux-hardware.org/?probe=0f6db66354) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | [2179e59b37](https://linux-hardware.org/?probe=2179e59b37) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | [84394a400e](https://linux-hardware.org/?probe=84394a400e) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [726f5ed51f](https://linux-hardware.org/?probe=726f5ed51f) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [e0307085f3](https://linux-hardware.org/?probe=e0307085f3) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | [e7b42c85f1](https://linux-hardware.org/?probe=e7b42c85f1) | Sep 17, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [abd7f0d0a1](https://linux-hardware.org/?probe=abd7f0d0a1) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c8208bc767](https://linux-hardware.org/?probe=c8208bc767) | Sep 17, 2021 |
| MSI           | GF75 Thin 9SC               | [47a6cd4031](https://linux-hardware.org/?probe=47a6cd4031) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | [8d4eff5ca2](https://linux-hardware.org/?probe=8d4eff5ca2) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [f226485da3](https://linux-hardware.org/?probe=f226485da3) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [643fafdceb](https://linux-hardware.org/?probe=643fafdceb) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | [e801613095](https://linux-hardware.org/?probe=e801613095) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [fb0c3317e3](https://linux-hardware.org/?probe=fb0c3317e3) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [5282f852aa](https://linux-hardware.org/?probe=5282f852aa) | Sep 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd5496fa35](https://linux-hardware.org/?probe=dd5496fa35) | Sep 17, 2021 |
| Timi          | TM1801                      | [d0919977cb](https://linux-hardware.org/?probe=d0919977cb) | Sep 17, 2021 |
| MSI           | Bravo 15 A4DDR              | [722f184570](https://linux-hardware.org/?probe=722f184570) | Sep 17, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | X751LD                      | [df29a592fb](https://linux-hardware.org/?probe=df29a592fb) | Sep 16, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ee258307b1](https://linux-hardware.org/?probe=ee258307b1) | Sep 15, 2021 |
| PC Special... | Standard                    | [1454a60100](https://linux-hardware.org/?probe=1454a60100) | Sep 15, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | [576b90b734](https://linux-hardware.org/?probe=576b90b734) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | [e9c177240a](https://linux-hardware.org/?probe=e9c177240a) | Sep 15, 2021 |
| Acer          | AO725                       | [68eeff0c2f](https://linux-hardware.org/?probe=68eeff0c2f) | Sep 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [730c0eebf9](https://linux-hardware.org/?probe=730c0eebf9) | Sep 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Aquarius      | NS585                       | [7f88a77812](https://linux-hardware.org/?probe=7f88a77812) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Aquarius      | NS585                       | [f2363c7d5e](https://linux-hardware.org/?probe=f2363c7d5e) | Sep 14, 2021 |
| Acer          | Aspire A315-23              | [01008b3cfd](https://linux-hardware.org/?probe=01008b3cfd) | Sep 13, 2021 |
| Apple         | MacBookAir7,1               | [cd3844f542](https://linux-hardware.org/?probe=cd3844f542) | Sep 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [eb55a1f000](https://linux-hardware.org/?probe=eb55a1f000) | Sep 13, 2021 |
| HP            | Notebook                    | [17f4133e28](https://linux-hardware.org/?probe=17f4133e28) | Sep 13, 2021 |
| Lenovo        | G50-45 80E3                 | [51cf32f87c](https://linux-hardware.org/?probe=51cf32f87c) | Sep 12, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| ASUSTek       | M3N                         | [28a5b48a05](https://linux-hardware.org/?probe=28a5b48a05) | Sep 12, 2021 |
| ASUSTek       | M3N                         | [04307947ae](https://linux-hardware.org/?probe=04307947ae) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Apple         | MacBookAir7,1               | [795f6bba58](https://linux-hardware.org/?probe=795f6bba58) | Sep 10, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b95c1b013e](https://linux-hardware.org/?probe=b95c1b013e) | Sep 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2377281799](https://linux-hardware.org/?probe=2377281799) | Sep 09, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| ASUSTek       | X540NA                      | [f14257cc20](https://linux-hardware.org/?probe=f14257cc20) | Sep 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8433dfbbb9](https://linux-hardware.org/?probe=8433dfbbb9) | Sep 09, 2021 |
| Apple         | MacBookPro10,1              | [1ff67401db](https://linux-hardware.org/?probe=1ff67401db) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Apple         | MacBookAir7,2               | [5c6f3696b2](https://linux-hardware.org/?probe=5c6f3696b2) | Sep 08, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d21daec9ea](https://linux-hardware.org/?probe=d21daec9ea) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 2325B12       | [a55f42da78](https://linux-hardware.org/?probe=a55f42da78) | Sep 08, 2021 |
| ASUSTek       | K52F                        | [b1f04036d8](https://linux-hardware.org/?probe=b1f04036d8) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | [19cfc85441](https://linux-hardware.org/?probe=19cfc85441) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| ASUSTek       | K52F                        | [0d72cf73ac](https://linux-hardware.org/?probe=0d72cf73ac) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | [498dd20152](https://linux-hardware.org/?probe=498dd20152) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6fc35e97d8](https://linux-hardware.org/?probe=6fc35e97d8) | Sep 07, 2021 |
| Dell          | Latitude 7480               | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [7f6c0d6337](https://linux-hardware.org/?probe=7f6c0d6337) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [e6ea97df06](https://linux-hardware.org/?probe=e6ea97df06) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [3aedb68952](https://linux-hardware.org/?probe=3aedb68952) | Sep 06, 2021 |
| Samsung       | NC10                        | [98ba59d155](https://linux-hardware.org/?probe=98ba59d155) | Sep 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e42726b566](https://linux-hardware.org/?probe=e42726b566) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Toshiba       | Satellite C55-B             | [fe8833475a](https://linux-hardware.org/?probe=fe8833475a) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | [0a1850f760](https://linux-hardware.org/?probe=0a1850f760) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | [4ba7363e9e](https://linux-hardware.org/?probe=4ba7363e9e) | Sep 05, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18fe596fba](https://linux-hardware.org/?probe=18fe596fba) | Sep 04, 2021 |
| HP            | Presario CQ62               | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9e235c4228](https://linux-hardware.org/?probe=9e235c4228) | Sep 04, 2021 |
| Dell          | Inspiron 1525               | [0e32e6945b](https://linux-hardware.org/?probe=0e32e6945b) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | [db35296aa1](https://linux-hardware.org/?probe=db35296aa1) | Sep 03, 2021 |
| Acer          | Aspire A315-23              | [fafd031d1f](https://linux-hardware.org/?probe=fafd031d1f) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | [1449c0a9cd](https://linux-hardware.org/?probe=1449c0a9cd) | Sep 02, 2021 |
| ASUSTek       | UX303LNB                    | [e0756d7ae6](https://linux-hardware.org/?probe=e0756d7ae6) | Sep 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5d183d4587](https://linux-hardware.org/?probe=5d183d4587) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [666c4fef08](https://linux-hardware.org/?probe=666c4fef08) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d6ee033eb7](https://linux-hardware.org/?probe=d6ee033eb7) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | [28fbb3d82d](https://linux-hardware.org/?probe=28fbb3d82d) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | [27c2ebc917](https://linux-hardware.org/?probe=27c2ebc917) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | [1d9e3a7503](https://linux-hardware.org/?probe=1d9e3a7503) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | [97c9e2dc1f](https://linux-hardware.org/?probe=97c9e2dc1f) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | [f1cad98694](https://linux-hardware.org/?probe=f1cad98694) | Sep 01, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [d542a6b8f9](https://linux-hardware.org/?probe=d542a6b8f9) | Sep 01, 2021 |
| Acer          | Aspire A315-23              | [12a5a0f9c5](https://linux-hardware.org/?probe=12a5a0f9c5) | Sep 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3267eec643](https://linux-hardware.org/?probe=3267eec643) | Sep 01, 2021 |
| Timi          | TM1613                      | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | [bc224fb15f](https://linux-hardware.org/?probe=bc224fb15f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9510c18df6](https://linux-hardware.org/?probe=9510c18df6) | Aug 31, 2021 |
| Acer          | Swift SF314-41              | [783955d696](https://linux-hardware.org/?probe=783955d696) | Aug 31, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | [db94fcaf10](https://linux-hardware.org/?probe=db94fcaf10) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | [baf38e8736](https://linux-hardware.org/?probe=baf38e8736) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Fujitsu Si... | LIFEBOOK S6420              | [b26e82328a](https://linux-hardware.org/?probe=b26e82328a) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | [70835c3aa7](https://linux-hardware.org/?probe=70835c3aa7) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | [3e22f55c7b](https://linux-hardware.org/?probe=3e22f55c7b) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | [b73b366bb6](https://linux-hardware.org/?probe=b73b366bb6) | Aug 30, 2021 |
| Toshiba       | Satellite C55-B             | [e1b2dc4810](https://linux-hardware.org/?probe=e1b2dc4810) | Aug 30, 2021 |
| Apple         | MacBookAir7,1               | [e94ab065a3](https://linux-hardware.org/?probe=e94ab065a3) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | [b1425fa900](https://linux-hardware.org/?probe=b1425fa900) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | [b5a84f215b](https://linux-hardware.org/?probe=b5a84f215b) | Aug 30, 2021 |
| Dell          | Latitude E6330              | [95d65375e2](https://linux-hardware.org/?probe=95d65375e2) | Aug 30, 2021 |
| Lenovo        | ThinkPad T61 7661BF3        | [69b6d76471](https://linux-hardware.org/?probe=69b6d76471) | Aug 30, 2021 |
| ASUSTek       | K56CB                       | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [6fcfbde79d](https://linux-hardware.org/?probe=6fcfbde79d) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [17ae4593ea](https://linux-hardware.org/?probe=17ae4593ea) | Aug 28, 2021 |
| HP            | EliteBook 840 G3            | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| Apple         | MacBookAir7,2               | [d215521170](https://linux-hardware.org/?probe=d215521170) | Aug 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [2c85ec0205](https://linux-hardware.org/?probe=2c85ec0205) | Aug 27, 2021 |
| Lenovo        | ThinkPad T440p 20AN006GU... | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| HP            | ProBook 4530s               | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| Acer          | Swift SF314-41              | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| HP            | EliteBook 840 G4            | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| Dell          | Latitude E7470              | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| Dell          | Precision 7520              | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Timi          | TM1612                      | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| SLIMBOOK      | TITAN                       | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| Google        | Enguarde                    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| Google        | Enguarde                    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [451fe761a6](https://linux-hardware.org/?probe=451fe761a6) | Aug 18, 2021 |
| Google        | Enguarde                    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [1f8c3f9487](https://linux-hardware.org/?probe=1f8c3f9487) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [9f6a737d07](https://linux-hardware.org/?probe=9f6a737d07) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [4eb4afec6b](https://linux-hardware.org/?probe=4eb4afec6b) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [5949002919](https://linux-hardware.org/?probe=5949002919) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b0d4ba09f6](https://linux-hardware.org/?probe=b0d4ba09f6) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [12377bdf65](https://linux-hardware.org/?probe=12377bdf65) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f345284082](https://linux-hardware.org/?probe=f345284082) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6229638b59](https://linux-hardware.org/?probe=6229638b59) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b95e1787ff](https://linux-hardware.org/?probe=b95e1787ff) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f1d344625b](https://linux-hardware.org/?probe=f1d344625b) | Aug 17, 2021 |
| Google        | Enguarde                    | [4d7eaa38ba](https://linux-hardware.org/?probe=4d7eaa38ba) | Aug 17, 2021 |
| Google        | Enguarde                    | [8be28c3080](https://linux-hardware.org/?probe=8be28c3080) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| Google        | Enguarde                    | [cfdf77fbd9](https://linux-hardware.org/?probe=cfdf77fbd9) | Aug 17, 2021 |
| Google        | Enguarde                    | [6e84dfb541](https://linux-hardware.org/?probe=6e84dfb541) | Aug 17, 2021 |
| Google        | Enguarde                    | [2549683d9f](https://linux-hardware.org/?probe=2549683d9f) | Aug 17, 2021 |
| Dell          | Latitude 7410               | [f7f6e5a4d5](https://linux-hardware.org/?probe=f7f6e5a4d5) | Aug 17, 2021 |
| ASUSTek       | 1225B                       | [1dd6877b22](https://linux-hardware.org/?probe=1dd6877b22) | Aug 17, 2021 |
| Google        | Enguarde                    | [0bdebdb178](https://linux-hardware.org/?probe=0bdebdb178) | Aug 16, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3a489f9498](https://linux-hardware.org/?probe=3a489f9498) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [635d3ab3e5](https://linux-hardware.org/?probe=635d3ab3e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2e04ae93d1](https://linux-hardware.org/?probe=2e04ae93d1) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dffcb4d4f6](https://linux-hardware.org/?probe=dffcb4d4f6) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [e3816a3d3a](https://linux-hardware.org/?probe=e3816a3d3a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d76cf98938](https://linux-hardware.org/?probe=d76cf98938) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [fc7b752ce3](https://linux-hardware.org/?probe=fc7b752ce3) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [346d3ca919](https://linux-hardware.org/?probe=346d3ca919) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [eb7cdde4b5](https://linux-hardware.org/?probe=eb7cdde4b5) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ae1b239645](https://linux-hardware.org/?probe=ae1b239645) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d7e9112089](https://linux-hardware.org/?probe=d7e9112089) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [35ab4c3075](https://linux-hardware.org/?probe=35ab4c3075) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [40796d62c2](https://linux-hardware.org/?probe=40796d62c2) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [1fa30fb77a](https://linux-hardware.org/?probe=1fa30fb77a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [81f2a65461](https://linux-hardware.org/?probe=81f2a65461) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [a54d2e496c](https://linux-hardware.org/?probe=a54d2e496c) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d0581c16e9](https://linux-hardware.org/?probe=d0581c16e9) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4704dd7dc2](https://linux-hardware.org/?probe=4704dd7dc2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2d48e28c72](https://linux-hardware.org/?probe=2d48e28c72) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dcded26792](https://linux-hardware.org/?probe=dcded26792) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [de06f0cb03](https://linux-hardware.org/?probe=de06f0cb03) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3171a06ab2](https://linux-hardware.org/?probe=3171a06ab2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [154d3f4aac](https://linux-hardware.org/?probe=154d3f4aac) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 20J10046US      | [6943b835e5](https://linux-hardware.org/?probe=6943b835e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [56e2f75dab](https://linux-hardware.org/?probe=56e2f75dab) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e070c3cee](https://linux-hardware.org/?probe=7e070c3cee) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [be42bbb09a](https://linux-hardware.org/?probe=be42bbb09a) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [42a5d4fb48](https://linux-hardware.org/?probe=42a5d4fb48) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [845219864e](https://linux-hardware.org/?probe=845219864e) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [99531c5564](https://linux-hardware.org/?probe=99531c5564) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [7e2e8d1364](https://linux-hardware.org/?probe=7e2e8d1364) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [c9b0773c42](https://linux-hardware.org/?probe=c9b0773c42) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [947e3524e3](https://linux-hardware.org/?probe=947e3524e3) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [a30c87c3fe](https://linux-hardware.org/?probe=a30c87c3fe) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [edaac7af9f](https://linux-hardware.org/?probe=edaac7af9f) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [94047a5fdc](https://linux-hardware.org/?probe=94047a5fdc) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [ccd9ef4a72](https://linux-hardware.org/?probe=ccd9ef4a72) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [97aab17694](https://linux-hardware.org/?probe=97aab17694) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3112135337](https://linux-hardware.org/?probe=3112135337) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [8da303b571](https://linux-hardware.org/?probe=8da303b571) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [449ea4adf6](https://linux-hardware.org/?probe=449ea4adf6) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [5bd9662328](https://linux-hardware.org/?probe=5bd9662328) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [079ef9affe](https://linux-hardware.org/?probe=079ef9affe) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [9e81b88eb8](https://linux-hardware.org/?probe=9e81b88eb8) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7b614dd679](https://linux-hardware.org/?probe=7b614dd679) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| Dell          | G3 3590                     | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 630                         | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [e3fd79d228](https://linux-hardware.org/?probe=e3fd79d228) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [daf1b7a963](https://linux-hardware.org/?probe=daf1b7a963) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [0b7f4b2da5](https://linux-hardware.org/?probe=0b7f4b2da5) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [f6b6388040](https://linux-hardware.org/?probe=f6b6388040) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Google        | Enguarde                    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| Google        | Enguarde                    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Dell          | G7 7790                     | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Samsung       | 300E5M/300E5L               | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Apple         | MacBookAir7,1               | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Google        | Parrot                      | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Dell          | Latitude E7240              | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | Presario R4100 (PN495AV)    | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [a3914442ca](https://linux-hardware.org/?probe=a3914442ca) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| Google        | Stout                       | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | [acff56e8e3](https://linux-hardware.org/?probe=acff56e8e3) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | [704ead0e75](https://linux-hardware.org/?probe=704ead0e75) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| Casper        | C17B                        | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Intel         | W7645                       | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d7722f9bbf](https://linux-hardware.org/?probe=d7722f9bbf) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3eceba473e](https://linux-hardware.org/?probe=3eceba473e) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [85da1219ad](https://linux-hardware.org/?probe=85da1219ad) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | [bccfe7e145](https://linux-hardware.org/?probe=bccfe7e145) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | [73a418aad6](https://linux-hardware.org/?probe=73a418aad6) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Acer          | Aspire E5-573               | [d946214a58](https://linux-hardware.org/?probe=d946214a58) | Jul 06, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| ASUSTek       | K42Jv                       | [88ee690bb2](https://linux-hardware.org/?probe=88ee690bb2) | Jun 30, 2021 |
| Sony          | SVE1512G1RB                 | [41dd93f0c7](https://linux-hardware.org/?probe=41dd93f0c7) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| HP            | ProBook 455 G1              | [c334d50b1f](https://linux-hardware.org/?probe=c334d50b1f) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Acer          | Aspire A315-23              | [0de49e4ceb](https://linux-hardware.org/?probe=0de49e4ceb) | Jun 11, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [95fe5984c2](https://linux-hardware.org/?probe=95fe5984c2) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [b992eee8b5](https://linux-hardware.org/?probe=b992eee8b5) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d71fba3e59](https://linux-hardware.org/?probe=d71fba3e59) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Acer          | Aspire A315-23              | [31547cbbcf](https://linux-hardware.org/?probe=31547cbbcf) | May 31, 2021 |
| Acer          | Aspire A315-23              | [4392e54288](https://linux-hardware.org/?probe=4392e54288) | May 31, 2021 |
| Acer          | Aspire A315-23              | [2fda3b392d](https://linux-hardware.org/?probe=2fda3b392d) | May 31, 2021 |
| Acer          | Aspire A315-23              | [41c4d75b72](https://linux-hardware.org/?probe=41c4d75b72) | May 31, 2021 |
| Acer          | Aspire A315-23              | [8b834e3fc0](https://linux-hardware.org/?probe=8b834e3fc0) | May 31, 2021 |
| Acer          | Aspire A315-23              | [8932eef460](https://linux-hardware.org/?probe=8932eef460) | May 31, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Lenovo        | Z710 20250                  | [76d72eb45f](https://linux-hardware.org/?probe=76d72eb45f) | May 27, 2021 |
| Aquarius      | NS585                       | [e2035017ff](https://linux-hardware.org/?probe=e2035017ff) | May 26, 2021 |
| Aquarius      | NS585                       | [d2b5b53798](https://linux-hardware.org/?probe=d2b5b53798) | May 26, 2021 |
| Aquarius      | NS585                       | [1c84a98f48](https://linux-hardware.org/?probe=1c84a98f48) | May 26, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23              | [834e2e7b7e](https://linux-hardware.org/?probe=834e2e7b7e) | May 24, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Acer          | Aspire A315-23              | [71c9c1e86f](https://linux-hardware.org/?probe=71c9c1e86f) | May 21, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| ASUSTek       | T100TAS                     | [0b8e360f8a](https://linux-hardware.org/?probe=0b8e360f8a) | May 07, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| MSI           | Bravo 15 A4DDR              | [372d11517d](https://linux-hardware.org/?probe=372d11517d) | Apr 28, 2021 |
| Lenovo        | G550 20023                  | [69b57eec89](https://linux-hardware.org/?probe=69b57eec89) | Apr 27, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Acer          | Aspire 5560                 | [853337664f](https://linux-hardware.org/?probe=853337664f) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Dell          | Latitude E6330              | [d2a06d1cde](https://linux-hardware.org/?probe=d2a06d1cde) | Apr 22, 2021 |
| MSI           | Bravo 15 A4DDR              | [60eb0d02a7](https://linux-hardware.org/?probe=60eb0d02a7) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 3442               | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [92866f8994](https://linux-hardware.org/?probe=92866f8994) | Apr 17, 2021 |
| HP            | Pavilion g6                 | [7a88de99e8](https://linux-hardware.org/?probe=7a88de99e8) | Apr 16, 2021 |
| HP            | Pavilion g6                 | [8f9f4e211d](https://linux-hardware.org/?probe=8f9f4e211d) | Apr 15, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| HP            | Pavilion g6                 | [d3e2f03de0](https://linux-hardware.org/?probe=d3e2f03de0) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| HP            | Pavilion 17                 | [9bd4ef879a](https://linux-hardware.org/?probe=9bd4ef879a) | Apr 12, 2021 |
| Sony          | VPCEJ3S1R                   | [a57c607409](https://linux-hardware.org/?probe=a57c607409) | Apr 12, 2021 |
| Dell          | Inspiron 5721               | [d90f3a34d1](https://linux-hardware.org/?probe=d90f3a34d1) | Apr 08, 2021 |
| Dell          | Inspiron 5721               | [a0bb6867cd](https://linux-hardware.org/?probe=a0bb6867cd) | Apr 07, 2021 |
| Dell          | Latitude E6330              | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Notebook      | N650DU                      | [34efc4fdfe](https://linux-hardware.org/?probe=34efc4fdfe) | Apr 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 20HRC... | [354cd6e94e](https://linux-hardware.org/?probe=354cd6e94e) | Apr 02, 2021 |
| Acer          | TravelMate P259-MG          | [9acbd94cd7](https://linux-hardware.org/?probe=9acbd94cd7) | Apr 01, 2021 |
| Dell          | Inspiron 5721               | [b93f919e23](https://linux-hardware.org/?probe=b93f919e23) | Mar 31, 2021 |
| Dell          | Inspiron 5721               | [2e925f1ee2](https://linux-hardware.org/?probe=2e925f1ee2) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Dell          | Inspiron 5721               | [d22bc80177](https://linux-hardware.org/?probe=d22bc80177) | Mar 29, 2021 |
| Micro Elec... | MG-VCTR002-2060             | [3724755eea](https://linux-hardware.org/?probe=3724755eea) | Mar 28, 2021 |
| HP            | ProBook 4520s               | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| Lenovo        | B50-30 20382                | [2d50a5e736](https://linux-hardware.org/?probe=2d50a5e736) | Mar 21, 2021 |
| Dell          | Inspiron 5548               | [f20eacbf5c](https://linux-hardware.org/?probe=f20eacbf5c) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | [e3d85d4006](https://linux-hardware.org/?probe=e3d85d4006) | Mar 15, 2021 |
| Dell          | Inspiron 5548               | [3c8f0ff2d4](https://linux-hardware.org/?probe=3c8f0ff2d4) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| Acer          | Aspire E5-521               | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| ASUSTek       | K53E                        | [f84c0f2b1b](https://linux-hardware.org/?probe=f84c0f2b1b) | Mar 05, 2021 |
| Micro Elec... | MG-VCTR002-2060             | [f86910b3b3](https://linux-hardware.org/?probe=f86910b3b3) | Mar 05, 2021 |
| ASUSTek       | K53E                        | [8a98e99c2f](https://linux-hardware.org/?probe=8a98e99c2f) | Mar 05, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [db2b8a39be](https://linux-hardware.org/?probe=db2b8a39be) | Mar 03, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Dell          | XPS 13 9310                 | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| HP            | Pavilion Notebook           | [88c5aee182](https://linux-hardware.org/?probe=88c5aee182) | Mar 02, 2021 |
| Lenovo        | V570 HuronRiver Platform    | [d93b0955fa](https://linux-hardware.org/?probe=d93b0955fa) | Feb 27, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [744852fa69](https://linux-hardware.org/?probe=744852fa69) | Feb 25, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [720734ca06](https://linux-hardware.org/?probe=720734ca06) | Feb 25, 2021 |
| Dell          | Inspiron 5759               | [3710e0320f](https://linux-hardware.org/?probe=3710e0320f) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | [3bb9f3d0f3](https://linux-hardware.org/?probe=3bb9f3d0f3) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| HP            | ENVY Notebook               | [e4cc508565](https://linux-hardware.org/?probe=e4cc508565) | Feb 21, 2021 |
| Lenovo        | B50-30 20382                | [6642872403](https://linux-hardware.org/?probe=6642872403) | Feb 19, 2021 |
| LG Electro... | A410-K.BE43P1               | [da5067a065](https://linux-hardware.org/?probe=da5067a065) | Feb 18, 2021 |
| Dell          | Latitude E6440              | [ce086f8df0](https://linux-hardware.org/?probe=ce086f8df0) | Feb 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [77da992403](https://linux-hardware.org/?probe=77da992403) | Feb 14, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [2e19efe5b1](https://linux-hardware.org/?probe=2e19efe5b1) | Feb 12, 2021 |
| Dell          | Inspiron 5759               | [e7c528c9be](https://linux-hardware.org/?probe=e7c528c9be) | Feb 11, 2021 |
| Dell          | XPS 13 9310                 | [97e14d7021](https://linux-hardware.org/?probe=97e14d7021) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [954514a52a](https://linux-hardware.org/?probe=954514a52a) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [67f2a70d2a](https://linux-hardware.org/?probe=67f2a70d2a) | Feb 09, 2021 |
| Dell          | Inspiron 5759               | [cd72d5cd68](https://linux-hardware.org/?probe=cd72d5cd68) | Feb 09, 2021 |
| Dell          | Latitude 7400               | [32c7787bcb](https://linux-hardware.org/?probe=32c7787bcb) | Feb 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9b82b49d40](https://linux-hardware.org/?probe=9b82b49d40) | Feb 04, 2021 |
| Unknown       | Unknown                     | [6acba7c545](https://linux-hardware.org/?probe=6acba7c545) | Feb 03, 2021 |
| Unknown       | Unknown                     | [ad10dd6be0](https://linux-hardware.org/?probe=ad10dd6be0) | Feb 03, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [67cfeeb58a](https://linux-hardware.org/?probe=67cfeeb58a) | Jan 31, 2021 |
| Unknown       | Unknown                     | [ea0d120a2b](https://linux-hardware.org/?probe=ea0d120a2b) | Jan 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [288a08d946](https://linux-hardware.org/?probe=288a08d946) | Jan 26, 2021 |
| Positivo      | C14CR21                     | [0807ce46f1](https://linux-hardware.org/?probe=0807ce46f1) | Jan 19, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4bdbb16f3d](https://linux-hardware.org/?probe=4bdbb16f3d) | Jan 17, 2021 |
| Acer          | Aspire 5750Z                | [14ca9bb504](https://linux-hardware.org/?probe=14ca9bb504) | Jan 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [286214a4e2](https://linux-hardware.org/?probe=286214a4e2) | Jan 15, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1ec8c1ccd1](https://linux-hardware.org/?probe=1ec8c1ccd1) | Jan 13, 2021 |
| Dell          | Vostro 5490                 | [6afcc11fef](https://linux-hardware.org/?probe=6afcc11fef) | Jan 08, 2021 |
| Dell          | Vostro 5490                 | [1708c28c7b](https://linux-hardware.org/?probe=1708c28c7b) | Jan 08, 2021 |
| Dell          | Latitude E6330              | [1d09a49510](https://linux-hardware.org/?probe=1d09a49510) | Jan 04, 2021 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Inspiron 11-3168            | [3831423c95](https://linux-hardware.org/?probe=3831423c95) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | [4343600da2](https://linux-hardware.org/?probe=4343600da2) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | [a1f5874ef6](https://linux-hardware.org/?probe=a1f5874ef6) | Jun 30, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 578       | 45.3%   |
| 5.10.0-9-amd64             | 167       | 13.09%  |
| 5.10.0-7-amd64             | 118       | 9.25%   |
| 5.10.0-10-amd64            | 90        | 7.05%   |
| 5.10.0-11-amd64            | 76        | 5.96%   |
| 5.10.0-2-amd64             | 29        | 2.27%   |
| 5.10.0-6-amd64             | 28        | 2.19%   |
| 5.14.0-0.bpo.2-amd64       | 15        | 1.18%   |
| 5.10.0-3-amd64             | 12        | 0.94%   |
| 5.15.0-2-amd64             | 11        | 0.86%   |
| 5.10.0-9-686-pae           | 9         | 0.71%   |
| 5.10.0-8-686-pae           | 9         | 0.71%   |
| 5.15.0-0.bpo.2-amd64       | 8         | 0.63%   |
| 5.10.0-9-686               | 7         | 0.55%   |
| 5.10.0-5-amd64             | 6         | 0.47%   |
| 5.10.0-4-amd64             | 5         | 0.39%   |
| 5.10.0-1-amd64             | 5         | 0.39%   |
| 5.15.0-3-amd64             | 4         | 0.31%   |
| 5.15.0-1-amd64             | 4         | 0.31%   |
| 5.10.0-8-686               | 4         | 0.31%   |
| 5.10.0-10-686-pae          | 4         | 0.31%   |
| 5.16.0-1-amd64             | 3         | 0.24%   |
| 5.15.0-0.bpo.3-amd64       | 3         | 0.24%   |
| 5.12.0-19.3-liquorix-amd64 | 3         | 0.24%   |
| 5.10.0-11-686-pae          | 3         | 0.24%   |
| 5.10.0-11-686              | 2         | 0.16%   |
| 4.19.0-6-amd64             | 2         | 0.16%   |
| 4.19.0-14-amd64            | 2         | 0.16%   |
| 5.16.5-titanide            | 1         | 0.08%   |
| 5.16.0-rc6-amd64           | 1         | 0.08%   |
| 5.16.0-5.1-liquorix-amd64  | 1         | 0.08%   |
| 5.15.8-edge                | 1         | 0.08%   |
| 5.15.7-xanmod1             | 1         | 0.08%   |
| 5.15.3-edge                | 1         | 0.08%   |
| 5.15.17-xanmod2-tt         | 1         | 0.08%   |
| 5.15.13titanide-1          | 1         | 0.08%   |
| 5.15.11-bully-1.0          | 1         | 0.08%   |
| 5.15.0-2mx-amd64           | 1         | 0.08%   |
| 5.15.0-13.1-liquorix-amd64 | 1         | 0.08%   |
| 5.14.9-xanmod1-cacule      | 1         | 0.08%   |
| 5.14.7-ct                  | 1         | 0.08%   |
| 5.14.6-ndmnet-sid-1        | 1         | 0.08%   |
| 5.14.21                    | 1         | 0.08%   |
| 5.14.12.1-sleek-amd64      | 1         | 0.08%   |
| 5.14.0-rc3-prygun          | 1         | 0.08%   |
| 5.14.0-4-amd64             | 1         | 0.08%   |
| 5.14.0-3-amd64             | 1         | 0.08%   |
| 5.14.0-2mx-amd64           | 1         | 0.08%   |
| 5.14.0-2-amd64             | 1         | 0.08%   |
| 5.14.0-16.4-liquorix-amd64 | 1         | 0.08%   |
| 5.14.0-14.1-liquorix-amd64 | 1         | 0.08%   |
| 5.14.0-0.bpo.2-686-pae     | 1         | 0.08%   |
| 5.14.0+                    | 1         | 0.08%   |
| 5.13.8-xanmod1             | 1         | 0.08%   |
| 5.13.8                     | 1         | 0.08%   |
| 5.13.5-xanmod1             | 1         | 0.08%   |
| 5.13.4-e5520               | 1         | 0.08%   |
| 5.13.3                     | 1         | 0.08%   |
| 5.13.19-4-pve              | 1         | 0.08%   |
| 5.13.19-3-pve              | 1         | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version   | Notebooks | Percent |
|-----------|-----------|---------|
| 5.10.0    | 1109      | 90.83%  |
| 5.15.0    | 32        | 2.62%   |
| 5.14.0    | 23        | 1.88%   |
| 4.19.0    | 7         | 0.57%   |
| 5.16.0    | 5         | 0.41%   |
| 5.12.0    | 4         | 0.33%   |
| 5.13.19   | 3         | 0.25%   |
| 5.13.8    | 2         | 0.16%   |
| 5.11.0    | 2         | 0.16%   |
| 5.16.5    | 1         | 0.08%   |
| 5.15.8    | 1         | 0.08%   |
| 5.15.7    | 1         | 0.08%   |
| 5.15.3    | 1         | 0.08%   |
| 5.15.17   | 1         | 0.08%   |
| 5.15.13   | 1         | 0.08%   |
| 5.15.11   | 1         | 0.08%   |
| 5.14.9    | 1         | 0.08%   |
| 5.14.7    | 1         | 0.08%   |
| 5.14.6    | 1         | 0.08%   |
| 5.14.21   | 1         | 0.08%   |
| 5.14.12.1 | 1         | 0.08%   |
| 5.13.5    | 1         | 0.08%   |
| 5.13.4    | 1         | 0.08%   |
| 5.13.3    | 1         | 0.08%   |
| 5.13.15   | 1         | 0.08%   |
| 5.13.0    | 1         | 0.08%   |
| 5.12.14   | 1         | 0.08%   |
| 5.12.10   | 1         | 0.08%   |
| 5.12.1    | 1         | 0.08%   |
| 5.11.9    | 1         | 0.08%   |
| 5.11.22   | 1         | 0.08%   |
| 5.11.15   | 1         | 0.08%   |
| 5.11.14   | 1         | 0.08%   |
| 5.10.78   | 1         | 0.08%   |
| 5.10.40   | 1         | 0.08%   |
| 5.10.18   | 1         | 0.08%   |
| 5.10.10   | 1         | 0.08%   |
| 5.1.12    | 1         | 0.08%   |
| 5.1.0     | 1         | 0.08%   |
| 4.9.0     | 1         | 0.08%   |
| 4.19.202  | 1         | 0.08%   |
| 4.19.181  | 1         | 0.08%   |
| 3.10.54   | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 1113      | 91.3%   |
| 5.15    | 37        | 3.04%   |
| 5.14    | 27        | 2.21%   |
| 5.13    | 9         | 0.74%   |
| 4.19    | 9         | 0.74%   |
| 5.12    | 7         | 0.57%   |
| 5.16    | 6         | 0.49%   |
| 5.11    | 6         | 0.49%   |
| 5.1     | 2         | 0.16%   |
| 5.14.12 | 1         | 0.08%   |
| 4.9     | 1         | 0.08%   |
| 3.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1157      | 96.5%   |
| i686   | 41        | 3.42%   |
| armv7l | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 380       | 31.2%   |
| GNOME            | 315       | 25.86%  |
| KDE5             | 169       | 13.88%  |
| XFCE             | 120       | 9.85%   |
| MATE             | 46        | 3.78%   |
| LXDE             | 37        | 3.04%   |
| X-Cinnamon       | 30        | 2.46%   |
| Cinnamon         | 27        | 2.22%   |
| KDE              | 20        | 1.64%   |
| i3               | 17        | 1.4%    |
| LXQt             | 12        | 0.99%   |
| lightdm-xsession | 11        | 0.9%    |
| GNOME Flashback  | 9         | 0.74%   |
| Openbox          | 5         | 0.41%   |
| GNOME Classic    | 5         | 0.41%   |
| trinity          | 2         | 0.16%   |
| Enlightenment    | 2         | 0.16%   |
| DWM              | 2         | 0.16%   |
| awesome          | 2         | 0.16%   |
| wmaker-common    | 1         | 0.08%   |
| sway             | 1         | 0.08%   |
| ICEWM            | 1         | 0.08%   |
| default          | 1         | 0.08%   |
| Deepin           | 1         | 0.08%   |
| Cutefish         | 1         | 0.08%   |
| Budgie           | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 594       | 48.81%  |
| Unknown | 340       | 27.94%  |
| Wayland | 243       | 19.97%  |
| Tty     | 40        | 3.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 523       | 43.15%  |
| GDM     | 270       | 22.28%  |
| SDDM    | 172       | 14.19%  |
| LightDM | 159       | 13.12%  |
| TDM     | 70        | 5.78%   |
| GDM3    | 12        | 0.99%   |
| SLiM    | 3         | 0.25%   |
| XDM     | 2         | 0.17%   |
| KDM     | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 340       | 28.15%  |
| Unknown | 252       | 20.86%  |
| ru_RU   | 130       | 10.76%  |
| de_DE   | 70        | 5.79%   |
| fr_FR   | 55        | 4.55%   |
| en_GB   | 53        | 4.39%   |
| es_ES   | 39        | 3.23%   |
| pl_PL   | 36        | 2.98%   |
| pt_BR   | 31        | 2.57%   |
| it_IT   | 31        | 2.57%   |
| es_MX   | 13        | 1.08%   |
| en_CA   | 11        | 0.91%   |
| en_IN   | 9         | 0.75%   |
| zh_CN   | 8         | 0.66%   |
| en_AU   | 8         | 0.66%   |
| tr_TR   | 6         | 0.5%    |
| sv_SE   | 6         | 0.5%    |
| ja_JP   | 6         | 0.5%    |
| C       | 6         | 0.5%    |
| pt_PT   | 5         | 0.41%   |
| de_AT   | 5         | 0.41%   |
| uk_UA   | 4         | 0.33%   |
| nl_NL   | 4         | 0.33%   |
| hu_HU   | 4         | 0.33%   |
| fi_FI   | 4         | 0.33%   |
| es_CL   | 4         | 0.33%   |
| es_AR   | 4         | 0.33%   |
| en_IE   | 4         | 0.33%   |
| de_CH   | 4         | 0.33%   |
| cs_CZ   | 4         | 0.33%   |
| nn_NO   | 3         | 0.25%   |
| es_CO   | 3         | 0.25%   |
| en_ZA   | 3         | 0.25%   |
| en_SG   | 3         | 0.25%   |
| en_DK   | 3         | 0.25%   |
| bg_BG   | 3         | 0.25%   |
| zh_TW   | 2         | 0.17%   |
| ru_UA   | 2         | 0.17%   |
| et_EE   | 2         | 0.17%   |
| es_VE   | 2         | 0.17%   |
| es_EC   | 2         | 0.17%   |
| en_NZ   | 2         | 0.17%   |
| en_HK   | 2         | 0.17%   |
| sl_SI   | 1         | 0.08%   |
| sk_SK   | 1         | 0.08%   |
| ro_RO   | 1         | 0.08%   |
| nl_BE   | 1         | 0.08%   |
| nb_NO   | 1         | 0.08%   |
| hr_HR   | 1         | 0.08%   |
| gl_ES   | 1         | 0.08%   |
| fr_CH   | 1         | 0.08%   |
| fr_BE   | 1         | 0.08%   |
| es_UY   | 1         | 0.08%   |
| es_PE   | 1         | 0.08%   |
| es_GT   | 1         | 0.08%   |
| es_CR   | 1         | 0.08%   |
| es_BO   | 1         | 0.08%   |
| eo      | 1         | 0.08%   |
| en_ZM   | 1         | 0.08%   |
| en_SI   | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 768       | 63.63%  |
| BIOS | 439       | 36.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 778       | 64.78%  |
| Overlay | 363       | 30.22%  |
| Btrfs   | 38        | 3.16%   |
| Xfs     | 9         | 0.75%   |
| Zfs     | 5         | 0.42%   |
| Tmpfs   | 2         | 0.17%   |
| Ext2    | 2         | 0.17%   |
| Unknown | 2         | 0.17%   |
| Rootfs  | 1         | 0.08%   |
| Ext3    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 797       | 66.14%  |
| MBR     | 238       | 19.75%  |
| Unknown | 170       | 14.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1108      | 91.95%  |
| Yes       | 97        | 8.05%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 874       | 72.47%  |
| Yes       | 332       | 27.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 308       | 25.71%  |
| Hewlett-Packard      | 176       | 14.69%  |
| Apple                | 164       | 13.69%  |
| Dell                 | 140       | 11.69%  |
| ASUSTek Computer     | 95        | 7.93%   |
| Acer                 | 84        | 7.01%   |
| Google               | 51        | 4.26%   |
| MSI                  | 20        | 1.67%   |
| Aquarius             | 18        | 1.5%    |
| Toshiba              | 16        | 1.34%   |
| Samsung Electronics  | 16        | 1.34%   |
| Sony                 | 13        | 1.09%   |
| HUAWEI               | 10        | 0.83%   |
| Notebook             | 7         | 0.58%   |
| Fujitsu              | 6         | 0.5%    |
| Timi                 | 5         | 0.42%   |
| Unknown              | 5         | 0.42%   |
| Packard Bell         | 4         | 0.33%   |
| IBM                  | 4         | 0.33%   |
| Clevo                | 4         | 0.33%   |
| TUXEDO               | 3         | 0.25%   |
| Gigabyte Technology  | 3         | 0.25%   |
| SLIMBOOK             | 2         | 0.17%   |
| Positivo             | 2         | 0.17%   |
| PC Specialist        | 2         | 0.17%   |
| Panasonic            | 2         | 0.17%   |
| Medion               | 2         | 0.17%   |
| LG Electronics       | 2         | 0.17%   |
| Jumper               | 2         | 0.17%   |
| GPU Company          | 2         | 0.17%   |
| Fujitsu Siemens      | 2         | 0.17%   |
| Compal               | 2         | 0.17%   |
| AXDIA International  | 2         | 0.17%   |
| YJKC                 | 1         | 0.08%   |
| UNOWHY               | 1         | 0.08%   |
| TrekStor             | 1         | 0.08%   |
| Tablet               | 1         | 0.08%   |
| System76             | 1         | 0.08%   |
| Schenker             | 1         | 0.08%   |
| Quanta               | 1         | 0.08%   |
| Philco               | 1         | 0.08%   |
| Pegatron             | 1         | 0.08%   |
| Monster              | 1         | 0.08%   |
| Micro Electronics    | 1         | 0.08%   |
| Maibenben            | 1         | 0.08%   |
| Lex BayTrail         | 1         | 0.08%   |
| Intel Client Systems | 1         | 0.08%   |
| Intel                | 1         | 0.08%   |
| HONOR                | 1         | 0.08%   |
| Framework            | 1         | 0.08%   |
| eMachines            | 1         | 0.08%   |
| CSL-Computer         | 1         | 0.08%   |
| Chuwi                | 1         | 0.08%   |
| Celestica            | 1         | 0.08%   |
| Casper               | 1         | 0.08%   |
| Alienware            | 1         | 0.08%   |
| Advent               | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBookAir7,1                               | 75        | 6.26%   |
| Apple MacBookAir7,2                               | 68        | 5.68%   |
| Google Enguarde                                   | 47        | 3.92%   |
| Lenovo ThinkPad E475 20H40006US                   | 23        | 1.92%   |
| Aquarius NS585                                    | 18        | 1.5%    |
| Lenovo ThinkPad 13 2nd Gen 20J10046US             | 16        | 1.34%   |
| Acer Aspire A315-23                               | 15        | 1.25%   |
| HP Pavilion Gaming Laptop 15-ec1xxx               | 6         | 0.5%    |
| HP Laptop 15-db1xxx                               | 6         | 0.5%    |
| HP EliteBook 8460p                                | 6         | 0.5%    |
| Dell XPS 13 9310                                  | 6         | 0.5%    |
| HP Pavilion Gaming Laptop 15-ec2xxx               | 5         | 0.42%   |
| HP Pavilion g6                                    | 5         | 0.42%   |
| HP Laptop 15-db0xxx                               | 5         | 0.42%   |
| Dell Latitude 7480                                | 5         | 0.42%   |
| Unknown                                           | 5         | 0.42%   |
| Lenovo IdeaPad L340-15API 81LW                    | 4         | 0.33%   |
| HP Notebook                                       | 4         | 0.33%   |
| ASUS X555LD                                       | 4         | 0.33%   |
| Acer Aspire A515-56                               | 4         | 0.33%   |
| Samsung 300E4C/300E5C/300E7C                      | 3         | 0.25%   |
| Lenovo ThinkPad T490 20N2CTO1WW                   | 3         | 0.25%   |
| Lenovo ThinkBook 14 G2 ARE 20VF                   | 3         | 0.25%   |
| Lenovo B50-30 20382                               | 3         | 0.25%   |
| HUAWEI NBLK-WAX9X                                 | 3         | 0.25%   |
| HP ProBook 4530s                                  | 3         | 0.25%   |
| HP Compaq CQ58                                    | 3         | 0.25%   |
| HP 250 G7 Notebook PC                             | 3         | 0.25%   |
| Dell XPS 15 7590                                  | 3         | 0.25%   |
| Dell XPS 13 9370                                  | 3         | 0.25%   |
| Dell Vostro 5471                                  | 3         | 0.25%   |
| Dell Inspiron 5570                                | 3         | 0.25%   |
| ASUS ZenBook UX325EA_UX325EA                      | 3         | 0.25%   |
| TUXEDO Pulse 15 Gen1                              | 2         | 0.17%   |
| Timi TM1613                                       | 2         | 0.17%   |
| MSI Bravo 15 A4DDR                                | 2         | 0.17%   |
| Lenovo V510-15IKB 80WQ                            | 2         | 0.17%   |
| Lenovo V330-15IKB 81AX                            | 2         | 0.17%   |
| Lenovo ThinkPad T430 2349GCG                      | 2         | 0.17%   |
| Lenovo ThinkPad L15 Gen 1 20U7001VMH              | 2         | 0.17%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS               | 2         | 0.17%   |
| Lenovo IdeaPad S145-15API 81V7                    | 2         | 0.17%   |
| Lenovo IdeaPad 700-15ISK 80RU                     | 2         | 0.17%   |
| Lenovo IdeaPad 330-15IKB 81DE                     | 2         | 0.17%   |
| Lenovo IdeaPad 330-15ARR 81D2                     | 2         | 0.17%   |
| Lenovo IdeaPad 3 14ADA05 81W0                     | 2         | 0.17%   |
| Lenovo G580 20157                                 | 2         | 0.17%   |
| Lenovo G50-80 80E5                                | 2         | 0.17%   |
| Jumper EZbook                                     | 2         | 0.17%   |
| HUAWEI HVY-WXX9                                   | 2         | 0.17%   |
| HP ZBook Firefly 15 inch G8 Mobile Workstation PC | 2         | 0.17%   |
| HP ProBook 650 G5                                 | 2         | 0.17%   |
| HP ProBook 635 Aero G7 Notebook PC                | 2         | 0.17%   |
| HP Presario CQ56                                  | 2         | 0.17%   |
| HP Pavilion Notebook                              | 2         | 0.17%   |
| HP Pavilion dv6                                   | 2         | 0.17%   |
| HP Pavilion 17                                    | 2         | 0.17%   |
| HP Laptop 15s-fq2xxx                              | 2         | 0.17%   |
| HP Laptop 15s-eq2xxx                              | 2         | 0.17%   |
| HP Laptop 15-da0xxx                               | 2         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 215       | 17.95%  |
| Apple MacBookAir7     | 143       | 11.94%  |
| Acer Aspire           | 58        | 4.84%   |
| Dell Inspiron         | 50        | 4.17%   |
| Lenovo IdeaPad        | 48        | 4.01%   |
| Google Enguarde       | 47        | 3.92%   |
| Dell Latitude         | 36        | 3.01%   |
| HP Pavilion           | 33        | 2.75%   |
| HP Laptop             | 32        | 2.67%   |
| HP EliteBook          | 30        | 2.5%    |
| HP ProBook            | 25        | 2.09%   |
| Dell XPS              | 25        | 2.09%   |
| Aquarius NS585        | 18        | 1.5%    |
| Toshiba Satellite     | 14        | 1.17%   |
| ASUS ZenBook          | 14        | 1.17%   |
| Dell Vostro           | 12        | 1%      |
| HP Compaq             | 11        | 0.92%   |
| Dell Precision        | 11        | 0.92%   |
| HP ZBook              | 9         | 0.75%   |
| ASUS VivoBook         | 9         | 0.75%   |
| Acer TravelMate       | 9         | 0.75%   |
| HP 250                | 8         | 0.67%   |
| ASUS ASUS             | 7         | 0.58%   |
| Acer Swift            | 7         | 0.58%   |
| ASUS ROG              | 6         | 0.5%    |
| Lenovo ThinkBook      | 5         | 0.42%   |
| HP Presario           | 5         | 0.42%   |
| Fujitsu LIFEBOOK      | 5         | 0.42%   |
| Acer Nitro            | 5         | 0.42%   |
| Unknown               | 5         | 0.42%   |
| Packard Bell EasyNote | 4         | 0.33%   |
| HP Notebook           | 4         | 0.33%   |
| ASUS X555LD           | 4         | 0.33%   |
| ASUS TUF              | 4         | 0.33%   |
| Samsung 300E4C        | 3         | 0.25%   |
| Lenovo G580           | 3         | 0.25%   |
| Lenovo B50-30         | 3         | 0.25%   |
| IBM ThinkPad          | 3         | 0.25%   |
| HUAWEI NBLK-WAX9X     | 3         | 0.25%   |
| HP ENVY               | 3         | 0.25%   |
| Dell G3               | 3         | 0.25%   |
| Apple MacBookPro11    | 3         | 0.25%   |
| TUXEDO Pulse          | 2         | 0.17%   |
| Timi TM1613           | 2         | 0.17%   |
| Notebook W65          | 2         | 0.17%   |
| MSI GE70              | 2         | 0.17%   |
| MSI GE60              | 2         | 0.17%   |
| MSI Bravo             | 2         | 0.17%   |
| Lenovo V510-15IKB     | 2         | 0.17%   |
| Lenovo V330-15IKB     | 2         | 0.17%   |
| Lenovo Legion         | 2         | 0.17%   |
| Lenovo G50-80         | 2         | 0.17%   |
| Jumper EZbook         | 2         | 0.17%   |
| HUAWEI HVY-WXX9       | 2         | 0.17%   |
| HP OMEN               | 2         | 0.17%   |
| HP 15                 | 2         | 0.17%   |
| GPU Company GWTC116-2 | 2         | 0.17%   |
| Google Stout          | 2         | 0.17%   |
| Gigabyte AERO         | 2         | 0.17%   |
| ASUS UX303LAB         | 2         | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 188       | 15.69%  |
| 2020    | 156       | 13.02%  |
| 2019    | 133       | 11.1%   |
| 2021    | 125       | 10.43%  |
| 2012    | 82        | 6.84%   |
| 2018    | 77        | 6.43%   |
| 2017    | 77        | 6.43%   |
| 2011    | 71        | 5.93%   |
| 2015    | 55        | 4.59%   |
| 2013    | 52        | 4.34%   |
| 2014    | 50        | 4.17%   |
| 2010    | 44        | 3.67%   |
| 2008    | 28        | 2.34%   |
| 2009    | 27        | 2.25%   |
| 2007    | 14        | 1.17%   |
| 2005    | 10        | 0.83%   |
| 2006    | 5         | 0.42%   |
| 2004    | 2         | 0.17%   |
| 2002    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1198      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1081      | 89.93%  |
| Enabled  | 121       | 10.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1146      | 95.66%  |
| Yes  | 52        | 4.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 405       | 33.64%  |
| 3.01-4.0    | 278       | 23.09%  |
| 16.01-24.0  | 196       | 16.28%  |
| 8.01-16.0   | 160       | 13.29%  |
| 32.01-64.0  | 62        | 5.15%   |
| 1.01-2.0    | 42        | 3.49%   |
| 2.01-3.0    | 21        | 1.74%   |
| 24.01-32.0  | 13        | 1.08%   |
| 0.51-1.0    | 12        | 1%      |
| 64.01-256.0 | 11        | 0.91%   |
| 0.01-0.5    | 4         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 516       | 41.35%  |
| 2.01-3.0   | 234       | 18.75%  |
| 4.01-8.0   | 159       | 12.74%  |
| 0.51-1.0   | 153       | 12.26%  |
| 3.01-4.0   | 113       | 9.05%   |
| 8.01-16.0  | 38        | 3.04%   |
| 0.01-0.5   | 31        | 2.48%   |
| 32.01-64.0 | 2         | 0.16%   |
| 24.01-32.0 | 1         | 0.08%   |
| 16.01-24.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 965       | 80.02%  |
| 2      | 213       | 17.66%  |
| 3      | 17        | 1.41%   |
| 4      | 6         | 0.5%    |
| 0      | 4         | 0.33%   |
| 5      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 890       | 74.29%  |
| Yes       | 308       | 25.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 858       | 71.56%  |
| No        | 341       | 28.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1178      | 98.33%  |
| No        | 20        | 1.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 988       | 82.2%   |
| No        | 214       | 17.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 362       | 30.12%  |
| Russia             | 127       | 10.57%  |
| Germany            | 94        | 7.82%   |
| France             | 69        | 5.74%   |
| Spain              | 45        | 3.74%   |
| Poland             | 45        | 3.74%   |
| Brazil             | 40        | 3.33%   |
| UK                 | 32        | 2.66%   |
| Italy              | 30        | 2.5%    |
| Ukraine            | 21        | 1.75%   |
| Netherlands        | 21        | 1.75%   |
| Sweden             | 17        | 1.41%   |
| Mexico             | 17        | 1.41%   |
| Switzerland        | 16        | 1.33%   |
| Canada             | 16        | 1.33%   |
| China              | 14        | 1.16%   |
| Turkey             | 12        | 1%      |
| India              | 11        | 0.92%   |
| Czechia            | 11        | 0.92%   |
| Austria            | 10        | 0.83%   |
| Portugal           | 9         | 0.75%   |
| Argentina          | 9         | 0.75%   |
| Australia          | 8         | 0.67%   |
| Norway             | 7         | 0.58%   |
| Japan              | 7         | 0.58%   |
| Finland            | 7         | 0.58%   |
| Indonesia          | 6         | 0.5%    |
| Hungary            | 6         | 0.5%    |
| Greece             | 6         | 0.5%    |
| Croatia            | 6         | 0.5%    |
| Chile              | 6         | 0.5%    |
| Belgium            | 6         | 0.5%    |
| Belarus            | 6         | 0.5%    |
| Thailand           | 5         | 0.42%   |
| Romania            | 5         | 0.42%   |
| Colombia           | 5         | 0.42%   |
| Slovenia           | 4         | 0.33%   |
| Latvia             | 4         | 0.33%   |
| Kazakhstan         | 4         | 0.33%   |
| Ireland            | 4         | 0.33%   |
| Ecuador            | 4         | 0.33%   |
| Denmark            | 4         | 0.33%   |
| Bulgaria           | 4         | 0.33%   |
| South Africa       | 3         | 0.25%   |
| Slovakia           | 3         | 0.25%   |
| Singapore          | 3         | 0.25%   |
| Philippines        | 3         | 0.25%   |
| Morocco            | 3         | 0.25%   |
| Guatemala          | 3         | 0.25%   |
| Venezuela          | 2         | 0.17%   |
| Taiwan             | 2         | 0.17%   |
| New Zealand        | 2         | 0.17%   |
| Iceland            | 2         | 0.17%   |
| Estonia            | 2         | 0.17%   |
| Dominican Republic | 2         | 0.17%   |
| Cuba               | 2         | 0.17%   |
| Costa Rica         | 2         | 0.17%   |
| Bangladesh         | 2         | 0.17%   |
| Zambia             | 1         | 0.08%   |
| Vietnam            | 1         | 0.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Portland       | 178       | 14.15%  |
| Voronezh       | 75        | 5.96%   |
| Dover-Foxcroft | 49        | 3.9%    |
| Bangor         | 23        | 1.83%   |
| Warsaw         | 20        | 1.59%   |
| St Petersburg  | 20        | 1.59%   |
| Eliot          | 19        | 1.51%   |
| Paris          | 17        | 1.35%   |
| MÃ¡laga      | 14        | 1.11%   |
| Berlin         | 12        | 0.95%   |
| London         | 8         | 0.64%   |
| Prague         | 7         | 0.56%   |
| Moscow         | 7         | 0.56%   |
| Hampden        | 7         | 0.56%   |
| SÃ£o Paulo   | 6         | 0.48%   |
| Milan          | 6         | 0.48%   |
| Madrid         | 6         | 0.48%   |
| Lyon           | 6         | 0.48%   |
| Amsterdam      | 6         | 0.48%   |
| Zagreb         | 5         | 0.4%    |
| Vienna         | 5         | 0.4%    |
| Munich         | 5         | 0.4%    |
| Leimen         | 5         | 0.4%    |
| Bengaluru      | 5         | 0.4%    |
| Bangkok        | 5         | 0.4%    |
| Zurich         | 4         | 0.32%   |
| Toronto        | 4         | 0.32%   |
| Manchester     | 4         | 0.32%   |
| Istanbul       | 4         | 0.32%   |
| Helsinki       | 4         | 0.32%   |
| Hamburg        | 4         | 0.32%   |
| Grenoble       | 4         | 0.32%   |
| Athens         | 4         | 0.32%   |
| Ankara         | 4         | 0.32%   |
| Yekaterinburg  | 3         | 0.24%   |
| Turin          | 3         | 0.24%   |
| Thermopolis    | 3         | 0.24%   |
| Sunnyvale      | 3         | 0.24%   |
| Stockholm      | 3         | 0.24%   |
| Singapore      | 3         | 0.24%   |
| Sevastopol     | 3         | 0.24%   |
| Rio de Janeiro | 3         | 0.24%   |
| Riga           | 3         | 0.24%   |
| Poznan         | 3         | 0.24%   |
| Perm           | 3         | 0.24%   |
| Oslo           | 3         | 0.24%   |
| Mesa           | 3         | 0.24%   |
| Kyiv           | 3         | 0.24%   |
| Iasi           | 3         | 0.24%   |
| Halstead       | 3         | 0.24%   |
| Guatemala City | 3         | 0.24%   |
| Frankfort      | 3         | 0.24%   |
| Dublin         | 3         | 0.24%   |
| Zerkow         | 2         | 0.16%   |
| Yevpatoriya    | 2         | 0.16%   |
| Wroclaw        | 2         | 0.16%   |
| Valencia       | 2         | 0.16%   |
| Tyreso Strand  | 2         | 0.16%   |
| Tucson         | 2         | 0.16%   |
| Ternopil       | 2         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 216       | 260    | 15.2%   |
| WDC                       | 158       | 199    | 11.12%  |
| Apple                     | 152       | 177    | 10.7%   |
| Seagate                   | 114       | 133    | 8.02%   |
| Kingston                  | 96        | 107    | 6.76%   |
| Unknown                   | 95        | 123    | 6.69%   |
| Toshiba                   | 69        | 74     | 4.86%   |
| SK Hynix                  | 56        | 59     | 3.94%   |
| SanDisk                   | 56        | 66     | 3.94%   |
| Crucial                   | 56        | 66     | 3.94%   |
| Hitachi                   | 42        | 44     | 2.96%   |
| Intel                     | 37        | 38     | 2.6%    |
| A-DATA Technology         | 37        | 47     | 2.6%    |
| Micron Technology         | 31        | 31     | 2.18%   |
| HGST                      | 20        | 21     | 1.41%   |
| KIOXIA                    | 17        | 20     | 1.2%    |
| SABRENT                   | 16        | 17     | 1.13%   |
| Transcend                 | 10        | 10     | 0.7%    |
| Fujitsu                   | 10        | 11     | 0.7%    |
| China                     | 10        | 10     | 0.7%    |
| LITEON                    | 9         | 9      | 0.63%   |
| Silicon Motion            | 7         | 8      | 0.49%   |
| PNY                       | 6         | 6      | 0.42%   |
| Intenso                   | 5         | 6      | 0.35%   |
| Union Memory              | 4         | 4      | 0.28%   |
| Patriot                   | 4         | 4      | 0.28%   |
| Lexar                     | 4         | 5      | 0.28%   |
| Lenovo                    | 4         | 5      | 0.28%   |
| JMicron                   | 4         | 4      | 0.28%   |
| GOODRAM                   | 4         | 4      | 0.28%   |
| SSSTC                     | 3         | 3      | 0.21%   |
| Phison                    | 3         | 6      | 0.21%   |
| LITEONIT                  | 3         | 3      | 0.21%   |
| Corsair                   | 3         | 3      | 0.21%   |
| Apacer                    | 3         | 3      | 0.21%   |
| Unknown                   | 3         | 3      | 0.21%   |
| ZTC                       | 2         | 5      | 0.14%   |
| XPG                       | 2         | 2      | 0.14%   |
| UMIS                      | 2         | 2      | 0.14%   |
| Team                      | 2         | 2      | 0.14%   |
| SPCC                      | 2         | 2      | 0.14%   |
| Solid State Storage       | 2         | 2      | 0.14%   |
| PLEXTOR                   | 2         | 2      | 0.14%   |
| Netac                     | 2         | 2      | 0.14%   |
| Micron/Crucial Technology | 2         | 2      | 0.14%   |
| Mass                      | 2         | 2      | 0.14%   |
| JetFlash                  | 2         | 2      | 0.14%   |
| FORESEE                   | 2         | 2      | 0.14%   |
| BIWIN                     | 2         | 2      | 0.14%   |
| ASMT                      | 2         | 3      | 0.14%   |
| YMTC                      | 1         | 1      | 0.07%   |
| Vaseky                    | 1         | 2      | 0.07%   |
| USB3.0                    | 1         | 1      | 0.07%   |
| TrekStor                  | 1         | 1      | 0.07%   |
| Teclast                   | 1         | 1      | 0.07%   |
| SILICONMOTION             | 1         | 1      | 0.07%   |
| Realtek                   | 1         | 1      | 0.07%   |
| RDM-II                    | 1         | 1      | 0.07%   |
| RAVPOWER                  | 1         | 1      | 0.07%   |
| Phison Electronics        | 1         | 1      | 0.07%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Apple SSD AP0128H 121GB              | 75        | 5.15%   |
| Apple SSD SM0128G 121GB              | 67        | 4.6%    |
| Kingston SA400S37120G 120GB SSD      | 28        | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB       | 27        | 1.85%   |
| Unknown AGND3R  16GB                 | 25        | 1.72%   |
| Unknown HAG2e  16GB                  | 19        | 1.3%    |
| A-DATA SU800 512GB SSD               | 18        | 1.24%   |
| SABRENT Disk 1TB                     | 16        | 1.1%    |
| Kingston SA400S37240G 240GB SSD      | 13        | 0.89%   |
| Toshiba MQ01ABF050 500GB             | 12        | 0.82%   |
| Toshiba MQ04ABF100 1TB               | 10        | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 0.69%   |
| Samsung SSD 860 EVO 500GB            | 10        | 0.69%   |
| SanDisk SD8SN8U128G1001 128GB SSD    | 9         | 0.62%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD | 9         | 0.62%   |
| Kingston SV300S37A120G 120GB SSD     | 9         | 0.62%   |
| Crucial CT500MX500SSD1 500GB         | 9         | 0.62%   |
| Crucial CT1000MX500SSD1 1TB          | 8         | 0.55%   |
| SanDisk SSD PLUS 240GB               | 7         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB         | 7         | 0.48%   |
| Samsung SSD 870 EVO 500GB            | 7         | 0.48%   |
| Samsung SSD 860 EVO 250GB            | 7         | 0.48%   |
| Intel SSDPEKNW512G8H 512GB           | 7         | 0.48%   |
| Intel SSDPEKNW512G8 512GB            | 7         | 0.48%   |
| HGST HTS721010A9E630 1TB             | 7         | 0.48%   |
| WDC WD10SPZX-24Z10 1TB               | 6         | 0.41%   |
| Toshiba MQ01ABD100 1TB               | 6         | 0.41%   |
| Samsung SSD 970 EVO 1TB              | 6         | 0.41%   |
| Samsung SSD 850 EVO 250GB            | 6         | 0.41%   |
| Unknown MMC Card  32GB               | 5         | 0.34%   |
| Unknown MMC Card  128GB              | 5         | 0.34%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.34%   |
| Samsung SSD 860 EVO 1TB              | 5         | 0.34%   |
| Samsung SSD 850 EVO 500GB            | 5         | 0.34%   |
| Crucial CT120BX500SSD1 120GB         | 5         | 0.34%   |
| WDC WD10SPZX-60Z10T0 1TB             | 4         | 0.27%   |
| WDC WD10SPZX-21Z10T0 1TB             | 4         | 0.27%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 4         | 0.27%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 4         | 0.27%   |
| WDC PC SN530 NVMe 256GB              | 4         | 0.27%   |
| Unknown SD/MMC/MS PRO 64GB           | 4         | 0.27%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB | 4         | 0.27%   |
| SK Hynix HFM001TD3JX013N 1TB         | 4         | 0.27%   |
| Seagate ST9320325AS 320GB            | 4         | 0.27%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 0.27%   |
| Samsung SSD 850 PRO 1TB              | 4         | 0.27%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 0.27%   |
| Samsung MZVLQ512HALU-000H1 512GB     | 4         | 0.27%   |
| Samsung MZVLB1T0HALR-00000 1TB       | 4         | 0.27%   |
| Samsung MZALQ256HAJD-000L1 256GB     | 4         | 0.27%   |
| Lexar 512GB SSD                      | 4         | 0.27%   |
| Kingston SUV400S37240G 240GB SSD     | 4         | 0.27%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.27%   |
| Hitachi HTS543216L9A300 160GB        | 4         | 0.27%   |
| HGST HTS725050A7E630 500GB           | 4         | 0.27%   |
| Crucial CT250MX500SSD1 250GB         | 4         | 0.27%   |
| Crucial CT1000P1SSD8 1TB             | 4         | 0.27%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 3         | 0.21%   |
| WDC WD10JPVX-60JC3T0 1TB             | 3         | 0.21%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 128    | 31.7%   |
| WDC                 | 87        | 96     | 25.07%  |
| Toshiba             | 47        | 49     | 13.54%  |
| Hitachi             | 42        | 44     | 12.1%   |
| HGST                | 20        | 21     | 5.76%   |
| SABRENT             | 16        | 17     | 4.61%   |
| Fujitsu             | 10        | 11     | 2.88%   |
| Samsung Electronics | 5         | 5      | 1.44%   |
| Unknown             | 4         | 5      | 1.15%   |
| ASMT                | 2         | 3      | 0.58%   |
| USB3.0              | 1         | 1      | 0.29%   |
| SILICONMOTION       | 1         | 1      | 0.29%   |
| Maxone              | 1         | 1      | 0.29%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 116       | 143    | 21.72%  |
| Kingston            | 78        | 89     | 14.61%  |
| Apple               | 74        | 78     | 13.86%  |
| Crucial             | 47        | 56     | 8.8%    |
| SanDisk             | 44        | 51     | 8.24%   |
| A-DATA Technology   | 28        | 31     | 5.24%   |
| WDC                 | 15        | 25     | 2.81%   |
| Micron Technology   | 14        | 14     | 2.62%   |
| SK Hynix            | 11        | 12     | 2.06%   |
| Intel               | 10        | 10     | 1.87%   |
| China               | 10        | 10     | 1.87%   |
| Transcend           | 9         | 9      | 1.69%   |
| Toshiba             | 7         | 7      | 1.31%   |
| LITEON              | 7         | 7      | 1.31%   |
| PNY                 | 6         | 6      | 1.12%   |
| Intenso             | 5         | 6      | 0.94%   |
| Patriot             | 4         | 4      | 0.75%   |
| Lexar               | 4         | 5      | 0.75%   |
| GOODRAM             | 4         | 4      | 0.75%   |
| Seagate             | 3         | 3      | 0.56%   |
| LITEONIT            | 3         | 3      | 0.56%   |
| ZTC                 | 2         | 5      | 0.37%   |
| Team                | 2         | 2      | 0.37%   |
| SPCC                | 2         | 2      | 0.37%   |
| PLEXTOR             | 2         | 2      | 0.37%   |
| Netac               | 2         | 2      | 0.37%   |
| Corsair             | 2         | 2      | 0.37%   |
| Apacer              | 2         | 2      | 0.37%   |
| Vaseky              | 1         | 2      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |
| Union Memory        | 1         | 1      | 0.19%   |
| TrekStor            | 1         | 1      | 0.19%   |
| Teclast             | 1         | 1      | 0.19%   |
| RDM-II              | 1         | 1      | 0.19%   |
| MyDigitalSSD        | 1         | 1      | 0.19%   |
| Mushkin             | 1         | 1      | 0.19%   |
| MAXTOR              | 1         | 4      | 0.19%   |
| LDLC                | 1         | 1      | 0.19%   |
| KingSpec            | 1         | 1      | 0.19%   |
| Integral            | 1         | 1      | 0.19%   |
| InnoDisk            | 1         | 1      | 0.19%   |
| FORESEE             | 1         | 1      | 0.19%   |
| EMTEC               | 1         | 1      | 0.19%   |
| Dogeish             | 1         | 1      | 0.19%   |
| BIWIN               | 1         | 1      | 0.19%   |
| ASUS-PHISON         | 1         | 1      | 0.19%   |
| AMD                 | 1         | 2      | 0.19%   |
| 2.5"                | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 509       | 616    | 37.26%  |
| NVMe    | 426       | 522    | 31.19%  |
| HDD     | 327       | 383    | 23.94%  |
| MMC     | 92        | 119    | 6.73%   |
| Unknown | 12        | 12     | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 754       | 946    | 57.08%  |
| NVMe | 423       | 518    | 32.02%  |
| MMC  | 92        | 119    | 6.96%   |
| SAS  | 52        | 69     | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 575       | 690    | 68.53%  |
| 0.51-1.0   | 237       | 276    | 28.25%  |
| 1.01-2.0   | 19        | 24     | 2.26%   |
| 4.01-10.0  | 5         | 6      | 0.6%    |
| 3.01-4.0   | 2         | 2      | 0.24%   |
| 2.01-3.0   | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 457       | 37.4%   |
| 251-500        | 238       | 19.48%  |
| 501-1000       | 134       | 10.97%  |
| Unknown        | 121       | 9.9%    |
| 1-20           | 92        | 7.53%   |
| 51-100         | 62        | 5.07%   |
| 1001-2000      | 61        | 4.99%   |
| 21-50          | 33        | 2.7%    |
| More than 3000 | 17        | 1.39%   |
| 2001-3000      | 7         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 549       | 44.13%  |
| 21-50          | 158       | 12.7%   |
| 101-250        | 131       | 10.53%  |
| 51-100         | 130       | 10.45%  |
| Unknown        | 121       | 9.73%   |
| 251-500        | 80        | 6.43%   |
| 501-1000       | 48        | 3.86%   |
| 1001-2000      | 15        | 1.21%   |
| More than 3000 | 5         | 0.4%    |
| 0              | 5         | 0.4%    |
| 2001-3000      | 2         | 0.16%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2      | 1.98%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 1.98%   |
| SK Hynix PC711 HFS512GDE9X073N 512GB                | 2         | 2      | 1.98%   |
| SK Hynix HFS256G39MND-2300A 256GB SSD               | 2         | 2      | 1.98%   |
| Seagate ST9500325AS 500GB                           | 2         | 2      | 1.98%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 1.98%   |
| Seagate ST500LM000-SSHD-8GB                         | 2         | 2      | 1.98%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 2      | 1.98%   |
| Hitachi HTS545050B9A300 500GB                       | 2         | 2      | 1.98%   |
| Hitachi HTS542516K9SA00 160GB                       | 2         | 2      | 1.98%   |
| Hitachi HTS541060G9AT00 64GB                        | 2         | 3      | 1.98%   |
| HGST HTS725050A7E630 500GB                          | 2         | 2      | 1.98%   |
| Crucial CT275MX300SSD1 275GB                        | 2         | 2      | 1.98%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 1      | 0.99%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1      | 0.99%   |
| WDC WD5000BPVT-08HXZT1 500GB                        | 1         | 1      | 0.99%   |
| WDC WD1600BJKT-75F4T0 160GB                         | 1         | 1      | 0.99%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 1      | 0.99%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1      | 0.99%   |
| WDC WD10JPVT-75A1YT0 1TB                            | 1         | 1      | 0.99%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 1      | 0.99%   |
| Toshiba MK3275GSX 320GB                             | 1         | 1      | 0.99%   |
| Toshiba MK2555GSX 250GB                             | 1         | 1      | 0.99%   |
| Toshiba MK1633GSG 160GB                             | 1         | 1      | 0.99%   |
| SK Hynix SH920 mSATA 128GB SSD                      | 1         | 1      | 0.99%   |
| SK Hynix SC210 mSATA 128GB SSD                      | 1         | 1      | 0.99%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 0.99%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 0.99%   |
| Seagate ST960822A 64GB                              | 1         | 1      | 0.99%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 0.99%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 0.99%   |
| Seagate ST9250315AS 250GB                           | 1         | 2      | 0.99%   |
| Seagate ST9160310AS 160GB                           | 1         | 1      | 0.99%   |
| Seagate ST500VT000-1DK142 500GB                     | 1         | 1      | 0.99%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1         | 1      | 0.99%   |
| Seagate ST500LM000-1EJ162 500GB                     | 1         | 1      | 0.99%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 0.99%   |
| Seagate ST2000LX001-1RG174 2TB                      | 1         | 1      | 0.99%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 0.99%   |
| SanDisk SSD U100 24GB                               | 1         | 1      | 0.99%   |
| SanDisk SD7SB3Q128G1002 128GB SSD                   | 1         | 1      | 0.99%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 0.99%   |
| Samsung Electronics SSD 850 EVO 1TB                 | 1         | 1      | 0.99%   |
| Samsung Electronics SSD 840 PRO Series 256GB        | 1         | 2      | 0.99%   |
| Samsung Electronics HM321HI 320GB                   | 1         | 1      | 0.99%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 0.99%   |
| Micron Technology 2300 NVMe 512GB                   | 1         | 1      | 0.99%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 0.99%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD      | 1         | 1      | 0.99%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 0.99%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                      | 1         | 1      | 0.99%   |
| LITEON IT SCS-256L9S 256GB SSD                      | 1         | 1      | 0.99%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 0.99%   |
| Kingston SHFS37A120G 120GB SSD                      | 1         | 1      | 0.99%   |
| Kingston SA400S37960G 960GB SSD                     | 1         | 1      | 0.99%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 22        | 24     | 21.78%  |
| Seagate             | 19        | 20     | 18.81%  |
| WDC                 | 9         | 9      | 8.91%   |
| Toshiba             | 8         | 8      | 7.92%   |
| SK Hynix            | 8         | 8      | 7.92%   |
| Micron Technology   | 5         | 5      | 4.95%   |
| HGST                | 5         | 5      | 4.95%   |
| Samsung Electronics | 4         | 5      | 3.96%   |
| Kingston            | 4         | 4      | 3.96%   |
| Intel               | 4         | 4      | 3.96%   |
| Crucial             | 4         | 4      | 3.96%   |
| SanDisk             | 2         | 2      | 1.98%   |
| Fujitsu             | 2         | 2      | 1.98%   |
| LITEONIT            | 1         | 1      | 0.99%   |
| LITEON              | 1         | 1      | 0.99%   |
| IBM/Hitachi         | 1         | 1      | 0.99%   |
| GOODRAM             | 1         | 1      | 0.99%   |
| A-DATA Technology   | 1         | 1      | 0.99%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 22        | 24     | 32.84%  |
| Seagate             | 19        | 20     | 28.36%  |
| WDC                 | 9         | 9      | 13.43%  |
| Toshiba             | 8         | 8      | 11.94%  |
| HGST                | 5         | 5      | 7.46%   |
| Fujitsu             | 2         | 2      | 2.99%   |
| Samsung Electronics | 1         | 1      | 1.49%   |
| IBM/Hitachi         | 1         | 1      | 1.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 67        | 70     | 66.34%  |
| SSD  | 29        | 30     | 28.71%  |
| NVMe | 5         | 5      | 4.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 886       | 1123   | 69.49%  |
| Detected | 288       | 423    | 22.59%  |
| Malfunc  | 100       | 105    | 7.84%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 683       | 51.55%  |
| Samsung Electronics            | 170       | 12.83%  |
| AMD                            | 147       | 11.09%  |
| Apple                          | 78        | 5.89%   |
| Sandisk                        | 69        | 5.21%   |
| SK Hynix                       | 44        | 3.32%   |
| Kingston Technology Company    | 18        | 1.36%   |
| Toshiba America Info Systems   | 17        | 1.28%   |
| Micron Technology              | 17        | 1.28%   |
| KIOXIA                         | 17        | 1.28%   |
| Silicon Motion                 | 11        | 0.83%   |
| Micron/Crucial Technology      | 11        | 0.83%   |
| ADATA Technology               | 9         | 0.68%   |
| Nvidia                         | 7         | 0.53%   |
| Union Memory (Shenzhen)        | 5         | 0.38%   |
| Solid State Storage Technology | 5         | 0.38%   |
| Phison Electronics             | 5         | 0.38%   |
| Lenovo                         | 3         | 0.23%   |
| Lite-On Technology             | 2         | 0.15%   |
| Yangtze Memory Technologies    | 1         | 0.08%   |
| Silicon Image                  | 1         | 0.08%   |
| Shenzhen Longsys Electronics   | 1         | 0.08%   |
| Realtek Semiconductor          | 1         | 0.08%   |
| Marvell Technology Group       | 1         | 0.08%   |
| ASMedia Technology             | 1         | 0.08%   |
| Unknown                        | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 136       | 9.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 91        | 6.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 89        | 6.38%   |
| Apple S1X NVMe Controller                                                        | 76        | 5.45%   |
| Samsung Electronics SATA controller                                              | 71        | 5.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 56        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 45        | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 40        | 2.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 35        | 2.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 33        | 2.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 33        | 2.37%   |
| Samsung NVMe SSD Controller 980                                                  | 28        | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 25        | 1.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 1.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 22        | 1.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 20        | 1.43%   |
| Intel SSD 660P Series                                                            | 18        | 1.29%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 18        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 18        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 18        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 18        | 1.29%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 17        | 1.22%   |
| Micron Non-Volatile memory controller                                            | 17        | 1.22%   |
| KIOXIA Non-Volatile memory controller                                            | 17        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 17        | 1.22%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 16        | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                            | 15        | 1.08%   |
| SK Hynix Gold P31 SSD                                                            | 14        | 1%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 1%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 13        | 0.93%   |
| SK Hynix BC511                                                                   | 13        | 0.93%   |
| Sandisk Non-Volatile memory controller                                           | 13        | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 13        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 13        | 0.93%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 12        | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 11        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 9         | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 9         | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 8         | 0.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 0.57%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 7         | 0.5%    |
| Sandisk PC SN520 NVMe SSD                                                        | 7         | 0.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 7         | 0.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 0.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 6         | 0.43%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 6         | 0.43%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 0.43%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 5         | 0.36%   |
| Solid State Storage Non-Volatile memory controller                               | 5         | 0.36%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 5         | 0.36%   |
| Kingston Company Company Non-Volatile memory controller                          | 5         | 0.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 0.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 5         | 0.36%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.29%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 794       | 58.34%  |
| NVMe | 424       | 31.15%  |
| RAID | 75        | 5.51%   |
| IDE  | 68        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 995       | 82.99%  |
| AMD    | 203       | 16.93%  |
| ARM    | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 141       | 11.76%  |
| Intel Celeron CPU N2840 @ 2.16GHz             | 51        | 4.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 36        | 3%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 27        | 2.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 1.92%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 23        | 1.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 1.5%    |
| Intel Core i3-9100 CPU @ 3.60GHz              | 18        | 1.5%    |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 1.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 13        | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 0.92%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 11        | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.83%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 0.67%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 8         | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.67%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.67%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 8         | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.58%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.58%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 7         | 0.58%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.58%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 6         | 0.5%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.42%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 5         | 0.42%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 5         | 0.42%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 5         | 0.42%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 5         | 0.42%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 5         | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.42%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 5         | 0.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.42%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 5         | 0.42%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 5         | 0.42%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 0.42%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.42%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 0.42%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 391       | 32.61%  |
| Intel Core i7           | 210       | 17.51%  |
| Intel Celeron           | 110       | 9.17%   |
| Other                   | 97        | 8.09%   |
| Intel Core i3           | 78        | 6.51%   |
| AMD Ryzen 5             | 75        | 6.26%   |
| Intel Core 2 Duo        | 39        | 3.25%   |
| Intel Pentium           | 27        | 2.25%   |
| Intel Atom              | 25        | 2.09%   |
| AMD Ryzen 7             | 24        | 2%      |
| AMD Ryzen 7 PRO         | 12        | 1%      |
| AMD A6                  | 11        | 0.92%   |
| Intel Pentium M         | 10        | 0.83%   |
| Intel Genuine           | 7         | 0.58%   |
| AMD A8                  | 6         | 0.5%    |
| AMD A4                  | 6         | 0.5%    |
| AMD Ryzen 9             | 5         | 0.42%   |
| AMD Ryzen 3             | 5         | 0.42%   |
| AMD E1                  | 5         | 0.42%   |
| Intel Pentium Dual-Core | 4         | 0.33%   |
| Intel Celeron M         | 4         | 0.33%   |
| AMD Ryzen 5 PRO         | 4         | 0.33%   |
| Intel Xeon              | 3         | 0.25%   |
| Intel Pentium Gold      | 3         | 0.25%   |
| Intel Pentium Dual      | 3         | 0.25%   |
| Intel Core 2            | 3         | 0.25%   |
| AMD A12                 | 3         | 0.25%   |
| Intel Pentium Silver    | 2         | 0.17%   |
| Intel Core m3           | 2         | 0.17%   |
| Intel Core i9           | 2         | 0.17%   |
| AMD Turion 64 Mobile    | 2         | 0.17%   |
| AMD E                   | 2         | 0.17%   |
| AMD C-60                | 2         | 0.17%   |
| AMD C-50                | 2         | 0.17%   |
| AMD Athlon              | 2         | 0.17%   |
| AMD A10                 | 2         | 0.17%   |
| Intel Pentium III       | 1         | 0.08%   |
| Intel Core m7           | 1         | 0.08%   |
| Intel Core M            | 1         | 0.08%   |
| ARM ARMv7               | 1         | 0.08%   |
| AMD V140                | 1         | 0.08%   |
| AMD Sempron             | 1         | 0.08%   |
| AMD PRO A8              | 1         | 0.08%   |
| AMD FX                  | 1         | 0.08%   |
| AMD E2                  | 1         | 0.08%   |
| AMD C-30                | 1         | 0.08%   |
| AMD Athlon 64           | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 662       | 55.21%  |
| 4      | 362       | 30.19%  |
| 6      | 67        | 5.59%   |
| 1      | 63        | 5.25%   |
| 8      | 45        | 3.75%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1198      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 893       | 74.54%  |
| 1      | 305       | 25.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1170      | 97.66%  |
| 32-bit         | 26        | 2.17%   |
| Unknown        | 2         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 220       | 18.15%  |
| 0x306d4    | 174       | 14.36%  |
| 0x306a9    | 56        | 4.62%   |
| 0x30678    | 56        | 4.62%   |
| 0x806c1    | 53        | 4.37%   |
| 0x206a7    | 51        | 4.21%   |
| 0x806e9    | 49        | 4.04%   |
| 0x806ec    | 43        | 3.55%   |
| 0x806ea    | 33        | 2.72%   |
| 0x40651    | 27        | 2.23%   |
| 0x08108109 | 26        | 2.15%   |
| 0x406e3    | 25        | 2.06%   |
| 0x1067a    | 24        | 1.98%   |
| 0x0600611a | 24        | 1.98%   |
| 0x306c3    | 21        | 1.73%   |
| 0x20655    | 21        | 1.73%   |
| 0x08600106 | 20        | 1.65%   |
| 0x906ea    | 19        | 1.57%   |
| 0xa0652    | 18        | 1.49%   |
| 0x906eb    | 18        | 1.49%   |
| 0x706e5    | 15        | 1.24%   |
| 0x0a50000c | 11        | 0.91%   |
| 0x806eb    | 10        | 0.83%   |
| 0x6d8      | 10        | 0.83%   |
| 0x906e9    | 9         | 0.74%   |
| 0x6fd      | 9         | 0.74%   |
| 0x08608103 | 9         | 0.74%   |
| 0x06006705 | 9         | 0.74%   |
| 0x706a8    | 8         | 0.66%   |
| 0x506c9    | 8         | 0.66%   |
| 0x08108102 | 8         | 0.66%   |
| 0x106ca    | 7         | 0.58%   |
| 0x106c2    | 7         | 0.58%   |
| 0x08600104 | 7         | 0.58%   |
| 0x506e3    | 6         | 0.5%    |
| 0x406c4    | 6         | 0.5%    |
| 0x20652    | 6         | 0.5%    |
| 0x10676    | 6         | 0.5%    |
| 0x08600103 | 6         | 0.5%    |
| 0x0810100b | 5         | 0.41%   |
| 0x806d1    | 4         | 0.33%   |
| 0x6fb      | 4         | 0.33%   |
| 0x0a50000b | 4         | 0.33%   |
| 0x05000119 | 4         | 0.33%   |
| 0x906ed    | 3         | 0.25%   |
| 0x706a1    | 3         | 0.25%   |
| 0x6f6      | 3         | 0.25%   |
| 0x6e8      | 3         | 0.25%   |
| 0x406c3    | 3         | 0.25%   |
| 0x06001119 | 3         | 0.25%   |
| 0x03000027 | 3         | 0.25%   |
| 0x806c2    | 2         | 0.17%   |
| 0x6fa      | 2         | 0.17%   |
| 0x695      | 2         | 0.17%   |
| 0x40661    | 2         | 0.17%   |
| 0x08608102 | 2         | 0.17%   |
| 0x07030106 | 2         | 0.17%   |
| 0x07030105 | 2         | 0.17%   |
| 0x06006110 | 2         | 0.17%   |
| 0x05000029 | 2         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 226       | 18.85%  |
| Broadwell     | 181       | 15.1%   |
| IvyBridge     | 78        | 6.51%   |
| Silvermont    | 72        | 6.01%   |
| SandyBridge   | 70        | 5.84%   |
| TigerLake     | 67        | 5.59%   |
| Haswell       | 64        | 5.34%   |
| Zen+          | 46        | 3.84%   |
| Zen 2         | 45        | 3.75%   |
| Skylake       | 45        | 3.75%   |
| Excavator     | 39        | 3.25%   |
| Westmere      | 37        | 3.09%   |
| Penryn        | 32        | 2.67%   |
| Core          | 23        | 1.92%   |
| IceLake       | 21        | 1.75%   |
| CometLake     | 20        | 1.67%   |
| P6            | 18        | 1.5%    |
| Zen 3         | 16        | 1.33%   |
| Bonnell       | 16        | 1.33%   |
| Goldmont plus | 13        | 1.08%   |
| Unknown       | 13        | 1.08%   |
| Bobcat        | 11        | 0.92%   |
| Zen           | 10        | 0.83%   |
| Goldmont      | 10        | 0.83%   |
| Puma          | 7         | 0.58%   |
| K10 Llano     | 7         | 0.58%   |
| Piledriver    | 4         | 0.33%   |
| K8 Hammer     | 3         | 0.25%   |
| K10           | 2         | 0.17%   |
| Jaguar        | 2         | 0.17%   |
| Nehalem       | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 941       | 65.67%  |
| AMD         | 261       | 18.21%  |
| Nvidia      | 230       | 16.05%  |
| S3 Graphics | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 6000                                                                   | 143       | 9.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 73        | 4.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 62        | 4.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 62        | 4.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 60        | 4.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 3.24%   |
| Intel UHD Graphics 620                                                                   | 45        | 3.04%   |
| AMD Renoir                                                                               | 45        | 3.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 2.5%    |
| Intel HD Graphics 5500                                                                   | 34        | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 33        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 32        | 2.16%   |
| Intel HD Graphics 620                                                                    | 32        | 2.16%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 29        | 1.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 1.35%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 19        | 1.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 1.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 15        | 1.01%   |
| AMD Cezanne                                                                              | 15        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 0.74%   |
| AMD Lucienne                                                                             | 11        | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.68%   |
| Nvidia TU117M                                                                            | 10        | 0.68%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 10        | 0.68%   |
| Intel HD Graphics 630                                                                    | 10        | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 10        | 0.68%   |
| Intel HD Graphics 530                                                                    | 9         | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.54%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 8         | 0.54%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 8         | 0.54%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.47%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 7         | 0.47%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 0.47%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.47%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 7         | 0.47%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.41%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 0.41%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.34%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.34%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 5         | 0.34%   |
| Intel Tiger Lake UHD Graphics                                                            | 5         | 0.34%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.34%   |
| Intel HD Graphics 500                                                                    | 5         | 0.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 0.34%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.34%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.34%   |
| Nvidia TU117M [GeForce MX450]                                                            | 4         | 0.27%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 726       | 60.45%  |
| 1 x AMD         | 189       | 15.74%  |
| Intel + Nvidia  | 176       | 14.65%  |
| Intel + AMD     | 39        | 3.25%   |
| 1 x Nvidia      | 34        | 2.83%   |
| AMD + Nvidia    | 21        | 1.75%   |
| 2 x AMD         | 12        | 1%      |
| Other           | 3         | 0.25%   |
| 1 x S3 Graphics | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1027      | 85.23%  |
| Unknown     | 94        | 7.8%    |
| Proprietary | 84        | 6.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 974       | 80.7%   |
| 0.01-0.5   | 106       | 8.78%   |
| 1.01-2.0   | 45        | 3.73%   |
| 3.01-4.0   | 41        | 3.4%    |
| 0.51-1.0   | 33        | 2.73%   |
| 5.01-6.0   | 4         | 0.33%   |
| 7.01-8.0   | 3         | 0.25%   |
| 2.01-3.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 206       | 16.17%  |
| BOE                     | 204       | 16.01%  |
| Apple                   | 165       | 12.95%  |
| Chimei Innolux          | 147       | 11.54%  |
| LG Display              | 140       | 10.99%  |
| Samsung Electronics     | 94        | 7.38%   |
| Sharp                   | 34        | 2.67%   |
| Lenovo                  | 33        | 2.59%   |
| Dell                    | 26        | 2.04%   |
| Goldstar                | 23        | 1.81%   |
| Chi Mei Optoelectronics | 23        | 1.81%   |
| InfoVision              | 18        | 1.41%   |
| BenQ                    | 18        | 1.41%   |
| PANDA                   | 15        | 1.18%   |
| Hewlett-Packard         | 13        | 1.02%   |
| Philips                 | 12        | 0.94%   |
| LG Philips              | 10        | 0.78%   |
| Unknown                 | 9         | 0.71%   |
| HannStar                | 8         | 0.63%   |
| Ancor Communications    | 8         | 0.63%   |
| AOC                     | 7         | 0.55%   |
| CSO                     | 6         | 0.47%   |
| Acer                    | 5         | 0.39%   |
| ViewSonic               | 4         | 0.31%   |
| Sony                    | 4         | 0.31%   |
| Iiyama                  | 4         | 0.31%   |
| NEC Computers           | 3         | 0.24%   |
| CPT                     | 3         | 0.24%   |
| ___                     | 2         | 0.16%   |
| Toshiba                 | 2         | 0.16%   |
| Quanta Display          | 2         | 0.16%   |
| Panasonic               | 2         | 0.16%   |
| ASUSTek Computer        | 2         | 0.16%   |
| Vestel Elektronik       | 1         | 0.08%   |
| TMX                     | 1         | 0.08%   |
| SLD                     | 1         | 0.08%   |
| RX_                     | 1         | 0.08%   |
| REG                     | 1         | 0.08%   |
| PHA                     | 1         | 0.08%   |
| Olevia                  | 1         | 0.08%   |
| NCS                     | 1         | 0.08%   |
| MSI                     | 1         | 0.08%   |
| LPL                     | 1         | 0.08%   |
| JXG                     | 1         | 0.08%   |
| JRY                     | 1         | 0.08%   |
| ITE                     | 1         | 0.08%   |
| IOD                     | 1         | 0.08%   |
| InnoLux Display         | 1         | 0.08%   |
| Grundig                 | 1         | 0.08%   |
| Green House             | 1         | 0.08%   |
| Eizo                    | 1         | 0.08%   |
| Denver                  | 1         | 0.08%   |
| Compaq Computer         | 1         | 0.08%   |
| CMN                     | 1         | 0.08%   |
| BOE Technology Group    | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 3.11%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 40        | 3.11%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 35        | 2.72%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 2.33%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 24        | 1.87%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 1.79%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 17        | 1.32%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.86%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 11        | 0.86%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 10        | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 9         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 8         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 8         | 0.62%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 8         | 0.62%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 7         | 0.54%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 7         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 7         | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 7         | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 7         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 6         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 5         | 0.39%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 5         | 0.39%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 5         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 5         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 5         | 0.39%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                         | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 5         | 0.39%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 5         | 0.39%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 4         | 0.31%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch               | 4         | 0.31%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 4         | 0.31%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                   | 4         | 0.31%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 4         | 0.31%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 340x190mm 15.3-inch          | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 4         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 4         | 0.31%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 4         | 0.31%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 4         | 0.31%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 4         | 0.31%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch     | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SAM052F 1360x768 410x256mm 19.0-inch      | 3         | 0.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.23%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch              | 3         | 0.23%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 3         | 0.23%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 3         | 0.23%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 470       | 38.81%  |
| 1366x768 (WXGA)    | 383       | 31.63%  |
| 1440x900 (WXGA+)   | 85        | 7.02%   |
| 1600x900 (HD+)     | 53        | 4.38%   |
| 1280x800 (WXGA)    | 43        | 3.55%   |
| 3840x2160 (4K)     | 36        | 2.97%   |
| 2560x1440 (QHD)    | 27        | 2.23%   |
| 1920x1200 (WUXGA)  | 22        | 1.82%   |
| 1024x600           | 15        | 1.24%   |
| 1280x1024 (SXGA)   | 14        | 1.16%   |
| 2288x1287          | 7         | 0.58%   |
| 1360x768           | 7         | 0.58%   |
| 2880x1800          | 6         | 0.5%    |
| 2560x1600          | 6         | 0.5%    |
| 3840x2400          | 5         | 0.41%   |
| 1024x768 (XGA)     | 5         | 0.41%   |
| 2160x1440          | 4         | 0.33%   |
| 3440x1440          | 3         | 0.25%   |
| 1680x1050 (WSXGA+) | 3         | 0.25%   |
| 3840x1100          | 2         | 0.17%   |
| 3840x1080          | 2         | 0.17%   |
| 3200x1800 (QHD+)   | 2         | 0.17%   |
| 2256x1504          | 2         | 0.17%   |
| 3840x1200          | 1         | 0.08%   |
| 2880x1920          | 1         | 0.08%   |
| 2520x1680          | 1         | 0.08%   |
| 2304x1440          | 1         | 0.08%   |
| 1920x515           | 1         | 0.08%   |
| 1792x768           | 1         | 0.08%   |
| 1600x1200          | 1         | 0.08%   |
| 1400x1050          | 1         | 0.08%   |
| Unknown            | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 373       | 29.32%  |
| 13      | 273       | 21.46%  |
| 11      | 144       | 11.32%  |
| 14      | 141       | 11.08%  |
| 17      | 64        | 5.03%   |
| 12      | 52        | 4.09%   |
| 24      | 47        | 3.69%   |
| 21      | 31        | 2.44%   |
| 27      | 28        | 2.2%    |
| 23      | 24        | 1.89%   |
| 19      | 13        | 1.02%   |
| 10      | 13        | 1.02%   |
| 18      | 11        | 0.86%   |
| Unknown | 8         | 0.63%   |
| 142     | 7         | 0.55%   |
| 31      | 6         | 0.47%   |
| 25      | 6         | 0.47%   |
| 16      | 5         | 0.39%   |
| 72      | 3         | 0.24%   |
| 34      | 3         | 0.24%   |
| 32      | 3         | 0.24%   |
| 20      | 3         | 0.24%   |
| 84      | 2         | 0.16%   |
| 54      | 2         | 0.16%   |
| 40      | 2         | 0.16%   |
| 8       | 2         | 0.16%   |
| 52      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 43      | 1         | 0.08%   |
| 33      | 1         | 0.08%   |
| 22      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 628       | 49.72%  |
| 201-300        | 363       | 28.74%  |
| 501-600        | 93        | 7.36%   |
| 351-400        | 76        | 6.02%   |
| 401-500        | 53        | 4.2%    |
| 601-700        | 13        | 1.03%   |
| Unknown        | 8         | 0.63%   |
| More than 2000 | 7         | 0.55%   |
| 701-800        | 7         | 0.55%   |
| 1001-1500      | 6         | 0.48%   |
| 1501-2000      | 5         | 0.4%    |
| 801-900        | 2         | 0.16%   |
| 101-200        | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 921       | 80.72%  |
| 16/10   | 168       | 14.72%  |
| 5/4     | 14        | 1.23%   |
| 3/2     | 11        | 0.96%   |
| 4/3     | 7         | 0.61%   |
| 1.00    | 7         | 0.61%   |
| 21/9    | 4         | 0.35%   |
| Unknown | 4         | 0.35%   |
| 3.40    | 2         | 0.18%   |
| 32/9    | 1         | 0.09%   |
| 3.73    | 1         | 0.09%   |
| 3.20    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 377       | 29.69%  |
| 81-90          | 301       | 23.7%   |
| 51-60          | 146       | 11.5%   |
| 71-80          | 111       | 8.74%   |
| 201-250        | 83        | 6.54%   |
| 121-130        | 51        | 4.02%   |
| 61-70          | 50        | 3.94%   |
| 301-350        | 28        | 2.2%    |
| 151-200        | 24        | 1.89%   |
| 251-300        | 17        | 1.34%   |
| 141-150        | 16        | 1.26%   |
| More than 1000 | 15        | 1.18%   |
| 351-500        | 13        | 1.02%   |
| 41-50          | 13        | 1.02%   |
| Unknown        | 8         | 0.63%   |
| 131-140        | 6         | 0.47%   |
| 501-1000       | 5         | 0.39%   |
| 91-100         | 4         | 0.31%   |
| 1-40           | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 656       | 52.65%  |
| 101-120       | 301       | 24.16%  |
| 51-100        | 167       | 13.4%   |
| 161-240       | 69        | 5.54%   |
| More than 240 | 28        | 2.25%   |
| 1-50          | 17        | 1.36%   |
| Unknown       | 8         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 932       | 77.02%  |
| 2     | 166       | 13.72%  |
| 0     | 95        | 7.85%   |
| 3     | 16        | 1.32%   |
| 5     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 586       | 32.39%  |
| Realtek Semiconductor             | 556       | 30.74%  |
| Qualcomm Atheros                  | 248       | 13.71%  |
| Broadcom Limited                  | 170       | 9.4%    |
| Broadcom                          | 90        | 4.98%   |
| Marvell Technology Group          | 18        | 1%      |
| Ralink                            | 16        | 0.88%   |
| MEDIATEK                          | 15        | 0.83%   |
| TP-Link                           | 11        | 0.61%   |
| Dell                              | 9         | 0.5%    |
| Sierra Wireless                   | 8         | 0.44%   |
| Ralink Technology                 | 8         | 0.44%   |
| Nvidia                            | 6         | 0.33%   |
| JMicron Technology                | 6         | 0.33%   |
| DisplayLink                       | 6         | 0.33%   |
| Ericsson Business Mobile Networks | 5         | 0.28%   |
| Hewlett-Packard                   | 4         | 0.22%   |
| Attansic Technology               | 4         | 0.22%   |
| ASIX Electronics                  | 4         | 0.22%   |
| Samsung Electronics               | 3         | 0.17%   |
| Qualcomm Atheros Communications   | 3         | 0.17%   |
| Qualcomm                          | 3         | 0.17%   |
| Lenovo                            | 3         | 0.17%   |
| Fibocom                           | 3         | 0.17%   |
| ASUSTek Computer                  | 3         | 0.17%   |
| AMD                               | 3         | 0.17%   |
| Xiaomi                            | 2         | 0.11%   |
| NetGear                           | 2         | 0.11%   |
| Huawei Technologies               | 2         | 0.11%   |
| D-Link                            | 2         | 0.11%   |
| Cypress Semiconductor             | 2         | 0.11%   |
| Winbond Electronics               | 1         | 0.06%   |
| U-Blox                            | 1         | 0.06%   |
| Motorola PCS                      | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| Google                            | 1         | 0.06%   |
| Edimax Technology                 | 1         | 0.06%   |
| Belkin Components                 | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 365       | 16.92%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 145       | 6.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 87        | 4.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 82        | 3.8%    |
| Intel Wireless 7260                                                     | 69        | 3.2%    |
| Intel Wireless 8265 / 8275                                              | 62        | 2.87%   |
| Intel Wi-Fi 6 AX200                                                     | 55        | 2.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 51        | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 42        | 1.95%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 1.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 1.53%   |
| Intel Wireless 7265                                                     | 32        | 1.48%   |
| Intel Ethernet Connection (4) I219-V                                    | 32        | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 1.16%   |
| Intel Wireless 8260                                                     | 24        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                   | 16        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                   | 15        | 0.7%    |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 14        | 0.65%   |
| Intel Wireless 3165                                                     | 14        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                | 14        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                    | 13        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.56%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.51%   |
| Intel Wireless 3160                                                     | 11        | 0.51%   |
| Intel Ethernet Connection I219-LM                                       | 11        | 0.51%   |
| Intel Ethernet Connection I218-LM                                       | 11        | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.51%   |
| Intel Centrino Wireless-N 2230                                          | 11        | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 10        | 0.46%   |
| Intel Ethernet Connection (13) I219-V                                   | 10        | 0.46%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.46%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 9         | 0.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.37%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 8         | 0.37%   |
| Intel Wireless-AC 9260                                                  | 8         | 0.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.37%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 7         | 0.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 0.32%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 7         | 0.32%   |
| Sierra Wireless EM7345 4G LTE                                           | 6         | 0.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 6         | 0.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.28%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 6         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 560       | 45.64%  |
| Qualcomm Atheros                | 223       | 18.17%  |
| Broadcom Limited                | 161       | 13.12%  |
| Realtek Semiconductor           | 152       | 12.39%  |
| Broadcom                        | 58        | 4.73%   |
| Ralink                          | 16        | 1.3%    |
| MEDIATEK                        | 13        | 1.06%   |
| Sierra Wireless                 | 8         | 0.65%   |
| Ralink Technology               | 8         | 0.65%   |
| TP-Link                         | 7         | 0.57%   |
| Dell                            | 5         | 0.41%   |
| Qualcomm Atheros Communications | 3         | 0.24%   |
| Qualcomm                        | 3         | 0.24%   |
| Fibocom                         | 3         | 0.24%   |
| ASUSTek Computer                | 3         | 0.24%   |
| NetGear                         | 2         | 0.16%   |
| Edimax Technology               | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 145       | 11.76%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 87        | 7.06%   |
| Intel Wireless 7260                                                     | 69        | 5.6%    |
| Intel Wireless 8265 / 8275                                              | 62        | 5.03%   |
| Intel Wi-Fi 6 AX200                                                     | 55        | 4.46%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 3.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 2.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 34        | 2.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 2.68%   |
| Intel Wireless 7265                                                     | 32        | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 30        | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 25        | 2.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 2.03%   |
| Intel Wireless 8260                                                     | 24        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 1.3%    |
| Intel Wireless 3165                                                     | 14        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.14%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 13        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.97%   |
| Intel Centrino Advanced-N 6200                                          | 12        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.89%   |
| Intel Wireless 3160                                                     | 11        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 0.89%   |
| Intel Centrino Wireless-N 2230                                          | 11        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 10        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 9         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 8         | 0.65%   |
| Intel Wireless-AC 9260                                                  | 8         | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.65%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 7         | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 0.57%   |
| Sierra Wireless EM7345 4G LTE                                           | 6         | 0.49%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.49%   |
| Intel WiFi Link 5100                                                    | 5         | 0.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 5         | 0.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 5         | 0.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 5         | 0.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.41%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.32%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.32%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.32%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.32%   |
| Broadcom BCM43227 802.11b/g/n                                           | 4         | 0.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 3         | 0.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.24%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.24%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.24%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 501       | 56.55%  |
| Intel                    | 231       | 26.07%  |
| Qualcomm Atheros         | 40        | 4.51%   |
| Broadcom                 | 38        | 4.29%   |
| Marvell Technology Group | 18        | 2.03%   |
| Broadcom Limited         | 10        | 1.13%   |
| Nvidia                   | 6         | 0.68%   |
| JMicron Technology       | 6         | 0.68%   |
| DisplayLink              | 6         | 0.68%   |
| TP-Link                  | 4         | 0.45%   |
| Attansic Technology      | 4         | 0.45%   |
| ASIX Electronics         | 4         | 0.45%   |
| Samsung Electronics      | 3         | 0.34%   |
| Lenovo                   | 3         | 0.34%   |
| Xiaomi                   | 2         | 0.23%   |
| D-Link                   | 2         | 0.23%   |
| Cypress Semiconductor    | 2         | 0.23%   |
| Motorola PCS             | 1         | 0.11%   |
| Microchip Technology     | 1         | 0.11%   |
| MediaTek                 | 1         | 0.11%   |
| ICS Advent               | 1         | 0.11%   |
| Huawei Technologies      | 1         | 0.11%   |
| Google                   | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 365       | 40.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 9.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 5.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 42        | 4.69%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 3.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.79%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 1.68%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 1.56%   |
| Intel Ethernet Connection (6) I219-V                              | 13        | 1.45%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.23%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 5         | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.45%   |
| Intel Ethernet Connection (3) I218-V                              | 4         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.45%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 4         | 0.45%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 4         | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.34%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.34%   |
| Intel Ethernet Connection (14) I219-LM                            | 3         | 0.34%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.34%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.34%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.34%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 3         | 0.34%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.22%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.22%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.22%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.22%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.22%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.22%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.22%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.22%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 2         | 0.22%   |
| Cypress K38231_03                                                 | 2         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1179      | 57.07%  |
| Ethernet | 858       | 41.53%  |
| Modem    | 27        | 1.31%   |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1026      | 59.89%  |
| Ethernet | 683       | 39.87%  |
| Modem    | 4         | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 784       | 65.44%  |
| 1     | 391       | 32.64%  |
| 0     | 12        | 1%      |
| 3     | 10        | 0.83%   |
| 4     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1010      | 83.54%  |
| Yes  | 199       | 16.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 420       | 42.21%  |
| Apple                           | 161       | 16.18%  |
| Realtek Semiconductor           | 93        | 9.35%   |
| Qualcomm Atheros Communications | 89        | 8.94%   |
| Lite-On Technology              | 47        | 4.72%   |
| Broadcom                        | 44        | 4.42%   |
| IMC Networks                    | 32        | 3.22%   |
| Foxconn / Hon Hai               | 27        | 2.71%   |
| Qualcomm Atheros                | 16        | 1.61%   |
| Cambridge Silicon Radio         | 14        | 1.41%   |
| Hewlett-Packard                 | 10        | 1.01%   |
| Dell                            | 9         | 0.9%    |
| Realtek                         | 7         | 0.7%    |
| Ralink                          | 7         | 0.7%    |
| Toshiba                         | 6         | 0.6%    |
| ASUSTek Computer                | 6         | 0.6%    |
| Taiyo Yuden                     | 2         | 0.2%    |
| Ralink Technology               | 1         | 0.1%    |
| Qcom                            | 1         | 0.1%    |
| Fujitsu                         | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 151       | 15.15%  |
| Apple Bluetooth USB Host Controller                                                 | 144       | 14.44%  |
| Intel Bluetooth wireless interface                                                  | 122       | 12.24%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 76        | 7.62%   |
| Intel AX201 Bluetooth                                                               | 69        | 6.92%   |
| Realtek Bluetooth Radio                                                             | 65        | 6.52%   |
| Intel AX200 Bluetooth                                                               | 56        | 5.62%   |
| Lite-On Bluetooth Device                                                            | 29        | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 26        | 2.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 16        | 1.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 14        | 1.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 14        | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.3%    |
| Apple Bluetooth Host Controller                                                     | 11        | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 1%      |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 9         | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 8         | 0.8%    |
| IMC Networks Bluetooth Device                                                       | 8         | 0.8%    |
| Realtek Bluetooth Radio                                                             | 7         | 0.7%    |
| Ralink RT3290 Bluetooth                                                             | 7         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.6%    |
| Lite-On Wireless_Device                                                             | 5         | 0.5%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 5         | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 0.5%    |
| IMC Networks Wireless_Device                                                        | 5         | 0.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 4         | 0.4%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.4%    |
| IMC Networks Bluetooth                                                              | 4         | 0.4%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 0.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.4%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 4         | 0.4%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 4         | 0.4%    |
| Toshiba Bluetooth Device                                                            | 3         | 0.3%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.3%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.3%    |
| Realtek RTL8723A Bluetooth                                                          | 2         | 0.2%    |
| Lite-On BCM43142A0                                                                  | 2         | 0.2%    |
| IMC Networks Bluetooth module                                                       | 2         | 0.2%    |
| HP Atheros AR9285 Malbec Bluetooth Adapter                                          | 2         | 0.2%    |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.2%    |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.2%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.2%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.2%    |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.2%    |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 0.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.2%    |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 2         | 0.2%    |
| Apple Bluetooth HCI                                                                 | 2         | 0.2%    |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.1%    |
| Toshiba Bluetooth Radio                                                             | 1         | 0.1%    |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.1%    |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)                                             | 1         | 0.1%    |
| Taiyo Yuden Bluetooth Device                                                        | 1         | 0.1%    |
| Realtek CSR BS8510                                                                  | 1         | 0.1%    |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.1%    |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.1%    |
| Lite-On Bluetooth Radio                                                             | 1         | 0.1%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 978       | 71.6%   |
| AMD                       | 215       | 15.74%  |
| Nvidia                    | 111       | 8.13%   |
| Logitech                  | 8         | 0.59%   |
| Generalplus Technology    | 8         | 0.59%   |
| C-Media Electronics       | 8         | 0.59%   |
| Creative Technology       | 5         | 0.37%   |
| Realtek Semiconductor     | 4         | 0.29%   |
| GN Netcom                 | 4         | 0.29%   |
| Texas Instruments         | 3         | 0.22%   |
| Plantronics               | 3         | 0.22%   |
| Lenovo                    | 3         | 0.22%   |
| JMTek                     | 2         | 0.15%   |
| Hewlett-Packard           | 2         | 0.15%   |
| CMX Systems               | 2         | 0.15%   |
| Thomann                   | 1         | 0.07%   |
| SteelSeries ApS           | 1         | 0.07%   |
| Sennheiser Communications | 1         | 0.07%   |
| SAVITECH                  | 1         | 0.07%   |
| Samsung Electronics       | 1         | 0.07%   |
| Razer USA                 | 1         | 0.07%   |
| Pixart Imaging            | 1         | 0.07%   |
| Microsoft                 | 1         | 0.07%   |
| Microdia                  | 1         | 0.07%   |
| ESS Technology            | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Broadwell-U Audio Controller                                                                | 181       | 10.12%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 180       | 10.06%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 136       | 7.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 126       | 7.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 98        | 5.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 67        | 3.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 56        | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 56        | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 55        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 50        | 2.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 47        | 2.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 38        | 2.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 38        | 2.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 38        | 2.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 1.96%   |
| Intel 8 Series HD Audio Controller                                                                | 35        | 1.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 1.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 29        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 26        | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 25        | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 23        | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 17        | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 0.61%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 0.56%   |
| AMD High Definition Audio Controller                                                              | 10        | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.5%    |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.45%   |
| Generalplus Technology USB Audio Device                                                           | 8         | 0.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 0.39%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 7         | 0.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 6         | 0.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.28%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.28%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 5         | 0.28%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.28%   |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.22%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.22%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.22%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.22%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 0.22%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.17%   |
| Nvidia Audio device                                                                               | 3         | 0.17%   |
| Logitech H390 headset with microphone                                                             | 3         | 0.17%   |
| Logitech 960 Headset                                                                              | 3         | 0.17%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.17%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 361       | 30.21%  |
| SK Hynix            | 243       | 20.33%  |
| Micron Technology   | 134       | 11.21%  |
| Crucial             | 86        | 7.2%    |
| Kingston            | 84        | 7.03%   |
| Unknown             | 71        | 5.94%   |
| Elpida              | 61        | 5.1%    |
| Ramaxel Technology  | 26        | 2.18%   |
| A-DATA Technology   | 22        | 1.84%   |
| Corsair             | 18        | 1.51%   |
| Nanya Technology    | 16        | 1.34%   |
| GOODRAM             | 14        | 1.17%   |
| Smart               | 9         | 0.75%   |
| Unknown (ABCD)      | 8         | 0.67%   |
| Team                | 6         | 0.5%    |
| Transcend           | 4         | 0.33%   |
| G.Skill             | 4         | 0.33%   |
| ASint Technology    | 4         | 0.33%   |
| Patriot             | 3         | 0.25%   |
| PNY                 | 2         | 0.17%   |
| Avant               | 2         | 0.17%   |
| AMD                 | 2         | 0.17%   |
| Wilk                | 1         | 0.08%   |
| Unknown (08C8)      | 1         | 0.08%   |
| Unifosa             | 1         | 0.08%   |
| Teikon              | 1         | 0.08%   |
| SMART Brazil        | 1         | 0.08%   |
| Silicon Power       | 1         | 0.08%   |
| Sesame              | 1         | 0.08%   |
| Novatech            | 1         | 0.08%   |
| Kllisre             | 1         | 0.08%   |
| Infineon            | 1         | 0.08%   |
| Goldkey             | 1         | 0.08%   |
| AXIOM               | 1         | 0.08%   |
| A-TECH              | 1         | 0.08%   |
| 48spaces            | 1         | 0.08%   |
| Unknown             | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 61        | 4.87%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 38        | 3.04%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 32        | 2.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 23        | 1.84%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 23        | 1.84%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 20        | 1.6%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 20        | 1.6%    |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 18        | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.2%    |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 15        | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 14        | 1.12%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 12        | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.96%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 12        | 0.96%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.88%   |
| Micron RAM 4KTF25664HZ-1G6E 2048MB SODIMM DDR3 1333MT/s          | 10        | 0.8%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 9         | 0.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 9         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.64%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.64%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 0.64%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 8         | 0.64%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s          | 8         | 0.64%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 7         | 0.56%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 7         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.56%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.48%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.48%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.48%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 6         | 0.48%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.4%    |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 5         | 0.4%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.4%    |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s   | 5         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 5         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s    | 5         | 0.4%    |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 5         | 0.4%    |
| GOODRAM RAM GR2666S464L19/16G 16384MB SODIMM DDR4 2667MT/s       | 5         | 0.4%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.4%    |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 4         | 0.32%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 0.32%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 4         | 0.32%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.32%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.32%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 4         | 0.32%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 474       | 45.4%   |
| DDR4    | 433       | 41.48%  |
| DDR2    | 40        | 3.83%   |
| LPDDR4  | 35        | 3.35%   |
| LPDDR3  | 25        | 2.39%   |
| SDRAM   | 18        | 1.72%   |
| DDR     | 13        | 1.25%   |
| Unknown | 5         | 0.48%   |
| DRAM    | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 970       | 92.65%  |
| Row Of Chips | 63        | 6.02%   |
| Chip         | 10        | 0.96%   |
| DIMM         | 2         | 0.19%   |
| Unknown      | 2         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 390       | 34.61%  |
| 8192  | 320       | 28.39%  |
| 2048  | 227       | 20.14%  |
| 16384 | 113       | 10.03%  |
| 1024  | 43        | 3.82%   |
| 32768 | 22        | 1.95%   |
| 512   | 10        | 0.89%   |
| 256   | 2         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 376       | 33.69%  |
| 2667    | 217       | 19.44%  |
| 3200    | 154       | 13.8%   |
| 2400    | 73        | 6.54%   |
| 1334    | 48        | 4.3%    |
| 2133    | 44        | 3.94%   |
| 1333    | 43        | 3.85%   |
| Unknown | 26        | 2.33%   |
| 667     | 22        | 1.97%   |
| 4267    | 18        | 1.61%   |
| 1067    | 15        | 1.34%   |
| 3266    | 14        | 1.25%   |
| 1867    | 11        | 0.99%   |
| 4199    | 9         | 0.81%   |
| 533     | 9         | 0.81%   |
| 800     | 7         | 0.63%   |
| 975     | 6         | 0.54%   |
| 1866    | 5         | 0.45%   |
| 333     | 4         | 0.36%   |
| 4266    | 3         | 0.27%   |
| 2048    | 3         | 0.27%   |
| 1066    | 3         | 0.27%   |
| 400     | 3         | 0.27%   |
| 8400    | 1         | 0.09%   |
| 3000    | 1         | 0.09%   |
| 933     | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Xerox               | 2         | 22.22%  |
| Hewlett-Packard     | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |
| Brother Industries  | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 2         | 22.22%  |
| Samsung ML-2010P Mono Laser Printer | 1         | 11.11%  |
| HP Ink Tank 110 series              | 1         | 11.11%  |
| HP DeskJet 2130 series              | 1         | 11.11%  |
| Canon PIXMA MX920 Series            | 1         | 11.11%  |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 11.11%  |
| Brother PT-9500PC                   | 1         | 11.11%  |
| Brother MFC-L2707DW                 | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 33.33%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 33.33%  |
| Canon CanoScan LiDE 120                       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 240       | 25.67%  |
| IMC Networks                           | 105       | 11.23%  |
| Acer                                   | 99        | 10.59%  |
| Quanta                                 | 97        | 10.37%  |
| Realtek Semiconductor                  | 69        | 7.38%   |
| Microdia                               | 65        | 6.95%   |
| Sunplus Innovation Technology          | 37        | 3.96%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 3.64%   |
| Suyin                                  | 30        | 3.21%   |
| Lite-On Technology                     | 24        | 2.57%   |
| Syntek                                 | 18        | 1.93%   |
| Luxvisions Innotech Limited            | 16        | 1.71%   |
| Logitech                               | 13        | 1.39%   |
| Apple                                  | 13        | 1.39%   |
| Silicon Motion                         | 10        | 1.07%   |
| Lenovo                                 | 10        | 1.07%   |
| Alcor Micro                            | 7         | 0.75%   |
| Ricoh                                  | 6         | 0.64%   |
| Z-Star Microelectronics                | 5         | 0.53%   |
| Primax Electronics                     | 4         | 0.43%   |
| SunplusIT                              | 3         | 0.32%   |
| Intel                                  | 3         | 0.32%   |
| Importek                               | 3         | 0.32%   |
| Sonix Technology                       | 2         | 0.21%   |
| Mimaki Engineering                     | 2         | 0.21%   |
| ALi                                    | 2         | 0.21%   |
| 8SSC20X55495V1SR0BH49GK                | 2         | 0.21%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Samsung Electronics                    | 1         | 0.11%   |
| Pixart Imaging                         | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |
| KYE Systems (Mouse Systems)            | 1         | 0.11%   |
| icSpring                               | 1         | 0.11%   |
| Holitech                               | 1         | 0.11%   |
| HD 2MP WEBCAM                          | 1         | 0.11%   |
| Generalplus Technology                 | 1         | 0.11%   |
| eMPIA Technology                       | 1         | 0.11%   |
| DJKANA1BIF866I                         | 1         | 0.11%   |
| Creative Technology                    | 1         | 0.11%   |
| ARC International                      | 1         | 0.11%   |
| A4Tech                                 | 1         | 0.11%   |
| 8SSC20F27145V1SR18P0H10                | 1         | 0.11%   |
| 8SSC20F27114V1SR0C91796                | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 90        | 9.58%   |
| Quanta Chromebook HD Camera                                                | 37        | 3.94%   |
| Microdia Integrated_Webcam_HD                                              | 37        | 3.94%   |
| IMC Networks Integrated Camera                                             | 37        | 3.94%   |
| Acer Integrated Camera                                                     | 26        | 2.77%   |
| Chicony HD WebCam                                                          | 25        | 2.66%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 24        | 2.56%   |
| Realtek Integrated_Webcam_HD                                               | 22        | 2.34%   |
| Acer BisonCam, NB Pro                                                      | 22        | 2.34%   |
| Quanta VGA WebCam                                                          | 17        | 1.81%   |
| Quanta HP TrueVision HD Camera                                             | 14        | 1.49%   |
| Sunplus Integrated_Webcam_HD                                               | 13        | 1.38%   |
| Chicony HP HD Camera                                                       | 12        | 1.28%   |
| Acer SunplusIT Integrated Camera                                           | 12        | 1.28%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 11        | 1.17%   |
| Lite-On Integrated Camera                                                  | 11        | 1.17%   |
| Syntek Integrated Camera                                                   | 10        | 1.06%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 10        | 1.06%   |
| Chicony Chromebook HD Camera                                               | 10        | 1.06%   |
| Chicony Integrated Camera (1280x720@30)                                    | 8         | 0.85%   |
| Acer Lenovo Integrated Webcam                                              | 8         | 0.85%   |
| Realtek USB Camera                                                         | 7         | 0.75%   |
| Quanta HD Webcam                                                           | 7         | 0.75%   |
| Lenovo Integrated Webcam                                                   | 7         | 0.75%   |
| Chicony Lenovo EasyCamera                                                  | 7         | 0.75%   |
| Chicony HD User Facing                                                     | 7         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 7         | 0.75%   |
| Acer Lenovo EasyCamera                                                     | 7         | 0.75%   |
| Realtek Lenovo EasyCamera                                                  | 6         | 0.64%   |
| Realtek Integrated Webcam                                                  | 6         | 0.64%   |
| Quanta HP HD Camera                                                        | 6         | 0.64%   |
| Quanta HD User Facing                                                      | 6         | 0.64%   |
| Lite-On HP HD Camera                                                       | 6         | 0.64%   |
| Chicony HP Truevision HD                                                   | 6         | 0.64%   |
| Chicony USB2.0 Camera                                                      | 5         | 0.53%   |
| Chicony HP Webcam                                                          | 5         | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 5         | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 5         | 0.53%   |
| Acer EasyCamera                                                            | 5         | 0.53%   |
| Suyin HP Truevision HD                                                     | 4         | 0.43%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 4         | 0.43%   |
| Sunplus HD WebCam                                                          | 4         | 0.43%   |
| Realtek USB2.0 HD UVC WebCam                                               | 4         | 0.43%   |
| Realtek EasyCamera                                                         | 4         | 0.43%   |
| Quanta HP Webcam                                                           | 4         | 0.43%   |
| Microdia Integrated Webcam                                                 | 4         | 0.43%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 4         | 0.43%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 4         | 0.43%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 0.43%   |
| IMC Networks HD Camera                                                     | 4         | 0.43%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 0.43%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 4         | 0.43%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 0.43%   |
| Chicony Integrated Camera [ThinkPad]                                       | 4         | 0.43%   |
| Chicony EasyCamera                                                         | 4         | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101                       | 4         | 0.43%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 4         | 0.43%   |
| Apple Built-in iSight                                                      | 4         | 0.43%   |
| Alcor Micro USB 2.0 Camera                                                 | 4         | 0.43%   |
| Acer ThinkPad Integrated Camera                                            | 4         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 70        | 34.65%  |
| Synaptics                  | 62        | 30.69%  |
| Shenzhen Goodix Technology | 31        | 15.35%  |
| Upek                       | 13        | 6.44%   |
| AuthenTec                  | 10        | 4.95%   |
| LighTuning Technology      | 8         | 3.96%   |
| Elan Microelectronics      | 5         | 2.48%   |
| STMicroelectronics         | 3         | 1.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 13.37%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 26        | 12.87%  |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 8.42%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 7.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 14        | 6.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 5.94%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 4.46%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 3.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 3.47%   |
| Unknown                                                                    | 6         | 2.97%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.48%   |
| Elan ELAN:Fingerprint                                                      | 5         | 2.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.98%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.49%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.49%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.49%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.49%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.99%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.99%   |
| Synaptics  WBDI                                                            | 2         | 0.99%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.99%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.99%   |
| Validity Sensors VFS491                                                    | 1         | 0.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.5%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.5%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.5%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.5%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.5%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.5%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.5%    |
| AuthenTec AES1600                                                          | 1         | 0.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 39        | 37.86%  |
| Broadcom                  | 30        | 29.13%  |
| Upek                      | 14        | 13.59%  |
| Lenovo                    | 9         | 8.74%   |
| O2 Micro                  | 5         | 4.85%   |
| Aladdin Knowledge Systems | 2         | 1.94%   |
| SCM Microsystems          | 1         | 0.97%   |
| OmniKey                   | 1         | 0.97%   |
| Gemalto (was Gemplus)     | 1         | 0.97%   |
| Cherry                    | 1         | 0.97%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 39        | 37.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 13.59%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 8.74%   |
| Broadcom 5880                                                                | 9         | 8.74%   |
| Broadcom 58200                                                               | 8         | 7.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 5.83%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 5.83%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.85%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.94%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.97%   |
| OmniKey CardMan 4321                                                         | 1         | 0.97%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.97%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.97%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 613       | 50.62%  |
| 1     | 482       | 39.8%   |
| 2     | 91        | 7.51%   |
| 3     | 23        | 1.9%    |
| 4     | 2         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 201       | 28.23%  |
| Multimedia controller    | 164       | 23.03%  |
| Graphics card            | 154       | 21.63%  |
| Chipcard                 | 92        | 12.92%  |
| Net/wireless             | 46        | 6.46%   |
| Bluetooth                | 17        | 2.39%   |
| Communication controller | 10        | 1.4%    |
| Storage                  | 7         | 0.98%   |
| Card reader              | 5         | 0.7%    |
| Network                  | 3         | 0.42%   |
| Net/ethernet             | 3         | 0.42%   |
| Camera                   | 3         | 0.42%   |
| Flash memory             | 2         | 0.28%   |
| Unassigned class         | 1         | 0.14%   |
| Tv card                  | 1         | 0.14%   |
| Sound                    | 1         | 0.14%   |
| Modem                    | 1         | 0.14%   |
| Firewire controller      | 1         | 0.14%   |

