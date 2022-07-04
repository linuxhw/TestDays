Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 2428

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21cba60be3](https://linux-hardware.org/?probe=21cba60be3) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [0dcbb35983](https://linux-hardware.org/?probe=0dcbb35983) | Jun 30, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [a2729b2e3b](https://linux-hardware.org/?probe=a2729b2e3b) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [d8190f3da8](https://linux-hardware.org/?probe=d8190f3da8) | Jun 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [9f64d5f095](https://linux-hardware.org/?probe=9f64d5f095) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Dell          | Precision M6800             | Notebook    | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [00ce30e950](https://linux-hardware.org/?probe=00ce30e950) | Jun 28, 2022 |
| MSI           | 2A9C                        | Desktop     | [c4d999a9a5](https://linux-hardware.org/?probe=c4d999a9a5) | Jun 26, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [800f6f5802](https://linux-hardware.org/?probe=800f6f5802) | Jun 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2103486702](https://linux-hardware.org/?probe=2103486702) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [62aec95456](https://linux-hardware.org/?probe=62aec95456) | Jun 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | Desktop     | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| Intel         | NUC11PHBi7 M26151-403       | Mini pc     | [7c3f1cd4c1](https://linux-hardware.org/?probe=7c3f1cd4c1) | Jun 21, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [5cde38b27f](https://linux-hardware.org/?probe=5cde38b27f) | Jun 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [6ec8ece12d](https://linux-hardware.org/?probe=6ec8ece12d) | Jun 19, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21f78f9cf4](https://linux-hardware.org/?probe=21f78f9cf4) | Jun 19, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [d84600d5b0](https://linux-hardware.org/?probe=d84600d5b0) | Jun 17, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [de123e03c3](https://linux-hardware.org/?probe=de123e03c3) | Jun 16, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [31aa19ff98](https://linux-hardware.org/?probe=31aa19ff98) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Clevo         | W150ER                      | Notebook    | [9121da24a8](https://linux-hardware.org/?probe=9121da24a8) | Jun 13, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | Notebook    | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| Microsoft     | Surface Book 3              | Tablet      | [26c417012f](https://linux-hardware.org/?probe=26c417012f) | Jun 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b31c452186](https://linux-hardware.org/?probe=b31c452186) | Jun 11, 2022 |
| HP            | 3032h                       | Desktop     | [fee76c58db](https://linux-hardware.org/?probe=fee76c58db) | Jun 09, 2022 |
| HP            | 8710                        | Mini pc     | [a4b6fd8f8a](https://linux-hardware.org/?probe=a4b6fd8f8a) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [6a14acf011](https://linux-hardware.org/?probe=6a14acf011) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0fbc627b7e](https://linux-hardware.org/?probe=0fbc627b7e) | Jun 07, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Shuttle       | DS10U                       | Desktop     | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [878cae499d](https://linux-hardware.org/?probe=878cae499d) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [0c53f7240c](https://linux-hardware.org/?probe=0c53f7240c) | Jun 03, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | Notebook    | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d8134fd2fe](https://linux-hardware.org/?probe=d8134fd2fe) | Jun 02, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [1fb17fc133](https://linux-hardware.org/?probe=1fb17fc133) | Jun 01, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [c4e901c3a6](https://linux-hardware.org/?probe=c4e901c3a6) | Jun 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | Desktop     | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [d4283c0b8b](https://linux-hardware.org/?probe=d4283c0b8b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e474768a25](https://linux-hardware.org/?probe=e474768a25) | May 30, 2022 |
| Minix         | NEO Z83-4A V1.1             | Desktop     | [e828d9bd38](https://linux-hardware.org/?probe=e828d9bd38) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [03a4099a33](https://linux-hardware.org/?probe=03a4099a33) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [cde5dba599](https://linux-hardware.org/?probe=cde5dba599) | May 27, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [e6ee61fdd8](https://linux-hardware.org/?probe=e6ee61fdd8) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| Lenovo        | V320-17IKB 81AH             | Notebook    | [c5d9a03264](https://linux-hardware.org/?probe=c5d9a03264) | May 27, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [6c7cfb5226](https://linux-hardware.org/?probe=6c7cfb5226) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [41529bd0e1](https://linux-hardware.org/?probe=41529bd0e1) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [da6bd78cdb](https://linux-hardware.org/?probe=da6bd78cdb) | May 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [071bc80c0b](https://linux-hardware.org/?probe=071bc80c0b) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [5f505dd767](https://linux-hardware.org/?probe=5f505dd767) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| HP            | 8703                        | Desktop     | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| Timi          | TM1613                      | Notebook    | [695d8d5ff0](https://linux-hardware.org/?probe=695d8d5ff0) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [da6b66b74f](https://linux-hardware.org/?probe=da6b66b74f) | May 21, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Acer          | V3-771                      | Notebook    | [8bcab66496](https://linux-hardware.org/?probe=8bcab66496) | May 20, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [625d790cde](https://linux-hardware.org/?probe=625d790cde) | May 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d8b886317a](https://linux-hardware.org/?probe=d8b886317a) | May 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| HP            | 81B7 1001                   | All in one  | [d99babe70f](https://linux-hardware.org/?probe=d99babe70f) | May 15, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| HP            | 805F                        | Desktop     | [c682455b49](https://linux-hardware.org/?probe=c682455b49) | May 13, 2022 |
| HP            | 805F                        | Desktop     | [ef6a65832f](https://linux-hardware.org/?probe=ef6a65832f) | May 13, 2022 |
| Shuttle       | DS10U                       | Desktop     | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| TUXEDO        | N2x0WU                      | Notebook    | [b70a08c999](https://linux-hardware.org/?probe=b70a08c999) | May 12, 2022 |
| ASUSTek       | GA35DX                      | Desktop     | [f604073d1f](https://linux-hardware.org/?probe=f604073d1f) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | Notebook    | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Sony          | VPCF23S1E                   | Notebook    | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| HP            | 870C                        | Desktop     | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | SDK0E50510 WIN 262504835... | Desktop     | [5565a2f131](https://linux-hardware.org/?probe=5565a2f131) | May 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [e95b0172b4](https://linux-hardware.org/?probe=e95b0172b4) | May 06, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [a888a93774](https://linux-hardware.org/?probe=a888a93774) | May 06, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [94806fd9bf](https://linux-hardware.org/?probe=94806fd9bf) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ebc49550d4](https://linux-hardware.org/?probe=ebc49550d4) | May 05, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Khadas        | VIM3                        | Soc         | [c17309ec68](https://linux-hardware.org/?probe=c17309ec68) | May 04, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [878c361636](https://linux-hardware.org/?probe=878c361636) | May 01, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [920d1b35ab](https://linux-hardware.org/?probe=920d1b35ab) | Apr 30, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| Acer          | Predator G3620              | Desktop     | [556a67d50d](https://linux-hardware.org/?probe=556a67d50d) | Apr 28, 2022 |
| NF541         | 1.0                         | Desktop     | [c0999696b6](https://linux-hardware.org/?probe=c0999696b6) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [99b46394bf](https://linux-hardware.org/?probe=99b46394bf) | Apr 27, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [25041b35de](https://linux-hardware.org/?probe=25041b35de) | Apr 27, 2022 |
| HP            | ENVY 17                     | Notebook    | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [c052066ee4](https://linux-hardware.org/?probe=c052066ee4) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [475131a6f4](https://linux-hardware.org/?probe=475131a6f4) | Apr 23, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [19d81a0ef0](https://linux-hardware.org/?probe=19d81a0ef0) | Apr 22, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [cd9c2dd8f9](https://linux-hardware.org/?probe=cd9c2dd8f9) | Apr 22, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [597940fbe8](https://linux-hardware.org/?probe=597940fbe8) | Apr 22, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6495b55188](https://linux-hardware.org/?probe=6495b55188) | Apr 21, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [3d667e4edf](https://linux-hardware.org/?probe=3d667e4edf) | Apr 21, 2022 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [1cabdda156](https://linux-hardware.org/?probe=1cabdda156) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | Notebook    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| HP            | 3048h                       | Desktop     | [b35df4ed74](https://linux-hardware.org/?probe=b35df4ed74) | Apr 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3af8357ab9](https://linux-hardware.org/?probe=3af8357ab9) | Apr 20, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| System76      | Galago Pro                  | Notebook    | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | Notebook    | [451ce5305a](https://linux-hardware.org/?probe=451ce5305a) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | Notebook    | [fa843a199c](https://linux-hardware.org/?probe=fa843a199c) | Apr 19, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [1ceaddfc92](https://linux-hardware.org/?probe=1ceaddfc92) | Apr 16, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Acer          | TMP455-M                    | Notebook    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | Notebook    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| HP            | 8298                        | Desktop     | [a9796ddd8d](https://linux-hardware.org/?probe=a9796ddd8d) | Apr 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8e46ef2a00](https://linux-hardware.org/?probe=8e46ef2a00) | Apr 13, 2022 |
| Acer          | Swift SF514-51              | Notebook    | [147a0161aa](https://linux-hardware.org/?probe=147a0161aa) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | Notebook    | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| Dell          | Inspiron 7786               | Convertible | [cdf7aa0cb8](https://linux-hardware.org/?probe=cdf7aa0cb8) | Apr 11, 2022 |
| Dell          | Latitude D400               | Notebook    | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| PC Engines    | apu4                        | Desktop     | [601866ecaa](https://linux-hardware.org/?probe=601866ecaa) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [36e8e44760](https://linux-hardware.org/?probe=36e8e44760) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [50d7c349cd](https://linux-hardware.org/?probe=50d7c349cd) | Apr 10, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [b160291e93](https://linux-hardware.org/?probe=b160291e93) | Apr 09, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [d56d880fd1](https://linux-hardware.org/?probe=d56d880fd1) | Apr 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [7e44cf1d2c](https://linux-hardware.org/?probe=7e44cf1d2c) | Apr 04, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [e43f33eef1](https://linux-hardware.org/?probe=e43f33eef1) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | Notebook    | [5090da9cbf](https://linux-hardware.org/?probe=5090da9cbf) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | Notebook    | [2388fe9587](https://linux-hardware.org/?probe=2388fe9587) | Apr 03, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0c9c9dd7e9](https://linux-hardware.org/?probe=0c9c9dd7e9) | Apr 02, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e7d599e001](https://linux-hardware.org/?probe=e7d599e001) | Apr 01, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [52d7f90956](https://linux-hardware.org/?probe=52d7f90956) | Apr 01, 2022 |
| Acer          | Aspire E5-773G              | Notebook    | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [6755915c96](https://linux-hardware.org/?probe=6755915c96) | Mar 29, 2022 |
| HP            | Pavilion g7                 | Notebook    | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [edbd5fd6aa](https://linux-hardware.org/?probe=edbd5fd6aa) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [85f4e6ff91](https://linux-hardware.org/?probe=85f4e6ff91) | Mar 26, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [ed949b0853](https://linux-hardware.org/?probe=ed949b0853) | Mar 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [684a4fd3c3](https://linux-hardware.org/?probe=684a4fd3c3) | Mar 24, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a9df37f3f0](https://linux-hardware.org/?probe=a9df37f3f0) | Mar 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [dd13dcfd89](https://linux-hardware.org/?probe=dd13dcfd89) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a1a39d622b](https://linux-hardware.org/?probe=a1a39d622b) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [18294dd367](https://linux-hardware.org/?probe=18294dd367) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f51c0bb134](https://linux-hardware.org/?probe=f51c0bb134) | Mar 21, 2022 |
| ASUSTek       | K73E                        | Notebook    | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d98f42c86b](https://linux-hardware.org/?probe=d98f42c86b) | Mar 20, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7664c536f4](https://linux-hardware.org/?probe=7664c536f4) | Mar 18, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [9c78b8d68b](https://linux-hardware.org/?probe=9c78b8d68b) | Mar 17, 2022 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [d0253d1ffc](https://linux-hardware.org/?probe=d0253d1ffc) | Mar 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [bf629bc1a5](https://linux-hardware.org/?probe=bf629bc1a5) | Mar 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7649fad366](https://linux-hardware.org/?probe=7649fad366) | Mar 14, 2022 |
| ASUSTek       | VC66                        | Mini pc     | [e89b5b2495](https://linux-hardware.org/?probe=e89b5b2495) | Mar 14, 2022 |
| ASUSTek       | VC66                        | Mini pc     | [52c0b45697](https://linux-hardware.org/?probe=52c0b45697) | Mar 14, 2022 |
| Dell          | Latitude 5400               | Notebook    | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [77b3a7f272](https://linux-hardware.org/?probe=77b3a7f272) | Mar 13, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [f56d8f0fe4](https://linux-hardware.org/?probe=f56d8f0fe4) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [f4f7ab1aaf](https://linux-hardware.org/?probe=f4f7ab1aaf) | Mar 12, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f735730566](https://linux-hardware.org/?probe=f735730566) | Mar 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e8ffb57db8](https://linux-hardware.org/?probe=e8ffb57db8) | Mar 11, 2022 |
| HP            | 806A                        | Desktop     | [60d334dbf5](https://linux-hardware.org/?probe=60d334dbf5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [566eee23f5](https://linux-hardware.org/?probe=566eee23f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [0046299935](https://linux-hardware.org/?probe=0046299935) | Mar 10, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [1526117b64](https://linux-hardware.org/?probe=1526117b64) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [c98fcbec3c](https://linux-hardware.org/?probe=c98fcbec3c) | Mar 10, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [af17a2da6b](https://linux-hardware.org/?probe=af17a2da6b) | Mar 05, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [95d4a7b220](https://linux-hardware.org/?probe=95d4a7b220) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [fd01513251](https://linux-hardware.org/?probe=fd01513251) | Mar 04, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [7d5295d845](https://linux-hardware.org/?probe=7d5295d845) | Mar 03, 2022 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [ee54bb96c5](https://linux-hardware.org/?probe=ee54bb96c5) | Mar 03, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [5c8b94d514](https://linux-hardware.org/?probe=5c8b94d514) | Mar 03, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [75b63c2d2c](https://linux-hardware.org/?probe=75b63c2d2c) | Mar 02, 2022 |
| HP            | 8592                        | Desktop     | [a34dbdb173](https://linux-hardware.org/?probe=a34dbdb173) | Mar 01, 2022 |
| Medion        | P6624                       | Notebook    | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [e0d39731a0](https://linux-hardware.org/?probe=e0d39731a0) | Feb 27, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [e996ec20ea](https://linux-hardware.org/?probe=e996ec20ea) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Notebook      | N13xWU                      | Notebook    | [50acf36954](https://linux-hardware.org/?probe=50acf36954) | Feb 25, 2022 |
| Acer          | TMP455-MG                   | Notebook    | [f1a500ae43](https://linux-hardware.org/?probe=f1a500ae43) | Feb 25, 2022 |
| Dell          | Precision 3551              | Notebook    | [9394fc8844](https://linux-hardware.org/?probe=9394fc8844) | Feb 24, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [98a6706e6a](https://linux-hardware.org/?probe=98a6706e6a) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [923930ee4e](https://linux-hardware.org/?probe=923930ee4e) | Feb 22, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [226452fec0](https://linux-hardware.org/?probe=226452fec0) | Feb 21, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1b5b236f76](https://linux-hardware.org/?probe=1b5b236f76) | Feb 21, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b0e0d82d12](https://linux-hardware.org/?probe=b0e0d82d12) | Feb 20, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [0ab1ff409b](https://linux-hardware.org/?probe=0ab1ff409b) | Feb 20, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [40f1930253](https://linux-hardware.org/?probe=40f1930253) | Feb 19, 2022 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [6baa824f3a](https://linux-hardware.org/?probe=6baa824f3a) | Feb 17, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2620ebab43](https://linux-hardware.org/?probe=2620ebab43) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [1055dc7082](https://linux-hardware.org/?probe=1055dc7082) | Feb 14, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [91dbebb5dd](https://linux-hardware.org/?probe=91dbebb5dd) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [34bb725d27](https://linux-hardware.org/?probe=34bb725d27) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3dd59d8ebe](https://linux-hardware.org/?probe=3dd59d8ebe) | Feb 13, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [4583e687ca](https://linux-hardware.org/?probe=4583e687ca) | Feb 13, 2022 |
| HP            | Compaq 15                   | Notebook    | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [6a16b1953c](https://linux-hardware.org/?probe=6a16b1953c) | Feb 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c5b6cfb8bc](https://linux-hardware.org/?probe=c5b6cfb8bc) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [8b31b460fc](https://linux-hardware.org/?probe=8b31b460fc) | Feb 11, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [6312e054ab](https://linux-hardware.org/?probe=6312e054ab) | Feb 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [b32b83ff4b](https://linux-hardware.org/?probe=b32b83ff4b) | Feb 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b8a4437ef8](https://linux-hardware.org/?probe=b8a4437ef8) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e06f742b06](https://linux-hardware.org/?probe=e06f742b06) | Feb 09, 2022 |
| whyopencom... | Unknown                     | Notebook    | [ed4f02d91d](https://linux-hardware.org/?probe=ed4f02d91d) | Feb 09, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [da25fcadb3](https://linux-hardware.org/?probe=da25fcadb3) | Feb 09, 2022 |
| HP            | 18E5                        | Desktop     | [85267de714](https://linux-hardware.org/?probe=85267de714) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| Dell          | Latitude E5410              | Notebook    | [fd73c50faa](https://linux-hardware.org/?probe=fd73c50faa) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [59a8e93ae4](https://linux-hardware.org/?probe=59a8e93ae4) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [99770a5e77](https://linux-hardware.org/?probe=99770a5e77) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| ZOTAC         | ZBOXNANO-ID67               | Mini pc     | [7eab522138](https://linux-hardware.org/?probe=7eab522138) | Feb 05, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [091a9c467d](https://linux-hardware.org/?probe=091a9c467d) | Feb 04, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [7ff1fc83fc](https://linux-hardware.org/?probe=7ff1fc83fc) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [dde47afaff](https://linux-hardware.org/?probe=dde47afaff) | Feb 03, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [60aaa89bfa](https://linux-hardware.org/?probe=60aaa89bfa) | Feb 03, 2022 |
| Unknown       | 1.0                         | Desktop     | [03f9d9de62](https://linux-hardware.org/?probe=03f9d9de62) | Jan 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [08a04a280f](https://linux-hardware.org/?probe=08a04a280f) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [cb51d0cf78](https://linux-hardware.org/?probe=cb51d0cf78) | Jan 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [31a1c1d4ab](https://linux-hardware.org/?probe=31a1c1d4ab) | Jan 28, 2022 |
| Clevo         | W76x/M77xCUH                | Notebook    | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f5b79eabf](https://linux-hardware.org/?probe=5f5b79eabf) | Jan 25, 2022 |
| AMI           | Cherry Trail Tablet         | Notebook    | [0560bf99e5](https://linux-hardware.org/?probe=0560bf99e5) | Jan 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [055decea61](https://linux-hardware.org/?probe=055decea61) | Jan 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [dbeeb0a6f3](https://linux-hardware.org/?probe=dbeeb0a6f3) | Jan 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [db3a3ddae1](https://linux-hardware.org/?probe=db3a3ddae1) | Jan 23, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a934945d5](https://linux-hardware.org/?probe=7a934945d5) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cf8776e11f](https://linux-hardware.org/?probe=cf8776e11f) | Jan 22, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4a0bd17330](https://linux-hardware.org/?probe=4a0bd17330) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c528c04bb7](https://linux-hardware.org/?probe=c528c04bb7) | Jan 22, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [e0b61bcde4](https://linux-hardware.org/?probe=e0b61bcde4) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [d2a1835844](https://linux-hardware.org/?probe=d2a1835844) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [328e103a74](https://linux-hardware.org/?probe=328e103a74) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0bb120993f](https://linux-hardware.org/?probe=0bb120993f) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [4b8a587819](https://linux-hardware.org/?probe=4b8a587819) | Jan 20, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e2161b5856](https://linux-hardware.org/?probe=e2161b5856) | Jan 20, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [3749e7dc2e](https://linux-hardware.org/?probe=3749e7dc2e) | Jan 19, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [f1c61e2a1b](https://linux-hardware.org/?probe=f1c61e2a1b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [d897de368d](https://linux-hardware.org/?probe=d897de368d) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [1478a3da5a](https://linux-hardware.org/?probe=1478a3da5a) | Jan 17, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [1c35674fd1](https://linux-hardware.org/?probe=1c35674fd1) | Jan 17, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [80a80d7619](https://linux-hardware.org/?probe=80a80d7619) | Jan 16, 2022 |
| HP            | 3048h                       | Desktop     | [d6f6435471](https://linux-hardware.org/?probe=d6f6435471) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [d508a12888](https://linux-hardware.org/?probe=d508a12888) | Jan 15, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2d14961843](https://linux-hardware.org/?probe=2d14961843) | Jan 14, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [0c991d9fae](https://linux-hardware.org/?probe=0c991d9fae) | Jan 14, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| HP            | 829A                        | Mini pc     | [9526ea61c6](https://linux-hardware.org/?probe=9526ea61c6) | Jan 13, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [88396d099b](https://linux-hardware.org/?probe=88396d099b) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [642e01d970](https://linux-hardware.org/?probe=642e01d970) | Jan 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0eb5cecbac](https://linux-hardware.org/?probe=0eb5cecbac) | Jan 12, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [bb65153cf2](https://linux-hardware.org/?probe=bb65153cf2) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [06f3fa0e22](https://linux-hardware.org/?probe=06f3fa0e22) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [ec88cd8e93](https://linux-hardware.org/?probe=ec88cd8e93) | Jan 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [102e1371f8](https://linux-hardware.org/?probe=102e1371f8) | Jan 11, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [0c0a6589e8](https://linux-hardware.org/?probe=0c0a6589e8) | Jan 11, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [2cbbce1a0e](https://linux-hardware.org/?probe=2cbbce1a0e) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [993e94e5fd](https://linux-hardware.org/?probe=993e94e5fd) | Jan 09, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [c908574f83](https://linux-hardware.org/?probe=c908574f83) | Jan 09, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [aad9837ee4](https://linux-hardware.org/?probe=aad9837ee4) | Jan 08, 2022 |
| Acer          | Aspire R7-572G              | Notebook    | [dc4a930b99](https://linux-hardware.org/?probe=dc4a930b99) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4d67659f6c](https://linux-hardware.org/?probe=4d67659f6c) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [b3428338c0](https://linux-hardware.org/?probe=b3428338c0) | Jan 07, 2022 |
| ASUSTek       | K53U                        | Notebook    | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad5ae136c9](https://linux-hardware.org/?probe=ad5ae136c9) | Jan 05, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| MSI           | 2A9Ch                       | Desktop     | [358b325347](https://linux-hardware.org/?probe=358b325347) | Jan 05, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [843345dfe6](https://linux-hardware.org/?probe=843345dfe6) | Jan 04, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [9980b9fb17](https://linux-hardware.org/?probe=9980b9fb17) | Jan 04, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [bb8b56ca21](https://linux-hardware.org/?probe=bb8b56ca21) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [6a1f7a20cf](https://linux-hardware.org/?probe=6a1f7a20cf) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [bd7de25478](https://linux-hardware.org/?probe=bd7de25478) | Jan 02, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [48524c94d1](https://linux-hardware.org/?probe=48524c94d1) | Jan 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [0551fb871e](https://linux-hardware.org/?probe=0551fb871e) | Dec 31, 2021 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c4103c8737](https://linux-hardware.org/?probe=c4103c8737) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [2e51628103](https://linux-hardware.org/?probe=2e51628103) | Dec 30, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [40eee8c893](https://linux-hardware.org/?probe=40eee8c893) | Dec 30, 2021 |
| Dell          | Latitude E5420              | Notebook    | [a2d1902586](https://linux-hardware.org/?probe=a2d1902586) | Dec 29, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [ca7f3a7275](https://linux-hardware.org/?probe=ca7f3a7275) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [1c36b4c1cd](https://linux-hardware.org/?probe=1c36b4c1cd) | Dec 29, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [997c8caab6](https://linux-hardware.org/?probe=997c8caab6) | Dec 29, 2021 |
| Acer          | Aspire V3-572               | Notebook    | [57f2afd2a3](https://linux-hardware.org/?probe=57f2afd2a3) | Dec 28, 2021 |
| Gigabyte      | H55M-USB3                   | Desktop     | [6ae95f862e](https://linux-hardware.org/?probe=6ae95f862e) | Dec 28, 2021 |
| Intel         | MONTARA                     | Desktop     | [963db2e79c](https://linux-hardware.org/?probe=963db2e79c) | Dec 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [41edb1b55b](https://linux-hardware.org/?probe=41edb1b55b) | Dec 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [79cc0303f4](https://linux-hardware.org/?probe=79cc0303f4) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a940c31cf7](https://linux-hardware.org/?probe=a940c31cf7) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [1afb1306eb](https://linux-hardware.org/?probe=1afb1306eb) | Dec 27, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3ab4ebdbfd](https://linux-hardware.org/?probe=3ab4ebdbfd) | Dec 27, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d9456116de](https://linux-hardware.org/?probe=d9456116de) | Dec 27, 2021 |
| HP            | 300-250                     | Notebook    | [94f3405ce4](https://linux-hardware.org/?probe=94f3405ce4) | Dec 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f113b07c3e](https://linux-hardware.org/?probe=f113b07c3e) | Dec 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cb4cb1ea51](https://linux-hardware.org/?probe=cb4cb1ea51) | Dec 26, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0195687c06](https://linux-hardware.org/?probe=0195687c06) | Dec 26, 2021 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [7ebdb585ab](https://linux-hardware.org/?probe=7ebdb585ab) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [527037fe8b](https://linux-hardware.org/?probe=527037fe8b) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0f19f19470](https://linux-hardware.org/?probe=0f19f19470) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | Notebook    | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| Shuttle       | FZ87                        | Desktop     | [e26f5a10e8](https://linux-hardware.org/?probe=e26f5a10e8) | Dec 24, 2021 |
| Shuttle       | FZ87                        | Desktop     | [62a0a858a6](https://linux-hardware.org/?probe=62a0a858a6) | Dec 24, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [d2ce6b29f7](https://linux-hardware.org/?probe=d2ce6b29f7) | Dec 23, 2021 |
| HP            | 3048h                       | Desktop     | [2e47687170](https://linux-hardware.org/?probe=2e47687170) | Dec 23, 2021 |
| HP            | ProBook 4740s               | Notebook    | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [da59408c08](https://linux-hardware.org/?probe=da59408c08) | Dec 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [72ba2d0d17](https://linux-hardware.org/?probe=72ba2d0d17) | Dec 22, 2021 |
| Lenovo        | 3176 SDK0J40697 WIN 3305... | Desktop     | [7ffa31df44](https://linux-hardware.org/?probe=7ffa31df44) | Dec 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [711a930635](https://linux-hardware.org/?probe=711a930635) | Dec 20, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [a55ed0d992](https://linux-hardware.org/?probe=a55ed0d992) | Dec 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f86ef0f23](https://linux-hardware.org/?probe=1f86ef0f23) | Dec 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [aa65cbb14e](https://linux-hardware.org/?probe=aa65cbb14e) | Dec 19, 2021 |
| HP            | 8056                        | Desktop     | [68992da248](https://linux-hardware.org/?probe=68992da248) | Dec 19, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [60db65ec3a](https://linux-hardware.org/?probe=60db65ec3a) | Dec 19, 2021 |
| HP            | 18E4                        | Desktop     | [b4a1d6b778](https://linux-hardware.org/?probe=b4a1d6b778) | Dec 19, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [3e25d6dd20](https://linux-hardware.org/?probe=3e25d6dd20) | Dec 18, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e1ac371752](https://linux-hardware.org/?probe=e1ac371752) | Dec 18, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Dell          | Latitude E5410              | Notebook    | [433ad50dd3](https://linux-hardware.org/?probe=433ad50dd3) | Dec 16, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [d103baf427](https://linux-hardware.org/?probe=d103baf427) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | Notebook    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [2d145ac87e](https://linux-hardware.org/?probe=2d145ac87e) | Dec 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c821efaed8](https://linux-hardware.org/?probe=c821efaed8) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [4fdfe223e0](https://linux-hardware.org/?probe=4fdfe223e0) | Dec 13, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [7abd85fdc5](https://linux-hardware.org/?probe=7abd85fdc5) | Dec 12, 2021 |
| ZOTAC         | ZBOX-EN1070/1060 Rev.00     | Mini pc     | [7348d34142](https://linux-hardware.org/?probe=7348d34142) | Dec 12, 2021 |
| HP            | 871A                        | Mini pc     | [fdbb17d3b2](https://linux-hardware.org/?probe=fdbb17d3b2) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | Notebook    | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [663a79c9de](https://linux-hardware.org/?probe=663a79c9de) | Dec 11, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [4166d874cc](https://linux-hardware.org/?probe=4166d874cc) | Dec 11, 2021 |
| ASRock        | B560M-HDV                   | Desktop     | [6390e2db9b](https://linux-hardware.org/?probe=6390e2db9b) | Dec 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [892d6ba035](https://linux-hardware.org/?probe=892d6ba035) | Dec 09, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd20a94e3e](https://linux-hardware.org/?probe=cd20a94e3e) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fa1e8b87a6](https://linux-hardware.org/?probe=fa1e8b87a6) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1dba035790](https://linux-hardware.org/?probe=1dba035790) | Dec 07, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [64c5154edc](https://linux-hardware.org/?probe=64c5154edc) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [ca6047ef7c](https://linux-hardware.org/?probe=ca6047ef7c) | Dec 06, 2021 |
| HP            | ENVY dv7                    | Notebook    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [6a2129aabd](https://linux-hardware.org/?probe=6a2129aabd) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| Razer         | Blade Stealth               | Notebook    | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [585c81c884](https://linux-hardware.org/?probe=585c81c884) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [0e777fade8](https://linux-hardware.org/?probe=0e777fade8) | Dec 03, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e2e7015852](https://linux-hardware.org/?probe=e2e7015852) | Dec 03, 2021 |
| Unknown       | 1.0                         | Desktop     | [412614529f](https://linux-hardware.org/?probe=412614529f) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74dcac77ec](https://linux-hardware.org/?probe=74dcac77ec) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [9bbe9ad940](https://linux-hardware.org/?probe=9bbe9ad940) | Nov 27, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [3b55838cb6](https://linux-hardware.org/?probe=3b55838cb6) | Nov 27, 2021 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b7cb8d0193](https://linux-hardware.org/?probe=b7cb8d0193) | Nov 27, 2021 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b1147db572](https://linux-hardware.org/?probe=b1147db572) | Nov 27, 2021 |
| MSI           | MS-17G                      | Notebook    | [0fd0763f15](https://linux-hardware.org/?probe=0fd0763f15) | Nov 26, 2021 |
| MSI           | MS-17G                      | Notebook    | [00c3cd9a83](https://linux-hardware.org/?probe=00c3cd9a83) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [51d432b698](https://linux-hardware.org/?probe=51d432b698) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [6c1248588e](https://linux-hardware.org/?probe=6c1248588e) | Nov 24, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [4ae4bcc876](https://linux-hardware.org/?probe=4ae4bcc876) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [2fbb75de6f](https://linux-hardware.org/?probe=2fbb75de6f) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [c70684a5e6](https://linux-hardware.org/?probe=c70684a5e6) | Nov 24, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [ab7e1ab2f6](https://linux-hardware.org/?probe=ab7e1ab2f6) | Nov 23, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [0a637eba53](https://linux-hardware.org/?probe=0a637eba53) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | Notebook    | [bf8a290d91](https://linux-hardware.org/?probe=bf8a290d91) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | Notebook    | [3b2959cf2d](https://linux-hardware.org/?probe=3b2959cf2d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [4c05633d40](https://linux-hardware.org/?probe=4c05633d40) | Nov 22, 2021 |
| HP            | Notebook                    | Notebook    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | Notebook    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c0960ee402](https://linux-hardware.org/?probe=c0960ee402) | Nov 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ec72611685](https://linux-hardware.org/?probe=ec72611685) | Nov 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [fa7d35906a](https://linux-hardware.org/?probe=fa7d35906a) | Nov 19, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [69a210799e](https://linux-hardware.org/?probe=69a210799e) | Nov 19, 2021 |
| HP            | ProLiant ML350 Gen9         | Desktop     | [9a5ec34f4b](https://linux-hardware.org/?probe=9a5ec34f4b) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Google        | Lars                        | Notebook    | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [701785b28a](https://linux-hardware.org/?probe=701785b28a) | Nov 17, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [2fd9cf16d9](https://linux-hardware.org/?probe=2fd9cf16d9) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2984f10b43](https://linux-hardware.org/?probe=2984f10b43) | Nov 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2067df0e1e](https://linux-hardware.org/?probe=2067df0e1e) | Nov 16, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [1e66881588](https://linux-hardware.org/?probe=1e66881588) | Nov 16, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [f40c4458aa](https://linux-hardware.org/?probe=f40c4458aa) | Nov 16, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [8facfa8bce](https://linux-hardware.org/?probe=8facfa8bce) | Nov 15, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [d193380f1d](https://linux-hardware.org/?probe=d193380f1d) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Dell          | Latitude E7240              | Notebook    | [aaf6395a70](https://linux-hardware.org/?probe=aaf6395a70) | Nov 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [09a1713d46](https://linux-hardware.org/?probe=09a1713d46) | Nov 14, 2021 |
| Dell          | Latitude E7270              | Notebook    | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| HP            | EliteBook 735 G5            | Notebook    | [79600db29f](https://linux-hardware.org/?probe=79600db29f) | Nov 14, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [30b1c49250](https://linux-hardware.org/?probe=30b1c49250) | Nov 13, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a283cb744b](https://linux-hardware.org/?probe=a283cb744b) | Nov 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [366558c9a6](https://linux-hardware.org/?probe=366558c9a6) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [20898da2a5](https://linux-hardware.org/?probe=20898da2a5) | Nov 10, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [e0856ca7fa](https://linux-hardware.org/?probe=e0856ca7fa) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3876a60641](https://linux-hardware.org/?probe=3876a60641) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [92b50813ac](https://linux-hardware.org/?probe=92b50813ac) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| Intel         | DH77DF AAG40293-300         | Desktop     | [64ba244f45](https://linux-hardware.org/?probe=64ba244f45) | Nov 09, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [e0d50907c2](https://linux-hardware.org/?probe=e0d50907c2) | Nov 07, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [e4a203dda2](https://linux-hardware.org/?probe=e4a203dda2) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [86f84e606c](https://linux-hardware.org/?probe=86f84e606c) | Nov 05, 2021 |
| Acer          | V3-771                      | Notebook    | [bf99ad481c](https://linux-hardware.org/?probe=bf99ad481c) | Nov 04, 2021 |
| ASUSTek       | A85XM-A                     | Desktop     | [f28dea1e67](https://linux-hardware.org/?probe=f28dea1e67) | Nov 03, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [84e47bb477](https://linux-hardware.org/?probe=84e47bb477) | Nov 03, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [5fabc60d11](https://linux-hardware.org/?probe=5fabc60d11) | Nov 03, 2021 |
| HP            | 1494                        | Desktop     | [ef0237e3cf](https://linux-hardware.org/?probe=ef0237e3cf) | Nov 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [bc49b41641](https://linux-hardware.org/?probe=bc49b41641) | Nov 03, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [8686d92d45](https://linux-hardware.org/?probe=8686d92d45) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [6c7ecc284b](https://linux-hardware.org/?probe=6c7ecc284b) | Oct 31, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [f35cfefa93](https://linux-hardware.org/?probe=f35cfefa93) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [3f7a2585fe](https://linux-hardware.org/?probe=3f7a2585fe) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [e6958a71d6](https://linux-hardware.org/?probe=e6958a71d6) | Oct 31, 2021 |
| Acer          | TravelMate P459-G2-MG       | Notebook    | [05087f89c1](https://linux-hardware.org/?probe=05087f89c1) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| Acer          | TravelMate P459-G2-MG       | Notebook    | [4a80b949aa](https://linux-hardware.org/?probe=4a80b949aa) | Oct 30, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [d0307fd66e](https://linux-hardware.org/?probe=d0307fd66e) | Oct 29, 2021 |
| HP            | 1998                        | Desktop     | [f943d839a8](https://linux-hardware.org/?probe=f943d839a8) | Oct 29, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [a5abf5d5ee](https://linux-hardware.org/?probe=a5abf5d5ee) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Medion        | S3409 MD60234               | Notebook    | [4bb4415dae](https://linux-hardware.org/?probe=4bb4415dae) | Oct 27, 2021 |
| Acer          | Aspire X3450                | Desktop     | [8f27aff70b](https://linux-hardware.org/?probe=8f27aff70b) | Oct 27, 2021 |
| Supermicro    | X9DR3-F                     | Desktop     | [6908407322](https://linux-hardware.org/?probe=6908407322) | Oct 26, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | Notebook    | [a567978a3c](https://linux-hardware.org/?probe=a567978a3c) | Oct 26, 2021 |
| Acer          | V3-771                      | Notebook    | [b953b67d06](https://linux-hardware.org/?probe=b953b67d06) | Oct 25, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [d19235c3d0](https://linux-hardware.org/?probe=d19235c3d0) | Oct 24, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [681b537e82](https://linux-hardware.org/?probe=681b537e82) | Oct 23, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [5ebedd4a1c](https://linux-hardware.org/?probe=5ebedd4a1c) | Oct 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d53c49a17f](https://linux-hardware.org/?probe=d53c49a17f) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [117223995c](https://linux-hardware.org/?probe=117223995c) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [e97646cc2e](https://linux-hardware.org/?probe=e97646cc2e) | Oct 23, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [3517455df5](https://linux-hardware.org/?probe=3517455df5) | Oct 22, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [ff356cba89](https://linux-hardware.org/?probe=ff356cba89) | Oct 22, 2021 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [b198944ad7](https://linux-hardware.org/?probe=b198944ad7) | Oct 22, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [2edb67185b](https://linux-hardware.org/?probe=2edb67185b) | Oct 21, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [717c3395f2](https://linux-hardware.org/?probe=717c3395f2) | Oct 20, 2021 |
| Medion        | E6226                       | Notebook    | [ebc0f3d72b](https://linux-hardware.org/?probe=ebc0f3d72b) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [4f400bb9ab](https://linux-hardware.org/?probe=4f400bb9ab) | Oct 20, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [4d7535970d](https://linux-hardware.org/?probe=4d7535970d) | Oct 20, 2021 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [88785336ba](https://linux-hardware.org/?probe=88785336ba) | Oct 19, 2021 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [b8d302afbb](https://linux-hardware.org/?probe=b8d302afbb) | Oct 19, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [6bb186c28b](https://linux-hardware.org/?probe=6bb186c28b) | Oct 19, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [d8302cc197](https://linux-hardware.org/?probe=d8302cc197) | Oct 19, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [dc42de3c30](https://linux-hardware.org/?probe=dc42de3c30) | Oct 18, 2021 |
| HP            | 86C7                        | All in one  | [5d87deb347](https://linux-hardware.org/?probe=5d87deb347) | Oct 18, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [a3f6fa0ac9](https://linux-hardware.org/?probe=a3f6fa0ac9) | Oct 17, 2021 |
| Gigabyte      | H55M-USB3                   | Desktop     | [4f5274c16a](https://linux-hardware.org/?probe=4f5274c16a) | Oct 17, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [dda062734d](https://linux-hardware.org/?probe=dda062734d) | Oct 17, 2021 |
| HP            | 870C                        | Desktop     | [8b056a8a9f](https://linux-hardware.org/?probe=8b056a8a9f) | Oct 16, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [4ee6c35b8f](https://linux-hardware.org/?probe=4ee6c35b8f) | Oct 16, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [bf7f394d00](https://linux-hardware.org/?probe=bf7f394d00) | Oct 16, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [338292d813](https://linux-hardware.org/?probe=338292d813) | Oct 15, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [a775c0fa85](https://linux-hardware.org/?probe=a775c0fa85) | Oct 15, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| HP            | 8054                        | Desktop     | [ba0e318652](https://linux-hardware.org/?probe=ba0e318652) | Oct 15, 2021 |
| Samsung       | DP505A2G-K01CH SAMSUNG_S... | All in one  | [4939b251f2](https://linux-hardware.org/?probe=4939b251f2) | Oct 15, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Dell          | Latitude 5410               | Notebook    | [bdd46a0cd7](https://linux-hardware.org/?probe=bdd46a0cd7) | Oct 14, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [62872f38de](https://linux-hardware.org/?probe=62872f38de) | Oct 14, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [3638982195](https://linux-hardware.org/?probe=3638982195) | Oct 12, 2021 |
| HP            | 8054                        | Desktop     | [9a1bdf2e07](https://linux-hardware.org/?probe=9a1bdf2e07) | Oct 10, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [cfbe862160](https://linux-hardware.org/?probe=cfbe862160) | Oct 10, 2021 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [b72f6d9f64](https://linux-hardware.org/?probe=b72f6d9f64) | Oct 08, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [38dedb920e](https://linux-hardware.org/?probe=38dedb920e) | Oct 08, 2021 |
| ASRock        | J4105B-ITX                  | Desktop     | [33fc4b9e37](https://linux-hardware.org/?probe=33fc4b9e37) | Oct 08, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [e9ee820848](https://linux-hardware.org/?probe=e9ee820848) | Oct 06, 2021 |
| ASUSTek       | P7P55D LE                   | Desktop     | [21e7391f6a](https://linux-hardware.org/?probe=21e7391f6a) | Oct 05, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [a31bd40281](https://linux-hardware.org/?probe=a31bd40281) | Oct 03, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [770a47642f](https://linux-hardware.org/?probe=770a47642f) | Oct 03, 2021 |
| Acer          | Aspire A515-52              | Notebook    | [1f5c815672](https://linux-hardware.org/?probe=1f5c815672) | Oct 02, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e68e81c986](https://linux-hardware.org/?probe=e68e81c986) | Sep 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f273082d09](https://linux-hardware.org/?probe=f273082d09) | Sep 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [feed153041](https://linux-hardware.org/?probe=feed153041) | Sep 28, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [05ad040f44](https://linux-hardware.org/?probe=05ad040f44) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [af3fbbd82c](https://linux-hardware.org/?probe=af3fbbd82c) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [28c82e6c3c](https://linux-hardware.org/?probe=28c82e6c3c) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7a75c1404b](https://linux-hardware.org/?probe=7a75c1404b) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [79aa111080](https://linux-hardware.org/?probe=79aa111080) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [99b52f5b1a](https://linux-hardware.org/?probe=99b52f5b1a) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [7e50f2bf77](https://linux-hardware.org/?probe=7e50f2bf77) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d516cbbc97](https://linux-hardware.org/?probe=d516cbbc97) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [825770fd12](https://linux-hardware.org/?probe=825770fd12) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e6770f9bd](https://linux-hardware.org/?probe=8e6770f9bd) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a022c3ec02](https://linux-hardware.org/?probe=a022c3ec02) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [991e447de1](https://linux-hardware.org/?probe=991e447de1) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3470189758](https://linux-hardware.org/?probe=3470189758) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8a23b4112f](https://linux-hardware.org/?probe=8a23b4112f) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1843bfdb65](https://linux-hardware.org/?probe=1843bfdb65) | Sep 27, 2021 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [96079334bd](https://linux-hardware.org/?probe=96079334bd) | Sep 27, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bc4d5fd16b](https://linux-hardware.org/?probe=bc4d5fd16b) | Sep 27, 2021 |
| Intel         | W2600CR G21602-302          | Server      | [e70645d3e6](https://linux-hardware.org/?probe=e70645d3e6) | Sep 27, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [8db88d13ec](https://linux-hardware.org/?probe=8db88d13ec) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [cc4ac84959](https://linux-hardware.org/?probe=cc4ac84959) | Sep 22, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [521913f7c9](https://linux-hardware.org/?probe=521913f7c9) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [2c7e4f944f](https://linux-hardware.org/?probe=2c7e4f944f) | Sep 18, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [a0a6460520](https://linux-hardware.org/?probe=a0a6460520) | Sep 17, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [de56866167](https://linux-hardware.org/?probe=de56866167) | Sep 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [4340e989f9](https://linux-hardware.org/?probe=4340e989f9) | Sep 17, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [c1fd594d52](https://linux-hardware.org/?probe=c1fd594d52) | Sep 17, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [17b2d3483a](https://linux-hardware.org/?probe=17b2d3483a) | Sep 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b2b889b773](https://linux-hardware.org/?probe=b2b889b773) | Sep 16, 2021 |
| Dell          | 0YJPT1 A00                  | Desktop     | [69d571e9f5](https://linux-hardware.org/?probe=69d571e9f5) | Sep 15, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ab2e5dcff2](https://linux-hardware.org/?probe=ab2e5dcff2) | Sep 14, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f01a6435b7](https://linux-hardware.org/?probe=f01a6435b7) | Sep 14, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [491b5db2ce](https://linux-hardware.org/?probe=491b5db2ce) | Sep 12, 2021 |
| Gigabyte      | P35-DS4                     | Desktop     | [ff9057981b](https://linux-hardware.org/?probe=ff9057981b) | Sep 11, 2021 |
| Gigabyte      | P35-DS4                     | Desktop     | [d5cbc70a78](https://linux-hardware.org/?probe=d5cbc70a78) | Sep 11, 2021 |
| Lenovo        | ThinkPad T550 20CJS03300    | Notebook    | [2b53cd0d2d](https://linux-hardware.org/?probe=2b53cd0d2d) | Sep 11, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | Notebook    | [60ee8c9731](https://linux-hardware.org/?probe=60ee8c9731) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [737878ed56](https://linux-hardware.org/?probe=737878ed56) | Sep 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS27X02    | Notebook    | [c11d22f126](https://linux-hardware.org/?probe=c11d22f126) | Sep 10, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74d478552c](https://linux-hardware.org/?probe=74d478552c) | Sep 10, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [49f1f54552](https://linux-hardware.org/?probe=49f1f54552) | Sep 09, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3333d2aabd](https://linux-hardware.org/?probe=3333d2aabd) | Sep 09, 2021 |
| Lenovo        | ThinkPad L460 20FVS01500    | Notebook    | [065324adcb](https://linux-hardware.org/?probe=065324adcb) | Sep 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| HP            | 8750                        | Desktop     | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [522f36731e](https://linux-hardware.org/?probe=522f36731e) | Sep 07, 2021 |
| Medion        | S3409 MD60234               | Notebook    | [30a93543cd](https://linux-hardware.org/?probe=30a93543cd) | Sep 07, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26db00edc0](https://linux-hardware.org/?probe=26db00edc0) | Sep 06, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [c9716b0149](https://linux-hardware.org/?probe=c9716b0149) | Sep 06, 2021 |
| Medion        | S3409 MD60234               | Notebook    | [274fe63960](https://linux-hardware.org/?probe=274fe63960) | Sep 06, 2021 |
| HP            | 870C                        | Desktop     | [f46fa4ba94](https://linux-hardware.org/?probe=f46fa4ba94) | Sep 06, 2021 |
| HP            | 870C                        | Desktop     | [fcd88590bc](https://linux-hardware.org/?probe=fcd88590bc) | Sep 06, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c98e112d49](https://linux-hardware.org/?probe=c98e112d49) | Sep 05, 2021 |
| MSI           | IONA                        | Desktop     | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| MSI           | AMETHYST-M                  | Desktop     | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [41a2fef2aa](https://linux-hardware.org/?probe=41a2fef2aa) | Sep 05, 2021 |
| MSI           | IONA                        | Desktop     | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| HP            | 3396                        | Desktop     | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [022e87f791](https://linux-hardware.org/?probe=022e87f791) | Sep 04, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [a507f9835b](https://linux-hardware.org/?probe=a507f9835b) | Sep 03, 2021 |
| ASUSTek       | P7P55D LE                   | Desktop     | [8bbe7e58ae](https://linux-hardware.org/?probe=8bbe7e58ae) | Sep 02, 2021 |
| ASUSTek       | P7P55D LE                   | Desktop     | [21fd5c096a](https://linux-hardware.org/?probe=21fd5c096a) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [61fdddc7a9](https://linux-hardware.org/?probe=61fdddc7a9) | Sep 01, 2021 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [87353376d7](https://linux-hardware.org/?probe=87353376d7) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [4fc1ff5f76](https://linux-hardware.org/?probe=4fc1ff5f76) | Aug 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [2087b72fe1](https://linux-hardware.org/?probe=2087b72fe1) | Aug 31, 2021 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [4d4510dbfb](https://linux-hardware.org/?probe=4d4510dbfb) | Aug 30, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [6f82a1cdeb](https://linux-hardware.org/?probe=6f82a1cdeb) | Aug 30, 2021 |
| Samsung       | 700G7C                      | Notebook    | [9bdbd478e5](https://linux-hardware.org/?probe=9bdbd478e5) | Aug 29, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [9061a72f3a](https://linux-hardware.org/?probe=9061a72f3a) | Aug 29, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [666660f555](https://linux-hardware.org/?probe=666660f555) | Aug 29, 2021 |
| Dell          | Precision M6700             | Notebook    | [c1e66e1633](https://linux-hardware.org/?probe=c1e66e1633) | Aug 28, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [aeec497ed8](https://linux-hardware.org/?probe=aeec497ed8) | Aug 28, 2021 |
| ASUSTek       | Q87M-E                      | Desktop     | [588e2a68e5](https://linux-hardware.org/?probe=588e2a68e5) | Aug 28, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9b335e87fe](https://linux-hardware.org/?probe=9b335e87fe) | Aug 28, 2021 |
| Pegatron      | IPMSB-GS                    | Desktop     | [b17f032a44](https://linux-hardware.org/?probe=b17f032a44) | Aug 27, 2021 |
| Pegatron      | IPMSB-GS                    | Desktop     | [9d2bbbabf1](https://linux-hardware.org/?probe=9d2bbbabf1) | Aug 27, 2021 |
| Shuttle       | FH61V                       | Desktop     | [11b6744d1c](https://linux-hardware.org/?probe=11b6744d1c) | Aug 27, 2021 |
| TrekStor      | Surfbook E11B               | Notebook    | [9014dfda1f](https://linux-hardware.org/?probe=9014dfda1f) | Aug 26, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [4971ce2382](https://linux-hardware.org/?probe=4971ce2382) | Aug 25, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [2135d34339](https://linux-hardware.org/?probe=2135d34339) | Aug 25, 2021 |
| Shuttle       | FH61V                       | Desktop     | [1b74c0ad1d](https://linux-hardware.org/?probe=1b74c0ad1d) | Aug 25, 2021 |
| Dell          | Precision 5520              | Notebook    | [12782a8da6](https://linux-hardware.org/?probe=12782a8da6) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | Notebook    | [76b34b8383](https://linux-hardware.org/?probe=76b34b8383) | Aug 24, 2021 |
| ASUSTek       | ZenBook UX431DA             | Notebook    | [35b4ea3ba9](https://linux-hardware.org/?probe=35b4ea3ba9) | Aug 24, 2021 |
| Dell          | Precision 5520              | Notebook    | [43f1c9c69c](https://linux-hardware.org/?probe=43f1c9c69c) | Aug 24, 2021 |
| HP            | 8054                        | Desktop     | [d54cd14c63](https://linux-hardware.org/?probe=d54cd14c63) | Aug 24, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3598b4e555](https://linux-hardware.org/?probe=3598b4e555) | Aug 23, 2021 |
| Dell          | Latitude E5550              | Notebook    | [186ab38330](https://linux-hardware.org/?probe=186ab38330) | Aug 23, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [e59555689c](https://linux-hardware.org/?probe=e59555689c) | Aug 23, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [ddd4cdd7ca](https://linux-hardware.org/?probe=ddd4cdd7ca) | Aug 22, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [6713ee6c8f](https://linux-hardware.org/?probe=6713ee6c8f) | Aug 22, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [47cea1b5c7](https://linux-hardware.org/?probe=47cea1b5c7) | Aug 20, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| Dell          | Precision 5520              | Notebook    | [bb6728e105](https://linux-hardware.org/?probe=bb6728e105) | Aug 19, 2021 |
| Dell          | Precision 5520              | Notebook    | [87389dc90a](https://linux-hardware.org/?probe=87389dc90a) | Aug 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d55ce04f89](https://linux-hardware.org/?probe=d55ce04f89) | Aug 18, 2021 |
| Acer          | V3-771                      | Notebook    | [5235c8cb39](https://linux-hardware.org/?probe=5235c8cb39) | Aug 18, 2021 |
| Acer          | Aspire 5253                 | Notebook    | [8d12d69ada](https://linux-hardware.org/?probe=8d12d69ada) | Aug 18, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [2ca8cc81b1](https://linux-hardware.org/?probe=2ca8cc81b1) | Aug 18, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [95aad48ba3](https://linux-hardware.org/?probe=95aad48ba3) | Aug 17, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [eb50acee36](https://linux-hardware.org/?probe=eb50acee36) | Aug 16, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [2afd21c6f7](https://linux-hardware.org/?probe=2afd21c6f7) | Aug 16, 2021 |
| Acer          | Aspire 5253                 | Notebook    | [06a6ece9cb](https://linux-hardware.org/?probe=06a6ece9cb) | Aug 16, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [6d761276c9](https://linux-hardware.org/?probe=6d761276c9) | Aug 16, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [d628c6c320](https://linux-hardware.org/?probe=d628c6c320) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [8724bdb133](https://linux-hardware.org/?probe=8724bdb133) | Aug 15, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [21e8e956d2](https://linux-hardware.org/?probe=21e8e956d2) | Aug 15, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [8bd4184e25](https://linux-hardware.org/?probe=8bd4184e25) | Aug 15, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [64f4c407c6](https://linux-hardware.org/?probe=64f4c407c6) | Aug 14, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [b3ff3985c5](https://linux-hardware.org/?probe=b3ff3985c5) | Aug 13, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [4b51090679](https://linux-hardware.org/?probe=4b51090679) | Aug 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [f78358fed7](https://linux-hardware.org/?probe=f78358fed7) | Aug 13, 2021 |
| Dell          | Latitude 7490               | Notebook    | [3c3c535058](https://linux-hardware.org/?probe=3c3c535058) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4dc4a0efe0](https://linux-hardware.org/?probe=4dc4a0efe0) | Aug 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6e44d2998d](https://linux-hardware.org/?probe=6e44d2998d) | Aug 13, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [3f6cd51532](https://linux-hardware.org/?probe=3f6cd51532) | Aug 13, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0fb5cb1e91](https://linux-hardware.org/?probe=0fb5cb1e91) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [de1de1fa76](https://linux-hardware.org/?probe=de1de1fa76) | Aug 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d7c235a5d9](https://linux-hardware.org/?probe=d7c235a5d9) | Aug 12, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [142e0703fb](https://linux-hardware.org/?probe=142e0703fb) | Aug 12, 2021 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [5091bbdda5](https://linux-hardware.org/?probe=5091bbdda5) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [9fef85ae5d](https://linux-hardware.org/?probe=9fef85ae5d) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| Dell          | Latitude E7440              | Notebook    | [33a205253e](https://linux-hardware.org/?probe=33a205253e) | Aug 10, 2021 |
| HP            | ENVY dv7                    | Notebook    | [888257031e](https://linux-hardware.org/?probe=888257031e) | Aug 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [92fb2e26c0](https://linux-hardware.org/?probe=92fb2e26c0) | Aug 10, 2021 |
| Dell          | Latitude E7440              | Notebook    | [89a521499a](https://linux-hardware.org/?probe=89a521499a) | Aug 10, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [9092457b4b](https://linux-hardware.org/?probe=9092457b4b) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [05628cae80](https://linux-hardware.org/?probe=05628cae80) | Aug 09, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Biostar       | X370GTN                     | Desktop     | [eeff407867](https://linux-hardware.org/?probe=eeff407867) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | Notebook    | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| GPD           | P2 MAX                      | Notebook    | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [15b26f4936](https://linux-hardware.org/?probe=15b26f4936) | Aug 07, 2021 |
| MSI           | Z97 XPOWER AC               | Desktop     | [a8b7705861](https://linux-hardware.org/?probe=a8b7705861) | Aug 07, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [ed862d4cb6](https://linux-hardware.org/?probe=ed862d4cb6) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | Desktop     | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | Notebook    | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | Desktop     | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [7d11767c07](https://linux-hardware.org/?probe=7d11767c07) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [b42131915e](https://linux-hardware.org/?probe=b42131915e) | Aug 05, 2021 |
| Lenovo        | ThinkPad T510 43494JG       | Notebook    | [80fafef64f](https://linux-hardware.org/?probe=80fafef64f) | Aug 05, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [8a1231d4f0](https://linux-hardware.org/?probe=8a1231d4f0) | Aug 05, 2021 |
| Dell          | Inspiron 15-5578            | Notebook    | [1169a22f51](https://linux-hardware.org/?probe=1169a22f51) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | Notebook    | [0724f0e60d](https://linux-hardware.org/?probe=0724f0e60d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T420 4236NGG       | Notebook    | [5b70933531](https://linux-hardware.org/?probe=5b70933531) | Aug 01, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [730d886e60](https://linux-hardware.org/?probe=730d886e60) | Jul 31, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e9254ad52f](https://linux-hardware.org/?probe=e9254ad52f) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [3963220295](https://linux-hardware.org/?probe=3963220295) | Jul 31, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [f8eb40a0a3](https://linux-hardware.org/?probe=f8eb40a0a3) | Jul 30, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [9cf9065745](https://linux-hardware.org/?probe=9cf9065745) | Jul 30, 2021 |
| Dell          | Latitude E5550              | Notebook    | [84d60c9f30](https://linux-hardware.org/?probe=84d60c9f30) | Jul 30, 2021 |
| ASRock        | Z170 OC Formula             | Desktop     | [0d1ca849b8](https://linux-hardware.org/?probe=0d1ca849b8) | Jul 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [4ad09b336f](https://linux-hardware.org/?probe=4ad09b336f) | Jul 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [423bc2b7a1](https://linux-hardware.org/?probe=423bc2b7a1) | Jul 28, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8dbd1ca0eb](https://linux-hardware.org/?probe=8dbd1ca0eb) | Jul 26, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [cde8deea7e](https://linux-hardware.org/?probe=cde8deea7e) | Jul 26, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | Notebook    | [7330b29e94](https://linux-hardware.org/?probe=7330b29e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | Notebook    | [1a104c4440](https://linux-hardware.org/?probe=1a104c4440) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| GPD           | P2 MAX                      | Notebook    | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [a52bc56d5e](https://linux-hardware.org/?probe=a52bc56d5e) | Jul 23, 2021 |
| Medion        | E6226                       | Notebook    | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| ASUSTek       | ZenBook Q536FD              | Convertible | [94fbb604be](https://linux-hardware.org/?probe=94fbb604be) | Jul 22, 2021 |
| HP            | Pavilion g7                 | Notebook    | [59f46869ee](https://linux-hardware.org/?probe=59f46869ee) | Jul 21, 2021 |
| HP            | Pavilion g7                 | Notebook    | [b71a21e87a](https://linux-hardware.org/?probe=b71a21e87a) | Jul 21, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ece0155c70](https://linux-hardware.org/?probe=ece0155c70) | Jul 20, 2021 |
| Medion        | P6618                       | Notebook    | [d8b3d2db11](https://linux-hardware.org/?probe=d8b3d2db11) | Jul 20, 2021 |
| Dell          | 0W13NR A05                  | Server      | [ad7d2477f8](https://linux-hardware.org/?probe=ad7d2477f8) | Jul 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [592fa7e11f](https://linux-hardware.org/?probe=592fa7e11f) | Jul 18, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8af5553693](https://linux-hardware.org/?probe=8af5553693) | Jul 18, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [5c3f0aef89](https://linux-hardware.org/?probe=5c3f0aef89) | Jul 17, 2021 |
| Sony          | SVE14A2V1EW                 | Notebook    | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [c61db52d00](https://linux-hardware.org/?probe=c61db52d00) | Jul 16, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [65c592c13e](https://linux-hardware.org/?probe=65c592c13e) | Jul 15, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [432f6ee87d](https://linux-hardware.org/?probe=432f6ee87d) | Jul 14, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [90fcb82f7e](https://linux-hardware.org/?probe=90fcb82f7e) | Jul 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [427828621f](https://linux-hardware.org/?probe=427828621f) | Jul 12, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [7aa338a8dc](https://linux-hardware.org/?probe=7aa338a8dc) | Jul 12, 2021 |
| Toshiba       | NB550D                      | Notebook    | [6e4b998cc0](https://linux-hardware.org/?probe=6e4b998cc0) | Jul 12, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [04163e3fa8](https://linux-hardware.org/?probe=04163e3fa8) | Jul 12, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1b90aa16a1](https://linux-hardware.org/?probe=1b90aa16a1) | Jul 09, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [97bc068489](https://linux-hardware.org/?probe=97bc068489) | Jul 09, 2021 |
| Notebook      | NS50MU                      | Notebook    | [6841e398e3](https://linux-hardware.org/?probe=6841e398e3) | Jul 09, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [179a7af7be](https://linux-hardware.org/?probe=179a7af7be) | Jul 09, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [c2ed93c130](https://linux-hardware.org/?probe=c2ed93c130) | Jul 07, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | Notebook    | [6c9599ccf7](https://linux-hardware.org/?probe=6c9599ccf7) | Jul 07, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [8887f14351](https://linux-hardware.org/?probe=8887f14351) | Jul 06, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [3aa1e79866](https://linux-hardware.org/?probe=3aa1e79866) | Jul 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [70c0bc44a2](https://linux-hardware.org/?probe=70c0bc44a2) | Jul 05, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | Notebook    | [7bbd48efde](https://linux-hardware.org/?probe=7bbd48efde) | Jul 03, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [ca01402661](https://linux-hardware.org/?probe=ca01402661) | Jul 03, 2021 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [734f246fde](https://linux-hardware.org/?probe=734f246fde) | Jul 02, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [0ffffb72ed](https://linux-hardware.org/?probe=0ffffb72ed) | Jul 02, 2021 |
| Lenovo        | ThinkPad T450s 20BX004KM... | Notebook    | [dbd8629d3c](https://linux-hardware.org/?probe=dbd8629d3c) | Jul 02, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [64603b3562](https://linux-hardware.org/?probe=64603b3562) | Jul 02, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [78ad5dbea0](https://linux-hardware.org/?probe=78ad5dbea0) | Jul 01, 2021 |
| HP            | 8056                        | Desktop     | [d10cd539f1](https://linux-hardware.org/?probe=d10cd539f1) | Jul 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [6fde0ddd03](https://linux-hardware.org/?probe=6fde0ddd03) | Jul 01, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [ddaae68bd8](https://linux-hardware.org/?probe=ddaae68bd8) | Jun 30, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [934190169c](https://linux-hardware.org/?probe=934190169c) | Jun 30, 2021 |
| Lenovo        | 31900058 STD                | Desktop     | [338127e8ca](https://linux-hardware.org/?probe=338127e8ca) | Jun 26, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [5d5b2c944a](https://linux-hardware.org/?probe=5d5b2c944a) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [68cd01f446](https://linux-hardware.org/?probe=68cd01f446) | Jun 25, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [d6bb5b7636](https://linux-hardware.org/?probe=d6bb5b7636) | Jun 25, 2021 |
| Lenovo        | ThinkPad E570 20H5006VMZ    | Notebook    | [05a46ada33](https://linux-hardware.org/?probe=05a46ada33) | Jun 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [ea4ab7e535](https://linux-hardware.org/?probe=ea4ab7e535) | Jun 22, 2021 |
| HP            | 8703                        | Desktop     | [e43f806f55](https://linux-hardware.org/?probe=e43f806f55) | Jun 21, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJ0... | Convertible | [e9486a38da](https://linux-hardware.org/?probe=e9486a38da) | Jun 19, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [94fbab0837](https://linux-hardware.org/?probe=94fbab0837) | Jun 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7366bb28e8](https://linux-hardware.org/?probe=7366bb28e8) | Jun 19, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [822acd5e9b](https://linux-hardware.org/?probe=822acd5e9b) | Jun 19, 2021 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4c0b858cde](https://linux-hardware.org/?probe=4c0b858cde) | Jun 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [32c83da9dd](https://linux-hardware.org/?probe=32c83da9dd) | Jun 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [6687380bd7](https://linux-hardware.org/?probe=6687380bd7) | Jun 18, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [a69ed7dfd9](https://linux-hardware.org/?probe=a69ed7dfd9) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [b10313d89f](https://linux-hardware.org/?probe=b10313d89f) | Jun 17, 2021 |
| Dell          | 0D28YY A00                  | Desktop     | [d9cac45ec3](https://linux-hardware.org/?probe=d9cac45ec3) | Jun 16, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [790371eae7](https://linux-hardware.org/?probe=790371eae7) | Jun 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [96ee62e1dc](https://linux-hardware.org/?probe=96ee62e1dc) | Jun 15, 2021 |
| MSI           | B360M PRO-VH                | Desktop     | [78845a4897](https://linux-hardware.org/?probe=78845a4897) | Jun 15, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [f0a5e0cbb6](https://linux-hardware.org/?probe=f0a5e0cbb6) | Jun 13, 2021 |
| Dell          | 0YHMCJ A01                  | Server      | [a35e7d3eb0](https://linux-hardware.org/?probe=a35e7d3eb0) | Jun 11, 2021 |
| Dell          | Latitude E6510              | Notebook    | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Acer          | Aspire X3400                | Desktop     | [8fcc9b6607](https://linux-hardware.org/?probe=8fcc9b6607) | Jun 10, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [5ac932248a](https://linux-hardware.org/?probe=5ac932248a) | Jun 10, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [455a20d0a7](https://linux-hardware.org/?probe=455a20d0a7) | Jun 10, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [bd3527232d](https://linux-hardware.org/?probe=bd3527232d) | Jun 09, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [68ec58f92a](https://linux-hardware.org/?probe=68ec58f92a) | Jun 08, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [503cffa288](https://linux-hardware.org/?probe=503cffa288) | Jun 08, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5521709029](https://linux-hardware.org/?probe=5521709029) | Jun 08, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [467c46c227](https://linux-hardware.org/?probe=467c46c227) | Jun 08, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5456739d8f](https://linux-hardware.org/?probe=5456739d8f) | Jun 08, 2021 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [95708a9a82](https://linux-hardware.org/?probe=95708a9a82) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | Notebook    | [0a5cb29f98](https://linux-hardware.org/?probe=0a5cb29f98) | Jun 07, 2021 |
| HP            | ProBook 4510s (NX684EA)     | Notebook    | [55591c1e24](https://linux-hardware.org/?probe=55591c1e24) | Jun 07, 2021 |
| Toshiba       | Satellite Pro C850-1GR      | Notebook    | [29f66db2d1](https://linux-hardware.org/?probe=29f66db2d1) | Jun 07, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [188fcc64df](https://linux-hardware.org/?probe=188fcc64df) | Jun 06, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [08b1e4c99f](https://linux-hardware.org/?probe=08b1e4c99f) | Jun 05, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [940e48e534](https://linux-hardware.org/?probe=940e48e534) | Jun 05, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [c0022674fa](https://linux-hardware.org/?probe=c0022674fa) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [32b9a694b3](https://linux-hardware.org/?probe=32b9a694b3) | Jun 04, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [93185b618c](https://linux-hardware.org/?probe=93185b618c) | Jun 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | 3032h                       | Desktop     | [dade0cb1d6](https://linux-hardware.org/?probe=dade0cb1d6) | Jun 03, 2021 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [c1ec69ad60](https://linux-hardware.org/?probe=c1ec69ad60) | Jun 02, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [62ddf1b4f0](https://linux-hardware.org/?probe=62ddf1b4f0) | May 31, 2021 |
| HP            | 3032h                       | Desktop     | [ea009f77d1](https://linux-hardware.org/?probe=ea009f77d1) | May 31, 2021 |
| HP            | 8056                        | Desktop     | [fc6d4c2e7d](https://linux-hardware.org/?probe=fc6d4c2e7d) | May 30, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [0f7555a7bd](https://linux-hardware.org/?probe=0f7555a7bd) | May 30, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| HP            | 355 G2                      | Notebook    | [c80a118e90](https://linux-hardware.org/?probe=c80a118e90) | May 29, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [8ab1f1c2cf](https://linux-hardware.org/?probe=8ab1f1c2cf) | May 29, 2021 |
| Acer          | Aspire 7736                 | Notebook    | [f8cf9b2aa2](https://linux-hardware.org/?probe=f8cf9b2aa2) | May 29, 2021 |
| HP            | ENVY 17                     | Notebook    | [bdaee2e27b](https://linux-hardware.org/?probe=bdaee2e27b) | May 28, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [d0c45f9b31](https://linux-hardware.org/?probe=d0c45f9b31) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| HP            | 18E7                        | Desktop     | [74314fffc3](https://linux-hardware.org/?probe=74314fffc3) | May 27, 2021 |
| HP            | 18E7                        | Desktop     | [dbb0731dd9](https://linux-hardware.org/?probe=dbb0731dd9) | May 27, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [049671564e](https://linux-hardware.org/?probe=049671564e) | May 27, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [cb5051e015](https://linux-hardware.org/?probe=cb5051e015) | May 27, 2021 |
| HP            | Unknown                     | Notebook    | [42eeaf84d9](https://linux-hardware.org/?probe=42eeaf84d9) | May 24, 2021 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [234767f4ba](https://linux-hardware.org/?probe=234767f4ba) | May 24, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | TravelMate P215-53          | Notebook    | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [75bca9816e](https://linux-hardware.org/?probe=75bca9816e) | May 23, 2021 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [bc4b4dca67](https://linux-hardware.org/?probe=bc4b4dca67) | May 23, 2021 |
| Gigabyte      | P35-DQ6                     | Desktop     | [5b2102ba4e](https://linux-hardware.org/?probe=5b2102ba4e) | May 23, 2021 |
| Gigabyte      | P35-DQ6                     | Desktop     | [e5ef68ed7f](https://linux-hardware.org/?probe=e5ef68ed7f) | May 23, 2021 |
| Sony          | VAIO                        | All in one  | [b2b912ef1e](https://linux-hardware.org/?probe=b2b912ef1e) | May 22, 2021 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [4a9dd7d6a1](https://linux-hardware.org/?probe=4a9dd7d6a1) | May 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [92d06972e9](https://linux-hardware.org/?probe=92d06972e9) | May 22, 2021 |
| eMachines     | ET1861                      | Desktop     | [732f584b67](https://linux-hardware.org/?probe=732f584b67) | May 22, 2021 |
| HP            | 8055                        | Desktop     | [d6291acc4a](https://linux-hardware.org/?probe=d6291acc4a) | May 20, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [895d614ba3](https://linux-hardware.org/?probe=895d614ba3) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [901f37d11b](https://linux-hardware.org/?probe=901f37d11b) | May 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [39f2002b6b](https://linux-hardware.org/?probe=39f2002b6b) | May 19, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [877462fbca](https://linux-hardware.org/?probe=877462fbca) | May 18, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [abdc61ad94](https://linux-hardware.org/?probe=abdc61ad94) | May 18, 2021 |
| HP            | 87C3                        | Desktop     | [6ef8441fda](https://linux-hardware.org/?probe=6ef8441fda) | May 16, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [710fdca60a](https://linux-hardware.org/?probe=710fdca60a) | May 16, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d180569750](https://linux-hardware.org/?probe=d180569750) | May 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [344858ad94](https://linux-hardware.org/?probe=344858ad94) | May 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a1d8f5a045](https://linux-hardware.org/?probe=a1d8f5a045) | May 15, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [25a571732b](https://linux-hardware.org/?probe=25a571732b) | May 15, 2021 |
| HP            | ProBook 455 G4              | Notebook    | [aca836bae8](https://linux-hardware.org/?probe=aca836bae8) | May 14, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [356a329ce3](https://linux-hardware.org/?probe=356a329ce3) | May 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [674a800477](https://linux-hardware.org/?probe=674a800477) | May 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [42a1bf7901](https://linux-hardware.org/?probe=42a1bf7901) | May 14, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7e38915bdc](https://linux-hardware.org/?probe=7e38915bdc) | May 13, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [43907153c2](https://linux-hardware.org/?probe=43907153c2) | May 13, 2021 |
| TrekStor      | Primebook C13               | Convertible | [7332052765](https://linux-hardware.org/?probe=7332052765) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [36ade7dd15](https://linux-hardware.org/?probe=36ade7dd15) | May 13, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [06c1bbc65e](https://linux-hardware.org/?probe=06c1bbc65e) | May 13, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [ef1799419d](https://linux-hardware.org/?probe=ef1799419d) | May 12, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [29ad7fb8e1](https://linux-hardware.org/?probe=29ad7fb8e1) | May 12, 2021 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [beb0d03960](https://linux-hardware.org/?probe=beb0d03960) | May 12, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fab7d18783](https://linux-hardware.org/?probe=fab7d18783) | May 12, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [63c11ce610](https://linux-hardware.org/?probe=63c11ce610) | May 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [b313183fd5](https://linux-hardware.org/?probe=b313183fd5) | May 11, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [e2d8f58e1e](https://linux-hardware.org/?probe=e2d8f58e1e) | May 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [e126e1aa0c](https://linux-hardware.org/?probe=e126e1aa0c) | May 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [952093c613](https://linux-hardware.org/?probe=952093c613) | May 09, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f671c92f38](https://linux-hardware.org/?probe=f671c92f38) | May 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e08abc7d05](https://linux-hardware.org/?probe=e08abc7d05) | May 08, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [a6ed80ed47](https://linux-hardware.org/?probe=a6ed80ed47) | May 08, 2021 |
| Google        | Lars                        | Notebook    | [2cba94fe45](https://linux-hardware.org/?probe=2cba94fe45) | May 08, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d20858b78f](https://linux-hardware.org/?probe=d20858b78f) | May 08, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | Notebook    | [eedf4bb0ca](https://linux-hardware.org/?probe=eedf4bb0ca) | May 08, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [f28c9e243e](https://linux-hardware.org/?probe=f28c9e243e) | May 07, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [f72c74aa38](https://linux-hardware.org/?probe=f72c74aa38) | May 06, 2021 |
| Lenovo        | ThinkCentre M58 8820AJG     | Desktop     | [239c4bf44d](https://linux-hardware.org/?probe=239c4bf44d) | May 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [110e1b8b1a](https://linux-hardware.org/?probe=110e1b8b1a) | May 06, 2021 |
| HP            | Compaq nc4400 (EN004AV)     | Notebook    | [d6154d7955](https://linux-hardware.org/?probe=d6154d7955) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [06d44f569d](https://linux-hardware.org/?probe=06d44f569d) | May 06, 2021 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | Desktop     | [24f944159d](https://linux-hardware.org/?probe=24f944159d) | May 05, 2021 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [a4d6f3cce4](https://linux-hardware.org/?probe=a4d6f3cce4) | May 04, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [ff0d2758aa](https://linux-hardware.org/?probe=ff0d2758aa) | May 04, 2021 |
| ASRock        | X79 Extreme4                | Desktop     | [87e9e3ff1c](https://linux-hardware.org/?probe=87e9e3ff1c) | May 04, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [523fba1dd3](https://linux-hardware.org/?probe=523fba1dd3) | May 04, 2021 |
| Lenovo        | ThinkPad T480s 20L7001LM... | Notebook    | [0b155bcbcd](https://linux-hardware.org/?probe=0b155bcbcd) | May 04, 2021 |
| HP            | Notebook                    | Notebook    | [4e09e8ff3b](https://linux-hardware.org/?probe=4e09e8ff3b) | May 03, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [084ee4289f](https://linux-hardware.org/?probe=084ee4289f) | May 03, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [5568d6a07f](https://linux-hardware.org/?probe=5568d6a07f) | May 03, 2021 |
| HP            | 2133                        | Notebook    | [e81cac058d](https://linux-hardware.org/?probe=e81cac058d) | May 03, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [7a38618a4f](https://linux-hardware.org/?probe=7a38618a4f) | May 02, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [d490ee9c19](https://linux-hardware.org/?probe=d490ee9c19) | May 02, 2021 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [5be5e699bf](https://linux-hardware.org/?probe=5be5e699bf) | May 02, 2021 |
| Alienware     | m15 R2                      | Notebook    | [4884d06d2e](https://linux-hardware.org/?probe=4884d06d2e) | May 02, 2021 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [226f359e79](https://linux-hardware.org/?probe=226f359e79) | May 01, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e69f0b2a6e](https://linux-hardware.org/?probe=e69f0b2a6e) | May 01, 2021 |
| Lenovo        | ThinkPad T580 20LAS3NJ08    | Notebook    | [7efd61973c](https://linux-hardware.org/?probe=7efd61973c) | Apr 30, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [019f1d6c17](https://linux-hardware.org/?probe=019f1d6c17) | Apr 30, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [9689ca0570](https://linux-hardware.org/?probe=9689ca0570) | Apr 30, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [fcfd291a4f](https://linux-hardware.org/?probe=fcfd291a4f) | Apr 30, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fb11e4cdcc](https://linux-hardware.org/?probe=fb11e4cdcc) | Apr 29, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [93033f85c6](https://linux-hardware.org/?probe=93033f85c6) | Apr 29, 2021 |
| HP            | 8056                        | Desktop     | [34d3f923a3](https://linux-hardware.org/?probe=34d3f923a3) | Apr 29, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [96c6f86018](https://linux-hardware.org/?probe=96c6f86018) | Apr 29, 2021 |
| HP            | 2133                        | Notebook    | [fd8d7a6a94](https://linux-hardware.org/?probe=fd8d7a6a94) | Apr 29, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2ff23ca44c](https://linux-hardware.org/?probe=2ff23ca44c) | Apr 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Alienware     | m15 R2                      | Notebook    | [77d90d2a91](https://linux-hardware.org/?probe=77d90d2a91) | Apr 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [909c049308](https://linux-hardware.org/?probe=909c049308) | Apr 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6fd9f38406](https://linux-hardware.org/?probe=6fd9f38406) | Apr 26, 2021 |
| Dell          | Latitude E7440              | Notebook    | [b8c6136bd0](https://linux-hardware.org/?probe=b8c6136bd0) | Apr 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [98a664ebcc](https://linux-hardware.org/?probe=98a664ebcc) | Apr 26, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [ff3ba69d3e](https://linux-hardware.org/?probe=ff3ba69d3e) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [e4b338aa1a](https://linux-hardware.org/?probe=e4b338aa1a) | Apr 25, 2021 |
| OriginPC      | ND-17                       | Notebook    | [8ff850fe97](https://linux-hardware.org/?probe=8ff850fe97) | Apr 25, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [bcc4e8b350](https://linux-hardware.org/?probe=bcc4e8b350) | Apr 25, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [7ecfe05882](https://linux-hardware.org/?probe=7ecfe05882) | Apr 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | Notebook    | [101cc9e3ae](https://linux-hardware.org/?probe=101cc9e3ae) | Apr 23, 2021 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [41ade399b3](https://linux-hardware.org/?probe=41ade399b3) | Apr 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [926fa9f69a](https://linux-hardware.org/?probe=926fa9f69a) | Apr 21, 2021 |
| Dell          | 0TP406                      | Desktop     | [5a53a4349a](https://linux-hardware.org/?probe=5a53a4349a) | Apr 21, 2021 |
| HP            | ENVY Laptop 17-cg1xxx       | Notebook    | [38221d2991](https://linux-hardware.org/?probe=38221d2991) | Apr 21, 2021 |
| Acer          | Aspire 1410                 | Notebook    | [7288f31e3c](https://linux-hardware.org/?probe=7288f31e3c) | Apr 20, 2021 |
| HP            | 0B4Ch D                     | Desktop     | [3721f71fb0](https://linux-hardware.org/?probe=3721f71fb0) | Apr 19, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5b66c48c4a](https://linux-hardware.org/?probe=5b66c48c4a) | Apr 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [414dee060e](https://linux-hardware.org/?probe=414dee060e) | Apr 15, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [c96585f787](https://linux-hardware.org/?probe=c96585f787) | Apr 14, 2021 |
| Dell          | Latitude E7240              | Notebook    | [45870a7f89](https://linux-hardware.org/?probe=45870a7f89) | Apr 14, 2021 |
| whyopencom... | Unknown                     | Notebook    | [aad3ad526f](https://linux-hardware.org/?probe=aad3ad526f) | Apr 13, 2021 |
| HP            | 3033h                       | Desktop     | [bbdefab03d](https://linux-hardware.org/?probe=bbdefab03d) | Apr 13, 2021 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [08bd5bdc20](https://linux-hardware.org/?probe=08bd5bdc20) | Apr 13, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [bc738ac65f](https://linux-hardware.org/?probe=bc738ac65f) | Apr 11, 2021 |
| Dell          | 0TP406                      | Desktop     | [d903abaa08](https://linux-hardware.org/?probe=d903abaa08) | Apr 10, 2021 |
| Dell          | 0TP406                      | Desktop     | [bf1adf4111](https://linux-hardware.org/?probe=bf1adf4111) | Apr 10, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3dd02b4af9](https://linux-hardware.org/?probe=3dd02b4af9) | Apr 09, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [4d759a05db](https://linux-hardware.org/?probe=4d759a05db) | Apr 09, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [5bc4edd8b4](https://linux-hardware.org/?probe=5bc4edd8b4) | Apr 08, 2021 |
| HP            | 1497                        | Desktop     | [d93ce1eeb3](https://linux-hardware.org/?probe=d93ce1eeb3) | Apr 07, 2021 |
| Dell          | Latitude E6500              | Notebook    | [3bdee6855c](https://linux-hardware.org/?probe=3bdee6855c) | Apr 07, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [e4f7f8688b](https://linux-hardware.org/?probe=e4f7f8688b) | Apr 05, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cc943c576f](https://linux-hardware.org/?probe=cc943c576f) | Apr 05, 2021 |
| Lenovo        | IdeaPad Yoga 13 2191        | Notebook    | [44aa3ba48f](https://linux-hardware.org/?probe=44aa3ba48f) | Apr 05, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [1f560968ab](https://linux-hardware.org/?probe=1f560968ab) | Apr 04, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [c5010e1348](https://linux-hardware.org/?probe=c5010e1348) | Apr 03, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4fce2c6b09](https://linux-hardware.org/?probe=4fce2c6b09) | Apr 02, 2021 |
| Acer          | Predator G3610              | Desktop     | [58f942e8c3](https://linux-hardware.org/?probe=58f942e8c3) | Apr 02, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [9e4b82fb49](https://linux-hardware.org/?probe=9e4b82fb49) | Apr 02, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2b3b29eb9e](https://linux-hardware.org/?probe=2b3b29eb9e) | Apr 02, 2021 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [d140ff934b](https://linux-hardware.org/?probe=d140ff934b) | Apr 01, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [f74fdee693](https://linux-hardware.org/?probe=f74fdee693) | Apr 01, 2021 |
| TrekStor      | Surfbook E11B               | Notebook    | [464dce7796](https://linux-hardware.org/?probe=464dce7796) | Apr 01, 2021 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [426f11f2d2](https://linux-hardware.org/?probe=426f11f2d2) | Mar 31, 2021 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [d40236931f](https://linux-hardware.org/?probe=d40236931f) | Mar 31, 2021 |
| ASRock        | Z77 Pro4                    | Desktop     | [981009625b](https://linux-hardware.org/?probe=981009625b) | Mar 29, 2021 |
| Dell          | Latitude E5450              | Notebook    | [5ce2bad1c1](https://linux-hardware.org/?probe=5ce2bad1c1) | Mar 29, 2021 |
| Medion        | MS-7621                     | Desktop     | [d0f1e17b38](https://linux-hardware.org/?probe=d0f1e17b38) | Mar 29, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [449ee0c3ef](https://linux-hardware.org/?probe=449ee0c3ef) | Mar 28, 2021 |
| Lenovo        | ThinkPad E14 20RA001HMZ     | Notebook    | [44e41b06e8](https://linux-hardware.org/?probe=44e41b06e8) | Mar 28, 2021 |
| HP            | 1497                        | Desktop     | [57f83dc5e5](https://linux-hardware.org/?probe=57f83dc5e5) | Mar 28, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7ccab1854d](https://linux-hardware.org/?probe=7ccab1854d) | Mar 27, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a21b63e491](https://linux-hardware.org/?probe=a21b63e491) | Mar 26, 2021 |
| Medion        | S3409 MD60234               | Notebook    | [eee4e7256b](https://linux-hardware.org/?probe=eee4e7256b) | Mar 26, 2021 |
| HP            | 1497                        | Desktop     | [d28570a6cb](https://linux-hardware.org/?probe=d28570a6cb) | Mar 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7e10f0b649](https://linux-hardware.org/?probe=7e10f0b649) | Mar 25, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [27a3733dc4](https://linux-hardware.org/?probe=27a3733dc4) | Mar 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e3d4f5753e](https://linux-hardware.org/?probe=e3d4f5753e) | Mar 25, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0e12cc8e95](https://linux-hardware.org/?probe=0e12cc8e95) | Mar 25, 2021 |
| PC Engines    | APU2                        | Desktop     | [76bdee5902](https://linux-hardware.org/?probe=76bdee5902) | Mar 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [c8a3d807bb](https://linux-hardware.org/?probe=c8a3d807bb) | Mar 24, 2021 |
| PC Engines    | APU2                        | Desktop     | [aacc455c74](https://linux-hardware.org/?probe=aacc455c74) | Mar 24, 2021 |
| ASUSTek       | H170M-E D3                  | Desktop     | [454261a973](https://linux-hardware.org/?probe=454261a973) | Mar 24, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [f00d8623c8](https://linux-hardware.org/?probe=f00d8623c8) | Mar 24, 2021 |
| Lenovo        | ThinkPad T460s 20F9005CS... | Notebook    | [c03bed695b](https://linux-hardware.org/?probe=c03bed695b) | Mar 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1ef0fbf40d](https://linux-hardware.org/?probe=1ef0fbf40d) | Mar 23, 2021 |
| HP            | 250 G8 Notebook PC          | Notebook    | [8889dc5ad5](https://linux-hardware.org/?probe=8889dc5ad5) | Mar 22, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | Notebook    | [045f977209](https://linux-hardware.org/?probe=045f977209) | Mar 22, 2021 |
| Shuttle       | FH61R                       | Desktop     | [5b90db2538](https://linux-hardware.org/?probe=5b90db2538) | Mar 21, 2021 |
| Acer          | V3-771                      | Notebook    | [a602c93819](https://linux-hardware.org/?probe=a602c93819) | Mar 21, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [329c4eed31](https://linux-hardware.org/?probe=329c4eed31) | Mar 20, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [98b7e6584d](https://linux-hardware.org/?probe=98b7e6584d) | Mar 20, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2892bb172b](https://linux-hardware.org/?probe=2892bb172b) | Mar 20, 2021 |
| Apple         | MacBookAir5,2               | Notebook    | [23d38894c7](https://linux-hardware.org/?probe=23d38894c7) | Mar 20, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [25f556cacf](https://linux-hardware.org/?probe=25f556cacf) | Mar 18, 2021 |
| ZOTAC         | ZBOXNXS-AD13                | Mini pc     | [8c3ca64606](https://linux-hardware.org/?probe=8c3ca64606) | Mar 18, 2021 |
| ZOTAC         | ZBOXNXS-AD13                | Mini pc     | [187ae2b4ed](https://linux-hardware.org/?probe=187ae2b4ed) | Mar 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ceb09854c9](https://linux-hardware.org/?probe=ceb09854c9) | Mar 18, 2021 |
| HP            | 838B                        | All in one  | [a8811301bc](https://linux-hardware.org/?probe=a8811301bc) | Mar 18, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [75cb082ef8](https://linux-hardware.org/?probe=75cb082ef8) | Mar 18, 2021 |
| HP            | ProLiant DL380 G5           | Server      | [3d73b20bc9](https://linux-hardware.org/?probe=3d73b20bc9) | Mar 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b828e7c8f6](https://linux-hardware.org/?probe=b828e7c8f6) | Mar 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7156475fba](https://linux-hardware.org/?probe=7156475fba) | Mar 17, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [49ee1765af](https://linux-hardware.org/?probe=49ee1765af) | Mar 16, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [20bf0cfe70](https://linux-hardware.org/?probe=20bf0cfe70) | Mar 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [63e83f6ac6](https://linux-hardware.org/?probe=63e83f6ac6) | Mar 15, 2021 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [1111114ddb](https://linux-hardware.org/?probe=1111114ddb) | Mar 15, 2021 |
| eMachines     | ET1861                      | Desktop     | [c8e6e483f5](https://linux-hardware.org/?probe=c8e6e483f5) | Mar 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1deb9edb46](https://linux-hardware.org/?probe=1deb9edb46) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [3d10849f6e](https://linux-hardware.org/?probe=3d10849f6e) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [6c33ce2e79](https://linux-hardware.org/?probe=6c33ce2e79) | Mar 14, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [2847b20ae0](https://linux-hardware.org/?probe=2847b20ae0) | Mar 14, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [ba3613bf62](https://linux-hardware.org/?probe=ba3613bf62) | Mar 14, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [1d220bf375](https://linux-hardware.org/?probe=1d220bf375) | Mar 14, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [bd1886f540](https://linux-hardware.org/?probe=bd1886f540) | Mar 14, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a095d0e6d8](https://linux-hardware.org/?probe=a095d0e6d8) | Mar 13, 2021 |
| Acer          | Aspire E1-731               | Notebook    | [23ea26d43f](https://linux-hardware.org/?probe=23ea26d43f) | Mar 12, 2021 |
| HP            | 1998                        | Desktop     | [78e05b078e](https://linux-hardware.org/?probe=78e05b078e) | Mar 12, 2021 |
| HP            | 1998                        | Desktop     | [2d721136a1](https://linux-hardware.org/?probe=2d721136a1) | Mar 12, 2021 |
| Gigabyte      | EP35-DS3R                   | Desktop     | [4ebcc8525d](https://linux-hardware.org/?probe=4ebcc8525d) | Mar 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5f46359865](https://linux-hardware.org/?probe=5f46359865) | Mar 12, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f5a10112c1](https://linux-hardware.org/?probe=f5a10112c1) | Mar 12, 2021 |
| Gigabyte      | EP35-DS3R                   | Desktop     | [0c64fa32bb](https://linux-hardware.org/?probe=0c64fa32bb) | Mar 12, 2021 |
| Acer          | Aspire 7736                 | Notebook    | [f3777d97b2](https://linux-hardware.org/?probe=f3777d97b2) | Mar 11, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [32ba5b9a6e](https://linux-hardware.org/?probe=32ba5b9a6e) | Mar 11, 2021 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [7cac1d69b0](https://linux-hardware.org/?probe=7cac1d69b0) | Mar 11, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [55af96f7d6](https://linux-hardware.org/?probe=55af96f7d6) | Mar 11, 2021 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [ac9a248a29](https://linux-hardware.org/?probe=ac9a248a29) | Mar 11, 2021 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [c20fa07cef](https://linux-hardware.org/?probe=c20fa07cef) | Mar 11, 2021 |
| Medion        | E6226                       | Notebook    | [fd72b6bbc9](https://linux-hardware.org/?probe=fd72b6bbc9) | Mar 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [8e4ebb57eb](https://linux-hardware.org/?probe=8e4ebb57eb) | Mar 10, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5c28995118](https://linux-hardware.org/?probe=5c28995118) | Mar 10, 2021 |
| Dell          | Latitude E7440              | Notebook    | [4521f4c1a3](https://linux-hardware.org/?probe=4521f4c1a3) | Mar 10, 2021 |
| HP            | ProBook 4720s               | Notebook    | [1dbaa2aa4b](https://linux-hardware.org/?probe=1dbaa2aa4b) | Mar 10, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a769c30f9c](https://linux-hardware.org/?probe=a769c30f9c) | Mar 10, 2021 |
| GPD           | P2 MAX                      | Notebook    | [931b98f992](https://linux-hardware.org/?probe=931b98f992) | Mar 09, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [332460236a](https://linux-hardware.org/?probe=332460236a) | Mar 09, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [56dfe79cf3](https://linux-hardware.org/?probe=56dfe79cf3) | Mar 09, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [bdbb6f7cb7](https://linux-hardware.org/?probe=bdbb6f7cb7) | Mar 09, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [26b1d3237f](https://linux-hardware.org/?probe=26b1d3237f) | Mar 09, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [7d142fb2ab](https://linux-hardware.org/?probe=7d142fb2ab) | Mar 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ae4c33fe91](https://linux-hardware.org/?probe=ae4c33fe91) | Mar 09, 2021 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [63c5c732d0](https://linux-hardware.org/?probe=63c5c732d0) | Mar 09, 2021 |
| HP            | 843B                        | Desktop     | [6c0504f168](https://linux-hardware.org/?probe=6c0504f168) | Mar 08, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [43719f69cc](https://linux-hardware.org/?probe=43719f69cc) | Mar 08, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [09ff2814ff](https://linux-hardware.org/?probe=09ff2814ff) | Mar 08, 2021 |
| Acer          | Predator G3610              | Desktop     | [49b3263bb1](https://linux-hardware.org/?probe=49b3263bb1) | Mar 07, 2021 |
| Dell          | 0R230R A00                  | Desktop     | [d51bdac334](https://linux-hardware.org/?probe=d51bdac334) | Mar 06, 2021 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [b926f7249f](https://linux-hardware.org/?probe=b926f7249f) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [6aea799f3a](https://linux-hardware.org/?probe=6aea799f3a) | Mar 06, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [f87b2a351a](https://linux-hardware.org/?probe=f87b2a351a) | Mar 06, 2021 |
| Lenovo        | ThinkPad T410s 2924AM7      | Notebook    | [c1211fb175](https://linux-hardware.org/?probe=c1211fb175) | Mar 04, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [d80f548759](https://linux-hardware.org/?probe=d80f548759) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [025319ae47](https://linux-hardware.org/?probe=025319ae47) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | Notebook    | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [44974397a8](https://linux-hardware.org/?probe=44974397a8) | Mar 01, 2021 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [0c2c32289a](https://linux-hardware.org/?probe=0c2c32289a) | Feb 28, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [1c477e6a87](https://linux-hardware.org/?probe=1c477e6a87) | Feb 28, 2021 |
| HP            | Pavilion Notebook g6        | Notebook    | [e8fb0d80d6](https://linux-hardware.org/?probe=e8fb0d80d6) | Feb 27, 2021 |
| ASUSTek       | PN60-R                      | Mini pc     | [847a813a2c](https://linux-hardware.org/?probe=847a813a2c) | Feb 27, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [eb73a917eb](https://linux-hardware.org/?probe=eb73a917eb) | Feb 26, 2021 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [e684219b02](https://linux-hardware.org/?probe=e684219b02) | Feb 25, 2021 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [430a666f91](https://linux-hardware.org/?probe=430a666f91) | Feb 25, 2021 |
| Medion        | P6624                       | Notebook    | [29fba6cccc](https://linux-hardware.org/?probe=29fba6cccc) | Feb 24, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [91e4ee1214](https://linux-hardware.org/?probe=91e4ee1214) | Feb 24, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [3dac06ca11](https://linux-hardware.org/?probe=3dac06ca11) | Feb 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [52b46f5660](https://linux-hardware.org/?probe=52b46f5660) | Feb 23, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [53ada57eb3](https://linux-hardware.org/?probe=53ada57eb3) | Feb 23, 2021 |
| Dell          | 0WG855                      | Desktop     | [2d58070beb](https://linux-hardware.org/?probe=2d58070beb) | Feb 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [f87a8067f6](https://linux-hardware.org/?probe=f87a8067f6) | Feb 22, 2021 |
| HP            | Pavilion Notebook g6        | Notebook    | [786a3e39df](https://linux-hardware.org/?probe=786a3e39df) | Feb 21, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [ede7d0e26c](https://linux-hardware.org/?probe=ede7d0e26c) | Feb 21, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [9b1c3d7ac7](https://linux-hardware.org/?probe=9b1c3d7ac7) | Feb 21, 2021 |
| Toshiba       | QOSMIO X770                 | Notebook    | [1d2a7b2b7a](https://linux-hardware.org/?probe=1d2a7b2b7a) | Feb 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6e7ed306ee](https://linux-hardware.org/?probe=6e7ed306ee) | Feb 20, 2021 |
| Dell          | 06XMFM A01                  | Desktop     | [648b9905de](https://linux-hardware.org/?probe=648b9905de) | Feb 20, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [201d0f8a0c](https://linux-hardware.org/?probe=201d0f8a0c) | Feb 20, 2021 |
| Acer          | V3-771                      | Notebook    | [b6e90947b8](https://linux-hardware.org/?probe=b6e90947b8) | Feb 20, 2021 |
| ASRock        | Z77 Pro4                    | Desktop     | [ac6c97daff](https://linux-hardware.org/?probe=ac6c97daff) | Feb 19, 2021 |
| HP            | Pavilion g7                 | Notebook    | [35f315adb8](https://linux-hardware.org/?probe=35f315adb8) | Feb 19, 2021 |
| HP            | Pavilion g7                 | Notebook    | [93b1476aa8](https://linux-hardware.org/?probe=93b1476aa8) | Feb 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5e5ead9c6a](https://linux-hardware.org/?probe=5e5ead9c6a) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [184fbe6548](https://linux-hardware.org/?probe=184fbe6548) | Feb 18, 2021 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [48279fe75f](https://linux-hardware.org/?probe=48279fe75f) | Feb 18, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f80d7003a7](https://linux-hardware.org/?probe=f80d7003a7) | Feb 18, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [b098b42d49](https://linux-hardware.org/?probe=b098b42d49) | Feb 18, 2021 |
| TUXEDO        | N13xWU                      | Notebook    | [905dae2b25](https://linux-hardware.org/?probe=905dae2b25) | Feb 18, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [e0a760df71](https://linux-hardware.org/?probe=e0a760df71) | Feb 17, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [23e2da6146](https://linux-hardware.org/?probe=23e2da6146) | Feb 17, 2021 |
| HP            | 2B2C                        | Desktop     | [8c45c42df1](https://linux-hardware.org/?probe=8c45c42df1) | Feb 17, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [64fa49b9d3](https://linux-hardware.org/?probe=64fa49b9d3) | Feb 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [fd4dd43574](https://linux-hardware.org/?probe=fd4dd43574) | Feb 16, 2021 |
| HP            | 845A                        | Desktop     | [9e9db37079](https://linux-hardware.org/?probe=9e9db37079) | Feb 16, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [8730756c6f](https://linux-hardware.org/?probe=8730756c6f) | Feb 16, 2021 |
| HP            | 8703                        | Desktop     | [5f8e1f5b57](https://linux-hardware.org/?probe=5f8e1f5b57) | Feb 15, 2021 |
| Samsung       | 730U3E/740U3E               | Notebook    | [094783ff7a](https://linux-hardware.org/?probe=094783ff7a) | Feb 15, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2d7919d18a](https://linux-hardware.org/?probe=2d7919d18a) | Feb 15, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [8815b92009](https://linux-hardware.org/?probe=8815b92009) | Feb 15, 2021 |
| ASRock        | Z77E-ITX                    | Desktop     | [ce16fccf9d](https://linux-hardware.org/?probe=ce16fccf9d) | Feb 14, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [23a6027065](https://linux-hardware.org/?probe=23a6027065) | Feb 14, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [d8957c1789](https://linux-hardware.org/?probe=d8957c1789) | Feb 14, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [f002df90ed](https://linux-hardware.org/?probe=f002df90ed) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [6e7025de29](https://linux-hardware.org/?probe=6e7025de29) | Feb 14, 2021 |
| Medion        | S621xT                      | Notebook    | [3b77cd1079](https://linux-hardware.org/?probe=3b77cd1079) | Feb 14, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [d955eb3433](https://linux-hardware.org/?probe=d955eb3433) | Feb 14, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fd9c733ca2](https://linux-hardware.org/?probe=fd9c733ca2) | Feb 14, 2021 |
| Gigabyte      | H81M-D2W                    | Desktop     | [0c4d4005b0](https://linux-hardware.org/?probe=0c4d4005b0) | Feb 13, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [381e94eee9](https://linux-hardware.org/?probe=381e94eee9) | Feb 13, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [02406791c2](https://linux-hardware.org/?probe=02406791c2) | Feb 13, 2021 |
| HP            | ENVY 15                     | Notebook    | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| Samsung       | 730U3E/740U3E               | Notebook    | [df4eb897c9](https://linux-hardware.org/?probe=df4eb897c9) | Feb 12, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [0fdb263ea1](https://linux-hardware.org/?probe=0fdb263ea1) | Feb 11, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [1c912f6f4b](https://linux-hardware.org/?probe=1c912f6f4b) | Feb 11, 2021 |
| Intel         | ChiefRiver                  | Desktop     | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | MZ52-G41-00 00010001        | Server      | [4231bb05ce](https://linux-hardware.org/?probe=4231bb05ce) | Feb 09, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6e5763c38e](https://linux-hardware.org/?probe=6e5763c38e) | Feb 08, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [a37995c746](https://linux-hardware.org/?probe=a37995c746) | Feb 08, 2021 |
| Samsung       | UNIVERSAL8890 board base... | Soc         | [8ad4dee3b1](https://linux-hardware.org/?probe=8ad4dee3b1) | Feb 08, 2021 |
| Acer          | V3-771                      | Notebook    | [525217a48b](https://linux-hardware.org/?probe=525217a48b) | Feb 07, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [899f63eec0](https://linux-hardware.org/?probe=899f63eec0) | Feb 07, 2021 |
| Dell          | Latitude E5440              | Notebook    | [421629b6e9](https://linux-hardware.org/?probe=421629b6e9) | Feb 07, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f9f288372e](https://linux-hardware.org/?probe=f9f288372e) | Feb 06, 2021 |
| HP            | 838B                        | All in one  | [58ac2e74cb](https://linux-hardware.org/?probe=58ac2e74cb) | Feb 05, 2021 |
| Medion        | X782X                       | Notebook    | [384e3543dd](https://linux-hardware.org/?probe=384e3543dd) | Feb 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c3062ebba4](https://linux-hardware.org/?probe=c3062ebba4) | Feb 04, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2203826b83](https://linux-hardware.org/?probe=2203826b83) | Feb 04, 2021 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [9815c7f01c](https://linux-hardware.org/?probe=9815c7f01c) | Feb 03, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [c35aaa7489](https://linux-hardware.org/?probe=c35aaa7489) | Feb 03, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [a4faf732cf](https://linux-hardware.org/?probe=a4faf732cf) | Feb 03, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [c7f7ee988b](https://linux-hardware.org/?probe=c7f7ee988b) | Feb 03, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [83d43fefbb](https://linux-hardware.org/?probe=83d43fefbb) | Feb 02, 2021 |
| ASUSTek       | G20CB                       | Desktop     | [253070b21b](https://linux-hardware.org/?probe=253070b21b) | Feb 01, 2021 |
| Sony          | SVE1511F4E                  | Notebook    | [6e713387ef](https://linux-hardware.org/?probe=6e713387ef) | Feb 01, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [c8b5f3921a](https://linux-hardware.org/?probe=c8b5f3921a) | Jan 31, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [669829c000](https://linux-hardware.org/?probe=669829c000) | Jan 31, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [ccf18d4e4e](https://linux-hardware.org/?probe=ccf18d4e4e) | Jan 31, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [ecaf6db2cc](https://linux-hardware.org/?probe=ecaf6db2cc) | Jan 31, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9947e9c2b1](https://linux-hardware.org/?probe=9947e9c2b1) | Jan 31, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [015d322a6f](https://linux-hardware.org/?probe=015d322a6f) | Jan 31, 2021 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [2b8a47f04b](https://linux-hardware.org/?probe=2b8a47f04b) | Jan 30, 2021 |
| Schenker      | VIA 15 Pro                  | Notebook    | [4f091c50f8](https://linux-hardware.org/?probe=4f091c50f8) | Jan 30, 2021 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [c317851bb7](https://linux-hardware.org/?probe=c317851bb7) | Jan 30, 2021 |
| Acer          | V3-771                      | Notebook    | [84fb01f37b](https://linux-hardware.org/?probe=84fb01f37b) | Jan 30, 2021 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [58ac4fe903](https://linux-hardware.org/?probe=58ac4fe903) | Jan 30, 2021 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [cecce826bf](https://linux-hardware.org/?probe=cecce826bf) | Jan 29, 2021 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [a52ad0ac35](https://linux-hardware.org/?probe=a52ad0ac35) | Jan 29, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | Notebook    | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Acer          | Aspire 7736                 | Notebook    | [361d552fde](https://linux-hardware.org/?probe=361d552fde) | Jan 28, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [c036495c81](https://linux-hardware.org/?probe=c036495c81) | Jan 26, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [ce7dd9632f](https://linux-hardware.org/?probe=ce7dd9632f) | Jan 26, 2021 |
| Sony          | VGN-AR61ZU                  | Notebook    | [32858b781b](https://linux-hardware.org/?probe=32858b781b) | Jan 25, 2021 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [bf9124e2f7](https://linux-hardware.org/?probe=bf9124e2f7) | Jan 24, 2021 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [3cb541a737](https://linux-hardware.org/?probe=3cb541a737) | Jan 24, 2021 |
| HP            | 2B47                        | Desktop     | [406d514ed5](https://linux-hardware.org/?probe=406d514ed5) | Jan 24, 2021 |
| Pegatron      | 2AED                        | Desktop     | [ffee72581f](https://linux-hardware.org/?probe=ffee72581f) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | Notebook    | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Gigabyte      | EP35-DS3R                   | Desktop     | [2012688df3](https://linux-hardware.org/?probe=2012688df3) | Jan 22, 2021 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [76934bec17](https://linux-hardware.org/?probe=76934bec17) | Jan 21, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b3b5cb12ff](https://linux-hardware.org/?probe=b3b5cb12ff) | Jan 21, 2021 |
| Lenovo        | ThinkPad X260 20F6CT01WW    | Notebook    | [6f921d73e3](https://linux-hardware.org/?probe=6f921d73e3) | Jan 20, 2021 |
| Lenovo        | ThinkPad Edge E530 32597... | Notebook    | [bb6fc12e56](https://linux-hardware.org/?probe=bb6fc12e56) | Jan 20, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [d2bc47e82b](https://linux-hardware.org/?probe=d2bc47e82b) | Jan 20, 2021 |
| Sony          | SVE14A2V1EW                 | Notebook    | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Lenovo        | ThinkPad T430 2349G5G       | Notebook    | [f552a37632](https://linux-hardware.org/?probe=f552a37632) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [b5f6cc5993](https://linux-hardware.org/?probe=b5f6cc5993) | Jan 19, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [ba6a149cba](https://linux-hardware.org/?probe=ba6a149cba) | Jan 17, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [731e0dfa98](https://linux-hardware.org/?probe=731e0dfa98) | Jan 17, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [287cefb90e](https://linux-hardware.org/?probe=287cefb90e) | Jan 17, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [f5873c65c2](https://linux-hardware.org/?probe=f5873c65c2) | Jan 17, 2021 |
| GPD           | P2 MAX                      | Notebook    | [cdc2c0ab67](https://linux-hardware.org/?probe=cdc2c0ab67) | Jan 17, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [951df975ad](https://linux-hardware.org/?probe=951df975ad) | Jan 17, 2021 |
| whyopencom... | Unknown                     | Notebook    | [c120bc7ad7](https://linux-hardware.org/?probe=c120bc7ad7) | Jan 17, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [79907a946b](https://linux-hardware.org/?probe=79907a946b) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [25fb58cc9f](https://linux-hardware.org/?probe=25fb58cc9f) | Jan 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e07ae256e7](https://linux-hardware.org/?probe=e07ae256e7) | Jan 16, 2021 |
| Notebook      | W65_67SZ                    | Notebook    | [1992f23f11](https://linux-hardware.org/?probe=1992f23f11) | Jan 15, 2021 |
| whyopencom... | Unknown                     | Notebook    | [05e1dc54c4](https://linux-hardware.org/?probe=05e1dc54c4) | Jan 15, 2021 |
| Gigabyte      | EP35-DS3R                   | Desktop     | [bbc0778ca2](https://linux-hardware.org/?probe=bbc0778ca2) | Jan 15, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [680db2a270](https://linux-hardware.org/?probe=680db2a270) | Jan 14, 2021 |
| ASUSTek       | TUF H310M-PLUS GAMING       | Desktop     | [9d96d0c467](https://linux-hardware.org/?probe=9d96d0c467) | Jan 14, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a0a962c57c](https://linux-hardware.org/?probe=a0a962c57c) | Jan 13, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [7cb0f8bbd2](https://linux-hardware.org/?probe=7cb0f8bbd2) | Jan 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e881933fc](https://linux-hardware.org/?probe=9e881933fc) | Jan 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9589d96b86](https://linux-hardware.org/?probe=9589d96b86) | Jan 13, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [51f542581b](https://linux-hardware.org/?probe=51f542581b) | Jan 13, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [04aa021d72](https://linux-hardware.org/?probe=04aa021d72) | Jan 13, 2021 |
| Sony          | SVE1511F4E                  | Notebook    | [18f6b7a23f](https://linux-hardware.org/?probe=18f6b7a23f) | Jan 13, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [2e35accad4](https://linux-hardware.org/?probe=2e35accad4) | Jan 12, 2021 |
| Dell          | Latitude XT2                | Notebook    | [958e277130](https://linux-hardware.org/?probe=958e277130) | Jan 12, 2021 |
| Acer          | V3-771                      | Notebook    | [816da2c056](https://linux-hardware.org/?probe=816da2c056) | Jan 11, 2021 |
| ASRock        | J4105-ITX                   | Desktop     | [7917a1f444](https://linux-hardware.org/?probe=7917a1f444) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [1209b7ddaa](https://linux-hardware.org/?probe=1209b7ddaa) | Jan 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6b7093fb90](https://linux-hardware.org/?probe=6b7093fb90) | Jan 10, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [ee990dcfb4](https://linux-hardware.org/?probe=ee990dcfb4) | Jan 10, 2021 |
| ASUSTek       | M11AD                       | Desktop     | [9cf107a36f](https://linux-hardware.org/?probe=9cf107a36f) | Jan 09, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [53ebfb5925](https://linux-hardware.org/?probe=53ebfb5925) | Jan 08, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [0720e27a99](https://linux-hardware.org/?probe=0720e27a99) | Jan 06, 2021 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [0e2c597625](https://linux-hardware.org/?probe=0e2c597625) | Jan 06, 2021 |
| Lenovo        | ThinkPad T490 20N3S4AF00    | Notebook    | [88d0c92974](https://linux-hardware.org/?probe=88d0c92974) | Jan 05, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [df07a5791b](https://linux-hardware.org/?probe=df07a5791b) | Jan 05, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [308605d361](https://linux-hardware.org/?probe=308605d361) | Jan 05, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [6226d61b8d](https://linux-hardware.org/?probe=6226d61b8d) | Jan 05, 2021 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [0280683b9f](https://linux-hardware.org/?probe=0280683b9f) | Jan 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0f6cbbdc40](https://linux-hardware.org/?probe=0f6cbbdc40) | Jan 03, 2021 |
| Apple         | Mac-F42786C8 PVT            | All in one  | [376ef8baec](https://linux-hardware.org/?probe=376ef8baec) | Jan 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [7fcac0b28e](https://linux-hardware.org/?probe=7fcac0b28e) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [403e79415b](https://linux-hardware.org/?probe=403e79415b) | Jan 01, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [4e4dfa1185](https://linux-hardware.org/?probe=4e4dfa1185) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [120cc88a70](https://linux-hardware.org/?probe=120cc88a70) | Dec 31, 2020 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [7c5bea876e](https://linux-hardware.org/?probe=7c5bea876e) | Dec 30, 2020 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [cd772a516d](https://linux-hardware.org/?probe=cd772a516d) | Dec 30, 2020 |
| Sony          | SVE1511F4E                  | Notebook    | [2482a9cf42](https://linux-hardware.org/?probe=2482a9cf42) | Dec 29, 2020 |
| Sony          | SVE1511F4E                  | Notebook    | [9ddcb0cab8](https://linux-hardware.org/?probe=9ddcb0cab8) | Dec 29, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [fa31ae75bf](https://linux-hardware.org/?probe=fa31ae75bf) | Dec 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [05666d1c95](https://linux-hardware.org/?probe=05666d1c95) | Dec 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9e768a771f](https://linux-hardware.org/?probe=9e768a771f) | Dec 29, 2020 |
| Dell          | Latitude E7470              | Notebook    | [5e06bae0e3](https://linux-hardware.org/?probe=5e06bae0e3) | Dec 28, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a360c35bec](https://linux-hardware.org/?probe=a360c35bec) | Dec 28, 2020 |
| ASRock        | A780GMH/128M                | Desktop     | [bf97146186](https://linux-hardware.org/?probe=bf97146186) | Dec 28, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [0566fe029e](https://linux-hardware.org/?probe=0566fe029e) | Dec 28, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [ff668fef04](https://linux-hardware.org/?probe=ff668fef04) | Dec 28, 2020 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Acer          | Predator G3-605             | Desktop     | [fd882239bd](https://linux-hardware.org/?probe=fd882239bd) | Dec 27, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [017b4363ac](https://linux-hardware.org/?probe=017b4363ac) | Dec 26, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [232d92124f](https://linux-hardware.org/?probe=232d92124f) | Dec 26, 2020 |
| HP            | Pavilion 17                 | Notebook    | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [c7791463a7](https://linux-hardware.org/?probe=c7791463a7) | Dec 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [c5acd280dc](https://linux-hardware.org/?probe=c5acd280dc) | Dec 25, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [e37c5dee56](https://linux-hardware.org/?probe=e37c5dee56) | Dec 25, 2020 |
| Sony          | VPCEH2P1E                   | Notebook    | [f68b654e04](https://linux-hardware.org/?probe=f68b654e04) | Dec 24, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [28a3b8bc6f](https://linux-hardware.org/?probe=28a3b8bc6f) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460 20FMS08Q1B    | Notebook    | [97f9380c82](https://linux-hardware.org/?probe=97f9380c82) | Dec 24, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [c1da0ab577](https://linux-hardware.org/?probe=c1da0ab577) | Dec 24, 2020 |
| Samsung       | 700T1C                      | Notebook    | [0f8a8671f2](https://linux-hardware.org/?probe=0f8a8671f2) | Dec 24, 2020 |
| ASRock        | X79 Extreme6/GB             | Desktop     | [2f789c5a38](https://linux-hardware.org/?probe=2f789c5a38) | Dec 24, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [bb04468cdd](https://linux-hardware.org/?probe=bb04468cdd) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [7b60dbe66e](https://linux-hardware.org/?probe=7b60dbe66e) | Dec 22, 2020 |
| ASUSTek       | PN60-R                      | Mini pc     | [91ea4fd3f1](https://linux-hardware.org/?probe=91ea4fd3f1) | Dec 22, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [9736b48f8d](https://linux-hardware.org/?probe=9736b48f8d) | Dec 22, 2020 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [1746196bea](https://linux-hardware.org/?probe=1746196bea) | Dec 22, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [574c33d611](https://linux-hardware.org/?probe=574c33d611) | Dec 21, 2020 |
| ASUSTek       | UX331UA                     | Notebook    | [f570bd4fca](https://linux-hardware.org/?probe=f570bd4fca) | Dec 21, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [30cd09db67](https://linux-hardware.org/?probe=30cd09db67) | Dec 21, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [dd42567df3](https://linux-hardware.org/?probe=dd42567df3) | Dec 21, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [86f1e40ed8](https://linux-hardware.org/?probe=86f1e40ed8) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [991d88e936](https://linux-hardware.org/?probe=991d88e936) | Dec 21, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | Notebook    | [f5320272b1](https://linux-hardware.org/?probe=f5320272b1) | Dec 21, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [1dddf64cc8](https://linux-hardware.org/?probe=1dddf64cc8) | Dec 20, 2020 |
| IGEL Techn... | M330C                       | Notebook    | [e2f47ddf56](https://linux-hardware.org/?probe=e2f47ddf56) | Dec 20, 2020 |
| IGEL Techn... | M330C                       | Notebook    | [e22d107c2b](https://linux-hardware.org/?probe=e22d107c2b) | Dec 20, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [0966f43d9e](https://linux-hardware.org/?probe=0966f43d9e) | Dec 19, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [829e9caa8c](https://linux-hardware.org/?probe=829e9caa8c) | Dec 19, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [af06892f03](https://linux-hardware.org/?probe=af06892f03) | Dec 19, 2020 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [1d5dd84a5b](https://linux-hardware.org/?probe=1d5dd84a5b) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [f10be822b8](https://linux-hardware.org/?probe=f10be822b8) | Dec 17, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3939d927b3](https://linux-hardware.org/?probe=3939d927b3) | Dec 16, 2020 |
| Dell          | Vostro 7590                 | Notebook    | [d71985d7a7](https://linux-hardware.org/?probe=d71985d7a7) | Dec 16, 2020 |
| Pegatron      | IPMSB-GS                    | Desktop     | [dacde4d76b](https://linux-hardware.org/?probe=dacde4d76b) | Dec 14, 2020 |
| Dell          | 0KC9NP A01                  | Desktop     | [33f50f83ff](https://linux-hardware.org/?probe=33f50f83ff) | Dec 14, 2020 |
| Dell          | 0KC9NP A01                  | Desktop     | [b3ae5f5dbf](https://linux-hardware.org/?probe=b3ae5f5dbf) | Dec 14, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [a1b69bb2a0](https://linux-hardware.org/?probe=a1b69bb2a0) | Dec 14, 2020 |
| PC Engines    | apu4                        | Desktop     | [7231a77ab4](https://linux-hardware.org/?probe=7231a77ab4) | Dec 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [33e1d553df](https://linux-hardware.org/?probe=33e1d553df) | Dec 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [e062ad33d4](https://linux-hardware.org/?probe=e062ad33d4) | Dec 14, 2020 |
| PC Engines    | APU2                        | Desktop     | [1a4672add5](https://linux-hardware.org/?probe=1a4672add5) | Dec 14, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6f483bd376](https://linux-hardware.org/?probe=6f483bd376) | Dec 13, 2020 |
| Medion        | MS-7707                     | Desktop     | [30a66403c3](https://linux-hardware.org/?probe=30a66403c3) | Dec 13, 2020 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [433aa65798](https://linux-hardware.org/?probe=433aa65798) | Dec 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | Notebook    | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| eMachines     | ET1861                      | Desktop     | [48ea624990](https://linux-hardware.org/?probe=48ea624990) | Dec 12, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | Notebook    | [d89c8f909d](https://linux-hardware.org/?probe=d89c8f909d) | Dec 12, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f635d01bd0](https://linux-hardware.org/?probe=f635d01bd0) | Dec 11, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [88c6bb8d12](https://linux-hardware.org/?probe=88c6bb8d12) | Dec 11, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [ecfcd2d772](https://linux-hardware.org/?probe=ecfcd2d772) | Dec 10, 2020 |
| Acer          | Aspire F5-771G              | Notebook    | [6d732fe2b5](https://linux-hardware.org/?probe=6d732fe2b5) | Dec 10, 2020 |
| HPE           | ProLiant DL380 Gen10        | Server      | [3120e02c21](https://linux-hardware.org/?probe=3120e02c21) | Dec 09, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [0ebe86b001](https://linux-hardware.org/?probe=0ebe86b001) | Dec 08, 2020 |
| Packard Be... | IXTREME M5850               | Desktop     | [f3d8657377](https://linux-hardware.org/?probe=f3d8657377) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [4120fa5430](https://linux-hardware.org/?probe=4120fa5430) | Dec 07, 2020 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [307334cdad](https://linux-hardware.org/?probe=307334cdad) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [f3fea11b14](https://linux-hardware.org/?probe=f3fea11b14) | Dec 07, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [efdfbd73d5](https://linux-hardware.org/?probe=efdfbd73d5) | Dec 06, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e5622116f9](https://linux-hardware.org/?probe=e5622116f9) | Dec 05, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [5c75458a8d](https://linux-hardware.org/?probe=5c75458a8d) | Dec 05, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | Notebook    | [112d12030c](https://linux-hardware.org/?probe=112d12030c) | Dec 04, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [94dd9615c9](https://linux-hardware.org/?probe=94dd9615c9) | Dec 03, 2020 |
| PC Engines    | APU2                        | Desktop     | [569b195a9d](https://linux-hardware.org/?probe=569b195a9d) | Dec 02, 2020 |
| PC Engines    | apu4                        | Desktop     | [7170ad3e95](https://linux-hardware.org/?probe=7170ad3e95) | Dec 02, 2020 |
| PC Engines    | apu4                        | Desktop     | [38969f1f9b](https://linux-hardware.org/?probe=38969f1f9b) | Dec 02, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [33c705cbf6](https://linux-hardware.org/?probe=33c705cbf6) | Dec 02, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0UD0... | Notebook    | [992060a459](https://linux-hardware.org/?probe=992060a459) | Dec 02, 2020 |
| Samsung       | 730U3E/740U3E               | Notebook    | [f392da9fc9](https://linux-hardware.org/?probe=f392da9fc9) | Dec 02, 2020 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0UD0... | Notebook    | [47e51b151b](https://linux-hardware.org/?probe=47e51b151b) | Dec 01, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [b80ed54426](https://linux-hardware.org/?probe=b80ed54426) | Dec 01, 2020 |
| ASUSTek       | Z170-PRO                    | Desktop     | [2c51e8d9ab](https://linux-hardware.org/?probe=2c51e8d9ab) | Nov 29, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [0a0bbf9708](https://linux-hardware.org/?probe=0a0bbf9708) | Nov 29, 2020 |
| ASUSTek       | Z170-PRO                    | Desktop     | [15fdf5da42](https://linux-hardware.org/?probe=15fdf5da42) | Nov 29, 2020 |
| Lenovo        | ThinkPad SL510 28479UU      | Notebook    | [f805d10499](https://linux-hardware.org/?probe=f805d10499) | Nov 28, 2020 |
| Acer          | Veriton X4660G V:1.0        | Desktop     | [8eb6f7795d](https://linux-hardware.org/?probe=8eb6f7795d) | Nov 28, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [afff87899c](https://linux-hardware.org/?probe=afff87899c) | Nov 28, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [37437b477e](https://linux-hardware.org/?probe=37437b477e) | Nov 28, 2020 |
| Toshiba       | TECRA R950                  | Notebook    | [e9755d13c3](https://linux-hardware.org/?probe=e9755d13c3) | Nov 28, 2020 |
| Acer          | Veriton X4660G V:1.0        | Desktop     | [4691a7224b](https://linux-hardware.org/?probe=4691a7224b) | Nov 28, 2020 |
| ASUSTek       | H87-PLUS                    | Desktop     | [563b11dfc7](https://linux-hardware.org/?probe=563b11dfc7) | Nov 27, 2020 |
| ASUSTek       | H87-PLUS                    | Desktop     | [7b22071212](https://linux-hardware.org/?probe=7b22071212) | Nov 27, 2020 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [dec24f879f](https://linux-hardware.org/?probe=dec24f879f) | Nov 26, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [7da87ec366](https://linux-hardware.org/?probe=7da87ec366) | Nov 26, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [30c4a823d8](https://linux-hardware.org/?probe=30c4a823d8) | Nov 26, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [d4f0cf4cf6](https://linux-hardware.org/?probe=d4f0cf4cf6) | Nov 25, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | Notebook    | [814797bb7b](https://linux-hardware.org/?probe=814797bb7b) | Nov 24, 2020 |
| Lenovo        | ThinkPad T500 20828YG       | Notebook    | [a45fc859a5](https://linux-hardware.org/?probe=a45fc859a5) | Nov 24, 2020 |
| Lenovo        | MIIX 720-12IKB 80VV         | Tablet      | [14dc838f85](https://linux-hardware.org/?probe=14dc838f85) | Nov 23, 2020 |
| Lenovo        | MIIX 720-12IKB 80VV         | Tablet      | [5e2a75e796](https://linux-hardware.org/?probe=5e2a75e796) | Nov 23, 2020 |
| ASRock        | J4105B-ITX                  | Desktop     | [f11bfd2c5d](https://linux-hardware.org/?probe=f11bfd2c5d) | Nov 22, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [521ec439fa](https://linux-hardware.org/?probe=521ec439fa) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | Notebook    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | Notebook    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude E6430              | Notebook    | [a1d7b0f9ab](https://linux-hardware.org/?probe=a1d7b0f9ab) | Nov 20, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [7c3fde4136](https://linux-hardware.org/?probe=7c3fde4136) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f0e1e0b6b](https://linux-hardware.org/?probe=8f0e1e0b6b) | Nov 20, 2020 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [958c7f88a6](https://linux-hardware.org/?probe=958c7f88a6) | Nov 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [07b3330478](https://linux-hardware.org/?probe=07b3330478) | Nov 19, 2020 |
| HP            | ProBook 455 G7              | Notebook    | [86e6b8d3b3](https://linux-hardware.org/?probe=86e6b8d3b3) | Nov 18, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [caf24dedc0](https://linux-hardware.org/?probe=caf24dedc0) | Nov 18, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [f5551f2781](https://linux-hardware.org/?probe=f5551f2781) | Nov 18, 2020 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a19d2a71f4](https://linux-hardware.org/?probe=a19d2a71f4) | Nov 17, 2020 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [04b88a5f7b](https://linux-hardware.org/?probe=04b88a5f7b) | Nov 16, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [eafab55a01](https://linux-hardware.org/?probe=eafab55a01) | Nov 15, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [572a7393df](https://linux-hardware.org/?probe=572a7393df) | Nov 14, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [965a2c7deb](https://linux-hardware.org/?probe=965a2c7deb) | Nov 14, 2020 |
| HP            | ENVY 15                     | Notebook    | [fb33289aed](https://linux-hardware.org/?probe=fb33289aed) | Nov 13, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [f44a4e3bfb](https://linux-hardware.org/?probe=f44a4e3bfb) | Nov 12, 2020 |
| ASUSTek       | TUF H310M-PLUS GAMING       | Desktop     | [4004a93f83](https://linux-hardware.org/?probe=4004a93f83) | Nov 12, 2020 |
| Dell          | Precision 7530              | Notebook    | [2dca9dbf01](https://linux-hardware.org/?probe=2dca9dbf01) | Nov 12, 2020 |
| HP            | 198E                        | Desktop     | [b894e40cf6](https://linux-hardware.org/?probe=b894e40cf6) | Nov 12, 2020 |
| HP            | 198E                        | Desktop     | [1078da35fb](https://linux-hardware.org/?probe=1078da35fb) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [7c89e8677b](https://linux-hardware.org/?probe=7c89e8677b) | Nov 12, 2020 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [e996126e7f](https://linux-hardware.org/?probe=e996126e7f) | Nov 12, 2020 |
| Shuttle       | FH61V                       | Desktop     | [078f8f6f11](https://linux-hardware.org/?probe=078f8f6f11) | Nov 11, 2020 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [77d6b5680d](https://linux-hardware.org/?probe=77d6b5680d) | Nov 11, 2020 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [f2fb66005f](https://linux-hardware.org/?probe=f2fb66005f) | Nov 11, 2020 |
| Lenovo        | ThinkPad E15 20RD003HMZ     | Notebook    | [3895f41e90](https://linux-hardware.org/?probe=3895f41e90) | Nov 10, 2020 |
| Acer          | Swift SF314-56              | Notebook    | [0a2c9a74a4](https://linux-hardware.org/?probe=0a2c9a74a4) | Nov 10, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [233b60886e](https://linux-hardware.org/?probe=233b60886e) | Nov 10, 2020 |
| Acer          | Aspire S7-391               | Notebook    | [b2b78adbd5](https://linux-hardware.org/?probe=b2b78adbd5) | Nov 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [04dd6da950](https://linux-hardware.org/?probe=04dd6da950) | Nov 09, 2020 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [d8543c7406](https://linux-hardware.org/?probe=d8543c7406) | Nov 09, 2020 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [7bdc42e804](https://linux-hardware.org/?probe=7bdc42e804) | Nov 08, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [8393d44a56](https://linux-hardware.org/?probe=8393d44a56) | Nov 06, 2020 |
| Pegatron      | IPMSB-GS                    | Desktop     | [977bda281d](https://linux-hardware.org/?probe=977bda281d) | Nov 05, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [ef2f846e22](https://linux-hardware.org/?probe=ef2f846e22) | Nov 04, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [cf06ba276e](https://linux-hardware.org/?probe=cf06ba276e) | Nov 04, 2020 |
| ASUSTek       | F3U                         | Notebook    | [a48a07cbcf](https://linux-hardware.org/?probe=a48a07cbcf) | Nov 03, 2020 |
| ASUSTek       | F3U                         | Notebook    | [828ad4fe18](https://linux-hardware.org/?probe=828ad4fe18) | Nov 03, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [754191159a](https://linux-hardware.org/?probe=754191159a) | Nov 03, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [c70d54792c](https://linux-hardware.org/?probe=c70d54792c) | Nov 02, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e68efeb7b8](https://linux-hardware.org/?probe=e68efeb7b8) | Nov 01, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f1f671ec54](https://linux-hardware.org/?probe=f1f671ec54) | Nov 01, 2020 |
| Dell          | 0KC9NP A01                  | Desktop     | [b2b887c55b](https://linux-hardware.org/?probe=b2b887c55b) | Nov 01, 2020 |
| Schenker      | SLIM15 SSL15L19             | Notebook    | [fa9a4ec7af](https://linux-hardware.org/?probe=fa9a4ec7af) | Oct 31, 2020 |
| Acer          | Aspire V3-772G              | Notebook    | [5eaea33f57](https://linux-hardware.org/?probe=5eaea33f57) | Oct 31, 2020 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6d530055ab](https://linux-hardware.org/?probe=6d530055ab) | Oct 31, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [14f636e00d](https://linux-hardware.org/?probe=14f636e00d) | Oct 30, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f9bdd2abb9](https://linux-hardware.org/?probe=f9bdd2abb9) | Oct 30, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [cd1259f1c9](https://linux-hardware.org/?probe=cd1259f1c9) | Oct 29, 2020 |
| Dell          | Latitude E7240              | Notebook    | [60701e4df3](https://linux-hardware.org/?probe=60701e4df3) | Oct 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [edbb5344b2](https://linux-hardware.org/?probe=edbb5344b2) | Oct 29, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [258c5c88be](https://linux-hardware.org/?probe=258c5c88be) | Oct 29, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [7df4485d80](https://linux-hardware.org/?probe=7df4485d80) | Oct 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | Desktop     | [c2d0ba9f5a](https://linux-hardware.org/?probe=c2d0ba9f5a) | Oct 26, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [5f09eb2168](https://linux-hardware.org/?probe=5f09eb2168) | Oct 26, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [3ed569dfa5](https://linux-hardware.org/?probe=3ed569dfa5) | Oct 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [72335ec621](https://linux-hardware.org/?probe=72335ec621) | Oct 25, 2020 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [5b96832844](https://linux-hardware.org/?probe=5b96832844) | Oct 25, 2020 |
| MSI           | B350M GAMING PRO            | Desktop     | [cb5ad0c5c6](https://linux-hardware.org/?probe=cb5ad0c5c6) | Oct 24, 2020 |
| Pegatron      | IPMSB-GS                    | Desktop     | [8175f30936](https://linux-hardware.org/?probe=8175f30936) | Oct 23, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [5aa23a1d7e](https://linux-hardware.org/?probe=5aa23a1d7e) | Oct 23, 2020 |
| Pegatron      | IPMSB-GS                    | Desktop     | [2c61275a87](https://linux-hardware.org/?probe=2c61275a87) | Oct 23, 2020 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [38240830f2](https://linux-hardware.org/?probe=38240830f2) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [94a8a3e5b3](https://linux-hardware.org/?probe=94a8a3e5b3) | Oct 22, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [816557b1e9](https://linux-hardware.org/?probe=816557b1e9) | Oct 22, 2020 |
| MSI           | 990XA-GD55                  | Desktop     | [2f0471bbf2](https://linux-hardware.org/?probe=2f0471bbf2) | Oct 22, 2020 |
| HP            | EliteBook x360 1040 G5      | Notebook    | [78cbc1663e](https://linux-hardware.org/?probe=78cbc1663e) | Oct 22, 2020 |
| Acer          | V3-771                      | Notebook    | [25aef0ed9b](https://linux-hardware.org/?probe=25aef0ed9b) | Oct 22, 2020 |
| Acer          | V3-771                      | Notebook    | [a360f75508](https://linux-hardware.org/?probe=a360f75508) | Oct 22, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [3b00a26eab](https://linux-hardware.org/?probe=3b00a26eab) | Oct 22, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [0e8e3a9c90](https://linux-hardware.org/?probe=0e8e3a9c90) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [4a883571a1](https://linux-hardware.org/?probe=4a883571a1) | Oct 21, 2020 |
| HP            | ProLiant DL360p Gen8        | Server      | [12d0d76c15](https://linux-hardware.org/?probe=12d0d76c15) | Oct 20, 2020 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [5fe1c3bf7f](https://linux-hardware.org/?probe=5fe1c3bf7f) | Oct 20, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [c527497a87](https://linux-hardware.org/?probe=c527497a87) | Oct 20, 2020 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c1bcb36fc6](https://linux-hardware.org/?probe=c1bcb36fc6) | Oct 20, 2020 |
| TUXEDO        | Book XC1711                 | Notebook    | [85474c7447](https://linux-hardware.org/?probe=85474c7447) | Oct 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| Lenovo        | ThinkPad W510 4389A16       | Notebook    | [4d825513e3](https://linux-hardware.org/?probe=4d825513e3) | Oct 18, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [632f3c5363](https://linux-hardware.org/?probe=632f3c5363) | Oct 18, 2020 |
| HP            | Pavilion dv6700             | Notebook    | [7fee612d83](https://linux-hardware.org/?probe=7fee612d83) | Oct 18, 2020 |
| HP            | ProLiant DL380p Gen8        | Server      | [fdc516788a](https://linux-hardware.org/?probe=fdc516788a) | Oct 16, 2020 |
| HP            | ProLiant DL380p Gen8        | Server      | [74c085215a](https://linux-hardware.org/?probe=74c085215a) | Oct 16, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [25c98f28de](https://linux-hardware.org/?probe=25c98f28de) | Oct 15, 2020 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [30fb642867](https://linux-hardware.org/?probe=30fb642867) | Oct 15, 2020 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [e3dcf6fb53](https://linux-hardware.org/?probe=e3dcf6fb53) | Oct 15, 2020 |
| Lenovo        | ThinkPad R500 2732BHG       | Notebook    | [ce5551a52f](https://linux-hardware.org/?probe=ce5551a52f) | Oct 15, 2020 |
| Dell          | Latitude 7490               | Notebook    | [8b6e96473e](https://linux-hardware.org/?probe=8b6e96473e) | Oct 15, 2020 |
| Dell          | XPS 13 9350                 | Notebook    | [f99a03a6fa](https://linux-hardware.org/?probe=f99a03a6fa) | Oct 14, 2020 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [1392da5d39](https://linux-hardware.org/?probe=1392da5d39) | Oct 14, 2020 |
| Lenovo        | ThinkPad T61 7661WBL        | Notebook    | [f19b646a14](https://linux-hardware.org/?probe=f19b646a14) | Oct 14, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2833baf5af](https://linux-hardware.org/?probe=2833baf5af) | Oct 13, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [489b1319b4](https://linux-hardware.org/?probe=489b1319b4) | Oct 13, 2020 |
| ASRock        | X370 Professional Gaming    | Desktop     | [2b432df0be](https://linux-hardware.org/?probe=2b432df0be) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [097db248db](https://linux-hardware.org/?probe=097db248db) | Oct 12, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [ede21e126b](https://linux-hardware.org/?probe=ede21e126b) | Oct 12, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | Desktop     | [aa1a7a9b37](https://linux-hardware.org/?probe=aa1a7a9b37) | Oct 12, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [41141f049e](https://linux-hardware.org/?probe=41141f049e) | Oct 11, 2020 |
| Dell          | 0KC9NP A01                  | Desktop     | [cbe082ec38](https://linux-hardware.org/?probe=cbe082ec38) | Oct 11, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [e7f8db7d2d](https://linux-hardware.org/?probe=e7f8db7d2d) | Oct 10, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [feae512d4a](https://linux-hardware.org/?probe=feae512d4a) | Oct 10, 2020 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [0f0bc8ef65](https://linux-hardware.org/?probe=0f0bc8ef65) | Oct 10, 2020 |
| Acer          | Spin SP111-34N              | Convertible | [4bf0b7c4f2](https://linux-hardware.org/?probe=4bf0b7c4f2) | Oct 10, 2020 |
| Acer          | Spin SP111-34N              | Convertible | [655f8f301e](https://linux-hardware.org/?probe=655f8f301e) | Oct 10, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [44f062803c](https://linux-hardware.org/?probe=44f062803c) | Oct 10, 2020 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [72f14374ee](https://linux-hardware.org/?probe=72f14374ee) | Oct 10, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | Notebook    | [ee0934ca90](https://linux-hardware.org/?probe=ee0934ca90) | Oct 10, 2020 |
| ASUSTek       | K73SD                       | Notebook    | [776517f452](https://linux-hardware.org/?probe=776517f452) | Oct 10, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [47dc69334e](https://linux-hardware.org/?probe=47dc69334e) | Oct 10, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [3d6de31d0c](https://linux-hardware.org/?probe=3d6de31d0c) | Oct 09, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [83ae97a2cc](https://linux-hardware.org/?probe=83ae97a2cc) | Oct 08, 2020 |
| HP            | 1998                        | Desktop     | [36f71f3062](https://linux-hardware.org/?probe=36f71f3062) | Oct 07, 2020 |
| ASUSTek       | P8P67-M                     | Desktop     | [1d67603237](https://linux-hardware.org/?probe=1d67603237) | Oct 06, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [31719f8646](https://linux-hardware.org/?probe=31719f8646) | Oct 06, 2020 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [7b8341379e](https://linux-hardware.org/?probe=7b8341379e) | Oct 05, 2020 |
| HP            | EliteBook x360 1040 G6      | Convertible | [dd643d4c19](https://linux-hardware.org/?probe=dd643d4c19) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [fb75c1edd7](https://linux-hardware.org/?probe=fb75c1edd7) | Oct 05, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [6ba5f5a971](https://linux-hardware.org/?probe=6ba5f5a971) | Oct 05, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | Notebook    | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Apple         | MacBookAir5,2               | Notebook    | [ae92ea7a52](https://linux-hardware.org/?probe=ae92ea7a52) | Oct 04, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [b02303b4f3](https://linux-hardware.org/?probe=b02303b4f3) | Oct 04, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [6b46fbb6cd](https://linux-hardware.org/?probe=6b46fbb6cd) | Oct 04, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [12f0e8aae9](https://linux-hardware.org/?probe=12f0e8aae9) | Oct 04, 2020 |
| ASUSTek       | AM1M-A                      | Desktop     | [c621d4658d](https://linux-hardware.org/?probe=c621d4658d) | Oct 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Sony          | VPCYB3V1E                   | Notebook    | [f116097e48](https://linux-hardware.org/?probe=f116097e48) | Oct 02, 2020 |
| Samsung       | NC10                        | Notebook    | [8ba791387e](https://linux-hardware.org/?probe=8ba791387e) | Oct 02, 2020 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [e26e52e0a5](https://linux-hardware.org/?probe=e26e52e0a5) | Oct 02, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [07387013eb](https://linux-hardware.org/?probe=07387013eb) | Sep 30, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a295a656f1](https://linux-hardware.org/?probe=a295a656f1) | Sep 30, 2020 |
| Sony          | VGN-AR61ZU                  | Notebook    | [b7d1817106](https://linux-hardware.org/?probe=b7d1817106) | Sep 29, 2020 |
| Dell          | Latitude 7490               | Notebook    | [13cb89196f](https://linux-hardware.org/?probe=13cb89196f) | Sep 29, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [0406278a16](https://linux-hardware.org/?probe=0406278a16) | Sep 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [5faa8e4ca3](https://linux-hardware.org/?probe=5faa8e4ca3) | Sep 28, 2020 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [8d4c5d114f](https://linux-hardware.org/?probe=8d4c5d114f) | Sep 28, 2020 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [f6828f515f](https://linux-hardware.org/?probe=f6828f515f) | Sep 28, 2020 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [d3631c75ab](https://linux-hardware.org/?probe=d3631c75ab) | Sep 27, 2020 |
| ASRock        | X570 Creator                | Desktop     | [35756027f1](https://linux-hardware.org/?probe=35756027f1) | Sep 23, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [77bafd89ba](https://linux-hardware.org/?probe=77bafd89ba) | Sep 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c00efa87f7](https://linux-hardware.org/?probe=c00efa87f7) | Sep 21, 2020 |
| ASUSTek       | X510URR                     | Notebook    | [e0520a6f96](https://linux-hardware.org/?probe=e0520a6f96) | Sep 21, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [8352a0ac0e](https://linux-hardware.org/?probe=8352a0ac0e) | Sep 20, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [b66433f2e6](https://linux-hardware.org/?probe=b66433f2e6) | Sep 20, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [d0712e5a04](https://linux-hardware.org/?probe=d0712e5a04) | Sep 19, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [467adb37ce](https://linux-hardware.org/?probe=467adb37ce) | Sep 19, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [711a85f008](https://linux-hardware.org/?probe=711a85f008) | Sep 19, 2020 |
| Unknown       | Unknown                     | Phone       | [7ff15fbf6f](https://linux-hardware.org/?probe=7ff15fbf6f) | Sep 19, 2020 |
| Unknown       | Unknown                     | Phone       | [b345d75a76](https://linux-hardware.org/?probe=b345d75a76) | Sep 19, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [ece1d236b5](https://linux-hardware.org/?probe=ece1d236b5) | Sep 18, 2020 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | Notebook    | [123de4a1c7](https://linux-hardware.org/?probe=123de4a1c7) | Sep 17, 2020 |
| Toshiba       | Satellite P50-C             | Notebook    | [6245fb1a20](https://linux-hardware.org/?probe=6245fb1a20) | Sep 17, 2020 |
| HP            | ZBook 15 G6                 | Notebook    | [4e73019ac5](https://linux-hardware.org/?probe=4e73019ac5) | Sep 16, 2020 |
| Sony          | SVE1511F4E                  | Notebook    | [891f09413c](https://linux-hardware.org/?probe=891f09413c) | Sep 16, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6130ae6b01](https://linux-hardware.org/?probe=6130ae6b01) | Sep 16, 2020 |
| HP            | 212B                        | Desktop     | [a7683d9b64](https://linux-hardware.org/?probe=a7683d9b64) | Sep 16, 2020 |
| HP            | 212B                        | Desktop     | [ea4618cf40](https://linux-hardware.org/?probe=ea4618cf40) | Sep 16, 2020 |
| ASUSTek       | K73SD                       | Notebook    | [67507a1125](https://linux-hardware.org/?probe=67507a1125) | Sep 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS20100     | Notebook    | [0f91d1ee1f](https://linux-hardware.org/?probe=0f91d1ee1f) | Sep 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS20100     | Notebook    | [1288fee0ed](https://linux-hardware.org/?probe=1288fee0ed) | Sep 16, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [4c0cfd6509](https://linux-hardware.org/?probe=4c0cfd6509) | Sep 16, 2020 |
| ASRock        | X570M Pro4                  | Desktop     | [4e53e35223](https://linux-hardware.org/?probe=4e53e35223) | Sep 15, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [5511ff7784](https://linux-hardware.org/?probe=5511ff7784) | Sep 15, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [510a70ab34](https://linux-hardware.org/?probe=510a70ab34) | Sep 15, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [4c15a9819a](https://linux-hardware.org/?probe=4c15a9819a) | Sep 14, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [1aca06c6ec](https://linux-hardware.org/?probe=1aca06c6ec) | Sep 14, 2020 |
| HP            | Compaq 15                   | Notebook    | [3c3d5c4299](https://linux-hardware.org/?probe=3c3d5c4299) | Sep 12, 2020 |
| HP            | Compaq 15                   | Notebook    | [8ae9fd7bff](https://linux-hardware.org/?probe=8ae9fd7bff) | Sep 12, 2020 |
| Razer         | Blade                       | Notebook    | [8a242cff29](https://linux-hardware.org/?probe=8a242cff29) | Sep 11, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [14142cd530](https://linux-hardware.org/?probe=14142cd530) | Sep 09, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [4734a349de](https://linux-hardware.org/?probe=4734a349de) | Sep 09, 2020 |
| Toshiba       | PORTEGE Z10T-A              | Notebook    | [0a43ad62d7](https://linux-hardware.org/?probe=0a43ad62d7) | Sep 08, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [a4465c328f](https://linux-hardware.org/?probe=a4465c328f) | Sep 08, 2020 |
| Lenovo        | ThinkPad Edge E530 3259A... | Notebook    | [deca89911a](https://linux-hardware.org/?probe=deca89911a) | Sep 07, 2020 |
| Dell          | Latitude E7470              | Notebook    | [42f49c6394](https://linux-hardware.org/?probe=42f49c6394) | Sep 07, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [04ec95546f](https://linux-hardware.org/?probe=04ec95546f) | Sep 06, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [96509c0af6](https://linux-hardware.org/?probe=96509c0af6) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [59ed33b893](https://linux-hardware.org/?probe=59ed33b893) | Sep 06, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6d53389b4e](https://linux-hardware.org/?probe=6d53389b4e) | Sep 05, 2020 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [beeac93f6f](https://linux-hardware.org/?probe=beeac93f6f) | Sep 04, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | Notebook    | [ff7f82b032](https://linux-hardware.org/?probe=ff7f82b032) | Sep 04, 2020 |
| Lenovo        | ThinkPad T590 20N4000BMZ    | Notebook    | [587d4d9277](https://linux-hardware.org/?probe=587d4d9277) | Sep 04, 2020 |
| ASUSTek       | Q170T                       | Desktop     | [a424aaa559](https://linux-hardware.org/?probe=a424aaa559) | Sep 03, 2020 |
| Intel         | D54250WYK H13922-303        | Desktop     | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| HP            | Elite Dragonfly             | Convertible | [0d1b4b8d37](https://linux-hardware.org/?probe=0d1b4b8d37) | Sep 03, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [7002eaa135](https://linux-hardware.org/?probe=7002eaa135) | Sep 03, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [9cd9dff24f](https://linux-hardware.org/?probe=9cd9dff24f) | Sep 03, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [755f86c144](https://linux-hardware.org/?probe=755f86c144) | Sep 03, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [40ab9f3cc9](https://linux-hardware.org/?probe=40ab9f3cc9) | Sep 03, 2020 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [bb1b799e64](https://linux-hardware.org/?probe=bb1b799e64) | Sep 03, 2020 |
| HP            | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [6b4ddf377d](https://linux-hardware.org/?probe=6b4ddf377d) | Sep 03, 2020 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [ea3b88b23f](https://linux-hardware.org/?probe=ea3b88b23f) | Sep 02, 2020 |
| Pegatron      | 2AB5                        | Desktop     | [06a5617e63](https://linux-hardware.org/?probe=06a5617e63) | Sep 02, 2020 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [efb03db319](https://linux-hardware.org/?probe=efb03db319) | Sep 02, 2020 |
| HP            | Pavilion g6                 | Notebook    | [ad8002e60e](https://linux-hardware.org/?probe=ad8002e60e) | Sep 01, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [5e853f5521](https://linux-hardware.org/?probe=5e853f5521) | Aug 31, 2020 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [e21dcc1b23](https://linux-hardware.org/?probe=e21dcc1b23) | Aug 31, 2020 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [cd93574726](https://linux-hardware.org/?probe=cd93574726) | Aug 31, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [eb90c11058](https://linux-hardware.org/?probe=eb90c11058) | Aug 30, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [8d0fb64559](https://linux-hardware.org/?probe=8d0fb64559) | Aug 30, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [028177bab3](https://linux-hardware.org/?probe=028177bab3) | Aug 30, 2020 |
| ASUSTek       | GL752VW                     | Notebook    | [d350d76726](https://linux-hardware.org/?probe=d350d76726) | Aug 29, 2020 |
| ASRock        | H170M Pro4                  | Desktop     | [10d84618d9](https://linux-hardware.org/?probe=10d84618d9) | Aug 29, 2020 |
| Microsoft     | Surface Pro 3               | Tablet      | [ef69732217](https://linux-hardware.org/?probe=ef69732217) | Aug 29, 2020 |
| Intel         | NUC7i7DNB J83500-202        | Mini pc     | [60b16780a6](https://linux-hardware.org/?probe=60b16780a6) | Aug 28, 2020 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [24cdd4715c](https://linux-hardware.org/?probe=24cdd4715c) | Aug 28, 2020 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c74ee85b0b](https://linux-hardware.org/?probe=c74ee85b0b) | Aug 26, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [ad27d76a1a](https://linux-hardware.org/?probe=ad27d76a1a) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f58e055469](https://linux-hardware.org/?probe=f58e055469) | Aug 25, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [d19c11c74a](https://linux-hardware.org/?probe=d19c11c74a) | Aug 25, 2020 |
| Apple         | MacBookAir4,1               | Notebook    | [b6d976fc76](https://linux-hardware.org/?probe=b6d976fc76) | Aug 24, 2020 |
| Lenovo        | ThinkPad X230 23252S4       | Notebook    | [5fe0becd60](https://linux-hardware.org/?probe=5fe0becd60) | Aug 22, 2020 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9abc29d5de](https://linux-hardware.org/?probe=9abc29d5de) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20LAS1VW00    | Notebook    | [f75ec41143](https://linux-hardware.org/?probe=f75ec41143) | Aug 20, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| Lenovo        | ThinkPad X280 20KES3DB00    | Notebook    | [c5e30308a8](https://linux-hardware.org/?probe=c5e30308a8) | Aug 19, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [b5a4ca1efe](https://linux-hardware.org/?probe=b5a4ca1efe) | Aug 18, 2020 |
| ASUSTek       | GL702ZC                     | Notebook    | [f685b1bfc0](https://linux-hardware.org/?probe=f685b1bfc0) | Aug 18, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3f770a739d](https://linux-hardware.org/?probe=3f770a739d) | Aug 18, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| Acer          | TMP455-M                    | Notebook    | [8ebc259273](https://linux-hardware.org/?probe=8ebc259273) | Aug 17, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [19d3840414](https://linux-hardware.org/?probe=19d3840414) | Aug 17, 2020 |
| HP            | 3033h                       | Desktop     | [11c542a41c](https://linux-hardware.org/?probe=11c542a41c) | Aug 17, 2020 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [0aebb46ce0](https://linux-hardware.org/?probe=0aebb46ce0) | Aug 16, 2020 |
| Gigabyte      | H81M-D2W                    | Desktop     | [5a58efce4c](https://linux-hardware.org/?probe=5a58efce4c) | Aug 15, 2020 |
| Lenovo        | ThinkPad W530 24415QG       | Notebook    | [03d4068143](https://linux-hardware.org/?probe=03d4068143) | Aug 14, 2020 |
| Dell          | 0P1KTG A00                  | Desktop     | [2af9ac31a0](https://linux-hardware.org/?probe=2af9ac31a0) | Aug 14, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [8a6fdea191](https://linux-hardware.org/?probe=8a6fdea191) | Aug 13, 2020 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [2db0caca58](https://linux-hardware.org/?probe=2db0caca58) | Aug 13, 2020 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [32d0727725](https://linux-hardware.org/?probe=32d0727725) | Aug 13, 2020 |
| HP            | Pavilion dm1                | Notebook    | [60fa55c570](https://linux-hardware.org/?probe=60fa55c570) | Aug 12, 2020 |
| Dell          | 0XCR8D A01                  | Desktop     | [33ff30025d](https://linux-hardware.org/?probe=33ff30025d) | Aug 11, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ac527dcde7](https://linux-hardware.org/?probe=ac527dcde7) | Aug 11, 2020 |
| HP            | 83E7                        | Desktop     | [0d0c333a28](https://linux-hardware.org/?probe=0d0c333a28) | Aug 10, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [943de78484](https://linux-hardware.org/?probe=943de78484) | Aug 10, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a22cc9f46c](https://linux-hardware.org/?probe=a22cc9f46c) | Aug 10, 2020 |
| Acer          | Aspire E1-572G              | Notebook    | [1a738a3991](https://linux-hardware.org/?probe=1a738a3991) | Aug 08, 2020 |
| PC Special... | X170SM                      | Notebook    | [0c9f2dc741](https://linux-hardware.org/?probe=0c9f2dc741) | Aug 07, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [0f16448380](https://linux-hardware.org/?probe=0f16448380) | Aug 07, 2020 |
| Dell          | 0KC9NP A01                  | Desktop     | [81335a6478](https://linux-hardware.org/?probe=81335a6478) | Aug 07, 2020 |
| ASUSTek       | P8H77-M                     | Desktop     | [9ae3669bd7](https://linux-hardware.org/?probe=9ae3669bd7) | Aug 07, 2020 |
| Dell          | 0VD5HY A07                  | Desktop     | [e555b823c5](https://linux-hardware.org/?probe=e555b823c5) | Aug 06, 2020 |
| Intel         | D54250WYK H13922-303        | Desktop     | [887f56c31c](https://linux-hardware.org/?probe=887f56c31c) | Aug 01, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [e6d4017b20](https://linux-hardware.org/?probe=e6d4017b20) | Aug 01, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [2cf170371c](https://linux-hardware.org/?probe=2cf170371c) | Jul 31, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1b44a0dac4](https://linux-hardware.org/?probe=1b44a0dac4) | Jul 31, 2020 |
| Dell          | 0P1KTG A00                  | Desktop     | [10049bd4d8](https://linux-hardware.org/?probe=10049bd4d8) | Jul 31, 2020 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [f321bf47d9](https://linux-hardware.org/?probe=f321bf47d9) | Jul 31, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [379f2065ae](https://linux-hardware.org/?probe=379f2065ae) | Jul 31, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [50c100fc45](https://linux-hardware.org/?probe=50c100fc45) | Jul 31, 2020 |
| Dell          | Latitude E7470              | Notebook    | [b01705d65a](https://linux-hardware.org/?probe=b01705d65a) | Jul 31, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7dfc906476](https://linux-hardware.org/?probe=7dfc906476) | Jul 30, 2020 |
| Dell          | System XPS L502X            | Notebook    | [2d4d18566a](https://linux-hardware.org/?probe=2d4d18566a) | Jul 28, 2020 |
| Dell          | System XPS L502X            | Notebook    | [8bb4b95768](https://linux-hardware.org/?probe=8bb4b95768) | Jul 28, 2020 |
| HP            | Pavilion dm1                | Notebook    | [db3461a440](https://linux-hardware.org/?probe=db3461a440) | Jul 25, 2020 |
| Dell          | 0773VG A00                  | Desktop     | [acfb59e260](https://linux-hardware.org/?probe=acfb59e260) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Biostar       | X370GT7                     | Desktop     | [09da2694be](https://linux-hardware.org/?probe=09da2694be) | Jul 23, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [472fe9bea2](https://linux-hardware.org/?probe=472fe9bea2) | Jul 23, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [cdc922b41d](https://linux-hardware.org/?probe=cdc922b41d) | Jul 23, 2020 |
| Dell          | XPS 15 9500                 | Notebook    | [de8b60de3d](https://linux-hardware.org/?probe=de8b60de3d) | Jul 23, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [fee1e401ad](https://linux-hardware.org/?probe=fee1e401ad) | Jul 23, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [c90f589ae7](https://linux-hardware.org/?probe=c90f589ae7) | Jul 21, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [a9202a9c5e](https://linux-hardware.org/?probe=a9202a9c5e) | Jul 20, 2020 |
| ASUSTek       | CM6870                      | Desktop     | [3833dcdedf](https://linux-hardware.org/?probe=3833dcdedf) | Jul 19, 2020 |
| HP            | Pavilion dm1                | Notebook    | [84fc871f29](https://linux-hardware.org/?probe=84fc871f29) | Jul 18, 2020 |
| HP            | Pavilion dm1                | Notebook    | [ccc4a944e8](https://linux-hardware.org/?probe=ccc4a944e8) | Jul 18, 2020 |
| Lenovo        | ThinkPad T530 24296JG       | Notebook    | [4a78a5df90](https://linux-hardware.org/?probe=4a78a5df90) | Jul 17, 2020 |
| HP            | OMEN by Laptop              | Notebook    | [2b163aed02](https://linux-hardware.org/?probe=2b163aed02) | Jul 16, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [c16798ee68](https://linux-hardware.org/?probe=c16798ee68) | Jul 16, 2020 |
| Lenovo        | ThinkPad T410 2522FY2       | Notebook    | [0b82f79ac2](https://linux-hardware.org/?probe=0b82f79ac2) | Jul 16, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [822d9649e3](https://linux-hardware.org/?probe=822d9649e3) | Jul 16, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [26cc806766](https://linux-hardware.org/?probe=26cc806766) | Jul 15, 2020 |
| whyopencom... | Unknown                     | Notebook    | [8d75881990](https://linux-hardware.org/?probe=8d75881990) | Jul 14, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [b30f8b6630](https://linux-hardware.org/?probe=b30f8b6630) | Jul 14, 2020 |
| Microsoft     | Surface Go                  | Tablet      | [eb497446be](https://linux-hardware.org/?probe=eb497446be) | Jul 14, 2020 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [49816db41b](https://linux-hardware.org/?probe=49816db41b) | Jul 13, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d6e99bc5f7](https://linux-hardware.org/?probe=d6e99bc5f7) | Jul 13, 2020 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [aeea739b46](https://linux-hardware.org/?probe=aeea739b46) | Jul 13, 2020 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [c0ff1007eb](https://linux-hardware.org/?probe=c0ff1007eb) | Jul 13, 2020 |
| Gigabyte      | H55N-USB3                   | Desktop     | [e1c8c5a9b4](https://linux-hardware.org/?probe=e1c8c5a9b4) | Jul 12, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [2744d071ac](https://linux-hardware.org/?probe=2744d071ac) | Jul 11, 2020 |
| Supermicro    | X9DR3-F                     | Desktop     | [74efa61302](https://linux-hardware.org/?probe=74efa61302) | Jul 11, 2020 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [504504aa5b](https://linux-hardware.org/?probe=504504aa5b) | Jul 11, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | Notebook    | [e8a304ecb6](https://linux-hardware.org/?probe=e8a304ecb6) | Jul 10, 2020 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [b215151d03](https://linux-hardware.org/?probe=b215151d03) | Jul 10, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [eac2bb7a6a](https://linux-hardware.org/?probe=eac2bb7a6a) | Jul 10, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9e4137e3d2](https://linux-hardware.org/?probe=9e4137e3d2) | Jul 09, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [312aabd74a](https://linux-hardware.org/?probe=312aabd74a) | Jul 09, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7744b749d9](https://linux-hardware.org/?probe=7744b749d9) | Jul 09, 2020 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [952d14c604](https://linux-hardware.org/?probe=952d14c604) | Jul 08, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [74b86d62c3](https://linux-hardware.org/?probe=74b86d62c3) | Jul 08, 2020 |
| Gigabyte      | H81M-D2W                    | Desktop     | [1683414cc3](https://linux-hardware.org/?probe=1683414cc3) | Jul 08, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [317f89a84a](https://linux-hardware.org/?probe=317f89a84a) | Jul 08, 2020 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [bd95d49c15](https://linux-hardware.org/?probe=bd95d49c15) | Jul 07, 2020 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [e7446f8931](https://linux-hardware.org/?probe=e7446f8931) | Jul 06, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [5508f52018](https://linux-hardware.org/?probe=5508f52018) | Jul 02, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [76a0b6b5a9](https://linux-hardware.org/?probe=76a0b6b5a9) | Jun 30, 2020 |
| Dell          | Latitude E4200              | Notebook    | [562288b958](https://linux-hardware.org/?probe=562288b958) | Jun 27, 2020 |
| Acer          | Aspire E1-522               | Notebook    | [e386d1b82d](https://linux-hardware.org/?probe=e386d1b82d) | Jun 22, 2020 |
| Acer          | Aspire E1-522               | Notebook    | [0a89c3643f](https://linux-hardware.org/?probe=0a89c3643f) | Jun 22, 2020 |
| HP            | EliteBook x360 1040 G6      | Convertible | [a8027ae745](https://linux-hardware.org/?probe=a8027ae745) | Jun 22, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [87c93c4148](https://linux-hardware.org/?probe=87c93c4148) | Jun 21, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [01beb1ea00](https://linux-hardware.org/?probe=01beb1ea00) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK S782               | Notebook    | [a7efefc897](https://linux-hardware.org/?probe=a7efefc897) | Jun 20, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [ca2ce997bd](https://linux-hardware.org/?probe=ca2ce997bd) | Jun 19, 2020 |
| ASUSTek       | X550EA                      | Notebook    | [98ccbfcea2](https://linux-hardware.org/?probe=98ccbfcea2) | Jun 19, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [3a46e21507](https://linux-hardware.org/?probe=3a46e21507) | Jun 19, 2020 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [edc208c6e9](https://linux-hardware.org/?probe=edc208c6e9) | Jun 19, 2020 |
| HP            | 18E7                        | Desktop     | [6f27ceecc3](https://linux-hardware.org/?probe=6f27ceecc3) | Jun 18, 2020 |
| ASUSTek       | UX303UB                     | Notebook    | [822415c699](https://linux-hardware.org/?probe=822415c699) | Jun 17, 2020 |
| Lenovo        | ThinkPad T430s 2356GU7      | Notebook    | [287790c54d](https://linux-hardware.org/?probe=287790c54d) | Jun 17, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [7347cc1a10](https://linux-hardware.org/?probe=7347cc1a10) | Jun 17, 2020 |
| GPD           | P2 MAX                      | Notebook    | [8786ccb6b6](https://linux-hardware.org/?probe=8786ccb6b6) | Jun 17, 2020 |
| Toshiba       | Satellite L770D-10M         | Notebook    | [6d5d87e5a8](https://linux-hardware.org/?probe=6d5d87e5a8) | Jun 17, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [72d0af747c](https://linux-hardware.org/?probe=72d0af747c) | Jun 17, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [39db0a8a39](https://linux-hardware.org/?probe=39db0a8a39) | Jun 17, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [37b7bdbe2b](https://linux-hardware.org/?probe=37b7bdbe2b) | Jun 17, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [bbdcf69bc4](https://linux-hardware.org/?probe=bbdcf69bc4) | Jun 16, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [b6fee1670d](https://linux-hardware.org/?probe=b6fee1670d) | Jun 16, 2020 |
| Apple         | MacBookPro6,2               | Notebook    | [e22d69a6c7](https://linux-hardware.org/?probe=e22d69a6c7) | Jun 14, 2020 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [e1434af9c8](https://linux-hardware.org/?probe=e1434af9c8) | Jun 14, 2020 |
| HP            | Pavilion g7                 | Notebook    | [ee9eefa3e9](https://linux-hardware.org/?probe=ee9eefa3e9) | Jun 14, 2020 |
| HP            | EliteBook 735 G5            | Notebook    | [f0fd278615](https://linux-hardware.org/?probe=f0fd278615) | Jun 13, 2020 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [f347e99704](https://linux-hardware.org/?probe=f347e99704) | Jun 13, 2020 |
| Acer          | Spin SP513-53N              | Convertible | [e682206e89](https://linux-hardware.org/?probe=e682206e89) | Jun 13, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [acfbf614c0](https://linux-hardware.org/?probe=acfbf614c0) | Jun 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [de0f29b8a1](https://linux-hardware.org/?probe=de0f29b8a1) | Jun 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [b59aed06a2](https://linux-hardware.org/?probe=b59aed06a2) | Jun 11, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ab4e5215f2](https://linux-hardware.org/?probe=ab4e5215f2) | Jun 11, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [089d044872](https://linux-hardware.org/?probe=089d044872) | Jun 11, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [00ba5d4e85](https://linux-hardware.org/?probe=00ba5d4e85) | Jun 11, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [603c2b1a6d](https://linux-hardware.org/?probe=603c2b1a6d) | Jun 11, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [b7b58ba2d6](https://linux-hardware.org/?probe=b7b58ba2d6) | Jun 10, 2020 |
| HP            | ProBook 650 G2              | Notebook    | [3c556d8bae](https://linux-hardware.org/?probe=3c556d8bae) | Jun 10, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [601eeac41c](https://linux-hardware.org/?probe=601eeac41c) | Jun 10, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [72e82818d9](https://linux-hardware.org/?probe=72e82818d9) | Jun 10, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1ef78276ca](https://linux-hardware.org/?probe=1ef78276ca) | Jun 09, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [aa6d4f78a1](https://linux-hardware.org/?probe=aa6d4f78a1) | Jun 09, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [cc19d86c6b](https://linux-hardware.org/?probe=cc19d86c6b) | Jun 09, 2020 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [7f199a6312](https://linux-hardware.org/?probe=7f199a6312) | Jun 09, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [325dca9452](https://linux-hardware.org/?probe=325dca9452) | Jun 08, 2020 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cc9b7372fd](https://linux-hardware.org/?probe=cc9b7372fd) | Jun 08, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [3224444329](https://linux-hardware.org/?probe=3224444329) | Jun 08, 2020 |
| Dell          | Latitude E7470              | Notebook    | [91977e2445](https://linux-hardware.org/?probe=91977e2445) | Jun 07, 2020 |
| Shuttle       | FH310V                      | Desktop     | [b7ec22d789](https://linux-hardware.org/?probe=b7ec22d789) | Jun 06, 2020 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [00d1356ce8](https://linux-hardware.org/?probe=00d1356ce8) | Jun 06, 2020 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [e8b8d502fc](https://linux-hardware.org/?probe=e8b8d502fc) | Jun 06, 2020 |
| Lenovo        | ThinkPad T410 2539FN8       | Notebook    | [cd7eaa3370](https://linux-hardware.org/?probe=cd7eaa3370) | Jun 06, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [64b0911b1b](https://linux-hardware.org/?probe=64b0911b1b) | Jun 04, 2020 |
| HP            | 85BA 01100                  | All in one  | [071c59d998](https://linux-hardware.org/?probe=071c59d998) | Jun 04, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4ba768ffa9](https://linux-hardware.org/?probe=4ba768ffa9) | Jun 03, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [c7abaff76b](https://linux-hardware.org/?probe=c7abaff76b) | Jun 02, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [d330404f1a](https://linux-hardware.org/?probe=d330404f1a) | May 31, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [57f813b6d6](https://linux-hardware.org/?probe=57f813b6d6) | May 30, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9786d0ee28](https://linux-hardware.org/?probe=9786d0ee28) | May 27, 2020 |
| Toshiba       | Satellite L770D-10M         | Notebook    | [45d7d93e61](https://linux-hardware.org/?probe=45d7d93e61) | May 27, 2020 |
| GPD           | P2 MAX                      | Notebook    | [0ab7631fa0](https://linux-hardware.org/?probe=0ab7631fa0) | May 27, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [360fae2046](https://linux-hardware.org/?probe=360fae2046) | May 27, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [814a77a446](https://linux-hardware.org/?probe=814a77a446) | May 27, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [38836b62c5](https://linux-hardware.org/?probe=38836b62c5) | May 26, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eb687fbfa0](https://linux-hardware.org/?probe=eb687fbfa0) | May 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [520b0f5836](https://linux-hardware.org/?probe=520b0f5836) | May 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [bf07595146](https://linux-hardware.org/?probe=bf07595146) | May 26, 2020 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [8d05c8ea16](https://linux-hardware.org/?probe=8d05c8ea16) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349K63       | Notebook    | [43257c3441](https://linux-hardware.org/?probe=43257c3441) | May 26, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [233f8405a6](https://linux-hardware.org/?probe=233f8405a6) | May 25, 2020 |
| HP            | ProLiant DL380p Gen8        | Server      | [f2602534be](https://linux-hardware.org/?probe=f2602534be) | May 25, 2020 |
| HP            | ProLiant DL380p Gen8        | Server      | [55a7b7ec76](https://linux-hardware.org/?probe=55a7b7ec76) | May 25, 2020 |
| HP            | ProLiant DL380p Gen8        | Server      | [05fab72756](https://linux-hardware.org/?probe=05fab72756) | May 25, 2020 |
| HP            | ProBook 4720s               | Notebook    | [8a930097b3](https://linux-hardware.org/?probe=8a930097b3) | May 25, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [316c2aa080](https://linux-hardware.org/?probe=316c2aa080) | May 24, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [f4ee09f8cb](https://linux-hardware.org/?probe=f4ee09f8cb) | May 23, 2020 |
| HP            | Spectre XT Ultrabook PC     | Notebook    | [33888211a1](https://linux-hardware.org/?probe=33888211a1) | May 23, 2020 |
| HP            | EliteBook x360 1030 G2      | Convertible | [fc868835c0](https://linux-hardware.org/?probe=fc868835c0) | May 23, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [fc33c76bdd](https://linux-hardware.org/?probe=fc33c76bdd) | May 23, 2020 |
| HP            | 0A54h                       | Desktop     | [9092cc6d5b](https://linux-hardware.org/?probe=9092cc6d5b) | May 23, 2020 |
| HP            | ENVY 15                     | Notebook    | [0cb17045b2](https://linux-hardware.org/?probe=0cb17045b2) | May 23, 2020 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [b700eaca6d](https://linux-hardware.org/?probe=b700eaca6d) | May 21, 2020 |
| HP            | Presario M2000 (EF152EA#... | Notebook    | [0fe7032974](https://linux-hardware.org/?probe=0fe7032974) | May 21, 2020 |
| Dell          | Latitude 5580               | Notebook    | [39fa074546](https://linux-hardware.org/?probe=39fa074546) | May 21, 2020 |
| HP            | ZBook 17 G5                 | Notebook    | [81b70e2c63](https://linux-hardware.org/?probe=81b70e2c63) | May 21, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [9db9c52de8](https://linux-hardware.org/?probe=9db9c52de8) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| MSI           | AMETHYST-M                  | Desktop     | [b22dad141f](https://linux-hardware.org/?probe=b22dad141f) | May 21, 2020 |
| MSI           | AMETHYST-M                  | Desktop     | [cfd86618c2](https://linux-hardware.org/?probe=cfd86618c2) | May 21, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2450db4a51](https://linux-hardware.org/?probe=2450db4a51) | May 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [4afdcc3247](https://linux-hardware.org/?probe=4afdcc3247) | May 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [651828652f](https://linux-hardware.org/?probe=651828652f) | May 19, 2020 |
| Dell          | 0N4YC8 A00                  | Desktop     | [6230500b28](https://linux-hardware.org/?probe=6230500b28) | May 18, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [e1e0318c65](https://linux-hardware.org/?probe=e1e0318c65) | May 17, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [7e2e078ed7](https://linux-hardware.org/?probe=7e2e078ed7) | May 17, 2020 |
| Toshiba       | Satellite L770D-10M         | Notebook    | [0535faa68f](https://linux-hardware.org/?probe=0535faa68f) | May 16, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [dcf31c4bd0](https://linux-hardware.org/?probe=dcf31c4bd0) | May 16, 2020 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [0aba51adc0](https://linux-hardware.org/?probe=0aba51adc0) | May 16, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [f3c754042c](https://linux-hardware.org/?probe=f3c754042c) | May 16, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [0478994a03](https://linux-hardware.org/?probe=0478994a03) | May 15, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [ffcbdac96b](https://linux-hardware.org/?probe=ffcbdac96b) | May 15, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b8bfdbc277](https://linux-hardware.org/?probe=b8bfdbc277) | May 14, 2020 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [b28847c6ea](https://linux-hardware.org/?probe=b28847c6ea) | May 13, 2020 |
| ASUSTek       | LOCKTITE                    | Desktop     | [422df6694c](https://linux-hardware.org/?probe=422df6694c) | May 11, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [f53d1298ed](https://linux-hardware.org/?probe=f53d1298ed) | May 11, 2020 |
| HP            | ProBook 4510s (NX684EA)     | Notebook    | [d5ef290d7c](https://linux-hardware.org/?probe=d5ef290d7c) | May 11, 2020 |
| Dell          | Latitude E7470              | Notebook    | [faf9979211](https://linux-hardware.org/?probe=faf9979211) | May 10, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [e2c15c5de3](https://linux-hardware.org/?probe=e2c15c5de3) | May 10, 2020 |
| Dell          | 0N4YC8 A00                  | Desktop     | [f405428117](https://linux-hardware.org/?probe=f405428117) | May 09, 2020 |
| HP            | 339A                        | Desktop     | [62dd24eb8b](https://linux-hardware.org/?probe=62dd24eb8b) | May 09, 2020 |
| ICP / iEi     | SA28 V1.0                   | Desktop     | [0c8acc8327](https://linux-hardware.org/?probe=0c8acc8327) | May 09, 2020 |
| HP            | Pavilion dv7                | Notebook    | [886f774f58](https://linux-hardware.org/?probe=886f774f58) | May 07, 2020 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [df6eb0ead4](https://linux-hardware.org/?probe=df6eb0ead4) | May 06, 2020 |
| Notebook      | N130BU                      | Notebook    | [a82966c663](https://linux-hardware.org/?probe=a82966c663) | May 05, 2020 |
| HP            | Notebook                    | Notebook    | [b181cd3ea7](https://linux-hardware.org/?probe=b181cd3ea7) | May 05, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [26402eeaa2](https://linux-hardware.org/?probe=26402eeaa2) | May 05, 2020 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [59cab1b572](https://linux-hardware.org/?probe=59cab1b572) | May 04, 2020 |
| Lenovo        | ThinkPad X230 2325AT6       | Notebook    | [cfa1314238](https://linux-hardware.org/?probe=cfa1314238) | May 04, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [10f7deeb9a](https://linux-hardware.org/?probe=10f7deeb9a) | May 03, 2020 |
| Dell          | Latitude E4200              | Notebook    | [aa2e8b7fd6](https://linux-hardware.org/?probe=aa2e8b7fd6) | May 03, 2020 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [88325f76f5](https://linux-hardware.org/?probe=88325f76f5) | May 03, 2020 |
| HP            | 3033h                       | Desktop     | [c451ac4d8a](https://linux-hardware.org/?probe=c451ac4d8a) | May 03, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [b2b19968b0](https://linux-hardware.org/?probe=b2b19968b0) | May 03, 2020 |
| Acer          | EG43M                       | Desktop     | [7705c31c5e](https://linux-hardware.org/?probe=7705c31c5e) | May 03, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [33eb7a78bc](https://linux-hardware.org/?probe=33eb7a78bc) | May 02, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4962abc204](https://linux-hardware.org/?probe=4962abc204) | May 02, 2020 |
| Kiano         | IntelectX3HD+               | Tablet      | [7310b416de](https://linux-hardware.org/?probe=7310b416de) | May 01, 2020 |
| Kiano         | IntelectX3HD+               | Tablet      | [5309202e51](https://linux-hardware.org/?probe=5309202e51) | May 01, 2020 |
| Razer         | Blade                       | Notebook    | [295cd53ffd](https://linux-hardware.org/?probe=295cd53ffd) | May 01, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1b7191941b](https://linux-hardware.org/?probe=1b7191941b) | May 01, 2020 |
| ASUSTek       | K54HR                       | Notebook    | [4e3b225150](https://linux-hardware.org/?probe=4e3b225150) | May 01, 2020 |
| HP            | Presario CQ62               | Notebook    | [dbca6018f8](https://linux-hardware.org/?probe=dbca6018f8) | Apr 30, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [41cc636255](https://linux-hardware.org/?probe=41cc636255) | Apr 30, 2020 |
| HP            | Presario M2000 (EF152EA#... | Notebook    | [306e665622](https://linux-hardware.org/?probe=306e665622) | Apr 29, 2020 |
| Medion        | MS-7621                     | Desktop     | [6b4999f818](https://linux-hardware.org/?probe=6b4999f818) | Apr 28, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | Notebook    | [88f3f693f1](https://linux-hardware.org/?probe=88f3f693f1) | Apr 28, 2020 |
| ASUSTek       | X751LA                      | Notebook    | [b2d722393a](https://linux-hardware.org/?probe=b2d722393a) | Apr 28, 2020 |
| ASUSTek       | X751LA                      | Notebook    | [803678b78d](https://linux-hardware.org/?probe=803678b78d) | Apr 28, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [e1dad7a6ef](https://linux-hardware.org/?probe=e1dad7a6ef) | Apr 27, 2020 |
| Dell          | 0N4YC8 A00                  | Desktop     | [440b6386de](https://linux-hardware.org/?probe=440b6386de) | Apr 27, 2020 |
| Dell          | 06D7TR A01                  | Desktop     | [50650db6e3](https://linux-hardware.org/?probe=50650db6e3) | Apr 27, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [2c436dd9bf](https://linux-hardware.org/?probe=2c436dd9bf) | Apr 27, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [81a846949f](https://linux-hardware.org/?probe=81a846949f) | Apr 27, 2020 |
| ASUSTek       | UX32LA                      | Notebook    | [5324d81db6](https://linux-hardware.org/?probe=5324d81db6) | Apr 26, 2020 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [b13896e6b7](https://linux-hardware.org/?probe=b13896e6b7) | Apr 26, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [ff7c3fbf23](https://linux-hardware.org/?probe=ff7c3fbf23) | Apr 25, 2020 |
| Lenovo        | ThinkPad W530 24415QG       | Notebook    | [68355ffdc7](https://linux-hardware.org/?probe=68355ffdc7) | Apr 25, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [cbb04bb139](https://linux-hardware.org/?probe=cbb04bb139) | Apr 25, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [36a03baa12](https://linux-hardware.org/?probe=36a03baa12) | Apr 24, 2020 |
| DALCO AG S... | +41 44 908 38 38 support... | Desktop     | [c4614d808a](https://linux-hardware.org/?probe=c4614d808a) | Apr 24, 2020 |
| DALCO AG S... | +41 44 908 38 38 support... | Desktop     | [6bac4a2fa4](https://linux-hardware.org/?probe=6bac4a2fa4) | Apr 24, 2020 |
| DALCO AG S... | +41 44 908 38 38 support... | Desktop     | [d73c67cc67](https://linux-hardware.org/?probe=d73c67cc67) | Apr 24, 2020 |
| DALCO AG S... | +41 44 908 38 38 support... | Desktop     | [4d850557b6](https://linux-hardware.org/?probe=4d850557b6) | Apr 24, 2020 |
| DALCO AG S... | +41 44 908 38 38 support... | Desktop     | [8960d6fa43](https://linux-hardware.org/?probe=8960d6fa43) | Apr 24, 2020 |
| DALCO AG S... | +41 44 908 38 38 support... | Desktop     | [c8471f4e71](https://linux-hardware.org/?probe=c8471f4e71) | Apr 24, 2020 |
| Supermicro    | X8STi                       | Desktop     | [aaf8f51649](https://linux-hardware.org/?probe=aaf8f51649) | Apr 24, 2020 |
| MSI           | MS-9280                     | Server      | [933eed177a](https://linux-hardware.org/?probe=933eed177a) | Apr 24, 2020 |
| Supermicro    | X8DAH                       | Server      | [0b2e10175b](https://linux-hardware.org/?probe=0b2e10175b) | Apr 24, 2020 |
| ASUSTek       | P6T6 WS REVOLUTION          | Desktop     | [9f4f7596c7](https://linux-hardware.org/?probe=9f4f7596c7) | Apr 24, 2020 |
| Acer          | AW2000h F2 G49053-503       | Server      | [d15b8f8758](https://linux-hardware.org/?probe=d15b8f8758) | Apr 24, 2020 |
| Gigabyte      | MG50-G21-XX 01234567        | Server      | [23bc09dd20](https://linux-hardware.org/?probe=23bc09dd20) | Apr 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [5882c13b3b](https://linux-hardware.org/?probe=5882c13b3b) | Apr 24, 2020 |
| Supermicro    | X8STi                       | Desktop     | [3602c430ec](https://linux-hardware.org/?probe=3602c430ec) | Apr 24, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [cd6057df7b](https://linux-hardware.org/?probe=cd6057df7b) | Apr 24, 2020 |
| Supermicro    | X8DT6                       | Server      | [87018aa3b3](https://linux-hardware.org/?probe=87018aa3b3) | Apr 24, 2020 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [83cff222b1](https://linux-hardware.org/?probe=83cff222b1) | Apr 24, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [d27a8c06d5](https://linux-hardware.org/?probe=d27a8c06d5) | Apr 24, 2020 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [801d710e79](https://linux-hardware.org/?probe=801d710e79) | Apr 24, 2020 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [fe75c04eda](https://linux-hardware.org/?probe=fe75c04eda) | Apr 24, 2020 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [5e26461d54](https://linux-hardware.org/?probe=5e26461d54) | Apr 24, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [9d0c57fcda](https://linux-hardware.org/?probe=9d0c57fcda) | Apr 24, 2020 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [9320fe9eed](https://linux-hardware.org/?probe=9320fe9eed) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [19541f6f0c](https://linux-hardware.org/?probe=19541f6f0c) | Apr 24, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e73dadfea3](https://linux-hardware.org/?probe=e73dadfea3) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [8761a9b076](https://linux-hardware.org/?probe=8761a9b076) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [826ebad850](https://linux-hardware.org/?probe=826ebad850) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c04e2415bd](https://linux-hardware.org/?probe=c04e2415bd) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [16b7a6a8f3](https://linux-hardware.org/?probe=16b7a6a8f3) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [129412be91](https://linux-hardware.org/?probe=129412be91) | Apr 24, 2020 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [b7bd40c12a](https://linux-hardware.org/?probe=b7bd40c12a) | Apr 24, 2020 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [0cf9c93ea0](https://linux-hardware.org/?probe=0cf9c93ea0) | Apr 24, 2020 |
| Intel         | DH87MC AAG74242-403         | Desktop     | [9b4a769724](https://linux-hardware.org/?probe=9b4a769724) | Apr 24, 2020 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [8f61b7c628](https://linux-hardware.org/?probe=8f61b7c628) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [d9fb8b2a97](https://linux-hardware.org/?probe=d9fb8b2a97) | Apr 24, 2020 |
| Intel         | S2600WFT H48104-860         | Server      | [d373af93cd](https://linux-hardware.org/?probe=d373af93cd) | Apr 24, 2020 |
| Intel         | S2600WFT H48104-860         | Server      | [89dce5c892](https://linux-hardware.org/?probe=89dce5c892) | Apr 24, 2020 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [ec5f67643e](https://linux-hardware.org/?probe=ec5f67643e) | Apr 24, 2020 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [9dc66cec6a](https://linux-hardware.org/?probe=9dc66cec6a) | Apr 24, 2020 |
| Intel         | DP55WG AAE57269-404         | Desktop     | [052fd5f298](https://linux-hardware.org/?probe=052fd5f298) | Apr 24, 2020 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [07e1348174](https://linux-hardware.org/?probe=07e1348174) | Apr 24, 2020 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [2058c5816b](https://linux-hardware.org/?probe=2058c5816b) | Apr 24, 2020 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [e24cfe07cb](https://linux-hardware.org/?probe=e24cfe07cb) | Apr 24, 2020 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [cbadceabd7](https://linux-hardware.org/?probe=cbadceabd7) | Apr 24, 2020 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [ffc5c7bbbb](https://linux-hardware.org/?probe=ffc5c7bbbb) | Apr 24, 2020 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [4150effa59](https://linux-hardware.org/?probe=4150effa59) | Apr 24, 2020 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [70bbb811be](https://linux-hardware.org/?probe=70bbb811be) | Apr 24, 2020 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [eeeca38b60](https://linux-hardware.org/?probe=eeeca38b60) | Apr 24, 2020 |
| Intel         | W2600CR G21602-302          | Server      | [fbdcc4d1f5](https://linux-hardware.org/?probe=fbdcc4d1f5) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [36fbd50814](https://linux-hardware.org/?probe=36fbd50814) | Apr 24, 2020 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [e048100091](https://linux-hardware.org/?probe=e048100091) | Apr 24, 2020 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [ff23a0f976](https://linux-hardware.org/?probe=ff23a0f976) | Apr 24, 2020 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [11364b1406](https://linux-hardware.org/?probe=11364b1406) | Apr 24, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [af795173b9](https://linux-hardware.org/?probe=af795173b9) | Apr 24, 2020 |
| Intel         | SVRBD-ROW_P G49987-502      | Server      | [30cfd7bc18](https://linux-hardware.org/?probe=30cfd7bc18) | Apr 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [e92dec72e7](https://linux-hardware.org/?probe=e92dec72e7) | Apr 24, 2020 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [0a83e8ce94](https://linux-hardware.org/?probe=0a83e8ce94) | Apr 24, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [da0324a047](https://linux-hardware.org/?probe=da0324a047) | Apr 24, 2020 |
| Medion        | GA-Z170X-Gaming 7           | Desktop     | [0e57192f4c](https://linux-hardware.org/?probe=0e57192f4c) | Apr 24, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [58cbb7a0bd](https://linux-hardware.org/?probe=58cbb7a0bd) | Apr 24, 2020 |
| Supermicro    | H8QG6                       | Server      | [578fea3a6c](https://linux-hardware.org/?probe=578fea3a6c) | Apr 24, 2020 |
| Medion        | GA-Z170X-Gaming 7           | Desktop     | [237fa3c71b](https://linux-hardware.org/?probe=237fa3c71b) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [27751b3305](https://linux-hardware.org/?probe=27751b3305) | Apr 24, 2020 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [ee225cb5df](https://linux-hardware.org/?probe=ee225cb5df) | Apr 24, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [420fa4760d](https://linux-hardware.org/?probe=420fa4760d) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [a7faca0402](https://linux-hardware.org/?probe=a7faca0402) | Apr 24, 2020 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [e71ac23f5f](https://linux-hardware.org/?probe=e71ac23f5f) | Apr 24, 2020 |
| Intel         | DX79SI AAG28808-602         | Desktop     | [7a416f4032](https://linux-hardware.org/?probe=7a416f4032) | Apr 24, 2020 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [fd6eb6c036](https://linux-hardware.org/?probe=fd6eb6c036) | Apr 24, 2020 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d3e211a30f](https://linux-hardware.org/?probe=d3e211a30f) | Apr 24, 2020 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [72f1203e39](https://linux-hardware.org/?probe=72f1203e39) | Apr 24, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [68b75b6456](https://linux-hardware.org/?probe=68b75b6456) | Apr 24, 2020 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [f4979a5d77](https://linux-hardware.org/?probe=f4979a5d77) | Apr 24, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [78ff267cf5](https://linux-hardware.org/?probe=78ff267cf5) | Apr 24, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [87adf30c00](https://linux-hardware.org/?probe=87adf30c00) | Apr 24, 2020 |
| ASUSTek       | X99-S                       | Desktop     | [80a9a70140](https://linux-hardware.org/?probe=80a9a70140) | Apr 24, 2020 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [8383ae4447](https://linux-hardware.org/?probe=8383ae4447) | Apr 24, 2020 |
| ASUSTek       | X99-S                       | Desktop     | [6d6133e931](https://linux-hardware.org/?probe=6d6133e931) | Apr 24, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [7a38347974](https://linux-hardware.org/?probe=7a38347974) | Apr 24, 2020 |
| ASUSTek       | X99-S                       | Desktop     | [497e04da14](https://linux-hardware.org/?probe=497e04da14) | Apr 24, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [7bef7d3648](https://linux-hardware.org/?probe=7bef7d3648) | Apr 24, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [635e0b7a20](https://linux-hardware.org/?probe=635e0b7a20) | Apr 24, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [7567df9403](https://linux-hardware.org/?probe=7567df9403) | Apr 24, 2020 |
| ASUSTek       | X99-S                       | Desktop     | [2ea13c29e3](https://linux-hardware.org/?probe=2ea13c29e3) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [1fe0a4107c](https://linux-hardware.org/?probe=1fe0a4107c) | Apr 24, 2020 |
| ASUSTek       | P6T6 WS REVOLUTION          | Desktop     | [ad07dc757a](https://linux-hardware.org/?probe=ad07dc757a) | Apr 24, 2020 |
| Intel         | DX79SI AAG28808-600         | Desktop     | [576596c77a](https://linux-hardware.org/?probe=576596c77a) | Apr 24, 2020 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [6fcca24e48](https://linux-hardware.org/?probe=6fcca24e48) | Apr 24, 2020 |
| ASUSTek       | P9X79 WS                    | Desktop     | [c6f17810da](https://linux-hardware.org/?probe=c6f17810da) | Apr 24, 2020 |
| Supermicro    | X11QPH+                     | Server      | [e9a2314525](https://linux-hardware.org/?probe=e9a2314525) | Apr 24, 2020 |
| ASUSTek       | X99-S                       | Desktop     | [c25305c678](https://linux-hardware.org/?probe=c25305c678) | Apr 24, 2020 |
| Supermicro    | H8QG6                       | Server      | [b4d697228c](https://linux-hardware.org/?probe=b4d697228c) | Apr 24, 2020 |
| Intel         | W2600CR G21602-302          | Server      | [91f3c901d3](https://linux-hardware.org/?probe=91f3c901d3) | Apr 24, 2020 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [fe1e6cff79](https://linux-hardware.org/?probe=fe1e6cff79) | Apr 24, 2020 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [c22d279967](https://linux-hardware.org/?probe=c22d279967) | Apr 24, 2020 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [7999eec59e](https://linux-hardware.org/?probe=7999eec59e) | Apr 24, 2020 |
| Dell          | 0K240Y A01                  | Desktop     | [b5582d3b26](https://linux-hardware.org/?probe=b5582d3b26) | Apr 24, 2020 |
| Supermicro    | X11QPH+                     | Server      | [106004b589](https://linux-hardware.org/?probe=106004b589) | Apr 24, 2020 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [a6aca7c635](https://linux-hardware.org/?probe=a6aca7c635) | Apr 24, 2020 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [aa750af5d2](https://linux-hardware.org/?probe=aa750af5d2) | Apr 24, 2020 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [1b3d55284f](https://linux-hardware.org/?probe=1b3d55284f) | Apr 24, 2020 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [a75c40f334](https://linux-hardware.org/?probe=a75c40f334) | Apr 24, 2020 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [302e42825d](https://linux-hardware.org/?probe=302e42825d) | Apr 24, 2020 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [511cabeb09](https://linux-hardware.org/?probe=511cabeb09) | Apr 24, 2020 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [35d41193a7](https://linux-hardware.org/?probe=35d41193a7) | Apr 24, 2020 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [ea3d9f0fe8](https://linux-hardware.org/?probe=ea3d9f0fe8) | Apr 24, 2020 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [fabc7c5f56](https://linux-hardware.org/?probe=fabc7c5f56) | Apr 24, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [b1e5672377](https://linux-hardware.org/?probe=b1e5672377) | Apr 24, 2020 |
| Supermicro    | X11DPG-OT-CPU               | Server      | [be9847546a](https://linux-hardware.org/?probe=be9847546a) | Apr 24, 2020 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [a33820a440](https://linux-hardware.org/?probe=a33820a440) | Apr 23, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [963d9a7731](https://linux-hardware.org/?probe=963d9a7731) | Apr 22, 2020 |
| Notebook      | W65_67SZ                    | Notebook    | [dd1415c69a](https://linux-hardware.org/?probe=dd1415c69a) | Apr 22, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [a51b445475](https://linux-hardware.org/?probe=a51b445475) | Apr 21, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ad2959d25b](https://linux-hardware.org/?probe=ad2959d25b) | Apr 20, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b8782abd20](https://linux-hardware.org/?probe=b8782abd20) | Apr 20, 2020 |
| Lenovo        | ThinkPad R61e/R61i 76508... | Notebook    | [6c8a68f429](https://linux-hardware.org/?probe=6c8a68f429) | Apr 19, 2020 |
| Lenovo        | ThinkPad R61e/R61i 76508... | Notebook    | [79cc39e4fe](https://linux-hardware.org/?probe=79cc39e4fe) | Apr 19, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [64c3331e4b](https://linux-hardware.org/?probe=64c3331e4b) | Apr 19, 2020 |
| HP            | Spectre XT Ultrabook PC     | Notebook    | [61a6ec6e80](https://linux-hardware.org/?probe=61a6ec6e80) | Apr 19, 2020 |
| Dell          | Latitude 7490               | Notebook    | [e758664c53](https://linux-hardware.org/?probe=e758664c53) | Apr 18, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [bd484a81ae](https://linux-hardware.org/?probe=bd484a81ae) | Apr 18, 2020 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [29564aa07b](https://linux-hardware.org/?probe=29564aa07b) | Apr 17, 2020 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [f73bfebc87](https://linux-hardware.org/?probe=f73bfebc87) | Apr 17, 2020 |
| Gigabyte      | MG50-G21-XX 01234567        | Server      | [4eaccf1bcd](https://linux-hardware.org/?probe=4eaccf1bcd) | Apr 17, 2020 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [6a4591fe1e](https://linux-hardware.org/?probe=6a4591fe1e) | Apr 17, 2020 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [970c0bc018](https://linux-hardware.org/?probe=970c0bc018) | Apr 17, 2020 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [3962faa988](https://linux-hardware.org/?probe=3962faa988) | Apr 17, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5f75c1ead1](https://linux-hardware.org/?probe=5f75c1ead1) | Apr 17, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [ad8ada015d](https://linux-hardware.org/?probe=ad8ada015d) | Apr 16, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [e9b2348697](https://linux-hardware.org/?probe=e9b2348697) | Apr 16, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [fae24ef621](https://linux-hardware.org/?probe=fae24ef621) | Apr 15, 2020 |
| Toshiba       | Satellite C670D-11G         | Notebook    | [bd4c6365f0](https://linux-hardware.org/?probe=bd4c6365f0) | Apr 14, 2020 |
| Toshiba       | PORTEGE Z10T-A              | Notebook    | [e589328dfd](https://linux-hardware.org/?probe=e589328dfd) | Apr 14, 2020 |
| Toshiba       | Satellite C670D-11G         | Notebook    | [e5d9f42564](https://linux-hardware.org/?probe=e5d9f42564) | Apr 14, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [b39074a74b](https://linux-hardware.org/?probe=b39074a74b) | Apr 13, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [9b6660e48d](https://linux-hardware.org/?probe=9b6660e48d) | Apr 13, 2020 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [d4cc1d31f8](https://linux-hardware.org/?probe=d4cc1d31f8) | Apr 12, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [9bc8062711](https://linux-hardware.org/?probe=9bc8062711) | Apr 12, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [de58b77e1e](https://linux-hardware.org/?probe=de58b77e1e) | Apr 12, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3cdd294ded](https://linux-hardware.org/?probe=3cdd294ded) | Apr 12, 2020 |
| Acer          | Swift SF514-52T             | Notebook    | [5aab994428](https://linux-hardware.org/?probe=5aab994428) | Apr 11, 2020 |
| HP            | Pavilion x2 Detachable      | Tablet      | [67c34aa84e](https://linux-hardware.org/?probe=67c34aa84e) | Apr 11, 2020 |
| Toshiba       | Satellite L830              | Notebook    | [b61b14b568](https://linux-hardware.org/?probe=b61b14b568) | Apr 10, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [5fccd4e61a](https://linux-hardware.org/?probe=5fccd4e61a) | Apr 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [e3e43fc692](https://linux-hardware.org/?probe=e3e43fc692) | Apr 08, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [760ea332f8](https://linux-hardware.org/?probe=760ea332f8) | Apr 08, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [e1d0e412e7](https://linux-hardware.org/?probe=e1d0e412e7) | Apr 08, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [c043b205ae](https://linux-hardware.org/?probe=c043b205ae) | Apr 08, 2020 |
| ASUSTek       | GL702ZC                     | Notebook    | [6d53521870](https://linux-hardware.org/?probe=6d53521870) | Apr 08, 2020 |
| Toshiba       | Satellite L770D-10M         | Notebook    | [2de171c7fb](https://linux-hardware.org/?probe=2de171c7fb) | Apr 08, 2020 |
| GPD           | P2 MAX                      | Notebook    | [4d0fb79b80](https://linux-hardware.org/?probe=4d0fb79b80) | Apr 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [415525e0cb](https://linux-hardware.org/?probe=415525e0cb) | Apr 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [604566e117](https://linux-hardware.org/?probe=604566e117) | Apr 08, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7f26e3bf38](https://linux-hardware.org/?probe=7f26e3bf38) | Apr 08, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [fc6c1fb9af](https://linux-hardware.org/?probe=fc6c1fb9af) | Apr 07, 2020 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [8ffdabd96c](https://linux-hardware.org/?probe=8ffdabd96c) | Apr 06, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [3635caddd6](https://linux-hardware.org/?probe=3635caddd6) | Apr 06, 2020 |
| Acer          | Aspire E1-572G              | Notebook    | [65b7187917](https://linux-hardware.org/?probe=65b7187917) | Apr 06, 2020 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [31e4fb69f4](https://linux-hardware.org/?probe=31e4fb69f4) | Apr 05, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [8fda391db3](https://linux-hardware.org/?probe=8fda391db3) | Apr 03, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [75b9592f5b](https://linux-hardware.org/?probe=75b9592f5b) | Apr 02, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [95ea11518e](https://linux-hardware.org/?probe=95ea11518e) | Apr 01, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [10fda9ca4f](https://linux-hardware.org/?probe=10fda9ca4f) | Apr 01, 2020 |
| Acer          | AOD255E                     | Notebook    | [f04d1a1bf5](https://linux-hardware.org/?probe=f04d1a1bf5) | Apr 01, 2020 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [4d21c77b2b](https://linux-hardware.org/?probe=4d21c77b2b) | Mar 30, 2020 |
| Gigabyte      | Z170N-Gaming 5              | Desktop     | [6b1c9f4403](https://linux-hardware.org/?probe=6b1c9f4403) | Mar 30, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [266020f70f](https://linux-hardware.org/?probe=266020f70f) | Mar 29, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [c24febeb28](https://linux-hardware.org/?probe=c24febeb28) | Mar 28, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [e7400380e1](https://linux-hardware.org/?probe=e7400380e1) | Mar 28, 2020 |
| HP            | Pavilion dv7                | Notebook    | [4dfd72b613](https://linux-hardware.org/?probe=4dfd72b613) | Mar 25, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [81ec5d7a38](https://linux-hardware.org/?probe=81ec5d7a38) | Mar 24, 2020 |
| Alienware     | M17xR3                      | Notebook    | [c95c1a6306](https://linux-hardware.org/?probe=c95c1a6306) | Mar 22, 2020 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [d6c3c3e4de](https://linux-hardware.org/?probe=d6c3c3e4de) | Mar 22, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [1a7c0f8913](https://linux-hardware.org/?probe=1a7c0f8913) | Mar 22, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [2e75c92ac7](https://linux-hardware.org/?probe=2e75c92ac7) | Mar 21, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [f1f43e0def](https://linux-hardware.org/?probe=f1f43e0def) | Mar 20, 2020 |
| HP            | Compaq 8510p                | Notebook    | [df003f9b94](https://linux-hardware.org/?probe=df003f9b94) | Mar 19, 2020 |
| HP            | Compaq 8510p                | Notebook    | [6a272fe91c](https://linux-hardware.org/?probe=6a272fe91c) | Mar 19, 2020 |
| Lenovo        | ThinkPad T440s 20ARA0K40... | Notebook    | [e44cab8ed9](https://linux-hardware.org/?probe=e44cab8ed9) | Mar 19, 2020 |
| ASUSTek       | P5QC                        | Desktop     | [d93794a40c](https://linux-hardware.org/?probe=d93794a40c) | Mar 18, 2020 |
| HP            | EliteBook 1050 G1           | Notebook    | [167fb7714a](https://linux-hardware.org/?probe=167fb7714a) | Mar 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [be9fa7d137](https://linux-hardware.org/?probe=be9fa7d137) | Mar 18, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [6fc8fe8a2b](https://linux-hardware.org/?probe=6fc8fe8a2b) | Mar 18, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [96e42952bb](https://linux-hardware.org/?probe=96e42952bb) | Mar 17, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [5857953046](https://linux-hardware.org/?probe=5857953046) | Mar 17, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [0b56bb4691](https://linux-hardware.org/?probe=0b56bb4691) | Mar 17, 2020 |
| Intel         | NUC5i5RYB H40999-506        | Mini pc     | [4b8850eb6b](https://linux-hardware.org/?probe=4b8850eb6b) | Mar 17, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [fe149adc3e](https://linux-hardware.org/?probe=fe149adc3e) | Mar 17, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [ca91d7623b](https://linux-hardware.org/?probe=ca91d7623b) | Mar 16, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [9c6027e4f4](https://linux-hardware.org/?probe=9c6027e4f4) | Mar 16, 2020 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [2daaf4abb5](https://linux-hardware.org/?probe=2daaf4abb5) | Mar 16, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [a272506aba](https://linux-hardware.org/?probe=a272506aba) | Mar 15, 2020 |
| Lenovo        | 36F5 SDK0J40709 WIN 3259... | All in one  | [c61f993775](https://linux-hardware.org/?probe=c61f993775) | Mar 15, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [4067c9ebf6](https://linux-hardware.org/?probe=4067c9ebf6) | Mar 14, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [33202d11c3](https://linux-hardware.org/?probe=33202d11c3) | Mar 14, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [5e585ebf8d](https://linux-hardware.org/?probe=5e585ebf8d) | Mar 14, 2020 |
| Lenovo        | V110-17IKB 80V2             | Notebook    | [627d8806c0](https://linux-hardware.org/?probe=627d8806c0) | Mar 14, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [8bb55a3d9e](https://linux-hardware.org/?probe=8bb55a3d9e) | Mar 13, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [70fcb71068](https://linux-hardware.org/?probe=70fcb71068) | Mar 08, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e439957a21](https://linux-hardware.org/?probe=e439957a21) | Mar 08, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [77506db6b3](https://linux-hardware.org/?probe=77506db6b3) | Mar 07, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [2d8726b789](https://linux-hardware.org/?probe=2d8726b789) | Mar 07, 2020 |
| Dell          | Latitude E7240              | Notebook    | [5a2177b51f](https://linux-hardware.org/?probe=5a2177b51f) | Mar 07, 2020 |
| Apple         | MacBookPro5,5               | Notebook    | [626eb80e57](https://linux-hardware.org/?probe=626eb80e57) | Mar 06, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [f36db4ade4](https://linux-hardware.org/?probe=f36db4ade4) | Mar 03, 2020 |
| Kontron       | SMX945                      | Mini pc     | [10db69dd6c](https://linux-hardware.org/?probe=10db69dd6c) | Mar 03, 2020 |
| Intel         | NUC6CAYB J26842-406         | Mini pc     | [ef4cbe2d05](https://linux-hardware.org/?probe=ef4cbe2d05) | Feb 29, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [39e883651d](https://linux-hardware.org/?probe=39e883651d) | Feb 23, 2020 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5289928f59](https://linux-hardware.org/?probe=5289928f59) | Feb 20, 2020 |
| Lenovo        | ThinkPad T580 20L90025MZ    | Notebook    | [eec9fced7e](https://linux-hardware.org/?probe=eec9fced7e) | Feb 20, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [a07b95ca17](https://linux-hardware.org/?probe=a07b95ca17) | Feb 19, 2020 |
| Intel         | S2600WFT H48104-860         | Server      | [722c728658](https://linux-hardware.org/?probe=722c728658) | Feb 19, 2020 |
| Gigabyte      | MG50-G21-XX 01234567        | Server      | [43243d3e32](https://linux-hardware.org/?probe=43243d3e32) | Feb 19, 2020 |
| Supermicro    | X11QPH+                     | Server      | [8e9ab4e7a1](https://linux-hardware.org/?probe=8e9ab4e7a1) | Feb 19, 2020 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [4d9abaae4c](https://linux-hardware.org/?probe=4d9abaae4c) | Feb 19, 2020 |
| Intel         | W2600CR G21602-302          | Server      | [a230cb590f](https://linux-hardware.org/?probe=a230cb590f) | Feb 19, 2020 |
| ASUSTek       | BU201LA                     | Notebook    | [8deefa2e71](https://linux-hardware.org/?probe=8deefa2e71) | Feb 18, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [094dcdba54](https://linux-hardware.org/?probe=094dcdba54) | Feb 16, 2020 |
| Lenovo        | ThinkPad L490 20Q500E2GE    | Notebook    | [600d77c38c](https://linux-hardware.org/?probe=600d77c38c) | Feb 12, 2020 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [277f724b59](https://linux-hardware.org/?probe=277f724b59) | Feb 08, 2020 |
| Acer          | Aspire E5-571               | Notebook    | [35c5646f7a](https://linux-hardware.org/?probe=35c5646f7a) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | Notebook    | [26283f93ce](https://linux-hardware.org/?probe=26283f93ce) | Feb 06, 2020 |
| Acer          | Aspire E5-571               | Notebook    | [e4e6b2ff99](https://linux-hardware.org/?probe=e4e6b2ff99) | Feb 06, 2020 |
| Razer         | Blade                       | Notebook    | [f3ca010de6](https://linux-hardware.org/?probe=f3ca010de6) | Feb 05, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [16a5c6cce2](https://linux-hardware.org/?probe=16a5c6cce2) | Feb 05, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b173313efb](https://linux-hardware.org/?probe=b173313efb) | Feb 04, 2020 |
| HP            | 18E5                        | Desktop     | [45c740f3c6](https://linux-hardware.org/?probe=45c740f3c6) | Feb 04, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [cf9327ee85](https://linux-hardware.org/?probe=cf9327ee85) | Feb 03, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [0b86ca51ce](https://linux-hardware.org/?probe=0b86ca51ce) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460s 20FAS35H0... | Notebook    | [3cac01dde7](https://linux-hardware.org/?probe=3cac01dde7) | Jan 30, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [7dd3327069](https://linux-hardware.org/?probe=7dd3327069) | Jan 29, 2020 |
| Acer          | Extensa 5620                | Notebook    | [74ce2714b9](https://linux-hardware.org/?probe=74ce2714b9) | Jan 28, 2020 |
| ASUSTek       | Z97-PRO                     | Desktop     | [ec5274c25b](https://linux-hardware.org/?probe=ec5274c25b) | Jan 26, 2020 |
| HP            | Pavilion g6                 | Notebook    | [b4dc59c9b5](https://linux-hardware.org/?probe=b4dc59c9b5) | Jan 26, 2020 |
| ASRock        | X399 Taichi                 | Desktop     | [9051923242](https://linux-hardware.org/?probe=9051923242) | Jan 25, 2020 |
| HP            | 18E5                        | Desktop     | [12a4308fbb](https://linux-hardware.org/?probe=12a4308fbb) | Jan 25, 2020 |
| HP            | 18E5                        | Desktop     | [ef1bf0b9d7](https://linux-hardware.org/?probe=ef1bf0b9d7) | Jan 25, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [4093fa6a7b](https://linux-hardware.org/?probe=4093fa6a7b) | Jan 25, 2020 |
| Dell          | Latitude E5470              | Notebook    | [b7cde05446](https://linux-hardware.org/?probe=b7cde05446) | Jan 25, 2020 |
| HP            | ProBook 470 G4              | Notebook    | [e892d44c9a](https://linux-hardware.org/?probe=e892d44c9a) | Jan 24, 2020 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [29dc0371d1](https://linux-hardware.org/?probe=29dc0371d1) | Jan 24, 2020 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [64fcbf4969](https://linux-hardware.org/?probe=64fcbf4969) | Jan 24, 2020 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [5e60c2c70d](https://linux-hardware.org/?probe=5e60c2c70d) | Jan 24, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [7037464ff1](https://linux-hardware.org/?probe=7037464ff1) | Jan 24, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [b26cdf336b](https://linux-hardware.org/?probe=b26cdf336b) | Jan 23, 2020 |
| ASRock        | H370M Pro4                  | Desktop     | [89c886d682](https://linux-hardware.org/?probe=89c886d682) | Jan 22, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [45c0b43f7d](https://linux-hardware.org/?probe=45c0b43f7d) | Jan 22, 2020 |
| Dell          | Inspiron 7586               | Notebook    | [817366445e](https://linux-hardware.org/?probe=817366445e) | Jan 19, 2020 |
| Acer          | Aspire A515-51              | Notebook    | [d62b0e00e5](https://linux-hardware.org/?probe=d62b0e00e5) | Jan 16, 2020 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [30eef366f0](https://linux-hardware.org/?probe=30eef366f0) | Jan 14, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [429670a7b5](https://linux-hardware.org/?probe=429670a7b5) | Jan 12, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [6c4e2e9577](https://linux-hardware.org/?probe=6c4e2e9577) | Jan 12, 2020 |
| HP            | ProBook 4510s (NX684EA)     | Notebook    | [c5e3713f32](https://linux-hardware.org/?probe=c5e3713f32) | Jan 11, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [52afbedeb1](https://linux-hardware.org/?probe=52afbedeb1) | Jan 11, 2020 |
| HP            | ProBook 4510s (NX684EA)     | Notebook    | [adc6fb36d6](https://linux-hardware.org/?probe=adc6fb36d6) | Jan 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [aba575e92e](https://linux-hardware.org/?probe=aba575e92e) | Jan 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [46fbb0765e](https://linux-hardware.org/?probe=46fbb0765e) | Jan 08, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5144138cef](https://linux-hardware.org/?probe=5144138cef) | Jan 07, 2020 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [1980160fda](https://linux-hardware.org/?probe=1980160fda) | Jan 07, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [8d4fecc4d4](https://linux-hardware.org/?probe=8d4fecc4d4) | Jan 04, 2020 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [78b5820785](https://linux-hardware.org/?probe=78b5820785) | Jan 03, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [25f2dfdae2](https://linux-hardware.org/?probe=25f2dfdae2) | Jan 02, 2020 |
| ZOTAC         | ZBOX-CI329NANO              | Mini pc     | [1505d24b7d](https://linux-hardware.org/?probe=1505d24b7d) | Jan 02, 2020 |
| Dell          | 0C7195                      | Desktop     | [9f2d67a15d](https://linux-hardware.org/?probe=9f2d67a15d) | Dec 30, 2019 |
| Dell          | 0C7195                      | Desktop     | [888b00ca6e](https://linux-hardware.org/?probe=888b00ca6e) | Dec 30, 2019 |
| ASRock        | X570 Taichi                 | Desktop     | [db38404062](https://linux-hardware.org/?probe=db38404062) | Dec 29, 2019 |
| ASRock        | X570 Taichi                 | Desktop     | [7c5c95338c](https://linux-hardware.org/?probe=7c5c95338c) | Dec 29, 2019 |
| HP            | Laptop 15-bs1xx             | Notebook    | [466f00e8ce](https://linux-hardware.org/?probe=466f00e8ce) | Dec 28, 2019 |
| HP            | Laptop 15-bs1xx             | Notebook    | [3c1859d120](https://linux-hardware.org/?probe=3c1859d120) | Dec 28, 2019 |
| ASRock        | X570 Taichi                 | Desktop     | [53a54c8b79](https://linux-hardware.org/?probe=53a54c8b79) | Dec 28, 2019 |
| Dell          | 0WG855                      | Desktop     | [ad5a7b75b6](https://linux-hardware.org/?probe=ad5a7b75b6) | Dec 27, 2019 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [41b8e420f5](https://linux-hardware.org/?probe=41b8e420f5) | Dec 25, 2019 |
| HP            | ENVY 15                     | Notebook    | [2e33715189](https://linux-hardware.org/?probe=2e33715189) | Dec 23, 2019 |
| Dell          | XPS 15 9570                 | Notebook    | [0f12a3e78b](https://linux-hardware.org/?probe=0f12a3e78b) | Dec 22, 2019 |
| TrekStor      | Primebook C13B              | Convertible | [cba368d785](https://linux-hardware.org/?probe=cba368d785) | Dec 21, 2019 |
| Acer          | Swift SF515-51T             | Notebook    | [82680ee78b](https://linux-hardware.org/?probe=82680ee78b) | Dec 19, 2019 |
| ASUSTek       | N53SN                       | Notebook    | [b7b1c7df29](https://linux-hardware.org/?probe=b7b1c7df29) | Dec 18, 2019 |
| Dell          | XPS 13 9380                 | Notebook    | [ed8598db62](https://linux-hardware.org/?probe=ed8598db62) | Dec 18, 2019 |
| HP            | 1496                        | Desktop     | [b31e6e7c4b](https://linux-hardware.org/?probe=b31e6e7c4b) | Dec 17, 2019 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [8962c13bbb](https://linux-hardware.org/?probe=8962c13bbb) | Dec 15, 2019 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [a028ac88e0](https://linux-hardware.org/?probe=a028ac88e0) | Dec 15, 2019 |
| HP            | 1496                        | Desktop     | [52f354b570](https://linux-hardware.org/?probe=52f354b570) | Dec 12, 2019 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [cd3c0c4583](https://linux-hardware.org/?probe=cd3c0c4583) | Dec 09, 2019 |
| HP            | EliteBook 840 G6            | Notebook    | [6b2396c6ac](https://linux-hardware.org/?probe=6b2396c6ac) | Dec 08, 2019 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [fd4052dd11](https://linux-hardware.org/?probe=fd4052dd11) | Dec 07, 2019 |
| Dell          | XPS 13 9380                 | Notebook    | [5ad2c7bcc8](https://linux-hardware.org/?probe=5ad2c7bcc8) | Dec 07, 2019 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [9d7fe6ed8f](https://linux-hardware.org/?probe=9d7fe6ed8f) | Dec 05, 2019 |
| ASUSTek       | UX32LA                      | Notebook    | [e6d66177e4](https://linux-hardware.org/?probe=e6d66177e4) | Dec 02, 2019 |
| Intel         | SLIMBOOK                    | Notebook    | [83fd1e037a](https://linux-hardware.org/?probe=83fd1e037a) | Nov 30, 2019 |
| Sony          | VGN-AR61ZU                  | Notebook    | [29555cdbc9](https://linux-hardware.org/?probe=29555cdbc9) | Nov 29, 2019 |
| Sony          | VGN-AR61ZU                  | Notebook    | [f0fdef9237](https://linux-hardware.org/?probe=f0fdef9237) | Nov 29, 2019 |
| Sony          | VGN-AR61ZU                  | Notebook    | [f2d1cef8d0](https://linux-hardware.org/?probe=f2d1cef8d0) | Nov 29, 2019 |
| HP            | ProBook 440 G6              | Notebook    | [c5d25d77c1](https://linux-hardware.org/?probe=c5d25d77c1) | Nov 25, 2019 |
| Acer          | Aspire 5750G                | Notebook    | [12268e6403](https://linux-hardware.org/?probe=12268e6403) | Nov 24, 2019 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [e3f4b8cc47](https://linux-hardware.org/?probe=e3f4b8cc47) | Nov 21, 2019 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [fd5a5fbd54](https://linux-hardware.org/?probe=fd5a5fbd54) | Nov 17, 2019 |
| Dell          | 0N2828                      | Desktop     | [2db2d591e5](https://linux-hardware.org/?probe=2db2d591e5) | Nov 17, 2019 |
| Dell          | 0N2828                      | Desktop     | [230c913876](https://linux-hardware.org/?probe=230c913876) | Nov 17, 2019 |
| ASRock        | H97M Pro4                   | Desktop     | [cf6b1c24e5](https://linux-hardware.org/?probe=cf6b1c24e5) | Nov 16, 2019 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [ca81165f05](https://linux-hardware.org/?probe=ca81165f05) | Nov 11, 2019 |
| Purism        | Librem 15 v3                | Notebook    | [8200c0dcd0](https://linux-hardware.org/?probe=8200c0dcd0) | Nov 11, 2019 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [ba2c110e8a](https://linux-hardware.org/?probe=ba2c110e8a) | Nov 11, 2019 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [b243c93172](https://linux-hardware.org/?probe=b243c93172) | Nov 10, 2019 |
| Dell          | 0H634K A00                  | Desktop     | [dd884cb062](https://linux-hardware.org/?probe=dd884cb062) | Nov 09, 2019 |
| Lenovo        | G50-80 80E5                 | Notebook    | [c8baf0aedf](https://linux-hardware.org/?probe=c8baf0aedf) | Nov 04, 2019 |
| Lenovo        | ThinkPad W530 24415QG       | Notebook    | [e9fdf75898](https://linux-hardware.org/?probe=e9fdf75898) | Nov 03, 2019 |
| HP            | ProBook 4510s (NX684EA)     | Notebook    | [0f854e2760](https://linux-hardware.org/?probe=0f854e2760) | Nov 03, 2019 |
| Acer          | Predator G3620              | Desktop     | [100c1162bf](https://linux-hardware.org/?probe=100c1162bf) | Nov 01, 2019 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [ef911c1d99](https://linux-hardware.org/?probe=ef911c1d99) | Oct 31, 2019 |
| Lenovo        | ThinkPad X200 7458AL7       | Notebook    | [82bf41baa8](https://linux-hardware.org/?probe=82bf41baa8) | Oct 30, 2019 |
| HP            | 1905                        | Desktop     | [b71478d2e9](https://linux-hardware.org/?probe=b71478d2e9) | Oct 29, 2019 |
| Dell          | 0M9KCM A00                  | Desktop     | [cd6b602b21](https://linux-hardware.org/?probe=cd6b602b21) | Oct 28, 2019 |
| Medion        | MS-7728                     | Desktop     | [011b6595f4](https://linux-hardware.org/?probe=011b6595f4) | Oct 27, 2019 |
| HP            | ProBook 4720s               | Notebook    | [2b18aab1d4](https://linux-hardware.org/?probe=2b18aab1d4) | Oct 27, 2019 |
| Unknown       | Unknown                     | Phone       | [bd5043a779](https://linux-hardware.org/?probe=bd5043a779) | Oct 27, 2019 |
| Acer          | Predator G3620              | Desktop     | [24e070af7f](https://linux-hardware.org/?probe=24e070af7f) | Oct 25, 2019 |
| Dell          | XPS 13 9360                 | Notebook    | [6345d39841](https://linux-hardware.org/?probe=6345d39841) | Oct 24, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [c480ceb1fc](https://linux-hardware.org/?probe=c480ceb1fc) | Oct 23, 2019 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [b9e00b59be](https://linux-hardware.org/?probe=b9e00b59be) | Oct 23, 2019 |
| HP            | 340 G1                      | Notebook    | [f863818e22](https://linux-hardware.org/?probe=f863818e22) | Oct 20, 2019 |
| HP            | 340 G1                      | Notebook    | [e3c7d03451](https://linux-hardware.org/?probe=e3c7d03451) | Oct 16, 2019 |
| HP            | 340 G1                      | Notebook    | [215a000bc9](https://linux-hardware.org/?probe=215a000bc9) | Oct 15, 2019 |
| Acer          | Swift SF515-51T             | Notebook    | [41acdd878f](https://linux-hardware.org/?probe=41acdd878f) | Oct 11, 2019 |
| HP            | ZBook 15u G5                | Notebook    | [2da8c12709](https://linux-hardware.org/?probe=2da8c12709) | Oct 11, 2019 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [940fe08674](https://linux-hardware.org/?probe=940fe08674) | Oct 08, 2019 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d3d097861b](https://linux-hardware.org/?probe=d3d097861b) | Oct 06, 2019 |
| HP            | ZBook 15u G5                | Notebook    | [64f3687189](https://linux-hardware.org/?probe=64f3687189) | Oct 05, 2019 |
| Acer          | Aspire V3-772G              | Notebook    | [9cbde1e6e7](https://linux-hardware.org/?probe=9cbde1e6e7) | Oct 04, 2019 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [b3ee98b7cc](https://linux-hardware.org/?probe=b3ee98b7cc) | Sep 30, 2019 |
| HP            | 0B4Ch D                     | Desktop     | [0036caeb83](https://linux-hardware.org/?probe=0036caeb83) | Sep 29, 2019 |
| HP            | 1998                        | Desktop     | [05505081a2](https://linux-hardware.org/?probe=05505081a2) | Sep 27, 2019 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [499cf2b15d](https://linux-hardware.org/?probe=499cf2b15d) | Sep 27, 2019 |
| HP            | Pavilion dv6                | Notebook    | [b4abc46a27](https://linux-hardware.org/?probe=b4abc46a27) | Sep 26, 2019 |
| ASUSTek       | UX32LA                      | Notebook    | [e0f1a331b9](https://linux-hardware.org/?probe=e0f1a331b9) | Sep 25, 2019 |
| HP            | Pavilion dv6                | Notebook    | [0486a0da54](https://linux-hardware.org/?probe=0486a0da54) | Sep 25, 2019 |
| ASRock        | Z87 Killer                  | Desktop     | [78b2cb4498](https://linux-hardware.org/?probe=78b2cb4498) | Sep 24, 2019 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [33a0e5fdca](https://linux-hardware.org/?probe=33a0e5fdca) | Sep 22, 2019 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a615b72041](https://linux-hardware.org/?probe=a615b72041) | Sep 22, 2019 |
| Lenovo        | ThinkPad W530 24415QG       | Notebook    | [38f63abc72](https://linux-hardware.org/?probe=38f63abc72) | Sep 20, 2019 |
| Apple         | Mac-F221BEC8                | Desktop     | [426d47274f](https://linux-hardware.org/?probe=426d47274f) | Sep 20, 2019 |
| Acer          | Aspire 9420                 | Notebook    | [ba6be6e3d1](https://linux-hardware.org/?probe=ba6be6e3d1) | Sep 18, 2019 |
| Acer          | Aspire 9420                 | Notebook    | [e3d0a72d4c](https://linux-hardware.org/?probe=e3d0a72d4c) | Sep 18, 2019 |
| Acer          | Aspire 9420                 | Notebook    | [812a215a30](https://linux-hardware.org/?probe=812a215a30) | Sep 18, 2019 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [5b2acded8d](https://linux-hardware.org/?probe=5b2acded8d) | Sep 18, 2019 |
| HP            | Laptop 15-da1xxx            | Notebook    | [d0baad03d5](https://linux-hardware.org/?probe=d0baad03d5) | Sep 17, 2019 |
| ASUSTek       | X541UAK                     | Notebook    | [3391ce42a4](https://linux-hardware.org/?probe=3391ce42a4) | Sep 15, 2019 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [e608c63a17](https://linux-hardware.org/?probe=e608c63a17) | Sep 13, 2019 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [21c54b23dd](https://linux-hardware.org/?probe=21c54b23dd) | Sep 12, 2019 |
| HP            | 0A58h                       | Desktop     | [52ce0d8cdb](https://linux-hardware.org/?probe=52ce0d8cdb) | Sep 09, 2019 |
| HP            | 0A58h                       | Desktop     | [380bee64b6](https://linux-hardware.org/?probe=380bee64b6) | Sep 09, 2019 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [90a5bb3f2d](https://linux-hardware.org/?probe=90a5bb3f2d) | Sep 02, 2019 |
| Dell          | XPS 13 9370                 | Notebook    | [db11a12d79](https://linux-hardware.org/?probe=db11a12d79) | Aug 30, 2019 |
| Gigabyte      | X299 UD4-CF                 | Desktop     | [2a419739cd](https://linux-hardware.org/?probe=2a419739cd) | Aug 30, 2019 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [ec40f1eaf7](https://linux-hardware.org/?probe=ec40f1eaf7) | Aug 29, 2019 |
| Sony          | VGN-N31Z_W                  | Notebook    | [b389939ee8](https://linux-hardware.org/?probe=b389939ee8) | Aug 26, 2019 |
| HP            | EliteBook 8570w             | Notebook    | [6505212d74](https://linux-hardware.org/?probe=6505212d74) | Aug 20, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [c7c67b372e](https://linux-hardware.org/?probe=c7c67b372e) | Aug 18, 2019 |
| HP            | 18E5                        | Desktop     | [f56e8ddf03](https://linux-hardware.org/?probe=f56e8ddf03) | Aug 12, 2019 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [b71ea2bec1](https://linux-hardware.org/?probe=b71ea2bec1) | Aug 12, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [c84b37d646](https://linux-hardware.org/?probe=c84b37d646) | Aug 07, 2019 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [169a8accfa](https://linux-hardware.org/?probe=169a8accfa) | Aug 05, 2019 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [1a463ad731](https://linux-hardware.org/?probe=1a463ad731) | Aug 05, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [2c04cb9707](https://linux-hardware.org/?probe=2c04cb9707) | Aug 02, 2019 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [e42e6b15b6](https://linux-hardware.org/?probe=e42e6b15b6) | Jul 31, 2019 |
| Shuttle       | FS61                        | Desktop     | [fb926e0210](https://linux-hardware.org/?probe=fb926e0210) | Jul 30, 2019 |
| HP            | ProBook 4510s (NX684EA)     | Notebook    | [ed4599659c](https://linux-hardware.org/?probe=ed4599659c) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20ARA0K3M... | Notebook    | [efd88a9c7a](https://linux-hardware.org/?probe=efd88a9c7a) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20ARA0K3M... | Notebook    | [19fe1122be](https://linux-hardware.org/?probe=19fe1122be) | Jul 29, 2019 |
| LattePanda    | Alpha                       | Desktop     | [44204f310c](https://linux-hardware.org/?probe=44204f310c) | Jul 27, 2019 |
| HP            | ZBook 14 G2                 | Notebook    | [ac96dd45f9](https://linux-hardware.org/?probe=ac96dd45f9) | Jul 26, 2019 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ec70e7cec](https://linux-hardware.org/?probe=2ec70e7cec) | Jul 25, 2019 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [23dc7c0455](https://linux-hardware.org/?probe=23dc7c0455) | Jul 25, 2019 |
| HP            | Pavilion dv6                | Notebook    | [e09686c315](https://linux-hardware.org/?probe=e09686c315) | Jul 24, 2019 |
| ASUSTek       | PTGD2-VX                    | Desktop     | [f1e5880584](https://linux-hardware.org/?probe=f1e5880584) | Jul 24, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [3b331bb4af](https://linux-hardware.org/?probe=3b331bb4af) | Jul 24, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [b18f2347f5](https://linux-hardware.org/?probe=b18f2347f5) | Jul 24, 2019 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [83192a2228](https://linux-hardware.org/?probe=83192a2228) | Jul 22, 2019 |
| HP            | 0A60h                       | Desktop     | [a95491b363](https://linux-hardware.org/?probe=a95491b363) | Jul 20, 2019 |
| HP            | 0A60h                       | Desktop     | [09f65dea65](https://linux-hardware.org/?probe=09f65dea65) | Jul 20, 2019 |
| HP            | 18E5                        | Desktop     | [7ef14d422d](https://linux-hardware.org/?probe=7ef14d422d) | Jul 17, 2019 |
| HP            | Compaq 6730b (NB021ET#UU... | Notebook    | [6832a5fe8d](https://linux-hardware.org/?probe=6832a5fe8d) | Jul 16, 2019 |
| Gigabyte      | X79-UD3                     | Desktop     | [e3cd42a469](https://linux-hardware.org/?probe=e3cd42a469) | Jul 11, 2019 |
| Sony          | VGN-SZ3HP_B                 | Notebook    | [50e5b9d6ca](https://linux-hardware.org/?probe=50e5b9d6ca) | Jul 10, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [ff3cfe3b17](https://linux-hardware.org/?probe=ff3cfe3b17) | Jul 08, 2019 |
| Dell          | XPS 13 9380                 | Notebook    | [d4a2d02674](https://linux-hardware.org/?probe=d4a2d02674) | Jul 06, 2019 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [0a0473cd45](https://linux-hardware.org/?probe=0a0473cd45) | Jul 06, 2019 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [f24ee710ee](https://linux-hardware.org/?probe=f24ee710ee) | Jul 06, 2019 |
| whyopencom... | Unknown                     | Notebook    | [9ebfe9a2d8](https://linux-hardware.org/?probe=9ebfe9a2d8) | Jul 03, 2019 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [252e0b908d](https://linux-hardware.org/?probe=252e0b908d) | Jun 28, 2019 |
| HP            | TouchSmart tm2              | Notebook    | [746faf4d3a](https://linux-hardware.org/?probe=746faf4d3a) | Jun 28, 2019 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [30502c41de](https://linux-hardware.org/?probe=30502c41de) | Jun 27, 2019 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [99f67add36](https://linux-hardware.org/?probe=99f67add36) | Jun 27, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [464706154e](https://linux-hardware.org/?probe=464706154e) | Jun 26, 2019 |
| HP            | ZBook 14 G2                 | Notebook    | [5bf8f80c1a](https://linux-hardware.org/?probe=5bf8f80c1a) | Jun 26, 2019 |
| Dell          | 0TP412                      | Desktop     | [be7a893f7d](https://linux-hardware.org/?probe=be7a893f7d) | Jun 22, 2019 |
| HP            | 0B4Ch D                     | Desktop     | [31167a5e46](https://linux-hardware.org/?probe=31167a5e46) | Jun 22, 2019 |
| HP            | Pavilion 15                 | Notebook    | [cc56a61ba6](https://linux-hardware.org/?probe=cc56a61ba6) | Jun 22, 2019 |
| Gigabyte      | X79-UD3                     | Desktop     | [be4bc12f99](https://linux-hardware.org/?probe=be4bc12f99) | Jun 22, 2019 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [eee7d322df](https://linux-hardware.org/?probe=eee7d322df) | Jun 22, 2019 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [44d558f4b2](https://linux-hardware.org/?probe=44d558f4b2) | Jun 22, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [db63ea2d00](https://linux-hardware.org/?probe=db63ea2d00) | Jun 19, 2019 |
| HP            | ProBook 6560b               | Notebook    | [6140d0688e](https://linux-hardware.org/?probe=6140d0688e) | Jun 19, 2019 |
| HP            | ProBook 6560b               | Notebook    | [8a19b4d629](https://linux-hardware.org/?probe=8a19b4d629) | Jun 19, 2019 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0f8766c667](https://linux-hardware.org/?probe=0f8766c667) | Jun 19, 2019 |
| Samsung       | 700G7C                      | Notebook    | [6e5c32f6b0](https://linux-hardware.org/?probe=6e5c32f6b0) | Jun 18, 2019 |
| TrekStor      | SurfTab wintron 7.0         | Tablet      | [9e530b2e21](https://linux-hardware.org/?probe=9e530b2e21) | Jun 18, 2019 |
| Dell          | 0TP412                      | Desktop     | [1df76bfec2](https://linux-hardware.org/?probe=1df76bfec2) | Jun 17, 2019 |
| HP            | ProBook 4720s               | Notebook    | [a6ec431460](https://linux-hardware.org/?probe=a6ec431460) | Jun 17, 2019 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [0805aa16d5](https://linux-hardware.org/?probe=0805aa16d5) | Jun 15, 2019 |
| Notebook      | MIM2300                     | Notebook    | [25be6b90ca](https://linux-hardware.org/?probe=25be6b90ca) | Jun 15, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [a659440214](https://linux-hardware.org/?probe=a659440214) | Jun 15, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c09ceb2357](https://linux-hardware.org/?probe=c09ceb2357) | Jun 15, 2019 |
| HP            | ProBook 4720s               | Notebook    | [b3e69d5f2c](https://linux-hardware.org/?probe=b3e69d5f2c) | Jun 13, 2019 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [5a50cfebf0](https://linux-hardware.org/?probe=5a50cfebf0) | Jun 12, 2019 |
| Dell          | 0J3C2F A00                  | Desktop     | [da636483fa](https://linux-hardware.org/?probe=da636483fa) | Jun 11, 2019 |
| MPMAN         | NT10                        | Notebook    | [30c34ab5a7](https://linux-hardware.org/?probe=30c34ab5a7) | Jun 08, 2019 |
| HP            | Unknown                     | Notebook    | [6ae9888758](https://linux-hardware.org/?probe=6ae9888758) | Jun 07, 2019 |
| Acer          | Extensa 5630                | Notebook    | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [6e27570ce5](https://linux-hardware.org/?probe=6e27570ce5) | Jun 04, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [1625938ff3](https://linux-hardware.org/?probe=1625938ff3) | Jun 03, 2019 |
| HP            | ProLiant DL360 G6           | Server      | [6806624961](https://linux-hardware.org/?probe=6806624961) | Jun 03, 2019 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [7347f3c28f](https://linux-hardware.org/?probe=7347f3c28f) | Jun 02, 2019 |
| Gigabyte      | H97-HD3                     | Desktop     | [8ebc1afd18](https://linux-hardware.org/?probe=8ebc1afd18) | Jun 02, 2019 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [38b85675b9](https://linux-hardware.org/?probe=38b85675b9) | May 30, 2019 |
| HP            | EliteBook 735 G5            | Notebook    | [607dee6bbb](https://linux-hardware.org/?probe=607dee6bbb) | May 30, 2019 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [30400d4387](https://linux-hardware.org/?probe=30400d4387) | May 30, 2019 |
| ASUSTek       | P6TD DELUXE                 | Desktop     | [a1d8e1026d](https://linux-hardware.org/?probe=a1d8e1026d) | May 25, 2019 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [7a608f78bf](https://linux-hardware.org/?probe=7a608f78bf) | May 24, 2019 |
| HP            | ProBook 4720s               | Notebook    | [4cfb07305a](https://linux-hardware.org/?probe=4cfb07305a) | May 24, 2019 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [81de1b6b7f](https://linux-hardware.org/?probe=81de1b6b7f) | May 20, 2019 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [539d35250d](https://linux-hardware.org/?probe=539d35250d) | May 20, 2019 |
| ASUSTek       | M4A77TD PRO                 | Desktop     | [3a9f87a529](https://linux-hardware.org/?probe=3a9f87a529) | May 12, 2019 |
| Apple         | MacBookPro6,2               | Notebook    | [1beb0f5895](https://linux-hardware.org/?probe=1beb0f5895) | May 12, 2019 |
| HP            | EliteBook 735 G5            | Notebook    | [c261abdcb2](https://linux-hardware.org/?probe=c261abdcb2) | May 11, 2019 |
| Apple         | MacBookPro6,2               | Notebook    | [7dcaaa0aba](https://linux-hardware.org/?probe=7dcaaa0aba) | May 10, 2019 |
| ASUSTek       | X550CA                      | Notebook    | [1bb7adda0a](https://linux-hardware.org/?probe=1bb7adda0a) | May 08, 2019 |
| Dell          | Latitude E7450              | Notebook    | [6c5f8e4975](https://linux-hardware.org/?probe=6c5f8e4975) | May 07, 2019 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [e313ef3c46](https://linux-hardware.org/?probe=e313ef3c46) | May 05, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [060bde41b0](https://linux-hardware.org/?probe=060bde41b0) | May 04, 2019 |
| HP            | 82F2                        | Desktop     | [d4dd63f262](https://linux-hardware.org/?probe=d4dd63f262) | May 04, 2019 |
| ASRock        | X470 Taichi                 | Desktop     | [f1cf09d00c](https://linux-hardware.org/?probe=f1cf09d00c) | May 01, 2019 |
| ASRock        | X470 Taichi                 | Desktop     | [9ec1e5626c](https://linux-hardware.org/?probe=9ec1e5626c) | May 01, 2019 |
| HP            | ProBook x360 440 G1         | Convertible | [a9baf3bf1b](https://linux-hardware.org/?probe=a9baf3bf1b) | Apr 30, 2019 |
| HP            | ProBook x360 440 G1         | Convertible | [e5da00d166](https://linux-hardware.org/?probe=e5da00d166) | Apr 30, 2019 |
| HP            | 18E7                        | Desktop     | [180a566e97](https://linux-hardware.org/?probe=180a566e97) | Apr 27, 2019 |
| HP            | 3395                        | All in one  | [68246e58c1](https://linux-hardware.org/?probe=68246e58c1) | Apr 26, 2019 |
| Toshiba       | Satellite C850D-102         | Notebook    | [1a0a4e8bcb](https://linux-hardware.org/?probe=1a0a4e8bcb) | Apr 25, 2019 |
| Medion        | S1219T MD99667              | Tablet      | [0995a2d2e4](https://linux-hardware.org/?probe=0995a2d2e4) | Apr 19, 2019 |
| Medion        | Akoya E7226                 | Notebook    | [79d0fc293a](https://linux-hardware.org/?probe=79d0fc293a) | Apr 14, 2019 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [01a6ccacea](https://linux-hardware.org/?probe=01a6ccacea) | Apr 13, 2019 |
| Apple         | Mac-F2218FC8                | All in one  | [1ccb72ad4c](https://linux-hardware.org/?probe=1ccb72ad4c) | Apr 13, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [59ca47d9e7](https://linux-hardware.org/?probe=59ca47d9e7) | Apr 12, 2019 |
| Acer          | Aspire TC-280               | Desktop     | [4f50aad112](https://linux-hardware.org/?probe=4f50aad112) | Apr 12, 2019 |
| Acer          | Aspire TC-280               | Desktop     | [d41d630ad6](https://linux-hardware.org/?probe=d41d630ad6) | Apr 12, 2019 |
| ASUSTek       | X540LA                      | Notebook    | [a75bac056c](https://linux-hardware.org/?probe=a75bac056c) | Apr 11, 2019 |
| ASUSTek       | X540LA                      | Notebook    | [b65a74387a](https://linux-hardware.org/?probe=b65a74387a) | Apr 10, 2019 |
| Acer          | Aspire one 1-431            | Notebook    | [c7647bf1c9](https://linux-hardware.org/?probe=c7647bf1c9) | Apr 09, 2019 |
| Dell          | Latitude E6520              | Notebook    | [8b18d510e6](https://linux-hardware.org/?probe=8b18d510e6) | Apr 09, 2019 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [f582fc7b09](https://linux-hardware.org/?probe=f582fc7b09) | Apr 09, 2019 |
| ASUSTek       | X540LA                      | Notebook    | [a4281ced7f](https://linux-hardware.org/?probe=a4281ced7f) | Apr 07, 2019 |
| HPE           | ProLiant MicroServer Gen... | Server      | [4b4029781f](https://linux-hardware.org/?probe=4b4029781f) | Apr 05, 2019 |
| Intel         | ChiefRiver                  | Desktop     | [084b561015](https://linux-hardware.org/?probe=084b561015) | Apr 05, 2019 |
| Lenovo        | ThinkPad T440s 20ARS0MG0... | Notebook    | [764e1505f9](https://linux-hardware.org/?probe=764e1505f9) | Mar 30, 2019 |
| ASRock        | H77M-ITX                    | Desktop     | [82b34d144d](https://linux-hardware.org/?probe=82b34d144d) | Mar 29, 2019 |
| HP            | Compaq 6910p                | Notebook    | [5ff034e324](https://linux-hardware.org/?probe=5ff034e324) | Mar 27, 2019 |
| HP            | Compaq 6910p                | Notebook    | [d4fd792576](https://linux-hardware.org/?probe=d4fd792576) | Mar 27, 2019 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [ebe0baee7f](https://linux-hardware.org/?probe=ebe0baee7f) | Mar 27, 2019 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [aa5d109b02](https://linux-hardware.org/?probe=aa5d109b02) | Mar 27, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [7e12226e95](https://linux-hardware.org/?probe=7e12226e95) | Mar 26, 2019 |
| Dell          | 0RF705                      | Desktop     | [5c49479ac2](https://linux-hardware.org/?probe=5c49479ac2) | Mar 20, 2019 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d315bc4d5f](https://linux-hardware.org/?probe=d315bc4d5f) | Mar 19, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [7e1c3bbf7f](https://linux-hardware.org/?probe=7e1c3bbf7f) | Mar 18, 2019 |
| HP            | 81C5 MVB                    | Desktop     | [46ea2e591e](https://linux-hardware.org/?probe=46ea2e591e) | Mar 18, 2019 |
| Acer          | Extensa 5620                | Notebook    | [13df1a9427](https://linux-hardware.org/?probe=13df1a9427) | Mar 16, 2019 |
| LG Electro... | 14ZD970-GX5SK               | Notebook    | [421a29844a](https://linux-hardware.org/?probe=421a29844a) | Mar 09, 2019 |
| MSI           | X299 RAIDER                 | Desktop     | [f06f57dde9](https://linux-hardware.org/?probe=f06f57dde9) | Mar 07, 2019 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [707b18aa4c](https://linux-hardware.org/?probe=707b18aa4c) | Feb 25, 2019 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [8e8cd1b9ef](https://linux-hardware.org/?probe=8e8cd1b9ef) | Feb 25, 2019 |
| HP            | 1496                        | Desktop     | [de9f0ead75](https://linux-hardware.org/?probe=de9f0ead75) | Feb 13, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [23c23d0963](https://linux-hardware.org/?probe=23c23d0963) | Feb 10, 2019 |
| Sony          | VPCCB3S1E                   | Notebook    | [1825e1aed8](https://linux-hardware.org/?probe=1825e1aed8) | Feb 06, 2019 |
| Dell          | 0WG855                      | Desktop     | [eb36bde92e](https://linux-hardware.org/?probe=eb36bde92e) | Jan 29, 2019 |
| HP            | 1496                        | Desktop     | [992a71a3d4](https://linux-hardware.org/?probe=992a71a3d4) | Jan 19, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [3faa4af120](https://linux-hardware.org/?probe=3faa4af120) | Jan 17, 2019 |
| HUAWEI        | MACH-WX9                    | Notebook    | [e91a9060a0](https://linux-hardware.org/?probe=e91a9060a0) | Jan 13, 2019 |
| TrekStor      | Primebook C13               | Convertible | [48e3cc8030](https://linux-hardware.org/?probe=48e3cc8030) | Dec 30, 2018 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [f69b762d01](https://linux-hardware.org/?probe=f69b762d01) | Dec 30, 2018 |
| Acer          | Extensa 5510                | Notebook    | [af4af03783](https://linux-hardware.org/?probe=af4af03783) | Dec 29, 2018 |
| HP            | Pavilion dv6                | Notebook    | [17f74b1c5e](https://linux-hardware.org/?probe=17f74b1c5e) | Dec 28, 2018 |
| HP            | Pavilion dv6                | Notebook    | [c296c8a5e5](https://linux-hardware.org/?probe=c296c8a5e5) | Dec 28, 2018 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1e7adbe67a](https://linux-hardware.org/?probe=1e7adbe67a) | Dec 26, 2018 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [a684d1aeea](https://linux-hardware.org/?probe=a684d1aeea) | Dec 26, 2018 |
| Toshiba       | Satellite R850              | Notebook    | [fb960a89a5](https://linux-hardware.org/?probe=fb960a89a5) | Dec 18, 2018 |
| Acer          | TravelMate B113             | Notebook    | [3a384dbaba](https://linux-hardware.org/?probe=3a384dbaba) | Dec 09, 2018 |
| HP            | 1496                        | Desktop     | [b2d0e4d272](https://linux-hardware.org/?probe=b2d0e4d272) | Dec 05, 2018 |
| HP            | 1496                        | Desktop     | [00359473e5](https://linux-hardware.org/?probe=00359473e5) | Dec 05, 2018 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [8c427755b7](https://linux-hardware.org/?probe=8c427755b7) | Nov 29, 2018 |
| Notebook      | MIM2300                     | Notebook    | [bb190776db](https://linux-hardware.org/?probe=bb190776db) | Nov 23, 2018 |
| Notebook      | MIM2300                     | Notebook    | [13f74d56de](https://linux-hardware.org/?probe=13f74d56de) | Nov 23, 2018 |
| Intel         | NUC5i7RYB H73774-104        | Mini pc     | [44caa27aad](https://linux-hardware.org/?probe=44caa27aad) | Nov 22, 2018 |
| Acer          | TravelMate B113             | Notebook    | [34b1209bb2](https://linux-hardware.org/?probe=34b1209bb2) | Nov 20, 2018 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8d29e7c679](https://linux-hardware.org/?probe=8d29e7c679) | Nov 20, 2018 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f3a757f578](https://linux-hardware.org/?probe=f3a757f578) | Nov 20, 2018 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [707960b3ec](https://linux-hardware.org/?probe=707960b3ec) | Nov 20, 2018 |
| ASUSTek       | 1015P                       | Notebook    | [58ce9d06ac](https://linux-hardware.org/?probe=58ce9d06ac) | Nov 17, 2018 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [5bfd55dd52](https://linux-hardware.org/?probe=5bfd55dd52) | Nov 16, 2018 |
| Dell          | Latitude E6520              | Notebook    | [8e5073fe38](https://linux-hardware.org/?probe=8e5073fe38) | Nov 16, 2018 |
| ASUSTek       | X553MA                      | Notebook    | [c3f51f2dbc](https://linux-hardware.org/?probe=c3f51f2dbc) | Nov 14, 2018 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [1a67024c19](https://linux-hardware.org/?probe=1a67024c19) | Nov 09, 2018 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [0616076476](https://linux-hardware.org/?probe=0616076476) | Nov 09, 2018 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [008dbc2e63](https://linux-hardware.org/?probe=008dbc2e63) | Nov 09, 2018 |
| Dell          | Latitude D810               | Notebook    | [01ec82b9fa](https://linux-hardware.org/?probe=01ec82b9fa) | Nov 07, 2018 |
| Acer          | Aspire 5253                 | Notebook    | [c49cd8e4e3](https://linux-hardware.org/?probe=c49cd8e4e3) | Nov 02, 2018 |
| Acer          | Aspire 5253                 | Notebook    | [2ff8269050](https://linux-hardware.org/?probe=2ff8269050) | Nov 02, 2018 |
| Sony          | SVE1511F4E                  | Notebook    | [1cbcf1ea17](https://linux-hardware.org/?probe=1cbcf1ea17) | Nov 01, 2018 |
| Sony          | SVE1511F4E                  | Notebook    | [14fa60ef8b](https://linux-hardware.org/?probe=14fa60ef8b) | Nov 01, 2018 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [1452de25da](https://linux-hardware.org/?probe=1452de25da) | Oct 31, 2018 |
| Medion        | X783X                       | Notebook    | [852662bdf3](https://linux-hardware.org/?probe=852662bdf3) | Oct 31, 2018 |
| ASRock        | H77M-ITX                    | Desktop     | [543d683992](https://linux-hardware.org/?probe=543d683992) | Oct 28, 2018 |
| ASUSTek       | X553MA                      | Notebook    | [b2a4f5cbe1](https://linux-hardware.org/?probe=b2a4f5cbe1) | Oct 28, 2018 |
| ASRock        | H77M-ITX                    | Desktop     | [5f140fc4e2](https://linux-hardware.org/?probe=5f140fc4e2) | Oct 25, 2018 |
| Acer          | Aspire E5-521               | Notebook    | [31181c5775](https://linux-hardware.org/?probe=31181c5775) | Oct 23, 2018 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [e480d824df](https://linux-hardware.org/?probe=e480d824df) | Sep 26, 2018 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [60aa838dba](https://linux-hardware.org/?probe=60aa838dba) | Jul 03, 2018 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [d3bf1c59ef](https://linux-hardware.org/?probe=d3bf1c59ef) | Jul 03, 2018 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [c4dfa88ac3](https://linux-hardware.org/?probe=c4dfa88ac3) | Jun 28, 2018 |
| Intel         | NUC5PGYB H78167-102         | Mini pc     | [5df12fb380](https://linux-hardware.org/?probe=5df12fb380) | Jun 22, 2018 |
| Supermicro    | X9DRW                       | Server      | [c293f8ae6e](https://linux-hardware.org/?probe=c293f8ae6e) | Jun 20, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [76e1d53b06](https://linux-hardware.org/?probe=76e1d53b06) | May 21, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [e046570d7f](https://linux-hardware.org/?probe=e046570d7f) | May 14, 2018 |
| ASRock        | H67DE3                      | Desktop     | [950456784f](https://linux-hardware.org/?probe=950456784f) | May 05, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [73b1be59e6](https://linux-hardware.org/?probe=73b1be59e6) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [7b5a78d2db](https://linux-hardware.org/?probe=7b5a78d2db) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [6d7db21504](https://linux-hardware.org/?probe=6d7db21504) | May 03, 2018 |
| Supermicro    | X8DTN+-F                    | Server      | [7e6e74a11d](https://linux-hardware.org/?probe=7e6e74a11d) | May 03, 2018 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [8505f4654f](https://linux-hardware.org/?probe=8505f4654f) | May 01, 2018 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [a5918b30a1](https://linux-hardware.org/?probe=a5918b30a1) | May 01, 2018 |
| Supermicro    | X10DRW-i                    | Server      | [37aec1e068](https://linux-hardware.org/?probe=37aec1e068) | Apr 25, 2018 |
| Supermicro    | X9DRW                       | Server      | [98ca4d1013](https://linux-hardware.org/?probe=98ca4d1013) | Apr 24, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d52d9fed5f](https://linux-hardware.org/?probe=d52d9fed5f) | Apr 24, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [6d6481cf9e](https://linux-hardware.org/?probe=6d6481cf9e) | Apr 24, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [18f679c146](https://linux-hardware.org/?probe=18f679c146) | Apr 23, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [e081575a40](https://linux-hardware.org/?probe=e081575a40) | Apr 23, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [5e5e82b2a5](https://linux-hardware.org/?probe=5e5e82b2a5) | Apr 23, 2018 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [db0943094c](https://linux-hardware.org/?probe=db0943094c) | Apr 20, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a579d177b4](https://linux-hardware.org/?probe=a579d177b4) | Apr 14, 2018 |
| Lenovo        | G570 20079                  | Notebook    | [d1bd6fb889](https://linux-hardware.org/?probe=d1bd6fb889) | Apr 14, 2018 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [4239e3e21c](https://linux-hardware.org/?probe=4239e3e21c) | Mar 14, 2018 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [35bb6fa5ff](https://linux-hardware.org/?probe=35bb6fa5ff) | Feb 28, 2018 |
| Acer          | Aspire A515-51              | Notebook    | [ce4d09bd98](https://linux-hardware.org/?probe=ce4d09bd98) | Feb 03, 2018 |
| ASUSTek       | N73Jn                       | Notebook    | [d97e769583](https://linux-hardware.org/?probe=d97e769583) | Jan 03, 2018 |
| ASUSTek       | N73Jn                       | Notebook    | [6f752ca5a9](https://linux-hardware.org/?probe=6f752ca5a9) | Dec 30, 2017 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1e5183425f](https://linux-hardware.org/?probe=1e5183425f) | Nov 30, 2017 |
| HP            | 3031h                       | Desktop     | [ced7c0313d](https://linux-hardware.org/?probe=ced7c0313d) | Nov 23, 2017 |
| Dell          | Latitude E6530              | Notebook    | [a53c93d7c1](https://linux-hardware.org/?probe=a53c93d7c1) | Nov 17, 2017 |
| Lenovo        | ThinkPad T420 4236ML1       | Notebook    | [8fa7c7d8e4](https://linux-hardware.org/?probe=8fa7c7d8e4) | Nov 05, 2017 |
| HP            | Pavilion dv6                | Notebook    | [68afe6213f](https://linux-hardware.org/?probe=68afe6213f) | Oct 17, 2017 |
| HP            | ENVY dv7                    | Notebook    | [903c2180a3](https://linux-hardware.org/?probe=903c2180a3) | Oct 04, 2017 |
| Dell          | Inspiron 1720               | Notebook    | [0db1f5a27a](https://linux-hardware.org/?probe=0db1f5a27a) | Sep 17, 2017 |
| Gigabyte      | B75M-D3H                    | Desktop     | [eb73aae971](https://linux-hardware.org/?probe=eb73aae971) | Sep 08, 2017 |
| HP            | ENVY Laptop 17-ae0xx        | Notebook    | [e116e381dd](https://linux-hardware.org/?probe=e116e381dd) | Aug 22, 2017 |
| HP            | ENVY Laptop 17-ae0xx        | Notebook    | [0fef681def](https://linux-hardware.org/?probe=0fef681def) | Aug 15, 2017 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [89bfa5602c](https://linux-hardware.org/?probe=89bfa5602c) | Jun 27, 2017 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [de22f8533f](https://linux-hardware.org/?probe=de22f8533f) | Jun 21, 2017 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [24c3f07e9c](https://linux-hardware.org/?probe=24c3f07e9c) | May 25, 2017 |
| Acer          | EG31M P01-A0                | Desktop     | [57daef5260](https://linux-hardware.org/?probe=57daef5260) | Apr 27, 2017 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [15125ef418](https://linux-hardware.org/?probe=15125ef418) | Mar 09, 2017 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [624ac7cb71](https://linux-hardware.org/?probe=624ac7cb71) | Mar 09, 2017 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [ce7cf807a6](https://linux-hardware.org/?probe=ce7cf807a6) | Mar 08, 2017 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [a356492026](https://linux-hardware.org/?probe=a356492026) | Mar 08, 2017 |
| Lenovo        | ThinkPad X230 2320LFG       | Notebook    | [64dd6b6919](https://linux-hardware.org/?probe=64dd6b6919) | Mar 07, 2017 |
| Dell          | Latitude E5550              | Notebook    | [b451c295b3](https://linux-hardware.org/?probe=b451c295b3) | Dec 31, 2016 |
| HP            | EliteBook 2540p             | Notebook    | [3d853c3fd8](https://linux-hardware.org/?probe=3d853c3fd8) | Dec 20, 2016 |
| HP            | EliteBook 2540p             | Notebook    | [c855dfd733](https://linux-hardware.org/?probe=c855dfd733) | Dec 19, 2016 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [ba3116d018](https://linux-hardware.org/?probe=ba3116d018) | Jul 27, 2016 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [3c1532db04](https://linux-hardware.org/?probe=3c1532db04) | Apr 12, 2016 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [85356dc9e2](https://linux-hardware.org/?probe=85356dc9e2) | Dec 03, 2015 |
| Lenovo        | G570 20079                  | Notebook    | [fc57cb086b](https://linux-hardware.org/?probe=fc57cb086b) | Nov 26, 2015 |
| Lenovo        | G570 20079                  | Notebook    | [2239d316e8](https://linux-hardware.org/?probe=2239d316e8) | Nov 26, 2015 |
| Lenovo        | G570 20079                  | Notebook    | [8c602f13e9](https://linux-hardware.org/?probe=8c602f13e9) | Nov 26, 2015 |
| HP            | ProLiant DL380e Gen8        | Server      | [3fac52af81](https://linux-hardware.org/?probe=3fac52af81) | Nov 25, 2015 |
| Lenovo        | G570 20079                  | Notebook    | [46ebaff7ec](https://linux-hardware.org/?probe=46ebaff7ec) | Nov 25, 2015 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 285       | 16.82%  |
| Ubuntu 18.04                 | 270       | 15.94%  |
| Debian 11                    | 54        | 3.19%   |
| Debian 10                    | 40        | 2.36%   |
| Ubuntu 21.10                 | 38        | 2.24%   |
| Linux Mint 20.2              | 35        | 2.07%   |
| Linux Mint 20.1              | 35        | 2.07%   |
| Linux Mint 20.3              | 33        | 1.95%   |
| KDE neon 20.04               | 30        | 1.77%   |
| OpenMandriva 4.2             | 29        | 1.71%   |
| Arch                         | 28        | 1.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 27        | 1.59%   |
| Ubuntu 20.10                 | 25        | 1.48%   |
| Fedora 32                    | 24        | 1.42%   |
| Ubuntu 21.04                 | 23        | 1.36%   |
| Ubuntu 19.10                 | 21        | 1.24%   |
| Pop!_OS 21.04                | 21        | 1.24%   |
| Pop!_OS 20.04                | 21        | 1.24%   |
| OpenMandriva 4.3             | 21        | 1.24%   |
| Fedora 33                    | 21        | 1.24%   |
| Ubuntu 19.04                 | 20        | 1.18%   |
| Fedora 34                    | 20        | 1.18%   |
| Pop!_OS 20.10                | 19        | 1.12%   |
| Fedora 35                    | 19        | 1.12%   |
| Linux Mint 19.3              | 18        | 1.06%   |
| Manjaro                      | 17        | 1%      |
| Arch Rolling                 | 17        | 1%      |
| ArcoLinux Rolling            | 16        | 0.94%   |
| Zorin 16                     | 15        | 0.89%   |
| Zorin 15                     | 15        | 0.89%   |
| Ubuntu 22.04                 | 15        | 0.89%   |
| Linux Mint 20                | 14        | 0.83%   |
| Kubuntu 20.04                | 14        | 0.83%   |
| Fedora 31                    | 13        | 0.77%   |
| Xubuntu 20.04                | 11        | 0.65%   |
| Debian Testing               | 11        | 0.65%   |
| Ubuntu MATE 20.04            | 10        | 0.59%   |
| ROSA R9                      | 9         | 0.53%   |
| Pop!_OS 22.04                | 9         | 0.53%   |
| Lubuntu 20.04                | 9         | 0.53%   |
| Fedora 36                    | 8         | 0.47%   |
| Ubuntu 18.10                 | 7         | 0.41%   |
| ROSA R10                     | 7         | 0.41%   |
| Pop!_OS 21.10                | 7         | 0.41%   |
| Linux Mint 19.1              | 7         | 0.41%   |
| Elementary 6.1               | 7         | 0.41%   |
| CentOS 7                     | 7         | 0.41%   |
| BlackPanther 18.1            | 7         | 0.41%   |
| Ubuntu 16.04                 | 6         | 0.35%   |
| LMDE 4                       | 6         | 0.35%   |
| Gentoo 2.7                   | 6         | 0.35%   |
| Gentoo 2.6                   | 6         | 0.35%   |
| Feren OS 18.04               | 6         | 0.35%   |
| Debian Unstable              | 6         | 0.35%   |
| Xubuntu 18.04                | 5         | 0.3%    |
| Manjaro 20.2                 | 5         | 0.3%    |
| Kubuntu 22.04                | 5         | 0.3%    |
| Kubuntu 21.10                | 5         | 0.3%    |
| Kubuntu 19.10                | 5         | 0.3%    |
| Ubuntu Budgie 20.04          | 4         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 669       | 42.37%  |
| Linux Mint    | 128       | 8.11%   |
| Debian        | 111       | 7.03%   |
| Fedora        | 99        | 6.27%   |
| Pop!_OS       | 72        | 4.56%   |
| OpenMandriva  | 55        | 3.48%   |
| Manjaro       | 50        | 3.17%   |
| Arch          | 44        | 2.79%   |
| openSUSE      | 34        | 2.15%   |
| Kubuntu       | 33        | 2.09%   |
| KDE neon      | 32        | 2.03%   |
| Zorin         | 30        | 1.9%    |
| ROSA          | 24        | 1.52%   |
| ArcoLinux     | 18        | 1.14%   |
| Xubuntu       | 16        | 1.01%   |
| Ubuntu MATE   | 15        | 0.95%   |
| Lubuntu       | 12        | 0.76%   |
| Gentoo        | 12        | 0.76%   |
| Elementary    | 11        | 0.7%    |
| Kali          | 10        | 0.63%   |
| CentOS        | 10        | 0.63%   |
| Feren OS      | 9         | 0.57%   |
| Clear Linux   | 8         | 0.51%   |
| Ubuntu Budgie | 7         | 0.44%   |
| Endless       | 7         | 0.44%   |
| BlackPanther  | 7         | 0.44%   |
| LMDE          | 6         | 0.38%   |
| EndeavourOS   | 5         | 0.32%   |
| MX            | 4         | 0.25%   |
| Artix         | 4         | 0.25%   |
| Void Linux    | 3         | 0.19%   |
| Virtuozzo     | 3         | 0.19%   |
| Solus         | 3         | 0.19%   |
| RHEL          | 3         | 0.19%   |
| NixOS         | 3         | 0.19%   |
| Q4OS          | 2         | 0.13%   |
| PCS           | 2         | 0.13%   |
| Manjaro-ARM   | 2         | 0.13%   |
| Android       | 2         | 0.13%   |
| Ubuntu Studio | 1         | 0.06%   |
| Sparky        | 1         | 0.06%   |
| Slackware     | 1         | 0.06%   |
| Reborn OS     | 1         | 0.06%   |
| Peppermint    | 1         | 0.06%   |
| Parrot        | 1         | 0.06%   |
| Makulu        | 1         | 0.06%   |
| KaOS          | 1         | 0.06%   |
| Kaisen        | 1         | 0.06%   |
| Guix          | 1         | 0.06%   |
| Garuda Linux  | 1         | 0.06%   |
| Devuan        | 1         | 0.06%   |
| ArchLabs      | 1         | 0.06%   |
| Alpine        | 1         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 2.3%    |
| 5.4.0-42-generic         | 32        | 1.67%   |
| 5.10.14-desktop-1omv4002 | 28        | 1.46%   |
| 4.15.0-91-generic        | 27        | 1.41%   |
| 5.4.0-52-generic         | 22        | 1.15%   |
| 5.4.0-48-generic         | 22        | 1.15%   |
| 4.15.0-96-generic        | 22        | 1.15%   |
| 5.4.0-58-generic         | 21        | 1.1%    |
| 5.16.7-desktop-1omv4003  | 20        | 1.04%   |
| 5.10.0-8-arm64           | 17        | 0.89%   |
| 5.8.0-43-generic         | 15        | 0.78%   |
| 5.4.0-91-generic         | 14        | 0.73%   |
| 5.13.0-35-generic        | 14        | 0.73%   |
| 5.4.0-80-generic         | 13        | 0.68%   |
| 5.4.0-26-generic         | 13        | 0.68%   |
| 5.11.0-43-generic        | 13        | 0.68%   |
| 5.11.0-27-generic        | 13        | 0.68%   |
| 5.4.0-81-generic         | 12        | 0.63%   |
| 5.4.0-47-generic         | 12        | 0.63%   |
| 5.13.0-30-generic        | 12        | 0.63%   |
| 5.10.0-8-amd64           | 12        | 0.63%   |
| 5.0.0-37-generic         | 12        | 0.63%   |
| 5.8.0-55-generic         | 11        | 0.57%   |
| 5.8.0-53-generic         | 11        | 0.57%   |
| 5.8.0-48-generic         | 11        | 0.57%   |
| 5.8.0-44-generic         | 11        | 0.57%   |
| 5.4.0-72-generic         | 11        | 0.57%   |
| 5.4.0-66-generic         | 11        | 0.57%   |
| 5.13.0-39-generic        | 11        | 0.57%   |
| 5.8.0-59-generic         | 10        | 0.52%   |
| 5.4.0-70-generic         | 10        | 0.52%   |
| 5.4.0-65-generic         | 10        | 0.52%   |
| 5.4.0-37-generic         | 10        | 0.52%   |
| 5.4.0-29-generic         | 10        | 0.52%   |
| 5.3.0-51-generic         | 10        | 0.52%   |
| 5.13.0-22-generic        | 10        | 0.52%   |
| 5.11.0-41-generic        | 10        | 0.52%   |
| 4.15.0-70-generic        | 10        | 0.52%   |
| 5.4.0-54-generic         | 9         | 0.47%   |
| 5.4.0-33-generic         | 9         | 0.47%   |
| 5.3.0-46-generic         | 9         | 0.47%   |
| 5.3.0-28-generic         | 9         | 0.47%   |
| 5.3.0-26-generic         | 9         | 0.47%   |
| 5.13.0-27-generic        | 9         | 0.47%   |
| 5.11.0-7620-generic      | 9         | 0.47%   |
| 5.11.0-40-generic        | 9         | 0.47%   |
| 5.11.0-37-generic        | 9         | 0.47%   |
| 4.15.0-76-generic        | 9         | 0.47%   |
| 5.4.0-7642-generic       | 8         | 0.42%   |
| 5.4.0-73-generic         | 8         | 0.42%   |
| 5.3.0-40-generic         | 8         | 0.42%   |
| 5.17.5-76051705-generic  | 8         | 0.42%   |
| 5.11.0-38-generic        | 8         | 0.42%   |
| 5.11.0-34-generic        | 8         | 0.42%   |
| 5.10.0-9-amd64           | 8         | 0.42%   |
| 4.19.0-13-amd64          | 8         | 0.42%   |
| 4.15.0-72-generic        | 8         | 0.42%   |
| 5.8.0-50-generic         | 7         | 0.37%   |
| 5.4.0-89-generic         | 7         | 0.37%   |
| 5.4.0-62-generic         | 7         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 351       | 19.76%  |
| 4.15.0  | 203       | 11.43%  |
| 5.8.0   | 127       | 7.15%   |
| 5.11.0  | 115       | 6.48%   |
| 5.13.0  | 99        | 5.57%   |
| 5.3.0   | 72        | 4.05%   |
| 5.10.0  | 61        | 3.43%   |
| 5.0.0   | 50        | 2.82%   |
| 4.18.0  | 39        | 2.2%    |
| 4.19.0  | 36        | 2.03%   |
| 5.15.0  | 33        | 1.86%   |
| 5.10.14 | 29        | 1.63%   |
| 5.16.7  | 21        | 1.18%   |
| 5.17.5  | 12        | 0.68%   |
| 5.6.0   | 11        | 0.62%   |
| 5.7.0   | 9         | 0.51%   |
| 5.14.0  | 9         | 0.51%   |
| 3.10.0  | 8         | 0.45%   |
| 5.10.7  | 7         | 0.39%   |
| 4.9.60  | 7         | 0.39%   |
| 5.6.14  | 6         | 0.34%   |
| 5.16.0  | 6         | 0.34%   |
| 4.18.16 | 6         | 0.34%   |
| 5.9.16  | 5         | 0.28%   |
| 5.9.11  | 5         | 0.28%   |
| 5.7.1   | 5         | 0.28%   |
| 5.6.15  | 5         | 0.28%   |
| 5.15.5  | 5         | 0.28%   |
| 5.14.14 | 5         | 0.28%   |
| 5.11.2  | 5         | 0.28%   |
| 5.11.16 | 5         | 0.28%   |
| 4.9.20  | 5         | 0.28%   |
| 5.9.8   | 4         | 0.23%   |
| 5.9.1   | 4         | 0.23%   |
| 5.9.0   | 4         | 0.23%   |
| 5.8.5   | 4         | 0.23%   |
| 5.8.16  | 4         | 0.23%   |
| 5.8.15  | 4         | 0.23%   |
| 5.7.8   | 4         | 0.23%   |
| 5.5.8   | 4         | 0.23%   |
| 5.3.18  | 4         | 0.23%   |
| 5.17.1  | 4         | 0.23%   |
| 5.16.18 | 4         | 0.23%   |
| 5.16.13 | 4         | 0.23%   |
| 5.16.11 | 4         | 0.23%   |
| 5.15.7  | 4         | 0.23%   |
| 5.13.6  | 4         | 0.23%   |
| 5.12.9  | 4         | 0.23%   |
| 5.12.13 | 4         | 0.23%   |
| 5.10.16 | 4         | 0.23%   |
| 5.10.12 | 4         | 0.23%   |
| 5.9.14  | 3         | 0.17%   |
| 5.8.4   | 3         | 0.17%   |
| 5.8.18  | 3         | 0.17%   |
| 5.8.11  | 3         | 0.17%   |
| 5.8.10  | 3         | 0.17%   |
| 5.7.7   | 3         | 0.17%   |
| 5.6.7   | 3         | 0.17%   |
| 5.6.6   | 3         | 0.17%   |
| 5.6.4   | 3         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 370       | 21.28%  |
| 4.15    | 204       | 11.73%  |
| 5.8     | 160       | 9.2%    |
| 5.11    | 144       | 8.28%   |
| 5.10    | 129       | 7.42%   |
| 5.13    | 116       | 6.67%   |
| 5.3     | 83        | 4.77%   |
| 5.15    | 68        | 3.91%   |
| 5.0     | 55        | 3.16%   |
| 5.16    | 51        | 2.93%   |
| 4.18    | 47        | 2.7%    |
| 4.19    | 43        | 2.47%   |
| 5.6     | 41        | 2.36%   |
| 5.17    | 32        | 1.84%   |
| 5.9     | 29        | 1.67%   |
| 5.7     | 29        | 1.67%   |
| 5.14    | 28        | 1.61%   |
| 5.12    | 25        | 1.44%   |
| 4.9     | 22        | 1.27%   |
| 5.5     | 11        | 0.63%   |
| 5.18    | 9         | 0.52%   |
| 3.10    | 8         | 0.46%   |
| 4.4     | 4         | 0.23%   |
| 4.14    | 4         | 0.23%   |
| 5.2     | 3         | 0.17%   |
| 4.20    | 3         | 0.17%   |
| 4.13    | 3         | 0.17%   |
| 4.1     | 3         | 0.17%   |
| 2.6     | 3         | 0.17%   |
| 4.10    | 2         | 0.12%   |
| 3.16    | 2         | 0.12%   |
| 5.1     | 1         | 0.06%   |
| 5       | 1         | 0.06%   |
| 4.2     | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.12    | 1         | 0.06%   |
| 3.4     | 1         | 0.06%   |
| 3.18    | 1         | 0.06%   |
| 3.17    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1456      | 95.73%  |
| aarch64 | 32        | 2.1%    |
| i686    | 31        | 2.04%   |
| armv8l  | 1         | 0.07%   |
| armv7l  | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 624       | 39%     |
| Unknown         | 280       | 17.5%   |
| KDE5            | 188       | 11.75%  |
| GNUstep         | 113       | 7.06%   |
| X-Cinnamon      | 101       | 6.31%   |
| XFCE            | 71        | 4.44%   |
| KDE             | 41        | 2.56%   |
| MATE            | 39        | 2.44%   |
| Cinnamon        | 30        | 1.88%   |
| LXQt            | 18        | 1.13%   |
| KDE4            | 16        | 1%      |
| Pantheon        | 12        | 0.75%   |
| Budgie          | 12        | 0.75%   |
| LXDE            | 11        | 0.69%   |
| i3              | 9         | 0.56%   |
| GNOME Flashback | 8         | 0.5%    |
| Unity           | 5         | 0.31%   |
| bspwm           | 5         | 0.31%   |
| qtile           | 3         | 0.19%   |
| Trinity         | 2         | 0.13%   |
| sway            | 2         | 0.13%   |
| GNOME Classic   | 2         | 0.13%   |
| DWM             | 2         | 0.13%   |
| xmonad          | 1         | 0.06%   |
| openbox         | 1         | 0.06%   |
| none+awesome    | 1         | 0.06%   |
| ICEWM           | 1         | 0.06%   |
| herbstluftwm    | 1         | 0.06%   |
| fluxbox         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1157      | 72.54%  |
| Wayland | 218       | 13.67%  |
| Unknown | 155       | 9.72%   |
| Tty     | 63        | 3.95%   |
| Web     | 2         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 773       | 48.4%   |
| LightDM | 258       | 16.16%  |
| GDM     | 212       | 13.27%  |
| SDDM    | 171       | 10.71%  |
| TDM     | 81        | 5.07%   |
| GDM3    | 79        | 4.95%   |
| KDM     | 15        | 0.94%   |
| XDM     | 4         | 0.25%   |
| SLiM    | 2         | 0.13%   |
| LXDM    | 1         | 0.06%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 477       | 30.23%  |
| de_CH      | 353       | 22.37%  |
| Unknown    | 345       | 21.86%  |
| fr_CH      | 104       | 6.59%   |
| de_DE      | 96        | 6.08%   |
| en_GB      | 64        | 4.06%   |
| C          | 34        | 2.15%   |
| fr_FR      | 26        | 1.65%   |
| pt_PT      | 16        | 1.01%   |
| it_CH      | 11        | 0.7%    |
| it_IT      | 9         | 0.57%   |
| pl_PL      | 6         | 0.38%   |
| es_ES      | 5         | 0.32%   |
| en_CH      | 5         | 0.32%   |
| ru_RU      | 3         | 0.19%   |
| POSIX      | 3         | 0.19%   |
| en_IE      | 3         | 0.19%   |
| en_AU      | 3         | 0.19%   |
| de_AT      | 3         | 0.19%   |
| en_CA      | 2         | 0.13%   |
| tr_TR      | 1         | 0.06%   |
| ru_UA      | 1         | 0.06%   |
| nl_BE      | 1         | 0.06%   |
| hu_HU      | 1         | 0.06%   |
| gsw_CH     | 1         | 0.06%   |
| de_IT      | 1         | 0.06%   |
| de_CH.UTF8 | 1         | 0.06%   |
| cs_CZ      | 1         | 0.06%   |
| ca_ES      | 1         | 0.06%   |
| C.UTF8     | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 817       | 52.88%  |
| BIOS | 728       | 47.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1254      | 80.64%  |
| Btrfs   | 103       | 6.62%   |
| Overlay | 77        | 4.95%   |
| Unknown | 64        | 4.12%   |
| Xfs     | 32        | 2.06%   |
| Zfs     | 10        | 0.64%   |
| Ext2    | 6         | 0.39%   |
| F2fs    | 3         | 0.19%   |
| Ext3    | 3         | 0.19%   |
| Jfs     | 1         | 0.06%   |
| ExX4    | 1         | 0.06%   |
| Aufs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 792       | 51.16%  |
| GPT     | 581       | 37.53%  |
| MBR     | 175       | 11.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1315      | 84.62%  |
| Yes       | 239       | 15.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1163      | 74.98%  |
| Yes       | 388       | 25.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 262       | 17.25%  |
| Hewlett-Packard         | 258       | 16.98%  |
| Lenovo                  | 224       | 14.75%  |
| Dell                    | 127       | 8.36%   |
| Acer                    | 83        | 5.46%   |
| Gigabyte Technology     | 75        | 4.94%   |
| Intel                   | 60        | 3.95%   |
| MSI                     | 53        | 3.49%   |
| ASRock                  | 52        | 3.42%   |
| Apple                   | 50        | 3.29%   |
| Fujitsu                 | 31        | 2.04%   |
| Raspberry Pi Foundation | 28        | 1.84%   |
| Medion                  | 20        | 1.32%   |
| Supermicro              | 18        | 1.18%   |
| Toshiba                 | 17        | 1.12%   |
| Sony                    | 12        | 0.79%   |
| Microsoft               | 11        | 0.72%   |
| TUXEDO                  | 9         | 0.59%   |
| Samsung Electronics     | 9         | 0.59%   |
| Unknown                 | 9         | 0.59%   |
| Shuttle                 | 8         | 0.53%   |
| Notebook                | 8         | 0.53%   |
| TrekStor                | 7         | 0.46%   |
| PC Engines              | 7         | 0.46%   |
| ZOTAC                   | 6         | 0.39%   |
| Razer                   | 6         | 0.39%   |
| Pegatron                | 6         | 0.39%   |
| HUAWEI                  | 6         | 0.39%   |
| DALCO AG Switzerland    | 6         | 0.39%   |
| Schenker                | 4         | 0.26%   |
| Packard Bell            | 3         | 0.2%    |
| Clevo                   | 3         | 0.2%    |
| whyopencomputing        | 2         | 0.13%   |
| PC Specialist           | 2         | 0.13%   |
| HPE                     | 2         | 0.13%   |
| Fujitsu Siemens         | 2         | 0.13%   |
| Biostar                 | 2         | 0.13%   |
| AMI                     | 2         | 0.13%   |
| Alienware               | 2         | 0.13%   |
| Timi                    | 1         | 0.07%   |
| System76                | 1         | 0.07%   |
| SLIMBOOK                | 1         | 0.07%   |
| Quanta                  | 1         | 0.07%   |
| Quanmax                 | 1         | 0.07%   |
| Purism                  | 1         | 0.07%   |
| Polaroid                | 1         | 0.07%   |
| Pine Microsystems       | 1         | 0.07%   |
| OriginPC                | 1         | 0.07%   |
| NF541                   | 1         | 0.07%   |
| MPMAN                   | 1         | 0.07%   |
| Minix                   | 1         | 0.07%   |
| LG Electronics          | 1         | 0.07%   |
| LattePanda              | 1         | 0.07%   |
| Kontron                 | 1         | 0.07%   |
| Kiano                   | 1         | 0.07%   |
| Khadas                  | 1         | 0.07%   |
| IGEL Technology         | 1         | 0.07%   |
| ICP / iEi               | 1         | 0.07%   |
| Hardkernel              | 1         | 0.07%   |
| Hampoo                  | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 27        | 1.78%   |
| Unknown                               | 14        | 0.92%   |
| Fujitsu CELSIUS_W550                  | 12        | 0.79%   |
| RPi Raspberry Pi 4 Model B Rev 1.2    | 9         | 0.59%   |
| RPi Raspberry Pi 4 Model B Rev 1.1    | 7         | 0.46%   |
| RPi Raspberry Pi 3 Model B Rev 1.2    | 7         | 0.46%   |
| ASUS STRIX Z270F GAMING               | 7         | 0.46%   |
| ASUS P9X79 WS                         | 7         | 0.46%   |
| DALCO AG Switzerland +41 44 908 38 38 | 6         | 0.39%   |
| ASUS ROG STRIX X570-E GAMING          | 6         | 0.39%   |
| ASUS P8Z77-V LX                       | 6         | 0.39%   |
| PC Engines APU2                       | 5         | 0.33%   |
| Microsoft Surface Pro 4               | 5         | 0.33%   |
| Intel DP67BA AAG10219-303             | 5         | 0.33%   |
| HP Pavilion dv7                       | 5         | 0.33%   |
| Dell XPS 15 9570                      | 5         | 0.33%   |
| Dell Latitude E7240                   | 5         | 0.33%   |
| Dell Latitude 7490                    | 5         | 0.33%   |
| ASUS ROG STRIX Z370-F GAMING          | 5         | 0.33%   |
| Supermicro X8DTN+-F                   | 4         | 0.26%   |
| MSI MS-7C02                           | 4         | 0.26%   |
| Lenovo MIIX 310-10ICR 80SG            | 4         | 0.26%   |
| Intel S4600LH                         | 4         | 0.26%   |
| Intel NUC8i7BEH                       | 4         | 0.26%   |
| Intel DP55WB AAE64798-207             | 4         | 0.26%   |
| HP Pavilion g7                        | 4         | 0.26%   |
| HP Pavilion dv6                       | 4         | 0.26%   |
| HP Notebook                           | 4         | 0.26%   |
| HP Laptop 15-bs1xx                    | 4         | 0.26%   |
| HP ENVY 15                            | 4         | 0.26%   |
| HP EliteDesk 800 G1 SFF               | 4         | 0.26%   |
| HP EliteBook Folio 1040 G1            | 4         | 0.26%   |
| Gigabyte X570 AORUS ELITE             | 4         | 0.26%   |
| Gigabyte H97-HD3                      | 4         | 0.26%   |
| Fujitsu CELSIUS W570                  | 4         | 0.26%   |
| Dell XPS 15 7590                      | 4         | 0.26%   |
| Dell OptiPlex 9020                    | 4         | 0.26%   |
| Dell OptiPlex 790                     | 4         | 0.26%   |
| ASUS PRIME Z370-A II                  | 4         | 0.26%   |
| Apple MacBookPro9,2                   | 4         | 0.26%   |
| Apple iMac8,1                         | 4         | 0.26%   |
| Apple iMac12,2                        | 4         | 0.26%   |
| Razer Blade                           | 3         | 0.2%    |
| MSI MS-7C56                           | 3         | 0.2%    |
| MSI MS-7971                           | 3         | 0.2%    |
| Lenovo Yoga 3 Pro-1370 80HE           | 3         | 0.2%    |
| HUAWEI MACH-WX9                       | 3         | 0.2%    |
| HP ProDesk 600 G1 TWR                 | 3         | 0.2%    |
| HP Pavilion g6                        | 3         | 0.2%    |
| HP Pavilion 15                        | 3         | 0.2%    |
| HP OMEN 30L Desktop GT13-0xxx         | 3         | 0.2%    |
| HP ENVY x360 Convertible 15-ee0xxx    | 3         | 0.2%    |
| HP ENVY dv7                           | 3         | 0.2%    |
| HP EliteDesk 800 G1 USDT              | 3         | 0.2%    |
| HP EliteBook 840 G6                   | 3         | 0.2%    |
| HP EliteBook 840 G5                   | 3         | 0.2%    |
| Gigabyte X570 AORUS PRO               | 3         | 0.2%    |
| Gigabyte X399 AORUS XTREME            | 3         | 0.2%    |
| Dell XPS 15 9560                      | 3         | 0.2%    |
| Dell XPS 13 7390                      | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 140       | 9.22%   |
| Acer Aspire              | 49        | 3.23%   |
| HP EliteBook             | 47        | 3.09%   |
| HP Pavilion              | 45        | 2.96%   |
| ASUS ROG                 | 41        | 2.7%    |
| Dell XPS                 | 37        | 2.44%   |
| Dell Latitude            | 36        | 2.37%   |
| RPi Raspberry            | 28        | 1.84%   |
| ASUS All                 | 27        | 1.78%   |
| ASUS PRIME               | 26        | 1.71%   |
| Fujitsu CELSIUS          | 25        | 1.65%   |
| Dell OptiPlex            | 25        | 1.65%   |
| HP ENVY                  | 24        | 1.58%   |
| Lenovo Yoga              | 23        | 1.51%   |
| HP ProBook               | 23        | 1.51%   |
| HP Compaq                | 22        | 1.45%   |
| HP EliteDesk             | 20        | 1.32%   |
| Lenovo IdeaPad           | 15        | 0.99%   |
| HP Laptop                | 15        | 0.99%   |
| Unknown                  | 14        | 0.92%   |
| Toshiba Satellite        | 11        | 0.72%   |
| Microsoft Surface        | 11        | 0.72%   |
| Dell Inspiron            | 11        | 0.72%   |
| ASUS VivoBook            | 11        | 0.72%   |
| Acer Swift               | 11        | 0.72%   |
| HP ZBook                 | 9         | 0.59%   |
| Gigabyte X570            | 9         | 0.59%   |
| Dell Precision           | 9         | 0.59%   |
| ASUS ZenBook             | 9         | 0.59%   |
| HP ProLiant              | 8         | 0.53%   |
| ASUS TUF                 | 8         | 0.53%   |
| ASUS STRIX               | 8         | 0.53%   |
| ASUS P9X79               | 8         | 0.53%   |
| HP ProDesk               | 7         | 0.46%   |
| ASUS P8Z77-V             | 7         | 0.46%   |
| Razer Blade              | 6         | 0.39%   |
| Lenovo ThinkCentre       | 6         | 0.39%   |
| Intel DP55WB             | 6         | 0.39%   |
| HP Spectre               | 6         | 0.39%   |
| HP OMEN                  | 6         | 0.39%   |
| DALCO AG Switzerland +41 | 6         | 0.39%   |
| ASRock X570              | 6         | 0.39%   |
| Apple iMac12             | 6         | 0.39%   |
| PC Engines APU2          | 5         | 0.33%   |
| Lenovo MIIX              | 5         | 0.33%   |
| Intel DP67BA             | 5         | 0.33%   |
| ASUS SABERTOOTH          | 5         | 0.33%   |
| Apple MacBookPro11       | 5         | 0.33%   |
| Supermicro X8DTN+-F      | 4         | 0.26%   |
| MSI MS-7C02              | 4         | 0.26%   |
| Lenovo IdeaPadFlex       | 4         | 0.26%   |
| Lenovo IdeaCentre        | 4         | 0.26%   |
| Intel S4600LH            | 4         | 0.26%   |
| Intel NUC8i7BEH          | 4         | 0.26%   |
| HP Notebook              | 4         | 0.26%   |
| Gigabyte H97-HD3         | 4         | 0.26%   |
| ASUS P8P67               | 4         | 0.26%   |
| ASRock B450              | 4         | 0.26%   |
| Apple MacBookPro9        | 4         | 0.26%   |
| Apple iMac8              | 4         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 174       | 11.45%  |
| 2019    | 166       | 10.93%  |
| 2017    | 137       | 9.02%   |
| 2012    | 129       | 8.49%   |
| 2020    | 127       | 8.36%   |
| 2014    | 104       | 6.85%   |
| 2011    | 104       | 6.85%   |
| 2013    | 98        | 6.45%   |
| 2015    | 97        | 6.39%   |
| 2016    | 73        | 4.81%   |
| 2021    | 68        | 4.48%   |
| 2010    | 68        | 4.48%   |
| 2008    | 50        | 3.29%   |
| 2009    | 43        | 2.83%   |
| 2007    | 27        | 1.78%   |
| Unknown | 27        | 1.78%   |
| 2006    | 14        | 0.92%   |
| 2005    | 6         | 0.39%   |
| 2022    | 3         | 0.2%    |
| 2004    | 3         | 0.2%    |
| 2003    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 680       | 44.77%  |
| Desktop        | 597       | 39.3%   |
| Convertible    | 73        | 4.81%   |
| Server         | 42        | 2.76%   |
| Mini pc        | 39        | 2.57%   |
| System on chip | 31        | 2.04%   |
| All in one     | 28        | 1.84%   |
| Tablet         | 26        | 1.71%   |
| Phone          | 3         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1397      | 91.01%  |
| Enabled  | 138       | 8.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1508      | 99.28%  |
| Yes  | 11        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 401       | 25.85%  |
| 4.01-8.0        | 270       | 17.41%  |
| 8.01-16.0       | 250       | 16.12%  |
| 32.01-64.0      | 224       | 14.44%  |
| 3.01-4.0        | 198       | 12.77%  |
| 64.01-256.0     | 82        | 5.29%   |
| 1.01-2.0        | 44        | 2.84%   |
| 24.01-32.0      | 30        | 1.93%   |
| 0.51-1.0        | 20        | 1.29%   |
| More than 256.0 | 18        | 1.16%   |
| 2.01-3.0        | 13        | 0.84%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 564       | 32.96%  |
| 2.01-3.0        | 379       | 22.15%  |
| 4.01-8.0        | 255       | 14.9%   |
| 3.01-4.0        | 196       | 11.46%  |
| 0.51-1.0        | 153       | 8.94%   |
| 8.01-16.0       | 88        | 5.14%   |
| 0.01-0.5        | 36        | 2.1%    |
| 16.01-24.0      | 14        | 0.82%   |
| 24.01-32.0      | 7         | 0.41%   |
| 64.01-256.0     | 7         | 0.41%   |
| 32.01-64.0      | 6         | 0.35%   |
| Unknown         | 4         | 0.23%   |
| More than 256.0 | 2         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 929       | 59.21%  |
| 2       | 377       | 24.03%  |
| 3       | 130       | 8.29%   |
| 4       | 48        | 3.06%   |
| 5       | 35        | 2.23%   |
| 0       | 18        | 1.15%   |
| 6       | 16        | 1.02%   |
| 7       | 13        | 0.83%   |
| 9       | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 955       | 62.26%  |
| Yes       | 579       | 37.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1315      | 85.89%  |
| No        | 216       | 14.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1053      | 68.91%  |
| No        | 475       | 31.09%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 859       | 55.85%  |
| No        | 679       | 44.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 1519      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 447       | 27.16%  |
| Bern                               | 85        | 5.16%   |
| Geneva                             | 50        | 3.04%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 2%      |
| Basel                              | 31        | 1.88%   |
| Lucerne                            | 30        | 1.82%   |
| Winterthur                         | 25        | 1.52%   |
| Neuchatel                          | 25        | 1.52%   |
| Thun                               | 23        | 1.4%    |
| Lausanne                           | 23        | 1.4%    |
| Lyss                               | 16        | 0.97%   |
| St. Gallen                         | 13        | 0.79%   |
| Herrliberg                         | 12        | 0.73%   |
| Dietikon                           | 12        | 0.73%   |
| Wil                                | 11        | 0.67%   |
| Wettingen                          | 11        | 0.67%   |
| Lugano                             | 11        | 0.67%   |
| Munchenstein                       | 10        | 0.61%   |
| Sion                               | 9         | 0.55%   |
| Oberwil-Lieli                      | 9         | 0.55%   |
| Dubendorf                          | 9         | 0.55%   |
| Burgdorf                           | 8         | 0.49%   |
| Bosingen                           | 8         | 0.49%   |
| Aarau                              | 8         | 0.49%   |
| Willisau                           | 7         | 0.43%   |
| Wetzikon                           | 7         | 0.43%   |
| Schaffhausen                       | 7         | 0.43%   |
| Le Mont-sur-Lausanne               | 7         | 0.43%   |
| Kloten                             | 7         | 0.43%   |
| Kilchberg                          | 7         | 0.43%   |
| Uster                              | 6         | 0.36%   |
| Schwarzenbach                      | 6         | 0.36%   |
| Riehen                             | 6         | 0.36%   |
| Onex                               | 6         | 0.36%   |
| Morges                             | 6         | 0.36%   |
| Bussigny                           | 6         | 0.36%   |
| Bulle                              | 6         | 0.36%   |
| Biel/Bienne                        | 6         | 0.36%   |
| Baden                              | 6         | 0.36%   |
| Baar                               | 6         | 0.36%   |
| Wettswil                           | 5         | 0.3%    |
| Prilly                             | 5         | 0.3%    |
| Oftringen                          | 5         | 0.3%    |
| Muttenz                            | 5         | 0.3%    |
| Meyrin                             | 5         | 0.3%    |
| Lenzburg                           | 5         | 0.3%    |
| Gerlafingen                        | 5         | 0.3%    |
| Frauenfeld                         | 5         | 0.3%    |
| Carouge                            | 5         | 0.3%    |
| Bulach                             | 5         | 0.3%    |
| Brugg                              | 5         | 0.3%    |
| Zug                                | 4         | 0.24%   |
| Yverdon-les-Bains                  | 4         | 0.24%   |
| Wohlen                             | 4         | 0.24%   |
| Wallisellen                        | 4         | 0.24%   |
| Vernier                            | 4         | 0.24%   |
| Therwil                            | 4         | 0.24%   |
| Spiegel BE                         | 4         | 0.24%   |
| Solothurn                          | 4         | 0.24%   |
| Rothenburg                         | 4         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 546       | 1004   | 25.32%  |
| WDC                       | 326       | 523    | 15.12%  |
| Seagate                   | 279       | 369    | 12.94%  |
| Toshiba                   | 114       | 154    | 5.29%   |
| Unknown                   | 107       | 162    | 4.96%   |
| SanDisk                   | 107       | 139    | 4.96%   |
| Intel                     | 107       | 149    | 4.96%   |
| Hitachi                   | 67        | 92     | 3.11%   |
| SK hynix                  | 58        | 69     | 2.69%   |
| Crucial                   | 58        | 85     | 2.69%   |
| Kingston                  | 55        | 84     | 2.55%   |
| Micron Technology         | 29        | 40     | 1.35%   |
| HGST                      | 23        | 29     | 1.07%   |
| Corsair                   | 23        | 28     | 1.07%   |
| Apple                     | 23        | 25     | 1.07%   |
| A-DATA Technology         | 20        | 32     | 0.93%   |
| OCZ                       | 18        | 23     | 0.83%   |
| Phison                    | 17        | 27     | 0.79%   |
| LITEON                    | 16        | 21     | 0.74%   |
| Transcend                 | 11        | 21     | 0.51%   |
| LITEONIT                  | 11        | 13     | 0.51%   |
| Intenso                   | 10        | 10     | 0.46%   |
| KIOXIA                    | 9         | 12     | 0.42%   |
| China                     | 8         | 9      | 0.37%   |
| ASMT                      | 8         | 13     | 0.37%   |
| KingSpec                  | 7         | 12     | 0.32%   |
| LaCie                     | 6         | 6      | 0.28%   |
| JMicron Technology        | 6         | 6      | 0.28%   |
| Hewlett-Packard           | 6         | 8      | 0.28%   |
| Silicon Motion            | 5         | 6      | 0.23%   |
| Fujitsu                   | 5         | 8      | 0.23%   |
| PNY                       | 4         | 9      | 0.19%   |
| Plextor                   | 4         | 4      | 0.19%   |
| Patriot                   | 4         | 5      | 0.19%   |
| Micron/Crucial Technology | 4         | 6      | 0.19%   |
| HPE                       | 4         | 9      | 0.19%   |
| SPCC                      | 3         | 3      | 0.14%   |
| Maxtor                    | 3         | 4      | 0.14%   |
| Lenovo                    | 3         | 3      | 0.14%   |
| XPG                       | 2         | 2      | 0.09%   |
| Realtek Semiconductor     | 2         | 3      | 0.09%   |
| Phison Electronics        | 2         | 8      | 0.09%   |
| Mushkin                   | 2         | 2      | 0.09%   |
| Lite-On                   | 2         | 2      | 0.09%   |
| Leven                     | 2         | 2      | 0.09%   |
| KingFast                  | 2         | 7      | 0.09%   |
| ASMedia                   | 2         | 2      | 0.09%   |
| Unknown                   | 2         | 2      | 0.09%   |
| USB3.0                    | 1         | 2      | 0.05%   |
| Unknown (CF)              | 1         | 1      | 0.05%   |
| SABRENT                   | 1         | 1      | 0.05%   |
| ROG                       | 1         | 1      | 0.05%   |
| Palit                     | 1         | 1      | 0.05%   |
| ORICO                     | 1         | 1      | 0.05%   |
| Netac                     | 1         | 1      | 0.05%   |
| MARVELL                   | 1         | 1      | 0.05%   |
| Kolink                    | 1         | 1      | 0.05%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.05%   |
| KingDian                  | 1         | 1      | 0.05%   |
| ICY BOX                   | 1         | 1      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB              | 32        | 1.32%   |
| Samsung SSD 850 EVO 250GB              | 28        | 1.16%   |
| Samsung SSD 860 EVO 1TB                | 27        | 1.12%   |
| Samsung SSD 860 EVO 500GB              | 25        | 1.03%   |
| Samsung NVMe SSD Drive 512GB           | 23        | 0.95%   |
| Samsung SSD 860 EVO 250GB              | 21        | 0.87%   |
| Samsung NVMe SSD Drive 1TB             | 18        | 0.74%   |
| Unknown MMC Card  32GB                 | 17        | 0.7%    |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 17        | 0.7%    |
| Seagate ST2000DM006-2DM164 2TB         | 16        | 0.66%   |
| SanDisk NVMe SSD Drive 512GB           | 14        | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB           | 14        | 0.58%   |
| Unknown MMC Card  64GB                 | 13        | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB         | 13        | 0.54%   |
| Seagate ST2000DM001-1ER164 2TB         | 13        | 0.54%   |
| Samsung NVMe SSD Drive 1024GB          | 13        | 0.54%   |
| Unknown MMC Card  128GB                | 12        | 0.5%    |
| SK hynix NVMe SSD Drive 512GB          | 11        | 0.45%   |
| Seagate Expansion 1TB                  | 11        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB         | 11        | 0.45%   |
| Samsung SSD 970 EVO 1TB                | 11        | 0.45%   |
| Samsung SSD 850 PRO 256GB              | 11        | 0.45%   |
| Samsung SSD 850 EVO 1TB                | 11        | 0.45%   |
| Samsung NVMe SSD Drive 256GB           | 11        | 0.45%   |
| HGST HTS721010A9E630 1TB               | 11        | 0.45%   |
| Samsung SSD 860 QVO 1TB                | 10        | 0.41%   |
| Samsung SSD 840 EVO 250GB              | 10        | 0.41%   |
| Samsung NVMe SSD Drive 2TB             | 10        | 0.41%   |
| Samsung HD103SJ 1TB                    | 10        | 0.41%   |
| Intel SSDPEKNW512G8H 512GB             | 10        | 0.41%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 9         | 0.37%   |
| Toshiba DT01ACA100 1TB                 | 9         | 0.37%   |
| Seagate ST1000LM048-2E7172 1TB         | 9         | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 9         | 0.37%   |
| Samsung SSD 970 EVO 500GB              | 9         | 0.37%   |
| Crucial CT1000MX500SSD1 1TB            | 9         | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 8         | 0.33%   |
| Unknown Y032V  32GB                    | 8         | 0.33%   |
| Toshiba NVMe SSD Drive 512GB           | 8         | 0.33%   |
| Seagate ST1000LM035-1RK172 1TB         | 8         | 0.33%   |
| Samsung SSD 970 PRO 512GB              | 8         | 0.33%   |
| Samsung SSD 970 EVO Plus 2TB           | 8         | 0.33%   |
| Samsung SSD 850 PRO 512GB              | 8         | 0.33%   |
| Samsung SSD 840 PRO Series 256GB       | 8         | 0.33%   |
| Samsung SSD 830 Series 128GB           | 8         | 0.33%   |
| Intel NVMe SSD Drive 512GB             | 8         | 0.33%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 7         | 0.29%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 7         | 0.29%   |
| WDC WD20EFRX-68EUZN0 2TB               | 7         | 0.29%   |
| Unknown SD/MMC/MS PRO 128GB            | 7         | 0.29%   |
| Toshiba MQ01ABD100 1TB                 | 7         | 0.29%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 7         | 0.29%   |
| Toshiba DT01ACA200 2TB                 | 7         | 0.29%   |
| Seagate ST4000DM004-2CV104 4TB         | 7         | 0.29%   |
| Seagate ST2000DM001-1CH164 2TB         | 7         | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB         | 7         | 0.29%   |
| Intel SSDPEKKW256G7 256GB              | 7         | 0.29%   |
| Intel NVMe SSD Drive 1024GB            | 7         | 0.29%   |
| Hitachi HUA722020ALA330 2TB            | 7         | 0.29%   |
| Crucial CT500MX500SSD1 500GB           | 7         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 269       | 353    | 36.35%  |
| WDC                 | 247       | 396    | 33.38%  |
| Hitachi             | 67        | 92     | 9.05%   |
| Toshiba             | 61        | 76     | 8.24%   |
| Samsung Electronics | 36        | 51     | 4.86%   |
| HGST                | 23        | 29     | 3.11%   |
| Unknown             | 8         | 9      | 1.08%   |
| Fujitsu             | 5         | 8      | 0.68%   |
| JMicron Technology  | 4         | 4      | 0.54%   |
| ASMT                | 4         | 6      | 0.54%   |
| Maxtor              | 3         | 4      | 0.41%   |
| Intenso             | 3         | 3      | 0.41%   |
| ASMedia             | 2         | 2      | 0.27%   |
| Unknown (CF)        | 1         | 1      | 0.14%   |
| MARVELL             | 1         | 1      | 0.14%   |
| ICY BOX             | 1         | 1      | 0.14%   |
| HPE                 | 1         | 2      | 0.14%   |
| Hewlett-Packard     | 1         | 2      | 0.14%   |
| ExcelStor           | 1         | 2      | 0.14%   |
| ASMT109x            | 1         | 1      | 0.14%   |
| Apple               | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 321       | 560    | 39.58%  |
| SanDisk             | 72        | 94     | 8.88%   |
| WDC                 | 54        | 72     | 6.66%   |
| Crucial             | 54        | 81     | 6.66%   |
| Intel               | 49        | 60     | 6.04%   |
| Kingston            | 41        | 67     | 5.06%   |
| Toshiba             | 22        | 32     | 2.71%   |
| Micron Technology   | 22        | 32     | 2.71%   |
| Apple               | 19        | 20     | 2.34%   |
| OCZ                 | 18        | 23     | 2.22%   |
| SK hynix            | 16        | 18     | 1.97%   |
| LITEON              | 16        | 21     | 1.97%   |
| A-DATA Technology   | 13        | 22     | 1.6%    |
| Corsair             | 12        | 13     | 1.48%   |
| Transcend           | 11        | 21     | 1.36%   |
| LITEONIT            | 11        | 13     | 1.36%   |
| China               | 8         | 9      | 0.99%   |
| KingSpec            | 7         | 12     | 0.86%   |
| Intenso             | 6         | 6      | 0.74%   |
| Plextor             | 4         | 4      | 0.49%   |
| Patriot             | 4         | 5      | 0.49%   |
| Seagate             | 3         | 3      | 0.37%   |
| ASMT                | 3         | 6      | 0.37%   |
| SPCC                | 2         | 2      | 0.25%   |
| PNY                 | 2         | 3      | 0.25%   |
| Mushkin             | 2         | 2      | 0.25%   |
| Hewlett-Packard     | 2         | 3      | 0.25%   |
| USB3.0              | 1         | 2      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |
| Phison              | 1         | 3      | 0.12%   |
| Palit               | 1         | 1      | 0.12%   |
| ORICO               | 1         | 1      | 0.12%   |
| Netac               | 1         | 1      | 0.12%   |
| Leven               | 1         | 1      | 0.12%   |
| Kolink              | 1         | 1      | 0.12%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.12%   |
| KingDian            | 1         | 1      | 0.12%   |
| HPE                 | 1         | 1      | 0.12%   |
| FORESEE             | 1         | 1      | 0.12%   |
| Dogfish             | 1         | 1      | 0.12%   |
| CT2000BX            | 1         | 1      | 0.12%   |
| BIWIN               | 1         | 1      | 0.12%   |
| Apacer              | 1         | 2      | 0.12%   |
| Advantech           | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 717       | 1225   | 36.08%  |
| HDD     | 637       | 1044   | 32.06%  |
| NVMe    | 506       | 813    | 25.47%  |
| MMC     | 100       | 155    | 5.03%   |
| Unknown | 27        | 42     | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1073      | 2193   | 60.76%  |
| NVMe | 505       | 812    | 28.6%   |
| MMC  | 100       | 155    | 5.66%   |
| SAS  | 88        | 119    | 4.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 746       | 1194   | 51.81%  |
| 0.51-1.0   | 400       | 636    | 27.78%  |
| 1.01-2.0   | 168       | 250    | 11.67%  |
| 3.01-4.0   | 47        | 77     | 3.26%   |
| 2.01-3.0   | 42        | 62     | 2.92%   |
| 4.01-10.0  | 31        | 40     | 2.15%   |
| 10.01-20.0 | 6         | 10     | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 379       | 23.28%  |
| 251-500        | 312       | 19.16%  |
| 501-1000       | 237       | 14.56%  |
| 1001-2000      | 166       | 10.2%   |
| 1-20           | 113       | 6.94%   |
| More than 3000 | 111       | 6.82%   |
| 51-100         | 86        | 5.28%   |
| 2001-3000      | 82        | 5.04%   |
| Unknown        | 75        | 4.61%   |
| 21-50          | 67        | 4.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 596       | 35.18%  |
| 21-50          | 217       | 12.81%  |
| 101-250        | 203       | 11.98%  |
| 51-100         | 195       | 11.51%  |
| 251-500        | 141       | 8.32%   |
| 501-1000       | 116       | 6.85%   |
| 1001-2000      | 81        | 4.78%   |
| Unknown        | 75        | 4.43%   |
| More than 3000 | 45        | 2.66%   |
| 2001-3000      | 25        | 1.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB                 | 2         | 2      | 1.92%   |
| Seagate ST9320325AS 320GB                    | 2         | 2      | 1.92%   |
| Seagate ST3250310AS 250GB                    | 2         | 2      | 1.92%   |
| Seagate ST31500341AS 1TB                     | 2         | 4      | 1.92%   |
| Hitachi HUA722020ALA330 2TB                  | 2         | 2      | 1.92%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD             | 1         | 1      | 0.96%   |
| WDC WD5000AAKS-65A7B0 500GB                  | 1         | 1      | 0.96%   |
| WDC WD5000AAKS-00E4A0 500GB                  | 1         | 1      | 0.96%   |
| WDC WD40EZRZ-00WN9B0 4TB                     | 1         | 1      | 0.96%   |
| WDC WD3200AAKS-00B3A0 320GB                  | 1         | 1      | 0.96%   |
| WDC WD3200AAJS-40VWA1 320GB                  | 1         | 1      | 0.96%   |
| WDC WD30EZRX-00D8PB0 3TB                     | 1         | 1      | 0.96%   |
| WDC WD2502ABYS-01B7A0 256GB                  | 1         | 1      | 0.96%   |
| WDC WD20EZRZ-00Z5HB0 2TB                     | 1         | 1      | 0.96%   |
| WDC WD20EZRX-00D8PB0 2TB                     | 1         | 2      | 0.96%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1         | 1      | 0.96%   |
| WDC WD1600BEKT-60A25T1 160GB                 | 1         | 1      | 0.96%   |
| WDC WD10EZEX-08M2NA0 1TB                     | 1         | 1      | 0.96%   |
| WDC WD10EARS-00Y5B1 1TB                      | 1         | 1      | 0.96%   |
| WDC WD10EADS-22M2B0 1TB                      | 1         | 1      | 0.96%   |
| WDC WD10EADS-00L5B1 1TB                      | 1         | 1      | 0.96%   |
| WDC WD1001FALS-403AA0 1TB                    | 1         | 1      | 0.96%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 0.96%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 0.96%   |
| Toshiba MQ01ABD075 752GB                     | 1         | 1      | 0.96%   |
| Toshiba MK7575GSX 752GB                      | 1         | 3      | 0.96%   |
| Toshiba MK1652GSX 160GB                      | 1         | 1      | 0.96%   |
| Toshiba DT01ACA100 1TB                       | 1         | 1      | 0.96%   |
| SK hynix SC401 SATA 512GB SSD                | 1         | 2      | 0.96%   |
| SK hynix SC210 mSATA 256GB SSD               | 1         | 1      | 0.96%   |
| SK hynix HFS256G39TND-N210A 256GB SSD        | 1         | 1      | 0.96%   |
| SK hynix HFS256G32MND-2200A 256GB SSD        | 1         | 1      | 0.96%   |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 1      | 0.96%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB      | 1         | 1      | 0.96%   |
| Seagate ST9500420AS 500GB                    | 1         | 2      | 0.96%   |
| Seagate ST9500325ASG 500GB                   | 1         | 1      | 0.96%   |
| Seagate ST9120822AS 120GB                    | 1         | 1      | 0.96%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 0.96%   |
| Seagate ST5000NM0024-1HT170 5TB              | 1         | 2      | 0.96%   |
| Seagate ST3500413AS 500GB                    | 1         | 2      | 0.96%   |
| Seagate ST31000528AS 1TB                     | 1         | 1      | 0.96%   |
| Seagate ST3000DM001-9YN166 3TB               | 1         | 1      | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1      | 0.96%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 2      | 0.96%   |
| Seagate ST2000DM001-1CH164 2TB               | 1         | 1      | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 0.96%   |
| SanDisk SD8SN8U-512G-1006 512GB SSD          | 1         | 1      | 0.96%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD          | 1         | 1      | 0.96%   |
| SanDisk SD7SB3Q256G1002 256GB SSD            | 1         | 2      | 0.96%   |
| SanDisk SD6SF1M128G1022I 128GB SSD           | 1         | 1      | 0.96%   |
| Samsung Electronics SSD 970 PRO 512GB        | 1         | 1      | 0.96%   |
| Samsung Electronics SSD 970 EVO 500GB        | 1         | 1      | 0.96%   |
| Samsung Electronics SSD 870 EVO 2TB          | 1         | 1      | 0.96%   |
| Samsung Electronics SSD 860 EVO M.2 1TB      | 1         | 1      | 0.96%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 1      | 0.96%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 3      | 0.96%   |
| Samsung Electronics HM500JI 500GB            | 1         | 1      | 0.96%   |
| Samsung Electronics HM121HI 120GB            | 1         | 1      | 0.96%   |
| Samsung Electronics HD502IJ 500GB            | 1         | 1      | 0.96%   |
| Samsung Electronics HD204UI 2TB              | 1         | 1      | 0.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 20     | 18.45%  |
| Seagate             | 17        | 24     | 16.5%   |
| Samsung Electronics | 11        | 13     | 10.68%  |
| Hitachi             | 9         | 9      | 8.74%   |
| Intel               | 7         | 8      | 6.8%    |
| Toshiba             | 6         | 8      | 5.83%   |
| SK hynix            | 6         | 7      | 5.83%   |
| Kingston            | 5         | 6      | 4.85%   |
| SanDisk             | 4         | 5      | 3.88%   |
| HGST                | 4         | 4      | 3.88%   |
| OCZ                 | 3         | 4      | 2.91%   |
| Micron Technology   | 3         | 3      | 2.91%   |
| A-DATA Technology   | 3         | 5      | 2.91%   |
| Crucial             | 2         | 2      | 1.94%   |
| Patriot             | 1         | 2      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| Intenso             | 1         | 1      | 0.97%   |
| ASMedia             | 1         | 1      | 0.97%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 30%     |
| Seagate             | 17        | 24     | 28.33%  |
| Hitachi             | 9         | 9      | 15%     |
| Toshiba             | 6         | 8      | 10%     |
| Samsung Electronics | 5         | 5      | 8.33%   |
| HGST                | 4         | 4      | 6.67%   |
| ASMedia             | 1         | 1      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 70     | 55.67%  |
| SSD  | 38        | 47     | 39.18%  |
| NVMe | 5         | 6      | 5.15%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 864       | 1786   | 52.78%  |
| Works    | 680       | 1369   | 41.54%  |
| Malfunc  | 92        | 123    | 5.62%   |
| Failed   | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 1053      | 54.03%  |
| Samsung Electronics          | 250       | 12.83%  |
| AMD                          | 221       | 11.34%  |
| SanDisk                      | 63        | 3.23%   |
| ASMedia Technology           | 53        | 2.72%   |
| Marvell Technology Group     | 47        | 2.41%   |
| SK hynix                     | 38        | 1.95%   |
| Toshiba America Info Systems | 35        | 1.8%    |
| Phison Electronics           | 28        | 1.44%   |
| Nvidia                       | 22        | 1.13%   |
| JMicron Technology           | 22        | 1.13%   |
| Kingston Technology Company  | 17        | 0.87%   |
| Areca Technology             | 13        | 0.67%   |
| LSI Logic / Symbios Logic    | 12        | 0.62%   |
| Silicon Motion               | 10        | 0.51%   |
| KIOXIA                       | 9         | 0.46%   |
| Seagate Technology           | 8         | 0.41%   |
| Micron Technology            | 8         | 0.41%   |
| Hewlett-Packard              | 7         | 0.36%   |
| ADATA Technology             | 7         | 0.36%   |
| Micron/Crucial Technology    | 6         | 0.31%   |
| Broadcom / LSI               | 4         | 0.21%   |
| VIA Technologies             | 3         | 0.15%   |
| Realtek Semiconductor        | 3         | 0.15%   |
| Lite-On Technology           | 3         | 0.15%   |
| Lenovo                       | 3         | 0.15%   |
| Apple                        | 2         | 0.1%    |
| Tekram Technology            | 1         | 0.05%   |
| Adaptec                      | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 157       | 7.04%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 155       | 6.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 80        | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 71        | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 68        | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 54        | 2.42%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 49        | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 48        | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 47        | 2.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 44        | 1.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 41        | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 40        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 38        | 1.7%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 37        | 1.66%   |
| Intel SATA Controller [RAID mode]                                                | 32        | 1.44%   |
| AMD 400 Series Chipset SATA Controller                                           | 31        | 1.39%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 29        | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 28        | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                              | 28        | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 27        | 1.21%   |
| Intel SSD 660P Series                                                            | 26        | 1.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 24        | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 23        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 21        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 21        | 0.94%   |
| Samsung NVMe SSD Controller 980                                                  | 19        | 0.85%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 19        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 18        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17        | 0.76%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 16        | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 0.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 16        | 0.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 15        | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 15        | 0.67%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 15        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 15        | 0.67%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 14        | 0.63%   |
| Phison E12 NVMe Controller                                                       | 13        | 0.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 13        | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 13        | 0.58%   |
| AMD 300 Series Chipset SATA Controller                                           | 13        | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 12        | 0.54%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 12        | 0.54%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 12        | 0.54%   |
| SK hynix Non-Volatile memory controller                                          | 11        | 0.49%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 11        | 0.49%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo            | 11        | 0.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 0.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 11        | 0.49%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 10        | 0.45%   |
| JMicron JMB363 SATA/IDE Controller                                               | 10        | 0.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 10        | 0.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.45%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 10        | 0.45%   |
| Areca ARC-188x series PCIe 2.0/3.0 to SAS/SATA 6/12Gb RAID Controller            | 10        | 0.45%   |
| AMD X370 Series Chipset SATA Controller                                          | 10        | 0.45%   |
| AMD 500 Series Chipset SATA Controller                                           | 10        | 0.45%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 9         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1077      | 55.98%  |
| NVMe | 510       | 26.51%  |
| IDE  | 170       | 8.84%   |
| RAID | 150       | 7.8%    |
| SAS  | 16        | 0.83%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1217      | 80.12%  |
| AMD          | 266       | 17.51%  |
| ARM          | 32        | 2.11%   |
| QUALCOMM     | 2         | 0.13%   |
| CentaurHauls | 2         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 38        | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz          | 36        | 2.37%   |
| ARM Processor                              | 32        | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 24        | 1.58%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 20        | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 19        | 1.25%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 18        | 1.18%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 17        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 15        | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 14        | 0.92%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 14        | 0.92%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 14        | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 13        | 0.86%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 13        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.79%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 12        | 0.79%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 12        | 0.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 12        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 12        | 0.79%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 11        | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor          | 11        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 10        | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 9         | 0.59%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 9         | 0.59%   |
| Intel Core i7-3770K CPU @ 3.50GHz          | 9         | 0.59%   |
| Intel Core i5-6500 CPU @ 3.20GHz           | 9         | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 9         | 0.59%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 9         | 0.59%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 9         | 0.59%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 9         | 0.59%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 9         | 0.59%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 8         | 0.53%   |
| Intel Core i7-3610QM CPU @ 2.30GHz         | 8         | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 8         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 8         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 8         | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 8         | 0.53%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz        | 7         | 0.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 7         | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 7         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 7         | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz          | 7         | 0.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 7         | 0.46%   |
| Intel Core i5 CPU 760 @ 2.80GHz            | 7         | 0.46%   |
| Intel Celeron N4000 CPU @ 1.10GHz          | 7         | 0.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 7         | 0.46%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 7         | 0.46%   |
| AMD Quad-Core Opteron Processor 2354       | 7         | 0.46%   |
| AMD GX-412TC SOC                           | 7         | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 6         | 0.39%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 6         | 0.39%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 6         | 0.39%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz         | 6         | 0.39%   |
| Intel Core i7-4510U CPU @ 2.00GHz          | 6         | 0.39%   |
| Intel Core i7-4500U CPU @ 1.80GHz          | 6         | 0.39%   |
| Intel Core i7-2620M CPU @ 2.70GHz          | 6         | 0.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz          | 6         | 0.39%   |
| AMD Ryzen 5 4500U with Radeon Graphics     | 6         | 0.39%   |
| Intel Xeon CPU X5650 @ 2.67GHz             | 5         | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 541       | 35.62%  |
| Intel Core i5           | 300       | 19.75%  |
| Other                   | 82        | 5.4%    |
| Intel Xeon              | 63        | 4.15%   |
| AMD Ryzen 7             | 60        | 3.95%   |
| AMD Ryzen 5             | 57        | 3.75%   |
| Intel Core 2 Duo        | 55        | 3.62%   |
| Intel Core i3           | 43        | 2.83%   |
| Intel Celeron           | 39        | 2.57%   |
| Intel Atom              | 26        | 1.71%   |
| Intel Pentium           | 24        | 1.58%   |
| AMD Ryzen 9             | 21        | 1.38%   |
| Intel Core i9           | 16        | 1.05%   |
| AMD FX                  | 14        | 0.92%   |
| Intel Core 2            | 13        | 0.86%   |
| Intel Core 2 Quad       | 12        | 0.79%   |
| AMD Ryzen Threadripper  | 11        | 0.72%   |
| Intel Pentium Dual-Core | 10        | 0.66%   |
| AMD Ryzen 7 PRO         | 10        | 0.66%   |
| AMD Ryzen 3             | 9         | 0.59%   |
| AMD Quad-Core Opteron   | 8         | 0.53%   |
| AMD GX                  | 7         | 0.46%   |
| Intel Xeon Gold         | 6         | 0.39%   |
| AMD A8                  | 6         | 0.39%   |
| AMD Opteron             | 5         | 0.33%   |
| AMD EPYC                | 5         | 0.33%   |
| AMD E                   | 5         | 0.33%   |
| AMD Athlon              | 5         | 0.33%   |
| Intel Pentium 4         | 4         | 0.26%   |
| AMD Phenom II X6        | 4         | 0.26%   |
| AMD Phenom II X4        | 4         | 0.26%   |
| AMD A10                 | 4         | 0.26%   |
| Intel Pentium Silver    | 3         | 0.2%    |
| Intel Pentium M         | 3         | 0.2%    |
| Intel Genuine           | 3         | 0.2%    |
| Intel Core M            | 3         | 0.2%    |
| AMD Ryzen 5 PRO         | 3         | 0.2%    |
| AMD E2                  | 3         | 0.2%    |
| AMD E1                  | 3         | 0.2%    |
| Intel Core m3           | 2         | 0.13%   |
| AMD Phenom II           | 2         | 0.13%   |
| AMD C-50                | 2         | 0.13%   |
| AMD Athlon II X2        | 2         | 0.13%   |
| AMD Athlon 64 X2        | 2         | 0.13%   |
| AMD A6                  | 2         | 0.13%   |
| AMD A4                  | 2         | 0.13%   |
| QUALCOMM AArch64        | 1         | 0.07%   |
| Intel Pentium Gold      | 1         | 0.07%   |
| Intel Pentium Dual      | 1         | 0.07%   |
| Intel Core Duo          | 1         | 0.07%   |
| Intel Celeron M         | 1         | 0.07%   |
| Intel Celeron Dual-Core | 1         | 0.07%   |
| CentaurHauls VIA Eden   | 1         | 0.07%   |
| CentaurHauls VIA C7     | 1         | 0.07%   |
| AMD Turion 64 X2 Mobile | 1         | 0.07%   |
| AMD Turion 64 Mobile    | 1         | 0.07%   |
| AMD Phenom              | 1         | 0.07%   |
| AMD C-60                | 1         | 0.07%   |
| AMD Athlon II X4        | 1         | 0.07%   |
| AMD Athlon Dual Core    | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 686       | 45.1%   |
| 2       | 440       | 28.93%  |
| 6       | 163       | 10.72%  |
| 8       | 125       | 8.22%   |
| 12      | 27        | 1.78%   |
| 1       | 20        | 1.31%   |
| 16      | 18        | 1.18%   |
| 32      | 7         | 0.46%   |
| 24      | 6         | 0.39%   |
| 10      | 6         | 0.39%   |
| Unknown | 6         | 0.39%   |
| 40      | 4         | 0.26%   |
| 3       | 4         | 0.26%   |
| 128     | 3         | 0.2%    |
| 48      | 3         | 0.2%    |
| 20      | 1         | 0.07%   |
| 18      | 1         | 0.07%   |
| 14      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1465      | 96.38%  |
| 2       | 41        | 2.7%    |
| 4       | 10        | 0.66%   |
| Unknown | 4         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1076      | 70.46%  |
| 1       | 445       | 29.14%  |
| Unknown | 6         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1481      | 97.11%  |
| Unknown        | 31        | 2.03%   |
| 32-bit         | 12        | 0.79%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 288       | 18.43%  |
| 0x306a9    | 105       | 6.72%   |
| 0x206a7    | 87        | 5.57%   |
| 0x306c3    | 82        | 5.25%   |
| 0x806ea    | 68        | 4.35%   |
| 0x906ea    | 59        | 3.77%   |
| 0x506e3    | 50        | 3.2%    |
| 0x40651    | 47        | 3.01%   |
| 0x1067a    | 44        | 2.82%   |
| 0x806ec    | 42        | 2.69%   |
| 0x806e9    | 39        | 2.5%    |
| 0x806c1    | 31        | 1.98%   |
| 0x906e9    | 29        | 1.86%   |
| 0x306d4    | 27        | 1.73%   |
| 0x406e3    | 22        | 1.41%   |
| 0x08701021 | 21        | 1.34%   |
| 0x30678    | 18        | 1.15%   |
| 0x20655    | 18        | 1.15%   |
| 0x806eb    | 15        | 0.96%   |
| 0x706e5    | 15        | 0.96%   |
| 0x10676    | 15        | 0.96%   |
| 0x206d7    | 14        | 0.9%    |
| 0x0800820d | 14        | 0.9%    |
| 0xa0655    | 13        | 0.83%   |
| 0xa0652    | 13        | 0.83%   |
| 0x50654    | 12        | 0.77%   |
| 0x20652    | 12        | 0.77%   |
| 0x706a1    | 11        | 0.7%    |
| 0x6fd      | 11        | 0.7%    |
| 0x406c4    | 11        | 0.7%    |
| 0x306e4    | 11        | 0.7%    |
| 0x0a50000c | 11        | 0.7%    |
| 0x08701013 | 11        | 0.7%    |
| 0x906ed    | 10        | 0.64%   |
| 0x306f2    | 10        | 0.64%   |
| 0x206c2    | 9         | 0.58%   |
| 0x106e5    | 9         | 0.58%   |
| 0x08600106 | 9         | 0.58%   |
| 0x08600103 | 9         | 0.58%   |
| 0x06000852 | 9         | 0.58%   |
| 0x506c9    | 8         | 0.51%   |
| 0x106a5    | 8         | 0.51%   |
| 0x08001138 | 8         | 0.51%   |
| 0x01000083 | 8         | 0.51%   |
| 0x6f6      | 7         | 0.45%   |
| 0x07030105 | 7         | 0.45%   |
| 0x010000c8 | 7         | 0.45%   |
| 0xa0653    | 6         | 0.38%   |
| 0x0a201009 | 6         | 0.38%   |
| 0x08108109 | 6         | 0.38%   |
| 0x0700010f | 6         | 0.38%   |
| 0x05000119 | 6         | 0.38%   |
| 0x0a201016 | 5         | 0.32%   |
| 0x08608103 | 5         | 0.32%   |
| 0x0810100b | 5         | 0.32%   |
| 0x08001137 | 5         | 0.32%   |
| 0x08600104 | 4         | 0.26%   |
| 0x08108102 | 4         | 0.26%   |
| 0x08101016 | 4         | 0.26%   |
| 0x06001119 | 4         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 322       | 21.18%  |
| Haswell          | 165       | 10.86%  |
| IvyBridge        | 132       | 8.68%   |
| SandyBridge      | 117       | 7.7%    |
| Skylake          | 103       | 6.78%   |
| Zen 2            | 76        | 5%      |
| Penryn           | 66        | 4.34%   |
| Unknown          | 54        | 3.55%   |
| Westmere         | 44        | 2.89%   |
| Silvermont       | 38        | 2.5%    |
| CometLake        | 38        | 2.5%    |
| TigerLake        | 36        | 2.37%   |
| Broadwell        | 34        | 2.24%   |
| Zen+             | 32        | 2.11%   |
| Zen              | 31        | 2.04%   |
| Core             | 31        | 2.04%   |
| Zen 3            | 30        | 1.97%   |
| K10              | 23        | 1.51%   |
| Nehalem          | 22        | 1.45%   |
| Piledriver       | 18        | 1.18%   |
| IceLake          | 17        | 1.12%   |
| Goldmont plus    | 15        | 0.99%   |
| Goldmont         | 11        | 0.72%   |
| Bobcat           | 11        | 0.72%   |
| Puma             | 10        | 0.66%   |
| K8 Hammer        | 7         | 0.46%   |
| Jaguar           | 7         | 0.46%   |
| P6               | 6         | 0.39%   |
| Excavator        | 5         | 0.33%   |
| Bonnell          | 5         | 0.33%   |
| NetBurst         | 4         | 0.26%   |
| K10 Llano        | 3         | 0.2%    |
| Alderlake Hybrid | 3         | 0.2%    |
| Steamroller      | 2         | 0.13%   |
| Bulldozer        | 2         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 846       | 49.02%  |
| Nvidia                                       | 529       | 30.65%  |
| AMD                                          | 300       | 17.38%  |
| Matrox Electronics Systems                   | 28        | 1.62%   |
| ASPEED Technology                            | 12        | 0.7%    |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.52%   |
| VIA Technologies                             | 2         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 70        | 3.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 3.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 63        | 3.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 52        | 2.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 2.96%   |
| Intel HD Graphics 620                                                                    | 38        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 36        | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 1.77%   |
| Intel HD Graphics 530                                                                    | 30        | 1.71%   |
| AMD Renoir                                                                               | 29        | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 27        | 1.54%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 1.2%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.14%   |
| Intel HD Graphics 630                                                                    | 18        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.03%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.97%   |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.86%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 0.86%   |
| AMD Cezanne                                                                              | 14        | 0.8%    |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 13        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 12        | 0.68%   |
| Intel Iris Plus Graphics G7                                                              | 12        | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.68%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 12        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 11        | 0.63%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.63%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 10        | 0.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 0.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 0.57%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 10        | 0.57%   |
| XGI Technology (eXtreme Graphics Innovation) Z7/Z9 (XG20 core)                           | 9         | 0.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.51%   |
| Intel HD Graphics 500                                                                    | 9         | 0.51%   |
| AMD Lucienne                                                                             | 9         | 0.51%   |
| Nvidia GP107GL [Quadro P400]                                                             | 8         | 0.46%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.46%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 8         | 0.46%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 8         | 0.46%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 8         | 0.46%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 7         | 0.4%    |
| Nvidia GP102 [TITAN Xp]                                                                  | 7         | 0.4%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 7         | 0.4%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 7         | 0.4%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 7         | 0.4%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 0.4%    |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 6         | 0.34%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.34%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 6         | 0.34%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 6         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 622       | 40.63%  |
| 1 x Nvidia               | 339       | 22.14%  |
| 1 x AMD                  | 254       | 16.59%  |
| Intel + Nvidia           | 174       | 11.37%  |
| Other                    | 43        | 2.81%   |
| Intel + AMD              | 28        | 1.83%   |
| 1 x Matrox               | 26        | 1.7%    |
| 1 x XGI                  | 9         | 0.59%   |
| 2 x AMD                  | 8         | 0.52%   |
| 1 x ASPEED               | 8         | 0.52%   |
| AMD + Nvidia             | 8         | 0.52%   |
| Nvidia + ASPEED          | 4         | 0.26%   |
| 2 x Nvidia               | 3         | 0.2%    |
| 1 x VIA                  | 2         | 0.13%   |
| Nvidia + Matrox          | 1         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.07%   |
| AMD + Matrox             | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1125      | 73.34%  |
| Proprietary | 314       | 20.47%  |
| Unknown     | 95        | 6.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 808       | 51.93%  |
| 1.01-2.0   | 213       | 13.69%  |
| 0.01-0.5   | 151       | 9.7%    |
| 3.01-4.0   | 118       | 7.58%   |
| 0.51-1.0   | 110       | 7.07%   |
| 7.01-8.0   | 68        | 4.37%   |
| 8.01-16.0  | 50        | 3.21%   |
| 5.01-6.0   | 29        | 1.86%   |
| 2.01-3.0   | 8         | 0.51%   |
| 4.01-5.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 223       | 13.56%  |
| AU Optronics            | 176       | 10.71%  |
| LG Display              | 153       | 9.31%   |
| Dell                    | 111       | 6.75%   |
| Chimei Innolux          | 92        | 5.6%    |
| Acer                    | 85        | 5.17%   |
| Hewlett-Packard         | 82        | 4.99%   |
| BOE                     | 74        | 4.5%    |
| Philips                 | 71        | 4.32%   |
| Apple                   | 60        | 3.65%   |
| BenQ                    | 53        | 3.22%   |
| Ancor Communications    | 50        | 3.04%   |
| Sharp                   | 44        | 2.68%   |
| Lenovo                  | 41        | 2.49%   |
| Goldstar                | 38        | 2.31%   |
| AOC                     | 36        | 2.19%   |
| Eizo                    | 27        | 1.64%   |
| Unknown                 | 19        | 1.16%   |
| Chi Mei Optoelectronics | 18        | 1.09%   |
| Sony                    | 17        | 1.03%   |
| InfoVision              | 15        | 0.91%   |
| ASUSTek Computer        | 15        | 0.91%   |
| Iiyama                  | 11        | 0.67%   |
| NEC Computers           | 10        | 0.61%   |
| Panasonic               | 8         | 0.49%   |
| CSO                     | 8         | 0.49%   |
| Toshiba                 | 7         | 0.43%   |
| PANDA                   | 6         | 0.36%   |
| Medion                  | 6         | 0.36%   |
| ViewSonic               | 5         | 0.3%    |
| Vestel Elektronik       | 5         | 0.3%    |
| LG Electronics          | 5         | 0.3%    |
| LG Philips              | 4         | 0.24%   |
| AUS                     | 4         | 0.24%   |
| ___                     | 3         | 0.18%   |
| MSI                     | 3         | 0.18%   |
| Gigabyte Technology     | 3         | 0.18%   |
| Belinea                 | 3         | 0.18%   |
| Onkyo                   | 2         | 0.12%   |
| Nvidia                  | 2         | 0.12%   |
| LGD                     | 2         | 0.12%   |
| JDI                     | 2         | 0.12%   |
| Idek Iiyama             | 2         | 0.12%   |
| HPN                     | 2         | 0.12%   |
| HannStar                | 2         | 0.12%   |
| Fujitsu Siemens         | 2         | 0.12%   |
| Denver                  | 2         | 0.12%   |
| DENON                   | 2         | 0.12%   |
| Compal                  | 2         | 0.12%   |
| CHD                     | 2         | 0.12%   |
| Yamaha                  | 1         | 0.06%   |
| Wacom                   | 1         | 0.06%   |
| VMO                     | 1         | 0.06%   |
| VFV                     | 1         | 0.06%   |
| Vestel                  | 1         | 0.06%   |
| USR                     | 1         | 0.06%   |
| Tianma XM               | 1         | 0.06%   |
| RS                      | 1         | 0.06%   |
| Packard Bell            | 1         | 0.06%   |
| Optoma                  | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 10        | 0.58%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                    | 9         | 0.52%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                   | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch       | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 7         | 0.4%    |
| Philips LCD Monitor PHL 272S4L 2560x1440                               | 6         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 6         | 0.35%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                       | 6         | 0.35%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                          | 5         | 0.29%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 5         | 0.29%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 5         | 0.29%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch       | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 5         | 0.29%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 4         | 0.23%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch      | 4         | 0.23%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 4         | 0.23%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch     | 4         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 4         | 0.23%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 4         | 0.23%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch           | 4         | 0.23%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch               | 4         | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 4         | 0.23%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch           | 4         | 0.23%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch           | 4         | 0.23%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 4         | 0.23%   |
| Dell LCD Monitor P2719H 3840x1080                                      | 4         | 0.23%   |
| Dell LCD Monitor P2719H                                                | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch       | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch       | 4         | 0.23%   |
| BOE LCD Monitor BOE07C8 3840x2160 309x174mm 14.0-inch                  | 4         | 0.23%   |
| BOE LCD Monitor BOE06EE 1920x1080 309x173mm 13.9-inch                  | 4         | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                  | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch         | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 4         | 0.23%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                       | 4         | 0.23%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch       | 4         | 0.23%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 600x340mm 27.2-inch  | 4         | 0.23%   |
| Acer X223HQ ACR0098 1920x1080 470x270mm 21.3-inch                      | 4         | 0.23%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 3         | 0.17%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                | 3         | 0.17%   |
| Sharp HDMI SHP1022 1920x1080 820x460mm 37.0-inch                       | 3         | 0.17%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch      | 3         | 0.17%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch      | 3         | 0.17%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch      | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SyncMaster 1600x1200                   | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SMS24A450 1920x1200                    | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SMS24A450                              | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch  | 3         | 0.17%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 1020x570mm 46.0-inch | 3         | 0.17%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 3         | 0.17%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 3         | 0.17%   |
| Philips 220SW PHL086F 1680x1050 474x296mm 22.0-inch                    | 3         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 666       | 41.94%  |
| 3840x2160 (4K)     | 131       | 8.25%   |
| 2560x1440 (QHD)    | 122       | 7.68%   |
| 1366x768 (WXGA)    | 120       | 7.56%   |
| 1920x1200 (WUXGA)  | 76        | 4.79%   |
| 1600x900 (HD+)     | 63        | 3.97%   |
| 1680x1050 (WSXGA+) | 53        | 3.34%   |
| Unknown            | 50        | 3.15%   |
| 1280x1024 (SXGA)   | 49        | 3.09%   |
| 1280x800 (WXGA)    | 31        | 1.95%   |
| 3440x1440          | 25        | 1.57%   |
| 1440x900 (WXGA+)   | 25        | 1.57%   |
| 3840x1080          | 19        | 1.2%    |
| 1600x1200          | 17        | 1.07%   |
| 2560x1600          | 14        | 0.88%   |
| 3200x1800 (QHD+)   | 11        | 0.69%   |
| 2880x1800          | 9         | 0.57%   |
| 2560x1080          | 8         | 0.5%    |
| 1024x768 (XGA)     | 7         | 0.44%   |
| 3840x1200          | 6         | 0.38%   |
| 3000x2000          | 6         | 0.38%   |
| 2736x1824          | 6         | 0.38%   |
| 1920x540           | 6         | 0.38%   |
| 1360x768           | 6         | 0.38%   |
| 4480x1440          | 5         | 0.31%   |
| 3840x1600          | 5         | 0.31%   |
| 1024x600           | 5         | 0.31%   |
| 3840x2400          | 4         | 0.25%   |
| 3520x1200          | 3         | 0.19%   |
| 3360x1050          | 3         | 0.19%   |
| 2160x1440          | 3         | 0.19%   |
| 2048x1152          | 3         | 0.19%   |
| 7680x2160          | 2         | 0.13%   |
| 6400x1440          | 2         | 0.13%   |
| 5120x1440          | 2         | 0.13%   |
| 3840x1100          | 2         | 0.13%   |
| 2560x1024          | 2         | 0.13%   |
| 2288x1287          | 2         | 0.13%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 5440x1080          | 1         | 0.06%   |
| 5348x1080          | 1         | 0.06%   |
| 3968x1200          | 1         | 0.06%   |
| 3600x1200          | 1         | 0.06%   |
| 3286x1080          | 1         | 0.06%   |
| 3200x1080          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 2880x1920          | 1         | 0.06%   |
| 2880x1200          | 1         | 0.06%   |
| 2160x1350          | 1         | 0.06%   |
| 1920x515           | 1         | 0.06%   |
| 1800x1200          | 1         | 0.06%   |
| 1400x1050          | 1         | 0.06%   |
| 1280x960           | 1         | 0.06%   |
| 1280x768           | 1         | 0.06%   |
| 1280x720 (HD)      | 1         | 0.06%   |
| 10240x2160         | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 309       | 18.95%  |
| 27      | 171       | 10.48%  |
| Unknown | 154       | 9.44%   |
| 13      | 141       | 8.65%   |
| 24      | 137       | 8.4%    |
| 14      | 120       | 7.36%   |
| 17      | 99        | 6.07%   |
| 23      | 91        | 5.58%   |
| 21      | 66        | 4.05%   |
| 31      | 46        | 2.82%   |
| 12      | 46        | 2.82%   |
| 19      | 30        | 1.84%   |
| 34      | 26        | 1.59%   |
| 22      | 25        | 1.53%   |
| 20      | 24        | 1.47%   |
| 32      | 16        | 0.98%   |
| 84      | 12        | 0.74%   |
| 72      | 10        | 0.61%   |
| 33      | 10        | 0.61%   |
| 25      | 10        | 0.61%   |
| 11      | 9         | 0.55%   |
| 46      | 7         | 0.43%   |
| 37      | 7         | 0.43%   |
| 54      | 6         | 0.37%   |
| 40      | 6         | 0.37%   |
| 29      | 6         | 0.37%   |
| 18      | 6         | 0.37%   |
| 10      | 5         | 0.31%   |
| 55      | 4         | 0.25%   |
| 49      | 4         | 0.25%   |
| 48      | 4         | 0.25%   |
| 28      | 4         | 0.25%   |
| 26      | 4         | 0.25%   |
| 16      | 4         | 0.25%   |
| 142     | 2         | 0.12%   |
| 74      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 59      | 1         | 0.06%   |
| 50      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 30      | 1         | 0.06%   |
| 9       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 483       | 30.17%  |
| 501-600        | 372       | 23.24%  |
| Unknown        | 154       | 9.62%   |
| 201-300        | 152       | 9.49%   |
| 401-500        | 123       | 7.68%   |
| 351-400        | 123       | 7.68%   |
| 601-700        | 71        | 4.43%   |
| 701-800        | 52        | 3.25%   |
| 1001-1500      | 28        | 1.75%   |
| 1501-2000      | 23        | 1.44%   |
| 801-900        | 15        | 0.94%   |
| More than 2000 | 2         | 0.12%   |
| 901-1000       | 2         | 0.12%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 995       | 68.06%  |
| 16/10   | 194       | 13.27%  |
| Unknown | 140       | 9.58%   |
| 5/4     | 42        | 2.87%   |
| 21/9    | 34        | 2.33%   |
| 4/3     | 20        | 1.37%   |
| 3/2     | 20        | 1.37%   |
| 32/9    | 7         | 0.48%   |
| 6/5     | 3         | 0.21%   |
| 1.00    | 3         | 0.21%   |
| 3.40    | 2         | 0.14%   |
| 3.73    | 1         | 0.07%   |
| 2.50    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 308       | 19.11%  |
| 201-250        | 229       | 14.21%  |
| 81-90          | 177       | 10.98%  |
| 301-350        | 173       | 10.73%  |
| Unknown        | 154       | 9.55%   |
| 351-500        | 108       | 6.7%    |
| 71-80          | 81        | 5.02%   |
| 121-130        | 77        | 4.78%   |
| 251-300        | 75        | 4.65%   |
| 151-200        | 70        | 4.34%   |
| 61-70          | 44        | 2.73%   |
| More than 1000 | 41        | 2.54%   |
| 501-1000       | 27        | 1.67%   |
| 141-150        | 15        | 0.93%   |
| 51-60          | 11        | 0.68%   |
| 131-140        | 10        | 0.62%   |
| 41-50          | 5         | 0.31%   |
| 111-120        | 3         | 0.19%   |
| 91-100         | 3         | 0.19%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 479       | 30.55%  |
| 121-160       | 412       | 26.28%  |
| 101-120       | 306       | 19.52%  |
| Unknown       | 154       | 9.82%   |
| 161-240       | 106       | 6.76%   |
| More than 240 | 71        | 4.53%   |
| 1-50          | 40        | 2.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1132      | 72.47%  |
| 2     | 268       | 17.16%  |
| 0     | 122       | 7.81%   |
| 3     | 39        | 2.5%    |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 936       | 42.16%  |
| Realtek Semiconductor             | 600       | 27.03%  |
| Qualcomm Atheros                  | 172       | 7.75%   |
| Broadcom                          | 132       | 5.95%   |
| Broadcom Limited                  | 34        | 1.53%   |
| Marvell Technology Group          | 30        | 1.35%   |
| Ralink                            | 29        | 1.31%   |
| Lenovo                            | 20        | 0.9%    |
| Aquantia                          | 20        | 0.9%    |
| Nvidia                            | 16        | 0.72%   |
| Ralink Technology                 | 15        | 0.68%   |
| ASIX Electronics                  | 15        | 0.68%   |
| Sierra Wireless                   | 14        | 0.63%   |
| MediaTek                          | 14        | 0.63%   |
| Huawei Technologies               | 12        | 0.54%   |
| Samsung Electronics               | 11        | 0.5%    |
| Hewlett-Packard                   | 11        | 0.5%    |
| Edimax Technology                 | 10        | 0.45%   |
| Dell                              | 10        | 0.45%   |
| Microchip Technology              | 9         | 0.41%   |
| Ericsson Business Mobile Networks | 9         | 0.41%   |
| DisplayLink                       | 9         | 0.41%   |
| TP-Link                           | 8         | 0.36%   |
| NetGear                           | 8         | 0.36%   |
| D-Link                            | 7         | 0.32%   |
| ASUSTek Computer                  | 6         | 0.27%   |
| Fibocom                           | 5         | 0.23%   |
| Microsoft                         | 4         | 0.18%   |
| AVM                               | 4         | 0.18%   |
| Xiaomi                            | 3         | 0.14%   |
| Wilocity                          | 3         | 0.14%   |
| NetXen Incorporated               | 3         | 0.14%   |
| Linksys                           | 3         | 0.14%   |
| ICS Advent                        | 3         | 0.14%   |
| D-Link System                     | 3         | 0.14%   |
| Qualcomm                          | 2         | 0.09%   |
| Micro Star International          | 2         | 0.09%   |
| Mellanox Technologies             | 2         | 0.09%   |
| IMC Networks                      | 2         | 0.09%   |
| Arduino SA                        | 2         | 0.09%   |
| ZEPHYR                            | 1         | 0.05%   |
| Team Xecuter                      | 1         | 0.05%   |
| Standard Microsystems             | 1         | 0.05%   |
| SEGGER                            | 1         | 0.05%   |
| Qualcomm Atheros Communications   | 1         | 0.05%   |
| Philips (or NXP)                  | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.05%   |
| Novatek Microelectronics          | 1         | 0.05%   |
| Netopia                           | 1         | 0.05%   |
| Netchip Technology                | 1         | 0.05%   |
| MosChip Semiconductor             | 1         | 0.05%   |
| JMicron Technology                | 1         | 0.05%   |
| Intersil                          | 1         | 0.05%   |
| Holtek Semiconductor              | 1         | 0.05%   |
| HMD Global                        | 1         | 0.05%   |
| Gemtek                            | 1         | 0.05%   |
| Exar                              | 1         | 0.05%   |
| Cypress Semiconductor             | 1         | 0.05%   |
| Apple                             | 1         | 0.05%   |
| AMD                               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 435       | 16.43%  |
| Intel Wi-Fi 6 AX200                                               | 100       | 3.78%   |
| Intel Wireless 8265 / 8275                                        | 77        | 2.91%   |
| Intel I211 Gigabit Network Connection                             | 66        | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64        | 2.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1.93%   |
| Intel Wireless 7260                                               | 42        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 1.44%   |
| Intel Wireless 7265                                               | 36        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 33        | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 1.21%   |
| Intel 82579V Gigabit Network Connection                           | 31        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 27        | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 26        | 0.98%   |
| Intel Wireless 8260                                               | 25        | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 23        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 21        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 21        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 20        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 0.72%   |
| Intel Wireless 3165                                               | 19        | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 0.68%   |
| Intel I350 Gigabit Network Connection                             | 18        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.64%   |
| Intel Wireless-AC 9260                                            | 16        | 0.6%    |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 16        | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 14        | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 14        | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 13        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 12        | 0.45%   |
| Intel Centrino Advanced-N 6235                                    | 11        | 0.42%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.34%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 8         | 0.3%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 8         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 615       | 55.41%  |
| Qualcomm Atheros                      | 141       | 12.7%   |
| Realtek Semiconductor                 | 110       | 9.91%   |
| Broadcom                              | 72        | 6.49%   |
| Ralink                                | 29        | 2.61%   |
| Broadcom Limited                      | 20        | 1.8%    |
| Ralink Technology                     | 15        | 1.35%   |
| Sierra Wireless                       | 14        | 1.26%   |
| MediaTek                              | 11        | 0.99%   |
| Edimax Technology                     | 10        | 0.9%    |
| Marvell Technology Group              | 8         | 0.72%   |
| TP-Link                               | 7         | 0.63%   |
| NetGear                               | 7         | 0.63%   |
| Dell                                  | 6         | 0.54%   |
| D-Link                                | 6         | 0.54%   |
| ASUSTek Computer                      | 6         | 0.54%   |
| Hewlett-Packard                       | 5         | 0.45%   |
| Fibocom                               | 5         | 0.45%   |
| AVM                                   | 4         | 0.36%   |
| Wilocity                              | 3         | 0.27%   |
| Qualcomm                              | 2         | 0.18%   |
| Microsoft                             | 2         | 0.18%   |
| Micro Star International              | 2         | 0.18%   |
| IMC Networks                          | 2         | 0.18%   |
| D-Link System                         | 2         | 0.18%   |
| Qualcomm Atheros Communications       | 1         | 0.09%   |
| Philips (or NXP)                      | 1         | 0.09%   |
| Netopia                               | 1         | 0.09%   |
| Linksys                               | 1         | 0.09%   |
| Gemtek                                | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 100       | 8.95%   |
| Intel Wireless 8265 / 8275                                              | 77        | 6.89%   |
| Intel Wireless 7260                                                     | 42        | 3.76%   |
| Intel Wireless 7265                                                     | 36        | 3.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 33        | 2.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 28        | 2.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 2.51%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 2.33%   |
| Intel Wireless 8260                                                     | 25        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 21        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 21        | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.7%    |
| Intel Wireless 3165                                                     | 19        | 1.7%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 1.52%   |
| Intel Wireless-AC 9260                                                  | 16        | 1.43%   |
| Intel Centrino Ultimate-N 6300                                          | 16        | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 14        | 1.25%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.07%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 8         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.72%   |
| Intel Wireless 3160                                                     | 8         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.72%   |
| Sierra Wireless EM7455                                                  | 7         | 0.63%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 7         | 0.63%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.63%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 7         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                         | 7         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.63%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.63%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                  | 7         | 0.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 7         | 0.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 7         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 6         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.54%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.54%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.54%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 6         | 0.54%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 0.54%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.45%   |
| NetGear A6210                                                           | 5         | 0.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.45%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 5         | 0.45%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 5         | 0.45%   |
| Dell Hub of E-Port Replicator                                           | 5         | 0.45%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 5         | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 588       | 40.95%  |
| Realtek Semiconductor         | 552       | 38.44%  |
| Broadcom                      | 75        | 5.22%   |
| Qualcomm Atheros              | 49        | 3.41%   |
| Marvell Technology Group      | 22        | 1.53%   |
| Lenovo                        | 20        | 1.39%   |
| Aquantia                      | 20        | 1.39%   |
| Nvidia                        | 16        | 1.11%   |
| ASIX Electronics              | 15        | 1.04%   |
| Broadcom Limited              | 14        | 0.97%   |
| Samsung Electronics           | 11        | 0.77%   |
| DisplayLink                   | 9         | 0.63%   |
| Microchip Technology          | 7         | 0.49%   |
| Huawei Technologies           | 7         | 0.49%   |
| Xiaomi                        | 3         | 0.21%   |
| NetXen Incorporated           | 3         | 0.21%   |
| MediaTek                      | 3         | 0.21%   |
| ICS Advent                    | 3         | 0.21%   |
| Microsoft                     | 2         | 0.14%   |
| Linksys                       | 2         | 0.14%   |
| TP-Link                       | 1         | 0.07%   |
| Standard Microsystems         | 1         | 0.07%   |
| OnePlus Technology (Shenzhen) | 1         | 0.07%   |
| NetGear                       | 1         | 0.07%   |
| Netchip Technology            | 1         | 0.07%   |
| MosChip Semiconductor         | 1         | 0.07%   |
| Mellanox Technologies         | 1         | 0.07%   |
| JMicron Technology            | 1         | 0.07%   |
| HMD Global                    | 1         | 0.07%   |
| Hewlett-Packard               | 1         | 0.07%   |
| D-Link System                 | 1         | 0.07%   |
| D-Link                        | 1         | 0.07%   |
| Cypress Semiconductor         | 1         | 0.07%   |
| Apple                         | 1         | 0.07%   |
| ADMtek                        | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 435       | 29.21%  |
| Intel I211 Gigabit Network Connection                             | 66        | 4.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 64        | 4.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 3.63%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 3.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 2.55%   |
| Intel Ethernet Connection I217-LM                                 | 38        | 2.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 2.15%   |
| Intel 82579V Gigabit Network Connection                           | 31        | 2.08%   |
| Intel 82574L Gigabit Network Connection                           | 27        | 1.81%   |
| Intel Ethernet Connection (6) I219-V                              | 23        | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18        | 1.21%   |
| Intel I350 Gigabit Network Connection                             | 18        | 1.21%   |
| Intel I210 Gigabit Network Connection                             | 17        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 1.07%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 1.01%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.94%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 14        | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.6%    |
| Intel 82576 Gigabit Network Connection                            | 8         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.47%   |
| Nvidia MCP55 Ethernet                                             | 7         | 0.47%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 7         | 0.47%   |
| Lenovo ThinkPad Lan                                               | 7         | 0.47%   |
| Intel Ethernet Controller I225-V                                  | 7         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.4%    |
| Nvidia MCP79 Ethernet                                             | 6         | 0.4%    |
| Intel Ethernet Connection (11) I219-LM                            | 6         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.34%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5         | 0.34%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 5         | 0.34%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.34%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.34%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.34%   |
| Huawei COL-L29                                                    | 5         | 0.34%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 5         | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.27%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 0.27%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.27%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 4         | 0.27%   |
| Intel Ethernet Controller X550                                    | 4         | 0.27%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 4         | 0.27%   |
| Intel Ethernet Connection I218-V                                  | 4         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1310      | 54.63%  |
| WiFi     | 1049      | 43.74%  |
| Modem    | 36        | 1.5%    |
| Unknown  | 3         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 767       | 50.36%  |
| WiFi     | 756       | 49.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 770       | 50.43%  |
| 1     | 603       | 39.49%  |
| 3     | 67        | 4.39%   |
| 0     | 52        | 3.41%   |
| 4     | 22        | 1.44%   |
| 6     | 7         | 0.46%   |
| 5     | 3         | 0.2%    |
| 10    | 1         | 0.07%   |
| 8     | 1         | 0.07%   |
| 7     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1293      | 83.26%  |
| Yes  | 260       | 16.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 489       | 56.34%  |
| Broadcom                        | 52        | 5.99%   |
| Realtek Semiconductor           | 50        | 5.76%   |
| Apple                           | 47        | 5.41%   |
| Cambridge Silicon Radio         | 41        | 4.72%   |
| Qualcomm Atheros Communications | 40        | 4.61%   |
| Foxconn / Hon Hai               | 29        | 3.34%   |
| Lite-On Technology              | 25        | 2.88%   |
| IMC Networks                    | 21        | 2.42%   |
| ASUSTek Computer                | 20        | 2.3%    |
| Hewlett-Packard                 | 11        | 1.27%   |
| Dell                            | 11        | 1.27%   |
| Ralink                          | 9         | 1.04%   |
| Marvell Semiconductor           | 6         | 0.69%   |
| Toshiba                         | 3         | 0.35%   |
| Micro Star International        | 3         | 0.35%   |
| Alps Electric                   | 2         | 0.23%   |
| USI                             | 1         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.12%   |
| Realtek                         | 1         | 0.12%   |
| Ralink Technology               | 1         | 0.12%   |
| MediaTek                        | 1         | 0.12%   |
| Logitech                        | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Chicony Electronics             | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 203       | 23.36%  |
| Intel AX200 Bluetooth                               | 95        | 10.93%  |
| Intel Bluetooth Device                              | 73        | 8.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 62        | 7.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 41        | 4.72%   |
| Realtek Bluetooth Radio                             | 30        | 3.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 2.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.96%   |
| Apple Bluetooth Host Controller                     | 17        | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 14        | 1.61%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 1.27%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 1.15%   |
| Apple Bluetooth USB Host Controller                 | 10        | 1.15%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 1.04%   |
| IMC Networks Bluetooth Radio                        | 9         | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.69%   |
| Apple Bluetooth HCI                                 | 6         | 0.69%   |
| Lite-On Bluetooth Device                            | 5         | 0.58%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite        | 4         | 0.46%   |
| IMC Networks Wireless_Device                        | 4         | 0.46%   |
| IMC Networks Bluetooth Device                       | 4         | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.46%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.46%   |
| ASUS Qualcomm Bluetooth 4.1                         | 4         | 0.46%   |
| ASUS Bluetooth Device                               | 4         | 0.46%   |
| ASUS BCM20702A0                                     | 4         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.35%   |
| Intel AX210 Bluetooth                               | 3         | 0.35%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.35%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.35%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 3         | 0.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.35%   |
| ASUS Bluetooth Radio                                | 3         | 0.35%   |
| Micro Star International Bluetooth Device           | 2         | 0.23%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.23%   |
| Lite-On Wireless_Device                             | 2         | 0.23%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]         | 2         | 0.23%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.23%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.23%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.23%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.23%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.23%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.23%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.23%   |
| USI Bluetooth Device                                | 1         | 0.12%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.12%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1142      | 55.25%  |
| Nvidia                     | 392       | 18.96%  |
| AMD                        | 315       | 15.24%  |
| C-Media Electronics        | 23        | 1.11%   |
| Logitech                   | 22        | 1.06%   |
| GN Netcom                  | 21        | 1.02%   |
| Lenovo                     | 14        | 0.68%   |
| Plantronics                | 8         | 0.39%   |
| Hewlett-Packard            | 7         | 0.34%   |
| SteelSeries ApS            | 6         | 0.29%   |
| RODE Microphones           | 6         | 0.29%   |
| BEHRINGER International    | 6         | 0.29%   |
| ASUSTek Computer           | 6         | 0.29%   |
| Realtek Semiconductor      | 5         | 0.24%   |
| Creative Labs              | 5         | 0.24%   |
| Texas Instruments          | 4         | 0.19%   |
| Samson Technologies        | 4         | 0.19%   |
| Razer USA                  | 4         | 0.19%   |
| Kingston Technology        | 4         | 0.19%   |
| Generalplus Technology     | 4         | 0.19%   |
| Apple                      | 4         | 0.19%   |
| Corsair                    | 3         | 0.15%   |
| Conexant Systems           | 3         | 0.15%   |
| Yamaha                     | 2         | 0.1%    |
| XMOS                       | 2         | 0.1%    |
| VIA Technologies           | 2         | 0.1%    |
| TerraTec Electronic        | 2         | 0.1%    |
| Tenx Technology            | 2         | 0.1%    |
| Sennheiser Communications  | 2         | 0.1%    |
| Roland                     | 2         | 0.1%    |
| ROCCAT                     | 2         | 0.1%    |
| JMTek                      | 2         | 0.1%    |
| HiFiBerry                  | 2         | 0.1%    |
| GYROCOM C&C                | 2         | 0.1%    |
| Focusrite-Novation         | 2         | 0.1%    |
| Creative Technology        | 2         | 0.1%    |
| Audinate                   | 2         | 0.1%    |
| Turtle Beach               | 1         | 0.05%   |
| Trust                      | 1         | 0.05%   |
| Textech International      | 1         | 0.05%   |
| TEAC                       | 1         | 0.05%   |
| Sony                       | 1         | 0.05%   |
| Shure                      | 1         | 0.05%   |
| SAVITECH                   | 1         | 0.05%   |
| PreSonus Audio Electronics | 1         | 0.05%   |
| Other World Computing      | 1         | 0.05%   |
| ONN                        | 1         | 0.05%   |
| miniDSP                    | 1         | 0.05%   |
| Microsoft                  | 1         | 0.05%   |
| Micronas                   | 1         | 0.05%   |
| Micro Star International   | 1         | 0.05%   |
| Magic Control Technology   | 1         | 0.05%   |
| Griffin Technology         | 1         | 0.05%   |
| Giga-Byte Technology       | 1         | 0.05%   |
| freeVoice                  | 1         | 0.05%   |
| Elite Silicon              | 1         | 0.05%   |
| Elgato Systems             | 1         | 0.05%   |
| DisplayLink                | 1         | 0.05%   |
| Cambridge Silicon Radio    | 1         | 0.05%   |
| Bose                       | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 146       | 6.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 125       | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 90        | 3.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 77        | 3.22%   |
| AMD Family 17h/19h HD Audio Controller                                            | 75        | 3.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 66        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 62        | 2.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 60        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 56        | 2.34%   |
| AMD Starship/Matisse HD Audio Controller                                          | 55        | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                             | 53        | 2.22%   |
| Intel 8 Series HD Audio Controller                                                | 53        | 2.22%   |
| Intel 200 Series PCH HD Audio                                                     | 50        | 2.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 50        | 2.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 44        | 1.84%   |
| Nvidia GK107 HDMI Audio Controller                                                | 40        | 1.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 40        | 1.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 36        | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 36        | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 32        | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 32        | 1.34%   |
| Intel Broadwell-U Audio Controller                                                | 32        | 1.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 32        | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 27        | 1.13%   |
| Nvidia GP102 HDMI Audio Controller                                                | 25        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 25        | 1.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 25        | 1.05%   |
| Nvidia GP104 High Definition Audio Controller                                     | 24        | 1%      |
| Intel Comet Lake PCH cAVS                                                         | 24        | 1%      |
| Nvidia GK104 HDMI Audio Controller                                                | 22        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                                     | 22        | 0.92%   |
| AMD FCH Azalia Controller                                                         | 22        | 0.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 21        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 20        | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 20        | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 19        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 19        | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                | 18        | 0.75%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 18        | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 17        | 0.71%   |
| Nvidia GP106 High Definition Audio Controller                                     | 16        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 14        | 0.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 14        | 0.59%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 14        | 0.59%   |
| AMD Navi 10 HDMI Audio                                                            | 14        | 0.59%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 14        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                     | 13        | 0.54%   |
| Nvidia High Definition Audio Controller                                           | 12        | 0.5%    |
| Intel CM238 HD Audio Controller                                                   | 12        | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 12        | 0.5%    |
| Nvidia TU116 High Definition Audio Controller                                     | 11        | 0.46%   |
| Nvidia TU104 HD Audio Controller                                                  | 11        | 0.46%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 11        | 0.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 11        | 0.46%   |
| Nvidia TU102 High Definition Audio Controller                                     | 10        | 0.42%   |
| Nvidia GM206 High Definition Audio Controller                                     | 10        | 0.42%   |
| Nvidia GM204 High Definition Audio Controller                                     | 10        | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                 | 10        | 0.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 10        | 0.42%   |
| Nvidia MCP79 High Definition Audio                                                | 9         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 248       | 25.13%  |
| SK hynix            | 168       | 17.02%  |
| Kingston            | 159       | 16.11%  |
| Corsair             | 104       | 10.54%  |
| Micron Technology   | 92        | 9.32%   |
| Unknown             | 76        | 7.7%    |
| Crucial             | 40        | 4.05%   |
| G.Skill             | 31        | 3.14%   |
| Elpida              | 14        | 1.42%   |
| A-DATA Technology   | 11        | 1.11%   |
| Ramaxel Technology  | 10        | 1.01%   |
| Patriot             | 5         | 0.51%   |
| Nanya Technology    | 4         | 0.41%   |
| Hewlett-Packard     | 3         | 0.3%    |
| Avant               | 3         | 0.3%    |
| Unknown (ABCD)      | 2         | 0.2%    |
| Unknown (0x9801)    | 2         | 0.2%    |
| Apacer              | 2         | 0.2%    |
| Unknown             | 2         | 0.2%    |
| Unknown (08AE)      | 1         | 0.1%    |
| Unifosa             | 1         | 0.1%    |
| Princeton           | 1         | 0.1%    |
| OnBoard             | 1         | 0.1%    |
| OCZ                 | 1         | 0.1%    |
| HPE                 | 1         | 0.1%    |
| G-Alantic           | 1         | 0.1%    |
| ASint Technology    | 1         | 0.1%    |
| Advantech           | 1         | 0.1%    |
| A-DA                | 1         | 0.1%    |
| 48spaces            | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.03%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 1.03%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 10        | 0.94%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 9         | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.56%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 6         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 6         | 0.56%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s           | 6         | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.47%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 5         | 0.47%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 5         | 0.47%   |
| Kingston RAM 99U5471-020.A00LF 4096MB DIMM DDR3 1600MT/s         | 5         | 0.47%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 0.47%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3000MT/s         | 5         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 4         | 0.37%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 4         | 0.37%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 4         | 0.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.37%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s          | 4         | 0.37%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s          | 4         | 0.37%   |
| Samsung RAM Module 8192MB DIMM DDR3 800MT/s                      | 4         | 0.37%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 4         | 0.37%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.37%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.37%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 4         | 0.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.37%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s           | 4         | 0.37%   |
| Samsung RAM K4EBE304EB-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s  | 4         | 0.37%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.37%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                    | 4         | 0.37%   |
| Kingston RAM Module 2048MB DIMM DDR3 1333MT/s                    | 4         | 0.37%   |
| Kingston RAM 99U5471-037.A00LF 8GB DIMM DDR3 1600MT/s            | 4         | 0.37%   |
| G.Skill RAM F4-3600C17-16GTZR 16GB DIMM DDR4 3666MT/s            | 4         | 0.37%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s         | 4         | 0.37%   |
| Corsair RAM CM4X16GC3000C16K8 16384MB DIMM DDR4 3000MT/s         | 4         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 3         | 0.28%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 3         | 0.28%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                          | 3         | 0.28%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.28%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.28%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.28%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 3         | 0.28%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.28%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 0.28%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s              | 3         | 0.28%   |
| Samsung RAM M378A1G43EB1-CPB 8GB DIMM DDR4 2133MT/s              | 3         | 0.28%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 3         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 429       | 48.31%  |
| DDR3    | 323       | 36.37%  |
| LPDDR3  | 44        | 4.95%   |
| DDR2    | 30        | 3.38%   |
| LPDDR4  | 29        | 3.27%   |
| Unknown | 15        | 1.69%   |
| SDRAM   | 13        | 1.46%   |
| DDR     | 5         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 422       | 47.68%  |
| DIMM         | 382       | 43.16%  |
| Row Of Chips | 66        | 7.46%   |
| Chip         | 8         | 0.9%    |
| RIMM         | 3         | 0.34%   |
| Unknown      | 3         | 0.34%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 400       | 42.11%  |
| 4096  | 223       | 23.47%  |
| 16384 | 183       | 19.26%  |
| 2048  | 87        | 9.16%   |
| 32768 | 30        | 3.16%   |
| 1024  | 23        | 2.42%   |
| 65536 | 3         | 0.32%   |
| 512   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 203       | 21.39%  |
| 2667    | 135       | 14.23%  |
| 3200    | 116       | 12.22%  |
| 2133    | 84        | 8.85%   |
| 2400    | 79        | 8.32%   |
| 1333    | 74        | 7.8%    |
| 1334    | 29        | 3.06%   |
| 800     | 21        | 2.21%   |
| 1867    | 19        | 2%      |
| 2666    | 18        | 1.9%    |
| 3600    | 17        | 1.79%   |
| 3000    | 14        | 1.48%   |
| 4267    | 12        | 1.26%   |
| 3400    | 11        | 1.16%   |
| 667     | 11        | 1.16%   |
| 1067    | 10        | 1.05%   |
| Unknown | 9         | 0.95%   |
| 3466    | 8         | 0.84%   |
| 3733    | 7         | 0.74%   |
| 3266    | 7         | 0.74%   |
| 2933    | 6         | 0.63%   |
| 1066    | 6         | 0.63%   |
| 2000    | 5         | 0.53%   |
| 3666    | 4         | 0.42%   |
| 2465    | 4         | 0.42%   |
| 2048    | 4         | 0.42%   |
| 4266    | 3         | 0.32%   |
| 3100    | 3         | 0.32%   |
| 1866    | 3         | 0.32%   |
| 333     | 3         | 0.32%   |
| 4800    | 2         | 0.21%   |
| 4199    | 2         | 0.21%   |
| 3800    | 2         | 0.21%   |
| 3500    | 2         | 0.21%   |
| 3334    | 2         | 0.21%   |
| 2800    | 2         | 0.21%   |
| 975     | 2         | 0.21%   |
| 266     | 2         | 0.21%   |
| 3867    | 1         | 0.11%   |
| 3533    | 1         | 0.11%   |
| 3333    | 1         | 0.11%   |
| 3066    | 1         | 0.11%   |
| 3020    | 1         | 0.11%   |
| 2866    | 1         | 0.11%   |
| 1639    | 1         | 0.11%   |
| 400     | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 20        | 44.44%  |
| Brother Industries       | 11        | 24.44%  |
| Canon                    | 4         | 8.89%   |
| Samsung Electronics      | 3         | 6.67%   |
| Oki Data                 | 2         | 4.44%   |
| Zhuhai Poskey Technology | 1         | 2.22%   |
| Seiko Epson              | 1         | 2.22%   |
| Prolific Technology      | 1         | 2.22%   |
| Konica Minolta           | 1         | 2.22%   |
| Dymo-CoStar              | 1         | 2.22%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series                             | 2         | 4.44%   |
| Oki Data USB Device                                        | 2         | 4.44%   |
| HP OfficeJet Pro 7730 series                               | 2         | 4.44%   |
| HP OfficeJet 6950                                          | 2         | 4.44%   |
| HP ENVY 5540 series                                        | 2         | 4.44%   |
| Zhuhai Poskey Printer                                      | 1         | 2.22%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 2.22%   |
| Samsung C48x Series Color Laser Multifunction Printer      | 1         | 2.22%   |
| Prolific PL2305 Parallel Port                              | 1         | 2.22%   |
| Konica Minolta Printer                                     | 1         | 2.22%   |
| HP Smart Tank Plus 550 series                              | 1         | 2.22%   |
| HP Officejet 4630 series                                   | 1         | 2.22%   |
| HP LaserJet Pro M148f-M149f                                | 1         | 2.22%   |
| HP LaserJet P3010 Series                                   | 1         | 2.22%   |
| HP LaserJet P2055 series                                   | 1         | 2.22%   |
| HP Laserjet P1505                                          | 1         | 2.22%   |
| HP LaserJet 3050                                           | 1         | 2.22%   |
| HP LaserJet 1320                                           | 1         | 2.22%   |
| HP LaserJet 1020                                           | 1         | 2.22%   |
| HP Laser 107a                                              | 1         | 2.22%   |
| HP ENVY Photo 6200 series                                  | 1         | 2.22%   |
| HP ENVY 4520 series                                        | 1         | 2.22%   |
| HP DeskJet F2100 Printer series                            | 1         | 2.22%   |
| HP Deskjet 2540 series                                     | 1         | 2.22%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 2.22%   |
| Canon TS3300 series                                        | 1         | 2.22%   |
| Canon PIXMA TS6250                                         | 1         | 2.22%   |
| Canon PIXMA MX450 Series                                   | 1         | 2.22%   |
| Canon iP7200 series                                        | 1         | 2.22%   |
| Brother Printer                                            | 1         | 2.22%   |
| Brother MFC Composite Device                               | 1         | 2.22%   |
| Brother HL-L2360D series                                   | 1         | 2.22%   |
| Brother HL-L2350DW series                                  | 1         | 2.22%   |
| Brother HL-3140CW series                                   | 1         | 2.22%   |
| Brother HL-3040CN series                                   | 1         | 2.22%   |
| Brother HL-2130 series                                     | 1         | 2.22%   |
| Brother HL-2030 Laser Printer                              | 1         | 2.22%   |
| Brother DCP-9020CDW                                        | 1         | 2.22%   |
| Brother DCP-7055W                                          | 1         | 2.22%   |
| Brother DCP-7030                                           | 1         | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 53.85%  |
| Seiko Epson       | 3         | 23.08%  |
| Hewlett-Packard   | 2         | 15.38%  |
| Canon Electronics | 1         | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                 | 2         | 15.38%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 7.69%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 7.69%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 7.69%   |
| HP ScanJet 4070 PhotoSmart                              | 1         | 7.69%   |
| HP ScanJet 2400c                                        | 1         | 7.69%   |
| Canon P-150 Scanner                                     | 1         | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 7.69%   |
| Canon CanoScan N650U/N656U                              | 1         | 7.69%   |
| Canon CanoScan LIDE 25                                  | 1         | 7.69%   |
| Canon CanoScan LiDE 200                                 | 1         | 7.69%   |
| Canon CanoScan LiDE 100                                 | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 229       | 27.59%  |
| IMC Networks                           | 61        | 7.35%   |
| Logitech                               | 59        | 7.11%   |
| Acer                                   | 58        | 6.99%   |
| Microdia                               | 51        | 6.14%   |
| Apple                                  | 50        | 6.02%   |
| Realtek Semiconductor                  | 47        | 5.66%   |
| Sunplus Innovation Technology          | 37        | 4.46%   |
| Quanta                                 | 37        | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 3.73%   |
| Lite-On Technology                     | 27        | 3.25%   |
| Suyin                                  | 23        | 2.77%   |
| Syntek                                 | 15        | 1.81%   |
| Lenovo                                 | 13        | 1.57%   |
| Alcor Micro                            | 11        | 1.33%   |
| Microsoft                              | 10        | 1.2%    |
| Samsung Electronics                    | 9         | 1.08%   |
| Ricoh                                  | 9         | 1.08%   |
| Luxvisions Innotech Limited            | 7         | 0.84%   |
| Silicon Motion                         | 6         | 0.72%   |
| Z-Star Microelectronics                | 4         | 0.48%   |
| Primax Electronics                     | 3         | 0.36%   |
| Generalplus Technology                 | 3         | 0.36%   |
| Xiaomi                                 | 2         | 0.24%   |
| OmniVision Technologies                | 2         | 0.24%   |
| MacroSilicon                           | 2         | 0.24%   |
| Genesys Logic                          | 2         | 0.24%   |
| DigiTech                               | 2         | 0.24%   |
| Creative Technology                    | 2         | 0.24%   |
| ALi                                    | 2         | 0.24%   |
| YGTek                                  | 1         | 0.12%   |
| Pixart Imaging                         | 1         | 0.12%   |
| Novatek Microelectronics               | 1         | 0.12%   |
| Nikon                                  | 1         | 0.12%   |
| Mimaki Engineering                     | 1         | 0.12%   |
| Leap Motion                            | 1         | 0.12%   |
| IPEVO                                  | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| Importek                               | 1         | 0.12%   |
| Huawei Technologies                    | 1         | 0.12%   |
| Hewlett-Packard                        | 1         | 0.12%   |
| Foxconn / Hon Hai                      | 1         | 0.12%   |
| Blackmagic Design                      | 1         | 0.12%   |
| Aveo Technology                        | 1         | 0.12%   |
| ASUSTek Computer                       | 1         | 0.12%   |
| A4Tech                                 | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 50        | 5.92%   |
| Microdia Integrated_Webcam_HD                       | 28        | 3.32%   |
| IMC Networks Integrated Camera                      | 28        | 3.32%   |
| Chicony HD WebCam                                   | 24        | 2.84%   |
| Realtek Integrated_Webcam_HD                        | 16        | 1.9%    |
| Chicony HP HD Camera                                | 16        | 1.9%    |
| Acer Integrated Camera                              | 15        | 1.78%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 14        | 1.66%   |
| Apple Built-in iSight                               | 14        | 1.66%   |
| Lite-On Integrated Camera                           | 13        | 1.54%   |
| Apple FaceTime HD Camera (Built-in)                 | 13        | 1.54%   |
| Quanta HP HD Camera                                 | 12        | 1.42%   |
| Logitech HD Pro Webcam C920                         | 11        | 1.3%    |
| Chicony HP Truevision HD                            | 11        | 1.3%    |
| Sunplus HD WebCam                                   | 10        | 1.18%   |
| Chicony USB2.0 Camera                               | 10        | 1.18%   |
| Chicony HP Wide Vision HD Camera                    | 10        | 1.18%   |
| Samsung Galaxy series, misc. (MTP mode)             | 9         | 1.07%   |
| Microdia Integrated Webcam                          | 8         | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE                           | 8         | 0.95%   |
| Acer Lenovo EasyCamera                              | 8         | 0.95%   |
| Syntek Integrated Camera                            | 7         | 0.83%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 0.83%   |
| Logitech Webcam C270                                | 7         | 0.83%   |
| Lite-On HP HD Camera                                | 7         | 0.83%   |
| Chicony Integrated Camera (1280x720@30)             | 7         | 0.83%   |
| Apple FaceTime HD Camera                            | 7         | 0.83%   |
| Suyin HP Truevision HD                              | 6         | 0.71%   |
| Realtek USB2.0 HD UVC WebCam                        | 6         | 0.71%   |
| Lenovo Integrated Webcam                            | 6         | 0.71%   |
| Chicony VGA Webcam                                  | 6         | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 0.71%   |
| Chicony HP HD Webcam                                | 6         | 0.71%   |
| Chicony HD User Facing                              | 6         | 0.71%   |
| Chicony CNF9055 Toshiba Webcam                      | 6         | 0.71%   |
| Syntek Lenovo EasyCamera                            | 5         | 0.59%   |
| Realtek Integrated Webcam HD                        | 5         | 0.59%   |
| Logitech QuickCam Pro 9000                          | 5         | 0.59%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 0.59%   |
| Chicony HP Full-HD Camera                           | 5         | 0.59%   |
| Acer ThinkPad Integrated Camera                     | 5         | 0.59%   |
| Acer SunplusIT Integrated Camera                    | 5         | 0.59%   |
| Sunplus SPCA2281 Web Camera                         | 4         | 0.47%   |
| Realtek HP "Truevision HD" laptop camera            | 4         | 0.47%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.47%   |
| Quanta HD Webcam                                    | 4         | 0.47%   |
| Logitech HD Webcam C615                             | 4         | 0.47%   |
| Lenovo Integrated Webcam [R5U877]                   | 4         | 0.47%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.47%   |
| Chicony USB2.0 HD UVC WebCam                        | 4         | 0.47%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.47%   |
| Chicony HP TrueVision HD Camera                     | 4         | 0.47%   |
| Chicony FJ Camera                                   | 4         | 0.47%   |
| Chicony EasyCamera                                  | 4         | 0.47%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 4         | 0.47%   |
| Acer BisonCam,NB Pro                                | 4         | 0.47%   |
| Acer BisonCam, NB Pro                               | 4         | 0.47%   |
| Suyin USB2.0 RGBIR Camera                           | 3         | 0.36%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.36%   |
| Suyin 1.3M HD WebCam                                | 3         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 93        | 36.33%  |
| Synaptics                  | 93        | 36.33%  |
| Shenzhen Goodix Technology | 20        | 7.81%   |
| Elan Microelectronics      | 14        | 5.47%   |
| AuthenTec                  | 14        | 5.47%   |
| Upek                       | 12        | 4.69%   |
| LighTuning Technology      | 8         | 3.13%   |
| STMicroelectronics         | 2         | 0.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 7.81%   |
| Unknown                                                                    | 20        | 7.81%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 4.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.69%   |
| Synaptics  WBDI                                                            | 10        | 3.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.91%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 3.52%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 3.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.13%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 2.73%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 2.73%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 2.73%   |
| Validity Sensors VFS491                                                    | 6         | 2.34%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.34%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.95%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.95%   |
| AuthenTec AES2810                                                          | 5         | 1.95%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 1.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.56%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.56%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.78%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.78%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.39%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.39%   |
| Synaptics WBDI Device                                                      | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 31        | 37.8%   |
| Broadcom                  | 30        | 36.59%  |
| Upek                      | 8         | 9.76%   |
| Yubico.com                | 3         | 3.66%   |
| O2 Micro                  | 3         | 3.66%   |
| Lenovo                    | 2         | 2.44%   |
| OmniKey                   | 1         | 1.22%   |
| Clay Logic                | 1         | 1.22%   |
| BIT4ID                    | 1         | 1.22%   |
| Aladdin Knowledge Systems | 1         | 1.22%   |
| Advanced Card Systems     | 1         | 1.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 37.8%   |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 12.2%   |
| Broadcom 5880                                                                | 10        | 12.2%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 9.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 7.32%   |
| Broadcom 58200                                                               | 4         | 4.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.66%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.44%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.44%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.22%   |
| OmniKey CardMan 4321                                                         | 1         | 1.22%   |
| Clay Logic Nitrokey Start                                                    | 1         | 1.22%   |
| BIT4ID miniLector-S                                                          | 1         | 1.22%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.22%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1032      | 65.86%  |
| 1     | 418       | 26.68%  |
| 2     | 89        | 5.68%   |
| 3     | 17        | 1.08%   |
| 4     | 9         | 0.57%   |
| 7     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 251       | 37.92%  |
| Graphics card            | 102       | 15.41%  |
| Chipcard                 | 70        | 10.57%  |
| Net/wireless             | 69        | 10.42%  |
| Communication controller | 35        | 5.29%   |
| Multimedia controller    | 34        | 5.14%   |
| Unassigned class         | 23        | 3.47%   |
| Bluetooth                | 17        | 2.57%   |
| Camera                   | 14        | 2.11%   |
| Card reader              | 10        | 1.51%   |
| Sound                    | 9         | 1.36%   |
| Net/ethernet             | 8         | 1.21%   |
| Network                  | 5         | 0.76%   |
| Storage                  | 4         | 0.6%    |
| Modem                    | 4         | 0.6%    |
| Dvb card                 | 3         | 0.45%   |
| Storage/nvme             | 2         | 0.3%    |
| Storage/raid             | 1         | 0.15%   |
| Flash memory             | 1         | 0.15%   |

