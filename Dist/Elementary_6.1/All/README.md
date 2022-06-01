Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

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

Total: 507

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | Desktop     | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [5881b6ea1b](https://linux-hardware.org/?probe=5881b6ea1b) | May 28, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [6cc36ec0ae](https://linux-hardware.org/?probe=6cc36ec0ae) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [50f70bc9af](https://linux-hardware.org/?probe=50f70bc9af) | May 27, 2022 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [fc581d0fb4](https://linux-hardware.org/?probe=fc581d0fb4) | May 26, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [94796b9e96](https://linux-hardware.org/?probe=94796b9e96) | May 26, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [6789d8dad5](https://linux-hardware.org/?probe=6789d8dad5) | May 26, 2022 |
| AMI           | Intel                       | Notebook    | [ee3b1abf63](https://linux-hardware.org/?probe=ee3b1abf63) | May 25, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [601f82b2dd](https://linux-hardware.org/?probe=601f82b2dd) | May 23, 2022 |
| MSI           | H97M-P35                    | Desktop     | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [8cd4fba0ca](https://linux-hardware.org/?probe=8cd4fba0ca) | May 22, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [27f751618e](https://linux-hardware.org/?probe=27f751618e) | May 22, 2022 |
| HP            | ProBook 6550b               | Notebook    | [5a80f0ac5d](https://linux-hardware.org/?probe=5a80f0ac5d) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| AMI           | Intel                       | Notebook    | [6c571e79d0](https://linux-hardware.org/?probe=6c571e79d0) | May 21, 2022 |
| eMachines     | E525                        | Notebook    | [ca296b06c9](https://linux-hardware.org/?probe=ca296b06c9) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| Toshiba       | PORTEGE Z830                | Notebook    | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| MSI           | B85I                        | Desktop     | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [4d73e73cf8](https://linux-hardware.org/?probe=4d73e73cf8) | May 17, 2022 |
| Sony          | VPCEB23FM                   | Notebook    | [07d2cadefb](https://linux-hardware.org/?probe=07d2cadefb) | May 17, 2022 |
| Samsung       | Lumpy                       | Notebook    | [84a78226dd](https://linux-hardware.org/?probe=84a78226dd) | May 16, 2022 |
| HP            | ENVY 14                     | Notebook    | [9fe635b800](https://linux-hardware.org/?probe=9fe635b800) | May 15, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | K55A                        | Notebook    | [3391d004a7](https://linux-hardware.org/?probe=3391d004a7) | May 15, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [4521ae6617](https://linux-hardware.org/?probe=4521ae6617) | May 14, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [513d1e2c73](https://linux-hardware.org/?probe=513d1e2c73) | May 14, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c0e150d349](https://linux-hardware.org/?probe=c0e150d349) | May 13, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [919200b122](https://linux-hardware.org/?probe=919200b122) | May 13, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d5df500fa3](https://linux-hardware.org/?probe=d5df500fa3) | May 10, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | ProBook 4510s               | Notebook    | [1464ea43d3](https://linux-hardware.org/?probe=1464ea43d3) | May 09, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [b726ded078](https://linux-hardware.org/?probe=b726ded078) | May 08, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [2eb968b190](https://linux-hardware.org/?probe=2eb968b190) | May 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | Desktop     | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| eMachines     | E525                        | Notebook    | [dfc36c2ea0](https://linux-hardware.org/?probe=dfc36c2ea0) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [271a0aaed2](https://linux-hardware.org/?probe=271a0aaed2) | May 01, 2022 |
| ASUSTek       | X202E                       | Notebook    | [37ad2923f5](https://linux-hardware.org/?probe=37ad2923f5) | May 01, 2022 |
| HP            | 0B48h                       | Desktop     | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | Notebook    | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [eb3d4d0f78](https://linux-hardware.org/?probe=eb3d4d0f78) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [c12f5ae663](https://linux-hardware.org/?probe=c12f5ae663) | Apr 28, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| Dell          | 05R2TK A01                  | All in one  | [317f2966c3](https://linux-hardware.org/?probe=317f2966c3) | Apr 25, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| Lenovo        | ThinkPad T420 41786VU       | Notebook    | [e2b4c2327b](https://linux-hardware.org/?probe=e2b4c2327b) | Apr 25, 2022 |
| AZW           | GTi                         | Desktop     | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | Desktop     | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| Dell          | Latitude 3120               | Notebook    | [78f0703e75](https://linux-hardware.org/?probe=78f0703e75) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [2f497982cd](https://linux-hardware.org/?probe=2f497982cd) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63f6b73d50](https://linux-hardware.org/?probe=63f6b73d50) | Apr 21, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [b720cd5fc5](https://linux-hardware.org/?probe=b720cd5fc5) | Apr 20, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [336a67fbee](https://linux-hardware.org/?probe=336a67fbee) | Apr 19, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [d3d2e2fe8a](https://linux-hardware.org/?probe=d3d2e2fe8a) | Apr 18, 2022 |
| HP            | ProBook 6440b               | Notebook    | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | Desktop     | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Lenovo        | ThinkPad W541 20EGS0UB03    | Notebook    | [f566cb7f4c](https://linux-hardware.org/?probe=f566cb7f4c) | Apr 14, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [07bdcd6978](https://linux-hardware.org/?probe=07bdcd6978) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | Notebook    | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| Pegatron      | IPMH61P1                    | Desktop     | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3abf9847e4](https://linux-hardware.org/?probe=3abf9847e4) | Apr 10, 2022 |
| ASUSTek       | N56DY                       | Notebook    | [aff377f6ed](https://linux-hardware.org/?probe=aff377f6ed) | Apr 09, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | Notebook    | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [84c694e881](https://linux-hardware.org/?probe=84c694e881) | Apr 08, 2022 |
| ASRock        | C226 WS                     | Desktop     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [0626d13541](https://linux-hardware.org/?probe=0626d13541) | Apr 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [fd62bf7f91](https://linux-hardware.org/?probe=fd62bf7f91) | Apr 05, 2022 |
| Dell          | Latitude 5410               | Notebook    | [9d03bb6cad](https://linux-hardware.org/?probe=9d03bb6cad) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [a25b973df6](https://linux-hardware.org/?probe=a25b973df6) | Apr 05, 2022 |
| HP            | Stream Laptop 14-ax1xxx     | Notebook    | [4228c17983](https://linux-hardware.org/?probe=4228c17983) | Apr 05, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [656e7d1b73](https://linux-hardware.org/?probe=656e7d1b73) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| HP            | Notebook                    | Notebook    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Dell          | Inspiron 5481               | Convertible | [e364cee660](https://linux-hardware.org/?probe=e364cee660) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | Notebook    | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [7fc2cd808d](https://linux-hardware.org/?probe=7fc2cd808d) | Apr 02, 2022 |
| Dell          | Vostro A860                 | Notebook    | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9375dd090a](https://linux-hardware.org/?probe=9375dd090a) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [ab016f94d5](https://linux-hardware.org/?probe=ab016f94d5) | Apr 01, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | Notebook    | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | Notebook    | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b39b0fda2](https://linux-hardware.org/?probe=2b39b0fda2) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [78df63a35f](https://linux-hardware.org/?probe=78df63a35f) | Mar 20, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1268effe7d](https://linux-hardware.org/?probe=1268effe7d) | Mar 17, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [9eb7577acd](https://linux-hardware.org/?probe=9eb7577acd) | Mar 12, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| MSI           | B85I                        | Desktop     | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| Teclast       | F15S                        | Notebook    | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | Desktop     | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | Notebook    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| HP            | 1589                        | Desktop     | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| HP            | 805D                        | Desktop     | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [1f32b0aa84](https://linux-hardware.org/?probe=1f32b0aa84) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ef94f0dd4d](https://linux-hardware.org/?probe=ef94f0dd4d) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | Notebook    | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| MSI           | B85I                        | Desktop     | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Google        | Lulu                        | Notebook    | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f7500c309c](https://linux-hardware.org/?probe=f7500c309c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| HP            | 339A                        | Desktop     | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| HP            | 805D                        | Desktop     | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
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
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
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
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
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
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 95        | 23.11%  |
| 5.13.0-28-generic          | 53        | 12.9%   |
| 5.13.0-30-generic          | 40        | 9.73%   |
| 5.13.0-27-generic          | 35        | 8.52%   |
| 5.13.0-39-generic          | 34        | 8.27%   |
| 5.13.0-40-generic          | 25        | 6.08%   |
| 5.13.0-35-generic          | 23        | 5.6%    |
| 5.13.0-37-generic          | 19        | 4.62%   |
| 5.11.0-44-generic          | 17        | 4.14%   |
| 5.13.0-41-generic          | 13        | 3.16%   |
| 5.11.0-46-generic          | 12        | 2.92%   |
| 5.11.0-41-generic          | 10        | 2.43%   |
| 5.13.0-44-generic          | 5         | 1.22%   |
| 5.13.0-25-generic          | 4         | 0.97%   |
| 5.11.0-40-generic          | 3         | 0.73%   |
| 5.15.36-xanmod1            | 2         | 0.49%   |
| 5.8.0-50-generic           | 1         | 0.24%   |
| 5.4.0-1055-raspi           | 1         | 0.24%   |
| 5.16.16-051616-generic     | 1         | 0.24%   |
| 5.16.11-surface            | 1         | 0.24%   |
| 5.16.10-051610-generic     | 1         | 0.24%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.24%   |
| 5.15.6-surface             | 1         | 0.24%   |
| 5.15.5-051505-generic      | 1         | 0.24%   |
| 5.15.3-xanmod1             | 1         | 0.24%   |
| 5.15.21-051521-generic     | 1         | 0.24%   |
| 5.15.13-xanmod1            | 1         | 0.24%   |
| 5.15.12-xanmod1-tt         | 1         | 0.24%   |
| 5.15.11-t2-big-sur         | 1         | 0.24%   |
| 5.15.10-xanmod1            | 1         | 0.24%   |
| 5.14.10-051410-generic     | 1         | 0.24%   |
| 5.14.0-1029-oem            | 1         | 0.24%   |
| 5.14.0-1011-oem            | 1         | 0.24%   |
| 5.13.0-28-lowlatency       | 1         | 0.24%   |
| 5.13.0-22-generic          | 1         | 0.24%   |
| 5.11.0-43-lowlatency       | 1         | 0.24%   |
| 5.11.0-37-generic          | 1         | 0.24%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 239       | 60.51%  |
| 5.11.0  | 137       | 34.68%  |
| 5.15.36 | 2         | 0.51%   |
| 5.14.0  | 2         | 0.51%   |
| 5.8.0   | 1         | 0.25%   |
| 5.4.0   | 1         | 0.25%   |
| 5.16.16 | 1         | 0.25%   |
| 5.16.11 | 1         | 0.25%   |
| 5.16.10 | 1         | 0.25%   |
| 5.16.0  | 1         | 0.25%   |
| 5.15.6  | 1         | 0.25%   |
| 5.15.5  | 1         | 0.25%   |
| 5.15.3  | 1         | 0.25%   |
| 5.15.21 | 1         | 0.25%   |
| 5.15.13 | 1         | 0.25%   |
| 5.15.12 | 1         | 0.25%   |
| 5.15.11 | 1         | 0.25%   |
| 5.15.10 | 1         | 0.25%   |
| 5.14.10 | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 239       | 60.66%  |
| 5.11    | 137       | 34.77%  |
| 5.15    | 10        | 2.54%   |
| 5.16    | 3         | 0.76%   |
| 5.14    | 3         | 0.76%   |
| 5.8     | 1         | 0.25%   |
| 5.4     | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 389       | 99.74%  |
| aarch64 | 1         | 0.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 388       | 99.49%  |
| GNOME    | 1         | 0.26%   |
| Unknown  | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 390       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 314       | 80.31%  |
| LightDM | 74        | 18.93%  |
| GDM3    | 2         | 0.51%   |
| GDM     | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 170       | 43.59%  |
| de_DE   | 56        | 14.36%  |
| es_ES   | 33        | 8.46%   |
| fr_FR   | 20        | 5.13%   |
| en_GB   | 19        | 4.87%   |
| ru_RU   | 15        | 3.85%   |
| pt_BR   | 13        | 3.33%   |
| it_IT   | 13        | 3.33%   |
| pl_PL   | 11        | 2.82%   |
| en_CA   | 5         | 1.28%   |
| tr_TR   | 4         | 1.03%   |
| pt_PT   | 4         | 1.03%   |
| en_AU   | 4         | 1.03%   |
| zh_CN   | 2         | 0.51%   |
| sv_SE   | 2         | 0.51%   |
| nl_NL   | 2         | 0.51%   |
| nb_NO   | 2         | 0.51%   |
| ja_JP   | 2         | 0.51%   |
| uk_UA   | 1         | 0.26%   |
| sr_RS   | 1         | 0.26%   |
| id_ID   | 1         | 0.26%   |
| hu_HU   | 1         | 0.26%   |
| hr_HR   | 1         | 0.26%   |
| fr_CA   | 1         | 0.26%   |
| et_EE   | 1         | 0.26%   |
| de_CH   | 1         | 0.26%   |
| da_DK   | 1         | 0.26%   |
| cs_CZ   | 1         | 0.26%   |
| C       | 1         | 0.26%   |
| bg_BG   | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 255       | 65.38%  |
| BIOS | 135       | 34.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 378       | 96.92%  |
| Btrfs   | 8         | 2.05%   |
| Overlay | 3         | 0.77%   |
| Xfs     | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 333       | 85.17%  |
| GPT     | 51        | 13.04%  |
| MBR     | 7         | 1.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 376       | 96.41%  |
| Yes       | 14        | 3.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 364       | 93.33%  |
| Yes       | 26        | 6.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 64        | 16.41%  |
| Lenovo                  | 60        | 15.38%  |
| Hewlett-Packard         | 52        | 13.33%  |
| Apple                   | 37        | 9.49%   |
| Dell                    | 33        | 8.46%   |
| MSI                     | 22        | 5.64%   |
| Acer                    | 21        | 5.38%   |
| Gigabyte Technology     | 15        | 3.85%   |
| HUAWEI                  | 8         | 2.05%   |
| ASRock                  | 8         | 2.05%   |
| Sony                    | 6         | 1.54%   |
| Samsung Electronics     | 6         | 1.54%   |
| Intel                   | 6         | 1.54%   |
| Toshiba                 | 4         | 1.03%   |
| Microsoft               | 4         | 1.03%   |
| Biostar                 | 4         | 1.03%   |
| Teclast                 | 3         | 0.77%   |
| AMI                     | 3         | 0.77%   |
| Timi                    | 2         | 0.51%   |
| Star Labs               | 2         | 0.51%   |
| Notebook                | 2         | 0.51%   |
| Monster                 | 2         | 0.51%   |
| LG Electronics          | 2         | 0.51%   |
| Fujitsu                 | 2         | 0.51%   |
| Foxconn                 | 2         | 0.51%   |
| ECS                     | 2         | 0.51%   |
| Unknown                 | 2         | 0.51%   |
| Wortmann AG             | 1         | 0.26%   |
| Razer                   | 1         | 0.26%   |
| Raspberry Pi Foundation | 1         | 0.26%   |
| PIPO                    | 1         | 0.26%   |
| Pegatron                | 1         | 0.26%   |
| Packard Bell            | 1         | 0.26%   |
| LORD ELECTRONICS        | 1         | 0.26%   |
| iOTA                    | 1         | 0.26%   |
| Google                  | 1         | 0.26%   |
| FIRICH                  | 1         | 0.26%   |
| eMachines               | 1         | 0.26%   |
| BANGHO                  | 1         | 0.26%   |
| AZW                     | 1         | 0.26%   |
| Avell High Performance  | 1         | 0.26%   |
| AOpen                   | 1         | 0.26%   |
| Acidanthera             | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| ASUS All Series                                   | 4         | 1.03%   |
| Apple MacBook5,1                                  | 4         | 1.03%   |
| HUAWEI MACHD-WXX9                                 | 3         | 0.77%   |
| ASUS ZenBook UX425EA_UX425EA                      | 3         | 0.77%   |
| ASUS X550CA                                       | 3         | 0.77%   |
| Apple MacBookPro8,2                               | 3         | 0.77%   |
| Timi TM1613                                       | 2         | 0.51%   |
| MSI Prestige 15 A11UC                             | 2         | 0.51%   |
| MSI MS-7C35                                       | 2         | 0.51%   |
| Lenovo IdeaPad 310-15IKB 80TV                     | 2         | 0.51%   |
| HUAWEI NBLK-WAX9X                                 | 2         | 0.51%   |
| HP ENVY x360 Convertible 13-ay0xxx                | 2         | 0.51%   |
| HP EliteBook 8460p                                | 2         | 0.51%   |
| HP EliteBook 840 G1                               | 2         | 0.51%   |
| Gigabyte Z390 UD                                  | 2         | 0.51%   |
| Dell XPS 13 9343                                  | 2         | 0.51%   |
| Dell Inspiron N5050                               | 2         | 0.51%   |
| Dell Inspiron 15-3567                             | 2         | 0.51%   |
| ASUS TUF Gaming B550M-PLUS                        | 2         | 0.51%   |
| Apple MacBookPro6,2                               | 2         | 0.51%   |
| Apple MacBookPro5,5                               | 2         | 0.51%   |
| Apple MacBookAir7,1                               | 2         | 0.51%   |
| Apple MacBookAir4,2                               | 2         | 0.51%   |
| Apple MacBook4,1                                  | 2         | 0.51%   |
| Apple iMac9,1                                     | 2         | 0.51%   |
| Acer Swift SF114-32                               | 2         | 0.51%   |
| Unknown                                           | 2         | 0.51%   |
| Wortmann AG 1220729_1470271                       | 1         | 0.26%   |
| Toshiba Satellite L850D-BJS                       | 1         | 0.26%   |
| Toshiba Satellite L50D-C                          | 1         | 0.26%   |
| Toshiba Satellite C70D-A                          | 1         | 0.26%   |
| Toshiba PORTEGE Z830                              | 1         | 0.26%   |
| Teclast X6 plus                                   | 1         | 0.26%   |
| Teclast F7                                        | 1         | 0.26%   |
| Teclast F15S                                      | 1         | 0.26%   |
| Star Labs StarBook                                | 1         | 0.26%   |
| Star Labs LabTop                                  | 1         | 0.26%   |
| Sony VPCEB23FM                                    | 1         | 0.26%   |
| Sony VPCEA3S1E                                    | 1         | 0.26%   |
| Sony VPCCA4E1E                                    | 1         | 0.26%   |
| Sony SVP1321B4E                                   | 1         | 0.26%   |
| Sony SVE15115EN                                   | 1         | 0.26%   |
| Sony SVE14A390X                                   | 1         | 0.26%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411       | 1         | 0.26%   |
| Samsung Lumpy                                     | 1         | 0.26%   |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.26%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D        | 1         | 0.26%   |
| Samsung 870Z5E/880Z5E/680Z5E                      | 1         | 0.26%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.26%   |
| Razer Blade Stealth                               | 1         | 0.26%   |
| RPi Raspberry Pi 400 Rev 1.0                      | 1         | 0.26%   |
| PIPO W9                                           | 1         | 0.26%   |
| Pegatron IPMH61P1                                 | 1         | 0.26%   |
| Packard Bell EasyNote LS11HR                      | 1         | 0.26%   |
| Notebook W65_67SJ                                 | 1         | 0.26%   |
| Notebook P65xHP                                   | 1         | 0.26%   |
| MSI PS63 Modern 8RD                               | 1         | 0.26%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1         | 0.26%   |
| MSI MS-7D52                                       | 1         | 0.26%   |
| MSI MS-7C91                                       | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 29        | 7.44%   |
| Lenovo IdeaPad      | 16        | 4.1%    |
| Dell Inspiron       | 12        | 3.08%   |
| Acer Aspire         | 12        | 3.08%   |
| HP ProBook          | 8         | 2.05%   |
| HP Pavilion         | 8         | 2.05%   |
| HP EliteBook        | 8         | 2.05%   |
| ASUS VivoBook       | 7         | 1.79%   |
| Dell Latitude       | 6         | 1.54%   |
| ASUS ZenBook        | 6         | 1.54%   |
| HP ENVY             | 5         | 1.28%   |
| Dell Precision      | 5         | 1.28%   |
| ASUS TUF            | 5         | 1.28%   |
| Apple MacBook5      | 5         | 1.28%   |
| Acer Swift          | 5         | 1.28%   |
| Microsoft Surface   | 4         | 1.03%   |
| HP Laptop           | 4         | 1.03%   |
| Dell OptiPlex       | 4         | 1.03%   |
| ASUS ROG            | 4         | 1.03%   |
| ASUS PRIME          | 4         | 1.03%   |
| ASUS All            | 4         | 1.03%   |
| Apple MacBookPro8   | 4         | 1.03%   |
| Toshiba Satellite   | 3         | 0.77%   |
| HUAWEI MACHD-WXX9   | 3         | 0.77%   |
| HP ProDesk          | 3         | 0.77%   |
| HP Compaq           | 3         | 0.77%   |
| Dell XPS            | 3         | 0.77%   |
| Dell Vostro         | 3         | 0.77%   |
| ASUS X550CA         | 3         | 0.77%   |
| Apple MacBookPro5   | 3         | 0.77%   |
| Apple MacBookAir7   | 3         | 0.77%   |
| Timi TM1613         | 2         | 0.51%   |
| MSI Prestige        | 2         | 0.51%   |
| MSI MS-7C35         | 2         | 0.51%   |
| MSI Modern          | 2         | 0.51%   |
| Lenovo ThinkCentre  | 2         | 0.51%   |
| Lenovo ThinkBook    | 2         | 0.51%   |
| Lenovo Legion       | 2         | 0.51%   |
| Lenovo IdeaCentre   | 2         | 0.51%   |
| Lenovo G550         | 2         | 0.51%   |
| HUAWEI NBLK-WAX9X   | 2         | 0.51%   |
| HP Stream           | 2         | 0.51%   |
| HP ProLiant         | 2         | 0.51%   |
| Gigabyte Z390       | 2         | 0.51%   |
| ASUS P8H61-M        | 2         | 0.51%   |
| Apple MacBookPro9   | 2         | 0.51%   |
| Apple MacBookPro6   | 2         | 0.51%   |
| Apple MacBookAir6   | 2         | 0.51%   |
| Apple MacBookAir4   | 2         | 0.51%   |
| Apple MacBook4      | 2         | 0.51%   |
| Apple iMac9         | 2         | 0.51%   |
| Acer Nitro          | 2         | 0.51%   |
| Unknown             | 2         | 0.51%   |
| Wortmann AG 1220729 | 1         | 0.26%   |
| Toshiba PORTEGE     | 1         | 0.26%   |
| Teclast X6          | 1         | 0.26%   |
| Teclast F7          | 1         | 0.26%   |
| Teclast F15S        | 1         | 0.26%   |
| Star Labs StarBook  | 1         | 0.26%   |
| Star Labs LabTop    | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 50        | 12.82%  |
| 2018    | 39        | 10%     |
| 2012    | 34        | 8.72%   |
| 2021    | 33        | 8.46%   |
| 2019    | 33        | 8.46%   |
| 2015    | 29        | 7.44%   |
| 2011    | 28        | 7.18%   |
| 2016    | 25        | 6.41%   |
| 2013    | 24        | 6.15%   |
| 2014    | 22        | 5.64%   |
| 2010    | 22        | 5.64%   |
| 2017    | 18        | 4.62%   |
| 2009    | 17        | 4.36%   |
| 2008    | 10        | 2.56%   |
| 2007    | 2         | 0.51%   |
| 2006    | 2         | 0.51%   |
| 2022    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 248       | 63.59%  |
| Desktop        | 110       | 28.21%  |
| All in one     | 9         | 2.31%   |
| Tablet         | 8         | 2.05%   |
| Convertible    | 8         | 2.05%   |
| Mini pc        | 5         | 1.28%   |
| System on chip | 1         | 0.26%   |
| Server         | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 340       | 87.18%  |
| Enabled  | 50        | 12.82%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 386       | 98.97%  |
| Yes  | 4         | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 115       | 29.41%  |
| 3.01-4.0    | 80        | 20.46%  |
| 16.01-24.0  | 73        | 18.67%  |
| 8.01-16.0   | 63        | 16.11%  |
| 32.01-64.0  | 34        | 8.7%    |
| 1.01-2.0    | 14        | 3.58%   |
| 64.01-256.0 | 5         | 1.28%   |
| 24.01-32.0  | 4         | 1.02%   |
| 2.01-3.0    | 3         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 155       | 37.8%   |
| 2.01-3.0   | 122       | 29.76%  |
| 3.01-4.0   | 57        | 13.9%   |
| 4.01-8.0   | 44        | 10.73%  |
| 0.51-1.0   | 17        | 4.15%   |
| 8.01-16.0  | 13        | 3.17%   |
| 24.01-32.0 | 1         | 0.24%   |
| 16.01-24.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 244       | 62.09%  |
| 2      | 104       | 26.46%  |
| 3      | 22        | 5.6%    |
| 4      | 12        | 3.05%   |
| 5      | 6         | 1.53%   |
| 7      | 2         | 0.51%   |
| 6      | 2         | 0.51%   |
| 0      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 64.63%  |
| Yes       | 139       | 35.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 303       | 77.69%  |
| No        | 87        | 22.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 325       | 83.12%  |
| No        | 66        | 16.88%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 292       | 74.68%  |
| No        | 99        | 25.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 51        | 13.08%  |
| USA          | 48        | 12.31%  |
| Russia       | 19        | 4.87%   |
| UK           | 18        | 4.62%   |
| Brazil       | 18        | 4.62%   |
| India        | 17        | 4.36%   |
| Spain        | 16        | 4.1%    |
| Italy        | 16        | 4.1%    |
| France       | 16        | 4.1%    |
| Poland       | 13        | 3.33%   |
| Canada       | 12        | 3.08%   |
| Australia    | 12        | 3.08%   |
| Turkey       | 10        | 2.56%   |
| Indonesia    | 10        | 2.56%   |
| Austria      | 9         | 2.31%   |
| Mexico       | 8         | 2.05%   |
| Switzerland  | 6         | 1.54%   |
| Argentina    | 6         | 1.54%   |
| New Zealand  | 5         | 1.28%   |
| Japan        | 4         | 1.03%   |
| Czechia      | 4         | 1.03%   |
| Chile        | 4         | 1.03%   |
| Belgium      | 4         | 1.03%   |
| Sweden       | 3         | 0.77%   |
| South Africa | 3         | 0.77%   |
| Romania      | 3         | 0.77%   |
| Portugal     | 3         | 0.77%   |
| Norway       | 3         | 0.77%   |
| Netherlands  | 3         | 0.77%   |
| Colombia     | 3         | 0.77%   |
| Sri Lanka    | 2         | 0.51%   |
| Serbia       | 2         | 0.51%   |
| Pakistan     | 2         | 0.51%   |
| Malaysia     | 2         | 0.51%   |
| Lithuania    | 2         | 0.51%   |
| Iran         | 2         | 0.51%   |
| Estonia      | 2         | 0.51%   |
| Croatia      | 2         | 0.51%   |
| China        | 2         | 0.51%   |
| Bulgaria     | 2         | 0.51%   |
| Belarus      | 2         | 0.51%   |
| Vietnam      | 1         | 0.26%   |
| Ukraine      | 1         | 0.26%   |
| Thailand     | 1         | 0.26%   |
| Taiwan       | 1         | 0.26%   |
| Senegal      | 1         | 0.26%   |
| Peru         | 1         | 0.26%   |
| Nicaragua    | 1         | 0.26%   |
| Mozambique   | 1         | 0.26%   |
| Luxembourg   | 1         | 0.26%   |
| Latvia       | 1         | 0.26%   |
| Kenya        | 1         | 0.26%   |
| Israel       | 1         | 0.26%   |
| Ireland      | 1         | 0.26%   |
| Iceland      | 1         | 0.26%   |
| Hungary      | 1         | 0.26%   |
| Hong Kong    | 1         | 0.26%   |
| Guyana       | 1         | 0.26%   |
| Greece       | 1         | 0.26%   |
| Finland      | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Sydney                 | 7         | 1.74%   |
| Moscow                 | 7         | 1.74%   |
| Warsaw                 | 6         | 1.49%   |
| Munich                 | 6         | 1.49%   |
| Hamburg                | 5         | 1.24%   |
| Vienna                 | 4         | 0.99%   |
| St Petersburg          | 4         | 0.99%   |
| Sao Paulo              | 3         | 0.74%   |
| Paris                  | 3         | 0.74%   |
| Madrid                 | 3         | 0.74%   |
| Istanbul               | 3         | 0.74%   |
| Ankara                 | 3         | 0.74%   |
| Wroclaw                | 2         | 0.5%    |
| Wolgast                | 2         | 0.5%    |
| Tucson                 | 2         | 0.5%    |
| Toronto                | 2         | 0.5%    |
| Tangerang              | 2         | 0.5%    |
| Santo André           | 2         | 0.5%    |
| Muralto                | 2         | 0.5%    |
| Monza                  | 2         | 0.5%    |
| Montornès del Vallès | 2         | 0.5%    |
| Minsk                  | 2         | 0.5%    |
| Milan                  | 2         | 0.5%    |
| Jakarta                | 2         | 0.5%    |
| Islamabad              | 2         | 0.5%    |
| Dresden                | 2         | 0.5%    |
| Cankaya                | 2         | 0.5%    |
| Brisbane               | 2         | 0.5%    |
| Bonn                   | 2         | 0.5%    |
| Bogor                  | 2         | 0.5%    |
| Bern                   | 2         | 0.5%    |
| Berlin                 | 2         | 0.5%    |
| Antalya                | 2         | 0.5%    |
| Zhengzhou              | 1         | 0.25%   |
| Zagreb                 | 1         | 0.25%   |
| Yokohama               | 1         | 0.25%   |
| Yarang                 | 1         | 0.25%   |
| Woolloongabba          | 1         | 0.25%   |
| Wonosari               | 1         | 0.25%   |
| Witbank                | 1         | 0.25%   |
| West Bromwich          | 1         | 0.25%   |
| Wellington             | 1         | 0.25%   |
| Warrenton              | 1         | 0.25%   |
| Wallerfangen           | 1         | 0.25%   |
| Vitória da Conquista  | 1         | 0.25%   |
| Vilnius                | 1         | 0.25%   |
| Vila Nova de Gaia      | 1         | 0.25%   |
| Vigodarzere            | 1         | 0.25%   |
| Vernouillet            | 1         | 0.25%   |
| Vear                   | 1         | 0.25%   |
| Vantaa                 | 1         | 0.25%   |
| Vanse                  | 1         | 0.25%   |
| Valencia               | 1         | 0.25%   |
| Unken                  | 1         | 0.25%   |
| Ulyanovsk              | 1         | 0.25%   |
| Ubstadt-Weiher         | 1         | 0.25%   |
| Tromsø                | 1         | 0.25%   |
| Trieste                | 1         | 0.25%   |
| Treviso                | 1         | 0.25%   |
| Tournus                | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 85        | 108    | 15.21%  |
| Seagate                   | 70        | 79     | 12.52%  |
| WDC                       | 65        | 85     | 11.63%  |
| Toshiba                   | 38        | 43     | 6.8%    |
| Kingston                  | 38        | 45     | 6.8%    |
| SanDisk                   | 33        | 36     | 5.9%    |
| Unknown                   | 24        | 33     | 4.29%   |
| Crucial                   | 23        | 27     | 4.11%   |
| SK Hynix                  | 15        | 16     | 2.68%   |
| Intel                     | 14        | 15     | 2.5%    |
| Apple                     | 12        | 13     | 2.15%   |
| HGST                      | 11        | 11     | 1.97%   |
| Hitachi                   | 10        | 10     | 1.79%   |
| A-DATA Technology         | 9         | 9      | 1.61%   |
| Phison                    | 8         | 8      | 1.43%   |
| Micron Technology         | 7         | 7      | 1.25%   |
| Micron/Crucial Technology | 6         | 8      | 1.07%   |
| PNY                       | 5         | 9      | 0.89%   |
| KIOXIA                    | 5         | 5      | 0.89%   |
| Unknown                   | 5         | 6      | 0.89%   |
| JMicron                   | 4         | 4      | 0.72%   |
| China                     | 4         | 4      | 0.72%   |
| Transcend                 | 3         | 3      | 0.54%   |
| Team                      | 3         | 3      | 0.54%   |
| OCZ                       | 3         | 3      | 0.54%   |
| MAXTOR                    | 3         | 3      | 0.54%   |
| LITEON                    | 3         | 3      | 0.54%   |
| Leven                     | 3         | 3      | 0.54%   |
| Fujitsu                   | 3         | 3      | 0.54%   |
| ASMT                      | 3         | 3      | 0.54%   |
| TO Exter                  | 2         | 2      | 0.36%   |
| Teclast                   | 2         | 2      | 0.36%   |
| PLEXTOR                   | 2         | 2      | 0.36%   |
| Netac                     | 2         | 2      | 0.36%   |
| KingDian                  | 2         | 2      | 0.36%   |
| GOODRAM                   | 2         | 2      | 0.36%   |
| Dogfish                   | 2         | 2      | 0.36%   |
| XPG                       | 1         | 1      | 0.18%   |
| tigo                      | 1         | 1      | 0.18%   |
| Star Drive                | 1         | 1      | 0.18%   |
| Star                      | 1         | 1      | 0.18%   |
| SSSTC                     | 1         | 1      | 0.18%   |
| SSK                       | 1         | 1      | 0.18%   |
| SSDPR-CX                  | 1         | 1      | 0.18%   |
| SPCC                      | 1         | 1      | 0.18%   |
| Smartbuy                  | 1         | 1      | 0.18%   |
| Silicon Motion            | 1         | 1      | 0.18%   |
| SABRENT                   | 1         | 1      | 0.18%   |
| Realtek Semiconductor     | 1         | 1      | 0.18%   |
| Pichau                    | 1         | 1      | 0.18%   |
| OSCOO                     | 1         | 1      | 0.18%   |
| OCZ-VERTEX2               | 1         | 1      | 0.18%   |
| NGFF                      | 1         | 1      | 0.18%   |
| MidasForce                | 1         | 1      | 0.18%   |
| MENGMI                    | 1         | 1      | 0.18%   |
| Lite-On                   | 1         | 1      | 0.18%   |
| KingSpec                  | 1         | 1      | 0.18%   |
| Kingchuxing               | 1         | 1      | 0.18%   |
| Intenso                   | 1         | 1      | 0.18%   |
| Hewlett-Packard           | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB        | 9         | 1.51%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 1.34%   |
| Samsung NVMe SSD Drive 500GB        | 8         | 1.34%   |
| Samsung NVMe SSD Drive 256GB        | 8         | 1.34%   |
| Samsung SSD 860 EVO 250GB           | 7         | 1.18%   |
| Kingston SA400S37240G 240GB SSD     | 7         | 1.18%   |
| Unknown MMC Card  32GB              | 6         | 1.01%   |
| Sandisk NVMe SSD Drive 512GB        | 6         | 1.01%   |
| Kingston SA400S37120G 120GB SSD     | 6         | 1.01%   |
| SK Hynix NVMe SSD Drive 256GB       | 5         | 0.84%   |
| Samsung SSD 850 EVO 250GB           | 5         | 0.84%   |
| Phison NVMe SSD Drive 1TB           | 5         | 0.84%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 5         | 0.84%   |
| Intel NVMe SSD Drive 512GB          | 5         | 0.84%   |
| Crucial CT240BX500SSD1 240GB        | 5         | 0.84%   |
| Unknown                             | 5         | 0.84%   |
| Toshiba MQ01ABD100 1TB              | 4         | 0.67%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 4         | 0.67%   |
| Toshiba DT01ACA050 500GB            | 4         | 0.67%   |
| SK Hynix NVMe SSD Drive 512GB       | 4         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 0.67%   |
| Samsung NVMe SSD Drive 1024GB       | 4         | 0.67%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 4         | 0.67%   |
| Kingston NVMe SSD Drive 500GB       | 4         | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3         | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 3         | 0.5%    |
| Unknown MMC Card  64GB              | 3         | 0.5%    |
| Unknown MMC Card  128GB             | 3         | 0.5%    |
| Toshiba NVMe SSD Drive 512GB        | 3         | 0.5%    |
| Toshiba MQ04ABF100 1TB              | 3         | 0.5%    |
| Toshiba MQ01ABF050 500GB            | 3         | 0.5%    |
| Seagate ST3500418AS 500GB           | 3         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB      | 3         | 0.5%    |
| Samsung SSD 860 EVO 500GB           | 3         | 0.5%    |
| Samsung SSD 840 EVO 120GB           | 3         | 0.5%    |
| Samsung NVMe SSD Drive 1TB          | 3         | 0.5%    |
| PNY CS900 480GB SSD                 | 3         | 0.5%    |
| Kingston SV300S37A120G 120GB SSD    | 3         | 0.5%    |
| Kingston NVMe SSD Drive 1TB         | 3         | 0.5%    |
| JMicron Tech 250GB                  | 3         | 0.5%    |
| HGST HTS541010B7E610 1TB            | 3         | 0.5%    |
| Crucial CT480BX500SSD1 480GB        | 3         | 0.5%    |
| Crucial CT1000MX500SSD1 1TB         | 3         | 0.5%    |
| A-DATA SU650 120GB SSD              | 3         | 0.5%    |
| WDC WD5000LPVX-75V0TT0 500GB        | 2         | 0.34%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB            | 2         | 0.34%   |
| Unknown SD/MMC/MS PRO 999GB         | 2         | 0.34%   |
| Unknown SD/MMC 16GB                 | 2         | 0.34%   |
| Unknown MMC Card  16GB              | 2         | 0.34%   |
| Unknown M.S./M.S.Pro/HG 16GB        | 2         | 0.34%   |
| Toshiba HDWD110 1TB                 | 2         | 0.34%   |
| TO Exter nal USB 3.0 320GB          | 2         | 0.34%   |
| Seagate ST980811AS 80GB             | 2         | 0.34%   |
| Seagate ST9750420AS 752GB           | 2         | 0.34%   |
| Seagate ST9500325AS 500GB           | 2         | 0.34%   |
| Seagate ST2000DX002-2DV164 2TB      | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 76     | 36.22%  |
| WDC                 | 51        | 63     | 27.57%  |
| Toshiba             | 28        | 32     | 15.14%  |
| HGST                | 11        | 11     | 5.95%   |
| Hitachi             | 10        | 10     | 5.41%   |
| Samsung Electronics | 4         | 5      | 2.16%   |
| Fujitsu             | 3         | 3      | 1.62%   |
| Unknown             | 2         | 2      | 1.08%   |
| MAXTOR              | 2         | 2      | 1.08%   |
| ASMT                | 2         | 2      | 1.08%   |
| Apple               | 2         | 2      | 1.08%   |
| SABRENT             | 1         | 1      | 0.54%   |
| Hewlett-Packard     | 1         | 1      | 0.54%   |
| Ext Hard            | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 57     | 21.96%  |
| Kingston            | 27        | 30     | 12.62%  |
| Crucial             | 23        | 27     | 10.75%  |
| SanDisk             | 19        | 21     | 8.88%   |
| WDC                 | 11        | 15     | 5.14%   |
| Apple               | 10        | 10     | 4.67%   |
| A-DATA Technology   | 7         | 7      | 3.27%   |
| Micron Technology   | 6         | 6      | 2.8%    |
| PNY                 | 5         | 9      | 2.34%   |
| Intel               | 5         | 5      | 2.34%   |
| China               | 4         | 4      | 1.87%   |
| Transcend           | 3         | 3      | 1.4%    |
| Toshiba             | 3         | 3      | 1.4%    |
| Team                | 3         | 3      | 1.4%    |
| OCZ                 | 3         | 3      | 1.4%    |
| LITEON              | 3         | 3      | 1.4%    |
| TO Exter            | 2         | 2      | 0.93%   |
| Teclast             | 2         | 2      | 0.93%   |
| PLEXTOR             | 2         | 2      | 0.93%   |
| Leven               | 2         | 2      | 0.93%   |
| GOODRAM             | 2         | 2      | 0.93%   |
| Dogfish             | 2         | 2      | 0.93%   |
| tigo                | 1         | 1      | 0.47%   |
| Star                | 1         | 1      | 0.47%   |
| SPCC                | 1         | 1      | 0.47%   |
| Smartbuy            | 1         | 1      | 0.47%   |
| SK Hynix            | 1         | 1      | 0.47%   |
| Seagate             | 1         | 1      | 0.47%   |
| Pichau              | 1         | 1      | 0.47%   |
| OCZ-VERTEX2         | 1         | 1      | 0.47%   |
| NGFF                | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| MidasForce          | 1         | 1      | 0.47%   |
| MENGMI              | 1         | 1      | 0.47%   |
| MAXTOR              | 1         | 1      | 0.47%   |
| KingSpec            | 1         | 1      | 0.47%   |
| KingDian            | 1         | 1      | 0.47%   |
| JMicron             | 1         | 1      | 0.47%   |
| Intenso             | 1         | 1      | 0.47%   |
| Gigabyte Technology | 1         | 1      | 0.47%   |
| FORESEE             | 1         | 1      | 0.47%   |
| Corsair             | 1         | 1      | 0.47%   |
| Colorful            | 1         | 1      | 0.47%   |
| Apacer              | 1         | 1      | 0.47%   |
| Unknown             | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 196       | 241    | 37.69%  |
| HDD     | 165       | 211    | 31.73%  |
| NVMe    | 119       | 146    | 22.88%  |
| MMC     | 23        | 26     | 4.42%   |
| Unknown | 17        | 25     | 3.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 299       | 444    | 64.3%   |
| NVMe | 119       | 146    | 25.59%  |
| SAS  | 24        | 33     | 5.16%   |
| MMC  | 23        | 26     | 4.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 238       | 311    | 67.81%  |
| 0.51-1.0   | 77        | 96     | 21.94%  |
| 1.01-2.0   | 17        | 22     | 4.84%   |
| 4.01-10.0  | 9         | 10     | 2.56%   |
| 3.01-4.0   | 5         | 5      | 1.42%   |
| 2.01-3.0   | 5         | 8      | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 149       | 37.82%  |
| 251-500        | 102       | 25.89%  |
| 501-1000       | 57        | 14.47%  |
| 51-100         | 32        | 8.12%   |
| 1001-2000      | 23        | 5.84%   |
| 21-50          | 19        | 4.82%   |
| More than 3000 | 9         | 2.28%   |
| 2001-3000      | 2         | 0.51%   |
| Unknown        | 1         | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 185       | 45.68%  |
| 21-50          | 94        | 23.21%  |
| 51-100         | 43        | 10.62%  |
| 101-250        | 42        | 10.37%  |
| 251-500        | 17        | 4.2%    |
| 501-1000       | 14        | 3.46%   |
| 1001-2000      | 5         | 1.23%   |
| More than 3000 | 2         | 0.49%   |
| 2001-3000      | 2         | 0.49%   |
| Unknown        | 1         | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 12.5%   |
| Toshiba KBG30ZPZ128G 128GB              | 1         | 1      | 12.5%   |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1      | 12.5%   |
| Seagate ST3500312CS 500GB               | 1         | 1      | 12.5%   |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 12.5%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 12.5%   |
| HGST HTS721010A9E630 1TB                | 1         | 1      | 12.5%   |
| Crucial CT512M550SSD3 512GB             | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 25%     |
| WDC      | 1         | 1      | 12.5%   |
| Toshiba  | 1         | 1      | 12.5%   |
| SanDisk  | 1         | 1      | 12.5%   |
| Kingston | 1         | 1      | 12.5%   |
| HGST     | 1         | 1      | 12.5%   |
| Crucial  | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 50%     |
| SSD  | 3         | 3      | 37.5%   |
| NVMe | 1         | 1      | 12.5%   |

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
| Detected | 347       | 565    | 84.63%  |
| Works    | 55        | 76     | 13.41%  |
| Malfunc  | 8         | 8      | 1.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 265       | 56.03%  |
| AMD                            | 57        | 12.05%  |
| Samsung Electronics            | 42        | 8.88%   |
| Sandisk                        | 17        | 3.59%   |
| Nvidia                         | 15        | 3.17%   |
| SK Hynix                       | 14        | 2.96%   |
| Kingston Technology Company    | 13        | 2.75%   |
| Phison Electronics             | 9         | 1.9%    |
| Toshiba America Info Systems   | 7         | 1.48%   |
| Micron/Crucial Technology      | 6         | 1.27%   |
| Marvell Technology Group       | 6         | 1.27%   |
| ASMedia Technology             | 4         | 0.85%   |
| KIOXIA                         | 3         | 0.63%   |
| Seagate Technology             | 2         | 0.42%   |
| Realtek Semiconductor          | 2         | 0.42%   |
| JMicron Technology             | 2         | 0.42%   |
| ADATA Technology               | 2         | 0.42%   |
| Solid State Storage Technology | 1         | 0.21%   |
| Silicon Motion                 | 1         | 0.21%   |
| Micron Technology              | 1         | 0.21%   |
| LSI Logic / Symbios Logic      | 1         | 0.21%   |
| Lite-On Technology             | 1         | 0.21%   |
| Hewlett-Packard                | 1         | 0.21%   |
| Apple                          | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 45        | 8.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 23        | 4.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 21        | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 20        | 3.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16        | 3.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 2.85%   |
| Samsung NVMe SSD Controller 980                                                         | 12        | 2.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12        | 2.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 11        | 2.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10        | 1.9%    |
| Nvidia MCP79 AHCI Controller                                                            | 9         | 1.71%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7         | 1.33%   |
| Intel SSD 660P Series                                                                   | 7         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 1.33%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 6         | 1.14%   |
| Kingston Company A2000 NVMe SSD                                                         | 6         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.14%   |
| SK Hynix BC511                                                                          | 5         | 0.95%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 5         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 5         | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.76%   |
| SK Hynix Gold P31 SSD                                                                   | 4         | 0.76%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4         | 0.76%   |
| Phison E12 NVMe Controller                                                              | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 0.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 0.76%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.57%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.57%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.57%   |
| Samsung Electronics SATA controller                                                     | 3         | 0.57%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3         | 0.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.57%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.38%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.38%   |
| Sandisk Non-Volatile memory controller                                                  | 2         | 0.38%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.38%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 0.38%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 2         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 296       | 62.32%  |
| NVMe | 117       | 24.63%  |
| IDE  | 41        | 8.63%   |
| RAID | 20        | 4.21%   |
| SAS  | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 313       | 80.26%  |
| AMD    | 76        | 19.49%  |
| ARM    | 1         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 2.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 1.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.28%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.03%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.03%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 1.03%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.03%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.77%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.77%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 3         | 0.77%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 0.77%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.77%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 3         | 0.77%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.77%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz       | 3         | 0.77%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 3         | 0.77%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 3         | 0.77%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.77%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.77%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.77%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.51%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.51%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 2         | 0.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.51%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.51%   |
| Intel Core i7-5650U CPU @ 2.20GHz             | 2         | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 2         | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2         | 0.51%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 2         | 0.51%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.51%   |
| Intel Core i7-2635QM CPU @ 2.00GHz            | 2         | 0.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.51%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2         | 0.51%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.51%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.51%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.51%   |
| Intel Core i5-4260U CPU @ 1.40GHz             | 2         | 0.51%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.51%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.51%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.51%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.51%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 87        | 22.31%  |
| Intel Core i7           | 78        | 20%     |
| Intel Core i3           | 39        | 10%     |
| Intel Celeron           | 27        | 6.92%   |
| Other                   | 26        | 6.67%   |
| AMD Ryzen 5             | 24        | 6.15%   |
| Intel Core 2 Duo        | 22        | 5.64%   |
| AMD Ryzen 7             | 13        | 3.33%   |
| Intel Xeon              | 11        | 2.82%   |
| Intel Pentium           | 7         | 1.79%   |
| AMD Ryzen 9             | 6         | 1.54%   |
| Intel Atom              | 5         | 1.28%   |
| AMD Ryzen 3             | 5         | 1.28%   |
| Intel Pentium Silver    | 3         | 0.77%   |
| Intel Core 2 Quad       | 3         | 0.77%   |
| AMD Ryzen 7 PRO         | 3         | 0.77%   |
| AMD Phenom II X4        | 3         | 0.77%   |
| AMD A8                  | 3         | 0.77%   |
| AMD A6                  | 3         | 0.77%   |
| AMD A10                 | 3         | 0.77%   |
| Intel Pentium Dual-Core | 2         | 0.51%   |
| Intel Celeron Dual-Core | 2         | 0.51%   |
| AMD Athlon II X2        | 2         | 0.51%   |
| AMD Athlon              | 2         | 0.51%   |
| AMD A12                 | 2         | 0.51%   |
| Intel Pentium Dual      | 1         | 0.26%   |
| Intel Genuine           | 1         | 0.26%   |
| Intel Core m5           | 1         | 0.26%   |
| Intel Core i9           | 1         | 0.26%   |
| Intel Core 2            | 1         | 0.26%   |
| AMD FX                  | 1         | 0.26%   |
| AMD E1                  | 1         | 0.26%   |
| AMD Athlon X4           | 1         | 0.26%   |
| AMD A4                  | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 177       | 45.38%  |
| 4      | 148       | 37.95%  |
| 6      | 29        | 7.44%   |
| 8      | 28        | 7.18%   |
| 12     | 5         | 1.28%   |
| 1      | 2         | 0.51%   |
| 16     | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 388       | 99.49%  |
| 2      | 2         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 266       | 68.21%  |
| 1      | 124       | 31.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 389       | 99.74%  |
| 64-bit         | 1         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 37        | 9.44%   |
| Unknown    | 31        | 7.91%   |
| 0x306a9    | 27        | 6.89%   |
| 0x306c3    | 17        | 4.34%   |
| 0x1067a    | 17        | 4.34%   |
| 0x806c1    | 15        | 3.83%   |
| 0x306d4    | 13        | 3.32%   |
| 0x806ec    | 12        | 3.06%   |
| 0x20655    | 11        | 2.81%   |
| 0x406e3    | 10        | 2.55%   |
| 0x40651    | 10        | 2.55%   |
| 0x806e9    | 9         | 2.3%    |
| 0x10676    | 8         | 2.04%   |
| 0x806ea    | 7         | 1.79%   |
| 0x706a8    | 7         | 1.79%   |
| 0x506e3    | 7         | 1.79%   |
| 0x20652    | 7         | 1.79%   |
| 0x08600106 | 7         | 1.79%   |
| 0x08108109 | 7         | 1.79%   |
| 0x906ea    | 6         | 1.53%   |
| 0x906e9    | 6         | 1.53%   |
| 0x406c3    | 6         | 1.53%   |
| 0x08701021 | 6         | 1.53%   |
| 0x806eb    | 5         | 1.28%   |
| 0x506c9    | 5         | 1.28%   |
| 0x906ed    | 4         | 1.02%   |
| 0x30678    | 4         | 1.02%   |
| 0x206d7    | 4         | 1.02%   |
| 0x08108102 | 4         | 1.02%   |
| 0x06006705 | 4         | 1.02%   |
| 0xa0671    | 3         | 0.77%   |
| 0xa0652    | 3         | 0.77%   |
| 0x906eb    | 3         | 0.77%   |
| 0x706a1    | 3         | 0.77%   |
| 0x6fd      | 3         | 0.77%   |
| 0x6fb      | 3         | 0.77%   |
| 0x406c4    | 3         | 0.77%   |
| 0x0a50000c | 3         | 0.77%   |
| 0x08608103 | 3         | 0.77%   |
| 0x0800820d | 3         | 0.77%   |
| 0x06001119 | 3         | 0.77%   |
| 0x806c2    | 2         | 0.51%   |
| 0x706e5    | 2         | 0.51%   |
| 0x106e5    | 2         | 0.51%   |
| 0x0a201016 | 2         | 0.51%   |
| 0x08600104 | 2         | 0.51%   |
| 0x08101007 | 2         | 0.51%   |
| 0x0700010f | 2         | 0.51%   |
| 0x06003106 | 2         | 0.51%   |
| 0x010000c8 | 2         | 0.51%   |
| 0xa0660    | 1         | 0.26%   |
| 0xa0655    | 1         | 0.26%   |
| 0xa0653    | 1         | 0.26%   |
| 0x906ec    | 1         | 0.26%   |
| 0x906c0    | 1         | 0.26%   |
| 0x6fa      | 1         | 0.26%   |
| 0x6f7      | 1         | 0.26%   |
| 0x6f2      | 1         | 0.26%   |
| 0x40671    | 1         | 0.26%   |
| 0x40661    | 1         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 62        | 15.9%   |
| SandyBridge   | 43        | 11.03%  |
| Haswell       | 32        | 8.21%   |
| IvyBridge     | 28        | 7.18%   |
| Penryn        | 25        | 6.41%   |
| Zen 2         | 20        | 5.13%   |
| TigerLake     | 19        | 4.87%   |
| Westmere      | 18        | 4.62%   |
| Skylake       | 18        | 4.62%   |
| Zen+          | 16        | 4.1%    |
| Silvermont    | 14        | 3.59%   |
| Broadwell     | 14        | 3.59%   |
| Goldmont plus | 10        | 2.56%   |
| Core          | 9         | 2.31%   |
| Zen 3         | 8         | 2.05%   |
| Excavator     | 8         | 2.05%   |
| CometLake     | 6         | 1.54%   |
| Zen           | 5         | 1.28%   |
| K10           | 5         | 1.28%   |
| IceLake       | 5         | 1.28%   |
| Goldmont      | 5         | 1.28%   |
| Unknown       | 5         | 1.28%   |
| Piledriver    | 3         | 0.77%   |
| Nehalem       | 3         | 0.77%   |
| Steamroller   | 2         | 0.51%   |
| Puma          | 2         | 0.51%   |
| Jaguar        | 2         | 0.51%   |
| Tremont       | 1         | 0.26%   |
| Bulldozer     | 1         | 0.26%   |
| Bonnell       | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 247       | 53.46%  |
| Nvidia                     | 111       | 24.03%  |
| AMD                        | 103       | 22.29%  |
| Matrox Electronics Systems | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 7.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 3.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 3.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.73%   |
| AMD Renoir                                                                               | 12        | 2.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.31%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 10        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 2.1%    |
| Intel UHD Graphics 620                                                                   | 9         | 1.89%   |
| Intel HD Graphics 620                                                                    | 9         | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.68%   |
| Nvidia C79 [GeForce 9400M]                                                               | 7         | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.26%   |
| Intel HD Graphics 630                                                                    | 5         | 1.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.84%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.84%   |
| Intel HD Graphics 530                                                                    | 4         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.84%   |
| AMD Lucienne                                                                             | 4         | 0.84%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4         | 0.84%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.63%   |
| Intel HD Graphics 6000                                                                   | 3         | 0.63%   |
| Intel HD Graphics 500                                                                    | 3         | 0.63%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.63%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.63%   |
| AMD Cezanne                                                                              | 3         | 0.63%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.63%   |
| Nvidia TU117M                                                                            | 2         | 0.42%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.42%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.42%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.42%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.42%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.42%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.42%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.42%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 2         | 0.42%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.42%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.42%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.42%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2         | 0.42%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 179       | 45.66%  |
| 1 x AMD        | 78        | 19.9%   |
| 1 x Nvidia     | 56        | 14.29%  |
| Intel + Nvidia | 51        | 13.01%  |
| Intel + AMD    | 14        | 3.57%   |
| 2 x AMD        | 8         | 2.04%   |
| AMD + Nvidia   | 3         | 0.77%   |
| Other          | 1         | 0.26%   |
| 2 x Nvidia     | 1         | 0.26%   |
| 1 x Matrox     | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 336       | 85.71%  |
| Proprietary | 52        | 13.27%  |
| Unknown     | 4         | 1.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 208       | 52.93%  |
| 1.01-2.0   | 49        | 12.47%  |
| 0.01-0.5   | 48        | 12.21%  |
| 0.51-1.0   | 37        | 9.41%   |
| 3.01-4.0   | 28        | 7.12%   |
| 7.01-8.0   | 9         | 2.29%   |
| 5.01-6.0   | 8         | 2.04%   |
| 2.01-3.0   | 3         | 0.76%   |
| 8.01-16.0  | 3         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 12.76%  |
| LG Display              | 46        | 10.48%  |
| Samsung Electronics     | 45        | 10.25%  |
| Chimei Innolux          | 40        | 9.11%   |
| Apple                   | 37        | 8.43%   |
| BOE                     | 30        | 6.83%   |
| Goldstar                | 17        | 3.87%   |
| Acer                    | 17        | 3.87%   |
| Hewlett-Packard         | 16        | 3.64%   |
| Dell                    | 16        | 3.64%   |
| Lenovo                  | 15        | 3.42%   |
| Sharp                   | 11        | 2.51%   |
| Philips                 | 11        | 2.51%   |
| BenQ                    | 8         | 1.82%   |
| Ancor Communications    | 8         | 1.82%   |
| PANDA                   | 6         | 1.37%   |
| AOC                     | 6         | 1.37%   |
| InfoVision              | 4         | 0.91%   |
| CSO                     | 4         | 0.91%   |
| Unknown                 | 3         | 0.68%   |
| NEC Computers           | 3         | 0.68%   |
| Chi Mei Optoelectronics | 3         | 0.68%   |
| ViewSonic               | 2         | 0.46%   |
| Panasonic               | 2         | 0.46%   |
| LG Electronics          | 2         | 0.46%   |
| HPN                     | 2         | 0.46%   |
| Fujitsu Siemens         | 2         | 0.46%   |
| AUS                     | 2         | 0.46%   |
| ___                     | 1         | 0.23%   |
| Vizio                   | 1         | 0.23%   |
| Vestel                  | 1         | 0.23%   |
| Toshiba                 | 1         | 0.23%   |
| SPC                     | 1         | 0.23%   |
| Sony                    | 1         | 0.23%   |
| Plain Tree Systems      | 1         | 0.23%   |
| Packard Bell            | 1         | 0.23%   |
| MSI                     | 1         | 0.23%   |
| Mi                      | 1         | 0.23%   |
| Marantz                 | 1         | 0.23%   |
| Konka                   | 1         | 0.23%   |
| JDI                     | 1         | 0.23%   |
| IOD                     | 1         | 0.23%   |
| Iiyama                  | 1         | 0.23%   |
| HUAWEI                  | 1         | 0.23%   |
| HJC                     | 1         | 0.23%   |
| EXP                     | 1         | 0.23%   |
| Element                 | 1         | 0.23%   |
| Eizo                    | 1         | 0.23%   |
| DPL                     | 1         | 0.23%   |
| CPT                     | 1         | 0.23%   |
| CHR                     | 1         | 0.23%   |
| CHD                     | 1         | 0.23%   |
| Unknown                 | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 1.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.66%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.66%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.66%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.66%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 3         | 0.66%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.66%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 3         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.44%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 2         | 0.44%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch               | 2         | 0.44%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.44%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 0.44%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 344x193mm 15.5-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.44%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.44%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.44%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.44%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.44%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 0.44%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.44%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 2         | 0.44%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 2         | 0.44%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.22%   |
| Vizio D32x-D1 VIZ1005 1920x1080 700x390mm 31.5-inch                   | 1         | 0.22%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.22%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                              | 1         | 0.22%   |
| ViewSonic LCD Monitor VX2260WM                                        | 1         | 0.22%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                             | 1         | 0.22%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.22%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1         | 0.22%   |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                            | 1         | 0.22%   |
| Toshiba TV TSB2019 3840x2160                                          | 1         | 0.22%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                  | 1         | 0.22%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.22%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.22%   |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.22%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 1         | 0.22%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.22%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.22%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 167       | 39.11%  |
| 1366x768 (WXGA)    | 96        | 22.48%  |
| 3840x2160 (4K)     | 27        | 6.32%   |
| 2560x1440 (QHD)    | 24        | 5.62%   |
| 1440x900 (WXGA+)   | 18        | 4.22%   |
| 1600x900 (HD+)     | 17        | 3.98%   |
| 1680x1050 (WSXGA+) | 15        | 3.51%   |
| 1280x800 (WXGA)    | 13        | 3.04%   |
| 1920x1200 (WUXGA)  | 8         | 1.87%   |
| 1360x768           | 5         | 1.17%   |
| 3840x1080          | 4         | 0.94%   |
| 3000x2000          | 4         | 0.94%   |
| 1280x1024 (SXGA)   | 4         | 0.94%   |
| Unknown            | 4         | 0.94%   |
| 3440x1440          | 2         | 0.47%   |
| 2880x1800          | 2         | 0.47%   |
| 2560x1600          | 2         | 0.47%   |
| 2560x1080          | 2         | 0.47%   |
| 1920x1280          | 2         | 0.47%   |
| 7680x2160          | 1         | 0.23%   |
| 5120x1440          | 1         | 0.23%   |
| 3840x2400          | 1         | 0.23%   |
| 3200x1800 (QHD+)   | 1         | 0.23%   |
| 3072x1920          | 1         | 0.23%   |
| 2880x1920          | 1         | 0.23%   |
| 2496x1664          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1800x1200          | 1         | 0.23%   |
| 1400x1050          | 1         | 0.23%   |
| 1280x720 (HD)      | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 111       | 25.28%  |
| 13      | 63        | 14.35%  |
| 14      | 45        | 10.25%  |
| 27      | 25        | 5.69%   |
| Unknown | 25        | 5.69%   |
| 24      | 23        | 5.24%   |
| 23      | 21        | 4.78%   |
| 17      | 21        | 4.78%   |
| 21      | 18        | 4.1%    |
| 22      | 11        | 2.51%   |
| 11      | 10        | 2.28%   |
| 31      | 9         | 2.05%   |
| 18      | 8         | 1.82%   |
| 12      | 8         | 1.82%   |
| 20      | 6         | 1.37%   |
| 34      | 4         | 0.91%   |
| 84      | 3         | 0.68%   |
| 32      | 3         | 0.68%   |
| 26      | 3         | 0.68%   |
| 25      | 3         | 0.68%   |
| 16      | 3         | 0.68%   |
| 10      | 3         | 0.68%   |
| 72      | 2         | 0.46%   |
| 52      | 2         | 0.46%   |
| 19      | 2         | 0.46%   |
| 65      | 1         | 0.23%   |
| 55      | 1         | 0.23%   |
| 49      | 1         | 0.23%   |
| 48      | 1         | 0.23%   |
| 47      | 1         | 0.23%   |
| 43      | 1         | 0.23%   |
| 37      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 183       | 42.46%  |
| 501-600     | 66        | 15.31%  |
| 201-300     | 58        | 13.46%  |
| 401-500     | 43        | 9.98%   |
| Unknown     | 25        | 5.8%    |
| 351-400     | 22        | 5.1%    |
| 601-700     | 13        | 3.02%   |
| 701-800     | 7         | 1.62%   |
| 1001-1500   | 7         | 1.62%   |
| 1501-2000   | 5         | 1.16%   |
| 801-900     | 1         | 0.23%   |
| 901-1000    | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 299       | 74.94%  |
| 16/10   | 58        | 14.54%  |
| Unknown | 22        | 5.51%   |
| 3/2     | 11        | 2.76%   |
| 21/9    | 4         | 1%      |
| 5/4     | 3         | 0.75%   |
| 4/3     | 1         | 0.25%   |
| 32/9    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 24.94%  |
| 81-90          | 84        | 19.4%   |
| 201-250        | 53        | 12.24%  |
| 301-350        | 26        | 6%      |
| 71-80          | 25        | 5.77%   |
| Unknown        | 25        | 5.77%   |
| 351-500        | 16        | 3.7%    |
| 251-300        | 15        | 3.46%   |
| 121-130        | 14        | 3.23%   |
| 151-200        | 13        | 3%      |
| More than 1000 | 10        | 2.31%   |
| 51-60          | 10        | 2.31%   |
| 141-150        | 10        | 2.31%   |
| 61-70          | 7         | 1.62%   |
| 131-140        | 4         | 0.92%   |
| 111-120        | 4         | 0.92%   |
| 501-1000       | 4         | 0.92%   |
| 41-50          | 3         | 0.69%   |
| 91-100         | 2         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 130       | 30.3%   |
| 101-120       | 124       | 28.9%   |
| 51-100        | 101       | 23.54%  |
| 161-240       | 27        | 6.29%   |
| Unknown       | 25        | 5.83%   |
| More than 240 | 13        | 3.03%   |
| 1-50          | 9         | 2.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 336       | 85.28%  |
| 2     | 47        | 11.93%  |
| 3     | 8         | 2.03%   |
| 0     | 2         | 0.51%   |
| 4     | 1         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 186       | 32.63%  |
| Realtek Semiconductor             | 184       | 32.28%  |
| Qualcomm Atheros                  | 64        | 11.23%  |
| Broadcom                          | 53        | 9.3%    |
| Nvidia                            | 13        | 2.28%   |
| Marvell Technology Group          | 10        | 1.75%   |
| Broadcom Limited                  | 10        | 1.75%   |
| Ralink Technology                 | 6         | 1.05%   |
| TP-Link                           | 5         | 0.88%   |
| Xiaomi                            | 4         | 0.7%    |
| Samsung Electronics               | 4         | 0.7%    |
| Ralink                            | 4         | 0.7%    |
| ASIX Electronics                  | 3         | 0.53%   |
| Lenovo                            | 2         | 0.35%   |
| Huawei Technologies               | 2         | 0.35%   |
| Google                            | 2         | 0.35%   |
| vivo                              | 1         | 0.18%   |
| TRENDnet                          | 1         | 0.18%   |
| Sitecom Europe                    | 1         | 0.18%   |
| Sierra Wireless                   | 1         | 0.18%   |
| OPPO Electronics                  | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.18%   |
| Motorola PCS                      | 1         | 0.18%   |
| Microsoft                         | 1         | 0.18%   |
| MEDIATEK                          | 1         | 0.18%   |
| Linksys                           | 1         | 0.18%   |
| LG Electronics                    | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| D-Link                            | 1         | 0.18%   |
| AVM                               | 1         | 0.18%   |
| Apple                             | 1         | 0.18%   |
| AboCom Systems                    | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 114       | 17.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 4.33%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 2.84%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 2.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.24%   |
| Intel Wireless 8260                                               | 14        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.49%   |
| Nvidia MCP79 Ethernet                                             | 10        | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.35%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.35%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 9         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.2%    |
| Intel Wireless 7265                                               | 8         | 1.2%    |
| Intel Wireless 7260                                               | 8         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 7         | 1.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 7         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 6         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.75%   |
| Intel Wireless 3165                                               | 5         | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.75%   |
| Intel Centrino Advanced-N 6200                                    | 5         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.75%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.6%    |
| Realtek 802.11ac NIC                                              | 4         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.6%    |
| Intel Ethernet Controller I225-V                                  | 4         | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.6%    |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 4         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.45%   |
| Intel Wireless-AC 9260                                            | 3         | 0.45%   |
| Intel Wireless 3160                                               | 3         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 150       | 44.25%  |
| Realtek Semiconductor    | 52        | 15.34%  |
| Qualcomm Atheros         | 51        | 15.04%  |
| Broadcom                 | 48        | 14.16%  |
| Broadcom Limited         | 10        | 2.95%   |
| Ralink Technology        | 6         | 1.77%   |
| TP-Link                  | 5         | 1.47%   |
| Ralink                   | 4         | 1.18%   |
| Marvell Technology Group | 2         | 0.59%   |
| TRENDnet                 | 1         | 0.29%   |
| Sitecom Europe           | 1         | 0.29%   |
| Sierra Wireless          | 1         | 0.29%   |
| Microsoft                | 1         | 0.29%   |
| MEDIATEK                 | 1         | 0.29%   |
| Linksys                  | 1         | 0.29%   |
| LG Electronics           | 1         | 0.29%   |
| D-Link System            | 1         | 0.29%   |
| D-Link                   | 1         | 0.29%   |
| AVM                      | 1         | 0.29%   |
| AboCom Systems           | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 19        | 5.57%   |
| Intel Wi-Fi 6 AX201                                                               | 16        | 4.69%   |
| Intel Wireless 8260                                                               | 14        | 4.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 12        | 3.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 11        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                        | 11        | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                 | 11        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                        | 10        | 2.93%   |
| Intel Wireless 8265 / 8275                                                        | 9         | 2.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                            | 9         | 2.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                          | 8         | 2.35%   |
| Intel Wireless 7265                                                               | 8         | 2.35%   |
| Intel Wireless 7260                                                               | 8         | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                          | 8         | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                      | 7         | 2.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                                    | 7         | 2.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                                   | 7         | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                    | 6         | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                   | 5         | 1.47%   |
| Intel Wireless 3165                                                               | 5         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                                   | 5         | 1.47%   |
| Intel Centrino Advanced-N 6200                                                    | 5         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                        | 5         | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                   | 4         | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 4         | 1.17%   |
| Realtek 802.11ac NIC                                                              | 4         | 1.17%   |
| Ralink MT7601U Wireless Adapter                                                   | 4         | 1.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 4         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                   | 4         | 1.17%   |
| Broadcom BCM4321 802.11a/b/g/n                                                    | 4         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                                     | 4         | 1.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                 | 4         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                  | 3         | 0.88%   |
| Intel Wireless-AC 9260                                                            | 3         | 0.88%   |
| Intel Wireless 3160                                                               | 3         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3         | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 3         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 3         | 0.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                       | 3         | 0.88%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 2         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 2         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2         | 0.59%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 2         | 0.59%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 2         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                         | 2         | 0.59%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 2         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                        | 2         | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                  | 2         | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                    | 2         | 0.59%   |
| Intel Ultimate N WiFi Link 5300                                                   | 2         | 0.59%   |
| Intel Centrino Advanced-N 6235                                                    | 2         | 0.59%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                                            | 2         | 0.59%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                         | 2         | 0.59%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2         | 0.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                                   | 2         | 0.59%   |
| Broadcom BCM43227 802.11b/g/n                                                     | 2         | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                               | 2         | 0.59%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1         | 0.29%   |
| TP-Link Archer T4U ver.3                                                          | 1         | 0.29%   |
| TP-Link 802.11n NIC                                                               | 1         | 0.29%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 162       | 50.15%  |
| Intel                    | 83        | 25.7%   |
| Qualcomm Atheros         | 18        | 5.57%   |
| Broadcom                 | 17        | 5.26%   |
| Nvidia                   | 13        | 4.02%   |
| Marvell Technology Group | 8         | 2.48%   |
| Xiaomi                   | 4         | 1.24%   |
| Samsung Electronics      | 4         | 1.24%   |
| ASIX Electronics         | 3         | 0.93%   |
| Lenovo                   | 2         | 0.62%   |
| Google                   | 2         | 0.62%   |
| vivo                     | 1         | 0.31%   |
| OPPO Electronics         | 1         | 0.31%   |
| Motorola PCS             | 1         | 0.31%   |
| Huawei Technologies      | 1         | 0.31%   |
| Hewlett-Packard          | 1         | 0.31%   |
| Broadcom Limited         | 1         | 0.31%   |
| Apple                    | 1         | 0.31%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 114       | 35.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 8.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 4.62%   |
| Nvidia MCP79 Ethernet                                                          | 10        | 3.08%   |
| Realtek RTL8125 2.5GbE Controller                                              | 9         | 2.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 2.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 1.85%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.54%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.23%   |
| Intel Ethernet Controller I225-V                                               | 4         | 1.23%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.23%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.92%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.92%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.92%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.92%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.92%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.62%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.62%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.62%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.62%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.62%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.62%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.62%   |
| Intel 82578DM Gigabit Network Connection                                       | 2         | 0.62%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.62%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.62%   |
| vivo 1806                                                                      | 1         | 0.31%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.31%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.31%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.31%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.31%   |
| OPPO realme X50 5G                                                             | 1         | 0.31%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.31%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.31%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.31%   |
| Motorola PCS moto g(6) play                                                    | 1         | 0.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.31%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.31%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.31%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 327       | 51.82%  |
| Ethernet | 301       | 47.7%   |
| Modem    | 2         | 0.32%   |
| Unknown  | 1         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 64.69%  |
| Ethernet | 137       | 35.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 205       | 52.43%  |
| 1     | 172       | 43.99%  |
| 3     | 8         | 2.05%   |
| 0     | 5         | 1.28%   |
| 4     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 277       | 70.3%   |
| Yes  | 117       | 29.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 130       | 43.92%  |
| Apple                           | 38        | 12.84%  |
| Realtek Semiconductor           | 31        | 10.47%  |
| Qualcomm Atheros Communications | 17        | 5.74%   |
| Cambridge Silicon Radio         | 16        | 5.41%   |
| Broadcom                        | 15        | 5.07%   |
| Lite-On Technology              | 11        | 3.72%   |
| IMC Networks                    | 11        | 3.72%   |
| Foxconn / Hon Hai               | 7         | 2.36%   |
| Hewlett-Packard                 | 6         | 2.03%   |
| Toshiba                         | 3         | 1.01%   |
| ASUSTek Computer                | 3         | 1.01%   |
| Realtek                         | 2         | 0.68%   |
| Ralink                          | 2         | 0.68%   |
| Marvell Semiconductor           | 2         | 0.68%   |
| Qcom                            | 1         | 0.34%   |
| Dell                            | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 50        | 16.89%  |
| Intel AX201 Bluetooth                                                               | 26        | 8.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 7.43%   |
| Intel AX200 Bluetooth                                                               | 18        | 6.08%   |
| Realtek Bluetooth Radio                                                             | 17        | 5.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 5.41%   |
| Apple Bluetooth Host Controller                                                     | 16        | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 3.72%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 3.72%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 2.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 7         | 2.36%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.69%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.69%   |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.35%   |
| Apple Bluetooth HCI                                                                 | 4         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.01%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.01%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.01%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 1.01%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.01%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.68%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.68%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.68%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.34%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.34%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.34%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.34%   |
| Realtek Bluetooth 5.1 Radio                                                         | 1         | 0.34%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.34%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.34%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.34%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.34%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.34%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.34%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.34%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.34%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.34%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.34%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.34%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.34%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.34%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.34%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.34%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.34%   |
| ASUS BCM20702A0                                                                     | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 291       | 56.61%  |
| AMD                      | 102       | 19.84%  |
| Nvidia                   | 77        | 14.98%  |
| C-Media Electronics      | 10        | 1.95%   |
| Creative Labs            | 7         | 1.36%   |
| Logitech                 | 5         | 0.97%   |
| Generalplus Technology   | 2         | 0.39%   |
| Focusrite-Novation       | 2         | 0.39%   |
| ESS Technology           | 2         | 0.39%   |
| Unknown                  | 1         | 0.19%   |
| Texas Instruments        | 1         | 0.19%   |
| SteelSeries ApS          | 1         | 0.19%   |
| Realtek Semiconductor    | 1         | 0.19%   |
| Razer USA                | 1         | 0.19%   |
| No brand                 | 1         | 0.19%   |
| Native Instruments       | 1         | 0.19%   |
| Micro Star International | 1         | 0.19%   |
| GN Netcom                | 1         | 0.19%   |
| Fry's Electronics        | 1         | 0.19%   |
| Dell                     | 1         | 0.19%   |
| Creative Technology      | 1         | 0.19%   |
| Corsair                  | 1         | 0.19%   |
| BEHRINGER International  | 1         | 0.19%   |
| ASUSTek Computer         | 1         | 0.19%   |
| Apple                    | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 39        | 6.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 35        | 5.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 4.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 20        | 3.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 3.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 2.45%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 2.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 2.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 1.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.79%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 11        | 1.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 10        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.31%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.14%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 7         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.98%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 0.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6         | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.82%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.82%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 0.82%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4         | 0.65%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.65%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.49%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.49%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.49%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.49%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.49%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                                     | 3         | 0.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.49%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.33%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.33%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 35.06%  |
| SK Hynix            | 16        | 20.78%  |
| Micron Technology   | 10        | 12.99%  |
| Unknown             | 5         | 6.49%   |
| Kingston            | 4         | 5.19%   |
| Ramaxel Technology  | 2         | 2.6%    |
| G.Skill             | 2         | 2.6%    |
| Corsair             | 2         | 2.6%    |
| Unknown (ABCD)      | 1         | 1.3%    |
| SHARETRONIC         | 1         | 1.3%    |
| PNY                 | 1         | 1.3%    |
| Patriot             | 1         | 1.3%    |
| Hewlett-Packard     | 1         | 1.3%    |
| GSkill              | 1         | 1.3%    |
| ELPIDA              | 1         | 1.3%    |
| Crucial             | 1         | 1.3%    |
| A-DATA Technology   | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 3         | 3.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 2         | 2.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s          | 2         | 2.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 2         | 2.35%   |
| Unknown RAM Module 8192MB SODIMM DDR3                           | 1         | 1.18%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                    | 1         | 1.18%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.18%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                  | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s  | 1         | 1.18%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                 | 1         | 1.18%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s               | 1         | 1.18%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.18%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4096MB Chip DDR3 1600MT/s         | 1         | 1.18%   |
| SK Hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s           | 1         | 1.18%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s         | 1         | 1.18%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s       | 1         | 1.18%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s       | 1         | 1.18%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s      | 1         | 1.18%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s              | 1         | 1.18%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.18%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                  | 1         | 1.18%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                    | 1         | 1.18%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 1         | 1.18%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM 1600MT/s                | 1         | 1.18%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 1         | 1.18%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s           | 1         | 1.18%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s           | 1         | 1.18%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s    | 1         | 1.18%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s           | 1         | 1.18%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s             | 1         | 1.18%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s             | 1         | 1.18%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.18%   |
| Samsung RAM K3QF4F40BM-AGCF 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 1.18%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s       | 1         | 1.18%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s       | 1         | 1.18%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s             | 1         | 1.18%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s              | 1         | 1.18%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.18%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s                    | 1         | 1.18%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 34        | 48.57%  |
| DDR3   | 26        | 37.14%  |
| LPDDR4 | 7         | 10%     |
| LPDDR3 | 3         | 4.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 49        | 70%     |
| DIMM         | 13        | 18.57%  |
| Row Of Chips | 7         | 10%     |
| Chip         | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 44.74%  |
| 4096  | 25        | 32.89%  |
| 16384 | 8         | 10.53%  |
| 2048  | 8         | 10.53%  |
| 32768 | 1         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 22.97%  |
| 2667    | 14        | 18.92%  |
| 3200    | 11        | 14.86%  |
| 2400    | 5         | 6.76%   |
| 4267    | 4         | 5.41%   |
| 2133    | 4         | 5.41%   |
| 1333    | 4         | 5.41%   |
| 3266    | 2         | 2.7%    |
| 1867    | 2         | 2.7%    |
| 1334    | 2         | 2.7%    |
| 1066    | 2         | 2.7%    |
| 4266    | 1         | 1.35%   |
| 3600    | 1         | 1.35%   |
| 2800    | 1         | 1.35%   |
| 2666    | 1         | 1.35%   |
| 2200    | 1         | 1.35%   |
| 1800    | 1         | 1.35%   |
| Unknown | 1         | 1.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 3         | 37.5%   |
| Samsung Electronics             | 2         | 25%     |
| Hewlett-Packard                 | 1         | 12.5%   |
| Dymo-CoStar                     | 1         | 12.5%   |
| cab Produkttechnik GmbH & Co KG | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 2         | 25%     |
| HP Ink Tank 110 series                   | 1         | 12.5%   |
| Dymo-CoStar LabelWriter 450              | 1         | 12.5%   |
| Canon PIXMA MG3600 Series                | 1         | 12.5%   |
| Canon PIXMA MG2500 Series                | 1         | 12.5%   |
| Canon G3000 series                       | 1         | 12.5%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 12.5%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 51        | 18.48%  |
| IMC Networks                           | 32        | 11.59%  |
| Apple                                  | 32        | 11.59%  |
| Realtek Semiconductor                  | 25        | 9.06%   |
| Acer                                   | 19        | 6.88%   |
| Quanta                                 | 14        | 5.07%   |
| Microdia                               | 14        | 5.07%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.35%   |
| Sunplus Innovation Technology          | 10        | 3.62%   |
| Syntek                                 | 8         | 2.9%    |
| Suyin                                  | 8         | 2.9%    |
| Logitech                               | 8         | 2.9%    |
| Alcor Micro                            | 7         | 2.54%   |
| Silicon Motion                         | 5         | 1.81%   |
| Microsoft                              | 4         | 1.45%   |
| Lenovo                                 | 4         | 1.45%   |
| Luxvisions Innotech Limited            | 3         | 1.09%   |
| Ricoh                                  | 2         | 0.72%   |
| KYE Systems (Mouse Systems)            | 2         | 0.72%   |
| Y Media                                | 1         | 0.36%   |
| Unknown                                | 1         | 0.36%   |
| SunplusIT                              | 1         | 0.36%   |
| Sony                                   | 1         | 0.36%   |
| Samsung Electronics                    | 1         | 0.36%   |
| Razer USA                              | 1         | 0.36%   |
| Primax Electronics                     | 1         | 0.36%   |
| Lite-On Technology                     | 1         | 0.36%   |
| kingcome                               | 1         | 0.36%   |
| Jieli Technology                       | 1         | 0.36%   |
| Importek                               | 1         | 0.36%   |
| Google                                 | 1         | 0.36%   |
| Generalplus Technology                 | 1         | 0.36%   |
| Foxconn / Hon Hai                      | 1         | 0.36%   |
| Cubeternet                             | 1         | 0.36%   |
| ANYKA                                  | 1         | 0.36%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                      | 14        | 5%      |
| Chicony Integrated Camera                                                  | 12        | 4.29%   |
| IMC Networks Integrated Camera                                             | 10        | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 3.21%   |
| Syntek Integrated Camera                                                   | 8         | 2.86%   |
| Realtek Integrated_Webcam_HD                                               | 7         | 2.5%    |
| Chicony HD WebCam                                                          | 7         | 2.5%    |
| Apple FaceTime HD Camera                                                   | 6         | 2.14%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 1.79%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 5         | 1.79%   |
| Realtek USB2.0 HD UVC WebCam                                               | 4         | 1.43%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 1.43%   |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 1.43%   |
| Acer Lenovo EasyCamera                                                     | 4         | 1.43%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 3         | 1.07%   |
| Quanta VGA WebCam                                                          | 3         | 1.07%   |
| Quanta HD User Facing                                                      | 3         | 1.07%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 3         | 1.07%   |
| Chicony USB 2.0 Camera                                                     | 3         | 1.07%   |
| Apple FaceTime Camera                                                      | 3         | 1.07%   |
| Alcor Micro SHUNCCM2MP                                                     | 3         | 1.07%   |
| Acer HD Webcam                                                             | 3         | 1.07%   |
| Acer EasyCamera                                                            | 3         | 1.07%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.71%   |
| Sunplus Asus Webcam                                                        | 2         | 0.71%   |
| Realtek USB Camera                                                         | 2         | 0.71%   |
| Realtek Integrated Webcam                                                  | 2         | 0.71%   |
| Realtek Acer 640 x 480 laptop camera                                       | 2         | 0.71%   |
| Quanta HP Webcam                                                           | 2         | 0.71%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.71%   |
| Microdia USB 2.0 Camera                                                    | 2         | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.71%   |
| Logitech BRIO 4K Stream Edition                                            | 2         | 0.71%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.71%   |
| Lenovo Integrated Webcam                                                   | 2         | 0.71%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera                                 | 2         | 0.71%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.71%   |
| IMC Networks EasyCamera                                                    | 2         | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.71%   |
| Chicony HP Wide Vision HD Camera                                           | 2         | 0.71%   |
| Chicony EasyCamera                                                         | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 2         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 2         | 0.71%   |
| Alcor Micro Acer Integrated Webcam                                         | 2         | 0.71%   |
| Acer Integrated Camera                                                     | 2         | 0.71%   |
| Acer HD Camera                                                             | 2         | 0.71%   |
| Y Media USB Camera                                                         | 1         | 0.36%   |
| Unknown 720p HD Camera                                                     | 1         | 0.36%   |
| Suyin UVC HD Webcam                                                        | 1         | 0.36%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.36%   |
| Suyin Integrated_Webcam_HD                                                 | 1         | 0.36%   |
| Suyin HP Integrated Webcam                                                 | 1         | 0.36%   |
| Suyin HD WebCam                                                            | 1         | 0.36%   |
| Suyin Asus Integrated Webcam [CN031B]                                      | 1         | 0.36%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 0.36%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.36%   |
| SunplusIT USB Camera                                                       | 1         | 0.36%   |
| Sunplus TOSHIBA Web Camera - HD                                            | 1         | 0.36%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 34.88%  |
| Validity Sensors           | 10        | 23.26%  |
| LighTuning Technology      | 7         | 16.28%  |
| Upek                       | 5         | 11.63%  |
| Shenzhen Goodix Technology | 4         | 9.3%    |
| Elan Microelectronics      | 2         | 4.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 6         | 13.95%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 11.63%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 4         | 9.3%    |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 9.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor               | 4         | 9.3%    |
| Validity Sensors VFS 5011 fingerprint sensor              | 3         | 6.98%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 4.65%   |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 4.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 4.65%   |
| Validity Sensors VFS491                                   | 1         | 2.33%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 2.33%   |
| LighTuning Fingerprint Sensor                             | 1         | 2.33%   |
| Elan ELAN:Fingerprint                                     | 1         | 2.33%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 35.71%  |
| Alcor Micro           | 5         | 35.71%  |
| Lenovo                | 2         | 14.29%  |
| Gemalto (was Gemplus) | 1         | 7.14%   |
| Chicony Electronics   | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 5         | 35.71%  |
| Lenovo Integrated Smart Card Reader                    | 2         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor         | 2         | 14.29%  |
| Broadcom 58200                                         | 2         | 14.29%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 7.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1         | 7.14%   |
| Broadcom 5880                                          | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 298       | 75.83%  |
| 1     | 76        | 19.34%  |
| 2     | 17        | 4.33%   |
| 4     | 1         | 0.25%   |
| 3     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 37.07%  |
| Net/wireless             | 20        | 17.24%  |
| Multimedia controller    | 13        | 11.21%  |
| Chipcard                 | 13        | 11.21%  |
| Graphics card            | 9         | 7.76%   |
| Camera                   | 4         | 3.45%   |
| Bluetooth                | 3         | 2.59%   |
| Unassigned class         | 2         | 1.72%   |
| Sound                    | 2         | 1.72%   |
| Net/ethernet             | 2         | 1.72%   |
| Card reader              | 2         | 1.72%   |
| Storage/ide              | 1         | 0.86%   |
| Storage                  | 1         | 0.86%   |
| Communication controller | 1         | 0.86%   |

