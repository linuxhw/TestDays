OpenMandriva 23.03 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.03.

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

Total: 665

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 339A                        | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| Dell          | 0D883F A06                  | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| GuoGuang      | IC2M1028V-J                 | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Acer          | Predator G3600              | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| ASUSTek       | P8H61-M LX2                 | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| HP            | 09E0h                       | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| HP            | 8169                        | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| Kraftway      | KWH510                      | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| HP            | 2B34                        | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| ASRock        | Z790 Taichi Carrara         | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| HP            | 822A                        | [8cf8694f03](https://linux-hardware.org/?probe=8cf8694f03) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| Acer          | EQ45LM                      | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| HP            | 8265                        | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-P                | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| ASRock        | B150M Pro4                  | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| HP            | 8643 SMVB                   | [697cc43136](https://linux-hardware.org/?probe=697cc43136) | Jun 04, 2023 |
| Acer          | Veriton X4630G V:1.0        | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| Foxconn       | G41MD                       | [f988a585c9](https://linux-hardware.org/?probe=f988a585c9) | Jun 04, 2023 |
| ASUSTek       | Pro B550M-C                 | [094889a0e2](https://linux-hardware.org/?probe=094889a0e2) | Jun 03, 2023 |
| ECS           | G31T-M                      | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [f22933cdb1](https://linux-hardware.org/?probe=f22933cdb1) | Jun 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| OEM           | Intel H81                   | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| ASUSTek       | P5G41T-M LX3                | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| ASRock        | H310CM-HG4                  | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | 82F2 A01                    | [fb729f1358](https://linux-hardware.org/?probe=fb729f1358) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | P67A-GD65                   | [fe5e3bcd7b](https://linux-hardware.org/?probe=fe5e3bcd7b) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASUSTek       | H81M-C                      | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| ASRock        | G41M-VS3                    | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| ASRock        | B450M Steel Legend          | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| Gateway       | DT55                        | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| ASUSTek       | F2A85-V PRO                 | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| Dell          | 0TP412                      | [112fa3015f](https://linux-hardware.org/?probe=112fa3015f) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| MSI           | B560M PRO-VDH               | [b0435ce0dc](https://linux-hardware.org/?probe=b0435ce0dc) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| MSI           | B450 TOMAHAWK               | [3e9709dc25](https://linux-hardware.org/?probe=3e9709dc25) | May 27, 2023 |
| MSI           | B250M BAZOOKA               | [2bfe50d945](https://linux-hardware.org/?probe=2bfe50d945) | May 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [5977804b94](https://linux-hardware.org/?probe=5977804b94) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [5d54a10d85](https://linux-hardware.org/?probe=5d54a10d85) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | [313c8a3663](https://linux-hardware.org/?probe=313c8a3663) | May 26, 2023 |
| Acer          | EQ45LM                      | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| Acer          | Aspire M3910                | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| MSI           | Z590 PLUS                   | [1f531f4e58](https://linux-hardware.org/?probe=1f531f4e58) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Dell          | 0XJ8C4 A00                  | [b6b7396e06](https://linux-hardware.org/?probe=b6b7396e06) | May 25, 2023 |
| ASUSTek       | PRIME H510M-E               | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| Gigabyte      | 8I945GZME-RH                | [3b4c63eddb](https://linux-hardware.org/?probe=3b4c63eddb) | May 24, 2023 |
| Intel         | H61                         | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| Unknown       | Unknown                     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| Foxconn       | G41MD                       | [a3a8a67867](https://linux-hardware.org/?probe=a3a8a67867) | May 23, 2023 |
| BESSTAR Te... | HM90                        | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| HP            | 2AF3                        | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| ASRock        | H310M-STX                   | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | [0ef682fa85](https://linux-hardware.org/?probe=0ef682fa85) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| ASRock        | Q1900M                      | [0290a65c70](https://linux-hardware.org/?probe=0290a65c70) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASRock        | Z68 Pro3-M                  | [0deaff38f5](https://linux-hardware.org/?probe=0deaff38f5) | May 21, 2023 |
| Unknown       | Unknown                     | [c3af6442c9](https://linux-hardware.org/?probe=c3af6442c9) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| Foxconn       | G41MD                       | [1a649b0512](https://linux-hardware.org/?probe=1a649b0512) | May 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| ASUSTek       | PRIME Z790-P                | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Gigabyte      | GA-970A-D3                  | [b30dee1244](https://linux-hardware.org/?probe=b30dee1244) | May 18, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| Maxtang       | FP650 V1.0                  | [8f1eba846a](https://linux-hardware.org/?probe=8f1eba846a) | May 16, 2023 |
| Foxconn       | P35A01                      | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | [652d9e0fa9](https://linux-hardware.org/?probe=652d9e0fa9) | May 15, 2023 |
| Gigabyte      | B360M DS3H                  | [eee39f2f10](https://linux-hardware.org/?probe=eee39f2f10) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | 8436                        | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Dell          | 0KRC95 A02                  | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Inventec      | D CLASS A02                 | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Intel         | H61                         | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | 0A58h                       | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| MSI           | MEG X570 GODLIKE            | [989d8eef43](https://linux-hardware.org/?probe=989d8eef43) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| ASUSTek       | PRIME A320M-E               | [8376015b15](https://linux-hardware.org/?probe=8376015b15) | May 10, 2023 |
| Intel         | X58M                        | [666b002908](https://linux-hardware.org/?probe=666b002908) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [8f7bcc525d](https://linux-hardware.org/?probe=8f7bcc525d) | May 10, 2023 |
| ASUSTek       | P8H77-V                     | [f86702afcf](https://linux-hardware.org/?probe=f86702afcf) | May 10, 2023 |
| HP            | 304Ah                       | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| Acer          | EG43M                       | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| ASRock        | B450M Steel Legend          | [53d91dca3c](https://linux-hardware.org/?probe=53d91dca3c) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [acf61a6132](https://linux-hardware.org/?probe=acf61a6132) | May 08, 2023 |
| Dell          | 0T656F A01                  | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | [47388f4553](https://linux-hardware.org/?probe=47388f4553) | May 08, 2023 |
| Pegatron      | NARRA5                      | [46a87a6448](https://linux-hardware.org/?probe=46a87a6448) | May 07, 2023 |
| Dell          | 0R230R A00                  | [16611a8ed6](https://linux-hardware.org/?probe=16611a8ed6) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| MSI           | H110M PRO-VH                | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| Unknown       | Unknown                     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [895855ed9a](https://linux-hardware.org/?probe=895855ed9a) | May 07, 2023 |
| Gigabyte      | H470M K                     | [655bbe4068](https://linux-hardware.org/?probe=655bbe4068) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [f3ea9b926d](https://linux-hardware.org/?probe=f3ea9b926d) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| ASUSTek       | P5G41T-M LE                 | [d5456946bb](https://linux-hardware.org/?probe=d5456946bb) | May 06, 2023 |
| ASRock        | G41C-GS                     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| ASRock        | Q270 Pro BTC+               | [4fc3d2c86f](https://linux-hardware.org/?probe=4fc3d2c86f) | May 05, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [09bd22441b](https://linux-hardware.org/?probe=09bd22441b) | May 05, 2023 |
| Foxconn       | H61MXV/H67MXV               | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6f2b69becc](https://linux-hardware.org/?probe=6f2b69becc) | May 05, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| Dell          | 0PU052                      | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| ASRock        | Z590 Steel Legend           | [d36cec198b](https://linux-hardware.org/?probe=d36cec198b) | May 04, 2023 |
| Gigabyte      | H410M H                     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | H81M-H                      | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [2dabac74e0](https://linux-hardware.org/?probe=2dabac74e0) | May 03, 2023 |
| Acer          | H57M01                      | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Unknown       | 1.0                         | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| HP            | 3031h                       | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [00dc63bf78](https://linux-hardware.org/?probe=00dc63bf78) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| HP            | 3033h                       | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| HP            | 3648h                       | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| Dell          | 06D7TR A00                  | [e7905065dd](https://linux-hardware.org/?probe=e7905065dd) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| Gigabyte      | Z77M-D3H                    | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| T-bao         | MINI PC V1.0                | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Intel         | H61                         | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| Dell          | 0773VG A02                  | [a684ad4938](https://linux-hardware.org/?probe=a684ad4938) | Apr 29, 2023 |
| ASRock        | A320M-DVS R4.0              | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| MSI           | H81M-P33                    | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASRock        | H510M-HDV R2.0              | [91930613cb](https://linux-hardware.org/?probe=91930613cb) | Apr 27, 2023 |
| MSI           | A78M-E35 V2                 | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| ASUSTek       | PRIME B250M-C               | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| Biostar       | H610MH                      | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| Intel         | H81                         | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| HP            | 83E2                        | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [8a0cd0bb6e](https://linux-hardware.org/?probe=8a0cd0bb6e) | Apr 26, 2023 |
| MSI           | B250M PRO-VH                | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| ASUSTek       | J1800I-C                    | [0a58f3fa51](https://linux-hardware.org/?probe=0a58f3fa51) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| ASUSTek       | P7P55D-E                    | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| ASRock        | X570 Taichi                 | [0842334fa2](https://linux-hardware.org/?probe=0842334fa2) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Gigabyte      | GA-970A-UD3                 | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | Z170-K                      | [538ebf1f96](https://linux-hardware.org/?probe=538ebf1f96) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| ASUSTek       | P8H77-I                     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| Fujitsu       | FJNB037                     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| Gigabyte      | B75M-HD3                    | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| HP            | 18E5                        | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | F2A85-V                     | [422eb87f07](https://linux-hardware.org/?probe=422eb87f07) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| ASRock        | P43DE                       | [8f2c0ecc69](https://linux-hardware.org/?probe=8f2c0ecc69) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| MSI           | B550-A PRO                  | [f2fc6a5da5](https://linux-hardware.org/?probe=f2fc6a5da5) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Acer          | Aspire XC-710 V:1.1         | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| ASUSTek       | P5K SE                      | [eeff4cd84c](https://linux-hardware.org/?probe=eeff4cd84c) | Apr 20, 2023 |
| Gigabyte      | H81N                        | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| Intel         | H61S                        | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| HP            | 18E4                        | [1bd96a017f](https://linux-hardware.org/?probe=1bd96a017f) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | [9c7e865b56](https://linux-hardware.org/?probe=9c7e865b56) | Apr 19, 2023 |
| ECS           | BSW-MINI                    | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| MSI           | 0B58h                       | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| HP            | 8309                        | [d82a6a4488](https://linux-hardware.org/?probe=d82a6a4488) | Apr 19, 2023 |
| MSI           | MS-7235                     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Biostar       | A960D+V2                    | [34c47b4141](https://linux-hardware.org/?probe=34c47b4141) | Apr 18, 2023 |
| MSI           | B450 TOMAHAWK               | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| NEC Comput... | MS-7451VM                   | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| ASUSTek       | P5QC                        | [7d47aa511b](https://linux-hardware.org/?probe=7d47aa511b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [dc707578c9](https://linux-hardware.org/?probe=dc707578c9) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| Acer          | FQ965M MP                   | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| HP            | 18E9                        | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [8944559c50](https://linux-hardware.org/?probe=8944559c50) | Apr 17, 2023 |
| HP            | 1850                        | [fa2fa68792](https://linux-hardware.org/?probe=fa2fa68792) | Apr 17, 2023 |
| HP            | 8062                        | [a2558d47e8](https://linux-hardware.org/?probe=a2558d47e8) | Apr 17, 2023 |
| ASRock        | H61M-DGS R2.0               | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| ASRock        | X99 Extreme4                | [e375be2ea6](https://linux-hardware.org/?probe=e375be2ea6) | Apr 17, 2023 |
| Medion        | MS-7728                     | [1da2d605db](https://linux-hardware.org/?probe=1da2d605db) | Apr 16, 2023 |
| Acer          | Aspire X3950                | [5a9abbd85f](https://linux-hardware.org/?probe=5a9abbd85f) | Apr 16, 2023 |
| MSI           | H310M PRO-VDH               | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0134b33f82](https://linux-hardware.org/?probe=0134b33f82) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| ASRock        | B650M PG Riptide            | [71643d03ec](https://linux-hardware.org/?probe=71643d03ec) | Apr 16, 2023 |
| ASUSTek       | PRIME H410M-E               | [fedecfd9ff](https://linux-hardware.org/?probe=fedecfd9ff) | Apr 16, 2023 |
| Foxconn       | ALOE                        | [702f958604](https://linux-hardware.org/?probe=702f958604) | Apr 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| Foxconn       | 2A8C                        | [8a75d034c7](https://linux-hardware.org/?probe=8a75d034c7) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [83d43e489d](https://linux-hardware.org/?probe=83d43e489d) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [82abb09c06](https://linux-hardware.org/?probe=82abb09c06) | Apr 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | [a359e8f3ea](https://linux-hardware.org/?probe=a359e8f3ea) | Apr 15, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [8a5b5b102c](https://linux-hardware.org/?probe=8a5b5b102c) | Apr 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3741318176](https://linux-hardware.org/?probe=3741318176) | Apr 14, 2023 |
| HP            | 1791                        | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | 1589                        | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| Gigabyte      | Z77M-D3H                    | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| Gigabyte      | H61M-HD2                    | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| HP            | 1998                        | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| HP            | 805D                        | [f12230e709](https://linux-hardware.org/?probe=f12230e709) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| Gigabyte      | H310M S2H x.x               | [203aeef6a1](https://linux-hardware.org/?probe=203aeef6a1) | Apr 12, 2023 |
| Gigabyte      | B450M DS3H V2               | [63c52bc5db](https://linux-hardware.org/?probe=63c52bc5db) | Apr 12, 2023 |
| ABIT          | NF-M2S                      | [30e3a2e8c4](https://linux-hardware.org/?probe=30e3a2e8c4) | Apr 11, 2023 |
| ASUSTek       | P5LD2-X/1333                | [e0e655f63c](https://linux-hardware.org/?probe=e0e655f63c) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| HP            | 805B                        | [591658775d](https://linux-hardware.org/?probe=591658775d) | Apr 11, 2023 |
| MSI           | B450M MORTAR MAX            | [e2cffb810b](https://linux-hardware.org/?probe=e2cffb810b) | Apr 10, 2023 |
| Biostar       | H61MHV                      | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| ASRock        | B550M-ITX/ac                | [e043c1c94c](https://linux-hardware.org/?probe=e043c1c94c) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| HP            | 3032h                       | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| Biostar       | H81MHV3L                    | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| Biostar       | A320MH                      | [a2aef00c0c](https://linux-hardware.org/?probe=a2aef00c0c) | Apr 09, 2023 |
| MACHINIST     | X99-k9 V1.0                 | [650acc25ef](https://linux-hardware.org/?probe=650acc25ef) | Apr 09, 2023 |
| ASRock        | Q1900M                      | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| Pegatron      | 2A73h                       | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| ECS           | H61H2-M17                   | [a2860baaee](https://linux-hardware.org/?probe=a2860baaee) | Apr 09, 2023 |
| HP            | 1998                        | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| Dell          | 0TTDMJ A00                  | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| ASUSTek       | B85M-E                      | [fe9976de62](https://linux-hardware.org/?probe=fe9976de62) | Apr 09, 2023 |
| Gigabyte      | H370 HD3-CF                 | [b2c9afc61f](https://linux-hardware.org/?probe=b2c9afc61f) | Apr 09, 2023 |
| MSI           | B350M MORTAR                | [03960a3def](https://linux-hardware.org/?probe=03960a3def) | Apr 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| Unknown       | Unknown                     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Dell          | 0Y2MRG A01                  | [d512dee0ba](https://linux-hardware.org/?probe=d512dee0ba) | Apr 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4644a0ea43](https://linux-hardware.org/?probe=4644a0ea43) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| SYWZ          | S210H Series                | [5989537064](https://linux-hardware.org/?probe=5989537064) | Apr 09, 2023 |
| AZW           | U59                         | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| ASRock        | B150 Combo                  | [c4acc08020](https://linux-hardware.org/?probe=c4acc08020) | Apr 09, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | [e579aabfdb](https://linux-hardware.org/?probe=e579aabfdb) | Apr 09, 2023 |
| Dell          | 0PU052                      | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| Intel         | DH67BL AAG10189-207         | [1f13dff346](https://linux-hardware.org/?probe=1f13dff346) | Apr 08, 2023 |
| MSI           | B350 PC MATE                | [5c6c535e4d](https://linux-hardware.org/?probe=5c6c535e4d) | Apr 08, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| HP            | 1459                        | [201dc05036](https://linux-hardware.org/?probe=201dc05036) | Apr 08, 2023 |
| ASRock        | 4X4-R1000                   | [56af110ee1](https://linux-hardware.org/?probe=56af110ee1) | Apr 08, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [e1d6888ead](https://linux-hardware.org/?probe=e1d6888ead) | Apr 08, 2023 |
| Gigabyte      | GA-73PVM-S2                 | [2149d942b3](https://linux-hardware.org/?probe=2149d942b3) | Apr 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e657bedde3](https://linux-hardware.org/?probe=e657bedde3) | Apr 08, 2023 |
| ASUSTek       | A88XM-A                     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [4b4e5dfe24](https://linux-hardware.org/?probe=4b4e5dfe24) | Apr 08, 2023 |
| ASUSTek       | P5K                         | [ea3489709c](https://linux-hardware.org/?probe=ea3489709c) | Apr 08, 2023 |
| Gigabyte      | B450M S2H                   | [f08d8d6bbd](https://linux-hardware.org/?probe=f08d8d6bbd) | Apr 08, 2023 |
| MSI           | B550M-A PRO                 | [e3fcf877c0](https://linux-hardware.org/?probe=e3fcf877c0) | Apr 08, 2023 |
| Acer          | Aspire X3990                | [4d4816d6f8](https://linux-hardware.org/?probe=4d4816d6f8) | Apr 08, 2023 |
| ASRock        | 960GC-GS FX                 | [90cb74d9f0](https://linux-hardware.org/?probe=90cb74d9f0) | Apr 08, 2023 |
| ASRock        | 970 Pro3 R2.0               | [375bb1794b](https://linux-hardware.org/?probe=375bb1794b) | Apr 08, 2023 |
| ASUSTek       | A68HM-K                     | [55d971a67f](https://linux-hardware.org/?probe=55d971a67f) | Apr 08, 2023 |
| Lenovo        | No DPK                      | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c2132caa73](https://linux-hardware.org/?probe=c2132caa73) | Apr 08, 2023 |
| Biostar       | A520MH                      | [9cf296886b](https://linux-hardware.org/?probe=9cf296886b) | Apr 07, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [fa161c8db8](https://linux-hardware.org/?probe=fa161c8db8) | Apr 07, 2023 |
| ASRock        | B360M/OEM                   | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| ASUSTek       | H110M-R                     | [d4e3e5d85c](https://linux-hardware.org/?probe=d4e3e5d85c) | Apr 07, 2023 |
| Dell          | 0KRC95 A01                  | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| ASRock        | H97M Pro4                   | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | B75M-D3H                    | [bf0c0bb982](https://linux-hardware.org/?probe=bf0c0bb982) | Apr 07, 2023 |
| HP            | 82A2                        | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Gigabyte      | Z77M-D3H                    | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| Alienware     | 0TYR0X A01                  | [35c94d7cd4](https://linux-hardware.org/?probe=35c94d7cd4) | Apr 07, 2023 |
| ASRock        | Z370 Taichi                 | [49aced4300](https://linux-hardware.org/?probe=49aced4300) | Apr 07, 2023 |
| MSI           | KA790GX                     | [c3dfb7614d](https://linux-hardware.org/?probe=c3dfb7614d) | Apr 07, 2023 |
| HP            | 1998                        | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Biostar       | G41D3                       | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| ASUSTek       | P8H61-M LX                  | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| Dell          | 04GJJT A00                  | [5c7df0085d](https://linux-hardware.org/?probe=5c7df0085d) | Apr 06, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [4a0aa9f6d0](https://linux-hardware.org/?probe=4a0aa9f6d0) | Apr 06, 2023 |
| MSI           | J1800I                      | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| Dell          | 0HD5W2 A01                  | [294131b150](https://linux-hardware.org/?probe=294131b150) | Apr 06, 2023 |
| Biostar       | G31D-M7                     | [9d1a5129bd](https://linux-hardware.org/?probe=9d1a5129bd) | Apr 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| MSI           | A88XM-E35 V2                | [bf4c16404e](https://linux-hardware.org/?probe=bf4c16404e) | Apr 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [122c9d0ae2](https://linux-hardware.org/?probe=122c9d0ae2) | Apr 06, 2023 |
| ASUSTek       | A68HM-E                     | [0c9ae9bcd7](https://linux-hardware.org/?probe=0c9ae9bcd7) | Apr 06, 2023 |
| eMachines     | EL1352                      | [ccd83551e0](https://linux-hardware.org/?probe=ccd83551e0) | Apr 06, 2023 |
| ASUSTek       | P5B                         | [a2a4936e2c](https://linux-hardware.org/?probe=a2a4936e2c) | Apr 06, 2023 |
| Gigabyte      | Z690 UD DDR4                | [7644d4a8fa](https://linux-hardware.org/?probe=7644d4a8fa) | Apr 06, 2023 |
| Dell          | 0HHV7N A00                  | [73cc9e48a0](https://linux-hardware.org/?probe=73cc9e48a0) | Apr 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [8b92d25f91](https://linux-hardware.org/?probe=8b92d25f91) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| Dell          | 0GXM1W A02                  | [3fae5e4d5c](https://linux-hardware.org/?probe=3fae5e4d5c) | Apr 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [0893f3016e](https://linux-hardware.org/?probe=0893f3016e) | Apr 05, 2023 |
| Gigabyte      | X570 GAMING X               | [83132b245e](https://linux-hardware.org/?probe=83132b245e) | Apr 05, 2023 |
| Dell          | 0HN7XN A01                  | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| HP            | 3397                        | [2c3fa64234](https://linux-hardware.org/?probe=2c3fa64234) | Apr 05, 2023 |
| Gigabyte      | H97-HD3                     | [caf5563d44](https://linux-hardware.org/?probe=caf5563d44) | Apr 05, 2023 |
| Acer          | Aspire XC-330               | [a0e2b31c08](https://linux-hardware.org/?probe=a0e2b31c08) | Apr 05, 2023 |
| Acer          | EG31M R01-C3                | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [0e7d453676](https://linux-hardware.org/?probe=0e7d453676) | Apr 05, 2023 |
| Gigabyte      | F2A75M-HD2                  | [04694eb1f9](https://linux-hardware.org/?probe=04694eb1f9) | Apr 05, 2023 |
| MSI           | B150 PC MATE                | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | [62bdbae29c](https://linux-hardware.org/?probe=62bdbae29c) | Apr 05, 2023 |
| HP            | 2AA2                        | [28c42fc95f](https://linux-hardware.org/?probe=28c42fc95f) | Apr 05, 2023 |
| ASRock        | B75 Pro3-M                  | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| Gigabyte      | GA-A75M-UD2H                | [7f4b812a58](https://linux-hardware.org/?probe=7f4b812a58) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | [41a5c82c1e](https://linux-hardware.org/?probe=41a5c82c1e) | Apr 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [59d486f5bd](https://linux-hardware.org/?probe=59d486f5bd) | Apr 05, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [4505cd8ddc](https://linux-hardware.org/?probe=4505cd8ddc) | Apr 05, 2023 |
| ASUSTek       | PRIME B360M-K               | [caa685db91](https://linux-hardware.org/?probe=caa685db91) | Apr 05, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | [9fc5c6f8a7](https://linux-hardware.org/?probe=9fc5c6f8a7) | Apr 05, 2023 |
| Dell          | 0V8WGR A02                  | [3b8d266671](https://linux-hardware.org/?probe=3b8d266671) | Apr 05, 2023 |
| HP            | 18E5                        | [71c68a2c6a](https://linux-hardware.org/?probe=71c68a2c6a) | Apr 05, 2023 |
| ASRock        | H61MV-ITX                   | [c721707e0a](https://linux-hardware.org/?probe=c721707e0a) | Apr 05, 2023 |
| MSI           | MS-7529                     | [2c6cdf6397](https://linux-hardware.org/?probe=2c6cdf6397) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f43197a66f](https://linux-hardware.org/?probe=f43197a66f) | Apr 04, 2023 |
| ASUSTek       | A68HM-PLUS                  | [4246e4df2b](https://linux-hardware.org/?probe=4246e4df2b) | Apr 04, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [9885a8adee](https://linux-hardware.org/?probe=9885a8adee) | Apr 04, 2023 |
| MSI           | Z390-A PRO                  | [60583d2cb0](https://linux-hardware.org/?probe=60583d2cb0) | Apr 04, 2023 |
| Acer          | Aspire M1470                | [d0120a6452](https://linux-hardware.org/?probe=d0120a6452) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| ASUSTek       | PRIME A320M-C R2.0          | [70b2a73996](https://linux-hardware.org/?probe=70b2a73996) | Apr 04, 2023 |
| Dell          | 040DDP A00                  | [af03c6afe4](https://linux-hardware.org/?probe=af03c6afe4) | Apr 04, 2023 |
| Lenovo        | 3140 NOK                    | [207d400267](https://linux-hardware.org/?probe=207d400267) | Apr 04, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | [89962b2435](https://linux-hardware.org/?probe=89962b2435) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| ECS           | Iris8                       | [f86927f9ff](https://linux-hardware.org/?probe=f86927f9ff) | Apr 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| Intel         | B75                         | [8d116f68cf](https://linux-hardware.org/?probe=8d116f68cf) | Apr 04, 2023 |
| Dell          | 0D6H9T A01                  | [dd49afbf3f](https://linux-hardware.org/?probe=dd49afbf3f) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8db8b523f3](https://linux-hardware.org/?probe=8db8b523f3) | Apr 04, 2023 |
| ASUSTek       | PRIME Q270M-C               | [a3d5910e8e](https://linux-hardware.org/?probe=a3d5910e8e) | Apr 04, 2023 |
| ASRock        | FM2A68M-DG3+                | [47c6d88922](https://linux-hardware.org/?probe=47c6d88922) | Apr 03, 2023 |
| MSI           | H81M-E33                    | [34b04c305a](https://linux-hardware.org/?probe=34b04c305a) | Apr 03, 2023 |
| ASRock        | A55M-HVS                    | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [08612f7258](https://linux-hardware.org/?probe=08612f7258) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [65668a06ad](https://linux-hardware.org/?probe=65668a06ad) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [2cbd354a8f](https://linux-hardware.org/?probe=2cbd354a8f) | Apr 03, 2023 |
| Pegatron      | JESSE                       | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| ASUSTek       | H61M-K                      | [f4b76d1e01](https://linux-hardware.org/?probe=f4b76d1e01) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| MSI           | B450M MORTAR MAX            | [53ace0533c](https://linux-hardware.org/?probe=53ace0533c) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [07089aebf5](https://linux-hardware.org/?probe=07089aebf5) | Apr 02, 2023 |
| Lenovo        | ThinkCentre M91p 4518RH1    | [ead0ecfb3a](https://linux-hardware.org/?probe=ead0ecfb3a) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| HP            | 2215                        | [9e43555613](https://linux-hardware.org/?probe=9e43555613) | Apr 02, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [f9d9946012](https://linux-hardware.org/?probe=f9d9946012) | Apr 02, 2023 |
| ASRock        | Q1900M                      | [dfae44d3f6](https://linux-hardware.org/?probe=dfae44d3f6) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [f46913bb86](https://linux-hardware.org/?probe=f46913bb86) | Apr 02, 2023 |
| MSI           | H510M-A PRO                 | [f580fda8f1](https://linux-hardware.org/?probe=f580fda8f1) | Apr 02, 2023 |
| MSI           | FM2-A75IA-E53               | [f8092c0da9](https://linux-hardware.org/?probe=f8092c0da9) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [d0006b7678](https://linux-hardware.org/?probe=d0006b7678) | Apr 02, 2023 |
| HP            | 2AF3                        | [fe33aa7257](https://linux-hardware.org/?probe=fe33aa7257) | Apr 02, 2023 |
| MSI           | A320M-A PRO MAX             | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| Gigabyte      | H410M S2 V3                 | [b908036588](https://linux-hardware.org/?probe=b908036588) | Apr 02, 2023 |
| HP            | 3397                        | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| ASUSTek       | B150M-K D3                  | [08df6b50be](https://linux-hardware.org/?probe=08df6b50be) | Apr 02, 2023 |
| Dell          | 096JG8 A01                  | [d016e78eab](https://linux-hardware.org/?probe=d016e78eab) | Apr 02, 2023 |
| Dell          | 0GDG8Y A02                  | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| ULTRATOP      | C2017-LIVA-ZE               | [96d0c389b8](https://linux-hardware.org/?probe=96d0c389b8) | Apr 02, 2023 |
| Acer          | EQ45LM                      | [5bafe47784](https://linux-hardware.org/?probe=5bafe47784) | Apr 02, 2023 |
| Intel         | B75                         | [caad7f240a](https://linux-hardware.org/?probe=caad7f240a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [7ccbfd0fd3](https://linux-hardware.org/?probe=7ccbfd0fd3) | Apr 02, 2023 |
| Dell          | 02YYK5 A01                  | [ecfba44652](https://linux-hardware.org/?probe=ecfba44652) | Apr 02, 2023 |
| Unknown       | Unknown                     | [089fc02d40](https://linux-hardware.org/?probe=089fc02d40) | Apr 01, 2023 |
| Nvidia        | MCP7A 2                     | [26ab83ffcb](https://linux-hardware.org/?probe=26ab83ffcb) | Apr 01, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [d645276b0a](https://linux-hardware.org/?probe=d645276b0a) | Apr 01, 2023 |
| Acer          | RS880M05                    | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [4f9739adf7](https://linux-hardware.org/?probe=4f9739adf7) | Apr 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Gigabyte      | H410M DS2V                  | [67b081e859](https://linux-hardware.org/?probe=67b081e859) | Apr 01, 2023 |
| Gigabyte      | Z68X-UD4-B3                 | [79bcb88c5b](https://linux-hardware.org/?probe=79bcb88c5b) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| Biostar       | H61MLV                      | [db9714357e](https://linux-hardware.org/?probe=db9714357e) | Apr 01, 2023 |
| ASUSTek       | PRIME Z490-P                | [bbbfbb2dfc](https://linux-hardware.org/?probe=bbbfbb2dfc) | Apr 01, 2023 |
| Intel         | DB75EN AAG39650-303         | [50d4a766a6](https://linux-hardware.org/?probe=50d4a766a6) | Apr 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [3f218796ae](https://linux-hardware.org/?probe=3f218796ae) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | [a4cad34ac9](https://linux-hardware.org/?probe=a4cad34ac9) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [da86fa8f75](https://linux-hardware.org/?probe=da86fa8f75) | Apr 01, 2023 |
| MSI           | MEG X670E ACE               | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [091d2eda88](https://linux-hardware.org/?probe=091d2eda88) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Gigabyte      | MZGLKDP-00                  | [c9427f4873](https://linux-hardware.org/?probe=c9427f4873) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| ASRock        | B460M Pro4                  | [1f3b96d1a0](https://linux-hardware.org/?probe=1f3b96d1a0) | Apr 01, 2023 |
| Acer          | Aspire XC-780               | [206239c162](https://linux-hardware.org/?probe=206239c162) | Apr 01, 2023 |
| MSI           | H97M-G43                    | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [86241cd6ad](https://linux-hardware.org/?probe=86241cd6ad) | Apr 01, 2023 |
| HP            | 304Ah                       | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| HP            | 84FD                        | [79367d5f7d](https://linux-hardware.org/?probe=79367d5f7d) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [ad3ead1116](https://linux-hardware.org/?probe=ad3ead1116) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [16f87cd333](https://linux-hardware.org/?probe=16f87cd333) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [d774a892d1](https://linux-hardware.org/?probe=d774a892d1) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Dell          | 0M5DCD A00                  | [91cc314380](https://linux-hardware.org/?probe=91cc314380) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| HP            | 8053                        | [6c887800bb](https://linux-hardware.org/?probe=6c887800bb) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| Pegatron      | 2AC2                        | [ca0b0464d7](https://linux-hardware.org/?probe=ca0b0464d7) | Apr 01, 2023 |
| Dell          | 04YP6J A02                  | [0223f7bb3e](https://linux-hardware.org/?probe=0223f7bb3e) | Mar 31, 2023 |
| ECS           | GeForce 8000 series         | [32e951a2ca](https://linux-hardware.org/?probe=32e951a2ca) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9e09a54915](https://linux-hardware.org/?probe=9e09a54915) | Mar 31, 2023 |
| ASRock        | Z87 Extreme6                | [675d214cbe](https://linux-hardware.org/?probe=675d214cbe) | Mar 31, 2023 |
| Dell          | 0JP3NX A00                  | [016632c560](https://linux-hardware.org/?probe=016632c560) | Mar 31, 2023 |
| MSI           | H81M-P33                    | [e2442d5cac](https://linux-hardware.org/?probe=e2442d5cac) | Mar 31, 2023 |
| Gigabyte      | Z77-DS3H                    | [79e2cfa0f1](https://linux-hardware.org/?probe=79e2cfa0f1) | Mar 31, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a025953f4c](https://linux-hardware.org/?probe=a025953f4c) | Mar 31, 2023 |
| Dell          | 0WMJ54 A00                  | [d11328af2a](https://linux-hardware.org/?probe=d11328af2a) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | [ab4f36e0fa](https://linux-hardware.org/?probe=ab4f36e0fa) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [c27e3be5ba](https://linux-hardware.org/?probe=c27e3be5ba) | Mar 31, 2023 |
| Dell          | 0HMX8D A01                  | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| MSI           | Z270-A PRO                  | [a5d218b9a6](https://linux-hardware.org/?probe=a5d218b9a6) | Mar 31, 2023 |
| Gigabyte      | Z68XP-UD3                   | [029afd6a5c](https://linux-hardware.org/?probe=029afd6a5c) | Mar 31, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [6bd60aa5f0](https://linux-hardware.org/?probe=6bd60aa5f0) | Mar 31, 2023 |
| ASUSTek       | P8Z77-V                     | [498726ce78](https://linux-hardware.org/?probe=498726ce78) | Mar 31, 2023 |
| Dell          | 042P49 A02                  | [46dc3b9655](https://linux-hardware.org/?probe=46dc3b9655) | Mar 31, 2023 |
| Medion        | MS-7728                     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| ASUSTek       | H110M-R                     | [bd1a48e47d](https://linux-hardware.org/?probe=bd1a48e47d) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a0f5608b2](https://linux-hardware.org/?probe=7a0f5608b2) | Mar 31, 2023 |
| ASRock        | Z97 Anniversary             | [c23aeb60ba](https://linux-hardware.org/?probe=c23aeb60ba) | Mar 31, 2023 |
| HP            | 3397                        | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| HP            | 1998                        | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| ASRock        | H61M                        | [29327171c4](https://linux-hardware.org/?probe=29327171c4) | Mar 31, 2023 |
| HP            | 8767 A                      | [186bad76b7](https://linux-hardware.org/?probe=186bad76b7) | Mar 31, 2023 |
| Gigabyte      | H310M A-CF                  | [c26786d423](https://linux-hardware.org/?probe=c26786d423) | Mar 31, 2023 |
| ASUSTek       | H97-PLUS                    | [5f163f6a24](https://linux-hardware.org/?probe=5f163f6a24) | Mar 31, 2023 |
| ASUSTek       | UN65U                       | [70d0f8f069](https://linux-hardware.org/?probe=70d0f8f069) | Mar 31, 2023 |
| Gigabyte      | EP43-DS3L                   | [b7594db73b](https://linux-hardware.org/?probe=b7594db73b) | Mar 31, 2023 |
| ASUSTek       | PRIME J4005I-C              | [193d27ceac](https://linux-hardware.org/?probe=193d27ceac) | Mar 31, 2023 |
| MSI           | H110M PRO-VH PLUS           | [0992e2d8d8](https://linux-hardware.org/?probe=0992e2d8d8) | Mar 31, 2023 |
| OEM_MB        | NARRA3                      | [75050a4d2e](https://linux-hardware.org/?probe=75050a4d2e) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX3                | [6ff0a3cb3f](https://linux-hardware.org/?probe=6ff0a3cb3f) | Mar 31, 2023 |
| Foxconn       | 2ABF                        | [8daf4bf0a5](https://linux-hardware.org/?probe=8daf4bf0a5) | Mar 30, 2023 |
| ASRock        | H310CM-HDV                  | [a9a41a38ed](https://linux-hardware.org/?probe=a9a41a38ed) | Mar 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [3670f0a6ed](https://linux-hardware.org/?probe=3670f0a6ed) | Mar 30, 2023 |
| HP            | 843F                        | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| ASRock        | 970 Extreme3                | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| Gigabyte      | P41T-D3P                    | [c8cadc8a94](https://linux-hardware.org/?probe=c8cadc8a94) | Mar 30, 2023 |
| DFI           | LP UT X58                   | [cd706d90d3](https://linux-hardware.org/?probe=cd706d90d3) | Mar 30, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| MSI           | Z370-A PRO                  | [9aba047596](https://linux-hardware.org/?probe=9aba047596) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| Intel         | B75A                        | [b7b1423f34](https://linux-hardware.org/?probe=b7b1423f34) | Mar 30, 2023 |
| Biostar       | B550MX/E PRO                | [cffcb0a2a6](https://linux-hardware.org/?probe=cffcb0a2a6) | Mar 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ad1392d8c0](https://linux-hardware.org/?probe=ad1392d8c0) | Mar 30, 2023 |
| HP            | 82B4                        | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| Dell          | 0T7D40 A01                  | [dc44647f41](https://linux-hardware.org/?probe=dc44647f41) | Mar 30, 2023 |
| ASUSTek       | B85M-E                      | [7c7f9d0e36](https://linux-hardware.org/?probe=7c7f9d0e36) | Mar 30, 2023 |
| Packard Be... | FIH57                       | [f1336c6cc4](https://linux-hardware.org/?probe=f1336c6cc4) | Mar 30, 2023 |
| Pegatron      | 2ADC                        | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| Packard Be... | MCP73PV                     | [2082d90602](https://linux-hardware.org/?probe=2082d90602) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [393fc00a5d](https://linux-hardware.org/?probe=393fc00a5d) | Mar 30, 2023 |
| ASUSTek       | P8H77-V                     | [1869e23c56](https://linux-hardware.org/?probe=1869e23c56) | Mar 30, 2023 |
| MSI           | H97 PC Mate                 | [37c098e51a](https://linux-hardware.org/?probe=37c098e51a) | Mar 30, 2023 |
| ASRock        | B85M Pro4                   | [d237bcc0a2](https://linux-hardware.org/?probe=d237bcc0a2) | Mar 30, 2023 |
| Shuttle       | FH270                       | [83c990d212](https://linux-hardware.org/?probe=83c990d212) | Mar 30, 2023 |
| MSI           | H81M-P33                    | [4606b5b93d](https://linux-hardware.org/?probe=4606b5b93d) | Mar 29, 2023 |
| Dell          | 042P49 A01                  | [9a4f4be1ab](https://linux-hardware.org/?probe=9a4f4be1ab) | Mar 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [fb2605e6fa](https://linux-hardware.org/?probe=fb2605e6fa) | Mar 29, 2023 |
| Dell          | 0TP412                      | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [599577c3b4](https://linux-hardware.org/?probe=599577c3b4) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | 0T2HR0 A02                  | [bf959f65d2](https://linux-hardware.org/?probe=bf959f65d2) | Mar 29, 2023 |
| Gigabyte      | B550M DS3H                  | [612dd1dba2](https://linux-hardware.org/?probe=612dd1dba2) | Mar 29, 2023 |
| Lenovo        | 30D2 NOK                    | [e4d898e37d](https://linux-hardware.org/?probe=e4d898e37d) | Mar 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [634c2e1e74](https://linux-hardware.org/?probe=634c2e1e74) | Mar 29, 2023 |
| WinFast       | 6100M2MA FAB1.0             | [bed481b8ce](https://linux-hardware.org/?probe=bed481b8ce) | Mar 28, 2023 |
| MSI           | B450-A PRO MAX              | [f3ebf80a3d](https://linux-hardware.org/?probe=f3ebf80a3d) | Mar 28, 2023 |
| Gigabyte      | H310M S2 x.x                | [21504643b4](https://linux-hardware.org/?probe=21504643b4) | Mar 28, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [4807db08a9](https://linux-hardware.org/?probe=4807db08a9) | Mar 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ad5969356b](https://linux-hardware.org/?probe=ad5969356b) | Mar 28, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [1c14b29af5](https://linux-hardware.org/?probe=1c14b29af5) | Mar 28, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [16db0eb166](https://linux-hardware.org/?probe=16db0eb166) | Mar 28, 2023 |
| ASUSTek       | P5G41T-M LX                 | [3f2f66842c](https://linux-hardware.org/?probe=3f2f66842c) | Mar 28, 2023 |
| Dell          | 0R5KF8 A03                  | [decf0f5193](https://linux-hardware.org/?probe=decf0f5193) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| Lenovo        | ThinkStation S30 0568E8G    | [ea3855cca5](https://linux-hardware.org/?probe=ea3855cca5) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| ASRock        | X470 Taichi                 | [79d0ee9715](https://linux-hardware.org/?probe=79d0ee9715) | Mar 28, 2023 |
| ASUSTek       | PRIME X570-P                | [8234cd55a8](https://linux-hardware.org/?probe=8234cd55a8) | Mar 28, 2023 |
| Intel         | H61                         | [56437a0e05](https://linux-hardware.org/?probe=56437a0e05) | Mar 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [6b4122e888](https://linux-hardware.org/?probe=6b4122e888) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| Acer          | Predator G3-605             | [8caea0f833](https://linux-hardware.org/?probe=8caea0f833) | Mar 27, 2023 |
| ASRock        | Z77 Extreme6                | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [8d039976c9](https://linux-hardware.org/?probe=8d039976c9) | Mar 27, 2023 |
| Pegatron      | 2AD5                        | [502ff745d4](https://linux-hardware.org/?probe=502ff745d4) | Mar 27, 2023 |
| ASUSTek       | PRIME Z590-P                | [ab55adbf68](https://linux-hardware.org/?probe=ab55adbf68) | Mar 27, 2023 |
| Gigabyte      | H81M-H                      | [709242697d](https://linux-hardware.org/?probe=709242697d) | Mar 27, 2023 |
| HP            | 1998                        | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| Dell          | 0G919G A00                  | [139207e1a7](https://linux-hardware.org/?probe=139207e1a7) | Mar 27, 2023 |
| Lenovo        | 102F NO DPK                 | [85a4bbf301](https://linux-hardware.org/?probe=85a4bbf301) | Mar 27, 2023 |
| ASUSTek       | P7H55                       | [40158bca43](https://linux-hardware.org/?probe=40158bca43) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [a71ced0077](https://linux-hardware.org/?probe=a71ced0077) | Mar 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| ASRock        | A320M-HDV                   | [9685e81600](https://linux-hardware.org/?probe=9685e81600) | Mar 27, 2023 |
| Gigabyte      | H87M-D3H                    | [b277bc971f](https://linux-hardware.org/?probe=b277bc971f) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LK                  | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | [943075edf7](https://linux-hardware.org/?probe=943075edf7) | Mar 27, 2023 |
| Unknown       | Unknown                     | [ecf55ab179](https://linux-hardware.org/?probe=ecf55ab179) | Mar 27, 2023 |
| Gigabyte      | G31M-ES2C                   | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| HP            | 844C                        | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| Unknown       | 1.0                         | [e09cc1385b](https://linux-hardware.org/?probe=e09cc1385b) | Mar 27, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8af0f96567](https://linux-hardware.org/?probe=8af0f96567) | Mar 27, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [9064f6704d](https://linux-hardware.org/?probe=9064f6704d) | Mar 27, 2023 |
| ASUSTek       | Z97-K R2.0                  | [b1e1f4d711](https://linux-hardware.org/?probe=b1e1f4d711) | Mar 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [2077f4f3ab](https://linux-hardware.org/?probe=2077f4f3ab) | Mar 27, 2023 |
| HP            | 8704                        | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [83448b2d9b](https://linux-hardware.org/?probe=83448b2d9b) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [8decb2b6c4](https://linux-hardware.org/?probe=8decb2b6c4) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| ASUSTek       | P8H67                       | [3b9e638ecb](https://linux-hardware.org/?probe=3b9e638ecb) | Mar 26, 2023 |
| PCWare        | IPMH61R3                    | [2fbd1f3f64](https://linux-hardware.org/?probe=2fbd1f3f64) | Mar 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [b527095c8c](https://linux-hardware.org/?probe=b527095c8c) | Mar 26, 2023 |
| Chuwi         | RZBOX                       | [14ef8add03](https://linux-hardware.org/?probe=14ef8add03) | Mar 26, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| Gigabyte      | H310N                       | [33a905038c](https://linux-hardware.org/?probe=33a905038c) | Mar 24, 2023 |
| Gigabyte      | M52S-S3P                    | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| Dell          | 0NK5PH A00                  | [f76bc64ee4](https://linux-hardware.org/?probe=f76bc64ee4) | Mar 24, 2023 |
| MSI           | B450M PRO-M2 MAX            | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| Gigabyte      | A520I AC                    | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| Dell          | 0F6X5P A00                  | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| ASUSTek       | PRIME H510M-E               | [8c46e42391](https://linux-hardware.org/?probe=8c46e42391) | Mar 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [32d80303b6](https://linux-hardware.org/?probe=32d80303b6) | Mar 20, 2023 |
| HP            | 3646h                       | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| ASUSTek       | M51BC                       | [65db0797b0](https://linux-hardware.org/?probe=65db0797b0) | Mar 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [727e5c46b7](https://linux-hardware.org/?probe=727e5c46b7) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d8004fdcde](https://linux-hardware.org/?probe=d8004fdcde) | Mar 18, 2023 |
| Dell          | 07N90W A02                  | [267dad60ba](https://linux-hardware.org/?probe=267dad60ba) | Mar 18, 2023 |
| HP            | 1589                        | [5c483a16fc](https://linux-hardware.org/?probe=5c483a16fc) | Mar 18, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [452349c032](https://linux-hardware.org/?probe=452349c032) | Mar 17, 2023 |
| Lenovo        | ThinkCentre A58 7522M4J     | [ba0a303be5](https://linux-hardware.org/?probe=ba0a303be5) | Mar 17, 2023 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [14c33dda50](https://linux-hardware.org/?probe=14c33dda50) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [293b961af2](https://linux-hardware.org/?probe=293b961af2) | Mar 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [e89d2059c0](https://linux-hardware.org/?probe=e89d2059c0) | Mar 16, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c7a98e4c15](https://linux-hardware.org/?probe=c7a98e4c15) | Mar 16, 2023 |
| OEM           | B85 JHS359                  | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| Biostar       | A10N-8800E                  | [1f081ed675](https://linux-hardware.org/?probe=1f081ed675) | Mar 16, 2023 |
| Gigabyte      | B550 VISION D-P             | [4707dc8ed6](https://linux-hardware.org/?probe=4707dc8ed6) | Mar 15, 2023 |
| Packard Be... | IMEDIA S3840                | [b54abceafe](https://linux-hardware.org/?probe=b54abceafe) | Mar 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [05da6b812c](https://linux-hardware.org/?probe=05da6b812c) | Mar 13, 2023 |
| ASUSTek       | A88X-PLUS                   | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [c5950249eb](https://linux-hardware.org/?probe=c5950249eb) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| Dell          | 0G2DM9 A02                  | [e6d8fa1563](https://linux-hardware.org/?probe=e6d8fa1563) | Mar 10, 2023 |
| Acer          | Veriton X4640G V:1.1        | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [349f7731c8](https://linux-hardware.org/?probe=349f7731c8) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [38cb86265f](https://linux-hardware.org/?probe=38cb86265f) | Mar 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [2891c31951](https://linux-hardware.org/?probe=2891c31951) | Mar 06, 2023 |
| Dell          | 06D7TR A00                  | [375809fb93](https://linux-hardware.org/?probe=375809fb93) | Mar 06, 2023 |
| Dell          | 0VRWRC A00                  | [4810cd01e3](https://linux-hardware.org/?probe=4810cd01e3) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Gigabyte      | H370 HD3-CF                 | [30365cbef7](https://linux-hardware.org/?probe=30365cbef7) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| MSI           | MS-6702E                    | [e17662e6c0](https://linux-hardware.org/?probe=e17662e6c0) | Mar 05, 2023 |
| Foxconn       | 2A8C                        | [1cf53baf99](https://linux-hardware.org/?probe=1cf53baf99) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| HP            | 8062                        | [b3adfec9fb](https://linux-hardware.org/?probe=b3adfec9fb) | Mar 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.03/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 6.2.6-desktop-1omv2390      | 621      | 93.95%  |
| 6.2.2-desktop-1omv2390      | 19       | 2.87%   |
| 6.1.1-desktop-1omv2290      | 9        | 1.36%   |
| 6.2.1-desktop-1omv2390      | 4        | 0.61%   |
| 5.16.13-desktop-1omv4003    | 3        | 0.45%   |
| 6.1.4-desktop-1omv2301      | 2        | 0.3%    |
| 6.3.5-desktop-3omv2390      | 1        | 0.15%   |
| 6.2.8-desktop-1omv2390      | 1        | 0.15%   |
| 6.2.10-desktop-2.0omv4.9mjn | 1        | 0.15%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2.6   | 621      | 93.95%  |
| 6.2.2   | 19       | 2.87%   |
| 6.1.1   | 9        | 1.36%   |
| 6.2.1   | 4        | 0.61%   |
| 5.16.13 | 3        | 0.45%   |
| 6.1.4   | 2        | 0.3%    |
| 6.3.5   | 1        | 0.15%   |
| 6.2.8   | 1        | 0.15%   |
| 6.2.10  | 1        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.2     | 646      | 97.73%  |
| 6.1     | 11       | 1.66%   |
| 5.16    | 3        | 0.45%   |
| 6.3     | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 661      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 563      | 85.17%  |
| GNOME    | 53       | 8.02%   |
| LXQt     | 40       | 6.05%   |
| Cinnamon | 2        | 0.3%    |
| Budgie   | 2        | 0.3%    |
| Unknown  | 1        | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 607      | 91.83%  |
| Wayland | 54       | 8.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 606      | 91.68%  |
| GDM     | 53       | 8.02%   |
| LightDM | 1        | 0.15%   |
| Unknown | 1        | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 304      | 45.99%  |
| de_DE | 62       | 9.38%   |
| ru_RU | 55       | 8.32%   |
| fr_FR | 36       | 5.45%   |
| en_GB | 28       | 4.24%   |
| pt_BR | 23       | 3.48%   |
| it_IT | 19       | 2.87%   |
| pl_PL | 18       | 2.72%   |
| en_CA | 16       | 2.42%   |
| es_ES | 15       | 2.27%   |
| en_AU | 11       | 1.66%   |
| es_MX | 9        | 1.36%   |
| hu_HU | 8        | 1.21%   |
| de_AT | 8        | 1.21%   |
| ja_JP | 6        | 0.91%   |
| es_VE | 6        | 0.91%   |
| cs_CZ | 6        | 0.91%   |
| nl_NL | 4        | 0.61%   |
| fr_CA | 4        | 0.61%   |
| en_IN | 4        | 0.61%   |
| de_CH | 4        | 0.61%   |
| es_AR | 3        | 0.45%   |
| fr_BE | 2        | 0.3%    |
| UTF-8 | 1        | 0.15%   |
| tr_TR | 1        | 0.15%   |
| sk_SK | 1        | 0.15%   |
| pt_PT | 1        | 0.15%   |
| es_UY | 1        | 0.15%   |
| es_DO | 1        | 0.15%   |
| es_CO | 1        | 0.15%   |
| en_ZA | 1        | 0.15%   |
| en_SG | 1        | 0.15%   |
| da_DK | 1        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 353      | 53.4%   |
| BIOS | 308      | 46.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 360      | 54.46%  |
| Overlay | 259      | 39.18%  |
| Btrfs   | 29       | 4.39%   |
| Xfs     | 9        | 1.36%   |
| Ext3    | 2        | 0.3%    |
| Jfs     | 1        | 0.15%   |
| F2fs    | 1        | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 515      | 77.91%  |
| MBR  | 146      | 22.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 363      | 54.92%  |
| No        | 298      | 45.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 344      | 52.04%  |
| No        | 317      | 47.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 137      | 20.73%  |
| Gigabyte Technology                  | 109      | 16.49%  |
| MSI                                  | 74       | 11.2%   |
| Dell                                 | 59       | 8.93%   |
| ASRock                               | 57       | 8.62%   |
| Hewlett-Packard                      | 53       | 8.02%   |
| Lenovo                               | 35       | 5.3%    |
| Acer                                 | 20       | 3.03%   |
| Intel                                | 15       | 2.27%   |
| Fujitsu                              | 13       | 1.97%   |
| Biostar                              | 11       | 1.66%   |
| Foxconn                              | 10       | 1.51%   |
| Fujitsu Siemens                      | 8        | 1.21%   |
| Unknown                              | 8        | 1.21%   |
| ECS                                  | 7        | 1.06%   |
| Pegatron                             | 6        | 0.91%   |
| Packard Bell                         | 3        | 0.45%   |
| Medion                               | 3        | 0.45%   |
| OEM                                  | 2        | 0.3%    |
| GuoGuang                             | 2        | 0.3%    |
| Alienware                            | 2        | 0.3%    |
| Wistron                              | 1        | 0.15%   |
| WinFast                              | 1        | 0.15%   |
| ULTRATOP                             | 1        | 0.15%   |
| T-bao                                | 1        | 0.15%   |
| SYWZ                                 | 1        | 0.15%   |
| Shuttle                              | 1        | 0.15%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.15%   |
| PCWare                               | 1        | 0.15%   |
| OEM_MB                               | 1        | 0.15%   |
| Nvidia                               | 1        | 0.15%   |
| NEC Computers                        | 1        | 0.15%   |
| MouseComputer                        | 1        | 0.15%   |
| Maxtang                              | 1        | 0.15%   |
| MACHINIST                            | 1        | 0.15%   |
| Lanix                                | 1        | 0.15%   |
| Kraftway                             | 1        | 0.15%   |
| Inventec                             | 1        | 0.15%   |
| Gateway                              | 1        | 0.15%   |
| EPoX Computer                        | 1        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 8        | 1.21%   |
| Dell OptiPlex 7010               | 7        | 1.06%   |
| ASUS PRIME A320M-K               | 7        | 1.06%   |
| ASUS All Series                  | 7        | 1.06%   |
| Gigabyte Z77M-D3H                | 6        | 0.91%   |
| MSI MS-7C02                      | 5        | 0.76%   |
| MSI MS-7817                      | 4        | 0.61%   |
| Intel H61                        | 4        | 0.61%   |
| HP EliteDesk 800 G1 SFF          | 4        | 0.61%   |
| Dell OptiPlex 3020               | 4        | 0.61%   |
| MSI MS-7C56                      | 3        | 0.45%   |
| MSI MS-7B86                      | 3        | 0.45%   |
| HP Compaq Elite 8300 SFF         | 3        | 0.45%   |
| Foxconn G41MD                    | 3        | 0.45%   |
| Dell OptiPlex 990                | 3        | 0.45%   |
| Dell OptiPlex 9020               | 3        | 0.45%   |
| Dell OptiPlex 390                | 3        | 0.45%   |
| ASUS PRIME Z590-P                | 3        | 0.45%   |
| ASRock Q1900M                    | 3        | 0.45%   |
| Acer Veriton L670G               | 3        | 0.45%   |
| MSI MS-7D54                      | 2        | 0.3%    |
| MSI MS-7C91                      | 2        | 0.3%    |
| MSI MS-7C09                      | 2        | 0.3%    |
| MSI MS-7B89                      | 2        | 0.3%    |
| MSI MS-7B84                      | 2        | 0.3%    |
| MSI MS-7B79                      | 2        | 0.3%    |
| MSI MS-7A15                      | 2        | 0.3%    |
| MSI MS-7971                      | 2        | 0.3%    |
| MSI MS-7850                      | 2        | 0.3%    |
| MSI MS-7721                      | 2        | 0.3%    |
| Medion MS-7728                   | 2        | 0.3%    |
| Intel B75                        | 2        | 0.3%    |
| HP Z420 Workstation              | 2        | 0.3%    |
| HP ProDesk 400 G3 SFF            | 2        | 0.3%    |
| HP EliteDesk 800 G1 USDT         | 2        | 0.3%    |
| HP Compaq 8100 Elite SFF PC      | 2        | 0.3%    |
| GuoGuang IC2M1028V-J             | 2        | 0.3%    |
| Gigabyte X470 AORUS ULTRA GAMING | 2        | 0.3%    |
| Gigabyte H81M-H                  | 2        | 0.3%    |
| Gigabyte H370HD3                 | 2        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| Dell OptiPlex           | 41       | 6.2%    |
| ASUS PRIME              | 37       | 5.6%    |
| Lenovo ThinkCentre      | 18       | 2.72%   |
| HP Compaq               | 15       | 2.27%   |
| HP EliteDesk            | 13       | 1.97%   |
| ASUS ROG                | 11       | 1.66%   |
| Dell Precision          | 10       | 1.51%   |
| ASUS TUF                | 10       | 1.51%   |
| Acer Aspire             | 10       | 1.51%   |
| Fujitsu ESPRIMO         | 9        | 1.36%   |
| Lenovo IdeaCentre       | 8        | 1.21%   |
| Acer Veriton            | 8        | 1.21%   |
| Unknown                 | 8        | 1.21%   |
| HP ProDesk              | 7        | 1.06%   |
| ASUS All                | 7        | 1.06%   |
| Gigabyte Z77M-D3H       | 6        | 0.91%   |
| Gigabyte B550           | 6        | 0.91%   |
| MSI MS-7C02             | 5        | 0.76%   |
| Fujitsu Siemens ESPRIMO | 5        | 0.76%   |
| MSI MS-7817             | 4        | 0.61%   |
| Lenovo ThinkStation     | 4        | 0.61%   |
| Intel H61               | 4        | 0.61%   |
| Gigabyte X570           | 4        | 0.61%   |
| Gigabyte H310M          | 4        | 0.61%   |
| Gigabyte B450M          | 4        | 0.61%   |
| Dell Vostro             | 4        | 0.61%   |
| ASUS P8Z77-V            | 4        | 0.61%   |
| ASUS P8H61-M            | 4        | 0.61%   |
| ASUS M5A78L-M           | 4        | 0.61%   |
| Packard Bell IMEDIA     | 3        | 0.45%   |
| MSI MS-7C56             | 3        | 0.45%   |
| MSI MS-7B86             | 3        | 0.45%   |
| HP Pavilion             | 3        | 0.45%   |
| HP OMEN                 | 3        | 0.45%   |
| Gigabyte H410M          | 3        | 0.45%   |
| Gigabyte GA-78LMT-USB3  | 3        | 0.45%   |
| Gigabyte B550M          | 3        | 0.45%   |
| Gigabyte B450           | 3        | 0.45%   |
| Foxconn G41MD           | 3        | 0.45%   |
| ASUS Pro                | 3        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 62       | 9.38%   |
| 2013 | 58       | 8.77%   |
| 2019 | 54       | 8.17%   |
| 2020 | 50       | 7.56%   |
| 2018 | 50       | 7.56%   |
| 2021 | 47       | 7.11%   |
| 2017 | 47       | 7.11%   |
| 2011 | 44       | 6.66%   |
| 2010 | 40       | 6.05%   |
| 2014 | 39       | 5.9%    |
| 2016 | 33       | 4.99%   |
| 2009 | 29       | 4.39%   |
| 2015 | 28       | 4.24%   |
| 2008 | 27       | 4.08%   |
| 2022 | 26       | 3.93%   |
| 2007 | 13       | 1.97%   |
| 2006 | 9        | 1.36%   |
| 2023 | 3        | 0.45%   |
| 2005 | 2        | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 661      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 661      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 661      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 165      | 24.96%  |
| 4.01-8.0        | 146      | 22.09%  |
| 8.01-16.0       | 134      | 20.27%  |
| 3.01-4.0        | 97       | 14.67%  |
| 32.01-64.0      | 68       | 10.29%  |
| 24.01-32.0      | 16       | 2.42%   |
| 64.01-256.0     | 16       | 2.42%   |
| 1.01-2.0        | 9        | 1.36%   |
| 2.01-3.0        | 8        | 1.21%   |
| More than 256.0 | 1        | 0.15%   |
| 0.51-1.0        | 1        | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 426      | 64.45%  |
| 2.01-3.0  | 167      | 25.26%  |
| 0.51-1.0  | 28       | 4.24%   |
| 3.01-4.0  | 26       | 3.93%   |
| 4.01-8.0  | 8        | 1.21%   |
| 0.01-0.5  | 5        | 0.76%   |
| 8.01-16.0 | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 247      | 37.37%  |
| 2      | 202      | 30.56%  |
| 3      | 96       | 14.52%  |
| 4      | 61       | 9.23%   |
| 5      | 27       | 4.08%   |
| 6      | 9        | 1.36%   |
| 0      | 9        | 1.36%   |
| 8      | 4        | 0.61%   |
| 7      | 4        | 0.61%   |
| 13     | 1        | 0.15%   |
| 9      | 1        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 336      | 50.83%  |
| Yes       | 325      | 49.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 653      | 98.79%  |
| No        | 8        | 1.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 396      | 59.91%  |
| Yes       | 265      | 40.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 476      | 72.01%  |
| Yes       | 185      | 27.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 77       | 11.65%  |
| Germany     | 72       | 10.89%  |
| Russia      | 56       | 8.47%   |
| Brazil      | 40       | 6.05%   |
| France      | 39       | 5.9%    |
| Canada      | 30       | 4.54%   |
| Italy       | 26       | 3.93%   |
| Poland      | 25       | 3.78%   |
| UK          | 24       | 3.63%   |
| Japan       | 23       | 3.48%   |
| Spain       | 17       | 2.57%   |
| Australia   | 16       | 2.42%   |
| India       | 12       | 1.82%   |
| Hungary     | 10       | 1.51%   |
| Finland     | 10       | 1.51%   |
| Venezuela   | 8        | 1.21%   |
| Netherlands | 8        | 1.21%   |
| Czechia     | 8        | 1.21%   |
| Austria     | 8        | 1.21%   |
| Malaysia    | 7        | 1.06%   |
| Argentina   | 7        | 1.06%   |
| Sweden      | 6        | 0.91%   |
| Mexico      | 6        | 0.91%   |
| Greece      | 6        | 0.91%   |
| China       | 6        | 0.91%   |
| Switzerland | 5        | 0.76%   |
| Portugal    | 5        | 0.76%   |
| Indonesia   | 5        | 0.76%   |
| Denmark     | 5        | 0.76%   |
| Belarus     | 5        | 0.76%   |
| Taiwan      | 4        | 0.61%   |
| Slovenia    | 4        | 0.61%   |
| Slovakia    | 4        | 0.61%   |
| Romania     | 4        | 0.61%   |
| Puerto Rico | 4        | 0.61%   |
| Chile       | 4        | 0.61%   |
| Bulgaria    | 4        | 0.61%   |
| Algeria     | 4        | 0.61%   |
| Vietnam     | 3        | 0.45%   |
| Ukraine     | 3        | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 11       | 1.66%   |
| Kuala Lumpur      | 7        | 1.06%   |
| Vienna            | 6        | 0.91%   |
| Helsinki          | 6        | 0.91%   |
| Montreal          | 5        | 0.76%   |
| Milan             | 5        | 0.76%   |
| Berlin            | 5        | 0.76%   |
| Sydney            | 4        | 0.61%   |
| St Petersburg     | 4        | 0.61%   |
| Rio de Janeiro    | 4        | 0.61%   |
| New Taipei        | 4        | 0.61%   |
| Hamburg           | 4        | 0.61%   |
| Glasgow           | 4        | 0.61%   |
| Brisbane          | 4        | 0.61%   |
| Athens            | 4        | 0.61%   |
| Warsaw            | 3        | 0.45%   |
| Santiago          | 3        | 0.45%   |
| Pescara           | 3        | 0.45%   |
| Les Sorinieres    | 3        | 0.45%   |
| Hanover           | 3        | 0.45%   |
| Caracas           | 3        | 0.45%   |
| Budapest          | 3        | 0.45%   |
| Baku              | 3        | 0.45%   |
| Yoshkar-Ola       | 2        | 0.3%    |
| Yokohama          | 2        | 0.3%    |
| Yekaterinburg     | 2        | 0.3%    |
| Wroclaw           | 2        | 0.3%    |
| Winnipeg          | 2        | 0.3%    |
| Waldkirch         | 2        | 0.3%    |
| Vitebsk           | 2        | 0.3%    |
| Vigia             | 2        | 0.3%    |
| Umeda             | 2        | 0.3%    |
| Uberlândia       | 2        | 0.3%    |
| Tula              | 2        | 0.3%    |
| Tua Chua          | 2        | 0.3%    |
| Tel Aviv          | 2        | 0.3%    |
| Târgu Mureş     | 2        | 0.3%    |
| St. Jean Baptiste | 2        | 0.3%    |
| Santo Domingo     | 2        | 0.3%    |
| San Juan          | 2        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 220      | 286    | 18.09%  |
| Seagate             | 208      | 243    | 17.11%  |
| Samsung Electronics | 121      | 166    | 9.95%   |
| Kingston            | 92       | 114    | 7.57%   |
| Crucial             | 69       | 80     | 5.67%   |
| Toshiba             | 67       | 72     | 5.51%   |
| SanDisk             | 49       | 58     | 4.03%   |
| Hitachi             | 36       | 40     | 2.96%   |
| SPCC                | 28       | 33     | 2.3%    |
| A-DATA Technology   | 25       | 27     | 2.06%   |
| China               | 23       | 25     | 1.89%   |
| PNY                 | 18       | 19     | 1.48%   |
| Intel               | 15       | 15     | 1.23%   |
| HGST                | 15       | 16     | 1.23%   |
| Unknown             | 13       | 15     | 1.07%   |
| Patriot             | 12       | 12     | 0.99%   |
| Maxtor              | 11       | 11     | 0.9%    |
| XPG                 | 9        | 11     | 0.74%   |
| Micron Technology   | 8        | 8      | 0.66%   |
| Transcend           | 6        | 6      | 0.49%   |
| Team                | 6        | 6      | 0.49%   |
| SABRENT             | 6        | 6      | 0.49%   |
| Netac               | 6        | 7      | 0.49%   |
| KingSpec            | 6        | 6      | 0.49%   |
| GOODRAM             | 6        | 6      | 0.49%   |
| Gigabyte Technology | 6        | 6      | 0.49%   |
| Corsair             | 6        | 6      | 0.49%   |
| Apacer              | 6        | 7      | 0.49%   |
| Silicon Motion      | 5        | 5      | 0.41%   |
| Phison              | 5        | 6      | 0.41%   |
| KIOXIA-EXCERIA      | 5        | 5      | 0.41%   |
| OCZ                 | 4        | 6      | 0.33%   |
| LITEON              | 4        | 4      | 0.33%   |
| JMicron Technology  | 4        | 4      | 0.33%   |
| Intenso             | 4        | 5      | 0.33%   |
| SK hynix            | 3        | 3      | 0.25%   |
| Hewlett-Packard     | 3        | 3      | 0.25%   |
| Unknown             | 3        | 4      | 0.25%   |
| XrayDisk            | 2        | 2      | 0.16%   |
| WD MediaMax         | 2        | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 21       | 1.52%   |
| Toshiba DT01ACA100 1TB           | 19       | 1.38%   |
| Kingston SA400S37240G 240GB SSD  | 17       | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB   | 12       | 0.87%   |
| Seagate ST2000DM008-2FR102 2TB   | 11       | 0.8%    |
| Kingston SA400S37120G 120GB SSD  | 11       | 0.8%    |
| Crucial CT500MX500SSD1 500GB     | 11       | 0.8%    |
| Crucial CT240BX500SSD1 240GB     | 11       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB         | 9        | 0.65%   |
| Seagate ST3500418AS 500GB        | 9        | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB   | 9        | 0.65%   |
| Samsung SSD 860 EVO 250GB        | 9        | 0.65%   |
| Kingston SA400S37480G 480GB SSD  | 9        | 0.65%   |
| Unknown SD/MMC/MS PRO 64GB       | 8        | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB     | 8        | 0.58%   |
| WDC WD5000AAKX-75U6AA0 500GB     | 7        | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB      | 7        | 0.51%   |
| Seagate ST3500414CS 500GB        | 7        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB   | 7        | 0.51%   |
| Kingston SV300S37A120G 120GB SSD | 7        | 0.51%   |
| Crucial CT480BX500SSD1 480GB     | 7        | 0.51%   |
| WDC WD2500AAKX-753CA1 250GB      | 6        | 0.43%   |
| WDC WD10EZEX-60WN4A0 1TB         | 6        | 0.43%   |
| Toshiba DT01ACA050 500GB         | 6        | 0.43%   |
| Samsung SSD 860 EVO 500GB        | 6        | 0.43%   |
| Samsung SSD 850 EVO 250GB        | 6        | 0.43%   |
| Kingston SA2000M8500G 500GB      | 6        | 0.43%   |
| Hitachi HDS721010CLA332 1TB      | 6        | 0.43%   |
| XPG GAMMIX S11 Pro 512GB         | 5        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5        | 0.36%   |
| Toshiba DT01ACA200 2TB           | 5        | 0.36%   |
| SPCC Solid State Disk 512GB      | 5        | 0.36%   |
| SPCC Solid State Disk 256GB      | 5        | 0.36%   |
| SPCC Solid State Disk 1TB        | 5        | 0.36%   |
| SPCC Solid State Disk 128GB      | 5        | 0.36%   |
| SPCC M.2 PCIe SSD 256GB          | 5        | 0.36%   |
| Seagate ST3320418AS 320GB        | 5        | 0.36%   |
| Seagate ST31000528AS 1TB         | 5        | 0.36%   |
| Seagate ST2000DM001-1CH164 2TB   | 5        | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB   | 5        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 205      | 239    | 36.35%  |
| WDC                 | 183      | 228    | 32.45%  |
| Toshiba             | 62       | 66     | 10.99%  |
| Hitachi             | 36       | 40     | 6.38%   |
| Samsung Electronics | 32       | 36     | 5.67%   |
| HGST                | 15       | 16     | 2.66%   |
| Maxtor              | 10       | 10     | 1.77%   |
| Unknown             | 8        | 8      | 1.42%   |
| WD MediaMax         | 2        | 2      | 0.35%   |
| External            | 2        | 2      | 0.35%   |
| USB                 | 1        | 1      | 0.18%   |
| StoreJet            | 1        | 1      | 0.18%   |
| SAGE                | 1        | 1      | 0.18%   |
| SABRENT             | 1        | 1      | 0.18%   |
| RSH-319             | 1        | 1      | 0.18%   |
| QUANTUM             | 1        | 1      | 0.18%   |
| KESU                | 1        | 1      | 0.18%   |
| Intenso             | 1        | 1      | 0.18%   |
| Fujitsu             | 1        | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 67       | 83     | 13.51%  |
| Samsung Electronics | 64       | 76     | 12.9%   |
| Crucial             | 58       | 62     | 11.69%  |
| SanDisk             | 40       | 47     | 8.06%   |
| WDC                 | 38       | 44     | 7.66%   |
| SPCC                | 23       | 25     | 4.64%   |
| China               | 23       | 25     | 4.64%   |
| A-DATA Technology   | 21       | 22     | 4.23%   |
| PNY                 | 16       | 17     | 3.23%   |
| Patriot             | 12       | 12     | 2.42%   |
| Intel               | 8        | 8      | 1.61%   |
| Netac               | 6        | 7      | 1.21%   |
| SABRENT             | 5        | 5      | 1.01%   |
| KingSpec            | 5        | 5      | 1.01%   |
| GOODRAM             | 5        | 5      | 1.01%   |
| Apacer              | 5        | 5      | 1.01%   |
| Transcend           | 4        | 4      | 0.81%   |
| Toshiba             | 4        | 4      | 0.81%   |
| Team                | 4        | 4      | 0.81%   |
| OCZ                 | 4        | 6      | 0.81%   |
| Micron Technology   | 4        | 4      | 0.81%   |
| LITEON              | 4        | 4      | 0.81%   |
| Intenso             | 4        | 4      | 0.81%   |
| Gigabyte Technology | 4        | 4      | 0.81%   |
| Seagate             | 3        | 3      | 0.6%    |
| JMicron Technology  | 3        | 3      | 0.6%    |
| Unknown             | 3        | 4      | 0.6%    |
| XrayDisk            | 2        | 2      | 0.4%    |
| SUNEAST             | 2        | 2      | 0.4%    |
| PNY CS90            | 2        | 2      | 0.4%    |
| Lexar               | 2        | 2      | 0.4%    |
| KingFast            | 2        | 2      | 0.4%    |
| Emtec               | 2        | 2      | 0.4%    |
| Dogfish             | 2        | 2      | 0.4%    |
| Corsair             | 2        | 2      | 0.4%    |
| ASMT                | 2        | 2      | 0.4%    |
| ANACOMDA            | 2        | 2      | 0.4%    |
| addlink             | 2        | 2      | 0.4%    |
| ZHITAI              | 1        | 1      | 0.2%    |
| XUM                 | 1        | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 434      | 656    | 43.75%  |
| SSD     | 382      | 551    | 38.51%  |
| NVMe    | 167      | 221    | 16.83%  |
| Unknown | 7        | 9      | 0.71%   |
| MMC     | 2        | 2      | 0.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 612      | 1130   | 71.92%  |
| NVMe | 166      | 219    | 19.51%  |
| SAS  | 71       | 88     | 8.34%   |
| MMC  | 2        | 2      | 0.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 486      | 731    | 56.18%  |
| 0.51-1.0   | 249      | 318    | 28.79%  |
| 1.01-2.0   | 76       | 91     | 8.79%   |
| 2.01-3.0   | 18       | 21     | 2.08%   |
| 3.01-4.0   | 17       | 21     | 1.97%   |
| 4.01-10.0  | 12       | 17     | 1.39%   |
| 10.01-20.0 | 7        | 8      | 0.81%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 188      | 28.44%  |
| 101-250        | 138      | 20.88%  |
| 251-500        | 101      | 15.28%  |
| 501-1000       | 67       | 10.14%  |
| 51-100         | 45       | 6.81%   |
| 21-50          | 40       | 6.05%   |
| 1001-2000      | 33       | 4.99%   |
| Unknown        | 27       | 4.08%   |
| More than 3000 | 13       | 1.97%   |
| 2001-3000      | 9        | 1.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 495      | 74.89%  |
| 21-50          | 52       | 7.87%   |
| Unknown        | 27       | 4.08%   |
| 101-250        | 24       | 3.63%   |
| 251-500        | 20       | 3.03%   |
| 51-100         | 19       | 2.87%   |
| 501-1000       | 16       | 2.42%   |
| 2001-3000      | 3        | 0.45%   |
| 1001-2000      | 3        | 0.45%   |
| More than 3000 | 2        | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 11       | 11     | 4.7%    |
| WDC WD5000AAKX-75U6AA0 500GB        | 6        | 6      | 2.56%   |
| Seagate ST3500418AS 500GB           | 5        | 5      | 2.14%   |
| Hitachi HDS721010CLA332 1TB         | 5        | 5      | 2.14%   |
| WDC WD5000AAKX-001CA0 500GB         | 4        | 4      | 1.71%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 4      | 1.28%   |
| Seagate ST1000DM003-1CH162 1TB      | 3        | 3      | 1.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2        | 2      | 0.85%   |
| WDC WD3200AAKS-61L9A0 320GB         | 2        | 2      | 0.85%   |
| WDC WD20EARX-00PASB0 2TB            | 2        | 2      | 0.85%   |
| WDC WD10EARS-00Y5B1 1TB             | 2        | 2      | 0.85%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 2        | 2      | 0.85%   |
| Toshiba DT01ACA100 1TB              | 2        | 2      | 0.85%   |
| Seagate ST500LT012-9WS142 500GB     | 2        | 2      | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB     | 2        | 2      | 0.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2        | 2      | 0.85%   |
| Seagate ST3320813AS 320GB           | 2        | 2      | 0.85%   |
| Seagate ST3320418AS 320GB           | 2        | 2      | 0.85%   |
| Seagate ST3250318AS 250GB           | 2        | 2      | 0.85%   |
| Seagate ST31000528AS 1TB            | 2        | 2      | 0.85%   |
| Seagate ST31000524AS 1TB            | 2        | 2      | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB      | 2        | 2      | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 2      | 0.85%   |
| Samsung Electronics HD103SI 1TB     | 2        | 2      | 0.85%   |
| Maxtor STM380215AS 80GB             | 2        | 2      | 0.85%   |
| Kingston SV300S37A240G 240GB SSD    | 2        | 2      | 0.85%   |
| Hitachi HDS721050CLA362 500GB       | 2        | 2      | 0.85%   |
| HGST HTS725050A7E630 500GB          | 2        | 2      | 0.85%   |
| HGST HTS545050A7E380 500GB          | 2        | 2      | 0.85%   |
| China SSD 240GB                     | 2        | 2      | 0.85%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1        | 1      | 0.43%   |
| WDC WDS100T2G0A-00JH30 1TB SSD      | 1        | 1      | 0.43%   |
| WDC WD800JD-23LSA0 80GB             | 1        | 1      | 0.43%   |
| WDC WD800JD-22LSA0 80GB             | 1        | 1      | 0.43%   |
| WDC WD800JB-00JJC0 80GB             | 1        | 1      | 0.43%   |
| WDC WD800BD-22LRA0 80GB             | 1        | 1      | 0.43%   |
| WDC WD800BB-75JHC0 80GB             | 1        | 1      | 0.43%   |
| WDC WD5003ABYX-88 LEN 500GB         | 1        | 1      | 0.43%   |
| WDC WD5003ABYX-01WERA0 500GB        | 1        | 1      | 0.43%   |
| WDC WD5002ABYS-02B1B0 500GB         | 1        | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 71       | 72     | 31%     |
| WDC                 | 69       | 75     | 30.13%  |
| Samsung Electronics | 20       | 21     | 8.73%   |
| Hitachi             | 16       | 16     | 6.99%   |
| Toshiba             | 10       | 10     | 4.37%   |
| Maxtor              | 7        | 7      | 3.06%   |
| Kingston            | 6        | 6      | 2.62%   |
| HGST                | 6        | 6      | 2.62%   |
| Intel               | 3        | 3      | 1.31%   |
| Crucial             | 2        | 2      | 0.87%   |
| China               | 2        | 2      | 0.87%   |
| WD MediaMax         | 1        | 1      | 0.44%   |
| Team                | 1        | 1      | 0.44%   |
| SPCC                | 1        | 1      | 0.44%   |
| SATAFIRM            | 1        | 1      | 0.44%   |
| SanDisk             | 1        | 1      | 0.44%   |
| SAGE                | 1        | 1      | 0.44%   |
| RSH-319             | 1        | 1      | 0.44%   |
| QUANTUM             | 1        | 1      | 0.44%   |
| Patriot             | 1        | 1      | 0.44%   |
| Netac               | 1        | 1      | 0.44%   |
| KingSpec            | 1        | 1      | 0.44%   |
| Intenso             | 1        | 1      | 0.44%   |
| Hewlett-Packard     | 1        | 1      | 0.44%   |
| Fujitsu             | 1        | 1      | 0.44%   |
| Fanxiang            | 1        | 1      | 0.44%   |
| BAITITON            | 1        | 1      | 0.44%   |
| A-DATA Technology   | 1        | 1      | 0.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 71       | 72     | 36.04%  |
| WDC                 | 64       | 69     | 32.49%  |
| Samsung Electronics | 18       | 19     | 9.14%   |
| Hitachi             | 16       | 16     | 8.12%   |
| Toshiba             | 10       | 10     | 5.08%   |
| Maxtor              | 7        | 7      | 3.55%   |
| HGST                | 6        | 6      | 3.05%   |
| WD MediaMax         | 1        | 1      | 0.51%   |
| SAGE                | 1        | 1      | 0.51%   |
| RSH-319             | 1        | 1      | 0.51%   |
| QUANTUM             | 1        | 1      | 0.51%   |
| Fujitsu             | 1        | 1      | 0.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 180      | 204    | 84.51%  |
| SSD  | 30       | 30     | 14.08%  |
| NVMe | 3        | 3      | 1.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST9320423AS 320GB         | 1        | 1      | 20%     |
| Seagate ST500DM002-1BD142 500GB   | 1        | 1      | 20%     |
| Samsung Electronics HD753LJ 752GB | 1        | 1      | 20%     |
| Samsung Electronics HD252HJ 250GB | 1        | 1      | 20%     |
| Samsung Electronics HD103UJ 1TB   | 1        | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 60%     |
| Seagate             | 2        | 2      | 40%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 565      | 1118   | 67.26%  |
| Malfunc  | 204      | 237    | 24.29%  |
| Detected | 66       | 79     | 7.86%   |
| Failed   | 5        | 5      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 433      | 48.33%  |
| AMD                          | 208      | 23.21%  |
| Samsung Electronics          | 41       | 4.58%   |
| Kingston Technology Company  | 28       | 3.13%   |
| Phison Electronics           | 26       | 2.9%    |
| ASMedia Technology           | 25       | 2.79%   |
| SanDisk                      | 22       | 2.46%   |
| Nvidia                       | 17       | 1.9%    |
| Silicon Motion               | 16       | 1.79%   |
| Micron/Crucial Technology    | 15       | 1.67%   |
| Marvell Technology Group     | 11       | 1.23%   |
| ADATA Technology             | 11       | 1.23%   |
| JMicron Technology           | 10       | 1.12%   |
| VIA Technologies             | 7        | 0.78%   |
| KIOXIA                       | 5        | 0.56%   |
| Micron Technology            | 4        | 0.45%   |
| MAXIO Technology (Hangzhou)  | 4        | 0.45%   |
| Toshiba America Info Systems | 3        | 0.33%   |
| SK hynix                     | 2        | 0.22%   |
| Realtek Semiconductor        | 2        | 0.22%   |
| Broadcom / LSI               | 2        | 0.22%   |
| Silicon Image                | 1        | 0.11%   |
| Shenzhen Longsys Electronics | 1        | 0.11%   |
| Promise Technology           | 1        | 0.11%   |
| Biwin Storage Technology     | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 105      | 9.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 59       | 5.31%   |
| AMD 400 Series Chipset SATA Controller                                                  | 39       | 3.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 38       | 3.42%   |
| AMD 500 Series Chipset SATA Controller                                                  | 37       | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 36       | 3.24%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 34       | 3.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 31       | 2.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 29       | 2.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 27       | 2.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 24       | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 23       | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 23       | 2.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 22       | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19       | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19       | 1.71%   |
| AMD FCH SATA Controller D                                                               | 19       | 1.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 18       | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 17       | 1.53%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 16       | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 15       | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 13       | 1.17%   |
| Phison PS5013 E13 NVMe Controller                                                       | 12       | 1.08%   |
| Samsung NVMe SSD Controller 980                                                         | 11       | 0.99%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 11       | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 11       | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 11       | 0.99%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 10       | 0.9%    |
| Kingston Company A2000 NVMe SSD                                                         | 10       | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 10       | 0.9%    |
| Kingston Company Company Non-Volatile memory controller                                 | 9        | 0.81%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 9        | 0.81%   |
| AMD FCH IDE Controller                                                                  | 8        | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 7        | 0.63%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.63%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.63%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 7        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 531      | 60.14%  |
| NVMe | 165      | 18.69%  |
| IDE  | 159      | 18.01%  |
| RAID | 24       | 2.72%   |
| SAS  | 4        | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 439      | 66.41%  |
| AMD    | 222      | 33.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 5600G with Radeon Graphics      | 17       | 2.57%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 15       | 2.27%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 11       | 1.66%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 10       | 1.51%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10       | 1.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 9        | 1.36%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9        | 1.36%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 9        | 1.36%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 9        | 1.36%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.21%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 8        | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.21%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 7        | 1.06%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 7        | 1.06%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 7        | 1.06%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 7        | 1.06%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6        | 0.91%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 6        | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 0.91%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 6        | 0.91%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 6        | 0.91%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 5        | 0.76%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 0.76%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 5        | 0.76%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 5        | 0.76%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 5        | 0.76%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 5        | 0.76%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 5        | 0.76%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 5        | 0.76%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 5        | 0.76%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 5        | 0.76%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.76%   |
| AMD Ryzen 5 5600 6-Core Processor           | 5        | 0.76%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 0.76%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 0.76%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 5        | 0.76%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 4        | 0.61%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 4        | 0.61%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 4        | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 4        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 128      | 19.36%  |
| Intel Core i3           | 74       | 11.2%   |
| AMD Ryzen 5             | 72       | 10.89%  |
| Intel Core i7           | 71       | 10.74%  |
| Intel Core 2 Duo        | 31       | 4.69%   |
| AMD Ryzen 7             | 28       | 4.24%   |
| Other                   | 22       | 3.33%   |
| Intel Pentium           | 22       | 3.33%   |
| Intel Celeron           | 22       | 3.33%   |
| AMD FX                  | 19       | 2.87%   |
| Intel Xeon              | 18       | 2.72%   |
| Intel Core 2 Quad       | 15       | 2.27%   |
| Intel Pentium Dual-Core | 14       | 2.12%   |
| AMD A8                  | 13       | 1.97%   |
| AMD Ryzen 9             | 10       | 1.51%   |
| AMD Ryzen 3             | 10       | 1.51%   |
| AMD Athlon II X2        | 9        | 1.36%   |
| AMD Athlon              | 7        | 1.06%   |
| AMD Phenom II X6        | 6        | 0.91%   |
| AMD A4                  | 6        | 0.91%   |
| AMD A10                 | 6        | 0.91%   |
| Intel Pentium Dual      | 5        | 0.76%   |
| AMD Athlon 64 X2        | 5        | 0.76%   |
| Intel Pentium Gold      | 4        | 0.61%   |
| Intel Core 2            | 4        | 0.61%   |
| Intel Core i9           | 3        | 0.45%   |
| Intel Atom              | 3        | 0.45%   |
| AMD Ryzen 5 PRO         | 3        | 0.45%   |
| AMD PRO A10             | 3        | 0.45%   |
| AMD Athlon X4           | 3        | 0.45%   |
| AMD A6                  | 3        | 0.45%   |
| Intel Pentium 4         | 2        | 0.3%    |
| Intel Genuine           | 2        | 0.3%    |
| AMD Phenom II X4        | 2        | 0.3%    |
| AMD Phenom II X2        | 2        | 0.3%    |
| AMD Athlon II X4        | 2        | 0.3%    |
| AMD Athlon II X3        | 2        | 0.3%    |
| AMD Athlon 64           | 2        | 0.3%    |
| Intel Pentium Silver    | 1        | 0.15%   |
| AMD Sempron             | 1        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 243      | 36.76%  |
| 2      | 215      | 32.53%  |
| 6      | 109      | 16.49%  |
| 8      | 47       | 7.11%   |
| 1      | 21       | 3.18%   |
| 16     | 7        | 1.06%   |
| 3      | 7        | 1.06%   |
| 12     | 6        | 0.91%   |
| 24     | 2        | 0.3%    |
| 14     | 2        | 0.3%    |
| 10     | 2        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 659      | 99.7%   |
| 2      | 2        | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 363      | 54.92%  |
| 1      | 293      | 44.33%  |
| 4      | 3        | 0.45%   |
| 8      | 2        | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 661      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 442      | 66.87%  |
| 0x08701021 | 22       | 3.33%   |
| 0x0a50000d | 16       | 2.42%   |
| 0x08108109 | 16       | 2.42%   |
| 0x06001119 | 15       | 2.27%   |
| 0x0800820d | 12       | 1.82%   |
| 0x06003106 | 11       | 1.66%   |
| 0x06000822 | 10       | 1.51%   |
| 0x0a50000c | 9        | 1.36%   |
| 0x0a201016 | 9        | 1.36%   |
| 0x08101016 | 9        | 1.36%   |
| 0x010000c8 | 9        | 1.36%   |
| 0x0a20120a | 7        | 1.06%   |
| 0x010000bf | 6        | 0.91%   |
| 0x0600611a | 5        | 0.76%   |
| 0x0a201025 | 4        | 0.61%   |
| 0x0600081c | 4        | 0.61%   |
| 0x206a7    | 3        | 0.45%   |
| 0x08600106 | 3        | 0.45%   |
| 0x0800820b | 3        | 0.45%   |
| 0x906ea    | 2        | 0.3%    |
| 0x1067a    | 2        | 0.3%    |
| 0x08701030 | 2        | 0.3%    |
| 0x08701013 | 2        | 0.3%    |
| 0x08600103 | 2        | 0.3%    |
| 0x06006705 | 2        | 0.3%    |
| 0x06000817 | 2        | 0.3%    |
| 0x03000027 | 2        | 0.3%    |
| 0x010000c7 | 2        | 0.3%    |
| 0x010000b6 | 2        | 0.3%    |
| 0x00000000 | 2        | 0.3%    |
| 0x906eb    | 1        | 0.15%   |
| 0x906e9    | 1        | 0.15%   |
| 0x506e3    | 1        | 0.15%   |
| 0x306a9    | 1        | 0.15%   |
| 0x0a601203 | 1        | 0.15%   |
| 0x0a601201 | 1        | 0.15%   |
| 0x0a201205 | 1        | 0.15%   |
| 0x0a201204 | 1        | 0.15%   |
| 0x0a201009 | 1        | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 76       | 11.5%   |
| KabyLake         | 66       | 9.98%   |
| IvyBridge        | 54       | 8.17%   |
| Penryn           | 53       | 8.02%   |
| SandyBridge      | 51       | 7.72%   |
| Zen 3            | 49       | 7.41%   |
| Skylake          | 38       | 5.75%   |
| Zen 2            | 33       | 4.99%   |
| Piledriver       | 33       | 4.99%   |
| Zen+             | 32       | 4.84%   |
| K10              | 26       | 3.93%   |
| Core             | 21       | 3.18%   |
| CometLake        | 19       | 2.87%   |
| Zen              | 15       | 2.27%   |
| Westmere         | 12       | 1.82%   |
| Steamroller      | 11       | 1.66%   |
| Icelake          | 11       | 1.66%   |
| Nehalem          | 8        | 1.21%   |
| K8 Hammer        | 8        | 1.21%   |
| Excavator        | 8        | 1.21%   |
| Alderlake Hybrid | 8        | 1.21%   |
| Silvermont       | 7        | 1.06%   |
| K10 Llano        | 4        | 0.61%   |
| Goldmont         | 4        | 0.61%   |
| Unknown          | 3        | 0.45%   |
| Tremont          | 2        | 0.3%    |
| NetBurst         | 2        | 0.3%    |
| Goldmont plus    | 2        | 0.3%    |
| Broadwell        | 2        | 0.3%    |
| Bonnell          | 2        | 0.3%    |
| Bobcat           | 1        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Intel            | 250      | 36.71%  |
| Nvidia           | 232      | 34.07%  |
| AMD              | 197      | 28.93%  |
| S3 Graphics      | 1        | 0.15%   |
| ATI Technologies | 1        | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 42       | 6.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 31       | 4.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 29       | 4.22%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 28       | 4.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 3.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 21       | 3.06%   |
| Intel HD Graphics 530                                                       | 18       | 2.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 18       | 2.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17       | 2.47%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 15       | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 13       | 1.89%   |
| Nvidia GK208B [GeForce GT 730]                                              | 12       | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 1.46%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 10       | 1.46%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 10       | 1.46%   |
| Nvidia GK208B [GeForce GT 710]                                              | 9        | 1.31%   |
| Intel HD Graphics 630                                                       | 9        | 1.31%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 9        | 1.31%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 9        | 1.31%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 8        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 7        | 1.02%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 7        | 1.02%   |
| Nvidia GF119 [GeForce GT 610]                                               | 7        | 1.02%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.02%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 6        | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 6        | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                  | 6        | 0.87%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 6        | 0.87%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 6        | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 0.87%   |
| AMD RS880 [Radeon HD 4250]                                                  | 6        | 0.87%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 0.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5        | 0.73%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 5        | 0.73%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5        | 0.73%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 218      | 32.98%  |
| 1 x Intel                | 213      | 32.22%  |
| 1 x AMD                  | 185      | 27.99%  |
| 2 x Intel                | 20       | 3.03%   |
| Intel + Nvidia           | 10       | 1.51%   |
| Intel + AMD              | 6        | 0.91%   |
| 2 x AMD                  | 5        | 0.76%   |
| 2 x Nvidia               | 1        | 0.15%   |
| 1 x S3 Graphics          | 1        | 0.15%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.15%   |
| AMD + Nvidia             | 1        | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 613      | 92.74%  |
| Proprietary | 30       | 4.54%   |
| Unknown     | 18       | 2.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 248      | 37.52%  |
| 1.01-2.0   | 112      | 16.94%  |
| 0.51-1.0   | 75       | 11.35%  |
| 0.01-0.5   | 70       | 10.59%  |
| 3.01-4.0   | 57       | 8.62%   |
| 7.01-8.0   | 48       | 7.26%   |
| 5.01-6.0   | 33       | 4.99%   |
| 8.01-16.0  | 12       | 1.82%   |
| 2.01-3.0   | 4        | 0.61%   |
| 16.01-24.0 | 2        | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 104      | 15.83%  |
| Goldstar             | 71       | 10.81%  |
| Dell                 | 56       | 8.52%   |
| Hewlett-Packard      | 52       | 7.91%   |
| Acer                 | 49       | 7.46%   |
| AOC                  | 44       | 6.7%    |
| Philips              | 38       | 5.78%   |
| BenQ                 | 36       | 5.48%   |
| Ancor Communications | 22       | 3.35%   |
| ViewSonic            | 19       | 2.89%   |
| ASUSTek Computer     | 16       | 2.44%   |
| Iiyama               | 12       | 1.83%   |
| Lenovo               | 10       | 1.52%   |
| Sceptre Tech         | 8        | 1.22%   |
| Unknown              | 8        | 1.22%   |
| Unknown              | 7        | 1.07%   |
| NEC Computers        | 6        | 0.91%   |
| Sony                 | 5        | 0.76%   |
| Fujitsu Siemens      | 5        | 0.76%   |
| Sharp                | 4        | 0.61%   |
| Seiki                | 4        | 0.61%   |
| Panasonic            | 4        | 0.61%   |
| MSI                  | 4        | 0.61%   |
| LG Electronics       | 4        | 0.61%   |
| NCS                  | 3        | 0.46%   |
| Vestel               | 2        | 0.3%    |
| Unknown (XXX)        | 2        | 0.3%    |
| UMC                  | 2        | 0.3%    |
| UGD                  | 2        | 0.3%    |
| SGT                  | 2        | 0.3%    |
| Insignia             | 2        | 0.3%    |
| Idek Iiyama          | 2        | 0.3%    |
| HKC                  | 2        | 0.3%    |
| HannStar             | 2        | 0.3%    |
| Eizo                 | 2        | 0.3%    |
| AOpen                | 2        | 0.3%    |
| Xiaomi               | 1        | 0.15%   |
| VMO                  | 1        | 0.15%   |
| Vizio                | 1        | 0.15%   |
| Vita                 | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Unknown                                                                | 8        | 1.19%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 6        | 0.89%   |
| BenQ GL2023 BNQ78CC 1600x900 443x249mm 20.0-inch                       | 6        | 0.89%   |
| Seiki SE20HY SEK0CA8 1360x768 440x250mm 19.9-inch                      | 4        | 0.6%    |
| Samsung Electronics SyncMaster SAM0527 1600x900 443x250mm 20.0-inch    | 3        | 0.45%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 3        | 0.45%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 3        | 0.45%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 3        | 0.45%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                  | 3        | 0.45%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                 | 3        | 0.45%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 3        | 0.45%   |
| Goldstar IPS225 GSM587B 1920x1080 510x290mm 23.1-inch                  | 3        | 0.45%   |
| Dell P2210 DEL404D 1680x1050 474x296mm 22.0-inch                       | 3        | 0.45%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                      | 3        | 0.45%   |
| AOC 2752H AOC2752 1920x1080 598x336mm 27.0-inch                        | 3        | 0.45%   |
| AOC 2050 AOC2050 1600x900 443x249mm 20.0-inch                          | 3        | 0.45%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch       | 3        | 0.45%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch            | 2        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 2        | 0.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2        | 0.3%    |
| UMC TV UMCC032 1920x1080 702x396mm 31.7-inch                           | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch   | 2        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.3%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 2        | 0.3%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM04FD 1280x720                       | 2        | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2        | 0.3%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 2        | 0.3%    |
| Philips 191EL PHLC03D 1366x768 410x230mm 18.5-inch                     | 2        | 0.3%    |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                     | 2        | 0.3%    |
| Lenovo D24-20 LEN66AE 1920x1080 530x300mm 24.0-inch                    | 2        | 0.3%    |
| Hewlett-Packard Z23i HWP3090 1920x1080 509x286mm 23.0-inch             | 2        | 0.3%    |
| Hewlett-Packard w2207 HWP26A9 1680x1050 473x296mm 22.0-inch            | 2        | 0.3%    |
| Hewlett-Packard V270 HPN3521 1920x1080 598x336mm 27.0-inch             | 2        | 0.3%    |
| Hewlett-Packard P201 HWP3056 1600x900 443x249mm 20.0-inch              | 2        | 0.3%    |
| Hewlett-Packard LA1951 HWP285B 1280x960 380x300mm 19.1-inch            | 2        | 0.3%    |
| Hewlett-Packard L2105tm HWP2863 1920x1080 477x268mm 21.5-inch          | 2        | 0.3%    |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 2        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 338      | 52.24%  |
| 3840x2160 (4K)     | 51       | 7.88%   |
| 1680x1050 (WSXGA+) | 45       | 6.96%   |
| 2560x1440 (QHD)    | 42       | 6.49%   |
| 1280x1024 (SXGA)   | 33       | 5.1%    |
| 1600x900 (HD+)     | 24       | 3.71%   |
| 1366x768 (WXGA)    | 24       | 3.71%   |
| 1920x1200 (WUXGA)  | 23       | 3.55%   |
| 1360x768           | 18       | 2.78%   |
| 1440x900 (WXGA+)   | 12       | 1.85%   |
| 3440x1440          | 10       | 1.55%   |
| 2560x1080          | 5        | 0.77%   |
| Unknown            | 5        | 0.77%   |
| 2288x1287          | 2        | 0.31%   |
| 1920x540           | 2        | 0.31%   |
| 1280x960           | 2        | 0.31%   |
| 1024x768 (XGA)     | 2        | 0.31%   |
| 8320x1440          | 1        | 0.15%   |
| 6000x1440          | 1        | 0.15%   |
| 5760x2160          | 1        | 0.15%   |
| 5120x1440          | 1        | 0.15%   |
| 4480x2023          | 1        | 0.15%   |
| 3840x1080          | 1        | 0.15%   |
| 2560x1600          | 1        | 0.15%   |
| 1280x768           | 1        | 0.15%   |
| 1280x720 (HD)      | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 93       | 14.24%  |
| 27      | 88       | 13.48%  |
| 23      | 88       | 13.48%  |
| 21      | 84       | 12.86%  |
| Unknown | 42       | 6.43%   |
| 22      | 38       | 5.82%   |
| 19      | 37       | 5.67%   |
| 31      | 28       | 4.29%   |
| 18      | 28       | 4.29%   |
| 20      | 23       | 3.52%   |
| 34      | 14       | 2.14%   |
| 17      | 14       | 2.14%   |
| 54      | 7        | 1.07%   |
| 84      | 6        | 0.92%   |
| 15      | 6        | 0.92%   |
| 72      | 5        | 0.77%   |
| 39      | 5        | 0.77%   |
| 32      | 5        | 0.77%   |
| 25      | 5        | 0.77%   |
| 40      | 4        | 0.61%   |
| 26      | 4        | 0.61%   |
| 48      | 3        | 0.46%   |
| 12      | 3        | 0.46%   |
| 142     | 2        | 0.31%   |
| 37      | 2        | 0.31%   |
| 28      | 2        | 0.31%   |
| 74      | 1        | 0.15%   |
| 65      | 1        | 0.15%   |
| 64      | 1        | 0.15%   |
| 60      | 1        | 0.15%   |
| 58      | 1        | 0.15%   |
| 55      | 1        | 0.15%   |
| 52      | 1        | 0.15%   |
| 50      | 1        | 0.15%   |
| 49      | 1        | 0.15%   |
| 46      | 1        | 0.15%   |
| 42      | 1        | 0.15%   |
| 41      | 1        | 0.15%   |
| 35      | 1        | 0.15%   |
| 33      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 247      | 38.65%  |
| 401-500        | 188      | 29.42%  |
| 601-700        | 45       | 7.04%   |
| Unknown        | 42       | 6.57%   |
| 351-400        | 25       | 3.91%   |
| 701-800        | 21       | 3.29%   |
| 301-350        | 19       | 2.97%   |
| 1001-1500      | 19       | 2.97%   |
| 801-900        | 12       | 1.88%   |
| 1501-2000      | 12       | 1.88%   |
| 201-300        | 5        | 0.78%   |
| More than 2000 | 2        | 0.31%   |
| 901-1000       | 2        | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 451      | 71.82%  |
| 16/10   | 80       | 12.74%  |
| 5/4     | 35       | 5.57%   |
| Unknown | 30       | 4.78%   |
| 21/9    | 15       | 2.39%   |
| 4/3     | 7        | 1.11%   |
| 3/2     | 6        | 0.96%   |
| 1.00    | 2        | 0.32%   |
| 2.12    | 1        | 0.16%   |
| 2.00    | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 242      | 37.46%  |
| 151-200        | 92       | 14.24%  |
| 301-350        | 89       | 13.78%  |
| 351-500        | 49       | 7.59%   |
| Unknown        | 42       | 6.5%    |
| 141-150        | 38       | 5.88%   |
| 251-300        | 35       | 5.42%   |
| More than 1000 | 32       | 4.95%   |
| 501-1000       | 15       | 2.32%   |
| 101-110        | 6        | 0.93%   |
| 71-80          | 3        | 0.46%   |
| 51-60          | 1        | 0.15%   |
| 131-140        | 1        | 0.15%   |
| 91-100         | 1        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 405      | 64.39%  |
| 101-120 | 120      | 19.08%  |
| Unknown | 42       | 6.68%   |
| 1-50    | 32       | 5.09%   |
| 121-160 | 21       | 3.34%   |
| 161-240 | 9        | 1.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 592      | 89.56%  |
| 2     | 55       | 8.32%   |
| 0     | 7        | 1.06%   |
| 3     | 6        | 0.91%   |
| 4     | 1        | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 442      | 49.94%  |
| Intel                           | 222      | 25.08%  |
| Qualcomm Atheros                | 67       | 7.57%   |
| Ralink Technology               | 23       | 2.6%    |
| Broadcom                        | 21       | 2.37%   |
| MediaTek                        | 15       | 1.69%   |
| Qualcomm Atheros Communications | 12       | 1.36%   |
| Nvidia                          | 12       | 1.36%   |
| TP-Link                         | 11       | 1.24%   |
| Ralink                          | 10       | 1.13%   |
| ASUSTek Computer                | 7        | 0.79%   |
| D-Link                          | 5        | 0.56%   |
| Microsoft                       | 3        | 0.34%   |
| Marvell Technology Group        | 3        | 0.34%   |
| Broadcom Limited                | 3        | 0.34%   |
| ASIX Electronics                | 3        | 0.34%   |
| NetGear                         | 2        | 0.23%   |
| IMC Networks                    | 2        | 0.23%   |
| Aquantia                        | 2        | 0.23%   |
| ZyDAS                           | 1        | 0.11%   |
| Xiaomi                          | 1        | 0.11%   |
| Wilocity                        | 1        | 0.11%   |
| VIA Technologies                | 1        | 0.11%   |
| THEC64 Joystick                 | 1        | 0.11%   |
| T & A Mobile Phones             | 1        | 0.11%   |
| Samsung Electronics             | 1        | 0.11%   |
| Qualcomm                        | 1        | 0.11%   |
| OPPO Electronics                | 1        | 0.11%   |
| Motorola PCS                    | 1        | 0.11%   |
| Linksys                         | 1        | 0.11%   |
| Huawei Technologies             | 1        | 0.11%   |
| Fitbit                          | 1        | 0.11%   |
| Edimax Technology               | 1        | 0.11%   |
| D-Link System                   | 1        | 0.11%   |
| BUFFALO                         | 1        | 0.11%   |
| Belkin Components               | 1        | 0.11%   |
| AVM                             | 1        | 0.11%   |
| Arduino SA                      | 1        | 0.11%   |
| 3Com                            | 1        | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 362      | 37.2%   |
| Intel Ethernet Connection I217-LM                                 | 24       | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23       | 2.36%   |
| Intel I211 Gigabit Network Connection                             | 21       | 2.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18       | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 18       | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 1.54%   |
| Intel Ethernet Connection (2) I219-V                              | 15       | 1.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 1.44%   |
| Intel Ethernet Controller I225-V                                  | 13       | 1.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 12       | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12       | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11       | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.13%   |
| Intel 82579V Gigabit Network Connection                           | 11       | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10       | 1.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 8        | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8        | 0.82%   |
| Intel Wireless 7265                                               | 8        | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 0.82%   |
| Ralink MT7601U Wireless Adapter                                   | 7        | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7        | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.72%   |
| Intel Wireless 3165                                               | 7        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.62%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6        | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 6        | 0.62%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 5        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 0.51%   |
| Realtek 802.11ac NIC                                              | 5        | 0.51%   |
| Nvidia MCP73 Ethernet                                             | 5        | 0.51%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4        | 0.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 0.41%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.41%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.41%   |
| Intel Wireless-AC 9260                                            | 4        | 0.41%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 76       | 27.34%  |
| Intel                           | 73       | 26.26%  |
| Qualcomm Atheros                | 30       | 10.79%  |
| Ralink Technology               | 23       | 8.27%   |
| Qualcomm Atheros Communications | 12       | 4.32%   |
| MediaTek                        | 12       | 4.32%   |
| TP-Link                         | 11       | 3.96%   |
| Ralink                          | 10       | 3.6%    |
| ASUSTek Computer                | 7        | 2.52%   |
| D-Link                          | 5        | 1.8%    |
| Microsoft                       | 3        | 1.08%   |
| Broadcom                        | 3        | 1.08%   |
| NetGear                         | 2        | 0.72%   |
| IMC Networks                    | 2        | 0.72%   |
| ZyDAS                           | 1        | 0.36%   |
| Wilocity                        | 1        | 0.36%   |
| VIA Technologies                | 1        | 0.36%   |
| Linksys                         | 1        | 0.36%   |
| Edimax Technology               | 1        | 0.36%   |
| D-Link System                   | 1        | 0.36%   |
| BUFFALO                         | 1        | 0.36%   |
| Belkin Components               | 1        | 0.36%   |
| AVM                             | 1        | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 18       | 6.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 12       | 4.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12       | 4.3%    |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 3.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10       | 3.58%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 8        | 2.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8        | 2.87%   |
| Intel Wireless 7265                                            | 8        | 2.87%   |
| Ralink MT7601U Wireless Adapter                                | 7        | 2.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7        | 2.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7        | 2.51%   |
| Intel Wireless 3165                                            | 7        | 2.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6        | 2.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 2.15%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 5        | 1.79%   |
| Realtek 802.11ac NIC                                           | 5        | 1.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4        | 1.43%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4        | 1.43%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4        | 1.43%   |
| Intel Wireless-AC 9260                                         | 4        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 1.08%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.08%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 3        | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3        | 1.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 3        | 1.08%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3        | 1.08%   |
| Microsoft Xbox 360 Wireless Adapter                            | 3        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3        | 1.08%   |
| Intel Wireless 7260                                            | 3        | 1.08%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2        | 0.72%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2        | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2        | 0.72%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 2        | 0.72%   |
| Ralink RT5572 Wireless Adapter                                 | 2        | 0.72%   |
| Ralink RT5372 Wireless Adapter                                 | 2        | 0.72%   |
| Ralink RT3072 Wireless Adapter                                 | 2        | 0.72%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 0.72%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                      | 2        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 411      | 60.62%  |
| Intel                    | 175      | 25.81%  |
| Qualcomm Atheros         | 39       | 5.75%   |
| Broadcom                 | 19       | 2.8%    |
| Nvidia                   | 12       | 1.77%   |
| MediaTek                 | 3        | 0.44%   |
| Marvell Technology Group | 3        | 0.44%   |
| Broadcom Limited         | 3        | 0.44%   |
| ASIX Electronics         | 3        | 0.44%   |
| Aquantia                 | 2        | 0.29%   |
| Xiaomi                   | 1        | 0.15%   |
| T & A Mobile Phones      | 1        | 0.15%   |
| Samsung Electronics      | 1        | 0.15%   |
| Qualcomm                 | 1        | 0.15%   |
| OPPO Electronics         | 1        | 0.15%   |
| Motorola PCS             | 1        | 0.15%   |
| Huawei Technologies      | 1        | 0.15%   |
| 3Com                     | 1        | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 362      | 52.39%  |
| Intel Ethernet Connection I217-LM                                 | 24       | 3.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23       | 3.33%   |
| Intel I211 Gigabit Network Connection                             | 21       | 3.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 2.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18       | 2.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15       | 2.17%   |
| Intel Ethernet Connection (2) I219-V                              | 15       | 2.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 2.03%   |
| Intel Ethernet Controller I225-V                                  | 13       | 1.88%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.59%   |
| Intel 82579V Gigabit Network Connection                           | 11       | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 8        | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 6        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 0.72%   |
| Nvidia MCP73 Ethernet                                             | 5        | 0.72%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.58%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.58%   |
| Intel Ethernet Connection (14) I219-V                             | 4        | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.43%   |
| MediaTek TECNO SPARK 9T                                           | 3        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.43%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 3        | 0.43%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 3        | 0.43%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 3        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3        | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.29%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2        | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.29%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.29%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.29%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.29%   |
| Intel Ethernet Connection (14) I219-LM                            | 2        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 653      | 70.9%   |
| WiFi     | 265      | 28.77%  |
| Modem    | 2        | 0.22%   |
| Unknown  | 1        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 528      | 80.12%  |
| WiFi     | 131      | 19.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 473      | 71.56%  |
| 2     | 165      | 24.96%  |
| 3     | 14       | 2.12%   |
| 0     | 7        | 1.06%   |
| 4     | 2        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 459      | 69.44%  |
| Yes  | 202      | 30.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 65       | 34.95%  |
| Cambridge Silicon Radio         | 48       | 25.81%  |
| Realtek Semiconductor           | 20       | 10.75%  |
| ASUSTek Computer                | 12       | 6.45%   |
| Qualcomm Atheros Communications | 9        | 4.84%   |
| MediaTek                        | 8        | 4.3%    |
| Broadcom                        | 8        | 4.3%    |
| IMC Networks                    | 6        | 3.23%   |
| TP-Link                         | 2        | 1.08%   |
| Realtek                         | 1        | 0.54%   |
| Integrated System Solution      | 1        | 0.54%   |
| Foxconn / Hon Hai               | 1        | 0.54%   |
| Edimax Technology               | 1        | 0.54%   |
| Dynex                           | 1        | 0.54%   |
| Dell                            | 1        | 0.54%   |
| Belkin Components               | 1        | 0.54%   |
| Apple                           | 1        | 0.54%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 48       | 25.67%  |
| Intel Bluetooth wireless interface                       | 20       | 10.7%   |
| Intel AX200 Bluetooth                                    | 16       | 8.56%   |
| Realtek Bluetooth Radio                                  | 14       | 7.49%   |
| Intel Wireless-AC 3168 Bluetooth                         | 11       | 5.88%   |
| Intel AX210 Bluetooth                                    | 10       | 5.35%   |
| MediaTek Wireless_Device                                 | 8        | 4.28%   |
| Qualcomm Atheros  Bluetooth Device                       | 7        | 3.74%   |
| ASUS ASUS USB-BT500                                      | 7        | 3.74%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 1.6%    |
| Intel AX201 Bluetooth                                    | 3        | 1.6%    |
| IMC Networks Bluetooth Radio                             | 3        | 1.6%    |
| TP-Link UB500 Adapter                                    | 2        | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 2        | 1.07%   |
| Intel Bluetooth Device                                   | 2        | 1.07%   |
| IMC Networks Bluetooth Device                            | 2        | 1.07%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 1.07%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 1.07%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 1        | 0.53%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.53%   |
| Realtek Bluetooth 5.1 Radio                              | 1        | 0.53%   |
| Realtek Bluetooth Radio                                  | 1        | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 1        | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.53%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 0.53%   |
| Integrated System Solution Bluetooth Device              | 1        | 0.53%   |
| IMC Networks Wireless_Device                             | 1        | 0.53%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter             | 1        | 0.53%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.53%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.53%   |
| Dell BT Mini-Receiver                                    | 1        | 0.53%   |
| Broadcom Bluetooth Device                                | 1        | 0.53%   |
| Broadcom Bluetooth Controller                            | 1        | 0.53%   |
| Broadcom Bluetooth 3.0 Dongle                            | 1        | 0.53%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle      | 1        | 0.53%   |
| Broadcom BCM2035B3 Bluetooth Adapter                     | 1        | 0.53%   |
| Broadcom ANYCOM Blue USB-200/250                         | 1        | 0.53%   |
| Belkin Components Bluetooth Mini Dongle                  | 1        | 0.53%   |
| ASUS Bluetooth Device                                    | 1        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 425      | 41.22%  |
| AMD                                          | 261      | 25.32%  |
| Nvidia                                       | 218      | 21.14%  |
| C-Media Electronics                          | 23       | 2.23%   |
| Creative Labs                                | 22       | 2.13%   |
| Logitech                                     | 9        | 0.87%   |
| Generalplus Technology                       | 7        | 0.68%   |
| Tenx Technology                              | 4        | 0.39%   |
| Micro Star International                     | 4        | 0.39%   |
| Texas Instruments                            | 3        | 0.29%   |
| SteelSeries ApS                              | 3        | 0.29%   |
| JMTek                                        | 3        | 0.29%   |
| Creative Technology                          | 3        | 0.29%   |
| VIA Technologies                             | 2        | 0.19%   |
| Schiit Audio                                 | 2        | 0.19%   |
| ROCCAT                                       | 2        | 0.19%   |
| Native Instruments                           | 2        | 0.19%   |
| KTMicro                                      | 2        | 0.19%   |
| Guangzhou FiiO Electronics                   | 2        | 0.19%   |
| Focusrite-Novation                           | 2        | 0.19%   |
| DSEA A/S                                     | 2        | 0.19%   |
| Dell                                         | 2        | 0.19%   |
| ASUSTek Computer                             | 2        | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.1%    |
| Yamaha                                       | 1        | 0.1%    |
| XMOS                                         | 1        | 0.1%    |
| Xilinx                                       | 1        | 0.1%    |
| USB-Speaker                                  | 1        | 0.1%    |
| Tdlasunnic                                   | 1        | 0.1%    |
| Sterling                                     | 1        | 0.1%    |
| Samson Technologies                          | 1        | 0.1%    |
| RODE Microphones                             | 1        | 0.1%    |
| Razer USA                                    | 1        | 0.1%    |
| PreSonus Audio Electronics                   | 1        | 0.1%    |
| Nordic Semiconductor ASA                     | 1        | 0.1%    |
| Nintendo                                     | 1        | 0.1%    |
| Logic3 / SpectraVideo                        | 1        | 0.1%    |
| Kingston Technology                          | 1        | 0.1%    |
| Jieli Technology                             | 1        | 0.1%    |
| Hewlett-Packard                              | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 59       | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 57       | 4.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 57       | 4.7%    |
| AMD Starship/Matisse HD Audio Controller                                   | 50       | 4.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 43       | 3.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 41       | 3.38%   |
| Intel 200 Series PCH HD Audio                                              | 41       | 3.38%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 40       | 3.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 35       | 2.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 34       | 2.8%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 31       | 2.55%   |
| AMD FCH Azalia Controller                                                  | 30       | 2.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29       | 2.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 25       | 2.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 24       | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23       | 1.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 1.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20       | 1.65%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 17       | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 16       | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 16       | 1.32%   |
| Nvidia GP108 High Definition Audio Controller                              | 15       | 1.24%   |
| Nvidia GP106 High Definition Audio Controller                              | 14       | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13       | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13       | 1.07%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 12       | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12       | 0.99%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 12       | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 12       | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11       | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 10       | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 10       | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 10       | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10       | 0.82%   |
| AMD Trinity HDMI Audio Controller                                          | 9        | 0.74%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 9        | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 8        | 0.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8        | 0.66%   |
| Intel Comet Lake PCH-V cAVS                                                | 7        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Kingston                   | 150      | 19.66%  |
| Unknown                    | 103      | 13.5%   |
| Samsung Electronics        | 90       | 11.8%   |
| SK hynix                   | 67       | 8.78%   |
| Corsair                    | 63       | 8.26%   |
| Crucial                    | 55       | 7.21%   |
| G.Skill                    | 40       | 5.24%   |
| Micron Technology          | 37       | 4.85%   |
| A-DATA Technology          | 23       | 3.01%   |
| Team                       | 17       | 2.23%   |
| Unknown                    | 17       | 2.23%   |
| Ramaxel Technology         | 13       | 1.7%    |
| Nanya Technology           | 13       | 1.7%    |
| Patriot                    | 7        | 0.92%   |
| Multilaser                 | 6        | 0.79%   |
| GOODRAM                    | 5        | 0.66%   |
| Elpida                     | 5        | 0.66%   |
| Apacer                     | 5        | 0.66%   |
| Unifosa                    | 3        | 0.39%   |
| Hikvision                  | 3        | 0.39%   |
| Avant                      | 3        | 0.39%   |
| AMD                        | 3        | 0.39%   |
| Unknown (ABCD)             | 2        | 0.26%   |
| Transcend                  | 2        | 0.26%   |
| Toshiba                    | 2        | 0.26%   |
| Silicon Power              | 2        | 0.26%   |
| Kllisre                    | 2        | 0.26%   |
| GeIL                       | 2        | 0.26%   |
| ASint Technology           | 2        | 0.26%   |
| A Force                    | 2        | 0.26%   |
| Wilk Elektronik            | 1        | 0.13%   |
| Wilk                       | 1        | 0.13%   |
| Unknown (7F7F7F7F7F7F7F83) | 1        | 0.13%   |
| Unknown (0x0DD5)           | 1        | 0.13%   |
| Unknown (04E9)             | 1        | 0.13%   |
| Timetec                    | 1        | 0.13%   |
| SUPER KINGSTEK             | 1        | 0.13%   |
| Smart                      | 1        | 0.13%   |
| SemsoTai                   | 1        | 0.13%   |
| PUSKILL                    | 1        | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown                                                | 17       | 1.97%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 10       | 1.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 9        | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 9        | 1.04%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 8        | 0.93%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 8        | 0.93%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 7        | 0.81%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s         | 7        | 0.81%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 7        | 0.81%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 7        | 0.81%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s    | 7        | 0.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 7        | 0.81%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 6        | 0.7%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 6        | 0.7%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 6        | 0.7%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 6        | 0.7%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s   | 6        | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 5        | 0.58%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 5        | 0.58%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 5        | 0.58%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s     | 5        | 0.58%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 5        | 0.58%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s            | 5        | 0.58%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 4        | 0.46%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 4        | 0.46%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s    | 4        | 0.46%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.46%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 4        | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 4        | 0.46%   |
| Samsung RAM M378B5673FH0-CF8 2GB DIMM DDR3 1067MT/s    | 4        | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 4        | 0.46%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 3        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 3        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s               | 3        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 3        | 0.35%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 3        | 0.35%   |
| Team RAM TEAMGROUP-UD4-2666 16384MB DIMM DDR4 2933MT/s | 3        | 0.35%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s              | 3        | 0.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 3        | 0.35%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM 2200MT/s         | 3        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 277      | 41.41%  |
| DDR3    | 245      | 36.62%  |
| SDRAM   | 51       | 7.62%   |
| DDR2    | 45       | 6.73%   |
| Unknown | 39       | 5.83%   |
| DDR5    | 6        | 0.9%    |
| DDR     | 3        | 0.45%   |
| LPDDR4  | 2        | 0.3%    |
| DRAM    | 1        | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 602      | 92.47%  |
| SODIMM | 45       | 6.91%   |
| RIMM   | 4        | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 269      | 36.25%  |
| 4096  | 219      | 29.51%  |
| 2048  | 128      | 17.25%  |
| 16384 | 69       | 9.3%    |
| 1024  | 33       | 4.45%   |
| 32768 | 21       | 2.83%   |
| 512   | 2        | 0.27%   |
| 64    | 1        | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 151      | 20.13%  |
| 1333    | 104      | 13.87%  |
| 2400    | 52       | 6.93%   |
| 3600    | 48       | 6.4%    |
| 2667    | 46       | 6.13%   |
| 3200    | 45       | 6%      |
| 2133    | 41       | 5.47%   |
| 800     | 27       | 3.6%    |
| 667     | 24       | 3.2%    |
| Unknown | 21       | 2.8%    |
| 2933    | 17       | 2.27%   |
| 1867    | 14       | 1.87%   |
| 1866    | 13       | 1.73%   |
| 3000    | 12       | 1.6%    |
| 2666    | 10       | 1.33%   |
| 1800    | 8        | 1.07%   |
| 1066    | 8        | 1.07%   |
| 1067    | 7        | 0.93%   |
| 3800    | 6        | 0.8%    |
| 3733    | 5        | 0.67%   |
| 3666    | 5        | 0.67%   |
| 3533    | 5        | 0.67%   |
| 1334    | 5        | 0.67%   |
| 3466    | 4        | 0.53%   |
| 3400    | 4        | 0.53%   |
| 400     | 4        | 0.53%   |
| 49926   | 3        | 0.4%    |
| 3534    | 3        | 0.4%    |
| 3266    | 3        | 0.4%    |
| 3151    | 3        | 0.4%    |
| 2800    | 3        | 0.4%    |
| 2200    | 3        | 0.4%    |
| 2048    | 3        | 0.4%    |
| 1648    | 3        | 0.4%    |
| 1639    | 3        | 0.4%    |
| 6000    | 2        | 0.27%   |
| 4800    | 2        | 0.27%   |
| 4266    | 2        | 0.27%   |
| 3866    | 2        | 0.27%   |
| 3007    | 2        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 12       | 34.29%  |
| Seiko Epson         | 7        | 20%     |
| Hewlett-Packard     | 7        | 20%     |
| Canon               | 6        | 17.14%  |
| Samsung Electronics | 3        | 8.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Brother HL-L2390DW         | 3        | 8.57%   |
| HP DeskJet 2600 series     | 2        | 5.71%   |
| Seiko Epson XP-7100 Series | 1        | 2.86%   |
| Seiko Epson Printer        | 1        | 2.86%   |
| Seiko Epson L6160 Series   | 1        | 2.86%   |
| Seiko Epson L365 Series    | 1        | 2.86%   |
| Seiko Epson L3110 Series   | 1        | 2.86%   |
| Seiko Epson L120 Series    | 1        | 2.86%   |
| Seiko Epson ET-2710 Series | 1        | 2.86%   |
| Samsung ML-1710 Printer    | 1        | 2.86%   |
| Samsung M267x 287x Series  | 1        | 2.86%   |
| Samsung M2070 Series       | 1        | 2.86%   |
| HP OfficeJet 3830 series   | 1        | 2.86%   |
| HP LaserJet P1005          | 1        | 2.86%   |
| HP Laser 107a              | 1        | 2.86%   |
| HP ENVY 5000 series        | 1        | 2.86%   |
| HP DeskJet 5650c           | 1        | 2.86%   |
| Canon TS5300 series        | 1        | 2.86%   |
| Canon TS5100 series        | 1        | 2.86%   |
| Canon TR7500 series        | 1        | 2.86%   |
| Canon LiDE 300             | 1        | 2.86%   |
| Canon GX7000 series        | 1        | 2.86%   |
| Canon G3000 series         | 1        | 2.86%   |
| Brother MFC-J435W          | 1        | 2.86%   |
| Brother MFC-7460DN         | 1        | 2.86%   |
| Brother HL-5450DN series   | 1        | 2.86%   |
| Brother HL-5370DW series   | 1        | 2.86%   |
| Brother HL-2140 series     | 1        | 2.86%   |
| Brother DCP-T420W          | 1        | 2.86%   |
| Brother DCP-T310           | 1        | 2.86%   |
| Brother DCP-8085DN         | 1        | 2.86%   |
| Brother DCP-1510           | 1        | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 3        | 50%     |
| KYE Systems (Mouse Systems) | 1        | 16.67%  |
| Hewlett-Packard             | 1        | 16.67%  |
| Acer Peripherals (now BenQ) | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE | 1        | 16.67%  |
| HP ScanJet 3670                                     | 1        | 16.67%  |
| Canon CanoScan LiDE 90                              | 1        | 16.67%  |
| Canon CanoScan LiDE 210                             | 1        | 16.67%  |
| Canon CanoScan 1220U                                | 1        | 16.67%  |
| Acer Peripherals (now BenQ) Prisa 1240UT            | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 27       | 33.33%  |
| Microdia                      | 8        | 9.88%   |
| Generalplus Technology        | 4        | 4.94%   |
| Chicony Electronics           | 4        | 4.94%   |
| Sunplus Innovation Technology | 3        | 3.7%    |
| Realtek Semiconductor         | 3        | 3.7%    |
| ARC International             | 3        | 3.7%    |
| Z-Star Microelectronics       | 2        | 2.47%   |
| WaveRider Communications      | 2        | 2.47%   |
| Unknown                       | 2        | 2.47%   |
| Microsoft                     | 2        | 2.47%   |
| Creative Technology           | 2        | 2.47%   |
| AVerMedia Technologies        | 2        | 2.47%   |
| A4Tech                        | 2        | 2.47%   |
| Silicon Motion                | 1        | 1.23%   |
| Samsung Electronics           | 1        | 1.23%   |
| Razer USA                     | 1        | 1.23%   |
| LG Electronics                | 1        | 1.23%   |
| Jieli Technology              | 1        | 1.23%   |
| Hewlett-Packard               | 1        | 1.23%   |
| Genesys Logic                 | 1        | 1.23%   |
| GEMBIRD                       | 1        | 1.23%   |
| eMeet-200611                  | 1        | 1.23%   |
| eMeet                         | 1        | 1.23%   |
| Aveo Technology               | 1        | 1.23%   |
| ASUSTek Computer              | 1        | 1.23%   |
| Apple                         | 1        | 1.23%   |
| ALi                           | 1        | 1.23%   |
| Alcor Micro                   | 1        | 1.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 9        | 11.11%  |
| Generalplus GENERAL WEBCAM                            | 4        | 4.94%   |
| Microdia Webcam Vitade AF                             | 3        | 3.7%    |
| Logitech HD Pro Webcam C920                           | 3        | 3.7%    |
| ARC International Camera                              | 3        | 3.7%    |
| WaveRider USB 2.0 Camera                              | 2        | 2.47%   |
| Unknown HD camera                                     | 2        | 2.47%   |
| Sunplus Full HD webcam                                | 2        | 2.47%   |
| Realtek USB Camera                                    | 2        | 2.47%   |
| Microdia Integrated Camera                            | 2        | 2.47%   |
| Microdia CameraA                                      | 2        | 2.47%   |
| A4Tech FHD 1080P PC Camera                            | 2        | 2.47%   |
| Z-Star Venus USB2.0 Camera                            | 1        | 1.23%   |
| Z-Star A4 TECH USB2.0 PC Camera J                     | 1        | 1.23%   |
| Sunplus Aoni FHD Camera                               | 1        | 1.23%   |
| Silicon Motion Silicon Motion Camera                  | 1        | 1.23%   |
| Samsung Galaxy series, misc. (MTP mode)               | 1        | 1.23%   |
| Realtek HP 1.0MP High Definition Webcam               | 1        | 1.23%   |
| Razer USA Razer Kiyo Pro                              | 1        | 1.23%   |
| Microsoft MicrosoftÂ LifeCam HD-5001                 | 1        | 1.23%   |
| Microsoft LifeCam VX-800                              | 1        | 1.23%   |
| Microdia Camera                                       | 1        | 1.23%   |
| Logitech Webcam C930e                                 | 1        | 1.23%   |
| Logitech Webcam C925e                                 | 1        | 1.23%   |
| Logitech Webcam C600                                  | 1        | 1.23%   |
| Logitech Webcam C310                                  | 1        | 1.23%   |
| Logitech Webcam C210                                  | 1        | 1.23%   |
| Logitech Webcam C200                                  | 1        | 1.23%   |
| Logitech Webcam C120                                  | 1        | 1.23%   |
| Logitech QuickCam Pro 5000                            | 1        | 1.23%   |
| Logitech Portable Webcam C905                         | 1        | 1.23%   |
| Logitech HD Webcam C910                               | 1        | 1.23%   |
| Logitech HD Webcam C525                               | 1        | 1.23%   |
| Logitech HD Webcam C510                               | 1        | 1.23%   |
| Logitech CrystalCam                                   | 1        | 1.23%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 1.23%   |
| Logitech B525 HD Webcam                               | 1        | 1.23%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 1.23%   |
| Jieli USB PHY 2.0                                     | 1        | 1.23%   |
| HP USB Webcam                                         | 1        | 1.23%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 25%     |
| Gemalto (was Gemplus) | 1        | 25%     |
| Castles Technology    | 1        | 25%     |
| Alcor Micro           | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR333 SmartCard Reader          | 1        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 25%     |
| Castles Technology EZCCID Smart Card Reader       | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 605      | 91.53%  |
| 1     | 52       | 7.87%   |
| 2     | 4        | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 33       | 55.93%  |
| Unassigned class         | 8        | 13.56%  |
| Net/wireless             | 8        | 13.56%  |
| Chipcard                 | 4        | 6.78%   |
| Camera                   | 3        | 5.08%   |
| Multimedia controller    | 2        | 3.39%   |
| Communication controller | 1        | 1.69%   |

