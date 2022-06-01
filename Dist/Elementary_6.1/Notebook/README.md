Elementary 6.1 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

Total: 320

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 13 9343                 | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| ASUSTek       | X550CA                      | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| Acer          | Swift SF114-32              | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| Apple         | MacBook4,1                  | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| AMI           | Intel                       | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| Sony          | VPCEB23FM                   | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| ASUSTek       | K55A                        | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| eMachines     | E525                        | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X202E                       | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| HP            | ProBook 440 G7              | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Acer          | Aspire E5-575G              | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| HP            | Notebook                    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Dell          | Inspiron MM061              | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| Sony          | SVP1321B4E                  | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | MacBookAir7,1               | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| Acer          | Nitro AN517-52              | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| Packard Be... | EasyNote LS11HR             | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | X540SA                      | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| Dell          | Precision 7720              | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Google        | Lulu                        | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Sony          | SVE15115EN                  | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| Apple         | MacBookAir4,2               | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| Timi          | TM1613                      | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Apple         | MacBookPro6,2               | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | K95VJ                       | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
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
| Apple         | MacBookPro8,2               | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| Dell          | Latitude E5400              | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
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


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 62        | 24.12%  |
| 5.13.0-28-generic          | 32        | 12.45%  |
| 5.13.0-30-generic          | 28        | 10.89%  |
| 5.13.0-27-generic          | 24        | 9.34%   |
| 5.13.0-40-generic          | 15        | 5.84%   |
| 5.13.0-39-generic          | 15        | 5.84%   |
| 5.13.0-35-generic          | 13        | 5.06%   |
| 5.11.0-44-generic          | 13        | 5.06%   |
| 5.13.0-37-generic          | 12        | 4.67%   |
| 5.11.0-46-generic          | 10        | 3.89%   |
| 5.13.0-41-generic          | 9         | 3.5%    |
| 5.11.0-41-generic          | 4         | 1.56%   |
| 5.13.0-44-generic          | 3         | 1.17%   |
| 5.13.0-25-generic          | 2         | 0.78%   |
| 5.11.0-40-generic          | 2         | 0.78%   |
| 5.8.0-50-generic           | 1         | 0.39%   |
| 5.16.16-051616-generic     | 1         | 0.39%   |
| 5.16.10-051610-generic     | 1         | 0.39%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.39%   |
| 5.15.36-xanmod1            | 1         | 0.39%   |
| 5.15.3-xanmod1             | 1         | 0.39%   |
| 5.15.21-051521-generic     | 1         | 0.39%   |
| 5.15.13-xanmod1            | 1         | 0.39%   |
| 5.15.12-xanmod1-tt         | 1         | 0.39%   |
| 5.15.11-t2-big-sur         | 1         | 0.39%   |
| 5.14.10-051410-generic     | 1         | 0.39%   |
| 5.14.0-1029-oem            | 1         | 0.39%   |
| 5.14.0-1011-oem            | 1         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 147       | 58.57%  |
| 5.11.0  | 91        | 36.25%  |
| 5.14.0  | 2         | 0.8%    |
| 5.8.0   | 1         | 0.4%    |
| 5.16.16 | 1         | 0.4%    |
| 5.16.10 | 1         | 0.4%    |
| 5.16.0  | 1         | 0.4%    |
| 5.15.36 | 1         | 0.4%    |
| 5.15.3  | 1         | 0.4%    |
| 5.15.21 | 1         | 0.4%    |
| 5.15.13 | 1         | 0.4%    |
| 5.15.12 | 1         | 0.4%    |
| 5.15.11 | 1         | 0.4%    |
| 5.14.10 | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 147       | 58.8%   |
| 5.11    | 91        | 36.4%   |
| 5.15    | 6         | 2.4%    |
| 5.14    | 3         | 1.2%    |
| 5.16    | 2         | 0.8%    |
| 5.8     | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 248       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Pantheon | 247       | 99.6%   |
| Unknown  | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 248       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 198       | 79.52%  |
| LightDM | 50        | 20.08%  |
| GDM     | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 114       | 45.97%  |
| de_DE   | 34        | 13.71%  |
| es_ES   | 19        | 7.66%   |
| en_GB   | 12        | 4.84%   |
| ru_RU   | 11        | 4.44%   |
| fr_FR   | 11        | 4.44%   |
| pt_BR   | 10        | 4.03%   |
| it_IT   | 9         | 3.63%   |
| pl_PL   | 6         | 2.42%   |
| pt_PT   | 3         | 1.21%   |
| en_CA   | 3         | 1.21%   |
| tr_TR   | 2         | 0.81%   |
| nl_NL   | 2         | 0.81%   |
| nb_NO   | 2         | 0.81%   |
| en_AU   | 2         | 0.81%   |
| sv_SE   | 1         | 0.4%    |
| hu_HU   | 1         | 0.4%    |
| et_EE   | 1         | 0.4%    |
| de_CH   | 1         | 0.4%    |
| cs_CZ   | 1         | 0.4%    |
| C       | 1         | 0.4%    |
| bg_BG   | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 169       | 68.15%  |
| BIOS | 79        | 31.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 242       | 97.58%  |
| Btrfs   | 4         | 1.61%   |
| Overlay | 2         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 210       | 84.34%  |
| GPT     | 34        | 13.65%  |
| MBR     | 5         | 2.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 242       | 97.58%  |
| Yes       | 6         | 2.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 230       | 92.74%  |
| Yes       | 18        | 7.26%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 53        | 21.37%  |
| Hewlett-Packard        | 36        | 14.52%  |
| ASUSTek Computer       | 33        | 13.31%  |
| Apple                  | 30        | 12.1%   |
| Dell                   | 24        | 9.68%   |
| Acer                   | 20        | 8.06%   |
| HUAWEI                 | 8         | 3.23%   |
| Sony                   | 6         | 2.42%   |
| Samsung Electronics    | 6         | 2.42%   |
| MSI                    | 6         | 2.42%   |
| Toshiba                | 4         | 1.61%   |
| Timi                   | 2         | 0.81%   |
| Teclast                | 2         | 0.81%   |
| Star Labs              | 2         | 0.81%   |
| Notebook               | 2         | 0.81%   |
| Monster                | 2         | 0.81%   |
| LG Electronics         | 2         | 0.81%   |
| Wortmann AG            | 1         | 0.4%    |
| Razer                  | 1         | 0.4%    |
| PIPO                   | 1         | 0.4%    |
| Packard Bell           | 1         | 0.4%    |
| iOTA                   | 1         | 0.4%    |
| Google                 | 1         | 0.4%    |
| Fujitsu                | 1         | 0.4%    |
| eMachines              | 1         | 0.4%    |
| Avell High Performance | 1         | 0.4%    |
| AMI                    | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBook5,1                                  | 4         | 1.61%   |
| HUAWEI MACHD-WXX9                                 | 3         | 1.21%   |
| ASUS ZenBook UX425EA_UX425EA                      | 3         | 1.21%   |
| ASUS X550CA                                       | 3         | 1.21%   |
| Apple MacBookPro8,2                               | 3         | 1.21%   |
| Timi TM1613                                       | 2         | 0.81%   |
| MSI Prestige 15 A11UC                             | 2         | 0.81%   |
| Lenovo IdeaPad 310-15IKB 80TV                     | 2         | 0.81%   |
| HUAWEI NBLK-WAX9X                                 | 2         | 0.81%   |
| HP EliteBook 8460p                                | 2         | 0.81%   |
| HP EliteBook 840 G1                               | 2         | 0.81%   |
| Dell XPS 13 9343                                  | 2         | 0.81%   |
| Dell Inspiron N5050                               | 2         | 0.81%   |
| Dell Inspiron 15-3567                             | 2         | 0.81%   |
| Apple MacBookPro6,2                               | 2         | 0.81%   |
| Apple MacBookPro5,5                               | 2         | 0.81%   |
| Apple MacBookAir7,1                               | 2         | 0.81%   |
| Apple MacBookAir4,2                               | 2         | 0.81%   |
| Apple MacBook4,1                                  | 2         | 0.81%   |
| Acer Swift SF114-32                               | 2         | 0.81%   |
| Wortmann AG 1220729_1470271                       | 1         | 0.4%    |
| Toshiba Satellite L850D-BJS                       | 1         | 0.4%    |
| Toshiba Satellite L50D-C                          | 1         | 0.4%    |
| Toshiba Satellite C70D-A                          | 1         | 0.4%    |
| Toshiba PORTEGE Z830                              | 1         | 0.4%    |
| Teclast F7                                        | 1         | 0.4%    |
| Teclast F15S                                      | 1         | 0.4%    |
| Star Labs StarBook                                | 1         | 0.4%    |
| Star Labs LabTop                                  | 1         | 0.4%    |
| Sony VPCEB23FM                                    | 1         | 0.4%    |
| Sony VPCEA3S1E                                    | 1         | 0.4%    |
| Sony VPCCA4E1E                                    | 1         | 0.4%    |
| Sony SVP1321B4E                                   | 1         | 0.4%    |
| Sony SVE15115EN                                   | 1         | 0.4%    |
| Sony SVE14A390X                                   | 1         | 0.4%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411       | 1         | 0.4%    |
| Samsung Lumpy                                     | 1         | 0.4%    |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.4%    |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D        | 1         | 0.4%    |
| Samsung 870Z5E/880Z5E/680Z5E                      | 1         | 0.4%    |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.4%    |
| Razer Blade Stealth                               | 1         | 0.4%    |
| PIPO W9                                           | 1         | 0.4%    |
| Packard Bell EasyNote LS11HR                      | 1         | 0.4%    |
| Notebook W65_67SJ                                 | 1         | 0.4%    |
| Notebook P65xHP                                   | 1         | 0.4%    |
| MSI PS63 Modern 8RD                               | 1         | 0.4%    |
| MSI Modern 14 B4MW                                | 1         | 0.4%    |
| MSI Modern 14 B10MW                               | 1         | 0.4%    |
| MSI GF63 Thin 9SCSR                               | 1         | 0.4%    |
| Monster MARKUT M7 V1.x                            | 1         | 0.4%    |
| Monster ABRA A5 V13.2                             | 1         | 0.4%    |
| LG A410-G.BC51P1                                  | 1         | 0.4%    |
| LG 17Z95P-K.AAE8U1                                | 1         | 0.4%    |
| Lenovo Yoga 300-11IBR 80M1                        | 1         | 0.4%    |
| Lenovo ThinkPad X270 W10DG 20K5S2VL00             | 1         | 0.4%    |
| Lenovo ThinkPad X260 20F5S84400                   | 1         | 0.4%    |
| Lenovo ThinkPad X230 2325ND9                      | 1         | 0.4%    |
| Lenovo ThinkPad X201 Tablet 3113CG2               | 1         | 0.4%    |
| Lenovo ThinkPad X13 Gen 1 20UFS00G00              | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 28        | 11.29%  |
| Lenovo IdeaPad        | 16        | 6.45%   |
| Acer Aspire           | 12        | 4.84%   |
| Dell Inspiron         | 10        | 4.03%   |
| HP ProBook            | 8         | 3.23%   |
| HP Pavilion           | 8         | 3.23%   |
| HP EliteBook          | 8         | 3.23%   |
| ASUS VivoBook         | 7         | 2.82%   |
| ASUS ZenBook          | 6         | 2.42%   |
| Dell Latitude         | 5         | 2.02%   |
| Apple MacBook5        | 5         | 2.02%   |
| Acer Swift            | 5         | 2.02%   |
| HP Laptop             | 4         | 1.61%   |
| Dell Precision        | 4         | 1.61%   |
| Apple MacBookPro8     | 4         | 1.61%   |
| Toshiba Satellite     | 3         | 1.21%   |
| HUAWEI MACHD-WXX9     | 3         | 1.21%   |
| Dell Vostro           | 3         | 1.21%   |
| ASUS X550CA           | 3         | 1.21%   |
| Apple MacBookPro5     | 3         | 1.21%   |
| Apple MacBookAir7     | 3         | 1.21%   |
| Timi TM1613           | 2         | 0.81%   |
| MSI Prestige          | 2         | 0.81%   |
| MSI Modern            | 2         | 0.81%   |
| Lenovo Legion         | 2         | 0.81%   |
| Lenovo G550           | 2         | 0.81%   |
| HUAWEI NBLK-WAX9X     | 2         | 0.81%   |
| HP Stream             | 2         | 0.81%   |
| Dell XPS              | 2         | 0.81%   |
| Apple MacBookPro9     | 2         | 0.81%   |
| Apple MacBookPro6     | 2         | 0.81%   |
| Apple MacBookAir6     | 2         | 0.81%   |
| Apple MacBookAir4     | 2         | 0.81%   |
| Apple MacBook4        | 2         | 0.81%   |
| Acer Nitro            | 2         | 0.81%   |
| Wortmann AG 1220729   | 1         | 0.4%    |
| Toshiba PORTEGE       | 1         | 0.4%    |
| Teclast F7            | 1         | 0.4%    |
| Teclast F15S          | 1         | 0.4%    |
| Star Labs StarBook    | 1         | 0.4%    |
| Star Labs LabTop      | 1         | 0.4%    |
| Sony VPCEB23FM        | 1         | 0.4%    |
| Sony VPCEA3S1E        | 1         | 0.4%    |
| Sony VPCCA4E1E        | 1         | 0.4%    |
| Sony SVP1321B4E       | 1         | 0.4%    |
| Sony SVE15115EN       | 1         | 0.4%    |
| Sony SVE14A390X       | 1         | 0.4%    |
| Samsung RV411         | 1         | 0.4%    |
| Samsung Lumpy         | 1         | 0.4%    |
| Samsung 950XDB        | 1         | 0.4%    |
| Samsung 900X3C        | 1         | 0.4%    |
| Samsung 870Z5E        | 1         | 0.4%    |
| Samsung 500R4K        | 1         | 0.4%    |
| Razer Blade           | 1         | 0.4%    |
| PIPO W9               | 1         | 0.4%    |
| Packard Bell EasyNote | 1         | 0.4%    |
| Notebook W65          | 1         | 0.4%    |
| Notebook P65xHP       | 1         | 0.4%    |
| MSI PS63              | 1         | 0.4%    |
| MSI GF63              | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 35        | 14.11%  |
| 2018 | 23        | 9.27%   |
| 2021 | 21        | 8.47%   |
| 2015 | 20        | 8.06%   |
| 2012 | 20        | 8.06%   |
| 2016 | 19        | 7.66%   |
| 2019 | 17        | 6.85%   |
| 2013 | 17        | 6.85%   |
| 2011 | 16        | 6.45%   |
| 2009 | 14        | 5.65%   |
| 2010 | 13        | 5.24%   |
| 2017 | 12        | 4.84%   |
| 2014 | 12        | 4.84%   |
| 2008 | 8         | 3.23%   |
| 2006 | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 248       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 206       | 83.06%  |
| Enabled  | 42        | 16.94%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 244       | 98.39%  |
| Yes  | 4         | 1.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 91        | 36.69%  |
| 3.01-4.0    | 61        | 24.6%   |
| 16.01-24.0  | 40        | 16.13%  |
| 8.01-16.0   | 34        | 13.71%  |
| 32.01-64.0  | 9         | 3.63%   |
| 1.01-2.0    | 9         | 3.63%   |
| 2.01-3.0    | 2         | 0.81%   |
| 24.01-32.0  | 1         | 0.4%    |
| 64.01-256.0 | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 97        | 37.89%  |
| 2.01-3.0   | 83        | 32.42%  |
| 3.01-4.0   | 33        | 12.89%  |
| 4.01-8.0   | 22        | 8.59%   |
| 0.51-1.0   | 12        | 4.69%   |
| 8.01-16.0  | 7         | 2.73%   |
| 24.01-32.0 | 1         | 0.39%   |
| 16.01-24.0 | 1         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 184       | 73.9%   |
| 2      | 60        | 24.1%   |
| 3      | 4         | 1.61%   |
| 5      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 67.2%   |
| Yes       | 82        | 32.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 176       | 70.97%  |
| No        | 72        | 29.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 98.79%  |
| No        | 3         | 1.21%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 89.92%  |
| No        | 25        | 10.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 35        | 14.11%  |
| Germany      | 30        | 12.1%   |
| Russia       | 15        | 6.05%   |
| India        | 14        | 5.65%   |
| Brazil       | 14        | 5.65%   |
| Italy        | 12        | 4.84%   |
| UK           | 10        | 4.03%   |
| Poland       | 8         | 3.23%   |
| France       | 8         | 3.23%   |
| Turkey       | 7         | 2.82%   |
| Spain        | 6         | 2.42%   |
| Mexico       | 6         | 2.42%   |
| Australia    | 6         | 2.42%   |
| Indonesia    | 5         | 2.02%   |
| Canada       | 5         | 2.02%   |
| Switzerland  | 4         | 1.61%   |
| Chile        | 4         | 1.61%   |
| Belgium      | 4         | 1.61%   |
| Austria      | 4         | 1.61%   |
| Portugal     | 3         | 1.21%   |
| New Zealand  | 3         | 1.21%   |
| Czechia      | 3         | 1.21%   |
| Argentina    | 3         | 1.21%   |
| South Africa | 2         | 0.81%   |
| Romania      | 2         | 0.81%   |
| Pakistan     | 2         | 0.81%   |
| Norway       | 2         | 0.81%   |
| Netherlands  | 2         | 0.81%   |
| Estonia      | 2         | 0.81%   |
| Colombia     | 2         | 0.81%   |
| Bulgaria     | 2         | 0.81%   |
| Belarus      | 2         | 0.81%   |
| Ukraine      | 1         | 0.4%    |
| Taiwan       | 1         | 0.4%    |
| Sweden       | 1         | 0.4%    |
| Sri Lanka    | 1         | 0.4%    |
| Serbia       | 1         | 0.4%    |
| Senegal      | 1         | 0.4%    |
| Peru         | 1         | 0.4%    |
| Nicaragua    | 1         | 0.4%    |
| Mozambique   | 1         | 0.4%    |
| Luxembourg   | 1         | 0.4%    |
| Lithuania    | 1         | 0.4%    |
| Latvia       | 1         | 0.4%    |
| Kenya        | 1         | 0.4%    |
| Japan        | 1         | 0.4%    |
| Ireland      | 1         | 0.4%    |
| Iceland      | 1         | 0.4%    |
| Hungary      | 1         | 0.4%    |
| Guyana       | 1         | 0.4%    |
| Greece       | 1         | 0.4%    |
| Finland      | 1         | 0.4%    |
| Croatia      | 1         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Sydney                 | 5         | 1.98%   |
| Moscow                 | 5         | 1.98%   |
| St Petersburg          | 4         | 1.58%   |
| Munich                 | 3         | 1.19%   |
| Warsaw                 | 2         | 0.79%   |
| Vienna                 | 2         | 0.79%   |
| Tucson                 | 2         | 0.79%   |
| Sao Paulo              | 2         | 0.79%   |
| Santo André           | 2         | 0.79%   |
| Monza                  | 2         | 0.79%   |
| Montornès del Vallès | 2         | 0.79%   |
| Minsk                  | 2         | 0.79%   |
| Madrid                 | 2         | 0.79%   |
| Islamabad              | 2         | 0.79%   |
| Hamburg                | 2         | 0.79%   |
| Cankaya                | 2         | 0.79%   |
| Bern                   | 2         | 0.79%   |
| Antalya                | 2         | 0.79%   |
| Ankara                 | 2         | 0.79%   |
| Zagreb                 | 1         | 0.4%    |
| Wroclaw                | 1         | 0.4%    |
| Wonosari               | 1         | 0.4%    |
| Wolgast                | 1         | 0.4%    |
| Witbank                | 1         | 0.4%    |
| West Bromwich          | 1         | 0.4%    |
| Wellington             | 1         | 0.4%    |
| Warrenton              | 1         | 0.4%    |
| Wallerfangen           | 1         | 0.4%    |
| Vitória da Conquista  | 1         | 0.4%    |
| Vilnius                | 1         | 0.4%    |
| Vila Nova de Gaia      | 1         | 0.4%    |
| Vigodarzere            | 1         | 0.4%    |
| Vernouillet            | 1         | 0.4%    |
| Vear                   | 1         | 0.4%    |
| Vantaa                 | 1         | 0.4%    |
| Valencia               | 1         | 0.4%    |
| Ulyanovsk              | 1         | 0.4%    |
| Ubstadt-Weiher         | 1         | 0.4%    |
| Tromsø                | 1         | 0.4%    |
| Trieste                | 1         | 0.4%    |
| Treviso                | 1         | 0.4%    |
| Toronto                | 1         | 0.4%    |
| Tomsk                  | 1         | 0.4%    |
| Timișoara             | 1         | 0.4%    |
| Thessaloniki           | 1         | 0.4%    |
| The Hague              | 1         | 0.4%    |
| Temuco                 | 1         | 0.4%    |
| Tecuci                 | 1         | 0.4%    |
| Tauranga               | 1         | 0.4%    |
| Surrey                 | 1         | 0.4%    |
| Stronsdorf             | 1         | 0.4%    |
| Strasbourg             | 1         | 0.4%    |
| Stockton               | 1         | 0.4%    |
| Stare Kozle            | 1         | 0.4%    |
| Sofia                  | 1         | 0.4%    |
| Sioux City             | 1         | 0.4%    |
| Sindelfingen           | 1         | 0.4%    |
| Shetland Islands       | 1         | 0.4%    |
| Semarang               | 1         | 0.4%    |
| Scottsdale             | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 50        | 60     | 16.03%  |
| Seagate                   | 34        | 34     | 10.9%   |
| WDC                       | 25        | 29     | 8.01%   |
| SanDisk                   | 24        | 25     | 7.69%   |
| Toshiba                   | 22        | 22     | 7.05%   |
| Unknown                   | 16        | 18     | 5.13%   |
| Kingston                  | 16        | 19     | 5.13%   |
| Crucial                   | 13        | 14     | 4.17%   |
| SK Hynix                  | 11        | 12     | 3.53%   |
| Apple                     | 11        | 11     | 3.53%   |
| HGST                      | 10        | 10     | 3.21%   |
| Intel                     | 9         | 10     | 2.88%   |
| Hitachi                   | 6         | 6      | 1.92%   |
| A-DATA Technology         | 5         | 5      | 1.6%    |
| Phison                    | 4         | 4      | 1.28%   |
| Micron Technology         | 4         | 4      | 1.28%   |
| KIOXIA                    | 4         | 4      | 1.28%   |
| Unknown                   | 4         | 4      | 1.28%   |
| Fujitsu                   | 3         | 3      | 0.96%   |
| China                     | 3         | 3      | 0.96%   |
| Transcend                 | 2         | 2      | 0.64%   |
| TO Exter                  | 2         | 2      | 0.64%   |
| OCZ                       | 2         | 2      | 0.64%   |
| LITEON                    | 2         | 2      | 0.64%   |
| KingDian                  | 2         | 2      | 0.64%   |
| JMicron                   | 2         | 2      | 0.64%   |
| Teclast                   | 1         | 1      | 0.32%   |
| Team                      | 1         | 1      | 0.32%   |
| Star Drive                | 1         | 1      | 0.32%   |
| Star                      | 1         | 1      | 0.32%   |
| SSSTC                     | 1         | 1      | 0.32%   |
| SSK                       | 1         | 1      | 0.32%   |
| SSDPR-CX                  | 1         | 1      | 0.32%   |
| SPCC                      | 1         | 1      | 0.32%   |
| Smartbuy                  | 1         | 1      | 0.32%   |
| Silicon Motion            | 1         | 1      | 0.32%   |
| SABRENT                   | 1         | 1      | 0.32%   |
| PNY                       | 1         | 2      | 0.32%   |
| Pichau                    | 1         | 1      | 0.32%   |
| OSCOO                     | 1         | 1      | 0.32%   |
| NGFF                      | 1         | 1      | 0.32%   |
| Netac                     | 1         | 1      | 0.32%   |
| Micron/Crucial Technology | 1         | 1      | 0.32%   |
| MENGMI                    | 1         | 1      | 0.32%   |
| Leven                     | 1         | 1      | 0.32%   |
| KingSpec                  | 1         | 1      | 0.32%   |
| Kingchuxing               | 1         | 1      | 0.32%   |
| GOODRAM                   | 1         | 1      | 0.32%   |
| FORESEE                   | 1         | 1      | 0.32%   |
| Dogfish                   | 1         | 1      | 0.32%   |
| Colorful                  | 1         | 1      | 0.32%   |
| asmedia                   | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 8         | 2.5%    |
| Samsung NVMe SSD Drive 512GB         | 7         | 2.19%   |
| Sandisk NVMe SSD Drive 512GB         | 6         | 1.88%   |
| Samsung NVMe SSD Drive 256GB         | 6         | 1.88%   |
| Unknown MMC Card  32GB               | 4         | 1.25%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.25%   |
| Seagate ST500LT012-1DG142 500GB      | 4         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.25%   |
| Samsung NVMe SSD Drive 1024GB        | 4         | 1.25%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 1.25%   |
| Intel NVMe SSD Drive 512GB           | 4         | 1.25%   |
| Unknown                              | 4         | 1.25%   |
| Unknown MMC Card  64GB               | 3         | 0.94%   |
| Unknown MMC Card  128GB              | 3         | 0.94%   |
| Toshiba MQ04ABF100 1TB               | 3         | 0.94%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.94%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD  | 3         | 0.94%   |
| SK Hynix NVMe SSD Drive 512GB        | 3         | 0.94%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.94%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.94%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 3         | 0.94%   |
| HGST HTS541010B7E610 1TB             | 3         | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.63%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.63%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.63%   |
| TO Exter nal USB 3.0 320GB           | 2         | 0.63%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 0.63%   |
| Seagate ST980811AS 80GB              | 2         | 0.63%   |
| Seagate ST9750420AS 752GB            | 2         | 0.63%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 0.63%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD  | 2         | 0.63%   |
| Sandisk NVMe SSD Drive 1024GB        | 2         | 0.63%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.63%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.63%   |
| Samsung SSD 850 EVO 120GB            | 2         | 0.63%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 2         | 0.63%   |
| Phison NVMe SSD Drive 512GB          | 2         | 0.63%   |
| Phison NVMe SSD Drive 1TB            | 2         | 0.63%   |
| OCZ VERTEX3 120GB SSD                | 2         | 0.63%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.63%   |
| Kingston NVMe SSD Drive 500GB        | 2         | 0.63%   |
| Intel NVMe SSD Drive 1024GB          | 2         | 0.63%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.63%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.63%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.63%   |
| Apple SSD SM0512G 500GB              | 2         | 0.63%   |
| A-DATA SU650 120GB SSD               | 2         | 0.63%   |
| WDC WDS500G2B0B 500GB SSD            | 1         | 0.31%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.31%   |
| WDC WDS200T2B0A-00SM50 2TB SSD       | 1         | 0.31%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.31%   |
| WDC WD7500BPVT-22A1YT0 752GB         | 1         | 0.31%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.31%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.31%   |
| WDC WD5000LPVT-08G33T1 500GB         | 1         | 0.31%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.31%   |
| WDC WD5000BPVT-22HXZT1 500GB         | 1         | 0.31%   |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 0.31%   |
| WDC WD3200BEVT-75A23T0 320GB         | 1         | 0.31%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 34        | 34     | 39.08%  |
| WDC     | 16        | 19     | 18.39%  |
| Toshiba | 15        | 15     | 17.24%  |
| HGST    | 10        | 10     | 11.49%  |
| Hitachi | 6         | 6      | 6.9%    |
| Fujitsu | 3         | 3      | 3.45%   |
| Unknown | 1         | 1      | 1.15%   |
| SABRENT | 1         | 1      | 1.15%   |
| Apple   | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 33     | 23.97%  |
| Crucial             | 13        | 14     | 10.74%  |
| SanDisk             | 12        | 13     | 9.92%   |
| Kingston            | 10        | 10     | 8.26%   |
| Apple               | 9         | 9      | 7.44%   |
| WDC                 | 6         | 6      | 4.96%   |
| Micron Technology   | 4         | 4      | 3.31%   |
| A-DATA Technology   | 4         | 4      | 3.31%   |
| China               | 3         | 3      | 2.48%   |
| Transcend           | 2         | 2      | 1.65%   |
| Toshiba             | 2         | 2      | 1.65%   |
| TO Exter            | 2         | 2      | 1.65%   |
| OCZ                 | 2         | 2      | 1.65%   |
| LITEON              | 2         | 2      | 1.65%   |
| Intel               | 2         | 2      | 1.65%   |
| Teclast             | 1         | 1      | 0.83%   |
| Team                | 1         | 1      | 0.83%   |
| Star                | 1         | 1      | 0.83%   |
| SPCC                | 1         | 1      | 0.83%   |
| Smartbuy            | 1         | 1      | 0.83%   |
| SK Hynix            | 1         | 1      | 0.83%   |
| PNY                 | 1         | 2      | 0.83%   |
| Pichau              | 1         | 1      | 0.83%   |
| NGFF                | 1         | 1      | 0.83%   |
| Netac               | 1         | 1      | 0.83%   |
| MENGMI              | 1         | 1      | 0.83%   |
| KingSpec            | 1         | 1      | 0.83%   |
| KingDian            | 1         | 1      | 0.83%   |
| JMicron             | 1         | 1      | 0.83%   |
| GOODRAM             | 1         | 1      | 0.83%   |
| FORESEE             | 1         | 1      | 0.83%   |
| Dogfish             | 1         | 1      | 0.83%   |
| Colorful            | 1         | 1      | 0.83%   |
| Unknown             | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 115       | 128    | 37.95%  |
| HDD     | 86        | 90     | 28.38%  |
| NVMe    | 75        | 90     | 24.75%  |
| MMC     | 17        | 18     | 5.61%   |
| Unknown | 10        | 10     | 3.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 182       | 214    | 63.41%  |
| NVMe | 75        | 90     | 26.13%  |
| MMC  | 17        | 18     | 5.92%   |
| SAS  | 13        | 14     | 4.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 165    | 74.62%  |
| 0.51-1.0   | 43        | 44     | 21.83%  |
| 1.01-2.0   | 5         | 7      | 2.54%   |
| 4.01-10.0  | 2         | 2      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 103       | 41.53%  |
| 251-500        | 67        | 27.02%  |
| 501-1000       | 33        | 13.31%  |
| 51-100         | 20        | 8.06%   |
| 21-50          | 12        | 4.84%   |
| 1001-2000      | 11        | 4.44%   |
| More than 3000 | 1         | 0.4%    |
| Unknown        | 1         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 120       | 47.43%  |
| 21-50     | 67        | 26.48%  |
| 51-100    | 28        | 11.07%  |
| 101-250   | 22        | 8.7%    |
| 251-500   | 7         | 2.77%   |
| 501-1000  | 6         | 2.37%   |
| 2001-3000 | 1         | 0.4%    |
| 1001-2000 | 1         | 0.4%    |
| Unknown   | 1         | 0.4%    |

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
| Detected | 222       | 284    | 83.77%  |
| Works    | 40        | 49     | 15.09%  |
| Malfunc  | 3         | 3      | 1.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 173       | 61.57%  |
| Samsung Electronics            | 25        | 8.9%    |
| AMD                            | 25        | 8.9%    |
| Sandisk                        | 14        | 4.98%   |
| SK Hynix                       | 10        | 3.56%   |
| Nvidia                         | 9         | 3.2%    |
| Kingston Technology Company    | 7         | 2.49%   |
| Toshiba America Info Systems   | 5         | 1.78%   |
| Phison Electronics             | 5         | 1.78%   |
| KIOXIA                         | 2         | 0.71%   |
| Solid State Storage Technology | 1         | 0.36%   |
| Silicon Motion                 | 1         | 0.36%   |
| Micron/Crucial Technology      | 1         | 0.36%   |
| Marvell Technology Group       | 1         | 0.36%   |
| Apple                          | 1         | 0.36%   |
| ADATA Technology               | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 25        | 8.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 22        | 7.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 20        | 6.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 19        | 6.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 11        | 3.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 10        | 3.37%   |
| Samsung NVMe SSD Controller 980                                                        | 9         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 7         | 2.36%   |
| Nvidia MCP79 AHCI Controller                                                           | 7         | 2.36%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 7         | 2.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 2.36%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 6         | 2.02%   |
| Intel SSD 660P Series                                                                  | 6         | 2.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 6         | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 2.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 6         | 2.02%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 1.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.68%   |
| SK Hynix BC511                                                                         | 4         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 4         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 4         | 1.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 1.01%   |
| SK Hynix Gold P31 SSD                                                                  | 3         | 1.01%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.01%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 3         | 1.01%   |
| Samsung Electronics SATA controller                                                    | 3         | 1.01%   |
| Phison E12 NVMe Controller                                                             | 3         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 3         | 1.01%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.67%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.67%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.67%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.67%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.67%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 2         | 0.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.67%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.34%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.34%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.34%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.34%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.34%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 0.34%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 0.34%   |
| Phison NVMe Storage Controller                                                         | 1         | 0.34%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.34%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.34%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                        | 1         | 0.34%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 1         | 0.34%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.34%   |
| Kingston Company KC2000 NVMe SSD                                                       | 1         | 0.34%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.34%   |
| Intel NVMe Optane Memory Series                                                        | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 188       | 65.73%  |
| NVMe | 73        | 25.52%  |
| IDE  | 13        | 4.55%   |
| RAID | 12        | 4.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 210       | 84.68%  |
| AMD    | 38        | 15.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 10        | 4.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 7         | 2.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 7         | 2.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 5         | 2.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 5         | 2.02%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 5         | 2.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 4         | 1.61%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 4         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 4         | 1.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 4         | 1.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.21%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 1.21%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.21%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 1.21%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 3         | 1.21%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz            | 3         | 1.21%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 3         | 1.21%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz         | 3         | 1.21%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 3         | 1.21%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.21%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 1.21%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 0.81%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 2         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 0.81%   |
| Intel Core i7-5650U CPU @ 2.20GHz               | 2         | 0.81%   |
| Intel Core i7-3635QM CPU @ 2.40GHz              | 2         | 0.81%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.81%   |
| Intel Core i7-2635QM CPU @ 2.00GHz              | 2         | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 2         | 0.81%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 2         | 0.81%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 2         | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 0.81%   |
| Intel Core i5 CPU M 460 @ 2.53GHz               | 2         | 0.81%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 2         | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 0.81%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 2         | 0.81%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 2         | 0.81%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 2         | 0.81%   |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 2         | 0.81%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz            | 2         | 0.81%   |
| Intel Celeron Dual-Core CPU T3000 @ 1.80GHz     | 2         | 0.81%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 0.81%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 0.81%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 2         | 0.81%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 2         | 0.81%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G    | 2         | 0.81%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.81%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 1         | 0.4%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.4%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 0.4%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 1         | 0.4%    |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1         | 0.4%    |
| Intel Genuine CPU U7300 @ 1.30GHz               | 1         | 0.4%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz                | 1         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 63        | 25.4%   |
| Intel Core i7           | 54        | 21.77%  |
| Intel Core i3           | 24        | 9.68%   |
| Other                   | 20        | 8.06%   |
| Intel Celeron           | 20        | 8.06%   |
| Intel Core 2 Duo        | 16        | 6.45%   |
| AMD Ryzen 5             | 13        | 5.24%   |
| AMD Ryzen 7             | 4         | 1.61%   |
| Intel Pentium Silver    | 3         | 1.21%   |
| Intel Pentium           | 3         | 1.21%   |
| AMD Ryzen 7 PRO         | 3         | 1.21%   |
| AMD Ryzen 3             | 3         | 1.21%   |
| AMD A6                  | 3         | 1.21%   |
| Intel Pentium Dual-Core | 2         | 0.81%   |
| Intel Celeron Dual-Core | 2         | 0.81%   |
| AMD A8                  | 2         | 0.81%   |
| AMD A12                 | 2         | 0.81%   |
| AMD A10                 | 2         | 0.81%   |
| Intel Pentium Dual      | 1         | 0.4%    |
| Intel Genuine           | 1         | 0.4%    |
| Intel Core m5           | 1         | 0.4%    |
| Intel Core 2 Quad       | 1         | 0.4%    |
| Intel Core 2            | 1         | 0.4%    |
| Intel Atom              | 1         | 0.4%    |
| AMD Ryzen 9             | 1         | 0.4%    |
| AMD E1                  | 1         | 0.4%    |
| AMD A4                  | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 138       | 55.65%  |
| 4      | 89        | 35.89%  |
| 6      | 12        | 4.84%   |
| 8      | 8         | 3.23%   |
| 1      | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 248       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 182       | 73.39%  |
| 1      | 66        | 26.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 248       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 23        | 9.2%    |
| 0x306a9    | 18        | 7.2%    |
| Unknown    | 18        | 7.2%    |
| 0x806c1    | 14        | 5.6%    |
| 0x306d4    | 13        | 5.2%    |
| 0x1067a    | 13        | 5.2%    |
| 0x806ec    | 10        | 4%      |
| 0x40651    | 10        | 4%      |
| 0x406e3    | 9         | 3.6%    |
| 0x20655    | 9         | 3.6%    |
| 0x806e9    | 8         | 3.2%    |
| 0x10676    | 7         | 2.8%    |
| 0x806ea    | 6         | 2.4%    |
| 0x706a8    | 6         | 2.4%    |
| 0x406c3    | 6         | 2.4%    |
| 0x08600106 | 6         | 2.4%    |
| 0x506c9    | 5         | 2%      |
| 0x306c3    | 5         | 2%      |
| 0x20652    | 5         | 2%      |
| 0x806eb    | 4         | 1.6%    |
| 0x08108109 | 4         | 1.6%    |
| 0x06006705 | 4         | 1.6%    |
| 0xa0652    | 3         | 1.2%    |
| 0x906ea    | 3         | 1.2%    |
| 0x6fd      | 3         | 1.2%    |
| 0x08608103 | 3         | 1.2%    |
| 0x08108102 | 3         | 1.2%    |
| 0x906e9    | 2         | 0.8%    |
| 0x806c2    | 2         | 0.8%    |
| 0x706e5    | 2         | 0.8%    |
| 0x706a1    | 2         | 0.8%    |
| 0x506e3    | 2         | 0.8%    |
| 0x0a50000c | 2         | 0.8%    |
| 0x08101007 | 2         | 0.8%    |
| 0x0700010f | 2         | 0.8%    |
| 0x06001119 | 2         | 0.8%    |
| 0xa0660    | 1         | 0.4%    |
| 0x906ed    | 1         | 0.4%    |
| 0x906c0    | 1         | 0.4%    |
| 0x6fb      | 1         | 0.4%    |
| 0x6f2      | 1         | 0.4%    |
| 0x40661    | 1         | 0.4%    |
| 0x30678    | 1         | 0.4%    |
| 0x106e5    | 1         | 0.4%    |
| 0x0810100b | 1         | 0.4%    |
| 0x07030105 | 1         | 0.4%    |
| 0x07030104 | 1         | 0.4%    |
| 0x06006704 | 1         | 0.4%    |
| 0x0600611a | 1         | 0.4%    |
| 0x06006110 | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 40        | 16.13%  |
| SandyBridge   | 24        | 9.68%   |
| Penryn        | 20        | 8.06%   |
| IvyBridge     | 18        | 7.26%   |
| Haswell       | 18        | 7.26%   |
| TigerLake     | 17        | 6.85%   |
| Westmere      | 14        | 5.65%   |
| Broadwell     | 13        | 5.24%   |
| Skylake       | 12        | 4.84%   |
| Zen 2         | 8         | 3.23%   |
| Silvermont    | 8         | 3.23%   |
| Goldmont plus | 8         | 3.23%   |
| Excavator     | 8         | 3.23%   |
| Zen+          | 7         | 2.82%   |
| Goldmont      | 5         | 2.02%   |
| Core          | 5         | 2.02%   |
| CometLake     | 4         | 1.61%   |
| Unknown       | 4         | 1.61%   |
| Zen           | 3         | 1.21%   |
| Zen 3         | 2         | 0.81%   |
| Puma          | 2         | 0.81%   |
| Piledriver    | 2         | 0.81%   |
| Jaguar        | 2         | 0.81%   |
| IceLake       | 2         | 0.81%   |
| Tremont       | 1         | 0.4%    |
| Nehalem       | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 191       | 61.61%  |
| Nvidia | 64        | 20.65%  |
| AMD    | 55        | 17.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 6.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 5.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 5.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 3.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 3.12%   |
| Intel HD Graphics 5500                                                                   | 10        | 3.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 3.12%   |
| Intel HD Graphics 620                                                                    | 9         | 2.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.49%   |
| AMD Renoir                                                                               | 8         | 2.49%   |
| Nvidia C79 [GeForce 9400M]                                                               | 7         | 2.18%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.25%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.25%   |
| AMD Lucienne                                                                             | 4         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.93%   |
| Intel HD Graphics 6000                                                                   | 3         | 0.93%   |
| Intel HD Graphics 500                                                                    | 3         | 0.93%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.93%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.93%   |
| Nvidia TU117M                                                                            | 2         | 0.62%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.62%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.62%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.62%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.62%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.62%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.62%   |
| Intel HD Graphics 630                                                                    | 2         | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2         | 0.62%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.62%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 2         | 0.62%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 0.62%   |
| AMD Cezanne                                                                              | 2         | 0.62%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.31%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.31%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.31%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.31%   |
| Nvidia GT218M [GeForce G210M]                                                            | 1         | 0.31%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.31%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.31%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.31%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 131       | 52.82%  |
| Intel + Nvidia | 48        | 19.35%  |
| 1 x AMD        | 35        | 14.11%  |
| 1 x Nvidia     | 13        | 5.24%   |
| Intel + AMD    | 12        | 4.84%   |
| 2 x AMD        | 6         | 2.42%   |
| AMD + Nvidia   | 2         | 0.81%   |
| 2 x Nvidia     | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 220       | 88.71%  |
| Proprietary | 26        | 10.48%  |
| Unknown     | 2         | 0.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 60.89%  |
| 0.01-0.5   | 37        | 14.92%  |
| 1.01-2.0   | 28        | 11.29%  |
| 0.51-1.0   | 20        | 8.06%   |
| 3.01-4.0   | 10        | 4.03%   |
| 5.01-6.0   | 2         | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 18.73%  |
| LG Display              | 44        | 15.55%  |
| Chimei Innolux          | 39        | 13.78%  |
| Apple                   | 30        | 10.6%   |
| BOE                     | 27        | 9.54%   |
| Samsung Electronics     | 24        | 8.48%   |
| Lenovo                  | 8         | 2.83%   |
| Sharp                   | 7         | 2.47%   |
| PANDA                   | 6         | 2.12%   |
| Dell                    | 6         | 2.12%   |
| Hewlett-Packard         | 5         | 1.77%   |
| Goldstar                | 5         | 1.77%   |
| CSO                     | 4         | 1.41%   |
| Chi Mei Optoelectronics | 3         | 1.06%   |
| InfoVision              | 2         | 0.71%   |
| AOC                     | 2         | 0.71%   |
| Acer                    | 2         | 0.71%   |
| ViewSonic               | 1         | 0.35%   |
| Toshiba                 | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| Plain Tree Systems      | 1         | 0.35%   |
| Philips                 | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| Packard Bell            | 1         | 0.35%   |
| Konka                   | 1         | 0.35%   |
| JDI                     | 1         | 0.35%   |
| HUAWEI                  | 1         | 0.35%   |
| HJC                     | 1         | 0.35%   |
| EXP                     | 1         | 0.35%   |
| DPL                     | 1         | 0.35%   |
| CPT                     | 1         | 0.35%   |
| BenQ                    | 1         | 0.35%   |
| Ancor Communications    | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 3         | 1.03%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 1.03%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.03%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.03%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 1.03%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 1.03%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.69%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.69%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.69%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.69%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 2         | 0.69%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 344x193mm 15.5-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.69%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.69%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.69%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 0.69%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.69%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 2         | 0.69%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.34%   |
| Toshiba TV TSB2019 3840x2160                                          | 1         | 0.34%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.34%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.34%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.34%   |
| Samsung Electronics SyncMaster SAM00C8 1280x1024 338x270mm 17.0-inch  | 1         | 0.34%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3142 1280x800 261x163mm 12.1-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4259 1920x1080 293x165mm 13.2-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.34%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 108       | 40%     |
| 1366x768 (WXGA)    | 84        | 31.11%  |
| 1600x900 (HD+)     | 13        | 4.81%   |
| 1440x900 (WXGA+)   | 13        | 4.81%   |
| 1280x800 (WXGA)    | 13        | 4.81%   |
| 3840x2160 (4K)     | 11        | 4.07%   |
| 2560x1440 (QHD)    | 8         | 2.96%   |
| 3000x2000          | 4         | 1.48%   |
| 2880x1800          | 2         | 0.74%   |
| 2560x1600          | 2         | 0.74%   |
| 2560x1080          | 2         | 0.74%   |
| 1920x1200 (WUXGA)  | 2         | 0.74%   |
| 3840x2400          | 1         | 0.37%   |
| 3200x1800 (QHD+)   | 1         | 0.37%   |
| 3072x1920          | 1         | 0.37%   |
| 1920x1280          | 1         | 0.37%   |
| 1680x1050 (WSXGA+) | 1         | 0.37%   |
| 1400x1050          | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |
| 1280x1024 (SXGA)   | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 107       | 37.41%  |
| 13      | 59        | 20.63%  |
| 14      | 42        | 14.69%  |
| 17      | 17        | 5.94%   |
| 27      | 9         | 3.15%   |
| 23      | 9         | 3.15%   |
| 11      | 9         | 3.15%   |
| 24      | 7         | 2.45%   |
| 12      | 6         | 2.1%    |
| 84      | 2         | 0.7%    |
| 52      | 2         | 0.7%    |
| 34      | 2         | 0.7%    |
| 31      | 2         | 0.7%    |
| 25      | 2         | 0.7%    |
| 18      | 2         | 0.7%    |
| 16      | 2         | 0.7%    |
| Unknown | 2         | 0.7%    |
| 72      | 1         | 0.35%   |
| 47      | 1         | 0.35%   |
| 26      | 1         | 0.35%   |
| 21      | 1         | 0.35%   |
| 20      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 61.7%   |
| 201-300     | 48        | 17.02%  |
| 501-600     | 25        | 8.87%   |
| 351-400     | 19        | 6.74%   |
| 401-500     | 4         | 1.42%   |
| 1501-2000   | 3         | 1.06%   |
| 1001-1500   | 3         | 1.06%   |
| 701-800     | 2         | 0.71%   |
| 601-700     | 2         | 0.71%   |
| Unknown     | 2         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 208       | 81.57%  |
| 16/10   | 35        | 13.73%  |
| 3/2     | 7         | 2.75%   |
| 21/9    | 2         | 0.78%   |
| 5/4     | 1         | 0.39%   |
| 4/3     | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 105       | 37.1%   |
| 81-90          | 81        | 28.62%  |
| 71-80          | 20        | 7.07%   |
| 201-250        | 13        | 4.59%   |
| 121-130        | 13        | 4.59%   |
| 51-60          | 9         | 3.18%   |
| 301-350        | 9         | 3.18%   |
| 61-70          | 6         | 2.12%   |
| More than 1000 | 5         | 1.77%   |
| 351-500        | 4         | 1.41%   |
| 251-300        | 4         | 1.41%   |
| 141-150        | 3         | 1.06%   |
| 131-140        | 3         | 1.06%   |
| 111-120        | 3         | 1.06%   |
| Unknown        | 2         | 0.71%   |
| 151-200        | 1         | 0.35%   |
| 501-1000       | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 120       | 42.86%  |
| 101-120       | 93        | 33.21%  |
| 51-100        | 34        | 12.14%  |
| 161-240       | 18        | 6.43%   |
| More than 240 | 10        | 3.57%   |
| 1-50          | 3         | 1.07%   |
| Unknown       | 2         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 213       | 85.2%   |
| 2     | 29        | 11.6%   |
| 3     | 6         | 2.4%    |
| 4     | 1         | 0.4%    |
| 0     | 1         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 124       | 33.42%  |
| Realtek Semiconductor             | 106       | 28.57%  |
| Qualcomm Atheros                  | 51        | 13.75%  |
| Broadcom                          | 41        | 11.05%  |
| Broadcom Limited                  | 9         | 2.43%   |
| Nvidia                            | 8         | 2.16%   |
| Marvell Technology Group          | 7         | 1.89%   |
| Ralink                            | 3         | 0.81%   |
| Xiaomi                            | 2         | 0.54%   |
| TP-Link                           | 2         | 0.54%   |
| Ralink Technology                 | 2         | 0.54%   |
| Lenovo                            | 2         | 0.54%   |
| Google                            | 2         | 0.54%   |
| ASIX Electronics                  | 2         | 0.54%   |
| Sitecom Europe                    | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| OPPO Electronics                  | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.27%   |
| MEDIATEK                          | 1         | 0.27%   |
| Huawei Technologies               | 1         | 0.27%   |
| Hewlett-Packard                   | 1         | 0.27%   |
| Ericsson Business Mobile Networks | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| Apple                             | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 64        | 14.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 4.75%   |
| Intel Wi-Fi 6 AX201                                                            | 14        | 3.17%   |
| Intel Wireless 8260                                                            | 12        | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 11        | 2.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 11        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 10        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 10        | 2.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 10        | 2.26%   |
| Nvidia MCP79 Ethernet                                                          | 8         | 1.81%   |
| Intel Wireless 8265 / 8275                                                     | 8         | 1.81%   |
| Intel Wireless 7260                                                            | 8         | 1.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 1.81%   |
| Intel Wireless 7265                                                            | 7         | 1.58%   |
| Intel Wi-Fi 6 AX200                                                            | 7         | 1.58%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 7         | 1.58%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 7         | 1.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 7         | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 6         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 1.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 5         | 1.13%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 5         | 1.13%   |
| Intel Centrino Advanced-N 6200                                                 | 5         | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 1.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                     | 5         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 4         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 0.9%    |
| Intel Wireless 3165                                                            | 4         | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                                  | 4         | 0.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                              | 4         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 3         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 3         | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 0.68%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.68%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 3         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 3         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.68%   |
| Broadcom BCM4321 802.11a/b/g/n                                                 | 3         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 2         | 0.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2         | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 2         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.45%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.45%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.45%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.45%   |
| Intel Wireless 3160                                                            | 2         | 0.45%   |
| Intel Ultimate N WiFi Link 5300                                                | 2         | 0.45%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 119       | 46.85%  |
| Qualcomm Atheros      | 44        | 17.32%  |
| Broadcom              | 39        | 15.35%  |
| Realtek Semiconductor | 32        | 12.6%   |
| Broadcom Limited      | 9         | 3.54%   |
| Ralink                | 3         | 1.18%   |
| TP-Link               | 2         | 0.79%   |
| Ralink Technology     | 2         | 0.79%   |
| Sitecom Europe        | 1         | 0.39%   |
| Sierra Wireless       | 1         | 0.39%   |
| MEDIATEK              | 1         | 0.39%   |
| D-Link                | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                                   | 14        | 5.49%   |
| Intel Wireless 8260                                                                   | 12        | 4.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 11        | 4.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 11        | 4.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 10        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 10        | 3.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 10        | 3.92%   |
| Intel Wireless 8265 / 8275                                                            | 8         | 3.14%   |
| Intel Wireless 7260                                                                   | 8         | 3.14%   |
| Intel Wireless 7265                                                                   | 7         | 2.75%   |
| Intel Wi-Fi 6 AX200                                                                   | 7         | 2.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 7         | 2.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 7         | 2.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 7         | 2.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 6         | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 6         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 5         | 1.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 5         | 1.96%   |
| Intel Centrino Advanced-N 6200                                                        | 5         | 1.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 5         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 5         | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 4         | 1.57%   |
| Intel Wireless 3165                                                                   | 4         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 4         | 1.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 4         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 3         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 3         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 3         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 3         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 3         | 1.18%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 3         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 2         | 0.78%   |
| Intel Wireless-AC 9260                                                                | 2         | 0.78%   |
| Intel Wireless 3160                                                                   | 2         | 0.78%   |
| Intel Ultimate N WiFi Link 5300                                                       | 2         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 0.78%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 0.78%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 2         | 0.78%   |
| Broadcom BCM43227 802.11b/g/n                                                         | 2         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 2         | 0.78%   |
| TP-Link 802.11n NIC                                                                   | 1         | 0.39%   |
| TP-Link 802.11ac WLAN Adapter                                                         | 1         | 0.39%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N                              | 1         | 0.39%   |
| Sierra Wireless EM7455                                                                | 1         | 0.39%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.39%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.39%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.39%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.39%   |
| Realtek Realtek Network controller                                                    | 1         | 0.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 1         | 0.39%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.39%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.39%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.39%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                         | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 93        | 51.1%   |
| Intel                    | 37        | 20.33%  |
| Broadcom                 | 13        | 7.14%   |
| Qualcomm Atheros         | 12        | 6.59%   |
| Nvidia                   | 8         | 4.4%    |
| Marvell Technology Group | 7         | 3.85%   |
| Xiaomi                   | 2         | 1.1%    |
| Lenovo                   | 2         | 1.1%    |
| Google                   | 2         | 1.1%    |
| ASIX Electronics         | 2         | 1.1%    |
| OPPO Electronics         | 1         | 0.55%   |
| Hewlett-Packard          | 1         | 0.55%   |
| Broadcom Limited         | 1         | 0.55%   |
| Apple                    | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 64        | 34.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 11.41%  |
| Nvidia MCP79 Ethernet                                                          | 8         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 8         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 3.26%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 3.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 2.17%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.63%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.63%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.09%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.09%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.09%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.09%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 1.09%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.09%   |
| Lenovo ThinkPad Lan                                                            | 2         | 1.09%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.09%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.09%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 1.09%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.09%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.09%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.54%   |
| OPPO realme X50 5G                                                             | 1         | 0.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.54%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.54%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.54%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.54%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.54%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.54%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.54%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.54%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.54%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.54%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.54%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.54%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.54%   |
| Apple T2 Controller                                                            | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 246       | 58.16%  |
| Ethernet | 174       | 41.13%  |
| Modem    | 2         | 0.47%   |
| Unknown  | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 81.1%   |
| Ethernet | 48        | 18.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 160       | 64.52%  |
| 1     | 85        | 34.27%  |
| 3     | 2         | 0.81%   |
| 0     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 173       | 69.2%   |
| Yes  | 77        | 30.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 44.25%  |
| Apple                           | 29        | 12.83%  |
| Realtek Semiconductor           | 23        | 10.18%  |
| Qualcomm Atheros Communications | 14        | 6.19%   |
| Broadcom                        | 14        | 6.19%   |
| Lite-On Technology              | 11        | 4.87%   |
| IMC Networks                    | 9         | 3.98%   |
| Foxconn / Hon Hai               | 7         | 3.1%    |
| Hewlett-Packard                 | 6         | 2.65%   |
| Cambridge Silicon Radio         | 4         | 1.77%   |
| Toshiba                         | 3         | 1.33%   |
| Realtek                         | 2         | 0.88%   |
| Ralink                          | 2         | 0.88%   |
| Dell                            | 1         | 0.44%   |
| ASUSTek Computer                | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 43        | 19.03%  |
| Intel AX201 Bluetooth                                                               | 22        | 9.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 7.96%   |
| Apple Bluetooth Host Controller                                                     | 15        | 6.64%   |
| Realtek Bluetooth Radio                                                             | 14        | 6.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 3.98%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 3.98%   |
| Intel AX200 Bluetooth                                                               | 7         | 3.1%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.65%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.77%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.33%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.33%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.33%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 1.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 1.33%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 0.88%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.88%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.88%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.88%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.88%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.88%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.88%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.44%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.44%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.44%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.44%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.44%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.44%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.44%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.44%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.44%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.44%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.44%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 199       | 68.38%  |
| AMD                     | 48        | 16.49%  |
| Nvidia                  | 31        | 10.65%  |
| Logitech                | 2         | 0.69%   |
| ESS Technology          | 2         | 0.69%   |
| Texas Instruments       | 1         | 0.34%   |
| SteelSeries ApS         | 1         | 0.34%   |
| Realtek Semiconductor   | 1         | 0.34%   |
| No brand                | 1         | 0.34%   |
| Generalplus Technology  | 1         | 0.34%   |
| Dell                    | 1         | 0.34%   |
| C-Media Electronics     | 1         | 0.34%   |
| BEHRINGER International | 1         | 0.34%   |
| Apple                   | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 7.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 6.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 5.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 4.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 4.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 3.62%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 3.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 3.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 3.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.06%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 2.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 8         | 2.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 2.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.39%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.11%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.84%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.84%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.56%   |
| ESS Technology Asus USB DAC                                                                       | 2         | 0.56%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.56%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.28%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                                     | 1         | 0.28%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia Audio device                                                                               | 1         | 0.28%   |
| No brand CalDigit Thunderbolt 3 Audio                                                             | 1         | 0.28%   |
| Logitech G430 Surround Sound Gaming Headset                                                       | 1         | 0.28%   |
| Logitech 960 Headset                                                                              | 1         | 0.28%   |
| Intel UNA USB audio                                                                               | 1         | 0.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 0.28%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.28%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.28%   |
| Dell PROFESSIONAL SOUND BAR AE515                                                                 | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 21        | 41.18%  |
| SK Hynix            | 10        | 19.61%  |
| Micron Technology   | 9         | 17.65%  |
| Unknown             | 2         | 3.92%   |
| G.Skill             | 2         | 3.92%   |
| SHARETRONIC         | 1         | 1.96%   |
| Ramaxel Technology  | 1         | 1.96%   |
| Kingston            | 1         | 1.96%   |
| GSkill              | 1         | 1.96%   |
| ELPIDA              | 1         | 1.96%   |
| Crucial             | 1         | 1.96%   |
| A-DATA Technology   | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 3.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 2         | 3.39%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 3.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 3.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 3.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3                          | 1         | 1.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.69%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                | 1         | 1.69%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s              | 1         | 1.69%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.69%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s        | 1         | 1.69%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 1.69%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s      | 1         | 1.69%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s      | 1         | 1.69%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.69%   |
| SK Hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s         | 1         | 1.69%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 1.69%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s             | 1         | 1.69%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.69%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                 | 1         | 1.69%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.69%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM 1600MT/s               | 1         | 1.69%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 1.69%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.69%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s          | 1         | 1.69%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s          | 1         | 1.69%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s   | 1         | 1.69%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.69%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.69%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s          | 1         | 1.69%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 1         | 1.69%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s      | 1         | 1.69%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.69%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.69%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.69%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 1         | 1.69%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.69%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.69%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.69%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.69%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 1         | 1.69%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s       | 1         | 1.69%   |
| Kingston RAM KHYXPX-HYJ 8GB SODIMM DDR4 2667MT/s               | 1         | 1.69%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.69%   |
| G.Skill RAM F4-2666C18-16GRS 16GB SODIMM DDR4 2667MT/s         | 1         | 1.69%   |
| G.Skill RAM F3-1600C11-8GSQ 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.69%   |
| G.Skill RAM F3-1600C11-8GSL 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.69%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s       | 1         | 1.69%   |
| Crucial RAM CB8GS2400.C8D 8GB SODIMM DDR4 2400MT/s             | 1         | 1.69%   |
| A-DATA RAM AM1U16BC4P2-B19N 4GB SODIMM DDR3 1600MT/s           | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 24        | 50%     |
| DDR3   | 16        | 33.33%  |
| LPDDR4 | 6         | 12.5%   |
| LPDDR3 | 2         | 4.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 41        | 85.42%  |
| Row Of Chips | 6         | 12.5%   |
| Chip         | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 25        | 46.3%   |
| 4096  | 18        | 33.33%  |
| 2048  | 7         | 12.96%  |
| 16384 | 4         | 7.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 13        | 25.49%  |
| 2667    | 11        | 21.57%  |
| 3200    | 8         | 15.69%  |
| 4267    | 4         | 7.84%   |
| 2400    | 4         | 7.84%   |
| 2133    | 3         | 5.88%   |
| 3266    | 2         | 3.92%   |
| 1334    | 2         | 3.92%   |
| 4266    | 1         | 1.96%   |
| 1867    | 1         | 1.96%   |
| 1333    | 1         | 1.96%   |
| Unknown | 1         | 1.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 50%     |
| Samsung Electronics             | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 1         | 25%     |
| Canon PIXMA MG2500 Series                | 1         | 25%     |
| Canon G3000 series                       | 1         | 25%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 25%     |

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
| Chicony Electronics                    | 46        | 19.49%  |
| IMC Networks                           | 31        | 13.14%  |
| Apple                                  | 24        | 10.17%  |
| Realtek Semiconductor                  | 23        | 9.75%   |
| Acer                                   | 19        | 8.05%   |
| Quanta                                 | 13        | 5.51%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.08%   |
| Microdia                               | 10        | 4.24%   |
| Sunplus Innovation Technology          | 9         | 3.81%   |
| Suyin                                  | 8         | 3.39%   |
| Syntek                                 | 7         | 2.97%   |
| Alcor Micro                            | 6         | 2.54%   |
| Silicon Motion                         | 5         | 2.12%   |
| Lenovo                                 | 4         | 1.69%   |
| Luxvisions Innotech Limited            | 3         | 1.27%   |
| Ricoh                                  | 2         | 0.85%   |
| Logitech                               | 2         | 0.85%   |
| KYE Systems (Mouse Systems)            | 2         | 0.85%   |
| Y Media                                | 1         | 0.42%   |
| Unknown                                | 1         | 0.42%   |
| Sony                                   | 1         | 0.42%   |
| Samsung Electronics                    | 1         | 0.42%   |
| Primax Electronics                     | 1         | 0.42%   |
| Lite-On Technology                     | 1         | 0.42%   |
| kingcome                               | 1         | 0.42%   |
| Importek                               | 1         | 0.42%   |
| Google                                 | 1         | 0.42%   |
| Foxconn / Hon Hai                      | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 12        | 5.04%   |
| Apple Built-in iSight                                                      | 10        | 4.2%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 3.78%   |
| IMC Networks Integrated Camera                                             | 9         | 3.78%   |
| Syntek Integrated Camera                                                   | 7         | 2.94%   |
| Chicony HD WebCam                                                          | 7         | 2.94%   |
| Apple FaceTime HD Camera                                                   | 6         | 2.52%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 2.1%    |
| Realtek USB2.0 HD UVC WebCam                                               | 4         | 1.68%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 1.68%   |
| Acer Lenovo EasyCamera                                                     | 4         | 1.68%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 1.26%   |
| Quanta VGA WebCam                                                          | 3         | 1.26%   |
| Quanta HD User Facing                                                      | 3         | 1.26%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 3         | 1.26%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 1.26%   |
| Apple FaceTime Camera                                                      | 3         | 1.26%   |
| Alcor Micro SHUNCCM2MP                                                     | 3         | 1.26%   |
| Acer HD Webcam                                                             | 3         | 1.26%   |
| Acer EasyCamera                                                            | 3         | 1.26%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.84%   |
| Sunplus Asus Webcam                                                        | 2         | 0.84%   |
| Realtek USB Camera                                                         | 2         | 0.84%   |
| Realtek Integrated Webcam                                                  | 2         | 0.84%   |
| Realtek Acer 640 x 480 laptop camera                                       | 2         | 0.84%   |
| Quanta HP Webcam                                                           | 2         | 0.84%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.84%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.84%   |
| Lenovo Integrated Webcam                                                   | 2         | 0.84%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 2         | 0.84%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.84%   |
| IMC Networks EasyCamera                                                    | 2         | 0.84%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.84%   |
| Chicony USB 2.0 Camera                                                     | 2         | 0.84%   |
| Chicony EasyCamera                                                         | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 2         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 2         | 0.84%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 0.84%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 0.84%   |
| Acer Integrated Camera                                                     | 2         | 0.84%   |
| Acer HD Camera                                                             | 2         | 0.84%   |
| Y Media USB Camera                                                         | 1         | 0.42%   |
| Unknown 720p HD Camera                                                     | 1         | 0.42%   |
| Suyin UVC HD Webcam                                                        | 1         | 0.42%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.42%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.42%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.42%   |
| Suyin HD WebCam                                                            | 1         | 0.42%   |
| Suyin Asus Integrated Webcam [CN031B]                                      | 1         | 0.42%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 0.42%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.42%   |
| Sunplus TOSHIBA Web Camera - HD                                            | 1         | 0.42%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 0.42%   |
| Sunplus HP Universal Camera                                                | 1         | 0.42%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 0.42%   |
| Sunplus HD User Facing                                                     | 1         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 29.73%  |
| Validity Sensors           | 10        | 27.03%  |
| LighTuning Technology      | 6         | 16.22%  |
| Upek                       | 5         | 13.51%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| Elan Microelectronics      | 2         | 5.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 13.51%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 4         | 10.81%  |
| LighTuning EgisTec Touch Fingerprint Sensor               | 4         | 10.81%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 3         | 8.11%   |
| Shenzhen Goodix  Fingerprint Device                       | 3         | 8.11%   |
| Unknown                                                   | 3         | 8.11%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 5.41%   |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 5.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 5.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 5.41%   |
| Validity Sensors VFS491                                   | 1         | 2.7%    |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 2.7%    |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                     | 1         | 2.7%    |
| Elan ELAN:ARM-M4                                          | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 38.46%  |
| Alcor Micro           | 5         | 38.46%  |
| Lenovo                | 2         | 15.38%  |
| Gemalto (was Gemplus) | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 5         | 38.46%  |
| Lenovo Integrated Smart Card Reader                    | 2         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor         | 2         | 15.38%  |
| Broadcom 58200                                         | 2         | 15.38%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 7.69%   |
| Broadcom 5880                                          | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 175       | 70.28%  |
| 1     | 57        | 22.89%  |
| 2     | 16        | 6.43%   |
| 3     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 37        | 40.22%  |
| Chipcard              | 13        | 14.13%  |
| Multimedia controller | 12        | 13.04%  |
| Net/wireless          | 11        | 11.96%  |
| Graphics card         | 8         | 8.7%    |
| Camera                | 4         | 4.35%   |
| Net/ethernet          | 2         | 2.17%   |
| Card reader           | 2         | 2.17%   |
| Bluetooth             | 2         | 2.17%   |
| Storage               | 1         | 1.09%   |

